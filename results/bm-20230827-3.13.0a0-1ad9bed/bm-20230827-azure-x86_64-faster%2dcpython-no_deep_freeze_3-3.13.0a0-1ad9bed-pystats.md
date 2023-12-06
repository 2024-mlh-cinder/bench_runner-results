
# Pystats results

- fork: faster-cpython
- ref: no-deep-freeze-3
- commit hash: 1ad9bed
- commit date: 2023-08-27T23:38:58+01:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 27,938,136,279 | 18.8% | 18.8% |  |
| STORE_FAST | 9,809,665,771 | 6.6% | 25.4% |  |
| LOAD_CONST | 9,573,479,262 | 6.4% | 31.9% |  |
| POP_JUMP_IF_FALSE | 8,399,526,865 | 5.7% | 37.5% |  |
| LOAD_FAST_LOAD_FAST | 8,000,347,180 | 5.4% | 42.9% |  |
| RESUME | 4,956,693,347 | 3.3% | 46.3% |  |
| LOAD_GLOBAL_BUILTIN | 4,128,267,262 | 2.8% | 49.0% | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,724,577,562 | 2.5% | 51.6% | 5.2% |
| JUMP_BACKWARD | 3,205,856,594 | 2.2% | 53.7% |  |
| TO_BOOL_BOOL | 3,185,736,837 | 2.1% | 55.9% | 0.0% |
| RETURN_VALUE | 2,982,799,237 | 2.0% | 57.9% |  |
| LOAD_GLOBAL_MODULE | 2,869,043,322 | 1.9% | 59.8% | 0.0% |
| CALL_PY_EXACT_ARGS | 2,803,065,185 | 1.9% | 61.7% | 3.1% |
| POP_TOP | 2,339,182,773 | 1.6% | 63.3% |  |
| BINARY_OP_ADD_INT | 2,222,560,615 | 1.5% | 64.8% | 0.0% |
| CONTAINS_OP | 1,983,037,790 | 1.3% | 66.1% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,863,235,873 | 1.3% | 67.4% | 8.2% |
| COMPARE_OP_STR | 1,590,671,324 | 1.1% | 68.4% | 0.0% |
| STORE_FAST_STORE_FAST | 1,543,052,244 | 1.0% | 69.5% |  |
| COMPARE_OP_INT | 1,502,265,912 | 1.0% | 70.5% | 0.1% |
| NOP | 1,497,493,238 | 1.0% | 71.5% |  |
| POP_JUMP_IF_TRUE | 1,457,045,225 | 1.0% | 72.5% |  |
| LOAD_ATTR_SLOT | 1,345,000,032 | 0.9% | 73.4% | 4.3% |
| RETURN_CONST | 1,340,330,926 | 0.9% | 74.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,334,083,426 | 0.9% | 75.2% | 3.4% |
| BINARY_SUBSCR_STR_INT | 1,239,946,580 | 0.8% | 76.0% | 0.0% |
| FOR_ITER_LIST | 1,239,716,555 | 0.8% | 76.8% | 5.3% |
| INTERPRETER_EXIT | 1,210,141,500 | 0.8% | 77.7% |  |
| BINARY_SUBSCR | 1,111,323,418 | 0.7% | 78.4% |  |
| PUSH_NULL | 1,081,981,183 | 0.7% | 79.1% |  |
| STORE_ATTR_SLOT | 1,062,913,448 | 0.7% | 79.9% | 10.6% |
| COPY | 1,056,551,219 | 0.7% | 80.6% |  |
| LOAD_ATTR | 1,037,818,672 | 0.7% | 81.3% |  |
| CALL_NO_KW_BUILTIN_FAST | 933,475,268 | 0.6% | 81.9% | 0.0% |
| SWAP | 931,356,668 | 0.6% | 82.5% |  |
| CALL | 894,810,760 | 0.6% | 83.1% |  |
| BINARY_SUBSCR_LIST_INT | 878,290,842 | 0.6% | 83.7% | 0.4% |
| BINARY_OP | 840,951,848 | 0.6% | 84.3% |  |
| LOAD_DEREF | 840,380,328 | 0.6% | 84.8% |  |
| BINARY_OP_MULTIPLY_FLOAT | 827,760,657 | 0.6% | 85.4% | 0.8% |
| STORE_ATTR_INSTANCE_VALUE | 811,489,864 | 0.5% | 86.0% | 8.6% |
| CALL_NO_KW_ISINSTANCE | 810,266,116 | 0.5% | 86.5% |  |
| CALL_NO_KW_BUILTIN_O | 785,536,665 | 0.5% | 87.0% | 0.1% |
| YIELD_VALUE | 693,473,036 | 0.5% | 87.5% |  |
| BUILD_TUPLE | 692,958,074 | 0.5% | 88.0% |  |
| BINARY_SUBSCR_DICT | 622,357,230 | 0.4% | 88.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 605,562,429 | 0.4% | 88.8% |  |
| GET_ITER | 594,096,135 | 0.4% | 89.2% |  |
| BINARY_OP_SUBTRACT_INT | 499,710,119 | 0.3% | 89.5% | 0.1% |
| FOR_ITER_RANGE | 482,009,280 | 0.3% | 89.9% | 0.0% |
| IS_OP | 444,551,829 | 0.3% | 90.1% |  |
| UNPACK_SEQUENCE_TUPLE | 425,326,194 | 0.3% | 90.4% | 0.3% |
| FOR_ITER_TUPLE | 422,559,752 | 0.3% | 90.7% | 15.5% |
| POP_JUMP_IF_NOT_NONE | 419,866,127 | 0.3% | 91.0% |  |
| JUMP_FORWARD | 419,212,821 | 0.3% | 91.3% |  |
| BINARY_OP_ADD_FLOAT | 391,154,477 | 0.3% | 91.5% | 1.6% |
| TO_BOOL_NONE | 376,300,991 | 0.3% | 91.8% | 10.9% |
| LOAD_ATTR_WITH_HINT | 347,157,533 | 0.2% | 92.0% | 0.5% |
| CALL_NO_KW_LEN | 345,746,415 | 0.2% | 92.3% |  |
| CALL_NO_KW_METHOD_DESCRIPTOR_FAST | 340,443,813 | 0.2% | 92.5% | 2.0% |
| LOAD_ATTR_MODULE | 340,049,851 | 0.2% | 92.7% | 0.0% |
| CALL_NO_KW_TYPE_1 | 335,967,229 | 0.2% | 93.0% |  |
| STORE_SUBSCR | 316,199,310 | 0.2% | 93.2% |  |
| EXTENDED_ARG | 308,251,641 | 0.2% | 93.4% |  |
| SEND_GEN | 302,362,089 | 0.2% | 93.6% | 0.0% |
| STORE_SUBSCR_LIST_INT | 301,631,696 | 0.2% | 93.8% | 0.0% |
| BUILD_LIST | 301,119,997 | 0.2% | 94.0% |  |
| FOR_ITER | 293,141,338 | 0.2% | 94.2% |  |
| POP_JUMP_IF_NONE | 290,303,311 | 0.2% | 94.4% |  |
| BINARY_OP_SUBTRACT_FLOAT | 270,386,982 | 0.2% | 94.6% | 5.6% |
| BINARY_OP_MULTIPLY_INT | 266,391,167 | 0.2% | 94.7% | 3.2% |
| COPY_FREE_VARS | 249,381,066 | 0.2% | 94.9% |  |
| BINARY_SLICE | 248,170,481 | 0.2% | 95.1% |  |
| CALL_NO_KW_LIST_APPEND | 239,610,540 | 0.2% | 95.2% | 0.0% |
| RETURN_GENERATOR | 238,824,557 | 0.2% | 95.4% |  |
| CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS | 233,393,948 | 0.2% | 95.6% | 6.9% |
| TO_BOOL_INT | 228,420,433 | 0.2% | 95.7% | 0.4% |
| CALL_NO_KW_METHOD_DESCRIPTOR_O | 228,041,880 | 0.2% | 95.9% | 0.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 214,745,238 | 0.1% | 96.0% |  |
| TO_BOOL | 205,436,301 | 0.1% | 96.1% |  |
| STORE_SUBSCR_DICT | 198,998,380 | 0.1% | 96.3% |  |
| END_SEND | 194,307,848 | 0.1% | 96.4% |  |
| BINARY_SUBSCR_TUPLE_INT | 188,460,061 | 0.1% | 96.5% | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 178,900,451 | 0.1% | 96.7% | 21.3% |
| KW_NAMES | 173,247,328 | 0.1% | 96.8% |  |
| CALL_PY_WITH_DEFAULTS | 170,991,384 | 0.1% | 96.9% | 3.1% |
| BUILD_SLICE | 158,211,441 | 0.1% | 97.0% |  |
| CALL_INTRINSIC_1 | 154,033,796 | 0.1% | 97.1% |  |
| LIST_APPEND | 146,930,162 | 0.1% | 97.2% |  |
| BINARY_SUBSCR_GETITEM | 146,424,252 | 0.1% | 97.3% | 0.0% |
| COMPARE_OP | 145,552,138 | 0.1% | 97.4% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 143,437,214 | 0.1% | 97.5% | 35.5% |
| UNPACK_SEQUENCE_LIST | 140,234,020 | 0.1% | 97.6% | 0.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 138,653,206 | 0.1% | 97.7% | 19.1% |
| STORE_FAST_LOAD_FAST | 136,651,759 | 0.1% | 97.8% |  |
| DELETE_SUBSCR | 127,970,286 | 0.1% | 97.9% |  |
| CALL_BUILTIN_CLASS | 126,641,142 | 0.1% | 97.9% |  |
| UNARY_NEGATIVE | 121,275,060 | 0.1% | 98.0% |  |
| LOAD_ATTR_CLASS | 121,002,242 | 0.1% | 98.1% | 1.1% |
| STORE_SLICE | 117,671,346 | 0.1% | 98.2% |  |
| FORMAT_SIMPLE | 117,345,333 | 0.1% | 98.3% |  |
| LOAD_SUPER_ATTR_METHOD | 114,441,728 | 0.1% | 98.3% |  |
| SEND | 112,730,180 | 0.1% | 98.4% |  |
| TO_BOOL_LIST | 112,242,054 | 0.1% | 98.5% | 1.2% |
| COMPARE_OP_FLOAT | 111,063,262 | 0.1% | 98.6% | 0.0% |
| CONVERT_VALUE | 103,739,101 | 0.1% | 98.6% |  |
| GET_ANEXT | 100,136,760 | 0.1% | 98.7% |  |
| MAKE_FUNCTION | 94,838,923 | 0.1% | 98.8% |  |
| MAKE_CELL | 92,656,433 | 0.1% | 98.8% |  |
| FOR_ITER_GEN | 90,214,933 | 0.1% | 98.9% | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 87,703,249 | 0.1% | 99.0% | 2.0% |
| GET_AWAITABLE | 85,010,195 | 0.1% | 99.0% |  |
| SET_FUNCTION_ATTRIBUTE | 83,744,656 | 0.1% | 99.1% |  |
| CALL_FUNCTION_EX | 83,028,959 | 0.1% | 99.1% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 76,657,833 | 0.1% | 99.2% | 0.0% |
| CALL_NO_KW_ALLOC_AND_ENTER_INIT | 68,850,314 | 0.0% | 99.2% | 2.5% |
| BINARY_OP_ADD_UNICODE | 68,048,021 | 0.0% | 99.3% |  |
| TO_BOOL_STR | 67,241,004 | 0.0% | 99.3% | 3.0% |
| EXIT_INIT_CHECK | 67,138,854 | 0.0% | 99.4% |  |
| STORE_DEREF | 65,759,900 | 0.0% | 99.4% |  |
| BUILD_MAP | 63,937,136 | 0.0% | 99.4% |  |
| BUILD_STRING | 59,066,277 | 0.0% | 99.5% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 56,934,657 | 0.0% | 99.5% | 0.0% |
| END_FOR | 56,701,028 | 0.0% | 99.6% |  |
| LIST_EXTEND | 54,344,879 | 0.0% | 99.6% |  |
| STORE_ATTR | 53,544,331 | 0.0% | 99.6% |  |
| LOAD_FAST_AND_CLEAR | 52,337,004 | 0.0% | 99.7% |  |
| UNARY_NOT | 51,005,981 | 0.0% | 99.7% |  |
| STORE_ATTR_WITH_HINT | 50,964,916 | 0.0% | 99.7% | 0.1% |
| LOAD_ATTR_PROPERTY | 48,605,363 | 0.0% | 99.8% | 11.3% |
| MAP_ADD | 41,400,808 | 0.0% | 99.8% |  |
| CALL_NO_KW_STR_1 | 37,654,120 | 0.0% | 99.8% |  |
| CALL_NO_KW_TUPLE_1 | 22,405,310 | 0.0% | 99.8% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 22,351,922 | 0.0% | 99.9% | 0.0% |
| PUSH_EXC_INFO | 17,044,462 | 0.0% | 99.9% |  |
| POP_EXCEPT | 17,044,455 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 16,576,726 | 0.0% | 99.9% |  |
| DICT_MERGE | 16,232,096 | 0.0% | 99.9% |  |
| GET_YIELD_FROM_ITER | 15,170,581 | 0.0% | 99.9% |  |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 14,599,620 | 0.0% | 99.9% |  |
| INSTRUMENTED_RESUME | 14,583,120 | 0.0% | 99.9% |  |
| INSTRUMENTED_RETURN_VALUE | 14,576,040 | 0.0% | 99.9% |  |
| UNARY_INVERT | 11,488,605 | 0.0% | 99.9% |  |
| DELETE_ATTR | 8,524,233 | 0.0% | 100.0% |  |
| RERAISE | 8,497,715 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 7,377,865 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 7,309,835 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 6,152,700 | 0.0% | 100.0% |  |
| GET_AITER | 6,000,000 | 0.0% | 100.0% |  |
| END_ASYNC_FOR | 6,000,000 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 5,924,440 | 0.0% | 100.0% |  |
| BEFORE_WITH | 5,259,167 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 4,633,889 | 0.0% | 100.0% |  |
| SET_ADD | 3,234,120 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 2,897,642 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 2,298,840 | 0.0% | 100.0% |  |
| IMPORT_FROM | 1,989,906 | 0.0% | 100.0% |  |
| IMPORT_NAME | 1,952,286 | 0.0% | 100.0% |  |
| BUILD_SET | 1,918,509 | 0.0% | 100.0% |  |
| DELETE_FAST | 622,555 | 0.0% | 100.0% |  |
| UNPACK_EX | 567,000 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 216,639 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 138,122 | 0.0% | 100.0% |  |
| SET_UPDATE | 66,360 | 0.0% | 100.0% |  |
| DICT_UPDATE | 51,366 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 9,984 | 0.0% | 100.0% |  |
| INSTRUMENTED_FOR_ITER | 8,424 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 8,160 | 0.0% | 100.0% |  |
| INSTRUMENTED_JUMP_BACKWARD | 7,404 | 0.0% | 100.0% |  |
| INSTRUMENTED_RETURN_CONST | 5,400 | 0.0% | 100.0% |  |
| STORE_NAME | 4,800 | 0.0% | 100.0% |  |
| LOAD_LOCALS | 2,580 | 0.0% | 100.0% |  |
| LOAD_FROM_DICT_OR_DEREF | 2,580 | 0.0% | 100.0% |  |
| FORMAT_WITH_SPEC | 2,220 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 1,580 | 0.0% | 100.0% |  |
| LOAD_NAME | 1,560 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 1,320 | 0.0% | 100.0% |  |
| DELETE_DEREF | 1,200 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 804 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_NONE | 540 | 0.0% | 100.0% |  |
| INSTRUMENTED_JUMP_FORWARD | 300 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_NOT_NONE | 240 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_CONST | 4,901,891,942 | 3.3% | 3.3% |
| STORE_FAST LOAD_FAST | 4,675,472,008 | 3.1% | 6.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 4,512,330,117 | 3.0% | 9.5% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 3,157,711,988 | 2.1% | 11.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,662,407,364 | 1.8% | 13.4% |
| CALL_PY_EXACT_ARGS RESUME | 2,493,051,257 | 1.7% | 15.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 2,325,355,389 | 1.6% | 16.7% |
| RESUME LOAD_FAST | 2,091,786,319 | 1.4% | 18.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,870,254,127 | 1.3% | 19.3% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,771,636,662 | 1.2% | 20.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,578,061,106 | 1.1% | 21.6% |
| LOAD_CONST COMPARE_OP_STR | 1,563,963,488 | 1.1% | 22.6% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,550,238,384 | 1.0% | 23.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,332,289,898 | 0.9% | 24.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,265,611,668 | 0.9% | 25.4% |
| BINARY_OP_ADD_INT STORE_FAST | 1,258,763,349 | 0.8% | 26.3% |
| LOAD_FAST LOAD_ATTR_SLOT | 1,230,792,270 | 0.8% | 27.1% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_STR_INT | 1,202,362,860 | 0.8% | 27.9% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,183,259,420 | 0.8% | 28.7% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,101,535,018 | 0.7% | 29.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 1,053,314,073 | 0.7% | 30.2% |
| LOAD_CONST LOAD_FAST | 1,052,725,274 | 0.7% | 30.9% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 989,416,440 | 0.7% | 31.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 982,238,350 | 0.7% | 32.2% |
| NOP LOAD_FAST_LOAD_FAST | 959,961,947 | 0.6% | 32.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 946,903,937 | 0.6% | 33.5% |
| JUMP_BACKWARD FOR_ITER_LIST | 924,243,998 | 0.6% | 34.1% |
| STORE_FAST JUMP_BACKWARD | 918,432,662 | 0.6% | 34.7% |
| POP_TOP LOAD_FAST | 902,998,533 | 0.6% | 35.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 888,343,682 | 0.6% | 35.9% |
| RESUME LOAD_GLOBAL_BUILTIN | 846,848,172 | 0.6% | 36.5% |
| BINARY_SUBSCR_STR_INT STORE_FAST | 841,517,940 | 0.6% | 37.1% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 815,163,841 | 0.5% | 37.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 804,002,507 | 0.5% | 38.2% |
| CALL_NO_KW_ISINSTANCE TO_BOOL_BOOL | 797,126,448 | 0.5% | 38.7% |
| LOAD_FAST LOAD_FAST | 782,192,863 | 0.5% | 39.2% |
| LOAD_FAST RETURN_VALUE | 774,016,469 | 0.5% | 39.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 767,116,429 | 0.5% | 40.3% |
| LOAD_CONST LOAD_CONST | 744,701,157 | 0.5% | 40.8% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 725,093,192 | 0.5% | 41.3% |
| JUMP_BACKWARD NOP | 718,029,452 | 0.5% | 41.7% |
| LOAD_FAST TO_BOOL_BOOL | 715,259,932 | 0.5% | 42.2% |
| STORE_FAST STORE_FAST | 711,199,785 | 0.5% | 42.7% |
| LOAD_CONST COMPARE_OP_INT | 670,995,505 | 0.5% | 43.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 663,908,106 | 0.4% | 43.6% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 660,075,765 | 0.4% | 44.0% |
| POP_TOP JUMP_BACKWARD | 657,995,439 | 0.4% | 44.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 643,979,578 | 0.4% | 44.9% |
| LOAD_FAST PUSH_NULL | 630,232,820 | 0.4% | 45.3% |
| RETURN_VALUE STORE_FAST | 618,327,777 | 0.4% | 45.8% |
| POP_JUMP_IF_TRUE LOAD_FAST | 593,776,670 | 0.4% | 46.2% |
| FOR_ITER_LIST STORE_FAST | 587,193,710 | 0.4% | 46.6% |
| LOAD_FAST LOAD_ATTR | 579,025,704 | 0.4% | 46.9% |
| RETURN_CONST POP_TOP | 569,746,457 | 0.4% | 47.3% |
| LOAD_FAST CALL_NO_KW_BUILTIN_O | 560,433,001 | 0.4% | 47.7% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 539,153,020 | 0.4% | 48.1% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 536,643,206 | 0.4% | 48.4% |
| PUSH_NULL LOAD_FAST | 535,082,148 | 0.4% | 48.8% |
| LOAD_DEREF LOAD_FAST | 519,821,200 | 0.4% | 49.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 515,576,012 | 0.3% | 49.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 512,747,703 | 0.3% | 49.8% |
| LOAD_FAST CONTAINS_OP | 510,851,644 | 0.3% | 50.2% |
| RETURN_VALUE RETURN_VALUE | 509,526,265 | 0.3% | 50.5% |
| LOAD_FAST STORE_ATTR_SLOT | 504,062,519 | 0.3% | 50.9% |
| BINARY_SUBSCR LOAD_FAST | 490,867,512 | 0.3% | 51.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 480,416,662 | 0.3% | 51.5% |
| CALL_NO_KW_BUILTIN_FAST TO_BOOL_BOOL | 477,720,462 | 0.3% | 51.8% |
| RESUME POP_TOP | 472,274,727 | 0.3% | 52.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 466,234,319 | 0.3% | 52.5% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 465,286,189 | 0.3% | 52.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 459,719,083 | 0.3% | 53.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 452,264,728 | 0.3% | 53.4% |
| YIELD_VALUE INTERPRETER_EXIT | 451,459,526 | 0.3% | 53.7% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 450,390,069 | 0.3% | 54.0% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 444,403,969 | 0.3% | 54.3% |
| LOAD_GLOBAL_BUILTIN CALL_NO_KW_BUILTIN_FAST | 434,565,160 | 0.3% | 54.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 430,842,101 | 0.3% | 54.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 428,278,770 | 0.3% | 55.2% |
| JUMP_BACKWARD FOR_ITER_RANGE | 428,145,233 | 0.3% | 55.5% |
| STORE_FAST LOAD_GLOBAL_MODULE | 420,455,256 | 0.3% | 55.8% |
| LOAD_CONST STORE_FAST | 420,276,067 | 0.3% | 56.0% |
| BUILD_TUPLE RETURN_VALUE | 413,113,208 | 0.3% | 56.3% |
| RETURN_CONST INTERPRETER_EXIT | 410,755,139 | 0.3% | 56.6% |
| NOP LOAD_FAST | 402,350,863 | 0.3% | 56.9% |
| FOR_ITER_RANGE STORE_FAST | 396,422,275 | 0.3% | 57.1% |
| BINARY_SUBSCR_STR_INT LOAD_FAST | 388,169,340 | 0.3% | 57.4% |
| IS_OP POP_JUMP_IF_FALSE | 376,235,112 | 0.3% | 57.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 368,162,123 | 0.2% | 57.9% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 365,585,465 | 0.2% | 58.1% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 361,672,163 | 0.2% | 58.4% |
| LOAD_FAST BINARY_SUBSCR | 352,865,637 | 0.2% | 58.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 346,440,354 | 0.2% | 58.9% |
| STORE_FAST LOAD_DEREF | 345,215,136 | 0.2% | 59.1% |
| LOAD_GLOBAL_MODULE CALL_NO_KW_ISINSTANCE | 342,574,240 | 0.2% | 59.3% |
| CALL_NO_KW_BUILTIN_O POP_TOP | 341,716,976 | 0.2% | 59.5% |
| LOAD_CONST CALL_NO_KW_BUILTIN_FAST | 339,165,099 | 0.2% | 59.8% |
| RESUME NOP | 337,479,845 | 0.2% | 60.0% |
| RESUME LOAD_GLOBAL_MODULE | 336,430,121 | 0.2% | 60.2% |
| LOAD_FAST CALL_NO_KW_TYPE_1 | 332,265,689 | 0.2% | 60.5% |
| LOAD_GLOBAL_BUILTIN CALL_NO_KW_ISINSTANCE | 331,910,910 | 0.2% | 60.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,500 | 91.9% |
| LOAD_ATTR_WITH_HINT | 360 | 4.4% |
| CALL | 180 | 2.2% |
| LOAD_FAST | 120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 8,160 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,436,252 | 46.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,273,339 | 43.2% |
| LOAD_GLOBAL_MODULE | 210,148 | 4.0% |
| LOAD_ATTR_WITH_HINT | 132,220 | 2.5% |
| LOAD_FAST | 132,060 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,628,241 | 88.0% |
| STORE_FAST | 629,486 | 12.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,440 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 247,643,241 | 29.4% |
| LOAD_FAST | 170,130,502 | 20.2% |
| CALL_NO_KW_METHOD_DESCRIPTOR_O | 72,002,140 | 8.6% |
| LOAD_FAST_LOAD_FAST | 47,866,831 | 5.7% |
| LOAD_ATTR_INSTANCE_VALUE | 44,172,908 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 153,800,759 | 18.3% |
| LOAD_FAST | 138,604,669 | 16.5% |
| LOAD_FAST_LOAD_FAST | 106,872,520 | 12.7% |
| LOAD_CONST | 90,465,236 | 10.8% |
| RETURN_VALUE | 69,617,581 | 8.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 284,109,360 | 72.6% |
| LOAD_FAST | 65,398,697 | 16.7% |
| RETURN_VALUE | 17,287,200 | 4.4% |
| BINARY_OP_MULTIPLY_INT | 8,437,640 | 2.2% |
| BINARY_OP | 6,256,877 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 116,612,580 | 29.8% |
| STORE_FAST | 116,109,830 | 29.7% |
| LOAD_FAST | 59,770,747 | 15.3% |
| RETURN_VALUE | 31,351,200 | 8.0% |
| LOAD_FAST_LOAD_FAST | 29,369,460 | 7.5% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,771,636,662 | 79.7% |
| LOAD_FAST | 244,359,704 | 11.0% |
| LOAD_FAST_LOAD_FAST | 94,801,379 | 4.3% |
| END_SEND | 29,134,080 | 1.3% |
| BINARY_OP_MULTIPLY_INT | 23,999,760 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,258,763,349 | 56.6% |
| LOAD_CONST | 132,211,081 | 5.9% |
| STORE_SLICE | 103,909,260 | 4.7% |
| BINARY_OP_MULTIPLY_INT | 96,091,986 | 4.3% |
| SWAP | 88,108,140 | 4.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,035,480 | 47.1% |
| BINARY_SLICE | 15,579,000 | 22.9% |
| LOAD_CONST | 13,078,200 | 19.2% |
| BUILD_STRING | 2,011,200 | 3.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,233,481 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,173,540 | 23.8% |
| CALL_NO_KW_BUILTIN_O | 15,909,600 | 23.4% |
| BUILD_TUPLE | 15,457,800 | 22.7% |
| LOAD_CONST | 8,423,340 | 12.4% |
| RETURN_VALUE | 3,047,640 | 4.5% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,590,560 | 43.7% |
| BINARY_SLICE | 1,580,580 | 26.7% |
| RETURN_VALUE | 680,220 | 11.5% |
| BINARY_OP_ADD_UNICODE | 365,380 | 6.2% |
| LOAD_ATTR_SLOT | 358,800 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,312,520 | 89.7% |
| JUMP_BACKWARD | 511,840 | 8.6% |
| LOAD_CONST | 60,360 | 1.0% |
| LOAD_FAST_LOAD_FAST | 24,300 | 0.4% |
| LOAD_GLOBAL_MODULE | 10,180 | 0.2% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 539,153,020 | 65.1% |
| LOAD_ATTR_INSTANCE_VALUE | 118,763,280 | 14.3% |
| BINARY_SUBSCR | 67,701,000 | 8.2% |
| LOAD_FAST_LOAD_FAST | 59,229,880 | 7.2% |
| CALL_BUILTIN_CLASS | 12,782,880 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 284,109,360 | 34.3% |
| YIELD_VALUE | 210,931,680 | 25.5% |
| LOAD_FAST | 111,266,820 | 13.4% |
| BINARY_OP_SUBTRACT_FLOAT | 109,285,680 | 13.2% |
| STORE_FAST | 36,071,920 | 4.4% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 96,091,986 | 36.1% |
| LOAD_ATTR_INSTANCE_VALUE | 51,230,999 | 19.2% |
| LOAD_FAST_LOAD_FAST | 44,913,135 | 16.9% |
| LOAD_FAST | 38,771,060 | 14.6% |
| BINARY_OP | 27,332,910 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 62,212,221 | 23.4% |
| LOAD_CONST | 61,633,010 | 23.1% |
| LOAD_FAST | 47,053,380 | 17.7% |
| LOAD_FAST_LOAD_FAST | 28,244,880 | 10.6% |
| BINARY_OP_ADD_INT | 23,999,760 | 9.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 109,285,680 | 40.4% |
| LOAD_FAST | 69,610,868 | 25.7% |
| LOAD_FAST_LOAD_FAST | 36,420,281 | 13.5% |
| LOAD_ATTR_INSTANCE_VALUE | 28,678,255 | 10.6% |
| BINARY_SUBSCR | 12,729,580 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,609,293 | 35.7% |
| LOAD_FAST_LOAD_FAST | 73,322,880 | 27.1% |
| SWAP | 55,832,924 | 20.6% |
| LOAD_FAST | 28,365,896 | 10.5% |
| BINARY_OP_SUBTRACT_FLOAT | 10,737,420 | 4.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 365,585,465 | 73.2% |
| LOAD_FAST | 79,047,914 | 15.8% |
| LOAD_FAST_LOAD_FAST | 29,856,886 | 6.0% |
| LOAD_ATTR_INSTANCE_VALUE | 21,634,225 | 4.3% |
| CALL_NO_KW_LEN | 2,724,600 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,029,420 | 19.2% |
| CALL_PY_EXACT_ARGS | 94,404,101 | 18.9% |
| SWAP | 68,653,095 | 13.7% |
| RETURN_VALUE | 40,191,182 | 8.0% |
| BINARY_OP | 37,297,235 | 7.5% |


