
# Pystats results

- benchmark: sympy
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 912,466,565 | 16.4% | 16.4% |  |
| STORE_FAST | 297,468,385 | 5.4% | 21.8% |  |
| POP_JUMP_IF_FALSE | 276,121,664 | 5.0% | 26.8% |  |
| RESUME_CHECK | 256,828,528 | 4.6% | 31.4% |  |
| LOAD_FAST_LOAD_FAST | 234,353,499 | 4.2% | 35.6% |  |
| LOAD_GLOBAL_BUILTIN | 225,916,816 | 4.1% | 39.7% | 0.0% |
| LOAD_CONST | 179,011,655 | 3.2% | 42.9% |  |
| RETURN_VALUE | 177,413,153 | 3.2% | 46.1% |  |
| TO_BOOL_BOOL | 169,821,853 | 3.1% | 49.1% | 0.1% |
| INTERPRETER_EXIT | 127,427,546 | 2.3% | 51.4% |  |
| LOAD_ATTR | 121,748,941 | 2.2% | 53.6% |  |
| LOAD_GLOBAL_MODULE | 121,556,197 | 2.2% | 55.8% | 0.0% |
| FOR_ITER | 104,317,192 | 1.9% | 57.7% |  |
| STORE_FAST_STORE_FAST | 103,622,315 | 1.9% | 59.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 100,738,353 | 1.8% | 61.4% |  |
| LOAD_ATTR_SLOT | 95,488,439 | 1.7% | 63.1% | 38.2% |
| LOAD_ATTR_METHOD_NO_DICT | 89,635,145 | 1.6% | 64.7% | 10.2% |
| ENTER_EXECUTOR | 84,120,938 | 1.5% | 66.2% |  |
| POP_JUMP_IF_TRUE | 76,256,306 | 1.4% | 67.6% |  |
| JUMP_BACKWARD | 67,905,388 | 1.2% | 68.8% |  |
| CALL_PY_EXACT_ARGS | 66,472,677 | 1.2% | 70.0% | 11.8% |
| LOAD_DEREF | 62,628,468 | 1.1% | 71.1% |  |
| CALL_ISINSTANCE | 62,538,533 | 1.1% | 72.3% |  |
| POP_TOP | 61,754,957 | 1.1% | 73.4% |  |
| GET_ITER | 59,574,900 | 1.1% | 74.4% |  |
| RETURN_CONST | 57,294,831 | 1.0% | 75.5% |  |
| BUILD_TUPLE | 56,904,789 | 1.0% | 76.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,869,184 | 1.0% | 77.5% | 27.7% |
| PUSH_NULL | 49,495,070 | 0.9% | 78.4% |  |
| COMPARE_OP_INT | 48,778,785 | 0.9% | 79.3% | 1.2% |
| IS_OP | 47,821,049 | 0.9% | 80.1% |  |
| SWAP | 45,031,052 | 0.8% | 81.0% |  |
| CALL_BUILTIN_FAST | 43,261,512 | 0.8% | 81.7% |  |
| POP_JUMP_IF_NONE | 41,162,213 | 0.7% | 82.5% |  |
| COMPARE_OP | 38,585,754 | 0.7% | 83.2% |  |
| CONTAINS_OP | 38,029,644 | 0.7% | 83.9% |  |
| CALL_BUILTIN_O | 37,676,033 | 0.7% | 84.5% | 7.1% |
| BINARY_OP | 35,327,223 | 0.6% | 85.2% |  |
| BUILD_MAP | 33,785,286 | 0.6% | 85.8% |  |
| COPY_FREE_VARS | 31,774,244 | 0.6% | 86.4% |  |
| NOP | 31,472,137 | 0.6% | 86.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 29,572,083 | 0.5% | 87.5% | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,518,282 | 0.5% | 88.0% | 22.0% |
| BINARY_SUBSCR_LIST_INT | 29,028,504 | 0.5% | 88.5% | 0.0% |
| CALL_LEN | 28,096,431 | 0.5% | 89.0% |  |
| CALL_FUNCTION_EX | 28,012,880 | 0.5% | 89.5% |  |
| LOAD_ATTR_PROPERTY | 27,991,389 | 0.5% | 90.0% | 14.7% |
| CALL | 26,860,007 | 0.5% | 90.5% |  |
| BINARY_SUBSCR | 24,165,437 | 0.4% | 90.9% |  |
| CALL_LIST_APPEND | 24,015,827 | 0.4% | 91.4% |  |
| DICT_MERGE | 23,270,420 | 0.4% | 91.8% |  |
| YIELD_VALUE | 23,083,886 | 0.4% | 92.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 22,018,799 | 0.4% | 92.6% | 65.6% |
| BUILD_LIST | 21,579,716 | 0.4% | 93.0% |  |
| STORE_SUBSCR_LIST_INT | 20,199,915 | 0.4% | 93.4% |  |
| TO_BOOL_INT | 19,063,714 | 0.3% | 93.7% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,145,689 | 0.3% | 94.0% |  |
| LOAD_FAST_AND_CLEAR | 16,788,091 | 0.3% | 94.3% |  |
| EXTENDED_ARG | 15,345,206 | 0.3% | 94.6% |  |
| CALL_TYPE_1 | 14,851,635 | 0.3% | 94.9% |  |
| COMPARE_OP_STR | 14,565,299 | 0.3% | 95.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,551,741 | 0.3% | 95.4% | 0.4% |
| RETURN_GENERATOR | 14,351,521 | 0.3% | 95.6% |  |
| TO_BOOL | 12,925,055 | 0.2% | 95.9% |  |
| FOR_ITER_LIST | 12,894,982 | 0.2% | 96.1% | 1.2% |
| MAKE_FUNCTION | 12,403,858 | 0.2% | 96.3% |  |
| FOR_ITER_TUPLE | 11,664,472 | 0.2% | 96.5% | 3.6% |
| CALL_KW | 10,673,262 | 0.2% | 96.7% |  |
| SET_FUNCTION_ATTRIBUTE | 10,387,189 | 0.2% | 96.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,064,645 | 0.2% | 97.1% | 0.0% |
| STORE_ATTR_SLOT | 9,060,259 | 0.2% | 97.3% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,988,144 | 0.2% | 97.4% | 0.1% |
| IMPORT_FROM | 8,955,260 | 0.2% | 97.6% |  |
| CALL_BUILTIN_CLASS | 8,628,930 | 0.2% | 97.7% |  |
| MAP_ADD | 7,866,612 | 0.1% | 97.9% |  |
| IMPORT_NAME | 7,759,977 | 0.1% | 98.0% |  |
| STORE_DEREF | 7,702,404 | 0.1% | 98.2% |  |
| MAKE_CELL | 6,049,257 | 0.1% | 98.3% |  |
| CALL_TUPLE_1 | 5,851,421 | 0.1% | 98.4% | 0.0% |
| JUMP_FORWARD | 5,744,191 | 0.1% | 98.5% |  |
| LIST_APPEND | 5,742,582 | 0.1% | 98.6% |  |
| UNARY_NOT | 5,273,908 | 0.1% | 98.7% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,846 | 0.1% | 98.8% | 0.1% |
| COPY | 4,626,820 | 0.1% | 98.8% |  |
| CALL_PY_WITH_DEFAULTS | 4,591,228 | 0.1% | 98.9% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,590,643 | 0.1% | 99.0% | 0.2% |
| BINARY_OP_ADD_INT | 3,785,920 | 0.1% | 99.1% |  |
| STORE_SUBSCR | 3,428,559 | 0.1% | 99.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,784 | 0.1% | 99.2% | 0.0% |
| BINARY_SUBSCR_DICT | 3,261,211 | 0.1% | 99.3% |  |
| BINARY_OP_MULTIPLY_INT | 2,764,689 | 0.0% | 99.3% | 0.0% |
| TO_BOOL_NONE | 2,653,355 | 0.0% | 99.4% | 8.5% |
| BINARY_OP_SUBTRACT_INT | 2,486,499 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 2,286,040 | 0.0% | 99.4% | 0.5% |
| STORE_SUBSCR_DICT | 2,281,102 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,809,885 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,114 | 0.0% | 99.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,650,924 | 0.0% | 99.6% | 20.7% |
| UNPACK_SEQUENCE_TUPLE | 1,592,138 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,578,329 | 0.0% | 99.6% |  |
| FOR_ITER_RANGE | 1,397,667 | 0.0% | 99.7% |  |
| LIST_EXTEND | 1,349,097 | 0.0% | 99.7% |  |
| CALL_INTRINSIC_1 | 1,349,057 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,735 | 0.0% | 99.8% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,181,936 | 0.0% | 99.8% |  |
| SEND_GEN | 1,029,804 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,626 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,626 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,626 | 0.0% | 99.9% |  |
| STORE_ATTR | 591,338 | 0.0% | 99.9% |  |
| BINARY_SLICE | 569,019 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 552,940 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,658 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,384 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 533,090 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 503,100 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 228,675 | 0.0% | 100.0% | 36.3% |
| FOR_ITER_GEN | 191,380 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,803 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,575 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,252 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 132,560 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,378 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,070 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 72,820 | 0.0% | 100.0% |  |
| BUILD_SET | 50,347 | 0.0% | 100.0% |  |
| RESUME | 47,568 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,722 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,531 | 0.0% | 100.0% |  |
| SET_ADD | 19,280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,260 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,760 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,006 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,203 | 0.0% | 100.0% |  |
| STORE_SLICE | 940 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 480 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 300 | 0.0% | 100.0% | 20.0% |
| DELETE_NAME | 120 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 60 | 0.0% | 100.0% |  |
| DICT_UPDATE | 20 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 161,628,678 | 2.9% | 2.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 156,095,275 | 2.8% | 5.7% |
| RESUME_CHECK LOAD_FAST | 115,556,636 | 2.1% | 7.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 110,019,375 | 2.0% | 9.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 109,487,176 | 2.0% | 11.8% |
| CACHE RESUME_CHECK | 99,193,772 | 1.8% | 13.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 96,935,838 | 1.7% | 15.3% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,136,651 | 1.7% | 17.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 76,902,576 | 1.4% | 18.4% |
| RETURN_VALUE INTERPRETER_EXIT | 72,898,372 | 1.3% | 19.7% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 71,568,473 | 1.3% | 21.0% |
| JUMP_BACKWARD FOR_ITER | 67,605,869 | 1.2% | 22.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 61,809,835 | 1.1% | 23.3% |
| LOAD_FAST LOAD_CONST | 60,614,018 | 1.1% | 24.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 59,534,602 | 1.1% | 25.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,704,346 | 1.0% | 26.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 54,182,488 | 1.0% | 27.5% |
| LOAD_FAST RETURN_VALUE | 52,780,825 | 1.0% | 28.4% |
| LOAD_FAST LOAD_ATTR | 51,087,658 | 0.9% | 29.3% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 50,511,514 | 0.9% | 30.2% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 49,587,128 | 0.9% | 31.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 49,548,874 | 0.9% | 32.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,382,805 | 0.8% | 32.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,265,167 | 0.7% | 33.5% |
| STORE_FAST_STORE_FAST LOAD_FAST | 40,965,913 | 0.7% | 34.3% |
| LOAD_CONST LOAD_CONST | 40,213,787 | 0.7% | 35.0% |
| RETURN_VALUE STORE_FAST | 38,556,053 | 0.7% | 35.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 37,803,602 | 0.7% | 36.4% |
| LOAD_ATTR STORE_FAST | 36,819,691 | 0.7% | 37.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 35,787,193 | 0.6% | 37.7% |
| PUSH_NULL LOAD_FAST | 35,369,422 | 0.6% | 38.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 34,799,596 | 0.6% | 38.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,554,593 | 0.6% | 39.5% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,432,382 | 0.6% | 40.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,201,847 | 0.6% | 40.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 33,035,323 | 0.6% | 41.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 32,309,106 | 0.6% | 41.9% |
| RETURN_CONST INTERPRETER_EXIT | 32,283,541 | 0.6% | 42.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 30,794,650 | 0.6% | 43.1% |
| IS_OP POP_JUMP_IF_FALSE | 30,049,591 | 0.5% | 43.6% |
| ENTER_EXECUTOR LOAD_ATTR | 29,616,166 | 0.5% | 44.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 29,410,909 | 0.5% | 44.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 29,355,093 | 0.5% | 45.2% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 28,835,404 | 0.5% | 45.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,705,700 | 0.5% | 46.2% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 27,645,877 | 0.5% | 46.7% |
| LOAD_FAST CALL_LEN | 27,055,170 | 0.5% | 47.2% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 26,385,818 | 0.5% | 47.7% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 25,624,493 | 0.5% | 48.1% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,300,017 | 0.5% | 48.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 24,512,219 | 0.4% | 49.0% |
| BINARY_OP STORE_FAST | 24,217,217 | 0.4% | 49.5% |
| LOAD_CONST CALL_BUILTIN_FAST | 24,055,733 | 0.4% | 49.9% |
| DICT_MERGE CALL_FUNCTION_EX | 23,270,420 | 0.4% | 50.3% |
| BUILD_MAP LOAD_FAST | 23,181,222 | 0.4% | 50.7% |
| LOAD_FAST DICT_MERGE | 23,141,508 | 0.4% | 51.2% |
| LOAD_ATTR_SLOT STORE_FAST | 22,508,154 | 0.4% | 51.6% |
| YIELD_VALUE INTERPRETER_EXIT | 22,237,893 | 0.4% | 52.0% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_BUILTIN | 22,035,073 | 0.4% | 52.4% |
| COPY_FREE_VARS RESUME_CHECK | 21,785,983 | 0.4% | 52.8% |
| LOAD_FAST TO_BOOL_BOOL | 21,602,243 | 0.4% | 53.1% |
| RESUME_CHECK NOP | 21,363,941 | 0.4% | 53.5% |
| LOAD_FAST GET_ITER | 21,292,222 | 0.4% | 53.9% |
| BUILD_TUPLE RETURN_VALUE | 21,222,059 | 0.4% | 54.3% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 21,115,081 | 0.4% | 54.7% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,088,599 | 0.4% | 55.1% |
| STORE_FAST_STORE_FAST LOAD_DEREF | 20,944,618 | 0.4% | 55.4% |
| POP_JUMP_IF_NONE JUMP_BACKWARD | 20,901,967 | 0.4% | 55.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,801,469 | 0.4% | 56.2% |
| LOAD_CONST COMPARE_OP_INT | 20,758,436 | 0.4% | 56.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 20,354,524 | 0.4% | 56.9% |
| COMPARE_OP POP_JUMP_IF_FALSE | 20,147,212 | 0.4% | 57.3% |
| LOAD_ATTR CONTAINS_OP | 20,047,556 | 0.4% | 57.6% |
| GET_ITER FOR_ITER | 20,014,489 | 0.4% | 58.0% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,466,541 | 0.4% | 58.4% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 18,938,684 | 0.3% | 58.7% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,849,019 | 0.3% | 59.0% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,812,747 | 0.3% | 59.4% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 18,753,502 | 0.3% | 59.7% |
| LOAD_FAST TO_BOOL_INT | 18,176,127 | 0.3% | 60.0% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 18,002,317 | 0.3% | 60.4% |
| LOAD_FAST PUSH_NULL | 17,306,319 | 0.3% | 60.7% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,264,948 | 0.3% | 61.0% |
| LOAD_ATTR IS_OP | 17,248,867 | 0.3% | 61.3% |
| LOAD_FAST BUILD_TUPLE | 17,148,876 | 0.3% | 61.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,706,146 | 0.3% | 61.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,194,051 | 0.3% | 62.2% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 16,113,827 | 0.3% | 62.5% |
| LOAD_ATTR LOAD_FAST | 16,074,356 | 0.3% | 62.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,028,492 | 0.3% | 63.1% |
| RESUME_CHECK LOAD_CONST | 15,734,662 | 0.3% | 63.4% |
| LOAD_FAST CALL_BUILTIN_O | 15,707,211 | 0.3% | 63.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,662,247 | 0.3% | 63.9% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 15,653,161 | 0.3% | 64.2% |
| LOAD_FAST CALL_LIST_APPEND | 15,555,100 | 0.3% | 64.5% |
| RETURN_VALUE RETURN_VALUE | 15,184,637 | 0.3% | 64.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 15,162,082 | 0.3% | 65.0% |
| RESUME_CHECK POP_TOP | 15,102,624 | 0.3% | 65.3% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 15,102,367 | 0.3% | 65.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 15,091,585 | 0.3% | 65.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 535,659 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,599 | 56.2% |
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
| RESUME_CHECK | 99,193,772 | 77.7% |
| POP_TOP | 13,902,561 | 10.9% |
| COPY_FREE_VARS | 12,999,878 | 10.2% |
| MAKE_CELL | 1,509,121 | 1.2% |
| RESUME | 18,058 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 13,554,631 | 56.1% |
| LOAD_DEREF | 6,404,317 | 26.5% |
| BUILD_TUPLE | 1,838,108 | 7.6% |
| ENTER_EXECUTOR | 1,248,367 | 5.2% |
| LOAD_FAST | 734,353 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 7,017,090 | 29.0% |
| LOAD_FAST | 6,912,775 | 28.6% |
| RETURN_VALUE | 6,066,154 | 25.1% |
| CALL | 919,800 | 3.8% |
| GET_ITER | 919,094 | 3.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,796 | 73.7% |
| BUILD_TUPLE | 157,200 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,290 | 8.7% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,466 | 100.0% |
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
| RETURN_CONST | 22,531 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,531 | 100.0% |


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
| LOAD_FAST | 21,292,222 | 35.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,456,823 | 24.3% |
| CALL | 10,953,422 | 18.4% |
| RETURN_VALUE | 4,116,526 | 6.9% |
| CALL_BUILTIN_O | 2,591,124 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 20,014,489 | 33.6% |
| CALL_PY_EXACT_ARGS | 13,022,313 | 21.9% |
| FOR_ITER_TUPLE | 9,883,522 | 16.6% |
| LOAD_FAST_AND_CLEAR | 9,198,146 | 15.4% |
| FOR_ITER_LIST | 4,311,572 | 7.2% |


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
| RETURN_VALUE | 72,898,372 | 57.2% |
| RETURN_CONST | 32,283,541 | 25.3% |
| YIELD_VALUE | 22,237,893 | 17.5% |
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
| LOAD_CONST | 12,403,858 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 10,385,649 | 83.7% |
| LOAD_GLOBAL_BUILTIN | 794,152 | 6.4% |
| STORE_FAST | 669,671 | 5.4% |
| LOAD_FAST | 458,604 | 3.7% |
| STORE_NAME | 33,580 | 0.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,363,941 | 67.9% |
| POP_JUMP_IF_TRUE | 4,183,908 | 13.3% |
| STORE_FAST | 1,973,323 | 6.3% |
| POP_JUMP_IF_FALSE | 1,913,093 | 6.1% |
| POP_TOP | 1,392,175 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,280,455 | 39.0% |
| LOAD_DEREF | 10,424,164 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,377,719 | 20.3% |
| LOAD_FAST_LOAD_FAST | 899,679 | 2.9% |
| LOAD_CONST | 751,152 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,923 | 45.8% |
| POP_TOP | 358,283 | 39.5% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,923 | 45.8% |
| EXTENDED_ARG | 201,210 | 22.2% |
| ENTER_EXECUTOR | 155,353 | 17.1% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,102,624 | 24.5% |
| CACHE | 13,902,561 | 22.5% |
| RETURN_CONST | 9,433,960 | 15.3% |
| STORE_FAST | 5,839,869 | 9.5% |
| SWAP | 5,778,542 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 14,832,079 | 24.0% |
| RESUME_CHECK | 14,345,959 | 23.2% |
| ENTER_EXECUTOR | 9,299,234 | 15.1% |
| LOAD_FAST | 7,247,672 | 11.7% |
| RETURN_VALUE | 5,302,342 | 8.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,851 | 41.3% |
| BINARY_SUBSCR_DICT | 169,955 | 18.7% |
| RAISE_VARARGS | 115,250 | 12.7% |
| ENTER_EXECUTOR | 95,940 | 10.6% |
| LOAD_ATTR | 95,500 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,416 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,770 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,306,319 | 35.0% |
| LOAD_ATTR | 14,956,608 | 30.2% |
| LOAD_DEREF | 11,886,648 | 24.0% |
| CALL_BUILTIN_FAST | 2,129,900 | 4.3% |
| LOAD_SUPER_ATTR_ATTR | 1,181,936 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,369,422 | 71.5% |
| LOAD_FAST_LOAD_FAST | 12,185,534 | 24.6% |
| LOAD_CONST | 1,723,720 | 3.5% |
| LOAD_DEREF | 128,566 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,907,575 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,117,124 | 28.7% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,080 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,212,114 | 71.2% |
| STORE_FAST | 2,660,363 | 18.5% |
| LOAD_FAST | 791,982 | 5.5% |
| GET_YIELD_FROM_ITER | 346,984 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,780,825 | 29.8% |
| LOAD_ATTR_SLOT | 33,432,382 | 18.8% |
| BUILD_TUPLE | 21,222,059 | 12.0% |
| RETURN_VALUE | 15,184,637 | 8.6% |
| CALL_BUILTIN_O | 11,432,733 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,898,372 | 41.1% |
| STORE_FAST | 38,556,053 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,466,541 | 11.0% |
| RETURN_VALUE | 15,184,637 | 8.6% |
| LOAD_FAST | 5,453,850 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,198,764 | 93.3% |
| ENTER_EXECUTOR | 104,629 | 3.1% |
| BINARY_SUBSCR | 93,200 | 2.7% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.6% |
| SWAP | 5,960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,290,313 | 96.0% |
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
| LOAD_FAST | 2,207,751 | 17.1% |
| LOAD_GLOBAL_MODULE | 119,058 | 0.9% |
| LOAD_ATTR | 117,980 | 0.9% |
| RETURN_VALUE | 27,305 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,253,088 | 94.8% |
| POP_JUMP_IF_TRUE | 509,864 | 3.9% |
| UNARY_NOT | 84,227 | 0.7% |
| TO_BOOL_BOOL | 41,186 | 0.3% |
| TO_BOOL | 21,472 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,482 | 22.0% |
| LOAD_FAST | 109,406 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,692 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,992 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,840 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,103 | 10.9% |
| CALL_LIST_APPEND | 39,980 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,659 | 65.3% |
| TO_BOOL_BOOL | 1,084,984 | 20.6% |
| TO_BOOL_LIST | 661,875 | 12.5% |
| TO_BOOL | 84,227 | 1.6% |
| TO_BOOL_INT | 163 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,438 | 66.9% |
| STORE_FAST | 882,751 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,990 | 1.6% |
| LOAD_CONST | 34,349 | 0.7% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,820,369 | 55.5% |
| ENTER_EXECUTOR | 4,716,354 | 20.4% |
| CALL_ISINSTANCE | 2,335,067 | 10.1% |
| LOAD_FAST | 1,146,786 | 5.0% |
| YIELD_VALUE | 677,464 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,237,893 | 96.3% |
| YIELD_VALUE | 677,464 | 2.9% |
| STORE_FAST | 162,889 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,760,270 | 33.3% |
| COMPARE_OP_INT | 6,304,740 | 17.8% |
| COMPARE_OP | 6,162,400 | 17.4% |
| CALL_TUPLE_1 | 4,707,284 | 13.3% |
| LOAD_FAST | 2,606,976 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,217,217 | 68.6% |
| RETURN_VALUE | 5,771,287 | 16.3% |
| BUILD_TUPLE | 1,556,880 | 4.4% |
| CALL_BUILTIN_O | 1,095,116 | 3.1% |
| LOAD_FAST | 857,877 | 2.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,378 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,598 | 97.9% |
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
| SWAP | 4,464,042 | 20.7% |
| POP_JUMP_IF_TRUE | 4,083,163 | 18.9% |
| STORE_FAST | 3,816,446 | 17.7% |
| LOAD_FAST | 2,311,980 | 10.7% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,712,543 | 54.3% |
| SWAP | 4,464,042 | 20.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,395 | 10.6% |
| LOAD_FAST | 1,374,397 | 6.4% |
| BUILD_LIST | 748,356 | 3.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,167,753 | 36.0% |
| BUILD_TUPLE | 10,996,530 | 32.5% |
| SWAP | 4,716,104 | 14.0% |
| LOAD_CONST | 1,656,800 | 4.9% |
| RESUME_CHECK | 1,285,960 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,181,222 | 68.6% |
| SWAP | 4,716,104 | 14.0% |
| STORE_FAST | 3,331,419 | 9.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 4.6% |
| CALL_FUNCTION_EX | 734,880 | 2.2% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,267 | 64.1% |
| SWAP | 18,000 | 35.8% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,267 | 64.1% |
| SWAP | 18,000 | 35.8% |
| STORE_FAST | 80 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,006 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 3,840 | 95.9% |
| BINARY_SUBSCR | 166 | 4.1% |


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
| LOAD_FAST_LOAD_FAST | 25,624,493 | 45.0% |
| LOAD_FAST | 17,148,876 | 30.1% |
| LOAD_ATTR_SLOT | 5,042,226 | 8.9% |
| LOAD_ATTR | 3,034,708 | 5.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,222,059 | 37.3% |
| BUILD_MAP | 10,996,530 | 19.3% |
| LOAD_CONST | 10,408,601 | 18.3% |
| LOAD_GLOBAL_BUILTIN | 4,707,084 | 8.3% |
| CALL_LIST_APPEND | 3,216,080 | 5.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,634,028 | 35.9% |
| LOAD_FAST | 7,278,346 | 27.1% |
| LOAD_ATTR | 3,067,167 | 11.4% |
| BINARY_OP_MULTIPLY_INT | 2,291,863 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,934 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,422 | 40.8% |
| STORE_FAST | 5,844,851 | 21.8% |
| RETURN_VALUE | 4,524,955 | 16.8% |
| POP_TOP | 1,142,682 | 4.3% |
| RESUME_CHECK | 1,068,512 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 23,270,420 | 83.1% |
| LOAD_FAST | 2,317,489 | 8.3% |
| CALL_INTRINSIC_1 | 1,256,735 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |
| BINARY_OP | 201,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,600,914 | 45.0% |
| RESUME_CHECK | 11,673,454 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,839 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,347,837 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,735 | 93.2% |
| BUILD_MAP | 91,262 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,509,113 | 98.5% |
| ENTER_EXECUTOR | 164,149 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,298 | 88.9% |
| POP_TOP | 698,042 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,803 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,088,599 | 54.7% |
| LOAD_FAST | 8,308,658 | 21.5% |
| CALL_TYPE_1 | 5,882,465 | 15.2% |
| LOAD_GLOBAL_MODULE | 1,180,671 | 3.1% |
| LOAD_CONST | 950,788 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20,147,212 | 52.2% |
| BINARY_OP | 6,162,400 | 16.0% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.0% |
| UNARY_NOT | 3,442,659 | 8.9% |
| POP_JUMP_IF_TRUE | 2,278,920 | 5.9% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 20,047,556 | 52.7% |
| LOAD_FAST_LOAD_FAST | 10,680,920 | 28.1% |
| LOAD_GLOBAL_MODULE | 5,290,376 | 13.9% |
| LOAD_DEREF | 1,480,880 | 3.9% |
| LOAD_CONST | 174,965 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,799,596 | 91.5% |
| POP_JUMP_IF_TRUE | 3,219,888 | 8.5% |
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
| LOAD_FAST | 1,237,528 | 26.7% |
| COPY | 1,074,000 | 23.2% |
| LOAD_FAST_LOAD_FAST | 872,880 | 18.9% |
| CALL_ISINSTANCE | 525,020 | 11.3% |
| LOAD_CONST | 236,767 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,339,285 | 28.9% |
| COPY | 1,074,000 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,067,720 | 23.1% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,567 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 12,999,878 | 40.9% |
| CALL_PY_EXACT_ARGS | 11,836,345 | 37.3% |
| LOAD_ATTR_PROPERTY | 5,065,519 | 15.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,196,598 | 3.8% |
| CALL_KW | 261,140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,785,983 | 68.6% |
| RETURN_GENERATOR | 9,907,575 | 31.2% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,186 | 0.0% |


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

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,141,508 | 99.4% |
| LOAD_DEREF | 128,912 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 23,270,420 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 27,645,877 | 32.9% |
| CALL_LIST_APPEND | 15,102,367 | 18.0% |
| STORE_SUBSCR_LIST_INT | 9,864,325 | 11.7% |
| POP_TOP | 9,299,234 | 11.1% |
| EXTENDED_ARG | 5,757,848 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 29,616,166 | 35.2% |
| LOAD_FAST | 10,160,320 | 12.1% |
| RESUME_CHECK | 9,215,723 | 11.0% |
| RETURN_CONST | 6,600,382 | 7.8% |
| ENTER_EXECUTOR | 5,417,439 | 6.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,065,925 | 33.0% |
| CALL_LIST_APPEND | 4,571,161 | 29.8% |
| GET_ITER | 2,378,125 | 15.5% |
| COMPARE_OP_INT | 1,719,889 | 11.2% |
| POP_JUMP_IF_FALSE | 810,342 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,612,649 | 43.1% |
| ENTER_EXECUTOR | 5,757,848 | 37.5% |
| FOR_ITER_LIST | 1,354,519 | 8.8% |
| FOR_ITER_RANGE | 642,400 | 4.2% |
| FOR_ITER_TUPLE | 395,000 | 2.6% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 67,605,869 | 64.8% |
| GET_ITER | 20,014,489 | 19.2% |
| SWAP | 7,638,536 | 7.3% |
| LOAD_FAST | 7,637,746 | 7.3% |
| ENTER_EXECUTOR | 1,320,387 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 71,568,473 | 68.6% |
| STORE_FAST | 8,363,966 | 8.0% |
| SWAP | 7,602,844 | 7.3% |
| LOAD_FAST | 4,701,318 | 4.5% |
| RETURN_CONST | 4,698,184 | 4.5% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,758,457 | 86.6% |
| STORE_FAST | 982,574 | 11.0% |
| STORE_DEREF | 185,689 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,822,227 | 76.2% |
| STORE_DEREF | 2,092,433 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,759,857 | 100.0% |
| ENTER_EXECUTOR | 100 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,758,457 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 17,248,867 | 36.1% |
| LOAD_FAST | 12,835,707 | 26.8% |
| LOAD_CONST | 10,976,443 | 23.0% |
| LOAD_FAST_LOAD_FAST | 5,893,579 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 539,779 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,049,591 | 62.8% |
| YIELD_VALUE | 12,820,369 | 26.8% |
| POP_JUMP_IF_TRUE | 4,906,906 | 10.3% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 20,901,967 | 30.8% |
| POP_JUMP_IF_TRUE | 16,113,827 | 23.7% |
| POP_TOP | 14,832,079 | 21.8% |
| MAP_ADD | 7,866,272 | 11.6% |
| CALL_LIST_APPEND | 2,240,687 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 67,605,869 | 99.6% |
| FOR_ITER_GEN | 100,584 | 0.1% |
| FOR_ITER_TUPLE | 80,743 | 0.1% |
| FOR_ITER_LIST | 53,837 | 0.1% |
| EXTENDED_ARG | 27,526 | 0.0% |


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
| STORE_FAST | 4,138,381 | 72.0% |
| POP_TOP | 734,252 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,876 | 3.3% |
| LOAD_FAST | 137,498 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,997,244 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,254 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,629 | 5.7% |
| STORE_FAST | 119,098 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,963,410 | 51.6% |
| BUILD_TUPLE | 1,568,821 | 27.3% |
| RETURN_VALUE | 510,671 | 8.9% |
| BINARY_SUBSCR | 489,426 | 8.5% |
| LOAD_ATTR_PROPERTY | 64,481 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,018,804 | 70.0% |
| JUMP_BACKWARD | 1,718,818 | 29.9% |
| LOAD_NAME | 4,800 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,346,957 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,347,837 | 99.9% |
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
| LOAD_FAST | 51,087,658 | 42.0% |
| LOAD_GLOBAL_MODULE | 33,554,593 | 27.6% |
| ENTER_EXECUTOR | 29,616,166 | 24.3% |
| CALL_TYPE_1 | 2,352,277 | 1.9% |
| LOAD_ATTR_SLOT | 2,297,055 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,819,691 | 30.2% |
| CONTAINS_OP | 20,047,556 | 16.5% |
| IS_OP | 17,248,867 | 14.2% |
| LOAD_FAST | 16,074,356 | 13.2% |
| PUSH_NULL | 14,956,608 | 12.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,614,018 | 33.9% |
| LOAD_CONST | 40,213,787 | 22.5% |
| RESUME_CHECK | 15,734,662 | 8.8% |
| BUILD_TUPLE | 10,408,601 | 5.8% |
| RETURN_CONST | 9,526,680 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,213,787 | 22.5% |
| CALL_BUILTIN_FAST | 24,055,733 | 13.4% |
| COMPARE_OP_INT | 20,758,436 | 11.6% |
| STORE_FAST | 14,275,386 | 8.0% |
| MAKE_FUNCTION | 12,403,858 | 6.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20,944,618 | 33.4% |
| NOP | 10,424,164 | 16.6% |
| LOAD_ATTR_SLOT | 6,404,317 | 10.2% |
| POP_JUMP_IF_FALSE | 4,644,681 | 7.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,038 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 21,115,081 | 33.7% |
| PUSH_NULL | 11,886,648 | 19.0% |
| LOAD_FAST | 9,396,180 | 15.0% |
| BINARY_SUBSCR | 6,404,317 | 10.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 5.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 161,628,678 | 17.7% |
| LOAD_GLOBAL_BUILTIN | 156,095,275 | 17.1% |
| RESUME_CHECK | 115,556,636 | 12.7% |
| POP_JUMP_IF_FALSE | 110,019,375 | 12.1% |
| STORE_FAST_STORE_FAST | 40,965,913 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,136,651 | 10.3% |
| LOAD_ATTR_METHOD_NO_DICT | 76,902,576 | 8.4% |
| LOAD_GLOBAL_MODULE | 61,809,835 | 6.8% |
| LOAD_CONST | 60,614,018 | 6.6% |
| RETURN_VALUE | 52,780,825 | 5.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,198,146 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,865 | 45.2% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,198,066 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,865 | 45.2% |
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
| STORE_FAST | 50,511,514 | 21.6% |
| POP_JUMP_IF_FALSE | 28,835,404 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 28,705,700 | 12.2% |
| RESUME_CHECK | 18,753,502 | 8.0% |
| STORE_FAST_STORE_FAST | 15,653,161 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 26,385,818 | 11.3% |
| BUILD_TUPLE | 25,624,493 | 10.9% |
| COMPARE_OP | 21,088,599 | 9.0% |
| STORE_SUBSCR_LIST_INT | 18,849,019 | 8.0% |
| CALL_BUILTIN_FAST | 17,264,948 | 7.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,256 | 19.4% |
| LOAD_FAST | 34,208 | 18.8% |
| STORE_FAST | 26,925 | 14.8% |
| RESUME_CHECK | 10,925 | 6.0% |
| RESUME | 10,780 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,515 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,247 | 22.7% |
| LOAD_FAST | 39,597 | 21.8% |
| LOAD_ATTR | 14,077 | 7.7% |
| CALL | 9,828 | 5.4% |


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
| LOAD_FAST | 1,083 | 90.0% |
| LOAD_DEREF | 120 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 500 | 41.6% |
| CALL | 323 | 26.8% |
| LOAD_FAST | 180 | 15.0% |
| PUSH_NULL | 100 | 8.3% |
| LOAD_SUPER_ATTR_ATTR | 100 | 8.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,274,689 | 37.6% |
| CACHE | 1,509,121 | 24.9% |
| CALL_PY_EXACT_ARGS | 770,471 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,398 | 10.8% |
| CALL | 523,692 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,771,008 | 62.3% |
| MAKE_CELL | 2,274,689 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,853,452 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,866,272 | 100.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 109,487,176 | 39.7% |
| CONTAINS_OP | 34,799,596 | 12.6% |
| COMPARE_OP_INT | 33,201,847 | 12.0% |
| IS_OP | 30,049,591 | 10.9% |
| COMPARE_OP | 20,147,212 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 110,019,375 | 39.8% |
| LOAD_GLOBAL_BUILTIN | 57,704,346 | 20.9% |
| RETURN_CONST | 29,355,093 | 10.6% |
| LOAD_FAST_LOAD_FAST | 28,835,404 | 10.4% |
| ENTER_EXECUTOR | 27,645,877 | 10.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,035,323 | 80.3% |
| BINARY_SUBSCR | 7,017,090 | 17.0% |
| LOAD_DEREF | 1,088,851 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |
| EXTENDED_ARG | 5,429 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,901,967 | 50.8% |
| LOAD_FAST_LOAD_FAST | 14,877,600 | 36.1% |
| LOAD_FAST | 2,501,282 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 1,438,295 | 3.5% |
| LOAD_CONST | 1,111,423 | 2.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,706,146 | 92.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,225,003 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,226,621 | 67.4% |
| LOAD_FAST_LOAD_FAST | 2,033,950 | 11.2% |
| LOAD_GLOBAL_MODULE | 1,878,667 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,220 | 7.6% |
| ENTER_EXECUTOR | 441,546 | 2.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 54,182,488 | 71.1% |
| TO_BOOL_INT | 8,698,628 | 11.4% |
| IS_OP | 4,906,906 | 6.4% |
| CONTAINS_OP | 3,219,888 | 4.2% |
| COMPARE_OP | 2,278,920 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,803,602 | 49.6% |
| JUMP_BACKWARD | 16,113,827 | 21.1% |
| LOAD_GLOBAL_BUILTIN | 5,256,267 | 6.9% |
| NOP | 4,183,908 | 5.5% |
| BUILD_LIST | 4,083,163 | 5.4% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,910 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,250 | 98.4% |
| COPY | 1,760 | 1.5% |
| LOAD_CONST | 160 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,355,093 | 51.2% |
| RESUME_CHECK | 10,045,382 | 17.5% |
| ENTER_EXECUTOR | 6,600,382 | 11.5% |
| FOR_ITER | 4,698,184 | 8.2% |
| STORE_SUBSCR | 3,290,313 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,283,541 | 56.3% |
| LOAD_CONST | 9,526,680 | 16.6% |
| POP_TOP | 9,433,960 | 16.5% |
| TO_BOOL_BOOL | 3,462,356 | 6.0% |
| STORE_FAST | 1,541,201 | 2.7% |


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
| MAKE_FUNCTION | 10,385,649 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,834,511 | 94.7% |
| STORE_FAST | 298,256 | 2.9% |
| STORE_DEREF | 95,651 | 0.9% |
| LOAD_CONST | 52,360 | 0.5% |
| LOAD_GLOBAL_MODULE | 42,944 | 0.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,817 | 82.3% |
| LOAD_FAST | 98,460 | 16.7% |
| STORE_ATTR | 3,906 | 0.7% |
| SWAP | 2,143 | 0.4% |
| LOAD_DEREF | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,647 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,250 | 19.7% |
| LOAD_FAST | 89,969 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,577,880 | 46.5% |
| IMPORT_FROM | 2,092,433 | 27.2% |
| LOAD_ATTR | 1,558,839 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,651 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,840 | 46.5% |
| POP_TOP | 1,906,744 | 24.8% |
| LOAD_DEREF | 1,298,328 | 16.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.3% |
| IMPORT_FROM | 185,689 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,556,053 | 13.0% |
| LOAD_ATTR | 36,819,691 | 12.4% |
| BINARY_OP | 24,217,217 | 8.1% |
| LOAD_ATTR_SLOT | 22,508,154 | 7.6% |
| LOAD_CONST | 14,275,386 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 161,628,678 | 54.3% |
| LOAD_FAST_LOAD_FAST | 50,511,514 | 17.0% |
| LOAD_GLOBAL_BUILTIN | 32,309,106 | 10.9% |
| LOAD_GLOBAL_MODULE | 11,363,358 | 3.8% |
| STORE_FAST | 9,345,034 | 3.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,347 | 69.6% |
| FOR_ITER_TUPLE | 409,136 | 22.6% |
| FOR_ITER | 92,962 | 5.1% |
| FOR_ITER_RANGE | 47,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,221,311 | 67.5% |
| LOAD_ATTR_PROPERTY | 201,954 | 11.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 187,187 | 10.3% |
| LOAD_DEREF | 51,440 | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,840 | 2.5% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 96,935,838 | 93.5% |
| RETURN_VALUE | 3,248,181 | 3.1% |
| UNPACK_SEQUENCE_TUPLE | 1,397,397 | 1.3% |
| STORE_FAST_STORE_FAST | 771,936 | 0.7% |
| BUILD_LIST | 413,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,965,913 | 39.5% |
| LOAD_GLOBAL_BUILTIN | 22,035,073 | 21.3% |
| LOAD_DEREF | 20,944,618 | 20.2% |
| LOAD_FAST_LOAD_FAST | 15,653,161 | 15.1% |
| LOAD_GLOBAL_MODULE | 1,958,160 | 1.9% |


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
| BINARY_SUBSCR_LIST_INT | 9,396,045 | 20.9% |
| LOAD_FAST_AND_CLEAR | 9,198,066 | 20.4% |
| FOR_ITER | 7,602,844 | 16.9% |
| BUILD_MAP | 4,716,104 | 10.5% |
| LOAD_FAST | 4,641,362 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,396,265 | 20.9% |
| STORE_FAST | 7,930,927 | 17.6% |
| FOR_ITER | 7,638,536 | 17.0% |
| POP_TOP | 5,778,542 | 12.8% |
| BUILD_MAP | 4,716,104 | 10.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,450 | 26.3% |
| FOR_ITER | 6,803 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 16.0% |
| LOAD_FAST | 3,962 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,673 | 47.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,426 | 23.7% |
| STORE_FAST | 8,091 | 20.4% |
| UNPACK_SEQUENCE_TUPLE | 1,138 | 2.9% |
| UNPACK_SEQUENCE | 914 | 2.3% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,058 | 38.0% |
| CALL | 11,118 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,099 | 12.8% |
| POP_TOP | 3,962 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,699 | 37.2% |
| LOAD_GLOBAL | 10,780 | 22.7% |
| LOAD_CONST | 8,762 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,362 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,634,677 | 69.6% |
| LOAD_FAST_LOAD_FAST | 574,239 | 15.2% |
| BINARY_SUBSCR_DICT | 422,960 | 11.2% |
| CALL_BUILTIN_CLASS | 81,218 | 2.1% |
| LOAD_FAST | 43,680 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,576,699 | 41.6% |
| SWAP | 944,643 | 25.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 540,088 | 14.3% |
| LOAD_CONST | 269,142 | 7.1% |
| LOAD_FAST | 201,614 | 5.3% |


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
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,676 | 60.4% |
| LOAD_ATTR_SLOT | 723,528 | 26.2% |
| LOAD_FAST_LOAD_FAST | 276,650 | 10.0% |
| LOAD_FAST | 94,285 | 3.4% |
| BINARY_OP | 1,443 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,863 | 82.9% |
| LOAD_FAST_LOAD_FAST | 181,166 | 6.6% |
| STORE_FAST | 175,622 | 6.4% |
| LOAD_FAST | 83,306 | 3.0% |
| LOAD_GLOBAL_MODULE | 25,193 | 0.9% |


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
| LOAD_CONST | 1,569,148 | 63.1% |
| LOAD_FAST_LOAD_FAST | 607,402 | 24.4% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,672 | 4.9% |
| BINARY_OP | 2,181 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,082,420 | 43.5% |
| STORE_FAST | 710,727 | 28.6% |
| BINARY_OP | 311,670 | 12.5% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,880 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,129,665 | 34.6% |
| LOAD_FAST_LOAD_FAST | 923,542 | 28.3% |
| LOAD_CONST | 642,800 | 19.7% |
| CALL_TUPLE_1 | 443,840 | 13.6% |
| RETURN_VALUE | 114,450 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 866,517 | 26.6% |
| RETURN_VALUE | 809,336 | 24.8% |
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
| LOAD_CONST | 14,552 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,240 | 100.0% |
| RETURN_VALUE | 6 | 0.0% |
| LOAD_CONST | 6 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,385,818 | 90.9% |
| COPY | 1,067,720 | 3.7% |
| LOAD_CONST | 1,026,680 | 3.5% |
| CALL_BUILTIN_CLASS | 282,674 | 1.0% |
| LOAD_FAST | 204,192 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,404,405 | 32.4% |
| SWAP | 9,396,045 | 32.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,552,688 | 26.0% |
| LOAD_CONST | 1,068,180 | 3.7% |
| RETURN_VALUE | 432,295 | 1.5% |


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
| LOAD_CONST | 8,721,502 | 97.0% |
| LOAD_FAST | 263,367 | 2.9% |
| BINARY_SUBSCR | 2,735 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,584 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 322,079 | 3.6% |
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
| LOAD_FAST | 13,221,481 | 90.9% |
| BINARY_OP_ADD_INT | 540,088 | 3.7% |
| LOAD_FAST_LOAD_FAST | 480,419 | 3.3% |
| LOAD_ATTR | 152,040 | 1.0% |
| LOAD_DEREF | 83,580 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,691,951 | 87.2% |
| COPY_FREE_VARS | 1,196,598 | 8.2% |
| MAKE_CELL | 654,398 | 4.5% |
| POP_TOP | 7,360 | 0.1% |
| CALL_PY_EXACT_ARGS | 674 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,796,625 | 32.4% |
| CALL_BUILTIN_CLASS | 1,959,326 | 22.7% |
| LOAD_CONST | 710,920 | 8.2% |
| CALL_LEN | 611,046 | 7.1% |
| BINARY_SUBSCR | 571,546 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,069,958 | 35.6% |
| CALL_BUILTIN_CLASS | 1,959,326 | 22.7% |
| GET_ITER | 1,728,349 | 20.0% |
| CALL | 284,476 | 3.3% |
| BINARY_SUBSCR_LIST_INT | 282,674 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,055,733 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,264,948 | 39.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,210 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 55,472 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,002,317 | 41.8% |
| STORE_FAST | 10,922,901 | 25.4% |
| TO_BOOL | 10,287,220 | 23.9% |
| PUSH_NULL | 2,129,900 | 4.9% |
| RETURN_VALUE | 1,500,082 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,804 | 94.4% |
| LOAD_FAST | 135,124 | 2.6% |
| BINARY_OP | 119,158 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,084 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 128,024 | 2.5% |
| CALL_BUILTIN_CLASS | 119,158 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,707,211 | 41.7% |
| RETURN_GENERATOR | 10,212,114 | 27.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,612,972 | 14.9% |
| LOAD_ATTR_SLOT | 4,879,635 | 13.0% |
| BINARY_OP | 1,095,116 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,590,884 | 36.1% |
| RETURN_VALUE | 11,432,733 | 30.3% |
| TO_BOOL_BOOL | 9,889,925 | 26.2% |
| GET_ITER | 2,591,124 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,787,193 | 57.2% |
| LOAD_GLOBAL_BUILTIN | 18,938,684 | 30.3% |
| LOAD_DEREF | 3,017,974 | 4.8% |
| LOAD_FAST_LOAD_FAST | 2,763,468 | 4.4% |
| LOAD_FAST | 1,614,936 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,534,602 | 95.2% |
| YIELD_VALUE | 2,335,067 | 3.7% |
| COPY | 525,020 | 0.8% |
| RETURN_VALUE | 127,525 | 0.2% |
| TO_BOOL | 9,663 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,055,170 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 185,800 | 0.7% |
| RETURN_VALUE | 95,080 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,271,118 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,676,824 | 34.4% |
| LOAD_CONST | 7,190,962 | 25.6% |
| CALL_BUILTIN_CLASS | 611,046 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,555,100 | 64.8% |
| BUILD_TUPLE | 3,216,080 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 959,820 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,102,367 | 62.9% |
| EXTENDED_ARG | 4,571,161 | 19.0% |
| JUMP_BACKWARD | 2,240,687 | 9.3% |
| LOAD_FAST | 1,681,756 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,162,082 | 68.9% |
| LOAD_CONST | 2,388,471 | 10.8% |
| BUILD_LIST | 2,294,395 | 10.4% |
| BUILD_MAP | 1,561,360 | 7.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 272,556 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,867,007 | 58.4% |
| STORE_FAST | 3,415,380 | 15.5% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.2% |
| POP_TOP | 908,820 | 4.1% |
| GET_ITER | 737,595 | 3.3% |


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
| LOAD_ATTR_METHOD_NO_DICT | 24,512,219 | 83.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,634 | 16.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,789 | 0.4% |
| LOAD_ATTR | 72,820 | 0.2% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,456,823 | 49.0% |
| STORE_FAST | 9,686,780 | 32.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,804 | 16.5% |
| CALL_BUILTIN_CLASS | 169,723 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,789 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.2% |
| LOAD_CONST | 1,226,503 | 26.7% |
| LOAD_FAST | 296,920 | 6.5% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.4% |
| LOAD_CONST | 1,224,503 | 26.7% |
| TO_BOOL_NONE | 48,400 | 1.1% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,801,469 | 31.3% |
| LOAD_FAST | 15,662,247 | 23.6% |
| GET_ITER | 13,022,313 | 19.6% |
| LOAD_FAST_LOAD_FAST | 12,388,063 | 18.6% |
| LOAD_SUPER_ATTR_METHOD | 1,539,377 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 49,548,874 | 74.5% |
| COPY_FREE_VARS | 11,836,345 | 17.8% |
| RETURN_GENERATOR | 4,117,124 | 6.2% |
| MAKE_CELL | 770,471 | 1.2% |
| CALL_PY_EXACT_ARGS | 144,991 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,622,006 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,413,442 | 30.8% |
| ENTER_EXECUTOR | 974,818 | 21.2% |
| RETURN_VALUE | 192,678 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,996 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,373,343 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,725 | 1.2% |
| CALL_PY_WITH_DEFAULTS | 220 | 0.0% |
| CALL_PY_EXACT_ARGS | 120 | 0.0% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,084 | 80.4% |
| LOAD_FAST | 1,017,309 | 17.4% |
| STORE_FAST | 105,764 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,144 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,284 | 80.4% |
| BINARY_SUBSCR_DICT | 443,840 | 7.6% |
| STORE_FAST | 353,204 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,728,745 | 99.2% |
| LOAD_CONST | 119,970 | 0.8% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,588 | 43.3% |
| COMPARE_OP | 5,882,465 | 39.6% |
| LOAD_ATTR | 2,352,277 | 15.8% |
| IS_OP | 64,230 | 0.4% |
| BUILD_TUPLE | 55,800 | 0.4% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,935 | 90.9% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,343 | 3.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,058 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,758,436 | 42.6% |
| LOAD_FAST_LOAD_FAST | 16,194,051 | 33.2% |
| CALL_LEN | 10,271,118 | 21.1% |
| LOAD_FAST | 1,020,444 | 2.1% |
| LOAD_ATTR_SLOT | 225,373 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,201,847 | 68.1% |
| BINARY_OP | 6,304,740 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.7% |
| EXTENDED_ARG | 1,719,889 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,566,000 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 68.9% |
| LOAD_CONST | 4,335,963 | 29.8% |
| LOAD_GLOBAL_MODULE | 192,556 | 1.3% |
| LOAD_ATTR | 3,160 | 0.0% |
| LOAD_FAST | 2,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,481,099 | 99.4% |
| YIELD_VALUE | 79,680 | 0.5% |
| POP_JUMP_IF_TRUE | 3,520 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,584 | 52.6% |
| GET_ITER | 90,696 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,664 | 52.1% |
| POP_TOP | 90,536 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,844,791 | 37.6% |
| GET_ITER | 4,311,572 | 33.4% |
| EXTENDED_ARG | 1,354,519 | 10.5% |
| SWAP | 1,221,435 | 9.5% |
| ENTER_EXECUTOR | 1,101,545 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,931,450 | 61.5% |
| LOAD_FAST | 2,085,131 | 16.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,484,421 | 11.5% |
| STORE_FAST_LOAD_FAST | 1,260,347 | 9.8% |
| RETURN_CONST | 85,451 | 0.7% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 669,095 | 47.9% |
| EXTENDED_ARG | 642,400 | 46.0% |
| SWAP | 38,880 | 2.8% |
| LOAD_FAST | 29,360 | 2.1% |
| JUMP_BACKWARD | 16,532 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,692 | 93.5% |
| STORE_FAST_LOAD_FAST | 47,440 | 3.4% |
| RETURN_CONST | 35,963 | 2.6% |
| LOAD_FAST | 3,780 | 0.3% |
| LOAD_GLOBAL_MODULE | 1,200 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,883,522 | 84.7% |
| LOAD_FAST | 517,678 | 4.4% |
| ENTER_EXECUTOR | 474,144 | 4.1% |
| EXTENDED_ARG | 395,000 | 3.4% |
| SWAP | 299,295 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,112,161 | 86.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 451,846 | 3.9% |
| STORE_FAST_LOAD_FAST | 409,136 | 3.5% |
| RETURN_CONST | 369,287 | 3.2% |
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
| LOAD_FAST | 5,478,856 | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,928 | 11.7% |
| LOAD_DEREF | 1,058,388 | 11.7% |
| COPY | 956,400 | 10.6% |
| LOAD_GLOBAL_MODULE | 481,593 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,443 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,210 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,225,003 | 13.5% |
| STORE_FAST | 1,076,088 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,928 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,902,576 | 85.8% |
| RETURN_VALUE | 4,635,548 | 5.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.5% |
| LOAD_GLOBAL_MODULE | 1,964,951 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,443 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,794,650 | 34.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,512,219 | 27.3% |
| CALL_PY_EXACT_ARGS | 20,801,469 | 23.2% |
| LOAD_CONST | 4,052,847 | 4.5% |
| LOAD_DEREF | 3,319,038 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 21,115,081 | 71.4% |
| LOAD_ATTR_SLOT | 4,711,184 | 15.9% |
| LOAD_FAST | 3,523,032 | 11.9% |
| LOAD_ATTR | 147,514 | 0.5% |
| STORE_FAST_LOAD_FAST | 45,840 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,091,585 | 51.0% |
| LOAD_FAST_LOAD_FAST | 9,344,730 | 31.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,634 | 16.3% |
| CALL_PY_EXACT_ARGS | 313,622 | 1.1% |
| LOAD_CONST | 6,623 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,261,152 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,403 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,497 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,718 | 6.3% |
| CALL | 57,380 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR | 19,780 | 1.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,587,128 | 87.2% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| ENTER_EXECUTOR | 2,966,042 | 5.2% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 215,637 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,382,805 | 74.5% |
| CALL_BUILTIN_O | 5,612,972 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,921,268 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,676 | 2.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 996,759 | 60.4% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.0% |
| LOAD_DEREF | 144,340 | 8.7% |
| LOAD_ATTR | 12,020 | 0.7% |
| ENTER_EXECUTOR | 10,586 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.0% |
| TO_BOOL_STR | 478,200 | 29.0% |
| TO_BOOL_BOOL | 410,439 | 24.9% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,300,017 | 90.4% |
| ENTER_EXECUTOR | 1,312,139 | 4.7% |
| RETURN_VALUE | 642,675 | 2.3% |
| STORE_FAST_LOAD_FAST | 201,954 | 0.7% |
| LOAD_DEREF | 190,732 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,812,747 | 67.2% |
| COPY_FREE_VARS | 5,065,519 | 18.1% |
| GET_ITER | 1,920,389 | 6.9% |
| TO_BOOL_BOOL | 709,451 | 2.5% |
| STORE_FAST | 506,230 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,136,651 | 98.6% |
| LOAD_ATTR_SLOT | 613,709 | 0.6% |
| ENTER_EXECUTOR | 553,290 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,046 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 69,993 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,432,382 | 35.0% |
| STORE_FAST | 22,508,154 | 23.6% |
| LOAD_DEREF | 6,404,317 | 6.7% |
| LOAD_FAST | 5,202,888 | 5.4% |
| LOAD_CONST | 5,202,605 | 5.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,704,346 | 25.5% |
| RESUME_CHECK | 41,265,167 | 18.3% |
| STORE_FAST | 32,309,106 | 14.3% |
| STORE_FAST_STORE_FAST | 22,035,073 | 9.8% |
| LOAD_FAST | 20,354,524 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 156,095,275 | 69.1% |
| LOAD_FAST_LOAD_FAST | 28,705,700 | 12.7% |
| CALL_ISINSTANCE | 18,938,684 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 8,972,642 | 4.0% |
| LOAD_DEREF | 3,220,852 | 1.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,809,835 | 50.8% |
| RESUME_CHECK | 16,028,492 | 13.2% |
| STORE_FAST | 11,363,358 | 9.3% |
| POP_JUMP_IF_FALSE | 9,674,960 | 8.0% |
| NOP | 6,377,719 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 35,787,193 | 29.4% |
| LOAD_ATTR | 33,554,593 | 27.6% |
| LOAD_FAST | 29,410,909 | 24.2% |
| CONTAINS_OP | 5,290,376 | 4.4% |
| LOAD_FAST_LOAD_FAST | 3,280,305 | 2.7% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,536 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,181,936 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,614 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,377 | 85.1% |
| LOAD_GLOBAL_MODULE | 172,237 | 9.5% |
| LOAD_FAST | 78,580 | 4.3% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 99,193,772 | 38.6% |
| CALL_PY_EXACT_ARGS | 49,548,874 | 19.3% |
| COPY_FREE_VARS | 21,785,983 | 8.5% |
| LOAD_ATTR_PROPERTY | 18,812,747 | 7.3% |
| POP_TOP | 14,345,959 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,556,636 | 45.0% |
| LOAD_GLOBAL_BUILTIN | 41,265,167 | 16.1% |
| NOP | 21,363,941 | 8.3% |
| LOAD_FAST_LOAD_FAST | 18,753,502 | 7.3% |
| LOAD_GLOBAL_MODULE | 16,028,492 | 6.2% |


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
| LOAD_FAST | 2,103,701 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,123 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,665 | 36.0% |
| RETURN_CONST | 887,362 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,358 | 52.2% |
| LOAD_FAST | 4,285,086 | 47.3% |
| STORE_ATTR_SLOT | 41,715 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,673,138 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,363 | 24.9% |
| LOAD_CONST | 1,890,729 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,854 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,571,883 | 68.9% |
| LOAD_FAST | 397,956 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,323 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,652,380 | 72.4% |
| EXTENDED_ARG | 226,736 | 9.9% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.0% |
| LOAD_FAST | 165,800 | 7.3% |
| LOAD_GLOBAL_MODULE | 38,943 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,849,019 | 93.3% |
| SWAP | 1,067,720 | 5.3% |
| BINARY_SUBSCR_DICT | 112,800 | 0.6% |
| LOAD_FAST | 99,416 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,021,105 | 49.6% |
| ENTER_EXECUTOR | 9,864,325 | 48.8% |
| JUMP_BACKWARD | 250,225 | 1.2% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,627 | 98.7% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| ENTER_EXECUTOR | 480 | 0.2% |
| TO_BOOL | 388 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 217,403 | 95.1% |
| POP_JUMP_IF_FALSE | 9,799 | 4.3% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 53 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 59,534,602 | 35.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,382,805 | 25.0% |
| LOAD_FAST | 21,602,243 | 12.7% |
| CALL_BUILTIN_FAST | 18,002,317 | 10.6% |
| CALL_BUILTIN_O | 9,889,925 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 109,487,176 | 64.5% |
| POP_JUMP_IF_TRUE | 54,182,488 | 31.9% |
| EXTENDED_ARG | 5,065,925 | 3.0% |
| UNARY_NOT | 1,084,984 | 0.6% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,176,127 | 95.3% |
| BINARY_OP | 733,096 | 3.8% |
| BINARY_SUBSCR_TUPLE_INT | 63,355 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,280 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,864 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,364,457 | 54.4% |
| POP_JUMP_IF_TRUE | 8,698,628 | 45.6% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 163 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,228,652 | 97.5% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,105 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |
| TO_BOOL | 2,143 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 823,688 | 36.0% |
| POP_JUMP_IF_TRUE | 784,517 | 34.3% |
| UNARY_NOT | 661,875 | 29.0% |
| EXTENDED_ARG | 15,720 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,787 | 69.4% |
| RETURN_VALUE | 389,372 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,131 | 11.0% |
| CALL_METHOD_DESCRIPTOR_O | 48,400 | 1.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,862 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,944,358 | 73.3% |
| POP_JUMP_IF_TRUE | 689,916 | 26.0% |
| EXTENDED_ARG | 15,420 | 0.6% |
| TO_BOOL_BOOL | 1,681 | 0.1% |
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
| LOAD_FAST | 120,315 | 67.4% |
| RETURN_VALUE | 49,120 | 27.5% |
| CALL_BUILTIN_CLASS | 2,600 | 1.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 1.0% |
| BINARY_SUBSCR_LIST_INT | 1,240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 64.4% |
| STORE_FAST_STORE_FAST | 63,635 | 35.6% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 885,439 | 55.6% |
| RETURN_VALUE | 660,901 | 41.5% |
| STORE_FAST | 40,240 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,138 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,397,397 | 87.8% |
| STORE_FAST | 154,821 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 71,568,473 | 71.0% |
| RETURN_VALUE | 19,466,541 | 19.3% |
| BINARY_SUBSCR_LIST_INT | 7,552,688 | 7.5% |
| FOR_ITER_LIST | 1,484,421 | 1.5% |
| FOR_ITER_TUPLE | 451,846 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 96,935,838 | 96.2% |
| STORE_DEREF | 3,577,880 | 3.6% |
| STORE_FAST | 218,395 | 0.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,680 | 0.0% |
| UNPACK_SEQUENCE_LIST | 1,760 | 0.0% |


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
| BUILD_LIST | 20 | 16.7% |
| RETURN_CONST | 20 | 16.7% |


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


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 35,269,117 | 78.5% |
|          hit | 9,592,808 | 21.4% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,762 | 11.6% |
| Failure | 51,344 | 88.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,465 | 18.4% |
| multiply different types | 7,463 | 14.5% |
| subtract other | 6,800 | 13.2% |
| and int | 4,145 | 8.1% |
| rshift | 3,822 | 7.4% |
| or | 3,700 | 7.2% |
| power | 2,861 | 5.6% |
| true divide different types | 2,523 | 4.9% |
| multiply other | 2,360 | 4.6% |
| remainder | 2,314 | 4.5% |
| add different types | 1,941 | 3.8% |
| floor divide | 1,272 | 2.5% |
| subtract different types | 1,195 | 2.3% |
| xor | 583 | 1.1% |
| and other | 374 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 223 | 0.4% |
| true divide float | 3 | 0.0% |


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
|     deferred | 24,141,692 | 36.8% |
|          hit | 41,441,447 | 63.2% |
|         miss | 14,924 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,715 | 32.5% |
| Failure | 16,030 | 67.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 12,207 | 76.2% |
| out of range | 2,040 | 12.7% |
| buffer int | 1,760 | 11.0% |
| array int | 20 | 0.1% |
| tuple slice | 3 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,135,309 | 6.3% |
|        deopt | 22,840 | 0.0% |
|          hit | 355,215,826 | 85.9% |
|         miss | 31,495,738 | 7.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 674,697 | 90.3% |
| Failure | 72,841 | 9.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,577 | 39.2% |
| code complex parameters | 14,055 | 19.3% |
| class no vectorcall | 9,220 | 12.7% |
| cfunc varargs keywords | 6,383 | 8.8% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.5% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,166 | 3.0% |
| meth descr varargs | 1,920 | 2.6% |
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
|     deferred | 38,495,925 | 37.6% |
|          hit | 63,311,755 | 61.8% |
|         miss | 575,987 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,467 | 22.8% |
| Failure | 69,362 | 77.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,493 | 26.7% |
| other | 15,248 | 22.0% |
| different types | 12,272 | 17.7% |
| tuple | 10,062 | 14.5% |
| string | 9,960 | 14.4% |
| bool | 2,127 | 3.1% |
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
|     deferred | 104,208,006 | 79.9% |
|          hit | 25,566,415 | 19.6% |
|         miss | 582,086 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,873 | 20.9% |
| Failure | 86,313 | 79.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 58,049 | 67.3% |
| set | 9,115 | 10.6% |
| zip | 7,600 | 8.8% |
| enumerate | 4,229 | 4.9% |
| other | 2,720 | 3.2% |
| itertools | 1,940 | 2.2% |
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
|     deferred | 120,266,950 | 27.7% |
|        deopt | 20 | 0.0% |
|          hit | 245,794,720 | 56.7% |
|         miss | 65,936,424 | 15.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,321,782 | 89.2% |
| Failure | 160,229 | 10.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 60,831 | 38.0% |
| mutable class | 58,761 | 36.7% |
| method | 10,465 | 6.5% |
| has managed dict | 8,780 | 5.5% |
| overridden | 8,666 | 5.4% |
| shadowed | 5,300 | 3.3% |
| class method obj | 3,900 | 2.4% |
| builtin class method | 1,320 | 0.8% |
| not managed dict | 1,106 | 0.7% |
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
|     deferred | 89,881 | 0.0% |
|          hit | 347,452,553 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,922 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 603 | 0.0% |
|          hit | 2,990,050 | 100.0% |

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
|     deferred | 540,657 | 4.2% |
|          hit | 10,200,996 | 78.4% |
|         miss | 2,218,047 | 17.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,775 | 92.3% |
| Failure | 3,906 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,960 | 50.2% |
| not managed dict | 1,446 | 37.0% |
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
|     deferred | 3,422,199 | 13.2% |
|          hit | 22,481,017 | 86.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,720 | 42.8% |
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
|     deferred | 12,842,097 | 6.2% |
|          hit | 194,116,512 | 93.6% |
|         miss | 440,225 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,913 | 72.2% |
| Failure | 23,045 | 27.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,794 | 46.8% |
| number | 3,525 | 15.3% |
| mapping | 3,300 | 14.3% |
| dict | 2,340 | 10.2% |
| other | 1,618 | 7.0% |
| set | 1,428 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,564 | 0.0% |
|          hit | 102,509,066 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,384 | 93.6% |
| Failure | 774 | 6.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 714 | 92.2% |
| iterator | 60 | 7.8% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 3,009,047,451 | 54.2% |
| Not specialized | 780,872,945 | 14.1% |
| Specialized hits | 1,663,956,531 | 30.0% |
| Specialized misses | 101,314,671 | 1.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 120,266,950 | 32.9% |
| FOR_ITER | 104,208,006 | 28.5% |
| COMPARE_OP | 38,495,925 | 10.5% |
| BINARY_OP | 35,269,117 | 9.6% |
| CALL | 26,135,309 | 7.1% |
| BINARY_SUBSCR | 24,141,692 | 6.6% |
| TO_BOOL | 12,842,097 | 3.5% |
| STORE_SUBSCR | 3,422,199 | 0.9% |
| STORE_ATTR | 540,657 | 0.1% |
| SEND | 439,140 | 0.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,453,731 | 36.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,761,623 | 15.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,453,414 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 9,129,698 | 9.0% |
| CALL_PY_EXACT_ARGS | 7,811,401 | 7.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,393 | 6.4% |
| LOAD_ATTR_PROPERTY | 4,105,543 | 4.1% |
| CALL_BUILTIN_O | 2,661,171 | 2.6% |
| STORE_ATTR_SLOT | 2,217,067 | 2.2% |
| COMPARE_OP_INT | 574,387 | 0.6% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,631,130 | 48.7% |
| Calls to Python functions inlined | 134,203,744 | 51.3% |
| Calls via PyEval_EvalFrame (total) | 127,631,130 | 48.7% |
| Calls via PyEval_EvalFrame (vector) | 98,450,987 | 37.6% |
| Calls via PyEval_EvalFrame (generator) | 29,180,143 | 11.1% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,443,687 | 37.6% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,145 | 9.0% |
| Calls via PyEval_EvalFrame (function ex) | 11,824,921 | 4.5% |
| Calls via PyEval_EvalFrame (api) | 53,323,779 | 20.4% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,333 | 0.5% |
| Frames pushed | 112,626,993 | 43.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,441,592 | 54.3% |
| Frees to freelist | 363,684,502 |  |
| Allocations | 305,644,780 | 45.7% |
| Allocations to 512 bytes | 304,575,726 | 45.5% |
| Allocations to 4 kbytes | 1,044,594 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,319,528 |  |
| New values | 1,057,381 |  |
| Interpreter increfs | 2,656,765,577 | 65.3% |
| Interpreter decrefs | 3,071,621,135 | 66.0% |
| Increfs | 1,413,428,158 | 34.7% |
| Decrefs | 1,579,403,618 | 34.0% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,712,381 |  |
| Method cache misses | 4,343,942 |  |
| Method cache collisions | 6,008,182 |  |
| Method cache dunder hits | 346,972,129 |  |
| Method cache dunder misses | 1,664,823 |  |


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
| Optimization attempts | 3,990,263 |  |
| Traces created | 9,997 | 0.3% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 121 | 0.0% |
| Trace too long | 40 | 0.0% |
| Trace too short | 3,980,266 | 99.7% |
| Inner loop found | 80 | 0.0% |
| Recursive call | 160 | 0.0% |
| Traces executed | 84,120,938 |  |
| Uops executed | 1,155,425,296 | 13.74 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 0.2% |
| <= 16 | 3,326 | 33.3% |
| <= 32 | 4,153 | 41.5% |
| <= 64 | 1,728 | 17.3% |
| <= 128 | 770 | 7.7% |


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
| <= 16 | 4,039 | 40.4% |
| <= 32 | 3,900 | 39.0% |
| <= 64 | 1,688 | 16.9% |
| <= 128 | 330 | 3.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 2,711,939 | 3.2% |
| <= 4 | 16,820 | 0.0% |
| <= 8 | 19,683,364 | 23.4% |
| <= 16 | 40,009,285 | 47.6% |
| <= 32 | 18,753,942 | 22.3% |
| <= 64 | 2,575,026 | 3.1% |
| <= 128 | 325,982 | 0.4% |
| <= 256 | 34,773 | 0.0% |
| <= 512 | 9,627 | 0.0% |
| <= 1,024 | 100 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 3,974,450 |
| FOR_ITER_GEN | 5,836 |
| LOAD_ATTR_PROPERTY | 2,606 |
| LOAD_ATTR | 1,520 |
| YIELD_VALUE | 780 |
| CALL | 493 |
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
Stats gathered on: 2023-11-02
