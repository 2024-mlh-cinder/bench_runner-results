
# Pystats results

- benchmark: all
- fork: faster-cpython
- ref: optimize-globals-to-constants
- commit hash: 3a5aea4
- commit date: 2023-11-16T19:32:28+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 31,315,370,022 | 19.0% | 19.0% |  |
| STORE_FAST | 8,654,001,040 | 5.2% | 24.2% |  |
| LOAD_CONST | 8,410,294,417 | 5.1% | 29.3% |  |
| POP_JUMP_IF_FALSE | 8,182,008,125 | 5.0% | 34.2% |  |
| LOAD_FAST_LOAD_FAST | 7,226,088,447 | 4.4% | 38.6% |  |
| RESUME_CHECK | 7,161,710,865 | 4.3% | 43.0% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 5,107,873,137 | 3.1% | 46.0% | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 4,803,049,610 | 2.9% | 49.0% | 5.4% |
| TO_BOOL_BOOL | 4,405,102,250 | 2.7% | 51.6% | 0.0% |
| RETURN_VALUE | 4,402,647,317 | 2.7% | 54.3% |  |
| LOAD_GLOBAL_MODULE | 3,903,831,545 | 2.4% | 56.6% | 0.0% |
| POP_TOP | 3,623,230,103 | 2.2% | 58.8% |  |
| CALL_PY_EXACT_ARGS | 3,369,486,107 | 2.0% | 60.9% | 3.7% |
| ENTER_EXECUTOR | 2,438,689,513 | 1.5% | 62.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,172,730,785 | 1.3% | 63.7% | 9.4% |
| RETURN_CONST | 2,087,462,094 | 1.3% | 64.9% |  |
| INTERPRETER_EXIT | 2,037,826,255 | 1.2% | 66.2% |  |
| POP_JUMP_IF_TRUE | 2,030,947,065 | 1.2% | 67.4% |  |
| STORE_FAST_STORE_FAST | 2,002,683,365 | 1.2% | 68.6% |  |
| LOAD_ATTR_SLOT | 1,917,355,983 | 1.2% | 69.8% | 6.0% |
| STORE_ATTR_SLOT | 1,748,816,406 | 1.1% | 70.8% | 9.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,608,853,303 | 1.0% | 71.8% | 4.2% |
| COMPARE_OP_INT | 1,537,619,357 | 0.9% | 72.7% | 0.1% |
| LOAD_ATTR | 1,524,643,157 | 0.9% | 73.7% |  |
| PUSH_NULL | 1,374,868,302 | 0.8% | 74.5% |  |
| BINARY_OP_ADD_INT | 1,325,124,388 | 0.8% | 75.3% | 0.0% |
| YIELD_VALUE | 1,304,983,901 | 0.8% | 76.1% |  |
| CALL | 1,207,705,976 | 0.7% | 76.8% |  |
| COPY | 1,190,677,218 | 0.7% | 77.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,127,083,875 | 0.7% | 78.2% | 8.8% |
| CALL_BUILTIN_FAST | 1,116,015,699 | 0.7% | 78.9% | 0.0% |
| CONTAINS_OP | 1,114,998,090 | 0.7% | 79.6% |  |
| CALL_ISINSTANCE | 1,083,991,436 | 0.7% | 80.2% |  |
| SWAP | 1,079,545,540 | 0.7% | 80.9% |  |
| CALL_BUILTIN_O | 1,056,108,769 | 0.6% | 81.5% | 0.4% |
| NOP | 966,668,871 | 0.6% | 82.1% |  |
| BUILD_TUPLE | 939,860,383 | 0.6% | 82.7% |  |
| BINARY_OP | 886,788,769 | 0.5% | 83.2% |  |
| IS_OP | 836,877,452 | 0.5% | 83.7% |  |
| LOAD_DEREF | 805,912,250 | 0.5% | 84.2% |  |
| GET_ITER | 787,257,207 | 0.5% | 84.7% |  |
| BINARY_SUBSCR_LIST_INT | 786,826,894 | 0.5% | 85.2% | 0.5% |
| FOR_ITER_LIST | 727,507,148 | 0.4% | 85.6% | 9.7% |
| SEND_GEN | 702,716,368 | 0.4% | 86.0% | 0.0% |
| BINARY_SUBSCR | 698,856,997 | 0.4% | 86.4% |  |
| POP_JUMP_IF_NOT_NONE | 690,545,716 | 0.4% | 86.9% |  |
| BINARY_SUBSCR_DICT | 667,077,673 | 0.4% | 87.3% |  |
| TO_BOOL_NONE | 632,904,213 | 0.4% | 87.6% | 9.7% |
| BINARY_OP_MULTIPLY_FLOAT | 576,284,680 | 0.3% | 88.0% | 1.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 570,254,597 | 0.3% | 88.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 545,602,821 | 0.3% | 88.7% |  |
| LOAD_ATTR_MODULE | 537,933,901 | 0.3% | 89.0% | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 533,070,655 | 0.3% | 89.3% | 0.3% |
| JUMP_FORWARD | 526,240,173 | 0.3% | 89.6% |  |
| JUMP_BACKWARD | 506,827,869 | 0.3% | 89.9% |  |
| FOR_ITER | 506,177,092 | 0.3% | 90.3% |  |
| POP_JUMP_IF_NONE | 480,014,333 | 0.3% | 90.5% |  |
| BINARY_SUBSCR_STR_INT | 470,509,047 | 0.3% | 90.8% | 0.1% |
| BINARY_OP_SUBTRACT_INT | 460,970,404 | 0.3% | 91.1% | 0.1% |
| LOAD_ATTR_WITH_HINT | 450,614,364 | 0.3% | 91.4% | 0.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 424,413,275 | 0.3% | 91.6% | 10.0% |
| EXTENDED_ARG | 423,908,745 | 0.3% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 418,302,578 | 0.3% | 92.1% | 0.1% |
| RETURN_GENERATOR | 397,719,484 | 0.2% | 92.4% |  |
| BINARY_OP_ADD_FLOAT | 394,688,480 | 0.2% | 92.6% | 2.2% |
| COPY_FREE_VARS | 392,589,529 | 0.2% | 92.9% |  |
| CALL_LEN | 389,081,676 | 0.2% | 93.1% |  |
| BUILD_LIST | 364,695,061 | 0.2% | 93.3% |  |
| TO_BOOL | 347,548,866 | 0.2% | 93.5% |  |
| CALL_TYPE_1 | 347,170,562 | 0.2% | 93.7% |  |
| FOR_ITER_TUPLE | 345,167,764 | 0.2% | 94.0% | 20.4% |
| STORE_SUBSCR | 342,804,710 | 0.2% | 94.2% |  |
| COMPARE_OP_STR | 340,078,068 | 0.2% | 94.4% | 0.2% |
| CALL_LIST_APPEND | 339,076,989 | 0.2% | 94.6% | 0.0% |
| END_SEND | 314,344,063 | 0.2% | 94.8% |  |
| STORE_SUBSCR_LIST_INT | 310,883,677 | 0.2% | 94.9% | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 298,745,759 | 0.2% | 95.1% | 9.3% |
| BINARY_SLICE | 285,226,415 | 0.2% | 95.3% |  |
| CALL_KW | 263,822,702 | 0.2% | 95.5% |  |
| STORE_SUBSCR_DICT | 258,782,535 | 0.2% | 95.6% |  |
| TO_BOOL_ALWAYS_TRUE | 248,951,484 | 0.2% | 95.8% | 22.8% |
| BINARY_OP_MULTIPLY_INT | 248,923,112 | 0.2% | 95.9% | 4.6% |
| BINARY_OP_SUBTRACT_FLOAT | 238,707,665 | 0.1% | 96.1% | 8.5% |
| BINARY_SUBSCR_TUPLE_INT | 222,969,777 | 0.1% | 96.2% | 0.0% |
| CALL_PY_WITH_DEFAULTS | 218,049,273 | 0.1% | 96.3% | 2.7% |
| FOR_ITER_GEN | 217,178,477 | 0.1% | 96.5% | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 213,571,784 | 0.1% | 96.6% | 18.2% |
| TO_BOOL_INT | 208,396,377 | 0.1% | 96.7% | 0.6% |
| BINARY_SUBSCR_GETITEM | 190,892,692 | 0.1% | 96.8% | 0.0% |
| CALL_FUNCTION_EX | 187,940,541 | 0.1% | 96.9% |  |
| COMPARE_OP_FLOAT | 187,624,372 | 0.1% | 97.1% | 0.0% |
| TO_BOOL_LIST | 183,906,760 | 0.1% | 97.2% | 1.0% |
| CALL_BUILTIN_CLASS | 179,149,828 | 0.1% | 97.3% | 0.0% |
| DELETE_SUBSCR | 177,433,721 | 0.1% | 97.4% |  |
| COMPARE_OP | 167,720,773 | 0.1% | 97.5% |  |
| LOAD_SUPER_ATTR_METHOD | 166,753,474 | 0.1% | 97.6% |  |
| SEND | 165,323,677 | 0.1% | 97.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 163,772,990 | 0.1% | 97.8% | 41.7% |
| UNARY_NEGATIVE | 161,434,081 | 0.1% | 97.9% |  |
| CALL_INTRINSIC_1 | 155,763,671 | 0.1% | 98.0% |  |
| FORMAT_SIMPLE | 152,295,644 | 0.1% | 98.1% |  |
| GET_AWAITABLE | 152,094,985 | 0.1% | 98.2% |  |
| UNPACK_SEQUENCE_LIST | 148,230,221 | 0.1% | 98.3% | 0.8% |
| CONVERT_VALUE | 138,348,886 | 0.1% | 98.3% |  |
| BUILD_MAP | 118,531,024 | 0.1% | 98.4% |  |
| MAKE_CELL | 118,229,165 | 0.1% | 98.5% |  |
| LOAD_ATTR_CLASS | 117,629,017 | 0.1% | 98.6% | 1.5% |
| MAKE_FUNCTION | 110,790,640 | 0.1% | 98.6% |  |
| LIST_APPEND | 106,612,339 | 0.1% | 98.7% |  |
| SET_FUNCTION_ATTRIBUTE | 99,682,610 | 0.1% | 98.7% |  |
| BINARY_OP_ADD_UNICODE | 96,930,193 | 0.1% | 98.8% | 0.0% |
| BUILD_SLICE | 95,917,987 | 0.1% | 98.9% |  |
| FOR_ITER_RANGE | 95,829,831 | 0.1% | 98.9% | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 94,512,414 | 0.1% | 99.0% | 2.4% |
| LOAD_ATTR_PROPERTY | 93,684,250 | 0.1% | 99.0% | 12.2% |
| STORE_DEREF | 93,244,948 | 0.1% | 99.1% |  |
| EXIT_INIT_CHECK | 92,224,914 | 0.1% | 99.1% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 82,958,058 | 0.1% | 99.2% | 19.0% |
| LOAD_FAST_AND_CLEAR | 80,819,174 | 0.0% | 99.2% |  |
| TO_BOOL_STR | 77,801,484 | 0.0% | 99.3% | 4.5% |
| BUILD_STRING | 76,821,616 | 0.0% | 99.3% |  |
| END_FOR | 76,107,172 | 0.0% | 99.4% |  |
| STORE_ATTR | 72,365,714 | 0.0% | 99.4% |  |
| UNARY_NOT | 72,310,489 | 0.0% | 99.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 72,124,207 | 0.0% | 99.5% | 0.1% |
| STORE_ATTR_WITH_HINT | 67,943,717 | 0.0% | 99.6% | 0.1% |
| LOAD_ATTR_METHOD_LAZY_DICT | 59,283,076 | 0.0% | 99.6% | 0.0% |
| MAP_ADD | 57,589,747 | 0.0% | 99.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 54,619,099 | 0.0% | 99.7% | 4.3% |
| CALL_STR_1 | 40,750,957 | 0.0% | 99.7% |  |
| STORE_FAST_LOAD_FAST | 40,618,475 | 0.0% | 99.7% |  |
| DICT_MERGE | 38,106,715 | 0.0% | 99.7% |  |
| GET_YIELD_FROM_ITER | 36,767,784 | 0.0% | 99.8% |  |
| LIST_EXTEND | 36,605,267 | 0.0% | 99.8% |  |
| STORE_SLICE | 35,836,058 | 0.0% | 99.8% |  |
| CALL_TUPLE_1 | 35,176,991 | 0.0% | 99.8% | 0.0% |
| PUSH_EXC_INFO | 22,326,253 | 0.0% | 99.8% |  |
| POP_EXCEPT | 22,326,107 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 21,702,444 | 0.0% | 99.9% |  |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 19,465,840 | 0.0% | 99.9% |  |
| INSTRUMENTED_RESUME | 19,443,620 | 0.0% | 99.9% |  |
| INSTRUMENTED_RETURN_VALUE | 19,434,720 | 0.0% | 99.9% |  |
| UNARY_INVERT | 15,570,478 | 0.0% | 99.9% |  |
| LOAD_NAME | 13,936,780 | 0.0% | 99.9% |  |
| BUILD_CONST_KEY_MAP | 12,332,316 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 11,712,615 | 0.0% | 99.9% |  |
| IMPORT_FROM | 11,645,183 | 0.0% | 99.9% |  |
| DELETE_ATTR | 11,363,306 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 10,840,299 | 0.0% | 99.9% |  |
| IMPORT_NAME | 10,404,670 | 0.0% | 100.0% |  |
| BEFORE_WITH | 10,388,405 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 8,108,800 | 0.0% | 100.0% |  |
| GET_ANEXT | 8,000,960 | 0.0% | 100.0% |  |
| END_ASYNC_FOR | 8,000,000 | 0.0% | 100.0% |  |
| GET_AITER | 8,000,000 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 6,941,800 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 4,251,767 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 3,984,929 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 3,005,932 | 0.0% | 100.0% |  |
| RERAISE | 2,886,358 | 0.0% | 100.0% |  |
| BUILD_SET | 2,603,724 | 0.0% | 100.0% |  |
| DELETE_FAST | 2,134,584 | 0.0% | 100.0% |  |
| SET_ADD | 1,648,200 | 0.0% | 100.0% |  |
| STORE_NAME | 940,500 | 0.0% | 100.0% |  |
| UNPACK_EX | 756,000 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 373,327 | 0.0% | 100.0% |  |
| RESUME | 271,054 | 0.0% | 100.0% | 184.3% |
| WITH_EXCEPT_START | 184,309 | 0.0% | 100.0% |  |
| SET_UPDATE | 88,680 | 0.0% | 100.0% |  |
| DICT_UPDATE | 65,206 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 19,880 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 18,424 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 13,420 | 0.0% | 100.0% |  |
| INSTRUMENTED_FOR_ITER | 11,260 | 0.0% | 100.0% |  |
| INSTRUMENTED_JUMP_BACKWARD | 9,980 | 0.0% | 100.0% |  |
| INSTRUMENTED_RETURN_CONST | 7,200 | 0.0% | 100.0% |  |
| LOAD_LOCALS | 3,860 | 0.0% | 100.0% |  |
| LOAD_FROM_DICT_OR_DEREF | 3,840 | 0.0% | 100.0% |  |
| DELETE_DEREF | 1,600 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 1,520 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 1,320 | 0.0% | 100.0% |  |
| DELETE_NAME | 900 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_NONE | 720 | 0.0% | 100.0% |  |
| SETUP_ANNOTATIONS | 520 | 0.0% | 100.0% |  |
| INSTRUMENTED_JUMP_FORWARD | 400 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_NOT_NONE | 400 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_2 | 80 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 4,572,234,333 | 2.8% | 2.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 4,348,767,888 | 2.6% | 5.4% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 4,179,845,918 | 2.5% | 7.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,188,374,510 | 1.9% | 9.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,173,205,396 | 1.9% | 11.8% |
| RESUME_CHECK LOAD_FAST | 2,949,000,842 | 1.8% | 13.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 2,946,795,076 | 1.8% | 15.4% |
| LOAD_FAST LOAD_CONST | 2,851,187,848 | 1.7% | 17.1% |
| LOAD_FAST LOAD_ATTR_SLOT | 1,751,215,294 | 1.1% | 18.1% |
| CACHE RESUME_CHECK | 1,708,611,812 | 1.0% | 19.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,657,838,884 | 1.0% | 20.2% |
| LOAD_CONST LOAD_FAST | 1,388,052,984 | 0.8% | 21.0% |
| POP_TOP LOAD_FAST | 1,381,636,003 | 0.8% | 21.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,285,257,921 | 0.8% | 22.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,278,435,091 | 0.8% | 23.4% |
| LOAD_FAST RETURN_VALUE | 1,260,494,325 | 0.8% | 24.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,257,158,144 | 0.8% | 24.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 1,179,209,658 | 0.7% | 25.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 1,171,955,761 | 0.7% | 26.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,131,064,535 | 0.7% | 27.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,115,693,908 | 0.7% | 27.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,066,510,644 | 0.6% | 28.4% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 1,048,652,549 | 0.6% | 29.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,038,719,806 | 0.6% | 29.6% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 968,289,322 | 0.6% | 30.2% |
| RETURN_VALUE STORE_FAST | 962,327,634 | 0.6% | 30.8% |
| LOAD_FAST TO_BOOL_BOOL | 942,161,963 | 0.6% | 31.4% |
| LOAD_FAST LOAD_ATTR | 926,670,828 | 0.6% | 31.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 905,699,652 | 0.5% | 32.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 889,917,237 | 0.5% | 33.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 885,093,299 | 0.5% | 33.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 877,694,582 | 0.5% | 34.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 863,684,451 | 0.5% | 34.6% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 859,193,824 | 0.5% | 35.1% |
| RETURN_CONST POP_TOP | 855,902,295 | 0.5% | 35.6% |
| POP_TOP ENTER_EXECUTOR | 853,330,670 | 0.5% | 36.2% |
| LOAD_CONST LOAD_CONST | 839,101,270 | 0.5% | 36.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 830,786,549 | 0.5% | 37.2% |
| LOAD_FAST STORE_ATTR_SLOT | 813,580,362 | 0.5% | 37.7% |
| LOAD_FAST CALL_BUILTIN_O | 767,032,419 | 0.5% | 38.1% |
| LOAD_FAST LOAD_FAST | 745,097,878 | 0.5% | 38.6% |
| RESUME_CHECK POP_TOP | 743,764,161 | 0.5% | 39.0% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 743,504,847 | 0.5% | 39.5% |
| LOAD_FAST PUSH_NULL | 717,870,050 | 0.4% | 39.9% |
| RETURN_VALUE RETURN_VALUE | 717,355,707 | 0.4% | 40.3% |
| RETURN_CONST INTERPRETER_EXIT | 702,176,442 | 0.4% | 40.8% |
| STORE_FAST STORE_FAST | 701,310,016 | 0.4% | 41.2% |
| LOAD_CONST COMPARE_OP_INT | 697,978,309 | 0.4% | 41.6% |
| IS_OP POP_JUMP_IF_FALSE | 690,169,484 | 0.4% | 42.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 680,907,859 | 0.4% | 42.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 673,388,351 | 0.4% | 42.9% |
| PUSH_NULL LOAD_FAST | 656,572,370 | 0.4% | 43.2% |
| RETURN_VALUE INTERPRETER_EXIT | 654,749,596 | 0.4% | 43.6% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 651,578,182 | 0.4% | 44.0% |
| YIELD_VALUE INTERPRETER_EXIT | 634,170,443 | 0.4% | 44.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 620,554,775 | 0.4% | 44.8% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 614,163,522 | 0.4% | 45.2% |
| LOAD_CONST STORE_FAST | 603,097,336 | 0.4% | 45.5% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 602,328,214 | 0.4% | 45.9% |
| STORE_FAST_STORE_FAST LOAD_FAST | 586,391,475 | 0.4% | 46.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 579,889,071 | 0.4% | 46.6% |
| LOAD_GLOBAL_BUILTIN CALL_BUILTIN_FAST | 578,108,900 | 0.3% | 47.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 570,315,073 | 0.3% | 47.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 566,252,613 | 0.3% | 47.6% |
| BUILD_TUPLE RETURN_VALUE | 561,744,596 | 0.3% | 48.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 548,951,074 | 0.3% | 48.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 546,879,934 | 0.3% | 48.6% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 546,656,206 | 0.3% | 49.0% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 545,597,651 | 0.3% | 49.3% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 532,082,439 | 0.3% | 49.6% |
| YIELD_VALUE YIELD_VALUE | 529,744,593 | 0.3% | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT SEND_GEN | 529,725,014 | 0.3% | 50.3% |
| SEND_GEN RESUME_CHECK | 529,708,888 | 0.3% | 50.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 527,964,238 | 0.3% | 50.9% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 524,348,250 | 0.3% | 51.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 520,125,218 | 0.3% | 51.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 519,119,332 | 0.3% | 51.9% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 515,497,157 | 0.3% | 52.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 513,276,338 | 0.3% | 52.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 502,768,838 | 0.3% | 52.8% |
| CALL STORE_FAST | 478,511,213 | 0.3% | 53.1% |
| POP_JUMP_IF_FALSE RETURN_CONST | 451,769,724 | 0.3% | 53.3% |
| LOAD_ATTR_SLOT LOAD_FAST | 449,458,573 | 0.3% | 53.6% |
| CALL_BUILTIN_O POP_TOP | 441,874,300 | 0.3% | 53.9% |
| BINARY_OP_ADD_INT STORE_FAST | 439,560,733 | 0.3% | 54.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 435,242,880 | 0.3% | 54.4% |
| NOP LOAD_FAST | 422,947,913 | 0.3% | 54.7% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_STR_INT | 421,115,813 | 0.3% | 54.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 418,181,330 | 0.3% | 55.2% |
| STORE_ATTR_SLOT LOAD_CONST | 401,597,768 | 0.2% | 55.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 401,469,492 | 0.2% | 55.7% |
| POP_TOP RESUME_CHECK | 397,701,967 | 0.2% | 55.9% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 395,403,098 | 0.2% | 56.1% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 390,894,554 | 0.2% | 56.4% |
| STORE_ATTR_SLOT RETURN_CONST | 385,912,033 | 0.2% | 56.6% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 385,442,957 | 0.2% | 56.9% |
| RESUME_CHECK NOP | 379,638,116 | 0.2% | 57.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 378,790,492 | 0.2% | 57.3% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 375,498,267 | 0.2% | 57.5% |
| POP_JUMP_IF_FALSE LOAD_CONST | 367,961,733 | 0.2% | 57.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 173,804,675 | 60.9% |
| LOAD_FAST_LOAD_FAST | 51,940,380 | 18.2% |
| LOAD_FAST | 33,186,662 | 11.6% |
| BINARY_OP_ADD_INT | 18,215,058 | 6.4% |
| LOAD_ATTR_SLOT | 6,400,800 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 69,869,874 | 24.5% |
| GET_ITER | 44,571,320 | 15.6% |
| CALL_PY_EXACT_ARGS | 33,230,813 | 11.7% |
| BUILD_TUPLE | 32,461,700 | 11.4% |
| LOAD_DEREF | 25,325,840 | 8.9% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 23,030,720 | 64.3% |
| LOAD_CONST | 12,449,938 | 34.7% |
| LOAD_FAST_LOAD_FAST | 344,480 | 1.0% |
| LOAD_ATTR_SLOT | 10,700 | 0.0% |
| LOAD_FAST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,967,338 | 78.0% |
| RETURN_CONST | 7,807,680 | 21.8% |
| ENTER_EXECUTOR | 46,200 | 0.1% |
| JUMP_BACKWARD | 8,880 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 3,560 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,708,611,812 | 83.7% |
| POP_TOP | 148,477,154 | 7.3% |
| COPY_FREE_VARS | 135,112,226 | 6.6% |
| RETURN_GENERATOR | 46,716,651 | 2.3% |
| MAKE_CELL | 1,969,507 | 0.1% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,488,640 | 43.0% |
| ENTER_EXECUTOR | 1,740,380 | 21.5% |
| RETURN_VALUE | 909,040 | 11.2% |
| BINARY_SLICE | 786,260 | 9.7% |
| BINARY_OP_ADD_UNICODE | 633,400 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,109,060 | 87.7% |
| JUMP_BACKWARD | 835,780 | 10.3% |
| LOAD_CONST | 80,460 | 1.0% |
| LOAD_FAST_LOAD_FAST | 32,340 | 0.4% |
| ENTER_EXECUTOR | 26,340 | 0.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 186,993,816 | 26.8% |
| LOAD_CONST | 173,067,627 | 24.8% |
| COPY | 116,013,305 | 16.6% |
| LOAD_FAST_LOAD_FAST | 102,915,262 | 14.7% |
| BINARY_OP_ADD_INT | 43,215,640 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 234,802,018 | 33.6% |
| STORE_FAST | 97,328,451 | 13.9% |
| LOAD_FAST_LOAD_FAST | 65,591,330 | 9.4% |
| BINARY_SUBSCR_DICT | 49,452,000 | 7.1% |
| RETURN_VALUE | 47,674,637 | 6.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 19,930,364 | 91.8% |
| LOAD_GLOBAL_MODULE | 999,000 | 4.6% |
| BUILD_TUPLE | 637,578 | 2.9% |
| LOAD_ATTR_MODULE | 129,205 | 0.6% |
| LOAD_GLOBAL | 4,284 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 21,702,124 | 100.0% |
| EXTENDED_ARG | 320 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 92,224,914 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 92,224,914 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 292,258,098 | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE | 71,869,679 | 9.1% |
| CALL_BUILTIN_CLASS | 69,447,578 | 8.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 58,259,469 | 7.4% |
| RETURN_VALUE | 55,188,933 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 250,328,476 | 31.8% |
| FOR_ITER_TUPLE | 168,992,900 | 21.5% |
| CALL_PY_EXACT_ARGS | 98,476,334 | 12.5% |
| FOR_ITER | 94,322,723 | 12.0% |
| FOR_ITER_GEN | 75,708,971 | 9.6% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 702,176,442 | 34.5% |
| RETURN_VALUE | 654,749,596 | 32.1% |
| YIELD_VALUE | 634,170,443 | 31.1% |
| RETURN_GENERATOR | 46,729,454 | 2.3% |
| INSTRUMENTED_RETURN_VALUE | 320 | 0.0% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 14,980 | 75.4% |
| STORE_DEREF | 1,800 | 9.1% |
| POP_TOP | 1,580 | 7.9% |
| STORE_FAST | 440 | 2.2% |
| RETURN_VALUE | 240 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 19,880 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 110,790,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 98,238,879 | 88.7% |
| LOAD_FAST | 6,727,913 | 6.1% |
| LOAD_GLOBAL_MODULE | 3,345,600 | 3.0% |
| LOAD_GLOBAL_BUILTIN | 842,422 | 0.8% |
| STORE_FAST | 815,874 | 0.7% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 379,638,116 | 39.3% |
| STORE_FAST | 201,252,583 | 20.8% |
| POP_JUMP_IF_FALSE | 109,550,455 | 11.3% |
| STORE_ATTR_INSTANCE_VALUE | 72,414,156 | 7.5% |
| NOP | 65,367,310 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 422,947,913 | 43.8% |
| LOAD_FAST_LOAD_FAST | 350,542,704 | 36.3% |
| NOP | 65,367,310 | 6.8% |
| LOAD_GLOBAL_BUILTIN | 39,639,443 | 4.1% |
| LOAD_CONST | 31,016,156 | 3.2% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 13,578,974 | 60.8% |
| SWAP | 3,047,602 | 13.7% |
| STORE_SUBSCR_DICT | 2,799,534 | 12.5% |
| COPY | 1,718,808 | 7.7% |
| STORE_FAST | 881,341 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 11,385,002 | 51.0% |
| RETURN_VALUE | 2,968,002 | 13.3% |
| JUMP_FORWARD | 2,296,760 | 10.3% |
| POP_TOP | 1,846,961 | 8.3% |
| RERAISE | 1,718,808 | 7.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 855,902,295 | 23.6% |
| RESUME_CHECK | 743,764,161 | 20.5% |
| CALL_BUILTIN_O | 441,874,300 | 12.2% |
| CALL_METHOD_DESCRIPTOR_O | 274,714,189 | 7.6% |
| POP_JUMP_IF_FALSE | 201,545,355 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,381,636,003 | 38.1% |
| ENTER_EXECUTOR | 853,330,670 | 23.6% |
| RESUME_CHECK | 397,701,967 | 11.0% |
| RETURN_CONST | 309,163,775 | 8.5% |
| LOAD_CONST | 149,755,025 | 4.1% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 5,816,450 | 26.1% |
| LOAD_ATTR | 4,419,800 | 19.8% |
| RAISE_VARARGS | 3,179,567 | 14.2% |
| CALL_BUILTIN_FAST | 2,382,292 | 10.7% |
| RERAISE | 1,490,350 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 20,045,240 | 89.8% |
| LOAD_GLOBAL_MODULE | 1,569,061 | 7.0% |
| LOAD_FAST | 517,720 | 2.3% |
| WITH_EXCEPT_START | 184,309 | 0.8% |
| LOAD_GLOBAL | 9,604 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 717,870,050 | 52.2% |
| LOAD_ATTR_MODULE | 435,242,880 | 31.7% |
| LOAD_DEREF | 68,050,783 | 4.9% |
| LOAD_ATTR | 64,171,588 | 4.7% |
| LOAD_FAST_LOAD_FAST | 39,219,582 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 656,572,370 | 47.8% |
| LOAD_FAST_LOAD_FAST | 385,442,957 | 28.0% |
| LOAD_CONST | 162,037,034 | 11.8% |
| CALL | 102,859,415 | 7.5% |
| LOAD_GLOBAL_MODULE | 33,064,170 | 2.4% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,260,494,325 | 28.6% |
| RETURN_VALUE | 717,355,707 | 16.3% |
| BUILD_TUPLE | 561,744,596 | 12.8% |
| LOAD_ATTR_INSTANCE_VALUE | 274,047,969 | 6.2% |
| COMPARE_OP_FLOAT | 128,319,704 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 962,327,634 | 21.9% |
| RETURN_VALUE | 717,355,707 | 16.3% |
| INTERPRETER_EXIT | 654,749,596 | 14.9% |
| TO_BOOL_BOOL | 350,766,922 | 8.0% |
| UNPACK_SEQUENCE_TUPLE | 345,372,827 | 7.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 116,023,585 | 33.8% |
| LOAD_FAST | 85,528,400 | 24.9% |
| LOAD_CONST | 44,699,648 | 13.0% |
| BINARY_OP_ADD_INT | 38,502,360 | 11.2% |
| LOAD_FAST_LOAD_FAST | 37,514,260 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 115,319,440 | 33.6% |
| ENTER_EXECUTOR | 77,429,040 | 22.6% |
| RETURN_CONST | 48,401,583 | 14.1% |
| LOAD_GLOBAL_BUILTIN | 36,004,000 | 10.5% |
| LOAD_FAST | 22,254,685 | 6.5% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 236,558,015 | 68.1% |
| LOAD_ATTR_INSTANCE_VALUE | 77,758,810 | 22.4% |
| CALL_BUILTIN_FAST | 10,290,920 | 3.0% |
| LOAD_ATTR | 9,988,158 | 2.9% |
| LOAD_ATTR_SLOT | 4,277,123 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 198,702,010 | 57.2% |
| POP_JUMP_IF_FALSE | 147,392,345 | 42.4% |
| TO_BOOL | 479,111 | 0.1% |
| UNARY_NOT | 380,115 | 0.1% |
| TO_BOOL_NONE | 197,540 | 0.1% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,149,289 | 20.4% |
| LOAD_CONST | 163,356,957 | 18.4% |
| CALL_METHOD_DESCRIPTOR_O | 96,003,000 | 10.8% |
| LOAD_FAST_LOAD_FAST | 67,925,924 | 7.7% |
| BINARY_OP_ADD_INT | 56,113,483 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 174,779,041 | 19.7% |
| LOAD_FAST | 151,445,256 | 17.1% |
| LOAD_FAST_LOAD_FAST | 130,557,317 | 14.7% |
| RETURN_VALUE | 97,755,340 | 11.0% |
| SWAP | 56,403,544 | 6.4% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 146,030,493 | 40.0% |
| LOAD_FAST | 45,348,578 | 12.4% |
| SWAP | 41,844,495 | 11.5% |
| RESUME_CHECK | 23,623,484 | 6.5% |
| LOAD_CONST | 16,109,966 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 183,534,792 | 50.3% |
| LOAD_FAST | 72,969,844 | 20.0% |
| SWAP | 41,883,983 | 11.5% |
| RETURN_VALUE | 11,905,048 | 3.3% |
| CALL | 11,841,840 | 3.2% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,194,673 | 28.0% |
| STORE_FAST | 14,691,330 | 12.4% |
| SWAP | 12,811,618 | 10.8% |
| RESUME_CHECK | 9,131,419 | 7.7% |
| BUILD_TUPLE | 8,801,706 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,486,420 | 40.1% |
| STORE_FAST | 31,987,880 | 27.0% |
| SWAP | 12,811,618 | 10.8% |
| CALL_FUNCTION_EX | 9,564,836 | 8.1% |
| CALL_BUILTIN_FAST | 5,767,140 | 4.9% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 284,983,918 | 30.3% |
| LOAD_CONST | 223,366,048 | 23.8% |
| LOAD_FAST_LOAD_FAST | 188,135,970 | 20.0% |
| CALL | 51,709,156 | 5.5% |
| LOAD_GLOBAL_BUILTIN | 38,467,004 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 561,744,596 | 59.8% |
| LOAD_CONST | 98,839,337 | 10.5% |
| CALL_ISINSTANCE | 44,685,517 | 4.8% |
| YIELD_VALUE | 40,563,168 | 4.3% |
| LIST_APPEND | 33,733,752 | 3.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 328,172,505 | 27.2% |
| LOAD_FAST_LOAD_FAST | 153,735,996 | 12.7% |
| PUSH_NULL | 102,859,415 | 8.5% |
| BINARY_SUBSCR_TUPLE_INT | 96,160,224 | 8.0% |
| ENTER_EXECUTOR | 93,541,310 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 478,511,213 | 39.6% |
| RESUME_CHECK | 206,468,314 | 17.1% |
| POP_TOP | 89,999,767 | 7.5% |
| RETURN_VALUE | 56,932,999 | 4.7% |
| LOAD_GLOBAL_MODULE | 56,452,018 | 4.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 94,464,699 | 50.3% |
| DICT_MERGE | 38,106,715 | 20.3% |
| LOAD_FAST | 22,838,728 | 12.2% |
| CALL_INTRINSIC_1 | 17,484,093 | 9.3% |
| BUILD_MAP | 9,564,836 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 110,388,205 | 58.7% |
| STORE_FAST | 27,208,883 | 14.5% |
| RESUME_CHECK | 21,411,268 | 11.4% |
| RETURN_VALUE | 9,536,498 | 5.1% |
| LOAD_FAST_LOAD_FAST | 6,654,200 | 3.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,515,680 | 75.4% |
| LIST_EXTEND | 35,416,389 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,757,500 | 1.8% |
| RERAISE | 56,520 | 0.0% |
| LIST_APPEND | 15,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 120,273,200 | 77.2% |
| CALL_FUNCTION_EX | 17,484,093 | 11.2% |
| LOAD_CONST | 9,378,916 | 6.0% |
| BUILD_MAP | 8,535,820 | 5.5% |
| RERAISE | 56,842 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 50,887,399 | 30.3% |
| LOAD_FAST_LOAD_FAST | 27,592,571 | 16.5% |
| LOAD_FAST | 22,941,039 | 13.7% |
| LOAD_ATTR_SLOT | 18,388,455 | 11.0% |
| LOAD_GLOBAL_MODULE | 13,556,667 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 106,746,043 | 63.6% |
| COPY | 17,307,863 | 10.3% |
| POP_JUMP_IF_TRUE | 16,479,645 | 9.8% |
| RETURN_VALUE | 9,642,112 | 5.7% |
| BINARY_OP | 6,162,440 | 3.7% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 171,883,124 | 43.8% |
| CACHE | 135,112,226 | 34.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 37,063,652 | 9.4% |
| ENTER_EXECUTOR | 21,350,460 | 5.4% |
| CALL | 7,491,815 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 285,378,477 | 72.7% |
| RETURN_GENERATOR | 107,088,098 | 27.3% |
| MAKE_CELL | 105,722 | 0.0% |
| RESUME | 17,232 | 0.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 853,330,670 | 35.0% |
| POP_JUMP_IF_TRUE | 524,348,250 | 21.5% |
| POP_JUMP_IF_FALSE | 260,653,323 | 10.7% |
| STORE_FAST | 156,307,896 | 6.4% |
| CALL_LIST_APPEND | 130,588,189 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 366,556,559 | 15.0% |
| FOR_ITER_LIST | 340,290,634 | 14.0% |
| POP_JUMP_IF_FALSE | 336,033,011 | 13.8% |
| FOR_ITER_TUPLE | 167,238,336 | 6.9% |
| SEND | 125,514,720 | 5.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 352,590,706 | 69.7% |
| GET_ITER | 94,322,723 | 18.6% |
| EXTENDED_ARG | 27,478,282 | 5.4% |
| SWAP | 16,598,370 | 3.3% |
| LOAD_FAST | 11,842,245 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 267,295,932 | 52.8% |
| STORE_FAST | 123,441,865 | 24.4% |
| LOAD_FAST | 40,149,391 | 7.9% |
| RETURN_CONST | 25,724,137 | 5.1% |
| SWAP | 15,843,970 | 3.1% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 303,262,853 | 36.2% |
| LOAD_GLOBAL_MODULE | 257,611,146 | 30.8% |
| LOAD_FAST_LOAD_FAST | 148,944,726 | 17.8% |
| LOAD_GLOBAL_BUILTIN | 61,899,021 | 7.4% |
| LOAD_FAST | 28,492,190 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 690,169,484 | 82.5% |
| POP_JUMP_IF_TRUE | 83,991,977 | 10.0% |
| EXTENDED_ARG | 24,207,600 | 2.9% |
| STORE_FAST | 14,900,040 | 1.8% |
| YIELD_VALUE | 12,963,558 | 1.5% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 137,063,208 | 27.0% |
| STORE_FAST | 100,087,998 | 19.7% |
| POP_JUMP_IF_TRUE | 57,198,400 | 11.3% |
| STORE_SUBSCR_LIST_INT | 47,752,199 | 9.4% |
| LIST_APPEND | 27,864,280 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 352,590,706 | 69.6% |
| FOR_ITER_GEN | 107,325,184 | 21.2% |
| EXTENDED_ARG | 43,321,771 | 8.5% |
| RETURN_CONST | 2,757,120 | 0.5% |
| FOR_ITER_LIST | 403,733 | 0.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 249,591,115 | 47.4% |
| POP_JUMP_IF_FALSE | 117,382,322 | 22.3% |
| POP_TOP | 54,186,032 | 10.3% |
| POP_JUMP_IF_NONE | 14,018,240 | 2.7% |
| LOAD_ATTR_SLOT | 13,647,700 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 215,298,830 | 40.9% |
| LOAD_FAST_LOAD_FAST | 97,612,039 | 18.5% |
| LOAD_CONST | 50,603,372 | 9.6% |
| LOAD_GLOBAL_BUILTIN | 36,395,316 | 6.9% |
| LOAD_GLOBAL_MODULE | 35,243,572 | 6.7% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,679,857 | 67.4% |
| LOAD_ATTR_SLOT | 10,937,481 | 29.9% |
| LOAD_CONST | 499,680 | 1.4% |
| RETURN_VALUE | 325,541 | 0.9% |
| LOAD_DEREF | 104,608 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 35,416,389 | 96.8% |
| STORE_FAST | 602,337 | 1.6% |
| LOAD_FAST | 341,001 | 0.9% |
| UNPACK_SEQUENCE_LIST | 230,040 | 0.6% |
| BUILD_TUPLE | 7,400 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 926,670,828 | 60.8% |
| LOAD_GLOBAL_BUILTIN | 297,839,808 | 19.5% |
| LOAD_GLOBAL_MODULE | 147,686,349 | 9.7% |
| LOAD_ATTR_SLOT | 70,456,666 | 4.6% |
| LOAD_FAST_LOAD_FAST | 29,696,251 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 303,262,853 | 19.9% |
| STORE_FAST | 262,547,655 | 17.2% |
| LOAD_FAST | 262,162,362 | 17.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 107,003,147 | 7.0% |
| CALL | 67,116,695 | 4.4% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,851,187,848 | 33.9% |
| LOAD_CONST | 839,101,270 | 10.0% |
| STORE_ATTR_SLOT | 401,597,768 | 4.8% |
| LOAD_FAST_LOAD_FAST | 390,894,554 | 4.6% |
| POP_JUMP_IF_FALSE | 367,961,733 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,388,052,984 | 16.5% |
| BINARY_OP_ADD_INT | 877,694,582 | 10.4% |
| LOAD_CONST | 839,101,270 | 10.0% |
| COMPARE_OP_INT | 697,978,309 | 8.3% |
| STORE_FAST | 603,097,336 | 7.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160,627,731 | 19.9% |
| STORE_FAST | 110,106,782 | 13.7% |
| POP_JUMP_IF_FALSE | 66,292,160 | 8.2% |
| STORE_FAST_STORE_FAST | 45,991,537 | 5.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 41,727,600 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 365,873,068 | 45.4% |
| LOAD_CONST | 94,473,792 | 11.7% |
| PUSH_NULL | 68,050,783 | 8.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 47,179,928 | 5.9% |
| LOAD_DEREF | 32,496,681 | 4.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,572,234,333 | 14.6% |
| POP_JUMP_IF_FALSE | 4,348,767,888 | 13.9% |
| LOAD_GLOBAL_BUILTIN | 3,173,205,396 | 10.1% |
| RESUME_CHECK | 2,949,000,842 | 9.4% |
| LOAD_CONST | 1,388,052,984 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,179,845,918 | 13.3% |
| LOAD_CONST | 2,851,187,848 | 9.1% |
| LOAD_ATTR_SLOT | 1,751,215,294 | 5.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,657,838,884 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 1,278,435,091 | 4.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 859,193,824 | 11.9% |
| POP_JUMP_IF_FALSE | 614,163,522 | 8.5% |
| LOAD_GLOBAL_MODULE | 579,889,071 | 8.0% |
| LOAD_FAST_LOAD_FAST | 548,951,074 | 7.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 527,964,238 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 885,093,299 | 12.2% |
| CALL_PY_EXACT_ARGS | 743,504,847 | 10.3% |
| LOAD_FAST | 680,907,859 | 9.4% |
| LOAD_FAST_LOAD_FAST | 548,951,074 | 7.6% |
| BINARY_SUBSCR_STR_INT | 421,115,813 | 5.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 9,716,800 | 89.6% |
| STORE_FAST | 158,202 | 1.5% |
| LOAD_FAST | 150,657 | 1.4% |
| POP_JUMP_IF_FALSE | 142,131 | 1.3% |
| POP_TOP | 85,015 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,910,545 | 91.4% |
| LOAD_GLOBAL_MODULE | 356,537 | 3.3% |
| LOAD_GLOBAL_BUILTIN | 187,371 | 1.7% |
| LOAD_ATTR | 114,738 | 1.1% |
| CALL | 65,969 | 0.6% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,739,060 | 48.4% |
| RESUME_CHECK | 5,281,700 | 37.9% |
| LOAD_NAME | 860,340 | 6.2% |
| STORE_NAME | 343,380 | 2.5% |
| BINARY_SUBSCR_DICT | 261,920 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,290,120 | 45.1% |
| LOAD_CONST | 5,818,360 | 41.7% |
| LOAD_NAME | 860,340 | 6.2% |
| STORE_SUBSCR_DICT | 278,780 | 2.0% |
| CONTAINS_OP | 262,640 | 1.9% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,964 | 97.5% |
| LOAD_DEREF | 300 | 1.6% |
| EXTENDED_ARG | 120 | 0.7% |
| LOAD_GLOBAL | 20 | 0.1% |
| LOAD_GLOBAL_MODULE | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 8,180 | 44.4% |
| CALL | 3,684 | 20.0% |
| LOAD_FAST | 2,760 | 15.0% |
| LOAD_FAST_LOAD_FAST | 1,620 | 8.8% |
| LOAD_SUPER_ATTR_ATTR | 960 | 5.2% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 66,582,235 | 56.3% |
| CALL_PY_EXACT_ARGS | 34,367,233 | 29.1% |
| CALL_KW | 5,443,986 | 4.6% |
| CALL_FUNCTION_EX | 5,007,752 | 4.2% |
| CALL_PY_WITH_DEFAULTS | 2,118,550 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 66,582,235 | 56.3% |
| RESUME_CHECK | 50,765,762 | 42.9% |
| RETURN_GENERATOR | 858,688 | 0.7% |
| RESUME | 11,440 | 0.0% |
| SWAP | 10,960 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,188,374,510 | 39.0% |
| COMPARE_OP_INT | 1,285,257,921 | 15.7% |
| CONTAINS_OP | 968,289,322 | 11.8% |
| IS_OP | 690,169,484 | 8.4% |
| TO_BOOL_NONE | 532,082,439 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,348,767,888 | 53.2% |
| LOAD_GLOBAL_BUILTIN | 1,171,955,761 | 14.3% |
| LOAD_FAST_LOAD_FAST | 614,163,522 | 7.5% |
| RETURN_CONST | 451,769,724 | 5.5% |
| LOAD_GLOBAL_MODULE | 378,790,492 | 4.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 329,714,869 | 68.7% |
| EXTENDED_ARG | 48,439,406 | 10.1% |
| LOAD_ATTR_INSTANCE_VALUE | 33,467,368 | 7.0% |
| LOAD_ATTR_SLOT | 31,492,960 | 6.6% |
| LOAD_DEREF | 19,462,488 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 289,291,211 | 60.3% |
| LOAD_DEREF | 36,714,385 | 7.6% |
| ENTER_EXECUTOR | 34,683,186 | 7.2% |
| LOAD_FAST_LOAD_FAST | 23,454,577 | 4.9% |
| JUMP_BACKWARD | 21,422,661 | 4.5% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 570,315,073 | 82.6% |
| LOAD_ATTR_INSTANCE_VALUE | 68,801,796 | 10.0% |
| LOAD_ATTR | 18,981,823 | 2.7% |
| EXTENDED_ARG | 9,717,120 | 1.4% |
| LOAD_ATTR_SLOT | 5,380,240 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 307,385,133 | 44.5% |
| LOAD_FAST_LOAD_FAST | 138,276,874 | 20.0% |
| LOAD_GLOBAL_MODULE | 80,758,455 | 11.7% |
| LOAD_GLOBAL_BUILTIN | 68,629,763 | 9.9% |
| RETURN_CONST | 27,552,406 | 4.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,038,719,806 | 51.1% |
| TO_BOOL | 198,702,010 | 9.8% |
| COMPARE_OP_INT | 151,420,931 | 7.5% |
| TO_BOOL_ALWAYS_TRUE | 109,997,935 | 5.4% |
| TO_BOOL_NONE | 98,272,372 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 889,917,237 | 43.8% |
| ENTER_EXECUTOR | 524,348,250 | 25.8% |
| LOAD_GLOBAL_BUILTIN | 146,547,340 | 7.2% |
| LOAD_CONST | 96,776,765 | 4.8% |
| POP_TOP | 87,372,245 | 4.3% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 451,769,724 | 21.6% |
| STORE_ATTR_SLOT | 385,912,033 | 18.5% |
| POP_TOP | 309,163,775 | 14.8% |
| STORE_ATTR_INSTANCE_VALUE | 227,231,564 | 10.9% |
| RESUME_CHECK | 176,805,617 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 855,902,295 | 41.0% |
| INTERPRETER_EXIT | 702,176,442 | 33.6% |
| EXIT_INIT_CHECK | 92,224,914 | 4.4% |
| TO_BOOL_BOOL | 79,490,582 | 3.8% |
| END_FOR | 76,107,172 | 3.6% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 125,514,720 | 75.9% |
| LOAD_CONST | 23,878,590 | 14.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 15,877,807 | 9.6% |
| SEND | 51,980 | 0.0% |
| SEND_GEN | 580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 141,380,052 | 85.5% |
| YIELD_VALUE | 15,865,712 | 9.6% |
| END_ASYNC_FOR | 8,000,000 | 4.8% |
| SEND | 51,980 | 0.0% |
| RESUME_CHECK | 10,200 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 98,238,879 | 98.6% |
| SET_FUNCTION_ATTRIBUTE | 1,443,731 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,881,466 | 60.1% |
| LOAD_GLOBAL_BUILTIN | 25,348,160 | 25.4% |
| STORE_FAST | 7,983,717 | 8.0% |
| CALL_PY_EXACT_ARGS | 2,704,550 | 2.7% |
| SET_FUNCTION_ATTRIBUTE | 1,443,731 | 1.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,787,735 | 57.7% |
| LOAD_FAST_LOAD_FAST | 21,102,431 | 29.2% |
| CALL | 6,424,560 | 8.9% |
| SWAP | 1,529,657 | 2.1% |
| CALL_KW | 801,120 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,035,127 | 29.1% |
| LOAD_DEREF | 17,938,486 | 24.8% |
| RETURN_CONST | 12,102,234 | 16.7% |
| LOAD_FAST_LOAD_FAST | 6,616,519 | 9.1% |
| ENTER_EXECUTOR | 5,710,700 | 7.9% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 35,847,844 | 38.4% |
| STORE_FAST | 25,638,100 | 27.5% |
| LOAD_CONST | 9,112,710 | 9.8% |
| LOAD_FAST | 3,889,520 | 4.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,579,820 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,893,400 | 31.0% |
| LOAD_DEREF | 19,660,882 | 21.1% |
| LOAD_FAST_LOAD_FAST | 17,926,006 | 19.2% |
| LOAD_FAST | 10,892,275 | 11.7% |
| LOAD_CONST | 6,425,030 | 6.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 962,327,634 | 11.1% |
| STORE_FAST | 701,310,016 | 8.1% |
| LOAD_CONST | 603,097,336 | 7.0% |
| CALL | 478,511,213 | 5.5% |
| BINARY_OP_ADD_INT | 439,560,733 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,572,234,333 | 52.8% |
| LOAD_FAST_LOAD_FAST | 859,193,824 | 9.9% |
| STORE_FAST | 701,310,016 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 566,252,613 | 6.5% |
| LOAD_GLOBAL_MODULE | 513,276,338 | 5.9% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,048,652,549 | 52.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 502,768,838 | 25.1% |
| UNPACK_SEQUENCE_TUPLE | 194,834,681 | 9.7% |
| UNPACK_SEQUENCE_LIST | 146,485,121 | 7.3% |
| LOAD_ATTR_SLOT | 61,211,344 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,048,652,549 | 52.4% |
| LOAD_FAST | 586,391,475 | 29.3% |
| LOAD_FAST_LOAD_FAST | 121,073,720 | 6.0% |
| STORE_FAST | 69,935,931 | 3.5% |
| LOAD_GLOBAL_MODULE | 63,180,491 | 3.2% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 279,420 | 29.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 276,160 | 29.4% |
| MAKE_FUNCTION | 104,220 | 11.1% |
| LOAD_CONST | 60,680 | 6.5% |
| IMPORT_FROM | 58,940 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 343,380 | 36.5% |
| STORE_NAME | 279,420 | 29.7% |
| LOAD_CONST | 198,360 | 21.1% |
| IMPORT_FROM | 35,660 | 3.8% |
| POP_TOP | 23,300 | 2.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 128,400 | 34.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 90,720 | 24.3% |
| LOAD_FAST | 35,074 | 9.4% |
| COPY | 26,720 | 7.2% |
| RETURN_VALUE | 25,792 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 216,031 | 57.9% |
| STORE_FAST | 109,815 | 29.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 26,689 | 7.1% |
| UNPACK_SEQUENCE_TUPLE | 13,759 | 3.7% |
| UNPACK_SEQUENCE | 2,853 | 0.8% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 104,765 | 38.7% |
| CACHE | 77,712 | 28.7% |
| CALL_PY_EXACT_ARGS | 17,963 | 6.6% |
| COPY_FREE_VARS | 17,232 | 6.4% |
| POP_TOP | 15,757 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 111,031 | 41.0% |
| LOAD_GLOBAL | 64,514 | 23.8% |
| LOAD_CONST | 23,942 | 8.8% |
| LOAD_NAME | 19,700 | 7.3% |
| LOAD_FAST_LOAD_FAST | 10,509 | 3.9% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 96,946,560 | 40.6% |
| LOAD_FAST | 75,806,464 | 31.8% |
| LOAD_ATTR_INSTANCE_VALUE | 38,337,315 | 16.1% |
| BINARY_OP_SUBTRACT_FLOAT | 14,316,500 | 6.0% |
| BINARY_SUBSCR | 8,809,880 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 74,443,752 | 31.2% |
| LOAD_FAST_LOAD_FAST | 73,524,560 | 30.8% |
| LOAD_FAST | 37,921,837 | 15.9% |
| STORE_FAST | 31,968,317 | 13.4% |
| BINARY_OP_SUBTRACT_FLOAT | 14,316,500 | 6.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 237,814,115 | 35.7% |
| LOAD_CONST | 229,586,986 | 34.4% |
| LOAD_FAST_LOAD_FAST | 111,997,747 | 16.8% |
| BINARY_SUBSCR | 49,452,000 | 7.4% |
| CALL_BUILTIN_O | 10,745,560 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 217,633,860 | 32.6% |
| RETURN_VALUE | 118,872,737 | 17.8% |
| CONTAINS_OP | 78,260,500 | 11.7% |
| LOAD_FAST | 65,887,777 | 9.9% |
| LOAD_ATTR_METHOD_NO_DICT | 53,778,966 | 8.1% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 21,530,660 | 22.8% |
| ENTER_EXECUTOR | 16,925,540 | 17.9% |
| BINARY_OP_MULTIPLY_FLOAT | 11,171,080 | 11.8% |
| RETURN_CONST | 10,486,240 | 11.1% |
| BINARY_OP_ADD_FLOAT | 6,838,650 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 90,290,391 | 95.5% |
| LOAD_FAST | 2,217,180 | 2.3% |
| COPY_FREE_VARS | 1,934,483 | 2.0% |
| CALL_ALLOC_AND_ENTER_INIT | 43,040 | 0.0% |
| STORE_FAST | 19,660 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,187,213 | 27.5% |
| CALL_LEN | 31,405,440 | 17.5% |
| LOAD_GLOBAL_BUILTIN | 17,872,307 | 10.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,231,458 | 6.8% |
| LOAD_CONST | 6,851,254 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 69,447,578 | 38.8% |
| STORE_FAST | 27,602,539 | 15.4% |
| BINARY_OP_MULTIPLY_FLOAT | 16,972,000 | 9.5% |
| LOAD_FAST | 16,555,423 | 9.2% |
| RETURN_VALUE | 6,555,989 | 3.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 578,108,900 | 51.8% |
| LOAD_CONST | 320,066,423 | 28.7% |
| LOAD_FAST_LOAD_FAST | 114,346,311 | 10.2% |
| CALL_BUILTIN_FAST | 28,096,780 | 2.5% |
| LOAD_FAST | 25,419,616 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 651,578,182 | 58.4% |
| STORE_FAST | 302,751,441 | 27.1% |
| POP_TOP | 42,062,887 | 3.8% |
| RETURN_VALUE | 37,505,169 | 3.4% |
| CALL_BUILTIN_FAST | 28,096,780 | 2.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 43,093,243 | 59.7% |
| LOAD_FAST | 12,792,561 | 17.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 7,731,309 | 10.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,986,400 | 4.1% |
| LOAD_FAST_LOAD_FAST | 2,224,120 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 41,727,600 | 57.9% |
| STORE_FAST | 12,577,869 | 17.4% |
| CALL_TUPLE_1 | 4,707,669 | 6.5% |
| POP_TOP | 4,403,615 | 6.1% |
| LOAD_FAST | 3,036,980 | 4.2% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 767,032,419 | 72.6% |
| RETURN_VALUE | 72,240,120 | 6.8% |
| LOAD_CONST | 62,268,375 | 5.9% |
| BUILD_STRING | 48,929,440 | 4.6% |
| BINARY_OP_ADD_UNICODE | 21,212,480 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 441,874,300 | 41.8% |
| LOAD_CONST | 229,039,204 | 21.7% |
| STORE_FAST | 223,330,601 | 21.1% |
| RETURN_VALUE | 52,575,743 | 5.0% |
| TO_BOOL_BOOL | 22,956,117 | 2.2% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 546,656,206 | 50.4% |
| LOAD_GLOBAL_BUILTIN | 375,498,267 | 34.6% |
| LOAD_FAST_LOAD_FAST | 64,286,676 | 5.9% |
| BUILD_TUPLE | 44,685,517 | 4.1% |
| LOAD_ATTR_MODULE | 33,701,633 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,066,510,644 | 98.4% |
| COPY | 8,611,300 | 0.8% |
| RETURN_VALUE | 3,380,885 | 0.3% |
| YIELD_VALUE | 3,134,882 | 0.3% |
| STORE_FAST | 1,987,392 | 0.2% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,764,389 | 71.6% |
| ENTER_EXECUTOR | 53,732,513 | 15.8% |
| BINARY_OP | 7,151,040 | 2.1% |
| BINARY_SUBSCR_TUPLE_INT | 6,856,180 | 2.0% |
| RETURN_VALUE | 6,273,800 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 130,588,189 | 38.5% |
| LOAD_FAST | 98,934,199 | 29.2% |
| EXTENDED_ARG | 41,813,032 | 12.3% |
| RETURN_CONST | 24,919,800 | 7.3% |
| LOAD_CONST | 15,073,520 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 210,014,410 | 49.5% |
| LOAD_FAST_LOAD_FAST | 65,463,721 | 15.4% |
| LOAD_ATTR_METHOD_NO_DICT | 53,965,700 | 12.7% |
| LOAD_CONST | 32,484,548 | 7.7% |
| LOAD_GLOBAL_MODULE | 24,405,052 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 326,933,363 | 77.0% |
| LOAD_FAST | 27,060,449 | 6.4% |
| RETURN_VALUE | 15,709,181 | 3.7% |
| TO_BOOL_BOOL | 11,818,058 | 2.8% |
| POP_TOP | 10,746,466 | 2.5% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 156,384,878 | 52.3% |
| LOAD_ATTR | 107,003,147 | 35.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 22,731,846 | 7.6% |
| LOAD_ATTR_METHOD_LAZY_DICT | 9,921,441 | 3.3% |
| LOAD_FAST | 2,104,284 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 108,421,011 | 36.3% |
| GET_ITER | 58,259,469 | 19.5% |
| STORE_FAST | 47,053,664 | 15.8% |
| LOAD_GLOBAL_MODULE | 24,843,120 | 8.3% |
| LOAD_FAST | 16,767,659 | 5.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,115,693,908 | 33.1% |
| LOAD_FAST_LOAD_FAST | 743,504,847 | 22.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 602,328,214 | 17.9% |
| LOAD_GLOBAL_MODULE | 197,998,082 | 5.9% |
| LOAD_ATTR_METHOD_NO_DICT | 124,483,544 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,946,795,076 | 87.5% |
| RETURN_GENERATOR | 194,119,622 | 5.8% |
| COPY_FREE_VARS | 171,883,124 | 5.1% |
| MAKE_CELL | 34,367,233 | 1.0% |
| INSTRUMENTED_RESUME | 19,436,580 | 0.6% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 59,888,501 | 27.5% |
| LOAD_FAST | 48,354,420 | 22.2% |
| LOAD_FAST_LOAD_FAST | 35,133,400 | 16.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 16,279,898 | 7.5% |
| BINARY_OP_ADD_INT | 11,201,440 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 199,903,882 | 91.7% |
| RETURN_GENERATOR | 8,945,409 | 4.1% |
| COPY_FREE_VARS | 6,957,432 | 3.2% |
| MAKE_CELL | 2,118,550 | 1.0% |
| CALL_PY_EXACT_ARGS | 97,000 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 342,099,583 | 98.5% |
| LOAD_CONST | 4,947,278 | 1.4% |
| BINARY_SUBSCR_TUPLE_INT | 87,960 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 25,720 | 0.0% |
| LOAD_GLOBAL_MODULE | 5,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 267,580,653 | 77.1% |
| LOAD_GLOBAL_BUILTIN | 24,716,999 | 7.1% |
| LOAD_GLOBAL_MODULE | 18,361,789 | 5.3% |
| LOAD_FAST | 9,451,912 | 2.7% |
| CALL_PY_EXACT_ARGS | 6,879,097 | 2.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 40,784,866 | 42.6% |
| LOAD_FAST | 28,737,640 | 30.0% |
| GET_ITER | 19,679,771 | 20.5% |
| SWAP | 5,615,180 | 5.9% |
| EXTENDED_ARG | 877,280 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 32,432,120 | 33.8% |
| STORE_FAST | 29,560,977 | 30.8% |
| ENTER_EXECUTOR | 12,046,400 | 12.6% |
| LOAD_FAST | 7,397,569 | 7.7% |
| LOAD_CONST | 4,239,259 | 4.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 830,786,549 | 51.6% |
| LOAD_ATTR_INSTANCE_VALUE | 315,771,863 | 19.6% |
| LOAD_CONST | 115,234,011 | 7.2% |
| LOAD_GLOBAL_MODULE | 62,831,099 | 3.9% |
| LOAD_ATTR_SLOT | 57,078,457 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 905,699,652 | 56.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 156,384,878 | 9.7% |
| LOAD_CONST | 152,604,790 | 9.5% |
| CALL_PY_EXACT_ARGS | 124,483,544 | 7.7% |
| LOAD_FAST_LOAD_FAST | 87,918,768 | 5.5% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,657,838,884 | 76.3% |
| LOAD_ATTR_SLOT | 122,726,375 | 5.6% |
| LOAD_ATTR_INSTANCE_VALUE | 104,348,545 | 4.8% |
| ENTER_EXECUTOR | 86,540,348 | 4.0% |
| LOAD_ATTR | 60,813,596 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 863,684,451 | 39.8% |
| CALL_PY_EXACT_ARGS | 602,328,214 | 27.7% |
| LOAD_FAST_LOAD_FAST | 527,964,238 | 24.3% |
| LOAD_CONST | 61,809,996 | 2.8% |
| LOAD_GLOBAL_MODULE | 60,947,309 | 2.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 520,125,218 | 96.7% |
| LOAD_ATTR_MODULE | 12,055,102 | 2.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,766,640 | 0.3% |
| LOAD_ATTR_CLASS | 1,546,560 | 0.3% |
| LOAD_FAST_LOAD_FAST | 1,238,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 435,242,880 | 80.9% |
| CALL_ISINSTANCE | 33,701,633 | 6.3% |
| LOAD_ATTR_MODULE | 12,055,102 | 2.2% |
| LOAD_FAST | 10,867,673 | 2.0% |
| LOAD_FAST_LOAD_FAST | 9,445,248 | 1.8% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,278,435,091 | 25.0% |
| POP_JUMP_IF_FALSE | 1,171,955,761 | 22.9% |
| RESUME_CHECK | 1,131,064,535 | 22.1% |
| STORE_FAST | 566,252,613 | 11.1% |
| POP_JUMP_IF_TRUE | 146,547,340 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,173,205,396 | 62.1% |
| CALL_BUILTIN_FAST | 578,108,900 | 11.3% |
| CALL_ISINSTANCE | 375,498,267 | 7.4% |
| LOAD_ATTR | 297,839,808 | 5.8% |
| LOAD_DEREF | 160,627,731 | 3.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,257,158,144 | 32.2% |
| RESUME_CHECK | 519,119,332 | 13.3% |
| STORE_FAST | 513,276,338 | 13.1% |
| POP_JUMP_IF_FALSE | 378,790,492 | 9.7% |
| LOAD_FAST_LOAD_FAST | 143,962,552 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 620,554,775 | 15.9% |
| LOAD_FAST_LOAD_FAST | 579,889,071 | 14.9% |
| CALL_ISINSTANCE | 546,656,206 | 14.0% |
| LOAD_ATTR_MODULE | 520,125,218 | 13.3% |
| CONTAINS_OP | 285,065,970 | 7.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,946,795,076 | 41.1% |
| CACHE | 1,708,611,812 | 23.9% |
| SEND_GEN | 529,708,888 | 7.4% |
| POP_TOP | 397,701,967 | 5.6% |
| COPY_FREE_VARS | 285,378,477 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,949,000,842 | 41.2% |
| LOAD_GLOBAL_BUILTIN | 1,131,064,535 | 15.8% |
| POP_TOP | 743,764,161 | 10.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 545,597,651 | 7.6% |
| LOAD_GLOBAL_MODULE | 519,119,332 | 7.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 546,879,934 | 48.5% |
| LOAD_FAST_LOAD_FAST | 401,469,492 | 35.6% |
| SWAP | 95,219,385 | 8.4% |
| BINARY_SUBSCR_LIST_INT | 36,129,520 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 17,061,760 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 418,181,330 | 37.1% |
| RETURN_CONST | 227,231,564 | 20.2% |
| LOAD_FAST_LOAD_FAST | 221,136,135 | 19.6% |
| LOAD_CONST | 116,207,530 | 10.3% |
| NOP | 72,414,156 | 6.4% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 125,240,907 | 48.4% |
| LOAD_FAST | 87,293,520 | 33.7% |
| CALL_BUILTIN_O | 14,732,720 | 5.7% |
| RETURN_VALUE | 8,130,900 | 3.1% |
| BINARY_SUBSCR_TUPLE_INT | 5,092,440 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 97,407,178 | 37.6% |
| LOAD_FAST | 86,565,745 | 33.5% |
| RETURN_CONST | 23,098,213 | 8.9% |
| ENTER_EXECUTOR | 17,753,211 | 6.9% |
| JUMP_BACKWARD | 17,041,917 | 6.6% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 1,066,510,644 | 24.2% |
| LOAD_FAST | 942,161,963 | 21.4% |
| LOAD_ATTR_INSTANCE_VALUE | 673,388,351 | 15.3% |
| CALL_BUILTIN_FAST | 651,578,182 | 14.8% |
| RETURN_VALUE | 350,766,922 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,188,374,510 | 72.4% |
| POP_JUMP_IF_TRUE | 1,038,719,806 | 23.6% |
| EXTENDED_ARG | 114,766,609 | 2.6% |
| UNARY_NOT | 63,184,045 | 1.4% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 18,040 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 218,099,869 | 34.5% |
| LOAD_ATTR_SLOT | 213,315,686 | 33.7% |
| LOAD_ATTR_INSTANCE_VALUE | 91,419,286 | 14.4% |
| LOAD_ATTR | 47,056,591 | 7.4% |
| RETURN_CONST | 18,545,220 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 532,082,439 | 84.1% |
| POP_JUMP_IF_TRUE | 98,272,372 | 15.5% |
| EXTENDED_ARG | 1,382,260 | 0.2% |
| TO_BOOL_ALWAYS_TRUE | 912,391 | 0.1% |
| TO_BOOL | 167,411 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 267,295,932 | 46.9% |
| RETURN_VALUE | 132,575,888 | 23.2% |
| FOR_ITER_LIST | 90,453,075 | 15.9% |
| LOAD_FAST | 48,731,904 | 8.5% |
| BINARY_SUBSCR_LIST_INT | 19,960,140 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 502,768,838 | 88.2% |
| STORE_FAST | 50,046,457 | 8.8% |
| STORE_FAST_LOAD_FAST | 12,249,620 | 2.1% |
| STORE_DEREF | 3,579,820 | 0.6% |
| LOAD_FAST | 1,210,002 | 0.2% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 63,184,045 | 87.4% |
| TO_BOOL_LIST | 4,191,721 | 5.8% |
| COMPARE_OP | 3,442,623 | 4.8% |
| TO_BOOL_INT | 574,405 | 0.8% |
| TO_BOOL_STR | 492,880 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 29,280,560 | 40.5% |
| RETURN_VALUE | 25,656,995 | 35.5% |
| LOAD_CONST | 13,722,966 | 19.0% |
| STORE_FAST | 1,193,968 | 1.7% |
| CALL_PY_EXACT_ARGS | 1,004,820 | 1.4% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 290,206,230 | 24.4% |
| COPY | 277,581,361 | 23.3% |
| SWAP | 116,984,271 | 9.8% |
| LOAD_CONST | 109,043,929 | 9.2% |
| LOAD_FAST_LOAD_FAST | 101,442,580 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 279,423,873 | 23.5% |
| COPY | 277,581,361 | 23.3% |
| BINARY_SUBSCR_LIST_INT | 159,144,720 | 13.4% |
| BINARY_SUBSCR | 116,013,305 | 9.7% |
| COMPARE_OP_INT | 112,854,076 | 9.5% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 114,766,609 | 27.1% |
| LOAD_FAST | 56,662,040 | 13.4% |
| JUMP_BACKWARD | 43,321,771 | 10.2% |
| CALL_LIST_APPEND | 41,813,032 | 9.9% |
| POP_TOP | 34,367,700 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 161,961,646 | 38.2% |
| ENTER_EXECUTOR | 80,439,198 | 19.0% |
| POP_JUMP_IF_NONE | 48,439,406 | 11.4% |
| FOR_ITER_GEN | 34,084,480 | 8.0% |
| FOR_ITER | 27,478,282 | 6.5% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 283,982,221 | 26.3% |
| BINARY_OP_ADD_FLOAT | 142,677,979 | 13.2% |
| LOAD_FAST | 135,921,902 | 12.6% |
| BINARY_OP_ADD_INT | 108,444,937 | 10.0% |
| BINARY_OP_SUBTRACT_FLOAT | 74,443,752 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 283,982,221 | 26.3% |
| STORE_SUBSCR_LIST_INT | 165,545,580 | 15.3% |
| COPY | 116,984,271 | 10.8% |
| STORE_SUBSCR | 116,023,585 | 10.7% |
| STORE_ATTR_INSTANCE_VALUE | 95,219,385 | 8.8% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 877,694,582 | 66.2% |
| LOAD_FAST | 185,506,133 | 14.0% |
| LOAD_FAST_LOAD_FAST | 118,336,203 | 8.9% |
| END_SEND | 38,845,400 | 2.9% |
| BINARY_OP_MULTIPLY_INT | 30,460,432 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 439,560,733 | 33.2% |
| LOAD_CONST | 153,259,731 | 11.6% |
| SWAP | 108,444,937 | 8.2% |
| RETURN_VALUE | 100,484,665 | 7.6% |
| LOAD_FAST_LOAD_FAST | 84,318,000 | 6.4% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 347,183,853 | 75.3% |
| LOAD_FAST | 67,627,988 | 14.7% |
| LOAD_FAST_LOAD_FAST | 30,860,508 | 6.7% |
| LOAD_ATTR_INSTANCE_VALUE | 9,328,860 | 2.0% |
| CALL_LEN | 3,690,220 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 112,957,920 | 24.5% |
| STORE_FAST | 86,340,322 | 18.7% |
| SWAP | 60,199,443 | 13.1% |
| RETURN_VALUE | 53,414,298 | 11.6% |
| LOAD_CONST | 42,929,052 | 9.3% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,879,431 | 35.7% |
| COPY | 159,144,720 | 20.2% |
| LOAD_FAST_LOAD_FAST | 141,944,192 | 18.0% |
| LOAD_CONST | 102,808,855 | 13.1% |
| UNARY_NEGATIVE | 34,943,080 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 148,856,385 | 19.0% |
| LOAD_CONST | 143,224,462 | 18.3% |
| STORE_FAST | 124,347,378 | 15.9% |
| RETURN_VALUE | 115,515,008 | 14.7% |
| LOAD_ATTR_INSTANCE_VALUE | 48,825,360 | 6.2% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 697,978,309 | 45.4% |
| LOAD_FAST_LOAD_FAST | 150,021,298 | 9.8% |
| LOAD_FAST | 149,152,993 | 9.7% |
| LOAD_ATTR_INSTANCE_VALUE | 141,057,744 | 9.2% |
| COPY | 112,854,076 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,285,257,921 | 83.6% |
| POP_JUMP_IF_TRUE | 151,420,931 | 9.8% |
| RETURN_VALUE | 37,571,207 | 2.4% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 19,422,780 | 1.3% |
| LOAD_FAST | 14,461,540 | 0.9% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,179,845,918 | 87.0% |
| LOAD_FAST_LOAD_FAST | 325,881,945 | 6.8% |
| COPY | 94,979,405 | 2.0% |
| LOAD_ATTR_INSTANCE_VALUE | 56,772,006 | 1.2% |
| ENTER_EXECUTOR | 53,324,242 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,179,209,658 | 24.6% |
| TO_BOOL_BOOL | 673,388,351 | 14.0% |
| STORE_FAST | 365,322,933 | 7.6% |
| LOAD_ATTR_METHOD_NO_DICT | 315,771,863 | 6.6% |
| RETURN_VALUE | 274,047,969 | 5.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 165,545,580 | 53.3% |
| LOAD_FAST_LOAD_FAST | 48,548,606 | 15.6% |
| LOAD_CONST | 35,792,598 | 11.5% |
| LOAD_FAST | 33,500,353 | 10.8% |
| BINARY_SUBSCR_LIST_INT | 26,894,680 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 119,712,120 | 38.5% |
| LOAD_FAST_LOAD_FAST | 75,194,220 | 24.2% |
| ENTER_EXECUTOR | 61,470,780 | 19.8% |
| JUMP_BACKWARD | 47,752,199 | 15.4% |
| RETURN_CONST | 6,015,780 | 1.9% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 97,349,132 | 54.9% |
| BUILD_SLICE | 71,237,639 | 40.1% |
| LOAD_CONST | 7,355,780 | 4.1% |
| LOAD_FAST | 1,362,152 | 0.8% |
| LOAD_ATTR_SLOT | 88,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,443,843 | 80.9% |
| LOAD_CONST | 24,226,926 | 13.7% |
| JUMP_FORWARD | 7,041,280 | 4.0% |
| ENTER_EXECUTOR | 1,111,360 | 0.6% |
| RETURN_CONST | 721,346 | 0.4% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 138,348,886 | 90.8% |
| LOAD_FAST | 7,041,348 | 4.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,898,580 | 1.2% |
| LOAD_ATTR_MODULE | 1,765,760 | 1.2% |
| RETURN_VALUE | 1,389,580 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 76,156,441 | 50.0% |
| BUILD_STRING | 68,262,425 | 44.8% |
| LOAD_FAST | 7,864,898 | 5.2% |
| LOAD_GLOBAL_MODULE | 11,640 | 0.0% |
| LOAD_GLOBAL | 120 | 0.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 68,262,425 | 88.9% |
| LOAD_CONST | 8,559,191 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 48,929,440 | 63.7% |
| CALL | 15,956,460 | 20.8% |
| STORE_FAST | 4,717,430 | 6.1% |
| BINARY_OP_ADD_UNICODE | 2,681,520 | 3.5% |
| CALL_LIST_APPEND | 1,864,080 | 2.4% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 246,503,998 | 93.4% |
| ENTER_EXECUTOR | 17,318,704 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 124,344,030 | 47.1% |
| STORE_FAST | 65,167,709 | 24.7% |
| RETURN_VALUE | 27,106,140 | 10.3% |
| UNPACK_SEQUENCE_LIST | 14,181,920 | 5.4% |
| POP_TOP | 7,520,764 | 2.9% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 315,714,301 | 28.3% |
| LOAD_FAST_LOAD_FAST | 307,886,811 | 27.6% |
| LOAD_GLOBAL_MODULE | 285,065,970 | 25.6% |
| BINARY_SUBSCR_DICT | 78,260,500 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 54,772,645 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 968,289,322 | 86.8% |
| POP_JUMP_IF_TRUE | 76,996,762 | 6.9% |
| RETURN_VALUE | 34,356,948 | 3.1% |
| COPY | 28,364,440 | 2.5% |
| EXTENDED_ARG | 4,153,480 | 0.4% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,759,160 | 83.7% |
| LOAD_ATTR | 15,441,320 | 11.2% |
| CALL_METHOD_DESCRIPTOR_O | 2,681,260 | 1.9% |
| RETURN_VALUE | 2,058,840 | 1.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,138,100 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 138,348,886 | 100.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,639,982 | 45.0% |
| BINARY_SLICE | 20,771,700 | 21.4% |
| LOAD_CONST | 14,872,700 | 15.3% |
| CALL_STR_1 | 6,403,040 | 6.6% |
| BUILD_STRING | 2,681,520 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,511,662 | 22.2% |
| CALL_BUILTIN_O | 21,212,480 | 21.9% |
| BUILD_TUPLE | 20,613,200 | 21.3% |
| LOAD_CONST | 11,487,160 | 11.9% |
| STORE_FAST | 10,455,806 | 10.8% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 215,948,299 | 96.9% |
| LOAD_FAST | 6,993,462 | 3.1% |
| LOAD_FAST_LOAD_FAST | 19,400 | 0.0% |
| BINARY_SUBSCR | 8,556 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 96,160,224 | 43.1% |
| LOAD_GLOBAL_MODULE | 40,559,740 | 18.2% |
| STORE_FAST | 12,697,942 | 5.7% |
| LOAD_CONST | 9,947,351 | 4.5% |
| LOAD_FAST | 9,151,218 | 4.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 270,674,333 | 69.6% |
| LOAD_ATTR_INSTANCE_VALUE | 56,495,148 | 14.5% |
| LOAD_DEREF | 27,299,299 | 7.0% |
| LOAD_ATTR_SLOT | 11,495,560 | 3.0% |
| BINARY_SUBSCR_DICT | 6,101,000 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 106,709,258 | 27.4% |
| LOAD_FAST | 58,080,595 | 14.9% |
| COMPARE_OP_INT | 52,757,288 | 13.6% |
| STORE_FAST | 50,212,838 | 12.9% |
| CALL_BUILTIN_CLASS | 31,405,440 | 8.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 338,965,701 | 81.0% |
| CALL | 44,075,877 | 10.5% |
| LOAD_GLOBAL_MODULE | 7,618,200 | 1.8% |
| LOAD_ATTR | 4,016,820 | 1.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 3,902,380 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 274,714,189 | 65.7% |
| BINARY_OP | 96,003,000 | 23.0% |
| RETURN_VALUE | 23,263,814 | 5.6% |
| LOAD_FAST | 8,345,780 | 2.0% |
| STORE_FAST | 4,461,773 | 1.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 340,290,634 | 46.8% |
| GET_ITER | 250,328,476 | 34.4% |
| LOAD_FAST | 82,691,521 | 11.4% |
| SWAP | 30,118,564 | 4.1% |
| EXTENDED_ARG | 22,318,512 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 261,592,600 | 36.0% |
| RETURN_CONST | 138,601,780 | 19.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 90,453,075 | 12.4% |
| LOAD_FAST | 88,892,057 | 12.2% |
| LOAD_FAST_LOAD_FAST | 65,614,582 | 9.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 168,992,900 | 49.0% |
| ENTER_EXECUTOR | 167,238,336 | 48.5% |
| SWAP | 4,352,297 | 1.3% |
| LOAD_FAST | 2,222,948 | 0.6% |
| FOR_ITER_LIST | 1,315,276 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 168,830,624 | 48.9% |
| LOAD_FAST | 92,106,951 | 26.7% |
| LOAD_FAST_LOAD_FAST | 45,853,940 | 13.3% |
| RETURN_CONST | 20,444,327 | 5.9% |
| LOAD_GLOBAL_MODULE | 5,902,029 | 1.7% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40,831,560 | 68.9% |
| LOAD_FAST | 18,446,156 | 31.1% |
| RETURN_VALUE | 3,800 | 0.0% |
| LOAD_ATTR | 1,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,331,678 | 79.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,921,441 | 16.7% |
| LOAD_FAST_LOAD_FAST | 1,638,360 | 2.8% |
| CALL | 226,197 | 0.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 125,840 | 0.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 148,802,020 | 90.9% |
| LOAD_FAST_LOAD_FAST | 11,901,438 | 7.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,358,954 | 0.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,014,731 | 0.6% |
| ENTER_EXECUTOR | 469,768 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,012,062 | 25.0% |
| GET_ITER | 25,700,680 | 15.7% |
| LOAD_GLOBAL_BUILTIN | 20,518,820 | 12.5% |
| LOAD_ATTR_METHOD_NO_DICT | 12,596,740 | 7.7% |
| LOAD_FAST_LOAD_FAST | 11,971,580 | 7.3% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,751,215,294 | 91.3% |
| LOAD_ATTR_SLOT | 54,753,486 | 2.9% |
| COPY | 45,868,052 | 2.4% |
| ENTER_EXECUTOR | 18,762,547 | 1.0% |
| LOAD_DEREF | 17,094,140 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 449,458,573 | 23.4% |
| TO_BOOL_NONE | 213,315,686 | 11.1% |
| COMPARE_OP_FLOAT | 128,333,484 | 6.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 122,726,375 | 6.4% |
| RETURN_VALUE | 87,607,167 | 4.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 885,093,299 | 50.6% |
| LOAD_FAST | 813,580,362 | 46.5% |
| SWAP | 45,868,052 | 2.6% |
| STORE_ATTR_SLOT | 3,010,331 | 0.2% |
| LOAD_ATTR_SLOT | 848,420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 515,497,157 | 29.5% |
| LOAD_CONST | 401,597,768 | 23.0% |
| RETURN_CONST | 385,912,033 | 22.1% |
| LOAD_FAST | 362,444,156 | 20.7% |
| LOAD_GLOBAL_BUILTIN | 33,864,364 | 1.9% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,457,566 | 63.9% |
| LOAD_ATTR_INSTANCE_VALUE | 54,101,681 | 29.4% |
| LOAD_ATTR_SLOT | 6,507,680 | 3.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,285,220 | 1.2% |
| COPY | 1,124,740 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 95,095,122 | 51.7% |
| POP_JUMP_IF_TRUE | 83,282,197 | 45.3% |
| UNARY_NOT | 4,191,721 | 2.3% |
| EXTENDED_ARG | 1,303,800 | 0.7% |
| TO_BOOL | 30,920 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 345,372,827 | 64.8% |
| LOAD_FAST | 136,095,581 | 25.5% |
| YIELD_VALUE | 33,453,160 | 6.3% |
| FOR_ITER | 8,306,140 | 1.6% |
| BINARY_SUBSCR_DICT | 6,550,620 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 337,773,694 | 63.4% |
| STORE_FAST_STORE_FAST | 194,834,681 | 36.5% |
| LOAD_FAST | 387,280 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 0.0% |
| UNPACK_SEQUENCE_LIST | 33,880 | 0.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,225,387 | 88.7% |
| LOAD_FAST_LOAD_FAST | 10,670,209 | 6.6% |
| LOAD_GLOBAL_MODULE | 4,028,921 | 2.5% |
| BINARY_SUBSCR_TUPLE_INT | 1,607,500 | 1.0% |
| CALL_LEN | 927,540 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 105,861,200 | 65.6% |
| BINARY_SUBSCR_LIST_INT | 34,943,080 | 21.6% |
| CALL_PY_EXACT_ARGS | 4,254,800 | 2.6% |
| BINARY_SUBSCR | 3,225,560 | 2.0% |
| STORE_SUBSCR | 3,225,520 | 2.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,257,521 | 60.2% |
| RETURN_VALUE | 3,343,976 | 32.2% |
| LOAD_GLOBAL_MODULE | 282,044 | 2.7% |
| LOAD_FAST | 193,540 | 1.9% |
| LOAD_ATTR_WITH_HINT | 176,680 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 9,467,461 | 91.1% |
| STORE_FAST | 919,024 | 8.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 0.0% |
| UNPACK_SEQUENCE | 160 | 0.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 141,380,052 | 45.0% |
| RETURN_VALUE | 108,959,661 | 34.7% |
| RETURN_CONST | 63,988,930 | 20.4% |
| SEND_GEN | 15,180 | 0.0% |
| JUMP_BACKWARD | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 129,802,966 | 41.3% |
| POP_TOP | 94,412,297 | 30.0% |
| BINARY_OP_ADD_INT | 38,845,400 | 12.4% |
| LOAD_GLOBAL_MODULE | 38,845,400 | 12.4% |
| LOAD_FAST | 8,588,043 | 2.7% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 194,119,622 | 48.8% |
| COPY_FREE_VARS | 107,088,098 | 26.9% |
| CACHE | 46,716,651 | 11.7% |
| ENTER_EXECUTOR | 36,469,360 | 9.2% |
| CALL_PY_WITH_DEFAULTS | 8,945,409 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 130,265,947 | 32.8% |
| GET_ITER | 50,228,880 | 12.6% |
| INTERPRETER_EXIT | 46,729,454 | 11.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 43,093,243 | 10.8% |
| CALL | 38,859,022 | 9.8% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 14,363,810 | 92.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 614,180 | 3.9% |
| LOAD_ATTR_MODULE | 407,428 | 2.6% |
| LOAD_FAST | 175,180 | 1.1% |
| LOAD_FAST_LOAD_FAST | 9,420 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 15,570,358 | 100.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_FAST | 40 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,942,183 | 96.9% |
| RETURN_VALUE | 502,240 | 1.3% |
| LOAD_ATTR_INSTANCE_VALUE | 291,494 | 0.8% |
| LOAD_DEREF | 270,572 | 0.7% |
| LOAD_GLOBAL_MODULE | 40,598 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 38,106,715 | 100.0% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 130,265,947 | 85.6% |
| LOAD_FAST | 8,732,701 | 5.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,638,980 | 2.4% |
| RETURN_VALUE | 3,443,408 | 2.3% |
| BEFORE_ASYNC_WITH | 3,005,932 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 152,094,985 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 9,837,097 | 84.5% |
| STORE_FAST | 1,584,200 | 13.6% |
| STORE_DEREF | 185,686 | 1.6% |
| STORE_NAME | 35,660 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,491,103 | 81.5% |
| STORE_DEREF | 2,092,400 | 18.0% |
| STORE_NAME | 58,940 | 0.5% |
| EXTENDED_ARG | 2,540 | 0.0% |
| PUSH_EXC_INFO | 200 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,404,550 | 100.0% |
| ENTER_EXECUTOR | 100 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 9,837,097 | 94.5% |
| STORE_FAST | 554,173 | 5.3% |
| STORE_NAME | 11,320 | 0.1% |
| CALL_INTRINSIC_1 | 1,580 | 0.0% |
| STORE_DEREF | 320 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 545,597,651 | 100.0% |
| RESUME | 5,170 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 529,725,014 | 97.1% |
| SEND | 15,877,807 | 2.9% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 33,733,752 | 31.6% |
| RETURN_VALUE | 20,300,385 | 19.0% |
| RETURN_GENERATOR | 17,923,920 | 16.8% |
| LOAD_FAST | 13,365,205 | 12.5% |
| CALL | 7,051,180 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 78,598,679 | 73.7% |
| JUMP_BACKWARD | 27,864,280 | 26.1% |
| LOAD_FAST | 128,000 | 0.1% |
| CALL_INTRINSIC_1 | 15,520 | 0.0% |
| LOAD_NAME | 4,820 | 0.0% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 56,685,213 | 70.1% |
| LOAD_FAST_AND_CLEAR | 24,133,881 | 29.9% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 56,674,253 | 70.1% |
| LOAD_FAST_AND_CLEAR | 24,133,881 | 29.9% |
| MAKE_CELL | 11,040 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,911,254 | 41.9% |
| POP_TOP | 2,769,312 | 23.6% |
| LOAD_ATTR_METHOD_NO_DICT | 1,627,056 | 13.9% |
| POP_JUMP_IF_NONE | 983,729 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 565,540 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,771,614 | 40.7% |
| POP_JUMP_IF_NOT_NONE | 2,041,280 | 17.4% |
| CALL_LIST_APPEND | 1,564,660 | 13.4% |
| LOAD_FAST | 1,210,112 | 10.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 575,920 | 4.9% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,099,680 | 52.7% |
| LOAD_ATTR_MODULE | 778,140 | 19.5% |
| LOAD_GLOBAL_BUILTIN | 724,160 | 18.2% |
| LOAD_FAST | 201,600 | 5.1% |
| RETURN_VALUE | 73,920 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 3,179,567 | 79.9% |
| COPY | 596,580 | 15.0% |
| LOAD_CONST | 201,860 | 5.1% |
| CALL_INTRINSIC_1 | 2 | 0.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 1,718,808 | 59.5% |
| POP_TOP | 516,120 | 17.9% |
| POP_JUMP_IF_FALSE | 209,360 | 7.3% |
| DELETE_FAST | 201,919 | 7.0% |
| POP_JUMP_IF_TRUE | 183,269 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,490,350 | 56.1% |
| COPY | 1,110,708 | 41.8% |
| CALL_INTRINSIC_1 | 56,520 | 2.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 17,161,673 | 42.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,249,620 | 30.2% |
| FOR_ITER_TUPLE | 5,055,362 | 12.4% |
| FOR_ITER | 4,053,474 | 10.0% |
| FOR_ITER_RANGE | 1,055,420 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 12,390,533 | 30.5% |
| TO_BOOL_ALWAYS_TRUE | 4,836,020 | 11.9% |
| LOAD_ATTR_SLOT | 4,234,271 | 10.4% |
| LOAD_CONST | 3,505,804 | 8.6% |
| LOAD_FAST | 2,694,916 | 6.6% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 6,936,320 | 99.9% |
| RETURN_VALUE | 2,780 | 0.0% |
| LOAD_ATTR | 760 | 0.0% |
| LOAD_FAST | 520 | 0.0% |
| CALL | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,225,320 | 75.3% |
| LOAD_GLOBAL_MODULE | 1,713,440 | 24.7% |
| LOAD_CONST | 2,000 | 0.0% |
| LOAD_GLOBAL | 400 | 0.0% |
| RETURN_CONST | 220 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 529,744,593 | 40.6% |
| ENTER_EXECUTOR | 366,556,559 | 28.1% |
| CALL_INTRINSIC_1 | 120,273,200 | 9.2% |
| LOAD_FAST | 64,446,096 | 4.9% |
| LOAD_ATTR_INSTANCE_VALUE | 42,112,600 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 634,170,443 | 48.6% |
| YIELD_VALUE | 529,744,593 | 40.6% |
| STORE_FAST | 102,368,494 | 7.8% |
| UNPACK_SEQUENCE_TUPLE | 33,453,160 | 2.6% |
| STORE_DEREF | 3,225,580 | 0.2% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 245,989,263 | 62.3% |
| LOAD_FAST | 91,520,266 | 23.2% |
| RETURN_VALUE | 23,049,480 | 5.8% |
| BINARY_OP_MULTIPLY_INT | 11,249,600 | 2.9% |
| BINARY_OP | 8,323,262 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 142,677,979 | 36.1% |
| STORE_FAST | 90,852,512 | 23.0% |
| LOAD_FAST | 68,007,159 | 17.2% |
| RETURN_VALUE | 41,800,520 | 10.6% |
| LOAD_FAST_LOAD_FAST | 23,126,620 | 5.9% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 55,520,460 | 29.1% |
| LOAD_CONST | 54,707,666 | 28.7% |
| ENTER_EXECUTOR | 41,458,620 | 21.7% |
| BUILD_TUPLE | 30,733,740 | 16.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,473,280 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 189,508,086 | 99.3% |
| MAKE_CELL | 1,100,014 | 0.6% |
| COPY_FREE_VARS | 263,960 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 7,680 | 0.0% |
| CONTAINS_OP | 6,060 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 83,599,102 | 39.1% |
| LOAD_CONST | 47,207,042 | 22.1% |
| BINARY_OP_MULTIPLY_INT | 30,018,280 | 14.1% |
| PUSH_NULL | 13,060,315 | 6.1% |
| RETURN_VALUE | 6,943,000 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 169,063,318 | 79.2% |
| COPY_FREE_VARS | 37,063,652 | 17.4% |
| GET_AWAITABLE | 3,005,412 | 1.4% |
| POP_TOP | 2,780,110 | 1.3% |
| MAKE_CELL | 885,336 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 43,000,867 | 78.7% |
| LOAD_ATTR_METHOD_NO_DICT | 5,553,095 | 10.2% |
| LOAD_FAST | 3,868,756 | 7.1% |
| LOAD_FAST_LOAD_FAST | 1,371,039 | 2.5% |
| LOAD_ATTR | 387,060 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 39,493,747 | 72.3% |
| CALL_METHOD_DESCRIPTOR_O | 3,902,380 | 7.1% |
| RETURN_VALUE | 3,007,760 | 5.5% |
| BINARY_OP | 2,681,320 | 4.9% |
| POP_TOP | 1,518,222 | 2.8% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 300,150,918 | 88.3% |
| LOAD_FAST | 11,648,112 | 3.4% |
| LOAD_FAST_LOAD_FAST | 10,973,280 | 3.2% |
| RETURN_VALUE | 5,383,260 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 3,750,082 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 293,062,340 | 86.2% |
| POP_JUMP_IF_TRUE | 33,165,870 | 9.8% |
| RETURN_VALUE | 5,871,706 | 1.7% |
| COPY | 4,887,016 | 1.4% |
| EXTENDED_ARG | 1,635,880 | 0.5% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 90,965,105 | 77.3% |
| LOAD_GLOBAL_BUILTIN | 22,935,704 | 19.5% |
| LOAD_FAST | 1,979,044 | 1.7% |
| ENTER_EXECUTOR | 770,940 | 0.7% |
| LOAD_ATTR_MODULE | 676,124 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 29,123,892 | 24.8% |
| LOAD_FAST_LOAD_FAST | 23,132,864 | 19.7% |
| LOAD_FAST | 19,184,115 | 16.3% |
| COMPARE_OP_INT | 15,527,496 | 13.2% |
| PUSH_NULL | 11,047,000 | 9.4% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 166,733,254 | 100.0% |
| LOAD_DEREF | 12,040 | 0.0% |
| LOAD_SUPER_ATTR | 8,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 93,116,976 | 55.8% |
| LOAD_FAST | 49,236,124 | 29.5% |
| CALL_PY_EXACT_ARGS | 14,346,863 | 8.6% |
| CALL_PY_WITH_DEFAULTS | 7,932,960 | 4.8% |
| LOAD_GLOBAL_MODULE | 861,471 | 0.5% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 529,725,014 | 75.4% |
| LOAD_CONST | 172,985,139 | 24.6% |
| SEND | 6,215 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 529,708,888 | 75.4% |
| POP_TOP | 172,972,899 | 24.6% |
| END_SEND | 15,180 | 0.0% |
| YIELD_VALUE | 15,140 | 0.0% |
| RESUME | 3,681 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 136,832,218 | 65.7% |
| COPY | 17,278,411 | 8.3% |
| CALL_BUILTIN_O | 17,121,860 | 8.2% |
| BINARY_OP | 12,360,922 | 5.9% |
| LOAD_ATTR_SLOT | 9,236,440 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 161,831,517 | 77.7% |
| POP_JUMP_IF_TRUE | 45,746,865 | 22.0% |
| UNARY_NOT | 574,405 | 0.3% |
| EXTENDED_ARG | 218,626 | 0.1% |
| TO_BOOL_BOOL | 18,400 | 0.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 128,333,484 | 68.4% |
| BINARY_SUBSCR | 31,176,840 | 16.6% |
| LOAD_GLOBAL_MODULE | 8,575,499 | 4.6% |
| LOAD_CONST | 8,437,278 | 4.5% |
| LOAD_FAST | 4,055,978 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 128,319,704 | 68.4% |
| POP_JUMP_IF_TRUE | 43,210,860 | 23.0% |
| POP_JUMP_IF_FALSE | 16,092,986 | 8.6% |
| COMPARE_OP | 500 | 0.0% |
| EXTENDED_ARG | 302 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 289,077,260 | 50.2% |
| LOAD_ATTR_INSTANCE_VALUE | 155,948,200 | 27.1% |
| LOAD_FAST_LOAD_FAST | 38,907,460 | 6.8% |
| ENTER_EXECUTOR | 31,071,420 | 5.4% |
| BINARY_SUBSCR | 26,268,940 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 245,989,263 | 42.7% |
| BINARY_OP_SUBTRACT_FLOAT | 96,946,560 | 16.8% |
| LOAD_FAST | 82,954,672 | 14.4% |
| YIELD_VALUE | 41,716,800 | 7.2% |
| STORE_FAST | 33,624,920 | 5.8% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 70,666,787 | 28.4% |
| LOAD_ATTR_INSTANCE_VALUE | 65,382,960 | 26.3% |
| LOAD_FAST_LOAD_FAST | 53,051,181 | 21.3% |
| BINARY_OP | 36,447,165 | 14.6% |
| LOAD_FAST | 12,025,909 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,404,666 | 23.9% |
| LOAD_CONST | 57,257,088 | 23.0% |
| LOAD_FAST_LOAD_FAST | 32,378,466 | 13.0% |
| BINARY_OP_ADD_INT | 30,460,432 | 12.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 30,018,280 | 12.1% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 76,107,172 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 48,922,740 | 64.3% |
| LOAD_FAST | 25,972,730 | 34.1% |
| RETURN_CONST | 1,054,740 | 1.4% |
| JUMP_BACKWARD | 134,080 | 0.2% |
| LOAD_CONST | 8,000 | 0.0% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 32,000,360 | 87.0% |
| RETURN_GENERATOR | 4,562,744 | 12.4% |
| BINARY_SUBSCR | 185,800 | 0.5% |
| LOAD_FAST | 9,440 | 0.0% |
| RETURN_VALUE | 7,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 36,767,784 | 100.0% |


