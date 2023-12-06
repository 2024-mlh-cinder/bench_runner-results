
# Pystats results

- benchmark: docutils
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,451,590,440 | 19.9% | 19.9% |  |
| STORE_FAST | 333,623,200 | 4.6% | 24.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 327,852,460 | 4.5% | 29.0% | 30.7% |
| RESUME_CHECK | 312,211,200 | 4.3% | 33.3% | 0.0% |
| LOAD_CONST | 266,648,100 | 3.7% | 36.9% |  |
| LOAD_FAST_LOAD_FAST | 252,209,940 | 3.5% | 40.4% |  |
| POP_JUMP_IF_FALSE | 227,896,380 | 3.1% | 43.5% |  |
| LOAD_GLOBAL_BUILTIN | 206,197,080 | 2.8% | 46.3% | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 202,307,880 | 2.8% | 49.1% | 42.1% |
| CALL_PY_EXACT_ARGS | 189,657,560 | 2.6% | 51.7% | 4.8% |
| POP_TOP | 172,578,280 | 2.4% | 54.1% |  |
| RETURN_CONST | 162,127,800 | 2.2% | 56.3% |  |
| TO_BOOL_BOOL | 152,672,680 | 2.1% | 58.4% | 0.0% |
| LOAD_ATTR | 148,241,620 | 2.0% | 60.4% |  |
| RETURN_VALUE | 145,437,940 | 2.0% | 62.4% |  |
| ENTER_EXECUTOR | 142,193,660 | 2.0% | 64.4% |  |
| POP_JUMP_IF_TRUE | 128,880,840 | 1.8% | 66.2% |  |
| GET_ITER | 122,848,400 | 1.7% | 67.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 122,291,780 | 1.7% | 69.5% | 0.1% |
| NOP | 116,719,520 | 1.6% | 71.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 93,039,720 | 1.3% | 72.4% | 58.0% |
| LOAD_GLOBAL_MODULE | 91,994,200 | 1.3% | 73.7% | 0.0% |
| LOAD_ATTR_WITH_HINT | 85,900,920 | 1.2% | 74.8% | 1.2% |
| CALL_ISINSTANCE | 80,236,020 | 1.1% | 75.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 66,479,320 | 0.9% | 76.9% | 70.9% |
| TO_BOOL_NONE | 64,920,180 | 0.9% | 77.7% | 9.4% |
| CALL_BUILTIN_FAST | 64,392,960 | 0.9% | 78.6% |  |
| CALL | 61,696,920 | 0.8% | 79.5% |  |
| CONTAINS_OP | 59,940,340 | 0.8% | 80.3% |  |
| PUSH_NULL | 58,147,260 | 0.8% | 81.1% |  |
| FOR_ITER_LIST | 56,975,360 | 0.8% | 81.9% | 23.1% |
| BUILD_LIST | 49,221,000 | 0.7% | 82.6% |  |
| POP_JUMP_IF_NOT_NONE | 48,627,080 | 0.7% | 83.2% |  |
| FOR_ITER | 45,340,760 | 0.6% | 83.8% |  |
| LOAD_ATTR_SLOT | 44,238,600 | 0.6% | 84.4% | 79.8% |
| JUMP_BACKWARD | 41,966,900 | 0.6% | 85.0% |  |
| FOR_ITER_GEN | 41,703,600 | 0.6% | 85.6% |  |
| STORE_SUBSCR_DICT | 41,604,280 | 0.6% | 86.2% |  |
| CALL_LIST_APPEND | 41,464,300 | 0.6% | 86.7% | 0.1% |
| BINARY_SUBSCR_DICT | 40,942,640 | 0.6% | 87.3% |  |
| INTERPRETER_EXIT | 39,027,960 | 0.5% | 87.8% |  |
| STORE_FAST_STORE_FAST | 37,296,000 | 0.5% | 88.3% |  |
| RETURN_GENERATOR | 37,113,120 | 0.5% | 88.9% |  |
| END_FOR | 36,887,100 | 0.5% | 89.4% |  |
| BUILD_TUPLE | 35,189,820 | 0.5% | 89.8% |  |
| FORMAT_SIMPLE | 29,693,880 | 0.4% | 90.2% |  |
| CONVERT_VALUE | 29,675,820 | 0.4% | 90.7% |  |
| FOR_ITER_TUPLE | 29,304,000 | 0.4% | 91.1% | 44.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 29,112,500 | 0.4% | 91.5% |  |
| LOAD_ATTR_MODULE | 28,793,580 | 0.4% | 91.9% | 0.0% |
| CALL_LEN | 28,278,260 | 0.4% | 92.2% |  |
| CALL_PY_WITH_DEFAULTS | 27,224,860 | 0.4% | 92.6% | 0.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 22,026,840 | 0.3% | 92.9% | 0.0% |
| STORE_ATTR | 21,966,280 | 0.3% | 93.2% |  |
| BINARY_OP_ADD_INT | 21,888,560 | 0.3% | 93.5% |  |
| BINARY_OP | 21,059,100 | 0.3% | 93.8% |  |
| COMPARE_OP_INT | 20,607,360 | 0.3% | 94.1% | 0.1% |
| CALL_METHOD_DESCRIPTOR_O | 19,960,140 | 0.3% | 94.4% |  |
| BINARY_SLICE | 19,736,920 | 0.3% | 94.6% |  |
| BINARY_OP_ADD_UNICODE | 19,372,020 | 0.3% | 94.9% |  |
| BINARY_SUBSCR_LIST_INT | 19,013,660 | 0.3% | 95.2% | 11.3% |
| COPY | 18,442,620 | 0.3% | 95.4% |  |
| CALL_BUILTIN_O | 17,482,140 | 0.2% | 95.7% |  |
| SWAP | 16,746,660 | 0.2% | 95.9% |  |
| TO_BOOL_INT | 16,682,980 | 0.2% | 96.1% | 1.4% |
| LOAD_ATTR_CLASS | 15,286,960 | 0.2% | 96.3% | 7.1% |
| BUILD_STRING | 15,106,200 | 0.2% | 96.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,809,140 | 0.2% | 96.7% |  |
| BUILD_MAP | 14,372,900 | 0.2% | 96.9% |  |
| TO_BOOL_STR | 12,760,100 | 0.2% | 97.1% | 5.1% |
| CALL_FUNCTION_EX | 11,631,900 | 0.2% | 97.3% |  |
| TO_BOOL_LIST | 11,371,940 | 0.2% | 97.4% | 9.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 9,934,560 | 0.1% | 97.6% | 45.4% |
| COMPARE_OP_STR | 8,595,180 | 0.1% | 97.7% | 2.8% |
| BINARY_SUBSCR_TUPLE_INT | 8,419,380 | 0.1% | 97.8% |  |
| BINARY_SUBSCR_GETITEM | 8,354,400 | 0.1% | 97.9% | 0.1% |
| UNPACK_SEQUENCE_TUPLE | 8,336,840 | 0.1% | 98.0% | 0.0% |
| POP_JUMP_IF_NONE | 7,832,100 | 0.1% | 98.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 7,778,400 | 0.1% | 98.2% | 22.6% |
| STORE_ATTR_WITH_HINT | 7,613,400 | 0.1% | 98.3% | 0.0% |
| CALL_STR_1 | 6,612,240 | 0.1% | 98.4% |  |
| JUMP_FORWARD | 6,326,820 | 0.1% | 98.5% |  |
| PUSH_EXC_INFO | 6,134,820 | 0.1% | 98.6% |  |
| POP_EXCEPT | 6,134,820 | 0.1% | 98.7% |  |
| LOAD_ATTR_PROPERTY | 5,895,920 | 0.1% | 98.8% | 68.6% |
| CHECK_EXC_MATCH | 5,778,720 | 0.1% | 98.8% |  |
| LIST_APPEND | 5,745,640 | 0.1% | 98.9% |  |
| CALL_BUILTIN_CLASS | 5,726,400 | 0.1% | 99.0% |  |
| BINARY_OP_SUBTRACT_INT | 5,192,340 | 0.1% | 99.1% |  |
| TO_BOOL_ALWAYS_TRUE | 5,132,280 | 0.1% | 99.1% | 62.8% |
| YIELD_VALUE | 4,946,760 | 0.1% | 99.2% |  |
| BINARY_SUBSCR_STR_INT | 4,857,220 | 0.1% | 99.3% | 0.1% |
| CALL_KW | 4,656,420 | 0.1% | 99.3% |  |
| CALL_TYPE_1 | 4,194,360 | 0.1% | 99.4% |  |
| STORE_SLICE | 3,974,040 | 0.1% | 99.5% |  |
| TO_BOOL | 3,847,540 | 0.1% | 99.5% |  |
| DICT_MERGE | 3,200,220 | 0.0% | 99.6% |  |
| CALL_INTRINSIC_1 | 2,779,860 | 0.0% | 99.6% |  |
| LIST_EXTEND | 2,731,500 | 0.0% | 99.6% |  |
| CALL_ALLOC_AND_ENTER_INIT | 2,694,500 | 0.0% | 99.7% | 63.3% |
| LOAD_FAST_AND_CLEAR | 2,480,940 | 0.0% | 99.7% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,220,720 | 0.0% | 99.7% |  |
| BUILD_CONST_KEY_MAP | 1,876,560 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 1,848,720 | 0.0% | 99.8% |  |
| EXTENDED_ARG | 1,700,240 | 0.0% | 99.8% |  |
| COMPARE_OP | 1,693,320 | 0.0% | 99.8% |  |
| RERAISE | 1,465,320 | 0.0% | 99.8% |  |
| RAISE_VARARGS | 1,175,460 | 0.0% | 99.9% |  |
| BINARY_SUBSCR | 1,169,540 | 0.0% | 99.9% |  |
| EXIT_INIT_CHECK | 988,840 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 918,840 | 0.0% | 99.9% |  |
| LOAD_DEREF | 904,140 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 842,380 | 0.0% | 99.9% |  |
| COPY_FREE_VARS | 823,860 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 787,980 | 0.0% | 99.9% |  |
| IS_OP | 637,440 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 589,200 | 0.0% | 100.0% | 0.4% |
| BUILD_SLICE | 443,220 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 398,500 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 331,920 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 230,880 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 228,360 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 176,880 | 0.0% | 100.0% |  |
| MAKE_CELL | 156,300 | 0.0% | 100.0% |  |
| UNARY_NOT | 130,620 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 75,960 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 73,620 | 0.0% | 100.0% |  |
| MAP_ADD | 49,980 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 27,940 | 0.0% | 100.0% | 5.6% |
| STORE_ATTR_SLOT | 21,840 | 0.0% | 100.0% |  |
| IMPORT_NAME | 14,700 | 0.0% | 100.0% |  |
| STORE_DEREF | 10,920 | 0.0% | 100.0% |  |
| BEFORE_WITH | 7,320 | 0.0% | 100.0% |  |
| UNARY_INVERT | 5,880 | 0.0% | 100.0% |  |
| IMPORT_FROM | 5,880 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,780 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 3,660 | 0.0% | 100.0% |  |
| RESUME | 3,420 | 0.0% | 100.0% | 718.7% |
| DELETE_ATTR | 3,360 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 3,300 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 2,940 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 2,940 | 0.0% | 100.0% | 2.0% |
| LOAD_GLOBAL | 1,920 | 0.0% | 100.0% |  |
| DELETE_FAST | 780 | 0.0% | 100.0% |  |
| STORE_NAME | 540 | 0.0% | 100.0% |  |
| LOAD_NAME | 300 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 260 | 0.0% | 100.0% |  |
| LOAD_LOCALS | 180 | 0.0% | 100.0% |  |
| LOAD_FROM_DICT_OR_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 247,844,840 | 3.4% | 3.4% |
| STORE_FAST LOAD_FAST | 157,955,260 | 2.2% | 5.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 151,525,780 | 2.1% | 7.6% |
| RESUME_CHECK LOAD_FAST | 141,079,380 | 1.9% | 9.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 122,039,660 | 1.7% | 11.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 121,609,200 | 1.7% | 12.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 120,356,480 | 1.7% | 14.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 117,354,380 | 1.6% | 16.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 112,930,180 | 1.5% | 17.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 103,040,780 | 1.4% | 19.1% |
| LOAD_FAST LOAD_ATTR | 89,492,380 | 1.2% | 20.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 87,540,140 | 1.2% | 21.6% |
| RETURN_CONST POP_TOP | 84,320,040 | 1.2% | 22.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 79,144,560 | 1.1% | 23.8% |
| LOAD_FAST LOAD_CONST | 75,356,060 | 1.0% | 24.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 73,611,840 | 1.0% | 25.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 72,249,100 | 1.0% | 26.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 71,396,860 | 1.0% | 27.8% |
| NOP LOAD_FAST | 68,596,640 | 0.9% | 28.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 67,723,740 | 0.9% | 29.7% |
| LOAD_CONST LOAD_FAST | 64,720,500 | 0.9% | 30.6% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 63,439,500 | 0.9% | 31.5% |
| POP_TOP LOAD_FAST | 63,203,020 | 0.9% | 32.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 60,225,440 | 0.8% | 33.2% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 53,097,440 | 0.7% | 33.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 49,550,960 | 0.7% | 34.6% |
| GET_ITER FOR_ITER_LIST | 49,406,900 | 0.7% | 35.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 46,955,600 | 0.6% | 35.9% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 46,933,240 | 0.6% | 36.5% |
| PUSH_NULL LOAD_FAST | 45,813,300 | 0.6% | 37.2% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 45,711,320 | 0.6% | 37.8% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 44,005,720 | 0.6% | 38.4% |
| LOAD_FAST LOAD_ATTR_SLOT | 43,554,660 | 0.6% | 39.0% |
| LOAD_FAST_LOAD_FAST CALL_ISINSTANCE | 43,342,200 | 0.6% | 39.6% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 43,329,080 | 0.6% | 40.2% |
| LOAD_ATTR_SLOT LOAD_ATTR | 42,337,740 | 0.6% | 40.8% |
| CACHE RESUME_CHECK | 39,861,360 | 0.5% | 41.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 38,995,700 | 0.5% | 41.8% |
| ENTER_EXECUTOR LOAD_ATTR_INSTANCE_VALUE | 38,112,960 | 0.5% | 42.4% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 37,122,200 | 0.5% | 42.9% |
| JUMP_BACKWARD FOR_ITER | 37,120,620 | 0.5% | 43.4% |
| POP_TOP RESUME_CHECK | 37,113,120 | 0.5% | 43.9% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 36,963,540 | 0.5% | 44.4% |
| FOR_ITER_GEN POP_TOP | 36,917,820 | 0.5% | 44.9% |
| RETURN_GENERATOR GET_ITER | 36,917,340 | 0.5% | 45.4% |
| GET_ITER FOR_ITER_GEN | 36,914,160 | 0.5% | 45.9% |
| RETURN_CONST END_FOR | 36,887,100 | 0.5% | 46.4% |
| FOR_ITER_LIST STORE_FAST | 36,735,140 | 0.5% | 46.9% |
| END_FOR ENTER_EXECUTOR | 36,688,380 | 0.5% | 47.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 36,445,580 | 0.5% | 47.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 34,939,800 | 0.5% | 48.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_NONE | 32,872,060 | 0.5% | 48.9% |
| LOAD_FAST BINARY_SUBSCR_DICT | 32,446,020 | 0.4% | 49.3% |
| LOAD_ATTR STORE_FAST | 32,115,180 | 0.4% | 49.7% |
| CALL_BUILTIN_FAST STORE_FAST | 32,102,400 | 0.4% | 50.2% |
| BUILD_TUPLE RETURN_VALUE | 31,690,860 | 0.4% | 50.6% |
| STORE_FAST NOP | 30,872,780 | 0.4% | 51.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 30,819,500 | 0.4% | 51.5% |
| LOAD_CONST CALL_BUILTIN_FAST | 29,796,540 | 0.4% | 51.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 29,700,320 | 0.4% | 52.3% |
| CONVERT_VALUE FORMAT_SIMPLE | 29,675,820 | 0.4% | 52.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_CONST | 29,581,920 | 0.4% | 53.1% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 29,563,620 | 0.4% | 53.5% |
| LOAD_FAST CALL_LIST_APPEND | 29,432,360 | 0.4% | 53.9% |
| LOAD_ATTR_WITH_HINT LOAD_FAST | 29,266,720 | 0.4% | 54.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 29,252,880 | 0.4% | 54.7% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 28,759,660 | 0.4% | 55.1% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 28,509,620 | 0.4% | 55.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 28,460,820 | 0.4% | 55.9% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 28,362,800 | 0.4% | 56.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 27,513,300 | 0.4% | 56.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 27,183,180 | 0.4% | 57.0% |
| ENTER_EXECUTOR RETURN_CONST | 26,699,580 | 0.4% | 57.4% |
| GET_ITER FOR_ITER_TUPLE | 26,384,700 | 0.4% | 57.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 25,987,780 | 0.4% | 58.1% |
| LOAD_CONST LOAD_CONST | 25,336,300 | 0.3% | 58.5% |
| LOAD_ATTR LOAD_FAST | 24,904,420 | 0.3% | 58.8% |
| LOAD_CONST STORE_FAST | 24,475,760 | 0.3% | 59.1% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 24,452,880 | 0.3% | 59.5% |
| CALL RESUME_CHECK | 24,128,080 | 0.3% | 59.8% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 23,870,540 | 0.3% | 60.1% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 23,639,920 | 0.3% | 60.5% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_WITH_VALUES | 23,209,420 | 0.3% | 60.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 23,104,580 | 0.3% | 61.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_FAST | 22,852,200 | 0.3% | 61.4% |
| CALL STORE_FAST | 22,729,220 | 0.3% | 61.7% |
| STORE_SUBSCR_DICT LOAD_FAST | 22,528,080 | 0.3% | 62.0% |
| LOAD_FAST BUILD_TUPLE | 22,231,200 | 0.3% | 62.3% |
| STORE_ATTR_INSTANCE_VALUE NOP | 22,151,220 | 0.3% | 62.6% |
| RETURN_VALUE STORE_FAST | 21,841,260 | 0.3% | 62.9% |
| NOP LOAD_GLOBAL_BUILTIN | 21,619,360 | 0.3% | 63.2% |
| LOAD_FAST PUSH_NULL | 21,615,480 | 0.3% | 63.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 21,243,900 | 0.3% | 63.8% |
| LOAD_FAST RETURN_VALUE | 21,093,540 | 0.3% | 64.1% |
| BINARY_SUBSCR_DICT STORE_FAST | 21,093,180 | 0.3% | 64.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 20,896,540 | 0.3% | 64.7% |
| TO_BOOL_NONE POP_JUMP_IF_TRUE | 20,694,980 | 0.3% | 65.0% |
| POP_JUMP_IF_TRUE NOP | 20,618,520 | 0.3% | 65.2% |
| LOAD_FAST CALL_PY_WITH_DEFAULTS | 20,388,320 | 0.3% | 65.5% |
| FOR_ITER STORE_FAST | 20,349,420 | 0.3% | 65.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,890,340 | 60.2% |
| BINARY_OP_ADD_INT | 2,863,160 | 14.5% |
| LOAD_ATTR | 2,053,260 | 10.4% |
| LOAD_FAST | 1,990,020 | 10.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 476,940 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,043,780 | 40.8% |
| RETURN_VALUE | 3,005,700 | 15.2% |
| LOAD_FAST | 2,422,040 | 12.3% |
| LOAD_CONST | 1,154,940 | 5.9% |
| LOAD_FAST_LOAD_FAST | 1,124,580 | 5.7% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,706,920 | 93.3% |
| LOAD_FAST_LOAD_FAST | 258,360 | 6.5% |
| LOAD_ATTR | 8,040 | 0.2% |
| BINARY_OP_ADD_INT | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,701,940 | 93.2% |
| RETURN_CONST | 268,380 | 6.8% |
| LOAD_GLOBAL_BUILTIN | 2,700 | 0.1% |
| LOAD_CONST | 540 | 0.0% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 39,861,360 | 99.4% |
| POP_TOP | 195,300 | 0.5% |
| CALL_INTRINSIC_1 | 51,420 | 0.1% |
| COPY_FREE_VARS | 9,600 | 0.0% |
| RESUME | 3,420 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,380 | 59.8% |
| CALL | 2,940 | 40.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,380 | 59.8% |
| POP_TOP | 2,940 | 40.2% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 396,540 | 50.3% |
| LOAD_FAST_LOAD_FAST | 162,420 | 20.6% |
| RETURN_VALUE | 134,820 | 17.1% |
| CALL_FUNCTION_EX | 60,360 | 7.7% |
| BINARY_OP_ADD_UNICODE | 17,700 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 695,520 | 88.3% |
| LOAD_CONST | 60,360 | 7.7% |
| JUMP_BACKWARD | 14,760 | 1.9% |
| LOAD_GLOBAL_MODULE | 8,820 | 1.1% |
| ENTER_EXECUTOR | 5,160 | 0.7% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 834,060 | 71.3% |
| COPY | 138,320 | 11.8% |
| LOAD_FAST | 112,560 | 9.6% |
| COMPARE_OP_STR | 76,440 | 6.5% |
| BINARY_SUBSCR_LIST_INT | 4,900 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 670,680 | 57.4% |
| LOAD_CONST | 174,480 | 14.9% |
| BUILD_TUPLE | 101,340 | 8.7% |
| LOAD_ATTR_METHOD_NO_DICT | 83,940 | 7.2% |
| STORE_FAST | 77,160 | 6.6% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,049,600 | 87.4% |
| LOAD_GLOBAL_MODULE | 381,660 | 6.6% |
| BUILD_TUPLE | 325,500 | 5.6% |
| LOAD_ATTR_MODULE | 21,960 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,778,720 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 991,800 | 53.6% |
| BUILD_SLICE | 443,220 | 24.0% |
| LOAD_FAST | 217,800 | 11.8% |
| LOAD_CONST | 195,900 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 981,960 | 53.1% |
| LOAD_FAST | 381,420 | 20.6% |
| RETURN_CONST | 308,760 | 16.7% |
| LOAD_FAST_LOAD_FAST | 170,940 | 9.2% |
| LOAD_CONST | 2,940 | 0.2% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 36,887,100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 36,688,380 | 99.5% |
| JUMP_BACKWARD | 97,860 | 0.3% |
| RETURN_CONST | 92,520 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 4,200 | 0.0% |
| LOAD_FAST | 3,120 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 988,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 988,840 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 29,675,820 | 99.9% |
| LOAD_FAST | 18,060 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 15,981,900 | 53.8% |
| BUILD_STRING | 11,595,060 | 39.0% |
| LOAD_FAST | 2,108,100 | 7.1% |
| LOAD_GLOBAL_MODULE | 8,820 | 0.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 36,917,340 | 30.1% |
| LOAD_ATTR_INSTANCE_VALUE | 28,509,620 | 23.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 19,275,920 | 15.7% |
| LOAD_FAST | 16,378,680 | 13.3% |
| BINARY_SLICE | 8,043,780 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 49,406,900 | 40.2% |
| FOR_ITER_GEN | 36,914,160 | 30.0% |
| FOR_ITER_TUPLE | 26,384,700 | 21.5% |
| FOR_ITER | 7,378,860 | 6.0% |
| LOAD_FAST_AND_CLEAR | 2,222,880 | 1.8% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20,031,620 | 51.3% |
| RETURN_CONST | 18,866,080 | 48.3% |
| YIELD_VALUE | 130,260 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 100.0% |


