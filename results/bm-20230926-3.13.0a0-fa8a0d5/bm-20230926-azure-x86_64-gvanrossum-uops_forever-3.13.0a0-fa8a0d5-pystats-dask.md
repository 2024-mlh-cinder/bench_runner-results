
# Pystats results

- benchmark: dask
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 616,481,417 | 20.3% | 20.3% |  |
| LOAD_CONST | 208,645,615 | 6.9% | 27.2% |  |
| POP_JUMP_IF_FALSE | 205,858,858 | 6.8% | 34.0% |  |
| STORE_FAST | 160,823,528 | 5.3% | 39.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 139,935,172 | 4.6% | 43.9% | 0.2% |
| COMPARE_OP_INT | 107,871,815 | 3.6% | 47.4% | 0.1% |
| LOAD_GLOBAL_BUILTIN | 102,550,171 | 3.4% | 50.8% | 0.0% |
| RESUME_CHECK | 100,455,987 | 3.3% | 54.1% | 0.0% |
| LOAD_GLOBAL_MODULE | 97,964,162 | 3.2% | 57.4% | 0.0% |
| LOAD_FAST_LOAD_FAST | 66,585,751 | 2.2% | 59.6% |  |
| RETURN_VALUE | 66,199,812 | 2.2% | 61.7% |  |
| TO_BOOL_BOOL | 65,074,895 | 2.1% | 63.9% |  |
| POP_TOP | 60,331,582 | 2.0% | 65.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 53,289,246 | 1.8% | 67.6% | 0.0% |
| PUSH_NULL | 52,662,064 | 1.7% | 69.4% |  |
| CALL_PY_EXACT_ARGS | 41,159,106 | 1.4% | 70.7% | 0.2% |
| CALL_ISINSTANCE | 34,622,256 | 1.1% | 71.9% |  |
| RETURN_CONST | 32,931,301 | 1.1% | 73.0% |  |
| BINARY_OP_SUBTRACT_INT | 31,161,997 | 1.0% | 74.0% |  |
| LOAD_DEREF | 30,746,769 | 1.0% | 75.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 29,429,655 | 1.0% | 76.0% | 1.0% |
| BINARY_OP | 29,168,435 | 1.0% | 76.9% |  |
| CALL_LEN | 26,902,923 | 0.9% | 77.8% |  |
| SWAP | 26,410,437 | 0.9% | 78.7% |  |
| BUILD_TUPLE | 25,898,798 | 0.9% | 79.5% |  |
| LOAD_ATTR_SLOT | 25,871,219 | 0.9% | 80.4% | 3.9% |
| BINARY_OP_ADD_INT | 23,757,164 | 0.8% | 81.2% | 0.0% |
| COPY | 22,273,642 | 0.7% | 81.9% |  |
| CALL | 21,418,734 | 0.7% | 82.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 20,947,919 | 0.7% | 83.3% | 0.0% |
| EXTENDED_ARG | 19,901,905 | 0.7% | 84.0% |  |
| NOP | 19,866,061 | 0.7% | 84.6% |  |
| CALL_PY_WITH_DEFAULTS | 19,480,030 | 0.6% | 85.3% | 0.0% |
| INTERPRETER_EXIT | 18,923,150 | 0.6% | 85.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 16,513,761 | 0.5% | 86.4% | 0.0% |
| LOAD_ATTR_WITH_HINT | 16,445,680 | 0.5% | 87.0% | 0.9% |
| LOAD_ATTR | 16,412,782 | 0.5% | 87.5% |  |
| LOAD_ATTR_MODULE | 14,760,237 | 0.5% | 88.0% | 0.0% |
| STORE_FAST_STORE_FAST | 13,668,338 | 0.5% | 88.4% |  |
| GET_ITER | 12,998,107 | 0.4% | 88.9% |  |
| STORE_ATTR_SLOT | 12,322,428 | 0.4% | 89.3% | 7.0% |
| BUILD_MAP | 11,966,057 | 0.4% | 89.7% |  |
| COMPARE_OP | 11,669,425 | 0.4% | 90.1% |  |
| POP_JUMP_IF_TRUE | 11,568,858 | 0.4% | 90.4% |  |
| FOR_ITER | 11,467,117 | 0.4% | 90.8% |  |
| POP_JUMP_IF_NOT_NONE | 11,158,827 | 0.4% | 91.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 10,300,958 | 0.3% | 91.5% |  |
| BINARY_SUBSCR_DICT | 10,079,785 | 0.3% | 91.9% |  |
| JUMP_FORWARD | 10,077,055 | 0.3% | 92.2% |  |
| ENTER_EXECUTOR | 9,890,363 | 0.3% | 92.5% |  |
| MAKE_CELL | 9,643,622 | 0.3% | 92.8% |  |
| CALL_FUNCTION_EX | 9,225,938 | 0.3% | 93.1% |  |
| BUILD_LIST | 9,196,347 | 0.3% | 93.4% |  |
| BINARY_SUBSCR | 8,173,747 | 0.3% | 93.7% |  |
| UNPACK_SEQUENCE_TUPLE | 8,155,305 | 0.3% | 94.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 8,105,086 | 0.3% | 94.2% |  |
| CONTAINS_OP | 7,899,818 | 0.3% | 94.5% |  |
| POP_JUMP_IF_NONE | 7,732,178 | 0.3% | 94.8% |  |
| CALL_BUILTIN_FAST | 7,489,543 | 0.2% | 95.0% | 0.0% |
| IS_OP | 7,456,590 | 0.2% | 95.2% |  |
| CALL_BUILTIN_CLASS | 7,206,532 | 0.2% | 95.5% |  |
| DICT_MERGE | 6,925,820 | 0.2% | 95.7% |  |
| CALL_KW | 6,817,184 | 0.2% | 95.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 6,695,593 | 0.2% | 96.2% | 1.3% |
| TO_BOOL | 6,515,163 | 0.2% | 96.4% |  |
| LIST_EXTEND | 6,457,324 | 0.2% | 96.6% |  |
| CALL_INTRINSIC_1 | 6,384,840 | 0.2% | 96.8% |  |
| JUMP_BACKWARD | 6,176,704 | 0.2% | 97.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 6,007,957 | 0.2% | 97.2% |  |
| CALL_TYPE_1 | 5,987,651 | 0.2% | 97.4% |  |
| STORE_SUBSCR_DICT | 5,987,618 | 0.2% | 97.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,087,314 | 0.2% | 97.8% | 2.7% |
| BINARY_SLICE | 4,624,913 | 0.2% | 97.9% |  |
| FOR_ITER_TUPLE | 4,488,030 | 0.1% | 98.1% |  |
| COMPARE_OP_STR | 4,125,825 | 0.1% | 98.2% | 0.0% |
| CALL_BUILTIN_O | 3,673,122 | 0.1% | 98.3% | 0.0% |
| TO_BOOL_NONE | 3,519,813 | 0.1% | 98.4% | 0.2% |
| COPY_FREE_VARS | 3,130,602 | 0.1% | 98.5% |  |
| LOAD_ATTR_PROPERTY | 2,052,390 | 0.1% | 98.6% | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,927,556 | 0.1% | 98.7% | 0.0% |
| FOR_ITER_RANGE | 1,725,895 | 0.1% | 98.7% |  |
| BEFORE_WITH | 1,666,619 | 0.1% | 98.8% |  |
| TO_BOOL_INT | 1,650,910 | 0.1% | 98.8% |  |
| LOAD_FAST_AND_CLEAR | 1,634,685 | 0.1% | 98.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,621,743 | 0.1% | 98.9% | 3.5% |
| FOR_ITER_LIST | 1,611,432 | 0.1% | 99.0% |  |
| COMPARE_OP_FLOAT | 1,427,703 | 0.0% | 99.0% | 0.1% |
| CALL_LIST_APPEND | 1,426,662 | 0.0% | 99.1% |  |
| BINARY_SUBSCR_LIST_INT | 1,316,227 | 0.0% | 99.1% | 4.3% |
| TO_BOOL_LIST | 1,246,854 | 0.0% | 99.2% |  |
| YIELD_VALUE | 1,171,193 | 0.0% | 99.2% |  |
| MAKE_FUNCTION | 1,159,175 | 0.0% | 99.3% |  |
| SET_FUNCTION_ATTRIBUTE | 1,146,320 | 0.0% | 99.3% |  |
| STORE_ATTR_WITH_HINT | 1,067,384 | 0.0% | 99.3% | 0.4% |
| DELETE_SUBSCR | 1,065,073 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 904,939 | 0.0% | 99.4% | 0.2% |
| BUILD_CONST_KEY_MAP | 891,846 | 0.0% | 99.4% |  |
| STORE_ATTR | 755,694 | 0.0% | 99.4% |  |
| RETURN_GENERATOR | 728,957 | 0.0% | 99.5% |  |
| STORE_FAST_LOAD_FAST | 698,337 | 0.0% | 99.5% |  |
| CALL_TUPLE_1 | 695,536 | 0.0% | 99.5% |  |
| PUSH_EXC_INFO | 693,663 | 0.0% | 99.5% |  |
| POP_EXCEPT | 693,658 | 0.0% | 99.6% |  |
| STORE_DEREF | 674,127 | 0.0% | 99.6% |  |
| MAP_ADD | 653,204 | 0.0% | 99.6% |  |
| TO_BOOL_ALWAYS_TRUE | 640,737 | 0.0% | 99.6% | 1.0% |
| BINARY_OP_SUBTRACT_FLOAT | 621,564 | 0.0% | 99.6% |  |
| CHECK_EXC_MATCH | 593,849 | 0.0% | 99.7% |  |
| SEND_GEN | 532,163 | 0.0% | 99.7% | 0.0% |
| BINARY_OP_MULTIPLY_INT | 516,422 | 0.0% | 99.7% |  |
| LOAD_SUPER_ATTR_METHOD | 512,157 | 0.0% | 99.7% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 493,325 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_GETITEM | 474,394 | 0.0% | 99.7% | 0.0% |
| BUILD_SET | 451,151 | 0.0% | 99.8% |  |
| END_SEND | 443,309 | 0.0% | 99.8% |  |
| GET_AWAITABLE | 442,447 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 430,002 | 0.0% | 99.8% | 0.3% |
| FORMAT_SIMPLE | 418,520 | 0.0% | 99.8% |  |
| LIST_APPEND | 415,002 | 0.0% | 99.8% |  |
| SEND | 406,024 | 0.0% | 99.8% |  |
| STORE_SUBSCR | 400,566 | 0.0% | 99.9% |  |
| BUILD_STRING | 371,574 | 0.0% | 99.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 315,372 | 0.0% | 99.9% | 0.1% |
| DELETE_FAST | 300,011 | 0.0% | 99.9% |  |
| TO_BOOL_STR | 286,819 | 0.0% | 99.9% | 0.1% |
| RERAISE | 272,450 | 0.0% | 99.9% |  |
| CALL_STR_1 | 244,824 | 0.0% | 99.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 220,785 | 0.0% | 99.9% | 0.3% |
| EXIT_INIT_CHECK | 220,005 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 192,377 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 179,102 | 0.0% | 99.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 159,162 | 0.0% | 100.0% | 19.9% |
| IMPORT_FROM | 153,447 | 0.0% | 100.0% |  |
| IMPORT_NAME | 152,967 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 148,966 | 0.0% | 100.0% | 1.1% |
| BINARY_SUBSCR_STR_INT | 139,860 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 133,803 | 0.0% | 100.0% |  |
| SET_ADD | 133,320 | 0.0% | 100.0% |  |
| UNARY_INVERT | 77,912 | 0.0% | 100.0% |  |
| BUILD_SLICE | 77,096 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 75,426 | 0.0% | 100.0% | 0.4% |
| UNPACK_EX | 66,000 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 66,000 | 0.0% | 100.0% |  |
| SET_UPDATE | 66,000 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 62,066 | 0.0% | 100.0% |  |
| DICT_UPDATE | 39,616 | 0.0% | 100.0% |  |
| STORE_SLICE | 38,236 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,510 | 0.0% | 100.0% |  |
| DELETE_ATTR | 8,229 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 8,040 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 7,494 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,483 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,720 | 0.0% | 100.0% | 95.2% |
| END_FOR | 3,087 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 2,580 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 2,398 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 1,860 | 0.0% | 100.0% |  |
| GET_YIELD_FROM_ITER | 1,322 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_LIST | 901 | 0.0% | 100.0% |  |
| UNARY_NOT | 782 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 600 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 400 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 300 | 0.0% | 100.0% |  |
| RESUME | 157 | 0.0% | 100.0% | 2946.5% |
| FORMAT_WITH_SPEC | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_FALSE LOAD_FAST | 137,041,414 | 4.5% | 4.5% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 107,946,011 | 3.6% | 8.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 100,628,281 | 3.3% | 11.4% |
| STORE_FAST LOAD_FAST | 91,752,148 | 3.0% | 14.4% |
| LOAD_FAST LOAD_CONST | 70,449,773 | 2.3% | 16.7% |
| LOAD_CONST COMPARE_OP_INT | 62,010,032 | 2.0% | 18.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 53,372,752 | 1.8% | 20.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 45,569,739 | 1.5% | 22.0% |
| RESUME_CHECK LOAD_FAST | 45,462,155 | 1.5% | 23.5% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 42,888,024 | 1.4% | 25.0% |
| PUSH_NULL LOAD_FAST | 39,050,302 | 1.3% | 26.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 38,301,047 | 1.3% | 27.5% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 37,065,235 | 1.2% | 28.7% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 36,067,492 | 1.2% | 29.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 35,420,283 | 1.2% | 31.1% |
| LOAD_FAST PUSH_NULL | 34,761,258 | 1.1% | 32.2% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 34,268,133 | 1.1% | 33.4% |
| LOAD_CONST LOAD_FAST | 31,019,807 | 1.0% | 34.4% |
| POP_TOP LOAD_FAST | 29,390,613 | 1.0% | 35.3% |
| LOAD_CONST BINARY_OP | 26,327,340 | 0.9% | 36.2% |
| RETURN_CONST POP_TOP | 25,624,422 | 0.8% | 37.1% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 24,435,766 | 0.8% | 37.9% |
| LOAD_FAST LOAD_ATTR_SLOT | 24,096,872 | 0.8% | 38.7% |
| BINARY_OP LOAD_CONST | 22,351,632 | 0.7% | 39.4% |
| LOAD_CONST STORE_FAST | 22,206,679 | 0.7% | 40.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 19,088,323 | 0.6% | 40.8% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 18,812,597 | 0.6% | 41.4% |
| RETURN_VALUE STORE_FAST | 18,742,938 | 0.6% | 42.0% |
| LOAD_FAST RETURN_VALUE | 18,693,544 | 0.6% | 42.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 18,408,888 | 0.6% | 43.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 17,891,420 | 0.6% | 43.8% |
| CACHE RESUME_CHECK | 17,300,180 | 0.6% | 44.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 16,629,258 | 0.5% | 44.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 16,506,440 | 0.5% | 45.5% |
| POP_JUMP_IF_FALSE RETURN_CONST | 15,444,357 | 0.5% | 46.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 15,232,171 | 0.5% | 46.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 14,604,001 | 0.5% | 47.0% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 14,361,123 | 0.5% | 47.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 14,310,976 | 0.5% | 47.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 14,237,909 | 0.5% | 48.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 14,216,090 | 0.5% | 48.8% |
| STORE_FAST LOAD_CONST | 14,086,983 | 0.5% | 49.3% |
| LOAD_FAST CALL_LEN | 13,665,481 | 0.5% | 49.8% |
| LOAD_DEREF LOAD_ATTR_INSTANCE_VALUE | 13,661,971 | 0.5% | 50.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 13,649,057 | 0.4% | 50.7% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 13,276,948 | 0.4% | 51.1% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 13,166,205 | 0.4% | 51.5% |
| RETURN_VALUE INTERPRETER_EXIT | 12,905,184 | 0.4% | 52.0% |
| CALL_LEN LOAD_FAST | 12,653,294 | 0.4% | 52.4% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 12,633,606 | 0.4% | 52.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 12,603,887 | 0.4% | 53.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 12,467,878 | 0.4% | 53.6% |
| NOP LOAD_FAST | 12,453,172 | 0.4% | 54.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 12,324,018 | 0.4% | 54.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 12,260,220 | 0.4% | 54.8% |
| LOAD_FAST BINARY_OP_SUBTRACT_INT | 11,967,450 | 0.4% | 55.2% |
| LOAD_GLOBAL_BUILTIN BUILD_TUPLE | 11,792,824 | 0.4% | 55.6% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 11,716,479 | 0.4% | 56.0% |
| STORE_FAST NOP | 11,657,272 | 0.4% | 56.4% |
| BINARY_OP_SUBTRACT_INT LOAD_FAST | 11,615,006 | 0.4% | 56.8% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_SUBTRACT_INT | 11,609,606 | 0.4% | 57.2% |
| LOAD_FAST LOAD_ATTR | 11,434,401 | 0.4% | 57.5% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 11,182,208 | 0.4% | 57.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 11,017,143 | 0.4% | 58.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 10,877,160 | 0.4% | 58.6% |
| LOAD_FAST COPY | 10,783,901 | 0.4% | 59.0% |
| LOAD_CONST LOAD_CONST | 10,769,745 | 0.4% | 59.3% |
| LOAD_FAST SWAP | 10,576,846 | 0.3% | 59.7% |
| COMPARE_OP POP_JUMP_IF_FALSE | 10,510,414 | 0.3% | 60.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 10,325,335 | 0.3% | 60.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_LAZY_DICT | 10,300,958 | 0.3% | 60.7% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 10,199,371 | 0.3% | 61.0% |
| LOAD_FAST BINARY_OP_ADD_INT | 10,028,679 | 0.3% | 61.4% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 9,998,511 | 0.3% | 61.7% |
| LOAD_GLOBAL_MODULE STORE_FAST | 9,976,752 | 0.3% | 62.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 9,888,837 | 0.3% | 62.4% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 9,858,590 | 0.3% | 62.7% |
| BINARY_OP_ADD_INT SWAP | 9,657,236 | 0.3% | 63.0% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 9,588,223 | 0.3% | 63.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 9,540,470 | 0.3% | 63.6% |
| POP_TOP RETURN_CONST | 8,630,656 | 0.3% | 63.9% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 8,576,182 | 0.3% | 64.2% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 8,576,182 | 0.3% | 64.5% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 8,545,760 | 0.3% | 64.8% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 8,476,673 | 0.3% | 65.0% |
| LOAD_FAST CALL | 8,282,248 | 0.3% | 65.3% |
| LOAD_FAST BUILD_TUPLE | 8,204,729 | 0.3% | 65.6% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 8,074,168 | 0.3% | 65.9% |
| STORE_FAST_STORE_FAST STORE_FAST | 8,065,407 | 0.3% | 66.1% |
| BUILD_TUPLE RETURN_VALUE | 8,016,798 | 0.3% | 66.4% |
| RETURN_VALUE POP_TOP | 7,937,576 | 0.3% | 66.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 7,889,962 | 0.3% | 66.9% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS STORE_FAST | 7,759,087 | 0.3% | 67.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 7,737,291 | 0.3% | 67.4% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 7,732,177 | 0.3% | 67.7% |
| MAKE_CELL RESUME_CHECK | 7,702,963 | 0.3% | 67.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 7,599,042 | 0.3% | 68.2% |
| RESUME_CHECK LOAD_CONST | 7,571,688 | 0.2% | 68.4% |
| LOAD_ATTR_INSTANCE_VALUE CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 7,512,524 | 0.2% | 68.7% |
| BINARY_SUBSCR STORE_FAST | 7,208,820 | 0.2% | 68.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,132,300 | 89.3% |
| LOAD_CONST | 293,268 | 6.3% |
| LOAD_FAST | 199,245 | 4.3% |
| LOAD_ATTR_INSTANCE_VALUE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,137,809 | 89.5% |
| GET_ITER | 67,681 | 1.5% |
| CALL_BUILTIN_CLASS | 66,660 | 1.4% |
| CALL_PY_WITH_DEFAULTS | 66,000 | 1.4% |
| CALL_METHOD_DESCRIPTOR_O | 66,000 | 1.4% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 38,116 | 99.7% |
| LOAD_FAST | 120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,116 | 99.7% |
| LOAD_CONST | 120 | 0.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 17,300,180 | 90.4% |
| COPY_FREE_VARS | 1,043,862 | 5.5% |
| POP_TOP | 440,168 | 2.3% |
| MAKE_CELL | 199,680 | 1.0% |
| RETURN_GENERATOR | 101,847 | 0.5% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,500 | 93.3% |
| LOAD_ATTR_WITH_HINT | 360 | 4.5% |
| CALL | 120 | 1.5% |
| CALL_KW | 60 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 8,040 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,182,951 | 71.0% |
| LOAD_GLOBAL_MODULE | 139,221 | 8.4% |
| LOAD_ATTR_WITH_HINT | 132,120 | 7.9% |
| LOAD_FAST | 132,060 | 7.9% |
| ENTER_EXECUTOR | 66,240 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,663,015 | 99.8% |
| STORE_FAST | 3,604 | 0.2% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,320 | 71.0% |
| BINARY_OP_ADD_UNICODE | 420 | 22.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 120 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,320 | 71.0% |
| JUMP_BACKWARD | 420 | 22.6% |
| LOAD_FAST | 120 | 6.5% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,076,781 | 86.6% |
| LOAD_FAST | 644,563 | 7.9% |
| COPY | 265,840 | 3.3% |
| LOAD_CONST | 183,309 | 2.2% |
| BINARY_SUBSCR | 3,112 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,208,820 | 88.2% |
| RETURN_VALUE | 258,060 | 3.2% |
| LOAD_CONST | 199,320 | 2.4% |
| LOAD_FAST | 132,010 | 1.6% |
| LOAD_ATTR_METHOD_NO_DICT | 122,740 | 1.5% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 515,577 | 86.8% |
| LOAD_ATTR_MODULE | 74,290 | 12.5% |
| BUILD_TUPLE | 3,660 | 0.6% |
| LOAD_GLOBAL_MODULE | 280 | 0.0% |
| LOAD_GLOBAL | 37 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 593,849 | 100.0% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 440 | 73.3% |
| JUMP_BACKWARD | 160 | 26.7% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 722,225 | 67.8% |
| LOAD_FAST_LOAD_FAST | 199,332 | 18.7% |
| BUILD_SLICE | 77,036 | 7.2% |
| LOAD_ATTR_SLOT | 66,060 | 6.2% |
| LOAD_DEREF | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 340,700 | 34.1% |
| PUSH_EXC_INFO | 264,000 | 26.4% |
| RETURN_CONST | 193,764 | 19.4% |
| LOAD_FAST_LOAD_FAST | 66,504 | 6.7% |
| LOAD_CONST | 66,365 | 6.6% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,087 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 38.9% |
| STORE_FAST | 743 | 24.1% |
| LOAD_CONST | 660 | 21.4% |
| SWAP | 240 | 7.8% |
| RETURN_CONST | 124 | 4.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 233,362 | 52.6% |
| SEND | 158,383 | 35.7% |
| RETURN_CONST | 51,284 | 11.6% |
| JUMP_BACKWARD | 160 | 0.0% |
| SEND_GEN | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 265,100 | 59.8% |
| POP_TOP | 103,907 | 23.4% |
| UNPACK_SEQUENCE_TUPLE | 66,240 | 14.9% |
| SWAP | 7,500 | 1.7% |
| LOAD_DEREF | 180 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 220,005 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 220,005 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 286,690 | 68.5% |
| LOAD_FAST | 121,514 | 29.0% |
| CONVERT_VALUE | 7,494 | 1.8% |
| LOAD_GLOBAL_MODULE | 2,400 | 0.6% |
| CALL_LEN | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 329,830 | 78.8% |
| LOAD_CONST | 49,374 | 11.8% |
| LOAD_FAST | 39,316 | 9.4% |


