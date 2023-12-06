
# Pystats results

- benchmark: sympy
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 899,666,746 | 16.6% | 16.6% |  |
| STORE_FAST | 295,437,052 | 5.5% | 22.1% |  |
| RESUME_CHECK | 257,434,850 | 4.8% | 26.9% |  |
| POP_JUMP_IF_FALSE | 256,939,651 | 4.8% | 31.6% |  |
| LOAD_FAST_LOAD_FAST | 228,662,171 | 4.2% | 35.9% |  |
| LOAD_GLOBAL_BUILTIN | 225,873,620 | 4.2% | 40.0% | 0.0% |
| LOAD_CONST | 178,852,305 | 3.3% | 43.3% |  |
| RETURN_VALUE | 177,416,725 | 3.3% | 46.6% |  |
| TO_BOOL_BOOL | 169,317,860 | 3.1% | 49.8% | 0.1% |
| INTERPRETER_EXIT | 127,463,380 | 2.4% | 52.1% |  |
| LOAD_GLOBAL_MODULE | 117,774,204 | 2.2% | 54.3% | 0.0% |
| STORE_FAST_STORE_FAST | 104,215,656 | 1.9% | 56.2% |  |
| FOR_ITER | 103,836,549 | 1.9% | 58.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 101,332,444 | 1.9% | 60.0% |  |
| LOAD_ATTR_SLOT | 95,514,103 | 1.8% | 61.8% | 38.2% |
| LOAD_ATTR | 91,952,028 | 1.7% | 63.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 89,534,766 | 1.7% | 65.1% | 10.2% |
| POP_JUMP_IF_TRUE | 72,015,628 | 1.3% | 66.5% |  |
| JUMP_BACKWARD | 69,912,461 | 1.3% | 67.8% |  |
| CALL_PY_EXACT_ARGS | 67,030,715 | 1.2% | 69.0% | 11.7% |
| LOAD_DEREF | 63,132,500 | 1.2% | 70.2% |  |
| CALL_ISINSTANCE | 62,516,618 | 1.2% | 71.3% |  |
| POP_TOP | 61,692,312 | 1.1% | 72.5% |  |
| ENTER_EXECUTOR | 61,020,127 | 1.1% | 73.6% |  |
| GET_ITER | 59,469,430 | 1.1% | 74.7% |  |
| RETURN_CONST | 56,892,849 | 1.1% | 75.8% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,727,716 | 1.0% | 76.8% | 27.6% |
| BUILD_TUPLE | 50,256,613 | 0.9% | 77.7% |  |
| COMPARE_OP_INT | 48,730,122 | 0.9% | 78.6% | 1.2% |
| IS_OP | 45,492,543 | 0.8% | 79.5% |  |
| SWAP | 45,033,687 | 0.8% | 80.3% |  |
| CALL_BUILTIN_FAST | 43,259,639 | 0.8% | 81.1% |  |
| PUSH_NULL | 42,922,869 | 0.8% | 81.9% |  |
| POP_JUMP_IF_NONE | 40,803,547 | 0.8% | 82.7% |  |
| COMPARE_OP | 38,148,078 | 0.7% | 83.4% |  |
| CALL_BUILTIN_O | 37,655,903 | 0.7% | 84.1% | 7.1% |
| BINARY_OP | 35,202,287 | 0.7% | 84.7% |  |
| COPY_FREE_VARS | 31,754,328 | 0.6% | 85.3% |  |
| NOP | 31,478,055 | 0.6% | 85.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 30,179,090 | 0.6% | 86.4% | 0.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,480,186 | 0.5% | 87.0% | 22.0% |
| BINARY_SUBSCR_LIST_INT | 29,010,600 | 0.5% | 87.5% | 0.0% |
| CALL_LEN | 28,084,523 | 0.5% | 88.0% |  |
| CALL_FUNCTION_EX | 28,013,533 | 0.5% | 88.6% |  |
| LOAD_ATTR_PROPERTY | 27,996,988 | 0.5% | 89.1% | 14.7% |
| BUILD_MAP | 27,215,927 | 0.5% | 89.6% |  |
| CALL | 26,838,504 | 0.5% | 90.1% |  |
| CALL_LIST_APPEND | 24,014,937 | 0.4% | 90.5% |  |
| YIELD_VALUE | 23,118,773 | 0.4% | 91.0% |  |
| BINARY_SUBSCR | 22,783,296 | 0.4% | 91.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 22,053,795 | 0.4% | 91.8% | 65.7% |
| BUILD_LIST | 21,579,935 | 0.4% | 92.2% |  |
| STORE_SUBSCR_LIST_INT | 20,203,072 | 0.4% | 92.6% |  |
| TO_BOOL_INT | 19,038,078 | 0.4% | 92.9% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,111,063 | 0.3% | 93.2% |  |
| CONTAINS_OP | 17,975,768 | 0.3% | 93.6% |  |
| LOAD_FAST_AND_CLEAR | 16,788,643 | 0.3% | 93.9% |  |
| DICT_MERGE | 16,700,970 | 0.3% | 94.2% |  |
| EXTENDED_ARG | 15,340,487 | 0.3% | 94.5% |  |
| CALL_TYPE_1 | 14,852,231 | 0.3% | 94.8% |  |
| COMPARE_OP_STR | 14,524,197 | 0.3% | 95.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,385,509 | 0.3% | 95.3% | 0.3% |
| RETURN_GENERATOR | 14,331,343 | 0.3% | 95.6% |  |
| FOR_ITER_LIST | 13,806,063 | 0.3% | 95.8% | 4.2% |
| TO_BOOL | 12,906,155 | 0.2% | 96.0% |  |
| MAKE_FUNCTION | 12,383,136 | 0.2% | 96.3% |  |
| FOR_ITER_TUPLE | 12,078,172 | 0.2% | 96.5% | 6.8% |
| CALL_KW | 10,673,514 | 0.2% | 96.7% |  |
| SET_FUNCTION_ATTRIBUTE | 10,366,571 | 0.2% | 96.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,087,392 | 0.2% | 97.1% | 0.0% |
| STORE_ATTR_SLOT | 9,060,411 | 0.2% | 97.2% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,985,660 | 0.2% | 97.4% | 0.1% |
| IMPORT_FROM | 8,955,339 | 0.2% | 97.6% |  |
| CALL_BUILTIN_CLASS | 8,539,023 | 0.2% | 97.7% |  |
| MAP_ADD | 7,867,253 | 0.1% | 97.9% |  |
| IMPORT_NAME | 7,760,045 | 0.1% | 98.0% |  |
| STORE_DEREF | 7,702,430 | 0.1% | 98.1% |  |
| MAKE_CELL | 6,049,839 | 0.1% | 98.3% |  |
| CALL_TUPLE_1 | 5,851,471 | 0.1% | 98.4% | 0.0% |
| JUMP_FORWARD | 5,743,909 | 0.1% | 98.5% |  |
| UNARY_NOT | 5,273,929 | 0.1% | 98.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,789 | 0.1% | 98.7% | 0.1% |
| COPY | 4,626,642 | 0.1% | 98.8% |  |
| CALL_PY_WITH_DEFAULTS | 4,591,168 | 0.1% | 98.8% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,590,671 | 0.1% | 98.9% | 0.2% |
| BINARY_OP_ADD_INT | 3,747,609 | 0.1% | 99.0% |  |
| LIST_APPEND | 3,516,504 | 0.1% | 99.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,987 | 0.1% | 99.1% | 0.0% |
| STORE_SUBSCR | 3,357,163 | 0.1% | 99.2% |  |
| BINARY_SUBSCR_DICT | 3,167,527 | 0.1% | 99.2% |  |
| BINARY_OP_MULTIPLY_INT | 2,757,735 | 0.1% | 99.3% | 0.0% |
| TO_BOOL_NONE | 2,653,369 | 0.0% | 99.3% | 8.5% |
| BINARY_OP_SUBTRACT_INT | 2,475,520 | 0.0% | 99.4% |  |
| TO_BOOL_LIST | 2,294,427 | 0.0% | 99.4% | 0.5% |
| STORE_SUBSCR_DICT | 2,278,699 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,809,346 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,049 | 0.0% | 99.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,643,968 | 0.0% | 99.6% | 20.5% |
| UNPACK_SEQUENCE_TUPLE | 1,591,674 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,578,348 | 0.0% | 99.6% |  |
| FOR_ITER_RANGE | 1,396,801 | 0.0% | 99.7% |  |
| LIST_EXTEND | 1,349,291 | 0.0% | 99.7% |  |
| CALL_INTRINSIC_1 | 1,349,251 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,463 | 0.0% | 99.7% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,182,013 | 0.0% | 99.8% |  |
| SEND_GEN | 1,029,836 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,732 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,732 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,732 | 0.0% | 99.9% |  |
| STORE_ATTR | 591,451 | 0.0% | 99.9% |  |
| BINARY_SLICE | 569,049 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 557,220 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,668 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,416 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 533,192 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 502,880 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 228,352 | 0.0% | 100.0% | 36.3% |
| FOR_ITER_GEN | 191,376 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,749 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,518 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,256 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 132,500 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,323 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,112 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 72,620 | 0.0% | 100.0% |  |
| BUILD_SET | 50,488 | 0.0% | 100.0% |  |
| RESUME | 47,545 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,800 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,522 | 0.0% | 100.0% |  |
| SET_ADD | 19,280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,260 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,740 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,006 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,203 | 0.0% | 100.0% |  |
| STORE_SLICE | 920 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 159,722,751 | 3.0% | 3.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 156,054,080 | 2.9% | 5.8% |
| RESUME_CHECK LOAD_FAST | 115,538,967 | 2.1% | 8.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 109,008,279 | 2.0% | 10.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 107,888,141 | 2.0% | 12.0% |
| CACHE RESUME_CHECK | 99,250,055 | 1.8% | 13.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 97,529,966 | 1.8% | 15.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,120,791 | 1.7% | 17.4% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 76,804,393 | 1.4% | 18.8% |
| RETURN_VALUE INTERPRETER_EXIT | 72,899,398 | 1.3% | 20.1% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 71,145,329 | 1.3% | 21.5% |
| JUMP_BACKWARD FOR_ITER | 67,992,654 | 1.3% | 22.7% |
| LOAD_FAST LOAD_CONST | 60,553,668 | 1.1% | 23.8% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 59,512,725 | 1.1% | 24.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 58,113,164 | 1.1% | 26.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,682,334 | 1.1% | 27.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 54,161,019 | 1.0% | 28.1% |
| LOAD_FAST RETURN_VALUE | 52,944,066 | 1.0% | 29.1% |
| LOAD_FAST LOAD_ATTR | 51,081,748 | 0.9% | 30.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 50,471,484 | 0.9% | 30.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 50,121,474 | 0.9% | 31.9% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 49,466,215 | 0.9% | 32.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,246,111 | 0.8% | 33.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,266,196 | 0.8% | 34.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 40,973,251 | 0.8% | 35.1% |
| LOAD_CONST LOAD_CONST | 40,214,664 | 0.7% | 35.8% |
| RETURN_VALUE STORE_FAST | 38,557,667 | 0.7% | 36.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 36,026,095 | 0.7% | 37.2% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 35,787,835 | 0.7% | 37.9% |
| PUSH_NULL LOAD_FAST | 35,363,423 | 0.7% | 38.5% |
| LOAD_ATTR STORE_FAST | 34,997,161 | 0.6% | 39.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,503,678 | 0.6% | 39.8% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,432,997 | 0.6% | 40.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,148,643 | 0.6% | 41.0% |
| LOAD_FAST POP_JUMP_IF_NONE | 33,044,305 | 0.6% | 41.6% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 32,308,023 | 0.6% | 42.2% |
| RETURN_CONST INTERPRETER_EXIT | 32,283,499 | 0.6% | 42.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 30,792,830 | 0.6% | 43.4% |
| IS_OP POP_JUMP_IF_FALSE | 29,952,165 | 0.6% | 44.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 29,376,987 | 0.5% | 44.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 29,325,844 | 0.5% | 45.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 28,987,998 | 0.5% | 45.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,702,851 | 0.5% | 46.1% |
| LOAD_FAST CALL_LEN | 27,055,272 | 0.5% | 46.6% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 26,368,185 | 0.5% | 47.1% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,299,302 | 0.5% | 47.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 24,474,016 | 0.5% | 48.0% |
| BINARY_OP STORE_FAST | 24,166,006 | 0.4% | 48.5% |
| LOAD_CONST CALL_BUILTIN_FAST | 24,056,170 | 0.4% | 48.9% |
| LOAD_ATTR_SLOT STORE_FAST | 22,510,641 | 0.4% | 49.3% |
| YIELD_VALUE INTERPRETER_EXIT | 22,272,743 | 0.4% | 49.7% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_BUILTIN | 22,014,860 | 0.4% | 50.1% |
| COPY_FREE_VARS RESUME_CHECK | 21,786,567 | 0.4% | 50.5% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 21,716,693 | 0.4% | 51.0% |
| LOAD_FAST TO_BOOL_BOOL | 21,602,256 | 0.4% | 51.4% |
| STORE_FAST_STORE_FAST LOAD_DEREF | 21,546,211 | 0.4% | 51.7% |
| RESUME_CHECK NOP | 21,364,805 | 0.4% | 52.1% |
| LOAD_FAST GET_ITER | 21,271,649 | 0.4% | 52.5% |
| BUILD_TUPLE RETURN_VALUE | 21,220,806 | 0.4% | 52.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,062,216 | 0.4% | 53.3% |
| POP_JUMP_IF_NONE JUMP_BACKWARD | 20,910,017 | 0.4% | 53.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,793,038 | 0.4% | 54.1% |
| LOAD_CONST COMPARE_OP_INT | 20,732,083 | 0.4% | 54.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 20,354,526 | 0.4% | 54.9% |
| GET_ITER FOR_ITER | 19,848,386 | 0.4% | 55.2% |
| COMPARE_OP POP_JUMP_IF_FALSE | 19,737,318 | 0.4% | 55.6% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,465,580 | 0.4% | 55.9% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 19,321,142 | 0.4% | 56.3% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 19,059,235 | 0.4% | 56.7% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 18,938,567 | 0.4% | 57.0% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,852,214 | 0.3% | 57.4% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,813,486 | 0.3% | 57.7% |
| LOAD_FAST TO_BOOL_INT | 18,161,480 | 0.3% | 58.0% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 18,000,811 | 0.3% | 58.4% |
| LOAD_FAST PUSH_NULL | 17,306,420 | 0.3% | 58.7% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,262,403 | 0.3% | 59.0% |
| LOAD_FAST BUILD_TUPLE | 17,066,371 | 0.3% | 59.3% |
| DICT_MERGE CALL_FUNCTION_EX | 16,700,970 | 0.3% | 59.6% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 16,685,382 | 0.3% | 59.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,671,492 | 0.3% | 60.3% |
| BUILD_MAP LOAD_FAST | 16,611,771 | 0.3% | 60.6% |
| LOAD_FAST DICT_MERGE | 16,572,054 | 0.3% | 60.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,178,834 | 0.3% | 61.2% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 16,098,072 | 0.3% | 61.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,028,104 | 0.3% | 61.8% |
| LOAD_ATTR LOAD_FAST | 15,962,280 | 0.3% | 62.1% |
| RESUME_CHECK LOAD_CONST | 15,734,759 | 0.3% | 62.3% |
| LOAD_FAST CALL_BUILTIN_O | 15,707,348 | 0.3% | 62.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,672,958 | 0.3% | 62.9% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 15,653,202 | 0.3% | 63.2% |
| LOAD_FAST CALL_LIST_APPEND | 15,553,289 | 0.3% | 63.5% |
| POP_TOP JUMP_BACKWARD | 15,410,034 | 0.3% | 63.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 15,195,037 | 0.3% | 64.1% |
| RETURN_VALUE RETURN_VALUE | 15,184,563 | 0.3% | 64.4% |
| RESUME_CHECK POP_TOP | 15,156,980 | 0.3% | 64.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 15,126,056 | 0.3% | 64.9% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 15,103,472 | 0.3% | 65.2% |
| LOAD_ATTR IS_OP | 14,885,564 | 0.3% | 65.5% |
| LOAD_FAST CALL_TYPE_1 | 14,729,298 | 0.3% | 65.7% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 14,510,606 | 0.3% | 66.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 535,689 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,626 | 56.2% |
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
| BINARY_OP_ADD_INT | 920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 600 | 65.2% |
| JUMP_BACKWARD | 320 | 34.8% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,250,055 | 77.7% |
| POP_TOP | 13,882,349 | 10.9% |
| COPY_FREE_VARS | 12,999,602 | 10.2% |
| MAKE_CELL | 1,509,160 | 1.2% |
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
| LOAD_FAST_LOAD_FAST | 13,459,142 | 59.1% |
| LOAD_DEREF | 6,404,947 | 28.1% |
| BUILD_TUPLE | 1,781,652 | 7.8% |
| LOAD_FAST | 734,332 | 3.2% |
| RETURN_VALUE | 152,426 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,649,417 | 29.2% |
| LOAD_FAST | 6,545,540 | 28.7% |
| RETURN_VALUE | 6,066,936 | 26.6% |
| CALL | 909,225 | 4.0% |
| GET_ITER | 873,211 | 3.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,776 | 73.6% |
| BUILD_TUPLE | 157,284 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,332 | 8.7% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,572 | 100.0% |
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
| RETURN_CONST | 22,522 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,522 | 100.0% |


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
| LOAD_FAST | 21,271,649 | 35.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,416,979 | 24.2% |
| CALL | 10,953,556 | 18.4% |
| RETURN_VALUE | 4,117,083 | 6.9% |
| CALL_BUILTIN_O | 2,591,134 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 19,848,386 | 33.4% |
| CALL_PY_EXACT_ARGS | 13,002,020 | 21.9% |
| FOR_ITER_TUPLE | 9,886,843 | 16.6% |
| LOAD_FAST_AND_CLEAR | 9,198,580 | 15.5% |
| FOR_ITER_LIST | 4,388,611 | 7.4% |


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
| RETURN_VALUE | 72,899,398 | 57.2% |
| RETURN_CONST | 32,283,499 | 25.3% |
| YIELD_VALUE | 22,272,743 | 17.5% |
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
| LOAD_CONST | 12,383,136 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 10,365,031 | 83.7% |
| LOAD_GLOBAL_BUILTIN | 793,935 | 6.4% |
| STORE_FAST | 669,672 | 5.4% |
| LOAD_FAST | 458,670 | 3.7% |
| STORE_NAME | 33,580 | 0.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,364,805 | 67.9% |
| POP_JUMP_IF_TRUE | 4,184,063 | 13.3% |
| STORE_FAST | 1,973,368 | 6.3% |
| POP_JUMP_IF_FALSE | 1,913,016 | 6.1% |
| POP_TOP | 1,392,202 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,281,203 | 39.0% |
| LOAD_DEREF | 10,424,223 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,382,815 | 20.3% |
| LOAD_FAST_LOAD_FAST | 899,760 | 2.9% |
| LOAD_CONST | 751,097 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,771 | 45.7% |
| POP_TOP | 358,541 | 39.5% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,771 | 45.7% |
| EXTENDED_ARG | 201,420 | 22.2% |
| ENTER_EXECUTOR | 145,001 | 16.0% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,156,980 | 24.6% |
| CACHE | 13,882,349 | 22.5% |
| RETURN_CONST | 9,347,383 | 15.2% |
| STORE_FAST | 5,839,906 | 9.5% |
| SWAP | 5,778,575 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 15,410,034 | 25.0% |
| RESUME_CHECK | 14,325,782 | 23.2% |
| ENTER_EXECUTOR | 8,677,996 | 14.1% |
| LOAD_FAST | 7,247,765 | 11.7% |
| RETURN_VALUE | 5,302,375 | 8.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,699 | 41.3% |
| BINARY_SUBSCR_DICT | 170,045 | 18.8% |
| RAISE_VARARGS | 115,292 | 12.7% |
| ENTER_EXECUTOR | 102,364 | 11.3% |
| LOAD_ATTR | 89,180 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,480 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,812 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,306,420 | 40.3% |
| LOAD_DEREF | 11,886,706 | 27.7% |
| LOAD_ATTR | 8,385,937 | 19.5% |
| CALL_BUILTIN_FAST | 2,128,600 | 5.0% |
| LOAD_SUPER_ATTR_ATTR | 1,182,013 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,363,423 | 82.4% |
| LOAD_FAST_LOAD_FAST | 5,620,428 | 13.1% |
| LOAD_CONST | 1,723,660 | 4.0% |
| LOAD_DEREF | 127,446 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,887,077 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,117,365 | 28.7% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,160 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,191,738 | 71.1% |
| STORE_FAST | 2,660,444 | 18.6% |
| LOAD_FAST | 792,066 | 5.5% |
| GET_YIELD_FROM_ITER | 347,016 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,944,066 | 29.8% |
| LOAD_ATTR_SLOT | 33,432,997 | 18.8% |
| BUILD_TUPLE | 21,220,806 | 12.0% |
| RETURN_VALUE | 15,184,563 | 8.6% |
| CALL_BUILTIN_O | 11,433,110 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,899,398 | 41.1% |
| STORE_FAST | 38,557,667 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,465,580 | 11.0% |
| RETURN_VALUE | 15,184,563 | 8.6% |
| LOAD_FAST | 5,453,801 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,268,328 | 97.4% |
| BINARY_SUBSCR | 56,960 | 1.7% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.6% |
| SWAP | 5,960 | 0.2% |
| STORE_SUBSCR | 3,549 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,255,248 | 97.0% |
| ENTER_EXECUTOR | 60,560 | 1.8% |
| JUMP_BACKWARD | 19,580 | 0.6% |
| JUMP_FORWARD | 9,840 | 0.3% |
| STORE_SUBSCR | 3,549 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.7% |
| LOAD_FAST | 2,208,062 | 17.1% |
| LOAD_GLOBAL_MODULE | 119,003 | 0.9% |
| LOAD_ATTR | 117,984 | 0.9% |
| RETURN_VALUE | 27,300 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,234,359 | 94.8% |
| POP_JUMP_IF_TRUE | 509,863 | 4.0% |
| UNARY_NOT | 84,171 | 0.7% |
| TO_BOOL_BOOL | 41,191 | 0.3% |
| TO_BOOL | 21,364 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,480 | 22.0% |
| LOAD_FAST | 109,480 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,693 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,989 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,842 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,135 | 10.9% |
| CALL_LIST_APPEND | 39,960 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,721 | 65.3% |
| TO_BOOL_BOOL | 1,084,995 | 20.6% |
| TO_BOOL_LIST | 661,878 | 12.5% |
| TO_BOOL | 84,171 | 1.6% |
| TO_BOOL_INT | 164 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,489 | 66.9% |
| STORE_FAST | 882,757 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,935 | 1.6% |
| LOAD_CONST | 34,368 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,752,970 | 33.4% |
| COMPARE_OP_INT | 6,307,120 | 17.9% |
| COMPARE_OP | 6,149,100 | 17.5% |
| CALL_TUPLE_1 | 4,707,379 | 13.4% |
| LOAD_FAST | 2,606,895 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,166,006 | 68.6% |
| RETURN_VALUE | 5,756,397 | 16.4% |
| BUILD_TUPLE | 1,556,880 | 4.4% |
| CALL_BUILTIN_O | 1,095,139 | 3.1% |
| LOAD_FAST | 857,867 | 2.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,323 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,543 | 97.9% |
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
| SWAP | 4,464,381 | 20.7% |
| POP_JUMP_IF_TRUE | 4,083,163 | 18.9% |
| STORE_FAST | 3,816,489 | 17.7% |
| LOAD_FAST | 2,312,197 | 10.7% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,712,220 | 54.3% |
| SWAP | 4,464,381 | 20.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,398 | 10.6% |
| LOAD_FAST | 1,374,571 | 6.4% |
| BUILD_LIST | 748,358 | 3.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,164,621 | 44.7% |
| SWAP | 4,716,199 | 17.3% |
| BUILD_TUPLE | 4,430,247 | 16.3% |
| LOAD_CONST | 1,656,740 | 6.1% |
| RESUME_CHECK | 1,285,960 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,611,771 | 61.0% |
| SWAP | 4,716,199 | 17.3% |
| STORE_FAST | 3,331,420 | 12.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 5.7% |
| CALL_FUNCTION_EX | 734,880 | 2.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,408 | 64.2% |
| SWAP | 18,000 | 35.7% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,408 | 64.2% |
| SWAP | 18,000 | 35.7% |
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
| LOAD_FAST_LOAD_FAST | 19,059,235 | 37.9% |
| LOAD_FAST | 17,066,371 | 34.0% |
| LOAD_ATTR_SLOT | 5,042,352 | 10.0% |
| LOAD_ATTR | 3,033,739 | 6.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,220,806 | 42.2% |
| LOAD_CONST | 10,384,767 | 20.7% |
| LOAD_GLOBAL_BUILTIN | 4,707,179 | 9.4% |
| BUILD_MAP | 4,430,247 | 8.8% |
| CALL_LIST_APPEND | 3,216,000 | 6.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,642,642 | 35.9% |
| LOAD_FAST | 7,267,106 | 27.1% |
| BINARY_OP_MULTIPLY_INT | 2,291,863 | 8.5% |
| ENTER_EXECUTOR | 1,992,023 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 1,572,940 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,556 | 40.8% |
| STORE_FAST | 5,844,845 | 21.8% |
| RETURN_VALUE | 4,519,264 | 16.8% |
| POP_TOP | 1,132,106 | 4.2% |
| RESUME_CHECK | 1,062,877 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 16,700,970 | 59.6% |
| ENTER_EXECUTOR | 6,572,740 | 23.5% |
| LOAD_FAST | 2,317,559 | 8.3% |
| CALL_INTRINSIC_1 | 1,256,883 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,600,999 | 45.0% |
| RESUME_CHECK | 11,673,645 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,866 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,348,031 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,883 | 93.2% |
| BUILD_MAP | 91,308 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,509,246 | 98.5% |
| ENTER_EXECUTOR | 164,268 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,528 | 88.9% |
| POP_TOP | 698,043 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,819 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,062,216 | 55.2% |
| LOAD_FAST | 7,941,510 | 20.8% |
| CALL_TYPE_1 | 5,882,643 | 15.4% |
| LOAD_GLOBAL_MODULE | 1,180,020 | 3.1% |
| LOAD_CONST | 949,700 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,737,318 | 51.7% |
| BINARY_OP | 6,149,100 | 16.1% |
| LOAD_FAST_LOAD_FAST | 6,149,020 | 16.1% |
| UNARY_NOT | 3,442,721 | 9.0% |
| POP_JUMP_IF_TRUE | 2,277,968 | 6.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,131,516 | 61.9% |
| LOAD_ATTR | 3,188,634 | 17.7% |
| LOAD_GLOBAL_MODULE | 1,645,866 | 9.2% |
| LOAD_DEREF | 1,479,900 | 8.2% |
| LOAD_CONST | 175,002 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,685,382 | 92.8% |
| POP_JUMP_IF_TRUE | 1,280,226 | 7.1% |
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
| LOAD_FAST | 1,237,529 | 26.7% |
| COPY | 1,073,960 | 23.2% |
| LOAD_FAST_LOAD_FAST | 872,880 | 18.9% |
| CALL_ISINSTANCE | 525,020 | 11.3% |
| LOAD_CONST | 236,788 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,339,120 | 28.9% |
| COPY | 1,073,960 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,067,680 | 23.1% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,588 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 12,999,602 | 40.9% |
| CALL_PY_EXACT_ARGS | 11,815,785 | 37.2% |
| LOAD_ATTR_PROPERTY | 5,066,495 | 16.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,196,623 | 3.8% |
| CALL_KW | 261,140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,786,567 | 68.6% |
| RETURN_GENERATOR | 9,887,077 | 31.1% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,184 | 0.0% |


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
| LOAD_FAST | 16,572,054 | 99.2% |
| LOAD_DEREF | 128,916 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 16,700,970 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 15,103,472 | 24.8% |
| STORE_SUBSCR_LIST_INT | 9,866,173 | 16.2% |
| POP_JUMP_IF_FALSE | 9,164,972 | 15.0% |
| POP_TOP | 8,677,996 | 14.2% |
| ENTER_EXECUTOR | 6,121,716 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,320,834 | 16.9% |
| RESUME_CHECK | 9,383,082 | 15.4% |
| RETURN_CONST | 6,601,812 | 10.8% |
| CALL_FUNCTION_EX | 6,572,740 | 10.8% |
| ENTER_EXECUTOR | 6,121,716 | 10.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,062,287 | 33.0% |
| CALL_LIST_APPEND | 4,571,184 | 29.8% |
| GET_ITER | 2,378,170 | 15.5% |
| COMPARE_OP_INT | 1,719,908 | 11.2% |
| POP_JUMP_IF_FALSE | 810,143 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,608,922 | 43.1% |
| ENTER_EXECUTOR | 5,758,882 | 37.5% |
| FOR_ITER_LIST | 1,353,640 | 8.8% |
| FOR_ITER_RANGE | 642,400 | 4.2% |
| FOR_ITER_TUPLE | 394,680 | 2.6% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 67,992,654 | 65.5% |
| GET_ITER | 19,848,386 | 19.1% |
| SWAP | 7,638,627 | 7.4% |
| LOAD_FAST | 7,617,144 | 7.3% |
| ENTER_EXECUTOR | 626,013 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 71,145,329 | 68.5% |
| STORE_FAST | 8,343,391 | 8.0% |
| SWAP | 7,602,939 | 7.3% |
| RETURN_CONST | 4,697,304 | 4.5% |
| LOAD_FAST | 4,690,379 | 4.5% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,758,525 | 86.6% |
| STORE_FAST | 982,566 | 11.0% |
| STORE_DEREF | 185,708 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,822,254 | 76.2% |
| STORE_DEREF | 2,092,485 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,759,905 | 100.0% |
| ENTER_EXECUTOR | 120 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,758,525 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 14,885,564 | 32.7% |
| LOAD_FAST | 12,869,908 | 28.3% |
| LOAD_CONST | 10,976,906 | 24.1% |
| LOAD_FAST_LOAD_FAST | 5,893,671 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 539,785 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,952,165 | 65.8% |
| YIELD_VALUE | 12,854,569 | 28.3% |
| POP_JUMP_IF_TRUE | 2,641,626 | 5.8% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 20,910,017 | 29.9% |
| POP_JUMP_IF_TRUE | 16,098,072 | 23.0% |
| POP_TOP | 15,410,034 | 22.0% |
| MAP_ADD | 7,866,913 | 11.3% |
| CALL_LIST_APPEND | 2,238,664 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 67,992,654 | 97.3% |
| FOR_ITER_LIST | 928,594 | 1.3% |
| FOR_ITER_TUPLE | 817,620 | 1.2% |
| FOR_ITER_GEN | 100,578 | 0.1% |
| EXTENDED_ARG | 26,370 | 0.0% |


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
| STORE_FAST | 4,138,157 | 72.0% |
| POP_TOP | 734,256 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,879 | 3.3% |
| LOAD_FAST | 137,443 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,997,140 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,153 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,609 | 5.7% |
| STORE_FAST | 119,043 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,568,844 | 44.6% |
| LOAD_FAST | 1,188,726 | 33.8% |
| RETURN_VALUE | 510,777 | 14.5% |
| LOAD_ATTR_PROPERTY | 64,631 | 1.8% |
| BINARY_SUBSCR | 37,826 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,794,826 | 51.0% |
| JUMP_BACKWARD | 1,716,718 | 48.8% |
| LOAD_NAME | 4,800 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,347,151 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,348,031 | 99.9% |
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
| LOAD_FAST | 51,081,748 | 55.6% |
| LOAD_GLOBAL_MODULE | 33,503,678 | 36.4% |
| CALL_TYPE_1 | 2,352,358 | 2.6% |
| LOAD_ATTR_SLOT | 2,297,058 | 2.5% |
| LOAD_GLOBAL_BUILTIN | 1,905,239 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 34,997,161 | 38.1% |
| LOAD_FAST | 15,962,280 | 17.4% |
| IS_OP | 14,885,564 | 16.2% |
| PUSH_NULL | 8,385,937 | 9.1% |
| CONTAINS_OP | 3,188,634 | 3.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,553,668 | 33.9% |
| LOAD_CONST | 40,214,664 | 22.5% |
| RESUME_CHECK | 15,734,759 | 8.8% |
| BUILD_TUPLE | 10,384,767 | 5.8% |
| RETURN_CONST | 9,526,680 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,214,664 | 22.5% |
| CALL_BUILTIN_FAST | 24,056,170 | 13.5% |
| COMPARE_OP_INT | 20,732,083 | 11.6% |
| STORE_FAST | 14,268,307 | 8.0% |
| MAKE_FUNCTION | 12,383,136 | 6.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 21,546,211 | 34.1% |
| NOP | 10,424,223 | 16.5% |
| LOAD_ATTR_SLOT | 6,404,947 | 10.1% |
| POP_JUMP_IF_FALSE | 4,644,678 | 7.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,076 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 21,716,693 | 34.4% |
| PUSH_NULL | 11,886,706 | 18.8% |
| LOAD_FAST | 9,395,152 | 14.9% |
| BINARY_SUBSCR | 6,404,947 | 10.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 4.9% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,722,751 | 17.8% |
| LOAD_GLOBAL_BUILTIN | 156,054,080 | 17.3% |
| RESUME_CHECK | 115,538,967 | 12.8% |
| POP_JUMP_IF_FALSE | 107,888,141 | 12.0% |
| STORE_FAST_STORE_FAST | 40,973,251 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,120,791 | 10.5% |
| LOAD_ATTR_METHOD_NO_DICT | 76,804,393 | 8.5% |
| LOAD_CONST | 60,553,668 | 6.7% |
| LOAD_GLOBAL_MODULE | 58,113,164 | 6.5% |
| RETURN_VALUE | 52,944,066 | 5.9% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,198,580 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,983 | 45.2% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,198,500 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,983 | 45.2% |
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
| STORE_FAST | 50,471,484 | 22.1% |
| POP_JUMP_IF_FALSE | 29,376,987 | 12.8% |
| LOAD_GLOBAL_BUILTIN | 28,702,851 | 12.6% |
| RESUME_CHECK | 19,321,142 | 8.4% |
| STORE_FAST_STORE_FAST | 15,653,202 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 26,368,185 | 11.5% |
| COMPARE_OP | 21,062,216 | 9.2% |
| BUILD_TUPLE | 19,059,235 | 8.3% |
| STORE_SUBSCR_LIST_INT | 18,852,214 | 8.2% |
| CALL_BUILTIN_FAST | 17,262,403 | 7.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,250 | 19.4% |
| LOAD_FAST | 34,189 | 18.8% |
| STORE_FAST | 26,914 | 14.8% |
| RESUME_CHECK | 10,930 | 6.0% |
| RESUME | 10,775 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,512 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,256 | 22.7% |
| LOAD_FAST | 39,566 | 21.8% |
| LOAD_ATTR | 14,073 | 7.7% |
| CALL | 9,827 | 5.4% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 28,240 | 38.9% |
| LOAD_NAME | 7,940 | 10.9% |
| CALL | 7,360 | 10.1% |
| LIST_APPEND | 4,800 | 6.6% |
| POP_TOP | 4,740 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 22,480 | 31.0% |
| LOAD_CONST | 19,560 | 26.9% |
| LOAD_NAME | 7,940 | 10.9% |
| CALL | 5,380 | 7.4% |
| EXTENDED_ARG | 4,320 | 5.9% |


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
| MAKE_CELL | 2,274,997 | 37.6% |
| CACHE | 1,509,160 | 24.9% |
| CALL_PY_EXACT_ARGS | 770,584 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,438 | 10.8% |
| CALL | 523,722 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,771,282 | 62.3% |
| MAKE_CELL | 2,274,997 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,854,093 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,866,913 | 100.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 109,008,279 | 42.4% |
| COMPARE_OP_INT | 33,148,643 | 12.9% |
| IS_OP | 29,952,165 | 11.7% |
| COMPARE_OP | 19,737,318 | 7.7% |
| CONTAINS_OP | 16,685,382 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 107,888,141 | 42.0% |
| LOAD_GLOBAL_BUILTIN | 57,682,334 | 22.4% |
| LOAD_FAST_LOAD_FAST | 29,376,987 | 11.4% |
| RETURN_CONST | 28,987,998 | 11.3% |
| LOAD_GLOBAL_MODULE | 9,654,291 | 3.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,044,305 | 81.0% |
| BINARY_SUBSCR | 6,649,417 | 16.3% |
| LOAD_DEREF | 1,088,857 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |
| EXTENDED_ARG | 5,448 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,910,017 | 51.2% |
| LOAD_FAST_LOAD_FAST | 14,510,606 | 35.6% |
| LOAD_FAST | 2,501,314 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 1,438,389 | 3.5% |
| LOAD_CONST | 1,111,435 | 2.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,671,492 | 92.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,225,031 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,235,665 | 67.6% |
| LOAD_FAST_LOAD_FAST | 1,988,144 | 11.0% |
| LOAD_GLOBAL_MODULE | 1,880,608 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,200 | 7.6% |
| ENTER_EXECUTOR | 433,886 | 2.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 54,161,019 | 75.2% |
| TO_BOOL_INT | 8,686,910 | 12.1% |
| IS_OP | 2,641,626 | 3.7% |
| COMPARE_OP | 2,277,968 | 3.2% |
| CONTAINS_OP | 1,280,226 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,026,095 | 50.0% |
| JUMP_BACKWARD | 16,098,072 | 22.4% |
| LOAD_GLOBAL_BUILTIN | 5,255,094 | 7.3% |
| NOP | 4,184,063 | 5.8% |
| BUILD_LIST | 4,083,163 | 5.7% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,952 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,292 | 98.4% |
| COPY | 1,760 | 1.5% |
| LOAD_CONST | 160 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 28,987,998 | 51.0% |
| RESUME_CHECK | 10,045,757 | 17.7% |
| ENTER_EXECUTOR | 6,601,812 | 11.6% |
| FOR_ITER | 4,697,304 | 8.3% |
| STORE_SUBSCR | 3,255,248 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,283,499 | 56.7% |
| LOAD_CONST | 9,526,680 | 16.7% |
| POP_TOP | 9,347,383 | 16.4% |
| TO_BOOL_BOOL | 3,147,061 | 5.5% |
| STORE_FAST | 1,541,212 | 2.7% |


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
| JUMP_BACKWARD | 17,680 | 91.7% |
| ENTER_EXECUTOR | 1,600 | 8.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 10,365,031 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,813,981 | 94.7% |
| STORE_FAST | 298,242 | 2.9% |
| STORE_DEREF | 95,593 | 0.9% |
| LOAD_CONST | 52,360 | 0.5% |
| LOAD_GLOBAL_MODULE | 42,976 | 0.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,920 | 82.3% |
| LOAD_FAST | 98,460 | 16.6% |
| STORE_ATTR | 3,904 | 0.7% |
| SWAP | 2,159 | 0.4% |
| LOAD_DEREF | 8 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,708 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,292 | 19.7% |
| LOAD_FAST | 89,983 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,577,820 | 46.5% |
| IMPORT_FROM | 2,092,485 | 27.2% |
| LOAD_ATTR | 1,558,854 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,593 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,780 | 46.5% |
| POP_TOP | 1,906,777 | 24.8% |
| LOAD_DEREF | 1,298,362 | 16.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.3% |
| IMPORT_FROM | 185,708 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,557,667 | 13.1% |
| LOAD_ATTR | 34,997,161 | 11.8% |
| BINARY_OP | 24,166,006 | 8.2% |
| LOAD_ATTR_SLOT | 22,510,641 | 7.6% |
| LOAD_CONST | 14,268,307 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,722,751 | 54.1% |
| LOAD_FAST_LOAD_FAST | 50,471,484 | 17.1% |
| LOAD_GLOBAL_BUILTIN | 32,308,023 | 10.9% |
| LOAD_GLOBAL_MODULE | 11,279,246 | 3.8% |
| STORE_FAST | 9,345,191 | 3.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,275 | 69.7% |
| FOR_ITER_TUPLE | 408,670 | 22.6% |
| FOR_ITER | 92,961 | 5.1% |
| FOR_ITER_RANGE | 47,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,221,177 | 67.5% |
| LOAD_ATTR_PROPERTY | 202,024 | 11.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 186,485 | 10.3% |
| LOAD_DEREF | 51,760 | 2.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,820 | 2.5% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 97,529,966 | 93.6% |
| RETURN_VALUE | 3,248,251 | 3.1% |
| UNPACK_SEQUENCE_TUPLE | 1,396,987 | 1.3% |
| STORE_FAST_STORE_FAST | 771,545 | 0.7% |
| BUILD_LIST | 413,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,973,251 | 39.3% |
| LOAD_GLOBAL_BUILTIN | 22,014,860 | 21.1% |
| LOAD_DEREF | 21,546,211 | 20.7% |
| LOAD_FAST_LOAD_FAST | 15,653,202 | 15.0% |
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
| LOAD_NAME | 28,240 | 21.3% |
| IMPORT_FROM | 26,000 | 19.6% |
| POP_TOP | 12,080 | 9.1% |
| RETURN_CONST | 4,860 | 3.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 9,397,633 | 20.9% |
| LOAD_FAST_AND_CLEAR | 9,198,500 | 20.4% |
| FOR_ITER | 7,602,939 | 16.9% |
| BUILD_MAP | 4,716,199 | 10.5% |
| LOAD_FAST | 4,641,395 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,397,853 | 20.9% |
| STORE_FAST | 7,931,289 | 17.6% |
| FOR_ITER | 7,638,627 | 17.0% |
| POP_TOP | 5,778,575 | 12.8% |
| BUILD_MAP | 4,716,199 | 10.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,442 | 26.2% |
| FOR_ITER | 6,802 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 15.9% |
| LOAD_FAST | 3,979 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,662 | 46.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,427 | 23.7% |
| STORE_FAST | 8,180 | 20.6% |
| UNPACK_SEQUENCE_TUPLE | 1,133 | 2.8% |
| UNPACK_SEQUENCE | 918 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,854,569 | 55.6% |
| ENTER_EXECUTOR | 4,755,934 | 20.6% |
| CALL_ISINSTANCE | 2,334,982 | 10.1% |
| LOAD_FAST | 1,146,902 | 5.0% |
| YIELD_VALUE | 677,496 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,272,743 | 96.3% |
| YIELD_VALUE | 677,496 | 2.9% |
| STORE_FAST | 162,894 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,060 | 38.0% |
| CALL | 11,111 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,081 | 12.8% |
| POP_TOP | 3,961 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,687 | 37.2% |
| LOAD_GLOBAL | 10,775 | 22.7% |
| LOAD_CONST | 8,760 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,361 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,596,683 | 69.3% |
| LOAD_FAST_LOAD_FAST | 573,935 | 15.3% |
| BINARY_SUBSCR_DICT | 422,960 | 11.3% |
| CALL_BUILTIN_CLASS | 81,163 | 2.2% |
| LOAD_FAST | 43,682 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,538,618 | 41.1% |
| SWAP | 944,619 | 25.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 540,219 | 14.4% |
| LOAD_CONST | 269,030 | 7.2% |
| LOAD_FAST | 201,503 | 5.4% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 479,420 | 86.0% |
| CALL_METHOD_DESCRIPTOR_O | 39,600 | 7.1% |
| LOAD_FAST | 16,420 | 2.9% |
| LOAD_FAST_LOAD_FAST | 13,440 | 2.4% |
| BINARY_SUBSCR_LIST_INT | 3,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 498,960 | 89.5% |
| RETURN_VALUE | 41,840 | 7.5% |
| CALL | 6,760 | 1.2% |
| LOAD_FAST | 6,720 | 1.2% |
| CALL_BUILTIN_FAST | 1,760 | 0.3% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,677 | 60.5% |
| LOAD_ATTR_SLOT | 723,515 | 26.2% |
| LOAD_FAST_LOAD_FAST | 269,751 | 9.8% |
| LOAD_FAST | 94,270 | 3.4% |
| BINARY_OP | 1,424 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,863 | 83.1% |
| LOAD_FAST_LOAD_FAST | 181,164 | 6.6% |
| STORE_FAST | 175,560 | 6.4% |
| LOAD_FAST | 76,464 | 2.8% |
| LOAD_GLOBAL_MODULE | 25,178 | 0.9% |


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
| LOAD_CONST | 1,558,531 | 63.0% |
| LOAD_FAST_LOAD_FAST | 607,080 | 24.5% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,634 | 5.0% |
| BINARY_OP | 2,177 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,082,420 | 43.7% |
| STORE_FAST | 699,835 | 28.3% |
| BINARY_OP | 311,638 | 12.6% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,840 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,959 | 32.7% |
| LOAD_FAST_LOAD_FAST | 923,619 | 29.2% |
| LOAD_CONST | 642,800 | 20.3% |
| CALL_TUPLE_1 | 443,840 | 14.0% |
| RETURN_VALUE | 114,451 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 866,399 | 27.4% |
| RETURN_VALUE | 809,226 | 25.5% |
| BINARY_OP_ADD_INT | 422,960 | 13.4% |
| PUSH_NULL | 376,980 | 11.9% |
| SWAP | 318,100 | 10.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 59,680 | 37.5% |
| LOAD_FAST_LOAD_FAST | 40,720 | 25.6% |
| ENTER_EXECUTOR | 39,760 | 25.0% |
| LOAD_CONST | 14,556 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,248 | 100.0% |
| RETURN_VALUE | 4 | 0.0% |
| LOAD_CONST | 4 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,368,185 | 90.9% |
| COPY | 1,067,680 | 3.7% |
| LOAD_CONST | 1,026,721 | 3.5% |
| CALL_BUILTIN_CLASS | 282,563 | 1.0% |
| LOAD_FAST | 204,071 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,405,973 | 32.4% |
| SWAP | 9,397,633 | 32.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,532,059 | 26.0% |
| LOAD_CONST | 1,068,140 | 3.7% |
| RETURN_VALUE | 432,309 | 1.5% |


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
| LOAD_CONST | 8,719,084 | 97.0% |
| LOAD_FAST | 263,305 | 2.9% |
| BINARY_SUBSCR | 2,731 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,485 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 322,106 | 3.6% |
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
| LOAD_FAST | 13,129,972 | 91.3% |
| BINARY_OP_ADD_INT | 540,219 | 3.8% |
| LOAD_FAST_LOAD_FAST | 480,449 | 3.3% |
| LOAD_ATTR | 152,040 | 1.1% |
| RETURN_VALUE | 36,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,525,914 | 87.1% |
| COPY_FREE_VARS | 1,196,623 | 8.3% |
| MAKE_CELL | 654,438 | 4.5% |
| POP_TOP | 7,360 | 0.1% |
| RESUME | 620 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,796,458 | 32.7% |
| CALL_BUILTIN_CLASS | 1,959,458 | 22.9% |
| LOAD_CONST | 710,920 | 8.3% |
| CALL_LEN | 611,153 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 568,749 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,979,969 | 34.9% |
| CALL_BUILTIN_CLASS | 1,959,458 | 22.9% |
| GET_ITER | 1,728,516 | 20.2% |
| CALL | 284,367 | 3.3% |
| BINARY_SUBSCR_LIST_INT | 282,563 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,056,170 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,262,403 | 39.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,328 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 55,476 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,000,811 | 41.8% |
| STORE_FAST | 10,923,489 | 25.4% |
| TO_BOOL | 10,287,220 | 23.9% |
| PUSH_NULL | 2,128,600 | 4.9% |
| RETURN_VALUE | 1,500,331 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,899 | 94.4% |
| LOAD_FAST | 135,027 | 2.6% |
| BINARY_OP | 119,103 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,179 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 127,927 | 2.5% |
| CALL_BUILTIN_CLASS | 119,103 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,707,348 | 41.7% |
| RETURN_GENERATOR | 10,191,738 | 27.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,609,892 | 14.9% |
| LOAD_ATTR_SLOT | 4,882,792 | 13.0% |
| BINARY_OP | 1,095,139 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,591,049 | 36.1% |
| RETURN_VALUE | 11,433,110 | 30.4% |
| TO_BOOL_BOOL | 9,869,242 | 26.2% |
| GET_ITER | 2,591,134 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,787,835 | 57.2% |
| LOAD_GLOBAL_BUILTIN | 18,938,567 | 30.3% |
| LOAD_DEREF | 3,017,998 | 4.8% |
| LOAD_FAST_LOAD_FAST | 2,763,394 | 4.4% |
| LOAD_FAST | 1,592,484 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,512,725 | 95.2% |
| YIELD_VALUE | 2,334,982 | 3.7% |
| COPY | 525,020 | 0.8% |
| RETURN_VALUE | 127,546 | 0.2% |
| TO_BOOL | 9,662 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,055,272 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 173,720 | 0.6% |
| RETURN_VALUE | 95,125 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,270,984 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,676,687 | 34.5% |
| LOAD_CONST | 7,179,235 | 25.6% |
| CALL_BUILTIN_CLASS | 611,153 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,553,289 | 64.8% |
| BUILD_TUPLE | 3,216,000 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 960,820 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,103,472 | 62.9% |
| EXTENDED_ARG | 4,571,184 | 19.0% |
| JUMP_BACKWARD | 2,238,664 | 9.3% |
| LOAD_FAST | 1,681,758 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,195,037 | 68.9% |
| LOAD_CONST | 2,388,491 | 10.8% |
| BUILD_LIST | 2,294,398 | 10.4% |
| BUILD_MAP | 1,561,360 | 7.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 273,228 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,901,208 | 58.5% |
| STORE_FAST | 3,415,501 | 15.5% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.1% |
| POP_TOP | 908,844 | 4.1% |
| GET_ITER | 737,598 | 3.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,220 | 46.8% |
| LOAD_ATTR_METHOD_NO_DICT | 1,600 | 33.8% |
| LOAD_FAST | 800 | 16.9% |
| CALL | 120 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,860 | 39.2% |
| LOAD_FAST_LOAD_FAST | 920 | 19.4% |
| GET_ITER | 880 | 18.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 680 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 220 | 4.6% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 24,474,016 | 83.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,739 | 16.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,791 | 0.4% |
| LOAD_ATTR | 72,820 | 0.2% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,416,979 | 48.9% |
| STORE_FAST | 9,688,419 | 32.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,899 | 16.6% |
| CALL_BUILTIN_CLASS | 169,739 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,791 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.2% |
| LOAD_CONST | 1,226,531 | 26.7% |
| LOAD_FAST | 296,920 | 6.5% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.4% |
| LOAD_CONST | 1,224,531 | 26.7% |
| TO_BOOL_NONE | 48,400 | 1.1% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,793,038 | 31.0% |
| LOAD_FAST | 15,672,958 | 23.4% |
| GET_ITER | 13,002,020 | 19.4% |
| LOAD_FAST_LOAD_FAST | 12,955,187 | 19.3% |
| LOAD_SUPER_ATTR_METHOD | 1,539,373 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 50,121,474 | 74.8% |
| COPY_FREE_VARS | 11,815,785 | 17.6% |
| RETURN_GENERATOR | 4,117,365 | 6.1% |
| MAKE_CELL | 770,584 | 1.1% |
| CALL_PY_EXACT_ARGS | 145,198 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,621,998 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,373,869 | 29.9% |
| ENTER_EXECUTOR | 1,014,546 | 22.1% |
| RETURN_VALUE | 192,623 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,886 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,373,260 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,746 | 1.2% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,179 | 80.4% |
| LOAD_FAST | 1,017,248 | 17.4% |
| STORE_FAST | 105,772 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,152 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,379 | 80.4% |
| BINARY_SUBSCR_DICT | 443,840 | 7.6% |
| STORE_FAST | 353,212 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,729,298 | 99.2% |
| LOAD_CONST | 120,012 | 0.8% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,081 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,779 | 43.3% |
| COMPARE_OP | 5,882,643 | 39.6% |
| LOAD_ATTR | 2,352,358 | 15.8% |
| IS_OP | 64,272 | 0.4% |
| BUILD_TUPLE | 55,800 | 0.4% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,602 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,686 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,068 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,732,083 | 42.5% |
| LOAD_FAST_LOAD_FAST | 16,178,834 | 33.2% |
| CALL_LEN | 10,270,984 | 21.1% |
| LOAD_FAST | 1,013,554 | 2.1% |
| LOAD_ATTR_SLOT | 225,459 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,148,643 | 68.0% |
| BINARY_OP | 6,307,120 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.7% |
| EXTENDED_ARG | 1,719,908 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,568,380 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 69.1% |
| LOAD_CONST | 4,296,397 | 29.6% |
| LOAD_GLOBAL_MODULE | 192,460 | 1.3% |
| LOAD_FAST | 2,040 | 0.0% |
| LOAD_ATTR | 1,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,480,893 | 99.7% |
| YIELD_VALUE | 40,224 | 0.3% |
| POP_JUMP_IF_TRUE | 2,080 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,578 | 52.6% |
| GET_ITER | 90,698 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,658 | 52.1% |
| POP_TOP | 90,538 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,844,834 | 35.1% |
| GET_ITER | 4,388,611 | 31.8% |
| EXTENDED_ARG | 1,353,640 | 9.8% |
| SWAP | 1,221,467 | 8.8% |
| ENTER_EXECUTOR | 1,053,529 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,935,287 | 57.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,210,585 | 16.0% |
| LOAD_FAST | 2,084,710 | 15.1% |
| STORE_FAST_LOAD_FAST | 1,260,275 | 9.1% |
| BUILD_LIST | 195,910 | 1.4% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 669,181 | 47.9% |
| EXTENDED_ARG | 642,400 | 46.0% |
| SWAP | 38,880 | 2.8% |
| LOAD_FAST | 29,360 | 2.1% |
| JUMP_BACKWARD | 15,580 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,459 | 93.5% |
| STORE_FAST_LOAD_FAST | 47,440 | 3.4% |
| RETURN_CONST | 35,802 | 2.6% |
| LOAD_FAST | 3,560 | 0.3% |
| LOAD_GLOBAL_MODULE | 1,100 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,886,843 | 81.9% |
| JUMP_BACKWARD | 817,620 | 6.8% |
| LOAD_FAST | 517,943 | 4.3% |
| EXTENDED_ARG | 394,680 | 3.3% |
| SWAP | 299,606 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,110,608 | 83.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 764,581 | 6.3% |
| STORE_FAST_LOAD_FAST | 408,670 | 3.4% |
| RETURN_CONST | 368,404 | 3.1% |
| BUILD_LIST | 191,314 | 1.6% |


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
| LOAD_FAST | 5,501,664 | 60.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,898 | 11.7% |
| LOAD_DEREF | 1,058,358 | 11.6% |
| COPY | 956,400 | 10.5% |
| LOAD_GLOBAL_MODULE | 481,592 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,471 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,328 | 14.7% |
| POP_JUMP_IF_NOT_NONE | 1,225,031 | 13.5% |
| STORE_FAST | 1,076,058 | 11.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,898 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,804,393 | 85.8% |
| RETURN_VALUE | 4,635,543 | 5.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.5% |
| LOAD_GLOBAL_MODULE | 1,964,944 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,471 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,792,830 | 34.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,474,016 | 27.3% |
| CALL_PY_EXACT_ARGS | 20,793,038 | 23.2% |
| LOAD_CONST | 4,051,360 | 4.5% |
| LOAD_DEREF | 3,319,076 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 21,716,693 | 72.0% |
| LOAD_ATTR_SLOT | 4,711,259 | 15.6% |
| LOAD_FAST | 3,528,273 | 11.7% |
| LOAD_ATTR | 147,517 | 0.5% |
| STORE_FAST_LOAD_FAST | 45,820 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,126,056 | 50.1% |
| LOAD_FAST_LOAD_FAST | 9,912,152 | 32.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,739 | 15.9% |
| CALL_PY_EXACT_ARGS | 318,594 | 1.1% |
| LOAD_CONST | 6,571 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260,882 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,401 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,280 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,664 | 6.3% |
| CALL | 57,379 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR_SLOT | 15,920 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,466,215 | 87.2% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| ENTER_EXECUTOR | 2,947,943 | 5.2% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 213,812 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,246,111 | 74.5% |
| CALL_BUILTIN_O | 5,609,892 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,921,243 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,677 | 2.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 990,736 | 60.3% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.1% |
| LOAD_DEREF | 144,340 | 8.8% |
| LOAD_ATTR | 12,020 | 0.7% |
| ENTER_EXECUTOR | 9,740 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.1% |
| TO_BOOL_STR | 478,200 | 29.1% |
| TO_BOOL_BOOL | 404,823 | 24.6% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,299,302 | 90.4% |
| ENTER_EXECUTOR | 1,318,418 | 4.7% |
| RETURN_VALUE | 642,547 | 2.3% |
| STORE_FAST_LOAD_FAST | 202,024 | 0.7% |
| LOAD_DEREF | 190,736 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,813,486 | 67.2% |
| COPY_FREE_VARS | 5,066,495 | 18.1% |
| GET_ITER | 1,920,214 | 6.9% |
| TO_BOOL_BOOL | 712,523 | 2.5% |
| STORE_FAST | 506,385 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,120,791 | 98.5% |
| LOAD_ATTR_SLOT | 613,654 | 0.6% |
| ENTER_EXECUTOR | 573,880 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,061 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 70,041 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,432,997 | 35.0% |
| STORE_FAST | 22,510,641 | 23.6% |
| LOAD_DEREF | 6,404,947 | 6.7% |
| LOAD_FAST | 5,219,991 | 5.5% |
| LOAD_CONST | 5,210,178 | 5.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,682,334 | 25.5% |
| RESUME_CHECK | 41,266,196 | 18.3% |
| STORE_FAST | 32,308,023 | 14.3% |
| STORE_FAST_STORE_FAST | 22,014,860 | 9.7% |
| LOAD_FAST | 20,354,526 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 156,054,080 | 69.1% |
| LOAD_FAST_LOAD_FAST | 28,702,851 | 12.7% |
| CALL_ISINSTANCE | 18,938,567 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 8,973,157 | 4.0% |
| LOAD_DEREF | 3,220,795 | 1.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,113,164 | 49.3% |
| RESUME_CHECK | 16,028,104 | 13.6% |
| STORE_FAST | 11,279,246 | 9.6% |
| POP_JUMP_IF_FALSE | 9,654,291 | 8.2% |
| NOP | 6,382,815 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 35,787,835 | 30.4% |
| LOAD_ATTR | 33,503,678 | 28.4% |
| LOAD_FAST | 29,325,844 | 24.9% |
| LOAD_FAST_LOAD_FAST | 3,279,969 | 2.8% |
| LOAD_DEREF | 3,256,933 | 2.8% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,613 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,182,013 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,549 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,373 | 85.1% |
| LOAD_GLOBAL_MODULE | 172,256 | 9.5% |
| LOAD_FAST | 78,500 | 4.3% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 99,250,055 | 38.6% |
| CALL_PY_EXACT_ARGS | 50,121,474 | 19.5% |
| COPY_FREE_VARS | 21,786,567 | 8.5% |
| LOAD_ATTR_PROPERTY | 18,813,486 | 7.3% |
| POP_TOP | 14,325,782 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,538,967 | 44.9% |
| LOAD_GLOBAL_BUILTIN | 41,266,196 | 16.0% |
| NOP | 21,364,805 | 8.3% |
| LOAD_FAST_LOAD_FAST | 19,321,142 | 7.5% |
| LOAD_GLOBAL_MODULE | 16,028,104 | 6.2% |


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
| LOAD_FAST | 2,103,888 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,139 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,765 | 36.0% |
| RETURN_CONST | 887,446 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,430 | 52.2% |
| LOAD_FAST | 4,285,097 | 47.3% |
| STORE_ATTR_SLOT | 41,784 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,673,210 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,319 | 24.9% |
| LOAD_CONST | 1,890,781 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,857 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,570,439 | 68.9% |
| LOAD_FAST | 396,979 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,339 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,652,220 | 72.5% |
| EXTENDED_ARG | 226,739 | 10.0% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.0% |
| LOAD_FAST | 164,821 | 7.2% |
| LOAD_GLOBAL_MODULE | 38,959 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,852,214 | 93.3% |
| SWAP | 1,067,680 | 5.3% |
| BINARY_SUBSCR_DICT | 112,800 | 0.6% |
| LOAD_FAST | 99,418 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,022,693 | 49.6% |
| ENTER_EXECUTOR | 9,866,173 | 48.8% |
| JUMP_BACKWARD | 249,986 | 1.2% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,310 | 98.7% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| ENTER_EXECUTOR | 480 | 0.2% |
| TO_BOOL | 382 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 217,403 | 95.2% |
| POP_JUMP_IF_FALSE | 9,481 | 4.2% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 48 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 59,512,725 | 35.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,246,111 | 25.0% |
| LOAD_FAST | 21,602,256 | 12.8% |
| CALL_BUILTIN_FAST | 18,000,811 | 10.6% |
| CALL_BUILTIN_O | 9,869,242 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 109,008,279 | 64.4% |
| POP_JUMP_IF_TRUE | 54,161,019 | 32.0% |
| EXTENDED_ARG | 5,062,287 | 3.0% |
| UNARY_NOT | 1,084,995 | 0.6% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,161,480 | 95.4% |
| BINARY_OP | 722,266 | 3.8% |
| BINARY_SUBSCR_TUPLE_INT | 63,291 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,180 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,852 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,350,540 | 54.4% |
| POP_JUMP_IF_TRUE | 8,686,910 | 45.6% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 164 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,228,297 | 97.1% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,066 | 0.4% |
| LOAD_ATTR_INSTANCE_VALUE | 8,780 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 832,066 | 36.3% |
| POP_JUMP_IF_TRUE | 784,563 | 34.2% |
| UNARY_NOT | 661,878 | 28.8% |
| EXTENDED_ARG | 15,680 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,816 | 69.4% |
| RETURN_VALUE | 389,333 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,034 | 11.0% |
| CALL_METHOD_DESCRIPTOR_O | 48,400 | 1.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,978 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,944,383 | 73.3% |
| POP_JUMP_IF_TRUE | 689,906 | 26.0% |
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
| STORE_FAST_LOAD_FAST | 11,200 | 2.2% |
| LOAD_FAST | 11,080 | 2.2% |
| COPY | 2,120 | 0.4% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 498,580 | 99.1% |
| POP_JUMP_IF_TRUE | 4,300 | 0.9% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,318 | 67.4% |
| RETURN_VALUE | 49,120 | 27.5% |
| CALL_BUILTIN_CLASS | 2,600 | 1.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 1.0% |
| STORE_FAST | 1,200 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 64.4% |
| STORE_FAST_STORE_FAST | 63,578 | 35.6% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 884,999 | 55.6% |
| RETURN_VALUE | 660,902 | 41.5% |
| STORE_FAST | 40,220 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,133 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,396,987 | 87.8% |
| STORE_FAST | 154,767 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 71,145,329 | 70.2% |
| RETURN_VALUE | 19,465,580 | 19.2% |
| BINARY_SUBSCR_LIST_INT | 7,532,059 | 7.4% |
| FOR_ITER_LIST | 2,210,585 | 2.2% |
| FOR_ITER_TUPLE | 764,581 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 97,529,966 | 96.2% |
| STORE_DEREF | 3,577,820 | 3.5% |
| STORE_FAST | 218,438 | 0.2% |
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
|     deferred | 35,144,842 | 78.5% |
|          hit | 9,540,844 | 21.3% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,736 | 11.7% |
| Failure | 50,709 | 88.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,468 | 18.7% |
| multiply different types | 7,302 | 14.4% |
| subtract other | 6,660 | 13.1% |
| and int | 4,123 | 8.1% |
| rshift | 3,804 | 7.5% |
| or | 3,700 | 7.3% |
| power | 2,854 | 5.6% |
| true divide different types | 2,522 | 5.0% |
| multiply other | 2,360 | 4.7% |
| remainder | 2,152 | 4.2% |
| add different types | 1,816 | 3.6% |
| floor divide | 1,268 | 2.5% |
| subtract different types | 1,194 | 2.4% |
| xor | 582 | 1.1% |
| and other | 378 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 224 | 0.4% |
| true divide float | 2 | 0.0% |


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
|     deferred | 22,760,198 | 35.5% |
|          hit | 41,327,368 | 64.4% |
|         miss | 14,935 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,711 | 33.4% |
| Failure | 15,387 | 66.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 12,005 | 78.0% |
| out of range | 1,960 | 12.7% |
| buffer int | 1,400 | 9.1% |
| array int | 20 | 0.1% |
| tuple slice | 2 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,113,161 | 6.3% |
|        deopt | 22,840 | 0.0% |
|          hit | 355,265,018 | 85.9% |
|         miss | 31,518,770 | 7.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 675,142 | 90.2% |
| Failure | 73,041 | 9.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,780 | 39.4% |
| code complex parameters | 14,057 | 19.2% |
| class no vectorcall | 9,220 | 12.6% |
| cfunc varargs keywords | 6,383 | 8.7% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.5% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,166 | 3.0% |
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
|     deferred | 38,058,644 | 37.3% |
|          hit | 63,222,014 | 62.0% |
|         miss | 575,973 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,468 | 22.9% |
| Failure | 68,966 | 77.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,420 | 26.7% |
| other | 15,282 | 22.2% |
| different types | 12,234 | 17.7% |
| tuple | 10,058 | 14.6% |
| string | 9,720 | 14.1% |
| bool | 2,052 | 3.0% |
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
|     deferred | 103,698,260 | 79.0% |
|          hit | 26,061,914 | 19.8% |
|         miss | 1,410,498 | 1.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 38,504 | 27.8% |
| Failure | 99,785 | 72.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 71,550 | 71.7% |
| set | 9,082 | 9.1% |
| zip | 7,600 | 7.6% |
| enumerate | 4,233 | 4.2% |
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
|     deferred | 90,480,457 | 22.4% |
|        deopt | 20 | 0.0% |
|          hit | 246,313,644 | 61.0% |
|         miss | 65,829,442 | 16.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,319,769 | 89.7% |
| Failure | 151,822 | 10.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mutable class | 58,674 | 38.6% |
| metaclass attribute | 53,229 | 35.1% |
| method | 10,401 | 6.9% |
| overridden | 8,673 | 5.7% |
| has managed dict | 8,600 | 5.7% |
| shadowed | 5,300 | 3.5% |
| class method obj | 3,900 | 2.6% |
| builtin class method | 1,320 | 0.9% |
| not managed dict | 745 | 0.5% |
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
|     deferred | 89,821 | 0.0% |
|          hit | 343,627,364 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,928 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 603 | 0.0% |
|          hit | 2,990,062 | 100.0% |

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
|     deferred | 540,703 | 4.2% |
|          hit | 10,197,133 | 78.4% |
|         miss | 2,222,265 | 17.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,844 | 92.3% |
| Failure | 3,904 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,960 | 50.2% |
| not managed dict | 1,444 | 37.0% |
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
|     deferred | 3,350,892 | 13.0% |
|          hit | 22,481,771 | 87.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,722 | 43.4% |
| Failure | 3,549 | 56.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 3,549 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,823,313 | 6.2% |
|          hit | 193,594,959 | 93.6% |
|         miss | 440,007 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,910 | 72.3% |
| Failure | 22,932 | 27.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,789 | 47.0% |
| number | 3,503 | 15.3% |
| mapping | 3,300 | 14.4% |
| dict | 2,240 | 9.8% |
| other | 1,623 | 7.1% |
| set | 1,437 | 6.3% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,642 | 0.0% |
|          hit | 103,102,636 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,380 | 93.6% |
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
| Basic | 2,916,830,995 | 54.0% |
| Not specialized | 724,723,001 | 13.4% |
| Specialized hits | 1,661,784,843 | 30.7% |
| Specialized misses | 102,063,130 | 1.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER | 103,698,260 | 31.1% |
| LOAD_ATTR | 90,480,457 | 27.1% |
| COMPARE_OP | 38,058,644 | 11.4% |
| BINARY_OP | 35,144,842 | 10.5% |
| CALL | 26,113,161 | 7.8% |
| BINARY_SUBSCR | 22,760,198 | 6.8% |
| TO_BOOL | 12,823,313 | 3.8% |
| STORE_SUBSCR | 3,350,892 | 1.0% |
| STORE_ATTR | 540,703 | 0.2% |
| SEND | 439,140 | 0.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,450,409 | 35.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,661,801 | 15.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,488,523 | 14.2% |
| LOAD_ATTR_METHOD_NO_DICT | 9,122,913 | 8.9% |
| CALL_PY_EXACT_ARGS | 7,814,033 | 7.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,490 | 6.3% |
| LOAD_ATTR_PROPERTY | 4,109,427 | 4.0% |
| CALL_BUILTIN_O | 2,661,181 | 2.6% |
| STORE_ATTR_SLOT | 2,221,285 | 2.2% |
| FOR_ITER_TUPLE | 823,987 | 0.8% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,666,966 | 48.7% |
| Calls to Python functions inlined | 134,586,690 | 51.3% |
| Calls via PyEval_EvalFrame (total) | 127,666,966 | 48.7% |
| Calls via PyEval_EvalFrame (vector) | 98,452,674 | 37.5% |
| Calls via PyEval_EvalFrame (generator) | 29,214,292 | 11.1% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,445,374 | 37.5% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,693 | 9.0% |
| Calls via PyEval_EvalFrame (function ex) | 11,825,133 | 4.5% |
| Calls via PyEval_EvalFrame (api) | 53,324,545 | 20.3% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,335 | 0.5% |
| Frames pushed | 112,545,699 | 42.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,394,457 | 54.3% |
| Frees to freelist | 363,637,405 |  |
| Allocations | 305,564,660 | 45.7% |
| Allocations to 512 bytes | 304,501,856 | 45.5% |
| Allocations to 4 kbytes | 1,038,344 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,237,053 |  |
| New values | 1,057,536 |  |
| Interpreter increfs | 2,632,312,304 | 65.1% |
| Interpreter decrefs | 3,047,197,156 | 65.9% |
| Increfs | 1,412,762,326 | 34.9% |
| Decrefs | 1,578,584,687 | 34.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,679,267 |  |
| Method cache misses | 4,249,453 |  |
| Method cache collisions | 5,643,283 |  |
| Method cache dunder hits | 346,985,644 |  |
| Method cache dunder misses | 1,394,424 |  |


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
| Optimization attempts | 14,365 |  |
| Traces created | 10,725 | 74.7% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 195 | 1.4% |
| Trace too long | 189 | 1.3% |
| Trace too short | 3,640 | 25.3% |
| Inner loop found | 100 | 0.7% |
| Recursive call | 160 | 1.1% |
| Traces executed | 61,020,127 |  |
| Uops executed | 1,355,432,026 | 22.21 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 2,769 | 25.8% |
| <= 32 | 4,720 | 44.0% |
| <= 64 | 2,156 | 20.1% |
| <= 128 | 1,080 | 10.1% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 3,569 | 33.3% |
| <= 32 | 4,700 | 43.8% |
| <= 64 | 1,636 | 15.3% |
| <= 128 | 820 | 7.6% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,627,873 | 2.7% |
| <= 4 | 6,320 | 0.0% |
| <= 8 | 15,885,633 | 26.0% |
| <= 16 | 12,088,574 | 19.8% |
| <= 32 | 25,673,344 | 42.1% |
| <= 64 | 2,463,527 | 4.0% |
| <= 128 | 1,982,344 | 3.2% |
| <= 256 | 1,270,385 | 2.1% |
| <= 512 | 21,313 | 0.0% |
| <= 1,024 | 294 | 0.0% |
| <= 2,048 | 60 | 0.0% |
| <= 4,096 | 20 | 0.0% |
| <= 8,192 | 260 | 0.0% |
| <= 16,384 | 100 | 0.0% |
| <= 32,768 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 348,447,464 | 25.7% | 25.7% |  |
| LOAD_FAST | 130,906,105 | 9.7% | 35.4% |  |
| _POP_JUMP_IF_TRUE | 119,907,294 | 8.8% | 44.2% |  |
| STORE_FAST | 70,421,094 | 5.2% | 49.4% |  |
| _EXIT_TRACE | 55,778,876 | 4.1% | 53.5% |  |
| _ITER_CHECK_LIST | 49,789,630 | 3.7% | 57.2% | 1.3% |
| _IS_ITER_EXHAUSTED_LIST | 49,120,277 | 3.6% | 60.8% |  |
| _ITER_NEXT_LIST | 39,552,891 | 2.9% | 63.7% |  |
| _GUARD_GLOBALS_VERSION | 36,436,416 | 2.7% | 66.4% | 1.4% |
| CONTAINS_OP | 34,135,220 | 2.5% | 68.9% |  |
| _LOAD_ATTR | 29,764,257 | 2.2% | 71.1% |  |
| _LOAD_GLOBAL_MODULE | 27,974,346 | 2.1% | 73.2% |  |
| _JUMP_TO_TOP | 25,762,816 | 1.9% | 75.1% |  |
| _ITER_CHECK_TUPLE | 23,769,868 | 1.8% | 76.9% | 4.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 22,811,348 | 1.7% | 78.5% |  |
| POP_TOP | 19,277,256 | 1.4% | 80.0% |  |
| PUSH_NULL | 17,790,677 | 1.3% | 81.3% |  |
| _ITER_NEXT_TUPLE | 13,940,883 | 1.0% | 82.3% |  |
| LOAD_CONST | 12,898,232 | 1.0% | 83.3% |  |
| _ITER_CHECK_RANGE | 10,735,981 | 0.8% | 84.0% |  |
| _IS_ITER_EXHAUSTED_RANGE | 10,735,981 | 0.8% | 84.8% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 10,216,345 | 0.8% | 85.6% | 0.4% |
| _CHECK_PEP_523 | 10,216,345 | 0.8% | 86.3% |  |
| _CHECK_STACK_SPACE | 10,177,461 | 0.8% | 87.1% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 10,174,914 | 0.8% | 87.8% |  |
| _PUSH_FRAME | 10,174,914 | 0.8% | 88.6% |  |
| _SAVE_RETURN_OFFSET | 10,174,914 | 0.8% | 89.4% |  |
| _ITER_NEXT_RANGE | 9,907,862 | 0.7% | 90.1% |  |
| _GUARD_BOTH_INT | 9,256,382 | 0.7% | 90.8% |  |
| _BINARY_OP_ADD_INT | 9,231,542 | 0.7% | 91.4% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 9,160,783 | 0.7% | 92.1% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 9,160,783 | 0.7% | 92.8% |  |
| _GUARD_TYPE_VERSION | 8,697,505 | 0.6% | 93.4% | 34.0% |
| _GUARD_BUILTINS_VERSION | 7,969,259 | 0.6% | 94.0% |  |
| _LOAD_GLOBAL_BUILTINS | 7,969,259 | 0.6% | 94.6% |  |
| BUILD_TUPLE | 6,705,511 | 0.5% | 95.1% |  |
| BUILD_MAP | 6,581,171 | 0.5% | 95.6% |  |
| DICT_MERGE | 6,571,620 | 0.5% | 96.1% |  |
| _POP_JUMP_IF_FALSE | 6,511,916 | 0.5% | 96.6% |  |
| LOAD_DEREF | 5,649,217 | 0.4% | 97.0% |  |
| CALL_ISINSTANCE | 4,943,717 | 0.4% | 97.3% |  |
| TO_BOOL_BOOL | 3,386,857 | 0.2% | 97.6% |  |
| LIST_APPEND | 2,672,058 | 0.2% | 97.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,558,396 | 0.2% | 98.0% |  |
| COMPARE_OP_INT | 2,445,274 | 0.2% | 98.2% |  |
| IS_OP | 2,363,151 | 0.2% | 98.3% |  |
| CALL_BUILTIN_O | 2,212,230 | 0.2% | 98.5% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 2,148,980 | 0.2% | 98.7% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,108,054 | 0.2% | 98.8% |  |
| MAKE_FUNCTION | 1,903,516 | 0.1% | 99.0% |  |
| CALL_TYPE_1 | 1,861,089 | 0.1% | 99.1% |  |
| BINARY_SUBSCR_LIST_INT | 1,185,060 | 0.1% | 99.2% | 1.6% |
| _BINARY_SUBSCR | 1,184,801 | 0.1% | 99.3% |  |
| STORE_DEREF | 993,124 | 0.1% | 99.3% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 861,340 | 0.1% | 99.4% |  |
| _GUARD_KEYS_VERSION | 861,340 | 0.1% | 99.5% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 861,340 | 0.1% | 99.5% |  |
| TO_BOOL_INT | 657,180 | 0.0% | 99.6% | 0.0% |
| RESUME_CHECK | 614,832 | 0.0% | 99.6% |  |
| CALL_BUILTIN_CLASS | 610,521 | 0.0% | 99.7% |  |
| GET_ITER | 569,458 | 0.0% | 99.7% |  |
| _LOAD_ATTR_SLOT | 534,318 | 0.0% | 99.7% |  |
| _IS_NONE | 434,056 | 0.0% | 99.8% |  |
| _COMPARE_OP | 348,900 | 0.0% | 99.8% |  |
| _POP_FRAME | 321,030 | 0.0% | 99.8% |  |
| COPY | 281,926 | 0.0% | 99.8% |  |
| SWAP | 281,040 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST | 238,556 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 181,512 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 140,440 | 0.0% | 99.9% |  |
| _BINARY_OP | 123,478 | 0.0% | 99.9% |  |
| LOAD_NAME | 106,200 | 0.0% | 99.9% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 90,061 | 0.0% | 99.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 90,061 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 80,288 | 0.0% | 99.9% |  |
| _STORE_SUBSCR | 71,550 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 71,040 | 0.0% | 100.0% | 2.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 59,540 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 57,040 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 55,600 | 0.0% | 100.0% |  |
| BUILD_LIST | 45,900 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 45,533 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 41,064 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 39,300 | 0.0% | 100.0% |  |
| STORE_NAME | 35,480 | 0.0% | 100.0% |  |
| UNARY_NOT | 33,728 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 30,080 | 0.0% | 100.0% |  |
| _TO_BOOL | 19,080 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 16,880 | 0.0% | 100.0% |  |
| CALL_LEN | 14,412 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 13,720 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 11,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 10,500 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 7,640 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 6,360 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 6,360 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 6,080 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 4,700 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,920 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 1,920 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 1,560 | 0.0% | 100.0% |  |
| STORE_SLICE | 1,240 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,240 | 0.0% | 100.0% |  |
| BUILD_STRING | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 480 | 0.0% | 100.0% | 100.0% |
| CALL_TUPLE_1 | 320 | 0.0% | 100.0% |  |
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
| FOR_ITER | 3,520 |
| LOAD_ATTR_PROPERTY | 2,869 |
| YIELD_VALUE | 940 |
| CALL | 700 |
| CALL_PY_WITH_DEFAULTS | 560 |
| CALL_LIST_APPEND | 440 |
| CALL_KW | 400 |
| CALL_FUNCTION_EX | 360 |
| BINARY_SUBSCR_GETITEM | 240 |
| FOR_ITER_GEN | 200 |
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
Stats gathered on: 2023-11-08
