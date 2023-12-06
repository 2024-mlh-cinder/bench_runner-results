
# Pystats results

- benchmark: sympy
- fork: python
- ref: dabc0d77b21d8cc619a2ffcf859f684b6c1c7020
- commit hash: dabc0d7
- commit date: 2023-11-17T15:11:30-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 898,860,510 | 16.6% | 16.6% |  |
| STORE_FAST | 295,388,978 | 5.4% | 22.0% |  |
| POP_JUMP_IF_FALSE | 262,530,652 | 4.8% | 26.9% |  |
| RESUME_CHECK | 256,650,536 | 4.7% | 31.6% |  |
| LOAD_FAST_LOAD_FAST | 228,469,548 | 4.2% | 35.8% |  |
| LOAD_GLOBAL_BUILTIN | 225,866,853 | 4.2% | 40.0% | 0.0% |
| LOAD_CONST | 178,815,587 | 3.3% | 43.3% |  |
| RETURN_VALUE | 177,408,416 | 3.3% | 46.5% |  |
| TO_BOOL_BOOL | 169,069,632 | 3.1% | 49.6% | 0.1% |
| INTERPRETER_EXIT | 127,268,088 | 2.3% | 52.0% |  |
| LOAD_GLOBAL_MODULE | 117,813,074 | 2.2% | 54.2% | 0.0% |
| FOR_ITER | 103,610,572 | 1.9% | 56.1% |  |
| STORE_FAST_STORE_FAST | 103,413,711 | 1.9% | 58.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 100,529,980 | 1.9% | 59.8% |  |
| LOAD_ATTR_SLOT | 95,505,560 | 1.8% | 61.6% | 38.2% |
| LOAD_ATTR | 91,990,906 | 1.7% | 63.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 89,532,159 | 1.7% | 64.9% | 10.2% |
| POP_JUMP_IF_TRUE | 74,697,366 | 1.4% | 66.3% |  |
| JUMP_BACKWARD | 67,701,118 | 1.2% | 67.6% |  |
| CALL_PY_EXACT_ARGS | 66,416,395 | 1.2% | 68.8% | 11.8% |
| CALL_ISINSTANCE | 62,538,662 | 1.2% | 69.9% |  |
| LOAD_DEREF | 62,353,922 | 1.1% | 71.1% |  |
| ENTER_EXECUTOR | 61,868,064 | 1.1% | 72.2% |  |
| POP_TOP | 61,514,697 | 1.1% | 73.4% |  |
| GET_ITER | 59,407,994 | 1.1% | 74.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,796,960 | 1.0% | 75.5% | 27.8% |
| RETURN_CONST | 56,589,406 | 1.0% | 76.5% |  |
| BUILD_TUPLE | 50,195,397 | 0.9% | 77.5% |  |
| COMPARE_OP_INT | 48,729,787 | 0.9% | 78.4% | 1.2% |
| IS_OP | 45,343,950 | 0.8% | 79.2% |  |
| SWAP | 45,018,725 | 0.8% | 80.0% |  |
| CALL_BUILTIN_FAST | 43,250,051 | 0.8% | 80.8% |  |
| PUSH_NULL | 42,913,656 | 0.8% | 81.6% |  |
| POP_JUMP_IF_NONE | 40,535,836 | 0.7% | 82.4% |  |
| COMPARE_OP | 37,926,232 | 0.7% | 83.1% |  |
| CALL_BUILTIN_O | 37,637,171 | 0.7% | 83.8% | 7.1% |
| BINARY_OP | 35,213,828 | 0.6% | 84.4% |  |
| COPY_FREE_VARS | 31,732,995 | 0.6% | 85.0% |  |
| NOP | 31,471,687 | 0.6% | 85.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,475,475 | 0.5% | 86.1% | 22.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 29,404,672 | 0.5% | 86.7% | 0.5% |
| BINARY_SUBSCR_LIST_INT | 28,985,989 | 0.5% | 87.2% | 0.0% |
| CALL_LEN | 28,082,291 | 0.5% | 87.7% |  |
| CALL_FUNCTION_EX | 28,012,918 | 0.5% | 88.2% |  |
| LOAD_ATTR_PROPERTY | 27,993,806 | 0.5% | 88.7% | 14.7% |
| BUILD_MAP | 27,215,221 | 0.5% | 89.2% |  |
| CALL | 26,847,983 | 0.5% | 89.7% |  |
| CALL_LIST_APPEND | 24,016,991 | 0.4% | 90.2% |  |
| YIELD_VALUE | 22,925,198 | 0.4% | 90.6% |  |
| FOR_ITER_LIST | 22,829,790 | 0.4% | 91.0% | 2.1% |
| BINARY_SUBSCR | 22,234,877 | 0.4% | 91.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 21,857,240 | 0.4% | 91.8% | 65.4% |
| BUILD_LIST | 21,580,279 | 0.4% | 92.2% |  |
| FOR_ITER_TUPLE | 20,912,763 | 0.4% | 92.6% | 3.7% |
| STORE_SUBSCR_LIST_INT | 20,189,459 | 0.4% | 93.0% |  |
| TO_BOOL_INT | 19,039,578 | 0.4% | 93.3% | 0.1% |
| CONTAINS_OP | 18,993,055 | 0.4% | 93.7% |  |
| POP_JUMP_IF_NOT_NONE | 18,051,122 | 0.3% | 94.0% |  |
| EXTENDED_ARG | 17,084,720 | 0.3% | 94.3% |  |
| LOAD_FAST_AND_CLEAR | 16,788,127 | 0.3% | 94.7% |  |
| DICT_MERGE | 16,700,371 | 0.3% | 95.0% |  |
| CALL_TYPE_1 | 14,851,781 | 0.3% | 95.2% |  |
| COMPARE_OP_STR | 14,524,349 | 0.3% | 95.5% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,384,705 | 0.3% | 95.8% | 0.3% |
| RETURN_GENERATOR | 14,319,461 | 0.3% | 96.0% |  |
| TO_BOOL | 12,897,125 | 0.2% | 96.3% |  |
| MAKE_FUNCTION | 12,370,972 | 0.2% | 96.5% |  |
| CALL_KW | 10,673,200 | 0.2% | 96.7% |  |
| SET_FUNCTION_ATTRIBUTE | 10,355,161 | 0.2% | 96.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,064,279 | 0.2% | 97.1% | 0.0% |
| STORE_ATTR_SLOT | 9,060,348 | 0.2% | 97.2% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,985,477 | 0.2% | 97.4% | 0.1% |
| IMPORT_FROM | 8,955,235 | 0.2% | 97.6% |  |
| CALL_BUILTIN_CLASS | 8,538,412 | 0.2% | 97.7% |  |
| MAP_ADD | 7,866,612 | 0.1% | 97.9% |  |
| IMPORT_NAME | 7,759,946 | 0.1% | 98.0% |  |
| STORE_DEREF | 7,702,409 | 0.1% | 98.1% |  |
| MAKE_CELL | 6,049,303 | 0.1% | 98.3% |  |
| CALL_TUPLE_1 | 5,849,109 | 0.1% | 98.4% | 0.0% |
| JUMP_FORWARD | 5,744,164 | 0.1% | 98.5% |  |
| UNARY_NOT | 5,273,842 | 0.1% | 98.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,853 | 0.1% | 98.7% | 0.1% |
| COPY | 4,616,584 | 0.1% | 98.7% |  |
| CALL_PY_WITH_DEFAULTS | 4,591,265 | 0.1% | 98.8% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,590,622 | 0.1% | 98.9% | 0.2% |
| BINARY_OP_ADD_INT | 3,743,358 | 0.1% | 99.0% |  |
| LIST_APPEND | 3,516,328 | 0.1% | 99.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,798 | 0.1% | 99.1% | 0.0% |
| STORE_SUBSCR | 3,302,150 | 0.1% | 99.2% |  |
| BINARY_SUBSCR_DICT | 3,165,261 | 0.1% | 99.2% |  |
| BINARY_OP_MULTIPLY_INT | 2,757,734 | 0.1% | 99.3% | 0.0% |
| TO_BOOL_NONE | 2,653,366 | 0.0% | 99.3% | 8.5% |
| BINARY_OP_SUBTRACT_INT | 2,473,562 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 2,286,544 | 0.0% | 99.4% | 0.5% |
| STORE_SUBSCR_DICT | 2,278,686 | 0.0% | 99.5% |  |
| FOR_ITER_RANGE | 2,224,685 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,809,841 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,080 | 0.0% | 99.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,646,030 | 0.0% | 99.6% | 20.5% |
| UNPACK_SEQUENCE_TUPLE | 1,592,076 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,578,337 | 0.0% | 99.7% |  |
| LIST_EXTEND | 1,349,139 | 0.0% | 99.7% |  |
| CALL_INTRINSIC_1 | 1,349,099 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,723 | 0.0% | 99.7% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,181,938 | 0.0% | 99.8% |  |
| SEND_GEN | 1,029,804 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,424 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,424 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,424 | 0.0% | 99.9% |  |
| STORE_ATTR | 591,358 | 0.0% | 99.9% |  |
| BINARY_SLICE | 569,006 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 551,660 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,621 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,384 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 533,067 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 503,100 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 228,487 | 0.0% | 100.0% | 36.3% |
| FOR_ITER_GEN | 191,236 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,492 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,560 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,252 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 132,560 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,377 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,086 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 72,820 | 0.0% | 100.0% |  |
| BUILD_SET | 50,403 | 0.0% | 100.0% |  |
| RESUME | 47,508 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,696 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,499 | 0.0% | 100.0% |  |
| SET_ADD | 19,280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,260 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,760 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,000 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,200 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 159,706,062 | 2.9% | 2.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 156,050,369 | 2.9% | 5.8% |
| RESUME_CHECK LOAD_FAST | 115,520,905 | 2.1% | 7.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 108,770,908 | 2.0% | 10.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 108,540,778 | 2.0% | 12.0% |
| CACHE RESUME_CHECK | 99,067,715 | 1.8% | 13.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 96,727,441 | 1.8% | 15.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,131,194 | 1.7% | 17.3% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 76,802,034 | 1.4% | 18.7% |
| RETURN_VALUE INTERPRETER_EXIT | 72,896,221 | 1.3% | 20.1% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 70,851,289 | 1.3% | 21.4% |
| JUMP_BACKWARD FOR_ITER | 67,397,538 | 1.2% | 22.6% |
| LOAD_FAST LOAD_CONST | 60,544,938 | 1.1% | 23.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 59,534,756 | 1.1% | 24.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 58,158,962 | 1.1% | 25.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,855,777 | 1.1% | 27.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 54,148,980 | 1.0% | 28.0% |
| LOAD_FAST RETURN_VALUE | 52,910,129 | 1.0% | 28.9% |
| LOAD_FAST LOAD_ATTR | 51,076,737 | 0.9% | 29.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 50,446,797 | 0.9% | 30.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 49,535,321 | 0.9% | 31.7% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 49,515,231 | 0.9% | 32.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,303,574 | 0.8% | 33.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,255,534 | 0.8% | 34.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 40,963,455 | 0.8% | 34.9% |
| LOAD_CONST LOAD_CONST | 40,205,013 | 0.7% | 35.7% |
| RETURN_VALUE STORE_FAST | 38,553,993 | 0.7% | 36.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 36,028,833 | 0.7% | 37.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 35,787,353 | 0.7% | 37.7% |
| PUSH_NULL LOAD_FAST | 35,354,189 | 0.7% | 38.4% |
| LOAD_ATTR STORE_FAST | 34,992,341 | 0.6% | 39.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,547,870 | 0.6% | 39.6% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,432,308 | 0.6% | 40.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,153,817 | 0.6% | 40.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 33,025,073 | 0.6% | 41.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 32,307,675 | 0.6% | 42.0% |
| RETURN_CONST INTERPRETER_EXIT | 32,284,810 | 0.6% | 42.6% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 31,277,905 | 0.6% | 43.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 30,794,957 | 0.6% | 43.8% |
| IS_OP POP_JUMP_IF_FALSE | 29,996,352 | 0.6% | 44.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 29,321,049 | 0.5% | 44.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 28,738,800 | 0.5% | 45.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,702,130 | 0.5% | 45.9% |
| LOAD_FAST CALL_LEN | 27,053,130 | 0.5% | 46.4% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 26,347,993 | 0.5% | 46.9% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,299,999 | 0.5% | 47.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 24,469,402 | 0.5% | 47.8% |
| BINARY_OP STORE_FAST | 24,166,211 | 0.4% | 48.3% |
| LOAD_CONST CALL_BUILTIN_FAST | 24,046,959 | 0.4% | 48.7% |
| LOAD_ATTR_SLOT STORE_FAST | 22,510,049 | 0.4% | 49.1% |
| YIELD_VALUE INTERPRETER_EXIT | 22,079,317 | 0.4% | 49.6% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_BUILTIN | 22,003,144 | 0.4% | 50.0% |
| COPY_FREE_VARS RESUME_CHECK | 21,776,765 | 0.4% | 50.4% |
| LOAD_FAST TO_BOOL_BOOL | 21,602,138 | 0.4% | 50.8% |
| RESUME_CHECK NOP | 21,363,645 | 0.4% | 51.2% |
| LOAD_FAST GET_ITER | 21,260,466 | 0.4% | 51.5% |
| BUILD_TUPLE RETURN_VALUE | 21,220,953 | 0.4% | 51.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,088,619 | 0.4% | 52.3% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 20,940,986 | 0.4% | 52.7% |
| POP_JUMP_IF_NONE JUMP_BACKWARD | 20,900,632 | 0.4% | 53.1% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,792,283 | 0.4% | 53.5% |
| STORE_FAST_STORE_FAST LOAD_DEREF | 20,770,526 | 0.4% | 53.9% |
| LOAD_CONST COMPARE_OP_INT | 20,732,521 | 0.4% | 54.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 20,354,578 | 0.4% | 54.6% |
| GET_ITER FOR_ITER | 19,801,812 | 0.4% | 55.0% |
| COMPARE_OP POP_JUMP_IF_FALSE | 19,488,809 | 0.4% | 55.3% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,465,504 | 0.4% | 55.7% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 19,059,470 | 0.4% | 56.1% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 18,938,702 | 0.3% | 56.4% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,843,203 | 0.3% | 56.7% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,813,348 | 0.3% | 57.1% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 18,747,594 | 0.3% | 57.4% |
| LOAD_FAST TO_BOOL_INT | 18,162,479 | 0.3% | 57.8% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 18,000,919 | 0.3% | 58.1% |
| LOAD_FAST PUSH_NULL | 17,297,852 | 0.3% | 58.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,262,229 | 0.3% | 58.7% |
| LOAD_FAST BUILD_TUPLE | 17,005,486 | 0.3% | 59.1% |
| DICT_MERGE CALL_FUNCTION_EX | 16,700,371 | 0.3% | 59.4% |
| BUILD_MAP LOAD_FAST | 16,611,163 | 0.3% | 59.7% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,606,260 | 0.3% | 60.0% |
| LOAD_FAST DICT_MERGE | 16,571,459 | 0.3% | 60.3% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,178,718 | 0.3% | 60.6% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 16,112,097 | 0.3% | 60.9% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 16,080,760 | 0.3% | 61.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,027,562 | 0.3% | 61.5% |
| LOAD_ATTR LOAD_FAST | 15,962,217 | 0.3% | 61.8% |
| RESUME_CHECK LOAD_CONST | 15,734,609 | 0.3% | 62.1% |
| LOAD_FAST CALL_BUILTIN_O | 15,700,436 | 0.3% | 62.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,662,038 | 0.3% | 62.6% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 15,653,167 | 0.3% | 62.9% |
| LOAD_FAST CALL_LIST_APPEND | 15,555,402 | 0.3% | 63.2% |
| RETURN_VALUE RETURN_VALUE | 15,184,455 | 0.3% | 63.5% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 15,102,333 | 0.3% | 63.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 15,002,104 | 0.3% | 64.0% |
| RESUME_CHECK POP_TOP | 14,977,145 | 0.3% | 64.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 14,932,847 | 0.3% | 64.6% |
| LOAD_ATTR IS_OP | 14,930,446 | 0.3% | 64.9% |
| LOAD_FAST CALL_TYPE_1 | 14,728,875 | 0.3% | 65.1% |
| POP_TOP JUMP_BACKWARD | 14,661,170 | 0.3% | 65.4% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 14,481,097 | 0.3% | 65.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 535,646 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,590 | 56.2% |
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
| RESUME_CHECK | 99,067,715 | 77.7% |
| POP_TOP | 13,870,557 | 10.9% |
| COPY_FREE_VARS | 12,998,498 | 10.2% |
| MAKE_CELL | 1,509,094 | 1.2% |
| RESUME | 18,056 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 12,960,667 | 58.3% |
| LOAD_DEREF | 6,404,091 | 28.8% |
| BUILD_TUPLE | 1,732,771 | 7.8% |
| LOAD_FAST | 734,211 | 3.3% |
| RETURN_VALUE | 152,420 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,399,864 | 28.8% |
| LOAD_FAST | 6,296,657 | 28.3% |
| RETURN_VALUE | 6,066,184 | 27.3% |
| CALL | 909,544 | 4.1% |
| GET_ITER | 824,007 | 3.7% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,546 | 73.6% |
| BUILD_TUPLE | 157,232 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,306 | 8.7% |
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
| RETURN_CONST | 22,499 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,499 | 100.0% |


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
| LOAD_FAST | 21,260,466 | 35.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,416,888 | 24.3% |
| CALL | 10,953,438 | 18.4% |
| RETURN_VALUE | 4,116,843 | 6.9% |
| CALL_BUILTIN_O | 2,591,100 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 19,801,812 | 33.3% |
| CALL_PY_EXACT_ARGS | 12,990,251 | 21.9% |
| FOR_ITER_TUPLE | 9,903,372 | 16.7% |
| LOAD_FAST_AND_CLEAR | 9,198,174 | 15.5% |
| FOR_ITER_LIST | 4,369,744 | 7.4% |


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
| RETURN_VALUE | 72,896,221 | 57.3% |
| RETURN_CONST | 32,284,810 | 25.4% |
| YIELD_VALUE | 22,079,317 | 17.3% |
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
| LOAD_CONST | 12,370,972 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 10,353,621 | 83.7% |
| LOAD_GLOBAL_BUILTIN | 793,326 | 6.4% |
| STORE_FAST | 669,670 | 5.4% |
| LOAD_FAST | 458,557 | 3.7% |
| STORE_NAME | 33,580 | 0.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,363,645 | 67.9% |
| POP_JUMP_IF_TRUE | 4,183,900 | 13.3% |
| STORE_FAST | 1,973,340 | 6.3% |
| POP_JUMP_IF_FALSE | 1,913,106 | 6.1% |
| POP_TOP | 1,392,000 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,280,240 | 39.0% |
| LOAD_DEREF | 10,424,109 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,377,775 | 20.3% |
| LOAD_FAST_LOAD_FAST | 899,476 | 2.9% |
| LOAD_CONST | 751,140 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,667 | 45.7% |
| POP_TOP | 358,337 | 39.5% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,667 | 45.7% |
| EXTENDED_ARG | 201,290 | 22.2% |
| ENTER_EXECUTOR | 155,327 | 17.1% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,977,145 | 24.3% |
| CACHE | 13,870,557 | 22.5% |
| RETURN_CONST | 9,362,861 | 15.2% |
| STORE_FAST | 5,839,845 | 9.5% |
| SWAP | 5,778,549 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 14,661,170 | 23.8% |
| RESUME_CHECK | 14,313,901 | 23.3% |
| ENTER_EXECUTOR | 9,263,688 | 15.1% |
| LOAD_FAST | 7,247,151 | 11.8% |
| RETURN_VALUE | 5,302,349 | 8.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,597 | 41.3% |
| BINARY_SUBSCR_DICT | 169,943 | 18.7% |
| RAISE_VARARGS | 115,266 | 12.7% |
| ENTER_EXECUTOR | 102,292 | 11.3% |
| LOAD_ATTR | 89,180 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,198 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,786 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,297,852 | 40.3% |
| LOAD_DEREF | 11,886,494 | 27.7% |
| LOAD_ATTR | 8,385,135 | 19.5% |
| CALL_BUILTIN_FAST | 2,128,620 | 5.0% |
| LOAD_SUPER_ATTR_ATTR | 1,181,938 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,354,189 | 82.4% |
| LOAD_FAST_LOAD_FAST | 5,620,505 | 13.1% |
| LOAD_CONST | 1,723,680 | 4.0% |
| LOAD_DEREF | 127,440 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,875,550 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,117,091 | 28.8% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,080 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,180,108 | 71.1% |
| STORE_FAST | 2,660,363 | 18.6% |
| LOAD_FAST | 791,986 | 5.5% |
| GET_YIELD_FROM_ITER | 346,984 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,910,129 | 29.8% |
| LOAD_ATTR_SLOT | 33,432,308 | 18.8% |
| BUILD_TUPLE | 21,220,953 | 12.0% |
| RETURN_VALUE | 15,184,455 | 8.6% |
| CALL_BUILTIN_O | 11,432,657 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,896,221 | 41.1% |
| STORE_FAST | 38,553,993 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,465,504 | 11.0% |
| RETURN_VALUE | 15,184,455 | 8.6% |
| LOAD_FAST | 5,453,818 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,213,333 | 97.3% |
| BINARY_SUBSCR | 56,960 | 1.7% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.6% |
| SWAP | 5,960 | 0.2% |
| STORE_SUBSCR | 3,537 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,200,253 | 96.9% |
| ENTER_EXECUTOR | 60,440 | 1.8% |
| JUMP_BACKWARD | 19,700 | 0.6% |
| JUMP_FORWARD | 9,840 | 0.3% |
| STORE_SUBSCR | 3,537 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.8% |
| LOAD_FAST | 2,199,060 | 17.1% |
| LOAD_GLOBAL_MODULE | 119,057 | 0.9% |
| LOAD_ATTR | 117,976 | 0.9% |
| RETURN_VALUE | 27,288 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,225,379 | 94.8% |
| POP_JUMP_IF_TRUE | 509,832 | 4.0% |
| UNARY_NOT | 84,217 | 0.7% |
| TO_BOOL_BOOL | 41,150 | 0.3% |
| TO_BOOL | 21,350 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,480 | 22.0% |
| LOAD_FAST | 109,388 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,673 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,977 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,840 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,079 | 10.9% |
| CALL_LIST_APPEND | 39,980 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,665 | 65.3% |
| TO_BOOL_BOOL | 1,084,940 | 20.6% |
| TO_BOOL_LIST | 661,860 | 12.5% |
| TO_BOOL | 84,217 | 1.6% |
| TO_BOOL_INT | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,404 | 66.9% |
| STORE_FAST | 882,724 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,977 | 1.6% |
| LOAD_CONST | 34,357 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,753,128 | 33.4% |
| COMPARE_OP_INT | 6,304,740 | 17.9% |
| COMPARE_OP | 6,162,400 | 17.5% |
| CALL_TUPLE_1 | 4,707,284 | 13.4% |
| LOAD_FAST | 2,606,883 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,166,211 | 68.6% |
| RETURN_VALUE | 5,767,237 | 16.4% |
| BUILD_TUPLE | 1,556,880 | 4.4% |
| CALL_BUILTIN_O | 1,095,121 | 3.1% |
| LOAD_FAST | 857,820 | 2.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,377 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,597 | 97.9% |
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
| SWAP | 4,464,070 | 20.7% |
| POP_JUMP_IF_TRUE | 4,083,240 | 18.9% |
| STORE_FAST | 3,816,429 | 17.7% |
| LOAD_FAST | 2,312,000 | 10.7% |
| FOR_ITER | 1,566,468 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,713,061 | 54.3% |
| SWAP | 4,464,070 | 20.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,380 | 10.6% |
| LOAD_FAST | 1,374,439 | 6.4% |
| BUILD_LIST | 748,356 | 3.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,163,946 | 44.7% |
| SWAP | 4,716,104 | 17.3% |
| BUILD_TUPLE | 4,430,320 | 16.3% |
| LOAD_CONST | 1,656,760 | 6.1% |
| RESUME_CHECK | 1,285,960 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,611,163 | 61.0% |
| SWAP | 4,716,104 | 17.3% |
| STORE_FAST | 3,331,404 | 12.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 5.7% |
| CALL_FUNCTION_EX | 734,880 | 2.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,323 | 64.1% |
| SWAP | 18,000 | 35.7% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,323 | 64.1% |
| SWAP | 18,000 | 35.7% |
| STORE_FAST | 80 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 3,840 | 96.0% |
| BINARY_SUBSCR | 160 | 4.0% |


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
| LOAD_FAST_LOAD_FAST | 19,059,470 | 38.0% |
| LOAD_FAST | 17,005,486 | 33.9% |
| LOAD_ATTR_SLOT | 5,042,220 | 10.0% |
| LOAD_ATTR | 3,033,730 | 6.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,220,953 | 42.3% |
| LOAD_CONST | 10,372,813 | 20.7% |
| LOAD_GLOBAL_BUILTIN | 4,707,084 | 9.4% |
| BUILD_MAP | 4,430,320 | 8.8% |
| CALL_LIST_APPEND | 3,216,080 | 6.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,633,174 | 35.9% |
| LOAD_FAST | 7,276,867 | 27.1% |
| BINARY_OP_MULTIPLY_INT | 2,291,860 | 8.5% |
| ENTER_EXECUTOR | 2,006,166 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,916 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,438 | 40.8% |
| STORE_FAST | 5,844,806 | 21.8% |
| RETURN_VALUE | 4,525,174 | 16.9% |
| POP_TOP | 1,132,424 | 4.2% |
| RESUME_CHECK | 1,066,775 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 16,700,371 | 59.6% |
| ENTER_EXECUTOR | 6,573,160 | 23.5% |
| LOAD_FAST | 2,317,487 | 8.3% |
| CALL_INTRINSIC_1 | 1,256,761 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,600,850 | 45.0% |
| RESUME_CHECK | 11,673,493 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,830 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,347,879 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,761 | 93.2% |
| BUILD_MAP | 91,278 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,509,003 | 98.5% |
| ENTER_EXECUTOR | 164,197 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,239 | 88.9% |
| POP_TOP | 698,024 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,811 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,088,619 | 55.6% |
| LOAD_FAST | 7,692,511 | 20.3% |
| CALL_TYPE_1 | 5,882,502 | 15.5% |
| LOAD_GLOBAL_MODULE | 1,180,601 | 3.1% |
| LOAD_CONST | 949,905 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,488,809 | 51.4% |
| BINARY_OP | 6,162,400 | 16.2% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.2% |
| UNARY_NOT | 3,442,665 | 9.1% |
| POP_JUMP_IF_TRUE | 2,277,993 | 6.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 12,148,512 | 64.0% |
| LOAD_ATTR | 3,188,620 | 16.8% |
| LOAD_GLOBAL_MODULE | 1,646,094 | 8.7% |
| LOAD_DEREF | 1,479,900 | 7.8% |
| LOAD_CONST | 174,980 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,112,097 | 84.8% |
| POP_JUMP_IF_TRUE | 2,870,798 | 15.1% |
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
| LOAD_FAST | 1,237,504 | 26.8% |
| COPY | 1,069,360 | 23.2% |
| LOAD_FAST_LOAD_FAST | 868,240 | 18.8% |
| CALL_ISINSTANCE | 525,020 | 11.4% |
| LOAD_CONST | 236,755 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,338,376 | 29.0% |
| COPY | 1,069,360 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,063,080 | 23.0% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,555 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 12,998,498 | 41.0% |
| CALL_PY_EXACT_ARGS | 11,794,108 | 37.2% |
| LOAD_ATTR_PROPERTY | 5,066,540 | 16.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,196,584 | 3.8% |
| CALL_KW | 261,140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,776,765 | 68.6% |
| RETURN_GENERATOR | 9,875,550 | 31.1% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,180 | 0.0% |


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
| LOAD_FAST | 16,571,459 | 99.2% |
| LOAD_DEREF | 128,912 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 16,700,371 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 15,102,333 | 24.4% |
| POP_JUMP_IF_FALSE | 13,543,759 | 21.9% |
| STORE_SUBSCR_LIST_INT | 9,859,093 | 15.9% |
| POP_TOP | 9,263,688 | 15.0% |
| EXTENDED_ARG | 5,757,715 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 9,638,631 | 15.6% |
| RESUME_CHECK | 9,386,658 | 15.2% |
| FOR_ITER_TUPLE | 9,320,171 | 15.1% |
| POP_JUMP_IF_FALSE | 6,579,224 | 10.6% |
| CALL_FUNCTION_EX | 6,573,160 | 10.6% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,063,524 | 29.6% |
| CALL_LIST_APPEND | 4,571,169 | 26.8% |
| GET_ITER | 2,378,126 | 13.9% |
| ENTER_EXECUTOR | 1,742,137 | 10.2% |
| COMPARE_OP_INT | 1,719,897 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,647,032 | 38.9% |
| ENTER_EXECUTOR | 5,757,715 | 33.7% |
| FOR_ITER_LIST | 2,686,841 | 15.7% |
| FOR_ITER_TUPLE | 767,880 | 4.5% |
| FOR_ITER_RANGE | 642,400 | 3.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 67,397,538 | 65.0% |
| GET_ITER | 19,801,812 | 19.1% |
| SWAP | 7,638,524 | 7.4% |
| LOAD_FAST | 7,605,731 | 7.3% |
| ENTER_EXECUTOR | 1,053,544 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 70,851,289 | 68.4% |
| STORE_FAST | 8,331,575 | 8.0% |
| SWAP | 7,602,844 | 7.3% |
| RETURN_CONST | 4,699,396 | 4.5% |
| LOAD_FAST | 4,691,603 | 4.5% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,758,426 | 86.6% |
| STORE_FAST | 982,572 | 11.0% |
| STORE_DEREF | 185,697 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,822,201 | 76.2% |
| STORE_DEREF | 2,092,434 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,759,826 | 100.0% |
| ENTER_EXECUTOR | 100 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,758,426 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 14,930,446 | 32.9% |
| LOAD_FAST | 12,677,111 | 28.0% |
| LOAD_CONST | 10,976,345 | 24.2% |
| LOAD_FAST_LOAD_FAST | 5,893,599 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 539,778 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,996,352 | 66.2% |
| YIELD_VALUE | 12,661,771 | 27.9% |
| POP_JUMP_IF_TRUE | 2,641,647 | 5.8% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 20,900,632 | 30.9% |
| POP_JUMP_IF_TRUE | 16,080,760 | 23.8% |
| POP_TOP | 14,661,170 | 21.7% |
| MAP_ADD | 7,866,272 | 11.6% |
| CALL_LIST_APPEND | 2,241,889 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 67,397,538 | 99.6% |
| FOR_ITER_GEN | 100,496 | 0.1% |
| FOR_ITER_TUPLE | 83,072 | 0.1% |
| FOR_ITER_LIST | 55,615 | 0.1% |
| EXTENDED_ARG | 27,542 | 0.0% |


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
| STORE_FAST | 4,138,371 | 72.0% |
| POP_TOP | 734,252 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,864 | 3.3% |
| LOAD_FAST | 137,497 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,997,212 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,258 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,637 | 5.7% |
| STORE_FAST | 119,097 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,568,829 | 44.6% |
| LOAD_FAST | 1,188,688 | 33.8% |
| RETURN_VALUE | 510,835 | 14.5% |
| LOAD_ATTR_PROPERTY | 64,375 | 1.8% |
| BINARY_SUBSCR | 37,820 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,792,568 | 51.0% |
| JUMP_BACKWARD | 1,718,800 | 48.9% |
| LOAD_NAME | 4,800 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,346,999 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,347,879 | 99.9% |
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
| LOAD_FAST | 51,076,737 | 55.5% |
| LOAD_GLOBAL_MODULE | 33,547,870 | 36.5% |
| CALL_TYPE_1 | 2,352,310 | 2.6% |
| LOAD_ATTR_SLOT | 2,297,040 | 2.5% |
| LOAD_GLOBAL_BUILTIN | 1,905,183 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 34,992,341 | 38.0% |
| LOAD_FAST | 15,962,217 | 17.4% |
| IS_OP | 14,930,446 | 16.2% |
| PUSH_NULL | 8,385,135 | 9.1% |
| CONTAINS_OP | 3,188,620 | 3.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,544,938 | 33.9% |
| LOAD_CONST | 40,205,013 | 22.5% |
| RESUME_CHECK | 15,734,609 | 8.8% |
| BUILD_TUPLE | 10,372,813 | 5.8% |
| RETURN_CONST | 9,526,680 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,205,013 | 22.5% |
| CALL_BUILTIN_FAST | 24,046,959 | 13.4% |
| COMPARE_OP_INT | 20,732,521 | 11.6% |
| STORE_FAST | 14,268,378 | 8.0% |
| MAKE_FUNCTION | 12,370,972 | 6.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20,770,526 | 33.3% |
| NOP | 10,424,109 | 16.7% |
| LOAD_ATTR_SLOT | 6,404,091 | 10.3% |
| POP_JUMP_IF_FALSE | 4,644,647 | 7.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,054 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 20,940,986 | 33.6% |
| PUSH_NULL | 11,886,494 | 19.1% |
| LOAD_FAST | 9,394,897 | 15.1% |
| BINARY_SUBSCR | 6,404,091 | 10.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 5.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,706,062 | 17.8% |
| LOAD_GLOBAL_BUILTIN | 156,050,369 | 17.4% |
| RESUME_CHECK | 115,520,905 | 12.9% |
| POP_JUMP_IF_FALSE | 108,540,778 | 12.1% |
| STORE_FAST_STORE_FAST | 40,963,455 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,131,194 | 10.5% |
| LOAD_ATTR_METHOD_NO_DICT | 76,802,034 | 8.5% |
| LOAD_CONST | 60,544,938 | 6.7% |
| LOAD_GLOBAL_MODULE | 58,158,962 | 6.5% |
| RETURN_VALUE | 52,910,129 | 5.9% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,198,174 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,873 | 45.2% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,198,094 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,873 | 45.2% |
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
| STORE_FAST | 50,446,797 | 22.1% |
| POP_JUMP_IF_FALSE | 31,277,905 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 28,702,130 | 12.6% |
| RESUME_CHECK | 18,747,594 | 8.2% |
| STORE_FAST_STORE_FAST | 15,653,167 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 26,347,993 | 11.5% |
| COMPARE_OP | 21,088,619 | 9.2% |
| BUILD_TUPLE | 19,059,470 | 8.3% |
| STORE_SUBSCR_LIST_INT | 18,843,203 | 8.2% |
| CALL_BUILTIN_FAST | 17,262,229 | 7.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,181 | 19.4% |
| LOAD_FAST | 34,156 | 18.8% |
| STORE_FAST | 26,880 | 14.8% |
| RESUME_CHECK | 10,915 | 6.0% |
| RESUME | 10,756 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,424 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,231 | 22.7% |
| LOAD_FAST | 39,509 | 21.8% |
| LOAD_ATTR | 14,056 | 7.7% |
| CALL | 9,816 | 5.4% |


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
| LOAD_FAST | 1,080 | 90.0% |
| LOAD_DEREF | 120 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 500 | 41.7% |
| CALL | 320 | 26.7% |
| LOAD_FAST | 180 | 15.0% |
| PUSH_NULL | 100 | 8.3% |
| LOAD_SUPER_ATTR_ATTR | 100 | 8.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,274,752 | 37.6% |
| CACHE | 1,509,094 | 24.9% |
| CALL_PY_EXACT_ARGS | 770,450 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,402 | 10.8% |
| CALL | 523,697 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,770,991 | 62.3% |
| MAKE_CELL | 2,274,752 | 37.6% |
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
| TO_BOOL_BOOL | 108,770,908 | 41.4% |
| COMPARE_OP_INT | 33,153,817 | 12.6% |
| IS_OP | 29,996,352 | 11.4% |
| COMPARE_OP | 19,488,809 | 7.4% |
| CONTAINS_OP | 16,112,097 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,540,778 | 41.3% |
| LOAD_GLOBAL_BUILTIN | 57,855,777 | 22.0% |
| LOAD_FAST_LOAD_FAST | 31,277,905 | 11.9% |
| RETURN_CONST | 28,738,800 | 10.9% |
| ENTER_EXECUTOR | 13,543,759 | 5.2% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,025,073 | 81.5% |
| BINARY_SUBSCR | 6,399,864 | 15.8% |
| LOAD_DEREF | 1,088,836 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |
| EXTENDED_ARG | 5,437 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,900,632 | 51.6% |
| LOAD_FAST_LOAD_FAST | 14,261,438 | 35.2% |
| LOAD_FAST | 2,492,532 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 1,438,164 | 3.5% |
| LOAD_CONST | 1,111,408 | 2.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,606,260 | 92.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,224,982 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,227,059 | 67.7% |
| LOAD_FAST_LOAD_FAST | 1,938,865 | 10.7% |
| LOAD_GLOBAL_MODULE | 1,878,685 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,240 | 7.7% |
| ENTER_EXECUTOR | 441,592 | 2.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 54,148,980 | 72.5% |
| TO_BOOL_INT | 8,688,018 | 11.6% |
| CONTAINS_OP | 2,870,798 | 3.8% |
| IS_OP | 2,641,647 | 3.5% |
| COMPARE_OP | 2,277,993 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,028,833 | 48.2% |
| JUMP_BACKWARD | 16,080,760 | 21.5% |
| LOAD_GLOBAL_BUILTIN | 5,255,037 | 7.0% |
| NOP | 4,183,900 | 5.6% |
| BUILD_LIST | 4,083,240 | 5.5% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,926 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,266 | 98.4% |
| COPY | 1,760 | 1.5% |
| LOAD_CONST | 160 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 28,738,800 | 50.8% |
| RESUME_CHECK | 10,045,458 | 17.8% |
| FOR_ITER_LIST | 5,671,965 | 10.0% |
| FOR_ITER | 4,699,396 | 8.3% |
| STORE_SUBSCR | 3,200,253 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,284,810 | 57.1% |
| LOAD_CONST | 9,526,680 | 16.8% |
| POP_TOP | 9,362,861 | 16.5% |
| TO_BOOL_BOOL | 2,827,104 | 5.0% |
| STORE_FAST | 1,541,104 | 2.7% |


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
| MAKE_FUNCTION | 10,353,621 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,802,486 | 94.7% |
| STORE_FAST | 298,257 | 2.9% |
| STORE_DEREF | 95,650 | 0.9% |
| LOAD_CONST | 52,360 | 0.5% |
| LOAD_GLOBAL_MODULE | 42,944 | 0.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,847 | 82.3% |
| LOAD_FAST | 98,460 | 16.6% |
| STORE_ATTR | 3,900 | 0.7% |
| SWAP | 2,151 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,661 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,266 | 19.7% |
| LOAD_FAST | 89,971 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,577,880 | 46.5% |
| IMPORT_FROM | 2,092,434 | 27.2% |
| LOAD_ATTR | 1,558,824 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,650 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,840 | 46.5% |
| POP_TOP | 1,906,737 | 24.8% |
| LOAD_DEREF | 1,298,321 | 16.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.3% |
| IMPORT_FROM | 185,697 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,553,993 | 13.1% |
| LOAD_ATTR | 34,992,341 | 11.8% |
| BINARY_OP | 24,166,211 | 8.2% |
| LOAD_ATTR_SLOT | 22,510,049 | 7.6% |
| LOAD_CONST | 14,268,378 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,706,062 | 54.1% |
| LOAD_FAST_LOAD_FAST | 50,446,797 | 17.1% |
| LOAD_GLOBAL_BUILTIN | 32,307,675 | 10.9% |
| LOAD_GLOBAL_MODULE | 11,273,302 | 3.8% |
| STORE_FAST | 9,345,047 | 3.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,332 | 69.6% |
| FOR_ITER_TUPLE | 409,109 | 22.6% |
| FOR_ITER | 92,960 | 5.1% |
| FOR_ITER_RANGE | 47,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,221,296 | 67.5% |
| LOAD_ATTR_PROPERTY | 202,644 | 11.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 186,437 | 10.3% |
| LOAD_DEREF | 51,440 | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,840 | 2.5% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 96,727,441 | 93.5% |
| RETURN_VALUE | 3,248,189 | 3.1% |
| UNPACK_SEQUENCE_TUPLE | 1,397,339 | 1.4% |
| STORE_FAST_STORE_FAST | 771,899 | 0.7% |
| BUILD_LIST | 413,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,963,455 | 39.6% |
| LOAD_GLOBAL_BUILTIN | 22,003,144 | 21.3% |
| LOAD_DEREF | 20,770,526 | 20.1% |
| LOAD_FAST_LOAD_FAST | 15,653,167 | 15.1% |
| LOAD_GLOBAL_MODULE | 1,958,120 | 1.9% |


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
| BINARY_SUBSCR_LIST_INT | 9,393,133 | 20.9% |
| LOAD_FAST_AND_CLEAR | 9,198,094 | 20.4% |
| FOR_ITER | 7,602,844 | 16.9% |
| BUILD_MAP | 4,716,104 | 10.5% |
| LOAD_FAST | 4,641,369 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,393,353 | 20.9% |
| STORE_FAST | 7,930,977 | 17.6% |
| FOR_ITER | 7,638,524 | 17.0% |
| POP_TOP | 5,778,549 | 12.8% |
| BUILD_MAP | 4,716,104 | 10.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,420 | 26.2% |
| FOR_ITER | 6,800 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 16.0% |
| LOAD_FAST | 3,949 | 9.9% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,640 | 47.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,420 | 23.7% |
| STORE_FAST | 8,120 | 20.5% |
| UNPACK_SEQUENCE_TUPLE | 1,120 | 2.8% |
| UNPACK_SEQUENCE | 916 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,661,771 | 55.2% |
| ENTER_EXECUTOR | 4,755,896 | 20.7% |
| CALL_ISINSTANCE | 2,335,033 | 10.2% |
| LOAD_FAST | 1,146,790 | 5.0% |
| YIELD_VALUE | 677,464 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,079,317 | 96.3% |
| YIELD_VALUE | 677,464 | 3.0% |
| STORE_FAST | 162,777 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,056 | 38.0% |
| CALL | 11,080 | 23.3% |
| CALL_PY_EXACT_ARGS | 6,086 | 12.8% |
| POP_TOP | 3,960 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,674 | 37.2% |
| LOAD_GLOBAL | 10,756 | 22.6% |
| LOAD_CONST | 8,759 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,360 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,594,495 | 69.3% |
| LOAD_FAST_LOAD_FAST | 574,201 | 15.3% |
| BINARY_SUBSCR_DICT | 420,640 | 11.2% |
| CALL_BUILTIN_CLASS | 81,217 | 2.2% |
| LOAD_FAST | 43,680 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,536,652 | 41.1% |
| SWAP | 942,331 | 25.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 539,839 | 14.4% |
| LOAD_CONST | 269,134 | 7.2% |
| LOAD_FAST | 201,594 | 5.4% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 479,440 | 86.9% |
| CALL_METHOD_DESCRIPTOR_O | 39,600 | 7.2% |
| LOAD_FAST | 15,880 | 2.9% |
| LOAD_FAST_LOAD_FAST | 8,400 | 1.5% |
| BINARY_SUBSCR_LIST_INT | 3,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 498,440 | 90.4% |
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
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,675 | 60.5% |
| LOAD_ATTR_SLOT | 723,522 | 26.2% |
| LOAD_FAST_LOAD_FAST | 269,837 | 9.8% |
| LOAD_FAST | 94,240 | 3.4% |
| BINARY_OP | 1,380 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,860 | 83.1% |
| LOAD_FAST_LOAD_FAST | 181,160 | 6.6% |
| STORE_FAST | 175,597 | 6.4% |
| LOAD_FAST | 76,500 | 2.8% |
| LOAD_GLOBAL_MODULE | 25,177 | 0.9% |


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
| LOAD_CONST | 1,556,329 | 62.9% |
| LOAD_FAST_LOAD_FAST | 607,304 | 24.6% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,673 | 5.0% |
| BINARY_OP | 2,160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,080,100 | 43.7% |
| STORE_FAST | 700,148 | 28.3% |
| BINARY_OP | 311,685 | 12.6% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,880 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,036,237 | 32.7% |
| LOAD_FAST_LOAD_FAST | 923,347 | 29.2% |
| LOAD_CONST | 642,800 | 20.3% |
| CALL_TUPLE_1 | 441,520 | 13.9% |
| RETURN_VALUE | 114,604 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 866,341 | 27.4% |
| RETURN_VALUE | 809,334 | 25.6% |
| BINARY_OP_ADD_INT | 420,640 | 13.3% |
| PUSH_NULL | 376,980 | 11.9% |
| SWAP | 318,100 | 10.0% |


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
| MAKE_CELL | 159,246 | 100.0% |
| RETURN_VALUE | 3 | 0.0% |
| LOAD_CONST | 3 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,347,993 | 90.9% |
| COPY | 1,063,080 | 3.7% |
| LOAD_CONST | 1,026,685 | 3.5% |
| CALL_BUILTIN_CLASS | 282,605 | 1.0% |
| LOAD_FAST | 204,206 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,401,493 | 32.4% |
| SWAP | 9,393,133 | 32.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,520,687 | 25.9% |
| LOAD_CONST | 1,063,540 | 3.7% |
| RETURN_VALUE | 432,298 | 1.5% |


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
| LOAD_CONST | 8,718,852 | 97.0% |
| LOAD_FAST | 263,365 | 2.9% |
| BINARY_SUBSCR | 2,720 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,357 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 322,070 | 3.6% |
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
| LOAD_FAST | 13,129,611 | 91.3% |
| BINARY_OP_ADD_INT | 539,839 | 3.8% |
| LOAD_FAST_LOAD_FAST | 480,406 | 3.3% |
| LOAD_ATTR | 152,040 | 1.1% |
| RETURN_VALUE | 36,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,525,142 | 87.1% |
| COPY_FREE_VARS | 1,196,584 | 8.3% |
| MAKE_CELL | 654,402 | 4.5% |
| POP_TOP | 7,360 | 0.1% |
| RESUME | 620 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,796,662 | 32.8% |
| CALL_BUILTIN_CLASS | 1,959,151 | 22.9% |
| LOAD_CONST | 710,920 | 8.3% |
| CALL_LEN | 610,878 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 568,481 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,979,817 | 34.9% |
| CALL_BUILTIN_CLASS | 1,959,151 | 22.9% |
| GET_ITER | 1,728,221 | 20.2% |
| CALL | 284,474 | 3.3% |
| BINARY_SUBSCR_LIST_INT | 282,605 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,046,959 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,262,229 | 39.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,202 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 55,472 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,000,919 | 41.8% |
| STORE_FAST | 10,914,222 | 25.4% |
| TO_BOOL | 10,287,220 | 23.9% |
| PUSH_NULL | 2,128,620 | 4.9% |
| RETURN_VALUE | 1,500,104 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,804 | 94.4% |
| LOAD_FAST | 135,132 | 2.6% |
| BINARY_OP | 119,157 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,084 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 128,032 | 2.5% |
| CALL_BUILTIN_CLASS | 119,157 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,700,436 | 41.7% |
| RETURN_GENERATOR | 10,180,108 | 27.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,615,549 | 14.9% |
| LOAD_ATTR_SLOT | 4,877,031 | 13.0% |
| BINARY_OP | 1,095,121 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,584,139 | 36.1% |
| RETURN_VALUE | 11,432,657 | 30.4% |
| TO_BOOL_BOOL | 9,857,911 | 26.2% |
| GET_ITER | 2,591,100 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,787,353 | 57.2% |
| LOAD_GLOBAL_BUILTIN | 18,938,702 | 30.3% |
| LOAD_DEREF | 3,017,911 | 4.8% |
| LOAD_FAST_LOAD_FAST | 2,763,474 | 4.4% |
| LOAD_FAST | 1,614,924 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,534,756 | 95.2% |
| YIELD_VALUE | 2,335,033 | 3.7% |
| COPY | 525,020 | 0.8% |
| RETURN_VALUE | 127,533 | 0.2% |
| TO_BOOL | 9,659 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,053,130 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 173,720 | 0.6% |
| RETURN_VALUE | 95,052 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,270,194 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,675,910 | 34.5% |
| LOAD_CONST | 7,178,820 | 25.6% |
| CALL_BUILTIN_CLASS | 610,878 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,555,402 | 64.8% |
| BUILD_TUPLE | 3,216,080 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 960,680 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,102,333 | 62.9% |
| EXTENDED_ARG | 4,571,169 | 19.0% |
| JUMP_BACKWARD | 2,241,889 | 9.3% |
| LOAD_FAST | 1,681,756 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,002,104 | 68.6% |
| LOAD_CONST | 2,388,523 | 10.9% |
| BUILD_LIST | 2,294,380 | 10.5% |
| BUILD_MAP | 1,561,360 | 7.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 269,521 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,708,411 | 58.1% |
| STORE_FAST | 3,415,443 | 15.6% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.3% |
| POP_TOP | 908,813 | 4.2% |
| GET_ITER | 737,580 | 3.4% |


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
| LOAD_ATTR_METHOD_NO_DICT | 24,469,402 | 83.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,644 | 16.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,789 | 0.4% |
| LOAD_ATTR | 72,820 | 0.2% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,416,888 | 48.9% |
| STORE_FAST | 9,683,892 | 32.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,804 | 16.6% |
| CALL_BUILTIN_CLASS | 169,731 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,789 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.2% |
| LOAD_CONST | 1,226,482 | 26.7% |
| LOAD_FAST | 296,920 | 6.5% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.5% |
| LOAD_CONST | 1,224,482 | 26.7% |
| TO_BOOL_NONE | 48,400 | 1.1% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,792,283 | 31.3% |
| LOAD_FAST | 15,662,038 | 23.6% |
| GET_ITER | 12,990,251 | 19.6% |
| LOAD_FAST_LOAD_FAST | 12,371,656 | 18.6% |
| LOAD_SUPER_ATTR_METHOD | 1,539,345 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 49,535,321 | 74.6% |
| COPY_FREE_VARS | 11,794,108 | 17.8% |
| RETURN_GENERATOR | 4,117,091 | 6.2% |
| MAKE_CELL | 770,450 | 1.2% |
| CALL_PY_EXACT_ARGS | 145,235 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,622,051 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,373,890 | 29.9% |
| ENTER_EXECUTOR | 1,014,374 | 22.1% |
| RETURN_VALUE | 192,677 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,994 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,373,372 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,733 | 1.2% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,084 | 80.5% |
| LOAD_FAST | 1,014,997 | 17.4% |
| STORE_FAST | 105,764 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,144 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,284 | 80.5% |
| BINARY_SUBSCR_DICT | 441,520 | 7.5% |
| STORE_FAST | 353,204 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,728,875 | 99.2% |
| LOAD_CONST | 119,986 | 0.8% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,624 | 43.3% |
| COMPARE_OP | 5,882,502 | 39.6% |
| LOAD_ATTR | 2,352,310 | 15.8% |
| IS_OP | 64,246 | 0.4% |
| BUILD_TUPLE | 55,800 | 0.4% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,657 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,584 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,021 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,732,521 | 42.5% |
| LOAD_FAST_LOAD_FAST | 16,178,718 | 33.2% |
| CALL_LEN | 10,270,194 | 21.1% |
| LOAD_FAST | 1,013,637 | 2.1% |
| LOAD_ATTR_SLOT | 225,301 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,153,817 | 68.0% |
| BINARY_OP | 6,304,740 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.7% |
| EXTENDED_ARG | 1,719,897 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,566,000 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 69.1% |
| LOAD_CONST | 4,296,431 | 29.6% |
| LOAD_GLOBAL_MODULE | 192,578 | 1.3% |
| LOAD_FAST | 2,040 | 0.0% |
| LOAD_ATTR | 1,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,481,097 | 99.7% |
| YIELD_VALUE | 40,172 | 0.3% |
| POP_JUMP_IF_TRUE | 2,080 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,496 | 52.6% |
| GET_ITER | 90,640 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,576 | 52.1% |
| POP_TOP | 90,480 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,638,631 | 42.2% |
| LOAD_FAST | 4,844,085 | 21.2% |
| GET_ITER | 4,369,744 | 19.1% |
| EXTENDED_ARG | 2,686,841 | 11.8% |
| SWAP | 1,221,425 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,054,543 | 39.7% |
| RETURN_CONST | 5,671,965 | 24.8% |
| LOAD_FAST | 4,094,180 | 17.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,806,831 | 7.9% |
| STORE_FAST_LOAD_FAST | 1,260,332 | 5.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 827,176 | 37.2% |
| GET_ITER | 668,935 | 30.1% |
| EXTENDED_ARG | 642,400 | 28.9% |
| SWAP | 38,880 | 1.7% |
| LOAD_FAST | 29,360 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,610 | 58.7% |
| RETURN_CONST | 630,098 | 28.3% |
| LOAD_FAST | 195,180 | 8.8% |
| STORE_FAST_LOAD_FAST | 47,440 | 2.1% |
| SWAP | 38,520 | 1.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,903,372 | 47.4% |
| ENTER_EXECUTOR | 9,320,171 | 44.6% |
| EXTENDED_ARG | 767,880 | 3.7% |
| LOAD_FAST | 518,335 | 2.5% |
| SWAP | 299,345 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,208,495 | 48.8% |
| LOAD_FAST | 7,494,821 | 35.8% |
| RETURN_CONST | 788,666 | 3.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 671,292 | 3.2% |
| LOAD_GLOBAL_MODULE | 602,512 | 2.9% |


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
| LOAD_FAST | 5,478,794 | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,847 | 11.7% |
| LOAD_DEREF | 1,058,307 | 11.7% |
| COPY | 956,400 | 10.6% |
| LOAD_GLOBAL_MODULE | 481,451 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,422 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,202 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,224,982 | 13.5% |
| STORE_FAST | 1,076,007 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,847 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,802,034 | 85.8% |
| RETURN_VALUE | 4,635,856 | 5.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.5% |
| LOAD_GLOBAL_MODULE | 1,964,960 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,422 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,794,957 | 34.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,469,402 | 27.3% |
| CALL_PY_EXACT_ARGS | 20,792,283 | 23.2% |
| LOAD_CONST | 4,051,450 | 4.5% |
| LOAD_DEREF | 3,319,054 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 20,940,986 | 71.2% |
| LOAD_ATTR_SLOT | 4,711,184 | 16.0% |
| LOAD_FAST | 3,529,599 | 12.0% |
| LOAD_ATTR | 147,504 | 0.5% |
| STORE_FAST_LOAD_FAST | 45,840 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,932,847 | 50.8% |
| LOAD_FAST_LOAD_FAST | 9,329,203 | 31.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,644 | 16.3% |
| CALL_PY_EXACT_ARGS | 320,394 | 1.1% |
| LOAD_CONST | 6,575 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,261,144 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,399 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,486 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,718 | 6.3% |
| CALL | 57,379 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR_SLOT | 15,920 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,515,231 | 87.2% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| ENTER_EXECUTOR | 2,966,352 | 5.2% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 215,813 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,303,574 | 74.5% |
| CALL_BUILTIN_O | 5,615,549 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,921,203 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,675 | 2.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 991,809 | 60.3% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.1% |
| LOAD_DEREF | 144,340 | 8.8% |
| LOAD_ATTR | 12,020 | 0.7% |
| ENTER_EXECUTOR | 10,731 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.1% |
| TO_BOOL_STR | 478,200 | 29.1% |
| TO_BOOL_BOOL | 410,745 | 25.0% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,299,999 | 90.4% |
| ENTER_EXECUTOR | 1,314,083 | 4.7% |
| RETURN_VALUE | 642,494 | 2.3% |
| STORE_FAST_LOAD_FAST | 202,644 | 0.7% |
| LOAD_DEREF | 190,732 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,813,348 | 67.2% |
| COPY_FREE_VARS | 5,066,540 | 18.1% |
| GET_ITER | 1,920,053 | 6.9% |
| TO_BOOL_BOOL | 711,397 | 2.5% |
| STORE_FAST | 505,010 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,131,194 | 98.6% |
| LOAD_ATTR_SLOT | 613,600 | 0.6% |
| ENTER_EXECUTOR | 555,100 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,051 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 69,965 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,432,308 | 35.0% |
| STORE_FAST | 22,510,049 | 23.6% |
| LOAD_DEREF | 6,404,091 | 6.7% |
| LOAD_FAST | 5,219,996 | 5.5% |
| LOAD_CONST | 5,210,048 | 5.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,855,777 | 25.6% |
| RESUME_CHECK | 41,255,534 | 18.3% |
| STORE_FAST | 32,307,675 | 14.3% |
| STORE_FAST_STORE_FAST | 22,003,144 | 9.7% |
| LOAD_FAST | 20,354,578 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 156,050,369 | 69.1% |
| LOAD_FAST_LOAD_FAST | 28,702,130 | 12.7% |
| CALL_ISINSTANCE | 18,938,702 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 8,972,465 | 4.0% |
| LOAD_DEREF | 3,220,815 | 1.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,158,962 | 49.4% |
| RESUME_CHECK | 16,027,562 | 13.6% |
| STORE_FAST | 11,273,302 | 9.6% |
| POP_JUMP_IF_FALSE | 9,673,878 | 8.2% |
| NOP | 6,377,775 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 35,787,353 | 30.4% |
| LOAD_ATTR | 33,547,870 | 28.5% |
| LOAD_FAST | 29,321,049 | 24.9% |
| LOAD_FAST_LOAD_FAST | 3,279,353 | 2.8% |
| LOAD_DEREF | 3,256,211 | 2.8% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,538 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,181,938 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,580 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,345 | 85.1% |
| LOAD_GLOBAL_MODULE | 172,235 | 9.5% |
| LOAD_FAST | 78,580 | 4.3% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 99,067,715 | 38.6% |
| CALL_PY_EXACT_ARGS | 49,535,321 | 19.3% |
| COPY_FREE_VARS | 21,776,765 | 8.5% |
| LOAD_ATTR_PROPERTY | 18,813,348 | 7.3% |
| POP_TOP | 14,313,901 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,520,905 | 45.0% |
| LOAD_GLOBAL_BUILTIN | 41,255,534 | 16.1% |
| NOP | 21,363,645 | 8.3% |
| LOAD_FAST_LOAD_FAST | 18,747,594 | 7.3% |
| LOAD_GLOBAL_MODULE | 16,027,562 | 6.2% |


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
| LOAD_FAST | 2,103,707 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,131 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,677 | 36.0% |
| RETURN_CONST | 887,366 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,381 | 52.2% |
| LOAD_FAST | 4,285,101 | 47.3% |
| STORE_ATTR_SLOT | 41,766 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,673,161 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,371 | 24.9% |
| LOAD_CONST | 1,890,746 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,844 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,570,451 | 68.9% |
| LOAD_FAST | 396,964 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,331 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,652,380 | 72.5% |
| EXTENDED_ARG | 226,724 | 9.9% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.0% |
| LOAD_FAST | 164,820 | 7.2% |
| LOAD_GLOBAL_MODULE | 38,951 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,843,203 | 93.3% |
| SWAP | 1,063,080 | 5.3% |
| BINARY_SUBSCR_DICT | 112,800 | 0.6% |
| LOAD_FAST | 99,416 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,015,873 | 49.6% |
| ENTER_EXECUTOR | 9,859,093 | 48.8% |
| JUMP_BACKWARD | 250,233 | 1.2% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,440 | 98.7% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| ENTER_EXECUTOR | 480 | 0.2% |
| TO_BOOL | 387 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 217,400 | 95.1% |
| POP_JUMP_IF_FALSE | 9,618 | 4.2% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 49 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 59,534,756 | 35.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,303,574 | 25.0% |
| LOAD_FAST | 21,602,138 | 12.8% |
| CALL_BUILTIN_FAST | 18,000,919 | 10.6% |
| CALL_BUILTIN_O | 9,857,911 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 108,770,908 | 64.3% |
| POP_JUMP_IF_TRUE | 54,148,980 | 32.0% |
| EXTENDED_ARG | 5,063,524 | 3.0% |
| UNARY_NOT | 1,084,940 | 0.6% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,162,479 | 95.4% |
| BINARY_OP | 722,629 | 3.8% |
| BINARY_SUBSCR_TUPLE_INT | 63,353 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,280 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,857 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,350,940 | 54.4% |
| POP_JUMP_IF_TRUE | 8,688,018 | 45.6% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 160 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,229,151 | 97.5% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,113 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |
| TO_BOOL | 2,140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 824,216 | 36.0% |
| POP_JUMP_IF_TRUE | 784,508 | 34.3% |
| UNARY_NOT | 661,860 | 28.9% |
| EXTENDED_ARG | 15,720 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,722 | 69.4% |
| RETURN_VALUE | 389,182 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,322 | 11.1% |
| CALL_METHOD_DESCRIPTOR_O | 48,400 | 1.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,930 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,944,298 | 73.3% |
| POP_JUMP_IF_TRUE | 689,988 | 26.0% |
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
| LOAD_FAST | 120,300 | 67.4% |
| RETURN_VALUE | 49,120 | 27.5% |
| CALL_BUILTIN_CLASS | 2,600 | 1.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 1.0% |
| BINARY_SUBSCR_LIST_INT | 1,240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 64.4% |
| STORE_FAST_STORE_FAST | 63,620 | 35.6% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 885,416 | 55.6% |
| RETURN_VALUE | 660,880 | 41.5% |
| STORE_FAST | 40,240 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,397,339 | 87.8% |
| STORE_FAST | 154,817 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 70,851,289 | 70.5% |
| RETURN_VALUE | 19,465,504 | 19.4% |
| BINARY_SUBSCR_LIST_INT | 7,520,687 | 7.5% |
| FOR_ITER_LIST | 1,806,831 | 1.8% |
| FOR_ITER_TUPLE | 671,292 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 96,727,441 | 96.2% |
| STORE_DEREF | 3,577,880 | 3.6% |
| STORE_FAST | 218,419 | 0.2% |
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
|     deferred | 35,156,384 | 78.6% |
|          hit | 9,529,074 | 21.3% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,660 | 11.6% |
| Failure | 50,784 | 88.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,457 | 18.6% |
| multiply different types | 7,300 | 14.4% |
| subtract other | 6,780 | 13.4% |
| and int | 4,126 | 8.1% |
| rshift | 3,804 | 7.5% |
| or | 3,700 | 7.3% |
| power | 2,840 | 5.6% |
| true divide different types | 2,519 | 5.0% |
| multiply other | 2,360 | 4.6% |
| remainder | 2,152 | 4.2% |
| add different types | 1,820 | 3.6% |
| floor divide | 1,260 | 2.5% |
| subtract different types | 1,190 | 2.3% |
| xor | 580 | 1.1% |
| and other | 376 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 220 | 0.4% |


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
|     deferred | 22,211,874 | 35.0% |
|          hit | 41,300,315 | 65.0% |
|         miss | 14,924 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,700 | 33.5% |
| Failure | 15,303 | 66.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 11,923 | 77.9% |
| out of range | 1,960 | 12.8% |
| buffer int | 1,400 | 9.1% |
| array int | 20 | 0.1% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,126,867 | 6.3% |
|        deopt | 22,840 | 0.0% |
|          hit | 354,639,941 | 85.9% |
|         miss | 31,316,939 | 7.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 671,241 | 90.2% |
| Failure | 72,715 | 9.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,476 | 39.2% |
| code complex parameters | 14,044 | 19.3% |
| class no vectorcall | 9,220 | 12.7% |
| cfunc varargs keywords | 6,380 | 8.8% |
| other | 3,039 | 4.2% |
| wrong number arguments | 2,520 | 3.5% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,160 | 3.0% |
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
|     deferred | 37,836,664 | 37.2% |
|          hit | 63,221,815 | 62.2% |
|         miss | 575,942 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,449 | 22.8% |
| Failure | 69,119 | 77.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,415 | 26.6% |
| other | 15,244 | 22.1% |
| different types | 12,233 | 17.7% |
| tuple | 10,056 | 14.5% |
| string | 9,960 | 14.4% |
| bool | 2,011 | 2.9% |
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
|     deferred | 103,475,496 | 69.1% |
|          hit | 44,903,121 | 30.0% |
|         miss | 1,255,353 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 35,537 | 26.3% |
| Failure | 99,539 | 73.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 71,390 | 71.7% |
| set | 8,998 | 9.0% |
| zip | 7,600 | 7.6% |
| enumerate | 4,231 | 4.3% |
| other | 2,720 | 2.7% |
| itertools | 1,940 | 1.9% |
| dict keys | 1,640 | 1.6% |
| reversed list | 860 | 0.9% |
| dict values | 80 | 0.1% |
| ascii string | 80 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 90,517,570 | 22.4% |
|        deopt | 20 | 0.0% |
|          hit | 245,475,792 | 60.9% |
|         miss | 65,926,997 | 16.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,321,603 | 89.7% |
| Failure | 151,753 | 10.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mutable class | 58,652 | 38.6% |
| metaclass attribute | 53,193 | 35.1% |
| method | 10,401 | 6.9% |
| overridden | 8,668 | 5.7% |
| has managed dict | 8,600 | 5.7% |
| shadowed | 5,300 | 3.5% |
| class method obj | 3,899 | 2.6% |
| builtin class method | 1,320 | 0.9% |
| not managed dict | 740 | 0.5% |
| non object slot | 560 | 0.4% |
| not in keys | 300 | 0.2% |
| non overriding descriptor | 60 | 0.0% |
| module attr not found | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 89,677 | 0.0% |
|          hit | 343,659,467 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,815 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 600 | 0.0% |
|          hit | 2,990,018 | 100.0% |

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
|     deferred | 540,632 | 4.2% |
|          hit | 10,198,335 | 78.4% |
|         miss | 2,220,811 | 17.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,826 | 92.3% |
| Failure | 3,900 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,960 | 50.3% |
| not managed dict | 1,440 | 36.9% |
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
|     deferred | 3,295,893 | 12.8% |
|          hit | 22,468,145 | 87.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,720 | 43.5% |
| Failure | 3,537 | 56.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 3,537 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,814,339 | 6.2% |
|          hit | 193,340,824 | 93.5% |
|         miss | 439,883 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,867 | 72.3% |
| Failure | 22,919 | 27.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,773 | 47.0% |
| number | 3,488 | 15.2% |
| mapping | 3,300 | 14.4% |
| dict | 2,260 | 9.9% |
| other | 1,629 | 7.1% |
| set | 1,429 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,560 | 0.0% |
|          hit | 102,300,616 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,360 | 93.6% |
| Failure | 776 | 6.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 716 | 92.3% |
| iterator | 60 | 7.7% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 2,914,313,487 | 53.7% |
| Not specialized | 731,667,221 | 13.5% |
| Specialized hits | 1,677,304,006 | 30.9% |
| Specialized misses | 101,802,089 | 1.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER | 103,475,496 | 31.1% |
| LOAD_ATTR | 90,517,570 | 27.2% |
| COMPARE_OP | 37,836,664 | 11.4% |
| BINARY_OP | 35,156,384 | 10.6% |
| CALL | 26,126,867 | 7.9% |
| BINARY_SUBSCR | 22,211,874 | 6.7% |
| TO_BOOL | 12,814,339 | 3.9% |
| STORE_SUBSCR | 3,295,893 | 1.0% |
| STORE_ATTR | 540,632 | 0.2% |
| SEND | 439,140 | 0.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,443,632 | 35.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,765,423 | 15.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,291,821 | 14.0% |
| LOAD_ATTR_METHOD_NO_DICT | 9,123,333 | 9.0% |
| CALL_PY_EXACT_ARGS | 7,809,177 | 7.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,393 | 6.4% |
| LOAD_ATTR_PROPERTY | 4,106,338 | 4.0% |
| CALL_BUILTIN_O | 2,661,144 | 2.6% |
| STORE_ATTR_SLOT | 2,219,831 | 2.2% |
| FOR_ITER_TUPLE | 769,663 | 0.8% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,471,660 | 48.8% |
| Calls to Python functions inlined | 133,980,799 | 51.2% |
| Calls via PyEval_EvalFrame (total) | 127,471,660 | 48.8% |
| Calls via PyEval_EvalFrame (vector) | 98,448,914 | 37.7% |
| Calls via PyEval_EvalFrame (generator) | 29,022,746 | 11.1% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,441,614 | 37.7% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,158 | 9.1% |
| Calls via PyEval_EvalFrame (function ex) | 11,824,962 | 4.5% |
| Calls via PyEval_EvalFrame (api) | 53,321,763 | 20.4% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,067 | 0.5% |
| Frames pushed | 112,541,456 | 43.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,379,192 | 54.3% |
| Frees to freelist | 363,622,101 |  |
| Allocations | 305,514,747 | 45.7% |
| Allocations to 512 bytes | 304,456,067 | 45.5% |
| Allocations to 4 kbytes | 1,034,220 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,190,540 |  |
| New values | 1,057,409 |  |
| Interpreter increfs | 2,630,043,963 | 64.8% |
| Interpreter decrefs | 3,054,627,716 | 65.8% |
| Increfs | 1,429,328,359 | 35.2% |
| Decrefs | 1,585,394,200 | 34.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,844,676 |  |
| Method cache misses | 4,172,893 |  |
| Method cache collisions | 5,842,922 |  |
| Method cache dunder hits | 346,752,709 |  |
| Method cache dunder misses | 1,670,641 |  |


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
| Optimization attempts | 56,072 |  |
| Traces created | 10,021 | 17.9% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 192 | 0.3% |
| Trace too long | 0 | 0.0% |
| Trace too short | 46,051 | 82.1% |
| Inner loop found | 80 | 0.1% |
| Recursive call | 160 | 0.3% |
| Traces executed | 61,868,064 |  |
| Uops executed | 1,157,526,957 | 18.71 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 2,534 | 25.3% |
| <= 32 | 3,755 | 37.5% |
| <= 64 | 2,654 | 26.5% |
| <= 128 | 703 | 7.0% |
| <= 256 | 375 | 3.7% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,514 | 25.1% |
| <= 16 | 3,286 | 32.8% |
| <= 32 | 2,681 | 26.8% |
| <= 64 | 1,245 | 12.4% |
| <= 128 | 255 | 2.5% |
| <= 256 | 40 | 0.4% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 2,713,519 | 4.4% |
| <= 2 | 14,772,170 | 23.9% |
| <= 4 | 737,716 | 1.2% |
| <= 8 | 4,466,614 | 7.2% |
| <= 16 | 13,193,792 | 21.3% |
| <= 32 | 21,001,620 | 33.9% |
| <= 64 | 1,729,400 | 2.8% |
| <= 128 | 2,256,148 | 3.6% |
| <= 256 | 954,656 | 1.5% |
| <= 512 | 41,577 | 0.1% |
| <= 1,024 | 332 | 0.0% |
| <= 2,048 | 20 | 0.0% |
| <= 4,096 | 40 | 0.0% |
| <= 8,192 | 360 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 100 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 144,521,040 | 12.5% | 12.5% |  |
| LOAD_FAST | 131,695,532 | 11.4% | 23.9% |  |
| _CHECK_VALIDITY | 121,055,696 | 10.5% | 34.3% |  |
| STORE_FAST | 71,634,546 | 6.2% | 40.5% |  |
| _ITER_CHECK_LIST | 51,568,922 | 4.5% | 45.0% | 3.2% |
| _GUARD_NOT_EXHAUSTED_LIST | 49,925,742 | 4.3% | 49.3% | 19.6% |
| _ITER_NEXT_LIST | 40,158,160 | 3.5% | 52.7% |  |
| _GUARD_GLOBALS_VERSION | 36,393,581 | 3.1% | 55.9% | 1.4% |
| CONTAINS_OP | 33,129,955 | 2.9% | 58.8% |  |
| _GUARD_IS_FALSE_POP | 31,776,099 | 2.7% | 61.5% | 13.2% |
| _LOAD_ATTR | 29,718,838 | 2.6% | 64.1% |  |
| _EXIT_TRACE | 28,295,678 | 2.4% | 66.5% |  |
| _LOAD_GLOBAL_MODULE | 27,934,176 | 2.4% | 68.9% |  |
| _JUMP_TO_TOP | 26,930,674 | 2.3% | 71.3% |  |
| _ITER_CHECK_TUPLE | 23,908,780 | 2.1% | 73.3% | 4.5% |
| _GUARD_NOT_EXHAUSTED_TUPLE | 22,838,441 | 2.0% | 75.3% | 39.0% |
| PUSH_NULL | 17,785,475 | 1.5% | 76.8% |  |
| _ITER_NEXT_TUPLE | 13,938,392 | 1.2% | 78.0% |  |
| LOAD_CONST | 13,238,289 | 1.1% | 79.2% |  |
| _GUARD_IS_TRUE_POP | 10,997,438 | 1.0% | 80.1% | 31.9% |
| _CHECK_FUNCTION_EXACT_ARGS | 10,822,307 | 0.9% | 81.1% | 0.4% |
| _CHECK_PEP_523 | 10,822,307 | 0.9% | 82.0% |  |
| _CHECK_STACK_SPACE | 10,783,467 | 0.9% | 82.9% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 10,780,798 | 0.9% | 83.9% |  |
| _PUSH_FRAME | 10,780,798 | 0.9% | 84.8% |  |
| _SAVE_RETURN_OFFSET | 10,780,798 | 0.9% | 85.7% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 10,730,476 | 0.9% | 86.6% | 7.7% |
| _ITER_CHECK_RANGE | 10,730,476 | 0.9% | 87.6% |  |
| _ITER_NEXT_RANGE | 9,903,300 | 0.9% | 88.4% |  |
| _GUARD_TYPE_VERSION | 9,275,174 | 0.8% | 89.2% | 32.1% |
| _GUARD_BOTH_INT | 9,258,740 | 0.8% | 90.0% |  |
| _BINARY_OP_ADD_INT | 9,231,680 | 0.8% | 90.8% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 9,156,227 | 0.8% | 91.6% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 9,156,227 | 0.8% | 92.4% |  |
| _GUARD_BUILTINS_VERSION | 7,959,220 | 0.7% | 93.1% |  |
| _LOAD_GLOBAL_BUILTINS | 7,959,220 | 0.7% | 93.8% |  |
| BUILD_TUPLE | 6,755,498 | 0.6% | 94.4% |  |
| BUILD_MAP | 6,581,548 | 0.6% | 94.9% |  |
| DICT_MERGE | 6,572,040 | 0.6% | 95.5% |  |
| LOAD_DEREF | 6,251,247 | 0.5% | 96.0% |  |
| CALL_ISINSTANCE | 4,920,506 | 0.4% | 96.5% |  |
| TO_BOOL_BOOL | 3,622,821 | 0.3% | 96.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,164,449 | 0.3% | 97.1% |  |
| LIST_APPEND | 2,671,841 | 0.2% | 97.3% |  |
| COMPARE_OP_INT | 2,436,457 | 0.2% | 97.5% |  |
| IS_OP | 2,317,985 | 0.2% | 97.7% |  |
| CALL_BUILTIN_O | 2,209,767 | 0.2% | 97.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 2,147,240 | 0.2% | 98.1% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,046,149 | 0.2% | 98.3% |  |
| MAKE_FUNCTION | 1,903,790 | 0.2% | 98.4% |  |
| CALL_TYPE_1 | 1,861,004 | 0.2% | 98.6% |  |
| _BINARY_SUBSCR | 1,769,960 | 0.2% | 98.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 1,462,517 | 0.1% | 98.9% |  |
| _GUARD_KEYS_VERSION | 1,462,517 | 0.1% | 99.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 1,462,517 | 0.1% | 99.1% |  |
| RESUME_CHECK | 1,215,752 | 0.1% | 99.2% |  |
| BINARY_SUBSCR_LIST_INT | 1,189,340 | 0.1% | 99.3% | 1.6% |
| STORE_DEREF | 992,892 | 0.1% | 99.4% |  |
| _GUARD_IS_NOT_NONE_POP | 758,405 | 0.1% | 99.5% | 0.1% |
| TO_BOOL_INT | 656,980 | 0.1% | 99.5% | 0.0% |
| _POP_FRAME | 642,992 | 0.1% | 99.6% |  |
| GET_ITER | 619,874 | 0.1% | 99.6% |  |
| CALL_BUILTIN_CLASS | 611,130 | 0.1% | 99.7% |  |
| _COMPARE_OP | 589,895 | 0.1% | 99.7% |  |
| _LOAD_ATTR_SLOT | 532,976 | 0.0% | 99.8% |  |
| COPY | 291,726 | 0.0% | 99.8% |  |
| SWAP | 290,240 | 0.0% | 99.8% |  |
| CALL_BUILTIN_FAST | 247,139 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 183,646 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 145,040 | 0.0% | 99.9% |  |
| _STORE_SUBSCR | 125,997 | 0.0% | 99.9% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 112,527 | 0.0% | 99.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 112,527 | 0.0% | 99.9% |  |
| _BINARY_OP | 112,383 | 0.0% | 99.9% |  |
| LOAD_NAME | 106,000 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 80,257 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 70,840 | 0.0% | 99.9% | 2.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 59,500 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 57,040 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 55,600 | 0.0% | 100.0% |  |
| BUILD_LIST | 45,840 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 45,324 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 41,012 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 39,280 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 38,487 | 0.0% | 100.0% |  |
| STORE_NAME | 35,420 | 0.0% | 100.0% |  |
| UNARY_NOT | 33,717 | 0.0% | 100.0% |  |
| _TO_BOOL | 27,827 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 17,652 | 0.0% | 100.0% | 30.1% |
| TO_BOOL_STR | 16,660 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,320 | 0.0% | 100.0% |  |
| CALL_LEN | 15,572 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 13,680 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 13,380 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 11,920 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 11,920 | 0.0% | 100.0% |  |
| POP_TOP | 11,886 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 10,500 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 6,000 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 4,680 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 2,560 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,920 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 1,920 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 1,500 | 0.0% | 100.0% |  |
| STORE_SLICE | 1,220 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,220 | 0.0% | 100.0% |  |
| BUILD_STRING | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 480 | 0.0% | 100.0% | 100.0% |
| BINARY_SUBSCR_STR_INT | 240 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 160 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 45,371 |
| LOAD_ATTR_PROPERTY | 2,834 |
| YIELD_VALUE | 840 |
| FOR_ITER_GEN | 760 |
| CALL | 695 |
| CALL_PY_WITH_DEFAULTS | 460 |
| CALL_LIST_APPEND | 420 |
| CALL_FUNCTION_EX | 380 |
| CALL_KW | 340 |
| BINARY_SUBSCR_GETITEM | 240 |
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
Stats gathered on: 2023-11-18
