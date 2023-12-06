
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
| LOAD_FAST | 2,907,614,592 | 20.7% | 20.7% |  |
| LOAD_CONST | 692,492,695 | 4.9% | 25.6% |  |
| RESUME_CHECK | 690,256,092 | 4.9% | 30.5% | 0.0% |
| STORE_ATTR_SLOT | 611,808,847 | 4.3% | 34.8% | 21.5% |
| LOAD_GLOBAL_MODULE | 605,336,502 | 4.3% | 39.1% | 0.0% |
| LOAD_FAST_LOAD_FAST | 562,268,373 | 4.0% | 43.1% |  |
| LOAD_GLOBAL_BUILTIN | 544,844,888 | 3.9% | 47.0% | 0.0% |
| POP_JUMP_IF_FALSE | 543,517,928 | 3.9% | 50.9% |  |
| LOAD_ATTR_SLOT | 493,819,581 | 3.5% | 54.4% | 1.7% |
| STORE_FAST | 490,493,564 | 3.5% | 57.9% |  |
| CALL_PY_EXACT_ARGS | 433,909,292 | 3.1% | 60.9% | 10.3% |
| TO_BOOL_BOOL | 411,475,236 | 2.9% | 63.9% | 0.0% |
| RETURN_VALUE | 396,228,958 | 2.8% | 66.7% |  |
| RETURN_CONST | 299,925,416 | 2.1% | 68.8% |  |
| CALL_ISINSTANCE | 274,837,290 | 2.0% | 70.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 261,776,601 | 1.9% | 72.6% | 21.8% |
| POP_TOP | 219,956,917 | 1.6% | 74.2% |  |
| POP_JUMP_IF_TRUE | 218,646,787 | 1.6% | 75.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 154,479,062 | 1.1% | 76.8% | 3.6% |
| LOAD_DEREF | 129,300,297 | 0.9% | 77.8% |  |
| FOR_ITER_LIST | 122,950,723 | 0.9% | 78.6% | 1.6% |
| INTERPRETER_EXIT | 120,922,467 | 0.9% | 79.5% |  |
| GET_ITER | 120,435,135 | 0.9% | 80.4% |  |
| BINARY_SUBSCR_DICT | 117,623,843 | 0.8% | 81.2% |  |
| ENTER_EXECUTOR | 117,019,311 | 0.8% | 82.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 113,266,923 | 0.8% | 82.8% | 12.9% |
| LOAD_ATTR | 111,342,639 | 0.8% | 83.6% |  |
| POP_JUMP_IF_NOT_NONE | 95,232,200 | 0.7% | 84.3% |  |
| COPY_FREE_VARS | 93,982,771 | 0.7% | 85.0% |  |
| CONTAINS_OP | 92,895,755 | 0.7% | 85.6% |  |
| SWAP | 87,534,380 | 0.6% | 86.2% |  |
| LOAD_SUPER_ATTR_METHOD | 86,018,980 | 0.6% | 86.9% |  |
| BUILD_LIST | 82,844,452 | 0.6% | 87.4% |  |
| POP_JUMP_IF_NONE | 79,969,980 | 0.6% | 88.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 78,000,900 | 0.6% | 88.6% | 2.2% |
| CALL_KW | 76,507,100 | 0.5% | 89.1% |  |
| CALL | 68,559,900 | 0.5% | 89.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 63,046,812 | 0.4% | 90.0% | 8.8% |
| IS_OP | 56,759,400 | 0.4% | 90.4% |  |
| NOP | 53,251,820 | 0.4% | 90.8% |  |
| COPY | 50,538,425 | 0.4% | 91.2% |  |
| JUMP_FORWARD | 47,248,248 | 0.3% | 91.5% |  |
| TO_BOOL_LIST | 45,693,200 | 0.3% | 91.8% | 0.7% |
| COMPARE_OP_STR | 43,386,490 | 0.3% | 92.2% | 0.3% |
| COMPARE_OP | 42,326,384 | 0.3% | 92.5% |  |
| BINARY_SUBSCR | 40,306,208 | 0.3% | 92.7% |  |
| CALL_BUILTIN_CLASS | 40,270,448 | 0.3% | 93.0% |  |
| COMPARE_OP_INT | 37,579,406 | 0.3% | 93.3% | 2.1% |
| CALL_LEN | 35,483,480 | 0.3% | 93.5% |  |
| PUSH_NULL | 34,721,046 | 0.2% | 93.8% |  |
| MAKE_CELL | 33,215,020 | 0.2% | 94.0% |  |
| CALL_LIST_APPEND | 32,144,400 | 0.2% | 94.3% |  |
| TO_BOOL_NONE | 32,071,935 | 0.2% | 94.5% | 8.3% |
| BUILD_TUPLE | 31,504,830 | 0.2% | 94.7% |  |
| EXTENDED_ARG | 31,275,900 | 0.2% | 94.9% |  |
| LOAD_ATTR_WITH_HINT | 30,574,820 | 0.2% | 95.1% | 2.1% |
| FOR_ITER_TUPLE | 30,195,479 | 0.2% | 95.4% | 6.4% |
| MAP_ADD | 29,553,700 | 0.2% | 95.6% |  |
| TO_BOOL_ALWAYS_TRUE | 29,119,845 | 0.2% | 95.8% | 13.2% |
| LOAD_FAST_AND_CLEAR | 27,810,960 | 0.2% | 96.0% |  |
| LOAD_ATTR_PROPERTY | 27,339,592 | 0.2% | 96.2% | 6.6% |
| UNARY_NOT | 26,161,520 | 0.2% | 96.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 26,000,480 | 0.2% | 96.5% | 30.9% |
| LOAD_ATTR_MODULE | 25,670,424 | 0.2% | 96.7% | 0.0% |
| LIST_APPEND | 25,398,674 | 0.2% | 96.9% |  |
| STORE_FAST_STORE_FAST | 24,983,648 | 0.2% | 97.1% |  |
| CALL_PY_WITH_DEFAULTS | 20,721,240 | 0.1% | 97.2% | 2.1% |
| TO_BOOL | 20,336,640 | 0.1% | 97.4% |  |
| CALL_TUPLE_1 | 20,335,332 | 0.1% | 97.5% |  |
| FOR_ITER | 18,581,213 | 0.1% | 97.6% |  |
| BINARY_SUBSCR_LIST_INT | 18,552,240 | 0.1% | 97.8% | 0.0% |
| CALL_BUILTIN_O | 15,813,898 | 0.1% | 97.9% | 8.4% |
| LOAD_ATTR_CLASS | 14,897,440 | 0.1% | 98.0% | 2.4% |
| UNPACK_SEQUENCE_LIST | 14,536,280 | 0.1% | 98.1% |  |
| CALL_BUILTIN_FAST | 12,792,595 | 0.1% | 98.2% | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 11,866,874 | 0.1% | 98.3% | 0.0% |
| STORE_ATTR | 11,621,400 | 0.1% | 98.4% |  |
| DELETE_ATTR | 11,254,400 | 0.1% | 98.4% |  |
| YIELD_VALUE | 11,222,484 | 0.1% | 98.5% |  |
| CALL_TYPE_1 | 11,112,060 | 0.1% | 98.6% |  |
| BUILD_MAP | 11,070,599 | 0.1% | 98.7% |  |
| FOR_ITER_RANGE | 9,438,439 | 0.1% | 98.7% |  |
| TO_BOOL_STR | 9,264,680 | 0.1% | 98.8% | 3.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 8,632,128 | 0.1% | 98.9% |  |
| MAKE_FUNCTION | 8,222,240 | 0.1% | 98.9% |  |
| CALL_FUNCTION_EX | 7,966,320 | 0.1% | 99.0% |  |
| RETURN_GENERATOR | 7,785,480 | 0.1% | 99.0% |  |
| STORE_FAST_LOAD_FAST | 7,567,603 | 0.1% | 99.1% |  |
| BINARY_OP_ADD_INT | 7,561,945 | 0.1% | 99.2% | 0.5% |
| CALL_ALLOC_AND_ENTER_INIT | 6,667,940 | 0.0% | 99.2% | 0.1% |
| EXIT_INIT_CHECK | 6,658,880 | 0.0% | 99.2% |  |
| BINARY_SLICE | 5,855,740 | 0.0% | 99.3% |  |
| BINARY_OP_ADD_UNICODE | 5,486,260 | 0.0% | 99.3% |  |
| SET_FUNCTION_ATTRIBUTE | 5,160,240 | 0.0% | 99.4% |  |
| STORE_SUBSCR_DICT | 4,858,802 | 0.0% | 99.4% |  |
| STORE_DEREF | 4,722,300 | 0.0% | 99.4% |  |
| BINARY_OP | 4,659,120 | 0.0% | 99.5% |  |
| CHECK_EXC_MATCH | 4,152,160 | 0.0% | 99.5% |  |
| POP_EXCEPT | 4,152,160 | 0.0% | 99.5% |  |
| PUSH_EXC_INFO | 4,152,160 | 0.0% | 99.6% |  |
| DICT_MERGE | 3,864,720 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_INT | 3,814,915 | 0.0% | 99.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,801,820 | 0.0% | 99.6% | 0.0% |
| STORE_SUBSCR | 3,770,760 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,030,180 | 0.0% | 99.7% | 11.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,863,920 | 0.0% | 99.7% |  |
| LOAD_FAST_CHECK | 2,822,800 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_GETITEM | 2,792,220 | 0.0% | 99.7% | 0.0% |
| BEFORE_WITH | 2,676,160 | 0.0% | 99.8% |  |
| IMPORT_FROM | 2,427,840 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 2,366,180 | 0.0% | 99.8% |  |
| IMPORT_NAME | 1,983,200 | 0.0% | 99.8% |  |
| UNARY_NEGATIVE | 1,949,620 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TUPLE | 1,912,780 | 0.0% | 99.8% |  |
| TO_BOOL_INT | 1,883,172 | 0.0% | 99.9% | 4.5% |
| BUILD_SET | 1,879,120 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,754,620 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 1,643,940 | 0.0% | 99.9% | 3.1% |
| JUMP_BACKWARD | 1,522,060 | 0.0% | 99.9% |  |
| BUILD_STRING | 1,456,140 | 0.0% | 99.9% |  |
| SET_ADD | 1,398,458 | 0.0% | 99.9% |  |
| FOR_ITER_GEN | 1,327,900 | 0.0% | 99.9% |  |
| CALL_STR_1 | 1,219,380 | 0.0% | 99.9% |  |
| LOAD_SUPER_ATTR_ATTR | 1,083,160 | 0.0% | 99.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,069,720 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,067,560 | 0.0% | 100.0% | 1.9% |
| BINARY_SUBSCR_STR_INT | 943,859 | 0.0% | 100.0% | 0.0% |
| BINARY_OP_INPLACE_ADD_UNICODE | 573,120 | 0.0% | 100.0% |  |
| RERAISE | 543,680 | 0.0% | 100.0% |  |
| SEND_GEN | 464,004 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 433,000 | 0.0% | 100.0% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 368,064 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 339,600 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 293,220 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 287,220 | 0.0% | 100.0% | 13.6% |
| LOAD_GLOBAL | 242,840 | 0.0% | 100.0% |  |
| DELETE_FAST | 201,920 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 193,100 | 0.0% | 100.0% |  |
| LIST_EXTEND | 150,540 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 138,050 | 0.0% | 100.0% |  |
| END_SEND | 96,000 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 96,000 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 75,900 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 67,960 | 0.0% | 100.0% |  |
| END_FOR | 54,080 | 0.0% | 100.0% |  |
| RESUME | 40,880 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 32,920 | 0.0% | 100.0% |  |
| BUILD_SLICE | 18,360 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 5,480 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 4,820 | 0.0% | 100.0% |  |
| STORE_NAME | 2,240 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,100 | 0.0% | 100.0% |  |
| UNARY_INVERT | 1,560 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 1,260 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 1,240 | 0.0% | 100.0% |  |
| STORE_SLICE | 960 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 680 | 0.0% | 100.0% |  |
| UNPACK_EX | 540 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_SLOT | 435,327,809 | 3.1% | 3.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 378,510,848 | 2.7% | 5.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 376,185,842 | 2.7% | 8.5% |
| LOAD_FAST STORE_ATTR_SLOT | 359,778,866 | 2.6% | 11.0% |
| RESUME_CHECK LOAD_FAST | 301,881,070 | 2.1% | 13.2% |
| LOAD_CONST LOAD_FAST | 280,807,944 | 2.0% | 15.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 277,350,368 | 2.0% | 17.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 269,201,099 | 1.9% | 19.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 268,589,146 | 1.9% | 20.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 253,230,916 | 1.8% | 22.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 248,585,380 | 1.8% | 24.5% |
| STORE_FAST LOAD_FAST | 240,614,224 | 1.7% | 26.2% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 232,120,226 | 1.6% | 27.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 188,878,819 | 1.3% | 29.2% |
| STORE_ATTR_SLOT LOAD_CONST | 170,370,120 | 1.2% | 30.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 168,107,118 | 1.2% | 31.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 162,096,682 | 1.2% | 32.8% |
| LOAD_FAST LOAD_CONST | 153,655,501 | 1.1% | 33.9% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 141,091,380 | 1.0% | 34.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 132,510,276 | 0.9% | 35.8% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 124,251,480 | 0.9% | 36.7% |
| STORE_ATTR_SLOT RETURN_CONST | 120,875,220 | 0.9% | 37.5% |
| LOAD_FAST RETURN_VALUE | 118,465,860 | 0.8% | 38.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 116,509,350 | 0.8% | 39.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 116,420,191 | 0.8% | 40.0% |
| STORE_ATTR_SLOT LOAD_FAST | 112,443,606 | 0.8% | 40.8% |
| RETURN_CONST POP_TOP | 105,683,920 | 0.8% | 41.6% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 102,307,746 | 0.7% | 42.3% |
| LOAD_CONST BINARY_SUBSCR_DICT | 101,555,560 | 0.7% | 43.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 100,866,548 | 0.7% | 43.8% |
| POP_JUMP_IF_TRUE LOAD_FAST | 97,578,101 | 0.7% | 44.5% |
| POP_TOP LOAD_FAST | 93,750,254 | 0.7% | 45.1% |
| COPY_FREE_VARS RESUME_CHECK | 93,013,820 | 0.7% | 45.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 92,613,921 | 0.7% | 46.4% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 92,064,060 | 0.7% | 47.1% |
| RETURN_VALUE STORE_FAST | 90,211,628 | 0.6% | 47.7% |
| LOAD_DEREF LOAD_FAST | 88,095,658 | 0.6% | 48.4% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 86,016,580 | 0.6% | 49.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 83,277,580 | 0.6% | 49.6% |
| RETURN_VALUE RETURN_VALUE | 80,684,667 | 0.6% | 50.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 79,441,144 | 0.6% | 50.7% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 78,393,224 | 0.6% | 51.3% |
| LOAD_FAST LOAD_FAST | 77,082,200 | 0.5% | 51.8% |
| LOAD_CONST CALL_KW | 74,964,360 | 0.5% | 52.3% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 74,527,972 | 0.5% | 52.9% |
| LOAD_FAST LOAD_ATTR | 74,509,839 | 0.5% | 53.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 72,231,744 | 0.5% | 53.9% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 71,619,920 | 0.5% | 54.4% |
| CACHE RESUME_CHECK | 69,747,627 | 0.5% | 54.9% |
| RESUME_CHECK RETURN_CONST | 67,668,480 | 0.5% | 55.4% |
| RETURN_CONST INTERPRETER_EXIT | 61,992,140 | 0.4% | 55.8% |
| RETURN_CONST LOAD_FAST | 61,621,760 | 0.4% | 56.3% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 60,441,560 | 0.4% | 56.7% |
| LOAD_ATTR_SLOT LOAD_FAST | 59,740,366 | 0.4% | 57.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 58,568,007 | 0.4% | 57.5% |
| LOAD_CONST LOAD_CONST | 53,485,200 | 0.4% | 57.9% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 53,166,420 | 0.4% | 58.3% |
| FOR_ITER_LIST STORE_FAST | 53,079,066 | 0.4% | 58.7% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 51,802,928 | 0.4% | 59.0% |
| RETURN_VALUE LOAD_FAST | 50,110,900 | 0.4% | 59.4% |
| LOAD_ATTR LOAD_FAST | 49,747,040 | 0.4% | 59.8% |
| RETURN_VALUE INTERPRETER_EXIT | 49,256,287 | 0.4% | 60.1% |
| LOAD_ATTR_SLOT GET_ITER | 47,884,756 | 0.3% | 60.4% |
| ENTER_EXECUTOR FOR_ITER_LIST | 47,857,451 | 0.3% | 60.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 47,565,700 | 0.3% | 61.1% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 47,448,651 | 0.3% | 61.5% |
| LOAD_FAST CONTAINS_OP | 46,586,524 | 0.3% | 61.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 45,757,800 | 0.3% | 62.1% |
| GET_ITER FOR_ITER_LIST | 44,683,783 | 0.3% | 62.4% |
| LOAD_ATTR_SLOT STORE_FAST | 44,469,340 | 0.3% | 62.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 44,208,940 | 0.3% | 63.1% |
| CACHE COPY_FREE_VARS | 43,492,280 | 0.3% | 63.4% |
| CALL_KW RESUME_CHECK | 43,426,700 | 0.3% | 63.7% |
| RETURN_CONST RETURN_VALUE | 42,797,460 | 0.3% | 64.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 41,696,905 | 0.3% | 64.3% |
| LOAD_GLOBAL_MODULE IS_OP | 41,593,560 | 0.3% | 64.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 39,480,360 | 0.3% | 64.9% |
| LOAD_FAST POP_JUMP_IF_NONE | 38,884,500 | 0.3% | 65.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 38,587,552 | 0.3% | 65.4% |
| COPY TO_BOOL_BOOL | 38,447,030 | 0.3% | 65.7% |
| IS_OP POP_JUMP_IF_FALSE | 38,094,420 | 0.3% | 66.0% |
| POP_JUMP_IF_NONE LOAD_FAST | 38,032,540 | 0.3% | 66.2% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 36,996,740 | 0.3% | 66.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 36,619,080 | 0.3% | 66.8% |
| LOAD_ATTR_SLOT RETURN_VALUE | 36,495,326 | 0.3% | 67.0% |
| POP_TOP LOAD_FAST_LOAD_FAST | 35,282,040 | 0.3% | 67.3% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 35,038,560 | 0.2% | 67.5% |
| TO_BOOL_LIST POP_JUMP_IF_TRUE | 34,742,340 | 0.2% | 67.8% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 34,706,422 | 0.2% | 68.0% |
| LOAD_FAST TO_BOOL_LIST | 34,675,680 | 0.2% | 68.2% |
| RETURN_VALUE POP_TOP | 34,490,380 | 0.2% | 68.5% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 34,393,959 | 0.2% | 68.7% |
| LOAD_FAST TO_BOOL_BOOL | 34,143,280 | 0.2% | 69.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 32,734,280 | 0.2% | 69.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 32,505,920 | 0.2% | 69.4% |
| BUILD_LIST STORE_FAST | 31,885,884 | 0.2% | 69.7% |
| STORE_ATTR_SLOT LOAD_GLOBAL_BUILTIN | 31,685,060 | 0.2% | 69.9% |
| LOAD_CONST COMPARE_OP_STR | 30,940,896 | 0.2% | 70.1% |
| LOAD_ATTR_SLOT POP_JUMP_IF_NONE | 30,484,020 | 0.2% | 70.3% |
| NOP LOAD_FAST | 29,997,840 | 0.2% | 70.5% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,453,440 | 76.1% |
| BINARY_OP_SUBTRACT_INT | 890,220 | 15.2% |
| LOAD_FAST | 377,500 | 6.4% |
| BINARY_OP_ADD_INT | 101,380 | 1.7% |
| LOAD_ATTR_SLOT | 23,980 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,339,560 | 40.0% |
| CALL_PY_EXACT_ARGS | 890,980 | 15.2% |
| STORE_FAST | 700,940 | 12.0% |
| GET_ITER | 646,400 | 11.0% |
| BUILD_TUPLE | 301,560 | 5.1% |


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
| RESUME_CHECK | 69,747,627 | 57.7% |
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
| ENTER_EXECUTOR | 523,880 | 91.4% |
| LOAD_FAST | 46,400 | 8.1% |
| JUMP_FORWARD | 1,260 | 0.2% |
| LOAD_FAST_LOAD_FAST | 940 | 0.2% |
| JUMP_BACKWARD | 640 | 0.1% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 19,888,028 | 49.3% |
| LOAD_FAST_LOAD_FAST | 15,020,700 | 37.3% |
| LOAD_FAST | 3,486,554 | 8.7% |
| LOAD_GLOBAL_MODULE | 1,199,040 | 3.0% |
| COPY | 287,400 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,157,754 | 42.6% |
| CONTAINS_OP | 4,464,740 | 11.1% |
| LOAD_CONST | 4,336,080 | 10.8% |
| LOAD_FAST | 3,199,660 | 7.9% |
| RETURN_VALUE | 2,830,040 | 7.0% |


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
| LOAD_CONST | 43,200 | 56.9% |
| BUILD_SLICE | 17,280 | 22.8% |
| LOAD_FAST | 12,540 | 16.5% |
| LOAD_FAST_LOAD_FAST | 2,880 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 54,340 | 71.6% |
| LOAD_DEREF | 17,280 | 22.8% |
| RETURN_CONST | 1,920 | 2.5% |
| JUMP_BACKWARD | 1,340 | 1.8% |
| LOAD_FAST | 640 | 0.8% |


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
| LOAD_FAST | 1,540,100 | 65.1% |
| RETURN_VALUE | 413,360 | 17.5% |
| BINARY_SUBSCR_TUPLE_INT | 281,600 | 11.9% |
| CONVERT_VALUE | 67,960 | 2.9% |
| LOAD_ATTR_SLOT | 38,660 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,384,940 | 58.5% |
| BUILD_STRING | 981,240 | 41.5% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 920 | 74.2% |
| LOAD_CONST | 320 | 25.8% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 47,884,756 | 39.8% |
| LOAD_FAST | 28,626,260 | 23.8% |
| CALL_BUILTIN_CLASS | 19,031,320 | 15.8% |
| BINARY_SUBSCR_DICT | 12,484,620 | 10.4% |
| CALL | 2,651,080 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 44,683,783 | 37.1% |
| LOAD_FAST_AND_CLEAR | 26,563,500 | 22.1% |
| FOR_ITER_TUPLE | 18,935,952 | 15.7% |
| FOR_ITER | 14,523,340 | 12.1% |
| FOR_ITER_RANGE | 5,973,100 | 5.0% |


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
| RETURN_VALUE | 49,256,287 | 40.7% |
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
| LOAD_CONST | 8,222,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,158,500 | 50.6% |
| SET_FUNCTION_ATTRIBUTE | 3,988,700 | 48.5% |
| LOAD_CONST | 48,060 | 0.6% |
| LOAD_GLOBAL_MODULE | 14,280 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 7,240 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,134,240 | 28.4% |
| POP_JUMP_IF_TRUE | 14,082,560 | 26.4% |
| POP_JUMP_IF_FALSE | 9,176,260 | 17.2% |
| RESUME_CHECK | 6,477,180 | 12.2% |
| CALL_LIST_APPEND | 2,435,240 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,997,840 | 56.3% |
| LOAD_CONST | 14,777,960 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 4,744,820 | 8.9% |
| LOAD_GLOBAL_MODULE | 3,054,440 | 5.7% |
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
| ENTER_EXECUTOR | 13,560 | 0.3% |
| JUMP_BACKWARD | 960 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 105,683,920 | 48.0% |
| RETURN_VALUE | 34,490,380 | 15.7% |
| POP_JUMP_IF_FALSE | 20,651,395 | 9.4% |
| POP_JUMP_IF_TRUE | 17,345,312 | 7.9% |
| RESUME_CHECK | 8,001,720 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,750,254 | 42.6% |
| LOAD_FAST_LOAD_FAST | 35,282,040 | 16.0% |
| ENTER_EXECUTOR | 26,757,734 | 12.2% |
| RETURN_CONST | 22,997,920 | 10.5% |
| LOAD_CONST | 8,837,200 | 4.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 2,282,200 | 55.0% |
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
| LOAD_FAST | 17,628,995 | 50.8% |
| LOAD_ATTR | 8,407,160 | 24.2% |
| LOAD_ATTR_MODULE | 4,893,100 | 14.1% |
| BINARY_SUBSCR_DICT | 1,481,440 | 4.3% |
| LOAD_SUPER_ATTR_ATTR | 1,077,400 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,929,966 | 80.4% |
| LOAD_FAST_LOAD_FAST | 5,611,280 | 16.2% |
| CALL | 569,700 | 1.6% |
| LOAD_CONST | 283,100 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 187,560 | 0.5% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,222,960 | 54.2% |
| CALL_FUNCTION_EX | 2,281,920 | 29.3% |
| COPY_FREE_VARS | 965,871 | 12.4% |
| ENTER_EXECUTOR | 216,549 | 2.8% |
| CACHE | 93,440 | 1.2% |

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
| LOAD_FAST | 118,465,860 | 29.9% |
| RETURN_VALUE | 80,684,667 | 20.4% |
| RETURN_CONST | 42,797,460 | 10.8% |
| LOAD_ATTR_SLOT | 36,495,326 | 9.2% |
| CALL | 12,594,440 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 90,211,628 | 22.8% |
| RETURN_VALUE | 80,684,667 | 20.4% |
| LOAD_FAST | 50,110,900 | 12.6% |
| INTERPRETER_EXIT | 49,256,287 | 12.4% |
| POP_TOP | 34,490,380 | 8.7% |


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
| LOAD_FAST_LOAD_FAST | 3,032,460 | 80.4% |
| LOAD_FAST | 346,800 | 9.2% |
| SWAP | 287,400 | 7.6% |
| LOAD_CONST | 79,980 | 2.1% |
| LOAD_ATTR_SLOT | 17,340 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,031,400 | 80.4% |
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
| LOAD_ATTR | 9,397,760 | 46.2% |
| LOAD_FAST | 6,900,400 | 33.9% |
| LOAD_ATTR_SLOT | 2,678,080 | 13.2% |
| COPY | 1,088,700 | 5.4% |
| LOAD_ATTR_WITH_HINT | 73,100 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,012,940 | 83.7% |
| POP_JUMP_IF_TRUE | 2,871,880 | 14.1% |
| UNARY_NOT | 294,700 | 1.4% |
| TO_BOOL_BOOL | 48,620 | 0.2% |
| TO_BOOL | 43,800 | 0.2% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,340 | 85.9% |
| LOAD_FAST | 220 | 14.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,560 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,008,820 | 51.7% |
| CALL_LEN | 890,520 | 45.7% |
| LOAD_GLOBAL_MODULE | 23,660 | 1.2% |
| CALL | 17,320 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 9,260 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 890,240 | 45.7% |
| COMPARE_OP_INT | 890,200 | 45.7% |
| CALL_PY_EXACT_ARGS | 86,360 | 4.4% |
| RETURN_VALUE | 26,560 | 1.4% |
| BUILD_TUPLE | 23,680 | 1.2% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 22,824,820 | 87.2% |
| TO_BOOL_LIST | 2,525,220 | 9.7% |
| TO_BOOL_STR | 369,580 | 1.4% |
| TO_BOOL | 294,700 | 1.1% |
| TO_BOOL_INT | 139,280 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,688,620 | 52.3% |
| RETURN_VALUE | 9,197,440 | 35.2% |
| COPY | 2,570,320 | 9.8% |
| LOAD_FAST | 456,960 | 1.7% |
| STORE_FAST | 152,320 | 0.6% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 2,644,140 | 56.8% |
| LOAD_FAST | 456,880 | 9.8% |
| BUILD_LIST | 374,160 | 8.0% |
| STORE_FAST | 346,600 | 7.4% |
| LOAD_ATTR | 190,080 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,900,760 | 40.8% |
| STORE_FAST | 1,219,440 | 26.2% |
| CALL_PY_EXACT_ARGS | 507,920 | 10.9% |
| GET_ITER | 210,600 | 4.5% |
| LOAD_CONST | 133,420 | 2.9% |


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
| SWAP | 24,162,740 | 29.2% |
| STORE_FAST | 18,511,800 | 22.3% |
| LOAD_GLOBAL_MODULE | 11,115,600 | 13.4% |
| RESUME_CHECK | 8,691,080 | 10.5% |
| STORE_ATTR_SLOT | 4,211,900 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,885,884 | 38.5% |
| SWAP | 24,162,740 | 29.2% |
| CALL | 11,485,520 | 13.9% |
| LOAD_FAST | 8,091,560 | 9.8% |
| LOAD_GLOBAL_BUILTIN | 2,538,120 | 3.1% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,105,940 | 37.1% |
| LOAD_CONST | 1,666,280 | 15.1% |
| STORE_ATTR_INSTANCE_VALUE | 960,220 | 8.7% |
| RESUME_CHECK | 883,400 | 8.0% |
| POP_JUMP_IF_FALSE | 796,480 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,354,680 | 57.4% |
| LOAD_CONST | 1,611,560 | 14.6% |
| STORE_FAST | 1,482,099 | 13.4% |
| SWAP | 654,220 | 5.9% |
| RETURN_VALUE | 271,360 | 2.5% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,747,280 | 93.0% |
| LOAD_CONST | 109,760 | 5.8% |
| LOAD_FAST | 21,760 | 1.2% |
| POP_JUMP_IF_FALSE | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,747,280 | 93.0% |
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
| FORMAT_SIMPLE | 981,240 | 67.4% |
| LOAD_CONST | 474,900 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 478,180 | 32.8% |
| RETURN_VALUE | 376,640 | 25.9% |
| LOAD_FAST | 167,520 | 11.5% |
| CALL | 94,220 | 6.5% |
| CALL_PY_EXACT_ARGS | 85,400 | 5.9% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,035,752 | 35.0% |
| LOAD_GLOBAL_MODULE | 5,212,920 | 16.5% |
| LOAD_ATTR_SLOT | 5,109,446 | 16.2% |
| LOAD_FAST_LOAD_FAST | 4,347,800 | 13.8% |
| LOAD_ATTR_INSTANCE_VALUE | 2,366,980 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,312,580 | 26.4% |
| CALL_BUILTIN_O | 5,669,858 | 18.0% |
| CALL_ISINSTANCE | 4,526,280 | 14.4% |
| LOAD_CONST | 3,990,300 | 12.7% |
| LOAD_FAST | 3,557,320 | 11.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,571,095 | 18.3% |
| BUILD_LIST | 11,485,520 | 16.8% |
| ENTER_EXECUTOR | 6,987,253 | 10.2% |
| LOAD_FAST_LOAD_FAST | 6,948,100 | 10.1% |
| RETURN_VALUE | 5,677,250 | 8.3% |

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
| LOAD_CONST | 74,964,360 | 98.0% |
| ENTER_EXECUTOR | 1,542,740 | 2.0% |

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
| LOAD_ATTR_SLOT | 18,253,241 | 43.1% |
| LOAD_GLOBAL_MODULE | 8,564,900 | 20.2% |
| LOAD_CONST | 7,772,227 | 18.4% |
| LOAD_ATTR_MODULE | 2,742,060 | 6.5% |
| LOAD_FAST | 2,161,120 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 16,887,270 | 39.9% |
| POP_JUMP_IF_FALSE | 13,132,547 | 31.0% |
| RETURN_VALUE | 8,404,849 | 19.9% |
| POP_JUMP_IF_TRUE | 2,606,920 | 6.2% |
| EXTENDED_ARG | 1,029,600 | 2.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,586,524 | 50.1% |
| LOAD_FAST_LOAD_FAST | 17,331,074 | 18.7% |
| LOAD_ATTR_INSTANCE_VALUE | 7,875,400 | 8.5% |
| LOAD_ATTR_SLOT | 4,854,684 | 5.2% |
| BINARY_SUBSCR | 4,464,740 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 78,393,224 | 84.4% |
| POP_JUMP_IF_TRUE | 10,806,031 | 11.6% |
| RETURN_VALUE | 2,852,620 | 3.1% |
| EXTENDED_ARG | 466,860 | 0.5% |
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
| COMPARE_OP | 16,887,270 | 33.4% |
| LOAD_FAST | 6,124,520 | 12.1% |
| CALL_ISINSTANCE | 4,208,200 | 8.3% |
| SWAP | 3,583,640 | 7.1% |
| COMPARE_OP_STR | 3,095,604 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 38,447,030 | 76.1% |
| COMPARE_OP_INT | 3,580,400 | 7.1% |
| TO_BOOL_NONE | 1,795,240 | 3.6% |
| TO_BOOL_STR | 1,506,780 | 3.0% |
| TO_BOOL | 1,088,700 | 2.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 47,448,651 | 50.5% |
| CACHE | 43,492,280 | 46.3% |
| CALL | 1,923,440 | 2.0% |
| CALL_ALLOC_AND_ENTER_INIT | 450,680 | 0.5% |
| CALL_KW | 424,320 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 93,013,820 | 99.0% |
| RETURN_GENERATOR | 965,871 | 1.0% |
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
| JUMP_BACKWARD | 340 | 0.2% |
| ENTER_EXECUTOR | 300 | 0.1% |


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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 29,858,863 | 25.5% |
| POP_TOP | 26,757,734 | 22.9% |
| LIST_APPEND | 25,355,474 | 21.7% |
| CALL_LIST_APPEND | 9,371,520 | 8.0% |
| EXTENDED_ARG | 6,459,920 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 47,857,451 | 40.9% |
| FOR_ITER_TUPLE | 8,469,572 | 7.2% |
| LOAD_ATTR_METHOD_NO_DICT | 8,176,127 | 7.0% |
| CALL | 6,987,253 | 6.0% |
| RESUME_CHECK | 5,441,120 | 4.6% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,432,860 | 33.4% |
| GET_ITER | 4,616,320 | 14.8% |
| POP_TOP | 3,421,980 | 10.9% |
| ENTER_EXECUTOR | 1,477,820 | 4.7% |
| LOAD_ATTR_SLOT | 1,255,320 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,950,100 | 47.8% |
| ENTER_EXECUTOR | 6,459,920 | 20.7% |
| FOR_ITER | 3,156,660 | 10.1% |
| FOR_ITER_LIST | 2,643,740 | 8.5% |
| POP_JUMP_IF_NONE | 2,423,400 | 7.7% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,523,340 | 78.2% |
| EXTENDED_ARG | 3,156,660 | 17.0% |
| SWAP | 723,760 | 3.9% |
| LOAD_FAST | 82,460 | 0.4% |
| JUMP_BACKWARD | 55,614 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 5,766,928 | 31.0% |
| RETURN_CONST | 4,383,366 | 23.6% |
| STORE_FAST | 3,860,303 | 20.8% |
| LOAD_FAST | 2,252,492 | 12.1% |
| LOAD_GLOBAL_BUILTIN | 556,360 | 3.0% |


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
| LOAD_GLOBAL_MODULE | 41,593,560 | 73.3% |
| LOAD_CONST | 7,084,200 | 12.5% |
| LOAD_FAST | 6,995,440 | 12.3% |
| LOAD_FAST_LOAD_FAST | 890,240 | 1.6% |
| LOAD_ATTR | 95,800 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 38,094,420 | 67.1% |
| POP_JUMP_IF_TRUE | 11,627,840 | 20.5% |
| RETURN_VALUE | 4,012,960 | 7.1% |
| LOAD_FAST | 1,637,440 | 2.9% |
| COPY | 801,380 | 1.4% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,172,680 | 77.0% |
| CALL_LIST_APPEND | 106,340 | 7.0% |
| POP_TOP | 93,480 | 6.1% |
| LIST_APPEND | 43,200 | 2.8% |
| POP_JUMP_IF_FALSE | 29,680 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 1,230,940 | 80.9% |
| FOR_ITER_LIST | 157,002 | 10.3% |
| FOR_ITER | 55,614 | 3.7% |
| EXTENDED_ARG | 33,920 | 2.2% |
| ENTER_EXECUTOR | 15,780 | 1.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 368,004 | 100.0% |
| RESUME | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 368,024 | 100.0% |
| SEND | 40 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 14,018,240 | 29.7% |
| LOAD_ATTR_SLOT | 13,640,820 | 28.9% |
| LOAD_FAST | 6,605,720 | 14.0% |
| STORE_ATTR_SLOT | 5,506,940 | 11.7% |
| STORE_FAST | 3,796,175 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,511,148 | 49.8% |
| STORE_FAST | 14,581,440 | 30.9% |
| MAP_ADD | 6,275,520 | 13.3% |
| LOAD_CONST | 1,026,560 | 2.2% |
| LOAD_GLOBAL_MODULE | 958,505 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 15,132,200 | 59.6% |
| CALL | 7,028,600 | 27.7% |
| LOAD_FAST | 1,585,214 | 6.2% |
| BINARY_SUBSCR_LIST_INT | 336,300 | 1.3% |
| LOAD_ATTR_SLOT | 308,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 25,355,474 | 99.8% |
| JUMP_BACKWARD | 43,200 | 0.2% |


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
| LOAD_FAST | 74,509,839 | 66.9% |
| LOAD_GLOBAL_MODULE | 27,794,100 | 25.0% |
| LOAD_ATTR_INSTANCE_VALUE | 2,611,180 | 2.3% |
| LOAD_FAST_LOAD_FAST | 1,952,900 | 1.8% |
| CALL_TYPE_1 | 1,443,800 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,747,040 | 44.7% |
| LOAD_FAST_LOAD_FAST | 11,035,200 | 9.9% |
| TO_BOOL | 9,397,760 | 8.4% |
| PUSH_NULL | 8,407,160 | 7.6% |
| CALL_PY_EXACT_ARGS | 6,676,500 | 6.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 170,370,120 | 24.6% |
| LOAD_FAST | 153,655,501 | 22.2% |
| LOAD_CONST | 53,485,200 | 7.7% |
| LOAD_ATTR_INSTANCE_VALUE | 27,754,420 | 4.0% |
| MAP_ADD | 27,390,400 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,807,944 | 40.6% |
| BINARY_SUBSCR_DICT | 101,555,560 | 14.7% |
| CALL_KW | 74,964,360 | 10.8% |
| LOAD_CONST | 53,485,200 | 7.7% |
| COMPARE_OP_STR | 30,940,896 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 92,064,060 | 71.2% |
| LOAD_DEREF | 12,941,260 | 10.0% |
| LOAD_FAST | 5,428,087 | 4.2% |
| LOAD_GLOBAL_MODULE | 4,891,240 | 3.8% |
| POP_JUMP_IF_FALSE | 2,647,948 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,095,658 | 68.1% |
| LOAD_DEREF | 12,941,260 | 10.0% |
| LOAD_ATTR_SLOT | 7,774,220 | 6.0% |
| LOAD_CONST | 4,305,685 | 3.3% |
| LOAD_FAST_LOAD_FAST | 3,517,680 | 2.7% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 378,510,848 | 13.0% |
| RESUME_CHECK | 301,881,070 | 10.4% |
| LOAD_CONST | 280,807,944 | 9.7% |
| POP_JUMP_IF_FALSE | 253,230,916 | 8.7% |
| STORE_FAST | 240,614,224 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 435,327,809 | 15.0% |
| STORE_ATTR_SLOT | 359,778,866 | 12.4% |
| LOAD_GLOBAL_MODULE | 269,201,099 | 9.3% |
| LOAD_ATTR_METHOD_NO_DICT | 188,878,819 | 6.5% |
| CALL_PY_EXACT_ARGS | 162,096,682 | 5.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 26,563,500 | 95.5% |
| LOAD_FAST_AND_CLEAR | 1,247,460 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 26,552,620 | 95.5% |
| LOAD_FAST_AND_CLEAR | 1,247,460 | 4.5% |
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
| STORE_ATTR_SLOT | 141,091,380 | 25.1% |
| LOAD_SUPER_ATTR_METHOD | 71,619,920 | 12.7% |
| RESUME_CHECK | 60,441,560 | 10.7% |
| LOAD_GLOBAL_MODULE | 45,757,800 | 8.1% |
| STORE_FAST | 41,696,905 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 248,585,380 | 44.2% |
| CALL_PY_EXACT_ARGS | 102,307,746 | 18.2% |
| STORE_ATTR_INSTANCE_VALUE | 44,208,940 | 7.9% |
| LOAD_FAST | 38,587,552 | 6.9% |
| CONTAINS_OP | 17,331,074 | 3.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,600 | 18.8% |
| POP_JUMP_IF_FALSE | 44,630 | 18.4% |
| STORE_FAST | 38,320 | 15.8% |
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
| MAKE_CELL | 21,837,960 | 65.7% |
| CALL_PY_EXACT_ARGS | 4,877,300 | 14.7% |
| CALL_KW | 4,870,760 | 14.7% |
| BINARY_SUBSCR_GETITEM | 940,780 | 2.8% |
| CALL_PY_WITH_DEFAULTS | 585,560 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 21,837,960 | 65.7% |
| RESUME_CHECK | 11,361,980 | 34.2% |
| SWAP | 10,880 | 0.0% |
| RETURN_GENERATOR | 2,560 | 0.0% |
| RESUME | 1,640 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,114,540 | 71.4% |
| JUMP_FORWARD | 6,275,520 | 21.2% |
| CALL_BUILTIN_CLASS | 1,614,360 | 5.5% |
| LOAD_FAST | 256,640 | 0.9% |
| RETURN_VALUE | 160,380 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,390,400 | 92.7% |
| CALL_FUNCTION_EX | 1,611,200 | 5.5% |
| ENTER_EXECUTOR | 547,720 | 1.9% |
| JUMP_BACKWARD | 4,380 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 277,350,368 | 51.0% |
| CONTAINS_OP | 78,393,224 | 14.4% |
| IS_OP | 38,094,420 | 7.0% |
| TO_BOOL_ALWAYS_TRUE | 25,226,957 | 4.6% |
| TO_BOOL_NONE | 23,004,103 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 253,230,916 | 46.6% |
| LOAD_GLOBAL_BUILTIN | 132,510,276 | 24.4% |
| LOAD_GLOBAL_MODULE | 47,565,700 | 8.8% |
| LOAD_FAST_LOAD_FAST | 27,473,880 | 5.1% |
| POP_TOP | 20,651,395 | 3.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,884,500 | 48.6% |
| LOAD_ATTR_SLOT | 30,484,020 | 38.1% |
| LOAD_ATTR | 4,233,300 | 5.3% |
| EXTENDED_ARG | 2,423,400 | 3.0% |
| BINARY_SUBSCR_DICT | 2,092,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,032,540 | 47.6% |
| RETURN_CONST | 15,863,000 | 19.8% |
| JUMP_FORWARD | 14,018,240 | 17.5% |
| LOAD_CONST | 4,814,220 | 6.0% |
| LOAD_GLOBAL_BUILTIN | 3,115,530 | 3.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 83,277,580 | 87.4% |
| LOAD_ATTR_SLOT | 4,804,680 | 5.0% |
| BINARY_SUBSCR_DICT | 3,950,580 | 4.1% |
| LOAD_FAST_CHECK | 2,008,560 | 2.1% |
| BINARY_SUBSCR | 298,060 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 36,996,740 | 38.8% |
| LOAD_FAST | 19,852,520 | 20.8% |
| LOAD_CONST | 14,004,760 | 14.7% |
| LOAD_FAST_LOAD_FAST | 10,608,520 | 11.1% |
| RETURN_CONST | 4,656,000 | 4.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 100,866,548 | 46.1% |
| TO_BOOL_LIST | 34,742,340 | 15.9% |
| COMPARE_OP_STR | 26,905,472 | 12.3% |
| IS_OP | 11,627,840 | 5.3% |
| COMPARE_OP_INT | 11,207,886 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,578,101 | 44.6% |
| ENTER_EXECUTOR | 29,858,863 | 13.7% |
| LOAD_GLOBAL_MODULE | 22,149,195 | 10.1% |
| POP_TOP | 17,345,312 | 7.9% |
| NOP | 14,082,560 | 6.4% |


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
| STORE_ATTR_SLOT | 120,875,220 | 40.3% |
| RESUME_CHECK | 67,668,480 | 22.6% |
| POP_TOP | 22,997,920 | 7.7% |
| POP_JUMP_IF_FALSE | 17,975,620 | 6.0% |
| POP_JUMP_IF_NONE | 15,863,000 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 105,683,920 | 35.2% |
| INTERPRETER_EXIT | 61,992,140 | 20.7% |
| LOAD_FAST | 61,621,760 | 20.5% |
| RETURN_VALUE | 42,797,460 | 14.3% |
| TO_BOOL_BOOL | 11,431,000 | 3.8% |


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
| BINARY_OP_ADD_UNICODE | 1,280,880 | 91.6% |
| LOAD_ATTR_INSTANCE_VALUE | 63,180 | 4.5% |
| STORE_FAST_LOAD_FAST | 40,020 | 2.9% |
| LOAD_FAST | 6,798 | 0.5% |
| RETURN_VALUE | 6,400 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,393,678 | 99.7% |
| JUMP_BACKWARD | 4,780 | 0.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,988,700 | 77.3% |
| SET_FUNCTION_ATTRIBUTE | 1,171,540 | 22.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,712,980 | 33.2% |
| SET_FUNCTION_ATTRIBUTE | 1,171,540 | 22.7% |
| STORE_FAST | 1,022,300 | 19.8% |
| LOAD_FAST | 452,140 | 8.8% |
| STORE_DEREF | 424,960 | 8.2% |


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
| LOAD_FAST | 2,058,280 | 17.7% |
| SWAP | 118,440 | 1.0% |
| STORE_ATTR | 25,760 | 0.2% |
| LOAD_ATTR_SLOT | 9,060 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,386,860 | 46.4% |
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
| LOAD_FAST | 3,888,640 | 82.3% |
| SET_FUNCTION_ATTRIBUTE | 424,960 | 9.0% |
| RETURN_VALUE | 160,920 | 3.4% |
| LOAD_ATTR_SLOT | 103,000 | 2.2% |
| FOR_ITER_LIST | 37,580 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,929,040 | 62.0% |
| LOAD_FAST | 1,131,200 | 24.0% |
| LOAD_GLOBAL_BUILTIN | 258,860 | 5.5% |
| LOAD_CONST | 189,160 | 4.0% |
| LOAD_DEREF | 177,000 | 3.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 90,211,628 | 18.4% |
| FOR_ITER_LIST | 53,079,066 | 10.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 51,802,928 | 10.6% |
| LOAD_ATTR_SLOT | 44,469,340 | 9.1% |
| BUILD_LIST | 31,885,884 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,614,224 | 49.1% |
| LOAD_GLOBAL_BUILTIN | 72,231,744 | 14.7% |
| LOAD_GLOBAL_MODULE | 58,568,007 | 11.9% |
| LOAD_FAST_LOAD_FAST | 41,696,905 | 8.5% |
| BUILD_LIST | 18,511,800 | 3.8% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,300,503 | 70.0% |
| FOR_ITER_TUPLE | 1,755,560 | 23.2% |
| FOR_ITER_RANGE | 334,960 | 4.4% |
| FOR_ITER | 175,580 | 2.3% |
| CALL_LEN | 1,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,977,120 | 39.3% |
| LOAD_CONST | 1,720,723 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,246,160 | 16.5% |
| LOAD_ATTR_METHOD_NO_DICT | 525,300 | 6.9% |
| LOAD_FAST | 422,680 | 5.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_LIST | 14,530,540 | 58.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,749,008 | 31.0% |
| UNPACK_SEQUENCE_TUPLE | 1,771,720 | 7.1% |
| COPY | 608,560 | 2.4% |
| BINARY_SUBSCR_LIST_INT | 100,180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,557,328 | 74.3% |
| LOAD_FAST_LOAD_FAST | 2,258,800 | 9.0% |
| STORE_FAST | 1,918,200 | 7.7% |
| LOAD_GLOBAL_BUILTIN | 1,391,720 | 5.6% |
| LOAD_GLOBAL_MODULE | 350,380 | 1.4% |


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
| LOAD_FAST_AND_CLEAR | 26,552,620 | 30.3% |
| BUILD_LIST | 24,162,740 | 27.6% |
| FOR_ITER_LIST | 17,863,500 | 20.4% |
| LOAD_FAST | 4,831,800 | 5.5% |
| CALL_LEN | 3,580,440 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 24,162,740 | 27.6% |
| FOR_ITER_LIST | 22,398,180 | 25.6% |
| STORE_FAST | 21,419,080 | 24.5% |
| COPY | 3,583,640 | 4.1% |
| POP_TOP | 3,524,980 | 4.0% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 540 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 90,560 | 65.6% |
| COPY | 26,560 | 19.2% |
| FOR_ITER_LIST | 8,110 | 5.9% |
| FOR_ITER | 4,540 | 3.3% |
| RETURN_VALUE | 3,680 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 98,490 | 71.3% |
| STORE_FAST_STORE_FAST | 33,300 | 24.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,120 | 3.0% |
| UNPACK_SEQUENCE_TUPLE | 980 | 0.7% |
| UNPACK_SEQUENCE | 880 | 0.6% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,524,560 | 22.5% |
| LOAD_CONST | 1,885,440 | 16.8% |
| ENTER_EXECUTOR | 1,727,924 | 15.4% |
| LOAD_FAST | 1,142,140 | 10.2% |
| CALL_ISINSTANCE | 797,780 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,580,600 | 85.4% |
| STORE_FAST | 897,560 | 8.0% |
| UNPACK_SEQUENCE_TUPLE | 376,200 | 3.4% |
| YIELD_VALUE | 368,064 | 3.3% |
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
| LOAD_FAST | 236,960 | 82.5% |
| ENTER_EXECUTOR | 49,380 | 17.2% |
| BINARY_OP_ADD_INT | 740 | 0.3% |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 286,360 | 99.7% |
| BINARY_OP_ADD_INT | 720 | 0.3% |
| STORE_FAST | 140 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,260,275 | 56.3% |
| CALL_LEN | 1,511,400 | 20.0% |
| CALL_METHOD_DESCRIPTOR_O | 1,467,800 | 19.4% |
| LOAD_FAST_LOAD_FAST | 158,690 | 2.1% |
| LOAD_FAST | 152,800 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,159,380 | 41.8% |
| LOAD_FAST | 2,067,770 | 27.3% |
| SWAP | 955,760 | 12.6% |
| LOAD_FAST_LOAD_FAST | 688,900 | 9.1% |
| LOAD_CONST | 213,940 | 2.8% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,961,480 | 35.8% |
| LOAD_FAST | 1,017,240 | 18.5% |
| CALL_METHOD_DESCRIPTOR_O | 984,600 | 17.9% |
| LOAD_FAST_LOAD_FAST | 984,220 | 17.9% |
| LOAD_ATTR | 360,240 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,545,120 | 28.2% |
| RETURN_VALUE | 1,346,260 | 24.5% |
| SET_ADD | 1,280,880 | 23.3% |
| STORE_FAST | 691,440 | 12.6% |
| BINARY_OP_INPLACE_ADD_UNICODE | 329,000 | 6.0% |


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
| LOAD_CONST | 3,531,775 | 92.6% |
| LOAD_FAST | 124,360 | 3.3% |
| CALL_LEN | 99,780 | 2.6% |
| ENTER_EXECUTOR | 44,160 | 1.2% |
| LOAD_FAST_LOAD_FAST | 7,600 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,849,840 | 48.5% |
| BINARY_SLICE | 890,220 | 23.3% |
| STORE_FAST | 319,480 | 8.4% |
| SWAP | 290,120 | 7.6% |
| BINARY_SUBSCR_LIST_INT | 263,540 | 6.9% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 101,555,560 | 86.3% |
| LOAD_FAST | 8,825,516 | 7.5% |
| BINARY_SUBSCR_DICT | 3,034,827 | 2.6% |
| BINARY_SUBSCR_LIST_INT | 1,821,400 | 1.5% |
| LOAD_DEREF | 1,502,160 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,912,600 | 18.6% |
| STORE_FAST | 19,975,430 | 17.0% |
| LOAD_CONST | 19,885,940 | 16.9% |
| GET_ITER | 12,484,620 | 10.6% |
| CALL_PY_EXACT_ARGS | 9,517,360 | 8.1% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,533,080 | 54.9% |
| ENTER_EXECUTOR | 852,800 | 30.5% |
| LOAD_FAST_LOAD_FAST | 398,620 | 14.3% |
| LOAD_CONST | 7,200 | 0.3% |
| LOAD_FAST | 420 | 0.0% |

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
| LOAD_CONST | 8,398,020 | 45.3% |
| LOAD_FAST | 5,410,280 | 29.2% |
| LOAD_FAST_LOAD_FAST | 4,386,120 | 23.6% |
| BINARY_OP_SUBTRACT_INT | 263,540 | 1.4% |
| BINARY_OP_ADD_INT | 47,160 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,738,140 | 14.8% |
| STORE_FAST | 2,622,840 | 14.1% |
| LOAD_GLOBAL_MODULE | 2,255,320 | 12.2% |
| BINARY_SUBSCR_DICT | 1,821,400 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,472,600 | 7.9% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 746,000 | 79.0% |
| BINARY_OP_ADD_INT | 117,560 | 12.5% |
| LOAD_FAST_LOAD_FAST | 41,179 | 4.4% |
| BINARY_OP_SUBTRACT_INT | 36,960 | 3.9% |
| LOAD_FAST | 1,700 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 632,260 | 67.0% |
| LOAD_FAST | 159,699 | 16.9% |
| CALL_BUILTIN_O | 67,820 | 7.2% |
| LOAD_FAST_LOAD_FAST | 33,880 | 3.6% |
| COMPARE_OP_STR | 33,840 | 3.6% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,748,780 | 99.7% |
| LOAD_FAST_LOAD_FAST | 4,400 | 0.3% |
| BINARY_SUBSCR | 1,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 307,600 | 17.5% |
| FORMAT_SIMPLE | 281,600 | 16.0% |
| LOAD_FAST_LOAD_FAST | 252,840 | 14.4% |
| STORE_FAST | 202,000 | 11.5% |
| COMPARE_OP_STR | 172,140 | 9.8% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,126,180 | 46.9% |
| LOAD_FAST | 1,826,580 | 27.4% |
| LOAD_GLOBAL_MODULE | 655,580 | 9.8% |
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
| LOAD_FAST | 15,553,700 | 59.8% |
| BINARY_SUBSCR_DICT | 6,452,840 | 24.8% |
| LOAD_CONST | 2,692,860 | 10.4% |
| ENTER_EXECUTOR | 923,460 | 3.6% |
| CALL_PY_EXACT_ARGS | 101,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 23,223,080 | 89.3% |
| POP_TOP | 2,625,160 | 10.1% |
| CALL_PY_EXACT_ARGS | 101,180 | 0.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 49,760 | 0.2% |
| RESUME | 980 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,003,820 | 29.8% |
| LOAD_GLOBAL_BUILTIN | 7,125,680 | 17.7% |
| LOAD_ATTR_SLOT | 4,516,448 | 11.2% |
| LOAD_ATTR_CLASS | 3,789,040 | 9.4% |
| CALL_LEN | 3,073,740 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,031,320 | 47.3% |
| LOAD_FAST | 10,521,320 | 26.1% |
| STORE_FAST | 3,772,660 | 9.4% |
| RETURN_VALUE | 2,544,960 | 6.3% |
| MAP_ADD | 1,614,360 | 4.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,902,615 | 46.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,659,640 | 36.4% |
| LOAD_FAST_LOAD_FAST | 1,844,640 | 14.4% |
| LOAD_FAST | 199,280 | 1.6% |
| LOAD_GLOBAL_BUILTIN | 90,280 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,896,460 | 22.7% |
| RETURN_VALUE | 2,325,720 | 18.2% |
| PUSH_EXC_INFO | 2,282,200 | 17.9% |
| TO_BOOL_BOOL | 2,040,500 | 16.0% |
| POP_TOP | 1,638,600 | 12.8% |


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
| BUILD_TUPLE | 5,669,858 | 35.9% |
| RETURN_GENERATOR | 4,748,320 | 30.0% |
| LOAD_FAST | 2,120,540 | 13.4% |
| LOAD_GLOBAL_MODULE | 1,203,052 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 653,440 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,973,352 | 44.1% |
| LOAD_FAST | 4,956,426 | 31.3% |
| TO_BOOL_BOOL | 1,700,040 | 10.8% |
| CALL_PY_EXACT_ARGS | 904,580 | 5.7% |
| STORE_FAST | 459,400 | 2.9% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 232,120,226 | 84.5% |
| LOAD_GLOBAL_BUILTIN | 35,038,560 | 12.7% |
| BUILD_TUPLE | 4,526,280 | 1.6% |
| LOAD_ATTR | 1,896,180 | 0.7% |
| LOAD_ATTR_MODULE | 940,884 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 268,589,146 | 97.7% |
| COPY | 4,208,200 | 1.5% |
| YIELD_VALUE | 797,780 | 0.3% |
| RETURN_VALUE | 744,584 | 0.3% |
| STORE_FAST | 395,980 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,141,980 | 56.8% |
| LOAD_ATTR_SLOT | 11,046,160 | 31.1% |
| LOAD_DEREF | 1,900,680 | 5.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,895,800 | 5.3% |
| LOAD_ATTR | 217,120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,420,180 | 26.5% |
| COMPARE_OP_INT | 5,888,020 | 16.6% |
| LOAD_GLOBAL_BUILTIN | 4,564,260 | 12.9% |
| SWAP | 3,580,440 | 10.1% |
| CALL_BUILTIN_CLASS | 3,073,740 | 8.7% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,897,288 | 77.5% |
| RETURN_VALUE | 2,635,720 | 8.2% |
| ENTER_EXECUTOR | 1,552,860 | 4.8% |
| LOAD_CONST | 567,720 | 1.8% |
| BUILD_TUPLE | 548,212 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,527,100 | 54.5% |
| ENTER_EXECUTOR | 9,371,520 | 29.2% |
| NOP | 2,435,240 | 7.6% |
| EXTENDED_ARG | 683,180 | 2.1% |
| LOAD_CONST | 680,720 | 2.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,393,959 | 54.6% |
| LOAD_ATTR_METHOD_NO_DICT | 20,250,976 | 32.1% |
| LOAD_CONST | 2,720,280 | 4.3% |
| ENTER_EXECUTOR | 1,887,260 | 3.0% |
| LOAD_GLOBAL_MODULE | 1,306,809 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 51,802,928 | 82.2% |
| POP_TOP | 4,744,076 | 7.5% |
| LOAD_FAST | 2,740,029 | 4.3% |
| CALL_PY_EXACT_ARGS | 923,140 | 1.5% |
| LOAD_ATTR_METHOD_NO_DICT | 619,620 | 1.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,468,940 | 86.2% |
| LOAD_FAST | 187,400 | 6.5% |
| LOAD_ATTR_MODULE | 92,440 | 3.2% |
| ENTER_EXECUTOR | 88,640 | 3.1% |
| LOAD_ATTR_METHOD_NO_DICT | 25,800 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,107,260 | 73.6% |
| LOAD_CONST | 248,840 | 8.7% |
| GET_ITER | 188,420 | 6.6% |
| UNPACK_SEQUENCE_LIST | 104,160 | 3.6% |
| CONTAINS_OP | 92,460 | 3.2% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,975,420 | 98.2% |
| ENTER_EXECUTOR | 45,580 | 1.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,200 | 0.2% |
| CALL | 1,540 | 0.1% |
| LOAD_ATTR | 1,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,727,860 | 57.0% |
| LOAD_FAST | 574,900 | 19.0% |
| POP_TOP | 320,620 | 10.6% |
| CALL_BUILTIN_CLASS | 239,760 | 7.9% |
| LOAD_ATTR_METHOD_NO_DICT | 89,560 | 3.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,516,600 | 54.9% |
| LOAD_FAST | 3,723,574 | 31.4% |
| RETURN_VALUE | 631,520 | 5.3% |
| LOAD_ATTR_SLOT | 257,100 | 2.2% |
| BUILD_TUPLE | 243,160 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,077,660 | 42.8% |
| POP_TOP | 4,081,914 | 34.4% |
| BINARY_OP_ADD_INT | 1,467,800 | 12.4% |
| BINARY_OP_ADD_UNICODE | 984,600 | 8.3% |
| STORE_FAST | 171,460 | 1.4% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,096,682 | 37.4% |
| LOAD_FAST_LOAD_FAST | 102,307,746 | 23.6% |
| LOAD_ATTR_METHOD_NO_DICT | 74,527,972 | 17.2% |
| LOAD_ATTR_SLOT | 13,797,604 | 3.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,906,680 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 376,185,842 | 86.7% |
| COPY_FREE_VARS | 47,448,651 | 10.9% |
| MAKE_CELL | 4,877,300 | 1.1% |
| RETURN_GENERATOR | 4,222,960 | 1.0% |
| CALL_PY_EXACT_ARGS | 721,039 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 7,932,960 | 38.3% |
| LOAD_FAST | 6,740,229 | 32.5% |
| LOAD_FAST_LOAD_FAST | 1,837,940 | 8.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,165,460 | 5.6% |
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
| LOAD_FAST | 1,218,980 | 100.0% |
| UNARY_NOT | 280 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 983,660 | 80.7% |
| CALL_BUILTIN_O | 187,180 | 15.4% |
| STORE_FAST | 33,140 | 2.7% |
| CALL | 15,040 | 1.2% |
| BUILD_TUPLE | 300 | 0.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,818,540 | 92.5% |
| LOAD_ATTR_SLOT | 1,464,632 | 7.2% |
| RETURN_VALUE | 22,540 | 0.1% |
| LOAD_FAST_CHECK | 19,480 | 0.1% |
| RETURN_GENERATOR | 8,240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,960,180 | 93.2% |
| LOAD_GLOBAL_BUILTIN | 762,360 | 3.7% |
| BUILD_TUPLE | 531,032 | 2.6% |
| CALL_PY_EXACT_ARGS | 33,560 | 0.2% |
| RETURN_VALUE | 24,440 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,111,500 | 100.0% |
| LOAD_CONST | 300 | 0.0% |
| CALL | 200 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,950,040 | 62.5% |
| STORE_FAST | 1,538,460 | 13.8% |
| LOAD_ATTR | 1,443,800 | 13.0% |
| PUSH_NULL | 890,280 | 8.0% |
| LOAD_GLOBAL_MODULE | 120,000 | 1.1% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 600 | 88.2% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 8.8% |
| COMPARE_OP | 20 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 620 | 91.2% |
| POP_JUMP_IF_FALSE | 60 | 8.8% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,741,513 | 39.2% |
| CALL_LEN | 5,888,020 | 15.7% |
| LOAD_GLOBAL_MODULE | 3,585,280 | 9.5% |
| COPY | 3,580,400 | 9.5% |
| LOAD_ATTR_CLASS | 3,555,000 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 22,039,986 | 58.6% |
| POP_JUMP_IF_TRUE | 11,207,886 | 29.8% |
| COPY | 2,105,700 | 5.6% |
| RETURN_VALUE | 1,278,603 | 3.4% |
| EXTENDED_ARG | 626,880 | 1.7% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 30,940,896 | 71.3% |
| LOAD_FAST | 9,063,692 | 20.9% |
| RETURN_VALUE | 957,820 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 836,326 | 1.9% |
| LOAD_ATTR_MODULE | 633,760 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 26,905,472 | 62.0% |
| POP_JUMP_IF_FALSE | 11,288,620 | 26.0% |
| COPY | 3,095,604 | 7.1% |
| RETURN_VALUE | 1,230,714 | 2.8% |
| EXTENDED_ARG | 777,260 | 1.8% |


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
| ENTER_EXECUTOR | 47,857,451 | 38.9% |
| GET_ITER | 44,683,783 | 36.3% |
| SWAP | 22,398,180 | 18.2% |
| LOAD_FAST | 5,162,300 | 4.2% |
| EXTENDED_ARG | 2,643,740 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,079,066 | 43.2% |
| LOAD_FAST | 27,117,057 | 22.1% |
| SWAP | 17,863,500 | 14.5% |
| RETURN_CONST | 14,501,956 | 11.8% |
| STORE_FAST_LOAD_FAST | 5,300,503 | 4.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,973,100 | 63.3% |
| ENTER_EXECUTOR | 2,453,179 | 26.0% |
| SWAP | 790,400 | 8.4% |
| EXTENDED_ARG | 213,640 | 2.3% |
| JUMP_BACKWARD | 7,460 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,869,039 | 30.4% |
| RETURN_CONST | 2,799,000 | 29.7% |
| LOAD_FAST | 2,203,380 | 23.3% |
| LOAD_GLOBAL_MODULE | 825,720 | 8.7% |
| STORE_FAST_LOAD_FAST | 334,960 | 3.5% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 18,935,952 | 62.7% |
| ENTER_EXECUTOR | 8,469,572 | 28.0% |
| SWAP | 2,651,900 | 8.8% |
| EXTENDED_ARG | 69,080 | 0.2% |
| FOR_ITER_LIST | 34,794 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,501,182 | 58.0% |
| STORE_FAST | 6,363,389 | 21.1% |
| SWAP | 2,630,960 | 8.7% |
| STORE_FAST_LOAD_FAST | 1,755,560 | 5.8% |
| LOAD_FAST_LOAD_FAST | 1,077,760 | 3.6% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,174,400 | 88.4% |
| LOAD_FAST | 1,544,160 | 10.4% |
| COPY | 105,520 | 0.7% |
| ENTER_EXECUTOR | 62,540 | 0.4% |
| LOAD_ATTR_CLASS | 6,680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 3,789,040 | 25.4% |
| COMPARE_OP_INT | 3,555,000 | 23.9% |
| LOAD_ATTR_METHOD_NO_DICT | 2,703,560 | 18.1% |
| CALL | 2,566,780 | 17.2% |
| LOAD_ATTR_MODULE | 1,544,160 | 10.4% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 124,251,480 | 80.4% |
| LOAD_FAST_LOAD_FAST | 12,619,022 | 8.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,948,940 | 3.9% |
| LOAD_GLOBAL_MODULE | 4,175,120 | 2.7% |
| ENTER_EXECUTOR | 1,854,720 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,875,605 | 18.7% |
| LOAD_CONST | 27,754,420 | 18.0% |
| LOAD_ATTR_METHOD_NO_DICT | 14,282,831 | 9.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,938,060 | 8.4% |
| CONTAINS_OP | 7,875,400 | 5.1% |


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
| LOAD_FAST | 188,878,819 | 72.2% |
| LOAD_ATTR_SLOT | 26,312,156 | 10.1% |
| LOAD_ATTR_INSTANCE_VALUE | 14,282,831 | 5.5% |
| LOAD_GLOBAL_MODULE | 10,018,040 | 3.8% |
| ENTER_EXECUTOR | 8,176,127 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 116,509,350 | 44.5% |
| CALL_PY_EXACT_ARGS | 74,527,972 | 28.5% |
| LOAD_CONST | 24,528,256 | 9.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 20,250,976 | 7.7% |
| LOAD_GLOBAL_MODULE | 17,982,944 | 6.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,613,921 | 81.8% |
| LOAD_ATTR_INSTANCE_VALUE | 12,938,060 | 11.4% |
| LOAD_DEREF | 2,523,560 | 2.2% |
| LOAD_ATTR_WITH_HINT | 1,358,040 | 1.2% |
| LOAD_FAST_LOAD_FAST | 1,281,440 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,441,144 | 70.1% |
| LOAD_FAST_LOAD_FAST | 15,713,406 | 13.9% |
| CALL_PY_EXACT_ARGS | 10,906,680 | 9.6% |
| LOAD_CONST | 2,703,800 | 2.4% |
| LOAD_DEREF | 2,126,500 | 1.9% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 16,878,644 | 65.8% |
| LOAD_ATTR_MODULE | 5,797,300 | 22.6% |
| LOAD_ATTR_CLASS | 1,544,160 | 6.0% |
| LOAD_FAST_LOAD_FAST | 1,235,000 | 4.8% |
| LOAD_FAST | 202,480 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 5,797,300 | 22.6% |
| PUSH_NULL | 4,893,100 | 19.1% |
| LOAD_FAST | 4,100,760 | 16.0% |
| COMPARE_OP | 2,742,060 | 10.7% |
| LOAD_GLOBAL_MODULE | 1,606,640 | 6.3% |


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
| LOAD_ATTR_INSTANCE_VALUE | 689,200 | 64.6% |
| LOAD_FAST | 371,720 | 34.8% |
| LOAD_FAST_LOAD_FAST | 3,440 | 0.3% |
| BINARY_SUBSCR_DICT | 980 | 0.1% |
| ENTER_EXECUTOR | 900 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 690,720 | 64.7% |
| CALL_LEN | 137,880 | 12.9% |
| RETURN_VALUE | 100,480 | 9.4% |
| LOAD_FAST | 95,560 | 9.0% |
| POP_JUMP_IF_NONE | 35,960 | 3.4% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,895,607 | 54.5% |
| LOAD_ATTR_SLOT | 6,438,309 | 23.5% |
| ENTER_EXECUTOR | 5,179,456 | 18.9% |
| LOAD_ATTR_INSTANCE_VALUE | 482,920 | 1.8% |
| CALL | 93,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 25,542,379 | 93.4% |
| RETURN_VALUE | 1,066,087 | 3.9% |
| LOAD_FAST | 239,400 | 0.9% |
| STORE_FAST | 238,600 | 0.9% |
| LOAD_CONST | 105,300 | 0.4% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 435,327,809 | 88.2% |
| LOAD_ATTR_SLOT | 34,706,422 | 7.0% |
| LOAD_DEREF | 7,774,220 | 1.6% |
| LOAD_FAST_LOAD_FAST | 6,552,344 | 1.3% |
| STORE_FAST_LOAD_FAST | 2,977,120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,740,366 | 12.1% |
| GET_ITER | 47,884,756 | 9.7% |
| STORE_FAST | 44,469,340 | 9.0% |
| RETURN_VALUE | 36,495,326 | 7.4% |
| LOAD_ATTR_SLOT | 34,706,422 | 7.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,493,520 | 57.2% |
| LOAD_FAST_LOAD_FAST | 6,344,020 | 20.7% |
| LOAD_ATTR_INSTANCE_VALUE | 6,215,840 | 20.3% |
| LOAD_ATTR_WITH_HINT | 500,740 | 1.6% |
| LOAD_DEREF | 10,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,599,580 | 31.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,625,480 | 11.9% |
| TO_BOOL_BOOL | 3,533,960 | 11.6% |
| COPY | 2,789,480 | 9.1% |
| LOAD_FAST | 2,393,580 | 7.8% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 168,107,118 | 30.9% |
| POP_JUMP_IF_FALSE | 132,510,276 | 24.3% |
| STORE_FAST | 72,231,744 | 13.3% |
| LOAD_FAST | 39,480,360 | 7.2% |
| POP_JUMP_IF_NOT_NONE | 36,996,740 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 378,510,848 | 69.5% |
| LOAD_DEREF | 92,064,060 | 16.9% |
| CALL_ISINSTANCE | 35,038,560 | 6.4% |
| CALL_BUILTIN_CLASS | 7,125,680 | 1.3% |
| LOAD_CONST | 6,281,240 | 1.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 269,201,099 | 44.5% |
| STORE_FAST | 58,568,007 | 9.7% |
| RESUME_CHECK | 53,166,420 | 8.8% |
| POP_JUMP_IF_FALSE | 47,565,700 | 7.9% |
| LOAD_GLOBAL_MODULE | 32,734,280 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 232,120,226 | 38.3% |
| LOAD_FAST | 116,420,191 | 19.2% |
| LOAD_FAST_LOAD_FAST | 45,757,800 | 7.6% |
| IS_OP | 41,593,560 | 6.9% |
| LOAD_GLOBAL_MODULE | 32,734,280 | 5.4% |


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
| LOAD_FAST | 86,016,580 | 100.0% |
| LOAD_SUPER_ATTR | 2,400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,619,920 | 83.3% |
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
| CALL_PY_EXACT_ARGS | 376,185,842 | 54.5% |
| COPY_FREE_VARS | 93,013,820 | 13.5% |
| CACHE | 69,747,627 | 10.1% |
| CALL_KW | 43,426,700 | 6.3% |
| LOAD_ATTR_PROPERTY | 25,542,379 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 301,881,070 | 43.7% |
| LOAD_GLOBAL_BUILTIN | 168,107,118 | 24.4% |
| RETURN_CONST | 67,668,480 | 9.8% |
| LOAD_FAST_LOAD_FAST | 60,441,560 | 8.8% |
| LOAD_GLOBAL_MODULE | 53,166,420 | 7.7% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 368,024 | 79.3% |
| LOAD_CONST | 95,920 | 20.7% |
| SEND | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 368,024 | 79.3% |
| POP_TOP | 95,940 | 20.7% |
| RESUME | 40 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 44,208,940 | 56.7% |
| LOAD_FAST | 32,505,920 | 41.7% |
| SWAP | 794,320 | 1.0% |
| BINARY_SUBSCR | 449,520 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 32,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,619,080 | 46.9% |
| RETURN_CONST | 13,693,620 | 17.6% |
| LOAD_FAST | 13,002,020 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 5,133,860 | 6.6% |
| LOAD_GLOBAL_MODULE | 3,667,940 | 4.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 359,778,866 | 58.8% |
| LOAD_FAST_LOAD_FAST | 248,585,380 | 40.6% |
| STORE_ATTR_SLOT | 2,483,841 | 0.4% |
| LOAD_ATTR_SLOT | 847,800 | 0.1% |
| ENTER_EXECUTOR | 83,580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 170,370,120 | 27.8% |
| LOAD_FAST_LOAD_FAST | 141,091,380 | 23.1% |
| RETURN_CONST | 120,875,220 | 19.8% |
| LOAD_FAST | 112,443,606 | 18.4% |
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
| LOAD_FAST | 3,630,442 | 74.7% |
| LOAD_FAST_LOAD_FAST | 439,000 | 9.0% |
| LOAD_ATTR_SLOT | 359,260 | 7.4% |
| SWAP | 332,600 | 6.8% |
| LOAD_ATTR_INSTANCE_VALUE | 47,240 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,497,460 | 51.4% |
| ENTER_EXECUTOR | 1,227,240 | 25.3% |
| LOAD_FAST | 918,842 | 18.9% |
| LOAD_GLOBAL_BUILTIN | 86,560 | 1.8% |
| LOAD_DEREF | 63,340 | 1.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 431,960 | 99.8% |
| LOAD_FAST | 960 | 0.2% |
| STORE_SUBSCR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 430,140 | 99.3% |
| EXTENDED_ARG | 1,380 | 0.3% |
| LOAD_FAST | 840 | 0.2% |
| JUMP_BACKWARD | 320 | 0.1% |
| RETURN_CONST | 320 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,643,297 | 74.3% |
| LOAD_ATTR_SLOT | 5,611,640 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 553,760 | 1.9% |
| ENTER_EXECUTOR | 545,980 | 1.9% |
| COPY | 234,540 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 25,226,957 | 86.6% |
| POP_JUMP_IF_TRUE | 2,828,200 | 9.7% |
| EXTENDED_ARG | 992,840 | 3.4% |
| TO_BOOL_NONE | 36,529 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 32,719 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 268,589,146 | 65.3% |
| COPY | 38,447,030 | 9.3% |
| LOAD_FAST | 34,143,280 | 8.3% |
| RETURN_VALUE | 25,355,360 | 6.2% |
| LOAD_ATTR_SLOT | 11,603,840 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 277,350,368 | 67.4% |
| POP_JUMP_IF_TRUE | 100,866,548 | 24.5% |
| UNARY_NOT | 22,824,820 | 5.5% |
| EXTENDED_ARG | 10,432,860 | 2.5% |
| TO_BOOL_STR | 640 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,185,012 | 62.9% |
| LOAD_ATTR_INSTANCE_VALUE | 356,080 | 18.9% |
| RETURN_VALUE | 148,400 | 7.9% |
| LOAD_ATTR_SLOT | 138,880 | 7.4% |
| BINARY_OP | 51,840 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,350,912 | 71.7% |
| POP_JUMP_IF_TRUE | 391,380 | 20.8% |
| UNARY_NOT | 139,280 | 7.4% |
| TO_BOOL_STR | 1,280 | 0.1% |
| TO_BOOL_BOOL | 320 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,675,680 | 75.9% |
| LOAD_ATTR_SLOT | 6,506,760 | 14.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,594,720 | 5.7% |
| COPY | 888,220 | 1.9% |
| BINARY_SUBSCR_LIST_INT | 393,200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 34,742,340 | 76.0% |
| POP_JUMP_IF_FALSE | 7,628,820 | 16.7% |
| UNARY_NOT | 2,525,220 | 5.5% |
| EXTENDED_ARG | 790,880 | 1.7% |
| TO_BOOL | 4,300 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,342,503 | 63.4% |
| LOAD_ATTR_SLOT | 8,021,360 | 25.0% |
| COPY | 1,795,240 | 5.6% |
| LOAD_ATTR_INSTANCE_VALUE | 582,760 | 1.8% |
| LOAD_ATTR_MODULE | 518,960 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,004,103 | 71.7% |
| POP_JUMP_IF_TRUE | 8,234,180 | 25.7% |
| EXTENDED_ARG | 776,420 | 2.4% |
| TO_BOOL_ALWAYS_TRUE | 36,852 | 0.1% |
| UNARY_NOT | 7,920 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,661,300 | 71.9% |
| COPY | 1,506,780 | 16.3% |
| LOAD_ATTR_SLOT | 436,820 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 349,280 | 3.8% |
| STORE_FAST_LOAD_FAST | 187,940 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,434,060 | 58.7% |
| POP_JUMP_IF_TRUE | 3,454,200 | 37.3% |
| UNARY_NOT | 369,580 | 4.0% |
| TO_BOOL_NONE | 4,940 | 0.1% |
| TO_BOOL_INT | 1,580 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 14,181,920 | 97.6% |
| RETURN_VALUE | 232,840 | 1.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 104,160 | 0.7% |
| LOAD_FAST | 15,920 | 0.1% |
| BINARY_SLICE | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 14,530,540 | 100.0% |
| STORE_FAST | 5,740 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 777,560 | 40.7% |
| YIELD_VALUE | 376,200 | 19.7% |
| STORE_FAST | 292,840 | 15.3% |
| FOR_ITER | 230,660 | 12.1% |
| LOAD_ATTR_INSTANCE_VALUE | 93,080 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,771,720 | 92.6% |
| STORE_FAST | 141,020 | 7.4% |
| STORE_DEREF | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 5,766,928 | 66.8% |
| RETURN_VALUE | 1,471,900 | 17.1% |
| FOR_ITER_LIST | 503,360 | 5.8% |
| RETURN_CONST | 290,360 | 3.4% |
| STORE_FAST | 256,460 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 7,749,008 | 89.8% |
| STORE_FAST | 853,980 | 9.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 29,120 | 0.3% |
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
|     deferred | 4,638,440 | 20.4% |
|          hit | 17,945,280 | 79.1% |
|         miss | 78,140 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,560 | 31.7% |
| Failure | 14,120 | 68.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 6,440 | 45.6% |
| multiply different types | 3,520 | 24.9% |
| or | 1,280 | 9.1% |
| remainder | 1,100 | 7.8% |
| subtract other | 860 | 6.1% |
| and int | 400 | 2.8% |
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
|     deferred | 40,265,662 | 22.1% |
|          hit | 141,665,202 | 77.8% |
|         miss | 1,580 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,320 | 30.4% |
| Failure | 28,226 | 69.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 16,546 | 58.6% |
| other | 7,080 | 25.1% |
| code complex parameters | 4,280 | 15.2% |
| buffer int | 240 | 0.9% |
| tuple slice | 80 | 0.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 67,199,261 | 6.1% |
|          hit | 978,288,945 | 88.4% |
|         miss | 60,175,316 | 5.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,247,139 | 91.7% |
| Failure | 113,500 | 8.3% |

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
|     deferred | 42,212,095 | 34.2% |
|          hit | 80,055,197 | 64.9% |
|         miss | 911,379 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 30,171 | 26.4% |
| Failure | 84,118 | 73.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 49,535 | 58.9% |
| baseobject | 13,600 | 16.2% |
| other | 6,080 | 7.2% |
| different types | 5,720 | 6.8% |
| bool | 3,443 | 4.1% |
| tuple | 3,020 | 3.6% |
| list | 2,120 | 2.5% |
| set | 320 | 0.4% |
| string | 280 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 18,461,274 | 10.1% |
|          hit | 160,000,853 | 87.7% |
|         miss | 3,911,688 | 2.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 86,078 | 71.8% |
| Failure | 33,861 | 28.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 8,121 | 24.0% |
| enumerate | 7,820 | 23.1% |
| zip | 6,320 | 18.7% |
| reversed list | 3,960 | 11.7% |
| dict items | 3,900 | 11.5% |
| dict keys | 1,980 | 5.8% |
| dict values | 1,000 | 3.0% |
| itertools | 480 | 1.4% |
| map | 200 | 0.6% |
| other | 80 | 0.2% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 109,315,413 | 8.8% |
|        deopt | 1,580 | 0.0% |
|          hit | 1,035,517,438 | 83.8% |
|         miss | 88,477,205 | 7.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,823,006 | 89.9% |
| Failure | 205,800 | 10.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 102,740 | 49.9% |
| not managed dict | 37,220 | 18.1% |
| shadowed | 27,060 | 13.1% |
| metaclass attribute | 9,240 | 4.5% |
| class method obj | 8,120 | 3.9% |
| non overriding descriptor | 8,020 | 3.9% |
| method | 5,660 | 2.8% |
| class attr simple | 4,060 | 2.0% |
| module attr not found | 2,980 | 1.4% |
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
|          hit | 1,150,174,910 | 100.0% |
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
|          hit | 87,102,140 | 100.0% |

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
|          hit | 464,004 | 100.0% |

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
|     deferred | 9,055,499 | 1.3% |
|          hit | 558,011,518 | 79.4% |
|         miss | 133,442,169 | 19.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,539,981 | 99.0% |
| Failure | 25,920 | 1.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 17,200 | 66.4% |
| not in dict | 7,200 | 27.8% |
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
|     deferred | 3,766,900 | 41.6% |
|          hit | 5,291,802 | 58.4% |

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
|     deferred | 20,083,360 | 3.7% |
|          hit | 522,214,868 | 95.0% |
|         miss | 7,293,200 | 1.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 196,740 | 77.7% |
| Failure | 56,540 | 22.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 26,500 | 46.9% |
| tuple | 17,760 | 31.4% |
| dict | 5,820 | 10.3% |
| other | 2,420 | 4.3% |
| set | 2,080 | 3.7% |
| mapping | 1,960 | 3.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 131,810 | 0.5% |
|          hit | 25,081,188 | 99.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,380 | 86.2% |
| Failure | 860 | 13.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 620 | 72.1% |
| iterator | 240 | 27.9% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 7,083,533,422 | 50.3% |
| Not specialized | 1,265,686,809 | 9.0% |
| Specialized hits | 5,428,949,397 | 38.6% |
| Specialized misses | 294,297,257 | 2.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 109,315,413 | 34.7% |
| CALL | 67,199,261 | 21.3% |
| COMPARE_OP | 42,212,095 | 13.4% |
| BINARY_SUBSCR | 40,265,662 | 12.8% |
| TO_BOOL | 20,083,360 | 6.4% |
| FOR_ITER | 18,461,274 | 5.9% |
| STORE_ATTR | 9,055,499 | 2.9% |
| BINARY_OP | 4,638,440 | 1.5% |
| STORE_SUBSCR | 3,766,900 | 1.2% |
| UNPACK_SEQUENCE | 131,810 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 131,662,489 | 44.7% |
| LOAD_ATTR_METHOD_NO_DICT | 57,131,652 | 19.4% |
| CALL_PY_EXACT_ARGS | 44,511,416 | 15.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 14,589,172 | 5.0% |
| LOAD_ATTR_SLOT | 8,298,248 | 2.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 8,038,180 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 5,638,060 | 1.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,525,760 | 1.9% |
| TO_BOOL_ALWAYS_TRUE | 3,841,025 | 1.3% |
| TO_BOOL_NONE | 2,650,755 | 0.9% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 120,974,487 | 17.5% |
| Calls to Python functions inlined | 571,445,436 | 82.5% |
| Calls via PyEval_EvalFrame (total) | 120,974,487 | 17.5% |
| Calls via PyEval_EvalFrame (vector) | 106,566,487 | 15.4% |
| Calls via PyEval_EvalFrame (generator) | 14,408,000 | 2.1% |
| Calls via PyEval_EvalFrame (legacy) | 100 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 106,566,347 | 15.4% |
| Calls via PyEval_EvalFrame (build class) | 40 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 13,896,626 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 2,475,100 | 0.4% |
| Calls via PyEval_EvalFrame (api) | 23,662,081 | 3.4% |
| Calls via PyEval_EvalFrame (method) | 100 | 0.0% |
| Frame objects created | 4,745,560 | 0.7% |
| Frames pushed | 487,194,770 | 70.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 307,147,706 | 28.5% |
| Frees to freelist | 307,217,718 |  |
| Allocations | 769,290,685 | 71.5% |
| Allocations to 512 bytes | 768,241,548 | 71.4% |
| Allocations to 4 kbytes | 731,037 | 0.1% |
| Allocations over 4 kbytes | 318,100 | 0.0% |
| Frees | 794,822,454 |  |
| New values | 8,867,540 |  |
| Interpreter increfs | 7,314,440,667 | 74.1% |
| Interpreter decrefs | 8,054,634,520 | 74.7% |
| Increfs | 2,559,496,099 | 25.9% |
| Decrefs | 2,723,249,274 | 25.3% |
| Materialize dict (on request) | 660 | 0.0% |
| Materialize dict (new key) | 2,300 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 400 | 0.0% |
| Method cache hits | 418,754,179 |  |
| Method cache misses | 10,778,255 |  |
| Method cache collisions | 13,809,785 |  |
| Method cache dunder hits | 354,740,232 |  |
| Method cache dunder misses | 3,282,346 |  |


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
| Optimization attempts | 17,280 |  |
| Traces created | 15,780 | 91.3% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 60 | 0.3% |
| Trace too long | 2,639 | 15.3% |
| Trace too short | 1,500 | 8.7% |
| Inner loop found | 321 | 1.9% |
| Recursive call | 360 | 2.1% |
| Traces executed | 117,019,311 |  |
| Uops executed | 1,687,401,534 | 14.42 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 0.1% |
| <= 16 | 360 | 2.3% |
| <= 32 | 5,471 | 34.7% |
| <= 64 | 4,454 | 28.2% |
| <= 128 | 5,475 | 34.7% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 20 | 0.1% |
| <= 8 | 540 | 3.4% |
| <= 16 | 3,991 | 25.3% |
| <= 32 | 5,178 | 32.8% |
| <= 64 | 3,281 | 20.8% |
| <= 128 | 2,770 | 17.6% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 2,262,574 | 1.9% |
| <= 2 | 56,310,660 | 48.1% |
| <= 4 | 1,913,079 | 1.6% |
| <= 8 | 15,092,456 | 12.9% |
| <= 16 | 12,501,161 | 10.7% |
| <= 32 | 14,735,788 | 12.6% |
| <= 64 | 11,164,356 | 9.5% |
| <= 128 | 2,609,718 | 2.2% |
| <= 256 | 163,729 | 0.1% |
| <= 512 | 193,364 | 0.2% |
| <= 1,024 | 33,986 | 0.0% |
| <= 2,048 | 8,060 | 0.0% |
| <= 4,096 | 15,340 | 0.0% |
| <= 8,192 | 14,420 | 0.0% |
| <= 16,384 | 620 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 200,076,113 | 11.9% | 11.9% |  |
| _SET_IP | 172,257,180 | 10.2% | 22.1% |  |
| _CHECK_VALIDITY | 135,100,238 | 8.0% | 30.1% |  |
| STORE_FAST | 97,532,669 | 5.8% | 35.9% |  |
| _ITER_CHECK_LIST | 97,012,269 | 5.7% | 41.6% | 0.6% |
| _GUARD_NOT_EXHAUSTED_LIST | 96,408,297 | 5.7% | 47.3% | 49.8% |
| _GUARD_GLOBALS_VERSION | 67,582,352 | 4.0% | 51.3% | 0.9% |
| _GUARD_TYPE_VERSION | 64,016,255 | 3.8% | 55.1% | 18.3% |
| _ITER_NEXT_LIST | 48,427,520 | 2.9% | 58.0% |  |
| LOAD_CONST | 42,579,417 | 2.5% | 60.5% |  |
| _LOAD_GLOBAL_MODULE | 36,667,336 | 2.2% | 62.7% |  |
| _GUARD_BUILTINS_VERSION | 30,313,016 | 1.8% | 64.5% |  |
| _LOAD_GLOBAL_BUILTINS | 30,313,016 | 1.8% | 66.3% |  |
| _GUARD_IS_FALSE_POP | 26,626,570 | 1.6% | 67.9% | 10.3% |
| _EXIT_TRACE | 25,550,553 | 1.5% | 69.4% |  |
| _GUARD_IS_TRUE_POP | 24,790,192 | 1.5% | 70.8% | 11.0% |
| _JUMP_TO_TOP | 22,244,297 | 1.3% | 72.2% |  |
| _LOAD_ATTR_SLOT | 21,187,218 | 1.3% | 73.4% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 19,717,715 | 1.2% | 74.6% | 9.2% |
| _CHECK_PEP_523 | 19,717,715 | 1.2% | 75.7% |  |
| _FOR_ITER_TIER_TWO | 19,335,160 | 1.1% | 76.9% |  |
| TO_BOOL_BOOL | 18,336,616 | 1.1% | 78.0% |  |
| _CHECK_STACK_SPACE | 17,897,455 | 1.1% | 79.0% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 17,895,855 | 1.1% | 80.1% |  |
| _PUSH_FRAME | 17,895,855 | 1.1% | 81.2% |  |
| _SAVE_RETURN_OFFSET | 17,895,855 | 1.1% | 82.2% |  |
| CALL_ISINSTANCE | 17,273,136 | 1.0% | 83.2% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 15,029,819 | 0.9% | 84.1% |  |
| _ITER_CHECK_TUPLE | 14,170,404 | 0.8% | 85.0% | 11.8% |
| BINARY_SUBSCR_LIST_INT | 13,686,220 | 0.8% | 85.8% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 12,502,382 | 0.7% | 86.5% | 59.3% |
| RESUME_CHECK | 12,190,446 | 0.7% | 87.2% |  |
| COMPARE_OP_STR | 12,151,200 | 0.7% | 88.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 11,832,810 | 0.7% | 88.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 11,832,810 | 0.7% | 89.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,125,752 | 0.7% | 90.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 9,535,840 | 0.6% | 90.6% |  |
| _GUARD_IS_NOT_NONE_POP | 8,824,540 | 0.5% | 91.1% | 1.7% |
| CONTAINS_OP | 8,581,297 | 0.5% | 91.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 7,841,348 | 0.5% | 92.1% | 24.1% |
| _GUARD_NOT_EXHAUSTED_RANGE | 6,039,560 | 0.4% | 92.4% | 42.2% |
| _ITER_CHECK_RANGE | 6,039,560 | 0.4% | 92.8% |  |
| _LOAD_ATTR | 5,786,521 | 0.3% | 93.2% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 5,714,060 | 0.3% | 93.5% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 5,714,060 | 0.3% | 93.8% |  |
| COMPARE_OP_INT | 5,270,921 | 0.3% | 94.1% |  |
| _ITER_NEXT_TUPLE | 5,089,112 | 0.3% | 94.4% |  |
| _GUARD_IS_NONE_POP | 5,051,380 | 0.3% | 94.7% | 5.7% |
| PUSH_NULL | 4,378,894 | 0.3% | 95.0% |  |
| LIST_APPEND | 3,912,166 | 0.2% | 95.2% |  |
| _GUARD_BOTH_UNICODE | 3,900,180 | 0.2% | 95.5% |  |
| _BINARY_OP_ADD_UNICODE | 3,900,180 | 0.2% | 95.7% |  |
| _GUARD_BOTH_INT | 3,787,000 | 0.2% | 95.9% | 1.5% |
| TO_BOOL_NONE | 3,551,080 | 0.2% | 96.1% | 4.8% |
| _ITER_NEXT_RANGE | 3,490,101 | 0.2% | 96.3% |  |
| _CHECK_ATTR_MODULE | 3,473,516 | 0.2% | 96.5% |  |
| _LOAD_ATTR_MODULE | 3,473,516 | 0.2% | 96.7% |  |
| _GUARD_KEYS_VERSION | 3,296,195 | 0.2% | 96.9% | 8.5% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 3,296,195 | 0.2% | 97.1% |  |
| _BINARY_OP_SUBTRACT_INT | 3,201,605 | 0.2% | 97.3% |  |
| BINARY_SUBSCR_DICT | 3,147,157 | 0.2% | 97.5% |  |
| LOAD_DEREF | 3,024,075 | 0.2% | 97.7% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 2,935,690 | 0.2% | 97.9% |  |
| SET_ADD | 2,718,422 | 0.2% | 98.0% |  |
| CALL_BUILTIN_FAST | 2,681,125 | 0.2% | 98.2% |  |
| BUILD_LIST | 2,343,268 | 0.1% | 98.3% |  |
| TO_BOOL_STR | 2,277,740 | 0.1% | 98.5% |  |
| CALL_STR_1 | 2,266,480 | 0.1% | 98.6% |  |
| CALL_BUILTIN_O | 2,262,320 | 0.1% | 98.7% |  |
| POP_TOP | 2,244,637 | 0.1% | 98.9% |  |
| GET_ITER | 1,882,701 | 0.1% | 99.0% |  |
| _POP_FRAME | 1,419,500 | 0.1% | 99.1% |  |
| MAP_ADD | 1,283,500 | 0.1% | 99.1% |  |
| FORMAT_SIMPLE | 1,079,260 | 0.1% | 99.2% |  |
| BUILD_STRING | 956,180 | 0.1% | 99.3% |  |
| BUILD_TUPLE | 793,208 | 0.0% | 99.3% |  |
| TO_BOOL_LIST | 742,980 | 0.0% | 99.3% |  |
| _COMPARE_OP | 723,760 | 0.0% | 99.4% |  |
| CALL_LEN | 702,020 | 0.0% | 99.4% |  |
| TO_BOOL_ALWAYS_TRUE | 607,760 | 0.0% | 99.5% | 82.6% |
| _BINARY_SUBSCR | 550,878 | 0.0% | 99.5% |  |
| _BINARY_OP_ADD_INT | 529,715 | 0.0% | 99.5% |  |
| SWAP | 515,640 | 0.0% | 99.6% |  |
| _STORE_ATTR_SLOT | 499,180 | 0.0% | 99.6% |  |
| BINARY_SLICE | 483,600 | 0.0% | 99.6% |  |
| CALL_TYPE_1 | 481,280 | 0.0% | 99.6% |  |
| IS_OP | 456,700 | 0.0% | 99.7% |  |
| _LOAD_ATTR_WITH_HINT | 420,220 | 0.0% | 99.7% | 0.1% |
| _CHECK_ATTR_WITH_HINT | 420,220 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 408,060 | 0.0% | 99.7% |  |
| COPY | 405,505 | 0.0% | 99.8% |  |
| STORE_SUBSCR_DICT | 399,658 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 336,960 | 0.0% | 99.8% |  |
| UNARY_NOT | 332,840 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_STR_INT | 330,661 | 0.0% | 99.9% | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 290,840 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 290,806 | 0.0% | 99.9% |  |
| BUILD_MAP | 244,561 | 0.0% | 99.9% |  |
| _BINARY_OP | 231,100 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 225,900 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 152,648 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 133,940 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 121,680 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 94,229 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 90,640 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 83,040 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 80,740 | 0.0% | 100.0% |  |
| MAKE_CELL | 68,960 | 0.0% | 100.0% |  |
| _TO_BOOL | 68,000 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 66,960 | 0.0% | 100.0% | 93.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 62,600 | 0.0% | 100.0% | 72.8% |
| STORE_DEREF | 38,720 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 17,600 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 10,680 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 10,680 | 0.0% | 100.0% |  |
| BUILD_SET | 7,040 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 6,710 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 5,440 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 4,960 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 4,420 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 1,640 | 0.0% | 100.0% |  |
| _STORE_SUBSCR | 1,180 | 0.0% | 100.0% |  |
| _STORE_ATTR | 840 | 0.0% | 100.0% |  |
| UNARY_INVERT | 580 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 540 | 0.0% | 100.0% |  |
| UNPACK_EX | 420 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 1,555 |
| FOR_ITER_GEN | 1,500 |
| LOAD_ATTR_PROPERTY | 800 |
| YIELD_VALUE | 760 |
| CALL_LIST_APPEND | 760 |
| CALL_PY_WITH_DEFAULTS | 760 |
| CALL_KW | 740 |
| CALL_ALLOC_AND_ENTER_INIT | 240 |
| BINARY_SUBSCR_GETITEM | 20 |
| RETURN_GENERATOR | 17 |


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
