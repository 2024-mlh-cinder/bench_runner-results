
# Pystats results

- benchmark: dask
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 340,981,448 | 20.4% | 20.4% |  |
| STORE_FAST | 88,223,477 | 5.3% | 25.7% |  |
| RESUME_CHECK | 76,296,170 | 4.6% | 30.3% | 0.0% |
| LOAD_CONST | 69,320,731 | 4.1% | 34.4% |  |
| POP_JUMP_IF_FALSE | 68,246,063 | 4.1% | 38.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 60,423,230 | 3.6% | 42.1% | 0.6% |
| RETURN_VALUE | 53,983,270 | 3.2% | 45.3% |  |
| LOAD_FAST_LOAD_FAST | 48,592,118 | 2.9% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 44,939,394 | 2.7% | 50.9% | 0.0% |
| POP_TOP | 43,460,582 | 2.6% | 53.5% |  |
| LOAD_GLOBAL_BUILTIN | 37,631,336 | 2.3% | 55.8% | 0.0% |
| LOAD_ATTR_SLOT | 35,481,897 | 2.1% | 57.9% | 3.2% |
| LOAD_ATTR_METHOD_NO_DICT | 32,065,975 | 1.9% | 59.8% | 1.2% |
| CALL_PY_EXACT_ARGS | 32,019,753 | 1.9% | 61.7% | 0.4% |
| TO_BOOL_BOOL | 27,093,874 | 1.6% | 63.4% |  |
| CALL | 27,002,006 | 1.6% | 65.0% |  |
| INTERPRETER_EXIT | 24,971,632 | 1.5% | 66.5% |  |
| LOAD_ATTR_WITH_HINT | 21,876,618 | 1.3% | 67.8% | 0.9% |
| LOAD_ATTR | 20,821,538 | 1.2% | 69.0% |  |
| RETURN_CONST | 20,667,922 | 1.2% | 70.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 20,415,540 | 1.2% | 71.5% | 0.1% |
| PUSH_NULL | 19,820,000 | 1.2% | 72.7% |  |
| NOP | 17,716,860 | 1.1% | 73.7% |  |
| SWAP | 15,775,560 | 0.9% | 74.7% |  |
| STORE_ATTR_SLOT | 15,118,990 | 0.9% | 75.6% | 5.8% |
| BUILD_MAP | 14,537,118 | 0.9% | 76.5% |  |
| GET_ITER | 14,452,300 | 0.9% | 77.3% |  |
| POP_JUMP_IF_TRUE | 13,965,103 | 0.8% | 78.2% |  |
| JUMP_BACKWARD | 12,904,755 | 0.8% | 78.9% |  |
| CALL_FUNCTION_EX | 11,650,577 | 0.7% | 79.6% |  |
| BUILD_LIST | 11,186,326 | 0.7% | 80.3% |  |
| FOR_ITER | 11,112,960 | 0.7% | 81.0% |  |
| BINARY_SUBSCR_DICT | 10,949,770 | 0.7% | 81.6% |  |
| CONTAINS_OP | 10,854,086 | 0.6% | 82.3% |  |
| STORE_ATTR_INSTANCE_VALUE | 10,475,590 | 0.6% | 82.9% | 0.0% |
| COPY | 10,386,383 | 0.6% | 83.5% |  |
| LOAD_DEREF | 10,220,684 | 0.6% | 84.1% |  |
| IS_OP | 9,758,789 | 0.6% | 84.7% |  |
| BUILD_TUPLE | 9,521,601 | 0.6% | 85.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,355,562 | 0.6% | 85.8% | 1.0% |
| TO_BOOL | 8,928,629 | 0.5% | 86.4% |  |
| CALL_METHOD_DESCRIPTOR_O | 8,803,717 | 0.5% | 86.9% | 0.1% |
| DICT_MERGE | 8,802,722 | 0.5% | 87.4% |  |
| COMPARE_OP_INT | 8,168,844 | 0.5% | 87.9% | 0.3% |
| LIST_EXTEND | 8,071,755 | 0.5% | 88.4% |  |
| CALL_INTRINSIC_1 | 7,993,963 | 0.5% | 88.9% |  |
| LOAD_ATTR_MODULE | 7,928,750 | 0.5% | 89.4% | 0.4% |
| FOR_ITER_TUPLE | 7,875,004 | 0.5% | 89.8% |  |
| CALL_TYPE_1 | 7,852,242 | 0.5% | 90.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 7,378,394 | 0.4% | 90.7% | 2.5% |
| CALL_BUILTIN_CLASS | 7,332,752 | 0.4% | 91.2% |  |
| POP_JUMP_IF_NONE | 6,928,649 | 0.4% | 91.6% |  |
| POP_JUMP_IF_NOT_NONE | 6,381,328 | 0.4% | 92.0% |  |
| COMPARE_OP_STR | 6,344,609 | 0.4% | 92.3% | 0.0% |
| CALL_LEN | 5,633,392 | 0.3% | 92.7% |  |
| STORE_FAST_STORE_FAST | 5,579,390 | 0.3% | 93.0% |  |
| BINARY_OP_ADD_INT | 5,135,431 | 0.3% | 93.3% | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,927,774 | 0.3% | 93.6% |  |
| FOR_ITER_LIST | 4,875,577 | 0.3% | 93.9% | 0.0% |
| STORE_SUBSCR_DICT | 4,658,356 | 0.3% | 94.2% |  |
| CALL_ISINSTANCE | 4,539,953 | 0.3% | 94.5% |  |
| MAKE_CELL | 4,427,662 | 0.3% | 94.7% |  |
| TO_BOOL_NONE | 4,292,124 | 0.3% | 95.0% | 0.2% |
| COPY_FREE_VARS | 3,919,942 | 0.2% | 95.2% |  |
| BINARY_OP | 3,905,950 | 0.2% | 95.5% |  |
| JUMP_FORWARD | 3,712,806 | 0.2% | 95.7% |  |
| CALL_KW | 3,486,578 | 0.2% | 95.9% |  |
| LOAD_ATTR_PROPERTY | 2,728,688 | 0.2% | 96.0% | 0.0% |
| CALL_PY_WITH_DEFAULTS | 2,412,234 | 0.1% | 96.2% | 0.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,241,531 | 0.1% | 96.3% | 0.1% |
| BEFORE_WITH | 2,237,894 | 0.1% | 96.5% |  |
| LOAD_FAST_AND_CLEAR | 2,170,243 | 0.1% | 96.6% |  |
| CALL_BUILTIN_FAST | 2,020,047 | 0.1% | 96.7% | 0.0% |
| BINARY_OP_SUBTRACT_INT | 2,006,552 | 0.1% | 96.8% |  |
| TO_BOOL_INT | 1,915,803 | 0.1% | 96.9% | 0.0% |
| COMPARE_OP | 1,857,632 | 0.1% | 97.1% |  |
| EXTENDED_ARG | 1,753,557 | 0.1% | 97.2% |  |
| COMPARE_OP_FLOAT | 1,748,467 | 0.1% | 97.3% | 0.1% |
| FOR_ITER_RANGE | 1,736,376 | 0.1% | 97.4% |  |
| TO_BOOL_LIST | 1,637,934 | 0.1% | 97.5% |  |
| CALL_BUILTIN_O | 1,608,010 | 0.1% | 97.6% | 0.1% |
| BINARY_SUBSCR_TUPLE_INT | 1,604,829 | 0.1% | 97.7% |  |
| BINARY_SUBSCR | 1,488,584 | 0.1% | 97.7% |  |
| YIELD_VALUE | 1,470,604 | 0.1% | 97.8% |  |
| MAKE_FUNCTION | 1,460,646 | 0.1% | 97.9% |  |
| STORE_ATTR_WITH_HINT | 1,418,499 | 0.1% | 98.0% | 0.3% |
| SET_FUNCTION_ATTRIBUTE | 1,408,679 | 0.1% | 98.1% |  |
| DELETE_SUBSCR | 1,398,198 | 0.1% | 98.2% |  |
| UNPACK_SEQUENCE_TUPLE | 1,350,972 | 0.1% | 98.3% |  |
| TO_BOOL_STR | 1,237,603 | 0.1% | 98.3% | 0.1% |
| BINARY_OP_ADD_FLOAT | 1,161,740 | 0.1% | 98.4% | 0.1% |
| BUILD_CONST_KEY_MAP | 1,155,646 | 0.1% | 98.5% |  |
| STORE_ATTR | 1,048,100 | 0.1% | 98.5% |  |
| BINARY_SUBSCR_LIST_INT | 1,004,595 | 0.1% | 98.6% | 0.1% |
| STORE_FAST_LOAD_FAST | 997,121 | 0.1% | 98.7% |  |
| RETURN_GENERATOR | 903,649 | 0.1% | 98.7% |  |
| MAP_ADD | 870,160 | 0.1% | 98.8% |  |
| PUSH_EXC_INFO | 854,752 | 0.1% | 98.8% |  |
| POP_EXCEPT | 854,746 | 0.1% | 98.9% |  |
| TO_BOOL_ALWAYS_TRUE | 839,019 | 0.1% | 98.9% | 0.9% |
| BINARY_OP_SUBTRACT_FLOAT | 813,320 | 0.0% | 99.0% | 0.3% |
| STORE_DEREF | 792,345 | 0.0% | 99.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 774,072 | 0.0% | 99.1% |  |
| LIST_APPEND | 759,455 | 0.0% | 99.1% |  |
| BINARY_SLICE | 723,721 | 0.0% | 99.1% |  |
| CHECK_EXC_MATCH | 721,520 | 0.0% | 99.2% |  |
| CALL_LIST_APPEND | 655,325 | 0.0% | 99.2% |  |
| BINARY_OP_MULTIPLY_INT | 650,719 | 0.0% | 99.3% |  |
| LOAD_SUPER_ATTR_METHOD | 634,005 | 0.0% | 99.3% |  |
| BUILD_SET | 602,767 | 0.0% | 99.3% |  |
| BINARY_SUBSCR_GETITEM | 579,151 | 0.0% | 99.4% | 0.0% |
| SEND_GEN | 578,518 | 0.0% | 99.4% | 0.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 575,435 | 0.0% | 99.4% |  |
| STORE_SUBSCR | 543,488 | 0.0% | 99.5% |  |
| FORMAT_SIMPLE | 518,484 | 0.0% | 99.5% |  |
| SEND | 511,151 | 0.0% | 99.5% |  |
| END_SEND | 509,920 | 0.0% | 99.6% |  |
| GET_AWAITABLE | 508,800 | 0.0% | 99.6% |  |
| BUILD_STRING | 468,098 | 0.0% | 99.6% |  |
| LOAD_ATTR_CLASS | 448,108 | 0.0% | 99.7% | 0.5% |
| BINARY_OP_ADD_UNICODE | 384,440 | 0.0% | 99.7% | 0.1% |
| DELETE_FAST | 364,824 | 0.0% | 99.7% |  |
| CALL_TUPLE_1 | 363,120 | 0.0% | 99.7% |  |
| RERAISE | 359,358 | 0.0% | 99.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 329,368 | 0.0% | 99.8% | 0.4% |
| CALL_ALLOC_AND_ENTER_INIT | 297,235 | 0.0% | 99.8% | 0.4% |
| EXIT_INIT_CHECK | 296,015 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 278,069 | 0.0% | 99.8% | 14.4% |
| LOAD_ATTR_METHOD_LAZY_DICT | 263,960 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_STR_INT | 256,520 | 0.0% | 99.8% | 0.2% |
| CALL_STR_1 | 253,156 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 247,765 | 0.0% | 99.9% |  |
| BINARY_OP_MULTIPLY_FLOAT | 207,575 | 0.0% | 99.9% | 1.1% |
| IMPORT_FROM | 201,880 | 0.0% | 99.9% |  |
| IMPORT_NAME | 201,117 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 179,306 | 0.0% | 99.9% |  |
| WITH_EXCEPT_START | 178,420 | 0.0% | 99.9% |  |
| SET_ADD | 177,760 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 120,880 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 108,979 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 97,660 | 0.0% | 100.0% | 0.4% |
| UNARY_NEGATIVE | 88,020 | 0.0% | 100.0% |  |
| SET_UPDATE | 88,020 | 0.0% | 100.0% |  |
| UNPACK_EX | 88,000 | 0.0% | 100.0% |  |
| UNARY_INVERT | 81,512 | 0.0% | 100.0% |  |
| BUILD_SLICE | 80,937 | 0.0% | 100.0% |  |
| DICT_UPDATE | 41,396 | 0.0% | 100.0% |  |
| STORE_SLICE | 39,696 | 0.0% | 100.0% |  |
| RESUME | 26,112 | 0.0% | 100.0% | 22.4% |
| UNPACK_SEQUENCE | 15,620 | 0.0% | 100.0% |  |
| STORE_NAME | 14,380 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 10,720 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 8,700 | 0.0% | 100.0% |  |
| DELETE_ATTR | 8,203 | 0.0% | 100.0% |  |
| LOAD_NAME | 6,720 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 5,920 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 4,938 | 0.0% | 100.0% | 90.0% |
| LOAD_SUPER_ATTR_ATTR | 3,920 | 0.0% | 100.0% |  |
| END_FOR | 3,641 | 0.0% | 100.0% |  |
| UNARY_NOT | 2,900 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,840 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 1,760 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 940 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 880 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 53,129,879 | 3.2% | 3.2% |
| STORE_FAST LOAD_FAST | 51,684,487 | 3.1% | 6.3% |
| RESUME_CHECK LOAD_FAST | 44,436,787 | 2.7% | 8.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 38,216,185 | 2.3% | 11.2% |
| LOAD_FAST LOAD_ATTR_SLOT | 33,001,953 | 2.0% | 13.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 30,099,127 | 1.8% | 15.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 23,231,917 | 1.4% | 16.4% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 21,922,140 | 1.3% | 17.7% |
| CACHE RESUME_CHECK | 21,900,968 | 1.3% | 19.0% |
| LOAD_CONST LOAD_FAST | 18,500,423 | 1.1% | 20.1% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 17,907,472 | 1.1% | 21.2% |
| RETURN_VALUE INTERPRETER_EXIT | 17,372,945 | 1.0% | 22.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 16,131,204 | 1.0% | 23.2% |
| POP_TOP LOAD_FAST | 15,763,110 | 0.9% | 24.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 15,712,887 | 0.9% | 25.1% |
| LOAD_FAST LOAD_ATTR | 14,970,150 | 0.9% | 26.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 14,082,718 | 0.8% | 26.8% |
| LOAD_FAST LOAD_CONST | 14,078,029 | 0.8% | 27.7% |
| RETURN_VALUE STORE_FAST | 13,838,679 | 0.8% | 28.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 13,750,708 | 0.8% | 29.3% |
| RETURN_CONST POP_TOP | 12,284,236 | 0.7% | 30.0% |
| PUSH_NULL LOAD_FAST | 12,266,061 | 0.7% | 30.8% |
| LOAD_FAST RETURN_VALUE | 11,851,040 | 0.7% | 31.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 11,192,105 | 0.7% | 32.2% |
| LOAD_FAST CALL | 10,839,393 | 0.6% | 32.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 9,556,537 | 0.6% | 33.4% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 9,466,876 | 0.6% | 33.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 8,837,136 | 0.5% | 34.5% |
| DICT_MERGE CALL_FUNCTION_EX | 8,802,722 | 0.5% | 35.0% |
| BUILD_MAP LOAD_FAST | 8,573,109 | 0.5% | 35.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 8,571,732 | 0.5% | 36.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 8,550,882 | 0.5% | 36.5% |
| BUILD_LIST LOAD_FAST | 8,441,712 | 0.5% | 37.0% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 8,324,753 | 0.5% | 37.5% |
| NOP LOAD_FAST | 8,304,687 | 0.5% | 38.0% |
| LOAD_FAST DICT_MERGE | 8,199,211 | 0.5% | 38.5% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 8,192,694 | 0.5% | 39.0% |
| LOAD_FAST PUSH_NULL | 8,188,667 | 0.5% | 39.5% |
| LOAD_FAST STORE_ATTR_SLOT | 8,186,519 | 0.5% | 40.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 7,992,643 | 0.5% | 40.5% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 7,911,612 | 0.5% | 41.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 7,780,502 | 0.5% | 41.4% |
| LOAD_FAST CALL_TYPE_1 | 7,762,402 | 0.5% | 41.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 7,666,313 | 0.5% | 42.3% |
| IS_OP POP_JUMP_IF_FALSE | 7,568,851 | 0.5% | 42.8% |
| STORE_FAST NOP | 7,384,311 | 0.4% | 43.2% |
| RETURN_VALUE RETURN_VALUE | 7,304,318 | 0.4% | 43.7% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 7,300,948 | 0.4% | 44.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 7,070,662 | 0.4% | 44.5% |
| LOAD_FAST BUILD_LIST | 6,996,279 | 0.4% | 45.0% |
| LOAD_CONST LOAD_CONST | 6,991,964 | 0.4% | 45.4% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 6,944,754 | 0.4% | 45.8% |
| LOAD_FAST LIST_EXTEND | 6,735,648 | 0.4% | 46.2% |
| BINARY_SUBSCR_DICT STORE_FAST | 6,700,842 | 0.4% | 46.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,601,622 | 0.4% | 47.0% |
| FOR_ITER_TUPLE STORE_FAST | 6,580,500 | 0.4% | 47.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 6,465,602 | 0.4% | 47.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 6,386,005 | 0.4% | 48.1% |
| RETURN_CONST INTERPRETER_EXIT | 6,351,265 | 0.4% | 48.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 6,286,916 | 0.4% | 48.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 6,180,930 | 0.4% | 49.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 6,119,633 | 0.4% | 49.6% |
| POP_TOP RETURN_CONST | 6,038,979 | 0.4% | 50.0% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 5,958,188 | 0.4% | 50.4% |
| TO_BOOL POP_JUMP_IF_FALSE | 5,874,572 | 0.4% | 50.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 5,855,776 | 0.4% | 51.1% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_METHOD_NO_DICT | 5,801,468 | 0.3% | 51.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 5,800,171 | 0.3% | 51.8% |
| CALL_INTRINSIC_1 BUILD_MAP | 5,729,667 | 0.3% | 52.1% |
| POP_JUMP_IF_FALSE LOAD_CONST | 5,712,672 | 0.3% | 52.4% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 5,710,261 | 0.3% | 52.8% |
| CALL_FUNCTION_EX RESUME_CHECK | 5,663,874 | 0.3% | 53.1% |
| RESUME_CHECK NOP | 5,507,059 | 0.3% | 53.4% |
| POP_TOP RETURN_VALUE | 5,370,336 | 0.3% | 53.8% |
| GET_ITER FOR_ITER_TUPLE | 5,362,358 | 0.3% | 54.1% |
| RETURN_VALUE TO_BOOL_BOOL | 5,303,709 | 0.3% | 54.4% |
| POP_TOP JUMP_BACKWARD | 5,249,940 | 0.3% | 54.7% |
| CALL POP_TOP | 5,226,031 | 0.3% | 55.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,163,742 | 0.3% | 55.3% |
| LOAD_CONST STORE_FAST | 5,119,346 | 0.3% | 55.7% |
| CALL RETURN_VALUE | 5,026,656 | 0.3% | 56.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 5,005,428 | 0.3% | 56.3% |
| LOAD_FAST LOAD_FAST | 4,984,692 | 0.3% | 56.6% |
| NOP LOAD_FAST_LOAD_FAST | 4,945,376 | 0.3% | 56.8% |
| LOAD_FAST SWAP | 4,897,674 | 0.3% | 57.1% |
| GET_ITER FOR_ITER | 4,858,015 | 0.3% | 57.4% |
| STORE_ATTR_SLOT LOAD_CONST | 4,841,861 | 0.3% | 57.7% |
| JUMP_BACKWARD FOR_ITER | 4,808,705 | 0.3% | 58.0% |
| POP_JUMP_IF_NONE LOAD_FAST | 4,792,932 | 0.3% | 58.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 4,771,264 | 0.3% | 58.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 4,759,539 | 0.3% | 58.9% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_DICT | 4,718,626 | 0.3% | 59.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 4,640,789 | 0.3% | 59.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_BUILTIN | 4,626,696 | 0.3% | 59.7% |
| LOAD_CONST COMPARE_OP_INT | 4,592,546 | 0.3% | 60.0% |
| LOAD_FAST_LOAD_FAST IS_OP | 4,564,046 | 0.3% | 60.2% |
| CALL STORE_FAST | 4,530,455 | 0.3% | 60.5% |
| LOAD_CONST COMPARE_OP_STR | 4,526,456 | 0.3% | 60.8% |
| SWAP POP_TOP | 4,489,506 | 0.3% | 61.1% |
| LOAD_ATTR GET_ITER | 4,484,326 | 0.3% | 61.3% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 469,875 | 64.9% |
| LOAD_FAST | 210,890 | 29.1% |
| BINARY_OP_ADD_INT | 42,016 | 5.8% |
| LOAD_ATTR_INSTANCE_VALUE | 860 | 0.1% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 112,100 | 15.5% |
| CALL_BUILTIN_CLASS | 96,060 | 13.3% |
| CALL_METHOD_DESCRIPTOR_O | 87,960 | 12.2% |
| CALL_PY_WITH_DEFAULTS | 87,960 | 12.2% |
| STORE_FAST | 70,706 | 9.8% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 39,396 | 99.2% |
| LOAD_FAST | 160 | 0.4% |
| BINARY_OP_ADD_INT | 140 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,396 | 99.2% |
| LOAD_CONST | 160 | 0.4% |
| JUMP_BACKWARD | 140 | 0.4% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,900,968 | 86.8% |
| COPY_FREE_VARS | 2,319,551 | 9.2% |
| POP_TOP | 577,527 | 2.3% |
| MAKE_CELL | 267,160 | 1.1% |
| RETURN_GENERATOR | 128,940 | 0.5% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,000 | 93.3% |
| LOAD_ATTR_WITH_HINT | 460 | 4.3% |
| CALL | 160 | 1.5% |
| CALL_KW | 80 | 0.7% |
| LOAD_ATTR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 10,720 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,675,524 | 74.9% |
| LOAD_GLOBAL_MODULE | 186,279 | 8.3% |
| LOAD_ATTR_WITH_HINT | 176,580 | 7.9% |
| LOAD_FAST | 176,240 | 7.9% |
| CALL | 11,340 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,233,028 | 99.8% |
| STORE_FAST | 4,866 | 0.2% |


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
| JUMP_BACKWARD | 118,560 | 98.1% |
| LOAD_GLOBAL_MODULE | 1,720 | 1.4% |
| LOAD_FAST | 360 | 0.3% |
| STORE_FAST | 220 | 0.2% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 910,359 | 61.2% |
| COPY | 355,140 | 23.9% |
| LOAD_CONST | 214,721 | 14.4% |
| BINARY_SUBSCR | 4,884 | 0.3% |
| BUILD_SLICE | 1,200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 344,260 | 23.1% |
| LOAD_CONST | 267,560 | 18.0% |
| STORE_FAST | 177,117 | 11.9% |
| LOAD_FAST | 176,980 | 11.9% |
| LOAD_ATTR_METHOD_NO_DICT | 163,636 | 11.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 639,077 | 88.6% |
| LOAD_ATTR_MODULE | 76,390 | 10.6% |
| BUILD_TUPLE | 4,880 | 0.7% |
| LOAD_GLOBAL | 727 | 0.1% |
| LOAD_GLOBAL_MODULE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 721,520 | 100.0% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 640 | 72.7% |
| JUMP_BACKWARD | 240 | 27.3% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 964,206 | 69.0% |
| LOAD_FAST_LOAD_FAST | 265,395 | 19.0% |
| LOAD_ATTR_SLOT | 88,040 | 6.3% |
| BUILD_SLICE | 79,737 | 5.7% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 431,662 | 32.9% |
| PUSH_EXC_INFO | 352,000 | 26.9% |
| RETURN_CONST | 258,225 | 19.7% |
| LOAD_FAST_LOAD_FAST | 88,545 | 6.8% |
| LOAD_CONST | 88,506 | 6.8% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,641 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,440 | 39.5% |
| LOAD_CONST | 880 | 24.2% |
| STORE_FAST | 701 | 19.3% |
| SWAP | 300 | 8.2% |
| RETURN_CONST | 180 | 4.9% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 264,538 | 51.9% |
| SEND | 188,319 | 36.9% |
| RETURN_CONST | 56,663 | 11.1% |
| JUMP_BACKWARD | 240 | 0.0% |
| SEND_GEN | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 296,180 | 58.1% |
| POP_TOP | 115,006 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 88,240 | 17.3% |
| SWAP | 10,000 | 2.0% |
| LOAD_DEREF | 160 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 296,015 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 296,015 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 373,196 | 72.0% |
| LOAD_FAST | 132,708 | 25.6% |
| CONVERT_VALUE | 8,700 | 1.7% |
| LOAD_GLOBAL_MODULE | 3,340 | 0.6% |
| CALL_LEN | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 419,472 | 80.9% |
| LOAD_CONST | 57,976 | 11.2% |
| LOAD_FAST | 41,036 | 7.9% |


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
| LOAD_ATTR | 4,484,326 | 31.0% |
| LOAD_FAST | 3,737,944 | 25.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,530,760 | 17.5% |
| LOAD_ATTR_SLOT | 1,617,021 | 11.2% |
| LOAD_ATTR_INSTANCE_VALUE | 914,828 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 5,362,358 | 37.1% |
| FOR_ITER | 4,858,015 | 33.6% |
| FOR_ITER_LIST | 2,163,607 | 15.0% |
| LOAD_FAST_AND_CLEAR | 1,386,403 | 9.6% |
| CALL_PY_EXACT_ARGS | 420,891 | 2.9% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,740 | 98.9% |
| LOAD_ATTR | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,760 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 17,372,945 | 69.6% |
| RETURN_CONST | 6,351,265 | 25.4% |
| YIELD_VALUE | 1,118,322 | 4.5% |
| RETURN_GENERATOR | 129,100 | 0.5% |


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
| LOAD_CONST | 1,460,646 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,200,807 | 82.2% |
| STORE_DEREF | 88,007 | 6.0% |
| LOAD_FAST | 85,440 | 5.8% |
| CALL | 40,316 | 2.8% |
| LOAD_GLOBAL_BUILTIN | 39,996 | 2.7% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,384,311 | 41.7% |
| RESUME_CHECK | 5,507,059 | 31.1% |
| POP_JUMP_IF_FALSE | 1,578,271 | 8.9% |
| STORE_ATTR_INSTANCE_VALUE | 589,869 | 3.3% |
| POP_JUMP_IF_TRUE | 536,244 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,304,687 | 46.9% |
| LOAD_FAST_LOAD_FAST | 4,945,376 | 27.9% |
| LOAD_GLOBAL_MODULE | 2,318,225 | 13.1% |
| LOAD_CONST | 584,218 | 3.3% |
| LOAD_GLOBAL_BUILTIN | 478,110 | 2.7% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 514,845 | 60.2% |
| COPY | 179,219 | 21.0% |
| STORE_FAST | 143,496 | 16.8% |
| STORE_SUBSCR_DICT | 8,846 | 1.0% |
| SWAP | 6,212 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 433,722 | 50.7% |
| RERAISE | 179,219 | 21.0% |
| EXTENDED_ARG | 128,335 | 15.0% |
| DELETE_FAST | 39,636 | 4.6% |
| LOAD_CONST | 39,315 | 4.6% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 12,284,236 | 28.3% |
| CALL_METHOD_DESCRIPTOR_O | 8,324,753 | 19.2% |
| CALL | 5,226,031 | 12.0% |
| SWAP | 4,489,506 | 10.3% |
| CALL_FUNCTION_EX | 2,953,164 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,763,110 | 36.3% |
| RETURN_CONST | 6,038,979 | 13.9% |
| RETURN_VALUE | 5,370,336 | 12.4% |
| JUMP_BACKWARD | 5,249,940 | 12.1% |
| LOAD_FAST_LOAD_FAST | 2,439,823 | 5.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 352,000 | 41.2% |
| BINARY_SUBSCR_DICT | 185,338 | 21.7% |
| CALL | 96,360 | 11.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 88,179 | 10.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 76,609 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 597,025 | 69.8% |
| WITH_EXCEPT_START | 178,420 | 20.9% |
| LOAD_GLOBAL_MODULE | 77,509 | 9.1% |
| LOAD_GLOBAL | 1,679 | 0.2% |
| DELETE_FAST | 79 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,188,667 | 41.3% |
| LOAD_ATTR_MODULE | 6,286,916 | 31.7% |
| LOAD_ATTR | 4,013,531 | 20.2% |
| LOAD_DEREF | 1,010,981 | 5.1% |
| RETURN_VALUE | 223,059 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,266,061 | 61.9% |
| LOAD_FAST_LOAD_FAST | 2,619,873 | 13.2% |
| CALL | 2,450,026 | 12.4% |
| LOAD_CONST | 1,189,833 | 6.0% |
| CALL_BUILTIN_CLASS | 437,640 | 2.2% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 297,335 | 32.9% |
| CALL_PY_EXACT_ARGS | 180,139 | 19.9% |
| CALL_KW | 130,216 | 14.4% |
| CACHE | 128,940 | 14.3% |
| CALL_PY_WITH_DEFAULTS | 82,719 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 289,441 | 32.0% |
| CALL_TUPLE_1 | 176,440 | 19.5% |
| INTERPRETER_EXIT | 129,100 | 14.3% |
| CALL_BUILTIN_O | 118,075 | 13.1% |
| CALL | 83,440 | 9.2% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,851,040 | 22.0% |
| RETURN_VALUE | 7,304,318 | 13.5% |
| POP_TOP | 5,370,336 | 9.9% |
| CALL | 5,026,656 | 9.3% |
| LOAD_ATTR_INSTANCE_VALUE | 3,813,836 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 17,372,945 | 32.2% |
| STORE_FAST | 13,838,679 | 25.6% |
| RETURN_VALUE | 7,304,318 | 13.5% |
| TO_BOOL_BOOL | 5,303,709 | 9.8% |
| LOAD_FAST | 1,503,155 | 2.8% |


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
| SWAP | 355,140 | 65.3% |
| LOAD_FAST | 90,806 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 88,120 | 16.2% |
| LOAD_CONST | 4,880 | 0.9% |
| STORE_SUBSCR | 1,935 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 268,227 | 49.4% |
| LOAD_CONST | 89,600 | 16.5% |
| RETURN_CONST | 89,386 | 16.4% |
| LOAD_GLOBAL_MODULE | 88,080 | 16.2% |
| STORE_SUBSCR_DICT | 3,460 | 0.6% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,351,822 | 48.7% |
| LOAD_ATTR_SLOT | 1,768,420 | 19.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,057,008 | 11.8% |
| RETURN_VALUE | 964,989 | 10.8% |
| COPY | 394,833 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,874,572 | 65.8% |
| POP_JUMP_IF_TRUE | 2,914,307 | 32.6% |
| EXTENDED_ARG | 99,958 | 1.1% |
| TO_BOOL | 21,633 | 0.2% |
| TO_BOOL_BOOL | 12,076 | 0.1% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 40,636 | 49.9% |
| BINARY_OP | 40,356 | 49.5% |
| LOAD_FAST | 480 | 0.6% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 81,512 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 87,980 | 100.0% |
| CALL | 20 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,000 | 100.0% |
| CALL_BUILTIN_CLASS | 20 | 0.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,160 | 40.0% |
| TO_BOOL_BOOL | 1,060 | 36.6% |
| TO_BOOL_LIST | 620 | 21.4% |
| TO_BOOL | 60 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,180 | 40.7% |
| STORE_DEREF | 880 | 30.3% |
| CALL_PY_EXACT_ARGS | 620 | 21.4% |
| RETURN_VALUE | 140 | 4.8% |
| STORE_FAST | 80 | 2.8% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 178,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 177,300 | 99.4% |
| TO_BOOL_BOOL | 960 | 0.5% |
| TO_BOOL | 160 | 0.1% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 755,507 | 19.3% |
| LOAD_FAST_LOAD_FAST | 714,815 | 18.3% |
| LOAD_GLOBAL_MODULE | 477,287 | 12.2% |
| LOAD_ATTR_WITH_HINT | 272,840 | 7.0% |
| LOAD_CONST | 230,335 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,337,080 | 34.2% |
| TO_BOOL_INT | 580,786 | 14.9% |
| LOAD_FAST_LOAD_FAST | 263,380 | 6.7% |
| LOAD_CONST | 260,643 | 6.7% |
| COPY | 251,998 | 6.5% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,155,646 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 433,146 | 37.5% |
| RETURN_VALUE | 188,387 | 16.3% |
| CALL_LIST_APPEND | 176,880 | 15.3% |
| LOAD_FAST | 129,036 | 11.2% |
| CALL_PY_EXACT_ARGS | 89,960 | 7.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,996,279 | 62.5% |
| LOAD_ATTR_SLOT | 1,334,120 | 11.9% |
| RESUME_CHECK | 536,500 | 4.8% |
| STORE_FAST | 469,890 | 4.2% |
| SWAP | 342,963 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,441,712 | 75.5% |
| STORE_FAST | 1,357,802 | 12.1% |
| BUILD_TUPLE | 512,676 | 4.6% |
| SWAP | 381,319 | 3.4% |
| LOAD_FAST_LOAD_FAST | 184,008 | 1.6% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 5,729,667 | 39.4% |
| STORE_FAST | 2,585,910 | 17.8% |
| LOAD_FAST | 1,768,344 | 12.2% |
| SWAP | 785,120 | 5.4% |
| BUILD_TUPLE | 660,016 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,573,109 | 59.0% |
| STORE_FAST | 4,078,353 | 28.1% |
| SWAP | 785,120 | 5.4% |
| LOAD_GLOBAL_MODULE | 433,440 | 3.0% |
| BUILD_LIST | 248,000 | 1.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 258,320 | 42.9% |
| LOAD_GLOBAL_MODULE | 176,287 | 29.2% |
| LOAD_ATTR | 88,080 | 14.6% |
| LOAD_CONST | 80,020 | 13.3% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 258,320 | 42.9% |
| CONTAINS_OP | 176,407 | 29.3% |
| LOAD_CONST | 88,020 | 14.6% |
| BINARY_OP | 80,020 | 13.3% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 78,952 | 97.5% |
| LOAD_CONST | 1,985 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 79,737 | 98.5% |
| BINARY_SUBSCR | 1,200 | 1.5% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 419,472 | 89.6% |
| LOAD_CONST | 48,626 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 197,236 | 42.1% |
| BUILD_MAP | 88,000 | 18.8% |
| LOAD_CONST | 88,000 | 18.8% |
| LOAD_FAST | 40,896 | 8.7% |
| LOAD_FAST_LOAD_FAST | 39,556 | 8.5% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,863,759 | 30.1% |
| LOAD_FAST_LOAD_FAST | 2,473,726 | 26.0% |
| CALL | 1,423,129 | 14.9% |
| BUILD_LIST | 512,676 | 5.4% |
| LOAD_GLOBAL_BUILTIN | 465,885 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,718,168 | 28.5% |
| LOAD_CONST | 1,551,413 | 16.3% |
| CALL_METHOD_DESCRIPTOR_O | 1,541,902 | 16.2% |
| BUILD_MAP | 660,016 | 6.9% |
| CONTAINS_OP | 561,713 | 5.9% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,839,393 | 40.1% |
| LOAD_GLOBAL_MODULE | 3,590,023 | 13.3% |
| LOAD_FAST_LOAD_FAST | 2,829,096 | 10.5% |
| LOAD_CONST | 2,717,068 | 10.1% |
| PUSH_NULL | 2,450,026 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,226,031 | 19.4% |
| RETURN_VALUE | 5,026,656 | 18.6% |
| STORE_FAST | 4,530,455 | 16.8% |
| RESUME_CHECK | 3,972,451 | 14.7% |
| BUILD_TUPLE | 1,423,129 | 5.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 8,802,722 | 75.6% |
| CALL_INTRINSIC_1 | 1,680,279 | 14.4% |
| LOAD_FAST | 979,063 | 8.4% |
| LOAD_ATTR_INSTANCE_VALUE | 88,040 | 0.8% |
| BUILD_MAP | 55,257 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,663,874 | 48.6% |
| POP_TOP | 2,953,164 | 25.3% |
| RETURN_VALUE | 1,151,294 | 9.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 615,920 | 5.3% |
| UNPACK_SEQUENCE_TUPLE | 431,960 | 3.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 7,992,643 | 100.0% |
| RERAISE | 1,320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 5,729,667 | 71.7% |
| CALL_FUNCTION_EX | 1,680,279 | 21.0% |
| LOAD_CONST | 582,697 | 7.3% |
| RERAISE | 1,320 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,486,578 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,541,784 | 72.9% |
| MAKE_CELL | 369,741 | 10.6% |
| STORE_FAST | 155,648 | 4.5% |
| RETURN_GENERATOR | 130,216 | 3.7% |
| RETURN_VALUE | 100,357 | 2.9% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,035,719 | 55.8% |
| LOAD_FAST | 184,640 | 9.9% |
| LOAD_ATTR | 179,855 | 9.7% |
| LOAD_ATTR_INSTANCE_VALUE | 128,136 | 6.9% |
| BINARY_OP | 97,500 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,840,531 | 99.1% |
| COMPARE_OP | 5,877 | 0.3% |
| POP_JUMP_IF_TRUE | 4,939 | 0.3% |
| COMPARE_OP_INT | 3,965 | 0.2% |
| COMPARE_OP_STR | 1,580 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,321,735 | 30.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,669,040 | 24.6% |
| LOAD_ATTR_WITH_HINT | 1,568,540 | 14.5% |
| LOAD_GLOBAL_MODULE | 735,058 | 6.8% |
| BUILD_TUPLE | 561,713 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,911,612 | 72.9% |
| RETURN_VALUE | 1,146,100 | 10.6% |
| POP_JUMP_IF_TRUE | 1,085,020 | 10.0% |
| COPY | 522,420 | 4.8% |
| SWAP | 176,334 | 1.6% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,040 | 57.9% |
| LOAD_FAST | 1,680 | 19.3% |
| BINARY_SLICE | 1,600 | 18.4% |
| LOAD_GLOBAL_MODULE | 280 | 3.2% |
| LOAD_ATTR | 100 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 8,700 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,195,686 | 40.4% |
| COPY | 1,381,862 | 13.3% |
| CALL_BUILTIN_FAST | 681,137 | 6.6% |
| LOAD_ATTR_SLOT | 608,659 | 5.9% |
| CONTAINS_OP | 522,420 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,916,361 | 18.5% |
| LOAD_ATTR_WITH_HINT | 1,407,840 | 13.6% |
| COPY | 1,381,862 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,352,069 | 13.0% |
| BINARY_SUBSCR_DICT | 1,026,602 | 9.9% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 2,319,551 | 59.2% |
| CALL_PY_EXACT_ARGS | 836,734 | 21.3% |
| CALL | 408,080 | 10.4% |
| BINARY_SUBSCR_GETITEM | 263,960 | 6.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 85,380 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,619,161 | 92.3% |
| RETURN_GENERATOR | 297,335 | 7.6% |
| MAKE_CELL | 1,760 | 0.0% |
| RESUME | 1,686 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,883 | 96.1% |
| LOAD_GLOBAL_MODULE | 280 | 3.4% |
| LOAD_GLOBAL | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,762 | 45.9% |
| NOP | 1,661 | 20.2% |
| PUSH_EXC_INFO | 1,600 | 19.5% |
| RETURN_CONST | 1,020 | 12.4% |
| LOAD_GLOBAL_MODULE | 120 | 1.5% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 88,334 | 24.2% |
| CALL | 79,512 | 21.8% |
| STORE_FAST | 77,751 | 21.3% |
| NOP | 39,876 | 10.9% |
| POP_EXCEPT | 39,636 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 126,436 | 34.7% |
| RETURN_VALUE | 79,512 | 21.8% |
| RETURN_CONST | 79,512 | 21.8% |
| LOAD_FAST | 39,643 | 10.9% |
| JUMP_BACKWARD | 38,842 | 10.6% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,199,211 | 93.1% |
| RETURN_VALUE | 433,600 | 4.9% |
| LOAD_ATTR_INSTANCE_VALUE | 88,847 | 1.0% |
| LOAD_DEREF | 39,603 | 0.4% |
| LOAD_GLOBAL_MODULE | 39,536 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 8,802,722 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 39,536 | 95.5% |
| BUILD_MAP | 720 | 1.7% |
| RETURN_VALUE | 640 | 1.5% |
| MAP_ADD | 240 | 0.6% |
| BUILD_CONST_KEY_MAP | 160 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,276 | 97.3% |
| STORE_FAST | 720 | 1.7% |
| LOAD_DEREF | 160 | 0.4% |
| RETURN_VALUE | 80 | 0.2% |
| BUILD_MAP | 80 | 0.2% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_WITH_HINT | 431,980 | 24.6% |
| COMPARE_OP_INT | 352,560 | 20.1% |
| IS_OP | 264,000 | 15.1% |
| TO_BOOL_STR | 129,480 | 7.4% |
| POP_EXCEPT | 128,335 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 860,578 | 49.1% |
| JUMP_FORWARD | 441,280 | 25.2% |
| JUMP_BACKWARD | 321,487 | 18.3% |
| POP_JUMP_IF_NOT_NONE | 88,020 | 5.0% |
| FOR_ITER_LIST | 17,040 | 1.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,858,015 | 43.7% |
| JUMP_BACKWARD | 4,808,705 | 43.3% |
| SWAP | 1,206,166 | 10.9% |
| LOAD_FAST | 211,696 | 1.9% |
| FOR_ITER | 22,178 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,577,393 | 23.2% |
| LOAD_FAST | 2,300,856 | 20.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,747,252 | 15.7% |
| RETURN_CONST | 1,311,479 | 11.8% |
| SWAP | 1,116,160 | 10.0% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 289,441 | 56.9% |
| RETURN_VALUE | 177,839 | 35.0% |
| LOAD_FAST | 19,600 | 3.9% |
| BEFORE_ASYNC_WITH | 10,720 | 2.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 10,600 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 508,800 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 199,260 | 98.7% |
| STORE_NAME | 1,740 | 0.9% |
| STORE_FAST | 880 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 197,520 | 97.8% |
| STORE_NAME | 4,200 | 2.1% |
| PUSH_EXC_INFO | 160 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 201,117 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 199,260 | 99.1% |
| STORE_FAST | 1,157 | 0.6% |
| STORE_NAME | 660 | 0.3% |
| PUSH_EXC_INFO | 40 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,564,046 | 46.8% |
| LOAD_GLOBAL_BUILTIN | 2,804,560 | 28.7% |
| LOAD_GLOBAL_MODULE | 1,128,672 | 11.6% |
| LOAD_CONST | 382,642 | 3.9% |
| LOAD_FAST | 263,300 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,568,851 | 77.6% |
| POP_JUMP_IF_TRUE | 1,260,796 | 12.9% |
| COPY | 359,205 | 3.7% |
| RETURN_VALUE | 305,897 | 3.1% |
| EXTENDED_ARG | 264,000 | 2.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,249,940 | 40.7% |
| POP_JUMP_IF_FALSE | 1,563,907 | 12.1% |
| POP_JUMP_IF_TRUE | 1,281,106 | 9.9% |
| STORE_SUBSCR_DICT | 1,130,548 | 8.8% |
| MAP_ADD | 860,480 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 4,808,705 | 37.3% |
| FOR_ITER_LIST | 2,624,354 | 20.3% |
| FOR_ITER_TUPLE | 2,190,811 | 17.0% |
| FOR_ITER_RANGE | 1,482,970 | 11.5% |
| LOAD_FAST | 1,318,916 | 10.2% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 574,217 | 99.8% |
| RESUME | 1,218 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 318,018 | 55.3% |
| SEND_GEN | 257,417 | 44.7% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,415,493 | 38.1% |
| POP_TOP | 1,060,924 | 28.6% |
| EXTENDED_ARG | 441,280 | 11.9% |
| POP_JUMP_IF_FALSE | 239,667 | 6.5% |
| DELETE_FAST | 126,436 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,530,777 | 68.2% |
| LOAD_GLOBAL_BUILTIN | 476,197 | 12.8% |
| NOP | 258,800 | 7.0% |
| LOAD_CONST | 209,034 | 5.6% |
| LOAD_GLOBAL_MODULE | 100,160 | 2.7% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 168,399 | 22.2% |
| LOAD_ATTR_SLOT | 167,940 | 22.1% |
| RETURN_VALUE | 127,616 | 16.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 95,040 | 12.5% |
| BINARY_SUBSCR_DICT | 88,120 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 759,455 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,735,648 | 83.4% |
| LOAD_ATTR_SLOT | 1,334,120 | 16.5% |
| BINARY_SLICE | 1,760 | 0.0% |
| LOAD_DEREF | 207 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 7,992,643 | 99.0% |
| STORE_FAST | 79,112 | 1.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,970,150 | 71.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,444,214 | 6.9% |
| LOAD_ATTR_SLOT | 1,336,060 | 6.4% |
| LOAD_GLOBAL_MODULE | 1,258,776 | 6.0% |
| LOAD_DEREF | 984,826 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,484,326 | 21.5% |
| PUSH_NULL | 4,013,531 | 19.3% |
| LOAD_FAST | 3,509,400 | 16.9% |
| LOAD_FAST_LOAD_FAST | 2,461,201 | 11.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,155,523 | 5.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,078,029 | 20.3% |
| LOAD_CONST | 6,991,964 | 10.1% |
| POP_JUMP_IF_FALSE | 5,712,672 | 8.2% |
| STORE_ATTR_SLOT | 4,841,861 | 7.0% |
| LOAD_ATTR_SLOT | 3,347,470 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,500,423 | 26.7% |
| LOAD_CONST | 6,991,964 | 10.1% |
| STORE_FAST | 5,119,346 | 7.4% |
| COMPARE_OP_INT | 4,592,546 | 6.6% |
| COMPARE_OP_STR | 4,526,456 | 6.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,281,741 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 1,014,787 | 9.9% |
| LOAD_DEREF | 963,740 | 9.4% |
| STORE_FAST | 958,742 | 9.4% |
| POP_JUMP_IF_FALSE | 928,882 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,217,643 | 11.9% |
| PUSH_NULL | 1,010,981 | 9.9% |
| CALL_PY_EXACT_ARGS | 995,788 | 9.7% |
| LOAD_ATTR | 984,826 | 9.6% |
| LOAD_DEREF | 963,740 | 9.4% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 51,684,487 | 15.2% |
| RESUME_CHECK | 44,436,787 | 13.0% |
| POP_JUMP_IF_FALSE | 38,216,185 | 11.2% |
| LOAD_GLOBAL_BUILTIN | 23,231,917 | 6.8% |
| LOAD_CONST | 18,500,423 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 53,129,879 | 15.6% |
| LOAD_ATTR_SLOT | 33,001,953 | 9.7% |
| LOAD_ATTR_WITH_HINT | 17,907,472 | 5.3% |
| LOAD_ATTR | 14,970,150 | 4.4% |
| LOAD_ATTR_METHOD_NO_DICT | 14,082,718 | 4.1% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,386,403 | 63.9% |
| LOAD_FAST_AND_CLEAR | 783,840 | 36.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,386,403 | 63.9% |
| LOAD_FAST_AND_CLEAR | 783,840 | 36.1% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 88,020 | 35.5% |
| STORE_ATTR_SLOT | 87,980 | 35.5% |
| LOAD_ATTR_METHOD_NO_DICT | 45,289 | 18.3% |
| POP_TOP | 10,576 | 4.3% |
| JUMP_FORWARD | 5,040 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 177,900 | 71.8% |
| CALL_METHOD_DESCRIPTOR_O | 44,449 | 17.9% |
| POP_JUMP_IF_NOT_NONE | 9,460 | 3.8% |
| LOAD_CONST | 5,600 | 2.3% |
| LOAD_FAST_CHECK | 5,000 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,466,876 | 19.5% |
| NOP | 4,945,376 | 10.2% |
| STORE_ATTR_SLOT | 4,061,618 | 8.4% |
| POP_JUMP_IF_FALSE | 2,963,294 | 6.1% |
| LOAD_GLOBAL_MODULE | 2,774,259 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 6,465,602 | 13.3% |
| LOAD_FAST | 5,800,171 | 11.9% |
| BINARY_SUBSCR_DICT | 4,718,626 | 9.7% |
| IS_OP | 4,564,046 | 9.4% |
| LOAD_ATTR_INSTANCE_VALUE | 3,697,322 | 7.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,893 | 11.8% |
| POP_JUMP_IF_FALSE | 11,200 | 10.3% |
| LOAD_FAST | 10,692 | 9.8% |
| RESUME_CHECK | 7,227 | 6.6% |
| RESUME | 7,086 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,594 | 32.7% |
| LOAD_GLOBAL_BUILTIN | 18,796 | 17.2% |
| LOAD_FAST | 16,124 | 14.8% |
| LOAD_ATTR | 14,196 | 13.0% |
| CALL | 7,317 | 6.7% |


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
| MAKE_CELL | 2,210,091 | 49.9% |
| CALL_PY_EXACT_ARGS | 813,877 | 18.4% |
| CALL_PY_WITH_DEFAULTS | 720,206 | 16.3% |
| CALL_KW | 369,741 | 8.4% |
| CACHE | 267,160 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,210,091 | 49.9% |
| RESUME_CHECK | 2,135,632 | 48.2% |
| RETURN_GENERATOR | 80,399 | 1.8% |
| RESUME | 1,540 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 344,080 | 39.5% |
| STORE_FAST | 168,160 | 19.3% |
| RETURN_VALUE | 88,220 | 10.1% |
| BINARY_OP | 88,000 | 10.1% |
| CALL_KW | 88,000 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 860,480 | 98.9% |
| LOAD_CONST | 9,120 | 1.0% |
| DICT_UPDATE | 240 | 0.0% |
| BUILD_MAP | 160 | 0.0% |
| CALL_FUNCTION_EX | 80 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 21,922,140 | 32.1% |
| CONTAINS_OP | 7,911,612 | 11.6% |
| IS_OP | 7,568,851 | 11.1% |
| COMPARE_OP_INT | 7,070,662 | 10.4% |
| TO_BOOL | 5,874,572 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,216,185 | 56.0% |
| LOAD_GLOBAL_MODULE | 5,855,776 | 8.6% |
| LOAD_CONST | 5,712,672 | 8.4% |
| RETURN_CONST | 5,005,428 | 7.3% |
| LOAD_FAST_LOAD_FAST | 2,963,294 | 4.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,759,539 | 68.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,495,398 | 21.6% |
| LOAD_DEREF | 312,506 | 4.5% |
| LOAD_ATTR_SLOT | 256,000 | 3.7% |
| LOAD_ATTR_WITH_HINT | 95,726 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,792,932 | 69.2% |
| RETURN_CONST | 669,214 | 9.7% |
| LOAD_GLOBAL_MODULE | 290,283 | 4.2% |
| NOP | 265,200 | 3.8% |
| LOAD_CONST | 202,579 | 2.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,771,264 | 74.8% |
| LOAD_ATTR_INSTANCE_VALUE | 940,812 | 14.7% |
| LOAD_DEREF | 451,172 | 7.1% |
| LOAD_GLOBAL_MODULE | 92,787 | 1.5% |
| EXTENDED_ARG | 88,020 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,242,731 | 35.1% |
| LOAD_FAST_LOAD_FAST | 1,242,568 | 19.5% |
| LOAD_GLOBAL_MODULE | 1,236,469 | 19.4% |
| LOAD_GLOBAL_BUILTIN | 666,437 | 10.4% |
| RETURN_CONST | 421,018 | 6.6% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,163,742 | 37.0% |
| TO_BOOL | 2,914,307 | 20.9% |
| IS_OP | 1,260,796 | 9.0% |
| CONTAINS_OP | 1,085,020 | 7.8% |
| TO_BOOL_INT | 1,080,679 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,601,622 | 47.3% |
| JUMP_BACKWARD | 1,281,106 | 9.2% |
| LOAD_CONST | 1,198,638 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 803,472 | 5.8% |
| LOAD_FAST_LOAD_FAST | 768,787 | 5.5% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,800 | 47.3% |
| CALL_KW | 1,520 | 25.7% |
| LOAD_GLOBAL_MODULE | 860 | 14.5% |
| LOAD_CONST | 400 | 6.8% |
| LOAD_FAST | 320 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,680 | 70.0% |
| COPY | 400 | 16.7% |
| LOAD_CONST | 320 | 13.3% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 179,219 | 49.9% |
| POP_JUMP_IF_TRUE | 177,380 | 49.4% |
| CALL_INTRINSIC_1 | 1,320 | 0.4% |
| POP_JUMP_IF_FALSE | 1,040 | 0.3% |
| DELETE_FAST | 399 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 178,819 | 98.3% |
| PUSH_EXC_INFO | 1,819 | 1.0% |
| CALL_INTRINSIC_1 | 1,320 | 0.7% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,038,979 | 29.2% |
| POP_JUMP_IF_FALSE | 5,005,428 | 24.2% |
| STORE_ATTR_SLOT | 2,311,976 | 11.2% |
| STORE_FAST | 1,566,676 | 7.6% |
| FOR_ITER | 1,311,479 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,284,236 | 59.4% |
| INTERPRETER_EXIT | 6,351,265 | 30.7% |
| TO_BOOL_BOOL | 612,985 | 3.0% |
| STORE_FAST | 354,203 | 1.7% |
| RETURN_VALUE | 306,110 | 1.5% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 318,018 | 62.2% |
| LOAD_CONST | 191,045 | 37.4% |
| SEND | 2,088 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 317,572 | 62.1% |
| END_SEND | 188,319 | 36.8% |
| SEND | 2,088 | 0.4% |
| POP_TOP | 1,586 | 0.3% |
| SEND_GEN | 1,586 | 0.3% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80,000 | 45.0% |
| STORE_FAST_LOAD_FAST | 80,000 | 45.0% |
| RETURN_GENERATOR | 8,000 | 4.5% |
| LOAD_FAST | 8,000 | 4.5% |
| JUMP_FORWARD | 1,760 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 177,760 | 100.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,200,807 | 85.2% |
| SET_FUNCTION_ATTRIBUTE | 207,872 | 14.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 515,129 | 36.6% |
| LOAD_FAST | 283,135 | 20.1% |
| CALL | 268,034 | 19.0% |
| SET_FUNCTION_ATTRIBUTE | 207,872 | 14.8% |
| STORE_DEREF | 78,673 | 5.6% |


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
| LOAD_FAST | 737,103 | 70.3% |
| LOAD_GLOBAL_MODULE | 265,180 | 25.3% |
| LOAD_FAST_LOAD_FAST | 22,689 | 2.2% |
| LOAD_DEREF | 10,960 | 1.0% |
| STORE_ATTR | 7,940 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 455,762 | 43.5% |
| LOAD_GLOBAL_MODULE | 179,153 | 17.1% |
| LOAD_GLOBAL_BUILTIN | 176,974 | 16.9% |
| LOAD_CONST | 95,701 | 9.1% |
| LOAD_FAST_LOAD_FAST | 91,678 | 8.7% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 169,124 | 21.3% |
| LOAD_CONST | 129,559 | 16.4% |
| CALL_BUILTIN_CLASS | 89,500 | 11.3% |
| MAKE_FUNCTION | 88,007 | 11.1% |
| JUMP_FORWARD | 88,007 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 266,251 | 33.6% |
| LOAD_CONST | 207,547 | 26.2% |
| LOAD_FAST | 189,555 | 23.9% |
| LOAD_DEREF | 49,174 | 6.2% |
| LOAD_GLOBAL_BUILTIN | 38,942 | 4.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 13,838,679 | 15.7% |
| LOAD_ATTR_INSTANCE_VALUE | 6,944,754 | 7.9% |
| BINARY_SUBSCR_DICT | 6,700,842 | 7.6% |
| FOR_ITER_TUPLE | 6,580,500 | 7.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,958,188 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,684,487 | 58.6% |
| LOAD_FAST_LOAD_FAST | 9,466,876 | 10.7% |
| NOP | 7,384,311 | 8.4% |
| LOAD_GLOBAL_MODULE | 4,003,848 | 4.5% |
| LOAD_GLOBAL_BUILTIN | 2,897,406 | 3.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 746,426 | 74.9% |
| FOR_ITER_TUPLE | 95,100 | 9.5% |
| COPY | 88,380 | 8.9% |
| SWAP | 39,316 | 3.9% |
| FOR_ITER_LIST | 26,640 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 407,760 | 40.9% |
| TO_BOOL_STR | 95,040 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 88,100 | 8.8% |
| LOAD_GLOBAL_MODULE | 87,960 | 8.8% |
| STORE_ATTR_SLOT | 87,960 | 8.8% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 4,138,694 | 74.2% |
| UNPACK_SEQUENCE_TUPLE | 1,268,860 | 22.7% |
| UNPACK_EX | 88,000 | 1.6% |
| STORE_FAST_STORE_FAST | 68,560 | 1.2% |
| UNPACK_SEQUENCE | 10,680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,660,189 | 65.6% |
| STORE_FAST | 1,266,540 | 22.7% |
| LOAD_GLOBAL_MODULE | 191,272 | 3.4% |
| NOP | 149,500 | 2.7% |
| LOAD_GLOBAL_BUILTIN | 127,956 | 2.3% |


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
| LOAD_FAST | 4,897,674 | 31.0% |
| BINARY_OP_ADD_INT | 2,768,102 | 17.5% |
| LOAD_FAST_AND_CLEAR | 1,386,403 | 8.8% |
| SWAP | 1,381,862 | 8.8% |
| FOR_ITER | 1,116,160 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,489,506 | 28.5% |
| STORE_ATTR_WITH_HINT | 1,407,840 | 8.9% |
| SWAP | 1,381,862 | 8.8% |
| STORE_FAST | 1,381,059 | 8.8% |
| STORE_ATTR_INSTANCE_VALUE | 1,352,069 | 8.6% |


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
| CALL_BUILTIN_CLASS | 9,080 | 58.1% |
| FOR_ITER | 1,860 | 11.9% |
| RETURN_VALUE | 1,420 | 9.1% |
| RETURN_GENERATOR | 800 | 5.1% |
| CALL | 420 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 10,680 | 68.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,040 | 13.1% |
| STORE_FAST | 1,920 | 12.3% |
| UNPACK_SEQUENCE_TUPLE | 520 | 3.3% |
| UNPACK_SEQUENCE | 320 | 2.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 393,268 | 26.7% |
| SEND | 317,572 | 21.6% |
| YIELD_VALUE | 258,663 | 17.6% |
| BUILD_TUPLE | 106,300 | 7.2% |
| LOAD_FAST | 80,212 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,118,322 | 76.0% |
| YIELD_VALUE | 258,663 | 17.6% |
| STORE_FAST | 93,280 | 6.3% |
| UNPACK_SEQUENCE_TUPLE | 200 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 80 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 9,863 | 37.8% |
| CACHE | 7,437 | 28.5% |
| POP_TOP | 2,366 | 9.1% |
| COPY_FREE_VARS | 1,686 | 6.5% |
| MAKE_CELL | 1,540 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,196 | 39.0% |
| LOAD_GLOBAL | 7,086 | 27.1% |
| LOAD_CONST | 1,500 | 5.7% |
| LOAD_FAST_LOAD_FAST | 1,426 | 5.5% |
| NOP | 1,380 | 5.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 322,297 | 27.7% |
| LOAD_FAST_LOAD_FAST | 271,920 | 23.4% |
| LOAD_ATTR_INSTANCE_VALUE | 270,812 | 23.3% |
| BINARY_OP | 201,971 | 17.4% |
| BINARY_OP_MULTIPLY_FLOAT | 87,920 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 470,691 | 40.5% |
| LOAD_FAST | 359,403 | 30.9% |
| STORE_FAST | 329,346 | 28.3% |
| CALL_ALLOC_AND_ENTER_INIT | 1,920 | 0.2% |
| RETURN_VALUE | 320 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,116,244 | 41.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,152,576 | 22.4% |
| CALL | 641,826 | 12.5% |
| LOAD_FAST | 480,941 | 9.4% |
| CALL_LEN | 354,008 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,768,102 | 53.9% |
| RETURN_VALUE | 1,246,946 | 24.3% |
| LOAD_GLOBAL_MODULE | 360,429 | 7.0% |
| LOAD_CONST | 333,943 | 6.5% |
| STORE_FAST | 120,082 | 2.3% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 110,500 | 28.7% |
| LOAD_FAST_LOAD_FAST | 90,000 | 23.4% |
| RETURN_VALUE | 89,360 | 23.2% |
| LOAD_CONST | 88,240 | 23.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,300 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 108,760 | 28.3% |
| LIST_APPEND | 87,980 | 22.9% |
| LOAD_GLOBAL_MODULE | 87,980 | 22.9% |
| LOAD_FAST | 45,480 | 11.8% |
| CALL | 45,280 | 11.8% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 184,080 | 88.7% |
| LOAD_CONST | 18,915 | 9.1% |
| LOAD_FAST_LOAD_FAST | 4,320 | 2.1% |
| BINARY_OP | 220 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 87,920 | 42.4% |
| LOAD_CONST | 87,900 | 42.3% |
| CALL_BUILTIN_O | 19,435 | 9.4% |
| COMPARE_OP_FLOAT | 7,720 | 3.7% |
| STORE_FAST | 4,340 | 2.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 320,953 | 49.3% |
| LOAD_FAST_LOAD_FAST | 174,980 | 26.9% |
| LOAD_CONST | 96,930 | 14.9% |
| BINARY_OP_ADD_INT | 39,516 | 6.1% |
| LOAD_GLOBAL_MODULE | 17,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 321,713 | 49.4% |
| BINARY_OP | 175,040 | 26.9% |
| COMPARE_OP_INT | 87,960 | 13.5% |
| STORE_FAST | 51,196 | 7.9% |
| LOAD_CONST | 6,650 | 1.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 446,010 | 54.8% |
| LOAD_FAST | 175,778 | 21.6% |
| CALL | 88,191 | 10.8% |
| RETURN_VALUE | 77,193 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 15,331 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 293,163 | 36.0% |
| LOAD_CONST | 266,400 | 32.8% |
| SWAP | 175,829 | 21.6% |
| CALL | 55,957 | 6.9% |
| LOAD_FAST | 15,701 | 1.9% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 791,223 | 39.4% |
| LOAD_FAST | 524,070 | 26.1% |
| BINARY_OP_MULTIPLY_INT | 321,713 | 16.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 263,880 | 13.2% |
| LOAD_FAST_LOAD_FAST | 62,130 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,048,163 | 52.2% |
| RETURN_VALUE | 322,613 | 16.1% |
| BINARY_OP | 176,200 | 8.8% |
| STORE_FAST | 170,989 | 8.5% |
| BINARY_SUBSCR_LIST_INT | 72,295 | 3.6% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,718,626 | 43.1% |
| LOAD_FAST | 3,558,023 | 32.5% |
| LOAD_CONST | 1,318,974 | 12.0% |
| COPY | 1,026,602 | 9.4% |
| CALL | 225,885 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,700,842 | 61.2% |
| LOAD_CONST | 1,405,943 | 12.8% |
| RETURN_VALUE | 1,067,569 | 9.7% |
| LOAD_FAST | 799,136 | 7.3% |
| PUSH_EXC_INFO | 185,338 | 1.7% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 576,611 | 99.6% |
| LOAD_CONST | 1,620 | 0.3% |
| LOAD_FAST_LOAD_FAST | 740 | 0.1% |
| BINARY_SUBSCR | 140 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 315,031 | 54.4% |
| COPY_FREE_VARS | 263,960 | 45.6% |
| BUILD_TUPLE | 160 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 777,620 | 77.4% |
| LOAD_FAST | 79,145 | 7.9% |
| LOAD_FAST_LOAD_FAST | 74,395 | 7.4% |
| BINARY_OP_SUBTRACT_INT | 72,295 | 7.2% |
| BINARY_SUBSCR | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 321,295 | 32.0% |
| LOAD_ATTR_SLOT | 255,198 | 25.4% |
| LOAD_FAST_LOAD_FAST | 129,650 | 12.9% |
| TO_BOOL_BOOL | 88,560 | 8.8% |
| LOAD_ATTR_METHOD_NO_DICT | 63,840 | 6.4% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 233,680 | 91.1% |
| LOAD_FAST_LOAD_FAST | 11,820 | 4.6% |
| LOAD_FAST | 10,260 | 4.0% |
| CALL_BUILTIN_O | 600 | 0.2% |
| BINARY_SUBSCR | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 207,080 | 80.7% |
| LOAD_ATTR_METHOD_NO_DICT | 38,260 | 14.9% |
| STORE_FAST | 9,760 | 3.8% |
| LIST_APPEND | 620 | 0.2% |
| PUSH_EXC_INFO | 440 | 0.2% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,482,689 | 92.4% |
| LOAD_FAST_LOAD_FAST | 121,360 | 7.6% |
| BINARY_SUBSCR | 640 | 0.0% |
| LOAD_FAST | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 688,240 | 42.9% |
| LOAD_ATTR_SLOT | 223,019 | 13.9% |
| STORE_FAST | 222,180 | 13.8% |
| CALL_BUILTIN_O | 176,880 | 11.0% |
| RETURN_VALUE | 99,090 | 6.2% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 177,160 | 59.6% |
| LOAD_FAST_LOAD_FAST | 93,401 | 31.4% |
| LOAD_FAST | 9,280 | 3.1% |
| LOAD_CONST | 8,000 | 2.7% |
| LOAD_GLOBAL_MODULE | 2,226 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 294,975 | 99.2% |
| COPY_FREE_VARS | 1,280 | 0.4% |
| POP_TOP | 920 | 0.3% |
| RESUME | 40 | 0.0% |
| STORE_FAST | 20 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 105,815 | 38.1% |
| BINARY_OP_SUBTRACT_INT | 61,530 | 22.1% |
| LOAD_FAST_LOAD_FAST | 41,676 | 15.0% |
| LOAD_CONST | 24,161 | 8.7% |
| PUSH_NULL | 23,349 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 167,997 | 60.4% |
| COPY_FREE_VARS | 85,380 | 30.7% |
| POP_TOP | 11,941 | 4.3% |
| GET_AWAITABLE | 10,600 | 3.8% |
| MAKE_CELL | 784 | 0.3% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,175,126 | 29.7% |
| LOAD_FAST | 2,113,365 | 28.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,078,686 | 14.7% |
| LOAD_ATTR_SLOT | 952,040 | 13.0% |
| PUSH_NULL | 437,640 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,145,866 | 29.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,262,317 | 17.2% |
| LOAD_FAST | 1,067,500 | 14.6% |
| CALL | 964,939 | 13.2% |
| GET_ITER | 847,422 | 11.6% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,140,944 | 56.5% |
| LOAD_FAST_LOAD_FAST | 403,346 | 20.0% |
| LOAD_GLOBAL_MODULE | 176,040 | 8.7% |
| BUILD_TUPLE | 167,920 | 8.3% |
| LOAD_FAST | 71,722 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 681,137 | 33.7% |
| TO_BOOL_BOOL | 579,360 | 28.7% |
| POP_TOP | 236,377 | 11.7% |
| RETURN_VALUE | 225,672 | 11.2% |
| STORE_FAST | 136,717 | 6.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,262,317 | 56.3% |
| LOAD_FAST | 534,347 | 23.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 168,080 | 7.5% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 88,000 | 3.9% |
| LOAD_ATTR | 81,964 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,152,576 | 51.4% |
| STORE_FAST | 421,434 | 18.8% |
| RETURN_VALUE | 301,030 | 13.4% |
| POP_TOP | 91,814 | 4.1% |
| LOAD_ATTR_METHOD_NO_DICT | 88,000 | 3.9% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 481,022 | 29.9% |
| LOAD_ATTR_INSTANCE_VALUE | 406,981 | 25.3% |
| BINARY_SUBSCR_TUPLE_INT | 176,880 | 11.0% |
| LOAD_ATTR_SLOT | 118,140 | 7.3% |
| RETURN_GENERATOR | 118,075 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 550,835 | 34.3% |
| RETURN_VALUE | 443,411 | 27.6% |
| STORE_FAST | 347,437 | 21.6% |
| LOAD_FAST | 90,346 | 5.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 87,960 | 5.5% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,837,651 | 40.5% |
| LOAD_GLOBAL_MODULE | 1,410,706 | 31.1% |
| LOAD_FAST_LOAD_FAST | 525,575 | 11.6% |
| LOAD_ATTR | 375,265 | 8.3% |
| BUILD_TUPLE | 279,425 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,102,035 | 90.4% |
| RETURN_VALUE | 274,767 | 6.1% |
| COPY | 158,231 | 3.5% |
| TO_BOOL | 2,460 | 0.1% |
| YIELD_VALUE | 2,020 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,464,131 | 61.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,366,038 | 24.2% |
| LOAD_ATTR_SLOT | 432,280 | 7.7% |
| LOAD_ATTR_WITH_HINT | 359,289 | 6.4% |
| LOAD_DEREF | 4,600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,134,009 | 37.9% |
| LOAD_CONST | 1,187,314 | 21.1% |
| RETURN_VALUE | 879,623 | 15.6% |
| LOAD_FAST | 386,908 | 6.9% |
| BINARY_OP_ADD_INT | 354,008 | 6.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 279,661 | 42.7% |
| BUILD_CONST_KEY_MAP | 176,880 | 27.0% |
| BUILD_TUPLE | 88,223 | 13.5% |
| BINARY_OP_ADD_INT | 60,680 | 9.3% |
| BINARY_SLICE | 39,516 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 298,106 | 45.5% |
| JUMP_BACKWARD | 157,243 | 24.0% |
| NOP | 90,716 | 13.8% |
| LOAD_FAST_LOAD_FAST | 89,000 | 13.6% |
| RETURN_CONST | 10,400 | 1.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,013,638 | 40.8% |
| LOAD_CONST | 2,695,711 | 36.5% |
| BUILD_TUPLE | 527,960 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 435,520 | 5.9% |
| LOAD_ATTR_METHOD_NO_DICT | 189,006 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,958,188 | 80.8% |
| BINARY_OP_SUBTRACT_INT | 263,880 | 3.6% |
| LOAD_FAST | 186,420 | 2.5% |
| POP_TOP | 179,636 | 2.4% |
| CALL_METHOD_DESCRIPTOR_O | 167,960 | 2.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 304,816 | 39.4% |
| LOAD_FAST_LOAD_FAST | 232,496 | 30.0% |
| LOAD_ATTR_METHOD_NO_DICT | 138,666 | 17.9% |
| LOAD_CONST | 57,077 | 7.4% |
| LOAD_ATTR | 40,316 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 345,213 | 44.6% |
| STORE_FAST | 335,459 | 43.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 88,000 | 11.4% |
| GET_ITER | 1,880 | 0.2% |
| RETURN_VALUE | 1,320 | 0.2% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 8,192,694 | 87.6% |
| LOAD_ATTR | 1,155,523 | 12.4% |
| CALL | 3,980 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,565 | 0.0% |
| LOAD_FAST | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,530,760 | 27.1% |
| STORE_FAST | 1,964,692 | 21.0% |
| POP_TOP | 1,321,072 | 14.1% |
| CALL_BUILTIN_CLASS | 1,078,686 | 11.5% |
| TO_BOOL_BOOL | 970,564 | 10.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,180,930 | 70.2% |
| BUILD_TUPLE | 1,541,902 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 337,880 | 3.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 167,960 | 1.9% |
| CALL | 154,327 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,324,753 | 94.6% |
| RETURN_VALUE | 162,678 | 1.8% |
| UNPACK_SEQUENCE_TUPLE | 125,300 | 1.4% |
| LOAD_CONST | 103,061 | 1.2% |
| STORE_FAST | 44,788 | 0.5% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,192,105 | 35.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,780,502 | 24.3% |
| CALL_TYPE_1 | 4,483,086 | 14.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,866,852 | 5.8% |
| LOAD_FAST_LOAD_FAST | 1,642,447 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 30,099,127 | 94.0% |
| COPY_FREE_VARS | 836,734 | 2.6% |
| MAKE_CELL | 813,877 | 2.5% |
| RETURN_GENERATOR | 180,139 | 0.6% |
| TO_BOOL_BOOL | 86,667 | 0.3% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,345,872 | 55.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 484,746 | 20.1% |
| LOAD_ATTR_INSTANCE_VALUE | 255,800 | 10.6% |
| LOAD_FAST_LOAD_FAST | 90,500 | 3.8% |
| BINARY_SLICE | 87,960 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,607,009 | 66.6% |
| MAKE_CELL | 720,206 | 29.9% |
| RETURN_GENERATOR | 82,719 | 3.4% |
| CALL | 1,060 | 0.0% |
| STORE_FAST | 1,040 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 88,000 | 34.8% |
| CALL_TYPE_1 | 87,960 | 34.7% |
| LOAD_ATTR | 71,030 | 28.1% |
| LOAD_FAST | 3,386 | 1.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,300 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 88,000 | 34.8% |
| CONTAINS_OP | 87,980 | 34.8% |
| BUILD_TUPLE | 71,050 | 28.1% |
| STORE_FAST | 4,106 | 1.6% |
| LIST_APPEND | 940 | 0.4% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 176,440 | 48.6% |
| CALL_BUILTIN_CLASS | 88,760 | 24.4% |
| STORE_FAST | 87,960 | 24.2% |
| LOAD_FAST | 8,320 | 2.3% |
| LOAD_GLOBAL_MODULE | 680 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 176,680 | 48.7% |
| CALL_STR_1 | 88,000 | 24.2% |
| BINARY_OP | 87,980 | 24.2% |
| LOAD_FAST_LOAD_FAST | 6,880 | 1.9% |
| STORE_FAST | 1,240 | 0.3% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,762,402 | 98.9% |
| BINARY_SUBSCR_TUPLE_INT | 87,960 | 1.1% |
| CALL | 780 | 0.0% |
| LOAD_GLOBAL_MODULE | 640 | 0.0% |
| LOAD_DEREF | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,483,086 | 57.1% |
| STORE_FAST | 2,089,640 | 26.6% |
| LOAD_GLOBAL_BUILTIN | 500,140 | 6.4% |
| LOAD_GLOBAL_MODULE | 244,895 | 3.1% |
| LOAD_FAST | 180,540 | 2.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 520,382 | 29.8% |
| LOAD_CONST | 431,511 | 24.7% |
| LOAD_FAST | 388,801 | 22.2% |
| BINARY_OP | 181,388 | 10.4% |
| COPY | 174,980 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,227,645 | 70.2% |
| RETURN_VALUE | 519,562 | 29.7% |
| POP_JUMP_IF_TRUE | 920 | 0.1% |
| EXTENDED_ARG | 300 | 0.0% |
| COMPARE_OP | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,592,546 | 56.2% |
| LOAD_FAST_LOAD_FAST | 1,757,526 | 21.5% |
| LOAD_ATTR_INSTANCE_VALUE | 502,308 | 6.1% |
| LOAD_GLOBAL_MODULE | 361,612 | 4.4% |
| LOAD_ATTR_WITH_HINT | 183,009 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,070,662 | 86.6% |
| POP_JUMP_IF_TRUE | 740,274 | 9.1% |
| EXTENDED_ARG | 352,560 | 4.3% |
| RETURN_VALUE | 3,320 | 0.0% |
| COPY | 940 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,526,456 | 71.3% |
| LOAD_FAST_LOAD_FAST | 672,620 | 10.6% |
| LOAD_FAST | 603,325 | 9.5% |
| LOAD_GLOBAL_MODULE | 360,228 | 5.7% |
| LOAD_ATTR_INSTANCE_VALUE | 90,460 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,710,261 | 90.0% |
| POP_JUMP_IF_TRUE | 536,028 | 8.4% |
| RETURN_VALUE | 88,040 | 1.4% |
| COPY | 7,240 | 0.1% |
| EXTENDED_ARG | 2,920 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 92,799 | 95.0% |
| GET_ITER | 3,480 | 3.6% |
| SWAP | 881 | 0.9% |
| FOR_ITER | 260 | 0.3% |
| EXTENDED_ARG | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 92,799 | 95.0% |
| POP_TOP | 4,361 | 4.5% |
| RETURN_CONST | 240 | 0.2% |
| STORE_FAST | 160 | 0.2% |
| RESUME | 100 | 0.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,624,354 | 53.8% |
| GET_ITER | 2,163,607 | 44.4% |
| SWAP | 43,696 | 0.9% |
| LOAD_FAST | 24,520 | 0.5% |
| EXTENDED_ARG | 17,040 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,359,704 | 48.4% |
| LOAD_FAST | 1,270,626 | 26.1% |
| RETURN_CONST | 881,501 | 18.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 320,386 | 6.6% |
| STORE_FAST_LOAD_FAST | 26,640 | 0.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,482,970 | 85.4% |
| GET_ITER | 252,706 | 14.6% |
| FOR_ITER | 300 | 0.0% |
| LOAD_FAST | 200 | 0.0% |
| SWAP | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,488,410 | 85.7% |
| LOAD_CONST | 232,536 | 13.4% |
| LOAD_FAST | 7,910 | 0.5% |
| LOAD_GLOBAL_BUILTIN | 6,860 | 0.4% |
| RETURN_CONST | 260 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,362,358 | 68.1% |
| JUMP_BACKWARD | 2,190,811 | 27.8% |
| LOAD_FAST | 185,575 | 2.4% |
| SWAP | 135,460 | 1.7% |
| FOR_ITER | 800 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,580,500 | 83.6% |
| LOAD_FAST | 760,529 | 9.7% |
| RETURN_CONST | 182,752 | 2.3% |
| SWAP | 135,580 | 1.7% |
| STORE_FAST_LOAD_FAST | 95,100 | 1.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 242,956 | 54.2% |
| LOAD_ATTR_MODULE | 198,100 | 44.2% |
| LOAD_FAST | 4,360 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 2,112 | 0.5% |
| LOAD_ATTR | 560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 159,104 | 35.5% |
| COMPARE_OP_INT | 118,948 | 26.5% |
| CALL_PY_EXACT_ARGS | 79,452 | 17.7% |
| LOAD_FAST | 44,996 | 10.0% |
| CALL | 40,596 | 9.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,129,879 | 87.9% |
| LOAD_FAST_LOAD_FAST | 3,697,322 | 6.1% |
| COPY | 1,352,069 | 2.2% |
| LOAD_ATTR_SLOT | 1,319,895 | 2.2% |
| LOAD_DEREF | 635,849 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,837,136 | 14.6% |
| LOAD_ATTR_METHOD_NO_DICT | 8,571,732 | 14.2% |
| STORE_FAST | 6,944,754 | 11.5% |
| TO_BOOL_BOOL | 6,119,633 | 10.1% |
| RETURN_VALUE | 3,813,836 | 6.3% |


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
| LOAD_FAST | 14,082,718 | 43.9% |
| LOAD_ATTR_INSTANCE_VALUE | 8,571,732 | 26.7% |
| LOAD_ATTR_WITH_HINT | 5,801,468 | 18.1% |
| LOAD_ATTR_SLOT | 2,003,150 | 6.2% |
| RETURN_VALUE | 527,765 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,712,887 | 49.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 8,192,694 | 25.5% |
| LOAD_CONST | 3,155,534 | 9.8% |
| CALL_PY_EXACT_ARGS | 1,866,852 | 5.8% |
| LOAD_FAST_LOAD_FAST | 1,463,087 | 4.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,750,708 | 67.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,467,058 | 12.1% |
| LOAD_ATTR_SLOT | 1,505,814 | 7.4% |
| LOAD_ATTR_WITH_HINT | 1,222,020 | 6.0% |
| LOAD_DEREF | 546,356 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 7,780,502 | 38.1% |
| LOAD_GLOBAL_BUILTIN | 4,626,696 | 22.7% |
| LOAD_FAST | 4,141,465 | 20.3% |
| LOAD_FAST_LOAD_FAST | 1,612,935 | 7.9% |
| LOAD_GLOBAL_MODULE | 797,723 | 3.9% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,666,313 | 96.7% |
| LOAD_FAST | 142,395 | 1.8% |
| LOAD_ATTR_MODULE | 104,998 | 1.3% |
| LOAD_ATTR | 13,244 | 0.2% |
| BINARY_SUBSCR_DICT | 1,760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,286,916 | 79.3% |
| LOAD_FAST | 318,977 | 4.0% |
| LOAD_ATTR_CLASS | 198,100 | 2.5% |
| LOAD_ATTR | 183,354 | 2.3% |
| BINARY_OP | 170,266 | 2.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,818 | 77.3% |
| LOAD_FAST_LOAD_FAST | 860 | 17.4% |
| LOAD_ATTR | 180 | 3.6% |
| LOAD_CONST | 80 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,579 | 32.0% |
| TO_BOOL_BOOL | 1,119 | 22.7% |
| LOAD_FAST | 940 | 19.0% |
| CALL_BUILTIN_FAST | 860 | 17.4% |
| CALL | 240 | 4.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 199,060 | 60.4% |
| LOAD_FAST | 87,212 | 26.5% |
| LOAD_FAST_LOAD_FAST | 42,336 | 12.9% |
| LOAD_ATTR | 700 | 0.2% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 120,328 | 36.5% |
| COMPARE_OP_INT | 79,192 | 24.0% |
| LOAD_FAST | 41,156 | 12.5% |
| LOAD_CONST | 39,716 | 12.1% |
| STORE_FAST | 39,616 | 12.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,420,103 | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE | 177,920 | 6.5% |
| RETURN_VALUE | 101,006 | 3.7% |
| STORE_FAST_LOAD_FAST | 24,144 | 0.9% |
| LOAD_ATTR | 2,570 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,726,348 | 99.9% |
| COPY_FREE_VARS | 1,840 | 0.1% |
| LOAD_GLOBAL_MODULE | 380 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 60 | 0.0% |
| LOAD_ATTR_PROPERTY | 60 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,001,953 | 93.0% |
| LOAD_FAST_LOAD_FAST | 962,265 | 2.7% |
| STORE_FAST_LOAD_FAST | 407,760 | 1.1% |
| COPY | 359,729 | 1.0% |
| BINARY_SUBSCR_LIST_INT | 255,198 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,778,823 | 10.7% |
| LOAD_CONST | 3,347,470 | 9.4% |
| TO_BOOL_NONE | 3,328,797 | 9.4% |
| STORE_FAST | 2,881,180 | 8.1% |
| LOAD_FAST | 2,534,620 | 7.1% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,907,472 | 81.9% |
| COPY | 1,407,840 | 6.4% |
| LOAD_FAST_LOAD_FAST | 1,159,326 | 5.3% |
| LOAD_DEREF | 945,680 | 4.3% |
| LOAD_ATTR_INSTANCE_VALUE | 440,440 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,801,468 | 26.5% |
| LOAD_FAST | 4,148,848 | 19.0% |
| TO_BOOL_BOOL | 2,593,000 | 11.9% |
| LOAD_CONST | 1,952,720 | 8.9% |
| RETURN_VALUE | 1,849,428 | 8.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,556,537 | 25.4% |
| LOAD_FAST | 4,640,789 | 12.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,626,696 | 12.3% |
| POP_JUMP_IF_FALSE | 2,944,496 | 7.8% |
| STORE_FAST | 2,897,406 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,231,917 | 61.7% |
| IS_OP | 2,804,560 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 2,337,638 | 6.2% |
| CALL_BUILTIN_CLASS | 2,175,126 | 5.8% |
| CALL_ISINSTANCE | 1,837,651 | 4.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,550,882 | 19.0% |
| LOAD_FAST | 6,386,005 | 14.2% |
| POP_JUMP_IF_FALSE | 5,855,776 | 13.0% |
| STORE_FAST | 4,003,848 | 8.9% |
| LOAD_GLOBAL_MODULE | 3,278,211 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,131,204 | 35.9% |
| LOAD_ATTR_MODULE | 7,666,313 | 17.1% |
| CALL | 3,590,023 | 8.0% |
| LOAD_GLOBAL_MODULE | 3,278,211 | 7.3% |
| LOAD_FAST_LOAD_FAST | 2,774,259 | 6.2% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,580 | 91.3% |
| LOAD_SUPER_ATTR | 220 | 5.6% |
| EXTENDED_ARG | 120 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,040 | 52.0% |
| LOAD_GLOBAL_MODULE | 1,840 | 46.9% |
| LOAD_GLOBAL | 40 | 1.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 633,205 | 99.9% |
| LOAD_SUPER_ATTR | 720 | 0.1% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 399,556 | 63.0% |
| LOAD_FAST_LOAD_FAST | 191,673 | 30.2% |
| CALL_PY_EXACT_ARGS | 42,036 | 6.6% |
| CALL | 380 | 0.1% |
| LOAD_CONST | 300 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 30,099,127 | 39.5% |
| CACHE | 21,900,968 | 28.7% |
| CALL_FUNCTION_EX | 5,663,874 | 7.4% |
| CALL | 3,972,451 | 5.2% |
| COPY_FREE_VARS | 3,619,161 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,436,787 | 58.2% |
| LOAD_GLOBAL_BUILTIN | 9,556,537 | 12.5% |
| LOAD_GLOBAL_MODULE | 8,550,882 | 11.2% |
| NOP | 5,507,059 | 7.2% |
| LOAD_FAST_LOAD_FAST | 2,675,344 | 3.5% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 319,515 | 55.2% |
| JUMP_BACKWARD_NO_INTERRUPT | 257,417 | 44.5% |
| SEND | 1,586 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 320,175 | 55.3% |
| RESUME_CHECK | 257,171 | 44.5% |
| RESUME | 932 | 0.2% |
| END_SEND | 160 | 0.0% |
| YIELD_VALUE | 80 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,300,948 | 69.7% |
| LOAD_FAST_LOAD_FAST | 1,601,928 | 15.3% |
| SWAP | 1,352,069 | 12.9% |
| LOAD_DEREF | 83,684 | 0.8% |
| BINARY_SUBSCR_DICT | 79,960 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,708,015 | 25.9% |
| LOAD_CONST | 2,700,660 | 25.8% |
| RETURN_CONST | 999,235 | 9.5% |
| LOAD_FAST_LOAD_FAST | 904,472 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 846,135 | 8.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,186,519 | 54.1% |
| LOAD_FAST_LOAD_FAST | 6,465,602 | 42.8% |
| SWAP | 359,729 | 2.4% |
| STORE_FAST_LOAD_FAST | 87,960 | 0.6% |
| STORE_ATTR_SLOT | 16,460 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,841,861 | 32.0% |
| LOAD_FAST_LOAD_FAST | 4,061,618 | 26.9% |
| LOAD_FAST | 2,476,964 | 16.4% |
| RETURN_CONST | 2,311,976 | 15.3% |
| LOAD_GLOBAL_BUILTIN | 704,940 | 4.7% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,407,840 | 99.2% |
| LOAD_FAST_LOAD_FAST | 7,126 | 0.5% |
| LOAD_DEREF | 1,400 | 0.1% |
| LOAD_FAST | 1,040 | 0.1% |
| STORE_ATTR | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 983,695 | 69.3% |
| EXTENDED_ARG | 431,980 | 30.5% |
| RETURN_CONST | 1,040 | 0.1% |
| LOAD_CONST | 511 | 0.0% |
| LOAD_GLOBAL_MODULE | 360 | 0.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,191,988 | 25.6% |
| SWAP | 1,026,602 | 22.0% |
| LOAD_FAST_LOAD_FAST | 897,400 | 19.3% |
| LOAD_CONST | 884,810 | 19.0% |
| LOAD_ATTR_SLOT | 511,688 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,794,472 | 38.5% |
| JUMP_BACKWARD | 1,130,548 | 24.3% |
| LOAD_FAST_LOAD_FAST | 881,420 | 18.9% |
| RETURN_CONST | 189,218 | 4.1% |
| LOAD_CONST | 178,086 | 3.8% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 130,410 | 72.7% |
| LOAD_CONST | 40,156 | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE | 7,960 | 4.4% |
| LOAD_FAST | 500 | 0.3% |
| STORE_SUBSCR | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 68,200 | 38.0% |
| LOAD_FAST_LOAD_FAST | 61,550 | 34.3% |
| LOAD_DEREF | 47,516 | 26.5% |
| RETURN_CONST | 1,460 | 0.8% |
| EXTENDED_ARG | 520 | 0.3% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 440,720 | 52.5% |
| LOAD_FAST | 378,516 | 45.1% |
| LOAD_ATTR_INSTANCE_VALUE | 8,823 | 1.1% |
| LOAD_ATTR_SLOT | 7,960 | 0.9% |
| CALL | 1,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 474,836 | 56.6% |
| POP_JUMP_IF_TRUE | 364,057 | 43.4% |
| TO_BOOL_NONE | 126 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,119,633 | 22.6% |
| RETURN_VALUE | 5,303,709 | 19.6% |
| CALL_ISINSTANCE | 4,102,035 | 15.1% |
| LOAD_ATTR_WITH_HINT | 2,593,000 | 9.6% |
| LOAD_ATTR_SLOT | 2,413,582 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 21,922,140 | 80.9% |
| POP_JUMP_IF_TRUE | 5,163,742 | 19.1% |
| EXTENDED_ARG | 6,932 | 0.0% |
| UNARY_NOT | 1,060 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 580,786 | 30.3% |
| COPY | 573,784 | 30.0% |
| LOAD_FAST | 312,244 | 16.3% |
| RETURN_VALUE | 175,271 | 9.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 150,944 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,080,679 | 56.4% |
| POP_JUMP_IF_FALSE | 833,964 | 43.5% |
| UNARY_NOT | 1,160 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 996,529 | 60.8% |
| LOAD_FAST | 451,171 | 27.5% |
| LOAD_ATTR_WITH_HINT | 187,018 | 11.4% |
| TO_BOOL | 940 | 0.1% |
| STORE_FAST_LOAD_FAST | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,587,321 | 96.9% |
| POP_JUMP_IF_TRUE | 49,933 | 3.0% |
| UNARY_NOT | 620 | 0.0% |
| EXTENDED_ARG | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 3,328,797 | 77.6% |
| LOAD_FAST | 424,073 | 9.9% |
| WITH_EXCEPT_START | 177,300 | 4.1% |
| LOAD_ATTR | 149,215 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 102,184 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,761,287 | 87.6% |
| POP_JUMP_IF_TRUE | 530,336 | 12.4% |
| EXTENDED_ARG | 380 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 118 | 0.0% |
| TO_BOOL | 3 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 909,363 | 73.5% |
| STORE_FAST_LOAD_FAST | 95,040 | 7.7% |
| LOAD_ATTR | 87,960 | 7.1% |
| LOAD_ATTR_WITH_HINT | 80,920 | 6.5% |
| COPY | 50,140 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 880,283 | 71.1% |
| POP_JUMP_IF_TRUE | 227,840 | 18.4% |
| EXTENDED_ARG | 129,480 | 10.5% |


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
| LOAD_FAST | 530,860 | 39.3% |
| CALL_FUNCTION_EX | 431,960 | 32.0% |
| CALL_METHOD_DESCRIPTOR_O | 125,300 | 9.3% |
| RETURN_VALUE | 90,900 | 6.7% |
| END_SEND | 88,240 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,268,860 | 93.9% |
| STORE_FAST | 82,112 | 6.1% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,747,252 | 35.5% |
| RETURN_VALUE | 887,628 | 18.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 856,200 | 17.4% |
| CALL_FUNCTION_EX | 615,920 | 12.5% |
| FOR_ITER_LIST | 320,386 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 4,138,694 | 84.0% |
| STORE_FAST | 698,200 | 14.2% |
| LOAD_FAST_LOAD_FAST | 87,980 | 1.8% |
| LOAD_FAST | 2,240 | 0.0% |
| STORE_DEREF | 600 | 0.0% |


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
|     deferred | 3,884,460 | 27.0% |
|          hit | 10,473,832 | 72.8% |
|         miss | 6,825 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,701 | 21.9% |
| Failure | 16,789 | 78.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 3,996 | 23.8% |
| or | 2,426 | 14.4% |
| multiply different types | 2,300 | 13.7% |
| add other | 1,821 | 10.8% |
| true divide different types | 1,700 | 10.1% |
| remainder | 920 | 5.5% |
| add different types | 861 | 5.1% |
| subtract different types | 840 | 5.0% |
| true divide other | 440 | 2.6% |
| true divide float | 400 | 2.4% |
| floor divide | 260 | 1.5% |
| power | 240 | 1.4% |
| lshift | 200 | 1.2% |
| subtract other | 160 | 1.0% |
| rshift | 125 | 0.7% |
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
|     deferred | 1,478,900 | 9.3% |
|          hit | 14,393,245 | 90.6% |
|         miss | 1,620 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,800 | 49.6% |
| Failure | 4,884 | 50.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 3,301 | 67.6% |
| buffer int | 963 | 19.7% |
| code complex parameters | 400 | 8.2% |
| out of range | 200 | 4.1% |
| list slice | 20 | 0.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,873,935 | 22.2% |
|          hit | 93,635,985 | 77.3% |
|         miss | 437,447 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 58,302 | 45.5% |
| Failure | 69,769 | 54.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 16,079 | 23.0% |
| cfunc noargs | 13,802 | 19.8% |
| class no vectorcall | 8,219 | 11.8% |
| meth descr varargs | 5,274 | 7.6% |
| meth descr method fastcall keywords | 4,076 | 5.8% |
| meth descr varargs keywords | 4,021 | 5.8% |
| cfunc varargs keywords | 4,002 | 5.7% |
| cfunc varargs | 3,868 | 5.5% |
| other | 3,842 | 5.5% |
| no dict | 2,263 | 3.2% |
| class mutable | 1,383 | 2.0% |
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
|     deferred | 1,845,262 | 10.2% |
|          hit | 16,233,432 | 89.6% |
|         miss | 28,488 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,025 | 48.7% |
| Failure | 6,345 | 51.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 2,009 | 31.7% |
| long float | 1,021 | 16.1% |
| baseobject | 1,015 | 16.0% |
| different types | 840 | 13.2% |
| big int | 820 | 12.9% |
| other | 520 | 8.2% |
| tuple | 80 | 1.3% |
| bool | 40 | 0.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 11,087,042 | 43.1% |
|          hit | 14,583,157 | 56.7% |
|         miss | 1,460 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,720 | 14.4% |
| Failure | 22,198 | 85.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 10,716 | 48.3% |
| dict items | 6,340 | 28.6% |
| zip | 1,182 | 5.3% |
| dict keys | 1,020 | 4.6% |
| dict values | 800 | 3.6% |
| other | 600 | 2.7% |
| enumerate | 480 | 2.2% |
| itertools | 420 | 1.9% |
| bytes | 220 | 1.0% |
| map | 140 | 0.6% |
| reversed list | 140 | 0.6% |
| seq iter | 120 | 0.5% |
| ascii string | 20 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,993,042 | 10.4% |
|        deopt | 357,057 | 0.2% |
|          hit | 179,823,339 | 88.7% |
|         miss | 2,143,733 | 1.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 121,182 | 65.3% |
| Failure | 64,371 | 34.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 19,708 | 30.6% |
| method | 17,952 | 27.9% |
| metaclass attribute | 7,857 | 12.2% |
| not managed dict | 7,798 | 12.1% |
| module attr not found | 2,354 | 3.7% |
| shadowed | 2,102 | 3.3% |
| overridden | 1,440 | 2.2% |
| class attr descriptor | 1,280 | 2.0% |
| mutable class | 1,040 | 1.6% |
| non overriding descriptor | 820 | 1.3% |
| non object slot | 820 | 1.3% |
| class method obj | 660 | 1.0% |
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
|     deferred | 55,109 | 0.1% |
|        deopt | 1,060 | 0.0% |
|          hit | 82,558,950 | 99.9% |
|         miss | 11,780 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 54,930 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 900 | 0.1% |
|          hit | 637,925 | 99.7% |

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
|     deferred | 507,477 | 46.6% |
|          hit | 578,278 | 53.1% |
|         miss | 240 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,586 | 43.2% |
| Failure | 2,088 | 56.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 1,848 | 88.5% |
| dict keys | 240 | 11.5% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,002,722 | 3.6% |
|          hit | 26,127,267 | 93.1% |
|         miss | 885,812 | 3.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 37,438 | 82.5% |
| Failure | 7,940 | 17.5% |

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
|     deferred | 537,933 | 10.0% |
|          hit | 4,837,662 | 89.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,620 | 65.2% |
| Failure | 1,935 | 34.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 1,140 | 58.9% |
| py simple | 775 | 40.1% |
| other | 20 | 1.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,888,650 | 19.3% |
|          hit | 36,998,639 | 80.5% |
|         miss | 17,718 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 18,343 | 45.9% |
| Failure | 21,636 | 54.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 6,483 | 30.0% |
| set | 6,020 | 27.8% |
| tuple | 3,220 | 14.9% |
| sequence | 2,466 | 11.4% |
| mapping | 1,181 | 5.5% |
| bytes | 881 | 4.1% |
| float | 860 | 4.0% |
| other | 300 | 1.4% |
| bytearray | 205 | 0.9% |
| number | 20 | 0.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,720 | 0.2% |
|          hit | 6,278,806 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,580 | 89.0% |
| Failure | 320 | 11.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| iterator | 320 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 930,560,636 | 55.7% |
| Not specialized | 173,751,917 | 10.4% |
| Specialized hits | 563,075,299 | 33.7% |
| Specialized misses | 3,540,763 | 0.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 26,873,935 | 34.8% |
| LOAD_ATTR | 20,993,042 | 27.2% |
| FOR_ITER | 11,087,042 | 14.4% |
| TO_BOOL | 8,888,650 | 11.5% |
| BINARY_OP | 3,884,460 | 5.0% |
| COMPARE_OP | 1,845,262 | 2.4% |
| BINARY_SUBSCR | 1,478,900 | 1.9% |
| STORE_ATTR | 1,002,722 | 1.3% |
| STORE_SUBSCR | 537,933 | 0.7% |
| SEND | 507,477 | 0.7% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,137,053 | 32.1% |
| STORE_ATTR_SLOT | 876,974 | 24.7% |
| LOAD_ATTR_METHOD_NO_DICT | 378,989 | 10.7% |
| LOAD_ATTR_INSTANCE_VALUE | 371,633 | 10.5% |
| LOAD_ATTR_WITH_HINT | 186,882 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 181,721 | 5.1% |
| CALL_PY_EXACT_ARGS | 113,640 | 3.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 89,637 | 2.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 40,148 | 1.1% |
| LOAD_ATTR_MODULE | 35,300 | 1.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 25,241,658 | 32.7% |
| Calls to Python functions inlined | 52,024,348 | 67.3% |
| Calls via PyEval_EvalFrame (total) | 25,241,658 | 32.7% |
| Calls via PyEval_EvalFrame (vector) | 23,550,372 | 30.5% |
| Calls via PyEval_EvalFrame (generator) | 1,691,286 | 2.2% |
| Calls via PyEval_EvalFrame (legacy) | 640 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 23,548,792 | 30.5% |
| Calls via PyEval_EvalFrame (build class) | 940 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 3,320,597 | 4.3% |
| Calls via PyEval_EvalFrame (function ex) | 5,708,714 | 7.4% |
| Calls via PyEval_EvalFrame (api) | 5,266,529 | 6.8% |
| Calls via PyEval_EvalFrame (method) | 1,449,535 | 1.9% |
| Frame objects created | 1,415,745 | 1.8% |
| Frames pushed | 38,453,257 | 49.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 99,969,645 | 47.9% |
| Frees to freelist | 100,336,211 |  |
| Allocations | 108,745,111 | 52.1% |
| Allocations to 512 bytes | 107,564,688 | 51.5% |
| Allocations to 4 kbytes | 909,858 | 0.4% |
| Allocations over 4 kbytes | 270,565 | 0.1% |
| Frees | 102,108,375 |  |
| New values | 297,303 |  |
| Interpreter increfs | 780,879,650 | 74.7% |
| Interpreter decrefs | 887,515,405 | 72.7% |
| Increfs | 264,499,757 | 25.3% |
| Decrefs | 332,698,689 | 27.3% |
| Materialize dict (on request) | 2,560 | 0.9% |
| Materialize dict (new key) | 240 | 0.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 2,520 | 0.8% |
| Method cache hits | 23,745,426 |  |
| Method cache misses | 279,369 |  |
| Method cache collisions | 343,114 |  |
| Method cache dunder hits | 34,238,291 |  |
| Method cache dunder misses | 67,976 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 8,607 | 568,987 | 60,572,748 |
| 1 | 779 | 267,767 | 39,259,056 |
| 2 | 80 | 37,164 | 88,311,003 |


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
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-11-16
