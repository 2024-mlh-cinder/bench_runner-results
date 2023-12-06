
# Pystats results

- benchmark: docutils
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,943,425,480 | 19.9% | 19.9% |  |
| STORE_FAST | 446,478,040 | 4.6% | 24.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 438,303,220 | 4.5% | 29.0% | 30.6% |
| RESUME_CHECK | 417,395,180 | 4.3% | 33.3% | 0.0% |
| LOAD_CONST | 358,324,720 | 3.7% | 37.0% |  |
| LOAD_FAST_LOAD_FAST | 336,549,200 | 3.5% | 40.4% |  |
| POP_JUMP_IF_FALSE | 305,319,520 | 3.1% | 43.6% |  |
| LOAD_GLOBAL_BUILTIN | 275,290,360 | 2.8% | 46.4% | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 270,170,860 | 2.8% | 49.2% | 42.1% |
| CALL_PY_EXACT_ARGS | 252,500,600 | 2.6% | 51.7% | 4.8% |
| POP_TOP | 230,519,780 | 2.4% | 54.1% |  |
| RETURN_CONST | 215,960,440 | 2.2% | 56.3% |  |
| TO_BOOL_BOOL | 202,784,460 | 2.1% | 58.4% | 0.0% |
| LOAD_ATTR | 199,683,720 | 2.0% | 60.5% |  |
| RETURN_VALUE | 194,175,080 | 2.0% | 62.4% |  |
| ENTER_EXECUTOR | 189,987,940 | 1.9% | 64.4% |  |
| POP_JUMP_IF_TRUE | 171,669,460 | 1.8% | 66.2% |  |
| GET_ITER | 163,925,140 | 1.7% | 67.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 162,251,520 | 1.7% | 69.5% | 0.1% |
| NOP | 155,910,180 | 1.6% | 71.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 124,498,120 | 1.3% | 72.4% | 57.7% |
| LOAD_GLOBAL_MODULE | 124,231,700 | 1.3% | 73.7% | 0.0% |
| LOAD_ATTR_WITH_HINT | 114,244,800 | 1.2% | 74.8% | 1.2% |
| CALL_ISINSTANCE | 106,564,540 | 1.1% | 75.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 87,486,080 | 0.9% | 76.8% | 71.9% |
| TO_BOOL_NONE | 86,605,940 | 0.9% | 77.7% | 9.4% |
| CALL_BUILTIN_FAST | 85,978,600 | 0.9% | 78.6% | 0.0% |
| CALL | 82,558,840 | 0.8% | 79.4% |  |
| CONTAINS_OP | 80,286,800 | 0.8% | 80.3% |  |
| PUSH_NULL | 78,333,720 | 0.8% | 81.1% |  |
| FOR_ITER_LIST | 76,066,200 | 0.8% | 81.8% | 23.1% |
| BUILD_LIST | 65,742,400 | 0.7% | 82.5% |  |
| POP_JUMP_IF_NOT_NONE | 65,073,960 | 0.7% | 83.2% |  |
| FOR_ITER | 60,553,020 | 0.6% | 83.8% |  |
| LOAD_ATTR_SLOT | 59,016,420 | 0.6% | 84.4% | 79.8% |
| JUMP_BACKWARD | 56,056,960 | 0.6% | 85.0% |  |
| FOR_ITER_GEN | 55,604,980 | 0.6% | 85.6% |  |
| STORE_SUBSCR_DICT | 55,562,180 | 0.6% | 86.1% |  |
| CALL_LIST_APPEND | 55,382,660 | 0.6% | 86.7% | 0.1% |
| BINARY_SUBSCR_DICT | 54,649,240 | 0.6% | 87.3% |  |
| INTERPRETER_EXIT | 52,204,740 | 0.5% | 87.8% |  |
| STORE_FAST_STORE_FAST | 49,882,960 | 0.5% | 88.3% |  |
| RETURN_GENERATOR | 49,488,060 | 0.5% | 88.8% |  |
| END_FOR | 49,182,780 | 0.5% | 89.3% |  |
| BUILD_TUPLE | 47,213,520 | 0.5% | 89.8% |  |
| FORMAT_SIMPLE | 39,600,340 | 0.4% | 90.2% |  |
| CONVERT_VALUE | 39,573,220 | 0.4% | 90.6% |  |
| FOR_ITER_TUPLE | 39,104,480 | 0.4% | 91.0% | 44.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 38,960,660 | 0.4% | 91.4% |  |
| LOAD_ATTR_MODULE | 38,167,540 | 0.4% | 91.8% | 0.0% |
| CALL_LEN | 37,909,300 | 0.4% | 92.2% |  |
| CALL_PY_WITH_DEFAULTS | 36,328,360 | 0.4% | 92.6% | 0.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 29,442,560 | 0.3% | 92.9% | 0.0% |
| STORE_ATTR | 29,420,080 | 0.3% | 93.2% |  |
| BINARY_OP_ADD_INT | 29,401,460 | 0.3% | 93.5% |  |
| BINARY_OP | 28,336,320 | 0.3% | 93.8% |  |
| COMPARE_OP_INT | 27,627,120 | 0.3% | 94.0% | 0.1% |
| CALL_METHOD_DESCRIPTOR_O | 26,642,460 | 0.3% | 94.3% | 0.0% |
| BINARY_SLICE | 26,572,160 | 0.3% | 94.6% |  |
| BINARY_OP_ADD_UNICODE | 25,852,320 | 0.3% | 94.9% |  |
| BINARY_SUBSCR_LIST_INT | 25,263,960 | 0.3% | 95.1% | 11.4% |
| COPY | 24,731,900 | 0.3% | 95.4% |  |
| CALL_BUILTIN_O | 23,648,400 | 0.2% | 95.6% | 0.0% |
| TO_BOOL_INT | 22,470,600 | 0.2% | 95.8% | 1.5% |
| SWAP | 22,396,900 | 0.2% | 96.1% |  |
| BUILD_STRING | 20,148,700 | 0.2% | 96.3% |  |
| LOAD_ATTR_CLASS | 20,017,740 | 0.2% | 96.5% | 7.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 19,749,800 | 0.2% | 96.7% | 0.0% |
| BUILD_MAP | 19,440,460 | 0.2% | 96.9% |  |
| TO_BOOL_STR | 17,098,040 | 0.2% | 97.1% | 5.1% |
| CALL_FUNCTION_EX | 15,529,320 | 0.2% | 97.2% |  |
| TO_BOOL_LIST | 15,184,680 | 0.2% | 97.4% | 9.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 13,442,040 | 0.1% | 97.5% | 44.8% |
| COMPARE_OP_STR | 11,896,360 | 0.1% | 97.6% | 2.7% |
| BINARY_SUBSCR_TUPLE_INT | 11,495,760 | 0.1% | 97.8% |  |
| BINARY_SUBSCR_GETITEM | 11,180,940 | 0.1% | 97.9% | 0.2% |
| UNPACK_SEQUENCE_TUPLE | 11,129,660 | 0.1% | 98.0% | 0.0% |
| POP_JUMP_IF_NONE | 10,505,300 | 0.1% | 98.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 10,375,140 | 0.1% | 98.2% | 22.6% |
| STORE_ATTR_WITH_HINT | 10,150,520 | 0.1% | 98.3% | 0.0% |
| CALL_STR_1 | 9,530,480 | 0.1% | 98.4% |  |
| JUMP_FORWARD | 8,641,800 | 0.1% | 98.5% |  |
| POP_EXCEPT | 8,194,060 | 0.1% | 98.6% |  |
| PUSH_EXC_INFO | 8,194,060 | 0.1% | 98.7% |  |
| LOAD_ATTR_PROPERTY | 7,881,720 | 0.1% | 98.7% | 68.4% |
| CALL_BUILTIN_CLASS | 7,749,420 | 0.1% | 98.8% | 0.1% |
| CHECK_EXC_MATCH | 7,719,060 | 0.1% | 98.9% |  |
| LIST_APPEND | 7,628,440 | 0.1% | 99.0% |  |
| BINARY_OP_SUBTRACT_INT | 6,987,980 | 0.1% | 99.0% |  |
| TO_BOOL_ALWAYS_TRUE | 6,846,140 | 0.1% | 99.1% | 62.7% |
| BINARY_SUBSCR_STR_INT | 6,740,820 | 0.1% | 99.2% | 2.6% |
| YIELD_VALUE | 6,601,200 | 0.1% | 99.3% |  |
| CALL_KW | 6,224,220 | 0.1% | 99.3% |  |
| CALL_TYPE_1 | 5,605,880 | 0.1% | 99.4% |  |
| TO_BOOL | 5,395,960 | 0.1% | 99.4% |  |
| STORE_SLICE | 5,304,660 | 0.1% | 99.5% |  |
| DICT_MERGE | 4,518,800 | 0.0% | 99.5% |  |
| LIST_EXTEND | 3,650,620 | 0.0% | 99.6% |  |
| CALL_INTRINSIC_1 | 3,645,760 | 0.0% | 99.6% |  |
| CALL_ALLOC_AND_ENTER_INIT | 3,610,100 | 0.0% | 99.6% | 63.1% |
| LOAD_FAST_AND_CLEAR | 3,320,580 | 0.0% | 99.7% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,976,480 | 0.0% | 99.7% | 0.1% |
| EXTENDED_ARG | 2,801,180 | 0.0% | 99.7% |  |
| DELETE_SUBSCR | 2,516,980 | 0.0% | 99.8% |  |
| BUILD_CONST_KEY_MAP | 2,511,060 | 0.0% | 99.8% |  |
| COMPARE_OP | 2,331,160 | 0.0% | 99.8% |  |
| RERAISE | 1,886,500 | 0.0% | 99.8% |  |
| BINARY_SUBSCR | 1,641,400 | 0.0% | 99.8% |  |
| RAISE_VARARGS | 1,567,760 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 1,503,520 | 0.0% | 99.9% |  |
| EXIT_INIT_CHECK | 1,333,120 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 1,255,000 | 0.0% | 99.9% |  |
| LOAD_DEREF | 1,240,440 | 0.0% | 99.9% |  |
| IS_OP | 1,136,460 | 0.0% | 99.9% |  |
| COPY_FREE_VARS | 1,118,920 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 1,064,480 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 1,013,580 | 0.0% | 100.0% | 0.3% |
| BUILD_SLICE | 604,140 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 575,240 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 493,420 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 319,440 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 311,340 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 237,620 | 0.0% | 100.0% |  |
| MAKE_CELL | 213,780 | 0.0% | 100.0% |  |
| UNARY_NOT | 185,840 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 113,720 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 108,300 | 0.0% | 100.0% |  |
| MAP_ADD | 97,000 | 0.0% | 100.0% |  |
| STORE_NAME | 96,580 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 63,200 | 0.0% | 100.0% |  |
| LOAD_NAME | 50,720 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 38,040 | 0.0% | 100.0% | 5.5% |
| STORE_ATTR_SLOT | 35,800 | 0.0% | 100.0% |  |
| RESUME | 33,480 | 0.0% | 100.0% | 97.2% |
| IMPORT_NAME | 26,500 | 0.0% | 100.0% |  |
| BEFORE_WITH | 25,160 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 16,660 | 0.0% | 100.0% |  |
| STORE_DEREF | 15,960 | 0.0% | 100.0% |  |
| IMPORT_FROM | 14,140 | 0.0% | 100.0% |  |
| UNARY_INVERT | 12,280 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 9,680 | 0.0% | 100.0% | 3.7% |
| UNPACK_SEQUENCE | 7,320 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 6,960 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 5,340 | 0.0% | 100.0% |  |
| DELETE_ATTR | 4,480 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 3,900 | 0.0% | 100.0% | 1.5% |
| BINARY_OP_SUBTRACT_FLOAT | 3,900 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 2,460 | 0.0% | 100.0% | 8.9% |
| DICT_UPDATE | 1,660 | 0.0% | 100.0% |  |
| DELETE_FAST | 1,040 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 580 | 0.0% | 100.0% |  |
| BUILD_SET | 340 | 0.0% | 100.0% |  |
| LOAD_LOCALS | 240 | 0.0% | 100.0% |  |
| LOAD_FROM_DICT_OR_DEREF | 240 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 220 | 0.0% | 100.0% |  |
| DELETE_NAME | 200 | 0.0% | 100.0% |  |
| SEND | 140 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 120 | 0.0% | 100.0% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 80 | 0.0% | 100.0% |  |
| SET_UPDATE | 80 | 0.0% | 100.0% |  |
| END_SEND | 40 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 331,424,420 | 3.4% | 3.4% |
| STORE_FAST LOAD_FAST | 211,428,560 | 2.2% | 5.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 201,647,560 | 2.1% | 7.6% |
| RESUME_CHECK LOAD_FAST | 189,050,900 | 1.9% | 9.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 163,837,100 | 1.7% | 11.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 163,275,600 | 1.7% | 12.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 160,853,240 | 1.7% | 14.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 157,479,720 | 1.6% | 16.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 150,632,580 | 1.5% | 17.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 136,965,520 | 1.4% | 19.1% |
| LOAD_FAST LOAD_ATTR | 119,624,980 | 1.2% | 20.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 116,924,200 | 1.2% | 21.6% |
| RETURN_CONST POP_TOP | 112,327,160 | 1.2% | 22.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 105,100,900 | 1.1% | 23.8% |
| LOAD_FAST LOAD_CONST | 102,205,200 | 1.0% | 24.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 98,308,760 | 1.0% | 25.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 96,164,580 | 1.0% | 26.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 94,302,720 | 1.0% | 27.8% |
| NOP LOAD_FAST | 91,645,720 | 0.9% | 28.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 90,366,980 | 0.9% | 29.7% |
| LOAD_CONST LOAD_FAST | 86,793,820 | 0.9% | 30.6% |
| POP_TOP LOAD_FAST | 84,639,700 | 0.9% | 31.4% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 84,596,460 | 0.9% | 32.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 80,527,040 | 0.8% | 33.1% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 70,542,600 | 0.7% | 33.9% |
| GET_ITER FOR_ITER_LIST | 65,907,700 | 0.7% | 34.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 65,616,480 | 0.7% | 35.2% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 62,701,920 | 0.6% | 35.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 62,672,820 | 0.6% | 36.5% |
| PUSH_NULL LOAD_FAST | 61,725,140 | 0.6% | 37.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 61,054,960 | 0.6% | 37.8% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 58,716,020 | 0.6% | 38.4% |
| LOAD_FAST LOAD_ATTR_SLOT | 58,101,700 | 0.6% | 39.0% |
| LOAD_FAST_LOAD_FAST CALL_ISINSTANCE | 57,800,240 | 0.6% | 39.5% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 57,789,220 | 0.6% | 40.1% |
| LOAD_ATTR_SLOT LOAD_ATTR | 56,475,280 | 0.6% | 40.7% |
| CACHE RESUME_CHECK | 53,300,420 | 0.5% | 41.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 52,169,000 | 0.5% | 41.8% |
| ENTER_EXECUTOR LOAD_ATTR_INSTANCE_VALUE | 50,826,340 | 0.5% | 42.3% |
| JUMP_BACKWARD FOR_ITER | 49,536,000 | 0.5% | 42.8% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 49,519,600 | 0.5% | 43.3% |
| POP_TOP RESUME_CHECK | 49,487,700 | 0.5% | 43.8% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 49,284,560 | 0.5% | 44.4% |
| FOR_ITER_GEN POP_TOP | 49,223,460 | 0.5% | 44.9% |
| RETURN_GENERATOR GET_ITER | 49,223,300 | 0.5% | 45.4% |
| GET_ITER FOR_ITER_GEN | 49,218,400 | 0.5% | 45.9% |
| RETURN_CONST END_FOR | 49,182,780 | 0.5% | 46.4% |
| FOR_ITER_LIST STORE_FAST | 49,023,300 | 0.5% | 46.9% |
| END_FOR ENTER_EXECUTOR | 48,917,160 | 0.5% | 47.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 48,678,900 | 0.5% | 47.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 46,362,580 | 0.5% | 48.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_NONE | 43,824,240 | 0.4% | 48.8% |
| LOAD_FAST BINARY_SUBSCR_DICT | 43,307,600 | 0.4% | 49.2% |
| LOAD_ATTR STORE_FAST | 42,941,680 | 0.4% | 49.7% |
| CALL_BUILTIN_FAST STORE_FAST | 42,839,980 | 0.4% | 50.1% |
| BUILD_TUPLE RETURN_VALUE | 42,313,200 | 0.4% | 50.6% |
| STORE_FAST NOP | 41,322,460 | 0.4% | 51.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 41,282,400 | 0.4% | 51.4% |
| LOAD_CONST CALL_BUILTIN_FAST | 39,793,520 | 0.4% | 51.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 39,705,740 | 0.4% | 52.2% |
| CONVERT_VALUE FORMAT_SIMPLE | 39,573,220 | 0.4% | 52.6% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 39,458,080 | 0.4% | 53.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_CONST | 39,446,720 | 0.4% | 53.4% |
| LOAD_FAST CALL_LIST_APPEND | 39,309,140 | 0.4% | 53.8% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 39,294,120 | 0.4% | 54.2% |
| LOAD_ATTR_WITH_HINT LOAD_FAST | 38,994,880 | 0.4% | 54.6% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 38,380,780 | 0.4% | 55.0% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 38,031,000 | 0.4% | 55.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 38,003,720 | 0.4% | 55.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 37,928,460 | 0.4% | 56.2% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 36,765,440 | 0.4% | 56.6% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 36,275,040 | 0.4% | 57.0% |
| ENTER_EXECUTOR RETURN_CONST | 35,604,480 | 0.4% | 57.3% |
| GET_ITER FOR_ITER_TUPLE | 35,184,960 | 0.4% | 57.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 34,860,640 | 0.4% | 58.0% |
| LOAD_CONST LOAD_CONST | 33,954,940 | 0.3% | 58.4% |
| LOAD_ATTR LOAD_FAST | 33,337,300 | 0.3% | 58.7% |
| LOAD_CONST STORE_FAST | 32,763,700 | 0.3% | 59.1% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 32,629,360 | 0.3% | 59.4% |
| CALL RESUME_CHECK | 32,211,220 | 0.3% | 59.7% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 31,861,460 | 0.3% | 60.1% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 31,620,540 | 0.3% | 60.4% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_WITH_VALUES | 30,945,200 | 0.3% | 60.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 30,911,920 | 0.3% | 61.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_FAST | 30,448,840 | 0.3% | 61.3% |
| CALL STORE_FAST | 30,314,320 | 0.3% | 61.6% |
| STORE_SUBSCR_DICT LOAD_FAST | 30,105,760 | 0.3% | 62.0% |
| LOAD_FAST BUILD_TUPLE | 29,725,780 | 0.3% | 62.3% |
| STORE_ATTR_INSTANCE_VALUE NOP | 29,542,380 | 0.3% | 62.6% |
| LOAD_FAST PUSH_NULL | 29,385,800 | 0.3% | 62.9% |
| RETURN_VALUE STORE_FAST | 29,303,660 | 0.3% | 63.2% |
| NOP LOAD_GLOBAL_BUILTIN | 28,858,920 | 0.3% | 63.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 28,313,380 | 0.3% | 63.7% |
| LOAD_FAST RETURN_VALUE | 28,278,300 | 0.3% | 64.0% |
| BINARY_SUBSCR_DICT STORE_FAST | 28,161,820 | 0.3% | 64.3% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 27,900,580 | 0.3% | 64.6% |
| TO_BOOL_NONE POP_JUMP_IF_TRUE | 27,598,740 | 0.3% | 64.9% |
| POP_JUMP_IF_TRUE NOP | 27,522,660 | 0.3% | 65.2% |
| LOAD_FAST CALL_PY_WITH_DEFAULTS | 27,198,840 | 0.3% | 65.5% |
| FOR_ITER STORE_FAST | 27,142,440 | 0.3% | 65.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,102,800 | 60.6% |
| BINARY_OP_ADD_INT | 3,819,560 | 14.4% |
| LOAD_ATTR | 2,737,700 | 10.3% |
| LOAD_FAST | 2,658,420 | 10.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 635,760 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,725,460 | 40.4% |
| RETURN_VALUE | 4,007,920 | 15.1% |
| LOAD_FAST | 3,436,440 | 12.9% |
| LOAD_CONST | 1,542,440 | 5.8% |
| LOAD_FAST_LOAD_FAST | 1,500,120 | 5.6% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,948,320 | 93.3% |
| LOAD_FAST_LOAD_FAST | 344,480 | 6.5% |
| LOAD_ATTR | 10,720 | 0.2% |
| BINARY_OP_ADD_INT | 1,120 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,941,680 | 93.2% |
| RETURN_CONST | 357,840 | 6.7% |
| LOAD_GLOBAL_BUILTIN | 3,560 | 0.1% |
| LOAD_CONST | 720 | 0.0% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 53,300,420 | 99.4% |
| POP_TOP | 264,600 | 0.5% |
| COPY_FREE_VARS | 27,600 | 0.1% |
| RESUME | 15,000 | 0.0% |
| MAKE_CELL | 800 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 10,640 | 42.3% |
| RETURN_VALUE | 9,360 | 37.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,640 | 14.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,440 | 5.7% |
| LOAD_GLOBAL | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 17,860 | 71.0% |
| STORE_FAST | 7,300 | 29.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 533,260 | 50.1% |
| LOAD_FAST_LOAD_FAST | 218,200 | 20.5% |
| RETURN_VALUE | 180,800 | 17.0% |
| CALL_FUNCTION_EX | 80,440 | 7.6% |
| BINARY_OP_ADD_UNICODE | 23,640 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 935,460 | 87.9% |
| LOAD_CONST | 80,460 | 7.6% |
| JUMP_BACKWARD | 20,040 | 1.9% |
| LOAD_GLOBAL_MODULE | 11,720 | 1.1% |
| ENTER_EXECUTOR | 11,640 | 1.1% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,135,500 | 69.2% |
| LOAD_FAST | 185,100 | 11.3% |
| COPY | 184,140 | 11.2% |
| COMPARE_OP_STR | 101,880 | 6.2% |
| BUILD_SLICE | 12,480 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 894,120 | 54.5% |
| LOAD_CONST | 235,140 | 14.3% |
| BUILD_TUPLE | 135,200 | 8.2% |
| LOAD_ATTR_METHOD_NO_DICT | 126,400 | 7.7% |
| STORE_FAST | 106,900 | 6.5% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,746,140 | 87.4% |
| LOAD_GLOBAL_MODULE | 508,700 | 6.6% |
| BUILD_TUPLE | 434,160 | 5.6% |
| LOAD_ATTR_MODULE | 29,220 | 0.4% |
| LOAD_GLOBAL | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,719,060 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,322,400 | 52.5% |
| BUILD_SLICE | 591,660 | 23.5% |
| LOAD_CONST | 310,800 | 12.3% |
| LOAD_FAST | 292,100 | 11.6% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,308,940 | 52.0% |
| LOAD_FAST | 508,560 | 20.2% |
| RETURN_CONST | 411,720 | 16.4% |
| LOAD_FAST_LOAD_FAST | 277,520 | 11.0% |
| LOAD_CONST | 3,920 | 0.2% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 49,182,780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 48,917,160 | 99.5% |
| JUMP_BACKWARD | 131,100 | 0.3% |
| RETURN_CONST | 123,340 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 5,480 | 0.0% |
| LOAD_FAST | 4,200 | 0.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 40 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,333,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,333,120 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 39,573,220 | 99.9% |
| LOAD_FAST | 25,920 | 0.1% |
| LOAD_ATTR_MODULE | 500 | 0.0% |
| LOAD_ATTR | 480 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 21,315,900 | 53.8% |
| BUILD_STRING | 15,461,680 | 39.0% |
| LOAD_FAST | 2,810,880 | 7.1% |
| LOAD_GLOBAL_MODULE | 11,640 | 0.0% |
| LOAD_GLOBAL | 120 | 0.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 49,223,300 | 30.0% |
| LOAD_ATTR_INSTANCE_VALUE | 38,031,000 | 23.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 25,695,580 | 15.7% |
| LOAD_FAST | 21,922,820 | 13.4% |
| BINARY_SLICE | 10,725,460 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 65,907,700 | 40.2% |
| FOR_ITER_GEN | 49,218,400 | 30.0% |
| FOR_ITER_TUPLE | 35,184,960 | 21.5% |
| FOR_ITER | 9,848,140 | 6.0% |
| LOAD_FAST_AND_CLEAR | 2,976,260 | 1.8% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 26,798,180 | 51.3% |
| RETURN_CONST | 25,227,560 | 48.3% |
| YIELD_VALUE | 179,000 | 0.3% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 6,060 | 87.1% |
| POP_TOP | 520 | 7.5% |
| RETURN_VALUE | 120 | 1.7% |
| LOAD_NAME | 60 | 0.9% |
| STORE_GLOBAL | 60 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,960 | 100.0% |