</details>

### LOAD_LOCALS

<details>
<summary> Successors and predecessors for LOAD_LOCALS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,840 | 47.7% |
| STORE_NAME | 1,780 | 46.1% |
| LOAD_CONST | 240 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FROM_DICT_OR_DEREF | 3,840 | 99.5% |
| STORE_DEREF | 20 | 0.5% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 184,309 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 183,100 | 99.3% |
| TO_BOOL_BOOL | 960 | 0.5% |
| TO_BOOL | 249 | 0.1% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,332,316 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,474,694 | 44.4% |
| LOAD_FAST | 3,144,683 | 25.5% |
| LOAD_FAST_LOAD_FAST | 2,272,240 | 18.4% |
| STORE_FAST | 697,650 | 5.7% |
| CALL_METHOD_DESCRIPTOR_O | 255,200 | 2.1% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,029,840 | 78.0% |
| LOAD_CONST | 190,280 | 7.3% |
| LOAD_GLOBAL_MODULE | 189,810 | 7.3% |
| LOAD_FAST | 102,794 | 3.9% |
| LOAD_ATTR | 89,040 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,029,840 | 78.0% |
| CONTAINS_OP | 190,770 | 7.3% |
| LOAD_CONST | 99,220 | 3.8% |
| BINARY_OP | 91,520 | 3.5% |
| STORE_FAST | 64,580 | 2.5% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 94,738,332 | 98.8% |
| LOAD_FAST | 1,105,495 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 71,980 | 0.1% |
| BINARY_OP_ADD_INT | 2,120 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 71,237,639 | 74.3% |
| BINARY_SUBSCR | 24,676,508 | 25.7% |
| BINARY_SUBSCR_GETITEM | 3,840 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,362,906 | 100.0% |
| LOAD_GLOBAL_MODULE | 280 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,871,980 | 78.1% |
| NOP | 2,286,752 | 20.1% |
| RETURN_CONST | 201,414 | 1.8% |
| PUSH_EXC_INFO | 1,640 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,360 | 0.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,285,120 | 60.2% |
| STORE_FAST | 341,933 | 16.0% |
| CALL | 189,636 | 8.9% |
| POP_TOP | 104,970 | 4.9% |
| NOP | 64,936 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 648,420 | 30.4% |
| BUILD_LIST | 642,560 | 30.1% |
| RETURN_VALUE | 266,436 | 12.5% |
| RERAISE | 201,919 | 9.5% |
| RETURN_CONST | 129,630 | 6.1% |


