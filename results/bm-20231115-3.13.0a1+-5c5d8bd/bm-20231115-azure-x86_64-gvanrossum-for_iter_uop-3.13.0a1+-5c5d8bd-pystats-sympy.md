
# Pystats results

- benchmark: sympy
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 976,731,693 | 16.4% | 16.4% |  |
| STORE_FAST | 359,053,297 | 6.0% | 22.4% |  |
| POP_JUMP_IF_FALSE | 291,828,059 | 4.9% | 27.3% |  |
| RESUME_CHECK | 258,067,014 | 4.3% | 31.7% |  |
| LOAD_FAST_LOAD_FAST | 253,999,954 | 4.3% | 36.0% |  |
| LOAD_GLOBAL_BUILTIN | 233,835,398 | 3.9% | 39.9% | 0.0% |
| LOAD_CONST | 191,427,574 | 3.2% | 43.1% |  |
| RETURN_VALUE | 177,422,525 | 3.0% | 46.1% |  |
| TO_BOOL_BOOL | 172,698,030 | 2.9% | 49.0% | 0.1% |
| JUMP_BACKWARD | 156,700,286 | 2.6% | 51.6% |  |
| LOAD_GLOBAL_MODULE | 145,748,012 | 2.4% | 54.1% | 0.0% |
| INTERPRETER_EXIT | 127,434,178 | 2.1% | 56.2% |  |
| LOAD_ATTR | 121,724,501 | 2.0% | 58.3% |  |
| STORE_FAST_STORE_FAST | 105,852,260 | 1.8% | 60.0% |  |
| FOR_ITER | 103,928,384 | 1.7% | 61.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 103,899,059 | 1.7% | 63.5% |  |
| LOAD_ATTR_SLOT | 96,037,040 | 1.6% | 65.1% | 38.1% |
| LOAD_ATTR_METHOD_NO_DICT | 91,693,507 | 1.5% | 66.7% | 10.1% |
| POP_JUMP_IF_TRUE | 80,540,168 | 1.4% | 68.0% |  |
| LOAD_DEREF | 68,798,563 | 1.2% | 69.2% |  |
| CALL_PY_EXACT_ARGS | 68,088,709 | 1.1% | 70.3% | 11.5% |
| CALL_ISINSTANCE | 67,460,589 | 1.1% | 71.5% |  |
| FOR_ITER_LIST | 62,891,933 | 1.1% | 72.5% | 1.2% |
| POP_TOP | 61,723,685 | 1.0% | 73.6% |  |
| PUSH_NULL | 60,711,279 | 1.0% | 74.6% |  |
| GET_ITER | 60,035,704 | 1.0% | 75.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 58,865,015 | 1.0% | 76.6% | 28.9% |
| RETURN_CONST | 57,260,585 | 1.0% | 77.5% |  |
| BUILD_TUPLE | 56,960,507 | 1.0% | 78.5% |  |
| CONTAINS_OP | 52,162,936 | 0.9% | 79.4% |  |
| COMPARE_OP_INT | 51,173,525 | 0.9% | 80.2% | 1.1% |
| IS_OP | 47,820,342 | 0.8% | 81.0% |  |
| SWAP | 45,313,754 | 0.8% | 81.8% |  |
| CALL_BUILTIN_FAST | 43,498,092 | 0.7% | 82.5% |  |
| POP_JUMP_IF_NONE | 41,248,768 | 0.7% | 83.2% |  |
| CALL_BUILTIN_O | 39,859,317 | 0.7% | 83.9% | 6.7% |
| COMPARE_OP | 38,549,255 | 0.6% | 84.5% |  |
| BINARY_OP | 35,326,096 | 0.6% | 85.1% |  |
| FOR_ITER_TUPLE | 34,846,177 | 0.6% | 85.7% | 2.3% |
| BUILD_MAP | 33,797,154 | 0.6% | 86.3% |  |
| NOP | 33,474,808 | 0.6% | 86.8% |  |
| COPY_FREE_VARS | 31,777,193 | 0.5% | 87.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 31,052,810 | 0.5% | 87.9% | 0.4% |
| BINARY_SUBSCR_LIST_INT | 30,185,857 | 0.5% | 88.4% | 0.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,538,994 | 0.5% | 88.9% | 21.9% |
| CALL_LEN | 28,098,916 | 0.5% | 89.4% |  |
| CALL_FUNCTION_EX | 28,013,721 | 0.5% | 89.8% |  |
| LOAD_ATTR_PROPERTY | 28,007,361 | 0.5% | 90.3% | 14.7% |
| CALL | 26,856,025 | 0.5% | 90.8% |  |
| BINARY_SUBSCR | 24,062,948 | 0.4% | 91.2% |  |
| CALL_LIST_APPEND | 24,015,945 | 0.4% | 91.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 23,524,529 | 0.4% | 92.0% | 0.2% |
| DICT_MERGE | 23,272,675 | 0.4% | 92.4% |  |
| YIELD_VALUE | 23,083,609 | 0.4% | 92.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 22,087,203 | 0.4% | 93.1% | 65.4% |
| BUILD_LIST | 21,626,600 | 0.4% | 93.5% |  |
| EXTENDED_ARG | 21,424,448 | 0.4% | 93.8% |  |
| STORE_SUBSCR_LIST_INT | 20,342,258 | 0.3% | 94.2% |  |
| TO_BOOL_INT | 19,694,404 | 0.3% | 94.5% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,153,848 | 0.3% | 94.8% |  |
| LOAD_FAST_AND_CLEAR | 16,788,759 | 0.3% | 95.1% |  |
| CALL_TYPE_1 | 16,713,355 | 0.3% | 95.4% |  |
| COMPARE_OP_STR | 14,565,262 | 0.2% | 95.6% |  |
| RETURN_GENERATOR | 14,324,071 | 0.2% | 95.9% |  |
| MAKE_FUNCTION | 14,279,416 | 0.2% | 96.1% |  |
| BINARY_OP_ADD_INT | 12,978,289 | 0.2% | 96.3% |  |
| TO_BOOL | 12,925,315 | 0.2% | 96.5% |  |
| FOR_ITER_RANGE | 12,132,122 | 0.2% | 96.8% |  |
| CALL_KW | 10,673,485 | 0.2% | 96.9% |  |
| SET_FUNCTION_ATTRIBUTE | 10,404,748 | 0.2% | 97.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,177,438 | 0.2% | 97.3% | 0.0% |
| CALL_BUILTIN_CLASS | 9,149,576 | 0.2% | 97.4% |  |
| STORE_ATTR_SLOT | 9,060,312 | 0.2% | 97.6% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,996,242 | 0.2% | 97.7% | 0.1% |
| IMPORT_FROM | 8,955,401 | 0.2% | 97.9% |  |
| STORE_DEREF | 8,695,584 | 0.1% | 98.0% |  |
| MAP_ADD | 7,867,339 | 0.1% | 98.1% |  |
| IMPORT_NAME | 7,760,111 | 0.1% | 98.3% |  |
| LIST_APPEND | 6,188,659 | 0.1% | 98.4% |  |
| MAKE_CELL | 6,049,895 | 0.1% | 98.5% |  |
| JUMP_FORWARD | 5,902,525 | 0.1% | 98.6% |  |
| CALL_TUPLE_1 | 5,851,758 | 0.1% | 98.7% | 0.0% |
| STORE_FAST_LOAD_FAST | 5,346,067 | 0.1% | 98.8% |  |
| UNARY_NOT | 5,307,705 | 0.1% | 98.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,733 | 0.1% | 98.9% | 0.1% |
| COPY | 4,908,493 | 0.1% | 99.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 4,647,773 | 0.1% | 99.1% | 0.2% |
| CALL_PY_WITH_DEFAULTS | 4,598,059 | 0.1% | 99.2% | 0.7% |
| STORE_SUBSCR | 3,428,919 | 0.1% | 99.2% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,986 | 0.1% | 99.3% | 0.0% |
| BINARY_SUBSCR_DICT | 3,348,967 | 0.1% | 99.4% |  |
| BINARY_OP_MULTIPLY_INT | 2,771,534 | 0.0% | 99.4% | 0.0% |
| TO_BOOL_NONE | 2,709,416 | 0.0% | 99.4% | 8.4% |
| BINARY_OP_SUBTRACT_INT | 2,486,428 | 0.0% | 99.5% |  |
| TO_BOOL_LIST | 2,302,636 | 0.0% | 99.5% | 0.5% |
| STORE_SUBSCR_DICT | 2,283,408 | 0.0% | 99.6% |  |
| LOAD_SUPER_ATTR_METHOD | 1,814,158 | 0.0% | 99.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,644,161 | 0.0% | 99.6% | 20.4% |
| UNPACK_SEQUENCE_TUPLE | 1,630,809 | 0.0% | 99.7% |  |
| LOAD_FAST_CHECK | 1,578,349 | 0.0% | 99.7% |  |
| LIST_EXTEND | 1,349,345 | 0.0% | 99.7% |  |
| CALL_INTRINSIC_1 | 1,349,305 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,570 | 0.0% | 99.8% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,182,029 | 0.0% | 99.8% |  |
| SEND_GEN | 1,029,804 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,424 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,424 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,424 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 613,489 | 0.0% | 99.9% |  |
| STORE_ATTR | 591,486 | 0.0% | 99.9% |  |
| BINARY_SLICE | 569,058 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 563,580 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,657 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,384 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 519,760 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 284,520 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 284,480 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 228,490 | 0.0% | 100.0% | 36.3% |
| FOR_ITER_GEN | 191,478 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,929 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 180,095 | 0.0% | 100.0% |  |
| LOAD_NAME | 178,820 | 0.0% | 100.0% |  |
| STORE_NAME | 167,980 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,262 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 141,900 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,297 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,920 | 0.0% | 100.0% | 0.2% |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| BUILD_SET | 50,507 | 0.0% | 100.0% |  |
| RESUME | 47,579 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,866 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,556 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,500 | 0.0% | 100.0% |  |
| SET_ADD | 19,280 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 5,980 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,010 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| STORE_SLICE | 2,160 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,205 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 480 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 300 | 0.0% | 100.0% | 20.0% |
| DELETE_NAME | 120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 60 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 20 | 0.0% | 100.0% |  |
| DICT_UPDATE | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 196,237,502 | 3.3% | 3.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 162,935,050 | 2.7% | 6.0% |
| RESUME_CHECK LOAD_FAST | 115,550,112 | 1.9% | 8.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 113,720,873 | 1.9% | 9.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 111,647,018 | 1.9% | 11.8% |
| CACHE RESUME_CHECK | 99,223,788 | 1.7% | 13.4% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 99,125,789 | 1.7% | 15.1% |
| LOAD_FAST LOAD_ATTR_SLOT | 95,203,666 | 1.6% | 16.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 79,141,697 | 1.3% | 18.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 78,854,939 | 1.3% | 19.4% |
| RETURN_VALUE INTERPRETER_EXIT | 72,904,414 | 1.2% | 20.6% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 71,213,514 | 1.2% | 21.8% |
| LOAD_FAST LOAD_CONST | 69,889,240 | 1.2% | 22.9% |
| JUMP_BACKWARD FOR_ITER | 68,569,356 | 1.2% | 24.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 62,550,601 | 1.1% | 25.2% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 59,845,672 | 1.0% | 26.2% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 58,003,307 | 1.0% | 27.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 57,026,812 | 1.0% | 28.1% |
| LOAD_FAST LOAD_ATTR | 55,274,868 | 0.9% | 29.0% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 54,473,878 | 0.9% | 29.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 54,444,799 | 0.9% | 30.8% |
| LOAD_FAST RETURN_VALUE | 53,599,071 | 0.9% | 31.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 50,993,842 | 0.9% | 32.6% |
| JUMP_BACKWARD FOR_ITER_LIST | 46,567,482 | 0.8% | 33.4% |
| PUSH_NULL LOAD_FAST | 46,541,861 | 0.8% | 34.2% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 45,409,062 | 0.8% | 34.9% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 44,302,401 | 0.7% | 35.7% |
| FOR_ITER_LIST STORE_FAST | 43,133,036 | 0.7% | 36.4% |
| STORE_FAST_STORE_FAST LOAD_FAST | 41,989,509 | 0.7% | 37.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,291,633 | 0.7% | 37.8% |
| LOAD_CONST LOAD_CONST | 40,446,629 | 0.7% | 38.5% |
| RETURN_VALUE STORE_FAST | 38,560,354 | 0.6% | 39.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 38,017,243 | 0.6% | 39.8% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 37,718,799 | 0.6% | 40.4% |
| LOAD_ATTR STORE_FAST | 36,818,770 | 0.6% | 41.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 35,900,105 | 0.6% | 41.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 35,531,095 | 0.6% | 42.2% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 34,399,601 | 0.6% | 42.8% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 34,085,215 | 0.6% | 43.4% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,433,180 | 0.6% | 43.9% |
| LOAD_FAST POP_JUMP_IF_NONE | 33,156,389 | 0.6% | 44.5% |
| RETURN_CONST INTERPRETER_EXIT | 32,284,481 | 0.5% | 45.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 31,845,389 | 0.5% | 45.6% |
| IS_OP POP_JUMP_IF_FALSE | 30,049,860 | 0.5% | 46.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 29,778,364 | 0.5% | 46.6% |
| POP_JUMP_IF_FALSE RETURN_CONST | 29,319,284 | 0.5% | 47.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,998,027 | 0.5% | 47.6% |
| LOAD_FAST PUSH_NULL | 28,420,561 | 0.5% | 48.0% |
| LOAD_FAST CALL_LEN | 27,057,562 | 0.5% | 48.5% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 26,981,778 | 0.5% | 48.9% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 26,484,875 | 0.4% | 49.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 25,639,613 | 0.4% | 49.8% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 24,718,746 | 0.4% | 50.2% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 24,532,888 | 0.4% | 50.6% |
| LOAD_CONST CALL_BUILTIN_FAST | 24,273,111 | 0.4% | 51.1% |
| BINARY_OP STORE_FAST | 24,216,850 | 0.4% | 51.5% |
| POP_TOP JUMP_BACKWARD | 24,124,411 | 0.4% | 51.9% |
| FOR_ITER_TUPLE STORE_FAST | 23,958,215 | 0.4% | 52.3% |
| DICT_MERGE CALL_FUNCTION_EX | 23,272,675 | 0.4% | 52.7% |
| BUILD_MAP LOAD_FAST | 23,183,477 | 0.4% | 53.0% |
| LOAD_FAST DICT_MERGE | 23,143,753 | 0.4% | 53.4% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 22,689,076 | 0.4% | 53.8% |
| LOAD_ATTR_SLOT STORE_FAST | 22,510,675 | 0.4% | 54.2% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 22,299,955 | 0.4% | 54.6% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 22,288,401 | 0.4% | 54.9% |
| YIELD_VALUE INTERPRETER_EXIT | 22,237,543 | 0.4% | 55.3% |
| STORE_FAST_STORE_FAST LOAD_DEREF | 22,130,998 | 0.4% | 55.7% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_BUILTIN | 22,009,949 | 0.4% | 56.1% |
| COPY_FREE_VARS RESUME_CHECK | 21,816,786 | 0.4% | 56.4% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 21,658,516 | 0.4% | 56.8% |
| LOAD_FAST TO_BOOL_BOOL | 21,619,970 | 0.4% | 57.2% |
| LOAD_FAST GET_ITER | 21,617,377 | 0.4% | 57.5% |
| RESUME_CHECK NOP | 21,364,850 | 0.4% | 57.9% |
| BUILD_TUPLE RETURN_VALUE | 21,221,685 | 0.4% | 58.2% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,088,817 | 0.4% | 58.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 21,016,330 | 0.4% | 58.9% |
| LOAD_CONST COMPARE_OP_INT | 20,987,350 | 0.4% | 59.3% |
| POP_JUMP_IF_NONE JUMP_BACKWARD | 20,928,440 | 0.4% | 59.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 20,513,129 | 0.3% | 60.0% |
| COMPARE_OP POP_JUMP_IF_FALSE | 20,110,687 | 0.3% | 60.3% |
| LOAD_ATTR CONTAINS_OP | 20,047,900 | 0.3% | 60.7% |
| GET_ITER FOR_ITER | 19,999,218 | 0.3% | 61.0% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 19,938,982 | 0.3% | 61.3% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,466,544 | 0.3% | 61.7% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 19,055,863 | 0.3% | 62.0% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,850,957 | 0.3% | 62.3% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,813,195 | 0.3% | 62.6% |
| LOAD_FAST TO_BOOL_INT | 18,367,546 | 0.3% | 62.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 18,327,105 | 0.3% | 63.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 18,255,644 | 0.3% | 63.5% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 18,103,708 | 0.3% | 63.8% |
| LOAD_FAST CALL_BUILTIN_O | 17,814,134 | 0.3% | 64.1% |
| CALL_LIST_APPEND JUMP_BACKWARD | 17,343,125 | 0.3% | 64.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,273,745 | 0.3% | 64.7% |
| LOAD_ATTR IS_OP | 17,248,510 | 0.3% | 65.0% |
| LOAD_FAST BUILD_TUPLE | 17,153,342 | 0.3% | 65.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,714,215 | 0.3% | 65.6% |
| LOAD_FAST CALL_TYPE_1 | 16,590,414 | 0.3% | 65.9% |
| LOAD_FAST CALL_LIST_APPEND | 16,419,526 | 0.3% | 66.1% |
| LOAD_ATTR LOAD_FAST | 16,057,233 | 0.3% | 66.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 535,698 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,632 | 56.2% |
| RETURN_VALUE | 93,840 | 16.5% |
| GET_ITER | 54,720 | 9.6% |
| BINARY_OP | 39,120 | 6.9% |
| STORE_FAST | 18,960 | 3.3% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,160 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,223,788 | 77.7% |
| POP_TOP | 13,875,072 | 10.9% |
| COPY_FREE_VARS | 13,003,955 | 10.2% |
| MAKE_CELL | 1,509,157 | 1.2% |
| RESUME | 18,060 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,560 | 46.9% |
| RETURN_VALUE | 10,660 | 28.5% |
| CALL | 7,360 | 19.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,840 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 35,580 | 95.1% |
| STORE_FAST | 1,840 | 4.9% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,020 | 99.0% |
| BINARY_OP | 20 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,040 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 14,134,270 | 58.7% |
| LOAD_DEREF | 6,405,019 | 26.6% |
| BUILD_TUPLE | 1,822,768 | 7.6% |
| LOAD_FAST | 1,313,080 | 5.5% |
| RETURN_VALUE | 152,430 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,981,176 | 29.0% |
| LOAD_FAST | 6,876,817 | 28.6% |
| RETURN_VALUE | 6,067,347 | 25.2% |
| CALL | 912,132 | 3.8% |
| GET_ITER | 911,424 | 3.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,444 | 73.6% |
| BUILD_TUPLE | 157,300 | 17.4% |
| LOAD_GLOBAL_MODULE | 79,340 | 8.8% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,264 | 100.0% |
| EXTENDED_ARG | 160 | 0.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,900 | 61.3% |
| LOAD_FAST_LOAD_FAST | 1,200 | 38.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,840 | 59.4% |
| JUMP_BACKWARD | 1,200 | 38.7% |
| LOAD_FAST | 60 | 1.9% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 22,556 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,556 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 335,800 | 64.7% |
| SEND | 168,540 | 32.5% |
| SEND_GEN | 15,020 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 519,360 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 95,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 95,600 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 284,480 | 100.0% |
| LOAD_FAST | 20 | 0.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 141,720 | 49.8% |
| LOAD_CONST | 108,280 | 38.1% |
| LOAD_FAST | 34,520 | 12.1% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,617,377 | 36.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,456,955 | 24.1% |
| CALL | 10,953,529 | 18.2% |
| RETURN_VALUE | 4,116,875 | 6.9% |
| CALL_BUILTIN_O | 2,591,158 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 19,999,218 | 33.3% |
| CALL_PY_EXACT_ARGS | 12,995,104 | 21.6% |
| FOR_ITER_TUPLE | 9,977,815 | 16.6% |
| LOAD_FAST_AND_CLEAR | 9,198,667 | 15.3% |
| FOR_ITER_LIST | 4,579,440 | 7.6% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 346,984 | 64.2% |
| BINARY_SUBSCR | 185,800 | 34.4% |
| RETURN_VALUE | 7,520 | 1.4% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540,384 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,904,414 | 57.2% |
| RETURN_CONST | 32,284,481 | 25.3% |
| YIELD_VALUE | 22,237,543 | 17.5% |
| RETURN_GENERATOR | 7,740 | 0.0% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 2,220 | 83.5% |
| POP_TOP | 420 | 15.8% |
| STORE_GLOBAL | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,660 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,279,416 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 10,403,208 | 72.9% |
| LOAD_GLOBAL_BUILTIN | 2,651,278 | 18.6% |
| STORE_FAST | 669,662 | 4.7% |
| LOAD_FAST | 459,426 | 3.2% |
| STORE_NAME | 33,580 | 0.2% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,364,850 | 63.8% |
| POP_JUMP_IF_TRUE | 4,183,991 | 12.5% |
| STORE_FAST | 3,935,371 | 11.8% |
| POP_JUMP_IF_FALSE | 1,913,674 | 5.7% |
| POP_TOP | 1,392,137 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,288,380 | 36.7% |
| LOAD_DEREF | 10,424,271 | 31.1% |
| LOAD_GLOBAL_MODULE | 6,493,415 | 19.4% |
| LOAD_CONST | 2,608,178 | 7.8% |
| LOAD_FAST_LOAD_FAST | 912,800 | 2.7% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,432 | 45.7% |
| POP_TOP | 358,572 | 39.6% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,432 | 45.7% |
| EXTENDED_ARG | 201,460 | 22.2% |
| JUMP_BACKWARD | 159,512 | 17.6% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,130,203 | 24.5% |
| CACHE | 13,875,072 | 22.5% |
| RETURN_CONST | 9,398,987 | 15.2% |
| STORE_FAST | 5,839,945 | 9.5% |
| SWAP | 5,778,582 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 24,124,411 | 39.1% |
| RESUME_CHECK | 14,318,510 | 23.2% |
| LOAD_FAST | 7,248,473 | 11.7% |
| RETURN_VALUE | 5,302,382 | 8.6% |
| LOAD_CONST | 2,641,259 | 4.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,363 | 41.3% |
| BINARY_SUBSCR_DICT | 233,901 | 25.8% |
| RAISE_VARARGS | 115,300 | 12.7% |
| LOAD_ATTR | 95,500 | 10.5% |
| CALL_BUILTIN_CLASS | 38,560 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,164 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,820 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,420,561 | 46.8% |
| LOAD_ATTR | 14,957,035 | 24.6% |
| LOAD_DEREF | 11,929,272 | 19.6% |
| CALL_BUILTIN_FAST | 2,129,900 | 3.5% |
| LOAD_SUPER_ATTR_ATTR | 1,182,029 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,541,861 | 76.7% |
| LOAD_FAST_LOAD_FAST | 12,229,124 | 20.1% |
| LOAD_CONST | 1,723,720 | 2.8% |
| LOAD_DEREF | 128,570 | 0.2% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,879,719 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,261,611 | 29.8% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| CALL_KW | 8,000 | 0.1% |
| CACHE | 7,740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,184,417 | 71.1% |
| STORE_FAST | 2,660,492 | 18.6% |
| LOAD_FAST | 792,062 | 5.5% |
| GET_YIELD_FROM_ITER | 346,984 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,599,071 | 30.2% |
| LOAD_ATTR_SLOT | 33,433,180 | 18.8% |
| BUILD_TUPLE | 21,221,685 | 12.0% |
| RETURN_VALUE | 15,184,349 | 8.6% |
| CALL_BUILTIN_O | 11,433,025 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,904,414 | 41.1% |
| STORE_FAST | 38,560,354 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,466,544 | 11.0% |
| RETURN_VALUE | 15,184,349 | 8.6% |
| LOAD_FAST | 5,453,711 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,303,749 | 96.3% |
| BINARY_SUBSCR | 93,200 | 2.7% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.6% |
| SWAP | 5,960 | 0.2% |
| STORE_SUBSCR | 3,640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,290,669 | 96.0% |
| JUMP_BACKWARD | 116,380 | 3.4% |
| JUMP_FORWARD | 9,840 | 0.3% |
| STORE_SUBSCR | 3,640 | 0.1% |
| LOAD_FAST | 2,624 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.6% |
| LOAD_FAST | 2,208,123 | 17.1% |
| LOAD_GLOBAL_MODULE | 118,977 | 0.9% |
| LOAD_ATTR | 117,997 | 0.9% |
| RETURN_VALUE | 27,313 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,253,332 | 94.8% |
| POP_JUMP_IF_TRUE | 509,895 | 3.9% |
| UNARY_NOT | 84,151 | 0.7% |
| TO_BOOL_BOOL | 41,193 | 0.3% |
| TO_BOOL | 21,496 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 188,645 | 30.7% |
| LOAD_ATTR_SLOT | 117,485 | 19.2% |
| LOAD_ATTR | 107,040 | 17.4% |
| RETURN_VALUE | 106,160 | 17.3% |
| LOAD_FAST_LOAD_FAST | 50,689 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,983 | 21.5% |
| CALL_LIST_APPEND | 119,120 | 19.4% |
| LOAD_GLOBAL_MODULE | 106,842 | 17.4% |
| IS_OP | 106,160 | 17.3% |
| STORE_FAST | 58,137 | 9.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,733 | 64.9% |
| TO_BOOL_BOOL | 1,118,760 | 21.1% |
| TO_BOOL_LIST | 661,895 | 12.5% |
| TO_BOOL | 84,151 | 1.6% |
| TO_BOOL_INT | 166 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,527 | 66.5% |
| STORE_FAST | 882,783 | 16.6% |
| BUILD_MAP | 734,720 | 13.8% |
| COPY | 86,917 | 1.6% |
| LOAD_CONST | 68,098 | 1.3% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,766,761 | 33.3% |
| COMPARE_OP_INT | 6,308,780 | 17.9% |
| COMPARE_OP | 6,162,400 | 17.4% |
| CALL_TUPLE_1 | 4,707,321 | 13.3% |
| LOAD_FAST | 2,678,549 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,216,850 | 68.6% |
| RETURN_VALUE | 5,771,285 | 16.3% |
| BUILD_TUPLE | 1,556,880 | 4.4% |
| CALL_BUILTIN_O | 1,095,149 | 3.1% |
| LOAD_FAST | 857,912 | 2.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,297 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,517 | 97.8% |
| RETURN_VALUE | 1,840 | 1.4% |
| LOAD_CONST | 500 | 0.4% |
| LOAD_FAST | 400 | 0.3% |
| DICT_UPDATE | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,464,446 | 20.6% |
| POP_JUMP_IF_TRUE | 4,083,245 | 18.9% |
| STORE_FAST | 3,817,220 | 17.7% |
| LOAD_FAST | 2,312,283 | 10.7% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,718,523 | 54.2% |
| SWAP | 4,464,446 | 20.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,415 | 10.6% |
| LOAD_FAST | 1,414,605 | 6.5% |
| BUILD_LIST | 748,361 | 3.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,167,905 | 36.0% |
| BUILD_TUPLE | 10,998,598 | 32.5% |
| SWAP | 4,716,221 | 14.0% |
| LOAD_CONST | 1,656,800 | 4.9% |
| RESUME_CHECK | 1,285,960 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,183,477 | 68.6% |
| SWAP | 4,716,221 | 14.0% |
| STORE_FAST | 3,331,894 | 9.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 4.6% |
| CALL_FUNCTION_EX | 734,880 | 2.2% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,427 | 64.2% |
| SWAP | 18,000 | 35.6% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,427 | 64.2% |
| SWAP | 18,000 | 35.6% |
| STORE_FAST | 80 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,010 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 3,840 | 95.8% |
| BINARY_SUBSCR | 170 | 4.2% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 141,720 | 99.9% |
| LOAD_CONST | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 106,160 | 74.8% |
| LOAD_CONST | 16,000 | 11.3% |
| LOAD_FAST | 16,000 | 11.3% |
| LIST_APPEND | 3,420 | 2.4% |
| CALL | 300 | 0.2% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 25,639,613 | 45.0% |
| LOAD_FAST | 17,153,342 | 30.1% |
| LOAD_ATTR_SLOT | 5,042,304 | 8.9% |
| LOAD_ATTR | 3,034,705 | 5.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,221,685 | 37.3% |
| BUILD_MAP | 10,998,598 | 19.3% |
| LOAD_CONST | 10,426,170 | 18.3% |
| LOAD_GLOBAL_BUILTIN | 4,707,121 | 8.3% |
| CALL_LIST_APPEND | 3,231,440 | 5.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,643,360 | 35.9% |
| LOAD_FAST | 7,331,253 | 27.3% |
| LOAD_ATTR | 3,067,199 | 11.4% |
| BINARY_OP_MULTIPLY_INT | 2,291,865 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,959 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,529 | 40.8% |
| STORE_FAST | 5,844,876 | 21.8% |
| RETURN_VALUE | 4,527,051 | 16.9% |
| POP_TOP | 1,135,013 | 4.2% |
| RESUME_CHECK | 1,069,921 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 23,272,675 | 83.1% |
| LOAD_FAST | 2,317,595 | 8.3% |
| CALL_INTRINSIC_1 | 1,256,923 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |
| BINARY_OP | 201,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,601,074 | 45.0% |
| RESUME_CHECK | 11,673,700 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,872 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,348,085 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,923 | 93.2% |
| BUILD_MAP | 91,322 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,673,485 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,486 | 88.9% |
| POP_TOP | 698,059 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,819 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,088,817 | 54.7% |
| LOAD_FAST | 8,272,745 | 21.5% |
| CALL_TYPE_1 | 5,882,579 | 15.3% |
| LOAD_GLOBAL_MODULE | 1,179,753 | 3.1% |
| LOAD_CONST | 950,725 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20,110,687 | 52.2% |
| BINARY_OP | 6,162,400 | 16.0% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.0% |
| UNARY_NOT | 3,442,733 | 8.9% |
| POP_JUMP_IF_TRUE | 2,278,934 | 5.9% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 24,718,746 | 47.4% |
| LOAD_ATTR | 20,047,900 | 38.4% |
| LOAD_GLOBAL_MODULE | 5,290,214 | 10.1% |
| LOAD_DEREF | 1,536,480 | 2.9% |
| LOAD_CONST | 174,995 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 45,409,062 | 87.1% |
| POP_JUMP_IF_TRUE | 6,743,714 | 12.9% |
| STORE_FAST | 4,560 | 0.0% |
| EXTENDED_ARG | 4,480 | 0.0% |
| RETURN_VALUE | 960 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 170,080 | 59.8% |
| LOAD_FAST | 111,500 | 39.2% |
| STORE_FAST_LOAD_FAST | 2,520 | 0.9% |
| LOAD_GLOBAL_MODULE | 300 | 0.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 284,480 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,237,546 | 25.2% |
| COPY | 1,214,400 | 24.7% |
| LOAD_FAST_LOAD_FAST | 872,880 | 17.8% |
| CALL_ISINSTANCE | 525,020 | 10.7% |
| LOAD_CONST | 236,783 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,340,080 | 27.3% |
| COPY | 1,214,400 | 24.7% |
| BINARY_SUBSCR_LIST_INT | 1,208,120 | 24.6% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 19.5% |
| STORE_FAST_STORE_FAST | 55,583 | 1.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 13,003,955 | 40.9% |
| CALL_PY_EXACT_ARGS | 11,862,824 | 37.3% |
| LOAD_ATTR_PROPERTY | 5,062,287 | 15.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,202,733 | 3.8% |
| CALL_KW | 261,140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,816,786 | 68.7% |
| RETURN_GENERATOR | 9,879,719 | 31.1% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,188 | 0.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,285,120 | 98.7% |
| POP_JUMP_IF_NONE | 15,920 | 1.2% |
| FOR_ITER_LIST | 880 | 0.1% |
| STORE_FAST | 160 | 0.0% |
| POP_TOP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 643,240 | 49.4% |
| BUILD_LIST | 642,560 | 49.3% |
| LOAD_FAST | 16,060 | 1.2% |
| LOAD_GLOBAL | 200 | 0.0% |
| RERAISE | 160 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,143,753 | 99.4% |
| LOAD_DEREF | 128,922 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 23,272,675 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,678,969 | 26.5% |
| TO_BOOL_BOOL | 5,486,173 | 25.6% |
| CALL_LIST_APPEND | 4,571,191 | 21.3% |
| GET_ITER | 2,378,195 | 11.1% |
| COMPARE_OP_INT | 1,719,909 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,038,618 | 32.9% |
| JUMP_BACKWARD | 5,792,909 | 27.0% |
| FOR_ITER_LIST | 5,660,762 | 26.4% |
| FOR_ITER_TUPLE | 1,740,040 | 8.1% |
| FOR_ITER_RANGE | 642,400 | 3.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 68,569,356 | 66.0% |
| GET_ITER | 19,999,218 | 19.2% |
| SWAP | 7,638,657 | 7.3% |
| LOAD_FAST | 7,609,771 | 7.3% |
| FOR_ITER | 79,875 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 71,213,514 | 68.5% |
| STORE_FAST | 8,335,678 | 8.0% |
| SWAP | 7,602,881 | 7.3% |
| RETURN_CONST | 4,698,223 | 4.5% |
| LOAD_FAST | 4,693,808 | 4.5% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,758,591 | 86.6% |
| STORE_FAST | 982,561 | 11.0% |
| STORE_DEREF | 185,709 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,822,285 | 76.2% |
| STORE_DEREF | 2,092,516 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,760,091 | 100.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,758,591 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 17,248,510 | 36.1% |
| LOAD_FAST | 12,834,635 | 26.8% |
| LOAD_CONST | 10,976,959 | 23.0% |
| LOAD_FAST_LOAD_FAST | 5,893,719 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 539,778 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,049,860 | 62.8% |
| YIELD_VALUE | 12,819,296 | 26.8% |
| POP_JUMP_IF_TRUE | 4,907,001 | 10.3% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,399,601 | 22.0% |
| POP_TOP | 24,124,411 | 15.4% |
| POP_JUMP_IF_TRUE | 22,689,076 | 14.5% |
| POP_JUMP_IF_NONE | 20,928,440 | 13.4% |
| CALL_LIST_APPEND | 17,343,125 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 68,569,356 | 43.8% |
| FOR_ITER_LIST | 46,567,482 | 29.7% |
| FOR_ITER_TUPLE | 22,288,401 | 14.2% |
| FOR_ITER_RANGE | 10,610,493 | 6.8% |
| EXTENDED_ARG | 5,678,969 | 3.6% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 928,400 | 100.0% |
| RESUME | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 661,220 | 71.2% |
| SEND | 267,340 | 28.8% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,278,440 | 72.5% |
| POP_TOP | 734,262 | 12.4% |
| STORE_FAST_STORE_FAST | 240,720 | 4.1% |
| CALL_LIST_APPEND | 191,888 | 3.3% |
| LOAD_FAST | 146,917 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,005,876 | 67.9% |
| BUILD_MAP | 642,560 | 10.9% |
| LOAD_GLOBAL_BUILTIN | 470,050 | 8.0% |
| LOAD_FAST_LOAD_FAST | 437,114 | 7.4% |
| STORE_FAST | 119,017 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,004,226 | 48.5% |
| BUILD_TUPLE | 1,568,851 | 25.4% |
| RETURN_VALUE | 511,448 | 8.3% |
| BINARY_SUBSCR | 489,430 | 7.9% |
| BINARY_SUBSCR_LIST_INT | 396,080 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,183,699 | 99.9% |
| LOAD_NAME | 4,800 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,347,205 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,348,085 | 99.9% |
| STORE_DEREF | 880 | 0.1% |
| STORE_NAME | 180 | 0.0% |
| STORE_FAST | 160 | 0.0% |
| EXTENDED_ARG | 40 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 57,026,812 | 46.8% |
| LOAD_FAST | 55,274,868 | 45.4% |
| CALL_TYPE_1 | 4,209,481 | 3.5% |
| LOAD_ATTR_SLOT | 2,297,075 | 1.9% |
| LOAD_GLOBAL_BUILTIN | 1,905,253 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,818,770 | 30.2% |
| CONTAINS_OP | 20,047,900 | 16.5% |
| IS_OP | 17,248,510 | 14.2% |
| LOAD_FAST | 16,057,233 | 13.2% |
| PUSH_NULL | 14,957,035 | 12.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 69,889,240 | 36.5% |
| LOAD_CONST | 40,446,629 | 21.1% |
| RESUME_CHECK | 15,734,898 | 8.2% |
| BUILD_TUPLE | 10,426,170 | 5.4% |
| RETURN_CONST | 9,526,680 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,446,629 | 21.1% |
| CALL_BUILTIN_FAST | 24,273,111 | 12.7% |
| COMPARE_OP_INT | 20,987,350 | 11.0% |
| STORE_FAST | 14,709,090 | 7.7% |
| MAKE_FUNCTION | 14,279,416 | 7.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 22,130,998 | 32.2% |
| NOP | 10,424,271 | 15.2% |
| LOAD_FAST | 7,794,388 | 11.3% |
| LOAD_ATTR_SLOT | 6,405,019 | 9.3% |
| POP_JUMP_IF_FALSE | 4,653,513 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 22,299,955 | 32.4% |
| PUSH_NULL | 11,929,272 | 17.3% |
| LOAD_FAST | 9,406,152 | 13.7% |
| CALL_ISINSTANCE | 7,549,471 | 11.0% |
| BINARY_SUBSCR | 6,405,019 | 9.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 196,237,502 | 20.1% |
| LOAD_GLOBAL_BUILTIN | 162,935,050 | 16.7% |
| RESUME_CHECK | 115,550,112 | 11.8% |
| POP_JUMP_IF_FALSE | 113,720,873 | 11.6% |
| PUSH_NULL | 46,541,861 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 95,203,666 | 9.7% |
| LOAD_ATTR_METHOD_NO_DICT | 79,141,697 | 8.1% |
| LOAD_GLOBAL_MODULE | 78,854,939 | 8.1% |
| LOAD_CONST | 69,889,240 | 7.2% |
| LOAD_ATTR | 55,274,868 | 5.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,198,667 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,590,012 | 45.2% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,198,587 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,590,012 | 45.2% |
| MAKE_CELL | 160 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,557,060 | 98.7% |
| LOAD_FAST | 9,760 | 0.6% |
| POP_TOP | 7,360 | 0.5% |
| LOAD_GLOBAL_BUILTIN | 2,980 | 0.2% |
| POP_JUMP_IF_FALSE | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 1,556,980 | 98.6% |
| COMPARE_OP_INT | 7,680 | 0.5% |
| POP_JUMP_IF_NOT_NONE | 7,360 | 0.5% |
| LOAD_FAST | 3,860 | 0.2% |
| CALL_BUILTIN_CLASS | 1,360 | 0.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 62,550,601 | 24.6% |
| POP_JUMP_IF_FALSE | 34,085,215 | 13.4% |
| LOAD_GLOBAL_BUILTIN | 28,998,027 | 11.4% |
| RESUME_CHECK | 19,938,982 | 7.8% |
| STORE_FAST_STORE_FAST | 15,653,151 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 26,981,778 | 10.6% |
| BUILD_TUPLE | 25,639,613 | 10.1% |
| CONTAINS_OP | 24,718,746 | 9.7% |
| COMPARE_OP | 21,088,817 | 8.3% |
| STORE_SUBSCR_LIST_INT | 18,850,957 | 7.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,284 | 19.4% |
| LOAD_FAST | 34,217 | 18.8% |
| STORE_FAST | 26,944 | 14.8% |
| RESUME_CHECK | 10,935 | 6.0% |
| RESUME | 10,791 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,554 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,265 | 22.7% |
| LOAD_FAST | 39,619 | 21.8% |
| LOAD_ATTR | 14,087 | 7.7% |
| CALL | 9,835 | 5.4% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 46,040 | 25.7% |
| LOAD_NAME | 43,340 | 24.2% |
| POP_JUMP_IF_FALSE | 35,940 | 20.1% |
| JUMP_BACKWARD | 17,980 | 10.1% |
| CALL | 7,360 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 43,340 | 24.2% |
| CONTAINS_OP | 35,920 | 20.1% |
| PUSH_NULL | 22,600 | 12.6% |
| LOAD_CONST | 19,560 | 10.9% |
| LOAD_ATTR_METHOD_NO_DICT | 18,340 | 10.3% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,085 | 90.0% |
| LOAD_DEREF | 120 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 500 | 41.5% |
| CALL | 325 | 27.0% |
| LOAD_FAST | 180 | 14.9% |
| PUSH_NULL | 100 | 8.3% |
| LOAD_SUPER_ATTR_ATTR | 100 | 8.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,275,075 | 37.6% |
| CACHE | 1,509,157 | 24.9% |
| CALL_PY_EXACT_ARGS | 772,766 | 12.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,447 | 10.8% |
| CALL | 523,737 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,771,260 | 62.3% |
| MAKE_CELL | 2,275,075 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,854,179 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,866,999 | 100.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 111,647,018 | 38.3% |
| CONTAINS_OP | 45,409,062 | 15.6% |
| COMPARE_OP_INT | 35,531,095 | 12.2% |
| IS_OP | 30,049,860 | 10.3% |
| COMPARE_OP | 20,110,687 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 113,720,873 | 39.0% |
| LOAD_GLOBAL_BUILTIN | 58,003,307 | 19.9% |
| JUMP_BACKWARD | 34,399,601 | 11.8% |
| LOAD_FAST_LOAD_FAST | 34,085,215 | 11.7% |
| RETURN_CONST | 29,319,284 | 10.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,156,389 | 80.4% |
| BINARY_SUBSCR | 6,981,176 | 16.9% |
| LOAD_DEREF | 1,088,874 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |
| EXTENDED_ARG | 6,809 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,928,440 | 50.7% |
| LOAD_FAST_LOAD_FAST | 14,842,459 | 36.0% |
| LOAD_FAST | 2,616,333 | 6.3% |
| LOAD_GLOBAL_BUILTIN | 1,438,357 | 3.5% |
| LOAD_CONST | 1,111,452 | 2.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,714,215 | 92.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,225,093 | 6.7% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,237,626 | 67.4% |
| LOAD_FAST_LOAD_FAST | 2,026,373 | 11.2% |
| LOAD_GLOBAL_MODULE | 1,880,636 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,724 | 7.6% |
| JUMP_BACKWARD | 504,030 | 2.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 54,444,799 | 67.6% |
| TO_BOOL_INT | 9,136,782 | 11.3% |
| CONTAINS_OP | 6,743,714 | 8.4% |
| IS_OP | 4,907,001 | 6.1% |
| COMPARE_OP | 2,278,934 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,017,243 | 47.2% |
| JUMP_BACKWARD | 22,689,076 | 28.2% |
| LOAD_GLOBAL_BUILTIN | 5,309,063 | 6.6% |
| NOP | 4,183,991 | 5.2% |
| BUILD_LIST | 4,083,245 | 5.1% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,960 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,300 | 98.4% |
| COPY | 1,760 | 1.5% |
| LOAD_CONST | 160 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,319,284 | 51.2% |
| RESUME_CHECK | 10,045,720 | 17.5% |
| FOR_ITER_LIST | 5,671,974 | 9.9% |
| FOR_ITER | 4,698,223 | 8.2% |
| STORE_SUBSCR | 3,290,669 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,284,481 | 56.4% |
| LOAD_CONST | 9,526,680 | 16.6% |
| POP_TOP | 9,398,987 | 16.4% |
| TO_BOOL_BOOL | 3,462,399 | 6.0% |
| STORE_FAST | 1,541,237 | 2.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 267,340 | 60.4% |
| LOAD_CONST | 172,420 | 38.9% |
| SEND | 2,500 | 0.6% |
| SEND_GEN | 580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 257,060 | 58.0% |
| END_SEND | 168,540 | 38.1% |
| RESUME_CHECK | 10,200 | 2.3% |
| POP_TOP | 3,920 | 0.9% |
| SEND | 2,500 | 0.6% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,200 | 89.2% |
| RETURN_VALUE | 2,040 | 10.6% |
| BINARY_SUBSCR | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 19,280 | 100.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 10,403,208 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,806,975 | 94.3% |
| STORE_FAST | 307,095 | 3.0% |
| STORE_DEREF | 113,265 | 1.1% |
| LOAD_CONST | 52,360 | 0.5% |
| LOAD_GLOBAL_MODULE | 42,944 | 0.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,943 | 82.3% |
| LOAD_FAST | 98,460 | 16.6% |
| STORE_ATTR | 3,908 | 0.7% |
| SWAP | 2,159 | 0.4% |
| LOAD_DEREF | 16 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,723 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,300 | 19.7% |
| LOAD_FAST | 89,987 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 4,491,620 | 51.7% |
| IMPORT_FROM | 2,092,516 | 24.1% |
| LOAD_ATTR | 1,558,871 | 17.9% |
| STORE_FAST | 240,860 | 2.8% |
| SET_FUNCTION_ATTRIBUTE | 113,265 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,491,580 | 51.7% |
| POP_TOP | 1,906,807 | 21.9% |
| LOAD_DEREF | 1,298,380 | 14.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 5.5% |
| IMPORT_FROM | 185,709 | 2.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 43,133,036 | 12.0% |
| RETURN_VALUE | 38,560,354 | 10.7% |
| LOAD_ATTR | 36,818,770 | 10.3% |
| BINARY_OP | 24,216,850 | 6.7% |
| FOR_ITER_TUPLE | 23,958,215 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 196,237,502 | 54.7% |
| LOAD_FAST_LOAD_FAST | 62,550,601 | 17.4% |
| LOAD_GLOBAL_BUILTIN | 37,718,799 | 10.5% |
| LOAD_GLOBAL_MODULE | 18,255,644 | 5.1% |
| STORE_FAST | 9,345,140 | 2.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 4,156,330 | 77.7% |
| FOR_ITER_TUPLE | 596,776 | 11.2% |
| FOR_ITER_RANGE | 500,000 | 9.4% |
| FOR_ITER | 92,961 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,303,808 | 80.5% |
| LOAD_ATTR_PROPERTY | 318,557 | 6.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 238,654 | 4.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 157,680 | 2.9% |
| LOAD_DEREF | 107,360 | 2.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 99,125,789 | 93.6% |
| RETURN_VALUE | 3,248,210 | 3.1% |
| UNPACK_SEQUENCE_TUPLE | 1,436,146 | 1.4% |
| STORE_FAST_STORE_FAST | 771,383 | 0.7% |
| BUILD_LIST | 413,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,989,509 | 39.7% |
| LOAD_DEREF | 22,130,998 | 20.9% |
| LOAD_GLOBAL_BUILTIN | 22,009,949 | 20.8% |
| LOAD_FAST_LOAD_FAST | 15,653,151 | 14.8% |
| LOAD_GLOBAL_MODULE | 1,958,340 | 1.9% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 38,060 | 22.7% |
| MAKE_FUNCTION | 33,580 | 20.0% |
| STORE_NAME | 21,720 | 12.9% |
| CALL | 21,600 | 12.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 18,940 | 11.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 48,660 | 29.0% |
| LOAD_NAME | 46,040 | 27.4% |
| IMPORT_FROM | 26,000 | 15.5% |
| STORE_NAME | 21,720 | 12.9% |
| POP_TOP | 12,080 | 7.2% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 9,397,004 | 20.7% |
| LOAD_FAST_AND_CLEAR | 9,198,587 | 20.3% |
| FOR_ITER | 7,602,881 | 16.8% |
| BUILD_MAP | 4,716,221 | 10.4% |
| LOAD_FAST | 4,641,402 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,397,224 | 20.7% |
| STORE_FAST | 7,931,263 | 17.5% |
| FOR_ITER | 7,638,657 | 16.9% |
| POP_TOP | 5,778,582 | 12.8% |
| BUILD_MAP | 4,716,221 | 10.4% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,462 | 26.2% |
| FOR_ITER | 6,804 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 15.9% |
| LOAD_FAST | 4,000 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,684 | 46.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,431 | 23.7% |
| STORE_FAST | 8,207 | 20.6% |
| UNPACK_SEQUENCE_TUPLE | 1,145 | 2.9% |
| UNPACK_SEQUENCE | 919 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,819,296 | 55.5% |
| CALL_ISINSTANCE | 6,945,986 | 30.1% |
| LOAD_FAST | 1,146,866 | 5.0% |
| YIELD_VALUE | 677,464 | 2.9% |
| RETURN_VALUE | 423,418 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,237,543 | 96.3% |
| YIELD_VALUE | 677,464 | 2.9% |
| STORE_FAST | 162,962 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,060 | 38.0% |
| CALL | 11,115 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,106 | 12.8% |
| POP_TOP | 3,961 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,699 | 37.2% |
| LOAD_GLOBAL | 10,791 | 22.7% |
| LOAD_CONST | 8,762 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,361 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,827,528 | 91.1% |
| LOAD_FAST_LOAD_FAST | 573,747 | 4.4% |
| BINARY_SUBSCR_DICT | 422,960 | 3.3% |
| CALL_BUILTIN_CLASS | 81,137 | 0.6% |
| LOAD_FAST | 43,682 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 9,395,228 | 72.4% |
| STORE_FAST | 1,576,280 | 12.1% |
| SWAP | 1,085,059 | 8.4% |
| LOAD_CONST | 268,982 | 2.1% |
| LOAD_FAST | 201,463 | 1.6% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 480,720 | 85.3% |
| CALL_METHOD_DESCRIPTOR_O | 39,600 | 7.0% |
| LOAD_FAST | 21,480 | 3.8% |
| LOAD_FAST_LOAD_FAST | 13,440 | 2.4% |
| BINARY_SUBSCR_LIST_INT | 3,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 503,960 | 89.4% |
| RETURN_VALUE | 41,840 | 7.4% |
| CALL | 6,760 | 1.2% |
| LOAD_FAST | 6,720 | 1.2% |
| CALL_BUILTIN_FAST | 3,120 | 0.6% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,683 | 60.2% |
| LOAD_ATTR_SLOT | 723,516 | 26.1% |
| LOAD_FAST_LOAD_FAST | 283,453 | 10.2% |
| LOAD_FAST | 94,300 | 3.4% |
| BINARY_OP | 1,466 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,865 | 82.7% |
| LOAD_FAST_LOAD_FAST | 181,168 | 6.5% |
| STORE_FAST | 175,550 | 6.3% |
| LOAD_FAST | 90,188 | 3.3% |
| LOAD_GLOBAL_MODULE | 25,191 | 0.9% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 83.3% |
| BINARY_OP | 80 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 280 | 58.3% |
| BINARY_OP | 200 | 41.7% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,568,987 | 63.1% |
| LOAD_FAST_LOAD_FAST | 606,912 | 24.4% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 123,237 | 5.0% |
| BINARY_OP | 2,191 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,082,420 | 43.5% |
| STORE_FAST | 710,160 | 28.6% |
| BINARY_OP | 311,579 | 12.5% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 54,440 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,215,241 | 36.3% |
| LOAD_FAST_LOAD_FAST | 925,799 | 27.6% |
| LOAD_CONST | 642,800 | 19.2% |
| CALL_TUPLE_1 | 443,840 | 13.3% |
| RETURN_VALUE | 114,327 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 884,538 | 26.4% |
| RETURN_VALUE | 809,174 | 24.2% |
| BINARY_OP_ADD_INT | 422,960 | 12.6% |
| PUSH_NULL | 376,980 | 11.3% |
| SWAP | 318,100 | 9.5% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 80,480 | 50.5% |
| BINARY_OP_ADD_INT | 59,680 | 37.5% |
| LOAD_CONST | 14,562 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |
| BINARY_SUBSCR | 700 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,252 | 100.0% |
| RETURN_VALUE | 5 | 0.0% |
| LOAD_CONST | 5 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,981,778 | 89.4% |
| COPY | 1,208,120 | 4.0% |
| LOAD_CONST | 1,026,726 | 3.4% |
| LOAD_FAST | 570,285 | 1.9% |
| CALL_BUILTIN_CLASS | 282,408 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,459,704 | 31.3% |
| SWAP | 9,397,004 | 31.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,524,710 | 24.9% |
| LOAD_CONST | 1,208,580 | 4.0% |
| STORE_FAST | 517,328 | 1.7% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,880 | 96.8% |
| LOAD_FAST | 600 | 3.1% |
| BINARY_SUBSCR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,880 | 96.8% |
| LIST_APPEND | 620 | 3.2% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,729,636 | 97.0% |
| LOAD_FAST | 263,325 | 2.9% |
| BINARY_SUBSCR | 2,741 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,738,645 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 322,112 | 3.6% |
| BINARY_OP | 205,240 | 2.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 77,660 | 81.0% |
| LOAD_FAST_LOAD_FAST | 16,820 | 17.5% |
| LOAD_GLOBAL_MODULE | 1,000 | 1.0% |
| CALL | 240 | 0.3% |
| PUSH_NULL | 160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 95,740 | 99.8% |
| COPY_FREE_VARS | 180 | 0.2% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,335,146 | 56.7% |
| BINARY_OP_ADD_INT | 9,395,228 | 39.9% |
| LOAD_FAST_LOAD_FAST | 480,458 | 2.0% |
| LOAD_ATTR | 152,040 | 0.6% |
| LOAD_DEREF | 83,580 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,658,516 | 92.1% |
| COPY_FREE_VARS | 1,202,733 | 5.1% |
| MAKE_CELL | 654,447 | 2.8% |
| POP_TOP | 7,360 | 0.0% |
| CALL_PY_EXACT_ARGS | 713 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,821,899 | 30.8% |
| CALL_BUILTIN_CLASS | 1,959,443 | 21.4% |
| LOAD_GLOBAL_BUILTIN | 921,773 | 10.1% |
| LOAD_CONST | 710,920 | 7.8% |
| CALL_LEN | 611,120 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,419,875 | 37.4% |
| CALL_BUILTIN_CLASS | 1,959,443 | 21.4% |
| GET_ITER | 1,868,939 | 20.4% |
| CALL | 284,315 | 3.1% |
| BINARY_SUBSCR_LIST_INT | 282,408 | 3.1% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,273,111 | 55.8% |
| LOAD_FAST_LOAD_FAST | 17,273,745 | 39.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,300 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 64,282 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,103,708 | 41.8% |
| STORE_FAST | 11,047,679 | 25.5% |
| TO_BOOL | 10,287,220 | 23.8% |
| PUSH_NULL | 2,129,900 | 4.9% |
| RETURN_VALUE | 1,500,349 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,841 | 94.4% |
| LOAD_FAST | 135,055 | 2.6% |
| BINARY_OP | 119,077 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,121 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 127,955 | 2.5% |
| CALL_BUILTIN_CLASS | 119,077 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,814,134 | 44.7% |
| RETURN_GENERATOR | 10,184,417 | 25.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,611,058 | 14.1% |
| LOAD_ATTR_SLOT | 4,881,652 | 12.2% |
| BINARY_OP | 1,095,149 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,692,887 | 39.4% |
| RETURN_VALUE | 11,433,025 | 28.7% |
| TO_BOOL_BOOL | 9,886,399 | 24.8% |
| GET_ITER | 2,591,158 | 6.5% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,900,105 | 53.2% |
| LOAD_GLOBAL_BUILTIN | 19,055,863 | 28.2% |
| LOAD_DEREF | 7,549,471 | 11.2% |
| LOAD_FAST_LOAD_FAST | 2,883,968 | 4.3% |
| LOAD_FAST | 1,621,100 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,845,672 | 88.7% |
| YIELD_VALUE | 6,945,986 | 10.3% |
| COPY | 525,020 | 0.8% |
| RETURN_VALUE | 127,550 | 0.2% |
| TO_BOOL | 9,663 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,057,562 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 185,800 | 0.7% |
| RETURN_VALUE | 95,144 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,271,168 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,676,864 | 34.4% |
| LOAD_CONST | 7,191,453 | 25.6% |
| CALL_BUILTIN_CLASS | 611,120 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,419,526 | 68.4% |
| BUILD_TUPLE | 3,231,440 | 13.5% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| CALL | 693,159 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 17,343,125 | 72.2% |
| EXTENDED_ARG | 4,571,191 | 19.0% |
| LOAD_FAST | 1,681,761 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |
| JUMP_FORWARD | 191,888 | 0.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,180,657 | 68.7% |
| LOAD_CONST | 2,390,787 | 10.8% |
| BUILD_LIST | 2,294,415 | 10.4% |
| BUILD_MAP | 1,561,360 | 7.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 272,555 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,867,375 | 58.3% |
| STORE_FAST | 3,454,051 | 15.6% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.1% |
| POP_TOP | 908,865 | 4.1% |
| GET_ITER | 737,615 | 3.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,840 | 47.5% |
| LOAD_CONST | 2,220 | 37.1% |
| LOAD_FAST | 800 | 13.4% |
| CALL | 120 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,160 | 36.1% |
| STORE_FAST | 1,860 | 31.1% |
| GET_ITER | 880 | 14.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 680 | 11.4% |
| LOAD_ATTR_METHOD_NO_DICT | 220 | 3.7% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 24,532,888 | 83.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,677 | 16.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,789 | 0.4% |
| LOAD_ATTR | 72,820 | 0.2% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,456,955 | 48.9% |
| STORE_FAST | 9,689,551 | 32.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,841 | 16.5% |
| CALL_BUILTIN_CLASS | 169,819 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,789 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 61.4% |
| LOAD_CONST | 1,226,593 | 26.4% |
| LOAD_FAST | 353,960 | 7.6% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,235,540 | 69.6% |
| LOAD_CONST | 1,224,593 | 26.3% |
| TO_BOOL_NONE | 104,000 | 2.2% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.5% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 21,016,330 | 30.9% |
| LOAD_FAST | 15,731,676 | 23.1% |
| LOAD_FAST_LOAD_FAST | 13,756,536 | 20.2% |
| GET_ITER | 12,995,104 | 19.1% |
| LOAD_SUPER_ATTR_METHOD | 1,539,395 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 50,993,842 | 74.9% |
| COPY_FREE_VARS | 11,862,824 | 17.4% |
| RETURN_GENERATOR | 4,261,611 | 6.3% |
| MAKE_CELL | 772,766 | 1.1% |
| CALL_PY_EXACT_ARGS | 144,905 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,105,017 | 45.8% |
| LOAD_FAST | 1,865,980 | 40.6% |
| RETURN_VALUE | 192,597 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,834 | 3.4% |
| LOAD_CONST | 80,477 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,380,047 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,750 | 1.2% |
| CALL_PY_EXACT_ARGS | 220 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 220 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 145,520 | 62.4% |
| RETURN_VALUE | 73,520 | 31.5% |
| LOAD_FAST | 14,020 | 6.0% |
| CALL | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 219,100 | 93.9% |
| BUILD_TUPLE | 6,860 | 2.9% |
| STORE_FAST | 4,380 | 1.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,840 | 0.8% |
| CALL_BUILTIN_O | 980 | 0.4% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,121 | 80.4% |
| LOAD_FAST | 1,017,569 | 17.4% |
| STORE_FAST | 105,784 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,164 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,321 | 80.4% |
| BINARY_SUBSCR_DICT | 443,840 | 7.6% |
| STORE_FAST | 353,224 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,590,414 | 99.3% |
| LOAD_CONST | 120,020 | 0.7% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,081 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,720 | 38.4% |
| COMPARE_OP | 5,882,579 | 35.2% |
| LOAD_ATTR | 4,209,481 | 25.2% |
| IS_OP | 64,280 | 0.4% |
| BUILD_TUPLE | 55,800 | 0.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,672 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,605 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,057 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,987,350 | 41.0% |
| LOAD_FAST_LOAD_FAST | 18,327,105 | 35.8% |
| CALL_LEN | 10,271,168 | 20.1% |
| LOAD_FAST | 1,029,121 | 2.0% |
| LOAD_ATTR_SLOT | 225,441 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,531,095 | 69.4% |
| BINARY_OP | 6,308,780 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.3% |
| EXTENDED_ARG | 1,719,909 | 3.4% |
| LOAD_FAST_LOAD_FAST | 1,570,040 | 3.1% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 68.9% |
| LOAD_CONST | 4,336,073 | 29.8% |
| LOAD_GLOBAL_MODULE | 192,409 | 1.3% |
| LOAD_ATTR | 3,160 | 0.0% |
| LOAD_FAST | 2,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,480,862 | 99.4% |
| YIELD_VALUE | 79,880 | 0.5% |
| POP_JUMP_IF_TRUE | 3,520 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,643 | 52.6% |
| GET_ITER | 90,735 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,723 | 52.1% |
| POP_TOP | 90,575 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 46,567,482 | 74.0% |
| EXTENDED_ARG | 5,660,762 | 9.0% |
| LOAD_FAST | 4,843,836 | 7.7% |
| GET_ITER | 4,579,440 | 7.3% |
| SWAP | 1,221,493 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 43,133,036 | 68.6% |
| RETURN_CONST | 5,671,974 | 9.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,734,990 | 7.5% |
| STORE_FAST_LOAD_FAST | 4,156,330 | 6.6% |
| LOAD_FAST | 4,094,146 | 6.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 10,610,493 | 87.5% |
| GET_ITER | 809,589 | 6.7% |
| EXTENDED_ARG | 642,400 | 5.3% |
| SWAP | 38,880 | 0.3% |
| LOAD_FAST | 29,360 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,761,233 | 88.7% |
| RETURN_CONST | 630,340 | 5.2% |
| STORE_FAST_LOAD_FAST | 500,000 | 4.1% |
| LOAD_FAST | 195,180 | 1.6% |
| SWAP | 38,520 | 0.3% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 22,288,401 | 64.0% |
| GET_ITER | 9,977,815 | 28.6% |
| EXTENDED_ARG | 1,740,040 | 5.0% |
| LOAD_FAST | 519,078 | 1.5% |
| SWAP | 299,637 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 23,958,215 | 68.8% |
| LOAD_FAST | 7,495,148 | 21.5% |
| RETURN_CONST | 789,299 | 2.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 727,333 | 2.1% |
| LOAD_GLOBAL_MODULE | 602,522 | 1.7% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 170,180 | 90.7% |
| LOAD_FAST_LOAD_FAST | 16,900 | 9.0% |
| LOAD_GLOBAL_MODULE | 280 | 0.1% |
| LOAD_ATTR | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 146,960 | 78.3% |
| LOAD_FAST | 34,200 | 18.2% |
| STORE_FAST | 6,320 | 3.4% |
| LOAD_ATTR | 120 | 0.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,501,724 | 59.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,877 | 11.6% |
| LOAD_DEREF | 1,058,337 | 11.5% |
| COPY | 956,400 | 10.4% |
| LOAD_GLOBAL_MODULE | 571,620 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,533 | 17.0% |
| CALL_BUILTIN_FAST | 1,337,300 | 14.6% |
| POP_JUMP_IF_NOT_NONE | 1,225,093 | 13.3% |
| STORE_FAST | 1,076,037 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,877 | 11.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,141,697 | 86.3% |
| RETURN_VALUE | 4,635,649 | 5.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.4% |
| LOAD_GLOBAL_MODULE | 1,983,861 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,533 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,845,389 | 34.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,532,888 | 26.8% |
| CALL_PY_EXACT_ARGS | 21,016,330 | 22.9% |
| LOAD_CONST | 4,055,618 | 4.4% |
| LOAD_DEREF | 3,320,118 | 3.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 22,299,955 | 71.8% |
| LOAD_ATTR_SLOT | 4,711,761 | 15.2% |
| LOAD_FAST | 3,706,689 | 11.9% |
| STORE_FAST_LOAD_FAST | 157,680 | 0.5% |
| LOAD_ATTR | 147,524 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,131,939 | 48.7% |
| LOAD_FAST_LOAD_FAST | 10,785,389 | 34.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,677 | 15.5% |
| CALL_PY_EXACT_ARGS | 313,430 | 1.0% |
| LOAD_CONST | 6,484 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260,988 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,402 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,173 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,639 | 6.3% |
| CALL | 57,378 | 4.5% |
| LOAD_FAST | 26,100 | 2.1% |
| LOAD_ATTR_SLOT | 15,920 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,473,878 | 92.5% |
| LOAD_DEREF | 3,109,100 | 5.3% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| STORE_FAST_LOAD_FAST | 238,654 | 0.4% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 236,958 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 44,302,401 | 75.3% |
| CALL_BUILTIN_O | 5,611,058 | 9.5% |
| BUILD_TUPLE | 2,484,120 | 4.2% |
| LOAD_FAST | 1,921,616 | 3.3% |
| BINARY_OP_MULTIPLY_INT | 1,668,683 | 2.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,000,207 | 60.8% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.1% |
| LOAD_DEREF | 144,340 | 8.8% |
| LOAD_ATTR | 12,020 | 0.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 4,885 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.1% |
| TO_BOOL_STR | 478,200 | 29.1% |
| TO_BOOL_BOOL | 410,316 | 25.0% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,484,875 | 94.6% |
| RETURN_VALUE | 642,470 | 2.3% |
| STORE_FAST_LOAD_FAST | 318,557 | 1.1% |
| LOAD_DEREF | 217,222 | 0.8% |
| LOAD_FAST_LOAD_FAST | 168,600 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,813,195 | 67.2% |
| COPY_FREE_VARS | 5,062,287 | 18.1% |
| GET_ITER | 1,920,539 | 6.9% |
| TO_BOOL_BOOL | 728,592 | 2.6% |
| STORE_FAST | 505,840 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 95,203,666 | 99.1% |
| LOAD_ATTR_SLOT | 613,651 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,063 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 72,535 | 0.1% |
| STORE_FAST_LOAD_FAST | 21,614 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,433,180 | 34.8% |
| STORE_FAST | 22,510,675 | 23.4% |
| LOAD_DEREF | 6,405,019 | 6.7% |
| LOAD_FAST | 5,219,227 | 5.4% |
| LOAD_CONST | 5,210,116 | 5.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 58,003,307 | 24.8% |
| RESUME_CHECK | 41,291,633 | 17.7% |
| STORE_FAST | 37,718,799 | 16.1% |
| STORE_FAST_STORE_FAST | 22,009,949 | 9.4% |
| LOAD_FAST | 20,513,129 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,935,050 | 69.7% |
| LOAD_FAST_LOAD_FAST | 28,998,027 | 12.4% |
| CALL_ISINSTANCE | 19,055,863 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 9,010,335 | 3.9% |
| LOAD_DEREF | 3,365,535 | 1.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 78,854,939 | 54.1% |
| STORE_FAST | 18,255,644 | 12.5% |
| RESUME_CHECK | 16,028,582 | 11.0% |
| POP_JUMP_IF_FALSE | 9,686,774 | 6.6% |
| NOP | 6,493,415 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 57,026,812 | 39.1% |
| CALL_ISINSTANCE | 35,900,105 | 24.6% |
| LOAD_FAST | 29,778,364 | 20.4% |
| CONTAINS_OP | 5,290,214 | 3.6% |
| LOAD_FAST_LOAD_FAST | 3,333,760 | 2.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,629 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,182,029 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,813,658 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,395 | 84.9% |
| LOAD_GLOBAL_MODULE | 172,263 | 9.5% |
| LOAD_FAST | 84,580 | 4.7% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 99,223,788 | 38.4% |
| CALL_PY_EXACT_ARGS | 50,993,842 | 19.8% |
| COPY_FREE_VARS | 21,816,786 | 8.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 21,658,516 | 8.4% |
| LOAD_ATTR_PROPERTY | 18,813,195 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,550,112 | 44.8% |
| LOAD_GLOBAL_BUILTIN | 41,291,633 | 16.0% |
| NOP | 21,364,850 | 8.3% |
| LOAD_FAST_LOAD_FAST | 19,938,982 | 7.7% |
| LOAD_GLOBAL_MODULE | 16,028,582 | 6.2% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 661,220 | 64.2% |
| LOAD_CONST | 367,964 | 35.7% |
| SEND | 620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 646,240 | 62.8% |
| POP_TOP | 352,904 | 34.3% |
| YIELD_VALUE | 15,060 | 1.5% |
| END_SEND | 15,020 | 1.5% |
| SEND | 580 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,887 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,139 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,761 | 36.0% |
| RETURN_CONST | 887,442 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,412 | 52.2% |
| LOAD_FAST | 4,285,058 | 47.3% |
| STORE_ATTR_SLOT | 41,742 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,673,192 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,275 | 24.9% |
| LOAD_CONST | 1,890,779 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,864 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,574,099 | 68.9% |
| LOAD_FAST | 397,968 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 7.9% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,339 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,660,519 | 72.7% |
| EXTENDED_ARG | 226,748 | 9.9% |
| LOAD_FAST_LOAD_FAST | 184,960 | 8.1% |
| LOAD_FAST | 165,801 | 7.3% |
| LOAD_GLOBAL_MODULE | 38,959 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,850,957 | 92.7% |
| SWAP | 1,208,120 | 5.9% |
| BINARY_SUBSCR_DICT | 112,800 | 0.6% |
| LOAD_FAST | 99,421 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 10,115,534 | 49.7% |
| LOAD_FAST_LOAD_FAST | 10,022,064 | 49.3% |
| LOAD_CONST | 160,200 | 0.8% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,446 | 98.7% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| STORE_FAST_LOAD_FAST | 1,240 | 0.5% |
| TO_BOOL | 384 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 217,405 | 95.1% |
| POP_JUMP_IF_FALSE | 9,614 | 4.2% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 51 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 59,845,672 | 34.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 44,302,401 | 25.7% |
| LOAD_FAST | 21,619,970 | 12.5% |
| CALL_BUILTIN_FAST | 18,103,708 | 10.5% |
| CALL_BUILTIN_O | 9,886,399 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 111,647,018 | 64.6% |
| POP_JUMP_IF_TRUE | 54,444,799 | 31.5% |
| EXTENDED_ARG | 5,486,173 | 3.2% |
| UNARY_NOT | 1,118,760 | 0.6% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,367,546 | 93.3% |
| BINARY_OP | 732,597 | 3.7% |
| BINARY_SUBSCR_LIST_INT | 485,260 | 2.5% |
| BINARY_SUBSCR_TUPLE_INT | 63,305 | 0.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,859 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,556,988 | 53.6% |
| POP_JUMP_IF_TRUE | 9,136,782 | 46.4% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 166 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,234,660 | 97.0% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 10,910 | 0.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8,780 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 834,450 | 36.2% |
| POP_JUMP_IF_TRUE | 784,571 | 34.1% |
| UNARY_NOT | 661,895 | 28.7% |
| EXTENDED_ARG | 21,480 | 0.9% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,741 | 68.0% |
| RETURN_VALUE | 389,282 | 14.4% |
| LOAD_ATTR_PROPERTY | 293,604 | 10.8% |
| CALL_METHOD_DESCRIPTOR_O | 104,000 | 3.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,960 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,944,692 | 71.8% |
| POP_JUMP_IF_TRUE | 745,644 | 27.5% |
| EXTENDED_ARG | 15,420 | 0.6% |
| TO_BOOL_BOOL | 1,680 | 0.1% |
| TO_BOOL | 1,500 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 92.0% |
| STORE_FAST_LOAD_FAST | 26,080 | 5.0% |
| LOAD_FAST | 13,080 | 2.5% |
| COPY | 2,120 | 0.4% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 513,460 | 98.8% |
| POP_JUMP_IF_TRUE | 6,300 | 1.2% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,335 | 66.8% |
| RETURN_VALUE | 49,120 | 27.3% |
| CALL_BUILTIN_CLASS | 2,600 | 1.4% |
| BINARY_SUBSCR_LIST_INT | 1,880 | 1.0% |
| FOR_ITER_LIST | 1,880 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 63.8% |
| STORE_FAST_STORE_FAST | 65,155 | 36.2% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 884,801 | 54.3% |
| RETURN_VALUE | 660,923 | 40.5% |
| STORE_FAST | 79,520 | 4.9% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,145 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,436,146 | 88.1% |
| STORE_FAST | 154,743 | 9.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.4% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 71,213,514 | 68.5% |
| RETURN_VALUE | 19,466,544 | 18.7% |
| BINARY_SUBSCR_LIST_INT | 7,524,710 | 7.2% |
| FOR_ITER_LIST | 4,734,990 | 4.6% |
| FOR_ITER_TUPLE | 727,333 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 99,125,789 | 95.4% |
| STORE_DEREF | 4,491,620 | 4.3% |
| STORE_FAST | 257,750 | 0.2% |
| STORE_NAME | 18,940 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,680 | 0.0% |


