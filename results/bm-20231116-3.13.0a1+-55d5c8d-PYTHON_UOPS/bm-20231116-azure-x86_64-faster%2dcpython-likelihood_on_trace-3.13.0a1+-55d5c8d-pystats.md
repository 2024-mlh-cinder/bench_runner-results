
# Pystats results

- benchmark: all
- fork: faster-cpython
- ref: likelihood-on-trace
- commit hash: 55d5c8d
- commit date: 2023-11-16T23:56:06+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 31,947,338,633 | 19.1% | 19.1% |  |
| STORE_FAST | 8,803,789,721 | 5.3% | 24.4% |  |
| LOAD_CONST | 8,700,959,833 | 5.2% | 29.6% |  |
| POP_JUMP_IF_FALSE | 8,253,551,284 | 4.9% | 34.6% |  |
| LOAD_FAST_LOAD_FAST | 7,325,103,342 | 4.4% | 39.0% |  |
| RESUME_CHECK | 6,983,172,281 | 4.2% | 43.2% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 5,388,181,499 | 3.2% | 46.4% | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 4,831,984,225 | 2.9% | 49.3% | 5.4% |
| RETURN_VALUE | 4,477,946,151 | 2.7% | 52.0% |  |
| TO_BOOL_BOOL | 4,443,596,886 | 2.7% | 54.6% | 0.0% |
| LOAD_GLOBAL_MODULE | 3,927,013,670 | 2.4% | 57.0% | 0.0% |
| POP_TOP | 3,592,155,760 | 2.2% | 59.1% |  |
| CALL_PY_EXACT_ARGS | 3,453,127,868 | 2.1% | 61.2% | 3.6% |
| ENTER_EXECUTOR | 2,461,328,356 | 1.5% | 62.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,211,179,890 | 1.3% | 64.0% | 9.2% |
| RETURN_CONST | 2,077,490,159 | 1.2% | 65.2% |  |
| LOAD_ATTR_SLOT | 2,032,693,811 | 1.2% | 66.5% | 5.6% |
| POP_JUMP_IF_TRUE | 2,031,321,254 | 1.2% | 67.7% |  |
| INTERPRETER_EXIT | 2,024,806,497 | 1.2% | 68.9% |  |
| STORE_FAST_STORE_FAST | 2,005,651,699 | 1.2% | 70.1% |  |
| STORE_ATTR_SLOT | 1,756,799,506 | 1.1% | 71.2% | 9.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,630,417,130 | 1.0% | 72.1% | 4.1% |
| COMPARE_OP_INT | 1,569,556,107 | 0.9% | 73.1% | 0.1% |
| LOAD_ATTR | 1,523,045,634 | 0.9% | 74.0% |  |
| PUSH_NULL | 1,396,278,324 | 0.8% | 74.8% |  |
| BINARY_OP_ADD_INT | 1,331,839,500 | 0.8% | 75.6% | 0.0% |
| CALL_BUILTIN_FAST | 1,244,752,565 | 0.7% | 76.4% | 0.0% |
| CALL | 1,209,046,644 | 0.7% | 77.1% |  |
| COPY | 1,191,851,061 | 0.7% | 77.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,129,217,390 | 0.7% | 78.5% | 8.8% |
| CONTAINS_OP | 1,124,264,855 | 0.7% | 79.2% |  |
| CALL_ISINSTANCE | 1,088,118,948 | 0.7% | 79.8% |  |
| SWAP | 1,077,519,993 | 0.6% | 80.5% |  |
| CALL_BUILTIN_O | 1,071,769,288 | 0.6% | 81.1% | 0.4% |
| YIELD_VALUE | 1,054,375,533 | 0.6% | 81.7% |  |
| NOP | 971,720,954 | 0.6% | 82.3% |  |
| BUILD_TUPLE | 941,760,828 | 0.6% | 82.9% |  |
| BINARY_OP | 919,387,275 | 0.6% | 83.4% |  |
| IS_OP | 853,306,576 | 0.5% | 83.9% |  |
| LOAD_DEREF | 812,882,562 | 0.5% | 84.4% |  |
| GET_ITER | 811,229,543 | 0.5% | 84.9% |  |
| BINARY_SUBSCR_LIST_INT | 806,074,987 | 0.5% | 85.4% | 0.5% |
| FOR_ITER_LIST | 709,267,442 | 0.4% | 85.8% | 9.9% |
| BINARY_SUBSCR | 699,152,156 | 0.4% | 86.2% |  |
| POP_JUMP_IF_NOT_NONE | 698,591,153 | 0.4% | 86.7% |  |
| BINARY_SUBSCR_DICT | 692,842,055 | 0.4% | 87.1% |  |
| TO_BOOL_NONE | 618,073,362 | 0.4% | 87.4% | 8.7% |
| BINARY_OP_MULTIPLY_FLOAT | 576,300,048 | 0.3% | 87.8% | 1.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 573,235,629 | 0.3% | 88.1% |  |
| JUMP_FORWARD | 545,955,772 | 0.3% | 88.5% |  |
| LOAD_ATTR_MODULE | 538,074,579 | 0.3% | 88.8% | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 533,070,263 | 0.3% | 89.1% | 0.3% |
| FOR_ITER | 510,805,373 | 0.3% | 89.4% |  |
| POP_JUMP_IF_NONE | 498,682,510 | 0.3% | 89.7% |  |
| JUMP_BACKWARD | 493,382,342 | 0.3% | 90.0% |  |
| BINARY_OP_SUBTRACT_INT | 475,410,222 | 0.3% | 90.3% | 0.1% |
| BINARY_SUBSCR_STR_INT | 472,998,340 | 0.3% | 90.6% | 0.1% |
| BUILD_LIST | 455,644,501 | 0.3% | 90.8% |  |
| SEND_GEN | 451,681,332 | 0.3% | 91.1% | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 441,456,323 | 0.3% | 91.4% | 9.7% |
| LOAD_ATTR_WITH_HINT | 431,237,456 | 0.3% | 91.6% | 0.5% |
| EXTENDED_ARG | 424,873,896 | 0.3% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 418,292,797 | 0.3% | 92.1% | 0.1% |
| BINARY_OP_ADD_FLOAT | 394,681,811 | 0.2% | 92.4% | 2.2% |
| COPY_FREE_VARS | 393,878,282 | 0.2% | 92.6% |  |
| CALL_LEN | 392,630,675 | 0.2% | 92.8% |  |
| RETURN_GENERATOR | 381,741,169 | 0.2% | 93.1% |  |
| CALL_TYPE_1 | 355,078,068 | 0.2% | 93.3% |  |
| TO_BOOL | 348,957,404 | 0.2% | 93.5% |  |
| STORE_SUBSCR | 346,931,638 | 0.2% | 93.7% |  |
| COMPARE_OP_STR | 346,473,689 | 0.2% | 93.9% | 0.2% |
| FOR_ITER_TUPLE | 344,351,214 | 0.2% | 94.1% | 20.4% |
| CALL_LIST_APPEND | 340,380,818 | 0.2% | 94.3% | 0.0% |
| STORE_SUBSCR_LIST_INT | 310,890,117 | 0.2% | 94.5% | 0.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 310,567,782 | 0.2% | 94.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 300,166,603 | 0.2% | 94.9% | 9.3% |
| END_SEND | 298,343,801 | 0.2% | 95.1% |  |
| BINARY_SLICE | 291,983,043 | 0.2% | 95.2% |  |
| STORE_SUBSCR_DICT | 267,956,397 | 0.2% | 95.4% |  |
| CALL_KW | 263,815,358 | 0.2% | 95.5% |  |
| BINARY_OP_MULTIPLY_INT | 248,923,054 | 0.1% | 95.7% | 4.6% |
| CALL_INTRINSIC_1 | 244,420,757 | 0.1% | 95.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 238,701,457 | 0.1% | 96.0% | 8.5% |
| TO_BOOL_ALWAYS_TRUE | 232,814,302 | 0.1% | 96.1% | 21.2% |
| CALL_PY_WITH_DEFAULTS | 227,205,405 | 0.1% | 96.3% | 3.1% |
| BINARY_SUBSCR_TUPLE_INT | 223,052,378 | 0.1% | 96.4% | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 214,860,956 | 0.1% | 96.5% | 18.2% |
| TO_BOOL_INT | 209,958,812 | 0.1% | 96.6% | 0.6% |
| COMPARE_OP_FLOAT | 203,610,062 | 0.1% | 96.8% | 0.0% |
| FOR_ITER_GEN | 201,178,450 | 0.1% | 96.9% | 0.0% |
| TO_BOOL_LIST | 192,478,744 | 0.1% | 97.0% | 0.9% |
| BINARY_SUBSCR_GETITEM | 190,892,142 | 0.1% | 97.1% | 0.0% |
| CALL_FUNCTION_EX | 190,560,798 | 0.1% | 97.2% |  |
| CALL_BUILTIN_CLASS | 179,233,731 | 0.1% | 97.3% | 0.0% |
| DELETE_SUBSCR | 177,433,786 | 0.1% | 97.4% |  |
| COMPARE_OP | 167,857,474 | 0.1% | 97.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 166,960,656 | 0.1% | 97.6% | 40.9% |
| LOAD_SUPER_ATTR_METHOD | 166,710,800 | 0.1% | 97.7% |  |
| SEND | 165,323,407 | 0.1% | 97.8% |  |
| UNARY_NEGATIVE | 162,182,415 | 0.1% | 97.9% |  |
| FORMAT_SIMPLE | 152,295,364 | 0.1% | 98.0% |  |
| GET_AWAITABLE | 152,094,564 | 0.1% | 98.1% |  |
| UNPACK_SEQUENCE_LIST | 148,230,245 | 0.1% | 98.2% | 0.8% |
| CONVERT_VALUE | 138,348,875 | 0.1% | 98.3% |  |
| LOAD_ATTR_CLASS | 130,694,437 | 0.1% | 98.4% | 1.4% |
| LIST_EXTEND | 125,249,844 | 0.1% | 98.5% |  |
| BUILD_MAP | 121,151,983 | 0.1% | 98.5% |  |
| MAKE_CELL | 120,881,606 | 0.1% | 98.6% |  |
| MAKE_FUNCTION | 111,147,623 | 0.1% | 98.7% |  |
| LIST_APPEND | 106,853,334 | 0.1% | 98.7% |  |
| SET_FUNCTION_ATTRIBUTE | 100,038,938 | 0.1% | 98.8% |  |
| BINARY_OP_ADD_UNICODE | 96,879,200 | 0.1% | 98.8% | 0.0% |
| BUILD_SLICE | 95,917,885 | 0.1% | 98.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 94,487,667 | 0.1% | 99.0% | 2.4% |
| LOAD_ATTR_PROPERTY | 93,661,412 | 0.1% | 99.0% | 12.2% |
| STORE_DEREF | 93,270,411 | 0.1% | 99.1% |  |
| EXIT_INIT_CHECK | 92,200,167 | 0.1% | 99.1% |  |
| FOR_ITER_RANGE | 92,017,608 | 0.1% | 99.2% | 0.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 83,040,860 | 0.0% | 99.2% | 19.0% |
| LOAD_FAST_AND_CLEAR | 80,812,015 | 0.0% | 99.3% |  |
| TO_BOOL_STR | 78,018,229 | 0.0% | 99.3% | 4.5% |
| BUILD_STRING | 76,821,414 | 0.0% | 99.4% |  |
| END_FOR | 76,107,046 | 0.0% | 99.4% |  |
| UNARY_NOT | 72,611,738 | 0.0% | 99.5% |  |
| STORE_ATTR | 72,394,658 | 0.0% | 99.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 72,123,874 | 0.0% | 99.6% | 0.1% |
| STORE_ATTR_WITH_HINT | 65,379,357 | 0.0% | 99.6% | 0.1% |
| LOAD_ATTR_METHOD_LAZY_DICT | 59,282,964 | 0.0% | 99.6% | 0.0% |
| MAP_ADD | 57,590,400 | 0.0% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 54,617,968 | 0.0% | 99.7% | 4.3% |
| CALL_STR_1 | 40,753,800 | 0.0% | 99.7% |  |
| STORE_FAST_LOAD_FAST | 40,439,882 | 0.0% | 99.7% |  |
| STORE_SLICE | 39,061,174 | 0.0% | 99.8% |  |
| DICT_MERGE | 38,106,410 | 0.0% | 99.8% |  |
| CALL_TUPLE_1 | 35,177,001 | 0.0% | 99.8% | 0.0% |
| PUSH_EXC_INFO | 23,633,498 | 0.0% | 99.8% |  |
| POP_EXCEPT | 23,633,348 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 23,009,744 | 0.0% | 99.9% |  |
| GET_YIELD_FROM_ITER | 20,767,929 | 0.0% | 99.9% |  |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 19,465,840 | 0.0% | 99.9% |  |
| INSTRUMENTED_RESUME | 19,443,620 | 0.0% | 99.9% |  |
| INSTRUMENTED_RETURN_VALUE | 19,434,720 | 0.0% | 99.9% |  |
| UNARY_INVERT | 15,527,891 | 0.0% | 99.9% |  |
| LOAD_NAME | 13,936,780 | 0.0% | 99.9% |  |
| BUILD_CONST_KEY_MAP | 12,331,998 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 11,706,201 | 0.0% | 99.9% |  |
| IMPORT_FROM | 11,645,283 | 0.0% | 99.9% |  |
| DELETE_ATTR | 11,363,293 | 0.0% | 99.9% |  |
| LOAD_GLOBAL | 10,840,710 | 0.0% | 100.0% |  |
| IMPORT_NAME | 10,404,755 | 0.0% | 100.0% |  |
| BEFORE_WITH | 10,375,727 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 8,108,800 | 0.0% | 100.0% |  |
| GET_ANEXT | 8,000,960 | 0.0% | 100.0% |  |
| END_ASYNC_FOR | 8,000,000 | 0.0% | 100.0% |  |
| GET_AITER | 8,000,000 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 6,941,800 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 4,251,836 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 3,984,952 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 3,005,938 | 0.0% | 100.0% |  |
| RERAISE | 2,886,357 | 0.0% | 100.0% |  |
| BUILD_SET | 2,603,800 | 0.0% | 100.0% |  |
| DELETE_FAST | 2,132,160 | 0.0% | 100.0% |  |
| SET_ADD | 1,648,200 | 0.0% | 100.0% |  |
| STORE_NAME | 940,500 | 0.0% | 100.0% |  |
| UNPACK_EX | 756,000 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 373,436 | 0.0% | 100.0% |  |
| RESUME | 271,181 | 0.0% | 100.0% | 184.2% |
| WITH_EXCEPT_START | 184,307 | 0.0% | 100.0% |  |
| SET_UPDATE | 88,680 | 0.0% | 100.0% |  |
| DICT_UPDATE | 65,126 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 19,880 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 18,427 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 13,448 | 0.0% | 100.0% |  |
| INSTRUMENTED_FOR_ITER | 11,288 | 0.0% | 100.0% |  |
| INSTRUMENTED_JUMP_BACKWARD | 10,008 | 0.0% | 100.0% |  |
| INSTRUMENTED_RETURN_CONST | 7,200 | 0.0% | 100.0% |  |
| LOAD_LOCALS | 3,860 | 0.0% | 100.0% |  |
| LOAD_FROM_DICT_OR_DEREF | 3,840 | 0.0% | 100.0% |  |
| DELETE_DEREF | 1,600 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 1,523 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 4,579,450,834 | 2.7% | 2.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 4,382,926,047 | 2.6% | 5.4% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 4,176,426,445 | 2.5% | 7.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,448,318,843 | 2.1% | 9.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,219,154,885 | 1.9% | 11.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 3,009,198,866 | 1.8% | 13.7% |
| LOAD_FAST LOAD_CONST | 2,998,927,782 | 1.8% | 15.5% |
| RESUME_CHECK LOAD_FAST | 2,972,031,668 | 1.8% | 17.3% |
| LOAD_FAST LOAD_ATTR_SLOT | 1,874,103,337 | 1.1% | 18.4% |
| CACHE RESUME_CHECK | 1,710,258,453 | 1.0% | 19.4% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,703,604,841 | 1.0% | 20.4% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,406,201,552 | 0.8% | 21.3% |
| LOAD_CONST LOAD_FAST | 1,404,251,676 | 0.8% | 22.1% |
| POP_TOP LOAD_FAST | 1,368,228,276 | 0.8% | 22.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,324,483,541 | 0.8% | 23.7% |
| LOAD_FAST RETURN_VALUE | 1,284,440,249 | 0.8% | 24.5% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,250,804,316 | 0.7% | 25.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 1,232,807,662 | 0.7% | 26.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 1,184,101,594 | 0.7% | 26.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,141,990,979 | 0.7% | 27.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,133,312,324 | 0.7% | 28.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,070,632,626 | 0.6% | 28.7% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 1,048,652,150 | 0.6% | 29.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,046,437,708 | 0.6% | 29.9% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 977,253,567 | 0.6% | 30.5% |
| RETURN_VALUE STORE_FAST | 976,225,295 | 0.6% | 31.1% |
| LOAD_CONST LOAD_CONST | 960,787,209 | 0.6% | 31.7% |
| LOAD_FAST TO_BOOL_BOOL | 946,135,255 | 0.6% | 32.3% |
| LOAD_FAST LOAD_ATTR | 921,788,658 | 0.6% | 32.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 919,077,424 | 0.6% | 33.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 888,848,060 | 0.5% | 33.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 885,170,759 | 0.5% | 34.4% |
| LOAD_CONST BINARY_OP_ADD_INT | 883,903,011 | 0.5% | 35.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 880,223,159 | 0.5% | 35.5% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 878,350,906 | 0.5% | 36.0% |
| RETURN_CONST POP_TOP | 860,042,470 | 0.5% | 36.5% |
| POP_TOP ENTER_EXECUTOR | 854,081,204 | 0.5% | 37.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 838,720,018 | 0.5% | 37.5% |
| LOAD_FAST STORE_ATTR_SLOT | 821,568,452 | 0.5% | 38.0% |
| LOAD_FAST CALL_BUILTIN_O | 781,322,879 | 0.5% | 38.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 753,046,060 | 0.5% | 39.0% |
| LOAD_FAST LOAD_FAST | 746,746,654 | 0.4% | 39.4% |
| LOAD_FAST PUSH_NULL | 731,973,574 | 0.4% | 39.8% |
| RESUME_CHECK POP_TOP | 728,168,593 | 0.4% | 40.3% |
| RETURN_VALUE RETURN_VALUE | 717,306,649 | 0.4% | 40.7% |
| LOAD_CONST COMPARE_OP_INT | 710,284,963 | 0.4% | 41.1% |
| IS_OP POP_JUMP_IF_FALSE | 704,786,509 | 0.4% | 41.6% |
| RETURN_CONST INTERPRETER_EXIT | 703,472,103 | 0.4% | 42.0% |
| STORE_FAST STORE_FAST | 701,304,247 | 0.4% | 42.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 687,237,535 | 0.4% | 42.8% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 687,165,494 | 0.4% | 43.2% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 673,389,295 | 0.4% | 43.6% |
| PUSH_NULL LOAD_FAST | 662,649,919 | 0.4% | 44.0% |
| RETURN_VALUE INTERPRETER_EXIT | 656,007,730 | 0.4% | 44.4% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 654,281,422 | 0.4% | 44.8% |
| YIELD_VALUE INTERPRETER_EXIT | 634,596,897 | 0.4% | 45.2% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 627,221,047 | 0.4% | 45.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 623,139,748 | 0.4% | 45.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 619,366,351 | 0.4% | 46.3% |
| LOAD_CONST STORE_FAST | 603,078,158 | 0.4% | 46.7% |
| STORE_FAST_STORE_FAST LOAD_FAST | 589,015,541 | 0.4% | 47.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 584,129,390 | 0.4% | 47.4% |
| LOAD_GLOBAL_BUILTIN CALL_BUILTIN_FAST | 579,419,620 | 0.3% | 47.7% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 578,372,797 | 0.3% | 48.1% |
| BUILD_TUPLE RETURN_VALUE | 563,055,018 | 0.3% | 48.4% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 549,613,080 | 0.3% | 48.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 548,918,971 | 0.3% | 49.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 548,046,168 | 0.3% | 49.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 529,012,254 | 0.3% | 49.7% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 524,381,272 | 0.3% | 50.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 520,231,730 | 0.3% | 50.3% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 519,570,597 | 0.3% | 50.6% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 517,389,304 | 0.3% | 51.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 517,256,788 | 0.3% | 51.3% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 515,492,969 | 0.3% | 51.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 505,749,833 | 0.3% | 51.9% |
| CALL STORE_FAST | 478,487,596 | 0.3% | 52.2% |
| LOAD_ATTR_SLOT LOAD_FAST | 457,485,951 | 0.3% | 52.4% |
| LOAD_CONST CALL_BUILTIN_FAST | 445,158,142 | 0.3% | 52.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 441,792,674 | 0.3% | 53.0% |
| CALL_BUILTIN_O POP_TOP | 441,765,203 | 0.3% | 53.2% |
| BINARY_OP_ADD_INT STORE_FAST | 440,307,056 | 0.3% | 53.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 435,260,081 | 0.3% | 53.8% |
| NOP LOAD_FAST | 428,060,349 | 0.3% | 54.0% |
| CALL_BUILTIN_FAST STORE_FAST | 426,681,432 | 0.3% | 54.3% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_STR_INT | 421,115,820 | 0.3% | 54.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 418,182,759 | 0.3% | 54.8% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 411,378,033 | 0.2% | 55.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 401,632,585 | 0.2% | 55.3% |
| STORE_ATTR_SLOT LOAD_CONST | 401,594,773 | 0.2% | 55.5% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 398,531,546 | 0.2% | 55.7% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 397,564,907 | 0.2% | 56.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 389,953,909 | 0.2% | 56.2% |
| STORE_ATTR_SLOT RETURN_CONST | 385,910,388 | 0.2% | 56.4% |
| RESUME_CHECK NOP | 382,262,358 | 0.2% | 56.7% |
| POP_TOP RESUME_CHECK | 381,723,639 | 0.2% | 56.9% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 377,958,010 | 0.2% | 57.1% |
| STORE_ATTR_SLOT LOAD_FAST | 370,435,548 | 0.2% | 57.3% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 369,324,999 | 0.2% | 57.6% |
| POP_JUMP_IF_FALSE LOAD_CONST | 368,147,892 | 0.2% | 57.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 177,029,241 | 60.6% |
| LOAD_FAST_LOAD_FAST | 51,940,380 | 17.8% |
| LOAD_FAST | 33,493,607 | 11.5% |
| BINARY_OP_ADD_INT | 21,440,175 | 7.3% |
| LOAD_ATTR_SLOT | 6,400,800 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 70,177,150 | 24.0% |
| GET_ITER | 44,571,320 | 15.3% |
| CALL_PY_EXACT_ARGS | 33,230,787 | 11.4% |
| BUILD_TUPLE | 32,461,701 | 11.1% |
| LOAD_DEREF | 25,325,840 | 8.7% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 23,030,720 | 59.0% |
| LOAD_CONST | 15,675,054 | 40.1% |
| LOAD_FAST_LOAD_FAST | 344,480 | 0.9% |
| LOAD_ATTR_SLOT | 10,700 | 0.0% |
| LOAD_FAST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,967,254 | 71.6% |
| RETURN_CONST | 7,807,680 | 20.0% |
| LOAD_FAST_LOAD_FAST | 3,225,960 | 8.3% |
| ENTER_EXECUTOR | 46,200 | 0.1% |
| JUMP_BACKWARD | 8,880 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,710,258,453 | 84.3% |
| POP_TOP | 148,499,063 | 7.3% |
| COPY_FREE_VARS | 136,423,984 | 6.7% |
| RETURN_GENERATOR | 30,716,643 | 1.5% |
| MAKE_CELL | 1,969,528 | 0.1% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,996,655 | 99.7% |
| LOAD_ATTR_WITH_HINT | 8,603 | 0.3% |
| CALL | 400 | 0.0% |
| LOAD_FAST | 160 | 0.0% |
| CALL_KW | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 3,005,938 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,257,214 | 60.3% |
| RETURN_VALUE | 3,331,578 | 32.1% |
| LOAD_GLOBAL_MODULE | 282,055 | 2.7% |
| LOAD_FAST | 193,540 | 1.9% |
| LOAD_ATTR_WITH_HINT | 176,680 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 9,467,180 | 91.2% |
| STORE_FAST | 906,627 | 8.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 0.0% |
| UNPACK_SEQUENCE | 160 | 0.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,488,640 | 43.0% |
| ENTER_EXECUTOR | 1,324,060 | 16.3% |
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
| LOAD_FAST | 186,993,952 | 26.7% |
| LOAD_CONST | 173,156,141 | 24.8% |
| COPY | 116,013,367 | 16.6% |
| LOAD_FAST_LOAD_FAST | 103,020,283 | 14.7% |
| BINARY_OP_ADD_INT | 43,215,640 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 234,862,416 | 33.6% |
| STORE_FAST | 97,325,483 | 13.9% |
| LOAD_FAST_LOAD_FAST | 65,591,329 | 9.4% |
| BINARY_SUBSCR_DICT | 49,452,000 | 7.1% |
| RETURN_VALUE | 47,675,139 | 6.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 21,237,809 | 92.3% |
| LOAD_GLOBAL_MODULE | 999,028 | 4.3% |
| BUILD_TUPLE | 637,627 | 2.8% |
| LOAD_ATTR_MODULE | 128,982 | 0.6% |
| LOAD_GLOBAL | 4,284 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,009,424 | 100.0% |
| EXTENDED_ARG | 320 | 0.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 97,349,300 | 54.9% |
| BUILD_SLICE | 71,237,531 | 40.1% |
| LOAD_CONST | 7,355,780 | 4.1% |
| LOAD_FAST | 1,362,158 | 0.8% |
| LOAD_ATTR_SLOT | 88,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,443,791 | 80.9% |
| LOAD_CONST | 24,226,929 | 13.7% |
| JUMP_FORWARD | 7,041,280 | 4.0% |
| ENTER_EXECUTOR | 1,111,360 | 0.6% |
| RETURN_CONST | 721,403 | 0.4% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 141,379,895 | 47.4% |
| RETURN_VALUE | 108,959,409 | 36.5% |
| RETURN_CONST | 47,989,076 | 16.1% |
| SEND_GEN | 15,180 | 0.0% |
| JUMP_BACKWARD | 241 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 129,802,557 | 43.5% |
| POP_TOP | 78,412,428 | 26.3% |
| BINARY_OP_ADD_INT | 38,845,400 | 13.0% |
| LOAD_GLOBAL_MODULE | 38,845,400 | 13.0% |
| LOAD_FAST | 8,588,044 | 2.9% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 92,200,167 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 92,200,167 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 292,289,016 | 36.0% |
| RETURN_VALUE | 76,028,563 | 9.4% |
| LOAD_ATTR_INSTANCE_VALUE | 72,188,626 | 8.9% |
| CALL_BUILTIN_CLASS | 69,555,282 | 8.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 59,570,216 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 251,559,298 | 31.0% |
| FOR_ITER_TUPLE | 168,983,257 | 20.8% |
| CALL_PY_EXACT_ARGS | 119,657,386 | 14.8% |
| FOR_ITER | 95,750,489 | 11.8% |
| FOR_ITER_GEN | 75,708,868 | 9.3% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 703,472,103 | 34.7% |
| RETURN_VALUE | 656,007,730 | 32.4% |
| YIELD_VALUE | 634,596,897 | 31.3% |
| RETURN_GENERATOR | 30,729,447 | 1.5% |
| INSTRUMENTED_RETURN_VALUE | 320 | 0.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 111,147,623 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 98,595,762 | 88.7% |
| LOAD_FAST | 6,728,091 | 6.1% |
| LOAD_GLOBAL_MODULE | 3,345,600 | 3.0% |
| LOAD_GLOBAL_BUILTIN | 842,406 | 0.8% |
| STORE_FAST | 815,859 | 0.7% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 382,262,358 | 39.3% |
| STORE_FAST | 203,803,217 | 21.0% |
| POP_JUMP_IF_FALSE | 109,529,969 | 11.3% |
| STORE_ATTR_INSTANCE_VALUE | 72,413,237 | 7.5% |
| NOP | 65,366,689 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 428,060,349 | 44.1% |
| LOAD_FAST_LOAD_FAST | 350,543,885 | 36.1% |
| NOP | 65,366,689 | 6.7% |
| LOAD_GLOBAL_BUILTIN | 39,633,247 | 4.1% |
| LOAD_CONST | 31,015,480 | 3.2% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 13,578,759 | 57.5% |
| STORE_SUBSCR_DICT | 4,110,200 | 17.4% |
| SWAP | 3,046,880 | 12.9% |
| COPY | 1,718,807 | 7.3% |
| STORE_FAST | 881,704 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 12,695,641 | 53.7% |
| RETURN_VALUE | 2,967,280 | 12.6% |
| JUMP_FORWARD | 2,296,760 | 9.7% |
| POP_TOP | 1,846,935 | 7.8% |
| RERAISE | 1,718,807 | 7.3% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 860,042,470 | 23.9% |
| RESUME_CHECK | 728,168,593 | 20.3% |
| CALL_BUILTIN_O | 441,765,203 | 12.3% |
| CALL_METHOD_DESCRIPTOR_O | 274,705,694 | 7.6% |
| POP_JUMP_IF_FALSE | 203,141,091 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,368,228,276 | 38.1% |
| ENTER_EXECUTOR | 854,081,204 | 23.8% |
| RESUME_CHECK | 381,723,639 | 10.6% |
| RETURN_CONST | 304,577,434 | 8.5% |
| LOAD_CONST | 149,738,083 | 4.2% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 7,127,030 | 30.2% |
| LOAD_ATTR | 4,419,801 | 18.7% |
| RAISE_VARARGS | 3,179,589 | 13.5% |
| CALL_BUILTIN_FAST | 2,382,291 | 10.1% |
| RERAISE | 1,490,348 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 21,352,681 | 90.3% |
| LOAD_GLOBAL_MODULE | 1,568,866 | 6.6% |
| LOAD_FAST | 517,720 | 2.2% |
| WITH_EXCEPT_START | 184,307 | 0.8% |
| LOAD_GLOBAL | 9,605 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 731,973,574 | 52.4% |
| LOAD_ATTR_MODULE | 435,260,081 | 31.2% |
| LOAD_DEREF | 69,361,241 | 5.0% |
| LOAD_ATTR | 66,238,433 | 4.7% |
| LOAD_FAST_LOAD_FAST | 42,781,643 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 662,649,919 | 47.5% |
| LOAD_FAST_LOAD_FAST | 398,531,546 | 28.5% |
| LOAD_CONST | 164,300,891 | 11.8% |
| CALL | 102,831,419 | 7.4% |
| LOAD_GLOBAL_MODULE | 33,063,928 | 2.4% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 194,113,872 | 50.8% |
| COPY_FREE_VARS | 107,109,942 | 28.1% |
| ENTER_EXECUTOR | 36,475,304 | 9.6% |
| CACHE | 30,716,643 | 8.0% |
| CALL_PY_WITH_DEFAULTS | 8,945,298 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 130,265,660 | 34.1% |
| GET_ITER | 50,228,881 | 13.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 43,093,244 | 11.3% |
| CALL | 38,859,025 | 10.2% |
| INTERPRETER_EXIT | 30,729,447 | 8.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,284,440,249 | 28.7% |
| RETURN_VALUE | 717,306,649 | 16.0% |
| BUILD_TUPLE | 563,055,018 | 12.6% |
| LOAD_ATTR_INSTANCE_VALUE | 275,646,244 | 6.2% |
| BINARY_SUBSCR_DICT | 139,712,170 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 976,225,295 | 21.8% |
| RETURN_VALUE | 717,306,649 | 16.0% |
| INTERPRETER_EXIT | 656,007,730 | 14.6% |
| TO_BOOL_BOOL | 363,821,026 | 8.1% |
| UNPACK_SEQUENCE_TUPLE | 345,372,856 | 7.7% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 116,023,647 | 33.4% |
| LOAD_FAST | 89,643,385 | 25.8% |
| LOAD_CONST | 44,699,654 | 12.9% |
| BINARY_OP_ADD_INT | 38,502,360 | 11.1% |
| LOAD_FAST_LOAD_FAST | 37,525,060 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 115,319,440 | 33.2% |
| ENTER_EXECUTOR | 77,429,100 | 22.3% |
| RETURN_CONST | 48,436,589 | 14.0% |
| LOAD_GLOBAL_BUILTIN | 36,004,000 | 10.4% |
| LOAD_FAST | 26,334,712 | 7.6% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 238,074,888 | 68.2% |
| LOAD_ATTR_INSTANCE_VALUE | 77,843,940 | 22.3% |
| CALL_BUILTIN_FAST | 10,290,920 | 2.9% |
| LOAD_ATTR | 9,988,144 | 2.9% |
| LOAD_ATTR_SLOT | 4,277,124 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 198,719,830 | 56.9% |
| POP_JUMP_IF_FALSE | 148,782,517 | 42.6% |
| TO_BOOL | 479,658 | 0.1% |
| UNARY_NOT | 380,075 | 0.1% |
| TO_BOOL_NONE | 197,543 | 0.1% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 14,333,738 | 92.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 601,754 | 3.9% |
| LOAD_ATTR_MODULE | 407,339 | 2.6% |
| LOAD_FAST | 175,180 | 1.1% |
| LOAD_FAST_LOAD_FAST | 9,420 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 15,527,771 | 100.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_FAST | 40 | 0.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 63,177,897 | 87.0% |
| TO_BOOL_LIST | 4,191,745 | 5.8% |
| COMPARE_OP | 3,442,672 | 4.7% |
| TO_BOOL_STR | 800,240 | 1.1% |
| TO_BOOL_INT | 574,409 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 29,280,523 | 40.3% |
| RETURN_VALUE | 25,650,871 | 35.3% |
| LOAD_CONST | 13,722,974 | 18.9% |
| STORE_FAST | 1,501,370 | 2.1% |
| CALL_PY_EXACT_ARGS | 1,004,820 | 1.4% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 194,682,867 | 21.2% |
| LOAD_CONST | 163,356,625 | 17.8% |
| CALL_METHOD_DESCRIPTOR_O | 96,003,000 | 10.4% |
| LOAD_FAST_LOAD_FAST | 67,925,906 | 7.4% |
| BINARY_OP_ADD_INT | 56,113,485 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 178,094,699 | 19.4% |
| LOAD_FAST | 165,164,975 | 18.0% |
| LOAD_FAST_LOAD_FAST | 133,782,450 | 14.6% |
| RETURN_VALUE | 97,755,334 | 10.6% |
| LOAD_CONST | 68,745,805 | 7.5% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 146,030,203 | 32.0% |
| ENTER_EXECUTOR | 86,589,849 | 19.0% |
| LOAD_FAST | 46,653,208 | 10.2% |
| SWAP | 41,842,780 | 9.2% |
| RESUME_CHECK | 23,623,494 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 183,523,587 | 40.3% |
| LOAD_FAST | 162,925,095 | 35.8% |
| SWAP | 41,882,180 | 9.2% |
| CALL | 12,849,020 | 2.8% |
| RETURN_VALUE | 11,905,044 | 2.6% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,194,344 | 27.4% |
| STORE_FAST | 14,711,484 | 12.1% |
| SWAP | 12,811,624 | 10.6% |
| RESUME_CHECK | 10,442,040 | 8.6% |
| BUILD_TUPLE | 8,801,647 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,473,855 | 39.2% |
| STORE_FAST | 34,621,631 | 28.6% |
| SWAP | 12,811,624 | 10.6% |
| CALL_FUNCTION_EX | 9,564,732 | 7.9% |
| CALL_BUILTIN_FAST | 5,767,140 | 4.8% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,029,840 | 78.0% |
| LOAD_CONST | 190,280 | 7.3% |
| LOAD_GLOBAL_MODULE | 189,814 | 7.3% |
| LOAD_FAST | 102,866 | 4.0% |
| LOAD_ATTR | 89,040 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,029,840 | 78.0% |
| CONTAINS_OP | 190,774 | 7.3% |
| LOAD_CONST | 99,220 | 3.8% |
| BINARY_OP | 91,520 | 3.5% |
| STORE_FAST | 64,580 | 2.5% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 94,738,394 | 98.8% |
| LOAD_FAST | 1,105,331 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 71,980 | 0.1% |
| BINARY_OP_ADD_INT | 2,120 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 71,237,531 | 74.3% |
| BINARY_SUBSCR | 24,676,514 | 25.7% |
| BINARY_SUBSCR_GETITEM | 3,840 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 285,421,016 | 30.3% |
| LOAD_CONST | 223,365,556 | 23.7% |
| LOAD_FAST_LOAD_FAST | 188,191,231 | 20.0% |
| CALL | 51,709,110 | 5.5% |
| LOAD_GLOBAL_BUILTIN | 38,488,232 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 563,055,018 | 59.8% |
| LOAD_CONST | 99,196,234 | 10.5% |
| CALL_ISINSTANCE | 44,756,369 | 4.8% |
| YIELD_VALUE | 40,563,452 | 4.3% |
| LIST_APPEND | 33,733,768 | 3.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 329,447,948 | 27.2% |
| LOAD_FAST_LOAD_FAST | 153,703,250 | 12.7% |
| PUSH_NULL | 102,831,419 | 8.5% |
| BINARY_SUBSCR_TUPLE_INT | 96,160,227 | 8.0% |
| ENTER_EXECUTOR | 92,501,963 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 478,487,596 | 39.6% |
| RESUME_CHECK | 206,461,520 | 17.1% |
| POP_TOP | 91,298,736 | 7.6% |
| RETURN_VALUE | 56,955,554 | 4.7% |
| LOAD_GLOBAL_MODULE | 56,452,095 | 4.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 106,141,132 | 55.7% |
| DICT_MERGE | 38,106,410 | 20.0% |
| LOAD_FAST | 24,149,490 | 12.7% |
| BUILD_MAP | 9,564,732 | 5.0% |
| ENTER_EXECUTOR | 7,117,463 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 110,386,755 | 57.9% |
| STORE_FAST | 28,519,673 | 15.0% |
| RESUME_CHECK | 21,411,852 | 11.2% |
| RETURN_VALUE | 9,536,276 | 5.0% |
| LOAD_FAST_LOAD_FAST | 6,654,200 | 3.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 124,073,474 | 50.8% |
| LOAD_FAST | 117,515,680 | 48.1% |
| LOAD_ATTR_INSTANCE_VALUE | 2,757,500 | 1.1% |
| RERAISE | 56,521 | 0.0% |
| LIST_APPEND | 15,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 120,273,200 | 49.2% |
| CALL_FUNCTION_EX | 106,141,132 | 43.4% |
| LOAD_CONST | 9,378,812 | 3.8% |
| BUILD_MAP | 8,535,970 | 3.5% |
| RERAISE | 56,843 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 245,635,240 | 93.1% |
| ENTER_EXECUTOR | 18,180,118 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 124,337,914 | 47.1% |
| STORE_FAST | 65,167,543 | 24.7% |
| RETURN_VALUE | 27,106,145 | 10.3% |
| UNPACK_SEQUENCE_LIST | 14,181,920 | 5.4% |
| POP_TOP | 7,520,874 | 2.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 50,971,936 | 30.4% |
| LOAD_FAST_LOAD_FAST | 27,592,728 | 16.4% |
| LOAD_FAST | 22,996,543 | 13.7% |
| LOAD_ATTR_SLOT | 18,387,863 | 11.0% |
| LOAD_GLOBAL_MODULE | 13,556,185 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 106,885,775 | 63.7% |
| COPY | 17,307,603 | 10.3% |
| POP_JUMP_IF_TRUE | 16,479,653 | 9.8% |
| RETURN_VALUE | 9,642,285 | 5.7% |
| BINARY_OP | 6,162,440 | 3.7% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 316,156,152 | 28.1% |
| LOAD_FAST | 315,721,360 | 28.1% |
| LOAD_GLOBAL_MODULE | 285,480,985 | 25.4% |
| BINARY_SUBSCR_DICT | 78,260,500 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 54,760,842 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 977,253,567 | 86.9% |
| POP_JUMP_IF_TRUE | 77,374,355 | 6.9% |
| RETURN_VALUE | 34,368,147 | 3.1% |
| COPY | 28,364,441 | 2.5% |
| EXTENDED_ARG | 4,067,200 | 0.4% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 287,901,199 | 24.2% |
| COPY | 277,580,539 | 23.3% |
| SWAP | 116,919,640 | 9.8% |
| LOAD_CONST | 109,042,960 | 9.1% |
| LOAD_FAST_LOAD_FAST | 101,442,580 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 283,007,846 | 23.7% |
| COPY | 277,580,539 | 23.3% |
| BINARY_SUBSCR_LIST_INT | 159,144,720 | 13.4% |
| BINARY_SUBSCR | 116,013,367 | 9.7% |
| COMPARE_OP_INT | 112,789,502 | 9.5% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 193,063,199 | 49.0% |
| CACHE | 136,423,984 | 34.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 37,063,741 | 9.4% |
| CALL | 7,491,439 | 1.9% |
| CALL_PY_WITH_DEFAULTS | 6,927,448 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 286,645,376 | 72.8% |
| RETURN_GENERATOR | 107,109,942 | 27.2% |
| MAKE_CELL | 105,723 | 0.0% |
| RESUME | 17,241 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,942,026 | 96.9% |
| RETURN_VALUE | 502,240 | 1.3% |
| LOAD_ATTR_INSTANCE_VALUE | 291,499 | 0.8% |
| LOAD_DEREF | 270,499 | 0.7% |
| LOAD_GLOBAL_MODULE | 40,514 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 38,106,410 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 854,081,204 | 34.7% |
| POP_JUMP_IF_TRUE | 524,381,272 | 21.3% |
| POP_JUMP_IF_FALSE | 268,590,792 | 10.9% |
| STORE_FAST | 157,635,990 | 6.4% |
| CALL_LIST_APPEND | 130,581,741 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 366,550,935 | 14.9% |
| FOR_ITER_LIST | 320,792,738 | 13.0% |
| POP_JUMP_IF_FALSE | 312,914,853 | 12.7% |
| FOR_ITER_TUPLE | 166,431,593 | 6.8% |
| SEND | 125,514,720 | 5.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 355,789,859 | 69.7% |
| GET_ITER | 95,750,489 | 18.7% |
| EXTENDED_ARG | 27,379,420 | 5.4% |
| SWAP | 16,598,389 | 3.2% |
| LOAD_FAST | 11,863,953 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 270,503,027 | 53.0% |
| STORE_FAST | 123,502,552 | 24.2% |
| LOAD_FAST | 41,470,580 | 8.1% |
| RETURN_CONST | 25,715,054 | 5.0% |
| SWAP | 15,843,977 | 3.1% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 130,265,660 | 85.6% |
| LOAD_FAST | 8,732,711 | 5.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,638,984 | 2.4% |
| RETURN_VALUE | 3,443,246 | 2.3% |
| BEFORE_ASYNC_WITH | 3,005,938 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 152,094,564 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 9,837,206 | 84.5% |
| STORE_FAST | 1,584,183 | 13.6% |
| STORE_DEREF | 185,694 | 1.6% |
| STORE_NAME | 35,660 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,491,144 | 81.5% |
| STORE_DEREF | 2,092,459 | 18.0% |
| STORE_NAME | 58,940 | 0.5% |
| EXTENDED_ARG | 2,540 | 0.0% |
| PUSH_EXC_INFO | 200 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,404,635 | 100.0% |
| ENTER_EXECUTOR | 100 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 9,837,206 | 94.5% |
| STORE_FAST | 554,149 | 5.3% |
| STORE_NAME | 11,320 | 0.1% |
| CALL_INTRINSIC_1 | 1,580 | 0.0% |
| STORE_DEREF | 320 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 303,315,722 | 35.5% |
| LOAD_GLOBAL_MODULE | 257,723,205 | 30.2% |
| LOAD_FAST_LOAD_FAST | 163,363,561 | 19.1% |
| LOAD_GLOBAL_BUILTIN | 61,987,062 | 7.3% |
| LOAD_FAST | 28,918,859 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 704,786,509 | 82.6% |
| POP_JUMP_IF_TRUE | 84,066,785 | 9.9% |
| EXTENDED_ARG | 24,207,600 | 2.8% |
| STORE_FAST | 16,210,762 | 1.9% |
| YIELD_VALUE | 13,390,222 | 1.6% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 136,943,998 | 27.8% |
| STORE_FAST | 84,088,046 | 17.0% |
| POP_JUMP_IF_TRUE | 57,247,835 | 11.6% |
| STORE_SUBSCR_LIST_INT | 47,752,211 | 9.7% |
| LIST_APPEND | 27,864,283 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 355,789,859 | 72.1% |
| FOR_ITER_GEN | 91,325,259 | 18.5% |
| EXTENDED_ARG | 42,675,600 | 8.6% |
| RETURN_CONST | 2,757,120 | 0.6% |
| FOR_ITER_LIST | 404,720 | 0.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 310,562,595 | 100.0% |
| RESUME | 5,187 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 294,690,099 | 94.9% |
| SEND | 15,877,683 | 5.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 259,964,287 | 47.6% |
| POP_JUMP_IF_FALSE | 117,382,138 | 21.5% |
| POP_TOP | 55,495,085 | 10.2% |
| LOAD_ATTR_SLOT | 21,640,960 | 4.0% |
| POP_JUMP_IF_NONE | 14,018,240 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,403,204 | 41.3% |
| LOAD_FAST_LOAD_FAST | 104,627,655 | 19.2% |
| LOAD_CONST | 50,570,954 | 9.3% |
| LOAD_GLOBAL_BUILTIN | 39,016,149 | 7.1% |
| LOAD_GLOBAL_MODULE | 35,255,847 | 6.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 33,733,768 | 31.6% |
| RETURN_VALUE | 20,636,239 | 19.3% |
| RETURN_GENERATOR | 17,923,920 | 16.8% |
| LOAD_FAST | 13,366,899 | 12.5% |
| CALL | 7,051,180 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 78,839,671 | 73.8% |
| JUMP_BACKWARD | 27,864,283 | 26.1% |
| LOAD_FAST | 128,000 | 0.1% |
| CALL_INTRINSIC_1 | 15,520 | 0.0% |
| LOAD_NAME | 4,820 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 98,283,851 | 78.5% |
| LOAD_FAST | 25,984,231 | 20.7% |
| LOAD_CONST | 499,680 | 0.4% |
| RETURN_VALUE | 319,371 | 0.3% |
| LOAD_DEREF | 104,611 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 124,073,474 | 99.1% |
| STORE_FAST | 595,999 | 0.5% |
| LOAD_FAST | 334,831 | 0.3% |
| UNPACK_SEQUENCE_LIST | 230,040 | 0.2% |
| BUILD_TUPLE | 7,400 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 921,788,658 | 60.5% |
| LOAD_GLOBAL_BUILTIN | 297,852,157 | 19.6% |
| LOAD_GLOBAL_MODULE | 150,171,425 | 9.9% |
| LOAD_ATTR_SLOT | 70,456,186 | 4.6% |
| LOAD_FAST_LOAD_FAST | 29,739,100 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 303,315,722 | 19.9% |
| STORE_FAST | 262,548,115 | 17.2% |
| LOAD_FAST | 262,405,825 | 17.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 107,001,272 | 7.0% |
| CALL | 67,105,476 | 4.4% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,998,927,782 | 34.5% |
| LOAD_CONST | 960,787,209 | 11.0% |
| STORE_ATTR_SLOT | 401,594,773 | 4.6% |
| LOAD_FAST_LOAD_FAST | 397,564,907 | 4.6% |
| POP_JUMP_IF_FALSE | 368,147,892 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,404,251,676 | 16.1% |
| LOAD_CONST | 960,787,209 | 11.0% |
| BINARY_OP_ADD_INT | 883,903,011 | 10.2% |
| COMPARE_OP_INT | 710,284,963 | 8.2% |
| STORE_FAST | 603,078,158 | 6.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160,593,427 | 19.8% |
| STORE_FAST | 110,106,458 | 13.5% |
| POP_JUMP_IF_FALSE | 67,606,530 | 8.3% |
| STORE_FAST_STORE_FAST | 46,428,968 | 5.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 41,727,760 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 365,837,286 | 45.0% |
| LOAD_CONST | 97,095,213 | 11.9% |
| PUSH_NULL | 69,361,241 | 8.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 47,617,082 | 5.9% |
| LOAD_DEREF | 32,496,016 | 4.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,579,450,834 | 14.3% |
| POP_JUMP_IF_FALSE | 4,382,926,047 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 3,448,318,843 | 10.8% |
| RESUME_CHECK | 2,972,031,668 | 9.3% |
| LOAD_CONST | 1,404,251,676 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,176,426,445 | 13.1% |
| LOAD_CONST | 2,998,927,782 | 9.4% |
| LOAD_ATTR_SLOT | 1,874,103,337 | 5.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,703,604,841 | 5.3% |
| LOAD_GLOBAL_BUILTIN | 1,406,201,552 | 4.4% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 56,684,244 | 70.1% |
| LOAD_FAST_AND_CLEAR | 24,127,691 | 29.9% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 56,673,284 | 70.1% |
| LOAD_FAST_AND_CLEAR | 24,127,691 | 29.9% |
| MAKE_CELL | 11,040 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,911,245 | 42.0% |
| POP_TOP | 2,769,303 | 23.7% |
| LOAD_ATTR_METHOD_NO_DICT | 1,626,847 | 13.9% |
| POP_JUMP_IF_NONE | 977,560 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 565,540 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,771,605 | 40.8% |
| POP_JUMP_IF_NOT_NONE | 2,041,280 | 17.4% |
| CALL_LIST_APPEND | 1,564,660 | 13.4% |
| LOAD_FAST | 1,210,122 | 10.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 575,920 | 4.9% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 878,350,906 | 12.0% |
| POP_JUMP_IF_FALSE | 627,221,047 | 8.6% |
| LOAD_GLOBAL_MODULE | 584,129,390 | 8.0% |
| LOAD_FAST_LOAD_FAST | 548,918,971 | 7.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 529,012,254 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 885,170,759 | 12.1% |
| CALL_PY_EXACT_ARGS | 753,046,060 | 10.3% |
| LOAD_FAST | 687,165,494 | 9.4% |
| LOAD_FAST_LOAD_FAST | 548,918,971 | 7.5% |
| BINARY_SUBSCR_STR_INT | 421,115,820 | 5.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 9,716,800 | 89.6% |
| STORE_FAST | 158,266 | 1.5% |
| LOAD_FAST | 150,714 | 1.4% |
| POP_JUMP_IF_FALSE | 142,220 | 1.3% |
| POP_TOP | 85,031 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,910,657 | 91.4% |
| LOAD_GLOBAL_MODULE | 356,628 | 3.3% |
| LOAD_GLOBAL_BUILTIN | 187,392 | 1.7% |
| LOAD_ATTR | 114,799 | 1.1% |
| CALL | 66,002 | 0.6% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,967 | 97.5% |
| LOAD_DEREF | 300 | 1.6% |
| EXTENDED_ARG | 120 | 0.7% |
| LOAD_GLOBAL | 20 | 0.1% |
| LOAD_GLOBAL_MODULE | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 8,180 | 44.4% |
| CALL | 3,687 | 20.0% |
| LOAD_FAST | 2,760 | 15.0% |
| LOAD_FAST_LOAD_FAST | 1,620 | 8.8% |
| LOAD_SUPER_ATTR_ATTR | 960 | 5.2% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 67,890,840 | 56.2% |
| CALL_PY_EXACT_ARGS | 34,401,674 | 28.5% |
| CALL_FUNCTION_EX | 6,318,405 | 5.2% |
| CALL_KW | 5,442,880 | 4.5% |
| CALL_PY_WITH_DEFAULTS | 2,118,472 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 67,890,840 | 56.2% |
| RESUME_CHECK | 52,109,761 | 43.1% |
| RETURN_GENERATOR | 858,525 | 0.7% |
| RESUME | 11,440 | 0.0% |
| SWAP | 10,960 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,219,154,885 | 39.0% |
| COMPARE_OP_INT | 1,324,483,541 | 16.0% |
| CONTAINS_OP | 977,253,567 | 11.8% |
| IS_OP | 704,786,509 | 8.5% |
| TO_BOOL_NONE | 517,389,304 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,382,926,047 | 53.1% |
| LOAD_GLOBAL_BUILTIN | 1,184,101,594 | 14.3% |
| LOAD_FAST_LOAD_FAST | 627,221,047 | 7.6% |
| RETURN_CONST | 441,792,674 | 5.4% |
| LOAD_GLOBAL_MODULE | 389,953,909 | 4.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 345,676,499 | 69.3% |
| EXTENDED_ARG | 49,201,354 | 9.9% |
| LOAD_ATTR_INSTANCE_VALUE | 33,473,405 | 6.7% |
| LOAD_ATTR_SLOT | 31,557,060 | 6.3% |
| LOAD_DEREF | 19,462,131 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 305,282,804 | 61.2% |
| LOAD_DEREF | 36,713,559 | 7.4% |
| ENTER_EXECUTOR | 34,683,200 | 7.0% |
| LOAD_FAST_LOAD_FAST | 23,504,722 | 4.7% |
| JUMP_BACKWARD | 21,450,704 | 4.3% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 578,372,797 | 82.8% |
| LOAD_ATTR_INSTANCE_VALUE | 68,789,371 | 9.8% |
| LOAD_ATTR | 18,957,321 | 2.7% |
| EXTENDED_ARG | 9,717,120 | 1.4% |
| LOAD_ATTR_SLOT | 5,415,680 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 313,992,410 | 44.9% |
| LOAD_FAST_LOAD_FAST | 138,395,423 | 19.8% |
| LOAD_GLOBAL_MODULE | 80,752,490 | 11.6% |
| LOAD_GLOBAL_BUILTIN | 68,700,987 | 9.8% |
| RETURN_CONST | 27,527,725 | 3.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,046,437,708 | 51.5% |
| TO_BOOL | 198,719,830 | 9.8% |
| COMPARE_OP_INT | 142,829,484 | 7.0% |
| TO_BOOL_ALWAYS_TRUE | 109,997,943 | 5.4% |
| TO_BOOL_NONE | 98,272,386 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 888,848,060 | 43.8% |
| ENTER_EXECUTOR | 524,381,272 | 25.8% |
| LOAD_GLOBAL_BUILTIN | 146,594,967 | 7.2% |
| LOAD_CONST | 96,784,873 | 4.8% |
| POP_TOP | 86,992,493 | 4.3% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,099,704 | 52.7% |
| LOAD_ATTR_MODULE | 778,140 | 19.5% |
| LOAD_GLOBAL_BUILTIN | 724,160 | 18.2% |
| LOAD_FAST | 201,601 | 5.1% |
| RETURN_VALUE | 73,920 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 3,179,589 | 79.9% |
| COPY | 596,580 | 15.0% |
| LOAD_CONST | 201,861 | 5.1% |
| CALL_INTRINSIC_1 | 2 | 0.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 1,718,807 | 59.5% |
| POP_TOP | 516,120 | 17.9% |
| POP_JUMP_IF_FALSE | 209,360 | 7.3% |
| DELETE_FAST | 201,920 | 7.0% |
| POP_JUMP_IF_TRUE | 183,267 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,490,348 | 56.1% |
| COPY | 1,110,707 | 41.8% |
| CALL_INTRINSIC_1 | 56,521 | 2.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 441,792,674 | 21.3% |
| STORE_ATTR_SLOT | 385,910,388 | 18.6% |
| POP_TOP | 304,577,434 | 14.7% |
| STORE_ATTR_INSTANCE_VALUE | 229,196,800 | 11.0% |
| RESUME_CHECK | 176,805,782 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 860,042,470 | 41.4% |
| INTERPRETER_EXIT | 703,472,103 | 33.9% |
| EXIT_INIT_CHECK | 92,200,167 | 4.4% |
| TO_BOOL_BOOL | 80,003,505 | 3.9% |
| END_FOR | 76,107,046 | 3.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 125,514,720 | 75.9% |
| LOAD_CONST | 23,878,443 | 14.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 15,877,683 | 9.6% |
| SEND | 51,981 | 0.0% |
| SEND_GEN | 580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 141,379,895 | 85.5% |
| YIELD_VALUE | 15,865,581 | 9.6% |
| END_ASYNC_FOR | 8,000,000 | 4.8% |
| SEND | 51,981 | 0.0% |
| RESUME_CHECK | 10,200 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 98,595,762 | 98.6% |
| SET_FUNCTION_ATTRIBUTE | 1,443,176 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,222,363 | 60.2% |
| LOAD_GLOBAL_BUILTIN | 25,348,160 | 25.3% |
| STORE_FAST | 7,983,007 | 8.0% |
| CALL_PY_EXACT_ARGS | 2,704,463 | 2.7% |
| SET_FUNCTION_ATTRIBUTE | 1,443,176 | 1.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,769,595 | 57.7% |
| LOAD_FAST_LOAD_FAST | 21,102,512 | 29.1% |
| CALL | 6,424,560 | 8.9% |
| SWAP | 1,529,662 | 2.1% |
| CALL_KW | 801,120 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,035,137 | 29.1% |
| LOAD_DEREF | 17,938,490 | 24.8% |
| RETURN_CONST | 12,102,284 | 16.7% |
| LOAD_FAST_LOAD_FAST | 6,616,558 | 9.1% |
| ENTER_EXECUTOR | 5,701,620 | 7.9% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 35,847,846 | 38.4% |
| STORE_FAST | 25,638,100 | 27.5% |
| LOAD_CONST | 9,112,621 | 9.8% |
| LOAD_FAST | 3,889,520 | 4.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,579,820 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,893,400 | 31.0% |
| LOAD_DEREF | 19,660,740 | 21.1% |
| LOAD_FAST_LOAD_FAST | 17,926,010 | 19.2% |
| LOAD_FAST | 10,892,069 | 11.7% |
| LOAD_CONST | 6,424,757 | 6.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 976,225,295 | 11.1% |
| STORE_FAST | 701,304,247 | 8.0% |
| LOAD_CONST | 603,078,158 | 6.9% |
| CALL | 478,487,596 | 5.4% |
| BINARY_OP_ADD_INT | 440,307,056 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,579,450,834 | 52.0% |
| LOAD_FAST_LOAD_FAST | 878,350,906 | 10.0% |
| STORE_FAST | 701,304,247 | 8.0% |
| LOAD_GLOBAL_BUILTIN | 687,237,535 | 7.8% |
| LOAD_GLOBAL_MODULE | 517,256,788 | 5.9% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 17,078,984 | 42.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,249,620 | 30.3% |
| FOR_ITER_TUPLE | 4,965,058 | 12.3% |
| FOR_ITER | 4,053,479 | 10.0% |
| FOR_ITER_RANGE | 1,049,900 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 12,390,447 | 30.6% |
| TO_BOOL_ALWAYS_TRUE | 4,836,020 | 12.0% |
| LOAD_ATTR_SLOT | 4,234,327 | 10.5% |
| LOAD_CONST | 3,505,804 | 8.7% |
| LOAD_FAST | 2,694,943 | 6.7% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,048,652,150 | 52.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 505,749,833 | 25.2% |
| UNPACK_SEQUENCE_TUPLE | 194,834,385 | 9.7% |
| UNPACK_SEQUENCE_LIST | 146,485,145 | 7.3% |
| LOAD_ATTR_SLOT | 61,211,336 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,048,652,150 | 52.3% |
| LOAD_FAST | 589,015,541 | 29.4% |
| LOAD_FAST_LOAD_FAST | 121,025,723 | 6.0% |
| STORE_FAST | 69,956,128 | 3.5% |
| LOAD_GLOBAL_MODULE | 63,180,329 | 3.2% |


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

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 283,981,399 | 26.4% |
| BINARY_OP_ADD_FLOAT | 142,677,966 | 13.2% |
| LOAD_FAST | 135,851,010 | 12.6% |
| BINARY_OP_ADD_INT | 107,801,194 | 10.0% |
| BINARY_OP_SUBTRACT_FLOAT | 74,443,758 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 283,981,399 | 26.4% |
| STORE_SUBSCR_LIST_INT | 165,545,580 | 15.4% |
| COPY | 116,919,640 | 10.9% |
| STORE_SUBSCR | 116,023,647 | 10.8% |
| STORE_ATTR_INSTANCE_VALUE | 94,456,869 | 8.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 128,400 | 34.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 90,720 | 24.3% |
| LOAD_FAST | 35,105 | 9.4% |
| COPY | 26,720 | 7.2% |
| RETURN_VALUE | 25,815 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 216,054 | 57.9% |
| STORE_FAST | 109,881 | 29.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 26,696 | 7.1% |
| UNPACK_SEQUENCE_TUPLE | 13,772 | 3.7% |
| UNPACK_SEQUENCE | 2,853 | 0.8% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 366,550,935 | 34.8% |
| YIELD_VALUE | 294,709,672 | 28.0% |
| CALL_INTRINSIC_1 | 120,273,200 | 11.4% |
| LOAD_FAST | 64,445,950 | 6.1% |
| BINARY_OP_MULTIPLY_FLOAT | 41,716,800 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 634,596,897 | 60.2% |
| YIELD_VALUE | 294,709,672 | 28.0% |
| STORE_FAST | 86,368,594 | 8.2% |
| UNPACK_SEQUENCE_TUPLE | 33,453,160 | 3.2% |
| STORE_DEREF | 3,225,580 | 0.3% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 104,802 | 38.6% |
| CACHE | 77,735 | 28.7% |
| CALL_PY_EXACT_ARGS | 18,160 | 6.7% |
| COPY_FREE_VARS | 17,241 | 6.4% |
| POP_TOP | 15,770 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 111,085 | 41.0% |
| LOAD_GLOBAL | 64,548 | 23.8% |
| LOAD_CONST | 23,947 | 8.8% |
| LOAD_NAME | 19,700 | 7.3% |
| LOAD_FAST_LOAD_FAST | 10,515 | 3.9% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 245,989,264 | 62.3% |
| LOAD_FAST | 91,513,956 | 23.2% |
| RETURN_VALUE | 23,049,480 | 5.8% |
| BINARY_OP_MULTIPLY_INT | 11,249,600 | 2.9% |
| BINARY_OP | 8,323,250 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 142,677,966 | 36.2% |
| STORE_FAST | 90,846,044 | 23.0% |
| LOAD_FAST | 68,006,966 | 17.2% |
| RETURN_VALUE | 41,800,520 | 10.6% |
| LOAD_FAST_LOAD_FAST | 23,126,620 | 5.9% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 883,903,011 | 66.4% |
| LOAD_FAST | 185,549,032 | 13.9% |
| LOAD_FAST_LOAD_FAST | 118,268,859 | 8.9% |
| END_SEND | 38,845,400 | 2.9% |
| BINARY_OP_MULTIPLY_INT | 30,460,440 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 440,307,056 | 33.1% |
| LOAD_CONST | 156,484,883 | 11.7% |
| SWAP | 107,801,194 | 8.1% |
| RETURN_VALUE | 100,484,901 | 7.5% |
| LOAD_FAST_LOAD_FAST | 84,284,520 | 6.3% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 70,666,709 | 28.4% |
| LOAD_ATTR_INSTANCE_VALUE | 65,382,964 | 26.3% |
| LOAD_FAST_LOAD_FAST | 53,051,072 | 21.3% |
| BINARY_OP | 36,447,209 | 14.6% |
| LOAD_FAST | 12,025,941 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,404,670 | 23.9% |
| LOAD_CONST | 57,257,119 | 23.0% |
| LOAD_FAST_LOAD_FAST | 32,378,470 | 13.0% |
| BINARY_OP_ADD_INT | 30,460,440 | 12.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 30,018,280 | 12.1% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 96,946,560 | 40.6% |
| LOAD_FAST | 75,806,476 | 31.8% |
| LOAD_ATTR_INSTANCE_VALUE | 38,337,300 | 16.1% |
| BINARY_OP_SUBTRACT_FLOAT | 14,316,500 | 6.0% |
| BINARY_SUBSCR | 8,809,880 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 74,443,758 | 31.2% |
| LOAD_FAST_LOAD_FAST | 73,524,560 | 30.8% |
| LOAD_FAST | 37,921,820 | 15.9% |
| STORE_FAST | 31,962,224 | 13.4% |
| BINARY_OP_SUBTRACT_FLOAT | 14,316,500 | 6.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 348,709,034 | 73.3% |
| LOAD_FAST | 81,470,563 | 17.1% |
| LOAD_FAST_LOAD_FAST | 30,860,159 | 6.5% |
| LOAD_ATTR_INSTANCE_VALUE | 9,328,860 | 2.0% |
| CALL_LEN | 3,690,220 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 112,957,920 | 23.8% |
| STORE_FAST | 86,336,772 | 18.2% |
| SWAP | 60,199,108 | 12.7% |
| RETURN_VALUE | 53,628,992 | 11.3% |
| BINARY_OP | 43,575,522 | 9.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 259,395,356 | 37.4% |
| LOAD_CONST | 231,104,395 | 33.4% |
| LOAD_FAST_LOAD_FAST | 111,998,889 | 16.2% |
| BINARY_SUBSCR | 49,452,000 | 7.1% |
| CALL_BUILTIN_O | 13,367,000 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 218,852,219 | 31.6% |
| RETURN_VALUE | 139,712,170 | 20.2% |
| CONTAINS_OP | 78,260,500 | 11.3% |
| LOAD_FAST | 65,992,871 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 55,838,008 | 8.1% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 56,752,680 | 29.7% |
| LOAD_CONST | 54,708,914 | 28.7% |
| ENTER_EXECUTOR | 40,223,560 | 21.1% |
| BUILD_TUPLE | 30,733,740 | 16.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,473,280 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 189,507,528 | 99.3% |
| MAKE_CELL | 1,100,030 | 0.6% |
| COPY_FREE_VARS | 263,960 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 7,680 | 0.0% |
| CONTAINS_OP | 6,060 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 281,650,395 | 34.9% |
| COPY | 159,144,720 | 19.7% |
| LOAD_FAST_LOAD_FAST | 151,062,011 | 18.7% |
| LOAD_CONST | 112,495,724 | 14.0% |
| UNARY_NEGATIVE | 35,691,400 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 157,468,804 | 19.6% |
| LOAD_CONST | 153,301,063 | 19.1% |
| STORE_FAST | 125,095,387 | 15.6% |
| RETURN_VALUE | 115,546,992 | 14.4% |
| LOAD_ATTR_INSTANCE_VALUE | 48,825,360 | 6.1% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 216,030,949 | 96.9% |
| LOAD_FAST | 6,993,432 | 3.1% |
| LOAD_FAST_LOAD_FAST | 19,370 | 0.0% |
| BINARY_SUBSCR | 8,567 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 96,160,227 | 43.1% |
| LOAD_GLOBAL_MODULE | 40,559,740 | 18.2% |
| STORE_FAST | 12,697,913 | 5.7% |
| LOAD_CONST | 9,947,363 | 4.5% |
| LOAD_FAST | 9,151,267 | 4.1% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 21,530,660 | 22.8% |
| ENTER_EXECUTOR | 17,012,820 | 18.0% |
| BINARY_OP_MULTIPLY_FLOAT | 11,178,680 | 11.8% |
| RETURN_CONST | 10,486,240 | 11.1% |
| BINARY_OP_ADD_FLOAT | 6,838,655 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 90,278,024 | 95.5% |
| LOAD_FAST | 2,217,180 | 2.3% |
| COPY_FREE_VARS | 1,922,103 | 2.0% |
| CALL_ALLOC_AND_ENTER_INIT | 43,040 | 0.0% |
| STORE_FAST | 19,660 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 85,614,237 | 39.8% |
| LOAD_CONST | 47,207,046 | 22.0% |
| BINARY_OP_MULTIPLY_INT | 30,018,280 | 14.0% |
| PUSH_NULL | 13,060,289 | 6.1% |
| RETURN_VALUE | 6,943,000 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 170,348,312 | 79.3% |
| COPY_FREE_VARS | 37,063,741 | 17.3% |
| GET_AWAITABLE | 3,005,418 | 1.4% |
| POP_TOP | 2,780,108 | 1.3% |
| MAKE_CELL | 885,382 | 0.4% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,225,043 | 27.5% |
| CALL_LEN | 31,406,061 | 17.5% |
| LOAD_GLOBAL_BUILTIN | 17,872,642 | 10.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,231,566 | 6.8% |
| LOAD_CONST | 6,914,800 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 69,555,282 | 38.8% |
| STORE_FAST | 27,584,455 | 15.4% |
| BINARY_OP_MULTIPLY_FLOAT | 16,972,000 | 9.5% |
| LOAD_FAST | 16,555,433 | 9.2% |
| RETURN_VALUE | 6,549,588 | 3.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 579,419,620 | 46.5% |
| LOAD_CONST | 445,158,142 | 35.8% |
| LOAD_FAST_LOAD_FAST | 114,345,600 | 9.2% |
| CALL_BUILTIN_FAST | 29,037,480 | 2.3% |
| LOAD_FAST | 26,712,213 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 654,281,422 | 52.6% |
| STORE_FAST | 426,681,432 | 34.3% |
| POP_TOP | 43,221,171 | 3.5% |
| RETURN_VALUE | 37,504,942 | 3.0% |
| CALL_BUILTIN_FAST | 29,037,480 | 2.3% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 43,093,244 | 59.7% |
| LOAD_FAST | 12,792,435 | 17.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 7,731,312 | 10.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,986,400 | 4.1% |
| LOAD_FAST_LOAD_FAST | 2,224,008 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 41,727,760 | 57.9% |
| STORE_FAST | 12,577,717 | 17.4% |
| CALL_TUPLE_1 | 4,707,672 | 6.5% |
| POP_TOP | 4,403,331 | 6.1% |
| LOAD_FAST | 3,036,980 | 4.2% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 781,322,879 | 72.9% |
| RETURN_VALUE | 72,240,120 | 6.7% |
| LOAD_CONST | 63,579,090 | 5.9% |
| BUILD_STRING | 48,929,440 | 4.6% |
| BINARY_OP_ADD_UNICODE | 21,212,480 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 441,765,203 | 41.2% |
| STORE_FAST | 232,511,185 | 21.7% |
| LOAD_CONST | 229,039,350 | 21.4% |
| RETURN_VALUE | 52,575,897 | 4.9% |
| TO_BOOL_BOOL | 22,991,225 | 2.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 548,046,168 | 50.4% |
| LOAD_GLOBAL_BUILTIN | 377,958,010 | 34.7% |
| LOAD_FAST_LOAD_FAST | 64,326,531 | 5.9% |
| BUILD_TUPLE | 44,756,369 | 4.1% |
| LOAD_ATTR_MODULE | 33,722,112 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,070,632,626 | 98.4% |
| COPY | 8,611,512 | 0.8% |
| RETURN_VALUE | 3,380,647 | 0.3% |
| YIELD_VALUE | 3,140,408 | 0.3% |
| STORE_FAST | 1,987,408 | 0.2% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 271,396,330 | 69.1% |
| LOAD_ATTR_INSTANCE_VALUE | 59,299,338 | 15.1% |
| LOAD_DEREF | 27,299,311 | 7.0% |
| LOAD_ATTR_SLOT | 11,506,360 | 2.9% |
| BINARY_SUBSCR_DICT | 6,101,000 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 106,904,907 | 27.2% |
| LOAD_FAST | 58,080,433 | 14.8% |
| COMPARE_OP_INT | 53,802,048 | 13.7% |
| STORE_FAST | 51,976,992 | 13.2% |
| CALL_BUILTIN_CLASS | 31,406,061 | 8.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 244,109,117 | 71.7% |
| ENTER_EXECUTOR | 53,615,667 | 15.8% |
| BINARY_OP | 7,151,040 | 2.1% |
| BINARY_SUBSCR_TUPLE_INT | 6,856,180 | 2.0% |
| RETURN_VALUE | 6,273,920 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 130,581,741 | 38.4% |
| LOAD_FAST | 98,934,231 | 29.1% |
| EXTENDED_ARG | 41,813,048 | 12.3% |
| RETURN_CONST | 26,230,520 | 7.7% |
| LOAD_CONST | 15,073,521 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 220,266,855 | 49.9% |
| LOAD_FAST_LOAD_FAST | 72,017,201 | 16.3% |
| LOAD_ATTR_METHOD_NO_DICT | 54,273,165 | 12.3% |
| LOAD_CONST | 32,484,547 | 7.4% |
| LOAD_GLOBAL_MODULE | 24,326,600 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 343,315,971 | 77.8% |
| LOAD_FAST | 27,487,111 | 6.2% |
| RETURN_VALUE | 15,721,349 | 3.6% |
| TO_BOOL_BOOL | 11,818,040 | 2.7% |
| POP_TOP | 10,716,668 | 2.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 43,000,259 | 78.7% |
| LOAD_ATTR_METHOD_NO_DICT | 5,553,002 | 10.2% |
| LOAD_FAST | 3,868,664 | 7.1% |
| LOAD_FAST_LOAD_FAST | 1,370,788 | 2.5% |
| LOAD_ATTR | 386,974 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 39,492,795 | 72.3% |
| CALL_METHOD_DESCRIPTOR_O | 3,902,380 | 7.1% |
| RETURN_VALUE | 3,007,760 | 5.5% |
| BINARY_OP | 2,681,320 | 4.9% |
| POP_TOP | 1,518,043 | 2.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 157,807,676 | 52.6% |
| LOAD_ATTR | 107,001,272 | 35.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 22,731,854 | 7.6% |
| LOAD_ATTR_METHOD_LAZY_DICT | 9,921,357 | 3.3% |
| LOAD_FAST | 2,104,286 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 108,419,539 | 36.1% |
| GET_ITER | 59,570,216 | 19.8% |
| STORE_FAST | 47,103,315 | 15.7% |
| LOAD_GLOBAL_MODULE | 24,843,120 | 8.3% |
| LOAD_FAST | 16,767,496 | 5.6% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 338,957,391 | 81.0% |
| CALL | 44,075,778 | 10.5% |
| LOAD_GLOBAL_MODULE | 7,618,200 | 1.8% |
| LOAD_ATTR | 4,016,820 | 1.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 3,902,380 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 274,705,694 | 65.7% |
| BINARY_OP | 96,003,000 | 23.0% |
| RETURN_VALUE | 23,262,740 | 5.6% |
| LOAD_FAST | 8,345,780 | 2.0% |
| STORE_FAST | 4,461,565 | 1.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,133,312,324 | 32.8% |
| LOAD_FAST_LOAD_FAST | 753,046,060 | 21.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 623,139,748 | 18.0% |
| LOAD_GLOBAL_MODULE | 197,991,930 | 5.7% |
| LOAD_ATTR_METHOD_NO_DICT | 124,491,987 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,009,198,866 | 87.1% |
| RETURN_GENERATOR | 194,113,872 | 5.6% |
| COPY_FREE_VARS | 193,063,199 | 5.6% |
| MAKE_CELL | 34,401,674 | 1.0% |
| INSTRUMENTED_RESUME | 19,436,580 | 0.6% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 66,493,701 | 29.3% |
| LOAD_FAST | 48,513,058 | 21.4% |
| LOAD_FAST_LOAD_FAST | 41,699,128 | 18.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 16,330,171 | 7.2% |
| BINARY_OP_ADD_INT | 11,201,440 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 209,070,327 | 92.0% |
| RETURN_GENERATOR | 8,945,298 | 3.9% |
| COPY_FREE_VARS | 6,927,448 | 3.0% |
| MAKE_CELL | 2,118,472 | 0.9% |
| CALL_PY_EXACT_ARGS | 116,860 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 350,007,064 | 98.6% |
| LOAD_CONST | 4,947,302 | 1.4% |
| BINARY_SUBSCR_TUPLE_INT | 87,960 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 25,720 | 0.0% |
| LOAD_GLOBAL_MODULE | 5,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 275,457,345 | 77.6% |
| LOAD_GLOBAL_BUILTIN | 24,717,277 | 7.0% |
| LOAD_GLOBAL_MODULE | 18,369,360 | 5.2% |
| LOAD_FAST | 9,451,918 | 2.7% |
| CALL_PY_EXACT_ARGS | 6,892,214 | 1.9% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 710,284,963 | 45.3% |
| LOAD_FAST | 158,017,992 | 10.1% |
| LOAD_ATTR_INSTANCE_VALUE | 156,592,472 | 10.0% |
| LOAD_FAST_LOAD_FAST | 150,161,075 | 9.6% |
| COPY | 112,789,502 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,324,483,541 | 84.4% |
| POP_JUMP_IF_TRUE | 142,829,484 | 9.1% |
| RETURN_VALUE | 38,566,566 | 2.5% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 19,422,780 | 1.2% |
| LOAD_FAST | 14,461,540 | 0.9% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 303,235,057 | 87.5% |
| LOAD_FAST | 11,647,977 | 3.4% |
| LOAD_FAST_LOAD_FAST | 10,992,440 | 3.2% |
| LOAD_GLOBAL_MODULE | 6,984,495 | 2.0% |
| RETURN_VALUE | 5,383,260 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 295,988,103 | 85.4% |
| POP_JUMP_IF_TRUE | 33,311,535 | 9.6% |
| COPY | 8,163,035 | 2.4% |
| RETURN_VALUE | 5,872,132 | 1.7% |
| EXTENDED_ARG | 1,635,880 | 0.5% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 320,792,738 | 45.2% |
| GET_ITER | 251,559,298 | 35.5% |
| LOAD_FAST | 82,691,629 | 11.7% |
| SWAP | 30,113,426 | 4.2% |
| EXTENDED_ARG | 22,350,415 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 243,585,033 | 34.3% |
| RETURN_CONST | 138,610,171 | 19.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 90,348,161 | 12.7% |
| LOAD_FAST | 88,870,555 | 12.5% |
| LOAD_FAST_LOAD_FAST | 65,614,583 | 9.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 36,864,441 | 40.1% |
| LOAD_FAST | 28,737,640 | 31.2% |
| GET_ITER | 19,787,692 | 21.5% |
| SWAP | 5,615,600 | 6.1% |
| EXTENDED_ARG | 877,280 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 32,432,336 | 35.2% |
| STORE_FAST | 25,760,495 | 28.0% |
| ENTER_EXECUTOR | 12,046,400 | 13.1% |
| LOAD_FAST | 7,391,390 | 8.0% |
| LOAD_CONST | 4,239,008 | 4.6% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 168,983,257 | 49.1% |
| ENTER_EXECUTOR | 166,431,593 | 48.3% |
| SWAP | 4,355,288 | 1.3% |
| LOAD_FAST | 2,223,165 | 0.6% |
| FOR_ITER_LIST | 1,315,169 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 168,353,882 | 48.9% |
| LOAD_FAST | 92,103,600 | 26.7% |
| LOAD_FAST_LOAD_FAST | 45,853,940 | 13.3% |
| RETURN_CONST | 20,444,477 | 5.9% |
| LOAD_GLOBAL_MODULE | 5,914,294 | 1.7% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 104,017,388 | 79.6% |
| LOAD_GLOBAL_BUILTIN | 22,948,092 | 17.6% |
| LOAD_FAST | 1,979,046 | 1.5% |
| ENTER_EXECUTOR | 770,940 | 0.6% |
| LOAD_ATTR_MODULE | 676,871 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 29,123,720 | 22.3% |
| COMPARE_OP_INT | 28,580,085 | 21.9% |
| LOAD_FAST_LOAD_FAST | 23,145,252 | 17.7% |
| LOAD_FAST | 19,185,202 | 14.7% |
| PUSH_NULL | 11,047,000 | 8.5% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,176,426,445 | 86.4% |
| LOAD_FAST_LOAD_FAST | 346,010,547 | 7.2% |
| COPY | 94,224,709 | 2.0% |
| LOAD_ATTR_INSTANCE_VALUE | 56,902,458 | 1.2% |
| ENTER_EXECUTOR | 53,299,601 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,232,807,662 | 25.5% |
| TO_BOOL_BOOL | 673,389,295 | 13.9% |
| STORE_FAST | 369,324,999 | 7.6% |
| LOAD_ATTR_METHOD_NO_DICT | 315,816,034 | 6.5% |
| RETURN_VALUE | 275,646,244 | 5.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 838,720,018 | 51.4% |
| LOAD_ATTR_INSTANCE_VALUE | 315,816,034 | 19.4% |
| LOAD_CONST | 115,233,047 | 7.1% |
| LOAD_GLOBAL_MODULE | 71,926,491 | 4.4% |
| LOAD_ATTR_SLOT | 59,239,459 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 919,077,424 | 56.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 157,807,676 | 9.7% |
| LOAD_CONST | 152,601,450 | 9.4% |
| CALL_PY_EXACT_ARGS | 124,491,987 | 7.6% |
| LOAD_FAST_LOAD_FAST | 94,510,727 | 5.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,703,604,841 | 77.0% |
| LOAD_ATTR_SLOT | 122,724,739 | 5.6% |
| LOAD_ATTR_INSTANCE_VALUE | 105,320,662 | 4.8% |
| ENTER_EXECUTOR | 77,828,777 | 3.5% |
| LOAD_ATTR | 60,813,608 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 880,223,159 | 39.8% |
| CALL_PY_EXACT_ARGS | 623,139,748 | 28.2% |
| LOAD_FAST_LOAD_FAST | 529,012,254 | 23.9% |
| LOAD_CONST | 61,810,024 | 2.8% |
| LOAD_GLOBAL_MODULE | 60,947,559 | 2.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 520,231,730 | 96.7% |
| LOAD_ATTR_MODULE | 12,087,739 | 2.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,766,640 | 0.3% |
| LOAD_ATTR_CLASS | 1,546,560 | 0.3% |
| LOAD_FAST_LOAD_FAST | 1,238,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 435,260,081 | 80.9% |
| CALL_ISINSTANCE | 33,722,112 | 6.3% |
| LOAD_ATTR_MODULE | 12,087,739 | 2.2% |
| LOAD_FAST | 10,895,147 | 2.0% |
| LOAD_FAST_LOAD_FAST | 9,445,252 | 1.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 148,773,004 | 89.1% |
| LOAD_FAST_LOAD_FAST | 15,118,469 | 9.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,358,539 | 0.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,014,728 | 0.6% |
| ENTER_EXECUTOR | 469,714 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,982,046 | 24.5% |
| GET_ITER | 25,700,680 | 15.4% |
| LOAD_GLOBAL_BUILTIN | 20,518,820 | 12.3% |
| LOAD_ATTR_METHOD_NO_DICT | 12,596,740 | 7.5% |
| LOAD_FAST_LOAD_FAST | 11,971,580 | 7.2% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,931,820 | 77.9% |
| ENTER_EXECUTOR | 9,016,084 | 9.6% |
| LOAD_ATTR_SLOT | 6,457,651 | 6.9% |
| RETURN_VALUE | 2,412,365 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,204,546 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 76,955,947 | 82.2% |
| COPY_FREE_VARS | 5,277,311 | 5.6% |
| TO_BOOL_NONE | 4,445,419 | 4.7% |
| GET_ITER | 1,929,735 | 2.1% |
| RETURN_VALUE | 1,122,925 | 1.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,874,103,337 | 92.2% |
| LOAD_ATTR_SLOT | 54,754,971 | 2.7% |
| COPY | 45,868,058 | 2.3% |
| LOAD_DEREF | 17,095,860 | 0.8% |
| LOAD_FAST_LOAD_FAST | 13,454,652 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 457,485,951 | 22.5% |
| TO_BOOL_NONE | 213,312,992 | 10.5% |
| COMPARE_OP_FLOAT | 136,326,335 | 6.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 122,724,739 | 6.0% |
| LIST_EXTEND | 98,283,851 | 4.8% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,406,201,552 | 26.1% |
| POP_JUMP_IF_FALSE | 1,184,101,594 | 22.0% |
| RESUME_CHECK | 1,141,990,979 | 21.2% |
| STORE_FAST | 687,237,535 | 12.8% |
| POP_JUMP_IF_TRUE | 146,594,967 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,448,318,843 | 64.0% |
| CALL_BUILTIN_FAST | 579,419,620 | 10.8% |
| CALL_ISINSTANCE | 377,958,010 | 7.0% |
| LOAD_ATTR | 297,852,157 | 5.5% |
| LOAD_DEREF | 160,593,427 | 3.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,250,804,316 | 31.9% |
| RESUME_CHECK | 519,570,597 | 13.2% |
| STORE_FAST | 517,256,788 | 13.2% |
| POP_JUMP_IF_FALSE | 389,953,909 | 9.9% |
| LOAD_FAST_LOAD_FAST | 143,965,323 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 619,366,351 | 15.8% |
| LOAD_FAST_LOAD_FAST | 584,129,390 | 14.9% |
| CALL_ISINSTANCE | 548,046,168 | 14.0% |
| LOAD_ATTR_MODULE | 520,231,730 | 13.2% |
| CONTAINS_OP | 285,480,985 | 7.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,173,196 | 98.2% |
| LOAD_DEREF | 77,440 | 1.8% |
| LOAD_SUPER_ATTR | 960 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 4,157,804 | 97.8% |
| LOAD_GLOBAL_MODULE | 87,932 | 2.1% |
| STORE_FAST | 5,760 | 0.1% |
| LOAD_GLOBAL | 200 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 166,690,580 | 100.0% |
| LOAD_DEREF | 12,040 | 0.0% |
| LOAD_SUPER_ATTR | 8,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 93,086,805 | 55.8% |
| LOAD_FAST | 49,236,040 | 29.5% |
| CALL_PY_EXACT_ARGS | 14,334,425 | 8.6% |
| CALL_PY_WITH_DEFAULTS | 7,932,960 | 4.8% |
| LOAD_GLOBAL_MODULE | 861,489 | 0.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,009,198,866 | 43.1% |
| CACHE | 1,710,258,453 | 24.5% |
| POP_TOP | 381,723,639 | 5.5% |
| SEND_GEN | 294,673,969 | 4.2% |
| COPY_FREE_VARS | 286,645,376 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,972,031,668 | 42.6% |
| LOAD_GLOBAL_BUILTIN | 1,141,990,979 | 16.4% |
| POP_TOP | 728,168,593 | 10.4% |
| LOAD_GLOBAL_MODULE | 519,570,597 | 7.4% |
| LOAD_FAST_LOAD_FAST | 411,378,033 | 5.9% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 294,690,099 | 65.2% |
| LOAD_CONST | 156,985,010 | 34.8% |
| SEND | 6,223 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 294,673,969 | 65.2% |
| POP_TOP | 156,972,770 | 34.8% |
| END_SEND | 15,180 | 0.0% |
| YIELD_VALUE | 15,140 | 0.0% |
| RESUME | 3,693 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 549,613,080 | 48.7% |
| LOAD_FAST_LOAD_FAST | 401,632,585 | 35.6% |
| SWAP | 94,456,869 | 8.4% |
| BINARY_SUBSCR_LIST_INT | 36,129,520 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 17,061,760 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 418,182,759 | 37.0% |
| RETURN_CONST | 229,196,800 | 20.3% |
| LOAD_FAST_LOAD_FAST | 221,297,607 | 19.6% |
| LOAD_CONST | 117,517,959 | 10.4% |
| NOP | 72,413,237 | 6.4% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 885,170,759 | 50.4% |
| LOAD_FAST | 821,568,452 | 46.8% |
| SWAP | 45,868,058 | 2.6% |
| STORE_ATTR_SLOT | 3,010,914 | 0.2% |
| LOAD_ATTR_SLOT | 848,420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 515,492,969 | 29.3% |
| LOAD_CONST | 401,594,773 | 22.9% |
| RETURN_CONST | 385,910,388 | 22.0% |
| LOAD_FAST | 370,435,548 | 21.1% |
| LOAD_GLOBAL_BUILTIN | 33,864,366 | 1.9% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 125,240,880 | 46.7% |
| LOAD_FAST | 89,944,811 | 33.6% |
| CALL_BUILTIN_O | 18,664,880 | 7.0% |
| RETURN_VALUE | 10,752,340 | 4.0% |
| BINARY_SUBSCR_TUPLE_INT | 5,092,440 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 97,407,187 | 36.4% |
| LOAD_FAST | 89,181,247 | 33.3% |
| RETURN_CONST | 23,103,024 | 8.6% |
| JUMP_BACKWARD | 19,663,329 | 7.3% |
| ENTER_EXECUTOR | 17,753,211 | 6.6% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 1,070,632,626 | 24.1% |
| LOAD_FAST | 946,135,255 | 21.3% |
| LOAD_ATTR_INSTANCE_VALUE | 673,389,295 | 15.2% |
| CALL_BUILTIN_FAST | 654,281,422 | 14.7% |
| RETURN_VALUE | 363,821,026 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,219,154,885 | 72.4% |
| POP_JUMP_IF_TRUE | 1,046,437,708 | 23.5% |
| EXTENDED_ARG | 114,769,088 | 2.6% |
| UNARY_NOT | 63,177,897 | 1.4% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 18,040 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 138,529,452 | 66.0% |
| COPY | 17,216,422 | 8.2% |
| CALL_BUILTIN_O | 17,121,860 | 8.2% |
| BINARY_OP | 12,261,974 | 5.8% |
| LOAD_ATTR_SLOT | 9,236,440 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 163,436,368 | 77.8% |
| POP_JUMP_IF_TRUE | 45,704,438 | 21.8% |
| UNARY_NOT | 574,409 | 0.3% |
| EXTENDED_ARG | 218,630 | 0.1% |
| TO_BOOL_BOOL | 18,400 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,445,490 | 61.0% |
| LOAD_ATTR_INSTANCE_VALUE | 54,100,581 | 28.1% |
| ENTER_EXECUTOR | 8,621,592 | 4.5% |
| LOAD_ATTR_SLOT | 6,507,680 | 3.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,285,220 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 103,667,076 | 53.9% |
| POP_JUMP_IF_TRUE | 83,282,203 | 43.3% |
| UNARY_NOT | 4,191,745 | 2.2% |
| EXTENDED_ARG | 1,303,800 | 0.7% |
| TO_BOOL | 30,920 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 219,409,586 | 35.5% |
| LOAD_ATTR_SLOT | 213,312,992 | 34.5% |
| LOAD_ATTR_INSTANCE_VALUE | 75,418,999 | 12.2% |
| LOAD_ATTR | 47,056,483 | 7.6% |
| RETURN_CONST | 18,545,220 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 517,389,304 | 83.7% |
| POP_JUMP_IF_TRUE | 98,272,386 | 15.9% |
| EXTENDED_ARG | 1,382,260 | 0.2% |
| TO_BOOL_ALWAYS_TRUE | 774,671 | 0.1% |
| TO_BOOL | 167,401 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 345,372,856 | 64.8% |
| LOAD_FAST | 136,095,349 | 25.5% |
| YIELD_VALUE | 33,453,160 | 6.3% |
| FOR_ITER | 8,306,140 | 1.6% |
| BINARY_SUBSCR_DICT | 6,550,620 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 337,773,598 | 63.4% |
| STORE_FAST_STORE_FAST | 194,834,385 | 36.5% |
| LOAD_FAST | 387,280 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 0.0% |
| UNPACK_SEQUENCE_LIST | 33,880 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 270,503,027 | 47.2% |
| RETURN_VALUE | 132,575,768 | 23.1% |
| FOR_ITER_LIST | 90,348,161 | 15.8% |
| LOAD_FAST | 48,731,855 | 8.5% |
| BINARY_SUBSCR_LIST_INT | 19,981,939 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 505,749,833 | 88.2% |
| STORE_FAST | 50,046,493 | 8.7% |
| STORE_FAST_LOAD_FAST | 12,249,620 | 2.1% |
| STORE_DEREF | 3,579,820 | 0.6% |
| LOAD_FAST | 1,210,003 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,973,711 | 88.8% |
| LOAD_FAST_LOAD_FAST | 10,670,209 | 6.6% |
| LOAD_GLOBAL_MODULE | 4,028,920 | 2.5% |
| BINARY_SUBSCR_TUPLE_INT | 1,607,500 | 1.0% |
| CALL_LEN | 927,540 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 105,861,200 | 65.3% |
| BINARY_SUBSCR_LIST_INT | 35,691,400 | 22.0% |
| CALL_PY_EXACT_ARGS | 4,254,800 | 2.6% |
| BINARY_SUBSCR | 3,225,560 | 2.0% |
| STORE_SUBSCR | 3,225,520 | 2.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 114,769,088 | 27.0% |
| LOAD_FAST | 57,423,980 | 13.5% |
| JUMP_BACKWARD | 42,675,600 | 10.0% |
| CALL_LIST_APPEND | 41,813,048 | 9.8% |
| POP_TOP | 34,367,700 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 161,893,044 | 38.1% |
| ENTER_EXECUTOR | 80,803,129 | 19.0% |
| POP_JUMP_IF_NONE | 49,201,354 | 11.6% |
| FOR_ITER_GEN | 34,084,480 | 8.0% |
| FOR_ITER | 27,379,420 | 6.4% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 421,115,820 | 89.0% |
| BINARY_OP_SUBTRACT_INT | 14,186,040 | 3.0% |
| LOAD_ATTR_SLOT | 13,808,080 | 2.9% |
| LOAD_FAST | 10,384,500 | 2.2% |
| LOAD_CONST | 6,650,480 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 238,426,400 | 50.4% |
| STORE_FAST | 223,084,880 | 47.2% |
| LOAD_CONST | 5,991,880 | 1.3% |
| RETURN_VALUE | 4,379,400 | 0.9% |
| BINARY_OP_INPLACE_ADD_UNICODE | 307,120 | 0.1% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,840,012 | 73.2% |
| RETURN_VALUE | 8,776,840 | 21.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,640,621 | 4.0% |
| LOAD_ATTR_SLOT | 145,520 | 0.4% |
| CALL_TUPLE_1 | 88,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,435,433 | 30.5% |
| YIELD_VALUE | 10,243,140 | 25.1% |
| BINARY_OP_ADD_UNICODE | 6,406,760 | 15.7% |
| RETURN_VALUE | 4,545,661 | 11.2% |
| LOAD_FAST | 4,242,900 | 10.4% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,353,379 | 57.9% |
| RETURN_GENERATOR | 7,374,080 | 21.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,672 | 13.4% |
| LOAD_ATTR_SLOT | 1,464,668 | 4.2% |
| CALL | 585,500 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,089,020 | 54.3% |
| BINARY_OP | 4,799,432 | 13.6% |
| BUILD_TUPLE | 3,877,228 | 11.0% |
| YIELD_VALUE | 3,228,920 | 9.2% |
| STORE_FAST | 1,211,548 | 3.4% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 339,554,608 | 78.7% |
| LOAD_ATTR_INSTANCE_VALUE | 30,303,929 | 7.0% |
| LOAD_ATTR_WITH_HINT | 29,698,512 | 6.9% |
| COPY | 17,166,640 | 4.0% |
| LOAD_FAST_LOAD_FAST | 11,235,045 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 112,528,498 | 26.1% |
| COMPARE_OP_INT | 47,045,390 | 10.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 44,677,351 | 10.4% |
| STORE_FAST | 44,641,520 | 10.4% |
| LOAD_CONST | 37,414,381 | 8.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 165,545,580 | 53.2% |
| LOAD_FAST_LOAD_FAST | 48,555,126 | 15.6% |
| LOAD_CONST | 35,792,514 | 11.5% |
| LOAD_FAST | 33,500,357 | 10.8% |
| BINARY_SUBSCR_LIST_INT | 26,894,680 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 119,712,120 | 38.5% |
| LOAD_FAST_LOAD_FAST | 75,197,391 | 24.2% |
| ENTER_EXECUTOR | 61,474,121 | 19.8% |
| JUMP_BACKWARD | 47,752,211 | 15.4% |
| RETURN_CONST | 6,015,780 | 1.9% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,442,942 | 62.1% |
| LOAD_ATTR_SLOT | 9,521,020 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,790,920 | 7.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,333,540 | 5.6% |
| COPY | 3,678,542 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 41,180,494 | 52.8% |
| POP_JUMP_IF_TRUE | 35,939,095 | 46.1% |
| UNARY_NOT | 800,240 | 1.0% |
| TO_BOOL_NONE | 48,220 | 0.1% |
| EXTENDED_ARG | 22,280 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 76,107,046 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 48,922,740 | 64.3% |
| LOAD_FAST | 25,972,763 | 34.1% |
| RETURN_CONST | 1,054,742 | 1.4% |
| JUMP_BACKWARD | 133,920 | 0.2% |
| LOAD_CONST | 8,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 91,325,259 | 45.4% |
| GET_ITER | 75,708,868 | 37.6% |
| EXTENDED_ARG | 34,084,480 | 16.9% |
| LOAD_FAST | 56,160 | 0.0% |
| FOR_ITER | 2,182 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 124,915,779 | 62.1% |
| POP_TOP | 76,258,049 | 37.9% |
| RESUME | 2,182 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 920 | 0.0% |
| STORE_FAST | 640 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,638,483 | 45.0% |
| BINARY_SLICE | 20,771,700 | 21.4% |
| LOAD_CONST | 14,872,700 | 15.4% |
| CALL_STR_1 | 6,406,760 | 6.6% |
| BUILD_STRING | 2,681,520 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,511,663 | 22.2% |
| CALL_BUILTIN_O | 21,212,480 | 21.9% |
| BUILD_TUPLE | 20,613,200 | 21.3% |
| LOAD_CONST | 11,487,160 | 11.9% |
| STORE_FAST | 10,454,309 | 10.8% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40,831,620 | 68.9% |
| LOAD_FAST | 18,445,984 | 31.1% |
| RETURN_VALUE | 3,800 | 0.0% |
| LOAD_ATTR | 1,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,331,652 | 79.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,921,357 | 16.7% |
| LOAD_FAST_LOAD_FAST | 1,638,360 | 2.8% |
| CALL | 226,195 | 0.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 125,840 | 0.2% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,633,931 | 32.9% |
| LOAD_ATTR_INSTANCE_VALUE | 59,949,366 | 25.7% |
| ENTER_EXECUTOR | 54,815,280 | 23.5% |
| LOAD_ATTR_SLOT | 23,534,700 | 10.1% |
| COPY | 9,559,526 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120,646,740 | 51.8% |
| POP_JUMP_IF_TRUE | 109,997,943 | 47.2% |
| EXTENDED_ARG | 1,209,080 | 0.5% |
| TO_BOOL_NONE | 774,207 | 0.3% |
| TO_BOOL_ALWAYS_TRUE | 155,882 | 0.1% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 289,077,260 | 50.2% |
| LOAD_ATTR_INSTANCE_VALUE | 155,955,800 | 27.1% |
| LOAD_FAST_LOAD_FAST | 38,907,466 | 6.8% |
| ENTER_EXECUTOR | 31,079,020 | 5.4% |
| BINARY_SUBSCR | 26,268,940 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 245,989,264 | 42.7% |
| BINARY_OP_SUBTRACT_FLOAT | 96,946,560 | 16.8% |
| LOAD_FAST | 82,954,674 | 14.4% |
| YIELD_VALUE | 41,716,800 | 7.2% |
| STORE_FAST | 33,624,926 | 5.8% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,362,893 | 100.0% |
| LOAD_GLOBAL_MODULE | 280 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,871,976 | 78.1% |
| NOP | 2,286,751 | 20.1% |
| RETURN_CONST | 201,411 | 1.8% |
| PUSH_EXC_INFO | 1,635 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,360 | 0.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 138,348,875 | 90.8% |
| LOAD_FAST | 7,041,118 | 4.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,898,580 | 1.2% |
| LOAD_ATTR_MODULE | 1,765,760 | 1.2% |
| RETURN_VALUE | 1,389,580 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 76,156,357 | 50.0% |
| BUILD_STRING | 68,262,312 | 44.8% |
| LOAD_FAST | 7,864,815 | 5.2% |
| LOAD_GLOBAL_MODULE | 11,640 | 0.0% |
| LOAD_GLOBAL | 120 | 0.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,331,998 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,474,644 | 44.4% |
| LOAD_FAST | 3,144,601 | 25.5% |
| LOAD_FAST_LOAD_FAST | 2,272,240 | 18.4% |
| STORE_FAST | 697,548 | 5.7% |
| CALL_METHOD_DESCRIPTOR_O | 255,200 | 2.1% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 68,262,312 | 88.9% |
| LOAD_CONST | 8,559,102 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 48,929,440 | 63.7% |
| CALL | 15,956,463 | 20.8% |
| STORE_FAST | 4,717,391 | 6.1% |
| BINARY_OP_ADD_UNICODE | 2,681,520 | 3.5% |
| CALL_LIST_APPEND | 1,864,080 | 2.4% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,759,160 | 83.7% |
| LOAD_ATTR | 15,441,321 | 11.2% |
| CALL_METHOD_DESCRIPTOR_O | 2,681,260 | 1.9% |
| RETURN_VALUE | 2,058,840 | 1.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,138,100 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 138,348,875 | 100.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 40,514 | 62.2% |
| LOAD_FAST | 17,520 | 26.9% |
| MAP_ADD | 4,920 | 7.6% |
| BUILD_MAP | 766 | 1.2% |
| BUILD_CONST_KEY_MAP | 660 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,260 | 63.4% |
| DICT_MERGE | 17,520 | 26.9% |
| BUILD_MAP | 4,380 | 6.7% |
| STORE_FAST | 726 | 1.1% |
| STORE_NAME | 520 | 0.8% |


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

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 21,194,640 | 36.8% |
| RETURN_VALUE | 8,511,240 | 14.8% |
| LOAD_FAST_LOAD_FAST | 8,303,708 | 14.4% |
| JUMP_FORWARD | 6,377,120 | 11.1% |
| STORE_FAST | 6,068,240 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,497,500 | 47.7% |
| JUMP_BACKWARD | 22,003,740 | 38.2% |
| ENTER_EXECUTOR | 6,414,940 | 11.1% |
| CALL_FUNCTION_EX | 1,615,440 | 2.8% |
| EXTENDED_ARG | 53,160 | 0.1% |


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

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 136,326,335 | 67.0% |
| BINARY_SUBSCR | 31,176,840 | 15.3% |
| LOAD_GLOBAL_MODULE | 8,575,465 | 4.2% |
| LOAD_CONST | 8,437,267 | 4.1% |
| ENTER_EXECUTOR | 7,994,220 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 128,319,295 | 63.0% |
| POP_JUMP_IF_TRUE | 43,210,860 | 21.2% |
| POP_JUMP_IF_FALSE | 32,079,084 | 15.8% |
| COMPARE_OP | 500 | 0.0% |
| EXTENDED_ARG | 303 | 0.0% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,400,162 | 46.5% |
| SWAP | 17,545,080 | 26.8% |
| LOAD_FAST_LOAD_FAST | 15,912,426 | 24.3% |
| ENTER_EXECUTOR | 1,187,600 | 1.8% |
| LOAD_DEREF | 322,326 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,482,195 | 69.6% |
| RETURN_CONST | 5,900,197 | 9.0% |
| ENTER_EXECUTOR | 5,799,960 | 8.9% |
| LOAD_CONST | 3,945,685 | 6.0% |
| LOAD_FAST_LOAD_FAST | 3,077,280 | 4.7% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,285,120 | 60.3% |
| STORE_FAST | 339,970 | 15.9% |
| CALL | 189,468 | 8.9% |
| POP_TOP | 104,925 | 4.9% |
| NOP | 64,855 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 648,420 | 30.4% |
| BUILD_LIST | 642,560 | 30.1% |
| RETURN_VALUE | 266,268 | 12.5% |
| RERAISE | 201,920 | 9.5% |
| RETURN_CONST | 129,467 | 6.1% |


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

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 130,490,885 | 88.0% |
| CALL_KW | 14,181,920 | 9.6% |
| STORE_FAST | 1,602,100 | 1.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,065,960 | 0.7% |
| ENTER_EXECUTOR | 327,680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 146,485,145 | 98.8% |
| STORE_FAST | 1,721,380 | 1.2% |
| UNPACK_SEQUENCE_TUPLE | 23,720 | 0.0% |


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

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,000,520 | 77.0% |
| RETURN_GENERATOR | 4,562,729 | 22.0% |
| BINARY_SUBSCR | 185,800 | 0.9% |
| LOAD_FAST | 9,440 | 0.0% |
| RETURN_VALUE | 7,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,767,929 | 100.0% |


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

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,576,130 | 86.2% |
| LOAD_FAST_LOAD_FAST | 4,357,142 | 5.2% |
| LOAD_DEREF | 3,109,100 | 3.7% |
| ENTER_EXECUTOR | 2,965,784 | 3.6% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,384,526 | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT | 11,182,914 | 13.5% |
| CALL_BUILTIN_O | 5,616,211 | 6.8% |
| CONTAINS_OP | 5,597,120 | 6.7% |
| CALL_PY_EXACT_ARGS | 4,361,700 | 5.3% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 1,523 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 962 | 63.2% |
| CALL_INTRINSIC_1 | 320 | 21.0% |
| JUMP_BACKWARD | 241 | 15.8% |


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

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 184,307 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 183,100 | 99.3% |
| TO_BOOL_BOOL | 960 | 0.5% |
| TO_BOOL | 247 | 0.1% |


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
| INSTRUMENTED_JUMP_BACKWARD | 5,928 | 52.5% |
| GET_ITER | 5,280 | 46.8% |
| SWAP | 80 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,008 | 53.2% |
| NOP | 4,080 | 36.1% |
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
| INSTRUMENTED_POP_JUMP_IF_TRUE | 1,288 | 12.9% |
| LIST_APPEND | 400 | 4.0% |
| POP_TOP | 80 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_FOR_ITER | 5,928 | 59.2% |
| LOAD_FAST | 4,080 | 40.8% |


