
# Pystats results

- benchmark: mypy2
- fork: python
- ref: main
- commit hash: 51863b7
- commit date: 2023-09-23T11:31:17-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 2,286,314,738 | 20.5% | 20.5% |  |
| LOAD_CONST | 550,315,022 | 4.9% | 25.5% |  |
| RESUME_CHECK | 526,829,624 | 4.7% | 30.2% | 0.0% |
| LOAD_GLOBAL_MODULE | 481,502,908 | 4.3% | 34.5% |  |
| STORE_ATTR_SLOT | 457,813,496 | 4.1% | 38.6% | 21.6% |
| LOAD_FAST_LOAD_FAST | 440,094,720 | 4.0% | 42.6% |  |
| LOAD_GLOBAL_BUILTIN | 431,375,183 | 3.9% | 46.4% | 0.0% |
| POP_JUMP_IF_FALSE | 428,662,946 | 3.8% | 50.3% |  |
| STORE_FAST | 417,375,964 | 3.7% | 54.0% |  |
| LOAD_ATTR_SLOT | 385,316,625 | 3.5% | 57.5% | 1.5% |
| CALL_PY_EXACT_ARGS | 335,481,303 | 3.0% | 60.5% | 10.1% |
| TO_BOOL_BOOL | 322,377,418 | 2.9% | 63.4% | 0.0% |
| RETURN_VALUE | 298,102,572 | 2.7% | 66.1% |  |
| RETURN_CONST | 225,048,332 | 2.0% | 68.1% |  |
| CALL_ISINSTANCE | 219,094,572 | 2.0% | 70.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 207,621,744 | 1.9% | 71.9% | 21.0% |
| POP_JUMP_IF_TRUE | 177,349,786 | 1.6% | 73.5% |  |
| POP_TOP | 166,626,592 | 1.5% | 75.0% |  |
| FOR_ITER_LIST | 128,535,138 | 1.2% | 76.2% | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 124,724,996 | 1.1% | 77.3% | 3.5% |
| JUMP_BACKWARD | 105,559,960 | 0.9% | 78.2% |  |
| LOAD_DEREF | 99,239,232 | 0.9% | 79.1% |  |
| GET_ITER | 91,733,132 | 0.8% | 80.0% |  |
| INTERPRETER_EXIT | 90,687,869 | 0.8% | 80.8% |  |
| BINARY_SUBSCR_DICT | 90,580,800 | 0.8% | 81.6% |  |
| LOAD_ATTR | 88,501,828 | 0.8% | 82.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 87,171,602 | 0.8% | 83.2% | 12.7% |
| CONTAINS_OP | 76,093,692 | 0.7% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 75,816,000 | 0.7% | 84.5% |  |
| COPY_FREE_VARS | 70,554,780 | 0.6% | 85.2% |  |
| SWAP | 66,036,000 | 0.6% | 85.8% |  |
| POP_JUMP_IF_NONE | 65,653,440 | 0.6% | 86.3% |  |
| LOAD_SUPER_ATTR_METHOD | 64,576,560 | 0.6% | 86.9% |  |
| BUILD_LIST | 63,887,160 | 0.6% | 87.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 58,506,940 | 0.5% | 88.0% | 2.2% |
| CALL_KW | 57,378,960 | 0.5% | 88.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 51,751,880 | 0.5% | 89.0% | 8.0% |
| CALL | 51,428,320 | 0.5% | 89.5% |  |
| IS_OP | 42,897,600 | 0.4% | 89.8% |  |
| COMPARE_OP_STR | 41,645,131 | 0.4% | 90.2% | 0.2% |
| NOP | 40,104,300 | 0.4% | 90.6% |  |
| COPY | 38,205,128 | 0.3% | 90.9% |  |
| JUMP_FORWARD | 35,598,000 | 0.3% | 91.2% |  |
| TO_BOOL_LIST | 34,829,420 | 0.3% | 91.6% | 0.7% |
| COMPARE_OP | 32,301,608 | 0.3% | 91.8% |  |
| COMPARE_OP_INT | 32,096,336 | 0.3% | 92.1% | 1.7% |
| BINARY_SUBSCR | 30,612,440 | 0.3% | 92.4% |  |
| CALL_BUILTIN_CLASS | 30,061,846 | 0.3% | 92.7% |  |
| PUSH_NULL | 29,307,360 | 0.3% | 92.9% |  |
| EXTENDED_ARG | 28,800,000 | 0.3% | 93.2% |  |
| FOR_ITER | 28,404,282 | 0.3% | 93.5% |  |
| STORE_FAST_STORE_FAST | 27,217,500 | 0.2% | 93.7% |  |
| CALL_LEN | 27,135,840 | 0.2% | 93.9% |  |
| TO_BOOL_NONE | 26,546,262 | 0.2% | 94.2% | 7.6% |
| FOR_ITER_TUPLE | 26,457,724 | 0.2% | 94.4% | 5.6% |
| MAKE_CELL | 24,962,400 | 0.2% | 94.6% |  |
| BUILD_TUPLE | 24,214,621 | 0.2% | 94.9% |  |
| BINARY_SUBSCR_LIST_INT | 24,177,840 | 0.2% | 95.1% |  |
| CALL_LIST_APPEND | 24,108,420 | 0.2% | 95.3% |  |
| LOAD_ATTR_WITH_HINT | 23,253,420 | 0.2% | 95.5% | 2.1% |
| MAP_ADD | 23,127,840 | 0.2% | 95.7% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 22,909,820 | 0.2% | 95.9% | 27.2% |
| LIST_APPEND | 21,982,320 | 0.2% | 96.1% |  |
| TO_BOOL_ALWAYS_TRUE | 21,943,878 | 0.2% | 96.3% | 13.3% |
| LOAD_ATTR_MODULE | 21,860,800 | 0.2% | 96.5% |  |
| LOAD_FAST_AND_CLEAR | 21,027,120 | 0.2% | 96.7% |  |
| LOAD_ATTR_PROPERTY | 20,515,233 | 0.2% | 96.9% | 6.6% |
| UNARY_NOT | 19,870,320 | 0.2% | 97.1% |  |
| CALL_PY_WITH_DEFAULTS | 15,545,380 | 0.1% | 97.2% | 2.1% |
| CALL_TUPLE_1 | 15,250,756 | 0.1% | 97.3% |  |
| TO_BOOL | 15,226,040 | 0.1% | 97.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 14,813,580 | 0.1% | 97.6% |  |
| CALL_BUILTIN_O | 13,550,747 | 0.1% | 97.7% | 7.3% |
| STORE_FAST_LOAD_FAST | 12,285,360 | 0.1% | 97.8% |  |
| CALL_BUILTIN_FAST | 11,604,480 | 0.1% | 97.9% |  |
| LOAD_ATTR_CLASS | 11,177,660 | 0.1% | 98.0% | 2.5% |
| UNPACK_SEQUENCE_LIST | 10,970,400 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 9,694,140 | 0.1% | 98.2% |  |
| STORE_ATTR | 9,289,120 | 0.1% | 98.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 9,118,560 | 0.1% | 98.4% |  |
| CALL_TYPE_1 | 8,694,000 | 0.1% | 98.5% |  |
| TO_BOOL_STR | 8,655,440 | 0.1% | 98.5% | 3.2% |
| BUILD_MAP | 8,485,440 | 0.1% | 98.6% |  |
| BINARY_SUBSCR_TUPLE_INT | 8,463,600 | 0.1% | 98.7% |  |
| DELETE_ATTR | 8,440,800 | 0.1% | 98.8% |  |
| YIELD_VALUE | 8,411,280 | 0.1% | 98.9% |  |
| BINARY_OP_ADD_UNICODE | 7,040,400 | 0.1% | 98.9% |  |
| MAKE_FUNCTION | 6,418,080 | 0.1% | 99.0% |  |
| BINARY_OP_ADD_INT | 6,064,020 | 0.1% | 99.0% | 0.8% |
| CALL_FUNCTION_EX | 5,974,200 | 0.1% | 99.1% |  |
| RETURN_GENERATOR | 5,838,480 | 0.1% | 99.1% |  |
| BINARY_OP_SUBTRACT_INT | 5,260,320 | 0.0% | 99.2% |  |
| CALL_ALLOC_AND_ENTER_INIT | 5,001,220 | 0.0% | 99.2% | 0.1% |
| EXIT_INIT_CHECK | 4,994,400 | 0.0% | 99.3% |  |
| BINARY_SLICE | 4,753,440 | 0.0% | 99.3% |  |
| SET_FUNCTION_ATTRIBUTE | 3,960,480 | 0.0% | 99.3% |  |
| STORE_SUBSCR_DICT | 3,944,400 | 0.0% | 99.4% |  |
| BINARY_OP | 3,647,340 | 0.0% | 99.4% |  |
| STORE_DEREF | 3,570,240 | 0.0% | 99.4% |  |
| PUSH_EXC_INFO | 3,113,760 | 0.0% | 99.5% |  |
| POP_EXCEPT | 3,113,760 | 0.0% | 99.5% |  |
| CHECK_EXC_MATCH | 3,113,760 | 0.0% | 99.5% |  |
| SET_ADD | 3,087,360 | 0.0% | 99.6% |  |
| DICT_MERGE | 2,898,000 | 0.0% | 99.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,851,260 | 0.0% | 99.6% |  |
| STORE_SUBSCR | 2,823,820 | 0.0% | 99.6% |  |
| CALL_STR_1 | 2,614,320 | 0.0% | 99.7% |  |
| FORMAT_SIMPLE | 2,582,640 | 0.0% | 99.7% |  |
| RERAISE | 2,513,760 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,454,480 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,286,380 | 0.0% | 99.7% | 10.9% |
| CALL_INTRINSIC_1 | 2,250,780 | 0.0% | 99.8% |  |
| LOAD_FAST_CHECK | 2,116,800 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_GETITEM | 2,091,360 | 0.0% | 99.8% | 0.0% |
| BEFORE_WITH | 2,006,700 | 0.0% | 99.8% |  |
| IMPORT_FROM | 1,819,920 | 0.0% | 99.8% |  |
| BUILD_STRING | 1,808,160 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TUPLE | 1,652,880 | 0.0% | 99.9% |  |
| TO_BOOL_INT | 1,520,640 | 0.0% | 99.9% | 4.2% |
| IMPORT_NAME | 1,487,040 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 1,465,920 | 0.0% | 99.9% |  |
| BUILD_SET | 1,414,560 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 1,233,120 | 0.0% | 99.9% | 3.2% |
| FOR_ITER_GEN | 996,000 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_STR_INT | 951,120 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 855,860 | 0.0% | 100.0% | 1.7% |
| LOAD_SUPER_ATTR_ATTR | 812,400 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 802,320 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 429,600 | 0.0% | 100.0% |  |
| SEND_GEN | 343,440 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 324,240 | 0.0% | 100.0% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 271,440 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 254,640 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 220,200 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 216,060 | 0.0% | 100.0% | 22.1% |
| DELETE_FAST | 151,440 | 0.0% | 100.0% |  |
| LIST_EXTEND | 112,860 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 100,120 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 72,000 | 0.0% | 100.0% |  |
| END_SEND | 72,000 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 70,080 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 50,880 | 0.0% | 100.0% |  |
| END_FOR | 40,560 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 24,720 | 0.0% | 100.0% |  |
| BUILD_SLICE | 13,440 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 4,560 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 3,360 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 2,160 | 0.0% | 100.0% |  |
| UNARY_INVERT | 1,440 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 960 | 0.0% | 100.0% |  |
| UNPACK_EX | 720 | 0.0% | 100.0% |  |
| STORE_SLICE | 720 | 0.0% | 100.0% |  |
| SET_UPDATE | 240 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 240 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 140 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 341,248,162 | 3.1% | 3.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 299,541,495 | 2.7% | 5.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 291,871,836 | 2.6% | 8.4% |
| LOAD_FAST STORE_ATTR_SLOT | 268,742,925 | 2.4% | 10.8% |
| RESUME_CHECK LOAD_FAST | 229,377,670 | 2.1% | 12.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 220,503,868 | 2.0% | 14.8% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 214,015,250 | 1.9% | 16.7% |
| LOAD_CONST LOAD_FAST | 212,095,980 | 1.9% | 18.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 208,925,772 | 1.9% | 20.5% |
| STORE_FAST LOAD_FAST | 208,564,744 | 1.9% | 22.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 200,525,689 | 1.8% | 24.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 186,557,760 | 1.7% | 25.9% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 182,094,012 | 1.6% | 27.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 151,442,624 | 1.4% | 28.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 131,619,154 | 1.2% | 30.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 129,868,800 | 1.2% | 31.2% |
| LOAD_FAST LOAD_CONST | 127,314,960 | 1.1% | 32.4% |
| STORE_ATTR_SLOT LOAD_CONST | 126,971,520 | 1.1% | 33.5% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 106,074,480 | 1.0% | 34.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 102,121,485 | 0.9% | 35.4% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 97,956,776 | 0.9% | 36.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 96,565,980 | 0.9% | 37.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 93,837,960 | 0.8% | 38.0% |
| STORE_ATTR_SLOT RETURN_CONST | 90,707,040 | 0.8% | 38.8% |
| LOAD_FAST RETURN_VALUE | 89,706,060 | 0.8% | 39.6% |
| STORE_ATTR_SLOT LOAD_FAST | 83,717,085 | 0.8% | 40.3% |
| RETURN_CONST POP_TOP | 79,320,480 | 0.7% | 41.0% |
| LOAD_CONST BINARY_SUBSCR_DICT | 77,595,600 | 0.7% | 41.7% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 77,489,760 | 0.7% | 42.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 76,643,550 | 0.7% | 43.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 76,534,626 | 0.7% | 43.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 71,530,240 | 0.6% | 44.4% |
| POP_TOP LOAD_FAST | 70,344,232 | 0.6% | 45.1% |
| FOR_ITER_LIST STORE_FAST | 70,292,548 | 0.6% | 45.7% |
| COPY_FREE_VARS RESUME_CHECK | 69,829,740 | 0.6% | 46.3% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 69,111,360 | 0.6% | 47.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 68,988,981 | 0.6% | 47.6% |
| RETURN_VALUE STORE_FAST | 67,764,000 | 0.6% | 48.2% |
| LOAD_DEREF LOAD_FAST | 66,867,600 | 0.6% | 48.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 66,816,240 | 0.6% | 49.4% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 64,576,560 | 0.6% | 50.0% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 61,548,000 | 0.6% | 50.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 60,926,080 | 0.5% | 51.1% |
| RETURN_VALUE RETURN_VALUE | 60,511,195 | 0.5% | 51.6% |
| LOAD_FAST LOAD_FAST | 59,189,520 | 0.5% | 52.1% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 58,851,920 | 0.5% | 52.7% |
| LOAD_FAST LOAD_ATTR | 57,725,748 | 0.5% | 53.2% |
| LOAD_CONST CALL_KW | 57,378,960 | 0.5% | 53.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 55,922,464 | 0.5% | 54.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 53,815,200 | 0.5% | 54.7% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 53,775,840 | 0.5% | 55.2% |
| CACHE RESUME_CHECK | 52,313,309 | 0.5% | 55.6% |
| RESUME_CHECK RETURN_CONST | 50,785,440 | 0.5% | 56.1% |
| RETURN_CONST INTERPRETER_EXIT | 46,489,260 | 0.4% | 56.5% |
| RETURN_CONST LOAD_FAST | 46,216,320 | 0.4% | 56.9% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 45,426,540 | 0.4% | 57.3% |
| LOAD_ATTR_SLOT LOAD_FAST | 45,234,420 | 0.4% | 57.7% |
| LOAD_ATTR LOAD_FAST | 41,458,464 | 0.4% | 58.1% |
| LOAD_CONST LOAD_CONST | 40,620,600 | 0.4% | 58.5% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 40,491,840 | 0.4% | 58.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 40,190,680 | 0.4% | 59.2% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 37,762,800 | 0.3% | 59.5% |
| RETURN_VALUE LOAD_FAST | 37,582,660 | 0.3% | 59.9% |
| RETURN_VALUE INTERPRETER_EXIT | 36,944,129 | 0.3% | 60.2% |
| LOAD_ATTR_SLOT STORE_FAST | 36,625,920 | 0.3% | 60.5% |
| LOAD_ATTR_SLOT GET_ITER | 35,968,112 | 0.3% | 60.9% |
| LOAD_FAST CONTAINS_OP | 35,965,440 | 0.3% | 61.2% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 35,664,720 | 0.3% | 61.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 35,403,360 | 0.3% | 61.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 35,336,880 | 0.3% | 62.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 34,554,960 | 0.3% | 62.4% |
| GET_ITER FOR_ITER_LIST | 34,084,830 | 0.3% | 62.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 33,184,320 | 0.3% | 63.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 33,165,900 | 0.3% | 63.3% |
| CACHE COPY_FREE_VARS | 32,616,960 | 0.3% | 63.6% |
| CALL_KW RESUME_CHECK | 32,570,160 | 0.3% | 63.9% |
| RETURN_CONST RETURN_VALUE | 32,131,200 | 0.3% | 64.2% |
| POP_JUMP_IF_NONE LOAD_FAST | 31,917,840 | 0.3% | 64.5% |
| LOAD_GLOBAL_MODULE IS_OP | 31,284,000 | 0.3% | 64.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 31,128,480 | 0.3% | 65.1% |
| LOAD_CONST COMPARE_OP_STR | 29,935,352 | 0.3% | 65.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 29,799,000 | 0.3% | 65.6% |
| COPY TO_BOOL_BOOL | 28,930,568 | 0.3% | 65.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 28,860,720 | 0.3% | 66.1% |
| IS_OP POP_JUMP_IF_FALSE | 28,605,600 | 0.3% | 66.4% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 28,576,800 | 0.3% | 66.6% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 28,556,560 | 0.3% | 66.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 27,463,920 | 0.2% | 67.1% |
| LOAD_ATTR_SLOT RETURN_VALUE | 27,348,147 | 0.2% | 67.4% |
| POP_TOP LOAD_FAST_LOAD_FAST | 26,461,260 | 0.2% | 67.6% |
| LOAD_FAST TO_BOOL_LIST | 26,335,680 | 0.2% | 67.9% |
| TO_BOOL_LIST POP_JUMP_IF_TRUE | 26,164,780 | 0.2% | 68.1% |
| LOAD_ATTR_SLOT LOAD_ATTR_SLOT | 26,046,325 | 0.2% | 68.3% |
| RETURN_VALUE POP_TOP | 25,899,120 | 0.2% | 68.6% |
| LOAD_FAST TO_BOOL_BOOL | 25,710,240 | 0.2% | 68.8% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 25,668,000 | 0.2% | 69.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 24,992,548 | 0.2% | 69.2% |
| LOAD_ATTR_SLOT POP_JUMP_IF_NONE | 24,543,840 | 0.2% | 69.5% |
| BUILD_LIST STORE_FAST | 24,489,660 | 0.2% | 69.7% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 24,383,580 | 0.2% | 69.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,681,120 | 77.4% |
| BINARY_OP_SUBTRACT_INT | 667,680 | 14.0% |
| LOAD_FAST | 300,000 | 6.3% |
| BINARY_OP_ADD_INT | 76,080 | 1.6% |
| LOAD_ATTR_SLOT | 18,000 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,754,640 | 36.9% |
| CALL_PY_EXACT_ARGS | 668,160 | 14.1% |
| STORE_FAST | 525,120 | 11.0% |
| GET_ITER | 485,040 | 10.2% |
| BINARY_OP_ADD_UNICODE | 338,160 | 7.1% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 52,313,309 | 56.4% |
| COPY_FREE_VARS | 32,616,960 | 35.1% |
| POP_TOP | 5,693,760 | 6.1% |
| CALL_INTRINSIC_1 | 2,106,000 | 2.3% |
| RETURN_GENERATOR | 70,080 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,945,920 | 97.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 36,060 | 1.8% |
| CALL | 24,720 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,785,600 | 89.0% |
| STORE_FAST | 221,100 | 11.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 246,720 | 57.4% |
| RETURN_VALUE | 147,840 | 34.4% |
| BUILD_STRING | 33,360 | 7.8% |
| LOAD_FAST_LOAD_FAST | 1,440 | 0.3% |
| LOAD_ATTR_MODULE | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 393,360 | 91.6% |
| LOAD_FAST | 34,560 | 8.0% |
| JUMP_FORWARD | 960 | 0.2% |
| LOAD_FAST_LOAD_FAST | 720 | 0.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 15,150,960 | 49.5% |
| LOAD_FAST_LOAD_FAST | 11,280,480 | 36.8% |
| LOAD_FAST | 2,716,560 | 8.9% |
| LOAD_GLOBAL_MODULE | 899,520 | 2.9% |
| COPY | 215,520 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,883,920 | 42.1% |
| CONTAINS_OP | 3,348,480 | 10.9% |
| LOAD_CONST | 3,315,600 | 10.8% |
| LOAD_FAST | 2,398,560 | 7.8% |
| RETURN_VALUE | 2,122,080 | 6.9% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,100,560 | 99.6% |
| BUILD_TUPLE | 12,480 | 0.4% |
| LOAD_GLOBAL_MODULE | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,113,760 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,600 | 65.1% |
| BUILD_SLICE | 12,960 | 18.5% |
| LOAD_FAST | 9,360 | 13.4% |
| LOAD_FAST_LOAD_FAST | 2,160 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 54,960 | 78.4% |
| LOAD_DEREF | 12,960 | 18.5% |
| RETURN_CONST | 1,440 | 2.1% |
| LOAD_FAST | 480 | 0.7% |
| LOAD_CONST | 240 | 0.3% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 40,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 37,920 | 93.5% |
| LOAD_FAST | 2,160 | 5.3% |
| JUMP_BACKWARD | 240 | 0.6% |
| EXTENDED_ARG | 240 | 0.6% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 72,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 72,000 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,994,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,994,400 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,962,000 | 76.0% |
| RETURN_VALUE | 310,080 | 12.0% |
| BINARY_SUBSCR_TUPLE_INT | 211,200 | 8.2% |
| CONVERT_VALUE | 50,880 | 2.0% |
| LOAD_ATTR_SLOT | 29,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,774,320 | 68.7% |
| BUILD_STRING | 808,320 | 31.3% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 88.9% |
| LOAD_CONST | 240 | 11.1% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 35,968,112 | 39.2% |
| LOAD_FAST | 22,018,080 | 24.0% |
| CALL_BUILTIN_CLASS | 14,308,140 | 15.6% |
| BINARY_SUBSCR_DICT | 9,441,120 | 10.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,032,080 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 34,084,830 | 37.2% |
| LOAD_FAST_AND_CLEAR | 20,086,320 | 21.9% |
| FOR_ITER_TUPLE | 14,530,322 | 15.8% |
| FOR_ITER | 10,975,680 | 12.0% |
| FOR_ITER_RANGE | 4,479,900 | 4.9% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 72,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 72,000 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 46,489,260 | 51.3% |
| RETURN_VALUE | 36,944,129 | 40.7% |
| YIELD_VALUE | 7,184,400 | 7.9% |
| RETURN_GENERATOR | 70,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,418,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,280,080 | 51.1% |
| SET_FUNCTION_ATTRIBUTE | 3,081,840 | 48.0% |
| LOAD_CONST | 36,000 | 0.6% |
| LOAD_GLOBAL_MODULE | 10,800 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 5,520 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,351,280 | 28.3% |
| POP_JUMP_IF_TRUE | 10,565,280 | 26.3% |
| POP_JUMP_IF_FALSE | 6,881,520 | 17.2% |
| RESUME_CHECK | 5,018,160 | 12.5% |
| CALL_LIST_APPEND | 1,826,400 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,658,640 | 56.5% |
| LOAD_CONST | 11,083,200 | 27.6% |
| LOAD_GLOBAL_BUILTIN | 3,562,560 | 8.9% |
| LOAD_GLOBAL_MODULE | 2,293,920 | 5.7% |
| LOAD_FAST_LOAD_FAST | 416,160 | 1.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,959,360 | 62.9% |
| SWAP | 950,880 | 30.5% |
| COPY | 192,480 | 6.2% |
| STORE_FAST | 10,320 | 0.3% |
| POP_JUMP_IF_FALSE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,958,640 | 62.9% |
| RETURN_VALUE | 950,880 | 30.5% |
| RERAISE | 192,480 | 6.2% |
| JUMP_BACKWARD | 10,800 | 0.3% |
| LOAD_CONST | 480 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 79,320,480 | 47.6% |
| RETURN_VALUE | 25,899,120 | 15.5% |
| POP_JUMP_IF_FALSE | 15,535,128 | 9.3% |
| POP_JUMP_IF_TRUE | 13,015,984 | 7.8% |
| RESUME_CHECK | 6,001,680 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,344,232 | 42.2% |
| LOAD_FAST_LOAD_FAST | 26,461,260 | 15.9% |
| JUMP_BACKWARD | 21,662,640 | 13.0% |
| RETURN_CONST | 17,265,600 | 10.4% |
| LOAD_CONST | 6,626,880 | 4.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 1,715,040 | 55.1% |
| LOAD_ATTR_SLOT | 948,000 | 30.4% |
| RERAISE | 160,080 | 5.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 154,320 | 5.0% |
| RAISE_VARARGS | 94,320 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,113,040 | 100.0% |
| LOAD_GLOBAL_MODULE | 720 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,736,480 | 50.3% |
| LOAD_ATTR | 6,315,620 | 21.5% |
| LOAD_ATTR_MODULE | 5,401,300 | 18.4% |
| BINARY_SUBSCR_DICT | 1,110,720 | 3.8% |
| LOAD_SUPER_ATTR_ATTR | 808,080 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,496,280 | 76.8% |
| LOAD_FAST_LOAD_FAST | 4,219,200 | 14.4% |
| LOAD_GLOBAL_BUILTIN | 1,836,720 | 6.3% |
| CALL | 440,520 | 1.5% |
| LOAD_CONST | 209,760 | 0.7% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,329,280 | 57.0% |
| CALL_FUNCTION_EX | 1,711,440 | 29.3% |
| COPY_FREE_VARS | 725,040 | 12.4% |
| CACHE | 70,080 | 1.2% |
| MAKE_CELL | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 3,563,280 | 61.0% |
| LOAD_FAST | 1,745,520 | 29.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 289,440 | 5.0% |
| GET_YIELD_FROM_ITER | 72,000 | 1.2% |
| INTERPRETER_EXIT | 70,080 | 1.2% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,706,060 | 30.1% |
| RETURN_VALUE | 60,511,195 | 20.3% |
| RETURN_CONST | 32,131,200 | 10.8% |
| LOAD_ATTR_SLOT | 27,348,147 | 9.2% |
| CALL | 9,479,520 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 67,764,000 | 22.7% |
| RETURN_VALUE | 60,511,195 | 20.3% |
| LOAD_FAST | 37,582,660 | 12.6% |
| INTERPRETER_EXIT | 36,944,129 | 12.4% |
| POP_TOP | 25,899,120 | 8.7% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,273,760 | 80.5% |
| LOAD_FAST | 258,480 | 9.2% |
| SWAP | 215,520 | 7.6% |
| LOAD_CONST | 59,280 | 2.1% |
| LOAD_ATTR_SLOT | 12,960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,273,760 | 80.5% |
| LOAD_CONST | 257,520 | 9.1% |
| LOAD_FAST | 180,000 | 6.4% |
| RETURN_CONST | 111,360 | 3.9% |
| STORE_SUBSCR | 940 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 7,044,460 | 46.3% |
| LOAD_FAST | 5,204,800 | 34.2% |
| LOAD_ATTR_SLOT | 2,026,320 | 13.3% |
| COPY | 809,460 | 5.3% |
| LOAD_ATTR_WITH_HINT | 53,520 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,786,260 | 84.0% |
| POP_JUMP_IF_TRUE | 2,157,960 | 14.2% |
| UNARY_NOT | 220,620 | 1.4% |
| EXTENDED_ARG | 28,080 | 0.2% |
| TO_BOOL | 24,720 | 0.2% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,440 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 760,320 | 51.9% |
| CALL_LEN | 667,920 | 45.6% |
| LOAD_GLOBAL_MODULE | 17,760 | 1.2% |
| CALL | 12,960 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 6,960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 667,680 | 45.5% |
| COMPARE_OP_INT | 667,680 | 45.5% |
| CALL_PY_EXACT_ARGS | 64,800 | 4.4% |
| RETURN_VALUE | 19,920 | 1.4% |
| BUILD_TUPLE | 17,760 | 1.2% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 17,368,800 | 87.4% |
| TO_BOOL_LIST | 1,893,840 | 9.5% |
| TO_BOOL_STR | 277,200 | 1.4% |
| TO_BOOL | 220,620 | 1.1% |
| TO_BOOL_INT | 104,160 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,516,080 | 52.9% |
| RETURN_VALUE | 6,898,080 | 34.7% |
| COPY | 1,927,440 | 9.7% |
| LOAD_FAST | 342,720 | 1.7% |
| STORE_FAST | 114,240 | 0.6% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,983,120 | 54.4% |
| LOAD_FAST | 379,440 | 10.4% |
| BUILD_LIST | 297,600 | 8.2% |
| STORE_FAST | 259,920 | 7.1% |
| LOAD_CONST | 179,040 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,424,880 | 39.1% |
| STORE_FAST | 911,760 | 25.0% |
| CALL_PY_EXACT_ARGS | 381,120 | 10.4% |
| LOAD_CONST | 215,520 | 5.9% |
| GET_ITER | 157,920 | 4.3% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 18,273,360 | 28.6% |
| STORE_FAST | 14,184,540 | 22.2% |
| LOAD_GLOBAL_MODULE | 9,092,400 | 14.2% |
| RESUME_CHECK | 6,518,160 | 10.2% |
| STORE_ATTR_SLOT | 3,159,120 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,489,660 | 38.3% |
| SWAP | 18,273,360 | 28.6% |
| CALL | 9,378,960 | 14.7% |
| LOAD_FAST | 6,086,640 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 1,903,920 | 3.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,078,960 | 36.3% |
| LOAD_CONST | 1,249,680 | 14.7% |
| STORE_ATTR_INSTANCE_VALUE | 720,720 | 8.5% |
| RESUME_CHECK | 696,960 | 8.2% |
| POP_JUMP_IF_FALSE | 597,360 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,765,200 | 56.2% |
| STORE_FAST | 1,288,320 | 15.2% |
| LOAD_CONST | 1,208,640 | 14.2% |
| SWAP | 497,280 | 5.9% |
| RETURN_VALUE | 203,520 | 2.4% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,315,680 | 93.0% |
| LOAD_CONST | 82,320 | 5.8% |
| LOAD_FAST | 16,320 | 1.2% |
| POP_JUMP_IF_FALSE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,315,680 | 93.0% |
| STORE_FAST | 48,240 | 3.4% |
| CALL_PY_EXACT_ARGS | 34,080 | 2.4% |
| BINARY_OP | 8,400 | 0.6% |
| LOAD_CONST | 8,160 | 0.6% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 12,960 | 96.4% |
| BINARY_SUBSCR | 480 | 3.6% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 999,840 | 55.3% |
| FORMAT_SIMPLE | 808,320 | 44.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 714,000 | 39.5% |
| STORE_FAST | 420,000 | 23.2% |
| RETURN_VALUE | 282,480 | 15.6% |
| LOAD_FAST | 125,520 | 6.9% |
| CALL_PY_EXACT_ARGS | 64,080 | 3.5% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,457,840 | 34.9% |
| LOAD_GLOBAL_MODULE | 3,982,560 | 16.4% |
| LOAD_ATTR_SLOT | 3,832,365 | 15.8% |
| LOAD_FAST_LOAD_FAST | 3,263,580 | 13.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,775,280 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,233,820 | 25.7% |
| CALL_BUILTIN_O | 4,252,561 | 17.6% |
| CALL_ISINSTANCE | 3,459,360 | 14.3% |
| LOAD_CONST | 3,083,040 | 12.7% |
| LOAD_FAST | 2,666,880 | 11.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,488,720 | 24.3% |
| BUILD_LIST | 9,378,960 | 18.2% |
| LOAD_FAST_LOAD_FAST | 5,210,160 | 10.1% |
| RETURN_VALUE | 4,693,920 | 9.1% |
| LOAD_ATTR_SLOT | 3,396,240 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20,395,440 | 39.7% |
| RETURN_VALUE | 9,479,520 | 18.4% |
| LIST_APPEND | 5,271,360 | 10.2% |
| RESUME_CHECK | 3,350,940 | 6.5% |
| TO_BOOL_BOOL | 2,759,520 | 5.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 2,898,000 | 48.5% |
| LOAD_FAST | 1,532,460 | 25.7% |
| MAP_ADD | 1,208,400 | 20.2% |
| LOAD_ATTR | 206,400 | 3.5% |
| CALL_INTRINSIC_1 | 108,540 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,025,200 | 50.6% |
| RETURN_GENERATOR | 1,711,440 | 28.6% |
| POP_TOP | 812,160 | 13.6% |
| STORE_FAST | 276,960 | 4.6% |
| RESUME_CHECK | 106,380 | 1.8% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 2,106,000 | 93.6% |
| LIST_EXTEND | 112,620 | 5.0% |
| RERAISE | 32,160 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 2,138,160 | 95.0% |
| CALL_FUNCTION_EX | 108,540 | 4.8% |
| BUILD_MAP | 4,080 | 0.2% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 57,378,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 32,570,160 | 56.8% |
| UNPACK_SEQUENCE_LIST | 10,636,560 | 18.5% |
| RETURN_VALUE | 4,061,760 | 7.1% |
| MAKE_CELL | 3,653,040 | 6.4% |
| CALL_PY_EXACT_ARGS | 2,814,480 | 4.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 13,695,499 | 42.4% |
| LOAD_GLOBAL_MODULE | 6,483,840 | 20.1% |
| LOAD_CONST | 5,857,021 | 18.1% |
| LOAD_ATTR_MODULE | 2,470,320 | 7.6% |
| LOAD_FAST | 1,627,680 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 12,666,584 | 39.2% |
| POP_JUMP_IF_FALSE | 10,279,061 | 31.8% |
| RETURN_VALUE | 6,307,769 | 19.5% |
| POP_JUMP_IF_TRUE | 2,100,480 | 6.5% |
| EXTENDED_ARG | 771,840 | 2.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,965,440 | 47.3% |
| LOAD_FAST_LOAD_FAST | 14,798,400 | 19.4% |
| LOAD_ATTR_INSTANCE_VALUE | 8,151,360 | 10.7% |
| LOAD_ATTR_SLOT | 4,057,440 | 5.3% |
| BINARY_SUBSCR | 3,348,480 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 61,548,000 | 80.9% |
| POP_JUMP_IF_TRUE | 11,775,372 | 15.5% |
| RETURN_VALUE | 2,139,120 | 2.8% |
| EXTENDED_ARG | 348,480 | 0.5% |
| COPY | 167,520 | 0.2% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,400 | 99.1% |
| RETURN_CONST | 480 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 50,880 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 12,666,584 | 33.2% |
| LOAD_FAST | 4,668,000 | 12.2% |
| CALL_ISINSTANCE | 3,219,360 | 8.4% |
| SWAP | 2,694,240 | 7.1% |
| COMPARE_OP_STR | 2,321,808 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 28,930,568 | 75.7% |
| COMPARE_OP_INT | 2,685,360 | 7.0% |
| TO_BOOL_NONE | 1,353,340 | 3.5% |
| TO_BOOL_STR | 1,133,760 | 3.0% |
| TO_BOOL | 809,460 | 2.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 35,664,720 | 50.5% |
| CACHE | 32,616,960 | 46.2% |
| CALL | 1,440,960 | 2.0% |
| CALL_ALLOC_AND_ENTER_INIT | 338,160 | 0.5% |
| CALL_KW | 318,240 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 69,829,740 | 99.0% |
| RETURN_GENERATOR | 725,040 | 1.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,440,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,603,120 | 78.2% |
| NOP | 1,711,440 | 20.3% |
| RETURN_CONST | 126,240 | 1.5% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 151,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 150,960 | 99.7% |
| JUMP_BACKWARD | 480 | 0.3% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,898,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 2,898,000 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,860,720 | 27.3% |
| JUMP_BACKWARD | 6,086,400 | 21.1% |
| GET_ITER | 3,557,040 | 12.4% |
| POP_TOP | 2,649,120 | 9.2% |
| LOAD_ATTR_SLOT | 941,520 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 11,210,880 | 38.9% |
| JUMP_BACKWARD | 4,945,680 | 17.2% |
| FOR_ITER | 4,750,080 | 16.5% |
| FOR_ITER_LIST | 4,608,480 | 16.0% |
| POP_JUMP_IF_NONE | 1,968,960 | 6.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 12,059,380 | 42.5% |
| GET_ITER | 10,975,680 | 38.6% |
| EXTENDED_ARG | 4,750,080 | 16.7% |
| SWAP | 545,040 | 1.9% |
| LOAD_FAST | 60,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 10,369,440 | 36.5% |
| STORE_FAST | 4,443,141 | 15.6% |
| RETURN_CONST | 4,202,400 | 14.8% |
| LOAD_FAST | 3,525,679 | 12.4% |
| LOAD_FAST_LOAD_FAST | 1,356,240 | 4.8% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 1,369,440 | 75.2% |
| STORE_FAST | 450,480 | 24.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,819,920 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,487,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 1,369,440 | 92.1% |
| STORE_FAST | 117,360 | 7.9% |
| STORE_DEREF | 240 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 31,284,000 | 72.9% |
| LOAD_CONST | 5,530,800 | 12.9% |
| LOAD_FAST | 5,262,000 | 12.3% |
| LOAD_FAST_LOAD_FAST | 667,680 | 1.6% |
| LOAD_ATTR | 71,760 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 28,605,600 | 66.7% |
| POP_JUMP_IF_TRUE | 8,796,480 | 20.5% |
| RETURN_VALUE | 3,074,640 | 7.2% |
| LOAD_FAST | 1,228,080 | 2.9% |
| COPY | 628,800 | 1.5% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 28,556,560 | 27.1% |
| LIST_APPEND | 21,982,320 | 20.8% |
| POP_TOP | 21,662,640 | 20.5% |
| CALL_LIST_APPEND | 7,108,440 | 6.7% |
| POP_JUMP_IF_FALSE | 5,114,400 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 68,988,981 | 65.4% |
| FOR_ITER | 12,059,380 | 11.4% |
| FOR_ITER_TUPLE | 9,863,943 | 9.3% |
| EXTENDED_ARG | 6,086,400 | 5.8% |
| FOR_ITER_RANGE | 4,361,040 | 4.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 271,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 271,440 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 10,513,680 | 29.5% |
| LOAD_ATTR_SLOT | 10,230,720 | 28.7% |
| LOAD_FAST | 5,016,480 | 14.1% |
| STORE_ATTR_SLOT | 4,130,400 | 11.6% |
| STORE_FAST | 2,908,320 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,736,240 | 49.8% |
| STORE_FAST | 10,936,080 | 30.7% |
| MAP_ADD | 4,706,640 | 13.2% |
| LOAD_CONST | 769,920 | 2.2% |
| LOAD_GLOBAL_MODULE | 719,040 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,651,280 | 53.0% |
| CALL | 5,271,360 | 24.0% |
| CALL_BUILTIN_O | 1,836,480 | 8.4% |
| LOAD_FAST | 1,401,360 | 6.4% |
| LOAD_ATTR_SLOT | 426,000 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 21,982,320 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 91,440 | 81.0% |
| RETURN_VALUE | 14,160 | 12.5% |
| BINARY_SLICE | 6,720 | 6.0% |
| STORE_FAST | 240 | 0.2% |
| LOAD_CONST | 240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 112,620 | 99.8% |
| LOAD_CONST | 240 | 0.2% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,725,748 | 65.2% |
| LOAD_GLOBAL_MODULE | 23,908,380 | 27.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,967,520 | 2.2% |
| LOAD_FAST_LOAD_FAST | 1,535,040 | 1.7% |
| CALL_TYPE_1 | 1,082,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,458,464 | 46.8% |
| LOAD_FAST_LOAD_FAST | 8,314,320 | 9.4% |
| TO_BOOL | 7,044,460 | 8.0% |
| PUSH_NULL | 6,315,620 | 7.1% |
| CALL_PY_EXACT_ARGS | 5,125,440 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 127,314,960 | 23.1% |
| STORE_ATTR_SLOT | 126,971,520 | 23.1% |
| LOAD_CONST | 40,620,600 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 21,607,920 | 3.9% |
| MAP_ADD | 20,542,800 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 212,095,980 | 38.5% |
| BINARY_SUBSCR_DICT | 77,595,600 | 14.1% |
| CALL_KW | 57,378,960 | 10.4% |
| LOAD_CONST | 40,620,600 | 7.4% |
| COMPARE_OP_STR | 29,935,352 | 5.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 69,111,360 | 69.6% |
| LOAD_DEREF | 9,918,960 | 10.0% |
| LOAD_FAST | 4,816,092 | 4.9% |
| LOAD_GLOBAL_MODULE | 3,840,960 | 3.9% |
| POP_JUMP_IF_FALSE | 1,986,228 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,867,600 | 67.4% |
| LOAD_DEREF | 9,918,960 | 10.0% |
| LOAD_ATTR_SLOT | 5,834,880 | 5.9% |
| LOAD_CONST | 3,451,440 | 3.5% |
| LOAD_FAST_LOAD_FAST | 2,732,160 | 2.8% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 299,541,495 | 13.1% |
| RESUME_CHECK | 229,377,670 | 10.0% |
| LOAD_CONST | 212,095,980 | 9.3% |
| STORE_FAST | 208,564,744 | 9.1% |
| POP_JUMP_IF_FALSE | 200,525,689 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 341,248,162 | 14.9% |
| STORE_ATTR_SLOT | 268,742,925 | 11.8% |
| LOAD_GLOBAL_MODULE | 208,925,772 | 9.1% |
| LOAD_ATTR_METHOD_NO_DICT | 151,442,624 | 6.6% |
| CALL_PY_EXACT_ARGS | 129,868,800 | 5.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 20,086,320 | 95.5% |
| LOAD_FAST_AND_CLEAR | 940,800 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 20,078,160 | 95.5% |
| LOAD_FAST_AND_CLEAR | 940,800 | 4.5% |
| MAKE_CELL | 8,160 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,616,880 | 76.4% |
| POP_JUMP_IF_FALSE | 229,200 | 10.8% |
| LOAD_GLOBAL_BUILTIN | 202,080 | 9.5% |
| POP_JUMP_IF_TRUE | 18,480 | 0.9% |
| LOAD_FAST_CHECK | 16,080 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 1,506,240 | 71.2% |
| LOAD_ATTR_SLOT | 133,200 | 6.3% |
| EXTENDED_ARG | 122,160 | 5.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 114,480 | 5.4% |
| TO_BOOL_BOOL | 75,120 | 3.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 106,074,480 | 24.1% |
| LOAD_SUPER_ATTR_METHOD | 53,775,840 | 12.2% |
| RESUME_CHECK | 45,426,540 | 10.3% |
| LOAD_GLOBAL_MODULE | 35,403,360 | 8.0% |
| STORE_FAST | 35,336,880 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 186,557,760 | 42.4% |
| CALL_PY_EXACT_ARGS | 77,489,760 | 17.6% |
| STORE_ATTR_INSTANCE_VALUE | 33,165,900 | 7.5% |
| LOAD_FAST | 29,799,000 | 6.8% |
| CONTAINS_OP | 14,798,400 | 3.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 28.6% |
| RETURN_VALUE | 40 | 28.6% |
| RESUME_CHECK | 20 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 20 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 57.1% |
| LOAD_GLOBAL_BUILTIN | 40 | 28.6% |
| LOAD_ATTR | 20 | 14.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 16,389,840 | 65.7% |
| CALL_PY_EXACT_ARGS | 3,727,680 | 14.9% |
| CALL_KW | 3,653,040 | 14.6% |
| BINARY_SUBSCR_GETITEM | 705,600 | 2.8% |
| CALL_PY_WITH_DEFAULTS | 439,440 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 16,389,840 | 65.7% |
| RESUME_CHECK | 8,562,480 | 34.3% |
| SWAP | 8,160 | 0.0% |
| RETURN_GENERATOR | 1,920 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 15,836,160 | 68.5% |
| JUMP_FORWARD | 4,706,640 | 20.4% |
| CALL_BUILTIN_CLASS | 1,255,920 | 5.4% |
| CALL_BUILTIN_FAST | 613,200 | 2.7% |
| LOAD_FAST_LOAD_FAST | 334,080 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,542,800 | 88.8% |
| JUMP_BACKWARD | 1,376,640 | 6.0% |
| CALL_FUNCTION_EX | 1,208,400 | 5.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 220,503,868 | 51.4% |
| CONTAINS_OP | 61,548,000 | 14.4% |
| IS_OP | 28,605,600 | 6.7% |
| COMPARE_OP_INT | 19,736,557 | 4.6% |
| TO_BOOL_ALWAYS_TRUE | 18,947,330 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200,525,689 | 46.8% |
| LOAD_GLOBAL_BUILTIN | 102,121,485 | 23.8% |
| LOAD_GLOBAL_MODULE | 37,762,800 | 8.8% |
| LOAD_FAST_LOAD_FAST | 23,475,360 | 5.5% |
| POP_TOP | 15,535,128 | 3.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,184,320 | 50.5% |
| LOAD_ATTR_SLOT | 24,543,840 | 37.4% |
| LOAD_ATTR | 3,183,600 | 4.8% |
| EXTENDED_ARG | 1,968,960 | 3.0% |
| BINARY_SUBSCR_DICT | 1,569,360 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,917,840 | 48.6% |
| RETURN_CONST | 11,897,520 | 18.1% |
| JUMP_FORWARD | 10,513,680 | 16.0% |
| LOAD_GLOBAL_BUILTIN | 3,987,120 | 6.1% |
| LOAD_CONST | 3,885,120 | 5.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,816,240 | 88.1% |
| LOAD_ATTR_SLOT | 3,667,680 | 4.8% |
| BINARY_SUBSCR_DICT | 2,963,040 | 3.9% |
| LOAD_FAST_CHECK | 1,506,240 | 2.0% |
| BINARY_SUBSCR | 223,440 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 28,576,800 | 37.7% |
| LOAD_FAST | 17,049,600 | 22.5% |
| LOAD_CONST | 10,569,840 | 13.9% |
| LOAD_FAST_LOAD_FAST | 8,051,520 | 10.6% |
| RETURN_CONST | 3,497,520 | 4.6% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 76,643,550 | 43.2% |
| TO_BOOL_LIST | 26,164,780 | 14.8% |
| COMPARE_OP_STR | 24,336,544 | 13.7% |
| CONTAINS_OP | 11,775,372 | 6.6% |
| COMPARE_OP_INT | 9,037,920 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,534,626 | 43.2% |
| JUMP_BACKWARD | 28,556,560 | 16.1% |
| LOAD_GLOBAL_MODULE | 20,575,680 | 11.6% |
| POP_TOP | 13,015,984 | 7.3% |
| NOP | 10,565,280 | 6.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 150,960 | 59.3% |
| RETURN_VALUE | 55,440 | 21.8% |
| CALL | 38,640 | 15.2% |
| LOAD_CONST | 9,120 | 3.6% |
| POP_TOP | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 150,960 | 59.3% |
| PUSH_EXC_INFO | 94,320 | 37.0% |
| COPY | 9,360 | 3.7% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 2,138,160 | 85.1% |
| POP_EXCEPT | 192,480 | 7.7% |
| DELETE_FAST | 150,960 | 6.0% |
| POP_JUMP_IF_FALSE | 32,160 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 183,120 | 48.8% |
| PUSH_EXC_INFO | 160,080 | 42.6% |
| CALL_INTRINSIC_1 | 32,160 | 8.6% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 90,707,040 | 40.3% |
| RESUME_CHECK | 50,785,440 | 22.6% |
| POP_TOP | 17,265,600 | 7.7% |
| POP_JUMP_IF_FALSE | 13,500,240 | 6.0% |
| POP_JUMP_IF_NONE | 11,897,520 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 79,320,480 | 35.2% |
| INTERPRETER_EXIT | 46,489,260 | 20.7% |
| LOAD_FAST | 46,216,320 | 20.5% |
| RETURN_VALUE | 32,131,200 | 14.3% |
| TO_BOOL_BOOL | 8,579,280 | 3.8% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 2,879,280 | 93.3% |
| LOAD_ATTR_INSTANCE_VALUE | 124,560 | 4.0% |
| STORE_FAST_LOAD_FAST | 48,000 | 1.6% |
| BINARY_SUBSCR_LIST_INT | 17,520 | 0.6% |
| LOAD_FAST | 13,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,087,360 | 100.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,081,840 | 77.8% |
| SET_FUNCTION_ATTRIBUTE | 878,640 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,312,320 | 33.1% |
| SET_FUNCTION_ATTRIBUTE | 878,640 | 22.2% |
| STORE_FAST | 766,560 | 19.4% |
| LOAD_FAST | 341,520 | 8.6% |
| LOAD_GLOBAL_MODULE | 332,160 | 8.4% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,040,640 | 75.8% |
| LOAD_FAST | 2,141,280 | 23.1% |
| SWAP | 88,560 | 1.0% |
| STORE_ATTR | 10,360 | 0.1% |
| LOAD_ATTR_SLOT | 6,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,035,360 | 43.4% |
| LOAD_FAST | 2,405,520 | 25.9% |
| RETURN_CONST | 2,380,080 | 25.6% |
| LOAD_GLOBAL_MODULE | 193,440 | 2.1% |
| LOAD_CONST | 193,440 | 2.1% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,916,480 | 81.7% |
| SET_FUNCTION_ATTRIBUTE | 318,720 | 8.9% |
| RETURN_VALUE | 120,720 | 3.4% |
| LOAD_ATTR_SLOT | 77,280 | 2.2% |
| FOR_ITER_LIST | 57,360 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,204,160 | 61.7% |
| LOAD_FAST | 867,600 | 24.3% |
| LOAD_GLOBAL_BUILTIN | 196,800 | 5.5% |
| LOAD_CONST | 141,840 | 4.0% |
| LOAD_DEREF | 132,720 | 3.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 70,292,548 | 16.8% |
| RETURN_VALUE | 67,764,000 | 16.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 40,491,840 | 9.7% |
| LOAD_ATTR_SLOT | 36,625,920 | 8.8% |
| BUILD_LIST | 24,489,660 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 208,564,744 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 58,851,920 | 14.1% |
| LOAD_GLOBAL_MODULE | 53,815,200 | 12.9% |
| LOAD_FAST_LOAD_FAST | 35,336,880 | 8.5% |
| LOAD_CONST | 15,329,280 | 3.7% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 7,446,000 | 60.6% |
| FOR_ITER_TUPLE | 3,426,720 | 27.9% |
| FOR_ITER | 986,880 | 8.0% |
| FOR_ITER_RANGE | 425,760 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,353,280 | 27.3% |
| LOAD_ATTR_SLOT | 2,842,320 | 23.1% |
| TO_BOOL_STR | 1,836,960 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,677,600 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 660,720 | 5.4% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 13,927,740 | 51.2% |
| UNPACK_SEQUENCE_LIST | 10,966,080 | 40.3% |
| UNPACK_SEQUENCE_TUPLE | 1,521,120 | 5.6% |
| COPY | 458,160 | 1.7% |
| STORE_FAST_STORE_FAST | 136,080 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,632,140 | 75.8% |
| LOAD_FAST_LOAD_FAST | 2,766,240 | 10.2% |
| STORE_FAST | 1,615,920 | 5.9% |
| LOAD_GLOBAL_BUILTIN | 1,420,800 | 5.2% |
| LOAD_GLOBAL_MODULE | 279,840 | 1.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 20,078,160 | 30.4% |
| BUILD_LIST | 18,273,360 | 27.7% |
| FOR_ITER_LIST | 13,418,400 | 20.3% |
| LOAD_FAST | 3,623,760 | 5.5% |
| CALL_LEN | 2,685,360 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 18,273,360 | 27.7% |
| FOR_ITER_LIST | 16,950,320 | 25.7% |
| STORE_FAST | 16,063,920 | 24.3% |
| COPY | 2,694,240 | 4.1% |
| POP_TOP | 2,643,600 | 4.0% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 720 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 67,920 | 67.8% |
| COPY | 19,920 | 19.9% |
| FOR_ITER_LIST | 10,560 | 10.5% |
| CALL_BUILTIN_CLASS | 960 | 1.0% |
| CALL_FUNCTION_EX | 480 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 78,240 | 78.1% |
| STORE_FAST_STORE_FAST | 21,600 | 21.6% |
| UNPACK_SEQUENCE | 260 | 0.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,961,280 | 23.3% |
| LOAD_CONST | 1,414,080 | 16.8% |
| CALL_ISINSTANCE | 945,360 | 11.2% |
| LOAD_FAST | 856,320 | 10.2% |
| LOAD_ATTR_INSTANCE_VALUE | 843,360 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,184,400 | 85.4% |
| STORE_FAST | 673,200 | 8.0% |
| UNPACK_SEQUENCE_TUPLE | 282,240 | 3.4% |
| YIELD_VALUE | 271,440 | 3.2% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 215,040 | 99.5% |
| BINARY_OP_ADD_INT | 900 | 0.4% |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 215,040 | 99.5% |
| BINARY_OP_ADD_INT | 900 | 0.4% |
| STORE_FAST | 120 | 0.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,542,640 | 58.4% |
| CALL_LEN | 1,133,760 | 18.7% |
| CALL_METHOD_DESCRIPTOR_O | 1,100,880 | 18.2% |
| LOAD_FAST | 145,920 | 2.4% |
| LOAD_FAST_LOAD_FAST | 138,720 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,479,200 | 40.9% |
| LOAD_FAST | 1,553,520 | 25.6% |
| SWAP | 743,280 | 12.3% |
| LOAD_FAST_LOAD_FAST | 605,760 | 10.0% |
| LOAD_CONST | 160,560 | 2.6% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,689,760 | 52.4% |
| LOAD_FAST | 1,158,720 | 16.5% |
| CALL_METHOD_DESCRIPTOR_O | 738,480 | 10.5% |
| LOAD_FAST_LOAD_FAST | 738,000 | 10.5% |
| BINARY_SLICE | 338,160 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_ADD | 2,879,280 | 40.9% |
| LOAD_FAST | 1,510,800 | 21.5% |
| RETURN_VALUE | 1,009,680 | 14.3% |
| STORE_FAST | 859,200 | 12.2% |
| BUILD_TUPLE | 327,360 | 4.6% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 960 | 100.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,360 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 134,520 | 61.1% |
| LOAD_FAST_LOAD_FAST | 85,440 | 38.8% |
| LOAD_ATTR_WITH_HINT | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 176,880 | 80.3% |
| LOAD_FAST_LOAD_FAST | 42,480 | 19.3% |
| LOAD_GLOBAL_BUILTIN | 480 | 0.2% |
| LOAD_FAST | 240 | 0.1% |
| BINARY_OP_ADD_FLOAT | 120 | 0.1% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,083,200 | 96.6% |
| LOAD_FAST | 92,640 | 1.8% |
| CALL_LEN | 73,920 | 1.4% |
| LOAD_FAST_LOAD_FAST | 5,760 | 0.1% |
| LOAD_ATTR_SLOT | 2,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,589,840 | 49.2% |
| CALL_BUILTIN_CLASS | 1,387,440 | 26.4% |
| BINARY_SLICE | 667,680 | 12.7% |
| SWAP | 217,680 | 4.1% |
| BINARY_SUBSCR_LIST_INT | 197,760 | 3.8% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 77,595,600 | 85.7% |
| LOAD_FAST | 7,297,200 | 8.1% |
| BINARY_SUBSCR_DICT | 2,280,480 | 2.5% |
| BINARY_SUBSCR_LIST_INT | 1,366,080 | 1.5% |
| LOAD_DEREF | 1,145,520 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,561,680 | 18.3% |
| STORE_FAST | 16,287,120 | 18.0% |
| LOAD_CONST | 15,105,360 | 16.7% |
| GET_ITER | 9,441,120 | 10.4% |
| CALL_PY_EXACT_ARGS | 7,138,560 | 7.9% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,149,840 | 55.0% |
| LOAD_FAST_LOAD_FAST | 934,320 | 44.7% |
| LOAD_CONST | 7,200 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,385,280 | 66.2% |
| MAKE_CELL | 705,600 | 33.7% |
| LOAD_ATTR_SLOT | 480 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,928,640 | 45.2% |
| LOAD_CONST | 6,512,640 | 26.9% |
| LOAD_FAST | 6,399,600 | 26.5% |
| BINARY_OP_SUBTRACT_INT | 197,760 | 0.8% |
| BINARY_OP_ADD_INT | 101,040 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,599,600 | 31.4% |
| LOAD_ATTR_INSTANCE_VALUE | 3,032,160 | 12.5% |
| STORE_FAST | 2,369,280 | 9.8% |
| LOAD_FAST | 2,193,120 | 9.1% |
| LOAD_GLOBAL_MODULE | 1,699,200 | 7.0% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 559,680 | 58.8% |
| LOAD_FAST_LOAD_FAST | 275,280 | 28.9% |
| BINARY_OP_ADD_INT | 88,320 | 9.3% |
| BINARY_OP_SUBTRACT_INT | 27,840 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 472,320 | 49.7% |
| LOAD_FAST | 264,480 | 27.8% |
| STORE_FAST | 112,560 | 11.8% |
| CALL_BUILTIN_O | 50,880 | 5.3% |
| LOAD_FAST_LOAD_FAST | 25,440 | 2.7% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,460,240 | 100.0% |
| LOAD_FAST_LOAD_FAST | 3,360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,546,880 | 30.1% |
| COMPARE_OP_STR | 2,470,800 | 29.2% |
| LOAD_ATTR_METHOD_NO_DICT | 2,364,240 | 27.9% |
| LOAD_CONST | 230,880 | 2.7% |
| STORE_FAST | 216,480 | 2.6% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,345,280 | 46.9% |
| LOAD_FAST | 1,370,160 | 27.4% |
| LOAD_GLOBAL_MODULE | 546,480 | 10.9% |
| CALL | 322,800 | 6.5% |
| RETURN_VALUE | 274,320 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,656,000 | 93.1% |
| COPY_FREE_VARS | 338,160 | 6.8% |
| CALL_PY_EXACT_ARGS | 4,800 | 0.1% |
| STORE_FAST | 1,920 | 0.0% |
| MAKE_CELL | 240 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,765,360 | 68.8% |
| BINARY_SUBSCR_DICT | 4,840,080 | 21.1% |
| LOAD_CONST | 2,020,320 | 8.8% |
| CALL_PY_EXACT_ARGS | 79,680 | 0.3% |
| RETURN_VALUE | 70,080 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 20,822,300 | 90.9% |
| POP_TOP | 1,969,920 | 8.6% |
| CALL_PY_EXACT_ARGS | 79,700 | 0.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 37,660 | 0.2% |
| COPY_FREE_VARS | 240 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,928,520 | 29.7% |
| LOAD_GLOBAL_BUILTIN | 5,364,000 | 17.8% |
| LOAD_ATTR_SLOT | 3,370,906 | 11.2% |
| LOAD_ATTR_CLASS | 2,841,840 | 9.5% |
| CALL_LEN | 2,305,440 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,308,140 | 47.6% |
| LOAD_FAST | 7,887,840 | 26.2% |
| STORE_FAST | 2,822,160 | 9.4% |
| RETURN_VALUE | 1,873,200 | 6.2% |
| MAP_ADD | 1,255,920 | 4.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,451,840 | 47.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,532,080 | 30.4% |
| LOAD_FAST_LOAD_FAST | 1,979,040 | 17.1% |
| LOAD_FAST | 498,720 | 4.3% |
| LOAD_GLOBAL_BUILTIN | 67,920 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,560,080 | 22.1% |
| STORE_FAST | 2,172,240 | 18.7% |
| RETURN_VALUE | 1,744,320 | 15.0% |
| PUSH_EXC_INFO | 1,715,040 | 14.8% |
| TO_BOOL_BOOL | 1,560,000 | 13.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,418,000 | 84.8% |
| RETURN_GENERATOR | 289,440 | 10.2% |
| CALL_BUILTIN_CLASS | 106,320 | 3.7% |
| RETURN_VALUE | 36,000 | 1.3% |
| LOAD_CONST | 520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,968,720 | 69.0% |
| COPY | 251,520 | 8.8% |
| LOAD_CONST | 228,240 | 8.0% |
| PUSH_EXC_INFO | 154,320 | 5.4% |
| RETURN_VALUE | 108,000 | 3.8% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 4,252,561 | 31.4% |
| RETURN_GENERATOR | 3,563,280 | 26.3% |
| CALL_STR_1 | 1,836,480 | 13.6% |
| LOAD_FAST | 1,587,600 | 11.7% |
| LOAD_GLOBAL_MODULE | 901,236 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,230,582 | 38.6% |
| LOAD_FAST | 3,717,405 | 27.4% |
| LIST_APPEND | 1,836,480 | 13.6% |
| TO_BOOL_BOOL | 1,276,560 | 9.4% |
| CALL_PY_EXACT_ARGS | 678,480 | 5.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 182,094,012 | 83.1% |
| LOAD_GLOBAL_BUILTIN | 31,128,480 | 14.2% |
| BUILD_TUPLE | 3,459,360 | 1.6% |
| LOAD_ATTR | 1,421,520 | 0.6% |
| LOAD_ATTR_MODULE | 772,800 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 214,015,250 | 97.7% |
| COPY | 3,219,360 | 1.5% |
| YIELD_VALUE | 945,360 | 0.4% |
| RETURN_VALUE | 557,962 | 0.3% |
| STORE_FAST | 297,120 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,593,040 | 57.5% |
| LOAD_ATTR_SLOT | 8,321,520 | 30.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,426,800 | 5.3% |
| LOAD_DEREF | 1,425,600 | 5.3% |
| LOAD_ATTR | 163,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,379,280 | 27.2% |
| COMPARE_OP_INT | 4,586,640 | 16.9% |
| LOAD_GLOBAL_BUILTIN | 3,426,000 | 12.6% |
| SWAP | 2,685,360 | 9.9% |
| CALL_BUILTIN_CLASS | 2,305,440 | 8.5% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,788,840 | 82.1% |
| RETURN_VALUE | 1,977,360 | 8.2% |
| LOAD_CONST | 426,000 | 1.8% |
| BUILD_TUPLE | 415,920 | 1.7% |
| BUILD_LIST | 366,240 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,146,000 | 54.5% |
| JUMP_BACKWARD | 7,108,440 | 29.5% |
| NOP | 1,826,400 | 7.6% |
| EXTENDED_ARG | 512,400 | 2.1% |
| LOAD_CONST | 510,780 | 2.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,860,720 | 55.8% |
| LOAD_ATTR_METHOD_NO_DICT | 17,719,200 | 34.2% |
| LOAD_CONST | 2,195,040 | 4.2% |
| LOAD_GLOBAL_MODULE | 1,039,680 | 2.0% |
| CALL_BUILTIN_CLASS | 549,600 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40,491,840 | 78.2% |
| POP_TOP | 3,562,320 | 6.9% |
| LOAD_CONST | 2,832,480 | 5.5% |
| LOAD_FAST | 2,100,000 | 4.1% |
| CALL_PY_EXACT_ARGS | 729,840 | 1.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,225,040 | 90.7% |
| LOAD_FAST | 140,640 | 5.7% |
| LOAD_ATTR_MODULE | 69,360 | 2.8% |
| LOAD_ATTR_METHOD_NO_DICT | 19,440 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,712,160 | 69.8% |
| LOAD_CONST | 292,080 | 11.9% |
| UNPACK_SEQUENCE_LIST | 145,680 | 5.9% |
| GET_ITER | 141,360 | 5.8% |
| CONTAINS_OP | 69,360 | 2.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,277,120 | 99.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,700 | 0.2% |
| LOAD_ATTR | 4,320 | 0.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,301,520 | 56.9% |
| LOAD_FAST | 431,280 | 18.9% |
| POP_TOP | 240,720 | 10.5% |
| CALL_BUILTIN_CLASS | 180,000 | 7.9% |
| LOAD_ATTR_METHOD_NO_DICT | 67,200 | 2.9% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,887,600 | 53.6% |
| LOAD_FAST | 2,990,880 | 32.8% |
| RETURN_VALUE | 474,240 | 5.2% |
| LOAD_ATTR_SLOT | 193,200 | 2.1% |
| BUILD_TUPLE | 182,400 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,808,320 | 41.8% |
| POP_TOP | 3,259,440 | 35.7% |
| BINARY_OP_ADD_INT | 1,100,880 | 12.1% |
| BINARY_OP_ADD_UNICODE | 738,480 | 8.1% |
| STORE_FAST | 149,280 | 1.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 129,868,800 | 38.7% |
| LOAD_FAST_LOAD_FAST | 77,489,760 | 23.1% |
| LOAD_ATTR_METHOD_NO_DICT | 55,922,464 | 16.7% |
| LOAD_ATTR_SLOT | 10,990,160 | 3.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,697,120 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 291,871,836 | 87.0% |
| COPY_FREE_VARS | 35,664,720 | 10.6% |
| MAKE_CELL | 3,727,680 | 1.1% |
| RETURN_GENERATOR | 3,329,280 | 1.0% |
| CALL_PY_EXACT_ARGS | 547,947 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 5,951,040 | 38.3% |
| LOAD_FAST | 5,229,120 | 33.6% |
| LOAD_FAST_LOAD_FAST | 1,399,680 | 9.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 946,560 | 6.1% |
| LOAD_ATTR_SLOT | 484,560 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,923,680 | 96.0% |
| MAKE_CELL | 439,440 | 2.8% |
| COPY_FREE_VARS | 175,440 | 1.1% |
| CALL_PY_EXACT_ARGS | 6,000 | 0.0% |
| RETURN_GENERATOR | 720 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,614,080 | 100.0% |
| UNARY_NOT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 1,836,480 | 70.2% |
| LOAD_FAST | 737,760 | 28.2% |
| STORE_FAST | 28,560 | 1.1% |
| CALL | 11,280 | 0.4% |
| BUILD_TUPLE | 240 | 0.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,113,680 | 92.5% |
| LOAD_ATTR_SLOT | 1,098,676 | 7.2% |
| RETURN_VALUE | 16,800 | 0.1% |
| LOAD_FAST_CHECK | 14,640 | 0.1% |
| RETURN_GENERATOR | 5,760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,220,000 | 93.2% |
| LOAD_GLOBAL_BUILTIN | 571,920 | 3.8% |
| BUILD_TUPLE | 398,356 | 2.6% |
| CALL_PY_EXACT_ARGS | 25,200 | 0.2% |
| RETURN_VALUE | 18,000 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,694,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,212,320 | 60.0% |
| STORE_FAST | 1,470,480 | 16.9% |
| LOAD_ATTR | 1,082,880 | 12.5% |
| PUSH_NULL | 667,680 | 7.7% |
| LOAD_GLOBAL_MODULE | 134,160 | 1.5% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,560 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,875,057 | 43.2% |
| CALL_LEN | 4,586,640 | 14.3% |
| LOAD_GLOBAL_MODULE | 2,733,120 | 8.5% |
| COPY | 2,685,360 | 8.4% |
| LOAD_ATTR_CLASS | 2,666,400 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,736,557 | 61.5% |
| POP_JUMP_IF_TRUE | 9,037,920 | 28.2% |
| COPY | 1,579,504 | 4.9% |
| RETURN_VALUE | 956,344 | 3.0% |
| EXTENDED_ARG | 470,400 | 1.5% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,935,352 | 71.9% |
| LOAD_FAST | 6,798,064 | 16.3% |
| BINARY_SUBSCR_TUPLE_INT | 2,470,800 | 5.9% |
| RETURN_VALUE | 718,500 | 1.7% |
| LOAD_ATTR_INSTANCE_VALUE | 625,588 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 24,336,544 | 58.4% |
| POP_JUMP_IF_FALSE | 13,412,980 | 32.2% |
| COPY | 2,321,808 | 5.6% |
| RETURN_VALUE | 923,179 | 2.2% |
| EXTENDED_ARG | 582,000 | 1.4% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 923,280 | 92.7% |
| GET_ITER | 72,720 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 923,280 | 92.7% |
| POP_TOP | 72,720 | 7.3% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 68,988,981 | 53.7% |
| GET_ITER | 34,084,830 | 26.5% |
| SWAP | 16,950,320 | 13.2% |
| EXTENDED_ARG | 4,608,480 | 3.6% |
| LOAD_FAST | 3,873,540 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 70,292,548 | 54.7% |
| LOAD_FAST | 20,321,171 | 15.8% |
| SWAP | 13,418,400 | 10.4% |
| RETURN_CONST | 10,877,072 | 8.5% |
| STORE_FAST_LOAD_FAST | 7,446,000 | 5.8% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,479,900 | 46.2% |
| JUMP_BACKWARD | 4,361,040 | 45.0% |
| SWAP | 620,160 | 6.4% |
| EXTENDED_ARG | 233,040 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,592,880 | 47.4% |
| RETURN_CONST | 2,099,280 | 21.7% |
| LOAD_FAST | 1,652,220 | 17.0% |
| LOAD_GLOBAL_MODULE | 619,440 | 6.4% |
| STORE_FAST_LOAD_FAST | 425,760 | 4.4% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,530,322 | 54.9% |
| JUMP_BACKWARD | 9,863,943 | 37.3% |
| SWAP | 1,970,800 | 7.4% |
| EXTENDED_ARG | 51,840 | 0.2% |
| FOR_ITER_LIST | 26,974 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,141,950 | 49.7% |
| STORE_FAST | 6,478,935 | 24.5% |
| STORE_FAST_LOAD_FAST | 3,426,720 | 13.0% |
| SWAP | 1,952,400 | 7.4% |
| LOAD_FAST_LOAD_FAST | 808,320 | 3.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,933,120 | 88.9% |
| LOAD_FAST | 1,158,240 | 10.4% |
| COPY | 79,200 | 0.7% |
| LOAD_ATTR_CLASS | 5,180 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,841,840 | 25.4% |
| COMPARE_OP_INT | 2,666,400 | 23.9% |
| LOAD_ATTR_METHOD_NO_DICT | 2,028,240 | 18.1% |
| CALL | 1,925,520 | 17.2% |
| LOAD_ATTR_MODULE | 1,158,240 | 10.4% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,956,776 | 78.5% |
| LOAD_FAST_LOAD_FAST | 12,207,840 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,472,460 | 3.6% |
| LOAD_GLOBAL_MODULE | 3,131,760 | 2.5% |
| BINARY_SUBSCR_LIST_INT | 3,032,160 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,992,548 | 20.0% |
| LOAD_CONST | 21,607,920 | 17.3% |
| LOAD_ATTR_METHOD_NO_DICT | 11,213,040 | 9.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,946,320 | 8.0% |
| CONTAINS_OP | 8,151,360 | 6.5% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,480 | 99.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 240 | 1.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 151,442,624 | 72.9% |
| LOAD_ATTR_SLOT | 22,902,752 | 11.0% |
| LOAD_ATTR_INSTANCE_VALUE | 11,213,040 | 5.4% |
| LOAD_GLOBAL_MODULE | 8,676,720 | 4.2% |
| LOAD_ATTR_WITH_HINT | 2,720,640 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,837,960 | 45.2% |
| CALL_PY_EXACT_ARGS | 55,922,464 | 26.9% |
| LOAD_CONST | 19,665,392 | 9.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 17,719,200 | 8.5% |
| LOAD_GLOBAL_MODULE | 14,253,160 | 6.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,530,240 | 82.1% |
| LOAD_ATTR_INSTANCE_VALUE | 9,946,320 | 11.4% |
| LOAD_DEREF | 1,984,320 | 2.3% |
| LOAD_ATTR_WITH_HINT | 1,020,000 | 1.2% |
| LOAD_FAST_LOAD_FAST | 1,019,760 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,926,080 | 69.9% |
| LOAD_FAST_LOAD_FAST | 12,052,800 | 13.8% |
| CALL_PY_EXACT_ARGS | 8,697,120 | 10.0% |
| LOAD_CONST | 2,031,360 | 2.3% |
| LOAD_DEREF | 1,595,280 | 1.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 15,074,260 | 69.0% |
| LOAD_ATTR_MODULE | 4,548,720 | 20.8% |
| LOAD_ATTR_CLASS | 1,158,240 | 5.3% |
| LOAD_FAST_LOAD_FAST | 926,400 | 4.2% |
| LOAD_FAST | 151,920 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 5,401,300 | 24.7% |
| LOAD_ATTR_MODULE | 4,548,720 | 20.8% |
| LOAD_FAST | 3,214,800 | 14.7% |
| COMPARE_OP | 2,470,320 | 11.3% |
| LOAD_GLOBAL_MODULE | 1,217,280 | 5.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 802,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 737,760 | 92.0% |
| LOAD_FAST | 32,400 | 4.0% |
| IS_OP | 32,160 | 4.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 516,960 | 60.4% |
| LOAD_FAST | 302,400 | 35.3% |
| STORE_FAST_LOAD_FAST | 33,600 | 3.9% |
| LOAD_FAST_LOAD_FAST | 2,640 | 0.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 538,800 | 63.0% |
| CALL_LEN | 103,440 | 12.1% |
| RETURN_VALUE | 78,960 | 9.2% |
| LOAD_FAST | 71,760 | 8.4% |
| TO_BOOL_BOOL | 34,560 | 4.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,793,175 | 72.1% |
| LOAD_ATTR_SLOT | 5,095,258 | 24.8% |
| LOAD_ATTR_INSTANCE_VALUE | 362,160 | 1.8% |
| CALL | 70,080 | 0.3% |
| BINARY_SUBSCR | 63,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 19,154,679 | 93.4% |
| RETURN_VALUE | 807,316 | 3.9% |
| STORE_FAST | 181,200 | 0.9% |
| LOAD_FAST | 180,220 | 0.9% |
| LOAD_CONST | 80,000 | 0.4% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 341,248,162 | 88.6% |
| LOAD_ATTR_SLOT | 26,046,325 | 6.8% |
| LOAD_DEREF | 5,834,880 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,317,440 | 1.4% |
| STORE_FAST_LOAD_FAST | 2,842,320 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,234,420 | 11.7% |
| STORE_FAST | 36,625,920 | 9.5% |
| GET_ITER | 35,968,112 | 9.3% |
| RETURN_VALUE | 27,348,147 | 7.1% |
| LOAD_ATTR_SLOT | 26,046,325 | 6.8% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,293,120 | 57.2% |
| LOAD_FAST_LOAD_FAST | 4,846,800 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,727,280 | 20.3% |
| LOAD_ATTR_WITH_HINT | 376,860 | 1.6% |
| LOAD_DEREF | 8,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,265,280 | 31.2% |
| TO_BOOL_BOOL | 2,745,840 | 11.8% |
| LOAD_ATTR_METHOD_NO_DICT | 2,720,640 | 11.7% |
| COPY | 2,092,320 | 9.0% |
| LOAD_FAST | 1,864,560 | 8.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 131,619,154 | 30.5% |
| POP_JUMP_IF_FALSE | 102,121,485 | 23.7% |
| STORE_FAST | 58,851,920 | 13.6% |
| LOAD_FAST | 34,554,960 | 8.0% |
| POP_JUMP_IF_NOT_NONE | 28,576,800 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 299,541,495 | 69.4% |
| LOAD_DEREF | 69,111,360 | 16.0% |
| CALL_ISINSTANCE | 31,128,480 | 7.2% |
| LOAD_FAST_LOAD_FAST | 5,903,520 | 1.4% |
| CALL_BUILTIN_CLASS | 5,364,000 | 1.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 208,925,772 | 43.4% |
| STORE_FAST | 53,815,200 | 11.2% |
| RESUME_CHECK | 40,190,680 | 8.3% |
| POP_JUMP_IF_FALSE | 37,762,800 | 7.8% |
| LOAD_GLOBAL_MODULE | 25,668,000 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 182,094,012 | 37.8% |
| LOAD_FAST | 96,565,980 | 20.1% |
| LOAD_FAST_LOAD_FAST | 35,403,360 | 7.4% |
| IS_OP | 31,284,000 | 6.5% |
| LOAD_GLOBAL_MODULE | 25,668,000 | 5.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 812,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 808,080 | 99.5% |
| STORE_FAST | 4,320 | 0.5% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,576,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 53,775,840 | 83.3% |
| CALL_PY_WITH_DEFAULTS | 5,951,040 | 9.2% |
| CALL_PY_EXACT_ARGS | 2,446,800 | 3.8% |
| LOAD_FAST | 1,556,880 | 2.4% |
| LOAD_GLOBAL_MODULE | 516,960 | 0.8% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 291,871,836 | 55.4% |
| COPY_FREE_VARS | 69,829,740 | 13.3% |
| CACHE | 52,313,309 | 9.9% |
| CALL_KW | 32,570,160 | 6.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 20,822,300 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229,377,670 | 43.5% |
| LOAD_GLOBAL_BUILTIN | 131,619,154 | 25.0% |
| RETURN_CONST | 50,785,440 | 9.6% |
| LOAD_FAST_LOAD_FAST | 45,426,540 | 8.6% |
| LOAD_GLOBAL_MODULE | 40,190,680 | 7.6% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 271,440 | 79.0% |
| LOAD_CONST | 72,000 | 21.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 271,440 | 79.0% |
| POP_TOP | 72,000 | 21.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 33,165,900 | 56.7% |
| LOAD_FAST | 24,383,580 | 41.7% |
| SWAP | 595,920 | 1.0% |
| BINARY_SUBSCR | 337,200 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 24,340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 27,463,920 | 46.9% |
| RETURN_CONST | 10,268,220 | 17.6% |
| LOAD_FAST | 9,754,560 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 3,851,520 | 6.6% |
| LOAD_GLOBAL_MODULE | 2,751,840 | 4.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 268,742,925 | 58.7% |
| LOAD_FAST_LOAD_FAST | 186,557,760 | 40.7% |
| STORE_ATTR_SLOT | 1,863,131 | 0.4% |
| LOAD_ATTR_SLOT | 636,960 | 0.1% |
| LOAD_DEREF | 11,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 126,971,520 | 27.7% |
| LOAD_FAST_LOAD_FAST | 106,074,480 | 23.2% |
| RETURN_CONST | 90,707,040 | 19.8% |
| LOAD_FAST | 83,717,085 | 18.3% |
| LOAD_GLOBAL_BUILTIN | 23,764,560 | 5.2% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 708,000 | 57.4% |
| LOAD_FAST_LOAD_FAST | 523,200 | 42.4% |
| SWAP | 720 | 0.1% |
| STORE_ATTR_WITH_HINT | 600 | 0.0% |
| LOAD_DEREF | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 384,240 | 31.2% |
| LOAD_GLOBAL_MODULE | 336,480 | 27.3% |
| RETURN_CONST | 258,480 | 21.0% |
| LOAD_FAST | 192,960 | 15.6% |
| LOAD_GLOBAL_BUILTIN | 59,040 | 4.8% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,804,400 | 71.1% |
| LOAD_FAST_LOAD_FAST | 483,600 | 12.3% |
| LOAD_ATTR_SLOT | 307,920 | 7.8% |
| SWAP | 276,000 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 35,520 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,873,200 | 47.5% |
| JUMP_BACKWARD | 1,146,480 | 29.1% |
| LOAD_FAST | 754,800 | 19.1% |
| LOAD_GLOBAL_BUILTIN | 71,520 | 1.8% |
| LOAD_FAST_LOAD_FAST | 49,440 | 1.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 323,280 | 99.7% |
| LOAD_FAST | 960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 322,800 | 99.6% |
| LOAD_FAST | 960 | 0.3% |
| EXTENDED_ARG | 480 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,631,843 | 75.8% |
| LOAD_ATTR_SLOT | 4,321,180 | 19.7% |
| LOAD_ATTR_INSTANCE_VALUE | 416,520 | 1.9% |
| COPY | 176,420 | 0.8% |
| LOAD_ATTR | 170,160 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,947,330 | 86.3% |
| POP_JUMP_IF_TRUE | 2,192,740 | 10.0% |
| EXTENDED_ARG | 748,900 | 3.4% |
| TO_BOOL_NONE | 28,365 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 25,643 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 214,015,250 | 66.4% |
| COPY | 28,930,568 | 9.0% |
| LOAD_FAST | 25,710,240 | 8.0% |
| RETURN_VALUE | 19,091,620 | 5.9% |
| LOAD_ATTR_SLOT | 9,038,780 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 220,503,868 | 68.4% |
| POP_JUMP_IF_TRUE | 76,643,550 | 23.8% |
| UNARY_NOT | 17,368,800 | 5.4% |
| EXTENDED_ARG | 7,860,720 | 2.4% |
| TO_BOOL_STR | 480 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 992,880 | 65.3% |
| LOAD_ATTR_INSTANCE_VALUE | 267,120 | 17.6% |
| RETURN_VALUE | 111,360 | 7.3% |
| LOAD_ATTR_SLOT | 104,160 | 6.8% |
| BINARY_OP | 36,960 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,014,480 | 66.7% |
| POP_JUMP_IF_TRUE | 400,800 | 26.4% |
| UNARY_NOT | 104,160 | 6.8% |
| TO_BOOL_STR | 960 | 0.1% |
| TO_BOOL_BOOL | 240 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,335,680 | 75.6% |
| LOAD_ATTR_SLOT | 5,049,000 | 14.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,975,920 | 5.7% |
| COPY | 666,300 | 1.9% |
| BINARY_SUBSCR_LIST_INT | 294,960 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 26,164,780 | 75.1% |
| POP_JUMP_IF_FALSE | 6,172,680 | 17.7% |
| UNARY_NOT | 1,893,840 | 5.4% |
| EXTENDED_ARG | 593,280 | 1.7% |
| TO_BOOL | 3,240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,264,597 | 57.5% |
| LOAD_ATTR_SLOT | 8,362,400 | 31.5% |
| COPY | 1,353,340 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 436,440 | 1.6% |
| LOAD_ATTR_MODULE | 389,280 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,247,950 | 65.0% |
| POP_JUMP_IF_TRUE | 8,676,280 | 32.7% |
| EXTENDED_ARG | 578,300 | 2.2% |
| TO_BOOL_ALWAYS_TRUE | 28,412 | 0.1% |
| UNARY_NOT | 5,700 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,996,680 | 57.7% |
| STORE_FAST_LOAD_FAST | 1,836,960 | 21.2% |
| COPY | 1,133,760 | 13.1% |
| LOAD_ATTR_SLOT | 327,420 | 3.8% |
| LOAD_ATTR_INSTANCE_VALUE | 270,000 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,289,520 | 49.6% |
| POP_JUMP_IF_FALSE | 4,083,540 | 47.2% |
| UNARY_NOT | 277,200 | 3.2% |
| TO_BOOL_NONE | 3,740 | 0.0% |
| TO_BOOL_INT | 1,200 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_KW | 10,636,560 | 97.0% |
| RETURN_VALUE | 174,720 | 1.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 145,680 | 1.3% |
| LOAD_FAST | 12,000 | 0.1% |
| LOAD_ATTR_SLOT | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 10,966,080 | 100.0% |
| STORE_FAST | 4,320 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 583,680 | 35.3% |
| YIELD_VALUE | 282,240 | 17.1% |
| STORE_FAST | 280,320 | 17.0% |
| FOR_ITER | 182,400 | 11.0% |
| FOR_ITER_LIST | 176,400 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,521,120 | 92.0% |
| STORE_FAST | 131,760 | 8.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 10,369,440 | 70.0% |
| FOR_ITER_LIST | 2,589,120 | 17.5% |
| RETURN_VALUE | 1,103,320 | 7.4% |
| STORE_FAST | 278,640 | 1.9% |
| RETURN_CONST | 217,920 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 13,927,740 | 94.0% |
| STORE_FAST | 863,280 | 5.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 22,560 | 0.2% |


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
| specialization.deferred |     30601680 | 19.5% |
|          hit |    126264240 | 80.5% |
|         miss |          480 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 10,760 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 5,540 | 51.5% |
| other | 3,760 | 34.9% |
| code complex parameters | 1,340 | 12.5% |
| buffer int | 80 | 0.7% |
| tuple slice | 40 | 0.4% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2822880 | 39.8% |
|          hit |      4268640 | 60.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 940 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 820 | 87.2% |
| out of range | 120 | 12.8% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     15192920 | 3.5% |
| specialization.deopt |       104640 | 0.0% |
|          hit |    410320033 | 95.2% |
|         miss |      5553025 | 1.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 104,640 | 76.0% |
| Failure | 33,120 | 24.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 14,540 | 43.9% |
| tuple | 11,620 | 35.1% |
| dict | 3,360 | 10.1% |
| other | 1,780 | 5.4% |
| mapping | 1,140 | 3.4% |
| set | 680 | 2.1% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3642960 | 15.9% |
| specialization.deopt |         1800 | 0.0% |
|          hit |     19139460 | 83.6% |
|         miss |        95460 | 0.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,800 | 29.1% |
| Failure | 4,380 | 70.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 1,760 | 40.2% |
| multiply different types | 1,080 | 24.7% |
| remainder | 480 | 11.0% |
| or | 480 | 11.0% |
| subtract other | 360 | 8.2% |
| and int | 80 | 1.8% |
| true divide different types | 40 | 0.9% |
| subtract different types | 40 | 0.9% |
| and other | 40 | 0.9% |
| and different types | 20 | 0.5% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     51390960 | 5.9% |
| specialization.deopt |       863607 | 0.1% |
|          hit |    774556727 | 88.8% |
|         miss |     45857957 | 5.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 863,667 | 95.9% |
| Failure | 37,300 | 4.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| no dict | 14,420 | 38.7% |
| code complex parameters | 8,580 | 23.0% |
| meth descr varargs | 3,400 | 9.1% |
| class no vectorcall | 2,880 | 7.7% |
| class mutable | 2,180 | 5.8% |
| cfunc noargs | 1,840 | 4.9% |
| cfunc varargs keywords | 1,080 | 2.9% |
| meth descr varargs keywords | 640 | 1.7% |
| wrong number arguments | 420 | 1.1% |
| other | 400 | 1.1% |
| init not simple | 380 | 1.0% |
| meth descr method fastcall keywords | 320 | 0.9% |
| cfunc varargs | 300 | 0.8% |
| bound method | 240 | 0.6% |
| init not python | 100 | 0.3% |
| cmethod | 80 | 0.2% |
| operator wrapper | 40 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     32251494 | 30.4% |
| specialization.deopt |        12471 | 0.0% |
|          hit |     73085788 | 68.9% |
|         miss |       660239 | 0.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,431 | 19.9% |
| Failure | 50,154 | 80.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 35,729 | 71.2% |
| baseobject | 4,820 | 9.6% |
| different types | 3,320 | 6.6% |
| bool | 2,105 | 4.2% |
| other | 2,040 | 4.1% |
| tuple | 1,340 | 2.7% |
| list | 660 | 1.3% |
| set | 80 | 0.2% |
| string | 60 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     28390180 | 14.6% |
| specialization.deopt |        57026 | 0.0% |
|          hit |    162662041 | 83.8% |
|         miss |      3020961 | 1.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 57,026 | 80.2% |
| Failure | 14,102 | 19.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 4,422 | 31.4% |
| enumerate | 2,980 | 21.1% |
| reversed list | 2,000 | 14.2% |
| dict items | 1,820 | 12.9% |
| zip | 1,640 | 11.6% |
| dict keys | 620 | 4.4% |
| dict values | 280 | 2.0% |
| itertools | 180 | 1.3% |
| map | 120 | 0.9% |
| other | 40 | 0.3% |


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
| specialization.deferred |     88421508 | 9.1% |
| specialization.deopt |      1260319 | 0.1% |
|          hit |    816451105 | 84.0% |
|         miss |     66873875 | 6.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,260,399 | 94.0% |
| Failure | 80,240 | 6.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 44,940 | 56.0% |
| not managed dict | 9,720 | 12.1% |
| shadowed | 9,020 | 11.2% |
| metaclass attribute | 5,000 | 6.2% |
| class method obj | 3,840 | 4.8% |
| non overriding descriptor | 3,020 | 3.8% |
| method | 1,700 | 2.1% |
| class attr simple | 1,080 | 1.3% |
| module attr not found | 880 | 1.1% |
| non object slot | 680 | 0.8% |
| builtin class method | 160 | 0.2% |
| class attr descriptor | 120 | 0.1% |
| mutable class | 80 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
| specialization.deopt |           20 | 0.0% |
|          hit |    912878051 | 100.0% |
|         miss |           40 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     65388960 | 100.0% |


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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       343440 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      9278640 | 1.8% |
| specialization.deopt |      1888191 | 0.4% |
|          hit |    417476527 | 79.2% |
|         miss |    100077029 | 19.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,888,191 | 99.4% |
| Failure | 10,480 | 0.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 5,240 | 50.0% |
| not in dict | 4,640 | 44.3% |
| overridden | 260 | 2.5% |
| non object slot | 180 | 1.7% |
| not in keys | 160 | 1.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        99840 | 0.4% |
|          hit |     27436860 | 99.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 7.1% |
| Failure | 260 | 92.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 140 | 53.8% |
| iterator | 120 | 46.2% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 5,481,089,094 | 49.2% |
| Not specialized | 1,342,270,456 | 12.0% |
| Specialized | 4,316,202,036 | 38.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,032,280 | 100.0% |
| LOAD_ATTR | 88,421,508 | 0.0% |
| CALL | 51,390,960 | 0.0% |
| COMPARE_OP | 32,251,494 | 0.0% |
| BINARY_SUBSCR | 30,601,680 | 0.0% |
| FOR_ITER | 28,390,180 | 0.0% |
| TO_BOOL | 15,192,920 | 0.0% |
| STORE_ATTR | 9,278,640 | 0.0% |
| BINARY_OP | 3,642,960 | 0.0% |
| STORE_SUBSCR | 2,822,880 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_SLOT | 98,746,229 | 44.5% |
| LOAD_ATTR_METHOD_NO_DICT | 43,505,561 | 19.6% |
| CALL_PY_EXACT_ARGS | 33,905,457 | 15.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,056,098 | 5.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,232,000 | 2.8% |
| LOAD_ATTR_SLOT | 5,808,042 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 4,364,320 | 2.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,145,000 | 1.9% |
| TO_BOOL_ALWAYS_TRUE | 2,912,655 | 1.3% |
| TO_BOOL_NONE | 2,019,990 | 0.9% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 92,832,269 | 17.4% |
| Calls to Python functions inlined | 441,973,995 | 82.6% |
| Calls via PyEval_EvalFrame (total) | 92,832,269 | 17.4% |
| Calls via PyEval_EvalFrame (vector) | 79,921,949 | 14.9% |
| Calls via PyEval_EvalFrame (generator) | 12,910,320 | 2.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 79,921,949 | 14.9% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 10,421,052 | 1.9% |
| Calls via PyEval_EvalFrame (function ex) | 1,856,280 | 0.3% |
| Calls via PyEval_EvalFrame (api) | 17,747,717 | 3.3% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 525,550,904 | 98.3% |
| Frame objects created | 6,893,580 | 1.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 230,540,763 | 28.3% |
| Frees to freelist | 230,534,861 |  |
| Allocations | 584,421,301 | 71.7% |
| Allocations to 512 bytes | 583,641,282 | 71.6% |
| Allocations to 4 kbytes | 541,639 | 0.1% |
| Allocations over 4 kbytes | 238,380 | 0.0% |
| Frees | 597,624,051 |  |
| New values | 6,648,780 |  |
| Interpreter increfs | 5,478,471,838 | 74.8% |
| Interpreter decrefs | 5,951,124,530 | 74.4% |
| Increfs | 1,846,307,861 | 25.2% |
| Decrefs | 2,050,269,459 | 25.6% |
| Materialize dict (on request) | 480 | 0.0% |
| Materialize dict (new key) | 1,720 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 280 | 0.0% |
| Method cache hits | 318,426,738 |  |
| Method cache misses | 5,471,134 |  |
| Method cache collisions | 6,532,591 |  |
| Method cache dunder hits | 267,424,963 |  |
| Method cache dunder misses | 1,066,751 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 280 | 312,800 | 670,432,440 |
| 1 | 20 | 28,138,360 | 523,882,640 |
| 2 | 0 | 0 | 0 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-24