</details>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 137,122,787 | 55.3% |
| BINARY_OP_ADD_INT | 40,077,511 | 16.1% |
| LOAD_FAST_LOAD_FAST | 39,988,020 | 16.1% |
| LOAD_FAST | 24,931,463 | 10.0% |
| LOAD_ATTR_SLOT | 2,747,460 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 57,269,080 | 23.1% |
| GET_ITER | 33,199,240 | 13.4% |
| CALL_PY_EXACT_ARGS | 25,430,573 | 10.2% |
| BUILD_TUPLE | 24,334,501 | 9.8% |
| LOAD_DEREF | 18,985,680 | 7.7% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 352,865,637 | 31.8% |
| LOAD_FAST_LOAD_FAST | 234,131,541 | 21.1% |
| LOAD_CONST | 133,671,678 | 12.0% |
| COPY | 109,830,042 | 9.9% |
| BUILD_SLICE | 104,833,980 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 490,867,512 | 44.2% |
| STORE_FAST | 136,326,831 | 12.3% |
| LOAD_FAST_LOAD_FAST | 110,182,080 | 9.9% |
| BINARY_OP_MULTIPLY_FLOAT | 67,701,000 | 6.1% |
| BINARY_SUBSCR | 48,283,063 | 4.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 206,828,669 | 33.2% |
| LOAD_FAST | 205,179,960 | 33.0% |
| LOAD_FAST_LOAD_FAST | 135,582,648 | 21.8% |
| BINARY_SUBSCR | 41,253,856 | 6.6% |
| LOAD_ATTR_INSTANCE_VALUE | 11,361,760 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 237,016,296 | 38.1% |
| RETURN_VALUE | 104,202,814 | 16.7% |
| CONTAINS_OP | 77,768,700 | 12.5% |
| LOAD_FAST | 48,681,247 | 7.8% |
| LOAD_ATTR_METHOD_NO_DICT | 41,442,640 | 6.7% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 67,927,140 | 46.4% |
| LOAD_CONST | 41,616,840 | 28.4% |
| BUILD_TUPLE | 28,812,000 | 19.7% |
| LOAD_FAST | 3,529,472 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 3,355,060 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME | 145,515,992 | 99.4% |
| MAKE_CELL | 705,600 | 0.5% |
| COPY_FREE_VARS | 198,000 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 2,420 | 0.0% |
| CONTAINS_OP | 1,020 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 270,630,036 | 30.8% |
| LOAD_CONST | 180,973,221 | 20.6% |
| COPY | 157,633,500 | 17.9% |
| LOAD_FAST_LOAD_FAST | 154,830,690 | 17.6% |
| BINARY_OP | 48,349,920 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 233,353,855 | 26.6% |
| LOAD_CONST | 192,236,280 | 21.9% |
| LOAD_FAST | 140,365,374 | 16.0% |
| RETURN_VALUE | 90,407,524 | 10.3% |
| BINARY_OP | 38,804,700 | 4.4% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,202,362,860 | 97.0% |
| BINARY_OP_SUBTRACT_INT | 10,639,800 | 0.9% |
| LOAD_ATTR_SLOT | 10,356,180 | 0.8% |
| LOAD_CONST | 6,067,220 | 0.5% |
| LOAD_FAST | 5,008,740 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 841,517,940 | 67.9% |
| LOAD_FAST | 388,169,340 | 31.3% |
| LOAD_CONST | 5,749,800 | 0.5% |
| RETURN_VALUE | 3,711,600 | 0.3% |
| BINARY_OP_INPLACE_ADD_UNICODE | 216,660 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 148,324,535 | 78.7% |
| LOAD_FAST | 39,803,100 | 21.1% |
| LOAD_FAST_LOAD_FAST | 329,565 | 0.2% |
| BINARY_SUBSCR_LIST_INT | 2,521 | 0.0% |
| BINARY_SUBSCR | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 72,116,900 | 38.3% |
| LOAD_CONST | 24,654,420 | 13.1% |
| LOAD_FAST | 24,246,766 | 12.9% |
| YIELD_VALUE | 19,353,600 | 10.3% |
| STORE_FAST | 8,763,756 | 4.7% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,633,889 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,034,606 | 43.9% |
| LOAD_FAST_LOAD_FAST | 1,704,180 | 36.8% |
| STORE_FAST | 383,708 | 8.3% |
| RETURN_VALUE | 145,028 | 3.1% |
| CALL_NO_KW_LIST_APPEND | 132,780 | 2.9% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 116,263,063 | 38.6% |
| LOAD_ATTR_SLOT | 38,394,939 | 12.8% |
| SWAP | 32,360,773 | 10.7% |
| LOAD_FAST | 30,544,625 | 10.1% |
| RESUME | 18,138,526 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 129,110,018 | 42.9% |
| LOAD_FAST | 89,944,827 | 29.9% |
| SWAP | 32,396,659 | 10.8% |
| CALL | 9,652,840 | 3.2% |
| RETURN_VALUE | 9,311,710 | 3.1% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,290,239 | 16.1% |
| LOAD_FAST | 8,874,317 | 13.9% |
| RESUME | 6,822,511 | 10.7% |
| CALL_INTRINSIC_1 | 6,521,299 | 10.2% |
| SWAP | 6,077,760 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,050,394 | 37.6% |
| LOAD_FAST | 23,252,398 | 36.4% |
| SWAP | 6,077,760 | 9.5% |
| CALL_FUNCTION_EX | 3,407,702 | 5.3% |
| LOAD_CONST | 2,982,600 | 4.7% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,514,100 | 78.9% |
| LOAD_CONST | 142,320 | 7.4% |
| LOAD_GLOBAL_MODULE | 142,209 | 7.4% |
| LOAD_ATTR | 66,000 | 3.4% |
| LOAD_FAST | 52,920 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,514,100 | 78.9% |
| CONTAINS_OP | 141,849 | 7.4% |
| LOAD_CONST | 74,280 | 3.9% |
| BINARY_OP | 68,400 | 3.6% |
| STORE_FAST | 48,240 | 2.5% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 157,375,156 | 99.5% |
| LOAD_FAST | 780,845 | 0.5% |
| LOAD_ATTR_INSTANCE_VALUE | 54,000 | 0.0% |
| BINARY_OP_ADD_INT | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 104,833,980 | 66.3% |
| DELETE_SUBSCR | 53,377,461 | 33.7% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 52,318,730 | 88.6% |
| LOAD_CONST | 6,747,547 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_NO_KW_BUILTIN_O | 36,694,920 | 62.1% |
| CALL | 12,296,990 | 20.8% |
| STORE_FAST | 4,750,095 | 8.0% |
| BINARY_OP_ADD_UNICODE | 2,011,200 | 3.4% |
| CALL_NO_KW_LIST_APPEND | 1,398,120 | 2.4% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 206,460,024 | 29.8% |
| LOAD_CONST | 167,603,615 | 24.2% |
| LOAD_FAST_LOAD_FAST | 127,393,460 | 18.4% |
| LOAD_GLOBAL_BUILTIN | 40,166,358 | 5.8% |
| CALL | 38,800,574 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 413,113,208 | 59.6% |
| LOAD_CONST | 82,948,941 | 12.0% |
| CALL_NO_KW_ISINSTANCE | 40,155,024 | 5.8% |
| STORE_FAST | 30,270,203 | 4.4% |
| BINARY_SUBSCR_GETITEM | 28,812,000 | 4.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,669,828 | 27.0% |
| KW_NAMES | 149,674,849 | 16.7% |
| LOAD_FAST_LOAD_FAST | 91,173,443 | 10.2% |
| BINARY_SUBSCR_TUPLE_INT | 72,116,900 | 8.1% |
| PUSH_NULL | 50,869,362 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 305,203,355 | 34.1% |
| RESUME | 212,167,544 | 23.7% |
| RETURN_VALUE | 51,172,358 | 5.7% |
| POP_TOP | 47,335,722 | 5.3% |
| LOAD_GLOBAL_MODULE | 39,308,324 | 4.4% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,743,384 | 36.6% |
| LOAD_CONST | 23,537,066 | 17.0% |
| BINARY_OP_MULTIPLY_INT | 22,513,860 | 16.2% |
| PUSH_NULL | 11,687,094 | 8.4% |
| LOAD_ATTR_INSTANCE_VALUE | 6,373,611 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME | 108,993,438 | 78.6% |
| COPY_FREE_VARS | 26,909,934 | 19.4% |
| POP_TOP | 2,068,106 | 1.5% |
| CALL_PY_EXACT_ARGS | 460,534 | 0.3% |
| MAKE_CELL | 172,398 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,153,969 | 28.5% |
| CALL_NO_KW_LEN | 23,257,783 | 18.4% |
| LOAD_GLOBAL_BUILTIN | 10,773,125 | 8.5% |
| CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS | 9,078,944 | 7.2% |
| BINARY_OP_MULTIPLY_INT | 6,174,460 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 63,644,693 | 50.3% |
| STORE_FAST | 13,560,116 | 10.7% |
| BINARY_OP_MULTIPLY_FLOAT | 12,782,880 | 10.1% |
| LOAD_FAST | 10,268,958 | 8.1% |
| CALL_BUILTIN_CLASS | 4,239,483 | 3.3% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 33,017,880 | 43.1% |
| KW_NAMES | 22,520,679 | 29.4% |
| LOAD_FAST | 12,867,119 | 16.8% |
| LOAD_FAST_LOAD_FAST | 3,303,308 | 4.3% |
| CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS | 2,137,420 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 31,295,880 | 40.8% |
| STORE_FAST | 27,917,790 | 36.4% |
| POP_TOP | 9,120,057 | 11.9% |
| RETURN_VALUE | 5,704,150 | 7.4% |
| BINARY_OP_ADD_INT | 931,723 | 1.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 43,150,440 | 52.0% |
| LOAD_FAST | 16,445,755 | 19.8% |
| DICT_MERGE | 16,232,096 | 19.5% |
| BUILD_MAP | 3,407,702 | 4.1% |
| STORE_FAST | 2,240,100 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 47,275,946 | 56.9% |
| STORE_FAST | 8,427,014 | 10.1% |
| RESUME | 7,482,941 | 9.0% |
| RETURN_VALUE | 6,926,461 | 8.3% |
| MAKE_CELL | 4,744,306 | 5.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,136,760 | 59.7% |
| LIST_EXTEND | 53,504,301 | 36.2% |
| LOAD_ATTR_INSTANCE_VALUE | 6,000,000 | 4.1% |
| RERAISE | 42,148 | 0.0% |
| LIST_APPEND | 11,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 94,136,760 | 61.1% |
| CALL_FUNCTION_EX | 43,150,440 | 28.0% |
| BUILD_MAP | 6,521,299 | 4.2% |
| RERAISE | 6,381,215 | 4.1% |
| LOAD_CONST | 3,819,422 | 2.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 63,944,192 | 72.9% |
| LOAD_FAST | 10,476,418 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 7,512,516 | 8.6% |
| LOAD_ATTR_METHOD_NO_DICT | 4,177,285 | 4.8% |
| LOAD_FAST_LOAD_FAST | 1,042,279 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 70,523,723 | 80.4% |
| CALL_NO_KW_METHOD_DESCRIPTOR_O | 6,935,320 | 7.9% |
| LOAD_ATTR_METHOD_NO_DICT | 2,438,080 | 2.8% |
| RETURN_VALUE | 2,242,720 | 2.6% |
| BINARY_OP | 2,010,960 | 2.3% |


