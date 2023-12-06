
# Pystats results

- benchmark: dask
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 321,468,437 | 20.3% | 20.3% |  |
| STORE_FAST | 79,614,758 | 5.0% | 25.3% |  |
| RESUME_CHECK | 76,427,049 | 4.8% | 30.1% | 0.0% |
| LOAD_CONST | 66,233,757 | 4.2% | 34.3% |  |
| POP_JUMP_IF_FALSE | 63,601,102 | 4.0% | 38.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 57,727,552 | 3.6% | 41.9% | 0.6% |
| RETURN_VALUE | 54,417,697 | 3.4% | 45.3% |  |
| LOAD_FAST_LOAD_FAST | 47,009,021 | 3.0% | 48.3% |  |
| LOAD_GLOBAL_MODULE | 43,159,233 | 2.7% | 51.0% | 0.0% |
| POP_TOP | 42,927,075 | 2.7% | 53.7% |  |
| LOAD_GLOBAL_BUILTIN | 36,791,815 | 2.3% | 56.0% | 0.0% |
| LOAD_ATTR_SLOT | 32,997,870 | 2.1% | 58.1% | 3.5% |
| CALL_PY_EXACT_ARGS | 30,342,207 | 1.9% | 60.0% | 0.4% |
| CALL | 27,206,298 | 1.7% | 61.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 26,504,972 | 1.7% | 63.4% | 1.4% |
| INTERPRETER_EXIT | 25,153,535 | 1.6% | 65.0% |  |
| TO_BOOL_BOOL | 24,909,458 | 1.6% | 66.6% |  |
| LOAD_ATTR_WITH_HINT | 21,038,976 | 1.3% | 67.9% | 0.3% |
| RETURN_CONST | 20,829,386 | 1.3% | 69.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 20,301,042 | 1.3% | 70.5% | 0.1% |
| LOAD_ATTR | 20,203,198 | 1.3% | 71.8% |  |
| PUSH_NULL | 19,626,385 | 1.2% | 73.0% |  |
| NOP | 17,320,759 | 1.1% | 74.1% |  |
| SWAP | 15,824,962 | 1.0% | 75.1% |  |
| STORE_ATTR_SLOT | 15,186,023 | 1.0% | 76.0% | 6.0% |
| BUILD_MAP | 14,593,526 | 0.9% | 77.0% |  |
| GET_ITER | 13,961,060 | 0.9% | 77.8% |  |
| POP_JUMP_IF_TRUE | 13,044,626 | 0.8% | 78.7% |  |
| CALL_FUNCTION_EX | 11,742,972 | 0.7% | 79.4% |  |
| ENTER_EXECUTOR | 11,315,384 | 0.7% | 80.1% |  |
| BUILD_LIST | 11,001,439 | 0.7% | 80.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 10,541,374 | 0.7% | 81.5% | 0.0% |
| COPY | 10,373,583 | 0.7% | 82.1% |  |
| BINARY_SUBSCR_DICT | 10,230,313 | 0.6% | 82.8% |  |
| CONTAINS_OP | 10,134,958 | 0.6% | 83.4% |  |
| IS_OP | 9,360,193 | 0.6% | 84.0% |  |
| BUILD_TUPLE | 9,210,598 | 0.6% | 84.6% |  |
| DICT_MERGE | 8,856,100 | 0.6% | 85.1% |  |
| LOAD_DEREF | 8,767,124 | 0.6% | 85.7% |  |
| TO_BOOL | 8,567,461 | 0.5% | 86.2% |  |
| COMPARE_OP_INT | 8,135,174 | 0.5% | 86.8% | 0.3% |
| LIST_EXTEND | 8,056,352 | 0.5% | 87.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 8,044,661 | 0.5% | 87.8% | 0.1% |
| CALL_INTRINSIC_1 | 7,975,838 | 0.5% | 88.3% |  |
| LOAD_ATTR_MODULE | 7,898,783 | 0.5% | 88.8% | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 7,732,741 | 0.5% | 89.3% | 1.2% |
| CALL_TYPE_1 | 7,709,151 | 0.5% | 89.7% |  |
| CALL_BUILTIN_CLASS | 7,134,022 | 0.4% | 90.2% |  |
| FOR_ITER_TUPLE | 6,942,340 | 0.4% | 90.6% |  |
| POP_JUMP_IF_NONE | 6,571,257 | 0.4% | 91.0% |  |
| POP_JUMP_IF_NOT_NONE | 6,146,998 | 0.4% | 91.4% |  |
| FOR_ITER | 6,080,568 | 0.4% | 91.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 6,023,406 | 0.4% | 92.2% | 3.0% |
| CALL_LEN | 5,578,977 | 0.4% | 92.5% |  |
| COMPARE_OP_STR | 5,555,692 | 0.4% | 92.9% | 0.0% |
| BINARY_OP_ADD_INT | 5,110,114 | 0.3% | 93.2% | 0.0% |
| CALL_ISINSTANCE | 4,499,186 | 0.3% | 93.5% |  |
| STORE_SUBSCR_DICT | 4,481,056 | 0.3% | 93.8% |  |
| STORE_FAST_STORE_FAST | 4,424,416 | 0.3% | 94.1% |  |
| MAKE_CELL | 4,182,403 | 0.3% | 94.3% |  |
| TO_BOOL_NONE | 4,178,922 | 0.3% | 94.6% | 0.2% |
| COPY_FREE_VARS | 3,870,074 | 0.2% | 94.8% |  |
| JUMP_FORWARD | 3,657,451 | 0.2% | 95.1% |  |
| BINARY_OP | 3,644,415 | 0.2% | 95.3% |  |
| CALL_KW | 3,503,102 | 0.2% | 95.5% |  |
| FOR_ITER_LIST | 3,447,530 | 0.2% | 95.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,301,444 | 0.2% | 95.9% |  |
| LOAD_ATTR_PROPERTY | 2,729,880 | 0.2% | 96.1% | 0.0% |
| CALL_PY_WITH_DEFAULTS | 2,427,811 | 0.2% | 96.3% | 0.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,259,927 | 0.1% | 96.4% | 0.1% |
| LOAD_FAST_AND_CLEAR | 2,171,739 | 0.1% | 96.5% |  |
| BEFORE_WITH | 2,150,077 | 0.1% | 96.7% |  |
| BINARY_OP_SUBTRACT_INT | 1,949,101 | 0.1% | 96.8% |  |
| CALL_BUILTIN_FAST | 1,944,733 | 0.1% | 96.9% | 0.0% |
| COMPARE_OP_FLOAT | 1,721,305 | 0.1% | 97.0% | 0.1% |
| TO_BOOL_INT | 1,720,109 | 0.1% | 97.1% | 0.0% |
| CALL_BUILTIN_O | 1,587,071 | 0.1% | 97.2% | 0.1% |
| EXTENDED_ARG | 1,532,172 | 0.1% | 97.3% |  |
| TO_BOOL_LIST | 1,521,720 | 0.1% | 97.4% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,489,398 | 0.1% | 97.5% |  |
| YIELD_VALUE | 1,488,721 | 0.1% | 97.6% |  |
| COMPARE_OP | 1,461,692 | 0.1% | 97.7% |  |
| BINARY_SUBSCR | 1,437,730 | 0.1% | 97.8% |  |
| STORE_ATTR_WITH_HINT | 1,418,839 | 0.1% | 97.9% | 0.3% |
| DELETE_SUBSCR | 1,400,909 | 0.1% | 98.0% |  |
| SET_FUNCTION_ATTRIBUTE | 1,349,515 | 0.1% | 98.1% |  |
| MAKE_FUNCTION | 1,318,795 | 0.1% | 98.1% |  |
| UNPACK_SEQUENCE_TUPLE | 1,243,196 | 0.1% | 98.2% |  |
| BINARY_OP_ADD_FLOAT | 1,168,412 | 0.1% | 98.3% | 0.1% |
| BUILD_CONST_KEY_MAP | 1,159,502 | 0.1% | 98.4% |  |
| STORE_ATTR | 1,048,334 | 0.1% | 98.4% |  |
| BINARY_SUBSCR_LIST_INT | 932,785 | 0.1% | 98.5% | 0.1% |
| RETURN_GENERATOR | 914,775 | 0.1% | 98.6% |  |
| PUSH_EXC_INFO | 866,643 | 0.1% | 98.6% |  |
| POP_EXCEPT | 866,636 | 0.1% | 98.7% |  |
| TO_BOOL_ALWAYS_TRUE | 831,072 | 0.1% | 98.7% | 0.9% |
| STORE_FAST_LOAD_FAST | 824,234 | 0.1% | 98.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 815,805 | 0.1% | 98.8% | 0.3% |
| STORE_DEREF | 806,044 | 0.1% | 98.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 774,147 | 0.0% | 98.9% |  |
| CHECK_EXC_MATCH | 733,394 | 0.0% | 99.0% |  |
| BINARY_SLICE | 724,773 | 0.0% | 99.0% |  |
| MAP_ADD | 688,172 | 0.0% | 99.1% |  |
| CALL_LIST_APPEND | 660,530 | 0.0% | 99.1% |  |
| BINARY_OP_MULTIPLY_INT | 652,619 | 0.0% | 99.1% |  |
| LOAD_SUPER_ATTR_METHOD | 640,257 | 0.0% | 99.2% |  |
| BUILD_SET | 602,773 | 0.0% | 99.2% |  |
| SEND_GEN | 594,366 | 0.0% | 99.3% | 0.0% |
| BINARY_SUBSCR_GETITEM | 586,589 | 0.0% | 99.3% | 0.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 585,451 | 0.0% | 99.3% |  |
| TO_BOOL_STR | 565,075 | 0.0% | 99.4% | 0.3% |
| STORE_SUBSCR | 542,259 | 0.0% | 99.4% |  |
| LIST_APPEND | 519,865 | 0.0% | 99.4% |  |
| END_SEND | 519,830 | 0.0% | 99.5% |  |
| FORMAT_SIMPLE | 518,852 | 0.0% | 99.5% |  |
| GET_AWAITABLE | 518,720 | 0.0% | 99.5% |  |
| SEND | 515,286 | 0.0% | 99.6% |  |
| BUILD_STRING | 466,948 | 0.0% | 99.6% |  |
| LOAD_ATTR_CLASS | 463,158 | 0.0% | 99.6% | 0.5% |
| FOR_ITER_RANGE | 455,923 | 0.0% | 99.6% |  |
| CALL_TUPLE_1 | 363,402 | 0.0% | 99.7% |  |
| RERAISE | 359,400 | 0.0% | 99.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 340,292 | 0.0% | 99.7% | 0.4% |
| DELETE_FAST | 337,177 | 0.0% | 99.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 297,242 | 0.0% | 99.8% | 0.3% |
| EXIT_INIT_CHECK | 296,162 | 0.0% | 99.8% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 263,960 | 0.0% | 99.8% |  |
| BINARY_OP_ADD_UNICODE | 261,438 | 0.0% | 99.8% | 0.1% |
| CALL_STR_1 | 259,942 | 0.0% | 99.8% |  |
| LOAD_FAST_CHECK | 249,418 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_STR_INT | 242,860 | 0.0% | 99.9% | 0.2% |
| BINARY_OP_MULTIPLY_FLOAT | 206,645 | 0.0% | 99.9% | 1.1% |
| IMPORT_FROM | 202,666 | 0.0% | 99.9% |  |
| IMPORT_NAME | 201,914 | 0.0% | 99.9% |  |
| WITH_EXCEPT_START | 178,435 | 0.0% | 99.9% |  |
| SET_ADD | 177,760 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 177,569 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 167,080 | 0.0% | 99.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 131,047 | 0.0% | 99.9% | 30.9% |
| BINARY_OP_INPLACE_ADD_UNICODE | 120,880 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 109,202 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 98,023 | 0.0% | 100.0% | 0.4% |
| SET_UPDATE | 88,020 | 0.0% | 100.0% |  |
| UNPACK_EX | 88,000 | 0.0% | 100.0% |  |
| UNARY_INVERT | 84,252 | 0.0% | 100.0% |  |
| BUILD_SLICE | 83,706 | 0.0% | 100.0% |  |
| DICT_UPDATE | 42,784 | 0.0% | 100.0% |  |
| STORE_SLICE | 41,060 | 0.0% | 100.0% |  |
| RESUME | 26,196 | 0.0% | 100.0% | 22.2% |
| STORE_NAME | 14,380 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 10,756 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 8,904 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 8,768 | 0.0% | 100.0% |  |
| DELETE_ATTR | 8,554 | 0.0% | 100.0% |  |
| LOAD_NAME | 6,720 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 6,241 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,012 | 0.0% | 100.0% | 89.9% |
| LOAD_SUPER_ATTR_ATTR | 3,956 | 0.0% | 100.0% |  |
| END_FOR | 3,708 | 0.0% | 100.0% |  |
| UNARY_NOT | 2,700 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,840 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 1,760 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 1,220 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 940 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 892 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 460 | 0.0% | 100.0% |  |
| SETUP_ANNOTATIONS | 440 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 80 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 50,452,810 | 3.2% | 3.2% |
| STORE_FAST LOAD_FAST | 45,076,830 | 2.8% | 6.0% |
| RESUME_CHECK LOAD_FAST | 44,766,161 | 2.8% | 8.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 34,314,940 | 2.2% | 11.0% |
| LOAD_FAST LOAD_ATTR_SLOT | 30,462,724 | 1.9% | 12.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 28,733,055 | 1.8% | 14.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 22,783,683 | 1.4% | 16.2% |
| CACHE RESUME_CHECK | 22,060,570 | 1.4% | 17.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 19,696,668 | 1.2% | 18.8% |
| LOAD_CONST LOAD_FAST | 18,502,997 | 1.2% | 20.0% |
| RETURN_VALUE INTERPRETER_EXIT | 17,505,097 | 1.1% | 21.1% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 17,405,079 | 1.1% | 22.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 15,244,527 | 1.0% | 23.1% |
| POP_TOP LOAD_FAST | 15,071,601 | 0.9% | 24.1% |
| LOAD_FAST LOAD_ATTR | 14,474,336 | 0.9% | 25.0% |
| RETURN_VALUE STORE_FAST | 13,948,855 | 0.9% | 25.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 13,665,413 | 0.9% | 26.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 13,595,304 | 0.9% | 27.6% |
| LOAD_FAST LOAD_CONST | 12,631,401 | 0.8% | 28.4% |
| RETURN_CONST POP_TOP | 12,388,091 | 0.8% | 29.2% |
| PUSH_NULL LOAD_FAST | 12,221,458 | 0.8% | 29.9% |
| LOAD_FAST RETURN_VALUE | 11,923,755 | 0.8% | 30.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 10,866,377 | 0.7% | 31.4% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 10,463,740 | 0.7% | 32.0% |
| LOAD_FAST CALL | 10,167,644 | 0.6% | 32.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 9,640,760 | 0.6% | 33.3% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 9,268,846 | 0.6% | 33.9% |
| DICT_MERGE CALL_FUNCTION_EX | 8,856,100 | 0.6% | 34.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 8,727,358 | 0.5% | 35.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 8,625,287 | 0.5% | 35.5% |
| BUILD_MAP LOAD_FAST | 8,624,456 | 0.5% | 36.1% |
| BUILD_LIST LOAD_FAST | 8,425,801 | 0.5% | 36.6% |
| LOAD_FAST DICT_MERGE | 8,249,841 | 0.5% | 37.1% |
| NOP LOAD_FAST | 8,232,911 | 0.5% | 37.6% |
| LOAD_FAST STORE_ATTR_SLOT | 8,172,843 | 0.5% | 38.1% |
| LOAD_FAST PUSH_NULL | 8,063,369 | 0.5% | 38.6% |
| LIST_EXTEND CALL_INTRINSIC_1 | 7,974,512 | 0.5% | 39.2% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 7,662,668 | 0.5% | 39.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 7,639,925 | 0.5% | 40.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 7,635,470 | 0.5% | 40.6% |
| LOAD_FAST CALL_TYPE_1 | 7,619,311 | 0.5% | 41.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 7,541,190 | 0.5% | 41.6% |
| STORE_FAST NOP | 7,442,290 | 0.5% | 42.0% |
| RETURN_VALUE RETURN_VALUE | 7,382,106 | 0.5% | 42.5% |
| IS_OP POP_JUMP_IF_FALSE | 7,341,720 | 0.5% | 42.9% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 7,338,445 | 0.5% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 7,323,340 | 0.5% | 43.9% |
| LOAD_FAST BUILD_LIST | 7,044,890 | 0.4% | 44.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 7,035,160 | 0.4% | 44.8% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 6,988,292 | 0.4% | 45.2% |
| LOAD_FAST LIST_EXTEND | 6,700,850 | 0.4% | 45.6% |
| LOAD_CONST LOAD_CONST | 6,560,792 | 0.4% | 46.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 6,547,567 | 0.4% | 46.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 6,545,693 | 0.4% | 46.9% |
| RETURN_CONST INTERPRETER_EXIT | 6,391,050 | 0.4% | 47.3% |
| BINARY_SUBSCR_DICT STORE_FAST | 6,350,316 | 0.4% | 47.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,296,473 | 0.4% | 48.1% |
| LOAD_ATTR_MODULE PUSH_NULL | 6,262,426 | 0.4% | 48.5% |
| POP_TOP RETURN_CONST | 6,089,137 | 0.4% | 48.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 5,952,134 | 0.4% | 49.2% |
| TO_BOOL POP_JUMP_IF_FALSE | 5,792,734 | 0.4% | 49.6% |
| CALL_INTRINSIC_1 BUILD_MAP | 5,774,104 | 0.4% | 49.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 5,745,673 | 0.4% | 50.3% |
| CALL_FUNCTION_EX RESUME_CHECK | 5,721,930 | 0.4% | 50.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 5,719,666 | 0.4% | 51.0% |
| FOR_ITER_TUPLE STORE_FAST | 5,693,474 | 0.4% | 51.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 5,548,859 | 0.3% | 51.7% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_NO_DICT | 5,452,585 | 0.3% | 52.1% |
| POP_TOP RETURN_VALUE | 5,423,720 | 0.3% | 52.4% |
| GET_ITER FOR_ITER_TUPLE | 5,418,931 | 0.3% | 52.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 5,407,084 | 0.3% | 53.1% |
| RETURN_VALUE TO_BOOL_BOOL | 5,358,368 | 0.3% | 53.4% |
| RESUME_CHECK NOP | 5,280,093 | 0.3% | 53.8% |
| CALL POP_TOP | 5,244,345 | 0.3% | 54.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,209,463 | 0.3% | 54.4% |
| POP_TOP ENTER_EXECUTOR | 5,157,427 | 0.3% | 54.8% |
| LOAD_CONST STORE_FAST | 5,149,336 | 0.3% | 55.1% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 5,087,961 | 0.3% | 55.4% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 5,087,832 | 0.3% | 55.7% |
| CALL RETURN_VALUE | 5,070,091 | 0.3% | 56.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 5,041,205 | 0.3% | 56.4% |
| NOP LOAD_FAST_LOAD_FAST | 4,993,595 | 0.3% | 56.7% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 4,972,833 | 0.3% | 57.0% |
| LOAD_FAST SWAP | 4,952,273 | 0.3% | 57.3% |
| STORE_ATTR_SLOT LOAD_CONST | 4,885,696 | 0.3% | 57.6% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_DICT | 4,760,781 | 0.3% | 57.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_BUILTIN | 4,682,014 | 0.3% | 58.2% |
| LOAD_FAST POP_JUMP_IF_NONE | 4,655,937 | 0.3% | 58.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 4,640,836 | 0.3% | 58.8% |
| LOAD_FAST_LOAD_FAST IS_OP | 4,617,257 | 0.3% | 59.1% |
| GET_ITER FOR_ITER | 4,606,259 | 0.3% | 59.4% |
| LOAD_CONST COMPARE_OP_INT | 4,595,143 | 0.3% | 59.7% |
| CALL STORE_FAST | 4,577,843 | 0.3% | 59.9% |
| SWAP POP_TOP | 4,542,711 | 0.3% | 60.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 4,538,100 | 0.3% | 60.5% |
| LOAD_ATTR GET_ITER | 4,537,539 | 0.3% | 60.8% |
| CALL_TYPE_1 CALL_PY_EXACT_ARGS | 4,536,291 | 0.3% | 61.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 4,306,989 | 0.3% | 61.4% |
| LOAD_FAST TO_BOOL | 4,250,895 | 0.3% | 61.6% |
| LOAD_FAST COPY | 4,207,752 | 0.3% | 61.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 463,397 | 63.9% |
| LOAD_FAST | 217,616 | 30.0% |
| BINARY_OP_ADD_INT | 43,380 | 6.0% |
| LOAD_ATTR_INSTANCE_VALUE | 300 | 0.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 112,130 | 15.5% |
| CALL_BUILTIN_CLASS | 89,178 | 12.3% |
| CALL_METHOD_DESCRIPTOR_O | 87,960 | 12.1% |
| CALL_PY_WITH_DEFAULTS | 87,960 | 12.1% |
| STORE_FAST | 72,068 | 9.9% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,760 | 99.3% |
| LOAD_FAST | 160 | 0.4% |
| BINARY_OP_ADD_INT | 140 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,760 | 99.3% |
| LOAD_CONST | 160 | 0.4% |
| ENTER_EXECUTOR | 140 | 0.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 22,060,570 | 86.8% |
| COPY_FREE_VARS | 2,335,723 | 9.2% |
| POP_TOP | 581,422 | 2.3% |
| MAKE_CELL | 267,182 | 1.1% |
| RETURN_GENERATOR | 129,802 | 0.5% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,030 | 93.3% |
| LOAD_ATTR_WITH_HINT | 466 | 4.3% |
| CALL | 160 | 1.5% |
| CALL_KW | 80 | 0.7% |
| LOAD_ATTR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 10,756 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,587,677 | 73.8% |
| LOAD_GLOBAL_MODULE | 186,281 | 8.7% |
| LOAD_ATTR_WITH_HINT | 176,380 | 8.2% |
| LOAD_FAST | 176,240 | 8.2% |
| CALL | 11,340 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,145,062 | 99.8% |
| STORE_FAST | 5,015 | 0.2% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 108,760 | 90.0% |
| LOAD_FAST_LOAD_FAST | 10,000 | 8.3% |
| LOAD_CONST | 1,720 | 1.4% |
| BINARY_SUBSCR_STR_INT | 220 | 0.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 118,240 | 97.8% |
| LOAD_GLOBAL_MODULE | 1,720 | 1.4% |
| LOAD_FAST | 360 | 0.3% |
| JUMP_BACKWARD | 320 | 0.3% |
| STORE_FAST | 220 | 0.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 857,383 | 59.6% |
| COPY | 353,994 | 24.6% |
| LOAD_CONST | 218,121 | 15.2% |
| BINARY_SUBSCR | 4,832 | 0.3% |
| BUILD_SLICE | 1,200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 344,260 | 23.9% |
| LOAD_CONST | 266,230 | 18.5% |
| LOAD_FAST | 176,989 | 12.3% |
| STORE_FAST | 176,610 | 12.3% |
| LOAD_ATTR_METHOD_NO_DICT | 162,727 | 11.3% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 648,257 | 88.4% |
| LOAD_ATTR_MODULE | 79,061 | 10.8% |
| BUILD_TUPLE | 4,886 | 0.7% |
| LOAD_GLOBAL | 729 | 0.1% |
| LOAD_GLOBAL_MODULE | 364 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 733,394 | 100.0% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 892 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 648 | 72.6% |
| JUMP_BACKWARD | 244 | 27.4% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 964,025 | 68.8% |
| LOAD_FAST_LOAD_FAST | 265,518 | 19.0% |
| LOAD_ATTR_SLOT | 88,040 | 6.3% |
| BUILD_SLICE | 82,506 | 5.9% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 434,272 | 33.1% |
| PUSH_EXC_INFO | 352,000 | 26.8% |
| RETURN_CONST | 258,278 | 19.7% |
| LOAD_FAST_LOAD_FAST | 88,586 | 6.7% |
| LOAD_CONST | 88,507 | 6.7% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,708 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,458 | 39.3% |
| LOAD_CONST | 880 | 23.7% |
| STORE_FAST | 750 | 20.2% |
| SWAP | 300 | 8.1% |
| RETURN_CONST | 180 | 4.9% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 270,203 | 52.0% |
| SEND | 191,071 | 36.8% |
| RETURN_CONST | 58,152 | 11.2% |
| JUMP_BACKWARD | 244 | 0.0% |
| SEND_GEN | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 303,046 | 58.3% |
| POP_TOP | 117,982 | 22.7% |
| UNPACK_SEQUENCE_TUPLE | 88,246 | 17.0% |
| SWAP | 10,030 | 1.9% |
| LOAD_DEREF | 168 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 296,162 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 296,162 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 374,164 | 72.1% |
| LOAD_FAST | 131,904 | 25.4% |
| CONVERT_VALUE | 8,904 | 1.7% |
| LOAD_GLOBAL_MODULE | 3,340 | 0.6% |
| CALL_LEN | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 421,856 | 81.3% |
| LOAD_CONST | 54,596 | 10.5% |
| LOAD_FAST | 42,400 | 8.2% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,537,539 | 32.5% |
| LOAD_FAST | 3,409,234 | 24.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,530,792 | 18.1% |
| LOAD_ATTR_SLOT | 1,450,270 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 912,795 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 5,418,931 | 38.8% |
| FOR_ITER | 4,606,259 | 33.0% |
| FOR_ITER_LIST | 2,080,700 | 14.9% |
| LOAD_FAST_AND_CLEAR | 1,387,871 | 9.9% |
| CALL_PY_EXACT_ARGS | 256,548 | 1.8% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,740 | 98.9% |
| LOAD_ATTR | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,760 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 17,505,097 | 69.6% |
| RETURN_CONST | 6,391,050 | 25.4% |
| YIELD_VALUE | 1,127,418 | 4.5% |
| RETURN_GENERATOR | 129,970 | 0.5% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 540 | 57.4% |
| POP_TOP | 300 | 31.9% |
| POP_JUMP_IF_FALSE | 40 | 4.3% |
| STORE_SUBSCR | 20 | 2.1% |
| JUMP_BACKWARD | 20 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 940 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,318,795 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,135,002 | 86.1% |
| STORE_DEREF | 88,007 | 6.7% |
| CALL | 41,680 | 3.2% |
| LOAD_GLOBAL_BUILTIN | 41,378 | 3.1% |
| LOAD_FAST | 6,606 | 0.5% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,442,290 | 43.0% |
| RESUME_CHECK | 5,280,093 | 30.5% |
| POP_JUMP_IF_FALSE | 1,497,556 | 8.6% |
| STORE_ATTR_INSTANCE_VALUE | 600,717 | 3.5% |
| POP_JUMP_IF_TRUE | 540,400 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,232,911 | 47.5% |
| LOAD_FAST_LOAD_FAST | 4,993,595 | 28.8% |
| LOAD_GLOBAL_MODULE | 2,015,077 | 11.6% |
| LOAD_CONST | 503,445 | 2.9% |
| LOAD_GLOBAL_BUILTIN | 480,164 | 2.8% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 522,080 | 60.2% |
| COPY | 179,237 | 20.7% |
| STORE_FAST | 147,234 | 17.0% |
| STORE_SUBSCR_DICT | 9,399 | 1.1% |
| SWAP | 6,258 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 438,528 | 50.6% |
| RERAISE | 179,237 | 20.7% |
| EXTENDED_ARG | 129,683 | 15.0% |
| DELETE_FAST | 40,995 | 4.7% |
| LOAD_CONST | 40,660 | 4.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 12,388,091 | 28.9% |
| CALL_METHOD_DESCRIPTOR_O | 7,662,668 | 17.9% |
| CALL | 5,244,345 | 12.2% |
| SWAP | 4,542,711 | 10.6% |
| CALL_FUNCTION_EX | 2,973,936 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,071,601 | 35.1% |
| RETURN_CONST | 6,089,137 | 14.2% |
| RETURN_VALUE | 5,423,720 | 12.6% |
| ENTER_EXECUTOR | 5,157,427 | 12.0% |
| LOAD_FAST_LOAD_FAST | 2,439,982 | 5.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 352,000 | 40.6% |
| BINARY_SUBSCR_DICT | 188,617 | 21.8% |
| CALL | 100,385 | 11.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 88,104 | 10.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 79,279 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 606,211 | 69.9% |
| WITH_EXCEPT_START | 178,435 | 20.6% |
| LOAD_GLOBAL_MODULE | 80,180 | 9.3% |
| LOAD_GLOBAL | 1,699 | 0.2% |
| DELETE_FAST | 78 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,063,369 | 41.1% |
| LOAD_ATTR_MODULE | 6,262,426 | 31.9% |
| LOAD_ATTR | 4,043,104 | 20.6% |
| LOAD_DEREF | 933,038 | 4.8% |
| RETURN_VALUE | 227,751 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,221,458 | 62.3% |
| LOAD_FAST_LOAD_FAST | 2,474,681 | 12.6% |
| CALL | 2,471,657 | 12.6% |
| LOAD_CONST | 1,193,890 | 6.1% |
| CALL_BUILTIN_CLASS | 437,656 | 2.2% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 297,658 | 32.5% |
| CALL_KW | 131,610 | 14.4% |
| CACHE | 129,802 | 14.2% |
| CALL_PY_EXACT_ARGS | 104,153 | 11.4% |
| CALL_PY_WITH_DEFAULTS | 85,518 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 296,465 | 32.4% |
| CALL_TUPLE_1 | 176,440 | 19.3% |
| INTERPRETER_EXIT | 129,970 | 14.2% |
| CALL_BUILTIN_O | 118,396 | 12.9% |
| CALL | 83,446 | 9.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,923,755 | 21.9% |
| RETURN_VALUE | 7,382,106 | 13.6% |
| POP_TOP | 5,423,720 | 10.0% |
| CALL | 5,070,091 | 9.3% |
| LOAD_ATTR_INSTANCE_VALUE | 3,878,317 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 17,505,097 | 32.2% |
| STORE_FAST | 13,948,855 | 25.6% |
| RETURN_VALUE | 7,382,106 | 13.6% |
| TO_BOOL_BOOL | 5,358,368 | 9.8% |
| LOAD_FAST | 1,513,138 | 2.8% |


