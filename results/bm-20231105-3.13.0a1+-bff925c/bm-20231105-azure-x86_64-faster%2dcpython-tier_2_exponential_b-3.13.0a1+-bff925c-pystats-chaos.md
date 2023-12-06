
# Pystats results

- benchmark: chaos
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 138,933,200 | 22.0% | 22.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 71,705,600 | 11.4% | 33.4% |  |
| LOAD_FAST_LOAD_FAST | 46,963,940 | 7.4% | 40.9% |  |
| BINARY_OP_MULTIPLY_FLOAT | 30,799,900 | 4.9% | 45.7% |  |
| STORE_FAST | 30,377,120 | 4.8% | 50.6% |  |
| LOAD_CONST | 28,416,380 | 4.5% | 55.1% |  |
| BINARY_OP_ADD_FLOAT | 19,999,920 | 3.2% | 58.2% |  |
| RESUME_CHECK | 19,200,100 | 3.0% | 61.3% |  |
| RETURN_VALUE | 18,800,100 | 3.0% | 64.3% |  |
| STORE_ATTR_INSTANCE_VALUE | 17,605,200 | 2.8% | 67.1% |  |
| BINARY_OP_SUBTRACT_INT | 17,207,580 | 2.7% | 69.8% |  |
| BINARY_SUBSCR_LIST_INT | 16,486,380 | 2.6% | 72.4% |  |
| BINARY_OP | 13,608,920 | 2.2% | 74.6% |  |
| BINARY_OP_ADD_INT | 13,104,160 | 2.1% | 76.6% |  |
| CALL_PY_EXACT_ARGS | 10,399,860 | 1.6% | 78.3% |  |
| ENTER_EXECUTOR | 9,409,420 | 1.5% | 79.8% |  |
| LOAD_GLOBAL_MODULE | 9,389,580 | 1.5% | 81.3% |  |
| POP_JUMP_IF_FALSE | 9,059,940 | 1.4% | 82.7% |  |
| LOAD_GLOBAL_BUILTIN | 8,408,380 | 1.3% | 84.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,000,220 | 1.3% | 85.3% |  |
| RETURN_CONST | 6,000,240 | 1.0% | 86.3% |  |
| POP_JUMP_IF_NOT_NONE | 6,000,000 | 1.0% | 87.2% |  |
| COMPARE_OP | 5,602,760 | 0.9% | 88.1% |  |
| EXIT_INIT_CHECK | 5,600,020 | 0.9% | 89.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 5,600,020 | 0.9% | 89.9% |  |
| STORE_SUBSCR_LIST_INT | 5,199,980 | 0.8% | 90.7% |  |
| BINARY_SUBSCR_TUPLE_INT | 5,199,900 | 0.8% | 91.5% |  |
| CALL_BUILTIN_CLASS | 4,800,040 | 0.8% | 92.3% |  |
| PUSH_NULL | 3,648,940 | 0.6% | 92.9% |  |
| FOR_ITER_RANGE | 3,601,240 | 0.6% | 93.4% |  |
| GET_ITER | 3,600,160 | 0.6% | 94.0% |  |
| COMPARE_OP_INT | 3,459,620 | 0.5% | 94.6% |  |
| CALL_LEN | 3,207,400 | 0.5% | 95.1% |  |
| CALL_BUILTIN_O | 3,058,860 | 0.5% | 95.6% |  |
| POP_JUMP_IF_TRUE | 2,800,560 | 0.4% | 96.0% |  |
| SWAP | 2,792,720 | 0.4% | 96.4% |  |
| BUILD_TUPLE | 2,400,160 | 0.4% | 96.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 2,399,940 | 0.4% | 97.2% |  |
| INTERPRETER_EXIT | 2,000,140 | 0.3% | 97.5% |  |
| LOAD_ATTR_MODULE | 1,789,620 | 0.3% | 97.8% |  |
| CALL | 1,602,840 | 0.3% | 98.1% |  |
| COMPARE_OP_FLOAT | 1,599,920 | 0.3% | 98.3% |  |
| POP_TOP | 1,405,280 | 0.2% | 98.5% |  |
| LOAD_ATTR | 803,220 | 0.1% | 98.7% |  |
| BUILD_LIST | 800,460 | 0.1% | 98.8% |  |
| LIST_APPEND | 800,380 | 0.1% | 98.9% |  |
| LOAD_FAST_AND_CLEAR | 800,080 | 0.1% | 99.0% |  |
| COPY | 800,000 | 0.1% | 99.2% |  |
| IS_OP | 800,000 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 799,980 | 0.1% | 99.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 799,980 | 0.1% | 99.6% |  |
| CALL_ISINSTANCE | 400,140 | 0.1% | 99.6% |  |
| TO_BOOL_BOOL | 400,140 | 0.1% | 99.7% |  |
| UNARY_NEGATIVE | 400,000 | 0.1% | 99.7% |  |
| JUMP_FORWARD | 400,000 | 0.1% | 99.8% |  |
| STORE_FAST_STORE_FAST | 400,000 | 0.1% | 99.9% |  |
| CALL_PY_WITH_DEFAULTS | 399,980 | 0.1% | 99.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 399,980 | 0.1% | 100.0% |  |
| BINARY_SUBSCR | 8,100 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 1,540 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,120 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| RESUME | 220 | 0.0% | 100.0% |  |
| STORE_ATTR | 180 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 160 | 0.0% | 100.0% |  |
| TO_BOOL | 120 | 0.0% | 100.0% |  |
| FOR_ITER | 120 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 80 | 0.0% | 100.0% | 100.0% |
| NOP | 80 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 80 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 80 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 40 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 40 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 65,400,500 | 10.4% | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 41,691,100 | 6.6% | 17.0% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 28,800,000 | 4.6% | 21.6% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 16,800,240 | 2.7% | 24.2% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 15,599,880 | 2.5% | 26.7% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 15,199,960 | 2.4% | 29.1% |
| STORE_FAST LOAD_FAST | 12,800,620 | 2.0% | 31.1% |
| BINARY_OP_ADD_FLOAT LOAD_FAST | 11,999,920 | 1.9% | 33.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 11,200,160 | 1.8% | 34.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 11,059,720 | 1.8% | 36.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,399,860 | 1.6% | 38.2% |
| RESUME_CHECK LOAD_FAST | 10,000,020 | 1.6% | 39.8% |
| RETURN_VALUE STORE_FAST | 9,200,020 | 1.5% | 41.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 8,007,360 | 1.3% | 42.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 7,600,200 | 1.2% | 43.7% |
| LOAD_FAST RETURN_VALUE | 7,324,060 | 1.2% | 44.9% |
| LOAD_FAST LOAD_CONST | 6,800,720 | 1.1% | 46.0% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 6,800,000 | 1.1% | 47.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 6,407,600 | 1.0% | 48.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 6,407,560 | 1.0% | 49.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 6,400,000 | 1.0% | 50.1% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 6,000,060 | 1.0% | 51.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 6,000,000 | 1.0% | 52.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 5,604,860 | 0.9% | 52.9% |
| EXIT_INIT_CHECK RETURN_VALUE | 5,600,020 | 0.9% | 53.8% |
| RETURN_CONST EXIT_INIT_CHECK | 5,600,020 | 0.9% | 54.7% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 5,600,020 | 0.9% | 55.6% |
| BINARY_OP_SUBTRACT_INT BINARY_SUBSCR_LIST_INT | 5,600,000 | 0.9% | 56.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,557,420 | 0.9% | 57.3% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,200,100 | 0.8% | 58.2% |
| BINARY_OP_ADD_FLOAT CALL_ALLOC_AND_ENTER_INIT | 5,199,960 | 0.8% | 59.0% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 5,199,800 | 0.8% | 59.8% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 5,199,680 | 0.8% | 60.6% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 4,800,000 | 0.8% | 61.4% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 4,800,000 | 0.8% | 62.2% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 4,800,000 | 0.8% | 62.9% |
| BINARY_OP_ADD_INT LOAD_FAST | 4,800,000 | 0.8% | 63.7% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_SUBTRACT_INT | 4,400,000 | 0.7% | 64.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 4,399,920 | 0.7% | 65.1% |
| LOAD_CONST BINARY_OP | 4,000,480 | 0.6% | 65.7% |
| BINARY_OP_ADD_INT BINARY_SUBSCR_LIST_INT | 4,000,240 | 0.6% | 66.3% |
| BINARY_OP STORE_FAST | 4,000,100 | 0.6% | 67.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 3,904,080 | 0.6% | 67.6% |
| FOR_ITER_RANGE STORE_FAST | 3,601,240 | 0.6% | 68.2% |
| BINARY_OP LOAD_FAST | 3,600,280 | 0.6% | 68.7% |
| CALL_BUILTIN_CLASS GET_ITER | 3,600,100 | 0.6% | 69.3% |
| BINARY_OP_SUBTRACT_INT LOAD_CONST | 3,599,980 | 0.6% | 69.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,599,800 | 0.6% | 70.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,459,620 | 0.5% | 71.0% |
| PUSH_NULL LOAD_FAST | 3,248,620 | 0.5% | 71.5% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 3,207,360 | 0.5% | 72.0% |
| COMPARE_OP POP_JUMP_IF_FALSE | 3,200,240 | 0.5% | 72.5% |
| LOAD_FAST BINARY_OP_SUBTRACT_INT | 3,200,000 | 0.5% | 73.0% |
| BINARY_SUBSCR_TUPLE_INT COMPARE_OP | 3,200,000 | 0.5% | 73.5% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_ADD_INT | 3,200,000 | 0.5% | 74.1% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_INT | 3,199,920 | 0.5% | 74.6% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 2,830,240 | 0.4% | 75.0% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 2,800,200 | 0.4% | 75.5% |
| GET_ITER FOR_ITER_RANGE | 2,800,040 | 0.4% | 75.9% |
| CALL_LEN LOAD_FAST | 2,800,000 | 0.4% | 76.3% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 2,799,980 | 0.4% | 76.8% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 2,799,960 | 0.4% | 77.2% |
| BINARY_SUBSCR_LIST_INT LOAD_ATTR_METHOD_WITH_VALUES | 2,799,960 | 0.4% | 77.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,799,920 | 0.4% | 78.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 2,618,280 | 0.4% | 78.5% |
| COMPARE_OP POP_JUMP_IF_TRUE | 2,400,480 | 0.4% | 78.9% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 2,400,160 | 0.4% | 79.3% |
| ENTER_EXECUTOR CALL_PY_EXACT_ARGS | 2,400,000 | 0.4% | 79.7% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 2,400,000 | 0.4% | 80.1% |
| BINARY_OP_ADD_INT CALL_BUILTIN_CLASS | 2,400,000 | 0.4% | 80.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 2,400,000 | 0.4% | 80.8% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 2,259,040 | 0.4% | 81.2% |
| BUILD_TUPLE RETURN_VALUE | 2,007,440 | 0.3% | 81.5% |
| LOAD_FAST BINARY_OP | 2,000,420 | 0.3% | 81.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,000,320 | 0.3% | 82.1% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 2,000,120 | 0.3% | 82.4% |
| CACHE RESUME_CHECK | 2,000,060 | 0.3% | 82.8% |
| RETURN_VALUE INTERPRETER_EXIT | 2,000,000 | 0.3% | 83.1% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 2,000,000 | 0.3% | 83.4% |
| BINARY_SUBSCR_LIST_INT BUILD_TUPLE | 2,000,000 | 0.3% | 83.7% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 2,000,000 | 0.3% | 84.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_BUILTIN | 2,000,000 | 0.3% | 84.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,999,920 | 0.3% | 84.7% |
| CALL_BUILTIN_O STORE_FAST | 1,858,880 | 0.3% | 85.0% |
| LOAD_FAST CALL_BUILTIN_O | 1,858,820 | 0.3% | 85.3% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,789,560 | 0.3% | 85.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,789,480 | 0.3% | 85.8% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 1,686,180 | 0.3% | 86.1% |
| BINARY_SUBSCR_LIST_INT COMPARE_OP | 1,600,480 | 0.3% | 86.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,600,300 | 0.3% | 86.6% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 1,600,240 | 0.3% | 86.9% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP | 1,600,140 | 0.3% | 87.1% |
| ENTER_EXECUTOR LOAD_ATTR_INSTANCE_VALUE | 1,600,000 | 0.3% | 87.4% |
| LOAD_FAST BINARY_OP_ADD_INT | 1,600,000 | 0.3% | 87.6% |
| BINARY_OP_SUBTRACT_INT BINARY_OP | 1,600,000 | 0.3% | 87.9% |
| BINARY_OP_SUBTRACT_INT LOAD_FAST | 1,600,000 | 0.3% | 88.1% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 1,600,000 | 0.3% | 88.4% |
| BINARY_OP_SUBTRACT_FLOAT LOAD_FAST | 1,599,920 | 0.3% | 88.6% |
| COMPARE_OP_FLOAT POP_JUMP_IF_FALSE | 1,599,920 | 0.3% | 88.9% |
| BINARY_SUBSCR_TUPLE_INT BINARY_SUBSCR_LIST_INT | 1,599,840 | 0.3% | 89.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,000,060 | 100.0% |
| RESUME | 80 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,640 | 94.3% |
| BINARY_SUBSCR | 220 | 2.7% |
| LOAD_FAST | 120 | 1.5% |
| BINARY_SUBSCR_TUPLE_INT | 80 | 1.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 7,460 | 92.1% |
| BINARY_SUBSCR | 220 | 2.7% |
| BINARY_SUBSCR_LIST_INT | 160 | 2.0% |
| BINARY_SUBSCR_TUPLE_INT | 100 | 1.2% |
| BINARY_OP | 80 | 1.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,600,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,600,020 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 3,600,100 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 2,800,040 | 77.8% |
| LOAD_FAST_AND_CLEAR | 800,080 | 22.2% |
| FOR_ITER | 40 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,000,000 | 100.0% |
| RETURN_CONST | 140 | 0.0% |


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
| STORE_FAST | 612,400 | 43.6% |
| RETURN_CONST | 400,080 | 28.5% |
| SWAP | 392,560 | 27.9% |
| CALL | 160 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,012,480 | 72.0% |
| RETURN_VALUE | 392,560 | 27.9% |
| NOP | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,789,560 | 49.0% |
| LOAD_FAST | 1,059,180 | 29.0% |
| BINARY_SUBSCR_LIST_INT | 799,960 | 21.9% |
| LOAD_ATTR | 120 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,248,620 | 89.0% |
| LOAD_GLOBAL_BUILTIN | 399,960 | 11.0% |
| CALL | 320 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,324,060 | 39.0% |
| EXIT_INIT_CHECK | 5,600,020 | 29.8% |
| BUILD_TUPLE | 2,007,440 | 10.7% |
| CALL_BUILTIN_O | 1,199,980 | 6.4% |
| RETURN_VALUE | 800,000 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,200,020 | 48.9% |
| LOAD_FAST_LOAD_FAST | 4,800,000 | 25.5% |
| INTERPRETER_EXIT | 2,000,000 | 10.6% |
| RETURN_VALUE | 800,000 | 4.3% |
| BINARY_OP | 800,000 | 4.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 20 | 50.0% |
| BINARY_OP_SUBTRACT_INT | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20 | 50.0% |
| STORE_SUBSCR_LIST_INT | 20 | 50.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 60 | 50.0% |
| LOAD_FAST | 40 | 33.3% |
| CALL | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 60 | 50.0% |
| POP_JUMP_IF_FALSE | 20 | 16.7% |
| POP_JUMP_IF_TRUE | 20 | 16.7% |
| TO_BOOL_NONE | 20 | 16.7% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 399,980 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400,000 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,000,480 | 29.4% |
| LOAD_FAST | 2,000,420 | 14.7% |
| LOAD_FAST_LOAD_FAST | 2,000,120 | 14.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,600,140 | 11.8% |
| BINARY_OP_SUBTRACT_INT | 1,600,000 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,000,100 | 29.4% |
| LOAD_FAST | 3,600,280 | 26.5% |
| BINARY_OP_ADD_FLOAT | 2,400,160 | 17.6% |
| LOAD_FAST_LOAD_FAST | 2,000,000 | 14.7% |
| BINARY_OP | 807,280 | 5.9% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 800,080 | 100.0% |
| LOAD_CONST | 380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 800,080 | 100.0% |
| LOAD_FAST | 380 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 2,000,000 | 83.3% |
| RETURN_VALUE | 400,000 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,007,440 | 83.6% |
| SWAP | 392,560 | 16.4% |
| CALL_ISINSTANCE | 120 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400,500 | 25.0% |
| BINARY_OP_ADD_FLOAT | 400,020 | 25.0% |
| BINARY_OP_ADD_INT | 399,980 | 25.0% |
| ENTER_EXECUTOR | 210,480 | 13.1% |
| BINARY_SUBSCR_LIST_INT | 182,060 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 800,260 | 49.9% |
| RESUME_CHECK | 800,040 | 49.9% |
| CALL | 1,380 | 0.1% |
| POP_TOP | 160 | 0.0% |
| CALL_PY_EXACT_ARGS | 140 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 3,200,000 | 57.1% |
| BINARY_SUBSCR_LIST_INT | 1,600,480 | 28.6% |
| LOAD_CONST | 400,120 | 7.1% |
| LOAD_FAST | 400,000 | 7.1% |
| COMPARE_OP | 1,760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,200,240 | 57.1% |
| POP_JUMP_IF_TRUE | 2,400,480 | 42.8% |
| COMPARE_OP | 1,760 | 0.0% |
| COMPARE_OP_INT | 200 | 0.0% |
| COMPARE_OP_FLOAT | 80 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 799,920 | 100.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 50.0% |
| CALL_FUNCTION_EX | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 140 | 87.5% |
| RESUME | 20 | 12.5% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 5,199,680 | 55.3% |
| ENTER_EXECUTOR | 2,830,240 | 30.1% |
| LIST_APPEND | 800,060 | 8.5% |
| STORE_FAST | 303,360 | 3.2% |
| POP_JUMP_IF_TRUE | 187,580 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,830,240 | 30.1% |
| CALL_PY_EXACT_ARGS | 2,400,000 | 25.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,600,000 | 17.0% |
| LOAD_FAST | 800,080 | 8.5% |
| STORE_FAST | 800,080 | 8.5% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 60 | 50.0% |
| GET_ITER | 40 | 33.3% |
| SWAP | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| FOR_ITER_RANGE | 60 | 50.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 799,980 | 100.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 800,000 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 320 | 20.8% |
| POP_JUMP_IF_FALSE | 320 | 20.8% |
| STORE_FAST | 320 | 20.8% |
| STORE_SUBSCR_LIST_INT | 300 | 19.5% |
| POP_JUMP_IF_TRUE | 260 | 16.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 1,080 | 70.1% |
| LOAD_FAST | 300 | 19.5% |
| ENTER_EXECUTOR | 100 | 6.5% |
| FOR_ITER | 60 | 3.9% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 399,980 | 100.0% |
| STORE_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400,000 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 800,000 | 100.0% |
| BINARY_OP | 380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 800,060 | 100.0% |
| JUMP_BACKWARD | 320 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 802,360 | 99.9% |
| LOAD_ATTR | 380 | 0.0% |
| LOAD_GLOBAL | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 800,020 | 99.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,100 | 0.1% |
| LOAD_FAST | 620 | 0.1% |
| LOAD_ATTR | 380 | 0.0% |
| BINARY_OP | 300 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,007,360 | 28.2% |
| LOAD_FAST | 6,800,720 | 23.9% |
| LOAD_FAST_LOAD_FAST | 6,800,000 | 23.9% |
| BINARY_OP_SUBTRACT_INT | 3,599,980 | 12.7% |
| LOAD_GLOBAL_BUILTIN | 800,080 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 7,600,200 | 26.7% |
| BINARY_OP_SUBTRACT_INT | 6,407,560 | 22.5% |
| BINARY_SUBSCR_TUPLE_INT | 5,199,800 | 18.3% |
| BINARY_OP | 4,000,480 | 14.1% |
| COMPARE_OP_INT | 800,120 | 2.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 33.3% |
| STORE_FAST | 80 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 80 | 33.3% |
| LOAD_FAST | 80 | 33.3% |
| STORE_FAST | 80 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 41,691,100 | 30.0% |
| BINARY_OP_MULTIPLY_FLOAT | 15,199,960 | 10.9% |
| STORE_FAST | 12,800,620 | 9.2% |
| BINARY_OP_ADD_FLOAT | 11,999,920 | 8.6% |
| RESUME_CHECK | 10,000,020 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 65,400,500 | 47.1% |
| BINARY_OP_MULTIPLY_FLOAT | 28,800,000 | 20.7% |
| RETURN_VALUE | 7,324,060 | 5.3% |
| LOAD_CONST | 6,800,720 | 4.9% |
| POP_JUMP_IF_NOT_NONE | 6,000,000 | 4.3% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 800,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 800,080 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 11,200,160 | 23.8% |
| STORE_FAST | 11,059,720 | 23.5% |
| RESUME_CHECK | 6,000,060 | 12.8% |
| RETURN_VALUE | 4,800,000 | 10.2% |
| BINARY_SUBSCR_LIST_INT | 2,799,980 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 16,800,240 | 35.8% |
| LOAD_CONST | 6,800,000 | 14.5% |
| STORE_SUBSCR_LIST_INT | 4,800,000 | 10.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,904,080 | 8.3% |
| BINARY_OP_SUBTRACT_INT | 3,199,920 | 6.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 17.9% |
| LOAD_FAST | 160 | 14.3% |
| RESUME | 140 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 140 | 12.5% |
| RESUME_CHECK | 140 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 420 | 37.5% |
| LOAD_GLOBAL_MODULE | 260 | 23.2% |
| LOAD_FAST | 240 | 21.4% |
| LOAD_ATTR | 140 | 12.5% |
| CALL | 20 | 1.8% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 20 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 3,459,620 | 38.2% |
| COMPARE_OP | 3,200,240 | 35.3% |
| COMPARE_OP_FLOAT | 1,599,920 | 17.7% |
| IS_OP | 800,000 | 8.8% |
| TO_BOOL_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,557,420 | 61.3% |
| LOAD_FAST_LOAD_FAST | 2,618,280 | 28.9% |
| LOAD_CONST | 400,000 | 4.4% |
| RETURN_CONST | 395,360 | 4.4% |
| ENTER_EXECUTOR | 88,400 | 1.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,800,000 | 80.0% |
| LOAD_FAST | 1,200,000 | 20.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 2,400,480 | 85.7% |
| TO_BOOL_BOOL | 400,060 | 14.3% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,600,240 | 57.1% |
| LOAD_FAST | 612,400 | 21.9% |
| LOAD_GLOBAL_MODULE | 399,960 | 14.3% |
| ENTER_EXECUTOR | 187,580 | 6.7% |
| JUMP_BACKWARD | 260 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,604,860 | 93.4% |
| POP_JUMP_IF_FALSE | 395,360 | 6.6% |
| STORE_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXIT_INIT_CHECK | 5,600,020 | 93.3% |
| POP_TOP | 400,080 | 6.7% |
| INTERPRETER_EXIT | 140 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100 | 55.6% |
| SWAP | 80 | 44.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 100 | 55.6% |
| LOAD_FAST | 40 | 22.2% |
| JUMP_FORWARD | 20 | 11.1% |
| RETURN_CONST | 20 | 11.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,200,020 | 30.3% |
| BINARY_OP | 4,000,100 | 13.2% |
| FOR_ITER_RANGE | 3,601,240 | 11.9% |
| BINARY_OP_SUBTRACT_INT | 2,800,200 | 9.2% |
| CALL_BUILTIN_O | 1,858,880 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,800,620 | 42.1% |
| LOAD_FAST_LOAD_FAST | 11,059,720 | 36.4% |
| LOAD_GLOBAL_BUILTIN | 4,399,920 | 14.5% |
| STORE_FAST | 800,080 | 2.6% |
| POP_TOP | 612,400 | 2.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 399,980 | 100.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 400,000 | 100.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 800,080 | 28.6% |
| LOAD_FAST_AND_CLEAR | 800,080 | 28.6% |
| BINARY_OP_ADD_FLOAT | 799,960 | 28.6% |
| BUILD_TUPLE | 392,560 | 14.1% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 800,080 | 28.6% |
| FOR_ITER_RANGE | 800,060 | 28.6% |
| STORE_ATTR_INSTANCE_VALUE | 799,920 | 28.6% |
| POP_TOP | 392,560 | 14.1% |
| STORE_ATTR | 80 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 120 | 54.5% |
| CACHE | 80 | 36.4% |
| COPY_FREE_VARS | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 140 | 63.6% |
| LOAD_FAST | 60 | 27.3% |
| LOAD_FAST_LOAD_FAST | 20 | 9.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 15,599,880 | 78.0% |
| BINARY_OP | 2,400,160 | 12.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,199,960 | 6.0% |
| LOAD_CONST | 799,920 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,999,920 | 60.0% |
| CALL_ALLOC_AND_ENTER_INIT | 5,199,960 | 26.0% |
| CALL_BUILTIN_O | 1,199,960 | 6.0% |
| SWAP | 799,960 | 4.0% |
| CALL | 400,020 | 2.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,600,200 | 58.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,200,000 | 24.4% |
| LOAD_FAST | 1,600,000 | 12.2% |
| BINARY_SUBSCR_LIST_INT | 703,900 | 5.4% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800,000 | 36.6% |
| BINARY_SUBSCR_LIST_INT | 4,000,240 | 30.5% |
| CALL_BUILTIN_CLASS | 2,400,000 | 18.3% |
| LOAD_CONST | 800,000 | 6.1% |
| COMPARE_OP_INT | 400,260 | 3.1% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,800,000 | 93.5% |
| BINARY_OP_SUBTRACT_FLOAT | 799,920 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 799,920 | 2.6% |
| LOAD_FAST_LOAD_FAST | 399,960 | 1.3% |
| BINARY_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 15,599,880 | 50.6% |
| LOAD_FAST | 15,199,960 | 49.4% |
| BINARY_OP | 60 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,599,840 | 66.7% |
| LOAD_CONST | 799,920 | 33.3% |
| BINARY_OP | 140 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,599,920 | 66.7% |
| BINARY_OP_MULTIPLY_FLOAT | 799,920 | 33.3% |
| STORE_FAST | 60 | 0.0% |
| BINARY_OP | 40 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,407,560 | 37.2% |
| LOAD_ATTR_INSTANCE_VALUE | 4,400,000 | 25.6% |
| LOAD_FAST | 3,200,000 | 18.6% |
| LOAD_FAST_LOAD_FAST | 3,199,920 | 18.6% |
| BINARY_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 5,600,000 | 32.5% |
| LOAD_CONST | 3,599,980 | 20.9% |
| STORE_FAST | 2,800,200 | 16.3% |
| BINARY_OP | 1,600,000 | 9.3% |
| LOAD_FAST | 1,600,000 | 9.3% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 5,600,000 | 34.0% |
| BINARY_OP_ADD_INT | 4,000,240 | 24.3% |
| LOAD_FAST_LOAD_FAST | 2,799,960 | 17.0% |
| LOAD_FAST | 1,686,180 | 10.2% |
| BINARY_SUBSCR_TUPLE_INT | 1,599,840 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,799,980 | 17.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,799,960 | 17.0% |
| BUILD_TUPLE | 2,000,000 | 12.1% |
| LOAD_FAST | 2,000,000 | 12.1% |
| COMPARE_OP | 1,600,480 | 9.7% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,199,800 | 100.0% |
| BINARY_SUBSCR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,200,000 | 61.5% |
| BINARY_SUBSCR_LIST_INT | 1,599,840 | 30.8% |
| BINARY_OP | 399,980 | 7.7% |
| BINARY_SUBSCR | 80 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 5,199,960 | 92.9% |
| BINARY_OP | 399,960 | 7.1% |
| CALL | 60 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,600,020 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,400,000 | 50.0% |
| LOAD_FAST | 800,000 | 16.7% |
| BINARY_OP_SUBTRACT_INT | 800,000 | 16.7% |
| CALL_LEN | 399,960 | 8.3% |
| LOAD_ATTR_INSTANCE_VALUE | 399,960 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,600,100 | 75.0% |
| STORE_FAST | 799,960 | 16.7% |
| LOAD_CONST | 399,980 | 8.3% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,858,820 | 60.8% |
| BINARY_OP_ADD_FLOAT | 1,199,960 | 39.2% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,858,880 | 60.8% |
| RETURN_VALUE | 1,199,980 | 39.2% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 399,960 | 100.0% |
| BUILD_TUPLE | 120 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 400,080 | 100.0% |
| TO_BOOL | 60 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,207,360 | 100.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,800,000 | 87.3% |
| CALL_BUILTIN_CLASS | 399,960 | 12.5% |
| LOAD_CONST | 7,420 | 0.2% |
| CALL | 20 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 75.0% |
| CALL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 80 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 799,960 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 799,980 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,599,800 | 34.6% |
| ENTER_EXECUTOR | 2,400,000 | 23.1% |
| LOAD_FAST_LOAD_FAST | 2,400,000 | 23.1% |
| LOAD_FAST | 1,999,920 | 19.2% |
| CALL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,399,860 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 399,620 | 99.9% |
| LOAD_FAST | 340 | 0.1% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 399,980 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 75.0% |
| CALL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60 | 75.0% |
| LOAD_GLOBAL | 20 | 25.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,599,840 | 100.0% |
| COMPARE_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,599,920 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,259,040 | 65.3% |
| LOAD_CONST | 800,120 | 23.1% |
| BINARY_OP_ADD_INT | 400,260 | 11.6% |
| COMPARE_OP | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,459,620 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,800,040 | 77.8% |
| SWAP | 800,060 | 22.2% |
| JUMP_BACKWARD | 1,080 | 0.0% |
| FOR_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,601,240 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 65,400,500 | 91.2% |
| LOAD_FAST_LOAD_FAST | 3,904,080 | 5.4% |
| ENTER_EXECUTOR | 1,600,000 | 2.2% |
| COPY | 799,920 | 1.1% |
| LOAD_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,691,100 | 58.1% |
| LOAD_CONST | 8,007,360 | 11.2% |
| BINARY_OP_SUBTRACT_INT | 4,400,000 | 6.1% |
| CALL_LEN | 3,207,360 | 4.5% |
| BINARY_OP_ADD_INT | 3,200,000 | 4.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 799,960 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 799,960 | 100.0% |
| CALL | 20 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,200,100 | 65.0% |
| BINARY_SUBSCR_LIST_INT | 2,799,960 | 35.0% |
| LOAD_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,599,800 | 45.0% |
| LOAD_FAST_LOAD_FAST | 2,400,000 | 30.0% |
| LOAD_FAST | 2,000,320 | 25.0% |
| CALL | 100 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,789,480 | 100.0% |
| LOAD_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,789,560 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,399,920 | 52.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,000,000 | 23.8% |
| BINARY_OP_SUBTRACT_INT | 800,000 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 400,320 | 4.8% |
| PUSH_NULL | 399,960 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,407,600 | 76.2% |
| LOAD_CONST | 800,080 | 9.5% |
| LOAD_FAST_LOAD_FAST | 800,000 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 400,320 | 4.8% |
| BUILD_TUPLE | 160 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 4,800,000 | 51.1% |
| RESUME_CHECK | 2,799,920 | 29.8% |
| LOAD_FAST | 1,381,960 | 14.7% |
| POP_JUMP_IF_TRUE | 399,960 | 4.3% |
| BINARY_OP_SUBTRACT_INT | 7,400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,400,000 | 68.2% |
| LOAD_ATTR_MODULE | 1,789,480 | 19.1% |
| IS_OP | 799,980 | 8.5% |
| CALL_ISINSTANCE | 399,960 | 4.3% |
| LOAD_ATTR | 140 | 0.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 75.0% |
| LOAD_SUPER_ATTR | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,399,860 | 54.2% |
| CALL_ALLOC_AND_ENTER_INIT | 5,600,020 | 29.2% |
| CACHE | 2,000,060 | 10.4% |
| CALL | 800,040 | 4.2% |
| CALL_PY_WITH_DEFAULTS | 399,980 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,000,020 | 52.1% |
| LOAD_FAST_LOAD_FAST | 6,000,060 | 31.3% |
| LOAD_GLOBAL_MODULE | 2,799,920 | 14.6% |
| LOAD_GLOBAL_BUILTIN | 399,960 | 2.1% |
| LOAD_GLOBAL | 140 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 16,800,240 | 95.4% |
| SWAP | 799,920 | 4.5% |
| LOAD_FAST | 4,940 | 0.0% |
| STORE_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,200,160 | 63.6% |
| RETURN_CONST | 5,604,860 | 31.8% |
| LOAD_FAST | 400,200 | 2.3% |
| JUMP_FORWARD | 399,980 | 2.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,800,000 | 92.3% |
| BINARY_OP_SUBTRACT_INT | 399,960 | 7.7% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,199,680 | 100.0% |
| JUMP_BACKWARD | 300 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 400,080 | 100.0% |
| TO_BOOL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 400,060 | 100.0% |
| POP_JUMP_IF_FALSE | 80 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| TO_BOOL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 399,960 | 100.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 399,980 | 100.0% |


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
|     deferred | 13,601,180 | 14.0% |
|          hit | 83,511,500 | 86.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 640 | 8.3% |
| Failure | 7,100 | 91.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 2,020 | 28.5% |
| true divide float | 1,680 | 23.7% |
| power | 1,440 | 20.3% |
| true divide different types | 440 | 6.2% |
| subtract different types | 400 | 5.6% |
| add different types | 280 | 3.9% |
| add other | 280 | 3.9% |
| subtract other | 280 | 3.9% |
| true divide other | 280 | 3.9% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,700 | 0.0% |
|          hit | 21,686,280 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 65.0% |
| Failure | 140 | 35.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 140 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,600,900 | 5.3% |
|          hit | 28,666,360 | 94.7% |
|         miss | 80 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 580 | 29.9% |
| Failure | 1,360 | 70.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bound method | 720 | 52.9% |
| other | 580 | 42.6% |
| cfunc noargs | 60 | 4.4% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,600,720 | 52.5% |
|          hit | 5,059,540 | 47.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 13.7% |
| Failure | 1,760 | 86.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 1,760 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 0.0% |
|          hit | 3,601,240 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 801,420 | 1.0% |
|          hit | 82,295,420 | 99.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,420 | 78.9% |
| Failure | 380 | 21.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 380 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 440 | 0.0% |
|          hit | 17,797,960 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 680 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 80 | 80.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 80 | 0.0% |
|          hit | 17,605,200 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 5,199,980 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 400,200 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 399,980 | 100.0% |

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
| Basic | 305,551,060 | 48.5% |
| Not specialized | 39,487,980 | 6.3% |
| Specialized hits | 285,423,840 | 45.3% |
| Specialized misses | 80 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 13,601,180 | 62.9% |
| COMPARE_OP | 5,600,720 | 25.9% |
| CALL | 1,600,900 | 7.4% |
| LOAD_ATTR | 801,420 | 3.7% |
| BINARY_SUBSCR | 7,700 | 0.0% |
| LOAD_GLOBAL | 440 | 0.0% |
| STORE_ATTR | 80 | 0.0% |
| FOR_ITER | 60 | 0.0% |
| TO_BOOL | 40 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 80 | 100.0% |
| CACHE | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| UNARY_NEGATIVE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 2,000,140 | 10.4% |
| Calls to Python functions inlined | 17,200,180 | 89.6% |
| Calls via PyEval_EvalFrame (total) | 2,000,140 | 10.4% |
| Calls via PyEval_EvalFrame (vector) | 2,000,140 | 10.4% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 2,000,140 | 10.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 1,200,000 | 6.2% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 21,999,880 | 114.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 67,626,760 | 74.8% |
| Frees to freelist | 67,628,380 |  |
| Allocations | 22,836,460 | 25.2% |
| Allocations to 512 bytes | 22,815,940 | 25.2% |
| Allocations to 4 kbytes | 20,520 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 23,638,544 |  |
| New values | 60 |  |
| Interpreter increfs | 384,030,020 | 97.5% |
| Interpreter decrefs | 448,032,600 | 93.6% |
| Increfs | 10,003,860 | 2.5% |
| Decrefs | 30,829,965 | 6.4% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 803,070 |  |
| Method cache misses | 190 |  |
| Method cache collisions | 199 |  |
| Method cache dunder hits | 2,000,380 |  |
| Method cache dunder misses | 60 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 2,280 | 1,558,160 |
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
| Trace stack underflow | 40 | 40.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 9,409,420 |  |
| Uops executed | 548,483,640 | 58.29 |

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
| <= 32 | 60 | 60.0% |
| <= 64 | 40 | 40.0% |


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
| <= 16 | 20 | 20.0% |
| <= 32 | 40 | 40.0% |
| <= 64 | 40 | 40.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 3,207,520 | 34.1% |
| <= 16 | 543,080 | 5.8% |
| <= 32 | 85,460 | 0.9% |
| <= 64 | 773,280 | 8.2% |
| <= 128 | 4,800,000 | 51.0% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 132,923,640 | 24.2% | 24.2% |  |
| LOAD_FAST | 108,440,680 | 19.8% | 44.0% |  |
| _GUARD_BOTH_INT | 48,058,740 | 8.8% | 52.8% |  |
| _BINARY_OP_SUBTRACT_INT | 28,800,000 | 5.3% | 58.0% |  |
| STORE_FAST | 28,009,520 | 5.1% | 63.1% |  |
| _BINARY_OP_ADD_INT | 19,258,740 | 3.5% | 66.6% |  |
| _GUARD_TYPE_VERSION | 17,231,640 | 3.1% | 69.8% |  |
| BINARY_SUBSCR_LIST_INT | 16,832,020 | 3.1% | 72.8% |  |
| _BINARY_OP | 16,020,100 | 2.9% | 75.8% |  |
| LOAD_CONST | 14,982,900 | 2.7% | 78.5% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 14,432,020 | 2.6% | 81.1% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 14,432,020 | 2.6% | 83.8% |  |
| _POP_JUMP_IF_TRUE | 13,429,520 | 2.4% | 86.2% |  |
| _ITER_CHECK_RANGE | 13,286,060 | 2.4% | 88.6% |  |
| _IS_ITER_EXHAUSTED_RANGE | 13,286,060 | 2.4% | 91.1% |  |
| _EXIT_TRACE | 9,409,420 | 1.7% | 92.8% |  |
| _ITER_NEXT_RANGE | 9,278,460 | 1.7% | 94.5% |  |
| POP_TOP | 4,195,200 | 0.8% | 95.2% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 2,799,620 | 0.5% | 95.7% |  |
| _GUARD_KEYS_VERSION | 2,799,620 | 0.5% | 96.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 2,799,620 | 0.5% | 96.8% |  |
| LIST_APPEND | 2,420,100 | 0.4% | 97.2% |  |
| _JUMP_TO_TOP | 2,420,100 | 0.4% | 97.6% |  |
| _GUARD_GLOBALS_VERSION | 1,810,480 | 0.3% | 98.0% |  |
| _POP_JUMP_IF_FALSE | 1,717,480 | 0.3% | 98.3% |  |
| GET_ITER | 1,600,000 | 0.3% | 98.6% |  |
| CALL_BUILTIN_CLASS | 1,600,000 | 0.3% | 98.9% |  |
| _GUARD_BUILTINS_VERSION | 1,600,000 | 0.3% | 99.2% |  |
| _LOAD_GLOBAL_BUILTINS | 1,600,000 | 0.3% | 99.5% |  |
| _COMPARE_OP | 1,125,600 | 0.2% | 99.7% |  |
| COMPARE_OP_INT | 735,340 | 0.1% | 99.8% |  |
| PUSH_NULL | 353,940 | 0.1% | 99.9% |  |
| _LOAD_GLOBAL_MODULE | 210,480 | 0.0% | 99.9% |  |
| _CHECK_ATTR_MODULE | 210,480 | 0.0% | 99.9% |  |
| _LOAD_ATTR_MODULE | 210,480 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 143,460 | 0.0% | 100.0% |  |
| BUILD_LIST | 20,100 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 20 |
| CALL_PY_WITH_DEFAULTS | 20 |


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
