
# Pystats results

- benchmark: regex_effbot
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 4,897,580 | 16.7% | 16.7% |  |
| LOAD_GLOBAL_MODULE | 2,414,420 | 8.2% | 24.9% |  |
| LOAD_GLOBAL_BUILTIN | 2,393,760 | 8.2% | 33.1% |  |
| POP_JUMP_IF_FALSE | 1,954,880 | 6.7% | 39.7% |  |
| LOAD_FAST_LOAD_FAST | 1,864,880 | 6.4% | 46.1% |  |
| STORE_FAST | 1,005,320 | 3.4% | 49.5% |  |
| RESUME_CHECK | 980,420 | 3.3% | 52.9% |  |
| POP_TOP | 972,080 | 3.3% | 56.2% |  |
| RETURN_VALUE | 967,840 | 3.3% | 59.5% |  |
| TO_BOOL_BOOL | 960,140 | 3.3% | 62.7% |  |
| CALL_ISINSTANCE | 952,400 | 3.2% | 66.0% |  |
| BUILD_TUPLE | 951,000 | 3.2% | 69.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 950,120 | 3.2% | 72.5% |  |
| CALL_TYPE_1 | 941,900 | 3.2% | 75.7% |  |
| LOAD_CONST | 541,460 | 1.8% | 77.5% |  |
| CALL_PY_EXACT_ARGS | 485,580 | 1.7% | 79.2% |  |
| TO_BOOL_INT | 481,760 | 1.6% | 80.8% |  |
| JUMP_FORWARD | 479,700 | 1.6% | 82.4% |  |
| CALL | 478,640 | 1.6% | 84.1% |  |
| NOP | 476,380 | 1.6% | 85.7% |  |
| POP_JUMP_IF_NOT_NONE | 475,060 | 1.6% | 87.3% |  |
| BINARY_SUBSCR_DICT | 472,080 | 1.6% | 88.9% |  |
| CALL_PY_WITH_DEFAULTS | 471,200 | 1.6% | 90.5% |  |
| CHECK_EXC_MATCH | 471,080 | 1.6% | 92.1% |  |
| POP_EXCEPT | 471,080 | 1.6% | 93.7% |  |
| PUSH_EXC_INFO | 471,080 | 1.6% | 95.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 470,780 | 1.6% | 96.9% |  |
| PUSH_NULL | 452,660 | 1.5% | 98.5% |  |
| ENTER_EXECUTOR | 63,380 | 0.2% | 98.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 39,200 | 0.1% | 98.8% |  |
| EXTENDED_ARG | 23,440 | 0.1% | 98.9% |  |
| BINARY_OP | 19,360 | 0.1% | 99.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 18,860 | 0.1% | 99.0% |  |
| RETURN_CONST | 18,640 | 0.1% | 99.1% |  |
| CALL_BUILTIN_O | 15,160 | 0.1% | 99.2% |  |
| IS_OP | 13,900 | 0.0% | 99.2% |  |
| COMPARE_OP_STR | 12,420 | 0.0% | 99.3% | 4.5% |
| CONTAINS_OP | 12,160 | 0.0% | 99.3% |  |
| CALL_LEN | 11,620 | 0.0% | 99.3% |  |
| POP_JUMP_IF_TRUE | 11,560 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_INT | 10,840 | 0.0% | 99.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 10,680 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 10,220 | 0.0% | 99.5% |  |
| BINARY_SUBSCR_LIST_INT | 10,160 | 0.0% | 99.5% | 8.9% |
| STORE_FAST_STORE_FAST | 8,980 | 0.0% | 99.5% |  |
| LOAD_ATTR | 7,880 | 0.0% | 99.6% |  |
| INTERPRETER_EXIT | 7,620 | 0.0% | 99.6% |  |
| FOR_ITER_LIST | 6,960 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_TUPLE_INT | 6,700 | 0.0% | 99.6% |  |
| GET_ITER | 6,500 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 6,420 | 0.0% | 99.7% | 5.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,380 | 0.0% | 99.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,320 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_GETITEM | 5,180 | 0.0% | 99.7% |  |
| BINARY_OP_ADD_UNICODE | 5,040 | 0.0% | 99.8% |  |
| BUILD_LIST | 5,000 | 0.0% | 99.8% |  |
| COMPARE_OP_INT | 4,620 | 0.0% | 99.8% |  |
| FOR_ITER | 4,360 | 0.0% | 99.8% |  |
| BINARY_OP_SUBTRACT_INT | 4,240 | 0.0% | 99.8% |  |
| COPY | 3,560 | 0.0% | 99.8% |  |
| LOAD_DEREF | 3,320 | 0.0% | 99.8% |  |
| JUMP_BACKWARD | 3,180 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 3,080 | 0.0% | 99.9% |  |
| COPY_FREE_VARS | 3,020 | 0.0% | 99.9% |  |
| TO_BOOL_LIST | 2,600 | 0.0% | 99.9% | 13.8% |
| POP_JUMP_IF_NONE | 2,400 | 0.0% | 99.9% |  |
| TO_BOOL | 2,340 | 0.0% | 99.9% |  |
| LOAD_ATTR_MODULE | 2,000 | 0.0% | 99.9% |  |
| COMPARE_OP | 1,980 | 0.0% | 99.9% |  |
| BINARY_SUBSCR | 1,480 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 1,480 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 1,420 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 1,340 | 0.0% | 99.9% | 9.0% |
| STORE_SUBSCR | 1,340 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 1,180 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 1,160 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 1,100 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 1,080 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 1,080 | 0.0% | 100.0% |  |
| UNARY_NOT | 960 | 0.0% | 100.0% |  |
| LOAD_ATTR_PROPERTY | 920 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 820 | 0.0% | 100.0% |  |
| BUILD_SLICE | 740 | 0.0% | 100.0% |  |
| BUILD_MAP | 700 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 680 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 680 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 680 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 640 | 0.0% | 100.0% |  |
| BINARY_SLICE | 440 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 340 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 340 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 340 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 280 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 260 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 240 | 0.0% | 100.0% |  |
| UNARY_INVERT | 200 | 0.0% | 100.0% |  |
| RESUME | 180 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 160 | 0.0% | 100.0% | 100.0% |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 140 | 0.0% | 100.0% |  |
| MAKE_CELL | 140 | 0.0% | 100.0% |  |
| MAP_ADD | 140 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 140 | 0.0% | 100.0% |  |
| STORE_DEREF | 140 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 80 | 0.0% | 100.0% |  |
| STORE_SLICE | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| SWAP | 40 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 20 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 20 | 0.0% | 100.0% |  |
| STORE_ATTR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,905,400 | 6.5% | 6.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 997,160 | 3.4% | 9.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 972,340 | 3.3% | 13.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 957,620 | 3.3% | 16.5% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 951,380 | 3.2% | 19.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 947,780 | 3.2% | 22.9% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 942,420 | 3.2% | 26.1% |
| LOAD_FAST CALL_TYPE_1 | 941,900 | 3.2% | 29.4% |
| CALL_TYPE_1 LOAD_FAST_LOAD_FAST | 941,560 | 3.2% | 32.6% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 941,560 | 3.2% | 35.8% |
| STORE_FAST LOAD_FAST | 500,400 | 1.7% | 37.5% |
| LOAD_FAST LOAD_CONST | 498,220 | 1.7% | 39.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 485,820 | 1.7% | 40.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 482,940 | 1.6% | 42.5% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 477,780 | 1.6% | 44.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 477,100 | 1.6% | 45.7% |
| LOAD_FAST RETURN_VALUE | 477,040 | 1.6% | 47.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 475,440 | 1.6% | 49.0% |
| LOAD_FAST TO_BOOL_INT | 475,240 | 1.6% | 50.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 474,780 | 1.6% | 52.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 474,540 | 1.6% | 53.8% |
| RETURN_VALUE POP_TOP | 473,740 | 1.6% | 55.4% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 472,780 | 1.6% | 57.1% |
| JUMP_FORWARD LOAD_GLOBAL_BUILTIN | 472,140 | 1.6% | 58.7% |
| LOAD_FAST CALL | 472,000 | 1.6% | 60.3% |
| POP_JUMP_IF_FALSE POP_TOP | 471,980 | 1.6% | 61.9% |
| POP_JUMP_IF_FALSE NOP | 471,300 | 1.6% | 63.5% |
| BUILD_TUPLE STORE_FAST | 471,260 | 1.6% | 65.1% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 471,200 | 1.6% | 66.7% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 471,080 | 1.6% | 68.3% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 471,080 | 1.6% | 69.9% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 471,080 | 1.6% | 71.5% |
| NOP LOAD_GLOBAL_MODULE | 470,820 | 1.6% | 73.1% |
| BUILD_TUPLE BINARY_SUBSCR_DICT | 470,820 | 1.6% | 74.7% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 470,820 | 1.6% | 76.3% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 470,800 | 1.6% | 77.9% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 470,780 | 1.6% | 79.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_NO_DICT | 470,780 | 1.6% | 81.1% |
| POP_EXCEPT JUMP_FORWARD | 470,740 | 1.6% | 82.7% |
| POP_TOP POP_EXCEPT | 470,740 | 1.6% | 84.3% |
| CALL RETURN_VALUE | 470,740 | 1.6% | 85.9% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST | 470,740 | 1.6% | 87.6% |
| BINARY_SUBSCR_DICT PUSH_EXC_INFO | 470,740 | 1.6% | 89.2% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 470,380 | 1.6% | 90.8% |
| LOAD_FAST PUSH_NULL | 449,460 | 1.5% | 92.3% |
| POP_TOP LOAD_FAST | 442,800 | 1.5% | 93.8% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 425,680 | 1.5% | 95.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 423,940 | 1.4% | 96.7% |
| POP_TOP ENTER_EXECUTOR | 48,680 | 0.2% | 96.9% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 46,400 | 0.2% | 97.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 33,920 | 0.1% | 97.1% |
| PUSH_NULL LOAD_FAST | 13,280 | 0.0% | 97.2% |
| LOAD_GLOBAL_MODULE IS_OP | 13,120 | 0.0% | 97.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 12,920 | 0.0% | 97.3% |
| RETURN_CONST POP_TOP | 12,840 | 0.0% | 97.3% |
| RESUME_CHECK LOAD_FAST | 12,700 | 0.0% | 97.4% |
| CALL_BUILTIN_O POP_TOP | 12,340 | 0.0% | 97.4% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 11,060 | 0.0% | 97.4% |
| IS_OP POP_JUMP_IF_FALSE | 10,680 | 0.0% | 97.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 10,500 | 0.0% | 97.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 10,060 | 0.0% | 97.5% |
| LOAD_CONST COMPARE_OP_STR | 10,020 | 0.0% | 97.6% |
| LOAD_CONST BINARY_OP_ADD_INT | 9,940 | 0.0% | 97.6% |
| LOAD_CONST LOAD_FAST | 9,580 | 0.0% | 97.6% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 9,480 | 0.0% | 97.7% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 8,820 | 0.0% | 97.7% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 8,540 | 0.0% | 97.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 8,520 | 0.0% | 97.8% |
| CACHE RESUME_CHECK | 8,500 | 0.0% | 97.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 8,460 | 0.0% | 97.8% |
| LOAD_FAST CALL_BUILTIN_O | 8,400 | 0.0% | 97.8% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 8,040 | 0.0% | 97.9% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 7,960 | 0.0% | 97.9% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 7,220 | 0.0% | 97.9% |
| LOAD_GLOBAL_MODULE BINARY_OP | 7,180 | 0.0% | 98.0% |
| LOAD_FAST LOAD_ATTR | 6,980 | 0.0% | 98.0% |
| EXTENDED_ARG ENTER_EXECUTOR | 6,820 | 0.0% | 98.0% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 6,680 | 0.0% | 98.0% |
| LOAD_CONST STORE_FAST | 6,620 | 0.0% | 98.0% |
| PUSH_NULL LOAD_CONST | 6,460 | 0.0% | 98.1% |
| STORE_FAST LOAD_CONST | 6,460 | 0.0% | 98.1% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 6,380 | 0.0% | 98.1% |
| LOAD_FAST BINARY_OP | 6,260 | 0.0% | 98.1% |
| RETURN_VALUE INTERPRETER_EXIT | 6,180 | 0.0% | 98.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 6,180 | 0.0% | 98.2% |
| CALL_LIST_APPEND RETURN_CONST | 6,040 | 0.0% | 98.2% |
| BINARY_OP TO_BOOL_INT | 6,020 | 0.0% | 98.2% |
| LOAD_FAST CALL_LIST_APPEND | 6,020 | 0.0% | 98.2% |
| LOAD_ATTR STORE_FAST | 5,900 | 0.0% | 98.3% |
| LOAD_FAST CALL_LEN | 5,900 | 0.0% | 98.3% |
| LOAD_GLOBAL_MODULE STORE_FAST | 5,840 | 0.0% | 98.3% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 5,660 | 0.0% | 98.3% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 5,500 | 0.0% | 98.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 5,260 | 0.0% | 98.4% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 5,180 | 0.0% | 98.4% |
| BINARY_OP_ADD_INT LOAD_FAST | 5,140 | 0.0% | 98.4% |
| BINARY_OP_ADD_INT STORE_FAST | 5,060 | 0.0% | 98.4% |
| LOAD_FAST LOAD_FAST | 5,020 | 0.0% | 98.4% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 4,980 | 0.0% | 98.4% |
| NOP LOAD_FAST | 4,940 | 0.0% | 98.5% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 420 | 95.5% |
| CALL | 20 | 4.5% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 60 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,500 | 100.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 740 | 50.0% |
| LOAD_FAST | 480 | 32.4% |
| LOAD_CONST | 160 | 10.8% |
| LOAD_FAST_LOAD_FAST | 80 | 5.4% |
| BINARY_SUBSCR | 20 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 740 | 50.0% |
| CALL_ALLOC_AND_ENTER_INIT | 400 | 27.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 8.1% |
| STORE_FAST | 40 | 2.7% |
| BINARY_SUBSCR_LIST_INT | 40 | 2.7% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 471,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 471,080 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 50.0% |
| LOAD_FAST | 120 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 120 | 50.0% |
| RETURN_CONST | 120 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,080 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,980 | 45.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,900 | 29.2% |
| BINARY_SUBSCR | 740 | 11.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 340 | 5.2% |
| BINARY_SUBSCR_TUPLE_INT | 300 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 2,540 | 39.1% |
| FOR_ITER_LIST | 1,900 | 29.2% |
| FOR_ITER_RANGE | 1,260 | 19.4% |
| FOR_ITER | 780 | 12.0% |
| LOAD_FAST_AND_CLEAR | 20 | 0.3% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,180 | 81.1% |
| RETURN_CONST | 1,440 | 18.9% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 140 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 471,300 | 98.9% |
| STORE_FAST | 4,140 | 0.9% |
| RESUME_CHECK | 240 | 0.1% |
| NOP | 220 | 0.0% |
| STORE_FAST_STORE_FAST | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 470,820 | 98.8% |
| LOAD_FAST | 4,940 | 1.0% |
| NOP | 220 | 0.0% |
| LOAD_CONST | 180 | 0.0% |
| BUILD_LIST | 120 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 470,740 | 99.9% |
| STORE_ATTR_INSTANCE_VALUE | 340 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 470,740 | 99.9% |
| RETURN_CONST | 340 | 0.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 473,740 | 48.7% |
| POP_JUMP_IF_FALSE | 471,980 | 48.6% |
| RETURN_CONST | 12,840 | 1.3% |
| CALL_BUILTIN_O | 12,340 | 1.3% |
| POP_JUMP_IF_TRUE | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 470,740 | 48.4% |
| LOAD_FAST | 442,800 | 45.6% |
| ENTER_EXECUTOR | 48,680 | 5.0% |
| EXTENDED_ARG | 3,220 | 0.3% |
| JUMP_FORWARD | 1,680 | 0.2% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 470,740 | 99.9% |
| BINARY_SUBSCR_STR_INT | 340 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 471,080 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 449,460 | 99.3% |
| LOAD_ATTR_MODULE | 1,940 | 0.4% |
| STORE_FAST_LOAD_FAST | 1,020 | 0.2% |
| LOAD_DEREF | 160 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 425,680 | 94.0% |
| LOAD_FAST | 13,280 | 2.9% |
| LOAD_CONST | 6,460 | 1.4% |
| LOAD_GLOBAL_MODULE | 5,660 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,240 | 0.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 477,040 | 49.3% |
| CALL | 470,740 | 48.6% |
| BINARY_SUBSCR_LIST_INT | 7,960 | 0.8% |
| CALL_LEN | 3,680 | 0.4% |
| RETURN_VALUE | 1,660 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 473,740 | 48.9% |
| LOAD_ATTR_METHOD_NO_DICT | 470,380 | 48.6% |
| INTERPRETER_EXIT | 6,180 | 0.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,840 | 0.5% |
| STORE_FAST | 4,760 | 0.5% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460 | 34.3% |
| LOAD_FAST_LOAD_FAST | 460 | 34.3% |
| LOAD_CONST | 400 | 29.9% |
| STORE_SUBSCR | 20 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 460 | 34.3% |
| EXTENDED_ARG | 400 | 29.9% |
| ENTER_EXECUTOR | 240 | 17.9% |
| JUMP_FORWARD | 220 | 16.4% |
| STORE_SUBSCR | 20 | 1.5% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,420 | 60.7% |
| BINARY_OP | 360 | 15.4% |
| LOAD_ATTR | 340 | 14.5% |
| TO_BOOL | 100 | 4.3% |
| LOAD_GLOBAL | 40 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,580 | 67.5% |
| POP_JUMP_IF_TRUE | 540 | 23.1% |
| TO_BOOL | 100 | 4.3% |
| TO_BOOL_INT | 60 | 2.6% |
| TO_BOOL_BOOL | 40 | 1.7% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 200 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 560 | 58.3% |
| TO_BOOL_LIST | 400 | 41.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 560 | 58.3% |
| CALL_PY_EXACT_ARGS | 400 | 41.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,180 | 37.1% |
| LOAD_FAST | 6,260 | 32.3% |
| BINARY_OP | 3,020 | 15.6% |
| LOAD_FAST_LOAD_FAST | 1,000 | 5.2% |
| LOAD_CONST | 880 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 6,020 | 31.1% |
| LOAD_CONST | 3,700 | 19.1% |
| BINARY_OP | 3,020 | 15.6% |
| BINARY_OP_ADD_UNICODE | 2,940 | 15.2% |
| STORE_FAST | 1,520 | 7.9% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,300 | 26.0% |
| STORE_FAST | 1,080 | 21.6% |
| POP_JUMP_IF_NOT_NONE | 860 | 17.2% |
| LOAD_CONST | 780 | 15.6% |
| POP_JUMP_IF_FALSE | 400 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,980 | 79.6% |
| LOAD_FAST | 680 | 13.6% |
| STORE_DEREF | 140 | 2.8% |
| LOAD_GLOBAL_BUILTIN | 100 | 2.0% |
| LOAD_DEREF | 80 | 1.6% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 680 | 97.1% |
| SWAP | 20 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680 | 97.1% |
| SWAP | 20 | 2.9% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 740 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 740 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 942,420 | 99.1% |
| CALL_BUILTIN_O | 2,820 | 0.3% |
| LOAD_FAST | 1,860 | 0.2% |
| BUILD_TUPLE | 1,200 | 0.1% |
| CALL | 1,160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 471,260 | 49.6% |
| BINARY_SUBSCR_DICT | 470,820 | 49.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,920 | 0.3% |
| LOAD_FAST | 1,560 | 0.2% |
| BUILD_TUPLE | 1,200 | 0.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 472,000 | 98.6% |
| LOAD_GLOBAL_MODULE | 2,320 | 0.5% |
| LOAD_FAST_LOAD_FAST | 1,040 | 0.2% |
| BINARY_OP | 780 | 0.2% |
| LOAD_CONST | 640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 470,740 | 98.3% |
| STORE_FAST | 2,820 | 0.6% |
| BUILD_TUPLE | 1,160 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 1,160 | 0.2% |
| RESUME_CHECK | 620 | 0.1% |


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

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,560 | 78.8% |
| LOAD_FAST | 240 | 12.1% |
| COMPARE_OP | 100 | 5.1% |
| LOAD_ATTR | 40 | 2.0% |
| COMPARE_OP_STR | 20 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,380 | 69.7% |
| POP_JUMP_IF_TRUE | 480 | 24.2% |
| COMPARE_OP | 100 | 5.1% |
| COPY | 20 | 1.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,040 | 66.1% |
| LOAD_FAST_LOAD_FAST | 3,240 | 26.6% |
| LOAD_CONST | 860 | 7.1% |
| LOAD_GLOBAL | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,540 | 70.2% |
| EXTENDED_ARG | 3,300 | 27.1% |
| RETURN_VALUE | 320 | 2.6% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,340 | 37.6% |
| LOAD_CONST | 1,160 | 32.6% |
| UNARY_NOT | 560 | 15.7% |
| BINARY_OP | 220 | 6.2% |
| LOAD_FAST | 220 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 1,340 | 37.6% |
| STORE_FAST_STORE_FAST | 1,160 | 32.6% |
| TO_BOOL_BOOL | 600 | 16.9% |
| TO_BOOL_INT | 440 | 12.4% |
| TO_BOOL | 20 | 0.6% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,520 | 83.4% |
| CALL | 420 | 13.9% |
| CALL_FUNCTION_EX | 80 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,980 | 98.7% |
| RESUME | 40 | 1.3% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 48,680 | 76.8% |
| EXTENDED_ARG | 6,820 | 10.8% |
| CALL_LIST_APPEND | 3,060 | 4.8% |
| POP_JUMP_IF_TRUE | 2,920 | 4.6% |
| STORE_FAST | 960 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 46,400 | 73.2% |
| EXTENDED_ARG | 3,480 | 5.5% |
| CALL_LIST_APPEND | 2,500 | 3.9% |
| LOAD_CONST | 2,380 | 3.8% |
| POP_JUMP_IF_FALSE | 2,340 | 3.7% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 4,040 | 17.2% |
| ENTER_EXECUTOR | 3,480 | 14.8% |
| CONTAINS_OP | 3,300 | 14.1% |
| POP_TOP | 3,220 | 13.7% |
| STORE_FAST | 2,600 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,820 | 29.1% |
| POP_JUMP_IF_FALSE | 5,500 | 23.5% |
| JUMP_FORWARD | 4,520 | 19.3% |
| FOR_ITER | 3,420 | 14.6% |
| FOR_ITER_LIST | 2,760 | 11.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,420 | 78.4% |
| GET_ITER | 780 | 17.9% |
| JUMP_BACKWARD | 100 | 2.3% |
| FOR_ITER | 40 | 0.9% |
| SWAP | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,420 | 55.5% |
| RETURN_CONST | 1,000 | 22.9% |
| LOAD_FAST | 340 | 7.8% |
| LOAD_GLOBAL_MODULE | 340 | 7.8% |
| STORE_FAST | 60 | 1.4% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,120 | 94.4% |
| LOAD_FAST | 340 | 2.4% |
| LOAD_GLOBAL_BUILTIN | 340 | 2.4% |
| LOAD_CONST | 60 | 0.4% |
| LOAD_GLOBAL | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,680 | 76.8% |
| POP_JUMP_IF_TRUE | 3,160 | 22.7% |
| COPY | 40 | 0.3% |
| RETURN_VALUE | 20 | 0.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 940 | 29.6% |
| CALL_LIST_APPEND | 660 | 20.8% |
| EXTENDED_ARG | 420 | 13.2% |
| FOR_ITER_LIST | 320 | 10.1% |
| STORE_FAST | 220 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,420 | 44.7% |
| FOR_ITER_RANGE | 660 | 20.8% |
| EXTENDED_ARG | 520 | 16.4% |
| FOR_ITER_TUPLE | 240 | 7.5% |
| ENTER_EXECUTOR | 160 | 5.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 470,740 | 98.1% |
| EXTENDED_ARG | 4,520 | 0.9% |
| POP_TOP | 1,680 | 0.4% |
| STORE_FAST | 1,280 | 0.3% |
| POP_JUMP_IF_TRUE | 560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 472,140 | 98.4% |
| EXTENDED_ARG | 4,040 | 0.8% |
| LOAD_FAST | 2,300 | 0.5% |
| LOAD_GLOBAL_MODULE | 740 | 0.2% |
| LOAD_FAST_LOAD_FAST | 360 | 0.1% |


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
| LOAD_FAST | 6,980 | 88.6% |
| LOAD_ATTR | 280 | 3.6% |
| LOAD_GLOBAL_MODULE | 220 | 2.8% |
| LOAD_GLOBAL_BUILTIN | 160 | 2.0% |
| LOAD_GLOBAL | 140 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,900 | 74.9% |
| LOAD_FAST | 580 | 7.4% |
| LOAD_FAST_LOAD_FAST | 380 | 4.8% |
| TO_BOOL | 340 | 4.3% |
| LOAD_ATTR | 280 | 3.6% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 498,220 | 92.0% |
| PUSH_NULL | 6,460 | 1.2% |
| STORE_FAST | 6,460 | 1.2% |
| BINARY_SUBSCR_STR_INT | 3,860 | 0.7% |
| BINARY_OP | 3,700 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 470,740 | 86.9% |
| COMPARE_OP_STR | 10,020 | 1.9% |
| BINARY_OP_ADD_INT | 9,940 | 1.8% |
| LOAD_FAST | 9,580 | 1.8% |
| BINARY_SUBSCR_TUPLE_INT | 6,680 | 1.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,940 | 88.6% |
| POP_TOP | 140 | 4.2% |
| NOP | 80 | 2.4% |
| BUILD_LIST | 80 | 2.4% |
| RESUME_CHECK | 60 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,900 | 87.3% |
| PUSH_NULL | 160 | 4.8% |
| RETURN_VALUE | 140 | 4.2% |
| LIST_EXTEND | 80 | 2.4% |
| LOAD_ATTR | 40 | 1.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,905,400 | 38.9% |
| POP_JUMP_IF_FALSE | 997,160 | 20.4% |
| LOAD_ATTR_METHOD_NO_DICT | 947,780 | 19.4% |
| STORE_FAST | 500,400 | 10.2% |
| POP_TOP | 442,800 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 972,340 | 19.9% |
| CALL_TYPE_1 | 941,900 | 19.2% |
| LOAD_CONST | 498,220 | 10.2% |
| RETURN_VALUE | 477,040 | 9.7% |
| TO_BOOL_INT | 475,240 | 9.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 20 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 60 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TYPE_1 | 941,560 | 50.5% |
| LOAD_GLOBAL_MODULE | 474,780 | 25.5% |
| PUSH_NULL | 425,680 | 22.8% |
| STORE_ATTR_INSTANCE_VALUE | 5,260 | 0.3% |
| RESUME_CHECK | 4,340 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 942,420 | 50.5% |
| CALL_PY_EXACT_ARGS | 472,780 | 25.4% |
| CALL_PY_WITH_DEFAULTS | 423,940 | 22.7% |
| STORE_ATTR_INSTANCE_VALUE | 8,460 | 0.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,580 | 0.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 460 | 39.0% |
| STORE_FAST | 180 | 15.3% |
| LOAD_FAST | 100 | 8.5% |
| RESUME | 80 | 6.8% |
| RESUME_CHECK | 80 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 420 | 35.6% |
| LOAD_GLOBAL_MODULE | 240 | 20.3% |
| LOAD_ATTR | 140 | 11.9% |
| LOAD_FAST | 100 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 60 | 5.1% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 120 | 85.7% |
| CALL | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 85.7% |
| RESUME | 20 | 14.3% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 140 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 957,620 | 49.0% |
| TO_BOOL_INT | 477,780 | 24.4% |
| CHECK_EXC_MATCH | 471,080 | 24.1% |
| COMPARE_OP_STR | 11,060 | 0.6% |
| IS_OP | 10,680 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 997,160 | 51.0% |
| POP_TOP | 471,980 | 24.1% |
| NOP | 471,300 | 24.1% |
| LOAD_GLOBAL_MODULE | 4,000 | 0.2% |
| LOAD_DEREF | 2,940 | 0.2% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,620 | 67.5% |
| LOAD_FAST | 760 | 31.7% |
| LOAD_ATTR | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,160 | 48.3% |
| LOAD_FAST | 1,080 | 45.0% |
| ENTER_EXECUTOR | 80 | 3.3% |
| LOAD_GLOBAL_BUILTIN | 60 | 2.5% |
| RETURN_CONST | 20 | 0.8% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 474,540 | 99.9% |
| ENTER_EXECUTOR | 440 | 0.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 470,800 | 99.1% |
| LOAD_FAST | 2,160 | 0.5% |
| BUILD_LIST | 860 | 0.2% |
| LOAD_FAST_LOAD_FAST | 400 | 0.1% |
| LOAD_GLOBAL_MODULE | 380 | 0.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 3,420 | 29.6% |
| IS_OP | 3,160 | 27.3% |
| TO_BOOL_BOOL | 2,020 | 17.5% |
| TO_BOOL_STR | 1,340 | 11.6% |
| TO_BOOL_LIST | 600 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,500 | 38.9% |
| ENTER_EXECUTOR | 2,920 | 25.3% |
| CALL_LEN | 1,220 | 10.6% |
| RETURN_CONST | 640 | 5.5% |
| LOAD_GLOBAL_MODULE | 580 | 5.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 6,180 | 33.2% |
| CALL_LIST_APPEND | 6,040 | 32.4% |
| POP_JUMP_IF_FALSE | 1,900 | 10.2% |
| POP_TOP | 1,320 | 7.1% |
| FOR_ITER | 1,000 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,840 | 68.9% |
| TO_BOOL_BOOL | 2,300 | 12.3% |
| INTERPRETER_EXIT | 1,440 | 7.7% |
| EXIT_INIT_CHECK | 1,080 | 5.8% |
| STORE_FAST | 980 | 5.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 140 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 20 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 471,260 | 46.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 470,780 | 46.8% |
| LOAD_CONST | 6,620 | 0.7% |
| LOAD_ATTR | 5,900 | 0.6% |
| LOAD_GLOBAL_MODULE | 5,840 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 500,400 | 49.8% |
| LOAD_GLOBAL_MODULE | 477,100 | 47.5% |
| LOAD_CONST | 6,460 | 0.6% |
| STORE_FAST | 4,900 | 0.5% |
| NOP | 4,140 | 0.4% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,020 | 87.9% |
| FOR_ITER_TUPLE | 120 | 10.3% |
| FOR_ITER | 20 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,020 | 87.9% |
| LOAD_GLOBAL_MODULE | 100 | 8.6% |
| LOAD_GLOBAL | 40 | 3.4% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 7,220 | 80.4% |
| COPY | 1,160 | 12.9% |
| UNPACK_SEQUENCE_TUPLE | 480 | 5.3% |
| STORE_FAST_STORE_FAST | 80 | 0.9% |
| UNPACK_SEQUENCE | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,940 | 55.0% |
| LOAD_FAST_LOAD_FAST | 2,960 | 33.0% |
| STORE_FAST | 400 | 4.5% |
| LOAD_GLOBAL_BUILTIN | 300 | 3.3% |
| NOP | 220 | 2.4% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 20 | 50.0% |
| LOAD_FAST_AND_CLEAR | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 20 | 50.0% |
| FOR_ITER | 20 | 50.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 20 | 25.0% |
| RETURN_VALUE | 20 | 25.0% |
| FOR_ITER | 20 | 25.0% |
| FOR_ITER_LIST | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 40 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 100 | 55.6% |
| COPY_FREE_VARS | 40 | 22.2% |
| CALL_FUNCTION_EX | 20 | 11.1% |
| MAKE_CELL | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 80 | 44.4% |
| LOAD_FAST | 40 | 22.2% |
| BUILD_LIST | 20 | 11.1% |
| LOAD_DEREF | 20 | 11.1% |
| LOAD_FAST_LOAD_FAST | 20 | 11.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,940 | 91.7% |
| LOAD_FAST_LOAD_FAST | 480 | 4.4% |
| BINARY_OP_MULTIPLY_INT | 400 | 3.7% |
| BINARY_OP | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,140 | 47.4% |
| STORE_FAST | 5,060 | 46.7% |
| CALL_BUILTIN_CLASS | 240 | 2.2% |
| CALL_PY_EXACT_ARGS | 220 | 2.0% |
| CALL_BUILTIN_O | 120 | 1.1% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,940 | 58.3% |
| LOAD_CONST | 2,100 | 41.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,520 | 50.0% |
| CALL_PY_EXACT_ARGS | 2,100 | 41.7% |
| CALL | 420 | 8.3% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 400 | 62.5% |
| LOAD_CONST | 240 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 400 | 62.5% |
| LOAD_CONST | 120 | 18.8% |
| CALL_BUILTIN_O | 120 | 18.8% |


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

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,680 | 39.6% |
| CALL_LEN | 1,340 | 31.6% |
| LOAD_CONST | 1,220 | 28.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,340 | 31.6% |
| LOAD_FAST_LOAD_FAST | 1,200 | 28.3% |
| LOAD_CONST | 600 | 14.2% |
| LOAD_FAST | 460 | 10.8% |
| STORE_FAST | 380 | 9.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 470,820 | 99.7% |
| LOAD_FAST_LOAD_FAST | 900 | 0.2% |
| LOAD_FAST | 340 | 0.1% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 470,740 | 99.7% |
| LOAD_CONST | 480 | 0.1% |
| LOAD_FAST | 440 | 0.1% |
| RETURN_VALUE | 420 | 0.1% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,260 | 43.6% |
| LOAD_CONST | 2,140 | 41.3% |
| LOAD_FAST | 760 | 14.7% |
| BINARY_SUBSCR | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,180 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,820 | 86.8% |
| LOAD_CONST | 740 | 7.3% |
| LOAD_FAST_LOAD_FAST | 500 | 4.9% |
| BINARY_SUBSCR | 40 | 0.4% |
| BINARY_OP_SUBTRACT_INT | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,960 | 85.8% |
| STORE_FAST | 920 | 9.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 260 | 2.8% |
| LOAD_CONST | 40 | 0.4% |
| LOAD_FAST_LOAD_FAST | 40 | 0.4% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,860 | 60.1% |
| LOAD_FAST | 2,340 | 36.4% |
| ENTER_EXECUTOR | 220 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,860 | 60.1% |
| STORE_FAST | 2,200 | 34.3% |
| PUSH_EXC_INFO | 340 | 5.3% |
| BINARY_OP_INPLACE_ADD_UNICODE | 20 | 0.3% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,680 | 99.7% |
| BINARY_SUBSCR | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,160 | 32.2% |
| CALL_BUILTIN_O | 1,720 | 25.7% |
| LOAD_FAST | 640 | 9.6% |
| STORE_FAST | 480 | 7.2% |
| BINARY_OP_MULTIPLY_INT | 400 | 6.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 400 | 37.0% |
| LOAD_FAST | 340 | 31.5% |
| LOAD_GLOBAL_MODULE | 340 | 31.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,080 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 2,920 | 45.8% |
| LOAD_CONST | 2,200 | 34.5% |
| PUSH_NULL | 1,240 | 19.4% |
| LOAD_FAST | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,380 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 940 | 66.2% |
| BINARY_OP_ADD_INT | 240 | 16.9% |
| CALL_BUILTIN_FAST | 160 | 11.3% |
| CALL | 40 | 2.8% |
| LOAD_FAST | 40 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 740 | 52.1% |
| STORE_FAST | 300 | 21.1% |
| GET_ITER | 220 | 15.5% |
| RETURN_VALUE | 160 | 11.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 160 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 340 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,400 | 55.4% |
| LOAD_GLOBAL_MODULE | 1,940 | 12.8% |
| BINARY_SUBSCR_TUPLE_INT | 1,720 | 11.3% |
| LOAD_CONST | 1,320 | 8.7% |
| RETURN_VALUE | 740 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,340 | 81.4% |
| BUILD_TUPLE | 2,820 | 18.6% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 941,560 | 98.9% |
| LOAD_GLOBAL_BUILTIN | 9,480 | 1.0% |
| BUILD_TUPLE | 680 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 340 | 0.0% |
| LOAD_ATTR_SLOT | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 951,380 | 99.9% |
| RETURN_VALUE | 680 | 0.1% |
| LOAD_FAST | 340 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,900 | 50.8% |
| LOAD_ATTR_INSTANCE_VALUE | 3,680 | 31.7% |
| POP_JUMP_IF_TRUE | 1,220 | 10.5% |
| LOAD_GLOBAL_MODULE | 680 | 5.9% |
| LOAD_CONST | 120 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,680 | 31.7% |
| LOAD_CONST | 1,560 | 13.4% |
| BINARY_OP_SUBTRACT_INT | 1,340 | 11.5% |
| LOAD_FAST | 1,320 | 11.4% |
| STORE_FAST_LOAD_FAST | 1,020 | 8.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,020 | 58.9% |
| ENTER_EXECUTOR | 2,500 | 24.5% |
| BUILD_TUPLE | 1,200 | 11.7% |
| LOAD_GLOBAL_MODULE | 340 | 3.3% |
| LOAD_CONST | 120 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,040 | 59.1% |
| ENTER_EXECUTOR | 3,060 | 29.9% |
| JUMP_BACKWARD | 660 | 6.5% |
| LOAD_FAST | 460 | 4.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 470,740 | 100.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 470,780 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 340 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 61.5% |
| RETURN_VALUE | 100 | 38.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 260 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 472,780 | 97.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,680 | 1.0% |
| LOAD_FAST | 3,260 | 0.7% |
| BINARY_OP_ADD_UNICODE | 2,100 | 0.4% |
| LOAD_CONST | 560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 482,940 | 99.5% |
| COPY_FREE_VARS | 2,520 | 0.5% |
| MAKE_CELL | 120 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 423,940 | 90.0% |
| ENTER_EXECUTOR | 46,400 | 9.8% |
| LOAD_FAST | 640 | 0.1% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 471,200 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 340 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 941,900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 941,560 | 100.0% |
| LOAD_FAST | 340 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,320 | 71.9% |
| LOAD_GLOBAL_MODULE | 800 | 17.3% |
| LOAD_FAST | 240 | 5.2% |
| CALL_LEN | 220 | 4.8% |
| BINARY_SUBSCR_LIST_INT | 40 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,620 | 100.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,020 | 80.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,400 | 19.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 11,060 | 89.0% |
| EXTENDED_ARG | 1,340 | 10.8% |
| COMPARE_OP | 20 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 2,760 | 39.7% |
| GET_ITER | 1,900 | 27.3% |
| JUMP_BACKWARD | 1,420 | 20.4% |
| ENTER_EXECUTOR | 840 | 12.1% |
| FOR_ITER | 40 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,120 | 44.8% |
| LOAD_GLOBAL_BUILTIN | 1,160 | 16.7% |
| STORE_FAST | 1,100 | 15.8% |
| LOAD_FAST | 520 | 7.5% |
| LOAD_FAST_LOAD_FAST | 380 | 5.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,260 | 40.9% |
| ENTER_EXECUTOR | 1,120 | 36.4% |
| JUMP_BACKWARD | 660 | 21.4% |
| FOR_ITER | 40 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,780 | 57.8% |
| LOAD_FAST | 840 | 27.3% |
| JUMP_FORWARD | 240 | 7.8% |
| JUMP_BACKWARD | 140 | 4.5% |
| LOAD_GLOBAL | 40 | 1.3% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 85.7% |
| FOR_ITER | 40 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 140 | 50.0% |
| STORE_FAST_LOAD_FAST | 120 | 42.9% |
| LOAD_FAST | 20 | 7.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,920 | 86.5% |
| LOAD_FAST_LOAD_FAST | 3,580 | 9.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,700 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,920 | 33.0% |
| STORE_FAST | 4,980 | 12.7% |
| CALL_LEN | 3,680 | 9.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,240 | 8.3% |
| COMPARE_OP_STR | 2,400 | 6.1% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 470,780 | 49.5% |
| RETURN_VALUE | 470,380 | 49.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,240 | 0.3% |
| LOAD_DEREF | 2,900 | 0.3% |
| LOAD_FAST | 2,760 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 947,780 | 99.8% |
| LOAD_GLOBAL_MODULE | 820 | 0.1% |
| LOAD_CONST | 740 | 0.1% |
| LOAD_FAST_LOAD_FAST | 440 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 340 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,880 | 91.7% |
| BINARY_SUBSCR_TUPLE_INT | 320 | 6.0% |
| BINARY_SUBSCR | 120 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,680 | 88.0% |
| LOAD_FAST | 300 | 5.6% |
| LOAD_CONST | 220 | 4.1% |
| LOAD_GLOBAL_MODULE | 120 | 2.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,900 | 95.0% |
| LOAD_ATTR | 100 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,940 | 97.0% |
| STORE_FAST | 60 | 3.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 340 | 50.0% |
| LOAD_FAST_LOAD_FAST | 340 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 340 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 340 | 50.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 680 | 73.9% |
| LOAD_FAST | 240 | 26.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 920 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 340 | 50.0% |
| LOAD_FAST_LOAD_FAST | 340 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 340 | 50.0% |
| CALL_ISINSTANCE | 340 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 485,820 | 20.3% |
| JUMP_FORWARD | 472,140 | 19.7% |
| PUSH_EXC_INFO | 471,080 | 19.7% |
| LOAD_GLOBAL_MODULE | 470,820 | 19.7% |
| POP_JUMP_IF_NOT_NONE | 470,800 | 19.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,905,400 | 79.6% |
| CHECK_EXC_MATCH | 471,080 | 19.7% |
| CALL_ISINSTANCE | 9,480 | 0.4% |
| STORE_FAST | 2,640 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 1,680 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 972,340 | 40.3% |
| STORE_FAST | 477,100 | 19.8% |
| RESUME_CHECK | 475,440 | 19.7% |
| NOP | 470,820 | 19.5% |
| PUSH_NULL | 5,660 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 941,560 | 39.0% |
| LOAD_FAST_LOAD_FAST | 474,780 | 19.7% |
| LOAD_GLOBAL_BUILTIN | 470,820 | 19.5% |
| LOAD_ATTR_METHOD_NO_DICT | 470,780 | 19.5% |
| IS_OP | 13,120 | 0.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 482,940 | 49.3% |
| CALL_PY_WITH_DEFAULTS | 471,200 | 48.1% |
| CACHE | 8,500 | 0.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,380 | 0.7% |
| BINARY_SUBSCR_GETITEM | 5,180 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 485,820 | 49.6% |
| LOAD_GLOBAL_MODULE | 475,440 | 48.5% |
| LOAD_FAST | 12,700 | 1.3% |
| LOAD_FAST_LOAD_FAST | 4,340 | 0.4% |
| BUILD_LIST | 1,300 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,060 | 53.3% |
| LOAD_FAST_LOAD_FAST | 8,460 | 44.9% |
| LOAD_ATTR_INSTANCE_VALUE | 340 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,180 | 32.8% |
| LOAD_FAST_LOAD_FAST | 5,260 | 27.9% |
| LOAD_FAST | 3,440 | 18.2% |
| LOAD_CONST | 2,620 | 13.9% |
| BUILD_MAP | 680 | 3.6% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 340 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 340 | 50.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,240 | 83.8% |
| LOAD_FAST | 240 | 16.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 480 | 32.4% |
| ENTER_EXECUTOR | 460 | 31.1% |
| RETURN_CONST | 460 | 31.1% |
| LOAD_FAST | 80 | 5.4% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 951,380 | 99.1% |
| LOAD_GLOBAL_MODULE | 3,280 | 0.3% |
| RETURN_CONST | 2,300 | 0.2% |
| LOAD_FAST | 1,100 | 0.1% |
| RETURN_VALUE | 1,040 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 957,620 | 99.7% |
| POP_JUMP_IF_TRUE | 2,020 | 0.2% |
| EXTENDED_ARG | 500 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 475,240 | 98.6% |
| BINARY_OP | 6,020 | 1.2% |
| COPY | 440 | 0.1% |
| TO_BOOL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 477,780 | 99.2% |
| POP_JUMP_IF_TRUE | 3,420 | 0.7% |
| UNARY_NOT | 560 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,340 | 90.0% |
| LOAD_ATTR_INSTANCE_VALUE | 260 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,600 | 61.5% |
| POP_JUMP_IF_TRUE | 600 | 23.1% |
| UNARY_NOT | 400 | 15.4% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,080 | 98.2% |
| TO_BOOL | 20 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,100 | 100.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,340 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 400 | 48.8% |
| LOAD_FAST | 340 | 41.5% |
| BINARY_SUBSCR_TUPLE_INT | 80 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 480 | 58.5% |
| STORE_FAST | 340 | 41.5% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,840 | 45.3% |
| FOR_ITER_LIST | 3,120 | 29.2% |
| FOR_ITER | 2,420 | 22.7% |
| BINARY_SUBSCR_LIST_INT | 260 | 2.4% |
| UNPACK_SEQUENCE | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 7,220 | 67.6% |
| STORE_FAST | 3,460 | 32.4% |


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
|     deferred | 16,300 | 40.5% |
|          hit | 20,840 | 51.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 880 | 28.8% |
| Failure | 2,180 | 71.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 1,720 | 78.9% |
| and int | 320 | 14.7% |
| or | 100 | 4.6% |
| add other | 20 | 0.9% |
| and different types | 20 | 0.9% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> specialization stats for BINARY_OP_INPLACE_ADD_UNICODE family </summary>