</details>

### DELETE_NAME

<details>
<summary> Successors and predecessors for DELETE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 380 | 42.2% |
| FOR_ITER | 240 | 26.7% |
| STORE_NAME | 200 | 22.2% |
| POP_TOP | 40 | 4.4% |
| JUMP_FORWARD | 20 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 380 | 42.2% |
| LOAD_NAME | 140 | 15.6% |
| LOAD_BUILD_CLASS | 120 | 13.3% |
| LOAD_CONST | 120 | 13.3% |
| BUILD_LIST | 60 | 6.7% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40,598 | 62.3% |
| LOAD_FAST | 17,520 | 26.9% |
| MAP_ADD | 4,920 | 7.5% |
| BUILD_MAP | 764 | 1.2% |
| BUILD_CONST_KEY_MAP | 660 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,342 | 63.4% |
| DICT_MERGE | 17,520 | 26.9% |
| BUILD_MAP | 4,380 | 6.7% |
| STORE_FAST | 724 | 1.1% |
| STORE_NAME | 520 | 0.8% |


</details>

### LOAD_FROM_DICT_OR_DEREF

<details>
<summary> Successors and predecessors for LOAD_FROM_DICT_OR_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_LOCALS | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,600 | 41.7% |
| CALL_PY_EXACT_ARGS | 1,560 | 40.6% |
| LOAD_CONST | 240 | 6.2% |
| LOAD_ATTR | 200 | 5.2% |
| STORE_NAME | 160 | 4.2% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,194,640 | 36.8% |
| RETURN_VALUE | 8,511,240 | 14.8% |
| LOAD_FAST_LOAD_FAST | 8,303,063 | 14.4% |
| JUMP_FORWARD | 6,377,120 | 11.1% |
| STORE_FAST | 6,068,240 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,497,500 | 47.7% |
| JUMP_BACKWARD | 22,003,087 | 38.2% |
| ENTER_EXECUTOR | 6,414,940 | 11.1% |
| CALL_FUNCTION_EX | 1,615,440 | 2.8% |
| EXTENDED_ARG | 53,160 | 0.1% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 88,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 88,000 | 99.2% |
| STORE_FAST | 320 | 0.4% |
| STORE_NAME | 120 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.1% |
| CALL | 80 | 0.1% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 421,115,813 | 89.5% |
| BINARY_OP_SUBTRACT_INT | 14,186,040 | 3.0% |
| LOAD_ATTR_SLOT | 13,808,080 | 2.9% |
| LOAD_FAST | 7,809,540 | 1.7% |
| LOAD_CONST | 6,650,474 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 238,426,399 | 50.7% |
| STORE_FAST | 220,608,000 | 46.9% |
| LOAD_CONST | 5,991,880 | 1.3% |
| RETURN_VALUE | 4,367,000 | 0.9% |
| BINARY_OP_INPLACE_ADD_UNICODE | 307,120 | 0.1% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,840,008 | 73.2% |
| RETURN_VALUE | 8,776,840 | 21.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,640,620 | 4.0% |
| LOAD_ATTR_SLOT | 145,520 | 0.4% |
| CALL_TUPLE_1 | 88,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,435,428 | 30.5% |
| YIELD_VALUE | 10,243,140 | 25.1% |
| BINARY_OP_ADD_UNICODE | 6,403,040 | 15.7% |
| RETURN_VALUE | 4,545,660 | 11.2% |
| LOAD_FAST | 4,242,900 | 10.4% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,353,386 | 57.9% |
| RETURN_GENERATOR | 7,374,080 | 21.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,669 | 13.4% |
| LOAD_ATTR_SLOT | 1,464,688 | 4.2% |
| CALL | 585,500 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,089,020 | 54.3% |
| BINARY_OP | 4,799,429 | 13.6% |
| BUILD_TUPLE | 3,877,248 | 11.0% |
| YIELD_VALUE | 3,228,920 | 9.2% |
| STORE_FAST | 1,211,532 | 3.4% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 107,325,184 | 49.4% |
| GET_ITER | 75,708,971 | 34.9% |
| EXTENDED_ARG | 34,084,480 | 15.7% |
| LOAD_FAST | 56,160 | 0.0% |
| FOR_ITER | 2,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 140,915,704 | 64.9% |
| POP_TOP | 76,258,153 | 35.1% |
| RESUME | 2,180 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 920 | 0.0% |
| STORE_FAST | 640 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,492,347 | 86.2% |
| LOAD_FAST_LOAD_FAST | 4,357,126 | 5.3% |
| LOAD_DEREF | 3,109,100 | 3.7% |
| ENTER_EXECUTOR | 2,966,367 | 3.6% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,303,704 | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT | 11,182,910 | 13.5% |
| CALL_BUILTIN_O | 5,611,830 | 6.8% |
| CONTAINS_OP | 5,597,120 | 6.7% |
| CALL_PY_EXACT_ARGS | 4,361,700 | 5.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,633,879 | 77.5% |
| ENTER_EXECUTOR | 9,337,598 | 10.0% |
| LOAD_ATTR_SLOT | 6,457,532 | 6.9% |
| RETURN_VALUE | 2,412,376 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,204,544 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 76,980,984 | 82.2% |
| COPY_FREE_VARS | 5,278,715 | 5.6% |
| TO_BOOL_NONE | 4,445,006 | 4.7% |
| GET_ITER | 1,929,082 | 2.1% |
| RETURN_VALUE | 1,119,825 | 1.2% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 357,381,132 | 79.3% |
| LOAD_ATTR_INSTANCE_VALUE | 30,303,932 | 6.7% |
| LOAD_ATTR_WITH_HINT | 29,698,511 | 6.6% |
| COPY | 18,717,060 | 4.2% |
| LOAD_FAST_LOAD_FAST | 11,235,036 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 112,528,201 | 25.0% |
| STORE_FAST | 56,258,700 | 12.5% |
| COMPARE_OP_INT | 47,045,137 | 10.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 44,677,353 | 9.9% |
| LOAD_CONST | 38,959,934 | 8.6% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,173,127 | 98.2% |
| LOAD_DEREF | 77,440 | 1.8% |
| LOAD_SUPER_ATTR | 960 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 4,157,739 | 97.8% |
| LOAD_GLOBAL_MODULE | 87,928 | 2.1% |
| STORE_FAST | 5,760 | 0.1% |
| LOAD_GLOBAL | 200 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,964,395 | 48.5% |
| SWAP | 18,717,060 | 27.5% |
| LOAD_FAST_LOAD_FAST | 15,912,434 | 23.4% |
| LOAD_DEREF | 322,324 | 0.5% |
| ENTER_EXECUTOR | 15,620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,482,194 | 66.9% |
| ENTER_EXECUTOR | 7,082,080 | 10.4% |
| RETURN_CONST | 5,900,193 | 8.7% |
| LOAD_CONST | 5,227,810 | 7.7% |
| LOAD_FAST_LOAD_FAST | 3,077,280 | 4.5% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,633,705 | 30.8% |
| LOAD_ATTR_INSTANCE_VALUE | 75,949,068 | 30.5% |
| ENTER_EXECUTOR | 54,820,500 | 22.0% |
| LOAD_ATTR_SLOT | 23,534,700 | 9.5% |
| COPY | 9,559,520 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 136,646,191 | 54.9% |
| POP_JUMP_IF_TRUE | 109,997,935 | 44.2% |
| EXTENDED_ARG | 1,209,080 | 0.5% |
| TO_BOOL_NONE | 911,949 | 0.4% |
| TO_BOOL_ALWAYS_TRUE | 155,882 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,442,985 | 62.3% |
| LOAD_ATTR_SLOT | 9,521,020 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,790,920 | 7.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,026,180 | 5.2% |
| COPY | 3,678,536 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 41,271,124 | 53.0% |
| POP_JUMP_IF_TRUE | 35,939,080 | 46.2% |
| UNARY_NOT | 492,880 | 0.6% |
| TO_BOOL_NONE | 48,220 | 0.1% |
| EXTENDED_ARG | 22,280 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 130,490,861 | 88.0% |
| CALL_KW | 14,181,920 | 9.6% |
| STORE_FAST | 1,602,100 | 1.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,065,960 | 0.7% |
| ENTER_EXECUTOR | 327,680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 146,485,121 | 98.8% |
| STORE_FAST | 1,721,380 | 1.2% |
| UNPACK_SEQUENCE_TUPLE | 23,720 | 0.0% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 1,280,880 | 77.7% |
| STORE_FAST_LOAD_FAST | 144,000 | 8.7% |
| RETURN_VALUE | 93,860 | 5.7% |
| LOAD_ATTR_INSTANCE_VALUE | 63,180 | 3.8% |
| LOAD_FAST | 51,120 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,368,280 | 83.0% |
| JUMP_BACKWARD | 279,920 | 17.0% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,996,650 | 99.7% |
| LOAD_ATTR_WITH_HINT | 8,602 | 0.3% |
| CALL | 400 | 0.0% |
| LOAD_FAST | 160 | 0.0% |
| CALL_KW | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 3,005,932 | 100.0% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 462,400 | 61.2% |
| YIELD_VALUE | 291,340 | 38.5% |
| CALL_INTRINSIC_1 | 1,280 | 0.2% |
| FOR_ITER | 980 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 756,000 | 100.0% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 1,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 960 | 63.2% |
| CALL_INTRINSIC_1 | 320 | 21.1% |
| JUMP_BACKWARD | 240 | 15.8% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 920 | 69.7% |
| LOAD_CONST | 400 | 30.3% |


