
# Pystats results

- benchmark: mypy2
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 3,049,755,620 | 20.5% | 20.5% |  |
| LOAD_CONST | 734,916,520 | 4.9% | 25.5% |  |
| RESUME_CHECK | 702,446,024 | 4.7% | 30.2% | 0.0% |
| LOAD_GLOBAL_MODULE | 642,006,280 | 4.3% | 34.5% | 0.0% |
| STORE_ATTR_SLOT | 612,308,485 | 4.1% | 38.7% | 21.5% |
| LOAD_FAST_LOAD_FAST | 586,827,360 | 4.0% | 42.6% |  |
| LOAD_GLOBAL_BUILTIN | 575,162,532 | 3.9% | 46.5% | 0.0% |
| POP_JUMP_IF_FALSE | 571,633,194 | 3.8% | 50.3% |  |
| STORE_FAST | 556,574,852 | 3.7% | 54.1% |  |
| LOAD_ATTR_SLOT | 515,001,483 | 3.5% | 57.5% | 1.6% |
| CALL_PY_EXACT_ARGS | 447,268,004 | 3.0% | 60.6% | 10.1% |
| TO_BOOL_BOOL | 429,813,218 | 2.9% | 63.4% | 0.0% |
| RETURN_VALUE | 397,495,284 | 2.7% | 66.1% |  |
| RETURN_CONST | 300,081,436 | 2.0% | 68.1% |  |
| CALL_ISINSTANCE | 292,112,904 | 2.0% | 70.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 276,823,887 | 1.9% | 72.0% | 21.0% |
| POP_JUMP_IF_TRUE | 236,483,772 | 1.6% | 73.6% |  |
| POP_TOP | 222,201,088 | 1.5% | 75.1% |  |
| FOR_ITER_LIST | 171,381,123 | 1.2% | 76.2% | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 166,315,028 | 1.1% | 77.3% | 3.5% |
| JUMP_BACKWARD | 140,769,840 | 0.9% | 78.3% |  |
| LOAD_DEREF | 132,325,028 | 0.9% | 79.2% |  |
| GET_ITER | 122,317,836 | 0.8% | 80.0% |  |
| INTERPRETER_EXIT | 120,924,496 | 0.8% | 80.8% |  |
| BINARY_SUBSCR_DICT | 120,771,000 | 0.8% | 81.6% |  |
| LOAD_ATTR | 117,129,076 | 0.8% | 82.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 116,205,196 | 0.8% | 83.2% | 12.6% |
| CONTAINS_OP | 101,477,708 | 0.7% | 83.9% |  |
| POP_JUMP_IF_NOT_NONE | 101,095,780 | 0.7% | 84.6% |  |
| COPY_FREE_VARS | 94,077,000 | 0.6% | 85.2% |  |
| SWAP | 88,050,020 | 0.6% | 85.8% |  |
| POP_JUMP_IF_NONE | 87,541,120 | 0.6% | 86.4% |  |
| LOAD_SUPER_ATTR_METHOD | 86,102,020 | 0.6% | 87.0% |  |
| BUILD_LIST | 85,187,720 | 0.6% | 87.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 78,011,580 | 0.5% | 88.1% | 2.2% |
| CALL_KW | 76,507,100 | 0.5% | 88.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 69,000,900 | 0.5% | 89.0% | 8.0% |
| CALL | 68,559,900 | 0.5% | 89.5% |  |
| IS_OP | 57,216,100 | 0.4% | 89.9% |  |
| COMPARE_OP_STR | 55,535,451 | 0.4% | 90.3% | 0.2% |
| NOP | 53,483,620 | 0.4% | 90.6% |  |
| COPY | 50,943,448 | 0.3% | 91.0% |  |
| JUMP_FORWARD | 47,470,840 | 0.3% | 91.3% |  |
| TO_BOOL_LIST | 46,436,540 | 0.3% | 91.6% | 0.7% |
| COMPARE_OP | 43,015,915 | 0.3% | 91.9% |  |
| COMPARE_OP_INT | 42,888,293 | 0.3% | 92.2% | 1.9% |
| BINARY_SUBSCR | 40,857,260 | 0.3% | 92.4% |  |
| CALL_BUILTIN_CLASS | 40,404,464 | 0.3% | 92.7% |  |
| PUSH_NULL | 39,099,940 | 0.3% | 93.0% |  |
| EXTENDED_ARG | 38,420,800 | 0.3% | 93.2% |  |
| FOR_ITER | 37,924,016 | 0.3% | 93.5% |  |
| STORE_FAST_STORE_FAST | 36,299,600 | 0.2% | 93.7% |  |
| CALL_LEN | 36,185,500 | 0.2% | 94.0% |  |
| TO_BOOL_NONE | 35,450,001 | 0.2% | 94.2% | 7.7% |
| FOR_ITER_TUPLE | 35,283,561 | 0.2% | 94.5% | 5.6% |
| MAKE_CELL | 33,283,980 | 0.2% | 94.7% |  |
| BUILD_TUPLE | 32,298,014 | 0.2% | 94.9% |  |
| BINARY_SUBSCR_LIST_INT | 32,238,460 | 0.2% | 95.1% | 0.0% |
| CALL_LIST_APPEND | 32,144,400 | 0.2% | 95.3% |  |
| LOAD_ATTR_WITH_HINT | 30,994,800 | 0.2% | 95.5% | 2.1% |
| MAP_ADD | 30,837,200 | 0.2% | 95.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 30,555,060 | 0.2% | 96.0% | 27.2% |
| LIST_APPEND | 29,310,840 | 0.2% | 96.2% |  |
| TO_BOOL_ALWAYS_TRUE | 29,231,859 | 0.2% | 96.4% | 13.2% |
| LOAD_ATTR_MODULE | 29,143,940 | 0.2% | 96.5% | 0.0% |
| LOAD_FAST_AND_CLEAR | 28,036,860 | 0.2% | 96.7% |  |
| LOAD_ATTR_PROPERTY | 27,344,970 | 0.2% | 96.9% | 6.6% |
| UNARY_NOT | 26,494,360 | 0.2% | 97.1% |  |
| CALL_PY_WITH_DEFAULTS | 20,721,240 | 0.1% | 97.2% | 2.1% |
| TO_BOOL | 20,402,260 | 0.1% | 97.4% |  |
| CALL_TUPLE_1 | 20,335,316 | 0.1% | 97.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,757,880 | 0.1% | 97.6% |  |
| CALL_BUILTIN_O | 18,076,150 | 0.1% | 97.8% | 7.3% |
| STORE_FAST_LOAD_FAST | 16,387,080 | 0.1% | 97.9% |  |
| CALL_BUILTIN_FAST | 15,473,720 | 0.1% | 98.0% | 0.0% |
| LOAD_ATTR_CLASS | 14,901,860 | 0.1% | 98.1% | 2.4% |
| UNPACK_SEQUENCE_LIST | 14,626,920 | 0.1% | 98.2% |  |
| FOR_ITER_RANGE | 12,928,540 | 0.1% | 98.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 12,157,680 | 0.1% | 98.3% | 0.0% |
| STORE_ATTR | 11,622,320 | 0.1% | 98.4% |  |
| CALL_TYPE_1 | 11,593,340 | 0.1% | 98.5% |  |
| TO_BOOL_STR | 11,541,820 | 0.1% | 98.6% | 3.2% |
| BUILD_MAP | 11,315,160 | 0.1% | 98.7% |  |
| BINARY_SUBSCR_TUPLE_INT | 11,290,460 | 0.1% | 98.7% |  |
| DELETE_ATTR | 11,254,400 | 0.1% | 98.8% |  |
| YIELD_VALUE | 11,219,124 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_UNICODE | 9,386,440 | 0.1% | 98.9% |  |
| MAKE_FUNCTION | 8,559,200 | 0.1% | 99.0% |  |
| BINARY_OP_ADD_INT | 8,092,000 | 0.1% | 99.1% | 0.8% |
| CALL_FUNCTION_EX | 7,966,320 | 0.1% | 99.1% |  |
| RETURN_GENERATOR | 7,785,480 | 0.1% | 99.2% |  |
| BINARY_OP_SUBTRACT_INT | 7,016,520 | 0.0% | 99.2% |  |
| CALL_ALLOC_AND_ENTER_INIT | 6,667,940 | 0.0% | 99.3% | 0.1% |
| EXIT_INIT_CHECK | 6,658,880 | 0.0% | 99.3% |  |
| BINARY_SLICE | 6,339,340 | 0.0% | 99.3% |  |
| SET_FUNCTION_ATTRIBUTE | 5,281,920 | 0.0% | 99.4% |  |
| STORE_SUBSCR_DICT | 5,258,460 | 0.0% | 99.4% |  |
| BINARY_OP | 4,890,400 | 0.0% | 99.5% |  |
| STORE_DEREF | 4,761,020 | 0.0% | 99.5% |  |
| CHECK_EXC_MATCH | 4,152,160 | 0.0% | 99.5% |  |
| POP_EXCEPT | 4,152,160 | 0.0% | 99.5% |  |
| PUSH_EXC_INFO | 4,152,160 | 0.0% | 99.6% |  |
| SET_ADD | 4,116,880 | 0.0% | 99.6% |  |
| DICT_MERGE | 3,864,720 | 0.0% | 99.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,801,820 | 0.0% | 99.6% | 0.0% |
| STORE_SUBSCR | 3,771,940 | 0.0% | 99.7% |  |
| CALL_STR_1 | 3,485,860 | 0.0% | 99.7% |  |
| FORMAT_SIMPLE | 3,445,440 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 3,271,980 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,047,200 | 0.0% | 99.8% | 10.9% |
| LOAD_FAST_CHECK | 2,822,800 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_GETITEM | 2,792,220 | 0.0% | 99.8% | 0.0% |
| BEFORE_WITH | 2,676,160 | 0.0% | 99.8% |  |
| IMPORT_FROM | 2,427,840 | 0.0% | 99.8% |  |
| BUILD_STRING | 2,412,320 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TUPLE | 2,203,620 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 2,035,820 | 0.0% | 99.9% | 4.2% |
| IMPORT_NAME | 1,983,200 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 1,954,580 | 0.0% | 99.9% |  |
| BUILD_SET | 1,886,160 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 1,643,940 | 0.0% | 99.9% | 3.1% |
| FOR_ITER_GEN | 1,327,900 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_STR_INT | 1,274,360 | 0.0% | 99.9% | 0.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,148,300 | 0.0% | 100.0% | 1.7% |
| LOAD_SUPER_ATTR_ATTR | 1,083,160 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,069,720 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 573,120 | 0.0% | 100.0% |  |
| RERAISE | 543,680 | 0.0% | 100.0% |  |
| SEND_GEN | 460,644 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 433,540 | 0.0% | 100.0% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 364,704 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 339,600 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 293,220 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 287,820 | 0.0% | 100.0% | 22.1% |
| LOAD_GLOBAL | 242,840 | 0.0% | 100.0% |  |
| DELETE_FAST | 201,920 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 193,100 | 0.0% | 100.0% |  |
| LIST_EXTEND | 150,540 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 144,780 | 0.0% | 100.0% |  |
| END_SEND | 96,000 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 96,000 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 93,500 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 67,960 | 0.0% | 100.0% |  |
| END_FOR | 54,080 | 0.0% | 100.0% |  |
| RESUME | 40,880 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 32,920 | 0.0% | 100.0% |  |
| BUILD_SLICE | 18,360 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 6,120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 5,480 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 4,820 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 2,880 | 0.0% | 100.0% |  |
| STORE_NAME | 2,240 | 0.0% | 100.0% |  |
| UNARY_INVERT | 2,140 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,100 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 1,260 | 0.0% | 100.0% |  |
| STORE_SLICE | 960 | 0.0% | 100.0% |  |
| UNPACK_EX | 960 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 520 | 0.0% | 100.0% |  |
| SET_UPDATE | 320 | 0.0% | 100.0% |  |
| SEND | 120 | 0.0% | 100.0% |  |
| SETUP_ANNOTATIONS | 80 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 456,167,506 | 3.1% | 3.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 399,377,698 | 2.7% | 5.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 389,121,428 | 2.6% | 8.4% |
| LOAD_FAST STORE_ATTR_SLOT | 360,212,818 | 2.4% | 10.8% |
| RESUME_CHECK LOAD_FAST | 305,835,904 | 2.1% | 12.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 293,987,466 | 2.0% | 14.8% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 285,318,050 | 1.9% | 16.8% |
| LOAD_CONST LOAD_FAST | 283,877,440 | 1.9% | 18.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 278,562,464 | 1.9% | 20.6% |
| STORE_FAST LOAD_FAST | 278,120,532 | 1.9% | 22.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 267,431,888 | 1.8% | 24.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 248,734,180 | 1.7% | 25.9% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 242,747,684 | 1.6% | 27.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 201,907,112 | 1.4% | 28.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 175,488,076 | 1.2% | 30.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 173,116,120 | 1.2% | 31.2% |
| STORE_ATTR_SLOT LOAD_CONST | 170,370,120 | 1.1% | 32.4% |
| LOAD_FAST LOAD_CONST | 169,787,500 | 1.1% | 33.5% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 141,429,960 | 1.0% | 34.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 136,139,928 | 0.9% | 35.4% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 130,605,368 | 0.9% | 36.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 128,748,300 | 0.9% | 37.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 125,110,920 | 0.8% | 38.0% |
| STORE_ATTR_SLOT RETURN_CONST | 120,940,980 | 0.8% | 38.8% |
| LOAD_FAST RETURN_VALUE | 119,615,320 | 0.8% | 39.6% |
| STORE_ATTR_SLOT LOAD_FAST | 112,444,658 | 0.8% | 40.4% |
| RETURN_CONST POP_TOP | 105,768,380 | 0.7% | 41.1% |
| LOAD_CONST BINARY_SUBSCR_DICT | 103,454,600 | 0.7% | 41.8% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 103,310,100 | 0.7% | 42.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 102,188,032 | 0.7% | 43.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 102,051,030 | 0.7% | 43.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 95,343,200 | 0.6% | 44.5% |
| POP_TOP LOAD_FAST | 93,804,748 | 0.6% | 45.1% |
| FOR_ITER_LIST STORE_FAST | 93,718,682 | 0.6% | 45.7% |
| COPY_FREE_VARS RESUME_CHECK | 93,106,780 | 0.6% | 46.4% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 92,147,960 | 0.6% | 47.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 91,985,098 | 0.6% | 47.6% |
| RETURN_VALUE STORE_FAST | 90,360,600 | 0.6% | 48.2% |
| LOAD_DEREF LOAD_FAST | 89,159,220 | 0.6% | 48.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 89,095,080 | 0.6% | 49.4% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 86,099,620 | 0.6% | 50.0% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 82,078,260 | 0.6% | 50.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 81,221,620 | 0.5% | 51.1% |
| RETURN_VALUE RETURN_VALUE | 80,685,484 | 0.5% | 51.6% |
| LOAD_FAST LOAD_FAST | 78,925,760 | 0.5% | 52.2% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 78,453,460 | 0.5% | 52.7% |
| LOAD_CONST CALL_KW | 76,507,100 | 0.5% | 53.2% |
| LOAD_FAST LOAD_ATTR | 75,920,556 | 0.5% | 53.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 74,559,272 | 0.5% | 54.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 71,744,502 | 0.5% | 54.7% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 71,702,960 | 0.5% | 55.2% |
| CACHE RESUME_CHECK | 69,749,656 | 0.5% | 55.7% |
| RESUME_CHECK RETURN_CONST | 67,713,220 | 0.5% | 56.1% |
| RETURN_CONST INTERPRETER_EXIT | 61,992,140 | 0.4% | 56.5% |
| RETURN_CONST LOAD_FAST | 61,621,760 | 0.4% | 57.0% |
| LOAD_ATTR_SLOT LOAD_FAST | 61,126,652 | 0.4% | 57.4% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 60,571,320 | 0.4% | 57.8% |
| LOAD_ATTR LOAD_FAST | 54,495,868 | 0.4% | 58.1% |
| LOAD_CONST LOAD_CONST | 54,165,680 | 0.4% | 58.5% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 53,988,940 | 0.4% | 58.9% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 53,583,440 | 0.4% | 59.2% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 50,336,780 | 0.3% | 59.6% |
| RETURN_VALUE LOAD_FAST | 50,110,900 | 0.3% | 59.9% |
| RETURN_VALUE INTERPRETER_EXIT | 49,258,316 | 0.3% | 60.2% |
| LOAD_ATTR_SLOT STORE_FAST | 48,858,820 | 0.3% | 60.6% |
| LOAD_FAST CONTAINS_OP | 47,954,520 | 0.3% | 60.9% |
| LOAD_ATTR_SLOT GET_ITER | 47,954,056 | 0.3% | 61.2% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 47,552,680 | 0.3% | 61.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 47,201,680 | 0.3% | 61.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 47,117,920 | 0.3% | 62.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 46,079,080 | 0.3% | 62.5% |
| GET_ITER FOR_ITER_LIST | 45,440,610 | 0.3% | 62.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 44,247,240 | 0.3% | 63.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 44,219,300 | 0.3% | 63.4% |
| CACHE COPY_FREE_VARS | 43,492,280 | 0.3% | 63.7% |
| CALL_KW RESUME_CHECK | 43,426,700 | 0.3% | 64.0% |
| RETURN_CONST RETURN_VALUE | 42,841,600 | 0.3% | 64.3% |
| POP_JUMP_IF_NONE LOAD_FAST | 42,558,520 | 0.3% | 64.5% |
| LOAD_GLOBAL_MODULE IS_OP | 41,729,520 | 0.3% | 64.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 41,512,000 | 0.3% | 65.1% |
| LOAD_CONST COMPARE_OP_STR | 39,916,496 | 0.3% | 65.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 39,735,860 | 0.3% | 65.6% |
| COPY TO_BOOL_BOOL | 38,567,808 | 0.3% | 65.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 38,479,700 | 0.3% | 66.2% |
| IS_OP POP_JUMP_IF_FALSE | 38,157,920 | 0.3% | 66.4% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 38,102,120 | 0.3% | 66.7% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 38,082,020 | 0.3% | 66.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 36,619,400 | 0.2% | 67.2% |
| LOAD_ATTR_SLOT RETURN_VALUE | 36,490,462 | 0.2% | 67.4% |
| POP_TOP LOAD_FAST_LOAD_FAST | 35,282,040 | 0.2% | 67.7% |
| LOAD_FAST TO_BOOL_LIST | 35,112,220 | 0.2% | 67.9% |
| TO_BOOL_LIST POP_JUMP_IF_TRUE | 34,884,940 | 0.2% | 68.1% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 34,726,545 | 0.2% | 68.4% |
| RETURN_VALUE POP_TOP | 34,534,520 | 0.2% | 68.6% |
| LOAD_FAST TO_BOOL_BOOL | 34,274,380 | 0.2% | 68.8% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 34,219,120 | 0.2% | 69.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 33,331,524 | 0.2% | 69.3% |
| LOAD_ATTR_SLOT POP_JUMP_IF_NONE | 32,723,920 | 0.2% | 69.5% |
| BUILD_LIST STORE_FAST | 32,656,280 | 0.2% | 69.7% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 32,506,240 | 0.2% | 69.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,909,300 | 77.4% |
| BINARY_OP_SUBTRACT_INT | 890,220 | 14.0% |
| LOAD_FAST | 400,280 | 6.3% |
| BINARY_OP_ADD_INT | 101,380 | 1.6% |
| LOAD_ATTR_SLOT | 23,980 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,339,560 | 36.9% |
| CALL_PY_EXACT_ARGS | 890,980 | 14.1% |
| STORE_FAST | 700,940 | 11.1% |
| GET_ITER | 646,720 | 10.2% |
| BINARY_OP_ADD_UNICODE | 450,740 | 7.1% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 69,749,656 | 57.7% |
| COPY_FREE_VARS | 43,492,280 | 36.0% |
| POP_TOP | 7,592,620 | 6.3% |
| RETURN_GENERATOR | 93,440 | 0.1% |
| PUSH_EXC_INFO | 42,880 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,594,680 | 97.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 48,040 | 1.8% |
| CALL | 33,300 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,381,300 | 89.0% |
| STORE_FAST | 294,860 | 11.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 329,000 | 57.4% |
| RETURN_VALUE | 197,040 | 34.4% |
| BUILD_STRING | 44,360 | 7.7% |
| LOAD_FAST_LOAD_FAST | 1,880 | 0.3% |
| BINARY_SUBSCR_STR_INT | 400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 524,520 | 91.5% |
| LOAD_FAST | 46,400 | 8.1% |
| JUMP_FORWARD | 1,260 | 0.2% |
| LOAD_FAST_LOAD_FAST | 940 | 0.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,217,080 | 49.5% |
| LOAD_FAST_LOAD_FAST | 15,043,740 | 36.8% |
| LOAD_FAST | 3,627,600 | 8.9% |
| LOAD_GLOBAL_MODULE | 1,199,040 | 2.9% |
| COPY | 287,400 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,180,880 | 42.1% |
| CONTAINS_OP | 4,464,740 | 10.9% |
| LOAD_CONST | 4,422,640 | 10.8% |
| LOAD_FAST | 3,199,660 | 7.8% |
| RETURN_VALUE | 2,830,040 | 6.9% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,134,280 | 99.6% |
| BUILD_TUPLE | 16,640 | 0.4% |
| LOAD_GLOBAL_MODULE | 900 | 0.0% |
| LOAD_GLOBAL | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,152,160 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60,800 | 65.0% |
| BUILD_SLICE | 17,280 | 18.5% |
| LOAD_FAST | 12,540 | 13.4% |
| LOAD_FAST_LOAD_FAST | 2,880 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 73,280 | 78.4% |
| LOAD_DEREF | 17,280 | 18.5% |
| RETURN_CONST | 1,920 | 2.1% |
| LOAD_FAST | 640 | 0.7% |
| LOAD_CONST | 320 | 0.3% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 54,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 50,560 | 93.5% |
| LOAD_FAST | 2,880 | 5.3% |
| EXTENDED_ARG | 320 | 0.6% |
| JUMP_BACKWARD | 320 | 0.6% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 96,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 96,000 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,658,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,658,880 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,616,820 | 76.0% |
| RETURN_VALUE | 413,360 | 12.0% |
| BINARY_SUBSCR_TUPLE_INT | 281,600 | 8.2% |
| CONVERT_VALUE | 67,960 | 2.0% |
| LOAD_ATTR_SLOT | 38,660 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,367,200 | 68.7% |
| BUILD_STRING | 1,078,240 | 31.3% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,560 | 88.9% |
| LOAD_CONST | 320 | 11.1% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 47,954,056 | 39.2% |
| LOAD_FAST | 29,361,800 | 24.0% |
| CALL_BUILTIN_CLASS | 19,075,820 | 15.6% |
| BINARY_SUBSCR_DICT | 12,587,800 | 10.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,710,460 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 45,440,610 | 37.1% |
| LOAD_FAST_AND_CLEAR | 26,782,360 | 21.9% |
| FOR_ITER_TUPLE | 19,375,415 | 15.8% |
| FOR_ITER | 14,642,031 | 12.0% |
| FOR_ITER_RANGE | 5,973,100 | 4.9% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 96,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 96,000 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 61,992,140 | 51.3% |
| RETURN_VALUE | 49,258,316 | 40.7% |
| YIELD_VALUE | 9,580,600 | 7.9% |
| RETURN_GENERATOR | 93,440 | 0.1% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 20 | 50.0% |
| STORE_NAME | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 40 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,559,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,373,780 | 51.1% |
| SET_FUNCTION_ATTRIBUTE | 4,110,380 | 48.0% |
| LOAD_CONST | 48,060 | 0.6% |
| LOAD_GLOBAL_MODULE | 14,280 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 7,240 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,141,700 | 28.3% |
| POP_JUMP_IF_TRUE | 14,087,040 | 26.3% |
| POP_JUMP_IF_FALSE | 9,176,600 | 17.2% |
| RESUME_CHECK | 6,691,280 | 12.5% |
| CALL_LIST_APPEND | 2,435,240 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,219,640 | 56.5% |
| LOAD_CONST | 14,777,960 | 27.6% |
| LOAD_GLOBAL_BUILTIN | 4,749,940 | 8.9% |
| LOAD_GLOBAL_MODULE | 3,059,100 | 5.7% |
| LOAD_FAST_LOAD_FAST | 555,500 | 1.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,612,660 | 62.9% |
| SWAP | 1,267,840 | 30.5% |
| COPY | 256,640 | 6.2% |
| STORE_FAST | 13,880 | 0.3% |
| POP_JUMP_IF_FALSE | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,611,700 | 62.9% |
| RETURN_VALUE | 1,267,840 | 30.5% |
| RERAISE | 256,640 | 6.2% |
| JUMP_BACKWARD | 14,520 | 0.3% |
| EXTENDED_ARG | 640 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 105,768,380 | 47.6% |
| RETURN_VALUE | 34,534,520 | 15.5% |
| POP_JUMP_IF_FALSE | 20,713,216 | 9.3% |
| POP_JUMP_IF_TRUE | 17,355,552 | 7.8% |
| RESUME_CHECK | 8,001,720 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,804,748 | 42.2% |
| LOAD_FAST_LOAD_FAST | 35,282,040 | 15.9% |
| JUMP_BACKWARD | 28,889,040 | 13.0% |
| RETURN_CONST | 23,024,760 | 10.4% |
| LOAD_CONST | 8,837,200 | 4.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 2,286,680 | 55.1% |
| LOAD_ATTR_SLOT | 1,263,960 | 30.4% |
| RERAISE | 213,440 | 5.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 205,700 | 5.0% |
| RAISE_VARARGS | 125,760 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,150,580 | 100.0% |
| LOAD_GLOBAL_MODULE | 840 | 0.0% |
| LOAD_GLOBAL | 740 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,668,680 | 50.3% |
| LOAD_ATTR | 8,423,120 | 21.5% |
| LOAD_ATTR_MODULE | 7,201,120 | 18.4% |
| BINARY_SUBSCR_DICT | 1,481,440 | 3.8% |
| LOAD_SUPER_ATTR_ATTR | 1,077,400 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,005,920 | 76.7% |
| LOAD_FAST_LOAD_FAST | 5,628,020 | 14.4% |
| LOAD_GLOBAL_BUILTIN | 2,449,020 | 6.3% |
| CALL | 587,680 | 1.5% |
| LOAD_CONST | 283,120 | 0.7% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,438,240 | 57.0% |
| CALL_FUNCTION_EX | 2,281,920 | 29.3% |
| COPY_FREE_VARS | 967,140 | 12.4% |
| CACHE | 93,440 | 1.2% |
| MAKE_CELL | 2,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 4,748,320 | 61.0% |
| LOAD_FAST | 2,327,360 | 29.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 385,440 | 5.0% |
| GET_YIELD_FROM_ITER | 96,000 | 1.2% |
| CALL | 94,440 | 1.2% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 119,615,320 | 30.1% |
| RETURN_VALUE | 80,685,484 | 20.3% |
| RETURN_CONST | 42,841,600 | 10.8% |
| LOAD_ATTR_SLOT | 36,490,462 | 9.2% |
| CALL | 12,594,440 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 90,360,600 | 22.7% |
| RETURN_VALUE | 80,685,484 | 20.3% |
| LOAD_FAST | 50,110,900 | 12.6% |
| INTERPRETER_EXIT | 49,258,316 | 12.4% |
| POP_TOP | 34,534,520 | 8.7% |