</details>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,340 | 0.3% |
|          hit | 499,300 | 99.5% |
|         miss | 1,240 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 85.7% |
| Failure | 20 | 14.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 20 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 477,340 | 12.4% |
|          hit | 3,375,400 | 87.6% |
|         miss | 160 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 800 | 61.5% |
| Failure | 500 | 38.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 300 | 60.0% |
| cfunc noargs | 60 | 12.0% |
| wrong number arguments | 40 | 8.0% |
| cfunc varargs keywords | 40 | 8.0% |
| meth descr varargs | 40 | 8.0% |
| class mutable | 20 | 4.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,860 | 9.8% |
|          hit | 16,480 | 86.6% |
|         miss | 560 | 2.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 120 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 40 | 33.3% |
| different types | 40 | 33.3% |
| big int | 40 | 33.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,200 | 28.6% |
|          hit | 10,320 | 70.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 75.0% |
| Failure | 40 | 25.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict keys | 20 | 50.0% |
| seq iter | 20 | 50.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,460 | 0.7% |
|          hit | 998,920 | 99.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 38.1% |
| Failure | 260 | 61.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 140 | 53.8% |
| metaclass attribute | 60 | 23.1% |
| not managed dict | 40 | 15.4% |
| builtin class method | 20 | 7.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 880 | 0.0% |
|          hit | 4,808,180 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 300 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>


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
|     deferred | 20 | 0.1% |
|          hit | 18,860 | 99.9% |


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,320 | 37.7% |
|          hit | 2,160 | 61.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytearray int | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,120 | 0.1% |
|          hit | 1,446,460 | 99.8% |
|         miss | 480 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 54.5% |
| Failure | 100 | 45.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 60 | 60.0% |
| dict | 20 | 20.0% |
| number | 20 | 20.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.3% |
|          hit | 11,500 | 99.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 14,201,240 | 48.4% |
| Not specialized | 2,963,080 | 10.1% |
| Specialized hits | 12,182,440 | 41.5% |
| Specialized misses | 2,440 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 477,340 | 93.1% |
| BINARY_OP | 16,300 | 3.2% |
| LOAD_ATTR | 7,460 | 1.5% |
| FOR_ITER | 4,200 | 0.8% |
| TO_BOOL | 2,120 | 0.4% |
| COMPARE_OP | 1,860 | 0.4% |
| BINARY_SUBSCR | 1,340 | 0.3% |
| STORE_SUBSCR | 1,320 | 0.3% |
| LOAD_GLOBAL | 880 | 0.2% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 900 | 36.9% |
| COMPARE_OP_STR | 560 | 23.0% |
| TO_BOOL_LIST | 360 | 14.8% |
| BINARY_SUBSCR_STR_INT | 340 | 13.9% |
| CALL_BUILTIN_FAST | 160 | 6.6% |
| TO_BOOL_STR | 120 | 4.9% |
| CACHE | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |
| DELETE_SUBSCR | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 8,500 | 0.9% |
| Calls to Python functions inlined | 971,660 | 99.1% |
| Calls via PyEval_EvalFrame (total) | 8,500 | 0.9% |
| Calls via PyEval_EvalFrame (vector) | 8,500 | 0.9% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,500 | 0.9% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 7,260 | 0.7% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 40 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 472,840 | 48.2% |
| Frames pushed | 977,820 | 99.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,436,360 | 0.7% |
| Frees to freelist | 1,435,320 |  |
| Allocations | 211,661,080 | 99.3% |
| Allocations to 512 bytes | 211,655,460 | 99.3% |
| Allocations to 4 kbytes | 2,260 | 0.0% |
| Allocations over 4 kbytes | 3,360 | 0.0% |
| Frees | 212,084,327 |  |
| New values | 860 |  |
| Interpreter increfs | 12,854,860 | 69.6% |
| Interpreter decrefs | 13,351,200 | 59.9% |
| Increfs | 5,617,572 | 30.4% |
| Decrefs | 8,940,683 | 40.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 8,173 |  |
| Method cache misses | 87 |  |
| Method cache collisions | 121 |  |
| Method cache dunder hits | 960,308 |  |
| Method cache dunder misses | 52 |  |


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
| Optimization attempts | 160 |  |
| Traces created | 160 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 63,380 |  |
| Uops executed | 1,007,220 | 15.89 |

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
| <= 32 | 40 | 25.0% |
| <= 64 | 40 | 25.0% |
| <= 128 | 80 | 50.0% |


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
| <= 16 | 40 | 25.0% |
| <= 32 | 60 | 37.5% |
| <= 64 | 60 | 37.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 1,720 | 2.7% |
| <= 2 | 2,040 | 3.2% |
| <= 4 | 840 | 1.3% |
| <= 8 | 740 | 1.2% |
| <= 16 | 49,800 | 78.6% |
| <= 32 | 4,420 | 7.0% |
| <= 64 | 580 | 0.9% |
| <= 128 | 2,900 | 4.6% |
| <= 256 | 120 | 0.2% |
| <= 512 | 220 | 0.3% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 227,980 | 22.6% | 22.6% |  |
| STORE_FAST | 128,360 | 12.7% | 35.4% |  |
| _EXIT_TRACE | 54,780 | 5.4% | 40.8% |  |
| _ITER_CHECK_LIST | 54,520 | 5.4% | 46.2% | 3.2% |
| _GUARD_NOT_EXHAUSTED_LIST | 52,800 | 5.2% | 51.5% | 4.2% |
| PUSH_NULL | 51,080 | 5.1% | 56.5% |  |
| _ITER_NEXT_LIST | 50,560 | 5.0% | 61.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 50,000 | 5.0% | 66.5% |  |
| _SET_IP | 48,120 | 4.8% | 71.3% |  |
| _CHECK_VALIDITY | 44,020 | 4.4% | 75.7% |  |
| _GUARD_TYPE_VERSION | 18,580 | 1.8% | 77.5% |  |
| _GUARD_IS_FALSE_POP | 14,500 | 1.4% | 79.0% | 7.6% |
| LOAD_CONST | 13,720 | 1.4% | 80.3% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 11,980 | 1.2% | 81.5% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 11,980 | 1.2% | 82.7% |  |
| _GUARD_GLOBALS_VERSION | 10,940 | 1.1% | 83.8% |  |
| _LOAD_GLOBAL_MODULE | 10,860 | 1.1% | 84.9% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 10,660 | 1.1% | 85.9% | 10.5% |
| _ITER_CHECK_RANGE | 10,660 | 1.1% | 87.0% |  |
| _ITER_NEXT_RANGE | 9,540 | 0.9% | 87.9% |  |
| IS_OP | 7,280 | 0.7% | 88.7% |  |
| CONTAINS_OP | 6,600 | 0.7% | 89.3% |  |
| _CHECK_PEP_523 | 6,400 | 0.6% | 89.9% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 6,400 | 0.6% | 90.6% |  |
| _CHECK_STACK_SPACE | 6,400 | 0.6% | 91.2% |  |
| _INIT_CALL_PY_EXACT_ARGS | 6,400 | 0.6% | 91.8% |  |
| _PUSH_FRAME | 6,400 | 0.6% | 92.5% |  |
| _SAVE_RETURN_OFFSET | 6,400 | 0.6% | 93.1% |  |
| _JUMP_TO_TOP | 6,240 | 0.6% | 93.7% |  |
| RESUME_CHECK | 5,960 | 0.6% | 94.3% |  |
| BINARY_SUBSCR_LIST_INT | 5,440 | 0.5% | 94.9% |  |
| _STORE_SUBSCR | 4,720 | 0.5% | 95.3% |  |
| _GUARD_IS_TRUE_POP | 3,360 | 0.3% | 95.7% | 47.6% |
| _GUARD_IS_NOT_NONE_POP | 3,340 | 0.3% | 96.0% | 10.2% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 3,140 | 0.3% | 96.3% |  |
| _GUARD_KEYS_VERSION | 3,140 | 0.3% | 96.6% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 3,140 | 0.3% | 96.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 2,900 | 0.3% | 97.2% |  |
| BINARY_SUBSCR_STR_INT | 2,880 | 0.3% | 97.5% | 7.6% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 2,880 | 0.3% | 97.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 2,880 | 0.3% | 98.1% |  |
| COMPARE_OP_STR | 2,660 | 0.3% | 98.3% |  |
| BUILD_TUPLE | 2,520 | 0.3% | 98.6% |  |
| BINARY_SUBSCR_DICT | 2,480 | 0.2% | 98.8% |  |
| _GUARD_BOTH_INT | 1,980 | 0.2% | 99.0% |  |
| _BINARY_OP_ADD_INT | 1,580 | 0.2% | 99.2% |  |
| POP_TOP | 1,260 | 0.1% | 99.3% |  |
| CALL_BUILTIN_O | 1,260 | 0.1% | 99.4% |  |
| TO_BOOL_INT | 580 | 0.1% | 99.5% |  |
| _GUARD_DORV_VALUES | 560 | 0.1% | 99.6% |  |
| _STORE_ATTR_INSTANCE_VALUE | 560 | 0.1% | 99.6% |  |
| CALL_LEN | 440 | 0.0% | 99.7% |  |
| COMPARE_OP_INT | 440 | 0.0% | 99.7% |  |
| _BINARY_OP_SUBTRACT_INT | 400 | 0.0% | 99.7% |  |
| _BINARY_OP | 400 | 0.0% | 99.8% |  |
| STORE_SUBSCR_LIST_INT | 340 | 0.0% | 99.8% |  |
| _POP_FRAME | 280 | 0.0% | 99.8% |  |
| _FOR_ITER_TIER_TWO | 240 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 200 | 0.0% | 99.9% |  |
| TO_BOOL_NONE | 200 | 0.0% | 99.9% |  |
| UNARY_NOT | 180 | 0.0% | 99.9% |  |
| COPY | 180 | 0.0% | 99.9% |  |
| TO_BOOL_BOOL | 180 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 100 | 0.0% | 100.0% | 100.0% |
| _TO_BOOL | 100 | 0.0% | 100.0% |  |
| _GUARD_BUILTINS_VERSION | 80 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_BUILTINS | 80 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL_LIST_APPEND | 60 |
| BINARY_SUBSCR_GETITEM | 20 |
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
Stats gathered on: 2023-11-16
