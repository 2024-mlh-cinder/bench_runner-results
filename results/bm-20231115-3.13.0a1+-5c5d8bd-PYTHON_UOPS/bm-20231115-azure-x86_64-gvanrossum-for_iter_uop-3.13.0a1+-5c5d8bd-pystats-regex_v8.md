
# Pystats results

- benchmark: regex_v8
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_CONST | 20,451,400 | 19.0% | 19.0% |  |
| LOAD_GLOBAL_MODULE | 13,122,220 | 12.2% | 31.2% | 0.2% |
| BINARY_SUBSCR_LIST_INT | 8,879,440 | 8.3% | 39.5% | 0.1% |
| POP_TOP | 8,522,440 | 7.9% | 47.4% |  |
| CALL | 8,381,320 | 7.8% | 55.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 7,255,800 | 6.8% | 62.0% |  |
| LOAD_FAST | 7,116,200 | 6.6% | 68.6% |  |
| ENTER_EXECUTOR | 4,540,440 | 4.2% | 72.8% |  |
| POP_JUMP_IF_FALSE | 2,571,600 | 2.4% | 75.2% |  |
| LOAD_GLOBAL_BUILTIN | 2,436,180 | 2.3% | 77.5% | 0.0% |
| LOAD_FAST_LOAD_FAST | 2,335,440 | 2.2% | 79.7% |  |
| RESUME_CHECK | 2,262,460 | 2.1% | 81.8% |  |
| RETURN_VALUE | 2,206,540 | 2.1% | 83.8% |  |
| LOAD_ATTR_MODULE | 1,240,660 | 1.2% | 85.0% | 0.0% |
| CALL_PY_EXACT_ARGS | 1,205,520 | 1.1% | 86.1% | 0.0% |
| STORE_FAST | 1,083,240 | 1.0% | 87.1% |  |
| TO_BOOL_BOOL | 983,900 | 0.9% | 88.0% |  |
| PUSH_NULL | 942,420 | 0.9% | 88.9% |  |
| CALL_ISINSTANCE | 941,080 | 0.9% | 89.8% |  |
| BUILD_TUPLE | 926,520 | 0.9% | 90.6% |  |
| NOP | 916,220 | 0.9% | 91.5% |  |
| BINARY_SUBSCR_DICT | 880,800 | 0.8% | 92.3% |  |
| CALL_TYPE_1 | 866,200 | 0.8% | 93.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 703,620 | 0.7% | 93.8% |  |
| IS_OP | 494,960 | 0.5% | 94.2% |  |
| STORE_FAST_STORE_FAST | 434,880 | 0.4% | 94.6% |  |
| TO_BOOL_LIST | 389,560 | 0.4% | 95.0% | 0.1% |
| TO_BOOL | 389,520 | 0.4% | 95.3% |  |
| IMPORT_NAME | 375,800 | 0.3% | 95.7% |  |
| CALL_KW | 375,200 | 0.3% | 96.0% |  |
| UNPACK_EX | 374,400 | 0.3% | 96.4% |  |
| CALL_PY_WITH_DEFAULTS | 374,220 | 0.3% | 96.7% |  |
| EXTENDED_ARG | 284,180 | 0.3% | 97.0% |  |
| LOAD_ATTR | 231,820 | 0.2% | 97.2% |  |
| INTERPRETER_EXIT | 182,700 | 0.2% | 97.4% |  |
| POP_JUMP_IF_NOT_NONE | 167,540 | 0.2% | 97.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 165,880 | 0.2% | 97.7% |  |
| POP_JUMP_IF_NONE | 151,060 | 0.1% | 97.8% |  |
| RETURN_CONST | 135,680 | 0.1% | 98.0% |  |
| CALL_BUILTIN_O | 131,980 | 0.1% | 98.1% | 0.1% |
| TO_BOOL_INT | 110,760 | 0.1% | 98.2% | 1.0% |
| CONTAINS_OP | 108,700 | 0.1% | 98.3% |  |
| POP_JUMP_IF_TRUE | 107,020 | 0.1% | 98.4% |  |
| BINARY_OP_ADD_INT | 101,820 | 0.1% | 98.5% |  |
| COMPARE_OP_STR | 99,680 | 0.1% | 98.6% | 2.9% |
| BINARY_OP | 95,460 | 0.1% | 98.7% |  |
| LOAD_GLOBAL | 94,240 | 0.1% | 98.8% |  |
| CALL_LEN | 93,340 | 0.1% | 98.8% |  |
| BINARY_SUBSCR | 93,040 | 0.1% | 98.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 78,060 | 0.1% | 99.0% |  |
| JUMP_FORWARD | 77,760 | 0.1% | 99.1% |  |
| FOR_ITER_RANGE | 75,680 | 0.1% | 99.1% |  |
| GET_ITER | 70,460 | 0.1% | 99.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 60,180 | 0.1% | 99.3% |  |
| BINARY_SUBSCR_STR_INT | 56,720 | 0.1% | 99.3% | 5.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 53,060 | 0.0% | 99.4% | 0.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 42,320 | 0.0% | 99.4% | 0.1% |
| BUILD_LIST | 41,920 | 0.0% | 99.5% |  |
| FOR_ITER_LIST | 40,480 | 0.0% | 99.5% |  |
| BINARY_SUBSCR_GETITEM | 40,080 | 0.0% | 99.5% |  |
| CALL_LIST_APPEND | 37,320 | 0.0% | 99.6% |  |
| COMPARE_OP_INT | 34,900 | 0.0% | 99.6% |  |
| FOR_ITER | 33,280 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_INT | 32,400 | 0.0% | 99.7% |  |
| COPY | 29,620 | 0.0% | 99.7% |  |
| CALL_BUILTIN_CLASS | 28,920 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,600 | 0.0% | 99.7% |  |
| JUMP_BACKWARD | 26,220 | 0.0% | 99.8% |  |
| TO_BOOL_NONE | 13,660 | 0.0% | 99.8% | 20.8% |
| STORE_SUBSCR_LIST_INT | 13,520 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 12,240 | 0.0% | 99.8% |  |
| TO_BOOL_STR | 11,860 | 0.0% | 99.8% | 0.5% |
| LOAD_NAME | 11,320 | 0.0% | 99.8% |  |
| COMPARE_OP | 10,220 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 9,820 | 0.0% | 99.8% | 0.8% |
| LOAD_ATTR_PROPERTY | 9,120 | 0.0% | 99.8% |  |
| UNARY_NOT | 8,720 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 8,560 | 0.0% | 99.9% |  |
| EXIT_INIT_CHECK | 7,820 | 0.0% | 99.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 7,820 | 0.0% | 99.9% |  |
| STORE_SUBSCR_DICT | 7,380 | 0.0% | 99.9% |  |
| BUILD_SLICE | 7,220 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TUPLE | 7,120 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 6,500 | 0.0% | 99.9% |  |
| BUILD_MAP | 6,140 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 5,840 | 0.0% | 99.9% |  |
| POP_EXCEPT | 5,840 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 5,840 | 0.0% | 99.9% |  |
| SWAP | 5,680 | 0.0% | 99.9% |  |
| BINARY_OP_MULTIPLY_INT | 5,380 | 0.0% | 99.9% |  |
| STORE_NAME | 5,180 | 0.0% | 99.9% |  |
| FOR_ITER_TUPLE | 5,180 | 0.0% | 99.9% |  |
| BINARY_SLICE | 4,920 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 4,860 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 4,740 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 4,720 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 4,440 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,520 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,500 | 0.0% | 100.0% | 5.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,440 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 2,900 | 0.0% | 100.0% |  |
| MAP_ADD | 2,040 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 1,980 | 0.0% | 100.0% | 34.3% |
| UNARY_INVERT | 1,960 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 1,620 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,400 | 0.0% | 100.0% |  |
| LOAD_DEREF | 1,380 | 0.0% | 100.0% |  |
| BUILD_STRING | 1,360 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 1,360 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 1,140 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 1,040 | 0.0% | 100.0% |  |
| STORE_ATTR | 840 | 0.0% | 100.0% |  |
| RESUME | 800 | 0.0% | 100.0% |  |
| BEFORE_WITH | 680 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 600 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 460 | 0.0% | 100.0% |  |
| STORE_SLICE | 440 | 0.0% | 100.0% |  |
| MAKE_CELL | 400 | 0.0% | 100.0% |  |
| DICT_MERGE | 300 | 0.0% | 100.0% |  |
| STORE_DEREF | 280 | 0.0% | 100.0% |  |
| LIST_EXTEND | 260 | 0.0% | 100.0% |  |
| YIELD_VALUE | 220 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 200 | 0.0% | 100.0% |  |
| CALL_STR_1 | 200 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 180 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 180 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 160 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 160 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 140 | 0.0% | 100.0% |  |
| STORE_ATTR_SLOT | 140 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 120 | 0.0% | 100.0% |  |
| IMPORT_FROM | 100 | 0.0% | 100.0% |  |
| DELETE_NAME | 80 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 60 | 0.0% | 100.0% |  |
| BUILD_SET | 60 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| DICT_UPDATE | 40 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_MODULE LOAD_CONST | 8,805,520 | 8.2% | 8.2% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 8,768,440 | 8.2% | 16.4% |
| CALL POP_TOP | 6,966,100 | 6.5% | 22.8% |
| BINARY_SUBSCR_LIST_INT LOAD_ATTR_METHOD_NO_DICT | 6,298,540 | 5.9% | 28.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 6,094,080 | 5.7% | 34.4% |
| LOAD_CONST CALL | 4,701,580 | 4.4% | 38.7% |
| POP_TOP ENTER_EXECUTOR | 4,347,840 | 4.0% | 42.8% |
| POP_TOP LOAD_GLOBAL_MODULE | 3,814,440 | 3.5% | 46.3% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 3,559,640 | 3.3% | 49.6% |
| LOAD_CONST LOAD_CONST | 2,990,940 | 2.8% | 52.4% |
| LOAD_CONST LOAD_GLOBAL_MODULE | 2,079,940 | 1.9% | 54.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,900,260 | 1.8% | 56.1% |
| BINARY_SUBSCR_LIST_INT CALL | 1,859,480 | 1.7% | 57.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,518,500 | 1.4% | 59.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 1,337,200 | 1.2% | 60.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,205,240 | 1.1% | 61.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 970,560 | 0.9% | 62.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 955,560 | 0.9% | 63.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 932,580 | 0.9% | 64.3% |
| RETURN_VALUE POP_TOP | 901,900 | 0.8% | 65.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 892,480 | 0.8% | 66.0% |
| LOAD_FAST CALL | 882,560 | 0.8% | 66.8% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 873,120 | 0.8% | 67.6% |
| CALL RETURN_VALUE | 872,920 | 0.8% | 68.4% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 870,980 | 0.8% | 69.2% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 869,980 | 0.8% | 70.0% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 867,920 | 0.8% | 70.8% |
| LOAD_FAST CALL_TYPE_1 | 866,140 | 0.8% | 71.6% |
| NOP LOAD_GLOBAL_MODULE | 864,680 | 0.8% | 72.4% |
| CALL_TYPE_1 LOAD_FAST_LOAD_FAST | 864,300 | 0.8% | 73.3% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 863,420 | 0.8% | 74.1% |
| BUILD_TUPLE BINARY_SUBSCR_DICT | 861,480 | 0.8% | 74.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 861,420 | 0.8% | 75.7% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 859,560 | 0.8% | 76.5% |
| ENTER_EXECUTOR CALL | 773,560 | 0.7% | 77.2% |
| PUSH_NULL LOAD_CONST | 756,940 | 0.7% | 77.9% |
| POP_JUMP_IF_FALSE NOP | 749,120 | 0.7% | 78.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 741,220 | 0.7% | 79.3% |
| RESUME_CHECK LOAD_FAST | 738,120 | 0.7% | 80.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 659,980 | 0.6% | 80.6% |
| STORE_FAST LOAD_FAST | 622,700 | 0.6% | 81.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 540,400 | 0.5% | 81.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 502,080 | 0.5% | 82.1% |
| LOAD_GLOBAL_MODULE IS_OP | 491,160 | 0.5% | 82.6% |
| IS_OP POP_JUMP_IF_FALSE | 463,240 | 0.4% | 83.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 406,040 | 0.4% | 83.4% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 396,260 | 0.4% | 83.8% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 393,000 | 0.4% | 84.1% |
| LOAD_FAST TO_BOOL_LIST | 388,200 | 0.4% | 84.5% |
| TO_BOOL POP_JUMP_IF_FALSE | 384,760 | 0.4% | 84.8% |
| LOAD_FAST TO_BOOL | 384,660 | 0.4% | 85.2% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 381,500 | 0.4% | 85.6% |
| POP_JUMP_IF_FALSE LOAD_CONST | 379,880 | 0.4% | 85.9% |
| CALL RESUME_CHECK | 377,900 | 0.4% | 86.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 376,820 | 0.4% | 86.6% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 375,860 | 0.3% | 87.0% |
| LOAD_CONST IMPORT_NAME | 375,800 | 0.3% | 87.3% |
| IMPORT_NAME STORE_FAST | 375,520 | 0.3% | 87.7% |
| LOAD_FAST LOAD_ATTR_MODULE | 375,480 | 0.3% | 88.0% |
| LOAD_CONST CALL_KW | 375,200 | 0.3% | 88.4% |
| LOAD_ATTR_MODULE LOAD_CONST | 375,040 | 0.3% | 88.7% |
| CALL_KW POP_TOP | 374,400 | 0.3% | 89.1% |
| LOAD_FAST UNPACK_EX | 374,400 | 0.3% | 89.4% |
| UNPACK_EX STORE_FAST_STORE_FAST | 374,400 | 0.3% | 89.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 374,220 | 0.3% | 90.1% |
| BINARY_SUBSCR_LIST_INT LOAD_GLOBAL_MODULE | 268,100 | 0.2% | 90.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 236,160 | 0.2% | 90.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 227,960 | 0.2% | 90.8% |
| LOAD_FAST LOAD_CONST | 216,480 | 0.2% | 91.0% |
| LOAD_FAST PUSH_NULL | 189,420 | 0.2% | 91.2% |
| CACHE RESUME_CHECK | 189,100 | 0.2% | 91.3% |
| BINARY_SUBSCR_LIST_INT CALL_PY_WITH_DEFAULTS | 181,120 | 0.2% | 91.5% |
| LOAD_FAST LOAD_ATTR | 177,700 | 0.2% | 91.7% |
| LOAD_ATTR STORE_FAST | 169,820 | 0.2% | 91.8% |
| RETURN_VALUE INTERPRETER_EXIT | 168,460 | 0.2% | 92.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 161,600 | 0.2% | 92.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 159,580 | 0.1% | 92.3% |
| STORE_FAST NOP | 156,200 | 0.1% | 92.4% |
| LOAD_CONST CALL_PY_WITH_DEFAULTS | 147,780 | 0.1% | 92.6% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 147,380 | 0.1% | 92.7% |
| POP_TOP LOAD_FAST | 143,020 | 0.1% | 92.8% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 142,880 | 0.1% | 93.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 142,060 | 0.1% | 93.1% |
| EXTENDED_ARG ENTER_EXECUTOR | 140,500 | 0.1% | 93.2% |
| POP_JUMP_IF_NONE LOAD_FAST | 139,100 | 0.1% | 93.4% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 138,960 | 0.1% | 93.5% |
| RETURN_VALUE RETURN_VALUE | 133,040 | 0.1% | 93.6% |
| CALL CALL | 115,260 | 0.1% | 93.7% |
| PUSH_NULL LOAD_FAST | 112,560 | 0.1% | 93.8% |
| LOAD_ATTR_MODULE CALL_PY_EXACT_ARGS | 111,820 | 0.1% | 93.9% |
| POP_TOP EXTENDED_ARG | 111,740 | 0.1% | 94.0% |
| CALL_BUILTIN_O POP_TOP | 99,140 | 0.1% | 94.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 97,560 | 0.1% | 94.2% |
| LOAD_CONST BINARY_OP_ADD_INT | 94,600 | 0.1% | 94.3% |
| RETURN_CONST POP_TOP | 91,920 | 0.1% | 94.4% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 89,180 | 0.1% | 94.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 85,360 | 0.1% | 94.5% |
| LOAD_CONST BINARY_SUBSCR | 83,740 | 0.1% | 94.6% |
| LOAD_CONST COMPARE_OP_STR | 82,700 | 0.1% | 94.7% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 82,480 | 0.1% | 94.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,580 | 93.1% |
| LOAD_FAST | 300 | 6.1% |
| BINARY_OP_ADD_INT | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,980 | 80.9% |
| LOAD_FAST | 340 | 6.9% |
| LOAD_CONST | 180 | 3.7% |
| CALL_PY_EXACT_ARGS | 180 | 3.7% |
| BUILD_TUPLE | 120 | 2.4% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 400 | 90.9% |
| LOAD_CONST | 40 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 280 | 63.6% |
| JUMP_BACKWARD | 120 | 27.3% |
| LOAD_FAST | 40 | 9.1% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 189,100 | 99.7% |
| COPY_FREE_VARS | 240 | 0.1% |
| RESUME | 200 | 0.1% |
| POP_TOP | 140 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 280 | 41.2% |
| RETURN_VALUE | 180 | 26.5% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 23.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 600 | 88.2% |
| STORE_FAST | 80 | 11.8% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 3,780 | 77.8% |
| BINARY_OP | 1,080 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,860 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 83,740 | 90.0% |
| BUILD_SLICE | 7,220 | 7.8% |
| LOAD_FAST | 2,000 | 2.1% |
| BINARY_SUBSCR | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 41,080 | 44.2% |
| LOAD_ATTR | 21,480 | 23.1% |
| CALL | 16,180 | 17.4% |
| GET_ITER | 7,040 | 7.6% |
| LOAD_GLOBAL | 2,880 | 3.1% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,840 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 70.0% |
| LOAD_CONST | 60 | 30.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 40.0% |
| JUMP_BACKWARD | 60 | 30.0% |
| RETURN_CONST | 60 | 30.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 7,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,820 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,240 | 68.4% |
| LOAD_FAST | 1,400 | 29.5% |
| LOAD_ATTR | 80 | 1.7% |
| STORE_FAST_LOAD_FAST | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,600 | 97.0% |
| BUILD_STRING | 140 | 3.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 20,500 | 29.1% |
| LOAD_FAST | 18,820 | 26.7% |
| LOAD_ATTR_INSTANCE_VALUE | 15,360 | 21.8% |
| BINARY_SUBSCR | 7,040 | 10.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,820 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 26,240 | 37.2% |
| FOR_ITER_RANGE | 22,060 | 31.3% |
| FOR_ITER_LIST | 11,960 | 17.0% |
| FOR_ITER | 7,600 | 10.8% |
| LOAD_FAST_AND_CLEAR | 1,340 | 1.9% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 168,460 | 92.2% |
| RETURN_CONST | 14,020 | 7.7% |
| YIELD_VALUE | 220 | 0.1% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 40 | 66.7% |
| DELETE_NAME | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 460 | 40.4% |
| STORE_NAME | 460 | 40.4% |
| CALL_BUILTIN_FAST | 80 | 7.0% |
| LOAD_CONST | 60 | 5.3% |
| CALL | 40 | 3.5% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 749,120 | 81.8% |
| STORE_FAST | 156,200 | 17.0% |
| RESUME_CHECK | 3,600 | 0.4% |
| NOP | 1,820 | 0.2% |
| STORE_FAST_STORE_FAST | 1,820 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 864,680 | 94.4% |
| LOAD_FAST | 42,040 | 4.6% |
| LOAD_FAST_LOAD_FAST | 3,940 | 0.4% |
| LOAD_CONST | 2,440 | 0.3% |
| NOP | 1,820 | 0.2% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,820 | 48.3% |
| STORE_ATTR_INSTANCE_VALUE | 2,820 | 48.3% |
| STORE_FAST | 200 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 2,820 | 48.3% |
| RETURN_CONST | 2,820 | 48.3% |
| ENTER_EXECUTOR | 160 | 2.7% |
| EXTENDED_ARG | 40 | 0.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 6,966,100 | 81.7% |
| RETURN_VALUE | 901,900 | 10.6% |
| CALL_KW | 374,400 | 4.4% |
| CALL_BUILTIN_O | 99,140 | 1.2% |
| RETURN_CONST | 91,920 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,347,840 | 51.0% |
| LOAD_GLOBAL_MODULE | 3,814,440 | 44.8% |
| LOAD_FAST | 143,020 | 1.7% |
| EXTENDED_ARG | 111,740 | 1.3% |
| LOAD_GLOBAL | 46,620 | 0.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 2,980 | 51.0% |
| BINARY_SUBSCR_STR_INT | 2,820 | 48.3% |
| STORE_SUBSCR | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,840 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 741,220 | 78.7% |
| LOAD_FAST | 189,420 | 20.1% |
| STORE_FAST_LOAD_FAST | 7,320 | 0.8% |
| LOAD_ATTR | 3,100 | 0.3% |
| LOAD_NAME | 880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 756,940 | 80.3% |
| LOAD_FAST | 112,560 | 11.9% |
| LOAD_GLOBAL_MODULE | 49,580 | 5.3% |
| LOAD_FAST_LOAD_FAST | 11,860 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 8,940 | 0.9% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 120 | 85.7% |
| CALL_PY_EXACT_ARGS | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 120 | 85.7% |
| CALL_METHOD_DESCRIPTOR_O | 20 | 14.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 872,920 | 39.6% |
| BINARY_SUBSCR_DICT | 869,980 | 39.4% |
| LOAD_ATTR_INSTANCE_VALUE | 138,960 | 6.3% |
| RETURN_VALUE | 133,040 | 6.0% |
| BINARY_SUBSCR_LIST_INT | 61,460 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 901,900 | 40.9% |
| LOAD_ATTR_METHOD_NO_DICT | 870,980 | 39.5% |
| INTERPRETER_EXIT | 168,460 | 7.6% |
| RETURN_VALUE | 133,040 | 6.0% |
| STORE_FAST | 44,580 | 2.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,300 | 35.4% |
| LOAD_FAST_LOAD_FAST | 1,960 | 30.2% |
| LOAD_CONST | 1,880 | 28.9% |
| BINARY_OP | 160 | 2.5% |
| STORE_SUBSCR | 120 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,280 | 35.1% |
| EXTENDED_ARG | 1,880 | 28.9% |
| JUMP_FORWARD | 1,440 | 22.2% |
| ENTER_EXECUTOR | 260 | 4.0% |
| LOAD_FAST_LOAD_FAST | 180 | 2.8% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 384,660 | 98.8% |
| LOAD_ATTR | 1,740 | 0.4% |
| BINARY_OP | 940 | 0.2% |
| ENTER_EXECUTOR | 880 | 0.2% |
| TO_BOOL | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 384,760 | 98.8% |
| POP_JUMP_IF_TRUE | 3,680 | 0.9% |
| TO_BOOL | 780 | 0.2% |
| TO_BOOL_BOOL | 140 | 0.0% |
| TO_BOOL_INT | 80 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,960 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 180 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 4,880 | 56.0% |
| TO_BOOL_LIST | 3,840 | 44.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,880 | 56.0% |
| CALL_PY_EXACT_ARGS | 3,840 | 44.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 71,420 | 74.8% |
| LOAD_FAST_LOAD_FAST | 7,540 | 7.9% |
| LOAD_FAST | 4,540 | 4.8% |
| RETURN_VALUE | 3,000 | 3.1% |
| LOAD_ATTR_INSTANCE_VALUE | 2,820 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 63,060 | 66.1% |
| STORE_FAST | 14,180 | 14.9% |
| LOAD_FAST | 4,880 | 5.1% |
| LOAD_CONST | 2,900 | 3.0% |
| RETURN_VALUE | 2,040 | 2.1% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 100 | 55.6% |
| RETURN_VALUE | 60 | 33.3% |
| DICT_UPDATE | 20 | 11.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,720 | 23.2% |
| POP_JUMP_IF_NOT_NONE | 8,000 | 19.1% |
| STORE_FAST | 7,940 | 18.9% |
| LOAD_CONST | 7,140 | 17.0% |
| POP_JUMP_IF_FALSE | 3,340 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 32,560 | 77.7% |
| LOAD_FAST | 5,940 | 14.2% |
| LOAD_GLOBAL_BUILTIN | 1,500 | 3.6% |
| SWAP | 1,320 | 3.1% |
| CALL_METHOD_DESCRIPTOR_O | 180 | 0.4% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,640 | 91.9% |
| LOAD_FAST | 160 | 2.6% |
| LOAD_CONST | 80 | 1.3% |
| CALL_INTRINSIC_1 | 60 | 1.0% |
| STORE_FAST | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,860 | 95.4% |
| LOAD_GLOBAL_BUILTIN | 80 | 1.3% |
| LOAD_CONST | 60 | 1.0% |
| STORE_FAST | 60 | 1.0% |
| STORE_NAME | 40 | 0.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 7,220 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,220 | 89.7% |
| FORMAT_SIMPLE | 140 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,120 | 82.4% |
| CALL_BUILTIN_O | 100 | 7.4% |
| LOAD_FAST | 80 | 5.9% |
| LOAD_CONST | 40 | 2.9% |
| YIELD_VALUE | 20 | 1.5% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 867,920 | 93.7% |
| CALL_BUILTIN_O | 23,880 | 2.6% |
| CALL | 9,400 | 1.0% |
| LOAD_FAST | 7,620 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 5,680 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 861,480 | 93.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 25,260 | 2.7% |
| LOAD_FAST | 11,280 | 1.2% |
| RETURN_VALUE | 6,820 | 0.7% |
| CALL_ISINSTANCE | 5,700 | 0.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,701,580 | 56.1% |
| BINARY_SUBSCR_LIST_INT | 1,859,480 | 22.2% |
| LOAD_FAST | 882,560 | 10.5% |
| ENTER_EXECUTOR | 773,560 | 9.2% |
| CALL | 115,260 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,966,100 | 83.1% |
| RETURN_VALUE | 872,920 | 10.4% |
| RESUME_CHECK | 377,900 | 4.5% |
| CALL | 115,260 | 1.4% |
| STORE_FAST | 20,480 | 0.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 46.2% |
| DICT_MERGE | 300 | 28.8% |
| LOAD_FAST | 140 | 13.5% |
| CALL_INTRINSIC_1 | 80 | 7.7% |
| RETURN_VALUE | 20 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 480 | 46.2% |
| RESUME_CHECK | 200 | 19.2% |
| RETURN_VALUE | 160 | 15.4% |
| COPY_FREE_VARS | 80 | 7.7% |
| STORE_FAST | 80 | 7.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 140 | 87.5% |
| IMPORT_NAME | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 50.0% |
| BUILD_MAP | 60 | 37.5% |
| POP_TOP | 20 | 12.5% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 375,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 374,400 | 99.8% |
| RESUME_CHECK | 680 | 0.2% |
| STORE_FAST | 80 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,960 | 77.9% |
| LOAD_FAST | 1,140 | 11.2% |
| LOAD_CONST | 300 | 2.9% |
| LOAD_ATTR_INSTANCE_VALUE | 260 | 2.5% |
| COMPARE_OP | 180 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,440 | 82.6% |
| POP_JUMP_IF_TRUE | 1,340 | 13.1% |
| COMPARE_OP | 180 | 1.8% |
| COMPARE_OP_STR | 160 | 1.6% |
| COMPARE_OP_INT | 60 | 0.6% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 72,420 | 66.6% |
| LOAD_FAST_LOAD_FAST | 27,460 | 25.3% |
| LOAD_CONST | 7,940 | 7.3% |
| LOAD_FAST | 580 | 0.5% |
| LOAD_ATTR_MODULE | 200 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 82,480 | 75.9% |
| EXTENDED_ARG | 23,480 | 21.6% |
| RETURN_VALUE | 1,740 | 1.6% |
| POP_JUMP_IF_TRUE | 920 | 0.8% |
| STORE_FAST | 80 | 0.1% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 9,800 | 33.1% |
| LOAD_CONST | 9,400 | 31.7% |
| UNARY_NOT | 4,880 | 16.5% |
| LOAD_FAST | 2,280 | 7.7% |
| BINARY_OP | 2,040 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 9,820 | 33.2% |
| STORE_FAST_STORE_FAST | 9,380 | 31.7% |
| TO_BOOL_BOOL | 4,980 | 16.8% |
| TO_BOOL_INT | 4,080 | 13.8% |
| COMPARE_OP_INT | 1,060 | 3.6% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 240 | 40.0% |
| CALL | 140 | 23.3% |
| CALL_PY_EXACT_ARGS | 120 | 20.0% |
| CALL_FUNCTION_EX | 80 | 13.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 20 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 420 | 70.0% |
| RETURN_GENERATOR | 120 | 20.0% |
| RESUME | 60 | 10.0% |


