
# Pystats results

- benchmark: python_startup_no_site
- fork: brandtbucher
- ref: justin
- commit hash: 898dcc2
- commit date: 2023-10-10T14:45:03+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 61,600 | 21.5% | 21.5% |  |
| LOAD_CONST | 18,400 | 6.4% | 28.0% |  |
| STORE_FAST | 14,800 | 5.2% | 33.1% |  |
| POP_JUMP_IF_FALSE | 12,800 | 4.5% | 37.6% |  |
| LOAD_GLOBAL_MODULE | 11,780 | 4.1% | 41.7% |  |
| RESUME_CHECK | 9,400 | 3.3% | 45.0% |  |
| LOAD_GLOBAL_BUILTIN | 8,840 | 3.1% | 48.1% | 18.6% |
| LOAD_ATTR_INSTANCE_VALUE | 7,800 | 2.7% | 50.8% |  |
| LOAD_FAST_LOAD_FAST | 7,400 | 2.6% | 53.4% |  |
| LOAD_ATTR_MODULE | 7,180 | 2.5% | 55.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 6,600 | 2.3% | 58.2% |  |
| POP_TOP | 6,600 | 2.3% | 60.5% |  |
| CALL | 5,960 | 2.1% | 62.6% |  |
| TO_BOOL_BOOL | 5,600 | 2.0% | 64.6% |  |
| PUSH_NULL | 5,600 | 2.0% | 66.5% |  |
| RETURN_VALUE | 5,400 | 1.9% | 68.4% |  |
| RETURN_CONST | 4,200 | 1.5% | 69.9% |  |
| POP_JUMP_IF_NOT_NONE | 4,200 | 1.5% | 71.3% |  |
| LOAD_ATTR | 3,820 | 1.3% | 72.7% |  |
| COMPARE_OP_INT | 3,800 | 1.3% | 74.0% |  |
| NOP | 3,600 | 1.3% | 75.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,200 | 1.1% | 76.4% | 12.5% |
| INTERPRETER_EXIT | 3,200 | 1.1% | 77.5% |  |
| CALL_PY_EXACT_ARGS | 3,200 | 1.1% | 78.6% |  |
| LOAD_DEREF | 3,000 | 1.0% | 79.7% |  |
| CALL_BUILTIN_FAST | 2,600 | 0.9% | 80.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,400 | 0.8% | 81.4% |  |
| TO_BOOL | 2,300 | 0.8% | 82.2% |  |
| POP_JUMP_IF_TRUE | 2,200 | 0.8% | 83.0% |  |
| POP_JUMP_IF_NONE | 2,200 | 0.8% | 83.7% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,200 | 0.8% | 84.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,800 | 0.6% | 85.1% |  |
| CALL_ISINSTANCE | 1,800 | 0.6% | 85.8% |  |
| BUILD_TUPLE | 1,800 | 0.6% | 86.4% |  |
| STORE_FAST_STORE_FAST | 1,600 | 0.6% | 87.0% |  |
| BINARY_OP | 1,580 | 0.6% | 87.5% |  |
| LOAD_GLOBAL | 1,440 | 0.5% | 88.0% |  |
| STORE_ATTR | 1,360 | 0.5% | 88.5% |  |
| JUMP_FORWARD | 1,200 | 0.4% | 88.9% |  |
| DELETE_ATTR | 1,200 | 0.4% | 89.3% |  |
| CALL_FUNCTION_EX | 1,200 | 0.4% | 89.7% |  |
| BUILD_LIST | 1,200 | 0.4% | 90.2% |  |
| TO_BOOL_STR | 1,000 | 0.3% | 90.5% | 20.0% |
| TO_BOOL_NONE | 1,000 | 0.3% | 90.9% |  |
| MAKE_CELL | 1,000 | 0.3% | 91.2% |  |
| COPY | 1,000 | 0.3% | 91.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,000 | 0.3% | 91.9% |  |
| CALL_BUILTIN_CLASS | 1,000 | 0.3% | 92.3% |  |
| BINARY_SLICE | 1,000 | 0.3% | 92.6% |  |
| TO_BOOL_INT | 800 | 0.3% | 92.9% |  |
| DICT_MERGE | 800 | 0.3% | 93.2% |  |
| COPY_FREE_VARS | 800 | 0.3% | 93.4% |  |
| CALL_PY_WITH_DEFAULTS | 800 | 0.3% | 93.7% |  |
| CALL_METHOD_DESCRIPTOR_O | 800 | 0.3% | 94.0% |  |
| CALL_LEN | 800 | 0.3% | 94.3% |  |
| CALL_KW | 800 | 0.3% | 94.6% |  |
| BUILD_MAP | 800 | 0.3% | 94.8% |  |
| BEFORE_WITH | 800 | 0.3% | 95.1% |  |
| COMPARE_OP | 620 | 0.2% | 95.3% |  |
| SWAP | 600 | 0.2% | 95.5% |  |
| STORE_DEREF | 600 | 0.2% | 95.8% |  |
| GET_ITER | 600 | 0.2% | 96.0% |  |
| EXTENDED_ARG | 600 | 0.2% | 96.2% |  |
| EXIT_INIT_CHECK | 600 | 0.2% | 96.4% |  |
| COMPARE_OP_STR | 600 | 0.2% | 96.6% | 33.3% |
| CALL_ALLOC_AND_ENTER_INIT | 600 | 0.2% | 96.8% |  |
| BINARY_SUBSCR_LIST_INT | 600 | 0.2% | 97.0% |  |
| BINARY_OP_ADD_INT | 600 | 0.2% | 97.2% |  |
| FOR_ITER | 440 | 0.2% | 97.4% |  |
| YIELD_VALUE | 400 | 0.1% | 97.5% |  |
| SET_FUNCTION_ATTRIBUTE | 400 | 0.1% | 97.7% |  |
| RETURN_GENERATOR | 400 | 0.1% | 97.8% |  |
| PUSH_EXC_INFO | 400 | 0.1% | 97.9% |  |
| POP_EXCEPT | 400 | 0.1% | 98.1% |  |
| MAKE_FUNCTION | 400 | 0.1% | 98.2% |  |
| FOR_ITER_LIST | 400 | 0.1% | 98.4% |  |
| CHECK_EXC_MATCH | 400 | 0.1% | 98.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 400 | 0.1% | 98.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 400 | 0.1% | 98.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 400 | 0.1% | 98.9% | 100.0% |
| BINARY_SUBSCR_TUPLE_INT | 400 | 0.1% | 99.1% |  |
| UNPACK_SEQUENCE_TUPLE | 200 | 0.1% | 99.1% |  |
| TO_BOOL_ALWAYS_TRUE | 200 | 0.1% | 99.2% |  |
| STORE_SUBSCR_DICT | 200 | 0.1% | 99.3% |  |
| LIST_EXTEND | 200 | 0.1% | 99.3% |  |
| JUMP_BACKWARD | 200 | 0.1% | 99.4% |  |
| IS_OP | 200 | 0.1% | 99.5% |  |
| CALL_TYPE_1 | 200 | 0.1% | 99.5% |  |
| CALL_TUPLE_1 | 200 | 0.1% | 99.6% |  |
| CALL_STR_1 | 200 | 0.1% | 99.7% |  |
| CALL_INTRINSIC_1 | 200 | 0.1% | 99.8% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 200 | 0.1% | 99.8% |  |
| BINARY_OP_ADD_UNICODE | 200 | 0.1% | 99.9% |  |
| UNPACK_SEQUENCE | 180 | 0.1% | 100.0% |  |
| BINARY_SUBSCR | 100 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_FAST | 7,200 | 2.5% | 2.5% |
| STORE_FAST LOAD_FAST | 7,000 | 2.4% | 5.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 6,800 | 2.4% | 7.3% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 6,760 | 2.4% | 9.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 5,840 | 2.0% | 11.7% |
| LOAD_FAST LOAD_CONST | 5,800 | 2.0% | 13.8% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 5,780 | 2.0% | 15.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 5,400 | 1.9% | 17.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 4,200 | 1.5% | 19.1% |
| LOAD_ATTR_MODULE PUSH_NULL | 3,980 | 1.4% | 20.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,800 | 1.3% | 21.9% |
| RESUME_CHECK LOAD_FAST | 3,600 | 1.3% | 23.1% |
| PUSH_NULL LOAD_FAST | 3,600 | 1.3% | 24.4% |
| LOAD_CONST LOAD_FAST | 3,200 | 1.1% | 25.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,840 | 1.0% | 26.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,800 | 1.0% | 27.5% |
| LOAD_CONST LOAD_CONST | 2,800 | 1.0% | 28.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 2,800 | 1.0% | 29.4% |
| LOAD_CONST COMPARE_OP_INT | 2,700 | 0.9% | 30.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,600 | 0.9% | 31.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,600 | 0.9% | 32.2% |
| CACHE RESUME_CHECK | 2,600 | 0.9% | 33.1% |
| POP_TOP LOAD_FAST | 2,400 | 0.8% | 33.9% |
| LOAD_CONST STORE_FAST | 2,400 | 0.8% | 34.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 2,320 | 0.8% | 35.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 2,160 | 0.8% | 36.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,880 | 0.7% | 37.0% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,880 | 0.7% | 37.6% |
| LOAD_FAST CALL | 1,820 | 0.6% | 38.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,800 | 0.6% | 38.9% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,800 | 0.6% | 39.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,800 | 0.6% | 40.2% |
| LOAD_FAST RETURN_VALUE | 1,800 | 0.6% | 40.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,800 | 0.6% | 41.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,700 | 0.6% | 42.0% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,600 | 0.6% | 42.6% |
| NOP LOAD_FAST | 1,600 | 0.6% | 43.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,600 | 0.6% | 43.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,600 | 0.6% | 44.3% |
| LOAD_FAST LOAD_ATTR | 1,560 | 0.5% | 44.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,520 | 0.5% | 45.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,400 | 0.5% | 45.8% |
| RETURN_VALUE INTERPRETER_EXIT | 1,400 | 0.5% | 46.3% |
| RETURN_CONST INTERPRETER_EXIT | 1,400 | 0.5% | 46.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 1,340 | 0.5% | 47.3% |
| PUSH_NULL CALL | 1,220 | 0.4% | 47.7% |
| STORE_FAST STORE_FAST | 1,200 | 0.4% | 48.1% |
| RETURN_CONST POP_TOP | 1,200 | 0.4% | 48.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,200 | 0.4% | 48.9% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,200 | 0.4% | 49.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,200 | 0.4% | 49.8% |
| LOAD_FAST DELETE_ATTR | 1,200 | 0.4% | 50.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 1,200 | 0.4% | 50.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,160 | 0.4% | 51.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,080 | 0.4% | 51.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,080 | 0.4% | 51.8% |
| TO_BOOL_STR POP_JUMP_IF_FALSE | 1,000 | 0.3% | 52.1% |
| TO_BOOL POP_JUMP_IF_FALSE | 1,000 | 0.3% | 52.5% |
| STORE_FAST LOAD_CONST | 1,000 | 0.3% | 52.8% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,000 | 0.3% | 53.2% |
| POP_TOP RETURN_CONST | 1,000 | 0.3% | 53.5% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,000 | 0.3% | 53.9% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,000 | 0.3% | 54.2% |
| LOAD_FAST PUSH_NULL | 1,000 | 0.3% | 54.6% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NOT_NONE | 1,000 | 0.3% | 54.9% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 1,000 | 0.3% | 55.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 1,000 | 0.3% | 55.6% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 940 | 0.3% | 56.0% |
| LOAD_GLOBAL_MODULE TO_BOOL_BOOL | 900 | 0.3% | 56.3% |
| LOAD_FAST TO_BOOL | 900 | 0.3% | 56.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 900 | 0.3% | 56.9% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 800 | 0.3% | 57.2% |
| STORE_FAST NOP | 800 | 0.3% | 57.5% |
| RETURN_CONST STORE_FAST | 800 | 0.3% | 57.7% |
| POP_JUMP_IF_NONE LOAD_CONST | 800 | 0.3% | 58.0% |
| NOP LOAD_GLOBAL_BUILTIN | 800 | 0.3% | 58.3% |
| LOAD_FAST TO_BOOL_STR | 800 | 0.3% | 58.6% |
| LOAD_FAST COPY | 800 | 0.3% | 58.9% |
| LOAD_CONST CALL_KW | 800 | 0.3% | 59.1% |
| LOAD_ATTR_MODULE LOAD_FAST | 800 | 0.3% | 59.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 800 | 0.3% | 59.7% |
| LOAD_ATTR_INSTANCE_VALUE CALL_BUILTIN_FAST | 800 | 0.3% | 60.0% |
| DICT_MERGE CALL_FUNCTION_EX | 800 | 0.3% | 60.3% |
| DELETE_ATTR LOAD_FAST | 800 | 0.3% | 60.5% |
| COPY_FREE_VARS RESUME_CHECK | 800 | 0.3% | 60.8% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 800 | 0.3% | 61.1% |
| CALL_BUILTIN_FAST STORE_FAST | 800 | 0.3% | 61.4% |
| LOAD_FAST CALL_LEN | 780 | 0.3% | 61.6% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 760 | 0.3% | 61.9% |
| LOAD_CONST CALL_BUILTIN_FAST | 760 | 0.3% | 62.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 740 | 0.3% | 62.4% |
| LOAD_FAST CALL_BUILTIN_CLASS | 740 | 0.3% | 62.7% |
| LOAD_CONST CALL | 740 | 0.3% | 63.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 720 | 0.3% | 63.2% |
| LOAD_FAST TO_BOOL_BOOL | 720 | 0.3% | 63.5% |
| LOAD_ATTR_MODULE LOAD_ATTR_MODULE | 720 | 0.3% | 63.7% |
| CALL CALL | 680 | 0.2% | 63.9% |
| LOAD_ATTR LOAD_ATTR_INSTANCE_VALUE | 660 | 0.2% | 64.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR | 620 | 0.2% | 64.4% |
| LOAD_FAST STORE_ATTR | 620 | 0.2% | 64.6% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 60.0% |
| LOAD_CONST | 400 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 60.0% |
| LOAD_FAST | 200 | 20.0% |
| GET_ITER | 200 | 20.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,600 | 81.2% |
| POP_TOP | 400 | 12.5% |
| MAKE_CELL | 200 | 6.2% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 600 | 75.0% |
| LOAD_ATTR_INSTANCE_VALUE | 200 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 400 | 50.0% |
| POP_TOP | 400 | 50.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 200 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 60 | 60.0% |
| BINARY_SUBSCR_TUPLE_INT | 40 | 40.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 400 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 600 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 33.3% |
| CALL_BUILTIN_CLASS | 200 | 33.3% |
| BINARY_SLICE | 200 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 360 | 60.0% |
| FOR_ITER | 240 | 40.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,400 | 43.8% |
| RETURN_CONST | 1,400 | 43.8% |
| YIELD_VALUE | 400 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 400 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 800 | 22.2% |
| RESUME_CHECK | 400 | 11.1% |
| POP_JUMP_IF_NOT_NONE | 400 | 11.1% |
| DELETE_ATTR | 400 | 11.1% |
| POP_TOP | 200 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,600 | 44.4% |
| LOAD_GLOBAL_BUILTIN | 800 | 22.2% |
| LOAD_GLOBAL_MODULE | 540 | 15.0% |
| NOP | 200 | 5.6% |
| LOAD_DEREF | 200 | 5.6% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 400 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,200 | 18.2% |
| RETURN_VALUE | 600 | 9.1% |
| POP_JUMP_IF_TRUE | 600 | 9.1% |
| CALL_METHOD_DESCRIPTOR_O | 600 | 9.1% |
| CALL | 600 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,400 | 36.4% |
| RETURN_CONST | 1,000 | 15.2% |
| LOAD_CONST | 600 | 9.1% |
| LOAD_GLOBAL_MODULE | 540 | 8.2% |
| RESUME_CHECK | 400 | 6.1% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 400 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,980 | 71.1% |
| LOAD_FAST | 1,000 | 17.9% |
| LOAD_DEREF | 400 | 7.1% |
| LOAD_ATTR | 220 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,600 | 64.3% |
| CALL | 1,220 | 21.8% |
| LOAD_DEREF | 400 | 7.1% |
| LOAD_CONST | 200 | 3.6% |
| CALL_ALLOC_AND_ENTER_INIT | 180 | 3.2% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 100.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,800 | 33.3% |
| RETURN_VALUE | 600 | 11.1% |
| EXIT_INIT_CHECK | 600 | 11.1% |
| CALL_BUILTIN_FAST | 600 | 11.1% |
| BUILD_TUPLE | 600 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,400 | 25.9% |
| STORE_FAST | 600 | 11.1% |
| RETURN_VALUE | 600 | 11.1% |
| POP_TOP | 600 | 11.1% |
| BEFORE_WITH | 600 | 11.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 900 | 39.1% |
| LOAD_ATTR_INSTANCE_VALUE | 560 | 24.3% |
| TO_BOOL | 240 | 10.4% |
| RETURN_VALUE | 220 | 9.6% |
| LOAD_GLOBAL_MODULE | 100 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,000 | 43.5% |
| TO_BOOL_BOOL | 440 | 19.1% |
| TO_BOOL | 240 | 10.4% |
| POP_JUMP_IF_TRUE | 200 | 8.7% |
| EXTENDED_ARG | 200 | 8.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 38.0% |
| CALL_LEN | 600 | 38.0% |
| BUILD_LIST | 200 | 12.7% |
| BINARY_OP | 180 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 38.0% |
| COMPARE_OP_STR | 600 | 38.0% |
| LOAD_FAST | 200 | 12.7% |
| BINARY_OP | 180 | 11.4% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 33.3% |
| STORE_FAST | 200 | 16.7% |
| RESUME_CHECK | 200 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 200 | 16.7% |
| CALL_STR_1 | 200 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 50.0% |
| LOAD_FAST | 200 | 16.7% |
| BINARY_OP | 200 | 16.7% |
| LOAD_ATTR_METHOD_NO_DICT | 180 | 15.0% |
| LOAD_ATTR | 20 | 1.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 50.0% |
| LOAD_DEREF | 200 | 25.0% |
| CALL_INTRINSIC_1 | 200 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 75.0% |
| LOAD_DEREF | 200 | 25.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,000 | 55.6% |
| LOAD_FAST | 400 | 22.2% |
| LOAD_GLOBAL_BUILTIN | 200 | 11.1% |
| LOAD_DEREF | 200 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 600 | 33.3% |
| LOAD_CONST | 400 | 22.2% |
| CALL_METHOD_DESCRIPTOR_O | 360 | 20.0% |
| STORE_FAST | 200 | 11.1% |
| CALL_ISINSTANCE | 180 | 10.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,820 | 30.5% |
| PUSH_NULL | 1,220 | 20.5% |
| LOAD_CONST | 740 | 12.4% |
| CALL | 680 | 11.4% |
| LOAD_GLOBAL_MODULE | 280 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 680 | 11.4% |
| POP_TOP | 600 | 10.1% |
| LOAD_FAST | 600 | 10.1% |
| LOAD_CONST | 600 | 10.1% |
| TO_BOOL_BOOL | 400 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 800 | 66.7% |
| LOAD_FAST | 400 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 400 | 33.3% |
| POP_TOP | 200 | 16.7% |
| MAKE_CELL | 200 | 16.7% |
| COPY_FREE_VARS | 200 | 16.7% |
| LOAD_GLOBAL_MODULE | 160 | 13.3% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 200 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 400 | 50.0% |
| STORE_FAST | 200 | 25.0% |
| LOAD_FAST | 200 | 25.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 300 | 48.4% |
| LOAD_FAST_LOAD_FAST | 200 | 32.3% |
| LOAD_GLOBAL_MODULE | 60 | 9.7% |
| COMPARE_OP | 40 | 6.5% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 380 | 61.3% |
| POP_JUMP_IF_FALSE | 200 | 32.3% |
| COMPARE_OP | 40 | 6.5% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800 | 80.0% |
| RETURN_VALUE | 200 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 540 | 54.0% |
| LOAD_FAST | 200 | 20.0% |
| TO_BOOL_BOOL | 180 | 18.0% |
| TO_BOOL | 80 | 8.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 400 | 50.0% |
| CALL_PY_EXACT_ARGS | 200 | 25.0% |
| CALL_FUNCTION_EX | 200 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 800 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800 | 66.7% |
| NOP | 400 | 33.3% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 75.0% |
| LOAD_DEREF | 200 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 800 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 66.7% |
| TO_BOOL | 200 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 200 | 33.3% |
| POP_JUMP_IF_NONE | 200 | 33.3% |
| POP_JUMP_IF_FALSE | 200 | 33.3% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 240 | 54.5% |
| JUMP_BACKWARD | 200 | 45.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 45.5% |
| NOP | 200 | 45.5% |
| FOR_ITER_LIST | 40 | 9.1% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 200 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 50.0% |
| POP_TOP | 200 | 16.7% |
| POP_JUMP_IF_NOT_NONE | 200 | 16.7% |
| POP_JUMP_IF_FALSE | 200 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 50.0% |
| NOP | 200 | 16.7% |
| LOAD_CONST | 200 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 180 | 15.0% |
| LOAD_GLOBAL | 20 | 1.7% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 200 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,560 | 40.8% |
| LOAD_GLOBAL_MODULE | 740 | 19.4% |
| LOAD_ATTR_MODULE | 480 | 12.6% |
| LOAD_ATTR_INSTANCE_VALUE | 460 | 12.0% |
| LOAD_ATTR | 320 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 660 | 17.3% |
| LOAD_ATTR_MODULE | 620 | 16.2% |
| LOAD_FAST_LOAD_FAST | 400 | 10.5% |
| TO_BOOL_INT | 360 | 9.4% |
| LOAD_ATTR | 320 | 8.4% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,800 | 31.5% |
| LOAD_CONST | 2,800 | 15.2% |
| STORE_ATTR_INSTANCE_VALUE | 1,800 | 9.8% |
| STORE_FAST | 1,000 | 5.4% |
| POP_JUMP_IF_NONE | 800 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,200 | 17.4% |
| LOAD_CONST | 2,800 | 15.2% |
| COMPARE_OP_INT | 2,700 | 14.7% |
| STORE_FAST | 2,400 | 13.0% |
| CALL_KW | 800 | 4.3% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 400 | 13.3% |
| POP_JUMP_IF_FALSE | 400 | 13.3% |
| LOAD_GLOBAL_MODULE | 400 | 13.3% |
| LOAD_ATTR_MODULE | 400 | 13.3% |
| RESUME_CHECK | 200 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 600 | 20.0% |
| CALL_PY_EXACT_ARGS | 540 | 18.0% |
| PUSH_NULL | 400 | 13.3% |
| STORE_FAST | 200 | 6.7% |
| POP_JUMP_IF_NOT_NONE | 200 | 6.7% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,200 | 11.7% |
| STORE_FAST | 7,000 | 11.4% |
| POP_JUMP_IF_FALSE | 6,800 | 11.0% |
| LOAD_GLOBAL_BUILTIN | 5,400 | 8.8% |
| RESUME_CHECK | 3,600 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,200 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 6,760 | 11.0% |
| LOAD_CONST | 5,800 | 9.4% |
| STORE_ATTR_INSTANCE_VALUE | 5,780 | 9.4% |
| POP_JUMP_IF_NOT_NONE | 2,600 | 4.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,200 | 16.2% |
| LOAD_FAST_LOAD_FAST | 1,200 | 16.2% |
| STORE_FAST_STORE_FAST | 600 | 8.1% |
| LOAD_DEREF | 600 | 8.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 600 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,800 | 24.3% |
| LOAD_FAST_LOAD_FAST | 1,200 | 16.2% |
| BUILD_TUPLE | 1,000 | 13.5% |
| STORE_ATTR | 620 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 600 | 8.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 19.4% |
| LOAD_FAST | 240 | 16.7% |
| RESUME_CHECK | 200 | 13.9% |
| POP_JUMP_IF_FALSE | 180 | 12.5% |
| POP_JUMP_IF_NOT_NONE | 100 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 940 | 65.3% |
| LOAD_GLOBAL_BUILTIN | 480 | 33.3% |
| LOAD_ATTR | 20 | 1.4% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 400 | 40.0% |
| CALL_PY_EXACT_ARGS | 200 | 20.0% |
| CALL_FUNCTION_EX | 200 | 20.0% |
| CACHE | 200 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 600 | 60.0% |
| MAKE_CELL | 400 | 40.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,200 | 32.8% |
| COMPARE_OP_INT | 3,800 | 29.7% |
| TO_BOOL_STR | 1,000 | 7.8% |
| TO_BOOL | 1,000 | 7.8% |
| TO_BOOL_INT | 800 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,800 | 53.1% |
| LOAD_FAST_LOAD_FAST | 1,200 | 9.4% |
| LOAD_GLOBAL_MODULE | 1,080 | 8.4% |
| RETURN_CONST | 1,000 | 7.8% |
| LOAD_CONST | 600 | 4.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,600 | 72.7% |
| LOAD_ATTR_INSTANCE_VALUE | 400 | 18.2% |
| EXTENDED_ARG | 200 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 54.5% |
| LOAD_CONST | 800 | 36.4% |
| NOP | 200 | 9.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,600 | 61.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,000 | 23.8% |
| LOAD_GLOBAL_MODULE | 200 | 4.8% |
| LOAD_DEREF | 200 | 4.8% |
| EXTENDED_ARG | 200 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,800 | 42.9% |
| LOAD_GLOBAL_BUILTIN | 540 | 12.9% |
| NOP | 400 | 9.5% |
| LOAD_CONST | 400 | 9.5% |
| LOAD_GLOBAL_MODULE | 360 | 8.6% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,400 | 63.6% |
| TO_BOOL_NONE | 600 | 27.3% |
| TO_BOOL | 200 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 600 | 27.3% |
| LOAD_FAST | 600 | 27.3% |
| LOAD_GLOBAL_MODULE | 360 | 16.4% |
| NOP | 200 | 9.1% |
| LOAD_GLOBAL_BUILTIN | 200 | 9.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,000 | 23.8% |
| POP_TOP | 1,000 | 23.8% |
| POP_JUMP_IF_FALSE | 1,000 | 23.8% |
| STORE_ATTR | 400 | 9.5% |
| POP_EXCEPT | 400 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,400 | 33.3% |
| POP_TOP | 1,200 | 28.6% |
| STORE_FAST | 800 | 19.0% |
| EXIT_INIT_CHECK | 600 | 14.3% |
| TO_BOOL_NONE | 180 | 4.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 400 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 620 | 45.6% |
| LOAD_FAST | 620 | 45.6% |
| STORE_ATTR | 120 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 440 | 32.4% |
| RETURN_CONST | 400 | 29.4% |
| LOAD_FAST | 200 | 14.7% |
| LOAD_GLOBAL_MODULE | 180 | 13.2% |
| STORE_ATTR | 120 | 8.8% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 200 | 33.3% |
| CALL | 200 | 33.3% |
| BINARY_SUBSCR_LIST_INT | 200 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 360 | 60.0% |
| LOAD_FAST | 200 | 33.3% |
| LOAD_GLOBAL | 40 | 6.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,400 | 16.2% |
| STORE_FAST | 1,200 | 8.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,000 | 6.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,000 | 6.8% |
| RETURN_CONST | 800 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,000 | 47.3% |
| LOAD_GLOBAL_MODULE | 2,600 | 17.6% |
| STORE_FAST | 1,200 | 8.1% |
| LOAD_CONST | 1,000 | 6.8% |
| NOP | 800 | 5.4% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 600 | 37.5% |
| LOAD_FAST | 600 | 37.5% |
| LOAD_CONST | 400 | 25.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 66.7% |
| RETURN_VALUE | 200 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 66.7% |
| LOAD_CONST | 200 | 33.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 33.3% |
| RETURN_VALUE | 40 | 22.2% |
| CALL | 40 | 22.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 20 | 11.1% |
| CALL_BUILTIN_FAST | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 160 | 88.9% |
| UNPACK_SEQUENCE_TUPLE | 20 | 11.1% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 50.0% |
| LOAD_CONST | 200 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 400 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 100.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 200 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540 | 90.0% |
| BINARY_SUBSCR | 60 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 220 | 36.7% |
| STORE_DEREF | 200 | 33.3% |
| CALL_BUILTIN_CLASS | 180 | 30.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 360 | 90.0% |
| BINARY_SUBSCR | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 400 | 100.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 400 | 66.7% |
| PUSH_NULL | 180 | 30.0% |
| CALL | 20 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 600 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 360 | 90.0% |
| CALL | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 400 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 740 | 74.0% |
| BINARY_SUBSCR_LIST_INT | 180 | 18.0% |
| CALL | 80 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 60.0% |
| GET_ITER | 200 | 20.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 180 | 18.0% |
| CALL | 20 | 2.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 800 | 30.8% |
| LOAD_CONST | 760 | 29.2% |
| LOAD_FAST | 560 | 21.5% |
| LOAD_GLOBAL_MODULE | 180 | 6.9% |
| LOAD_FAST_LOAD_FAST | 180 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 800 | 30.8% |
| RETURN_VALUE | 600 | 23.1% |
| PUSH_EXC_INFO | 400 | 15.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 380 | 14.6% |
| POP_TOP | 200 | 7.7% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,880 | 85.5% |
| CALL_BUILTIN_CLASS | 180 | 8.2% |
| CALL | 140 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,000 | 45.5% |
| POP_TOP | 400 | 18.2% |
| LOAD_FAST | 400 | 18.2% |
| TO_BOOL_BOOL | 180 | 8.2% |
| CALL_TUPLE_1 | 180 | 8.2% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,340 | 74.4% |
| LOAD_ATTR_MODULE | 180 | 10.0% |
| BUILD_TUPLE | 180 | 10.0% |
| CALL | 100 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,700 | 94.4% |
| TO_BOOL | 100 | 5.6% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 780 | 97.5% |
| CALL | 20 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 600 | 75.0% |
| LOAD_CONST | 200 | 25.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 60.0% |
| LOAD_CONST | 180 | 18.0% |
| LOAD_ATTR | 180 | 18.0% |
| CALL | 40 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,000 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 180 | 45.0% |
| LOAD_ATTR_METHOD_NO_DICT | 180 | 45.0% |
| CALL | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 50.0% |
| RETURN_VALUE | 200 | 50.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 180 | 45.0% |
| LOAD_ATTR | 180 | 45.0% |
| CALL | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 200 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 45.0% |
| UNPACK_SEQUENCE | 20 | 5.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 360 | 45.0% |
| LOAD_FAST | 180 | 22.5% |
| LOAD_CONST | 180 | 22.5% |
| CALL | 80 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 600 | 75.0% |
| LOAD_CONST | 200 | 25.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,520 | 47.5% |
| LOAD_GLOBAL_MODULE | 540 | 16.9% |
| LOAD_DEREF | 540 | 16.9% |
| CALL | 220 | 6.9% |
| LOAD_FAST_LOAD_FAST | 200 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,800 | 87.5% |
| MAKE_CELL | 200 | 6.2% |
| COPY_FREE_VARS | 200 | 6.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 45.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 360 | 45.0% |
| CALL | 80 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 800 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 90.0% |
| CALL | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 200 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 180 | 90.0% |
| CALL | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 90.0% |
| CALL | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 200 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,700 | 71.1% |
| LOAD_GLOBAL_MODULE | 540 | 14.2% |
| COMPARE_OP | 380 | 10.0% |
| LOAD_ATTR_INSTANCE_VALUE | 180 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,800 | 100.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 600 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 360 | 90.0% |
| FOR_ITER | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 200 | 50.0% |
| NOP | 200 | 50.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,760 | 86.7% |
| LOAD_ATTR | 660 | 8.5% |
| LOAD_FAST_LOAD_FAST | 380 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 15.4% |
| POP_JUMP_IF_NOT_NONE | 1,000 | 12.8% |
| TO_BOOL_BOOL | 900 | 11.5% |
| CALL_BUILTIN_FAST | 800 | 10.3% |
| TO_BOOL | 560 | 7.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,320 | 72.5% |
| LOAD_ATTR_INSTANCE_VALUE | 540 | 16.9% |
| BUILD_LIST | 180 | 5.6% |
| LOAD_ATTR | 160 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,800 | 56.2% |
| LOAD_FAST_LOAD_FAST | 400 | 12.5% |
| LOAD_CONST | 400 | 12.5% |
| LOAD_DEREF | 200 | 6.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 180 | 5.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,160 | 90.0% |
| LOAD_ATTR | 240 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800 | 33.3% |
| LOAD_FAST_LOAD_FAST | 600 | 25.0% |
| CALL_PY_WITH_DEFAULTS | 360 | 15.0% |
| CALL | 240 | 10.0% |
| LOAD_CONST | 200 | 8.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 5,840 | 81.3% |
| LOAD_ATTR_MODULE | 720 | 10.0% |
| LOAD_ATTR | 620 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,980 | 55.4% |
| LOAD_FAST | 800 | 11.1% |
| LOAD_ATTR_MODULE | 720 | 10.0% |
| LOAD_ATTR | 480 | 6.7% |
| LOAD_DEREF | 400 | 5.6% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,880 | 21.3% |
| RESUME_CHECK | 1,160 | 13.1% |
| NOP | 800 | 9.0% |
| LOAD_GLOBAL_BUILTIN | 760 | 8.6% |
| STORE_FAST | 720 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,400 | 61.1% |
| CALL_ISINSTANCE | 1,340 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 760 | 8.6% |
| CHECK_EXC_MATCH | 400 | 4.5% |
| CALL | 260 | 2.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,840 | 24.1% |
| STORE_FAST | 2,600 | 22.1% |
| POP_JUMP_IF_FALSE | 1,080 | 9.2% |
| LOAD_FAST | 1,080 | 9.2% |
| LOAD_GLOBAL | 940 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 5,840 | 49.6% |
| LOAD_FAST | 1,600 | 13.6% |
| TO_BOOL_BOOL | 900 | 7.6% |
| LOAD_ATTR | 740 | 6.3% |
| COMPARE_OP_INT | 540 | 4.6% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,800 | 29.8% |
| CACHE | 2,600 | 27.7% |
| COPY_FREE_VARS | 800 | 8.5% |
| CALL_PY_WITH_DEFAULTS | 800 | 8.5% |
| MAKE_CELL | 600 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,600 | 38.3% |
| LOAD_GLOBAL_MODULE | 2,840 | 30.2% |
| LOAD_GLOBAL_BUILTIN | 1,160 | 12.3% |
| POP_TOP | 400 | 4.3% |
| NOP | 400 | 4.3% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,780 | 87.6% |
| STORE_ATTR | 440 | 6.7% |
| LOAD_FAST_LOAD_FAST | 380 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,800 | 42.4% |
| LOAD_CONST | 1,800 | 27.3% |
| RETURN_CONST | 1,000 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 400 | 6.1% |
| LOAD_FAST_LOAD_FAST | 400 | 6.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 90.0% |
| STORE_SUBSCR | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 100.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 180 | 90.0% |
| TO_BOOL | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 200 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 1,700 | 30.4% |
| LOAD_GLOBAL_MODULE | 900 | 16.1% |
| LOAD_ATTR_INSTANCE_VALUE | 900 | 16.1% |
| LOAD_FAST | 720 | 12.9% |
| TO_BOOL | 440 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,200 | 75.0% |
| POP_JUMP_IF_TRUE | 1,400 | 25.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 360 | 45.0% |
| LOAD_FAST | 180 | 22.5% |
| LOAD_ATTR_INSTANCE_VALUE | 180 | 22.5% |
| TO_BOOL | 80 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 800 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 540 | 54.0% |
| RETURN_CONST | 180 | 18.0% |
| LOAD_ATTR_INSTANCE_VALUE | 180 | 18.0% |
| TO_BOOL | 100 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 600 | 60.0% |
| POP_JUMP_IF_FALSE | 400 | 40.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800 | 80.0% |
| RETURN_VALUE | 180 | 18.0% |
| TO_BOOL | 20 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,000 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 180 | 90.0% |
| UNPACK_SEQUENCE | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540 | 30.0% |
| CALL_BUILTIN_FAST | 380 | 21.1% |
| CALL | 360 | 20.0% |
| RETURN_VALUE | 180 | 10.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 180 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,600 | 88.9% |
| STORE_FAST | 200 | 11.1% |


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

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         1000 | 90.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          200 | 90.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         1400 | 12.8% |
|          hit |         8400 | 77.1% |
|         miss |          200 | 1.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 660 | 73.3% |
| Failure | 240 | 26.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 80 | 33.3% |
| bytes | 80 | 33.3% |
| tuple | 40 | 16.7% |
| bytearray | 40 | 16.7% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         1400 | 54.3% |
|          hit |         1000 | 38.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 180 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 100 | 55.6% |
| multiply different types | 40 | 22.2% |
| add different types | 40 | 22.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         4200 | 18.6% |
|          hit |        16200 | 71.8% |
|         miss |          400 | 1.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,080 | 61.4% |
| Failure | 680 | 38.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 240 | 35.3% |
| code complex parameters | 200 | 29.4% |
| class no vectorcall | 120 | 17.6% |
| meth descr varargs | 40 | 5.9% |
| cfunc varargs keywords | 40 | 5.9% |
| cfunc varargs | 40 | 5.9% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          200 | 4.0% |
|          hit |         4200 | 83.7% |
|         miss |          200 | 4.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 90.5% |
| Failure | 40 | 9.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 40 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          400 | 47.6% |
|          hit |          400 | 47.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


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
| specialization.deferred |         1820 | 7.5% |
|          hit |        20180 | 82.7% |
|         miss |          400 | 1.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,680 | 84.0% |
| Failure | 320 | 16.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 80 | 25.0% |
| non object slot | 80 | 25.0% |
| metaclass attribute | 60 | 18.8% |
| class attr descriptor | 40 | 12.5% |
| shadowed | 40 | 12.5% |
| class attr simple | 20 | 6.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.1% |
| specialization.deopt |           40 | 0.2% |
|          hit |        18980 | 86.0% |
|         miss |         1640 | 7.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,460 | 100.0% |
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

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>

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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          800 | 10.1% |
|          hit |         6600 | 82.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 440 | 78.6% |
| Failure | 120 | 21.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 80 | 66.7% |
| not managed dict | 40 | 33.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         2000 | 91.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
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
| Basic | 154,400 | 53.9% |
| Not specialized | 43,260 | 15.1% |
| Specialized | 88,560 | 30.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 4,200 | 41.0% |
| LOAD_ATTR | 1,820 | 17.8% |
| TO_BOOL | 1,400 | 13.7% |
| BINARY_OP | 1,400 | 13.7% |
| STORE_ATTR | 800 | 7.8% |
| FOR_ITER | 400 | 3.9% |
| COMPARE_OP | 200 | 2.0% |
| LOAD_GLOBAL | 20 | 0.2% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,640 | 57.7% |
| LOAD_ATTR_METHOD_NO_DICT | 400 | 14.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 400 | 14.1% |
| TO_BOOL_STR | 200 | 7.0% |
| COMPARE_OP_STR | 200 | 7.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |
| TO_BOOL_INT | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 3,200 | 32.7% |
| Calls to Python functions inlined | 6,600 | 67.3% |
| Calls via PyEval_EvalFrame (total) | 3,200 | 32.7% |
| Calls via PyEval_EvalFrame (vector) | 2,400 | 24.5% |
| Calls via PyEval_EvalFrame (generator) | 800 | 8.2% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 2,400 | 24.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 800 | 8.2% |
| Calls via PyEval_EvalFrame (api) | 400 | 4.1% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 9,600 | 98.0% |
| Frame objects created | 400 | 4.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,060 | 37.4% |
| Frees to freelist | 14,200 |  |
| Allocations | 23,540 | 62.6% |
| Allocations to 512 bytes | 22,740 | 60.5% |
| Allocations to 4 kbytes | 200 | 0.5% |
| Allocations over 4 kbytes | 600 | 1.6% |
| Frees | 23,207 |  |
| New values | 400 |  |
| Interpreter increfs | 103,780 | 67.7% |
| Interpreter decrefs | 120,400 | 65.1% |
| Increfs | 49,464 | 32.3% |
| Decrefs | 64,451 | 34.9% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 13,795 |  |
| Method cache misses | 225 |  |
| Method cache collisions | 200 |  |
| Method cache dunder hits | 5,897 |  |
| Method cache dunder misses | 23 |  |


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
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 0 |  |
| Uops executed | 0 | 0 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |


</details>

**Trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|


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
Stats gathered on: 2023-10-11
