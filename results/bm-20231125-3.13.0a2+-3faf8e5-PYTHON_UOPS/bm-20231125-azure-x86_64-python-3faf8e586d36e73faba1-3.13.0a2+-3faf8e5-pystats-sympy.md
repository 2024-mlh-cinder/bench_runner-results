
# Pystats results

- benchmark: sympy
- fork: python
- ref: 3faf8e586d36e73faba13d9b61663afed6a24cb4
- commit hash: 3faf8e5
- commit date: 2023-11-25T15:40:19-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 832,684,472 | 16.8% | 16.8% |  |
| STORE_FAST | 285,696,743 | 5.8% | 22.6% |  |
| POP_JUMP_IF_FALSE | 256,749,662 | 5.2% | 27.8% |  |
| RESUME_CHECK | 249,831,638 | 5.0% | 32.8% |  |
| LOAD_GLOBAL_BUILTIN | 208,024,130 | 4.2% | 37.0% | 0.0% |
| LOAD_FAST_LOAD_FAST | 203,771,398 | 4.1% | 41.1% |  |
| RETURN_VALUE | 177,171,281 | 3.6% | 44.7% |  |
| LOAD_CONST | 171,390,013 | 3.5% | 48.1% |  |
| TO_BOOL_BOOL | 159,403,455 | 3.2% | 51.4% | 0.1% |
| INTERPRETER_EXIT | 127,120,827 | 2.6% | 53.9% |  |
| ENTER_EXECUTOR | 118,464,847 | 2.4% | 56.3% |  |
| LOAD_GLOBAL_MODULE | 110,212,650 | 2.2% | 58.5% | 0.0% |
| LOAD_ATTR_SLOT | 95,503,303 | 1.9% | 60.5% | 38.2% |
| LOAD_ATTR | 91,867,767 | 1.9% | 62.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 86,397,315 | 1.7% | 64.1% | 10.5% |
| POP_JUMP_IF_TRUE | 68,593,915 | 1.4% | 65.5% |  |
| POP_TOP | 59,950,441 | 1.2% | 66.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,533,638 | 1.1% | 67.8% | 27.6% |
| RETURN_CONST | 54,271,506 | 1.1% | 68.9% |  |
| CALL_ISINSTANCE | 54,027,901 | 1.1% | 70.0% |  |
| CALL_PY_EXACT_ARGS | 52,530,621 | 1.1% | 71.1% | 14.9% |
| GET_ITER | 50,664,341 | 1.0% | 72.1% |  |
| LOAD_DEREF | 50,421,665 | 1.0% | 73.1% |  |
| STORE_FAST_STORE_FAST | 49,460,088 | 1.0% | 74.1% |  |
| COMPARE_OP_INT | 48,594,108 | 1.0% | 75.1% | 1.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 46,572,578 | 0.9% | 76.0% |  |
| IS_OP | 45,198,544 | 0.9% | 76.9% |  |
| SWAP | 43,155,121 | 0.9% | 77.8% |  |
| CALL_BUILTIN_FAST | 43,056,789 | 0.9% | 78.7% |  |
| PUSH_NULL | 42,718,113 | 0.9% | 79.5% |  |
| BUILD_TUPLE | 42,239,938 | 0.9% | 80.4% |  |
| CALL_BUILTIN_O | 37,656,198 | 0.8% | 81.1% | 7.1% |
| COMPARE_OP | 36,827,387 | 0.7% | 81.9% |  |
| FOR_ITER | 34,113,880 | 0.7% | 82.6% |  |
| BINARY_OP | 34,088,703 | 0.7% | 83.3% |  |
| POP_JUMP_IF_NONE | 33,750,457 | 0.7% | 83.9% |  |
| COPY_FREE_VARS | 31,641,925 | 0.6% | 84.6% |  |
| NOP | 31,467,898 | 0.6% | 85.2% |  |
| CALL_LEN | 28,081,343 | 0.6% | 85.8% |  |
| CALL_FUNCTION_EX | 28,012,383 | 0.6% | 86.3% |  |
| LOAD_ATTR_PROPERTY | 27,992,167 | 0.6% | 86.9% | 14.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 27,647,384 | 0.6% | 87.5% | 23.4% |
| BUILD_MAP | 27,150,859 | 0.5% | 88.0% |  |
| CALL | 26,835,245 | 0.5% | 88.6% |  |
| CALL_LIST_APPEND | 24,016,022 | 0.5% | 89.0% |  |
| YIELD_VALUE | 22,780,715 | 0.5% | 89.5% |  |
| FOR_ITER_LIST | 22,389,616 | 0.5% | 90.0% | 0.9% |
| BINARY_SUBSCR_LIST_INT | 21,997,728 | 0.4% | 90.4% | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 21,652,045 | 0.4% | 90.8% | 65.3% |
| BUILD_LIST | 20,482,843 | 0.4% | 91.3% |  |
| FOR_ITER_TUPLE | 20,375,761 | 0.4% | 91.7% | 1.2% |
| BINARY_SUBSCR | 20,181,618 | 0.4% | 92.1% |  |
| STORE_SUBSCR_LIST_INT | 20,076,395 | 0.4% | 92.5% |  |
| TO_BOOL_INT | 18,501,906 | 0.4% | 92.8% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,075,232 | 0.4% | 93.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 17,860,155 | 0.4% | 93.6% | 0.8% |
| EXTENDED_ARG | 17,074,292 | 0.3% | 93.9% |  |
| DICT_MERGE | 16,636,176 | 0.3% | 94.3% |  |
| LOAD_FAST_AND_CLEAR | 14,956,952 | 0.3% | 94.6% |  |
| CALL_TYPE_1 | 14,797,358 | 0.3% | 94.9% |  |
| COMPARE_OP_STR | 14,523,718 | 0.3% | 95.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,381,994 | 0.3% | 95.4% | 0.3% |
| RETURN_GENERATOR | 14,338,603 | 0.3% | 95.7% |  |
| TO_BOOL | 12,896,589 | 0.3% | 96.0% |  |
| CONTAINS_OP | 12,577,943 | 0.3% | 96.2% |  |
| CALL_KW | 10,672,733 | 0.2% | 96.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,063,410 | 0.2% | 96.6% | 0.0% |
| STORE_ATTR_SLOT | 9,059,183 | 0.2% | 96.8% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,985,135 | 0.2% | 97.0% | 0.1% |
| IMPORT_FROM | 8,954,021 | 0.2% | 97.2% |  |
| CALL_BUILTIN_CLASS | 8,478,466 | 0.2% | 97.4% |  |
| MAP_ADD | 7,865,844 | 0.2% | 97.5% |  |
| IMPORT_NAME | 7,758,962 | 0.2% | 97.7% |  |
| STORE_DEREF | 7,701,660 | 0.2% | 97.8% |  |
| MAKE_CELL | 6,048,999 | 0.1% | 97.9% |  |
| CALL_TUPLE_1 | 5,849,111 | 0.1% | 98.1% | 0.0% |
| JUMP_FORWARD | 5,743,001 | 0.1% | 98.2% |  |
| MAKE_FUNCTION | 5,384,794 | 0.1% | 98.3% |  |
| UNARY_NOT | 5,273,705 | 0.1% | 98.4% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,693 | 0.1% | 98.5% | 0.1% |
| COPY | 4,612,588 | 0.1% | 98.6% |  |
| CALL_PY_WITH_DEFAULTS | 4,590,707 | 0.1% | 98.7% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,584,371 | 0.1% | 98.8% | 0.2% |
| BINARY_OP_ADD_INT | 3,742,582 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 3,369,147 | 0.1% | 98.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,782 | 0.1% | 99.0% | 0.0% |
| BINARY_SUBSCR_DICT | 3,051,058 | 0.1% | 99.1% |  |
| BINARY_OP_MULTIPLY_INT | 2,757,847 | 0.1% | 99.1% | 0.0% |
| TO_BOOL_NONE | 2,646,988 | 0.1% | 99.2% | 8.6% |
| LIST_APPEND | 2,556,768 | 0.1% | 99.2% |  |
| BINARY_OP_SUBTRACT_INT | 2,472,976 | 0.0% | 99.3% |  |
| TO_BOOL_LIST | 2,285,553 | 0.0% | 99.3% | 0.5% |
| STORE_SUBSCR_DICT | 2,276,490 | 0.0% | 99.4% |  |
| FOR_ITER_RANGE | 2,224,597 | 0.0% | 99.4% |  |
| STORE_SUBSCR | 2,027,791 | 0.0% | 99.4% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,123 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,754,873 | 0.0% | 99.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,646,471 | 0.0% | 99.5% | 20.6% |
| UNPACK_SEQUENCE_TUPLE | 1,591,438 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,572,567 | 0.0% | 99.6% |  |
| LIST_EXTEND | 1,349,013 | 0.0% | 99.6% |  |
| CALL_INTRINSIC_1 | 1,348,973 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,341 | 0.0% | 99.7% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,181,884 | 0.0% | 99.7% |  |
| SEND_GEN | 1,029,820 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,283 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,283 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,283 | 0.0% | 99.8% |  |
| STORE_ATTR | 591,318 | 0.0% | 99.8% |  |
| BINARY_SLICE | 563,936 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 551,660 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,615 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,400 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 532,977 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 503,100 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 369,403 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 99.9% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 227,834 | 0.0% | 100.0% | 36.5% |
| FOR_ITER_GEN | 191,184 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,913 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,560 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,248 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 131,280 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,290 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,062 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 71,540 | 0.0% | 100.0% |  |
| BUILD_SET | 50,325 | 0.0% | 100.0% |  |
| RESUME | 47,577 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,725 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,487 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 159,540,666 | 3.2% | 3.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 140,532,642 | 2.8% | 6.1% |
| RESUME_CHECK LOAD_FAST | 115,536,416 | 2.3% | 8.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 105,967,577 | 2.1% | 10.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 105,137,303 | 2.1% | 12.6% |
| CACHE RESUME_CHECK | 98,901,807 | 2.0% | 14.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,051,447 | 1.9% | 16.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 73,137,531 | 1.5% | 18.0% |
| RETURN_VALUE INTERPRETER_EXIT | 72,894,932 | 1.5% | 19.5% |
| LOAD_FAST LOAD_CONST | 60,354,762 | 1.2% | 20.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,848,537 | 1.2% | 21.9% |
| LOAD_FAST RETURN_VALUE | 52,880,344 | 1.1% | 22.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 51,676,100 | 1.0% | 24.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 51,182,377 | 1.0% | 25.0% |
| LOAD_FAST LOAD_ATTR | 50,957,318 | 1.0% | 26.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 48,116,636 | 1.0% | 27.0% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 47,061,118 | 0.9% | 28.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 43,459,328 | 0.9% | 28.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 42,775,155 | 0.9% | 29.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 42,737,367 | 0.9% | 30.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,044,966 | 0.8% | 31.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,193,893 | 0.8% | 32.3% |
| LOAD_CONST LOAD_CONST | 40,196,711 | 0.8% | 33.1% |
| RETURN_VALUE STORE_FAST | 38,442,998 | 0.8% | 33.8% |
| PUSH_NULL LOAD_FAST | 35,225,043 | 0.7% | 34.6% |
| LOAD_ATTR STORE_FAST | 34,991,705 | 0.7% | 35.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,545,182 | 0.7% | 35.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 33,432,359 | 0.7% | 36.6% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,431,710 | 0.7% | 37.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,130,923 | 0.7% | 38.0% |
| RETURN_CONST INTERPRETER_EXIT | 32,283,297 | 0.7% | 38.6% |
| IS_OP POP_JUMP_IF_FALSE | 29,995,240 | 0.6% | 39.2% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 29,940,144 | 0.6% | 39.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 29,560,718 | 0.6% | 40.4% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 29,351,699 | 0.6% | 41.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 28,959,086 | 0.6% | 41.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,346,758 | 0.6% | 42.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 28,278,217 | 0.6% | 42.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 27,696,556 | 0.6% | 43.3% |
| LOAD_FAST CALL_LEN | 27,052,954 | 0.5% | 43.8% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,062,531 | 0.5% | 44.3% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 24,566,808 | 0.5% | 44.8% |
| BINARY_OP STORE_FAST | 24,134,303 | 0.5% | 45.3% |
| LOAD_CONST CALL_BUILTIN_FAST | 23,928,009 | 0.5% | 45.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 22,641,285 | 0.5% | 46.3% |
| LOAD_ATTR_SLOT STORE_FAST | 22,509,691 | 0.5% | 46.7% |
| POP_TOP ENTER_EXECUTOR | 22,316,661 | 0.5% | 47.2% |
| YIELD_VALUE INTERPRETER_EXIT | 21,934,858 | 0.4% | 47.6% |
| COPY_FREE_VARS RESUME_CHECK | 21,666,419 | 0.4% | 48.1% |
| LOAD_FAST TO_BOOL_BOOL | 21,598,529 | 0.4% | 48.5% |
| RESUME_CHECK NOP | 21,362,637 | 0.4% | 48.9% |
| BUILD_TUPLE RETURN_VALUE | 21,220,500 | 0.4% | 49.3% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,085,749 | 0.4% | 49.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,792,564 | 0.4% | 50.2% |
| LOAD_CONST COMPARE_OP_INT | 20,726,272 | 0.4% | 50.6% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,465,507 | 0.4% | 51.0% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 19,360,754 | 0.4% | 51.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 18,992,244 | 0.4% | 51.8% |
| GET_ITER FOR_ITER | 18,945,288 | 0.4% | 52.2% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,842,001 | 0.4% | 52.5% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,812,493 | 0.4% | 52.9% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 18,550,384 | 0.4% | 53.3% |
| COMPARE_OP POP_JUMP_IF_FALSE | 18,443,631 | 0.4% | 53.7% |
| ENTER_EXECUTOR POP_JUMP_IF_NONE | 18,301,215 | 0.4% | 54.0% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 17,882,399 | 0.4% | 54.4% |
| LOAD_FAST TO_BOOL_INT | 17,625,343 | 0.4% | 54.8% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 17,314,395 | 0.3% | 55.1% |
| LOAD_FAST PUSH_NULL | 17,279,617 | 0.3% | 55.5% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,202,637 | 0.3% | 55.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 17,190,918 | 0.3% | 56.1% |
| DICT_MERGE CALL_FUNCTION_EX | 16,636,176 | 0.3% | 56.5% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,631,876 | 0.3% | 56.8% |
| BUILD_MAP LOAD_FAST | 16,610,938 | 0.3% | 57.2% |
| LOAD_FAST DICT_MERGE | 16,571,238 | 0.3% | 57.5% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,117,556 | 0.3% | 57.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,025,400 | 0.3% | 58.1% |
| LOAD_ATTR LOAD_FAST | 15,959,016 | 0.3% | 58.5% |
| LOAD_FAST CALL_BUILTIN_O | 15,700,309 | 0.3% | 58.8% |
| RESUME_CHECK LOAD_CONST | 15,610,888 | 0.3% | 59.1% |
| LOAD_FAST CALL_LIST_APPEND | 15,553,719 | 0.3% | 59.4% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 15,427,274 | 0.3% | 59.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,184,996 | 0.3% | 60.0% |
| RETURN_VALUE RETURN_VALUE | 15,183,196 | 0.3% | 60.3% |
| POP_JUMP_IF_NONE ENTER_EXECUTOR | 15,174,591 | 0.3% | 60.6% |
| LOAD_ATTR IS_OP | 14,930,302 | 0.3% | 60.9% |
| RESUME_CHECK POP_TOP | 14,812,500 | 0.3% | 61.2% |
| LOAD_FAST CALL_TYPE_1 | 14,728,475 | 0.3% | 61.5% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 14,727,690 | 0.3% | 61.8% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 14,480,514 | 0.3% | 62.1% |
| POP_TOP RESUME_CHECK | 14,333,042 | 0.3% | 62.4% |
| LOAD_FAST GET_ITER | 14,272,748 | 0.3% | 62.7% |
| LOAD_CONST STORE_FAST | 14,263,900 | 0.3% | 63.0% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 13,976,961 | 0.3% | 63.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 13,892,547 | 0.3% | 63.5% |
| CACHE POP_TOP | 13,889,702 | 0.3% | 63.8% |
| CALL_BUILTIN_O STORE_FAST | 13,585,920 | 0.3% | 64.1% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 13,219,190 | 0.3% | 64.4% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 13,126,816 | 0.3% | 64.6% |
| CACHE COPY_FREE_VARS | 12,997,997 | 0.3% | 64.9% |
| CALL_FUNCTION_EX STORE_FAST | 12,600,652 | 0.3% | 65.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 530,576 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,384 | 56.6% |
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
| RESUME_CHECK | 98,901,807 | 77.7% |
| POP_TOP | 13,889,702 | 10.9% |
| COPY_FREE_VARS | 12,997,997 | 10.2% |
| MAKE_CELL | 1,509,112 | 1.2% |
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
| LOAD_FAST_LOAD_FAST | 10,875,947 | 53.9% |
| LOAD_DEREF | 6,403,324 | 31.7% |
| BUILD_TUPLE | 1,809,476 | 9.0% |
| LOAD_FAST | 690,294 | 3.4% |
| RETURN_VALUE | 152,430 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,065,482 | 30.1% |
| POP_JUMP_IF_NONE | 5,357,163 | 26.5% |
| LOAD_FAST | 5,212,195 | 25.8% |
| CALL | 910,313 | 4.5% |
| GET_ITER | 899,951 | 4.5% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,477 | 73.6% |
| BUILD_TUPLE | 157,184 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,282 | 8.7% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,123 | 100.0% |
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
| RETURN_CONST | 22,487 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,487 | 100.0% |


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
| LOAD_FAST | 14,272,748 | 28.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,589,398 | 24.8% |
| CALL | 10,953,402 | 21.6% |
| RETURN_VALUE | 4,116,570 | 8.1% |
| CALL_BUILTIN_O | 2,591,096 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 18,945,288 | 37.4% |
| FOR_ITER_TUPLE | 9,974,753 | 19.7% |
| LOAD_FAST_AND_CLEAR | 8,282,505 | 16.3% |
| CALL_PY_EXACT_ARGS | 6,004,083 | 11.9% |
| FOR_ITER_LIST | 4,313,156 | 8.5% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 347,000 | 64.2% |
| BINARY_SUBSCR | 185,800 | 34.4% |
| RETURN_VALUE | 7,520 | 1.4% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540,400 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,894,932 | 57.3% |
| RETURN_CONST | 32,283,297 | 25.4% |
| YIELD_VALUE | 21,934,858 | 17.3% |
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
| LOAD_CONST | 5,384,794 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 3,367,607 | 62.5% |
| LOAD_GLOBAL_BUILTIN | 793,277 | 14.7% |
| STORE_FAST | 669,669 | 12.4% |
| LOAD_FAST | 458,471 | 8.5% |
| STORE_NAME | 33,580 | 0.6% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,362,637 | 67.9% |
| POP_JUMP_IF_TRUE | 4,183,829 | 13.3% |
| STORE_FAST | 1,973,279 | 6.3% |
| POP_JUMP_IF_FALSE | 1,911,047 | 6.1% |
| POP_TOP | 1,391,618 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,279,285 | 39.0% |
| LOAD_DEREF | 10,423,812 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,377,239 | 20.3% |
| LOAD_FAST_LOAD_FAST | 897,452 | 2.9% |
| LOAD_CONST | 751,138 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,602 | 45.7% |
| POP_TOP | 358,261 | 39.5% |
| STORE_FAST | 130,960 | 14.5% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,602 | 45.7% |
| EXTENDED_ARG | 201,170 | 22.2% |
| ENTER_EXECUTOR | 155,371 | 17.1% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,812,500 | 24.7% |
| CACHE | 13,889,702 | 23.2% |
| RETURN_CONST | 7,993,711 | 13.3% |
| STORE_FAST | 5,838,877 | 9.7% |
| SWAP | 5,747,074 | 9.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 22,316,661 | 37.2% |
| RESUME_CHECK | 14,333,042 | 23.9% |
| LOAD_FAST | 7,246,550 | 12.1% |
| RETURN_VALUE | 5,270,874 | 8.8% |
| LOAD_CONST | 2,640,639 | 4.4% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,530 | 41.3% |
| BINARY_SUBSCR_DICT | 169,965 | 18.8% |
| RAISE_VARARGS | 115,242 | 12.7% |
| ENTER_EXECUTOR | 102,244 | 11.3% |
| LOAD_ATTR | 89,180 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,081 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,762 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,279,617 | 40.5% |
| LOAD_DEREF | 11,774,326 | 27.6% |
| LOAD_ATTR | 8,320,723 | 19.5% |
| CALL_BUILTIN_FAST | 2,128,620 | 5.0% |
| LOAD_SUPER_ATTR_ATTR | 1,181,884 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,225,043 | 82.5% |
| LOAD_FAST_LOAD_FAST | 5,554,134 | 13.0% |
| LOAD_CONST | 1,723,680 | 4.0% |
| LOAD_DEREF | 127,450 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,894,818 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,116,964 | 28.7% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,080 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,199,300 | 71.1% |
| STORE_FAST | 2,660,315 | 18.6% |
| LOAD_FAST | 791,986 | 5.5% |
| GET_YIELD_FROM_ITER | 347,000 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,880,344 | 29.8% |
| LOAD_ATTR_SLOT | 33,431,710 | 18.9% |
| BUILD_TUPLE | 21,220,500 | 12.0% |
| RETURN_VALUE | 15,183,196 | 8.6% |
| CALL_BUILTIN_O | 11,432,615 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,894,932 | 41.1% |
| STORE_FAST | 38,442,998 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,465,507 | 11.0% |
| RETURN_VALUE | 15,183,196 | 8.6% |
| LOAD_FAST | 5,437,755 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,939,136 | 95.6% |
| BINARY_SUBSCR | 56,960 | 2.8% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.9% |
| SWAP | 5,960 | 0.3% |
| STORE_SUBSCR | 3,365 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,926,256 | 95.0% |
| ENTER_EXECUTOR | 70,640 | 3.5% |
| JUMP_FORWARD | 9,840 | 0.5% |
| JUMP_BACKWARD | 9,300 | 0.5% |
| STORE_SUBSCR | 3,365 | 0.2% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.8% |
| LOAD_FAST | 2,198,468 | 17.0% |
| LOAD_GLOBAL_MODULE | 118,970 | 0.9% |
| LOAD_ATTR | 117,982 | 0.9% |
| RETURN_VALUE | 27,303 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,224,858 | 94.8% |
| POP_JUMP_IF_TRUE | 509,769 | 4.0% |
| UNARY_NOT | 84,144 | 0.7% |
| TO_BOOL_BOOL | 41,194 | 0.3% |
| TO_BOOL | 21,383 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,476 | 22.0% |
| LOAD_FAST | 109,310 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,685 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,977 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,842 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,043 | 10.9% |
| CALL_LIST_APPEND | 39,980 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,617 | 65.3% |
| TO_BOOL_BOOL | 1,084,918 | 20.6% |
| TO_BOOL_LIST | 661,860 | 12.6% |
| TO_BOOL | 84,144 | 1.6% |
| TO_BOOL_INT | 166 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,344 | 66.9% |
| STORE_FAST | 882,724 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,910 | 1.6% |
| LOAD_CONST | 34,347 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,752,647 | 34.5% |
| COMPARE_OP_INT | 6,273,260 | 18.4% |
| COMPARE_OP | 6,162,400 | 18.1% |
| CALL_TUPLE_1 | 4,707,312 | 13.8% |
| LOAD_FAST | 1,516,444 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,134,303 | 70.8% |
| RETURN_VALUE | 5,644,628 | 16.6% |
| CALL_BUILTIN_O | 1,095,110 | 3.2% |
| LOAD_FAST | 857,877 | 2.5% |
| TO_BOOL_INT | 722,122 | 2.1% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,290 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,510 | 97.8% |
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
| STORE_FAST | 3,816,397 | 18.6% |
| SWAP | 3,548,373 | 17.3% |
| LOAD_FAST | 2,131,126 | 10.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,531,777 | 56.3% |
| SWAP | 3,548,373 | 17.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,380 | 11.2% |
| LOAD_FAST | 1,374,313 | 6.7% |
| BUILD_LIST | 748,354 | 3.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,163,749 | 44.8% |
| SWAP | 4,716,132 | 17.4% |
| BUILD_TUPLE | 4,366,338 | 16.1% |
| LOAD_CONST | 1,656,760 | 6.1% |
| RESUME_CHECK | 1,285,960 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,610,938 | 61.2% |
| SWAP | 4,716,132 | 17.4% |
| STORE_FAST | 3,331,406 | 12.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 5.8% |
| CALL_FUNCTION_EX | 734,880 | 2.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,245 | 64.1% |
| SWAP | 18,000 | 35.8% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,245 | 64.1% |
| SWAP | 18,000 | 35.8% |
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
| LOAD_FAST_LOAD_FAST | 18,992,244 | 45.0% |
| LOAD_FAST | 10,094,381 | 23.9% |
| LOAD_ATTR_SLOT | 5,042,254 | 11.9% |
| LOAD_ATTR | 3,033,600 | 7.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,220,500 | 50.2% |
| LOAD_GLOBAL_BUILTIN | 4,707,112 | 11.1% |
| BUILD_MAP | 4,366,338 | 10.3% |
| LOAD_CONST | 3,386,795 | 8.0% |
| CALL_LIST_APPEND | 3,214,240 | 7.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,373,328 | 34.9% |
| LOAD_FAST | 7,259,954 | 27.1% |
| BINARY_OP_MULTIPLY_INT | 2,291,865 | 8.5% |
| ENTER_EXECUTOR | 2,269,223 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,921 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,402 | 40.8% |
| STORE_FAST | 5,844,519 | 21.8% |
| RETURN_VALUE | 4,517,219 | 16.8% |
| POP_TOP | 1,133,194 | 4.2% |
| RESUME_CHECK | 1,061,213 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 16,636,176 | 59.4% |
| ENTER_EXECUTOR | 7,551,050 | 27.0% |
| LOAD_FAST | 1,403,513 | 5.0% |
| CALL_INTRINSIC_1 | 1,256,663 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,600,652 | 45.0% |
| RESUME_CHECK | 11,673,376 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,804 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,347,753 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,663 | 93.2% |
| BUILD_MAP | 91,250 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,508,366 | 98.5% |
| ENTER_EXECUTOR | 164,367 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,492,773 | 88.9% |
| POP_TOP | 698,031 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,805 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,085,749 | 57.3% |
| LOAD_FAST | 6,600,227 | 17.9% |
| CALL_TYPE_1 | 5,882,382 | 16.0% |
| LOAD_GLOBAL_MODULE | 1,179,647 | 3.2% |
| LOAD_CONST | 947,624 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,443,631 | 50.1% |
| BINARY_OP | 6,162,400 | 16.7% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.7% |
| UNARY_NOT | 3,442,617 | 9.3% |
| POP_JUMP_IF_TRUE | 2,275,102 | 6.2% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,744,109 | 45.7% |
| LOAD_ATTR | 3,188,616 | 25.4% |
| LOAD_GLOBAL_MODULE | 1,645,920 | 13.1% |
| LOAD_DEREF | 1,478,140 | 11.8% |
| LOAD_CONST | 174,973 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,668,473 | 76.9% |
| POP_JUMP_IF_TRUE | 2,899,310 | 23.1% |
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
| LOAD_FAST | 1,237,522 | 26.8% |
| COPY | 1,069,360 | 23.2% |
| LOAD_FAST_LOAD_FAST | 868,240 | 18.8% |
| CALL_ISINSTANCE | 525,020 | 11.4% |
| LOAD_CONST | 236,739 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,334,395 | 28.9% |
| COPY | 1,069,360 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,063,080 | 23.0% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,539 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 12,997,997 | 41.1% |
| ENTER_EXECUTOR | 7,037,351 | 22.2% |
| LOAD_ATTR_PROPERTY | 5,066,134 | 16.0% |
| CALL_PY_EXACT_ARGS | 4,700,589 | 14.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,194,642 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,666,419 | 68.5% |
| RETURN_GENERATOR | 9,894,818 | 31.3% |
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
| BUILD_LIST | 20 | 16.7% |
| RETURN_CONST | 20 | 16.7% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,571,238 | 99.6% |
| LOAD_DEREF | 64,938 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 16,636,176 | 100.0% |


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
| POP_TOP | 22,316,661 | 18.8% |
| CALL_LIST_APPEND | 17,314,395 | 14.6% |
| POP_JUMP_IF_TRUE | 15,427,274 | 13.0% |
| POP_JUMP_IF_NONE | 15,174,591 | 12.8% |
| POP_JUMP_IF_FALSE | 13,976,961 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 18,301,215 | 15.4% |
| POP_JUMP_IF_FALSE | 11,955,388 | 10.1% |
| RESUME_CHECK | 9,631,358 | 8.1% |
| FOR_ITER_LIST | 9,263,943 | 7.8% |
| FOR_ITER_TUPLE | 8,724,214 | 7.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,063,318 | 29.7% |
| CALL_LIST_APPEND | 4,571,155 | 26.8% |
| GET_ITER | 2,378,102 | 13.9% |
| ENTER_EXECUTOR | 1,742,143 | 10.2% |
| COMPARE_OP_INT | 1,718,047 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,645,042 | 38.9% |
| ENTER_EXECUTOR | 5,766,651 | 33.8% |
| FOR_ITER_LIST | 2,686,849 | 15.7% |
| FOR_ITER_TUPLE | 767,880 | 4.5% |
| FOR_ITER_RANGE | 642,400 | 3.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 18,945,288 | 55.5% |
| LOAD_FAST | 7,625,010 | 22.4% |
| SWAP | 6,724,808 | 19.7% |
| ENTER_EXECUTOR | 684,954 | 2.0% |
| JUMP_BACKWARD | 71,662 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 24,566,808 | 72.0% |
| ENTER_EXECUTOR | 2,590,056 | 7.6% |
| LOAD_FAST | 2,495,069 | 7.3% |
| SWAP | 1,295,618 | 3.8% |
| DELETE_FAST | 1,284,800 | 3.8% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,757,442 | 86.6% |
| STORE_FAST | 982,352 | 11.0% |
| STORE_DEREF | 185,687 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,821,015 | 76.2% |
| STORE_DEREF | 2,092,406 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,758,202 | 100.0% |
| ENTER_EXECUTOR | 740 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,757,442 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 14,930,302 | 33.0% |
| LOAD_FAST | 12,532,813 | 27.7% |
| LOAD_CONST | 10,975,441 | 24.3% |
| LOAD_FAST_LOAD_FAST | 5,893,542 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 539,784 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,995,240 | 66.4% |
| YIELD_VALUE | 12,517,474 | 27.7% |
| POP_JUMP_IF_TRUE | 2,641,645 | 5.8% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 90,254 | 24.4% |
| POP_TOP | 61,007 | 16.5% |
| LIST_APPEND | 52,029 | 14.1% |
| STORE_FAST | 34,416 | 9.3% |
| POP_JUMP_IF_TRUE | 29,944 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 100,463 | 27.2% |
| FOR_ITER_TUPLE | 80,742 | 21.9% |
| FOR_ITER | 71,662 | 19.4% |
| FOR_ITER_LIST | 53,835 | 14.6% |
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
| STORE_FAST | 4,138,025 | 72.1% |
| POP_TOP | 734,248 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,864 | 3.3% |
| LOAD_FAST | 137,410 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,996,247 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,148 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,628 | 5.7% |
| STORE_FAST | 119,010 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,144,582 | 44.8% |
| BUILD_TUPLE | 653,915 | 25.6% |
| RETURN_VALUE | 510,689 | 20.0% |
| LOAD_ATTR_PROPERTY | 64,369 | 2.5% |
| BINARY_SUBSCR | 37,830 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,499,779 | 97.8% |
| JUMP_BACKWARD | 52,029 | 2.0% |
| LOAD_NAME | 4,800 | 0.2% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,346,873 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,347,753 | 99.9% |
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
| LOAD_FAST | 50,957,318 | 55.5% |
| LOAD_GLOBAL_MODULE | 33,545,182 | 36.5% |
| CALL_TYPE_1 | 2,352,229 | 2.6% |
| LOAD_ATTR_SLOT | 2,297,040 | 2.5% |
| LOAD_GLOBAL_BUILTIN | 1,904,908 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 34,991,705 | 38.1% |
| LOAD_FAST | 15,959,016 | 17.4% |
| IS_OP | 14,930,302 | 16.3% |
| PUSH_NULL | 8,320,723 | 9.1% |
| CONTAINS_OP | 3,188,616 | 3.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,354,762 | 35.2% |
| LOAD_CONST | 40,196,711 | 23.5% |
| RESUME_CHECK | 15,610,888 | 9.1% |
| RETURN_CONST | 9,526,680 | 5.6% |
| CALL_LEN | 7,177,859 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,196,711 | 23.5% |
| CALL_BUILTIN_FAST | 23,928,009 | 14.0% |
| COMPARE_OP_INT | 20,726,272 | 12.1% |
| STORE_FAST | 14,263,900 | 8.3% |
| IS_OP | 10,975,441 | 6.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 10,423,812 | 20.7% |
| STORE_FAST_STORE_FAST | 9,226,028 | 18.3% |
| LOAD_ATTR_SLOT | 6,403,324 | 12.7% |
| POP_JUMP_IF_FALSE | 4,643,918 | 9.2% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,034 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 11,774,326 | 23.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,400,052 | 18.6% |
| LOAD_FAST | 9,344,570 | 18.5% |
| BINARY_SUBSCR | 6,403,324 | 12.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 6.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,540,666 | 19.2% |
| LOAD_GLOBAL_BUILTIN | 140,532,642 | 16.9% |
| RESUME_CHECK | 115,536,416 | 13.9% |
| POP_JUMP_IF_FALSE | 105,967,577 | 12.7% |
| PUSH_NULL | 35,225,043 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,051,447 | 11.3% |
| LOAD_ATTR_METHOD_NO_DICT | 73,137,531 | 8.8% |
| LOAD_CONST | 60,354,762 | 7.2% |
| RETURN_VALUE | 52,880,344 | 6.4% |
| LOAD_GLOBAL_MODULE | 51,676,100 | 6.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,282,505 | 55.4% |
| LOAD_FAST_AND_CLEAR | 6,674,367 | 44.6% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 8,282,425 | 55.4% |
| LOAD_FAST_AND_CLEAR | 6,674,367 | 44.6% |
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
| STORE_FAST | 43,459,328 | 21.3% |
| POP_JUMP_IF_FALSE | 28,959,086 | 14.2% |
| LOAD_GLOBAL_BUILTIN | 28,346,758 | 13.9% |
| STORE_FAST_STORE_FAST | 14,727,690 | 7.2% |
| POP_JUMP_IF_NONE | 13,219,190 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 21,085,749 | 10.3% |
| BINARY_SUBSCR_LIST_INT | 19,360,754 | 9.5% |
| BUILD_TUPLE | 18,992,244 | 9.3% |
| STORE_SUBSCR_LIST_INT | 18,842,001 | 9.2% |
| CALL_BUILTIN_FAST | 17,202,637 | 8.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,273 | 19.4% |
| LOAD_FAST | 34,221 | 18.8% |
| STORE_FAST | 26,944 | 14.8% |
| RESUME_CHECK | 10,933 | 6.0% |
| RESUME | 10,788 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,554 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,260 | 22.7% |
| LOAD_FAST | 39,617 | 21.8% |
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
| MAKE_CELL | 2,274,628 | 37.6% |
| CACHE | 1,509,112 | 24.9% |
| CALL_PY_EXACT_ARGS | 768,426 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,409 | 10.8% |
| CALL | 523,684 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,770,811 | 62.3% |
| MAKE_CELL | 2,274,628 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,853,384 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,863,106 | 100.0% |
| JUMP_BACKWARD | 2,398 | 0.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 105,137,303 | 40.9% |
| COMPARE_OP_INT | 33,130,923 | 12.9% |
| IS_OP | 29,995,240 | 11.7% |
| COMPARE_OP | 18,443,631 | 7.2% |
| COMPARE_OP_STR | 14,480,514 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 105,967,577 | 41.3% |
| LOAD_GLOBAL_BUILTIN | 57,848,537 | 22.5% |
| LOAD_FAST_LOAD_FAST | 28,959,086 | 11.3% |
| RETURN_CONST | 27,696,556 | 10.8% |
| ENTER_EXECUTOR | 13,976,961 | 5.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 18,301,215 | 54.2% |
| LOAD_FAST | 8,982,296 | 26.6% |
| BINARY_SUBSCR | 5,357,163 | 15.9% |
| LOAD_DEREF | 1,088,836 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,174,591 | 45.0% |
| LOAD_FAST_LOAD_FAST | 13,219,190 | 39.2% |
| LOAD_FAST | 2,491,937 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 1,437,823 | 4.3% |
| LOAD_CONST | 1,111,408 | 3.3% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,631,876 | 92.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,224,971 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,226,376 | 67.6% |
| LOAD_FAST_LOAD_FAST | 2,014,569 | 11.1% |
| LOAD_GLOBAL_MODULE | 1,878,388 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,130 | 7.7% |
| ENTER_EXECUTOR | 447,375 | 2.5% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 48,116,636 | 70.1% |
| TO_BOOL_INT | 8,150,763 | 11.9% |
| CONTAINS_OP | 2,899,310 | 4.2% |
| IS_OP | 2,641,645 | 3.9% |
| COMPARE_OP | 2,275,102 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,432,359 | 48.7% |
| ENTER_EXECUTOR | 15,427,274 | 22.5% |
| LOAD_GLOBAL_BUILTIN | 5,254,906 | 7.7% |
| NOP | 4,183,829 | 6.1% |
| BUILD_LIST | 4,083,245 | 6.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,902 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,242 | 98.4% |
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
| POP_JUMP_IF_FALSE | 27,696,556 | 51.0% |
| RESUME_CHECK | 10,045,048 | 18.5% |
| FOR_ITER_LIST | 5,671,906 | 10.5% |
| ENTER_EXECUTOR | 4,689,217 | 8.6% |
| STORE_SUBSCR | 1,926,256 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,283,297 | 59.5% |
| LOAD_CONST | 9,526,680 | 17.6% |
| POP_TOP | 7,993,711 | 14.7% |
| TO_BOOL_BOOL | 1,879,957 | 3.5% |
| STORE_FAST | 1,541,066 | 2.8% |


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
| MAKE_FUNCTION | 3,367,607 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,816,445 | 83.6% |
| STORE_FAST | 298,244 | 8.9% |
| STORE_DEREF | 95,653 | 2.8% |
| LOAD_CONST | 52,360 | 1.6% |
| LOAD_GLOBAL_MODULE | 42,960 | 1.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,789 | 82.3% |
| LOAD_FAST | 98,460 | 16.7% |
| STORE_ATTR | 3,908 | 0.7% |
| SWAP | 2,145 | 0.4% |
| LOAD_DEREF | 16 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,627 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,242 | 19.7% |
| LOAD_FAST | 89,973 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,577,880 | 46.5% |
| IMPORT_FROM | 2,092,406 | 27.2% |
| LOAD_ATTR | 1,558,824 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,653 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,840 | 46.5% |
| POP_TOP | 1,906,719 | 24.8% |
| LOAD_DEREF | 1,298,311 | 16.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.3% |
| IMPORT_FROM | 185,687 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,442,998 | 13.5% |
| LOAD_ATTR | 34,991,705 | 12.2% |
| BINARY_OP | 24,134,303 | 8.4% |
| LOAD_ATTR_SLOT | 22,509,691 | 7.9% |
| LOAD_CONST | 14,263,900 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,540,666 | 55.8% |
| LOAD_FAST_LOAD_FAST | 43,459,328 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 29,940,144 | 10.5% |
| LOAD_GLOBAL_MODULE | 11,161,944 | 3.9% |
| STORE_FAST | 9,340,767 | 3.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,330 | 71.8% |
| FOR_ITER_TUPLE | 408,942 | 23.3% |
| FOR_ITER_RANGE | 47,440 | 2.7% |
| FOR_ITER | 38,161 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,178,896 | 67.2% |
| LOAD_ATTR_PROPERTY | 190,856 | 10.9% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 187,388 | 10.7% |
| LOAD_DEREF | 49,680 | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,840 | 2.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 42,775,155 | 86.5% |
| RETURN_VALUE | 3,248,142 | 6.6% |
| UNPACK_SEQUENCE_TUPLE | 1,396,782 | 2.8% |
| STORE_FAST_STORE_FAST | 771,334 | 1.6% |
| BUILD_LIST | 413,120 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 14,727,690 | 29.8% |
| LOAD_FAST | 13,892,547 | 28.1% |
| LOAD_DEREF | 9,226,028 | 18.7% |
| LOAD_GLOBAL_BUILTIN | 8,512,834 | 17.2% |
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
| BINARY_SUBSCR_LIST_INT | 9,392,537 | 21.8% |
| LOAD_FAST_AND_CLEAR | 8,282,425 | 19.2% |
| ENTER_EXECUTOR | 6,307,254 | 14.6% |
| BUILD_MAP | 4,716,132 | 10.9% |
| LOAD_FAST | 4,609,894 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,392,757 | 21.8% |
| STORE_FAST | 7,930,853 | 18.4% |
| FOR_ITER | 6,724,808 | 15.6% |
| POP_TOP | 5,747,074 | 13.3% |
| BUILD_MAP | 4,716,132 | 10.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,462 | 26.3% |
| FOR_ITER | 6,804 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 16.0% |
| LOAD_FAST | 3,964 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,684 | 47.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,431 | 23.7% |
| STORE_FAST | 8,070 | 20.3% |
| UNPACK_SEQUENCE_TUPLE | 1,145 | 2.9% |
| UNPACK_SEQUENCE | 915 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,517,474 | 54.9% |
| ENTER_EXECUTOR | 4,974,503 | 21.8% |
| CALL_ISINSTANCE | 2,232,671 | 9.8% |
| LOAD_FAST | 1,140,806 | 5.0% |
| YIELD_VALUE | 677,480 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 21,934,858 | 96.3% |
| YIELD_VALUE | 677,480 | 3.0% |
| STORE_FAST | 162,737 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,057 | 38.0% |
| CALL | 11,137 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,082 | 12.8% |
| POP_TOP | 3,961 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,700 | 37.2% |
| LOAD_GLOBAL | 10,788 | 22.7% |
| LOAD_CONST | 8,762 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,361 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,594,260 | 69.3% |
| LOAD_FAST_LOAD_FAST | 573,725 | 15.3% |
| BINARY_SUBSCR_DICT | 420,640 | 11.2% |
| CALL_BUILTIN_CLASS | 81,130 | 2.2% |
| LOAD_FAST | 43,682 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,536,237 | 41.0% |
| SWAP | 942,325 | 25.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 540,003 | 14.4% |
| LOAD_CONST | 268,968 | 7.2% |
| LOAD_FAST | 201,449 | 5.4% |


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
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,680 | 60.5% |
| LOAD_ATTR_SLOT | 723,519 | 26.2% |
| LOAD_FAST_LOAD_FAST | 269,766 | 9.8% |
| LOAD_FAST | 94,300 | 3.4% |
| BINARY_OP | 1,466 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,865 | 83.1% |
| LOAD_FAST_LOAD_FAST | 181,168 | 6.6% |
| STORE_FAST | 175,543 | 6.4% |
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
| LOAD_CONST | 1,556,170 | 62.9% |
| LOAD_FAST_LOAD_FAST | 606,848 | 24.5% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,673 | 5.0% |
| BINARY_OP | 2,191 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,080,100 | 43.7% |
| STORE_FAST | 699,565 | 28.3% |
| BINARY_OP | 311,613 | 12.6% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,880 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,421 | 33.9% |
| LOAD_FAST_LOAD_FAST | 810,037 | 26.5% |
| LOAD_CONST | 642,800 | 21.1% |
| CALL_TUPLE_1 | 441,520 | 14.5% |
| RETURN_VALUE | 114,335 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 865,702 | 28.4% |
| RETURN_VALUE | 809,160 | 26.5% |
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
| LOAD_CONST | 14,548 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,244 | 100.0% |
| RETURN_VALUE | 2 | 0.0% |
| LOAD_CONST | 2 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 19,360,754 | 88.0% |
| COPY | 1,063,080 | 4.8% |
| LOAD_CONST | 1,025,957 | 4.7% |
| CALL_BUILTIN_CLASS | 282,358 | 1.3% |
| LOAD_FAST | 204,159 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,400,897 | 42.7% |
| SWAP | 9,392,537 | 42.7% |
| LOAD_CONST | 1,063,540 | 4.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 534,640 | 2.4% |
| RETURN_VALUE | 432,302 | 2.0% |


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
| LOAD_CONST | 8,718,543 | 97.0% |
| LOAD_FAST | 263,311 | 2.9% |
| BINARY_SUBSCR | 2,741 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,288 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 321,864 | 3.6% |
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
| LOAD_FAST | 13,126,816 | 91.3% |
| BINARY_OP_ADD_INT | 540,003 | 3.8% |
| LOAD_FAST_LOAD_FAST | 480,376 | 3.3% |
| LOAD_ATTR | 152,040 | 1.1% |
| RETURN_VALUE | 36,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,524,372 | 87.1% |
| COPY_FREE_VARS | 1,194,642 | 8.3% |
| MAKE_CELL | 654,409 | 4.6% |
| POP_TOP | 7,360 | 0.1% |
| RESUME | 620 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,795,448 | 33.0% |
| CALL_BUILTIN_CLASS | 1,959,108 | 23.1% |
| LOAD_CONST | 710,920 | 8.4% |
| CALL_LEN | 610,845 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 566,492 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,979,408 | 35.1% |
| CALL_BUILTIN_CLASS | 1,959,108 | 23.1% |
| GET_ITER | 1,727,974 | 20.4% |
| CALL | 284,301 | 3.4% |
| BINARY_SUBSCR_LIST_INT | 282,358 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 23,928,009 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,202,637 | 40.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,234 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 40,908 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 17,882,399 | 41.7% |
| STORE_FAST | 10,859,311 | 25.3% |
| TO_BOOL | 10,287,220 | 24.0% |
| PUSH_NULL | 2,128,620 | 5.0% |
| RETURN_VALUE | 1,500,070 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,832 | 94.4% |
| LOAD_FAST | 135,031 | 2.6% |
| BINARY_OP | 119,070 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,112 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 127,931 | 2.5% |
| CALL_BUILTIN_CLASS | 119,070 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,700,309 | 41.7% |
| RETURN_GENERATOR | 10,199,300 | 27.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,615,230 | 14.9% |
| LOAD_ATTR_SLOT | 4,877,290 | 13.0% |
| BINARY_OP | 1,095,110 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,585,920 | 36.1% |
| RETURN_VALUE | 11,432,615 | 30.4% |
| TO_BOOL_BOOL | 9,877,123 | 26.2% |
| GET_ITER | 2,591,096 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 29,351,699 | 54.3% |
| LOAD_GLOBAL_BUILTIN | 17,190,918 | 31.8% |
| LOAD_DEREF | 2,859,533 | 5.3% |
| LOAD_FAST_LOAD_FAST | 2,648,528 | 4.9% |
| LOAD_FAST | 1,614,956 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 51,182,377 | 94.7% |
| YIELD_VALUE | 2,232,671 | 4.1% |
| COPY | 525,020 | 1.0% |
| RETURN_VALUE | 71,521 | 0.1% |
| TO_BOOL | 9,664 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,052,954 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 173,720 | 0.6% |
| RETURN_VALUE | 95,011 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,270,222 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,675,942 | 34.5% |
| LOAD_CONST | 7,177,859 | 25.6% |
| CALL_BUILTIN_CLASS | 610,845 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,553,719 | 64.8% |
| BUILD_TUPLE | 3,214,240 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 963,240 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 17,314,395 | 72.1% |
| EXTENDED_ARG | 4,571,155 | 19.0% |
| LOAD_FAST | 1,681,754 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |
| JUMP_FORWARD | 191,864 | 0.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,879,589 | 45.6% |
| ENTER_EXECUTOR | 4,980,080 | 23.0% |
| LOAD_CONST | 2,332,171 | 10.8% |
| BUILD_LIST | 2,294,380 | 10.6% |
| BUILD_MAP | 1,561,360 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,562,433 | 58.0% |
| STORE_FAST | 3,360,985 | 15.5% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.4% |
| POP_TOP | 908,801 | 4.2% |
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
| LOAD_ATTR_METHOD_NO_DICT | 22,641,285 | 81.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,669 | 17.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,790 | 0.4% |
| LOAD_ATTR | 72,820 | 0.3% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 12,589,398 | 45.5% |
| STORE_FAST | 9,683,274 | 35.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,832 | 17.7% |
| CALL_BUILTIN_CLASS | 169,725 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,790 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.3% |
| LOAD_CONST | 1,226,471 | 26.8% |
| LOAD_FAST | 290,680 | 6.3% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.5% |
| LOAD_CONST | 1,224,471 | 26.7% |
| TO_BOOL_NONE | 42,400 | 0.9% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,792,564 | 39.6% |
| LOAD_FAST | 15,184,996 | 28.9% |
| GET_ITER | 6,004,083 | 11.4% |
| LOAD_FAST_LOAD_FAST | 5,951,975 | 11.3% |
| LOAD_SUPER_ATTR_METHOD | 1,539,398 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 42,737,367 | 81.4% |
| COPY_FREE_VARS | 4,700,589 | 8.9% |
| RETURN_GENERATOR | 4,116,964 | 7.8% |
| MAKE_CELL | 768,426 | 1.5% |
| CALL_PY_EXACT_ARGS | 145,233 | 0.3% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,621,753 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,373,869 | 29.9% |
| ENTER_EXECUTOR | 1,014,484 | 22.1% |
| RETURN_VALUE | 192,590 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,820 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,372,824 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,721 | 1.2% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,112 | 80.5% |
| LOAD_FAST | 1,014,987 | 17.4% |
| STORE_FAST | 105,756 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,136 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,312 | 80.5% |
| BINARY_SUBSCR_DICT | 441,520 | 7.5% |
| STORE_FAST | 353,196 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,728,475 | 99.5% |
| LOAD_CONST | 65,962 | 0.4% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,081 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,501 | 43.4% |
| COMPARE_OP | 5,882,382 | 39.8% |
| LOAD_ATTR | 2,352,229 | 15.9% |
| IS_OP | 64,222 | 0.4% |
| STORE_FAST | 32,971 | 0.2% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,605 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,630 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,015 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,726,272 | 42.7% |
| LOAD_FAST_LOAD_FAST | 16,117,556 | 33.2% |
| CALL_LEN | 10,270,222 | 21.1% |
| LOAD_FAST | 971,241 | 2.0% |
| LOAD_ATTR_SLOT | 225,233 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,130,923 | 68.2% |
| BINARY_OP | 6,273,260 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.8% |
| EXTENDED_ARG | 1,718,047 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,534,520 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 69.1% |
| LOAD_CONST | 4,295,935 | 29.6% |
| LOAD_GLOBAL_MODULE | 192,443 | 1.3% |
| LOAD_FAST | 2,040 | 0.0% |
| LOAD_ATTR | 1,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,480,514 | 99.7% |
| YIELD_VALUE | 40,124 | 0.3% |
| POP_JUMP_IF_TRUE | 2,080 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,463 | 52.5% |
| GET_ITER | 90,621 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,543 | 52.1% |
| POP_TOP | 90,461 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,263,943 | 41.4% |
| LOAD_FAST | 4,844,069 | 21.6% |
| GET_ITER | 4,313,156 | 19.3% |
| EXTENDED_ARG | 2,686,849 | 12.0% |
| SWAP | 1,219,659 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,052,101 | 40.4% |
| RETURN_CONST | 5,671,906 | 25.3% |
| LOAD_FAST | 4,094,143 | 18.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,490,583 | 6.7% |
| STORE_FAST_LOAD_FAST | 1,260,330 | 5.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 827,136 | 37.2% |
| GET_ITER | 668,892 | 30.1% |
| EXTENDED_ARG | 642,400 | 28.9% |
| SWAP | 38,880 | 1.7% |
| LOAD_FAST | 29,360 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,565 | 58.7% |
| RETURN_CONST | 630,065 | 28.3% |
| LOAD_FAST | 195,180 | 8.8% |
| STORE_FAST_LOAD_FAST | 47,440 | 2.1% |
| SWAP | 38,520 | 1.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,974,753 | 49.0% |
| ENTER_EXECUTOR | 8,724,214 | 42.8% |
| EXTENDED_ARG | 767,880 | 3.8% |
| LOAD_FAST | 518,198 | 2.5% |
| SWAP | 299,158 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,208,067 | 50.1% |
| LOAD_FAST | 7,494,515 | 36.8% |
| RETURN_CONST | 788,556 | 3.9% |
| LOAD_GLOBAL_MODULE | 602,508 | 3.0% |
| STORE_FAST_LOAD_FAST | 408,942 | 2.0% |


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
| LOAD_FAST | 5,478,824 | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,436 | 11.7% |
| LOAD_DEREF | 1,057,896 | 11.7% |
| COPY | 956,400 | 10.6% |
| LOAD_GLOBAL_MODULE | 481,374 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,411 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,234 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,224,971 | 13.5% |
| STORE_FAST | 1,075,596 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,436 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,137,531 | 84.7% |
| RETURN_VALUE | 4,635,784 | 5.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.6% |
| LOAD_GLOBAL_MODULE | 1,964,697 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,411 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,560,718 | 34.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 22,641,285 | 26.2% |
| CALL_PY_EXACT_ARGS | 20,792,564 | 24.1% |
| LOAD_CONST | 4,051,044 | 4.7% |
| LOAD_DEREF | 3,319,034 | 3.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 9,400,052 | 52.6% |
| LOAD_ATTR_SLOT | 4,711,212 | 26.4% |
| LOAD_FAST | 3,526,287 | 19.7% |
| LOAD_ATTR | 147,500 | 0.8% |
| STORE_FAST_LOAD_FAST | 45,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,810,100 | 54.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,669 | 26.9% |
| LOAD_FAST_LOAD_FAST | 2,910,568 | 16.3% |
| CALL_PY_EXACT_ARGS | 318,110 | 1.8% |
| LOAD_CONST | 6,352 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260,718 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,680 | 0.2% |
| LOAD_ATTR | 1,403 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,151 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,631 | 6.3% |
| CALL | 57,379 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR_SLOT | 15,920 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,061,118 | 83.2% |
| ENTER_EXECUTOR | 5,159,457 | 9.1% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 212,640 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,044,966 | 74.4% |
| CALL_BUILTIN_O | 5,615,230 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,920,998 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,680 | 3.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 988,675 | 60.0% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.1% |
| LOAD_DEREF | 144,340 | 8.8% |
| ENTER_EXECUTOR | 14,275 | 0.9% |
| LOAD_ATTR | 12,020 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.0% |
| TO_BOOL_STR | 478,200 | 29.0% |
| TO_BOOL_BOOL | 409,460 | 24.9% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,062,531 | 89.5% |
| ENTER_EXECUTOR | 1,561,692 | 5.6% |
| RETURN_VALUE | 642,498 | 2.3% |
| STORE_FAST_LOAD_FAST | 190,856 | 0.7% |
| LOAD_DEREF | 190,728 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,812,493 | 67.2% |
| COPY_FREE_VARS | 5,066,134 | 18.1% |
| GET_ITER | 1,920,038 | 6.9% |
| TO_BOOL_BOOL | 712,134 | 2.5% |
| STORE_FAST | 505,281 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,051,447 | 98.5% |
| ENTER_EXECUTOR | 632,570 | 0.7% |
| LOAD_ATTR_SLOT | 613,590 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,049 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 69,963 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,431,710 | 35.0% |
| STORE_FAST | 22,509,691 | 23.6% |
| LOAD_DEREF | 6,403,324 | 6.7% |
| LOAD_FAST | 5,219,743 | 5.5% |
| LOAD_CONST | 5,209,970 | 5.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,848,537 | 27.8% |
| RESUME_CHECK | 41,193,893 | 19.8% |
| STORE_FAST | 29,940,144 | 14.4% |
| LOAD_FAST | 18,550,384 | 8.9% |
| CALL_LEN | 9,675,942 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,532,642 | 67.6% |
| LOAD_FAST_LOAD_FAST | 28,346,758 | 13.6% |
| CALL_ISINSTANCE | 17,190,918 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 8,864,076 | 4.3% |
| LOAD_DEREF | 3,164,129 | 1.5% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,676,100 | 46.9% |
| RESUME_CHECK | 16,025,400 | 14.5% |
| STORE_FAST | 11,161,944 | 10.1% |
| POP_JUMP_IF_FALSE | 9,672,092 | 8.8% |
| NOP | 6,377,239 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 33,545,182 | 30.4% |
| CALL_ISINSTANCE | 29,351,699 | 26.6% |
| LOAD_FAST | 28,278,217 | 25.7% |
| LOAD_DEREF | 3,256,139 | 3.0% |
| LOAD_FAST_LOAD_FAST | 3,201,244 | 2.9% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,484 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,181,884 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,623 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,398 | 85.1% |
| LOAD_GLOBAL_MODULE | 172,225 | 9.5% |
| LOAD_FAST | 78,580 | 4.3% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 98,901,807 | 39.6% |
| CALL_PY_EXACT_ARGS | 42,737,367 | 17.1% |
| COPY_FREE_VARS | 21,666,419 | 8.7% |
| LOAD_ATTR_PROPERTY | 18,812,493 | 7.5% |
| POP_TOP | 14,333,042 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,536,416 | 46.2% |
| LOAD_GLOBAL_BUILTIN | 41,193,893 | 16.5% |
| NOP | 21,362,637 | 8.6% |
| LOAD_GLOBAL_MODULE | 16,025,400 | 6.4% |
| LOAD_CONST | 15,610,888 | 6.2% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 661,220 | 64.2% |
| LOAD_CONST | 367,980 | 35.7% |
| SEND | 620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 646,240 | 62.8% |
| POP_TOP | 352,920 | 34.3% |
| YIELD_VALUE | 15,060 | 1.5% |
| END_SEND | 15,020 | 1.5% |
| SEND | 580 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,697 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,125 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,671 | 36.0% |
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
| LOAD_FAST_LOAD_FAST | 4,731,898 | 52.2% |
| LOAD_FAST | 4,284,430 | 47.3% |
| STORE_ATTR_SLOT | 41,755 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,672,678 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,255,959 | 24.9% |
| LOAD_CONST | 1,890,491 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,840 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,568,585 | 68.9% |
| LOAD_FAST | 396,638 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,325 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,647,199 | 72.4% |
| EXTENDED_ARG | 226,724 | 10.0% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.1% |
| LOAD_FAST | 164,821 | 7.2% |
| LOAD_GLOBAL_MODULE | 38,945 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,842,001 | 93.9% |
| SWAP | 1,063,080 | 5.3% |
| LOAD_FAST | 98,934 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |
| LOAD_CONST | 20,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,015,277 | 49.9% |
| ENTER_EXECUTOR | 9,989,878 | 49.8% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |
| LOAD_CONST | 19,800 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 224,404 | 98.5% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| ENTER_EXECUTOR | 860 | 0.4% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| TO_BOOL | 390 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 216,425 | 95.0% |
| POP_JUMP_IF_FALSE | 9,933 | 4.4% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 56 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 51,182,377 | 32.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,044,966 | 26.4% |
| LOAD_FAST | 21,598,529 | 13.5% |
| CALL_BUILTIN_FAST | 17,882,399 | 11.2% |
| CALL_BUILTIN_O | 9,877,123 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 105,137,303 | 66.0% |
| POP_JUMP_IF_TRUE | 48,116,636 | 30.2% |
| EXTENDED_ARG | 5,063,318 | 3.2% |
| UNARY_NOT | 1,084,918 | 0.7% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,625,343 | 95.3% |
| BINARY_OP | 722,122 | 3.9% |
| BINARY_SUBSCR_TUPLE_INT | 63,305 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,280 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,859 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,350,509 | 55.9% |
| POP_JUMP_IF_TRUE | 8,150,763 | 44.1% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 166 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,228,166 | 97.5% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,101 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |
| TO_BOOL | 2,146 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 823,247 | 36.0% |
| POP_JUMP_IF_TRUE | 784,486 | 34.3% |
| UNARY_NOT | 661,860 | 29.0% |
| EXTENDED_ARG | 15,720 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,518 | 69.6% |
| RETURN_VALUE | 389,284 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,060 | 11.1% |
| CALL_METHOD_DESCRIPTOR_O | 42,400 | 1.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,910 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,937,883 | 73.2% |
| POP_JUMP_IF_TRUE | 690,026 | 26.1% |
| EXTENDED_ARG | 15,420 | 0.6% |
| TO_BOOL_BOOL | 1,679 | 0.1% |
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
| LOAD_FAST | 884,745 | 55.6% |
| RETURN_VALUE | 660,888 | 41.5% |
| STORE_FAST | 40,240 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,145 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,396,782 | 87.8% |
| STORE_FAST | 154,736 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 24,566,808 | 52.7% |
| RETURN_VALUE | 19,465,507 | 41.8% |
| FOR_ITER_LIST | 1,490,583 | 3.2% |
| BINARY_SUBSCR_LIST_INT | 534,640 | 1.1% |
| FOR_ITER_TUPLE | 311,119 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 42,775,155 | 91.8% |
| STORE_DEREF | 3,577,880 | 7.7% |
| STORE_FAST | 215,303 | 0.5% |
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
|     deferred | 34,031,400 | 78.0% |
|          hit | 9,527,825 | 21.8% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,804 | 11.9% |
| Failure | 50,499 | 88.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,470 | 18.8% |
| multiply different types | 7,164 | 14.2% |
| subtract other | 6,740 | 13.3% |
| and int | 4,124 | 8.2% |
| rshift | 3,807 | 7.5% |
| or | 3,700 | 7.3% |
| power | 2,868 | 5.7% |
| true divide different types | 2,524 | 5.0% |
| multiply other | 2,260 | 4.5% |
| remainder | 2,073 | 4.1% |
| add different types | 1,813 | 3.6% |
| floor divide | 1,276 | 2.5% |
| subtract different types | 1,191 | 2.4% |
| xor | 584 | 1.2% |
| and other | 375 | 0.7% |
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
|     deferred | 20,159,186 | 37.1% |
|          hit | 34,197,507 | 62.9% |
|         miss | 14,922 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,721 | 34.4% |
| Failure | 14,711 | 65.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 11,407 | 77.5% |
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
|     deferred | 26,116,268 | 6.7% |
|        deopt | 22,840 | 0.0% |
|          hit | 330,046,615 | 85.1% |
|         miss | 31,177,594 | 8.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 668,706 | 90.1% |
| Failure | 73,111 | 9.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,850 | 39.5% |
| code complex parameters | 14,051 | 19.2% |
| class no vectorcall | 9,220 | 12.6% |
| cfunc varargs keywords | 6,385 | 8.7% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.4% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,170 | 3.0% |
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
|     deferred | 36,738,072 | 36.6% |
|          hit | 63,084,488 | 62.8% |
|         miss | 576,953 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,488 | 22.9% |
| Failure | 68,827 | 77.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,449 | 26.8% |
| other | 15,218 | 22.1% |
| different types | 12,182 | 17.7% |
| tuple | 10,048 | 14.6% |
| string | 9,960 | 14.5% |
| bool | 1,771 | 2.6% |
| float long | 340 | 0.5% |
| baseobject | 280 | 0.4% |
| set | 279 | 0.4% |
| list | 220 | 0.3% |
| long float | 80 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 34,040,217 | 42.9% |
|          hit | 44,728,717 | 56.4% |
|         miss | 452,441 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,421 | 27.7% |
| Failure | 53,242 | 72.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 34,081 | 64.0% |
| zip | 4,980 | 9.4% |
| set | 4,457 | 8.4% |
| enumerate | 3,564 | 6.7% |
| other | 1,980 | 3.7% |
| itertools | 1,840 | 3.5% |
| dict keys | 1,400 | 2.6% |
| reversed list | 780 | 1.5% |
| dict values | 80 | 0.2% |
| ascii string | 80 | 0.2% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 90,399,326 | 23.3% |
|        deopt | 20 | 0.0% |
|          hit | 230,790,854 | 59.4% |
|         miss | 65,664,546 | 16.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,316,745 | 89.7% |
| Failure | 151,716 | 10.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mutable class | 58,662 | 38.7% |
| metaclass attribute | 53,197 | 35.1% |
| method | 10,379 | 6.8% |
| overridden | 8,670 | 5.7% |
| has managed dict | 8,580 | 5.7% |
| shadowed | 5,300 | 3.5% |
| class method obj | 3,879 | 2.6% |
| builtin class method | 1,320 | 0.9% |
| not managed dict | 749 | 0.5% |
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
|     deferred | 89,939 | 0.0% |
|          hit | 318,216,320 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,974 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 605 | 0.0% |
|          hit | 2,990,007 | 100.0% |

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
|          hit | 999,160 | 67.8% |
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
|     deferred | 540,595 | 4.2% |
|          hit | 10,197,864 | 78.4% |
|         miss | 2,220,101 | 17.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,815 | 92.3% |
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
|     deferred | 2,021,704 | 8.3% |
|          hit | 22,352,885 | 91.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,722 | 44.7% |
| Failure | 3,365 | 55.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 3,365 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,813,692 | 6.5% |
|          hit | 183,128,810 | 93.2% |
|         miss | 440,026 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,938 | 72.3% |
| Failure | 22,959 | 27.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,782 | 47.0% |
| number | 3,521 | 15.3% |
| mapping | 3,300 | 14.4% |
| dict | 2,260 | 9.8% |
| other | 1,631 | 7.1% |
| set | 1,425 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,554 | 0.1% |
|          hit | 48,342,576 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,396 | 93.6% |
| Failure | 775 | 6.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 715 | 92.3% |
| iterator | 60 | 7.7% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 2,681,820,355 | 54.1% |
| Not specialized | 637,832,163 | 12.9% |
| Specialized hits | 1,534,064,780 | 31.0% |
| Specialized misses | 100,597,823 | 2.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 90,399,326 | 35.1% |
| COMPARE_OP | 36,738,072 | 14.3% |
| FOR_ITER | 34,040,217 | 13.2% |
| BINARY_OP | 34,031,400 | 13.2% |
| CALL | 26,116,268 | 10.1% |
| BINARY_SUBSCR | 20,159,186 | 7.8% |
| TO_BOOL | 12,813,692 | 5.0% |
| STORE_SUBSCR | 2,021,704 | 0.8% |
| STORE_ATTR | 540,595 | 0.2% |
| SEND | 439,140 | 0.2% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,442,931 | 36.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,596,342 | 15.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,144,653 | 14.1% |
| LOAD_ATTR_METHOD_NO_DICT | 9,031,327 | 9.0% |
| CALL_PY_EXACT_ARGS | 7,817,461 | 7.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,422 | 6.4% |
| LOAD_ATTR_PROPERTY | 4,105,960 | 4.1% |
| CALL_BUILTIN_O | 2,661,139 | 2.6% |
| STORE_ATTR_SLOT | 2,219,121 | 2.2% |
| COMPARE_OP_INT | 575,353 | 0.6% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,324,415 | 51.5% |
| Calls to Python functions inlined | 120,076,514 | 48.5% |
| Calls via PyEval_EvalFrame (total) | 127,324,415 | 51.5% |
| Calls via PyEval_EvalFrame (vector) | 98,447,135 | 39.8% |
| Calls via PyEval_EvalFrame (generator) | 28,877,280 | 11.7% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,439,835 | 39.8% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,667,780 | 9.6% |
| Calls via PyEval_EvalFrame (function ex) | 11,824,839 | 4.8% |
| Calls via PyEval_EvalFrame (api) | 53,320,655 | 21.6% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,018 | 0.5% |
| Frames pushed | 112,544,684 | 45.5% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,395,397 | 54.3% |
| Frees to freelist | 363,638,300 |  |
| Allocations | 305,578,732 | 45.7% |
| Allocations to 512 bytes | 304,511,002 | 45.5% |
| Allocations to 4 kbytes | 1,043,270 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,251,019 |  |
| New values | 1,057,365 |  |
| Interpreter increfs | 2,685,511,120 | 65.3% |
| Interpreter decrefs | 3,110,416,860 | 66.2% |
| Increfs | 1,429,861,687 | 34.7% |
| Decrefs | 1,585,674,935 | 33.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,701,383 |  |
| Method cache misses | 4,047,301 |  |
| Method cache collisions | 5,676,896 |  |
| Method cache dunder hits | 346,735,933 |  |
| Method cache dunder misses | 1,630,136 |  |


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
| Optimization attempts | 14,032 |  |
| Traces created | 13,272 | 94.6% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 235 | 1.7% |
| Trace too long | 0 | 0.0% |
| Trace too short | 760 | 5.4% |
| Inner loop found | 280 | 2.0% |
| Recursive call | 160 | 1.1% |
| Traces executed | 118,464,847 |  |
| Uops executed | 2,216,087,652 | 18.71 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 2,662 | 20.1% |
| <= 32 | 5,232 | 39.4% |
| <= 64 | 3,700 | 27.9% |
| <= 128 | 1,263 | 9.5% |
| <= 256 | 395 | 3.0% |
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
| <= 8 | 2,642 | 19.9% |
| <= 16 | 4,322 | 32.6% |
| <= 32 | 3,968 | 29.9% |
| <= 64 | 1,965 | 14.8% |
| <= 128 | 315 | 2.4% |
| <= 256 | 60 | 0.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 1,885,151 | 1.6% |
| <= 2 | 28,412,395 | 24.0% |
| <= 4 | 737,676 | 0.6% |
| <= 8 | 23,141,777 | 19.5% |
| <= 16 | 13,522,593 | 11.4% |
| <= 32 | 34,333,688 | 29.0% |
| <= 64 | 12,285,368 | 10.4% |
| <= 128 | 2,765,603 | 2.3% |
| <= 256 | 1,232,694 | 1.0% |
| <= 512 | 133,301 | 0.1% |
| <= 1,024 | 9,975 | 0.0% |
| <= 2,048 | 4,126 | 0.0% |
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
| _SET_IP | 319,684,614 | 14.4% | 14.4% |  |
| _CHECK_VALIDITY | 265,356,916 | 12.0% | 26.4% |  |
| LOAD_FAST | 246,965,368 | 11.1% | 37.5% |  |
| STORE_FAST | 189,027,245 | 8.5% | 46.1% |  |
| _FOR_ITER_TIER_TWO | 70,890,301 | 3.2% | 49.3% | 22.4% |
| _GUARD_GLOBALS_VERSION | 61,841,331 | 2.8% | 52.1% | 0.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 56,987,771 | 2.6% | 54.6% |  |
| _ITER_CHECK_LIST | 50,096,667 | 2.3% | 56.9% | 1.8% |
| _GUARD_NOT_EXHAUSTED_LIST | 49,170,036 | 2.2% | 59.1% | 19.6% |
| _GUARD_IS_FALSE_POP | 42,452,221 | 1.9% | 61.0% | 20.0% |
| _ITER_NEXT_LIST | 39,543,432 | 1.8% | 62.8% |  |
| CONTAINS_OP | 39,528,016 | 1.8% | 64.6% |  |
| _EXIT_TRACE | 38,130,883 | 1.7% | 66.3% |  |
| _JUMP_TO_TOP | 37,515,171 | 1.7% | 68.0% |  |
| _LOAD_GLOBAL_MODULE | 35,527,152 | 1.6% | 69.6% |  |
| _LOAD_ATTR | 29,839,456 | 1.3% | 71.0% |  |
| _GUARD_TYPE_VERSION | 26,773,080 | 1.2% | 72.2% | 21.3% |
| _GUARD_BUILTINS_VERSION | 25,814,204 | 1.2% | 73.3% |  |
| _LOAD_GLOBAL_BUILTINS | 25,814,204 | 1.2% | 74.5% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 24,724,134 | 1.1% | 75.6% | 0.2% |
| _CHECK_PEP_523 | 24,724,134 | 1.1% | 76.7% |  |
| _CHECK_STACK_SPACE | 24,684,545 | 1.1% | 77.8% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 24,682,131 | 1.1% | 79.0% |  |
| _PUSH_FRAME | 24,682,131 | 1.1% | 80.1% |  |
| _SAVE_RETURN_OFFSET | 24,682,131 | 1.1% | 81.2% |  |
| _ITER_CHECK_TUPLE | 23,763,085 | 1.1% | 82.3% | 4.0% |
| LOAD_CONST | 22,970,938 | 1.0% | 83.3% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 22,804,565 | 1.0% | 84.3% | 38.9% |
| _GUARD_IS_TRUE_POP | 18,049,654 | 0.8% | 85.1% | 28.2% |
| LOAD_DEREF | 18,022,063 | 0.8% | 86.0% |  |
| PUSH_NULL | 17,983,406 | 0.8% | 86.8% |  |
| _GUARD_IS_NOT_NONE_POP | 16,865,244 | 0.8% | 87.5% | 89.9% |
| BUILD_TUPLE | 14,730,715 | 0.7% | 88.2% |  |
| _ITER_NEXT_TUPLE | 13,937,866 | 0.6% | 88.8% |  |
| CALL_ISINSTANCE | 13,429,722 | 0.6% | 89.4% |  |
| TO_BOOL_BOOL | 13,303,121 | 0.6% | 90.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 12,847,836 | 0.6% | 90.6% |  |
| _GUARD_KEYS_VERSION | 12,847,836 | 0.6% | 91.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 12,845,976 | 0.6% | 91.8% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 10,729,875 | 0.5% | 92.2% | 7.7% |
| _ITER_CHECK_RANGE | 10,729,875 | 0.5% | 92.7% |  |
| _ITER_NEXT_RANGE | 9,902,739 | 0.4% | 93.2% |  |
| GET_ITER | 9,381,792 | 0.4% | 93.6% |  |
| _GUARD_BOTH_INT | 9,258,179 | 0.4% | 94.0% |  |
| _BINARY_OP_ADD_INT | 9,231,119 | 0.4% | 94.4% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 9,157,870 | 0.4% | 94.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 9,157,870 | 0.4% | 95.3% |  |
| _GUARD_IS_NONE_POP | 8,960,356 | 0.4% | 95.7% | 35.1% |
| MAKE_FUNCTION | 8,909,047 | 0.4% | 96.1% |  |
| BINARY_SUBSCR_LIST_INT | 8,195,353 | 0.4% | 96.4% | 0.2% |
| RESUME_CHECK | 7,865,242 | 0.4% | 96.8% |  |
| SET_FUNCTION_ATTRIBUTE | 7,050,584 | 0.3% | 97.1% |  |
| BUILD_MAP | 6,645,687 | 0.3% | 97.4% |  |
| DICT_MERGE | 6,636,010 | 0.3% | 97.7% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 5,278,900 | 0.2% | 97.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,106,400 | 0.2% | 98.2% | 97.5% |
| _BINARY_SUBSCR | 3,791,550 | 0.2% | 98.4% |  |
| LIST_APPEND | 3,631,183 | 0.2% | 98.5% |  |
| _POP_FRAME | 3,173,203 | 0.1% | 98.7% |  |
| COMPARE_OP_INT | 2,514,676 | 0.1% | 98.8% | 0.0% |
| IS_OP | 2,317,997 | 0.1% | 98.9% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,301,961 | 0.1% | 99.0% |  |
| CALL_BUILTIN_O | 2,214,665 | 0.1% | 99.1% |  |
| SWAP | 2,152,760 | 0.1% | 99.2% |  |
| CALL_TYPE_1 | 1,914,994 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,887,020 | 0.1% | 99.3% |  |
| LOAD_FAST_AND_CLEAR | 1,831,200 | 0.1% | 99.4% |  |
| _COMPARE_OP | 1,732,061 | 0.1% | 99.5% |  |
| POP_TOP | 1,415,169 | 0.1% | 99.6% |  |
| _STORE_SUBSCR | 1,400,142 | 0.1% | 99.6% |  |
| _BINARY_OP | 1,236,167 | 0.1% | 99.7% |  |
| TO_BOOL_INT | 1,192,540 | 0.1% | 99.7% | 0.0% |
| BUILD_LIST | 1,142,420 | 0.1% | 99.8% |  |
| STORE_DEREF | 993,568 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 669,138 | 0.0% | 99.9% |  |
| _LOAD_ATTR_SLOT | 533,774 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST | 439,130 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 297,322 | 0.0% | 99.9% |  |
| COPY | 295,645 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 256,900 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 147,876 | 0.0% | 100.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 112,571 | 0.0% | 100.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 112,571 | 0.0% | 100.0% |  |
| LOAD_NAME | 107,280 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 80,247 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 63,280 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 61,600 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 40,964 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 39,280 | 0.0% | 100.0% |  |
| STORE_NAME | 36,700 | 0.0% | 100.0% |  |
| UNARY_NOT | 33,707 | 0.0% | 100.0% |  |
| _TO_BOOL | 27,816 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,800 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 16,660 | 0.0% | 100.0% |  |
| CALL_LEN | 16,290 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 13,680 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 13,380 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 11,920 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 11,920 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 10,680 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 6,866 | 0.0% | 100.0% |  |
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
| LOAD_ATTR_PROPERTY | 2,983 |
| YIELD_VALUE | 1,118 |
| CALL | 1,033 |
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
Stats gathered on: 2023-11-26
