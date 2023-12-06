
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
| LOAD_FAST | 833,317,136 | 16.8% | 16.8% |  |
| STORE_FAST | 285,750,347 | 5.8% | 22.6% |  |
| POP_JUMP_IF_FALSE | 257,018,870 | 5.2% | 27.8% |  |
| RESUME_CHECK | 250,260,368 | 5.0% | 32.8% |  |
| LOAD_GLOBAL_BUILTIN | 208,040,267 | 4.2% | 37.0% | 0.0% |
| LOAD_FAST_LOAD_FAST | 203,864,788 | 4.1% | 41.1% |  |
| RETURN_VALUE | 177,180,784 | 3.6% | 44.7% |  |
| LOAD_CONST | 171,440,098 | 3.5% | 48.1% |  |
| TO_BOOL_BOOL | 159,492,491 | 3.2% | 51.4% | 0.1% |
| INTERPRETER_EXIT | 127,482,587 | 2.6% | 53.9% |  |
| ENTER_EXECUTOR | 118,887,203 | 2.4% | 56.3% |  |
| LOAD_GLOBAL_MODULE | 110,220,904 | 2.2% | 58.5% | 0.0% |
| LOAD_ATTR_SLOT | 95,506,864 | 1.9% | 60.5% | 38.2% |
| LOAD_ATTR | 91,873,043 | 1.9% | 62.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 86,442,164 | 1.7% | 64.1% | 10.4% |
| POP_JUMP_IF_TRUE | 68,437,140 | 1.4% | 65.4% |  |
| POP_TOP | 60,324,601 | 1.2% | 66.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,535,699 | 1.1% | 67.8% | 27.6% |
| RETURN_CONST | 54,324,201 | 1.1% | 68.9% |  |
| CALL_ISINSTANCE | 54,028,867 | 1.1% | 70.0% |  |
| CALL_PY_EXACT_ARGS | 52,584,226 | 1.1% | 71.0% | 14.9% |
| GET_ITER | 50,663,177 | 1.0% | 72.1% |  |
| LOAD_DEREF | 50,482,021 | 1.0% | 73.1% |  |
| STORE_FAST_STORE_FAST | 49,509,016 | 1.0% | 74.1% |  |
| COMPARE_OP_INT | 48,604,228 | 1.0% | 75.1% | 1.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 46,620,628 | 0.9% | 76.0% |  |
| IS_OP | 45,558,581 | 0.9% | 76.9% |  |
| SWAP | 43,158,957 | 0.9% | 77.8% |  |
| CALL_BUILTIN_FAST | 43,066,191 | 0.9% | 78.7% |  |
| PUSH_NULL | 42,736,211 | 0.9% | 79.5% |  |
| BUILD_TUPLE | 42,248,708 | 0.9% | 80.4% |  |
| CALL_BUILTIN_O | 37,660,600 | 0.8% | 81.1% | 7.1% |
| COMPARE_OP | 36,889,758 | 0.7% | 81.9% |  |
| FOR_ITER | 34,153,191 | 0.7% | 82.6% |  |
| BINARY_OP | 34,089,296 | 0.7% | 83.3% |  |
| POP_JUMP_IF_NONE | 33,819,680 | 0.7% | 83.9% |  |
| COPY_FREE_VARS | 31,654,260 | 0.6% | 84.6% |  |
| NOP | 31,470,091 | 0.6% | 85.2% |  |
| CALL_LEN | 28,081,813 | 0.6% | 85.8% |  |
| CALL_FUNCTION_EX | 28,013,010 | 0.6% | 86.3% |  |
| LOAD_ATTR_PROPERTY | 27,994,343 | 0.6% | 86.9% | 14.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 27,650,454 | 0.6% | 87.5% | 23.4% |
| BUILD_MAP | 27,159,787 | 0.5% | 88.0% |  |
| CALL | 26,847,093 | 0.5% | 88.6% |  |
| CALL_LIST_APPEND | 24,016,365 | 0.5% | 89.0% |  |
| YIELD_VALUE | 23,139,841 | 0.5% | 89.5% |  |
| FOR_ITER_LIST | 22,408,860 | 0.5% | 90.0% | 1.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 22,018,523 | 0.4% | 90.4% | 65.9% |
| BINARY_SUBSCR_LIST_INT | 22,004,346 | 0.4% | 90.8% | 0.0% |
| BUILD_LIST | 20,483,628 | 0.4% | 91.3% |  |
| FOR_ITER_TUPLE | 20,393,952 | 0.4% | 91.7% | 1.3% |
| BINARY_SUBSCR | 20,301,183 | 0.4% | 92.1% |  |
| STORE_SUBSCR_LIST_INT | 20,082,689 | 0.4% | 92.5% |  |
| TO_BOOL_INT | 18,503,088 | 0.4% | 92.9% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,073,261 | 0.4% | 93.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 17,909,963 | 0.4% | 93.6% | 0.8% |
| EXTENDED_ARG | 17,076,602 | 0.3% | 93.9% |  |
| DICT_MERGE | 16,636,355 | 0.3% | 94.3% |  |
| LOAD_FAST_AND_CLEAR | 14,957,114 | 0.3% | 94.6% |  |
| CALL_TYPE_1 | 14,797,641 | 0.3% | 94.9% |  |
| COMPARE_OP_STR | 14,524,011 | 0.3% | 95.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,382,964 | 0.3% | 95.4% | 0.3% |
| RETURN_GENERATOR | 14,338,858 | 0.3% | 95.7% |  |
| TO_BOOL | 12,906,125 | 0.3% | 96.0% |  |
| CONTAINS_OP | 12,476,902 | 0.3% | 96.2% |  |
| CALL_KW | 10,673,151 | 0.2% | 96.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,064,700 | 0.2% | 96.6% | 0.0% |
| STORE_ATTR_SLOT | 9,060,208 | 0.2% | 96.8% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,985,240 | 0.2% | 97.0% | 0.1% |
| IMPORT_FROM | 8,954,845 | 0.2% | 97.2% |  |
| CALL_BUILTIN_CLASS | 8,480,463 | 0.2% | 97.4% |  |
| MAP_ADD | 7,865,630 | 0.2% | 97.5% |  |
| IMPORT_NAME | 7,759,674 | 0.2% | 97.7% |  |
| STORE_DEREF | 7,710,427 | 0.2% | 97.8% |  |
| MAKE_CELL | 6,049,246 | 0.1% | 98.0% |  |
| CALL_TUPLE_1 | 5,849,030 | 0.1% | 98.1% | 0.0% |
| JUMP_FORWARD | 5,743,356 | 0.1% | 98.2% |  |
| MAKE_FUNCTION | 5,394,686 | 0.1% | 98.3% |  |
| UNARY_NOT | 5,273,907 | 0.1% | 98.4% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,639 | 0.1% | 98.5% | 0.1% |
| COPY | 4,612,690 | 0.1% | 98.6% |  |
| CALL_PY_WITH_DEFAULTS | 4,591,088 | 0.1% | 98.7% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,584,376 | 0.1% | 98.8% | 0.2% |
| BINARY_OP_ADD_INT | 3,756,618 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 3,377,959 | 0.1% | 98.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,771 | 0.1% | 99.0% | 0.0% |
| BINARY_SUBSCR_DICT | 3,051,601 | 0.1% | 99.1% |  |
| BINARY_OP_MULTIPLY_INT | 2,757,902 | 0.1% | 99.1% | 0.0% |
| TO_BOOL_NONE | 2,647,538 | 0.1% | 99.2% | 8.6% |
| LIST_APPEND | 2,557,133 | 0.1% | 99.2% |  |
| BINARY_OP_SUBTRACT_INT | 2,473,300 | 0.0% | 99.3% |  |
| TO_BOOL_LIST | 2,285,863 | 0.0% | 99.3% | 0.5% |
| STORE_SUBSCR_DICT | 2,276,506 | 0.0% | 99.4% |  |
| FOR_ITER_RANGE | 2,225,017 | 0.0% | 99.4% |  |
| STORE_SUBSCR | 2,019,507 | 0.0% | 99.4% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,151 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,755,226 | 0.0% | 99.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,645,957 | 0.0% | 99.5% | 20.5% |
| UNPACK_SEQUENCE_TUPLE | 1,591,874 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,572,580 | 0.0% | 99.6% |  |
| LIST_EXTEND | 1,349,126 | 0.0% | 99.6% |  |
| CALL_INTRINSIC_1 | 1,349,086 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,562 | 0.0% | 99.7% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,181,965 | 0.0% | 99.7% |  |
| SEND_GEN | 1,029,788 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,392 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,392 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,392 | 0.0% | 99.8% |  |
| STORE_ATTR | 591,395 | 0.0% | 99.8% |  |
| BINARY_SLICE | 564,011 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 551,660 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,647 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,368 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 533,147 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 503,100 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 369,654 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 99.9% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 227,588 | 0.0% | 100.0% | 36.4% |
| FOR_ITER_GEN | 191,435 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,953 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,566 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,242 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 131,280 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,343 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,082 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 71,540 | 0.0% | 100.0% |  |
| BUILD_SET | 50,404 | 0.0% | 100.0% |  |
| RESUME | 47,581 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,761 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,548 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,260 | 0.0% | 100.0% |  |
| SET_ADD | 18,320 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,760 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,012 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,206 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 159,569,090 | 3.2% | 3.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 140,544,330 | 2.8% | 6.1% |
| RESUME_CHECK LOAD_FAST | 115,543,074 | 2.3% | 8.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 106,075,281 | 2.1% | 10.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 105,224,960 | 2.1% | 12.6% |
| CACHE RESUME_CHECK | 99,262,085 | 2.0% | 14.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,054,976 | 1.9% | 16.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 73,183,167 | 1.5% | 18.0% |
| RETURN_VALUE INTERPRETER_EXIT | 72,897,016 | 1.5% | 19.5% |
| LOAD_FAST LOAD_CONST | 60,373,900 | 1.2% | 20.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,849,772 | 1.2% | 21.9% |
| LOAD_FAST RETURN_VALUE | 52,944,994 | 1.1% | 22.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 51,679,665 | 1.0% | 24.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 51,183,316 | 1.0% | 25.0% |
| LOAD_FAST LOAD_ATTR | 50,961,248 | 1.0% | 26.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 48,117,728 | 1.0% | 27.0% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 47,062,733 | 0.9% | 28.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 43,472,050 | 0.9% | 28.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 42,823,175 | 0.9% | 29.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 42,785,279 | 0.9% | 30.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,045,846 | 0.8% | 31.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,203,824 | 0.8% | 32.2% |
| LOAD_CONST LOAD_CONST | 40,207,259 | 0.8% | 33.1% |
| RETURN_VALUE STORE_FAST | 38,447,957 | 0.8% | 33.8% |
| PUSH_NULL LOAD_FAST | 35,232,285 | 0.7% | 34.5% |
| LOAD_ATTR STORE_FAST | 34,995,100 | 0.7% | 35.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,545,961 | 0.7% | 35.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 33,433,692 | 0.7% | 36.6% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,432,611 | 0.7% | 37.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,141,090 | 0.7% | 37.9% |
| RETURN_CONST INTERPRETER_EXIT | 32,284,005 | 0.7% | 38.6% |
| IS_OP POP_JUMP_IF_FALSE | 29,996,396 | 0.6% | 39.2% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 29,940,948 | 0.6% | 39.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 29,561,340 | 0.6% | 40.4% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 29,352,027 | 0.6% | 41.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 28,846,358 | 0.6% | 41.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,347,882 | 0.6% | 42.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 28,280,725 | 0.6% | 42.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 27,756,337 | 0.6% | 43.3% |
| LOAD_FAST CALL_LEN | 27,053,334 | 0.5% | 43.8% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,064,239 | 0.5% | 44.3% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 24,593,545 | 0.5% | 44.8% |
| BINARY_OP STORE_FAST | 24,134,448 | 0.5% | 45.3% |
| LOAD_CONST CALL_BUILTIN_FAST | 23,937,290 | 0.5% | 45.8% |
| POP_TOP ENTER_EXECUTOR | 22,685,732 | 0.5% | 46.2% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 22,644,422 | 0.5% | 46.7% |
| LOAD_ATTR_SLOT STORE_FAST | 22,510,387 | 0.5% | 47.2% |
| YIELD_VALUE INTERPRETER_EXIT | 22,293,826 | 0.4% | 47.6% |
| COPY_FREE_VARS RESUME_CHECK | 21,678,667 | 0.4% | 48.0% |
| LOAD_FAST TO_BOOL_BOOL | 21,602,177 | 0.4% | 48.5% |
| RESUME_CHECK NOP | 21,364,054 | 0.4% | 48.9% |
| BUILD_TUPLE RETURN_VALUE | 21,220,927 | 0.4% | 49.3% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,085,897 | 0.4% | 49.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,791,862 | 0.4% | 50.2% |
| LOAD_CONST COMPARE_OP_INT | 20,725,642 | 0.4% | 50.6% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,465,547 | 0.4% | 51.0% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 19,367,132 | 0.4% | 51.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 18,992,617 | 0.4% | 51.8% |
| GET_ITER FOR_ITER | 18,942,174 | 0.4% | 52.1% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,848,298 | 0.4% | 52.5% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,813,434 | 0.4% | 52.9% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 18,551,082 | 0.4% | 53.3% |
| COMPARE_OP POP_JUMP_IF_FALSE | 18,505,787 | 0.4% | 53.7% |
| ENTER_EXECUTOR POP_JUMP_IF_NONE | 18,301,111 | 0.4% | 54.0% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 17,882,690 | 0.4% | 54.4% |
| LOAD_FAST TO_BOOL_INT | 17,626,318 | 0.4% | 54.7% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 17,314,692 | 0.3% | 55.1% |
| LOAD_FAST PUSH_NULL | 17,285,915 | 0.3% | 55.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,202,782 | 0.3% | 55.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 17,191,437 | 0.3% | 56.1% |
| DICT_MERGE CALL_FUNCTION_EX | 16,636,355 | 0.3% | 56.5% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,629,996 | 0.3% | 56.8% |
| BUILD_MAP LOAD_FAST | 16,611,135 | 0.3% | 57.1% |
| LOAD_FAST DICT_MERGE | 16,571,422 | 0.3% | 57.5% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,126,475 | 0.3% | 57.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,025,877 | 0.3% | 58.1% |
| LOAD_ATTR LOAD_FAST | 15,959,626 | 0.3% | 58.4% |
| LOAD_FAST CALL_BUILTIN_O | 15,704,420 | 0.3% | 58.8% |
| RESUME_CHECK LOAD_CONST | 15,611,293 | 0.3% | 59.1% |
| LOAD_FAST CALL_LIST_APPEND | 15,554,055 | 0.3% | 59.4% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 15,267,649 | 0.3% | 59.7% |
| RETURN_VALUE RETURN_VALUE | 15,184,211 | 0.3% | 60.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,177,699 | 0.3% | 60.3% |
| POP_JUMP_IF_NONE ENTER_EXECUTOR | 15,174,623 | 0.3% | 60.6% |
| RESUME_CHECK POP_TOP | 15,171,778 | 0.3% | 60.9% |
| LOAD_ATTR IS_OP | 14,930,450 | 0.3% | 61.2% |
| LOAD_FAST CALL_TYPE_1 | 14,728,737 | 0.3% | 61.5% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 14,727,797 | 0.3% | 61.8% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 14,480,767 | 0.3% | 62.1% |
| POP_TOP RESUME_CHECK | 14,333,297 | 0.3% | 62.4% |
| LOAD_FAST GET_ITER | 14,273,758 | 0.3% | 62.7% |
| LOAD_CONST STORE_FAST | 14,264,410 | 0.3% | 63.0% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 14,188,938 | 0.3% | 63.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 13,892,969 | 0.3% | 63.5% |
| CACHE POP_TOP | 13,889,893 | 0.3% | 63.8% |
| CALL_BUILTIN_O STORE_FAST | 13,588,114 | 0.3% | 64.1% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 13,278,704 | 0.3% | 64.4% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 13,127,566 | 0.3% | 64.6% |
| CACHE COPY_FREE_VARS | 12,999,320 | 0.3% | 64.9% |
| CALL_METHOD_DESCRIPTOR_FAST LOAD_FAST | 12,921,280 | 0.3% | 65.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 530,651 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,441 | 56.6% |
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
| RESUME_CHECK | 99,262,085 | 77.7% |
| POP_TOP | 13,889,893 | 10.9% |
| COPY_FREE_VARS | 12,999,320 | 10.2% |
| MAKE_CELL | 1,509,080 | 1.2% |
| RESUME | 18,057 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 10,995,046 | 54.2% |
| LOAD_DEREF | 6,404,499 | 31.5% |
| BUILD_TUPLE | 1,808,478 | 8.9% |
| LOAD_FAST | 690,510 | 3.4% |
| RETURN_VALUE | 152,432 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,066,629 | 29.9% |
| POP_JUMP_IF_NONE | 5,416,811 | 26.7% |
| LOAD_FAST | 5,271,680 | 26.0% |
| CALL | 912,289 | 4.5% |
| GET_ITER | 896,977 | 4.4% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,526 | 73.6% |
| BUILD_TUPLE | 157,224 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,302 | 8.7% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,232 | 100.0% |
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
| RETURN_CONST | 22,548 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,548 | 100.0% |


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
| LOAD_FAST | 14,273,758 | 28.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,589,337 | 24.8% |
| CALL | 10,953,405 | 21.6% |
| RETURN_VALUE | 4,117,119 | 8.1% |
| CALL_BUILTIN_O | 2,591,114 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 18,942,174 | 37.4% |
| FOR_ITER_TUPLE | 9,972,840 | 19.7% |
| LOAD_FAST_AND_CLEAR | 8,282,730 | 16.3% |
| CALL_PY_EXACT_ARGS | 6,004,382 | 11.9% |
| FOR_ITER_LIST | 4,316,163 | 8.5% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 346,968 | 64.2% |
| BINARY_SUBSCR | 185,800 | 34.4% |
| RETURN_VALUE | 7,520 | 1.4% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540,368 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,897,016 | 57.2% |
| RETURN_CONST | 32,284,005 | 25.3% |
| YIELD_VALUE | 22,293,826 | 17.5% |
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
| LOAD_CONST | 5,394,686 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 3,376,419 | 62.6% |
| LOAD_GLOBAL_BUILTIN | 794,171 | 14.7% |
| STORE_FAST | 669,669 | 12.4% |
| LOAD_FAST | 458,643 | 8.5% |
| STORE_NAME | 33,580 | 0.6% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,364,054 | 67.9% |
| POP_JUMP_IF_TRUE | 4,183,901 | 13.3% |
| STORE_FAST | 1,973,305 | 6.3% |
| POP_JUMP_IF_FALSE | 1,911,160 | 6.1% |
| POP_TOP | 1,392,129 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,280,575 | 39.0% |
| LOAD_DEREF | 10,423,969 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,377,604 | 20.3% |
| LOAD_FAST_LOAD_FAST | 897,828 | 2.9% |
| LOAD_CONST | 751,147 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,630 | 45.7% |
| POP_TOP | 358,342 | 39.5% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,630 | 45.7% |
| EXTENDED_ARG | 201,270 | 22.2% |
| ENTER_EXECUTOR | 155,352 | 17.1% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,171,778 | 25.2% |
| CACHE | 13,889,893 | 23.0% |
| RETURN_CONST | 8,002,589 | 13.3% |
| STORE_FAST | 5,839,579 | 9.7% |
| SWAP | 5,747,132 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 22,685,732 | 37.6% |
| RESUME_CHECK | 14,333,297 | 23.8% |
| LOAD_FAST | 7,247,574 | 12.0% |
| RETURN_VALUE | 5,270,932 | 8.7% |
| LOAD_CONST | 2,640,907 | 4.4% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,560 | 41.3% |
| BINARY_SUBSCR_DICT | 169,964 | 18.8% |
| RAISE_VARARGS | 115,262 | 12.7% |
| ENTER_EXECUTOR | 102,284 | 11.3% |
| LOAD_ATTR | 89,180 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,170 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,782 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,285,915 | 40.4% |
| LOAD_DEREF | 11,785,176 | 27.6% |
| LOAD_ATTR | 8,321,260 | 19.5% |
| CALL_BUILTIN_FAST | 2,128,620 | 5.0% |
| LOAD_SUPER_ATTR_ATTR | 1,181,965 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,232,285 | 82.4% |
| LOAD_FAST_LOAD_FAST | 5,564,948 | 13.0% |
| LOAD_CONST | 1,723,680 | 4.0% |
| LOAD_DEREF | 127,452 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,894,905 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,117,132 | 28.7% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,080 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,199,479 | 71.1% |
| STORE_FAST | 2,660,351 | 18.6% |
| LOAD_FAST | 791,962 | 5.5% |
| GET_YIELD_FROM_ITER | 346,968 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,944,994 | 29.9% |
| LOAD_ATTR_SLOT | 33,432,611 | 18.9% |
| BUILD_TUPLE | 21,220,927 | 12.0% |
| RETURN_VALUE | 15,184,211 | 8.6% |
| CALL_BUILTIN_O | 11,432,754 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,897,016 | 41.1% |
| STORE_FAST | 38,447,957 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,465,547 | 11.0% |
| RETURN_VALUE | 15,184,211 | 8.6% |
| LOAD_FAST | 5,437,966 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,930,851 | 95.6% |
| BINARY_SUBSCR | 56,960 | 2.8% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.9% |
| SWAP | 5,960 | 0.3% |
| STORE_SUBSCR | 3,364 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,917,971 | 95.0% |
| ENTER_EXECUTOR | 70,640 | 3.5% |
| JUMP_FORWARD | 9,840 | 0.5% |
| JUMP_BACKWARD | 9,300 | 0.5% |
| STORE_SUBSCR | 3,364 | 0.2% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.7% |
| LOAD_FAST | 2,207,926 | 17.1% |
| LOAD_GLOBAL_MODULE | 119,023 | 0.9% |
| LOAD_ATTR | 117,987 | 0.9% |
| RETURN_VALUE | 27,313 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,234,231 | 94.8% |
| POP_JUMP_IF_TRUE | 509,864 | 4.0% |
| UNARY_NOT | 84,199 | 0.7% |
| TO_BOOL_BOOL | 41,195 | 0.3% |
| TO_BOOL | 21,379 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,470 | 22.0% |
| LOAD_FAST | 109,463 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,682 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,969 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,844 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,137 | 10.9% |
| CALL_LIST_APPEND | 39,980 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,667 | 65.3% |
| TO_BOOL_BOOL | 1,085,007 | 20.6% |
| TO_BOOL_LIST | 661,866 | 12.5% |
| TO_BOOL | 84,199 | 1.6% |
| TO_BOOL_INT | 168 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,458 | 66.9% |
| STORE_FAST | 882,742 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,967 | 1.6% |
| LOAD_CONST | 34,360 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,752,859 | 34.5% |
| COMPARE_OP_INT | 6,273,260 | 18.4% |
| COMPARE_OP | 6,162,400 | 18.1% |
| CALL_TUPLE_1 | 4,707,242 | 13.8% |
| LOAD_FAST | 1,516,525 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,134,448 | 70.8% |
| RETURN_VALUE | 5,644,607 | 16.6% |
| CALL_BUILTIN_O | 1,095,129 | 3.2% |
| LOAD_FAST | 857,884 | 2.5% |
| TO_BOOL_INT | 722,340 | 2.1% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,343 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,563 | 97.9% |
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
| POP_JUMP_IF_TRUE | 4,083,246 | 19.9% |
| STORE_FAST | 3,816,464 | 18.6% |
| SWAP | 3,548,668 | 17.3% |
| LOAD_FAST | 2,131,267 | 10.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,532,134 | 56.3% |
| SWAP | 3,548,668 | 17.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,386 | 11.2% |
| LOAD_FAST | 1,374,426 | 6.7% |
| BUILD_LIST | 748,351 | 3.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,163,904 | 44.8% |
| SWAP | 4,716,062 | 17.4% |
| BUILD_TUPLE | 4,366,358 | 16.1% |
| LOAD_CONST | 1,656,760 | 6.1% |
| RESUME_CHECK | 1,285,960 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,611,135 | 61.2% |
| SWAP | 4,716,062 | 17.4% |
| STORE_FAST | 3,331,415 | 12.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 5.7% |
| CALL_FUNCTION_EX | 734,880 | 2.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,324 | 64.1% |
| SWAP | 18,000 | 35.7% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,324 | 64.1% |
| SWAP | 18,000 | 35.7% |
| STORE_FAST | 80 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,012 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 3,840 | 95.7% |
| BINARY_SUBSCR | 172 | 4.3% |


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
| LOAD_FAST_LOAD_FAST | 18,992,617 | 45.0% |
| LOAD_FAST | 10,102,353 | 23.9% |
| LOAD_ATTR_SLOT | 5,042,180 | 11.9% |
| LOAD_ATTR | 3,033,718 | 7.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,220,927 | 50.2% |
| LOAD_GLOBAL_BUILTIN | 4,707,042 | 11.1% |
| BUILD_MAP | 4,366,358 | 10.3% |
| LOAD_CONST | 3,395,601 | 8.0% |
| CALL_LIST_APPEND | 3,214,240 | 7.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,376,072 | 34.9% |
| LOAD_FAST | 7,269,749 | 27.1% |
| BINARY_OP_MULTIPLY_INT | 2,291,866 | 8.5% |
| ENTER_EXECUTOR | 2,266,527 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 1,572,928 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,405 | 40.8% |
| STORE_FAST | 5,844,789 | 21.8% |
| RETURN_VALUE | 4,522,413 | 16.8% |
| POP_TOP | 1,135,170 | 4.2% |
| RESUME_CHECK | 1,065,630 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 16,636,355 | 59.4% |
| ENTER_EXECUTOR | 7,551,049 | 27.0% |
| LOAD_FAST | 1,403,618 | 5.0% |
| CALL_INTRINSIC_1 | 1,256,762 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,600,832 | 45.0% |
| RESUME_CHECK | 11,673,489 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,861 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,347,866 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,762 | 93.2% |
| BUILD_MAP | 91,264 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,508,771 | 98.5% |
| ENTER_EXECUTOR | 164,380 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,164 | 88.9% |
| POP_TOP | 698,041 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,817 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,085,897 | 57.2% |
| LOAD_FAST | 6,659,649 | 18.1% |
| CALL_TYPE_1 | 5,882,503 | 15.9% |
| LOAD_GLOBAL_MODULE | 1,180,308 | 3.2% |
| LOAD_CONST | 949,629 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,505,787 | 50.2% |
| BINARY_OP | 6,162,400 | 16.7% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.7% |
| UNARY_NOT | 3,442,667 | 9.3% |
| POP_JUMP_IF_TRUE | 2,275,236 | 6.2% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,642,915 | 45.2% |
| LOAD_ATTR | 3,188,634 | 25.6% |
| LOAD_GLOBAL_MODULE | 1,646,026 | 13.2% |
| LOAD_DEREF | 1,478,140 | 11.8% |
| LOAD_CONST | 174,993 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,731,574 | 78.0% |
| POP_JUMP_IF_TRUE | 2,735,168 | 21.9% |
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
| LOAD_CONST | 236,784 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,334,367 | 28.9% |
| COPY | 1,069,360 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,063,080 | 23.0% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,584 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 12,999,320 | 41.1% |
| ENTER_EXECUTOR | 7,037,865 | 22.2% |
| LOAD_ATTR_PROPERTY | 5,066,201 | 16.0% |
| CALL_PY_EXACT_ARGS | 4,710,849 | 14.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,194,795 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,678,667 | 68.5% |
| RETURN_GENERATOR | 9,894,905 | 31.3% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,188 | 0.0% |


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
| RETURN_CONST | 20 | 16.7% |
| BUILD_LIST | 20 | 16.7% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,571,422 | 99.6% |
| LOAD_DEREF | 64,933 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 16,636,355 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 22,685,732 | 19.1% |
| CALL_LIST_APPEND | 17,314,692 | 14.6% |
| POP_JUMP_IF_TRUE | 15,267,649 | 12.8% |
| POP_JUMP_IF_NONE | 15,174,623 | 12.8% |
| POP_JUMP_IF_FALSE | 14,188,938 | 11.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 18,301,111 | 15.4% |
| POP_JUMP_IF_FALSE | 11,989,666 | 10.1% |
| RESUME_CHECK | 9,631,914 | 8.1% |
| FOR_ITER_LIST | 9,279,788 | 7.8% |
| FOR_ITER_TUPLE | 8,743,529 | 7.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,063,516 | 29.7% |
| CALL_LIST_APPEND | 4,571,162 | 26.8% |
| GET_ITER | 2,378,128 | 13.9% |
| ENTER_EXECUTOR | 1,742,150 | 10.2% |
| COMPARE_OP_INT | 1,718,060 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,645,194 | 38.9% |
| ENTER_EXECUTOR | 5,768,704 | 33.8% |
| FOR_ITER_LIST | 2,686,865 | 15.7% |
| FOR_ITER_TUPLE | 767,880 | 4.5% |
| FOR_ITER_RANGE | 642,400 | 3.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 18,942,174 | 55.5% |
| LOAD_FAST | 7,625,084 | 22.3% |
| SWAP | 6,724,738 | 19.7% |
| ENTER_EXECUTOR | 726,021 | 2.1% |
| JUMP_BACKWARD | 71,666 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 24,593,545 | 72.0% |
| ENTER_EXECUTOR | 2,590,074 | 7.6% |
| LOAD_FAST | 2,495,188 | 7.3% |
| SWAP | 1,295,617 | 3.8% |
| DELETE_FAST | 1,284,800 | 3.8% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,758,154 | 86.6% |
| STORE_FAST | 982,451 | 11.0% |
| STORE_DEREF | 185,700 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,821,819 | 76.2% |
| STORE_DEREF | 2,092,426 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,758,914 | 100.0% |
| ENTER_EXECUTOR | 740 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,758,154 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 14,930,450 | 32.8% |
| LOAD_FAST | 12,891,660 | 28.3% |
| LOAD_CONST | 10,976,471 | 24.1% |
| LOAD_FAST_LOAD_FAST | 5,893,543 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 539,781 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,996,396 | 65.8% |
| YIELD_VALUE | 12,876,321 | 28.3% |
| POP_JUMP_IF_TRUE | 2,641,678 | 5.8% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 90,403 | 24.5% |
| POP_TOP | 61,022 | 16.5% |
| LIST_APPEND | 52,035 | 14.1% |
| STORE_FAST | 34,469 | 9.3% |
| POP_JUMP_IF_TRUE | 29,941 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 100,618 | 27.2% |
| FOR_ITER_TUPLE | 80,774 | 21.9% |
| FOR_ITER | 71,666 | 19.4% |
| FOR_ITER_LIST | 53,867 | 14.6% |
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
| STORE_FAST | 4,138,296 | 72.1% |
| POP_TOP | 734,242 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,876 | 3.3% |
| LOAD_FAST | 137,463 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,996,535 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,148 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,642 | 5.7% |
| STORE_FAST | 119,063 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,144,693 | 44.8% |
| BUILD_TUPLE | 653,922 | 25.6% |
| RETURN_VALUE | 510,791 | 20.0% |
| LOAD_ATTR_PROPERTY | 64,511 | 2.5% |
| BINARY_SUBSCR | 37,832 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,500,138 | 97.8% |
| JUMP_BACKWARD | 52,035 | 2.0% |
| LOAD_NAME | 4,800 | 0.2% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,346,986 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,347,866 | 99.9% |
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
| LOAD_FAST | 50,961,248 | 55.5% |
| LOAD_GLOBAL_MODULE | 33,545,961 | 36.5% |
| CALL_TYPE_1 | 2,352,295 | 2.6% |
| LOAD_ATTR_SLOT | 2,297,046 | 2.5% |
| LOAD_GLOBAL_BUILTIN | 1,905,126 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 34,995,100 | 38.1% |
| LOAD_FAST | 15,959,626 | 17.4% |
| IS_OP | 14,930,450 | 16.3% |
| PUSH_NULL | 8,321,260 | 9.1% |
| CONTAINS_OP | 3,188,634 | 3.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,373,900 | 35.2% |
| LOAD_CONST | 40,207,259 | 23.5% |
| RESUME_CHECK | 15,611,293 | 9.1% |
| RETURN_CONST | 9,526,680 | 5.6% |
| CALL_LEN | 7,178,294 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,207,259 | 23.5% |
| CALL_BUILTIN_FAST | 23,937,290 | 14.0% |
| COMPARE_OP_INT | 20,725,642 | 12.1% |
| STORE_FAST | 14,264,410 | 8.3% |
| IS_OP | 10,976,471 | 6.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 10,423,969 | 20.6% |
| STORE_FAST_STORE_FAST | 9,273,892 | 18.4% |
| LOAD_ATTR_SLOT | 6,404,499 | 12.7% |
| POP_JUMP_IF_FALSE | 4,643,960 | 9.2% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,060 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 11,785,176 | 23.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,447,916 | 18.7% |
| LOAD_FAST | 9,344,644 | 18.5% |
| BINARY_SUBSCR | 6,404,499 | 12.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 6.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,569,090 | 19.1% |
| LOAD_GLOBAL_BUILTIN | 140,544,330 | 16.9% |
| RESUME_CHECK | 115,543,074 | 13.9% |
| POP_JUMP_IF_FALSE | 106,075,281 | 12.7% |
| PUSH_NULL | 35,232,285 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,054,976 | 11.3% |
| LOAD_ATTR_METHOD_NO_DICT | 73,183,167 | 8.8% |
| LOAD_CONST | 60,373,900 | 7.2% |
| RETURN_VALUE | 52,944,994 | 6.4% |
| LOAD_GLOBAL_MODULE | 51,679,665 | 6.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,282,730 | 55.4% |
| LOAD_FAST_AND_CLEAR | 6,674,304 | 44.6% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 8,282,650 | 55.4% |
| LOAD_FAST_AND_CLEAR | 6,674,304 | 44.6% |
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
| STORE_FAST | 43,472,050 | 21.3% |
| POP_JUMP_IF_FALSE | 28,846,358 | 14.1% |
| LOAD_GLOBAL_BUILTIN | 28,347,882 | 13.9% |
| STORE_FAST_STORE_FAST | 14,727,797 | 7.2% |
| POP_JUMP_IF_NONE | 13,278,704 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 21,085,897 | 10.3% |
| BINARY_SUBSCR_LIST_INT | 19,367,132 | 9.5% |
| BUILD_TUPLE | 18,992,617 | 9.3% |
| STORE_SUBSCR_LIST_INT | 18,848,298 | 9.2% |
| CALL_BUILTIN_FAST | 17,202,782 | 8.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,286 | 19.4% |
| LOAD_FAST | 34,226 | 18.8% |
| STORE_FAST | 26,948 | 14.8% |
| RESUME_CHECK | 10,940 | 6.0% |
| RESUME | 10,788 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,580 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,270 | 22.7% |
| LOAD_FAST | 39,620 | 21.8% |
| LOAD_ATTR | 14,084 | 7.7% |
| CALL | 9,832 | 5.4% |


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
| LOAD_FAST | 1,086 | 90.0% |
| LOAD_DEREF | 120 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 500 | 41.5% |
| CALL | 326 | 27.0% |
| LOAD_FAST | 180 | 14.9% |
| PUSH_NULL | 100 | 8.3% |
| LOAD_SUPER_ATTR_ATTR | 100 | 8.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,274,691 | 37.6% |
| CACHE | 1,509,080 | 24.9% |
| CALL_PY_EXACT_ARGS | 768,725 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,313 | 10.8% |
| CALL | 523,686 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,770,995 | 62.3% |
| MAKE_CELL | 2,274,691 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,853,170 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,862,893 | 100.0% |
| JUMP_BACKWARD | 2,397 | 0.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 105,224,960 | 40.9% |
| COMPARE_OP_INT | 33,141,090 | 12.9% |
| IS_OP | 29,996,396 | 11.7% |
| COMPARE_OP | 18,505,787 | 7.2% |
| COMPARE_OP_STR | 14,480,767 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 106,075,281 | 41.3% |
| LOAD_GLOBAL_BUILTIN | 57,849,772 | 22.5% |
| LOAD_FAST_LOAD_FAST | 28,846,358 | 11.2% |
| RETURN_CONST | 27,756,337 | 10.8% |
| ENTER_EXECUTOR | 14,188,938 | 5.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 18,301,111 | 54.1% |
| LOAD_FAST | 8,991,956 | 26.6% |
| BINARY_SUBSCR | 5,416,811 | 16.0% |
| LOAD_DEREF | 1,088,842 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,174,623 | 44.9% |
| LOAD_FAST_LOAD_FAST | 13,278,704 | 39.3% |
| LOAD_FAST | 2,501,168 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 1,438,181 | 4.3% |
| LOAD_CONST | 1,111,414 | 3.3% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,629,996 | 92.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,224,976 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,226,803 | 67.7% |
| LOAD_FAST_LOAD_FAST | 2,011,654 | 11.1% |
| LOAD_GLOBAL_MODULE | 1,878,564 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,226 | 7.7% |
| ENTER_EXECUTOR | 447,585 | 2.5% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 48,117,728 | 70.3% |
| TO_BOOL_INT | 8,151,749 | 11.9% |
| CONTAINS_OP | 2,735,168 | 4.0% |
| IS_OP | 2,641,678 | 3.9% |
| COMPARE_OP | 2,275,236 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,433,692 | 48.9% |
| ENTER_EXECUTOR | 15,267,649 | 22.3% |
| LOAD_GLOBAL_BUILTIN | 5,255,029 | 7.7% |
| NOP | 4,183,901 | 6.1% |
| BUILD_LIST | 4,083,246 | 6.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,922 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,262 | 98.4% |
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
| POP_JUMP_IF_FALSE | 27,756,337 | 51.1% |
| RESUME_CHECK | 10,045,317 | 18.5% |
| FOR_ITER_LIST | 5,672,097 | 10.4% |
| ENTER_EXECUTOR | 4,689,456 | 8.6% |
| STORE_SUBSCR | 1,917,971 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,284,005 | 59.4% |
| LOAD_CONST | 9,526,680 | 17.5% |
| POP_TOP | 8,002,589 | 14.7% |
| TO_BOOL_BOOL | 1,922,953 | 3.5% |
| STORE_FAST | 1,541,147 | 2.8% |


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
| MAKE_FUNCTION | 3,376,419 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,816,552 | 83.4% |
| STORE_FAST | 307,013 | 9.1% |
| STORE_DEREF | 95,652 | 2.8% |
| LOAD_CONST | 52,360 | 1.6% |
| LOAD_GLOBAL_MODULE | 42,928 | 1.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,854 | 82.3% |
| LOAD_FAST | 98,460 | 16.6% |
| STORE_ATTR | 3,908 | 0.7% |
| SWAP | 2,157 | 0.4% |
| LOAD_DEREF | 16 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,672 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,262 | 19.7% |
| LOAD_FAST | 89,985 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,577,880 | 46.4% |
| IMPORT_FROM | 2,092,426 | 27.1% |
| LOAD_ATTR | 1,558,830 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,652 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,840 | 46.4% |
| POP_TOP | 1,906,726 | 24.7% |
| LOAD_DEREF | 1,298,330 | 16.8% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.2% |
| IMPORT_FROM | 185,700 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,447,957 | 13.5% |
| LOAD_ATTR | 34,995,100 | 12.2% |
| BINARY_OP | 24,134,448 | 8.4% |
| LOAD_ATTR_SLOT | 22,510,387 | 7.9% |
| LOAD_CONST | 14,264,410 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,569,090 | 55.8% |
| LOAD_FAST_LOAD_FAST | 43,472,050 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 29,940,948 | 10.5% |
| LOAD_GLOBAL_MODULE | 11,162,573 | 3.9% |
| STORE_FAST | 9,340,999 | 3.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,333 | 71.8% |
| FOR_ITER_TUPLE | 409,292 | 23.3% |
| FOR_ITER_RANGE | 47,440 | 2.7% |
| FOR_ITER | 38,161 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,178,902 | 67.2% |
| LOAD_ATTR_PROPERTY | 190,960 | 10.9% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 187,521 | 10.7% |
| LOAD_DEREF | 49,680 | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,840 | 2.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 42,823,175 | 86.5% |
| RETURN_VALUE | 3,248,191 | 6.6% |
| UNPACK_SEQUENCE_TUPLE | 1,397,163 | 2.8% |
| STORE_FAST_STORE_FAST | 771,709 | 1.6% |
| BUILD_LIST | 413,120 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 14,727,797 | 29.7% |
| LOAD_FAST | 13,892,969 | 28.1% |
| LOAD_DEREF | 9,273,892 | 18.7% |
| LOAD_GLOBAL_BUILTIN | 8,512,985 | 17.2% |
| LOAD_GLOBAL_MODULE | 1,036,320 | 2.1% |


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
| BINARY_SUBSCR_LIST_INT | 9,395,679 | 21.8% |
| LOAD_FAST_AND_CLEAR | 8,282,650 | 19.2% |
| ENTER_EXECUTOR | 6,307,185 | 14.6% |
| BUILD_MAP | 4,716,062 | 10.9% |
| LOAD_FAST | 4,609,952 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,395,899 | 21.8% |
| STORE_FAST | 7,930,999 | 18.4% |
| FOR_ITER | 6,724,738 | 15.6% |
| POP_TOP | 5,747,132 | 13.3% |
| BUILD_MAP | 4,716,062 | 10.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,464 | 26.3% |
| FOR_ITER | 6,804 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 15.9% |
| LOAD_FAST | 3,972 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,684 | 47.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,434 | 23.7% |
| STORE_FAST | 8,101 | 20.4% |
| UNPACK_SEQUENCE_TUPLE | 1,146 | 2.9% |
| UNPACK_SEQUENCE | 916 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,876,321 | 55.6% |
| ENTER_EXECUTOR | 4,974,528 | 21.5% |
| CALL_ISINSTANCE | 2,232,684 | 9.6% |
| LOAD_FAST | 1,140,750 | 4.9% |
| YIELD_VALUE | 677,448 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,293,826 | 96.3% |
| YIELD_VALUE | 677,448 | 2.9% |
| STORE_FAST | 162,927 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,057 | 38.0% |
| CALL | 11,116 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,102 | 12.8% |
| POP_TOP | 3,961 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,702 | 37.2% |
| LOAD_GLOBAL | 10,788 | 22.7% |
| LOAD_CONST | 8,763 | 18.4% |
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
| LOAD_CONST | 2,608,027 | 69.4% |
| LOAD_FAST_LOAD_FAST | 573,908 | 15.3% |
| BINARY_SUBSCR_DICT | 420,640 | 11.2% |
| CALL_BUILTIN_CLASS | 81,183 | 2.2% |
| LOAD_FAST | 43,684 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,549,831 | 41.3% |
| SWAP | 942,337 | 25.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 540,149 | 14.4% |
| LOAD_CONST | 269,074 | 7.2% |
| LOAD_FAST | 201,560 | 5.4% |


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
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,677 | 60.5% |
| LOAD_ATTR_SLOT | 723,522 | 26.2% |
| LOAD_FAST_LOAD_FAST | 269,819 | 9.8% |
| LOAD_FAST | 94,300 | 3.4% |
| BINARY_OP | 1,468 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,866 | 83.1% |
| LOAD_FAST_LOAD_FAST | 181,168 | 6.6% |
| STORE_FAST | 175,597 | 6.4% |
| LOAD_FAST | 76,508 | 2.8% |
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
| LOAD_CONST | 1,556,199 | 62.9% |
| LOAD_FAST_LOAD_FAST | 607,139 | 24.5% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,677 | 5.0% |
| BINARY_OP | 2,194 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,080,100 | 43.7% |
| STORE_FAST | 699,875 | 28.3% |
| BINARY_OP | 311,627 | 12.6% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,880 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,521 | 33.9% |
| LOAD_FAST_LOAD_FAST | 810,425 | 26.6% |
| LOAD_CONST | 642,800 | 21.1% |
| CALL_TUPLE_1 | 441,520 | 14.5% |
| RETURN_VALUE | 114,365 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 866,152 | 28.4% |
| RETURN_VALUE | 809,266 | 26.5% |
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
| LOAD_CONST | 14,542 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,238 | 100.0% |
| RETURN_VALUE | 2 | 0.0% |
| LOAD_CONST | 2 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 19,367,132 | 88.0% |
| COPY | 1,063,080 | 4.8% |
| LOAD_CONST | 1,025,987 | 4.7% |
| CALL_BUILTIN_CLASS | 282,540 | 1.3% |
| LOAD_FAST | 204,187 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,404,039 | 42.7% |
| SWAP | 9,395,679 | 42.7% |
| LOAD_CONST | 1,063,540 | 4.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 534,734 | 2.4% |
| RETURN_VALUE | 432,307 | 2.0% |


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
| LOAD_CONST | 8,718,667 | 97.0% |
| LOAD_FAST | 263,291 | 2.9% |
| BINARY_SUBSCR | 2,742 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,289 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 321,921 | 3.6% |
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
| LOAD_FAST | 13,127,566 | 91.3% |
| BINARY_OP_ADD_INT | 540,149 | 3.8% |
| LOAD_FAST_LOAD_FAST | 480,451 | 3.3% |
| LOAD_ATTR | 152,040 | 1.1% |
| RETURN_VALUE | 36,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,525,283 | 87.1% |
| COPY_FREE_VARS | 1,194,795 | 8.3% |
| MAKE_CELL | 654,313 | 4.5% |
| POP_TOP | 7,360 | 0.1% |
| RESUME | 620 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,795,980 | 33.0% |
| CALL_BUILTIN_CLASS | 1,959,324 | 23.1% |
| LOAD_CONST | 710,920 | 8.4% |
| CALL_LEN | 611,042 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 566,981 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,979,989 | 35.1% |
| CALL_BUILTIN_CLASS | 1,959,324 | 23.1% |
| GET_ITER | 1,728,223 | 20.4% |
| CALL | 284,408 | 3.4% |
| BINARY_SUBSCR_LIST_INT | 282,540 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 23,937,290 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,202,782 | 39.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,178 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 40,902 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 17,882,690 | 41.7% |
| STORE_FAST | 10,868,502 | 25.4% |
| TO_BOOL | 10,287,220 | 24.0% |
| PUSH_NULL | 2,128,620 | 5.0% |
| RETURN_VALUE | 1,500,056 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,762 | 94.4% |
| LOAD_FAST | 134,994 | 2.6% |
| BINARY_OP | 119,123 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,042 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 127,894 | 2.5% |
| CALL_BUILTIN_CLASS | 119,123 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,704,420 | 41.7% |
| RETURN_GENERATOR | 10,199,479 | 27.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,614,505 | 14.9% |
| LOAD_ATTR_SLOT | 4,878,097 | 13.0% |
| BINARY_OP | 1,095,129 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,588,114 | 36.1% |
| RETURN_VALUE | 11,432,754 | 30.4% |
| TO_BOOL_BOOL | 9,877,252 | 26.2% |
| GET_ITER | 2,591,114 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 29,352,027 | 54.3% |
| LOAD_GLOBAL_BUILTIN | 17,191,437 | 31.8% |
| LOAD_DEREF | 2,859,591 | 5.3% |
| LOAD_FAST_LOAD_FAST | 2,648,589 | 4.9% |
| LOAD_FAST | 1,614,924 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 51,183,316 | 94.7% |
| YIELD_VALUE | 2,232,684 | 4.1% |
| COPY | 525,020 | 1.0% |
| RETURN_VALUE | 71,531 | 0.1% |
| TO_BOOL | 9,666 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,053,334 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 173,720 | 0.6% |
| RETURN_VALUE | 95,090 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,270,144 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,675,851 | 34.5% |
| LOAD_CONST | 7,178,294 | 25.6% |
| CALL_BUILTIN_CLASS | 611,042 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,554,055 | 64.8% |
| BUILD_TUPLE | 3,214,240 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 963,240 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 17,314,692 | 72.1% |
| EXTENDED_ARG | 4,571,162 | 19.0% |
| LOAD_FAST | 1,681,751 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |
| JUMP_FORWARD | 191,876 | 0.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,880,052 | 44.9% |
| ENTER_EXECUTOR | 5,338,821 | 24.2% |
| LOAD_CONST | 2,332,543 | 10.6% |
| BUILD_LIST | 2,294,386 | 10.4% |
| BUILD_MAP | 1,561,360 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,921,280 | 58.7% |
| STORE_FAST | 3,361,531 | 15.3% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.2% |
| POP_TOP | 908,817 | 4.1% |
| GET_ITER | 737,586 | 3.3% |


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
| LOAD_ATTR_METHOD_NO_DICT | 22,644,422 | 81.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,604 | 17.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,788 | 0.4% |
| LOAD_ATTR | 72,820 | 0.3% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 12,589,337 | 45.5% |
| STORE_FAST | 9,686,453 | 35.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,762 | 17.7% |
| CALL_BUILTIN_CLASS | 169,737 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,788 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.3% |
| LOAD_CONST | 1,226,476 | 26.8% |
| LOAD_FAST | 290,680 | 6.3% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.5% |
| LOAD_CONST | 1,224,476 | 26.7% |
| TO_BOOL_NONE | 42,400 | 0.9% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,791,862 | 39.5% |
| LOAD_FAST | 15,177,699 | 28.9% |
| LOAD_FAST_LOAD_FAST | 6,009,215 | 11.4% |
| GET_ITER | 6,004,382 | 11.4% |
| LOAD_SUPER_ATTR_METHOD | 1,539,401 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 42,785,279 | 81.4% |
| COPY_FREE_VARS | 4,710,849 | 9.0% |
| RETURN_GENERATOR | 4,117,132 | 7.8% |
| MAKE_CELL | 768,725 | 1.5% |
| CALL_PY_EXACT_ARGS | 145,307 | 0.3% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,621,830 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,413,467 | 30.8% |
| ENTER_EXECUTOR | 974,955 | 21.2% |
| RETURN_VALUE | 192,643 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,926 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,373,193 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,731 | 1.2% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,042 | 80.5% |
| LOAD_FAST | 1,015,000 | 17.4% |
| STORE_FAST | 105,744 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,124 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,242 | 80.5% |
| BINARY_SUBSCR_DICT | 441,520 | 7.5% |
| STORE_FAST | 353,184 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,728,737 | 99.5% |
| LOAD_CONST | 65,982 | 0.4% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,082 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,606 | 43.4% |
| COMPARE_OP | 5,882,503 | 39.8% |
| LOAD_ATTR | 2,352,295 | 15.9% |
| IS_OP | 64,242 | 0.4% |
| STORE_FAST | 32,965 | 0.2% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,708 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,559 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,047 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,725,642 | 42.6% |
| LOAD_FAST_LOAD_FAST | 16,126,475 | 33.2% |
| CALL_LEN | 10,270,144 | 21.1% |
| LOAD_FAST | 971,243 | 2.0% |
| LOAD_ATTR_SLOT | 225,371 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,141,090 | 68.2% |
| BINARY_OP | 6,273,260 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.7% |
| EXTENDED_ARG | 1,718,060 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,534,520 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 69.1% |
| LOAD_CONST | 4,296,229 | 29.6% |
| LOAD_GLOBAL_MODULE | 192,442 | 1.3% |
| LOAD_FAST | 2,040 | 0.0% |
| LOAD_ATTR | 1,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,480,767 | 99.7% |
| YIELD_VALUE | 40,164 | 0.3% |
| POP_JUMP_IF_TRUE | 2,080 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,618 | 52.6% |
| GET_ITER | 90,717 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,698 | 52.1% |
| POP_TOP | 90,557 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,279,788 | 41.4% |
| LOAD_FAST | 4,844,109 | 21.6% |
| GET_ITER | 4,316,163 | 19.3% |
| EXTENDED_ARG | 2,686,865 | 12.0% |
| SWAP | 1,219,676 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,052,414 | 40.4% |
| RETURN_CONST | 5,672,097 | 25.3% |
| LOAD_FAST | 4,094,217 | 18.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,503,106 | 6.7% |
| STORE_FAST_LOAD_FAST | 1,260,333 | 5.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 827,336 | 37.2% |
| GET_ITER | 669,102 | 30.1% |
| EXTENDED_ARG | 642,400 | 28.9% |
| SWAP | 38,880 | 1.7% |
| LOAD_FAST | 29,360 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,775 | 58.7% |
| RETURN_CONST | 630,262 | 28.3% |
| LOAD_FAST | 195,180 | 8.8% |
| STORE_FAST_LOAD_FAST | 47,440 | 2.1% |
| SWAP | 38,520 | 1.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,972,840 | 48.9% |
| ENTER_EXECUTOR | 8,743,529 | 42.9% |
| EXTENDED_ARG | 767,880 | 3.8% |
| LOAD_FAST | 518,395 | 2.5% |
| SWAP | 299,436 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,208,385 | 50.1% |
| LOAD_FAST | 7,494,754 | 36.7% |
| RETURN_CONST | 788,705 | 3.9% |
| LOAD_GLOBAL_MODULE | 602,502 | 3.0% |
| STORE_FAST_LOAD_FAST | 409,292 | 2.0% |


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
| LOAD_FAST | 5,478,752 | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,061,009 | 11.7% |
| LOAD_DEREF | 1,058,469 | 11.7% |
| COPY | 956,400 | 10.6% |
| LOAD_GLOBAL_MODULE | 481,590 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,416 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,178 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,224,976 | 13.5% |
| STORE_FAST | 1,076,169 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,061,009 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,183,167 | 84.7% |
| RETURN_VALUE | 4,635,642 | 5.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.6% |
| LOAD_GLOBAL_MODULE | 1,964,841 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,416 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,561,340 | 34.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 22,644,422 | 26.2% |
| CALL_PY_EXACT_ARGS | 20,791,862 | 24.1% |
| LOAD_CONST | 4,051,206 | 4.7% |
| LOAD_DEREF | 3,319,060 | 3.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 9,447,916 | 52.8% |
| LOAD_ATTR_SLOT | 4,711,142 | 26.3% |
| LOAD_FAST | 3,528,633 | 19.7% |
| LOAD_ATTR | 147,513 | 0.8% |
| STORE_FAST_LOAD_FAST | 45,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,810,942 | 54.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,604 | 26.8% |
| LOAD_FAST_LOAD_FAST | 2,958,449 | 16.5% |
| CALL_PY_EXACT_ARGS | 318,962 | 1.8% |
| LOAD_CONST | 6,630 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260,978 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,404 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,359 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,683 | 6.3% |
| CALL | 57,380 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR_SLOT | 15,920 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,062,733 | 83.2% |
| ENTER_EXECUTOR | 5,159,645 | 9.1% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 212,656 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,045,846 | 74.4% |
| CALL_BUILTIN_O | 5,614,505 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,921,525 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,677 | 3.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 988,089 | 60.0% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.1% |
| LOAD_DEREF | 144,340 | 8.8% |
| ENTER_EXECUTOR | 14,246 | 0.9% |
| LOAD_ATTR | 12,020 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.1% |
| TO_BOOL_STR | 478,200 | 29.1% |
| TO_BOOL_BOOL | 409,641 | 24.9% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,064,239 | 89.5% |
| ENTER_EXECUTOR | 1,562,034 | 5.6% |
| RETURN_VALUE | 642,460 | 2.3% |
| STORE_FAST_LOAD_FAST | 190,960 | 0.7% |
| LOAD_DEREF | 190,722 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,813,434 | 67.2% |
| COPY_FREE_VARS | 5,066,201 | 18.1% |
| GET_ITER | 1,920,029 | 6.9% |
| TO_BOOL_BOOL | 712,129 | 2.5% |
| STORE_FAST | 505,528 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,054,976 | 98.5% |
| ENTER_EXECUTOR | 632,540 | 0.7% |
| LOAD_ATTR_SLOT | 613,656 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,061 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 69,979 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,432,611 | 35.0% |
| STORE_FAST | 22,510,387 | 23.6% |
| LOAD_DEREF | 6,404,499 | 6.7% |
| LOAD_FAST | 5,219,565 | 5.5% |
| LOAD_CONST | 5,210,033 | 5.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,849,772 | 27.8% |
| RESUME_CHECK | 41,203,824 | 19.8% |
| STORE_FAST | 29,940,948 | 14.4% |
| LOAD_FAST | 18,551,082 | 8.9% |
| CALL_LEN | 9,675,851 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,544,330 | 67.6% |
| LOAD_FAST_LOAD_FAST | 28,347,882 | 13.6% |
| CALL_ISINSTANCE | 17,191,437 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 8,864,560 | 4.3% |
| LOAD_DEREF | 3,164,147 | 1.5% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,679,665 | 46.9% |
| RESUME_CHECK | 16,025,877 | 14.5% |
| STORE_FAST | 11,162,573 | 10.1% |
| POP_JUMP_IF_FALSE | 9,672,617 | 8.8% |
| NOP | 6,377,604 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 33,545,961 | 30.4% |
| CALL_ISINSTANCE | 29,352,027 | 26.6% |
| LOAD_FAST | 28,280,725 | 25.7% |
| LOAD_DEREF | 3,256,038 | 3.0% |
| LOAD_FAST_LOAD_FAST | 3,201,932 | 2.9% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,565 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,181,965 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,651 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,401 | 85.1% |
| LOAD_GLOBAL_MODULE | 172,250 | 9.5% |
| LOAD_FAST | 78,580 | 4.3% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 99,262,085 | 39.7% |
| CALL_PY_EXACT_ARGS | 42,785,279 | 17.1% |
| COPY_FREE_VARS | 21,678,667 | 8.7% |
| LOAD_ATTR_PROPERTY | 18,813,434 | 7.5% |
| POP_TOP | 14,333,297 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,543,074 | 46.2% |
| LOAD_GLOBAL_BUILTIN | 41,203,824 | 16.5% |
| NOP | 21,364,054 | 8.5% |
| LOAD_GLOBAL_MODULE | 16,025,877 | 6.4% |
| LOAD_CONST | 15,611,293 | 6.2% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 661,220 | 64.2% |
| LOAD_CONST | 367,948 | 35.7% |
| SEND | 620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 646,240 | 62.8% |
| POP_TOP | 352,888 | 34.3% |
| YIELD_VALUE | 15,060 | 1.5% |
| END_SEND | 15,020 | 1.5% |
| SEND | 580 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,674 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,137 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,659 | 36.0% |
| RETURN_CONST | 887,342 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,351 | 52.2% |
| LOAD_FAST | 4,285,004 | 47.3% |
| STORE_ATTR_SLOT | 41,753 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,673,131 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,300 | 24.9% |
| LOAD_CONST | 1,890,711 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,853 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,568,597 | 68.9% |
| LOAD_FAST | 396,628 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,337 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,647,189 | 72.4% |
| EXTENDED_ARG | 226,736 | 10.0% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.1% |
| LOAD_FAST | 164,822 | 7.2% |
| LOAD_GLOBAL_MODULE | 38,957 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,848,298 | 93.9% |
| SWAP | 1,063,080 | 5.3% |
| LOAD_FAST | 98,931 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |
| LOAD_CONST | 20,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,018,419 | 49.9% |
| ENTER_EXECUTOR | 9,993,030 | 49.8% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |
| LOAD_CONST | 19,800 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 224,161 | 98.5% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| ENTER_EXECUTOR | 860 | 0.4% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| TO_BOOL | 387 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 216,426 | 95.1% |
| POP_JUMP_IF_FALSE | 9,691 | 4.3% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 51 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 51,183,316 | 32.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,045,846 | 26.4% |
| LOAD_FAST | 21,602,177 | 13.5% |
| CALL_BUILTIN_FAST | 17,882,690 | 11.2% |
| CALL_BUILTIN_O | 9,877,252 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 105,224,960 | 66.0% |
| POP_JUMP_IF_TRUE | 48,117,728 | 30.2% |
| EXTENDED_ARG | 5,063,516 | 3.2% |
| UNARY_NOT | 1,085,007 | 0.7% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,626,318 | 95.3% |
| BINARY_OP | 722,340 | 3.9% |
| BINARY_SUBSCR_TUPLE_INT | 63,293 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,280 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,859 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,350,703 | 55.9% |
| POP_JUMP_IF_TRUE | 8,151,749 | 44.1% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 168 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,228,464 | 97.5% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,111 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |
| TO_BOOL | 2,148 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 823,489 | 36.0% |
| POP_JUMP_IF_TRUE | 784,548 | 34.3% |
| UNARY_NOT | 661,866 | 29.0% |
| EXTENDED_ARG | 15,720 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,744 | 69.6% |
| RETURN_VALUE | 389,026 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,483 | 11.1% |
| CALL_METHOD_DESCRIPTOR_O | 42,400 | 1.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,049 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,938,463 | 73.2% |
| POP_JUMP_IF_TRUE | 689,994 | 26.1% |
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
| LOAD_FAST | 120,306 | 67.4% |
| RETURN_VALUE | 49,120 | 27.5% |
| CALL_BUILTIN_CLASS | 2,600 | 1.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,760 | 1.0% |
| BINARY_SUBSCR_LIST_INT | 1,240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 64.4% |
| STORE_FAST_STORE_FAST | 63,626 | 35.6% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 885,174 | 55.6% |
| RETURN_VALUE | 660,894 | 41.5% |
| STORE_FAST | 40,240 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,146 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,397,163 | 87.8% |
| STORE_FAST | 154,791 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 24,593,545 | 52.8% |
| RETURN_VALUE | 19,465,547 | 41.8% |
| FOR_ITER_LIST | 1,503,106 | 3.2% |
| BINARY_SUBSCR_LIST_INT | 534,734 | 1.1% |
| FOR_ITER_TUPLE | 319,719 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 42,823,175 | 91.9% |
| STORE_DEREF | 3,577,880 | 7.7% |
| STORE_FAST | 215,333 | 0.5% |
| UNPACK_SEQUENCE_LIST | 1,760 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,320 | 0.0% |


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
|     deferred | 34,031,984 | 78.0% |
|          hit | 9,542,240 | 21.9% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,812 | 11.9% |
| Failure | 50,500 | 88.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,464 | 18.7% |
| multiply different types | 7,164 | 14.2% |
| subtract other | 6,740 | 13.3% |
| and int | 4,125 | 8.2% |
| rshift | 3,808 | 7.5% |
| or | 3,700 | 7.3% |
| power | 2,868 | 5.7% |
| true divide different types | 2,523 | 5.0% |
| multiply other | 2,260 | 4.5% |
| remainder | 2,070 | 4.1% |
| add different types | 1,825 | 3.6% |
| floor divide | 1,276 | 2.5% |
| subtract different types | 1,185 | 2.3% |
| xor | 584 | 1.2% |
| and other | 376 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 228 | 0.5% |
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
|     deferred | 20,278,718 | 37.2% |
|          hit | 34,204,762 | 62.7% |
|         miss | 14,927 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,722 | 34.4% |
| Failure | 14,743 | 65.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 11,439 | 77.6% |
| out of range | 1,960 | 13.3% |
| buffer int | 1,320 | 9.0% |
| array int | 20 | 0.1% |
| tuple slice | 4 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,121,409 | 6.7% |
|        deopt | 22,840 | 0.0% |
|          hit | 330,125,403 | 85.0% |
|         miss | 31,541,984 | 8.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 675,603 | 90.3% |
| Failure | 72,921 | 9.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,656 | 39.3% |
| code complex parameters | 14,052 | 19.3% |
| class no vectorcall | 9,220 | 12.6% |
| cfunc varargs keywords | 6,386 | 8.8% |
| other | 3,039 | 4.2% |
| wrong number arguments | 2,520 | 3.5% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,172 | 3.0% |
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
|     deferred | 36,800,461 | 36.6% |
|          hit | 63,095,958 | 62.7% |
|         miss | 575,928 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,470 | 22.9% |
| Failure | 68,827 | 77.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,415 | 26.8% |
| other | 15,216 | 22.1% |
| different types | 12,195 | 17.7% |
| tuple | 10,060 | 14.6% |
| string | 9,960 | 14.5% |
| bool | 1,781 | 2.6% |
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
|     deferred | 34,077,626 | 42.9% |
|          hit | 44,736,429 | 56.4% |
|         miss | 482,835 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,990 | 27.8% |
| Failure | 54,575 | 72.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 35,417 | 64.9% |
| zip | 4,980 | 9.1% |
| set | 4,454 | 8.2% |
| enumerate | 3,564 | 6.5% |
| other | 1,980 | 3.6% |
| itertools | 1,840 | 3.4% |
| dict keys | 1,400 | 2.6% |
| reversed list | 780 | 1.4% |
| dict values | 80 | 0.1% |
| ascii string | 80 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 90,404,494 | 23.3% |
|        deopt | 20 | 0.0% |
|          hit | 230,886,919 | 59.4% |
|         miss | 65,671,933 | 16.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,316,845 | 89.7% |
| Failure | 151,724 | 10.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mutable class | 58,663 | 38.7% |
| metaclass attribute | 53,195 | 35.1% |
| method | 10,384 | 6.8% |
| overridden | 8,672 | 5.7% |
| has managed dict | 8,580 | 5.7% |
| shadowed | 5,300 | 3.5% |
| class method obj | 3,880 | 2.6% |
| builtin class method | 1,320 | 0.9% |
| not managed dict | 750 | 0.5% |
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
|     deferred | 89,943 | 0.0% |
|          hit | 318,240,711 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 92,010 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 606 | 0.0% |
|          hit | 2,990,116 | 100.0% |

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
|          hit | 999,128 | 67.8% |
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
|     deferred | 540,674 | 4.2% |
|          hit | 10,198,835 | 78.4% |
|         miss | 2,220,144 | 17.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,813 | 92.3% |
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
|     deferred | 2,013,419 | 8.3% |
|          hit | 22,359,195 | 91.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,724 | 44.7% |
| Failure | 3,364 | 55.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 3,364 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,823,218 | 6.5% |
|          hit | 183,219,429 | 93.2% |
|         miss | 440,239 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,957 | 72.3% |
| Failure | 22,950 | 27.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,774 | 46.9% |
| number | 3,503 | 15.3% |
| mapping | 3,300 | 14.4% |
| dict | 2,260 | 9.8% |
| other | 1,639 | 7.1% |
| set | 1,434 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,585 | 0.1% |
|          hit | 48,391,068 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,400 | 93.6% |
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
| Basic | 2,684,687,301 | 54.1% |
| Not specialized | 638,252,293 | 12.9% |
| Specialized hits | 1,534,879,134 | 31.0% |
| Specialized misses | 100,999,230 | 2.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 90,404,494 | 35.1% |
| COMPARE_OP | 36,800,461 | 14.3% |
| FOR_ITER | 34,077,626 | 13.2% |
| BINARY_OP | 34,031,984 | 13.2% |
| CALL | 26,121,409 | 10.1% |
| BINARY_SUBSCR | 20,278,718 | 7.9% |
| TO_BOOL | 12,823,218 | 5.0% |
| STORE_SUBSCR | 2,013,419 | 0.8% |
| STORE_ATTR | 540,674 | 0.2% |
| SEND | 439,140 | 0.2% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,447,152 | 36.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,597,882 | 15.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,510,753 | 14.4% |
| LOAD_ATTR_METHOD_NO_DICT | 9,031,789 | 8.9% |
| CALL_PY_EXACT_ARGS | 7,815,313 | 7.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,350 | 6.4% |
| LOAD_ATTR_PROPERTY | 4,107,128 | 4.1% |
| CALL_BUILTIN_O | 2,661,158 | 2.6% |
| STORE_ATTR_SLOT | 2,219,164 | 2.2% |
| COMPARE_OP_INT | 574,328 | 0.6% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,686,175 | 51.5% |
| Calls to Python functions inlined | 120,142,673 | 48.5% |
| Calls via PyEval_EvalFrame (total) | 127,686,175 | 51.5% |
| Calls via PyEval_EvalFrame (vector) | 98,449,581 | 39.7% |
| Calls via PyEval_EvalFrame (generator) | 29,236,594 | 11.8% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,442,281 | 39.7% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,089 | 9.6% |
| Calls via PyEval_EvalFrame (function ex) | 11,824,959 | 4.8% |
| Calls via PyEval_EvalFrame (api) | 53,322,523 | 21.5% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,077 | 0.5% |
| Frames pushed | 112,557,301 | 45.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,405,766 | 54.3% |
| Frees to freelist | 363,648,681 |  |
| Allocations | 305,587,136 | 45.7% |
| Allocations to 512 bytes | 304,525,265 | 45.5% |
| Allocations to 4 kbytes | 1,037,411 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,257,986 |  |
| New values | 1,057,359 |  |
| Interpreter increfs | 2,687,644,946 | 65.3% |
| Interpreter decrefs | 3,112,919,748 | 66.3% |
| Increfs | 1,429,514,444 | 34.7% |
| Decrefs | 1,584,981,699 | 33.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,962,800 |  |
| Method cache misses | 3,801,320 |  |
| Method cache collisions | 4,886,541 |  |
| Method cache dunder hits | 347,326,320 |  |
| Method cache dunder misses | 1,085,887 |  |


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
| Optimization attempts | 14,052 |  |
| Traces created | 13,292 | 94.6% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 214 | 1.5% |
| Trace too long | 431 | 3.1% |
| Trace too short | 760 | 5.4% |
| Inner loop found | 260 | 1.9% |
| Recursive call | 160 | 1.1% |
| Traces executed | 118,887,203 |  |
| Uops executed | 2,220,392,808 | 18.68 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 2,684 | 20.2% |
| <= 32 | 5,253 | 39.5% |
| <= 64 | 3,680 | 27.7% |
| <= 128 | 1,675 | 12.6% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,664 | 20.0% |
| <= 16 | 4,319 | 32.5% |
| <= 32 | 3,969 | 29.9% |
| <= 64 | 2,200 | 16.6% |
| <= 128 | 140 | 1.1% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 1,948,215 | 1.6% |
| <= 2 | 28,407,904 | 23.9% |
| <= 4 | 737,876 | 0.6% |
| <= 8 | 23,142,184 | 19.5% |
| <= 16 | 13,534,528 | 11.4% |
| <= 32 | 34,702,392 | 29.2% |
| <= 64 | 12,314,870 | 10.4% |
| <= 128 | 2,718,134 | 2.3% |
| <= 256 | 1,233,672 | 1.0% |
| <= 512 | 135,666 | 0.1% |
| <= 1,024 | 7,235 | 0.0% |
| <= 2,048 | 4,107 | 0.0% |
| <= 4,096 | 40 | 0.0% |
| <= 8,192 | 280 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 100 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 320,736,044 | 14.4% | 14.4% |  |
| _CHECK_VALIDITY | 266,082,492 | 12.0% | 26.4% |  |
| LOAD_FAST | 247,071,162 | 11.1% | 37.6% |  |
| STORE_FAST | 189,633,369 | 8.5% | 46.1% |  |
| _FOR_ITER_TIER_TWO | 71,157,086 | 3.2% | 49.3% |  |
| _GUARD_GLOBALS_VERSION | 61,828,650 | 2.8% | 52.1% | 0.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 57,304,576 | 2.6% | 54.7% |  |
| _ITER_CHECK_LIST | 50,202,295 | 2.3% | 56.9% | 2.0% |
| _GUARD_NOT_EXHAUSTED_LIST | 49,212,600 | 2.2% | 59.1% | 19.6% |
| _GUARD_IS_FALSE_POP | 42,919,058 | 1.9% | 61.1% | 20.2% |
| CONTAINS_OP | 39,645,302 | 1.8% | 62.9% |  |
| _ITER_NEXT_LIST | 39,573,360 | 1.8% | 64.6% |  |
| _EXIT_TRACE | 38,103,452 | 1.7% | 66.4% |  |
| _JUMP_TO_TOP | 37,462,213 | 1.7% | 68.0% |  |
| _LOAD_GLOBAL_MODULE | 35,524,418 | 1.6% | 69.6% |  |
| _LOAD_ATTR | 29,839,722 | 1.3% | 71.0% |  |
| _GUARD_TYPE_VERSION | 27,055,528 | 1.2% | 72.2% | 21.1% |
| _GUARD_BUILTINS_VERSION | 25,804,147 | 1.2% | 73.4% |  |
| _LOAD_GLOBAL_BUILTINS | 25,804,147 | 1.2% | 74.5% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 24,679,116 | 1.1% | 75.6% | 0.2% |
| _CHECK_PEP_523 | 24,679,116 | 1.1% | 76.8% |  |
| _CHECK_STACK_SPACE | 24,639,526 | 1.1% | 77.9% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 24,637,133 | 1.1% | 79.0% |  |
| _PUSH_FRAME | 24,637,133 | 1.1% | 80.1% |  |
| _SAVE_RETURN_OFFSET | 24,637,133 | 1.1% | 81.2% |  |
| _ITER_CHECK_TUPLE | 23,764,218 | 1.1% | 82.3% | 4.0% |
| LOAD_CONST | 22,894,646 | 1.0% | 83.3% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 22,805,698 | 1.0% | 84.3% | 38.9% |
| LOAD_DEREF | 18,334,778 | 0.8% | 85.2% |  |
| PUSH_NULL | 17,970,080 | 0.8% | 86.0% |  |
| _GUARD_IS_TRUE_POP | 17,546,926 | 0.8% | 86.7% | 28.1% |
| _GUARD_IS_NOT_NONE_POP | 16,813,818 | 0.8% | 87.5% | 90.1% |
| BUILD_TUPLE | 14,726,934 | 0.7% | 88.2% |  |
| _ITER_NEXT_TUPLE | 13,938,465 | 0.6% | 88.8% |  |
| CALL_ISINSTANCE | 13,429,703 | 0.6% | 89.4% |  |
| TO_BOOL_BOOL | 13,218,216 | 0.6% | 90.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 13,170,943 | 0.6% | 90.6% |  |
| _GUARD_KEYS_VERSION | 13,170,943 | 0.6% | 91.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 13,169,083 | 0.6% | 91.8% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 10,733,020 | 0.5% | 92.3% | 7.7% |
| _ITER_CHECK_RANGE | 10,733,020 | 0.5% | 92.7% |  |
| _ITER_NEXT_RANGE | 9,905,684 | 0.4% | 93.2% |  |
| GET_ITER | 9,386,768 | 0.4% | 93.6% |  |
| _GUARD_BOTH_INT | 9,247,644 | 0.4% | 94.0% |  |
| _BINARY_OP_ADD_INT | 9,220,584 | 0.4% | 94.4% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 9,160,796 | 0.4% | 94.9% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 9,160,796 | 0.4% | 95.3% |  |
| _GUARD_IS_NONE_POP | 8,954,229 | 0.4% | 95.7% | 35.2% |
| MAKE_FUNCTION | 8,899,468 | 0.4% | 96.1% |  |
| BINARY_SUBSCR_LIST_INT | 8,195,365 | 0.4% | 96.4% | 0.2% |
| RESUME_CHECK | 7,819,174 | 0.4% | 96.8% |  |
| SET_FUNCTION_ATTRIBUTE | 7,041,841 | 0.3% | 97.1% |  |
| BUILD_MAP | 6,636,909 | 0.3% | 97.4% |  |
| DICT_MERGE | 6,636,009 | 0.3% | 97.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,465,141 | 0.2% | 98.0% | 97.7% |
| _LOAD_ATTR_METHOD_NO_DICT | 5,239,360 | 0.2% | 98.2% |  |
| _BINARY_SUBSCR | 3,701,499 | 0.2% | 98.4% |  |
| LIST_APPEND | 3,631,190 | 0.2% | 98.5% |  |
| _POP_FRAME | 3,134,505 | 0.1% | 98.7% |  |
| COMPARE_OP_INT | 2,503,789 | 0.1% | 98.8% | 0.0% |
| IS_OP | 2,318,009 | 0.1% | 98.9% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,301,967 | 0.1% | 99.0% |  |
| CALL_BUILTIN_O | 2,210,423 | 0.1% | 99.1% |  |
| SWAP | 2,152,760 | 0.1% | 99.2% |  |
| CALL_TYPE_1 | 1,914,991 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,887,020 | 0.1% | 99.4% |  |
| LOAD_FAST_AND_CLEAR | 1,831,200 | 0.1% | 99.4% |  |
| _COMPARE_OP | 1,684,518 | 0.1% | 99.5% |  |
| POP_TOP | 1,416,438 | 0.1% | 99.6% |  |
| _STORE_SUBSCR | 1,408,987 | 0.1% | 99.6% |  |
| _BINARY_OP | 1,236,169 | 0.1% | 99.7% |  |
| TO_BOOL_INT | 1,192,540 | 0.1% | 99.7% | 0.0% |
| BUILD_LIST | 1,142,420 | 0.1% | 99.8% |  |
| STORE_DEREF | 984,824 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 669,153 | 0.0% | 99.9% |  |
| _LOAD_ATTR_SLOT | 533,771 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST | 430,486 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 297,342 | 0.0% | 99.9% |  |
| COPY | 295,762 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 256,900 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 137,208 | 0.0% | 100.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 112,552 | 0.0% | 100.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 112,552 | 0.0% | 100.0% |  |
| LOAD_NAME | 107,280 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 80,260 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 63,280 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 61,600 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 41,004 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 39,280 | 0.0% | 100.0% |  |
| STORE_NAME | 36,700 | 0.0% | 100.0% |  |
| UNARY_NOT | 33,720 | 0.0% | 100.0% |  |
| _TO_BOOL | 19,040 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,800 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 16,660 | 0.0% | 100.0% |  |
| CALL_LEN | 16,524 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 13,680 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 13,380 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 11,920 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 11,920 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 10,680 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 6,888 | 0.0% | 100.0% |  |
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
| SET_ADD | 960 | 0.0% | 100.0% |  |
| BUILD_STRING | 960 | 0.0% | 100.0% |  |
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
| LOAD_ATTR_PROPERTY | 2,925 |
| YIELD_VALUE | 1,118 |
| CALL | 1,014 |
| FOR_ITER_GEN | 760 |
| CALL_FUNCTION_EX | 640 |
| CALL_PY_WITH_DEFAULTS | 520 |
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
Stats gathered on: 2023-11-16
