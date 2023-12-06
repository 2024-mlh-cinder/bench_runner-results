
# Pystats results

- benchmark: mypy2
- fork: gvanrossum
- ref: faster-uops
- commit hash: a2c4f00
- commit date: 2023-11-19T11:22:02-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 2,900,559,008 | 20.7% | 20.7% |  |
| LOAD_CONST | 690,851,699 | 4.9% | 25.6% |  |
| RESUME_CHECK | 689,419,723 | 4.9% | 30.5% | 0.0% |
| STORE_ATTR_SLOT | 611,790,647 | 4.4% | 34.8% | 21.5% |
| LOAD_GLOBAL_MODULE | 602,353,050 | 4.3% | 39.1% | 0.0% |
| LOAD_FAST_LOAD_FAST | 561,588,671 | 4.0% | 43.1% |  |
| LOAD_GLOBAL_BUILTIN | 542,510,579 | 3.9% | 47.0% | 0.0% |
| POP_JUMP_IF_FALSE | 541,473,781 | 3.9% | 50.9% |  |
| LOAD_ATTR_SLOT | 493,573,186 | 3.5% | 54.4% | 1.7% |
| STORE_FAST | 488,869,185 | 3.5% | 57.9% |  |
| CALL_PY_EXACT_ARGS | 433,199,482 | 3.1% | 60.9% | 10.3% |
| TO_BOOL_BOOL | 409,513,053 | 2.9% | 63.9% | 0.0% |
| RETURN_VALUE | 395,442,157 | 2.8% | 66.7% |  |
| RETURN_CONST | 299,922,096 | 2.1% | 68.8% |  |
| CALL_ISINSTANCE | 272,851,327 | 1.9% | 70.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 261,184,154 | 1.9% | 72.6% | 21.9% |
| POP_TOP | 219,933,089 | 1.6% | 74.2% |  |
| POP_JUMP_IF_TRUE | 218,178,868 | 1.6% | 75.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 154,378,989 | 1.1% | 76.8% | 3.7% |
| LOAD_DEREF | 129,291,789 | 0.9% | 77.7% |  |
| FOR_ITER_LIST | 122,952,614 | 0.9% | 78.6% | 1.6% |
| INTERPRETER_EXIT | 120,922,906 | 0.9% | 79.5% |  |
| GET_ITER | 120,359,615 | 0.9% | 80.3% |  |
| BINARY_SUBSCR_DICT | 117,175,085 | 0.8% | 81.2% |  |
| ENTER_EXECUTOR | 116,862,219 | 0.8% | 82.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 113,205,748 | 0.8% | 82.8% | 12.9% |
| LOAD_ATTR | 111,261,647 | 0.8% | 83.6% |  |
| POP_JUMP_IF_NOT_NONE | 94,736,900 | 0.7% | 84.3% |  |
| COPY_FREE_VARS | 93,983,064 | 0.7% | 85.0% |  |
| CONTAINS_OP | 92,886,815 | 0.7% | 85.6% |  |
| SWAP | 87,491,180 | 0.6% | 86.2% |  |
| LOAD_SUPER_ATTR_METHOD | 86,018,980 | 0.6% | 86.9% |  |
| BUILD_LIST | 82,570,844 | 0.6% | 87.4% |  |
| POP_JUMP_IF_NONE | 79,804,440 | 0.6% | 88.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 77,997,980 | 0.6% | 88.6% | 2.2% |
| CALL_KW | 76,507,100 | 0.5% | 89.1% |  |
| CALL | 68,559,900 | 0.5% | 89.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 62,880,181 | 0.4% | 90.0% | 8.8% |
| IS_OP | 56,759,400 | 0.4% | 90.4% |  |
| NOP | 53,251,480 | 0.4% | 90.8% |  |
| COPY | 50,506,555 | 0.4% | 91.2% |  |
| JUMP_FORWARD | 47,247,726 | 0.3% | 91.5% |  |
| TO_BOOL_LIST | 45,693,020 | 0.3% | 91.8% | 0.7% |
| COMPARE_OP_STR | 43,341,504 | 0.3% | 92.2% | 0.3% |
| COMPARE_OP | 42,049,579 | 0.3% | 92.5% |  |
| BINARY_SUBSCR | 40,299,647 | 0.3% | 92.7% |  |
| CALL_BUILTIN_CLASS | 40,061,330 | 0.3% | 93.0% |  |
| COMPARE_OP_INT | 37,424,805 | 0.3% | 93.3% | 2.1% |
| CALL_LEN | 35,394,840 | 0.3% | 93.5% |  |
| PUSH_NULL | 34,620,415 | 0.2% | 93.8% |  |
| MAKE_CELL | 33,195,320 | 0.2% | 94.0% |  |
| CALL_LIST_APPEND | 32,144,400 | 0.2% | 94.3% |  |
| TO_BOOL_NONE | 32,072,052 | 0.2% | 94.5% | 8.3% |
| BUILD_TUPLE | 31,307,928 | 0.2% | 94.7% |  |
| EXTENDED_ARG | 31,039,460 | 0.2% | 94.9% |  |
| LOAD_ATTR_WITH_HINT | 30,574,820 | 0.2% | 95.1% | 2.1% |
| FOR_ITER_TUPLE | 30,195,129 | 0.2% | 95.4% | 6.4% |
| MAP_ADD | 29,553,700 | 0.2% | 95.6% |  |
| TO_BOOL_ALWAYS_TRUE | 29,119,728 | 0.2% | 95.8% | 13.2% |
| LOAD_FAST_AND_CLEAR | 27,791,860 | 0.2% | 96.0% |  |
| LOAD_ATTR_PROPERTY | 27,343,794 | 0.2% | 96.2% | 6.6% |
| UNARY_NOT | 26,161,520 | 0.2% | 96.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 25,862,740 | 0.2% | 96.5% | 31.1% |
| LOAD_ATTR_MODULE | 25,439,605 | 0.2% | 96.7% | 0.0% |
| LIST_APPEND | 25,392,511 | 0.2% | 96.9% |  |
| STORE_FAST_STORE_FAST | 24,877,048 | 0.2% | 97.1% |  |
| CALL_PY_WITH_DEFAULTS | 20,721,240 | 0.1% | 97.2% | 2.1% |
| TO_BOOL | 20,336,640 | 0.1% | 97.4% |  |
| CALL_TUPLE_1 | 20,335,324 | 0.1% | 97.5% |  |
| FOR_ITER | 18,577,324 | 0.1% | 97.7% |  |
| BINARY_SUBSCR_LIST_INT | 18,035,780 | 0.1% | 97.8% | 0.0% |
| CALL_BUILTIN_O | 15,813,496 | 0.1% | 97.9% | 8.4% |
| LOAD_ATTR_CLASS | 14,896,340 | 0.1% | 98.0% | 2.4% |
| UNPACK_SEQUENCE_LIST | 14,447,640 | 0.1% | 98.1% |  |
| CALL_BUILTIN_FAST | 12,791,151 | 0.1% | 98.2% | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 11,852,290 | 0.1% | 98.3% | 0.0% |
| STORE_ATTR | 11,621,400 | 0.1% | 98.4% |  |
| DELETE_ATTR | 11,254,400 | 0.1% | 98.4% |  |
| YIELD_VALUE | 11,221,428 | 0.1% | 98.5% |  |
| CALL_TYPE_1 | 11,112,060 | 0.1% | 98.6% |  |
| BUILD_MAP | 10,997,919 | 0.1% | 98.7% |  |
| FOR_ITER_RANGE | 9,418,279 | 0.1% | 98.7% |  |
| TO_BOOL_STR | 9,176,040 | 0.1% | 98.8% | 4.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 8,631,773 | 0.1% | 98.9% |  |
| MAKE_FUNCTION | 8,202,540 | 0.1% | 98.9% |  |
| CALL_FUNCTION_EX | 7,966,320 | 0.1% | 99.0% |  |
| RETURN_GENERATOR | 7,785,480 | 0.1% | 99.0% |  |
| STORE_FAST_LOAD_FAST | 7,567,146 | 0.1% | 99.1% |  |
| BINARY_OP_ADD_INT | 7,354,155 | 0.1% | 99.2% | 0.5% |
| CALL_ALLOC_AND_ENTER_INIT | 6,667,940 | 0.0% | 99.2% | 0.1% |
| EXIT_INIT_CHECK | 6,658,880 | 0.0% | 99.2% |  |
| BINARY_SLICE | 5,855,740 | 0.0% | 99.3% |  |
| BINARY_OP_ADD_UNICODE | 5,486,260 | 0.0% | 99.3% |  |
| SET_FUNCTION_ATTRIBUTE | 5,140,540 | 0.0% | 99.4% |  |
| STORE_SUBSCR_DICT | 4,763,991 | 0.0% | 99.4% |  |
| STORE_DEREF | 4,722,300 | 0.0% | 99.4% |  |
| BINARY_OP | 4,659,120 | 0.0% | 99.5% |  |
| CHECK_EXC_MATCH | 4,152,160 | 0.0% | 99.5% |  |
| POP_EXCEPT | 4,152,160 | 0.0% | 99.5% |  |
| PUSH_EXC_INFO | 4,152,160 | 0.0% | 99.6% |  |
| DICT_MERGE | 3,864,720 | 0.0% | 99.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,801,520 | 0.0% | 99.6% | 0.0% |
| STORE_SUBSCR | 3,770,760 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_INT | 3,761,461 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,030,100 | 0.0% | 99.7% | 11.0% |
| LOAD_FAST_CHECK | 2,822,800 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_GETITEM | 2,792,220 | 0.0% | 99.7% | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,775,280 | 0.0% | 99.7% |  |
| BEFORE_WITH | 2,676,160 | 0.0% | 99.8% |  |
| IMPORT_FROM | 2,427,840 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 2,366,180 | 0.0% | 99.8% |  |
| IMPORT_NAME | 1,983,200 | 0.0% | 99.8% |  |
| UNARY_NEGATIVE | 1,949,620 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TUPLE | 1,912,780 | 0.0% | 99.8% |  |
| TO_BOOL_INT | 1,881,758 | 0.0% | 99.9% | 4.5% |
| BUILD_SET | 1,879,120 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,666,900 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 1,643,940 | 0.0% | 99.9% | 3.1% |
| JUMP_BACKWARD | 1,522,060 | 0.0% | 99.9% |  |
| BUILD_STRING | 1,456,140 | 0.0% | 99.9% |  |
| SET_ADD | 1,398,550 | 0.0% | 99.9% |  |
| FOR_ITER_GEN | 1,327,900 | 0.0% | 99.9% |  |
| CALL_STR_1 | 1,219,380 | 0.0% | 99.9% |  |
| LOAD_SUPER_ATTR_ATTR | 1,083,160 | 0.0% | 99.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,069,720 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,067,560 | 0.0% | 100.0% | 1.9% |
| BINARY_SUBSCR_STR_INT | 923,479 | 0.0% | 100.0% | 0.0% |
| BINARY_OP_INPLACE_ADD_UNICODE | 573,120 | 0.0% | 100.0% |  |
| RERAISE | 543,680 | 0.0% | 100.0% |  |
| SEND_GEN | 462,948 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 433,000 | 0.0% | 100.0% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 367,008 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 339,600 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 293,220 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 287,220 | 0.0% | 100.0% | 13.6% |
| LOAD_GLOBAL | 242,840 | 0.0% | 100.0% |  |
| DELETE_FAST | 201,920 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 193,100 | 0.0% | 100.0% |  |
| LIST_EXTEND | 150,540 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 138,054 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_SLOT | 435,067,122 | 3.1% | 3.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 376,245,483 | 2.7% | 5.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 375,496,241 | 2.7% | 8.5% |
| LOAD_FAST STORE_ATTR_SLOT | 359,760,466 | 2.6% | 11.0% |
| RESUME_CHECK LOAD_FAST | 301,413,663 | 2.1% | 13.2% |
| LOAD_CONST LOAD_FAST | 280,643,691 | 2.0% | 15.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 275,814,515 | 2.0% | 17.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 266,976,120 | 1.9% | 19.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 266,633,869 | 1.9% | 20.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 252,745,715 | 1.8% | 22.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 248,585,380 | 1.8% | 24.5% |
| STORE_FAST LOAD_FAST | 240,069,562 | 1.7% | 26.2% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 230,170,622 | 1.6% | 27.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 188,428,720 | 1.3% | 29.2% |
| STORE_ATTR_SLOT LOAD_CONST | 170,370,120 | 1.2% | 30.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 168,020,032 | 1.2% | 31.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 161,636,760 | 1.2% | 32.7% |
| LOAD_FAST LOAD_CONST | 152,885,877 | 1.1% | 33.8% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 141,091,380 | 1.0% | 34.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 131,381,445 | 0.9% | 35.8% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 124,139,752 | 0.9% | 36.7% |
| STORE_ATTR_SLOT RETURN_CONST | 120,875,220 | 0.9% | 37.5% |
| LOAD_FAST RETURN_VALUE | 117,845,751 | 0.8% | 38.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 116,073,201 | 0.8% | 39.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 115,788,138 | 0.8% | 40.0% |
| STORE_ATTR_SLOT LOAD_FAST | 112,443,606 | 0.8% | 40.8% |
| RETURN_CONST POP_TOP | 105,682,460 | 0.8% | 41.6% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 102,307,286 | 0.7% | 42.3% |
| LOAD_CONST BINARY_SUBSCR_DICT | 101,117,980 | 0.7% | 43.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 100,440,258 | 0.7% | 43.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 97,151,256 | 0.7% | 44.4% |
| POP_TOP LOAD_FAST | 93,746,488 | 0.7% | 45.1% |
| COPY_FREE_VARS RESUME_CHECK | 93,013,820 | 0.7% | 45.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 92,553,343 | 0.7% | 46.4% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 92,064,060 | 0.7% | 47.1% |
| RETURN_VALUE STORE_FAST | 89,559,900 | 0.6% | 47.7% |
| LOAD_DEREF LOAD_FAST | 88,094,862 | 0.6% | 48.3% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 86,016,580 | 0.6% | 48.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 82,791,560 | 0.6% | 49.5% |
| RETURN_VALUE RETURN_VALUE | 80,639,216 | 0.6% | 50.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 79,391,581 | 0.6% | 50.7% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 78,384,407 | 0.6% | 51.2% |
| LOAD_FAST LOAD_FAST | 77,048,268 | 0.5% | 51.8% |
| LOAD_CONST CALL_KW | 74,925,440 | 0.5% | 52.3% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 74,528,132 | 0.5% | 52.8% |
| LOAD_FAST LOAD_ATTR | 74,468,367 | 0.5% | 53.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 71,756,825 | 0.5% | 53.9% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 71,619,920 | 0.5% | 54.4% |
| CACHE RESUME_CHECK | 69,748,066 | 0.5% | 54.9% |
| RESUME_CHECK RETURN_CONST | 67,668,480 | 0.5% | 55.4% |
| RETURN_CONST INTERPRETER_EXIT | 61,992,140 | 0.4% | 55.8% |
| RETURN_CONST LOAD_FAST | 61,621,760 | 0.4% | 56.3% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 60,441,380 | 0.4% | 56.7% |
| LOAD_ATTR_SLOT LOAD_FAST | 59,553,620 | 0.4% | 57.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 58,269,684 | 0.4% | 57.5% |
| LOAD_CONST LOAD_CONST | 53,485,200 | 0.4% | 57.9% |
| FOR_ITER_LIST STORE_FAST | 53,080,289 | 0.4% | 58.3% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 52,899,400 | 0.4% | 58.7% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 51,799,403 | 0.4% | 59.0% |
| RETURN_VALUE LOAD_FAST | 50,111,100 | 0.4% | 59.4% |
| LOAD_ATTR LOAD_FAST | 49,707,164 | 0.4% | 59.7% |
| RETURN_VALUE INTERPRETER_EXIT | 49,256,726 | 0.4% | 60.1% |
| ENTER_EXECUTOR FOR_ITER_LIST | 47,901,473 | 0.3% | 60.4% |
| LOAD_ATTR_SLOT GET_ITER | 47,884,836 | 0.3% | 60.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 47,519,740 | 0.3% | 61.1% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 47,447,544 | 0.3% | 61.5% |
| LOAD_FAST CONTAINS_OP | 46,586,531 | 0.3% | 61.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 45,757,780 | 0.3% | 62.1% |
| GET_ITER FOR_ITER_LIST | 44,659,744 | 0.3% | 62.4% |
| LOAD_ATTR_SLOT STORE_FAST | 44,457,220 | 0.3% | 62.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 44,207,480 | 0.3% | 63.1% |
| CACHE COPY_FREE_VARS | 43,492,280 | 0.3% | 63.4% |
| CALL_KW RESUME_CHECK | 43,426,700 | 0.3% | 63.7% |
| RETURN_CONST RETURN_VALUE | 42,797,460 | 0.3% | 64.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 41,615,377 | 0.3% | 64.3% |
| LOAD_GLOBAL_MODULE IS_OP | 41,593,560 | 0.3% | 64.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 39,441,320 | 0.3% | 64.9% |
| LOAD_FAST POP_JUMP_IF_NONE | 38,718,980 | 0.3% | 65.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 38,476,058 | 0.3% | 65.4% |
| COPY TO_BOOL_BOOL | 38,416,604 | 0.3% | 65.7% |
| IS_OP POP_JUMP_IF_FALSE | 38,094,420 | 0.3% | 65.9% |
| POP_JUMP_IF_NONE LOAD_FAST | 38,032,540 | 0.3% | 66.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 36,617,620 | 0.3% | 66.5% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 36,588,400 | 0.3% | 66.7% |
| LOAD_ATTR_SLOT RETURN_VALUE | 36,491,790 | 0.3% | 67.0% |
| POP_TOP LOAD_FAST_LOAD_FAST | 35,282,040 | 0.3% | 67.3% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 34,999,520 | 0.2% | 67.5% |
| TO_BOOL_LIST POP_JUMP_IF_TRUE | 34,742,340 | 0.2% | 67.7% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 34,705,924 | 0.2% | 68.0% |
| LOAD_FAST TO_BOOL_LIST | 34,675,500 | 0.2% | 68.2% |
| RETURN_VALUE POP_TOP | 34,488,960 | 0.2% | 68.5% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 34,311,819 | 0.2% | 68.7% |
| LOAD_FAST TO_BOOL_BOOL | 34,142,960 | 0.2% | 69.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 32,687,520 | 0.2% | 69.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 32,504,460 | 0.2% | 69.4% |
| STORE_ATTR_SLOT LOAD_GLOBAL_BUILTIN | 31,685,060 | 0.2% | 69.7% |
| BUILD_LIST STORE_FAST | 31,672,171 | 0.2% | 69.9% |
| LOAD_CONST COMPARE_OP_STR | 30,940,436 | 0.2% | 70.1% |
| LOAD_ATTR_SLOT POP_JUMP_IF_NONE | 30,484,000 | 0.2% | 70.3% |
| NOP LOAD_FAST | 29,997,800 | 0.2% | 70.5% |


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
| RESUME_CHECK | 69,748,066 | 57.7% |
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
| LOAD_CONST | 19,881,473 | 49.3% |
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
| LOAD_ATTR_SLOT | 47,884,836 | 39.8% |
| LOAD_FAST | 28,593,540 | 23.8% |
| CALL_BUILTIN_CLASS | 19,010,140 | 15.8% |
| BINARY_SUBSCR_DICT | 12,484,620 | 10.4% |
| CALL | 2,651,080 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 44,659,744 | 37.1% |
| LOAD_FAST_AND_CLEAR | 26,544,400 | 22.1% |
| FOR_ITER_TUPLE | 18,926,277 | 15.7% |
| FOR_ITER | 14,521,894 | 12.1% |
| FOR_ITER_RANGE | 5,952,940 | 4.9% |


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
| RETURN_VALUE | 49,256,726 | 40.7% |
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
| LOAD_CONST | 8,202,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,158,500 | 50.7% |
| SET_FUNCTION_ATTRIBUTE | 3,969,000 | 48.4% |
| LOAD_CONST | 48,060 | 0.6% |
| LOAD_GLOBAL_MODULE | 14,280 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 7,240 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,134,200 | 28.4% |
| POP_JUMP_IF_TRUE | 14,082,560 | 26.4% |
| POP_JUMP_IF_FALSE | 9,175,960 | 17.2% |
| RESUME_CHECK | 6,477,180 | 12.2% |
| CALL_LIST_APPEND | 2,435,240 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,997,800 | 56.3% |
| LOAD_CONST | 14,777,960 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 4,744,820 | 8.9% |
| LOAD_GLOBAL_MODULE | 3,054,140 | 5.7% |
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
| RETURN_CONST | 105,682,460 | 48.1% |
| RETURN_VALUE | 34,488,960 | 15.7% |
| POP_JUMP_IF_FALSE | 20,650,631 | 9.4% |
| POP_JUMP_IF_TRUE | 17,344,512 | 7.9% |
| RESUME_CHECK | 8,001,720 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,746,488 | 42.6% |
| LOAD_FAST_LOAD_FAST | 35,282,040 | 16.0% |
| ENTER_EXECUTOR | 26,743,218 | 12.2% |
| RETURN_CONST | 22,997,880 | 10.5% |
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
| LOAD_FAST | 17,528,671 | 50.6% |
| LOAD_ATTR | 8,407,160 | 24.3% |
| LOAD_ATTR_MODULE | 4,892,500 | 14.1% |
| BINARY_SUBSCR_DICT | 1,481,440 | 4.3% |
| LOAD_SUPER_ATTR_ATTR | 1,077,400 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,829,515 | 80.4% |
| LOAD_FAST_LOAD_FAST | 5,611,280 | 16.2% |
| CALL | 569,700 | 1.6% |
| LOAD_CONST | 282,920 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 187,560 | 0.5% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,222,960 | 54.2% |
| CALL_FUNCTION_EX | 2,281,920 | 29.3% |
| COPY_FREE_VARS | 966,164 | 12.4% |
| ENTER_EXECUTOR | 216,256 | 2.8% |
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
| LOAD_FAST | 117,845,751 | 29.8% |
| RETURN_VALUE | 80,639,216 | 20.4% |
| RETURN_CONST | 42,797,460 | 10.8% |
| LOAD_ATTR_SLOT | 36,491,790 | 9.2% |
| CALL | 12,594,440 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 89,559,900 | 22.6% |
| RETURN_VALUE | 80,639,216 | 20.4% |
| LOAD_FAST | 50,111,100 | 12.7% |
| INTERPRETER_EXIT | 49,256,726 | 12.5% |
| POP_TOP | 34,488,960 | 8.7% |


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
| SWAP | 24,142,900 | 29.2% |
| STORE_FAST | 18,491,640 | 22.4% |
| LOAD_GLOBAL_MODULE | 11,076,560 | 13.4% |
| RESUME_CHECK | 8,677,460 | 10.5% |
| STORE_ATTR_SLOT | 4,211,900 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,672,171 | 38.4% |
| SWAP | 24,142,900 | 29.2% |
| CALL | 11,446,480 | 13.9% |
| LOAD_FAST | 8,091,560 | 9.8% |
| LOAD_GLOBAL_BUILTIN | 2,538,120 | 3.1% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,105,940 | 37.3% |
| LOAD_CONST | 1,666,280 | 15.2% |
| STORE_ATTR_INSTANCE_VALUE | 960,220 | 8.7% |
| RESUME_CHECK | 883,400 | 8.0% |
| POP_JUMP_IF_FALSE | 796,480 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,354,680 | 57.8% |
| LOAD_CONST | 1,611,560 | 14.7% |
| STORE_FAST | 1,441,779 | 13.1% |
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
| LOAD_FAST | 11,016,058 | 35.2% |
| LOAD_GLOBAL_MODULE | 5,209,080 | 16.6% |
| LOAD_ATTR_SLOT | 5,109,446 | 16.3% |
| LOAD_FAST_LOAD_FAST | 4,263,260 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,366,980 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,223,940 | 26.3% |
| CALL_BUILTIN_O | 5,669,850 | 18.1% |
| CALL_ISINSTANCE | 4,522,440 | 14.4% |
| LOAD_CONST | 3,970,600 | 12.7% |
| LOAD_FAST | 3,557,320 | 11.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,571,051 | 18.3% |
| BUILD_LIST | 11,446,480 | 16.7% |
| ENTER_EXECUTOR | 7,172,438 | 10.5% |
| LOAD_FAST_LOAD_FAST | 6,948,100 | 10.1% |
| RETURN_VALUE | 5,677,266 | 8.3% |

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
| LOAD_CONST | 74,925,440 | 97.9% |
| ENTER_EXECUTOR | 1,581,660 | 2.1% |

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
| LOAD_ATTR_SLOT | 18,253,586 | 43.4% |
| LOAD_GLOBAL_MODULE | 8,564,900 | 20.4% |
| LOAD_CONST | 7,730,890 | 18.4% |
| LOAD_ATTR_MODULE | 2,505,620 | 6.0% |
| LOAD_FAST | 2,161,120 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 16,886,500 | 40.2% |
| POP_JUMP_IF_FALSE | 13,091,210 | 31.1% |
| RETURN_VALUE | 8,405,878 | 20.0% |
| POP_JUMP_IF_TRUE | 2,606,120 | 6.2% |
| EXTENDED_ARG | 793,160 | 1.9% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,586,531 | 50.2% |
| LOAD_FAST_LOAD_FAST | 17,316,211 | 18.6% |
| LOAD_ATTR_INSTANCE_VALUE | 7,881,625 | 8.5% |
| LOAD_ATTR_SLOT | 4,854,682 | 5.2% |
| BINARY_SUBSCR | 4,464,740 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 78,384,407 | 84.4% |
| POP_JUMP_IF_TRUE | 10,805,908 | 11.6% |
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
| COMPARE_OP | 16,886,500 | 33.4% |
| LOAD_FAST | 6,124,360 | 12.1% |
| CALL_ISINSTANCE | 4,178,540 | 8.3% |
| SWAP | 3,583,640 | 7.1% |
| COMPARE_OP_STR | 3,095,724 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 38,416,604 | 76.1% |
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
| CALL_PY_EXACT_ARGS | 47,447,544 | 50.5% |
| CACHE | 43,492,280 | 46.3% |
| CALL | 1,923,440 | 2.0% |
| CALL_ALLOC_AND_ENTER_INIT | 450,680 | 0.5% |
| CALL_KW | 424,320 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 93,013,820 | 99.0% |
| RETURN_GENERATOR | 966,164 | 1.0% |
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
| POP_JUMP_IF_TRUE | 29,835,624 | 25.5% |
| POP_TOP | 26,743,218 | 22.9% |
| LIST_APPEND | 25,349,311 | 21.7% |
| CALL_LIST_APPEND | 9,371,520 | 8.0% |
| EXTENDED_ARG | 6,459,920 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 47,901,473 | 41.0% |
| FOR_ITER_TUPLE | 8,480,626 | 7.3% |
| LOAD_ATTR_METHOD_NO_DICT | 8,194,868 | 7.0% |
| CALL | 7,172,438 | 6.1% |
| RESUME_CHECK | 5,451,000 | 4.7% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,432,820 | 33.6% |
| GET_ITER | 4,616,320 | 14.9% |
| POP_TOP | 3,421,980 | 11.0% |
| ENTER_EXECUTOR | 1,477,860 | 4.8% |
| LOAD_ATTR_SLOT | 1,255,320 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,713,660 | 47.4% |
| ENTER_EXECUTOR | 6,459,920 | 20.8% |
| FOR_ITER | 3,156,660 | 10.2% |
| FOR_ITER_LIST | 2,643,740 | 8.5% |
| POP_JUMP_IF_NONE | 2,423,400 | 7.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,521,894 | 78.2% |
| EXTENDED_ARG | 3,156,660 | 17.0% |
| SWAP | 723,760 | 3.9% |
| LOAD_FAST | 82,460 | 0.4% |
| JUMP_BACKWARD | 55,604 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 5,766,573 | 31.0% |
| RETURN_CONST | 4,383,365 | 23.6% |
| STORE_FAST | 3,858,368 | 20.8% |
| LOAD_FAST | 2,252,420 | 12.1% |
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
| POP_JUMP_IF_TRUE | 1,172,623 | 77.0% |
| CALL_LIST_APPEND | 106,340 | 7.0% |
| POP_TOP | 93,412 | 6.1% |
| LIST_APPEND | 43,200 | 2.8% |
| POP_JUMP_IF_FALSE | 29,679 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 1,230,940 | 80.9% |
| FOR_ITER_LIST | 157,002 | 10.3% |
| FOR_ITER | 55,604 | 3.7% |
| EXTENDED_ARG | 33,920 | 2.2% |
| ENTER_EXECUTOR | 15,780 | 1.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 366,948 | 100.0% |
| RESUME | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 366,968 | 100.0% |
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
| STORE_FAST | 3,796,131 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,510,626 | 49.8% |
| STORE_FAST | 14,581,440 | 30.9% |
| MAP_ADD | 6,275,520 | 13.3% |
| LOAD_CONST | 1,026,560 | 2.2% |
| LOAD_GLOBAL_MODULE | 958,515 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 15,131,180 | 59.6% |
| CALL | 7,028,600 | 27.7% |
| LOAD_FAST | 1,580,071 | 6.2% |
| BINARY_SUBSCR_LIST_INT | 336,300 | 1.3% |
| LOAD_ATTR_SLOT | 308,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 25,349,311 | 99.8% |
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
| LOAD_FAST | 74,468,367 | 66.9% |
| LOAD_GLOBAL_MODULE | 27,754,740 | 24.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,611,180 | 2.3% |
| LOAD_FAST_LOAD_FAST | 1,952,900 | 1.8% |
| CALL_TYPE_1 | 1,443,800 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,707,164 | 44.7% |
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
| STORE_ATTR_SLOT | 170,370,120 | 24.7% |
| LOAD_FAST | 152,885,877 | 22.1% |
| LOAD_CONST | 53,485,200 | 7.7% |
| LOAD_ATTR_INSTANCE_VALUE | 27,730,240 | 4.0% |
| MAP_ADD | 27,390,400 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,643,691 | 40.6% |
| BINARY_SUBSCR_DICT | 101,117,980 | 14.6% |
| CALL_KW | 74,925,440 | 10.8% |
| LOAD_CONST | 53,485,200 | 7.7% |
| COMPARE_OP_STR | 30,940,436 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 92,064,060 | 71.2% |
| LOAD_DEREF | 12,941,260 | 10.0% |
| LOAD_FAST | 5,427,940 | 4.2% |
| LOAD_GLOBAL_MODULE | 4,891,240 | 3.8% |
| POP_JUMP_IF_FALSE | 2,647,756 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,094,862 | 68.1% |
| LOAD_DEREF | 12,941,260 | 10.0% |
| LOAD_ATTR_SLOT | 7,774,220 | 6.0% |
| LOAD_CONST | 4,304,887 | 3.3% |
| LOAD_FAST_LOAD_FAST | 3,517,680 | 2.7% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 376,245,483 | 13.0% |
| RESUME_CHECK | 301,413,663 | 10.4% |
| LOAD_CONST | 280,643,691 | 9.7% |
| POP_JUMP_IF_FALSE | 252,745,715 | 8.7% |
| STORE_FAST | 240,069,562 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 435,067,122 | 15.0% |
| STORE_ATTR_SLOT | 359,760,466 | 12.4% |
| LOAD_GLOBAL_MODULE | 266,976,120 | 9.2% |
| LOAD_ATTR_METHOD_NO_DICT | 188,428,720 | 6.5% |
| CALL_PY_EXACT_ARGS | 161,636,760 | 5.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 26,544,400 | 95.5% |
| LOAD_FAST_AND_CLEAR | 1,247,460 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 26,533,520 | 95.5% |
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
| LOAD_SUPER_ATTR_METHOD | 71,619,920 | 12.8% |
| RESUME_CHECK | 60,441,380 | 10.8% |
| LOAD_GLOBAL_MODULE | 45,757,780 | 8.1% |
| STORE_FAST | 41,615,377 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 248,585,380 | 44.3% |
| CALL_PY_EXACT_ARGS | 102,307,286 | 18.2% |
| STORE_ATTR_INSTANCE_VALUE | 44,207,480 | 7.9% |
| LOAD_FAST | 38,476,058 | 6.9% |
| CONTAINS_OP | 17,316,211 | 3.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,600 | 18.8% |
| POP_JUMP_IF_FALSE | 44,629 | 18.4% |
| STORE_FAST | 38,323 | 15.8% |
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
| MAKE_CELL | 21,837,960 | 65.8% |
| CALL_KW | 4,870,760 | 14.7% |
| CALL_PY_EXACT_ARGS | 4,857,600 | 14.6% |
| BINARY_SUBSCR_GETITEM | 940,780 | 2.8% |
| CALL_PY_WITH_DEFAULTS | 585,560 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 21,837,960 | 65.8% |
| RESUME_CHECK | 11,342,280 | 34.2% |
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
| TO_BOOL_BOOL | 275,814,515 | 50.9% |
| CONTAINS_OP | 78,384,407 | 14.5% |
| IS_OP | 38,094,420 | 7.0% |
| TO_BOOL_ALWAYS_TRUE | 25,226,842 | 4.7% |
| TO_BOOL_NONE | 23,004,218 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,745,715 | 46.7% |
| LOAD_GLOBAL_BUILTIN | 131,381,445 | 24.3% |
| LOAD_GLOBAL_MODULE | 47,519,740 | 8.8% |
| LOAD_FAST_LOAD_FAST | 27,433,017 | 5.1% |
| POP_TOP | 20,650,631 | 3.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,718,980 | 48.5% |
| LOAD_ATTR_SLOT | 30,484,000 | 38.2% |
| LOAD_ATTR | 4,233,300 | 5.3% |
| EXTENDED_ARG | 2,423,400 | 3.0% |
| BINARY_SUBSCR_DICT | 2,092,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,032,540 | 47.7% |
| RETURN_CONST | 15,863,000 | 19.9% |
| JUMP_FORWARD | 14,018,240 | 17.6% |
| LOAD_CONST | 4,668,360 | 5.8% |
| LOAD_GLOBAL_BUILTIN | 3,115,509 | 3.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 82,791,560 | 87.4% |
| LOAD_ATTR_SLOT | 4,804,680 | 5.1% |
| BINARY_SUBSCR_DICT | 3,950,580 | 4.2% |
| LOAD_FAST_CHECK | 2,008,560 | 2.1% |
| BINARY_SUBSCR | 298,060 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 36,588,400 | 38.6% |
| LOAD_FAST | 19,783,960 | 20.9% |
| LOAD_CONST | 13,986,360 | 14.8% |
| LOAD_FAST_LOAD_FAST | 10,608,520 | 11.2% |
| RETURN_CONST | 4,656,000 | 4.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 100,440,258 | 46.0% |
| TO_BOOL_LIST | 34,742,340 | 15.9% |
| COMPARE_OP_STR | 26,905,632 | 12.3% |
| IS_OP | 11,627,840 | 5.3% |
| COMPARE_OP_INT | 11,154,992 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,151,256 | 44.5% |
| ENTER_EXECUTOR | 29,835,624 | 13.7% |
| LOAD_GLOBAL_MODULE | 22,131,108 | 10.1% |
| POP_TOP | 17,344,512 | 7.9% |
| NOP | 14,082,560 | 6.5% |


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
| POP_TOP | 22,997,880 | 7.7% |
| POP_JUMP_IF_FALSE | 17,973,720 | 6.0% |
| POP_JUMP_IF_NONE | 15,863,000 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 105,682,460 | 35.2% |
| INTERPRETER_EXIT | 61,992,140 | 20.7% |
| LOAD_FAST | 61,621,760 | 20.5% |
| RETURN_VALUE | 42,797,460 | 14.3% |
| TO_BOOL_BOOL | 11,429,080 | 3.8% |


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
| LOAD_FAST | 6,890 | 0.5% |
| RETURN_VALUE | 6,400 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,393,770 | 99.7% |
| JUMP_BACKWARD | 4,780 | 0.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,969,000 | 77.2% |
| SET_FUNCTION_ATTRIBUTE | 1,171,540 | 22.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,712,980 | 33.3% |
| SET_FUNCTION_ATTRIBUTE | 1,171,540 | 22.8% |
| STORE_FAST | 1,022,300 | 19.9% |
| LOAD_FAST | 452,140 | 8.8% |
| STORE_DEREF | 424,960 | 8.3% |


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
| RETURN_VALUE | 89,559,900 | 18.3% |
| FOR_ITER_LIST | 53,080,289 | 10.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 51,799,403 | 10.6% |
| LOAD_ATTR_SLOT | 44,457,220 | 9.1% |
| BUILD_LIST | 31,672,171 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,069,562 | 49.1% |
| LOAD_GLOBAL_BUILTIN | 71,756,825 | 14.7% |
| LOAD_GLOBAL_MODULE | 58,269,684 | 11.9% |
| LOAD_FAST_LOAD_FAST | 41,615,377 | 8.5% |
| BUILD_LIST | 18,491,640 | 3.8% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,300,046 | 70.0% |
| FOR_ITER_TUPLE | 1,755,560 | 23.2% |
| FOR_ITER_RANGE | 334,960 | 4.4% |
| FOR_ITER | 175,580 | 2.3% |
| CALL_LEN | 1,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,977,120 | 39.3% |
| LOAD_CONST | 1,720,726 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,246,160 | 16.5% |
| LOAD_ATTR_METHOD_NO_DICT | 525,300 | 6.9% |
| LOAD_FAST | 422,680 | 5.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_LIST | 14,441,900 | 58.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,748,653 | 31.1% |
| UNPACK_SEQUENCE_TUPLE | 1,771,720 | 7.1% |
| COPY | 608,560 | 2.4% |
| BINARY_SUBSCR_LIST_INT | 94,780 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,557,333 | 74.6% |
| LOAD_FAST_LOAD_FAST | 2,255,560 | 9.1% |
| STORE_FAST | 1,903,475 | 7.7% |
| LOAD_GLOBAL_BUILTIN | 1,303,080 | 5.2% |
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
| LOAD_FAST_AND_CLEAR | 26,533,520 | 30.3% |
| BUILD_LIST | 24,142,900 | 27.6% |
| FOR_ITER_LIST | 17,863,460 | 20.4% |
| LOAD_FAST | 4,828,280 | 5.5% |
| CALL_LEN | 3,580,440 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 24,142,900 | 27.6% |
| FOR_ITER_LIST | 22,380,080 | 25.6% |
| STORE_FAST | 21,419,080 | 24.5% |
| COPY | 3,583,640 | 4.1% |
| POP_TOP | 3,521,460 | 4.0% |


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
| FOR_ITER_LIST | 8,114 | 5.9% |
| FOR_ITER | 4,540 | 3.3% |
| RETURN_VALUE | 3,680 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 98,494 | 71.3% |
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
| ENTER_EXECUTOR | 1,731,999 | 15.4% |
| LOAD_FAST | 1,142,140 | 10.2% |
| CALL_ISINSTANCE | 797,780 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,580,600 | 85.4% |
| STORE_FAST | 897,560 | 8.0% |
| UNPACK_SEQUENCE_TUPLE | 376,200 | 3.4% |
| YIELD_VALUE | 367,008 | 3.3% |
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
| LOAD_CONST | 4,052,481 | 55.1% |
| CALL_LEN | 1,511,400 | 20.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,467,800 | 20.0% |
| LOAD_FAST_LOAD_FAST | 158,694 | 2.2% |
| LOAD_FAST | 152,800 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,159,380 | 43.0% |
| LOAD_FAST | 1,959,944 | 26.7% |
| SWAP | 955,760 | 13.0% |
| LOAD_FAST_LOAD_FAST | 590,380 | 8.0% |
| LOAD_CONST | 213,940 | 2.9% |


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
| LOAD_CONST | 3,530,331 | 93.9% |
| LOAD_FAST | 116,510 | 3.1% |
| CALL_LEN | 99,780 | 2.7% |
| LOAD_FAST_LOAD_FAST | 7,600 | 0.2% |
| LOAD_ATTR_SLOT | 3,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,849,840 | 49.2% |
| BINARY_SLICE | 890,220 | 23.7% |
| SWAP | 290,120 | 7.7% |
| STORE_FAST | 275,320 | 7.3% |
| BINARY_SUBSCR_LIST_INT | 263,540 | 7.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 101,117,980 | 86.3% |
| LOAD_FAST | 8,826,393 | 7.5% |
| BINARY_SUBSCR_DICT | 3,037,032 | 2.6% |
| BINARY_SUBSCR_LIST_INT | 1,821,400 | 1.6% |
| LOAD_DEREF | 1,502,160 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,766,740 | 18.6% |
| LOAD_CONST | 19,885,940 | 17.0% |
| STORE_FAST | 19,833,251 | 16.9% |
| GET_ITER | 12,484,620 | 10.7% |
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
| LOAD_CONST | 8,309,380 | 46.1% |
| LOAD_FAST | 5,177,340 | 28.7% |
| LOAD_FAST_LOAD_FAST | 4,191,240 | 23.2% |
| BINARY_OP_SUBTRACT_INT | 263,540 | 1.5% |
| BINARY_OP_ADD_INT | 47,160 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,622,840 | 14.5% |
| LOAD_FAST | 2,412,080 | 13.4% |
| LOAD_GLOBAL_MODULE | 2,255,320 | 12.5% |
| BINARY_SUBSCR_DICT | 1,821,400 | 10.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,472,600 | 8.2% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 745,820 | 80.8% |
| BINARY_OP_ADD_INT | 117,560 | 12.7% |
| BINARY_OP_SUBTRACT_INT | 36,960 | 4.0% |
| LOAD_FAST_LOAD_FAST | 21,019 | 2.3% |
| LOAD_FAST | 1,660 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 632,080 | 68.4% |
| LOAD_FAST | 139,539 | 15.1% |
| CALL_BUILTIN_O | 67,820 | 7.3% |
| LOAD_FAST_LOAD_FAST | 33,880 | 3.7% |
| COMPARE_OP_STR | 33,840 | 3.7% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,661,060 | 99.6% |
| LOAD_FAST_LOAD_FAST | 4,400 | 0.3% |
| BINARY_SUBSCR | 1,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 307,600 | 18.5% |
| FORMAT_SIMPLE | 281,600 | 16.9% |
| LOAD_FAST_LOAD_FAST | 208,980 | 12.5% |
| STORE_FAST | 202,000 | 12.1% |
| CALL | 155,500 | 9.3% |


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
| LOAD_FAST | 15,416,140 | 59.6% |
| BINARY_SUBSCR_DICT | 6,452,840 | 25.0% |
| LOAD_CONST | 2,692,680 | 10.4% |
| ENTER_EXECUTOR | 923,460 | 3.6% |
| CALL_PY_EXACT_ARGS | 101,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 23,085,340 | 89.3% |
| POP_TOP | 2,625,160 | 10.2% |
| CALL_PY_EXACT_ARGS | 101,180 | 0.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 49,760 | 0.2% |
| RESUME | 980 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,826,540 | 29.5% |
| LOAD_GLOBAL_BUILTIN | 7,114,948 | 17.8% |
| LOAD_ATTR_SLOT | 4,516,522 | 11.3% |
| LOAD_ATTR_CLASS | 3,789,040 | 9.5% |
| CALL_LEN | 3,073,740 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,010,140 | 47.5% |
| LOAD_FAST | 10,521,320 | 26.3% |
| STORE_FAST | 3,772,660 | 9.4% |
| RETURN_VALUE | 2,544,960 | 6.4% |
| MAP_ADD | 1,614,360 | 4.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,901,171 | 46.1% |
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
| LOAD_FAST | 3,223,540 | 84.8% |
| RETURN_GENERATOR | 385,440 | 10.1% |
| CALL_BUILTIN_CLASS | 141,720 | 3.7% |
| RETURN_VALUE | 47,920 | 1.3% |
| LOAD_CONST | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,624,700 | 69.0% |
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
| BUILD_TUPLE | 5,669,850 | 35.9% |
| RETURN_GENERATOR | 4,748,320 | 30.0% |
| LOAD_FAST | 2,120,360 | 13.4% |
| LOAD_GLOBAL_MODULE | 1,203,132 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 653,440 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,973,130 | 44.1% |
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
| LOAD_GLOBAL_MODULE | 230,170,622 | 84.4% |
| LOAD_GLOBAL_BUILTIN | 34,999,520 | 12.8% |
| BUILD_TUPLE | 4,522,440 | 1.7% |
| LOAD_ATTR | 1,895,860 | 0.7% |
| LOAD_ATTR_MODULE | 947,425 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 266,633,869 | 97.7% |
| COPY | 4,178,540 | 1.5% |
| YIELD_VALUE | 797,780 | 0.3% |
| RETURN_VALUE | 744,358 | 0.3% |
| STORE_FAST | 395,180 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,053,340 | 56.7% |
| LOAD_ATTR_SLOT | 11,046,160 | 31.2% |
| LOAD_DEREF | 1,900,680 | 5.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,895,800 | 5.4% |
| LOAD_ATTR | 217,120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,331,540 | 26.4% |
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
| LOAD_FAST | 24,645,493 | 76.7% |
| RETURN_VALUE | 2,589,340 | 8.1% |
| ENTER_EXECUTOR | 1,892,029 | 5.9% |
| LOAD_CONST | 567,720 | 1.8% |
| BUILD_TUPLE | 548,218 | 1.7% |

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
| LOAD_FAST | 34,311,819 | 54.6% |
| LOAD_ATTR_METHOD_NO_DICT | 20,162,016 | 32.1% |
| LOAD_CONST | 2,720,280 | 4.3% |
| ENTER_EXECUTOR | 1,894,660 | 3.0% |
| LOAD_GLOBAL_MODULE | 1,303,873 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 51,799,403 | 82.4% |
| POP_TOP | 4,743,756 | 7.5% |
| LOAD_FAST | 2,737,103 | 4.4% |
| CALL_PY_EXACT_ARGS | 872,080 | 1.4% |
| LOAD_ATTR_METHOD_NO_DICT | 619,620 | 1.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,468,940 | 89.0% |
| LOAD_FAST | 187,400 | 6.8% |
| LOAD_ATTR_MODULE | 92,440 | 3.3% |
| LOAD_ATTR_METHOD_NO_DICT | 25,800 | 0.9% |
| CALL | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,107,260 | 75.9% |
| LOAD_CONST | 248,840 | 9.0% |
| GET_ITER | 188,420 | 6.8% |
| CONTAINS_OP | 92,460 | 3.3% |
| RETURN_VALUE | 91,780 | 3.3% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,975,340 | 98.2% |
| ENTER_EXECUTOR | 45,580 | 1.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,200 | 0.2% |
| CALL | 1,540 | 0.1% |
| LOAD_ATTR | 1,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,727,780 | 57.0% |
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
| LOAD_GLOBAL_MODULE | 6,516,600 | 55.0% |
| LOAD_FAST | 3,708,990 | 31.3% |
| RETURN_VALUE | 631,520 | 5.3% |
| LOAD_ATTR_SLOT | 257,100 | 2.2% |
| BUILD_TUPLE | 243,160 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,077,660 | 42.8% |
| POP_TOP | 4,067,330 | 34.3% |
| BINARY_OP_ADD_INT | 1,467,800 | 12.4% |
| BINARY_OP_ADD_UNICODE | 984,600 | 8.3% |
| STORE_FAST | 171,460 | 1.4% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 161,636,760 | 37.3% |
| LOAD_FAST_LOAD_FAST | 102,307,286 | 23.6% |
| LOAD_ATTR_METHOD_NO_DICT | 74,528,132 | 17.2% |
| LOAD_ATTR_SLOT | 13,762,671 | 3.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,906,640 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 375,496,241 | 86.7% |
| COPY_FREE_VARS | 47,447,544 | 11.0% |
| MAKE_CELL | 4,857,600 | 1.1% |
| RETURN_GENERATOR | 4,222,960 | 1.0% |
| CALL_PY_EXACT_ARGS | 721,637 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 7,932,960 | 38.3% |
| LOAD_FAST | 6,740,226 | 32.5% |
| LOAD_FAST_LOAD_FAST | 1,837,940 | 8.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,154,660 | 5.6% |
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
| LOAD_ATTR_SLOT | 1,464,624 | 7.2% |
| RETURN_VALUE | 22,540 | 0.1% |
| LOAD_FAST_CHECK | 19,480 | 0.1% |
| RETURN_GENERATOR | 8,240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,960,180 | 93.2% |
| LOAD_GLOBAL_BUILTIN | 762,360 | 3.7% |
| BUILD_TUPLE | 531,024 | 2.6% |
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
| LOAD_CONST | 14,650,104 | 39.1% |
| CALL_LEN | 5,888,020 | 15.7% |
| LOAD_GLOBAL_MODULE | 3,585,280 | 9.6% |
| COPY | 3,580,400 | 9.6% |
| LOAD_ATTR_CLASS | 3,555,000 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 21,938,533 | 58.6% |
| POP_JUMP_IF_TRUE | 11,154,992 | 29.8% |
| COPY | 2,105,664 | 5.6% |
| RETURN_VALUE | 1,277,940 | 3.4% |
| EXTENDED_ARG | 626,880 | 1.7% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 30,940,436 | 71.4% |
| LOAD_FAST | 9,063,852 | 20.9% |
| RETURN_VALUE | 957,820 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 836,208 | 1.9% |
| LOAD_ATTR_MODULE | 633,760 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 26,905,632 | 62.1% |
| POP_JUMP_IF_FALSE | 11,244,040 | 25.9% |
| COPY | 3,095,724 | 7.1% |
| RETURN_VALUE | 1,230,028 | 2.8% |
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
| ENTER_EXECUTOR | 47,901,473 | 39.0% |
| GET_ITER | 44,659,744 | 36.3% |
| SWAP | 22,380,080 | 18.2% |
| LOAD_FAST | 5,162,300 | 4.2% |
| EXTENDED_ARG | 2,643,740 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,080,289 | 43.2% |
| LOAD_FAST | 27,118,131 | 22.1% |
| SWAP | 17,863,460 | 14.5% |
| RETURN_CONST | 14,502,036 | 11.8% |
| STORE_FAST_LOAD_FAST | 5,300,046 | 4.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,952,940 | 63.2% |
| ENTER_EXECUTOR | 2,453,179 | 26.0% |
| SWAP | 790,400 | 8.4% |
| EXTENDED_ARG | 213,640 | 2.3% |
| JUMP_BACKWARD | 7,460 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,848,879 | 30.2% |
| RETURN_CONST | 2,799,000 | 29.7% |
| LOAD_FAST | 2,203,380 | 23.4% |
| LOAD_GLOBAL_MODULE | 825,720 | 8.8% |
| STORE_FAST_LOAD_FAST | 334,960 | 3.6% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 18,926,277 | 62.7% |
| ENTER_EXECUTOR | 8,480,626 | 28.1% |
| SWAP | 2,650,160 | 8.8% |
| EXTENDED_ARG | 69,080 | 0.2% |
| FOR_ITER_LIST | 34,765 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,500,183 | 58.0% |
| STORE_FAST | 6,363,997 | 21.1% |
| SWAP | 2,631,000 | 8.7% |
| STORE_FAST_LOAD_FAST | 1,755,560 | 5.8% |
| LOAD_FAST_LOAD_FAST | 1,077,760 | 3.6% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,154,700 | 88.3% |
| LOAD_FAST | 1,544,160 | 10.4% |
| COPY | 105,520 | 0.7% |
| ENTER_EXECUTOR | 81,140 | 0.5% |
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
| LOAD_FAST | 124,139,752 | 80.4% |
| LOAD_FAST_LOAD_FAST | 12,630,997 | 8.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,948,940 | 3.9% |
| LOAD_GLOBAL_MODULE | 4,175,120 | 2.7% |
| ENTER_EXECUTOR | 1,854,420 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,848,063 | 18.7% |
| LOAD_CONST | 27,730,240 | 18.0% |
| LOAD_ATTR_METHOD_NO_DICT | 14,231,213 | 9.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,938,060 | 8.4% |
| CONTAINS_OP | 7,881,625 | 5.1% |


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
| LOAD_FAST | 188,428,720 | 72.1% |
| LOAD_ATTR_SLOT | 26,305,836 | 10.1% |
| LOAD_ATTR_INSTANCE_VALUE | 14,231,213 | 5.4% |
| LOAD_GLOBAL_MODULE | 10,018,040 | 3.8% |
| ENTER_EXECUTOR | 8,194,868 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 116,073,201 | 44.4% |
| CALL_PY_EXACT_ARGS | 74,528,132 | 28.5% |
| LOAD_CONST | 24,528,336 | 9.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 20,162,016 | 7.7% |
| LOAD_GLOBAL_MODULE | 17,982,931 | 6.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,553,343 | 81.8% |
| LOAD_ATTR_INSTANCE_VALUE | 12,938,060 | 11.4% |
| LOAD_DEREF | 2,523,540 | 2.2% |
| LOAD_ATTR_WITH_HINT | 1,358,040 | 1.2% |
| LOAD_FAST_LOAD_FAST | 1,281,440 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,391,581 | 70.1% |
| LOAD_FAST_LOAD_FAST | 15,712,946 | 13.9% |
| CALL_PY_EXACT_ARGS | 10,906,640 | 9.6% |
| LOAD_CONST | 2,703,800 | 2.4% |
| LOAD_DEREF | 2,126,500 | 1.9% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 16,648,145 | 65.4% |
| LOAD_ATTR_MODULE | 5,797,300 | 22.8% |
| LOAD_ATTR_CLASS | 1,544,160 | 6.1% |
| LOAD_FAST_LOAD_FAST | 1,235,000 | 4.9% |
| LOAD_FAST | 202,480 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 5,797,300 | 22.8% |
| PUSH_NULL | 4,892,500 | 19.2% |
| LOAD_FAST | 4,100,440 | 16.1% |
| COMPARE_OP | 2,505,620 | 9.8% |
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
| LOAD_FAST | 14,899,662 | 54.5% |
| LOAD_ATTR_SLOT | 6,438,363 | 23.5% |
| ENTER_EXECUTOR | 5,179,549 | 18.9% |
| LOAD_ATTR_INSTANCE_VALUE | 482,920 | 1.8% |
| CALL | 93,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 25,543,788 | 93.4% |
| RETURN_VALUE | 1,068,828 | 3.9% |
| LOAD_FAST | 239,400 | 0.9% |
| STORE_FAST | 238,600 | 0.9% |
| LOAD_CONST | 105,300 | 0.4% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 435,067,122 | 88.1% |
| LOAD_ATTR_SLOT | 34,705,924 | 7.0% |
| LOAD_DEREF | 7,774,220 | 1.6% |
| LOAD_FAST_LOAD_FAST | 6,552,342 | 1.3% |
| STORE_FAST_LOAD_FAST | 2,977,120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,553,620 | 12.1% |
| GET_ITER | 47,884,836 | 9.7% |
| STORE_FAST | 44,457,220 | 9.0% |
| RETURN_VALUE | 36,491,790 | 7.4% |
| LOAD_ATTR_SLOT | 34,705,924 | 7.0% |


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
| RESUME_CHECK | 168,020,032 | 31.0% |
| POP_JUMP_IF_FALSE | 131,381,445 | 24.2% |
| STORE_FAST | 71,756,825 | 13.2% |
| LOAD_FAST | 39,441,320 | 7.3% |
| POP_JUMP_IF_NOT_NONE | 36,588,400 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 376,245,483 | 69.4% |
| LOAD_DEREF | 92,064,060 | 17.0% |
| CALL_ISINSTANCE | 34,999,520 | 6.5% |
| CALL_BUILTIN_CLASS | 7,114,948 | 1.3% |
| LOAD_CONST | 6,281,240 | 1.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 266,976,120 | 44.3% |
| STORE_FAST | 58,269,684 | 9.7% |
| RESUME_CHECK | 52,899,400 | 8.8% |
| POP_JUMP_IF_FALSE | 47,519,740 | 7.9% |
| LOAD_GLOBAL_MODULE | 32,687,520 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 230,170,622 | 38.2% |
| LOAD_FAST | 115,788,138 | 19.2% |
| LOAD_FAST_LOAD_FAST | 45,757,780 | 7.6% |
| IS_OP | 41,593,560 | 6.9% |
| LOAD_GLOBAL_MODULE | 32,687,520 | 5.4% |


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
| CALL_PY_EXACT_ARGS | 375,496,241 | 54.5% |
| COPY_FREE_VARS | 93,013,820 | 13.5% |
| CACHE | 69,748,066 | 10.1% |
| CALL_KW | 43,426,700 | 6.3% |
| LOAD_ATTR_PROPERTY | 25,543,788 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 301,413,663 | 43.7% |
| LOAD_GLOBAL_BUILTIN | 168,020,032 | 24.4% |
| RETURN_CONST | 67,668,480 | 9.8% |
| LOAD_FAST_LOAD_FAST | 60,441,380 | 8.8% |
| LOAD_GLOBAL_MODULE | 52,899,400 | 7.7% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 366,968 | 79.3% |
| LOAD_CONST | 95,920 | 20.7% |
| SEND | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 366,968 | 79.3% |
| POP_TOP | 95,940 | 20.7% |
| RESUME | 40 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 44,207,480 | 56.7% |
| LOAD_FAST | 32,504,460 | 41.7% |
| SWAP | 794,320 | 1.0% |
| BINARY_SUBSCR | 449,520 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 32,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,617,620 | 46.9% |
| RETURN_CONST | 13,692,160 | 17.6% |
| LOAD_FAST | 13,002,020 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 5,133,860 | 6.6% |
| LOAD_GLOBAL_MODULE | 3,667,940 | 4.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 359,760,466 | 58.8% |
| LOAD_FAST_LOAD_FAST | 248,585,380 | 40.6% |
| STORE_ATTR_SLOT | 2,484,041 | 0.4% |
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
| LOAD_FAST | 3,630,903 | 76.2% |
| LOAD_ATTR_SLOT | 359,260 | 7.5% |
| LOAD_FAST_LOAD_FAST | 343,728 | 7.2% |
| SWAP | 332,600 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 47,240 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,497,460 | 52.4% |
| ENTER_EXECUTOR | 1,142,700 | 24.0% |
| LOAD_FAST | 919,303 | 19.3% |
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
| LOAD_FAST | 21,643,182 | 74.3% |
| LOAD_ATTR_SLOT | 5,611,640 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 553,760 | 1.9% |
| ENTER_EXECUTOR | 545,980 | 1.9% |
| COPY | 234,540 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 25,226,842 | 86.6% |
| POP_JUMP_IF_TRUE | 2,828,200 | 9.7% |
| EXTENDED_ARG | 992,840 | 3.4% |
| TO_BOOL_NONE | 36,526 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 32,720 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 266,633,869 | 65.1% |
| COPY | 38,416,604 | 9.4% |
| LOAD_FAST | 34,142,960 | 8.3% |
| RETURN_VALUE | 25,330,620 | 6.2% |
| LOAD_ATTR_SLOT | 11,603,840 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 275,814,515 | 67.4% |
| POP_JUMP_IF_TRUE | 100,440,258 | 24.5% |
| UNARY_NOT | 22,824,820 | 5.6% |
| EXTENDED_ARG | 10,432,820 | 2.5% |
| TO_BOOL_STR | 640 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,183,598 | 62.9% |
| LOAD_ATTR_INSTANCE_VALUE | 356,080 | 18.9% |
| RETURN_VALUE | 148,400 | 7.9% |
| LOAD_ATTR_SLOT | 138,880 | 7.4% |
| BINARY_OP | 51,840 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,349,498 | 71.7% |
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
| LOAD_FAST | 34,675,500 | 75.9% |
| LOAD_ATTR_SLOT | 6,506,760 | 14.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,594,720 | 5.7% |
| COPY | 888,220 | 1.9% |
| BINARY_SUBSCR_LIST_INT | 393,200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 34,742,340 | 76.0% |
| POP_JUMP_IF_FALSE | 7,628,640 | 16.7% |
| UNARY_NOT | 2,525,220 | 5.5% |
| EXTENDED_ARG | 790,880 | 1.7% |
| TO_BOOL | 4,300 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,342,618 | 63.4% |
| LOAD_ATTR_SLOT | 8,021,360 | 25.0% |
| COPY | 1,795,240 | 5.6% |
| LOAD_ATTR_INSTANCE_VALUE | 582,760 | 1.8% |
| LOAD_ATTR_MODULE | 518,960 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,004,218 | 71.7% |
| POP_JUMP_IF_TRUE | 8,234,180 | 25.7% |
| EXTENDED_ARG | 776,420 | 2.4% |
| TO_BOOL_ALWAYS_TRUE | 36,854 | 0.1% |
| UNARY_NOT | 7,920 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,661,300 | 72.6% |
| COPY | 1,506,780 | 16.4% |
| LOAD_ATTR_SLOT | 436,820 | 4.8% |
| LOAD_ATTR_INSTANCE_VALUE | 349,280 | 3.8% |
| STORE_FAST_LOAD_FAST | 187,940 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,345,420 | 58.3% |
| POP_JUMP_IF_TRUE | 3,454,200 | 37.6% |
| UNARY_NOT | 369,580 | 4.0% |
| TO_BOOL_NONE | 4,940 | 0.1% |
| TO_BOOL_INT | 1,580 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 14,181,920 | 98.2% |
| RETURN_VALUE | 232,840 | 1.6% |
| LOAD_FAST | 15,920 | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 15,520 | 0.1% |
| BINARY_SLICE | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 14,441,900 | 100.0% |
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
| FOR_ITER | 5,766,573 | 66.8% |
| RETURN_VALUE | 1,471,900 | 17.1% |
| FOR_ITER_LIST | 503,360 | 5.8% |
| RETURN_CONST | 290,360 | 3.4% |
| STORE_FAST | 256,460 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 7,748,653 | 89.8% |
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
|     deferred | 4,638,440 | 20.7% |
|          hit | 17,684,036 | 78.9% |
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
|     deferred | 40,259,107 | 22.3% |
|          hit | 140,591,884 | 77.7% |
|         miss | 1,580 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,320 | 30.4% |
| Failure | 28,220 | 69.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 16,540 | 58.6% |
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
|     deferred | 67,198,663 | 6.1% |
|          hit | 974,715,541 | 88.3% |
|         miss | 60,207,620 | 5.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,247,737 | 91.7% |
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
|     deferred | 41,933,332 | 34.1% |
|          hit | 79,832,025 | 65.0% |
|         miss | 934,964 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 30,616 | 26.3% |
| Failure | 85,631 | 73.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 51,161 | 59.7% |
| baseobject | 13,520 | 15.8% |
| other | 6,040 | 7.1% |
| different types | 5,720 | 6.7% |
| bool | 3,450 | 4.0% |
| tuple | 3,020 | 3.5% |
| list | 2,120 | 2.5% |
| set | 320 | 0.4% |
| string | 280 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 18,457,298 | 10.1% |
|          hit | 159,981,773 | 87.7% |
|         miss | 3,912,149 | 2.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 86,087 | 71.7% |
| Failure | 33,939 | 28.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 8,199 | 24.2% |
| enumerate | 7,820 | 23.0% |
| zip | 6,320 | 18.6% |
| reversed list | 3,960 | 11.7% |
| dict items | 3,900 | 11.5% |
| dict keys | 1,980 | 5.8% |
| dict values | 1,000 | 2.9% |
| itertools | 480 | 1.4% |
| map | 200 | 0.6% |
| other | 80 | 0.2% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 109,234,816 | 8.9% |
|        deopt | 1,580 | 0.0% |
|          hit | 1,034,301,598 | 83.8% |
|         miss | 88,465,238 | 7.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,822,771 | 89.9% |
| Failure | 205,640 | 10.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 102,740 | 50.0% |
| not managed dict | 37,200 | 18.1% |
| shadowed | 26,980 | 13.1% |
| metaclass attribute | 9,240 | 4.5% |
| class method obj | 8,120 | 3.9% |
| non overriding descriptor | 8,020 | 3.9% |
| method | 5,620 | 2.7% |
| class attr simple | 4,060 | 2.0% |
| module attr not found | 2,960 | 1.4% |
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
|          hit | 1,144,857,149 | 100.0% |
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
|          hit | 462,948 | 100.0% |

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
|     deferred | 9,055,299 | 1.3% |
|          hit | 557,979,786 | 79.4% |
|         miss | 133,452,781 | 19.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,540,181 | 99.0% |
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
|     deferred | 3,766,900 | 42.0% |
|          hit | 5,196,991 | 58.0% |

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
|          hit | 520,162,477 | 95.0% |
|         miss | 7,293,174 | 1.3% |

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
|     deferred | 131,814 | 0.5% |
|          hit | 24,992,193 | 99.5% |

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
| Basic | 7,070,319,851 | 50.4% |
| Not specialized | 1,262,145,660 | 9.0% |
| Specialized hits | 5,414,297,964 | 38.6% |
| Specialized misses | 294,352,226 | 2.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 109,234,816 | 34.7% |
| CALL | 67,198,663 | 21.3% |
| COMPARE_OP | 41,933,332 | 13.3% |
| BINARY_SUBSCR | 40,259,107 | 12.8% |
| TO_BOOL | 20,083,360 | 6.4% |
| FOR_ITER | 18,457,298 | 5.9% |
| STORE_ATTR | 9,055,299 | 2.9% |
| BINARY_OP | 4,638,440 | 1.5% |
| STORE_SUBSCR | 3,766,900 | 1.2% |
| UNPACK_SEQUENCE | 131,814 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 131,673,101 | 44.7% |
| LOAD_ATTR_METHOD_NO_DICT | 57,135,849 | 19.4% |
| CALL_PY_EXACT_ARGS | 44,543,720 | 15.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 14,572,616 | 5.0% |
| LOAD_ATTR_SLOT | 8,295,847 | 2.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 8,038,180 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 5,638,060 | 1.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,525,760 | 1.9% |
| TO_BOOL_ALWAYS_TRUE | 3,840,892 | 1.3% |
| TO_BOOL_NONE | 2,650,862 | 0.9% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 120,974,926 | 17.5% |
| Calls to Python functions inlined | 570,597,641 | 82.5% |
| Calls via PyEval_EvalFrame (total) | 120,974,926 | 17.5% |
| Calls via PyEval_EvalFrame (vector) | 106,566,926 | 15.4% |
| Calls via PyEval_EvalFrame (generator) | 14,408,000 | 2.1% |
| Calls via PyEval_EvalFrame (legacy) | 100 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 106,566,786 | 15.4% |
| Calls via PyEval_EvalFrame (build class) | 40 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 13,898,102 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 2,475,100 | 0.4% |
| Calls via PyEval_EvalFrame (api) | 23,661,044 | 3.4% |
| Calls via PyEval_EvalFrame (method) | 100 | 0.0% |
| Frame objects created | 4,745,560 | 0.7% |
| Frames pushed | 487,164,713 | 70.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 307,147,696 | 28.5% |
| Frees to freelist | 307,217,710 |  |
| Allocations | 769,288,646 | 71.5% |
| Allocations to 512 bytes | 768,240,475 | 71.4% |
| Allocations to 4 kbytes | 729,651 | 0.1% |
| Allocations over 4 kbytes | 318,520 | 0.0% |
| Frees | 794,820,436 |  |
| New values | 8,867,540 |  |
| Interpreter increfs | 7,314,309,913 | 74.1% |
| Interpreter decrefs | 8,054,492,292 | 74.7% |
| Increfs | 2,559,029,566 | 25.9% |
| Decrefs | 2,722,794,059 | 25.3% |
| Materialize dict (on request) | 660 | 0.0% |
| Materialize dict (new key) | 2,300 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 400 | 0.0% |
| Method cache hits | 418,292,229 |  |
| Method cache misses | 11,238,958 |  |
| Method cache collisions | 13,230,184 |  |
| Method cache dunder hits | 355,783,700 |  |
| Method cache dunder misses | 2,242,188 |  |


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
| Trace stack overflow | 21 | 0.1% |
| Trace stack underflow | 80 | 0.5% |
| Trace too long | 300 | 1.7% |
| Trace too short | 1,500 | 8.7% |
| Inner loop found | 717 | 4.1% |
| Recursive call | 400 | 2.3% |
| Traces executed | 116,862,219 |  |
| Uops executed | 1,746,608,268 | 14.95 |

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
| <= 32 | 5,478 | 34.7% |
| <= 64 | 4,451 | 28.2% |
| <= 128 | 2,861 | 18.1% |
| <= 256 | 1,907 | 12.1% |
| <= 512 | 703 | 4.5% |


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
| <= 16 | 3,998 | 25.3% |
| <= 32 | 5,176 | 32.8% |
| <= 64 | 3,039 | 19.3% |
| <= 128 | 2,047 | 13.0% |
| <= 256 | 560 | 3.5% |
| <= 512 | 400 | 2.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 2,278,057 | 1.9% |
| <= 2 | 56,255,356 | 48.1% |
| <= 4 | 1,913,079 | 1.6% |
| <= 8 | 15,092,536 | 12.9% |
| <= 16 | 12,498,325 | 10.7% |
| <= 32 | 14,729,639 | 12.6% |
| <= 64 | 10,749,253 | 9.2% |
| <= 128 | 2,696,535 | 2.3% |
| <= 256 | 273,974 | 0.2% |
| <= 512 | 299,822 | 0.3% |
| <= 1,024 | 34,303 | 0.0% |
| <= 2,048 | 9,040 | 0.0% |
| <= 4,096 | 15,660 | 0.0% |
| <= 8,192 | 16,020 | 0.0% |
| <= 16,384 | 620 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 208,492,752 | 11.9% | 11.9% |  |
| _SET_IP | 179,255,327 | 10.3% | 22.2% |  |
| _CHECK_VALIDITY | 141,573,969 | 8.1% | 30.3% |  |
| STORE_FAST | 99,370,865 | 5.7% | 36.0% |  |
| _ITER_CHECK_LIST | 97,024,453 | 5.6% | 41.6% | 0.6% |
| _GUARD_NOT_EXHAUSTED_LIST | 96,431,957 | 5.5% | 47.1% | 49.8% |
| _GUARD_GLOBALS_VERSION | 72,904,991 | 4.2% | 51.2% | 0.8% |
| _GUARD_TYPE_VERSION | 65,069,660 | 3.7% | 55.0% | 18.1% |
| _ITER_NEXT_LIST | 48,426,009 | 2.8% | 57.7% |  |
| LOAD_CONST | 44,224,027 | 2.5% | 60.3% |  |
| _LOAD_GLOBAL_MODULE | 39,652,344 | 2.3% | 62.5% |  |
| _GUARD_BUILTINS_VERSION | 32,650,647 | 1.9% | 64.4% |  |
| _LOAD_GLOBAL_BUILTINS | 32,650,647 | 1.9% | 66.3% |  |
| _GUARD_IS_FALSE_POP | 28,473,844 | 1.6% | 67.9% | 9.8% |
| _GUARD_IS_TRUE_POP | 25,592,341 | 1.5% | 69.4% | 11.0% |
| _EXIT_TRACE | 25,137,184 | 1.4% | 70.8% |  |
| _JUMP_TO_TOP | 22,401,725 | 1.3% | 72.1% |  |
| _LOAD_ATTR_SLOT | 21,428,333 | 1.2% | 73.3% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 20,566,103 | 1.2% | 74.5% | 8.9% |
| _CHECK_PEP_523 | 20,566,103 | 1.2% | 75.7% |  |
| TO_BOOL_BOOL | 20,299,895 | 1.2% | 76.8% |  |
| _FOR_ITER_TIER_TWO | 19,339,120 | 1.1% | 78.0% | 42.3% |
| CALL_ISINSTANCE | 19,260,575 | 1.1% | 79.1% |  |
| _CHECK_STACK_SPACE | 18,745,843 | 1.1% | 80.1% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 18,744,243 | 1.1% | 81.2% |  |
| _PUSH_FRAME | 18,744,243 | 1.1% | 82.3% |  |
| _SAVE_RETURN_OFFSET | 18,744,243 | 1.1% | 83.3% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 15,622,575 | 0.9% | 84.2% |  |
| _ITER_CHECK_TUPLE | 14,212,600 | 0.8% | 85.1% | 12.0% |
| BINARY_SUBSCR_LIST_INT | 14,202,680 | 0.8% | 85.9% |  |
| RESUME_CHECK | 13,027,847 | 0.7% | 86.6% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 12,503,999 | 0.7% | 87.3% | 59.3% |
| COMPARE_OP_STR | 12,195,780 | 0.7% | 88.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 11,933,007 | 0.7% | 88.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 11,933,007 | 0.7% | 89.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,126,107 | 0.6% | 90.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 9,623,560 | 0.6% | 90.6% |  |
| _GUARD_IS_NOT_NONE_POP | 9,339,480 | 0.5% | 91.1% | 1.6% |
| CONTAINS_OP | 8,590,429 | 0.5% | 91.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 8,015,379 | 0.5% | 92.1% | 23.6% |
| _GUARD_NOT_EXHAUSTED_RANGE | 6,059,720 | 0.3% | 92.4% | 42.1% |
| _ITER_CHECK_RANGE | 6,059,720 | 0.3% | 92.8% |  |
| _LOAD_ATTR | 5,867,601 | 0.3% | 93.1% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 5,851,800 | 0.3% | 93.4% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 5,851,800 | 0.3% | 93.8% |  |
| COMPARE_OP_INT | 5,466,819 | 0.3% | 94.1% |  |
| _GUARD_IS_NONE_POP | 5,197,280 | 0.3% | 94.4% | 5.5% |
| _ITER_NEXT_TUPLE | 5,089,338 | 0.3% | 94.7% |  |
| PUSH_NULL | 4,479,525 | 0.3% | 94.9% |  |
| _GUARD_BOTH_INT | 4,048,244 | 0.2% | 95.2% | 1.4% |
| LIST_APPEND | 3,918,329 | 0.2% | 95.4% |  |
| _GUARD_BOTH_UNICODE | 3,900,180 | 0.2% | 95.6% |  |
| _BINARY_OP_ADD_UNICODE | 3,900,180 | 0.2% | 95.8% |  |
| _CHECK_ATTR_MODULE | 3,704,335 | 0.2% | 96.0% |  |
| _LOAD_ATTR_MODULE | 3,704,335 | 0.2% | 96.3% |  |
| BINARY_SUBSCR_DICT | 3,595,915 | 0.2% | 96.5% |  |
| TO_BOOL_NONE | 3,551,080 | 0.2% | 96.7% | 4.8% |
| _ITER_NEXT_RANGE | 3,510,261 | 0.2% | 96.9% |  |
| _GUARD_KEYS_VERSION | 3,357,058 | 0.2% | 97.1% | 8.3% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 3,357,058 | 0.2% | 97.2% |  |
| _BINARY_OP_SUBTRACT_INT | 3,255,059 | 0.2% | 97.4% |  |
| LOAD_DEREF | 3,032,775 | 0.2% | 97.6% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 2,996,553 | 0.2% | 97.8% |  |
| SET_ADD | 2,718,330 | 0.2% | 97.9% |  |
| CALL_BUILTIN_FAST | 2,682,569 | 0.2% | 98.1% |  |
| BUILD_LIST | 2,616,876 | 0.1% | 98.2% |  |
| TO_BOOL_STR | 2,366,380 | 0.1% | 98.4% |  |
| POP_TOP | 2,268,179 | 0.1% | 98.5% |  |
| CALL_STR_1 | 2,266,480 | 0.1% | 98.6% |  |
| CALL_BUILTIN_O | 2,262,800 | 0.1% | 98.8% |  |
| _POP_FRAME | 2,211,709 | 0.1% | 98.9% |  |
| GET_ITER | 1,958,301 | 0.1% | 99.0% |  |
| MAP_ADD | 1,283,500 | 0.1% | 99.1% |  |
| FORMAT_SIMPLE | 1,079,260 | 0.1% | 99.1% |  |
| BUILD_TUPLE | 990,102 | 0.1% | 99.2% |  |
| _COMPARE_OP | 961,160 | 0.1% | 99.3% |  |
| BUILD_STRING | 956,180 | 0.1% | 99.3% |  |
| CALL_LEN | 790,660 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 743,160 | 0.0% | 99.4% |  |
| _BINARY_OP_ADD_INT | 737,505 | 0.0% | 99.4% |  |
| TO_BOOL_ALWAYS_TRUE | 607,760 | 0.0% | 99.5% | 82.6% |
| SWAP | 558,840 | 0.0% | 99.5% |  |
| _BINARY_SUBSCR | 557,433 | 0.0% | 99.5% |  |
| _STORE_ATTR_SLOT | 517,580 | 0.0% | 99.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 496,700 | 0.0% | 99.6% |  |
| STORE_SUBSCR_DICT | 494,469 | 0.0% | 99.6% |  |
| BINARY_SLICE | 483,600 | 0.0% | 99.6% |  |
| CALL_TYPE_1 | 481,280 | 0.0% | 99.7% |  |
| IS_OP | 456,700 | 0.0% | 99.7% |  |
| COPY | 437,089 | 0.0% | 99.7% |  |
| _LOAD_ATTR_WITH_HINT | 420,220 | 0.0% | 99.8% | 0.1% |
| _CHECK_ATTR_WITH_HINT | 420,220 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 356,660 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_STR_INT | 351,041 | 0.0% | 99.8% | 0.0% |
| CALL_BUILTIN_CLASS | 343,132 | 0.0% | 99.8% |  |
| UNARY_NOT | 332,840 | 0.0% | 99.9% |  |
| BUILD_MAP | 317,241 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 305,390 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TUPLE | 290,840 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 245,000 | 0.0% | 99.9% |  |
| _BINARY_OP | 231,100 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_LIST | 179,280 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 154,062 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 141,380 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 93,936 | 0.0% | 100.0% |  |
| MAKE_CELL | 88,660 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 86,660 | 0.0% | 100.0% | 93.6% |
| LOAD_SUPER_ATTR_METHOD | 83,040 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 80,740 | 0.0% | 100.0% |  |
| _TO_BOOL | 68,000 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 62,680 | 0.0% | 100.0% | 72.7% |
| STORE_DEREF | 38,720 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 17,600 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 13,600 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 13,600 | 0.0% | 100.0% |  |
| BUILD_SET | 7,040 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 6,706 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 5,520 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 5,440 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 4,960 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 1,640 | 0.0% | 100.0% |  |
| _STORE_SUBSCR | 1,180 | 0.0% | 100.0% |  |
| _STORE_ATTR | 840 | 0.0% | 100.0% |  |
| UNARY_INVERT | 580 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 540 | 0.0% | 100.0% |  |
| UNPACK_EX | 420 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 300 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 1,959 |
| FOR_ITER_GEN | 1,500 |
| CALL_LIST_APPEND | 1,163 |
| CALL_KW | 940 |
| CALL_PY_WITH_DEFAULTS | 860 |
| LOAD_ATTR_PROPERTY | 821 |
| YIELD_VALUE | 780 |
| CALL_ALLOC_AND_ENTER_INIT | 240 |
| BINARY_SUBSCR_GETITEM | 20 |
| RETURN_GENERATOR | 15 |


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
Stats gathered on: 2023-11-19