</details>

### SETUP_ANNOTATIONS

<details>
<summary> Successors and predecessors for SETUP_ANNOTATIONS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 40 | 50.0% |
| RESUME | 40 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 50.0% |
| LOAD_NAME | 40 | 50.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,033,640 | 80.4% |
| LOAD_FAST | 346,800 | 9.2% |
| SWAP | 287,400 | 7.6% |
| LOAD_CONST | 79,980 | 2.1% |
| LOAD_ATTR_SLOT | 17,340 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,033,340 | 80.4% |
| LOAD_CONST | 343,480 | 9.1% |
| LOAD_FAST | 240,600 | 6.4% |
| RETURN_CONST | 149,180 | 4.0% |
| STORE_SUBSCR | 2,360 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 9,397,760 | 46.1% |
| LOAD_FAST | 6,953,400 | 34.1% |
| LOAD_ATTR_SLOT | 2,691,820 | 13.2% |
| COPY | 1,088,700 | 5.3% |
| LOAD_ATTR_WITH_HINT | 73,100 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,072,940 | 83.7% |
| POP_JUMP_IF_TRUE | 2,878,620 | 14.1% |
| UNARY_NOT | 294,700 | 1.4% |
| TO_BOOL_BOOL | 48,620 | 0.2% |
| TO_BOOL | 43,940 | 0.2% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,920 | 89.7% |
| LOAD_FAST | 220 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,140 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,013,780 | 51.9% |
| CALL_LEN | 890,520 | 45.6% |
| LOAD_GLOBAL_MODULE | 23,660 | 1.2% |
| CALL | 17,320 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 9,260 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 890,240 | 45.5% |
| COMPARE_OP_INT | 890,200 | 45.5% |
| CALL_PY_EXACT_ARGS | 86,360 | 4.4% |
| RETURN_VALUE | 26,560 | 1.4% |
| BUILD_TUPLE | 23,680 | 1.2% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 23,157,640 | 87.4% |
| TO_BOOL_LIST | 2,525,220 | 9.5% |
| TO_BOOL_STR | 369,580 | 1.4% |
| TO_BOOL | 294,700 | 1.1% |
| TO_BOOL_INT | 139,300 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,021,440 | 52.9% |
| RETURN_VALUE | 9,197,440 | 34.7% |
| COPY | 2,570,340 | 9.7% |
| LOAD_FAST | 456,960 | 1.7% |
| STORE_FAST | 152,320 | 0.6% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 2,644,140 | 54.1% |
| LOAD_FAST | 508,320 | 10.4% |
| BUILD_LIST | 396,800 | 8.1% |
| STORE_FAST | 346,600 | 7.1% |
| LOAD_CONST | 244,080 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,900,760 | 38.9% |
| STORE_FAST | 1,219,440 | 24.9% |
| CALL_PY_EXACT_ARGS | 507,920 | 10.4% |
| LOAD_CONST | 288,380 | 5.9% |
| GET_ITER | 210,600 | 4.3% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 320 | 61.5% |
| STORE_FAST | 140 | 26.9% |
| RETURN_VALUE | 60 | 11.5% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 24,364,960 | 28.6% |
| STORE_FAST | 18,913,560 | 22.2% |
| LOAD_GLOBAL_MODULE | 12,122,780 | 14.2% |
| RESUME_CHECK | 8,691,080 | 10.2% |
| STORE_ATTR_SLOT | 4,211,900 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 32,656,280 | 38.3% |
| SWAP | 24,364,960 | 28.6% |
| CALL | 12,506,840 | 14.7% |
| LOAD_FAST | 8,116,120 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 2,538,120 | 3.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,105,940 | 36.3% |
| LOAD_CONST | 1,666,280 | 14.7% |
| STORE_ATTR_INSTANCE_VALUE | 960,220 | 8.5% |
| RESUME_CHECK | 929,000 | 8.2% |
| POP_JUMP_IF_FALSE | 796,480 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,354,680 | 56.2% |
| STORE_FAST | 1,717,800 | 15.2% |
| LOAD_CONST | 1,611,560 | 14.2% |
| SWAP | 663,080 | 5.9% |
| RETURN_VALUE | 271,360 | 2.4% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,754,320 | 93.0% |
| LOAD_CONST | 109,760 | 5.8% |
| LOAD_FAST | 21,760 | 1.2% |
| POP_JUMP_IF_FALSE | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,754,320 | 93.0% |
| STORE_FAST | 64,320 | 3.4% |
| CALL_PY_EXACT_ARGS | 45,400 | 2.4% |
| BINARY_OP | 11,200 | 0.6% |
| LOAD_CONST | 10,880 | 0.6% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 17,280 | 94.1% |
| BINARY_SUBSCR | 1,080 | 5.9% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,334,080 | 55.3% |
| FORMAT_SIMPLE | 1,078,240 | 44.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 952,400 | 39.5% |
| STORE_FAST | 560,100 | 23.2% |
| RETURN_VALUE | 376,640 | 15.6% |
| LOAD_FAST | 167,720 | 7.0% |
| CALL_PY_EXACT_ARGS | 85,400 | 3.5% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,279,340 | 34.9% |
| LOAD_GLOBAL_MODULE | 5,312,560 | 16.4% |
| LOAD_ATTR_SLOT | 5,109,438 | 15.8% |
| LOAD_FAST_LOAD_FAST | 4,352,280 | 13.5% |
| LOAD_ATTR_INSTANCE_VALUE | 2,366,980 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,312,580 | 25.7% |
| CALL_BUILTIN_O | 5,669,834 | 17.6% |
| CALL_ISINSTANCE | 4,611,160 | 14.3% |
| LOAD_CONST | 4,111,980 | 12.7% |
| LOAD_FAST | 3,557,320 | 11.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,520,480 | 24.1% |
| BUILD_LIST | 12,506,840 | 18.2% |
| LOAD_FAST_LOAD_FAST | 6,962,560 | 10.2% |
| RETURN_VALUE | 6,217,499 | 9.1% |
| LOAD_ATTR_SLOT | 4,534,200 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 27,175,860 | 39.6% |
| RETURN_VALUE | 12,594,440 | 18.4% |
| LIST_APPEND | 7,028,600 | 10.3% |
| RESUME_CHECK | 4,504,360 | 6.6% |
| TO_BOOL_BOOL | 3,683,380 | 5.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 3,864,720 | 48.5% |
| LOAD_FAST | 2,043,280 | 25.6% |
| MAP_ADD | 1,611,200 | 20.2% |
| LOAD_ATTR | 275,200 | 3.5% |
| CALL_INTRINSIC_1 | 144,720 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,034,260 | 50.6% |
| RETURN_GENERATOR | 2,281,920 | 28.6% |
| POP_TOP | 1,082,880 | 13.6% |
| STORE_FAST | 369,280 | 4.6% |
| RESUME_CHECK | 141,800 | 1.8% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 150,220 | 77.8% |
| RERAISE | 42,880 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 144,720 | 74.9% |
| RERAISE | 42,880 | 22.2% |
| BUILD_MAP | 5,500 | 2.8% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 76,507,100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 43,426,700 | 56.8% |
| UNPACK_SEQUENCE_LIST | 14,181,920 | 18.5% |
| RETURN_VALUE | 5,415,940 | 7.1% |
| MAKE_CELL | 4,870,760 | 6.4% |
| CALL_PY_EXACT_ARGS | 3,752,480 | 4.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 18,252,745 | 42.4% |
| LOAD_GLOBAL_MODULE | 8,646,720 | 20.1% |
| LOAD_CONST | 7,735,083 | 18.0% |
| LOAD_ATTR_MODULE | 3,293,580 | 7.7% |
| LOAD_FAST | 2,171,580 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 16,886,760 | 39.3% |
| POP_JUMP_IF_FALSE | 13,624,483 | 31.7% |
| RETURN_VALUE | 8,405,405 | 19.5% |
| POP_JUMP_IF_TRUE | 2,803,040 | 6.5% |
| EXTENDED_ARG | 1,029,600 | 2.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,954,520 | 47.3% |
| LOAD_FAST_LOAD_FAST | 19,735,500 | 19.4% |
| LOAD_ATTR_INSTANCE_VALUE | 10,867,320 | 10.7% |
| LOAD_ATTR_SLOT | 5,409,640 | 5.3% |
| BINARY_SUBSCR | 4,464,740 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 82,078,260 | 80.9% |
| POP_JUMP_IF_TRUE | 15,702,008 | 15.5% |
| RETURN_VALUE | 2,852,620 | 2.8% |
| EXTENDED_ARG | 467,800 | 0.5% |
| COPY | 223,360 | 0.2% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,260 | 99.0% |
| RETURN_CONST | 640 | 0.9% |
| LOAD_GLOBAL_MODULE | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 67,960 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 16,886,760 | 33.1% |
| LOAD_FAST | 6,224,260 | 12.2% |
| CALL_ISINSTANCE | 4,291,560 | 8.4% |
| SWAP | 3,592,320 | 7.1% |
| COMPARE_OP_STR | 3,095,604 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 38,567,808 | 75.7% |
| COMPARE_OP_INT | 3,580,400 | 7.0% |
| TO_BOOL_NONE | 1,804,040 | 3.5% |
| TO_BOOL_STR | 1,511,700 | 3.0% |
| TO_BOOL | 1,088,700 | 2.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 47,552,680 | 50.5% |
| CACHE | 43,492,280 | 46.2% |
| CALL | 1,923,440 | 2.0% |
| CALL_ALLOC_AND_ENTER_INIT | 450,680 | 0.5% |
| CALL_KW | 424,320 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 93,106,780 | 99.0% |
| RETURN_GENERATOR | 967,140 | 1.0% |
| RESUME | 3,080 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,254,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,804,160 | 78.2% |
| NOP | 2,281,920 | 20.3% |
| RETURN_CONST | 168,320 | 1.5% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 201,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 201,280 | 99.7% |
| JUMP_BACKWARD | 640 | 0.3% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,864,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 3,864,720 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,479,440 | 27.3% |
| JUMP_BACKWARD | 8,120,060 | 21.1% |
| GET_ITER | 4,744,880 | 12.3% |
| POP_TOP | 3,534,420 | 9.2% |
| LOAD_ATTR_SLOT | 1,255,320 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,952,980 | 38.9% |
| JUMP_BACKWARD | 6,599,900 | 17.2% |
| FOR_ITER | 6,337,880 | 16.5% |
| FOR_ITER_LIST | 6,147,340 | 16.0% |
| POP_JUMP_IF_NONE | 2,625,280 | 6.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 16,089,695 | 42.4% |
| GET_ITER | 14,642,031 | 38.6% |
| EXTENDED_ARG | 6,337,880 | 16.7% |
| SWAP | 730,800 | 1.9% |
| LOAD_FAST | 82,460 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 13,825,240 | 36.5% |
| STORE_FAST | 5,933,063 | 15.6% |
| RETURN_CONST | 5,604,920 | 14.8% |
| LOAD_FAST | 4,700,443 | 12.4% |
| LOAD_FAST_LOAD_FAST | 1,808,360 | 4.8% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 1,826,360 | 75.2% |
| STORE_FAST | 600,640 | 24.7% |
| STORE_NAME | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,426,560 | 99.9% |
| STORE_NAME | 1,280 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,983,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 1,826,360 | 92.1% |
| STORE_FAST | 156,480 | 7.9% |
| STORE_DEREF | 320 | 0.0% |
| STORE_NAME | 40 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,729,520 | 72.9% |
| LOAD_CONST | 7,374,440 | 12.9% |
| LOAD_FAST | 7,016,180 | 12.3% |
| LOAD_FAST_LOAD_FAST | 890,240 | 1.6% |
| LOAD_ATTR | 95,800 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 38,157,920 | 66.7% |
| POP_JUMP_IF_TRUE | 11,730,800 | 20.5% |
| RETURN_VALUE | 4,099,520 | 7.2% |
| LOAD_FAST | 1,637,440 | 2.9% |
| COPY | 838,420 | 1.5% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 38,082,020 | 27.1% |
| LIST_APPEND | 29,310,840 | 20.8% |
| POP_TOP | 28,889,040 | 20.5% |
| CALL_LIST_APPEND | 9,477,860 | 6.7% |
| POP_JUMP_IF_FALSE | 6,819,640 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 91,985,098 | 65.3% |
| FOR_ITER | 16,089,695 | 11.4% |
| FOR_ITER_TUPLE | 13,154,599 | 9.3% |
| EXTENDED_ARG | 8,120,060 | 5.8% |
| FOR_ITER_RANGE | 5,817,480 | 4.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 364,644 | 100.0% |
| RESUME | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 364,664 | 100.0% |
| SEND | 40 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 14,018,240 | 29.5% |
| LOAD_ATTR_SLOT | 13,640,820 | 28.7% |
| LOAD_FAST | 6,688,760 | 14.1% |
| STORE_ATTR_SLOT | 5,506,940 | 11.6% |
| STORE_FAST | 3,879,100 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,650,700 | 49.8% |
| STORE_FAST | 14,581,440 | 30.7% |
| MAP_ADD | 6,275,520 | 13.2% |
| LOAD_CONST | 1,026,560 | 2.2% |
| LOAD_GLOBAL_MODULE | 958,506 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 15,534,940 | 53.0% |
| CALL | 7,028,600 | 24.0% |
| CALL_BUILTIN_O | 2,448,620 | 8.4% |
| LOAD_FAST | 1,868,560 | 6.4% |
| LOAD_ATTR_SLOT | 567,840 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 29,310,840 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 121,980 | 81.0% |
| RETURN_VALUE | 18,880 | 12.5% |
| BINARY_SLICE | 8,960 | 6.0% |
| LOAD_CONST | 320 | 0.2% |
| STORE_FAST | 320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 150,220 | 99.8% |
| LOAD_CONST | 320 | 0.2% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 75,920,556 | 64.8% |
| LOAD_GLOBAL_MODULE | 31,887,520 | 27.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,631,340 | 2.2% |
| LOAD_FAST_LOAD_FAST | 2,057,360 | 1.8% |
| CALL_TYPE_1 | 1,443,800 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,495,868 | 46.5% |
| LOAD_FAST_LOAD_FAST | 11,093,100 | 9.5% |
| TO_BOOL | 9,397,760 | 8.0% |
| PUSH_NULL | 8,423,120 | 7.2% |
| CALL_PY_EXACT_ARGS | 6,827,680 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 170,370,120 | 23.2% |
| LOAD_FAST | 169,787,500 | 23.1% |
| LOAD_CONST | 54,165,680 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 28,809,500 | 3.9% |
| MAP_ADD | 27,390,400 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 283,877,440 | 38.6% |
| BINARY_SUBSCR_DICT | 103,454,600 | 14.1% |
| CALL_KW | 76,507,100 | 10.4% |
| LOAD_CONST | 54,165,680 | 7.4% |
| COMPARE_OP_STR | 39,916,496 | 5.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 92,147,960 | 69.6% |
| LOAD_DEREF | 13,225,280 | 10.0% |
| LOAD_FAST | 6,422,368 | 4.9% |
| LOAD_GLOBAL_MODULE | 5,120,840 | 3.9% |
| POP_JUMP_IF_FALSE | 2,648,152 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,159,220 | 67.4% |
| LOAD_DEREF | 13,225,280 | 10.0% |
| LOAD_ATTR_SLOT | 7,776,800 | 5.9% |
| LOAD_CONST | 4,602,120 | 3.5% |
| LOAD_FAST_LOAD_FAST | 3,642,880 | 2.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 399,377,698 | 13.1% |
| RESUME_CHECK | 305,835,904 | 10.0% |
| LOAD_CONST | 283,877,440 | 9.3% |
| STORE_FAST | 278,120,532 | 9.1% |
| POP_JUMP_IF_FALSE | 267,431,888 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 456,167,506 | 15.0% |
| STORE_ATTR_SLOT | 360,212,818 | 11.8% |
| LOAD_GLOBAL_MODULE | 278,562,464 | 9.1% |
| LOAD_ATTR_METHOD_NO_DICT | 201,907,112 | 6.6% |
| CALL_PY_EXACT_ARGS | 173,116,120 | 5.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 26,782,360 | 95.5% |
| LOAD_FAST_AND_CLEAR | 1,254,500 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 26,771,480 | 95.5% |
| LOAD_FAST_AND_CLEAR | 1,254,500 | 4.5% |
| MAKE_CELL | 10,880 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,156,080 | 76.4% |
| POP_JUMP_IF_FALSE | 305,600 | 10.8% |
| LOAD_GLOBAL_BUILTIN | 269,360 | 9.5% |
| POP_JUMP_IF_TRUE | 24,640 | 0.9% |
| LOAD_FAST_CHECK | 21,440 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 2,008,560 | 71.2% |
| LOAD_ATTR_SLOT | 177,560 | 6.3% |
| EXTENDED_ARG | 162,880 | 5.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 152,360 | 5.4% |
| TO_BOOL_BOOL | 100,080 | 3.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 141,429,960 | 24.1% |
| LOAD_SUPER_ATTR_METHOD | 71,702,960 | 12.2% |
| RESUME_CHECK | 60,571,320 | 10.3% |
| LOAD_GLOBAL_MODULE | 47,201,680 | 8.0% |
| STORE_FAST | 47,117,920 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 248,734,180 | 42.4% |
| CALL_PY_EXACT_ARGS | 103,310,100 | 17.6% |
| STORE_ATTR_INSTANCE_VALUE | 44,219,300 | 7.5% |
| LOAD_FAST | 39,735,860 | 6.8% |
| CONTAINS_OP | 19,735,500 | 3.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,600 | 18.8% |
| POP_JUMP_IF_FALSE | 44,630 | 18.4% |
| STORE_FAST | 38,318 | 15.8% |
| RESUME_CHECK | 12,440 | 5.1% |
| RESUME | 12,340 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 75,380 | 31.0% |
| LOAD_FAST | 52,680 | 21.7% |
| LOAD_GLOBAL_BUILTIN | 46,100 | 19.0% |
| CALL | 26,740 | 11.0% |
| LOAD_ATTR | 11,580 | 4.8% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,080 | 51.4% |
| LOAD_NAME | 580 | 27.6% |
| STORE_NAME | 200 | 9.5% |
| STORE_SUBSCR | 100 | 4.8% |
| SETUP_ANNOTATIONS | 40 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 580 | 27.6% |
| LOAD_NAME | 580 | 27.6% |
| BUILD_TUPLE | 380 | 18.1% |
| BINARY_SUBSCR | 300 | 14.3% |
| GET_ITER | 80 | 3.8% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 2,400 | 49.8% |
| CALL | 1,040 | 21.6% |
| LOAD_FAST | 680 | 14.1% |
| LOAD_FAST_LOAD_FAST | 420 | 8.7% |
| LOAD_GLOBAL | 180 | 3.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 21,853,440 | 65.7% |
| CALL_PY_EXACT_ARGS | 4,968,720 | 14.9% |
| CALL_KW | 4,870,760 | 14.6% |
| BINARY_SUBSCR_GETITEM | 940,780 | 2.8% |
| CALL_PY_WITH_DEFAULTS | 585,560 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 21,853,440 | 65.7% |
| RESUME_CHECK | 11,415,460 | 34.3% |
| SWAP | 10,880 | 0.0% |
| RETURN_GENERATOR | 2,560 | 0.0% |
| RESUME | 1,640 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,114,540 | 68.5% |
| JUMP_FORWARD | 6,275,520 | 20.4% |
| CALL_BUILTIN_CLASS | 1,674,520 | 5.4% |
| CALL_BUILTIN_FAST | 817,580 | 2.7% |
| LOAD_FAST_LOAD_FAST | 445,440 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,390,400 | 88.8% |
| JUMP_BACKWARD | 1,835,600 | 6.0% |
| CALL_FUNCTION_EX | 1,611,200 | 5.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 293,987,466 | 51.4% |
| CONTAINS_OP | 82,078,260 | 14.4% |
| IS_OP | 38,157,920 | 6.7% |
| COMPARE_OP_INT | 26,405,765 | 4.6% |
| TO_BOOL_ALWAYS_TRUE | 25,235,555 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 267,431,888 | 46.8% |
| LOAD_GLOBAL_BUILTIN | 136,139,928 | 23.8% |
| LOAD_GLOBAL_MODULE | 50,336,780 | 8.8% |
| LOAD_FAST_LOAD_FAST | 31,302,580 | 5.5% |
| POP_TOP | 20,713,216 | 3.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,247,240 | 50.5% |
| LOAD_ATTR_SLOT | 32,723,920 | 37.4% |
| LOAD_ATTR | 4,245,220 | 4.8% |
| EXTENDED_ARG | 2,625,280 | 3.0% |
| BINARY_SUBSCR_DICT | 2,092,440 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,558,520 | 48.6% |
| RETURN_CONST | 15,863,360 | 18.1% |
| JUMP_FORWARD | 14,018,240 | 16.0% |
| LOAD_GLOBAL_BUILTIN | 5,314,970 | 6.1% |
| LOAD_CONST | 5,181,080 | 5.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,095,080 | 88.1% |
| LOAD_ATTR_SLOT | 4,889,800 | 4.8% |
| BINARY_SUBSCR_DICT | 3,950,580 | 3.9% |
| LOAD_FAST_CHECK | 2,008,560 | 2.0% |
| BINARY_SUBSCR | 298,060 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 38,102,120 | 37.7% |
| LOAD_FAST | 22,737,220 | 22.5% |
| LOAD_CONST | 14,093,240 | 13.9% |
| LOAD_FAST_LOAD_FAST | 10,735,880 | 10.6% |
| RETURN_CONST | 4,663,420 | 4.6% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 102,188,032 | 43.2% |
| TO_BOOL_LIST | 34,884,940 | 14.8% |
| COMPARE_OP_STR | 32,447,492 | 13.7% |
| CONTAINS_OP | 15,702,008 | 6.6% |
| COMPARE_OP_INT | 12,049,760 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 102,051,030 | 43.2% |
| JUMP_BACKWARD | 38,082,020 | 16.1% |
| LOAD_GLOBAL_MODULE | 27,428,492 | 11.6% |
| POP_TOP | 17,355,552 | 7.3% |
| NOP | 14,087,040 | 6.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 201,280 | 59.3% |
| RETURN_VALUE | 73,920 | 21.8% |
| CALL | 51,600 | 15.2% |
| LOAD_CONST | 12,160 | 3.6% |
| POP_TOP | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 201,280 | 59.3% |
| PUSH_EXC_INFO | 125,760 | 37.0% |
| COPY | 12,480 | 3.7% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 256,640 | 47.2% |
| DELETE_FAST | 201,280 | 37.0% |
| CALL_INTRINSIC_1 | 42,880 | 7.9% |
| POP_JUMP_IF_FALSE | 42,880 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 244,160 | 48.8% |
| PUSH_EXC_INFO | 213,440 | 42.6% |
| CALL_INTRINSIC_1 | 42,880 | 8.6% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 120,940,980 | 40.3% |
| RESUME_CHECK | 67,713,220 | 22.6% |
| POP_TOP | 23,024,760 | 7.7% |
| POP_JUMP_IF_FALSE | 18,003,120 | 6.0% |
| POP_JUMP_IF_NONE | 15,863,360 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 105,768,380 | 35.2% |
| INTERPRETER_EXIT | 61,992,140 | 20.7% |
| LOAD_FAST | 61,621,760 | 20.5% |
| RETURN_VALUE | 42,841,600 | 14.3% |
| TO_BOOL_BOOL | 11,436,160 | 3.8% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 66.7% |
| JUMP_BACKWARD_NO_INTERRUPT | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 50.0% |
| SEND_GEN | 60 | 50.0% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 3,838,920 | 93.2% |
| LOAD_ATTR_INSTANCE_VALUE | 166,060 | 4.0% |
| STORE_FAST_LOAD_FAST | 64,000 | 1.6% |
| BINARY_SUBSCR_LIST_INT | 23,340 | 0.6% |
| LOAD_FAST | 17,600 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,116,880 | 100.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 4,110,380 | 77.8% |
| SET_FUNCTION_ATTRIBUTE | 1,171,540 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,749,240 | 33.1% |
| SET_FUNCTION_ATTRIBUTE | 1,171,540 | 22.2% |
| STORE_FAST | 1,022,300 | 19.4% |
| LOAD_FAST | 455,660 | 8.6% |
| LOAD_GLOBAL_MODULE | 442,760 | 8.4% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,406,480 | 80.9% |
| LOAD_FAST | 2,058,480 | 17.7% |
| SWAP | 118,440 | 1.0% |
| STORE_ATTR | 25,840 | 0.2% |
| LOAD_ATTR_SLOT | 9,680 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,386,860 | 46.3% |
| RETURN_CONST | 3,177,280 | 27.3% |
| LOAD_FAST | 2,388,120 | 20.5% |
| LOAD_CONST | 262,020 | 2.3% |
| LOAD_GLOBAL_MODULE | 257,880 | 2.2% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,888,640 | 81.7% |
| SET_FUNCTION_ATTRIBUTE | 424,960 | 8.9% |
| RETURN_VALUE | 160,920 | 3.4% |
| LOAD_ATTR_SLOT | 103,000 | 2.2% |
| FOR_ITER_LIST | 76,300 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,938,640 | 61.7% |
| LOAD_FAST | 1,156,800 | 24.3% |
| LOAD_GLOBAL_BUILTIN | 262,380 | 5.5% |
| LOAD_CONST | 189,160 | 4.0% |
| LOAD_DEREF | 177,000 | 3.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 93,718,682 | 16.8% |
| RETURN_VALUE | 90,360,600 | 16.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 53,988,940 | 9.7% |
| LOAD_ATTR_SLOT | 48,858,820 | 8.8% |
| BUILD_LIST | 32,656,280 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 278,120,532 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 78,453,460 | 14.1% |
| LOAD_GLOBAL_MODULE | 71,744,502 | 12.9% |
| LOAD_FAST_LOAD_FAST | 47,117,920 | 8.5% |
| LOAD_CONST | 20,446,540 | 3.7% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 9,930,640 | 60.6% |
| FOR_ITER_TUPLE | 4,569,940 | 27.9% |
| FOR_ITER | 1,317,820 | 8.0% |
| FOR_ITER_RANGE | 567,660 | 3.5% |
| CALL_LEN | 1,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,471,040 | 27.3% |
| LOAD_ATTR_SLOT | 3,788,920 | 23.1% |
| TO_BOOL_STR | 2,450,040 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 2,236,480 | 13.6% |
| LOAD_GLOBAL_BUILTIN | 880,880 | 5.4% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 18,575,060 | 51.2% |
| UNPACK_SEQUENCE_LIST | 14,621,180 | 40.3% |
| UNPACK_SEQUENCE_TUPLE | 2,027,640 | 5.6% |
| COPY | 611,800 | 1.7% |
| STORE_FAST_STORE_FAST | 181,500 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,514,420 | 75.8% |
| LOAD_FAST_LOAD_FAST | 3,691,220 | 10.2% |
| STORE_FAST | 2,154,880 | 5.9% |
| LOAD_GLOBAL_BUILTIN | 1,893,820 | 5.2% |
| LOAD_GLOBAL_MODULE | 372,640 | 1.0% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 1,280 | 57.1% |
| SET_FUNCTION_ATTRIBUTE | 560 | 25.0% |
| LOAD_CONST | 120 | 5.4% |
| CALL | 80 | 3.6% |
| BUILD_STRING | 60 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 840 | 37.5% |
| LOAD_CONST | 620 | 27.7% |
| POP_TOP | 440 | 19.6% |
| LOAD_NAME | 200 | 8.9% |
| RETURN_CONST | 60 | 2.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 26,771,480 | 30.4% |
| BUILD_LIST | 24,364,960 | 27.7% |
| FOR_ITER_LIST | 17,890,860 | 20.3% |
| LOAD_FAST | 4,831,800 | 5.5% |
| CALL_LEN | 3,580,440 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 24,364,960 | 27.7% |
| FOR_ITER_LIST | 22,596,640 | 25.7% |
| STORE_FAST | 21,419,080 | 24.3% |
| COPY | 3,592,320 | 4.1% |
| POP_TOP | 3,524,980 | 4.0% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 960 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 90,560 | 62.6% |
| COPY | 26,560 | 18.3% |
| FOR_ITER_LIST | 14,820 | 10.2% |
| FOR_ITER | 4,540 | 3.1% |
| RETURN_VALUE | 3,680 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 105,040 | 72.6% |
| STORE_FAST_STORE_FAST | 33,460 | 23.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,120 | 2.8% |
| UNPACK_SEQUENCE_TUPLE | 980 | 0.7% |
| UNPACK_SEQUENCE | 900 | 0.6% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,614,960 | 23.3% |
| LOAD_CONST | 1,885,440 | 16.8% |
| CALL_ISINSTANCE | 1,260,160 | 11.2% |
| LOAD_FAST | 1,142,300 | 10.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,124,420 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,580,600 | 85.4% |
| STORE_FAST | 897,560 | 8.0% |
| UNPACK_SEQUENCE_TUPLE | 376,200 | 3.4% |
| YIELD_VALUE | 364,704 | 3.3% |
| UNPACK_SEQUENCE | 60 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 19,900 | 48.7% |
| CALL_PY_EXACT_ARGS | 5,500 | 13.5% |
| CACHE | 5,480 | 13.4% |
| COPY_FREE_VARS | 3,080 | 7.5% |
| POP_TOP | 2,420 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,400 | 47.5% |
| LOAD_GLOBAL | 12,340 | 30.2% |
| LOAD_FAST_LOAD_FAST | 2,060 | 5.0% |
| LOAD_CONST | 1,920 | 4.7% |
| POP_TOP | 1,820 | 4.5% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 286,480 | 99.5% |
| BINARY_OP_ADD_INT | 1,200 | 0.4% |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 286,480 | 99.5% |
| BINARY_OP_ADD_INT | 1,200 | 0.4% |
| STORE_FAST | 140 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,728,440 | 58.4% |
| CALL_LEN | 1,511,400 | 18.7% |
| CALL_METHOD_DESCRIPTOR_O | 1,467,800 | 18.1% |
| LOAD_FAST | 194,320 | 2.4% |
| LOAD_FAST_LOAD_FAST | 184,880 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,309,280 | 40.9% |
| LOAD_FAST | 2,074,660 | 25.6% |
| SWAP | 991,000 | 12.2% |
| LOAD_FAST_LOAD_FAST | 807,580 | 10.0% |
| LOAD_CONST | 213,940 | 2.6% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,918,320 | 52.4% |
| LOAD_FAST | 1,544,080 | 16.5% |
| CALL_METHOD_DESCRIPTOR_O | 984,600 | 10.5% |
| LOAD_FAST_LOAD_FAST | 984,400 | 10.5% |
| BINARY_SLICE | 450,740 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_ADD | 3,838,920 | 40.9% |
| LOAD_FAST | 2,014,180 | 21.5% |
| RETURN_VALUE | 1,346,260 | 14.3% |
| STORE_FAST | 1,145,220 | 12.2% |
| BUILD_TUPLE | 436,460 | 4.6% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 98.4% |
| BINARY_OP | 20 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,240 | 98.4% |
| CALL | 20 | 1.6% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,840 | 88.3% |
| BINARY_SUBSCR_TUPLE_INT | 640 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 4,480 | 81.8% |
| BINARY_OP_ADD_INT | 640 | 11.7% |
| LOAD_CONST | 180 | 3.3% |
| CALL_BUILTIN_O | 180 | 3.3% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 178,960 | 61.0% |
| LOAD_FAST_LOAD_FAST | 113,600 | 38.7% |
| BINARY_OP | 380 | 0.1% |
| LOAD_ATTR_WITH_HINT | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 235,600 | 80.3% |
| LOAD_FAST_LOAD_FAST | 56,580 | 19.3% |
| LOAD_GLOBAL_BUILTIN | 560 | 0.2% |
| LOAD_FAST | 300 | 0.1% |
| BINARY_OP_ADD_FLOAT | 120 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,777,300 | 96.6% |
| LOAD_FAST | 124,600 | 1.8% |
| CALL_LEN | 99,780 | 1.4% |
| LOAD_FAST_LOAD_FAST | 7,600 | 0.1% |
| LOAD_ATTR_SLOT | 3,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,453,240 | 49.2% |
| CALL_BUILTIN_CLASS | 1,849,840 | 26.4% |
| BINARY_SLICE | 890,220 | 12.7% |
| SWAP | 290,120 | 4.1% |
| BINARY_SUBSCR_LIST_INT | 263,580 | 3.8% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 103,454,600 | 85.7% |
| LOAD_FAST | 9,727,260 | 8.1% |
| BINARY_SUBSCR_DICT | 3,040,560 | 2.5% |
| BINARY_SUBSCR_LIST_INT | 1,821,400 | 1.5% |
| LOAD_DEREF | 1,527,760 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,081,400 | 18.3% |
| STORE_FAST | 21,715,660 | 18.0% |
| LOAD_CONST | 20,140,420 | 16.7% |
| GET_ITER | 12,587,800 | 10.4% |
| CALL_PY_EXACT_ARGS | 9,517,360 | 7.9% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,533,080 | 54.9% |
| LOAD_FAST_LOAD_FAST | 1,245,660 | 44.6% |
| LOAD_CONST | 11,720 | 0.4% |
| LOAD_FAST | 1,660 | 0.1% |
| BINARY_SUBSCR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,850,800 | 66.3% |
| MAKE_CELL | 940,780 | 33.7% |
| LOAD_ATTR_SLOT | 640 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 14,569,680 | 45.2% |
| LOAD_CONST | 8,678,440 | 26.9% |
| LOAD_FAST | 8,536,260 | 26.5% |
| BINARY_OP_SUBTRACT_INT | 263,580 | 0.8% |
| BINARY_OP_ADD_INT | 134,520 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,132,360 | 31.4% |
| LOAD_ATTR_INSTANCE_VALUE | 4,042,640 | 12.5% |
| STORE_FAST | 3,158,200 | 9.8% |
| LOAD_FAST | 2,923,560 | 9.1% |
| LOAD_GLOBAL_MODULE | 2,264,600 | 7.0% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 748,800 | 58.8% |
| LOAD_FAST_LOAD_FAST | 366,960 | 28.8% |
| BINARY_OP_ADD_INT | 117,560 | 9.2% |
| BINARY_OP_SUBTRACT_INT | 36,960 | 2.9% |
| LOAD_FAST | 3,780 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 632,260 | 49.6% |
| LOAD_FAST | 352,600 | 27.7% |
| STORE_FAST | 153,260 | 12.0% |
| CALL_BUILTIN_O | 67,820 | 5.3% |
| LOAD_FAST_LOAD_FAST | 33,880 | 2.7% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,284,620 | 99.9% |
| LOAD_FAST_LOAD_FAST | 4,400 | 0.0% |
| BINARY_SUBSCR | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,395,660 | 30.1% |
| COMPARE_OP_STR | 3,294,160 | 29.2% |
| LOAD_ATTR_METHOD_NO_DICT | 3,152,200 | 27.9% |
| LOAD_CONST | 307,600 | 2.7% |
| STORE_FAST | 288,720 | 2.6% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,126,680 | 46.9% |
| LOAD_FAST | 1,826,580 | 27.4% |
| LOAD_GLOBAL_MODULE | 727,780 | 10.9% |
| CALL | 431,800 | 6.5% |
| RETURN_VALUE | 365,640 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,207,900 | 93.1% |
| COPY_FREE_VARS | 450,680 | 6.8% |
| CALL_PY_EXACT_ARGS | 6,400 | 0.1% |
| STORE_FAST | 2,560 | 0.0% |
| MAKE_CELL | 300 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,024,600 | 68.8% |
| BINARY_SUBSCR_DICT | 6,452,840 | 21.1% |
| LOAD_CONST | 2,692,860 | 8.8% |
| CALL_PY_EXACT_ARGS | 106,180 | 0.3% |
| RETURN_VALUE | 93,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 27,772,620 | 90.9% |
| POP_TOP | 2,625,160 | 8.6% |
| CALL_PY_EXACT_ARGS | 106,220 | 0.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 49,760 | 0.2% |
| RESUME | 980 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,108,920 | 30.0% |
| LOAD_GLOBAL_BUILTIN | 7,148,900 | 17.7% |
| LOAD_ATTR_SLOT | 4,517,004 | 11.2% |
| LOAD_ATTR_CLASS | 3,789,040 | 9.4% |
| CALL_LEN | 3,073,740 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,075,820 | 47.2% |
| LOAD_FAST | 10,535,160 | 26.1% |
| STORE_FAST | 3,787,060 | 9.4% |
| RETURN_VALUE | 2,545,440 | 6.3% |
| MAP_ADD | 1,674,520 | 4.1% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,269,300 | 47.0% |
| LOAD_ATTR_INSTANCE_VALUE | 4,709,300 | 30.4% |
| LOAD_FAST_LOAD_FAST | 2,639,320 | 17.1% |
| LOAD_FAST | 664,900 | 4.3% |
| LOAD_GLOBAL_BUILTIN | 90,280 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,413,580 | 22.1% |
| STORE_FAST | 2,896,800 | 18.7% |
| RETURN_VALUE | 2,325,720 | 15.0% |
| PUSH_EXC_INFO | 2,286,680 | 14.8% |
| TO_BOOL_BOOL | 2,079,920 | 13.4% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,223,840 | 84.8% |
| RETURN_GENERATOR | 385,440 | 10.1% |
| CALL_BUILTIN_CLASS | 141,720 | 3.7% |
| RETURN_VALUE | 47,920 | 1.3% |
| LOAD_CONST | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,625,000 | 69.0% |
| COPY | 335,360 | 8.8% |
| LOAD_CONST | 304,300 | 8.0% |
| PUSH_EXC_INFO | 205,700 | 5.4% |
| RETURN_VALUE | 144,500 | 3.8% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 5,669,834 | 31.4% |
| RETURN_GENERATOR | 4,748,320 | 26.3% |
| CALL_STR_1 | 2,448,640 | 13.5% |
| LOAD_FAST | 2,121,380 | 11.7% |
| LOAD_GLOBAL_MODULE | 1,203,016 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,973,292 | 38.6% |
| LOAD_FAST | 4,956,418 | 27.4% |
| LIST_APPEND | 2,448,620 | 13.5% |
| TO_BOOL_BOOL | 1,700,040 | 9.4% |
| CALL_PY_EXACT_ARGS | 904,580 | 5.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 242,747,684 | 83.1% |
| LOAD_GLOBAL_BUILTIN | 41,512,000 | 14.2% |
| BUILD_TUPLE | 4,611,160 | 1.6% |
| LOAD_ATTR | 1,896,660 | 0.6% |
| LOAD_ATTR_MODULE | 1,030,240 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 285,318,050 | 97.7% |
| COPY | 4,291,560 | 1.5% |
| YIELD_VALUE | 1,260,160 | 0.4% |
| RETURN_VALUE | 745,554 | 0.3% |
| STORE_FAST | 395,980 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,790,060 | 57.5% |
| LOAD_ATTR_SLOT | 11,091,280 | 30.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,904,620 | 5.3% |
| LOAD_DEREF | 1,900,680 | 5.3% |
| LOAD_ATTR | 217,120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,838,600 | 27.2% |
| COMPARE_OP_INT | 6,114,120 | 16.9% |
| LOAD_GLOBAL_BUILTIN | 4,567,040 | 12.6% |
| SWAP | 3,580,440 | 9.9% |
| CALL_BUILTIN_CLASS | 3,073,740 | 8.5% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,383,580 | 82.1% |
| RETURN_VALUE | 2,635,720 | 8.2% |
| LOAD_CONST | 567,720 | 1.8% |
| BUILD_TUPLE | 554,220 | 1.7% |
| BUILD_LIST | 488,240 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,527,100 | 54.5% |
| JUMP_BACKWARD | 9,477,860 | 29.5% |
| NOP | 2,435,240 | 7.6% |
| EXTENDED_ARG | 683,180 | 2.1% |
| LOAD_CONST | 680,720 | 2.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,479,700 | 55.8% |
| LOAD_ATTR_METHOD_NO_DICT | 23,623,320 | 34.2% |
| LOAD_CONST | 2,925,680 | 4.2% |
| LOAD_GLOBAL_MODULE | 1,387,080 | 2.0% |
| CALL_BUILTIN_CLASS | 732,520 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,988,940 | 78.2% |
| POP_TOP | 4,749,180 | 6.9% |
| LOAD_CONST | 3,776,480 | 5.5% |
| LOAD_FAST | 2,799,580 | 4.1% |
| CALL_PY_EXACT_ARGS | 973,040 | 1.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,965,640 | 90.6% |
| LOAD_FAST | 187,400 | 5.7% |
| LOAD_ATTR_MODULE | 92,440 | 2.8% |
| LOAD_ATTR_METHOD_NO_DICT | 25,800 | 0.8% |
| CALL | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,282,620 | 69.8% |
| LOAD_CONST | 389,320 | 11.9% |
| UNPACK_SEQUENCE_LIST | 194,080 | 5.9% |
| GET_ITER | 188,420 | 5.8% |
| CONTAINS_OP | 92,460 | 2.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,033,540 | 99.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,200 | 0.2% |
| LOAD_ATTR | 5,640 | 0.2% |
| CALL | 1,540 | 0.1% |
| LOAD_ATTR_METHOD_LAZY_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,734,900 | 56.9% |
| LOAD_FAST | 574,900 | 18.9% |
| POP_TOP | 320,620 | 10.5% |
| CALL_BUILTIN_CLASS | 239,760 | 7.9% |
| LOAD_ATTR_METHOD_NO_DICT | 89,560 | 2.9% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,516,600 | 53.6% |
| LOAD_FAST | 3,986,560 | 32.8% |
| RETURN_VALUE | 631,520 | 5.2% |
| LOAD_ATTR_SLOT | 257,320 | 2.1% |
| BUILD_TUPLE | 243,160 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,077,660 | 41.8% |
| POP_TOP | 4,345,120 | 35.7% |
| BINARY_OP_ADD_INT | 1,467,800 | 12.1% |
| BINARY_OP_ADD_UNICODE | 984,600 | 8.1% |
| STORE_FAST | 199,060 | 1.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 173,116,120 | 38.7% |
| LOAD_FAST_LOAD_FAST | 103,310,100 | 23.1% |
| LOAD_ATTR_METHOD_NO_DICT | 74,559,272 | 16.7% |
| LOAD_ATTR_SLOT | 14,645,540 | 3.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,596,280 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 389,121,428 | 87.0% |
| COPY_FREE_VARS | 47,552,680 | 10.6% |
| MAKE_CELL | 4,968,720 | 1.1% |
| RETURN_GENERATOR | 4,438,240 | 1.0% |
| CALL_PY_EXACT_ARGS | 728,376 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 7,932,960 | 38.3% |
| LOAD_FAST | 6,967,240 | 33.6% |
| LOAD_FAST_LOAD_FAST | 1,865,480 | 9.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,261,640 | 6.1% |
| LOAD_ATTR_SLOT | 645,240 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 19,893,460 | 96.0% |
| MAKE_CELL | 585,560 | 2.8% |
| COPY_FREE_VARS | 233,200 | 1.1% |
| CALL_PY_EXACT_ARGS | 7,960 | 0.0% |
| RETURN_GENERATOR | 940 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,485,460 | 100.0% |
| UNARY_NOT | 280 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 2,448,640 | 70.2% |
| LOAD_FAST | 983,660 | 28.2% |
| STORE_FAST | 38,160 | 1.1% |
| CALL | 15,040 | 0.4% |
| BUILD_TUPLE | 300 | 0.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,818,540 | 92.5% |
| LOAD_ATTR_SLOT | 1,464,616 | 7.2% |
| RETURN_VALUE | 22,540 | 0.1% |
| LOAD_FAST_CHECK | 19,480 | 0.1% |
| RETURN_GENERATOR | 8,240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,960,180 | 93.2% |
| LOAD_GLOBAL_BUILTIN | 762,360 | 3.7% |
| BUILD_TUPLE | 531,016 | 2.6% |
| CALL_PY_EXACT_ARGS | 33,560 | 0.2% |
| RETURN_VALUE | 24,440 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,592,780 | 100.0% |
| LOAD_CONST | 300 | 0.0% |
| CALL | 200 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,950,040 | 59.9% |
| STORE_FAST | 1,960,580 | 16.9% |
| LOAD_ATTR | 1,443,800 | 12.5% |
| PUSH_NULL | 890,280 | 7.7% |
| LOAD_GLOBAL_MODULE | 178,840 | 1.5% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,040 | 98.7% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 1.0% |
| COMPARE_OP | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,060 | 99.0% |
| POP_JUMP_IF_FALSE | 60 | 1.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,586,205 | 43.3% |
| CALL_LEN | 6,114,120 | 14.3% |
| LOAD_GLOBAL_MODULE | 3,642,820 | 8.5% |
| COPY | 3,580,400 | 8.3% |
| LOAD_ATTR_CLASS | 3,555,000 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 26,405,765 | 61.6% |
| POP_JUMP_IF_TRUE | 12,049,760 | 28.1% |
| COPY | 2,105,728 | 4.9% |
| RETURN_VALUE | 1,278,532 | 3.0% |
| EXTENDED_ARG | 626,880 | 1.5% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 39,916,496 | 71.9% |
| LOAD_FAST | 9,063,692 | 16.3% |
| BINARY_SUBSCR_TUPLE_INT | 3,294,160 | 5.9% |
| RETURN_VALUE | 957,820 | 1.7% |
| LOAD_ATTR_INSTANCE_VALUE | 836,344 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 32,447,492 | 58.4% |
| POP_JUMP_IF_FALSE | 17,892,720 | 32.2% |
| COPY | 3,095,604 | 5.6% |
| RETURN_VALUE | 1,231,075 | 2.2% |
| EXTENDED_ARG | 777,260 | 1.4% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,230,940 | 92.7% |
| GET_ITER | 96,860 | 7.3% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,230,960 | 92.7% |
| POP_TOP | 96,860 | 7.3% |
| RESUME | 80 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 91,985,098 | 53.7% |
| GET_ITER | 45,440,610 | 26.5% |
| SWAP | 22,596,640 | 13.2% |
| EXTENDED_ARG | 6,147,340 | 3.6% |
| LOAD_FAST | 5,162,000 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 93,718,682 | 54.7% |
| LOAD_FAST | 27,094,808 | 15.8% |
| SWAP | 17,890,860 | 10.4% |
| RETURN_CONST | 14,501,656 | 8.5% |
| STORE_FAST_LOAD_FAST | 9,930,640 | 5.8% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,973,100 | 46.2% |
| JUMP_BACKWARD | 5,817,480 | 45.0% |
| SWAP | 826,660 | 6.4% |
| EXTENDED_ARG | 310,640 | 2.4% |
| FOR_ITER | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,126,440 | 47.4% |
| RETURN_CONST | 2,799,000 | 21.6% |
| LOAD_FAST | 2,203,380 | 17.0% |
| LOAD_GLOBAL_MODULE | 825,720 | 6.4% |
| STORE_FAST_LOAD_FAST | 567,660 | 4.4% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,375,415 | 54.9% |
| JUMP_BACKWARD | 13,154,599 | 37.3% |
| SWAP | 2,628,260 | 7.4% |
| EXTENDED_ARG | 69,080 | 0.2% |
| FOR_ITER_LIST | 35,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,523,809 | 49.7% |
| STORE_FAST | 8,640,487 | 24.5% |
| STORE_FAST_LOAD_FAST | 4,569,940 | 13.0% |
| SWAP | 2,603,600 | 7.4% |
| LOAD_FAST_LOAD_FAST | 1,077,760 | 3.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,241,360 | 88.9% |
| LOAD_FAST | 1,544,160 | 10.4% |
| COPY | 105,520 | 0.7% |
| LOAD_ATTR_CLASS | 6,680 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 2,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 3,789,040 | 25.4% |
| COMPARE_OP_INT | 3,555,000 | 23.9% |
| LOAD_ATTR_METHOD_NO_DICT | 2,703,880 | 18.1% |
| CALL | 2,566,780 | 17.2% |
| LOAD_ATTR_MODULE | 1,544,160 | 10.4% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 130,605,368 | 78.5% |
| LOAD_FAST_LOAD_FAST | 16,275,860 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 5,961,820 | 3.6% |
| LOAD_GLOBAL_MODULE | 4,175,120 | 2.5% |
| BINARY_SUBSCR_LIST_INT | 4,042,640 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,331,524 | 20.0% |
| LOAD_CONST | 28,809,500 | 17.3% |
| LOAD_ATTR_METHOD_NO_DICT | 14,949,440 | 9.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 13,254,440 | 8.0% |
| CONTAINS_OP | 10,867,320 | 6.5% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,880 | 99.9% |
| LOAD_ATTR | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,620 | 99.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 280 | 0.9% |
| CALL | 20 | 0.1% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 201,907,112 | 72.9% |
| LOAD_ATTR_SLOT | 30,528,976 | 11.0% |
| LOAD_ATTR_INSTANCE_VALUE | 14,949,440 | 5.4% |
| LOAD_GLOBAL_MODULE | 11,569,880 | 4.2% |
| LOAD_ATTR_WITH_HINT | 3,625,480 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 125,110,920 | 45.2% |
| CALL_PY_EXACT_ARGS | 74,559,272 | 26.9% |
| LOAD_CONST | 26,227,556 | 9.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 23,623,320 | 8.5% |
| LOAD_GLOBAL_MODULE | 19,002,300 | 6.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 95,343,200 | 82.0% |
| LOAD_ATTR_INSTANCE_VALUE | 13,254,440 | 11.4% |
| LOAD_DEREF | 2,642,640 | 2.3% |
| LOAD_FAST_LOAD_FAST | 1,358,880 | 1.2% |
| LOAD_ATTR_WITH_HINT | 1,358,200 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,221,620 | 69.9% |
| LOAD_FAST_LOAD_FAST | 16,065,440 | 13.8% |
| CALL_PY_EXACT_ARGS | 11,596,280 | 10.0% |
| LOAD_CONST | 2,706,100 | 2.3% |
| LOAD_DEREF | 2,126,500 | 1.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20,089,300 | 68.9% |
| LOAD_ATTR_MODULE | 6,059,820 | 20.8% |
| LOAD_ATTR_CLASS | 1,544,160 | 5.3% |
| LOAD_FAST_LOAD_FAST | 1,235,000 | 4.2% |
| LOAD_FAST | 202,480 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 7,201,120 | 24.7% |
| LOAD_ATTR_MODULE | 6,059,820 | 20.8% |
| LOAD_FAST | 4,286,280 | 14.7% |
| COMPARE_OP | 3,293,580 | 11.3% |
| LOAD_GLOBAL_MODULE | 1,622,360 | 5.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,069,640 | 100.0% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 983,660 | 92.0% |
| LOAD_FAST | 43,200 | 4.0% |
| IS_OP | 42,860 | 4.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 689,200 | 60.0% |
| LOAD_FAST | 404,020 | 35.2% |
| STORE_FAST_LOAD_FAST | 44,760 | 3.9% |
| BINARY_SUBSCR_DICT | 6,160 | 0.5% |
| LOAD_FAST_LOAD_FAST | 3,440 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 718,240 | 62.5% |
| CALL_LEN | 137,880 | 12.0% |
| RETURN_VALUE | 105,260 | 9.2% |
| LOAD_FAST | 95,560 | 8.3% |
| TO_BOOL_BOOL | 46,000 | 4.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,715,336 | 72.1% |
| LOAD_ATTR_SLOT | 6,789,814 | 24.8% |
| LOAD_ATTR_INSTANCE_VALUE | 482,920 | 1.8% |
| CALL | 93,400 | 0.3% |
| BINARY_SUBSCR | 84,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 25,543,196 | 93.4% |
| RETURN_VALUE | 1,070,562 | 3.9% |
| LOAD_FAST | 239,400 | 0.9% |
| STORE_FAST | 238,600 | 0.9% |
| LOAD_CONST | 105,300 | 0.4% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 456,167,506 | 88.6% |
| LOAD_ATTR_SLOT | 34,726,545 | 6.7% |
| LOAD_DEREF | 7,776,800 | 1.5% |
| LOAD_FAST_LOAD_FAST | 7,087,200 | 1.4% |
| STORE_FAST_LOAD_FAST | 3,788,920 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,126,652 | 11.9% |
| STORE_FAST | 48,858,820 | 9.5% |
| GET_ITER | 47,954,056 | 9.3% |
| RETURN_VALUE | 36,490,462 | 7.1% |
| LOAD_ATTR_SLOT | 34,726,545 | 6.7% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,712,240 | 57.1% |
| LOAD_FAST_LOAD_FAST | 6,461,320 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 6,300,040 | 20.3% |
| LOAD_ATTR_WITH_HINT | 500,740 | 1.6% |
| LOAD_DEREF | 10,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,686,140 | 31.3% |
| TO_BOOL_BOOL | 3,657,960 | 11.8% |
| LOAD_ATTR_METHOD_NO_DICT | 3,625,480 | 11.7% |
| COPY | 2,789,480 | 9.0% |
| LOAD_FAST | 2,485,120 | 8.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 175,488,076 | 30.5% |
| POP_JUMP_IF_FALSE | 136,139,928 | 23.7% |
| STORE_FAST | 78,453,460 | 13.6% |
| LOAD_FAST | 46,079,080 | 8.0% |
| POP_JUMP_IF_NOT_NONE | 38,102,120 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 399,377,698 | 69.4% |
| LOAD_DEREF | 92,147,960 | 16.0% |
| CALL_ISINSTANCE | 41,512,000 | 7.2% |
| LOAD_FAST_LOAD_FAST | 7,871,200 | 1.4% |
| CALL_BUILTIN_CLASS | 7,148,900 | 1.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 278,562,464 | 43.4% |
| STORE_FAST | 71,744,502 | 11.2% |
| RESUME_CHECK | 53,583,440 | 8.3% |
| POP_JUMP_IF_FALSE | 50,336,780 | 7.8% |
| LOAD_GLOBAL_MODULE | 34,219,120 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 242,747,684 | 37.8% |
| LOAD_FAST | 128,748,300 | 20.1% |
| LOAD_FAST_LOAD_FAST | 47,201,680 | 7.4% |
| IS_OP | 41,729,520 | 6.5% |
| LOAD_GLOBAL_MODULE | 34,219,120 | 5.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,083,100 | 100.0% |
| LOAD_SUPER_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,077,400 | 99.5% |
| STORE_FAST | 5,760 | 0.5% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,099,620 | 100.0% |
| LOAD_SUPER_ATTR | 2,400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,702,960 | 83.3% |
| CALL_PY_WITH_DEFAULTS | 7,932,960 | 9.2% |
| CALL_PY_EXACT_ARGS | 3,262,080 | 3.8% |
| LOAD_FAST | 2,075,160 | 2.4% |
| LOAD_GLOBAL_MODULE | 689,240 | 0.8% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 389,121,428 | 55.4% |
| COPY_FREE_VARS | 93,106,780 | 13.3% |
| CACHE | 69,749,656 | 9.9% |
| CALL_KW | 43,426,700 | 6.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 27,772,620 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 305,835,904 | 43.5% |
| LOAD_GLOBAL_BUILTIN | 175,488,076 | 25.0% |
| RETURN_CONST | 67,713,220 | 9.6% |
| LOAD_FAST_LOAD_FAST | 60,571,320 | 8.6% |
| LOAD_GLOBAL_MODULE | 53,583,440 | 7.6% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 364,664 | 79.2% |
| LOAD_CONST | 95,920 | 20.8% |
| SEND | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 364,664 | 79.2% |
| POP_TOP | 95,940 | 20.8% |
| RESUME | 40 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 44,219,300 | 56.7% |
| LOAD_FAST | 32,506,240 | 41.7% |
| SWAP | 794,320 | 1.0% |
| BINARY_SUBSCR | 449,520 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 32,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,619,400 | 46.9% |
| RETURN_CONST | 13,693,940 | 17.6% |
| LOAD_FAST | 13,007,040 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 5,133,860 | 6.6% |
| LOAD_GLOBAL_MODULE | 3,667,940 | 4.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360,212,818 | 58.8% |
| LOAD_FAST_LOAD_FAST | 248,734,180 | 40.6% |
| STORE_ATTR_SLOT | 2,484,307 | 0.4% |
| LOAD_ATTR_SLOT | 847,800 | 0.1% |
| LOAD_DEREF | 14,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 170,370,120 | 27.8% |
| LOAD_FAST_LOAD_FAST | 141,429,960 | 23.1% |
| RETURN_CONST | 120,940,980 | 19.8% |
| LOAD_FAST | 112,444,658 | 18.4% |
| LOAD_GLOBAL_BUILTIN | 31,685,060 | 5.2% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 943,280 | 57.4% |
| LOAD_FAST_LOAD_FAST | 697,880 | 42.5% |
| SWAP | 840 | 0.1% |
| STORE_ATTR_WITH_HINT | 700 | 0.0% |
| STORE_ATTR | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 512,260 | 31.2% |
| LOAD_GLOBAL_MODULE | 448,360 | 27.3% |
| RETURN_CONST | 344,580 | 21.0% |
| LOAD_FAST | 257,540 | 15.7% |
| LOAD_GLOBAL_BUILTIN | 78,680 | 4.8% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,738,200 | 71.1% |
| LOAD_FAST_LOAD_FAST | 644,400 | 12.3% |
| LOAD_ATTR_SLOT | 410,400 | 7.8% |
| SWAP | 367,960 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 47,240 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,497,460 | 47.5% |
| JUMP_BACKWARD | 1,528,320 | 29.1% |
| LOAD_FAST | 1,006,080 | 19.1% |
| LOAD_GLOBAL_BUILTIN | 95,380 | 1.8% |
| LOAD_FAST_LOAD_FAST | 65,800 | 1.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 432,000 | 99.6% |
| LOAD_FAST | 1,460 | 0.3% |
| STORE_SUBSCR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 430,520 | 99.3% |
| EXTENDED_ARG | 1,380 | 0.3% |
| LOAD_FAST | 1,320 | 0.3% |
| RETURN_CONST | 320 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,148,915 | 75.8% |
| LOAD_ATTR_SLOT | 5,763,480 | 19.7% |
| LOAD_ATTR_INSTANCE_VALUE | 553,760 | 1.9% |
| COPY | 234,540 | 0.8% |
| LOAD_ATTR | 225,500 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 25,235,555 | 86.3% |
| POP_JUMP_IF_TRUE | 2,931,040 | 10.0% |
| EXTENDED_ARG | 992,840 | 3.4% |
| TO_BOOL_NONE | 37,451 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 33,633 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 285,318,050 | 66.4% |
| COPY | 38,567,808 | 9.0% |
| LOAD_FAST | 34,274,380 | 8.0% |
| RETURN_VALUE | 25,447,180 | 5.9% |
| LOAD_ATTR_SLOT | 12,044,080 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 293,987,466 | 68.4% |
| POP_JUMP_IF_TRUE | 102,188,032 | 23.8% |
| UNARY_NOT | 23,157,640 | 5.4% |
| EXTENDED_ARG | 10,479,440 | 2.4% |
| TO_BOOL_STR | 640 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,326,640 | 65.2% |
| LOAD_ATTR_INSTANCE_VALUE | 356,080 | 17.5% |
| RETURN_VALUE | 148,400 | 7.3% |
| LOAD_ATTR_SLOT | 138,880 | 6.8% |
| BINARY_OP | 53,900 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,358,580 | 66.7% |
| POP_JUMP_IF_TRUE | 536,340 | 26.3% |
| UNARY_NOT | 139,300 | 6.8% |
| TO_BOOL_STR | 1,280 | 0.1% |
| TO_BOOL_BOOL | 320 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,112,220 | 75.6% |
| LOAD_ATTR_SLOT | 6,730,660 | 14.5% |
| LOAD_ATTR_INSTANCE_VALUE | 2,634,460 | 5.7% |
| COPY | 888,220 | 1.9% |
| BINARY_SUBSCR_LIST_INT | 393,200 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 34,884,940 | 75.1% |
| POP_JUMP_IF_FALSE | 8,229,120 | 17.7% |
| UNARY_NOT | 2,525,220 | 5.4% |
| EXTENDED_ARG | 790,880 | 1.7% |
| TO_BOOL | 4,300 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,384,305 | 57.5% |
| LOAD_ATTR_SLOT | 11,434,620 | 32.3% |
| COPY | 1,804,040 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 582,760 | 1.6% |
| LOAD_ATTR_MODULE | 518,960 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,040,185 | 65.0% |
| POP_JUMP_IF_TRUE | 11,574,840 | 32.7% |
| EXTENDED_ARG | 776,420 | 2.2% |
| TO_BOOL_ALWAYS_TRUE | 37,736 | 0.1% |
| UNARY_NOT | 7,920 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,661,720 | 57.7% |
| STORE_FAST_LOAD_FAST | 2,450,040 | 21.2% |
| COPY | 1,511,700 | 13.1% |
| LOAD_ATTR_SLOT | 436,820 | 3.8% |
| LOAD_ATTR_INSTANCE_VALUE | 359,480 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,720,400 | 49.6% |
| POP_JUMP_IF_FALSE | 5,445,000 | 47.2% |
| UNARY_NOT | 369,580 | 3.2% |
| TO_BOOL_NONE | 4,940 | 0.0% |
| TO_BOOL_INT | 1,580 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 14,181,920 | 97.0% |
| RETURN_VALUE | 232,840 | 1.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 194,080 | 1.3% |
| LOAD_FAST | 15,920 | 0.1% |
| LOAD_ATTR_SLOT | 1,240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 14,621,180 | 100.0% |
| STORE_FAST | 5,740 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 777,560 | 35.3% |
| YIELD_VALUE | 376,200 | 17.1% |
| STORE_FAST | 373,640 | 17.0% |
| FOR_ITER | 242,800 | 11.0% |
| FOR_ITER_LIST | 234,960 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,027,640 | 92.0% |
| STORE_FAST | 175,940 | 8.0% |
| STORE_DEREF | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 13,825,240 | 70.0% |
| FOR_ITER_LIST | 3,455,020 | 17.5% |
| RETURN_VALUE | 1,471,900 | 7.4% |
| STORE_FAST | 371,320 | 1.9% |
| RETURN_CONST | 290,360 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,575,060 | 94.0% |
| STORE_FAST | 1,152,760 | 5.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 30,040 | 0.2% |
| UNPACK_SEQUENCE | 20 | 0.0% |


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
|     deferred | 4,868,600 | 15.9% |
|          hit | 25,528,380 | 83.6% |
|         miss | 127,480 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,500 | 34.4% |
| Failure | 14,300 | 65.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 6,440 | 45.0% |
| multiply different types | 3,520 | 24.6% |
| or | 1,280 | 9.0% |
| remainder | 1,140 | 8.0% |
| subtract other | 980 | 6.9% |
| and int | 420 | 2.9% |
| and different types | 160 | 1.1% |
| subtract different types | 160 | 1.1% |
| true divide different types | 140 | 1.0% |
| and other | 60 | 0.4% |


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
|     deferred | 40,816,540 | 19.5% |
|          hit | 168,364,920 | 80.5% |
|         miss | 1,580 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,320 | 30.3% |
| Failure | 28,400 | 69.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 16,640 | 58.6% |
| other | 7,140 | 25.1% |
| code complex parameters | 4,280 | 15.1% |
| buffer int | 260 | 0.9% |
| tuple slice | 80 | 0.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 67,181,824 | 5.8% |
|          hit | 1,033,082,951 | 88.8% |
|         miss | 61,097,007 | 5.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,264,576 | 91.8% |
| Failure | 113,500 | 8.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| no dict | 39,960 | 35.2% |
| code complex parameters | 27,600 | 24.3% |
| meth descr varargs | 12,860 | 11.3% |
| class no vectorcall | 8,900 | 7.8% |
| class mutable | 5,720 | 5.0% |
| cfunc noargs | 5,380 | 4.7% |
| cfunc varargs keywords | 3,760 | 3.3% |
| meth descr varargs keywords | 1,620 | 1.4% |
| wrong number arguments | 1,440 | 1.3% |
| init not simple | 1,340 | 1.2% |
| meth descr method fastcall keywords | 1,180 | 1.0% |
| bound method | 1,060 | 0.9% |
| other | 1,040 | 0.9% |
| cfunc varargs | 580 | 0.5% |
| init not python | 540 | 0.5% |
| cmethod | 400 | 0.4% |
| operator wrapper | 120 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 42,899,780 | 30.3% |
|          hit | 97,496,810 | 68.9% |
|         miss | 933,054 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 30,568 | 26.3% |
| Failure | 85,567 | 73.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 50,588 | 59.1% |
| baseobject | 13,820 | 16.2% |
| other | 6,100 | 7.1% |
| different types | 5,760 | 6.7% |
| bool | 3,439 | 4.0% |
| tuple | 3,020 | 3.5% |
| list | 2,240 | 2.6% |
| set | 320 | 0.4% |
| string | 280 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 37,794,584 | 14.6% |
|          hit | 216,892,436 | 83.8% |
|         miss | 4,028,688 | 1.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 88,282 | 68.2% |
| Failure | 41,150 | 31.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 9,900 | 24.1% |
| set | 9,150 | 22.2% |
| zip | 7,220 | 17.5% |
| dict items | 5,860 | 14.2% |
| reversed list | 4,680 | 11.4% |
| dict keys | 2,220 | 5.4% |
| dict values | 1,140 | 2.8% |
| itertools | 480 | 1.2% |
| map | 260 | 0.6% |
| other | 220 | 0.5% |
| seq iter | 20 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 115,077,906 | 8.9% |
|        deopt | 1,580 | 0.0% |
|          hit | 1,089,399,498 | 84.1% |
|         miss | 89,582,606 | 6.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,843,930 | 89.8% |
| Failure | 208,820 | 10.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 103,340 | 49.5% |
| not managed dict | 37,360 | 17.9% |
| shadowed | 28,080 | 13.4% |
| metaclass attribute | 9,240 | 4.4% |
| class method obj | 9,160 | 4.4% |
| non overriding descriptor | 8,060 | 3.9% |
| method | 5,760 | 2.8% |
| class attr simple | 4,120 | 2.0% |
| module attr not found | 3,000 | 1.4% |
| builtin class method | 400 | 0.2% |
| class attr descriptor | 180 | 0.1% |
| mutable class | 120 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 122,060 | 0.0% |
|        deopt | 840 | 0.0% |
|          hit | 1,217,162,332 | 100.0% |
|         miss | 6,480 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 121,620 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,360 | 0.0% |
|          hit | 87,185,180 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,460 | 100.0% |
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
|     deferred | 60 | 0.0% |
|          hit | 460,644 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,055,873 | 1.3% |
|          hit | 558,497,142 | 79.4% |
|         miss | 133,466,863 | 19.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,540,447 | 99.0% |
| Failure | 26,000 | 1.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 17,280 | 66.5% |
| not in dict | 7,200 | 27.7% |
| not in keys | 800 | 3.1% |
| overridden | 720 | 2.8% |


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
|     deferred | 3,768,080 | 39.8% |
|          hit | 5,692,000 | 60.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,500 | 38.9% |
| Failure | 2,360 | 61.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 1,720 | 72.9% |
| out of range | 640 | 27.1% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,147,760 | 3.5% |
|          hit | 547,092,446 | 95.2% |
|         miss | 7,416,812 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 199,080 | 78.2% |
| Failure | 55,420 | 21.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 25,260 | 45.6% |
| tuple | 17,780 | 32.1% |
| dict | 5,820 | 10.5% |
| other | 2,440 | 4.4% |
| set | 2,160 | 3.9% |
| mapping | 1,960 | 3.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 138,520 | 0.4% |
|          hit | 36,588,420 | 99.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,380 | 85.9% |
| Failure | 880 | 14.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 640 | 72.7% |
| iterator | 240 | 27.3% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 7,446,191,278 | 50.1% |
| Not specialized | 1,352,232,933 | 9.1% |
| Specialized hits | 5,757,439,483 | 38.8% |
| Specialized misses | 296,660,670 | 2.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 115,077,906 | 33.7% |
| CALL | 67,181,824 | 19.7% |
| COMPARE_OP | 42,899,780 | 12.5% |
| BINARY_SUBSCR | 40,816,540 | 11.9% |
| FOR_ITER | 37,794,584 | 11.1% |
| TO_BOOL | 20,147,760 | 5.9% |
| STORE_ATTR | 9,055,873 | 2.6% |
| BINARY_OP | 4,868,600 | 1.4% |
| STORE_SUBSCR | 3,768,080 | 1.1% |
| UNPACK_SEQUENCE | 138,520 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 131,687,183 | 44.4% |
| LOAD_ATTR_METHOD_NO_DICT | 58,053,778 | 19.6% |
| CALL_PY_EXACT_ARGS | 45,164,967 | 15.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 14,590,645 | 4.9% |
| LOAD_ATTR_SLOT | 8,308,489 | 2.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 8,306,320 | 2.8% |
| LOAD_ATTR_INSTANCE_VALUE | 5,805,060 | 2.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,525,760 | 1.9% |
| TO_BOOL_ALWAYS_TRUE | 3,870,291 | 1.3% |
| TO_BOOL_NONE | 2,721,861 | 0.9% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 120,976,516 | 17.0% |
| Calls to Python functions inlined | 589,338,748 | 83.0% |
| Calls via PyEval_EvalFrame (total) | 120,976,516 | 17.0% |
| Calls via PyEval_EvalFrame (vector) | 106,568,516 | 15.0% |
| Calls via PyEval_EvalFrame (generator) | 14,408,000 | 2.0% |
| Calls via PyEval_EvalFrame (legacy) | 100 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 106,568,376 | 15.0% |
| Calls via PyEval_EvalFrame (build class) | 40 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 13,899,104 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 2,475,100 | 0.3% |
| Calls via PyEval_EvalFrame (api) | 23,661,632 | 3.3% |
| Calls via PyEval_EvalFrame (method) | 100 | 0.0% |
| Frame objects created | 4,745,560 | 0.7% |
| Frames pushed | 486,291,333 | 68.5% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 307,147,676 | 28.5% |
| Frees to freelist | 307,217,694 |  |
| Allocations | 769,275,017 | 71.5% |
| Allocations to 512 bytes | 768,233,065 | 71.4% |
| Allocations to 4 kbytes | 723,852 | 0.1% |
| Allocations over 4 kbytes | 318,100 | 0.0% |
| Frees | 794,824,229 |  |
| New values | 8,867,540 |  |
| Interpreter increfs | 7,196,316,643 | 73.8% |
| Interpreter decrefs | 7,937,652,881 | 74.5% |
| Increfs | 2,559,207,326 | 26.2% |
| Decrefs | 2,721,818,484 | 25.5% |
| Materialize dict (on request) | 660 | 0.0% |
| Materialize dict (new key) | 2,300 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 400 | 0.0% |
| Method cache hits | 421,287,257 |  |
| Method cache misses | 9,376,288 |  |
| Method cache collisions | 12,463,532 |  |
| Method cache dunder hits | 354,689,109 |  |
| Method cache dunder misses | 3,338,593 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 360 | 406,300 | 860,978,440 |
| 1 | 40 | 42,188,720 | 747,100,480 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |
| Traces executed | 0 |  |
| Uops executed | 0 |  |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


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