</details>

### CALL_NO_KW_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_NO_KW_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 20,210,840 | 29.4% |
| LOAD_GLOBAL_MODULE | 9,515,142 | 13.8% |
| BINARY_OP_MULTIPLY_FLOAT | 8,978,540 | 13.0% |
| RETURN_CONST | 7,864,740 | 11.4% |
| BINARY_OP_ADD_FLOAT | 5,101,500 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME | 65,416,499 | 95.0% |
| COPY_FREE_VARS | 1,722,235 | 2.5% |
| LOAD_FAST | 1,660,840 | 2.4% |
| CALL_NO_KW_ALLOC_AND_ENTER_INIT | 32,220 | 0.0% |
| STORE_FAST | 13,960 | 0.0% |


</details>

### CALL_NO_KW_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_NO_KW_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 434,565,160 | 46.6% |
| LOAD_CONST | 339,165,099 | 36.3% |
| LOAD_FAST_LOAD_FAST | 72,131,850 | 7.7% |
| CALL_NO_KW_BUILTIN_FAST | 37,468,660 | 4.0% |
| LOAD_FAST | 26,413,620 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 477,720,462 | 51.2% |
| STORE_FAST | 310,652,159 | 33.3% |
| POP_TOP | 47,792,714 | 5.1% |
| CALL_NO_KW_BUILTIN_FAST | 37,468,660 | 4.0% |
| RETURN_VALUE | 22,195,255 | 2.4% |


</details>

### CALL_NO_KW_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_NO_KW_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,433,001 | 71.3% |
| LOAD_CONST | 55,891,719 | 7.1% |
| RETURN_VALUE | 54,114,240 | 6.9% |
| BUILD_STRING | 36,694,920 | 4.7% |
| BINARY_OP_ADD_UNICODE | 15,909,600 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 341,716,976 | 43.5% |
| LOAD_CONST | 171,776,734 | 21.9% |
| STORE_FAST | 166,548,820 | 21.2% |
| RETURN_VALUE | 29,452,573 | 3.7% |
| STORE_SUBSCR_DICT | 13,999,260 | 1.8% |


</details>

### CALL_NO_KW_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_NO_KW_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 342,574,240 | 42.3% |
| LOAD_GLOBAL_BUILTIN | 331,910,910 | 41.0% |
| LOAD_FAST_LOAD_FAST | 62,969,143 | 7.8% |
| BUILD_TUPLE | 40,155,024 | 5.0% |
| LOAD_ATTR_MODULE | 22,114,621 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 797,126,448 | 98.4% |
| COPY | 6,062,046 | 0.7% |
| RETURN_VALUE | 2,415,162 | 0.3% |
| POP_TOP | 1,996,800 | 0.2% |
| STORE_FAST | 1,489,620 | 0.2% |


</details>

### CALL_NO_KW_LEN

<details>
<summary> Successors and predecessors for CALL_NO_KW_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 217,355,566 | 62.9% |
| LOAD_ATTR_INSTANCE_VALUE | 55,065,347 | 15.9% |
| BINARY_SUBSCR_LIST_INT | 29,548,500 | 8.5% |
| LOAD_DEREF | 20,449,960 | 5.9% |
| LOAD_ATTR_SLOT | 8,655,720 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 123,800,974 | 35.8% |
| LOAD_FAST | 55,702,243 | 16.1% |
| STORE_FAST | 43,147,830 | 12.5% |
| COMPARE_OP_INT | 32,614,237 | 9.4% |
| CALL_BUILTIN_CLASS | 23,257,783 | 6.7% |


</details>

### CALL_NO_KW_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_NO_KW_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 174,300,124 | 72.7% |
| BINARY_SUBSCR | 20,171,040 | 8.4% |
| BINARY_SLICE | 18,543,066 | 7.7% |
| BINARY_OP | 5,898,280 | 2.5% |
| RETURN_VALUE | 5,805,301 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 90,828,425 | 37.9% |
| LOAD_FAST | 72,490,258 | 30.3% |
| EXTENDED_ARG | 27,822,060 | 11.6% |
| RETURN_CONST | 20,554,860 | 8.6% |
| LOAD_CONST | 11,304,028 | 4.7% |


</details>

### CALL_NO_KW_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_NO_KW_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 178,403,945 | 52.4% |
| LOAD_FAST_LOAD_FAST | 56,756,039 | 16.7% |
| LOAD_ATTR_METHOD_NO_DICT | 50,384,068 | 14.8% |
| LOAD_CONST | 27,324,896 | 8.0% |
| LOAD_ATTR_SLOT | 8,567,760 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 249,387,412 | 73.3% |
| LIST_APPEND | 28,917,240 | 8.5% |
| RETURN_VALUE | 11,791,175 | 3.5% |
| LOAD_FAST | 10,856,760 | 3.2% |
| POP_TOP | 9,191,677 | 2.7% |


</details>

### CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 151,138,695 | 64.8% |
| LOAD_ATTR | 59,460,992 | 25.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 13,437,024 | 5.8% |
| LOAD_ATTR_METHOD_LAZY_DICT | 7,472,865 | 3.2% |
| LOAD_FAST | 1,577,820 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 73,502,750 | 31.5% |
| TO_BOOL_BOOL | 60,226,534 | 25.8% |
| GET_ITER | 33,735,960 | 14.5% |
| LOAD_GLOBAL_MODULE | 18,632,700 | 8.0% |
| LOAD_FAST | 12,556,153 | 5.4% |


</details>

### CALL_NO_KW_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_NO_KW_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 175,466,537 | 76.9% |
| CALL | 19,599,000 | 8.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 6,935,320 | 3.0% |
| CALL_NO_KW_BUILTIN_FAST | 6,013,961 | 2.6% |
| LOAD_GLOBAL_MODULE | 5,276,340 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 111,503,871 | 48.9% |
| BINARY_OP | 72,002,140 | 31.6% |
| RETURN_VALUE | 23,767,620 | 10.4% |
| STORE_FAST | 6,977,248 | 3.1% |
| LOAD_FAST | 5,876,700 | 2.6% |


</details>

### CALL_NO_KW_STR_1

