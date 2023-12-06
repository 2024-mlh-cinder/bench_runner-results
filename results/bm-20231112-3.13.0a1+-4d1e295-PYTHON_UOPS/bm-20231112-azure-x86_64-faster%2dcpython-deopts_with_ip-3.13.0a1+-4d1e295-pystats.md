
# Pystats results

- benchmark: all
- fork: faster-cpython
- ref: deopts-with-ip
- commit hash: 4d1e295
- commit date: 2023-11-12T06:35:45+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 30,913,320,577 | 19.1% | 19.1% |  |
| STORE_FAST | 8,520,919,958 | 5.3% | 24.3% |  |
| LOAD_CONST | 8,285,443,434 | 5.1% | 29.4% |  |
| POP_JUMP_IF_FALSE | 8,088,994,986 | 5.0% | 34.4% |  |
| LOAD_FAST_LOAD_FAST | 7,207,511,993 | 4.4% | 38.9% |  |
| RESUME_CHECK | 6,830,822,851 | 4.2% | 43.1% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 5,059,556,060 | 3.1% | 46.2% | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 4,709,077,657 | 2.9% | 49.1% | 5.5% |
| TO_BOOL_BOOL | 4,387,205,316 | 2.7% | 51.8% | 0.0% |
| RETURN_VALUE | 4,349,716,849 | 2.7% | 54.5% |  |
| LOAD_GLOBAL_MODULE | 3,821,039,415 | 2.4% | 56.9% | 0.0% |
| POP_TOP | 3,513,927,525 | 2.2% | 59.0% |  |
| CALL_PY_EXACT_ARGS | 3,346,880,182 | 2.1% | 61.1% | 3.8% |
| ENTER_EXECUTOR | 2,410,810,571 | 1.5% | 62.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,159,979,767 | 1.3% | 63.9% | 9.4% |
| RETURN_CONST | 2,062,099,483 | 1.3% | 65.2% |  |
| STORE_FAST_STORE_FAST | 2,000,928,094 | 1.2% | 66.4% |  |
| POP_JUMP_IF_TRUE | 1,997,411,758 | 1.2% | 67.7% |  |
| INTERPRETER_EXIT | 1,994,219,442 | 1.2% | 68.9% |  |
| LOAD_ATTR_SLOT | 1,887,677,539 | 1.2% | 70.1% | 6.0% |
| STORE_ATTR_SLOT | 1,732,939,238 | 1.1% | 71.1% | 9.2% |
| LOAD_ATTR_METHOD_NO_DICT | 1,606,071,959 | 1.0% | 72.1% | 4.1% |
| COMPARE_OP_INT | 1,512,155,076 | 0.9% | 73.1% | 0.1% |
| LOAD_ATTR | 1,501,910,799 | 0.9% | 74.0% |  |
| PUSH_NULL | 1,330,125,392 | 0.8% | 74.8% |  |
| BINARY_OP_ADD_INT | 1,318,666,109 | 0.8% | 75.6% | 0.0% |
| COPY | 1,179,471,862 | 0.7% | 76.4% |  |
| CALL | 1,179,016,940 | 0.7% | 77.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,126,006,407 | 0.7% | 77.8% | 8.8% |
| CALL_BUILTIN_FAST | 1,120,002,679 | 0.7% | 78.5% | 0.0% |
| CONTAINS_OP | 1,109,763,785 | 0.7% | 79.2% |  |
| CALL_ISINSTANCE | 1,081,762,058 | 0.7% | 79.8% |  |
| SWAP | 1,058,020,358 | 0.7% | 80.5% |  |
| YIELD_VALUE | 1,048,533,941 | 0.6% | 81.1% |  |
| CALL_BUILTIN_O | 1,044,279,289 | 0.6% | 81.8% | 0.4% |
| NOP | 949,712,558 | 0.6% | 82.4% |  |
| BUILD_TUPLE | 929,663,200 | 0.6% | 82.9% |  |
| BINARY_OP | 879,001,018 | 0.5% | 83.5% |  |
| LOAD_DEREF | 800,038,509 | 0.5% | 84.0% |  |
| IS_OP | 798,741,017 | 0.5% | 84.5% |  |
| BINARY_SUBSCR_LIST_INT | 785,091,865 | 0.5% | 84.9% | 0.5% |
| GET_ITER | 774,193,501 | 0.5% | 85.4% |  |
| BINARY_SUBSCR | 700,540,043 | 0.4% | 85.8% |  |
| FOR_ITER_LIST | 696,916,875 | 0.4% | 86.3% | 10.1% |
| POP_JUMP_IF_NOT_NONE | 687,370,454 | 0.4% | 86.7% |  |
| BINARY_SUBSCR_DICT | 665,787,294 | 0.4% | 87.1% |  |
| TO_BOOL_NONE | 611,009,356 | 0.4% | 87.5% | 8.5% |
| BINARY_OP_MULTIPLY_FLOAT | 576,077,738 | 0.4% | 87.8% | 1.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 568,822,767 | 0.4% | 88.2% |  |
| JUMP_FORWARD | 534,069,985 | 0.3% | 88.5% |  |
| UNPACK_SEQUENCE_TUPLE | 531,826,659 | 0.3% | 88.9% | 0.3% |
| LOAD_ATTR_MODULE | 528,471,418 | 0.3% | 89.2% | 0.0% |
| FOR_ITER | 500,335,683 | 0.3% | 89.5% |  |
| JUMP_BACKWARD | 489,904,235 | 0.3% | 89.8% |  |
| POP_JUMP_IF_NONE | 479,174,224 | 0.3% | 90.1% |  |
| BINARY_SUBSCR_STR_INT | 473,710,318 | 0.3% | 90.4% | 0.1% |
| BINARY_OP_SUBTRACT_INT | 455,763,001 | 0.3% | 90.7% | 0.1% |
| SEND_GEN | 451,092,579 | 0.3% | 90.9% | 0.0% |
| EXTENDED_ARG | 424,550,670 | 0.3% | 91.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 422,927,094 | 0.3% | 91.5% | 7.5% |
| CALL_METHOD_DESCRIPTOR_O | 412,096,221 | 0.3% | 91.7% | 0.1% |
| LOAD_ATTR_WITH_HINT | 400,063,517 | 0.2% | 92.0% | 0.5% |
| BINARY_OP_ADD_FLOAT | 393,528,446 | 0.2% | 92.2% | 2.2% |
| COPY_FREE_VARS | 383,840,683 | 0.2% | 92.4% |  |
| CALL_LEN | 381,928,934 | 0.2% | 92.7% |  |
| RETURN_GENERATOR | 377,874,819 | 0.2% | 92.9% |  |
| BUILD_LIST | 357,233,342 | 0.2% | 93.1% |  |
| COMPARE_OP_STR | 341,773,794 | 0.2% | 93.3% | 0.2% |
| TO_BOOL | 341,454,120 | 0.2% | 93.6% |  |
| CALL_TYPE_1 | 340,972,627 | 0.2% | 93.8% |  |
| CALL_LIST_APPEND | 340,864,694 | 0.2% | 94.0% | 0.0% |
| STORE_SUBSCR | 338,108,553 | 0.2% | 94.2% |  |
| FOR_ITER_TUPLE | 337,561,424 | 0.2% | 94.4% | 20.9% |
| STORE_SUBSCR_LIST_INT | 311,173,460 | 0.2% | 94.6% | 0.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 309,986,188 | 0.2% | 94.8% |  |
| END_SEND | 297,826,857 | 0.2% | 95.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 293,414,976 | 0.2% | 95.1% | 9.5% |
| BINARY_SLICE | 285,272,599 | 0.2% | 95.3% |  |
| STORE_SUBSCR_DICT | 264,770,101 | 0.2% | 95.5% |  |
| CALL_KW | 260,580,273 | 0.2% | 95.6% |  |
| BINARY_OP_MULTIPLY_INT | 248,272,155 | 0.2% | 95.8% | 4.6% |
| BINARY_OP_SUBTRACT_FLOAT | 237,898,586 | 0.1% | 95.9% | 8.5% |
| TO_BOOL_ALWAYS_TRUE | 228,652,560 | 0.1% | 96.1% | 20.8% |
| CALL_PY_WITH_DEFAULTS | 225,906,249 | 0.1% | 96.2% | 3.1% |
| BINARY_SUBSCR_TUPLE_INT | 221,471,075 | 0.1% | 96.4% | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 207,472,022 | 0.1% | 96.5% | 19.0% |
| TO_BOOL_INT | 206,924,032 | 0.1% | 96.6% | 0.6% |
| FOR_ITER_GEN | 201,772,324 | 0.1% | 96.7% | 0.0% |
| BINARY_SUBSCR_GETITEM | 190,312,780 | 0.1% | 96.9% | 0.0% |
| COMPARE_OP_FLOAT | 185,906,552 | 0.1% | 97.0% | 0.0% |
| TO_BOOL_LIST | 183,306,477 | 0.1% | 97.1% | 1.0% |
| CALL_FUNCTION_EX | 178,840,545 | 0.1% | 97.2% |  |
| DELETE_SUBSCR | 172,512,560 | 0.1% | 97.3% |  |
| CALL_BUILTIN_CLASS | 172,288,732 | 0.1% | 97.4% | 0.0% |
| COMPARE_OP | 167,632,889 | 0.1% | 97.5% |  |
| LOAD_SUPER_ATTR_METHOD | 166,159,986 | 0.1% | 97.6% |  |
| SEND | 164,809,258 | 0.1% | 97.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 163,477,283 | 0.1% | 97.8% | 41.8% |
| UNARY_NEGATIVE | 161,346,204 | 0.1% | 97.9% |  |
| FORMAT_SIMPLE | 152,223,880 | 0.1% | 98.0% |  |
| GET_AWAITABLE | 151,578,737 | 0.1% | 98.1% |  |
| CALL_INTRINSIC_1 | 149,028,485 | 0.1% | 98.2% |  |
| UNPACK_SEQUENCE_LIST | 148,232,272 | 0.1% | 98.3% | 0.8% |
| CONVERT_VALUE | 138,785,820 | 0.1% | 98.4% |  |
| MAKE_CELL | 116,677,843 | 0.1% | 98.4% |  |
| MAKE_FUNCTION | 109,249,257 | 0.1% | 98.5% |  |
| LOAD_ATTR_CLASS | 107,031,437 | 0.1% | 98.6% | 1.7% |
| BUILD_MAP | 106,277,255 | 0.1% | 98.6% |  |
| LIST_APPEND | 99,778,016 | 0.1% | 98.7% |  |
| SET_FUNCTION_ATTRIBUTE | 98,353,486 | 0.1% | 98.8% |  |
| BUILD_SLICE | 96,215,468 | 0.1% | 98.8% |  |
| BINARY_OP_ADD_UNICODE | 95,068,140 | 0.1% | 98.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 94,308,714 | 0.1% | 98.9% | 2.4% |
| LOAD_ATTR_PROPERTY | 93,440,943 | 0.1% | 99.0% | 12.2% |
| STORE_DEREF | 92,440,073 | 0.1% | 99.1% |  |
| EXIT_INIT_CHECK | 92,022,294 | 0.1% | 99.1% |  |
| FOR_ITER_RANGE | 91,527,957 | 0.1% | 99.2% | 0.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 82,958,503 | 0.1% | 99.2% | 19.0% |
| LOAD_FAST_AND_CLEAR | 77,520,845 | 0.0% | 99.3% |  |
| TO_BOOL_STR | 77,167,000 | 0.0% | 99.3% | 4.6% |
| BUILD_STRING | 76,578,500 | 0.0% | 99.4% |  |
| END_FOR | 76,103,409 | 0.0% | 99.4% |  |
| UNARY_NOT | 72,314,199 | 0.0% | 99.5% |  |
| STORE_ATTR | 72,014,100 | 0.0% | 99.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 69,867,802 | 0.0% | 99.5% | 0.1% |
| STORE_ATTR_WITH_HINT | 63,960,618 | 0.0% | 99.6% | 0.1% |
| LOAD_ATTR_METHOD_LAZY_DICT | 59,024,972 | 0.0% | 99.6% | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 53,686,585 | 0.0% | 99.7% | 4.4% |
| MAP_ADD | 53,609,365 | 0.0% | 99.7% |  |
| STORE_FAST_LOAD_FAST | 35,915,740 | 0.0% | 99.7% |  |
| STORE_SLICE | 35,795,300 | 0.0% | 99.7% |  |
| CALL_TUPLE_1 | 34,814,075 | 0.0% | 99.7% | 0.0% |
| CALL_STR_1 | 34,093,820 | 0.0% | 99.8% |  |
| LIST_EXTEND | 29,802,981 | 0.0% | 99.8% |  |
| DICT_MERGE | 29,263,710 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 22,776,955 | 0.0% | 99.8% |  |
| POP_EXCEPT | 22,776,815 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 22,286,413 | 0.0% | 99.8% |  |
| GET_YIELD_FROM_ITER | 20,766,152 | 0.0% | 99.9% |  |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 19,465,840 | 0.0% | 99.9% |  |
| INSTRUMENTED_RESUME | 19,443,620 | 0.0% | 99.9% |  |
| INSTRUMENTED_RETURN_VALUE | 19,434,720 | 0.0% | 99.9% |  |
| UNARY_INVERT | 15,532,061 | 0.0% | 99.9% |  |
| LOAD_NAME | 13,930,060 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 12,163,800 | 0.0% | 99.9% |  |
| BUILD_CONST_KEY_MAP | 11,929,742 | 0.0% | 99.9% |  |
| IMPORT_FROM | 11,442,215 | 0.0% | 99.9% |  |
| DELETE_ATTR | 11,354,873 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 10,731,429 | 0.0% | 100.0% |  |
| IMPORT_NAME | 10,202,564 | 0.0% | 100.0% |  |
| BEFORE_WITH | 8,250,981 | 0.0% | 100.0% |  |
| GET_ANEXT | 8,000,960 | 0.0% | 100.0% |  |
| END_ASYNC_FOR | 8,000,000 | 0.0% | 100.0% |  |
| GET_AITER | 8,000,000 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 7,990,000 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 6,941,340 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 4,247,488 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 3,979,056 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 2,995,200 | 0.0% | 100.0% |  |
| RERAISE | 2,526,980 | 0.0% | 100.0% |  |
| BUILD_SET | 2,001,136 | 0.0% | 100.0% |  |
| DELETE_FAST | 1,797,527 | 0.0% | 100.0% |  |
| SET_ADD | 1,470,440 | 0.0% | 100.0% |  |
| STORE_NAME | 926,120 | 0.0% | 100.0% |  |
| UNPACK_EX | 668,000 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 364,787 | 0.0% | 100.0% |  |
| RESUME | 244,946 | 0.0% | 100.0% | 201.8% |
| DICT_UPDATE | 22,740 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 18,940 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 16,585 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 13,432 | 0.0% | 100.0% |  |
| INSTRUMENTED_FOR_ITER | 11,272 | 0.0% | 100.0% |  |
| INSTRUMENTED_JUMP_BACKWARD | 9,992 | 0.0% | 100.0% |  |
| INSTRUMENTED_RETURN_CONST | 7,200 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,880 | 0.0% | 100.0% |  |
| LOAD_LOCALS | 3,860 | 0.0% | 100.0% |  |
| LOAD_FROM_DICT_OR_DEREF | 3,840 | 0.0% | 100.0% |  |
| DELETE_DEREF | 1,600 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 1,240 | 0.0% | 100.0% |  |
| DELETE_NAME | 900 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_NONE | 720 | 0.0% | 100.0% |  |
| SET_UPDATE | 660 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 640 | 0.0% | 100.0% |  |
| INSTRUMENTED_JUMP_FORWARD | 400 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_NOT_NONE | 400 | 0.0% | 100.0% |  |
| SETUP_ANNOTATIONS | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_2 | 80 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 4,479,808,870 | 2.8% | 2.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 4,282,294,831 | 2.6% | 5.4% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 4,091,145,420 | 2.5% | 7.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,172,928,482 | 2.0% | 9.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,168,937,396 | 2.0% | 11.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 2,932,361,635 | 1.8% | 13.7% |
| RESUME_CHECK LOAD_FAST | 2,895,648,572 | 1.8% | 15.4% |
| LOAD_FAST LOAD_CONST | 2,837,131,223 | 1.8% | 17.2% |
| LOAD_FAST LOAD_ATTR_SLOT | 1,723,378,605 | 1.1% | 18.3% |
| CACHE RESUME_CHECK | 1,685,713,163 | 1.0% | 19.3% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,646,341,444 | 1.0% | 20.3% |
| LOAD_CONST LOAD_FAST | 1,369,269,882 | 0.8% | 21.2% |
| POP_TOP LOAD_FAST | 1,331,944,488 | 0.8% | 22.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,271,612,737 | 0.8% | 22.8% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,262,030,461 | 0.8% | 23.5% |
| LOAD_FAST RETURN_VALUE | 1,252,142,388 | 0.8% | 24.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,230,634,086 | 0.8% | 25.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 1,179,385,520 | 0.7% | 25.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 1,172,581,293 | 0.7% | 26.5% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,119,554,677 | 0.7% | 27.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,103,937,435 | 0.7% | 27.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,064,724,122 | 0.7% | 28.6% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 1,048,603,098 | 0.6% | 29.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,036,265,518 | 0.6% | 29.8% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 964,692,107 | 0.6% | 30.4% |
| RETURN_VALUE STORE_FAST | 953,435,468 | 0.6% | 31.0% |
| LOAD_FAST TO_BOOL_BOOL | 941,204,221 | 0.6% | 31.6% |
| LOAD_FAST LOAD_ATTR | 907,602,136 | 0.6% | 32.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 905,358,159 | 0.6% | 32.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 877,925,941 | 0.5% | 33.3% |
| LOAD_CONST BINARY_OP_ADD_INT | 874,301,973 | 0.5% | 33.8% |
| POP_JUMP_IF_TRUE LOAD_FAST | 866,948,882 | 0.5% | 34.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 862,204,441 | 0.5% | 34.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 859,788,956 | 0.5% | 35.4% |
| RETURN_CONST POP_TOP | 849,266,083 | 0.5% | 35.9% |
| POP_TOP ENTER_EXECUTOR | 844,467,580 | 0.5% | 36.4% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 830,627,328 | 0.5% | 37.0% |
| LOAD_CONST LOAD_CONST | 819,765,879 | 0.5% | 37.5% |
| LOAD_FAST STORE_ATTR_SLOT | 805,338,119 | 0.5% | 38.0% |
| LOAD_FAST CALL_BUILTIN_O | 777,792,592 | 0.5% | 38.4% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 749,745,038 | 0.5% | 38.9% |
| LOAD_FAST LOAD_FAST | 734,149,711 | 0.5% | 39.4% |
| RESUME_CHECK POP_TOP | 725,786,392 | 0.4% | 39.8% |
| RETURN_VALUE RETURN_VALUE | 710,050,946 | 0.4% | 40.2% |
| STORE_FAST STORE_FAST | 698,622,255 | 0.4% | 40.7% |
| RETURN_CONST INTERPRETER_EXIT | 696,857,796 | 0.4% | 41.1% |
| LOAD_CONST COMPARE_OP_INT | 690,665,533 | 0.4% | 41.5% |
| LOAD_FAST PUSH_NULL | 685,179,486 | 0.4% | 42.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 678,228,321 | 0.4% | 42.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 668,531,033 | 0.4% | 42.8% |
| IS_OP POP_JUMP_IF_FALSE | 668,529,297 | 0.4% | 43.2% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 653,713,960 | 0.4% | 43.6% |
| RETURN_VALUE INTERPRETER_EXIT | 638,340,241 | 0.4% | 44.0% |
| PUSH_NULL LOAD_FAST | 635,867,362 | 0.4% | 44.4% |
| YIELD_VALUE INTERPRETER_EXIT | 628,421,265 | 0.4% | 44.8% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 616,463,706 | 0.4% | 45.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 604,278,692 | 0.4% | 45.5% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 599,101,940 | 0.4% | 45.9% |
| LOAD_CONST STORE_FAST | 593,029,513 | 0.4% | 46.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 585,938,194 | 0.4% | 46.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 581,569,223 | 0.4% | 47.0% |
| LOAD_GLOBAL_BUILTIN CALL_BUILTIN_FAST | 579,419,320 | 0.4% | 47.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 568,685,532 | 0.4% | 47.7% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 564,509,353 | 0.3% | 48.0% |
| BUILD_TUPLE RETURN_VALUE | 560,014,444 | 0.3% | 48.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 549,153,478 | 0.3% | 48.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 546,692,644 | 0.3% | 49.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 545,763,601 | 0.3% | 49.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 526,119,919 | 0.3% | 49.7% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 520,297,525 | 0.3% | 50.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 513,604,463 | 0.3% | 50.4% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 511,069,617 | 0.3% | 50.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 510,702,111 | 0.3% | 51.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 510,642,410 | 0.3% | 51.3% |
| STORE_FAST LOAD_GLOBAL_MODULE | 509,067,894 | 0.3% | 51.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 502,358,243 | 0.3% | 51.9% |
| CALL STORE_FAST | 474,225,095 | 0.3% | 52.2% |
| LOAD_ATTR_SLOT LOAD_FAST | 447,472,583 | 0.3% | 52.5% |
| POP_JUMP_IF_FALSE RETURN_CONST | 437,280,516 | 0.3% | 52.8% |
| BINARY_OP_ADD_INT STORE_FAST | 436,271,027 | 0.3% | 53.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 427,162,516 | 0.3% | 53.3% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_STR_INT | 421,110,718 | 0.3% | 53.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 419,412,642 | 0.3% | 53.8% |
| CALL_BUILTIN_O POP_TOP | 418,800,097 | 0.3% | 54.1% |
| NOP LOAD_FAST | 418,008,912 | 0.3% | 54.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 400,925,454 | 0.2% | 54.6% |
| STORE_ATTR_SLOT LOAD_CONST | 396,720,929 | 0.2% | 54.8% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 394,665,810 | 0.2% | 55.1% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 392,444,095 | 0.2% | 55.3% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 389,856,111 | 0.2% | 55.6% |
| STORE_ATTR_SLOT RETURN_CONST | 383,261,407 | 0.2% | 55.8% |
| POP_TOP RESUME_CHECK | 377,859,678 | 0.2% | 56.0% |
| RESUME_CHECK NOP | 377,252,210 | 0.2% | 56.3% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 375,451,227 | 0.2% | 56.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 375,025,693 | 0.2% | 56.7% |
| ENTER_EXECUTOR YIELD_VALUE | 366,551,783 | 0.2% | 57.0% |
| LOAD_DEREF LOAD_FAST | 364,777,514 | 0.2% | 57.2% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 362,917,049 | 0.2% | 57.4% |
| POP_JUMP_IF_FALSE LOAD_CONST | 362,288,827 | 0.2% | 57.6% |
| STORE_ATTR_SLOT LOAD_FAST | 359,945,427 | 0.2% | 57.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 173,576,201 | 60.8% |
| LOAD_FAST_LOAD_FAST | 51,940,380 | 18.2% |
| LOAD_FAST | 33,500,938 | 11.7% |
| BINARY_OP_ADD_INT | 18,175,820 | 6.4% |
| LOAD_ATTR_SLOT | 6,400,800 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 69,799,982 | 24.5% |
| GET_ITER | 44,687,620 | 15.7% |
| CALL_PY_EXACT_ARGS | 33,216,500 | 11.6% |
| BUILD_TUPLE | 32,457,760 | 11.4% |
| LOAD_DEREF | 25,324,560 | 8.9% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 23,030,580 | 64.3% |
| LOAD_CONST | 12,409,480 | 34.7% |
| LOAD_FAST_LOAD_FAST | 344,480 | 1.0% |
| LOAD_ATTR_SLOT | 10,700 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,926,880 | 78.0% |
| RETURN_CONST | 7,807,680 | 21.8% |
| ENTER_EXECUTOR | 46,060 | 0.1% |
| JUMP_BACKWARD | 8,880 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 3,560 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,685,713,163 | 84.4% |
| POP_TOP | 144,963,880 | 7.3% |
| COPY_FREE_VARS | 134,092,509 | 6.7% |
| RETURN_GENERATOR | 30,587,180 | 1.5% |
| MAKE_CELL | 1,702,354 | 0.1% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,478,640 | 43.5% |
| ENTER_EXECUTOR | 1,740,380 | 21.8% |
| RETURN_VALUE | 909,040 | 11.4% |
| BINARY_SLICE | 786,260 | 9.8% |
| BINARY_OP_ADD_UNICODE | 524,640 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,108,700 | 89.0% |
| JUMP_BACKWARD | 717,220 | 9.0% |
| LOAD_CONST | 80,460 | 1.0% |
| LOAD_FAST_LOAD_FAST | 32,340 | 0.4% |
| ENTER_EXECUTOR | 26,340 | 0.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 186,396,096 | 26.6% |
| LOAD_CONST | 175,381,366 | 25.0% |
| COPY | 115,659,020 | 16.5% |
| LOAD_FAST_LOAD_FAST | 102,853,695 | 14.7% |
| BINARY_OP_ADD_INT | 43,215,480 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 234,595,190 | 33.5% |
| STORE_FAST | 97,752,246 | 14.0% |
| LOAD_FAST_LOAD_FAST | 65,511,251 | 9.4% |
| BINARY_SUBSCR_DICT | 49,285,320 | 7.0% |
| RETURN_VALUE | 47,331,621 | 6.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 20,598,578 | 92.4% |
| LOAD_GLOBAL_MODULE | 998,696 | 4.5% |
| BUILD_TUPLE | 632,812 | 2.8% |
| LOAD_ATTR_MODULE | 50,847 | 0.2% |
| LOAD_GLOBAL | 3,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 22,286,093 | 100.0% |
| EXTENDED_ARG | 320 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 76,103,409 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 48,922,740 | 64.3% |
| LOAD_FAST | 25,971,289 | 34.1% |
| RETURN_CONST | 1,054,560 | 1.4% |
| JUMP_BACKWARD | 133,920 | 0.2% |
| LOAD_CONST | 7,200 | 0.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 141,189,599 | 47.4% |
| RETURN_VALUE | 108,690,859 | 36.5% |
| RETURN_CONST | 47,931,379 | 16.1% |
| SEND_GEN | 15,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 129,501,459 | 43.5% |
| POP_TOP | 78,295,358 | 26.3% |
| BINARY_OP_ADD_INT | 38,845,400 | 13.0% |
| LOAD_GLOBAL_MODULE | 38,845,400 | 13.0% |
| LOAD_FAST | 8,588,040 | 2.9% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 138,785,820 | 91.2% |
| LOAD_FAST | 6,910,420 | 4.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,898,580 | 1.2% |
| LOAD_ATTR_MODULE | 1,765,760 | 1.2% |
| RETURN_VALUE | 1,389,520 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 76,325,140 | 50.1% |
| BUILD_STRING | 68,064,060 | 44.7% |
| LOAD_FAST | 7,822,800 | 5.1% |
| LOAD_GLOBAL_MODULE | 11,640 | 0.0% |
| LOAD_GLOBAL | 120 | 0.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 287,438,440 | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE | 70,793,117 | 9.1% |
| CALL_BUILTIN_CLASS | 69,021,940 | 8.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 57,181,347 | 7.4% |
| RETURN_VALUE | 55,146,353 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 248,502,016 | 32.1% |
| FOR_ITER_TUPLE | 163,595,158 | 21.1% |
| CALL_PY_EXACT_ARGS | 97,993,806 | 12.7% |
| FOR_ITER | 91,476,477 | 11.8% |
| FOR_ITER_GEN | 75,705,369 | 9.8% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,000,520 | 77.1% |
| RETURN_GENERATOR | 4,562,712 | 22.0% |
| BINARY_SUBSCR | 185,800 | 0.9% |
| LOAD_FAST | 9,440 | 0.0% |
| RETURN_VALUE | 7,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,766,152 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 696,857,796 | 34.9% |
| RETURN_VALUE | 638,340,241 | 32.0% |
| YIELD_VALUE | 628,421,265 | 31.5% |
| RETURN_GENERATOR | 30,599,820 | 1.5% |
| INSTRUMENTED_RETURN_VALUE | 320 | 0.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 109,249,257 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 97,122,881 | 88.9% |
| LOAD_FAST | 6,478,869 | 5.9% |
| LOAD_GLOBAL_MODULE | 3,345,600 | 3.1% |
| STORE_FAST | 813,932 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 801,499 | 0.7% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 377,252,210 | 39.7% |
| STORE_FAST | 194,461,222 | 20.5% |
| POP_JUMP_IF_FALSE | 108,071,666 | 11.4% |
| STORE_ATTR_INSTANCE_VALUE | 71,815,709 | 7.6% |
| NOP | 65,029,439 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 418,008,912 | 44.0% |
| LOAD_FAST_LOAD_FAST | 345,556,651 | 36.4% |
| NOP | 65,029,439 | 6.8% |
| LOAD_GLOBAL_BUILTIN | 38,876,143 | 4.1% |
| LOAD_CONST | 30,514,342 | 3.2% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 13,059,151 | 57.3% |
| STORE_SUBSCR_DICT | 4,100,980 | 18.0% |
| SWAP | 3,041,595 | 13.4% |
| COPY | 1,539,580 | 6.8% |
| STORE_FAST | 736,627 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 12,258,838 | 53.8% |
| RETURN_VALUE | 2,964,795 | 13.0% |
| JUMP_FORWARD | 2,296,140 | 10.1% |
| POP_TOP | 1,845,623 | 8.1% |
| RERAISE | 1,539,580 | 6.8% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 849,266,083 | 24.2% |
| RESUME_CHECK | 725,786,392 | 20.7% |
| CALL_BUILTIN_O | 418,800,097 | 11.9% |
| CALL_METHOD_DESCRIPTOR_O | 267,746,885 | 7.6% |
| POP_JUMP_IF_FALSE | 200,316,370 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,331,944,488 | 37.9% |
| ENTER_EXECUTOR | 844,467,580 | 24.0% |
| RESUME_CHECK | 377,859,678 | 10.8% |
| RETURN_CONST | 300,247,136 | 8.5% |
| LOAD_CONST | 147,364,033 | 4.2% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 6,939,417 | 30.5% |
| LOAD_ATTR | 4,419,440 | 19.4% |
| RAISE_VARARGS | 3,177,936 | 14.0% |
| CALL_BUILTIN_FAST | 2,380,080 | 10.4% |
| RERAISE | 1,488,520 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 20,755,592 | 91.1% |
| LOAD_GLOBAL_MODULE | 1,489,643 | 6.5% |
| LOAD_FAST | 517,720 | 2.3% |
| LOAD_GLOBAL | 7,920 | 0.0% |
| WITH_EXCEPT_START | 5,880 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 685,179,486 | 51.5% |
| LOAD_ATTR_MODULE | 427,162,516 | 32.1% |
| LOAD_DEREF | 65,146,492 | 4.9% |
| LOAD_ATTR | 61,445,432 | 4.6% |
| LOAD_FAST_LOAD_FAST | 41,842,188 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 635,867,362 | 47.8% |
| LOAD_FAST_LOAD_FAST | 394,665,810 | 29.7% |
| LOAD_CONST | 134,602,575 | 10.1% |
| CALL | 98,334,256 | 7.4% |
| LOAD_GLOBAL_MODULE | 32,881,101 | 2.5% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 193,768,047 | 51.3% |
| COPY_FREE_VARS | 106,806,412 | 28.3% |
| ENTER_EXECUTOR | 33,690,019 | 8.9% |
| CACHE | 30,587,180 | 8.1% |
| CALL_PY_WITH_DEFAULTS | 8,860,600 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 129,971,238 | 34.4% |
| GET_ITER | 50,227,060 | 13.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 43,092,280 | 11.4% |
| CALL | 38,775,581 | 10.3% |
| INTERPRETER_EXIT | 30,599,820 | 8.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,252,142,388 | 28.8% |
| RETURN_VALUE | 710,050,946 | 16.3% |
| BUILD_TUPLE | 560,014,444 | 12.9% |
| LOAD_ATTR_INSTANCE_VALUE | 271,530,936 | 6.2% |
| COMPARE_OP_FLOAT | 127,781,115 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 953,435,468 | 21.9% |
| RETURN_VALUE | 710,050,946 | 16.3% |
| INTERPRETER_EXIT | 638,340,241 | 14.7% |
| UNPACK_SEQUENCE_TUPLE | 345,281,960 | 7.9% |
| TO_BOOL_BOOL | 342,606,932 | 7.9% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 115,669,300 | 34.2% |
| LOAD_FAST | 85,446,943 | 25.3% |
| LOAD_CONST | 40,853,490 | 12.1% |
| BINARY_OP_ADD_INT | 38,502,360 | 11.4% |
| LOAD_FAST_LOAD_FAST | 37,192,700 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 114,998,460 | 34.0% |
| ENTER_EXECUTOR | 77,429,040 | 22.9% |
| RETURN_CONST | 48,321,543 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 36,003,940 | 10.6% |
| LOAD_DEREF | 20,988,440 | 6.2% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 233,765,853 | 68.5% |
| LOAD_ATTR_INSTANCE_VALUE | 77,788,315 | 22.8% |
| CALL_BUILTIN_FAST | 10,290,420 | 3.0% |
| LOAD_ATTR | 9,973,902 | 2.9% |
| COPY | 2,738,477 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 196,393,215 | 57.5% |
| POP_JUMP_IF_FALSE | 143,745,724 | 42.1% |
| TO_BOOL | 458,389 | 0.1% |
| UNARY_NOT | 379,876 | 0.1% |
| TO_BOOL_NONE | 195,002 | 0.1% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 63,189,433 | 87.4% |
| TO_BOOL_LIST | 4,191,132 | 5.8% |
| COMPARE_OP | 3,442,732 | 4.8% |
| TO_BOOL_INT | 573,446 | 0.8% |
| TO_BOOL_STR | 492,880 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 29,279,402 | 40.5% |
| RETURN_VALUE | 25,663,370 | 35.5% |
| LOAD_CONST | 13,722,988 | 19.0% |
| STORE_FAST | 1,193,939 | 1.7% |
| CALL_PY_EXACT_ARGS | 1,004,200 | 1.4% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 176,939,898 | 20.1% |
| LOAD_CONST | 163,128,813 | 18.6% |
| CALL_METHOD_DESCRIPTOR_O | 96,003,000 | 10.9% |
| LOAD_FAST_LOAD_FAST | 67,210,665 | 7.6% |
| BINARY_OP_ADD_INT | 56,113,464 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 173,373,542 | 19.7% |
| LOAD_FAST | 151,272,349 | 17.2% |
| LOAD_FAST_LOAD_FAST | 130,293,986 | 14.8% |
| RETURN_VALUE | 97,567,122 | 11.1% |
| SWAP | 55,070,660 | 6.3% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,929,742 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,286,120 | 44.3% |
| LOAD_FAST | 3,450,740 | 28.9% |
| LOAD_FAST_LOAD_FAST | 2,272,240 | 19.0% |
| CALL_METHOD_DESCRIPTOR_O | 510,720 | 4.3% |
| STORE_FAST | 328,222 | 2.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 146,192,192 | 40.9% |
| SWAP | 40,858,406 | 11.4% |
| LOAD_FAST | 40,068,626 | 11.2% |
| RESUME_CHECK | 23,087,150 | 6.5% |
| LOAD_CONST | 16,398,440 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 182,909,697 | 51.2% |
| LOAD_FAST | 67,392,602 | 18.9% |
| SWAP | 40,858,486 | 11.4% |
| CALL | 11,840,760 | 3.3% |
| RETURN_VALUE | 11,824,888 | 3.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,421,328 | 29.6% |
| STORE_FAST | 12,104,718 | 11.4% |
| SWAP | 11,698,875 | 11.0% |
| RESUME_CHECK | 10,291,661 | 9.7% |
| BUILD_TUPLE | 8,140,994 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,891,170 | 36.6% |
| STORE_FAST | 30,546,974 | 28.7% |
| SWAP | 11,698,875 | 11.0% |
| CALL_FUNCTION_EX | 9,507,960 | 8.9% |
| CALL_BUILTIN_FAST | 5,766,700 | 5.4% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 68,064,060 | 88.9% |
| LOAD_CONST | 8,514,440 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 48,929,440 | 63.9% |
| CALL | 15,953,700 | 20.8% |
| STORE_FAST | 4,742,380 | 6.2% |
| BINARY_OP_ADD_UNICODE | 2,681,520 | 3.5% |
| CALL_LIST_APPEND | 1,864,080 | 2.4% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 282,552,466 | 30.4% |
| LOAD_CONST | 223,102,428 | 24.0% |
| LOAD_FAST_LOAD_FAST | 185,945,137 | 20.0% |
| CALL | 50,285,324 | 5.4% |
| LOAD_GLOBAL_BUILTIN | 38,005,624 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 560,014,444 | 60.2% |
| LOAD_CONST | 97,373,221 | 10.5% |
| CALL_ISINSTANCE | 44,402,924 | 4.8% |
| YIELD_VALUE | 40,457,140 | 4.4% |
| STORE_FAST | 32,806,655 | 3.5% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 315,769,487 | 26.8% |
| LOAD_FAST_LOAD_FAST | 151,051,722 | 12.8% |
| PUSH_NULL | 98,334,256 | 8.3% |
| BINARY_SUBSCR_TUPLE_INT | 96,159,805 | 8.2% |
| ENTER_EXECUTOR | 94,081,196 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 474,225,095 | 40.2% |
| RESUME_CHECK | 202,497,244 | 17.2% |
| POP_TOP | 86,310,633 | 7.3% |
| LOAD_GLOBAL_MODULE | 56,037,107 | 4.8% |
| RETURN_VALUE | 51,991,913 | 4.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 94,453,742 | 52.8% |
| DICT_MERGE | 29,263,710 | 16.4% |
| LOAD_FAST | 23,170,630 | 13.0% |
| CALL_INTRINSIC_1 | 17,096,969 | 9.6% |
| BUILD_MAP | 9,507,960 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 107,418,739 | 60.1% |
| STORE_FAST | 28,185,785 | 15.8% |
| RESUME_CHECK | 15,703,323 | 8.8% |
| RETURN_VALUE | 8,379,764 | 4.7% |
| LOAD_FAST_LOAD_FAST | 6,654,200 | 3.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,515,680 | 78.9% |
| LIST_EXTEND | 28,682,525 | 19.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,757,500 | 1.9% |
| RERAISE | 55,200 | 0.0% |
| LIST_APPEND | 15,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 120,273,200 | 80.7% |
| CALL_FUNCTION_EX | 17,096,969 | 11.5% |
| LOAD_CONST | 8,794,600 | 5.9% |
| BUILD_MAP | 2,773,396 | 1.9% |
| RERAISE | 55,520 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 242,585,542 | 93.1% |
| ENTER_EXECUTOR | 17,994,731 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 122,057,198 | 46.8% |
| STORE_FAST | 65,010,567 | 24.9% |
| RETURN_VALUE | 27,005,737 | 10.4% |
| UNPACK_SEQUENCE_LIST | 14,181,920 | 5.4% |
| POP_TOP | 7,520,145 | 2.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 50,313,791 | 30.0% |
| LOAD_FAST_LOAD_FAST | 27,588,362 | 16.5% |
| LOAD_FAST | 23,600,210 | 14.1% |
| LOAD_ATTR_SLOT | 18,300,784 | 10.9% |
| LOAD_GLOBAL_MODULE | 13,971,330 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 106,560,895 | 63.6% |
| COPY | 17,145,478 | 10.2% |
| POP_JUMP_IF_TRUE | 16,752,975 | 10.0% |
| RETURN_VALUE | 9,640,921 | 5.8% |
| BINARY_OP | 6,162,440 | 3.7% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 313,201,184 | 28.2% |
| LOAD_FAST_LOAD_FAST | 307,611,694 | 27.7% |
| LOAD_GLOBAL_MODULE | 287,521,524 | 25.9% |
| BINARY_SUBSCR_DICT | 78,260,500 | 7.1% |
| LOAD_ATTR_INSTANCE_VALUE | 52,576,619 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 964,692,107 | 86.9% |
| POP_JUMP_IF_TRUE | 76,638,158 | 6.9% |
| RETURN_VALUE | 33,212,920 | 3.0% |
| COPY | 27,842,020 | 2.5% |
| EXTENDED_ARG | 4,143,420 | 0.4% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 283,160,302 | 24.0% |
| COPY | 277,134,380 | 23.5% |
| SWAP | 116,688,780 | 9.9% |
| LOAD_CONST | 109,731,532 | 9.3% |
| LOAD_FAST_LOAD_FAST | 101,354,580 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 277,360,726 | 23.5% |
| COPY | 277,134,380 | 23.5% |
| BINARY_SUBSCR_LIST_INT | 159,448,840 | 13.5% |
| BINARY_SUBSCR | 115,659,020 | 9.8% |
| COMPARE_OP_INT | 112,734,720 | 9.6% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 164,739,964 | 42.9% |
| CACHE | 134,092,509 | 34.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 36,978,504 | 9.6% |
| ENTER_EXECUTOR | 21,263,260 | 5.5% |
| CALL | 7,079,912 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 276,914,763 | 72.1% |
| RETURN_GENERATOR | 106,806,412 | 27.8% |
| MAKE_CELL | 103,960 | 0.0% |
| RESUME | 15,548 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,704,810 | 98.1% |
| LOAD_DEREF | 229,920 | 0.8% |
| LOAD_ATTR_INSTANCE_VALUE | 202,640 | 0.7% |
| RETURN_VALUE | 68,640 | 0.2% |
| BUILD_CONST_KEY_MAP | 21,760 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 29,263,710 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,520 | 77.0% |
| MAP_ADD | 4,680 | 20.6% |
| BUILD_CONST_KEY_MAP | 500 | 2.2% |
| BUILD_MAP | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 17,520 | 77.0% |
| BUILD_MAP | 4,300 | 18.9% |
| STORE_NAME | 520 | 2.3% |
| EXTENDED_ARG | 140 | 0.6% |
| LOAD_CONST | 140 | 0.6% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 844,467,580 | 35.0% |
| POP_JUMP_IF_TRUE | 520,297,525 | 21.6% |
| POP_JUMP_IF_FALSE | 261,073,799 | 10.8% |
| STORE_FAST | 157,343,402 | 6.5% |
| CALL_LIST_APPEND | 130,442,572 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 366,551,783 | 15.2% |
| POP_JUMP_IF_FALSE | 336,121,650 | 13.9% |
| FOR_ITER_LIST | 315,498,631 | 13.1% |
| FOR_ITER_TUPLE | 165,361,859 | 6.9% |
| SEND | 125,514,720 | 5.2% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 114,764,591 | 27.0% |
| LOAD_FAST | 57,262,220 | 13.5% |
| JUMP_BACKWARD | 44,005,236 | 10.4% |
| CALL_LIST_APPEND | 41,812,268 | 9.8% |
| POP_TOP | 34,038,500 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 161,383,853 | 38.0% |
| ENTER_EXECUTOR | 79,806,911 | 18.8% |
| POP_JUMP_IF_NONE | 49,130,568 | 11.6% |
| FOR_ITER_GEN | 34,776,120 | 8.2% |
| FOR_ITER | 27,468,452 | 6.5% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 351,124,078 | 70.2% |
| GET_ITER | 91,476,477 | 18.3% |
| EXTENDED_ARG | 27,468,452 | 5.5% |
| SWAP | 15,392,251 | 3.1% |
| LOAD_FAST | 11,645,227 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 268,480,369 | 53.7% |
| STORE_FAST | 121,737,391 | 24.3% |
| LOAD_FAST | 39,159,306 | 7.8% |
| RETURN_CONST | 24,551,867 | 4.9% |
| SWAP | 14,727,855 | 2.9% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 303,039,555 | 37.9% |
| LOAD_GLOBAL_MODULE | 243,927,310 | 30.5% |
| LOAD_FAST_LOAD_FAST | 152,358,158 | 19.1% |
| LOAD_GLOBAL_BUILTIN | 40,165,409 | 5.0% |
| LOAD_FAST | 25,252,661 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 668,529,297 | 83.7% |
| POP_JUMP_IF_TRUE | 73,290,653 | 9.2% |
| EXTENDED_ARG | 24,031,440 | 3.0% |
| YIELD_VALUE | 13,100,542 | 1.6% |
| STORE_FAST | 9,810,720 | 1.2% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 135,925,440 | 27.7% |
| STORE_FAST | 84,086,400 | 17.2% |
| POP_JUMP_IF_TRUE | 57,006,110 | 11.6% |
| STORE_SUBSCR_LIST_INT | 47,751,288 | 9.7% |
| LIST_APPEND | 27,591,190 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 351,124,078 | 71.7% |
| FOR_ITER_GEN | 91,232,295 | 18.6% |
| EXTENDED_ARG | 44,005,236 | 9.0% |
| RETURN_CONST | 2,757,120 | 0.6% |
| FOR_ITER_LIST | 383,348 | 0.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 309,982,248 | 100.0% |
| RESUME | 3,940 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 294,427,509 | 95.0% |
| SEND | 15,558,679 | 5.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 259,251,701 | 48.5% |
| POP_JUMP_IF_FALSE | 117,208,660 | 21.9% |
| POP_TOP | 54,497,727 | 10.2% |
| POP_JUMP_IF_NONE | 14,018,240 | 2.6% |
| LOAD_ATTR_SLOT | 13,647,700 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 212,108,589 | 39.7% |
| LOAD_FAST_LOAD_FAST | 104,822,030 | 19.6% |
| LOAD_CONST | 50,908,809 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 38,583,371 | 7.2% |
| LOAD_GLOBAL_MODULE | 35,159,682 | 6.6% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 30,784,668 | 30.9% |
| RETURN_VALUE | 20,184,901 | 20.2% |
| RETURN_GENERATOR | 17,923,760 | 18.0% |
| LOAD_FAST | 10,414,615 | 10.4% |
| CALL | 7,050,840 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 72,037,446 | 72.2% |
| JUMP_BACKWARD | 27,591,190 | 27.7% |
| LOAD_FAST | 128,000 | 0.1% |
| CALL_INTRINSIC_1 | 15,520 | 0.0% |
| LOAD_NAME | 4,820 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,222,956 | 64.5% |
| LOAD_ATTR_SLOT | 9,587,677 | 32.2% |
| LOAD_CONST | 499,680 | 1.7% |
| RETURN_VALUE | 331,948 | 1.1% |
| LOAD_DEREF | 104,400 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 28,682,525 | 96.2% |
| STORE_FAST | 527,508 | 1.8% |
| LOAD_FAST | 347,408 | 1.2% |
| UNPACK_SEQUENCE_LIST | 230,040 | 0.8% |
| BUILD_TUPLE | 7,400 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 907,602,136 | 60.4% |
| LOAD_GLOBAL_BUILTIN | 297,852,829 | 19.8% |
| LOAD_GLOBAL_MODULE | 147,569,130 | 9.8% |
| LOAD_ATTR_SLOT | 69,104,949 | 4.6% |
| LOAD_FAST_LOAD_FAST | 29,409,702 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 303,039,555 | 20.2% |
| STORE_FAST | 262,239,210 | 17.5% |
| LOAD_FAST | 258,176,687 | 17.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 105,830,029 | 7.0% |
| CALL | 66,994,622 | 4.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,837,131,223 | 34.2% |
| LOAD_CONST | 819,765,879 | 9.9% |
| STORE_ATTR_SLOT | 396,720,929 | 4.8% |
| LOAD_FAST_LOAD_FAST | 389,856,111 | 4.7% |
| POP_JUMP_IF_FALSE | 362,288,827 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,369,269,882 | 16.5% |
| BINARY_OP_ADD_INT | 874,301,973 | 10.6% |
| LOAD_CONST | 819,765,879 | 9.9% |
| COMPARE_OP_INT | 690,665,533 | 8.3% |
| STORE_FAST | 593,029,513 | 7.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 159,649,050 | 20.0% |
| STORE_FAST | 109,265,923 | 13.7% |
| POP_JUMP_IF_FALSE | 66,833,780 | 8.4% |
| STORE_FAST_STORE_FAST | 46,077,070 | 5.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 41,727,460 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 364,777,514 | 45.6% |
| LOAD_CONST | 96,917,863 | 12.1% |
| PUSH_NULL | 65,146,492 | 8.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 46,722,279 | 5.8% |
| LOAD_DEREF | 31,613,979 | 4.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,479,808,870 | 14.5% |
| POP_JUMP_IF_FALSE | 4,282,294,831 | 13.9% |
| LOAD_GLOBAL_BUILTIN | 3,168,937,396 | 10.3% |
| RESUME_CHECK | 2,895,648,572 | 9.4% |
| LOAD_CONST | 1,369,269,882 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,091,145,420 | 13.2% |
| LOAD_CONST | 2,837,131,223 | 9.2% |
| LOAD_ATTR_SLOT | 1,723,378,605 | 5.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,646,341,444 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 1,262,030,461 | 4.1% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 54,328,061 | 70.1% |
| LOAD_FAST_AND_CLEAR | 23,192,704 | 29.9% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 54,317,101 | 70.1% |
| LOAD_FAST_AND_CLEAR | 23,192,704 | 29.9% |
| MAKE_CELL | 11,040 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 859,788,956 | 11.9% |
| POP_JUMP_IF_FALSE | 616,463,706 | 8.6% |
| LOAD_GLOBAL_MODULE | 581,569,223 | 8.1% |
| LOAD_FAST_LOAD_FAST | 546,692,644 | 7.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 526,119,919 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 877,925,941 | 12.2% |
| CALL_PY_EXACT_ARGS | 749,745,038 | 10.4% |
| LOAD_FAST | 678,228,321 | 9.4% |
| LOAD_FAST_LOAD_FAST | 546,692,644 | 7.6% |
| BINARY_SUBSCR_STR_INT | 421,110,718 | 5.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 9,716,800 | 90.5% |
| STORE_FAST | 145,304 | 1.4% |
| LOAD_FAST | 139,977 | 1.3% |
| POP_JUMP_IF_FALSE | 131,010 | 1.2% |
| POP_TOP | 78,631 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,894,474 | 92.2% |
| LOAD_GLOBAL_MODULE | 320,965 | 3.0% |
| LOAD_GLOBAL_BUILTIN | 168,610 | 1.6% |
| LOAD_ATTR | 100,536 | 0.9% |
| LOAD_CONST | 59,081 | 0.6% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,325 | 98.4% |
| LOAD_DEREF | 220 | 1.3% |
| LOAD_GLOBAL | 20 | 0.1% |
| LOAD_GLOBAL_MODULE | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 7,460 | 45.0% |
| CALL | 3,385 | 20.4% |
| LOAD_FAST | 2,500 | 15.1% |
| LOAD_FAST_LOAD_FAST | 1,520 | 9.2% |
| LOAD_SUPER_ATTR_ATTR | 740 | 4.5% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 65,831,955 | 56.4% |
| CALL_PY_EXACT_ARGS | 33,713,194 | 28.9% |
| CALL_FUNCTION_EX | 6,276,648 | 5.4% |
| CALL_KW | 5,066,660 | 4.3% |
| CACHE | 1,702,354 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 65,831,955 | 56.4% |
| RESUME_CHECK | 50,048,788 | 42.9% |
| RETURN_GENERATOR | 776,160 | 0.7% |
| SWAP | 10,960 | 0.0% |
| RESUME | 9,900 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,114,540 | 39.4% |
| RETURN_VALUE | 8,423,020 | 15.7% |
| LOAD_FAST_LOAD_FAST | 8,303,985 | 15.5% |
| JUMP_FORWARD | 6,376,960 | 11.9% |
| CALL_BUILTIN_CLASS | 3,282,560 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,488,380 | 51.3% |
| JUMP_BACKWARD | 21,145,345 | 39.4% |
| ENTER_EXECUTOR | 3,301,980 | 6.2% |
| CALL_FUNCTION_EX | 1,615,360 | 3.0% |
| EXTENDED_ARG | 53,160 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,172,928,482 | 39.2% |
| COMPARE_OP_INT | 1,271,612,737 | 15.7% |
| CONTAINS_OP | 964,692,107 | 11.9% |
| IS_OP | 668,529,297 | 8.3% |
| TO_BOOL_NONE | 513,604,463 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,282,294,831 | 52.9% |
| LOAD_GLOBAL_BUILTIN | 1,172,581,293 | 14.5% |
| LOAD_FAST_LOAD_FAST | 616,463,706 | 7.6% |
| RETURN_CONST | 437,280,516 | 5.4% |
| LOAD_GLOBAL_MODULE | 375,025,693 | 4.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 330,210,309 | 68.9% |
| EXTENDED_ARG | 49,130,568 | 10.3% |
| LOAD_ATTR_INSTANCE_VALUE | 31,985,763 | 6.7% |
| LOAD_ATTR_SLOT | 31,403,760 | 6.6% |
| LOAD_DEREF | 19,146,251 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 290,580,724 | 60.6% |
| LOAD_DEREF | 36,545,400 | 7.6% |
| ENTER_EXECUTOR | 34,682,101 | 7.2% |
| LOAD_FAST_LOAD_FAST | 23,239,866 | 4.8% |
| JUMP_BACKWARD | 21,432,681 | 4.5% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 568,685,532 | 82.7% |
| LOAD_ATTR_INSTANCE_VALUE | 67,879,289 | 9.9% |
| LOAD_ATTR | 18,990,765 | 2.8% |
| EXTENDED_ARG | 9,629,100 | 1.4% |
| LOAD_ATTR_SLOT | 5,380,200 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 313,000,174 | 45.5% |
| LOAD_FAST_LOAD_FAST | 130,633,631 | 19.0% |
| LOAD_GLOBAL_MODULE | 79,510,744 | 11.6% |
| LOAD_GLOBAL_BUILTIN | 68,050,091 | 9.9% |
| RETURN_CONST | 27,157,176 | 4.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,036,265,518 | 51.9% |
| TO_BOOL | 196,393,215 | 9.8% |
| COMPARE_OP_INT | 140,047,889 | 7.0% |
| TO_BOOL_ALWAYS_TRUE | 104,877,525 | 5.3% |
| TO_BOOL_NONE | 95,028,193 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 866,948,882 | 43.4% |
| ENTER_EXECUTOR | 520,297,525 | 26.0% |
| LOAD_GLOBAL_BUILTIN | 143,199,166 | 7.2% |
| LOAD_CONST | 95,821,804 | 4.8% |
| POP_TOP | 86,521,818 | 4.3% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 437,280,516 | 21.2% |
| STORE_ATTR_SLOT | 383,261,407 | 18.6% |
| POP_TOP | 300,247,136 | 14.6% |
| STORE_ATTR_INSTANCE_VALUE | 229,988,696 | 11.2% |
| RESUME_CHECK | 176,702,401 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 849,266,083 | 41.2% |
| INTERPRETER_EXIT | 696,857,796 | 33.8% |
| EXIT_INIT_CHECK | 92,022,294 | 4.5% |
| TO_BOOL_BOOL | 82,650,314 | 4.0% |
| END_FOR | 76,103,409 | 3.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 125,514,720 | 76.2% |
| LOAD_CONST | 23,685,399 | 14.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 15,558,679 | 9.4% |
| SEND | 49,880 | 0.0% |
| SEND_GEN | 580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 141,189,599 | 85.7% |
| YIELD_VALUE | 15,547,039 | 9.4% |
| END_ASYNC_FOR | 8,000,000 | 4.9% |
| SEND | 49,880 | 0.0% |
| RESUME_CHECK | 10,200 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 97,122,881 | 98.7% |
| SET_FUNCTION_ATTRIBUTE | 1,230,605 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,701,220 | 60.7% |
| LOAD_GLOBAL_BUILTIN | 25,347,960 | 25.8% |
| STORE_FAST | 7,458,584 | 7.6% |
| CALL_PY_EXACT_ARGS | 2,664,900 | 2.7% |
| SET_FUNCTION_ATTRIBUTE | 1,230,605 | 1.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,255,505 | 57.3% |
| LOAD_FAST_LOAD_FAST | 21,080,313 | 29.3% |
| CALL | 6,424,560 | 8.9% |
| SWAP | 1,783,538 | 2.5% |
| CALL_KW | 801,120 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,038,586 | 29.2% |
| LOAD_DEREF | 17,937,108 | 24.9% |
| RETURN_CONST | 12,351,177 | 17.2% |
| LOAD_FAST_LOAD_FAST | 6,525,056 | 9.1% |
| ENTER_EXECUTOR | 5,701,620 | 7.9% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 35,847,240 | 38.8% |
| STORE_FAST | 25,637,040 | 27.7% |
| LOAD_CONST | 8,982,040 | 9.7% |
| LOAD_FAST | 3,888,640 | 4.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,579,620 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,893,200 | 31.3% |
| LOAD_DEREF | 19,610,656 | 21.2% |
| LOAD_FAST_LOAD_FAST | 17,925,685 | 19.4% |
| LOAD_FAST | 10,698,213 | 11.6% |
| LOAD_CONST | 6,214,220 | 6.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 953,435,468 | 11.2% |
| STORE_FAST | 698,622,255 | 8.2% |
| LOAD_CONST | 593,029,513 | 7.0% |
| CALL | 474,225,095 | 5.6% |
| BINARY_OP_ADD_INT | 436,271,027 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,479,808,870 | 52.6% |
| LOAD_FAST_LOAD_FAST | 859,788,956 | 10.1% |
| STORE_FAST | 698,622,255 | 8.2% |
| LOAD_GLOBAL_BUILTIN | 564,509,353 | 6.6% |
| LOAD_GLOBAL_MODULE | 509,067,894 | 6.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 13,471,400 | 37.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,249,560 | 34.1% |
| FOR_ITER_TUPLE | 4,918,239 | 13.7% |
| FOR_ITER | 3,307,041 | 9.2% |
| FOR_ITER_RANGE | 1,049,480 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 12,353,360 | 34.4% |
| LOAD_ATTR_SLOT | 3,830,358 | 10.7% |
| LOAD_CONST | 3,505,169 | 9.8% |
| TO_BOOL_ALWAYS_TRUE | 2,994,180 | 8.3% |
| LOAD_FAST | 2,530,471 | 7.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,048,603,098 | 52.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 502,358,243 | 25.1% |
| UNPACK_SEQUENCE_TUPLE | 193,674,158 | 9.7% |
| UNPACK_SEQUENCE_LIST | 146,487,172 | 7.3% |
| LOAD_ATTR_SLOT | 61,210,640 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,048,603,098 | 52.4% |
| LOAD_FAST | 585,938,194 | 29.3% |
| LOAD_FAST_LOAD_FAST | 120,943,330 | 6.0% |
| STORE_FAST | 68,778,989 | 3.4% |
| LOAD_GLOBAL_MODULE | 62,992,040 | 3.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 283,535,240 | 26.8% |
| BINARY_OP_ADD_FLOAT | 142,206,760 | 13.4% |
| LOAD_FAST | 131,008,948 | 12.4% |
| BINARY_OP_ADD_INT | 104,117,561 | 9.8% |
| BINARY_OP_SUBTRACT_FLOAT | 74,267,920 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 283,535,240 | 26.8% |
| STORE_SUBSCR_LIST_INT | 165,849,700 | 15.7% |
| COPY | 116,688,780 | 11.0% |
| STORE_SUBSCR | 115,669,300 | 10.9% |
| STORE_ATTR_INSTANCE_VALUE | 92,566,437 | 8.7% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 128,320 | 35.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 90,720 | 24.9% |
| LOAD_FAST | 34,697 | 9.5% |
| COPY | 26,720 | 7.3% |
| RETURN_VALUE | 24,382 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 212,244 | 58.2% |
| STORE_FAST | 108,008 | 29.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 24,651 | 6.8% |
| UNPACK_SEQUENCE_TUPLE | 13,245 | 3.6% |
| UNPACK_SEQUENCE | 2,599 | 0.7% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 366,551,783 | 35.0% |
| YIELD_VALUE | 294,445,801 | 28.1% |
| CALL_INTRINSIC_1 | 120,273,200 | 11.5% |
| LOAD_FAST | 64,363,794 | 6.1% |
| BINARY_OP_MULTIPLY_FLOAT | 41,716,800 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 628,421,265 | 59.9% |
| YIELD_VALUE | 294,445,801 | 28.1% |
| STORE_FAST | 86,966,855 | 8.3% |
| UNPACK_SEQUENCE_TUPLE | 33,452,960 | 3.2% |
| STORE_DEREF | 3,225,580 | 0.3% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 94,909 | 38.7% |
| CACHE | 70,279 | 28.7% |
| CALL_PY_EXACT_ARGS | 17,760 | 7.3% |
| COPY_FREE_VARS | 15,548 | 6.3% |
| POP_TOP | 13,381 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,844 | 41.2% |
| LOAD_GLOBAL | 57,431 | 23.4% |
| LOAD_CONST | 22,443 | 9.2% |
| LOAD_NAME | 18,760 | 7.7% |
| LOAD_FAST_LOAD_FAST | 9,084 | 3.7% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 874,301,973 | 66.3% |
| LOAD_FAST | 185,018,469 | 14.0% |
| LOAD_FAST_LOAD_FAST | 118,216,059 | 9.0% |
| END_SEND | 38,845,400 | 2.9% |
| BINARY_OP_MULTIPLY_INT | 30,460,116 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 436,271,027 | 33.1% |
| LOAD_CONST | 152,921,832 | 11.6% |
| SWAP | 104,117,561 | 7.9% |
| RETURN_VALUE | 99,224,600 | 7.5% |
| LOAD_FAST_LOAD_FAST | 84,284,140 | 6.4% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 96,946,560 | 40.8% |
| LOAD_FAST | 75,630,680 | 31.8% |
| LOAD_ATTR_INSTANCE_VALUE | 38,321,440 | 16.1% |
| BINARY_OP_SUBTRACT_FLOAT | 14,316,500 | 6.0% |
| BINARY_SUBSCR | 8,809,880 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 74,267,920 | 31.2% |
| LOAD_FAST_LOAD_FAST | 73,524,560 | 30.9% |
| LOAD_FAST | 37,905,560 | 15.9% |
| STORE_FAST | 31,681,646 | 13.3% |
| BINARY_OP_SUBTRACT_FLOAT | 14,316,500 | 6.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 343,141,404 | 75.3% |
| LOAD_FAST | 67,103,534 | 14.7% |
| LOAD_FAST_LOAD_FAST | 30,852,952 | 6.8% |
| LOAD_ATTR_INSTANCE_VALUE | 9,328,860 | 2.0% |
| CALL_LEN | 3,688,540 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 112,957,920 | 24.8% |
| STORE_FAST | 82,907,980 | 18.2% |
| SWAP | 59,151,654 | 13.0% |
| RETURN_VALUE | 53,087,840 | 11.6% |
| LOAD_CONST | 42,864,027 | 9.4% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 236,285,480 | 35.5% |
| LOAD_FAST | 235,354,187 | 35.3% |
| LOAD_FAST_LOAD_FAST | 107,238,509 | 16.1% |
| BINARY_SUBSCR | 49,285,320 | 7.4% |
| CALL_BUILTIN_O | 13,367,000 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 213,731,480 | 32.1% |
| RETURN_VALUE | 117,800,004 | 17.7% |
| CONTAINS_OP | 78,260,500 | 11.8% |
| LOAD_FAST | 66,877,799 | 10.0% |
| LOAD_ATTR_METHOD_NO_DICT | 55,588,760 | 8.3% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,805,187 | 35.8% |
| COPY | 159,448,840 | 20.3% |
| LOAD_FAST_LOAD_FAST | 141,906,550 | 18.1% |
| LOAD_CONST | 102,239,019 | 13.0% |
| UNARY_NEGATIVE | 34,943,080 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 149,146,260 | 19.1% |
| LOAD_CONST | 143,203,960 | 18.3% |
| STORE_FAST | 124,087,112 | 15.9% |
| RETURN_VALUE | 115,493,509 | 14.8% |
| LOAD_ATTR_INSTANCE_VALUE | 48,825,360 | 6.2% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 421,110,718 | 88.9% |
| BINARY_OP_SUBTRACT_INT | 14,186,040 | 3.0% |
| LOAD_ATTR_SLOT | 13,808,080 | 2.9% |
| LOAD_FAST | 11,248,360 | 2.4% |
| LOAD_CONST | 6,416,780 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 238,428,718 | 50.3% |
| STORE_FAST | 224,046,920 | 47.3% |
| LOAD_CONST | 5,784,800 | 1.2% |
| RETURN_VALUE | 4,367,000 | 0.9% |
| BINARY_OP_INPLACE_ADD_UNICODE | 306,900 | 0.1% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 214,464,975 | 96.8% |
| LOAD_FAST | 6,993,239 | 3.2% |
| BINARY_SUBSCR | 7,921 | 0.0% |
| LOAD_FAST_LOAD_FAST | 4,880 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 96,159,805 | 43.4% |
| LOAD_GLOBAL_MODULE | 40,468,560 | 18.3% |
| STORE_FAST | 12,582,360 | 5.7% |
| LOAD_CONST | 9,947,486 | 4.5% |
| LOAD_FAST | 9,139,830 | 4.1% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,060,186 | 40.5% |
| LOAD_CONST | 40,140,900 | 19.3% |
| BINARY_OP_MULTIPLY_INT | 30,018,280 | 14.5% |
| PUSH_NULL | 13,044,493 | 6.3% |
| RETURN_VALUE | 6,943,000 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 163,061,380 | 78.6% |
| COPY_FREE_VARS | 36,978,504 | 17.8% |
| GET_AWAITABLE | 2,994,800 | 1.4% |
| POP_TOP | 2,768,120 | 1.3% |
| MAKE_CELL | 884,556 | 0.4% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,017,630 | 27.3% |
| CALL_LEN | 31,397,590 | 18.2% |
| LOAD_GLOBAL_BUILTIN | 15,696,759 | 9.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 11,145,058 | 6.5% |
| LOAD_CONST | 6,981,840 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 69,021,940 | 40.1% |
| STORE_FAST | 25,699,102 | 14.9% |
| BINARY_OP_MULTIPLY_FLOAT | 16,972,000 | 9.9% |
| LOAD_FAST | 15,487,900 | 9.0% |
| RETURN_VALUE | 6,215,278 | 3.6% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 579,419,320 | 51.7% |
| LOAD_CONST | 323,171,403 | 28.9% |
| LOAD_FAST_LOAD_FAST | 113,617,443 | 10.1% |
| CALL_BUILTIN_FAST | 28,097,020 | 2.5% |
| LOAD_FAST | 26,358,023 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 653,713,960 | 58.4% |
| STORE_FAST | 306,226,688 | 27.3% |
| POP_TOP | 41,824,195 | 3.7% |
| RETURN_VALUE | 36,954,807 | 3.3% |
| CALL_BUILTIN_FAST | 28,097,020 | 2.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 43,092,280 | 61.7% |
| LOAD_FAST | 12,261,351 | 17.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 7,563,215 | 10.8% |
| LOAD_ATTR_INSTANCE_VALUE | 2,986,360 | 4.3% |
| LOAD_FAST_LOAD_FAST | 2,142,400 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 41,727,460 | 59.7% |
| STORE_FAST | 12,158,551 | 17.4% |
| CALL_TUPLE_1 | 4,707,655 | 6.7% |
| POP_TOP | 4,309,725 | 6.2% |
| LOAD_FAST | 3,036,920 | 4.3% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 777,792,592 | 74.5% |
| RETURN_VALUE | 72,238,900 | 6.9% |
| BUILD_STRING | 48,929,440 | 4.7% |
| LOAD_CONST | 46,934,960 | 4.5% |
| BINARY_OP_ADD_UNICODE | 21,212,480 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 418,800,097 | 40.1% |
| STORE_FAST | 232,178,108 | 22.2% |
| LOAD_CONST | 229,005,018 | 21.9% |
| RETURN_VALUE | 49,182,813 | 4.7% |
| TO_BOOL_BOOL | 22,421,013 | 2.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 545,763,601 | 50.5% |
| LOAD_GLOBAL_BUILTIN | 375,451,227 | 34.7% |
| LOAD_FAST_LOAD_FAST | 63,756,800 | 5.9% |
| BUILD_TUPLE | 44,402,924 | 4.1% |
| LOAD_ATTR_MODULE | 33,604,432 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,064,724,122 | 98.4% |
| COPY | 8,451,460 | 0.8% |
| YIELD_VALUE | 3,132,986 | 0.3% |
| RETURN_VALUE | 3,102,534 | 0.3% |
| STORE_FAST | 1,987,508 | 0.2% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 267,498,423 | 70.0% |
| LOAD_ATTR_INSTANCE_VALUE | 56,261,574 | 14.7% |
| LOAD_DEREF | 27,294,728 | 7.1% |
| LOAD_ATTR_SLOT | 11,067,360 | 2.9% |
| BINARY_OP | 4,114,840 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 106,485,497 | 27.9% |
| LOAD_FAST | 54,744,112 | 14.3% |
| COMPARE_OP_INT | 52,895,491 | 13.8% |
| STORE_FAST | 47,831,706 | 12.5% |
| CALL_BUILTIN_CLASS | 31,397,590 | 8.2% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 244,241,008 | 71.7% |
| ENTER_EXECUTOR | 53,659,593 | 15.7% |
| BINARY_OP | 7,151,040 | 2.1% |
| BINARY_SUBSCR_TUPLE_INT | 6,856,180 | 2.0% |
| RETURN_VALUE | 6,279,360 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 130,442,572 | 38.3% |
| LOAD_FAST | 99,233,640 | 29.1% |
| EXTENDED_ARG | 41,812,268 | 12.3% |
| RETURN_CONST | 26,220,120 | 7.7% |
| LOAD_CONST | 15,072,760 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 215,252,981 | 50.9% |
| LOAD_FAST_LOAD_FAST | 71,933,006 | 17.0% |
| LOAD_ATTR_METHOD_NO_DICT | 54,705,177 | 12.9% |
| LOAD_CONST | 30,187,330 | 7.1% |
| LOAD_GLOBAL_MODULE | 14,033,057 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 326,953,958 | 77.3% |
| LOAD_FAST | 27,072,450 | 6.4% |
| RETURN_VALUE | 15,644,570 | 3.7% |
| TO_BOOL_BOOL | 11,817,401 | 2.8% |
| POP_TOP | 10,609,712 | 2.5% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 152,234,596 | 51.9% |
| LOAD_ATTR | 105,830,029 | 36.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 22,731,533 | 7.7% |
| LOAD_ATTR_METHOD_LAZY_DICT | 9,921,545 | 3.4% |
| LOAD_FAST | 2,102,840 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 107,443,264 | 36.6% |
| GET_ITER | 57,181,347 | 19.5% |
| STORE_FAST | 46,243,706 | 15.8% |
| LOAD_GLOBAL_MODULE | 24,842,600 | 8.5% |
| LOAD_FAST | 16,673,418 | 5.7% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 334,464,831 | 81.2% |
| CALL | 43,919,940 | 10.7% |
| LOAD_GLOBAL_MODULE | 8,197,800 | 2.0% |
| LOAD_ATTR | 4,016,780 | 1.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 3,902,380 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 267,746,885 | 65.0% |
| BINARY_OP | 96,003,000 | 23.3% |
| RETURN_VALUE | 23,095,620 | 5.6% |
| LOAD_FAST | 8,923,800 | 2.2% |
| STORE_FAST | 4,965,619 | 1.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,103,937,435 | 33.0% |
| LOAD_FAST_LOAD_FAST | 749,745,038 | 22.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 599,101,940 | 17.9% |
| LOAD_GLOBAL_MODULE | 194,156,414 | 5.8% |
| LOAD_ATTR_METHOD_NO_DICT | 123,665,479 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,932,361,635 | 87.6% |
| RETURN_GENERATOR | 193,768,047 | 5.8% |
| COPY_FREE_VARS | 164,739,964 | 4.9% |
| MAKE_CELL | 33,713,194 | 1.0% |
| INSTRUMENTED_RESUME | 19,436,580 | 0.6% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 66,662,100 | 29.5% |
| LOAD_FAST | 47,351,461 | 21.0% |
| LOAD_FAST_LOAD_FAST | 41,612,724 | 18.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 15,823,855 | 7.0% |
| BINARY_OP_ADD_INT | 11,201,440 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 208,517,484 | 92.3% |
| RETURN_GENERATOR | 8,860,600 | 3.9% |
| COPY_FREE_VARS | 6,989,917 | 3.1% |
| MAKE_CELL | 1,396,528 | 0.6% |
| CALL_PY_EXACT_ARGS | 116,860 | 0.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,345,048 | 58.4% |
| RETURN_GENERATOR | 7,197,640 | 20.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,655 | 13.5% |
| LOAD_ATTR_SLOT | 1,464,712 | 4.2% |
| CALL | 585,340 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,088,420 | 54.8% |
| BINARY_OP | 4,711,435 | 13.5% |
| BUILD_TUPLE | 3,877,352 | 11.1% |
| YIELD_VALUE | 3,228,920 | 9.3% |
| STORE_FAST | 1,210,400 | 3.5% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 335,991,350 | 98.5% |
| LOAD_CONST | 4,947,316 | 1.5% |
| LOAD_GLOBAL_BUILTIN | 25,600 | 0.0% |
| LOAD_GLOBAL_MODULE | 5,200 | 0.0% |
| CALL | 3,121 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 267,147,308 | 78.3% |
| LOAD_GLOBAL_BUILTIN | 24,232,443 | 7.1% |
| LOAD_GLOBAL_MODULE | 18,122,980 | 5.3% |
| LOAD_FAST | 9,271,360 | 2.7% |
| COMPARE_OP | 5,882,735 | 1.7% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 690,665,533 | 45.7% |
| LOAD_FAST | 149,742,507 | 9.9% |
| LOAD_FAST_LOAD_FAST | 149,600,057 | 9.9% |
| LOAD_ATTR_INSTANCE_VALUE | 144,393,491 | 9.5% |
| COPY | 112,734,720 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,271,612,737 | 84.1% |
| POP_JUMP_IF_TRUE | 140,047,889 | 9.3% |
| RETURN_VALUE | 37,568,916 | 2.5% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 19,422,780 | 1.3% |
| LOAD_FAST | 14,297,700 | 0.9% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 302,319,686 | 88.5% |
| LOAD_FAST | 11,133,760 | 3.3% |
| LOAD_FAST_LOAD_FAST | 10,582,780 | 3.1% |
| RETURN_VALUE | 5,401,940 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 4,351,430 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 294,419,387 | 86.1% |
| POP_JUMP_IF_TRUE | 33,577,661 | 9.8% |
| RETURN_VALUE | 5,784,774 | 1.7% |
| COPY | 4,898,540 | 1.4% |
| EXTENDED_ARG | 1,635,360 | 0.5% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 91,232,295 | 45.2% |
| GET_ITER | 75,705,369 | 37.5% |
| EXTENDED_ARG | 34,776,120 | 17.2% |
| LOAD_FAST | 56,040 | 0.0% |
| FOR_ITER | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 125,514,495 | 62.2% |
| POP_TOP | 76,253,709 | 37.8% |
| RESUME | 2,080 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 920 | 0.0% |
| STORE_FAST | 480 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 315,498,631 | 45.3% |
| GET_ITER | 248,502,016 | 35.7% |
| LOAD_FAST | 79,718,024 | 11.4% |
| SWAP | 29,103,656 | 4.2% |
| EXTENDED_ARG | 22,357,960 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,151,396 | 34.5% |
| RETURN_CONST | 137,621,219 | 19.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 90,265,985 | 13.0% |
| LOAD_FAST | 87,553,792 | 12.6% |
| LOAD_FAST_LOAD_FAST | 65,614,040 | 9.4% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 36,693,279 | 40.1% |
| LOAD_FAST | 28,737,440 | 31.4% |
| GET_ITER | 19,473,665 | 21.3% |
| SWAP | 5,614,980 | 6.1% |
| EXTENDED_ARG | 877,280 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 32,433,290 | 35.4% |
| STORE_FAST | 25,506,154 | 27.9% |
| ENTER_EXECUTOR | 12,046,400 | 13.2% |
| LOAD_FAST | 7,396,588 | 8.1% |
| SWAP | 4,128,740 | 4.5% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 165,361,859 | 49.0% |
| GET_ITER | 163,595,158 | 48.5% |
| SWAP | 4,217,294 | 1.2% |
| LOAD_FAST | 2,037,556 | 0.6% |
| FOR_ITER_LIST | 1,315,264 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 162,680,142 | 48.2% |
| LOAD_FAST | 91,344,108 | 27.1% |
| LOAD_FAST_LOAD_FAST | 45,852,420 | 13.6% |
| RETURN_CONST | 20,261,703 | 6.0% |
| LOAD_GLOBAL_MODULE | 5,883,244 | 1.7% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,091,145,420 | 86.9% |
| LOAD_FAST_LOAD_FAST | 321,315,040 | 6.8% |
| COPY | 92,326,457 | 2.0% |
| LOAD_ATTR_INSTANCE_VALUE | 59,417,063 | 1.3% |
| ENTER_EXECUTOR | 53,324,060 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,179,385,520 | 25.0% |
| TO_BOOL_BOOL | 668,531,033 | 14.2% |
| STORE_FAST | 362,917,049 | 7.7% |
| LOAD_ATTR_METHOD_NO_DICT | 310,687,673 | 6.6% |
| RETURN_VALUE | 271,530,936 | 5.8% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 830,627,328 | 51.7% |
| LOAD_ATTR_INSTANCE_VALUE | 310,687,673 | 19.3% |
| LOAD_CONST | 115,668,060 | 7.2% |
| LOAD_GLOBAL_MODULE | 70,626,930 | 4.4% |
| BINARY_SUBSCR_DICT | 55,588,760 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 905,358,159 | 56.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 152,234,596 | 9.5% |
| LOAD_CONST | 150,119,016 | 9.3% |
| CALL_PY_EXACT_ARGS | 123,665,479 | 7.7% |
| LOAD_FAST_LOAD_FAST | 93,104,323 | 5.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,646,341,444 | 76.2% |
| LOAD_ATTR_SLOT | 122,448,508 | 5.7% |
| LOAD_ATTR_INSTANCE_VALUE | 105,917,347 | 4.9% |
| ENTER_EXECUTOR | 86,505,278 | 4.0% |
| LOAD_ATTR | 60,801,128 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 862,204,441 | 39.9% |
| CALL_PY_EXACT_ARGS | 599,101,940 | 27.7% |
| LOAD_FAST_LOAD_FAST | 526,119,919 | 24.4% |
| LOAD_CONST | 61,611,499 | 2.9% |
| LOAD_GLOBAL_MODULE | 60,380,860 | 2.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 510,702,111 | 96.6% |
| LOAD_ATTR_MODULE | 11,950,100 | 2.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,766,640 | 0.3% |
| LOAD_ATTR_CLASS | 1,546,560 | 0.3% |
| LOAD_FAST_LOAD_FAST | 1,238,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 427,162,516 | 80.8% |
| CALL_ISINSTANCE | 33,604,432 | 6.4% |
| LOAD_ATTR_MODULE | 11,950,100 | 2.3% |
| LOAD_FAST | 10,769,680 | 2.0% |
| LOAD_FAST_LOAD_FAST | 9,441,220 | 1.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,492,409 | 86.2% |
| LOAD_FAST_LOAD_FAST | 4,356,292 | 5.3% |
| LOAD_DEREF | 3,109,100 | 3.7% |
| ENTER_EXECUTOR | 2,966,550 | 3.6% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,302,633 | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT | 11,181,320 | 13.5% |
| CALL_BUILTIN_O | 5,612,946 | 6.8% |
| CONTAINS_OP | 5,597,120 | 6.7% |
| CALL_PY_EXACT_ARGS | 4,361,700 | 5.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 148,741,845 | 91.0% |
| LOAD_FAST_LOAD_FAST | 11,870,862 | 7.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,154,580 | 0.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,014,702 | 0.6% |
| ENTER_EXECUTOR | 469,927 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,002,299 | 25.1% |
| GET_ITER | 25,700,680 | 15.7% |
| LOAD_GLOBAL_BUILTIN | 20,517,540 | 12.6% |
| LOAD_ATTR_METHOD_NO_DICT | 12,596,500 | 7.7% |
| LOAD_FAST_LOAD_FAST | 11,971,580 | 7.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,412,547 | 77.5% |
| ENTER_EXECUTOR | 9,342,525 | 10.0% |
| LOAD_ATTR_SLOT | 6,457,567 | 6.9% |
| RETURN_VALUE | 2,311,422 | 2.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,026,700 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 76,736,777 | 82.1% |
| COPY_FREE_VARS | 5,276,294 | 5.6% |
| TO_BOOL_NONE | 4,445,470 | 4.8% |
| GET_ITER | 1,929,385 | 2.1% |
| RETURN_VALUE | 1,121,490 | 1.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,723,378,605 | 91.3% |
| LOAD_ATTR_SLOT | 54,732,165 | 2.9% |
| COPY | 45,508,320 | 2.4% |
| ENTER_EXECUTOR | 18,700,150 | 1.0% |
| LOAD_DEREF | 17,094,140 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 447,472,583 | 23.7% |
| TO_BOOL_NONE | 209,956,306 | 11.1% |
| COMPARE_OP_FLOAT | 127,794,075 | 6.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 122,448,508 | 6.5% |
| RETURN_VALUE | 83,826,870 | 4.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,262,030,461 | 24.9% |
| POP_JUMP_IF_FALSE | 1,172,581,293 | 23.2% |
| RESUME_CHECK | 1,119,554,677 | 22.1% |
| STORE_FAST | 564,509,353 | 11.2% |
| POP_JUMP_IF_TRUE | 143,199,166 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,168,937,396 | 62.6% |
| CALL_BUILTIN_FAST | 579,419,320 | 11.5% |
| CALL_ISINSTANCE | 375,451,227 | 7.4% |
| LOAD_ATTR | 297,852,829 | 5.9% |
| LOAD_DEREF | 159,649,050 | 3.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,230,634,086 | 32.2% |
| RESUME_CHECK | 510,642,410 | 13.4% |
| STORE_FAST | 509,067,894 | 13.3% |
| POP_JUMP_IF_FALSE | 375,025,693 | 9.8% |
| LOAD_FAST_LOAD_FAST | 133,635,406 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 604,278,692 | 15.8% |
| LOAD_FAST_LOAD_FAST | 581,569,223 | 15.2% |
| CALL_ISINSTANCE | 545,763,601 | 14.3% |
| LOAD_ATTR_MODULE | 510,702,111 | 13.4% |
| CONTAINS_OP | 287,521,524 | 7.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,932,361,635 | 42.9% |
| CACHE | 1,685,713,163 | 24.7% |
| POP_TOP | 377,859,678 | 5.5% |
| SEND_GEN | 294,411,629 | 4.3% |
| COPY_FREE_VARS | 276,914,763 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,895,648,572 | 42.4% |
| LOAD_GLOBAL_BUILTIN | 1,119,554,677 | 16.4% |
| POP_TOP | 725,786,392 | 10.6% |
| LOAD_GLOBAL_MODULE | 510,642,410 | 7.5% |
| LOAD_FAST_LOAD_FAST | 392,444,095 | 5.7% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 294,427,509 | 65.3% |
| LOAD_CONST | 156,660,450 | 34.7% |
| SEND | 4,620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 294,411,629 | 65.3% |
| POP_TOP | 156,647,550 | 34.7% |
| YIELD_VALUE | 15,060 | 0.0% |
| END_SEND | 15,020 | 0.0% |
| RESUME | 2,740 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 877,925,941 | 50.7% |
| LOAD_FAST | 805,338,119 | 46.5% |
| SWAP | 45,508,320 | 2.6% |
| STORE_ATTR_SLOT | 2,993,178 | 0.2% |
| LOAD_ATTR_SLOT | 848,420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 511,069,617 | 29.5% |
| LOAD_CONST | 396,720,929 | 22.9% |
| RETURN_CONST | 383,261,407 | 22.1% |
| LOAD_FAST | 359,945,427 | 20.8% |
| LOAD_GLOBAL_BUILTIN | 33,159,420 | 1.9% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 124,343,318 | 47.0% |
| LOAD_FAST | 88,867,402 | 33.6% |
| CALL_BUILTIN_O | 18,664,880 | 7.0% |
| RETURN_VALUE | 10,742,360 | 4.1% |
| BINARY_SUBSCR_TUPLE_INT | 5,092,440 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 97,229,240 | 36.7% |
| LOAD_FAST | 88,082,357 | 33.3% |
| RETURN_CONST | 23,535,980 | 8.9% |
| JUMP_BACKWARD | 18,940,680 | 7.2% |
| ENTER_EXECUTOR | 17,496,678 | 6.6% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 77,723,624 | 34.0% |
| LOAD_ATTR_INSTANCE_VALUE | 59,935,360 | 26.2% |
| ENTER_EXECUTOR | 51,911,420 | 22.7% |
| LOAD_ATTR_SLOT | 23,526,740 | 10.3% |
| COPY | 9,118,760 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 121,640,317 | 53.2% |
| POP_JUMP_IF_TRUE | 104,877,525 | 45.9% |
| EXTENDED_ARG | 1,209,080 | 0.5% |
| TO_BOOL_NONE | 739,306 | 0.3% |
| TO_BOOL_ALWAYS_TRUE | 155,881 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 1,064,724,122 | 24.3% |
| LOAD_FAST | 941,204,221 | 21.5% |
| LOAD_ATTR_INSTANCE_VALUE | 668,531,033 | 15.2% |
| CALL_BUILTIN_FAST | 653,713,960 | 14.9% |
| RETURN_VALUE | 342,606,932 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,172,928,482 | 72.3% |
| POP_JUMP_IF_TRUE | 1,036,265,518 | 23.6% |
| EXTENDED_ARG | 114,764,591 | 2.6% |
| UNARY_NOT | 63,189,433 | 1.4% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 18,040 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 136,584,014 | 66.0% |
| CALL_BUILTIN_O | 17,119,880 | 8.3% |
| COPY | 16,824,039 | 8.1% |
| BINARY_OP | 11,822,930 | 5.7% |
| LOAD_ATTR_SLOT | 9,236,400 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 161,192,614 | 77.9% |
| POP_JUMP_IF_TRUE | 44,914,375 | 21.7% |
| UNARY_NOT | 573,446 | 0.3% |
| EXTENDED_ARG | 218,628 | 0.1% |
| TO_BOOL_BOOL | 18,400 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,019,447 | 63.8% |
| LOAD_ATTR_INSTANCE_VALUE | 53,916,996 | 29.4% |
| LOAD_ATTR_SLOT | 6,507,680 | 3.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,285,220 | 1.2% |
| COPY | 1,124,580 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 94,507,370 | 51.6% |
| POP_JUMP_IF_TRUE | 83,270,315 | 45.4% |
| UNARY_NOT | 4,191,132 | 2.3% |
| EXTENDED_ARG | 1,303,740 | 0.7% |
| TO_BOOL | 30,920 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 218,989,310 | 35.8% |
| LOAD_ATTR_SLOT | 209,956,306 | 34.4% |
| LOAD_ATTR_INSTANCE_VALUE | 75,318,300 | 12.3% |
| LOAD_ATTR | 47,142,040 | 7.7% |
| RETURN_CONST | 18,545,220 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 513,604,463 | 84.1% |
| POP_JUMP_IF_TRUE | 95,028,193 | 15.6% |
| EXTENDED_ARG | 1,381,880 | 0.2% |
| TO_BOOL_ALWAYS_TRUE | 739,773 | 0.1% |
| TO_BOOL | 167,407 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,159,620 | 62.4% |
| LOAD_ATTR_SLOT | 9,521,020 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 5,790,920 | 7.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,026,060 | 5.2% |
| COPY | 3,628,380 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 40,854,980 | 52.9% |
| POP_JUMP_IF_TRUE | 35,731,660 | 46.3% |
| UNARY_NOT | 492,880 | 0.6% |
| TO_BOOL_NONE | 48,520 | 0.1% |
| TO_BOOL | 16,000 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 345,281,960 | 64.9% |
| LOAD_FAST | 135,563,501 | 25.5% |
| YIELD_VALUE | 33,452,960 | 6.3% |
| FOR_ITER | 8,305,980 | 1.6% |
| BINARY_SUBSCR_DICT | 6,550,620 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 337,690,221 | 63.5% |
| STORE_FAST_STORE_FAST | 193,674,158 | 36.4% |
| LOAD_FAST | 387,280 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 0.0% |
| UNPACK_SEQUENCE_LIST | 33,880 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 268,480,369 | 47.2% |
| RETURN_VALUE | 131,687,342 | 23.2% |
| FOR_ITER_LIST | 90,265,985 | 15.9% |
| LOAD_FAST | 48,712,342 | 8.6% |
| BINARY_SUBSCR_LIST_INT | 19,975,858 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 502,358,243 | 88.3% |
| STORE_FAST | 49,114,504 | 8.6% |
| STORE_FAST_LOAD_FAST | 12,249,560 | 2.2% |
| STORE_DEREF | 3,579,620 | 0.6% |
| LOAD_FAST | 1,208,960 | 0.2% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,986,640 | 99.7% |
| LOAD_ATTR_WITH_HINT | 8,140 | 0.3% |
| CALL | 240 | 0.0% |
| LOAD_FAST | 160 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 2,995,200 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,669,933 | 56.6% |
| RETURN_VALUE | 3,346,497 | 40.6% |
| LOAD_GLOBAL_MODULE | 95,751 | 1.2% |
| CALL | 65,800 | 0.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 53,480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,322,204 | 88.7% |
| STORE_FAST | 926,857 | 11.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 0.0% |
| UNPACK_SEQUENCE | 160 | 0.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 97,083,680 | 56.3% |
| BUILD_SLICE | 71,155,758 | 41.2% |
| LOAD_CONST | 3,834,900 | 2.2% |
| LOAD_FAST | 397,831 | 0.2% |
| CALL | 27,571 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,009,918 | 82.9% |
| LOAD_CONST | 24,138,411 | 14.0% |
| JUMP_FORWARD | 3,520,640 | 2.0% |
| ENTER_EXECUTOR | 1,111,360 | 0.6% |
| RETURN_CONST | 463,091 | 0.3% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 92,022,294 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 92,022,294 | 100.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 14,354,795 | 92.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 627,002 | 4.0% |
| LOAD_ATTR_MODULE | 365,724 | 2.4% |
| LOAD_FAST | 174,700 | 1.1% |
| LOAD_FAST_LOAD_FAST | 9,420 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 15,531,941 | 100.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_FAST | 40 | 0.0% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,771,520 | 88.5% |
| LOAD_CONST | 110,260 | 5.5% |
| LOAD_FAST | 102,976 | 5.1% |
| LOAD_GLOBAL_MODULE | 13,520 | 0.7% |
| LOAD_ATTR_MODULE | 1,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,771,520 | 88.5% |
| STORE_FAST | 64,580 | 3.2% |
| LOAD_GLOBAL_BUILTIN | 48,760 | 2.4% |
| CALL_PY_EXACT_ARGS | 45,400 | 2.3% |
| RETURN_VALUE | 32,416 | 1.6% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 95,116,890 | 98.9% |
| LOAD_FAST | 1,024,418 | 1.1% |
| LOAD_ATTR_INSTANCE_VALUE | 71,980 | 0.1% |
| BINARY_OP_ADD_INT | 2,120 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 71,155,758 | 74.0% |
| BINARY_SUBSCR | 25,055,870 | 26.0% |
| BINARY_SUBSCR_GETITEM | 3,840 | 0.0% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 129,971,238 | 85.7% |
| LOAD_FAST | 8,713,080 | 5.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,638,979 | 2.4% |
| RETURN_VALUE | 3,263,440 | 2.2% |
| BEFORE_ASYNC_WITH | 2,995,200 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 151,578,737 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 9,636,904 | 84.2% |
| STORE_FAST | 1,583,143 | 13.8% |
| STORE_DEREF | 185,708 | 1.6% |
| STORE_NAME | 33,920 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,292,388 | 81.2% |
| STORE_DEREF | 2,092,507 | 18.3% |
| STORE_NAME | 54,740 | 0.5% |
| EXTENDED_ARG | 2,540 | 0.0% |
| PUSH_EXC_INFO | 40 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,202,444 | 100.0% |
| ENTER_EXECUTOR | 100 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 9,636,904 | 94.5% |
| STORE_FAST | 552,960 | 5.4% |
| STORE_NAME | 10,660 | 0.1% |
| CALL_INTRINSIC_1 | 1,580 | 0.0% |
| STORE_DEREF | 320 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,823,239 | 39.7% |
| POP_TOP | 2,758,680 | 22.7% |
| POP_JUMP_IF_NONE | 1,680,936 | 13.8% |
| LOAD_ATTR_METHOD_NO_DICT | 1,580,705 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 565,400 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,771,619 | 39.2% |
| POP_JUMP_IF_NOT_NONE | 2,031,820 | 16.7% |
| LOAD_FAST | 1,723,881 | 14.2% |
| CALL_LIST_APPEND | 1,564,040 | 12.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 575,920 | 4.7% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,096,936 | 52.7% |
| LOAD_ATTR_MODULE | 778,140 | 19.6% |
| LOAD_GLOBAL_BUILTIN | 724,160 | 18.2% |
| LOAD_FAST | 201,280 | 5.1% |
| RETURN_VALUE | 73,920 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 3,177,936 | 79.9% |
| COPY | 596,180 | 15.0% |
| LOAD_CONST | 201,540 | 5.1% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 1,539,580 | 60.9% |
| POP_TOP | 516,120 | 20.4% |
| POP_JUMP_IF_FALSE | 208,320 | 8.2% |
| DELETE_FAST | 201,520 | 8.0% |
| CALL_INTRINSIC_1 | 55,520 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,488,520 | 60.1% |
| COPY | 931,880 | 37.6% |
| CALL_INTRINSIC_1 | 55,200 | 2.2% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 6,936,180 | 99.9% |
| RETURN_VALUE | 2,760 | 0.0% |
| LOAD_ATTR | 760 | 0.0% |
| LOAD_FAST | 440 | 0.0% |
| CALL | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,225,240 | 75.3% |
| LOAD_GLOBAL_MODULE | 1,713,320 | 24.7% |
| LOAD_CONST | 1,820 | 0.0% |
| LOAD_GLOBAL | 320 | 0.0% |
| RETURN_CONST | 220 | 0.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 245,901,340 | 62.5% |
| LOAD_FAST | 91,202,749 | 23.2% |
| RETURN_VALUE | 23,049,480 | 5.9% |
| BINARY_OP_MULTIPLY_INT | 11,249,600 | 2.9% |
| BINARY_OP | 8,120,760 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 142,206,760 | 36.1% |
| STORE_FAST | 90,528,126 | 23.0% |
| LOAD_FAST | 67,645,040 | 17.2% |
| RETURN_VALUE | 41,800,200 | 10.6% |
| LOAD_FAST_LOAD_FAST | 23,126,620 | 5.9% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 70,626,212 | 28.4% |
| LOAD_ATTR_INSTANCE_VALUE | 65,382,959 | 26.3% |
| LOAD_FAST_LOAD_FAST | 52,876,078 | 21.3% |
| BINARY_OP | 36,446,766 | 14.7% |
| LOAD_FAST | 12,025,320 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,404,368 | 23.9% |
| LOAD_CONST | 57,250,900 | 23.1% |
| LOAD_FAST_LOAD_FAST | 32,378,468 | 13.0% |
| BINARY_OP_ADD_INT | 30,460,116 | 12.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 30,018,280 | 12.1% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 55,519,720 | 29.2% |
| LOAD_CONST | 54,703,620 | 28.7% |
| ENTER_EXECUTOR | 41,451,400 | 21.8% |
| BUILD_TUPLE | 30,733,740 | 16.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,473,240 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 189,192,280 | 99.4% |
| MAKE_CELL | 1,100,036 | 0.6% |
| LOAD_ATTR_METHOD_NO_DICT | 7,680 | 0.0% |
| CONTAINS_OP | 6,060 | 0.0% |
| LOAD_FAST | 2,580 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 21,530,620 | 22.8% |
| ENTER_EXECUTOR | 16,895,940 | 17.9% |
| BINARY_OP_MULTIPLY_FLOAT | 11,171,080 | 11.8% |
| RETURN_CONST | 10,486,240 | 11.1% |
| BINARY_OP_ADD_FLOAT | 6,836,720 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 89,852,557 | 95.3% |
| LOAD_FAST | 2,217,180 | 2.4% |
| COPY_FREE_VARS | 2,169,597 | 2.3% |
| CALL_ALLOC_AND_ENTER_INIT | 43,040 | 0.0% |
| STORE_FAST | 19,640 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 42,945,860 | 80.0% |
| LOAD_ATTR_METHOD_NO_DICT | 5,256,340 | 9.8% |
| LOAD_FAST | 3,563,988 | 6.6% |
| LOAD_FAST_LOAD_FAST | 1,137,137 | 2.1% |
| LOAD_ATTR | 345,680 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 39,164,117 | 72.9% |
| CALL_METHOD_DESCRIPTOR_O | 3,902,380 | 7.3% |
| RETURN_VALUE | 3,006,680 | 5.6% |
| BINARY_OP | 2,681,320 | 5.0% |
| UNPACK_SEQUENCE_LIST | 1,065,920 | 2.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 90,715,933 | 84.8% |
| LOAD_GLOBAL_BUILTIN | 12,794,424 | 12.0% |
| LOAD_FAST | 1,975,800 | 1.8% |
| ENTER_EXECUTOR | 769,880 | 0.7% |
| LOAD_ATTR_MODULE | 473,880 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 29,042,320 | 27.1% |
| LOAD_FAST | 19,139,401 | 17.9% |
| COMPARE_OP_INT | 15,405,360 | 14.4% |
| LOAD_FAST_LOAD_FAST | 12,992,524 | 12.1% |
| PUSH_NULL | 11,046,080 | 10.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,169,188 | 98.2% |
| LOAD_DEREF | 77,440 | 1.8% |
| LOAD_SUPER_ATTR | 740 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 4,155,348 | 97.8% |
| LOAD_GLOBAL_MODULE | 86,080 | 2.0% |
| STORE_FAST | 5,760 | 0.1% |
| LOAD_GLOBAL | 160 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 166,140,566 | 100.0% |
| LOAD_DEREF | 11,960 | 0.0% |
| LOAD_SUPER_ATTR | 7,460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 92,955,015 | 55.9% |
| LOAD_FAST | 48,835,500 | 29.4% |
| CALL_PY_EXACT_ARGS | 14,316,590 | 8.6% |
| CALL_PY_WITH_DEFAULTS | 7,932,960 | 4.8% |
| LOAD_GLOBAL_MODULE | 861,501 | 0.5% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 549,153,478 | 48.8% |
| LOAD_FAST_LOAD_FAST | 400,925,454 | 35.6% |
| SWAP | 92,566,437 | 8.2% |
| BINARY_SUBSCR_LIST_INT | 36,129,520 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 17,061,800 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 419,412,642 | 37.2% |
| RETURN_CONST | 229,988,696 | 20.4% |
| LOAD_FAST_LOAD_FAST | 220,458,020 | 19.6% |
| LOAD_CONST | 115,106,779 | 10.2% |
| NOP | 71,815,709 | 6.4% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 14,440 | 76.2% |
| STORE_DEREF | 1,800 | 9.5% |
| POP_TOP | 1,280 | 6.8% |
| STORE_FAST | 440 | 2.3% |
| RETURN_VALUE | 240 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 18,940 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,225,464 | 88.8% |
| LOAD_FAST_LOAD_FAST | 10,670,216 | 6.6% |
| LOAD_GLOBAL_MODULE | 4,028,931 | 2.5% |
| BINARY_SUBSCR_TUPLE_INT | 1,607,500 | 1.0% |
| CALL_LEN | 927,540 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 105,861,200 | 65.6% |
| BINARY_SUBSCR_LIST_INT | 34,943,080 | 21.7% |
| CALL_PY_EXACT_ARGS | 4,254,800 | 2.6% |
| BINARY_SUBSCR | 3,225,560 | 2.0% |
| STORE_SUBSCR | 3,225,520 | 2.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 116,203,240 | 83.7% |
| LOAD_ATTR | 15,441,220 | 11.1% |
| CALL_METHOD_DESCRIPTOR_O | 2,681,260 | 1.9% |
| RETURN_VALUE | 2,058,840 | 1.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,138,100 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 138,785,820 | 100.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,285,120 | 71.5% |
| STORE_FAST | 297,120 | 16.5% |
| CALL | 108,000 | 6.0% |
| NOP | 24,000 | 1.3% |
| POP_EXCEPT | 24,000 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 648,420 | 36.1% |
| BUILD_LIST | 642,560 | 35.7% |
| RERAISE | 201,520 | 11.2% |
| RETURN_VALUE | 184,800 | 10.3% |
| RETURN_CONST | 48,000 | 2.7% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,738,940 | 48.4% |
| RESUME_CHECK | 5,281,700 | 37.9% |
| LOAD_NAME | 859,440 | 6.2% |
| STORE_NAME | 342,460 | 2.5% |
| BINARY_SUBSCR_DICT | 261,920 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,289,940 | 45.2% |
| LOAD_CONST | 5,816,060 | 41.8% |
| LOAD_NAME | 859,440 | 6.2% |
| STORE_SUBSCR_DICT | 278,780 | 2.0% |
| CONTAINS_OP | 262,640 | 1.9% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 1,280,880 | 87.1% |
| STORE_FAST_LOAD_FAST | 64,000 | 4.4% |
| LOAD_ATTR_INSTANCE_VALUE | 63,180 | 4.3% |
| LOAD_FAST | 43,120 | 2.9% |
| RETURN_VALUE | 13,860 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,352,960 | 92.0% |
| JUMP_BACKWARD | 117,480 | 8.0% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 279,420 | 30.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 276,160 | 29.8% |
| MAKE_FUNCTION | 103,460 | 11.2% |
| LOAD_CONST | 59,140 | 6.4% |
| IMPORT_FROM | 54,740 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 342,460 | 37.0% |
| STORE_NAME | 279,420 | 30.2% |
| LOAD_CONST | 191,940 | 20.7% |
| IMPORT_FROM | 33,920 | 3.7% |
| RETURN_CONST | 22,000 | 2.4% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,423,620 | 46.7% |
| BINARY_SLICE | 20,771,700 | 21.8% |
| LOAD_CONST | 14,784,460 | 15.6% |
| CALL_STR_1 | 3,202,800 | 3.4% |
| BUILD_STRING | 2,681,520 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,466,180 | 22.6% |
| CALL_BUILTIN_O | 21,212,480 | 22.3% |
| BUILD_TUPLE | 20,613,200 | 21.7% |
| LOAD_CONST | 11,741,080 | 12.4% |
| STORE_FAST | 7,251,880 | 7.6% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,637,040 | 78.1% |
| RETURN_VALUE | 5,576,640 | 16.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,638,320 | 4.8% |
| LOAD_ATTR_SLOT | 145,520 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 40,520 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 10,243,140 | 30.0% |
| STORE_FAST | 9,231,320 | 27.1% |
| RETURN_VALUE | 4,545,660 | 13.3% |
| LOAD_FAST | 4,242,780 | 12.4% |
| BINARY_OP_ADD_UNICODE | 3,202,800 | 9.4% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 127,794,075 | 68.7% |
| BINARY_SUBSCR | 31,176,840 | 16.8% |
| LOAD_GLOBAL_MODULE | 8,575,485 | 4.6% |
| LOAD_CONST | 8,006,000 | 4.3% |
| LOAD_FAST | 3,717,743 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 127,781,115 | 68.7% |
| POP_JUMP_IF_TRUE | 43,209,940 | 23.2% |
| POP_JUMP_IF_FALSE | 14,915,017 | 8.0% |
| COMPARE_OP | 480 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 165,849,700 | 53.3% |
| LOAD_FAST_LOAD_FAST | 48,440,000 | 15.6% |
| LOAD_CONST | 35,895,300 | 11.5% |
| LOAD_FAST | 33,500,040 | 10.8% |
| BINARY_SUBSCR_LIST_INT | 26,894,680 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 119,855,980 | 38.5% |
| LOAD_FAST_LOAD_FAST | 75,142,166 | 24.1% |
| ENTER_EXECUTOR | 61,415,986 | 19.7% |
| JUMP_BACKWARD | 47,751,288 | 15.3% |
| RETURN_CONST | 6,158,320 | 2.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 130,490,892 | 88.0% |
| CALL_KW | 14,181,920 | 9.6% |
| STORE_FAST | 1,602,100 | 1.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,065,920 | 0.7% |
| ENTER_EXECUTOR | 327,680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 146,487,172 | 98.8% |
| STORE_FAST | 1,721,380 | 1.2% |
| UNPACK_SEQUENCE_TUPLE | 23,720 | 0.0% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320 | 48.5% |
| LOAD_GLOBAL_BUILTIN | 120 | 18.2% |
| STORE_NAME | 100 | 15.2% |
| CALL | 80 | 12.1% |
| LOAD_GLOBAL | 40 | 6.1% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 374,400 | 56.0% |
| YIELD_VALUE | 291,340 | 43.6% |
| CALL_INTRINSIC_1 | 1,280 | 0.2% |
| FOR_ITER | 980 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 668,000 | 100.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 312,346,274 | 78.1% |
| LOAD_ATTR_INSTANCE_VALUE | 29,863,283 | 7.5% |
| LOAD_ATTR_WITH_HINT | 29,697,480 | 7.4% |
| COPY | 15,758,800 | 3.9% |
| LOAD_FAST_LOAD_FAST | 10,075,462 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 106,119,000 | 26.5% |
| COMPARE_OP_INT | 44,365,782 | 11.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 43,455,156 | 10.9% |
| STORE_FAST | 41,752,320 | 10.4% |
| LOAD_CONST | 35,456,680 | 8.9% |


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

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40,569,180 | 68.7% |
| LOAD_FAST | 18,446,612 | 31.3% |
| RETURN_VALUE | 7,640 | 0.0% |
| LOAD_ATTR | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,073,046 | 79.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,921,545 | 16.8% |
| LOAD_FAST_LOAD_FAST | 1,638,360 | 2.8% |
| CALL | 226,221 | 0.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 125,840 | 0.2% |


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

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 288,893,180 | 50.1% |
| LOAD_ATTR_INSTANCE_VALUE | 155,948,200 | 27.1% |
| LOAD_FAST_LOAD_FAST | 38,903,140 | 6.8% |
| ENTER_EXECUTOR | 31,071,420 | 5.4% |
| BINARY_SUBSCR | 26,268,940 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 245,901,340 | 42.7% |
| BINARY_OP_SUBTRACT_FLOAT | 96,946,560 | 16.8% |
| LOAD_FAST | 82,954,600 | 14.4% |
| YIELD_VALUE | 41,716,800 | 7.2% |
| STORE_FAST | 33,620,580 | 5.8% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,399,117 | 47.5% |
| LOAD_FAST_LOAD_FAST | 15,905,080 | 24.9% |
| SWAP | 15,758,800 | 24.6% |
| ENTER_EXECUTOR | 1,566,040 | 2.4% |
| LOAD_DEREF | 320,920 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,498,260 | 69.6% |
| RETURN_CONST | 5,899,158 | 9.2% |
| ENTER_EXECUTOR | 5,799,960 | 9.1% |
| LOAD_CONST | 3,945,180 | 6.2% |
| LOAD_FAST_LOAD_FAST | 3,077,280 | 4.8% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 320 | 50.0% |
| PUSH_EXC_INFO | 320 | 50.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,354,793 | 100.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,868,102 | 78.1% |
| NOP | 2,285,040 | 20.1% |
| RETURN_CONST | 200,371 | 1.8% |
| LOAD_GLOBAL_MODULE | 1,240 | 0.0% |
| LOAD_CONST | 80 | 0.0% |


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
| INSTRUMENTED_JUMP_BACKWARD | 5,912 | 52.4% |
| GET_ITER | 5,280 | 46.8% |
| SWAP | 80 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,992 | 53.2% |
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
| BINARY_OP_INPLACE_ADD_UNICODE | 4,080 | 40.8% |
| STORE_FAST | 4,080 | 40.8% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 1,272 | 12.7% |
| LIST_APPEND | 400 | 4.0% |
| POP_TOP | 80 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_FOR_ITER | 5,912 | 59.2% |
| LOAD_FAST | 4,080 | 40.8% |