</details>

### LOAD_LOCALS

<details>
<summary> Successors and predecessors for LOAD_LOCALS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FROM_DICT_OR_DEREF | 240 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 493,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 318,640 | 64.6% |
| LOAD_FAST | 137,700 | 27.9% |
| STORE_NAME | 27,320 | 5.5% |
| LOAD_CONST | 7,060 | 1.4% |
| CALL | 1,420 | 0.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 41,322,460 | 26.5% |
| STORE_ATTR_INSTANCE_VALUE | 29,542,380 | 18.9% |
| POP_JUMP_IF_TRUE | 27,522,660 | 17.7% |
| RESUME_CHECK | 19,356,300 | 12.4% |
| NOP | 16,575,000 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 91,645,720 | 58.8% |
| LOAD_GLOBAL_BUILTIN | 28,858,920 | 18.5% |
| NOP | 16,575,000 | 10.6% |
| LOAD_FAST_LOAD_FAST | 7,139,840 | 4.6% |
| BUILD_LIST | 4,647,360 | 3.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,539,880 | 67.6% |
| COPY | 1,230,260 | 15.0% |
| SWAP | 1,214,780 | 14.8% |
| STORE_FAST | 189,340 | 2.3% |
| CALL_LIST_APPEND | 15,960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,827,940 | 58.9% |
| RERAISE | 1,230,260 | 15.0% |
| RETURN_VALUE | 1,214,780 | 14.8% |
| EXTENDED_ARG | 799,780 | 9.8% |
| ENTER_EXECUTOR | 94,780 | 1.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 112,327,160 | 48.7% |
| FOR_ITER_GEN | 49,223,460 | 21.4% |
| RETURN_VALUE | 20,439,680 | 8.9% |
| POP_JUMP_IF_FALSE | 9,474,460 | 4.1% |
| CALL | 7,376,580 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,639,700 | 36.7% |
| RESUME_CHECK | 49,487,700 | 21.5% |
| JUMP_BACKWARD | 19,531,160 | 8.5% |
| RETURN_CONST | 18,983,000 | 8.2% |
| ENTER_EXECUTOR | 17,758,420 | 7.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,325,220 | 52.8% |
| RERAISE | 1,230,080 | 15.0% |
| BINARY_SUBSCR_LIST_INT | 1,086,160 | 13.3% |
| RAISE_VARARGS | 1,004,800 | 12.3% |
| CALL | 305,420 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,757,680 | 82.5% |
| LOAD_GLOBAL_MODULE | 930,760 | 11.4% |
| LOAD_FAST | 503,960 | 6.2% |
| LOAD_GLOBAL | 1,360 | 0.0% |
| LOAD_NAME | 140 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,385,800 | 37.5% |
| LOAD_ATTR_MODULE | 26,100,720 | 33.3% |
| LOAD_ATTR | 11,221,020 | 14.3% |
| LOAD_ATTR_CLASS | 11,043,540 | 14.1% |
| LOAD_ATTR_INSTANCE_VALUE | 386,600 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,725,140 | 78.8% |
| LOAD_FAST_LOAD_FAST | 12,888,920 | 16.5% |
| LOAD_CONST | 2,202,920 | 2.8% |
| CALL_PY_EXACT_ARGS | 871,160 | 1.1% |
| CALL | 383,520 | 0.5% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 49,284,560 | 99.6% |
| CALL_KW | 158,080 | 0.3% |
| CALL_PY_WITH_DEFAULTS | 41,060 | 0.1% |
| COPY_FREE_VARS | 3,580 | 0.0% |
| CALL | 700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 49,223,300 | 99.5% |
| CALL_METHOD_DESCRIPTOR_O | 134,180 | 0.3% |
| CALL_BUILTIN_FAST | 114,920 | 0.2% |
| CALL_BUILTIN_CLASS | 3,880 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,880 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 42,313,200 | 21.8% |
| LOAD_FAST | 28,278,300 | 14.6% |
| RETURN_CONST | 19,819,520 | 10.2% |
| BINARY_SUBSCR_LIST_INT | 15,335,580 | 7.9% |
| BINARY_SUBSCR_DICT | 10,627,920 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,303,660 | 15.1% |
| INTERPRETER_EXIT | 26,798,180 | 13.8% |
| TO_BOOL_BOOL | 26,436,840 | 13.6% |
| LOAD_FAST_LOAD_FAST | 22,323,200 | 11.5% |
| POP_TOP | 20,439,680 | 10.5% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 961,960 | 64.0% |
| ENTER_EXECUTOR | 195,120 | 13.0% |
| SWAP | 195,040 | 13.0% |
| BINARY_OP | 92,220 | 6.1% |
| LOAD_FAST_LOAD_FAST | 26,140 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 583,840 | 38.8% |
| LOAD_CONST | 305,280 | 20.3% |
| ENTER_EXECUTOR | 266,000 | 17.7% |
| JUMP_FORWARD | 255,460 | 17.0% |
| BUILD_LIST | 26,480 | 1.8% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,299,240 | 42.6% |
| COPY | 1,558,540 | 28.9% |
| LOAD_ATTR_INSTANCE_VALUE | 678,880 | 12.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 244,720 | 4.5% |
| ENTER_EXECUTOR | 203,380 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,402,680 | 63.1% |
| POP_JUMP_IF_TRUE | 1,746,560 | 32.4% |
| TO_BOOL | 134,280 | 2.5% |
| TO_BOOL_NONE | 71,280 | 1.3% |
| TO_BOOL_LIST | 28,060 | 0.5% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,040 | 65.5% |
| LOAD_FAST | 4,240 | 34.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 12,160 | 99.0% |
| LOAD_CONST | 80 | 0.7% |
| LOAD_FAST | 40 | 0.3% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 237,620 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 235,840 | 99.3% |
| CALL_BUILTIN_CLASS | 1,780 | 0.7% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 123,300 | 66.3% |
| TO_BOOL_BOOL | 50,940 | 27.4% |
| TO_BOOL_INT | 9,480 | 5.1% |
| TO_BOOL_LIST | 2,040 | 1.1% |
| TO_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 116,760 | 62.8% |
| RETURN_VALUE | 57,840 | 31.1% |
| COPY | 7,760 | 4.2% |
| CALL_PY_EXACT_ARGS | 2,040 | 1.1% |
| BUILD_TUPLE | 1,440 | 0.8% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 120 | 100.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,391,920 | 96.8% |
| CALL_METHOD_DESCRIPTOR_O | 116,740 | 1.8% |
| BUILD_TUPLE | 66,200 | 1.0% |
| LOAD_ATTR_INSTANCE_VALUE | 12,460 | 0.2% |
| RETURN_VALUE | 6,320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,355,840 | 96.3% |
| INTERPRETER_EXIT | 179,000 | 2.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 65,160 | 1.0% |
| STORE_FAST_LOAD_FAST | 1,180 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 15,442,180 | 54.5% |
| LOAD_FAST | 3,666,560 | 12.9% |
| RETURN_VALUE | 3,001,660 | 10.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,681,260 | 9.5% |
| LOAD_FAST_LOAD_FAST | 1,520,020 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 15,483,400 | 54.6% |
| STORE_FAST | 5,816,560 | 20.5% |
| GET_ITER | 3,229,100 | 11.4% |
| SWAP | 1,728,000 | 6.1% |
| LOAD_FAST | 840,260 | 3.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,511,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,428,880 | 96.7% |
| STORE_FAST | 64,000 | 2.5% |
| LOAD_CONST | 14,340 | 0.6% |
| RETURN_VALUE | 1,440 | 0.1% |
| STORE_NAME | 1,100 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,202,100 | 27.7% |
| LOAD_CONST | 13,368,580 | 20.3% |
| RESUME_CHECK | 9,305,780 | 14.2% |
| LOAD_FAST | 7,127,420 | 10.8% |
| NOP | 4,647,360 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,032,540 | 32.0% |
| STORE_FAST | 20,448,780 | 31.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,848,180 | 8.9% |
| CALL_PY_EXACT_ARGS | 5,385,360 | 8.2% |
| BUILD_TUPLE | 3,691,540 | 5.6% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,461,960 | 38.4% |
| POP_TOP | 3,240,980 | 16.7% |
| NOP | 2,586,360 | 13.3% |
| CALL_INTRINSIC_1 | 2,466,320 | 12.7% |
| LOAD_CONST | 1,089,040 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,380,140 | 53.4% |
| STORE_FAST | 8,387,780 | 43.1% |
| CALL_BUILTIN_FAST | 482,420 | 2.5% |
| BUILD_TUPLE | 88,640 | 0.5% |
| CALL_FUNCTION_EX | 82,400 | 0.4% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 180 | 52.9% |
| LOAD_CONST | 80 | 23.5% |
| STORE_NAME | 80 | 23.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 180 | 52.9% |
| BINARY_OP | 60 | 17.6% |
| LOAD_CONST | 60 | 17.6% |
| EXTENDED_ARG | 20 | 5.9% |
| STORE_NAME | 20 | 5.9% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 351,200 | 58.1% |
| LOAD_CONST | 252,940 | 41.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 591,660 | 97.9% |
| BINARY_SUBSCR | 12,480 | 2.1% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 15,461,680 | 76.7% |
| LOAD_CONST | 4,687,020 | 23.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 15,441,580 | 76.6% |
| BINARY_OP_ADD_UNICODE | 2,681,240 | 13.3% |
| CALL_LIST_APPEND | 1,864,080 | 9.3% |
| STORE_FAST | 155,220 | 0.8% |
| LIST_APPEND | 4,880 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,725,780 | 63.0% |
| LOAD_FAST_LOAD_FAST | 9,963,840 | 21.1% |
| BUILD_LIST | 3,691,540 | 7.8% |
| LOAD_CONST | 1,284,360 | 2.7% |
| LOAD_ATTR_MODULE | 946,920 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 42,313,200 | 89.6% |
| CALL_ISINSTANCE | 1,005,880 | 2.1% |
| BUILD_MAP | 872,700 | 1.8% |
| BINARY_SUBSCR_DICT | 762,800 | 1.6% |
| SWAP | 454,960 | 1.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 18,986,960 | 23.0% |
| LOAD_FAST | 15,745,420 | 19.1% |
| BINARY_OP | 15,483,400 | 18.8% |
| BUILD_STRING | 15,441,580 | 18.7% |
| LOAD_CONST | 4,064,880 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 32,211,220 | 39.0% |
| STORE_FAST | 30,314,320 | 36.7% |
| POP_TOP | 7,376,580 | 8.9% |
| RETURN_VALUE | 3,077,160 | 3.7% |
| CALL_PY_EXACT_ARGS | 1,989,560 | 2.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,700,520 | 62.5% |
| DICT_MERGE | 4,518,800 | 29.1% |
| CALL_INTRINSIC_1 | 1,065,420 | 6.9% |
| ENTER_EXECUTOR | 158,260 | 1.0% |
| BUILD_MAP | 82,400 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,093,200 | 32.8% |
| POP_TOP | 4,631,240 | 29.8% |
| RESUME_CHECK | 2,438,440 | 15.7% |
| STORE_FAST | 2,392,560 | 15.4% |
| CALL_LIST_APPEND | 604,480 | 3.9% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 3,645,740 | 100.0% |
| IMPORT_NAME | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 2,466,320 | 67.6% |
| CALL_FUNCTION_EX | 1,065,420 | 29.2% |
| LOAD_CONST | 82,400 | 2.3% |
| LOAD_FAST | 27,680 | 0.8% |
| LOAD_GLOBAL_MODULE | 3,880 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,124,440 | 98.4% |
| ENTER_EXECUTOR | 99,780 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,146,160 | 66.6% |
| RETURN_VALUE | 1,347,980 | 21.7% |
| STORE_FAST | 527,020 | 8.5% |
| RETURN_GENERATOR | 158,080 | 2.5% |
| LOAD_FAST | 23,540 | 0.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,397,420 | 59.9% |
| BUILD_LIST | 695,800 | 29.8% |
| LOAD_FAST_LOAD_FAST | 147,640 | 6.3% |
| LOAD_GLOBAL_MODULE | 43,560 | 1.9% |
| LOAD_ATTR_INSTANCE_VALUE | 16,500 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,562,840 | 67.0% |
| POP_JUMP_IF_TRUE | 741,800 | 31.8% |
| COMPARE_OP | 13,580 | 0.6% |
| COMPARE_OP_STR | 8,360 | 0.4% |
| COMPARE_OP_INT | 4,080 | 0.2% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 32,629,360 | 40.6% |
| LOAD_FAST_LOAD_FAST | 31,620,540 | 39.4% |
| LOAD_CONST | 4,907,200 | 6.1% |
| LOAD_FAST | 4,029,700 | 5.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,972,580 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 39,294,120 | 48.9% |
| POP_JUMP_IF_TRUE | 38,380,780 | 47.8% |
| RETURN_VALUE | 2,200,480 | 2.7% |
| COPY | 372,400 | 0.5% |
| EXTENDED_ARG | 37,320 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,186,140 | 46.0% |
| LOAD_ATTR | 15,440,980 | 39.0% |
| CALL_METHOD_DESCRIPTOR_O | 2,681,260 | 6.8% |
| RETURN_VALUE | 1,888,760 | 4.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,138,100 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 39,573,220 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,793,220 | 39.6% |
| LOAD_ATTR | 9,292,840 | 37.6% |
| BINARY_SUBSCR_DICT | 1,203,860 | 4.9% |
| RERAISE | 656,240 | 2.7% |
| COPY | 587,540 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 8,442,300 | 34.1% |
| LOAD_ATTR_INSTANCE_VALUE | 7,271,640 | 29.4% |
| TO_BOOL_INT | 1,677,180 | 6.8% |
| TO_BOOL | 1,558,540 | 6.3% |
| POP_EXCEPT | 1,230,260 | 5.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,088,340 | 97.3% |
| CACHE | 27,600 | 2.5% |
| CALL | 1,760 | 0.2% |
| ENTER_EXECUTOR | 660 | 0.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,114,980 | 99.6% |
| RETURN_GENERATOR | 3,580 | 0.3% |
| RESUME | 360 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,480 | 100.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 880 | 84.6% |
| JUMP_BACKWARD | 80 | 7.7% |
| RERAISE | 80 | 7.7% |