</details>

### SETUP_ANNOTATIONS

<details>
<summary> Successors and predecessors for SETUP_ANNOTATIONS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 340 | 65.4% |
| RESUME | 180 | 34.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 92.3% |
| LOAD_NAME | 40 | 7.7% |


</details>

### END_ASYNC_FOR

<details>
<summary> Successors and predecessors for END_ASYNC_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 8,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,242,460 | 65.5% |
| JUMP_BACKWARD | 2,757,460 | 34.5% |
| RETURN_CONST | 80 | 0.0% |


</details>

### GET_AITER

<details>
<summary> Successors and predecessors for GET_AITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,999,880 | 100.0% |
| RETURN_VALUE | 80 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ANEXT | 8,000,000 | 100.0% |


</details>

### GET_ANEXT

<details>
<summary> Successors and predecessors for GET_ANEXT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_AITER | 8,000,000 | 100.0% |
| JUMP_BACKWARD | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,000,960 | 100.0% |


</details>

### CALL_INTRINSIC_2

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_2 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 75.0% |
| MAKE_FUNCTION | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 75.0% |
| COPY | 20 | 25.0% |


</details>

### INSTRUMENTED_RESUME

<details>
<summary> Successors and predecessors for INSTRUMENTED_RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 19,436,580 | 100.0% |
| CALL | 4,500 | 0.0% |
| RESUME_CHECK | 1,060 | 0.0% |
| INSTRUMENTED_RESUME | 660 | 0.0% |
| RESUME | 520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,425,760 | 99.9% |
| LOAD_GLOBAL | 16,000 | 0.1% |
| RESUME | 960 | 0.0% |
| INSTRUMENTED_RESUME | 660 | 0.0% |
| LOAD_CONST | 240 | 0.0% |