<details>
<summary> Successors and predecessors for CALL_NO_KW_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,382,667 | 91.3% |
| RETURN_VALUE | 1,727,780 | 4.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,230,541 | 3.3% |
| LOAD_ATTR | 101,031 | 0.3% |
| CALL_NO_KW_TYPE_1 | 66,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_NO_KW_BUILTIN_O | 12,689,520 | 33.7% |
| CALL_PY_EXACT_ARGS | 10,848,480 | 28.8% |
| STORE_FAST | 5,604,308 | 14.9% |
| RETURN_VALUE | 3,244,981 | 8.6% |
| BUILD_LIST | 1,966,480 | 5.2% |


</details>

### CALL_NO_KW_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_NO_KW_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,919,646 | 66.6% |
| RETURN_GENERATOR | 5,526,160 | 24.7% |
| LOAD_ATTR_SLOT | 1,098,664 | 4.9% |
| CALL | 436,440 | 1.9% |
| RETURN_VALUE | 180,060 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,283,640 | 63.8% |
| BUILD_TUPLE | 2,891,824 | 12.9% |
| YIELD_VALUE | 2,419,200 | 10.8% |
| RETURN_VALUE | 1,003,686 | 4.5% |
| STORE_FAST | 642,060 | 2.9% |


</details>

### CALL_NO_KW_TYPE_1

<details>
<summary> Successors and predecessors for CALL_NO_KW_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 332,265,689 | 98.9% |
| LOAD_CONST | 3,615,840 | 1.1% |
| BINARY_SUBSCR_TUPLE_INT | 66,000 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 19,240 | 0.0% |
| LOAD_DEREF | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 287,412,316 | 85.5% |
| LOAD_GLOBAL_MODULE | 13,779,526 | 4.1% |
| LOAD_GLOBAL_BUILTIN | 12,241,637 | 3.6% |
| CALL_PY_EXACT_ARGS | 8,063,044 | 2.4% |
| LOAD_FAST | 5,614,860 | 1.7% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 946,903,937 | 33.8% |
| LOAD_FAST_LOAD_FAST | 660,075,765 | 23.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 430,842,101 | 15.4% |
| LOAD_GLOBAL_MODULE | 165,493,588 | 5.9% |
| LOAD_ATTR_METHOD_NO_DICT | 111,388,138 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME | 2,493,051,257 | 88.9% |
| RETURN_GENERATOR | 140,431,899 | 5.0% |
| COPY_FREE_VARS | 121,554,272 | 4.3% |
| MAKE_CELL | 31,460,236 | 1.1% |
| INSTRUMENTED_RESUME | 14,577,900 | 0.5% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 55,239,956 | 32.3% |
| LOAD_FAST | 42,004,576 | 24.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,275,052 | 7.2% |
| LOAD_ATTR_METHOD_NO_DICT | 12,068,800 | 7.1% |
| LOAD_ATTR | 11,113,742 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME | 164,797,551 | 96.4% |
| RETURN_GENERATOR | 3,374,437 | 2.0% |
| MAKE_CELL | 1,593,271 | 0.9% |
| COPY_FREE_VARS | 1,119,325 | 0.7% |
| CALL_PY_EXACT_ARGS | 87,580 | 0.1% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 15,417,737 | 93.0% |
| LOAD_GLOBAL_MODULE | 690,028 | 4.2% |
| BUILD_TUPLE | 359,940 | 2.2% |
| LOAD_ATTR_MODULE | 108,981 | 0.7% |
| LOAD_GLOBAL | 33 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,576,726 | 100.0% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 416 | 51.7% |
| CALL_INTRINSIC_1 | 240 | 29.9% |
| JUMP_BACKWARD | 148 | 18.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 46,511,834 | 32.0% |
| LOAD_FAST_LOAD_FAST | 32,739,520 | 22.5% |
| LOAD_ATTR | 15,308,323 | 10.5% |
| LOAD_ATTR_SLOT | 13,756,839 | 9.5% |
| LOAD_FAST | 10,889,700 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 78,722,505 | 54.1% |
| POP_JUMP_IF_TRUE | 38,840,669 | 26.7% |
| COPY | 18,629,700 | 12.8% |
| RETURN_VALUE | 7,090,109 | 4.9% |
| EXTENDED_ARG | 1,918,439 | 1.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 66,489,543 | 59.9% |
| BINARY_SUBSCR | 23,382,660 | 21.1% |
| LOAD_CONST | 6,328,628 | 5.7% |
| LOAD_FAST | 6,312,590 | 5.7% |
| LOAD_GLOBAL_MODULE | 3,631,808 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 48,489,723 | 43.7% |
| POP_JUMP_IF_TRUE | 32,446,020 | 29.2% |
| POP_JUMP_IF_FALSE | 30,126,759 | 27.1% |
| COMPARE_OP | 380 | 0.0% |
| EXTENDED_ARG | 360 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 670,995,505 | 44.7% |
| LOAD_ATTR_INSTANCE_VALUE | 172,385,497 | 11.5% |
| LOAD_FAST | 121,639,159 | 8.1% |
| LOAD_FAST_LOAD_FAST | 120,554,875 | 8.0% |
| COPY | 109,002,726 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,265,611,668 | 84.2% |
| POP_JUMP_IF_TRUE | 122,123,949 | 8.1% |
| RETURN_VALUE | 59,381,427 | 4.0% |
| EXTENDED_ARG | 22,449,455 | 1.5% |
| LOAD_FAST | 15,024,000 | 1.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,563,963,488 | 98.3% |
| LOAD_FAST | 8,980,177 | 0.6% |
| LOAD_GLOBAL_MODULE | 5,070,941 | 0.3% |
| RETURN_VALUE | 4,023,960 | 0.3% |
| BINARY_SUBSCR_TUPLE_INT | 2,470,800 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,550,238,384 | 97.5% |
| POP_JUMP_IF_TRUE | 27,393,420 | 1.7% |
| COPY | 6,090,303 | 0.4% |
| RETURN_VALUE | 4,403,317 | 0.3% |
| EXTENDED_ARG | 1,172,820 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 989,416,440 | 49.9% |
| LOAD_FAST | 510,851,644 | 25.8% |
| LOAD_GLOBAL_MODULE | 301,873,950 | 15.2% |
| BINARY_SUBSCR_DICT | 77,768,700 | 3.9% |
| LOAD_ATTR_INSTANCE_VALUE | 44,388,769 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,870,254,127 | 94.3% |
| POP_JUMP_IF_TRUE | 60,455,784 | 3.0% |
| RETURN_VALUE | 25,865,640 | 1.3% |
| COPY | 21,273,121 | 1.1% |
| EXTENDED_ARG | 3,501,720 | 0.2% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,393,222 | 83.3% |
| LOAD_ATTR | 11,580,661 | 11.2% |
| CALL_NO_KW_METHOD_DESCRIPTOR_O | 2,010,960 | 1.9% |
| RETURN_VALUE | 1,416,480 | 1.4% |
| CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS | 1,385,580 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 103,739,101 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 268,862,560 | 25.4% |
| LOAD_FAST | 237,462,554 | 22.5% |
| LOAD_FAST_LOAD_FAST | 120,961,740 | 11.4% |
| SWAP | 112,622,822 | 10.7% |
| LOAD_CONST | 95,336,290 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 268,862,560 | 25.4% |
| TO_BOOL_BOOL | 215,368,995 | 20.4% |
| BINARY_SUBSCR_LIST_INT | 157,633,500 | 14.9% |
| BINARY_SUBSCR | 109,830,042 | 10.4% |
| COMPARE_OP_INT | 109,002,726 | 10.3% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 121,554,272 | 75.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 26,909,934 | 16.7% |
| CALL | 9,063,275 | 5.6% |
| CALL_NO_KW_ALLOC_AND_ENTER_INIT | 1,722,235 | 1.1% |
| CALL_PY_WITH_DEFAULTS | 1,119,325 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME | 175,755,144 | 70.5% |
| RETURN_GENERATOR | 73,606,062 | 29.5% |
| MAKE_CELL | 19,860 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,523,993 | 100.0% |
| LOAD_GLOBAL_MODULE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,654,662 | 78.1% |
| NOP | 1,715,426 | 20.1% |
| RETURN_CONST | 151,265 | 1.8% |
| PUSH_EXC_INFO | 1,800 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,080 | 0.0% |


</details>

### DELETE_DEREF

<details>
<summary> Successors and predecessors for DELETE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR | 1,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_FAST | 1,200 | 100.0% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 223,768 | 35.9% |
| CALL | 155,023 | 24.9% |
| POP_TOP | 77,699 | 12.5% |
| NOP | 55,054 | 8.8% |
| STORE_ATTR_INSTANCE_VALUE | 54,937 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 212,623 | 34.2% |
| RERAISE | 151,228 | 24.3% |
| RETURN_CONST | 109,928 | 17.7% |
| JUMP_FORWARD | 66,240 | 10.6% |
| LOAD_FAST | 57,387 | 9.2% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 73,193,448 | 57.2% |
| BUILD_SLICE | 53,377,461 | 41.7% |
| LOAD_FAST | 1,015,912 | 0.8% |
| LOAD_CONST | 286,740 | 0.2% |
| LOAD_ATTR_SLOT | 66,060 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 107,533,337 | 84.1% |
| LOAD_CONST | 18,169,152 | 14.2% |
| JUMP_BACKWARD | 1,105,140 | 0.9% |
| RETURN_CONST | 540,801 | 0.4% |
| LOAD_FAST_LOAD_FAST | 274,636 | 0.2% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,444,698 | 95.1% |
| RETURN_VALUE | 376,080 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 218,709 | 1.3% |
| LOAD_DEREF | 112,615 | 0.7% |
| LOAD_GLOBAL_MODULE | 36,846 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 16,232,096 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 36,846 | 71.7% |
| LOAD_FAST | 13,140 | 25.6% |
| BUILD_MAP | 540 | 1.1% |
| RETURN_VALUE | 480 | 0.9% |
| MAP_ADD | 180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,386 | 72.8% |
| DICT_MERGE | 13,140 | 25.6% |
| STORE_FAST | 540 | 1.1% |
| LOAD_DEREF | 120 | 0.2% |
| LOAD_CONST | 60 | 0.1% |


</details>

### END_ASYNC_FOR

<details>
<summary> Successors and predecessors for END_ASYNC_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 6,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,999,940 | 100.0% |
| RETURN_CONST | 60 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 56,701,028 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 36,792,300 | 64.9% |
| LOAD_FAST | 19,102,080 | 33.7% |
| RETURN_CONST | 789,602 | 1.4% |
| LOAD_CONST | 5,940 | 0.0% |
| NOP | 4,980 | 0.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 100,454,840 | 51.7% |
| RETURN_VALUE | 69,221,117 | 35.6% |
| RETURN_CONST | 24,631,623 | 12.7% |
| JUMP_BACKWARD | 148 | 0.0% |
| SEND_GEN | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 95,092,349 | 48.9% |
| POP_TOP | 36,245,941 | 18.7% |
| LOAD_GLOBAL_MODULE | 29,134,080 | 15.0% |
| BINARY_OP_ADD_INT | 29,134,080 | 15.0% |
| LOAD_FAST | 3,215,940 | 1.7% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 67,138,854 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 67,138,854 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 88,770,272 | 28.8% |
| LOAD_FAST | 42,654,620 | 13.8% |
| JUMP_BACKWARD | 40,665,601 | 13.2% |
| CALL_NO_KW_LIST_APPEND | 27,822,060 | 9.0% |
| COMPARE_OP_INT | 22,449,455 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 138,159,282 | 44.8% |
| JUMP_BACKWARD | 54,300,380 | 17.6% |
| FOR_ITER_LIST | 38,691,700 | 12.6% |
| POP_JUMP_IF_NONE | 36,519,160 | 11.8% |
| FOR_ITER | 16,516,642 | 5.4% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 103,739,101 | 88.4% |
| LOAD_FAST | 9,752,297 | 8.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,423,980 | 1.2% |
| RETURN_VALUE | 1,042,740 | 0.9% |
| LOAD_ATTR_SLOT | 860,640 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 59,138,077 | 50.4% |
| BUILD_STRING | 52,318,730 | 44.6% |
| LOAD_FAST | 5,879,706 | 5.0% |
| LOAD_GLOBAL_MODULE | 8,820 | 0.0% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 86.5% |
| LOAD_CONST | 300 | 13.5% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 212,752,962 | 72.6% |
| GET_ITER | 53,883,342 | 18.4% |
| EXTENDED_ARG | 16,516,642 | 5.6% |
| SWAP | 6,717,707 | 2.3% |
| LOAD_FAST | 3,174,006 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 151,762,819 | 51.8% |
| STORE_FAST | 76,698,401 | 26.2% |
| LOAD_FAST | 27,182,994 | 9.3% |
| RETURN_CONST | 15,909,850 | 5.4% |
| SWAP | 6,179,340 | 2.1% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 56,713,320 | 62.9% |
| JUMP_BACKWARD | 33,136,685 | 36.7% |
| EXTENDED_ARG | 321,360 | 0.4% |
| LOAD_FAST | 42,240 | 0.0% |
| SWAP | 1,306 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 56,764,926 | 62.9% |
| RESUME | 33,449,467 | 37.1% |
| RETURN_CONST | 300 | 0.0% |
| STORE_FAST | 240 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 924,243,998 | 74.6% |
| GET_ITER | 190,464,142 | 15.4% |
| LOAD_FAST | 59,098,400 | 4.8% |
| EXTENDED_ARG | 38,691,700 | 3.1% |
| SWAP | 25,975,440 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 587,193,710 | 47.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 314,628,090 | 25.4% |
| RETURN_CONST | 103,914,145 | 8.4% |
| STORE_FAST_LOAD_FAST | 80,532,600 | 6.5% |
| LOAD_FAST | 59,478,218 | 4.8% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 428,145,233 | 88.8% |
| GET_ITER | 27,240,827 | 5.7% |
| LOAD_FAST | 21,531,300 | 4.5% |
| SWAP | 4,261,440 | 0.9% |
| EXTENDED_ARG | 829,380 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 396,422,275 | 82.2% |
| STORE_FAST_LOAD_FAST | 35,717,280 | 7.4% |
| RETURN_CONST | 24,277,626 | 5.0% |
| JUMP_BACKWARD | 9,675,480 | 2.0% |
| LOAD_FAST | 5,454,453 | 1.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 292,027,150 | 69.1% |
| GET_ITER | 124,936,222 | 29.6% |
| SWAP | 2,996,680 | 0.7% |
| LOAD_FAST | 1,261,462 | 0.3% |
| FOR_ITER_LIST | 1,236,366 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 288,884,263 | 68.4% |
| LOAD_FAST | 61,891,157 | 14.6% |
| LOAD_FAST_LOAD_FAST | 43,821,240 | 10.4% |
| RETURN_CONST | 12,361,567 | 2.9% |
| STORE_FAST_LOAD_FAST | 6,874,080 | 1.6% |


</details>

### GET_AITER

<details>
<summary> Successors and predecessors for GET_AITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,999,940 | 100.0% |
| RETURN_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ANEXT | 6,000,000 | 100.0% |


</details>

### GET_ANEXT