</details>

### DELETE_NAME

<details>
<summary> Successors and predecessors for DELETE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 100 | 50.0% |
| STORE_NAME | 40 | 20.0% |
| FOR_ITER | 20 | 10.0% |
| JUMP_FORWARD | 20 | 10.0% |
| FOR_ITER_TUPLE | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 100 | 50.0% |
| LOAD_BUILD_CLASS | 20 | 10.0% |
| BUILD_LIST | 20 | 10.0% |
| LOAD_CONST | 20 | 10.0% |
| RERAISE | 20 | 10.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,386,040 | 97.1% |
| LOAD_ATTR_INSTANCE_VALUE | 131,780 | 2.9% |
| CALL | 520 | 0.0% |
| RETURN_VALUE | 320 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 4,518,800 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 1,440 | 86.7% |
| BUILD_CONST_KEY_MAP | 220 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 1,300 | 78.3% |
| STORE_NAME | 220 | 13.3% |
| LOAD_CONST | 100 | 6.0% |
| COPY | 20 | 1.2% |
| EXTENDED_ARG | 20 | 1.2% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 57,789,220 | 30.4% |
| END_FOR | 48,917,160 | 25.7% |
| CALL_LIST_APPEND | 31,861,460 | 16.8% |
| POP_TOP | 17,758,420 | 9.3% |
| STORE_SUBSCR_DICT | 16,905,500 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 50,826,340 | 26.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 49,519,600 | 26.1% |
| RETURN_CONST | 35,604,480 | 18.7% |
| LOAD_FAST | 17,143,980 | 9.0% |
| LOAD_FAST_LOAD_FAST | 8,703,080 | 4.6% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 799,780 | 28.6% |
| TO_BOOL_LIST | 372,920 | 13.3% |
| TO_BOOL_ALWAYS_TRUE | 216,240 | 7.7% |
| TO_BOOL_INT | 206,300 | 7.4% |
| JUMP_BACKWARD | 159,980 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,104,700 | 39.4% |
| JUMP_FORWARD | 789,520 | 28.2% |
| ENTER_EXECUTOR | 477,360 | 17.0% |
| FOR_ITER_GEN | 128,600 | 4.6% |
| FOR_ITER_LIST | 110,540 | 3.9% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 49,536,000 | 81.8% |
| GET_ITER | 9,848,140 | 16.3% |
| SWAP | 1,036,440 | 1.7% |
| EXTENDED_ARG | 60,260 | 0.1% |
| ENTER_EXECUTOR | 45,620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 27,142,440 | 44.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 24,836,000 | 41.0% |
| LOAD_FAST | 6,303,200 | 10.4% |
| RETURN_CONST | 1,418,320 | 2.3% |
| SWAP | 553,480 | 0.9% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 11,180 | 79.1% |
| STORE_NAME | 2,960 | 20.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,840 | 55.4% |
| STORE_NAME | 6,280 | 44.4% |
| PUSH_EXC_INFO | 20 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 26,500 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,780 | 44.5% |
| IMPORT_FROM | 11,180 | 42.2% |
| STORE_NAME | 3,400 | 12.8% |
| PUSH_EXC_INFO | 120 | 0.5% |
| CALL_INTRINSIC_1 | 20 | 0.1% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 674,480 | 59.3% |
| LOAD_CONST | 366,640 | 32.3% |
| LOAD_FAST | 69,840 | 6.1% |
| LOAD_ATTR_MODULE | 21,300 | 1.9% |
| LOAD_GLOBAL_BUILTIN | 4,020 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 715,820 | 63.0% |
| LOAD_CONST | 338,160 | 29.8% |
| POP_JUMP_IF_TRUE | 61,840 | 5.4% |
| STORE_FAST | 15,740 | 1.4% |
| LOAD_FAST | 4,140 | 0.4% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 22,376,360 | 39.9% |
| POP_TOP | 19,531,160 | 34.8% |
| LIST_APPEND | 5,559,680 | 9.9% |
| POP_JUMP_IF_FALSE | 4,915,460 | 8.8% |
| STORE_SUBSCR_DICT | 3,180,900 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 49,536,000 | 88.4% |
| FOR_ITER_GEN | 6,256,500 | 11.2% |
| EXTENDED_ARG | 159,980 | 0.3% |
| FOR_ITER_LIST | 42,960 | 0.1% |
| LOAD_FAST | 26,700 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 80 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,232,820 | 25.8% |
| STORE_ATTR_INSTANCE_VALUE | 2,061,360 | 23.9% |
| POP_JUMP_IF_FALSE | 1,043,940 | 12.1% |
| EXTENDED_ARG | 789,520 | 9.1% |
| JUMP_FORWARD | 689,840 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,993,400 | 34.6% |
| LOAD_GLOBAL_BUILTIN | 1,518,520 | 17.6% |
| LOAD_FAST_LOAD_FAST | 1,464,360 | 16.9% |
| LOAD_CONST | 802,900 | 9.3% |
| BUILD_LIST | 689,840 | 8.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,351,040 | 43.9% |
| BINARY_SUBSCR_DICT | 2,851,980 | 37.4% |
| RETURN_VALUE | 703,920 | 9.2% |
| BINARY_SLICE | 323,220 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 199,360 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,559,680 | 72.9% |
| ENTER_EXECUTOR | 2,068,760 | 27.1% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,622,560 | 99.2% |
| RETURN_VALUE | 16,220 | 0.4% |
| LOAD_ATTR_INSTANCE_VALUE | 6,020 | 0.2% |
| LOAD_CONST | 4,880 | 0.1% |
| BINARY_OP | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 3,645,740 | 99.9% |
| BUILD_TUPLE | 3,920 | 0.1% |
| STORE_NAME | 720 | 0.0% |
| LOAD_CONST | 220 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 119,624,980 | 59.9% |
| LOAD_ATTR_SLOT | 56,475,280 | 28.3% |
| LOAD_GLOBAL_MODULE | 11,176,020 | 5.6% |
| LOAD_ATTR | 5,610,580 | 2.8% |
| ENTER_EXECUTOR | 1,551,180 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 42,941,680 | 21.5% |
| LOAD_FAST | 33,337,300 | 16.7% |
| POP_JUMP_IF_NOT_NONE | 17,332,480 | 8.7% |
| BINARY_OP | 15,442,180 | 7.7% |
| CALL_BUILTIN_FAST | 15,441,100 | 7.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 102,205,200 | 28.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 39,446,720 | 11.0% |
| LOAD_CONST | 33,954,940 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 23,564,780 | 6.6% |
| FORMAT_SIMPLE | 21,315,900 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,793,820 | 24.2% |
| CALL_BUILTIN_FAST | 39,793,520 | 11.1% |
| LOAD_CONST | 33,954,940 | 9.5% |
| STORE_FAST | 32,763,700 | 9.1% |
| BINARY_SLICE | 16,102,800 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,066,160 | 86.0% |
| LOAD_ATTR | 56,020 | 4.5% |
| LOAD_ATTR_METHOD_NO_DICT | 47,140 | 3.8% |
| LOAD_GLOBAL_BUILTIN | 23,120 | 1.9% |
| LOAD_FAST | 15,140 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,064,120 | 85.8% |
| LOAD_ATTR_INSTANCE_VALUE | 55,920 | 4.5% |
| LOAD_CONST | 50,360 | 4.1% |
| LOAD_FAST | 25,800 | 2.1% |
| RETURN_VALUE | 14,500 | 1.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 211,428,560 | 10.9% |
| RESUME_CHECK | 189,050,900 | 9.7% |
| POP_JUMP_IF_FALSE | 163,837,100 | 8.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 157,479,720 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 150,632,580 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 331,424,420 | 17.1% |
| CALL_PY_EXACT_ARGS | 163,275,600 | 8.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 160,853,240 | 8.3% |
| LOAD_ATTR | 119,624,980 | 6.2% |
| LOAD_CONST | 102,205,200 | 5.3% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,976,260 | 89.6% |
| LOAD_FAST_AND_CLEAR | 344,320 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,976,260 | 89.6% |
| LOAD_FAST_AND_CLEAR | 344,320 | 10.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 26,200 | 24.2% |
| ENTER_EXECUTOR | 18,640 | 17.2% |
| STORE_FAST | 15,680 | 14.5% |
| FOR_ITER | 12,880 | 11.9% |
| POP_TOP | 8,660 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 34,080 | 31.5% |
| RETURN_VALUE | 22,880 | 21.1% |
| LOAD_FAST | 14,460 | 13.4% |
| TO_BOOL_NONE | 11,600 | 10.7% |
| POP_JUMP_IF_NOT_NONE | 7,200 | 6.6% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 90,366,980 | 26.9% |
| STORE_FAST | 61,054,960 | 18.1% |
| POP_JUMP_IF_FALSE | 36,765,440 | 10.9% |
| RESUME_CHECK | 24,685,580 | 7.3% |
| RETURN_VALUE | 22,323,200 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 57,800,240 | 17.2% |
| LOAD_FAST | 48,678,900 | 14.5% |
| STORE_ATTR_INSTANCE_VALUE | 34,860,640 | 10.4% |
| CONTAINS_OP | 31,620,540 | 9.4% |
| CALL_BUILTIN_FAST | 27,900,580 | 8.3% |