</details>

### SETUP_ANNOTATIONS

<details>
<summary> Successors and predecessors for SETUP_ANNOTATIONS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 300 | 68.2% |
| RESUME | 140 | 31.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 440 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 353,994 | 65.3% |
| LOAD_FAST | 90,807 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 88,120 | 16.3% |
| LOAD_CONST | 4,880 | 0.9% |
| STORE_SUBSCR | 1,936 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 267,108 | 49.3% |
| LOAD_CONST | 89,600 | 16.5% |
| RETURN_CONST | 89,395 | 16.5% |
| LOAD_GLOBAL_MODULE | 88,080 | 16.2% |
| STORE_SUBSCR_DICT | 3,460 | 0.6% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,250,895 | 49.6% |
| LOAD_ATTR_SLOT | 1,492,028 | 17.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,066,453 | 12.4% |
| RETURN_VALUE | 964,989 | 11.3% |
| COPY | 399,183 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,792,734 | 67.6% |
| POP_JUMP_IF_TRUE | 2,634,801 | 30.8% |
| EXTENDED_ARG | 100,450 | 1.2% |
| TO_BOOL | 21,315 | 0.2% |
| TO_BOOL_BOOL | 12,071 | 0.1% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 42,009 | 49.9% |
| BINARY_OP | 41,723 | 49.5% |
| LOAD_FAST | 480 | 0.6% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 84,252 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 1,180 | 96.7% |
| CALL | 20 | 1.6% |
| LOAD_FAST | 20 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 98.4% |
| CALL_BUILTIN_CLASS | 20 | 1.6% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,060 | 39.3% |
| TO_BOOL_INT | 960 | 35.6% |
| TO_BOOL_LIST | 620 | 23.0% |
| TO_BOOL | 60 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 980 | 36.3% |
| STORE_DEREF | 880 | 32.6% |
| CALL_PY_EXACT_ARGS | 620 | 23.0% |
| RETURN_VALUE | 140 | 5.2% |
| STORE_FAST | 80 | 3.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 178,435 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 177,300 | 99.4% |
| TO_BOOL_BOOL | 960 | 0.5% |
| TO_BOOL | 175 | 0.1% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 714,697 | 19.6% |
| LOAD_FAST | 588,782 | 16.2% |
| LOAD_GLOBAL_MODULE | 413,085 | 11.3% |
| LOAD_ATTR_WITH_HINT | 272,864 | 7.5% |
| LOAD_CONST | 230,190 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,319,172 | 36.2% |
| TO_BOOL_INT | 571,864 | 15.7% |
| LOAD_CONST | 260,674 | 7.2% |
| COPY | 209,781 | 5.8% |
| BINARY_OP_ADD_FLOAT | 202,697 | 5.6% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,159,502 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 433,681 | 37.4% |
| RETURN_VALUE | 188,942 | 16.3% |
| CALL_LIST_APPEND | 176,880 | 15.3% |
| LOAD_FAST | 130,414 | 11.2% |
| CALL_PY_EXACT_ARGS | 89,958 | 7.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,044,890 | 64.0% |
| LOAD_ATTR_SLOT | 1,353,515 | 12.3% |
| RESUME_CHECK | 536,524 | 4.9% |
| STORE_FAST | 468,454 | 4.3% |
| SWAP | 344,407 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,425,801 | 76.6% |
| STORE_FAST | 1,271,438 | 11.6% |
| BUILD_TUPLE | 512,705 | 4.7% |
| SWAP | 384,099 | 3.5% |
| LOAD_FAST_LOAD_FAST | 184,000 | 1.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 5,774,104 | 39.6% |
| STORE_FAST | 2,586,004 | 17.7% |
| LOAD_FAST | 1,775,243 | 12.2% |
| SWAP | 785,144 | 5.4% |
| BUILD_TUPLE | 661,388 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,624,456 | 59.1% |
| STORE_FAST | 4,078,505 | 27.9% |
| SWAP | 785,144 | 5.4% |
| LOAD_GLOBAL_MODULE | 433,440 | 3.0% |
| BUILD_LIST | 248,000 | 1.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 258,320 | 42.9% |
| LOAD_GLOBAL_MODULE | 176,293 | 29.2% |
| LOAD_ATTR | 88,080 | 14.6% |
| LOAD_CONST | 80,020 | 13.3% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 258,320 | 42.9% |
| CONTAINS_OP | 176,413 | 29.3% |
| LOAD_CONST | 88,020 | 14.6% |
| BINARY_OP | 80,020 | 13.3% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,680 | 97.6% |
| LOAD_CONST | 2,026 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 82,506 | 98.6% |
| BINARY_SUBSCR | 1,200 | 1.4% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 421,856 | 90.3% |
| LOAD_CONST | 45,092 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 198,204 | 42.4% |
| BUILD_MAP | 88,000 | 18.8% |
| LOAD_CONST | 88,000 | 18.8% |
| LOAD_FAST | 42,260 | 9.1% |
| LOAD_FAST_LOAD_FAST | 40,920 | 8.8% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,804,525 | 30.4% |
| LOAD_FAST_LOAD_FAST | 2,407,119 | 26.1% |
| CALL | 1,424,027 | 15.5% |
| BUILD_LIST | 512,705 | 5.6% |
| LOAD_GLOBAL_BUILTIN | 460,279 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,721,019 | 29.5% |
| CALL_METHOD_DESCRIPTOR_O | 1,551,843 | 16.8% |
| LOAD_CONST | 1,485,621 | 16.1% |
| BUILD_MAP | 661,388 | 7.2% |
| CONTAINS_OP | 554,583 | 6.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,167,644 | 37.4% |
| LOAD_GLOBAL_MODULE | 3,534,396 | 13.0% |
| LOAD_CONST | 2,591,500 | 9.5% |
| PUSH_NULL | 2,471,657 | 9.1% |
| LOAD_FAST_LOAD_FAST | 2,274,933 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,244,345 | 19.3% |
| RETURN_VALUE | 5,070,091 | 18.6% |
| STORE_FAST | 4,577,843 | 16.8% |
| RESUME_CHECK | 3,981,872 | 14.6% |
| BUILD_TUPLE | 1,424,027 | 5.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 8,856,100 | 75.4% |
| CALL_INTRINSIC_1 | 1,615,611 | 13.8% |
| LOAD_FAST | 979,120 | 8.3% |
| ENTER_EXECUTOR | 100,066 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 88,040 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,721,930 | 48.7% |
| POP_TOP | 2,973,936 | 25.3% |
| RETURN_VALUE | 1,157,593 | 9.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 615,920 | 5.2% |
| UNPACK_SEQUENCE_TUPLE | 431,960 | 3.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 7,974,512 | 100.0% |
| RERAISE | 1,324 | 0.0% |
| RAISE_VARARGS | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 5,774,104 | 72.4% |
| CALL_FUNCTION_EX | 1,615,611 | 20.3% |
| LOAD_CONST | 584,797 | 7.3% |
| RERAISE | 1,326 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,900,073 | 82.8% |
| ENTER_EXECUTOR | 603,029 | 17.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,543,336 | 72.6% |
| MAKE_CELL | 380,985 | 10.9% |
| STORE_FAST | 157,850 | 4.5% |
| RETURN_GENERATOR | 131,610 | 3.8% |
| RETURN_VALUE | 100,441 | 2.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 631,289 | 43.2% |
| LOAD_FAST | 184,694 | 12.6% |
| LOAD_ATTR | 179,936 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 129,494 | 8.9% |
| BINARY_OP | 97,500 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,444,674 | 98.8% |
| COMPARE_OP | 5,794 | 0.4% |
| POP_JUMP_IF_TRUE | 4,947 | 0.3% |
| COMPARE_OP_INT | 3,952 | 0.3% |
| COMPARE_OP_STR | 1,585 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,067,764 | 30.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,675,823 | 26.4% |
| LOAD_ATTR_WITH_HINT | 1,488,989 | 14.7% |
| LOAD_GLOBAL_MODULE | 634,122 | 6.3% |
| BUILD_TUPLE | 554,583 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,541,190 | 74.4% |
| RETURN_VALUE | 1,146,118 | 11.3% |
| POP_JUMP_IF_TRUE | 743,330 | 7.3% |
| COPY | 522,420 | 5.2% |
| SWAP | 176,340 | 1.7% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,244 | 58.9% |
| LOAD_FAST | 1,680 | 18.9% |
| BINARY_SLICE | 1,600 | 18.0% |
| LOAD_GLOBAL_MODULE | 280 | 3.1% |
| LOAD_ATTR | 100 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 8,904 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,207,752 | 40.6% |
| COPY | 1,381,292 | 13.3% |
| CALL_BUILTIN_FAST | 683,208 | 6.6% |
| LOAD_ATTR_SLOT | 608,672 | 5.9% |
| CONTAINS_OP | 522,420 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,920,754 | 18.5% |
| LOAD_ATTR_WITH_HINT | 1,407,840 | 13.6% |
| COPY | 1,381,292 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,365,133 | 13.2% |
| BINARY_SUBSCR_DICT | 1,027,178 | 9.9% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 2,335,723 | 60.4% |
| CALL_PY_EXACT_ARGS | 761,840 | 19.7% |
| CALL | 413,027 | 10.7% |
| BINARY_SUBSCR_GETITEM | 263,960 | 6.8% |
| ENTER_EXECUTOR | 87,200 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,568,963 | 92.2% |
| RETURN_GENERATOR | 297,658 | 7.7% |
| MAKE_CELL | 1,766 | 0.0% |
| RESUME | 1,687 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,234 | 96.3% |
| LOAD_GLOBAL_MODULE | 280 | 3.3% |
| LOAD_GLOBAL | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,912 | 45.7% |
| NOP | 1,736 | 20.3% |
| PUSH_EXC_INFO | 1,690 | 19.8% |
| RETURN_CONST | 1,056 | 12.3% |
| LOAD_GLOBAL_MODULE | 120 | 1.4% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 88,340 | 26.2% |
| CALL | 82,240 | 24.4% |
| STORE_FAST | 43,289 | 12.8% |
| NOP | 41,241 | 12.2% |
| POP_EXCEPT | 40,995 | 12.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 90,631 | 26.9% |
| RETURN_VALUE | 82,240 | 24.4% |
| RETURN_CONST | 82,236 | 24.4% |
| LOAD_FAST | 41,001 | 12.2% |
| ENTER_EXECUTOR | 39,334 | 11.7% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,249,841 | 93.2% |
| RETURN_VALUE | 433,600 | 4.9% |
| LOAD_ATTR_INSTANCE_VALUE | 88,859 | 1.0% |
| LOAD_DEREF | 40,967 | 0.5% |
| LOAD_GLOBAL_MODULE | 40,900 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 8,856,100 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40,900 | 95.6% |
| BUILD_MAP | 732 | 1.7% |
| RETURN_VALUE | 652 | 1.5% |
| MAP_ADD | 240 | 0.6% |
| BUILD_CONST_KEY_MAP | 160 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,652 | 97.4% |
| STORE_FAST | 732 | 1.7% |
| LOAD_DEREF | 160 | 0.4% |
| RETURN_VALUE | 80 | 0.2% |
| BUILD_MAP | 80 | 0.2% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,157,427 | 45.6% |
| POP_JUMP_IF_FALSE | 1,469,501 | 13.0% |
| STORE_SUBSCR_DICT | 937,164 | 8.3% |
| MAP_ADD | 673,348 | 6.0% |
| POP_JUMP_IF_TRUE | 625,934 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,571,200 | 13.9% |
| RESUME_CHECK | 1,447,394 | 12.8% |
| FOR_ITER_LIST | 1,269,999 | 11.2% |
| FOR_ITER_TUPLE | 1,193,113 | 10.5% |
| LOAD_FAST | 962,872 | 8.5% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_WITH_HINT | 431,980 | 28.2% |
| COMPARE_OP_INT | 352,566 | 23.0% |
| IS_OP | 176,160 | 11.5% |
| POP_EXCEPT | 129,683 | 8.5% |
| POP_JUMP_IF_FALSE | 102,132 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 663,119 | 43.3% |
| JUMP_FORWARD | 441,280 | 28.8% |
| ENTER_EXECUTOR | 314,858 | 20.5% |
| POP_JUMP_IF_NOT_NONE | 88,020 | 5.7% |
| LOAD_ATTR | 6,880 | 0.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,606,259 | 75.8% |
| SWAP | 1,206,221 | 19.8% |
| LOAD_FAST | 213,086 | 3.5% |
| JUMP_BACKWARD | 34,878 | 0.6% |
| FOR_ITER | 18,264 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,515,703 | 24.9% |
| LOAD_FAST | 1,347,292 | 22.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 822,628 | 13.5% |
| RETURN_CONST | 802,750 | 13.2% |
| STORE_FAST_LOAD_FAST | 644,033 | 10.6% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 296,465 | 57.2% |
| RETURN_VALUE | 180,583 | 34.8% |
| LOAD_FAST | 19,666 | 3.8% |
| BEFORE_ASYNC_WITH | 10,756 | 2.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 10,636 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 518,720 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 200,046 | 98.7% |
| STORE_NAME | 1,740 | 0.9% |
| STORE_FAST | 880 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 198,306 | 97.8% |
| STORE_NAME | 4,200 | 2.1% |
| PUSH_EXC_INFO | 160 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 201,914 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 200,046 | 99.1% |
| STORE_FAST | 1,168 | 0.6% |
| STORE_NAME | 660 | 0.3% |
| PUSH_EXC_INFO | 40 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,617,257 | 49.3% |
| LOAD_GLOBAL_BUILTIN | 2,533,620 | 27.1% |
| LOAD_GLOBAL_MODULE | 1,105,741 | 11.8% |
| LOAD_CONST | 391,244 | 4.2% |
| LOAD_ATTR_INSTANCE_VALUE | 253,592 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,341,720 | 78.4% |
| POP_JUMP_IF_TRUE | 1,175,436 | 12.6% |
| COPY | 359,564 | 3.8% |
| RETURN_VALUE | 307,273 | 3.3% |
| EXTENDED_ARG | 176,160 | 1.9% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 109,321 | 61.6% |
| STORE_SUBSCR_DICT | 12,676 | 7.1% |
| POP_JUMP_IF_TRUE | 11,812 | 6.7% |
| POP_JUMP_IF_FALSE | 8,199 | 4.6% |
| LIST_APPEND | 6,927 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 93,095 | 52.4% |
| FOR_ITER | 34,878 | 19.6% |
| FOR_ITER_LIST | 20,345 | 11.5% |
| FOR_ITER_TUPLE | 8,140 | 4.6% |
| LOAD_FAST | 7,640 | 4.3% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 584,198 | 99.8% |
| RESUME | 1,253 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 319,342 | 54.5% |
| SEND_GEN | 266,109 | 45.5% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,431,465 | 39.1% |
| POP_TOP | 1,066,339 | 29.2% |
| EXTENDED_ARG | 441,280 | 12.1% |
| POP_JUMP_IF_FALSE | 196,039 | 5.4% |
| STORE_SUBSCR_DICT | 96,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,514,624 | 68.8% |
| LOAD_GLOBAL_BUILTIN | 435,390 | 11.9% |
| NOP | 256,554 | 7.0% |
| LOAD_CONST | 213,116 | 5.8% |
| LOAD_GLOBAL_MODULE | 100,434 | 2.7% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 160,340 | 30.8% |
| RETURN_VALUE | 128,980 | 24.8% |
| BINARY_SUBSCR_DICT | 88,120 | 17.0% |
| BINARY_OP_ADD_UNICODE | 87,980 | 16.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 46,880 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 512,938 | 98.7% |
| JUMP_BACKWARD | 6,927 | 1.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,700,850 | 83.2% |
| LOAD_ATTR_SLOT | 1,353,515 | 16.8% |
| BINARY_SLICE | 1,760 | 0.0% |
| LOAD_DEREF | 207 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 7,974,512 | 99.0% |
| STORE_FAST | 81,840 | 1.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,474,336 | 71.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,447,099 | 7.2% |
| LOAD_ATTR_SLOT | 1,355,471 | 6.7% |
| LOAD_GLOBAL_MODULE | 1,183,424 | 5.9% |
| LOAD_DEREF | 913,710 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,537,539 | 22.5% |
| PUSH_NULL | 4,043,104 | 20.0% |
| LOAD_FAST | 3,312,886 | 16.4% |
| LOAD_FAST_LOAD_FAST | 1,958,220 | 9.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,177,478 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,631,401 | 19.1% |
| LOAD_CONST | 6,560,792 | 9.9% |
| POP_JUMP_IF_FALSE | 5,745,673 | 8.7% |
| STORE_ATTR_SLOT | 4,885,696 | 7.4% |
| LOAD_ATTR_SLOT | 2,929,436 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,502,997 | 27.9% |
| LOAD_CONST | 6,560,792 | 9.9% |
| STORE_FAST | 5,149,336 | 7.8% |
| COMPARE_OP_INT | 4,595,143 | 6.9% |
| COMPARE_OP_STR | 3,954,069 | 6.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,124,246 | 12.8% |
| LOAD_GLOBAL_BUILTIN | 1,027,016 | 11.7% |
| POP_TOP | 866,820 | 9.9% |
| POP_JUMP_IF_FALSE | 771,058 | 8.8% |
| LOAD_GLOBAL_MODULE | 743,499 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,057,739 | 12.1% |
| PUSH_NULL | 933,038 | 10.6% |
| CALL_PY_EXACT_ARGS | 919,660 | 10.5% |
| LOAD_ATTR | 913,710 | 10.4% |
| LOAD_DEREF | 711,089 | 8.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 45,076,830 | 14.0% |
| RESUME_CHECK | 44,766,161 | 13.9% |
| POP_JUMP_IF_FALSE | 34,314,940 | 10.7% |
| LOAD_GLOBAL_BUILTIN | 22,783,683 | 7.1% |
| LOAD_CONST | 18,502,997 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 50,452,810 | 15.7% |
| LOAD_ATTR_SLOT | 30,462,724 | 9.5% |
| LOAD_ATTR_WITH_HINT | 17,405,079 | 5.4% |
| LOAD_ATTR | 14,474,336 | 4.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 13,595,304 | 4.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,387,871 | 63.9% |
| LOAD_FAST_AND_CLEAR | 783,868 | 36.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,387,871 | 63.9% |
| LOAD_FAST_AND_CLEAR | 783,868 | 36.1% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 88,020 | 35.3% |
| STORE_ATTR_SLOT | 87,980 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 46,619 | 18.7% |
| POP_TOP | 10,623 | 4.3% |
| LOAD_FAST_CHECK | 5,156 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 177,924 | 71.3% |
| CALL_METHOD_DESCRIPTOR_O | 45,779 | 18.4% |
| POP_JUMP_IF_NOT_NONE | 9,460 | 3.8% |
| LOAD_CONST | 5,664 | 2.3% |
| LOAD_FAST_CHECK | 5,156 | 2.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,268,846 | 19.7% |
| NOP | 4,993,595 | 10.6% |
| STORE_ATTR_SLOT | 4,120,066 | 8.8% |
| POP_JUMP_IF_FALSE | 2,755,842 | 5.9% |
| RESUME_CHECK | 2,675,532 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 6,545,693 | 13.9% |
| LOAD_FAST | 5,548,859 | 11.8% |
| BINARY_SUBSCR_DICT | 4,760,781 | 10.1% |
| IS_OP | 4,617,257 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 3,660,513 | 7.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,946 | 11.9% |
| POP_JUMP_IF_FALSE | 11,218 | 10.3% |
| LOAD_FAST | 10,708 | 9.8% |
| RESUME_CHECK | 7,227 | 6.6% |
| RESUME | 7,119 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,602 | 32.6% |
| LOAD_GLOBAL_BUILTIN | 18,806 | 17.2% |
| LOAD_FAST | 16,160 | 14.8% |
| LOAD_ATTR | 14,258 | 13.1% |
| CALL | 7,381 | 6.8% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,420 | 50.9% |
| RESUME | 940 | 14.0% |
| STORE_NAME | 920 | 13.7% |
| LOAD_NAME | 900 | 13.4% |
| POP_TOP | 200 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,300 | 34.2% |
| STORE_NAME | 1,060 | 15.8% |
| LOAD_NAME | 900 | 13.4% |
| CALL | 620 | 9.2% |
| LOAD_ATTR | 600 | 8.9% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,640 | 89.1% |
| EXTENDED_ARG | 120 | 6.5% |
| LOAD_DEREF | 80 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 720 | 39.1% |
| CALL | 300 | 16.3% |
| LOAD_FAST | 260 | 14.1% |
| LOAD_SUPER_ATTR_ATTR | 220 | 12.0% |
| PUSH_NULL | 160 | 8.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,067,110 | 49.4% |
| CALL_PY_WITH_DEFAULTS | 721,722 | 17.3% |
| CALL_PY_EXACT_ARGS | 653,534 | 15.6% |
| CALL_KW | 380,985 | 9.1% |
| CACHE | 267,182 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,067,110 | 49.4% |
| RESUME_CHECK | 2,030,612 | 48.6% |
| RETURN_GENERATOR | 83,141 | 2.0% |
| RESUME | 1,540 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 249,282 | 36.2% |
| STORE_FAST | 168,160 | 24.4% |
| RETURN_VALUE | 88,220 | 12.8% |
| CALL_KW | 88,000 | 12.8% |
| LOAD_ATTR_SLOT | 80,100 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 673,348 | 97.8% |
| LOAD_CONST | 9,120 | 1.3% |
| JUMP_BACKWARD | 5,144 | 0.7% |
| DICT_UPDATE | 240 | 0.0% |
| BUILD_MAP | 160 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 19,696,668 | 31.0% |
| CONTAINS_OP | 7,541,190 | 11.9% |
| IS_OP | 7,341,720 | 11.5% |
| COMPARE_OP_INT | 7,035,160 | 11.1% |
| TO_BOOL | 5,792,734 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,314,940 | 54.0% |
| LOAD_CONST | 5,745,673 | 9.0% |
| LOAD_GLOBAL_MODULE | 5,719,666 | 9.0% |
| RETURN_CONST | 5,041,205 | 7.9% |
| LOAD_GLOBAL_BUILTIN | 2,849,288 | 4.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,655,937 | 70.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,487,160 | 22.6% |
| LOAD_DEREF | 317,204 | 4.8% |
| LOAD_ATTR_WITH_HINT | 96,043 | 1.5% |
| ENTER_EXECUTOR | 2,987 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,640,836 | 70.6% |
| RETURN_CONST | 676,829 | 10.3% |
| LOAD_GLOBAL_MODULE | 267,427 | 4.1% |
| NOP | 234,025 | 3.6% |
| LOAD_CONST | 203,308 | 3.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,538,100 | 73.8% |
| LOAD_ATTR_INSTANCE_VALUE | 950,793 | 15.5% |
| LOAD_DEREF | 363,340 | 5.9% |
| LOAD_GLOBAL_MODULE | 92,793 | 1.5% |
| EXTENDED_ARG | 88,020 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,155,346 | 35.1% |
| LOAD_FAST_LOAD_FAST | 1,252,501 | 20.4% |
| LOAD_GLOBAL_MODULE | 1,244,657 | 20.2% |
| LOAD_GLOBAL_BUILTIN | 579,838 | 9.4% |
| RETURN_CONST | 420,952 | 6.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,209,463 | 39.9% |
| TO_BOOL | 2,634,801 | 20.2% |
| IS_OP | 1,175,436 | 9.0% |
| TO_BOOL_INT | 934,206 | 7.2% |
| CONTAINS_OP | 743,330 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,296,473 | 48.3% |
| LOAD_CONST | 1,193,612 | 9.2% |
| LOAD_GLOBAL_BUILTIN | 806,426 | 6.2% |
| LOAD_FAST_LOAD_FAST | 771,563 | 5.9% |
| ENTER_EXECUTOR | 625,934 | 4.8% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,102 | 49.7% |
| CALL_KW | 1,520 | 24.4% |
| LOAD_GLOBAL_MODULE | 865 | 13.9% |
| LOAD_CONST | 400 | 6.4% |
| LOAD_FAST | 324 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,995 | 73.3% |
| COPY | 400 | 14.7% |
| LOAD_CONST | 324 | 11.9% |
| CALL_INTRINSIC_1 | 2 | 0.1% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 179,237 | 49.9% |
| POP_JUMP_IF_TRUE | 177,395 | 49.4% |
| CALL_INTRINSIC_1 | 1,326 | 0.4% |
| POP_JUMP_IF_FALSE | 1,040 | 0.3% |
| DELETE_FAST | 402 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 178,837 | 98.3% |
| PUSH_EXC_INFO | 1,835 | 1.0% |
| CALL_INTRINSIC_1 | 1,324 | 0.7% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,089,137 | 29.2% |
| POP_JUMP_IF_FALSE | 5,041,205 | 24.2% |
| STORE_ATTR_SLOT | 2,336,408 | 11.2% |
| STORE_FAST | 1,588,439 | 7.6% |
| STORE_ATTR_INSTANCE_VALUE | 1,006,499 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,388,091 | 59.5% |
| INTERPRETER_EXIT | 6,391,050 | 30.7% |
| TO_BOOL_BOOL | 617,266 | 3.0% |
| STORE_FAST | 357,224 | 1.7% |
| RETURN_VALUE | 313,556 | 1.5% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 319,342 | 62.0% |
| LOAD_CONST | 193,834 | 37.6% |
| SEND | 2,110 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 318,875 | 61.9% |
| END_SEND | 191,071 | 37.1% |
| SEND | 2,110 | 0.4% |
| POP_TOP | 1,619 | 0.3% |
| SEND_GEN | 1,611 | 0.3% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80,000 | 45.0% |
| STORE_FAST_LOAD_FAST | 80,000 | 45.0% |
| RETURN_GENERATOR | 8,000 | 4.5% |
| LOAD_FAST | 8,000 | 4.5% |
| JUMP_FORWARD | 1,760 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 176,060 | 99.0% |
| JUMP_BACKWARD | 1,700 | 1.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,135,002 | 84.1% |
| SET_FUNCTION_ATTRIBUTE | 214,513 | 15.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 526,141 | 39.0% |
| CALL | 274,017 | 20.3% |
| SET_FUNCTION_ATTRIBUTE | 214,513 | 15.9% |
| LOAD_FAST | 196,236 | 14.5% |
| STORE_DEREF | 81,422 | 6.0% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 88,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 88,000 | 100.0% |
| STORE_NAME | 20 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 737,219 | 70.3% |
| LOAD_GLOBAL_MODULE | 265,192 | 25.3% |
| LOAD_FAST_LOAD_FAST | 22,768 | 2.2% |
| LOAD_DEREF | 10,960 | 1.0% |
| STORE_ATTR | 7,940 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 455,852 | 43.5% |
| LOAD_GLOBAL_MODULE | 179,160 | 17.1% |
| LOAD_GLOBAL_BUILTIN | 176,986 | 16.9% |
| LOAD_CONST | 95,700 | 9.1% |
| LOAD_FAST_LOAD_FAST | 91,689 | 8.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 174,480 | 21.6% |
| LOAD_CONST | 130,952 | 16.2% |
| CALL_BUILTIN_CLASS | 89,500 | 11.1% |
| MAKE_FUNCTION | 88,007 | 10.9% |
| JUMP_FORWARD | 88,007 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 268,937 | 33.4% |
| LOAD_CONST | 211,641 | 26.3% |
| LOAD_FAST | 192,881 | 23.9% |
| LOAD_DEREF | 50,472 | 6.3% |
| LOAD_GLOBAL_BUILTIN | 40,279 | 5.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 13,948,855 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 6,988,292 | 8.8% |
| BINARY_SUBSCR_DICT | 6,350,316 | 8.0% |
| FOR_ITER_TUPLE | 5,693,474 | 7.2% |
| LOAD_CONST | 5,149,336 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,076,830 | 56.6% |
| LOAD_FAST_LOAD_FAST | 9,268,846 | 11.6% |
| NOP | 7,442,290 | 9.3% |
| LOAD_GLOBAL_MODULE | 3,466,373 | 4.4% |
| LOAD_CONST | 2,650,935 | 3.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 644,033 | 78.1% |
| COPY | 88,380 | 10.7% |
| FOR_ITER_TUPLE | 46,940 | 5.7% |
| SWAP | 40,674 | 4.9% |
| FOR_ITER_LIST | 3,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 400,160 | 48.5% |
| STORE_ATTR_SLOT | 87,960 | 10.7% |
| LOAD_DEREF | 80,600 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 80,500 | 9.8% |
| SET_ADD | 80,000 | 9.7% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,112,177 | 70.3% |
| UNPACK_SEQUENCE_TUPLE | 1,159,496 | 26.2% |
| UNPACK_EX | 88,000 | 2.0% |
| STORE_FAST_STORE_FAST | 49,056 | 1.1% |
| ENTER_EXECUTOR | 7,230 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,902,576 | 65.6% |
| STORE_FAST | 1,157,202 | 26.2% |
| NOP | 113,480 | 2.6% |
| LOAD_FAST_LOAD_FAST | 98,434 | 2.2% |
| LOAD_GLOBAL_MODULE | 56,482 | 1.3% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 140 | 30.4% |
| BINARY_OP_SUBTRACT_INT | 140 | 30.4% |
| LOAD_FAST | 80 | 17.4% |
| BINARY_OP | 40 | 8.7% |
| CALL | 40 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 39.1% |
| LOAD_GLOBAL_MODULE | 120 | 26.1% |
| LOAD_FAST | 80 | 17.4% |
| LOAD_GLOBAL | 80 | 17.4% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 4,200 | 29.2% |
| SET_FUNCTION_ATTRIBUTE | 3,580 | 24.9% |
| LOAD_CONST | 1,540 | 10.7% |
| CALL | 1,260 | 8.8% |
| LOAD_NAME | 1,060 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,420 | 44.6% |
| POP_TOP | 2,460 | 17.1% |
| IMPORT_FROM | 1,740 | 12.1% |
| RETURN_CONST | 980 | 6.8% |
| LOAD_NAME | 920 | 6.4% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,952,273 | 31.3% |
| BINARY_OP_ADD_INT | 2,775,950 | 17.5% |
| LOAD_FAST_AND_CLEAR | 1,387,871 | 8.8% |
| SWAP | 1,381,292 | 8.7% |
| BINARY_OP_SUBTRACT_INT | 1,050,732 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,542,711 | 28.7% |
| STORE_ATTR_WITH_HINT | 1,407,840 | 8.9% |
| SWAP | 1,381,292 | 8.7% |
| STORE_ATTR_INSTANCE_VALUE | 1,365,133 | 8.6% |
| STORE_FAST | 1,359,884 | 8.6% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 88,000 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,252 | 25.7% |
| FOR_ITER | 1,862 | 21.2% |
| RETURN_VALUE | 1,420 | 16.2% |
| RETURN_GENERATOR | 826 | 9.4% |
| CALL | 420 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 3,824 | 43.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,041 | 23.3% |
| STORE_FAST | 1,983 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 520 | 5.9% |
| UNPACK_SEQUENCE | 260 | 3.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 394,565 | 26.5% |
| SEND | 318,875 | 21.4% |
| YIELD_VALUE | 267,388 | 18.0% |
| BUILD_TUPLE | 98,588 | 6.6% |
| LOAD_FAST | 82,940 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,127,418 | 75.7% |
| YIELD_VALUE | 267,388 | 18.0% |
| STORE_FAST | 93,568 | 6.3% |
| UNPACK_SEQUENCE_TUPLE | 200 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 80 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 9,872 | 37.7% |
| CACHE | 7,447 | 28.4% |
| POP_TOP | 2,399 | 9.2% |
| COPY_FREE_VARS | 1,687 | 6.4% |
| MAKE_CELL | 1,540 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,210 | 39.0% |
| LOAD_GLOBAL | 7,119 | 27.2% |
| LOAD_CONST | 1,500 | 5.7% |
| LOAD_FAST_LOAD_FAST | 1,427 | 5.4% |
| NOP | 1,380 | 5.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 324,433 | 27.8% |
| LOAD_ATTR_INSTANCE_VALUE | 274,516 | 23.5% |
| LOAD_FAST_LOAD_FAST | 271,920 | 23.3% |
| BINARY_OP | 202,697 | 17.3% |
| BINARY_OP_MULTIPLY_FLOAT | 87,928 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 471,409 | 40.3% |
| LOAD_FAST | 362,901 | 31.1% |
| STORE_FAST | 331,772 | 28.4% |
| CALL_ALLOC_AND_ENTER_INIT | 1,950 | 0.2% |
| RETURN_VALUE | 320 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,100,207 | 41.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,170,549 | 22.9% |
| CALL | 652,096 | 12.8% |
| LOAD_FAST | 491,345 | 9.6% |
| CALL_LEN | 354,008 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,775,950 | 54.3% |
| RETURN_VALUE | 1,264,399 | 24.7% |
| LOAD_GLOBAL_MODULE | 366,928 | 7.2% |
| LOAD_CONST | 339,190 | 6.6% |
| LOAD_FAST | 119,857 | 2.3% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 110,146 | 42.1% |
| RETURN_VALUE | 89,384 | 34.2% |
| LOAD_FAST_LOAD_FAST | 54,120 | 20.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,300 | 0.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,560 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 108,760 | 41.6% |
| LIST_APPEND | 87,980 | 33.7% |
| LOAD_FAST | 45,486 | 17.4% |
| CALL | 9,400 | 3.6% |
| STORE_FAST | 2,438 | 0.9% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 184,080 | 89.1% |
| LOAD_CONST | 17,959 | 8.7% |
| LOAD_FAST_LOAD_FAST | 4,333 | 2.1% |
| BINARY_OP | 233 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 87,928 | 42.6% |
| LOAD_CONST | 87,900 | 42.5% |
| CALL_BUILTIN_O | 18,463 | 8.9% |
| COMPARE_OP_FLOAT | 7,720 | 3.7% |
| STORE_FAST | 4,352 | 2.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 326,088 | 50.0% |
| LOAD_FAST_LOAD_FAST | 174,927 | 26.8% |
| LOAD_CONST | 96,434 | 14.8% |
| BINARY_OP_ADD_INT | 40,880 | 6.3% |
| LOAD_GLOBAL_MODULE | 12,938 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 326,860 | 50.1% |
| BINARY_OP | 174,987 | 26.8% |
| COMPARE_OP_INT | 87,960 | 13.5% |
| STORE_FAST | 52,992 | 8.1% |
| LOAD_CONST | 6,130 | 0.9% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 446,076 | 54.7% |
| LOAD_FAST | 175,784 | 21.5% |
| CALL | 87,801 | 10.8% |
| RETURN_VALUE | 78,827 | 9.7% |
| LOAD_ATTR_INSTANCE_VALUE | 16,085 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 292,678 | 35.9% |
| LOAD_CONST | 266,400 | 32.7% |
| SWAP | 175,832 | 21.6% |
| CALL | 58,081 | 7.1% |
| LOAD_FAST | 16,485 | 2.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 781,446 | 40.1% |
| LOAD_FAST | 525,227 | 26.9% |
| BINARY_OP_MULTIPLY_INT | 326,860 | 16.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 263,880 | 13.5% |
| BINARY_OP_SUBTRACT_INT | 40,960 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,050,732 | 53.9% |
| RETURN_VALUE | 327,748 | 16.8% |
| BINARY_OP | 175,327 | 9.0% |
| STORE_FAST | 173,286 | 8.9% |
| BINARY_SUBSCR_LIST_INT | 64,180 | 3.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,760,781 | 46.5% |
| LOAD_FAST | 2,776,406 | 27.1% |
| LOAD_CONST | 1,328,582 | 13.0% |
| COPY | 1,027,178 | 10.0% |
| CALL | 230,578 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,350,316 | 62.1% |
| LOAD_CONST | 1,407,115 | 13.8% |
| RETURN_VALUE | 1,073,536 | 10.5% |
| LOAD_FAST | 669,181 | 6.5% |
| PUSH_EXC_INFO | 188,617 | 1.8% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 576,949 | 98.4% |
| ENTER_EXECUTOR | 7,220 | 1.2% |
| LOAD_CONST | 1,500 | 0.3% |
| LOAD_FAST_LOAD_FAST | 740 | 0.1% |
| BINARY_SUBSCR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 322,469 | 55.0% |
| COPY_FREE_VARS | 263,960 | 45.0% |
| BUILD_TUPLE | 160 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 725,681 | 77.8% |
| LOAD_FAST | 79,186 | 8.5% |
| BINARY_OP_SUBTRACT_INT | 64,180 | 6.9% |
| LOAD_FAST_LOAD_FAST | 62,598 | 6.7% |
| BINARY_SUBSCR | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 260,848 | 28.0% |
| LOAD_ATTR_SLOT | 257,082 | 27.6% |
| LOAD_FAST_LOAD_FAST | 115,800 | 12.4% |
| TO_BOOL_BOOL | 88,563 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 63,840 | 6.9% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 233,720 | 96.2% |
| LOAD_FAST_LOAD_FAST | 5,120 | 2.1% |
| LOAD_FAST | 2,860 | 1.2% |
| CALL_BUILTIN_O | 600 | 0.2% |
| ENTER_EXECUTOR | 400 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 207,080 | 85.3% |
| LOAD_ATTR_METHOD_NO_DICT | 31,600 | 13.0% |
| STORE_FAST | 2,760 | 1.1% |
| LIST_APPEND | 620 | 0.3% |
| PUSH_EXC_INFO | 440 | 0.2% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,485,726 | 99.8% |
| LOAD_FAST_LOAD_FAST | 2,952 | 0.2% |
| BINARY_SUBSCR | 640 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 688,240 | 46.2% |
| LOAD_ATTR_SLOT | 227,711 | 15.3% |
| CALL_BUILTIN_O | 176,880 | 11.9% |
| STORE_FAST | 103,778 | 7.0% |
| RETURN_VALUE | 99,669 | 6.7% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 177,166 | 59.6% |
| LOAD_FAST_LOAD_FAST | 93,482 | 31.4% |
| LOAD_FAST | 8,566 | 2.9% |
| LOAD_CONST | 8,000 | 2.7% |
| LOAD_GLOBAL_MODULE | 2,239 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 295,110 | 99.3% |
| COPY_FREE_VARS | 1,152 | 0.4% |
| POP_TOP | 920 | 0.3% |
| RESUME | 40 | 0.0% |
| STORE_FAST | 20 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 43,061 | 32.9% |
| LOAD_CONST | 24,264 | 18.5% |
| LOAD_FAST | 19,467 | 14.9% |
| PUSH_NULL | 16,154 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 10,842 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 104,052 | 79.4% |
| POP_TOP | 12,008 | 9.2% |
| GET_AWAITABLE | 10,636 | 8.1% |
| COPY_FREE_VARS | 2,115 | 1.6% |
| MAKE_CELL | 832 | 0.6% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,090,456 | 29.3% |
| LOAD_FAST | 1,995,907 | 28.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,089,036 | 15.3% |
| LOAD_ATTR_SLOT | 952,040 | 13.3% |
| PUSH_NULL | 437,656 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,058,638 | 28.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,280,193 | 17.9% |
| LOAD_FAST | 1,067,566 | 15.0% |
| CALL | 980,344 | 13.7% |
| GET_ITER | 798,493 | 11.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,143,980 | 58.8% |
| LOAD_FAST_LOAD_FAST | 411,094 | 21.1% |
| BUILD_TUPLE | 167,920 | 8.6% |
| LOAD_GLOBAL_MODULE | 88,200 | 4.5% |
| LOAD_FAST | 71,864 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 683,208 | 35.1% |
| TO_BOOL_BOOL | 492,354 | 25.3% |
| POP_TOP | 236,307 | 12.2% |
| RETURN_VALUE | 232,231 | 11.9% |
| STORE_FAST | 135,958 | 7.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,280,193 | 56.6% |
| LOAD_FAST | 529,200 | 23.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 168,080 | 7.4% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 88,000 | 3.9% |
| LOAD_ATTR | 84,591 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,170,549 | 51.8% |
| STORE_FAST | 424,332 | 18.8% |
| RETURN_VALUE | 301,376 | 13.3% |
| POP_TOP | 94,438 | 4.2% |
| LOAD_ATTR_METHOD_NO_DICT | 88,000 | 3.9% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 459,373 | 28.9% |
| LOAD_ATTR_INSTANCE_VALUE | 409,154 | 25.8% |
| BINARY_SUBSCR_TUPLE_INT | 176,880 | 11.1% |
| RETURN_GENERATOR | 118,396 | 7.5% |
| LOAD_ATTR_SLOT | 118,140 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 551,136 | 34.7% |
| RETURN_VALUE | 443,544 | 27.9% |
| STORE_FAST | 333,983 | 21.0% |
| LOAD_FAST | 90,347 | 5.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 87,271 | 5.5% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,847,737 | 41.1% |
| LOAD_GLOBAL_MODULE | 1,433,149 | 31.9% |
| LOAD_FAST_LOAD_FAST | 444,654 | 9.9% |
| LOAD_ATTR | 377,290 | 8.4% |
| BUILD_TUPLE | 281,499 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,054,527 | 90.1% |
| RETURN_VALUE | 279,383 | 6.2% |
| COPY | 160,356 | 3.6% |
| TO_BOOL | 2,460 | 0.1% |
| YIELD_VALUE | 2,020 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,485,018 | 62.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,290,169 | 23.1% |
| LOAD_ATTR_SLOT | 432,280 | 7.7% |
| LOAD_ATTR_WITH_HINT | 359,822 | 6.4% |
| LOAD_DEREF | 4,600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,069,767 | 37.1% |
| LOAD_CONST | 1,186,795 | 21.3% |
| RETURN_VALUE | 886,613 | 15.9% |
| LOAD_FAST | 390,840 | 7.0% |
| BINARY_OP_ADD_INT | 354,008 | 6.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 279,569 | 42.3% |
| BUILD_CONST_KEY_MAP | 176,880 | 26.8% |
| ENTER_EXECUTOR | 77,146 | 11.7% |
| BUILD_TUPLE | 65,885 | 10.0% |
| BINARY_SLICE | 40,880 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 299,552 | 45.4% |
| ENTER_EXECUTOR | 155,499 | 23.5% |
| NOP | 90,725 | 13.7% |
| LOAD_FAST_LOAD_FAST | 89,000 | 13.5% |
| RETURN_CONST | 10,400 | 1.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,456,964 | 40.8% |
| LOAD_CONST | 2,201,973 | 36.6% |
| BUILD_TUPLE | 527,960 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 435,528 | 7.2% |
| LOAD_ATTR_INSTANCE_VALUE | 104,580 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,972,833 | 82.6% |
| BINARY_OP_SUBTRACT_INT | 263,880 | 4.4% |
| POP_TOP | 179,665 | 3.0% |
| CALL_METHOD_DESCRIPTOR_O | 167,960 | 2.8% |
| LOAD_FAST | 99,620 | 1.7% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,195 | 39.6% |
| LOAD_FAST_LOAD_FAST | 234,864 | 30.3% |
| LOAD_ATTR_METHOD_NO_DICT | 133,286 | 17.2% |
| LOAD_CONST | 57,419 | 7.4% |
| LOAD_ATTR | 41,683 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 347,958 | 44.9% |
| STORE_FAST | 332,883 | 43.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 88,000 | 11.4% |
| GET_ITER | 1,880 | 0.2% |
| RETURN_VALUE | 1,320 | 0.2% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,547,567 | 84.7% |
| LOAD_ATTR | 1,177,478 | 15.2% |
| CALL | 3,980 | 0.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,618 | 0.0% |
| LOAD_FAST | 1,452 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,530,792 | 32.7% |
| POP_TOP | 1,323,516 | 17.1% |
| CALL_BUILTIN_CLASS | 1,089,036 | 14.1% |
| TO_BOOL_BOOL | 981,119 | 12.7% |
| STORE_FAST | 815,151 | 10.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,407,084 | 67.2% |
| BUILD_TUPLE | 1,551,843 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 337,880 | 4.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 167,960 | 2.1% |
| CALL | 156,428 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,662,668 | 95.3% |
| RETURN_VALUE | 171,174 | 2.1% |
| LOAD_CONST | 103,118 | 1.3% |
| STORE_FAST | 46,081 | 0.6% |
| BUILD_LIST | 40,820 | 0.5% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,866,377 | 35.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,639,925 | 25.2% |
| CALL_TYPE_1 | 4,536,291 | 15.0% |
| LOAD_FAST_LOAD_FAST | 1,612,067 | 5.3% |
| LOAD_DEREF | 919,660 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 28,733,055 | 94.7% |
| COPY_FREE_VARS | 761,840 | 2.5% |
| MAKE_CELL | 653,534 | 2.2% |
| RETURN_GENERATOR | 104,153 | 0.3% |
| TO_BOOL_BOOL | 86,673 | 0.3% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,092,526 | 45.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 482,333 | 19.9% |
| ENTER_EXECUTOR | 353,358 | 14.6% |
| LOAD_ATTR_INSTANCE_VALUE | 177,028 | 7.3% |
| LOAD_FAST_LOAD_FAST | 90,500 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,618,271 | 66.7% |
| MAKE_CELL | 721,722 | 29.7% |
| RETURN_GENERATOR | 85,518 | 3.5% |
| CALL | 1,060 | 0.0% |
| STORE_FAST | 1,040 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 88,000 | 33.9% |
| CALL_TYPE_1 | 87,960 | 33.8% |
| LOAD_ATTR | 78,235 | 30.1% |
| LOAD_FAST | 2,967 | 1.1% |
| LOAD_ATTR_INSTANCE_VALUE | 2,300 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 88,000 | 33.9% |
| CONTAINS_OP | 87,980 | 33.8% |
| BUILD_TUPLE | 78,255 | 30.1% |
| STORE_FAST | 4,107 | 1.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 640 | 0.2% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 176,440 | 48.6% |
| CALL_BUILTIN_CLASS | 88,760 | 24.4% |
| STORE_FAST | 87,960 | 24.2% |
| LOAD_FAST | 8,590 | 2.4% |
| LOAD_GLOBAL_MODULE | 680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 176,680 | 48.6% |
| CALL_STR_1 | 88,000 | 24.2% |
| BINARY_OP | 87,980 | 24.2% |
| LOAD_FAST_LOAD_FAST | 7,150 | 2.0% |
| STORE_FAST | 1,240 | 0.3% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,619,311 | 98.8% |
| BINARY_SUBSCR_TUPLE_INT | 87,960 | 1.1% |
| CALL | 780 | 0.0% |
| LOAD_GLOBAL_MODULE | 640 | 0.0% |
| LOAD_DEREF | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,536,291 | 58.8% |
| STORE_FAST | 1,914,220 | 24.8% |
| LOAD_GLOBAL_BUILTIN | 484,780 | 6.3% |
| LOAD_GLOBAL_MODULE | 239,280 | 3.1% |
| LOAD_FAST | 180,576 | 2.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 541,401 | 31.5% |
| LOAD_CONST | 431,097 | 25.0% |
| LOAD_FAST | 339,393 | 19.7% |
| BINARY_OP | 181,654 | 10.6% |
| COPY | 174,927 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,179,456 | 68.5% |
| RETURN_VALUE | 540,581 | 31.4% |
| POP_JUMP_IF_TRUE | 920 | 0.1% |
| EXTENDED_ARG | 308 | 0.0% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,595,143 | 56.5% |
| LOAD_FAST_LOAD_FAST | 1,699,734 | 20.9% |
| LOAD_ATTR_INSTANCE_VALUE | 509,683 | 6.3% |
| LOAD_GLOBAL_MODULE | 365,344 | 4.5% |
| LOAD_ATTR_WITH_HINT | 183,494 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,035,160 | 86.5% |
| POP_JUMP_IF_TRUE | 742,103 | 9.1% |
| EXTENDED_ARG | 352,566 | 4.3% |
| RETURN_VALUE | 3,320 | 0.0% |
| COPY | 960 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,954,069 | 71.2% |
| LOAD_FAST | 603,366 | 10.9% |
| LOAD_FAST_LOAD_FAST | 456,020 | 8.2% |
| LOAD_GLOBAL_MODULE | 360,252 | 6.5% |
| LOAD_ATTR_INSTANCE_VALUE | 90,460 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,087,832 | 91.6% |
| POP_JUMP_IF_TRUE | 369,540 | 6.7% |
| RETURN_VALUE | 88,040 | 1.6% |
| COPY | 7,240 | 0.1% |
| EXTENDED_ARG | 2,920 | 0.1% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 93,095 | 95.0% |
| GET_ITER | 3,498 | 3.6% |
| SWAP | 930 | 0.9% |
| FOR_ITER | 260 | 0.3% |
| EXTENDED_ARG | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 93,095 | 95.0% |
| POP_TOP | 4,428 | 4.5% |
| RETURN_CONST | 240 | 0.2% |
| STORE_FAST | 160 | 0.2% |
| RESUME | 100 | 0.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,080,700 | 60.4% |
| ENTER_EXECUTOR | 1,269,999 | 36.8% |
| SWAP | 45,060 | 1.3% |
| LOAD_FAST | 24,546 | 0.7% |
| JUMP_BACKWARD | 20,345 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,274,531 | 37.0% |
| STORE_FAST | 1,133,073 | 32.9% |
| RETURN_CONST | 883,923 | 25.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 137,285 | 4.0% |
| LOAD_GLOBAL_BUILTIN | 4,306 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 249,260 | 54.7% |
| GET_ITER | 202,413 | 44.4% |
| JUMP_BACKWARD | 3,550 | 0.8% |
| FOR_ITER | 300 | 0.1% |
| LOAD_FAST | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 234,904 | 51.5% |
| STORE_FAST | 205,839 | 45.1% |
| LOAD_FAST | 7,390 | 1.6% |
| LOAD_GLOBAL_BUILTIN | 7,130 | 1.6% |
| RETURN_CONST | 260 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,418,931 | 78.1% |
| ENTER_EXECUTOR | 1,193,113 | 17.2% |
| LOAD_FAST | 185,896 | 2.7% |
| SWAP | 135,460 | 2.0% |
| JUMP_BACKWARD | 8,140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,693,474 | 82.0% |
| LOAD_FAST | 762,606 | 11.0% |
| RETURN_CONST | 183,126 | 2.6% |
| SWAP | 135,580 | 2.0% |
| ENTER_EXECUTOR | 80,200 | 1.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 251,151 | 54.2% |
| LOAD_ATTR_MODULE | 204,927 | 44.2% |
| LOAD_FAST | 3,252 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 2,188 | 0.5% |
| ENTER_EXECUTOR | 1,060 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 164,560 | 35.5% |
| COMPARE_OP_INT | 123,046 | 26.6% |
| CALL_PY_EXACT_ARGS | 82,169 | 17.7% |
| LOAD_FAST | 46,386 | 10.0% |
| CALL | 41,969 | 9.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,452,810 | 87.4% |
| LOAD_FAST_LOAD_FAST | 3,660,513 | 6.3% |
| COPY | 1,365,133 | 2.4% |
| LOAD_ATTR_SLOT | 1,312,282 | 2.3% |
| LOAD_DEREF | 655,229 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,727,358 | 15.1% |
| LOAD_ATTR_METHOD_NO_DICT | 7,323,340 | 12.7% |
| STORE_FAST | 6,988,292 | 12.1% |
| TO_BOOL_BOOL | 5,087,961 | 8.8% |
| RETURN_VALUE | 3,878,317 | 6.7% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 263,900 | 100.0% |
| LOAD_FAST | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 263,920 | 100.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,463,740 | 39.5% |
| LOAD_ATTR_INSTANCE_VALUE | 7,323,340 | 27.6% |
| LOAD_ATTR_WITH_HINT | 5,452,585 | 20.6% |
| LOAD_ATTR_SLOT | 1,801,227 | 6.8% |
| RETURN_VALUE | 528,300 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,665,413 | 51.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,547,567 | 24.7% |
| LOAD_CONST | 2,636,766 | 9.9% |
| LOAD_FAST_LOAD_FAST | 1,391,275 | 5.2% |
| CALL | 978,199 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,595,304 | 67.0% |
| LOAD_ATTR_INSTANCE_VALUE | 2,448,203 | 12.1% |
| LOAD_ATTR_SLOT | 1,529,399 | 7.5% |
| LOAD_ATTR_WITH_HINT | 1,222,216 | 6.0% |
| LOAD_DEREF | 544,796 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 7,639,925 | 37.6% |
| LOAD_GLOBAL_BUILTIN | 4,682,014 | 23.1% |
| LOAD_FAST | 4,087,635 | 20.1% |
| LOAD_FAST_LOAD_FAST | 1,632,377 | 8.0% |
| LOAD_GLOBAL_MODULE | 803,672 | 4.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,635,470 | 96.7% |
| LOAD_FAST | 143,147 | 1.8% |
| LOAD_ATTR_MODULE | 105,067 | 1.3% |
| LOAD_ATTR | 13,245 | 0.2% |
| BINARY_SUBSCR_DICT | 1,814 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,262,426 | 79.3% |
| LOAD_FAST | 319,743 | 4.0% |
| LOAD_ATTR_CLASS | 204,927 | 2.6% |
| LOAD_ATTR | 183,378 | 2.3% |
| BINARY_OP | 148,998 | 1.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,880 | 77.4% |
| LOAD_FAST_LOAD_FAST | 872 | 17.4% |
| LOAD_ATTR | 180 | 3.6% |
| LOAD_CONST | 80 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,610 | 32.1% |
| TO_BOOL_BOOL | 1,138 | 22.7% |
| LOAD_FAST | 952 | 19.0% |
| CALL_BUILTIN_FAST | 872 | 17.4% |
| CALL | 240 | 4.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 205,895 | 60.5% |
| LOAD_FAST | 89,997 | 26.4% |
| LOAD_FAST_LOAD_FAST | 43,640 | 12.8% |
| LOAD_ATTR | 700 | 0.2% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 124,447 | 36.6% |
| COMPARE_OP_INT | 81,860 | 24.1% |
| LOAD_FAST | 42,535 | 12.5% |
| LOAD_CONST | 41,080 | 12.1% |
| STORE_FAST | 40,980 | 12.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,421,197 | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE | 177,932 | 6.5% |
| RETURN_VALUE | 101,007 | 3.7% |
| ENTER_EXECUTOR | 22,960 | 0.8% |
| LOAD_ATTR | 2,574 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,727,510 | 99.9% |
| COPY_FREE_VARS | 1,864 | 0.1% |
| LOAD_GLOBAL_MODULE | 386 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 60 | 0.0% |
| LOAD_ATTR_PROPERTY | 60 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,462,724 | 92.3% |
| LOAD_FAST_LOAD_FAST | 946,984 | 2.9% |
| STORE_FAST_LOAD_FAST | 400,160 | 1.2% |
| COPY | 359,732 | 1.1% |
| BINARY_SUBSCR_LIST_INT | 257,082 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,779,012 | 11.5% |
| TO_BOOL_NONE | 3,215,887 | 9.7% |
| LOAD_CONST | 2,929,436 | 8.9% |
| STORE_FAST | 2,881,186 | 8.7% |
| LOAD_FAST | 2,513,813 | 7.6% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,405,079 | 82.7% |
| COPY | 1,407,840 | 6.7% |
| LOAD_FAST_LOAD_FAST | 1,159,665 | 5.5% |
| LOAD_DEREF | 447,270 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 440,640 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,452,585 | 25.9% |
| LOAD_FAST | 3,746,636 | 17.8% |
| TO_BOOL_BOOL | 2,593,014 | 12.3% |
| LOAD_CONST | 1,952,552 | 9.3% |
| RETURN_VALUE | 1,850,031 | 8.8% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,640,760 | 26.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,682,014 | 12.7% |
| LOAD_FAST | 4,306,989 | 11.7% |
| POP_JUMP_IF_FALSE | 2,849,288 | 7.7% |
| STORE_FAST | 2,549,566 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,783,683 | 61.9% |
| IS_OP | 2,533,620 | 6.9% |
| LOAD_GLOBAL_BUILTIN | 2,331,148 | 6.3% |
| CALL_BUILTIN_CLASS | 2,090,456 | 5.7% |
| CALL_ISINSTANCE | 1,847,737 | 5.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,625,287 | 20.0% |
| LOAD_FAST | 5,952,134 | 13.8% |
| POP_JUMP_IF_FALSE | 5,719,666 | 13.3% |
| STORE_FAST | 3,466,373 | 8.0% |
| LOAD_GLOBAL_MODULE | 3,278,148 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,244,527 | 35.3% |
| LOAD_ATTR_MODULE | 7,635,470 | 17.7% |
| CALL | 3,534,396 | 8.2% |
| LOAD_GLOBAL_MODULE | 3,278,148 | 7.6% |
| LOAD_FAST_LOAD_FAST | 2,465,062 | 5.7% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,616 | 91.4% |
| LOAD_SUPER_ATTR | 220 | 5.6% |
| EXTENDED_ARG | 120 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,052 | 51.9% |
| LOAD_GLOBAL_MODULE | 1,864 | 47.1% |
| LOAD_GLOBAL | 40 | 1.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 639,457 | 99.9% |
| LOAD_SUPER_ATTR | 720 | 0.1% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400,935 | 62.6% |
| LOAD_FAST_LOAD_FAST | 195,170 | 30.5% |
| CALL_PY_EXACT_ARGS | 43,408 | 6.8% |
| CALL | 380 | 0.1% |
| LOAD_CONST | 304 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 28,733,055 | 37.6% |
| CACHE | 22,060,570 | 28.9% |
| CALL_FUNCTION_EX | 5,721,930 | 7.5% |
| CALL | 3,981,872 | 5.2% |
| COPY_FREE_VARS | 3,568,963 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,766,161 | 58.6% |
| LOAD_GLOBAL_BUILTIN | 9,640,760 | 12.6% |
| LOAD_GLOBAL_MODULE | 8,625,287 | 11.3% |
| NOP | 5,280,093 | 6.9% |
| LOAD_FAST_LOAD_FAST | 2,675,532 | 3.5% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 326,646 | 55.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 266,109 | 44.8% |
| SEND | 1,611 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 327,306 | 55.1% |
| RESUME_CHECK | 265,862 | 44.7% |
| RESUME | 958 | 0.2% |
| END_SEND | 160 | 0.0% |
| YIELD_VALUE | 80 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,338,445 | 69.6% |
| LOAD_FAST_LOAD_FAST | 1,613,339 | 15.3% |
| SWAP | 1,365,133 | 13.0% |
| LOAD_DEREF | 86,151 | 0.8% |
| BINARY_SUBSCR_DICT | 79,960 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,726,197 | 25.9% |
| LOAD_CONST | 2,706,499 | 25.7% |
| RETURN_CONST | 1,006,499 | 9.5% |
| LOAD_FAST_LOAD_FAST | 911,619 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 847,670 | 8.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,172,843 | 53.8% |
| LOAD_FAST_LOAD_FAST | 6,545,693 | 43.1% |
| SWAP | 359,732 | 2.4% |
| STORE_FAST_LOAD_FAST | 87,960 | 0.6% |
| STORE_ATTR_SLOT | 17,067 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,885,696 | 32.2% |
| LOAD_FAST_LOAD_FAST | 4,120,066 | 27.1% |
| LOAD_FAST | 2,503,466 | 16.5% |
| RETURN_CONST | 2,336,408 | 15.4% |
| LOAD_GLOBAL_BUILTIN | 704,952 | 4.6% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,407,840 | 99.2% |
| LOAD_FAST_LOAD_FAST | 7,427 | 0.5% |
| LOAD_DEREF | 1,416 | 0.1% |
| LOAD_FAST | 1,056 | 0.1% |
| STORE_ATTR | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 984,023 | 69.4% |
| EXTENDED_ARG | 431,980 | 30.4% |
| RETURN_CONST | 1,040 | 0.1% |
| LOAD_CONST | 516 | 0.0% |
| LOAD_GLOBAL_MODULE | 360 | 0.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,105,823 | 24.7% |
| SWAP | 1,027,178 | 22.9% |
| LOAD_CONST | 885,590 | 19.8% |
| LOAD_FAST_LOAD_FAST | 811,100 | 18.1% |
| LOAD_ATTR_SLOT | 504,080 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,796,864 | 40.1% |
| ENTER_EXECUTOR | 937,164 | 20.9% |
| LOAD_FAST_LOAD_FAST | 881,462 | 19.7% |
| RETURN_CONST | 189,573 | 4.2% |
| LOAD_CONST | 178,115 | 4.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 117,000 | 70.0% |
| LOAD_CONST | 41,520 | 24.9% |
| LOAD_ATTR_INSTANCE_VALUE | 7,960 | 4.8% |
| LOAD_FAST | 320 | 0.2% |
| STORE_SUBSCR | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 58,960 | 35.3% |
| LOAD_FAST_LOAD_FAST | 56,260 | 33.7% |
| LOAD_DEREF | 48,880 | 29.3% |
| RETURN_CONST | 1,460 | 0.9% |
| JUMP_BACKWARD | 940 | 0.6% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 440,726 | 53.0% |
| LOAD_FAST | 378,347 | 45.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8,633 | 1.0% |
| CALL | 1,000 | 0.1% |
| TO_BOOL | 800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 474,491 | 57.1% |
| POP_JUMP_IF_TRUE | 356,458 | 42.9% |
| TO_BOOL_NONE | 123 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,358,368 | 21.5% |
| LOAD_ATTR_INSTANCE_VALUE | 5,087,961 | 20.4% |
| CALL_ISINSTANCE | 4,054,527 | 16.3% |
| LOAD_ATTR_WITH_HINT | 2,593,014 | 10.4% |
| COPY | 1,920,754 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,696,668 | 79.1% |
| POP_JUMP_IF_TRUE | 5,209,463 | 20.9% |
| EXTENDED_ARG | 2,267 | 0.0% |
| UNARY_NOT | 1,060 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 571,864 | 33.2% |
| COPY | 534,001 | 31.0% |
| LOAD_FAST | 224,466 | 13.0% |
| RETURN_VALUE | 174,863 | 10.2% |
| LOAD_GLOBAL_MODULE | 97,574 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 934,206 | 54.3% |
| POP_JUMP_IF_FALSE | 784,943 | 45.6% |
| UNARY_NOT | 960 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 879,831 | 57.8% |
| LOAD_FAST | 451,302 | 29.7% |
| LOAD_ATTR_WITH_HINT | 187,502 | 12.3% |
| TO_BOOL | 940 | 0.1% |
| STORE_FAST_LOAD_FAST | 700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,509,163 | 99.2% |
| POP_JUMP_IF_TRUE | 11,877 | 0.8% |
| UNARY_NOT | 620 | 0.0% |
| EXTENDED_ARG | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 3,215,887 | 77.0% |
| LOAD_FAST | 421,533 | 10.1% |
| WITH_EXCEPT_START | 177,300 | 4.2% |
| LOAD_ATTR | 151,286 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 102,392 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,799,466 | 90.9% |
| POP_JUMP_IF_TRUE | 378,956 | 9.1% |
| EXTENDED_ARG | 380 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 284,947 | 50.4% |
| LOAD_ATTR | 87,960 | 15.6% |
| LOAD_ATTR_WITH_HINT | 80,928 | 14.3% |
| COPY | 50,180 | 8.9% |
| STORE_FAST_LOAD_FAST | 46,880 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 325,909 | 57.7% |
| POP_JUMP_IF_TRUE | 227,946 | 40.3% |
| EXTENDED_ARG | 11,220 | 2.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 40 | 66.7% |
| UNPACK_SEQUENCE | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 530,592 | 42.7% |
| CALL_FUNCTION_EX | 431,960 | 34.7% |
| RETURN_VALUE | 90,900 | 7.3% |
| END_SEND | 88,246 | 7.1% |
| CALL_BUILTIN_FAST | 40,880 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,159,496 | 93.3% |
| STORE_FAST | 83,700 | 6.7% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 890,451 | 27.0% |
| FOR_ITER | 822,628 | 24.9% |
| CALL_FUNCTION_EX | 615,920 | 18.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 353,806 | 10.7% |
| FOR_ITER_LIST | 137,285 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 3,112,177 | 94.3% |
| STORE_FAST | 98,781 | 3.0% |
| LOAD_FAST_LOAD_FAST | 87,980 | 2.7% |
| LOAD_FAST | 2,246 | 0.1% |
| STORE_DEREF | 200 | 0.0% |


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
|     deferred | 3,623,079 | 26.0% |
|          hit | 10,278,121 | 73.8% |
|         miss | 6,893 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,705 | 22.1% |
| Failure | 16,631 | 77.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 4,042 | 24.3% |
| or | 2,324 | 14.0% |
| multiply different types | 2,311 | 13.9% |
| add other | 1,714 | 10.3% |
| true divide different types | 1,700 | 10.2% |
| remainder | 920 | 5.5% |
| add different types | 869 | 5.2% |
| subtract different types | 856 | 5.1% |
| true divide other | 448 | 2.7% |
| true divide float | 400 | 2.4% |
| floor divide | 260 | 1.6% |
| lshift | 200 | 1.2% |
| power | 200 | 1.2% |
| subtract other | 160 | 1.0% |
| rshift | 127 | 0.8% |
| and other | 80 | 0.5% |
| and different types | 20 | 0.1% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> specialization stats for BINARY_OP_INPLACE_ADD_UNICODE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|         miss | 220 | 0.2% |


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
|     deferred | 1,428,096 | 9.6% |
|          hit | 13,480,325 | 90.4% |
|         miss | 1,620 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,802 | 49.8% |
| Failure | 4,832 | 50.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 3,229 | 66.8% |
| buffer int | 983 | 20.3% |
| code complex parameters | 400 | 8.3% |
| out of range | 200 | 4.1% |
| list slice | 20 | 0.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,077,767 | 23.5% |
|          hit | 87,436,631 | 76.0% |
|         miss | 441,312 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 58,379 | 45.4% |
| Failure | 70,152 | 54.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 16,105 | 23.0% |
| cfunc noargs | 13,814 | 19.7% |
| class no vectorcall | 8,408 | 12.0% |
| meth descr varargs | 5,287 | 7.5% |
| meth descr method fastcall keywords | 4,094 | 5.8% |
| meth descr varargs keywords | 4,051 | 5.8% |
| cfunc varargs keywords | 4,043 | 5.8% |
| cfunc varargs | 3,867 | 5.5% |
| other | 3,863 | 5.5% |
| no dict | 2,280 | 3.3% |
| class mutable | 1,400 | 2.0% |
| wrong number arguments | 1,340 | 1.9% |
| operator wrapper | 620 | 0.9% |
| init not simple | 580 | 0.8% |
| cmethod | 260 | 0.4% |
| init not python | 100 | 0.1% |
| str | 20 | 0.0% |
| method wrapper | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,449,436 | 8.6% |
|          hit | 15,384,926 | 91.2% |
|         miss | 27,245 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,017 | 49.1% |
| Failure | 6,239 | 50.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 2,003 | 32.1% |
| long float | 1,035 | 16.6% |
| baseobject | 1,017 | 16.3% |
| big int | 824 | 13.2% |
| different types | 720 | 11.5% |
| other | 520 | 8.3% |
| tuple | 80 | 1.3% |
| bool | 40 | 0.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,058,604 | 35.6% |
|          hit | 10,943,416 | 64.3% |
|         miss | 400 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,700 | 16.8% |
| Failure | 18,264 | 83.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 9,108 | 49.9% |
| dict items | 5,045 | 27.6% |
| zip | 854 | 4.7% |
| dict keys | 820 | 4.5% |
| dict values | 740 | 4.1% |
| other | 480 | 2.6% |
| enumerate | 377 | 2.1% |
| itertools | 360 | 2.0% |
| bytes | 200 | 1.1% |
| reversed list | 140 | 0.8% |
| map | 120 | 0.7% |
| ascii string | 20 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,377,647 | 10.7% |
|        deopt | 357,054 | 0.2% |
|          hit | 168,261,683 | 88.3% |
|         miss | 2,009,814 | 1.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 118,689 | 65.0% |
| Failure | 63,916 | 35.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 19,345 | 30.3% |
| method | 17,909 | 28.0% |
| metaclass attribute | 7,931 | 12.4% |
| not managed dict | 7,800 | 12.2% |
| module attr not found | 2,340 | 3.7% |
| shadowed | 2,101 | 3.3% |
| overridden | 1,445 | 2.3% |
| class attr descriptor | 1,280 | 2.0% |
| mutable class | 1,040 | 1.6% |
| non object slot | 825 | 1.3% |
| non overriding descriptor | 820 | 1.3% |
| class method obj | 540 | 0.8% |
| builtin class method | 200 | 0.3% |
| class attr simple | 200 | 0.3% |
| not in keys | 80 | 0.1% |
| property | 60 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 55,314 | 0.1% |
|        deopt | 1,060 | 0.0% |
|          hit | 79,939,268 | 99.8% |
|         miss | 11,780 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 54,948 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 900 | 0.1% |
|          hit | 644,213 | 99.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 940 | 100.0% |
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
|     deferred | 511,565 | 46.1% |
|          hit | 594,126 | 53.5% |
|         miss | 240 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,611 | 43.3% |
| Failure | 2,110 | 56.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 1,870 | 88.6% |
| dict keys | 240 | 11.4% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,002,339 | 3.6% |
|          hit | 26,227,501 | 93.0% |
|         miss | 918,735 | 3.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 38,055 | 82.7% |
| Failure | 7,940 | 17.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 3,420 | 43.1% |
| property | 1,440 | 18.1% |
| overridden | 1,080 | 13.6% |
| method | 740 | 9.3% |
| not in keys | 480 | 6.0% |
| class attr simple | 360 | 4.5% |
| not managed dict | 160 | 2.0% |
| overriding descriptor | 140 | 1.8% |
| no dict | 120 | 1.5% |


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
|     deferred | 536,703 | 10.3% |
|          hit | 4,648,136 | 89.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,620 | 65.2% |
| Failure | 1,936 | 34.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 1,140 | 58.9% |
| py simple | 776 | 40.1% |
| other | 20 | 1.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,527,802 | 20.2% |
|          hit | 33,708,741 | 79.7% |
|         miss | 17,615 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 18,344 | 46.3% |
| Failure | 21,315 | 53.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 6,343 | 29.8% |
| set | 5,740 | 26.9% |
| tuple | 3,220 | 15.1% |
| sequence | 2,541 | 11.9% |
| mapping | 1,194 | 5.6% |
| bytes | 895 | 4.2% |
| float | 868 | 4.1% |
| other | 300 | 1.4% |
| bytearray | 194 | 0.9% |
| number | 20 | 0.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,927 | 0.1% |
|          hit | 4,544,700 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,581 | 90.8% |
| Failure | 260 | 9.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| iterator | 260 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 890,077,326 | 56.1% |
| Not specialized | 161,077,747 | 10.2% |
| Specialized hits | 532,284,632 | 33.5% |
| Specialized misses | 3,441,238 | 0.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 27,077,767 | 38.3% |
| LOAD_ATTR | 20,377,647 | 28.8% |
| TO_BOOL | 8,527,802 | 12.1% |
| FOR_ITER | 6,058,604 | 8.6% |
| BINARY_OP | 3,623,079 | 5.1% |
| COMPARE_OP | 1,449,436 | 2.1% |
| BINARY_SUBSCR | 1,428,096 | 2.0% |
| STORE_ATTR | 1,002,339 | 1.4% |
| STORE_SUBSCR | 536,703 | 0.8% |
| SEND | 511,565 | 0.7% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,145,011 | 33.2% |
| STORE_ATTR_SLOT | 909,707 | 26.4% |
| LOAD_ATTR_INSTANCE_VALUE | 370,318 | 10.7% |
| LOAD_ATTR_METHOD_NO_DICT | 366,948 | 10.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 181,835 | 5.3% |
| CALL_PY_EXACT_ARGS | 114,306 | 3.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 92,503 | 2.7% |
| LOAD_ATTR_WITH_HINT | 59,313 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 40,434 | 1.2% |
| LOAD_ATTR_MODULE | 35,300 | 1.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 25,423,566 | 33.6% |
| Calls to Python functions inlined | 50,328,541 | 66.4% |
| Calls via PyEval_EvalFrame (total) | 25,423,566 | 33.6% |
| Calls via PyEval_EvalFrame (vector) | 23,719,228 | 31.3% |
| Calls via PyEval_EvalFrame (generator) | 1,704,338 | 2.2% |
| Calls via PyEval_EvalFrame (legacy) | 640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 23,717,648 | 31.3% |
| Calls via PyEval_EvalFrame (build class) | 940 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 3,347,636 | 4.4% |
| Calls via PyEval_EvalFrame (function ex) | 5,768,282 | 7.6% |
| Calls via PyEval_EvalFrame (api) | 5,270,166 | 7.0% |
| Calls via PyEval_EvalFrame (method) | 1,476,571 | 1.9% |
| Frame objects created | 1,438,868 | 1.9% |
| Frames pushed | 38,796,122 | 51.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 100,657,072 | 47.9% |
| Frees to freelist | 101,028,762 |  |
| Allocations | 109,509,637 | 52.1% |
| Allocations to 512 bytes | 108,319,620 | 51.5% |
| Allocations to 4 kbytes | 917,003 | 0.4% |
| Allocations over 4 kbytes | 273,014 | 0.1% |
| Frees | 102,856,399 |  |
| New values | 297,393 |  |
| Interpreter increfs | 797,670,892 | 74.9% |
| Interpreter decrefs | 905,079,786 | 73.0% |
| Increfs | 266,781,597 | 25.1% |
| Decrefs | 335,508,411 | 27.0% |
| Materialize dict (on request) | 2,560 | 0.9% |
| Materialize dict (new key) | 240 | 0.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 2,520 | 0.8% |
| Method cache hits | 24,055,267 |  |
| Method cache misses | 361,145 |  |
| Method cache collisions | 473,719 |  |
| Method cache dunder hits | 34,458,710 |  |
| Method cache dunder misses | 116,556 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 8,637 | 598,439 | 60,750,118 |
| 1 | 782 | 269,256 | 39,618,642 |
| 2 | 80 | 37,038 | 88,346,575 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 4,417 |  |
| Traces created | 4,107 | 93.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 73 | 1.7% |
| Trace too long | 306 | 6.9% |
| Trace too short | 310 | 7.0% |
| Inner loop found | 80 | 1.8% |
| Recursive call | 0 | 0.0% |
| Traces executed | 11,315,384 |  |
| Uops executed | 204,088,711 | 18.04 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 0.5% |
| <= 16 | 200 | 4.9% |
| <= 32 | 1,672 | 40.7% |
| <= 64 | 1,183 | 28.8% |
| <= 128 | 1,032 | 25.1% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 40 | 1.0% |
| <= 8 | 260 | 6.3% |
| <= 16 | 1,266 | 30.8% |
| <= 32 | 1,449 | 35.3% |
| <= 64 | 746 | 18.2% |
| <= 128 | 346 | 8.4% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 180 | 0.0% |
| <= 2 | 5,360,102 | 47.4% |
| <= 4 | 294,719 | 2.6% |
| <= 8 | 168,892 | 1.5% |
| <= 16 | 1,577,880 | 13.9% |
| <= 32 | 1,789,709 | 15.8% |
| <= 64 | 1,932,010 | 17.1% |
| <= 128 | 178,801 | 1.6% |
| <= 256 | 1,369 | 0.0% |
| <= 512 | 616 | 0.0% |
| <= 1,024 | 1,379 | 0.0% |
| <= 2,048 | 3,723 | 0.0% |
| <= 4,096 | 4,264 | 0.0% |
| <= 8,192 | 1,740 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 29,862,522 | 14.6% | 14.6% |  |
| LOAD_FAST | 25,961,466 | 12.7% | 27.4% |  |
| _CHECK_VALIDITY | 23,757,203 | 11.6% | 39.0% |  |
| _GUARD_TYPE_VERSION | 12,929,083 | 6.3% | 45.3% | 1.7% |
| STORE_FAST | 11,771,545 | 5.8% | 51.1% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 5,637,886 | 2.8% | 53.9% |  |
| _GUARD_IS_FALSE_POP | 5,218,065 | 2.6% | 56.4% | 4.2% |
| _FOR_ITER_TIER_TWO | 5,079,468 | 2.5% | 58.9% |  |
| _EXIT_TRACE | 4,736,722 | 2.3% | 61.2% |  |
| LOAD_CONST | 3,473,498 | 1.7% | 62.9% |  |
| _GUARD_GLOBALS_VERSION | 3,304,940 | 1.6% | 64.5% | 0.3% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 3,266,770 | 1.6% | 66.1% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 3,266,770 | 1.6% | 67.7% |  |
| _ITER_CHECK_LIST | 2,710,272 | 1.3% | 69.1% | 0.0% |
| _GUARD_NOT_EXHAUSTED_LIST | 2,710,092 | 1.3% | 70.4% | 46.9% |
| _LOAD_ATTR_SLOT | 2,553,637 | 1.3% | 71.7% |  |
| TO_BOOL_BOOL | 2,446,592 | 1.2% | 72.9% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 2,185,604 | 1.1% | 73.9% | 54.6% |
| _ITER_CHECK_TUPLE | 2,185,604 | 1.1% | 75.0% |  |
| _LOAD_GLOBAL_MODULE | 2,144,404 | 1.1% | 76.0% |  |
| _CHECK_PEP_523 | 2,143,890 | 1.1% | 77.1% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 2,143,890 | 1.1% | 78.1% |  |
| _CHECK_STACK_SPACE | 2,143,890 | 1.1% | 79.2% |  |
| _INIT_CALL_PY_EXACT_ARGS | 2,143,890 | 1.1% | 80.2% |  |
| _PUSH_FRAME | 2,143,890 | 1.1% | 81.3% |  |
| _SAVE_RETURN_OFFSET | 2,143,890 | 1.1% | 82.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,674,779 | 0.8% | 83.2% | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,645,742 | 0.8% | 84.0% |  |
| LOAD_DEREF | 1,585,125 | 0.8% | 84.8% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 1,548,531 | 0.8% | 85.5% | 16.1% |
| _ITER_CHECK_RANGE | 1,548,531 | 0.8% | 86.3% |  |
| _JUMP_TO_TOP | 1,499,156 | 0.7% | 87.0% |  |
| _ITER_NEXT_LIST | 1,438,293 | 0.7% | 87.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,397,667 | 0.7% | 88.4% |  |
| _GUARD_IS_TRUE_POP | 1,394,286 | 0.7% | 89.1% | 17.3% |
| _ITER_NEXT_RANGE | 1,299,271 | 0.6% | 89.7% |  |
| _GUARD_BUILTINS_VERSION | 1,150,316 | 0.6% | 90.3% | 0.6% |
| _LOAD_GLOBAL_BUILTINS | 1,143,056 | 0.6% | 90.8% |  |
| _LOAD_ATTR | 1,111,866 | 0.5% | 91.4% |  |
| _ITER_NEXT_TUPLE | 992,491 | 0.5% | 91.9% |  |
| POP_TOP | 814,316 | 0.4% | 92.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 801,480 | 0.4% | 92.7% |  |
| COMPARE_OP_STR | 789,586 | 0.4% | 93.0% |  |
| _CHECK_ATTR_WITH_HINT | 759,231 | 0.4% | 93.4% |  |
| _LOAD_ATTR_WITH_HINT | 759,231 | 0.4% | 93.8% |  |
| BINARY_SUBSCR_DICT | 732,615 | 0.4% | 94.2% |  |
| CONTAINS_OP | 731,218 | 0.4% | 94.5% |  |
| TO_BOOL_STR | 672,646 | 0.3% | 94.8% |  |
| GET_ITER | 562,914 | 0.3% | 95.1% |  |
| _GUARD_IS_NOT_NONE_POP | 559,210 | 0.3% | 95.4% | 0.3% |
| _TO_BOOL | 538,313 | 0.3% | 95.7% |  |
| RESUME_CHECK | 486,587 | 0.2% | 95.9% | 0.0% |
| IS_OP | 471,720 | 0.2% | 96.1% |  |
| _GUARD_KEYS_VERSION | 402,601 | 0.2% | 96.3% | 8.7% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 402,601 | 0.2% | 96.5% |  |
| _COMPARE_OP | 397,986 | 0.2% | 96.7% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 367,581 | 0.2% | 96.9% |  |
| BUILD_TUPLE | 365,210 | 0.2% | 97.1% |  |
| PUSH_NULL | 362,541 | 0.2% | 97.2% |  |
| MAKE_CELL | 300,825 | 0.1% | 97.4% |  |
| _BINARY_OP | 294,665 | 0.1% | 97.5% |  |
| BUILD_LIST | 280,480 | 0.1% | 97.7% |  |
| TO_BOOL_INT | 267,108 | 0.1% | 97.8% |  |
| _GUARD_IS_NONE_POP | 260,029 | 0.1% | 97.9% | 31.6% |
| LIST_APPEND | 241,106 | 0.1% | 98.1% |  |
| CALL_BUILTIN_CLASS | 241,060 | 0.1% | 98.2% |  |
| CALL_TYPE_1 | 198,560 | 0.1% | 98.3% |  |
| STORE_SUBSCR_DICT | 188,223 | 0.1% | 98.4% |  |
| MAP_ADD | 182,056 | 0.1% | 98.5% |  |
| MAKE_FUNCTION | 166,080 | 0.1% | 98.5% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 144,270 | 0.1% | 98.6% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 144,270 | 0.1% | 98.7% |  |
| _GUARD_BOTH_INT | 139,727 | 0.1% | 98.7% | 0.2% |
| _BINARY_SUBSCR | 135,852 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 129,394 | 0.1% | 98.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 125,460 | 0.1% | 98.9% |  |
| _CHECK_ATTR_MODULE | 124,737 | 0.1% | 99.0% |  |
| _LOAD_ATTR_MODULE | 124,737 | 0.1% | 99.1% |  |
| _GUARD_BOTH_UNICODE | 123,040 | 0.1% | 99.1% |  |
| _BINARY_OP_ADD_UNICODE | 123,040 | 0.1% | 99.2% |  |
| COMPARE_OP_INT | 112,584 | 0.1% | 99.2% | 9.6% |
| UNPACK_SEQUENCE_TUPLE | 110,862 | 0.1% | 99.3% |  |
| CALL_ISINSTANCE | 102,820 | 0.1% | 99.3% |  |
| CALL_LEN | 102,316 | 0.1% | 99.4% |  |
| CALL_INTRINSIC_1 | 100,066 | 0.0% | 99.4% |  |
| LIST_EXTEND | 100,066 | 0.0% | 99.5% |  |
| CALL_BUILTIN_FAST | 92,240 | 0.0% | 99.5% |  |
| BEFORE_WITH | 88,006 | 0.0% | 99.6% |  |
| SET_FUNCTION_ATTRIBUTE | 87,200 | 0.0% | 99.6% |  |
| UNARY_NEGATIVE | 86,800 | 0.0% | 99.7% |  |
| _STORE_ATTR_SLOT | 86,800 | 0.0% | 99.7% |  |
| COPY_FREE_VARS | 83,480 | 0.0% | 99.7% |  |
| _BINARY_OP_ADD_INT | 79,839 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_LIST_INT | 72,026 | 0.0% | 99.8% |  |
| COPY | 64,201 | 0.0% | 99.8% |  |
| COMPARE_OP_FLOAT | 56,230 | 0.0% | 99.9% | 2.8% |
| _BINARY_OP_SUBTRACT_INT | 54,932 | 0.0% | 99.9% |  |
| SWAP | 40,300 | 0.0% | 99.9% |  |
| DELETE_FAST | 37,145 | 0.0% | 99.9% |  |
| CALL_BUILTIN_O | 18,979 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_STR_INT | 14,180 | 0.0% | 100.0% | 2.8% |
| BUILD_MAP | 13,266 | 0.0% | 100.0% |  |
| DICT_MERGE | 13,266 | 0.0% | 100.0% |  |
| BINARY_SLICE | 8,010 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 7,600 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 7,290 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 7,170 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 7,050 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 5,000 | 0.0% | 100.0% |  |
| BUILD_STRING | 5,000 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 4,676 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 4,020 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 3,100 | 0.0% | 100.0% |  |
| _POP_FRAME | 1,626 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 1,120 | 0.0% | 100.0% | 94.6% |
| _STORE_SUBSCR | 1,080 | 0.0% | 100.0% |  |
| CALL_STR_1 | 420 | 0.0% | 100.0% |  |
| STORE_DEREF | 400 | 0.0% | 100.0% |  |
| UNARY_NOT | 200 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 160 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 160 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 66 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 60 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 766 |
| FOR_ITER_GEN | 310 |
| CALL_PY_WITH_DEFAULTS | 280 |
| CALL_KW | 251 |
| YIELD_VALUE | 140 |
| CALL_FUNCTION_EX | 100 |
| LOAD_ATTR_PROPERTY | 80 |
| CALL_LIST_APPEND | 72 |
| CALL_ALLOC_AND_ENTER_INIT | 40 |
| BINARY_SUBSCR_GETITEM | 20 |


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