</details>

### INSTRUMENTED_RETURN_VALUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,717,760 | 50.0% |
| BINARY_OP_ADD_INT | 9,711,340 | 50.0% |
| CALL | 1,280 | 0.0% |
| INSTRUMENTED_RETURN_VALUE | 1,280 | 0.0% |
| BINARY_SLICE | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 9,711,320 | 50.0% |
| LOAD_GLOBAL_MODULE | 9,711,320 | 50.0% |
| STORE_FAST | 7,040 | 0.0% |
| TO_BOOL_BOOL | 1,560 | 0.0% |
| INSTRUMENTED_RETURN_VALUE | 1,280 | 0.0% |


</details>

### INSTRUMENTED_RETURN_CONST

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 6,320 | 87.8% |
| POP_TOP | 420 | 5.8% |
| INSTRUMENTED_FOR_ITER | 320 | 4.4% |
| STORE_GLOBAL | 80 | 1.1% |
| CALL_LIST_APPEND | 60 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,400 | 88.9% |
| TO_BOOL_BOOL | 440 | 6.1% |
| POP_TOP | 240 | 3.3% |
| TO_BOOL | 120 | 1.7% |


</details>

### INSTRUMENTED_FOR_ITER

<details>
<summary> Successors and predecessors for INSTRUMENTED_FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_JUMP_BACKWARD | 5,900 | 52.4% |
| GET_ITER | 5,280 | 46.9% |
| SWAP | 80 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,980 | 53.1% |
| NOP | 4,080 | 36.2% |
| LOAD_CONST | 320 | 2.8% |
| INSTRUMENTED_RETURN_CONST | 320 | 2.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 280 | 2.5% |