</details>

### LOAD_LOCALS

<details>
<summary> Successors and predecessors for LOAD_LOCALS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FROM_DICT_OR_DEREF | 180 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 331,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 228,360 | 68.8% |
| LOAD_FAST | 103,200 | 31.1% |
| LOAD_FAST_CHECK | 360 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,872,780 | 26.5% |
| STORE_ATTR_INSTANCE_VALUE | 22,151,220 | 19.0% |
| POP_JUMP_IF_TRUE | 20,618,520 | 17.7% |
| RESUME_CHECK | 14,513,280 | 12.4% |
| NOP | 12,424,520 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 68,596,640 | 58.8% |
| LOAD_GLOBAL_BUILTIN | 21,619,360 | 18.5% |
| NOP | 12,424,520 | 10.6% |
| LOAD_FAST_LOAD_FAST | 5,344,500 | 4.6% |
| BUILD_LIST | 3,483,960 | 3.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,152,540 | 67.7% |
| COPY | 922,200 | 15.0% |
| SWAP | 911,040 | 14.9% |
| STORE_FAST | 139,080 | 2.3% |
| CALL_LIST_APPEND | 9,060 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,618,960 | 59.0% |
| RERAISE | 922,200 | 15.0% |
| RETURN_VALUE | 911,040 | 14.9% |
| EXTENDED_ARG | 596,280 | 9.7% |
| ENTER_EXECUTOR | 69,300 | 1.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 84,320,040 | 48.9% |
| FOR_ITER_GEN | 36,917,820 | 21.4% |
| RETURN_VALUE | 15,248,400 | 8.8% |
| POP_JUMP_IF_FALSE | 7,079,820 | 4.1% |
| CALL | 5,491,740 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 63,203,020 | 36.6% |
| RESUME_CHECK | 37,113,120 | 21.5% |
| JUMP_BACKWARD | 14,633,660 | 8.5% |
| RETURN_CONST | 14,169,000 | 8.2% |
| ENTER_EXECUTOR | 13,561,960 | 7.9% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 3,246,180 | 52.9% |
| RERAISE | 922,200 | 15.0% |
| BINARY_SUBSCR_LIST_INT | 814,620 | 13.3% |
| RAISE_VARARGS | 753,540 | 12.3% |
| CALL | 229,020 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,058,460 | 82.5% |
| LOAD_GLOBAL_MODULE | 698,360 | 11.4% |
| LOAD_FAST | 377,940 | 6.2% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,615,480 | 37.2% |
| LOAD_ATTR_MODULE | 19,695,400 | 33.9% |
| LOAD_ATTR_CLASS | 8,282,760 | 14.2% |
| LOAD_ATTR | 8,141,480 | 14.0% |
| LOAD_ATTR_INSTANCE_VALUE | 289,980 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,813,300 | 78.8% |
| LOAD_FAST_LOAD_FAST | 9,648,720 | 16.6% |
| LOAD_CONST | 1,615,740 | 2.8% |
| CALL_PY_EXACT_ARGS | 653,040 | 1.1% |
| CALL | 306,660 | 0.5% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 36,963,540 | 99.6% |
| CALL_KW | 118,560 | 0.3% |
| CALL_PY_WITH_DEFAULTS | 31,020 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 36,917,340 | 99.5% |
| CALL_METHOD_DESCRIPTOR_O | 100,260 | 0.3% |
| CALL_BUILTIN_FAST | 86,220 | 0.2% |
| CALL_TUPLE_1 | 2,940 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,940 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 31,690,860 | 21.8% |
| LOAD_FAST | 21,093,540 | 14.5% |
| RETURN_CONST | 15,122,440 | 10.4% |
| BINARY_SUBSCR_LIST_INT | 11,448,000 | 7.9% |
| BINARY_SUBSCR_DICT | 7,969,560 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 21,841,260 | 15.0% |
| TO_BOOL_BOOL | 20,056,160 | 13.8% |
| INTERPRETER_EXIT | 20,031,620 | 13.8% |
| LOAD_FAST_LOAD_FAST | 16,723,500 | 11.5% |
| POP_TOP | 15,248,400 | 10.5% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 679,620 | 80.7% |
| SWAP | 146,200 | 17.4% |
| LOAD_FAST | 11,200 | 1.3% |
| STORE_SUBSCR | 2,480 | 0.3% |
| LOAD_FAST_LOAD_FAST | 2,100 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 427,960 | 50.8% |
| LOAD_CONST | 191,700 | 22.8% |
| JUMP_FORWARD | 140,160 | 16.6% |
| ENTER_EXECUTOR | 33,720 | 4.0% |
| BUILD_LIST | 19,860 | 2.4% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,708,560 | 44.4% |
| COPY | 1,164,320 | 30.3% |
| LOAD_ATTR_INSTANCE_VALUE | 507,580 | 13.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 183,240 | 4.8% |
| TO_BOOL | 94,860 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,382,920 | 61.9% |
| POP_JUMP_IF_TRUE | 1,297,180 | 33.7% |
| TO_BOOL | 94,860 | 2.5% |
| TO_BOOL_NONE | 51,780 | 1.3% |
| TO_BOOL_LIST | 20,120 | 0.5% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 5,880 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 176,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 176,880 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 92,400 | 70.7% |
| TO_BOOL_BOOL | 38,220 | 29.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 86,160 | 66.0% |
| RETURN_VALUE | 43,380 | 33.2% |
| BUILD_TUPLE | 1,080 | 0.8% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 11,580,660 | 55.0% |
| LOAD_FAST | 2,739,320 | 13.0% |
| RETURN_VALUE | 2,249,100 | 10.7% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,010,960 | 9.5% |
| LOAD_FAST_LOAD_FAST | 1,122,000 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 11,609,480 | 55.1% |
| STORE_FAST | 4,342,740 | 20.6% |
| GET_ITER | 2,421,720 | 11.5% |
| SWAP | 1,295,580 | 6.2% |
| LOAD_FAST | 623,160 | 3.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,876,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,819,620 | 97.0% |
| STORE_FAST | 46,800 | 2.5% |
| LOAD_CONST | 10,140 | 0.5% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,637,580 | 27.7% |
| LOAD_CONST | 10,022,700 | 20.4% |
| RESUME_CHECK | 6,965,100 | 14.2% |
| LOAD_FAST | 5,331,180 | 10.8% |
| NOP | 3,483,960 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,759,180 | 32.0% |
| STORE_FAST | 15,292,140 | 31.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,377,740 | 8.9% |
| CALL_PY_EXACT_ARGS | 4,039,140 | 8.2% |
| BUILD_TUPLE | 2,768,520 | 5.6% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,591,460 | 38.9% |
| POP_TOP | 2,429,100 | 16.9% |
| NOP | 1,937,520 | 13.5% |
| CALL_INTRINSIC_1 | 1,848,660 | 12.9% |
| LOAD_CONST | 889,680 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,591,260 | 52.8% |
| STORE_FAST | 6,285,740 | 43.7% |
| CALL_BUILTIN_FAST | 361,920 | 2.5% |
| BUILD_TUPLE | 66,240 | 0.5% |
| CALL_FUNCTION_EX | 61,800 | 0.4% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 263,400 | 59.4% |
| LOAD_CONST | 179,820 | 40.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 443,220 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 11,595,060 | 76.8% |
| LOAD_CONST | 3,511,140 | 23.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 11,581,020 | 76.7% |
| BINARY_OP_ADD_UNICODE | 2,010,960 | 13.3% |
| CALL_LIST_APPEND | 1,398,120 | 9.3% |
| STORE_FAST | 112,320 | 0.7% |
| LIST_APPEND | 3,660 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,231,200 | 63.2% |
| LOAD_FAST_LOAD_FAST | 7,453,320 | 21.2% |
| BUILD_LIST | 2,768,520 | 7.9% |
| LOAD_CONST | 958,920 | 2.7% |
| LOAD_ATTR_MODULE | 711,180 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 31,690,860 | 90.1% |
| CALL_ISINSTANCE | 751,620 | 2.1% |
| BUILD_MAP | 654,360 | 1.9% |
| BINARY_SUBSCR_DICT | 570,720 | 1.6% |
| SWAP | 341,220 | 1.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 14,237,300 | 23.1% |
| LOAD_FAST | 12,562,180 | 20.4% |
| BINARY_OP | 11,609,480 | 18.8% |
| BUILD_STRING | 11,581,020 | 18.8% |
| LOAD_CONST | 3,013,980 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 24,128,080 | 39.1% |
| STORE_FAST | 22,729,220 | 36.8% |
| POP_TOP | 5,491,740 | 8.9% |
| RETURN_VALUE | 2,292,180 | 3.7% |
| LOAD_FAST | 1,477,560 | 2.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,270,200 | 62.5% |
| DICT_MERGE | 3,200,220 | 27.5% |
| CALL_INTRINSIC_1 | 794,280 | 6.8% |
| ENTER_EXECUTOR | 302,460 | 2.6% |
| BUILD_MAP | 61,800 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,815,580 | 32.8% |
| POP_TOP | 3,473,100 | 29.9% |
| RESUME_CHECK | 1,826,760 | 15.7% |
| STORE_FAST | 1,791,480 | 15.4% |
| CALL_LIST_APPEND | 453,560 | 3.9% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 2,728,440 | 98.2% |
| CACHE | 51,420 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 1,848,660 | 66.5% |
| CALL_FUNCTION_EX | 794,280 | 28.6% |
| LOAD_CONST | 61,800 | 2.2% |
| RERAISE | 51,420 | 1.8% |
| LOAD_FAST | 20,760 | 0.7% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,588,720 | 98.5% |
| ENTER_EXECUTOR | 67,700 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,100,500 | 66.6% |
| RETURN_VALUE | 1,010,940 | 21.7% |
| STORE_FAST | 393,900 | 8.5% |
| RETURN_GENERATOR | 118,560 | 2.5% |
| LOAD_FAST | 17,640 | 0.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,034,680 | 61.1% |
| BUILD_LIST | 519,300 | 30.7% |
| LOAD_FAST_LOAD_FAST | 113,340 | 6.7% |
| LOAD_ATTR_INSTANCE_VALUE | 12,200 | 0.7% |
| COMPARE_OP | 8,020 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,139,920 | 67.3% |
| POP_JUMP_IF_TRUE | 540,140 | 31.9% |
| COMPARE_OP | 8,020 | 0.5% |
| COMPARE_OP_STR | 4,760 | 0.3% |
| COMPARE_OP_INT | 480 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 24,452,880 | 40.8% |
| LOAD_FAST_LOAD_FAST | 23,639,920 | 39.4% |
| LOAD_CONST | 3,640,440 | 6.1% |
| LOAD_FAST | 3,010,740 | 5.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,229,600 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,252,880 | 48.8% |
| POP_JUMP_IF_TRUE | 28,759,660 | 48.0% |
| RETURN_VALUE | 1,647,840 | 2.7% |
| COPY | 279,300 | 0.5% |
| EXTENDED_ARG | 660 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,635,840 | 45.9% |
| LOAD_ATTR | 11,580,660 | 39.0% |
| CALL_METHOD_DESCRIPTOR_O | 2,010,960 | 6.8% |
| RETURN_VALUE | 1,416,480 | 4.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 853,500 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 29,675,820 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,333,560 | 39.8% |
| LOAD_ATTR | 6,964,980 | 37.8% |
| BINARY_SUBSCR_DICT | 902,940 | 4.9% |
| RERAISE | 491,700 | 2.7% |
| COPY | 441,120 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 6,329,640 | 34.3% |
| LOAD_ATTR_INSTANCE_VALUE | 5,454,520 | 29.6% |
| TO_BOOL_INT | 1,252,980 | 6.8% |
| TO_BOOL | 1,164,320 | 6.3% |
| POP_EXCEPT | 922,200 | 5.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 813,900 | 98.8% |
| CACHE | 9,600 | 1.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 300 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 823,860 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,360 | 100.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 660 | 84.6% |
| RERAISE | 60 | 7.7% |
| JUMP_BACKWARD | 60 | 7.7% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,100,860 | 96.9% |
| LOAD_ATTR_INSTANCE_VALUE | 99,120 | 3.1% |
| RETURN_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 3,200,220 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 43,329,080 | 30.5% |
| END_FOR | 36,688,380 | 25.8% |
| CALL_LIST_APPEND | 23,870,540 | 16.8% |
| POP_TOP | 13,561,960 | 9.5% |
| STORE_SUBSCR_DICT | 12,682,560 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 38,112,960 | 26.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 37,122,200 | 26.1% |
| RETURN_CONST | 26,699,580 | 18.8% |
| LOAD_FAST | 12,934,820 | 9.1% |
| LOAD_FAST_LOAD_FAST | 6,520,920 | 4.6% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 596,280 | 35.1% |
| TO_BOOL_LIST | 279,480 | 16.4% |
| TO_BOOL_ALWAYS_TRUE | 161,460 | 9.5% |
| TO_BOOL_INT | 154,740 | 9.1% |
| JUMP_BACKWARD | 108,680 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 709,320 | 41.7% |
| JUMP_FORWARD | 562,860 | 33.1% |
| ENTER_EXECUTOR | 152,460 | 9.0% |
| FOR_ITER_GEN | 96,480 | 5.7% |
| FOR_ITER_LIST | 63,320 | 3.7% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 37,120,620 | 81.9% |
| GET_ITER | 7,378,860 | 16.3% |
| SWAP | 776,700 | 1.7% |
| ENTER_EXECUTOR | 34,440 | 0.1% |
| EXTENDED_ARG | 18,240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20,349,420 | 44.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 18,589,920 | 41.0% |
| LOAD_FAST | 4,725,540 | 10.4% |
| RETURN_CONST | 1,051,920 | 2.3% |
| SWAP | 415,080 | 0.9% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 5,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,880 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,820 | 60.0% |
| IMPORT_FROM | 5,880 | 40.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 300,600 | 47.2% |
| LOAD_CONST | 271,320 | 42.6% |
| LOAD_FAST | 49,500 | 7.8% |
| LOAD_ATTR_MODULE | 16,020 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 348,960 | 54.7% |
| LOAD_CONST | 253,620 | 39.8% |
| POP_JUMP_IF_TRUE | 23,040 | 3.6% |
| STORE_FAST | 11,760 | 1.8% |
| COPY | 60 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 16,764,940 | 39.9% |
| POP_TOP | 14,633,660 | 34.9% |
| LIST_APPEND | 4,162,380 | 9.9% |
| POP_JUMP_IF_FALSE | 3,660,620 | 8.7% |
| STORE_SUBSCR_DICT | 2,376,160 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 37,120,620 | 88.5% |
| FOR_ITER_GEN | 4,692,240 | 11.2% |
| EXTENDED_ARG | 108,680 | 0.3% |
| LOAD_FAST | 37,520 | 0.1% |
| FOR_ITER_LIST | 4,520 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,653,240 | 26.1% |
| STORE_ATTR_INSTANCE_VALUE | 1,545,960 | 24.4% |
| POP_JUMP_IF_FALSE | 783,660 | 12.4% |
| EXTENDED_ARG | 562,860 | 8.9% |
| JUMP_FORWARD | 517,380 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,217,600 | 35.1% |
| LOAD_GLOBAL_BUILTIN | 1,121,140 | 17.7% |
| LOAD_FAST_LOAD_FAST | 1,094,100 | 17.3% |
| LOAD_CONST | 602,160 | 9.5% |
| JUMP_FORWARD | 517,380 | 8.2% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,554,980 | 44.5% |
| BINARY_SUBSCR_DICT | 2,139,000 | 37.2% |
| RETURN_VALUE | 527,940 | 9.2% |
| BINARY_SLICE | 242,120 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 148,360 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,162,380 | 72.4% |
| ENTER_EXECUTOR | 1,583,260 | 27.6% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,711,280 | 99.3% |
| RETURN_VALUE | 12,180 | 0.4% |
| LOAD_ATTR_INSTANCE_VALUE | 4,560 | 0.2% |
| LOAD_CONST | 3,060 | 0.1% |
| BINARY_OP | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 2,728,440 | 99.9% |
| BUILD_TUPLE | 2,940 | 0.1% |
| LOAD_CONST | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,492,380 | 60.4% |
| LOAD_ATTR_SLOT | 42,337,740 | 28.6% |
| LOAD_GLOBAL_MODULE | 8,370,540 | 5.6% |
| LOAD_ATTR | 4,156,740 | 2.8% |
| LOAD_FAST_LOAD_FAST | 1,108,580 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 32,115,180 | 21.7% |
| LOAD_FAST | 24,904,420 | 16.8% |
| POP_JUMP_IF_NOT_NONE | 12,997,280 | 8.8% |
| CONVERT_VALUE | 11,580,660 | 7.8% |
| CALL_BUILTIN_FAST | 11,580,660 | 7.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 75,356,060 | 28.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 29,581,920 | 11.1% |
| LOAD_CONST | 25,336,300 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 17,637,000 | 6.6% |
| FORMAT_SIMPLE | 15,981,900 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,720,500 | 24.3% |
| CALL_BUILTIN_FAST | 29,796,540 | 11.2% |
| LOAD_CONST | 25,336,300 | 9.5% |
| STORE_FAST | 24,475,760 | 9.2% |
| BINARY_SLICE | 11,890,340 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 798,360 | 88.3% |
| LOAD_ATTR | 42,000 | 4.6% |
| LOAD_ATTR_METHOD_NO_DICT | 35,280 | 3.9% |
| LOAD_FAST | 10,920 | 1.2% |
| POP_TOP | 10,860 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 798,300 | 88.3% |
| LOAD_ATTR_INSTANCE_VALUE | 42,000 | 4.6% |
| LOAD_CONST | 35,280 | 3.9% |
| CALL_PY_EXACT_ARGS | 10,900 | 1.2% |
| RETURN_VALUE | 10,860 | 1.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 157,955,260 | 10.9% |
| RESUME_CHECK | 141,079,380 | 9.7% |
| POP_JUMP_IF_FALSE | 122,039,660 | 8.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 117,354,380 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 112,930,180 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 247,844,840 | 17.1% |
| CALL_PY_EXACT_ARGS | 121,609,200 | 8.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120,356,480 | 8.3% |
| LOAD_ATTR | 89,492,380 | 6.2% |
| LOAD_CONST | 75,356,060 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,222,880 | 89.6% |
| LOAD_FAST_AND_CLEAR | 258,060 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,222,880 | 89.6% |
| LOAD_FAST_AND_CLEAR | 258,060 | 10.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,260 | 26.2% |
| ENTER_EXECUTOR | 14,220 | 19.3% |
| STORE_FAST | 11,760 | 16.0% |
| FOR_ITER | 9,660 | 13.1% |
| LOAD_FAST_LOAD_FAST | 4,380 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 25,560 | 34.7% |
| RETURN_VALUE | 17,160 | 23.3% |
| LOAD_FAST | 9,960 | 13.5% |
| TO_BOOL_NONE | 9,160 | 12.4% |
| BINARY_OP | 3,240 | 4.4% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 67,723,740 | 26.9% |
| STORE_FAST | 45,711,320 | 18.1% |
| POP_JUMP_IF_FALSE | 27,513,300 | 10.9% |
| RESUME_CHECK | 18,384,420 | 7.3% |
| RETURN_VALUE | 16,723,500 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 43,342,200 | 17.2% |
| LOAD_FAST | 36,445,580 | 14.5% |
| STORE_ATTR_INSTANCE_VALUE | 25,987,780 | 10.3% |
| CONTAINS_OP | 23,639,920 | 9.4% |
| CALL_BUILTIN_FAST | 20,896,540 | 8.3% |