<details>
<summary> Successors and predecessors for GET_ANEXT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 94,136,760 | 94.0% |
| GET_AITER | 6,000,000 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100,136,760 | 100.0% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 78,585,287 | 92.4% |
| LOAD_FAST | 3,323,640 | 3.9% |
| RETURN_VALUE | 2,594,509 | 3.1% |
| LOAD_ATTR_INSTANCE_VALUE | 489,659 | 0.6% |
| BEFORE_ASYNC_WITH | 8,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 85,010,195 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 213,868,118 | 36.0% |
| LOAD_ATTR_INSTANCE_VALUE | 64,977,464 | 10.9% |
| CALL_BUILTIN_CLASS | 63,644,693 | 10.7% |
| RETURN_VALUE | 50,004,072 | 8.4% |
| LOAD_ATTR_SLOT | 38,735,966 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 190,464,142 | 32.1% |
| FOR_ITER_TUPLE | 124,936,222 | 21.0% |
| CALL_PY_EXACT_ARGS | 85,107,088 | 14.3% |
| FOR_ITER_GEN | 56,713,320 | 9.5% |
| FOR_ITER | 53,883,342 | 9.1% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 12,000,420 | 79.1% |
| RETURN_GENERATOR | 3,161,761 | 20.8% |
| LOAD_FAST | 7,080 | 0.0% |
| LOAD_ATTR_SLOT | 1,320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 15,170,581 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 1,538,766 | 77.3% |
| STORE_FAST | 451,140 | 22.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,989,786 | 100.0% |
| PUSH_EXC_INFO | 120 | 0.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,952,286 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 1,538,766 | 78.8% |
| STORE_FAST | 412,920 | 21.2% |
| STORE_NAME | 360 | 0.0% |
| STORE_DEREF | 240 | 0.0% |


</details>

### INSTRUMENTED_FOR_ITER

<details>
<summary> Successors and predecessors for INSTRUMENTED_FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_JUMP_BACKWARD | 4,344 | 51.6% |
| GET_ITER | 4,020 | 47.7% |
| SWAP | 60 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,404 | 52.3% |
| NOP | 3,060 | 36.3% |
| INSTRUMENTED_RETURN_CONST | 240 | 2.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 240 | 2.8% |
| LOAD_CONST | 240 | 2.8% |


</details>

### INSTRUMENTED_JUMP_BACKWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,060 | 41.3% |
| BINARY_OP_INPLACE_ADD_UNICODE | 3,060 | 41.3% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 864 | 11.7% |
| LIST_APPEND | 300 | 4.1% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 60 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_FOR_ITER | 4,344 | 58.7% |
| LOAD_FAST | 3,060 | 41.3% |


</details>

### INSTRUMENTED_JUMP_FORWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 240 | 80.0% |
| STORE_FAST | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 80.0% |
| LOAD_GLOBAL | 60 | 20.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 14,567,100 | 99.8% |
| TO_BOOL_BOOL | 13,920 | 0.1% |
| COMPARE_OP_STR | 7,020 | 0.0% |
| TO_BOOL_STR | 6,600 | 0.0% |
| EXTENDED_ARG | 3,300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,297,260 | 50.0% |
| LOAD_GLOBAL | 7,287,600 | 49.9% |
| LOAD_FAST_LOAD_FAST | 9,420 | 0.1% |
| INSTRUMENTED_RETURN_CONST | 4,740 | 0.0% |
| LOAD_CONST | 240 | 0.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 100.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,304 | 53.1% |
| TO_BOOL | 3,060 | 30.6% |
| TO_BOOL_STR | 960 | 9.6% |
| TO_BOOL_NONE | 300 | 3.0% |
| COMPARE_OP_STR | 240 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,260 | 42.7% |
| LOAD_GLOBAL | 4,020 | 40.3% |
| INSTRUMENTED_JUMP_BACKWARD | 864 | 8.7% |
| INSTRUMENTED_RETURN_VALUE | 480 | 4.8% |
| LOAD_FAST_LOAD_FAST | 180 | 1.8% |


</details>

### INSTRUMENTED_RESUME

<details>
<summary> Successors and predecessors for INSTRUMENTED_RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 14,577,900 | 100.0% |
| CALL | 3,300 | 0.0% |
| RESUME | 1,020 | 0.0% |
| INSTRUMENTED_RESUME | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,569,320 | 99.9% |
| LOAD_GLOBAL | 12,000 | 0.1% |
| RESUME | 960 | 0.0% |
| INSTRUMENTED_RESUME | 660 | 0.0% |
| LOAD_CONST | 180 | 0.0% |


</details>

### INSTRUMENTED_RETURN_CONST

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 4,740 | 87.8% |
| POP_TOP | 300 | 5.6% |
| INSTRUMENTED_FOR_ITER | 240 | 4.4% |
| STORE_GLOBAL | 60 | 1.1% |
| CALL_NO_KW_LIST_APPEND | 60 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,800 | 88.9% |
| TO_BOOL_BOOL | 400 | 7.4% |
| POP_TOP | 180 | 3.3% |
| TO_BOOL | 20 | 0.4% |


</details>

### INSTRUMENTED_RETURN_VALUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,288,320 | 50.0% |
| BINARY_OP_ADD_INT | 7,283,520 | 50.0% |
| INSTRUMENTED_RETURN_VALUE | 960 | 0.0% |
| CALL | 960 | 0.0% |
| BINARY_SLICE | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,283,520 | 50.0% |
| BINARY_OP_ADD_INT | 7,283,520 | 50.0% |
| STORE_FAST | 5,340 | 0.0% |
| TO_BOOL_BOOL | 1,200 | 0.0% |
| INSTRUMENTED_RETURN_VALUE | 960 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 451,459,526 | 37.3% |
| RETURN_CONST | 410,755,139 | 33.9% |
| RETURN_VALUE | 329,750,369 | 27.2% |
| RETURN_GENERATOR | 18,176,226 | 1.5% |
| INSTRUMENTED_RETURN_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 216,239,456 | 48.6% |
| LOAD_FAST_LOAD_FAST | 111,731,448 | 25.1% |
| LOAD_GLOBAL_MODULE | 81,765,789 | 18.4% |
| LOAD_GLOBAL_BUILTIN | 15,924,417 | 3.6% |
| LOAD_CONST | 8,674,841 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 376,235,112 | 84.6% |
| POP_JUMP_IF_TRUE | 39,064,318 | 8.8% |
| EXTENDED_ARG | 18,199,680 | 4.1% |
| RETURN_VALUE | 3,377,313 | 0.8% |
| COPY | 3,175,483 | 0.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 918,432,662 | 28.6% |
| POP_TOP | 657,995,439 | 20.5% |
| POP_JUMP_IF_TRUE | 465,286,189 | 14.5% |
| POP_JUMP_IF_FALSE | 444,403,969 | 13.9% |
| LIST_APPEND | 146,822,342 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 924,243,998 | 28.8% |
| NOP | 718,029,452 | 22.4% |
| FOR_ITER_RANGE | 428,145,233 | 13.4% |
| LOAD_FAST | 308,058,756 | 9.6% |
| FOR_ITER_TUPLE | 292,027,150 | 9.1% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME | 214,745,238 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 208,499,841 | 97.1% |
| SEND | 6,245,397 | 2.9% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 171,888,381 | 41.0% |
| POP_JUMP_IF_FALSE | 100,900,412 | 24.1% |
| POP_TOP | 56,126,789 | 13.4% |
| LOAD_ATTR_SLOT | 22,225,800 | 5.3% |
| EXTENDED_ARG | 14,628,754 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 166,303,193 | 39.7% |
| LOAD_FAST_LOAD_FAST | 82,377,765 | 19.7% |
| LOAD_CONST | 37,404,740 | 8.9% |
| LOAD_GLOBAL_MODULE | 28,029,002 | 6.7% |
| LOAD_GLOBAL_BUILTIN | 25,952,874 | 6.2% |


</details>

### KW_NAMES

<details>
<summary> Successors and predecessors for KW_NAMES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,509,400 | 24.0% |
| LOAD_CONST | 38,433,911 | 22.2% |
| LOAD_FAST_LOAD_FAST | 35,229,245 | 20.3% |
| LOAD_GLOBAL_MODULE | 18,005,398 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,379,394 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 149,674,849 | 86.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 22,520,679 | 13.0% |
| CALL_BUILTIN_CLASS | 1,051,800 | 0.6% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_NO_KW_METHOD_DESCRIPTOR_FAST | 28,917,240 | 19.7% |
| BUILD_TUPLE | 26,458,320 | 18.0% |
| BINARY_OP | 20,606,280 | 14.0% |
| LOAD_FAST | 18,295,865 | 12.5% |
| RETURN_VALUE | 15,158,686 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 146,822,342 | 99.9% |
| LOAD_FAST | 96,000 | 0.1% |
| CALL_INTRINSIC_1 | 11,520 | 0.0% |
| INSTRUMENTED_JUMP_BACKWARD | 300 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 38,196,459 | 70.3% |
| LOAD_FAST | 15,445,288 | 28.4% |
| LOAD_CONST | 366,720 | 0.7% |
| RETURN_VALUE | 216,343 | 0.4% |
| LOAD_DEREF | 77,529 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 53,504,301 | 98.5% |
| STORE_FAST | 436,435 | 0.8% |
| LOAD_FAST | 227,683 | 0.4% |
| UNPACK_SEQUENCE_LIST | 172,560 | 0.3% |
| BUILD_TUPLE | 2,940 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 579,025,704 | 55.8% |
| LOAD_GLOBAL_BUILTIN | 221,917,316 | 21.4% |
| LOAD_GLOBAL_MODULE | 95,615,880 | 9.2% |
| LOAD_ATTR_SLOT | 81,099,147 | 7.8% |
| LOAD_FAST_LOAD_FAST | 23,057,989 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 216,239,456 | 20.8% |
| STORE_FAST | 169,633,007 | 16.3% |
| LOAD_FAST | 154,151,922 | 14.9% |
| PUSH_NULL | 69,675,061 | 6.7% |
| CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS | 59,460,992 | 5.7% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 116,574,284 | 96.3% |
| LOAD_GLOBAL_BUILTIN | 1,779,440 | 1.5% |
| LOAD_FAST | 1,408,580 | 1.2% |
| LOAD_FAST_LOAD_FAST | 591,660 | 0.5% |
| LOAD_ATTR_MODULE | 543,058 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 59,810,778 | 49.4% |
| CALL_PY_EXACT_ARGS | 21,858,680 | 18.1% |
| LOAD_FAST | 14,220,383 | 11.8% |
| PUSH_NULL | 8,285,400 | 6.8% |
| CALL_BUILTIN_CLASS | 2,841,920 | 2.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,157,711,988 | 84.8% |
| LOAD_FAST_LOAD_FAST | 330,978,551 | 8.9% |
| COPY | 77,247,692 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 50,253,027 | 1.3% |
| BINARY_SUBSCR_LIST_INT | 38,546,760 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,053,314,073 | 28.3% |
| TO_BOOL_BOOL | 428,278,770 | 11.5% |
| STORE_FAST | 276,444,973 | 7.4% |
| LOAD_ATTR_METHOD_NO_DICT | 190,052,834 | 5.1% |
| RETURN_VALUE | 177,027,272 | 4.8% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 40,723,025 | 71.5% |
| LOAD_FAST | 16,211,192 | 28.5% |
| LOAD_ATTR | 400 | 0.0% |
| LOAD_ATTR_WITH_HINT | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,574,994 | 69.5% |
| CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS | 7,472,865 | 13.1% |
| LOAD_GLOBAL_MODULE | 5,902,241 | 10.4% |
| LOAD_CONST | 2,491,800 | 4.4% |
| LOAD_FAST_LOAD_FAST | 1,228,800 | 2.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 767,116,429 | 57.5% |
| LOAD_ATTR_INSTANCE_VALUE | 190,052,834 | 14.2% |
| LOAD_CONST | 90,391,065 | 6.8% |
| LOAD_GLOBAL_MODULE | 52,877,635 | 4.0% |
| LOAD_ATTR_SLOT | 48,976,800 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 663,908,106 | 49.8% |
| LOAD_CONST | 155,815,405 | 11.7% |
| CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS | 151,138,695 | 11.3% |
| LOAD_FAST_LOAD_FAST | 111,690,268 | 8.4% |
| CALL_PY_EXACT_ARGS | 111,388,138 | 8.3% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,578,061,106 | 84.7% |
| LOAD_ATTR_INSTANCE_VALUE | 63,494,673 | 3.4% |
| LOAD_ATTR_SLOT | 45,626,411 | 2.4% |
| LOAD_ATTR | 45,436,246 | 2.4% |
| LOAD_ATTR_WITH_HINT | 37,579,059 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 804,002,507 | 43.2% |
| LOAD_FAST_LOAD_FAST | 480,416,662 | 25.8% |
| CALL_PY_EXACT_ARGS | 430,842,101 | 23.1% |
| LOAD_GLOBAL_MODULE | 55,444,783 | 3.0% |
| LOAD_CONST | 53,010,904 | 2.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 324,259,345 | 95.4% |
| LOAD_ATTR_MODULE | 11,618,945 | 3.4% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,324,680 | 0.4% |
| LOAD_ATTR_CLASS | 1,160,080 | 0.3% |
| LOAD_FAST_LOAD_FAST | 927,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 266,382,107 | 78.3% |
| CALL_NO_KW_ISINSTANCE | 22,114,621 | 6.5% |
| LOAD_ATTR_MODULE | 11,618,945 | 3.4% |
| LOAD_FAST | 10,382,218 | 3.1% |
| LOAD_GLOBAL_MODULE | 4,984,900 | 1.5% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,484,882 | 73.8% |
| LOAD_FAST_LOAD_FAST | 5,866,920 | 26.2% |
| LOAD_ATTR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 8,387,821 | 37.5% |
| CONTAINS_OP | 6,929,880 | 31.0% |
| CALL_PY_EXACT_ARGS | 3,269,240 | 14.6% |
| LOAD_ATTR_MODULE | 1,324,680 | 5.9% |
| STORE_FAST | 1,071,420 | 4.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 130,480,155 | 91.0% |
| LOAD_FAST_LOAD_FAST | 10,938,489 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,059,910 | 0.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 759,700 | 0.5% |
| STORE_FAST_LOAD_FAST | 181,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,647,403 | 21.4% |
| LOAD_FAST_LOAD_FAST | 27,613,920 | 19.3% |
| GET_ITER | 19,279,760 | 13.4% |
| LOAD_GLOBAL_BUILTIN | 15,384,960 | 10.7% |
| LOAD_ATTR_METHOD_NO_DICT | 10,309,640 | 7.2% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,595,773 | 83.5% |
| LOAD_ATTR_SLOT | 5,106,844 | 10.5% |
| RETURN_VALUE | 1,327,489 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,064,920 | 2.2% |
| LOAD_FAST_LOAD_FAST | 125,480 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME | 42,964,111 | 88.4% |
| TO_BOOL_NONE | 3,107,760 | 6.4% |
| RETURN_VALUE | 831,828 | 1.7% |
| LOAD_FAST | 560,620 | 1.2% |
| LOAD_ATTR_WITH_HINT | 402,480 | 0.8% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,230,792,270 | 91.5% |
| LOAD_ATTR_SLOT | 40,651,782 | 3.0% |
| COPY | 40,401,404 | 3.0% |
| LOAD_DEREF | 12,824,040 | 1.0% |
| LOAD_FAST_LOAD_FAST | 8,700,851 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 307,012,167 | 22.8% |
| TO_BOOL_NONE | 88,076,972 | 6.5% |
| LOAD_ATTR | 81,099,147 | 6.0% |
| TO_BOOL_BOOL | 68,845,934 | 5.1% |
| COMPARE_OP_FLOAT | 66,489,543 | 4.9% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 277,224,650 | 79.9% |
| LOAD_ATTR_INSTANCE_VALUE | 22,741,240 | 6.6% |
| LOAD_ATTR_WITH_HINT | 22,281,414 | 6.4% |
| COPY | 14,038,523 | 4.0% |
| LOAD_FAST_LOAD_FAST | 8,451,657 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 85,380,272 | 24.6% |
| STORE_FAST | 43,154,700 | 12.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 37,579,059 | 10.8% |
| COMPARE_OP_INT | 35,280,839 | 10.2% |
| LOAD_CONST | 29,373,000 | 8.5% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 1,200 | 90.9% |
| RESUME | 120 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,320 | 100.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,901,891,942 | 51.2% |
| LOAD_CONST | 744,701,157 | 7.8% |
| LOAD_FAST_LOAD_FAST | 450,390,069 | 4.7% |
| STORE_FAST | 292,606,340 | 3.1% |
| POP_JUMP_IF_FALSE | 274,848,994 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,771,636,662 | 18.5% |
| COMPARE_OP_STR | 1,563,963,488 | 16.3% |
| LOAD_FAST | 1,052,725,274 | 11.0% |
| LOAD_CONST | 744,701,157 | 7.8% |
| COMPARE_OP_INT | 670,995,505 | 7.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 345,215,136 | 41.1% |
| LOAD_GLOBAL_BUILTIN | 107,521,211 | 12.8% |
| POP_JUMP_IF_FALSE | 57,741,221 | 6.9% |
| RESUME | 33,046,681 | 3.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,295,880 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 519,821,200 | 61.9% |
| LOAD_CONST | 69,818,600 | 8.3% |
| PUSH_NULL | 38,304,765 | 4.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 31,865,564 | 3.8% |
| LOAD_DEREF | 24,556,739 | 2.9% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,675,472,008 | 16.7% |
| POP_JUMP_IF_FALSE | 4,512,330,117 | 16.2% |
| LOAD_GLOBAL_BUILTIN | 2,662,407,364 | 9.5% |
| RESUME | 2,091,786,319 | 7.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,053,314,073 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,901,891,942 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,157,711,988 | 11.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,578,061,106 | 5.6% |
| LOAD_ATTR_SLOT | 1,230,792,270 | 4.4% |
| LOAD_GLOBAL_BUILTIN | 1,101,535,018 | 3.9% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 39,952,633 | 76.3% |
| LOAD_FAST_AND_CLEAR | 12,384,371 | 23.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 39,944,473 | 76.3% |
| LOAD_FAST_AND_CLEAR | 12,384,371 | 23.7% |
| MAKE_CELL | 8,160 | 0.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,682,680 | 50.4% |
| POP_TOP | 2,058,372 | 28.2% |
| LOAD_GLOBAL_BUILTIN | 421,860 | 5.8% |
| LOAD_ATTR_METHOD_NO_DICT | 338,968 | 4.6% |
| STORE_FAST | 308,760 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,578,840 | 49.0% |
| POP_JUMP_IF_NOT_NONE | 1,511,040 | 20.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 5.9% |
| LOAD_FAST | 383,640 | 5.2% |
| CALL_NO_KW_METHOD_DESCRIPTOR_O | 334,768 | 4.6% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,332,289,898 | 16.7% |
| POP_JUMP_IF_FALSE | 1,183,259,420 | 14.8% |
| NOP | 959,961,947 | 12.0% |
| LOAD_FAST_LOAD_FAST | 512,747,703 | 6.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 480,416,662 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 1,202,362,860 | 15.0% |
| CONTAINS_OP | 989,416,440 | 12.4% |
| CALL_PY_EXACT_ARGS | 660,075,765 | 8.3% |
| LOAD_FAST | 643,979,578 | 8.0% |
| STORE_ATTR_SLOT | 515,576,012 | 6.4% |