</details>

### INSTRUMENTED_JUMP_FORWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 320 | 80.0% |
| STORE_FAST | 80 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320 | 80.0% |
| LOAD_GLOBAL | 80 | 20.0% |


</details>

### INSTRUMENTED_JUMP_BACKWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 4,080 | 40.9% |
| STORE_FAST | 4,080 | 40.9% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 1,260 | 12.6% |
| LIST_APPEND | 400 | 4.0% |
| POP_TOP | 80 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_FOR_ITER | 5,900 | 59.1% |
| LOAD_FAST | 4,080 | 40.9% |


</details>

### INSTRUMENTED_POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,080 | 52.8% |
| TO_BOOL | 4,280 | 31.9% |
| TO_BOOL_STR | 1,240 | 9.2% |
| TO_BOOL_NONE | 360 | 2.7% |
| COMPARE_OP_STR | 280 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,680 | 42.3% |
| LOAD_GLOBAL | 5,360 | 39.9% |
| INSTRUMENTED_JUMP_BACKWARD | 1,260 | 9.4% |
| INSTRUMENTED_RETURN_VALUE | 640 | 4.8% |
| POP_TOP | 240 | 1.8% |


</details>

### INSTRUMENTED_POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 19,422,780 | 99.8% |
| TO_BOOL_BOOL | 18,040 | 0.1% |
| COMPARE_OP_STR | 9,300 | 0.0% |
| TO_BOOL_STR | 8,760 | 0.0% |
| EXTENDED_ARG | 4,400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,729,360 | 50.0% |
| LOAD_GLOBAL | 9,716,800 | 49.9% |
| LOAD_FAST_LOAD_FAST | 12,560 | 0.1% |
| INSTRUMENTED_RETURN_CONST | 6,320 | 0.0% |
| POP_TOP | 320 | 0.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 100.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 360 | 90.0% |
| LOAD_ATTR | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 100.0% |