</details>

### LOAD_FROM_DICT_OR_DEREF

<details>
<summary> Successors and predecessors for LOAD_FROM_DICT_OR_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_LOCALS | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 300 | 15.6% |
| STORE_FAST | 240 | 12.5% |
| LOAD_FAST | 200 | 10.4% |
| RESUME_CHECK | 180 | 9.4% |
| RETURN_VALUE | 140 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,280 | 66.7% |
| LOAD_GLOBAL_BUILTIN | 620 | 32.3% |
| LOAD_ATTR | 20 | 1.0% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 240 | 80.0% |
| RESUME_CHECK | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 60.0% |
| STORE_NAME | 60 | 20.0% |
| UNPACK_SEQUENCE_TUPLE | 40 | 13.3% |
| UNPACK_SEQUENCE | 20 | 6.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 145,380 | 93.0% |
| MAKE_CELL | 10,920 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 145,380 | 93.0% |
| MAKE_CELL | 10,920 | 7.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,160 | 82.4% |
| LOAD_ATTR_MODULE | 5,880 | 11.8% |
| LOAD_CONST | 2,940 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 47,040 | 94.1% |
| CALL_FUNCTION_EX | 2,940 | 5.9% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 103,040,780 | 45.2% |
| TO_BOOL_NONE | 44,005,720 | 19.3% |
| CONTAINS_OP | 29,252,880 | 12.8% |
| COMPARE_OP_INT | 14,806,420 | 6.5% |
| TO_BOOL_LIST | 10,686,940 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,039,660 | 53.6% |
| RETURN_CONST | 34,939,800 | 15.3% |
| LOAD_FAST_LOAD_FAST | 27,513,300 | 12.1% |
| LOAD_GLOBAL_BUILTIN | 11,131,800 | 4.9% |
| LOAD_CONST | 9,947,760 | 4.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,900,100 | 75.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,925,880 | 24.6% |
| CALL_BUILTIN_FAST | 3,060 | 0.0% |
| LOAD_ATTR_WITH_HINT | 2,880 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,969,000 | 50.7% |
| RETURN_CONST | 2,604,720 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 1,129,380 | 14.4% |
| LOAD_CONST | 111,720 | 1.4% |
| LOAD_GLOBAL_MODULE | 7,720 | 0.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,819,500 | 63.4% |
| LOAD_ATTR | 12,997,280 | 26.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,578,260 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,004,100 | 2.1% |
| STORE_FAST_LOAD_FAST | 109,980 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,995,700 | 80.2% |
| NOP | 3,840,600 | 7.9% |
| RETURN_CONST | 2,318,220 | 4.8% |
| LOAD_GLOBAL_BUILTIN | 2,035,480 | 4.2% |
| LOAD_FAST_LOAD_FAST | 1,043,400 | 2.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 49,550,960 | 38.4% |
| CONTAINS_OP | 28,759,660 | 22.3% |
| TO_BOOL_NONE | 20,694,980 | 16.1% |
| TO_BOOL_INT | 12,807,420 | 9.9% |
| TO_BOOL_STR | 6,523,580 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 43,329,080 | 33.6% |
| LOAD_FAST | 21,243,900 | 16.5% |
| NOP | 20,618,520 | 16.0% |
| JUMP_BACKWARD | 16,764,940 | 13.0% |
| RETURN_CONST | 12,380,160 | 9.6% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 583,740 | 49.7% |
| LOAD_GLOBAL_BUILTIN | 543,240 | 46.2% |
| POP_JUMP_IF_FALSE | 32,160 | 2.7% |
| LOAD_CONST | 11,760 | 1.0% |
| CALL | 3,900 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 753,540 | 64.1% |
| COPY | 421,860 | 35.9% |
| LOAD_CONST | 60 | 0.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 922,200 | 62.9% |
| POP_TOP | 377,940 | 25.8% |
| POP_JUMP_IF_FALSE | 113,700 | 7.8% |
| CALL_INTRINSIC_1 | 51,420 | 3.5% |
| DELETE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 922,200 | 65.2% |
| COPY | 491,700 | 34.8% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,939,800 | 21.6% |
| ENTER_EXECUTOR | 26,699,580 | 16.5% |
| RESUME_CHECK | 16,878,540 | 10.4% |
| POP_TOP | 14,169,000 | 8.7% |
| POP_JUMP_IF_TRUE | 12,380,160 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 84,320,040 | 52.0% |
| END_FOR | 36,887,100 | 22.8% |
| INTERPRETER_EXIT | 18,866,080 | 11.6% |
| RETURN_VALUE | 15,122,440 | 9.3% |
| TO_BOOL_NONE | 3,193,360 | 2.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 228,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 134,400 | 58.9% |
| STORE_FAST | 93,840 | 41.1% |
| STORE_NAME | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,223,460 | 69.3% |
| LOAD_FAST_LOAD_FAST | 5,828,840 | 26.5% |
| SWAP | 857,600 | 3.9% |
| LOAD_ATTR_MODULE | 38,220 | 0.2% |
| STORE_ATTR | 11,680 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,116,100 | 59.7% |
| RETURN_CONST | 6,125,220 | 27.9% |
| LOAD_GLOBAL_MODULE | 1,838,580 | 8.4% |
| LOAD_FAST_LOAD_FAST | 619,380 | 2.8% |
| LOAD_GLOBAL_BUILTIN | 74,160 | 0.3% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 10,860 | 99.5% |
| CALL | 60 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,860 | 99.5% |
| LOAD_GLOBAL_MODULE | 40 | 0.4% |
| LOAD_GLOBAL | 20 | 0.2% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 36,735,140 | 11.0% |
| LOAD_ATTR | 32,115,180 | 9.6% |
| CALL_BUILTIN_FAST | 32,102,400 | 9.6% |
| LOAD_CONST | 24,475,760 | 7.3% |
| CALL | 22,729,220 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 157,955,260 | 47.3% |
| LOAD_GLOBAL_BUILTIN | 46,933,240 | 14.1% |
| LOAD_FAST_LOAD_FAST | 45,711,320 | 13.7% |
| NOP | 30,872,780 | 9.3% |
| LOAD_CONST | 14,097,000 | 4.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 629,920 | 68.6% |
| FOR_ITER_TUPLE | 279,300 | 30.4% |
| FOR_ITER | 4,800 | 0.5% |
| FOR_ITER_RANGE | 3,200 | 0.3% |
| YIELD_VALUE | 900 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 369,300 | 40.2% |
| TO_BOOL_STR | 280,260 | 30.5% |
| POP_JUMP_IF_NOT_NONE | 109,980 | 12.0% |
| LOAD_ATTR_METHOD_NO_DICT | 96,620 | 10.5% |
| LOAD_ATTR | 21,640 | 2.4% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 28,362,800 | 76.0% |
| UNPACK_SEQUENCE_TUPLE | 8,330,340 | 22.3% |
| STORE_FAST_STORE_FAST | 573,920 | 1.5% |
| UNPACK_SEQUENCE_LIST | 27,860 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,000,360 | 32.2% |
| LOAD_GLOBAL_MODULE | 11,756,640 | 31.5% |
| STORE_FAST | 7,998,600 | 21.4% |
| LOAD_GLOBAL_BUILTIN | 2,474,100 | 6.6% |
| LOAD_FAST_LOAD_FAST | 2,363,300 | 6.3% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 180 | 33.3% |
| STORE_NAME | 120 | 22.2% |
| UNPACK_SEQUENCE_TUPLE | 60 | 11.1% |
| SET_FUNCTION_ATTRIBUTE | 60 | 11.1% |
| LOAD_NAME | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 240 | 44.4% |
| STORE_NAME | 120 | 22.2% |
| RETURN_CONST | 60 | 11.1% |
| LOAD_FAST | 60 | 11.1% |
| LOAD_CONST | 60 | 11.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,272,540 | 25.5% |
| RETURN_VALUE | 2,394,900 | 14.3% |
| LOAD_FAST_AND_CLEAR | 2,222,880 | 13.3% |
| BUILD_LIST | 2,222,880 | 13.3% |
| BINARY_OP | 1,295,580 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,464,060 | 32.6% |
| POP_TOP | 2,600,760 | 15.5% |
| BUILD_LIST | 2,222,880 | 13.3% |
| STORE_FAST | 1,248,420 | 7.5% |
| FOR_ITER_LIST | 1,134,480 | 6.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 220 | 84.6% |
| LOAD_NAME | 20 | 7.7% |
| LOAD_ATTR | 20 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 69.2% |
| UNPACK_SEQUENCE_TUPLE | 60 | 23.1% |
| UNPACK_SEQUENCE_LIST | 20 | 7.7% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,793,740 | 96.9% |
| CALL_METHOD_DESCRIPTOR_O | 87,600 | 1.8% |
| BUILD_TUPLE | 48,900 | 1.0% |
| LOAD_ATTR_INSTANCE_VALUE | 9,360 | 0.2% |
| RETURN_VALUE | 4,740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,766,700 | 96.4% |
| INTERPRETER_EXIT | 130,260 | 2.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 48,900 | 1.0% |
| STORE_FAST_LOAD_FAST | 900 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 3,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,420 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 2,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,940 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,938,200 | 45.4% |
| LOAD_FAST | 8,733,960 | 39.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,956,660 | 8.9% |
| CALL_LEN | 728,840 | 3.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 367,380 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,964,340 | 22.7% |
| SWAP | 4,272,540 | 19.5% |
| LOAD_FAST | 3,356,760 | 15.3% |
| BINARY_SLICE | 2,863,160 | 13.1% |
| LOAD_GLOBAL_BUILTIN | 2,759,220 | 12.6% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,863,780 | 76.7% |
| BUILD_STRING | 2,010,960 | 10.4% |
| LOAD_CONST | 868,400 | 4.5% |
| LOAD_ATTR | 603,300 | 3.1% |
| RETURN_VALUE | 411,960 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,200,440 | 73.3% |
| RETURN_VALUE | 2,037,360 | 10.5% |
| STORE_FAST | 1,438,860 | 7.4% |
| SWAP | 1,171,500 | 6.0% |
| LOAD_CONST | 344,940 | 1.8% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,940 | 89.1% |
| BINARY_OP_SUBTRACT_INT | 180 | 5.5% |
| BINARY_OP_ADD_INT | 180 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,940 | 89.1% |
| STORE_FAST | 180 | 5.5% |
| BINARY_OP_SUBTRACT_INT | 180 | 5.5% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 2,940 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,953,680 | 56.9% |
| CALL_LEN | 916,860 | 17.7% |
| LOAD_ATTR_INSTANCE_VALUE | 836,520 | 16.1% |
| LOAD_FAST | 480,360 | 9.3% |
| LOAD_FAST_LOAD_FAST | 4,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,703,820 | 32.8% |
| LOAD_CONST | 1,084,900 | 20.9% |
| CALL_PY_EXACT_ARGS | 910,720 | 17.5% |
| BINARY_SUBSCR_LIST_INT | 432,060 | 8.3% |
| LOAD_FAST | 325,440 | 6.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,446,020 | 79.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,451,100 | 6.0% |
| CALL_BUILTIN_O | 2,139,000 | 5.2% |
| LOAD_CONST | 1,112,580 | 2.7% |
| LOAD_FAST_LOAD_FAST | 1,099,640 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 21,093,180 | 51.5% |
| RETURN_VALUE | 7,969,560 | 19.5% |
| UNPACK_SEQUENCE_TUPLE | 4,903,800 | 12.0% |
| LIST_APPEND | 2,139,000 | 5.2% |
| TO_BOOL_ALWAYS_TRUE | 999,060 | 2.4% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,670,940 | 55.9% |
| LOAD_ATTR_INSTANCE_VALUE | 3,355,020 | 40.2% |
| ENTER_EXECUTOR | 221,000 | 2.6% |
| LOAD_FAST_LOAD_FAST | 59,640 | 0.7% |
| LOAD_FAST | 29,520 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,344,240 | 99.9% |
| LOAD_ATTR_METHOD_NO_DICT | 5,300 | 0.1% |
| LOAD_FAST | 1,920 | 0.0% |
| CONTAINS_OP | 1,020 | 0.0% |
| PUSH_EXC_INFO | 900 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,392,440 | 75.7% |
| LOAD_FAST_LOAD_FAST | 2,532,420 | 13.3% |
| LOAD_CONST | 1,437,300 | 7.6% |
| BINARY_OP_SUBTRACT_INT | 432,060 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 104,100 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,448,000 | 63.7% |
| LOAD_CONST | 1,622,640 | 9.0% |
| LOAD_FAST | 1,399,140 | 7.8% |
| STORE_FAST | 988,740 | 5.5% |
| PUSH_EXC_INFO | 814,620 | 4.5% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,273,000 | 67.4% |
| LOAD_CONST | 1,048,560 | 21.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 246,480 | 5.1% |
| BINARY_OP_SUBTRACT_INT | 246,480 | 5.1% |
| LOAD_FAST | 33,060 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,273,540 | 67.4% |
| LOAD_CONST | 855,600 | 17.6% |
| STORE_FAST | 617,700 | 12.7% |
| LOAD_FAST | 85,740 | 1.8% |
| COMPARE_OP_STR | 17,460 | 0.4% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,419,360 | 100.0% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 3,815,040 | 45.3% |
| CALL_LIST_APPEND | 3,815,040 | 45.3% |
| LOAD_CONST | 337,140 | 4.0% |
| LOAD_GLOBAL_BUILTIN | 296,940 | 3.5% |
| STORE_FAST | 84,900 | 1.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,904,280 | 70.7% |
| LOAD_FAST | 386,160 | 14.3% |
| LOAD_GLOBAL_MODULE | 188,460 | 7.0% |
| LOAD_FAST_LOAD_FAST | 62,860 | 2.3% |
| LOAD_ATTR_WITH_HINT | 60,300 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,661,000 | 61.6% |
| RESUME_CHECK | 988,840 | 36.7% |
| CALL_ALLOC_AND_ENTER_INIT | 32,180 | 1.2% |
| STORE_FAST | 12,480 | 0.5% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,830,420 | 99.0% |
| CALL_PY_EXACT_ARGS | 84,280 | 0.8% |
| LOAD_FAST_LOAD_FAST | 9,660 | 0.1% |
| LOAD_CONST | 2,940 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,846,300 | 99.1% |
| CALL_PY_EXACT_ARGS | 84,600 | 0.9% |
| POP_TOP | 2,940 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 360 | 0.0% |
| COPY_FREE_VARS | 300 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,932,000 | 33.7% |
| LOAD_FAST | 1,621,540 | 28.3% |
| CALL_BUILTIN_CLASS | 1,486,320 | 26.0% |
| CALL_LEN | 455,640 | 8.0% |
| CALL_FUNCTION_EX | 87,600 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,620,560 | 45.8% |
| CALL_BUILTIN_CLASS | 1,486,320 | 26.0% |
| LOAD_FAST | 1,089,600 | 19.0% |
| BINARY_OP | 297,780 | 5.2% |
| STORE_FAST | 143,940 | 2.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,796,540 | 46.3% |
| LOAD_FAST_LOAD_FAST | 20,896,540 | 32.5% |
| LOAD_ATTR | 11,580,660 | 18.0% |
| BINARY_SUBSCR_DICT | 981,960 | 1.5% |
| LOAD_FAST | 503,220 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 32,102,400 | 49.9% |
| TO_BOOL_BOOL | 29,563,620 | 45.9% |
| POP_TOP | 1,670,160 | 2.6% |
| LOAD_ATTR_METHOD_NO_DICT | 536,400 | 0.8% |
| COPY | 137,220 | 0.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,011,320 | 90.6% |
| STORE_FAST | 131,640 | 5.9% |
| LOAD_FAST | 68,880 | 3.1% |
| RETURN_GENERATOR | 2,940 | 0.1% |
| LOAD_FAST_LOAD_FAST | 2,940 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,192,700 | 98.7% |
| PUSH_EXC_INFO | 17,700 | 0.8% |
| POP_TOP | 5,940 | 0.3% |
| RETURN_VALUE | 4,380 | 0.2% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,383,440 | 99.4% |
| RETURN_VALUE | 48,660 | 0.3% |
| CALL_BUILTIN_FAST | 35,280 | 0.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,880 | 0.0% |
| BINARY_SLICE | 4,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 12,835,620 | 73.4% |
| LOAD_CONST | 2,452,140 | 14.0% |
| BINARY_SUBSCR_DICT | 2,139,000 | 12.2% |
| TO_BOOL_BOOL | 41,160 | 0.2% |
| LOAD_FAST | 5,340 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 43,342,200 | 54.0% |
| LOAD_GLOBAL_MODULE | 15,613,140 | 19.5% |
| LOAD_GLOBAL_BUILTIN | 13,876,780 | 17.3% |
| LOAD_ATTR_MODULE | 5,546,540 | 6.9% |
| LOAD_FAST | 1,021,500 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 79,144,560 | 98.6% |
| RETURN_VALUE | 1,091,280 | 1.4% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 15,690,640 | 55.5% |
| LOAD_FAST | 11,838,680 | 41.9% |
| LOAD_ATTR | 293,400 | 1.0% |
| RETURN_VALUE | 177,540 | 0.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 108,240 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 6,555,460 | 23.2% |
| LOAD_CONST | 5,157,060 | 18.2% |
| RETURN_VALUE | 4,728,120 | 16.7% |
| LOAD_FAST | 3,825,000 | 13.5% |
| CALL_PY_EXACT_ARGS | 2,726,280 | 9.6% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,432,360 | 71.0% |
| BINARY_SUBSCR_TUPLE_INT | 3,815,040 | 9.2% |
| RETURN_VALUE | 2,079,740 | 5.0% |
| LOAD_CONST | 2,045,660 | 4.9% |
| BUILD_STRING | 1,398,120 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 23,870,540 | 57.6% |
| RETURN_CONST | 9,282,660 | 22.4% |
| LOAD_GLOBAL_MODULE | 2,634,240 | 6.4% |
| LOAD_FAST | 2,459,660 | 5.9% |
| LOAD_CONST | 932,220 | 2.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 7,832,320 | 35.6% |
| LOAD_CONST | 4,502,500 | 20.4% |
| LOAD_FAST_LOAD_FAST | 4,489,920 | 20.4% |
| BUILD_LIST | 4,377,740 | 19.9% |
| LOAD_FAST | 716,400 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,971,260 | 31.6% |
| RETURN_VALUE | 4,497,120 | 20.4% |
| TO_BOOL_STR | 2,954,940 | 13.4% |
| LOAD_ATTR_METHOD_NO_DICT | 2,259,120 | 10.3% |
| CALL_METHOD_DESCRIPTOR_O | 2,011,000 | 9.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,625,080 | 46.6% |
| LOAD_FAST | 2,234,100 | 28.7% |
| LOAD_CONST | 1,772,740 | 22.8% |
| LOAD_FAST_LOAD_FAST | 105,120 | 1.4% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 33,180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 2,926,840 | 37.6% |
| BINARY_OP | 2,010,960 | 25.9% |
| STORE_FAST | 1,091,400 | 14.0% |
| RETURN_VALUE | 802,860 | 10.3% |
| LOAD_FAST | 277,140 | 3.6% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 14,800,240 | 99.9% |
| LOAD_ATTR | 8,880 | 0.1% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,267,580 | 35.6% |
| STORE_FAST | 3,410,580 | 23.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,011,320 | 13.6% |
| STORE_SUBSCR_DICT | 1,473,660 | 10.0% |
| RETURN_VALUE | 1,115,880 | 7.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,886,580 | 54.5% |
| LOAD_ATTR | 3,012,180 | 15.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,926,840 | 14.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,011,000 | 10.1% |
| STORE_FAST | 414,060 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,074,020 | 25.4% |
| RETURN_VALUE | 4,908,360 | 24.6% |
| STORE_FAST | 2,641,080 | 13.2% |
| LOAD_CONST | 2,017,380 | 10.1% |
| CONVERT_VALUE | 2,010,960 | 10.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 121,609,200 | 64.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 29,700,320 | 15.7% |
| LOAD_FAST_LOAD_FAST | 10,473,500 | 5.5% |
| LOAD_ATTR_INSTANCE_VALUE | 6,173,920 | 3.3% |
| BUILD_LIST | 4,039,140 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 151,525,780 | 79.9% |
| RETURN_GENERATOR | 36,963,540 | 19.5% |
| COPY_FREE_VARS | 813,900 | 0.4% |
| MAKE_CELL | 145,380 | 0.1% |
| CALL_PY_EXACT_ARGS | 85,740 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,388,320 | 74.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,433,560 | 12.6% |
| LOAD_CONST | 1,267,700 | 4.7% |
| CALL_STR_1 | 853,500 | 3.1% |
| ENTER_EXECUTOR | 630,080 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 27,183,180 | 99.8% |
| RETURN_GENERATOR | 31,020 | 0.1% |
| STORE_FAST | 5,080 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,120 | 0.0% |
| CALL_PY_EXACT_ARGS | 1,260 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,884,400 | 73.9% |
| RETURN_VALUE | 1,724,700 | 26.1% |
| CALL_LEN | 1,980 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,140 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,018,960 | 45.7% |
| RETURN_VALUE | 1,923,420 | 29.1% |
| CALL_PY_WITH_DEFAULTS | 853,500 | 12.9% |
| STORE_SUBSCR_DICT | 718,500 | 10.9% |
| CALL | 75,720 | 1.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 163,260 | 70.7% |
| POP_JUMP_IF_TRUE | 35,280 | 15.3% |
| LOAD_CONST | 17,640 | 7.6% |
| LOAD_FAST | 11,760 | 5.1% |
| RETURN_GENERATOR | 2,940 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 166,200 | 72.0% |
| LOAD_FAST | 61,740 | 26.7% |
| BINARY_OP | 2,940 | 1.3% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,577,200 | 85.3% |
| LOAD_FAST | 617,160 | 14.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,200 | 85.3% |
| LOAD_FAST_LOAD_FAST | 586,560 | 14.0% |
| LOAD_FAST | 17,640 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 8,820 | 0.2% |
| PUSH_NULL | 3,660 | 0.1% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,475,280 | 36.3% |
| CALL_LEN | 6,555,460 | 31.8% |
| LOAD_FAST_LOAD_FAST | 2,595,840 | 12.6% |
| LOAD_ATTR_WITH_HINT | 2,250,420 | 10.9% |
| LOAD_FAST | 1,333,380 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,806,420 | 71.9% |
| POP_JUMP_IF_TRUE | 3,741,280 | 18.2% |
| RETURN_VALUE | 1,970,820 | 9.6% |
| COPY | 88,380 | 0.4% |
| COMPARE_OP | 280 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,451,560 | 63.4% |
| RETURN_VALUE | 2,809,920 | 32.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 212,400 | 2.5% |
| LOAD_FAST | 37,040 | 0.4% |
| LOAD_FAST_LOAD_FAST | 28,860 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,628,560 | 53.9% |
| RETURN_VALUE | 2,941,320 | 34.2% |
| POP_JUMP_IF_TRUE | 881,540 | 10.3% |
| BINARY_SUBSCR | 76,440 | 0.9% |
| LOAD_GLOBAL_MODULE | 38,220 | 0.4% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 36,914,160 | 88.5% |
| JUMP_BACKWARD | 4,692,240 | 11.3% |
| EXTENDED_ARG | 96,480 | 0.2% |
| SWAP | 360 | 0.0% |
| LOAD_FAST | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 36,917,820 | 88.5% |
| RESUME_CHECK | 4,785,780 | 11.5% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 49,406,900 | 86.7% |
| ENTER_EXECUTOR | 6,014,620 | 10.6% |
| SWAP | 1,134,480 | 2.0% |
| FOR_ITER_TUPLE | 248,320 | 0.4% |
| LOAD_FAST | 103,200 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,735,140 | 64.5% |
| RETURN_CONST | 9,928,500 | 17.4% |
| LOAD_FAST | 6,837,860 | 12.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,954,500 | 3.4% |
| STORE_FAST_LOAD_FAST | 629,920 | 1.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 365,040 | 91.6% |
| SWAP | 32,040 | 8.0% |
| JUMP_BACKWARD | 1,420 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 366,300 | 91.9% |
| SWAP | 28,560 | 7.2% |
| STORE_FAST_LOAD_FAST | 3,200 | 0.8% |
| LOAD_FAST | 420 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 20 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 26,384,700 | 90.0% |
| ENTER_EXECUTOR | 2,388,320 | 8.2% |
| SWAP | 279,300 | 1.0% |
| FOR_ITER_LIST | 248,340 | 0.8% |
| EXTENDED_ARG | 2,940 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,301,860 | 62.5% |
| RETURN_CONST | 8,680,260 | 29.6% |
| LOAD_FAST | 1,478,060 | 5.0% |
| LOAD_FAST_LOAD_FAST | 298,120 | 1.0% |
| STORE_FAST_LOAD_FAST | 279,300 | 1.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 14,188,880 | 92.8% |
| ENTER_EXECUTOR | 807,600 | 5.3% |
| LOAD_FAST | 156,000 | 1.0% |
| LOAD_FAST_LOAD_FAST | 105,060 | 0.7% |
| LOAD_ATTR_CLASS | 20,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 8,282,760 | 54.2% |
| TO_BOOL_BOOL | 2,450,640 | 16.0% |
| LOAD_FAST | 2,090,760 | 13.7% |
| CONTAINS_OP | 1,750,380 | 11.5% |
| CALL_PY_EXACT_ARGS | 253,380 | 1.7% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 247,844,840 | 75.6% |
| ENTER_EXECUTOR | 38,112,960 | 11.6% |
| LOAD_ATTR_INSTANCE_VALUE | 18,010,580 | 5.5% |
| LOAD_FAST_LOAD_FAST | 17,390,660 | 5.3% |
| COPY | 5,454,520 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 87,540,140 | 26.7% |
| TO_BOOL_NONE | 32,872,060 | 10.0% |
| GET_ITER | 28,509,620 | 8.7% |
| CONTAINS_OP | 24,452,880 | 7.5% |
| LOAD_ATTR_INSTANCE_VALUE | 18,010,580 | 5.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,611,840 | 60.2% |
| LOAD_ATTR_INSTANCE_VALUE | 15,431,480 | 12.6% |
| LOAD_CONST | 11,066,640 | 9.0% |
| LOAD_ATTR_WITH_HINT | 7,483,800 | 6.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,898,060 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,396,860 | 58.4% |
| LOAD_CONST | 17,637,000 | 14.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,800,240 | 12.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 7,832,320 | 6.4% |
| LOAD_FAST_LOAD_FAST | 6,021,540 | 4.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,356,480 | 59.5% |
| ENTER_EXECUTOR | 37,122,200 | 18.3% |
| LOAD_ATTR_WITH_HINT | 23,209,420 | 11.5% |
| LOAD_ATTR_INSTANCE_VALUE | 11,884,200 | 5.9% |
| LOAD_FAST_LOAD_FAST | 4,475,220 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,354,380 | 58.0% |
| CALL_PY_EXACT_ARGS | 29,700,320 | 14.7% |
| LOAD_CONST | 29,581,920 | 14.6% |
| LOAD_FAST_LOAD_FAST | 16,616,200 | 8.2% |
| CALL_PY_WITH_DEFAULTS | 3,433,560 | 1.7% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 28,460,820 | 98.8% |
| ENTER_EXECUTOR | 214,580 | 0.7% |
| LOAD_ATTR_MODULE | 71,180 | 0.2% |
| LOAD_FAST | 24,120 | 0.1% |
| LOAD_ATTR_WITH_HINT | 12,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 19,695,400 | 68.4% |
| CALL_ISINSTANCE | 5,546,540 | 19.3% |
| LOAD_GLOBAL_MODULE | 801,600 | 2.8% |
| BUILD_TUPLE | 711,180 | 2.5% |
| LOAD_CONST | 646,380 | 2.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,720 | 98.4% |
| LOAD_ATTR | 60 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,680 | 97.4% |
| CALL | 60 | 1.6% |
| LOAD_ATTR | 40 | 1.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 63,439,500 | 95.4% |
| ENTER_EXECUTOR | 1,217,920 | 1.8% |
| LOAD_FAST_LOAD_FAST | 914,280 | 1.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 687,300 | 1.0% |
| LOAD_ATTR_INSTANCE_VALUE | 196,020 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,852,200 | 34.4% |
| GET_ITER | 19,275,920 | 29.0% |
| STORE_FAST | 4,201,680 | 6.3% |
| LOAD_ATTR_METHOD_NO_DICT | 3,898,060 | 5.9% |
| CALL_PY_EXACT_ARGS | 3,754,860 | 5.6% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,802,880 | 98.4% |
| LOAD_ATTR_PROPERTY | 76,020 | 1.3% |
| LOAD_ATTR | 17,020 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 3,114,180 | 52.8% |
| RESUME_CHECK | 1,852,240 | 31.4% |
| LOAD_ATTR_WITH_HINT | 402,480 | 6.8% |
| LOAD_FAST | 383,760 | 6.5% |
| LOAD_ATTR_PROPERTY | 76,020 | 1.3% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,554,660 | 98.5% |
| LOAD_ATTR_SLOT | 666,300 | 1.5% |
| LOAD_FAST_LOAD_FAST | 17,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 42,337,740 | 95.7% |
| LOAD_FAST | 1,010,880 | 2.3% |
| LOAD_ATTR_SLOT | 666,300 | 1.5% |
| PUSH_NULL | 84,960 | 0.2% |
| LOAD_GLOBAL_MODULE | 76,320 | 0.2% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,097,440 | 61.8% |
| LOAD_ATTR_WITH_HINT | 16,586,460 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 13,729,180 | 16.0% |
| LOAD_FAST_LOAD_FAST | 1,266,500 | 1.5% |
| RETURN_VALUE | 489,720 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,266,720 | 34.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 23,209,420 | 27.0% |
| LOAD_ATTR_WITH_HINT | 16,586,460 | 19.3% |
| LOAD_ATTR_METHOD_NO_DICT | 7,483,800 | 8.7% |
| TO_BOOL_BOOL | 2,831,640 | 3.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 72,249,100 | 35.0% |
| STORE_FAST | 46,933,240 | 22.8% |
| NOP | 21,619,360 | 10.5% |
| LOAD_FAST | 14,861,640 | 7.2% |
| POP_JUMP_IF_FALSE | 11,131,800 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 112,930,180 | 54.8% |
| LOAD_FAST_LOAD_FAST | 67,723,740 | 32.8% |
| CALL_ISINSTANCE | 13,876,780 | 6.7% |
| CHECK_EXC_MATCH | 5,049,600 | 2.4% |
| LOAD_CONST | 3,594,960 | 1.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 23,104,580 | 25.1% |
| LOAD_FAST | 18,678,260 | 20.3% |
| STORE_FAST_STORE_FAST | 11,756,640 | 12.8% |
| STORE_FAST | 8,978,260 | 9.8% |
| POP_JUMP_IF_FALSE | 4,880,260 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 28,460,820 | 30.9% |
| CALL_ISINSTANCE | 15,613,140 | 17.0% |
| LOAD_ATTR_CLASS | 14,188,880 | 15.4% |
| LOAD_FAST | 12,114,960 | 13.2% |
| LOAD_ATTR | 8,370,540 | 9.1% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,660 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 75,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,020 | 96.1% |
| CALL | 2,940 | 3.9% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 151,525,780 | 48.5% |
| CACHE | 39,861,360 | 12.8% |
| POP_TOP | 37,113,120 | 11.9% |
| CALL_PY_WITH_DEFAULTS | 27,183,180 | 8.7% |
| CALL | 24,128,080 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 141,079,380 | 45.2% |
| LOAD_GLOBAL_BUILTIN | 72,249,100 | 23.1% |
| LOAD_GLOBAL_MODULE | 23,104,580 | 7.4% |
| LOAD_FAST_LOAD_FAST | 18,384,420 | 5.9% |
| RETURN_CONST | 16,878,540 | 5.4% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,225,440 | 64.7% |
| LOAD_FAST_LOAD_FAST | 25,987,780 | 27.9% |
| SWAP | 5,464,060 | 5.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,016,980 | 1.1% |
| RETURN_VALUE | 224,100 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,955,600 | 50.5% |
| NOP | 22,151,220 | 23.8% |
| LOAD_GLOBAL_BUILTIN | 8,305,400 | 8.9% |
| RETURN_CONST | 6,368,160 | 6.8% |
| LOAD_FAST_LOAD_FAST | 2,638,740 | 2.8% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,040 | 50.5% |
| LOAD_FAST | 10,800 | 49.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,800 | 49.5% |
| LOAD_FAST_LOAD_FAST | 7,320 | 33.5% |
| RETURN_CONST | 3,720 | 17.0% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,897,120 | 51.2% |
| LOAD_FAST | 3,490,340 | 45.8% |
| SWAP | 220,980 | 2.9% |
| LOAD_ATTR_INSTANCE_VALUE | 4,860 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,763,680 | 49.4% |
| LOAD_FAST | 3,702,180 | 48.6% |
| LOAD_GLOBAL_MODULE | 75,540 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 59,280 | 0.8% |
| BUILD_LIST | 4,980 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 16,701,540 | 40.1% |
| LOAD_FAST | 16,681,320 | 40.1% |
| BINARY_SUBSCR_TUPLE_INT | 3,815,040 | 9.2% |
| LOAD_CONST | 1,639,260 | 3.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,473,660 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,528,080 | 54.1% |
| ENTER_EXECUTOR | 12,682,560 | 30.5% |
| RETURN_CONST | 2,580,840 | 6.2% |
| JUMP_BACKWARD | 2,376,160 | 5.7% |
| LOAD_CONST | 898,800 | 2.2% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 318,240 | 54.0% |
| LOAD_FAST | 239,600 | 40.7% |
| LOAD_FAST_LOAD_FAST | 29,880 | 5.1% |
| ENTER_EXECUTOR | 1,440 | 0.2% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 246,660 | 41.9% |
| LOAD_FAST | 222,260 | 37.7% |
| STORE_FAST | 80,580 | 13.7% |
| RETURN_CONST | 37,260 | 6.3% |
| JUMP_FORWARD | 2,220 | 0.4% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,774,480 | 73.5% |
| BINARY_SUBSCR_DICT | 999,060 | 19.5% |
| CALL | 84,040 | 1.6% |
| RETURN_CONST | 65,720 | 1.3% |
| RETURN_VALUE | 65,400 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 3,642,620 | 71.0% |
| POP_JUMP_IF_FALSE | 1,267,460 | 24.7% |
| EXTENDED_ARG | 161,460 | 3.1% |
| TO_BOOL_NONE | 48,120 | 0.9% |
| TO_BOOL_ALWAYS_TRUE | 12,620 | 0.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 79,144,560 | 51.8% |
| CALL_BUILTIN_FAST | 29,563,620 | 19.4% |
| RETURN_VALUE | 20,056,160 | 13.1% |
| LOAD_FAST | 12,084,000 | 7.9% |
| LOAD_ATTR_WITH_HINT | 2,831,640 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 103,040,780 | 67.5% |
| POP_JUMP_IF_TRUE | 49,550,960 | 32.5% |
| EXTENDED_ARG | 41,700 | 0.0% |
| UNARY_NOT | 38,220 | 0.0% |
| TO_BOOL_INT | 980 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 12,835,620 | 76.9% |
| COPY | 1,252,980 | 7.5% |
| LOAD_FAST | 988,460 | 5.9% |
| LOAD_ATTR | 468,320 | 2.8% |
| CALL_LEN | 384,940 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 12,807,420 | 76.8% |
| POP_JUMP_IF_FALSE | 3,716,280 | 22.3% |
| EXTENDED_ARG | 154,740 | 0.9% |
| TO_BOOL_NONE | 3,580 | 0.0% |
| TO_BOOL_BOOL | 960 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,860,740 | 77.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,712,020 | 15.1% |
| RETURN_VALUE | 296,280 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 289,800 | 2.5% |
| BINARY_SUBSCR_DICT | 104,100 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,686,940 | 94.0% |
| POP_JUMP_IF_TRUE | 385,500 | 3.4% |
| EXTENDED_ARG | 279,480 | 2.5% |
| TO_BOOL | 19,960 | 0.2% |
| TO_BOOL_NONE | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 32,872,060 | 50.6% |
| LOAD_FAST | 16,765,660 | 25.8% |
| COPY | 6,329,640 | 9.7% |
| RETURN_CONST | 3,193,360 | 4.9% |
| LOAD_ATTR_PROPERTY | 3,114,180 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,005,720 | 67.8% |
| POP_JUMP_IF_TRUE | 20,694,980 | 31.9% |
| EXTENDED_ARG | 103,740 | 0.2% |
| TO_BOOL | 51,680 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 48,160 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,192,200 | 64.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,954,940 | 23.2% |
| COPY | 731,940 | 5.7% |
| LOAD_ATTR | 281,060 | 2.2% |
| STORE_FAST_LOAD_FAST | 280,260 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,523,580 | 51.1% |
| POP_JUMP_IF_FALSE | 6,131,500 | 48.1% |
| UNARY_NOT | 92,400 | 0.7% |
| TO_BOOL_NONE | 12,260 | 0.1% |
| EXTENDED_ARG | 360 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,080 | 86.2% |
| BINARY_SLICE | 2,940 | 10.5% |
| ENTER_EXECUTOR | 840 | 3.0% |
| RETURN_VALUE | 40 | 0.1% |
| UNPACK_SEQUENCE_TUPLE | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 27,860 | 99.7% |
| STORE_FAST | 60 | 0.2% |
| UNPACK_SEQUENCE_TUPLE | 20 | 0.1% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 4,903,800 | 58.8% |
| RETURN_VALUE | 3,378,940 | 40.5% |
| LOAD_FAST | 21,420 | 0.3% |
| FOR_ITER_TUPLE | 17,640 | 0.2% |
| BINARY_SLICE | 11,760 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 8,330,340 | 99.9% |
| STORE_FAST | 6,420 | 0.1% |
| STORE_NAME | 60 | 0.0% |
| UNPACK_SEQUENCE_LIST | 20 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 18,589,920 | 63.9% |
| RETURN_VALUE | 8,405,160 | 28.9% |
| FOR_ITER_LIST | 1,954,500 | 6.7% |
| BINARY_SUBSCR_LIST_INT | 51,180 | 0.2% |
| YIELD_VALUE | 48,900 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 28,362,800 | 97.4% |
| LOAD_FAST | 702,000 | 2.4% |
| STORE_FAST | 47,700 | 0.2% |


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
| specialization.deferred |      1160980 | 1.2% |
| specialization.deopt |        40780 | 0.0% |
|          hit |     93959620 | 96.6% |
|         miss |      2165900 | 2.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 41,380 | 83.9% |
| Failure | 7,960 | 16.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 7,780 | 97.7% |
| other | 180 | 2.3% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       839740 | 1.9% |
| specialization.deopt |           40 | 0.0% |
|          hit |     42562200 | 98.1% |
|         miss |         2220 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 6.0% |
| Failure | 2,520 | 94.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 2,260 | 89.7% |
| out of range | 220 | 8.7% |
| other | 40 | 1.6% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3680160 | 1.3% |
| specialization.deopt |       214320 | 0.1% |
|          hit |    271077160 | 94.7% |
|         miss |     11360780 | 4.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 215,200 | 56.4% |
| Failure | 166,500 | 43.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 121,160 | 72.8% |
| tuple | 41,540 | 24.9% |
| mapping | 2,240 | 1.3% |
| dict | 1,420 | 0.9% |
| other | 140 | 0.1% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     21046860 | 30.3% |
|          hit |     48411720 | 69.7% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 1.6% |
| Failure | 12,040 | 98.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 4,980 | 41.4% |
| add other | 3,220 | 26.7% |
| add different types | 3,160 | 26.2% |
| or | 320 | 2.7% |
| multiply different types | 180 | 1.5% |
| and int | 160 | 1.3% |
| true divide other | 20 | 0.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     61666980 | 9.4% |
| specialization.deopt |       326100 | 0.0% |
|          hit |    576981660 | 88.0% |
|         miss |     17297280 | 2.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 329,200 | 92.5% |
| Failure | 26,840 | 7.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,680 | 28.6% |
| meth descr method fastcall keywords | 5,480 | 20.4% |
| meth descr varargs | 3,020 | 11.3% |
| init not simple | 2,580 | 9.6% |
| meth descr varargs keywords | 1,740 | 6.5% |
| init not python | 1,140 | 4.2% |
| cfunc varargs keywords | 1,120 | 4.2% |
| class mutable | 1,040 | 3.9% |
| class no vectorcall | 900 | 3.4% |
| other | 700 | 2.6% |
| cmethod | 380 | 1.4% |
| bound method | 360 | 1.3% |
| wrong number arguments | 280 | 1.0% |
| cfunc noargs | 180 | 0.7% |
| cfunc varargs | 160 | 0.6% |
| operator wrapper | 40 | 0.1% |
| str | 40 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1680060 | 4.6% |
| specialization.deopt |         4900 | 0.0% |
|          hit |     34776960 | 94.7% |
|         miss |       259780 | 0.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,240 | 28.9% |
| Failure | 12,920 | 71.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 12,440 | 96.3% |
| list | 200 | 1.5% |
| big int | 100 | 0.8% |
| tuple | 80 | 0.6% |
| baseobject | 40 | 0.3% |
| other | 40 | 0.3% |
| long float | 20 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     45328860 | 26.1% |
| specialization.deopt |       496660 | 0.3% |
|          hit |    102058020 | 58.7% |
|         miss |     26323440 | 15.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 496,660 | 97.7% |
| Failure | 11,900 | 2.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 4,280 | 36.0% |
| dict values | 2,480 | 20.8% |
| dict items | 1,840 | 15.5% |
| ascii string | 1,600 | 13.4% |
| set | 780 | 6.6% |
| seq iter | 560 | 4.7% |
| dict keys | 220 | 1.8% |
| reversed list | 40 | 0.3% |
| zip | 40 | 0.3% |
| other | 40 | 0.3% |
| map | 20 | 0.2% |


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
| specialization.deferred |    148129680 | 13.5% |
| specialization.deopt |      5179780 | 0.5% |
|          hit |    674652060 | 61.5% |
|         miss |    274546840 | 25.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,186,180 | 98.0% |
| Failure | 105,540 | 2.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 49,740 | 47.1% |
| shadowed | 26,940 | 25.5% |
| metaclass attribute | 13,920 | 13.2% |
| method | 5,520 | 5.2% |
| non object slot | 2,880 | 2.7% |
| overridden | 2,840 | 2.7% |
| not managed dict | 2,520 | 2.4% |
| mutable class | 620 | 0.6% |
| class method obj | 300 | 0.3% |
| class attr descriptor | 200 | 0.2% |
| class attr simple | 40 | 0.0% |
| module attr not found | 20 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
| specialization.deopt |           40 | 0.0% |
|          hit |    319127500 | 100.0% |
|         miss |         1780 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,940 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |        79620 | 100.0% |


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
| specialization.deferred |     21953800 | 17.8% |
| specialization.deopt |      1017520 | 0.8% |
|          hit |     47146920 | 38.3% |
|         miss |     53924580 | 43.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,017,840 | 98.8% |
| Failure | 12,160 | 1.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 10,660 | 87.7% |
| not in dict | 940 | 7.7% |
| not in keys | 320 | 2.6% |
| property | 200 | 1.6% |
| overridden | 40 | 0.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |           40 | 0.0% |
|          hit |     48289620 | 100.0% |
|         miss |         2620 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 300 | 100.0% |
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
| Basic | 3,719,370,220 | 51.0% |
| Not specialized | 1,170,683,760 | 16.1% |
| Specialized | 2,398,854,980 | 32.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,007,740 | 100.0% |
| LOAD_ATTR | 148,129,680 | 0.0% |
| CALL | 61,666,980 | 0.0% |
| FOR_ITER | 45,328,860 | 0.0% |
| STORE_ATTR | 21,953,800 | 0.0% |
| BINARY_OP | 21,046,860 | 0.0% |
| TO_BOOL | 3,680,160 | 0.0% |
| COMPARE_OP | 1,680,060 | 0.0% |
| BINARY_SUBSCR | 1,160,980 | 0.0% |
| STORE_SUBSCR | 839,740 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 100,674,740 | 26.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 85,130,920 | 22.1% |
| STORE_ATTR_INSTANCE_VALUE | 53,921,400 | 14.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 47,106,480 | 12.2% |
| LOAD_ATTR_SLOT | 35,314,820 | 9.2% |
| FOR_ITER_TUPLE | 13,161,760 | 3.4% |
| FOR_ITER_LIST | 13,161,680 | 3.4% |
| CALL_PY_EXACT_ARGS | 9,155,140 | 2.4% |
| TO_BOOL_NONE | 6,134,120 | 1.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,506,460 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 40,121,100 | 11.3% |
| Calls to Python functions inlined | 314,282,760 | 88.7% |
| Calls via PyEval_EvalFrame (total) | 40,121,100 | 11.3% |
| Calls via PyEval_EvalFrame (vector) | 39,764,820 | 11.2% |
| Calls via PyEval_EvalFrame (generator) | 356,280 | 0.1% |
| Calls via PyEval_EvalFrame (legacy) | 3,420 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 39,761,340 | 11.2% |
| Calls via PyEval_EvalFrame (build class) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 13,645,460 | 3.9% |
| Calls via PyEval_EvalFrame (function ex) | 1,826,820 | 0.5% |
| Calls via PyEval_EvalFrame (api) | 8,643,440 | 2.4% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 313,332,820 | 88.4% |
| Frame objects created | 9,649,500 | 2.7% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 277,258,300 | 30.3% |
| Frees to freelist | 279,501,760 |  |
| Allocations | 636,935,640 | 69.7% |
| Allocations to 512 bytes | 636,104,720 | 69.6% |
| Allocations to 4 kbytes | 486,880 | 0.1% |
| Allocations over 4 kbytes | 344,040 | 0.0% |
| Frees | 672,561,328 |  |
| New values | 7,893,140 |  |
| Interpreter increfs | 3,153,078,520 | 57.3% |
| Interpreter decrefs | 3,823,450,280 | 61.5% |
| Increfs | 2,349,361,372 | 42.7% |
| Decrefs | 2,388,928,261 | 38.5% |
| Materialize dict (on request) | 28,580 | 0.4% |
| Materialize dict (new key) | 112,720 | 1.4% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 2,160 | 0.0% |
| Method cache hits | 445,781,416 |  |
| Method cache misses | 32,450,764 |  |
| Method cache collisions | 34,572,921 |  |
| Method cache dunder hits | 214,488,344 |  |
| Method cache dunder misses | 2,123,476 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 67,940 | 32,379,680 | 846,394,040 |
| 1 | 6,180 | 17,131,380 | 362,014,680 |
| 2 | 560 | 23,615,820 | 487,633,760 |


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
