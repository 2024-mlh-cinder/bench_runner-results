
# Pystats results

- benchmark: dask
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 14aea56
- commit date: 2023-11-17T15:11:51-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 320,684,975 | 20.3% | 20.3% |  |
| STORE_FAST | 79,427,041 | 5.0% | 25.3% |  |
| RESUME_CHECK | 76,231,071 | 4.8% | 30.1% | 0.0% |
| LOAD_CONST | 66,082,166 | 4.2% | 34.3% |  |
| POP_JUMP_IF_FALSE | 63,454,048 | 4.0% | 38.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 57,551,978 | 3.6% | 41.9% | 0.6% |
| RETURN_VALUE | 54,274,467 | 3.4% | 45.3% |  |
| LOAD_FAST_LOAD_FAST | 46,865,709 | 3.0% | 48.3% |  |
| LOAD_GLOBAL_MODULE | 43,046,692 | 2.7% | 51.0% | 0.0% |
| POP_TOP | 42,809,258 | 2.7% | 53.7% |  |
| LOAD_GLOBAL_BUILTIN | 36,699,203 | 2.3% | 56.0% | 0.0% |
| LOAD_ATTR_SLOT | 32,921,830 | 2.1% | 58.1% | 3.5% |
| CALL_PY_EXACT_ARGS | 30,196,652 | 1.9% | 60.0% | 0.4% |
| CALL | 27,143,289 | 1.7% | 61.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 26,409,794 | 1.7% | 63.4% | 1.4% |
| INTERPRETER_EXIT | 25,100,747 | 1.6% | 65.0% |  |
| TO_BOOL_BOOL | 24,827,438 | 1.6% | 66.6% | 0.0% |
| LOAD_ATTR_WITH_HINT | 21,037,690 | 1.3% | 67.9% | 0.3% |
| RETURN_CONST | 20,763,395 | 1.3% | 69.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 20,218,840 | 1.3% | 70.5% | 0.1% |
| LOAD_ATTR | 20,150,775 | 1.3% | 71.8% |  |
| PUSH_NULL | 19,579,297 | 1.2% | 73.0% |  |
| NOP | 17,262,983 | 1.1% | 74.1% |  |
| SWAP | 15,800,375 | 1.0% | 75.1% |  |
| STORE_ATTR_SLOT | 15,135,988 | 1.0% | 76.0% | 5.9% |
| BUILD_MAP | 14,579,878 | 0.9% | 77.0% |  |
| GET_ITER | 13,940,902 | 0.9% | 77.8% |  |
| POP_JUMP_IF_TRUE | 13,021,046 | 0.8% | 78.7% |  |
| CALL_FUNCTION_EX | 11,719,305 | 0.7% | 79.4% |  |
| ENTER_EXECUTOR | 11,297,115 | 0.7% | 80.1% |  |
| BUILD_LIST | 10,978,595 | 0.7% | 80.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 10,505,280 | 0.7% | 81.5% | 0.0% |
| COPY | 10,355,062 | 0.7% | 82.1% |  |
| BINARY_SUBSCR_DICT | 10,199,525 | 0.6% | 82.8% |  |
| CONTAINS_OP | 10,131,072 | 0.6% | 83.4% |  |
| IS_OP | 9,344,429 | 0.6% | 84.0% |  |
| BUILD_TUPLE | 9,186,343 | 0.6% | 84.6% |  |
| DICT_MERGE | 8,843,461 | 0.6% | 85.2% |  |
| LOAD_DEREF | 8,723,030 | 0.6% | 85.7% |  |
| TO_BOOL | 8,558,154 | 0.5% | 86.2% |  |
| COMPARE_OP_INT | 8,112,018 | 0.5% | 86.8% | 0.3% |
| LIST_EXTEND | 8,037,963 | 0.5% | 87.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 8,020,065 | 0.5% | 87.8% | 0.1% |
| CALL_INTRINSIC_1 | 7,958,355 | 0.5% | 88.3% |  |
| LOAD_ATTR_MODULE | 7,869,396 | 0.5% | 88.8% | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 7,720,611 | 0.5% | 89.3% | 1.2% |
| CALL_TYPE_1 | 7,697,479 | 0.5% | 89.7% |  |
| CALL_BUILTIN_CLASS | 7,123,116 | 0.5% | 90.2% |  |
| FOR_ITER_TUPLE | 6,928,877 | 0.4% | 90.6% |  |
| POP_JUMP_IF_NONE | 6,542,066 | 0.4% | 91.0% |  |
| POP_JUMP_IF_NOT_NONE | 6,124,174 | 0.4% | 91.4% |  |
| FOR_ITER | 6,078,170 | 0.4% | 91.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 6,017,511 | 0.4% | 92.2% | 3.0% |
| CALL_LEN | 5,563,539 | 0.4% | 92.5% |  |
| COMPARE_OP_STR | 5,555,077 | 0.4% | 92.9% | 0.0% |
| BINARY_OP_ADD_INT | 5,083,699 | 0.3% | 93.2% | 0.0% |
| CALL_ISINSTANCE | 4,478,059 | 0.3% | 93.5% |  |
| STORE_SUBSCR_DICT | 4,469,557 | 0.3% | 93.8% |  |
| STORE_FAST_STORE_FAST | 4,404,136 | 0.3% | 94.1% |  |
| TO_BOOL_NONE | 4,165,353 | 0.3% | 94.3% | 0.2% |
| MAKE_CELL | 4,162,370 | 0.3% | 94.6% |  |
| COPY_FREE_VARS | 3,858,958 | 0.2% | 94.8% |  |
| JUMP_FORWARD | 3,636,679 | 0.2% | 95.1% |  |
| BINARY_OP | 3,635,029 | 0.2% | 95.3% |  |
| CALL_KW | 3,497,473 | 0.2% | 95.5% |  |
| FOR_ITER_LIST | 3,442,349 | 0.2% | 95.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,296,696 | 0.2% | 95.9% |  |
| LOAD_ATTR_PROPERTY | 2,729,456 | 0.2% | 96.1% | 0.0% |
| CALL_PY_WITH_DEFAULTS | 2,422,589 | 0.2% | 96.3% | 0.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,251,992 | 0.1% | 96.4% | 0.1% |
| LOAD_FAST_AND_CLEAR | 2,170,338 | 0.1% | 96.5% |  |
| BEFORE_WITH | 2,150,052 | 0.1% | 96.7% |  |
| BINARY_OP_SUBTRACT_INT | 1,946,337 | 0.1% | 96.8% |  |
| CALL_BUILTIN_FAST | 1,939,044 | 0.1% | 96.9% | 0.0% |
| COMPARE_OP_FLOAT | 1,710,758 | 0.1% | 97.0% | 0.1% |
| TO_BOOL_INT | 1,701,964 | 0.1% | 97.1% | 0.0% |
| CALL_BUILTIN_O | 1,586,483 | 0.1% | 97.2% | 0.1% |
| EXTENDED_ARG | 1,530,657 | 0.1% | 97.3% |  |
| TO_BOOL_LIST | 1,516,105 | 0.1% | 97.4% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,486,295 | 0.1% | 97.5% |  |
| YIELD_VALUE | 1,482,555 | 0.1% | 97.6% |  |
| COMPARE_OP | 1,460,127 | 0.1% | 97.7% |  |
| BINARY_SUBSCR | 1,431,191 | 0.1% | 97.8% |  |
| STORE_ATTR_WITH_HINT | 1,418,739 | 0.1% | 97.9% | 0.3% |
| DELETE_SUBSCR | 1,400,054 | 0.1% | 98.0% |  |
| SET_FUNCTION_ATTRIBUTE | 1,340,233 | 0.1% | 98.1% |  |
| MAKE_FUNCTION | 1,310,735 | 0.1% | 98.1% |  |
| UNPACK_SEQUENCE_TUPLE | 1,242,047 | 0.1% | 98.2% |  |
| BINARY_OP_ADD_FLOAT | 1,165,431 | 0.1% | 98.3% | 0.1% |
| BUILD_CONST_KEY_MAP | 1,158,324 | 0.1% | 98.4% |  |
| STORE_ATTR | 1,048,261 | 0.1% | 98.4% |  |
| BINARY_SUBSCR_LIST_INT | 930,074 | 0.1% | 98.5% | 0.1% |
| RETURN_GENERATOR | 911,022 | 0.1% | 98.6% |  |
| PUSH_EXC_INFO | 860,110 | 0.1% | 98.6% |  |
| POP_EXCEPT | 860,100 | 0.1% | 98.7% |  |
| TO_BOOL_ALWAYS_TRUE | 831,255 | 0.1% | 98.7% | 0.9% |
| STORE_FAST_LOAD_FAST | 823,792 | 0.1% | 98.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 814,769 | 0.1% | 98.8% | 0.3% |
| STORE_DEREF | 801,410 | 0.1% | 98.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 770,775 | 0.0% | 98.9% |  |
| CHECK_EXC_MATCH | 726,891 | 0.0% | 99.0% |  |
| BINARY_SLICE | 721,709 | 0.0% | 99.0% |  |
| MAP_ADD | 688,162 | 0.0% | 99.1% |  |
| CALL_LIST_APPEND | 658,031 | 0.0% | 99.1% |  |
| BINARY_OP_MULTIPLY_INT | 650,614 | 0.0% | 99.1% |  |
| LOAD_SUPER_ATTR_METHOD | 638,203 | 0.0% | 99.2% |  |
| BUILD_SET | 601,894 | 0.0% | 99.2% |  |
| SEND_GEN | 589,080 | 0.0% | 99.3% | 0.0% |
| BINARY_SUBSCR_GETITEM | 584,134 | 0.0% | 99.3% | 0.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 582,175 | 0.0% | 99.3% |  |
| TO_BOOL_STR | 563,209 | 0.0% | 99.4% | 0.3% |
| STORE_SUBSCR | 542,349 | 0.0% | 99.4% |  |
| LIST_APPEND | 519,407 | 0.0% | 99.4% |  |
| FORMAT_SIMPLE | 516,999 | 0.0% | 99.5% |  |
| END_SEND | 516,456 | 0.0% | 99.5% |  |
| GET_AWAITABLE | 515,338 | 0.0% | 99.5% |  |
| SEND | 513,891 | 0.0% | 99.6% |  |
| BUILD_STRING | 465,631 | 0.0% | 99.6% |  |
| LOAD_ATTR_CLASS | 458,122 | 0.0% | 99.6% | 0.5% |
| FOR_ITER_RANGE | 453,073 | 0.0% | 99.6% |  |
| CALL_TUPLE_1 | 363,214 | 0.0% | 99.7% |  |
| RERAISE | 359,376 | 0.0% | 99.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 336,606 | 0.0% | 99.7% | 0.4% |
| DELETE_FAST | 332,486 | 0.0% | 99.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 297,175 | 0.0% | 99.8% | 0.3% |
| EXIT_INIT_CHECK | 296,095 | 0.0% | 99.8% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 263,960 | 0.0% | 99.8% |  |
| BINARY_OP_ADD_UNICODE | 261,413 | 0.0% | 99.8% | 0.1% |
| CALL_STR_1 | 257,387 | 0.0% | 99.8% |  |
| LOAD_FAST_CHECK | 248,731 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_STR_INT | 242,804 | 0.0% | 99.9% | 0.2% |
| BINARY_OP_MULTIPLY_FLOAT | 206,973 | 0.0% | 99.9% | 1.1% |
| IMPORT_FROM | 202,440 | 0.0% | 99.9% |  |
| IMPORT_NAME | 201,716 | 0.0% | 99.9% |  |
| WITH_EXCEPT_START | 178,426 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 177,320 | 0.0% | 99.9% |  |
| SET_ADD | 176,880 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 168,335 | 0.0% | 99.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 130,358 | 0.0% | 99.9% | 30.9% |
| BINARY_OP_INPLACE_ADD_UNICODE | 120,880 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 109,190 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 97,819 | 0.0% | 100.0% | 0.4% |
| SET_UPDATE | 88,020 | 0.0% | 100.0% |  |
| UNPACK_EX | 88,000 | 0.0% | 100.0% |  |
| UNARY_INVERT | 83,334 | 0.0% | 100.0% |  |
| BUILD_SLICE | 82,787 | 0.0% | 100.0% |  |
| DICT_UPDATE | 42,313 | 0.0% | 100.0% |  |
| STORE_SLICE | 40,605 | 0.0% | 100.0% |  |
| RESUME | 26,205 | 0.0% | 100.0% | 22.0% |
| STORE_NAME | 14,380 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 10,732 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 8,809 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 8,697 | 0.0% | 100.0% |  |
| DELETE_ATTR | 8,383 | 0.0% | 100.0% |  |
| LOAD_NAME | 6,720 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 6,128 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 4,964 | 0.0% | 100.0% | 90.0% |
| LOAD_SUPER_ATTR_ATTR | 3,932 | 0.0% | 100.0% |  |
| END_FOR | 3,687 | 0.0% | 100.0% |  |
| UNARY_NOT | 2,701 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,840 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 1,761 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 1,220 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 940 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 883 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 460 | 0.0% | 100.0% |  |
| SETUP_ANNOTATIONS | 440 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 80 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 50,297,782 | 3.2% | 3.2% |
| STORE_FAST LOAD_FAST | 44,985,097 | 2.8% | 6.0% |
| RESUME_CHECK LOAD_FAST | 44,654,174 | 2.8% | 8.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 34,240,929 | 2.2% | 11.0% |
| LOAD_FAST LOAD_ATTR_SLOT | 30,404,680 | 1.9% | 12.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 28,596,516 | 1.8% | 14.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 22,726,846 | 1.4% | 16.2% |
| CACHE RESUME_CHECK | 22,015,133 | 1.4% | 17.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 19,631,408 | 1.2% | 18.8% |
| LOAD_CONST LOAD_FAST | 18,466,545 | 1.2% | 20.0% |
| RETURN_VALUE INTERPRETER_EXIT | 17,468,568 | 1.1% | 21.1% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 17,403,798 | 1.1% | 22.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 15,209,600 | 1.0% | 23.1% |
| POP_TOP LOAD_FAST | 15,012,644 | 0.9% | 24.1% |
| LOAD_FAST LOAD_ATTR | 14,442,753 | 0.9% | 25.0% |
| RETURN_VALUE STORE_FAST | 13,916,507 | 0.9% | 25.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 13,630,379 | 0.9% | 26.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 13,536,104 | 0.9% | 27.6% |
| LOAD_FAST LOAD_CONST | 12,606,718 | 0.8% | 28.4% |
| RETURN_CONST POP_TOP | 12,342,620 | 0.8% | 29.2% |
| PUSH_NULL LOAD_FAST | 12,200,383 | 0.8% | 29.9% |
| LOAD_FAST RETURN_VALUE | 11,878,753 | 0.8% | 30.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 10,835,022 | 0.7% | 31.4% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 10,443,801 | 0.7% | 32.0% |
| LOAD_FAST CALL | 10,143,668 | 0.6% | 32.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 9,614,373 | 0.6% | 33.3% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 9,250,074 | 0.6% | 33.9% |
| DICT_MERGE CALL_FUNCTION_EX | 8,843,461 | 0.6% | 34.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 8,711,739 | 0.6% | 35.0% |
| BUILD_MAP LOAD_FAST | 8,612,500 | 0.5% | 35.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 8,602,904 | 0.5% | 36.1% |
| BUILD_LIST LOAD_FAST | 8,407,508 | 0.5% | 36.6% |
| LOAD_FAST DICT_MERGE | 8,238,111 | 0.5% | 37.1% |
| NOP LOAD_FAST | 8,205,031 | 0.5% | 37.6% |
| LOAD_FAST STORE_ATTR_SLOT | 8,149,047 | 0.5% | 38.1% |
| LOAD_FAST PUSH_NULL | 8,052,063 | 0.5% | 38.7% |
| LIST_EXTEND CALL_INTRINSIC_1 | 7,957,033 | 0.5% | 39.2% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 7,643,415 | 0.5% | 39.6% |
| LOAD_FAST CALL_TYPE_1 | 7,607,639 | 0.5% | 40.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 7,606,382 | 0.5% | 40.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 7,600,987 | 0.5% | 41.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 7,537,329 | 0.5% | 41.6% |
| STORE_FAST NOP | 7,421,324 | 0.5% | 42.0% |
| RETURN_VALUE RETURN_VALUE | 7,363,004 | 0.5% | 42.5% |
| IS_OP POP_JUMP_IF_FALSE | 7,326,953 | 0.5% | 43.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 7,318,728 | 0.5% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 7,302,522 | 0.5% | 43.9% |
| LOAD_FAST BUILD_LIST | 7,033,856 | 0.4% | 44.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 7,016,079 | 0.4% | 44.8% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 6,967,442 | 0.4% | 45.2% |
| LOAD_FAST LIST_EXTEND | 6,688,708 | 0.4% | 45.6% |
| LOAD_CONST LOAD_CONST | 6,556,403 | 0.4% | 46.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 6,542,869 | 0.4% | 46.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 6,519,688 | 0.4% | 46.9% |
| RETURN_CONST INTERPRETER_EXIT | 6,378,201 | 0.4% | 47.3% |
| BINARY_SUBSCR_DICT STORE_FAST | 6,336,008 | 0.4% | 47.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,285,940 | 0.4% | 48.1% |
| LOAD_ATTR_MODULE PUSH_NULL | 6,239,459 | 0.4% | 48.5% |
| POP_TOP RETURN_CONST | 6,070,452 | 0.4% | 48.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 5,931,510 | 0.4% | 49.2% |
| TO_BOOL POP_JUMP_IF_FALSE | 5,788,342 | 0.4% | 49.6% |
| CALL_INTRINSIC_1 BUILD_MAP | 5,764,438 | 0.4% | 49.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 5,731,785 | 0.4% | 50.3% |
| CALL_FUNCTION_EX RESUME_CHECK | 5,709,328 | 0.4% | 50.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 5,703,136 | 0.4% | 51.0% |
| FOR_ITER_TUPLE STORE_FAST | 5,681,282 | 0.4% | 51.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 5,526,496 | 0.3% | 51.7% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_NO_DICT | 5,452,665 | 0.3% | 52.1% |
| POP_TOP RETURN_VALUE | 5,412,666 | 0.3% | 52.4% |
| GET_ITER FOR_ITER_TUPLE | 5,406,830 | 0.3% | 52.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 5,388,985 | 0.3% | 53.1% |
| RETURN_VALUE TO_BOOL_BOOL | 5,340,340 | 0.3% | 53.4% |
| RESUME_CHECK NOP | 5,260,662 | 0.3% | 53.8% |
| CALL POP_TOP | 5,236,674 | 0.3% | 54.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,192,700 | 0.3% | 54.4% |
| POP_TOP ENTER_EXECUTOR | 5,149,290 | 0.3% | 54.8% |
| LOAD_CONST STORE_FAST | 5,122,714 | 0.3% | 55.1% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 5,087,214 | 0.3% | 55.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 5,063,189 | 0.3% | 55.7% |
| CALL RETURN_VALUE | 5,058,728 | 0.3% | 56.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 5,029,256 | 0.3% | 56.4% |
| NOP LOAD_FAST_LOAD_FAST | 4,982,124 | 0.3% | 56.7% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 4,969,730 | 0.3% | 57.0% |
| LOAD_FAST SWAP | 4,940,799 | 0.3% | 57.3% |
| STORE_ATTR_SLOT LOAD_CONST | 4,871,442 | 0.3% | 57.6% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_DICT | 4,747,782 | 0.3% | 57.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_BUILTIN | 4,670,381 | 0.3% | 58.2% |
| LOAD_FAST POP_JUMP_IF_NONE | 4,638,743 | 0.3% | 58.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 4,623,936 | 0.3% | 58.8% |
| LOAD_FAST_LOAD_FAST IS_OP | 4,606,270 | 0.3% | 59.1% |
| GET_ITER FOR_ITER | 4,605,281 | 0.3% | 59.4% |
| LOAD_CONST COMPARE_OP_INT | 4,584,861 | 0.3% | 59.7% |
| CALL STORE_FAST | 4,562,009 | 0.3% | 60.0% |
| SWAP POP_TOP | 4,531,728 | 0.3% | 60.2% |
| LOAD_ATTR GET_ITER | 4,526,551 | 0.3% | 60.5% |
| CALL_TYPE_1 CALL_PY_EXACT_ARGS | 4,525,308 | 0.3% | 60.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 4,518,651 | 0.3% | 61.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 4,299,147 | 0.3% | 61.4% |
| LOAD_FAST TO_BOOL | 4,247,929 | 0.3% | 61.6% |
| LOAD_FAST COPY | 4,203,436 | 0.3% | 61.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 463,139 | 64.2% |
| LOAD_FAST | 215,264 | 29.8% |
| BINARY_OP_ADD_INT | 42,926 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 300 | 0.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 112,096 | 15.5% |
| CALL_BUILTIN_CLASS | 89,166 | 12.4% |
| CALL_METHOD_DESCRIPTOR_O | 87,960 | 12.2% |
| CALL_PY_WITH_DEFAULTS | 87,960 | 12.2% |
| STORE_FAST | 71,568 | 9.9% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,305 | 99.3% |
| LOAD_FAST | 160 | 0.4% |
| BINARY_OP_ADD_INT | 140 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,305 | 99.3% |
| LOAD_CONST | 160 | 0.4% |
| ENTER_EXECUTOR | 140 | 0.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 22,015,133 | 86.8% |
| COPY_FREE_VARS | 2,330,377 | 9.2% |
| POP_TOP | 580,149 | 2.3% |
| MAKE_CELL | 267,166 | 1.1% |
| RETURN_GENERATOR | 129,526 | 0.5% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,010 | 93.3% |
| LOAD_ATTR_WITH_HINT | 462 | 4.3% |
| CALL | 160 | 1.5% |
| CALL_KW | 80 | 0.7% |
| LOAD_ATTR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 10,732 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,587,624 | 73.8% |
| LOAD_GLOBAL_MODULE | 186,293 | 8.7% |
| LOAD_ATTR_WITH_HINT | 176,480 | 8.2% |
| LOAD_FAST | 176,240 | 8.2% |
| CALL | 11,340 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,145,104 | 99.8% |
| STORE_FAST | 4,948 | 0.2% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 108,760 | 90.0% |
| LOAD_FAST_LOAD_FAST | 10,000 | 8.3% |
| LOAD_CONST | 1,720 | 1.4% |
| BINARY_SUBSCR_STR_INT | 220 | 0.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 118,240 | 97.8% |
| LOAD_GLOBAL_MODULE | 1,720 | 1.4% |
| LOAD_FAST | 360 | 0.3% |
| JUMP_BACKWARD | 320 | 0.3% |
| STORE_FAST | 220 | 0.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 852,304 | 59.6% |
| COPY | 354,084 | 24.7% |
| LOAD_CONST | 216,618 | 15.1% |
| BINARY_SUBSCR | 4,784 | 0.3% |
| BUILD_SLICE | 1,200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 344,260 | 24.1% |
| LOAD_CONST | 266,408 | 18.6% |
| LOAD_FAST | 176,984 | 12.4% |
| STORE_FAST | 176,512 | 12.3% |
| LOAD_ATTR_METHOD_NO_DICT | 162,704 | 11.4% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 642,638 | 88.4% |
| LOAD_ATTR_MODULE | 78,191 | 10.8% |
| BUILD_TUPLE | 4,882 | 0.7% |
| LOAD_GLOBAL | 725 | 0.1% |
| LOAD_GLOBAL_MODULE | 361 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 726,891 | 100.0% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 883 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 642 | 72.7% |
| JUMP_BACKWARD | 241 | 27.3% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 964,116 | 68.9% |
| LOAD_FAST_LOAD_FAST | 265,491 | 19.0% |
| LOAD_ATTR_SLOT | 88,040 | 6.3% |
| BUILD_SLICE | 81,587 | 5.8% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 433,444 | 33.0% |
| PUSH_EXC_INFO | 352,000 | 26.8% |
| RETURN_CONST | 258,261 | 19.7% |
| LOAD_FAST_LOAD_FAST | 88,577 | 6.8% |
| LOAD_CONST | 88,510 | 6.7% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,687 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,446 | 39.2% |
| LOAD_CONST | 880 | 23.9% |
| STORE_FAST | 739 | 20.0% |
| SWAP | 300 | 8.1% |
| RETURN_CONST | 182 | 4.9% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 268,267 | 51.9% |
| SEND | 190,150 | 36.8% |
| RETURN_CONST | 57,638 | 11.2% |
| JUMP_BACKWARD | 241 | 0.0% |
| SEND_GEN | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 300,739 | 58.2% |
| POP_TOP | 116,953 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 88,242 | 17.1% |
| SWAP | 10,010 | 1.9% |
| LOAD_DEREF | 162 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 296,095 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 296,095 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 373,838 | 72.3% |
| LOAD_FAST | 130,471 | 25.2% |
| CONVERT_VALUE | 8,809 | 1.7% |
| LOAD_GLOBAL_MODULE | 3,340 | 0.6% |
| CALL_LEN | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 421,041 | 81.4% |
| LOAD_CONST | 54,012 | 10.4% |
| LOAD_FAST | 41,946 | 8.1% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,526,551 | 32.5% |
| LOAD_FAST | 3,402,716 | 24.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,530,768 | 18.2% |
| LOAD_ATTR_SLOT | 1,450,259 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 912,770 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 5,406,830 | 38.8% |
| FOR_ITER | 4,605,281 | 33.0% |
| FOR_ITER_LIST | 2,076,717 | 14.9% |
| LOAD_FAST_AND_CLEAR | 1,386,490 | 9.9% |
| CALL_PY_EXACT_ARGS | 255,957 | 1.8% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,740 | 98.8% |
| LOAD_ATTR | 20 | 1.1% |
| RETURN_GENERATOR | 1 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,761 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 17,468,568 | 69.6% |
| RETURN_CONST | 6,378,201 | 25.4% |
| YIELD_VALUE | 1,124,290 | 4.5% |
| RETURN_GENERATOR | 129,688 | 0.5% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 540 | 57.4% |
| POP_TOP | 300 | 31.9% |
| POP_JUMP_IF_FALSE | 40 | 4.3% |
| STORE_SUBSCR | 20 | 2.1% |
| JUMP_BACKWARD | 20 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 940 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,310,735 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,127,918 | 86.1% |
| STORE_DEREF | 88,012 | 6.7% |
| CALL | 41,226 | 3.1% |
| LOAD_GLOBAL_BUILTIN | 40,911 | 3.1% |
| LOAD_FAST | 6,574 | 0.5% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,421,324 | 43.0% |
| RESUME_CHECK | 5,260,662 | 30.5% |
| POP_JUMP_IF_FALSE | 1,494,577 | 8.7% |
| STORE_ATTR_INSTANCE_VALUE | 597,122 | 3.5% |
| POP_JUMP_IF_TRUE | 537,436 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,205,031 | 47.5% |
| LOAD_FAST_LOAD_FAST | 4,982,124 | 28.9% |
| LOAD_GLOBAL_MODULE | 2,006,192 | 11.6% |
| LOAD_CONST | 501,020 | 2.9% |
| LOAD_GLOBAL_BUILTIN | 478,733 | 2.8% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 519,671 | 60.4% |
| COPY | 179,227 | 20.8% |
| STORE_FAST | 144,098 | 16.8% |
| STORE_SUBSCR_DICT | 9,273 | 1.1% |
| SWAP | 6,247 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 436,185 | 50.7% |
| RERAISE | 179,227 | 20.8% |
| EXTENDED_ARG | 129,240 | 15.0% |
| DELETE_FAST | 40,543 | 4.7% |
| LOAD_CONST | 40,218 | 4.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 12,342,620 | 28.8% |
| CALL_METHOD_DESCRIPTOR_O | 7,643,415 | 17.9% |
| CALL | 5,236,674 | 12.2% |
| SWAP | 4,531,728 | 10.6% |
| CALL_FUNCTION_EX | 2,967,216 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,012,644 | 35.1% |
| RETURN_CONST | 6,070,452 | 14.2% |
| RETURN_VALUE | 5,412,666 | 12.6% |
| ENTER_EXECUTOR | 5,149,290 | 12.0% |
| LOAD_FAST_LOAD_FAST | 2,440,186 | 5.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 352,000 | 40.9% |
| BINARY_SUBSCR_DICT | 187,570 | 21.8% |
| CALL | 96,436 | 11.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 88,100 | 10.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 78,408 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 600,568 | 69.8% |
| WITH_EXCEPT_START | 178,426 | 20.7% |
| LOAD_GLOBAL_MODULE | 79,309 | 9.2% |
| LOAD_GLOBAL | 1,687 | 0.2% |
| DELETE_FAST | 80 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,052,063 | 41.1% |
| LOAD_ATTR_MODULE | 6,239,459 | 31.9% |
| LOAD_ATTR | 4,033,595 | 20.6% |
| LOAD_DEREF | 931,280 | 4.8% |
| RETURN_VALUE | 226,218 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,200,383 | 62.3% |
| CALL | 2,463,871 | 12.6% |
| LOAD_FAST_LOAD_FAST | 2,463,797 | 12.6% |
| LOAD_CONST | 1,192,470 | 6.1% |
| CALL_BUILTIN_CLASS | 437,644 | 2.2% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 297,556 | 32.7% |
| CALL_KW | 131,134 | 14.4% |
| CACHE | 129,526 | 14.2% |
| CALL_PY_EXACT_ARGS | 103,153 | 11.3% |
| CALL_PY_WITH_DEFAULTS | 84,585 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 294,103 | 32.3% |
| CALL_TUPLE_1 | 176,440 | 19.4% |
| INTERPRETER_EXIT | 129,688 | 14.2% |
| CALL_BUILTIN_O | 118,296 | 13.0% |
| CALL | 83,443 | 9.2% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,878,753 | 21.9% |
| RETURN_VALUE | 7,363,004 | 13.6% |
| POP_TOP | 5,412,666 | 10.0% |
| CALL | 5,058,728 | 9.3% |
| LOAD_ATTR_INSTANCE_VALUE | 3,857,021 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 17,468,568 | 32.2% |
| STORE_FAST | 13,916,507 | 25.6% |
| RETURN_VALUE | 7,363,004 | 13.6% |
| TO_BOOL_BOOL | 5,340,340 | 9.8% |
| LOAD_FAST | 1,508,991 | 2.8% |


