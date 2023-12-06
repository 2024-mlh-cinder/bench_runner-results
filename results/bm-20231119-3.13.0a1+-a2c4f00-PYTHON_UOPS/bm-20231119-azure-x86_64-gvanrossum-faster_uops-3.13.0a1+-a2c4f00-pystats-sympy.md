
# Pystats results

- benchmark: sympy
- fork: gvanrossum
- ref: faster-uops
- commit hash: a2c4f00
- commit date: 2023-11-19T11:22:02-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 832,658,764 | 16.8% | 16.8% |  |
| STORE_FAST | 285,721,542 | 5.8% | 22.6% |  |
| POP_JUMP_IF_FALSE | 256,797,274 | 5.2% | 27.7% |  |
| RESUME_CHECK | 250,103,578 | 5.0% | 32.8% |  |
| LOAD_GLOBAL_BUILTIN | 208,029,974 | 4.2% | 37.0% | 0.0% |
| LOAD_FAST_LOAD_FAST | 204,061,228 | 4.1% | 41.1% |  |
| RETURN_VALUE | 177,181,738 | 3.6% | 44.7% |  |
| LOAD_CONST | 171,397,058 | 3.5% | 48.1% |  |
| TO_BOOL_BOOL | 159,508,450 | 3.2% | 51.4% | 0.1% |
| INTERPRETER_EXIT | 127,248,669 | 2.6% | 53.9% |  |
| ENTER_EXECUTOR | 118,530,623 | 2.4% | 56.3% |  |
| LOAD_GLOBAL_MODULE | 110,216,408 | 2.2% | 58.5% | 0.0% |
| LOAD_ATTR_SLOT | 95,509,664 | 1.9% | 60.5% | 38.2% |
| LOAD_ATTR | 91,874,382 | 1.9% | 62.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 86,387,972 | 1.7% | 64.1% | 10.5% |
| POP_JUMP_IF_TRUE | 68,564,953 | 1.4% | 65.4% |  |
| POP_TOP | 59,925,438 | 1.2% | 66.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,532,861 | 1.1% | 67.8% | 27.6% |
| RETURN_CONST | 54,271,395 | 1.1% | 68.9% |  |
| CALL_ISINSTANCE | 54,028,718 | 1.1% | 70.0% |  |
| CALL_PY_EXACT_ARGS | 52,664,640 | 1.1% | 71.0% | 14.8% |
| GET_ITER | 50,655,794 | 1.0% | 72.1% |  |
| LOAD_DEREF | 50,522,988 | 1.0% | 73.1% |  |
| STORE_FAST_STORE_FAST | 49,557,627 | 1.0% | 74.1% |  |
| COMPARE_OP_INT | 48,594,890 | 1.0% | 75.1% | 1.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 46,669,732 | 0.9% | 76.0% |  |
| IS_OP | 45,325,197 | 0.9% | 76.9% |  |
| SWAP | 43,160,892 | 0.9% | 77.8% |  |
| CALL_BUILTIN_FAST | 43,057,646 | 0.9% | 78.7% |  |
| PUSH_NULL | 42,723,598 | 0.9% | 79.5% |  |
| BUILD_TUPLE | 42,216,010 | 0.9% | 80.4% |  |
| CALL_BUILTIN_O | 37,623,555 | 0.8% | 81.1% | 7.1% |
| COMPARE_OP | 36,851,106 | 0.7% | 81.9% |  |
| FOR_ITER | 34,301,114 | 0.7% | 82.6% |  |
| BINARY_OP | 34,088,829 | 0.7% | 83.3% |  |
| POP_JUMP_IF_NONE | 33,772,883 | 0.7% | 83.9% |  |
| COPY_FREE_VARS | 31,610,720 | 0.6% | 84.6% |  |
| NOP | 31,470,127 | 0.6% | 85.2% |  |
| CALL_LEN | 28,082,302 | 0.6% | 85.8% |  |
| CALL_FUNCTION_EX | 28,012,884 | 0.6% | 86.3% |  |
| LOAD_ATTR_PROPERTY | 27,995,080 | 0.6% | 86.9% | 14.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 27,652,454 | 0.6% | 87.5% | 23.4% |
| BUILD_MAP | 27,151,109 | 0.5% | 88.0% |  |
| CALL | 26,821,432 | 0.5% | 88.6% |  |
| CALL_LIST_APPEND | 24,015,809 | 0.5% | 89.0% |  |
| YIELD_VALUE | 22,906,651 | 0.5% | 89.5% |  |
| FOR_ITER_LIST | 22,392,639 | 0.5% | 90.0% | 0.9% |
| BINARY_SUBSCR_LIST_INT | 22,007,650 | 0.4% | 90.4% | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 21,780,381 | 0.4% | 90.8% | 65.5% |
| BUILD_LIST | 20,483,264 | 0.4% | 91.3% |  |
| FOR_ITER_TUPLE | 20,352,033 | 0.4% | 91.7% | 1.2% |
| BINARY_SUBSCR | 20,201,045 | 0.4% | 92.1% |  |
| STORE_SUBSCR_LIST_INT | 20,086,263 | 0.4% | 92.5% |  |
| TO_BOOL_INT | 18,502,213 | 0.4% | 92.8% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,065,892 | 0.4% | 93.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 17,958,383 | 0.4% | 93.6% | 0.8% |
| EXTENDED_ARG | 17,074,561 | 0.3% | 93.9% |  |
| DICT_MERGE | 16,636,343 | 0.3% | 94.3% |  |
| LOAD_FAST_AND_CLEAR | 14,957,259 | 0.3% | 94.6% |  |
| CALL_TYPE_1 | 14,797,771 | 0.3% | 94.9% |  |
| COMPARE_OP_STR | 14,523,886 | 0.3% | 95.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,383,183 | 0.3% | 95.4% | 0.3% |
| RETURN_GENERATOR | 14,304,075 | 0.3% | 95.7% |  |
| TO_BOOL | 12,896,829 | 0.3% | 96.0% |  |
| CONTAINS_OP | 12,714,305 | 0.3% | 96.2% |  |
| CALL_KW | 10,673,151 | 0.2% | 96.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,064,521 | 0.2% | 96.6% | 0.0% |
| STORE_ATTR_SLOT | 9,059,758 | 0.2% | 96.8% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,985,530 | 0.2% | 97.0% | 0.1% |
| IMPORT_FROM | 8,954,497 | 0.2% | 97.2% |  |
| CALL_BUILTIN_CLASS | 8,479,923 | 0.2% | 97.4% |  |
| MAP_ADD | 7,866,144 | 0.2% | 97.5% |  |
| IMPORT_NAME | 7,759,362 | 0.2% | 97.7% |  |
| STORE_DEREF | 7,701,746 | 0.2% | 97.8% |  |
| MAKE_CELL | 6,049,313 | 0.1% | 98.0% |  |
| CALL_TUPLE_1 | 5,849,156 | 0.1% | 98.1% | 0.0% |
| JUMP_FORWARD | 5,743,169 | 0.1% | 98.2% |  |
| MAKE_FUNCTION | 5,385,166 | 0.1% | 98.3% |  |
| UNARY_NOT | 5,273,840 | 0.1% | 98.4% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,725 | 0.1% | 98.5% | 0.1% |
| COPY | 4,612,825 | 0.1% | 98.6% |  |
| CALL_PY_WITH_DEFAULTS | 4,590,866 | 0.1% | 98.7% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,584,385 | 0.1% | 98.8% | 0.2% |
| BINARY_OP_ADD_INT | 3,742,965 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 3,369,230 | 0.1% | 98.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,851 | 0.1% | 99.0% | 0.0% |
| BINARY_SUBSCR_DICT | 3,051,520 | 0.1% | 99.1% |  |
| BINARY_OP_MULTIPLY_INT | 2,757,824 | 0.1% | 99.1% | 0.0% |
| TO_BOOL_NONE | 2,647,428 | 0.1% | 99.2% | 8.6% |
| LIST_APPEND | 2,557,025 | 0.1% | 99.2% |  |
| BINARY_OP_SUBTRACT_INT | 2,473,007 | 0.0% | 99.3% |  |
| TO_BOOL_LIST | 2,285,640 | 0.0% | 99.3% | 0.5% |
| STORE_SUBSCR_DICT | 2,276,478 | 0.0% | 99.4% |  |
| FOR_ITER_RANGE | 2,225,198 | 0.0% | 99.4% |  |
| STORE_SUBSCR | 2,005,143 | 0.0% | 99.4% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,140 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,755,159 | 0.0% | 99.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,645,759 | 0.0% | 99.5% | 20.5% |
| UNPACK_SEQUENCE_TUPLE | 1,591,562 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,572,572 | 0.0% | 99.6% |  |
| LIST_EXTEND | 1,349,102 | 0.0% | 99.6% |  |
| CALL_INTRINSIC_1 | 1,349,062 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,381 | 0.0% | 99.7% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,181,959 | 0.0% | 99.7% |  |
| SEND_GEN | 1,029,836 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,464 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,464 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,464 | 0.0% | 99.8% |  |
| STORE_ATTR | 591,357 | 0.0% | 99.8% |  |
| BINARY_SLICE | 564,009 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 551,660 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,677 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,416 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 533,148 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 503,100 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 369,557 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 99.9% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 227,836 | 0.0% | 100.0% | 36.5% |
| FOR_ITER_GEN | 191,356 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,876 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,571 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,246 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 131,280 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,305 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,070 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 71,540 | 0.0% | 100.0% |  |
| BUILD_SET | 50,356 | 0.0% | 100.0% |  |
| RESUME | 47,565 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,721 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,512 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,260 | 0.0% | 100.0% |  |
| SET_ADD | 18,320 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,760 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,010 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,205 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 159,555,607 | 3.2% | 3.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 140,535,690 | 2.8% | 6.1% |
| RESUME_CHECK LOAD_FAST | 115,509,831 | 2.3% | 8.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 105,888,852 | 2.1% | 10.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 105,275,949 | 2.1% | 12.6% |
| CACHE RESUME_CHECK | 99,063,108 | 2.0% | 14.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,057,646 | 1.9% | 16.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 73,128,020 | 1.5% | 18.0% |
| RETURN_VALUE INTERPRETER_EXIT | 72,896,728 | 1.5% | 19.5% |
| LOAD_FAST LOAD_CONST | 60,357,446 | 1.2% | 20.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,849,587 | 1.2% | 21.9% |
| LOAD_FAST RETURN_VALUE | 52,812,966 | 1.1% | 22.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 51,676,987 | 1.0% | 24.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 51,183,165 | 1.0% | 25.0% |
| LOAD_FAST LOAD_ATTR | 50,963,029 | 1.0% | 26.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 48,082,755 | 1.0% | 27.0% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 47,060,836 | 0.9% | 28.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 43,466,386 | 0.9% | 28.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 42,872,297 | 0.9% | 29.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 42,870,809 | 0.9% | 30.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,047,053 | 0.8% | 31.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,195,157 | 0.8% | 32.2% |
| LOAD_CONST LOAD_CONST | 40,198,068 | 0.8% | 33.1% |
| RETURN_VALUE STORE_FAST | 38,448,604 | 0.8% | 33.8% |
| PUSH_NULL LOAD_FAST | 35,228,432 | 0.7% | 34.5% |
| LOAD_ATTR STORE_FAST | 34,996,989 | 0.7% | 35.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,545,746 | 0.7% | 35.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 33,432,672 | 0.7% | 36.6% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,432,500 | 0.7% | 37.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,131,534 | 0.7% | 37.9% |
| RETURN_CONST INTERPRETER_EXIT | 32,283,570 | 0.7% | 38.6% |
| IS_OP POP_JUMP_IF_FALSE | 29,996,433 | 0.6% | 39.2% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 29,940,901 | 0.6% | 39.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 29,560,668 | 0.6% | 40.4% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 29,352,061 | 0.6% | 41.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 28,961,727 | 0.6% | 41.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,347,174 | 0.6% | 42.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 28,279,266 | 0.6% | 42.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 27,718,194 | 0.6% | 43.3% |
| LOAD_FAST CALL_LEN | 27,053,823 | 0.5% | 43.8% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,064,246 | 0.5% | 44.3% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 24,687,697 | 0.5% | 44.8% |
| BINARY_OP STORE_FAST | 24,134,341 | 0.5% | 45.3% |
| LOAD_CONST CALL_BUILTIN_FAST | 23,928,593 | 0.5% | 45.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 22,646,304 | 0.5% | 46.3% |
| LOAD_ATTR_SLOT STORE_FAST | 22,510,349 | 0.5% | 46.7% |
| POP_TOP ENTER_EXECUTOR | 22,324,157 | 0.5% | 47.2% |
| YIELD_VALUE INTERPRETER_EXIT | 22,060,631 | 0.4% | 47.6% |
| COPY_FREE_VARS RESUME_CHECK | 21,669,969 | 0.4% | 48.0% |
| LOAD_FAST TO_BOOL_BOOL | 21,598,992 | 0.4% | 48.5% |
| RESUME_CHECK NOP | 21,364,180 | 0.4% | 48.9% |
| BUILD_TUPLE RETURN_VALUE | 21,220,708 | 0.4% | 49.3% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,085,942 | 0.4% | 49.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,793,140 | 0.4% | 50.2% |
| LOAD_CONST COMPARE_OP_INT | 20,725,036 | 0.4% | 50.6% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,465,580 | 0.4% | 51.0% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 19,370,618 | 0.4% | 51.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 18,992,414 | 0.4% | 51.8% |
| GET_ITER FOR_ITER | 18,960,871 | 0.4% | 52.2% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,851,870 | 0.4% | 52.5% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,813,740 | 0.4% | 52.9% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 18,550,732 | 0.4% | 53.3% |
| COMPARE_OP POP_JUMP_IF_FALSE | 18,467,211 | 0.4% | 53.7% |
| ENTER_EXECUTOR POP_JUMP_IF_NONE | 18,301,504 | 0.4% | 54.0% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 17,882,671 | 0.4% | 54.4% |
| LOAD_FAST TO_BOOL_INT | 17,625,581 | 0.4% | 54.7% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 17,314,146 | 0.3% | 55.1% |
| LOAD_FAST PUSH_NULL | 17,282,394 | 0.3% | 55.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,202,860 | 0.3% | 55.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 17,191,195 | 0.3% | 56.1% |
| DICT_MERGE CALL_FUNCTION_EX | 16,636,343 | 0.3% | 56.5% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,622,472 | 0.3% | 56.8% |
| BUILD_MAP LOAD_FAST | 16,611,126 | 0.3% | 57.1% |
| LOAD_FAST DICT_MERGE | 16,571,409 | 0.3% | 57.5% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,119,432 | 0.3% | 57.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,025,986 | 0.3% | 58.1% |
| LOAD_ATTR LOAD_FAST | 15,959,314 | 0.3% | 58.4% |
| LOAD_FAST CALL_BUILTIN_O | 15,702,221 | 0.3% | 58.8% |
| RESUME_CHECK LOAD_CONST | 15,611,190 | 0.3% | 59.1% |
| LOAD_FAST CALL_LIST_APPEND | 15,553,505 | 0.3% | 59.4% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 15,397,121 | 0.3% | 59.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,185,244 | 0.3% | 60.0% |
| RETURN_VALUE RETURN_VALUE | 15,183,899 | 0.3% | 60.3% |
| POP_JUMP_IF_NONE ENTER_EXECUTOR | 15,174,604 | 0.3% | 60.6% |
| RESUME_CHECK POP_TOP | 14,972,781 | 0.3% | 60.9% |
| LOAD_ATTR IS_OP | 14,930,569 | 0.3% | 61.2% |
| LOAD_FAST CALL_TYPE_1 | 14,728,879 | 0.3% | 61.5% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 14,727,797 | 0.3% | 61.8% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 14,480,666 | 0.3% | 62.1% |
| POP_TOP RESUME_CHECK | 14,298,515 | 0.3% | 62.4% |
| LOAD_FAST GET_ITER | 14,273,453 | 0.3% | 62.7% |
| LOAD_CONST STORE_FAST | 14,264,137 | 0.3% | 63.0% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 14,076,833 | 0.3% | 63.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 13,892,851 | 0.3% | 63.5% |
| CACHE POP_TOP | 13,855,087 | 0.3% | 63.8% |
| CALL_BUILTIN_O STORE_FAST | 13,587,807 | 0.3% | 64.1% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 13,240,890 | 0.3% | 64.4% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 13,127,681 | 0.3% | 64.6% |
| CACHE COPY_FREE_VARS | 12,999,125 | 0.3% | 64.9% |
| CALL_METHOD_DESCRIPTOR_FAST LOAD_FAST | 12,687,890 | 0.3% | 65.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 530,649 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,447 | 56.6% |
| RETURN_VALUE | 93,840 | 16.6% |
| GET_ITER | 54,720 | 9.7% |
| BINARY_OP | 39,120 | 6.9% |
| STORE_FAST | 18,960 | 3.4% |


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
| RESUME_CHECK | 99,063,108 | 77.7% |
| POP_TOP | 13,855,087 | 10.9% |
| COPY_FREE_VARS | 12,999,125 | 10.2% |
| MAKE_CELL | 1,509,139 | 1.2% |
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
| LOAD_FAST_LOAD_FAST | 10,918,506 | 54.0% |
| LOAD_DEREF | 6,404,508 | 31.7% |
| BUILD_TUPLE | 1,784,833 | 8.8% |
| LOAD_FAST | 690,579 | 3.4% |
| RETURN_VALUE | 152,430 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,066,532 | 30.0% |
| POP_JUMP_IF_NONE | 5,378,478 | 26.6% |
| LOAD_FAST | 5,233,480 | 25.9% |
| CALL | 895,839 | 4.4% |
| GET_ITER | 889,780 | 4.4% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,634 | 73.7% |
| BUILD_TUPLE | 157,200 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,290 | 8.7% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,304 | 100.0% |
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
| JUMP_BACKWARD | 920 | 29.7% |
| ENTER_EXECUTOR | 280 | 9.0% |
| LOAD_FAST | 60 | 1.9% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 22,512 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,512 | 100.0% |


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
| LOAD_FAST | 14,273,453 | 28.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,589,458 | 24.9% |
| CALL | 10,953,493 | 21.6% |
| RETURN_VALUE | 4,117,023 | 8.1% |
| CALL_BUILTIN_O | 2,591,126 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 18,960,871 | 37.4% |
| FOR_ITER_TUPLE | 9,948,890 | 19.6% |
| LOAD_FAST_AND_CLEAR | 8,282,761 | 16.4% |
| CALL_PY_EXACT_ARGS | 6,004,338 | 11.9% |
| FOR_ITER_LIST | 4,313,992 | 8.5% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 347,016 | 64.2% |
| BINARY_SUBSCR | 185,800 | 34.4% |
| RETURN_VALUE | 7,520 | 1.4% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540,416 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,896,728 | 57.3% |
| RETURN_CONST | 32,283,570 | 25.4% |
| YIELD_VALUE | 22,060,631 | 17.3% |
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
| LOAD_CONST | 5,385,166 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 3,367,690 | 62.5% |
| LOAD_GLOBAL_BUILTIN | 793,404 | 14.7% |
| STORE_FAST | 669,680 | 12.4% |
| LOAD_FAST | 458,616 | 8.5% |
| STORE_NAME | 33,580 | 0.6% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,364,180 | 67.9% |
| POP_JUMP_IF_TRUE | 4,184,003 | 13.3% |
| STORE_FAST | 1,973,302 | 6.3% |
| POP_JUMP_IF_FALSE | 1,911,089 | 6.1% |
| POP_TOP | 1,392,049 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,280,655 | 39.0% |
| LOAD_DEREF | 10,423,972 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,377,498 | 20.3% |
| LOAD_FAST_LOAD_FAST | 897,861 | 2.9% |
| LOAD_CONST | 751,153 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,736 | 45.8% |
| POP_TOP | 358,308 | 39.5% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,736 | 45.8% |
| EXTENDED_ARG | 201,210 | 22.2% |
| ENTER_EXECUTOR | 155,378 | 17.1% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,972,781 | 25.0% |
| CACHE | 13,855,087 | 23.1% |
| RETURN_CONST | 7,856,572 | 13.1% |
| STORE_FAST | 5,839,262 | 9.7% |
| SWAP | 5,747,065 | 9.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 22,324,157 | 37.3% |
| RESUME_CHECK | 14,298,515 | 23.9% |
| LOAD_FAST | 7,247,610 | 12.1% |
| RETURN_VALUE | 5,270,865 | 8.8% |
| LOAD_CONST | 2,640,800 | 4.4% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,670 | 41.3% |
| BINARY_SUBSCR_DICT | 169,974 | 18.8% |
| RAISE_VARARGS | 115,250 | 12.7% |
| ENTER_EXECUTOR | 102,260 | 11.3% |
| LOAD_ATTR | 89,180 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,254 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,770 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,282,394 | 40.5% |
| LOAD_DEREF | 11,776,496 | 27.6% |
| LOAD_ATTR | 8,321,081 | 19.5% |
| CALL_BUILTIN_FAST | 2,128,620 | 5.0% |
| LOAD_SUPER_ATTR_ATTR | 1,181,959 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,228,432 | 82.5% |
| LOAD_FAST_LOAD_FAST | 5,556,154 | 13.0% |
| LOAD_CONST | 1,723,680 | 4.0% |
| LOAD_DEREF | 127,450 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,860,065 | 68.9% |
| CALL_PY_EXACT_ARGS | 4,117,190 | 28.8% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,080 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,164,628 | 71.1% |
| STORE_FAST | 2,660,353 | 18.6% |
| LOAD_FAST | 792,006 | 5.5% |
| GET_YIELD_FROM_ITER | 347,016 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,812,966 | 29.8% |
| LOAD_ATTR_SLOT | 33,432,500 | 18.9% |
| BUILD_TUPLE | 21,220,708 | 12.0% |
| RETURN_VALUE | 15,183,899 | 8.6% |
| CALL_BUILTIN_O | 11,432,831 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,896,728 | 41.1% |
| STORE_FAST | 38,448,604 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,465,580 | 11.0% |
| RETURN_VALUE | 15,183,899 | 8.6% |
| LOAD_FAST | 5,437,911 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,916,490 | 95.6% |
| BINARY_SUBSCR | 56,960 | 2.8% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.9% |
| SWAP | 5,960 | 0.3% |
| STORE_SUBSCR | 3,363 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,903,610 | 94.9% |
| ENTER_EXECUTOR | 70,640 | 3.5% |
| JUMP_FORWARD | 9,840 | 0.5% |
| JUMP_BACKWARD | 9,300 | 0.5% |
| STORE_SUBSCR | 3,363 | 0.2% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.8% |
| LOAD_FAST | 2,198,687 | 17.0% |
| LOAD_GLOBAL_MODULE | 118,985 | 0.9% |
| LOAD_ATTR | 117,984 | 0.9% |
| RETURN_VALUE | 27,310 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,225,046 | 94.8% |
| POP_JUMP_IF_TRUE | 509,800 | 4.0% |
| UNARY_NOT | 84,158 | 0.7% |
| TO_BOOL_BOOL | 41,197 | 0.3% |
| TO_BOOL | 21,389 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,472 | 22.0% |
| LOAD_FAST | 109,469 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,697 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,986 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,844 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,141 | 10.9% |
| CALL_LIST_APPEND | 39,980 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,671 | 65.3% |
| TO_BOOL_BOOL | 1,084,973 | 20.6% |
| TO_BOOL_LIST | 661,871 | 12.6% |
| TO_BOOL | 84,158 | 1.6% |
| TO_BOOL_INT | 167 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,432 | 66.9% |
| STORE_FAST | 882,751 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,925 | 1.6% |
| LOAD_CONST | 34,352 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,752,718 | 34.5% |
| COMPARE_OP_INT | 6,273,260 | 18.4% |
| COMPARE_OP | 6,162,400 | 18.1% |
| CALL_TUPLE_1 | 4,707,360 | 13.8% |
| LOAD_FAST | 1,516,439 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,134,341 | 70.8% |
| RETURN_VALUE | 5,644,706 | 16.6% |
| CALL_BUILTIN_O | 1,095,122 | 3.2% |
| LOAD_FAST | 857,875 | 2.5% |
| TO_BOOL_INT | 722,185 | 2.1% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,305 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,525 | 97.9% |
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
| POP_JUMP_IF_TRUE | 4,083,245 | 19.9% |
| STORE_FAST | 3,816,442 | 18.6% |
| SWAP | 3,548,581 | 17.3% |
| LOAD_FAST | 2,131,243 | 10.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,531,876 | 56.3% |
| SWAP | 3,548,581 | 17.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,391 | 11.2% |
| LOAD_FAST | 1,374,402 | 6.7% |
| BUILD_LIST | 748,353 | 3.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,163,909 | 44.8% |
| SWAP | 4,716,180 | 17.4% |
| BUILD_TUPLE | 4,366,343 | 16.1% |
| LOAD_CONST | 1,656,760 | 6.1% |
| RESUME_CHECK | 1,285,960 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,611,126 | 61.2% |
| SWAP | 4,716,180 | 17.4% |
| STORE_FAST | 3,331,418 | 12.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 5.8% |
| CALL_FUNCTION_EX | 734,880 | 2.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,276 | 64.1% |
| SWAP | 18,000 | 35.7% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,276 | 64.1% |
| SWAP | 18,000 | 35.7% |
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
| LOAD_FAST_LOAD_FAST | 18,992,414 | 45.0% |
| LOAD_FAST | 10,069,897 | 23.9% |
| LOAD_ATTR_SLOT | 5,042,318 | 11.9% |
| LOAD_ATTR | 3,033,683 | 7.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,220,708 | 50.3% |
| LOAD_GLOBAL_BUILTIN | 4,707,160 | 11.2% |
| BUILD_MAP | 4,366,343 | 10.3% |
| LOAD_CONST | 3,386,876 | 8.0% |
| CALL_LIST_APPEND | 3,214,240 | 7.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,375,369 | 35.0% |
| LOAD_FAST | 7,260,444 | 27.1% |
| BINARY_OP_MULTIPLY_INT | 2,291,865 | 8.5% |
| ENTER_EXECUTOR | 2,267,282 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,934 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,493 | 40.8% |
| STORE_FAST | 5,844,642 | 21.8% |
| RETURN_VALUE | 4,517,396 | 16.8% |
| POP_TOP | 1,118,719 | 4.2% |
| RESUME_CHECK | 1,061,468 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 16,636,343 | 59.4% |
| ENTER_EXECUTOR | 7,551,052 | 27.0% |
| LOAD_FAST | 1,403,596 | 5.0% |
| CALL_INTRINSIC_1 | 1,256,746 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,600,827 | 45.0% |
| RESUME_CHECK | 11,673,466 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,867 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,347,842 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,746 | 93.2% |
| BUILD_MAP | 91,256 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,508,779 | 98.5% |
| ENTER_EXECUTOR | 164,372 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,175 | 88.9% |
| POP_TOP | 698,043 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,811 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,085,942 | 57.2% |
| LOAD_FAST | 6,621,485 | 18.0% |
| CALL_TYPE_1 | 5,882,565 | 16.0% |
| LOAD_GLOBAL_MODULE | 1,179,822 | 3.2% |
| LOAD_CONST | 949,542 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,467,211 | 50.1% |
| BINARY_OP | 6,162,400 | 16.7% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.7% |
| UNARY_NOT | 3,442,671 | 9.3% |
| POP_JUMP_IF_TRUE | 2,275,155 | 6.2% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,880,389 | 46.3% |
| LOAD_ATTR | 3,188,646 | 25.1% |
| LOAD_GLOBAL_MODULE | 1,645,950 | 12.9% |
| LOAD_DEREF | 1,478,140 | 11.6% |
| LOAD_CONST | 174,992 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,801,044 | 77.1% |
| POP_JUMP_IF_TRUE | 2,903,101 | 22.8% |
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
| LOAD_FAST | 1,237,536 | 26.8% |
| COPY | 1,069,360 | 23.2% |
| LOAD_FAST_LOAD_FAST | 868,240 | 18.8% |
| CALL_ISINSTANCE | 525,020 | 11.4% |
| LOAD_CONST | 236,771 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,334,534 | 28.9% |
| COPY | 1,069,360 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,063,080 | 23.0% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,571 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 12,999,125 | 41.1% |
| ENTER_EXECUTOR | 7,004,396 | 22.2% |
| LOAD_ATTR_PROPERTY | 5,066,436 | 16.0% |
| CALL_PY_EXACT_ARGS | 4,700,760 | 14.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,194,786 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,669,969 | 68.6% |
| RETURN_GENERATOR | 9,860,065 | 31.2% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,186 | 0.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,284,800 | 98.7% |
| POP_JUMP_IF_NONE | 15,920 | 1.2% |
| FOR_ITER_LIST | 880 | 0.1% |
| ENTER_EXECUTOR | 320 | 0.0% |
| STORE_FAST | 160 | 0.0% |

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
| ENTER_EXECUTOR | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 80 | 66.7% |
| BUILD_LIST | 20 | 16.7% |
| RETURN_CONST | 20 | 16.7% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,571,409 | 99.6% |
| LOAD_DEREF | 64,934 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 16,636,343 | 100.0% |


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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 22,324,157 | 18.8% |
| CALL_LIST_APPEND | 17,314,146 | 14.6% |
| POP_JUMP_IF_TRUE | 15,397,121 | 13.0% |
| POP_JUMP_IF_NONE | 15,174,604 | 12.8% |
| POP_JUMP_IF_FALSE | 14,076,833 | 11.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 18,301,504 | 15.4% |
| POP_JUMP_IF_FALSE | 11,705,045 | 9.9% |
| RESUME_CHECK | 9,636,015 | 8.1% |
| FOR_ITER_LIST | 9,265,974 | 7.8% |
| FOR_ITER_TUPLE | 8,726,110 | 7.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,063,493 | 29.7% |
| CALL_LIST_APPEND | 4,571,158 | 26.8% |
| GET_ITER | 2,378,121 | 13.9% |
| ENTER_EXECUTOR | 1,742,151 | 10.2% |
| COMPARE_OP_INT | 1,718,052 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,645,155 | 38.9% |
| ENTER_EXECUTOR | 5,766,714 | 33.8% |
| FOR_ITER_LIST | 2,686,869 | 15.7% |
| FOR_ITER_TUPLE | 767,880 | 4.5% |
| FOR_ITER_RANGE | 642,400 | 3.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 18,960,871 | 55.3% |
| LOAD_FAST | 7,590,203 | 22.1% |
| SWAP | 6,724,852 | 19.6% |
| ENTER_EXECUTOR | 891,083 | 2.6% |
| JUMP_BACKWARD | 71,661 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 24,687,697 | 72.0% |
| ENTER_EXECUTOR | 2,590,086 | 7.6% |
| LOAD_FAST | 2,495,038 | 7.3% |
| SWAP | 1,295,619 | 3.8% |
| DELETE_FAST | 1,284,800 | 3.7% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,757,842 | 86.6% |
| STORE_FAST | 982,423 | 11.0% |
| STORE_DEREF | 185,692 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,821,472 | 76.2% |
| STORE_DEREF | 2,092,425 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,758,602 | 100.0% |
| ENTER_EXECUTOR | 740 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,757,842 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 14,930,569 | 32.9% |
| LOAD_FAST | 12,658,270 | 27.9% |
| LOAD_CONST | 10,976,347 | 24.2% |
| LOAD_FAST_LOAD_FAST | 5,893,544 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 539,792 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,996,433 | 66.2% |
| YIELD_VALUE | 12,642,930 | 27.9% |
| POP_JUMP_IF_TRUE | 2,641,649 | 5.8% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 90,354 | 24.4% |
| POP_TOP | 61,012 | 16.5% |
| LIST_APPEND | 52,030 | 14.1% |
| STORE_FAST | 34,457 | 9.3% |
| POP_JUMP_IF_TRUE | 29,934 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 100,564 | 27.2% |
| FOR_ITER_TUPLE | 80,754 | 21.9% |
| FOR_ITER | 71,661 | 19.4% |
| FOR_ITER_LIST | 53,862 | 14.6% |
| EXTENDED_ARG | 22,600 | 6.1% |


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
| STORE_FAST | 4,138,139 | 72.1% |
| POP_TOP | 734,246 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,880 | 3.3% |
| LOAD_FAST | 137,425 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,996,375 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,169 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,634 | 5.7% |
| STORE_FAST | 119,025 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,144,677 | 44.8% |
| BUILD_TUPLE | 653,918 | 25.6% |
| RETURN_VALUE | 510,859 | 20.0% |
| LOAD_ATTR_PROPERTY | 64,357 | 2.5% |
| BINARY_SUBSCR | 37,830 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,500,035 | 97.8% |
| JUMP_BACKWARD | 52,030 | 2.0% |
| LOAD_NAME | 4,800 | 0.2% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,346,962 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,347,842 | 99.9% |
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
| LOAD_FAST | 50,963,029 | 55.5% |
| LOAD_GLOBAL_MODULE | 33,545,746 | 36.5% |
| CALL_TYPE_1 | 2,352,272 | 2.6% |
| LOAD_ATTR_SLOT | 2,297,051 | 2.5% |
| LOAD_GLOBAL_BUILTIN | 1,905,025 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 34,996,989 | 38.1% |
| LOAD_FAST | 15,959,314 | 17.4% |
| IS_OP | 14,930,569 | 16.3% |
| PUSH_NULL | 8,321,081 | 9.1% |
| CONTAINS_OP | 3,188,646 | 3.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,357,446 | 35.2% |
| LOAD_CONST | 40,198,068 | 23.5% |
| RESUME_CHECK | 15,611,190 | 9.1% |
| RETURN_CONST | 9,526,680 | 5.6% |
| CALL_LEN | 7,178,270 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,198,068 | 23.5% |
| CALL_BUILTIN_FAST | 23,928,593 | 14.0% |
| COMPARE_OP_INT | 20,725,036 | 12.1% |
| STORE_FAST | 14,264,137 | 8.3% |
| IS_OP | 10,976,347 | 6.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 10,423,972 | 20.6% |
| STORE_FAST_STORE_FAST | 9,322,980 | 18.5% |
| LOAD_ATTR_SLOT | 6,404,508 | 12.7% |
| POP_JUMP_IF_FALSE | 4,643,981 | 9.2% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,044 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 11,776,496 | 23.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,497,003 | 18.8% |
| LOAD_FAST | 9,344,824 | 18.5% |
| BINARY_SUBSCR | 6,404,508 | 12.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 6.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,555,607 | 19.2% |
| LOAD_GLOBAL_BUILTIN | 140,535,690 | 16.9% |
| RESUME_CHECK | 115,509,831 | 13.9% |
| POP_JUMP_IF_FALSE | 105,888,852 | 12.7% |
| PUSH_NULL | 35,228,432 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,057,646 | 11.3% |
| LOAD_ATTR_METHOD_NO_DICT | 73,128,020 | 8.8% |
| LOAD_CONST | 60,357,446 | 7.2% |
| RETURN_VALUE | 52,812,966 | 6.3% |
| LOAD_GLOBAL_MODULE | 51,676,987 | 6.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,282,761 | 55.4% |
| LOAD_FAST_AND_CLEAR | 6,674,418 | 44.6% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 8,282,681 | 55.4% |
| LOAD_FAST_AND_CLEAR | 6,674,418 | 44.6% |
| MAKE_CELL | 160 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,557,060 | 99.0% |
| POP_TOP | 7,360 | 0.5% |
| LOAD_FAST | 4,000 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 2,980 | 0.2% |
| POP_JUMP_IF_FALSE | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 1,556,980 | 99.0% |
| POP_JUMP_IF_NOT_NONE | 7,360 | 0.5% |
| LOAD_FAST | 3,860 | 0.2% |
| COMPARE_OP_INT | 1,920 | 0.1% |
| CALL_BUILTIN_CLASS | 1,360 | 0.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 43,466,386 | 21.3% |
| POP_JUMP_IF_FALSE | 28,961,727 | 14.2% |
| LOAD_GLOBAL_BUILTIN | 28,347,174 | 13.9% |
| STORE_FAST_STORE_FAST | 14,727,797 | 7.2% |
| POP_JUMP_IF_NONE | 13,240,890 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 21,085,942 | 10.3% |
| BINARY_SUBSCR_LIST_INT | 19,370,618 | 9.5% |
| BUILD_TUPLE | 18,992,414 | 9.3% |
| STORE_SUBSCR_LIST_INT | 18,851,870 | 9.2% |
| CALL_BUILTIN_FAST | 17,202,860 | 8.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,274 | 19.4% |
| LOAD_FAST | 34,210 | 18.8% |
| STORE_FAST | 26,933 | 14.8% |
| RESUME_CHECK | 10,939 | 6.0% |
| RESUME | 10,782 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,561 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,269 | 22.7% |
| LOAD_FAST | 39,596 | 21.8% |
| LOAD_ATTR | 14,079 | 7.7% |
| CALL | 9,830 | 5.4% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 27,640 | 38.6% |
| LOAD_NAME | 8,000 | 11.2% |
| CALL | 7,360 | 10.3% |
| LIST_APPEND | 4,800 | 6.7% |
| POP_TOP | 4,740 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 22,500 | 31.5% |
| LOAD_CONST | 19,560 | 27.3% |
| LOAD_NAME | 8,000 | 11.2% |
| CALL | 5,380 | 7.5% |
| EXTENDED_ARG | 3,700 | 5.2% |


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
| MAKE_CELL | 2,274,690 | 37.6% |
| CACHE | 1,509,139 | 24.9% |
| CALL_PY_EXACT_ARGS | 768,616 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,436 | 10.8% |
| CALL | 523,687 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,771,063 | 62.3% |
| MAKE_CELL | 2,274,690 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,853,684 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,863,405 | 100.0% |
| JUMP_BACKWARD | 2,399 | 0.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 105,275,949 | 41.0% |
| COMPARE_OP_INT | 33,131,534 | 12.9% |
| IS_OP | 29,996,433 | 11.7% |
| COMPARE_OP | 18,467,211 | 7.2% |
| COMPARE_OP_STR | 14,480,666 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 105,888,852 | 41.2% |
| LOAD_GLOBAL_BUILTIN | 57,849,587 | 22.5% |
| LOAD_FAST_LOAD_FAST | 28,961,727 | 11.3% |
| RETURN_CONST | 27,718,194 | 10.8% |
| ENTER_EXECUTOR | 14,076,833 | 5.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 18,301,504 | 54.2% |
| LOAD_FAST | 8,983,100 | 26.6% |
| BINARY_SUBSCR | 5,378,478 | 15.9% |
| LOAD_DEREF | 1,088,849 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,174,604 | 44.9% |
| LOAD_FAST_LOAD_FAST | 13,240,890 | 39.2% |
| LOAD_FAST | 2,492,220 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 1,438,195 | 4.3% |
| LOAD_CONST | 1,111,425 | 3.3% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,622,472 | 92.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,224,985 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,226,600 | 67.7% |
| LOAD_FAST_LOAD_FAST | 2,004,431 | 11.1% |
| LOAD_GLOBAL_MODULE | 1,878,503 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,169 | 7.7% |
| ENTER_EXECUTOR | 447,749 | 2.5% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 48,082,755 | 70.1% |
| TO_BOOL_INT | 8,150,949 | 11.9% |
| CONTAINS_OP | 2,903,101 | 4.2% |
| IS_OP | 2,641,649 | 3.9% |
| COMPARE_OP | 2,275,155 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,432,672 | 48.8% |
| ENTER_EXECUTOR | 15,397,121 | 22.5% |
| LOAD_GLOBAL_BUILTIN | 5,255,037 | 7.7% |
| NOP | 4,184,003 | 6.1% |
| BUILD_LIST | 4,083,245 | 6.0% |


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
| POP_JUMP_IF_FALSE | 27,718,194 | 51.1% |
| RESUME_CHECK | 10,045,317 | 18.5% |
| FOR_ITER_LIST | 5,672,272 | 10.5% |
| ENTER_EXECUTOR | 4,688,958 | 8.6% |
| STORE_SUBSCR | 1,903,610 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,283,570 | 59.5% |
| LOAD_CONST | 9,526,680 | 17.6% |
| POP_TOP | 7,856,572 | 14.5% |
| TO_BOOL_BOOL | 2,016,441 | 3.7% |
| STORE_FAST | 1,541,220 | 2.8% |


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
| LOAD_FAST | 16,240 | 88.6% |
| RETURN_VALUE | 2,040 | 11.1% |
| BINARY_SUBSCR | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 16,900 | 92.2% |
| JUMP_BACKWARD | 1,420 | 7.8% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,367,690 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,816,494 | 83.6% |
| STORE_FAST | 298,242 | 8.9% |
| STORE_DEREF | 95,657 | 2.8% |
| LOAD_CONST | 52,360 | 1.6% |
| LOAD_GLOBAL_MODULE | 42,976 | 1.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,828 | 82.3% |
| LOAD_FAST | 98,460 | 16.6% |
| STORE_ATTR | 3,906 | 0.7% |
| SWAP | 2,151 | 0.4% |
| LOAD_DEREF | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,658 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,250 | 19.7% |
| LOAD_FAST | 89,977 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,577,880 | 46.5% |
| IMPORT_FROM | 2,092,425 | 27.2% |
| LOAD_ATTR | 1,558,843 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,657 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,840 | 46.5% |
| POP_TOP | 1,906,733 | 24.8% |
| LOAD_DEREF | 1,298,335 | 16.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.3% |
| IMPORT_FROM | 185,692 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,448,604 | 13.5% |
| LOAD_ATTR | 34,996,989 | 12.2% |
| BINARY_OP | 24,134,341 | 8.4% |
| LOAD_ATTR_SLOT | 22,510,349 | 7.9% |
| LOAD_CONST | 14,264,137 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,555,607 | 55.8% |
| LOAD_FAST_LOAD_FAST | 43,466,386 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 29,940,901 | 10.5% |
| LOAD_GLOBAL_MODULE | 11,162,445 | 3.9% |
| STORE_FAST | 9,340,944 | 3.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,342 | 71.8% |
| FOR_ITER_TUPLE | 409,217 | 23.3% |
| FOR_ITER_RANGE | 47,440 | 2.7% |
| FOR_ITER | 38,160 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,178,909 | 67.2% |
| LOAD_ATTR_PROPERTY | 191,465 | 10.9% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 186,959 | 10.7% |
| LOAD_DEREF | 49,680 | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,840 | 2.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 42,872,297 | 86.5% |
| RETURN_VALUE | 3,248,232 | 6.6% |
| UNPACK_SEQUENCE_TUPLE | 1,396,890 | 2.8% |
| STORE_FAST_STORE_FAST | 771,433 | 1.6% |
| BUILD_LIST | 413,120 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 14,727,797 | 29.7% |
| LOAD_FAST | 13,892,851 | 28.0% |
| LOAD_DEREF | 9,322,980 | 18.8% |
| LOAD_GLOBAL_BUILTIN | 8,512,910 | 17.2% |
| LOAD_GLOBAL_MODULE | 1,036,320 | 2.1% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 38,060 | 29.0% |
| MAKE_FUNCTION | 33,580 | 25.6% |
| CALL | 21,600 | 16.5% |
| LOAD_CONST | 9,120 | 6.9% |
| SET_FUNCTION_ATTRIBUTE | 7,660 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 48,660 | 37.1% |
| LOAD_NAME | 27,640 | 21.1% |
| IMPORT_FROM | 26,000 | 19.8% |
| POP_TOP | 12,080 | 9.2% |
| RETURN_CONST | 4,860 | 3.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 9,397,469 | 21.8% |
| LOAD_FAST_AND_CLEAR | 8,282,681 | 19.2% |
| ENTER_EXECUTOR | 6,307,301 | 14.6% |
| BUILD_MAP | 4,716,180 | 10.9% |
| LOAD_FAST | 4,609,885 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,397,689 | 21.8% |
| STORE_FAST | 7,931,049 | 18.4% |
| FOR_ITER | 6,724,852 | 15.6% |
| POP_TOP | 5,747,065 | 13.3% |
| BUILD_MAP | 4,716,180 | 10.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,454 | 26.3% |
| FOR_ITER | 6,803 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 16.0% |
| LOAD_FAST | 3,961 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,673 | 47.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,432 | 23.7% |
| STORE_FAST | 8,082 | 20.3% |
| UNPACK_SEQUENCE_TUPLE | 1,140 | 2.9% |
| UNPACK_SEQUENCE | 914 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,642,930 | 55.2% |
| ENTER_EXECUTOR | 4,974,577 | 21.7% |
| CALL_ISINSTANCE | 2,232,694 | 9.7% |
| LOAD_FAST | 1,140,842 | 5.0% |
| YIELD_VALUE | 677,496 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,060,631 | 96.3% |
| YIELD_VALUE | 677,496 | 3.0% |
| STORE_FAST | 162,884 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,058 | 38.0% |
| CALL | 11,117 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,096 | 12.8% |
| POP_TOP | 3,960 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,696 | 37.2% |
| LOAD_GLOBAL | 10,782 | 22.7% |
| LOAD_CONST | 8,762 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,360 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,594,562 | 69.3% |
| LOAD_FAST_LOAD_FAST | 573,779 | 15.3% |
| BINARY_SUBSCR_DICT | 420,640 | 11.2% |
| CALL_BUILTIN_CLASS | 81,145 | 2.2% |
| LOAD_FAST | 43,684 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,536,249 | 41.0% |
| SWAP | 942,331 | 25.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 540,174 | 14.4% |
| LOAD_CONST | 268,996 | 7.2% |
| LOAD_FAST | 201,478 | 5.4% |


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

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,676 | 60.5% |
| LOAD_ATTR_SLOT | 723,532 | 26.2% |
| LOAD_FAST_LOAD_FAST | 269,777 | 9.8% |
| LOAD_FAST | 94,285 | 3.4% |
| BINARY_OP | 1,447 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,865 | 83.1% |
| LOAD_FAST_LOAD_FAST | 181,166 | 6.6% |
| STORE_FAST | 175,551 | 6.4% |
| LOAD_FAST | 76,506 | 2.8% |
| LOAD_GLOBAL_MODULE | 25,197 | 0.9% |


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
| LOAD_CONST | 1,556,157 | 62.9% |
| LOAD_FAST_LOAD_FAST | 606,895 | 24.5% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,675 | 5.0% |
| BINARY_OP | 2,187 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,080,100 | 43.7% |
| STORE_FAST | 699,588 | 28.3% |
| BINARY_OP | 311,639 | 12.6% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,880 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,453 | 33.9% |
| LOAD_FAST_LOAD_FAST | 810,452 | 26.6% |
| LOAD_CONST | 642,800 | 21.1% |
| CALL_TUPLE_1 | 441,520 | 14.5% |
| RETURN_VALUE | 114,503 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 866,121 | 28.4% |
| RETURN_VALUE | 809,190 | 26.5% |
| BINARY_OP_ADD_INT | 420,640 | 13.8% |
| PUSH_NULL | 376,980 | 12.4% |
| SWAP | 318,100 | 10.4% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 59,680 | 37.5% |
| LOAD_FAST_LOAD_FAST | 40,800 | 25.6% |
| ENTER_EXECUTOR | 39,680 | 24.9% |
| LOAD_CONST | 14,546 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,242 | 100.0% |
| RETURN_VALUE | 2 | 0.0% |
| LOAD_CONST | 2 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 19,370,618 | 88.0% |
| COPY | 1,063,080 | 4.8% |
| LOAD_CONST | 1,025,968 | 4.7% |
| CALL_BUILTIN_CLASS | 282,366 | 1.3% |
| LOAD_FAST | 204,198 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,405,829 | 42.7% |
| SWAP | 9,397,469 | 42.7% |
| LOAD_CONST | 1,063,540 | 4.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 534,640 | 2.4% |
| RETURN_VALUE | 432,303 | 2.0% |


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
| LOAD_CONST | 8,718,946 | 97.0% |
| LOAD_FAST | 263,307 | 2.9% |
| BINARY_SUBSCR | 2,737 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,558 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 321,927 | 3.6% |
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
| LOAD_FAST | 13,127,681 | 91.3% |
| BINARY_OP_ADD_INT | 540,174 | 3.8% |
| LOAD_FAST_LOAD_FAST | 480,449 | 3.3% |
| LOAD_ATTR | 152,040 | 1.1% |
| RETURN_VALUE | 36,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,525,389 | 87.1% |
| COPY_FREE_VARS | 1,194,786 | 8.3% |
| MAKE_CELL | 654,436 | 4.6% |
| POP_TOP | 7,360 | 0.1% |
| RESUME | 620 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,795,638 | 33.0% |
| CALL_BUILTIN_CLASS | 1,959,418 | 23.1% |
| LOAD_CONST | 710,920 | 8.4% |
| CALL_LEN | 611,137 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 566,842 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,979,895 | 35.1% |
| CALL_BUILTIN_CLASS | 1,959,418 | 23.1% |
| GET_ITER | 1,728,288 | 20.4% |
| CALL | 284,332 | 3.4% |
| BINARY_SUBSCR_LIST_INT | 282,366 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 23,928,593 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,202,860 | 40.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,270 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 40,906 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 17,882,671 | 41.7% |
| STORE_FAST | 10,859,734 | 25.3% |
| TO_BOOL | 10,287,220 | 24.0% |
| PUSH_NULL | 2,128,620 | 5.0% |
| RETURN_VALUE | 1,500,147 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,880 | 94.4% |
| LOAD_FAST | 135,000 | 2.6% |
| BINARY_OP | 119,085 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,160 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 127,900 | 2.5% |
| CALL_BUILTIN_CLASS | 119,085 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,702,221 | 41.7% |
| RETURN_GENERATOR | 10,164,628 | 27.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,612,426 | 14.9% |
| LOAD_ATTR_SLOT | 4,880,185 | 13.0% |
| BINARY_OP | 1,095,122 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,587,807 | 36.1% |
| RETURN_VALUE | 11,432,831 | 30.4% |
| TO_BOOL_BOOL | 9,842,342 | 26.2% |
| GET_ITER | 2,591,126 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 29,352,061 | 54.3% |
| LOAD_GLOBAL_BUILTIN | 17,191,195 | 31.8% |
| LOAD_DEREF | 2,859,623 | 5.3% |
| LOAD_FAST_LOAD_FAST | 2,648,591 | 4.9% |
| LOAD_FAST | 1,614,968 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 51,183,165 | 94.7% |
| YIELD_VALUE | 2,232,694 | 4.1% |
| COPY | 525,020 | 1.0% |
| RETURN_VALUE | 71,525 | 0.1% |
| TO_BOOL | 9,665 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,053,823 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 173,720 | 0.6% |
| RETURN_VALUE | 95,094 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,270,357 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,676,060 | 34.5% |
| LOAD_CONST | 7,178,270 | 25.6% |
| CALL_BUILTIN_CLASS | 611,137 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,553,505 | 64.8% |
| BUILD_TUPLE | 3,214,240 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 963,240 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 17,314,146 | 72.1% |
| EXTENDED_ARG | 4,571,158 | 19.0% |
| LOAD_FAST | 1,681,753 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |
| JUMP_FORWARD | 191,880 | 0.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,845,058 | 45.2% |
| ENTER_EXECUTOR | 5,140,355 | 23.6% |
| LOAD_CONST | 2,332,335 | 10.7% |
| BUILD_LIST | 2,294,391 | 10.5% |
| BUILD_MAP | 1,561,360 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,687,890 | 58.3% |
| STORE_FAST | 3,361,366 | 15.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.3% |
| POP_TOP | 908,816 | 4.2% |
| GET_ITER | 737,591 | 3.4% |


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
| LOAD_ATTR_METHOD_NO_DICT | 22,646,304 | 81.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,719 | 17.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,791 | 0.4% |
| LOAD_ATTR | 72,820 | 0.3% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 12,589,458 | 45.5% |
| STORE_FAST | 9,688,223 | 35.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,880 | 17.7% |
| CALL_BUILTIN_CLASS | 169,731 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,791 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.3% |
| LOAD_CONST | 1,226,485 | 26.8% |
| LOAD_FAST | 290,680 | 6.3% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.5% |
| LOAD_CONST | 1,224,485 | 26.7% |
| TO_BOOL_NONE | 42,400 | 0.9% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,793,140 | 39.5% |
| LOAD_FAST | 15,185,244 | 28.8% |
| LOAD_FAST_LOAD_FAST | 6,084,393 | 11.6% |
| GET_ITER | 6,004,338 | 11.4% |
| LOAD_SUPER_ATTR_METHOD | 1,539,392 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 42,870,809 | 81.4% |
| COPY_FREE_VARS | 4,700,760 | 8.9% |
| RETURN_GENERATOR | 4,117,190 | 7.8% |
| MAKE_CELL | 768,616 | 1.5% |
| CALL_PY_EXACT_ARGS | 145,227 | 0.3% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,621,783 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,373,932 | 29.9% |
| ENTER_EXECUTOR | 1,014,489 | 22.1% |
| RETURN_VALUE | 192,605 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,850 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,372,977 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,725 | 1.2% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,160 | 80.5% |
| LOAD_FAST | 1,014,992 | 17.4% |
| STORE_FAST | 105,752 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,132 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,360 | 80.5% |
| BINARY_SUBSCR_DICT | 441,520 | 7.5% |
| STORE_FAST | 353,192 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,728,879 | 99.5% |
| LOAD_CONST | 65,970 | 0.4% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,082 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,687 | 43.4% |
| COMPARE_OP | 5,882,565 | 39.8% |
| LOAD_ATTR | 2,352,272 | 15.9% |
| IS_OP | 64,230 | 0.4% |
| STORE_FAST | 32,971 | 0.2% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,683 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,614 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,077 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,725,036 | 42.6% |
| LOAD_FAST_LOAD_FAST | 16,119,432 | 33.2% |
| CALL_LEN | 10,270,357 | 21.1% |
| LOAD_FAST | 971,252 | 2.0% |
| LOAD_ATTR_SLOT | 225,419 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,131,534 | 68.2% |
| BINARY_OP | 6,273,260 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.8% |
| EXTENDED_ARG | 1,718,052 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,534,520 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 69.1% |
| LOAD_CONST | 4,296,077 | 29.6% |
| LOAD_GLOBAL_MODULE | 192,469 | 1.3% |
| LOAD_FAST | 2,040 | 0.0% |
| LOAD_ATTR | 1,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,480,666 | 99.7% |
| YIELD_VALUE | 40,140 | 0.3% |
| POP_JUMP_IF_TRUE | 2,080 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,564 | 52.6% |
| GET_ITER | 90,692 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,644 | 52.1% |
| POP_TOP | 90,532 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,265,974 | 41.4% |
| LOAD_FAST | 4,844,129 | 21.6% |
| GET_ITER | 4,313,992 | 19.3% |
| EXTENDED_ARG | 2,686,869 | 12.0% |
| SWAP | 1,219,678 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,052,519 | 40.4% |
| RETURN_CONST | 5,672,272 | 25.3% |
| LOAD_FAST | 4,094,199 | 18.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,492,008 | 6.7% |
| STORE_FAST_LOAD_FAST | 1,260,342 | 5.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 827,432 | 37.2% |
| GET_ITER | 669,189 | 30.1% |
| EXTENDED_ARG | 642,400 | 28.9% |
| SWAP | 38,880 | 1.7% |
| LOAD_FAST | 29,360 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,869 | 58.7% |
| RETURN_CONST | 630,357 | 28.3% |
| LOAD_FAST | 195,180 | 8.8% |
| STORE_FAST_LOAD_FAST | 47,440 | 2.1% |
| SWAP | 38,520 | 1.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,948,890 | 48.9% |
| ENTER_EXECUTOR | 8,726,110 | 42.9% |
| EXTENDED_ARG | 767,880 | 3.8% |
| LOAD_FAST | 518,381 | 2.5% |
| SWAP | 299,351 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,208,322 | 50.2% |
| LOAD_FAST | 7,494,643 | 36.8% |
| RETURN_CONST | 788,616 | 3.9% |
| LOAD_GLOBAL_MODULE | 602,506 | 3.0% |
| STORE_FAST_LOAD_FAST | 409,217 | 2.0% |


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
| LOAD_FAST | 5,478,912 | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,805 | 11.7% |
| LOAD_DEREF | 1,058,265 | 11.7% |
| COPY | 956,400 | 10.6% |
| LOAD_GLOBAL_MODULE | 481,659 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,425 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,270 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,224,985 | 13.5% |
| STORE_FAST | 1,075,965 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,805 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,128,020 | 84.7% |
| RETURN_VALUE | 4,635,896 | 5.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.6% |
| LOAD_GLOBAL_MODULE | 1,964,787 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,425 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,560,668 | 34.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 22,646,304 | 26.2% |
| CALL_PY_EXACT_ARGS | 20,793,140 | 24.1% |
| LOAD_CONST | 4,050,538 | 4.7% |
| LOAD_DEREF | 3,319,044 | 3.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 9,497,003 | 52.9% |
| LOAD_ATTR_SLOT | 4,711,260 | 26.2% |
| LOAD_FAST | 3,527,488 | 19.6% |
| LOAD_ATTR | 147,517 | 0.8% |
| STORE_FAST_LOAD_FAST | 45,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,775,972 | 54.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,719 | 26.8% |
| LOAD_FAST_LOAD_FAST | 3,042,491 | 16.9% |
| CALL_PY_EXACT_ARGS | 317,799 | 1.8% |
| LOAD_CONST | 7,036 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260,798 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,403 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,216 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,645 | 6.3% |
| CALL | 57,380 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR_SLOT | 15,920 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,060,836 | 83.2% |
| ENTER_EXECUTOR | 5,159,256 | 9.1% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 212,617 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,047,053 | 74.4% |
| CALL_BUILTIN_O | 5,612,426 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,921,347 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,676 | 3.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 987,773 | 60.0% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.1% |
| LOAD_DEREF | 144,340 | 8.8% |
| ENTER_EXECUTOR | 14,408 | 0.9% |
| LOAD_ATTR | 12,020 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.1% |
| TO_BOOL_STR | 478,200 | 29.1% |
| TO_BOOL_BOOL | 408,890 | 24.8% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,064,246 | 89.5% |
| ENTER_EXECUTOR | 1,562,082 | 5.6% |
| RETURN_VALUE | 642,641 | 2.3% |
| STORE_FAST_LOAD_FAST | 191,465 | 0.7% |
| LOAD_DEREF | 190,726 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,813,740 | 67.2% |
| COPY_FREE_VARS | 5,066,436 | 18.1% |
| GET_ITER | 1,919,981 | 6.9% |
| TO_BOOL_BOOL | 711,952 | 2.5% |
| STORE_FAST | 506,314 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,057,646 | 98.5% |
| ENTER_EXECUTOR | 632,600 | 0.7% |
| LOAD_ATTR_SLOT | 613,656 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,054 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 69,996 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,432,500 | 35.0% |
| STORE_FAST | 22,510,349 | 23.6% |
| LOAD_DEREF | 6,404,508 | 6.7% |
| LOAD_FAST | 5,219,803 | 5.5% |
| LOAD_CONST | 5,210,281 | 5.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,849,587 | 27.8% |
| RESUME_CHECK | 41,195,157 | 19.8% |
| STORE_FAST | 29,940,901 | 14.4% |
| LOAD_FAST | 18,550,732 | 8.9% |
| CALL_LEN | 9,676,060 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,535,690 | 67.6% |
| LOAD_FAST_LOAD_FAST | 28,347,174 | 13.6% |
| CALL_ISINSTANCE | 17,191,195 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 8,864,555 | 4.3% |
| LOAD_DEREF | 3,164,271 | 1.5% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,676,987 | 46.9% |
| RESUME_CHECK | 16,025,986 | 14.5% |
| STORE_FAST | 11,162,445 | 10.1% |
| POP_JUMP_IF_FALSE | 9,672,592 | 8.8% |
| NOP | 6,377,498 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 33,545,746 | 30.4% |
| CALL_ISINSTANCE | 29,352,061 | 26.6% |
| LOAD_FAST | 28,279,266 | 25.7% |
| LOAD_DEREF | 3,256,393 | 3.0% |
| LOAD_FAST_LOAD_FAST | 3,201,813 | 2.9% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,559 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,181,959 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,640 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,392 | 85.1% |
| LOAD_GLOBAL_MODULE | 172,248 | 9.5% |
| LOAD_FAST | 78,580 | 4.3% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 99,063,108 | 39.6% |
| CALL_PY_EXACT_ARGS | 42,870,809 | 17.1% |
| COPY_FREE_VARS | 21,669,969 | 8.7% |
| LOAD_ATTR_PROPERTY | 18,813,740 | 7.5% |
| POP_TOP | 14,298,515 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,509,831 | 46.2% |
| LOAD_GLOBAL_BUILTIN | 41,195,157 | 16.5% |
| NOP | 21,364,180 | 8.5% |
| LOAD_GLOBAL_MODULE | 16,025,986 | 6.4% |
| LOAD_CONST | 15,611,190 | 6.2% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 661,220 | 64.2% |
| LOAD_CONST | 367,996 | 35.7% |
| SEND | 620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 646,240 | 62.8% |
| POP_TOP | 352,936 | 34.3% |
| YIELD_VALUE | 15,060 | 1.5% |
| END_SEND | 15,020 | 1.5% |
| SEND | 580 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,760 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,131 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,697 | 36.0% |
| RETURN_CONST | 887,386 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,142 | 52.2% |
| LOAD_FAST | 4,284,715 | 47.3% |
| STORE_ATTR_SLOT | 41,801 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,672,922 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,110 | 24.9% |
| LOAD_CONST | 1,890,608 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,857 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,568,591 | 68.9% |
| LOAD_FAST | 396,612 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,331 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,647,163 | 72.4% |
| EXTENDED_ARG | 226,740 | 10.0% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.1% |
| LOAD_FAST | 164,822 | 7.2% |
| LOAD_GLOBAL_MODULE | 38,951 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,851,870 | 93.9% |
| SWAP | 1,063,080 | 5.3% |
| LOAD_FAST | 98,933 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |
| LOAD_CONST | 20,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,020,209 | 49.9% |
| ENTER_EXECUTOR | 9,994,814 | 49.8% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |
| LOAD_CONST | 19,800 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 224,407 | 98.5% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| ENTER_EXECUTOR | 860 | 0.4% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| TO_BOOL | 389 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 216,425 | 95.0% |
| POP_JUMP_IF_FALSE | 9,935 | 4.4% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 56 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 51,183,165 | 32.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,047,053 | 26.4% |
| LOAD_FAST | 21,598,992 | 13.5% |
| CALL_BUILTIN_FAST | 17,882,671 | 11.2% |
| CALL_BUILTIN_O | 9,842,342 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 105,275,949 | 66.0% |
| POP_JUMP_IF_TRUE | 48,082,755 | 30.1% |
| EXTENDED_ARG | 5,063,493 | 3.2% |
| UNARY_NOT | 1,084,973 | 0.7% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,625,581 | 95.3% |
| BINARY_OP | 722,185 | 3.9% |
| BINARY_SUBSCR_TUPLE_INT | 63,305 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,280 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,868 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,350,631 | 55.9% |
| POP_JUMP_IF_TRUE | 8,150,949 | 44.1% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 167 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,228,248 | 97.5% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,105 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |
| TO_BOOL | 2,147 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 823,279 | 36.0% |
| POP_JUMP_IF_TRUE | 784,530 | 34.3% |
| UNARY_NOT | 661,871 | 29.0% |
| EXTENDED_ARG | 15,720 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,757 | 69.6% |
| RETURN_VALUE | 389,243 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,254 | 11.1% |
| CALL_METHOD_DESCRIPTOR_O | 42,400 | 1.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,949 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,938,385 | 73.2% |
| POP_JUMP_IF_TRUE | 689,963 | 26.1% |
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
| LOAD_FAST | 120,311 | 67.4% |
| RETURN_VALUE | 49,120 | 27.5% |
| CALL_BUILTIN_CLASS | 2,600 | 1.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 1.0% |
| BINARY_SUBSCR_LIST_INT | 1,240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 64.4% |
| STORE_FAST_STORE_FAST | 63,631 | 35.6% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 884,865 | 55.6% |
| RETURN_VALUE | 660,897 | 41.5% |
| STORE_FAST | 40,240 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,396,890 | 87.8% |
| STORE_FAST | 154,752 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 24,687,697 | 52.9% |
| RETURN_VALUE | 19,465,580 | 41.7% |
| FOR_ITER_LIST | 1,492,008 | 3.2% |
| BINARY_SUBSCR_LIST_INT | 534,640 | 1.1% |
| FOR_ITER_TUPLE | 285,870 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 42,872,297 | 91.9% |
| STORE_DEREF | 3,577,880 | 7.7% |
| STORE_FAST | 215,315 | 0.5% |
| UNPACK_SEQUENCE_LIST | 1,760 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,320 | 0.0% |


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
|     deferred | 34,031,569 | 78.0% |
|          hit | 9,528,216 | 21.8% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,778 | 11.8% |
| Failure | 50,482 | 88.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,464 | 18.7% |
| multiply different types | 7,163 | 14.2% |
| subtract other | 6,740 | 13.4% |
| and int | 4,124 | 8.2% |
| rshift | 3,807 | 7.5% |
| or | 3,700 | 7.3% |
| power | 2,861 | 5.7% |
| true divide different types | 2,523 | 5.0% |
| multiply other | 2,260 | 4.5% |
| remainder | 2,074 | 4.1% |
| add different types | 1,821 | 3.6% |
| floor divide | 1,272 | 2.5% |
| subtract different types | 1,186 | 2.3% |
| xor | 583 | 1.2% |
| and other | 374 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 227 | 0.4% |
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
|     deferred | 20,178,606 | 37.1% |
|          hit | 34,208,282 | 62.9% |
|         miss | 14,924 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,717 | 34.4% |
| Failure | 14,722 | 65.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 11,419 | 77.6% |
| out of range | 1,960 | 13.3% |
| buffer int | 1,320 | 9.0% |
| array int | 20 | 0.1% |
| tuple slice | 3 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,100,083 | 6.7% |
|        deopt | 22,840 | 0.0% |
|          hit | 330,160,402 | 85.0% |
|         miss | 31,305,444 | 8.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 671,132 | 90.2% |
| Failure | 73,057 | 9.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,799 | 39.4% |
| code complex parameters | 14,051 | 19.2% |
| class no vectorcall | 9,220 | 12.6% |
| cfunc varargs keywords | 6,385 | 8.7% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.4% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,170 | 3.0% |
| meth descr varargs | 1,912 | 2.6% |
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
|     deferred | 36,761,827 | 36.6% |
|          hit | 63,086,478 | 62.8% |
|         miss | 575,975 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,472 | 22.9% |
| Failure | 68,807 | 77.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,415 | 26.8% |
| other | 15,217 | 22.1% |
| different types | 12,187 | 17.7% |
| tuple | 10,050 | 14.6% |
| string | 9,960 | 14.5% |
| bool | 1,778 | 2.6% |
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
|     deferred | 34,227,291 | 43.1% |
|          hit | 44,714,211 | 56.3% |
|         miss | 447,015 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,302 | 27.5% |
| Failure | 53,521 | 72.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 34,374 | 64.2% |
| zip | 4,980 | 9.3% |
| set | 4,442 | 8.3% |
| enumerate | 3,565 | 6.7% |
| other | 1,980 | 3.7% |
| itertools | 1,840 | 3.4% |
| dict keys | 1,400 | 2.6% |
| reversed list | 780 | 1.5% |
| dict values | 80 | 0.1% |
| ascii string | 80 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 90,405,848 | 23.3% |
|        deopt | 20 | 0.0% |
|          hit | 230,882,068 | 59.4% |
|         miss | 65,671,153 | 16.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,316,840 | 89.7% |
| Failure | 151,714 | 10.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mutable class | 58,666 | 38.7% |
| metaclass attribute | 53,190 | 35.1% |
| method | 10,383 | 6.8% |
| overridden | 8,667 | 5.7% |
| has managed dict | 8,580 | 5.7% |
| shadowed | 5,300 | 3.5% |
| class method obj | 3,880 | 2.6% |
| builtin class method | 1,320 | 0.9% |
| not managed dict | 748 | 0.5% |
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
|     deferred | 89,886 | 0.0% |
|          hit | 318,225,922 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,990 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 605 | 0.0% |
|          hit | 2,990,099 | 100.0% |

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
|          hit | 999,176 | 67.8% |
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
|     deferred | 540,590 | 4.2% |
|          hit | 10,195,983 | 78.4% |
|         miss | 2,222,626 | 17.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,861 | 92.3% |
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
|     deferred | 1,999,056 | 8.2% |
|          hit | 22,362,741 | 91.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,724 | 44.8% |
| Failure | 3,363 | 55.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 3,363 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,813,920 | 6.5% |
|          hit | 183,234,241 | 93.2% |
|         miss | 440,426 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,944 | 72.3% |
| Failure | 22,965 | 27.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,784 | 47.0% |
| number | 3,523 | 15.3% |
| mapping | 3,300 | 14.4% |
| dict | 2,260 | 9.8% |
| other | 1,627 | 7.1% |
| set | 1,431 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,555 | 0.1% |
|          hit | 48,439,865 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,392 | 93.6% |
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
| Basic | 2,682,804,953 | 54.1% |
| Not specialized | 638,064,870 | 12.9% |
| Specialized hits | 1,534,759,650 | 31.0% |
| Specialized misses | 100,728,803 | 2.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 90,405,848 | 35.1% |
| COMPARE_OP | 36,761,827 | 14.3% |
| FOR_ITER | 34,227,291 | 13.3% |
| BINARY_OP | 34,031,569 | 13.2% |
| CALL | 26,100,083 | 10.1% |
| BINARY_SUBSCR | 20,178,606 | 7.8% |
| TO_BOOL | 12,813,920 | 5.0% |
| STORE_SUBSCR | 1,999,056 | 0.8% |
| STORE_ATTR | 540,590 | 0.2% |
| SEND | 439,140 | 0.2% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,448,121 | 36.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,596,208 | 15.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,272,813 | 14.2% |
| LOAD_ATTR_METHOD_NO_DICT | 9,031,310 | 9.0% |
| CALL_PY_EXACT_ARGS | 7,816,649 | 7.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,471 | 6.4% |
| LOAD_ATTR_PROPERTY | 4,107,324 | 4.1% |
| CALL_BUILTIN_O | 2,661,173 | 2.6% |
| STORE_ATTR_SLOT | 2,221,646 | 2.2% |
| COMPARE_OP_INT | 574,375 | 0.6% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,452,257 | 51.5% |
| Calls to Python functions inlined | 120,214,370 | 48.5% |
| Calls via PyEval_EvalFrame (total) | 127,452,257 | 51.5% |
| Calls via PyEval_EvalFrame (vector) | 98,449,413 | 39.8% |
| Calls via PyEval_EvalFrame (generator) | 29,002,844 | 11.7% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,442,113 | 39.7% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,241 | 9.6% |
| Calls via PyEval_EvalFrame (function ex) | 11,824,930 | 4.8% |
| Calls via PyEval_EvalFrame (api) | 53,322,133 | 21.5% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,177 | 0.5% |
| Frames pushed | 112,408,814 | 45.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,322,235 | 54.3% |
| Frees to freelist | 363,565,167 |  |
| Allocations | 305,447,417 | 45.7% |
| Allocations to 512 bytes | 304,390,148 | 45.5% |
| Allocations to 4 kbytes | 1,032,809 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,118,744 |  |
| New values | 1,057,393 |  |
| Interpreter increfs | 2,684,515,120 | 65.3% |
| Interpreter decrefs | 3,109,263,536 | 66.2% |
| Increfs | 1,428,555,938 | 34.7% |
| Decrefs | 1,584,330,943 | 33.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,906,816 |  |
| Method cache misses | 3,859,361 |  |
| Method cache collisions | 5,009,428 |  |
| Method cache dunder hits | 346,895,280 |  |
| Method cache dunder misses | 1,150,747 |  |


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
| Optimization attempts | 14,039 |  |
| Traces created | 13,279 | 94.6% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 240 | 1.7% |
| Trace too long | 0 | 0.0% |
| Trace too short | 760 | 5.4% |
| Inner loop found | 280 | 2.0% |
| Recursive call | 160 | 1.1% |
| Traces executed | 118,530,623 |  |
| Uops executed | 2,207,395,235 | 18.62 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 2,667 | 20.1% |
| <= 32 | 5,254 | 39.6% |
| <= 64 | 3,680 | 27.7% |
| <= 128 | 1,264 | 9.5% |
| <= 256 | 394 | 3.0% |
| <= 512 | 20 | 0.2% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,647 | 19.9% |
| <= 16 | 4,324 | 32.6% |
| <= 32 | 3,968 | 29.9% |
| <= 64 | 1,966 | 14.8% |
| <= 128 | 314 | 2.4% |
| <= 256 | 60 | 0.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 2,058,311 | 1.7% |
| <= 2 | 28,370,648 | 23.9% |
| <= 4 | 737,972 | 0.6% |
| <= 8 | 23,142,419 | 19.5% |
| <= 16 | 13,625,590 | 11.5% |
| <= 32 | 34,390,110 | 29.0% |
| <= 64 | 12,119,400 | 10.2% |
| <= 128 | 2,695,449 | 2.3% |
| <= 256 | 1,232,409 | 1.0% |
| <= 512 | 149,364 | 0.1% |
| <= 1,024 | 4,341 | 0.0% |
| <= 2,048 | 4,110 | 0.0% |
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
| _SET_IP | 318,234,293 | 14.4% | 14.4% |  |
| _CHECK_VALIDITY | 263,851,979 | 12.0% | 26.4% |  |
| LOAD_FAST | 245,465,839 | 11.1% | 37.5% |  |
| STORE_FAST | 188,746,620 | 8.6% | 46.0% |  |
| _FOR_ITER_TIER_TWO | 70,593,322 | 3.2% | 49.2% | 22.4% |
| _GUARD_GLOBALS_VERSION | 61,806,541 | 2.8% | 52.0% | 0.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 56,861,716 | 2.6% | 54.6% |  |
| _ITER_CHECK_LIST | 50,400,438 | 2.3% | 56.9% | 2.2% |
| _GUARD_NOT_EXHAUSTED_LIST | 49,300,647 | 2.2% | 59.1% | 19.6% |
| _GUARD_IS_FALSE_POP | 42,486,584 | 1.9% | 61.1% | 19.9% |
| _ITER_NEXT_LIST | 39,637,456 | 1.8% | 62.9% |  |
| CONTAINS_OP | 39,288,208 | 1.8% | 64.6% |  |
| _EXIT_TRACE | 38,157,301 | 1.7% | 66.4% |  |
| _JUMP_TO_TOP | 37,462,229 | 1.7% | 68.1% |  |
| _LOAD_GLOBAL_MODULE | 35,527,473 | 1.6% | 69.7% |  |
| _LOAD_ATTR | 29,839,856 | 1.4% | 71.0% |  |
| _GUARD_TYPE_VERSION | 26,690,633 | 1.2% | 72.2% | 21.3% |
| _GUARD_BUILTINS_VERSION | 25,779,045 | 1.2% | 73.4% |  |
| _LOAD_GLOBAL_BUILTINS | 25,779,045 | 1.2% | 74.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 24,450,942 | 1.1% | 75.7% | 0.2% |
| _CHECK_PEP_523 | 24,450,942 | 1.1% | 76.8% |  |
| _CHECK_STACK_SPACE | 24,411,354 | 1.1% | 77.9% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 24,408,954 | 1.1% | 79.0% |  |
| _PUSH_FRAME | 24,408,954 | 1.1% | 80.1% |  |
| _SAVE_RETURN_OFFSET | 24,408,954 | 1.1% | 81.2% |  |
| _ITER_CHECK_TUPLE | 23,763,786 | 1.1% | 82.3% | 4.0% |
| LOAD_CONST | 22,831,438 | 1.0% | 83.3% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 22,805,266 | 1.0% | 84.3% | 38.9% |
| PUSH_NULL | 17,982,305 | 0.8% | 85.2% |  |
| LOAD_DEREF | 17,937,516 | 0.8% | 86.0% |  |
| _GUARD_IS_TRUE_POP | 17,502,722 | 0.8% | 86.8% | 27.9% |
| _GUARD_IS_NOT_NONE_POP | 16,728,700 | 0.8% | 87.5% | 90.6% |
| BUILD_TUPLE | 14,691,609 | 0.7% | 88.2% |  |
| _ITER_NEXT_TUPLE | 13,938,250 | 0.6% | 88.8% |  |
| CALL_ISINSTANCE | 13,429,914 | 0.6% | 89.4% |  |
| TO_BOOL_BOOL | 13,166,575 | 0.6% | 90.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 12,765,265 | 0.6% | 90.6% |  |
| _GUARD_KEYS_VERSION | 12,765,265 | 0.6% | 91.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 12,763,405 | 0.6% | 91.8% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 10,734,804 | 0.5% | 92.2% | 7.7% |
| _ITER_CHECK_RANGE | 10,734,804 | 0.5% | 92.7% |  |
| _ITER_NEXT_RANGE | 9,907,372 | 0.4% | 93.2% |  |
| GET_ITER | 9,342,549 | 0.4% | 93.6% |  |
| _GUARD_BOTH_INT | 9,262,812 | 0.4% | 94.0% |  |
| _BINARY_OP_ADD_INT | 9,235,752 | 0.4% | 94.4% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 9,162,510 | 0.4% | 94.9% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 9,162,510 | 0.4% | 95.3% |  |
| _GUARD_IS_NONE_POP | 8,951,458 | 0.4% | 95.7% | 35.2% |
| MAKE_FUNCTION | 8,874,154 | 0.4% | 96.1% |  |
| BINARY_SUBSCR_LIST_INT | 8,160,535 | 0.4% | 96.5% | 0.2% |
| RESUME_CHECK | 7,620,363 | 0.3% | 96.8% |  |
| SET_FUNCTION_ATTRIBUTE | 7,015,772 | 0.3% | 97.1% |  |
| BUILD_MAP | 6,645,691 | 0.3% | 97.4% |  |
| DICT_MERGE | 6,636,012 | 0.3% | 97.7% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 5,278,900 | 0.2% | 98.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,266,675 | 0.2% | 98.2% | 97.6% |
| LIST_APPEND | 3,631,195 | 0.2% | 98.4% |  |
| _BINARY_SUBSCR | 3,522,601 | 0.2% | 98.5% |  |
| _POP_FRAME | 3,063,954 | 0.1% | 98.7% |  |
| COMPARE_OP_INT | 2,510,676 | 0.1% | 98.8% | 0.0% |
| IS_OP | 2,318,034 | 0.1% | 98.9% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,301,985 | 0.1% | 99.0% |  |
| CALL_BUILTIN_O | 2,210,765 | 0.1% | 99.1% |  |
| SWAP | 2,152,760 | 0.1% | 99.2% |  |
| CALL_TYPE_1 | 1,915,005 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,887,020 | 0.1% | 99.3% |  |
| LOAD_FAST_AND_CLEAR | 1,831,200 | 0.1% | 99.4% |  |
| _COMPARE_OP | 1,599,731 | 0.1% | 99.5% |  |
| POP_TOP | 1,442,391 | 0.1% | 99.6% |  |
| _STORE_SUBSCR | 1,423,223 | 0.1% | 99.6% |  |
| _BINARY_OP | 1,236,175 | 0.1% | 99.7% |  |
| TO_BOOL_INT | 1,192,540 | 0.1% | 99.7% | 0.0% |
| BUILD_LIST | 1,142,420 | 0.1% | 99.8% |  |
| STORE_DEREF | 993,576 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 669,029 | 0.0% | 99.9% |  |
| _LOAD_ATTR_SLOT | 533,773 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST | 439,069 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 297,330 | 0.0% | 99.9% |  |
| COPY | 295,549 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 256,900 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 146,035 | 0.0% | 100.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 112,578 | 0.0% | 100.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 112,578 | 0.0% | 100.0% |  |
| LOAD_NAME | 107,280 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 80,252 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 63,280 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 61,600 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 40,980 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 39,280 | 0.0% | 100.0% |  |
| STORE_NAME | 36,700 | 0.0% | 100.0% |  |
| UNARY_NOT | 33,712 | 0.0% | 100.0% |  |
| _TO_BOOL | 27,819 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,800 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 16,660 | 0.0% | 100.0% |  |
| CALL_LEN | 16,098 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 13,680 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 13,380 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 11,920 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 11,920 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 10,680 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 6,908 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 6,000 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 5,760 | 0.0% | 100.0% |  |
| BINARY_SLICE | 5,040 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 2,560 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,920 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 1,920 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,860 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 1,840 | 0.0% | 100.0% | 46.7% |
| UNPACK_SEQUENCE_LIST | 1,500 | 0.0% | 100.0% |  |
| STORE_SLICE | 1,220 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,220 | 0.0% | 100.0% |  |
| BUILD_STRING | 960 | 0.0% | 100.0% |  |
| SET_ADD | 960 | 0.0% | 100.0% |  |
| MAP_ADD | 700 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 240 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 240 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| LOAD_ATTR_PROPERTY | 2,987 |
| YIELD_VALUE | 1,120 |
| CALL | 1,014 |
| FOR_ITER_GEN | 760 |
| CALL_FUNCTION_EX | 640 |
| CALL_PY_WITH_DEFAULTS | 580 |
| CALL_LIST_APPEND | 480 |
| CALL_KW | 420 |
| BINARY_SUBSCR_GETITEM | 240 |
| IMPORT_NAME | 40 |


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
Stats gathered on: 2023-11-19
