
# Pystats results

- benchmark: mako
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_CONST | 72,942,660 | 23.2% | 23.2% |  |
| LOAD_FAST | 45,272,280 | 14.4% | 37.7% |  |
| POP_TOP | 29,444,940 | 9.4% | 47.0% |  |
| CALL_BUILTIN_O | 29,353,680 | 9.4% | 56.4% |  |
| STORE_FAST | 29,300,820 | 9.3% | 65.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 29,087,280 | 9.3% | 75.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 29,061,020 | 9.3% | 84.2% |  |
| PUSH_NULL | 14,908,060 | 4.7% | 89.0% |  |
| ENTER_EXECUTOR | 14,751,340 | 4.7% | 93.7% |  |
| RETURN_VALUE | 14,746,980 | 4.7% | 98.4% |  |
| LOAD_GLOBAL_BUILTIN | 569,400 | 0.2% | 98.6% | 0.0% |
| RESUME_CHECK | 400,380 | 0.1% | 98.7% |  |
| LOAD_GLOBAL_MODULE | 346,240 | 0.1% | 98.8% |  |
| POP_JUMP_IF_FALSE | 280,080 | 0.1% | 98.9% |  |
| LOAD_FAST_LOAD_FAST | 267,660 | 0.1% | 99.0% |  |
| LOAD_ATTR | 235,000 | 0.1% | 99.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 226,220 | 0.1% | 99.1% | 1.1% |
| CALL_PY_EXACT_ARGS | 212,320 | 0.1% | 99.2% |  |
| TO_BOOL_BOOL | 204,460 | 0.1% | 99.3% |  |
| FOR_ITER_RANGE | 198,260 | 0.1% | 99.3% |  |
| CALL_ISINSTANCE | 194,640 | 0.1% | 99.4% |  |
| CALL | 158,260 | 0.1% | 99.4% |  |
| POP_JUMP_IF_TRUE | 142,580 | 0.0% | 99.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 127,580 | 0.0% | 99.5% |  |
| NOP | 111,920 | 0.0% | 99.6% |  |
| CALL_STR_1 | 105,600 | 0.0% | 99.6% |  |
| TO_BOOL | 104,780 | 0.0% | 99.6% |  |
| RETURN_CONST | 84,560 | 0.0% | 99.7% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 76,640 | 0.0% | 99.7% |  |
| POP_JUMP_IF_NONE | 74,480 | 0.0% | 99.7% |  |
| COPY | 73,200 | 0.0% | 99.7% |  |
| BUILD_TUPLE | 71,500 | 0.0% | 99.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 59,780 | 0.0% | 99.8% |  |
| LOAD_ATTR_MODULE | 49,880 | 0.0% | 99.8% | 2.5% |
| CALL_BUILTIN_FAST | 48,520 | 0.0% | 99.8% | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 44,760 | 0.0% | 99.8% |  |
| INTERPRETER_EXIT | 41,980 | 0.0% | 99.8% |  |
| BINARY_OP | 41,820 | 0.0% | 99.8% |  |
| TO_BOOL_NONE | 39,900 | 0.0% | 99.9% |  |
| BINARY_SUBSCR | 39,640 | 0.0% | 99.9% |  |
| JUMP_FORWARD | 37,900 | 0.0% | 99.9% |  |
| CONTAINS_OP | 37,660 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 35,740 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 33,460 | 0.0% | 99.9% |  |
| CALL_PY_WITH_DEFAULTS | 33,360 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 32,680 | 0.0% | 99.9% |  |
| CALL_LEN | 32,640 | 0.0% | 99.9% |  |
| COMPARE_OP_INT | 32,560 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 32,020 | 0.0% | 100.0% |  |
| LOAD_ATTR_WITH_HINT | 18,840 | 0.0% | 100.0% |  |
| LOAD_DEREF | 9,760 | 0.0% | 100.0% |  |
| STORE_ATTR | 7,640 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 5,740 | 0.0% | 100.0% |  |
| CALL_KW | 5,120 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 5,060 | 0.0% | 100.0% |  |
| GET_ITER | 4,920 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 4,800 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 4,760 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 4,440 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 3,920 | 0.0% | 100.0% |  |
| BUILD_MAP | 3,880 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 3,840 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 3,440 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,560 | 0.0% | 100.0% | 41.4% |
| JUMP_BACKWARD | 2,440 | 0.0% | 100.0% |  |
| BUILD_LIST | 2,320 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 2,000 | 0.0% | 100.0% |  |
| DICT_MERGE | 1,920 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 1,720 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 1,300 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 1,280 | 0.0% | 100.0% |  |
| LIST_EXTEND | 1,280 | 0.0% | 100.0% |  |
| MAKE_CELL | 1,280 | 0.0% | 100.0% |  |
| RESUME | 1,260 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 1,100 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 980 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 940 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_INT | 940 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 780 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 760 | 0.0% | 100.0% |  |
| IS_OP | 760 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 740 | 0.0% | 100.0% | 2.7% |
| BINARY_SLICE | 740 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 720 | 0.0% | 100.0% |  |
| IMPORT_FROM | 640 | 0.0% | 100.0% |  |
| IMPORT_NAME | 640 | 0.0% | 100.0% |  |
| STORE_DEREF | 640 | 0.0% | 100.0% |  |
| FOR_ITER | 480 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 300 | 0.0% | 100.0% | 6.7% |
| BINARY_OP_SUBTRACT_INT | 260 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 260 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 200 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 160 | 0.0% | 100.0% | 12.5% |
| COMPARE_OP | 160 | 0.0% | 100.0% |  |
| SWAP | 120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 100 | 0.0% | 100.0% |  |
| BUILD_SLICE | 80 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 80 | 0.0% | 100.0% |  |
| LOAD_ATTR_PROPERTY | 80 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 60 | 0.0% | 100.0% |  |
| UNARY_INVERT | 60 | 0.0% | 100.0% |  |
| UNARY_NOT | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 40 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 40 | 0.0% | 100.0% |  |
| POP_EXCEPT | 40 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 40 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 40 | 0.0% | 100.0% |  |
| LIST_APPEND | 40 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 40 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 40 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 40 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 40 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| CALL_BUILTIN_O POP_TOP | 29,353,400 | 9.4% | 9.4% |
| STORE_FAST LOAD_FAST | 29,116,900 | 9.3% | 18.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS STORE_FAST | 29,060,980 | 9.3% | 27.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 28,966,080 | 9.2% | 37.1% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 28,965,800 | 9.2% | 46.3% |
| LOAD_CONST LOAD_CONST | 28,940,660 | 9.2% | 55.6% |
| LOAD_FAST PUSH_NULL | 14,862,180 | 4.7% | 60.3% |
| PUSH_NULL LOAD_CONST | 14,781,340 | 4.7% | 65.0% |
| LOAD_CONST CALL_BUILTIN_O | 14,778,320 | 4.7% | 69.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 14,695,740 | 4.7% | 74.4% |
| POP_TOP ENTER_EXECUTOR | 14,655,580 | 4.7% | 79.1% |
| POP_TOP LOAD_FAST | 14,628,980 | 4.7% | 83.7% |
| RETURN_VALUE CALL_BUILTIN_O | 14,464,520 | 4.6% | 88.3% |
| LOAD_FAST RETURN_VALUE | 14,455,780 | 4.6% | 92.9% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_NO_DICT | 14,303,680 | 4.6% | 97.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 341,700 | 0.1% | 97.6% |
| RESUME_CHECK LOAD_FAST | 238,160 | 0.1% | 97.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 208,600 | 0.1% | 97.7% |
| ENTER_EXECUTOR FOR_ITER_RANGE | 193,400 | 0.1% | 97.8% |
| FOR_ITER_RANGE LOAD_FAST | 193,400 | 0.1% | 97.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 192,600 | 0.1% | 97.9% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 181,220 | 0.1% | 98.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 169,760 | 0.1% | 98.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 160,060 | 0.1% | 98.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 135,100 | 0.0% | 98.1% |
| RETURN_VALUE RETURN_VALUE | 133,120 | 0.0% | 98.2% |
| LOAD_FAST LOAD_ATTR | 129,920 | 0.0% | 98.2% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 128,040 | 0.0% | 98.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 119,400 | 0.0% | 98.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 101,460 | 0.0% | 98.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 100,640 | 0.0% | 98.4% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 99,120 | 0.0% | 98.4% |
| RETURN_VALUE STORE_FAST | 97,740 | 0.0% | 98.4% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 95,040 | 0.0% | 98.4% |
| ENTER_EXECUTOR CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 95,040 | 0.0% | 98.5% |
| LOAD_CONST LOAD_FAST | 82,260 | 0.0% | 98.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 81,300 | 0.0% | 98.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 81,140 | 0.0% | 98.6% |
| NOP LOAD_FAST | 77,220 | 0.0% | 98.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 77,100 | 0.0% | 98.6% |
| POP_TOP LOAD_CONST | 76,840 | 0.0% | 98.6% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 76,640 | 0.0% | 98.7% |
| LOAD_ATTR CALL_BOUND_METHOD_EXACT_ARGS | 75,920 | 0.0% | 98.7% |
| PUSH_NULL LOAD_GLOBAL_BUILTIN | 74,240 | 0.0% | 98.7% |
| LOAD_FAST CALL | 72,700 | 0.0% | 98.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 72,480 | 0.0% | 98.7% |
| LOAD_FAST TO_BOOL | 71,160 | 0.0% | 98.8% |
| CALL_STR_1 CALL_BUILTIN_O | 70,560 | 0.0% | 98.8% |
| TO_BOOL POP_JUMP_IF_TRUE | 69,280 | 0.0% | 98.8% |
| LOAD_FAST CALL_STR_1 | 67,920 | 0.0% | 98.8% |
| POP_JUMP_IF_FALSE LOAD_CONST | 65,540 | 0.0% | 98.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 65,460 | 0.0% | 98.9% |
| ENTER_EXECUTOR CALL | 62,440 | 0.0% | 98.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 54,280 | 0.0% | 98.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 46,280 | 0.0% | 98.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 45,380 | 0.0% | 98.9% |
| LOAD_ATTR LOAD_FAST | 45,240 | 0.0% | 99.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 44,480 | 0.0% | 99.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 44,380 | 0.0% | 99.0% |
| RETURN_CONST POP_TOP | 42,520 | 0.0% | 99.0% |
| CACHE RESUME_CHECK | 41,100 | 0.0% | 99.0% |
| CALL STORE_FAST | 40,920 | 0.0% | 99.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 40,900 | 0.0% | 99.0% |
| LOAD_CONST STORE_FAST | 40,100 | 0.0% | 99.1% |
| STORE_FAST NOP | 39,980 | 0.0% | 99.1% |
| POP_TOP RETURN_CONST | 39,760 | 0.0% | 99.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 39,760 | 0.0% | 99.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 39,220 | 0.0% | 99.1% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 39,180 | 0.0% | 99.1% |
| LOAD_CONST BINARY_SUBSCR | 39,140 | 0.0% | 99.1% |
| LOAD_FAST CALL_BUILTIN_O | 38,800 | 0.0% | 99.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 38,500 | 0.0% | 99.2% |
| POP_TOP NOP | 38,480 | 0.0% | 99.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 38,440 | 0.0% | 99.2% |
| LOAD_ATTR COPY | 38,420 | 0.0% | 99.2% |
| POP_JUMP_IF_TRUE POP_TOP | 38,420 | 0.0% | 99.2% |
| CALL_BUILTIN_FAST LOAD_FAST | 38,380 | 0.0% | 99.2% |
| TO_BOOL_NONE POP_JUMP_IF_TRUE | 38,380 | 0.0% | 99.2% |
| BINARY_SUBSCR LOAD_ATTR_INSTANCE_VALUE | 38,360 | 0.0% | 99.2% |
| COPY TO_BOOL_NONE | 38,360 | 0.0% | 99.2% |
| LOAD_ATTR CALL_BUILTIN_FAST | 38,360 | 0.0% | 99.3% |
| RETURN_CONST INTERPRETER_EXIT | 37,820 | 0.0% | 99.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 37,740 | 0.0% | 99.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 37,600 | 0.0% | 99.3% |
| LOAD_FAST BINARY_OP | 37,180 | 0.0% | 99.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 36,880 | 0.0% | 99.3% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 36,120 | 0.0% | 99.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 35,240 | 0.0% | 99.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 35,140 | 0.0% | 99.4% |
| CALL_STR_1 CALL_PY_EXACT_ARGS | 34,720 | 0.0% | 99.4% |
| STORE_FAST JUMP_FORWARD | 34,680 | 0.0% | 99.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 34,580 | 0.0% | 99.4% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 34,460 | 0.0% | 99.4% |
| TO_BOOL POP_JUMP_IF_FALSE | 34,260 | 0.0% | 99.4% |
| CALL CALL_STR_1 | 34,080 | 0.0% | 99.4% |
| JUMP_FORWARD LOAD_FAST | 34,060 | 0.0% | 99.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 33,980 | 0.0% | 99.4% |
| NOP LOAD_GLOBAL_MODULE | 33,800 | 0.0% | 99.5% |
| CALL RETURN_VALUE | 33,460 | 0.0% | 99.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 33,360 | 0.0% | 99.5% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 97.3% |
| LOAD_CONST | 20 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 600 | 81.1% |
| STORE_FAST | 60 | 8.1% |
| CALL | 40 | 5.4% |
| LOAD_CONST | 40 | 5.4% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 41,100 | 97.9% |
| MAKE_CELL | 640 | 1.5% |
| RESUME | 260 | 0.6% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 20 | 33.3% |
| LOAD_FAST_LOAD_FAST | 20 | 33.3% |
| BINARY_SUBSCR_STR_INT | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 40 | 66.7% |
| LOAD_FAST | 20 | 33.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 39,140 | 98.7% |
| BINARY_SUBSCR | 260 | 0.7% |
| LOAD_FAST | 160 | 0.4% |
| BUILD_SLICE | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 38,360 | 96.8% |
| TO_BOOL_STR | 600 | 1.5% |
| BINARY_SUBSCR | 260 | 0.7% |
| STORE_FAST | 80 | 0.2% |
| BINARY_SUBSCR_DICT | 60 | 0.2% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 40 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,040 | 82.1% |
| CALL_BUILTIN_CLASS | 700 | 14.2% |
| LOAD_ATTR_INSTANCE_VALUE | 100 | 2.0% |
| BINARY_SUBSCR | 40 | 0.8% |
| CALL | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 3,220 | 65.4% |
| FOR_ITER_LIST | 1,320 | 26.8% |
| FOR_ITER | 220 | 4.5% |
| EXTENDED_ARG | 120 | 2.4% |
| LOAD_FAST_AND_CLEAR | 40 | 0.8% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 37,820 | 90.1% |
| RETURN_VALUE | 4,160 | 9.9% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 3,840 | 80.0% |
| LOAD_FAST | 960 | 20.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 39,980 | 35.7% |
| POP_TOP | 38,480 | 34.4% |
| POP_JUMP_IF_FALSE | 32,040 | 28.6% |
| RESUME_CHECK | 1,280 | 1.1% |
| NOP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 77,220 | 69.0% |
| LOAD_GLOBAL_MODULE | 33,800 | 30.2% |
| LOAD_DEREF | 720 | 0.6% |
| LOAD_GLOBAL | 120 | 0.1% |
| NOP | 40 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 20 | 50.0% |
| STORE_ATTR_INSTANCE_VALUE | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 20 | 50.0% |
| RETURN_CONST | 20 | 50.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 29,353,400 | 99.7% |
| RETURN_CONST | 42,520 | 0.1% |
| POP_JUMP_IF_TRUE | 38,420 | 0.1% |
| CALL | 7,140 | 0.0% |
| CALL_BUILTIN_FAST | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 14,655,580 | 49.8% |
| LOAD_FAST | 14,628,980 | 49.7% |
| LOAD_CONST | 76,840 | 0.3% |
| RETURN_CONST | 39,760 | 0.1% |
| NOP | 38,480 | 0.1% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 20 | 50.0% |
| BINARY_SUBSCR_STR_INT | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 40 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,862,180 | 99.7% |
| LOAD_ATTR_MODULE | 45,380 | 0.3% |
| LOAD_ATTR | 380 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| STORE_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,781,340 | 99.1% |
| LOAD_GLOBAL_BUILTIN | 74,240 | 0.5% |
| LOAD_GLOBAL_MODULE | 36,120 | 0.2% |
| LOAD_FAST | 6,360 | 0.0% |
| LOAD_FAST_LOAD_FAST | 3,940 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,455,780 | 98.0% |
| RETURN_VALUE | 133,120 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 38,440 | 0.3% |
| BINARY_SUBSCR_DICT | 34,460 | 0.2% |
| CALL | 33,460 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 14,464,520 | 98.1% |
| RETURN_VALUE | 133,120 | 0.9% |
| STORE_FAST | 97,740 | 0.7% |
| LOAD_ATTR_METHOD_NO_DICT | 32,000 | 0.2% |
| TO_BOOL_BOOL | 4,360 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 260 | 34.2% |
| LOAD_CONST | 240 | 31.6% |
| LOAD_FAST_LOAD_FAST | 200 | 26.3% |
| STORE_SUBSCR | 60 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280 | 36.8% |
| JUMP_FORWARD | 200 | 26.3% |
| STORE_SUBSCR_DICT | 140 | 18.4% |
| STORE_SUBSCR | 60 | 7.9% |
| LOAD_GLOBAL | 60 | 7.9% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,160 | 67.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 31,980 | 30.5% |
| TO_BOOL | 800 | 0.8% |
| RETURN_VALUE | 160 | 0.2% |
| CALL | 160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 69,280 | 66.1% |
| POP_JUMP_IF_FALSE | 34,260 | 32.7% |
| TO_BOOL | 800 | 0.8% |
| TO_BOOL_BOOL | 340 | 0.3% |
| TO_BOOL_INT | 40 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 60 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 40 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 40 | 66.7% |
| TO_BOOL_LIST | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 40 | 66.7% |
| CALL_PY_EXACT_ARGS | 20 | 33.3% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,180 | 88.9% |
| LOAD_ATTR_WITH_HINT | 1,880 | 4.5% |
| LOAD_ATTR_MODULE | 1,240 | 3.0% |
| BINARY_OP | 760 | 1.8% |
| LOAD_GLOBAL_MODULE | 360 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 31,960 | 76.4% |
| CALL_BUILTIN_FAST | 5,040 | 12.1% |
| LOAD_FAST | 2,000 | 4.8% |
| TO_BOOL_INT | 1,520 | 3.6% |
| BINARY_OP | 760 | 1.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 82.8% |
| RESUME_CHECK | 120 | 5.2% |
| STORE_FAST | 100 | 4.3% |
| LOAD_CONST | 40 | 1.7% |
| POP_JUMP_IF_NOT_NONE | 40 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,960 | 84.5% |
| STORE_FAST | 320 | 13.8% |
| SWAP | 40 | 1.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,280 | 33.0% |
| LOAD_FAST | 1,280 | 33.0% |
| STORE_ATTR_INSTANCE_VALUE | 660 | 17.0% |
| BUILD_TUPLE | 640 | 16.5% |
| STORE_ATTR | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,960 | 50.5% |
| CALL_PY_EXACT_ARGS | 1,240 | 32.0% |
| LOAD_GLOBAL_MODULE | 600 | 15.5% |
| CALL | 40 | 1.0% |
| LOAD_GLOBAL | 40 | 1.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 80 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 33,340 | 46.6% |
| LOAD_GLOBAL_BUILTIN | 32,020 | 44.8% |
| LOAD_FAST | 5,920 | 8.3% |
| CALL_BUILTIN_O | 100 | 0.1% |
| CALL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 32,000 | 44.8% |
| CALL_ISINSTANCE | 32,000 | 44.8% |
| LOAD_CONST | 3,840 | 5.4% |
| STORE_FAST | 1,380 | 1.9% |
| RETURN_VALUE | 740 | 1.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,700 | 45.9% |
| ENTER_EXECUTOR | 62,440 | 39.5% |
| LOAD_GLOBAL_MODULE | 6,020 | 3.8% |
| LOAD_ATTR | 4,680 | 3.0% |
| LOAD_CONST | 3,280 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40,920 | 25.9% |
| CALL_STR_1 | 34,080 | 21.5% |
| RETURN_VALUE | 33,460 | 21.1% |
| RESUME_CHECK | 33,000 | 20.9% |
| POP_TOP | 7,140 | 4.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 1,920 | 96.0% |
| LOAD_FAST | 80 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,240 | 62.0% |
| STORE_FAST | 640 | 32.0% |
| COPY_FREE_VARS | 80 | 4.0% |
| RESUME | 40 | 2.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 1,280 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,560 | 50.0% |
| LOAD_FAST | 1,280 | 25.0% |
| STORE_DEREF | 640 | 12.5% |
| RESUME_CHECK | 620 | 12.1% |
| RESUME | 20 | 0.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 75.0% |
| LOAD_GLOBAL_MODULE | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 100 | 62.5% |
| COMPARE_OP_INT | 40 | 25.0% |
| COMPARE_OP_STR | 20 | 12.5% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,000 | 85.0% |
| LOAD_ATTR_INSTANCE_VALUE | 2,720 | 7.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,540 | 6.7% |
| LOAD_GLOBAL_MODULE | 160 | 0.4% |
| LOAD_CONST | 100 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 37,600 | 99.8% |
| EXTENDED_ARG | 60 | 0.2% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 38,420 | 52.5% |
| CALL_LEN | 31,980 | 43.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,340 | 1.8% |
| CALL | 660 | 0.9% |
| LOAD_FAST | 660 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 38,360 | 52.4% |
| STORE_FAST | 32,000 | 43.7% |
| LOAD_FAST | 2,560 | 3.5% |
| TO_BOOL_STR | 80 | 0.1% |
| TO_BOOL | 40 | 0.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,720 | 94.9% |
| CALL | 120 | 3.1% |
| CALL_FUNCTION_EX | 80 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,780 | 96.4% |
| RESUME | 140 | 3.6% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,280 | 66.7% |
| RETURN_VALUE | 640 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,920 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,655,580 | 99.4% |
| ENTER_EXECUTOR | 95,040 | 0.6% |
| EXTENDED_ARG | 400 | 0.0% |
| JUMP_BACKWARD | 140 | 0.0% |
| CALL_LIST_APPEND | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 14,303,680 | 97.0% |
| FOR_ITER_RANGE | 193,400 | 1.3% |
| ENTER_EXECUTOR | 95,040 | 0.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 95,040 | 0.6% |
| CALL | 62,440 | 0.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 240 | 25.5% |
| POP_TOP | 140 | 14.9% |
| GET_ITER | 120 | 12.8% |
| TO_BOOL_BOOL | 120 | 12.8% |
| ENTER_EXECUTOR | 100 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 400 | 42.6% |
| POP_JUMP_IF_FALSE | 240 | 25.5% |
| FOR_ITER_LIST | 160 | 17.0% |
| JUMP_FORWARD | 80 | 8.5% |
| FOR_ITER | 60 | 6.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 220 | 45.8% |
| JUMP_BACKWARD | 180 | 37.5% |
| EXTENDED_ARG | 60 | 12.5% |
| FOR_ITER | 20 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 37.5% |
| FOR_ITER_RANGE | 100 | 20.8% |
| NOP | 40 | 8.3% |
| FOR_ITER_LIST | 40 | 8.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 8.3% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 640 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 640 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 680 | 89.5% |
| POP_JUMP_IF_TRUE | 80 | 10.5% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,380 | 97.5% |
| BINARY_OP_INPLACE_ADD_UNICODE | 40 | 1.6% |
| POP_JUMP_IF_FALSE | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 1,500 | 61.5% |
| FOR_ITER_LIST | 600 | 24.6% |
| FOR_ITER | 180 | 7.4% |
| ENTER_EXECUTOR | 140 | 5.7% |
| LOAD_FAST | 20 | 0.8% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 34,680 | 91.5% |
| STORE_ATTR | 1,920 | 5.1% |
| LOAD_ATTR | 640 | 1.7% |
| STORE_SUBSCR | 200 | 0.5% |
| CALL_BUILTIN_O | 180 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,060 | 89.9% |
| LOAD_GLOBAL_BUILTIN | 2,620 | 6.9% |
| STORE_FAST | 840 | 2.2% |
| EXTENDED_ARG | 240 | 0.6% |
| LOAD_GLOBAL_MODULE | 60 | 0.2% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 40 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,280 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 129,920 | 55.3% |
| LOAD_ATTR_INSTANCE_VALUE | 77,100 | 32.8% |
| LOAD_GLOBAL_MODULE | 13,140 | 5.6% |
| LOAD_ATTR | 10,180 | 4.3% |
| LOAD_FAST_LOAD_FAST | 3,480 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 75,920 | 32.3% |
| LOAD_FAST | 45,240 | 19.3% |
| COPY | 38,420 | 16.3% |
| CALL_BUILTIN_FAST | 38,360 | 16.3% |
| LOAD_ATTR | 10,180 | 4.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 28,966,080 | 39.7% |
| LOAD_CONST | 28,940,660 | 39.7% |
| PUSH_NULL | 14,781,340 | 20.3% |
| POP_TOP | 76,840 | 0.1% |
| POP_JUMP_IF_FALSE | 65,540 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 28,965,800 | 39.7% |
| LOAD_CONST | 28,940,660 | 39.7% |
| CALL_BUILTIN_O | 14,778,320 | 20.3% |
| LOAD_FAST | 82,260 | 0.1% |
| STORE_FAST | 40,100 | 0.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,720 | 38.1% |
| LOAD_GLOBAL_MODULE | 3,720 | 38.1% |
| NOP | 720 | 7.4% |
| STORE_FAST | 720 | 7.4% |
| RESUME_CHECK | 620 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,200 | 43.0% |
| CALL_PY_EXACT_ARGS | 3,600 | 36.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,200 | 12.3% |
| LOAD_ATTR | 360 | 3.7% |
| CALL | 240 | 2.5% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,116,900 | 64.3% |
| POP_TOP | 14,628,980 | 32.3% |
| LOAD_GLOBAL_BUILTIN | 341,700 | 0.8% |
| RESUME_CHECK | 238,160 | 0.5% |
| FOR_ITER_RANGE | 193,400 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 14,862,180 | 32.8% |
| LOAD_ATTR_METHOD_NO_DICT | 14,695,740 | 32.5% |
| RETURN_VALUE | 14,455,780 | 31.9% |
| LOAD_ATTR_INSTANCE_VALUE | 181,220 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 160,060 | 0.4% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 40 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 100,640 | 37.6% |
| LOAD_ATTR_METHOD_NO_DICT | 37,740 | 14.1% |
| LOAD_GLOBAL_BUILTIN | 35,140 | 13.1% |
| LOAD_FAST_LOAD_FAST | 33,980 | 12.7% |
| CALL_TYPE_1 | 32,020 | 12.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 99,120 | 37.0% |
| LOAD_FAST | 36,880 | 13.8% |
| LOAD_FAST_LOAD_FAST | 33,980 | 12.7% |
| BUILD_TUPLE | 33,340 | 12.5% |
| CALL_BUILTIN_CLASS | 31,960 | 11.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 920 | 20.7% |
| RESUME | 500 | 11.3% |
| RESUME_CHECK | 460 | 10.4% |
| LOAD_CONST | 440 | 9.9% |
| LOAD_FAST | 360 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,360 | 30.6% |
| LOAD_FAST | 900 | 20.3% |
| LOAD_GLOBAL_BUILTIN | 840 | 18.9% |
| LOAD_ATTR | 560 | 12.6% |
| CALL | 340 | 7.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 640 | 50.0% |
| MAKE_CELL | 640 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 640 | 50.0% |
| RESUME_CHECK | 620 | 48.4% |
| RESUME | 20 | 1.6% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 169,760 | 60.6% |
| CONTAINS_OP | 37,600 | 13.4% |
| TO_BOOL | 34,260 | 12.2% |
| COMPARE_OP_INT | 32,560 | 11.6% |
| TO_BOOL_INT | 1,560 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,300 | 29.0% |
| LOAD_CONST | 65,540 | 23.4% |
| LOAD_GLOBAL_MODULE | 65,460 | 23.4% |
| LOAD_GLOBAL_BUILTIN | 32,320 | 11.5% |
| NOP | 32,040 | 11.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,480 | 97.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,960 | 2.6% |
| LOAD_ATTR | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,760 | 53.4% |
| LOAD_GLOBAL_MODULE | 31,960 | 42.9% |
| LOAD_FAST_LOAD_FAST | 1,920 | 2.6% |
| LOAD_GLOBAL_BUILTIN | 660 | 0.9% |
| LOAD_GLOBAL | 120 | 0.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,460 | 72.7% |
| LOAD_ATTR_WITH_HINT | 1,260 | 26.5% |
| ENTER_EXECUTOR | 20 | 0.4% |
| LOAD_ATTR | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,740 | 57.6% |
| LOAD_GLOBAL_MODULE | 1,860 | 39.1% |
| LOAD_GLOBAL | 80 | 1.7% |
| BUILD_LIST | 40 | 0.8% |
| EXTENDED_ARG | 20 | 0.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 69,280 | 48.6% |
| TO_BOOL_NONE | 38,380 | 26.9% |
| TO_BOOL_BOOL | 34,580 | 24.3% |
| TO_BOOL_INT | 120 | 0.1% |
| IS_OP | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,220 | 27.5% |
| POP_TOP | 38,420 | 26.9% |
| LOAD_GLOBAL_MODULE | 32,600 | 22.9% |
| LOAD_GLOBAL_BUILTIN | 32,000 | 22.4% |
| LOAD_GLOBAL | 120 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 39,760 | 47.0% |
| STORE_ATTR_INSTANCE_VALUE | 39,180 | 46.3% |
| POP_JUMP_IF_FALSE | 2,820 | 3.3% |
| RESUME_CHECK | 1,240 | 1.5% |
| STORE_ATTR | 680 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 42,520 | 50.3% |
| INTERPRETER_EXIT | 37,820 | 44.7% |
| RETURN_VALUE | 3,840 | 4.5% |
| TO_BOOL_BOOL | 180 | 0.2% |
| STORE_FAST | 160 | 0.2% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,840 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,040 | 52.9% |
| LOAD_FAST | 3,220 | 42.1% |
| STORE_ATTR | 380 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,200 | 28.8% |
| LOAD_FAST_LOAD_FAST | 1,960 | 25.7% |
| JUMP_FORWARD | 1,920 | 25.1% |
| RETURN_CONST | 680 | 8.9% |
| STORE_ATTR_INSTANCE_VALUE | 420 | 5.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 29,060,980 | 99.2% |
| RETURN_VALUE | 97,740 | 0.3% |
| CALL | 40,920 | 0.1% |
| LOAD_CONST | 40,100 | 0.1% |
| COPY | 32,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,116,900 | 99.4% |
| NOP | 39,980 | 0.1% |
| LOAD_GLOBAL_MODULE | 38,500 | 0.1% |
| JUMP_FORWARD | 34,680 | 0.1% |
| LOAD_CONST | 33,020 | 0.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 40 | 50.0% |
| CALL_LEN | 40 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 40 | 50.0% |
| LOAD_ATTR | 40 | 50.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 920 | 83.6% |
| UNPACK_SEQUENCE_TUPLE | 80 | 7.3% |
| COPY | 40 | 3.6% |
| STORE_FAST_STORE_FAST | 40 | 3.6% |
| UNPACK_SEQUENCE | 20 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 640 | 58.2% |
| LOAD_FAST | 240 | 21.8% |
| LOAD_FAST_LOAD_FAST | 60 | 5.5% |
| NOP | 40 | 3.6% |
| LOAD_GLOBAL | 40 | 3.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 40 | 33.3% |
| LOAD_FAST_AND_CLEAR | 40 | 33.3% |
| FOR_ITER_RANGE | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 40 | 33.3% |
| STORE_FAST | 40 | 33.3% |
| FOR_ITER_RANGE | 40 | 33.3% |


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
| CALL | 780 | 61.9% |
| CACHE | 260 | 20.6% |
| COPY_FREE_VARS | 140 | 11.1% |
| CALL_FUNCTION_EX | 40 | 3.2% |
| CALL_KW | 20 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 520 | 41.3% |
| LOAD_GLOBAL | 500 | 39.7% |
| LOAD_FAST_LOAD_FAST | 120 | 9.5% |
| LOAD_CONST | 40 | 3.2% |
| RETURN_CONST | 40 | 3.2% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 640 | 68.1% |
| LOAD_CONST | 280 | 29.8% |
| BINARY_OP | 20 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 760 | 80.9% |
| LOAD_FAST | 140 | 14.9% |
| CALL_BUILTIN_O | 20 | 2.1% |
| CALL_PY_EXACT_ARGS | 20 | 2.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 50.0% |
| CALL_BUILTIN_O | 20 | 50.0% |


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
| LOAD_CONST | 100 | 38.5% |
| LOAD_FAST | 80 | 30.8% |
| CALL_LEN | 80 | 30.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 30.8% |
| LOAD_FAST | 60 | 23.1% |
| LOAD_CONST | 40 | 15.4% |
| LOAD_FAST_LOAD_FAST | 40 | 15.4% |
| STORE_FAST | 40 | 15.4% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 32,000 | 89.5% |
| LOAD_FAST | 3,680 | 10.3% |
| BINARY_SUBSCR | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 34,460 | 96.4% |
| CALL_PY_EXACT_ARGS | 1,240 | 3.5% |
| PUSH_EXC_INFO | 20 | 0.1% |
| CALL | 20 | 0.1% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 95.4% |
| LOAD_FAST | 40 | 3.1% |
| BINARY_SUBSCR | 20 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,300 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 50.0% |
| LOAD_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 100 | 71.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 28.6% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 53.3% |
| LOAD_FAST | 120 | 40.0% |
| BINARY_SUBSCR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 53.3% |
| STORE_FAST | 80 | 26.7% |
| BINARY_OP_INPLACE_ADD_UNICODE | 20 | 6.7% |
| PUSH_EXC_INFO | 20 | 6.7% |
| CALL_BUILTIN_O | 20 | 6.7% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 83.3% |
| LOAD_CONST | 100 | 13.9% |
| BINARY_SUBSCR | 20 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 620 | 86.1% |
| LOAD_GLOBAL_MODULE | 100 | 13.9% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 50.0% |
| LOAD_GLOBAL_MODULE | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 40 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 75,920 | 99.1% |
| CALL | 440 | 0.6% |
| LOAD_CONST | 180 | 0.2% |
| PUSH_NULL | 60 | 0.1% |
| BUILD_TUPLE | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 76,640 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 31,960 | 95.5% |
| LOAD_FAST | 680 | 2.0% |
| BINARY_SLICE | 600 | 1.8% |
| CALL | 80 | 0.2% |
| UNARY_NEGATIVE | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 31,960 | 95.5% |
| GET_ITER | 700 | 2.1% |
| STORE_FAST | 680 | 2.0% |
| LIST_APPEND | 40 | 0.1% |
| LOAD_CONST | 40 | 0.1% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 38,360 | 79.1% |
| BINARY_OP | 5,040 | 10.4% |
| LOAD_FAST | 2,540 | 5.2% |
| LOAD_CONST | 2,440 | 5.0% |
| CALL | 140 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,380 | 79.1% |
| RETURN_VALUE | 5,080 | 10.5% |
| POP_TOP | 2,540 | 5.2% |
| STORE_FAST | 1,880 | 3.9% |
| TO_BOOL_BOOL | 600 | 1.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 80.0% |
| CALL_TUPLE_1 | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 80.0% |
| RETURN_VALUE | 20 | 20.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,778,320 | 50.3% |
| RETURN_VALUE | 14,464,520 | 49.3% |
| CALL_STR_1 | 70,560 | 0.2% |
| LOAD_FAST | 38,800 | 0.1% |
| CALL | 1,300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 29,353,400 | 100.0% |
| JUMP_FORWARD | 180 | 0.0% |
| BUILD_TUPLE | 100 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 128,040 | 65.8% |
| LOAD_GLOBAL_MODULE | 32,020 | 16.5% |
| BUILD_TUPLE | 32,000 | 16.4% |
| LOAD_ATTR | 1,800 | 0.9% |
| LOAD_ATTR_MODULE | 600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 192,600 | 99.0% |
| RETURN_VALUE | 1,900 | 1.0% |
| TO_BOOL | 120 | 0.1% |
| LOAD_FAST | 20 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,380 | 99.2% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.4% |
| POP_JUMP_IF_TRUE | 80 | 0.2% |
| LOAD_GLOBAL_MODULE | 40 | 0.1% |
| CALL | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 31,980 | 98.0% |
| LOAD_CONST | 280 | 0.9% |
| RETURN_VALUE | 120 | 0.4% |
| BINARY_OP_SUBTRACT_INT | 80 | 0.2% |
| LOAD_FAST | 40 | 0.1% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 120 | 60.0% |
| LOAD_FAST | 40 | 20.0% |
| LOAD_CONST | 20 | 10.0% |
| LOAD_GLOBAL_MODULE | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 80 | 40.0% |
| LOAD_FAST | 40 | 20.0% |
| LOAD_FAST_LOAD_FAST | 40 | 20.0% |
| RETURN_CONST | 40 | 20.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 31,960 | 71.4% |
| LOAD_FAST_LOAD_FAST | 5,720 | 12.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,720 | 12.8% |
| LOAD_ATTR_METHOD_NO_DICT | 1,200 | 2.7% |
| CALL | 100 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 31,980 | 71.4% |
| RETURN_VALUE | 6,980 | 15.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,720 | 12.8% |
| STORE_FAST | 60 | 0.1% |
| CALL | 20 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,965,800 | 99.7% |
| ENTER_EXECUTOR | 95,040 | 0.3% |
| CALL | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,060,980 | 100.0% |
| LOAD_CONST | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,700 | 99.3% |
| CALL | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,720 | 99.7% |
| GET_ITER | 20 | 0.3% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 31,960 | 97.8% |
| LOAD_ATTR_INSTANCE_VALUE | 640 | 2.0% |
| LOAD_FAST | 60 | 0.2% |
| CALL | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,620 | 99.8% |
| POP_TOP | 60 | 0.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 99,120 | 46.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 44,480 | 20.9% |
| CALL_STR_1 | 34,720 | 16.4% |
| LOAD_FAST | 12,020 | 5.7% |
| LOAD_GLOBAL_MODULE | 6,600 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 208,600 | 98.2% |
| COPY_FREE_VARS | 3,720 | 1.8% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,080 | 96.2% |
| LOAD_FAST_LOAD_FAST | 1,220 | 3.7% |
| CALL | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 33,360 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,920 | 64.3% |
| CALL | 34,080 | 32.3% |
| RETURN_VALUE | 3,600 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 70,560 | 66.8% |
| CALL_PY_EXACT_ARGS | 34,720 | 32.9% |
| CALL | 320 | 0.3% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 32,020 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 32,460 | 99.7% |
| LOAD_GLOBAL_MODULE | 60 | 0.2% |
| COMPARE_OP | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 32,560 | 100.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 520 | 70.3% |
| LOAD_ATTR_INSTANCE_VALUE | 200 | 27.0% |
| COMPARE_OP | 20 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 680 | 91.9% |
| EXTENDED_ARG | 60 | 8.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,320 | 38.4% |
| ENTER_EXECUTOR | 1,320 | 38.4% |
| JUMP_BACKWARD | 600 | 17.4% |
| EXTENDED_ARG | 160 | 4.7% |
| FOR_ITER | 40 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,880 | 54.7% |
| LOAD_FAST | 1,320 | 38.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 160 | 4.7% |
| BUILD_LIST | 40 | 1.2% |
| LOAD_GLOBAL_BUILTIN | 40 | 1.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 193,400 | 97.5% |
| GET_ITER | 3,220 | 1.6% |
| JUMP_BACKWARD | 1,500 | 0.8% |
| FOR_ITER | 100 | 0.1% |
| SWAP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 193,400 | 97.5% |
| STORE_FAST | 4,820 | 2.4% |
| SWAP | 40 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,220 | 80.1% |
| BINARY_SUBSCR | 38,360 | 17.0% |
| LOAD_FAST_LOAD_FAST | 4,160 | 1.8% |
| LOAD_DEREF | 1,200 | 0.5% |
| LOAD_ATTR | 1,180 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 77,100 | 34.1% |
| LOAD_CONST | 44,380 | 19.6% |
| RETURN_VALUE | 38,440 | 17.0% |
| LOAD_FAST | 35,240 | 15.6% |
| LOAD_ATTR_METHOD_NO_DICT | 17,180 | 7.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,695,740 | 50.5% |
| ENTER_EXECUTOR | 14,303,680 | 49.2% |
| RETURN_VALUE | 32,000 | 0.1% |
| LOAD_CONST | 31,960 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 17,180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,966,080 | 99.6% |
| LOAD_FAST_LOAD_FAST | 37,740 | 0.1% |
| LOAD_GLOBAL_MODULE | 32,060 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 31,960 | 0.1% |
| LOAD_FAST | 12,420 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,280 | 90.8% |
| LOAD_DEREF | 4,200 | 7.0% |
| LOAD_ATTR | 680 | 1.1% |
| RETURN_VALUE | 600 | 1.0% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 44,480 | 74.4% |
| LOAD_CONST | 6,860 | 11.5% |
| LOAD_DEREF | 3,720 | 6.2% |
| LOAD_FAST_LOAD_FAST | 2,520 | 4.2% |
| LOAD_FAST | 1,920 | 3.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 46,280 | 92.8% |
| LOAD_ATTR_WITH_HINT | 2,480 | 5.0% |
| LOAD_FAST_LOAD_FAST | 600 | 1.2% |
| LOAD_ATTR | 500 | 1.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 45,380 | 91.0% |
| LOAD_FAST | 1,940 | 3.9% |
| BINARY_OP | 1,240 | 2.5% |
| LOAD_FAST_LOAD_FAST | 620 | 1.2% |
| CALL_ISINSTANCE | 600 | 1.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,520 | 98.4% |
| LOAD_ATTR | 20 | 0.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 2,540 | 99.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 20 | 0.8% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 50.0% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80 | 100.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,640 | 88.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,240 | 6.6% |
| LOAD_FAST_LOAD_FAST | 600 | 3.2% |
| LOAD_ATTR | 360 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,200 | 43.5% |
| LOAD_ATTR_MODULE | 2,480 | 13.2% |
| BINARY_OP | 1,880 | 10.0% |
| POP_JUMP_IF_NOT_NONE | 1,260 | 6.7% |
| STORE_FAST | 1,260 | 6.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160,060 | 28.1% |
| RESUME_CHECK | 135,100 | 23.7% |
| PUSH_NULL | 74,240 | 13.0% |
| STORE_FAST | 32,760 | 5.8% |
| POP_JUMP_IF_FALSE | 32,320 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 341,700 | 60.0% |
| CALL_ISINSTANCE | 128,040 | 22.5% |
| LOAD_FAST_LOAD_FAST | 35,140 | 6.2% |
| LOAD_GLOBAL_BUILTIN | 32,100 | 5.6% |
| BUILD_TUPLE | 32,020 | 5.6% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 65,460 | 18.9% |
| LOAD_FAST | 40,900 | 11.8% |
| STORE_FAST | 38,500 | 11.1% |
| PUSH_NULL | 36,120 | 10.4% |
| NOP | 33,800 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 101,460 | 29.3% |
| LOAD_FAST_LOAD_FAST | 100,640 | 29.1% |
| LOAD_ATTR_MODULE | 46,280 | 13.4% |
| CALL_ISINSTANCE | 32,020 | 9.2% |
| LOAD_GLOBAL_BUILTIN | 32,020 | 9.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 208,600 | 52.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 76,640 | 19.1% |
| CACHE | 41,100 | 10.3% |
| CALL_PY_WITH_DEFAULTS | 33,360 | 8.3% |
| CALL | 33,000 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 238,160 | 59.5% |
| LOAD_GLOBAL_BUILTIN | 135,100 | 33.7% |
| LOAD_GLOBAL_MODULE | 14,060 | 3.5% |
| LOAD_FAST_LOAD_FAST | 8,080 | 2.0% |
| NOP | 1,280 | 0.3% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 119,400 | 93.6% |
| LOAD_FAST_LOAD_FAST | 7,740 | 6.1% |
| STORE_ATTR | 420 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,140 | 63.6% |
| RETURN_CONST | 39,180 | 30.7% |
| LOAD_FAST_LOAD_FAST | 4,580 | 3.6% |
| LOAD_CONST | 1,360 | 1.1% |
| BUILD_MAP | 660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,880 | 96.4% |
| STORE_SUBSCR | 140 | 2.8% |
| LOAD_FAST | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 37.9% |
| LOAD_GLOBAL_BUILTIN | 1,860 | 36.8% |
| RETURN_CONST | 620 | 12.3% |
| LOAD_GLOBAL_MODULE | 600 | 11.9% |
| LOAD_GLOBAL | 60 | 1.2% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40 | 66.7% |
| LOAD_FAST | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 40 | 66.7% |
| EXTENDED_ARG | 20 | 33.3% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 192,600 | 94.2% |
| RETURN_VALUE | 4,360 | 2.1% |
| LOAD_FAST | 3,240 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,260 | 0.6% |
| LOAD_ATTR_WITH_HINT | 1,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 169,760 | 83.0% |
| POP_JUMP_IF_TRUE | 34,580 | 16.9% |
| EXTENDED_ARG | 120 | 0.1% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,520 | 88.4% |
| LOAD_FAST | 120 | 7.0% |
| TO_BOOL | 40 | 2.3% |
| COPY | 40 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,560 | 90.7% |
| POP_JUMP_IF_TRUE | 120 | 7.0% |
| UNARY_NOT | 40 | 2.3% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 220 | 84.6% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 15.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 180 | 69.2% |
| POP_JUMP_IF_TRUE | 60 | 23.1% |
| UNARY_NOT | 20 | 7.7% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 38,360 | 96.1% |
| LOAD_ATTR_INSTANCE_VALUE | 640 | 1.6% |
| LOAD_ATTR_WITH_HINT | 600 | 1.5% |
| LOAD_FAST | 260 | 0.7% |
| TO_BOOL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 38,380 | 96.2% |
| POP_JUMP_IF_FALSE | 1,520 | 3.8% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 600 | 76.9% |
| COPY | 80 | 10.3% |
| LOAD_FAST | 80 | 10.3% |
| TO_BOOL | 20 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 700 | 89.7% |
| POP_JUMP_IF_TRUE | 80 | 10.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 66.7% |
| RETURN_VALUE | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 80 | 66.7% |
| STORE_FAST | 40 | 33.3% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 720 | 73.5% |
| FOR_ITER_LIST | 160 | 16.3% |
| FOR_ITER | 40 | 4.1% |
| BINARY_SUBSCR_LIST_INT | 40 | 4.1% |
| UNPACK_SEQUENCE | 20 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 920 | 93.9% |
| STORE_FAST | 60 | 6.1% |


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
|     deferred | 41,000 | 95.0% |
|          hit | 1,360 | 3.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 7.3% |
| Failure | 760 | 92.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 420 | 55.3% |
| add other | 180 | 23.7% |
| and int | 160 | 21.1% |


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
|     deferred | 39,260 | 50.4% |
|          hit | 38,180 | 49.0% |
|         miss | 40 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 31.6% |
| Failure | 260 | 68.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 180 | 69.2% |
| buffer int | 80 | 30.8% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 152,180 | 0.3% |
|          hit | 59,344,060 | 99.7% |
|         miss | 20 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,200 | 69.1% |
| Failure | 1,880 | 30.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 680 | 36.2% |
| class no vectorcall | 260 | 13.8% |
| cfunc varargs keywords | 220 | 11.7% |
| code complex parameters | 200 | 10.6% |
| class mutable | 160 | 8.5% |
| meth descr varargs keywords | 140 | 7.4% |
| meth descr varargs | 100 | 5.3% |
| cfunc noargs | 60 | 3.2% |
| meth descr method fastcall keywords | 60 | 3.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 0.3% |
|          hit | 33,280 | 99.5% |
|         miss | 20 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 320 | 0.2% |
|          hit | 201,700 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 87.5% |
| Failure | 20 | 12.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| map | 20 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 227,480 | 0.8% |
|          hit | 29,439,840 | 99.2% |
|         miss | 4,800 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,120 | 41.5% |
| Failure | 4,400 | 58.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overridden | 2,500 | 56.8% |
| module attr not found | 380 | 8.6% |
| shadowed | 360 | 8.2% |
| non object slot | 320 | 7.3% |
| not managed dict | 320 | 7.3% |
| has managed dict | 240 | 5.5% |
| metaclass attribute | 140 | 3.2% |
| mutable class | 80 | 1.8% |
| method | 60 | 1.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,240 | 0.2% |
|          hit | 915,440 | 99.5% |
|         miss | 200 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,200 | 100.0% |
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
|     deferred | 6,840 | 5.1% |
|          hit | 127,580 | 94.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 420 | 52.5% |
| Failure | 380 | 47.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 300 | 78.9% |
| no dict | 80 | 21.1% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 560 | 9.5% |
|          hit | 5,120 | 87.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 70.0% |
| Failure | 60 | 30.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 40 | 66.7% |
| bytearray int | 20 | 33.3% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 103,540 | 29.4% |
|          hit | 247,120 | 70.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 440 | 35.5% |
| Failure | 800 | 64.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 360 | 45.0% |
| tuple | 220 | 27.5% |
| dict | 140 | 17.5% |
| set | 80 | 10.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 1.8% |
|          hit | 1,100 | 96.5% |

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
| Basic | 222,148,880 | 70.8% |
| Not specialized | 1,095,720 | 0.3% |
| Specialized hits | 90,678,460 | 28.9% |
| Specialized misses | 5,080 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 227,480 | 39.7% |
| CALL | 152,180 | 26.5% |
| TO_BOOL | 103,540 | 18.1% |
| BINARY_OP | 41,000 | 7.1% |
| BINARY_SUBSCR | 39,260 | 6.8% |
| STORE_ATTR | 6,840 | 1.2% |
| LOAD_GLOBAL | 2,240 | 0.4% |
| STORE_SUBSCR | 560 | 0.1% |
| FOR_ITER | 320 | 0.1% |
| COMPARE_OP | 100 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,480 | 48.8% |
| LOAD_ATTR_MODULE | 1,260 | 24.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,060 | 20.9% |
| LOAD_GLOBAL_BUILTIN | 200 | 3.9% |
| BINARY_SUBSCR_LIST_INT | 20 | 0.4% |
| BINARY_SUBSCR_STR_INT | 20 | 0.4% |
| CALL_BUILTIN_FAST | 20 | 0.4% |
| COMPARE_OP_STR | 20 | 0.4% |
| CACHE | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 42,000 | 10.5% |
| Calls to Python functions inlined | 359,640 | 89.5% |
| Calls via PyEval_EvalFrame (total) | 42,000 | 10.5% |
| Calls via PyEval_EvalFrame (vector) | 42,000 | 10.5% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 42,000 | 10.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 100 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 1,360 | 0.3% |
| Calls via PyEval_EvalFrame (api) | 20 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 80 | 0.0% |
| Frames pushed | 14,753,740 | 3,673.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 287,220 | 0.5% |
| Frees to freelist | 287,360 |  |
| Allocations | 59,767,340 | 99.5% |
| Allocations to 512 bytes | 58,402,660 | 97.2% |
| Allocations to 4 kbytes | 1,363,380 | 2.3% |
| Allocations over 4 kbytes | 1,300 | 0.0% |
| Frees | 59,796,657 |  |
| New values | 8,360 |  |
| Interpreter increfs | 437,885,960 | 63.8% |
| Interpreter decrefs | 539,577,560 | 72.4% |
| Increfs | 248,460,373 | 36.2% |
| Decrefs | 205,327,622 | 27.6% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 237,150 |  |
| Method cache misses | 6,590 |  |
| Method cache collisions | 6,712 |  |
| Method cache dunder hits | 599,043 |  |
| Method cache dunder misses | 417 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 10,040 | 2,839,880 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 140 |  |
| Traces created | 140 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 40 | 28.6% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 20 | 14.3% |
| Recursive call | 0 | 0.0% |
| Traces executed | 14,751,340 |  |
| Uops executed | 1,516,064,240 | 102.77 |

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
| <= 32 | 20 | 14.3% |
| <= 64 | 20 | 14.3% |
| <= 128 | 100 | 71.4% |


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
| <= 16 | 20 | 14.3% |
| <= 32 | 20 | 14.3% |
| <= 64 | 60 | 42.9% |
| <= 128 | 40 | 28.6% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,440 | 0.0% |
| <= 4 | 97,360 | 0.7% |
| <= 8 | 100 | 0.0% |
| <= 16 | 460 | 0.0% |
| <= 32 | 31,040 | 0.2% |
| <= 64 | 126,100 | 0.9% |
| <= 128 | 14,398,800 | 97.6% |
| <= 256 | 40 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 96,000 | 0.7% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 216,489,040 | 14.3% | 14.3% |  |
| _CHECK_VALIDITY | 216,294,700 | 14.3% | 28.5% |  |
| LOAD_FAST | 158,796,400 | 10.5% | 39.0% |  |
| LOAD_CONST | 129,775,360 | 8.6% | 47.6% |  |
| PUSH_NULL | 86,769,300 | 5.7% | 53.3% |  |
| STORE_FAST | 72,056,900 | 4.8% | 58.1% |  |
| POP_TOP | 57,847,040 | 3.8% | 61.9% |  |
| CALL_BUILTIN_O | 57,847,040 | 3.8% | 65.7% |  |
| _GUARD_GLOBALS_VERSION | 43,320,480 | 2.9% | 68.5% |  |
| _GUARD_TYPE_VERSION | 43,132,840 | 2.8% | 71.4% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 43,101,200 | 2.8% | 74.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 43,006,080 | 2.8% | 77.1% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 29,053,480 | 1.9% | 79.0% | 0.7% |
| _ITER_CHECK_RANGE | 29,053,480 | 1.9% | 80.9% |  |
| _ITER_NEXT_RANGE | 28,860,080 | 1.9% | 82.8% |  |
| _GUARD_BUILTINS_VERSION | 28,859,520 | 1.9% | 84.7% |  |
| _LOAD_GLOBAL_BUILTINS | 28,859,520 | 1.9% | 86.6% |  |
| CALL_STR_1 | 28,828,480 | 1.9% | 88.5% |  |
| _EXIT_TRACE | 14,556,280 | 1.0% | 89.5% |  |
| _LOAD_GLOBAL_MODULE | 14,460,960 | 1.0% | 90.4% |  |
| _CHECK_ATTR_MODULE | 14,460,800 | 1.0% | 91.4% |  |
| _LOAD_ATTR_MODULE | 14,460,800 | 1.0% | 92.3% |  |
| RESUME_CHECK | 14,429,960 | 1.0% | 93.3% |  |
| _CHECK_PEP_523 | 14,429,960 | 1.0% | 94.2% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 14,429,960 | 1.0% | 95.2% |  |
| _CHECK_STACK_SPACE | 14,429,960 | 1.0% | 96.1% |  |
| _INIT_CALL_PY_EXACT_ARGS | 14,429,960 | 1.0% | 97.1% |  |
| _PUSH_FRAME | 14,429,960 | 1.0% | 98.0% |  |
| _SAVE_RETURN_OFFSET | 14,429,960 | 1.0% | 99.0% |  |
| _JUMP_TO_TOP | 14,303,960 | 0.9% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 191,660 | 0.0% | 100.0% | 0.7% |
| _ITER_CHECK_LIST | 191,660 | 0.0% | 100.0% |  |
| _ITER_NEXT_LIST | 190,240 | 0.0% | 100.0% |  |
| GET_ITER | 190,080 | 0.0% | 100.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 31,380 | 0.0% | 100.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 31,380 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 31,040 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 360 | 0.0% | 100.0% |  |
| _GUARD_IS_FALSE_POP | 280 | 0.0% | 100.0% | 71.4% |
| BINARY_SLICE | 280 | 0.0% | 100.0% |  |
| LIST_APPEND | 280 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 280 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 280 | 0.0% | 100.0% |  |
| IS_OP | 160 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 160 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 160 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 160 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 100 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 100 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 100 | 0.0% | 100.0% |  |
| _GUARD_KEYS_VERSION | 100 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 100 | 0.0% | 100.0% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 100 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 100 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 80 | 0.0% | 100.0% |  |
| _POP_FRAME | 80 | 0.0% | 100.0% |  |
| _GUARD_IS_NOT_NONE_POP | 40 | 0.0% | 100.0% | 50.0% |
| CONTAINS_OP | 20 | 0.0% | 100.0% |  |
| _FOR_ITER_TIER_TWO | 20 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 60 |


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
