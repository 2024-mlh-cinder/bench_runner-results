
# Pystats results

- benchmark: regex_v8
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_CONST | 20,431,660 | 19.0% | 19.0% |  |
| LOAD_GLOBAL_MODULE | 13,137,560 | 12.2% | 31.2% | 0.2% |
| BINARY_SUBSCR_LIST_INT | 8,876,460 | 8.3% | 39.5% | 0.1% |
| POP_TOP | 8,510,660 | 7.9% | 47.4% |  |
| CALL | 8,381,320 | 7.8% | 55.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 7,248,740 | 6.7% | 62.0% |  |
| LOAD_FAST | 7,117,460 | 6.6% | 68.6% |  |
| ENTER_EXECUTOR | 4,520,360 | 4.2% | 72.8% |  |
| POP_JUMP_IF_FALSE | 2,557,460 | 2.4% | 75.2% |  |
| LOAD_GLOBAL_BUILTIN | 2,436,180 | 2.3% | 77.5% | 0.0% |
| LOAD_FAST_LOAD_FAST | 2,333,060 | 2.2% | 79.6% |  |
| RESUME_CHECK | 2,262,440 | 2.1% | 81.7% |  |
| RETURN_VALUE | 2,175,700 | 2.0% | 83.8% |  |
| LOAD_ATTR_MODULE | 1,240,360 | 1.2% | 84.9% | 0.0% |
| CALL_PY_EXACT_ARGS | 1,205,240 | 1.1% | 86.0% | 0.0% |
| STORE_FAST | 1,087,440 | 1.0% | 87.0% |  |
| TO_BOOL_BOOL | 987,100 | 0.9% | 88.0% |  |
| PUSH_NULL | 959,080 | 0.9% | 88.9% |  |
| CALL_ISINSTANCE | 942,240 | 0.9% | 89.7% |  |
| BUILD_TUPLE | 926,660 | 0.9% | 90.6% |  |
| NOP | 916,560 | 0.9% | 91.4% |  |
| BINARY_SUBSCR_DICT | 873,140 | 0.8% | 92.3% |  |
| CALL_TYPE_1 | 866,180 | 0.8% | 93.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 704,200 | 0.7% | 93.7% |  |
| IS_OP | 496,340 | 0.5% | 94.2% |  |
| STORE_FAST_STORE_FAST | 448,500 | 0.4% | 94.6% |  |
| TO_BOOL | 391,540 | 0.4% | 95.0% |  |
| TO_BOOL_LIST | 389,640 | 0.4% | 95.3% | 0.1% |
| IMPORT_NAME | 375,800 | 0.3% | 95.7% |  |
| CALL_KW | 375,200 | 0.3% | 96.0% |  |
| UNPACK_EX | 374,400 | 0.3% | 96.4% |  |
| CALL_PY_WITH_DEFAULTS | 374,220 | 0.3% | 96.7% |  |
| EXTENDED_ARG | 293,420 | 0.3% | 97.0% |  |
| LOAD_ATTR | 231,800 | 0.2% | 97.2% |  |
| INTERPRETER_EXIT | 182,700 | 0.2% | 97.4% |  |
| POP_JUMP_IF_NOT_NONE | 163,020 | 0.2% | 97.5% |  |
| POP_JUMP_IF_NONE | 151,060 | 0.1% | 97.7% |  |
| CALL_BUILTIN_O | 147,620 | 0.1% | 97.8% | 0.1% |
| CONTAINS_OP | 125,560 | 0.1% | 97.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 125,520 | 0.1% | 98.0% |  |
| TO_BOOL_INT | 122,600 | 0.1% | 98.2% | 0.9% |
| POP_JUMP_IF_TRUE | 118,960 | 0.1% | 98.3% |  |
| RETURN_CONST | 115,500 | 0.1% | 98.4% |  |
| BINARY_OP | 107,240 | 0.1% | 98.5% |  |
| COMPARE_OP_STR | 98,640 | 0.1% | 98.6% | 2.9% |
| LOAD_GLOBAL | 94,240 | 0.1% | 98.7% |  |
| CALL_LEN | 93,400 | 0.1% | 98.7% |  |
| BINARY_SUBSCR | 93,100 | 0.1% | 98.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 91,680 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_INT | 83,560 | 0.1% | 99.0% |  |
| JUMP_FORWARD | 77,760 | 0.1% | 99.1% |  |
| GET_ITER | 70,620 | 0.1% | 99.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 60,040 | 0.1% | 99.2% |  |
| BINARY_SUBSCR_STR_INT | 56,240 | 0.1% | 99.2% | 5.1% |
| JUMP_BACKWARD | 54,500 | 0.1% | 99.3% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 53,140 | 0.0% | 99.3% | 0.8% |
| FOR_ITER | 50,500 | 0.0% | 99.4% |  |
| FOR_ITER_RANGE | 46,660 | 0.0% | 99.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 42,140 | 0.0% | 99.5% | 0.1% |
| BUILD_LIST | 41,920 | 0.0% | 99.5% |  |
| BINARY_SUBSCR_GETITEM | 40,080 | 0.0% | 99.5% |  |
| CALL_LIST_APPEND | 37,320 | 0.0% | 99.6% |  |
| COMPARE_OP_INT | 34,920 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_INT | 32,380 | 0.0% | 99.6% |  |
| COPY | 29,620 | 0.0% | 99.7% |  |
| CALL_BUILTIN_CLASS | 28,920 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,360 | 0.0% | 99.7% |  |
| FOR_ITER_LIST | 26,680 | 0.0% | 99.7% | 4.0% |
| LOAD_NAME | 16,280 | 0.0% | 99.8% |  |
| TO_BOOL_NONE | 13,660 | 0.0% | 99.8% | 20.8% |
| STORE_SUBSCR_LIST_INT | 13,520 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 13,020 | 0.0% | 99.8% |  |
| TO_BOOL_STR | 12,640 | 0.0% | 99.8% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 11,440 | 0.0% | 99.8% | 0.7% |
| COMPARE_OP | 10,220 | 0.0% | 99.8% |  |
| STORE_FAST_LOAD_FAST | 9,340 | 0.0% | 99.8% |  |
| LOAD_ATTR_PROPERTY | 9,120 | 0.0% | 99.8% |  |
| UNARY_NOT | 8,720 | 0.0% | 99.9% |  |
| STORE_SUBSCR_DICT | 8,020 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 7,920 | 0.0% | 99.9% |  |
| EXIT_INIT_CHECK | 7,820 | 0.0% | 99.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 7,820 | 0.0% | 99.9% |  |
| BUILD_SLICE | 7,220 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TUPLE | 7,180 | 0.0% | 99.9% |  |
| BUILD_MAP | 6,140 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 5,840 | 0.0% | 99.9% |  |
| POP_EXCEPT | 5,840 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 5,840 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 5,820 | 0.0% | 99.9% |  |
| SWAP | 5,680 | 0.0% | 99.9% |  |
| STORE_NAME | 5,660 | 0.0% | 99.9% |  |
| BINARY_OP_MULTIPLY_INT | 5,380 | 0.0% | 99.9% |  |
| FOR_ITER_TUPLE | 4,980 | 0.0% | 99.9% |  |
| BINARY_SLICE | 4,920 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 4,860 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 4,740 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 4,720 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,520 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,500 | 0.0% | 100.0% | 5.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,440 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 2,900 | 0.0% | 100.0% |  |
| LIST_APPEND | 2,180 | 0.0% | 100.0% |  |
| MAP_ADD | 2,040 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 1,980 | 0.0% | 100.0% | 34.3% |
| UNARY_INVERT | 1,960 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 1,620 | 0.0% | 100.0% |  |
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
| LOAD_GLOBAL_MODULE LOAD_CONST | 8,803,620 | 8.2% | 8.2% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 8,766,540 | 8.2% | 16.4% |
| CALL POP_TOP | 6,966,100 | 6.5% | 22.8% |
| BINARY_SUBSCR_LIST_INT LOAD_ATTR_METHOD_NO_DICT | 6,297,500 | 5.9% | 28.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 6,095,080 | 5.7% | 34.4% |
| LOAD_CONST CALL | 4,702,320 | 4.4% | 38.7% |
| POP_TOP ENTER_EXECUTOR | 4,335,640 | 4.0% | 42.8% |
| POP_TOP LOAD_GLOBAL_MODULE | 3,814,300 | 3.5% | 46.3% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 3,559,940 | 3.3% | 49.6% |
| LOAD_CONST LOAD_CONST | 2,989,960 | 2.8% | 52.4% |
| LOAD_CONST LOAD_GLOBAL_MODULE | 2,079,260 | 1.9% | 54.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,900,260 | 1.8% | 56.1% |
| BINARY_SUBSCR_LIST_INT CALL | 1,857,860 | 1.7% | 57.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,532,520 | 1.4% | 59.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 1,328,100 | 1.2% | 60.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,204,960 | 1.1% | 61.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 970,580 | 0.9% | 62.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 956,720 | 0.9% | 63.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 933,740 | 0.9% | 64.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 892,440 | 0.8% | 65.1% |
| RETURN_VALUE POP_TOP | 881,720 | 0.8% | 66.0% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 873,080 | 0.8% | 66.8% |
| LOAD_FAST CALL | 872,940 | 0.8% | 67.6% |
| CALL RETURN_VALUE | 872,920 | 0.8% | 68.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 867,900 | 0.8% | 69.2% |
| LOAD_FAST CALL_TYPE_1 | 866,120 | 0.8% | 70.0% |
| NOP LOAD_GLOBAL_MODULE | 865,020 | 0.8% | 70.8% |
| CALL_TYPE_1 LOAD_FAST_LOAD_FAST | 864,280 | 0.8% | 71.6% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 863,400 | 0.8% | 72.4% |
| BUILD_TUPLE BINARY_SUBSCR_DICT | 861,460 | 0.8% | 73.2% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 861,360 | 0.8% | 74.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 861,120 | 0.8% | 74.8% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 860,360 | 0.8% | 75.6% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 859,520 | 0.8% | 76.4% |
| ENTER_EXECUTOR CALL | 783,360 | 0.7% | 77.2% |
| PUSH_NULL LOAD_CONST | 756,680 | 0.7% | 77.9% |
| POP_JUMP_IF_FALSE NOP | 749,120 | 0.7% | 78.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 740,960 | 0.7% | 79.2% |
| RESUME_CHECK LOAD_FAST | 738,120 | 0.7% | 79.9% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 660,560 | 0.6% | 80.6% |
| STORE_FAST LOAD_FAST | 625,400 | 0.6% | 81.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 531,540 | 0.5% | 81.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 502,040 | 0.5% | 82.1% |
| LOAD_GLOBAL_MODULE IS_OP | 492,540 | 0.5% | 82.6% |
| IS_OP POP_JUMP_IF_FALSE | 464,640 | 0.4% | 83.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 406,020 | 0.4% | 83.4% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 396,260 | 0.4% | 83.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 393,000 | 0.4% | 84.1% |
| LOAD_FAST TO_BOOL_LIST | 388,200 | 0.4% | 84.5% |
| LOAD_FAST TO_BOOL | 386,680 | 0.4% | 84.8% |
| TO_BOOL POP_JUMP_IF_FALSE | 384,760 | 0.4% | 85.2% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 381,580 | 0.4% | 85.5% |
| POP_JUMP_IF_FALSE LOAD_CONST | 379,880 | 0.4% | 85.9% |
| CALL RESUME_CHECK | 377,900 | 0.4% | 86.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 376,820 | 0.4% | 86.6% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 375,860 | 0.3% | 86.9% |
| LOAD_CONST IMPORT_NAME | 375,800 | 0.3% | 87.3% |
| IMPORT_NAME STORE_FAST | 375,520 | 0.3% | 87.6% |
| LOAD_FAST LOAD_ATTR_MODULE | 375,480 | 0.3% | 88.0% |
| LOAD_CONST CALL_KW | 375,200 | 0.3% | 88.3% |
| LOAD_ATTR_MODULE LOAD_CONST | 375,040 | 0.3% | 88.7% |
| CALL_KW POP_TOP | 374,400 | 0.3% | 89.0% |
| LOAD_FAST UNPACK_EX | 374,400 | 0.3% | 89.4% |
| UNPACK_EX STORE_FAST_STORE_FAST | 374,400 | 0.3% | 89.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 374,220 | 0.3% | 90.1% |
| BINARY_SUBSCR_LIST_INT LOAD_GLOBAL_MODULE | 268,020 | 0.2% | 90.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 236,800 | 0.2% | 90.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 227,960 | 0.2% | 90.8% |
| LOAD_FAST LOAD_CONST | 216,860 | 0.2% | 91.0% |
| LOAD_FAST PUSH_NULL | 205,140 | 0.2% | 91.2% |
| CACHE RESUME_CHECK | 189,100 | 0.2% | 91.3% |
| BINARY_SUBSCR_LIST_INT CALL_PY_WITH_DEFAULTS | 181,100 | 0.2% | 91.5% |
| LOAD_FAST LOAD_ATTR | 177,680 | 0.2% | 91.7% |
| LOAD_ATTR STORE_FAST | 169,800 | 0.2% | 91.8% |
| RETURN_VALUE INTERPRETER_EXIT | 168,460 | 0.2% | 92.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 160,720 | 0.1% | 92.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 159,500 | 0.1% | 92.3% |
| STORE_FAST NOP | 156,120 | 0.1% | 92.4% |
| LOAD_CONST CALL_PY_WITH_DEFAULTS | 147,740 | 0.1% | 92.6% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 147,340 | 0.1% | 92.7% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 142,880 | 0.1% | 92.8% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 140,180 | 0.1% | 93.0% |
| POP_JUMP_IF_NONE LOAD_FAST | 139,100 | 0.1% | 93.1% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 138,960 | 0.1% | 93.2% |
| EXTENDED_ARG ENTER_EXECUTOR | 136,020 | 0.1% | 93.3% |
| RETURN_VALUE RETURN_VALUE | 133,040 | 0.1% | 93.5% |
| PUSH_NULL LOAD_FAST | 127,460 | 0.1% | 93.6% |
| POP_TOP LOAD_FAST | 126,140 | 0.1% | 93.7% |
| CALL CALL | 115,260 | 0.1% | 93.8% |
| LOAD_ATTR_MODULE CALL_PY_EXACT_ARGS | 111,780 | 0.1% | 93.9% |
| POP_TOP EXTENDED_ARG | 111,740 | 0.1% | 94.0% |
| CALL_BUILTIN_O POP_TOP | 110,720 | 0.1% | 94.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 96,620 | 0.1% | 94.2% |
| LOAD_FAST CALL_BUILTIN_O | 91,740 | 0.1% | 94.3% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 88,140 | 0.1% | 94.4% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 85,980 | 0.1% | 94.5% |
| LOAD_CONST BINARY_SUBSCR | 83,800 | 0.1% | 94.5% |
| LOAD_GLOBAL_MODULE BINARY_OP | 83,240 | 0.1% | 94.6% |
| LOAD_CONST COMPARE_OP_STR | 81,660 | 0.1% | 94.7% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 81,020 | 0.1% | 94.8% |


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
| ENTER_EXECUTOR | 300 | 68.2% |
| JUMP_BACKWARD | 100 | 22.7% |
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
| LOAD_CONST | 83,800 | 90.0% |
| BUILD_SLICE | 7,220 | 7.8% |
| LOAD_FAST | 2,000 | 2.1% |
| BINARY_SUBSCR | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 41,080 | 44.1% |
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
| CALL_BUILTIN_CLASS | 20,500 | 29.0% |
| LOAD_FAST | 18,820 | 26.6% |
| LOAD_ATTR_INSTANCE_VALUE | 15,360 | 21.8% |
| BINARY_SUBSCR | 7,040 | 10.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,820 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 26,240 | 37.2% |
| FOR_ITER_RANGE | 22,060 | 31.2% |
| FOR_ITER_LIST | 11,960 | 16.9% |
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
| POP_JUMP_IF_FALSE | 749,120 | 81.7% |
| STORE_FAST | 156,120 | 17.0% |
| RESUME_CHECK | 3,600 | 0.4% |
| STORE_FAST_STORE_FAST | 2,240 | 0.2% |
| NOP | 1,820 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 865,020 | 94.4% |
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
| JUMP_BACKWARD | 160 | 2.7% |
| EXTENDED_ARG | 40 | 0.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 6,966,100 | 81.9% |
| RETURN_VALUE | 881,720 | 10.4% |
| CALL_KW | 374,400 | 4.4% |
| CALL_BUILTIN_O | 110,720 | 1.3% |
| RETURN_CONST | 71,740 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,335,640 | 50.9% |
| LOAD_GLOBAL_MODULE | 3,814,300 | 44.8% |
| LOAD_FAST | 126,140 | 1.5% |
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
| LOAD_ATTR_MODULE | 740,960 | 77.3% |
| LOAD_FAST | 205,140 | 21.4% |
| STORE_FAST_LOAD_FAST | 7,320 | 0.8% |
| LOAD_ATTR | 3,100 | 0.3% |
| LOAD_NAME | 2,080 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 756,680 | 78.9% |
| LOAD_FAST | 127,460 | 13.3% |
| LOAD_GLOBAL_MODULE | 51,600 | 5.4% |
| LOAD_FAST_LOAD_FAST | 11,860 | 1.2% |
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
| CALL | 872,920 | 40.1% |
| BINARY_SUBSCR_DICT | 860,360 | 39.5% |
| LOAD_ATTR_INSTANCE_VALUE | 138,960 | 6.4% |
| RETURN_VALUE | 133,040 | 6.1% |
| BINARY_SUBSCR_LIST_INT | 61,460 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 881,720 | 40.5% |
| LOAD_ATTR_METHOD_NO_DICT | 861,360 | 39.6% |
| INTERPRETER_EXIT | 168,460 | 7.7% |
| RETURN_VALUE | 133,040 | 6.1% |
| STORE_FAST | 43,540 | 2.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,380 | 42.7% |
| LOAD_FAST | 2,300 | 29.0% |
| LOAD_CONST | 1,880 | 23.7% |
| BINARY_OP | 160 | 2.0% |
| STORE_SUBSCR | 120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,280 | 28.8% |
| EXTENDED_ARG | 1,880 | 23.7% |
| LOAD_FAST_LOAD_FAST | 1,600 | 20.2% |
| JUMP_FORWARD | 1,440 | 18.2% |
| ENTER_EXECUTOR | 260 | 3.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 386,680 | 98.8% |
| LOAD_ATTR | 1,740 | 0.4% |
| BINARY_OP | 940 | 0.2% |
| ENTER_EXECUTOR | 880 | 0.2% |
| TO_BOOL | 780 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 384,760 | 98.3% |
| POP_JUMP_IF_TRUE | 5,700 | 1.5% |
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
| LOAD_GLOBAL_MODULE | 83,240 | 77.6% |
| LOAD_FAST_LOAD_FAST | 7,540 | 7.0% |
| LOAD_FAST | 4,540 | 4.2% |
| RETURN_VALUE | 3,000 | 2.8% |
| LOAD_ATTR_INSTANCE_VALUE | 2,820 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 74,840 | 69.8% |
| STORE_FAST | 14,180 | 13.2% |
| LOAD_FAST | 4,880 | 4.6% |
| LOAD_CONST | 2,900 | 2.7% |
| RETURN_VALUE | 2,040 | 1.9% |


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
| LOAD_FAST_LOAD_FAST | 867,900 | 93.7% |
| CALL_BUILTIN_O | 23,880 | 2.6% |
| CALL | 9,400 | 1.0% |
| LOAD_FAST | 7,620 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 5,680 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 861,460 | 93.0% |
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
| LOAD_CONST | 4,702,320 | 56.1% |
| BINARY_SUBSCR_LIST_INT | 1,857,860 | 22.2% |
| LOAD_FAST | 872,940 | 10.4% |
| ENTER_EXECUTOR | 783,360 | 9.3% |
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
| LOAD_GLOBAL_MODULE | 73,280 | 58.4% |
| LOAD_FAST_LOAD_FAST | 43,460 | 34.6% |
| LOAD_CONST | 7,940 | 6.3% |
| LOAD_FAST | 580 | 0.5% |
| LOAD_ATTR_MODULE | 200 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 85,980 | 68.5% |
| EXTENDED_ARG | 35,420 | 28.2% |
| POP_JUMP_IF_TRUE | 2,340 | 1.9% |
| RETURN_VALUE | 1,740 | 1.4% |
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
| FOR_ITER | 40 | 50.0% |
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
| POP_TOP | 4,335,640 | 95.9% |
| EXTENDED_ARG | 136,020 | 3.0% |
| POP_JUMP_IF_TRUE | 27,980 | 0.6% |
| STORE_FAST | 9,500 | 0.2% |
| STORE_SUBSCR_LIST_INT | 5,480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,559,940 | 78.8% |
| CALL | 783,360 | 17.3% |
| LOAD_FAST | 40,300 | 0.9% |
| CALL_PY_WITH_DEFAULTS | 38,160 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 23,560 | 0.5% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 111,740 | 38.1% |
| CONTAINS_OP | 35,420 | 12.1% |
| JUMP_FORWARD | 32,460 | 11.1% |
| JUMP_BACKWARD | 28,540 | 9.7% |
| GET_ITER | 26,240 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 136,020 | 46.4% |
| POP_JUMP_IF_FALSE | 49,360 | 16.8% |
| JUMP_FORWARD | 37,560 | 12.8% |
| FOR_ITER | 34,780 | 11.9% |
| FOR_ITER_LIST | 13,280 | 4.5% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 34,780 | 68.9% |
| GET_ITER | 7,600 | 15.0% |
| JUMP_BACKWARD | 7,220 | 14.3% |
| FOR_ITER | 720 | 1.4% |
| LOAD_FAST | 120 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 27,680 | 54.8% |
| RETURN_CONST | 8,100 | 16.0% |
| STORE_FAST | 4,920 | 9.7% |
| LOAD_FAST | 2,820 | 5.6% |
| LOAD_GLOBAL_MODULE | 2,820 | 5.6% |


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
| LOAD_GLOBAL_MODULE | 492,540 | 99.2% |
| LOAD_GLOBAL_BUILTIN | 1,840 | 0.4% |
| LOAD_FAST | 1,800 | 0.4% |
| LOAD_CONST | 100 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 464,640 | 93.6% |
| POP_JUMP_IF_TRUE | 31,600 | 6.4% |
| COPY | 100 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 34,160 | 62.7% |
| EXTENDED_ARG | 11,980 | 22.0% |
| POP_JUMP_IF_TRUE | 2,100 | 3.9% |
| LIST_APPEND | 1,760 | 3.2% |
| MAP_ADD | 1,360 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 28,540 | 52.4% |
| FOR_ITER_RANGE | 12,720 | 23.3% |
| FOR_ITER | 7,220 | 13.2% |
| FOR_ITER_TUPLE | 2,500 | 4.6% |
| ENTER_EXECUTOR | 1,460 | 2.7% |


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
| CALL_METHOD_DESCRIPTOR_FAST | 1,440 | 66.1% |
| BUILD_TUPLE | 560 | 25.7% |
| CALL_BUILTIN_CLASS | 180 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,760 | 80.7% |
| ENTER_EXECUTOR | 420 | 19.3% |


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
| LOAD_FAST | 177,680 | 76.7% |
| BINARY_SUBSCR | 21,480 | 9.3% |
| BINARY_SUBSCR_LIST_INT | 21,460 | 9.3% |
| LOAD_GLOBAL | 3,780 | 1.6% |
| LOAD_GLOBAL_MODULE | 3,760 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 169,800 | 73.3% |
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
| LOAD_GLOBAL_MODULE | 8,803,620 | 43.1% |
| LOAD_ATTR_METHOD_NO_DICT | 6,095,080 | 29.8% |
| LOAD_CONST | 2,989,960 | 14.6% |
| PUSH_NULL | 756,680 | 3.7% |
| LOAD_GLOBAL_BUILTIN | 396,260 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 8,766,540 | 42.9% |
| CALL | 4,702,320 | 23.0% |
| LOAD_CONST | 2,989,960 | 14.6% |
| LOAD_GLOBAL_MODULE | 2,079,260 | 10.2% |
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
| POP_JUMP_IF_FALSE | 1,328,100 | 18.7% |
| RESUME_CHECK | 738,120 | 10.4% |
| STORE_FAST | 625,400 | 8.8% |
| LOAD_ATTR_METHOD_NO_DICT | 531,540 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,532,520 | 21.5% |
| CALL | 872,940 | 12.3% |
| CALL_TYPE_1 | 866,120 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 660,560 | 9.3% |
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
| LOAD_GLOBAL_MODULE | 892,440 | 38.3% |
| CALL_TYPE_1 | 864,280 | 37.0% |
| LOAD_ATTR_METHOD_NO_DICT | 376,820 | 16.2% |
| RESUME_CHECK | 32,500 | 1.4% |
| STORE_FAST_STORE_FAST | 31,640 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 873,080 | 37.4% |
| BUILD_TUPLE | 867,900 | 37.2% |
| LOAD_FAST | 393,000 | 16.8% |
| STORE_ATTR_INSTANCE_VALUE | 57,180 | 2.5% |
| CONTAINS_OP | 43,460 | 1.9% |


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
| LOAD_NAME | 4,600 | 28.3% |
| STORE_NAME | 2,860 | 17.6% |
| LOAD_FAST | 1,540 | 9.5% |
| STORE_FAST_STORE_FAST | 1,540 | 9.5% |
| STORE_SUBSCR_DICT | 1,440 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 4,600 | 28.3% |
| LOAD_CONST | 4,220 | 25.9% |
| PUSH_NULL | 2,080 | 12.8% |
| CALL_ISINSTANCE | 1,500 | 9.2% |
| CALL_METHOD_DESCRIPTOR_O | 1,240 | 7.6% |


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
| JUMP_BACKWARD | 1,360 | 66.7% |
| LOAD_CONST | 640 | 31.4% |
| BUILD_MAP | 20 | 1.0% |
| DICT_UPDATE | 20 | 1.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 956,720 | 37.4% |
| IS_OP | 464,640 | 18.2% |
| TO_BOOL | 384,760 | 15.0% |
| TO_BOOL_LIST | 381,580 | 14.9% |
| COMPARE_OP_STR | 88,140 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,328,100 | 51.9% |
| NOP | 749,120 | 29.3% |
| LOAD_CONST | 379,880 | 14.9% |
| LOAD_GLOBAL_MODULE | 36,760 | 1.4% |
| LOAD_FAST_LOAD_FAST | 14,160 | 0.6% |


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
| LOAD_FAST | 160,720 | 98.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,420 | 0.9% |
| CALL_BUILTIN_FAST | 440 | 0.3% |
| LOAD_FAST_CHECK | 280 | 0.2% |
| LOAD_GLOBAL_MODULE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,180 | 86.0% |
| BUILD_LIST | 8,000 | 4.9% |
| LOAD_GLOBAL_MODULE | 5,540 | 3.4% |
| LOAD_GLOBAL_BUILTIN | 4,160 | 2.6% |
| LOAD_FAST_LOAD_FAST | 1,880 | 1.2% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 36,680 | 30.8% |
| IS_OP | 31,600 | 26.6% |
| TO_BOOL_BOOL | 26,920 | 22.6% |
| TO_BOOL_STR | 9,840 | 8.3% |
| TO_BOOL | 5,700 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,660 | 42.6% |
| ENTER_EXECUTOR | 27,980 | 23.5% |
| CALL_LEN | 9,620 | 8.1% |
| LOAD_FAST_LOAD_FAST | 8,180 | 6.9% |
| LOAD_GLOBAL_MODULE | 5,500 | 4.6% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 32,180 | 27.9% |
| CALL_LIST_APPEND | 29,680 | 25.7% |
| POP_TOP | 13,920 | 12.1% |
| POP_JUMP_IF_FALSE | 13,240 | 11.5% |
| FOR_ITER | 8,100 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 71,740 | 62.1% |
| TO_BOOL_BOOL | 16,440 | 14.2% |
| INTERPRETER_EXIT | 14,020 | 12.1% |
| EXIT_INIT_CHECK | 7,820 | 6.8% |
| STORE_FAST | 5,340 | 4.6% |


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
| IMPORT_NAME | 375,520 | 34.5% |
| LOAD_ATTR | 169,800 | 15.6% |
| LOAD_CONST | 55,820 | 5.1% |
| BINARY_OP_ADD_INT | 55,600 | 5.1% |
| LOAD_GLOBAL_MODULE | 48,640 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 625,400 | 57.5% |
| NOP | 156,120 | 14.4% |
| LOAD_GLOBAL_MODULE | 96,620 | 8.9% |
| LOAD_CONST | 56,680 | 5.2% |
| STORE_FAST | 43,500 | 4.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 7,320 | 78.4% |
| FOR_ITER_TUPLE | 2,000 | 21.4% |
| FOR_ITER | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 7,320 | 78.4% |
| TO_BOOL_STR | 1,440 | 15.4% |
| LOAD_FAST | 560 | 6.0% |
| FORMAT_SIMPLE | 20 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_EX | 374,400 | 83.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 60,780 | 13.6% |
| COPY | 9,380 | 2.1% |
| UNPACK_SEQUENCE_TUPLE | 3,520 | 0.8% |
| STORE_FAST_STORE_FAST | 360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 406,020 | 90.5% |
| LOAD_FAST_LOAD_FAST | 31,640 | 7.1% |
| STORE_FAST | 3,160 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 3,080 | 0.7% |
| NOP | 2,240 | 0.5% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,780 | 31.4% |
| FOR_ITER_TUPLE | 1,280 | 22.6% |
| FOR_ITER | 1,040 | 18.4% |
| MAKE_FUNCTION | 460 | 8.1% |
| RETURN_VALUE | 300 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 2,860 | 50.5% |
| LOAD_CONST | 2,460 | 43.5% |
| RETURN_CONST | 100 | 1.8% |
| POP_TOP | 80 | 1.4% |
| LOAD_BUILD_CLASS | 40 | 0.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 1,340 | 23.6% |
| BUILD_LIST | 1,320 | 23.2% |
| LOAD_FAST | 1,240 | 21.8% |
| FOR_ITER_TUPLE | 880 | 15.5% |
| ENTER_EXECUTOR | 440 | 7.7% |

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
| LOAD_CONST | 76,340 | 91.4% |
| LOAD_FAST_LOAD_FAST | 5,080 | 6.1% |
| BINARY_OP_MULTIPLY_INT | 2,140 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 55,600 | 66.5% |
| LOAD_FAST | 22,680 | 27.1% |
| CALL_PY_EXACT_ARGS | 2,060 | 2.5% |
| CALL_BUILTIN_O | 1,600 | 1.9% |
| LOAD_FAST_LOAD_FAST | 740 | 0.9% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,040 | 69.4% |
| LOAD_FAST_LOAD_FAST | 1,080 | 18.6% |
| CALL_METHOD_DESCRIPTOR_O | 360 | 6.2% |
| BINARY_OP | 220 | 3.8% |
| BINARY_SUBSCR_LIST_INT | 120 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 1,840 | 31.6% |
| BUILD_TUPLE | 960 | 16.5% |
| LOAD_NAME | 960 | 16.5% |
| CALL | 540 | 9.3% |
| LOAD_FAST | 540 | 9.3% |


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
| LOAD_CONST | 11,640 | 35.9% |
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
| BUILD_TUPLE | 861,460 | 98.7% |
| LOAD_FAST | 9,220 | 1.1% |
| LOAD_FAST_LOAD_FAST | 2,280 | 0.3% |
| LOAD_CONST | 120 | 0.0% |
| BINARY_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 860,360 | 98.5% |
| CALL_BUILTIN_O | 4,940 | 0.6% |
| LOAD_CONST | 3,080 | 0.4% |
| PUSH_EXC_INFO | 2,980 | 0.3% |
| STORE_FAST | 1,360 | 0.2% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 22,260 | 55.5% |
| LOAD_CONST | 10,820 | 27.0% |
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
| LOAD_CONST | 8,766,540 | 98.8% |
| LOAD_FAST | 63,440 | 0.7% |
| BINARY_SUBSCR | 41,080 | 0.5% |
| LOAD_FAST_LOAD_FAST | 2,800 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 2,460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,297,500 | 71.0% |
| CALL | 1,857,860 | 20.9% |
| LOAD_GLOBAL_MODULE | 268,020 | 3.0% |
| CALL_PY_WITH_DEFAULTS | 181,100 | 2.0% |
| LOAD_CONST | 147,340 | 1.7% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 33,580 | 59.7% |
| LOAD_FAST | 20,960 | 37.3% |
| ENTER_EXECUTOR | 1,640 | 2.9% |
| BINARY_SUBSCR_STR_INT | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 31,640 | 56.3% |
| STORE_FAST | 16,000 | 28.4% |
| BINARY_OP_INPLACE_ADD_UNICODE | 3,780 | 6.7% |
| PUSH_EXC_INFO | 2,820 | 5.0% |
| CALL_BUILTIN_O | 1,940 | 3.4% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,340 | 99.9% |
| BINARY_SUBSCR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,460 | 33.4% |
| CALL_BUILTIN_O | 6,260 | 22.1% |
| GET_ITER | 2,460 | 8.7% |
| LOAD_FAST | 2,220 | 7.8% |
| BINARY_OP_MULTIPLY_INT | 2,140 | 7.5% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,980 | 38.1% |
| LOAD_GLOBAL_MODULE | 2,820 | 36.1% |
| BINARY_SUBSCR | 1,880 | 24.0% |
| LOAD_FAST_LOAD_FAST | 140 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,820 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 25,260 | 47.5% |
| LOAD_CONST | 15,180 | 28.6% |
| PUSH_NULL | 8,940 | 16.8% |
| LOAD_FAST | 3,720 | 7.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 52,840 | 99.4% |
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
| LOAD_FAST | 91,740 | 62.1% |
| LOAD_GLOBAL_MODULE | 16,240 | 11.0% |
| LOAD_CONST | 10,480 | 7.1% |
| RETURN_VALUE | 7,040 | 4.8% |
| BINARY_SUBSCR_TUPLE_INT | 6,260 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 110,720 | 75.0% |
| BUILD_TUPLE | 23,880 | 16.2% |
| TO_BOOL_BOOL | 8,880 | 6.0% |
| STORE_FAST | 4,040 | 2.7% |
| TO_BOOL_INT | 80 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 859,520 | 91.2% |
| LOAD_GLOBAL_BUILTIN | 72,040 | 7.6% |
| BUILD_TUPLE | 5,700 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,720 | 0.2% |
| LOAD_ATTR_SLOT | 1,720 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 933,740 | 99.1% |
| RETURN_VALUE | 5,640 | 0.6% |
| LOAD_FAST | 2,820 | 0.3% |
| TO_BOOL | 40 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,380 | 55.0% |
| LOAD_ATTR_INSTANCE_VALUE | 26,640 | 28.5% |
| POP_JUMP_IF_TRUE | 9,620 | 10.3% |
| LOAD_GLOBAL_MODULE | 5,640 | 6.0% |
| LOAD_CONST | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 26,400 | 28.3% |
| LOAD_CONST | 13,440 | 14.4% |
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
| ENTER_EXECUTOR | 1,600 | 4.3% |
| EXTENDED_ARG | 1,240 | 3.3% |
| LOAD_FAST_LOAD_FAST | 180 | 0.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000 | 46.1% |
| LOAD_CONST | 2,820 | 21.7% |
| LOAD_GLOBAL_MODULE | 1,600 | 12.3% |
| LOAD_FAST_LOAD_FAST | 1,260 | 9.7% |
| LOAD_ATTR_METHOD_NO_DICT | 1,140 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,320 | 86.9% |
| LIST_APPEND | 1,440 | 11.1% |
| POP_TOP | 120 | 0.9% |
| LOAD_FAST | 80 | 0.6% |
| SWAP | 60 | 0.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 33,260 | 55.4% |
| BINARY_SUBSCR_LIST_INT | 25,880 | 43.1% |
| CALL | 700 | 1.2% |
| LOAD_GLOBAL_MODULE | 180 | 0.3% |
| LOAD_ATTR_METHOD_NO_DICT | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 59,760 | 99.5% |
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
| LOAD_FAST | 4,940 | 43.2% |
| RETURN_VALUE | 1,500 | 13.1% |
| CALL_METHOD_DESCRIPTOR_O | 1,400 | 12.2% |
| LOAD_NAME | 1,240 | 10.8% |
| LOAD_GLOBAL_MODULE | 920 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,560 | 66.1% |
| RETURN_VALUE | 1,600 | 14.0% |
| CALL_METHOD_DESCRIPTOR_O | 1,400 | 12.2% |
| BINARY_OP_ADD_UNICODE | 360 | 3.1% |
| LOAD_CONST | 220 | 1.9% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 873,080 | 72.4% |
| LOAD_FAST | 159,500 | 13.2% |
| LOAD_ATTR_MODULE | 111,780 | 9.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 35,340 | 2.9% |
| LOAD_CONST | 4,920 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,204,960 | 100.0% |
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
| BINARY_SUBSCR_LIST_INT | 181,100 | 48.4% |
| LOAD_CONST | 147,740 | 39.5% |
| ENTER_EXECUTOR | 38,160 | 10.2% |
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
| LOAD_FAST | 866,120 | 100.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 864,280 | 99.8% |
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
| LOAD_CONST | 21,420 | 61.3% |
| LOAD_GLOBAL_MODULE | 7,240 | 20.7% |
| CALL_LEN | 2,620 | 7.5% |
| BINARY_SUBSCR_LIST_INT | 1,400 | 4.0% |
| COPY | 1,060 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,460 | 98.7% |
| POP_JUMP_IF_TRUE | 340 | 1.0% |
| RETURN_VALUE | 60 | 0.2% |
| STORE_FAST | 60 | 0.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 81,660 | 82.8% |
| LOAD_ATTR_INSTANCE_VALUE | 16,720 | 17.0% |
| COMPARE_OP | 160 | 0.2% |
| LOAD_FAST | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 88,140 | 89.4% |
| EXTENDED_ARG | 10,440 | 10.6% |
| COMPARE_OP | 60 | 0.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 13,280 | 49.8% |
| GET_ITER | 11,960 | 44.8% |
| JUMP_BACKWARD | 1,400 | 5.2% |
| FOR_ITER | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 18,540 | 69.5% |
| STORE_FAST | 6,260 | 23.5% |
| LOAD_FAST_LOAD_FAST | 1,120 | 4.2% |
| RETURN_CONST | 480 | 1.8% |
| LOAD_FAST | 200 | 0.7% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 22,060 | 47.3% |
| JUMP_BACKWARD | 12,720 | 27.3% |
| EXTENDED_ARG | 10,440 | 22.4% |
| FOR_ITER | 1,260 | 2.7% |
| SWAP | 180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 45,600 | 97.7% |
| RETURN_CONST | 420 | 0.9% |
| LOAD_FAST | 400 | 0.9% |
| LOAD_GLOBAL | 200 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 20 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,500 | 50.2% |
| GET_ITER | 1,280 | 25.7% |
| SWAP | 1,120 | 22.5% |
| FOR_ITER | 60 | 1.2% |
| LOAD_FAST | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 2,000 | 40.2% |
| STORE_NAME | 1,280 | 25.7% |
| SWAP | 880 | 17.7% |
| STORE_FAST | 400 | 8.0% |
| JUMP_BACKWARD | 220 | 4.4% |


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
| LOAD_FAST | 660,560 | 93.8% |
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
| BINARY_SUBSCR_LIST_INT | 6,297,500 | 86.9% |
| RETURN_VALUE | 861,360 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 31,440 | 0.4% |
| LOAD_FAST | 22,380 | 0.3% |
| LOAD_ATTR | 21,720 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,095,080 | 84.1% |
| LOAD_FAST | 531,540 | 7.3% |
| LOAD_FAST_LOAD_FAST | 376,820 | 5.2% |
| LOAD_GLOBAL_MODULE | 236,800 | 3.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,500 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,780 | 92.0% |
| BINARY_SUBSCR | 1,600 | 3.8% |
| BINARY_SUBSCR_TUPLE_INT | 1,360 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 320 | 0.8% |
| LOAD_GLOBAL_MODULE | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 35,340 | 83.9% |
| LOAD_FAST | 3,700 | 8.8% |
| LOAD_CONST | 2,040 | 4.8% |
| LOAD_GLOBAL_MODULE | 940 | 2.2% |
| LOAD_FAST_LOAD_FAST | 120 | 0.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 861,120 | 69.4% |
| LOAD_FAST | 375,480 | 30.3% |
| LOAD_ATTR | 3,760 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 740,960 | 59.7% |
| LOAD_CONST | 375,040 | 30.2% |
| CALL_PY_EXACT_ARGS | 111,780 | 9.0% |
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
| RESUME_CHECK | 970,580 | 39.8% |
| LOAD_GLOBAL_MODULE | 863,400 | 35.4% |
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
| POP_TOP | 3,814,300 | 29.0% |
| ENTER_EXECUTOR | 3,559,940 | 27.1% |
| LOAD_CONST | 2,079,260 | 15.8% |
| LOAD_FAST | 1,532,520 | 11.7% |
| NOP | 865,020 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,803,620 | 67.0% |
| LOAD_FAST_LOAD_FAST | 892,440 | 6.8% |
| LOAD_GLOBAL_BUILTIN | 863,400 | 6.6% |
| LOAD_ATTR_MODULE | 861,120 | 6.6% |
| CALL_ISINSTANCE | 859,520 | 6.5% |


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
| CALL_PY_EXACT_ARGS | 1,204,960 | 53.3% |
| CALL | 377,900 | 16.7% |
| CALL_PY_WITH_DEFAULTS | 374,220 | 16.5% |
| CACHE | 189,100 | 8.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 52,840 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 970,580 | 42.9% |
| LOAD_FAST | 738,120 | 32.6% |
| LOAD_GLOBAL_MODULE | 502,040 | 22.2% |
| LOAD_FAST_LOAD_FAST | 32,500 | 1.4% |
| BUILD_LIST | 9,720 | 0.4% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 65,180 | 51.9% |
| LOAD_FAST_LOAD_FAST | 57,180 | 45.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,820 | 2.2% |
| STORE_ATTR | 180 | 0.1% |
| SWAP | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 32,180 | 25.6% |
| LOAD_FAST_LOAD_FAST | 30,380 | 24.2% |
| LOAD_FAST | 29,720 | 23.7% |
| LOAD_CONST | 21,480 | 17.1% |
| BUILD_MAP | 5,640 | 4.5% |


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
| LOAD_FAST | 5,940 | 74.1% |
| BINARY_OP_ADD_UNICODE | 1,840 | 22.9% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 2.0% |
| STORE_SUBSCR | 80 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,940 | 36.7% |
| LOAD_GLOBAL_BUILTIN | 2,820 | 35.2% |
| LOAD_NAME | 1,440 | 18.0% |
| JUMP_BACKWARD | 580 | 7.2% |
| LOAD_GLOBAL_MODULE | 160 | 2.0% |


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
| ENTER_EXECUTOR | 5,480 | 40.5% |
| RETURN_CONST | 4,360 | 32.2% |
| EXTENDED_ARG | 3,480 | 25.7% |
| LOAD_FAST | 140 | 1.0% |
| JUMP_BACKWARD | 60 | 0.4% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 933,740 | 94.6% |
| RETURN_CONST | 16,440 | 1.7% |
| LOAD_FAST | 9,100 | 0.9% |
| CALL_BUILTIN_O | 8,880 | 0.9% |
| RETURN_VALUE | 7,680 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 956,720 | 96.9% |
| POP_JUMP_IF_TRUE | 26,920 | 2.7% |
| EXTENDED_ARG | 3,460 | 0.4% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 74,840 | 61.0% |
| LOAD_FAST | 43,440 | 35.4% |
| COPY | 4,080 | 3.3% |
| TO_BOOL | 80 | 0.1% |
| CALL_BUILTIN_O | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 81,020 | 66.1% |
| POP_JUMP_IF_TRUE | 36,680 | 29.9% |
| UNARY_NOT | 4,880 | 4.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,200 | 99.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,420 | 0.4% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 381,580 | 97.9% |
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
| COPY | 9,820 | 77.7% |
| STORE_FAST_LOAD_FAST | 1,440 | 11.4% |
| LOAD_FAST | 1,360 | 10.8% |
| TO_BOOL | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 9,840 | 77.8% |
| POP_JUMP_IF_FALSE | 2,800 | 22.2% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,860 | 53.8% |
| RETURN_VALUE | 3,040 | 42.3% |
| BINARY_SUBSCR_TUPLE_INT | 140 | 1.9% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 1.7% |
| BUILD_TUPLE | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,640 | 50.7% |
| STORE_FAST_STORE_FAST | 3,520 | 49.0% |
| STORE_DEREF | 20 | 0.3% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 43,520 | 47.5% |
| FOR_ITER | 27,680 | 30.2% |
| FOR_ITER_LIST | 18,540 | 20.2% |
| BINARY_SUBSCR_LIST_INT | 1,340 | 1.5% |
| CALL_BUILTIN_FAST | 340 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60,780 | 66.3% |
| STORE_FAST | 30,900 | 33.7% |


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
|     deferred | 105,760 | 44.2% |
|          hit | 132,060 | 55.2% |

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
|     deferred | 51,700 | 0.5% |
|          hit | 9,864,280 | 99.0% |
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
|     deferred | 8,261,600 | 67.2% |
|          hit | 3,903,820 | 31.8% |
|         miss | 1,740 | 0.0% |

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
|     deferred | 9,760 | 6.8% |
|          hit | 130,820 | 90.9% |
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
|     deferred | 48,400 | 37.6% |
|          hit | 77,260 | 60.0% |
|         miss | 1,060 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,360 | 64.8% |
| Failure | 740 | 35.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| seq iter | 220 | 29.7% |
| itertools | 180 | 24.3% |
| set | 120 | 16.2% |
| dict items | 120 | 16.2% |
| dict keys | 40 | 5.4% |
| enumerate | 20 | 2.7% |
| map | 20 | 2.7% |
| ascii string | 20 | 2.7% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 205,440 | 2.2% |
|          hit | 9,252,600 | 97.6% |
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
|          hit | 15,548,300 | 99.2% |
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
|     deferred | 660 | 0.5% |
|          hit | 125,660 | 99.3% |

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
|     deferred | 7,720 | 26.2% |
|          hit | 21,540 | 73.1% |

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
|     deferred | 390,340 | 20.4% |
|          hit | 1,521,440 | 79.4% |
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
|          hit | 98,860 | 99.9% |

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
| Basic | 52,148,880 | 48.5% |
| Not specialized | 12,369,500 | 11.5% |
| Specialized hits | 42,881,520 | 39.9% |
| Specialized misses | 45,440 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,261,600 | 90.5% |
| TO_BOOL | 390,340 | 4.3% |
| LOAD_ATTR | 205,440 | 2.3% |
| BINARY_OP | 105,760 | 1.2% |
| BINARY_SUBSCR | 51,700 | 0.6% |
| FOR_ITER | 48,400 | 0.5% |
| LOAD_GLOBAL | 46,860 | 0.5% |
| COMPARE_OP | 9,760 | 0.1% |
| STORE_SUBSCR | 7,720 | 0.1% |
| STORE_ATTR | 660 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 25,000 | 55.0% |
| BINARY_SUBSCR_LIST_INT | 7,120 | 15.7% |
| BINARY_SUBSCR_STR_INT | 2,880 | 6.3% |
| COMPARE_OP_STR | 2,860 | 6.3% |
| TO_BOOL_NONE | 2,840 | 6.2% |
| FOR_ITER_LIST | 1,060 | 2.3% |
| TO_BOOL_INT | 1,060 | 2.3% |
| CALL_BUILTIN_FAST | 680 | 1.5% |
| LOAD_GLOBAL_BUILTIN | 440 | 1.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 420 | 0.9% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 189,680 | 8.4% |
| Calls to Python functions inlined | 2,068,900 | 91.6% |
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
| Frames pushed | 1,781,020 | 78.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 5,029,160 | 16.5% |
| Frees to freelist | 5,032,180 |  |
| Allocations | 25,368,120 | 83.5% |
| Allocations to 512 bytes | 25,185,260 | 82.9% |
| Allocations to 4 kbytes | 159,420 | 0.5% |
| Allocations over 4 kbytes | 23,440 | 0.1% |
| Frees | 35,384,438 |  |
| New values | 9,480 |  |
| Interpreter increfs | 56,486,440 | 64.0% |
| Interpreter decrefs | 65,119,620 | 61.4% |
| Increfs | 31,760,668 | 36.0% |
| Decrefs | 41,017,471 | 38.6% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 627,141 |  |
| Method cache misses | 2,799 |  |
| Method cache collisions | 2,971 |  |
| Method cache dunder hits | 3,255,806 |  |
| Method cache dunder misses | 594 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 1,920 | 167,600 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 1,560 |  |
| Traces created | 1,460 | 93.6% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 40 | 2.6% |
| Trace too short | 100 | 6.4% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 4,520,360 |  |
| Uops executed | 52,163,380 | 11.54 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 1.4% |
| <= 32 | 600 | 41.1% |
| <= 64 | 700 | 47.9% |
| <= 128 | 140 | 9.6% |


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
| <= 16 | 20 | 1.4% |
| <= 32 | 1,240 | 84.9% |
| <= 64 | 80 | 5.5% |
| <= 128 | 120 | 8.2% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 3,720 | 0.1% |
| <= 4 | 0 | 0.0% |
| <= 8 | 3,603,780 | 79.7% |
| <= 16 | 30,660 | 0.7% |
| <= 32 | 807,860 | 17.9% |
| <= 64 | 32,680 | 0.7% |
| <= 128 | 39,980 | 0.9% |
| <= 256 | 880 | 0.0% |
| <= 512 | 560 | 0.0% |
| <= 1,024 | 200 | 0.0% |
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
| _SET_IP | 13,288,360 | 25.5% | 25.5% |  |
| _GUARD_GLOBALS_VERSION | 5,034,600 | 9.7% | 35.1% | 70.7% |
| _POP_JUMP_IF_TRUE | 4,679,580 | 9.0% | 44.1% |  |
| STORE_FAST | 4,631,420 | 8.9% | 53.0% |  |
| _ITER_CHECK_RANGE | 4,452,120 | 8.5% | 61.5% |  |
| _IS_ITER_EXHAUSTED_RANGE | 4,452,120 | 8.5% | 70.0% |  |
| _ITER_NEXT_RANGE | 4,424,280 | 8.5% | 78.5% |  |
| LOAD_CONST | 2,703,540 | 5.2% | 83.7% |  |
| _LOAD_GLOBAL_MODULE | 1,450,520 | 2.8% | 86.5% |  |
| BINARY_SUBSCR_LIST_INT | 1,157,920 | 2.2% | 88.7% |  |
| _EXIT_TRACE | 954,000 | 1.8% | 90.5% |  |
| _GUARD_TYPE_VERSION | 891,820 | 1.7% | 92.2% |  |
| LOAD_FAST | 823,980 | 1.6% | 93.8% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 717,540 | 1.4% | 95.2% |  |
| PUSH_NULL | 185,280 | 0.4% | 95.6% |  |
| _CHECK_ATTR_MODULE | 154,740 | 0.3% | 95.9% |  |
| _LOAD_ATTR_MODULE | 154,740 | 0.3% | 96.2% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 104,460 | 0.2% | 96.4% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 104,460 | 0.2% | 96.6% |  |
| POP_TOP | 99,720 | 0.2% | 96.7% |  |
| _CHECK_PEP_523 | 84,260 | 0.2% | 96.9% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 84,260 | 0.2% | 97.1% |  |
| _CHECK_STACK_SPACE | 84,260 | 0.2% | 97.2% |  |
| _INIT_CALL_PY_EXACT_ARGS | 84,260 | 0.2% | 97.4% |  |
| _PUSH_FRAME | 84,260 | 0.2% | 97.6% |  |
| _SAVE_RETURN_OFFSET | 84,260 | 0.2% | 97.7% |  |
| RESUME_CHECK | 79,460 | 0.2% | 97.9% |  |
| IS_OP | 72,380 | 0.1% | 98.0% |  |
| CONTAINS_OP | 65,960 | 0.1% | 98.1% |  |
| _ITER_CHECK_LIST | 60,940 | 0.1% | 98.2% | 6.1% |
| _POP_JUMP_IF_FALSE | 60,440 | 0.1% | 98.4% |  |
| _IS_ITER_EXHAUSTED_LIST | 57,220 | 0.1% | 98.5% |  |
| _POP_FRAME | 52,120 | 0.1% | 98.6% |  |
| _GUARD_BOTH_INT | 46,200 | 0.1% | 98.7% |  |
| _GUARD_DORV_VALUES | 42,440 | 0.1% | 98.7% |  |
| _STORE_ATTR_INSTANCE_VALUE | 42,440 | 0.1% | 98.8% |  |
| _ITER_NEXT_LIST | 39,680 | 0.1% | 98.9% |  |
| _BINARY_OP_ADD_INT | 39,420 | 0.1% | 99.0% |  |
| _IS_NONE | 32,500 | 0.1% | 99.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 31,340 | 0.1% | 99.1% |  |
| _JUMP_TO_TOP | 29,820 | 0.1% | 99.2% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 27,380 | 0.1% | 99.2% |  |
| _GUARD_KEYS_VERSION | 27,380 | 0.1% | 99.3% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 27,380 | 0.1% | 99.3% |  |
| BINARY_SUBSCR_STR_INT | 25,140 | 0.0% | 99.4% | 6.5% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 24,720 | 0.0% | 99.4% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 24,720 | 0.0% | 99.5% |  |
| _GUARD_BUILTINS_VERSION | 24,440 | 0.0% | 99.5% | 0.2% |
| _LOAD_GLOBAL_BUILTINS | 24,380 | 0.0% | 99.6% |  |
| COMPARE_OP_STR | 24,120 | 0.0% | 99.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 21,800 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 20,720 | 0.0% | 99.7% |  |
| TO_BOOL_BOOL | 18,300 | 0.0% | 99.7% |  |
| _STORE_SUBSCR | 14,580 | 0.0% | 99.7% |  |
| _BINARY_OP | 14,520 | 0.0% | 99.8% |  |
| CALL_ISINSTANCE | 14,500 | 0.0% | 99.8% |  |
| BINARY_SLICE | 12,100 | 0.0% | 99.8% |  |
| CALL_BUILTIN_O | 12,040 | 0.0% | 99.8% |  |
| BUILD_TUPLE | 10,040 | 0.0% | 99.9% |  |
| _LOAD_ATTR | 9,780 | 0.0% | 99.9% |  |
| CALL_TYPE_1 | 9,620 | 0.0% | 99.9% |  |
| _BINARY_OP_SUBTRACT_INT | 6,780 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 6,440 | 0.0% | 99.9% |  |
| COMPARE_OP_INT | 5,140 | 0.0% | 99.9% |  |
| TO_BOOL_NONE | 4,420 | 0.0% | 99.9% | 29.4% |
| STORE_SUBSCR_LIST_INT | 4,420 | 0.0% | 100.0% |  |
| CALL_LEN | 4,280 | 0.0% | 100.0% |  |
| _TO_BOOL | 2,580 | 0.0% | 100.0% |  |
| _ITER_CHECK_TUPLE | 2,320 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 2,320 | 0.0% | 100.0% |  |
| COPY | 2,240 | 0.0% | 100.0% |  |
| UNARY_NOT | 2,160 | 0.0% | 100.0% |  |
| LIST_APPEND | 2,060 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 1,900 | 0.0% | 100.0% |  |
| LOAD_NAME | 1,360 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 1,180 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 740 | 0.0% | 100.0% |  |
| STORE_NAME | 680 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 580 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 280 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 200 | 0.0% | 100.0% |  |
| BUILD_STRING | 180 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 160 | 0.0% | 100.0% |  |
| _STORE_ATTR | 100 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 80 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 1,220 |
| FOR_ITER | 100 |
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
Stats gathered on: 2023-11-08