</details>

### FORMAT_WITH_SPEC

<details>
<summary> Successors and predecessors for FORMAT_WITH_SPEC </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 3,565,370 | 27.4% |
| LOAD_FAST | 3,439,879 | 26.5% |
| CALL_BUILTIN_CLASS | 2,091,919 | 16.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,899,900 | 14.6% |
| LOAD_ATTR_SLOT | 1,087,943 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 4,244,627 | 32.7% |
| FOR_ITER | 4,172,884 | 32.1% |
| FOR_ITER_RANGE | 1,724,943 | 13.3% |
| FOR_ITER_LIST | 1,560,967 | 12.0% |
| LOAD_FAST_AND_CLEAR | 1,046,685 | 8.1% |


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,320 | 99.8% |
| RETURN_GENERATOR | 2 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,322 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 12,905,184 | 68.2% |
| RETURN_CONST | 5,064,109 | 26.8% |
| YIELD_VALUE | 851,830 | 4.5% |
| RETURN_GENERATOR | 102,027 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,159,175 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 949,130 | 81.9% |
| STORE_DEREF | 66,011 | 5.7% |
| LOAD_FAST | 63,180 | 5.5% |
| CALL | 38,778 | 3.3% |
| LOAD_GLOBAL_BUILTIN | 38,756 | 3.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,657,272 | 58.7% |
| RESUME_CHECK | 4,501,240 | 22.7% |
| POP_JUMP_IF_FALSE | 1,221,124 | 6.1% |
| STORE_ATTR_INSTANCE_VALUE | 510,494 | 2.6% |
| POP_JUMP_IF_TRUE | 454,575 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,453,172 | 62.7% |
| LOAD_FAST_LOAD_FAST | 3,915,911 | 19.7% |
| LOAD_GLOBAL_MODULE | 1,720,325 | 8.7% |
| LOAD_CONST | 481,371 | 2.4% |
| LOAD_GLOBAL_BUILTIN | 382,634 | 1.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 429,143 | 61.9% |
| COPY | 134,381 | 19.4% |
| STORE_FAST | 113,098 | 16.3% |
| STORE_SUBSCR_DICT | 11,147 | 1.6% |
| SWAP | 4,827 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 351,693 | 50.7% |
| RERAISE | 134,381 | 19.4% |
| EXTENDED_ARG | 105,075 | 15.1% |
| DELETE_FAST | 38,276 | 5.5% |
| LOAD_CONST | 37,932 | 5.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 25,624,422 | 42.5% |
| CALL_METHOD_DESCRIPTOR_O | 9,858,590 | 16.3% |
| RETURN_VALUE | 7,937,576 | 13.2% |
| CALL | 4,009,880 | 6.6% |
| SWAP | 3,568,368 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,390,613 | 48.7% |
| RETURN_CONST | 8,630,656 | 14.3% |
| RETURN_VALUE | 4,228,748 | 7.0% |
| ENTER_EXECUTOR | 4,028,853 | 6.7% |
| JUMP_BACKWARD | 3,433,240 | 5.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 264,000 | 38.1% |
| BINARY_SUBSCR_DICT | 158,901 | 22.9% |
| CALL | 78,177 | 11.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 74,341 | 10.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 66,006 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 484,333 | 69.8% |
| WITH_EXCEPT_START | 133,803 | 19.3% |
| LOAD_GLOBAL_MODULE | 75,185 | 10.8% |
| LOAD_GLOBAL | 284 | 0.0% |
| DELETE_FAST | 58 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,761,258 | 66.0% |
| LOAD_ATTR_MODULE | 13,649,057 | 25.9% |
| LOAD_ATTR | 3,194,059 | 6.1% |
| LOAD_DEREF | 790,677 | 1.5% |
| RETURN_VALUE | 197,462 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,050,302 | 74.2% |
| LOAD_CONST | 6,818,841 | 12.9% |
| LOAD_FAST_LOAD_FAST | 3,755,255 | 7.1% |
| CALL | 1,961,955 | 3.7% |
| CALL_BUILTIN_CLASS | 328,440 | 0.6% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 208,743 | 28.6% |
| CALL_PY_EXACT_ARGS | 152,476 | 20.9% |
| CALL_KW | 106,398 | 14.6% |
| CACHE | 101,847 | 14.0% |
| CALL_PY_WITH_DEFAULTS | 79,478 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 260,503 | 35.7% |
| CALL_TUPLE_1 | 132,000 | 18.1% |
| INTERPRETER_EXIT | 102,027 | 14.0% |
| CALL_BUILTIN_O | 75,883 | 10.4% |
| CALL | 61,002 | 8.4% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,693,544 | 28.2% |
| BUILD_TUPLE | 8,016,798 | 12.1% |
| CALL_METHOD_DESCRIPTOR_O | 6,493,901 | 9.8% |
| RETURN_VALUE | 5,877,643 | 8.9% |
| POP_TOP | 4,228,748 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,742,938 | 28.3% |
| INTERPRETER_EXIT | 12,905,184 | 19.5% |
| POP_TOP | 7,937,576 | 12.0% |
| UNPACK_SEQUENCE_TUPLE | 6,040,242 | 9.1% |
| RETURN_VALUE | 5,877,643 | 8.9% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 265,840 | 66.4% |
| LOAD_FAST | 66,485 | 16.6% |
| LOAD_ATTR_INSTANCE_VALUE | 66,080 | 16.5% |
| LOAD_CONST | 960 | 0.2% |
| LOAD_ATTR_SLOT | 582 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200,022 | 49.9% |
| LOAD_CONST | 66,360 | 16.6% |
| RETURN_CONST | 66,305 | 16.6% |
| LOAD_GLOBAL_MODULE | 66,120 | 16.5% |
| STORE_SUBSCR_DICT | 1,120 | 0.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,210,202 | 49.3% |
| LOAD_ATTR_SLOT | 1,135,540 | 17.4% |
| LOAD_ATTR_INSTANCE_VALUE | 841,179 | 12.9% |
| RETURN_VALUE | 720,613 | 11.1% |
| COPY | 320,077 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,477,250 | 68.7% |
| POP_JUMP_IF_TRUE | 1,949,971 | 29.9% |
| EXTENDED_ARG | 78,370 | 1.2% |
| TO_BOOL | 5,734 | 0.1% |
| TO_BOOL_BOOL | 2,376 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 39,076 | 50.2% |
| BINARY_OP | 38,836 | 49.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 77,912 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 66,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,000 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 720 | 92.1% |
| TO_BOOL_INT | 60 | 7.7% |
| TO_BOOL | 2 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 660 | 84.4% |
| STORE_FAST | 62 | 7.9% |
| COPY | 60 | 7.7% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 133,803 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 133,003 | 99.4% |
| TO_BOOL_BOOL | 780 | 0.6% |
| TO_BOOL | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 26,327,340 | 90.3% |
| LOAD_FAST | 603,896 | 2.1% |
| LOAD_FAST_LOAD_FAST | 537,472 | 1.8% |
| LOAD_GLOBAL_MODULE | 328,448 | 1.1% |
| LOAD_ATTR_WITH_HINT | 205,042 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 22,351,632 | 76.6% |
| STORE_FAST | 5,004,281 | 17.2% |
| TO_BOOL_INT | 527,516 | 1.8% |
| LOAD_FAST_LOAD_FAST | 197,350 | 0.7% |
| COPY | 175,302 | 0.6% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 891,846 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 328,787 | 36.9% |
| RETURN_VALUE | 145,307 | 16.3% |
| CALL_LIST_APPEND | 132,780 | 14.9% |
| LOAD_FAST | 105,376 | 11.8% |
| CALL_PY_EXACT_ARGS | 67,560 | 7.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,504,398 | 59.9% |
| LOAD_ATTR_SLOT | 1,125,119 | 12.2% |
| RESUME_CHECK | 822,976 | 8.9% |
| STORE_FAST | 370,888 | 4.0% |
| SWAP | 264,825 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,728,426 | 73.2% |
| STORE_FAST | 983,348 | 10.7% |
| RETURN_VALUE | 483,146 | 5.3% |
| BUILD_TUPLE | 384,160 | 4.2% |
| SWAP | 302,036 | 3.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 4,528,462 | 37.8% |
| STORE_FAST | 1,940,063 | 16.2% |
| LOAD_FAST | 1,368,664 | 11.4% |
| POP_JUMP_IF_NONE | 728,700 | 6.1% |
| SWAP | 588,960 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,740,844 | 56.3% |
| STORE_FAST | 3,788,262 | 31.7% |
| SWAP | 588,960 | 4.9% |
| LOAD_GLOBAL_MODULE | 325,120 | 2.7% |
| BUILD_LIST | 186,000 | 1.6% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 192,900 | 42.8% |
| LOAD_GLOBAL_MODULE | 132,251 | 29.3% |
| LOAD_ATTR | 66,000 | 14.6% |
| LOAD_CONST | 60,000 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 192,900 | 42.8% |
| CONTAINS_OP | 132,251 | 29.3% |
| LOAD_CONST | 66,000 | 14.6% |
| BINARY_OP | 60,000 | 13.3% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,352 | 99.0% |
| LOAD_CONST | 744 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 77,036 | 99.9% |
| BINARY_SUBSCR | 60 | 0.1% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 329,830 | 88.8% |
| LOAD_CONST | 41,744 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 154,692 | 41.6% |
| LOAD_CONST | 66,000 | 17.8% |
| BUILD_MAP | 66,000 | 17.8% |
| LOAD_FAST | 39,196 | 10.5% |
| LOAD_FAST_LOAD_FAST | 38,236 | 10.3% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 11,792,824 | 45.5% |
| LOAD_FAST | 8,204,729 | 31.7% |
| LOAD_FAST_LOAD_FAST | 1,814,712 | 7.0% |
| LOAD_GLOBAL_MODULE | 1,551,011 | 6.0% |
| CALL | 1,072,605 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,016,798 | 31.0% |
| CALL_ISINSTANCE | 6,903,860 | 26.7% |
| STORE_FAST | 6,304,924 | 24.3% |
| CALL_METHOD_DESCRIPTOR_O | 1,230,807 | 4.8% |
| LOAD_CONST | 1,214,335 | 4.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,282,248 | 38.7% |
| LOAD_GLOBAL_MODULE | 2,774,307 | 13.0% |
| LOAD_CONST | 2,054,536 | 9.6% |
| PUSH_NULL | 1,961,955 | 9.2% |
| LOAD_FAST_LOAD_FAST | 1,910,481 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,225,635 | 19.7% |
| POP_TOP | 4,009,880 | 18.7% |
| STORE_FAST | 3,748,558 | 17.5% |
| RESUME_CHECK | 2,928,171 | 13.7% |
| LOAD_FAST | 1,087,054 | 5.1% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 6,925,820 | 75.1% |
| CALL_INTRINSIC_1 | 1,401,762 | 15.2% |
| LOAD_FAST | 734,392 | 8.0% |
| LOAD_ATTR_INSTANCE_VALUE | 66,000 | 0.7% |
| BUILD_MAP | 55,048 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,520,190 | 49.0% |
| POP_TOP | 2,347,637 | 25.4% |
| RETURN_VALUE | 863,414 | 9.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 462,000 | 5.0% |
| UNPACK_SEQUENCE_TUPLE | 324,000 | 3.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 6,380,852 | 99.9% |
| CACHE | 2,968 | 0.0% |
| RERAISE | 1,000 | 0.0% |
| RAISE_VARARGS | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 4,528,462 | 70.9% |
| CALL_FUNCTION_EX | 1,401,762 | 22.0% |
| LOAD_CONST | 450,628 | 7.1% |
| RERAISE | 3,988 | 0.1% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,625,244 | 97.2% |
| ENTER_EXECUTOR | 191,940 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,006,644 | 88.1% |
| MAKE_CELL | 358,771 | 5.3% |
| STORE_FAST | 129,636 | 1.9% |
| RETURN_GENERATOR | 106,398 | 1.6% |
| RETURN_VALUE | 75,275 | 1.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,348,460 | 45.8% |
| LOAD_CONST | 5,293,205 | 45.4% |
| COPY | 533,854 | 4.6% |
| LOAD_FAST | 137,260 | 1.2% |
| LOAD_ATTR | 134,710 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,510,414 | 90.1% |
| EXTENDED_ARG | 1,148,451 | 9.8% |
| COMPARE_OP | 4,851 | 0.0% |
| COMPARE_OP_INT | 3,190 | 0.0% |
| POP_JUMP_IF_TRUE | 2,139 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,366,606 | 30.0% |
| LOAD_ATTR_INSTANCE_VALUE | 2,044,940 | 25.9% |
| LOAD_ATTR_WITH_HINT | 1,177,112 | 14.9% |
| LOAD_GLOBAL_MODULE | 546,357 | 6.9% |
| BUILD_TUPLE | 418,020 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,830,154 | 73.8% |
| RETURN_VALUE | 859,380 | 10.9% |
| POP_JUMP_IF_TRUE | 685,320 | 8.7% |
| COPY | 391,742 | 5.0% |
| SWAP | 132,262 | 1.7% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 5,328 | 71.1% |
| BINARY_SLICE | 1,200 | 16.0% |
| LOAD_FAST | 964 | 12.9% |
| LOAD_ATTR | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 7,494 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,783,901 | 48.4% |
| SWAP | 6,873,338 | 30.9% |
| COPY | 1,086,183 | 4.9% |
| CALL_BUILTIN_FAST | 524,186 | 2.4% |
| LOAD_ATTR_SLOT | 456,540 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,576,182 | 38.5% |
| COMPARE_OP_INT | 6,208,312 | 27.9% |
| TO_BOOL_BOOL | 1,464,741 | 6.6% |
| COPY | 1,086,183 | 4.9% |
| LOAD_ATTR_WITH_HINT | 1,056,148 | 4.7% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,417,874 | 45.3% |
| CACHE | 1,043,862 | 33.3% |
| CALL | 336,252 | 10.7% |
| BINARY_SUBSCR_GETITEM | 198,000 | 6.3% |
| ENTER_EXECUTOR | 65,460 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,920,532 | 93.3% |
| RETURN_GENERATOR | 208,743 | 6.7% |
| MAKE_CELL | 1,320 | 0.0% |
| RESUME | 7 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,989 | 97.1% |
| LOAD_GLOBAL_MODULE | 240 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,646 | 44.3% |
| PUSH_EXC_INFO | 1,800 | 21.9% |
| NOP | 1,643 | 20.0% |
| RETURN_CONST | 1,020 | 12.4% |
| LOAD_GLOBAL_MODULE | 120 | 1.5% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 76,798 | 25.6% |
| POP_TOP | 66,262 | 22.1% |
| STORE_FAST | 41,839 | 13.9% |
| NOP | 38,456 | 12.8% |
| STORE_ATTR_INSTANCE_VALUE | 38,322 | 12.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 76,798 | 25.6% |
| RETURN_CONST | 76,732 | 25.6% |
| JUMP_FORWARD | 69,927 | 23.3% |
| LOAD_FAST | 38,333 | 12.8% |
| ENTER_EXECUTOR | 37,232 | 12.4% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,456,141 | 93.2% |
| RETURN_VALUE | 325,200 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 66,671 | 1.0% |
| LOAD_DEREF | 38,247 | 0.6% |
| LOAD_GLOBAL_MODULE | 38,236 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 6,925,820 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 38,236 | 96.5% |
| BUILD_MAP | 540 | 1.4% |
| RETURN_VALUE | 480 | 1.2% |
| MAP_ADD | 180 | 0.5% |
| BUILD_CONST_KEY_MAP | 120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,776 | 97.9% |
| STORE_FAST | 540 | 1.4% |
| LOAD_DEREF | 120 | 0.3% |
| RETURN_VALUE | 60 | 0.2% |
| LOAD_CONST | 60 | 0.2% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,028,853 | 40.7% |
| STORE_SUBSCR_DICT | 2,646,802 | 26.8% |
| CALL_LIST_APPEND | 1,050,188 | 10.6% |
| POP_JUMP_IF_FALSE | 1,028,066 | 10.4% |
| EXTENDED_ARG | 314,410 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,489,778 | 25.2% |
| LOAD_FAST | 1,316,461 | 13.3% |
| RESUME_CHECK | 1,173,215 | 11.9% |
| LOAD_DEREF | 1,072,317 | 10.8% |
| RETURN_CONST | 866,950 | 8.8% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,122,624 | 35.8% |
| COMPARE_OP_INT | 5,813,864 | 29.2% |
| STORE_FAST | 4,620,562 | 23.2% |
| COMPARE_OP | 1,148,451 | 5.8% |
| STORE_ATTR_WITH_HINT | 324,000 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,361,123 | 72.2% |
| JUMP_FORWARD | 5,144,684 | 25.9% |
| ENTER_EXECUTOR | 314,410 | 1.6% |
| POP_JUMP_IF_NOT_NONE | 66,000 | 0.3% |
| LOAD_ATTR | 4,800 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,091,734 | 53.1% |
| GET_ITER | 4,172,884 | 36.4% |
| SWAP | 904,245 | 7.9% |
| LOAD_FAST | 166,136 | 1.4% |
| ENTER_EXECUTOR | 125,340 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,846,676 | 33.5% |
| STORE_FAST | 1,879,386 | 16.4% |
| LOAD_FAST | 1,733,602 | 15.1% |
| RETURN_CONST | 1,719,516 | 15.0% |
| SWAP | 837,300 | 7.3% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 260,503 | 58.9% |
| RETURN_VALUE | 150,503 | 34.0% |
| LOAD_FAST | 14,941 | 3.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 8,040 | 1.8% |
| BEFORE_ASYNC_WITH | 8,040 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 442,447 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 152,787 | 99.6% |
| STORE_FAST | 660 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 153,327 | 99.9% |
| PUSH_EXC_INFO | 120 | 0.1% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 152,967 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 152,787 | 99.9% |
| STORE_FAST | 180 | 0.1% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,625,968 | 48.6% |
| LOAD_GLOBAL_BUILTIN | 1,998,280 | 26.8% |
| LOAD_GLOBAL_MODULE | 877,653 | 11.8% |
| LOAD_CONST | 351,962 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 194,520 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,859,488 | 78.6% |
| POP_JUMP_IF_TRUE | 889,257 | 11.9% |
| COPY | 271,830 | 3.6% |
| RETURN_VALUE | 238,009 | 3.2% |
| EXTENDED_ARG | 198,000 | 2.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,433,240 | 55.6% |
| MAP_ADD | 645,944 | 10.5% |
| STORE_SUBSCR_DICT | 644,700 | 10.4% |
| POP_JUMP_IF_TRUE | 535,450 | 8.7% |
| LIST_APPEND | 203,359 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 6,091,734 | 98.6% |
| FOR_ITER_GEN | 71,499 | 1.2% |
| FOR_ITER_LIST | 4,864 | 0.1% |
| LOAD_FAST | 3,860 | 0.1% |
| FOR_ITER_TUPLE | 2,200 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 493,308 | 100.0% |
| RESUME | 17 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 246,997 | 50.1% |
| SEND | 246,328 | 49.9% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 5,144,684 | 51.1% |
| POP_JUMP_IF_FALSE | 2,111,537 | 21.0% |
| STORE_FAST | 1,556,420 | 15.4% |
| POP_TOP | 811,035 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 81,396 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,837,106 | 48.0% |
| LOAD_FAST | 2,850,447 | 28.3% |
| LOAD_GLOBAL_MODULE | 1,583,350 | 15.7% |
| LOAD_GLOBAL_BUILTIN | 351,360 | 3.5% |
| NOP | 196,860 | 2.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 126,000 | 30.4% |
| RETURN_VALUE | 104,236 | 25.1% |
| BINARY_SUBSCR_DICT | 66,120 | 15.9% |
| BINARY_OP_ADD_UNICODE | 66,000 | 15.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 33,600 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 211,643 | 51.0% |
| JUMP_BACKWARD | 203,359 | 49.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,330,814 | 82.6% |
| LOAD_ATTR_SLOT | 1,125,119 | 17.4% |
| BINARY_SLICE | 1,320 | 0.0% |
| LOAD_DEREF | 71 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 6,380,852 | 98.8% |
| STORE_FAST | 76,472 | 1.2% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,434,401 | 69.7% |
| LOAD_ATTR_SLOT | 1,126,099 | 6.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,097,812 | 6.7% |
| LOAD_GLOBAL_MODULE | 973,463 | 5.9% |
| LOAD_DEREF | 879,010 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,565,370 | 21.7% |
| PUSH_NULL | 3,194,059 | 19.5% |
| LOAD_FAST | 2,905,485 | 17.7% |
| LOAD_FAST_LOAD_FAST | 1,463,197 | 8.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,008,521 | 6.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,449,773 | 33.8% |
| BINARY_OP | 22,351,632 | 10.7% |
| POP_JUMP_IF_FALSE | 17,891,420 | 8.6% |
| STORE_FAST | 14,086,983 | 6.8% |
| LOAD_CONST | 10,769,745 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 62,010,032 | 29.7% |
| LOAD_FAST | 31,019,807 | 14.9% |
| BINARY_OP | 26,327,340 | 12.6% |
| STORE_FAST | 22,206,679 | 10.6% |
| LOAD_CONST | 10,769,745 | 5.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,021,847 | 22.8% |
| STORE_FAST | 6,334,366 | 20.6% |
| POP_JUMP_IF_FALSE | 5,100,929 | 16.6% |
| LOAD_CONST | 3,841,436 | 12.5% |
| POP_JUMP_IF_NONE | 1,329,312 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 13,661,971 | 44.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,998,511 | 32.5% |
| LOAD_FAST | 929,742 | 3.0% |
| LOAD_ATTR | 879,010 | 2.9% |
| PUSH_NULL | 790,677 | 2.6% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 137,041,414 | 22.2% |
| STORE_FAST | 91,752,148 | 14.9% |
| LOAD_GLOBAL_BUILTIN | 45,569,739 | 7.4% |
| RESUME_CHECK | 45,462,155 | 7.4% |
| PUSH_NULL | 39,050,302 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 107,946,011 | 17.5% |
| LOAD_CONST | 70,449,773 | 11.4% |
| LOAD_GLOBAL_MODULE | 42,888,024 | 7.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 38,301,047 | 6.2% |
| LOAD_GLOBAL_BUILTIN | 36,067,492 | 5.9% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,046,685 | 64.0% |
| LOAD_FAST_AND_CLEAR | 588,000 | 36.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,046,685 | 64.0% |
| LOAD_FAST_AND_CLEAR | 588,000 | 36.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 66,000 | 34.3% |
| POP_JUMP_IF_FALSE | 66,000 | 34.3% |
| LOAD_ATTR_METHOD_NO_DICT | 42,150 | 21.9% |
| POP_TOP | 5,560 | 2.9% |
| LOAD_FAST_CHECK | 5,166 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 132,960 | 69.1% |
| CALL_METHOD_DESCRIPTOR_O | 42,030 | 21.8% |
| LOAD_FAST_CHECK | 5,166 | 2.7% |
| POP_JUMP_IF_NOT_NONE | 4,800 | 2.5% |
| LOAD_CONST | 4,440 | 2.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,182,208 | 16.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,877,160 | 16.3% |
| JUMP_FORWARD | 4,837,106 | 7.3% |
| LOAD_ATTR_INSTANCE_VALUE | 4,562,964 | 6.9% |
| NOP | 3,915,911 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,237,909 | 21.4% |
| LOAD_CONST | 10,199,371 | 15.3% |
| LOAD_ATTR_INSTANCE_VALUE | 8,545,760 | 12.8% |
| STORE_ATTR_SLOT | 5,361,067 | 8.1% |
| BINARY_SUBSCR_DICT | 3,747,108 | 5.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 2,020 | 11.5% |
| STORE_FAST | 1,865 | 10.7% |
| RESUME_CHECK | 1,592 | 9.1% |
| POP_TOP | 1,580 | 9.0% |
| LOAD_GLOBAL_MODULE | 1,540 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,453 | 71.1% |
| LOAD_GLOBAL_BUILTIN | 4,609 | 26.3% |
| LOAD_ATTR | 88 | 0.5% |
| LOAD_FAST | 82 | 0.5% |
| LOAD_GLOBAL | 51 | 0.3% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 75.0% |
| EXTENDED_ARG | 60 | 15.0% |
| LOAD_DEREF | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 300 | 75.0% |
| LOAD_SUPER_ATTR_ATTR | 100 | 25.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,101,875 | 42.5% |
| ENTER_EXECUTOR | 2,489,778 | 25.8% |
| MAKE_CELL | 1,863,075 | 19.3% |
| CALL_PY_WITH_DEFAULTS | 587,835 | 6.1% |
| CALL_KW | 358,771 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,702,963 | 79.9% |
| MAKE_CELL | 1,863,075 | 19.3% |
| RETURN_GENERATOR | 77,564 | 0.8% |
| RESUME | 20 | 0.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 258,082 | 39.5% |
| STORE_FAST | 126,120 | 19.3% |
| RETURN_VALUE | 66,180 | 10.1% |
| BINARY_OP | 66,006 | 10.1% |
| CALL_KW | 66,000 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 645,944 | 98.9% |
| LOAD_CONST | 6,840 | 1.0% |
| DICT_UPDATE | 180 | 0.0% |
| BUILD_MAP | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 100,628,281 | 48.9% |
| TO_BOOL_BOOL | 53,372,752 | 25.9% |
| EXTENDED_ARG | 14,361,123 | 7.0% |
| COMPARE_OP | 10,510,414 | 5.1% |
| IS_OP | 5,859,488 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 137,041,414 | 66.6% |
| LOAD_CONST | 17,891,420 | 8.7% |
| RETURN_CONST | 15,444,357 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 12,260,220 | 6.0% |
| LOAD_GLOBAL_MODULE | 7,889,962 | 3.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,128,064 | 53.4% |
| LOAD_ATTR_INSTANCE_VALUE | 3,193,946 | 41.3% |
| LOAD_DEREF | 264,553 | 3.4% |
| LOAD_ATTR_WITH_HINT | 74,161 | 1.0% |
| LOAD_ATTR_SLOT | 66,660 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,105,019 | 53.1% |
| LOAD_DEREF | 1,329,312 | 17.2% |
| BUILD_MAP | 728,700 | 9.4% |
| RETURN_CONST | 551,314 | 7.1% |
| LOAD_GLOBAL_MODULE | 265,201 | 3.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,888,837 | 88.6% |
| LOAD_ATTR_INSTANCE_VALUE | 775,149 | 6.9% |
| LOAD_DEREF | 338,230 | 3.0% |
| LOAD_GLOBAL_MODULE | 68,591 | 0.6% |
| EXTENDED_ARG | 66,000 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,732,177 | 69.3% |
| LOAD_FAST_LOAD_FAST | 1,043,150 | 9.3% |
| LOAD_GLOBAL_MODULE | 973,587 | 8.7% |
| LOAD_GLOBAL_BUILTIN | 508,159 | 4.6% |
| RETURN_CONST | 316,010 | 2.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,578,799 | 39.6% |
| TO_BOOL | 1,949,971 | 16.9% |
| COMPARE_OP_INT | 1,386,223 | 12.0% |
| TO_BOOL_INT | 941,128 | 8.1% |
| IS_OP | 889,257 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,993,660 | 51.8% |
| LOAD_CONST | 888,810 | 7.7% |
| LOAD_FAST_LOAD_FAST | 667,767 | 5.8% |
| POP_TOP | 560,245 | 4.8% |
| JUMP_BACKWARD | 535,450 | 4.6% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,220 | 49.5% |
| CALL_KW | 1,020 | 22.8% |
| LOAD_GLOBAL_MODULE | 723 | 16.1% |
| LOAD_CONST | 300 | 6.7% |
| LOAD_FAST | 220 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,843 | 77.3% |
| COPY | 300 | 12.6% |
| LOAD_CONST | 220 | 9.2% |
| CALL_INTRINSIC_1 | 20 | 0.8% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 134,381 | 49.3% |
| POP_JUMP_IF_TRUE | 133,023 | 48.8% |
| CALL_INTRINSIC_1 | 3,988 | 1.5% |
| POP_JUMP_IF_FALSE | 780 | 0.3% |
| DELETE_FAST | 278 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 134,081 | 98.2% |
| PUSH_EXC_INFO | 1,401 | 1.0% |
| CALL_INTRINSIC_1 | 1,000 | 0.7% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,444,357 | 46.9% |
| POP_TOP | 8,630,656 | 26.2% |
| STORE_ATTR_SLOT | 1,890,268 | 5.7% |
| FOR_ITER | 1,719,516 | 5.2% |
| STORE_FAST | 1,304,944 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 25,624,422 | 77.8% |
| INTERPRETER_EXIT | 5,064,109 | 15.4% |
| RETURN_VALUE | 1,005,255 | 3.1% |
| TO_BOOL_BOOL | 481,522 | 1.5% |
| EXIT_INIT_CHECK | 220,005 | 0.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 246,328 | 60.7% |
| LOAD_CONST | 158,950 | 39.1% |
| SEND | 746 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 246,541 | 60.7% |
| END_SEND | 158,383 | 39.0% |
| SEND | 746 | 0.2% |
| SEND_GEN | 347 | 0.1% |
| POP_TOP | 7 | 0.0% |


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 60,000 | 45.0% |
| RETURN_VALUE | 60,000 | 45.0% |
| RETURN_GENERATOR | 6,000 | 4.5% |
| LOAD_FAST | 6,000 | 4.5% |
| JUMP_FORWARD | 1,320 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 121,320 | 91.0% |
| ENTER_EXECUTOR | 12,000 | 9.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 949,130 | 82.8% |
| SET_FUNCTION_ATTRIBUTE | 197,190 | 17.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 453,897 | 39.6% |
| CALL | 238,719 | 20.8% |
| SET_FUNCTION_ATTRIBUTE | 197,190 | 17.2% |
| LOAD_FAST | 141,003 | 12.3% |
| STORE_DEREF | 76,255 | 6.7% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 66,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 66,000 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 533,237 | 70.6% |
| LOAD_GLOBAL_MODULE | 198,900 | 26.3% |
| LOAD_FAST_LOAD_FAST | 10,249 | 1.4% |
| LOAD_DEREF | 7,600 | 1.0% |
| STORE_ATTR | 4,140 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 334,897 | 44.3% |
| LOAD_GLOBAL_MODULE | 134,476 | 17.8% |
| LOAD_GLOBAL_BUILTIN | 132,782 | 17.6% |
| LOAD_CONST | 68,229 | 9.0% |
| LOAD_FAST_LOAD_FAST | 66,499 | 8.8% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 153,124 | 22.7% |
| LOAD_CONST | 105,247 | 15.6% |
| SET_FUNCTION_ATTRIBUTE | 76,255 | 11.3% |
| CALL_BUILTIN_CLASS | 67,140 | 10.0% |
| MAKE_FUNCTION | 66,011 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 209,353 | 31.1% |
| LOAD_CONST | 180,439 | 26.8% |
| LOAD_FAST | 163,267 | 24.2% |
| LOAD_DEREF | 45,211 | 6.7% |
| JUMP_FORWARD | 37,756 | 5.6% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 22,206,679 | 13.8% |
| RETURN_VALUE | 18,742,938 | 11.7% |
| BINARY_OP_SUBTRACT_INT | 11,716,479 | 7.3% |
| LOAD_GLOBAL_MODULE | 9,976,752 | 6.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,588,223 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 91,752,148 | 57.1% |
| LOAD_CONST | 14,086,983 | 8.8% |
| NOP | 11,657,272 | 7.2% |
| LOAD_FAST_LOAD_FAST | 11,182,208 | 7.0% |
| LOAD_GLOBAL_BUILTIN | 6,999,506 | 4.4% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 559,625 | 80.1% |
| COPY | 66,122 | 9.5% |
| SWAP | 38,051 | 5.4% |
| FOR_ITER_TUPLE | 33,600 | 4.8% |
| FOR_ITER_LIST | 840 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 306,000 | 43.8% |
| STORE_ATTR_SLOT | 66,000 | 9.5% |
| LOAD_GLOBAL_MODULE | 66,000 | 9.5% |
| LOAD_DEREF | 60,180 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 60,062 | 8.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 8,074,168 | 59.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 5,487,921 | 40.2% |
| UNPACK_EX | 66,000 | 0.5% |
| STORE_FAST_STORE_FAST | 37,864 | 0.3% |
| UNPACK_SEQUENCE_LIST | 901 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,065,407 | 59.0% |
| LOAD_FAST | 5,138,835 | 37.6% |
| LOAD_GLOBAL_MODULE | 145,332 | 1.1% |
| LOAD_GLOBAL_BUILTIN | 104,296 | 0.8% |
| LOAD_FAST_LOAD_FAST | 88,920 | 0.7% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 120 | 40.0% |
| BINARY_OP_ADD_INT | 120 | 40.0% |
| LOAD_FAST | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 40.0% |
| LOAD_CONST | 120 | 40.0% |
| LOAD_FAST | 60 | 20.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,576,846 | 40.0% |
| BINARY_OP_ADD_INT | 9,657,236 | 36.6% |
| SWAP | 1,086,183 | 4.1% |
| LOAD_FAST_AND_CLEAR | 1,046,685 | 4.0% |
| FOR_ITER | 837,300 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 8,576,182 | 32.5% |
| COPY | 6,873,338 | 26.0% |
| POP_TOP | 3,568,368 | 13.5% |
| SWAP | 1,086,183 | 4.1% |
| STORE_ATTR_WITH_HINT | 1,056,148 | 4.0% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 66,000 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,920 | 80.1% |
| RETURN_VALUE | 162 | 6.8% |
| FOR_ITER | 94 | 3.9% |
| UNPACK_SEQUENCE | 60 | 2.5% |
| YIELD_VALUE | 40 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,448 | 60.4% |
| STORE_FAST_STORE_FAST | 484 | 20.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 306 | 12.8% |
| UNPACK_SEQUENCE_TUPLE | 80 | 3.3% |
| UNPACK_SEQUENCE | 60 | 2.5% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 302,668 | 25.8% |
| YIELD_VALUE | 247,324 | 21.1% |
| SEND | 246,541 | 21.1% |
| LOAD_FAST | 76,832 | 6.6% |
| BUILD_TUPLE | 73,440 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 851,830 | 72.7% |
| YIELD_VALUE | 247,324 | 21.1% |
| STORE_FAST | 71,880 | 6.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 80 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 46 | 29.3% |
| CALL | 37 | 23.6% |
| MAKE_CELL | 20 | 12.7% |
| POP_TOP | 13 | 8.3% |
| CALL_KW | 13 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76 | 48.4% |
| LOAD_GLOBAL | 37 | 23.6% |
| JUMP_BACKWARD_NO_INTERRUPT | 17 | 10.8% |
| POP_TOP | 7 | 4.5% |
| LOAD_CONST | 6 | 3.8% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 255,628 | 28.2% |
| LOAD_ATTR_INSTANCE_VALUE | 217,036 | 24.0% |
| LOAD_FAST_LOAD_FAST | 204,080 | 22.6% |
| BINARY_OP | 160,249 | 17.7% |
| BINARY_OP_MULTIPLY_FLOAT | 66,060 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 358,009 | 39.6% |
| LOAD_FAST | 292,142 | 32.3% |
| STORE_FAST | 252,928 | 27.9% |
| CALL_ALLOC_AND_ENTER_INIT | 1,500 | 0.2% |
| RETURN_VALUE | 240 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,028,679 | 42.2% |
| LOAD_CONST | 7,599,042 | 32.0% |
| CALL_LEN | 4,396,118 | 18.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 936,291 | 3.9% |
| CALL | 521,902 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,657,236 | 40.6% |
| LOAD_FAST | 4,217,270 | 17.8% |
| BINARY_SLICE | 4,132,300 | 17.4% |
| CALL_BUILTIN_FAST | 4,041,988 | 17.0% |
| RETURN_VALUE | 1,003,257 | 4.2% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 67,180 | 37.5% |
| LOAD_CONST | 66,280 | 37.0% |
| LOAD_FAST_LOAD_FAST | 40,320 | 22.5% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,742 | 1.0% |
| LOAD_FAST | 1,440 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 66,000 | 36.9% |
| LIST_APPEND | 66,000 | 36.9% |
| LOAD_FAST | 34,020 | 19.0% |
| CALL | 6,960 | 3.9% |
| CALL_METHOD_DESCRIPTOR_O | 1,742 | 1.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 138,180 | 92.8% |
| LOAD_CONST | 7,706 | 5.2% |
| LOAD_FAST_LOAD_FAST | 2,860 | 1.9% |
| BINARY_OP | 180 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 66,060 | 44.3% |
| LOAD_CONST | 65,940 | 44.3% |
| CALL_BUILTIN_O | 7,946 | 5.3% |
| COMPARE_OP_FLOAT | 5,820 | 3.9% |
| STORE_FAST | 2,860 | 1.9% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 260,508 | 50.4% |
| LOAD_FAST_LOAD_FAST | 131,110 | 25.4% |
| LOAD_CONST | 68,516 | 13.3% |
| BINARY_OP_ADD_INT | 38,236 | 7.4% |
| LOAD_GLOBAL_MODULE | 17,407 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 260,948 | 50.5% |
| BINARY_OP | 131,110 | 25.4% |
| COMPARE_OP_INT | 66,000 | 12.8% |
| STORE_FAST | 49,891 | 9.7% |
| LIST_APPEND | 5,887 | 1.1% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 331,263 | 53.3% |
| LOAD_FAST | 131,982 | 21.2% |
| CALL | 66,596 | 10.7% |
| RETURN_VALUE | 64,100 | 10.3% |
| LOAD_ATTR_INSTANCE_VALUE | 16,799 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 206,180 | 33.2% |
| LOAD_CONST | 199,862 | 32.2% |
| SWAP | 131,931 | 21.2% |
| CALL | 65,100 | 10.5% |
| LOAD_FAST | 17,232 | 2.8% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,967,450 | 38.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,609,606 | 37.3% |
| LOAD_CONST | 7,084,565 | 22.7% |
| BINARY_OP_MULTIPLY_INT | 260,948 | 0.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 198,000 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,716,479 | 37.6% |
| LOAD_FAST | 11,615,006 | 37.3% |
| CALL_PY_WITH_DEFAULTS | 5,801,264 | 18.6% |
| SWAP | 803,290 | 2.6% |
| CALL_PY_EXACT_ARGS | 728,700 | 2.3% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,175,286 | 41.4% |
| LOAD_FAST_LOAD_FAST | 3,747,108 | 37.2% |
| LOAD_CONST | 1,062,907 | 10.5% |
| COPY | 820,223 | 8.1% |
| CALL | 199,569 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,293,156 | 52.5% |
| UNPACK_SEQUENCE_TUPLE | 1,240,286 | 12.3% |
| LOAD_CONST | 1,110,094 | 11.0% |
| RETURN_VALUE | 839,365 | 8.3% |
| LOAD_FAST | 559,098 | 5.5% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 473,774 | 99.9% |
| LOAD_FAST_LOAD_FAST | 540 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 0.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 276,274 | 58.2% |
| COPY_FREE_VARS | 198,000 | 41.7% |
| BUILD_TUPLE | 120 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 528,197 | 40.1% |
| LOAD_FAST_LOAD_FAST | 390,787 | 29.7% |
| ENTER_EXECUTOR | 330,690 | 25.1% |
| LOAD_FAST | 48,444 | 3.7% |
| BINARY_OP_SUBTRACT_INT | 16,907 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 725,607 | 55.1% |
| LOAD_ATTR_SLOT | 189,490 | 14.4% |
| STORE_FAST | 181,409 | 13.8% |
| TO_BOOL_BOOL | 66,480 | 5.1% |
| LOAD_ATTR_METHOD_NO_DICT | 48,000 | 3.6% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 135,780 | 97.1% |
| LOAD_FAST_LOAD_FAST | 3,600 | 2.6% |
| CALL_BUILTIN_O | 480 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 132,180 | 94.5% |
| LOAD_ATTR_METHOD_NO_DICT | 7,200 | 5.1% |
| LIST_APPEND | 480 | 0.3% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,539,546 | 94.9% |
| LOAD_FAST_LOAD_FAST | 52,281 | 3.2% |
| ENTER_EXECUTOR | 28,754 | 1.8% |
| BINARY_SUBSCR_LIST_INT | 1,062 | 0.1% |
| BINARY_SUBSCR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 516,000 | 31.8% |
| STORE_FAST | 487,162 | 30.0% |
| LOAD_ATTR_SLOT | 197,462 | 12.2% |
| CALL_BUILTIN_O | 132,000 | 8.1% |
| RETURN_VALUE | 78,800 | 4.9% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 133,081 | 60.3% |
| LOAD_FAST_LOAD_FAST | 69,564 | 31.5% |
| LOAD_CONST | 6,040 | 2.7% |
| LOAD_FAST | 5,160 | 2.3% |
| ENTER_EXECUTOR | 1,660 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 219,105 | 99.2% |
| COPY_FREE_VARS | 960 | 0.4% |
| POP_TOP | 720 | 0.3% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 75,053 | 47.2% |
| LOAD_FAST_LOAD_FAST | 39,856 | 25.0% |
| PUSH_NULL | 15,270 | 9.6% |
| LOAD_CONST | 15,183 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 10,608 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 77,568 | 48.7% |
| COPY_FREE_VARS | 64,080 | 40.3% |
| GET_AWAITABLE | 8,040 | 5.1% |
| POP_TOP | 7,583 | 4.8% |
| MAKE_CELL | 801 | 0.5% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,206,495 | 44.5% |
| LOAD_GLOBAL_BUILTIN | 1,649,443 | 22.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 849,476 | 11.8% |
| LOAD_ATTR_SLOT | 714,160 | 9.9% |
| PUSH_NULL | 328,440 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,091,919 | 29.0% |
| STORE_FAST | 1,610,042 | 22.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,018,136 | 14.1% |
| LOAD_FAST | 912,288 | 12.7% |
| CALL | 782,844 | 10.9% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,041,988 | 54.0% |
| LOAD_FAST | 1,961,664 | 26.2% |
| LOAD_CONST | 852,930 | 11.4% |
| LOAD_FAST_LOAD_FAST | 360,456 | 4.8% |
| LOAD_GLOBAL_MODULE | 132,000 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 5,903,640 | 78.8% |
| COPY | 524,186 | 7.0% |
| TO_BOOL_BOOL | 430,224 | 5.7% |
| RETURN_VALUE | 207,781 | 2.8% |
| POP_TOP | 187,468 | 2.5% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,018,136 | 52.8% |
| LOAD_ATTR_INSTANCE_VALUE | 402,387 | 20.9% |
| LOAD_FAST | 139,650 | 7.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 126,100 | 6.5% |
| LOAD_ATTR | 78,342 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 936,291 | 48.6% |
| LOAD_CONST | 464,362 | 24.1% |
| RETURN_VALUE | 216,929 | 11.3% |
| STORE_FAST | 84,584 | 4.4% |
| POP_TOP | 79,242 | 4.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,926,150 | 79.7% |
| LOAD_ATTR_INSTANCE_VALUE | 319,265 | 8.7% |
| BINARY_SUBSCR_TUPLE_INT | 132,000 | 3.6% |
| RETURN_GENERATOR | 75,883 | 2.1% |
| LOAD_ATTR_WITH_HINT | 66,000 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,655,151 | 72.3% |
| TO_BOOL_BOOL | 515,151 | 14.0% |
| RETURN_VALUE | 333,286 | 9.1% |
| LOAD_FAST | 67,560 | 1.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 66,000 | 1.8% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,435,766 | 70.6% |
| BUILD_TUPLE | 6,903,860 | 19.9% |
| LOAD_FAST_LOAD_FAST | 1,649,599 | 4.8% |
| LOAD_GLOBAL_MODULE | 1,250,101 | 3.6% |
| LOAD_ATTR | 278,863 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 34,268,133 | 99.0% |
| RETURN_VALUE | 219,542 | 0.6% |
| COPY | 132,561 | 0.4% |
| YIELD_VALUE | 1,560 | 0.0% |
| TO_BOOL | 460 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,665,481 | 50.8% |
| LOAD_ATTR_INSTANCE_VALUE | 12,633,606 | 47.0% |
| LOAD_ATTR_SLOT | 324,380 | 1.2% |
| LOAD_ATTR_WITH_HINT | 273,584 | 1.0% |
| LOAD_DEREF | 3,660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,653,294 | 47.0% |
| STORE_FAST | 6,156,235 | 22.9% |
| BINARY_OP_ADD_INT | 4,396,118 | 16.3% |
| LOAD_CONST | 2,377,244 | 8.8% |
| RETURN_VALUE | 702,432 | 2.6% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 910,860 | 63.8% |
| LOAD_FAST | 197,394 | 13.8% |
| BUILD_CONST_KEY_MAP | 132,780 | 9.3% |
| ENTER_EXECUTOR | 83,353 | 5.8% |
| BUILD_TUPLE | 50,975 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,050,188 | 73.6% |
| LOAD_FAST | 231,364 | 16.2% |
| NOP | 67,090 | 4.7% |
| LOAD_FAST_LOAD_FAST | 66,780 | 4.7% |
| JUMP_FORWARD | 6,120 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,255,505 | 44.3% |
| LOAD_CONST | 1,722,146 | 33.9% |
| BUILD_TUPLE | 396,000 | 7.8% |
| LOAD_GLOBAL_BUILTIN | 326,700 | 6.4% |
| CALL_BUILTIN_CLASS | 132,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,016,593 | 79.0% |
| BINARY_OP_SUBTRACT_INT | 198,000 | 3.9% |
| TO_BOOL_INT | 149,655 | 2.9% |
| LOAD_FAST | 139,260 | 2.7% |
| POP_TOP | 133,420 | 2.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,512,524 | 92.7% |
| LOAD_FAST | 237,317 | 2.9% |
| LOAD_FAST_LOAD_FAST | 179,825 | 2.2% |
| LOAD_ATTR_METHOD_NO_DICT | 108,400 | 1.3% |
| LOAD_ATTR | 38,836 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,759,087 | 95.7% |
| POP_TOP | 276,158 | 3.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 66,000 | 0.8% |
| GET_ITER | 1,320 | 0.0% |
| LOAD_CONST | 901 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,644,698 | 84.3% |
| LOAD_ATTR | 1,008,521 | 15.1% |
| LOAD_ATTR_METHOD_LAZY_DICT | 38,236 | 0.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,518 | 0.0% |
| CALL | 1,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,899,900 | 28.4% |
| POP_TOP | 1,022,165 | 15.3% |
| CALL_BUILTIN_CLASS | 849,476 | 12.7% |
| LOAD_FAST | 816,934 | 12.2% |
| TO_BOOL_BOOL | 800,174 | 12.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,476,673 | 51.3% |
| CALL_BUILTIN_FAST | 5,903,640 | 35.7% |
| BUILD_TUPLE | 1,230,807 | 7.5% |
| LOAD_ATTR_INSTANCE_VALUE | 253,000 | 1.5% |
| LOAD_CONST | 149,183 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 9,858,590 | 59.7% |
| RETURN_VALUE | 6,493,901 | 39.3% |
| LOAD_CONST | 75,623 | 0.5% |
| STORE_FAST | 41,008 | 0.2% |
| BUILD_LIST | 38,176 | 0.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,232,171 | 37.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,324,018 | 29.9% |
| LOAD_GLOBAL_MODULE | 4,078,253 | 9.9% |
| CALL_TYPE_1 | 3,565,408 | 8.7% |
| LOAD_FAST_LOAD_FAST | 1,239,707 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 35,420,283 | 86.1% |
| MAKE_CELL | 4,101,875 | 10.0% |
| COPY_FREE_VARS | 1,417,874 | 3.4% |
| RETURN_GENERATOR | 152,476 | 0.4% |
| TO_BOOL_BOOL | 64,991 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,635,158 | 34.1% |
| LOAD_CONST | 6,015,442 | 30.9% |
| BINARY_OP_SUBTRACT_INT | 5,801,264 | 29.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 409,563 | 2.1% |
| ENTER_EXECUTOR | 204,240 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,812,597 | 96.6% |
| MAKE_CELL | 587,835 | 3.0% |
| RETURN_GENERATOR | 79,478 | 0.4% |
| COPY_FREE_VARS | 120 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 109,995 | 44.9% |
| CALL_TYPE_1 | 66,000 | 27.0% |
| CALL_TUPLE_1 | 66,000 | 27.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,742 | 0.7% |
| LOAD_FAST | 745 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 109,995 | 44.9% |
| LOAD_ATTR_METHOD_NO_DICT | 66,000 | 27.0% |
| CONTAINS_OP | 66,000 | 27.0% |
| STORE_FAST | 2,107 | 0.9% |
| LIST_APPEND | 300 | 0.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 430,276 | 61.9% |
| RETURN_GENERATOR | 132,000 | 19.0% |
| CALL_BUILTIN_CLASS | 66,600 | 9.6% |
| STORE_FAST | 66,000 | 9.5% |
| LOAD_ATTR_MODULE | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 555,076 | 79.8% |
| CALL_STR_1 | 66,000 | 9.5% |
| BINARY_OP | 66,000 | 9.5% |
| LOAD_FAST_LOAD_FAST | 7,200 | 1.0% |
| STORE_FAST | 780 | 0.1% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,921,291 | 98.9% |
| BINARY_SUBSCR_TUPLE_INT | 66,000 | 1.1% |
| LOAD_DEREF | 240 | 0.0% |
| CALL | 80 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,565,408 | 59.5% |
| STORE_FAST | 1,501,420 | 25.1% |
| LOAD_GLOBAL_BUILTIN | 330,060 | 5.5% |
| LOAD_GLOBAL_MODULE | 191,120 | 3.2% |
| LOAD_FAST | 134,880 | 2.3% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 524,611 | 36.7% |
| LOAD_CONST | 324,176 | 22.7% |
| LOAD_FAST | 262,474 | 18.4% |
| BINARY_OP | 138,081 | 9.7% |
| COPY | 131,110 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 901,971 | 63.2% |
| RETURN_VALUE | 524,611 | 36.7% |
| POP_JUMP_IF_TRUE | 720 | 0.1% |
| EXTENDED_ARG | 361 | 0.0% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 62,010,032 | 57.5% |
| LOAD_GLOBAL_MODULE | 37,065,235 | 34.4% |
| COPY | 6,208,312 | 5.8% |
| LOAD_FAST_LOAD_FAST | 1,301,332 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 519,675 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 100,628,281 | 93.3% |
| EXTENDED_ARG | 5,813,864 | 5.4% |
| POP_JUMP_IF_TRUE | 1,386,223 | 1.3% |
| RETURN_VALUE | 40,158 | 0.0% |
| COMPARE_OP | 2,727 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,946,649 | 71.4% |
| LOAD_FAST | 452,186 | 11.0% |
| LOAD_FAST_LOAD_FAST | 324,040 | 7.9% |
| LOAD_GLOBAL_MODULE | 270,330 | 6.6% |
| LOAD_ATTR_SLOT | 66,000 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,777,759 | 91.6% |
| POP_JUMP_IF_TRUE | 276,840 | 6.7% |
| RETURN_VALUE | 66,000 | 1.6% |
| COPY | 5,226 | 0.1% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 71,499 | 94.8% |
| GET_ITER | 2,820 | 3.7% |
| SWAP | 963 | 1.3% |
| LOAD_FAST | 120 | 0.2% |
| FOR_ITER | 24 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 71,379 | 94.6% |
| POP_TOP | 3,743 | 5.0% |
| RETURN_CONST | 180 | 0.2% |
| STORE_FAST | 120 | 0.2% |
| RESUME | 4 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,560,967 | 96.9% |
| SWAP | 41,997 | 2.6% |
| JUMP_BACKWARD | 4,864 | 0.3% |
| LOAD_FAST | 2,560 | 0.2% |
| EXTENDED_ARG | 700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 790,796 | 49.1% |
| LOAD_FAST | 369,386 | 22.9% |
| RETURN_CONST | 342,682 | 21.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 104,064 | 6.5% |
| STORE_FAST_LOAD_FAST | 840 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,724,943 | 99.9% |
| JUMP_BACKWARD | 532 | 0.0% |
| SWAP | 180 | 0.0% |
| LOAD_FAST | 180 | 0.0% |
| FOR_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,640,012 | 95.0% |
| LOAD_DEREF | 79,459 | 4.6% |
| RETURN_CONST | 6,240 | 0.4% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_CONST | 64 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,244,627 | 94.6% |
| LOAD_FAST | 141,043 | 3.1% |
| SWAP | 100,140 | 2.2% |
| JUMP_BACKWARD | 2,200 | 0.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,450,950 | 99.2% |
| STORE_FAST_LOAD_FAST | 33,600 | 0.7% |
| RETURN_CONST | 1,360 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 640 | 0.0% |
| LOAD_GLOBAL_MODULE | 340 | 0.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 233,816 | 54.4% |
| LOAD_ATTR_MODULE | 191,520 | 44.5% |
| LOAD_GLOBAL_BUILTIN | 1,906 | 0.4% |
| LOAD_FAST | 1,560 | 0.4% |
| ENTER_EXECUTOR | 1,080 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 153,664 | 35.7% |
| COMPARE_OP_INT | 114,948 | 26.7% |
| CALL_PY_EXACT_ARGS | 76,572 | 17.8% |
| LOAD_FAST | 42,236 | 9.8% |
| CALL | 39,016 | 9.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 107,946,011 | 77.1% |
| LOAD_DEREF | 13,661,971 | 9.8% |
| COPY | 8,576,182 | 6.1% |
| LOAD_FAST_LOAD_FAST | 8,545,760 | 6.1% |
| LOAD_ATTR_SLOT | 990,179 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,408,888 | 13.2% |
| LOAD_FAST | 16,629,258 | 11.9% |
| CALL_LEN | 12,633,606 | 9.0% |
| BINARY_OP_SUBTRACT_INT | 11,609,606 | 8.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 10,300,958 | 7.4% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 10,300,958 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 5,903,640 | 57.3% |
| LOAD_FAST | 4,290,262 | 41.6% |
| LOAD_CONST | 68,820 | 0.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 38,236 | 0.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,506,440 | 56.1% |
| LOAD_ATTR_INSTANCE_VALUE | 5,892,532 | 20.0% |
| LOAD_ATTR_WITH_HINT | 4,352,860 | 14.8% |
| LOAD_ATTR_SLOT | 1,494,160 | 5.1% |
| RETURN_VALUE | 400,417 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,017,143 | 37.4% |
| LOAD_CONST | 9,540,470 | 32.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 5,644,698 | 19.2% |
| LOAD_FAST_LOAD_FAST | 1,077,028 | 3.7% |
| CALL | 742,512 | 2.5% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,301,047 | 71.9% |
| LOAD_DEREF | 9,998,511 | 18.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,985,551 | 3.7% |
| LOAD_ATTR_SLOT | 1,279,574 | 2.4% |
| LOAD_ATTR_WITH_HINT | 918,406 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,310,976 | 26.9% |
| CALL_PY_EXACT_ARGS | 12,324,018 | 23.1% |
| LOAD_FAST_LOAD_FAST | 10,877,160 | 20.4% |
| LOAD_CONST | 6,476,599 | 12.2% |
| LOAD_GLOBAL_BUILTIN | 4,415,492 | 8.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 14,604,001 | 98.9% |
| LOAD_FAST | 86,908 | 0.6% |
| ENTER_EXECUTOR | 33,276 | 0.2% |
| LOAD_ATTR_MODULE | 28,530 | 0.2% |
| LOAD_ATTR | 5,802 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 13,649,057 | 92.5% |
| LOAD_ATTR_CLASS | 191,520 | 1.3% |
| LOAD_ATTR | 170,062 | 1.2% |
| BINARY_OP | 144,696 | 1.0% |
| LOAD_FAST | 144,335 | 1.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,060 | 82.3% |
| LOAD_FAST_LOAD_FAST | 660 | 17.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,320 | 35.5% |
| TO_BOOL_BOOL | 900 | 24.2% |
| LOAD_FAST | 660 | 17.7% |
| CALL_BUILTIN_FAST | 660 | 17.7% |
| CALL | 180 | 4.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 192,360 | 61.0% |
| LOAD_FAST | 82,714 | 26.2% |
| LOAD_FAST_LOAD_FAST | 40,038 | 12.7% |
| LOAD_ATTR | 220 | 0.1% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 116,048 | 36.8% |
| COMPARE_OP_INT | 76,592 | 24.3% |
| LOAD_FAST | 39,496 | 12.5% |
| LOAD_CONST | 38,416 | 12.2% |
| STORE_FAST | 38,296 | 12.1% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,821,297 | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE | 133,000 | 6.5% |
| RETURN_VALUE | 75,769 | 3.7% |
| ENTER_EXECUTOR | 11,880 | 0.6% |
| STORE_FAST_LOAD_FAST | 6,146 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,050,530 | 99.9% |
| COPY_FREE_VARS | 1,440 | 0.1% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 60 | 0.0% |
| LOAD_ATTR_PROPERTY | 60 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,096,872 | 93.1% |
| LOAD_FAST_LOAD_FAST | 720,434 | 2.8% |
| STORE_FAST_LOAD_FAST | 306,000 | 1.2% |
| COPY | 269,931 | 1.0% |
| BINARY_SUBSCR_TUPLE_INT | 197,462 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,834,279 | 11.0% |
| TO_BOOL_NONE | 2,742,764 | 10.6% |
| LOAD_CONST | 2,269,964 | 8.8% |
| STORE_FAST | 2,163,892 | 8.4% |
| LOAD_FAST | 1,876,506 | 7.3% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,166,205 | 80.1% |
| COPY | 1,056,148 | 6.4% |
| LOAD_FAST_LOAD_FAST | 872,651 | 5.3% |
| LOAD_DEREF | 586,808 | 3.6% |
| ENTER_EXECUTOR | 423,158 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,352,860 | 26.5% |
| LOAD_FAST | 3,112,572 | 18.9% |
| TO_BOOL_BOOL | 1,945,741 | 11.8% |
| LOAD_CONST | 1,465,700 | 8.9% |
| RETURN_VALUE | 1,391,311 | 8.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,067,492 | 35.2% |
| RESUME_CHECK | 19,088,323 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 13,276,948 | 12.9% |
| POP_JUMP_IF_FALSE | 12,260,220 | 12.0% |
| STORE_FAST | 6,999,506 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,569,739 | 44.4% |
| CALL_ISINSTANCE | 24,435,766 | 23.8% |
| LOAD_GLOBAL_BUILTIN | 13,276,948 | 12.9% |
| BUILD_TUPLE | 11,792,824 | 11.5% |
| IS_OP | 1,998,280 | 1.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,888,024 | 43.8% |
| RESUME_CHECK | 12,603,887 | 12.9% |
| POP_JUMP_IF_FALSE | 7,889,962 | 8.1% |
| STORE_FAST | 6,823,516 | 7.0% |
| LOAD_ATTR_METHOD_LAZY_DICT | 5,903,640 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 37,065,235 | 37.8% |
| LOAD_ATTR_MODULE | 14,604,001 | 14.9% |
| LOAD_FAST | 14,216,090 | 14.5% |
| STORE_FAST | 9,976,752 | 10.2% |
| CALL_PY_EXACT_ARGS | 4,078,253 | 4.2% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,360 | 91.5% |
| EXTENDED_ARG | 120 | 4.7% |
| LOAD_SUPER_ATTR | 100 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,440 | 55.8% |
| PUSH_NULL | 1,140 | 44.2% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 511,777 | 99.9% |
| LOAD_SUPER_ATTR | 300 | 0.1% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 308,176 | 60.2% |
| LOAD_FAST_LOAD_FAST | 163,244 | 31.9% |
| CALL_PY_EXACT_ARGS | 40,117 | 7.8% |
| CALL | 340 | 0.1% |
| LOAD_CONST | 220 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 35,420,283 | 35.3% |
| CALL_PY_WITH_DEFAULTS | 18,812,597 | 18.7% |
| CACHE | 17,300,180 | 17.2% |
| MAKE_CELL | 7,702,963 | 7.7% |
| CALL_KW | 6,006,644 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,462,155 | 45.3% |
| LOAD_GLOBAL_BUILTIN | 19,088,323 | 19.0% |
| LOAD_GLOBAL_MODULE | 12,603,887 | 12.5% |
| LOAD_CONST | 7,571,688 | 7.5% |
| LOAD_DEREF | 7,021,847 | 7.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 284,819 | 53.5% |
| JUMP_BACKWARD_NO_INTERRUPT | 246,997 | 46.4% |
| SEND | 347 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 285,039 | 53.6% |
| RESUME_CHECK | 246,932 | 46.4% |
| END_SEND | 120 | 0.0% |
| YIELD_VALUE | 60 | 0.0% |
| RESUME | 12 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,325,335 | 49.3% |
| SWAP | 8,576,182 | 40.9% |
| LOAD_FAST_LOAD_FAST | 1,861,741 | 8.9% |
| LOAD_DEREF | 79,922 | 0.4% |
| BINARY_SUBSCR_DICT | 60,040 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,467,878 | 59.5% |
| LOAD_FAST_LOAD_FAST | 2,442,369 | 11.7% |
| LOAD_CONST | 2,209,598 | 10.5% |
| RETURN_CONST | 820,803 | 3.9% |
| LOAD_GLOBAL_BUILTIN | 758,609 | 3.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,608,566 | 53.6% |
| LOAD_FAST_LOAD_FAST | 5,361,067 | 43.5% |
| SWAP | 269,931 | 2.2% |
| STORE_FAST_LOAD_FAST | 66,000 | 0.5% |
| STORE_ATTR_SLOT | 16,212 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,911,689 | 31.7% |
| LOAD_FAST_LOAD_FAST | 3,420,012 | 27.8% |
| LOAD_FAST | 2,026,198 | 16.4% |
| RETURN_CONST | 1,890,268 | 15.3% |
| LOAD_GLOBAL_BUILTIN | 529,060 | 4.3% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,056,148 | 98.9% |
| LOAD_FAST_LOAD_FAST | 7,541 | 0.7% |
| LOAD_DEREF | 1,562 | 0.1% |
| LOAD_FAST | 1,320 | 0.1% |
| STORE_ATTR | 672 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 740,633 | 69.4% |
| EXTENDED_ARG | 324,000 | 30.4% |
| RETURN_CONST | 900 | 0.1% |
| LOAD_CONST | 550 | 0.1% |
| LOAD_GLOBAL_MODULE | 400 | 0.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,189,202 | 53.3% |
| LOAD_FAST | 881,434 | 14.7% |
| SWAP | 820,223 | 13.7% |
| LOAD_CONST | 669,693 | 11.2% |
| LOAD_ATTR_SLOT | 318,660 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,646,802 | 44.2% |
| LOAD_FAST | 1,405,057 | 23.5% |
| LOAD_FAST_LOAD_FAST | 661,500 | 11.0% |
| JUMP_BACKWARD | 644,700 | 10.8% |
| RETURN_CONST | 144,880 | 2.4% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 38,756 | 62.4% |
| LOAD_FAST_LOAD_FAST | 17,170 | 27.7% |
| LOAD_ATTR_INSTANCE_VALUE | 6,000 | 9.7% |
| SWAP | 120 | 0.2% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 44,236 | 71.3% |
| ENTER_EXECUTOR | 9,660 | 15.6% |
| LOAD_FAST_LOAD_FAST | 7,510 | 12.1% |
| RETURN_CONST | 600 | 1.0% |
| LOAD_FAST | 60 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 330,700 | 51.6% |
| LOAD_FAST | 278,044 | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE | 23,218 | 3.6% |
| LOAD_ATTR_SLOT | 6,000 | 0.9% |
| CALL | 780 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 368,246 | 57.5% |
| POP_JUMP_IF_TRUE | 272,388 | 42.5% |
| TO_BOOL_NONE | 103 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 34,268,133 | 52.7% |
| LOAD_ATTR_INSTANCE_VALUE | 18,408,888 | 28.3% |
| RETURN_VALUE | 4,321,523 | 6.6% |
| LOAD_ATTR_WITH_HINT | 1,945,741 | 3.0% |
| COPY | 1,464,741 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 53,372,752 | 82.0% |
| EXTENDED_ARG | 7,122,624 | 10.9% |
| POP_JUMP_IF_TRUE | 4,578,799 | 7.0% |
| UNARY_NOT | 720 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 527,516 | 32.0% |
| COPY | 460,686 | 27.9% |
| LOAD_FAST | 265,493 | 16.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 149,655 | 9.1% |
| RETURN_VALUE | 131,876 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 941,128 | 57.0% |
| POP_JUMP_IF_FALSE | 709,722 | 43.0% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 765,098 | 61.4% |
| LOAD_FAST | 337,111 | 27.0% |
| LOAD_ATTR_WITH_HINT | 143,765 | 11.5% |
| LOAD_DEREF | 360 | 0.0% |
| LOAD_FAST_CHECK | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,239,676 | 99.4% |
| POP_JUMP_IF_TRUE | 7,118 | 0.6% |
| EXTENDED_ARG | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,742,764 | 77.9% |
| LOAD_FAST | 321,624 | 9.1% |
| WITH_EXCEPT_START | 133,003 | 3.8% |
| LOAD_ATTR | 125,300 | 3.6% |
| COPY | 114,936 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,088,354 | 87.7% |
| POP_JUMP_IF_TRUE | 431,048 | 12.2% |
| EXTENDED_ARG | 300 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 111 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 110,557 | 38.5% |
| LOAD_ATTR | 66,000 | 23.0% |
| LOAD_ATTR_WITH_HINT | 60,780 | 21.2% |
| STORE_FAST_LOAD_FAST | 33,600 | 11.7% |
| COPY | 13,780 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 147,000 | 51.3% |
| POP_JUMP_IF_FALSE | 139,819 | 48.7% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 841 | 93.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 40 | 4.4% |
| UNPACK_SEQUENCE | 20 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 901 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,040,242 | 74.1% |
| BINARY_SUBSCR_DICT | 1,240,286 | 15.2% |
| LOAD_FAST | 399,220 | 4.9% |
| CALL_FUNCTION_EX | 324,000 | 4.0% |
| END_SEND | 66,240 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 8,074,168 | 99.0% |
| STORE_FAST | 81,137 | 1.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 3,846,676 | 64.0% |
| RETURN_VALUE | 665,452 | 11.1% |
| CALL_FUNCTION_EX | 462,000 | 7.7% |
| BINARY_SUBSCR_DICT | 305,078 | 5.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 264,960 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 5,487,921 | 91.3% |
| STORE_FAST | 452,176 | 7.5% |
| LOAD_FAST_LOAD_FAST | 66,000 | 1.1% |
| LOAD_FAST | 1,740 | 0.0% |
| STORE_FAST_LOAD_FAST | 60 | 0.0% |


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

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8170043 | 36.7% |
| specialization.deopt |         2124 | 0.0% |
|          hit |     13961268 | 62.8% |
|         miss |       112537 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,716 | 46.6% |
| Failure | 3,112 | 53.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 2,000 | 64.3% |
| other | 952 | 30.6% |
| code complex parameters | 80 | 2.6% |
| out of range | 60 | 1.9% |
| list slice | 20 | 0.6% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       398927 | 6.1% |
|          hit |      6124431 | 93.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,140 | 69.6% |
| Failure | 499 | 30.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 262 | 52.5% |
| py simple | 237 | 47.5% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6505593 | 8.0% |
| specialization.deopt |          214 | 0.0% |
|          hit |     75009096 | 92.0% |
|         miss |        12833 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,050 | 41.4% |
| Failure | 5,734 | 58.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 2,132 | 37.2% |
| set | 1,361 | 23.7% |
| tuple | 700 | 12.2% |
| sequence | 580 | 10.1% |
| float | 340 | 5.9% |
| mapping | 320 | 5.6% |
| bytes | 161 | 2.8% |
| other | 100 | 1.7% |
| bytearray | 40 | 0.7% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     29155978 | 33.6% |
| specialization.deopt |           40 | 0.0% |
|          hit |     57524321 | 66.4% |
|         miss |         3559 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 949 | 7.6% |
| Failure | 11,548 | 92.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 7,340 | 63.6% |
| multiply different types | 801 | 6.9% |
| or | 740 | 6.4% |
| true divide different types | 521 | 4.5% |
| remainder | 460 | 4.0% |
| add other | 360 | 3.1% |
| true divide other | 233 | 2.0% |
| add different types | 220 | 1.9% |
| subtract different types | 200 | 1.7% |
| true divide float | 141 | 1.2% |
| lshift | 140 | 1.2% |
| floor divide | 140 | 1.2% |
| rshift | 99 | 0.9% |
| subtract other | 80 | 0.7% |
| and other | 40 | 0.3% |
| power | 33 | 0.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     21380060 | 9.9% |
| specialization.deopt |         6213 | 0.0% |
|          hit |    193919538 | 89.9% |
|         miss |       346839 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 19,065 | 42.5% |
| Failure | 25,822 | 57.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 5,578 | 21.6% |
| cfunc noargs | 5,041 | 19.5% |
| class no vectorcall | 3,929 | 15.2% |
| cfunc varargs keywords | 1,823 | 7.1% |
| meth descr varargs keywords | 1,506 | 5.8% |
| meth descr varargs | 1,506 | 5.8% |
| meth descr method fastcall keywords | 1,284 | 5.0% |
| other | 1,126 | 4.4% |
| cfunc varargs | 1,117 | 4.3% |
| no dict | 870 | 3.4% |
| wrong number arguments | 720 | 2.8% |
| class mutable | 528 | 2.0% |
| init not simple | 360 | 1.4% |
| operator wrapper | 294 | 1.1% |
| init not python | 60 | 0.2% |
| cmethod | 60 | 0.2% |
| str | 20 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     11661004 | 9.3% |
| specialization.deopt |         2787 | 0.0% |
|          hit |    113895070 | 90.6% |
|         miss |       147825 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,610 | 32.2% |
| Failure | 7,598 | 67.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 6,058 | 79.7% |
| float long | 444 | 5.8% |
| baseobject | 376 | 4.9% |
| long float | 260 | 3.4% |
| different types | 200 | 2.6% |
| other | 200 | 2.6% |
| tuple | 40 | 0.5% |
| bool | 20 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     11460015 | 59.2% |
|          hit |      7900483 | 40.8% |
|         miss |          300 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 448 | 6.3% |
| Failure | 6,654 | 93.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 2,650 | 39.8% |
| set | 2,342 | 35.2% |
| dict values | 440 | 6.6% |
| dict keys | 320 | 4.8% |
| zip | 300 | 4.5% |
| itertools | 220 | 3.3% |
| other | 160 | 2.4% |
| enumerate | 120 | 1.8% |
| reversed list | 62 | 0.9% |
| bytes | 40 | 0.6% |


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
| specialization.deferred |     16364586 | 5.1% |
| specialization.deopt |        32694 | 0.0% |
|          hit |    302547888 | 94.3% |
|         miss |      1748271 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 55,566 | 68.7% |
| Failure | 25,324 | 31.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 9,336 | 36.9% |
| has managed dict | 5,621 | 22.2% |
| metaclass attribute | 3,156 | 12.5% |
| not managed dict | 2,476 | 9.8% |
| non object slot | 1,020 | 4.0% |
| module attr not found | 620 | 2.4% |
| shadowed | 552 | 2.2% |
| mutable class | 542 | 2.1% |
| class attr descriptor | 541 | 2.1% |
| overridden | 540 | 2.1% |
| non overriding descriptor | 420 | 1.7% |
| class method obj | 280 | 1.1% |
| builtin class method | 80 | 0.3% |
| class attr simple | 60 | 0.2% |
| not in keys | 60 | 0.2% |
| property | 20 | 0.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          448 | 0.0% |
| specialization.deopt |           40 | 0.0% |
|          hit |    204104443 | 100.0% |
|         miss |         1228 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 17,102 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       514737 | 99.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 400 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       404931 | 43.2% |
|          hit |       531983 | 56.7% |
|         miss |          180 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 347 | 31.7% |
| Failure | 746 | 68.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 706 | 94.6% |
| dict keys | 40 | 5.4% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       743742 | 2.1% |
| specialization.deopt |        16293 | 0.0% |
|          hit |     33471014 | 95.4% |
|         miss |       866717 | 2.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 24,105 | 85.3% |
| Failure | 4,140 | 14.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 2,920 | 70.5% |
| property | 460 | 11.1% |
| overridden | 220 | 5.3% |
| method | 180 | 4.3% |
| class attr simple | 140 | 3.4% |
| overriding descriptor | 80 | 1.9% |
| no dict | 60 | 1.4% |
| not in keys | 40 | 1.0% |
| not managed dict | 40 | 1.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         1932 | 0.0% |
|          hit |     14707634 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 406 | 87.1% |
| Failure | 60 | 12.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| iterator | 60 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,578,911,429 | 52.0% |
| Not specialized | 356,811,484 | 11.8% |
| Specialized | 1,098,425,153 | 36.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,027,694 | 100.0% |
| BINARY_OP | 29,155,978 | 0.0% |
| CALL | 21,380,060 | 0.0% |
| LOAD_ATTR | 16,364,586 | 0.0% |
| COMPARE_OP | 11,661,004 | 0.0% |
| FOR_ITER | 11,460,015 | 0.0% |
| BINARY_SUBSCR | 8,170,043 | 0.0% |
| TO_BOOL | 6,505,593 | 0.0% |
| STORE_ATTR | 743,742 | 0.0% |
| SEND | 404,931 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,003,346 | 30.9% |
| STORE_ATTR_SLOT | 858,604 | 26.4% |
| LOAD_ATTR_INSTANCE_VALUE | 291,950 | 9.0% |
| LOAD_ATTR_METHOD_NO_DICT | 285,147 | 8.8% |
| COMPARE_OP_INT | 146,365 | 4.5% |
| LOAD_ATTR_WITH_HINT | 143,825 | 4.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 136,384 | 4.2% |
| CALL_PY_EXACT_ARGS | 87,860 | 2.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 85,250 | 2.6% |
| BINARY_SUBSCR_TUPLE_INT | 56,286 | 1.7% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 19,127,223 | 18.9% |
| Calls to Python functions inlined | 82,106,278 | 81.1% |
| Calls via PyEval_EvalFrame (total) | 19,127,223 | 18.9% |
| Calls via PyEval_EvalFrame (vector) | 17,834,189 | 17.6% |
| Calls via PyEval_EvalFrame (generator) | 1,293,034 | 1.3% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 17,834,189 | 17.6% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 2,654,787 | 2.6% |
| Calls via PyEval_EvalFrame (function ex) | 4,562,688 | 4.5% |
| Calls via PyEval_EvalFrame (api) | 3,218,404 | 3.2% |
| Calls via PyEval_EvalFrame (method) | 1,259,190 | 1.2% |
| Frames pushed | 99,553,416 | 98.3% |
| Frame objects created | 1,186,639 | 1.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 98,436,007 | 38.3% |
| Frees to freelist | 98,724,684 |  |
| Allocations | 158,765,690 | 61.7% |
| Allocations to 512 bytes | 157,791,627 | 61.3% |
| Allocations to 4 kbytes | 812,311 | 0.3% |
| Allocations over 4 kbytes | 161,752 | 0.1% |
| Frees | 154,882,331 |  |
| New values | 294,525 |  |
| Interpreter increfs | 1,123,908,193 | 78.9% |
| Interpreter decrefs | 1,287,456,991 | 77.7% |
| Increfs | 300,943,812 | 21.1% |
| Decrefs | 369,175,933 | 22.3% |
| Materialize dict (on request) | 1,742 | 0.6% |
| Materialize dict (new key) | 180 | 0.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 1,742 | 0.6% |
| Method cache hits | 19,435,401 |  |
| Method cache misses | 276,617 |  |
| Method cache collisions | 563,784 |  |
| Method cache dunder hits | 56,414,730 |  |
| Method cache dunder misses | 287,510 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 6,638 | 601,861 | 45,454,452 |
| 1 | 609 | 225,935 | 29,108,506 |
| 2 | 60 | 33,478 | 75,102,686 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