</details>

### SETUP_ANNOTATIONS

<details>
<summary> Successors and predecessors for SETUP_ANNOTATIONS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 300 | 68.2% |
| RESUME | 140 | 31.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 440 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 354,084 | 65.3% |
| LOAD_FAST | 90,810 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 88,120 | 16.2% |
| LOAD_CONST | 4,880 | 0.9% |
| STORE_SUBSCR | 1,936 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 267,201 | 49.3% |
| LOAD_CONST | 89,600 | 16.5% |
| RETURN_CONST | 89,392 | 16.5% |
| LOAD_GLOBAL_MODULE | 88,080 | 16.2% |
| STORE_SUBSCR_DICT | 3,460 | 0.6% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,247,929 | 49.6% |
| LOAD_ATTR_SLOT | 1,492,022 | 17.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,062,501 | 12.4% |
| RETURN_VALUE | 964,992 | 11.3% |
| COPY | 397,759 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,788,342 | 67.6% |
| POP_JUMP_IF_TRUE | 2,630,145 | 30.7% |
| EXTENDED_ARG | 100,283 | 1.2% |
| TO_BOOL | 21,221 | 0.2% |
| TO_BOOL_BOOL | 12,078 | 0.1% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 41,548 | 49.9% |
| BINARY_OP | 41,266 | 49.5% |
| LOAD_FAST | 480 | 0.6% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 83,334 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 1,180 | 96.7% |
| CALL | 20 | 1.6% |
| LOAD_FAST | 20 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 98.4% |
| CALL_BUILTIN_CLASS | 20 | 1.6% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,060 | 39.2% |
| TO_BOOL_INT | 960 | 35.5% |
| TO_BOOL_LIST | 620 | 23.0% |
| TO_BOOL | 61 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 980 | 36.3% |
| STORE_DEREF | 880 | 32.6% |
| CALL_PY_EXACT_ARGS | 620 | 23.0% |
| RETURN_VALUE | 140 | 5.2% |
| STORE_FAST | 81 | 3.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 178,426 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 177,300 | 99.4% |
| TO_BOOL_BOOL | 960 | 0.5% |
| TO_BOOL | 166 | 0.1% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 714,653 | 19.7% |
| LOAD_FAST | 586,330 | 16.1% |
| LOAD_GLOBAL_MODULE | 411,629 | 11.3% |
| LOAD_ATTR_WITH_HINT | 272,846 | 7.5% |
| LOAD_CONST | 230,288 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,317,438 | 36.2% |
| TO_BOOL_INT | 566,909 | 15.6% |
| LOAD_CONST | 260,655 | 7.2% |
| COPY | 208,863 | 5.7% |
| BINARY_OP_ADD_FLOAT | 202,486 | 5.6% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,158,324 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 433,567 | 37.4% |
| RETURN_VALUE | 188,814 | 16.3% |
| CALL_LIST_APPEND | 176,880 | 15.3% |
| LOAD_FAST | 129,949 | 11.2% |
| CALL_PY_EXACT_ARGS | 89,960 | 7.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,033,856 | 64.1% |
| LOAD_ATTR_SLOT | 1,347,263 | 12.3% |
| RESUME_CHECK | 536,508 | 4.9% |
| STORE_FAST | 466,174 | 4.2% |
| SWAP | 343,924 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,407,508 | 76.6% |
| STORE_FAST | 1,268,236 | 11.6% |
| BUILD_TUPLE | 512,698 | 4.7% |
| SWAP | 383,181 | 3.5% |
| LOAD_FAST_LOAD_FAST | 184,000 | 1.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 5,764,438 | 39.5% |
| STORE_FAST | 2,585,962 | 17.7% |
| LOAD_FAST | 1,773,014 | 12.2% |
| SWAP | 785,126 | 5.4% |
| BUILD_TUPLE | 660,928 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,612,500 | 59.1% |
| STORE_FAST | 4,078,424 | 28.0% |
| SWAP | 785,126 | 5.4% |
| LOAD_GLOBAL_MODULE | 433,440 | 3.0% |
| BUILD_LIST | 248,000 | 1.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 257,440 | 42.8% |
| LOAD_GLOBAL_MODULE | 176,294 | 29.3% |
| LOAD_ATTR | 88,080 | 14.6% |
| LOAD_CONST | 80,020 | 13.3% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 257,440 | 42.8% |
| CONTAINS_OP | 176,414 | 29.3% |
| LOAD_CONST | 88,020 | 14.6% |
| BINARY_OP | 80,020 | 13.3% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80,770 | 97.6% |
| LOAD_CONST | 2,017 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 81,587 | 98.6% |
| BINARY_SUBSCR | 1,200 | 1.4% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 421,041 | 90.4% |
| LOAD_CONST | 44,590 | 9.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 197,879 | 42.5% |
| BUILD_MAP | 88,000 | 18.9% |
| LOAD_CONST | 88,000 | 18.9% |
| LOAD_FAST | 41,805 | 9.0% |
| LOAD_FAST_LOAD_FAST | 40,465 | 8.7% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,788,038 | 30.3% |
| LOAD_FAST_LOAD_FAST | 2,406,984 | 26.2% |
| CALL | 1,423,733 | 15.5% |
| BUILD_LIST | 512,698 | 5.6% |
| LOAD_GLOBAL_BUILTIN | 458,406 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,720,039 | 29.6% |
| CALL_METHOD_DESCRIPTOR_O | 1,548,367 | 16.9% |
| LOAD_CONST | 1,478,532 | 16.1% |
| BUILD_MAP | 660,928 | 7.2% |
| CONTAINS_OP | 554,401 | 6.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,143,668 | 37.4% |
| LOAD_GLOBAL_MODULE | 3,531,582 | 13.0% |
| LOAD_CONST | 2,586,887 | 9.5% |
| PUSH_NULL | 2,463,871 | 9.1% |
| LOAD_FAST_LOAD_FAST | 2,268,006 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,236,674 | 19.3% |
| RETURN_VALUE | 5,058,728 | 18.6% |
| STORE_FAST | 4,562,009 | 16.8% |
| RESUME_CHECK | 3,978,879 | 14.7% |
| BUILD_TUPLE | 1,423,733 | 5.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 8,843,461 | 75.5% |
| CALL_INTRINSIC_1 | 1,608,448 | 13.7% |
| LOAD_FAST | 979,130 | 8.4% |
| ENTER_EXECUTOR | 97,362 | 0.8% |
| LOAD_ATTR_INSTANCE_VALUE | 88,040 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,709,328 | 48.7% |
| POP_TOP | 2,967,216 | 25.3% |
| RETURN_VALUE | 1,155,570 | 9.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 615,920 | 5.3% |
| UNPACK_SEQUENCE_TUPLE | 431,960 | 3.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 7,957,033 | 100.0% |
| RERAISE | 1,321 | 0.0% |
| RAISE_VARARGS | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 5,764,438 | 72.4% |
| CALL_FUNCTION_EX | 1,608,448 | 20.2% |
| LOAD_CONST | 584,147 | 7.3% |
| RERAISE | 1,322 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,894,434 | 82.8% |
| ENTER_EXECUTOR | 603,039 | 17.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,542,803 | 72.7% |
| MAKE_CELL | 377,113 | 10.8% |
| STORE_FAST | 157,153 | 4.5% |
| RETURN_GENERATOR | 131,134 | 3.7% |
| RETURN_VALUE | 100,410 | 2.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 630,194 | 43.2% |
| LOAD_FAST | 184,656 | 12.6% |
| LOAD_ATTR | 179,922 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 129,043 | 8.8% |
| BINARY_OP | 97,500 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,443,109 | 98.8% |
| COMPARE_OP | 5,797 | 0.4% |
| POP_JUMP_IF_TRUE | 4,956 | 0.3% |
| COMPARE_OP_INT | 3,943 | 0.3% |
| COMPARE_OP_STR | 1,582 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,067,838 | 30.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,673,506 | 26.4% |
| LOAD_ATTR_WITH_HINT | 1,488,965 | 14.7% |
| LOAD_GLOBAL_MODULE | 633,394 | 6.3% |
| BUILD_TUPLE | 554,401 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,537,329 | 74.4% |
| RETURN_VALUE | 1,146,106 | 11.3% |
| POP_JUMP_IF_TRUE | 743,310 | 7.3% |
| COPY | 522,421 | 5.2% |
| SWAP | 176,346 | 1.7% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,148 | 58.4% |
| LOAD_FAST | 1,680 | 19.1% |
| BINARY_SLICE | 1,600 | 18.2% |
| LOAD_GLOBAL_MODULE | 280 | 3.2% |
| LOAD_ATTR | 101 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 8,809 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,203,436 | 40.6% |
| COPY | 1,378,785 | 13.3% |
| CALL_BUILTIN_FAST | 682,590 | 6.6% |
| LOAD_ATTR_SLOT | 608,664 | 5.9% |
| CONTAINS_OP | 522,421 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,919,306 | 18.5% |
| LOAD_ATTR_WITH_HINT | 1,407,840 | 13.6% |
| COPY | 1,378,785 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,360,822 | 13.1% |
| BINARY_SUBSCR_DICT | 1,024,581 | 9.9% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 2,330,377 | 60.4% |
| CALL_PY_EXACT_ARGS | 757,771 | 19.6% |
| CALL | 411,385 | 10.7% |
| BINARY_SUBSCR_GETITEM | 263,960 | 6.8% |
| ENTER_EXECUTOR | 87,200 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,557,949 | 92.2% |
| RETURN_GENERATOR | 297,556 | 7.7% |
| MAKE_CELL | 1,762 | 0.0% |
| RESUME | 1,691 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,063 | 96.2% |
| LOAD_GLOBAL_MODULE | 280 | 3.3% |
| LOAD_GLOBAL | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,854 | 46.0% |
| NOP | 1,707 | 20.4% |
| PUSH_EXC_INFO | 1,630 | 19.4% |
| RETURN_CONST | 1,032 | 12.3% |
| LOAD_GLOBAL_MODULE | 120 | 1.4% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 88,346 | 26.6% |
| CALL | 81,330 | 24.5% |
| STORE_FAST | 40,859 | 12.3% |
| NOP | 40,785 | 12.3% |
| POP_EXCEPT | 40,543 | 12.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 88,642 | 26.7% |
| RETURN_VALUE | 81,330 | 24.5% |
| RETURN_CONST | 81,328 | 24.5% |
| LOAD_FAST | 40,555 | 12.2% |
| ENTER_EXECUTOR | 38,896 | 11.7% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,238,111 | 93.2% |
| RETURN_VALUE | 433,600 | 4.9% |
| LOAD_ATTR_INSTANCE_VALUE | 88,856 | 1.0% |
| LOAD_DEREF | 40,517 | 0.5% |
| LOAD_GLOBAL_MODULE | 40,445 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 8,843,461 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40,445 | 95.6% |
| BUILD_MAP | 724 | 1.7% |
| RETURN_VALUE | 644 | 1.5% |
| MAP_ADD | 240 | 0.6% |
| BUILD_CONST_KEY_MAP | 160 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,189 | 97.3% |
| STORE_FAST | 724 | 1.7% |
| LOAD_DEREF | 160 | 0.4% |
| RETURN_VALUE | 80 | 0.2% |
| BUILD_MAP | 80 | 0.2% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,149,290 | 45.6% |
| POP_JUMP_IF_FALSE | 1,467,266 | 13.0% |
| STORE_SUBSCR_DICT | 929,348 | 8.2% |
| MAP_ADD | 673,342 | 6.0% |
| POP_JUMP_IF_TRUE | 633,513 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,571,244 | 13.9% |
| RESUME_CHECK | 1,482,997 | 13.1% |
| FOR_ITER_LIST | 1,269,274 | 11.2% |
| FOR_ITER_TUPLE | 1,191,851 | 10.6% |
| LOAD_FAST | 955,853 | 8.5% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_WITH_HINT | 431,980 | 28.2% |
| COMPARE_OP_INT | 352,562 | 23.0% |
| IS_OP | 176,160 | 11.5% |
| POP_EXCEPT | 129,240 | 8.4% |
| POP_JUMP_IF_FALSE | 102,149 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 662,932 | 43.3% |
| JUMP_FORWARD | 441,280 | 28.8% |
| ENTER_EXECUTOR | 313,550 | 20.5% |
| POP_JUMP_IF_NOT_NONE | 88,020 | 5.8% |
| LOAD_ATTR | 6,880 | 0.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,605,281 | 75.8% |
| SWAP | 1,205,306 | 19.8% |
| LOAD_FAST | 212,613 | 3.5% |
| JUMP_BACKWARD | 34,881 | 0.6% |
| FOR_ITER | 18,227 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,514,794 | 24.9% |
| LOAD_FAST | 1,347,281 | 22.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 821,257 | 13.5% |
| RETURN_CONST | 802,704 | 13.2% |
| STORE_FAST_LOAD_FAST | 644,032 | 10.6% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 294,103 | 57.1% |
| RETURN_VALUE | 179,667 | 34.9% |
| LOAD_FAST | 19,620 | 3.8% |
| BEFORE_ASYNC_WITH | 10,732 | 2.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 10,612 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 515,338 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 199,820 | 98.7% |
| STORE_NAME | 1,740 | 0.9% |
| STORE_FAST | 880 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 198,080 | 97.8% |
| STORE_NAME | 4,200 | 2.1% |
| PUSH_EXC_INFO | 160 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 201,716 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 199,820 | 99.1% |
| STORE_FAST | 1,196 | 0.6% |
| STORE_NAME | 660 | 0.3% |
| PUSH_EXC_INFO | 40 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,606,270 | 49.3% |
| LOAD_GLOBAL_BUILTIN | 2,533,620 | 27.1% |
| LOAD_GLOBAL_MODULE | 1,101,780 | 11.8% |
| LOAD_CONST | 388,262 | 4.2% |
| LOAD_ATTR_INSTANCE_VALUE | 256,284 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,326,953 | 78.4% |
| POP_JUMP_IF_TRUE | 1,174,985 | 12.6% |
| COPY | 359,462 | 3.8% |
| RETURN_VALUE | 306,825 | 3.3% |
| EXTENDED_ARG | 176,160 | 1.9% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 109,312 | 61.6% |
| STORE_SUBSCR_DICT | 12,532 | 7.1% |
| POP_JUMP_IF_TRUE | 11,764 | 6.6% |
| POP_JUMP_IF_FALSE | 8,181 | 4.6% |
| LIST_APPEND | 6,936 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 92,912 | 52.4% |
| FOR_ITER | 34,881 | 19.7% |
| FOR_ITER_LIST | 20,343 | 11.5% |
| FOR_ITER_TUPLE | 8,140 | 4.6% |
| LOAD_FAST | 7,647 | 4.3% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 580,936 | 99.8% |
| RESUME | 1,239 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 318,901 | 54.8% |
| SEND_GEN | 263,274 | 45.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,418,935 | 39.0% |
| POP_TOP | 1,064,510 | 29.3% |
| EXTENDED_ARG | 441,280 | 12.1% |
| POP_JUMP_IF_FALSE | 194,742 | 5.4% |
| STORE_SUBSCR_DICT | 96,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,505,010 | 68.9% |
| LOAD_GLOBAL_BUILTIN | 432,246 | 11.9% |
| NOP | 259,218 | 7.1% |
| LOAD_CONST | 211,763 | 5.8% |
| LOAD_GLOBAL_MODULE | 100,239 | 2.8% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 160,340 | 30.9% |
| RETURN_VALUE | 128,525 | 24.7% |
| BINARY_SUBSCR_DICT | 88,120 | 17.0% |
| BINARY_OP_ADD_UNICODE | 87,980 | 16.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 46,880 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 512,471 | 98.7% |
| JUMP_BACKWARD | 6,936 | 1.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,688,708 | 83.2% |
| LOAD_ATTR_SLOT | 1,347,263 | 16.8% |
| BINARY_SLICE | 1,760 | 0.0% |
| LOAD_DEREF | 212 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 7,957,033 | 99.0% |
| STORE_FAST | 80,930 | 1.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,442,753 | 71.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,446,206 | 7.2% |
| LOAD_ATTR_SLOT | 1,349,208 | 6.7% |
| LOAD_GLOBAL_MODULE | 1,180,659 | 5.9% |
| LOAD_DEREF | 906,445 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,526,551 | 22.5% |
| PUSH_NULL | 4,033,595 | 20.0% |
| LOAD_FAST | 3,305,760 | 16.4% |
| LOAD_FAST_LOAD_FAST | 1,958,007 | 9.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,170,077 | 5.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,606,718 | 19.1% |
| LOAD_CONST | 6,556,403 | 9.9% |
| POP_JUMP_IF_FALSE | 5,731,785 | 8.7% |
| STORE_ATTR_SLOT | 4,871,442 | 7.4% |
| LOAD_ATTR_SLOT | 2,928,815 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,466,545 | 27.9% |
| LOAD_CONST | 6,556,403 | 9.9% |
| STORE_FAST | 5,122,714 | 7.8% |
| COMPARE_OP_INT | 4,584,861 | 6.9% |
| COMPARE_OP_STR | 3,953,458 | 6.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,119,704 | 12.8% |
| LOAD_GLOBAL_BUILTIN | 1,022,939 | 11.7% |
| POP_TOP | 865,920 | 9.9% |
| POP_JUMP_IF_FALSE | 768,001 | 8.8% |
| LOAD_GLOBAL_MODULE | 738,622 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,053,233 | 12.1% |
| PUSH_NULL | 931,280 | 10.7% |
| CALL_PY_EXACT_ARGS | 915,722 | 10.5% |
| LOAD_ATTR | 906,445 | 10.4% |
| LOAD_DEREF | 708,199 | 8.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 44,985,097 | 14.0% |
| RESUME_CHECK | 44,654,174 | 13.9% |
| POP_JUMP_IF_FALSE | 34,240,929 | 10.7% |
| LOAD_GLOBAL_BUILTIN | 22,726,846 | 7.1% |
| LOAD_CONST | 18,466,545 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 50,297,782 | 15.7% |
| LOAD_ATTR_SLOT | 30,404,680 | 9.5% |
| LOAD_ATTR_WITH_HINT | 17,403,798 | 5.4% |
| LOAD_ATTR | 14,442,753 | 4.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 13,536,104 | 4.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,386,490 | 63.9% |
| LOAD_FAST_AND_CLEAR | 783,848 | 36.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,386,490 | 63.9% |
| LOAD_FAST_AND_CLEAR | 783,848 | 36.1% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 88,020 | 35.4% |
| STORE_ATTR_SLOT | 87,980 | 35.4% |
| LOAD_ATTR_METHOD_NO_DICT | 46,140 | 18.6% |
| POP_TOP | 10,604 | 4.3% |
| JUMP_FORWARD | 5,053 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 177,908 | 71.5% |
| CALL_METHOD_DESCRIPTOR_O | 45,300 | 18.2% |
| POP_JUMP_IF_NOT_NONE | 9,460 | 3.8% |
| LOAD_CONST | 5,620 | 2.3% |
| LOAD_FAST_CHECK | 5,048 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,250,074 | 19.7% |
| NOP | 4,982,124 | 10.6% |
| STORE_ATTR_SLOT | 4,101,064 | 8.8% |
| POP_JUMP_IF_FALSE | 2,749,257 | 5.9% |
| RESUME_CHECK | 2,675,445 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 6,519,688 | 13.9% |
| LOAD_FAST | 5,526,496 | 11.8% |
| BINARY_SUBSCR_DICT | 4,747,782 | 10.1% |
| IS_OP | 4,606,270 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 3,652,008 | 7.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,932 | 11.8% |
| POP_JUMP_IF_FALSE | 11,236 | 10.3% |
| LOAD_FAST | 10,714 | 9.8% |
| RESUME_CHECK | 7,232 | 6.6% |
| RESUME | 7,104 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,622 | 32.6% |
| LOAD_GLOBAL_BUILTIN | 18,804 | 17.2% |
| LOAD_FAST | 16,169 | 14.8% |
| LOAD_ATTR | 14,245 | 13.0% |
| CALL | 7,357 | 6.7% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,420 | 50.9% |
| RESUME | 940 | 14.0% |
| STORE_NAME | 920 | 13.7% |
| LOAD_NAME | 900 | 13.4% |
| POP_TOP | 200 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,300 | 34.2% |
| STORE_NAME | 1,060 | 15.8% |
| LOAD_NAME | 900 | 13.4% |
| CALL | 620 | 9.2% |
| LOAD_ATTR | 600 | 8.9% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,640 | 89.1% |
| EXTENDED_ARG | 120 | 6.5% |
| LOAD_DEREF | 80 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 720 | 39.1% |
| CALL | 300 | 16.3% |
| LOAD_FAST | 260 | 14.1% |
| LOAD_SUPER_ATTR_ATTR | 220 | 12.0% |
| PUSH_NULL | 160 | 8.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,056,341 | 49.4% |
| CALL_PY_WITH_DEFAULTS | 721,253 | 17.3% |
| CALL_PY_EXACT_ARGS | 649,542 | 15.6% |
| CALL_KW | 377,113 | 9.1% |
| CACHE | 267,166 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,056,341 | 49.4% |
| RESUME_CHECK | 2,022,263 | 48.6% |
| RETURN_GENERATOR | 82,226 | 2.0% |
| RESUME | 1,540 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 249,280 | 36.2% |
| STORE_FAST | 168,160 | 24.4% |
| RETURN_VALUE | 88,220 | 12.8% |
| CALL_KW | 88,000 | 12.8% |
| LOAD_ATTR_SLOT | 80,100 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 673,342 | 97.8% |
| LOAD_CONST | 9,120 | 1.3% |
| JUMP_BACKWARD | 5,140 | 0.7% |
| DICT_UPDATE | 240 | 0.0% |
| BUILD_MAP | 160 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 19,631,408 | 30.9% |
| CONTAINS_OP | 7,537,329 | 11.9% |
| IS_OP | 7,326,953 | 11.5% |
| COMPARE_OP_INT | 7,016,079 | 11.1% |
| TO_BOOL | 5,788,342 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,240,929 | 54.0% |
| LOAD_CONST | 5,731,785 | 9.0% |
| LOAD_GLOBAL_MODULE | 5,703,136 | 9.0% |
| RETURN_CONST | 5,029,256 | 7.9% |
| LOAD_GLOBAL_BUILTIN | 2,843,702 | 4.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,638,743 | 70.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,478,804 | 22.6% |
| LOAD_DEREF | 315,672 | 4.8% |
| LOAD_ATTR_WITH_HINT | 95,955 | 1.5% |
| LOAD_GLOBAL_MODULE | 2,914 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,623,936 | 70.7% |
| RETURN_CONST | 674,363 | 10.3% |
| LOAD_GLOBAL_MODULE | 263,865 | 4.0% |
| NOP | 230,494 | 3.5% |
| LOAD_CONST | 203,102 | 3.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,518,651 | 73.8% |
| LOAD_ATTR_INSTANCE_VALUE | 947,420 | 15.5% |
| LOAD_DEREF | 363,342 | 5.9% |
| LOAD_GLOBAL_MODULE | 92,794 | 1.5% |
| EXTENDED_ARG | 88,020 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,148,520 | 35.1% |
| LOAD_FAST_LOAD_FAST | 1,246,749 | 20.4% |
| LOAD_GLOBAL_MODULE | 1,241,381 | 20.3% |
| LOAD_GLOBAL_BUILTIN | 579,338 | 9.5% |
| RETURN_CONST | 421,475 | 6.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,192,700 | 39.9% |
| TO_BOOL | 2,630,145 | 20.2% |
| IS_OP | 1,174,985 | 9.0% |
| TO_BOOL_INT | 929,770 | 7.1% |
| CONTAINS_OP | 743,310 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,285,940 | 48.3% |
| LOAD_CONST | 1,189,254 | 9.1% |
| LOAD_GLOBAL_BUILTIN | 804,940 | 6.2% |
| LOAD_FAST_LOAD_FAST | 770,615 | 5.9% |
| ENTER_EXECUTOR | 633,513 | 4.9% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,001 | 49.0% |
| CALL_KW | 1,520 | 24.8% |
| LOAD_GLOBAL_MODULE | 862 | 14.1% |
| LOAD_CONST | 400 | 6.5% |
| LOAD_FAST | 321 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,886 | 72.3% |
| COPY | 400 | 15.3% |
| LOAD_CONST | 321 | 12.3% |
| CALL_INTRINSIC_1 | 1 | 0.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 179,227 | 49.9% |
| POP_JUMP_IF_TRUE | 177,386 | 49.4% |
| CALL_INTRINSIC_1 | 1,322 | 0.4% |
| POP_JUMP_IF_FALSE | 1,040 | 0.3% |
| DELETE_FAST | 401 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 178,827 | 98.3% |
| PUSH_EXC_INFO | 1,827 | 1.0% |
| CALL_INTRINSIC_1 | 1,321 | 0.7% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,070,452 | 29.2% |
| POP_JUMP_IF_FALSE | 5,029,256 | 24.2% |
| STORE_ATTR_SLOT | 2,328,455 | 11.2% |
| STORE_FAST | 1,580,556 | 7.6% |
| STORE_ATTR_INSTANCE_VALUE | 997,132 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,342,620 | 59.4% |
| INTERPRETER_EXIT | 6,378,201 | 30.7% |
| TO_BOOL_BOOL | 614,270 | 3.0% |
| STORE_FAST | 356,045 | 1.7% |
| RETURN_VALUE | 311,096 | 1.5% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 318,901 | 62.1% |
| LOAD_CONST | 192,890 | 37.5% |
| SEND | 2,100 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 318,445 | 62.0% |
| END_SEND | 190,150 | 37.0% |
| SEND | 2,100 | 0.4% |
| POP_TOP | 1,599 | 0.3% |
| SEND_GEN | 1,597 | 0.3% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80,000 | 45.2% |
| STORE_FAST_LOAD_FAST | 80,000 | 45.2% |
| RETURN_GENERATOR | 8,000 | 4.5% |
| LOAD_FAST | 8,000 | 4.5% |
| JUMP_FORWARD | 880 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 175,180 | 99.0% |
| JUMP_BACKWARD | 1,700 | 1.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,127,918 | 84.2% |
| SET_FUNCTION_ATTRIBUTE | 212,315 | 15.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 522,471 | 39.0% |
| CALL | 272,035 | 20.3% |
| SET_FUNCTION_ATTRIBUTE | 212,315 | 15.8% |
| LOAD_FAST | 196,150 | 14.6% |
| STORE_DEREF | 80,521 | 6.0% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 88,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 88,000 | 100.0% |
| STORE_NAME | 20 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 737,181 | 70.3% |
| LOAD_GLOBAL_MODULE | 265,184 | 25.3% |
| LOAD_FAST_LOAD_FAST | 22,755 | 2.2% |
| LOAD_DEREF | 10,960 | 1.0% |
| STORE_ATTR | 7,940 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 455,812 | 43.5% |
| LOAD_GLOBAL_MODULE | 179,164 | 17.1% |
| LOAD_GLOBAL_BUILTIN | 176,988 | 16.9% |
| LOAD_CONST | 95,703 | 9.1% |
| LOAD_FAST_LOAD_FAST | 91,694 | 8.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 172,732 | 21.6% |
| LOAD_CONST | 130,495 | 16.3% |
| CALL_BUILTIN_CLASS | 89,500 | 11.2% |
| MAKE_FUNCTION | 88,012 | 11.0% |
| JUMP_FORWARD | 88,012 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 268,070 | 33.4% |
| LOAD_CONST | 210,307 | 26.2% |
| LOAD_FAST | 191,786 | 23.9% |
| LOAD_DEREF | 50,017 | 6.2% |
| LOAD_GLOBAL_BUILTIN | 39,847 | 5.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 13,916,507 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 6,967,442 | 8.8% |
| BINARY_SUBSCR_DICT | 6,336,008 | 8.0% |
| FOR_ITER_TUPLE | 5,681,282 | 7.2% |
| LOAD_CONST | 5,122,714 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,985,097 | 56.6% |
| LOAD_FAST_LOAD_FAST | 9,250,074 | 11.6% |
| NOP | 7,421,324 | 9.3% |
| LOAD_GLOBAL_MODULE | 3,458,104 | 4.4% |
| LOAD_CONST | 2,643,307 | 3.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 644,032 | 78.2% |
| COPY | 88,381 | 10.7% |
| FOR_ITER_TUPLE | 46,940 | 5.7% |
| SWAP | 40,223 | 4.9% |
| FOR_ITER_LIST | 3,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 400,160 | 48.6% |
| STORE_ATTR_SLOT | 87,960 | 10.7% |
| LOAD_DEREF | 80,600 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 80,501 | 9.8% |
| SET_ADD | 80,000 | 9.7% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,107,434 | 70.6% |
| UNPACK_SEQUENCE_TUPLE | 1,159,257 | 26.3% |
| UNPACK_EX | 88,000 | 2.0% |
| STORE_FAST_STORE_FAST | 41,029 | 0.9% |
| UNPACK_SEQUENCE | 3,796 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,899,567 | 65.8% |
| STORE_FAST | 1,149,954 | 26.1% |
| NOP | 113,480 | 2.6% |
| LOAD_FAST_LOAD_FAST | 97,380 | 2.2% |
| LOAD_GLOBAL_MODULE | 55,997 | 1.3% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 140 | 30.4% |
| BINARY_OP_SUBTRACT_INT | 140 | 30.4% |
| LOAD_FAST | 80 | 17.4% |
| BINARY_OP | 40 | 8.7% |
| CALL | 40 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 39.1% |
| LOAD_GLOBAL_MODULE | 120 | 26.1% |
| LOAD_FAST | 80 | 17.4% |
| LOAD_GLOBAL | 80 | 17.4% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 4,200 | 29.2% |
| SET_FUNCTION_ATTRIBUTE | 3,580 | 24.9% |
| LOAD_CONST | 1,540 | 10.7% |
| CALL | 1,260 | 8.8% |
| LOAD_NAME | 1,060 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,420 | 44.6% |
| POP_TOP | 2,460 | 17.1% |
| IMPORT_FROM | 1,740 | 12.1% |
| RETURN_CONST | 980 | 6.8% |
| LOAD_NAME | 920 | 6.4% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,940,799 | 31.3% |
| BINARY_OP_ADD_INT | 2,770,599 | 17.5% |
| LOAD_FAST_AND_CLEAR | 1,386,490 | 8.8% |
| SWAP | 1,378,785 | 8.7% |
| BINARY_OP_SUBTRACT_INT | 1,049,923 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,531,728 | 28.7% |
| STORE_ATTR_WITH_HINT | 1,407,840 | 8.9% |
| SWAP | 1,378,785 | 8.7% |
| STORE_ATTR_INSTANCE_VALUE | 1,360,822 | 8.6% |
| STORE_FAST | 1,359,385 | 8.6% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 88,000 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,204 | 25.3% |
| FOR_ITER | 1,861 | 21.4% |
| RETURN_VALUE | 1,421 | 16.3% |
| RETURN_GENERATOR | 808 | 9.3% |
| CALL | 421 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 3,796 | 43.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,040 | 23.5% |
| STORE_FAST | 1,941 | 22.3% |
| UNPACK_SEQUENCE_TUPLE | 520 | 6.0% |
| UNPACK_SEQUENCE | 260 | 3.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 386,269 | 26.1% |
| SEND | 318,445 | 21.5% |
| YIELD_VALUE | 264,533 | 17.8% |
| BUILD_TUPLE | 91,406 | 6.2% |
| LOAD_FAST | 82,030 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,124,290 | 75.8% |
| YIELD_VALUE | 264,533 | 17.8% |
| STORE_FAST | 93,376 | 6.3% |
| UNPACK_SEQUENCE_TUPLE | 200 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 80 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 9,895 | 37.8% |
| CACHE | 7,450 | 28.4% |
| POP_TOP | 2,382 | 9.1% |
| COPY_FREE_VARS | 1,691 | 6.5% |
| MAKE_CELL | 1,540 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,235 | 39.1% |
| LOAD_GLOBAL | 7,104 | 27.1% |
| LOAD_CONST | 1,503 | 5.7% |
| LOAD_FAST_LOAD_FAST | 1,430 | 5.5% |
| NOP | 1,381 | 5.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 323,759 | 27.8% |
| LOAD_ATTR_INSTANCE_VALUE | 272,450 | 23.4% |
| LOAD_FAST_LOAD_FAST | 271,920 | 23.3% |
| BINARY_OP | 202,486 | 17.4% |
| BINARY_OP_MULTIPLY_FLOAT | 87,922 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 471,204 | 40.4% |
| LOAD_FAST | 361,794 | 31.0% |
| STORE_FAST | 330,123 | 28.3% |
| CALL_ALLOC_AND_ENTER_INIT | 1,930 | 0.2% |
| RETURN_VALUE | 320 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,089,927 | 41.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,166,583 | 22.9% |
| CALL | 649,866 | 12.8% |
| LOAD_FAST | 487,896 | 9.6% |
| CALL_LEN | 354,002 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,770,599 | 54.5% |
| RETURN_VALUE | 1,260,532 | 24.8% |
| LOAD_GLOBAL_MODULE | 365,358 | 7.2% |
| LOAD_CONST | 338,021 | 6.6% |
| LOAD_FAST | 112,774 | 2.2% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 110,142 | 42.1% |
| RETURN_VALUE | 89,368 | 34.2% |
| LOAD_FAST_LOAD_FAST | 54,120 | 20.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,301 | 0.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,560 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 108,760 | 41.6% |
| LIST_APPEND | 87,980 | 33.7% |
| LOAD_FAST | 45,482 | 17.4% |
| CALL | 9,400 | 3.6% |
| STORE_FAST | 2,426 | 0.9% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 184,080 | 88.9% |
| LOAD_CONST | 18,299 | 8.8% |
| LOAD_FAST_LOAD_FAST | 4,332 | 2.1% |
| BINARY_OP | 222 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 87,922 | 42.5% |
| LOAD_CONST | 87,900 | 42.5% |
| CALL_BUILTIN_O | 18,815 | 9.1% |
| COMPARE_OP_FLOAT | 7,720 | 3.7% |
| STORE_FAST | 4,352 | 2.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 324,973 | 49.9% |
| LOAD_FAST_LOAD_FAST | 174,923 | 26.9% |
| LOAD_CONST | 96,317 | 14.8% |
| BINARY_OP_ADD_INT | 40,425 | 6.2% |
| LOAD_GLOBAL_MODULE | 12,632 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 325,737 | 50.1% |
| BINARY_OP | 174,983 | 26.9% |
| COMPARE_OP_INT | 87,960 | 13.5% |
| STORE_FAST | 52,249 | 8.0% |
| LOAD_CONST | 6,229 | 1.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 446,052 | 54.7% |
| LOAD_FAST | 175,778 | 21.6% |
| CALL | 87,676 | 10.8% |
| RETURN_VALUE | 78,284 | 9.6% |
| LOAD_ATTR_INSTANCE_VALUE | 15,856 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 292,558 | 35.9% |
| LOAD_CONST | 266,401 | 32.7% |
| SWAP | 175,829 | 21.6% |
| CALL | 57,415 | 7.0% |
| LOAD_FAST | 16,256 | 2.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 782,014 | 40.2% |
| LOAD_FAST | 523,668 | 26.9% |
| BINARY_OP_MULTIPLY_INT | 325,737 | 16.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 263,880 | 13.6% |
| BINARY_OP_SUBTRACT_INT | 40,505 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,049,923 | 53.9% |
| RETURN_VALUE | 326,633 | 16.8% |
| BINARY_OP | 175,323 | 9.0% |
| STORE_FAST | 172,281 | 8.9% |
| BINARY_SUBSCR_LIST_INT | 64,763 | 3.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,747,782 | 46.5% |
| LOAD_FAST | 2,771,218 | 27.2% |
| LOAD_CONST | 1,325,207 | 13.0% |
| COPY | 1,024,581 | 10.0% |
| CALL | 229,049 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,336,008 | 62.1% |
| LOAD_CONST | 1,404,318 | 13.8% |
| RETURN_VALUE | 1,071,572 | 10.5% |
| LOAD_FAST | 661,344 | 6.5% |
| PUSH_EXC_INFO | 187,570 | 1.8% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 574,494 | 98.3% |
| ENTER_EXECUTOR | 7,220 | 1.2% |
| LOAD_CONST | 1,500 | 0.3% |
| LOAD_FAST_LOAD_FAST | 740 | 0.1% |
| BINARY_SUBSCR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320,014 | 54.8% |
| COPY_FREE_VARS | 263,960 | 45.2% |
| BUILD_TUPLE | 160 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 721,433 | 77.6% |
| LOAD_FAST | 79,177 | 8.5% |
| BINARY_OP_SUBTRACT_INT | 64,763 | 7.0% |
| LOAD_FAST_LOAD_FAST | 63,561 | 6.8% |
| BINARY_SUBSCR | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 259,196 | 27.9% |
| LOAD_ATTR_SLOT | 255,579 | 27.5% |
| LOAD_FAST_LOAD_FAST | 117,510 | 12.6% |
| TO_BOOL_BOOL | 88,561 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 63,840 | 6.9% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 233,692 | 96.2% |
| LOAD_FAST_LOAD_FAST | 5,092 | 2.1% |
| LOAD_FAST | 2,860 | 1.2% |
| CALL_BUILTIN_O | 600 | 0.2% |
| ENTER_EXECUTOR | 400 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 207,080 | 85.3% |
| LOAD_ATTR_METHOD_NO_DICT | 31,544 | 13.0% |
| STORE_FAST | 2,760 | 1.1% |
| LIST_APPEND | 620 | 0.3% |
| PUSH_EXC_INFO | 440 | 0.2% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,482,671 | 99.8% |
| LOAD_FAST_LOAD_FAST | 2,904 | 0.2% |
| BINARY_SUBSCR | 640 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 688,240 | 46.3% |
| LOAD_ATTR_SLOT | 226,178 | 15.2% |
| CALL_BUILTIN_O | 176,880 | 11.9% |
| STORE_FAST | 102,366 | 6.9% |
| RETURN_VALUE | 99,510 | 6.7% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 177,163 | 59.6% |
| LOAD_FAST_LOAD_FAST | 93,450 | 31.4% |
| LOAD_FAST | 8,562 | 2.9% |
| LOAD_CONST | 8,000 | 2.7% |
| LOAD_GLOBAL_MODULE | 2,234 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 295,051 | 99.3% |
| COPY_FREE_VARS | 1,144 | 0.4% |
| POP_TOP | 920 | 0.3% |
| RESUME | 40 | 0.0% |
| STORE_FAST | 20 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 42,592 | 32.7% |
| LOAD_CONST | 24,217 | 18.6% |
| LOAD_FAST | 19,472 | 14.9% |
| PUSH_NULL | 16,044 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 10,727 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 103,441 | 79.4% |
| POP_TOP | 11,985 | 9.2% |
| GET_AWAITABLE | 10,612 | 8.1% |
| COPY_FREE_VARS | 2,105 | 1.6% |
| MAKE_CELL | 829 | 0.6% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,089,364 | 29.3% |
| LOAD_FAST | 1,990,429 | 27.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,086,752 | 15.3% |
| LOAD_ATTR_SLOT | 952,040 | 13.4% |
| PUSH_NULL | 437,644 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,058,206 | 28.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,276,180 | 17.9% |
| LOAD_FAST | 1,067,520 | 15.0% |
| CALL | 976,999 | 13.7% |
| GET_ITER | 796,925 | 11.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,142,977 | 58.9% |
| LOAD_FAST_LOAD_FAST | 407,814 | 21.0% |
| BUILD_TUPLE | 167,920 | 8.7% |
| LOAD_GLOBAL_MODULE | 88,200 | 4.5% |
| LOAD_FAST | 71,079 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 682,590 | 35.2% |
| TO_BOOL_BOOL | 492,125 | 25.4% |
| POP_TOP | 235,557 | 12.1% |
| RETURN_VALUE | 230,055 | 11.9% |
| STORE_FAST | 135,474 | 7.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,276,180 | 56.7% |
| LOAD_FAST | 527,340 | 23.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 168,080 | 7.5% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 88,000 | 3.9% |
| LOAD_ATTR | 83,702 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,166,583 | 51.8% |
| STORE_FAST | 423,372 | 18.8% |
| RETURN_VALUE | 299,809 | 13.3% |
| POP_TOP | 93,543 | 4.2% |
| LOAD_ATTR_METHOD_NO_DICT | 88,000 | 3.9% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 459,532 | 29.0% |
| LOAD_ATTR_INSTANCE_VALUE | 408,486 | 25.7% |
| BINARY_SUBSCR_TUPLE_INT | 176,880 | 11.1% |
| RETURN_GENERATOR | 118,296 | 7.5% |
| LOAD_ATTR_SLOT | 118,140 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 551,050 | 34.7% |
| RETURN_VALUE | 443,497 | 28.0% |
| STORE_FAST | 333,313 | 21.0% |
| LOAD_FAST | 90,350 | 5.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 87,261 | 5.5% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,842,266 | 41.1% |
| LOAD_GLOBAL_MODULE | 1,423,152 | 31.8% |
| LOAD_FAST_LOAD_FAST | 442,688 | 9.9% |
| LOAD_ATTR | 376,602 | 8.4% |
| BUILD_TUPLE | 279,626 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,035,653 | 90.1% |
| RETURN_VALUE | 277,828 | 6.2% |
| COPY | 159,658 | 3.6% |
| TO_BOOL | 2,460 | 0.1% |
| YIELD_VALUE | 2,020 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,475,454 | 62.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,284,529 | 23.1% |
| LOAD_ATTR_SLOT | 432,280 | 7.8% |
| LOAD_ATTR_WITH_HINT | 359,594 | 6.5% |
| LOAD_DEREF | 4,600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,060,910 | 37.0% |
| LOAD_CONST | 1,186,618 | 21.3% |
| RETURN_VALUE | 884,285 | 15.9% |
| LOAD_FAST | 389,461 | 7.0% |
| BINARY_OP_ADD_INT | 354,002 | 6.4% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 271,787 | 41.3% |
| BUILD_CONST_KEY_MAP | 176,880 | 26.9% |
| ENTER_EXECUTOR | 88,049 | 13.4% |
| BUILD_TUPLE | 65,878 | 10.0% |
| BINARY_SLICE | 40,425 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 299,079 | 45.5% |
| ENTER_EXECUTOR | 153,497 | 23.3% |
| NOP | 90,724 | 13.8% |
| LOAD_FAST_LOAD_FAST | 89,000 | 13.5% |
| RETURN_CONST | 10,400 | 1.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,454,935 | 40.8% |
| LOAD_CONST | 2,199,748 | 36.6% |
| BUILD_TUPLE | 527,960 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 435,522 | 7.2% |
| LOAD_ATTR_INSTANCE_VALUE | 104,580 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,969,730 | 82.6% |
| BINARY_OP_SUBTRACT_INT | 263,880 | 4.4% |
| POP_TOP | 179,658 | 3.0% |
| CALL_METHOD_DESCRIPTOR_O | 167,960 | 2.8% |
| LOAD_FAST | 99,620 | 1.7% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 305,731 | 39.7% |
| LOAD_FAST_LOAD_FAST | 233,233 | 30.3% |
| LOAD_ATTR_METHOD_NO_DICT | 132,747 | 17.2% |
| LOAD_CONST | 57,137 | 7.4% |
| LOAD_ATTR | 41,226 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 347,038 | 45.0% |
| STORE_FAST | 330,449 | 42.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 88,000 | 11.4% |
| GET_ITER | 1,880 | 0.2% |
| RETURN_VALUE | 1,320 | 0.2% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,542,869 | 84.7% |
| LOAD_ATTR | 1,170,077 | 15.2% |
| CALL | 3,980 | 0.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,599 | 0.0% |
| LOAD_FAST | 1,444 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,530,768 | 32.8% |
| POP_TOP | 1,322,205 | 17.1% |
| CALL_BUILTIN_CLASS | 1,086,752 | 14.1% |
| TO_BOOL_BOOL | 975,305 | 12.6% |
| STORE_FAST | 814,485 | 10.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,388,985 | 67.2% |
| BUILD_TUPLE | 1,548,367 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 337,880 | 4.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 167,960 | 2.1% |
| CALL | 155,766 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,643,415 | 95.3% |
| RETURN_VALUE | 168,160 | 2.1% |
| LOAD_CONST | 101,741 | 1.3% |
| STORE_FAST | 45,628 | 0.6% |
| BUILD_LIST | 40,365 | 0.5% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,835,022 | 35.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,600,987 | 25.2% |
| CALL_TYPE_1 | 4,525,308 | 15.0% |
| LOAD_FAST_LOAD_FAST | 1,610,216 | 5.3% |
| LOAD_DEREF | 915,722 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 28,596,516 | 94.7% |
| COPY_FREE_VARS | 757,771 | 2.5% |
| MAKE_CELL | 649,542 | 2.2% |
| RETURN_GENERATOR | 103,153 | 0.3% |
| TO_BOOL_BOOL | 86,674 | 0.3% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,089,052 | 45.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 481,833 | 19.9% |
| ENTER_EXECUTOR | 353,585 | 14.6% |
| LOAD_ATTR_INSTANCE_VALUE | 177,022 | 7.3% |
| LOAD_FAST_LOAD_FAST | 90,500 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,614,451 | 66.6% |
| MAKE_CELL | 721,253 | 29.8% |
| RETURN_GENERATOR | 84,585 | 3.5% |
| CALL | 1,060 | 0.0% |
| STORE_FAST | 1,040 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 88,000 | 34.2% |
| CALL_TYPE_1 | 87,960 | 34.2% |
| LOAD_ATTR | 75,675 | 29.4% |
| LOAD_FAST | 2,970 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,301 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 88,000 | 34.2% |
| CONTAINS_OP | 87,980 | 34.2% |
| BUILD_TUPLE | 75,695 | 29.4% |
| STORE_FAST | 4,111 | 1.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 640 | 0.2% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 176,440 | 48.6% |
| CALL_BUILTIN_CLASS | 88,760 | 24.4% |
| STORE_FAST | 87,960 | 24.2% |
| LOAD_FAST | 8,410 | 2.3% |
| LOAD_GLOBAL_MODULE | 680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 176,680 | 48.6% |
| CALL_STR_1 | 88,000 | 24.2% |
| BINARY_OP | 87,980 | 24.2% |
| LOAD_FAST_LOAD_FAST | 6,970 | 1.9% |
| STORE_FAST | 1,240 | 0.3% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,607,639 | 98.8% |
| BINARY_SUBSCR_TUPLE_INT | 87,960 | 1.1% |
| CALL | 780 | 0.0% |
| LOAD_GLOBAL_MODULE | 640 | 0.0% |
| LOAD_DEREF | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,525,308 | 58.8% |
| STORE_FAST | 1,914,220 | 24.9% |
| LOAD_GLOBAL_BUILTIN | 484,780 | 6.3% |
| LOAD_GLOBAL_MODULE | 238,636 | 3.1% |
| LOAD_FAST | 180,552 | 2.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 534,876 | 31.3% |
| LOAD_CONST | 430,988 | 25.2% |
| LOAD_FAST | 337,557 | 19.7% |
| BINARY_OP | 181,571 | 10.6% |
| COPY | 174,923 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,175,440 | 68.7% |
| RETURN_VALUE | 534,056 | 31.2% |
| POP_JUMP_IF_TRUE | 920 | 0.1% |
| EXTENDED_ARG | 302 | 0.0% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,584,861 | 56.5% |
| LOAD_FAST_LOAD_FAST | 1,695,939 | 20.9% |
| LOAD_ATTR_INSTANCE_VALUE | 506,040 | 6.2% |
| LOAD_GLOBAL_MODULE | 363,258 | 4.5% |
| LOAD_ATTR_WITH_HINT | 183,302 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,016,079 | 86.5% |
| POP_JUMP_IF_TRUE | 738,044 | 9.1% |
| EXTENDED_ARG | 352,562 | 4.3% |
| RETURN_VALUE | 3,321 | 0.0% |
| COPY | 947 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,953,458 | 71.2% |
| LOAD_FAST | 603,358 | 10.9% |
| LOAD_FAST_LOAD_FAST | 456,020 | 8.2% |
| LOAD_GLOBAL_MODULE | 360,259 | 6.5% |
| LOAD_ATTR_INSTANCE_VALUE | 90,460 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,087,214 | 91.6% |
| POP_JUMP_IF_TRUE | 369,540 | 6.7% |
| RETURN_VALUE | 88,040 | 1.6% |
| COPY | 7,243 | 0.1% |
| EXTENDED_ARG | 2,920 | 0.1% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 92,912 | 95.0% |
| GET_ITER | 3,486 | 3.6% |
| SWAP | 919 | 0.9% |
| FOR_ITER | 262 | 0.3% |
| EXTENDED_ARG | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 92,912 | 95.0% |
| POP_TOP | 4,405 | 4.5% |
| RETURN_CONST | 240 | 0.2% |
| STORE_FAST | 160 | 0.2% |
| RESUME | 102 | 0.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,076,717 | 60.3% |
| ENTER_EXECUTOR | 1,269,274 | 36.9% |
| SWAP | 44,605 | 1.3% |
| LOAD_FAST | 24,528 | 0.7% |
| JUMP_BACKWARD | 20,343 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,272,361 | 37.0% |
| STORE_FAST | 1,131,888 | 32.9% |
| RETURN_CONST | 882,100 | 25.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 137,292 | 4.0% |
| LOAD_GLOBAL_BUILTIN | 4,302 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 247,554 | 54.6% |
| GET_ITER | 201,300 | 44.4% |
| JUMP_BACKWARD | 3,519 | 0.8% |
| FOR_ITER | 300 | 0.1% |
| LOAD_FAST | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 233,273 | 51.5% |
| STORE_FAST | 204,701 | 45.2% |
| LOAD_FAST | 7,489 | 1.7% |
| LOAD_GLOBAL_BUILTIN | 6,950 | 1.5% |
| RETURN_CONST | 260 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,406,830 | 78.0% |
| ENTER_EXECUTOR | 1,191,851 | 17.2% |
| LOAD_FAST | 185,796 | 2.7% |
| SWAP | 135,460 | 2.0% |
| JUMP_BACKWARD | 8,140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,681,282 | 82.0% |
| LOAD_FAST | 761,950 | 11.0% |
| RETURN_CONST | 182,973 | 2.6% |
| SWAP | 135,580 | 2.0% |
| ENTER_EXECUTOR | 80,200 | 1.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 248,415 | 54.2% |
| LOAD_ATTR_MODULE | 202,647 | 44.2% |
| LOAD_FAST | 3,244 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 2,176 | 0.5% |
| ENTER_EXECUTOR | 1,060 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 162,740 | 35.5% |
| COMPARE_OP_INT | 121,677 | 26.6% |
| CALL_PY_EXACT_ARGS | 81,266 | 17.7% |
| LOAD_FAST | 45,915 | 10.0% |
| CALL | 41,508 | 9.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,297,782 | 87.4% |
| LOAD_FAST_LOAD_FAST | 3,652,008 | 6.3% |
| COPY | 1,360,822 | 2.4% |
| LOAD_ATTR_SLOT | 1,312,282 | 2.3% |
| LOAD_DEREF | 648,450 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,711,739 | 15.1% |
| LOAD_ATTR_METHOD_NO_DICT | 7,302,522 | 12.7% |
| STORE_FAST | 6,967,442 | 12.1% |
| TO_BOOL_BOOL | 5,063,189 | 8.8% |
| RETURN_VALUE | 3,857,021 | 6.7% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 263,900 | 100.0% |
| LOAD_FAST | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 263,920 | 100.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,443,801 | 39.5% |
| LOAD_ATTR_INSTANCE_VALUE | 7,302,522 | 27.7% |
| LOAD_ATTR_WITH_HINT | 5,452,665 | 20.6% |
| LOAD_ATTR_SLOT | 1,801,136 | 6.8% |
| RETURN_VALUE | 528,163 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,630,379 | 51.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,542,869 | 24.8% |
| LOAD_CONST | 2,631,282 | 10.0% |
| LOAD_FAST_LOAD_FAST | 1,388,148 | 5.3% |
| CALL | 977,962 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,536,104 | 66.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,437,381 | 12.1% |
| LOAD_ATTR_SLOT | 1,521,696 | 7.5% |
| LOAD_ATTR_WITH_HINT | 1,222,192 | 6.0% |
| LOAD_DEREF | 542,835 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 7,600,987 | 37.6% |
| LOAD_GLOBAL_BUILTIN | 4,670,381 | 23.1% |
| LOAD_FAST | 4,067,047 | 20.1% |
| LOAD_FAST_LOAD_FAST | 1,625,534 | 8.0% |
| LOAD_GLOBAL_MODULE | 801,714 | 4.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,606,382 | 96.7% |
| LOAD_FAST | 142,937 | 1.8% |
| LOAD_ATTR_MODULE | 105,012 | 1.3% |
| LOAD_ATTR | 13,247 | 0.2% |
| BINARY_SUBSCR_DICT | 1,778 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,239,459 | 79.3% |
| LOAD_FAST | 319,078 | 4.1% |
| LOAD_ATTR_CLASS | 202,647 | 2.6% |
| LOAD_ATTR | 183,372 | 2.3% |
| BINARY_OP | 148,584 | 1.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840 | 77.4% |
| LOAD_FAST_LOAD_FAST | 864 | 17.4% |
| LOAD_ATTR | 180 | 3.6% |
| LOAD_CONST | 80 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,590 | 32.0% |
| TO_BOOL_BOOL | 1,126 | 22.7% |
| LOAD_FAST | 944 | 19.0% |
| CALL_BUILTIN_FAST | 864 | 17.4% |
| CALL | 240 | 4.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 203,610 | 60.5% |
| LOAD_FAST | 89,050 | 26.5% |
| LOAD_FAST_LOAD_FAST | 43,186 | 12.8% |
| LOAD_ATTR | 700 | 0.2% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 123,064 | 36.6% |
| COMPARE_OP_INT | 80,950 | 24.0% |
| LOAD_FAST | 42,070 | 12.5% |
| LOAD_CONST | 40,625 | 12.1% |
| STORE_FAST | 40,525 | 12.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,420,782 | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE | 177,924 | 6.5% |
| RETURN_VALUE | 101,012 | 3.7% |
| ENTER_EXECUTOR | 22,960 | 0.8% |
| LOAD_ATTR | 2,577 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,727,106 | 99.9% |
| COPY_FREE_VARS | 1,848 | 0.1% |
| LOAD_GLOBAL_MODULE | 382 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 60 | 0.0% |
| LOAD_ATTR_PROPERTY | 60 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,404,680 | 92.4% |
| LOAD_FAST_LOAD_FAST | 946,976 | 2.9% |
| STORE_FAST_LOAD_FAST | 400,160 | 1.2% |
| COPY | 359,729 | 1.1% |
| BINARY_SUBSCR_LIST_INT | 255,579 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,779,040 | 11.5% |
| TO_BOOL_NONE | 3,203,511 | 9.7% |
| LOAD_CONST | 2,928,815 | 8.9% |
| STORE_FAST | 2,879,822 | 8.7% |
| LOAD_FAST | 2,502,893 | 7.6% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,403,798 | 82.7% |
| COPY | 1,407,840 | 6.7% |
| LOAD_FAST_LOAD_FAST | 1,159,561 | 5.5% |
| LOAD_DEREF | 447,218 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 440,640 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,452,665 | 25.9% |
| LOAD_FAST | 3,746,591 | 17.8% |
| TO_BOOL_BOOL | 2,593,004 | 12.3% |
| LOAD_CONST | 1,952,628 | 9.3% |
| RETURN_VALUE | 1,849,845 | 8.8% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,614,373 | 26.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,670,381 | 12.7% |
| LOAD_FAST | 4,299,147 | 11.7% |
| POP_JUMP_IF_FALSE | 2,843,702 | 7.7% |
| STORE_FAST | 2,542,285 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,726,846 | 61.9% |
| IS_OP | 2,533,620 | 6.9% |
| LOAD_GLOBAL_BUILTIN | 2,324,701 | 6.3% |
| CALL_BUILTIN_CLASS | 2,089,364 | 5.7% |
| CALL_ISINSTANCE | 1,842,266 | 5.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,602,904 | 20.0% |
| LOAD_FAST | 5,931,510 | 13.8% |
| POP_JUMP_IF_FALSE | 5,703,136 | 13.2% |
| STORE_FAST | 3,458,104 | 8.0% |
| LOAD_GLOBAL_MODULE | 3,277,721 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,209,600 | 35.3% |
| LOAD_ATTR_MODULE | 7,606,382 | 17.7% |
| CALL | 3,531,582 | 8.2% |
| LOAD_GLOBAL_MODULE | 3,277,721 | 7.6% |
| LOAD_FAST_LOAD_FAST | 2,460,147 | 5.7% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,592 | 91.4% |
| LOAD_SUPER_ATTR | 220 | 5.6% |
| EXTENDED_ARG | 120 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,044 | 52.0% |
| LOAD_GLOBAL_MODULE | 1,848 | 47.0% |
| LOAD_GLOBAL | 40 | 1.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 637,403 | 99.9% |
| LOAD_SUPER_ATTR | 720 | 0.1% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400,470 | 62.7% |
| LOAD_FAST_LOAD_FAST | 194,043 | 30.4% |
| CALL_PY_EXACT_ARGS | 42,949 | 6.7% |
| CALL | 380 | 0.1% |
| LOAD_CONST | 301 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 28,596,516 | 37.5% |
| CACHE | 22,015,133 | 28.9% |
| CALL_FUNCTION_EX | 5,709,328 | 7.5% |
| CALL | 3,978,879 | 5.2% |
| COPY_FREE_VARS | 3,557,949 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,654,174 | 58.6% |
| LOAD_GLOBAL_BUILTIN | 9,614,373 | 12.6% |
| LOAD_GLOBAL_MODULE | 8,602,904 | 11.3% |
| NOP | 5,260,662 | 6.9% |
| LOAD_FAST_LOAD_FAST | 2,675,445 | 3.5% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 324,209 | 55.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 263,274 | 44.7% |
| SEND | 1,597 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 324,869 | 55.1% |
| RESUME_CHECK | 263,024 | 44.6% |
| RESUME | 947 | 0.2% |
| END_SEND | 160 | 0.0% |
| YIELD_VALUE | 80 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,318,728 | 69.7% |
| LOAD_FAST_LOAD_FAST | 1,602,601 | 15.3% |
| SWAP | 1,360,822 | 13.0% |
| LOAD_DEREF | 85,262 | 0.8% |
| BINARY_SUBSCR_DICT | 79,960 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,719,933 | 25.9% |
| LOAD_CONST | 2,704,461 | 25.7% |
| RETURN_CONST | 997,132 | 9.5% |
| LOAD_FAST_LOAD_FAST | 902,330 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 847,150 | 8.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,149,047 | 53.8% |
| LOAD_FAST_LOAD_FAST | 6,519,688 | 43.1% |
| SWAP | 359,729 | 2.4% |
| STORE_FAST_LOAD_FAST | 87,960 | 0.6% |
| STORE_ATTR_SLOT | 16,842 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,871,442 | 32.2% |
| LOAD_FAST_LOAD_FAST | 4,101,064 | 27.1% |
| LOAD_FAST | 2,494,870 | 16.5% |
| RETURN_CONST | 2,328,455 | 15.4% |
| LOAD_GLOBAL_BUILTIN | 704,944 | 4.7% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,407,840 | 99.2% |
| LOAD_FAST_LOAD_FAST | 7,351 | 0.5% |
| LOAD_DEREF | 1,404 | 0.1% |
| LOAD_FAST | 1,044 | 0.1% |
| STORE_ATTR | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 983,926 | 69.4% |
| EXTENDED_ARG | 431,980 | 30.4% |
| RETURN_CONST | 1,040 | 0.1% |
| LOAD_CONST | 513 | 0.0% |
| LOAD_GLOBAL_MODULE | 360 | 0.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,105,658 | 24.7% |
| SWAP | 1,024,581 | 22.9% |
| LOAD_CONST | 885,296 | 19.8% |
| LOAD_FAST_LOAD_FAST | 810,740 | 18.1% |
| LOAD_ATTR_SLOT | 496,480 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,793,652 | 40.1% |
| ENTER_EXECUTOR | 929,348 | 20.8% |
| LOAD_FAST_LOAD_FAST | 881,434 | 19.7% |
| RETURN_CONST | 189,437 | 4.2% |
| LOAD_CONST | 178,099 | 4.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 118,710 | 70.5% |
| LOAD_CONST | 41,065 | 24.4% |
| LOAD_ATTR_INSTANCE_VALUE | 7,960 | 4.7% |
| LOAD_FAST | 320 | 0.2% |
| STORE_SUBSCR | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 59,950 | 35.6% |
| LOAD_FAST_LOAD_FAST | 56,980 | 33.8% |
| LOAD_DEREF | 48,425 | 28.8% |
| RETURN_CONST | 1,460 | 0.9% |
| JUMP_BACKWARD | 940 | 0.6% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 440,722 | 53.0% |
| LOAD_FAST | 378,527 | 45.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8,644 | 1.0% |
| CALL | 1,000 | 0.1% |
| TO_BOOL | 800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 474,674 | 57.1% |
| POP_JUMP_IF_TRUE | 356,455 | 42.9% |
| TO_BOOL_NONE | 126 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,340,340 | 21.5% |
| LOAD_ATTR_INSTANCE_VALUE | 5,063,189 | 20.4% |
| CALL_ISINSTANCE | 4,035,653 | 16.3% |
| LOAD_ATTR_WITH_HINT | 2,593,004 | 10.4% |
| COPY | 1,919,306 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,631,408 | 79.1% |
| POP_JUMP_IF_TRUE | 5,192,700 | 20.9% |
| EXTENDED_ARG | 2,250 | 0.0% |
| UNARY_NOT | 1,060 | 0.0% |
| TO_BOOL_INT | 20 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 566,909 | 33.3% |
| COPY | 531,428 | 31.2% |
| LOAD_FAST | 215,205 | 12.6% |
| RETURN_VALUE | 174,750 | 10.3% |
| LOAD_GLOBAL_MODULE | 96,518 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 929,770 | 54.6% |
| POP_JUMP_IF_FALSE | 771,234 | 45.3% |
| UNARY_NOT | 960 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 874,415 | 57.7% |
| LOAD_FAST | 451,273 | 29.8% |
| LOAD_ATTR_WITH_HINT | 187,339 | 12.4% |
| TO_BOOL | 940 | 0.1% |
| STORE_FAST_LOAD_FAST | 700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,503,577 | 99.2% |
| POP_JUMP_IF_TRUE | 11,848 | 0.8% |
| UNARY_NOT | 620 | 0.0% |
| EXTENDED_ARG | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 3,203,511 | 76.9% |
| LOAD_FAST | 421,067 | 10.1% |
| WITH_EXCEPT_START | 177,300 | 4.3% |
| LOAD_ATTR | 150,638 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 102,379 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,785,773 | 90.9% |
| POP_JUMP_IF_TRUE | 379,080 | 9.1% |
| EXTENDED_ARG | 380 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 284,474 | 50.5% |
| LOAD_ATTR | 87,960 | 15.6% |
| LOAD_ATTR_WITH_HINT | 80,922 | 14.4% |
| COPY | 48,792 | 8.7% |
| STORE_FAST_LOAD_FAST | 46,880 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 325,479 | 57.8% |
| POP_JUMP_IF_TRUE | 226,510 | 40.2% |
| EXTENDED_ARG | 11,220 | 2.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 40 | 66.7% |
| UNPACK_SEQUENCE | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 530,398 | 42.7% |
| CALL_FUNCTION_EX | 431,960 | 34.8% |
| RETURN_VALUE | 90,901 | 7.3% |
| END_SEND | 88,242 | 7.1% |
| CALL_BUILTIN_FAST | 40,425 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,159,257 | 93.3% |
| STORE_FAST | 82,790 | 6.7% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 889,488 | 27.0% |
| FOR_ITER | 821,257 | 24.9% |
| CALL_FUNCTION_EX | 615,920 | 18.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 353,802 | 10.7% |
| FOR_ITER_LIST | 137,292 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 3,107,434 | 94.3% |
| STORE_FAST | 98,780 | 3.0% |
| LOAD_FAST_LOAD_FAST | 87,980 | 2.7% |
| LOAD_FAST | 2,242 | 0.1% |
| STORE_DEREF | 200 | 0.0% |


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
|     deferred | 3,613,787 | 26.0% |
|          hit | 10,243,268 | 73.8% |
|         miss | 6,848 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,704 | 22.1% |
| Failure | 16,538 | 77.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,999 | 24.2% |
| or | 2,315 | 14.0% |
| multiply different types | 2,302 | 13.9% |
| add other | 1,705 | 10.3% |
| true divide different types | 1,700 | 10.3% |
| remainder | 920 | 5.6% |
| add different types | 864 | 5.2% |
| subtract different types | 844 | 5.1% |
| true divide other | 442 | 2.7% |
| true divide float | 400 | 2.4% |
| floor divide | 260 | 1.6% |
| lshift | 200 | 1.2% |
| power | 200 | 1.2% |
| subtract other | 160 | 1.0% |
| rshift | 127 | 0.8% |
| and other | 80 | 0.5% |
| and different types | 20 | 0.1% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> specialization stats for BINARY_OP_INPLACE_ADD_UNICODE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|         miss | 220 | 0.2% |


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
|     deferred | 1,421,607 | 9.6% |
|          hit | 13,441,212 | 90.4% |
|         miss | 1,620 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,800 | 50.1% |
| Failure | 4,784 | 49.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 3,207 | 67.0% |
| buffer int | 957 | 20.0% |
| code complex parameters | 400 | 8.4% |
| out of range | 200 | 4.2% |
| list slice | 20 | 0.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,014,986 | 23.5% |
|          hit | 87,161,313 | 76.0% |
|         miss | 439,867 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 58,355 | 45.5% |
| Failure | 69,948 | 54.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 16,092 | 23.0% |
| cfunc noargs | 13,806 | 19.7% |
| class no vectorcall | 8,289 | 11.9% |
| meth descr varargs | 5,288 | 7.6% |
| meth descr method fastcall keywords | 4,080 | 5.8% |
| meth descr varargs keywords | 4,032 | 5.8% |
| cfunc varargs keywords | 4,025 | 5.8% |
| cfunc varargs | 3,873 | 5.5% |
| other | 3,849 | 5.5% |
| no dict | 2,277 | 3.3% |
| class mutable | 1,397 | 2.0% |
| wrong number arguments | 1,340 | 1.9% |
| operator wrapper | 620 | 0.9% |
| init not simple | 580 | 0.8% |
| cmethod | 260 | 0.4% |
| init not python | 100 | 0.1% |
| str | 20 | 0.0% |
| method wrapper | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,447,880 | 8.6% |
|          hit | 15,350,320 | 91.2% |
|         miss | 27,533 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,005 | 49.0% |
| Failure | 6,242 | 51.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 2,009 | 32.2% |
| long float | 1,027 | 16.5% |
| baseobject | 1,018 | 16.3% |
| big int | 828 | 13.3% |
| different types | 720 | 11.5% |
| other | 520 | 8.3% |
| tuple | 80 | 1.3% |
| bool | 40 | 0.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,056,239 | 35.6% |
|          hit | 10,921,718 | 64.2% |
|         miss | 400 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,704 | 16.9% |
| Failure | 18,227 | 83.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 9,110 | 50.0% |
| dict items | 5,026 | 27.6% |
| zip | 840 | 4.6% |
| dict keys | 820 | 4.5% |
| dict values | 740 | 4.1% |
| other | 480 | 2.6% |
| enumerate | 370 | 2.0% |
| itertools | 360 | 2.0% |
| bytes | 200 | 1.1% |
| reversed list | 141 | 0.8% |
| map | 120 | 0.7% |
| ascii string | 20 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,325,786 | 10.7% |
|        deopt | 357,272 | 0.2% |
|          hit | 167,805,325 | 88.3% |
|         miss | 1,997,311 | 1.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 118,479 | 65.0% |
| Failure | 63,782 | 35.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 19,312 | 30.3% |
| method | 17,900 | 28.1% |
| metaclass attribute | 7,895 | 12.4% |
| not managed dict | 7,750 | 12.2% |
| module attr not found | 2,340 | 3.7% |
| shadowed | 2,100 | 3.3% |
| overridden | 1,442 | 2.3% |
| class attr descriptor | 1,280 | 2.0% |
| mutable class | 1,041 | 1.6% |
| non object slot | 822 | 1.3% |
| non overriding descriptor | 820 | 1.3% |
| class method obj | 540 | 0.8% |
| builtin class method | 200 | 0.3% |
| class attr simple | 200 | 0.3% |
| not in keys | 80 | 0.1% |
| property | 60 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 55,284 | 0.1% |
|        deopt | 1,060 | 0.0% |
|          hit | 79,734,091 | 99.8% |
|         miss | 11,804 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 54,966 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 900 | 0.1% |
|          hit | 642,135 | 99.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 940 | 100.0% |
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
|     deferred | 510,194 | 46.3% |
|          hit | 588,840 | 53.4% |
|         miss | 240 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,597 | 43.2% |
| Failure | 2,100 | 56.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 1,860 | 88.6% |
| dict keys | 240 | 11.4% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,002,491 | 3.6% |
|          hit | 26,152,896 | 93.0% |
|         miss | 907,111 | 3.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 37,830 | 82.7% |
| Failure | 7,940 | 17.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 3,420 | 43.1% |
| property | 1,440 | 18.1% |
| overridden | 1,080 | 13.6% |
| method | 740 | 9.3% |
| not in keys | 480 | 6.0% |
| class attr simple | 360 | 4.5% |
| not managed dict | 160 | 2.0% |
| overriding descriptor | 140 | 1.8% |
| no dict | 120 | 1.5% |


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
|     deferred | 536,793 | 10.4% |
|          hit | 4,637,892 | 89.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,620 | 65.2% |
| Failure | 1,936 | 34.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 1,140 | 58.9% |
| py simple | 776 | 40.1% |
| other | 20 | 1.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,518,565 | 20.2% |
|          hit | 33,587,114 | 79.7% |
|         miss | 18,210 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 18,368 | 46.4% |
| Failure | 21,221 | 53.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 6,327 | 29.8% |
| set | 5,740 | 27.0% |
| tuple | 3,220 | 15.2% |
| sequence | 2,497 | 11.8% |
| mapping | 1,185 | 5.6% |
| bytes | 885 | 4.2% |
| float | 862 | 4.1% |
| other | 300 | 1.4% |
| bytearray | 185 | 0.9% |
| number | 20 | 0.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,857 | 0.1% |
|          hit | 4,538,803 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,580 | 90.8% |
| Failure | 260 | 9.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| iterator | 260 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 887,889,327 | 56.1% |
| Not specialized | 160,705,491 | 10.2% |
| Specialized hits | 530,802,465 | 33.5% |
| Specialized misses | 3,416,497 | 0.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 27,014,986 | 38.3% |
| LOAD_ATTR | 20,325,786 | 28.8% |
| TO_BOOL | 8,518,565 | 12.1% |
| FOR_ITER | 6,056,239 | 8.6% |
| BINARY_OP | 3,613,787 | 5.1% |
| COMPARE_OP | 1,447,880 | 2.1% |
| BINARY_SUBSCR | 1,421,607 | 2.0% |
| STORE_ATTR | 1,002,491 | 1.4% |
| STORE_SUBSCR | 536,793 | 0.8% |
| SEND | 510,194 | 0.7% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,137,294 | 33.2% |
| STORE_ATTR_SLOT | 898,148 | 26.2% |
| LOAD_ATTR_INSTANCE_VALUE | 370,540 | 10.8% |
| LOAD_ATTR_METHOD_NO_DICT | 362,325 | 10.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 181,789 | 5.3% |
| CALL_PY_EXACT_ARGS | 114,015 | 3.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 91,516 | 2.7% |
| LOAD_ATTR_WITH_HINT | 58,966 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 40,340 | 1.2% |
| LOAD_ATTR_MODULE | 35,300 | 1.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 25,370,778 | 33.6% |
| Calls to Python functions inlined | 50,146,015 | 66.4% |
| Calls via PyEval_EvalFrame (total) | 25,370,778 | 33.6% |
| Calls via PyEval_EvalFrame (vector) | 23,670,902 | 31.3% |
| Calls via PyEval_EvalFrame (generator) | 1,699,876 | 2.3% |
| Calls via PyEval_EvalFrame (legacy) | 640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 23,669,322 | 31.3% |
| Calls via PyEval_EvalFrame (build class) | 940 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 3,339,096 | 4.4% |
| Calls via PyEval_EvalFrame (function ex) | 5,755,176 | 7.6% |
| Calls via PyEval_EvalFrame (api) | 5,269,059 | 7.0% |
| Calls via PyEval_EvalFrame (method) | 1,467,721 | 1.9% |
| Frame objects created | 1,428,997 | 1.9% |
| Frames pushed | 38,681,581 | 51.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 100,460,736 | 47.9% |
| Frees to freelist | 100,826,487 |  |
| Allocations | 109,264,842 | 52.1% |
| Allocations to 512 bytes | 108,077,408 | 51.5% |
| Allocations to 4 kbytes | 915,305 | 0.4% |
| Allocations over 4 kbytes | 272,129 | 0.1% |
| Frees | 102,620,168 |  |
| New values | 297,363 |  |
| Interpreter increfs | 795,889,665 | 74.9% |
| Interpreter decrefs | 903,068,695 | 73.0% |
| Increfs | 266,119,338 | 25.1% |
| Decrefs | 334,683,711 | 27.0% |
| Materialize dict (on request) | 2,561 | 0.9% |
| Materialize dict (new key) | 240 | 0.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 2,521 | 0.8% |
| Method cache hits | 24,010,458 |  |
| Method cache misses | 318,446 |  |
| Method cache collisions | 546,303 |  |
| Method cache dunder hits | 34,273,189 |  |
| Method cache dunder misses | 231,792 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 8,615 | 587,463 | 60,559,158 |
| 1 | 778 | 269,519 | 39,357,480 |
| 2 | 80 | 36,744 | 88,681,303 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 4,380 |  |
| Traces created | 4,076 | 93.1% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 78 | 1.8% |
| Trace too long | 2 | 0.0% |
| Trace too short | 304 | 6.9% |
| Inner loop found | 100 | 2.3% |
| Recursive call | 0 | 0.0% |
| Traces executed | 11,297,115 |  |
| Uops executed | 204,735,613 | 18.12 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 0.5% |
| <= 16 | 200 | 4.9% |
| <= 32 | 1,664 | 40.8% |
| <= 64 | 1,168 | 28.7% |
| <= 128 | 722 | 17.7% |
| <= 256 | 302 | 7.4% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 40 | 1.0% |
| <= 8 | 260 | 6.4% |
| <= 16 | 1,262 | 31.0% |
| <= 32 | 1,430 | 35.1% |
| <= 64 | 742 | 18.2% |
| <= 128 | 300 | 7.4% |
| <= 256 | 42 | 1.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 180 | 0.0% |
| <= 2 | 5,356,755 | 47.4% |
| <= 4 | 290,362 | 2.6% |
| <= 8 | 168,407 | 1.5% |
| <= 16 | 1,575,763 | 13.9% |
| <= 32 | 1,799,362 | 15.9% |
| <= 64 | 1,926,633 | 17.1% |
| <= 128 | 164,259 | 1.5% |
| <= 256 | 3,611 | 0.0% |
| <= 512 | 606 | 0.0% |
| <= 1,024 | 1,377 | 0.0% |
| <= 2,048 | 3,718 | 0.0% |
| <= 4,096 | 4,262 | 0.0% |
| <= 8,192 | 1,820 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 29,989,918 | 14.6% | 14.6% |  |
| LOAD_FAST | 26,048,699 | 12.7% | 27.4% |  |
| _CHECK_VALIDITY | 23,843,227 | 11.6% | 39.0% |  |
| _GUARD_TYPE_VERSION | 12,975,449 | 6.3% | 45.4% | 1.7% |
| STORE_FAST | 11,783,597 | 5.8% | 51.1% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 5,683,208 | 2.8% | 53.9% |  |
| _GUARD_IS_FALSE_POP | 5,205,587 | 2.5% | 56.4% | 4.4% |
| _FOR_ITER_TIER_TWO | 5,071,846 | 2.5% | 58.9% | 59.8% |
| _EXIT_TRACE | 4,712,005 | 2.3% | 61.2% |  |
| LOAD_CONST | 3,493,695 | 1.7% | 62.9% |  |
| _GUARD_GLOBALS_VERSION | 3,303,898 | 1.6% | 64.5% | 0.3% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 3,252,288 | 1.6% | 66.1% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 3,252,288 | 1.6% | 67.7% |  |
| _ITER_CHECK_LIST | 2,708,069 | 1.3% | 69.0% | 0.0% |
| _GUARD_NOT_EXHAUSTED_LIST | 2,707,889 | 1.3% | 70.4% | 46.9% |
| _LOAD_ATTR_SLOT | 2,556,968 | 1.2% | 71.6% |  |
| TO_BOOL_BOOL | 2,439,518 | 1.2% | 72.8% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 2,184,686 | 1.1% | 73.9% | 54.6% |
| _ITER_CHECK_TUPLE | 2,184,686 | 1.1% | 74.9% |  |
| _CHECK_PEP_523 | 2,183,439 | 1.1% | 76.0% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 2,183,439 | 1.1% | 77.1% |  |
| _CHECK_STACK_SPACE | 2,183,439 | 1.1% | 78.1% |  |
| _INIT_CALL_PY_EXACT_ARGS | 2,183,439 | 1.1% | 79.2% |  |
| _PUSH_FRAME | 2,183,439 | 1.1% | 80.3% |  |
| _SAVE_RETURN_OFFSET | 2,183,439 | 1.1% | 81.3% |  |
| _LOAD_GLOBAL_MODULE | 2,144,151 | 1.0% | 82.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,669,732 | 0.8% | 83.2% | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,643,998 | 0.8% | 84.0% |  |
| LOAD_DEREF | 1,585,030 | 0.8% | 84.8% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 1,541,024 | 0.8% | 85.5% | 16.1% |
| _ITER_CHECK_RANGE | 1,541,024 | 0.8% | 86.3% |  |
| _JUMP_TO_TOP | 1,491,092 | 0.7% | 87.0% |  |
| _ITER_NEXT_LIST | 1,436,815 | 0.7% | 87.7% |  |
| _GUARD_IS_TRUE_POP | 1,399,255 | 0.7% | 88.4% | 17.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,396,561 | 0.7% | 89.1% |  |
| _ITER_NEXT_RANGE | 1,293,470 | 0.6% | 89.7% |  |
| _GUARD_BUILTINS_VERSION | 1,149,527 | 0.6% | 90.3% | 0.6% |
| _LOAD_GLOBAL_BUILTINS | 1,142,267 | 0.6% | 90.8% |  |
| _LOAD_ATTR | 1,107,913 | 0.5% | 91.4% |  |
| _ITER_NEXT_TUPLE | 992,835 | 0.5% | 91.8% |  |
| POP_TOP | 836,613 | 0.4% | 92.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 811,400 | 0.4% | 92.6% |  |
| COMPARE_OP_STR | 790,048 | 0.4% | 93.0% |  |
| _CHECK_ATTR_WITH_HINT | 759,614 | 0.4% | 93.4% |  |
| _LOAD_ATTR_WITH_HINT | 759,614 | 0.4% | 93.8% |  |
| BINARY_SUBSCR_DICT | 737,822 | 0.4% | 94.1% |  |
| CONTAINS_OP | 731,238 | 0.4% | 94.5% |  |
| TO_BOOL_STR | 674,468 | 0.3% | 94.8% |  |
| GET_ITER | 563,165 | 0.3% | 95.1% |  |
| _GUARD_IS_NOT_NONE_POP | 559,867 | 0.3% | 95.4% | 0.3% |
| _TO_BOOL | 537,892 | 0.3% | 95.6% |  |
| RESUME_CHECK | 490,984 | 0.2% | 95.9% | 0.0% |
| IS_OP | 471,720 | 0.2% | 96.1% |  |
| _GUARD_KEYS_VERSION | 401,177 | 0.2% | 96.3% | 8.6% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 401,177 | 0.2% | 96.5% |  |
| _COMPARE_OP | 398,448 | 0.2% | 96.7% |  |
| BUILD_TUPLE | 370,221 | 0.2% | 96.9% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 366,623 | 0.2% | 97.0% |  |
| PUSH_NULL | 358,602 | 0.2% | 97.2% |  |
| MAKE_CELL | 302,374 | 0.1% | 97.4% |  |
| _BINARY_OP | 292,569 | 0.1% | 97.5% |  |
| BUILD_LIST | 277,620 | 0.1% | 97.7% |  |
| TO_BOOL_INT | 265,994 | 0.1% | 97.8% |  |
| _GUARD_IS_NONE_POP | 258,040 | 0.1% | 97.9% | 31.1% |
| LIST_APPEND | 241,022 | 0.1% | 98.0% |  |
| CALL_BUILTIN_CLASS | 240,143 | 0.1% | 98.1% |  |
| CALL_TYPE_1 | 198,560 | 0.1% | 98.2% |  |
| STORE_SUBSCR_DICT | 195,721 | 0.1% | 98.3% |  |
| MAP_ADD | 182,014 | 0.1% | 98.4% |  |
| MAKE_FUNCTION | 166,080 | 0.1% | 98.5% |  |
| _GUARD_BOTH_INT | 150,987 | 0.1% | 98.6% | 0.2% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 145,161 | 0.1% | 98.6% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 145,161 | 0.1% | 98.7% |  |
| _BINARY_SUBSCR | 139,372 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 128,956 | 0.1% | 98.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 123,700 | 0.1% | 98.9% |  |
| _GUARD_BOTH_UNICODE | 123,040 | 0.1% | 99.0% |  |
| _BINARY_OP_ADD_UNICODE | 123,040 | 0.1% | 99.0% |  |
| _CHECK_ATTR_MODULE | 122,155 | 0.1% | 99.1% |  |
| _LOAD_ATTR_MODULE | 122,155 | 0.1% | 99.2% |  |
| UNPACK_SEQUENCE_TUPLE | 110,860 | 0.1% | 99.2% |  |
| COMPARE_OP_INT | 110,586 | 0.1% | 99.3% | 9.7% |
| CALL_ISINSTANCE | 103,700 | 0.1% | 99.3% |  |
| CALL_LEN | 101,044 | 0.0% | 99.4% |  |
| CALL_INTRINSIC_1 | 97,362 | 0.0% | 99.4% |  |
| LIST_EXTEND | 97,362 | 0.0% | 99.5% |  |
| CALL_BUILTIN_FAST | 92,320 | 0.0% | 99.5% |  |
| _BINARY_OP_ADD_INT | 90,159 | 0.0% | 99.5% |  |
| BEFORE_WITH | 88,002 | 0.0% | 99.6% |  |
| SET_FUNCTION_ATTRIBUTE | 87,200 | 0.0% | 99.6% |  |
| UNARY_NEGATIVE | 86,800 | 0.0% | 99.7% |  |
| _STORE_ATTR_SLOT | 86,800 | 0.0% | 99.7% |  |
| COPY_FREE_VARS | 83,480 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_LIST_INT | 71,168 | 0.0% | 99.8% |  |
| COPY | 64,509 | 0.0% | 99.8% |  |
| COMPARE_OP_FLOAT | 56,916 | 0.0% | 99.8% | 2.8% |
| _BINARY_OP_SUBTRACT_INT | 55,780 | 0.0% | 99.9% |  |
| SWAP | 41,430 | 0.0% | 99.9% |  |
| DELETE_FAST | 38,694 | 0.0% | 99.9% |  |
| _POP_FRAME | 26,062 | 0.0% | 99.9% |  |
| CALL_BUILTIN_O | 19,307 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_STR_INT | 14,152 | 0.0% | 99.9% | 2.8% |
| _GUARD_DORV_VALUES | 13,880 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 13,880 | 0.0% | 100.0% |  |
| BUILD_MAP | 10,562 | 0.0% | 100.0% |  |
| DICT_MERGE | 10,562 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 8,230 | 0.0% | 100.0% |  |
| BINARY_SLICE | 7,830 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 7,600 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 7,110 | 0.0% | 100.0% |  |
| _UNPACK_SEQUENCE | 6,990 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 5,000 | 0.0% | 100.0% |  |
| BUILD_STRING | 5,000 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 4,768 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 4,020 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 3,100 | 0.0% | 100.0% |  |
| _CHECK_ATTR_CLASS | 1,120 | 0.0% | 100.0% | 94.6% |
| _STORE_SUBSCR | 1,080 | 0.0% | 100.0% |  |
| BUILD_SET | 880 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 880 | 0.0% | 100.0% |  |
| SET_ADD | 880 | 0.0% | 100.0% |  |
| CALL_STR_1 | 420 | 0.0% | 100.0% |  |
| STORE_DEREF | 400 | 0.0% | 100.0% |  |
| UNARY_NOT | 200 | 0.0% | 100.0% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 62 | 0.0% | 100.0% |  |
| _LOAD_ATTR_CLASS | 60 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 822 |
| FOR_ITER_GEN | 304 |
| CALL_PY_WITH_DEFAULTS | 280 |
| CALL_KW | 264 |
| YIELD_VALUE | 180 |
| CALL_LIST_APPEND | 124 |
| CALL_FUNCTION_EX | 100 |
| LOAD_ATTR_PROPERTY | 80 |
| CALL_ALLOC_AND_ENTER_INIT | 40 |
| BINARY_SUBSCR_GETITEM | 20 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-11-18
