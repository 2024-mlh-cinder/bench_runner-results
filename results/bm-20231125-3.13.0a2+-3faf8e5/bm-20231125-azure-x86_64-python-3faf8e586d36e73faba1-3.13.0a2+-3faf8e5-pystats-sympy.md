
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
| LOAD_FAST | 976,263,507 | 16.4% | 16.4% |  |
| STORE_FAST | 359,072,109 | 6.0% | 22.5% |  |
| POP_JUMP_IF_FALSE | 291,671,227 | 4.9% | 27.4% |  |
| RESUME_CHECK | 257,773,122 | 4.3% | 31.7% |  |
| LOAD_FAST_LOAD_FAST | 253,677,660 | 4.3% | 36.0% |  |
| LOAD_GLOBAL_BUILTIN | 233,851,775 | 3.9% | 39.9% | 0.0% |
| LOAD_CONST | 191,448,420 | 3.2% | 43.1% |  |
| RETURN_VALUE | 177,424,228 | 3.0% | 46.1% |  |
| TO_BOOL_BOOL | 172,717,118 | 2.9% | 49.0% | 0.1% |
| JUMP_BACKWARD | 156,401,795 | 2.6% | 51.6% |  |
| LOAD_GLOBAL_MODULE | 145,751,871 | 2.5% | 54.1% | 0.0% |
| INTERPRETER_EXIT | 127,220,085 | 2.1% | 56.2% |  |
| LOAD_ATTR | 121,724,381 | 2.0% | 58.3% |  |
| STORE_FAST_STORE_FAST | 105,568,492 | 1.8% | 60.0% |  |
| FOR_ITER | 103,649,922 | 1.7% | 61.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 103,613,914 | 1.7% | 63.5% |  |
| LOAD_ATTR_SLOT | 96,034,190 | 1.6% | 65.1% | 38.1% |
| LOAD_ATTR_METHOD_NO_DICT | 91,689,896 | 1.5% | 66.7% | 10.1% |
| POP_JUMP_IF_TRUE | 80,557,278 | 1.4% | 68.0% |  |
| LOAD_DEREF | 68,502,481 | 1.2% | 69.2% |  |
| CALL_PY_EXACT_ARGS | 68,032,353 | 1.1% | 70.3% | 11.5% |
| CALL_ISINSTANCE | 67,460,242 | 1.1% | 71.5% |  |
| FOR_ITER_LIST | 62,893,999 | 1.1% | 72.5% | 1.2% |
| POP_TOP | 61,421,894 | 1.0% | 73.6% |  |
| PUSH_NULL | 60,712,821 | 1.0% | 74.6% |  |
| GET_ITER | 60,047,567 | 1.0% | 75.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 58,864,974 | 1.0% | 76.6% | 28.9% |
| RETURN_CONST | 57,180,096 | 1.0% | 77.5% |  |
| BUILD_TUPLE | 56,967,555 | 1.0% | 78.5% |  |
| CONTAINS_OP | 52,078,850 | 0.9% | 79.4% |  |
| COMPARE_OP_INT | 51,176,377 | 0.9% | 80.2% | 1.1% |
| IS_OP | 47,605,841 | 0.8% | 81.0% |  |
| SWAP | 45,312,922 | 0.8% | 81.8% |  |
| CALL_BUILTIN_FAST | 43,497,956 | 0.7% | 82.5% |  |
| POP_JUMP_IF_NONE | 41,163,318 | 0.7% | 83.2% |  |
| CALL_BUILTIN_O | 39,876,281 | 0.7% | 83.9% | 6.7% |
| COMPARE_OP | 38,468,023 | 0.6% | 84.5% |  |
| BINARY_OP | 35,328,029 | 0.6% | 85.1% |  |
| FOR_ITER_TUPLE | 34,832,712 | 0.6% | 85.7% | 2.3% |
| BUILD_MAP | 33,797,038 | 0.6% | 86.3% |  |
| NOP | 33,475,351 | 0.6% | 86.9% |  |
| COPY_FREE_VARS | 31,793,276 | 0.5% | 87.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 30,756,445 | 0.5% | 87.9% | 0.4% |
| BINARY_SUBSCR_LIST_INT | 30,200,630 | 0.5% | 88.4% | 0.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,538,305 | 0.5% | 88.9% | 21.9% |
| CALL_LEN | 28,098,723 | 0.5% | 89.4% |  |
| CALL_FUNCTION_EX | 28,013,490 | 0.5% | 89.9% |  |
| LOAD_ATTR_PROPERTY | 28,008,061 | 0.5% | 90.3% | 14.7% |
| CALL | 26,845,002 | 0.5% | 90.8% |  |
| CALL_LIST_APPEND | 24,017,683 | 0.4% | 91.2% |  |
| BINARY_SUBSCR | 23,889,031 | 0.4% | 91.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 23,523,208 | 0.4% | 92.0% | 0.2% |
| DICT_MERGE | 23,272,603 | 0.4% | 92.4% |  |
| YIELD_VALUE | 22,868,597 | 0.4% | 92.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 21,868,371 | 0.4% | 93.1% | 65.1% |
| BUILD_LIST | 21,626,942 | 0.4% | 93.5% |  |
| EXTENDED_ARG | 21,424,287 | 0.4% | 93.8% |  |
| STORE_SUBSCR_LIST_INT | 20,340,872 | 0.3% | 94.2% |  |
| TO_BOOL_INT | 19,696,775 | 0.3% | 94.5% | 0.1% |
| POP_JUMP_IF_NOT_NONE | 18,149,016 | 0.3% | 94.8% |  |
| LOAD_FAST_AND_CLEAR | 16,788,568 | 0.3% | 95.1% |  |
| CALL_TYPE_1 | 16,713,028 | 0.3% | 95.4% |  |
| COMPARE_OP_STR | 14,565,541 | 0.2% | 95.6% |  |
| RETURN_GENERATOR | 14,339,742 | 0.2% | 95.9% |  |
| MAKE_FUNCTION | 14,295,024 | 0.2% | 96.1% |  |
| BINARY_OP_ADD_INT | 12,978,481 | 0.2% | 96.3% |  |
| TO_BOOL | 12,925,714 | 0.2% | 96.5% |  |
| FOR_ITER_RANGE | 12,131,378 | 0.2% | 96.8% |  |
| CALL_KW | 10,673,609 | 0.2% | 96.9% |  |
| SET_FUNCTION_ATTRIBUTE | 10,420,528 | 0.2% | 97.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 9,178,305 | 0.2% | 97.3% | 0.0% |
| CALL_BUILTIN_CLASS | 9,151,011 | 0.2% | 97.4% |  |
| STORE_ATTR_SLOT | 9,061,040 | 0.2% | 97.6% | 24.4% |
| BINARY_SUBSCR_TUPLE_INT | 8,996,339 | 0.2% | 97.7% | 0.1% |
| IMPORT_FROM | 8,955,898 | 0.2% | 97.9% |  |
| STORE_DEREF | 8,695,438 | 0.1% | 98.0% |  |
| MAP_ADD | 7,866,335 | 0.1% | 98.1% |  |
| IMPORT_NAME | 7,760,509 | 0.1% | 98.3% |  |
| LIST_APPEND | 6,188,499 | 0.1% | 98.4% |  |
| MAKE_CELL | 6,049,774 | 0.1% | 98.5% |  |
| JUMP_FORWARD | 5,903,061 | 0.1% | 98.6% |  |
| CALL_TUPLE_1 | 5,851,670 | 0.1% | 98.7% | 0.0% |
| STORE_FAST_LOAD_FAST | 5,345,947 | 0.1% | 98.8% |  |
| UNARY_NOT | 5,307,773 | 0.1% | 98.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,171,876 | 0.1% | 98.9% | 0.1% |
| COPY | 4,908,551 | 0.1% | 99.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 4,647,725 | 0.1% | 99.1% | 0.2% |
| CALL_PY_WITH_DEFAULTS | 4,598,378 | 0.1% | 99.2% | 0.7% |
| STORE_SUBSCR | 3,429,295 | 0.1% | 99.2% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,358,933 | 0.1% | 99.3% | 0.0% |
| BINARY_SUBSCR_DICT | 3,349,311 | 0.1% | 99.4% |  |
| BINARY_OP_MULTIPLY_INT | 2,771,776 | 0.0% | 99.4% | 0.0% |
| TO_BOOL_NONE | 2,709,098 | 0.0% | 99.4% | 8.4% |
| BINARY_OP_SUBTRACT_INT | 2,487,238 | 0.0% | 99.5% |  |
| TO_BOOL_LIST | 2,303,229 | 0.0% | 99.5% | 0.5% |
| STORE_SUBSCR_DICT | 2,283,432 | 0.0% | 99.6% |  |
| LOAD_SUPER_ATTR_METHOD | 1,814,203 | 0.0% | 99.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,648,091 | 0.0% | 99.6% | 20.6% |
| UNPACK_SEQUENCE_TUPLE | 1,631,551 | 0.0% | 99.7% |  |
| LOAD_FAST_CHECK | 1,578,345 | 0.0% | 99.7% |  |
| LIST_EXTEND | 1,349,235 | 0.0% | 99.7% |  |
| CALL_INTRINSIC_1 | 1,349,195 | 0.0% | 99.7% |  |
| DELETE_FAST | 1,302,220 | 0.0% | 99.7% |  |
| LOAD_ATTR_MODULE | 1,272,068 | 0.0% | 99.8% | 0.5% |
| LOAD_SUPER_ATTR_ATTR | 1,182,027 | 0.0% | 99.8% |  |
| SEND_GEN | 1,029,820 | 0.0% | 99.8% | 3.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 928,560 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 906,505 | 0.0% | 99.8% |  |
| POP_EXCEPT | 906,505 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 906,505 | 0.0% | 99.9% |  |
| UNARY_NEGATIVE | 613,416 | 0.0% | 99.9% |  |
| STORE_ATTR | 591,475 | 0.0% | 99.9% |  |
| BINARY_SLICE | 569,088 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 563,580 | 0.0% | 99.9% |  |
| COMPARE_OP_FLOAT | 543,639 | 0.0% | 99.9% | 0.3% |
| GET_YIELD_FROM_ITER | 540,400 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 519,760 | 0.0% | 99.9% |  |
| END_SEND | 519,360 | 0.0% | 99.9% |  |
| SEND | 442,840 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 284,520 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 284,480 | 0.0% | 100.0% |  |
| CALL_STR_1 | 233,240 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 228,646 | 0.0% | 100.0% | 36.3% |
| FOR_ITER_GEN | 191,419 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_CLASS | 187,600 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 182,218 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 180,088 | 0.0% | 100.0% |  |
| LOAD_NAME | 178,820 | 0.0% | 100.0% |  |
| STORE_NAME | 167,980 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 159,246 | 0.0% | 100.0% | 0.0% |
| BUILD_STRING | 141,900 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 129,385 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 119,096 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 95,920 | 0.0% | 100.0% | 0.2% |
| EXIT_INIT_CHECK | 95,600 | 0.0% | 100.0% |  |
| BUILD_SET | 50,447 | 0.0% | 100.0% |  |
| RESUME | 47,629 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 39,855 | 0.0% | 100.0% |  |
| BEFORE_WITH | 37,420 | 0.0% | 100.0% |  |
| END_FOR | 22,550 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 19,500 | 0.0% | 100.0% |  |
| SET_ADD | 19,280 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 5,980 | 0.0% | 100.0% |  |
| BUILD_SLICE | 4,018 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 3,100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 2,660 | 0.0% | 100.0% |  |
| STORE_SLICE | 2,160 | 0.0% | 100.0% |  |
| RERAISE | 2,080 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,209 | 0.0% | 100.0% |  |
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
| STORE_FAST LOAD_FAST | 196,239,281 | 3.3% | 3.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 162,950,647 | 2.7% | 6.0% |
| RESUME_CHECK LOAD_FAST | 115,566,575 | 1.9% | 8.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 113,717,423 | 1.9% | 9.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 111,650,296 | 1.9% | 11.8% |
| CACHE RESUME_CHECK | 98,993,080 | 1.7% | 13.4% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 98,840,680 | 1.7% | 15.1% |
| LOAD_FAST LOAD_ATTR_SLOT | 95,200,807 | 1.6% | 16.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 79,138,187 | 1.3% | 18.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 78,856,537 | 1.3% | 19.4% |
| RETURN_VALUE INTERPRETER_EXIT | 72,903,737 | 1.2% | 20.6% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 70,920,025 | 1.2% | 21.8% |
| LOAD_FAST LOAD_CONST | 69,891,344 | 1.2% | 23.0% |
| JUMP_BACKWARD FOR_ITER | 68,277,714 | 1.1% | 24.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 62,566,172 | 1.1% | 25.2% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 59,845,442 | 1.0% | 26.2% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 58,003,664 | 1.0% | 27.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 57,027,116 | 1.0% | 28.1% |
| LOAD_FAST LOAD_ATTR | 55,274,466 | 0.9% | 29.0% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 54,473,876 | 0.9% | 29.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 54,460,578 | 0.9% | 30.9% |
| LOAD_FAST RETURN_VALUE | 53,599,104 | 0.9% | 31.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 50,918,057 | 0.9% | 32.6% |
| JUMP_BACKWARD FOR_ITER_LIST | 46,568,722 | 0.8% | 33.4% |
| PUSH_NULL LOAD_FAST | 46,543,263 | 0.8% | 34.2% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 45,325,537 | 0.8% | 34.9% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT TO_BOOL_BOOL | 44,303,190 | 0.7% | 35.7% |
| FOR_ITER_LIST STORE_FAST | 43,131,306 | 0.7% | 36.4% |
| STORE_FAST_STORE_FAST LOAD_FAST | 41,986,589 | 0.7% | 37.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 41,291,479 | 0.7% | 37.8% |
| LOAD_CONST LOAD_CONST | 40,447,135 | 0.7% | 38.5% |
| RETURN_VALUE STORE_FAST | 38,560,386 | 0.6% | 39.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 38,019,890 | 0.6% | 39.8% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 37,718,836 | 0.6% | 40.4% |
| LOAD_ATTR STORE_FAST | 36,818,007 | 0.6% | 41.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 35,899,699 | 0.6% | 41.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 35,533,935 | 0.6% | 42.2% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 34,408,889 | 0.6% | 42.8% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 34,003,062 | 0.6% | 43.4% |
| LOAD_ATTR_SLOT RETURN_VALUE | 33,433,085 | 0.6% | 43.9% |
| LOAD_FAST POP_JUMP_IF_NONE | 33,153,170 | 0.6% | 44.5% |
| RETURN_CONST INTERPRETER_EXIT | 32,286,040 | 0.5% | 45.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 31,847,287 | 0.5% | 45.6% |
| IS_OP POP_JUMP_IF_FALSE | 30,050,122 | 0.5% | 46.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 29,779,032 | 0.5% | 46.6% |
| POP_JUMP_IF_FALSE RETURN_CONST | 29,237,026 | 0.5% | 47.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 28,998,019 | 0.5% | 47.6% |
| LOAD_FAST PUSH_NULL | 28,421,465 | 0.5% | 48.0% |
| LOAD_FAST CALL_LEN | 27,057,408 | 0.5% | 48.5% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 26,996,248 | 0.5% | 49.0% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 26,485,384 | 0.4% | 49.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 25,640,111 | 0.4% | 49.8% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 24,634,561 | 0.4% | 50.2% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 24,532,214 | 0.4% | 50.7% |
| LOAD_CONST CALL_BUILTIN_FAST | 24,273,014 | 0.4% | 51.1% |
| BINARY_OP STORE_FAST | 24,217,379 | 0.4% | 51.5% |
| FOR_ITER_TUPLE STORE_FAST | 23,958,086 | 0.4% | 51.9% |
| POP_TOP JUMP_BACKWARD | 23,806,486 | 0.4% | 52.3% |
| DICT_MERGE CALL_FUNCTION_EX | 23,272,603 | 0.4% | 52.7% |
| BUILD_MAP LOAD_FAST | 23,183,420 | 0.4% | 53.1% |
| LOAD_FAST DICT_MERGE | 23,143,697 | 0.4% | 53.4% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 22,702,291 | 0.4% | 53.8% |
| LOAD_ATTR_SLOT STORE_FAST | 22,510,702 | 0.4% | 54.2% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 22,277,496 | 0.4% | 54.6% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_BUILTIN | 22,025,257 | 0.4% | 55.0% |
| YIELD_VALUE INTERPRETER_EXIT | 22,022,568 | 0.4% | 55.3% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 22,003,094 | 0.4% | 55.7% |
| STORE_FAST_STORE_FAST LOAD_DEREF | 21,834,084 | 0.4% | 56.1% |
| COPY_FREE_VARS RESUME_CHECK | 21,817,019 | 0.4% | 56.4% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 21,657,183 | 0.4% | 56.8% |
| LOAD_FAST GET_ITER | 21,634,320 | 0.4% | 57.2% |
| LOAD_FAST TO_BOOL_BOOL | 21,620,234 | 0.4% | 57.5% |
| RESUME_CHECK NOP | 21,365,046 | 0.4% | 57.9% |
| BUILD_TUPLE RETURN_VALUE | 21,222,323 | 0.4% | 58.2% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 21,088,758 | 0.4% | 58.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 21,015,951 | 0.4% | 58.9% |
| LOAD_CONST COMPARE_OP_INT | 20,988,957 | 0.4% | 59.3% |
| POP_JUMP_IF_NONE JUMP_BACKWARD | 20,925,863 | 0.4% | 59.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 20,513,558 | 0.3% | 60.0% |
| LOAD_ATTR CONTAINS_OP | 20,047,803 | 0.3% | 60.3% |
| COMPARE_OP POP_JUMP_IF_FALSE | 20,029,299 | 0.3% | 60.7% |
| GET_ITER FOR_ITER | 19,996,987 | 0.3% | 61.0% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 19,856,868 | 0.3% | 61.3% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 19,466,570 | 0.3% | 61.7% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 19,056,185 | 0.3% | 62.0% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 18,849,579 | 0.3% | 62.3% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 18,814,255 | 0.3% | 62.6% |
| LOAD_FAST TO_BOOL_INT | 18,369,293 | 0.3% | 62.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 18,328,402 | 0.3% | 63.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 18,255,673 | 0.3% | 63.5% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 18,103,901 | 0.3% | 63.8% |
| LOAD_FAST CALL_BUILTIN_O | 17,815,426 | 0.3% | 64.1% |
| CALL_LIST_APPEND JUMP_BACKWARD | 17,344,889 | 0.3% | 64.4% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 17,273,830 | 0.3% | 64.7% |
| LOAD_ATTR IS_OP | 17,248,795 | 0.3% | 65.0% |
| LOAD_FAST BUILD_TUPLE | 17,159,765 | 0.3% | 65.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 16,709,431 | 0.3% | 65.6% |
| LOAD_FAST CALL_TYPE_1 | 16,590,110 | 0.3% | 65.9% |
| LOAD_FAST CALL_LIST_APPEND | 16,421,278 | 0.3% | 66.1% |
| LOAD_ATTR LOAD_FAST | 16,057,623 | 0.3% | 66.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 535,728 | 94.1% |
| LOAD_FAST | 26,720 | 4.7% |
| BINARY_OP_ADD_INT | 6,320 | 1.1% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,652 | 56.2% |
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
| RESUME_CHECK | 98,993,080 | 77.7% |
| POP_TOP | 13,890,756 | 10.9% |
| COPY_FREE_VARS | 13,004,908 | 10.2% |
| MAKE_CELL | 1,509,142 | 1.2% |
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
| LOAD_FAST_LOAD_FAST | 13,969,638 | 58.5% |
| LOAD_DEREF | 6,405,182 | 26.8% |
| BUILD_TUPLE | 1,813,310 | 7.6% |
| LOAD_FAST | 1,313,031 | 5.5% |
| RETURN_VALUE | 152,438 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,898,960 | 28.9% |
| LOAD_FAST | 6,794,435 | 28.4% |
| RETURN_VALUE | 6,067,272 | 25.4% |
| CALL | 907,409 | 3.8% |
| GET_ITER | 906,695 | 3.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 667,597 | 73.6% |
| BUILD_TUPLE | 157,252 | 17.3% |
| LOAD_GLOBAL_MODULE | 79,316 | 8.7% |
| LOAD_FAST | 1,600 | 0.2% |
| LOAD_GLOBAL | 740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 906,345 | 100.0% |
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
| RETURN_CONST | 22,550 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,550 | 100.0% |


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
| LOAD_FAST | 21,634,320 | 36.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,456,936 | 24.1% |
| CALL | 10,953,511 | 18.2% |
| RETURN_VALUE | 4,117,435 | 6.9% |
| CALL_BUILTIN_O | 2,591,146 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 19,996,987 | 33.3% |
| CALL_PY_EXACT_ARGS | 13,010,794 | 21.7% |
| FOR_ITER_TUPLE | 9,975,736 | 16.6% |
| LOAD_FAST_AND_CLEAR | 9,198,516 | 15.3% |
| FOR_ITER_LIST | 4,580,186 | 7.6% |


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
| RETURN_VALUE | 72,903,737 | 57.3% |
| RETURN_CONST | 32,286,040 | 25.4% |
| YIELD_VALUE | 22,022,568 | 17.3% |
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
| LOAD_CONST | 14,295,024 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 10,418,988 | 72.9% |
| LOAD_GLOBAL_BUILTIN | 2,651,218 | 18.5% |
| STORE_FAST | 669,667 | 4.7% |
| LOAD_FAST | 459,349 | 3.2% |
| STORE_NAME | 33,580 | 0.2% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,365,046 | 63.8% |
| POP_JUMP_IF_TRUE | 4,184,002 | 12.5% |
| STORE_FAST | 3,935,203 | 11.8% |
| POP_JUMP_IF_FALSE | 1,913,814 | 5.7% |
| POP_TOP | 1,392,424 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,288,579 | 36.7% |
| LOAD_DEREF | 10,424,275 | 31.1% |
| LOAD_GLOBAL_MODULE | 6,493,624 | 19.4% |
| LOAD_CONST | 2,608,166 | 7.8% |
| LOAD_FAST_LOAD_FAST | 912,908 | 2.7% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 414,670 | 45.7% |
| POP_TOP | 358,415 | 39.5% |
| STORE_FAST | 130,960 | 14.4% |
| COPY | 1,920 | 0.2% |
| STORE_SUBSCR_DICT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 414,670 | 45.7% |
| EXTENDED_ARG | 201,340 | 22.2% |
| JUMP_BACKWARD | 159,475 | 17.6% |
| LOAD_FAST | 83,020 | 9.2% |
| RETURN_CONST | 45,040 | 5.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,901,085 | 24.3% |
| CACHE | 13,890,756 | 22.6% |
| RETURN_CONST | 9,314,968 | 15.2% |
| STORE_FAST | 5,840,382 | 9.5% |
| SWAP | 5,778,623 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 23,806,486 | 38.8% |
| RESUME_CHECK | 14,334,180 | 23.3% |
| LOAD_FAST | 7,249,005 | 11.8% |
| RETURN_VALUE | 5,302,423 | 8.6% |
| LOAD_CONST | 2,641,192 | 4.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 374,597 | 41.3% |
| BINARY_SUBSCR_DICT | 233,820 | 25.8% |
| RAISE_VARARGS | 115,276 | 12.7% |
| LOAD_ATTR | 95,500 | 10.5% |
| CALL_BUILTIN_CLASS | 38,512 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 788,269 | 87.0% |
| LOAD_GLOBAL_MODULE | 114,796 | 12.7% |
| LOAD_GLOBAL | 1,840 | 0.2% |
| LOAD_FAST | 1,600 | 0.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,421,465 | 46.8% |
| LOAD_ATTR | 14,957,097 | 24.6% |
| LOAD_DEREF | 11,929,284 | 19.6% |
| CALL_BUILTIN_FAST | 2,129,900 | 3.5% |
| LOAD_SUPER_ATTR_ATTR | 1,182,027 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,543,263 | 76.7% |
| LOAD_FAST_LOAD_FAST | 12,229,236 | 20.1% |
| LOAD_CONST | 1,723,720 | 2.8% |
| LOAD_DEREF | 128,578 | 0.2% |
| CALL | 35,600 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,895,563 | 69.0% |
| CALL_PY_EXACT_ARGS | 4,261,437 | 29.7% |
| CALL_PY_WITH_DEFAULTS | 163,640 | 1.1% |
| CALL_KW | 8,000 | 0.1% |
| CACHE | 7,740 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,200,216 | 71.1% |
| STORE_FAST | 2,660,412 | 18.6% |
| LOAD_FAST | 792,026 | 5.5% |
| GET_YIELD_FROM_ITER | 347,000 | 2.4% |
| CALL_BUILTIN_CLASS | 160,600 | 1.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,599,104 | 30.2% |
| LOAD_ATTR_SLOT | 33,433,085 | 18.8% |
| BUILD_TUPLE | 21,222,323 | 12.0% |
| RETURN_VALUE | 15,185,210 | 8.6% |
| CALL_BUILTIN_O | 11,432,956 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,903,737 | 41.1% |
| STORE_FAST | 38,560,386 | 21.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 19,466,570 | 11.0% |
| RETURN_VALUE | 15,185,210 | 8.6% |
| LOAD_FAST | 5,453,940 | 3.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,304,117 | 96.3% |
| BINARY_SUBSCR | 93,200 | 2.7% |
| LOAD_FAST_LOAD_FAST | 18,960 | 0.6% |
| SWAP | 5,960 | 0.2% |
| STORE_SUBSCR | 3,640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,291,037 | 96.0% |
| JUMP_BACKWARD | 116,380 | 3.4% |
| JUMP_FORWARD | 9,840 | 0.3% |
| STORE_SUBSCR | 3,640 | 0.1% |
| LOAD_FAST | 2,627 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,287,220 | 79.6% |
| LOAD_FAST | 2,208,370 | 17.1% |
| LOAD_GLOBAL_MODULE | 119,065 | 0.9% |
| LOAD_ATTR | 117,994 | 0.9% |
| RETURN_VALUE | 27,323 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,253,475 | 94.8% |
| POP_JUMP_IF_TRUE | 509,991 | 3.9% |
| UNARY_NOT | 84,250 | 0.7% |
| TO_BOOL_BOOL | 41,235 | 0.3% |
| TO_BOOL | 21,493 | 0.2% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 188,575 | 30.7% |
| LOAD_ATTR_SLOT | 117,478 | 19.2% |
| LOAD_ATTR | 107,040 | 17.4% |
| RETURN_VALUE | 106,160 | 17.3% |
| LOAD_FAST_LOAD_FAST | 50,693 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 131,980 | 21.5% |
| CALL_LIST_APPEND | 119,120 | 19.4% |
| LOAD_GLOBAL_MODULE | 106,844 | 17.4% |
| IS_OP | 106,160 | 17.3% |
| STORE_FAST | 58,071 | 9.5% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,442,713 | 64.9% |
| TO_BOOL_BOOL | 1,118,751 | 21.1% |
| TO_BOOL_LIST | 661,888 | 12.5% |
| TO_BOOL | 84,250 | 1.6% |
| TO_BOOL_INT | 171 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,529,504 | 66.5% |
| STORE_FAST | 882,778 | 16.6% |
| BUILD_MAP | 734,720 | 13.8% |
| COPY | 87,021 | 1.6% |
| LOAD_CONST | 68,090 | 1.3% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,767,202 | 33.3% |
| COMPARE_OP_INT | 6,308,780 | 17.9% |
| COMPARE_OP | 6,162,400 | 17.4% |
| CALL_TUPLE_1 | 4,707,301 | 13.3% |
| LOAD_FAST | 2,678,729 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,217,379 | 68.6% |
| RETURN_VALUE | 5,771,312 | 16.3% |
| BUILD_TUPLE | 1,556,880 | 4.4% |
| CALL_BUILTIN_O | 1,095,147 | 3.1% |
| LOAD_FAST | 857,948 | 2.4% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 129,385 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 126,605 | 97.9% |
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
| SWAP | 4,464,315 | 20.6% |
| POP_JUMP_IF_TRUE | 4,083,249 | 18.9% |
| STORE_FAST | 3,817,212 | 17.7% |
| LOAD_FAST | 2,312,163 | 10.7% |
| BINARY_SUBSCR_TUPLE_INT | 1,557,600 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,719,136 | 54.2% |
| SWAP | 4,464,315 | 20.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,294,408 | 10.6% |
| LOAD_FAST | 1,414,495 | 6.5% |
| BUILD_LIST | 748,353 | 3.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,167,865 | 36.0% |
| BUILD_TUPLE | 10,998,594 | 32.5% |
| SWAP | 4,716,201 | 14.0% |
| LOAD_CONST | 1,656,800 | 4.9% |
| RESUME_CHECK | 1,285,960 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,183,420 | 68.6% |
| SWAP | 4,716,201 | 14.0% |
| STORE_FAST | 3,331,895 | 9.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,561,360 | 4.6% |
| CALL_FUNCTION_EX | 734,880 | 2.2% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,367 | 64.2% |
| SWAP | 18,000 | 35.7% |
| BINARY_OP | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 32,367 | 64.2% |
| SWAP | 18,000 | 35.7% |
| STORE_FAST | 80 | 0.2% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,018 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 3,840 | 95.6% |
| BINARY_SUBSCR | 178 | 4.4% |


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
| LOAD_FAST_LOAD_FAST | 25,640,111 | 45.0% |
| LOAD_FAST | 17,159,765 | 30.1% |
| LOAD_ATTR_SLOT | 5,042,240 | 8.9% |
| LOAD_ATTR | 3,034,791 | 5.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 2,484,120 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,222,323 | 37.3% |
| BUILD_MAP | 10,998,594 | 19.3% |
| LOAD_CONST | 10,441,934 | 18.3% |
| LOAD_GLOBAL_BUILTIN | 4,707,101 | 8.3% |
| CALL_LIST_APPEND | 3,231,440 | 5.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,643,333 | 35.9% |
| LOAD_FAST | 7,324,595 | 27.3% |
| LOAD_ATTR | 3,067,189 | 11.4% |
| BINARY_OP_MULTIPLY_INT | 2,291,869 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,952 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,953,511 | 40.8% |
| STORE_FAST | 5,845,108 | 21.8% |
| RETURN_VALUE | 4,523,636 | 16.9% |
| POP_TOP | 1,130,291 | 4.2% |
| RESUME_CHECK | 1,066,495 | 4.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 23,272,603 | 83.1% |
| LOAD_FAST | 2,317,605 | 8.3% |
| CALL_INTRINSIC_1 | 1,256,853 | 4.5% |
| BUILD_MAP | 734,880 | 2.6% |
| BINARY_OP | 201,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,601,051 | 45.0% |
| RESUME_CHECK | 11,673,608 | 41.7% |
| LOAD_FAST_LOAD_FAST | 1,561,000 | 5.6% |
| BUILD_TUPLE | 638,892 | 2.3% |
| SWAP | 480,160 | 1.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,347,975 | 99.9% |
| IMPORT_NAME | 1,060 | 0.1% |
| LIST_APPEND | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,256,853 | 93.2% |
| BUILD_MAP | 91,282 | 6.8% |
| POP_TOP | 1,060 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,673,609 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,493,590 | 88.9% |
| POP_TOP | 698,064 | 6.5% |
| COPY_FREE_VARS | 261,140 | 2.4% |
| RETURN_VALUE | 84,829 | 0.8% |
| STORE_FAST | 35,740 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,088,758 | 54.8% |
| LOAD_FAST | 8,190,379 | 21.3% |
| CALL_TYPE_1 | 5,882,604 | 15.3% |
| LOAD_GLOBAL_MODULE | 1,180,883 | 3.1% |
| LOAD_CONST | 950,802 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20,029,299 | 52.1% |
| BINARY_OP | 6,162,400 | 16.0% |
| LOAD_FAST_LOAD_FAST | 6,162,320 | 16.0% |
| UNARY_NOT | 3,442,713 | 8.9% |
| POP_JUMP_IF_TRUE | 2,279,000 | 5.9% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 24,634,561 | 47.3% |
| LOAD_ATTR | 20,047,803 | 38.5% |
| LOAD_GLOBAL_MODULE | 5,290,390 | 10.2% |
| LOAD_DEREF | 1,536,480 | 3.0% |
| LOAD_CONST | 175,027 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 45,325,537 | 87.0% |
| POP_JUMP_IF_TRUE | 6,743,153 | 12.9% |
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
| LOAD_FAST | 1,237,562 | 25.2% |
| COPY | 1,214,400 | 24.7% |
| LOAD_FAST_LOAD_FAST | 872,880 | 17.8% |
| CALL_ISINSTANCE | 525,020 | 10.7% |
| LOAD_CONST | 236,777 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,340,112 | 27.3% |
| COPY | 1,214,400 | 24.7% |
| BINARY_SUBSCR_LIST_INT | 1,208,120 | 24.6% |
| LOAD_ATTR_INSTANCE_VALUE | 956,400 | 19.5% |
| STORE_FAST_STORE_FAST | 55,577 | 1.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 13,004,908 | 40.9% |
| CALL_PY_EXACT_ARGS | 11,878,667 | 37.4% |
| LOAD_ATTR_PROPERTY | 5,061,531 | 15.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,202,760 | 3.8% |
| CALL_KW | 261,140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,817,019 | 68.6% |
| RETURN_GENERATOR | 9,895,563 | 31.1% |
| MAKE_CELL | 78,500 | 0.2% |
| RESUME | 2,194 | 0.0% |


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
| LOAD_FAST | 23,143,697 | 99.4% |
| LOAD_DEREF | 128,906 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 23,272,603 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,678,939 | 26.5% |
| TO_BOOL_BOOL | 5,486,213 | 25.6% |
| CALL_LIST_APPEND | 4,571,171 | 21.3% |
| GET_ITER | 2,378,164 | 11.1% |
| COMPARE_OP_INT | 1,719,905 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,038,676 | 32.9% |
| JUMP_BACKWARD | 5,792,759 | 27.0% |
| FOR_ITER_LIST | 5,660,765 | 26.4% |
| FOR_ITER_TUPLE | 1,740,040 | 8.1% |
| FOR_ITER_RANGE | 642,400 | 3.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 68,277,714 | 65.9% |
| GET_ITER | 19,996,987 | 19.3% |
| SWAP | 7,638,649 | 7.4% |
| LOAD_FAST | 7,625,644 | 7.4% |
| FOR_ITER | 79,635 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 70,920,025 | 68.4% |
| STORE_FAST | 8,351,584 | 8.1% |
| SWAP | 7,602,861 | 7.3% |
| RETURN_CONST | 4,699,973 | 4.5% |
| LOAD_FAST | 4,689,691 | 4.5% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 7,758,989 | 86.6% |
| STORE_FAST | 982,664 | 11.0% |
| STORE_DEREF | 185,705 | 2.1% |
| STORE_NAME | 26,000 | 0.3% |
| EXTENDED_ARG | 2,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,822,833 | 76.2% |
| STORE_DEREF | 2,092,465 | 23.4% |
| STORE_NAME | 38,060 | 0.4% |
| EXTENDED_ARG | 2,540 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,760,489 | 100.0% |
| EXTENDED_ARG | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 7,758,989 | 100.0% |
| CALL_INTRINSIC_1 | 1,060 | 0.0% |
| STORE_NAME | 440 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 17,248,795 | 36.2% |
| LOAD_FAST | 12,619,877 | 26.5% |
| LOAD_CONST | 10,977,077 | 23.1% |
| LOAD_FAST_LOAD_FAST | 5,893,588 | 12.4% |
| LOAD_GLOBAL_BUILTIN | 539,791 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,050,122 | 63.1% |
| YIELD_VALUE | 12,604,539 | 26.5% |
| POP_JUMP_IF_TRUE | 4,906,991 | 10.3% |
| EXTENDED_ARG | 27,180 | 0.1% |
| STORE_FAST | 8,960 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,408,889 | 22.0% |
| POP_TOP | 23,806,486 | 15.2% |
| POP_JUMP_IF_TRUE | 22,702,291 | 14.5% |
| POP_JUMP_IF_NONE | 20,925,863 | 13.4% |
| CALL_LIST_APPEND | 17,344,889 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 68,277,714 | 43.7% |
| FOR_ITER_LIST | 46,568,722 | 29.8% |
| FOR_ITER_TUPLE | 22,277,496 | 14.2% |
| FOR_ITER_RANGE | 10,609,802 | 6.8% |
| EXTENDED_ARG | 5,678,939 | 3.6% |


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
| STORE_FAST | 4,278,901 | 72.5% |
| POP_TOP | 734,246 | 12.4% |
| STORE_FAST_STORE_FAST | 240,720 | 4.1% |
| CALL_LIST_APPEND | 191,890 | 3.3% |
| LOAD_FAST | 147,005 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,006,150 | 67.9% |
| BUILD_MAP | 642,560 | 10.9% |
| LOAD_GLOBAL_BUILTIN | 470,047 | 8.0% |
| LOAD_FAST_LOAD_FAST | 437,285 | 7.4% |
| STORE_FAST | 119,105 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,004,226 | 48.5% |
| BUILD_TUPLE | 1,568,831 | 25.4% |
| RETURN_VALUE | 511,460 | 8.3% |
| BINARY_SUBSCR | 489,438 | 7.9% |
| BINARY_SUBSCR_LIST_INT | 396,080 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,183,539 | 99.9% |
| LOAD_NAME | 4,800 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,347,095 | 99.8% |
| LOAD_CONST | 1,260 | 0.1% |
| LOAD_DEREF | 640 | 0.0% |
| LOAD_ATTR_SLOT | 200 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,347,975 | 99.9% |
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
| LOAD_GLOBAL_MODULE | 57,027,116 | 46.8% |
| LOAD_FAST | 55,274,466 | 45.4% |
| CALL_TYPE_1 | 4,209,375 | 3.5% |
| LOAD_ATTR_SLOT | 2,297,068 | 1.9% |
| LOAD_GLOBAL_BUILTIN | 1,905,343 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,818,007 | 30.2% |
| CONTAINS_OP | 20,047,803 | 16.5% |
| IS_OP | 17,248,795 | 14.2% |
| LOAD_FAST | 16,057,623 | 13.2% |
| PUSH_NULL | 14,957,097 | 12.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 69,891,344 | 36.5% |
| LOAD_CONST | 40,447,135 | 21.1% |
| RESUME_CHECK | 15,735,089 | 8.2% |
| BUILD_TUPLE | 10,441,934 | 5.5% |
| RETURN_CONST | 9,526,680 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,447,135 | 21.1% |
| CALL_BUILTIN_FAST | 24,273,014 | 12.7% |
| COMPARE_OP_INT | 20,988,957 | 11.0% |
| STORE_FAST | 14,709,292 | 7.7% |
| MAKE_FUNCTION | 14,295,024 | 7.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 21,834,084 | 31.9% |
| NOP | 10,424,275 | 15.2% |
| LOAD_FAST | 7,794,300 | 11.4% |
| LOAD_ATTR_SLOT | 6,405,182 | 9.4% |
| POP_JUMP_IF_FALSE | 4,653,485 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 22,003,094 | 32.1% |
| PUSH_NULL | 11,929,284 | 17.4% |
| LOAD_FAST | 9,406,497 | 13.7% |
| CALL_ISINSTANCE | 7,549,381 | 11.0% |
| BINARY_SUBSCR | 6,405,182 | 9.4% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 196,239,281 | 20.1% |
| LOAD_GLOBAL_BUILTIN | 162,950,647 | 16.7% |
| RESUME_CHECK | 115,566,575 | 11.8% |
| POP_JUMP_IF_FALSE | 113,717,423 | 11.6% |
| PUSH_NULL | 46,543,263 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 95,200,807 | 9.8% |
| LOAD_ATTR_METHOD_NO_DICT | 79,138,187 | 8.1% |
| LOAD_GLOBAL_MODULE | 78,856,537 | 8.1% |
| LOAD_CONST | 69,891,344 | 7.2% |
| LOAD_ATTR | 55,274,466 | 5.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,198,516 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,972 | 45.2% |
| MAKE_CELL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,198,436 | 54.8% |
| LOAD_FAST_AND_CLEAR | 7,589,972 | 45.2% |
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
| STORE_FAST | 62,566,172 | 24.7% |
| POP_JUMP_IF_FALSE | 34,003,062 | 13.4% |
| LOAD_GLOBAL_BUILTIN | 28,998,019 | 11.4% |
| RESUME_CHECK | 19,856,868 | 7.8% |
| STORE_FAST_STORE_FAST | 15,653,224 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 26,996,248 | 10.6% |
| BUILD_TUPLE | 25,640,111 | 10.1% |
| CONTAINS_OP | 24,634,561 | 9.7% |
| COMPARE_OP | 21,088,758 | 8.3% |
| STORE_SUBSCR_LIST_INT | 18,849,579 | 7.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,337 | 19.4% |
| LOAD_FAST | 34,262 | 18.8% |
| STORE_FAST | 26,993 | 14.8% |
| RESUME_CHECK | 10,945 | 6.0% |
| RESUME | 10,811 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 50,646 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 41,280 | 22.7% |
| LOAD_FAST | 39,697 | 21.8% |
| LOAD_ATTR | 14,104 | 7.7% |
| CALL | 9,843 | 5.4% |


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
| LOAD_FAST | 1,089 | 90.1% |
| LOAD_DEREF | 120 | 9.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 500 | 41.4% |
| CALL | 329 | 27.2% |
| LOAD_FAST | 180 | 14.9% |
| PUSH_NULL | 100 | 8.3% |
| LOAD_SUPER_ATTR_ATTR | 100 | 8.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,274,868 | 37.6% |
| CACHE | 1,509,142 | 24.9% |
| CALL_PY_EXACT_ARGS | 772,962 | 12.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 654,430 | 10.8% |
| CALL | 523,701 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,771,346 | 62.3% |
| MAKE_CELL | 2,274,868 | 37.6% |
| RESUME | 3,000 | 0.0% |
| RETURN_GENERATOR | 400 | 0.0% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,853,175 | 99.8% |
| LOAD_FAST | 4,160 | 0.1% |
| RETURN_VALUE | 3,620 | 0.0% |
| CALL | 1,920 | 0.0% |
| STORE_FAST | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,865,995 | 100.0% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_NAME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 111,650,296 | 38.3% |
| CONTAINS_OP | 45,325,537 | 15.5% |
| COMPARE_OP_INT | 35,533,935 | 12.2% |
| IS_OP | 30,050,122 | 10.3% |
| COMPARE_OP | 20,029,299 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 113,717,423 | 39.0% |
| LOAD_GLOBAL_BUILTIN | 58,003,664 | 19.9% |
| JUMP_BACKWARD | 34,408,889 | 11.8% |
| LOAD_FAST_LOAD_FAST | 34,003,062 | 11.7% |
| RETURN_CONST | 29,237,026 | 10.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,153,170 | 80.5% |
| BINARY_SUBSCR | 6,898,960 | 16.8% |
| LOAD_DEREF | 1,088,863 | 2.6% |
| LOAD_ATTR_INSTANCE_VALUE | 8,380 | 0.0% |
| EXTENDED_ARG | 6,805 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,925,863 | 50.8% |
| LOAD_FAST_LOAD_FAST | 14,759,235 | 35.9% |
| LOAD_FAST | 2,616,657 | 6.4% |
| LOAD_GLOBAL_BUILTIN | 1,438,369 | 3.5% |
| LOAD_CONST | 1,111,433 | 2.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,709,431 | 92.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,225,045 | 6.7% |
| EXTENDED_ARG | 179,780 | 1.0% |
| CALL_BUILTIN_FAST | 11,040 | 0.1% |
| LOAD_DEREF | 8,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,237,666 | 67.4% |
| LOAD_FAST_LOAD_FAST | 2,021,642 | 11.1% |
| LOAD_GLOBAL_MODULE | 1,880,615 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 1,385,830 | 7.6% |
| JUMP_BACKWARD | 503,827 | 2.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 54,460,578 | 67.6% |
| TO_BOOL_INT | 9,138,682 | 11.3% |
| CONTAINS_OP | 6,743,153 | 8.4% |
| IS_OP | 4,906,991 | 6.1% |
| COMPARE_OP | 2,279,000 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,019,890 | 47.2% |
| JUMP_BACKWARD | 22,702,291 | 28.2% |
| LOAD_GLOBAL_BUILTIN | 5,308,948 | 6.6% |
| NOP | 4,184,002 | 5.2% |
| BUILD_LIST | 4,083,249 | 5.1% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,936 | 99.9% |
| CALL_KW | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 115,276 | 98.4% |
| COPY | 1,760 | 1.5% |
| LOAD_CONST | 160 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,237,026 | 51.1% |
| RESUME_CHECK | 10,045,730 | 17.6% |
| FOR_ITER_LIST | 5,671,849 | 9.9% |
| FOR_ITER | 4,699,973 | 8.2% |
| STORE_SUBSCR | 3,291,037 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,286,040 | 56.5% |
| LOAD_CONST | 9,526,680 | 16.7% |
| POP_TOP | 9,314,968 | 16.3% |
| TO_BOOL_BOOL | 3,464,277 | 6.1% |
| STORE_FAST | 1,541,260 | 2.7% |


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
| MAKE_FUNCTION | 10,418,988 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,822,803 | 94.3% |
| STORE_FAST | 307,031 | 2.9% |
| STORE_DEREF | 113,245 | 1.1% |
| LOAD_CONST | 52,360 | 0.5% |
| LOAD_GLOBAL_MODULE | 42,960 | 0.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 486,904 | 82.3% |
| LOAD_FAST | 98,460 | 16.6% |
| STORE_ATTR | 3,914 | 0.7% |
| SWAP | 2,169 | 0.4% |
| LOAD_DEREF | 28 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 289,708 | 49.0% |
| LOAD_FAST_LOAD_FAST | 116,276 | 19.7% |
| LOAD_FAST | 90,003 | 15.2% |
| LOAD_GLOBAL_BUILTIN | 74,060 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 3,960 | 0.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 4,491,620 | 51.7% |
| IMPORT_FROM | 2,092,465 | 24.1% |
| LOAD_ATTR | 1,558,848 | 17.9% |
| STORE_FAST | 240,860 | 2.8% |
| SET_FUNCTION_ATTRIBUTE | 113,245 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,491,580 | 51.7% |
| POP_TOP | 1,906,760 | 21.9% |
| LOAD_DEREF | 1,298,353 | 14.9% |
| LOAD_GLOBAL_MODULE | 481,480 | 5.5% |
| IMPORT_FROM | 185,705 | 2.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 43,131,306 | 12.0% |
| RETURN_VALUE | 38,560,386 | 10.7% |
| LOAD_ATTR | 36,818,007 | 10.3% |
| BINARY_OP | 24,217,379 | 6.7% |
| FOR_ITER_TUPLE | 23,958,086 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 196,239,281 | 54.7% |
| LOAD_FAST_LOAD_FAST | 62,566,172 | 17.4% |
| LOAD_GLOBAL_BUILTIN | 37,718,836 | 10.5% |
| LOAD_GLOBAL_MODULE | 18,255,673 | 5.1% |
| STORE_FAST | 9,345,273 | 2.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 4,156,292 | 77.7% |
| FOR_ITER_TUPLE | 596,693 | 11.2% |
| FOR_ITER_RANGE | 500,000 | 9.4% |
| FOR_ITER | 92,962 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,303,786 | 80.5% |
| LOAD_ATTR_PROPERTY | 318,633 | 6.0% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 238,651 | 4.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 157,680 | 2.9% |
| LOAD_DEREF | 107,360 | 2.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 98,840,680 | 93.6% |
| RETURN_VALUE | 3,248,217 | 3.1% |
| UNPACK_SEQUENCE_TUPLE | 1,436,795 | 1.4% |
| STORE_FAST_STORE_FAST | 772,033 | 0.7% |
| BUILD_LIST | 413,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,986,589 | 39.8% |
| LOAD_GLOBAL_BUILTIN | 22,025,257 | 20.9% |
| LOAD_DEREF | 21,834,084 | 20.7% |
| LOAD_FAST_LOAD_FAST | 15,653,224 | 14.8% |
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
| BINARY_SUBSCR_LIST_INT | 9,396,317 | 20.7% |
| LOAD_FAST_AND_CLEAR | 9,198,436 | 20.3% |
| FOR_ITER | 7,602,861 | 16.8% |
| BUILD_MAP | 4,716,201 | 10.4% |
| LOAD_FAST | 4,641,443 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,396,537 | 20.7% |
| STORE_FAST | 7,931,131 | 17.5% |
| FOR_ITER | 7,638,649 | 16.9% |
| POP_TOP | 5,778,623 | 12.8% |
| BUILD_MAP | 4,716,201 | 10.4% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,494 | 26.3% |
| FOR_ITER | 6,807 | 17.1% |
| CALL_BUILTIN_CLASS | 6,340 | 15.9% |
| LOAD_FAST | 4,002 | 10.0% |
| CALL_BUILTIN_FAST | 3,260 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,717 | 47.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,440 | 23.7% |
| STORE_FAST | 8,138 | 20.4% |
| UNPACK_SEQUENCE_TUPLE | 1,164 | 2.9% |
| UNPACK_SEQUENCE | 916 | 2.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,604,539 | 55.1% |
| CALL_ISINSTANCE | 6,945,910 | 30.4% |
| LOAD_FAST | 1,146,846 | 5.0% |
| YIELD_VALUE | 677,480 | 3.0% |
| RETURN_VALUE | 423,528 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 22,022,568 | 96.3% |
| YIELD_VALUE | 677,480 | 3.0% |
| STORE_FAST | 162,909 | 0.7% |
| UNPACK_SEQUENCE | 3,120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,520 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,057 | 37.9% |
| CALL | 11,144 | 23.4% |
| CALL_PY_EXACT_ARGS | 6,112 | 12.8% |
| POP_TOP | 3,962 | 8.3% |
| MAKE_CELL | 3,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,717 | 37.2% |
| LOAD_GLOBAL | 10,811 | 22.7% |
| LOAD_CONST | 8,766 | 18.4% |
| LOAD_NAME | 3,700 | 7.8% |
| POP_TOP | 3,362 | 7.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,827,060 | 91.1% |
| LOAD_FAST_LOAD_FAST | 574,261 | 4.4% |
| BINARY_SUBSCR_DICT | 422,960 | 3.3% |
| CALL_BUILTIN_CLASS | 81,225 | 0.6% |
| LOAD_FAST | 43,684 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 9,394,437 | 72.4% |
| STORE_FAST | 1,576,749 | 12.1% |
| SWAP | 1,085,069 | 8.4% |
| LOAD_CONST | 269,164 | 2.1% |
| LOAD_FAST | 201,662 | 1.6% |


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
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,668,679 | 60.2% |
| LOAD_ATTR_SLOT | 723,525 | 26.1% |
| LOAD_FAST_LOAD_FAST | 283,553 | 10.2% |
| LOAD_FAST | 94,345 | 3.4% |
| BINARY_OP | 1,531 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,291,869 | 82.7% |
| LOAD_FAST_LOAD_FAST | 181,174 | 6.5% |
| STORE_FAST | 175,663 | 6.3% |
| LOAD_FAST | 90,194 | 3.3% |
| LOAD_GLOBAL_MODULE | 25,205 | 0.9% |


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
| LOAD_CONST | 1,569,196 | 63.1% |
| LOAD_FAST_LOAD_FAST | 607,499 | 24.4% |
| BINARY_SUBSCR_LIST_INT | 181,120 | 7.3% |
| LOAD_FAST | 123,235 | 5.0% |
| BINARY_OP | 2,215 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,082,420 | 43.5% |
| STORE_FAST | 710,799 | 28.6% |
| BINARY_OP | 311,707 | 12.5% |
| COMPARE_OP_INT | 184,120 | 7.4% |
| BINARY_SUBSCR_LIST_INT | 54,440 | 2.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,215,371 | 36.3% |
| LOAD_FAST_LOAD_FAST | 925,917 | 27.6% |
| LOAD_CONST | 642,800 | 19.2% |
| CALL_TUPLE_1 | 443,840 | 13.3% |
| RETURN_VALUE | 114,531 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 884,757 | 26.4% |
| RETURN_VALUE | 809,350 | 24.2% |
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
| LOAD_CONST | 14,546 | 9.1% |
| BUILD_SLICE | 3,840 | 2.4% |
| BINARY_SUBSCR | 700 | 0.4% |

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
| LOAD_FAST_LOAD_FAST | 26,996,248 | 89.4% |
| COPY | 1,208,120 | 4.0% |
| LOAD_CONST | 1,026,732 | 3.4% |
| LOAD_FAST | 570,303 | 1.9% |
| CALL_BUILTIN_CLASS | 282,687 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,459,017 | 31.3% |
| SWAP | 9,396,317 | 31.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 7,540,554 | 25.0% |
| LOAD_CONST | 1,208,580 | 4.0% |
| STORE_FAST | 517,607 | 1.7% |


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
| LOAD_CONST | 8,729,699 | 97.0% |
| LOAD_FAST | 263,343 | 2.9% |
| BINARY_SUBSCR | 2,757 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,738,690 | 52.7% |
| CALL_LIST_APPEND | 1,762,920 | 19.6% |
| BUILD_LIST | 1,557,600 | 17.3% |
| LOAD_FAST | 322,132 | 3.6% |
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
| LOAD_FAST | 13,334,568 | 56.7% |
| BINARY_OP_ADD_INT | 9,394,437 | 39.9% |
| LOAD_FAST_LOAD_FAST | 480,488 | 2.0% |
| LOAD_ATTR | 152,040 | 0.6% |
| LOAD_DEREF | 83,580 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,657,183 | 92.1% |
| COPY_FREE_VARS | 1,202,760 | 5.1% |
| MAKE_CELL | 654,430 | 2.8% |
| POP_TOP | 7,360 | 0.0% |
| CALL_PY_EXACT_ARGS | 715 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,822,396 | 30.8% |
| CALL_BUILTIN_CLASS | 1,959,379 | 21.4% |
| LOAD_GLOBAL_BUILTIN | 922,326 | 10.1% |
| LOAD_CONST | 710,920 | 7.8% |
| CALL_LEN | 611,071 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,420,609 | 37.4% |
| CALL_BUILTIN_CLASS | 1,959,379 | 21.4% |
| GET_ITER | 1,868,852 | 20.4% |
| CALL | 284,492 | 3.1% |
| BINARY_SUBSCR_LIST_INT | 282,687 | 3.1% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,273,014 | 55.8% |
| LOAD_FAST_LOAD_FAST | 17,273,830 | 39.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,337,284 | 3.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 478,200 | 1.1% |
| LOAD_FAST | 64,266 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,103,901 | 41.8% |
| STORE_FAST | 11,047,524 | 25.5% |
| TO_BOOL | 10,287,220 | 23.8% |
| PUSH_NULL | 2,129,900 | 4.9% |
| RETURN_VALUE | 1,500,221 | 3.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,880,821 | 94.4% |
| LOAD_FAST | 135,130 | 2.6% |
| BINARY_OP | 119,165 | 2.3% |
| RETURN_GENERATOR | 27,800 | 0.5% |
| LOAD_CONST | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 4,707,101 | 91.0% |
| GET_ITER | 173,780 | 3.4% |
| STORE_FAST | 128,030 | 2.5% |
| CALL_BUILTIN_CLASS | 119,165 | 2.3% |
| RETURN_VALUE | 34,520 | 0.7% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,815,426 | 44.7% |
| RETURN_GENERATOR | 10,200,216 | 25.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 5,614,833 | 14.1% |
| LOAD_ATTR_SLOT | 4,877,814 | 12.2% |
| BINARY_OP | 1,095,147 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,694,178 | 39.4% |
| RETURN_VALUE | 11,432,956 | 28.7% |
| TO_BOOL_BOOL | 9,902,150 | 24.8% |
| GET_ITER | 2,591,146 | 6.5% |
| LOAD_FAST | 50,620 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,899,699 | 53.2% |
| LOAD_GLOBAL_BUILTIN | 19,056,185 | 28.2% |
| LOAD_DEREF | 7,549,381 | 11.2% |
| LOAD_FAST_LOAD_FAST | 2,883,804 | 4.3% |
| LOAD_FAST | 1,621,128 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 59,845,442 | 88.7% |
| YIELD_VALUE | 6,945,910 | 10.3% |
| COPY | 525,020 | 0.8% |
| RETURN_VALUE | 127,538 | 0.2% |
| TO_BOOL | 9,666 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,057,408 | 96.3% |
| LOAD_GLOBAL_MODULE | 553,240 | 2.0% |
| BINARY_SUBSCR | 185,800 | 0.7% |
| RETURN_VALUE | 95,118 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 93,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 10,271,124 | 36.6% |
| LOAD_GLOBAL_BUILTIN | 9,676,821 | 34.4% |
| LOAD_CONST | 7,191,416 | 25.6% |
| CALL_BUILTIN_CLASS | 611,071 | 2.2% |
| STORE_FAST | 84,420 | 0.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,421,278 | 68.4% |
| BUILD_TUPLE | 3,231,440 | 13.5% |
| BINARY_SUBSCR_TUPLE_INT | 1,762,920 | 7.3% |
| LOAD_FAST_CHECK | 1,556,980 | 6.5% |
| CALL | 693,145 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 17,344,889 | 72.2% |
| EXTENDED_ARG | 4,571,171 | 19.0% |
| LOAD_FAST | 1,681,753 | 7.0% |
| LOAD_FAST_LOAD_FAST | 207,500 | 0.9% |
| JUMP_FORWARD | 191,890 | 0.8% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,965,770 | 68.4% |
| LOAD_CONST | 2,390,987 | 10.9% |
| BUILD_LIST | 2,294,408 | 10.5% |
| BUILD_MAP | 1,561,360 | 7.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 268,427 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,652,617 | 57.9% |
| STORE_FAST | 3,453,994 | 15.8% |
| LOAD_ATTR_METHOD_NO_DICT | 3,116,160 | 14.2% |
| POP_TOP | 908,846 | 4.2% |
| GET_ITER | 737,608 | 3.4% |


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
| LOAD_ATTR_METHOD_NO_DICT | 24,532,214 | 83.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,807,661 | 16.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,790 | 0.4% |
| LOAD_ATTR | 72,820 | 0.2% |
| CALL | 3,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,456,936 | 48.9% |
| STORE_FAST | 9,688,880 | 32.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,880,821 | 16.5% |
| CALL_BUILTIN_CLASS | 169,829 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 121,790 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,853,920 | 61.4% |
| LOAD_CONST | 1,226,545 | 26.4% |
| LOAD_FAST | 353,960 | 7.6% |
| RETURN_VALUE | 97,600 | 2.1% |
| BUILD_LIST | 44,300 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,235,540 | 69.6% |
| LOAD_CONST | 1,224,545 | 26.3% |
| TO_BOOL_NONE | 104,000 | 2.2% |
| BINARY_OP_ADD_UNICODE | 39,600 | 0.9% |
| STORE_FAST | 25,520 | 0.5% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 21,015,951 | 30.9% |
| LOAD_FAST | 15,740,306 | 23.1% |
| LOAD_FAST_LOAD_FAST | 13,674,857 | 20.1% |
| GET_ITER | 13,010,794 | 19.1% |
| LOAD_SUPER_ATTR_METHOD | 1,539,431 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 50,918,057 | 74.8% |
| COPY_FREE_VARS | 11,878,667 | 17.5% |
| RETURN_GENERATOR | 4,261,437 | 6.3% |
| MAKE_CELL | 772,962 | 1.1% |
| CALL_PY_EXACT_ARGS | 144,889 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,105,041 | 45.8% |
| LOAD_FAST | 1,865,920 | 40.6% |
| RETURN_VALUE | 192,685 | 4.2% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 158,010 | 3.4% |
| LOAD_CONST | 80,565 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,380,376 | 95.3% |
| RETURN_GENERATOR | 163,640 | 3.6% |
| MAKE_CELL | 53,738 | 1.2% |
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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 4,707,101 | 80.4% |
| LOAD_FAST | 1,017,565 | 17.4% |
| STORE_FAST | 105,752 | 1.8% |
| RETURN_VALUE | 7,920 | 0.1% |
| LOAD_DEREF | 4,132 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,707,301 | 80.4% |
| BINARY_SUBSCR_DICT | 443,840 | 7.6% |
| STORE_FAST | 353,192 | 6.0% |
| STORE_SUBSCR_DICT | 181,360 | 3.1% |
| RETURN_VALUE | 56,520 | 1.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,590,110 | 99.3% |
| LOAD_CONST | 119,996 | 0.7% |
| LOAD_GLOBAL_MODULE | 1,840 | 0.0% |
| CALL | 1,082 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 6,423,725 | 38.4% |
| COMPARE_OP | 5,882,604 | 35.2% |
| LOAD_ATTR | 4,209,375 | 25.2% |
| IS_OP | 64,256 | 0.4% |
| BUILD_TUPLE | 55,800 | 0.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 493,883 | 90.8% |
| CALL_BUILTIN_CLASS | 25,400 | 4.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,376 | 3.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,840 | 0.3% |
| UNARY_NEGATIVE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 542,039 | 99.7% |
| RETURN_VALUE | 1,580 | 0.3% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,988,957 | 41.0% |
| LOAD_FAST_LOAD_FAST | 18,328,402 | 35.8% |
| CALL_LEN | 10,271,124 | 20.1% |
| LOAD_FAST | 1,029,128 | 2.0% |
| LOAD_ATTR_SLOT | 225,258 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 35,533,935 | 69.4% |
| BINARY_OP | 6,308,780 | 12.3% |
| LOAD_GLOBAL_BUILTIN | 4,738,660 | 9.3% |
| EXTENDED_ARG | 1,719,905 | 3.4% |
| LOAD_FAST_LOAD_FAST | 1,570,040 | 3.1% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,030,880 | 68.9% |
| LOAD_CONST | 4,336,200 | 29.8% |
| LOAD_GLOBAL_MODULE | 192,561 | 1.3% |
| LOAD_ATTR | 3,160 | 0.0% |
| LOAD_FAST | 2,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,481,237 | 99.4% |
| YIELD_VALUE | 79,784 | 0.5% |
| POP_JUMP_IF_TRUE | 3,520 | 0.0% |
| EXTENDED_ARG | 1,000 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100,613 | 52.6% |
| GET_ITER | 90,706 | 47.4% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 99,693 | 52.1% |
| POP_TOP | 90,546 | 47.3% |
| RESUME | 860 | 0.4% |
| STORE_FAST | 320 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 46,568,722 | 74.0% |
| EXTENDED_ARG | 5,660,765 | 9.0% |
| LOAD_FAST | 4,843,790 | 7.7% |
| GET_ITER | 4,580,186 | 7.3% |
| SWAP | 1,221,469 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 43,131,306 | 68.6% |
| RETURN_CONST | 5,671,849 | 9.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,738,052 | 7.5% |
| STORE_FAST_LOAD_FAST | 4,156,292 | 6.6% |
| LOAD_FAST | 4,094,111 | 6.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 10,609,802 | 87.5% |
| GET_ITER | 809,536 | 6.7% |
| EXTENDED_ARG | 642,400 | 5.3% |
| SWAP | 38,880 | 0.3% |
| LOAD_FAST | 29,360 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,760,542 | 88.7% |
| RETURN_CONST | 630,291 | 5.2% |
| STORE_FAST_LOAD_FAST | 500,000 | 4.1% |
| LOAD_FAST | 195,180 | 1.6% |
| SWAP | 38,520 | 0.3% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 22,277,496 | 64.0% |
| GET_ITER | 9,975,736 | 28.6% |
| EXTENDED_ARG | 1,740,040 | 5.0% |
| LOAD_FAST | 518,942 | 1.5% |
| SWAP | 299,518 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 23,958,086 | 68.8% |
| LOAD_FAST | 7,495,194 | 21.5% |
| RETURN_CONST | 789,179 | 2.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 716,648 | 2.1% |
| LOAD_GLOBAL_MODULE | 602,506 | 1.7% |


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
| LOAD_FAST | 5,501,638 | 59.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,061,378 | 11.6% |
| LOAD_DEREF | 1,058,838 | 11.5% |
| COPY | 956,400 | 10.4% |
| LOAD_GLOBAL_MODULE | 571,571 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,560,485 | 17.0% |
| CALL_BUILTIN_FAST | 1,337,284 | 14.6% |
| POP_JUMP_IF_NOT_NONE | 1,225,045 | 13.3% |
| STORE_FAST | 1,076,538 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,061,378 | 11.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,138,187 | 86.3% |
| RETURN_VALUE | 4,635,745 | 5.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 3,116,160 | 3.4% |
| LOAD_GLOBAL_MODULE | 1,983,881 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,560,485 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,847,287 | 34.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,532,214 | 26.8% |
| CALL_PY_EXACT_ARGS | 21,015,951 | 22.9% |
| LOAD_CONST | 4,055,939 | 4.4% |
| LOAD_DEREF | 3,320,110 | 3.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 22,003,094 | 71.5% |
| LOAD_ATTR_SLOT | 4,711,741 | 15.3% |
| LOAD_FAST | 3,707,199 | 12.1% |
| STORE_FAST_LOAD_FAST | 157,680 | 0.5% |
| LOAD_ATTR | 147,523 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,917,222 | 48.5% |
| LOAD_FAST_LOAD_FAST | 10,703,370 | 34.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,807,661 | 15.6% |
| CALL_PY_EXACT_ARGS | 313,771 | 1.0% |
| LOAD_CONST | 6,526 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,261,444 | 99.2% |
| LOAD_FAST | 5,540 | 0.4% |
| LOAD_ATTR_MODULE | 2,680 | 0.2% |
| LOAD_ATTR | 1,404 | 0.1% |
| LOAD_FAST_LOAD_FAST | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,044,543 | 82.1% |
| CALL_PY_EXACT_ARGS | 80,728 | 6.3% |
| CALL | 57,377 | 4.5% |
| LOAD_FAST | 26,100 | 2.1% |
| LOAD_ATTR_SLOT | 15,920 | 1.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,473,876 | 92.5% |
| LOAD_DEREF | 3,109,100 | 5.3% |
| BINARY_SUBSCR_LIST_INT | 342,120 | 0.6% |
| STORE_FAST_LOAD_FAST | 238,651 | 0.4% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 236,952 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 44,303,190 | 75.3% |
| CALL_BUILTIN_O | 5,614,833 | 9.5% |
| BUILD_TUPLE | 2,484,120 | 4.2% |
| LOAD_FAST | 1,921,061 | 3.3% |
| BINARY_OP_MULTIPLY_INT | 1,668,679 | 2.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,004,188 | 60.9% |
| LOAD_FAST_LOAD_FAST | 478,940 | 29.1% |
| LOAD_DEREF | 144,340 | 8.8% |
| LOAD_ATTR | 12,020 | 0.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 4,942 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 478,200 | 29.0% |
| TO_BOOL_STR | 478,200 | 29.0% |
| TO_BOOL_BOOL | 409,440 | 24.8% |
| LOAD_CONST | 106,520 | 6.5% |
| CALL_LEN | 73,480 | 4.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,485,384 | 94.6% |
| RETURN_VALUE | 642,599 | 2.3% |
| STORE_FAST_LOAD_FAST | 318,633 | 1.1% |
| LOAD_DEREF | 217,206 | 0.8% |
| LOAD_FAST_LOAD_FAST | 168,600 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,814,255 | 67.2% |
| COPY_FREE_VARS | 5,061,531 | 18.1% |
| GET_ITER | 1,919,877 | 6.9% |
| TO_BOOL_BOOL | 729,745 | 2.6% |
| STORE_FAST | 506,282 | 1.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 95,200,807 | 99.1% |
| LOAD_ATTR_SLOT | 613,696 | 0.6% |
| LOAD_FAST_LOAD_FAST | 88,076 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 72,492 | 0.1% |
| STORE_FAST_LOAD_FAST | 21,598 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,433,085 | 34.8% |
| STORE_FAST | 22,510,702 | 23.4% |
| LOAD_DEREF | 6,405,182 | 6.7% |
| LOAD_FAST | 5,220,086 | 5.4% |
| LOAD_CONST | 5,210,298 | 5.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 58,003,664 | 24.8% |
| RESUME_CHECK | 41,291,479 | 17.7% |
| STORE_FAST | 37,718,836 | 16.1% |
| STORE_FAST_STORE_FAST | 22,025,257 | 9.4% |
| LOAD_FAST | 20,513,558 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,950,647 | 69.7% |
| LOAD_FAST_LOAD_FAST | 28,998,019 | 12.4% |
| CALL_ISINSTANCE | 19,056,185 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 9,010,241 | 3.9% |
| LOAD_DEREF | 3,365,546 | 1.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 78,856,537 | 54.1% |
| STORE_FAST | 18,255,673 | 12.5% |
| RESUME_CHECK | 16,028,988 | 11.0% |
| POP_JUMP_IF_FALSE | 9,687,831 | 6.6% |
| NOP | 6,493,624 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 57,027,116 | 39.1% |
| CALL_ISINSTANCE | 35,899,699 | 24.6% |
| LOAD_FAST | 29,779,032 | 20.4% |
| CONTAINS_OP | 5,290,390 | 3.6% |
| LOAD_FAST_LOAD_FAST | 3,334,220 | 2.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,104,627 | 93.5% |
| LOAD_DEREF | 77,300 | 6.5% |
| LOAD_SUPER_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,182,027 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,813,703 | 100.0% |
| LOAD_SUPER_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,539,431 | 84.9% |
| LOAD_GLOBAL_MODULE | 172,272 | 9.5% |
| LOAD_FAST | 84,580 | 4.7% |
| LOAD_FAST_LOAD_FAST | 17,560 | 1.0% |
| CALL | 360 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 98,993,080 | 38.4% |
| CALL_PY_EXACT_ARGS | 50,918,057 | 19.8% |
| COPY_FREE_VARS | 21,817,019 | 8.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 21,657,183 | 8.4% |
| LOAD_ATTR_PROPERTY | 18,814,255 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 115,566,575 | 44.8% |
| LOAD_GLOBAL_BUILTIN | 41,291,479 | 16.0% |
| NOP | 21,365,046 | 8.3% |
| LOAD_FAST_LOAD_FAST | 19,856,868 | 7.7% |
| LOAD_GLOBAL_MODULE | 16,028,988 | 6.2% |


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
| LOAD_FAST | 2,103,824 | 62.6% |
| SWAP | 956,400 | 28.5% |
| LOAD_FAST_LOAD_FAST | 259,600 | 7.7% |
| LOAD_ATTR_SLOT | 35,149 | 1.0% |
| STORE_ATTR | 3,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,210,735 | 36.0% |
| RETURN_CONST | 887,406 | 26.4% |
| NOP | 480,100 | 14.3% |
| RETURN_VALUE | 478,260 | 14.2% |
| LOAD_FAST_LOAD_FAST | 122,720 | 3.7% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,732,756 | 52.2% |
| LOAD_FAST | 4,285,529 | 47.3% |
| STORE_ATTR_SLOT | 41,655 | 0.5% |
| STORE_ATTR | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,673,536 | 51.6% |
| LOAD_FAST_LOAD_FAST | 2,256,613 | 24.9% |
| LOAD_CONST | 1,890,913 | 20.9% |
| LOAD_GLOBAL_MODULE | 136,863 | 1.5% |
| RETURN_CONST | 45,660 | 0.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,574,109 | 68.9% |
| LOAD_FAST | 397,970 | 17.4% |
| CALL_TUPLE_1 | 181,360 | 7.9% |
| RETURN_VALUE | 82,840 | 3.6% |
| LOAD_CONST | 39,349 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,660,529 | 72.7% |
| EXTENDED_ARG | 226,750 | 9.9% |
| LOAD_FAST_LOAD_FAST | 184,960 | 8.1% |
| LOAD_FAST | 165,802 | 7.3% |
| LOAD_GLOBAL_MODULE | 38,969 | 1.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,849,579 | 92.7% |
| SWAP | 1,208,120 | 5.9% |
| BINARY_SUBSCR_DICT | 112,800 | 0.6% |
| LOAD_FAST | 99,413 | 0.5% |
| BINARY_OP_SUBTRACT_INT | 49,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 10,114,835 | 49.7% |
| LOAD_FAST_LOAD_FAST | 10,021,377 | 49.3% |
| LOAD_CONST | 160,200 | 0.8% |
| LOAD_FAST | 21,140 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 21,060 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,600 | 98.7% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| STORE_FAST_LOAD_FAST | 1,240 | 0.5% |
| TO_BOOL | 386 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 217,409 | 95.1% |
| POP_JUMP_IF_FALSE | 9,764 | 4.3% |
| TO_BOOL_ALWAYS_TRUE | 1,420 | 0.6% |
| TO_BOOL | 53 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 59,845,442 | 34.6% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 44,303,190 | 25.7% |
| LOAD_FAST | 21,620,234 | 12.5% |
| CALL_BUILTIN_FAST | 18,103,901 | 10.5% |
| CALL_BUILTIN_O | 9,902,150 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 111,650,296 | 64.6% |
| POP_JUMP_IF_TRUE | 54,460,578 | 31.5% |
| EXTENDED_ARG | 5,486,213 | 3.2% |
| UNARY_NOT | 1,118,751 | 0.6% |
| TO_BOOL_NONE | 1,280 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,369,293 | 93.3% |
| BINARY_OP | 733,167 | 3.7% |
| BINARY_SUBSCR_LIST_INT | 485,260 | 2.5% |
| BINARY_SUBSCR_TUPLE_INT | 63,341 | 0.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 24,864 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,557,448 | 53.6% |
| POP_JUMP_IF_TRUE | 9,138,682 | 46.4% |
| TO_BOOL_NONE | 440 | 0.0% |
| UNARY_NOT | 171 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,235,260 | 97.0% |
| COPY | 39,560 | 1.7% |
| LOAD_DEREF | 10,898 | 0.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8,780 | 0.4% |
| STORE_FAST | 6,240 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 835,053 | 36.3% |
| POP_JUMP_IF_TRUE | 784,568 | 34.1% |
| UNARY_NOT | 661,888 | 28.7% |
| EXTENDED_ARG | 21,480 | 0.9% |
| TO_BOOL_NONE | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,841,950 | 68.0% |
| RETURN_VALUE | 389,150 | 14.4% |
| LOAD_ATTR_PROPERTY | 293,198 | 10.8% |
| CALL_METHOD_DESCRIPTOR_O | 104,000 | 3.8% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 41,977 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,944,541 | 71.8% |
| POP_JUMP_IF_TRUE | 745,477 | 27.5% |
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
| LOAD_FAST | 120,328 | 66.8% |
| RETURN_VALUE | 49,120 | 27.3% |
| CALL_BUILTIN_CLASS | 2,600 | 1.4% |
| BINARY_SUBSCR_LIST_INT | 1,880 | 1.0% |
| FOR_ITER_LIST | 1,880 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 114,940 | 63.8% |
| STORE_FAST_STORE_FAST | 65,148 | 36.2% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 885,525 | 54.3% |
| RETURN_VALUE | 660,922 | 40.5% |
| STORE_FAST | 79,520 | 4.9% |
| CALL_METHOD_DESCRIPTOR_O | 3,680 | 0.2% |
| UNPACK_SEQUENCE | 1,164 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,436,795 | 88.1% |
| STORE_FAST | 154,836 | 9.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,760 | 2.4% |
| STORE_DEREF | 120 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 70,920,025 | 68.4% |
| RETURN_VALUE | 19,466,570 | 18.8% |
| BINARY_SUBSCR_LIST_INT | 7,540,554 | 7.3% |
| FOR_ITER_LIST | 4,738,052 | 4.6% |
| FOR_ITER_TUPLE | 716,648 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 98,840,680 | 95.4% |
| STORE_DEREF | 4,491,620 | 4.3% |
| STORE_FAST | 257,714 | 0.2% |
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
|     deferred | 35,269,696 | 65.2% |
|          hit | 18,803,835 | 34.7% |
|         miss | 120 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,914 | 11.9% |
| Failure | 51,419 | 88.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 9,464 | 18.4% |
| multiply different types | 7,467 | 14.5% |
| subtract other | 6,800 | 13.2% |
| and int | 4,145 | 8.1% |
| rshift | 3,830 | 7.4% |
| or | 3,700 | 7.2% |
| power | 2,889 | 5.6% |
| true divide different types | 2,527 | 4.9% |
| multiply other | 2,360 | 4.6% |
| remainder | 2,314 | 4.5% |
| add different types | 1,948 | 3.8% |
| floor divide | 1,288 | 2.5% |
| subtract different types | 1,186 | 2.3% |
| xor | 587 | 1.1% |
| and other | 376 | 0.7% |
| true divide other | 300 | 0.6% |
| lshift | 231 | 0.4% |
| true divide float | 7 | 0.0% |


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
|     deferred | 23,863,054 | 35.8% |
|          hit | 42,679,452 | 64.1% |
|         miss | 45,574 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,377 | 32.2% |
| Failure | 17,600 | 67.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 12,173 | 69.2% |
| out of range | 3,640 | 20.7% |
| buffer int | 1,760 | 10.0% |
| array int | 20 | 0.1% |
| tuple slice | 7 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,132,337 | 5.9% |
|        deopt | 31,040 | 0.0% |
|          hit | 384,611,118 | 86.9% |
|         miss | 31,286,540 | 7.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 670,801 | 90.2% |
| Failure | 72,904 | 9.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 28,622 | 39.3% |
| code complex parameters | 14,055 | 19.3% |
| class no vectorcall | 9,220 | 12.6% |
| cfunc varargs keywords | 6,389 | 8.8% |
| other | 3,040 | 4.2% |
| wrong number arguments | 2,520 | 3.5% |
| cfunc noargs | 2,400 | 3.3% |
| bound method | 2,178 | 3.0% |
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
|     deferred | 38,378,198 | 36.6% |
|          hit | 65,709,618 | 62.7% |
|         miss | 575,939 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20,482 | 22.8% |
| Failure | 69,343 | 77.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 18,504 | 26.7% |
| other | 15,241 | 22.0% |
| different types | 12,271 | 17.7% |
| tuple | 10,064 | 14.5% |
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
|     deferred | 103,511,345 | 48.4% |
|          hit | 108,478,370 | 50.8% |
|         miss | 1,571,138 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 41,547 | 30.0% |
| Failure | 97,030 | 70.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 68,901 | 71.0% |
| set | 8,976 | 9.3% |
| zip | 7,600 | 7.8% |
| enumerate | 4,233 | 4.4% |
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
|     deferred | 120,213,912 | 27.4% |
|        deopt | 20 | 0.0% |
|          hit | 250,199,795 | 56.9% |
|         miss | 67,439,835 | 15.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,350,256 | 89.4% |
| Failure | 160,233 | 10.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 60,847 | 38.0% |
| mutable class | 58,772 | 36.7% |
| method | 10,463 | 6.5% |
| has managed dict | 8,780 | 5.5% |
| overridden | 8,675 | 5.4% |
| shadowed | 5,300 | 3.3% |
| class method obj | 3,980 | 2.5% |
| builtin class method | 1,320 | 0.8% |
| not managed dict | 1,116 | 0.7% |
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
|     deferred | 90,132 | 0.0% |
|          hit | 379,583,186 | 99.9% |
|         miss | 20,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 92,086 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 609 | 0.0% |
|          hit | 2,996,230 | 100.0% |

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
|     deferred | 540,846 | 4.2% |
|          hit | 10,204,940 | 78.4% |
|         miss | 2,215,033 | 17.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 46,715 | 92.3% |
| Failure | 3,914 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 1,960 | 50.1% |
| not managed dict | 1,454 | 37.1% |
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
|     deferred | 3,422,931 | 13.1% |
|          hit | 22,624,304 | 86.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,724 | 42.8% |
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
|     deferred | 12,842,651 | 6.1% |
|          hit | 197,734,255 | 93.7% |
|         miss | 440,371 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 59,997 | 72.2% |
| Failure | 23,066 | 27.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 10,799 | 46.8% |
| number | 3,536 | 15.3% |
| mapping | 3,300 | 14.3% |
| dict | 2,340 | 10.1% |
| other | 1,620 | 7.0% |
| set | 1,431 | 6.2% |
| float | 40 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,655 | 0.0% |
|          hit | 105,425,553 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 11,424 | 93.6% |
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
| Basic | 3,219,168,534 | 54.1% |
| Not specialized | 799,631,121 | 13.4% |
| Specialized hits | 1,824,305,190 | 30.7% |
| Specialized misses | 103,625,670 | 1.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 120,213,912 | 33.0% |
| FOR_ITER | 103,511,345 | 28.4% |
| COMPARE_OP | 38,378,198 | 10.5% |
| BINARY_OP | 35,269,696 | 9.7% |
| CALL | 26,132,337 | 7.2% |
| BINARY_SUBSCR | 23,863,054 | 6.5% |
| TO_BOOL | 12,842,651 | 3.5% |
| STORE_SUBSCR | 3,422,931 | 0.9% |
| STORE_ATTR | 540,846 | 0.1% |
| SEND | 439,140 | 0.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 36,605,224 | 35.3% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 17,007,636 | 16.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,233,870 | 13.7% |
| LOAD_ATTR_METHOD_NO_DICT | 9,218,245 | 8.9% |
| CALL_PY_EXACT_ARGS | 7,815,585 | 7.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,479,411 | 6.3% |
| LOAD_ATTR_PROPERTY | 4,124,695 | 4.0% |
| CALL_BUILTIN_O | 2,661,195 | 2.6% |
| STORE_ATTR_SLOT | 2,214,053 | 2.1% |
| FOR_ITER_TUPLE | 790,941 | 0.8% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,423,683 | 46.8% |
| Calls to Python functions inlined | 144,736,810 | 53.2% |
| Calls via PyEval_EvalFrame (total) | 127,423,683 | 46.8% |
| Calls via PyEval_EvalFrame (vector) | 98,456,913 | 36.2% |
| Calls via PyEval_EvalFrame (generator) | 28,966,770 | 10.6% |
| Calls via PyEval_EvalFrame (legacy) | 4,640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 98,449,613 | 36.2% |
| Calls via PyEval_EvalFrame (build class) | 2,660 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 23,668,619 | 8.7% |
| Calls via PyEval_EvalFrame (function ex) | 11,825,093 | 4.3% |
| Calls via PyEval_EvalFrame (api) | 53,328,873 | 19.6% |
| Calls via PyEval_EvalFrame (method) | 6,960 | 0.0% |
| Frame objects created | 1,287,176 | 0.5% |
| Frames pushed | 112,490,803 | 41.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 363,397,891 | 54.3% |
| Frees to freelist | 363,640,793 |  |
| Allocations | 305,577,271 | 45.7% |
| Allocations to 512 bytes | 304,515,990 | 45.5% |
| Allocations to 4 kbytes | 1,036,821 | 0.2% |
| Allocations over 4 kbytes | 24,460 | 0.0% |
| Frees | 313,263,380 |  |
| New values | 1,057,452 |  |
| Interpreter increfs | 2,567,235,088 | 64.2% |
| Interpreter decrefs | 2,992,366,504 | 65.4% |
| Increfs | 1,428,891,047 | 35.8% |
| Decrefs | 1,584,494,811 | 34.6% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 0.0% |
| Method cache hits | 244,201,598 |  |
| Method cache misses | 3,332,642 |  |
| Method cache collisions | 4,550,400 |  |
| Method cache dunder hits | 347,070,391 |  |
| Method cache dunder misses | 1,218,427 |  |


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
Stats gathered on: 2023-11-26
