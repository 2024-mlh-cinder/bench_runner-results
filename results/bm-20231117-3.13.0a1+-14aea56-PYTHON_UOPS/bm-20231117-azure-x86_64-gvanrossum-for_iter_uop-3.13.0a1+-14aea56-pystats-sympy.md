
# Pystats results

- benchmark: sympy
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 14aea56
- commit date: 2023-11-17T15:11:51-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 833,206,999 | 16.8% | 16.8% |  |
| STORE_FAST | 285,715,260 | 5.8% | 22.6% |  |
| POP_JUMP_IF_FALSE | 257,103,146 | 5.2% | 27.8% |  |
| RESUME_CHECK | 250,124,603 | 5.0% | 32.8% |  |
| LOAD_GLOBAL_BUILTIN | 208,023,693 | 4.2% | 37.0% | 0.0% |
| LOAD_FAST_LOAD_FAST | 204,066,773 | 4.1% | 41.1% |  |
| RETURN_VALUE | 177,175,868 | 3.6% | 44.7% |  |
| LOAD_CONST | 171,388,033 | 3.5% | 48.1% |  |
| TO_BOOL_BOOL | 159,410,429 | 3.2% | 51.3% | 0.1% |
| INTERPRETER_EXIT | 127,376,928 | 2.6% | 53.9% |  |
| ENTER_EXECUTOR | 118,906,797 | 2.4% | 56.3% |  |
| LOAD_GLOBAL_MODULE | 110,211,186 | 2.2% | 58.5% | 0.0% |
| LOAD_ATTR_SLOT | 95,503,798 | 1.9% | 60.5% | 38.2% |
| LOAD_ATTR | 91,872,008 | 1.9% | 62.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 86,413,658 | 1.7% | 64.1% | 10.5% |
| POP_JUMP_IF_TRUE | 68,490,102 | 1.4% | 65.4% |  |
| POP_TOP | 60,364,368 | 1.2% | 66.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 56,533,825 | 1.1% | 67.8% | 27.6% |
| RETURN_CONST | 54,421,569 | 1.1% | 68.9% |  |
| CALL_ISINSTANCE | 54,027,263 | 1.1% | 70.0% |  |
| CALL_PY_EXACT_ARGS | 52,550,898 | 1.1% | 71.0% | 14.9% |
| GET_ITER | 50,686,451 | 1.0% | 72.1% |  |
| LOAD_DEREF | 50,458,520 | 1.0% | 73.1% |  |
| STORE_FAST_STORE_FAST | 49,494,184 | 1.0% | 74.1% |  |
| COMPARE_OP_INT | 48,597,237 | 1.0% | 75.1% | 1.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 46,606,847 | 0.9% | 76.0% |  |
| IS_OP | 45,454,572 | 0.9% | 76.9% |  |
| SWAP | 43,160,041 | 0.9% | 77.8% |  |
| CALL_BUILTIN_FAST | 43,056,450 | 0.9% | 78.7% |  |
| PUSH_NULL | 42,725,666 | 0.9% | 79.5% |  |
| BUILD_TUPLE | 42,274,204 | 0.9% | 80.4% |  |
| CALL_BUILTIN_O | 37,665,490 | 0.8% | 81.1% | 7.1% |
| COMPARE_OP | 36,967,091 | 0.7% | 81.9% |  |
| FOR_ITER | 34,202,572 | 0.7% | 82.6% |  |
| BINARY_OP | 34,088,397 | 0.7% | 83.3% |  |
| POP_JUMP_IF_NONE | 33,888,140 | 0.7% | 83.9% |  |
| COPY_FREE_VARS | 31,648,090 | 0.6% | 84.6% |  |
| NOP | 31,468,586 | 0.6% | 85.2% |  |
| CALL_LEN | 28,081,824 | 0.6% | 85.8% |  |
| CALL_FUNCTION_EX | 28,012,149 | 0.6% | 86.3% |  |
| LOAD_ATTR_PROPERTY | 27,992,274 | 0.6% | 86.9% | 14.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 27,652,270 | 0.6% | 87.5% | 23.4% |
| BUILD_MAP | 27,150,836 | 0.5% | 88.0% |  |
| CALL | 26,857,743 | 0.5% | 88.6% |  |
| CALL_LIST_APPEND | 24,014,885 | 0.5% | 89.0% |  |
| YIELD_VALUE | 23,036,909 | 0.5% | 89.5% |  |
| FOR_ITER_LIST | 22,358,499 | 0.5% | 90.0% | 0.8% |
| BINARY_SUBSCR_LIST_INT | 22,006,850 | 0.4% | 90.4% | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 21,912,708 | 0.4% | 90.8% | 65.7% |
| BINARY_SUBSCR | 20,492,351 | 0.4% | 91.3% |  |
| BUILD_LIST | 20,482,226 | 0.4% | 91.7% |  |
| FOR_ITER_TUPLE | 20,338,886 | 0.4% | 92.1% | 1.1% |
| STORE_SUBSCR_LIST_INT | 20,085,623 | 0.4% | 92.5% |  |
| TO_BOOL_INT | 18,501,304 | 0.4% | 92.9% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,097,033 | 0.4% | 93.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 17,894,332 | 0.4% | 93.6% | 0.8% |
| EXTENDED_ARG | 17,074,091 | 0.3% | 93.9% |  |
| DICT_MERGE | 16,636,008 | 0.3% | 94.3% |  |
| LOAD_FAST_AND_CLEAR | 14,957,160 | 0.3% | 94.6% |  |
| CALL_TYPE_1 | 14,797,492 | 0.3% | 94.9% |  |
| COMPARE_OP_STR | 14,523,411 | 0.3% | 95.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,382,903 | 0.3% | 95.4% | 0.3% |
| RETURN_GENERATOR | 14,342,347 | 0.3% | 95.7% |  |
| TO_BOOL | 12,896,621 | 0.3% | 96.0% |  |
| CONTAINS_OP | 12,494,648 | 0.3% | 96.2% |  |
| CALL_KW | 10,672,779 | 0.2% | 96.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,063,486 | 0.2% | 96.6% | 0.0% |
| STORE_ATTR_SLOT | 9,058,793 | 0.2% | 96.8% | 24.5% |
| BINARY_SUBSCR_TUPLE_INT | 8,985,314 | 0.2% | 97.0% | 0.1% |
| IMPORT_FROM | 8,953,492 | 0.2% | 97.2% |  |
| CALL_BUILTIN_CLASS | 8,478,843 | 0.2% | 97.4% |  |
| MAP_ADD | 7,866,040 | 0.2% | 97.5% |  |
| IMPORT_NAME | 7,758,527 | 0.2% | 97.7% |  |
| STORE_DEREF | 7,701,716 | 0.2% | 97.8% |  |
| MAKE_CELL | 6,048,918 | 0.1% | 98.0% |  |
| CALL_TUPLE_1 | 5,849,200 | 0.1% | 98.1% | 0.0% |
| JUMP_FORWARD | 5,742,844 | 0.1% | 98.2% |  |
| MAKE_FUNCTION | 5,384,857 | 0.1% | 98.3% |  |
| UNARY_NOT | 5,273,678 | 0.1% | 98.4% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,795 | 0.1% | 98.5% | 0.1% |
| COPY | 4,612,655 | 0.1% | 98.6% |  |
| CALL_PY_WITH_DEFAULTS | 4,590,474 | 0.1% | 98.7% | 0.5% |
| CALL_METHOD_DESCRIPTOR_O | 4,584,321 | 0.1% | 98.8% | 0.2% |
| BINARY_OP_ADD_INT | 3,742,648 | 0.1% | 98.9% |  |
| SET_FUNCTION_ATTRIBUTE | 3,369,221 | 0.1% | 98.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,832 | 0.1% | 99.0% | 0.0% |
| BINARY_SUBSCR_DICT | 3,051,156 | 0.1% | 99.1% |  |
| BINARY_OP_MULTIPLY_INT | 2,757,767 | 0.1% | 99.1% | 0.0% |
| TO_BOOL_NONE | 2,647,480 | 0.1% | 99.2% | 8.6% |
| LIST_APPEND | 2,556,750 | 0.1% | 99.2% |  |
| BINARY_OP_SUBTRACT_INT | 2,472,835 | 0.0% | 99.3% |  |
| TO_BOOL_LIST | 2,285,084 | 0.0% | 99.3% | 0.5% |
| STORE_SUBSCR_DICT | 2,276,504 | 0.0% | 99.4% |  |
| FOR_ITER_RANGE | 2,225,124 | 0.0% | 99.4% |  |
| STORE_SUBSCR | 2,040,668 | 0.0% | 99.4% |  |
| LOAD_SUPER_ATTR_METHOD | 1,808,130 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 1,754,971 | 0.0% | 99.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,648,795 | 0.0% | 99.5% | 20.7% |
| UNPACK_SEQUENCE_TUPLE | 1,591,231 | 0.0% | 99.6% |  |
| LOAD_FAST_CHECK | 1,572,560 | 0.0% | 99.6% |  |
| LIST_EXTEND | 1,348,930 | 0.0% | 99.6% |  |
| CALL_INTRINSIC_1 | 1,348,890 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,271,168 | 0.0% | 99.7% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,181,891 | 0.0% | 99.7% |  |
| SEND_GEN | 1,029,884 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,224 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,224 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,224 | 0.0% | 99.8% |  |
| STORE_ATTR | 591,274 | 0.0% | 99.8% |  |
| BINARY_SLICE | 563,985 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 551,660 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,669 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,464 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 532,959 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 503,100 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 369,498 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 282,600 | 0.0% | 99.9% |  |
| CONVERT_VALUE | 282,560 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 227,603 | 0.0% | 100.0% | 36.4% |
| FOR_ITER_GEN | 191,262 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 181,861 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 178,560 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,238 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 140,940 | 0.0% | 100.0% |  |
| STORE_NAME | 131,280 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,265 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,038 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,760 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| LOAD_NAME | 71,540 | 0.0% | 100.0% |  |
| BUILD_SET | 50,256 | 0.0% | 100.0% |  |
| RESUME | 47,563 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,644 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,486 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 159,549,491 | 3.2% | 3.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 140,532,300 | 2.8% | 6.1% |
| RESUME_CHECK LOAD_FAST | 115,545,332 | 2.3% | 8.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 106,013,744 | 2.1% | 10.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 105,140,695 | 2.1% | 12.6% |
| CACHE RESUME_CHECK | 99,153,236 | 2.0% | 14.6% |
| LOAD_FAST LOAD_ATTR_SLOT | 94,051,830 | 1.9% | 16.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 73,153,932 | 1.5% | 18.0% |
| RETURN_VALUE INTERPRETER_EXIT | 72,896,092 | 1.5% | 19.5% |
| LOAD_FAST LOAD_CONST | 60,353,997 | 1.2% | 20.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 57,848,131 | 1.2% | 21.9% |
| LOAD_FAST RETURN_VALUE | 52,902,813 | 1.1% | 22.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 51,675,366 | 1.0% | 24.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 51,181,805 | 1.0% | 25.0% |
| LOAD_FAST LOAD_ATTR | 50,962,127 | 1.0% | 26.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 48,120,231 | 1.0% | 27.0% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 47,060,819 | 0.9% | 28.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 43,469,821 | 0.9% | 28.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 42,809,460 | 0.9% | 29.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 42,763,323 | 0.9% | 30.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 42,045,190 | 0.8% | 31.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,193,751 | 0.8% | 32.2% |
| LOAD_CONST LOAD_CONST | 40,195,921 | 0.8% | 33.0% |
| RETURN_VALUE STORE_FAST | 38,446,158 | 0.8% | 33.8% |
| PUSH_NULL LOAD_FAST | 35,230,654 | 0.7% | 34.5% |
| LOAD_ATTR STORE_FAST | 34,996,589 | 0.7% | 35.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 33,544,840 | 0.7% | 35.9% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,431,955 | 0.7% | 36.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 33,430,759 | 0.7% | 37.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 33,134,101 | 0.7% | 37.9% |
| RETURN_CONST INTERPRETER_EXIT | 32,282,187 | 0.7% | 38.6% |
| IS_OP POP_JUMP_IF_FALSE | 29,995,287 | 0.6% | 39.2% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 29,940,051 | 0.6% | 39.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 29,559,368 | 0.6% | 40.4% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 29,351,566 | 0.6% | 41.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 28,995,114 | 0.6% | 41.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,346,595 | 0.6% | 42.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 28,277,836 | 0.6% | 42.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 27,834,461 | 0.6% | 43.3% |
| LOAD_FAST CALL_LEN | 27,053,408 | 0.5% | 43.8% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 25,062,832 | 0.5% | 44.3% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 24,651,989 | 0.5% | 44.8% |
| BINARY_OP STORE_FAST | 24,134,294 | 0.5% | 45.3% |
| LOAD_CONST CALL_BUILTIN_FAST | 23,927,829 | 0.5% | 45.8% |
| POP_TOP ENTER_EXECUTOR | 22,726,498 | 0.5% | 46.2% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 22,646,031 | 0.5% | 46.7% |
| LOAD_ATTR_SLOT STORE_FAST | 22,509,932 | 0.5% | 47.2% |
| YIELD_VALUE INTERPRETER_EXIT | 22,190,909 | 0.4% | 47.6% |
| COPY_FREE_VARS RESUME_CHECK | 21,668,896 | 0.4% | 48.0% |
| LOAD_FAST TO_BOOL_BOOL | 21,598,325 | 0.4% | 48.5% |
| RESUME_CHECK NOP | 21,363,228 | 0.4% | 48.9% |
| BUILD_TUPLE RETURN_VALUE | 21,220,405 | 0.4% | 49.3% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,085,818 | 0.4% | 49.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 20,793,710 | 0.4% | 50.2% |
| LOAD_CONST COMPARE_OP_INT | 20,723,788 | 0.4% | 50.6% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,465,570 | 0.4% | 51.0% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 19,369,931 | 0.4% | 51.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 18,992,073 | 0.4% | 51.8% |
| GET_ITER FOR_ITER | 18,973,894 | 0.4% | 52.1% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,851,234 | 0.4% | 52.5% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,812,351 | 0.4% | 52.9% |
| COMPARE_OP POP_JUMP_IF_FALSE | 18,583,351 | 0.4% | 53.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 18,549,821 | 0.4% | 53.7% |
| ENTER_EXECUTOR POP_JUMP_IF_NONE | 18,301,271 | 0.4% | 54.0% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 17,882,307 | 0.4% | 54.4% |
| LOAD_FAST TO_BOOL_INT | 17,624,932 | 0.4% | 54.7% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 17,313,247 | 0.3% | 55.1% |
| LOAD_FAST PUSH_NULL | 17,285,498 | 0.3% | 55.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,202,484 | 0.3% | 55.8% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 17,190,463 | 0.3% | 56.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,653,745 | 0.3% | 56.5% |
| DICT_MERGE CALL_FUNCTION_EX | 16,636,008 | 0.3% | 56.8% |
| BUILD_MAP LOAD_FAST | 16,610,792 | 0.3% | 57.1% |
| LOAD_FAST DICT_MERGE | 16,571,078 | 0.3% | 57.5% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 16,123,136 | 0.3% | 57.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 16,025,349 | 0.3% | 58.1% |
| LOAD_ATTR LOAD_FAST | 15,958,742 | 0.3% | 58.4% |
| LOAD_FAST CALL_BUILTIN_O | 15,705,898 | 0.3% | 58.8% |
| RESUME_CHECK LOAD_CONST | 15,610,781 | 0.3% | 59.1% |
| LOAD_FAST CALL_LIST_APPEND | 15,552,601 | 0.3% | 59.4% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 15,325,034 | 0.3% | 59.7% |
| RETURN_VALUE RETURN_VALUE | 15,182,987 | 0.3% | 60.0% |
| POP_JUMP_IF_NONE ENTER_EXECUTOR | 15,174,616 | 0.3% | 60.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,173,826 | 0.3% | 60.6% |
| RESUME_CHECK POP_TOP | 15,063,643 | 0.3% | 60.9% |
| LOAD_ATTR IS_OP | 14,930,350 | 0.3% | 61.2% |
| LOAD_FAST CALL_TYPE_1 | 14,728,632 | 0.3% | 61.5% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 14,727,760 | 0.3% | 61.8% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 14,480,255 | 0.3% | 62.1% |
| POP_TOP RESUME_CHECK | 14,336,786 | 0.3% | 62.4% |
| LOAD_FAST GET_ITER | 14,272,306 | 0.3% | 62.7% |
| LOAD_CONST STORE_FAST | 14,263,941 | 0.3% | 63.0% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 14,111,217 | 0.3% | 63.3% |
| CACHE POP_TOP | 13,893,344 | 0.3% | 63.5% |
| STORE_FAST_STORE_FAST LOAD_FAST | 13,892,605 | 0.3% | 63.8% |
| CALL_BUILTIN_O STORE_FAST | 13,591,494 | 0.3% | 64.1% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 13,357,073 | 0.3% | 64.4% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 13,127,528 | 0.3% | 64.6% |
| CACHE COPY_FREE_VARS | 12,998,972 | 0.3% | 64.9% |
| CALL_METHOD_DESCRIPTOR_FAST LOAD_FAST | 12,818,385 | 0.3% | 65.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 530,625 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,417 | 56.6% |
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
| RESUME_CHECK | 99,153,236 | 77.7% |
| POP_TOP | 13,893,344 | 10.9% |
| COPY_FREE_VARS | 12,998,972 | 10.2% |
| MAKE_CELL | 1,509,166 | 1.2% |
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
| LOAD_FAST_LOAD_FAST | 11,151,371 | 54.4% |
| LOAD_DEREF | 6,403,832 | 31.2% |
| BUILD_TUPLE | 1,843,961 | 9.0% |
| LOAD_FAST | 690,556 | 3.4% |
| RETURN_VALUE | 152,430 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,065,935 | 29.6% |
| POP_JUMP_IF_NONE | 5,494,851 | 26.8% |
| LOAD_FAST | 5,349,910 | 26.1% |
| CALL | 922,745 | 4.5% |
| GET_ITER | 922,002 | 4.5% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,490 | 73.7% |
| BUILD_TUPLE | 157,136 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,258 | 8.7% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,064 | 100.0% |
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
| LOAD_FAST | 14,272,306 | 28.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 12,589,539 | 24.8% |
| CALL | 10,953,537 | 21.6% |
| RETURN_VALUE | 4,116,602 | 8.1% |
| CALL_BUILTIN_O | 2,591,112 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 18,973,894 | 37.4% |
| FOR_ITER_TUPLE | 9,970,494 | 19.7% |
| LOAD_FAST_AND_CLEAR | 8,282,594 | 16.3% |
| CALL_PY_EXACT_ARGS | 6,004,085 | 11.8% |
| FOR_ITER_LIST | 4,310,553 | 8.5% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 347,064 | 64.2% |
| BINARY_SUBSCR | 185,800 | 34.4% |
| RETURN_VALUE | 7,520 | 1.4% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540,464 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,896,092 | 57.2% |
| RETURN_CONST | 32,282,187 | 25.3% |
| YIELD_VALUE | 22,190,909 | 17.4% |
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
| LOAD_CONST | 5,384,857 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 3,367,681 | 62.5% |
| LOAD_GLOBAL_BUILTIN | 793,275 | 14.7% |
| STORE_FAST | 669,682 | 12.4% |
| LOAD_FAST | 458,483 | 8.5% |
| STORE_NAME | 33,580 | 0.6% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,363,228 | 67.9% |
| POP_JUMP_IF_TRUE | 4,184,029 | 13.3% |
| STORE_FAST | 1,973,199 | 6.3% |
| POP_JUMP_IF_FALSE | 1,910,952 | 6.1% |
| POP_TOP | 1,391,714 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,279,922 | 39.0% |
| LOAD_DEREF | 10,423,717 | 33.1% |
| LOAD_GLOBAL_MODULE | 6,377,167 | 20.3% |
| LOAD_FAST_LOAD_FAST | 897,681 | 2.9% |
| LOAD_CONST | 751,146 | 2.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,657 | 45.8% |
| POP_TOP | 358,147 | 39.5% |
| STORE_FAST | 130,960 | 14.5% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,657 | 45.8% |
| EXTENDED_ARG | 201,050 | 22.2% |
| ENTER_EXECUTOR | 155,377 | 17.1% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,063,643 | 25.0% |
| CACHE | 13,893,344 | 23.0% |
| RETURN_CONST | 8,140,710 | 13.5% |
| STORE_FAST | 5,838,462 | 9.7% |
| SWAP | 5,747,061 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 22,726,498 | 37.6% |
| RESUME_CHECK | 14,336,786 | 23.8% |
| LOAD_FAST | 7,247,066 | 12.0% |
| RETURN_VALUE | 5,270,861 | 8.7% |
| LOAD_CONST | 2,640,431 | 4.4% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,586 | 41.3% |
| BINARY_SUBSCR_DICT | 169,946 | 18.8% |
| RAISE_VARARGS | 115,218 | 12.7% |
| ENTER_EXECUTOR | 102,196 | 11.3% |
| LOAD_ATTR | 89,180 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,046 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,738 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,285,498 | 40.5% |
| LOAD_DEREF | 11,776,240 | 27.6% |
| LOAD_ATTR | 8,320,624 | 19.5% |
| CALL_BUILTIN_FAST | 2,128,620 | 5.0% |
| LOAD_SUPER_ATTR_ATTR | 1,181,891 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,230,654 | 82.5% |
| LOAD_FAST_LOAD_FAST | 5,556,013 | 13.0% |
| LOAD_CONST | 1,723,680 | 4.0% |
| LOAD_DEREF | 127,450 | 0.3% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,898,508 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,117,018 | 28.7% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| ENTER_EXECUTOR | 144,080 | 1.0% |
| CALL_KW | 8,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,202,962 | 71.1% |
| STORE_FAST | 2,660,275 | 18.5% |
| LOAD_FAST | 792,006 | 5.5% |
| GET_YIELD_FROM_ITER | 347,064 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,902,813 | 29.9% |
| LOAD_ATTR_SLOT | 33,431,955 | 18.9% |
| BUILD_TUPLE | 21,220,405 | 12.0% |
| RETURN_VALUE | 15,182,987 | 8.6% |
| CALL_BUILTIN_O | 11,432,749 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,896,092 | 41.1% |
| STORE_FAST | 38,446,158 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,465,570 | 11.0% |
| RETURN_VALUE | 15,182,987 | 8.6% |
| LOAD_FAST | 5,437,813 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,952,003 | 95.7% |
| BINARY_SUBSCR | 56,960 | 2.8% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.9% |
| SWAP | 5,960 | 0.3% |
| STORE_SUBSCR | 3,375 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,939,123 | 95.0% |
| ENTER_EXECUTOR | 70,640 | 3.5% |
| JUMP_FORWARD | 9,840 | 0.5% |
| JUMP_BACKWARD | 9,300 | 0.5% |
| STORE_SUBSCR | 3,375 | 0.2% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.8% |
| LOAD_FAST | 2,198,568 | 17.0% |
| LOAD_GLOBAL_MODULE | 118,945 | 0.9% |
| LOAD_ATTR | 117,984 | 0.9% |
| RETURN_VALUE | 27,312 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,225,004 | 94.8% |
| POP_JUMP_IF_TRUE | 509,704 | 4.0% |
| UNARY_NOT | 84,118 | 0.7% |
| TO_BOOL_BOOL | 41,186 | 0.3% |
| TO_BOOL | 21,361 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 117,464 | 22.0% |
| LOAD_FAST | 109,314 | 20.5% |
| LOAD_ATTR | 107,040 | 20.1% |
| RETURN_VALUE | 106,160 | 19.9% |
| LOAD_FAST_LOAD_FAST | 50,695 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,980 | 24.8% |
| LOAD_GLOBAL_MODULE | 106,844 | 20.0% |
| IS_OP | 106,160 | 19.9% |
| STORE_FAST | 58,035 | 10.9% |
| CALL_LIST_APPEND | 39,980 | 7.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,610 | 65.3% |
| TO_BOOL_BOOL | 1,084,923 | 20.6% |
| TO_BOOL_LIST | 661,860 | 12.6% |
| TO_BOOL | 84,118 | 1.6% |
| TO_BOOL_INT | 167 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,336 | 66.9% |
| STORE_FAST | 882,737 | 16.7% |
| BUILD_MAP | 734,720 | 13.9% |
| COPY | 86,885 | 1.6% |
| LOAD_CONST | 34,340 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,752,616 | 34.5% |
| COMPARE_OP_INT | 6,273,260 | 18.4% |
| COMPARE_OP | 6,162,400 | 18.1% |
| CALL_TUPLE_1 | 4,707,448 | 13.8% |
| LOAD_FAST | 1,516,367 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,134,294 | 70.8% |
| RETURN_VALUE | 5,644,746 | 16.6% |
| CALL_BUILTIN_O | 1,095,105 | 3.2% |
| LOAD_FAST | 857,864 | 2.5% |
| TO_BOOL_INT | 721,950 | 2.1% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,265 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,485 | 97.8% |
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
| STORE_FAST | 3,816,396 | 18.6% |
| SWAP | 3,548,326 | 17.3% |
| LOAD_FAST | 2,131,041 | 10.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,531,307 | 56.3% |
| SWAP | 3,548,326 | 17.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,380 | 11.2% |
| LOAD_FAST | 1,374,230 | 6.7% |
| BUILD_LIST | 748,349 | 3.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,163,622 | 44.8% |
| SWAP | 4,716,268 | 17.4% |
| BUILD_TUPLE | 4,366,319 | 16.1% |
| LOAD_CONST | 1,656,760 | 6.1% |
| RESUME_CHECK | 1,285,960 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,610,792 | 61.2% |
| SWAP | 4,716,268 | 17.4% |
| STORE_FAST | 3,331,411 | 12.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 5.8% |
| CALL_FUNCTION_EX | 734,880 | 2.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,176 | 64.0% |
| SWAP | 18,000 | 35.8% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,176 | 64.0% |
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
| LOAD_FAST_LOAD_FAST | 18,992,073 | 44.9% |
| LOAD_FAST | 10,128,867 | 24.0% |
| LOAD_ATTR_SLOT | 5,042,398 | 11.9% |
| LOAD_ATTR | 3,033,589 | 7.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,220,405 | 50.2% |
| LOAD_GLOBAL_BUILTIN | 4,707,248 | 11.1% |
| BUILD_MAP | 4,366,319 | 10.3% |
| LOAD_CONST | 3,386,859 | 8.0% |
| CALL_LIST_APPEND | 3,214,240 | 7.6% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,375,318 | 34.9% |
| LOAD_FAST | 7,270,384 | 27.1% |
| BINARY_OP_MULTIPLY_INT | 2,291,865 | 8.5% |
| ENTER_EXECUTOR | 2,267,333 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 1,572,923 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,537 | 40.8% |
| STORE_FAST | 5,844,355 | 21.8% |
| RETURN_VALUE | 4,522,960 | 16.8% |
| POP_TOP | 1,145,626 | 4.3% |
| RESUME_CHECK | 1,066,041 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 16,636,008 | 59.4% |
| ENTER_EXECUTOR | 7,551,048 | 27.0% |
| LOAD_FAST | 1,403,530 | 5.0% |
| CALL_INTRINSIC_1 | 1,256,614 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,600,546 | 45.0% |
| RESUME_CHECK | 11,673,298 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,837 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,347,670 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,614 | 93.2% |
| BUILD_MAP | 91,216 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,508,419 | 98.5% |
| ENTER_EXECUTOR | 164,360 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,492,821 | 88.9% |
| POP_TOP | 698,036 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,803 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,085,818 | 57.0% |
| LOAD_FAST | 6,738,025 | 18.2% |
| CALL_TYPE_1 | 5,882,580 | 15.9% |
| LOAD_GLOBAL_MODULE | 1,179,330 | 3.2% |
| LOAD_CONST | 949,662 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,583,351 | 50.3% |
| BINARY_OP | 6,162,400 | 16.7% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.7% |
| UNARY_NOT | 3,442,610 | 9.3% |
| POP_JUMP_IF_TRUE | 2,275,056 | 6.2% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,660,875 | 45.3% |
| LOAD_ATTR | 3,188,632 | 25.5% |
| LOAD_GLOBAL_MODULE | 1,645,870 | 13.2% |
| LOAD_DEREF | 1,478,140 | 11.8% |
| LOAD_CONST | 174,963 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,699,507 | 77.6% |
| POP_JUMP_IF_TRUE | 2,784,981 | 22.3% |
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
| LOAD_FAST | 1,237,533 | 26.8% |
| COPY | 1,069,360 | 23.2% |
| LOAD_FAST_LOAD_FAST | 868,240 | 18.8% |
| CALL_ISINSTANCE | 525,020 | 11.4% |
| LOAD_CONST | 236,756 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,334,423 | 28.9% |
| COPY | 1,069,360 | 23.2% |
| BINARY_SUBSCR_LIST_INT | 1,063,080 | 23.0% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 20.7% |
| STORE_FAST_STORE_FAST | 55,556 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 12,998,972 | 41.1% |
| ENTER_EXECUTOR | 7,042,855 | 22.3% |
| LOAD_ATTR_PROPERTY | 5,065,623 | 16.0% |
| CALL_PY_EXACT_ARGS | 4,700,745 | 14.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,194,690 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,668,896 | 68.5% |
| RETURN_GENERATOR | 9,898,508 | 31.3% |
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

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,571,078 | 99.6% |
| LOAD_DEREF | 64,930 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 16,636,008 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 22,726,498 | 19.1% |
| CALL_LIST_APPEND | 17,313,247 | 14.6% |
| POP_JUMP_IF_TRUE | 15,325,034 | 12.9% |
| POP_JUMP_IF_NONE | 15,174,616 | 12.8% |
| POP_JUMP_IF_FALSE | 14,111,217 | 11.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 18,301,271 | 15.4% |
| POP_JUMP_IF_FALSE | 12,132,090 | 10.2% |
| RESUME_CHECK | 9,635,376 | 8.1% |
| FOR_ITER_LIST | 9,235,929 | 7.8% |
| FOR_ITER_TUPLE | 8,692,198 | 7.3% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,063,300 | 29.7% |
| CALL_LIST_APPEND | 4,571,138 | 26.8% |
| GET_ITER | 2,378,078 | 13.9% |
| ENTER_EXECUTOR | 1,742,148 | 10.2% |
| COMPARE_OP_INT | 1,718,040 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,644,999 | 38.9% |
| ENTER_EXECUTOR | 5,766,507 | 33.8% |
| FOR_ITER_LIST | 2,686,859 | 15.7% |
| FOR_ITER_TUPLE | 767,880 | 4.5% |
| FOR_ITER_RANGE | 642,400 | 3.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 18,973,894 | 55.5% |
| LOAD_FAST | 7,628,665 | 22.3% |
| SWAP | 6,724,940 | 19.7% |
| ENTER_EXECUTOR | 743,660 | 2.2% |
| JUMP_BACKWARD | 71,660 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 24,651,989 | 72.1% |
| ENTER_EXECUTOR | 2,590,072 | 7.6% |
| LOAD_FAST | 2,494,645 | 7.3% |
| SWAP | 1,295,616 | 3.8% |
| DELETE_FAST | 1,284,800 | 3.8% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,757,007 | 86.6% |
| STORE_FAST | 982,265 | 11.0% |
| STORE_DEREF | 185,680 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,820,518 | 76.2% |
| STORE_DEREF | 2,092,374 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,757,767 | 100.0% |
| ENTER_EXECUTOR | 740 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,757,007 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 14,930,350 | 32.8% |
| LOAD_FAST | 12,788,765 | 28.1% |
| LOAD_CONST | 10,975,610 | 24.1% |
| LOAD_FAST_LOAD_FAST | 5,893,454 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 539,779 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,995,287 | 66.0% |
| YIELD_VALUE | 12,773,426 | 28.1% |
| POP_JUMP_IF_TRUE | 2,641,674 | 5.8% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 90,290 | 24.4% |
| POP_TOP | 61,019 | 16.5% |
| LIST_APPEND | 52,030 | 14.1% |
| STORE_FAST | 34,437 | 9.3% |
| POP_JUMP_IF_TRUE | 29,950 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 100,503 | 27.2% |
| FOR_ITER_TUPLE | 80,760 | 21.9% |
| FOR_ITER | 71,660 | 19.4% |
| FOR_ITER_LIST | 53,856 | 14.6% |
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
| STORE_FAST | 4,137,876 | 72.1% |
| POP_TOP | 734,238 | 12.8% |
| STORE_FAST_STORE_FAST | 240,720 | 4.2% |
| CALL_LIST_APPEND | 191,877 | 3.3% |
| LOAD_FAST | 137,385 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,996,154 | 69.6% |
| BUILD_MAP | 642,560 | 11.2% |
| LOAD_FAST_LOAD_FAST | 437,117 | 7.6% |
| LOAD_GLOBAL_BUILTIN | 329,622 | 5.7% |
| STORE_FAST | 118,985 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,144,644 | 44.8% |
| BUILD_TUPLE | 653,898 | 25.6% |
| RETURN_VALUE | 510,768 | 20.0% |
| LOAD_ATTR_PROPERTY | 64,254 | 2.5% |
| BINARY_SUBSCR | 37,830 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,499,760 | 97.8% |
| JUMP_BACKWARD | 52,030 | 2.0% |
| LOAD_NAME | 4,800 | 0.2% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,346,790 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,347,670 | 99.9% |
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
| LOAD_FAST | 50,962,127 | 55.5% |
| LOAD_GLOBAL_MODULE | 33,544,840 | 36.5% |
| CALL_TYPE_1 | 2,352,152 | 2.6% |
| LOAD_ATTR_SLOT | 2,297,040 | 2.5% |
| LOAD_GLOBAL_BUILTIN | 1,904,773 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 34,996,589 | 38.1% |
| LOAD_FAST | 15,958,742 | 17.4% |
| IS_OP | 14,930,350 | 16.3% |
| PUSH_NULL | 8,320,624 | 9.1% |
| CONTAINS_OP | 3,188,632 | 3.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,353,997 | 35.2% |
| LOAD_CONST | 40,195,921 | 23.5% |
| RESUME_CHECK | 15,610,781 | 9.1% |
| RETURN_CONST | 9,526,680 | 5.6% |
| CALL_LEN | 7,177,941 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,195,921 | 23.5% |
| CALL_BUILTIN_FAST | 23,927,829 | 14.0% |
| COMPARE_OP_INT | 20,723,788 | 12.1% |
| STORE_FAST | 14,263,941 | 8.3% |
| IS_OP | 10,975,610 | 6.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 10,423,717 | 20.7% |
| STORE_FAST_STORE_FAST | 9,260,202 | 18.4% |
| LOAD_ATTR_SLOT | 6,403,832 | 12.7% |
| POP_JUMP_IF_FALSE | 4,643,953 | 9.2% |
| LOAD_ATTR_METHOD_NO_DICT | 3,319,020 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 11,776,240 | 23.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,434,225 | 18.7% |
| LOAD_FAST | 9,344,763 | 18.5% |
| BINARY_SUBSCR | 6,403,832 | 12.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,109,100 | 6.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,549,491 | 19.1% |
| LOAD_GLOBAL_BUILTIN | 140,532,300 | 16.9% |
| RESUME_CHECK | 115,545,332 | 13.9% |
| POP_JUMP_IF_FALSE | 106,013,744 | 12.7% |
| PUSH_NULL | 35,230,654 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 94,051,830 | 11.3% |
| LOAD_ATTR_METHOD_NO_DICT | 73,153,932 | 8.8% |
| LOAD_CONST | 60,353,997 | 7.2% |
| RETURN_VALUE | 52,902,813 | 6.3% |
| LOAD_GLOBAL_MODULE | 51,675,366 | 6.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,282,594 | 55.4% |
| LOAD_FAST_AND_CLEAR | 6,674,486 | 44.6% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 8,282,514 | 55.4% |
| LOAD_FAST_AND_CLEAR | 6,674,486 | 44.6% |
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
| STORE_FAST | 43,469,821 | 21.3% |
| POP_JUMP_IF_FALSE | 28,995,114 | 14.2% |
| LOAD_GLOBAL_BUILTIN | 28,346,595 | 13.9% |
| STORE_FAST_STORE_FAST | 14,727,760 | 7.2% |
| POP_JUMP_IF_NONE | 13,357,073 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 21,085,818 | 10.3% |
| BINARY_SUBSCR_LIST_INT | 19,369,931 | 9.5% |
| BUILD_TUPLE | 18,992,073 | 9.3% |
| STORE_SUBSCR_LIST_INT | 18,851,234 | 9.2% |
| CALL_BUILTIN_FAST | 17,202,484 | 8.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,268 | 19.4% |
| LOAD_FAST | 34,206 | 18.8% |
| STORE_FAST | 26,933 | 14.8% |
| RESUME_CHECK | 10,938 | 6.0% |
| RESUME | 10,782 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,550 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,268 | 22.7% |
| LOAD_FAST | 39,592 | 21.8% |
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
| MAKE_CELL | 2,274,491 | 37.6% |
| CACHE | 1,509,166 | 24.9% |
| CALL_PY_EXACT_ARGS | 768,449 | 12.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,450 | 10.8% |
| CALL | 523,659 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,770,867 | 62.3% |
| MAKE_CELL | 2,274,491 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,853,580 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,863,304 | 100.0% |
| JUMP_BACKWARD | 2,396 | 0.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 105,140,695 | 40.9% |
| COMPARE_OP_INT | 33,134,101 | 12.9% |
| IS_OP | 29,995,287 | 11.7% |
| COMPARE_OP | 18,583,351 | 7.2% |
| COMPARE_OP_STR | 14,480,255 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 106,013,744 | 41.2% |
| LOAD_GLOBAL_BUILTIN | 57,848,131 | 22.5% |
| LOAD_FAST_LOAD_FAST | 28,995,114 | 11.3% |
| RETURN_CONST | 27,834,461 | 10.8% |
| ENTER_EXECUTOR | 14,111,217 | 5.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 18,301,271 | 54.0% |
| LOAD_FAST | 8,982,240 | 26.5% |
| BINARY_SUBSCR | 5,494,851 | 16.2% |
| LOAD_DEREF | 1,088,838 | 3.2% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,174,616 | 44.8% |
| LOAD_FAST_LOAD_FAST | 13,357,073 | 39.4% |
| LOAD_FAST | 2,491,681 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 1,437,887 | 4.2% |
| LOAD_CONST | 1,111,414 | 3.3% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,653,745 | 92.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,224,921 | 6.8% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,226,184 | 67.6% |
| LOAD_FAST_LOAD_FAST | 2,036,630 | 11.3% |
| LOAD_GLOBAL_MODULE | 1,878,159 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,096 | 7.7% |
| ENTER_EXECUTOR | 447,531 | 2.5% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 48,120,231 | 70.3% |
| TO_BOOL_INT | 8,150,291 | 11.9% |
| CONTAINS_OP | 2,784,981 | 4.1% |
| IS_OP | 2,641,674 | 3.9% |
| COMPARE_OP | 2,275,056 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,430,759 | 48.8% |
| ENTER_EXECUTOR | 15,325,034 | 22.4% |
| LOAD_GLOBAL_BUILTIN | 5,254,915 | 7.7% |
| NOP | 4,184,029 | 6.1% |
| BUILD_LIST | 4,083,245 | 6.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,878 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,218 | 98.4% |
| COPY | 1,760 | 1.5% |
| LOAD_CONST | 160 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 27,834,461 | 51.1% |
| RESUME_CHECK | 10,045,023 | 18.5% |
| FOR_ITER_LIST | 5,672,193 | 10.4% |
| ENTER_EXECUTOR | 4,688,113 | 8.6% |
| STORE_SUBSCR | 1,939,123 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,282,187 | 59.3% |
| LOAD_CONST | 9,526,680 | 17.5% |
| POP_TOP | 8,140,710 | 15.0% |
| TO_BOOL_BOOL | 1,883,974 | 3.5% |
| STORE_FAST | 1,541,182 | 2.8% |


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
| MAKE_FUNCTION | 3,367,681 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,816,413 | 83.6% |
| STORE_FAST | 298,218 | 8.9% |
| STORE_DEREF | 95,657 | 2.8% |
| LOAD_CONST | 52,360 | 1.6% |
| LOAD_GLOBAL_MODULE | 43,024 | 1.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,753 | 82.3% |
| LOAD_FAST | 98,460 | 16.7% |
| STORE_ATTR | 3,906 | 0.7% |
| SWAP | 2,143 | 0.4% |
| LOAD_DEREF | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,615 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,218 | 19.7% |
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
| IMPORT_FROM | 2,092,374 | 27.2% |
| LOAD_ATTR | 1,558,832 | 20.2% |
| STORE_FAST | 240,860 | 3.1% |
| SET_FUNCTION_ATTRIBUTE | 95,657 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,577,840 | 46.5% |
| POP_TOP | 1,906,694 | 24.8% |
| LOAD_DEREF | 1,298,312 | 16.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 6.3% |
| IMPORT_FROM | 185,680 | 2.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,446,158 | 13.5% |
| LOAD_ATTR | 34,996,589 | 12.2% |
| BINARY_OP | 24,134,294 | 8.4% |
| LOAD_ATTR_SLOT | 22,509,932 | 7.9% |
| LOAD_CONST | 14,263,941 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,549,491 | 55.8% |
| LOAD_FAST_LOAD_FAST | 43,469,821 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 29,940,051 | 10.5% |
| LOAD_GLOBAL_MODULE | 11,161,917 | 3.9% |
| STORE_FAST | 9,340,731 | 3.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,260,327 | 71.8% |
| FOR_ITER_TUPLE | 409,043 | 23.3% |
| FOR_ITER_RANGE | 47,440 | 2.7% |
| FOR_ITER | 38,161 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,178,898 | 67.2% |
| LOAD_ATTR_PROPERTY | 190,464 | 10.9% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 187,912 | 10.7% |
| LOAD_DEREF | 49,680 | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 45,840 | 2.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 42,809,460 | 86.5% |
| RETURN_VALUE | 3,248,259 | 6.6% |
| UNPACK_SEQUENCE_TUPLE | 1,396,599 | 2.8% |
| STORE_FAST_STORE_FAST | 771,153 | 1.6% |
| BUILD_LIST | 413,120 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 14,727,760 | 29.8% |
| LOAD_FAST | 13,892,605 | 28.1% |
| LOAD_DEREF | 9,260,202 | 18.7% |
| LOAD_GLOBAL_BUILTIN | 8,512,819 | 17.2% |
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
| BINARY_SUBSCR_LIST_INT | 9,397,157 | 21.8% |
| LOAD_FAST_AND_CLEAR | 8,282,514 | 19.2% |
| ENTER_EXECUTOR | 6,307,392 | 14.6% |
| BUILD_MAP | 4,716,268 | 10.9% |
| LOAD_FAST | 4,609,881 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,397,377 | 21.8% |
| STORE_FAST | 7,930,935 | 18.4% |
| FOR_ITER | 6,724,940 | 15.6% |
| POP_TOP | 5,747,061 | 13.3% |
| BUILD_MAP | 4,716,268 | 10.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,454 | 26.4% |
| FOR_ITER | 6,803 | 17.2% |
| CALL_BUILTIN_CLASS | 6,340 | 16.0% |
| LOAD_FAST | 3,941 | 9.9% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,673 | 47.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,432 | 23.8% |
| STORE_FAST | 8,006 | 20.2% |
| UNPACK_SEQUENCE_TUPLE | 1,140 | 2.9% |
| UNPACK_SEQUENCE | 913 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,773,426 | 55.4% |
| ENTER_EXECUTOR | 4,974,567 | 21.6% |
| CALL_ISINSTANCE | 2,232,644 | 9.7% |
| LOAD_FAST | 1,140,890 | 5.0% |
| YIELD_VALUE | 677,544 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,190,909 | 96.3% |
| YIELD_VALUE | 677,544 | 2.9% |
| STORE_FAST | 162,816 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,058 | 38.0% |
| CALL | 11,112 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,100 | 12.8% |
| POP_TOP | 3,961 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,693 | 37.2% |
| LOAD_GLOBAL | 10,782 | 22.7% |
| LOAD_CONST | 8,762 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,361 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,594,434 | 69.3% |
| LOAD_FAST_LOAD_FAST | 573,681 | 15.3% |
| BINARY_SUBSCR_DICT | 420,640 | 11.2% |
| CALL_BUILTIN_CLASS | 81,105 | 2.2% |
| LOAD_FAST | 43,684 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,536,169 | 41.0% |
| SWAP | 942,323 | 25.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 539,771 | 14.4% |
| LOAD_CONST | 268,916 | 7.2% |
| LOAD_FAST | 201,398 | 5.4% |


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
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,678 | 60.5% |
| LOAD_ATTR_SLOT | 723,513 | 26.2% |
| LOAD_FAST_LOAD_FAST | 269,737 | 9.8% |
| LOAD_FAST | 94,285 | 3.4% |
| BINARY_OP | 1,447 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,865 | 83.1% |
| LOAD_FAST_LOAD_FAST | 181,166 | 6.6% |
| STORE_FAST | 175,511 | 6.4% |
| LOAD_FAST | 76,506 | 2.8% |
| LOAD_GLOBAL_MODULE | 25,180 | 0.9% |


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
| LOAD_CONST | 1,556,120 | 62.9% |
| LOAD_FAST_LOAD_FAST | 606,768 | 24.5% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 122,671 | 5.0% |
| BINARY_OP | 2,187 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,080,100 | 43.7% |
| STORE_FAST | 699,468 | 28.3% |
| BINARY_OP | 311,595 | 12.6% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 53,880 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,317 | 33.9% |
| LOAD_FAST_LOAD_FAST | 810,264 | 26.6% |
| LOAD_CONST | 642,800 | 21.1% |
| CALL_TUPLE_1 | 441,520 | 14.5% |
| RETURN_VALUE | 114,484 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 865,878 | 28.4% |
| RETURN_VALUE | 809,110 | 26.5% |
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
| LOAD_CONST | 14,538 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 159,236 | 100.0% |
| RETURN_VALUE | 1 | 0.0% |
| LOAD_CONST | 1 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 19,369,931 | 88.0% |
| COPY | 1,063,080 | 4.8% |
| LOAD_CONST | 1,025,947 | 4.7% |
| CALL_BUILTIN_CLASS | 282,344 | 1.3% |
| LOAD_FAST | 204,128 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,405,517 | 42.7% |
| SWAP | 9,397,157 | 42.7% |
| LOAD_CONST | 1,063,540 | 4.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 534,577 | 2.4% |
| RETURN_VALUE | 432,290 | 2.0% |


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
| LOAD_CONST | 8,718,746 | 97.0% |
| LOAD_FAST | 263,291 | 2.9% |
| BINARY_SUBSCR | 2,737 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,735,441 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 321,897 | 3.6% |
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
| LOAD_FAST | 13,127,528 | 91.3% |
| BINARY_OP_ADD_INT | 539,771 | 3.8% |
| LOAD_FAST_LOAD_FAST | 480,425 | 3.3% |
| LOAD_ATTR | 152,040 | 1.1% |
| RETURN_VALUE | 36,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,525,184 | 87.1% |
| COPY_FREE_VARS | 1,194,690 | 8.3% |
| MAKE_CELL | 654,450 | 4.6% |
| POP_TOP | 7,360 | 0.1% |
| RESUME | 620 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,795,179 | 33.0% |
| CALL_BUILTIN_CLASS | 1,959,371 | 23.1% |
| LOAD_CONST | 710,920 | 8.4% |
| CALL_LEN | 611,113 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 566,469 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,979,550 | 35.1% |
| CALL_BUILTIN_CLASS | 1,959,371 | 23.1% |
| GET_ITER | 1,728,192 | 20.4% |
| CALL | 284,252 | 3.4% |
| BINARY_SUBSCR_LIST_INT | 282,344 | 3.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 23,927,829 | 55.6% |
| LOAD_FAST_LOAD_FAST | 17,202,484 | 40.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,318 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 40,898 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 17,882,307 | 41.7% |
| STORE_FAST | 10,859,015 | 25.3% |
| TO_BOOL | 10,287,220 | 24.0% |
| PUSH_NULL | 2,128,620 | 5.0% |
| RETURN_VALUE | 1,500,087 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,968 | 94.4% |
| LOAD_FAST | 135,022 | 2.6% |
| BINARY_OP | 119,045 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,248 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 127,922 | 2.5% |
| CALL_BUILTIN_CLASS | 119,045 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,705,898 | 41.7% |
| RETURN_GENERATOR | 10,202,962 | 27.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,616,201 | 14.9% |
| LOAD_ATTR_SLOT | 4,876,343 | 12.9% |
| BINARY_OP | 1,095,105 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,591,494 | 36.1% |
| RETURN_VALUE | 11,432,749 | 30.4% |
| TO_BOOL_BOOL | 9,880,688 | 26.2% |
| GET_ITER | 2,591,112 | 6.9% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 29,351,566 | 54.3% |
| LOAD_GLOBAL_BUILTIN | 17,190,463 | 31.8% |
| LOAD_DEREF | 2,859,553 | 5.3% |
| LOAD_FAST_LOAD_FAST | 2,648,434 | 4.9% |
| LOAD_FAST | 1,615,016 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 51,181,805 | 94.7% |
| YIELD_VALUE | 2,232,644 | 4.1% |
| COPY | 525,020 | 1.0% |
| RETURN_VALUE | 71,509 | 0.1% |
| TO_BOOL | 9,664 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,053,408 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 173,720 | 0.6% |
| RETURN_VALUE | 95,047 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,270,303 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,676,009 | 34.5% |
| LOAD_CONST | 7,177,941 | 25.6% |
| CALL_BUILTIN_CLASS | 611,113 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,552,601 | 64.8% |
| BUILD_TUPLE | 3,214,240 | 13.4% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| ENTER_EXECUTOR | 963,240 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 17,313,247 | 72.1% |
| EXTENDED_ARG | 4,571,138 | 19.0% |
| LOAD_FAST | 1,681,749 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |
| JUMP_FORWARD | 191,877 | 0.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,883,363 | 45.1% |
| ENTER_EXECUTOR | 5,232,437 | 23.9% |
| LOAD_CONST | 2,331,790 | 10.6% |
| BUILD_LIST | 2,294,380 | 10.5% |
| BUILD_MAP | 1,561,360 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,818,385 | 58.5% |
| STORE_FAST | 3,360,908 | 15.3% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.2% |
| POP_TOP | 908,789 | 4.1% |
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
| LOAD_ATTR_METHOD_NO_DICT | 22,646,031 | 81.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,805 | 17.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,794 | 0.4% |
| LOAD_ATTR | 72,820 | 0.3% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 12,589,539 | 45.5% |
| STORE_FAST | 9,687,883 | 35.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,968 | 17.7% |
| CALL_BUILTIN_CLASS | 169,723 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,794 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 62.3% |
| LOAD_CONST | 1,226,421 | 26.8% |
| LOAD_FAST | 290,680 | 6.3% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,234,100 | 70.5% |
| LOAD_CONST | 1,224,421 | 26.7% |
| TO_BOOL_NONE | 42,400 | 0.9% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.6% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 20,793,710 | 39.6% |
| LOAD_FAST | 15,173,826 | 28.9% |
| GET_ITER | 6,004,085 | 11.4% |
| LOAD_FAST_LOAD_FAST | 5,982,648 | 11.4% |
| LOAD_SUPER_ATTR_METHOD | 1,539,393 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 42,763,323 | 81.4% |
| COPY_FREE_VARS | 4,700,745 | 8.9% |
| RETURN_GENERATOR | 4,117,018 | 7.8% |
| MAKE_CELL | 768,449 | 1.5% |
| CALL_PY_EXACT_ARGS | 145,245 | 0.3% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,621,630 | 35.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,373,902 | 29.9% |
| ENTER_EXECUTOR | 1,014,445 | 22.1% |
| RETURN_VALUE | 192,565 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 157,770 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,372,601 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,709 | 1.2% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,248 | 80.5% |
| LOAD_FAST | 1,014,980 | 17.4% |
| STORE_FAST | 105,736 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,116 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,448 | 80.5% |
| BINARY_SUBSCR_DICT | 441,520 | 7.5% |
| STORE_FAST | 353,176 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,728,632 | 99.5% |
| LOAD_CONST | 65,938 | 0.4% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,082 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,673 | 43.4% |
| COMPARE_OP | 5,882,580 | 39.8% |
| LOAD_ATTR | 2,352,152 | 15.9% |
| IS_OP | 64,198 | 0.4% |
| STORE_FAST | 32,875 | 0.2% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,673 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,616 | 4.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,069 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,723,788 | 42.6% |
| LOAD_FAST_LOAD_FAST | 16,123,136 | 33.2% |
| CALL_LEN | 10,270,303 | 21.1% |
| LOAD_FAST | 971,235 | 2.0% |
| LOAD_ATTR_SLOT | 225,403 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,134,101 | 68.2% |
| BINARY_OP | 6,273,260 | 12.9% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.8% |
| EXTENDED_ARG | 1,718,040 | 3.5% |
| LOAD_FAST_LOAD_FAST | 1,534,520 | 3.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 69.1% |
| LOAD_CONST | 4,295,654 | 29.6% |
| LOAD_GLOBAL_MODULE | 192,417 | 1.3% |
| LOAD_FAST | 2,040 | 0.0% |
| LOAD_ATTR | 1,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,480,255 | 99.7% |
| YIELD_VALUE | 40,076 | 0.3% |
| POP_JUMP_IF_TRUE | 2,080 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,235,929 | 41.3% |
| LOAD_FAST | 4,844,077 | 21.7% |
| GET_ITER | 4,310,553 | 19.3% |
| EXTENDED_ARG | 2,686,859 | 12.0% |
| SWAP | 1,219,647 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,052,384 | 40.5% |
| RETURN_CONST | 5,672,193 | 25.4% |
| LOAD_FAST | 4,094,122 | 18.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,465,725 | 6.6% |
| STORE_FAST_LOAD_FAST | 1,260,327 | 5.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 827,399 | 37.2% |
| GET_ITER | 669,153 | 30.1% |
| EXTENDED_ARG | 642,400 | 28.9% |
| SWAP | 38,880 | 1.7% |
| LOAD_FAST | 29,360 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,306,831 | 58.7% |
| RETURN_CONST | 630,333 | 28.3% |
| LOAD_FAST | 195,180 | 8.8% |
| STORE_FAST_LOAD_FAST | 47,440 | 2.1% |
| SWAP | 38,520 | 1.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,970,494 | 49.0% |
| ENTER_EXECUTOR | 8,692,198 | 42.7% |
| EXTENDED_ARG | 767,880 | 3.8% |
| LOAD_FAST | 518,195 | 2.5% |
| SWAP | 299,127 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,207,929 | 50.2% |
| LOAD_FAST | 7,494,368 | 36.8% |
| RETURN_CONST | 788,423 | 3.9% |
| LOAD_GLOBAL_MODULE | 602,498 | 3.0% |
| STORE_FAST_LOAD_FAST | 409,043 | 2.0% |


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
| LOAD_FAST | 5,478,884 | 60.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,313 | 11.7% |
| LOAD_DEREF | 1,057,773 | 11.7% |
| COPY | 956,400 | 10.6% |
| LOAD_GLOBAL_MODULE | 481,636 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,361 | 17.2% |
| CALL_BUILTIN_FAST | 1,337,318 | 14.8% |
| POP_JUMP_IF_NOT_NONE | 1,224,921 | 13.5% |
| STORE_FAST | 1,075,473 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,060,313 | 11.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,153,932 | 84.7% |
| RETURN_VALUE | 4,635,768 | 5.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.6% |
| LOAD_GLOBAL_MODULE | 1,964,502 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,361 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,559,368 | 34.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 22,646,031 | 26.2% |
| CALL_PY_EXACT_ARGS | 20,793,710 | 24.1% |
| LOAD_CONST | 4,050,406 | 4.7% |
| LOAD_DEREF | 3,319,020 | 3.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 9,434,225 | 52.7% |
| LOAD_ATTR_SLOT | 4,711,348 | 26.3% |
| LOAD_FAST | 3,526,141 | 19.7% |
| LOAD_ATTR | 147,514 | 0.8% |
| STORE_FAST_LOAD_FAST | 45,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,814,096 | 54.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,805 | 26.9% |
| LOAD_FAST_LOAD_FAST | 2,941,192 | 16.4% |
| CALL_PY_EXACT_ARGS | 317,213 | 1.8% |
| LOAD_CONST | 6,679 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260,586 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% |
| LOAD_ATTR | 1,402 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,043 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,606 | 6.3% |
| CALL | 57,379 | 4.5% |
| LOAD_FAST | 25,860 | 2.0% |
| LOAD_ATTR_SLOT | 15,920 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,060,819 | 83.2% |
| ENTER_EXECUTOR | 5,159,444 | 9.1% |
| LOAD_DEREF | 3,109,100 | 5.5% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 212,594 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,045,190 | 74.4% |
| CALL_BUILTIN_O | 5,616,201 | 9.9% |
| BUILD_TUPLE | 2,484,120 | 4.4% |
| LOAD_FAST | 1,921,263 | 3.4% |
| BINARY_OP_MULTIPLY_INT | 1,668,678 | 3.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 990,895 | 60.1% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.0% |
| LOAD_DEREF | 144,340 | 8.8% |
| ENTER_EXECUTOR | 14,401 | 0.9% |
| LOAD_ATTR | 12,020 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.0% |
| TO_BOOL_STR | 478,200 | 29.0% |
| TO_BOOL_BOOL | 409,793 | 24.9% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,062,832 | 89.5% |
| ENTER_EXECUTOR | 1,561,677 | 5.6% |
| RETURN_VALUE | 642,650 | 2.3% |
| LOAD_DEREF | 190,718 | 0.7% |
| STORE_FAST_LOAD_FAST | 190,464 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,812,351 | 67.2% |
| COPY_FREE_VARS | 5,065,623 | 18.1% |
| GET_ITER | 1,920,096 | 6.9% |
| TO_BOOL_BOOL | 712,073 | 2.5% |
| STORE_FAST | 506,314 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 94,051,830 | 98.5% |
| ENTER_EXECUTOR | 632,630 | 0.7% |
| LOAD_ATTR_SLOT | 613,612 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,046 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 69,950 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,431,955 | 35.0% |
| STORE_FAST | 22,509,932 | 23.6% |
| LOAD_DEREF | 6,403,832 | 6.7% |
| LOAD_FAST | 5,219,501 | 5.5% |
| LOAD_CONST | 5,210,211 | 5.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,848,131 | 27.8% |
| RESUME_CHECK | 41,193,751 | 19.8% |
| STORE_FAST | 29,940,051 | 14.4% |
| LOAD_FAST | 18,549,821 | 8.9% |
| CALL_LEN | 9,676,009 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,532,300 | 67.6% |
| LOAD_FAST_LOAD_FAST | 28,346,595 | 13.6% |
| CALL_ISINSTANCE | 17,190,463 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 8,864,247 | 4.3% |
| LOAD_DEREF | 3,164,289 | 1.5% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,675,366 | 46.9% |
| RESUME_CHECK | 16,025,349 | 14.5% |
| STORE_FAST | 11,161,917 | 10.1% |
| POP_JUMP_IF_FALSE | 9,671,704 | 8.8% |
| NOP | 6,377,167 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 33,544,840 | 30.4% |
| CALL_ISINSTANCE | 29,351,566 | 26.6% |
| LOAD_FAST | 28,277,836 | 25.7% |
| LOAD_DEREF | 3,256,272 | 3.0% |
| LOAD_FAST_LOAD_FAST | 3,201,267 | 2.9% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,491 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,181,891 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,807,630 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,393 | 85.1% |
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
| CACHE | 99,153,236 | 39.6% |
| CALL_PY_EXACT_ARGS | 42,763,323 | 17.1% |
| COPY_FREE_VARS | 21,668,896 | 8.7% |
| LOAD_ATTR_PROPERTY | 18,812,351 | 7.5% |
| POP_TOP | 14,336,786 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,545,332 | 46.2% |
| LOAD_GLOBAL_BUILTIN | 41,193,751 | 16.5% |
| NOP | 21,363,228 | 8.5% |
| LOAD_GLOBAL_MODULE | 16,025,349 | 6.4% |
| LOAD_CONST | 15,610,781 | 6.2% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 661,220 | 64.2% |
| LOAD_CONST | 368,044 | 35.7% |
| SEND | 620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 646,240 | 62.7% |
| POP_TOP | 352,984 | 34.3% |
| YIELD_VALUE | 15,060 | 1.5% |
| END_SEND | 15,020 | 1.5% |
| SEND | 580 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,103,749 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,123 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,689 | 36.0% |
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
| LOAD_FAST_LOAD_FAST | 4,731,741 | 52.2% |
| LOAD_FAST | 4,284,184 | 47.3% |
| STORE_ATTR_SLOT | 41,768 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,672,521 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,255,802 | 24.9% |
| LOAD_CONST | 1,890,388 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,854 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,568,583 | 68.9% |
| LOAD_FAST | 396,654 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 8.0% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,323 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,647,200 | 72.4% |
| EXTENDED_ARG | 226,737 | 10.0% |
| LOAD_FAST_LOAD_FAST | 183,280 | 8.1% |
| LOAD_FAST | 164,822 | 7.2% |
| LOAD_GLOBAL_MODULE | 38,943 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,851,234 | 93.9% |
| SWAP | 1,063,080 | 5.3% |
| LOAD_FAST | 98,929 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |
| LOAD_CONST | 20,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,019,897 | 49.9% |
| ENTER_EXECUTOR | 9,994,486 | 49.8% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |
| LOAD_CONST | 19,800 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 224,175 | 98.5% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| ENTER_EXECUTOR | 860 | 0.4% |
| STORE_FAST_LOAD_FAST | 760 | 0.3% |
| TO_BOOL | 388 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 216,425 | 95.1% |
| POP_JUMP_IF_FALSE | 9,707 | 4.3% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 51 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 51,181,805 | 32.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 42,045,190 | 26.4% |
| LOAD_FAST | 21,598,325 | 13.5% |
| CALL_BUILTIN_FAST | 17,882,307 | 11.2% |
| CALL_BUILTIN_O | 9,880,688 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 105,140,695 | 66.0% |
| POP_JUMP_IF_TRUE | 48,120,231 | 30.2% |
| EXTENDED_ARG | 5,063,300 | 3.2% |
| UNARY_NOT | 1,084,923 | 0.7% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,624,932 | 95.3% |
| BINARY_OP | 721,950 | 3.9% |
| BINARY_SUBSCR_TUPLE_INT | 63,297 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 45,280 | 0.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,851 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,350,380 | 55.9% |
| POP_JUMP_IF_TRUE | 8,150,291 | 44.1% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 167 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,227,708 | 97.5% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 9,089 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |
| TO_BOOL | 2,147 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 822,760 | 36.0% |
| POP_JUMP_IF_TRUE | 784,504 | 34.3% |
| UNARY_NOT | 661,860 | 29.0% |
| EXTENDED_ARG | 15,720 | 0.7% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,686 | 69.6% |
| RETURN_VALUE | 389,140 | 14.7% |
| LOAD_ATTR_PROPERTY | 293,429 | 11.1% |
| CALL_METHOD_DESCRIPTOR_O | 42,400 | 1.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,990 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,938,297 | 73.2% |
| POP_JUMP_IF_TRUE | 690,103 | 26.1% |
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
| LOAD_FAST | 884,545 | 55.6% |
| RETURN_VALUE | 660,886 | 41.5% |
| STORE_FAST | 40,240 | 2.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,396,599 | 87.8% |
| STORE_FAST | 154,712 | 9.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.5% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 24,651,989 | 52.9% |
| RETURN_VALUE | 19,465,570 | 41.8% |
| FOR_ITER_LIST | 1,465,725 | 3.1% |
| BINARY_SUBSCR_LIST_INT | 534,577 | 1.1% |
| FOR_ITER_TUPLE | 285,089 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 42,809,460 | 91.9% |
| STORE_DEREF | 3,577,880 | 7.7% |
| STORE_FAST | 215,267 | 0.5% |
| UNPACK_SEQUENCE_LIST | 1,760 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,320 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 22,486 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,486 | 100.0% |


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

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,503 | 52.5% |
| GET_ITER | 90,659 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,583 | 52.1% |
| POP_TOP | 90,499 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


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
|     deferred | 34,031,157 | 78.0% |
|          hit | 9,527,670 | 21.8% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,778 | 11.8% |
| Failure | 50,462 | 88.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,457 | 18.7% |
| multiply different types | 7,163 | 14.2% |
| subtract other | 6,740 | 13.4% |
| and int | 4,122 | 8.2% |
| rshift | 3,805 | 7.5% |
| or | 3,700 | 7.3% |
| power | 2,861 | 5.7% |
| true divide different types | 2,523 | 5.0% |
| multiply other | 2,260 | 4.5% |
| remainder | 2,071 | 4.1% |
| add different types | 1,822 | 3.6% |
| floor divide | 1,272 | 2.5% |
| subtract different types | 1,180 | 2.3% |
| xor | 583 | 1.2% |
| and other | 373 | 0.7% |
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
|     deferred | 20,469,838 | 37.4% |
|          hit | 34,206,909 | 62.5% |
|         miss | 14,909 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,717 | 34.3% |
| Failure | 14,796 | 65.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 11,493 | 77.7% |
| out of range | 1,960 | 13.2% |
| buffer int | 1,320 | 8.9% |
| array int | 20 | 0.1% |
| tuple slice | 3 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,134,169 | 6.7% |
|        deopt | 22,840 | 0.0% |
|          hit | 330,085,647 | 85.0% |
|         miss | 31,433,976 | 8.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 673,544 | 90.2% |
| Failure | 72,870 | 9.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,606 | 39.3% |
| code complex parameters | 14,049 | 19.3% |
| class no vectorcall | 9,220 | 12.7% |
| cfunc varargs keywords | 6,385 | 8.8% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.5% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,170 | 3.0% |
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
|     deferred | 36,877,808 | 36.6% |
|          hit | 63,088,385 | 62.7% |
|         miss | 575,932 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,468 | 22.9% |
| Failure | 68,815 | 77.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,421 | 26.8% |
| other | 15,224 | 22.1% |
| different types | 12,159 | 17.7% |
| tuple | 10,050 | 14.6% |
| string | 9,960 | 14.5% |
| bool | 1,801 | 2.6% |
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
|     deferred | 34,132,396 | 43.0% |
|          hit | 44,719,579 | 56.4% |
|         miss | 394,192 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 19,310 | 27.5% |
| Failure | 50,866 | 72.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 31,699 | 62.3% |
| zip | 4,980 | 9.8% |
| set | 4,463 | 8.8% |
| enumerate | 3,564 | 7.0% |
| other | 1,980 | 3.9% |
| itertools | 1,840 | 3.6% |
| dict keys | 1,400 | 2.8% |
| reversed list | 780 | 1.5% |
| dict values | 80 | 0.2% |
| ascii string | 80 | 0.2% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 90,403,555 | 23.3% |
|        deopt | 20 | 0.0% |
|          hit | 230,841,014 | 59.4% |
|         miss | 65,667,922 | 16.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,316,778 | 89.7% |
| Failure | 151,695 | 10.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mutable class | 58,662 | 38.7% |
| metaclass attribute | 53,182 | 35.1% |
| method | 10,381 | 6.8% |
| overridden | 8,662 | 5.7% |
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
|     deferred | 89,883 | 0.0% |
|          hit | 318,214,419 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 91,978 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 605 | 0.0% |
|          hit | 2,990,021 | 100.0% |

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
|          hit | 999,224 | 67.8% |
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
|     deferred | 540,540 | 4.2% |
|          hit | 10,196,980 | 78.4% |
|         miss | 2,220,645 | 17.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,828 | 92.3% |
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
|     deferred | 2,034,569 | 8.3% |
|          hit | 22,362,127 | 91.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,724 | 44.7% |
| Failure | 3,375 | 55.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 3,375 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,813,747 | 6.5% |
|          hit | 183,134,938 | 93.2% |
|         miss | 440,062 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,942 | 72.3% |
| Failure | 22,932 | 27.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,787 | 47.0% |
| number | 3,496 | 15.2% |
| mapping | 3,300 | 14.4% |
| dict | 2,260 | 9.9% |
| other | 1,623 | 7.1% |
| set | 1,426 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,479 | 0.1% |
|          hit | 48,376,638 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,392 | 93.6% |
| Failure | 773 | 6.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 713 | 92.2% |
| iterator | 60 | 7.8% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 2,684,498,722 | 54.1% |
| Not specialized | 638,819,661 | 12.9% |
| Specialized hits | 1,534,497,067 | 30.9% |
| Specialized misses | 100,798,878 | 2.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 90,403,555 | 35.0% |
| COMPARE_OP | 36,877,808 | 14.3% |
| FOR_ITER | 34,132,396 | 13.2% |
| BINARY_OP | 34,031,157 | 13.2% |
| CALL | 26,134,169 | 10.1% |
| BINARY_SUBSCR | 20,469,838 | 7.9% |
| TO_BOOL | 12,813,747 | 5.0% |
| STORE_SUBSCR | 2,034,569 | 0.8% |
| STORE_ATTR | 540,540 | 0.2% |
| SEND | 439,140 | 0.2% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,443,120 | 36.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 15,595,432 | 15.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,405,700 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 9,032,763 | 9.0% |
| CALL_PY_EXACT_ARGS | 7,811,947 | 7.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,562 | 6.4% |
| LOAD_ATTR_PROPERTY | 4,106,719 | 4.1% |
| CALL_BUILTIN_O | 2,661,157 | 2.6% |
| STORE_ATTR_SLOT | 2,219,665 | 2.2% |
| COMPARE_OP_INT | 574,332 | 0.6% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,580,516 | 51.5% |
| Calls to Python functions inlined | 120,107,586 | 48.5% |
| Calls via PyEval_EvalFrame (total) | 127,580,516 | 51.5% |
| Calls via PyEval_EvalFrame (vector) | 98,448,491 | 39.7% |
| Calls via PyEval_EvalFrame (generator) | 29,132,025 | 11.8% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,441,191 | 39.7% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,667,877 | 9.6% |
| Calls via PyEval_EvalFrame (function ex) | 11,824,742 | 4.8% |
| Calls via PyEval_EvalFrame (api) | 53,322,043 | 21.5% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,017 | 0.5% |
| Frames pushed | 112,688,910 | 45.5% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,436,304 | 54.3% |
| Frees to freelist | 363,679,240 |  |
| Allocations | 305,627,215 | 45.7% |
| Allocations to 512 bytes | 304,551,797 | 45.5% |
| Allocations to 4 kbytes | 1,050,958 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,299,161 |  |
| New values | 1,057,329 |  |
| Interpreter increfs | 2,688,699,222 | 65.3% |
| Interpreter decrefs | 3,114,082,190 | 66.3% |
| Increfs | 1,430,143,690 | 34.7% |
| Decrefs | 1,585,561,168 | 33.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 241,977,361 |  |
| Method cache misses | 3,779,729 |  |
| Method cache collisions | 4,955,743 |  |
| Method cache dunder hits | 347,618,072 |  |
| Method cache dunder misses | 1,176,642 |  |


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
| Optimization attempts | 14,047 |  |
| Traces created | 13,287 | 94.6% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 234 | 1.7% |
| Trace too long | 20 | 0.1% |
| Trace too short | 760 | 5.4% |
| Inner loop found | 260 | 1.9% |
| Recursive call | 160 | 1.1% |
| Traces executed | 118,906,797 |  |
| Uops executed | 2,224,891,618 | 18.71 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 2,675 | 20.1% |
| <= 32 | 5,253 | 39.5% |
| <= 64 | 3,680 | 27.7% |
| <= 128 | 1,268 | 9.5% |
| <= 256 | 411 | 3.1% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,655 | 20.0% |
| <= 16 | 4,320 | 32.5% |
| <= 32 | 3,972 | 29.9% |
| <= 64 | 1,969 | 14.8% |
| <= 128 | 311 | 2.3% |
| <= 256 | 60 | 0.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 1,886,320 | 1.6% |
| <= 2 | 28,422,720 | 23.9% |
| <= 4 | 737,939 | 0.6% |
| <= 8 | 23,141,833 | 19.5% |
| <= 16 | 13,548,167 | 11.4% |
| <= 32 | 34,726,572 | 29.2% |
| <= 64 | 12,316,772 | 10.4% |
| <= 128 | 2,733,178 | 2.3% |
| <= 256 | 1,249,156 | 1.1% |
| <= 512 | 134,190 | 0.1% |
| <= 1,024 | 5,303 | 0.0% |
| <= 2,048 | 4,147 | 0.0% |
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
| _SET_IP | 321,422,112 | 14.4% | 14.4% |  |
| _CHECK_VALIDITY | 266,807,388 | 12.0% | 26.4% |  |
| LOAD_FAST | 247,847,769 | 11.1% | 37.6% |  |
| STORE_FAST | 189,767,502 | 8.5% | 46.1% |  |
| _FOR_ITER_TIER_TWO | 71,311,866 | 3.2% | 49.3% | 22.3% |
| _GUARD_GLOBALS_VERSION | 61,844,321 | 2.8% | 52.1% | 0.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 57,351,602 | 2.6% | 54.7% |  |
| _ITER_CHECK_LIST | 50,063,474 | 2.3% | 56.9% | 1.9% |
| _GUARD_NOT_EXHAUSTED_LIST | 49,135,674 | 2.2% | 59.1% | 19.6% |
| _GUARD_IS_FALSE_POP | 42,917,959 | 1.9% | 61.1% | 20.4% |
| CONTAINS_OP | 39,759,986 | 1.8% | 62.8% |  |
| _ITER_NEXT_LIST | 39,511,267 | 1.8% | 64.6% |  |
| _EXIT_TRACE | 38,116,507 | 1.7% | 66.3% |  |
| _JUMP_TO_TOP | 37,475,708 | 1.7% | 68.0% |  |
| _LOAD_GLOBAL_MODULE | 35,527,239 | 1.6% | 69.6% |  |
| _LOAD_ATTR | 29,839,599 | 1.3% | 71.0% |  |
| _GUARD_TYPE_VERSION | 27,136,958 | 1.2% | 72.2% | 21.0% |
| _GUARD_BUILTINS_VERSION | 25,817,205 | 1.2% | 73.3% |  |
| _LOAD_GLOBAL_BUILTINS | 25,817,205 | 1.2% | 74.5% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 24,843,568 | 1.1% | 75.6% | 0.2% |
| _CHECK_PEP_523 | 24,843,568 | 1.1% | 76.7% |  |
| _CHECK_STACK_SPACE | 24,803,980 | 1.1% | 77.8% | 0.0% |
| _INIT_CALL_PY_EXACT_ARGS | 24,801,241 | 1.1% | 79.0% |  |
| _PUSH_FRAME | 24,801,241 | 1.1% | 80.1% |  |
| _SAVE_RETURN_OFFSET | 24,801,241 | 1.1% | 81.2% |  |
| _ITER_CHECK_TUPLE | 23,762,628 | 1.1% | 82.3% | 4.0% |
| LOAD_CONST | 22,970,445 | 1.0% | 83.3% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 22,804,108 | 1.0% | 84.3% | 38.9% |
| LOAD_DEREF | 18,383,992 | 0.8% | 85.1% |  |
| PUSH_NULL | 17,986,267 | 0.8% | 85.9% |  |
| _GUARD_IS_TRUE_POP | 17,815,368 | 0.8% | 86.7% | 28.1% |
| _GUARD_IS_NOT_NONE_POP | 16,859,875 | 0.8% | 87.5% | 89.9% |
| BUILD_TUPLE | 14,724,705 | 0.7% | 88.2% |  |
| _ITER_NEXT_TUPLE | 13,937,700 | 0.6% | 88.8% |  |
| CALL_ISINSTANCE | 13,429,778 | 0.6% | 89.4% |  |
| TO_BOOL_BOOL | 13,297,869 | 0.6% | 90.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 13,211,667 | 0.6% | 90.6% |  |
| _GUARD_KEYS_VERSION | 13,211,667 | 0.6% | 91.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 13,209,807 | 0.6% | 91.8% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 10,734,485 | 0.5% | 92.3% | 7.7% |
| _ITER_CHECK_RANGE | 10,734,485 | 0.5% | 92.7% |  |
| _ITER_NEXT_RANGE | 9,907,086 | 0.4% | 93.2% |  |
| GET_ITER | 9,375,404 | 0.4% | 93.6% |  |
| _GUARD_BOTH_INT | 9,262,526 | 0.4% | 94.0% |  |
| _BINARY_OP_ADD_INT | 9,235,466 | 0.4% | 94.4% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 9,162,223 | 0.4% | 94.9% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 9,162,223 | 0.4% | 95.3% |  |
| _GUARD_IS_NONE_POP | 8,956,694 | 0.4% | 95.7% | 35.2% |
| MAKE_FUNCTION | 8,912,633 | 0.4% | 96.1% |  |
| BINARY_SUBSCR_LIST_INT | 8,199,011 | 0.4% | 96.4% | 0.2% |
| RESUME_CHECK | 7,974,830 | 0.4% | 96.8% |  |
| SET_FUNCTION_ATTRIBUTE | 7,054,200 | 0.3% | 97.1% |  |
| BUILD_MAP | 6,645,671 | 0.3% | 97.4% |  |
| DICT_MERGE | 6,636,008 | 0.3% | 97.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,358,757 | 0.2% | 98.0% | 97.6% |
| _LOAD_ATTR_METHOD_NO_DICT | 5,278,900 | 0.2% | 98.2% |  |
| _BINARY_SUBSCR | 3,790,657 | 0.2% | 98.4% |  |
| LIST_APPEND | 3,631,156 | 0.2% | 98.5% |  |
| _POP_FRAME | 3,164,946 | 0.1% | 98.7% |  |
| COMPARE_OP_INT | 2,515,001 | 0.1% | 98.8% | 0.0% |
| IS_OP | 2,318,014 | 0.1% | 98.9% |  |
| _LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,301,976 | 0.1% | 99.0% |  |
| CALL_BUILTIN_O | 2,215,000 | 0.1% | 99.1% |  |
| SWAP | 2,152,760 | 0.1% | 99.2% |  |
| CALL_TYPE_1 | 1,914,982 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,887,020 | 0.1% | 99.4% |  |
| LOAD_FAST_AND_CLEAR | 1,831,200 | 0.1% | 99.4% |  |
| _COMPARE_OP | 1,736,486 | 0.1% | 99.5% |  |
| POP_TOP | 1,412,020 | 0.1% | 99.6% |  |
| _STORE_SUBSCR | 1,387,460 | 0.1% | 99.6% |  |
| _BINARY_OP | 1,236,172 | 0.1% | 99.7% |  |
| TO_BOOL_INT | 1,192,540 | 0.1% | 99.7% | 0.0% |
| BUILD_LIST | 1,142,420 | 0.1% | 99.8% |  |
| STORE_DEREF | 993,512 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 668,691 | 0.0% | 99.9% |  |
| _LOAD_ATTR_SLOT | 533,769 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST | 439,058 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 297,298 | 0.0% | 99.9% |  |
| COPY | 295,607 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 256,900 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 146,066 | 0.0% | 100.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 112,577 | 0.0% | 100.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 112,577 | 0.0% | 100.0% |  |
| LOAD_NAME | 107,280 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 80,240 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 63,280 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 61,600 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 40,916 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 39,280 | 0.0% | 100.0% |  |
| STORE_NAME | 36,700 | 0.0% | 100.0% |  |
| UNARY_NOT | 33,700 | 0.0% | 100.0% |  |
| _TO_BOOL | 27,802 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,800 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 16,660 | 0.0% | 100.0% |  |
| CALL_LEN | 16,214 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 13,680 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 13,380 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 11,920 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 11,920 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 10,680 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 6,863 | 0.0% | 100.0% |  |
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
| LOAD_ATTR_PROPERTY | 2,995 |
| YIELD_VALUE | 1,120 |
| CALL | 1,013 |
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
Stats gathered on: 2023-11-18