</details>

### DELETE_NAME

<details>
<summary> Successors and predecessors for DELETE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 80 | 66.7% |
| POP_TOP | 20 | 16.7% |
| FOR_ITER | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 80 | 66.7% |
| RETURN_CONST | 20 | 16.7% |
| BUILD_LIST | 20 | 16.7% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 1,920 | 92.3% |
| DELETE_FAST | 160 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 320 | 66.7% |
| COPY | 160 | 33.3% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_BUILD_CLASS | 20 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 280 | 93.3% |
| BINARY_OP | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 300 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_CONST_KEY_MAP | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 20 | 100.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 40 | 66.7% |
| CALL | 20 | 33.3% |


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
|     deferred | 35,267,920 | 65.2% |
|          hit | 18,802,591 | 34.7% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,804 | 11.7% |
| Failure | 51,372 | 88.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,462 | 18.4% |
| multiply different types | 7,464 | 14.5% |
| subtract other | 6,800 | 13.2% |
| and int | 4,143 | 8.1% |
| rshift | 3,825 | 7.4% |
| or | 3,700 | 7.2% |
| power | 2,868 | 5.6% |
| true divide different types | 2,524 | 4.9% |
| multiply other | 2,360 | 4.6% |
| remainder | 2,309 | 4.5% |
| add different types | 1,952 | 3.8% |
| floor divide | 1,276 | 2.5% |
| subtract different types | 1,196 | 2.3% |
| xor | 584 | 1.1% |
| and other | 379 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 226 | 0.4% |
| true divide float | 4 | 0.0% |


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
|     deferred | 24,036,954 | 36.0% |
|          hit | 42,664,255 | 63.9% |
|         miss | 45,573 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,361 | 32.2% |
| Failure | 17,633 | 67.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 12,209 | 69.2% |
| out of range | 3,640 | 20.6% |
| buffer int | 1,760 | 10.0% |
| array int | 20 | 0.1% |
| tuple slice | 4 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,139,515 | 5.9% |
|        deopt | 31,040 | 0.0% |
|          hit | 384,654,522 | 86.8% |
|         miss | 31,502,195 | 7.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 674,799 | 90.3% |
| Failure | 72,751 | 9.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,487 | 39.2% |
| code complex parameters | 14,053 | 19.3% |
| class no vectorcall | 9,220 | 12.7% |
| cfunc varargs keywords | 6,385 | 8.8% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.5% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,170 | 3.0% |
| meth descr varargs | 1,916 | 2.6% |
| no dict | 1,120 | 1.5% |
| meth descr varargs keywords | 640 | 0.9% |
| operator wrapper | 380 | 0.5% |
| cfunc varargs | 240 | 0.3% |
| meth descr method fastcall keywords | 180 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 38,459,454 | 36.7% |
|          hit | 65,706,464 | 62.7% |
|         miss | 575,980 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,467 | 22.8% |
| Failure | 69,334 | 77.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,494 | 26.7% |
| other | 15,267 | 22.0% |
| different types | 12,240 | 17.7% |
| tuple | 10,040 | 14.5% |
| string | 9,960 | 14.4% |
| bool | 2,133 | 3.1% |
| float long | 340 | 0.5% |
| set | 280 | 0.4% |
| baseobject | 280 | 0.4% |
| list | 220 | 0.3% |
| long float | 80 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 103,789,338 | 48.5% |
|          hit | 108,485,255 | 50.7% |
|         miss | 1,576,455 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 41,626 | 29.9% |
| Failure | 97,420 | 70.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 69,219 | 71.1% |
| set | 9,046 | 9.3% |
| zip | 7,600 | 7.8% |
| enumerate | 4,235 | 4.3% |
| other | 2,720 | 2.8% |
| itertools | 1,940 | 2.0% |
| dict keys | 1,640 | 1.7% |
| reversed list | 860 | 0.9% |
| dict values | 80 | 0.1% |
| ascii string | 80 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120,214,157 | 27.3% |
|        deopt | 20 | 0.0% |
|          hit | 250,500,403 | 57.0% |
|         miss | 67,436,099 | 15.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,350,142 | 89.4% |
| Failure | 160,222 | 10.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 60,845 | 38.0% |
| mutable class | 58,769 | 36.7% |
| method | 10,461 | 6.5% |
| has managed dict | 8,780 | 5.5% |
| overridden | 8,678 | 5.4% |
| shadowed | 5,300 | 3.3% |
| class method obj | 3,980 | 2.5% |
| builtin class method | 1,320 | 0.8% |
| not managed dict | 1,109 | 0.7% |
| non object slot | 560 | 0.3% |
| not in keys | 300 | 0.2% |
| non overriding descriptor | 60 | 0.0% |
| module attr not found | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 89,950 | 0.0% |
|          hit | 379,562,950 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,979 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 605 | 0.0% |
|          hit | 2,996,187 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 100.0% |
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
|     deferred | 439,140 | 29.8% |
|          hit | 999,144 | 67.8% |
|         miss | 30,660 | 2.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 620 | 16.8% |
| Failure | 3,080 | 83.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| list | 3,080 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 540,776 | 4.2% |
|          hit | 10,199,639 | 78.4% |
|         miss | 2,219,659 | 17.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,802 | 92.3% |
| Failure | 3,908 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,960 | 50.2% |
| not managed dict | 1,448 | 37.1% |
| overridden | 240 | 6.1% |
| no dict | 200 | 5.1% |
| not in keys | 60 | 1.5% |


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
|     deferred | 3,422,557 | 13.1% |
|          hit | 22,625,666 | 86.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,722 | 42.8% |
| Failure | 3,640 | 57.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 3,640 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,842,303 | 6.1% |
|          hit | 197,712,374 | 93.7% |
|         miss | 440,362 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,945 | 72.2% |
| Failure | 23,067 | 27.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,782 | 46.7% |
| number | 3,536 | 15.3% |
| mapping | 3,300 | 14.3% |
| dict | 2,340 | 10.1% |
| other | 1,631 | 7.1% |
| set | 1,438 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,691 | 0.0% |
|          hit | 105,709,963 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,396 | 93.6% |
| Failure | 779 | 6.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 719 | 92.3% |
| iterator | 60 | 7.7% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 3,221,822,941 | 54.1% |
| Not specialized | 800,402,870 | 13.4% |
| Specialized hits | 1,825,167,358 | 30.7% |
| Specialized misses | 103,847,563 | 1.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 120,214,157 | 32.9% |
| FOR_ITER | 103,789,338 | 28.4% |
| COMPARE_OP | 38,459,454 | 10.5% |
| BINARY_OP | 35,267,920 | 9.7% |
| CALL | 26,139,515 | 7.2% |
| BINARY_SUBSCR | 24,036,954 | 6.6% |
| TO_BOOL | 12,842,303 | 3.5% |
| STORE_SUBSCR | 3,422,557 | 0.9% |
| STORE_ATTR | 540,776 | 0.1% |
| SEND | 439,140 | 0.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,605,198 | 35.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 17,007,802 | 16.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,452,893 | 13.9% |
| LOAD_ATTR_METHOD_NO_DICT | 9,218,891 | 8.9% |
| CALL_PY_EXACT_ARGS | 7,811,977 | 7.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,430 | 6.2% |
| LOAD_ATTR_PROPERTY | 4,124,299 | 4.0% |
| CALL_BUILTIN_O | 2,661,205 | 2.6% |
| STORE_ATTR_SLOT | 2,218,679 | 2.1% |
| FOR_ITER_TUPLE | 803,262 | 0.8% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,637,772 | 46.9% |
| Calls to Python functions inlined | 144,800,892 | 53.1% |
| Calls via PyEval_EvalFrame (total) | 127,637,772 | 46.9% |
| Calls via PyEval_EvalFrame (vector) | 98,457,599 | 36.1% |
| Calls via PyEval_EvalFrame (generator) | 29,180,173 | 10.7% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,450,299 | 36.1% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,642 | 8.7% |
| Calls via PyEval_EvalFrame (function ex) | 11,825,199 | 4.3% |
| Calls via PyEval_EvalFrame (api) | 53,329,343 | 19.6% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,023 | 0.5% |
| Frames pushed | 112,551,264 | 41.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,396,227 | 54.3% |
| Frees to freelist | 363,639,174 |  |
| Allocations | 305,541,658 | 45.7% |
| Allocations to 512 bytes | 304,478,877 | 45.5% |
| Allocations to 4 kbytes | 1,038,321 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,225,072 |  |
| New values | 1,057,556 |  |
| Interpreter increfs | 2,568,824,821 | 64.2% |
| Interpreter decrefs | 2,994,232,218 | 65.4% |
| Increfs | 1,429,880,688 | 35.8% |
| Decrefs | 1,585,166,488 | 34.6% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 243,599,481 |  |
| Method cache misses | 3,933,637 |  |
| Method cache collisions | 5,029,619 |  |
| Method cache dunder hits | 347,441,795 |  |
| Method cache dunder misses | 1,096,689 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 0 | 0 | 0 |
| 1 | 0 | 0 | 0 |
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
| Number of data files | 80 |


</details>

---
Stats gathered on: 2023-11-16
