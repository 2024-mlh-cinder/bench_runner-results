
# Pystats results

- benchmark: sympy
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 912,443,635 | 16.4% | 16.4% |  |
| STORE_FAST | 297,464,430 | 5.4% | 21.8% |  |
| POP_JUMP_IF_FALSE | 275,837,776 | 5.0% | 26.8% |  |
| RESUME_CHECK | 256,717,873 | 4.6% | 31.4% |  |
| LOAD_FAST_LOAD_FAST | 233,813,189 | 4.2% | 35.6% |  |
| LOAD_GLOBAL_BUILTIN | 225,898,274 | 4.1% | 39.7% | 0.0% |
| LOAD_CONST | 178,990,700 | 3.2% | 42.9% |  |
| RETURN_VALUE | 177,424,503 | 3.2% | 46.1% |  |
| TO_BOOL_BOOL | 169,799,118 | 3.1% | 49.1% | 0.1% |
| INTERPRETER_EXIT | 127,442,770 | 2.3% | 51.4% |  |
| LOAD_ATTR | 121,756,404 | 2.2% | 53.6% |  |
| LOAD_GLOBAL_MODULE | 121,559,188 | 2.2% | 55.8% | 0.0% |
| FOR_ITER | 104,119,036 | 1.9% | 57.7% |  |
| STORE_FAST_STORE_FAST | 103,474,740 | 1.9% | 59.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 100,591,381 | 1.8% | 61.4% |  |
| LOAD_ATTR_SLOT | 95,486,814 | 1.7% | 63.1% | 38.2% |
| LOAD_ATTR_METHOD_NO_DICT | 89,621,797 | 1.6% | 64.7% | 10.2% |
| ENTER_EXECUTOR | 83,990,332 | 1.5% | 66.2% |  |
| POP_JUMP_IF_TRUE | 76,196,940 | 1.4% | 67.6% |  |
| JUMP_BACKWARD | 67,762,760 | 1.2% | 68.8% |  |
| CALL_PY_EXACT_ARGS | 66,323,359 | 1.2% | 70.0% | 11.8% |
| CALL_ISINSTANCE | 62,540,773 | 1.1% | 71.1% |  |
| LOAD_DEREF | 62,504,849 | 1.1% | 72.3% |  |
| POP_TOP | 61,589,970 | 1.1% | 73.4% |  |
| GET_ITER | 59,531,071 | 1.1% | 74.4% |  |
| RETURN_CONST | 57,139,169 | 1.0% | 75.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,880,716 | 1.0% | 76.5% | 27.7% |
| BUILD_TUPLE | 56,839,861 | 1.0% | 77.5% |  |
| PUSH_NULL | 49,499,986 | 0.9% | 78.4% |  |
| COMPARE_OP_INT | 48,782,117 | 0.9% | 79.3% | 1.2% |
| IS_OP | 47,831,464 | 0.9% | 80.2% |  |
| SWAP | 45,036,711 | 0.8% | 81.0% |  |
| CALL_BUILTIN_FAST | 43,262,946 | 0.8% | 81.7% |  |
| POP_JUMP_IF_NONE | 41,010,586 | 0.7% | 82.5% |  |
| COMPARE_OP | 38,426,824 | 0.7% | 83.2% |  |
| CONTAINS_OP | 37,863,019 | 0.7% | 83.9% |  |
| CALL_BUILTIN_O | 37,651,922 | 0.7% | 84.5% | 7.1% |
| BINARY_OP | 35,326,127 | 0.6% | 85.2% |  |
| BUILD_MAP | 33,785,733 | 0.6% | 85.8% |  |
| COPY_FREE_VARS | 31,748,601 | 0.6% | 86.4% |  |
| NOP | 31,474,807 | 0.6% | 86.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,522,366 | 0.5% | 87.5% | 21.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 29,446,694 | 0.5% | 88.0% | 0.5% |
| BINARY_SUBSCR_LIST_INT | 29,008,505 | 0.5% | 88.5% | 0.0% |
| CALL_LEN | 28,097,675 | 0.5% | 89.0% |  |
| CALL_FUNCTION_EX | 28,014,240 | 0.5% | 89.5% |  |
| LOAD_ATTR_PROPERTY | 27,994,088 | 0.5% | 90.0% | 14.7% |
| CALL | 26,830,152 | 0.5% | 90.5% |  |
| CALL_LIST_APPEND | 24,016,341 | 0.4% | 90.9% |  |
| BINARY_SUBSCR | 23,811,792 | 0.4% | 91.4% |  |
| DICT_MERGE | 23,270,822 | 0.4% | 91.8% |  |
| YIELD_VALUE | 23,093,731 | 0.4% | 92.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 22,028,572 | 0.4% | 92.6% | 65.7% |
| BUILD_LIST | 21,581,303 | 0.4% | 93.0% |  |
| STORE_SUBSCR_LIST_INT | 20,208,021 | 0.4% | 93.3% |  |
| TO_BOOL_INT | 19,062,361 | 0.3% | 93.7% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,128,306 | 0.3% | 94.0% |  |
| LOAD_FAST_AND_CLEAR | 16,788,718 | 0.3% | 94.3% |  |
| EXTENDED_ARG | 15,346,078 | 0.3% | 94.6% |  |
| CALL_TYPE_1 | 14,852,617 | 0.3% | 94.9% |  |
| COMPARE_OP_STR | 14,565,549 | 0.3% | 95.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,552,684 | 0.3% | 95.4% | 0.4% |
| RETURN_GENERATOR | 14,324,147 | 0.3% | 95.6% |  |
| FOR_ITER_LIST | 12,962,126 | 0.2% | 95.9% | 1.6% |
| TO_BOOL | 12,925,105 | 0.2% | 96.1% |  |
| MAKE_FUNCTION | 12,376,501 | 0.2% | 96.3% |  |
| FOR_ITER_TUPLE | 11,632,004 | 0.2% | 96.5% | 3.4% |
| CALL_KW | 10,673,751 | 0.2% | 96.7% |  |
| SET_FUNCTION_ATTRIBUTE | 10,359,268 | 0.2% | 96.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,065,411 | 0.2% | 97.1% | 0.0% |
| STORE_ATTR_SLOT | 9,060,898 | 0.2% | 97.3% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,988,296 | 0.2% | 97.4% | 0.1% |
| IMPORT_FROM | 8,955,836 | 0.2% | 97.6% |  |
| CALL_BUILTIN_CLASS | 8,630,090 | 0.2% | 97.7% |  |
| MAP_ADD | 7,867,484 | 0.1% | 97.9% |  |
| IMPORT_NAME | 7,760,488 | 0.1% | 98.0% |  |
| STORE_DEREF | 7,702,595 | 0.1% | 98.2% |  |
| MAKE_CELL | 6,050,043 | 0.1% | 98.3% |  |
| CALL_TUPLE_1 | 5,851,481 | 0.1% | 98.4% | 0.0% |
| JUMP_FORWARD | 5,744,041 | 0.1% | 98.5% |  |
| LIST_APPEND | 5,743,303 | 0.1% | 98.6% |  |
| UNARY_NOT | 5,274,110 | 0.1% | 98.7% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,677 | 0.1% | 98.8% | 0.1% |
| COPY | 4,627,004 | 0.1% | 98.8% |  |
| CALL_PY_WITH_DEFAULTS | 4,591,403 | 0.1% | 98.9% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,590,722 | 0.1% | 99.0% | 0.2% |
| BINARY_OP_ADD_INT | 3,785,738 | 0.1% | 99.1% |  |
| STORE_SUBSCR | 3,429,145 | 0.1% | 99.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,939 | 0.1% | 99.2% | 0.0% |
| BINARY_SUBSCR_DICT | 3,261,421 | 0.1% | 99.3% |  |
| BINARY_OP_MULTIPLY_INT | 2,764,541 | 0.0% | 99.3% | 0.0% |
| TO_BOOL_NONE | 2,654,077 | 0.0% | 99.4% | 8.6% |
| BINARY_OP_SUBTRACT_INT | 2,485,983 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 2,286,525 | 0.0% | 99.4% | 0.5% |
| STORE_SUBSCR_DICT | 2,281,138 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,810,463 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,120 | 0.0% | 99.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,647,335 | 0.0% | 99.6% | 20.6% |
| UNPACK_SEQUENCE_TUPLE | 1,591,738 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,578,357 | 0.0% | 99.6% |  |
| FOR_ITER_RANGE | 1,397,963 | 0.0% | 99.7% |  |
| LIST_EXTEND | 1,349,455 | 0.0% | 99.7% |  |
| CALL_INTRINSIC_1 | 1,349,415 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,485 | 0.0% | 99.8% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,182,088 | 0.0% | 99.8% |  |
| SEND_GEN | 1,029,772 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,989 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,989 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,989 | 0.0% | 99.9% |  |
| STORE_ATTR | 591,497 | 0.0% | 99.9% |  |
| BINARY_SLICE | 569,120 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 552,940 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,690 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,352 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 533,242 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 503,100 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 228,783 | 0.0% | 100.0% | 36.4% |
| FOR_ITER_GEN | 191,673 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,655 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,595 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,264 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 132,560 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,328 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,138 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 72,820 | 0.0% | 100.0% |  |
| BUILD_SET | 50,567 | 0.0% | 100.0% |  |
| RESUME | 47,535 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,844 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,600 | 0.0% | 100.0% |  |
| SET_ADD | 19,280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,260 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,760 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,004 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,202 | 0.0% | 100.0% |  |
| STORE_SLICE | 940 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 161,641,758 | 2.9% | 2.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 156,072,748 | 2.8% | 5.7% |
| RESUME_CHECK LOAD_FAST | 115,536,372 | 2.1% | 7.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 110,005,622 | 2.0% | 9.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 109,490,311 | 2.0% | 11.8% |
| CACHE RESUME_CHECK | 99,234,864 | 1.8% | 13.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 96,788,764 | 1.7% | 15.3% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,134,950 | 1.7% | 17.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 76,888,950 | 1.4% | 18.4% |
| RETURN_VALUE INTERPRETER_EXIT | 72,902,348 | 1.3% | 19.7% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 71,417,303 | 1.3% | 21.0% |
| JUMP_BACKWARD FOR_ITER | 67,462,887 | 1.2% | 22.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 61,810,234 | 1.1% | 23.3% |
| LOAD_FAST LOAD_CONST | 60,615,951 | 1.1% | 24.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 59,536,668 | 1.1% | 25.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,706,127 | 1.0% | 26.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 54,156,284 | 1.0% | 27.5% |
| LOAD_FAST RETURN_VALUE | 52,994,492 | 1.0% | 28.4% |
| LOAD_FAST LOAD_ATTR | 51,092,618 | 0.9% | 29.4% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 50,490,671 | 0.9% | 30.3% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 49,598,374 | 0.9% | 31.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 49,419,434 | 0.9% | 32.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,385,186 | 0.8% | 32.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,267,630 | 0.7% | 33.6% |
| STORE_FAST_STORE_FAST LOAD_FAST | 40,972,131 | 0.7% | 34.3% |
| LOAD_CONST LOAD_CONST | 40,216,016 | 0.7% | 35.0% |
| RETURN_VALUE STORE_FAST | 38,560,940 | 0.7% | 35.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 37,804,610 | 0.7% | 36.4% |
| LOAD_ATTR STORE_FAST | 36,824,124 | 0.7% | 37.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 35,788,442 | 0.6% | 37.7% |
| PUSH_NULL LOAD_FAST | 35,374,242 | 0.6% | 38.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 34,665,528 | 0.6% | 39.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,555,507 | 0.6% | 39.6% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,433,886 | 0.6% | 40.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,205,103 | 0.6% | 40.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 33,042,507 | 0.6% | 41.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 32,310,457 | 0.6% | 41.9% |
| RETURN_CONST INTERPRETER_EXIT | 32,285,136 | 0.6% | 42.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 30,795,349 | 0.6% | 43.1% |
| IS_OP POP_JUMP_IF_FALSE | 30,051,054 | 0.5% | 43.6% |
| ENTER_EXECUTOR LOAD_ATTR | 29,616,706 | 0.5% | 44.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 29,412,203 | 0.5% | 44.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 29,196,468 | 0.5% | 45.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,706,192 | 0.5% | 45.7% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 28,700,373 | 0.5% | 46.2% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 27,666,874 | 0.5% | 46.7% |
| LOAD_FAST CALL_LEN | 27,056,255 | 0.5% | 47.2% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 26,365,901 | 0.5% | 47.7% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 25,624,395 | 0.5% | 48.2% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,302,069 | 0.5% | 48.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 24,516,312 | 0.4% | 49.1% |
| BINARY_OP STORE_FAST | 24,216,881 | 0.4% | 49.5% |
| LOAD_CONST CALL_BUILTIN_FAST | 24,056,781 | 0.4% | 49.9% |
| DICT_MERGE CALL_FUNCTION_EX | 23,270,822 | 0.4% | 50.3% |
| BUILD_MAP LOAD_FAST | 23,181,627 | 0.4% | 50.8% |
| LOAD_FAST DICT_MERGE | 23,141,898 | 0.4% | 51.2% |
| LOAD_ATTR_SLOT STORE_FAST | 22,509,101 | 0.4% | 51.6% |
| YIELD_VALUE INTERPRETER_EXIT | 22,247,546 | 0.4% | 52.0% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_BUILTIN | 22,007,742 | 0.4% | 52.4% |
| COPY_FREE_VARS RESUME_CHECK | 21,788,265 | 0.4% | 52.8% |
| LOAD_FAST TO_BOOL_BOOL | 21,602,965 | 0.4% | 53.2% |
| RESUME_CHECK NOP | 21,365,997 | 0.4% | 53.6% |
| LOAD_FAST GET_ITER | 21,265,545 | 0.4% | 53.9% |
| BUILD_TUPLE RETURN_VALUE | 21,221,904 | 0.4% | 54.3% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,088,968 | 0.4% | 54.7% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 20,988,917 | 0.4% | 55.1% |
| POP_JUMP_IF_NONE JUMP_BACKWARD | 20,907,478 | 0.4% | 55.5% |
| STORE_FAST_STORE_FAST LOAD_DEREF | 20,818,456 | 0.4% | 55.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,801,735 | 0.4% | 56.2% |
| LOAD_CONST COMPARE_OP_INT | 20,758,384 | 0.4% | 56.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 20,355,095 | 0.4% | 56.9% |
| LOAD_ATTR CONTAINS_OP | 20,047,956 | 0.4% | 57.3% |
| GET_ITER FOR_ITER | 19,995,293 | 0.4% | 57.7% |
| COMPARE_OP POP_JUMP_IF_FALSE | 19,988,054 | 0.4% | 58.0% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,466,609 | 0.4% | 58.4% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 18,939,136 | 0.3% | 58.7% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,857,119 | 0.3% | 59.1% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,814,233 | 0.3% | 59.4% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 18,619,072 | 0.3% | 59.7% |
| LOAD_FAST TO_BOOL_INT | 18,175,128 | 0.3% | 60.1% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 18,002,462 | 0.3% | 60.4% |
| LOAD_FAST PUSH_NULL | 17,310,314 | 0.3% | 60.7% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,265,100 | 0.3% | 61.0% |
| LOAD_ATTR IS_OP | 17,248,988 | 0.3% | 61.3% |
| LOAD_FAST BUILD_TUPLE | 17,083,456 | 0.3% | 61.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,688,684 | 0.3% | 61.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,197,318 | 0.3% | 62.2% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 16,086,021 | 0.3% | 62.5% |
| LOAD_ATTR LOAD_FAST | 16,074,856 | 0.3% | 62.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,028,923 | 0.3% | 63.1% |
| RESUME_CHECK LOAD_CONST | 15,735,062 | 0.3% | 63.4% |
| LOAD_FAST CALL_BUILTIN_O | 15,710,522 | 0.3% | 63.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,674,662 | 0.3% | 63.9% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 15,653,230 | 0.3% | 64.2% |
| LOAD_FAST CALL_LIST_APPEND | 15,555,578 | 0.3% | 64.5% |
| RETURN_VALUE RETURN_VALUE | 15,185,090 | 0.3% | 64.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 15,171,322 | 0.3% | 65.0% |
| RESUME_CHECK POP_TOP | 15,140,706 | 0.3% | 65.3% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 15,102,459 | 0.3% | 65.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 15,101,142 | 0.3% | 65.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 535,760 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,683 | 56.2% |
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
| BINARY_OP_ADD_INT | 940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 580 | 61.7% |
| JUMP_BACKWARD | 360 | 38.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,234,864 | 77.7% |
| POP_TOP | 13,875,106 | 10.9% |
| COPY_FREE_VARS | 13,001,466 | 10.2% |
| MAKE_CELL | 1,509,117 | 1.2% |
| RESUME | 18,061 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 13,344,477 | 56.0% |
| LOAD_DEREF | 6,405,949 | 26.9% |
| BUILD_TUPLE | 1,800,450 | 7.6% |
| ENTER_EXECUTOR | 1,140,798 | 4.8% |
| LOAD_FAST | 734,543 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,858,227 | 28.8% |
| LOAD_FAST | 6,753,849 | 28.4% |
| RETURN_VALUE | 6,067,833 | 25.5% |
| CALL | 900,967 | 3.8% |
| GET_ITER | 900,265 | 3.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,955 | 73.6% |
| BUILD_TUPLE | 157,336 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,358 | 8.7% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,829 | 100.0% |
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
| RETURN_CONST | 22,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,600 | 100.0% |


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
| CONVERT_VALUE | 282,560 | 100.0% |
| LOAD_FAST | 20 | 0.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 140,760 | 49.8% |
| LOAD_CONST | 108,280 | 38.3% |
| LOAD_FAST | 33,560 | 11.9% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,265,545 | 35.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,456,821 | 24.3% |
| CALL | 10,953,526 | 18.4% |
| RETURN_VALUE | 4,116,902 | 6.9% |
| CALL_BUILTIN_O | 2,591,164 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 19,995,293 | 33.6% |
| CALL_PY_EXACT_ARGS | 12,994,912 | 21.8% |
| FOR_ITER_TUPLE | 9,876,110 | 16.6% |
| LOAD_FAST_AND_CLEAR | 9,198,749 | 15.5% |
| FOR_ITER_LIST | 4,320,661 | 7.3% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 346,952 | 64.2% |
| BINARY_SUBSCR | 185,800 | 34.4% |
| RETURN_VALUE | 7,520 | 1.4% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540,352 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,902,348 | 57.2% |
| RETURN_CONST | 32,285,136 | 25.3% |
| YIELD_VALUE | 22,247,546 | 17.5% |
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
| LOAD_CONST | 12,376,501 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 10,357,728 | 83.7% |
| LOAD_GLOBAL_BUILTIN | 794,308 | 6.4% |
| STORE_FAST | 669,668 | 5.4% |
| LOAD_FAST | 458,935 | 3.7% |
| STORE_NAME | 33,580 | 0.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,365,997 | 67.9% |
| POP_JUMP_IF_TRUE | 4,184,044 | 13.3% |
| STORE_FAST | 1,973,526 | 6.3% |
| POP_JUMP_IF_FALSE | 1,913,083 | 6.1% |
| POP_TOP | 1,392,509 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,282,256 | 39.0% |
| LOAD_DEREF | 10,424,416 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,377,998 | 20.3% |
| LOAD_FAST_LOAD_FAST | 900,000 | 2.9% |
| LOAD_CONST | 751,172 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,876 | 45.7% |
| POP_TOP | 358,693 | 39.5% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,876 | 45.7% |
| EXTENDED_ARG | 201,550 | 22.2% |
| ENTER_EXECUTOR | 155,423 | 17.1% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,140,706 | 24.6% |
| CACHE | 13,875,106 | 22.5% |
| RETURN_CONST | 9,275,890 | 15.1% |
| STORE_FAST | 5,840,310 | 9.5% |
| SWAP | 5,778,548 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 14,710,162 | 23.9% |
| RESUME_CHECK | 14,318,586 | 23.2% |
| ENTER_EXECUTOR | 9,281,341 | 15.1% |
| LOAD_FAST | 7,248,313 | 11.8% |
| RETURN_VALUE | 5,302,348 | 8.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,806 | 41.3% |
| BINARY_SUBSCR_DICT | 170,091 | 18.8% |
| RAISE_VARARGS | 115,318 | 12.7% |
| ENTER_EXECUTOR | 96,076 | 10.6% |
| LOAD_ATTR | 95,500 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,711 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,838 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,310,314 | 35.0% |
| LOAD_ATTR | 14,957,382 | 30.2% |
| LOAD_DEREF | 11,886,916 | 24.0% |
| CALL_BUILTIN_FAST | 2,129,900 | 4.3% |
| LOAD_SUPER_ATTR_ATTR | 1,182,088 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,374,242 | 71.5% |
| LOAD_FAST_LOAD_FAST | 12,185,532 | 24.6% |
| LOAD_CONST | 1,723,720 | 3.5% |
| LOAD_DEREF | 128,564 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,879,654 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,117,672 | 28.7% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,080 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,184,434 | 71.1% |
| STORE_FAST | 2,660,529 | 18.6% |
| LOAD_FAST | 792,042 | 5.5% |
| GET_YIELD_FROM_ITER | 346,952 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,994,492 | 29.9% |
| LOAD_ATTR_SLOT | 33,433,886 | 18.8% |
| BUILD_TUPLE | 21,221,904 | 12.0% |
| RETURN_VALUE | 15,185,090 | 8.6% |
| CALL_BUILTIN_O | 11,433,130 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,902,348 | 41.1% |
| STORE_FAST | 38,560,940 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,466,609 | 11.0% |
| RETURN_VALUE | 15,185,090 | 8.6% |
| LOAD_FAST | 5,453,838 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,215,371 | 93.8% |
| BINARY_SUBSCR | 93,200 | 2.7% |
| ENTER_EXECUTOR | 88,610 | 2.6% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.6% |
| SWAP | 5,960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,290,901 | 96.0% |
| ENTER_EXECUTOR | 96,680 | 2.8% |
| JUMP_BACKWARD | 19,700 | 0.6% |
| JUMP_FORWARD | 9,840 | 0.3% |
| STORE_SUBSCR | 3,640 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.6% |
| LOAD_FAST | 2,207,825 | 17.1% |
| LOAD_GLOBAL_MODULE | 119,008 | 0.9% |
| LOAD_ATTR | 117,983 | 0.9% |
| RETURN_VALUE | 27,309 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,253,156 | 94.8% |
| POP_JUMP_IF_TRUE | 509,896 | 3.9% |
| UNARY_NOT | 84,173 | 0.7% |
| TO_BOOL_BOOL | 41,169 | 0.3% |
| TO_BOOL | 21,489 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,484 | 22.0% |
| LOAD_FAST | 109,514 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,690 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,988 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,842 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,095 | 10.9% |
| CALL_LIST_APPEND | 39,980 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,785 | 65.3% |
| TO_BOOL_BOOL | 1,085,094 | 20.6% |
| TO_BOOL_LIST | 661,895 | 12.5% |
| TO_BOOL | 84,173 | 1.6% |
| TO_BOOL_INT | 163 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,632 | 66.9% |
| STORE_FAST | 882,785 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,936 | 1.6% |
| LOAD_CONST | 34,377 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,760,028 | 33.3% |
| COMPARE_OP_INT | 6,304,740 | 17.8% |
| COMPARE_OP | 6,162,400 | 17.4% |
| CALL_TUPLE_1 | 4,707,268 | 13.3% |
| LOAD_FAST | 2,606,930 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,216,881 | 68.6% |
| RETURN_VALUE | 5,771,265 | 16.3% |
| BUILD_TUPLE | 1,556,880 | 4.4% |
| CALL_BUILTIN_O | 1,095,153 | 3.1% |
| LOAD_FAST | 857,870 | 2.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,328 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,548 | 97.9% |
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
| SWAP | 4,464,661 | 20.7% |
| POP_JUMP_IF_TRUE | 4,083,162 | 18.9% |
| STORE_FAST | 3,816,567 | 17.7% |
| LOAD_FAST | 2,312,400 | 10.7% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,713,074 | 54.3% |
| SWAP | 4,464,661 | 20.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,415 | 10.6% |
| LOAD_FAST | 1,374,755 | 6.4% |
| BUILD_LIST | 748,362 | 3.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,168,063 | 36.0% |
| BUILD_TUPLE | 10,996,576 | 32.5% |
| SWAP | 4,716,088 | 14.0% |
| LOAD_CONST | 1,656,800 | 4.9% |
| RESUME_CHECK | 1,285,960 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,181,627 | 68.6% |
| SWAP | 4,716,088 | 14.0% |
| STORE_FAST | 3,331,433 | 9.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 4.6% |
| CALL_FUNCTION_EX | 734,880 | 2.2% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,487 | 64.2% |
| SWAP | 18,000 | 35.6% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,487 | 64.2% |
| SWAP | 18,000 | 35.6% |
| STORE_FAST | 80 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,004 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 3,840 | 95.9% |
| BINARY_SUBSCR | 164 | 4.1% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 140,760 | 99.9% |
| LOAD_CONST | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 106,160 | 75.3% |
| LOAD_CONST | 16,000 | 11.4% |
| LOAD_FAST | 16,000 | 11.4% |
| LIST_APPEND | 2,460 | 1.7% |
| CALL | 300 | 0.2% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 25,624,395 | 45.1% |
| LOAD_FAST | 17,083,456 | 30.1% |
| LOAD_ATTR_SLOT | 5,042,256 | 8.9% |
| LOAD_ATTR | 3,034,783 | 5.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,221,904 | 37.3% |
| BUILD_MAP | 10,996,576 | 19.3% |
| LOAD_CONST | 10,380,692 | 18.3% |
| LOAD_GLOBAL_BUILTIN | 4,707,068 | 8.3% |
| CALL_LIST_APPEND | 3,216,080 | 5.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,634,127 | 35.9% |
| LOAD_FAST | 7,266,755 | 27.1% |
| LOAD_ATTR | 3,067,203 | 11.4% |
| BINARY_OP_MULTIPLY_INT | 2,291,862 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,957 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,526 | 40.8% |
| STORE_FAST | 5,844,996 | 21.8% |
| RETURN_VALUE | 4,517,933 | 16.8% |
| POP_TOP | 1,123,848 | 4.2% |
| RESUME_CHECK | 1,063,720 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 23,270,822 | 83.1% |
| LOAD_FAST | 2,317,670 | 8.3% |
| CALL_INTRINSIC_1 | 1,257,013 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |
| BINARY_OP | 201,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,601,244 | 45.0% |
| RESUME_CHECK | 11,673,793 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,923 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,348,195 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,257,013 | 93.2% |
| BUILD_MAP | 91,342 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,509,574 | 98.5% |
| ENTER_EXECUTOR | 164,177 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,759 | 88.9% |
| POP_TOP | 698,055 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,813 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,088,968 | 54.9% |
| LOAD_FAST | 8,149,657 | 21.2% |
| CALL_TYPE_1 | 5,882,671 | 15.3% |
| LOAD_GLOBAL_MODULE | 1,180,067 | 3.1% |
| LOAD_CONST | 950,790 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,988,054 | 52.0% |
| BINARY_OP | 6,162,400 | 16.0% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.0% |
| UNARY_NOT | 3,442,785 | 9.0% |
| POP_JUMP_IF_TRUE | 2,279,038 | 5.9% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 20,047,956 | 52.9% |
| LOAD_FAST_LOAD_FAST | 10,513,933 | 27.8% |
| LOAD_GLOBAL_MODULE | 5,290,276 | 14.0% |
| LOAD_DEREF | 1,480,880 | 3.9% |
| LOAD_CONST | 174,989 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,665,528 | 91.6% |
| POP_JUMP_IF_TRUE | 3,187,331 | 8.4% |
| STORE_FAST | 4,560 | 0.0% |
| EXTENDED_ARG | 4,480 | 0.0% |
| RETURN_VALUE | 960 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 170,080 | 60.2% |
| LOAD_FAST | 110,540 | 39.1% |
| STORE_FAST_LOAD_FAST | 1,560 | 0.6% |
| LOAD_GLOBAL_MODULE | 300 | 0.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 282,560 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,237,536 | 26.7% |
| COPY | 1,074,000 | 23.2% |
| LOAD_FAST_LOAD_FAST | 872,880 | 18.9% |
| CALL_ISINSTANCE | 525,020 | 11.3% |
| LOAD_CONST | 236,817 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,339,336 | 28.9% |
| COPY | 1,074,000 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,067,720 | 23.1% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,617 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 13,001,466 | 41.0% |
| CALL_PY_EXACT_ARGS | 11,808,508 | 37.2% |
| LOAD_ATTR_PROPERTY | 5,065,849 | 16.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,196,851 | 3.8% |
| CALL_KW | 261,140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,788,265 | 68.6% |
| RETURN_GENERATOR | 9,879,654 | 31.1% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,182 | 0.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,285,120 | 98.7% |
| POP_JUMP_IF_NONE | 15,920 | 1.2% |
| ENTER_EXECUTOR | 740 | 0.1% |
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

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,141,898 | 99.4% |
| LOAD_DEREF | 128,924 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 23,270,822 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 27,666,874 | 32.9% |
| CALL_LIST_APPEND | 15,102,459 | 18.0% |
| STORE_SUBSCR_LIST_INT | 9,868,361 | 11.7% |
| POP_TOP | 9,281,341 | 11.1% |
| EXTENDED_ARG | 5,758,216 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 29,616,706 | 35.3% |
| LOAD_FAST | 10,368,934 | 12.3% |
| RESUME_CHECK | 9,219,700 | 11.0% |
| RETURN_CONST | 6,601,402 | 7.9% |
| ENTER_EXECUTOR | 5,307,720 | 6.3% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,066,149 | 33.0% |
| CALL_LIST_APPEND | 4,571,201 | 29.8% |
| GET_ITER | 2,378,213 | 15.5% |
| COMPARE_OP_INT | 1,719,917 | 11.2% |
| POP_JUMP_IF_FALSE | 810,356 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,612,773 | 43.1% |
| ENTER_EXECUTOR | 5,758,216 | 37.5% |
| FOR_ITER_LIST | 1,354,533 | 8.8% |
| FOR_ITER_RANGE | 642,400 | 4.2% |
| FOR_ITER_TUPLE | 395,000 | 2.6% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 67,462,887 | 64.8% |
| GET_ITER | 19,995,293 | 19.2% |
| SWAP | 7,638,512 | 7.3% |
| LOAD_FAST | 7,609,716 | 7.3% |
| ENTER_EXECUTOR | 1,313,309 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 71,417,303 | 68.6% |
| STORE_FAST | 8,335,893 | 8.0% |
| SWAP | 7,602,828 | 7.3% |
| RETURN_CONST | 4,698,572 | 4.5% |
| LOAD_FAST | 4,682,804 | 4.5% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,758,968 | 86.6% |
| STORE_FAST | 982,611 | 11.0% |
| STORE_DEREF | 185,717 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,822,699 | 76.2% |
| STORE_DEREF | 2,092,537 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,760,368 | 100.0% |
| ENTER_EXECUTOR | 100 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,758,968 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 17,248,988 | 36.1% |
| LOAD_FAST | 12,844,565 | 26.9% |
| LOAD_CONST | 10,977,625 | 23.0% |
| LOAD_FAST_LOAD_FAST | 5,893,749 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 539,784 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,051,054 | 62.8% |
| YIELD_VALUE | 12,829,226 | 26.8% |
| POP_JUMP_IF_TRUE | 4,907,002 | 10.3% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 20,907,478 | 30.9% |
| POP_JUMP_IF_TRUE | 16,086,021 | 23.7% |
| POP_TOP | 14,710,162 | 21.7% |
| MAP_ADD | 7,867,144 | 11.6% |
| CALL_LIST_APPEND | 2,241,049 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 67,462,887 | 99.6% |
| FOR_ITER_GEN | 100,764 | 0.1% |
| FOR_ITER_TUPLE | 80,791 | 0.1% |
| FOR_ITER_LIST | 53,858 | 0.1% |
| EXTENDED_ARG | 27,600 | 0.0% |


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
| STORE_FAST | 4,138,233 | 72.0% |
| POP_TOP | 734,264 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,890 | 3.3% |
| LOAD_FAST | 137,448 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,997,227 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,146 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,658 | 5.7% |
| STORE_FAST | 119,048 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,963,579 | 51.6% |
| BUILD_TUPLE | 1,568,861 | 27.3% |
| RETURN_VALUE | 510,834 | 8.9% |
| BINARY_SUBSCR | 489,424 | 8.5% |
| LOAD_ATTR_PROPERTY | 64,780 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,019,531 | 70.0% |
| JUMP_BACKWARD | 1,718,812 | 29.9% |
| LOAD_NAME | 4,800 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,347,315 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,348,195 | 99.9% |
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
| LOAD_FAST | 51,092,618 | 42.0% |
| LOAD_GLOBAL_MODULE | 33,555,507 | 27.6% |
| ENTER_EXECUTOR | 29,616,706 | 24.3% |
| CALL_TYPE_1 | 2,352,528 | 1.9% |
| LOAD_ATTR_SLOT | 2,297,075 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,824,124 | 30.2% |
| CONTAINS_OP | 20,047,956 | 16.5% |
| IS_OP | 17,248,988 | 14.2% |
| LOAD_FAST | 16,074,856 | 13.2% |
| PUSH_NULL | 14,957,382 | 12.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,615,951 | 33.9% |
| LOAD_CONST | 40,216,016 | 22.5% |
| RESUME_CHECK | 15,735,062 | 8.8% |
| BUILD_TUPLE | 10,380,692 | 5.8% |
| RETURN_CONST | 9,526,680 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,216,016 | 22.5% |
| CALL_BUILTIN_FAST | 24,056,781 | 13.4% |
| COMPARE_OP_INT | 20,758,384 | 11.6% |
| STORE_FAST | 14,275,502 | 8.0% |
| MAKE_FUNCTION | 12,376,501 | 6.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20,818,456 | 33.3% |
| NOP | 10,424,416 | 16.7% |
| LOAD_ATTR_SLOT | 6,405,949 | 10.2% |
| POP_JUMP_IF_FALSE | 4,644,739 | 7.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,094 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 20,988,917 | 33.6% |
| PUSH_NULL | 11,886,916 | 19.0% |
| LOAD_FAST | 9,396,186 | 15.0% |
| BINARY_SUBSCR | 6,405,949 | 10.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 5.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 161,641,758 | 17.7% |
| LOAD_GLOBAL_BUILTIN | 156,072,748 | 17.1% |
| RESUME_CHECK | 115,536,372 | 12.7% |
| POP_JUMP_IF_FALSE | 110,005,622 | 12.1% |
| STORE_FAST_STORE_FAST | 40,972,131 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,134,950 | 10.3% |
| LOAD_ATTR_METHOD_NO_DICT | 76,888,950 | 8.4% |
| LOAD_GLOBAL_MODULE | 61,810,234 | 6.8% |
| LOAD_CONST | 60,615,951 | 6.6% |
| RETURN_VALUE | 52,994,492 | 5.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,198,749 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,889 | 45.2% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,198,669 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,889 | 45.2% |
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
| STORE_FAST | 50,490,671 | 21.6% |
| LOAD_GLOBAL_BUILTIN | 28,706,192 | 12.3% |
| POP_JUMP_IF_FALSE | 28,700,373 | 12.3% |
| RESUME_CHECK | 18,619,072 | 8.0% |
| STORE_FAST_STORE_FAST | 15,653,230 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 26,365,901 | 11.3% |
| BUILD_TUPLE | 25,624,395 | 11.0% |
| COMPARE_OP | 21,088,968 | 9.0% |
| STORE_SUBSCR_LIST_INT | 18,857,119 | 8.1% |
| CALL_BUILTIN_FAST | 17,265,100 | 7.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,230 | 19.4% |
| LOAD_FAST | 34,169 | 18.8% |
| STORE_FAST | 26,899 | 14.8% |
| RESUME_CHECK | 10,927 | 6.0% |
| RESUME | 10,768 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,479 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,252 | 22.7% |
| LOAD_FAST | 39,544 | 21.8% |
| LOAD_ATTR | 14,067 | 7.7% |
| CALL | 9,824 | 5.4% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 28,280 | 38.8% |
| LOAD_NAME | 8,000 | 11.0% |
| CALL | 7,360 | 10.1% |
| LIST_APPEND | 4,800 | 6.6% |
| POP_TOP | 4,740 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 22,500 | 30.9% |
| LOAD_CONST | 19,560 | 26.9% |
| LOAD_NAME | 8,000 | 11.0% |
| CALL | 5,380 | 7.4% |
| EXTENDED_ARG | 4,340 | 6.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,082 | 90.0% |
| LOAD_DEREF | 120 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 500 | 41.6% |
| CALL | 322 | 26.8% |
| LOAD_FAST | 180 | 15.0% |
| PUSH_NULL | 100 | 8.3% |
| LOAD_SUPER_ATTR_ATTR | 100 | 8.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,275,145 | 37.6% |
| CACHE | 1,509,117 | 24.9% |
| CALL_PY_EXACT_ARGS | 770,626 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,428 | 10.8% |
| CALL | 523,747 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,771,338 | 62.3% |
| MAKE_CELL | 2,275,145 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,854,324 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,867,144 | 100.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 109,490,311 | 39.7% |
| CONTAINS_OP | 34,665,528 | 12.6% |
| COMPARE_OP_INT | 33,205,103 | 12.0% |
| IS_OP | 30,051,054 | 10.9% |
| COMPARE_OP | 19,988,054 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 110,005,622 | 39.9% |
| LOAD_GLOBAL_BUILTIN | 57,706,127 | 20.9% |
| RETURN_CONST | 29,196,468 | 10.6% |
| LOAD_FAST_LOAD_FAST | 28,700,373 | 10.4% |
| ENTER_EXECUTOR | 27,666,874 | 10.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,042,507 | 80.6% |
| BINARY_SUBSCR | 6,858,227 | 16.7% |
| LOAD_DEREF | 1,088,875 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |
| EXTENDED_ARG | 5,457 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,907,478 | 51.0% |
| LOAD_FAST_LOAD_FAST | 14,719,697 | 35.9% |
| LOAD_FAST | 2,501,573 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 1,438,684 | 3.5% |
| LOAD_CONST | 1,111,455 | 2.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,688,684 | 92.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,225,082 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,227,180 | 67.4% |
| LOAD_FAST_LOAD_FAST | 2,015,273 | 11.1% |
| LOAD_GLOBAL_MODULE | 1,878,977 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,227 | 7.6% |
| ENTER_EXECUTOR | 441,920 | 2.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 54,156,284 | 71.1% |
| TO_BOOL_INT | 8,697,524 | 11.4% |
| IS_OP | 4,907,002 | 6.4% |
| CONTAINS_OP | 3,187,331 | 4.2% |
| COMPARE_OP | 2,279,038 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,804,610 | 49.6% |
| JUMP_BACKWARD | 16,086,021 | 21.1% |
| LOAD_GLOBAL_BUILTIN | 5,256,642 | 6.9% |
| NOP | 4,184,044 | 5.5% |
| BUILD_LIST | 4,083,162 | 5.4% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,978 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,318 | 98.4% |
| COPY | 1,760 | 1.5% |
| LOAD_CONST | 160 | 0.1% |


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

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,196,468 | 51.1% |
| RESUME_CHECK | 10,045,928 | 17.6% |
| ENTER_EXECUTOR | 6,601,402 | 11.6% |
| FOR_ITER | 4,698,572 | 8.2% |
| STORE_SUBSCR | 3,290,901 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,285,136 | 56.5% |
| LOAD_CONST | 9,526,680 | 16.7% |
| POP_TOP | 9,275,890 | 16.2% |
| TO_BOOL_BOOL | 3,462,837 | 6.1% |
| STORE_FAST | 1,541,336 | 2.7% |


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
| JUMP_BACKWARD | 17,700 | 91.8% |
| ENTER_EXECUTOR | 1,580 | 8.2% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 10,357,728 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,806,622 | 94.7% |
| STORE_FAST | 298,294 | 2.9% |
| STORE_DEREF | 95,646 | 0.9% |
| LOAD_CONST | 52,360 | 0.5% |
| LOAD_GLOBAL_MODULE | 42,912 | 0.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,978 | 82.3% |
| LOAD_FAST | 98,460 | 16.6% |
| STORE_ATTR | 3,902 | 0.7% |
| SWAP | 2,153 | 0.4% |
| LOAD_DEREF | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,740 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,318 | 19.7% |
| LOAD_FAST | 89,975 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,577,880 | 46.5% |
| IMPORT_FROM | 2,092,537 | 27.2% |
| LOAD_ATTR | 1,558,875 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,646 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,840 | 46.4% |
| POP_TOP | 1,906,820 | 24.8% |
| LOAD_DEREF | 1,298,392 | 16.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.3% |
| IMPORT_FROM | 185,717 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,560,940 | 13.0% |
| LOAD_ATTR | 36,824,124 | 12.4% |
| BINARY_OP | 24,216,881 | 8.1% |
| LOAD_ATTR_SLOT | 22,509,101 | 7.6% |
| LOAD_CONST | 14,275,502 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 161,641,758 | 54.3% |
| LOAD_FAST_LOAD_FAST | 50,490,671 | 17.0% |
| LOAD_GLOBAL_BUILTIN | 32,310,457 | 10.9% |
| LOAD_GLOBAL_MODULE | 11,364,105 | 3.8% |
| STORE_FAST | 9,345,279 | 3.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,377 | 69.6% |
| FOR_ITER_TUPLE | 409,685 | 22.6% |
| FOR_ITER | 92,961 | 5.1% |
| FOR_ITER_RANGE | 47,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,221,335 | 67.5% |
| LOAD_ATTR_PROPERTY | 202,423 | 11.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 187,061 | 10.3% |
| LOAD_DEREF | 51,440 | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,840 | 2.5% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 96,788,764 | 93.5% |
| RETURN_VALUE | 3,248,255 | 3.1% |
| UNPACK_SEQUENCE_TUPLE | 1,397,047 | 1.4% |
| STORE_FAST_STORE_FAST | 771,570 | 0.7% |
| BUILD_LIST | 413,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,972,131 | 39.6% |
| LOAD_GLOBAL_BUILTIN | 22,007,742 | 21.3% |
| LOAD_DEREF | 20,818,456 | 20.1% |
| LOAD_FAST_LOAD_FAST | 15,653,230 | 15.1% |
| LOAD_GLOBAL_MODULE | 1,958,160 | 1.9% |


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

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 38,060 | 28.7% |
| MAKE_FUNCTION | 33,580 | 25.3% |
| CALL | 21,600 | 16.3% |
| LOAD_CONST | 9,120 | 6.9% |
| SET_FUNCTION_ATTRIBUTE | 7,660 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 48,660 | 36.7% |
| LOAD_NAME | 28,280 | 21.3% |
| IMPORT_FROM | 26,000 | 19.6% |
| POP_TOP | 12,080 | 9.1% |
| RETURN_CONST | 4,860 | 3.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 9,400,081 | 20.9% |
| LOAD_FAST_AND_CLEAR | 9,198,669 | 20.4% |
| FOR_ITER | 7,602,828 | 16.9% |
| BUILD_MAP | 4,716,088 | 10.5% |
| LOAD_FAST | 4,641,368 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,400,301 | 20.9% |
| STORE_FAST | 7,931,375 | 17.6% |
| FOR_ITER | 7,638,512 | 17.0% |
| POP_TOP | 5,778,548 | 12.8% |
| BUILD_MAP | 4,716,088 | 10.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,432 | 26.2% |
| FOR_ITER | 6,801 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 15.9% |
| LOAD_FAST | 3,989 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,651 | 46.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,425 | 23.7% |
| STORE_FAST | 8,243 | 20.7% |
| UNPACK_SEQUENCE_TUPLE | 1,127 | 2.8% |
| UNPACK_SEQUENCE | 918 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,829,226 | 55.6% |
| ENTER_EXECUTOR | 4,716,414 | 20.4% |
| CALL_ISINSTANCE | 2,335,159 | 10.1% |
| LOAD_FAST | 1,146,814 | 5.0% |
| YIELD_VALUE | 677,432 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,247,546 | 96.3% |
| YIELD_VALUE | 677,432 | 2.9% |
| STORE_FAST | 163,113 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,061 | 38.0% |
| CALL | 11,098 | 23.3% |
| CALL_PY_EXACT_ARGS | 6,087 | 12.8% |
| POP_TOP | 3,961 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,683 | 37.2% |
| LOAD_GLOBAL | 10,768 | 22.7% |
| LOAD_CONST | 8,761 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,361 | 7.1% |


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

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,634,830 | 69.6% |
| LOAD_FAST_LOAD_FAST | 573,895 | 15.2% |
| BINARY_SUBSCR_DICT | 422,960 | 11.2% |
| CALL_BUILTIN_CLASS | 81,168 | 2.1% |
| LOAD_FAST | 43,682 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,576,403 | 41.6% |
| SWAP | 944,653 | 25.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 540,580 | 14.3% |
| LOAD_CONST | 269,038 | 7.1% |
| LOAD_FAST | 201,507 | 5.3% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 480,720 | 86.9% |
| CALL_METHOD_DESCRIPTOR_O | 39,600 | 7.2% |
| LOAD_FAST | 15,880 | 2.9% |
| LOAD_FAST_LOAD_FAST | 8,400 | 1.5% |
| BINARY_SUBSCR_LIST_INT | 3,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 499,720 | 90.4% |
| RETURN_VALUE | 41,840 | 7.6% |
| LOAD_FAST | 6,720 | 1.2% |
| CALL_BUILTIN_FAST | 1,760 | 0.3% |
| CALL | 1,720 | 0.3% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,677 | 60.4% |
| LOAD_ATTR_SLOT | 723,525 | 26.2% |
| LOAD_FAST_LOAD_FAST | 276,592 | 10.0% |
| LOAD_FAST | 94,255 | 3.4% |
| BINARY_OP | 1,403 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,862 | 82.9% |
| LOAD_FAST_LOAD_FAST | 181,162 | 6.6% |
| STORE_FAST | 175,557 | 6.4% |
| LOAD_FAST | 83,302 | 3.0% |
| LOAD_GLOBAL_MODULE | 25,185 | 0.9% |


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
| LOAD_CONST | 1,569,002 | 63.1% |
| LOAD_FAST_LOAD_FAST | 607,040 | 24.4% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,669 | 4.9% |
| BINARY_OP | 2,170 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,082,420 | 43.5% |
| STORE_FAST | 710,286 | 28.6% |
| BINARY_OP | 311,629 | 12.5% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,880 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,129,596 | 34.6% |
| LOAD_FAST_LOAD_FAST | 923,873 | 28.3% |
| LOAD_CONST | 642,800 | 19.7% |
| CALL_TUPLE_1 | 443,840 | 13.6% |
| RETURN_VALUE | 114,591 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 866,750 | 26.6% |
| RETURN_VALUE | 809,236 | 24.8% |
| BINARY_OP_ADD_INT | 422,960 | 13.0% |
| PUSH_NULL | 376,980 | 11.6% |
| SWAP | 318,100 | 9.8% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 59,680 | 37.5% |
| LOAD_FAST_LOAD_FAST | 40,800 | 25.6% |
| ENTER_EXECUTOR | 39,680 | 24.9% |
| LOAD_CONST | 14,564 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,260 | 100.0% |
| RETURN_VALUE | 2 | 0.0% |
| LOAD_CONST | 2 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,365,901 | 90.9% |
| COPY | 1,067,720 | 3.7% |
| LOAD_CONST | 1,026,766 | 3.5% |
| CALL_BUILTIN_CLASS | 282,490 | 1.0% |
| LOAD_FAST | 204,208 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,408,441 | 32.4% |
| SWAP | 9,400,081 | 32.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,524,699 | 25.9% |
| LOAD_CONST | 1,068,180 | 3.7% |
| RETURN_VALUE | 432,325 | 1.5% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,880 | 98.0% |
| LOAD_FAST | 360 | 1.9% |
| BINARY_SUBSCR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,880 | 98.0% |
| LIST_APPEND | 380 | 2.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,721,712 | 97.0% |
| LOAD_FAST | 263,318 | 2.9% |
| BINARY_SUBSCR | 2,726 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,578 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 322,163 | 3.6% |
| BINARY_OP | 205,240 | 2.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 77,500 | 80.9% |
| LOAD_FAST_LOAD_FAST | 16,820 | 17.6% |
| LOAD_GLOBAL_MODULE | 1,000 | 1.0% |
| CALL | 240 | 0.3% |
| PUSH_NULL | 160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 95,740 | 100.0% |
| COPY_FREE_VARS | 20 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,222,007 | 90.9% |
| BINARY_OP_ADD_INT | 540,580 | 3.7% |
| LOAD_FAST_LOAD_FAST | 480,520 | 3.3% |
| LOAD_ATTR | 152,040 | 1.0% |
| LOAD_DEREF | 83,580 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,692,615 | 87.2% |
| COPY_FREE_VARS | 1,196,851 | 8.2% |
| MAKE_CELL | 654,428 | 4.5% |
| POP_TOP | 7,360 | 0.1% |
| CALL_PY_EXACT_ARGS | 670 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,796,690 | 32.4% |
| CALL_BUILTIN_CLASS | 1,959,638 | 22.7% |
| LOAD_CONST | 710,920 | 8.2% |
| CALL_LEN | 611,306 | 7.1% |
| BINARY_SUBSCR | 571,806 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,070,352 | 35.6% |
| CALL_BUILTIN_CLASS | 1,959,638 | 22.7% |
| GET_ITER | 1,728,755 | 20.0% |
| CALL | 284,377 | 3.3% |
| BINARY_SUBSCR_LIST_INT | 282,490 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,056,781 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,265,100 | 39.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,238 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 55,484 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,002,462 | 41.8% |
| STORE_FAST | 10,923,929 | 25.4% |
| TO_BOOL | 10,287,220 | 23.9% |
| PUSH_NULL | 2,129,900 | 4.9% |
| RETURN_VALUE | 1,500,334 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,788 | 94.4% |
| LOAD_FAST | 135,021 | 2.6% |
| BINARY_OP | 119,108 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,068 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 127,921 | 2.5% |
| CALL_BUILTIN_CLASS | 119,108 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,710,522 | 41.7% |
| RETURN_GENERATOR | 10,184,434 | 27.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,619,077 | 14.9% |
| LOAD_ATTR_SLOT | 4,873,709 | 12.9% |
| BINARY_OP | 1,095,153 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,594,187 | 36.1% |
| RETURN_VALUE | 11,433,130 | 30.4% |
| TO_BOOL_BOOL | 9,862,070 | 26.2% |
| GET_ITER | 2,591,164 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,788,442 | 57.2% |
| LOAD_GLOBAL_BUILTIN | 18,939,136 | 30.3% |
| LOAD_DEREF | 3,018,126 | 4.8% |
| LOAD_FAST_LOAD_FAST | 2,763,796 | 4.4% |
| LOAD_FAST | 1,614,896 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,536,668 | 95.2% |
| YIELD_VALUE | 2,335,159 | 3.7% |
| COPY | 525,020 | 0.8% |
| RETURN_VALUE | 127,559 | 0.2% |
| TO_BOOL | 9,660 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,056,255 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 185,800 | 0.7% |
| RETURN_VALUE | 95,200 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,271,191 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,676,882 | 34.4% |
| LOAD_CONST | 7,191,775 | 25.6% |
| CALL_BUILTIN_CLASS | 611,306 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,555,578 | 64.8% |
| BUILD_TUPLE | 3,216,080 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 959,820 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,102,459 | 62.9% |
| EXTENDED_ARG | 4,571,201 | 19.0% |
| JUMP_BACKWARD | 2,241,049 | 9.3% |
| LOAD_FAST | 1,681,762 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,171,322 | 68.9% |
| LOAD_CONST | 2,388,777 | 10.8% |
| BUILD_LIST | 2,294,415 | 10.4% |
| BUILD_MAP | 1,561,360 | 7.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 272,750 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,875,865 | 58.5% |
| STORE_FAST | 3,415,951 | 15.5% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.1% |
| POP_TOP | 908,874 | 4.1% |
| GET_ITER | 737,615 | 3.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,220 | 46.6% |
| LOAD_ATTR_METHOD_NO_DICT | 1,620 | 34.0% |
| LOAD_FAST | 800 | 16.8% |
| CALL | 120 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,860 | 39.1% |
| LOAD_FAST_LOAD_FAST | 940 | 19.7% |
| GET_ITER | 880 | 18.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 680 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 220 | 4.6% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 24,516,312 | 83.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,627 | 16.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,787 | 0.4% |
| LOAD_ATTR | 72,820 | 0.2% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,456,821 | 49.0% |
| STORE_FAST | 9,690,864 | 32.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,788 | 16.5% |
| CALL_BUILTIN_CLASS | 169,733 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,787 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.2% |
| LOAD_CONST | 1,226,582 | 26.7% |
| LOAD_FAST | 296,920 | 6.5% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.4% |
| LOAD_CONST | 1,224,582 | 26.7% |
| TO_BOOL_NONE | 48,400 | 1.1% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,801,735 | 31.4% |
| LOAD_FAST | 15,674,662 | 23.6% |
| GET_ITER | 12,994,912 | 19.6% |
| LOAD_FAST_LOAD_FAST | 12,253,292 | 18.5% |
| LOAD_SUPER_ATTR_METHOD | 1,539,358 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 49,419,434 | 74.5% |
| COPY_FREE_VARS | 11,808,508 | 17.8% |
| RETURN_GENERATOR | 4,117,672 | 6.2% |
| MAKE_CELL | 770,626 | 1.2% |
| CALL_PY_EXACT_ARGS | 144,999 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,622,171 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,413,525 | 30.8% |
| ENTER_EXECUTOR | 974,904 | 21.2% |
| RETURN_VALUE | 192,628 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,896 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,373,482 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,759 | 1.2% |
| CALL_PY_WITH_DEFAULTS | 220 | 0.0% |
| RESUME | 120 | 0.0% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,068 | 80.4% |
| LOAD_FAST | 1,017,337 | 17.4% |
| STORE_FAST | 105,788 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,168 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,268 | 80.4% |
| BINARY_SUBSCR_DICT | 443,840 | 7.6% |
| STORE_FAST | 353,228 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,729,658 | 99.2% |
| LOAD_CONST | 120,038 | 0.8% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,081 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,822 | 43.3% |
| COMPARE_OP | 5,882,671 | 39.6% |
| LOAD_ATTR | 2,352,528 | 15.8% |
| IS_OP | 64,298 | 0.4% |
| BUILD_TUPLE | 55,800 | 0.4% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,706 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,604 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,090 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,758,384 | 42.6% |
| LOAD_FAST_LOAD_FAST | 16,197,318 | 33.2% |
| CALL_LEN | 10,271,191 | 21.1% |
| LOAD_FAST | 1,020,444 | 2.1% |
| LOAD_ATTR_SLOT | 225,517 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,205,103 | 68.1% |
| BINARY_OP | 6,304,740 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.7% |
| EXTENDED_ARG | 1,719,917 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,566,000 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 68.9% |
| LOAD_CONST | 4,336,310 | 29.8% |
| LOAD_GLOBAL_MODULE | 192,459 | 1.3% |
| LOAD_ATTR | 3,160 | 0.0% |
| LOAD_FAST | 2,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,481,077 | 99.4% |
| YIELD_VALUE | 79,952 | 0.5% |
| POP_JUMP_IF_TRUE | 3,520 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,764 | 52.6% |
| GET_ITER | 90,809 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,844 | 52.1% |
| POP_TOP | 90,649 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,844,913 | 37.4% |
| GET_ITER | 4,320,661 | 33.3% |
| EXTENDED_ARG | 1,354,533 | 10.4% |
| SWAP | 1,221,501 | 9.4% |
| ENTER_EXECUTOR | 1,158,374 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,931,894 | 61.2% |
| LOAD_FAST | 2,085,173 | 16.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,542,334 | 11.9% |
| STORE_FAST_LOAD_FAST | 1,260,377 | 9.7% |
| RETURN_CONST | 85,483 | 0.7% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 669,383 | 47.9% |
| EXTENDED_ARG | 642,400 | 46.0% |
| SWAP | 38,880 | 2.8% |
| LOAD_FAST | 29,360 | 2.1% |
| JUMP_BACKWARD | 16,540 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,975 | 93.5% |
| STORE_FAST_LOAD_FAST | 47,440 | 3.4% |
| RETURN_CONST | 35,968 | 2.6% |
| LOAD_FAST | 3,780 | 0.3% |
| LOAD_GLOBAL_MODULE | 1,200 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,876,110 | 84.9% |
| LOAD_FAST | 518,184 | 4.5% |
| ENTER_EXECUTOR | 448,463 | 3.9% |
| EXTENDED_ARG | 395,000 | 3.4% |
| SWAP | 299,856 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,112,815 | 86.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 426,103 | 3.7% |
| STORE_FAST_LOAD_FAST | 409,685 | 3.5% |
| RETURN_CONST | 369,280 | 3.2% |
| LOAD_GLOBAL_BUILTIN | 117,460 | 1.0% |


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
| LOAD_FAST | 5,479,006 | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,061,141 | 11.7% |
| LOAD_DEREF | 1,058,601 | 11.7% |
| COPY | 956,400 | 10.5% |
| LOAD_GLOBAL_MODULE | 481,783 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,522 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,238 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,225,082 | 13.5% |
| STORE_FAST | 1,076,301 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,061,141 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,888,950 | 85.8% |
| RETURN_VALUE | 4,635,696 | 5.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.5% |
| LOAD_GLOBAL_MODULE | 1,965,147 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,522 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,795,349 | 34.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,516,312 | 27.4% |
| CALL_PY_EXACT_ARGS | 20,801,735 | 23.2% |
| LOAD_CONST | 4,053,009 | 4.5% |
| LOAD_DEREF | 3,319,094 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 20,988,917 | 71.3% |
| LOAD_ATTR_SLOT | 4,711,168 | 16.0% |
| LOAD_FAST | 3,523,803 | 12.0% |
| LOAD_ATTR | 147,529 | 0.5% |
| STORE_FAST_LOAD_FAST | 45,840 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,101,142 | 51.3% |
| LOAD_FAST_LOAD_FAST | 9,209,799 | 31.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,627 | 16.3% |
| CALL_PY_EXACT_ARGS | 313,676 | 1.1% |
| LOAD_CONST | 6,561 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260,906 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,399 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,297 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,670 | 6.3% |
| CALL | 57,378 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR | 19,780 | 1.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,598,374 | 87.2% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| ENTER_EXECUTOR | 2,966,080 | 5.2% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 215,930 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,385,186 | 74.5% |
| CALL_BUILTIN_O | 5,619,077 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,921,328 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,677 | 2.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 992,998 | 60.3% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.1% |
| LOAD_DEREF | 144,340 | 8.8% |
| LOAD_ATTR | 12,020 | 0.7% |
| ENTER_EXECUTOR | 10,750 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.0% |
| TO_BOOL_STR | 478,200 | 29.0% |
| TO_BOOL_BOOL | 408,988 | 24.8% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,302,069 | 90.4% |
| ENTER_EXECUTOR | 1,312,387 | 4.7% |
| RETURN_VALUE | 642,537 | 2.3% |
| STORE_FAST_LOAD_FAST | 202,423 | 0.7% |
| LOAD_DEREF | 190,744 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,814,233 | 67.2% |
| COPY_FREE_VARS | 5,065,849 | 18.1% |
| GET_ITER | 1,920,892 | 6.9% |
| TO_BOOL_BOOL | 709,450 | 2.5% |
| STORE_FAST | 505,785 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,134,950 | 98.6% |
| LOAD_ATTR_SLOT | 613,668 | 0.6% |
| ENTER_EXECUTOR | 553,380 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,054 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 69,922 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,433,886 | 35.0% |
| STORE_FAST | 22,509,101 | 23.6% |
| LOAD_DEREF | 6,405,949 | 6.7% |
| LOAD_FAST | 5,202,960 | 5.4% |
| LOAD_CONST | 5,202,538 | 5.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,706,127 | 25.5% |
| RESUME_CHECK | 41,267,630 | 18.3% |
| STORE_FAST | 32,310,457 | 14.3% |
| STORE_FAST_STORE_FAST | 22,007,742 | 9.7% |
| LOAD_FAST | 20,355,095 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 156,072,748 | 69.1% |
| LOAD_FAST_LOAD_FAST | 28,706,192 | 12.7% |
| CALL_ISINSTANCE | 18,939,136 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 8,973,399 | 4.0% |
| LOAD_DEREF | 3,220,984 | 1.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,810,234 | 50.8% |
| RESUME_CHECK | 16,028,923 | 13.2% |
| STORE_FAST | 11,364,105 | 9.3% |
| POP_JUMP_IF_FALSE | 9,674,922 | 8.0% |
| NOP | 6,377,998 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 35,788,442 | 29.4% |
| LOAD_ATTR | 33,555,507 | 27.6% |
| LOAD_FAST | 29,412,203 | 24.2% |
| CONTAINS_OP | 5,290,276 | 4.4% |
| LOAD_FAST_LOAD_FAST | 3,280,460 | 2.7% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,688 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,182,088 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,620 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,358 | 85.1% |
| LOAD_GLOBAL_MODULE | 172,262 | 9.5% |
| LOAD_FAST | 78,580 | 4.3% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 99,234,864 | 38.7% |
| CALL_PY_EXACT_ARGS | 49,419,434 | 19.3% |
| COPY_FREE_VARS | 21,788,265 | 8.5% |
| LOAD_ATTR_PROPERTY | 18,814,233 | 7.3% |
| POP_TOP | 14,318,586 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,536,372 | 45.0% |
| LOAD_GLOBAL_BUILTIN | 41,267,630 | 16.1% |
| NOP | 21,365,997 | 8.3% |
| LOAD_FAST_LOAD_FAST | 18,619,072 | 7.3% |
| LOAD_GLOBAL_MODULE | 16,028,923 | 6.2% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 661,220 | 64.2% |
| LOAD_CONST | 367,932 | 35.7% |
| SEND | 620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 646,240 | 62.8% |
| POP_TOP | 352,872 | 34.3% |
| YIELD_VALUE | 15,060 | 1.5% |
| END_SEND | 15,020 | 1.5% |
| SEND | 580 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,846 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,133 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,735 | 36.0% |
| RETURN_CONST | 887,422 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,641 | 52.2% |
| LOAD_FAST | 4,285,366 | 47.3% |
| STORE_ATTR_SLOT | 41,791 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,673,421 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,447 | 24.9% |
| LOAD_CONST | 1,890,910 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,869 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,571,893 | 68.9% |
| LOAD_FAST | 397,970 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,333 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,652,380 | 72.4% |
| EXTENDED_ARG | 226,750 | 9.9% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.0% |
| LOAD_FAST | 165,801 | 7.3% |
| LOAD_GLOBAL_MODULE | 38,953 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,857,119 | 93.3% |
| SWAP | 1,067,720 | 5.3% |
| BINARY_SUBSCR_DICT | 112,800 | 0.6% |
| LOAD_FAST | 99,422 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,025,141 | 49.6% |
| ENTER_EXECUTOR | 9,868,361 | 48.8% |
| JUMP_BACKWARD | 250,259 | 1.2% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,732 | 98.7% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| ENTER_EXECUTOR | 480 | 0.2% |
| TO_BOOL | 391 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 217,402 | 95.0% |
| POP_JUMP_IF_FALSE | 9,906 | 4.3% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 55 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 59,536,668 | 35.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,385,186 | 25.0% |
| LOAD_FAST | 21,602,965 | 12.7% |
| CALL_BUILTIN_FAST | 18,002,462 | 10.6% |
| CALL_BUILTIN_O | 9,862,070 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 109,490,311 | 64.5% |
| POP_JUMP_IF_TRUE | 54,156,284 | 31.9% |
| EXTENDED_ARG | 5,066,149 | 3.0% |
| UNARY_NOT | 1,085,094 | 0.6% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,175,128 | 95.3% |
| BINARY_OP | 732,810 | 3.8% |
| BINARY_SUBSCR_TUPLE_INT | 63,296 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,280 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,862 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,364,212 | 54.4% |
| POP_JUMP_IF_TRUE | 8,697,524 | 45.6% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 163 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,229,103 | 97.5% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,139 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |
| TO_BOOL | 2,143 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 824,053 | 36.0% |
| POP_JUMP_IF_TRUE | 784,617 | 34.3% |
| UNARY_NOT | 661,895 | 28.9% |
| EXTENDED_ARG | 15,720 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,849 | 69.4% |
| RETURN_VALUE | 389,375 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,676 | 11.1% |
| CALL_METHOD_DESCRIPTOR_O | 48,400 | 1.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,954 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,945,050 | 73.3% |
| POP_JUMP_IF_TRUE | 689,947 | 26.0% |
| EXTENDED_ARG | 15,420 | 0.6% |
| TO_BOOL_BOOL | 1,680 | 0.1% |
| TO_BOOL | 1,500 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 95.1% |
| LOAD_FAST | 11,300 | 2.2% |
| STORE_FAST_LOAD_FAST | 11,200 | 2.2% |
| COPY | 2,120 | 0.4% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 498,580 | 99.1% |
| POP_JUMP_IF_TRUE | 4,520 | 0.9% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,335 | 67.4% |
| RETURN_VALUE | 49,120 | 27.5% |
| CALL_BUILTIN_CLASS | 2,600 | 1.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 1.0% |
| BINARY_SUBSCR_LIST_INT | 1,240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 64.4% |
| STORE_FAST_STORE_FAST | 63,655 | 35.6% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 885,034 | 55.6% |
| RETURN_VALUE | 660,917 | 41.5% |
| STORE_FAST | 40,240 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,127 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,397,047 | 87.8% |
| STORE_FAST | 154,771 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 71,417,303 | 71.0% |
| RETURN_VALUE | 19,466,609 | 19.4% |
| BINARY_SUBSCR_LIST_INT | 7,524,699 | 7.5% |
| FOR_ITER_LIST | 1,542,334 | 1.5% |
| FOR_ITER_TUPLE | 426,103 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 96,788,764 | 96.2% |
| STORE_DEREF | 3,577,880 | 3.6% |
| STORE_FAST | 218,497 | 0.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,680 | 0.0% |
| UNPACK_SEQUENCE_LIST | 1,760 | 0.0% |


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
|     deferred | 35,268,111 | 78.5% |
|          hit | 9,591,962 | 21.4% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,702 | 11.6% |
| Failure | 51,314 | 88.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,458 | 18.4% |
| multiply different types | 7,461 | 14.5% |
| subtract other | 6,800 | 13.3% |
| and int | 4,145 | 8.1% |
| rshift | 3,825 | 7.5% |
| or | 3,700 | 7.2% |
| power | 2,847 | 5.5% |
| true divide different types | 2,521 | 4.9% |
| multiply other | 2,360 | 4.6% |
| remainder | 2,311 | 4.5% |
| add different types | 1,945 | 3.8% |
| floor divide | 1,264 | 2.5% |
| subtract different types | 1,194 | 2.3% |
| xor | 581 | 1.1% |
| and other | 378 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 223 | 0.4% |
| true divide float | 1 | 0.0% |


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
|     deferred | 23,788,119 | 36.5% |
|          hit | 41,421,798 | 63.5% |
|         miss | 14,948 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,706 | 32.6% |
| Failure | 15,967 | 67.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 12,146 | 76.1% |
| out of range | 2,040 | 12.8% |
| buffer int | 1,760 | 11.0% |
| array int | 20 | 0.1% |
| tuple slice | 1 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,104,775 | 6.3% |
|        deopt | 22,840 | 0.0% |
|          hit | 355,049,321 | 85.9% |
|         miss | 31,512,416 | 7.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 675,014 | 90.2% |
| Failure | 73,203 | 9.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,942 | 39.5% |
| code complex parameters | 14,060 | 19.2% |
| class no vectorcall | 9,220 | 12.6% |
| cfunc varargs keywords | 6,382 | 8.7% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.4% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,164 | 3.0% |
| meth descr varargs | 1,915 | 2.6% |
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
|     deferred | 38,337,017 | 37.5% |
|          hit | 63,315,435 | 61.9% |
|         miss | 575,921 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,458 | 22.8% |
| Failure | 69,349 | 77.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,497 | 26.7% |
| other | 15,273 | 22.0% |
| different types | 12,270 | 17.7% |
| tuple | 10,046 | 14.5% |
| string | 9,960 | 14.4% |
| bool | 2,103 | 3.0% |
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
|     deferred | 104,010,331 | 79.8% |
|          hit | 25,573,606 | 19.6% |
|         miss | 610,160 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 23,386 | 21.5% |
| Failure | 85,319 | 78.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 57,117 | 66.9% |
| set | 9,047 | 10.6% |
| zip | 7,600 | 8.9% |
| enumerate | 4,235 | 5.0% |
| other | 2,720 | 3.2% |
| itertools | 1,940 | 2.3% |
| dict keys | 1,640 | 1.9% |
| reversed list | 860 | 1.0% |
| dict values | 80 | 0.1% |
| ascii string | 80 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120,274,359 | 27.8% |
|        deopt | 20 | 0.0% |
|          hit | 245,665,421 | 56.7% |
|         miss | 65,936,519 | 15.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,321,784 | 89.2% |
| Failure | 160,281 | 10.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 60,855 | 38.0% |
| mutable class | 58,780 | 36.7% |
| method | 10,468 | 6.5% |
| has managed dict | 8,780 | 5.5% |
| overridden | 8,675 | 5.4% |
| shadowed | 5,300 | 3.3% |
| class method obj | 3,900 | 2.4% |
| builtin class method | 1,320 | 0.8% |
| not managed dict | 1,103 | 0.7% |
| non object slot | 680 | 0.4% |
| not in keys | 300 | 0.2% |
| non overriding descriptor | 60 | 0.0% |
| module attr not found | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 89,764 | 0.0% |
|          hit | 347,437,002 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,891 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 602 | 0.0% |
|          hit | 2,990,208 | 100.0% |

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
|          hit | 999,112 | 67.8% |
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
|     deferred | 540,744 | 4.2% |
|          hit | 10,197,497 | 78.4% |
|         miss | 2,222,340 | 17.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,851 | 92.3% |
| Failure | 3,902 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,960 | 50.2% |
| not managed dict | 1,442 | 37.0% |
| overridden | 240 | 6.2% |
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
|     deferred | 3,422,783 | 13.2% |
|          hit | 22,489,159 | 86.8% |

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
|     deferred | 12,842,134 | 6.2% |
|          hit | 194,093,084 | 93.6% |
|         miss | 440,880 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,907 | 72.2% |
| Failure | 23,064 | 27.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,789 | 46.8% |
| number | 3,535 | 15.3% |
| mapping | 3,300 | 14.3% |
| dict | 2,340 | 10.1% |
| other | 1,623 | 7.0% |
| set | 1,437 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,694 | 0.0% |
|          hit | 102,361,714 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,372 | 93.6% |
| Failure | 778 | 6.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 718 | 92.3% |
| iterator | 60 | 7.7% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 3,007,283,106 | 54.2% |
| Not specialized | 779,627,331 | 14.0% |
| Specialized hits | 1,663,357,803 | 30.0% |
| Specialized misses | 101,364,424 | 1.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 120,274,359 | 32.9% |
| FOR_ITER | 104,010,331 | 28.5% |
| COMPARE_OP | 38,337,017 | 10.5% |
| BINARY_OP | 35,268,111 | 9.7% |
| CALL | 26,104,775 | 7.1% |
| BINARY_SUBSCR | 23,788,119 | 6.5% |
| TO_BOOL | 12,842,134 | 3.5% |
| STORE_SUBSCR | 3,422,783 | 0.9% |
| STORE_ATTR | 540,744 | 0.1% |
| SEND | 439,140 | 0.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,448,409 | 36.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,769,441 | 15.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,462,854 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 9,129,267 | 9.0% |
| CALL_PY_EXACT_ARGS | 7,818,745 | 7.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,375 | 6.4% |
| LOAD_ATTR_PROPERTY | 4,106,426 | 4.1% |
| CALL_BUILTIN_O | 2,661,214 | 2.6% |
| STORE_ATTR_SLOT | 2,221,360 | 2.2% |
| COMPARE_OP_INT | 574,321 | 0.6% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,646,354 | 48.8% |
| Calls to Python functions inlined | 134,046,481 | 51.2% |
| Calls via PyEval_EvalFrame (total) | 127,646,354 | 48.8% |
| Calls via PyEval_EvalFrame (vector) | 98,455,765 | 37.6% |
| Calls via PyEval_EvalFrame (generator) | 29,190,589 | 11.2% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,448,465 | 37.6% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,913 | 9.0% |
| Calls via PyEval_EvalFrame (function ex) | 11,825,296 | 4.5% |
| Calls via PyEval_EvalFrame (api) | 53,327,009 | 20.4% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,522 | 0.5% |
| Frames pushed | 112,453,750 | 43.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,366,398 | 54.3% |
| Frees to freelist | 363,609,353 |  |
| Allocations | 305,536,956 | 45.7% |
| Allocations to 512 bytes | 304,472,998 | 45.5% |
| Allocations to 4 kbytes | 1,039,498 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,211,953 |  |
| New values | 1,057,567 |  |
| Interpreter increfs | 2,654,603,738 | 65.3% |
| Interpreter decrefs | 3,069,229,552 | 66.0% |
| Increfs | 1,412,217,293 | 34.7% |
| Decrefs | 1,578,242,622 | 34.0% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,914,586 |  |
| Method cache misses | 4,154,646 |  |
| Method cache collisions | 5,612,239 |  |
| Method cache dunder hits | 346,720,938 |  |
| Method cache dunder misses | 1,458,216 |  |


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
| Optimization attempts | 3,981,895 |  |
| Traces created | 10,021 | 0.3% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 112 | 0.0% |
| Trace too long | 40 | 0.0% |
| Trace too short | 3,971,874 | 99.7% |
| Inner loop found | 80 | 0.0% |
| Recursive call | 160 | 0.0% |
| Traces executed | 83,990,332 |  |
| Uops executed | 1,154,594,052 | 13.75 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 0.2% |
| <= 16 | 3,344 | 33.4% |
| <= 32 | 4,158 | 41.5% |
| <= 64 | 1,725 | 17.2% |
| <= 128 | 774 | 7.7% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 20 | 0.2% |
| <= 8 | 20 | 0.2% |
| <= 16 | 4,062 | 40.5% |
| <= 32 | 3,900 | 38.9% |
| <= 64 | 1,685 | 16.8% |
| <= 128 | 334 | 3.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 2,712,020 | 3.2% |
| <= 4 | 16,820 | 0.0% |
| <= 8 | 19,686,521 | 23.4% |
| <= 16 | 39,804,909 | 47.4% |
| <= 32 | 18,812,987 | 22.4% |
| <= 64 | 2,579,199 | 3.1% |
| <= 128 | 333,136 | 0.4% |
| <= 256 | 34,981 | 0.0% |
| <= 512 | 9,579 | 0.0% |
| <= 1,024 | 100 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 275,854,255 | 23.9% | 23.9% |  |
| LOAD_FAST | 107,122,225 | 9.3% | 33.2% |  |
| _POP_JUMP_IF_TRUE | 99,629,769 | 8.6% | 41.8% |  |
| _EXIT_TRACE | 77,670,551 | 6.7% | 48.5% |  |
| STORE_FAST | 69,682,252 | 6.0% | 54.6% |  |
| _ITER_CHECK_LIST | 51,749,628 | 4.5% | 59.0% | 3.4% |
| _IS_ITER_EXHAUSTED_LIST | 49,996,128 | 4.3% | 63.4% |  |
| _ITER_NEXT_LIST | 40,196,223 | 3.5% | 66.9% |  |
| _GUARD_GLOBALS_VERSION | 32,635,030 | 2.8% | 69.7% | 1.5% |
| _LOAD_GLOBAL_MODULE | 24,192,641 | 2.1% | 71.8% |  |
| _ITER_CHECK_TUPLE | 23,766,117 | 2.1% | 73.8% | 4.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 22,807,597 | 2.0% | 75.8% |  |
| POP_TOP | 19,506,824 | 1.7% | 77.5% |  |
| CONTAINS_OP | 14,181,217 | 1.2% | 78.7% |  |
| _ITER_NEXT_TUPLE | 13,939,333 | 1.2% | 79.9% |  |
| LOAD_CONST | 12,445,991 | 1.1% | 81.0% |  |
| PUSH_NULL | 11,222,396 | 1.0% | 82.0% |  |
| _ITER_CHECK_RANGE | 10,737,438 | 0.9% | 82.9% |  |
| _IS_ITER_EXHAUSTED_RANGE | 10,737,438 | 0.9% | 83.8% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 10,660,000 | 0.9% | 84.8% | 0.1% |
| _CHECK_PEP_523 | 10,660,000 | 0.9% | 85.7% |  |
| _CHECK_STACK_SPACE | 10,644,477 | 0.9% | 86.6% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 10,642,195 | 0.9% | 87.5% |  |
| _PUSH_FRAME | 10,642,195 | 0.9% | 88.5% |  |
| _SAVE_RETURN_OFFSET | 10,642,195 | 0.9% | 89.4% |  |
| _ITER_NEXT_RANGE | 9,909,823 | 0.9% | 90.2% |  |
| _GUARD_BOTH_INT | 9,203,283 | 0.8% | 91.0% |  |
| _BINARY_OP_ADD_INT | 9,195,843 | 0.8% | 91.8% |  |
| _GUARD_TYPE_VERSION | 9,138,830 | 0.8% | 92.6% | 32.5% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 8,977,723 | 0.8% | 93.4% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 8,977,723 | 0.8% | 94.2% |  |
| _GUARD_BUILTINS_VERSION | 7,942,237 | 0.7% | 94.9% |  |
| _LOAD_GLOBAL_BUILTINS | 7,942,237 | 0.7% | 95.6% |  |
| LOAD_DEREF | 6,182,290 | 0.5% | 96.1% |  |
| CALL_ISINSTANCE | 4,920,665 | 0.4% | 96.5% |  |
| _JUMP_TO_TOP | 4,854,513 | 0.4% | 96.9% |  |
| _POP_JUMP_IF_FALSE | 4,147,662 | 0.4% | 97.3% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,193,899 | 0.3% | 97.6% |  |
| TO_BOOL_BOOL | 2,902,269 | 0.3% | 97.8% |  |
| COMPARE_OP_INT | 2,399,035 | 0.2% | 98.0% |  |
| CALL_BUILTIN_O | 2,214,309 | 0.2% | 98.2% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 2,063,080 | 0.2% | 98.4% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,966,422 | 0.2% | 98.6% |  |
| MAKE_FUNCTION | 1,903,063 | 0.2% | 98.7% |  |
| CALL_TYPE_1 | 1,861,060 | 0.2% | 98.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 1,492,935 | 0.1% | 99.0% |  |
| _GUARD_KEYS_VERSION | 1,492,935 | 0.1% | 99.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 1,492,935 | 0.1% | 99.3% |  |
| RESUME_CHECK | 1,245,475 | 0.1% | 99.4% |  |
| BINARY_SUBSCR_LIST_INT | 1,184,700 | 0.1% | 99.5% | 1.6% |
| STORE_DEREF | 993,008 | 0.1% | 99.6% |  |
| TO_BOOL_INT | 632,940 | 0.1% | 99.6% | 0.0% |
| _LOAD_ATTR_SLOT | 530,582 | 0.0% | 99.7% |  |
| CALL_BUILTIN_CLASS | 520,876 | 0.0% | 99.7% |  |
| GET_ITER | 494,738 | 0.0% | 99.8% |  |
| LIST_APPEND | 445,625 | 0.0% | 99.8% |  |
| COPY | 281,600 | 0.0% | 99.8% |  |
| SWAP | 280,960 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST | 235,804 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 140,400 | 0.0% | 99.9% |  |
| _IS_NONE | 129,784 | 0.0% | 99.9% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 112,623 | 0.0% | 99.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 112,623 | 0.0% | 99.9% |  |
| LOAD_NAME | 106,000 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 98,828 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 87,938 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 80,277 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 69,420 | 0.0% | 100.0% | 0.8% |
| CALL_METHOD_DESCRIPTOR_O | 57,040 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 55,600 | 0.0% | 100.0% |  |
| BUILD_LIST | 45,840 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 45,411 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 39,280 | 0.0% | 100.0% |  |
| STORE_NAME | 35,420 | 0.0% | 100.0% |  |
| UNARY_NOT | 33,737 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 29,700 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 19,580 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 16,660 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,320 | 0.0% | 100.0% |  |
| BUILD_MAP | 11,557 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 10,640 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 10,640 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 8,080 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 6,880 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 6,000 | 0.0% | 100.0% |  |
| _POP_FRAME | 5,580 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 2,260 | 0.0% | 100.0% |  |
| DICT_MERGE | 2,020 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,920 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 1,920 | 0.0% | 100.0% |  |
| CALL_LEN | 1,800 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 1,500 | 0.0% | 100.0% |  |
| STORE_SLICE | 1,220 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,220 | 0.0% | 100.0% |  |
| BUILD_STRING | 960 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 560 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 480 | 0.0% | 100.0% | 100.0% |
| CALL_TUPLE_1 | 240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 240 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 160 | 0.0% | 100.0% |  |
| IS_OP | 20 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 3,966,051 |
| FOR_ITER_GEN | 5,843 |
| LOAD_ATTR_PROPERTY | 2,624 |
| LOAD_ATTR | 1,520 |
| YIELD_VALUE | 780 |
| CALL | 498 |
| CALL_LIST_APPEND | 400 |
| CALL_PY_WITH_DEFAULTS | 400 |
| CALL_KW | 320 |
| BINARY_SUBSCR | 260 |
| BINARY_OP | 260 |
| BINARY_SUBSCR_GETITEM | 240 |
| CALL_FUNCTION_EX | 100 |
| TO_BOOL | 60 |
| STORE_SUBSCR | 20 |
| IMPORT_NAME | 20 |


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
Stats gathered on: 2023-11-03