</details>

### LOAD_FROM_DICT_OR_DEREF

<details>
<summary> Successors and predecessors for LOAD_FROM_DICT_OR_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_LOCALS | 2,580 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,200 | 46.5% |
| PUSH_NULL | 1,200 | 46.5% |
| LOAD_CONST | 180 | 7.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 7,287,600 | 98.8% |
| STORE_FAST | 20,217 | 0.3% |
| INSTRUMENTED_RESUME | 12,000 | 0.2% |
| RESUME | 8,383 | 0.1% |
| NOP | 4,592 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,298,656 | 98.9% |
| LOAD_GLOBAL_MODULE | 42,909 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 15,908 | 0.2% |
| LOAD_ATTR_MODULE | 14,100 | 0.2% |
| LOAD_FAST_LOAD_FAST | 3,611 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,101,535,018 | 26.7% |
| POP_JUMP_IF_FALSE | 982,238,350 | 23.8% |
| RESUME | 846,848,172 | 20.5% |
| STORE_FAST | 536,643,206 | 13.0% |
| POP_JUMP_IF_TRUE | 98,146,602 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,662,407,364 | 64.5% |
| CALL_NO_KW_BUILTIN_FAST | 434,565,160 | 10.5% |
| CALL_NO_KW_ISINSTANCE | 331,910,910 | 8.0% |
| LOAD_ATTR | 221,917,316 | 5.4% |
| LOAD_FAST_LOAD_FAST | 113,563,331 | 2.8% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 888,343,682 | 31.0% |
| STORE_FAST | 420,455,256 | 14.7% |
| RESUME | 336,430,121 | 11.7% |
| POP_JUMP_IF_FALSE | 273,135,877 | 9.5% |
| LOAD_FAST_LOAD_FAST | 113,386,400 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 459,719,083 | 16.0% |
| LOAD_FAST | 452,264,728 | 15.8% |
| CALL_NO_KW_ISINSTANCE | 342,574,240 | 11.9% |
| LOAD_ATTR_MODULE | 324,259,345 | 11.3% |
| CONTAINS_OP | 301,873,950 | 10.5% |


</details>

### LOAD_LOCALS