</details>

### LOAD_FROM_DICT_OR_DEREF

<details>
<summary> Successors and predecessors for LOAD_FROM_DICT_OR_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_LOCALS | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,020 | 15.9% |
| POP_JUMP_IF_FALSE | 7,860 | 12.4% |
| LOAD_FAST | 7,200 | 11.4% |
| LOAD_ATTR | 4,620 | 7.3% |
| RESUME | 4,280 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 18,720 | 29.6% |
| LOAD_GLOBAL_BUILTIN | 12,400 | 19.6% |
| LOAD_FAST | 12,360 | 19.6% |
| LOAD_ATTR | 11,600 | 18.4% |
| CALL | 3,080 | 4.9% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 12,500 | 24.6% |
| LOAD_CONST | 11,060 | 21.8% |
| RESUME | 6,900 | 13.6% |
| LOAD_NAME | 5,560 | 11.0% |
| PUSH_NULL | 4,700 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 8,840 | 17.4% |
| STORE_NAME | 8,760 | 17.3% |
| CALL | 6,480 | 12.8% |
| PUSH_NULL | 6,320 | 12.5% |
| LOAD_NAME | 5,560 | 11.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 80 | 36.4% |
| CALL | 40 | 18.2% |
| LOAD_FAST | 40 | 18.2% |
| PUSH_NULL | 20 | 9.1% |
| LOAD_FAST_LOAD_FAST | 20 | 9.1% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 196,580 | 92.0% |
| MAKE_CELL | 15,820 | 7.4% |
| CACHE | 800 | 0.4% |
| CALL | 440 | 0.2% |
| CALL_KW | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 197,240 | 92.3% |
| MAKE_CELL | 15,820 | 7.4% |
| RESUME | 720 | 0.3% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,880 | 56.6% |
| LOAD_CONST | 30,440 | 31.4% |
| LOAD_ATTR_MODULE | 7,800 | 8.0% |
| BUILD_TUPLE | 2,360 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,220 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 75,060 | 77.4% |
| EXTENDED_ARG | 14,920 | 15.4% |
| CALL_FUNCTION_EX | 3,920 | 4.0% |
| DICT_UPDATE | 1,440 | 1.5% |
| JUMP_BACKWARD | 1,360 | 1.4% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 136,965,520 | 44.9% |
| TO_BOOL_NONE | 58,716,020 | 19.2% |
| CONTAINS_OP | 39,294,120 | 12.9% |
| COMPARE_OP_INT | 19,869,820 | 6.5% |
| TO_BOOL_LIST | 14,294,960 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 163,837,100 | 53.7% |
| RETURN_CONST | 46,362,580 | 15.2% |
| LOAD_FAST_LOAD_FAST | 36,765,440 | 12.0% |
| LOAD_GLOBAL_BUILTIN | 14,891,560 | 4.9% |
| LOAD_CONST | 13,285,220 | 4.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,896,540 | 75.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,594,300 | 24.7% |
| CALL_BUILTIN_FAST | 4,060 | 0.0% |
| LOAD_ATTR_WITH_HINT | 3,820 | 0.0% |
| LOAD_ATTR_MODULE | 3,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,319,180 | 50.6% |
| RETURN_CONST | 3,473,040 | 33.1% |
| LOAD_GLOBAL_BUILTIN | 1,510,780 | 14.4% |
| LOAD_CONST | 164,100 | 1.6% |
| LOAD_GLOBAL_MODULE | 19,260 | 0.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,282,400 | 63.4% |
| LOAD_ATTR | 17,332,480 | 26.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 4,787,680 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,346,640 | 2.1% |
| STORE_FAST_LOAD_FAST | 146,960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,169,000 | 80.2% |
| NOP | 5,131,400 | 7.9% |
| RETURN_CONST | 3,095,320 | 4.8% |
| LOAD_GLOBAL_BUILTIN | 2,716,060 | 4.2% |
| LOAD_FAST_LOAD_FAST | 1,397,020 | 2.1% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 65,616,480 | 38.2% |
| CONTAINS_OP | 38,380,780 | 22.4% |
| TO_BOOL_NONE | 27,598,740 | 16.1% |
| TO_BOOL_INT | 17,114,000 | 10.0% |
| TO_BOOL_STR | 8,729,220 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 57,789,220 | 33.7% |
| LOAD_FAST | 28,313,380 | 16.5% |
| NOP | 27,522,660 | 16.0% |
| JUMP_BACKWARD | 22,376,360 | 13.0% |
| RETURN_CONST | 16,167,920 | 9.4% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 778,140 | 49.6% |
| LOAD_GLOBAL_BUILTIN | 724,160 | 46.2% |
| POP_JUMP_IF_FALSE | 42,900 | 2.7% |
| LOAD_CONST | 15,680 | 1.0% |
| CALL | 5,340 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,004,800 | 64.1% |
| COPY | 562,500 | 35.9% |
| LOAD_CONST | 100 | 0.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 1,230,260 | 65.2% |
| POP_TOP | 503,960 | 26.7% |
| POP_JUMP_IF_FALSE | 152,040 | 8.1% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |
| DELETE_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,230,080 | 65.2% |
| COPY | 656,240 | 34.8% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 46,362,580 | 21.5% |
| ENTER_EXECUTOR | 35,604,480 | 16.5% |
| RESUME_CHECK | 22,513,240 | 10.4% |
| POP_TOP | 18,983,000 | 8.8% |
| POP_JUMP_IF_TRUE | 16,167,920 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 112,327,160 | 52.0% |
| END_FOR | 49,182,780 | 22.8% |
| INTERPRETER_EXIT | 25,227,560 | 11.7% |
| RETURN_VALUE | 19,819,520 | 9.2% |
| TO_BOOL_NONE | 4,258,780 | 2.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 80 | 57.1% |
| LOAD_CONST | 40 | 28.6% |
| SEND | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 80 | 57.1% |
| END_SEND | 40 | 28.6% |
| SEND | 20 | 14.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 318,640 | 99.7% |
| SET_FUNCTION_ATTRIBUTE | 800 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 179,080 | 56.1% |
| STORE_FAST | 127,500 | 39.9% |
| STORE_NAME | 8,120 | 2.5% |
| LOAD_GLOBAL_MODULE | 2,880 | 0.9% |
| SET_FUNCTION_ATTRIBUTE | 800 | 0.3% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 80 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,396,120 | 69.3% |
| LOAD_FAST_LOAD_FAST | 7,786,600 | 26.5% |
| SWAP | 1,145,320 | 3.9% |
| ENTER_EXECUTOR | 47,700 | 0.2% |
| STORE_ATTR | 31,260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,521,140 | 59.6% |
| RETURN_CONST | 8,173,040 | 27.8% |
| LOAD_GLOBAL_MODULE | 2,454,220 | 8.3% |
| LOAD_FAST_LOAD_FAST | 828,680 | 2.8% |
| ENTER_EXECUTOR | 144,300 | 0.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 14,520 | 91.0% |
| LOAD_ATTR | 320 | 2.0% |
| STORE_DEREF | 320 | 2.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 220 | 1.4% |
| CALL | 100 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,740 | 92.4% |
| STORE_DEREF | 320 | 2.0% |
| LOAD_GLOBAL_BUILTIN | 300 | 1.9% |
| STORE_FAST | 220 | 1.4% |
| LOAD_DEREF | 120 | 0.8% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 49,023,300 | 11.0% |
| LOAD_ATTR | 42,941,680 | 9.6% |
| CALL_BUILTIN_FAST | 42,839,980 | 9.6% |
| LOAD_CONST | 32,763,700 | 7.3% |
| CALL | 30,314,320 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 211,428,560 | 47.4% |
| LOAD_GLOBAL_BUILTIN | 62,701,920 | 14.0% |
| LOAD_FAST_LOAD_FAST | 61,054,960 | 13.7% |
| NOP | 41,322,460 | 9.3% |
| LOAD_CONST | 18,924,320 | 4.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 838,740 | 66.8% |
| FOR_ITER_TUPLE | 386,320 | 30.8% |
| CALL_LEN | 14,480 | 1.2% |
| FOR_ITER | 8,080 | 0.6% |
| FOR_ITER_RANGE | 4,700 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 491,240 | 39.1% |
| TO_BOOL_STR | 387,080 | 30.8% |
| POP_JUMP_IF_NOT_NONE | 146,960 | 11.7% |
| LOAD_ATTR_METHOD_NO_DICT | 125,740 | 10.0% |
| LOAD_ATTR | 28,880 | 2.3% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 37,928,460 | 76.0% |
| UNPACK_SEQUENCE_TUPLE | 11,113,900 | 22.3% |
| STORE_FAST_STORE_FAST | 767,280 | 1.5% |
| UNPACK_SEQUENCE_LIST | 37,960 | 0.1% |
| BINARY_SLICE | 15,980 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,099,480 | 32.3% |
| LOAD_GLOBAL_MODULE | 15,676,120 | 31.4% |
| STORE_FAST | 10,671,540 | 21.4% |
| LOAD_GLOBAL_BUILTIN | 3,302,960 | 6.6% |
| LOAD_FAST_LOAD_FAST | 3,183,900 | 6.4% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 41.4% |
| COPY | 80 | 13.8% |
| STORE_GLOBAL | 80 | 13.8% |
| BINARY_SUBSCR | 40 | 6.9% |
| LOAD_ATTR | 40 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 41.4% |
| LOAD_FAST | 100 | 17.2% |
| STORE_GLOBAL | 80 | 13.8% |
| LOAD_BUILD_CLASS | 60 | 10.3% |
| RETURN_CONST | 40 | 6.9% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 27,320 | 28.3% |
| LOAD_CONST | 22,820 | 23.6% |
| CALL | 9,140 | 9.5% |
| LOAD_NAME | 8,760 | 9.1% |
| SET_FUNCTION_ATTRIBUTE | 8,120 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,700 | 60.8% |
| LOAD_NAME | 12,500 | 12.9% |
| RETURN_CONST | 7,640 | 7.9% |
| LOAD_BUILD_CLASS | 6,060 | 6.3% |
| POP_TOP | 3,320 | 3.4% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 5,696,840 | 25.4% |
| RETURN_VALUE | 3,196,580 | 14.3% |
| LOAD_FAST_AND_CLEAR | 2,976,260 | 13.3% |
| BUILD_LIST | 2,976,100 | 13.3% |
| BINARY_OP | 1,728,000 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 7,284,040 | 32.5% |
| POP_TOP | 3,481,740 | 15.5% |
| BUILD_LIST | 2,976,100 | 13.3% |
| STORE_FAST | 1,680,240 | 7.5% |
| FOR_ITER_LIST | 1,509,140 | 6.7% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,920 | 67.2% |
| FOR_ITER | 1,120 | 15.3% |
| LOAD_FAST | 320 | 4.4% |
| BINARY_SUBSCR | 200 | 2.7% |
| FOR_ITER_LIST | 180 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 3,280 | 44.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,720 | 37.2% |
| UNPACK_SEQUENCE_TUPLE | 900 | 12.3% |
| LOAD_FAST | 260 | 3.6% |
| STORE_FAST | 100 | 1.4% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 15,000 | 44.8% |
| CALL | 10,100 | 30.2% |
| CALL_PY_EXACT_ARGS | 3,060 | 9.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,860 | 8.5% |
| MAKE_CELL | 720 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,220 | 33.5% |
| LOAD_NAME | 6,900 | 20.6% |
| RETURN_CONST | 5,040 | 15.1% |
| LOAD_GLOBAL | 4,280 | 12.8% |
| LOAD_CONST | 2,840 | 8.5% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 3,880 | 99.5% |
| BINARY_OP | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,900 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,448,200 | 45.7% |
| LOAD_FAST | 11,646,200 | 39.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,608,800 | 8.9% |
| CALL_LEN | 972,240 | 3.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 489,760 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,667,060 | 22.7% |
| SWAP | 5,696,840 | 19.4% |
| LOAD_FAST | 4,612,580 | 15.7% |
| BINARY_SLICE | 3,819,560 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 3,679,440 | 12.5% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,826,880 | 76.7% |
| BUILD_STRING | 2,681,240 | 10.4% |
| LOAD_CONST | 1,156,900 | 4.5% |
| LOAD_ATTR | 804,920 | 3.1% |
| RETURN_VALUE | 548,760 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,951,560 | 73.3% |
| RETURN_VALUE | 2,716,500 | 10.5% |
| STORE_FAST | 1,921,120 | 7.4% |
| SWAP | 1,561,700 | 6.0% |
| LOAD_CONST | 459,740 | 1.8% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,760 | 58.6% |
| BINARY_SUBSCR_TUPLE_INT | 5,780 | 34.7% |
| BINARY_OP_ADD_INT | 520 | 3.1% |
| LOAD_ATTR | 320 | 1.9% |
| BINARY_OP_SUBTRACT_INT | 200 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 5,780 | 34.7% |
| CALL | 3,900 | 23.4% |
| LOAD_CONST | 3,200 | 19.2% |
| CALL_BUILTIN_O | 2,680 | 16.1% |
| BINARY_OP_SUBTRACT_INT | 520 | 3.1% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,880 | 99.5% |
| BINARY_OP | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 3,880 | 99.5% |
| BINARY_OP | 20 | 0.5% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,956,280 | 56.6% |
| CALL_LEN | 1,244,440 | 17.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,115,240 | 16.0% |
| LOAD_FAST | 663,400 | 9.5% |
| LOAD_FAST_LOAD_FAST | 6,100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,282,140 | 32.7% |
| LOAD_CONST | 1,454,820 | 20.8% |
| CALL_PY_EXACT_ARGS | 1,214,040 | 17.4% |
| BINARY_SUBSCR_LIST_INT | 576,460 | 8.2% |
| LOAD_FAST | 439,160 | 6.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,307,600 | 79.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,268,000 | 6.0% |
| CALL_BUILTIN_O | 2,851,960 | 5.2% |
| LOAD_CONST | 1,485,420 | 2.7% |
| LOAD_FAST_LOAD_FAST | 1,473,420 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,161,820 | 51.5% |
| RETURN_VALUE | 10,627,920 | 19.4% |
| UNPACK_SEQUENCE_TUPLE | 6,538,660 | 12.0% |
| LIST_APPEND | 2,851,980 | 5.2% |
| TO_BOOL_ALWAYS_TRUE | 1,328,320 | 2.4% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,246,640 | 55.9% |
| LOAD_ATTR_INSTANCE_VALUE | 4,473,240 | 40.0% |
| ENTER_EXECUTOR | 300,240 | 2.7% |
| LOAD_FAST_LOAD_FAST | 80,720 | 0.7% |
| LOAD_FAST | 51,400 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,161,160 | 99.8% |
| LOAD_ATTR_METHOD_NO_DICT | 7,680 | 0.1% |
| CONTAINS_OP | 6,060 | 0.1% |
| LOAD_FAST | 2,580 | 0.0% |
| PUSH_EXC_INFO | 1,200 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,225,960 | 76.1% |
| LOAD_FAST_LOAD_FAST | 3,022,000 | 12.0% |
| LOAD_CONST | 2,144,360 | 8.5% |
| BINARY_OP_SUBTRACT_INT | 576,460 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 138,760 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 15,335,580 | 64.3% |
| LOAD_FAST | 2,062,320 | 8.6% |
| LOAD_CONST | 1,809,860 | 7.6% |
| STORE_FAST | 1,320,000 | 5.5% |
| PUSH_EXC_INFO | 1,086,160 | 4.6% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,365,240 | 64.8% |
| LOAD_CONST | 1,508,220 | 22.4% |
| BINARY_OP_SUBTRACT_INT | 328,600 | 4.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 328,600 | 4.9% |
| LOAD_FAST | 123,760 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,365,980 | 64.8% |
| LOAD_CONST | 1,258,500 | 18.7% |
| STORE_FAST | 950,160 | 14.1% |
| LOAD_FAST | 119,100 | 1.8% |
| COMPARE_OP_STR | 23,240 | 0.3% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,495,220 | 100.0% |
| BINARY_SUBSCR | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 5,092,440 | 44.3% |
| STORE_SUBSCR_DICT | 5,092,440 | 44.3% |
| LOAD_CONST | 468,720 | 4.1% |
| LOAD_GLOBAL_BUILTIN | 395,840 | 3.4% |
| STORE_FAST | 155,740 | 1.4% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,541,540 | 70.4% |
| LOAD_FAST | 512,420 | 14.2% |
| LOAD_GLOBAL_MODULE | 252,660 | 7.0% |
| LOAD_FAST_LOAD_FAST | 87,520 | 2.4% |
| LOAD_ATTR_WITH_HINT | 80,360 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,217,180 | 61.4% |
| RESUME_CHECK | 1,333,120 | 36.9% |
| CALL_ALLOC_AND_ENTER_INIT | 42,940 | 1.2% |
| STORE_FAST | 16,860 | 0.5% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,120,920 | 97.6% |
| LOAD_CONST | 131,640 | 1.0% |
| CALL_PY_EXACT_ARGS | 112,400 | 0.8% |
| PUSH_NULL | 40,620 | 0.3% |
| BUILD_TUPLE | 16,040 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 13,314,540 | 99.1% |
| CALL_PY_EXACT_ARGS | 112,840 | 0.8% |
| POP_TOP | 10,620 | 0.1% |
| RESUME | 2,860 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 480 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,575,640 | 33.2% |
| LOAD_FAST | 2,190,100 | 28.3% |
| CALL_BUILTIN_CLASS | 1,981,800 | 25.6% |
| CALL_LEN | 619,240 | 8.0% |
| CALL_FUNCTION_EX | 116,760 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,498,180 | 45.1% |
| CALL_BUILTIN_CLASS | 1,981,800 | 25.6% |
| LOAD_FAST | 1,461,380 | 18.9% |
| BINARY_OP | 396,980 | 5.1% |
| STORE_FAST | 269,220 | 3.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 39,793,520 | 46.3% |
| LOAD_FAST_LOAD_FAST | 27,900,580 | 32.5% |
| LOAD_ATTR | 15,441,100 | 18.0% |
| BINARY_SUBSCR_DICT | 1,309,240 | 1.5% |
| LOAD_FAST | 683,500 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 42,839,980 | 49.8% |
| TO_BOOL_BOOL | 39,458,080 | 45.9% |
| POP_TOP | 2,237,600 | 2.6% |
| LOAD_ATTR_METHOD_NO_DICT | 715,100 | 0.8% |
| COPY | 192,340 | 0.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,681,640 | 90.1% |
| STORE_FAST | 175,480 | 5.9% |
| LOAD_FAST | 99,420 | 3.3% |
| LOAD_CONST | 8,280 | 0.3% |
| RETURN_GENERATOR | 3,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,924,600 | 98.3% |
| PUSH_EXC_INFO | 24,340 | 0.8% |
| RETURN_VALUE | 17,940 | 0.6% |
| POP_TOP | 7,920 | 0.3% |
| BEFORE_WITH | 1,440 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,400,760 | 99.0% |
| RETURN_VALUE | 75,600 | 0.3% |
| CALL_BUILTIN_FAST | 47,000 | 0.2% |
| LOAD_GLOBAL_MODULE | 28,480 | 0.1% |
| LOAD_CONST | 23,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 17,115,780 | 72.4% |
| LOAD_CONST | 3,269,480 | 13.8% |
| BINARY_SUBSCR_DICT | 2,851,960 | 12.1% |
| POP_TOP | 222,720 | 0.9% |
| BUILD_TUPLE | 110,620 | 0.5% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 57,800,240 | 54.2% |
| LOAD_GLOBAL_MODULE | 20,470,100 | 19.2% |
| LOAD_GLOBAL_BUILTIN | 18,602,560 | 17.5% |
| LOAD_ATTR_MODULE | 7,314,680 | 6.9% |
| LOAD_FAST | 1,340,120 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 105,100,900 | 98.6% |
| RETURN_VALUE | 1,458,720 | 1.4% |
| TO_BOOL | 3,040 | 0.0% |
| LOAD_FAST | 1,880 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 20,978,760 | 55.3% |
| LOAD_FAST | 15,911,480 | 42.0% |
| LOAD_ATTR | 391,460 | 1.0% |
| RETURN_VALUE | 236,040 | 0.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 144,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 8,744,200 | 23.1% |
| LOAD_CONST | 6,934,640 | 18.3% |
| RETURN_VALUE | 6,348,660 | 16.7% |
| LOAD_FAST | 5,128,500 | 13.5% |
| CALL_PY_EXACT_ARGS | 3,635,640 | 9.6% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,309,140 | 71.0% |
| BINARY_SUBSCR_TUPLE_INT | 5,092,440 | 9.2% |
| RETURN_VALUE | 2,770,440 | 5.0% |
| LOAD_CONST | 2,729,720 | 4.9% |
| BUILD_STRING | 1,864,080 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 31,861,460 | 57.5% |
| RETURN_CONST | 12,411,620 | 22.4% |
| LOAD_GLOBAL_MODULE | 3,512,100 | 6.3% |
| LOAD_FAST | 3,286,780 | 5.9% |
| LOAD_CONST | 1,242,720 | 2.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 10,440,460 | 35.5% |
| LOAD_CONST | 6,006,340 | 20.4% |
| LOAD_FAST_LOAD_FAST | 5,988,100 | 20.3% |
| BUILD_LIST | 5,848,180 | 19.9% |
| LOAD_FAST | 969,260 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,333,960 | 31.7% |
| RETURN_VALUE | 5,996,060 | 20.4% |
| TO_BOOL_STR | 3,936,140 | 13.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,011,940 | 10.2% |
| CALL_METHOD_DESCRIPTOR_O | 2,681,280 | 9.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,833,860 | 46.6% |
| LOAD_FAST | 2,979,160 | 28.7% |
| LOAD_CONST | 2,364,060 | 22.8% |
| LOAD_FAST_LOAD_FAST | 140,080 | 1.4% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 44,220 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 3,902,380 | 37.6% |
| BINARY_OP | 2,681,260 | 25.8% |
| STORE_FAST | 1,456,400 | 14.0% |
| RETURN_VALUE | 1,070,440 | 10.3% |
| LOAD_FAST | 369,660 | 3.6% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 19,736,680 | 99.9% |
| LOAD_ATTR | 11,760 | 0.1% |
| CALL | 1,300 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 7,025,820 | 35.6% |
| STORE_FAST | 4,547,080 | 23.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,681,640 | 13.6% |
| STORE_SUBSCR_DICT | 1,965,360 | 10.0% |
| RETURN_VALUE | 1,488,180 | 7.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,517,940 | 54.5% |
| LOAD_ATTR | 4,016,300 | 15.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 3,902,380 | 14.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,681,280 | 10.1% |
| STORE_FAST | 565,340 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,768,260 | 25.4% |
| RETURN_VALUE | 6,557,900 | 24.6% |
| STORE_FAST | 3,524,160 | 13.2% |
| LOAD_CONST | 2,696,640 | 10.1% |
| CONVERT_VALUE | 2,681,260 | 10.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 163,275,600 | 64.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 39,705,740 | 15.7% |
| LOAD_FAST_LOAD_FAST | 13,648,360 | 5.4% |
| LOAD_ATTR_INSTANCE_VALUE | 8,236,880 | 3.3% |
| BUILD_LIST | 5,385,360 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 201,647,560 | 79.9% |
| RETURN_GENERATOR | 49,284,560 | 19.5% |
| COPY_FREE_VARS | 1,088,340 | 0.4% |
| MAKE_CELL | 196,580 | 0.1% |
| CALL_PY_EXACT_ARGS | 113,960 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,198,840 | 74.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,577,620 | 12.6% |
| CALL_STR_1 | 1,847,400 | 5.1% |
| LOAD_CONST | 1,688,940 | 4.6% |
| LOAD_FAST_LOAD_FAST | 477,480 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 36,275,040 | 99.9% |
| RETURN_GENERATOR | 41,060 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 5,180 | 0.0% |
| STORE_FAST | 3,820 | 0.0% |
| CALL_PY_EXACT_ARGS | 1,680 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,226,320 | 75.8% |
| RETURN_VALUE | 2,299,560 | 24.1% |
| CALL_LEN | 2,800 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,480 | 0.0% |
| CALL | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,028,540 | 42.3% |
| RETURN_VALUE | 2,564,520 | 26.9% |
| CALL_PY_WITH_DEFAULTS | 1,847,400 | 19.4% |
| STORE_SUBSCR_DICT | 957,960 | 10.1% |
| CALL | 100,980 | 1.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 217,560 | 69.9% |
| POP_JUMP_IF_TRUE | 46,980 | 15.1% |
| LOAD_CONST | 23,460 | 7.5% |
| LOAD_FAST | 17,480 | 5.6% |
| RETURN_GENERATOR | 3,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 221,560 | 71.2% |
| LOAD_FAST | 82,240 | 26.4% |
| BINARY_OP | 3,900 | 1.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,860 | 0.6% |
| CALL | 1,680 | 0.5% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,774,960 | 85.2% |
| LOAD_FAST | 829,400 | 14.8% |
| LOAD_GLOBAL_MODULE | 1,440 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,774,980 | 85.2% |
| LOAD_FAST_LOAD_FAST | 785,780 | 14.0% |
| LOAD_FAST | 25,520 | 0.5% |
| LOAD_GLOBAL_BUILTIN | 12,660 | 0.2% |
| PUSH_NULL | 6,320 | 0.1% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,460 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,460 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,057,780 | 36.4% |
| CALL_LEN | 8,744,200 | 31.7% |
| LOAD_FAST_LOAD_FAST | 3,465,600 | 12.5% |
| LOAD_ATTR_WITH_HINT | 3,000,480 | 10.9% |
| LOAD_FAST | 1,816,040 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,869,820 | 71.9% |
| POP_JUMP_IF_TRUE | 4,996,900 | 18.1% |
| RETURN_VALUE | 2,630,200 | 9.5% |
| COPY | 128,200 | 0.5% |
| STORE_FAST | 1,560 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,564,220 | 63.6% |
| RETURN_VALUE | 3,746,760 | 31.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 283,040 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 125,220 | 1.1% |
| LOAD_FAST | 51,900 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,612,480 | 55.6% |
| RETURN_VALUE | 3,922,860 | 33.0% |
| POP_JUMP_IF_TRUE | 1,177,760 | 9.9% |
| BINARY_SUBSCR | 101,880 | 0.9% |
| COPY | 34,140 | 0.3% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 49,218,400 | 88.5% |
| JUMP_BACKWARD | 6,256,500 | 11.3% |
| EXTENDED_ARG | 128,600 | 0.2% |
| FOR_ITER | 520 | 0.0% |
| SWAP | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 49,223,460 | 88.5% |
| RESUME_CHECK | 6,381,320 | 11.5% |
| RESUME | 200 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 65,907,700 | 86.6% |
| ENTER_EXECUTOR | 8,023,960 | 10.5% |
| SWAP | 1,509,140 | 2.0% |
| FOR_ITER_TUPLE | 331,100 | 0.4% |
| LOAD_FAST | 138,120 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 49,023,300 | 64.4% |
| RETURN_CONST | 13,234,920 | 17.4% |
| LOAD_FAST | 9,132,080 | 12.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,642,220 | 3.5% |
| STORE_FAST_LOAD_FAST | 838,740 | 1.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 516,200 | 89.7% |
| SWAP | 44,420 | 7.7% |
| JUMP_BACKWARD | 13,840 | 2.4% |
| FOR_ITER | 780 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 527,700 | 91.7% |
| SWAP | 38,120 | 6.6% |
| STORE_FAST_LOAD_FAST | 4,700 | 0.8% |
| LOAD_FAST | 2,980 | 0.5% |
| LOAD_FAST_LOAD_FAST | 740 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 35,184,960 | 90.0% |
| ENTER_EXECUTOR | 3,185,360 | 8.1% |
| SWAP | 385,760 | 1.0% |
| FOR_ITER_LIST | 331,100 | 0.8% |
| JUMP_BACKWARD | 11,940 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,414,720 | 62.4% |
| RETURN_CONST | 11,575,700 | 29.6% |
| LOAD_FAST | 1,972,080 | 5.0% |
| LOAD_FAST_LOAD_FAST | 398,280 | 1.0% |
| STORE_FAST_LOAD_FAST | 386,320 | 1.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 18,919,420 | 94.5% |
| ENTER_EXECUTOR | 713,640 | 3.6% |
| LOAD_FAST | 208,100 | 1.0% |
| LOAD_FAST_LOAD_FAST | 140,320 | 0.7% |
| LOAD_ATTR_CLASS | 27,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 11,043,540 | 55.2% |
| TO_BOOL_BOOL | 2,909,040 | 14.5% |
| LOAD_FAST | 2,786,280 | 13.9% |
| CONTAINS_OP | 2,333,640 | 11.7% |
| CALL_PY_EXACT_ARGS | 333,820 | 1.7% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 331,424,420 | 75.6% |
| ENTER_EXECUTOR | 50,826,340 | 11.6% |
| LOAD_ATTR_INSTANCE_VALUE | 24,019,720 | 5.5% |
| LOAD_FAST_LOAD_FAST | 23,351,180 | 5.3% |
| COPY | 7,271,640 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 116,924,200 | 26.7% |
| TO_BOOL_NONE | 43,824,240 | 10.0% |
| GET_ITER | 38,031,000 | 8.7% |
| CONTAINS_OP | 32,629,360 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 24,019,720 | 5.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,308,760 | 60.6% |
| LOAD_ATTR_INSTANCE_VALUE | 20,612,260 | 12.7% |
| LOAD_CONST | 14,757,100 | 9.1% |
| LOAD_ATTR_WITH_HINT | 9,968,260 | 6.1% |
| RETURN_VALUE | 4,157,060 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,302,720 | 58.1% |
| LOAD_CONST | 23,564,780 | 14.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 19,736,680 | 12.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 10,440,460 | 6.4% |
| LOAD_FAST_LOAD_FAST | 8,036,640 | 5.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160,853,240 | 59.5% |
| ENTER_EXECUTOR | 49,519,600 | 18.3% |
| LOAD_ATTR_WITH_HINT | 30,945,200 | 11.5% |
| LOAD_ATTR_INSTANCE_VALUE | 15,847,220 | 5.9% |
| LOAD_FAST_LOAD_FAST | 5,968,720 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 157,479,720 | 58.3% |
| CALL_PY_EXACT_ARGS | 39,705,740 | 14.7% |
| LOAD_CONST | 39,446,720 | 14.6% |
| LOAD_FAST_LOAD_FAST | 21,455,420 | 7.9% |
| CALL_PY_WITH_DEFAULTS | 4,577,620 | 1.7% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 38,003,720 | 99.6% |
| LOAD_ATTR_MODULE | 87,440 | 0.2% |
| LOAD_FAST | 36,900 | 0.1% |
| LOAD_ATTR_WITH_HINT | 16,680 | 0.0% |
| LOAD_ATTR | 10,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 26,100,720 | 68.4% |
| CALL_ISINSTANCE | 7,314,680 | 19.2% |
| LOAD_GLOBAL_MODULE | 1,060,740 | 2.8% |
| BUILD_TUPLE | 946,920 | 2.5% |
| LOAD_CONST | 874,220 | 2.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,380 | 96.9% |
| LOAD_CONST | 180 | 1.9% |
| LOAD_ATTR | 120 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 4,840 | 50.0% |
| LOAD_FAST | 4,140 | 42.8% |
| TO_BOOL_STR | 200 | 2.1% |
| LOAD_GLOBAL_BUILTIN | 180 | 1.9% |
| LOAD_ATTR_METHOD_NO_DICT | 160 | 1.7% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,596,460 | 96.7% |
| LOAD_FAST_LOAD_FAST | 1,220,720 | 1.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 916,960 | 1.0% |
| ENTER_EXECUTOR | 452,040 | 0.5% |
| LOAD_ATTR_INSTANCE_VALUE | 261,340 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,448,840 | 34.8% |
| GET_ITER | 25,695,580 | 29.4% |
| STORE_FAST | 5,606,020 | 6.4% |
| CALL_PY_EXACT_ARGS | 5,011,480 | 5.7% |
| POP_JUMP_IF_NOT_NONE | 4,787,680 | 5.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,749,760 | 98.3% |
| LOAD_ATTR_PROPERTY | 101,320 | 1.3% |
| LOAD_ATTR | 26,900 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 3,720 | 0.0% |
| LOAD_FAST_LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 4,152,060 | 52.7% |
| RESUME_CHECK | 2,488,160 | 31.6% |
| LOAD_ATTR_WITH_HINT | 535,560 | 6.8% |
| LOAD_FAST | 511,400 | 6.5% |
| LOAD_ATTR_PROPERTY | 101,320 | 1.3% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,101,700 | 98.5% |
| LOAD_ATTR_SLOT | 888,720 | 1.5% |
| LOAD_FAST_LOAD_FAST | 25,520 | 0.0% |
| LOAD_ATTR | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 56,475,280 | 95.7% |
| LOAD_FAST | 1,347,800 | 2.3% |
| LOAD_ATTR_SLOT | 888,720 | 1.5% |
| PUSH_NULL | 113,260 | 0.2% |
| LOAD_GLOBAL_MODULE | 101,640 | 0.2% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,542,600 | 61.7% |
| LOAD_ATTR_WITH_HINT | 22,109,720 | 19.4% |
| LOAD_ATTR_INSTANCE_VALUE | 18,306,100 | 16.0% |
| LOAD_FAST_LOAD_FAST | 1,686,660 | 1.5% |
| RETURN_VALUE | 653,960 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,994,880 | 34.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 30,945,200 | 27.1% |
| LOAD_ATTR_WITH_HINT | 22,109,720 | 19.4% |
| LOAD_ATTR_METHOD_NO_DICT | 9,968,260 | 8.7% |
| TO_BOOL_BOOL | 3,775,240 | 3.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 96,164,580 | 34.9% |
| STORE_FAST | 62,701,920 | 22.8% |
| NOP | 28,858,920 | 10.5% |
| LOAD_FAST | 19,920,900 | 7.2% |
| POP_JUMP_IF_FALSE | 14,891,560 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 150,632,580 | 54.7% |
| LOAD_FAST_LOAD_FAST | 90,366,980 | 32.8% |
| CALL_ISINSTANCE | 18,602,560 | 6.8% |
| CHECK_EXC_MATCH | 6,746,140 | 2.5% |
| LOAD_CONST | 4,804,840 | 1.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 30,911,920 | 24.9% |
| LOAD_FAST | 25,042,180 | 20.2% |
| STORE_FAST_STORE_FAST | 15,676,120 | 12.6% |
| STORE_FAST | 12,076,340 | 9.7% |
| POP_JUMP_IF_FALSE | 6,687,800 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 38,003,720 | 30.6% |
| CALL_ISINSTANCE | 20,470,100 | 16.5% |
| LOAD_ATTR_CLASS | 18,919,420 | 15.2% |
| LOAD_FAST | 17,125,720 | 13.8% |
| LOAD_ATTR | 11,176,020 | 9.0% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,320 | 99.6% |
| LOAD_SUPER_ATTR | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 5,340 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 113,640 | 99.9% |
| LOAD_SUPER_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,040 | 86.2% |
| LOAD_FAST_LOAD_FAST | 11,720 | 10.3% |
| CALL | 3,960 | 3.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 201,647,560 | 48.3% |
| CACHE | 53,300,420 | 12.8% |
| POP_TOP | 49,487,700 | 11.9% |
| CALL_PY_WITH_DEFAULTS | 36,275,040 | 8.7% |
| CALL | 32,211,220 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 189,050,900 | 45.3% |
| LOAD_GLOBAL_BUILTIN | 96,164,580 | 23.0% |
| LOAD_GLOBAL_MODULE | 30,911,920 | 7.4% |
| LOAD_FAST_LOAD_FAST | 24,685,580 | 5.9% |
| RETURN_CONST | 22,513,240 | 5.4% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80,527,040 | 64.7% |
| LOAD_FAST_LOAD_FAST | 34,860,640 | 28.0% |
| SWAP | 7,284,040 | 5.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,354,820 | 1.1% |
| RETURN_VALUE | 298,680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,672,820 | 50.3% |
| NOP | 29,542,380 | 23.7% |
| LOAD_GLOBAL_BUILTIN | 11,082,280 | 8.9% |
| RETURN_CONST | 8,654,980 | 7.0% |
| LOAD_FAST_LOAD_FAST | 3,670,000 | 2.9% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,160 | 53.5% |
| LOAD_FAST_LOAD_FAST | 16,520 | 46.1% |
| STORE_ATTR | 120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,180 | 45.2% |
| LOAD_FAST_LOAD_FAST | 9,760 | 27.3% |
| RETURN_CONST | 4,980 | 13.9% |
| LOAD_CONST | 4,880 | 13.6% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,196,000 | 51.2% |
| LOAD_FAST | 4,652,880 | 45.8% |
| SWAP | 294,480 | 2.9% |
| LOAD_ATTR_INSTANCE_VALUE | 6,400 | 0.1% |
| STORE_ATTR | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,018,080 | 49.4% |
| LOAD_FAST | 4,935,900 | 48.6% |
| LOAD_GLOBAL_MODULE | 100,680 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 79,000 | 0.8% |
| BUILD_LIST | 6,600 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 22,298,060 | 40.1% |
| LOAD_FAST | 22,287,980 | 40.1% |
| BINARY_SUBSCR_TUPLE_INT | 5,092,440 | 9.2% |
| LOAD_CONST | 2,188,220 | 3.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,965,360 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,105,760 | 54.2% |
| ENTER_EXECUTOR | 16,905,500 | 30.4% |
| RETURN_CONST | 3,444,280 | 6.2% |
| JUMP_BACKWARD | 3,180,900 | 5.7% |
| LOAD_CONST | 1,198,600 | 2.2% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 625,600 | 61.7% |
| LOAD_FAST | 325,740 | 32.1% |
| LOAD_FAST_LOAD_FAST | 57,100 | 5.6% |
| LOAD_NAME | 3,160 | 0.3% |
| ENTER_EXECUTOR | 1,600 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 498,940 | 49.2% |
| ENTER_EXECUTOR | 333,720 | 32.9% |
| STORE_FAST | 107,740 | 10.6% |
| RETURN_CONST | 54,600 | 5.4% |
| EXTENDED_ARG | 9,580 | 0.9% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,036,440 | 73.6% |
| BINARY_SUBSCR_DICT | 1,328,320 | 19.4% |
| CALL | 111,420 | 1.6% |
| RETURN_CONST | 86,920 | 1.3% |
| RETURN_VALUE | 85,700 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,853,480 | 70.9% |
| POP_JUMP_IF_FALSE | 1,695,520 | 24.8% |
| EXTENDED_ARG | 216,240 | 3.2% |
| TO_BOOL_NONE | 63,980 | 0.9% |
| TO_BOOL_ALWAYS_TRUE | 16,900 | 0.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 105,100,900 | 51.8% |
| CALL_BUILTIN_FAST | 39,458,080 | 19.5% |
| RETURN_VALUE | 26,436,840 | 13.0% |
| LOAD_FAST | 16,205,420 | 8.0% |
| LOAD_ATTR_WITH_HINT | 3,775,240 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 136,965,520 | 67.5% |
| POP_JUMP_IF_TRUE | 65,616,480 | 32.4% |
| EXTENDED_ARG | 150,100 | 0.1% |
| UNARY_NOT | 50,940 | 0.0% |
| TO_BOOL_INT | 1,380 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 17,115,780 | 76.2% |
| COPY | 1,677,180 | 7.5% |
| LOAD_FAST | 1,398,020 | 6.2% |
| LOAD_ATTR | 683,460 | 3.0% |
| CALL_LEN | 514,700 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 17,114,000 | 76.2% |
| POP_JUMP_IF_FALSE | 5,134,660 | 22.9% |
| EXTENDED_ARG | 206,300 | 0.9% |
| UNARY_NOT | 9,480 | 0.0% |
| TO_BOOL_NONE | 4,700 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,927,620 | 78.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,285,060 | 15.0% |
| RETURN_VALUE | 394,160 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 387,400 | 2.6% |
| BINARY_SUBSCR_DICT | 138,760 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,294,960 | 94.1% |
| POP_JUMP_IF_TRUE | 488,080 | 3.2% |
| EXTENDED_ARG | 372,920 | 2.5% |
| TO_BOOL | 26,620 | 0.2% |
| UNARY_NOT | 2,040 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 43,824,240 | 50.6% |
| LOAD_FAST | 22,397,680 | 25.9% |
| COPY | 8,442,300 | 9.7% |
| RETURN_CONST | 4,258,780 | 4.9% |
| LOAD_ATTR_PROPERTY | 4,152,060 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 58,716,020 | 67.8% |
| POP_JUMP_IF_TRUE | 27,598,740 | 31.9% |
| EXTENDED_ARG | 137,300 | 0.2% |
| TO_BOOL | 68,820 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 64,000 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,948,740 | 64.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,936,140 | 23.0% |
| COPY | 999,960 | 5.8% |
| STORE_FAST_LOAD_FAST | 387,080 | 2.3% |
| LOAD_ATTR | 382,620 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 8,729,220 | 51.1% |
| POP_JUMP_IF_FALSE | 8,228,860 | 48.1% |
| UNARY_NOT | 123,300 | 0.7% |
| TO_BOOL_NONE | 16,200 | 0.1% |
| EXTENDED_ARG | 460 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,900 | 86.5% |
| BINARY_SLICE | 3,920 | 10.3% |
| ENTER_EXECUTOR | 1,120 | 2.9% |
| RETURN_VALUE | 40 | 0.1% |
| UNPACK_SEQUENCE | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 37,960 | 99.8% |
| STORE_FAST | 60 | 0.2% |
| UNPACK_SEQUENCE_TUPLE | 20 | 0.1% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 6,538,660 | 58.7% |
| RETURN_VALUE | 4,506,360 | 40.5% |
| LOAD_FAST | 34,600 | 0.3% |
| FOR_ITER_TUPLE | 24,120 | 0.2% |
| BINARY_SLICE | 15,860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 11,113,900 | 99.9% |
| STORE_FAST | 15,600 | 0.1% |
| STORE_DEREF | 80 | 0.0% |
| STORE_NAME | 60 | 0.0% |
| UNPACK_SEQUENCE_LIST | 20 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 24,836,000 | 63.7% |
| RETURN_VALUE | 11,258,620 | 28.9% |
| FOR_ITER_LIST | 2,642,220 | 6.8% |
| BINARY_SUBSCR_LIST_INT | 69,940 | 0.2% |
| YIELD_VALUE | 65,160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 37,928,460 | 97.4% |
| LOAD_FAST | 935,740 | 2.4% |
| STORE_FAST | 96,240 | 0.2% |
| STORE_DEREF | 220 | 0.0% |


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
|     deferred | 28,293,240 | 30.9% |
|          hit | 63,330,640 | 69.1% |
|         miss | 60 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,080 | 16.4% |
| Failure | 36,000 | 83.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 11,560 | 32.1% |
| add different types | 10,860 | 30.2% |
| add other | 9,360 | 26.0% |
| and int | 1,800 | 5.0% |
| or | 1,260 | 3.5% |
| multiply different types | 680 | 1.9% |
| floor divide | 360 | 1.0% |
| and different types | 40 | 0.1% |
| true divide other | 40 | 0.1% |
| power | 20 | 0.1% |
| xor | 20 | 0.1% |


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
|     deferred | 1,558,400 | 1.4% |
|          hit | 106,256,600 | 95.8% |
|         miss | 3,074,120 | 2.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 69,320 | 83.5% |
| Failure | 13,680 | 16.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 12,320 | 90.1% |
| other | 1,280 | 9.4% |
| list slice | 40 | 0.3% |
| buffer slice | 40 | 0.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 82,007,560 | 10.0% |
|          hit | 718,082,980 | 87.2% |
|         miss | 23,095,920 | 2.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 487,740 | 88.5% |
| Failure | 63,540 | 11.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 13,480 | 21.2% |
| meth descr method fastcall keywords | 11,120 | 17.5% |
| meth descr varargs | 10,880 | 17.1% |
| init not simple | 8,020 | 12.6% |
| meth descr varargs keywords | 3,660 | 5.8% |
| cfunc varargs keywords | 3,520 | 5.5% |
| init not python | 3,440 | 5.4% |
| class mutable | 2,700 | 4.2% |
| other | 1,520 | 2.4% |
| wrong number arguments | 1,180 | 1.9% |
| cmethod | 1,020 | 1.6% |
| class no vectorcall | 860 | 1.4% |
| cfunc noargs | 740 | 1.2% |
| cfunc varargs | 620 | 1.0% |
| bound method | 480 | 0.8% |
| str | 140 | 0.2% |
| operator wrapper | 140 | 0.2% |
| method wrapper | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,298,700 | 5.5% |
|          hit | 39,182,600 | 93.6% |
|         miss | 343,340 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,440 | 38.3% |
| Failure | 20,020 | 61.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 17,680 | 88.3% |
| big int | 720 | 3.6% |
| list | 640 | 3.2% |
| tuple | 380 | 1.9% |
| other | 340 | 1.7% |
| baseobject | 200 | 1.0% |
| long float | 40 | 0.2% |
| bytes | 20 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 59,862,720 | 25.8% |
|          hit | 136,246,540 | 58.8% |
|         miss | 35,104,360 | 15.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 666,880 | 96.6% |
| Failure | 23,420 | 3.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 7,000 | 29.9% |
| dict items | 3,940 | 16.8% |
| dict values | 3,780 | 16.1% |
| seq iter | 2,740 | 11.7% |
| ascii string | 2,700 | 11.5% |
| set | 1,220 | 5.2% |
| dict keys | 1,040 | 4.4% |
| map | 260 | 1.1% |
| bytes | 220 | 0.9% |
| reversed list | 200 | 0.9% |
| zip | 180 | 0.8% |
| other | 120 | 0.5% |
| string | 20 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 192,488,060 | 13.8% |
|        deopt | 500 | 0.0% |
|          hit | 831,115,260 | 59.5% |
|         miss | 366,434,320 | 26.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,995,800 | 97.2% |
| Failure | 200,360 | 2.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 88,000 | 43.9% |
| shadowed | 53,080 | 26.5% |
| metaclass attribute | 24,860 | 12.4% |
| method | 12,100 | 6.0% |
| non object slot | 9,000 | 4.5% |
| not managed dict | 4,660 | 2.3% |
| overridden | 4,160 | 2.1% |
| mutable class | 2,520 | 1.3% |
| class attr descriptor | 800 | 0.4% |
| class method obj | 740 | 0.4% |
| module attr not found | 200 | 0.1% |
| class attr simple | 120 | 0.1% |
| builtin class method | 80 | 0.0% |
| non overriding descriptor | 40 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 32,440 | 0.0% |
|        deopt | 1,320 | 0.0% |
|          hit | 399,494,480 | 100.0% |
|         miss | 27,580 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 32,080 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120 | 0.1% |
|          hit | 119,060 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120 | 85.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| list | 20 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 28,021,680 | 17.1% |
|          hit | 62,787,960 | 38.3% |
|         miss | 71,896,480 | 43.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,366,300 | 97.7% |
| Failure | 32,100 | 2.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 24,960 | 77.8% |
| not in dict | 3,200 | 10.0% |
| not in keys | 2,760 | 8.6% |
| property | 460 | 1.4% |
| overridden | 380 | 1.2% |
| no dict | 160 | 0.5% |
| non object slot | 160 | 0.5% |
| overriding descriptor | 20 | 0.1% |


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
|     deferred | 1,492,000 | 2.6% |
|          hit | 56,572,880 | 97.4% |
|         miss | 2,880 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,300 | 20.0% |
| Failure | 9,220 | 80.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 7,380 | 80.0% |
| bytearray int | 840 | 9.1% |
| out of range | 780 | 8.5% |
| other | 220 | 2.4% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,864,340 | 1.4% |
|          hit | 335,824,980 | 94.2% |
|         miss | 15,164,880 | 4.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 301,880 | 56.8% |
| Failure | 229,740 | 43.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 162,380 | 70.7% |
| tuple | 56,100 | 24.4% |
| mapping | 7,620 | 3.3% |
| dict | 2,960 | 1.3% |
| other | 660 | 0.3% |
| set | 20 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,620 | 0.0% |
|          hit | 50,125,200 | 100.0% |
|         miss | 3,160 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,700 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 5,033,325,260 | 51.6% |
| Not specialized | 997,004,440 | 10.2% |
| Specialized hits | 3,202,006,600 | 32.8% |
| Specialized misses | 515,179,640 | 5.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 192,488,060 | 48.0% |
| CALL | 82,007,560 | 20.5% |
| FOR_ITER | 59,862,720 | 14.9% |
| BINARY_OP | 28,293,240 | 7.1% |
| STORE_ATTR | 28,021,680 | 7.0% |
| TO_BOOL | 4,864,340 | 1.2% |
| COMPARE_OP | 2,298,700 | 0.6% |
| BINARY_SUBSCR | 1,558,400 | 0.4% |
| STORE_SUBSCR | 1,492,000 | 0.4% |
| LOAD_GLOBAL | 32,440 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 134,235,800 | 26.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 113,764,800 | 22.1% |
| STORE_ATTR_INSTANCE_VALUE | 71,892,240 | 14.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 62,880,620 | 12.2% |
| LOAD_ATTR_SLOT | 47,107,640 | 9.1% |
| FOR_ITER_LIST | 17,554,540 | 3.4% |
| FOR_ITER_TUPLE | 17,549,820 | 3.4% |
| CALL_PY_EXACT_ARGS | 12,212,820 | 2.4% |
| TO_BOOL_NONE | 8,179,260 | 1.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,019,060 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 53,608,420 | 11.5% |
| Calls to Python functions inlined | 411,463,620 | 88.5% |
| Calls via PyEval_EvalFrame (total) | 53,608,420 | 11.5% |
| Calls via PyEval_EvalFrame (vector) | 53,192,800 | 11.4% |
| Calls via PyEval_EvalFrame (generator) | 415,620 | 0.1% |
| Calls via PyEval_EvalFrame (legacy) | 6,080 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 53,179,760 | 11.4% |
| Calls via PyEval_EvalFrame (build class) | 6,960 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 18,291,280 | 3.9% |
| Calls via PyEval_EvalFrame (function ex) | 2,438,740 | 0.5% |
| Calls via PyEval_EvalFrame (api) | 11,531,860 | 2.5% |
| Calls via PyEval_EvalFrame (method) | 200 | 0.0% |
| Frame objects created | 12,809,380 | 2.8% |
| Frames pushed | 308,932,760 | 66.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 370,504,720 | 30.3% |
| Frees to freelist | 373,450,560 |  |
| Allocations | 852,503,200 | 69.7% |
| Allocations to 512 bytes | 851,337,260 | 69.6% |
| Allocations to 4 kbytes | 701,180 | 0.1% |
| Allocations over 4 kbytes | 464,760 | 0.0% |
| Frees | 896,123,879 |  |
| New values | 10,554,780 |  |
| Interpreter increfs | 4,610,947,680 | 62.6% |
| Interpreter decrefs | 5,664,166,900 | 68.2% |
| Increfs | 2,753,489,209 | 37.4% |
| Decrefs | 2,644,187,031 | 31.8% |
| Materialize dict (on request) | 113,800 | 1.1% |
| Materialize dict (new key) | 150,400 | 1.4% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 78,600 | 0.7% |
| Method cache hits | 590,924,702 |  |
| Method cache misses | 47,696,578 |  |
| Method cache collisions | 50,930,033 |  |
| Method cache dunder hits | 286,114,383 |  |
| Method cache dunder misses | 3,257,157 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 91,000 | 43,181,360 | 1,146,357,040 |
| 1 | 8,260 | 22,676,340 | 487,715,680 |
| 2 | 740 | 30,203,960 | 623,388,520 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 3,295,980 |  |
| Traces created | 5,100 | 0.2% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 20 | 0.0% |
| Trace too long | 200 | 0.0% |
| Trace too short | 3,290,880 | 99.8% |
| Inner loop found | 320 | 0.0% |
| Recursive call | 80 | 0.0% |
| Traces executed | 189,987,940 |  |
| Uops executed | 2,882,944,860 | 15.17 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 80 | 1.6% |
| <= 16 | 540 | 10.6% |
| <= 32 | 1,940 | 38.0% |
| <= 64 | 1,660 | 32.5% |
| <= 128 | 880 | 17.3% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 20 | 0.4% |
| <= 8 | 220 | 4.3% |
| <= 16 | 600 | 11.8% |
| <= 32 | 2,140 | 42.0% |
| <= 64 | 1,560 | 30.6% |
| <= 128 | 560 | 11.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 11,225,120 | 5.9% |
| <= 4 | 2,484,020 | 1.3% |
| <= 8 | 59,728,680 | 31.4% |
| <= 16 | 72,170,240 | 38.0% |
| <= 32 | 35,521,460 | 18.7% |
| <= 64 | 5,322,580 | 2.8% |
| <= 128 | 2,799,320 | 1.5% |
| <= 256 | 538,440 | 0.3% |
| <= 512 | 39,000 | 0.0% |
| <= 1,024 | 74,560 | 0.0% |
| <= 2,048 | 76,460 | 0.0% |
| <= 4,096 | 2,520 | 0.0% |
| <= 8,192 | 2,660 | 0.0% |
| <= 16,384 | 1,200 | 0.0% |
| <= 32,768 | 800 | 0.0% |
| <= 65,536 | 560 | 0.0% |
| <= 131,072 | 320 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 2,914,720 |
| FOR_ITER_GEN | 375,040 |
| LOAD_ATTR | 1,400 |
| BINARY_SUBSCR_GETITEM | 500 |
| CALL | 420 |
| CALL_PY_WITH_DEFAULTS | 300 |
| BINARY_OP | 240 |
| CALL_LIST_APPEND | 200 |
| CALL_FUNCTION_EX | 140 |
| CALL_KW | 140 |
| BINARY_SUBSCR | 100 |
| YIELD_VALUE | 100 |
| CALL_ALLOC_AND_ENTER_INIT | 80 |
| BINARY_OP_INPLACE_ADD_UNICODE | 40 |
| STORE_SUBSCR | 40 |
| TO_BOOL | 20 |
| COMPARE_OP | 20 |
| STORE_ATTR | 20 |


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
Stats gathered on: 2023-11-02