</details>

### INSTRUMENTED_POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,092 | 52.8% |
| TO_BOOL | 4,280 | 31.9% |
| TO_BOOL_STR | 1,240 | 9.2% |
| TO_BOOL_NONE | 360 | 2.7% |
| COMPARE_OP_STR | 280 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,680 | 42.3% |
| LOAD_GLOBAL | 5,360 | 39.9% |
| INSTRUMENTED_JUMP_BACKWARD | 1,272 | 9.5% |
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

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 5,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 5,800 | 98.6% |
| TO_BOOL | 80 | 1.4% |


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

### SETUP_ANNOTATIONS

<details>
<summary> Successors and predecessors for SETUP_ANNOTATIONS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME | 40 | 50.0% |
| STORE_NAME | 40 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 50.0% |
| LOAD_NAME | 40 | 50.0% |


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


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 876,463,813 | 20.8% |
|          hit | 3,283,108,155 | 77.9% |
|         miss | 50,156,020 | 1.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 990,324 | 39.0% |
| Failure | 1,546,881 | 61.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| subtract different types | 775,010 | 50.1% |
| multiply different types | 246,302 | 15.9% |
| add different types | 190,076 | 12.3% |
| add other | 57,356 | 3.7% |
| and int | 52,879 | 3.4% |
| remainder | 52,730 | 3.4% |
| floor divide | 45,476 | 2.9% |
| true divide different types | 22,184 | 1.4% |
| lshift | 20,066 | 1.3% |
| rshift | 16,805 | 1.1% |
| xor | 15,984 | 1.0% |
| or | 15,642 | 1.0% |
| subtract other | 12,800 | 0.8% |
| true divide float | 9,024 | 0.6% |
| power | 5,108 | 0.3% |
| multiply other | 4,320 | 0.3% |
| true divide other | 2,880 | 0.2% |
| and other | 1,659 | 0.1% |
| and different types | 580 | 0.0% |


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
|     deferred | 700,112,061 | 23.1% |
|          hit | 2,331,614,063 | 76.8% |
|         miss | 4,759,269 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 184,221 | 43.0% |
| Failure | 243,761 | 57.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 78,640 | 32.3% |
| out of range | 76,364 | 31.3% |
| other | 56,593 | 23.2% |
| buffer int | 16,000 | 6.6% |
| list slice | 6,360 | 2.6% |
| code complex parameters | 4,380 | 1.8% |
| sequence int | 4,280 | 1.8% |
| buffer slice | 940 | 0.4% |
| tuple slice | 104 | 0.0% |
| string slice | 100 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 737,869,762,949,555,239,730 | 6,673,658,845,345.7% |
|        deopt | 22,840 | 0.0% |
|          hit | 9,634,304,378 | 87.1% |
|         miss | 243,128,825 | 2.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,044,632 | 86.0% |
| Failure | 820,058 | 14.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 174,400 | 21.3% |
| code complex parameters | 147,443 | 18.0% |
| no dict | 106,600 | 13.0% |
| meth descr varargs | 58,624 | 7.1% |
| class no vectorcall | 57,100 | 7.0% |
| cfunc noargs | 54,222 | 6.6% |
| class mutable | 50,395 | 6.1% |
| cfunc varargs keywords | 50,026 | 6.1% |
| other | 29,347 | 3.6% |
| init not python | 17,020 | 2.1% |
| meth descr varargs keywords | 14,259 | 1.7% |
| bound method | 11,970 | 1.5% |
| init not simple | 11,280 | 1.4% |
| cmethod | 10,820 | 1.3% |
| wrong number arguments | 8,500 | 1.0% |
| cfunc varargs | 7,280 | 0.9% |
| operator wrapper | 4,609 | 0.6% |
| method wrapper | 4,483 | 0.5% |
| str | 1,680 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 167,285,200 | 7.6% |
|          hit | 2,037,541,188 | 92.3% |
|         miss | 2,294,234 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 101,034 | 29.1% |
| Failure | 246,655 | 70.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 82,802 | 33.6% |
| different types | 52,055 | 21.1% |
| baseobject | 30,120 | 12.2% |
| other | 24,941 | 10.1% |
| tuple | 15,410 | 6.2% |
| float long | 15,162 | 6.1% |
| string | 10,640 | 4.3% |
| bool | 6,325 | 2.6% |
| list | 3,440 | 1.4% |
| bytes | 3,320 | 1.3% |
| set | 1,860 | 0.8% |
| long float | 580 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 737,869,762,948,879,415,656 | 40,362,343,748,580.0% |
|          hit | 1,186,989,158 | 64.9% |
|         miss | 140,789,422 | 7.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,703,895 | 90.6% |
| Failure | 280,772 | 9.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 110,921 | 39.5% |
| enumerate | 44,712 | 15.9% |
| set | 29,379 | 10.5% |
| other | 18,880 | 6.7% |
| zip | 18,660 | 6.6% |
| seq iter | 14,480 | 5.2% |
| dict values | 12,400 | 4.4% |
| reversed list | 9,200 | 3.3% |
| dict keys | 7,960 | 2.8% |
| itertools | 6,600 | 2.4% |
| ascii string | 5,260 | 1.9% |
| map | 1,380 | 0.5% |
| callable | 480 | 0.2% |
| bytes | 440 | 0.2% |
| string | 20 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 737,869,762,949,869,739,559 | 5,548,232,608,967.4% |
|        deopt | 1,460,840 | 0.0% |
|          hit | 11,056,218,480 | 83.1% |
|         miss | 741,056,515 | 5.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 14,616,430 | 93.1% |
| Failure | 1,080,290 | 6.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 319,242 | 29.6% |
| metaclass attribute | 239,438 | 22.2% |
| not managed dict | 134,580 | 12.5% |
| method | 121,449 | 11.2% |
| shadowed | 101,190 | 9.4% |
| mutable class | 66,747 | 6.2% |
| class method obj | 24,640 | 2.3% |
| overridden | 16,614 | 1.5% |
| class attr descriptor | 16,540 | 1.5% |
| non overriding descriptor | 11,800 | 1.1% |
| module attr not found | 8,780 | 0.8% |
| not in keys | 7,180 | 0.7% |
| class attr simple | 6,470 | 0.6% |
| builtin class method | 2,940 | 0.3% |
| non object slot | 2,680 | 0.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 10,249,572 | 0.1% |
|        deopt | 8,300 | 0.0% |
|          hit | 8,880,275,753 | 99.9% |
|         miss | 319,722 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 490,157 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,385 | 0.0% |
|          hit | 170,407,474 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,200 | 100.0% |
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
|     deferred | 164,754,178 | 26.8% |
|          hit | 451,061,919 | 73.2% |
|         miss | 30,660 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,620 | 8.4% |
| Failure | 50,460 | 91.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| async generator send | 33,180 | 65.8% |
| other | 14,020 | 27.8% |
| list | 3,260 | 6.5% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,058,283,696,216,168,289,953 | 135,505,562,897,539.0% |
|          hit | 2,664,580,917 | 89.0% |
|         miss | 258,325,346 | 8.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,985,839 | 98.2% |
| Failure | 93,828 | 1.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 48,580 | 51.8% |
| not in dict | 14,580 | 15.5% |
| overriding descriptor | 10,500 | 11.2% |
| not in keys | 7,000 | 7.5% |
| overridden | 4,120 | 4.4% |
| no dict | 3,000 | 3.2% |
| property | 2,720 | 2.9% |
| not managed dict | 2,508 | 2.7% |
| method | 800 | 0.9% |
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
|     deferred | 337,966,111 | 37.0% |
|          hit | 575,940,681 | 63.0% |
|         miss | 2,880 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 12,542 | 8.8% |
| Failure | 129,900 | 91.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 55,580 | 42.8% |
| py simple | 42,660 | 32.8% |
| dict subclass no override | 26,080 | 20.1% |
| out of range | 2,900 | 2.2% |
| bytearray int | 1,980 | 1.5% |
| other | 700 | 0.5% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,582,544,170,319,675,762,424 | 42,787,681,629,886.2% |
|          hit | 5,586,305,307 | 92.6% |
|         miss | 107,959,434 | 1.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,243,769 | 76.9% |
| Failure | 674,167 | 23.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 191,396 | 28.4% |
| other | 172,893 | 25.6% |
| tuple | 117,580 | 17.4% |
| mapping | 98,103 | 14.6% |
| dict | 31,160 | 4.6% |
| set | 27,317 | 4.1% |
| bytes | 18,218 | 2.7% |
| sequence | 14,300 | 2.1% |
| float | 1,740 | 0.3% |
| bytearray | 1,040 | 0.2% |
| memory view | 420 | 0.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 368,934,881,474,191,299,952 | 29,532,593,119,458.8% |
|          hit | 1,245,942,038 | 99.7% |
|         miss | 2,939,660 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 94,836 | 97.6% |
| Failure | 2,319 | 2.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 1,519 | 65.5% |
| iterator | 420 | 18.1% |
| other | 380 | 16.4% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 87,328,880,165 | 53.9% |
| Not specialized | 17,437,945,525 | 10.8% |
| Specialized hits | 55,726,761,620 | 34.4% |
| Specialized misses | 1,552,256,279 | 1.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR | 4,058,283,696,216,168,289,953 | 44.0% |
| TO_BOOL | 2,582,544,170,319,675,762,424 | 28.0% |
| LOAD_ATTR | 737,869,762,949,869,739,559 | 8.0% |
| CALL | 737,869,762,949,555,239,730 | 8.0% |
| FOR_ITER | 737,869,762,948,879,415,656 | 8.0% |
| UNPACK_SEQUENCE | 368,934,881,474,191,299,952 | 4.0% |
| BINARY_OP | 876,463,813 | 0.0% |
| BINARY_SUBSCR | 700,112,061 | 0.0% |
| STORE_SUBSCR | 337,966,111 | 0.0% |
| COMPARE_OP | 167,285,200 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 258,458,523 | 16.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 203,227,860 | 13.1% |
| STORE_ATTR_SLOT | 158,706,683 | 10.2% |
| CALL_PY_EXACT_ARGS | 127,771,287 | 8.2% |
| LOAD_ATTR_SLOT | 113,220,961 | 7.3% |
| STORE_ATTR_INSTANCE_VALUE | 99,544,143 | 6.4% |
| FOR_ITER_TUPLE | 70,465,895 | 4.5% |
| FOR_ITER_LIST | 70,315,127 | 4.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 68,356,894 | 4.4% |
| LOAD_ATTR_METHOD_NO_DICT | 66,560,152 | 4.3% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 1,997,173,185 | 27.9% |
| Calls to Python functions inlined | 5,156,278,995 | 72.1% |
| Calls via PyEval_EvalFrame (total) | 1,997,173,185 | 27.9% |
| Calls via PyEval_EvalFrame (vector) | 1,236,313,648 | 17.3% |
| Calls via PyEval_EvalFrame (generator) | 760,859,537 | 10.6% |
| Calls via PyEval_EvalFrame (legacy) | 5,294,180 | 0.1% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,231,000,528 | 17.2% |
| Calls via PyEval_EvalFrame (build class) | 18,940 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 339,643,175 | 4.7% |
| Calls via PyEval_EvalFrame (function ex) | 24,431,519 | 0.3% |
| Calls via PyEval_EvalFrame (api) | 222,045,787 | 3.1% |
| Calls via PyEval_EvalFrame (method) | 211,356,663 | 3.0% |
| Frame objects created | 63,617,746 | 0.9% |
| Frames pushed | 4,764,291,384 | 66.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 6,129,390,293 | 35.8% |
| Frees to freelist | 6,136,780,071 |  |
| Allocations | 10,998,593,452 | 64.2% |
| Allocations to 512 bytes | 10,884,375,937 | 63.5% |
| Allocations to 4 kbytes | 94,072,794 | 0.5% |
| Allocations over 4 kbytes | 20,144,721 | 0.1% |
| Frees | 11,328,820,236 |  |
| New values | 77,380,006 |  |
| Interpreter increfs | 85,376,967,993 | 77.4% |
| Interpreter decrefs | 98,688,286,708 | 78.1% |
| Increfs | 24,920,263,445 | 22.6% |
| Decrefs | 27,690,881,685 | 21.9% |
| Materialize dict (on request) | 5,304,000 | 6.9% |
| Materialize dict (new key) | 190,320 | 0.2% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 2,030,840 | 2.6% |
| Method cache hits | 2,965,674,270 |  |
| Method cache misses | 89,389,801 |  |
| Method cache collisions | 98,675,324 |  |
| Method cache dunder hits | 3,358,577,565 |  |
| Method cache dunder misses | 9,689,562 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 713,904 | 45,323,885 | 6,377,300,846 |
| 1 | 63,822 | 66,817,140 | 5,368,862,178 |
| 2 | 20,727 | 53,077,179 | 18,004,242,962 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 354,263 |  |
| Traces created | 46,519 | 13.1% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 1,936 | 0.5% |
| Trace too long | 5,394 | 1.5% |
| Trace too short | 307,744 | 86.9% |
| Inner loop found | 962 | 0.3% |
| Recursive call | 940 | 0.3% |
| Traces executed | 2,410,810,571 |  |
| Uops executed | 96,084,163,029 | 39.86 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 60 | 0.1% |
| <= 16 | 3,862 | 8.3% |
| <= 32 | 15,544 | 33.4% |
| <= 64 | 13,157 | 28.3% |
| <= 128 | 13,896 | 29.9% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 180 | 0.4% |
| <= 8 | 4,262 | 9.2% |
| <= 16 | 13,010 | 28.0% |
| <= 32 | 13,395 | 28.8% |
| <= 64 | 10,224 | 22.0% |
| <= 128 | 5,448 | 11.7% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 94,407,376 | 3.9% |
| <= 2 | 358,221,785 | 14.9% |
| <= 4 | 35,370,260 | 1.5% |
| <= 8 | 318,732,840 | 13.2% |
| <= 16 | 371,044,888 | 15.4% |
| <= 32 | 565,303,404 | 23.4% |
| <= 64 | 233,172,113 | 9.7% |
| <= 128 | 380,966,277 | 15.8% |
| <= 256 | 23,920,035 | 1.0% |
| <= 512 | 8,093,277 | 0.3% |
| <= 1,024 | 6,073,872 | 0.3% |
| <= 2,048 | 14,485,008 | 0.6% |
| <= 4,096 | 823,294 | 0.0% |
| <= 8,192 | 151,586 | 0.0% |
| <= 16,384 | 36,780 | 0.0% |
| <= 32,768 | 1,140 | 0.0% |
| <= 65,536 | 4,723 | 0.0% |
| <= 131,072 | 793 | 0.0% |
| <= 262,144 | 340 | 0.0% |
| <= 524,288 | 140 | 0.0% |
| <= 1,048,576 | 400 | 0.0% |
| <= 2,097,152 | 94 | 0.0% |
| <= 4,194,304 | 146 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 17,970,728,786 | 18.7% | 18.7% |  |
| _SET_IP | 12,040,836,930 | 12.5% | 31.2% |  |
| _CHECK_VALIDITY | 9,530,713,870 | 9.9% | 41.2% |  |
| STORE_FAST | 5,815,866,392 | 6.1% | 47.2% |  |
| LOAD_CONST | 5,253,452,686 | 5.5% | 52.7% |  |
| _GUARD_IS_FALSE_POP | 3,526,854,346 | 3.7% | 56.3% | 2.6% |
| _GUARD_TYPE_VERSION | 2,436,707,634 | 2.5% | 58.9% | 6.5% |
| _GUARD_BOTH_INT | 1,948,605,036 | 2.0% | 60.9% | 0.0% |
| COMPARE_OP_STR | 1,803,672,112 | 1.9% | 62.8% |  |
| _BINARY_OP_ADD_INT | 1,643,828,508 | 1.7% | 64.5% |  |
| _JUMP_TO_TOP | 1,608,915,651 | 1.7% | 66.2% |  |
| CONTAINS_OP | 1,572,558,470 | 1.6% | 67.8% |  |
| _EXIT_TRACE | 1,288,608,047 | 1.3% | 69.1% |  |
| _ITER_CHECK_LIST | 1,225,382,678 | 1.3% | 70.4% | 1.3% |
| _GUARD_NOT_EXHAUSTED_LIST | 1,208,927,532 | 1.3% | 71.7% | 21.7% |
| BINARY_SUBSCR_STR_INT | 1,187,188,762 | 1.2% | 72.9% | 0.0% |
| _GUARD_GLOBALS_VERSION | 1,185,002,412 | 1.2% | 74.2% | 0.4% |
| _ITER_NEXT_LIST | 946,799,876 | 1.0% | 75.1% |  |
| _GUARD_IS_TRUE_POP | 922,752,590 | 1.0% | 76.1% | 26.7% |
| _BINARY_SUBSCR | 797,679,219 | 0.8% | 76.9% |  |
| _GUARD_BOTH_FLOAT | 780,592,520 | 0.8% | 77.7% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 711,526,289 | 0.7% | 78.5% | 1.3% |
| _CHECK_PEP_523 | 711,526,289 | 0.7% | 79.2% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 704,812,890 | 0.7% | 80.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 704,812,890 | 0.7% | 80.7% |  |
| _GUARD_BUILTINS_VERSION | 702,422,546 | 0.7% | 81.4% | 0.0% |
| _LOAD_GLOBAL_BUILTINS | 702,420,646 | 0.7% | 82.2% |  |
| _CHECK_STACK_SPACE | 701,965,060 | 0.7% | 82.9% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 701,960,982 | 0.7% | 83.6% |  |
| _PUSH_FRAME | 701,960,982 | 0.7% | 84.3% |  |
| _SAVE_RETURN_OFFSET | 701,960,982 | 0.7% | 85.1% |  |
| _ITER_CHECK_RANGE | 642,288,798 | 0.7% | 85.7% | 0.1% |
| _GUARD_NOT_EXHAUSTED_RANGE | 641,610,078 | 0.7% | 86.4% | 5.7% |
| RESUME_CHECK | 626,993,326 | 0.7% | 87.1% |  |
| _ITER_NEXT_RANGE | 604,879,119 | 0.6% | 87.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 539,899,374 | 0.6% | 88.3% | 0.0% |
| _GUARD_KEYS_VERSION | 539,876,934 | 0.6% | 88.8% | 0.6% |
| _BINARY_OP_MULTIPLY_FLOAT | 527,422,940 | 0.5% | 89.4% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 507,288,469 | 0.5% | 89.9% |  |
| _LOAD_ATTR_SLOT | 495,319,985 | 0.5% | 90.4% |  |
| _LOAD_GLOBAL_MODULE | 477,734,034 | 0.5% | 90.9% |  |
| TO_BOOL_BOOL | 477,311,839 | 0.5% | 91.4% |  |
| _ITER_CHECK_TUPLE | 474,790,337 | 0.5% | 91.9% | 16.4% |
| _LOAD_ATTR_METHOD_NO_DICT | 441,148,331 | 0.5% | 92.4% |  |
| PUSH_NULL | 400,984,692 | 0.4% | 92.8% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 396,828,687 | 0.4% | 93.2% | 35.9% |
| COMPARE_OP_INT | 389,429,982 | 0.4% | 93.6% |  |
| BINARY_SUBSCR_LIST_INT | 373,873,353 | 0.4% | 94.0% | 0.0% |
| LOAD_DEREF | 339,052,226 | 0.4% | 94.3% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 337,551,512 | 0.4% | 94.7% |  |
| _ITER_NEXT_TUPLE | 254,238,702 | 0.3% | 94.9% |  |
| _BINARY_OP | 245,065,318 | 0.3% | 95.2% |  |
| COPY | 228,752,126 | 0.2% | 95.4% |  |
| _BINARY_OP_SUBTRACT_INT | 198,444,508 | 0.2% | 95.6% |  |
| SWAP | 192,824,224 | 0.2% | 95.8% |  |
| CALL_BUILTIN_FAST | 184,523,296 | 0.2% | 96.0% |  |
| _LOAD_ATTR | 182,543,769 | 0.2% | 96.2% |  |
| BINARY_SUBSCR_DICT | 170,752,851 | 0.2% | 96.4% |  |
| POP_TOP | 158,329,212 | 0.2% | 96.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 131,985,812 | 0.1% | 96.7% | 0.0% |
| _BINARY_OP_ADD_FLOAT | 131,231,820 | 0.1% | 96.8% |  |
| CALL_TYPE_1 | 126,009,607 | 0.1% | 97.0% |  |
| GET_ANEXT | 125,514,720 | 0.1% | 97.1% |  |
| _BINARY_OP_SUBTRACT_FLOAT | 121,937,760 | 0.1% | 97.2% |  |
| STORE_SLICE | 121,060,060 | 0.1% | 97.4% |  |
| TO_BOOL_INT | 120,407,563 | 0.1% | 97.5% | 0.0% |
| BUILD_SLICE | 115,518,240 | 0.1% | 97.6% |  |
| STORE_SUBSCR_LIST_INT | 110,667,960 | 0.1% | 97.7% |  |
| BUILD_LIST | 108,573,526 | 0.1% | 97.8% |  |
| CALL_ISINSTANCE | 108,283,856 | 0.1% | 97.9% |  |
| _BINARY_OP_MULTIPLY_INT | 105,880,500 | 0.1% | 98.1% |  |
| CALL_BUILTIN_O | 104,334,122 | 0.1% | 98.2% | 0.0% |
| _STORE_SUBSCR | 96,697,982 | 0.1% | 98.3% |  |
| CALL_INTRINSIC_1 | 92,590,942 | 0.1% | 98.4% |  |
| BINARY_SUBSCR_TUPLE_INT | 88,222,100 | 0.1% | 98.5% |  |
| LIST_EXTEND | 87,348,462 | 0.1% | 98.5% |  |
| _POP_FRAME | 80,117,119 | 0.1% | 98.6% |  |
| LIST_APPEND | 74,100,291 | 0.1% | 98.7% |  |
| GET_ITER | 68,697,450 | 0.1% | 98.8% |  |
| TO_BOOL_NONE | 59,899,780 | 0.1% | 98.8% | 90.2% |
| UNPACK_SEQUENCE_TUPLE | 59,344,580 | 0.1% | 98.9% | 0.6% |
| _CHECK_ATTR_MODULE | 53,588,277 | 0.1% | 99.0% |  |
| _LOAD_ATTR_MODULE | 53,588,277 | 0.1% | 99.0% |  |
| _COMPARE_OP | 51,559,432 | 0.1% | 99.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 51,545,700 | 0.1% | 99.1% |  |
| BUILD_TUPLE | 49,957,310 | 0.1% | 99.2% |  |
| CALL_LEN | 49,201,660 | 0.1% | 99.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 43,557,050 | 0.0% | 99.3% | 6.4% |
| _STORE_ATTR_SLOT | 42,300,461 | 0.0% | 99.3% |  |
| _LOAD_ATTR_WITH_HINT | 41,090,981 | 0.0% | 99.4% | 0.0% |
| _CHECK_ATTR_WITH_HINT | 41,090,981 | 0.0% | 99.4% |  |
| BINARY_SLICE | 40,939,680 | 0.0% | 99.4% |  |
| UNPACK_SEQUENCE_LIST | 38,510,280 | 0.0% | 99.5% | 0.0% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 37,365,889 | 0.0% | 99.5% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 37,365,889 | 0.0% | 99.6% |  |
| CALL_STR_1 | 35,874,120 | 0.0% | 99.6% |  |
| COMPARE_OP_FLOAT | 32,621,800 | 0.0% | 99.6% |  |
| _GUARD_IS_NOT_NONE_POP | 30,701,244 | 0.0% | 99.7% | 2.3% |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 29,426,820 | 0.0% | 99.7% |  |
| _CHECK_ATTR_CLASS | 27,503,740 | 0.0% | 99.7% | 2.8% |
| _LOAD_ATTR_CLASS | 26,733,860 | 0.0% | 99.7% |  |
| MAKE_FUNCTION | 26,163,505 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 21,876,158 | 0.0% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 21,272,758 | 0.0% | 99.8% |  |
| TO_BOOL_LIST | 16,357,435 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 15,169,028 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 13,579,660 | 0.0% | 99.9% | 0.0% |
| _GUARD_IS_NONE_POP | 12,041,605 | 0.0% | 99.9% | 14.0% |
| TO_BOOL_ALWAYS_TRUE | 11,309,760 | 0.0% | 99.9% | 93.0% |
| IS_OP | 11,023,515 | 0.0% | 99.9% |  |
| UNARY_NOT | 10,881,628 | 0.0% | 99.9% |  |
| _TO_BOOL | 8,070,114 | 0.0% | 99.9% |  |
| BUILD_MAP | 7,357,753 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 7,225,260 | 0.0% | 99.9% |  |
| DICT_MERGE | 7,044,220 | 0.0% | 99.9% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,688,199 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 5,424,710 | 0.0% | 100.0% | 6.4% |
| _STORE_ATTR_INSTANCE_VALUE | 5,076,930 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 3,752,117 | 0.0% | 100.0% |  |
| _CHECK_ATTR_METHOD_LAZY_DICT | 3,199,460 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_LAZY_DICT | 3,199,460 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 3,010,160 | 0.0% | 100.0% |  |
| MAP_ADD | 2,797,980 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 2,761,340 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 2,761,340 | 0.0% | 100.0% |  |
| _STORE_ATTR | 2,686,260 | 0.0% | 100.0% |  |
| SET_ADD | 2,683,640 | 0.0% | 100.0% |  |
| STORE_DEREF | 1,989,997 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,384,400 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 1,260,560 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 883,668 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 721,280 | 0.0% | 100.0% |  |
| BUILD_STRING | 547,340 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 376,856 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 311,780 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 139,700 | 0.0% | 100.0% |  |
| MAKE_CELL | 119,781 | 0.0% | 100.0% |  |
| LOAD_NAME | 110,080 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 89,040 | 0.0% | 100.0% |  |
| STORE_NAME | 37,460 | 0.0% | 100.0% |  |
| BUILD_SET | 7,040 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 6,708 | 0.0% | 100.0% |  |
| BEFORE_WITH | 5,306 | 0.0% | 100.0% |  |
| UNARY_INVERT | 4,500 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 2,560 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 1,640 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 239,364 |
| FOR_ITER_GEN | 67,420 |
| CALL | 5,998 |
| LOAD_ATTR_PROPERTY | 4,241 |
| YIELD_VALUE | 2,480 |
| CALL_LIST_APPEND | 2,320 |
| CALL_PY_WITH_DEFAULTS | 2,140 |
| CALL_KW | 1,641 |
| BINARY_SUBSCR_GETITEM | 1,480 |
| CALL_FUNCTION_EX | 920 |
| CALL_ALLOC_AND_ENTER_INIT | 700 |
| RETURN_GENERATOR | 160 |
| BINARY_OP_INPLACE_ADD_UNICODE | 140 |
| STORE_ATTR_WITH_HINT | 80 |
| SEND | 60 |
| IMPORT_NAME | 20 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 1,900 |


</details>

---
Stats gathered on: 2023-11-14