<details>
<summary> Successors and predecessors for LOAD_LOCALS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,380 | 53.5% |
| STORE_NAME | 1,200 | 46.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FROM_DICT_OR_DEREF | 2,580 | 100.0% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME | 1,320 | 84.6% |
| STORE_NAME | 240 | 15.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 1,320 | 84.6% |
| PUSH_NULL | 180 | 11.5% |
| UNPACK_SEQUENCE_TUPLE | 40 | 2.6% |
| UNPACK_SEQUENCE | 20 | 1.3% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,460 | 92.4% |
| LOAD_DEREF | 60 | 3.8% |
| EXTENDED_ARG | 60 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 1,460 | 92.4% |
| LOAD_SUPER_ATTR_ATTR | 120 | 7.6% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,298,440 | 100.0% |
| LOAD_SUPER_ATTR | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| EXTENDED_ARG | 120 | 0.0% |
| LOAD_DEREF | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,228,880 | 97.0% |
| LOAD_GLOBAL_MODULE | 65,520 | 2.9% |
| STORE_FAST | 4,320 | 0.2% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 114,431,188 | 100.0% |
| LOAD_DEREF | 9,080 | 0.0% |
| LOAD_SUPER_ATTR | 1,460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 62,752,533 | 54.8% |
| LOAD_FAST | 37,260,486 | 32.6% |
| CALL_PY_EXACT_ARGS | 6,426,681 | 5.6% |
| CALL_PY_WITH_DEFAULTS | 5,951,040 | 5.2% |
| CALL | 1,200,040 | 1.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 49,466,529 | 53.6% |
| CALL_PY_EXACT_ARGS | 31,460,236 | 34.1% |
| CALL_FUNCTION_EX | 4,744,306 | 5.1% |
| CALL | 4,144,873 | 4.5% |
| CALL_PY_WITH_DEFAULTS | 1,593,271 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 49,466,529 | 53.4% |
| RESUME | 42,526,103 | 45.9% |
| RETURN_GENERATOR | 655,641 | 0.7% |
| SWAP | 8,160 | 0.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 94,838,923 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 82,636,401 | 87.1% |
| LOAD_FAST | 9,062,460 | 9.6% |
| LOAD_GLOBAL_MODULE | 2,504,360 | 2.6% |
| KW_NAMES | 255,360 | 0.3% |
| CALL | 127,687 | 0.1% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 15,896,280 | 38.4% |
| RETURN_VALUE | 6,380,580 | 15.4% |
| LOAD_FAST | 6,188,714 | 14.9% |
| JUMP_FORWARD | 4,782,840 | 11.6% |
| STORE_FAST | 4,549,800 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,597,580 | 49.8% |
| JUMP_BACKWARD | 19,591,408 | 47.3% |
| CALL_FUNCTION_EX | 1,211,460 | 2.9% |
| DICT_UPDATE | 180 | 0.0% |
| BUILD_MAP | 120 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 718,029,452 | 47.9% |
| RESUME | 337,479,845 | 22.5% |
| STORE_FAST | 159,035,766 | 10.6% |
| POP_JUMP_IF_FALSE | 80,744,895 | 5.4% |
| NOP | 52,969,437 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 959,961,947 | 64.1% |
| LOAD_FAST | 402,350,863 | 26.9% |
| NOP | 52,969,437 | 3.5% |
| LOAD_GLOBAL_BUILTIN | 34,272,471 | 2.3% |
| LOAD_CONST | 22,889,143 | 1.5% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 9,939,267 | 58.3% |
| STORE_SUBSCR_DICT | 3,086,108 | 18.1% |
| SWAP | 1,973,400 | 11.6% |
| COPY | 1,285,290 | 7.5% |
| STORE_FAST | 547,609 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 9,500,854 | 55.7% |
| RETURN_VALUE | 1,913,709 | 11.2% |
| JUMP_FORWARD | 1,715,820 | 10.1% |
| POP_TOP | 1,384,862 | 8.1% |
| RERAISE | 1,285,290 | 7.5% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,325,355,389 | 27.7% |
| CONTAINS_OP | 1,870,254,127 | 22.3% |
| COMPARE_OP_STR | 1,550,238,384 | 18.5% |
| COMPARE_OP_INT | 1,265,611,668 | 15.1% |
| IS_OP | 376,235,112 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,512,330,117 | 53.7% |
| LOAD_FAST_LOAD_FAST | 1,183,259,420 | 14.1% |
| LOAD_GLOBAL_BUILTIN | 982,238,350 | 11.7% |
| JUMP_BACKWARD | 444,403,969 | 5.3% |
| LOAD_CONST | 274,848,994 | 3.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 195,056,622 | 67.2% |
| EXTENDED_ARG | 36,519,160 | 12.6% |
| LOAD_ATTR_SLOT | 25,425,420 | 8.8% |
| LOAD_DEREF | 13,781,809 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 11,404,825 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 184,158,546 | 63.4% |
| LOAD_DEREF | 28,712,760 | 9.9% |
| JUMP_BACKWARD | 20,403,964 | 7.0% |
| RETURN_CONST | 15,883,930 | 5.5% |
| LOAD_GLOBAL_BUILTIN | 12,782,700 | 4.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 346,440,354 | 82.5% |
| LOAD_ATTR_INSTANCE_VALUE | 27,684,181 | 6.6% |
| LOAD_ATTR | 14,185,608 | 3.4% |
| STORE_FAST_LOAD_FAST | 8,887,140 | 2.1% |
| EXTENDED_ARG | 7,255,900 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 167,100,698 | 39.8% |
| LOAD_GLOBAL_BUILTIN | 96,627,572 | 23.0% |
| LOAD_FAST_LOAD_FAST | 58,936,227 | 14.0% |
| LOAD_GLOBAL_MODULE | 36,033,352 | 8.6% |
| NOP | 18,019,901 | 4.3% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 725,093,192 | 49.8% |
| TO_BOOL | 132,444,873 | 9.1% |
| COMPARE_OP_INT | 122,123,949 | 8.4% |
| TO_BOOL_ALWAYS_TRUE | 82,915,551 | 5.7% |
| TO_BOOL_NONE | 77,693,586 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 593,776,670 | 40.8% |
| JUMP_BACKWARD | 465,286,189 | 31.9% |
| LOAD_GLOBAL_BUILTIN | 98,146,602 | 6.7% |
| LOAD_CONST | 68,424,821 | 4.7% |
| POP_TOP | 66,409,314 | 4.6% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 569,746,457 | 25.3% |
| RESUME | 472,274,727 | 21.0% |
| CALL_NO_KW_BUILTIN_O | 341,716,976 | 15.2% |
| POP_JUMP_IF_FALSE | 161,992,903 | 7.2% |
| RETURN_VALUE | 121,253,521 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 902,998,533 | 38.6% |
| JUMP_BACKWARD | 657,995,439 | 28.1% |
| RESUME | 238,824,557 | 10.2% |
| RETURN_CONST | 184,087,638 | 7.9% |
| LOAD_FAST_LOAD_FAST | 99,544,092 | 4.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 5,217,141 | 30.7% |
| LOAD_ATTR | 3,246,420 | 19.1% |
| RAISE_VARARGS | 2,298,602 | 13.5% |
| CALL_NO_KW_BUILTIN_FAST | 1,785,266 | 10.5% |
| RERAISE | 1,115,614 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 15,415,363 | 90.4% |
| LOAD_GLOBAL_MODULE | 1,103,107 | 6.5% |
| LOAD_FAST | 387,180 | 2.3% |
| WITH_EXCEPT_START | 138,122 | 0.8% |
| LOAD_GLOBAL | 630 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 630,232,820 | 58.2% |
| LOAD_ATTR_MODULE | 266,382,107 | 24.6% |
| LOAD_ATTR | 69,675,061 | 6.4% |
| LOAD_FAST_LOAD_FAST | 47,492,640 | 4.4% |
| LOAD_DEREF | 38,304,765 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 535,082,148 | 49.5% |
| LOAD_FAST_LOAD_FAST | 283,761,771 | 26.2% |
| LOAD_CONST | 138,367,887 | 12.8% |
| CALL | 50,869,362 | 4.7% |
| LOAD_GLOBAL_MODULE | 31,522,706 | 2.9% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,494,932 | 51.6% |
| LOAD_ATTR_MODULE | 583,740 | 20.1% |
| LOAD_GLOBAL_BUILTIN | 543,240 | 18.7% |
| LOAD_FAST | 151,168 | 5.2% |
| RETURN_VALUE | 55,440 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 2,298,602 | 79.4% |
| COPY | 445,440 | 15.4% |
| LOAD_CONST | 151,228 | 5.2% |
| CALL_INTRINSIC_1 | 32 | 0.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 6,381,215 | 75.1% |
| POP_EXCEPT | 1,285,290 | 15.1% |
| POP_TOP | 386,940 | 4.6% |
| POP_JUMP_IF_FALSE | 155,640 | 1.8% |
| DELETE_FAST | 151,228 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,115,614 | 56.1% |
| COPY | 831,210 | 41.8% |
| CALL_INTRINSIC_1 | 42,148 | 2.1% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,493,051,257 | 63.3% |
| POP_TOP | 238,824,557 | 6.1% |
| CALL | 212,167,544 | 5.4% |
| SEND_GEN | 208,499,789 | 5.3% |
| COPY_FREE_VARS | 175,755,144 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,091,786,319 | 42.2% |
| LOAD_GLOBAL_BUILTIN | 846,848,172 | 17.1% |
| POP_TOP | 472,274,727 | 9.5% |
| NOP | 337,479,845 | 6.8% |
| LOAD_GLOBAL_MODULE | 336,430,121 | 6.8% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 267,566,008 | 20.0% |
| STORE_ATTR_SLOT | 246,970,561 | 18.4% |
| POP_TOP | 184,087,638 | 13.7% |
| STORE_ATTR_INSTANCE_VALUE | 176,818,478 | 13.2% |
| RESUME | 122,771,701 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 569,746,457 | 42.5% |
| INTERPRETER_EXIT | 410,755,139 | 30.6% |
| EXIT_INIT_CHECK | 67,138,854 | 5.0% |
| TO_BOOL_BOOL | 56,809,903 | 4.2% |
| END_FOR | 56,701,028 | 4.2% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 140,431,899 | 63.6% |
| COPY_FREE_VARS | 73,606,062 | 33.4% |
| CALL_PY_WITH_DEFAULTS | 3,374,437 | 1.5% |
| CALL_FUNCTION_EX | 1,715,666 | 0.8% |
| CALL | 873,190 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 78,585,287 | 32.9% |
| GET_ITER | 37,670,521 | 15.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 33,017,880 | 13.8% |
| STORE_FAST | 19,530,120 | 8.2% |
| INTERPRETER_EXIT | 18,176,226 | 7.6% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 774,016,469 | 25.9% |
| RETURN_VALUE | 509,526,265 | 17.1% |
| BUILD_TUPLE | 413,113,208 | 13.8% |
| LOAD_ATTR_INSTANCE_VALUE | 177,027,272 | 5.9% |
| BINARY_SUBSCR_DICT | 104,202,814 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 618,327,777 | 20.7% |
| RETURN_VALUE | 509,526,265 | 17.1% |
| INTERPRETER_EXIT | 329,750,369 | 11.1% |
| UNPACK_SEQUENCE_TUPLE | 264,500,662 | 8.9% |
| TO_BOOL_BOOL | 251,537,988 | 8.4% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 106,455,896 | 94.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 6,245,397 | 5.5% |
| SEND | 28,887 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 100,454,840 | 89.1% |
| YIELD_VALUE | 6,245,837 | 5.5% |
| END_ASYNC_FOR | 6,000,000 | 5.3% |
| SEND | 28,887 | 0.0% |
| SEND_GEN | 608 | 0.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 208,499,841 | 69.0% |
| LOAD_CONST | 93,861,640 | 31.0% |
| SEND | 608 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME | 208,499,789 | 69.0% |
| POP_TOP | 93,862,120 | 31.0% |
| END_SEND | 120 | 0.0% |
| YIELD_VALUE | 60 | 0.0% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 2,879,280 | 89.0% |
| LOAD_ATTR_INSTANCE_VALUE | 124,560 | 3.9% |
| STORE_FAST_LOAD_FAST | 108,000 | 3.3% |
| RETURN_VALUE | 69,060 | 2.1% |
| LOAD_FAST | 25,440 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,234,120 | 100.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 82,636,401 | 98.7% |
| SET_FUNCTION_ATTRIBUTE | 1,108,255 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,220,062 | 64.7% |
| LOAD_GLOBAL_BUILTIN | 18,989,340 | 22.7% |
| STORE_FAST | 5,794,375 | 6.9% |
| CALL_PY_EXACT_ARGS | 2,062,866 | 2.5% |
| SET_FUNCTION_ATTRIBUTE | 1,108,255 | 1.3% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 66,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 66,000 | 99.5% |
| STORE_FAST | 240 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.2% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,581,337 | 59.0% |
| LOAD_FAST_LOAD_FAST | 15,245,053 | 28.5% |
| CALL | 5,419,260 | 10.1% |
| SWAP | 946,681 | 1.8% |
| LOAD_GLOBAL_MODULE | 199,180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,910,891 | 29.7% |
| LOAD_DEREF | 13,447,060 | 25.1% |
| RETURN_CONST | 8,606,142 | 16.1% |
| JUMP_BACKWARD | 5,554,200 | 10.4% |
| LOAD_FAST_LOAD_FAST | 4,744,243 | 8.9% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 361,672,163 | 44.6% |
| LOAD_FAST_LOAD_FAST | 297,312,852 | 36.6% |
| SWAP | 77,247,692 | 9.5% |
| BINARY_SUBSCR_LIST_INT | 27,097,200 | 3.3% |
| RETURN_VALUE | 21,167,460 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300,522,404 | 37.0% |
| RETURN_CONST | 176,818,478 | 21.8% |
| LOAD_FAST_LOAD_FAST | 167,678,228 | 20.7% |
| LOAD_CONST | 67,548,903 | 8.3% |
| NOP | 51,795,471 | 6.4% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 515,576,012 | 48.5% |
| LOAD_FAST | 504,062,519 | 47.4% |
| SWAP | 40,401,404 | 3.8% |
| STORE_ATTR_SLOT | 2,126,415 | 0.2% |
| LOAD_ATTR_SLOT | 636,960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 279,498,428 | 26.3% |
| LOAD_FAST | 253,874,953 | 23.9% |
| RETURN_CONST | 246,970,561 | 23.2% |
| LOAD_CONST | 220,181,851 | 20.7% |
| LOAD_GLOBAL_BUILTIN | 25,391,400 | 2.4% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,739,760 | 48.5% |
| SWAP | 14,038,523 | 27.5% |
| LOAD_FAST_LOAD_FAST | 11,936,959 | 23.4% |
| LOAD_DEREF | 242,500 | 0.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,113,583 | 66.9% |
| JUMP_BACKWARD | 5,313,540 | 10.4% |
| RETURN_CONST | 4,426,120 | 8.7% |
| LOAD_CONST | 3,924,016 | 7.7% |
| LOAD_FAST_LOAD_FAST | 2,308,020 | 4.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 26,874,000 | 40.9% |
| STORE_FAST | 19,047,660 | 29.0% |
| LOAD_CONST | 6,838,767 | 10.4% |
| LOAD_FAST | 2,917,140 | 4.4% |
| YIELD_VALUE | 2,419,200 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,986,460 | 28.9% |
| LOAD_DEREF | 13,769,675 | 20.9% |
| LOAD_FAST_LOAD_FAST | 13,437,000 | 20.4% |
| LOAD_FAST | 9,639,580 | 14.7% |
| LOAD_CONST | 4,834,671 | 7.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,258,763,349 | 12.8% |
| BINARY_SUBSCR_STR_INT | 841,517,940 | 8.6% |
| STORE_FAST | 711,199,785 | 7.2% |
| RETURN_VALUE | 618,327,777 | 6.3% |
| FOR_ITER_LIST | 587,193,710 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,675,472,008 | 47.7% |
| LOAD_FAST_LOAD_FAST | 1,332,289,898 | 13.6% |
| JUMP_BACKWARD | 918,432,662 | 9.4% |
| STORE_FAST | 711,199,785 | 7.2% |
| LOAD_GLOBAL_BUILTIN | 536,643,206 | 5.5% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 80,532,600 | 58.9% |
| FOR_ITER_RANGE | 35,717,280 | 26.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,187,140 | 6.7% |
| FOR_ITER_TUPLE | 6,874,080 | 5.0% |
| FOR_ITER | 2,965,747 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 29,577,780 | 21.6% |
| LOAD_FAST | 24,445,380 | 17.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 20,928,140 | 15.3% |
| STORE_ATTR_INSTANCE_VALUE | 9,297,246 | 6.8% |
| POP_JUMP_IF_NOT_NONE | 8,887,140 | 6.5% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 815,163,841 | 52.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 368,162,123 | 23.9% |
| UNPACK_SEQUENCE_TUPLE | 140,575,186 | 9.1% |
| UNPACK_SEQUENCE_LIST | 134,205,000 | 8.7% |
| LOAD_ATTR_SLOT | 45,908,040 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 815,163,841 | 52.8% |
| LOAD_FAST | 466,234,319 | 30.2% |
| LOAD_FAST_LOAD_FAST | 86,531,279 | 5.6% |
| STORE_FAST | 75,477,105 | 4.9% |
| LOAD_GLOBAL_MODULE | 46,178,812 | 3.0% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 6,147,720 | 99.9% |
| RETURN_VALUE | 3,900 | 0.1% |
| LOAD_ATTR | 540 | 0.0% |
| LOAD_FAST | 360 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,864,320 | 79.1% |
| LOAD_GLOBAL_MODULE | 1,286,100 | 20.9% |
| LOAD_CONST | 2,040 | 0.0% |
| RETURN_CONST | 120 | 0.0% |
| INSTRUMENTED_RETURN_CONST | 60 | 0.0% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 1,320 | 27.5% |
| LOAD_CONST | 1,320 | 27.5% |
| LOAD_ATTR | 1,200 | 25.0% |
| IMPORT_NAME | 360 | 7.5% |
| CALL_NO_KW_BUILTIN_FAST | 180 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,680 | 35.0% |
| LOAD_CONST | 1,440 | 30.0% |
| LOAD_LOCALS | 1,200 | 25.0% |
| LOAD_NAME | 240 | 5.0% |
| STORE_NAME | 120 | 2.5% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 103,909,260 | 88.3% |
| LOAD_CONST | 13,495,566 | 11.5% |
| LOAD_FAST_LOAD_FAST | 258,360 | 0.2% |
| LOAD_ATTR | 8,040 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 107,615,046 | 91.5% |
| RETURN_CONST | 5,855,760 | 5.0% |
| LOAD_FAST_LOAD_FAST | 4,157,040 | 3.5% |
| JUMP_BACKWARD | 39,840 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 2,700 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 109,837,922 | 34.7% |
| LOAD_FAST | 64,774,559 | 20.5% |
| LOAD_FAST_LOAD_FAST | 56,745,560 | 17.9% |
| BINARY_OP_ADD_INT | 41,532,300 | 13.1% |
| LOAD_CONST | 27,783,040 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 112,068,360 | 35.4% |
| LOAD_FAST_LOAD_FAST | 104,111,580 | 32.9% |
| RETURN_CONST | 33,885,787 | 10.7% |
| LOAD_GLOBAL_BUILTIN | 27,003,020 | 8.5% |
| LOAD_DEREF | 15,741,300 | 5.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 95,460,717 | 48.0% |
| LOAD_FAST | 63,114,454 | 31.7% |
| CALL_NO_KW_BUILTIN_O | 13,999,260 | 7.0% |
| RETURN_VALUE | 7,992,040 | 4.0% |
| BINARY_SUBSCR_TUPLE_INT | 3,815,040 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 73,054,147 | 36.7% |
| LOAD_FAST | 66,169,726 | 33.3% |
| JUMP_BACKWARD | 31,630,097 | 15.9% |
| RETURN_CONST | 12,894,194 | 6.5% |
| LOAD_GLOBAL_MODULE | 7,343,168 | 3.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 157,633,500 | 52.3% |
| LOAD_FAST | 56,880,860 | 18.9% |
| LOAD_CONST | 26,911,806 | 8.9% |
| LOAD_FAST_LOAD_FAST | 24,060,530 | 8.0% |
| BINARY_SUBSCR_LIST_INT | 20,171,040 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 114,923,300 | 38.1% |
| JUMP_BACKWARD | 110,077,340 | 36.5% |
| LOAD_FAST_LOAD_FAST | 71,547,390 | 23.7% |
| RETURN_CONST | 4,469,760 | 1.5% |
| LOAD_CONST | 230,760 | 0.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 268,862,560 | 28.9% |
| BINARY_OP_ADD_FLOAT | 116,612,580 | 12.5% |
| LOAD_FAST | 105,302,956 | 11.3% |
| BINARY_OP_ADD_INT | 88,108,140 | 9.5% |
| BINARY_OP_SUBTRACT_INT | 68,653,095 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 268,862,560 | 28.9% |
| STORE_SUBSCR_LIST_INT | 157,633,500 | 16.9% |
| COPY | 112,622,822 | 12.1% |
| STORE_SUBSCR | 109,837,922 | 11.8% |
| STORE_ATTR_INSTANCE_VALUE | 77,247,692 | 8.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 166,245,701 | 80.9% |
| LOAD_ATTR_INSTANCE_VALUE | 23,952,643 | 11.7% |
| LOAD_ATTR | 7,358,306 | 3.6% |
| LOAD_ATTR_SLOT | 3,352,621 | 1.6% |
| COPY | 2,330,947 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 132,444,873 | 64.5% |
| POP_JUMP_IF_FALSE | 72,262,736 | 35.2% |
| TO_BOOL | 236,214 | 0.1% |
| UNARY_NOT | 220,621 | 0.1% |
| TO_BOOL_NONE | 125,707 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 83,565,323 | 46.7% |
| LOAD_ATTR_INSTANCE_VALUE | 59,746,346 | 33.4% |
| LOAD_ATTR_SLOT | 17,761,080 | 9.9% |
| STORE_FAST_LOAD_FAST | 7,990,920 | 4.5% |
| COPY | 7,172,924 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 94,344,369 | 52.7% |
| POP_JUMP_IF_TRUE | 82,915,551 | 46.3% |
| EXTENDED_ARG | 901,240 | 0.5% |
| TO_BOOL_NONE | 600,844 | 0.3% |
| TO_BOOL_ALWAYS_TRUE | 116,507 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_NO_KW_ISINSTANCE | 797,126,448 | 25.0% |
| LOAD_FAST | 715,259,932 | 22.5% |
| CALL_NO_KW_BUILTIN_FAST | 477,720,462 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 428,278,770 | 13.4% |
| RETURN_VALUE | 251,537,988 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,325,355,389 | 73.0% |
| POP_JUMP_IF_TRUE | 725,093,192 | 22.8% |
| EXTENDED_ARG | 88,770,272 | 2.8% |
| UNARY_NOT | 46,475,500 | 1.5% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 13,920 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 173,573,273 | 76.0% |
| CALL_NO_KW_BUILTIN_O | 12,836,580 | 5.6% |
| COPY | 12,775,318 | 5.6% |
| BINARY_OP | 9,168,461 | 4.0% |
| LOAD_ATTR_SLOT | 6,926,500 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 201,610,134 | 88.3% |
| POP_JUMP_IF_TRUE | 25,592,416 | 11.2% |
| UNARY_NOT | 1,035,600 | 0.5% |
| EXTENDED_ARG | 164,040 | 0.1% |
| TO_BOOL_BOOL | 13,620 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 75,164,993 | 67.0% |
| LOAD_ATTR_INSTANCE_VALUE | 27,750,632 | 24.7% |
| LOAD_ATTR_SLOT | 5,049,000 | 4.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,712,180 | 1.5% |
| COPY | 814,420 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 61,666,504 | 54.9% |
| POP_JUMP_IF_FALSE | 47,006,430 | 41.9% |
| UNARY_NOT | 2,640,720 | 2.4% |
| EXTENDED_ARG | 902,760 | 0.8% |
| TO_BOOL | 23,200 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 169,518,759 | 45.0% |
| LOAD_ATTR_SLOT | 88,076,972 | 23.4% |
| LOAD_ATTR_INSTANCE_VALUE | 56,724,292 | 15.1% |
| LOAD_ATTR | 21,871,026 | 5.8% |
| RETURN_CONST | 13,912,340 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 296,850,500 | 78.9% |
| POP_JUMP_IF_TRUE | 77,693,586 | 20.6% |
| EXTENDED_ARG | 967,320 | 0.3% |
| TO_BOOL_ALWAYS_TRUE | 600,929 | 0.2% |
| TO_BOOL | 123,676 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,966,063 | 63.9% |
| LOAD_ATTR_SLOT | 7,140,480 | 10.6% |
| LOAD_ATTR_INSTANCE_VALUE | 4,407,740 | 6.6% |
| CALL_NO_KW_METHOD_DESCRIPTOR_FAST | 3,881,340 | 5.8% |
| COPY | 2,682,160 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 36,172,744 | 53.8% |
| POP_JUMP_IF_TRUE | 30,414,560 | 45.2% |
| UNARY_NOT | 600,240 | 0.9% |
| TO_BOOL_NONE | 36,180 | 0.1% |
| EXTENDED_ARG | 8,280 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 10,639,711 | 92.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 405,022 | 3.5% |
| LOAD_ATTR_MODULE | 311,572 | 2.7% |
| LOAD_FAST | 122,040 | 1.1% |
| LOAD_FAST_LOAD_FAST | 10,260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 11,488,605 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 107,898,960 | 89.0% |
| LOAD_FAST_LOAD_FAST | 7,964,640 | 6.6% |
| LOAD_GLOBAL_MODULE | 3,058,560 | 2.5% |
| BINARY_SUBSCR_TUPLE_INT | 1,205,640 | 1.0% |
| CALL_NO_KW_LEN | 668,220 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 79,368,120 | 65.4% |
| BINARY_SUBSCR_LIST_INT | 26,768,580 | 22.1% |
| CALL_PY_EXACT_ARGS | 3,191,160 | 2.6% |
| STORE_SUBSCR | 2,419,140 | 2.0% |
| BINARY_SUBSCR | 2,419,140 | 2.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 46,475,500 | 91.1% |
| TO_BOOL_LIST | 2,640,720 | 5.2% |
| TO_BOOL_INT | 1,035,600 | 2.0% |
| TO_BOOL_STR | 600,240 | 1.2% |
| TO_BOOL | 220,621 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 23,463,060 | 46.0% |
| RETURN_VALUE | 15,192,100 | 29.8% |
| KW_NAMES | 10,514,640 | 20.6% |
| CALL_PY_EXACT_ARGS | 746,880 | 1.5% |
| LOAD_FAST | 555,240 | 1.1% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 346,800 | 61.2% |
| YIELD_VALUE | 218,520 | 38.5% |
| CALL_INTRINSIC_1 | 960 | 0.2% |
| FOR_ITER | 720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 567,000 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_NO_KW_METHOD_DESCRIPTOR_NOARGS | 96,120 | 44.4% |
| CALL_NO_KW_METHOD_DESCRIPTOR_FAST | 67,940 | 31.4% |
| COPY | 19,920 | 9.2% |
| FOR_ITER_LIST | 10,560 | 4.9% |
| CALL_BUILTIN_CLASS | 10,080 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 134,282 | 62.0% |
| STORE_FAST | 79,689 | 36.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,728 | 0.8% |
| UNPACK_SEQUENCE | 460 | 0.2% |
| UNPACK_SEQUENCE_TUPLE | 440 | 0.2% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,417,940 | 70.2% |
| UNPACK_SEQUENCE_TUPLE | 24,026,440 | 17.1% |
| CALL | 10,636,560 | 7.6% |
| STORE_FAST | 6,001,740 | 4.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 799,600 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 134,205,000 | 95.7% |
| STORE_FAST | 6,004,980 | 4.3% |
| UNPACK_SEQUENCE_TUPLE | 24,040 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 264,500,662 | 62.2% |
| LOAD_FAST | 103,134,100 | 24.2% |
| BINARY_SUBSCR_DICT | 15,509,644 | 3.6% |
| STORE_FAST | 12,281,520 | 2.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,001,200 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 260,433,868 | 61.2% |
| STORE_FAST_STORE_FAST | 140,575,186 | 33.1% |
| UNPACK_SEQUENCE_LIST | 24,026,440 | 5.6% |
| LOAD_FAST | 290,520 | 0.1% |
| POP_TOP | 120 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 314,628,090 | 52.0% |
| FOR_ITER | 151,762,819 | 25.1% |
| RETURN_VALUE | 84,701,604 | 14.0% |
| LOAD_FAST | 35,337,180 | 5.8% |
| BINARY_SUBSCR_LIST_INT | 9,483,960 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 368,162,123 | 60.8% |
| STORE_FAST | 215,215,606 | 35.5% |
| UNPACK_SEQUENCE_TUPLE | 12,001,200 | 2.0% |
| STORE_FAST_LOAD_FAST | 9,187,140 | 1.5% |
| LOAD_FAST | 906,540 | 0.1% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 138,122 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 137,322 | 99.4% |
| TO_BOOL_BOOL | 780 | 0.6% |
| TO_BOOL | 20 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 210,931,680 | 30.4% |
| YIELD_VALUE | 208,500,145 | 30.1% |
| CALL_INTRINSIC_1 | 94,136,760 | 13.6% |
| BINARY_SUBSCR | 30,970,265 | 4.5% |
| LOAD_CONST | 26,891,057 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 451,459,526 | 65.1% |
| YIELD_VALUE | 208,500,145 | 30.1% |
| STORE_FAST | 24,773,580 | 3.6% |
| UNPACK_SEQUENCE_TUPLE | 4,808,640 | 0.7% |
| STORE_DEREF | 2,419,200 | 0.3% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |   1111034459 | 26.5% |
| specialization.deopt |        68522 | 0.0% |
|          hit |   3071844444 | 73.4% |
|         miss |      3634521 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 70,618 | 19.8% |
| Failure | 286,863 | 80.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 112,980 | 39.4% |
| other | 77,501 | 27.0% |
| out of range | 40,680 | 14.2% |
| buffer int | 25,742 | 9.0% |
| list slice | 25,520 | 8.9% |
| sequence int | 2,920 | 1.0% |
| code complex parameters | 1,420 | 0.5% |
| buffer slice | 40 | 0.0% |
| tuple slice | 40 | 0.0% |
| string slice | 20 | 0.0% |


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    316113803 | 38.7% |
| specialization.deopt |           40 | 0.0% |
|          hit |    500627856 | 61.3% |
|         miss |         2220 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,746 | 2.0% |
| Failure | 83,801 | 98.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 45,640 | 54.5% |
| dict subclass no override | 17,961 | 21.4% |
| py simple | 13,820 | 16.5% |
| bytearray int | 5,200 | 6.2% |
| out of range | 1,020 | 1.2% |
| other | 120 | 0.1% |
| list slice | 40 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    205038229 | 4.7% |
| specialization.deopt |      1599019 | 0.0% |
|          hit |   4064061606 | 93.3% |
|         miss |     84780164 | 1.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,613,101 | 80.8% |
| Failure | 383,990 | 19.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| number | 135,740 | 35.3% |
| other | 125,980 | 32.8% |
| tuple | 75,340 | 19.6% |
| dict | 16,915 | 4.4% |
| bytes | 10,781 | 2.8% |
| set | 7,220 | 1.9% |
| sequence | 6,042 | 1.6% |
| mapping | 4,592 | 1.2% |
| float | 980 | 0.3% |
| bytearray | 320 | 0.1% |
| memory view | 80 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    839837347 | 15.6% |
| specialization.deopt |       712840 | 0.0% |
|          hit |   4514153519 | 83.7% |
|         miss |     37782959 | 0.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 716,922 | 39.2% |
| Failure | 1,110,419 | 60.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| subtract different types | 579,020 | 52.1% |
| multiply different types | 171,572 | 15.5% |
| add different types | 151,880 | 13.7% |
| floor divide | 32,760 | 3.0% |
| and int | 32,092 | 2.9% |
| remainder | 32,025 | 2.9% |
| add other | 27,100 | 2.4% |
| lshift | 18,760 | 1.7% |
| rshift | 16,638 | 1.5% |
| true divide different types | 14,864 | 1.3% |
| xor | 10,420 | 0.9% |
| true divide float | 6,788 | 0.6% |
| subtract other | 5,520 | 0.5% |
| or | 4,096 | 0.4% |
| power | 3,702 | 0.3% |
| true divide other | 1,202 | 0.1% |
| multiply other | 1,060 | 0.1% |
| and other | 860 | 0.1% |
| and different types | 60 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    894366025 | 10.1% |
| specialization.deopt |      2750642 | 0.0% |
|          hit |   7775705546 | 88.2% |
|         miss |    145906423 | 1.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,798,505 | 87.6% |
| Failure | 396,872 | 12.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 66,309 | 16.7% |
| code complex parameters | 56,637 | 14.3% |
| kwnames | 56,135 | 14.1% |
| no dict | 51,380 | 12.9% |
| class no vectorcall | 29,483 | 7.4% |
| cfunc varargs keywords | 24,912 | 6.3% |
| cfunc noargs | 22,583 | 5.7% |
| meth descr varargs | 22,422 | 5.6% |
| other | 11,447 | 2.9% |
| init not python | 10,420 | 2.6% |
| class mutable | 8,758 | 2.2% |
| init not simple | 8,420 | 2.1% |
| meth descr varargs keywords | 7,335 | 1.8% |
| wrong number arguments | 4,460 | 1.1% |
| cmethod | 3,600 | 0.9% |
| cfunc varargs | 3,372 | 0.8% |
| bound method | 3,367 | 0.8% |
| method wrapper | 2,468 | 0.6% |
| operator wrapper | 2,364 | 0.6% |
| str | 1,000 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    145435002 | 4.3% |
| specialization.deopt |        26208 | 0.0% |
|          hit |   3202610288 | 95.6% |
|         miss |      1390210 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 30,252 | 21.1% |
| Failure | 113,092 | 78.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 50,786 | 44.9% |
| different types | 23,809 | 21.1% |
| baseobject | 13,265 | 11.7% |
| float long | 9,297 | 8.2% |
| set | 6,620 | 5.9% |
| other | 3,000 | 2.7% |
| bool | 2,355 | 2.1% |
| tuple | 1,680 | 1.5% |
| list | 1,020 | 0.9% |
| bytes | 800 | 0.7% |
| long float | 320 | 0.3% |
| string | 140 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    293043594 | 11.6% |
| specialization.deopt |      2480430 | 0.1% |
|          hit |   2103037045 | 83.2% |
|         miss |    131463475 | 5.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,481,495 | 96.3% |
| Failure | 96,679 | 3.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 23,020 | 23.8% |
| dict items | 20,431 | 21.1% |
| seq iter | 15,120 | 15.6% |
| set | 13,227 | 13.7% |
| other | 7,660 | 7.9% |
| dict values | 3,820 | 4.0% |
| reversed list | 3,641 | 3.8% |
| zip | 3,400 | 3.5% |
| ascii string | 2,680 | 2.8% |
| dict keys | 2,060 | 2.1% |
| itertools | 820 | 0.8% |
| map | 600 | 0.6% |
| callable | 120 | 0.1% |
| bytes | 80 | 0.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |   1037297132 | 10.0% |
| specialization.deopt |      9595920 | 0.1% |
|          hit |   8837706345 | 85.1% |
|         miss |    508729330 | 4.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,667,751 | 95.6% |
| Failure | 449,709 | 4.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 147,846 | 32.9% |
| metaclass attribute | 101,972 | 22.7% |
| method | 60,704 | 13.5% |
| not managed dict | 59,478 | 13.2% |
| shadowed | 40,665 | 9.0% |
| non object slot | 7,723 | 1.7% |
| class method obj | 7,260 | 1.6% |
| class attr descriptor | 6,280 | 1.4% |
| overridden | 5,220 | 1.2% |
| non overriding descriptor | 4,472 | 1.0% |
| mutable class | 2,861 | 0.6% |
| not in keys | 1,740 | 0.4% |
| class attr simple | 1,688 | 0.4% |
| module attr not found | 1,340 | 0.3% |
| builtin class method | 440 | 0.1% |
| property | 20 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      7322508 | 0.1% |
| specialization.deopt |          480 | 0.0% |
|          hit |   6997282626 | 99.9% |
|         miss |        27958 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 55,837 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |    116740568 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,580 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    112700685 | 27.2% |
|          hit |    302361909 | 72.8% |
|         miss |          180 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 608 | 2.1% |
| Failure | 28,887 | 97.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| async generator send | 24,440 | 84.6% |
| other | 4,367 | 15.1% |
| dict keys | 40 | 0.1% |
| list | 40 | 0.1% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     53482899 | 2.7% |
| specialization.deopt |      3437592 | 0.2% |
|          hit |   1743167016 | 88.1% |
|         miss |    182201212 | 9.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,460,284 | 98.9% |
| Failure | 38,740 | 1.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 17,280 | 44.6% |
| not in dict | 10,740 | 27.7% |
| overriding descriptor | 5,020 | 13.0% |
| property | 1,220 | 3.1% |
| not in keys | 1,160 | 3.0% |
| non object slot | 920 | 2.4% |
| overridden | 860 | 2.2% |
| no dict | 860 | 2.2% |
| not managed dict | 380 | 1.0% |
| method | 300 | 0.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       213971 | 0.0% |
| specialization.deopt |        48080 | 0.0% |
|          hit |   1168574943 | 99.8% |
|         miss |      2547700 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 50,288 | 99.1% |
| Failure | 460 | 0.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| iterator | 200 | 43.5% |
| sequence | 180 | 39.1% |
| other | 80 | 17.4% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 94,495,993,400 | 63.7% |
| Not specialized | 9,689,269,153 | 6.5% |
| Specialized | 44,261,365,359 | 29.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 1,111,034,459 | 22.2% |
| LOAD_ATTR | 1,037,297,132 | 20.7% |
| CALL | 894,366,025 | 17.8% |
| BINARY_OP | 839,837,347 | 16.7% |
| STORE_SUBSCR | 316,113,803 | 6.3% |
| FOR_ITER | 293,043,594 | 5.8% |
| TO_BOOL | 205,038,229 | 4.1% |
| COMPARE_OP | 145,435,002 | 2.9% |
| SEND | 112,700,685 | 2.2% |
| STORE_ATTR | 53,482,899 | 1.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 193,657,750 | 17.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 152,827,426 | 13.9% |
| STORE_ATTR_SLOT | 112,693,969 | 10.3% |
| CALL_PY_EXACT_ARGS | 86,801,607 | 7.9% |
| STORE_ATTR_INSTANCE_VALUE | 69,438,560 | 6.3% |
| FOR_ITER_LIST | 65,827,364 | 6.0% |
| FOR_ITER_TUPLE | 65,584,691 | 6.0% |
| LOAD_ATTR_SLOT | 57,456,883 | 5.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 50,962,801 | 4.6% |
| LOAD_ATTR_METHOD_NO_DICT | 45,168,351 | 4.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 1,218,713,465 | 23.4% |
| Calls to Python functions inlined | 3,997,786,444 | 76.6% |
| Calls via PyEval_EvalFrame (total) | 1,218,713,465 | 23.4% |
| Calls via PyEval_EvalFrame (vector) | 678,992,182 | 13.0% |
| Calls via PyEval_EvalFrame (generator) | 539,721,283 | 10.3% |
| Calls via PyEval_EvalFrame (legacy) | 3,780 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 678,987,082 | 13.0% |
| Calls via PyEval_EvalFrame (build class) | 1,320 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 191,536,213 | 3.7% |
| Calls via PyEval_EvalFrame (function ex) | 13,953,401 | 0.3% |
| Calls via PyEval_EvalFrame (api) | 115,849,339 | 2.2% |
| Calls via PyEval_EvalFrame (method) | 94,975,694 | 1.8% |
| Frames pushed | 4,351,341,230 | 83.4% |
| Frame objects created | 59,580,159 | 1.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 4,173,338,233 | 35.4% |
| Frees to freelist | 4,177,464,671 |  |
| Allocations | 7,614,076,828 | 64.6% |
| Allocations to 512 bytes | 7,532,345,161 | 63.9% |
| Allocations to 4 kbytes | 66,548,640 | 0.6% |
| Allocations over 4 kbytes | 15,183,027 | 0.1% |
| Frees | 7,850,424,166 |  |
| New values | 57,541,417 |  |
| Interpreter increfs | 56,313,820,410 | 77.9% |
| Interpreter decrefs | 65,318,292,791 | 78.3% |
| Increfs | 15,971,077,043 | 22.1% |
| Decrefs | 18,112,701,329 | 21.7% |
| Materialize dict (on request) | 3,979,281 | 6.9% |
| Materialize dict (new key) | 142,640 | 0.2% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 1,524,461 | 2.6% |
| Method cache hits | 1,825,330,332 |  |
| Method cache misses | 64,767,059 |  |
| Method cache collisions | 70,303,654 |  |
| Method cache dunder hits | 2,210,898,874 |  |
| Method cache dunder misses | 5,563,304 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 345,701 | 34,533,165 | 3,545,704,662 |
| 1 | 30,643 | 47,672,264 | 2,659,310,040 |
| 2 | 14,205 | 40,830,864 | 9,804,098,383 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 8,277 |


</details>

---
Stats gathered on: 2023-08-31