</details>

### DELETE_NAME

<details>
<summary> Successors and predecessors for DELETE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 40 | 50.0% |
| DELETE_NAME | 20 | 25.0% |
| STORE_NAME | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_BUILD_CLASS | 20 | 25.0% |
| DELETE_NAME | 20 | 25.0% |
| LOAD_CONST | 20 | 25.0% |
| LOAD_NAME | 20 | 25.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 220 | 73.3% |
| CALL | 80 | 26.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 300 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_CONST_KEY_MAP | 20 | 50.0% |
| MAP_ADD | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 20 | 50.0% |
| STORE_NAME | 20 | 50.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,347,840 | 95.8% |
| EXTENDED_ARG | 140,500 | 3.1% |
| POP_JUMP_IF_TRUE | 28,640 | 0.6% |
| STORE_FAST | 9,500 | 0.2% |
| STORE_SUBSCR_LIST_INT | 5,460 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,559,640 | 78.4% |
| CALL | 773,560 | 17.0% |
| CALL_PY_WITH_DEFAULTS | 38,100 | 0.8% |
| POP_JUMP_IF_FALSE | 32,200 | 0.7% |
| EXTENDED_ARG | 30,000 | 0.7% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 111,740 | 39.3% |
| JUMP_FORWARD | 32,460 | 11.4% |
| ENTER_EXECUTOR | 30,000 | 10.6% |
| GET_ITER | 26,240 | 9.2% |
| STORE_FAST | 23,820 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 140,500 | 49.4% |
| POP_JUMP_IF_FALSE | 39,180 | 13.8% |
| JUMP_FORWARD | 37,560 | 13.2% |
| FOR_ITER | 22,400 | 7.9% |
| FOR_ITER_LIST | 22,100 | 7.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 22,400 | 67.3% |
| GET_ITER | 7,600 | 22.8% |
| JUMP_BACKWARD | 2,660 | 8.0% |
| FOR_ITER | 460 | 1.4% |
| LOAD_FAST | 120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 16,180 | 48.6% |
| RETURN_CONST | 5,820 | 17.5% |
| LOAD_FAST | 2,820 | 8.5% |
| LOAD_GLOBAL_MODULE | 2,820 | 8.5% |
| STORE_FAST | 2,700 | 8.1% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 80 | 80.0% |
| STORE_NAME | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 100 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 375,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 375,520 | 99.9% |
| STORE_NAME | 180 | 0.0% |
| IMPORT_FROM | 80 | 0.0% |
| CALL_INTRINSIC_1 | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 491,160 | 99.2% |
| LOAD_GLOBAL_BUILTIN | 1,840 | 0.4% |
| LOAD_FAST | 1,800 | 0.4% |
| LOAD_CONST | 100 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 463,240 | 93.6% |
| POP_JUMP_IF_TRUE | 31,620 | 6.4% |
| COPY | 100 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 16,720 | 63.8% |
| EXTENDED_ARG | 6,540 | 24.9% |
| POP_JUMP_IF_FALSE | 440 | 1.7% |
| FOR_ITER_TUPLE | 420 | 1.6% |
| FOR_ITER | 360 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 13,660 | 52.1% |
| EXTENDED_ARG | 5,920 | 22.6% |
| FOR_ITER | 2,660 | 10.1% |
| ENTER_EXECUTOR | 1,540 | 5.9% |
| FOR_ITER_TUPLE | 1,140 | 4.3% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 37,560 | 48.3% |
| POP_TOP | 13,360 | 17.2% |
| STORE_FAST | 13,180 | 16.9% |
| POP_JUMP_IF_TRUE | 4,880 | 6.3% |
| POP_JUMP_IF_FALSE | 4,080 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 32,460 | 41.7% |
| LOAD_FAST | 19,500 | 25.1% |
| LOAD_GLOBAL_BUILTIN | 16,360 | 21.0% |
| LOAD_GLOBAL_MODULE | 4,780 | 6.1% |
| LOAD_FAST_LOAD_FAST | 3,700 | 4.8% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 660 | 47.1% |
| BUILD_TUPLE | 560 | 40.0% |
| CALL_BUILTIN_CLASS | 180 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,060 | 75.7% |
| JUMP_BACKWARD | 340 | 24.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 46.2% |
| LOAD_DEREF | 80 | 30.8% |
| LOAD_FAST | 60 | 23.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 140 | 53.8% |
| STORE_FAST | 60 | 23.1% |
| STORE_NAME | 40 | 15.4% |
| BINARY_OP | 20 | 7.7% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 177,700 | 76.7% |
| BINARY_SUBSCR | 21,480 | 9.3% |
| BINARY_SUBSCR_LIST_INT | 21,460 | 9.3% |
| LOAD_GLOBAL | 3,780 | 1.6% |
| LOAD_GLOBAL_MODULE | 3,760 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 169,820 | 73.3% |
| LOAD_ATTR_METHOD_NO_DICT | 21,720 | 9.4% |
| LOAD_CONST | 19,240 | 8.3% |
| LOAD_FAST | 5,260 | 2.3% |
| LOAD_ATTR_MODULE | 3,760 | 1.6% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,805,520 | 43.1% |
| LOAD_ATTR_METHOD_NO_DICT | 6,094,080 | 29.8% |
| LOAD_CONST | 2,990,940 | 14.6% |
| PUSH_NULL | 756,940 | 3.7% |
| LOAD_GLOBAL_BUILTIN | 396,260 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 8,768,440 | 42.9% |
| CALL | 4,701,580 | 23.0% |
| LOAD_CONST | 2,990,940 | 14.6% |
| LOAD_GLOBAL_MODULE | 2,079,940 | 10.2% |
| LOAD_GLOBAL_BUILTIN | 375,860 | 1.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 260 | 18.8% |
| POP_JUMP_IF_FALSE | 240 | 17.4% |
| STORE_FAST | 160 | 11.6% |
| NOP | 140 | 10.1% |
| RESUME_CHECK | 140 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 360 | 26.1% |
| LOAD_FAST | 300 | 21.7% |
| LOAD_CONST | 180 | 13.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 10.1% |
| LIST_EXTEND | 80 | 5.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,900,260 | 26.7% |
| POP_JUMP_IF_FALSE | 1,337,200 | 18.8% |
| RESUME_CHECK | 738,120 | 10.4% |
| STORE_FAST | 622,700 | 8.8% |
| LOAD_ATTR_METHOD_NO_DICT | 540,400 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,518,500 | 21.3% |
| CALL | 882,560 | 12.4% |
| CALL_TYPE_1 | 866,140 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 659,980 | 9.3% |
| TO_BOOL_LIST | 388,200 | 5.5% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,340 | 98.5% |
| LOAD_FAST_AND_CLEAR | 20 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,340 | 98.5% |
| LOAD_FAST_AND_CLEAR | 20 | 1.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 1,320 | 81.5% |
| POP_TOP | 300 | 18.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,320 | 81.5% |
| POP_JUMP_IF_NOT_NONE | 280 | 17.3% |
| TO_BOOL | 20 | 1.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 892,480 | 38.2% |
| CALL_TYPE_1 | 864,300 | 37.0% |
| LOAD_ATTR_METHOD_NO_DICT | 376,820 | 16.1% |
| STORE_ATTR_INSTANCE_VALUE | 50,560 | 2.2% |
| RESUME_CHECK | 32,500 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 873,120 | 37.4% |
| BUILD_TUPLE | 867,920 | 37.2% |
| LOAD_FAST | 393,000 | 16.8% |
| STORE_ATTR_INSTANCE_VALUE | 77,360 | 3.3% |
| LOAD_ATTR_INSTANCE_VALUE | 29,140 | 1.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 46,620 | 49.5% |
| LOAD_CONST | 30,220 | 32.1% |
| BINARY_SUBSCR | 2,880 | 3.1% |
| BINARY_SUBSCR_LIST_INT | 2,880 | 3.1% |
| STORE_FAST | 2,720 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 45,520 | 48.3% |
| LOAD_CONST | 42,320 | 44.9% |
| LOAD_ATTR | 3,780 | 4.0% |
| LOAD_GLOBAL_BUILTIN | 1,400 | 1.5% |
| LOAD_FAST | 380 | 0.4% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 3,320 | 29.3% |
| STORE_NAME | 2,380 | 21.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,120 | 9.9% |
| STORE_SUBSCR_DICT | 960 | 8.5% |
| LOAD_CONST | 860 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 3,320 | 29.3% |
| LOAD_CONST | 3,260 | 28.8% |
| CALL_METHOD_DESCRIPTOR_O | 1,080 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,080 | 9.5% |
| PUSH_NULL | 880 | 7.8% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 220 | 55.0% |
| CALL_PY_EXACT_ARGS | 120 | 30.0% |
| CALL | 60 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 220 | 55.0% |
| RESUME_CHECK | 160 | 40.0% |
| RESUME | 20 | 5.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,360 | 66.7% |
| LOAD_NAME | 680 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,200 | 58.8% |
| LOAD_CONST | 640 | 31.4% |
| JUMP_BACKWARD | 160 | 7.8% |
| BUILD_MAP | 20 | 1.0% |
| DICT_UPDATE | 20 | 1.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 955,560 | 37.2% |
| IS_OP | 463,240 | 18.0% |
| TO_BOOL | 384,760 | 15.0% |
| TO_BOOL_LIST | 381,500 | 14.8% |
| COMPARE_OP_STR | 89,180 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,337,200 | 52.0% |
| NOP | 749,120 | 29.1% |
| LOAD_CONST | 379,880 | 14.8% |
| LOAD_GLOBAL_MODULE | 37,040 | 1.4% |
| LOAD_FAST_LOAD_FAST | 13,660 | 0.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 142,880 | 94.6% |
| LOAD_FAST | 7,980 | 5.3% |
| LOAD_ATTR_MODULE | 120 | 0.1% |
| RETURN_VALUE | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 139,100 | 92.1% |
| LOAD_CONST | 9,460 | 6.3% |
| ENTER_EXECUTOR | 1,500 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 580 | 0.4% |
| LOAD_GLOBAL_MODULE | 360 | 0.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 161,600 | 96.5% |
| ENTER_EXECUTOR | 3,720 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,420 | 0.8% |
| CALL_BUILTIN_FAST | 440 | 0.3% |
| LOAD_FAST_CHECK | 280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 142,060 | 84.8% |
| BUILD_LIST | 8,000 | 4.8% |
| LOAD_GLOBAL_MODULE | 5,380 | 3.2% |
| LOAD_GLOBAL_BUILTIN | 4,160 | 2.5% |
| EXTENDED_ARG | 2,820 | 1.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 31,620 | 29.5% |
| TO_BOOL_INT | 26,800 | 25.0% |
| TO_BOOL_BOOL | 24,880 | 23.2% |
| TO_BOOL_STR | 9,840 | 9.2% |
| TO_BOOL_LIST | 4,180 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,020 | 39.3% |
| ENTER_EXECUTOR | 28,640 | 26.8% |
| CALL_LEN | 9,620 | 9.0% |
| LOAD_FAST_LOAD_FAST | 6,160 | 5.8% |
| LOAD_GLOBAL_MODULE | 5,500 | 5.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 52,360 | 38.6% |
| CALL_LIST_APPEND | 29,680 | 21.9% |
| POP_TOP | 13,920 | 10.3% |
| POP_JUMP_IF_FALSE | 13,240 | 9.8% |
| FOR_ITER | 5,820 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 91,920 | 67.7% |
| TO_BOOL_BOOL | 16,440 | 12.1% |
| INTERPRETER_EXIT | 14,020 | 10.3% |
| EXIT_INIT_CHECK | 7,820 | 5.8% |
| STORE_FAST | 5,340 | 3.9% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 460 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 43.5% |
| LOAD_GLOBAL_MODULE | 120 | 26.1% |
| STORE_NAME | 100 | 21.7% |
| CALL | 20 | 4.3% |
| LOAD_FAST | 20 | 4.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 460 | 54.8% |
| LOAD_FAST | 340 | 40.5% |
| SWAP | 40 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 42.9% |
| STORE_ATTR_INSTANCE_VALUE | 180 | 21.4% |
| LOAD_FAST_LOAD_FAST | 120 | 14.3% |
| NOP | 80 | 9.5% |
| RETURN_CONST | 40 | 4.8% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 80 | 28.6% |
| LOAD_ATTR | 40 | 14.3% |
| LOAD_CONST | 20 | 7.1% |
| STORE_FAST | 20 | 7.1% |
| BINARY_OP_ADD_UNICODE | 20 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 80 | 28.6% |
| LOAD_GLOBAL_BUILTIN | 80 | 28.6% |
| LOAD_CONST | 60 | 21.4% |
| LOAD_DEREF | 20 | 7.1% |
| LOAD_GLOBAL | 20 | 7.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 375,520 | 34.7% |
| LOAD_ATTR | 169,820 | 15.7% |
| LOAD_CONST | 55,880 | 5.2% |
| BINARY_OP_ADD_INT | 53,680 | 5.0% |
| LOAD_GLOBAL_MODULE | 48,640 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 622,700 | 57.5% |
| NOP | 156,200 | 14.4% |
| LOAD_GLOBAL_MODULE | 97,560 | 9.0% |
| LOAD_CONST | 55,260 | 5.1% |
| STORE_FAST | 43,320 | 4.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 7,320 | 85.5% |
| FOR_ITER_TUPLE | 1,220 | 14.3% |
| FOR_ITER | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 7,320 | 85.5% |
| TO_BOOL_STR | 660 | 7.7% |
| LOAD_FAST | 560 | 6.5% |
| FORMAT_SIMPLE | 20 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_EX | 374,400 | 86.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 47,160 | 10.8% |
| COPY | 9,380 | 2.2% |
| UNPACK_SEQUENCE_TUPLE | 3,520 | 0.8% |
| STORE_FAST_STORE_FAST | 360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 406,040 | 93.4% |
| LOAD_FAST_LOAD_FAST | 19,700 | 4.5% |
| STORE_FAST | 3,160 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 3,080 | 0.7% |
| NOP | 1,820 | 0.4% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,780 | 34.4% |
| FOR_ITER_TUPLE | 1,120 | 21.6% |
| FOR_ITER | 720 | 13.9% |
| MAKE_FUNCTION | 460 | 8.9% |
| RETURN_VALUE | 300 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,460 | 47.5% |
| LOAD_NAME | 2,380 | 45.9% |
| RETURN_CONST | 100 | 1.9% |
| POP_TOP | 80 | 1.5% |
| LOAD_BUILD_CLASS | 40 | 0.8% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 1,340 | 23.6% |
| BUILD_LIST | 1,320 | 23.2% |
| LOAD_FAST | 1,240 | 21.8% |
| FOR_ITER_TUPLE | 1,140 | 20.1% |
| BINARY_OP | 200 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,360 | 23.9% |
| BUILD_LIST | 1,320 | 23.2% |
| FOR_ITER_TUPLE | 1,120 | 19.7% |
| COPY | 1,100 | 19.4% |
| POP_TOP | 200 | 3.5% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 374,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 374,400 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 40 | 66.7% |
| RETURN_VALUE | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 40 | 66.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 33.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 120 | 54.5% |
| ENTER_EXECUTOR | 80 | 36.4% |
| BUILD_STRING | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 220 | 100.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 480 | 60.0% |
| CACHE | 200 | 25.0% |
| COPY_FREE_VARS | 60 | 7.5% |
| CALL_FUNCTION_EX | 40 | 5.0% |
| MAKE_CELL | 20 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 360 | 45.0% |
| LOAD_CONST | 120 | 15.0% |
| NOP | 100 | 12.5% |
| LOAD_FAST | 100 | 12.5% |
| LOAD_NAME | 60 | 7.5% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 94,600 | 92.9% |
| LOAD_FAST_LOAD_FAST | 5,080 | 5.0% |
| BINARY_OP_MULTIPLY_INT | 2,140 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,680 | 52.7% |
| LOAD_FAST | 42,860 | 42.1% |
| CALL_PY_EXACT_ARGS | 2,060 | 2.0% |
| CALL_BUILTIN_O | 1,600 | 1.6% |
| LOAD_FAST_LOAD_FAST | 740 | 0.7% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,080 | 69.4% |
| LOAD_FAST_LOAD_FAST | 660 | 14.9% |
| CALL_METHOD_DESCRIPTOR_O | 360 | 8.1% |
| BINARY_OP | 220 | 5.0% |
| BINARY_SUBSCR_LIST_INT | 120 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 1,200 | 27.0% |
| BUILD_TUPLE | 800 | 18.0% |
| LOAD_NAME | 800 | 18.0% |
| LOAD_FAST | 540 | 12.2% |
| RETURN_VALUE | 380 | 8.6% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,200 | 59.5% |
| BINARY_SUBSCR_TUPLE_INT | 2,140 | 39.8% |
| LOAD_ATTR | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,140 | 39.8% |
| LOAD_CONST | 1,600 | 29.7% |
| CALL_BUILTIN_O | 1,600 | 29.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.7% |


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
| LOAD_CONST | 11,660 | 36.0% |
| LOAD_FAST | 11,040 | 34.1% |
| CALL_LEN | 9,680 | 29.9% |
| BINARY_OP | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,680 | 29.9% |
| LOAD_FAST_LOAD_FAST | 9,460 | 29.2% |
| LOAD_FAST | 3,940 | 12.2% |
| LOAD_CONST | 3,660 | 11.3% |
| STORE_FAST | 2,920 | 9.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 861,480 | 97.8% |
| ENTER_EXECUTOR | 9,600 | 1.1% |
| LOAD_FAST | 7,260 | 0.8% |
| LOAD_FAST_LOAD_FAST | 2,280 | 0.3% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 869,980 | 98.8% |
| LOAD_CONST | 3,080 | 0.3% |
| PUSH_EXC_INFO | 2,980 | 0.3% |
| CALL_BUILTIN_O | 2,980 | 0.3% |
| STORE_FAST | 1,360 | 0.2% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 22,320 | 55.7% |
| LOAD_CONST | 10,760 | 26.8% |
| LOAD_FAST | 7,000 | 17.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 40,080 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,768,440 | 98.7% |
| LOAD_FAST | 63,440 | 0.7% |
| BINARY_SUBSCR | 41,080 | 0.5% |
| LOAD_FAST_LOAD_FAST | 2,840 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 2,480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,298,540 | 71.0% |
| CALL | 1,859,480 | 21.0% |
| LOAD_GLOBAL_MODULE | 268,100 | 3.0% |
| CALL_PY_WITH_DEFAULTS | 181,120 | 2.0% |
| LOAD_CONST | 147,380 | 1.7% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 34,060 | 60.0% |
| LOAD_FAST | 20,960 | 37.0% |
| ENTER_EXECUTOR | 1,640 | 2.9% |
| BINARY_SUBSCR_STR_INT | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 32,120 | 56.6% |
| STORE_FAST | 16,000 | 28.2% |
| BINARY_OP_INPLACE_ADD_UNICODE | 3,780 | 6.7% |
| PUSH_EXC_INFO | 2,820 | 5.0% |
| CALL_BUILTIN_O | 1,940 | 3.4% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,580 | 99.9% |
| BINARY_SUBSCR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,460 | 33.1% |
| CALL_BUILTIN_O | 6,260 | 21.9% |
| GET_ITER | 2,460 | 8.6% |
| LOAD_FAST | 2,220 | 7.8% |
| BINARY_OP_MULTIPLY_INT | 2,140 | 7.5% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,900 | 37.1% |
| LOAD_GLOBAL_MODULE | 2,820 | 36.1% |
| BINARY_SUBSCR | 1,880 | 24.0% |
| LOAD_FAST_LOAD_FAST | 140 | 1.8% |
| ENTER_EXECUTOR | 80 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,820 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 25,260 | 47.6% |
| LOAD_CONST | 15,180 | 28.6% |
| PUSH_NULL | 8,940 | 16.8% |
| LOAD_FAST | 3,640 | 6.9% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 52,760 | 99.4% |
| POP_TOP | 280 | 0.5% |
| COPY_FREE_VARS | 20 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 17,580 | 60.8% |
| CALL_LEN | 8,540 | 29.5% |
| CALL | 1,280 | 4.4% |
| CALL_BUILTIN_FAST | 680 | 2.4% |
| BINARY_OP_ADD_INT | 320 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 20,500 | 70.9% |
| LOAD_CONST | 7,040 | 24.3% |
| RETURN_VALUE | 680 | 2.4% |
| STORE_FAST | 420 | 1.5% |
| LIST_APPEND | 180 | 0.6% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,040 | 52.5% |
| LOAD_CONST | 620 | 31.3% |
| LOAD_FAST_LOAD_FAST | 120 | 6.1% |
| MAKE_FUNCTION | 80 | 4.0% |
| LOAD_ATTR_SLOT | 80 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 680 | 34.3% |
| POP_JUMP_IF_NOT_NONE | 440 | 22.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 340 | 17.2% |
| TO_BOOL_BOOL | 180 | 9.1% |
| POP_TOP | 160 | 8.1% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 2,820 | 80.6% |
| LOAD_FAST | 420 | 12.0% |
| LOAD_CONST | 200 | 5.7% |
| CALL_STR_1 | 60 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,240 | 92.6% |
| STORE_FAST | 180 | 5.1% |
| BEFORE_WITH | 60 | 1.7% |
| COPY | 20 | 0.6% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 78,120 | 59.2% |
| LOAD_GLOBAL_MODULE | 16,180 | 12.3% |
| LOAD_CONST | 10,480 | 7.9% |
| RETURN_VALUE | 7,040 | 5.3% |
| BINARY_SUBSCR_TUPLE_INT | 6,260 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 99,140 | 75.1% |
| BUILD_TUPLE | 23,880 | 18.1% |
| TO_BOOL_BOOL | 6,840 | 5.2% |
| STORE_FAST | 2,020 | 1.5% |
| TO_BOOL_INT | 80 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 859,560 | 91.3% |
| LOAD_GLOBAL_BUILTIN | 72,040 | 7.7% |
| BUILD_TUPLE | 5,700 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,720 | 0.2% |
| LOAD_ATTR_SLOT | 1,720 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 932,580 | 99.1% |
| RETURN_VALUE | 5,640 | 0.6% |
| LOAD_FAST | 2,820 | 0.3% |
| TO_BOOL | 40 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,320 | 55.0% |
| LOAD_ATTR_INSTANCE_VALUE | 26,640 | 28.5% |
| POP_JUMP_IF_TRUE | 9,620 | 10.3% |
| LOAD_GLOBAL_MODULE | 5,640 | 6.0% |
| LOAD_CONST | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 26,400 | 28.3% |
| LOAD_CONST | 13,380 | 14.3% |
| LOAD_FAST | 10,440 | 11.2% |
| BINARY_OP_SUBTRACT_INT | 9,680 | 10.4% |
| CALL_BUILTIN_CLASS | 8,540 | 9.1% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,600 | 79.3% |
| BUILD_TUPLE | 2,880 | 7.7% |
| LOAD_GLOBAL_MODULE | 2,820 | 7.6% |
| LOAD_CONST | 1,680 | 4.5% |
| ENTER_EXECUTOR | 260 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 29,680 | 79.5% |
| LOAD_FAST | 4,420 | 11.8% |
| ENTER_EXECUTOR | 1,580 | 4.2% |
| EXTENDED_ARG | 1,240 | 3.3% |
| LOAD_FAST_LOAD_FAST | 180 | 0.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000 | 49.0% |
| LOAD_CONST | 2,820 | 23.0% |
| LOAD_FAST_LOAD_FAST | 1,260 | 10.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,140 | 9.3% |
| LOAD_GLOBAL_MODULE | 820 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,320 | 92.5% |
| LIST_APPEND | 660 | 5.4% |
| POP_TOP | 120 | 1.0% |
| LOAD_FAST | 80 | 0.7% |
| SWAP | 60 | 0.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 33,280 | 55.3% |
| BINARY_SUBSCR_LIST_INT | 26,000 | 43.2% |
| CALL | 700 | 1.2% |
| LOAD_GLOBAL_MODULE | 180 | 0.3% |
| LOAD_ATTR_METHOD_NO_DICT | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 59,900 | 99.5% |
| LOAD_CONST | 180 | 0.3% |
| STORE_FAST | 60 | 0.1% |
| STORE_DEREF | 20 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 20 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,500 | 99.4% |
| CALL | 20 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,820 | 80.1% |
| BUILD_TUPLE | 540 | 15.3% |
| TO_BOOL_BOOL | 120 | 3.4% |
| RETURN_VALUE | 40 | 1.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,180 | 42.6% |
| RETURN_VALUE | 1,500 | 15.3% |
| LOAD_NAME | 1,080 | 11.0% |
| LOAD_GLOBAL_MODULE | 920 | 9.4% |
| STORE_FAST | 660 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,640 | 67.6% |
| RETURN_VALUE | 1,600 | 16.3% |
| CALL_METHOD_DESCRIPTOR_O | 640 | 6.5% |
| BINARY_OP_ADD_UNICODE | 360 | 3.7% |
| LOAD_CONST | 280 | 2.9% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 873,120 | 72.4% |
| LOAD_FAST | 159,580 | 13.2% |
| LOAD_ATTR_MODULE | 111,820 | 9.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 35,520 | 2.9% |
| LOAD_CONST | 4,920 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,205,240 | 100.0% |
| COPY_FREE_VARS | 120 | 0.0% |
| MAKE_CELL | 120 | 0.0% |
| RETURN_GENERATOR | 20 | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 181,120 | 48.4% |
| LOAD_CONST | 147,780 | 39.5% |
| ENTER_EXECUTOR | 38,100 | 10.2% |
| LOAD_FAST_LOAD_FAST | 2,900 | 0.8% |
| LOAD_FAST | 2,260 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 374,220 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 60.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 30.0% |
| CALL_BUILTIN_O | 20 | 10.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,820 | 97.2% |
| LOAD_GLOBAL_MODULE | 60 | 2.1% |
| CALL_BUILTIN_CLASS | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,820 | 97.2% |
| CALL | 60 | 2.1% |
| STORE_DEREF | 20 | 0.7% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 866,140 | 100.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 864,300 | 99.8% |
| LOAD_FAST | 1,720 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| PUSH_NULL | 60 | 0.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 21,380 | 61.3% |
| LOAD_GLOBAL_MODULE | 7,240 | 20.7% |
| CALL_LEN | 2,620 | 7.5% |
| BINARY_SUBSCR_LIST_INT | 1,420 | 4.1% |
| COPY | 1,060 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,440 | 98.7% |
| POP_JUMP_IF_TRUE | 340 | 1.0% |
| RETURN_VALUE | 60 | 0.2% |
| STORE_FAST | 60 | 0.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 82,700 | 83.0% |
| LOAD_ATTR_INSTANCE_VALUE | 16,720 | 16.8% |
| COMPARE_OP | 160 | 0.2% |
| LOAD_FAST | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 89,180 | 89.5% |
| EXTENDED_ARG | 10,440 | 10.5% |
| COMPARE_OP | 60 | 0.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 22,100 | 54.6% |
| GET_ITER | 11,960 | 29.5% |
| ENTER_EXECUTOR | 5,600 | 13.8% |
| JUMP_BACKWARD | 800 | 2.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 16,420 | 40.6% |
| LOAD_GLOBAL_BUILTIN | 9,400 | 23.2% |
| STORE_FAST | 6,080 | 15.0% |
| LOAD_FAST_LOAD_FAST | 3,020 | 7.5% |
| LOAD_FAST | 2,900 | 7.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 22,620 | 29.9% |
| GET_ITER | 22,060 | 29.1% |
| EXTENDED_ARG | 15,900 | 21.0% |
| JUMP_BACKWARD | 13,660 | 18.0% |
| FOR_ITER | 1,260 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 46,780 | 61.8% |
| LOAD_GLOBAL_BUILTIN | 14,000 | 18.5% |
| LOAD_FAST | 8,540 | 11.3% |
| RETURN_CONST | 3,840 | 5.1% |
| LOAD_GLOBAL | 2,040 | 2.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,720 | 33.2% |
| JUMP_BACKWARD | 1,140 | 22.0% |
| GET_ITER | 1,120 | 21.6% |
| SWAP | 1,120 | 21.6% |
| FOR_ITER | 60 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 1,220 | 23.6% |
| SWAP | 1,140 | 22.0% |
| STORE_NAME | 1,120 | 21.6% |
| LOAD_NAME | 500 | 9.7% |
| JUMP_BACKWARD | 420 | 8.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 659,980 | 93.8% |
| LOAD_FAST_LOAD_FAST | 29,140 | 4.1% |
| LOAD_ATTR_INSTANCE_VALUE | 14,100 | 2.0% |
| LOAD_ATTR | 240 | 0.0% |
| COPY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 227,960 | 32.4% |
| POP_JUMP_IF_NONE | 142,880 | 20.3% |
| RETURN_VALUE | 138,960 | 19.7% |
| STORE_FAST | 39,260 | 5.6% |
| LOAD_ATTR_METHOD_NO_DICT | 31,440 | 4.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 6,298,540 | 86.8% |
| RETURN_VALUE | 870,980 | 12.0% |
| LOAD_ATTR_INSTANCE_VALUE | 31,440 | 0.4% |
| LOAD_ATTR | 21,720 | 0.3% |
| LOAD_FAST | 19,700 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,094,080 | 84.0% |
| LOAD_FAST | 540,400 | 7.4% |
| LOAD_FAST_LOAD_FAST | 376,820 | 5.2% |
| LOAD_GLOBAL_MODULE | 236,160 | 3.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,500 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,780 | 91.6% |
| BINARY_SUBSCR_TUPLE_INT | 1,600 | 3.8% |
| BINARY_SUBSCR | 1,540 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 320 | 0.8% |
| LOAD_GLOBAL_MODULE | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 35,520 | 83.9% |
| LOAD_FAST | 3,700 | 8.7% |
| LOAD_CONST | 2,040 | 4.8% |
| LOAD_GLOBAL_MODULE | 940 | 2.2% |
| LOAD_FAST_LOAD_FAST | 120 | 0.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 861,420 | 69.4% |
| LOAD_FAST | 375,480 | 30.3% |
| LOAD_ATTR | 3,760 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 741,220 | 59.7% |
| LOAD_CONST | 375,040 | 30.2% |
| CALL_PY_EXACT_ARGS | 111,820 | 9.0% |
| STORE_FAST | 5,900 | 0.5% |
| CALL | 1,960 | 0.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,720 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,720 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 1,720 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 1,720 | 50.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,640 | 61.8% |
| LOAD_FAST | 3,480 | 38.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,120 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,020 | 42.8% |
| LOAD_FAST_LOAD_FAST | 1,720 | 36.4% |
| LOAD_ATTR_MODULE | 860 | 18.2% |
| RETURN_VALUE | 120 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,720 | 36.4% |
| CALL_ISINSTANCE | 1,720 | 36.4% |
| LOAD_FAST | 820 | 17.4% |
| LOAD_CONST | 240 | 5.1% |
| STORE_FAST | 120 | 2.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 970,560 | 39.8% |
| LOAD_GLOBAL_MODULE | 863,420 | 35.4% |
| LOAD_CONST | 375,860 | 15.4% |
| LOAD_FAST | 80,480 | 3.3% |
| STORE_FAST | 32,660 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,900,260 | 78.0% |
| LOAD_CONST | 396,260 | 16.3% |
| CALL_ISINSTANCE | 72,040 | 3.0% |
| STORE_FAST | 23,480 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 13,700 | 0.6% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,814,440 | 29.1% |
| ENTER_EXECUTOR | 3,559,640 | 27.1% |
| LOAD_CONST | 2,079,940 | 15.9% |
| LOAD_FAST | 1,518,500 | 11.6% |
| NOP | 864,680 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,805,520 | 67.1% |
| LOAD_FAST_LOAD_FAST | 892,480 | 6.8% |
| LOAD_GLOBAL_BUILTIN | 863,420 | 6.6% |
| LOAD_ATTR_MODULE | 861,420 | 6.6% |
| CALL_ISINSTANCE | 859,560 | 6.6% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 160 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,205,240 | 53.3% |
| CALL | 377,900 | 16.7% |
| CALL_PY_WITH_DEFAULTS | 374,220 | 16.5% |
| CACHE | 189,100 | 8.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 52,760 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 970,560 | 42.9% |
| LOAD_FAST | 738,120 | 32.6% |
| LOAD_GLOBAL_MODULE | 502,080 | 22.2% |
| LOAD_FAST_LOAD_FAST | 32,500 | 1.4% |
| BUILD_LIST | 9,720 | 0.4% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 85,360 | 51.5% |
| LOAD_FAST_LOAD_FAST | 77,360 | 46.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,820 | 1.7% |
| STORE_ATTR | 180 | 0.1% |
| SWAP | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 52,360 | 31.6% |
| LOAD_FAST_LOAD_FAST | 50,560 | 30.5% |
| LOAD_FAST | 29,720 | 17.9% |
| LOAD_CONST | 21,480 | 12.9% |
| BUILD_MAP | 5,640 | 3.4% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 80 | 57.1% |
| LOAD_FAST | 40 | 28.6% |
| LOAD_ATTR_SLOT | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,940 | 80.5% |
| BINARY_OP_ADD_UNICODE | 1,200 | 16.3% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 2.2% |
| STORE_SUBSCR | 80 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,940 | 39.8% |
| LOAD_GLOBAL_BUILTIN | 2,820 | 38.2% |
| LOAD_NAME | 960 | 13.0% |
| JUMP_BACKWARD | 320 | 4.3% |
| LOAD_GLOBAL_MODULE | 160 | 2.2% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,980 | 81.2% |
| LOAD_FAST | 2,540 | 18.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,460 | 40.4% |
| RETURN_CONST | 4,360 | 32.2% |
| EXTENDED_ARG | 3,480 | 25.7% |
| LOAD_FAST | 140 | 1.0% |
| JUMP_BACKWARD | 80 | 0.6% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 932,580 | 94.8% |
| RETURN_CONST | 16,440 | 1.7% |
| LOAD_FAST | 9,100 | 0.9% |
| RETURN_VALUE | 7,680 | 0.8% |
| CALL_BUILTIN_O | 6,840 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 955,560 | 97.1% |
| POP_JUMP_IF_TRUE | 24,880 | 2.5% |
| EXTENDED_ARG | 3,460 | 0.4% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 63,060 | 56.9% |
| LOAD_FAST | 43,380 | 39.2% |
| COPY | 4,080 | 3.7% |
| TO_BOOL | 80 | 0.1% |
| CALL_BUILTIN_O | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 79,060 | 71.4% |
| POP_JUMP_IF_TRUE | 26,800 | 24.2% |
| UNARY_NOT | 4,880 | 4.4% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,200 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,340 | 0.3% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 381,500 | 97.9% |
| POP_JUMP_IF_TRUE | 4,180 | 1.1% |
| UNARY_NOT | 3,840 | 1.0% |
| TO_BOOL_NONE | 40 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,160 | 96.3% |
| ENTER_EXECUTOR | 420 | 3.1% |
| TO_BOOL | 40 | 0.3% |
| TO_BOOL_LIST | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,580 | 99.4% |
| TO_BOOL | 60 | 0.4% |
| POP_JUMP_IF_TRUE | 20 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 9,820 | 82.8% |
| LOAD_FAST | 1,360 | 11.5% |
| STORE_FAST_LOAD_FAST | 660 | 5.6% |
| TO_BOOL | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 9,840 | 83.0% |
| POP_JUMP_IF_FALSE | 2,020 | 17.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,800 | 53.4% |
| RETURN_VALUE | 3,040 | 42.7% |
| BINARY_SUBSCR_TUPLE_INT | 140 | 2.0% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 1.7% |
| BUILD_TUPLE | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,580 | 50.3% |
| STORE_FAST_STORE_FAST | 3,520 | 49.4% |
| STORE_DEREF | 20 | 0.3% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 43,520 | 55.8% |
| FOR_ITER_LIST | 16,420 | 21.0% |
| FOR_ITER | 16,180 | 20.7% |
| BINARY_SUBSCR_LIST_INT | 1,340 | 1.7% |
| CALL_BUILTIN_FAST | 340 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 47,160 | 60.4% |
| STORE_FAST | 30,900 | 39.6% |


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
|     deferred | 93,980 | 38.5% |
|          hit | 148,960 | 60.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 18.9% |
| Failure | 1,200 | 81.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 620 | 51.7% |
| or | 220 | 18.3% |
| and different types | 120 | 10.0% |
| multiply different types | 80 | 6.7% |
| remainder | 80 | 6.7% |
| add other | 60 | 5.0% |
| floor divide | 20 | 1.7% |


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
|     deferred | 51,640 | 0.5% |
|          hit | 9,875,640 | 99.0% |
|         miss | 10,000 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 41,360 | 99.9% |
| Failure | 40 | 0.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 20 | 50.0% |
| list slice | 20 | 50.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,261,600 | 67.3% |
|          hit | 3,884,820 | 31.7% |
|         miss | 1,760 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,500 | 3.8% |
| Failure | 115,220 | 96.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 107,900 | 93.6% |
| code complex parameters | 6,900 | 6.0% |
| cfunc varargs keywords | 120 | 0.1% |
| meth descr varargs | 120 | 0.1% |
| cfunc noargs | 60 | 0.1% |
| class no vectorcall | 60 | 0.1% |
| wrong number arguments | 40 | 0.0% |
| class mutable | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,760 | 6.7% |
|          hit | 131,840 | 91.0% |
|         miss | 2,860 | 2.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 47.8% |
| Failure | 240 | 52.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 100 | 41.7% |
| other | 60 | 25.0% |
| big int | 60 | 25.0% |
| tuple | 20 | 8.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 31,480 | 20.4% |
|          hit | 121,340 | 78.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,340 | 74.4% |
| Failure | 460 | 25.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| itertools | 160 | 34.8% |
| set | 120 | 26.1% |
| dict items | 80 | 17.4% |
| dict keys | 40 | 8.7% |
| seq iter | 40 | 8.7% |
| map | 20 | 4.3% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 205,460 | 2.2% |
|          hit | 9,259,560 | 97.6% |
|         miss | 140 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 25,720 | 97.6% |
| Failure | 640 | 2.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 260 | 40.6% |
| metaclass attribute | 160 | 25.0% |
| mutable class | 100 | 15.6% |
| not managed dict | 100 | 15.6% |
| class attr simple | 20 | 3.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 46,860 | 0.3% |
|          hit | 15,532,960 | 99.2% |
|         miss | 25,440 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 47,380 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 160 | 100.0% |


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
|     deferred | 660 | 0.4% |
|          hit | 166,020 | 99.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
| Failure | 0 | 0.0% |


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
|     deferred | 6,300 | 23.0% |
|          hit | 20,900 | 76.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 40.0% |
| Failure | 120 | 60.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytearray int | 80 | 66.7% |
| out of range | 20 | 16.7% |
| py simple | 20 | 16.7% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 388,320 | 20.4% |
|          hit | 1,505,540 | 79.3% |
|         miss | 4,200 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 28.3% |
| Failure | 860 | 71.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 360 | 41.9% |
| other | 220 | 25.6% |
| mapping | 100 | 11.6% |
| number | 100 | 11.6% |
| dict | 80 | 9.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 85,180 | 99.9% |

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
| Basic | 52,154,740 | 48.5% |
| Not specialized | 12,343,740 | 11.5% |
| Specialized hits | 42,937,740 | 39.9% |
| Specialized misses | 44,400 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,261,600 | 90.8% |
| TO_BOOL | 388,320 | 4.3% |
| LOAD_ATTR | 205,460 | 2.3% |
| BINARY_OP | 93,980 | 1.0% |
| BINARY_SUBSCR | 51,640 | 0.6% |
| LOAD_GLOBAL | 46,860 | 0.5% |
| FOR_ITER | 31,480 | 0.3% |
| COMPARE_OP | 9,760 | 0.1% |
| STORE_SUBSCR | 6,300 | 0.1% |
| STORE_ATTR | 660 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 25,000 | 56.3% |
| BINARY_SUBSCR_LIST_INT | 7,120 | 16.0% |
| BINARY_SUBSCR_STR_INT | 2,880 | 6.5% |
| COMPARE_OP_STR | 2,860 | 6.4% |
| TO_BOOL_NONE | 2,840 | 6.4% |
| TO_BOOL_INT | 1,060 | 2.4% |
| CALL_BUILTIN_FAST | 680 | 1.5% |
| LOAD_GLOBAL_BUILTIN | 440 | 1.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 360 | 0.8% |
| CALL_PY_EXACT_ARGS | 340 | 0.8% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 189,680 | 8.4% |
| Calls to Python functions inlined | 2,069,100 | 91.6% |
| Calls via PyEval_EvalFrame (total) | 189,680 | 8.4% |
| Calls via PyEval_EvalFrame (vector) | 189,320 | 8.4% |
| Calls via PyEval_EvalFrame (generator) | 360 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 189,180 | 8.4% |
| Calls via PyEval_EvalFrame (build class) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 46,860 | 2.1% |
| Calls via PyEval_EvalFrame (function ex) | 320 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,680 | 0.1% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 397,720 | 17.6% |
| Frames pushed | 1,781,000 | 78.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 5,029,180 | 16.5% |
| Frees to freelist | 5,032,180 |  |
| Allocations | 25,368,160 | 83.5% |
| Allocations to 512 bytes | 25,185,880 | 82.9% |
| Allocations to 4 kbytes | 158,840 | 0.5% |
| Allocations over 4 kbytes | 23,440 | 0.1% |
| Frees | 35,384,476 |  |
| New values | 9,480 |  |
| Interpreter increfs | 54,882,800 | 61.9% |
| Interpreter decrefs | 65,514,380 | 61.5% |
| Increfs | 33,760,565 | 38.1% |
| Decrefs | 41,019,027 | 38.5% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 627,141 |  |
| Method cache misses | 2,799 |  |
| Method cache collisions | 3,113 |  |
| Method cache dunder hits | 3,255,772 |  |
| Method cache dunder misses | 628 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 1,920 | 167,840 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 1,540 |  |
| Traces created | 1,540 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 100 | 6.5% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 40 | 2.6% |
| Recursive call | 0 | 0.0% |
| Traces executed | 4,540,440 |  |
| Uops executed | 45,301,860 | 9.98 |

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
| <= 32 | 440 | 28.6% |
| <= 64 | 920 | 59.7% |
| <= 128 | 180 | 11.7% |


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
| <= 16 | 520 | 33.8% |
| <= 32 | 800 | 51.9% |
| <= 64 | 140 | 9.1% |
| <= 128 | 80 | 5.2% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 10,020 | 0.2% |
| <= 2 | 20,800 | 0.5% |
| <= 4 | 26,760 | 0.6% |
| <= 8 | 3,563,820 | 78.5% |
| <= 16 | 437,460 | 9.6% |
| <= 32 | 423,120 | 9.3% |
| <= 64 | 21,260 | 0.5% |
| <= 128 | 34,980 | 0.8% |
| <= 256 | 1,240 | 0.0% |
| <= 512 | 660 | 0.0% |
| <= 1,024 | 280 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 0 | 0.0% |
| <= 16,384 | 40 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 5,612,580 | 12.4% | 12.4% |  |
| _CHECK_VALIDITY | 5,516,960 | 12.2% | 24.6% |  |
| _GUARD_GLOBALS_VERSION | 5,050,040 | 11.1% | 35.7% | 70.5% |
| STORE_FAST | 4,663,640 | 10.3% | 46.0% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 4,450,820 | 9.8% | 55.8% | 0.6% |
| _ITER_CHECK_RANGE | 4,450,820 | 9.8% | 65.7% |  |
| _ITER_NEXT_RANGE | 4,423,100 | 9.8% | 75.4% |  |
| LOAD_CONST | 2,663,620 | 5.9% | 81.3% |  |
| _LOAD_GLOBAL_MODULE | 1,465,860 | 3.2% | 84.5% |  |
| BINARY_SUBSCR_LIST_INT | 1,154,940 | 2.5% | 87.1% |  |
| _EXIT_TRACE | 874,120 | 1.9% | 89.0% |  |
| _GUARD_TYPE_VERSION | 844,800 | 1.9% | 90.9% |  |
| LOAD_FAST | 821,260 | 1.8% | 92.7% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 710,480 | 1.6% | 94.3% |  |
| PUSH_NULL | 201,940 | 0.4% | 94.7% |  |
| _CHECK_ATTR_MODULE | 154,440 | 0.3% | 95.1% |  |
| _LOAD_ATTR_MODULE | 154,440 | 0.3% | 95.4% |  |
| _GUARD_IS_FALSE_POP | 150,320 | 0.3% | 95.7% | 12.4% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 105,040 | 0.2% | 96.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 105,040 | 0.2% | 96.2% |  |
| _CHECK_PEP_523 | 84,060 | 0.2% | 96.4% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 84,060 | 0.2% | 96.6% |  |
| _CHECK_STACK_SPACE | 84,060 | 0.2% | 96.7% |  |
| _INIT_CALL_PY_EXACT_ARGS | 84,060 | 0.2% | 96.9% |  |
| _PUSH_FRAME | 84,060 | 0.2% | 97.1% |  |
| _SAVE_RETURN_OFFSET | 84,060 | 0.2% | 97.3% |  |
| CONTAINS_OP | 82,820 | 0.2% | 97.5% |  |
| _GUARD_IS_TRUE_POP | 80,700 | 0.2% | 97.7% | 23.2% |
| RESUME_CHECK | 79,440 | 0.2% | 97.8% |  |
| _ITER_CHECK_LIST | 75,580 | 0.2% | 98.0% | 13.3% |
| IS_OP | 73,760 | 0.2% | 98.2% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 65,560 | 0.1% | 98.3% | 28.6% |
| _ITER_NEXT_LIST | 46,840 | 0.1% | 98.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 44,960 | 0.1% | 98.5% |  |
| POP_TOP | 41,420 | 0.1% | 98.6% |  |
| _JUMP_TO_TOP | 38,100 | 0.1% | 98.7% |  |
| _GUARD_IS_NOT_NONE_POP | 30,620 | 0.1% | 98.8% | 9.1% |
| _GUARD_BOTH_INT | 27,920 | 0.1% | 98.8% |  |
| CALL_BUILTIN_O | 27,680 | 0.1% | 98.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 27,200 | 0.1% | 98.9% |  |
| _GUARD_KEYS_VERSION | 27,200 | 0.1% | 99.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 27,200 | 0.1% | 99.1% |  |
| _BINARY_OP | 26,300 | 0.1% | 99.1% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 24,720 | 0.1% | 99.2% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 24,720 | 0.1% | 99.2% |  |
| BINARY_SUBSCR_STR_INT | 24,660 | 0.1% | 99.3% | 6.7% |
| _GUARD_BUILTINS_VERSION | 24,440 | 0.1% | 99.3% | 0.2% |
| _LOAD_GLOBAL_BUILTINS | 24,380 | 0.1% | 99.4% |  |
| COMPARE_OP_STR | 23,080 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 21,660 | 0.0% | 99.5% |  |
| TO_BOOL_BOOL | 21,500 | 0.0% | 99.5% |  |
| _BINARY_OP_ADD_INT | 21,160 | 0.0% | 99.6% |  |
| TO_BOOL_INT | 18,280 | 0.0% | 99.6% |  |
| _STORE_SUBSCR | 16,000 | 0.0% | 99.7% |  |
| CALL_ISINSTANCE | 15,660 | 0.0% | 99.7% |  |
| _FOR_ITER_TIER_TWO | 13,500 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 13,060 | 0.0% | 99.8% |  |
| BINARY_SLICE | 12,100 | 0.0% | 99.8% |  |
| BUILD_TUPLE | 10,180 | 0.0% | 99.8% |  |
| _LOAD_ATTR | 9,760 | 0.0% | 99.8% |  |
| CALL_TYPE_1 | 9,600 | 0.0% | 99.8% |  |
| _BINARY_OP_SUBTRACT_INT | 6,760 | 0.0% | 99.9% |  |
| LOAD_NAME | 6,320 | 0.0% | 99.9% |  |
| COMPARE_OP_INT | 5,160 | 0.0% | 99.9% |  |
| _TO_BOOL | 4,600 | 0.0% | 99.9% |  |
| TO_BOOL_NONE | 4,420 | 0.0% | 99.9% | 29.4% |
| STORE_SUBSCR_LIST_INT | 4,420 | 0.0% | 99.9% |  |
| CALL_LEN | 4,340 | 0.0% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 3,840 | 0.0% | 99.9% | 44.8% |
| _ITER_CHECK_TUPLE | 3,840 | 0.0% | 99.9% |  |
| LIST_APPEND | 2,840 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 2,360 | 0.0% | 100.0% |  |
| COPY | 2,240 | 0.0% | 100.0% |  |
| UNARY_NOT | 2,160 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 2,120 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 2,080 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 2,080 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 1,900 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 1,380 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 1,380 | 0.0% | 100.0% |  |
| STORE_NAME | 1,160 | 0.0% | 100.0% |  |
| _POP_FRAME | 1,100 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 1,080 | 0.0% | 100.0% | 85.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 780 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 780 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 720 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 340 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 280 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 200 | 0.0% | 100.0% |  |
| BUILD_STRING | 180 | 0.0% | 100.0% |  |
| GET_ITER | 160 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 160 | 0.0% | 100.0% |  |
| _STORE_ATTR | 100 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 80 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% | 100.0% |  |
| _BINARY_SUBSCR | 60 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 1,160 |
| CALL_PY_WITH_DEFAULTS | 60 |
| BINARY_SUBSCR_GETITEM | 20 |
| CALL_LIST_APPEND | 20 |


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