</details>

### INSTRUMENTED_POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,108 | 52.9% |
| TO_BOOL | 4,280 | 31.8% |
| TO_BOOL_STR | 1,240 | 9.2% |
| TO_BOOL_NONE | 360 | 2.7% |
| COMPARE_OP_STR | 280 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,680 | 42.2% |
| LOAD_GLOBAL | 5,360 | 39.9% |
| INSTRUMENTED_JUMP_BACKWARD | 1,288 | 9.6% |
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


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 916,819,381 | 21.4% |
|          hit | 3,320,681,229 | 77.4% |
|         miss | 50,162,863 | 1.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 995,071 | 38.8% |
| Failure | 1,572,823 | 61.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| subtract different types | 775,860 | 49.3% |
| multiply different types | 248,573 | 15.8% |
| add different types | 191,845 | 12.2% |
| add other | 60,090 | 3.8% |
| and int | 56,900 | 3.6% |
| remainder | 54,393 | 3.5% |
| floor divide | 45,740 | 2.9% |
| true divide different types | 23,885 | 1.5% |
| lshift | 23,629 | 1.5% |
| rshift | 20,315 | 1.3% |
| or | 18,071 | 1.1% |
| xor | 15,845 | 1.0% |
| subtract other | 12,960 | 0.8% |
| true divide float | 9,425 | 0.6% |
| power | 5,315 | 0.3% |
| multiply other | 4,320 | 0.3% |
| true divide other | 3,324 | 0.2% |
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
|     deferred | 698,715,587 | 22.6% |
|          hit | 2,381,099,164 | 77.2% |
|         miss | 4,760,738 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 189,027 | 43.3% |
| Failure | 247,542 | 56.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 78,640 | 31.8% |
| out of range | 75,692 | 30.6% |
| other | 59,881 | 24.2% |
| buffer int | 16,864 | 6.8% |
| list slice | 6,340 | 2.6% |
| code complex parameters | 4,780 | 1.9% |
| sequence int | 4,280 | 1.7% |
| buffer slice | 860 | 0.3% |
| tuple slice | 105 | 0.0% |
| string slice | 100 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 737,869,762,949,584,989,789 | 6,449,032,632,270.6% |
|        deopt | 22,840 | 0.0% |
|          hit | 9,980,957,912 | 87.2% |
|         miss | 251,552,729 | 2.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,253,598 | 85.5% |
| Failure | 890,737 | 14.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 178,263 | 20.0% |
| code complex parameters | 163,481 | 18.4% |
| no dict | 108,956 | 12.2% |
| cfunc noargs | 68,051 | 7.6% |
| class no vectorcall | 65,301 | 7.3% |
| meth descr varargs | 63,794 | 7.2% |
| cfunc varargs keywords | 54,019 | 6.1% |
| class mutable | 52,116 | 5.9% |
| other | 33,289 | 3.7% |
| meth descr varargs keywords | 18,294 | 2.1% |
| init not python | 17,120 | 1.9% |
| bound method | 11,972 | 1.3% |
| cmethod | 11,860 | 1.3% |
| init not simple | 11,860 | 1.3% |
| cfunc varargs | 11,157 | 1.3% |
| wrong number arguments | 9,840 | 1.1% |
| operator wrapper | 5,188 | 0.6% |
| method wrapper | 4,496 | 0.5% |
| str | 1,680 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 167,500,626 | 7.3% |
|          hit | 2,117,353,707 | 92.6% |
|         miss | 2,286,151 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 106,366 | 29.8% |
| Failure | 250,482 | 70.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 81,978 | 32.7% |
| different types | 52,331 | 20.9% |
| baseobject | 31,098 | 12.4% |
| other | 25,501 | 10.2% |
| float long | 17,177 | 6.9% |
| tuple | 15,272 | 6.1% |
| string | 10,640 | 4.2% |
| bool | 6,417 | 2.6% |
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
|     deferred | 737,869,762,948,889,865,545 | 39,721,241,609,770.0% |
|          hit | 1,206,155,091 | 64.9% |
|         miss | 140,659,623 | 7.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,705,120 | 90.0% |
| Failure | 299,348 | 10.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 113,358 | 37.9% |
| enumerate | 45,191 | 15.1% |
| set | 40,242 | 13.4% |
| zip | 19,856 | 6.6% |
| other | 19,480 | 6.5% |
| seq iter | 14,940 | 5.0% |
| dict values | 13,200 | 4.4% |
| reversed list | 9,121 | 3.0% |
| dict keys | 8,980 | 3.0% |
| itertools | 7,020 | 2.3% |
| ascii string | 5,280 | 1.8% |
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
|     deferred | 737,869,762,949,891,037,353 | 5,373,252,920,680.6% |
|        deopt | 1,816,793 | 0.0% |
|          hit | 11,465,594,911 | 83.5% |
|         miss | 743,632,509 | 5.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 14,745,860 | 92.8% |
| Failure | 1,143,854 | 7.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 339,281 | 29.7% |
| metaclass attribute | 247,284 | 21.6% |
| not managed dict | 142,163 | 12.4% |
| method | 138,307 | 12.1% |
| shadowed | 103,289 | 9.0% |
| mutable class | 67,815 | 5.9% |
| class method obj | 25,660 | 2.2% |
| overridden | 18,012 | 1.6% |
| class attr descriptor | 17,840 | 1.6% |
| non overriding descriptor | 12,616 | 1.1% |
| module attr not found | 11,120 | 1.0% |
| not in keys | 7,260 | 0.6% |
| class attr simple | 6,506 | 0.6% |
| non object slot | 3,501 | 0.3% |
| builtin class method | 3,140 | 0.3% |
| property | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 10,304,929 | 0.1% |
|        deopt | 9,360 | 0.0% |
|          hit | 9,314,865,206 | 99.9% |
|         miss | 329,963 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 545,141 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,287 | 0.0% |
|          hit | 170,962,636 | 100.0% |

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
|     deferred | 165,264,623 | 26.8% |
|          hit | 451,650,432 | 73.2% |
|         miss | 30,900 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,223 | 10.6% |
| Failure | 52,561 | 89.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| async generator send | 33,180 | 63.1% |
| other | 15,881 | 30.2% |
| list | 3,260 | 6.2% |
| dict keys | 240 | 0.5% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,058,283,696,216,168,624,083 | 134,211,783,012,273.5% |
|          hit | 2,692,117,230 | 89.0% |
|         miss | 259,279,023 | 8.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,024,565 | 98.0% |
| Failure | 101,530 | 2.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 48,940 | 48.2% |
| not in dict | 18,000 | 17.7% |
| overriding descriptor | 10,480 | 10.3% |
| not in keys | 7,480 | 7.4% |
| overridden | 5,280 | 5.2% |
| property | 4,020 | 4.0% |
| no dict | 3,100 | 3.1% |
| not managed dict | 2,670 | 2.6% |
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
|     deferred | 346,781,546 | 37.5% |
|          hit | 578,843,634 | 62.5% |
|         miss | 2,880 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 16,164 | 10.8% |
| Failure | 133,928 | 89.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 56,580 | 42.2% |
| py simple | 43,442 | 32.4% |
| dict subclass no override | 28,206 | 21.1% |
| out of range | 2,900 | 2.2% |
| bytearray int | 2,000 | 1.5% |
| other | 800 | 0.6% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,582,544,170,319,683,157,134 | 42,171,575,692,271.4% |
|          hit | 5,663,311,024 | 92.5% |
|         miss | 111,629,311 | 1.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,331,081 | 77.0% |
| Failure | 695,429 | 23.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 191,417 | 27.5% |
| other | 173,187 | 24.9% |
| tuple | 120,792 | 17.4% |
| mapping | 99,186 | 14.3% |
| dict | 37,370 | 5.4% |
| set | 33,306 | 4.8% |
| bytes | 19,199 | 2.8% |
| sequence | 16,705 | 2.4% |
| float | 2,604 | 0.4% |
| bytearray | 1,243 | 0.2% |
| memory view | 420 | 0.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 368,934,881,474,191,305,755 | 29,399,320,031,658.7% |
|          hit | 1,251,596,477 | 99.7% |
|         miss | 2,939,660 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 97,428 | 97.4% |
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
| Basic | 90,142,768,113 | 54.0% |
| Not specialized | 17,795,433,454 | 10.7% |
| Specialized hits | 57,361,476,490 | 34.4% |
| Specialized misses | 1,567,765,708 | 0.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR | 4,058,283,696,216,168,624,083 | 44.0% |
| TO_BOOL | 2,582,544,170,319,683,157,134 | 28.0% |
| LOAD_ATTR | 737,869,762,949,891,037,353 | 8.0% |
| CALL | 737,869,762,949,584,989,789 | 8.0% |
| FOR_ITER | 737,869,762,948,889,865,545 | 8.0% |
| UNPACK_SEQUENCE | 368,934,881,474,191,305,755 | 4.0% |
| BINARY_OP | 916,819,381 | 0.0% |
| BINARY_SUBSCR | 698,715,587 | 0.0% |
| STORE_SUBSCR | 346,781,546 | 0.0% |
| COMPARE_OP | 167,500,626 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 258,835,316 | 16.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 203,251,671 | 13.0% |
| STORE_ATTR_SLOT | 159,653,308 | 10.2% |
| CALL_PY_EXACT_ARGS | 125,727,058 | 8.0% |
| LOAD_ATTR_SLOT | 114,438,727 | 7.3% |
| STORE_ATTR_INSTANCE_VALUE | 99,546,927 | 6.3% |
| FOR_ITER_TUPLE | 70,355,153 | 4.5% |
| FOR_ITER_LIST | 70,295,670 | 4.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 68,361,948 | 4.4% |
| LOAD_ATTR_METHOD_NO_DICT | 67,413,425 | 4.3% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 2,028,030,269 | 27.7% |
| Calls to Python functions inlined | 5,285,054,019 | 72.3% |
| Calls via PyEval_EvalFrame (total) | 2,028,030,269 | 27.7% |
| Calls via PyEval_EvalFrame (vector) | 1,260,255,388 | 17.2% |
| Calls via PyEval_EvalFrame (generator) | 767,774,881 | 10.5% |
| Calls via PyEval_EvalFrame (legacy) | 5,294,820 | 0.1% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,254,940,688 | 17.2% |
| Calls via PyEval_EvalFrame (build class) | 19,880 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 342,977,387 | 4.7% |
| Calls via PyEval_EvalFrame (function ex) | 30,185,873 | 0.4% |
| Calls via PyEval_EvalFrame (api) | 227,067,475 | 3.1% |
| Calls via PyEval_EvalFrame (method) | 212,825,563 | 2.9% |
| Frame objects created | 65,043,358 | 0.9% |
| Frames pushed | 4,818,025,665 | 65.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 6,230,676,181 | 35.9% |
| Frees to freelist | 6,238,438,382 |  |
| Allocations | 11,130,197,428 | 64.1% |
| Allocations to 512 bytes | 11,014,601,639 | 63.4% |
| Allocations to 4 kbytes | 95,183,589 | 0.5% |
| Allocations over 4 kbytes | 20,412,200 | 0.1% |
| Frees | 11,458,704,884 |  |
| New values | 77,677,063 |  |
| Interpreter increfs | 86,432,814,832 | 77.4% |
| Interpreter decrefs | 99,868,849,967 | 78.1% |
| Increfs | 25,210,323,110 | 22.6% |
| Decrefs | 28,055,689,619 | 21.9% |
| Materialize dict (on request) | 5,306,561 | 6.8% |
| Materialize dict (new key) | 190,560 | 0.2% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 2,033,361 | 2.6% |
| Method cache hits | 3,007,105,794 |  |
| Method cache misses | 75,660,675 |  |
| Method cache collisions | 83,222,423 |  |
| Method cache dunder hits | 3,394,721,156 |  |
| Method cache dunder misses | 7,965,702 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 720,764 | 45,914,981 | 6,415,531,332 |
| 1 | 64,444 | 67,083,775 | 5,401,448,348 |
| 2 | 20,817 | 53,113,756 | 18,138,605,294 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 367,184 |  |
| Traces created | 48,790 | 13.3% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 1,945 | 0.5% |
| Trace too long | 950 | 0.3% |
| Trace too short | 318,394 | 86.7% |
| Inner loop found | 740 | 0.2% |
| Recursive call | 760 | 0.2% |
| Traces executed | 2,461,328,356 |  |
| Uops executed | 91,331,580,822 | 37.11 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 80 | 0.2% |
| <= 16 | 3,949 | 8.1% |
| <= 32 | 16,547 | 33.9% |
| <= 64 | 16,197 | 33.2% |
| <= 128 | 12,017 | 24.6% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 220 | 0.5% |
| <= 8 | 4,429 | 9.1% |
| <= 16 | 13,808 | 28.3% |
| <= 32 | 16,600 | 34.0% |
| <= 64 | 12,520 | 25.7% |
| <= 128 | 1,213 | 2.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 94,950,149 | 3.9% |
| <= 2 | 364,115,933 | 14.8% |
| <= 4 | 36,203,188 | 1.5% |
| <= 8 | 322,678,031 | 13.1% |
| <= 16 | 374,507,871 | 15.2% |
| <= 32 | 596,023,833 | 24.2% |
| <= 64 | 538,218,697 | 21.9% |
| <= 128 | 82,026,897 | 3.3% |
| <= 256 | 23,885,661 | 1.0% |
| <= 512 | 7,794,381 | 0.3% |
| <= 1,024 | 5,422,568 | 0.2% |
| <= 2,048 | 14,481,387 | 0.6% |
| <= 4,096 | 824,940 | 0.0% |
| <= 8,192 | 151,520 | 0.0% |
| <= 16,384 | 36,320 | 0.0% |
| <= 32,768 | 1,140 | 0.0% |
| <= 65,536 | 4,720 | 0.0% |
| <= 131,072 | 480 | 0.0% |
| <= 262,144 | 160 | 0.0% |
| <= 524,288 | 0 | 0.0% |
| <= 1,048,576 | 400 | 0.0% |
| <= 2,097,152 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 17,340,477,551 | 19.0% | 19.0% |  |
| _SET_IP | 11,356,797,963 | 12.4% | 31.4% |  |
| _CHECK_VALIDITY | 8,912,977,870 | 9.8% | 41.2% |  |
| STORE_FAST | 5,722,473,591 | 6.3% | 47.4% |  |
| LOAD_CONST | 4,977,886,006 | 5.5% | 52.9% |  |
| _GUARD_IS_FALSE_POP | 3,464,111,995 | 3.8% | 56.7% | 2.3% |
| _GUARD_TYPE_VERSION | 2,197,560,126 | 2.4% | 59.1% | 6.7% |
| _GUARD_BOTH_INT | 1,925,880,987 | 2.1% | 61.2% | 0.0% |
| COMPARE_OP_STR | 1,798,057,552 | 2.0% | 63.2% |  |
| _BINARY_OP_ADD_INT | 1,635,490,595 | 1.8% | 65.0% |  |
| _JUMP_TO_TOP | 1,606,267,403 | 1.8% | 66.7% |  |
| CONTAINS_OP | 1,564,119,559 | 1.7% | 68.4% |  |
| _EXIT_TRACE | 1,353,240,606 | 1.5% | 69.9% |  |
| _ITER_CHECK_LIST | 1,272,805,893 | 1.4% | 71.3% | 1.3% |
| _GUARD_NOT_EXHAUSTED_LIST | 1,255,860,914 | 1.4% | 72.7% | 21.3% |
| BINARY_SUBSCR_STR_INT | 1,184,615,160 | 1.3% | 74.0% | 0.0% |
| _ITER_NEXT_LIST | 988,397,594 | 1.1% | 75.1% |  |
| _GUARD_GLOBALS_VERSION | 917,352,295 | 1.0% | 76.1% | 0.5% |
| _GUARD_IS_TRUE_POP | 879,986,411 | 1.0% | 77.0% | 27.9% |
| _BINARY_SUBSCR | 800,401,779 | 0.9% | 77.9% |  |
| _GUARD_BOTH_FLOAT | 780,577,320 | 0.9% | 78.8% |  |
| _ITER_CHECK_RANGE | 643,905,918 | 0.7% | 79.5% | 0.1% |
| _GUARD_NOT_EXHAUSTED_RANGE | 643,227,198 | 0.7% | 80.2% | 5.7% |
| _CHECK_FUNCTION_EXACT_ARGS | 642,574,067 | 0.7% | 80.9% | 0.8% |
| _CHECK_PEP_523 | 642,574,067 | 0.7% | 81.6% |  |
| _CHECK_STACK_SPACE | 637,188,735 | 0.7% | 82.3% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 637,184,836 | 0.7% | 83.0% |  |
| _PUSH_FRAME | 637,184,836 | 0.7% | 83.7% |  |
| _SAVE_RETURN_OFFSET | 637,184,836 | 0.7% | 84.4% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 621,284,235 | 0.7% | 85.1% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 621,284,235 | 0.7% | 85.7% |  |
| _ITER_NEXT_RANGE | 606,260,937 | 0.7% | 86.4% |  |
| RESUME_CHECK | 565,566,232 | 0.6% | 87.0% | 0.0% |
| _BINARY_OP_MULTIPLY_FLOAT | 527,407,740 | 0.6% | 87.6% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 506,710,662 | 0.6% | 88.1% | 0.0% |
| _GUARD_KEYS_VERSION | 506,688,302 | 0.6% | 88.7% | 0.6% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 477,295,067 | 0.5% | 89.2% |  |
| _ITER_CHECK_TUPLE | 477,009,350 | 0.5% | 89.7% | 16.4% |
| _LOAD_ATTR_METHOD_NO_DICT | 460,156,742 | 0.5% | 90.2% |  |
| _GUARD_BUILTINS_VERSION | 456,663,082 | 0.5% | 90.7% | 0.0% |
| _LOAD_GLOBAL_BUILTINS | 456,653,922 | 0.5% | 91.2% |  |
| _LOAD_GLOBAL_MODULE | 455,832,860 | 0.5% | 91.7% |  |
| TO_BOOL_BOOL | 453,529,525 | 0.5% | 92.2% |  |
| PUSH_NULL | 404,515,611 | 0.4% | 92.7% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 399,004,180 | 0.4% | 93.1% | 36.0% |
| _LOAD_ATTR_SLOT | 382,044,459 | 0.4% | 93.5% |  |
| BINARY_SUBSCR_LIST_INT | 353,408,058 | 0.4% | 93.9% | 0.0% |
| LOAD_DEREF | 339,802,472 | 0.4% | 94.3% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 338,309,095 | 0.4% | 94.7% |  |
| COMPARE_OP_INT | 337,410,032 | 0.4% | 95.0% | 0.0% |
| _ITER_NEXT_TUPLE | 255,219,249 | 0.3% | 95.3% |  |
| COPY | 228,417,999 | 0.3% | 95.6% |  |
| _BINARY_OP | 210,875,011 | 0.2% | 95.8% |  |
| SWAP | 197,499,232 | 0.2% | 96.0% |  |
| _BINARY_OP_SUBTRACT_INT | 184,053,512 | 0.2% | 96.2% |  |
| _LOAD_ATTR | 182,467,003 | 0.2% | 96.4% |  |
| BINARY_SUBSCR_DICT | 153,544,693 | 0.2% | 96.6% |  |
| POP_TOP | 152,468,903 | 0.2% | 96.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 133,525,480 | 0.1% | 96.9% | 0.0% |
| _BINARY_OP_ADD_FLOAT | 131,231,820 | 0.1% | 97.0% |  |
| CALL_TYPE_1 | 126,180,429 | 0.1% | 97.2% |  |
| GET_ANEXT | 125,514,720 | 0.1% | 97.3% |  |
| _BINARY_OP_SUBTRACT_FLOAT | 121,937,760 | 0.1% | 97.5% |  |
| TO_BOOL_INT | 118,848,426 | 0.1% | 97.6% | 0.0% |
| STORE_SLICE | 117,834,860 | 0.1% | 97.7% |  |
| BUILD_SLICE | 115,518,240 | 0.1% | 97.8% |  |
| STORE_SUBSCR_LIST_INT | 110,671,060 | 0.1% | 98.0% |  |
| CALL_BUILTIN_O | 107,645,960 | 0.1% | 98.1% | 0.0% |
| _BINARY_OP_MULTIPLY_INT | 105,885,080 | 0.1% | 98.2% |  |
| CALL_ISINSTANCE | 105,459,797 | 0.1% | 98.3% |  |
| _STORE_SUBSCR | 95,781,816 | 0.1% | 98.4% |  |
| LIST_APPEND | 94,287,877 | 0.1% | 98.5% |  |
| BINARY_SUBSCR_TUPLE_INT | 88,250,138 | 0.1% | 98.6% |  |
| TO_BOOL_NONE | 65,638,200 | 0.1% | 98.7% | 89.5% |
| CALL_BUILTIN_FAST | 65,589,799 | 0.1% | 98.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 59,747,400 | 0.1% | 98.8% | 4.7% |
| UNPACK_SEQUENCE_TUPLE | 59,455,081 | 0.1% | 98.9% | 0.6% |
| _COMPARE_OP | 55,735,745 | 0.1% | 98.9% |  |
| GET_ITER | 51,996,445 | 0.1% | 99.0% |  |
| _CHECK_ATTR_MODULE | 51,646,863 | 0.1% | 99.1% |  |
| _LOAD_ATTR_MODULE | 51,646,863 | 0.1% | 99.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 51,552,825 | 0.1% | 99.2% |  |
| BUILD_TUPLE | 49,548,276 | 0.1% | 99.2% |  |
| CALL_LEN | 45,733,242 | 0.1% | 99.3% |  |
| UNPACK_SEQUENCE_LIST | 38,509,720 | 0.0% | 99.3% | 0.0% |
| CALL_STR_1 | 35,870,820 | 0.0% | 99.4% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 35,731,950 | 0.0% | 99.4% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 35,731,950 | 0.0% | 99.4% |  |
| _STORE_ATTR_SLOT | 34,307,571 | 0.0% | 99.5% |  |
| BINARY_SLICE | 34,189,445 | 0.0% | 99.5% |  |
| _LOAD_ATTR_WITH_HINT | 31,795,030 | 0.0% | 99.6% | 0.0% |
| _CHECK_ATTR_WITH_HINT | 31,795,030 | 0.0% | 99.6% |  |
| MAKE_FUNCTION | 28,699,341 | 0.0% | 99.6% |  |
| _GUARD_IS_NOT_NONE_POP | 26,561,520 | 0.0% | 99.6% | 2.3% |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 26,197,283 | 0.0% | 99.7% |  |
| BUILD_LIST | 23,091,074 | 0.0% | 99.7% |  |
| CALL_BUILTIN_CLASS | 21,801,147 | 0.0% | 99.7% |  |
| _POP_FRAME | 21,284,594 | 0.0% | 99.7% |  |
| SET_FUNCTION_ATTRIBUTE | 21,023,320 | 0.0% | 99.8% |  |
| COMPARE_OP_FLOAT | 16,690,909 | 0.0% | 99.8% | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 15,790,341 | 0.0% | 99.8% |  |
| _CHECK_ATTR_CLASS | 14,452,020 | 0.0% | 99.8% | 5.3% |
| TO_BOOL_STR | 13,945,368 | 0.0% | 99.8% | 0.0% |
| _LOAD_ATTR_CLASS | 13,681,080 | 0.0% | 99.9% |  |
| _GUARD_IS_NONE_POP | 12,184,376 | 0.0% | 99.9% | 14.4% |
| TO_BOOL_ALWAYS_TRUE | 11,296,640 | 0.0% | 99.9% | 93.1% |
| IS_OP | 11,232,514 | 0.0% | 99.9% |  |
| UNARY_NOT | 10,574,454 | 0.0% | 99.9% |  |
| BUILD_MAP | 7,369,415 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 7,225,260 | 0.0% | 99.9% |  |
| DICT_MERGE | 7,055,883 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 5,784,220 | 0.0% | 99.9% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,608,524 | 0.0% | 99.9% |  |
| MAP_ADD | 5,583,260 | 0.0% | 99.9% |  |
| CALL_INTRINSIC_1 | 5,254,663 | 0.0% | 99.9% |  |
| _TO_BOOL | 4,741,863 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 4,550,840 | 0.0% | 100.0% | 7.6% |
| TO_BOOL_LIST | 4,468,699 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 4,203,060 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 3,735,213 | 0.0% | 100.0% |  |
| _CHECK_ATTR_METHOD_LAZY_DICT | 3,199,320 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_LAZY_DICT | 3,199,320 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 2,793,860 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 2,793,860 | 0.0% | 100.0% |  |
| SET_ADD | 2,683,640 | 0.0% | 100.0% |  |
| _STORE_ATTR | 2,638,560 | 0.0% | 100.0% |  |
| STORE_DEREF | 1,964,000 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,389,400 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 1,260,560 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 721,280 | 0.0% | 100.0% |  |
| BUILD_STRING | 552,340 | 0.0% | 100.0% |  |
| MAKE_CELL | 383,548 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 376,951 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 311,780 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 139,900 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 135,334 | 0.0% | 100.0% |  |
| LOAD_NAME | 110,080 | 0.0% | 100.0% |  |
| BEFORE_WITH | 93,456 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 89,040 | 0.0% | 100.0% |  |
| STORE_NAME | 37,460 | 0.0% | 100.0% |  |
| DELETE_FAST | 36,838 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 13,710 | 0.0% | 100.0% |  |
| LIST_EXTEND | 12,183 | 0.0% | 100.0% |  |
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
| FOR_ITER | 250,070 |
| FOR_ITER_GEN | 67,404 |
| CALL | 5,725 |
| LOAD_ATTR_PROPERTY | 3,769 |
| YIELD_VALUE | 2,398 |
| CALL_PY_WITH_DEFAULTS | 2,140 |
| CALL_LIST_APPEND | 1,819 |
| CALL_KW | 1,466 |
| BINARY_SUBSCR_GETITEM | 1,320 |
| CALL_FUNCTION_EX | 720 |
| CALL_ALLOC_AND_ENTER_INIT | 660 |
| RETURN_GENERATOR | 160 |
| BINARY_OP_INPLACE_ADD_UNICODE | 60 |
| SEND | 60 |
| STORE_ATTR_WITH_HINT | 60 |
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