</details>

### DELETE_DEREF

<details>
<summary> Successors and predecessors for DELETE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR | 1,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_FAST | 1,600 | 100.0% |


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
|     deferred | 884,229,070 | 20.9% |
|          hit | 3,299,574,847 | 77.9% |
|         miss | 50,162,875 | 1.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 994,995 | 38.9% |
| Failure | 1,564,704 | 61.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| subtract different types | 775,855 | 49.6% |
| multiply different types | 248,567 | 15.9% |
| add different types | 190,927 | 12.2% |
| add other | 59,166 | 3.8% |
| and int | 56,849 | 3.6% |
| remainder | 54,631 | 3.5% |
| floor divide | 45,732 | 2.9% |
| true divide different types | 23,881 | 1.5% |
| lshift | 20,265 | 1.3% |
| or | 18,058 | 1.2% |
| rshift | 16,930 | 1.1% |
| xor | 16,183 | 1.0% |
| subtract other | 12,960 | 0.8% |
| true divide float | 9,423 | 0.6% |
| power | 5,301 | 0.3% |
| multiply other | 4,320 | 0.3% |
| true divide other | 3,323 | 0.2% |
| and other | 1,733 | 0.1% |
| and different types | 600 | 0.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> specialization stats for BINARY_OP_INPLACE_ADD_UNICODE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|         miss | 220 | 0.0% |


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
|     deferred | 698,420,549 | 23.0% |
|          hit | 2,333,515,355 | 76.8% |
|         miss | 4,760,728 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 189,016 | 43.3% |
| Failure | 247,432 | 56.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 78,640 | 31.8% |
| out of range | 75,686 | 30.6% |
| other | 59,837 | 24.2% |
| buffer int | 16,806 | 6.8% |
| list slice | 6,340 | 2.6% |
| code complex parameters | 4,780 | 1.9% |
| sequence int | 4,280 | 1.7% |
| buffer slice | 860 | 0.3% |
| tuple slice | 103 | 0.0% |
| string slice | 100 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 737,869,762,949,583,709,252 | 6,609,095,825,852.1% |
|        deopt | 22,840 | 0.0% |
|          hit | 9,708,359,403 | 87.0% |
|         miss | 248,393,155 | 2.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,193,966 | 85.4% |
| Failure | 890,238 | 14.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 178,254 | 20.0% |
| code complex parameters | 163,481 | 18.4% |
| no dict | 108,958 | 12.2% |
| cfunc noargs | 68,093 | 7.6% |
| class no vectorcall | 65,316 | 7.3% |
| meth descr varargs | 63,789 | 7.2% |
| cfunc varargs keywords | 54,025 | 6.1% |
| class mutable | 51,929 | 5.8% |
| other | 33,278 | 3.7% |
| meth descr varargs keywords | 17,977 | 2.0% |
| init not python | 17,120 | 1.9% |
| bound method | 11,964 | 1.3% |
| cmethod | 11,860 | 1.3% |
| init not simple | 11,860 | 1.3% |
| cfunc varargs | 11,154 | 1.3% |
| wrong number arguments | 9,840 | 1.1% |
| operator wrapper | 5,185 | 0.6% |
| method wrapper | 4,475 | 0.5% |
| str | 1,680 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 167,359,964 | 7.5% |
|          hit | 2,062,982,518 | 92.4% |
|         miss | 2,339,279 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 107,352 | 29.8% |
| Failure | 253,457 | 70.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 84,977 | 33.5% |
| different types | 52,346 | 20.7% |
| baseobject | 31,096 | 12.3% |
| other | 25,476 | 10.1% |
| float long | 17,166 | 6.8% |
| tuple | 15,280 | 6.0% |
| string | 10,640 | 4.2% |
| bool | 6,408 | 2.5% |
| list | 3,440 | 1.4% |
| bytes | 3,200 | 1.3% |
| set | 1,860 | 0.7% |
| long float | 1,568 | 0.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 737,869,762,948,885,221,838 | 39,002,338,506,104.5% |
|          hit | 1,244,795,915 | 65.8% |
|         miss | 140,887,305 | 7.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,709,396 | 89.7% |
| Failure | 310,498 | 10.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 125,148 | 40.3% |
| enumerate | 45,191 | 14.6% |
| set | 40,059 | 12.9% |
| zip | 19,860 | 6.4% |
| other | 19,480 | 6.3% |
| seq iter | 14,480 | 4.7% |
| dict values | 13,200 | 4.3% |
| reversed list | 9,120 | 2.9% |
| dict keys | 8,980 | 2.9% |
| itertools | 7,020 | 2.3% |
| ascii string | 5,280 | 1.7% |
| map | 1,520 | 0.5% |
| bytes | 660 | 0.2% |
| callable | 480 | 0.2% |
| string | 20 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 737,869,762,949,892,647,096 | 5,452,571,954,985.6% |
|        deopt | 1,817,941 | 0.0% |
|          hit | 11,264,823,179 | 83.2% |
|         miss | 743,042,158 | 5.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 14,734,693 | 92.8% |
| Failure | 1,143,949 | 7.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 341,094 | 29.8% |
| metaclass attribute | 247,242 | 21.6% |
| not managed dict | 142,112 | 12.4% |
| method | 137,784 | 12.0% |
| shadowed | 103,300 | 9.0% |
| mutable class | 67,701 | 5.9% |
| class method obj | 25,300 | 2.2% |
| overridden | 18,009 | 1.6% |
| class attr descriptor | 17,200 | 1.5% |
| non overriding descriptor | 12,622 | 1.1% |
| module attr not found | 11,120 | 1.0% |
| not in keys | 7,260 | 0.6% |
| class attr simple | 6,505 | 0.6% |
| non object slot | 3,500 | 0.3% |
| builtin class method | 3,140 | 0.3% |
| property | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 10,304,616 | 0.1% |
|        deopt | 9,360 | 0.0% |
|          hit | 9,011,374,267 | 99.9% |
|         miss | 330,415 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 545,043 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,284 | 0.0% |
|          hit | 171,005,241 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,140 | 100.0% |
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
|     deferred | 165,264,902 | 19.0% |
|          hit | 702,685,468 | 81.0% |
|         miss | 30,900 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,215 | 10.6% |
| Failure | 52,560 | 89.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| async generator send | 33,180 | 63.1% |
| other | 15,880 | 30.2% |
| list | 3,260 | 6.2% |
| dict keys | 240 | 0.5% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,058,283,696,216,168,594,880 | 134,549,122,366,070.0% |
|          hit | 2,684,588,887 | 89.0% |
|         miss | 259,255,111 | 8.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,024,108 | 98.0% |
| Failure | 102,246 | 2.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 48,940 | 47.9% |
| not in dict | 18,400 | 18.0% |
| overriding descriptor | 10,480 | 10.2% |
| not in keys | 7,880 | 7.7% |
| overridden | 5,200 | 5.1% |
| property | 4,020 | 3.9% |
| no dict | 3,100 | 3.0% |
| not managed dict | 2,666 | 2.6% |
| method | 1,540 | 1.5% |
| mutable class | 20 | 0.0% |


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
|     deferred | 342,655,651 | 37.6% |
|          hit | 569,663,332 | 62.4% |
|         miss | 2,880 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 16,162 | 10.8% |
| Failure | 132,897 | 89.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 55,580 | 41.8% |
| py simple | 43,439 | 32.7% |
| dict subclass no override | 28,198 | 21.2% |
| out of range | 2,900 | 2.2% |
| bytearray int | 1,980 | 1.5% |
| other | 800 | 0.6% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,582,544,170,319,681,473,725 | 42,304,808,393,472.0% |
|          hit | 5,630,833,736 | 92.2% |
|         miss | 126,228,832 | 2.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,606,492 | 79.0% |
| Failure | 694,889 | 21.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 191,413 | 27.5% |
| other | 173,193 | 24.9% |
| tuple | 120,459 | 17.3% |
| mapping | 99,187 | 14.3% |
| dict | 37,369 | 5.4% |
| set | 33,283 | 4.8% |
| bytes | 19,069 | 2.7% |
| sequence | 16,649 | 2.4% |
| float | 2,603 | 0.4% |
| bytearray | 1,244 | 0.2% |
| memory view | 420 | 0.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 368,934,881,474,191,305,666 | 29,469,318,181,209.0% |
|          hit | 1,248,615,813 | 99.7% |
|         miss | 2,939,660 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 97,408 | 97.4% |
| Failure | 2,573 | 2.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 1,513 | 58.8% |
| iterator | 680 | 26.4% |
| other | 380 | 14.8% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 89,083,625,702 | 53.9% |
| Not specialized | 17,643,854,293 | 10.7% |
| Specialized hits | 56,879,515,608 | 34.4% |
| Specialized misses | 1,578,872,561 | 1.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR | 4,058,283,696,216,168,594,880 | 44.0% |
| TO_BOOL | 2,582,544,170,319,681,473,725 | 28.0% |
| LOAD_ATTR | 737,869,762,949,892,647,096 | 8.0% |
| CALL | 737,869,762,949,583,709,252 | 8.0% |
| FOR_ITER | 737,869,762,948,885,221,838 | 8.0% |
| UNPACK_SEQUENCE | 368,934,881,474,191,305,666 | 4.0% |
| BINARY_OP | 884,229,070 | 0.0% |
| BINARY_SUBSCR | 698,420,549 | 0.0% |
| STORE_SUBSCR | 342,655,651 | 0.0% |
| COMPARE_OP | 167,359,964 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 258,828,187 | 16.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 203,255,215 | 12.9% |
| STORE_ATTR_SLOT | 159,623,267 | 10.1% |
| CALL_PY_EXACT_ARGS | 124,277,795 | 7.9% |
| LOAD_ATTR_SLOT | 114,354,322 | 7.2% |
| STORE_ATTR_INSTANCE_VALUE | 99,546,933 | 6.3% |
| FOR_ITER_TUPLE | 70,556,102 | 4.5% |
| FOR_ITER_LIST | 70,322,403 | 4.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 68,360,798 | 4.3% |
| LOAD_ATTR_METHOD_NO_DICT | 66,919,508 | 4.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 2,041,050,007 | 27.2% |
| Calls to Python functions inlined | 5,456,809,974 | 72.8% |
| Calls via PyEval_EvalFrame (total) | 2,041,050,007 | 27.2% |
| Calls via PyEval_EvalFrame (vector) | 1,273,701,091 | 17.0% |
| Calls via PyEval_EvalFrame (generator) | 767,348,916 | 10.2% |
| Calls via PyEval_EvalFrame (legacy) | 5,294,820 | 0.1% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,268,386,391 | 16.9% |
| Calls via PyEval_EvalFrame (build class) | 19,880 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 342,977,479 | 4.6% |
| Calls via PyEval_EvalFrame (function ex) | 28,874,630 | 0.4% |
| Calls via PyEval_EvalFrame (api) | 243,075,014 | 3.2% |
| Calls via PyEval_EvalFrame (method) | 212,827,500 | 2.8% |
| Frame objects created | 63,736,499 | 0.9% |
| Frames pushed | 4,802,567,122 | 64.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 6,216,300,465 | 35.9% |
| Frees to freelist | 6,224,059,573 |  |
| Allocations | 11,109,647,822 | 64.1% |
| Allocations to 512 bytes | 10,994,046,987 | 63.5% |
| Allocations to 4 kbytes | 95,188,489 | 0.5% |
| Allocations over 4 kbytes | 20,412,346 | 0.1% |
| Frees | 11,438,173,005 |  |
| New values | 76,366,242 |  |
| Interpreter increfs | 86,326,563,683 | 77.4% |
| Interpreter decrefs | 99,742,313,866 | 78.1% |
| Increfs | 25,167,682,368 | 22.6% |
| Decrefs | 28,004,874,445 | 21.9% |
| Materialize dict (on request) | 3,995,840 | 5.2% |
| Materialize dict (new key) | 190,560 | 0.2% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 2,033,360 | 2.7% |
| Method cache hits | 2,987,511,067 |  |
| Method cache misses | 91,012,222 |  |
| Method cache collisions | 105,718,144 |  |
| Method cache dunder hits | 3,390,282,343 |  |
| Method cache dunder misses | 15,108,279 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 720,764 | 45,914,742 | 6,421,547,854 |
| 1 | 64,446 | 67,087,089 | 5,401,817,894 |
| 2 | 20,817 | 53,113,614 | 18,128,540,501 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 373,692 |  |
| Traces created | 48,704 | 13.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 2,013 | 0.5% |
| Trace too long | 5,618 | 1.5% |
| Trace too short | 324,988 | 87.0% |
| Inner loop found | 981 | 0.3% |
| Recursive call | 940 | 0.3% |
| Traces executed | 2,438,689,513 |  |
| Uops executed | 99,780,273,270 | 40.92 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 80 | 0.2% |
| <= 16 | 3,943 | 8.1% |
| <= 32 | 16,430 | 33.7% |
| <= 64 | 13,678 | 28.1% |
| <= 128 | 14,573 | 29.9% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 120 | 0.2% |
| <= 8 | 2,984 | 6.1% |
| <= 16 | 13,607 | 27.9% |
| <= 32 | 15,861 | 32.6% |
| <= 64 | 10,625 | 21.8% |
| <= 128 | 5,507 | 11.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 31,521,515 | 1.3% |
| <= 2 | 97,284,901 | 4.0% |
| <= 4 | 388,022,701 | 15.9% |
| <= 8 | 261,505,640 | 10.7% |
| <= 16 | 381,798,677 | 15.7% |
| <= 32 | 594,044,478 | 24.4% |
| <= 64 | 223,242,949 | 9.2% |
| <= 128 | 406,536,928 | 16.7% |
| <= 256 | 24,637,737 | 1.0% |
| <= 512 | 8,248,146 | 0.3% |
| <= 1,024 | 6,046,012 | 0.2% |
| <= 2,048 | 14,501,173 | 0.6% |
| <= 4,096 | 1,098,939 | 0.0% |
| <= 8,192 | 150,929 | 0.0% |
| <= 16,384 | 40,859 | 0.0% |
| <= 32,768 | 1,220 | 0.0% |
| <= 65,536 | 4,806 | 0.0% |
| <= 131,072 | 783 | 0.0% |
| <= 262,144 | 340 | 0.0% |
| <= 524,288 | 140 | 0.0% |
| <= 1,048,576 | 400 | 0.0% |
| <= 2,097,152 | 80 | 0.0% |
| <= 4,194,304 | 160 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 18,020,603,260 | 18.1% | 18.1% |  |
| _CHECK_VALIDITY | 13,626,803,729 | 13.7% | 31.7% | 0.3% |
| _SET_IP | 12,096,727,464 | 12.1% | 43.8% |  |
| STORE_FAST | 5,835,456,208 | 5.8% | 49.7% |  |
| _INLINE_IMMORTAL_CONSTANT | 4,822,729,903 | 4.8% | 54.5% |  |
| _GUARD_IS_FALSE_POP | 3,518,017,283 | 3.5% | 58.0% | 2.6% |
| _GUARD_TYPE_VERSION | 2,447,916,688 | 2.5% | 60.5% | 6.5% |
| _GUARD_BOTH_INT | 1,947,039,201 | 2.0% | 62.5% | 0.0% |
| COMPARE_OP_STR | 1,804,459,253 | 1.8% | 64.3% |  |
| _BINARY_OP_ADD_INT | 1,642,204,412 | 1.6% | 65.9% |  |
| _JUMP_TO_TOP | 1,627,005,701 | 1.6% | 67.5% |  |
| CONTAINS_OP | 1,573,286,083 | 1.6% | 69.1% |  |
| _EXIT_TRACE | 1,288,109,264 | 1.3% | 70.4% |  |
| _ITER_CHECK_LIST | 1,248,061,541 | 1.3% | 71.7% | 1.3% |
| _GUARD_NOT_EXHAUSTED_LIST | 1,231,536,036 | 1.2% | 72.9% | 21.2% |
| BINARY_SUBSCR_STR_INT | 1,187,202,515 | 1.2% | 74.1% | 0.0% |
| _ITER_NEXT_LIST | 970,148,278 | 1.0% | 75.1% |  |
| _GUARD_IS_TRUE_POP | 913,636,977 | 0.9% | 76.0% | 26.7% |
| _BINARY_SUBSCR | 800,537,000 | 0.8% | 76.8% |  |
| _GUARD_BOTH_FLOAT | 780,592,520 | 0.8% | 77.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 719,836,193 | 0.7% | 78.3% | 0.9% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 714,523,836 | 0.7% | 79.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 714,523,836 | 0.7% | 79.7% |  |
| _CHECK_STACK_SPACE | 713,016,246 | 0.7% | 80.4% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 713,012,172 | 0.7% | 81.1% |  |
| _PUSH_FRAME | 713,012,172 | 0.7% | 81.8% |  |
| _SAVE_RETURN_OFFSET | 713,012,172 | 0.7% | 82.6% |  |
| _ITER_CHECK_RANGE | 638,788,112 | 0.6% | 83.2% | 0.1% |
| _GUARD_NOT_EXHAUSTED_RANGE | 638,109,392 | 0.6% | 83.8% | 5.8% |
| RESUME_CHECK | 631,652,414 | 0.6% | 84.5% | 0.0% |
| _GUARD_GLOBALS_VERSION | 618,906,228 | 0.6% | 85.1% | 0.1% |
| _ITER_NEXT_RANGE | 601,154,866 | 0.6% | 85.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 546,806,045 | 0.5% | 86.2% | 0.0% |
| _GUARD_KEYS_VERSION | 546,783,605 | 0.5% | 86.8% | 0.6% |
| _BINARY_OP_MULTIPLY_FLOAT | 527,422,940 | 0.5% | 87.3% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 514,160,800 | 0.5% | 87.8% |  |
| _LOAD_ATTR_SLOT | 497,396,487 | 0.5% | 88.3% |  |
| TO_BOOL_BOOL | 484,271,622 | 0.5% | 88.8% |  |
| _ITER_CHECK_TUPLE | 472,608,698 | 0.5% | 89.3% | 16.3% |
| _LOAD_ATTR_METHOD_NO_DICT | 463,410,373 | 0.5% | 89.8% |  |
| _GUARD_BUILTINS_VERSION | 414,516,747 | 0.4% | 90.2% | 0.0% |
| _LOAD_GLOBAL_BUILTINS | 414,516,087 | 0.4% | 90.6% |  |
| LOAD_CONST | 414,350,266 | 0.4% | 91.0% |  |
| PUSH_NULL | 407,594,482 | 0.4% | 91.4% |  |
| _GUARD_GLOBALS_DICT | 398,335,894 | 0.4% | 91.8% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 395,707,902 | 0.4% | 92.2% | 35.7% |
| BINARY_SUBSCR_LIST_INT | 372,640,750 | 0.4% | 92.6% | 0.0% |
| COMPARE_OP_INT | 369,491,444 | 0.4% | 93.0% | 0.0% |
| LOAD_DEREF | 339,774,254 | 0.3% | 93.3% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 338,158,046 | 0.3% | 93.6% |  |
| _INLINE_CONSTANT | 265,421,802 | 0.3% | 93.9% |  |
| _INLINE_CONSTANT_WITH_NULL | 258,987,575 | 0.3% | 94.2% |  |
| _ITER_NEXT_TUPLE | 254,572,916 | 0.3% | 94.4% |  |
| _BINARY_OP | 243,642,871 | 0.2% | 94.7% |  |
| COPY | 229,668,639 | 0.2% | 94.9% |  |
| _CHECK_PEP_523 | 222,073,232 | 0.2% | 95.1% |  |
| _GUARD_BUILTINS_DICT | 215,346,613 | 0.2% | 95.3% |  |
| _LOAD_GLOBAL_MODULE | 203,779,121 | 0.2% | 95.5% |  |
| _BINARY_OP_SUBTRACT_INT | 198,497,909 | 0.2% | 95.7% |  |
| SWAP | 195,521,960 | 0.2% | 95.9% |  |
| CALL_BUILTIN_FAST | 187,804,157 | 0.2% | 96.1% |  |
| _LOAD_ATTR | 177,084,935 | 0.2% | 96.3% |  |
| BINARY_SUBSCR_DICT | 176,690,380 | 0.2% | 96.5% |  |
| POP_TOP | 162,605,878 | 0.2% | 96.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 133,656,989 | 0.1% | 96.8% | 0.0% |
| _BINARY_OP_ADD_FLOAT | 131,231,820 | 0.1% | 96.9% |  |
| CALL_TYPE_1 | 126,167,152 | 0.1% | 97.0% |  |
| GET_ANEXT | 125,514,720 | 0.1% | 97.2% |  |
| _BINARY_OP_SUBTRACT_FLOAT | 121,937,760 | 0.1% | 97.3% |  |
| STORE_SLICE | 121,060,060 | 0.1% | 97.4% |  |
| TO_BOOL_INT | 120,519,899 | 0.1% | 97.5% | 0.0% |
| BUILD_SLICE | 115,518,240 | 0.1% | 97.6% |  |
| BUILD_LIST | 111,457,450 | 0.1% | 97.7% |  |
| STORE_SUBSCR_LIST_INT | 110,671,060 | 0.1% | 97.9% |  |
| CALL_ISINSTANCE | 108,308,358 | 0.1% | 98.0% |  |
| CALL_BUILTIN_O | 107,551,080 | 0.1% | 98.1% | 0.0% |
| _BINARY_OP_MULTIPLY_INT | 105,885,080 | 0.1% | 98.2% |  |
| _STORE_SUBSCR | 99,907,117 | 0.1% | 98.3% |  |
| LIST_APPEND | 94,548,488 | 0.1% | 98.4% |  |
| CALL_INTRINSIC_1 | 92,601,899 | 0.1% | 98.5% |  |
| BINARY_SUBSCR_TUPLE_INT | 88,333,292 | 0.1% | 98.6% |  |
| LIST_EXTEND | 87,359,419 | 0.1% | 98.6% |  |
| _POP_FRAME | 80,652,475 | 0.1% | 98.7% |  |
| GET_ITER | 74,655,898 | 0.1% | 98.8% |  |
| TO_BOOL_NONE | 65,638,200 | 0.1% | 98.9% | 89.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 61,940,265 | 0.1% | 98.9% | 4.5% |
| _INLINE_IMMORTAL_CONSTANT_WITH_NULL | 61,511,559 | 0.1% | 99.0% |  |
| UNPACK_SEQUENCE_TUPLE | 59,455,241 | 0.1% | 99.0% | 0.6% |
| _COMPARE_OP | 55,721,277 | 0.1% | 99.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 51,552,240 | 0.1% | 99.2% |  |
| _CHECK_ATTR_MODULE | 50,536,692 | 0.1% | 99.2% |  |
| _LOAD_ATTR_MODULE | 50,536,692 | 0.1% | 99.3% |  |
| BUILD_TUPLE | 50,135,007 | 0.1% | 99.3% |  |
| CALL_LEN | 49,289,552 | 0.0% | 99.4% |  |
| _STORE_ATTR_SLOT | 42,300,623 | 0.0% | 99.4% |  |
| BINARY_SLICE | 40,946,620 | 0.0% | 99.4% |  |
| UNPACK_SEQUENCE_LIST | 38,509,720 | 0.0% | 99.5% | 0.0% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 37,878,396 | 0.0% | 99.5% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 37,878,396 | 0.0% | 99.6% |  |
| CALL_STR_1 | 35,874,540 | 0.0% | 99.6% |  |
| COMPARE_OP_FLOAT | 32,677,525 | 0.0% | 99.6% | 0.0% |
| _GUARD_IS_NOT_NONE_POP | 31,089,064 | 0.0% | 99.7% | 2.3% |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 29,426,822 | 0.0% | 99.7% |  |
| MAKE_FUNCTION | 29,035,906 | 0.0% | 99.7% |  |
| _CHECK_ATTR_CLASS | 27,506,028 | 0.0% | 99.7% | 2.8% |
| _LOAD_ATTR_CLASS | 26,735,088 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 21,923,607 | 0.0% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 21,359,906 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 15,789,884 | 0.0% | 99.8% |  |
| TO_BOOL_STR | 14,162,117 | 0.0% | 99.8% | 0.0% |
| TO_BOOL_LIST | 13,053,633 | 0.0% | 99.9% |  |
| _LOAD_ATTR_WITH_HINT | 12,418,350 | 0.0% | 99.9% | 0.0% |
| _CHECK_ATTR_WITH_HINT | 12,418,350 | 0.0% | 99.9% |  |
| _GUARD_IS_NONE_POP | 12,216,002 | 0.0% | 99.9% | 14.5% |
| IS_OP | 11,414,864 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 11,303,520 | 0.0% | 99.9% | 93.1% |
| UNARY_NOT | 10,881,806 | 0.0% | 99.9% |  |
| BUILD_MAP | 7,368,918 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 7,225,420 | 0.0% | 99.9% |  |
| DICT_MERGE | 7,055,382 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 5,795,440 | 0.0% | 99.9% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,688,193 | 0.0% | 100.0% |  |
| MAP_ADD | 5,583,260 | 0.0% | 100.0% |  |
| _TO_BOOL | 4,850,407 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 4,129,025 | 0.0% | 100.0% | 8.4% |
| _STORE_ATTR_INSTANCE_VALUE | 3,781,245 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 3,763,833 | 0.0% | 100.0% |  |
| _CHECK_ATTR_METHOD_LAZY_DICT | 3,199,380 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_LAZY_DICT | 3,199,380 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 2,742,860 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 2,742,860 | 0.0% | 100.0% |  |
| SET_ADD | 2,683,640 | 0.0% | 100.0% |  |
| STORE_DEREF | 1,990,319 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,389,400 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 1,260,560 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 883,646 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 721,280 | 0.0% | 100.0% |  |
| BUILD_STRING | 552,340 | 0.0% | 100.0% |  |
| MAKE_CELL | 418,576 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 376,932 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 311,780 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 139,900 | 0.0% | 100.0% |  |
| LOAD_NAME | 110,080 | 0.0% | 100.0% |  |
| _STORE_ATTR | 103,860 | 0.0% | 100.0% |  |
| BEFORE_WITH | 93,209 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 89,040 | 0.0% | 100.0% |  |
| STORE_NAME | 37,460 | 0.0% | 100.0% |  |
| DELETE_FAST | 35,042 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 13,730 | 0.0% | 100.0% |  |
| BUILD_SET | 7,040 | 0.0% | 100.0% |  |
| UNARY_INVERT | 4,500 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 2,560 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 1,640 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 248,902 |
| FOR_ITER_GEN | 75,166 |
| CALL | 6,537 |
| LOAD_ATTR_PROPERTY | 4,244 |
| YIELD_VALUE | 2,538 |
| CALL_LIST_APPEND | 2,384 |
| CALL_PY_WITH_DEFAULTS | 2,240 |
| CALL_KW | 1,764 |
| BINARY_SUBSCR_GETITEM | 1,500 |
| CALL_FUNCTION_EX | 960 |
| CALL_ALLOC_AND_ENTER_INIT | 740 |
| RETURN_GENERATOR | 160 |
| BINARY_OP_INPLACE_ADD_UNICODE | 140 |
| STORE_ATTR_WITH_HINT | 100 |
| SEND | 60 |
| IMPORT_NAME | 20 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 1,920 |


</details>

---
Stats gathered on: 2023-11-17
