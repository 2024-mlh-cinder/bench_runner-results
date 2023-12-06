
# Pystats results

- benchmark: async_generators
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 281,764,640 | 12.7% | 12.7% |  |
| RESUME_CHECK | 181,825,900 | 8.2% | 20.9% | 0.0% |
| STORE_FAST | 157,877,580 | 7.1% | 28.0% |  |
| POP_TOP | 157,779,380 | 7.1% | 35.2% |  |
| INTERPRETER_EXIT | 157,616,100 | 7.1% | 42.3% |  |
| SEND | 133,548,900 | 6.0% | 48.3% |  |
| ENTER_EXECUTOR | 130,861,540 | 5.9% | 54.2% |  |
| YIELD_VALUE | 125,521,580 | 5.7% | 59.9% |  |
| END_SEND | 125,515,760 | 5.7% | 65.5% |  |
| CALL_INTRINSIC_1 | 120,278,460 | 5.4% | 71.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 82,966,320 | 3.7% | 74.7% | 0.0% |
| LOAD_CONST | 56,653,380 | 2.6% | 77.3% |  |
| POP_JUMP_IF_FALSE | 56,398,680 | 2.5% | 79.8% |  |
| LOAD_FAST_LOAD_FAST | 48,233,140 | 2.2% | 82.0% |  |
| RETURN_CONST | 48,152,240 | 2.2% | 84.1% |  |
| LOAD_GLOBAL_MODULE | 32,388,800 | 1.5% | 85.6% | 0.2% |
| CALL_PY_EXACT_ARGS | 24,130,800 | 1.1% | 86.7% | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 24,127,320 | 1.1% | 87.8% | 0.1% |
| LOAD_GLOBAL_BUILTIN | 16,267,220 | 0.7% | 88.5% | 0.3% |
| CALL | 16,209,000 | 0.7% | 89.3% |  |
| RETURN_VALUE | 16,193,440 | 0.7% | 90.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 16,119,140 | 0.7% | 90.7% |  |
| CALL_LEN | 16,062,440 | 0.7% | 91.4% |  |
| COMPARE_OP_INT | 16,056,440 | 0.7% | 92.2% | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 16,031,220 | 0.7% | 92.9% | 0.0% |
| BINARY_SLICE | 16,021,100 | 0.7% | 93.6% |  |
| TO_BOOL_BOOL | 8,205,720 | 0.4% | 94.0% | 0.0% |
| PUSH_NULL | 8,100,820 | 0.4% | 94.3% |  |
| TO_BOOL_NONE | 8,083,940 | 0.4% | 94.7% | 45.2% |
| TO_BOOL_ALWAYS_TRUE | 8,069,900 | 0.4% | 95.1% | 45.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,043,440 | 0.4% | 95.4% | 0.0% |
| POP_JUMP_IF_NONE | 8,034,180 | 0.4% | 95.8% |  |
| BINARY_OP | 8,032,180 | 0.4% | 96.2% |  |
| BINARY_OP_ADD_INT | 8,026,140 | 0.4% | 96.5% |  |
| TO_BOOL | 8,015,720 | 0.4% | 96.9% |  |
| BINARY_SUBSCR | 8,013,020 | 0.4% | 97.2% |  |
| CALL_ALLOC_AND_ENTER_INIT | 8,009,660 | 0.4% | 97.6% | 0.0% |
| EXIT_INIT_CHECK | 8,009,560 | 0.4% | 98.0% |  |
| TO_BOOL_LIST | 8,005,840 | 0.4% | 98.3% | 0.0% |
| RETURN_GENERATOR | 8,003,940 | 0.4% | 98.7% |  |
| GET_ANEXT | 8,000,960 | 0.4% | 99.1% |  |
| END_ASYNC_FOR | 8,000,000 | 0.4% | 99.4% |  |
| GET_AITER | 8,000,000 | 0.4% | 99.8% |  |
| JUMP_BACKWARD | 2,777,080 | 0.1% | 99.9% |  |
| POP_JUMP_IF_TRUE | 118,600 | 0.0% | 99.9% |  |
| LOAD_ATTR | 109,160 | 0.0% | 99.9% |  |
| LOAD_ATTR_MODULE | 104,700 | 0.0% | 99.9% | 8.8% |
| NOP | 81,940 | 0.0% | 99.9% |  |
| STORE_NAME | 81,500 | 0.0% | 99.9% |  |
| COPY | 76,020 | 0.0% | 99.9% |  |
| CONTAINS_OP | 70,700 | 0.0% | 99.9% |  |
| COMPARE_OP_STR | 63,640 | 0.0% | 99.9% | 0.4% |
| POP_JUMP_IF_NOT_NONE | 61,660 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST | 55,280 | 0.0% | 99.9% | 1.3% |
| SWAP | 55,200 | 0.0% | 99.9% |  |
| LOAD_DEREF | 53,380 | 0.0% | 99.9% |  |
| EXTENDED_ARG | 51,180 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 50,360 | 0.0% | 99.9% |  |
| LOAD_NAME | 48,140 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 47,120 | 0.0% | 99.9% |  |
| IS_OP | 46,560 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 40,800 | 0.0% | 100.0% |  |
| GET_ITER | 40,360 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 40,200 | 0.0% | 100.0% |  |
| BUILD_LIST | 39,320 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 36,600 | 0.0% | 100.0% |  |
| STORE_ATTR | 35,300 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 32,140 | 0.0% | 100.0% | 2.2% |
| CALL_BUILTIN_O | 31,380 | 0.0% | 100.0% | 5.8% |
| JUMP_FORWARD | 31,120 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 29,780 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 27,180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 25,820 | 0.0% | 100.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 24,960 | 0.0% | 100.0% | 27.5% |
| LOAD_ATTR_SLOT | 24,600 | 0.0% | 100.0% | 1.1% |
| TO_BOOL_INT | 23,740 | 0.0% | 100.0% | 2.8% |
| CALL_LIST_APPEND | 22,740 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 22,360 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 21,540 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 20,640 | 0.0% | 100.0% | 1.2% |
| FOR_ITER_LIST | 20,420 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 19,480 | 0.0% | 100.0% |  |
| FOR_ITER | 19,360 | 0.0% | 100.0% |  |
| BEFORE_WITH | 18,100 | 0.0% | 100.0% |  |
| COMPARE_OP | 17,760 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 17,560 | 0.0% | 100.0% |  |
| BUILD_MAP | 17,380 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 17,060 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 16,280 | 0.0% | 100.0% | 18.8% |
| BINARY_SUBSCR_LIST_INT | 15,260 | 0.0% | 100.0% | 14.4% |
| BINARY_OP_ADD_UNICODE | 14,940 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 14,840 | 0.0% | 100.0% |  |
| CALL_KW | 14,640 | 0.0% | 100.0% |  |
| LIST_APPEND | 13,520 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 13,420 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 12,740 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 11,900 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 11,540 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 10,940 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 10,700 | 0.0% | 100.0% |  |
| RESUME | 9,280 | 0.0% | 100.0% | 123.1% |
| BUILD_STRING | 9,160 | 0.0% | 100.0% |  |
| MAKE_CELL | 8,320 | 0.0% | 100.0% |  |
| STORE_ATTR_SLOT | 8,040 | 0.0% | 100.0% | 0.7% |
| CHECK_EXC_MATCH | 7,980 | 0.0% | 100.0% |  |
| POP_EXCEPT | 7,980 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 7,980 | 0.0% | 100.0% |  |
| MAP_ADD | 7,680 | 0.0% | 100.0% |  |
| IMPORT_NAME | 7,140 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 7,060 | 0.0% | 100.0% |  |
| DICT_MERGE | 6,720 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 6,340 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 6,100 | 0.0% | 100.0% |  |
| LOAD_ATTR_PROPERTY | 5,800 | 0.0% | 100.0% |  |
| LIST_EXTEND | 5,480 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 5,420 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 5,340 | 0.0% | 100.0% |  |
| IMPORT_FROM | 4,900 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 4,460 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 4,340 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 4,140 | 0.0% | 100.0% |  |
| STORE_DEREF | 4,020 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 4,020 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,860 | 0.0% | 100.0% | 11.4% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 3,760 | 0.0% | 100.0% | 0.5% |
| UNPACK_SEQUENCE_TUPLE | 3,760 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 3,420 | 0.0% | 100.0% |  |
| CALL_STR_1 | 3,300 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 2,960 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 2,180 | 0.0% | 100.0% |  |
| RERAISE | 2,000 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 1,800 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 1,700 | 0.0% | 100.0% | 3.5% |
| BUILD_SLICE | 1,540 | 0.0% | 100.0% |  |
| UNARY_NOT | 1,520 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 1,360 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 1,220 | 0.0% | 100.0% |  |
| BUILD_SET | 1,100 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,060 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 740 | 0.0% | 100.0% |  |
| UNARY_INVERT | 720 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 620 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 540 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 540 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 480 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 400 | 0.0% | 100.0% |  |
| DELETE_NAME | 300 | 0.0% | 100.0% |  |
| DICT_UPDATE | 300 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 240 | 0.0% | 100.0% |  |
| STORE_SLICE | 160 | 0.0% | 100.0% |  |
| DELETE_FAST | 140 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 140 | 0.0% | 100.0% |  |
| LOAD_LOCALS | 100 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 100 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_2 | 80 | 0.0% | 100.0% |  |
| GET_AWAITABLE | 80 | 0.0% | 100.0% |  |
| LOAD_FROM_DICT_OR_DEREF | 80 | 0.0% | 100.0% |  |
| SET_UPDATE | 80 | 0.0% | 100.0% |  |
| END_FOR | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| SEND_GEN | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 141,669,020 | 6.4% | 6.4% |
| CACHE RESUME_CHECK | 141,577,220 | 6.4% | 12.8% |
| YIELD_VALUE INTERPRETER_EXIT | 125,521,160 | 5.7% | 18.4% |
| RESUME_CHECK POP_TOP | 125,521,160 | 5.7% | 24.1% |
| END_SEND STORE_FAST | 125,515,680 | 5.7% | 29.8% |
| SEND END_SEND | 125,515,680 | 5.7% | 35.4% |
| ENTER_EXECUTOR SEND | 125,514,720 | 5.7% | 41.1% |
| CALL_INTRINSIC_1 YIELD_VALUE | 120,273,200 | 5.4% | 46.5% |
| POP_TOP ENTER_EXECUTOR | 117,524,640 | 5.3% | 51.8% |
| LOAD_FAST CALL_INTRINSIC_1 | 117,515,680 | 5.3% | 57.1% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 74,947,840 | 3.4% | 60.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 42,933,740 | 1.9% | 62.4% |
| LOAD_FAST LOAD_CONST | 32,187,760 | 1.5% | 63.9% |
| RESUME_CHECK LOAD_FAST | 32,102,660 | 1.4% | 65.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 24,123,660 | 1.1% | 66.4% |
| RETURN_CONST INTERPRETER_EXIT | 24,068,060 | 1.1% | 67.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 24,058,660 | 1.1% | 68.6% |
| POP_TOP RETURN_CONST | 24,057,480 | 1.1% | 69.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 16,150,900 | 0.7% | 70.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 16,058,860 | 0.7% | 71.1% |
| LOAD_FAST CALL_LEN | 16,041,560 | 0.7% | 71.9% |
| LOAD_CONST COMPARE_OP_INT | 16,036,680 | 0.7% | 72.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 16,036,480 | 0.7% | 73.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 16,031,680 | 0.7% | 74.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 16,023,540 | 0.7% | 74.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 16,017,260 | 0.7% | 75.5% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 16,008,680 | 0.7% | 76.2% |
| CALL_LEN STORE_FAST | 16,005,340 | 0.7% | 76.9% |
| BINARY_SLICE CALL_PY_EXACT_ARGS | 16,002,980 | 0.7% | 77.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 13,268,420 | 0.6% | 78.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 8,134,740 | 0.4% | 78.6% |
| POP_TOP LOAD_FAST | 8,089,820 | 0.4% | 79.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 8,081,860 | 0.4% | 79.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 8,055,320 | 0.4% | 79.7% |
| LOAD_FAST PUSH_NULL | 8,055,160 | 0.4% | 80.1% |
| RETURN_CONST POP_TOP | 8,052,780 | 0.4% | 80.4% |
| LOAD_CONST LOAD_FAST | 8,052,040 | 0.4% | 80.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 8,040,040 | 0.4% | 81.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 8,039,260 | 0.4% | 81.5% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 8,033,980 | 0.4% | 81.9% |
| CALL STORE_FAST | 8,032,460 | 0.4% | 82.3% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 8,029,920 | 0.4% | 82.6% |
| LOAD_CONST BINARY_OP_ADD_INT | 8,023,680 | 0.4% | 83.0% |
| LOAD_FAST POP_JUMP_IF_NONE | 8,019,540 | 0.4% | 83.3% |
| LOAD_CONST BINARY_SLICE | 8,018,360 | 0.4% | 83.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 8,016,800 | 0.4% | 84.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 8,015,520 | 0.4% | 84.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 8,014,900 | 0.4% | 84.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 8,012,760 | 0.4% | 85.1% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 8,010,740 | 0.4% | 85.5% |
| RETURN_VALUE RETURN_VALUE | 8,010,600 | 0.4% | 85.9% |
| EXIT_INIT_CHECK RETURN_VALUE | 8,009,560 | 0.4% | 86.2% |
| RETURN_CONST EXIT_INIT_CHECK | 8,009,560 | 0.4% | 86.6% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 8,009,500 | 0.4% | 87.0% |
| PUSH_NULL CALL | 8,009,340 | 0.4% | 87.3% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 8,009,040 | 0.4% | 87.7% |
| TO_BOOL POP_JUMP_IF_FALSE | 8,008,560 | 0.4% | 88.0% |
| LOAD_CONST BINARY_OP | 8,006,860 | 0.4% | 88.4% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 8,006,160 | 0.4% | 88.8% |
| BINARY_OP STORE_FAST | 8,005,300 | 0.4% | 89.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 8,005,280 | 0.4% | 89.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 8,004,240 | 0.4% | 89.8% |
| CACHE POP_TOP | 8,003,800 | 0.4% | 90.2% |
| POP_TOP RESUME_CHECK | 8,003,700 | 0.4% | 90.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 8,003,520 | 0.4% | 90.9% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 8,003,260 | 0.4% | 91.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 8,002,480 | 0.4% | 91.7% |
| LOAD_FAST BINARY_SLICE | 8,002,260 | 0.4% | 92.0% |
| BINARY_OP_ADD_INT LOAD_CONST | 8,001,980 | 0.4% | 92.4% |
| STORE_FAST ENTER_EXECUTOR | 8,001,680 | 0.4% | 92.7% |
| LOAD_ATTR_INSTANCE_VALUE CALL | 8,001,680 | 0.4% | 93.1% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_FALSE | 8,001,040 | 0.4% | 93.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_ALWAYS_TRUE | 8,001,020 | 0.4% | 93.8% |
| LOAD_CONST SEND | 8,001,000 | 0.4% | 94.2% |
| GET_ANEXT LOAD_CONST | 8,000,960 | 0.4% | 94.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 8,000,580 | 0.4% | 94.9% |
| CALL CALL_METHOD_DESCRIPTOR_O | 8,000,340 | 0.4% | 95.3% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR | 8,000,040 | 0.4% | 95.6% |
| CACHE RETURN_GENERATOR | 8,000,000 | 0.4% | 96.0% |
| GET_AITER GET_ANEXT | 8,000,000 | 0.4% | 96.3% |
| RETURN_GENERATOR INTERPRETER_EXIT | 8,000,000 | 0.4% | 96.7% |
| SEND END_ASYNC_FOR | 8,000,000 | 0.4% | 97.1% |
| BINARY_SUBSCR LOAD_GLOBAL_MODULE | 7,999,960 | 0.4% | 97.4% |
| LOAD_ATTR_INSTANCE_VALUE GET_AITER | 7,999,880 | 0.4% | 97.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_NONE | 7,998,960 | 0.4% | 98.1% |
| ENTER_EXECUTOR YIELD_VALUE | 5,244,140 | 0.2% | 98.4% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 5,242,880 | 0.2% | 98.6% |
| RETURN_CONST CALL_ALLOC_AND_ENTER_INIT | 5,242,840 | 0.2% | 98.9% |
| END_ASYNC_FOR ENTER_EXECUTOR | 5,242,460 | 0.2% | 99.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_INTRINSIC_1 | 2,757,500 | 0.1% | 99.2% |
| END_ASYNC_FOR JUMP_BACKWARD | 2,757,460 | 0.1% | 99.3% |
| RETURN_CONST LOAD_FAST_LOAD_FAST | 2,757,200 | 0.1% | 99.5% |
| RETURN_VALUE CALL_ALLOC_AND_ENTER_INIT | 2,757,120 | 0.1% | 99.6% |
| JUMP_BACKWARD RETURN_CONST | 2,757,120 | 0.1% | 99.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 100,200 | 0.0% | 99.7% |
| LOAD_CONST LOAD_CONST | 99,740 | 0.0% | 99.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 97,520 | 0.0% | 99.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 79,380 | 0.0% | 99.7% |
| TO_BOOL_ALWAYS_TRUE TO_BOOL_NONE | 68,860 | 0.0% | 99.7% |
| TO_BOOL_NONE TO_BOOL_ALWAYS_TRUE | 68,840 | 0.0% | 99.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,018,360 | 50.0% |
| LOAD_FAST | 8,002,260 | 49.9% |
| BINARY_OP_ADD_INT | 460 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 16,002,980 | 99.9% |
| LOAD_FAST | 4,680 | 0.0% |
| SWAP | 4,680 | 0.0% |
| STORE_FAST | 4,180 | 0.0% |
| BUILD_TUPLE | 2,000 | 0.0% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 120 | 75.0% |
| LOAD_CONST | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 120 | 75.0% |
| LOAD_FAST | 40 | 25.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 141,577,220 | 89.8% |
| POP_TOP | 8,003,800 | 5.1% |
| RETURN_GENERATOR | 8,000,000 | 5.1% |
| COPY_FREE_VARS | 30,880 | 0.0% |
| RESUME | 5,320 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,400 | 40.9% |
| RETURN_VALUE | 4,920 | 27.2% |
| CALL | 4,660 | 25.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,000 | 5.5% |
| LOAD_GLOBAL | 100 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 17,100 | 94.5% |
| STORE_FAST | 1,000 | 5.5% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 1,640 | 75.2% |
| LOAD_FAST_LOAD_FAST | 500 | 22.9% |
| RETURN_VALUE | 20 | 0.9% |
| BINARY_OP | 20 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,680 | 77.1% |
| ENTER_EXECUTOR | 500 | 22.9% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,000,040 | 99.8% |
| LOAD_CONST | 7,400 | 0.1% |
| BINARY_SUBSCR | 2,340 | 0.0% |
| BUILD_SLICE | 1,540 | 0.0% |
| LOAD_FAST | 980 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,999,960 | 99.8% |
| SWAP | 4,700 | 0.1% |
| BINARY_SUBSCR | 2,340 | 0.0% |
| GET_ITER | 1,320 | 0.0% |
| LOAD_CONST | 1,320 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 7,920 | 99.2% |
| LOAD_GLOBAL | 40 | 0.5% |
| LOAD_NAME | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,980 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,220 | 100.0% |


</details>

### END_ASYNC_FOR

<details>
<summary> Successors and predecessors for END_ASYNC_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 8,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,242,460 | 65.5% |
| JUMP_BACKWARD | 2,757,460 | 34.5% |
| RETURN_CONST | 80 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 125,515,680 | 100.0% |
| RETURN_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 125,515,680 | 100.0% |
| POP_TOP | 80 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,009,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,009,560 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 5,340 | 46.3% |
| LOAD_FAST | 3,760 | 32.6% |
| LOAD_ATTR | 1,620 | 14.0% |
| LOAD_ATTR_MODULE | 360 | 3.1% |
| STORE_FAST_LOAD_FAST | 300 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,120 | 87.7% |
| BUILD_STRING | 1,380 | 12.0% |
| LOAD_FAST | 40 | 0.3% |


</details>

### GET_AITER

<details>
<summary> Successors and predecessors for GET_AITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,999,880 | 100.0% |
| RETURN_VALUE | 80 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ANEXT | 8,000,000 | 100.0% |


</details>

### GET_ANEXT

<details>
<summary> Successors and predecessors for GET_ANEXT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_AITER | 8,000,000 | 100.0% |
| JUMP_BACKWARD | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,000,960 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,020 | 59.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,300 | 10.7% |
| LOAD_GLOBAL_MODULE | 2,000 | 5.0% |
| BUILD_TUPLE | 1,380 | 3.4% |
| BINARY_SUBSCR | 1,320 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 10,480 | 26.0% |
| FOR_ITER_LIST | 8,560 | 21.2% |
| FOR_ITER_TUPLE | 7,620 | 18.9% |
| EXTENDED_ARG | 5,540 | 13.7% |
| CALL_PY_EXACT_ARGS | 3,360 | 8.3% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 125,521,160 | 79.6% |
| RETURN_CONST | 24,068,060 | 15.3% |
| RETURN_GENERATOR | 8,000,000 | 5.1% |
| RETURN_VALUE | 26,880 | 0.0% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 3,540 | 85.5% |
| POP_TOP | 200 | 4.8% |
| LOAD_NAME | 120 | 2.9% |
| RETURN_VALUE | 100 | 2.4% |
| DELETE_NAME | 60 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 4,140 | 100.0% |


</details>

### LOAD_LOCALS

<details>
<summary> Successors and predecessors for LOAD_LOCALS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 60 | 60.0% |
| LOAD_CONST | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FROM_DICT_OR_DEREF | 80 | 80.0% |
| STORE_DEREF | 20 | 20.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 50,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 25,760 | 51.2% |
| SET_FUNCTION_ATTRIBUTE | 16,040 | 31.9% |
| LOAD_CONST | 4,260 | 8.5% |
| CALL | 2,060 | 4.1% |
| LOAD_FAST | 760 | 1.5% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,700 | 35.0% |
| POP_TOP | 14,380 | 17.5% |
| RESUME_CHECK | 6,740 | 8.2% |
| NOP | 6,400 | 7.8% |
| POP_JUMP_IF_FALSE | 6,320 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,880 | 49.9% |
| LOAD_GLOBAL_MODULE | 18,660 | 22.8% |
| LOAD_CONST | 9,880 | 12.1% |
| NOP | 6,400 | 7.8% |
| LOAD_FAST_LOAD_FAST | 4,160 | 5.1% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,960 | 62.2% |
| COPY | 1,040 | 13.0% |
| POP_TOP | 640 | 8.0% |
| JUMP_FORWARD | 620 | 7.8% |
| POP_JUMP_IF_FALSE | 240 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,920 | 61.7% |
| RERAISE | 1,040 | 13.0% |
| EXTENDED_ARG | 1,020 | 12.8% |
| RETURN_CONST | 540 | 6.8% |
| JUMP_FORWARD | 240 | 3.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 125,521,160 | 79.6% |
| CALL_METHOD_DESCRIPTOR_O | 16,008,680 | 10.1% |
| RETURN_CONST | 8,052,780 | 5.1% |
| CACHE | 8,003,800 | 5.1% |
| CALL | 54,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 117,524,640 | 74.5% |
| RETURN_CONST | 24,057,480 | 15.2% |
| LOAD_FAST | 8,089,820 | 5.1% |
| RESUME_CHECK | 8,003,700 | 5.1% |
| LOAD_GLOBAL_BUILTIN | 20,640 | 0.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 6,260 | 78.4% |
| RERAISE | 1,040 | 13.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 300 | 3.8% |
| BINARY_SUBSCR_STR_INT | 240 | 3.0% |
| CALL_PY_EXACT_ARGS | 60 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 7,900 | 99.0% |
| LOAD_GLOBAL | 60 | 0.8% |
| LOAD_NAME | 20 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,055,160 | 99.4% |
| LOAD_ATTR_MODULE | 18,740 | 0.2% |
| LOAD_ATTR | 4,960 | 0.1% |
| LOAD_DEREF | 4,940 | 0.1% |
| LOAD_NAME | 4,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 8,009,340 | 98.9% |
| LOAD_FAST | 46,900 | 0.6% |
| LOAD_CONST | 17,080 | 0.2% |
| LOAD_FAST_LOAD_FAST | 11,100 | 0.1% |
| LOAD_GLOBAL_MODULE | 8,060 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 8,000,000 | 100.0% |
| COPY_FREE_VARS | 2,800 | 0.0% |
| CALL_PY_EXACT_ARGS | 1,020 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 8,000,000 | 100.0% |
| CALL | 2,340 | 0.0% |
| CALL_TUPLE_1 | 620 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 0.0% |
| CALL_BUILTIN_O | 320 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,010,600 | 49.5% |
| EXIT_INIT_CHECK | 8,009,560 | 49.5% |
| LOAD_FAST | 54,800 | 0.3% |
| CALL | 20,280 | 0.1% |
| POP_JUMP_IF_FALSE | 14,340 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,010,600 | 49.5% |
| LOAD_FAST_LOAD_FAST | 5,242,880 | 32.4% |
| CALL_ALLOC_AND_ENTER_INIT | 2,757,120 | 17.0% |
| STORE_FAST | 53,520 | 0.3% |
| TO_BOOL_BOOL | 42,940 | 0.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,760 | 45.2% |
| LOAD_FAST | 1,080 | 17.7% |
| LOAD_CONST | 1,060 | 17.4% |
| BINARY_OP | 580 | 9.5% |
| STORE_SUBSCR | 320 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 1,320 | 21.6% |
| LOAD_FAST | 1,240 | 20.3% |
| RETURN_CONST | 960 | 15.7% |
| EXTENDED_ARG | 840 | 13.8% |
| JUMP_BACKWARD | 820 | 13.4% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,004,240 | 99.9% |
| LOAD_FAST | 4,020 | 0.1% |
| TO_BOOL | 2,380 | 0.0% |
| CALL | 1,400 | 0.0% |
| LOAD_ATTR | 800 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,008,560 | 99.9% |
| TO_BOOL | 2,380 | 0.0% |
| POP_JUMP_IF_TRUE | 2,060 | 0.0% |
| TO_BOOL_BOOL | 1,880 | 0.0% |
| TO_BOOL_INT | 340 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 520 | 72.2% |
| BINARY_OP | 80 | 11.1% |
| LOAD_ATTR_MODULE | 60 | 8.3% |
| LOAD_FAST_LOAD_FAST | 40 | 5.6% |
| LOAD_ATTR | 20 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 720 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 240 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,180 | 77.6% |
| TO_BOOL_LIST | 240 | 15.8% |
| TO_BOOL_BOOL | 60 | 3.9% |
| TO_BOOL | 40 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,000 | 65.8% |
| STORE_FAST | 280 | 18.4% |
| CALL_PY_EXACT_ARGS | 240 | 15.8% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,006,860 | 99.7% |
| LOAD_GLOBAL_MODULE | 11,420 | 0.1% |
| BINARY_OP | 3,780 | 0.0% |
| LOAD_FAST_LOAD_FAST | 2,300 | 0.0% |
| BUILD_TUPLE | 1,540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,005,300 | 99.7% |
| TO_BOOL_INT | 11,760 | 0.1% |
| BINARY_OP | 3,780 | 0.0% |
| LOAD_FAST | 2,060 | 0.0% |
| LOAD_CONST | 1,880 | 0.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,260 | 41.7% |
| STORE_FAST | 1,600 | 29.5% |
| RETURN_VALUE | 1,000 | 18.5% |
| STORE_NAME | 240 | 4.4% |
| LOAD_FAST | 140 | 2.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 10,260 | 26.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,800 | 12.2% |
| STORE_ATTR_INSTANCE_VALUE | 4,120 | 10.5% |
| RESUME_CHECK | 4,040 | 10.3% |
| LOAD_FAST | 3,700 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 10,260 | 26.1% |
| LOAD_FAST | 10,180 | 25.9% |
| STORE_FAST | 9,980 | 25.4% |
| COMPARE_OP | 4,800 | 12.2% |
| CALL_METHOD_DESCRIPTOR_O | 2,060 | 5.2% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,140 | 41.1% |
| LOAD_FAST | 4,220 | 24.3% |
| CALL_INTRINSIC_1 | 1,000 | 5.8% |
| BUILD_TUPLE | 940 | 5.4% |
| STORE_FAST | 920 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,580 | 43.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 5,960 | 34.3% |
| STORE_FAST | 780 | 4.5% |
| LOAD_GLOBAL_BUILTIN | 600 | 3.5% |
| CALL_BUILTIN_FAST | 560 | 3.2% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 600 | 54.5% |
| LOAD_CONST | 260 | 23.6% |
| LOAD_GLOBAL_MODULE | 140 | 12.7% |
| PUSH_NULL | 80 | 7.3% |
| LOAD_GLOBAL | 20 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 760 | 69.1% |
| BINARY_OP | 200 | 18.2% |
| LOAD_CONST | 80 | 7.3% |
| STORE_FAST | 60 | 5.5% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 1,540 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,780 | 84.9% |
| FORMAT_SIMPLE | 1,380 | 15.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,400 | 59.0% |
| LOAD_FAST | 1,920 | 21.0% |
| LOAD_CONST | 600 | 6.6% |
| LIST_APPEND | 340 | 3.7% |
| CALL | 300 | 3.3% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,140 | 40.6% |
| LOAD_GLOBAL_MODULE | 5,000 | 10.6% |
| LOAD_FAST_LOAD_FAST | 4,800 | 10.2% |
| CALL_BUILTIN_O | 2,940 | 6.2% |
| CALL | 2,380 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,740 | 22.8% |
| STORE_FAST | 6,580 | 14.0% |
| RETURN_VALUE | 6,080 | 12.9% |
| LOAD_FAST | 3,600 | 7.6% |
| CONTAINS_OP | 3,200 | 6.8% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 8,009,340 | 49.4% |
| LOAD_ATTR_INSTANCE_VALUE | 8,001,680 | 49.4% |
| LOAD_CONST | 46,600 | 0.3% |
| LOAD_FAST | 29,480 | 0.2% |
| LOAD_ATTR_MODULE | 29,020 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,032,460 | 49.6% |
| CALL_METHOD_DESCRIPTOR_O | 8,000,340 | 49.4% |
| POP_TOP | 54,820 | 0.3% |
| RESUME_CHECK | 25,600 | 0.2% |
| RETURN_VALUE | 20,280 | 0.1% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 6,720 | 52.7% |
| CALL_INTRINSIC_1 | 3,520 | 27.6% |
| LOAD_FAST | 1,560 | 12.2% |
| STORE_FAST | 480 | 3.8% |
| ENTER_EXECUTOR | 340 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,420 | 34.7% |
| RETURN_VALUE | 3,920 | 30.8% |
| POP_TOP | 1,920 | 15.1% |
| RESUME_CHECK | 1,220 | 9.6% |
| GET_ITER | 480 | 3.8% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,515,680 | 97.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,757,500 | 2.3% |
| LIST_EXTEND | 4,700 | 0.0% |
| IMPORT_NAME | 420 | 0.0% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 120,273,200 | 100.0% |
| CALL_FUNCTION_EX | 3,520 | 0.0% |
| BUILD_MAP | 1,000 | 0.0% |
| POP_TOP | 420 | 0.0% |
| GET_ITER | 160 | 0.0% |


</details>

### CALL_INTRINSIC_2

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_2 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 75.0% |
| MAKE_FUNCTION | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 75.0% |
| COPY | 20 | 25.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,980 | 75.0% |
| STORE_FAST | 1,400 | 9.6% |
| STORE_NAME | 740 | 5.1% |
| RETURN_VALUE | 620 | 4.2% |
| MAKE_CELL | 360 | 2.5% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,600 | 37.2% |
| BUILD_LIST | 4,800 | 27.0% |
| LOAD_GLOBAL_MODULE | 2,700 | 15.2% |
| LOAD_CONST | 1,540 | 8.7% |
| BINARY_OP | 1,000 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,200 | 68.7% |
| POP_JUMP_IF_TRUE | 4,240 | 23.9% |
| COMPARE_OP | 400 | 2.3% |
| COMPARE_OP_INT | 400 | 2.3% |
| COMPARE_OP_STR | 380 | 2.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 21,480 | 30.4% |
| LOAD_FAST_LOAD_FAST | 17,020 | 24.1% |
| LOAD_FAST | 11,580 | 16.4% |
| LOAD_CONST | 7,220 | 10.2% |
| LOAD_ATTR_MODULE | 3,880 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 52,060 | 73.6% |
| POP_JUMP_IF_TRUE | 11,480 | 16.2% |
| EXTENDED_ARG | 4,920 | 7.0% |
| STORE_FAST | 1,380 | 2.0% |
| RETURN_VALUE | 720 | 1.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,200 | 97.4% |
| LOAD_GLOBAL_MODULE | 120 | 2.2% |
| LOAD_GLOBAL | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 5,340 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_STR | 10,820 | 14.2% |
| CALL | 9,980 | 13.1% |
| COMPARE_OP_INT | 9,700 | 12.8% |
| SWAP | 9,360 | 12.3% |
| CALL_BUILTIN_FAST | 8,360 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 49,460 | 65.1% |
| COMPARE_OP_STR | 9,360 | 12.3% |
| TO_BOOL_STR | 5,240 | 6.9% |
| TO_BOOL_NONE | 3,800 | 5.0% |
| STORE_FAST_STORE_FAST | 2,120 | 2.8% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 30,880 | 84.4% |
| CALL_PY_EXACT_ARGS | 3,560 | 9.7% |
| CALL | 1,560 | 4.3% |
| CALL_FUNCTION_EX | 300 | 0.8% |
| ENTER_EXECUTOR | 120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 32,900 | 89.9% |
| RETURN_GENERATOR | 2,800 | 7.7% |
| RESUME | 460 | 1.3% |
| MAKE_CELL | 440 | 1.2% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 120 | 85.7% |
| POP_TOP | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 100 | 71.4% |
| LOAD_GLOBAL | 40 | 28.6% |


</details>

### DELETE_NAME

<details>
<summary> Successors and predecessors for DELETE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 120 | 40.0% |
| STORE_NAME | 100 | 33.3% |
| ENTER_EXECUTOR | 40 | 13.3% |
| POP_TOP | 20 | 6.7% |
| FOR_ITER | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 120 | 40.0% |
| LOAD_NAME | 80 | 26.7% |
| LOAD_BUILD_CLASS | 60 | 20.0% |
| LOAD_CONST | 40 | 13.3% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,120 | 91.1% |
| CALL | 600 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 6,720 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 220 | 73.3% |
| BUILD_CONST_KEY_MAP | 60 | 20.0% |
| BUILD_MAP | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 160 | 53.3% |
| STORE_NAME | 80 | 26.7% |
| EXTENDED_ARG | 20 | 6.7% |
| LOAD_CONST | 20 | 6.7% |
| LOAD_NAME | 20 | 6.7% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 117,524,640 | 89.8% |
| STORE_FAST | 8,001,680 | 6.1% |
| END_ASYNC_FOR | 5,242,460 | 4.0% |
| POP_JUMP_IF_FALSE | 26,300 | 0.0% |
| EXTENDED_ARG | 16,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 125,514,720 | 95.9% |
| YIELD_VALUE | 5,244,140 | 4.0% |
| CALL | 16,720 | 0.0% |
| FOR_ITER_TUPLE | 16,220 | 0.0% |
| CALL_PY_EXACT_ARGS | 14,760 | 0.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,540 | 10.8% |
| POP_TOP | 5,220 | 10.2% |
| JUMP_FORWARD | 5,200 | 10.2% |
| CONTAINS_OP | 4,920 | 9.6% |
| COMPARE_OP_STR | 4,380 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 16,560 | 32.4% |
| POP_JUMP_IF_FALSE | 12,940 | 25.3% |
| FOR_ITER_LIST | 6,100 | 11.9% |
| JUMP_FORWARD | 5,700 | 11.1% |
| FOR_ITER | 4,360 | 8.5% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,720 | 39.9% |
| EXTENDED_ARG | 4,360 | 22.5% |
| GET_ITER | 2,960 | 15.3% |
| LOAD_FAST | 2,360 | 12.2% |
| FOR_ITER | 1,540 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,960 | 41.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 5,500 | 28.4% |
| RETURN_CONST | 1,580 | 8.2% |
| FOR_ITER | 1,540 | 8.0% |
| STORE_NAME | 720 | 3.7% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 2,980 | 60.8% |
| STORE_NAME | 1,920 | 39.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 4,860 | 99.2% |
| PUSH_EXC_INFO | 20 | 0.4% |
| STORE_FAST | 20 | 0.4% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 3,660 | 51.3% |
| IMPORT_FROM | 2,980 | 41.7% |
| CALL_INTRINSIC_1 | 420 | 5.9% |
| STORE_FAST | 80 | 1.1% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 35,160 | 75.5% |
| LOAD_GLOBAL_BUILTIN | 5,580 | 12.0% |
| LOAD_CONST | 4,000 | 8.6% |
| LOAD_FAST | 1,480 | 3.2% |
| LOAD_GLOBAL | 180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 36,840 | 79.1% |
| POP_JUMP_IF_TRUE | 5,580 | 12.0% |
| LOAD_FAST | 3,100 | 6.7% |
| RETURN_VALUE | 400 | 0.9% |
| COPY | 300 | 0.6% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| END_ASYNC_FOR | 2,757,460 | 99.3% |
| POP_TOP | 4,460 | 0.2% |
| POP_JUMP_IF_TRUE | 2,840 | 0.1% |
| LIST_APPEND | 2,440 | 0.1% |
| POP_JUMP_IF_FALSE | 1,760 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,757,120 | 99.3% |
| FOR_ITER | 7,720 | 0.3% |
| FOR_ITER_TUPLE | 5,120 | 0.2% |
| FOR_ITER_LIST | 1,760 | 0.1% |
| ENTER_EXECUTOR | 1,160 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,380 | 43.0% |
| EXTENDED_ARG | 5,700 | 18.3% |
| POP_TOP | 3,300 | 10.6% |
| LOAD_FAST | 2,000 | 6.4% |
| COMPARE_OP_STR | 1,640 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,920 | 44.7% |
| LOAD_GLOBAL_BUILTIN | 5,280 | 17.0% |
| EXTENDED_ARG | 5,200 | 16.7% |
| LOAD_FAST_LOAD_FAST | 2,360 | 7.6% |
| COPY | 1,640 | 5.3% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 9,200 | 68.0% |
| BUILD_TUPLE | 1,900 | 14.1% |
| LOAD_FAST | 1,420 | 10.5% |
| LOAD_ATTR_INSTANCE_VALUE | 400 | 3.0% |
| BUILD_STRING | 340 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 11,080 | 82.0% |
| JUMP_BACKWARD | 2,440 | 18.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,380 | 79.9% |
| LOAD_CONST | 600 | 10.9% |
| LOAD_ATTR | 180 | 3.3% |
| LOAD_ATTR_SLOT | 140 | 2.6% |
| CALL_KW | 80 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 4,700 | 85.8% |
| STORE_NAME | 240 | 4.4% |
| LOAD_FAST | 160 | 2.9% |
| LOAD_CONST | 140 | 2.6% |
| BUILD_LIST | 120 | 2.2% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,420 | 59.0% |
| LOAD_ATTR_INSTANCE_VALUE | 7,980 | 7.3% |
| LOAD_FAST_LOAD_FAST | 7,880 | 7.2% |
| LOAD_NAME | 6,720 | 6.2% |
| LOAD_ATTR | 5,520 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,600 | 20.7% |
| STORE_FAST | 18,940 | 17.4% |
| CALL | 12,160 | 11.1% |
| LOAD_ATTR_METHOD_NO_DICT | 10,200 | 9.3% |
| LOAD_ATTR | 5,520 | 5.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,187,760 | 56.8% |
| LOAD_FAST_LOAD_FAST | 8,006,160 | 14.1% |
| BINARY_OP_ADD_INT | 8,001,980 | 14.1% |
| GET_ANEXT | 8,000,960 | 14.1% |
| LOAD_CONST | 99,740 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 16,036,680 | 28.3% |
| LOAD_FAST | 8,052,040 | 14.2% |
| BINARY_OP_ADD_INT | 8,023,680 | 14.2% |
| BINARY_SLICE | 8,018,360 | 14.2% |
| BINARY_OP | 8,006,860 | 14.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 30,000 | 56.2% |
| POP_JUMP_IF_FALSE | 6,300 | 11.8% |
| RESUME_CHECK | 3,760 | 7.0% |
| STORE_FAST | 3,260 | 6.1% |
| BINARY_SLICE | 2,000 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,660 | 57.4% |
| PUSH_NULL | 4,940 | 9.3% |
| LOAD_CONST | 3,740 | 7.0% |
| TO_BOOL_BOOL | 2,700 | 5.1% |
| LOAD_ATTR_METHOD_NO_DICT | 2,220 | 4.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 141,669,020 | 50.3% |
| POP_JUMP_IF_FALSE | 42,933,740 | 15.2% |
| RESUME_CHECK | 32,102,660 | 11.4% |
| LOAD_GLOBAL_BUILTIN | 16,150,900 | 5.7% |
| POP_TOP | 8,089,820 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 117,515,680 | 41.7% |
| LOAD_ATTR_INSTANCE_VALUE | 74,947,840 | 26.6% |
| LOAD_CONST | 32,187,760 | 11.4% |
| CALL_LEN | 16,041,560 | 5.7% |
| CALL_PY_EXACT_ARGS | 8,055,320 | 2.9% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,480 | 97.9% |
| LOAD_FAST_AND_CLEAR | 220 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 10,480 | 97.9% |
| LOAD_FAST_AND_CLEAR | 220 | 2.1% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,660 | 73.5% |
| LOAD_ATTR_METHOD_NO_DICT | 800 | 12.6% |
| LOAD_FAST | 620 | 9.8% |
| LOAD_GLOBAL_BUILTIN | 120 | 1.9% |
| POP_JUMP_IF_FALSE | 80 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 4,740 | 74.8% |
| LOAD_FAST | 620 | 9.8% |
| CALL_LIST_APPEND | 620 | 9.8% |
| LOAD_ATTR | 180 | 2.8% |
| LOAD_GLOBAL_BUILTIN | 120 | 1.9% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 16,031,680 | 33.2% |
| LOAD_GLOBAL_MODULE | 16,023,540 | 33.2% |
| RESUME_CHECK | 8,029,920 | 16.6% |
| RETURN_VALUE | 5,242,880 | 10.9% |
| RETURN_CONST | 2,757,200 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 24,058,660 | 49.9% |
| LOAD_ATTR_INSTANCE_VALUE | 8,014,900 | 16.6% |
| LOAD_CONST | 8,006,160 | 16.6% |
| BINARY_SUBSCR | 8,000,040 | 16.6% |
| LOAD_FAST | 30,340 | 0.1% |


</details>

### LOAD_FROM_DICT_OR_DEREF

<details>
<summary> Successors and predecessors for LOAD_FROM_DICT_OR_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_LOCALS | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 40 | 50.0% |
| STORE_NAME | 40 | 50.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,460 | 16.6% |
| POP_JUMP_IF_FALSE | 2,060 | 13.9% |
| STORE_FAST | 1,620 | 10.9% |
| RESUME | 1,440 | 9.7% |
| RESUME_CHECK | 1,120 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,840 | 25.9% |
| LOAD_GLOBAL_BUILTIN | 3,040 | 20.5% |
| LOAD_FAST | 2,780 | 18.7% |
| LOAD_ATTR | 1,280 | 8.6% |
| CALL | 860 | 5.8% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 13,940 | 29.0% |
| LOAD_NAME | 8,180 | 17.0% |
| LOAD_CONST | 7,240 | 15.0% |
| RESUME | 4,140 | 8.6% |
| STORE_FAST | 3,660 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,060 | 18.8% |
| LOAD_NAME | 8,180 | 17.0% |
| LOAD_ATTR | 6,720 | 14.0% |
| STORE_NAME | 5,600 | 11.6% |
| PUSH_NULL | 4,440 | 9.2% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 700 | 94.6% |
| LOAD_DEREF | 40 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 240 | 32.4% |
| CALL | 140 | 18.9% |
| PUSH_NULL | 100 | 13.5% |
| LOAD_FAST_LOAD_FAST | 100 | 13.5% |
| LOAD_SUPER_ATTR_ATTR | 100 | 13.5% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 3,140 | 37.7% |
| CALL_PY_EXACT_ARGS | 2,180 | 26.2% |
| CACHE | 1,500 | 18.0% |
| CALL | 700 | 8.4% |
| COPY_FREE_VARS | 440 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,900 | 46.9% |
| MAKE_CELL | 3,140 | 37.7% |
| RESUME | 1,280 | 15.4% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,080 | 53.1% |
| LOAD_FAST_LOAD_FAST | 1,480 | 19.3% |
| LOAD_NAME | 680 | 8.9% |
| LOAD_FAST | 540 | 7.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 320 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,260 | 42.4% |
| EXTENDED_ARG | 1,560 | 20.3% |
| ENTER_EXECUTOR | 1,520 | 19.8% |
| JUMP_BACKWARD | 1,060 | 13.8% |
| DICT_UPDATE | 220 | 2.9% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 16,036,480 | 28.4% |
| TO_BOOL_BOOL | 8,134,740 | 14.4% |
| TO_BOOL_NONE | 8,010,740 | 14.2% |
| TO_BOOL | 8,008,560 | 14.2% |
| TO_BOOL_LIST | 8,003,260 | 14.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,933,740 | 76.1% |
| RETURN_CONST | 13,268,420 | 23.5% |
| LOAD_GLOBAL_MODULE | 34,620 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 32,140 | 0.1% |
| POP_TOP | 26,360 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,019,540 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 7,780 | 0.1% |
| LOAD_GLOBAL_MODULE | 3,020 | 0.0% |
| LOAD_ATTR_MODULE | 2,060 | 0.0% |
| RETURN_VALUE | 1,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,016,800 | 99.8% |
| LOAD_GLOBAL_MODULE | 6,460 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 5,160 | 0.1% |
| LOAD_CONST | 2,720 | 0.0% |
| NOP | 1,100 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,580 | 62.6% |
| LOAD_ATTR_INSTANCE_VALUE | 8,060 | 13.1% |
| CALL_BUILTIN_FAST | 7,080 | 11.5% |
| LOAD_FAST_CHECK | 4,740 | 7.7% |
| LOAD_GLOBAL_MODULE | 2,200 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,420 | 54.2% |
| LOAD_GLOBAL_MODULE | 10,960 | 17.8% |
| ENTER_EXECUTOR | 4,740 | 7.7% |
| NOP | 4,000 | 6.5% |
| LOAD_CONST | 2,400 | 3.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 67,480 | 56.9% |
| CONTAINS_OP | 11,480 | 9.7% |
| TO_BOOL_INT | 7,580 | 6.4% |
| COMPARE_OP_INT | 7,060 | 6.0% |
| IS_OP | 5,580 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,720 | 31.0% |
| LOAD_GLOBAL_BUILTIN | 18,260 | 15.4% |
| ENTER_EXECUTOR | 14,880 | 12.5% |
| LOAD_GLOBAL_MODULE | 14,020 | 11.8% |
| POP_TOP | 12,620 | 10.6% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 400 | 74.1% |
| LOAD_CONST | 80 | 14.8% |
| CALL_KW | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 80 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 1,040 | 52.0% |
| POP_JUMP_IF_FALSE | 960 | 48.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,040 | 52.0% |
| COPY | 960 | 48.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 24,057,480 | 50.0% |
| POP_JUMP_IF_FALSE | 13,268,420 | 27.6% |
| STORE_ATTR_INSTANCE_VALUE | 8,033,980 | 16.7% |
| JUMP_BACKWARD | 2,757,120 | 5.7% |
| RESUME_CHECK | 7,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 24,068,060 | 50.0% |
| POP_TOP | 8,052,780 | 16.7% |
| EXIT_INIT_CHECK | 8,009,560 | 16.6% |
| CALL_ALLOC_AND_ENTER_INIT | 5,242,840 | 10.9% |
| LOAD_FAST_LOAD_FAST | 2,757,200 | 5.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 125,514,720 | 94.0% |
| LOAD_CONST | 8,001,000 | 6.0% |
| SEND | 33,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 125,515,680 | 94.0% |
| END_ASYNC_FOR | 8,000,000 | 6.0% |
| SEND | 33,180 | 0.0% |
| POP_TOP | 20 | 0.0% |
| SEND_GEN | 20 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 16,040 | 91.3% |
| SET_FUNCTION_ATTRIBUTE | 1,520 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 8,000 | 45.6% |
| STORE_FAST | 3,380 | 19.2% |
| LOAD_GLOBAL_MODULE | 2,000 | 11.4% |
| CALL | 1,740 | 9.9% |
| SET_FUNCTION_ATTRIBUTE | 1,520 | 8.7% |


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,280 | 65.9% |
| LOAD_FAST_LOAD_FAST | 8,060 | 22.8% |
| STORE_ATTR | 2,080 | 5.9% |
| SWAP | 580 | 1.6% |
| LOAD_DEREF | 380 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,400 | 52.1% |
| RETURN_CONST | 3,520 | 10.0% |
| LOAD_CONST | 2,720 | 7.7% |
| LOAD_FAST_LOAD_FAST | 2,600 | 7.4% |
| STORE_ATTR | 2,080 | 5.9% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 1,200 | 29.9% |
| LOAD_ATTR | 520 | 12.9% |
| CALL_BUILTIN_CLASS | 380 | 9.5% |
| LOAD_CONST | 300 | 7.5% |
| BINARY_OP_ADD_UNICODE | 300 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,320 | 32.8% |
| STORE_DEREF | 1,200 | 29.9% |
| LOAD_FAST | 340 | 8.5% |
| LOAD_CONST | 300 | 7.5% |
| LOAD_DEREF | 300 | 7.5% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 125,515,680 | 79.5% |
| CALL_LEN | 16,005,340 | 10.1% |
| CALL | 8,032,460 | 5.1% |
| BINARY_OP | 8,005,300 | 5.1% |
| RETURN_VALUE | 53,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 141,669,020 | 89.7% |
| LOAD_GLOBAL_MODULE | 8,039,260 | 5.1% |
| ENTER_EXECUTOR | 8,001,680 | 5.1% |
| LOAD_GLOBAL_BUILTIN | 38,700 | 0.0% |
| NOP | 28,700 | 0.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 10,180 | 75.9% |
| CALL_LEN | 2,340 | 17.4% |
| FOR_ITER_LIST | 820 | 6.1% |
| FOR_ITER | 60 | 0.4% |
| COPY | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 9,200 | 68.6% |
| PUSH_NULL | 2,340 | 17.4% |
| LOAD_FAST | 1,100 | 8.2% |
| FORMAT_SIMPLE | 300 | 2.2% |
| LOAD_DEREF | 180 | 1.3% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 16,740 | 77.7% |
| UNPACK_SEQUENCE_TUPLE | 2,380 | 11.0% |
| COPY | 2,120 | 9.8% |
| UNPACK_SEQUENCE | 180 | 0.8% |
| STORE_FAST_STORE_FAST | 120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,780 | 50.0% |
| LOAD_FAST_LOAD_FAST | 4,180 | 19.4% |
| NOP | 2,520 | 11.7% |
| STORE_FAST | 2,260 | 10.5% |
| LOAD_GLOBAL_BUILTIN | 620 | 2.9% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 40.0% |
| LOAD_NAME | 40 | 40.0% |
| CALL | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 60.0% |
| LOAD_BUILD_CLASS | 20 | 20.0% |
| LOAD_NAME | 20 | 20.0% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 25,760 | 31.6% |
| LOAD_CONST | 15,180 | 18.6% |
| SET_FUNCTION_ATTRIBUTE | 8,000 | 9.8% |
| CALL | 7,640 | 9.4% |
| LOAD_NAME | 5,600 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 49,180 | 60.3% |
| LOAD_NAME | 13,940 | 17.1% |
| RETURN_CONST | 3,960 | 4.9% |
| LOAD_BUILD_CLASS | 3,540 | 4.3% |
| POP_TOP | 2,940 | 3.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 10,480 | 19.0% |
| BUILD_LIST | 10,260 | 18.6% |
| FOR_ITER_TUPLE | 9,700 | 17.6% |
| POP_JUMP_IF_FALSE | 7,720 | 14.0% |
| BINARY_SUBSCR | 4,700 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 11,560 | 20.9% |
| STORE_FAST | 10,280 | 18.6% |
| BUILD_LIST | 10,260 | 18.6% |
| FOR_ITER_TUPLE | 9,660 | 17.5% |
| COPY | 9,360 | 17.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 320 | 51.6% |
| LOAD_FAST | 120 | 19.4% |
| RETURN_VALUE | 100 | 16.1% |
| CALL | 40 | 6.5% |
| STORE_FAST | 40 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 320 | 51.6% |
| STORE_FAST_STORE_FAST | 180 | 29.0% |
| STORE_NAME | 60 | 9.7% |
| STORE_FAST | 40 | 6.5% |
| LOAD_FAST | 20 | 3.2% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 120,273,200 | 95.8% |
| ENTER_EXECUTOR | 5,244,140 | 4.2% |
| CALL | 2,020 | 0.0% |
| LOAD_FAST | 680 | 0.0% |
| RETURN_VALUE | 620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 125,521,160 | 100.0% |
| STORE_FAST | 420 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 5,320 | 57.3% |
| CALL | 1,700 | 18.3% |
| MAKE_CELL | 1,280 | 13.8% |
| COPY_FREE_VARS | 460 | 5.0% |
| POP_TOP | 240 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 4,140 | 44.6% |
| LOAD_CONST | 1,620 | 17.5% |
| LOAD_FAST | 1,460 | 15.7% |
| LOAD_GLOBAL | 1,440 | 15.5% |
| POP_TOP | 200 | 2.2% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 120 | 85.7% |
| BINARY_OP | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 140 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,023,680 | 100.0% |
| LOAD_FAST_LOAD_FAST | 1,280 | 0.0% |
| BINARY_OP_MULTIPLY_INT | 1,060 | 0.0% |
| BINARY_OP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,001,980 | 99.7% |
| LOAD_FAST | 15,280 | 0.2% |
| STORE_FAST | 6,680 | 0.1% |
| CALL_PY_EXACT_ARGS | 680 | 0.0% |
| BINARY_SLICE | 460 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,300 | 55.6% |
| LOAD_CONST | 3,360 | 22.5% |
| BINARY_SUBSCR_LIST_INT | 2,000 | 13.4% |
| CALL_METHOD_DESCRIPTOR_O | 640 | 4.3% |
| BINARY_OP | 260 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,700 | 44.8% |
| STORE_FAST | 2,100 | 14.1% |
| CALL | 1,600 | 10.7% |
| STORE_SUBSCR_DICT | 1,360 | 9.1% |
| BUILD_TUPLE | 800 | 5.4% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 1,060 | 58.9% |
| LOAD_CONST | 720 | 40.0% |
| BINARY_OP | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,060 | 58.9% |
| LOAD_CONST | 360 | 20.0% |
| CALL_BUILTIN_O | 360 | 20.0% |
| LOAD_GLOBAL | 20 | 1.1% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,000 | 36.6% |
| LOAD_FAST | 3,700 | 33.8% |
| CALL_LEN | 3,180 | 29.1% |
| BINARY_OP | 40 | 0.4% |
| ENTER_EXECUTOR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,180 | 29.1% |
| LOAD_FAST_LOAD_FAST | 2,720 | 24.9% |
| STORE_FAST | 1,360 | 12.4% |
| LOAD_CONST | 1,200 | 11.0% |
| LOAD_FAST | 1,140 | 10.4% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,860 | 75.4% |
| LOAD_CONST | 2,000 | 11.7% |
| LOAD_FAST_LOAD_FAST | 1,020 | 6.0% |
| LOAD_DEREF | 640 | 3.8% |
| BUILD_TUPLE | 240 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 6,260 | 36.7% |
| STORE_FAST | 3,180 | 18.6% |
| PUSH_NULL | 3,140 | 18.4% |
| LOAD_FAST | 1,340 | 7.9% |
| CALL_BUILTIN_CLASS | 1,000 | 5.9% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,040 | 57.2% |
| ENTER_EXECUTOR | 1,520 | 21.5% |
| LOAD_FAST | 1,400 | 19.8% |
| LOAD_FAST_LOAD_FAST | 80 | 1.1% |
| BINARY_SUBSCR | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,060 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,880 | 77.9% |
| LOAD_CONST | 3,240 | 21.2% |
| BINARY_SUBSCR | 40 | 0.3% |
| LOAD_FAST_LOAD_FAST | 40 | 0.3% |
| BINARY_SUBSCR_LIST_INT | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,380 | 79.2% |
| BINARY_OP_ADD_UNICODE | 2,000 | 15.3% |
| STORE_FAST | 340 | 2.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 200 | 1.5% |
| LOAD_CONST | 100 | 0.8% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,120 | 63.6% |
| LOAD_FAST | 7,380 | 35.8% |
| ENTER_EXECUTOR | 120 | 0.6% |
| BINARY_SUBSCR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,640 | 37.0% |
| STORE_FAST | 5,620 | 27.2% |
| LOAD_FAST | 4,680 | 22.7% |
| BINARY_OP_INPLACE_ADD_UNICODE | 1,640 | 7.9% |
| CALL_BUILTIN_O | 800 | 3.9% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,060 | 99.6% |
| BINARY_SUBSCR | 120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,860 | 25.2% |
| LOAD_GLOBAL_MODULE | 6,280 | 23.1% |
| RETURN_VALUE | 3,120 | 11.5% |
| CALL_BUILTIN_O | 3,080 | 11.3% |
| LOAD_FAST | 2,620 | 9.6% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,242,840 | 65.5% |
| RETURN_VALUE | 2,757,120 | 34.4% |
| LOAD_FAST_LOAD_FAST | 4,800 | 0.1% |
| LOAD_FAST | 3,160 | 0.0% |
| BINARY_SUBSCR | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,009,500 | 100.0% |
| STORE_FAST | 100 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,860 | 47.5% |
| LOAD_FAST | 6,520 | 26.1% |
| PUSH_NULL | 3,200 | 12.8% |
| BUILD_TUPLE | 2,040 | 8.2% |
| LOAD_FAST_LOAD_FAST | 1,080 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 20,080 | 80.4% |
| POP_TOP | 4,660 | 18.7% |
| COPY_FREE_VARS | 100 | 0.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 80 | 0.3% |
| CALL_PY_EXACT_ARGS | 40 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 3,780 | 31.8% |
| LOAD_GLOBAL_BUILTIN | 1,620 | 13.6% |
| CALL_LEN | 1,340 | 11.3% |
| LOAD_FAST | 1,200 | 10.1% |
| BINARY_SUBSCR_DICT | 1,000 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,640 | 30.6% |
| STORE_FAST | 3,320 | 27.9% |
| LOAD_CONST | 1,480 | 12.4% |
| GET_ITER | 900 | 7.6% |
| RETURN_VALUE | 740 | 6.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,200 | 52.8% |
| LOAD_FAST | 10,900 | 19.7% |
| LOAD_FAST_LOAD_FAST | 6,420 | 11.6% |
| LOAD_ATTR_SLOT | 3,700 | 6.7% |
| LOAD_GLOBAL_MODULE | 3,280 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,220 | 22.1% |
| TO_BOOL_BOOL | 9,260 | 16.8% |
| COPY | 8,360 | 15.1% |
| STORE_FAST | 8,120 | 14.7% |
| POP_JUMP_IF_NOT_NONE | 7,080 | 12.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,100 | 68.2% |
| LOAD_CONST | 3,300 | 20.3% |
| CALL_STR_1 | 1,000 | 6.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 300 | 1.8% |
| CALL_TUPLE_1 | 240 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,180 | 44.1% |
| TO_BOOL_BOOL | 3,380 | 20.8% |
| STORE_FAST | 3,160 | 19.4% |
| BEFORE_WITH | 1,000 | 6.1% |
| LOAD_ATTR_METHOD_NO_DICT | 340 | 2.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,500 | 43.0% |
| LOAD_GLOBAL_MODULE | 4,460 | 14.2% |
| LOAD_CONST | 3,120 | 9.9% |
| BINARY_SUBSCR_TUPLE_INT | 3,080 | 9.8% |
| ENTER_EXECUTOR | 1,480 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 21,360 | 68.1% |
| BUILD_TUPLE | 2,940 | 9.4% |
| TO_BOOL_BOOL | 2,640 | 8.4% |
| STORE_FAST | 2,540 | 8.1% |
| TO_BOOL_INT | 1,220 | 3.9% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,940 | 63.6% |
| LOAD_GLOBAL_MODULE | 11,400 | 27.9% |
| BUILD_TUPLE | 2,160 | 5.3% |
| CALL | 500 | 1.2% |
| LOAD_NAME | 300 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 39,520 | 96.9% |
| TO_BOOL | 500 | 1.2% |
| RETURN_VALUE | 480 | 1.2% |
| LOAD_FAST | 240 | 0.6% |
| YIELD_VALUE | 60 | 0.1% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,041,560 | 99.9% |
| LOAD_ATTR_INSTANCE_VALUE | 15,140 | 0.1% |
| POP_JUMP_IF_TRUE | 3,180 | 0.0% |
| LOAD_ATTR | 1,060 | 0.0% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 16,005,340 | 99.6% |
| LOAD_CONST | 24,560 | 0.2% |
| LOAD_FAST | 12,160 | 0.1% |
| RETURN_VALUE | 6,100 | 0.0% |
| TO_BOOL_INT | 3,700 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,100 | 48.8% |
| LOAD_CONST | 4,240 | 18.6% |
| LOAD_ATTR_INSTANCE_VALUE | 3,700 | 16.3% |
| BUILD_TUPLE | 2,280 | 10.0% |
| LOAD_FAST_CHECK | 620 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,640 | 29.2% |
| NOP | 4,320 | 19.0% |
| LOAD_FAST | 3,800 | 16.7% |
| EXTENDED_ARG | 3,540 | 15.6% |
| ENTER_EXECUTOR | 1,440 | 6.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 11,640 | 36.2% |
| BUILD_MAP | 5,960 | 18.5% |
| LOAD_ATTR_METHOD_NO_DICT | 4,660 | 14.5% |
| LOAD_FAST | 4,080 | 12.7% |
| LOAD_CONST | 1,600 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,180 | 44.1% |
| LIST_APPEND | 9,200 | 28.6% |
| POP_TOP | 5,640 | 17.5% |
| LOAD_FAST | 1,220 | 3.8% |
| SWAP | 1,000 | 3.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 300 | 28.3% |
| LOAD_GLOBAL_MODULE | 240 | 22.6% |
| LOAD_ATTR_METHOD_NO_DICT | 220 | 20.8% |
| LOAD_FAST_LOAD_FAST | 120 | 11.3% |
| CALL | 80 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 22.6% |
| STORE_DEREF | 220 | 20.8% |
| LOAD_ATTR_METHOD_NO_DICT | 220 | 20.8% |
| STORE_FAST | 180 | 17.0% |
| POP_TOP | 120 | 11.3% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,060 | 79.3% |
| CALL | 380 | 9.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 180 | 4.7% |
| LOAD_ATTR | 120 | 3.1% |
| LOAD_FAST | 120 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 960 | 24.9% |
| BUILD_TUPLE | 540 | 14.0% |
| TO_BOOL_BOOL | 460 | 11.9% |
| BINARY_OP | 400 | 10.4% |
| POP_TOP | 380 | 9.8% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,003,520 | 49.9% |
| CALL | 8,000,340 | 49.9% |
| STORE_FAST | 9,200 | 0.1% |
| LOAD_CONST | 8,740 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 3,700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 16,008,680 | 99.9% |
| RETURN_VALUE | 10,180 | 0.1% |
| LOAD_CONST | 6,660 | 0.0% |
| STORE_FAST | 2,300 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 2,000 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 16,002,980 | 66.3% |
| LOAD_FAST | 8,055,320 | 33.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 19,900 | 0.1% |
| ENTER_EXECUTOR | 14,760 | 0.1% |
| LOAD_FAST_LOAD_FAST | 13,240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 24,123,660 | 100.0% |
| COPY_FREE_VARS | 3,560 | 0.0% |
| MAKE_CELL | 2,180 | 0.0% |
| RETURN_GENERATOR | 1,020 | 0.0% |
| RESUME | 160 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,640 | 55.4% |
| LOAD_FAST | 820 | 27.7% |
| LOAD_DEREF | 160 | 5.4% |
| CALL | 140 | 4.7% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,960 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,000 | 60.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,000 | 30.3% |
| CALL_BUILTIN_O | 300 | 9.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,200 | 35.1% |
| LOAD_FAST | 960 | 28.1% |
| RETURN_GENERATOR | 620 | 18.1% |
| CALL_BUILTIN_CLASS | 300 | 8.8% |
| CALL | 180 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,200 | 35.1% |
| RETURN_VALUE | 700 | 20.5% |
| LOAD_FAST | 640 | 18.7% |
| STORE_FAST | 340 | 9.9% |
| STORE_DEREF | 300 | 8.8% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,940 | 67.7% |
| LOAD_GLOBAL_MODULE | 1,020 | 23.5% |
| LOAD_CONST | 280 | 6.5% |
| CALL | 80 | 1.8% |
| LOAD_ATTR_MODULE | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,160 | 49.8% |
| PUSH_NULL | 1,040 | 24.0% |
| LOAD_FAST_LOAD_FAST | 480 | 11.1% |
| LOAD_FAST | 440 | 10.1% |
| BUILD_TUPLE | 140 | 3.2% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,700 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,036,680 | 99.9% |
| LOAD_FAST | 16,180 | 0.1% |
| CALL_LEN | 1,120 | 0.0% |
| BINARY_OP | 1,000 | 0.0% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,036,480 | 99.9% |
| COPY | 9,700 | 0.1% |
| POP_JUMP_IF_TRUE | 7,060 | 0.0% |
| RETURN_VALUE | 2,200 | 0.0% |
| STORE_FAST | 1,000 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 44,900 | 70.6% |
| COPY | 9,360 | 14.7% |
| LOAD_ATTR_INSTANCE_VALUE | 7,800 | 12.3% |
| LOAD_FAST | 1,000 | 1.6% |
| COMPARE_OP | 380 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 45,620 | 71.7% |
| COPY | 10,820 | 17.0% |
| EXTENDED_ARG | 4,380 | 6.9% |
| JUMP_FORWARD | 1,640 | 2.6% |
| RETURN_VALUE | 1,160 | 1.8% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 420 | 87.5% |
| SWAP | 40 | 8.3% |
| FOR_ITER | 20 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 420 | 87.5% |
| POP_TOP | 60 | 12.5% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,560 | 41.9% |
| EXTENDED_ARG | 6,100 | 29.9% |
| ENTER_EXECUTOR | 3,520 | 17.2% |
| JUMP_BACKWARD | 1,760 | 8.6% |
| LOAD_FAST | 240 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 6,720 | 32.9% |
| STORE_FAST | 5,180 | 25.4% |
| LOAD_GLOBAL_BUILTIN | 2,420 | 11.9% |
| LOAD_FAST | 2,160 | 10.6% |
| BUILD_LIST | 920 | 4.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,600 | 35.9% |
| GET_ITER | 1,540 | 34.5% |
| JUMP_BACKWARD | 1,020 | 22.9% |
| SWAP | 240 | 5.4% |
| FOR_ITER | 60 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,620 | 58.7% |
| LOAD_FAST | 1,340 | 30.0% |
| SWAP | 260 | 5.8% |
| LOAD_CONST | 160 | 3.6% |
| JUMP_FORWARD | 40 | 0.9% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 16,220 | 40.3% |
| SWAP | 9,660 | 24.0% |
| GET_ITER | 7,620 | 19.0% |
| JUMP_BACKWARD | 5,120 | 12.7% |
| LOAD_FAST | 1,180 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 10,180 | 25.3% |
| SWAP | 9,700 | 24.1% |
| STORE_FAST | 9,560 | 23.8% |
| LOAD_FAST | 4,080 | 10.1% |
| RETURN_CONST | 1,300 | 3.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 260 | 65.0% |
| LOAD_ATTR | 140 | 35.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 45.0% |
| LOAD_CONST | 100 | 25.0% |
| GET_ITER | 40 | 10.0% |
| CALL | 20 | 5.0% |
| CONTAINS_OP | 20 | 5.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 74,947,840 | 90.3% |
| LOAD_FAST_LOAD_FAST | 8,014,900 | 9.7% |
| LOAD_ATTR | 2,160 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,340 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 16,017,260 | 19.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,005,280 | 9.6% |
| TO_BOOL | 8,004,240 | 9.6% |
| TO_BOOL_BOOL | 8,002,480 | 9.6% |
| CALL | 8,001,680 | 9.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,017,260 | 99.4% |
| LOAD_FAST | 65,840 | 0.4% |
| LOAD_GLOBAL_MODULE | 13,860 | 0.1% |
| LOAD_ATTR | 10,200 | 0.1% |
| LOAD_ATTR_MODULE | 3,780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,040,040 | 49.9% |
| LOAD_GLOBAL_MODULE | 8,012,760 | 49.7% |
| LOAD_CONST | 51,680 | 0.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 4,660 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,060 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,005,280 | 99.5% |
| LOAD_FAST | 31,600 | 0.4% |
| LOAD_GLOBAL_MODULE | 3,700 | 0.0% |
| LOAD_ATTR | 1,140 | 0.0% |
| BINARY_SUBSCR_TUPLE_INT | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,015,520 | 99.7% |
| CALL_PY_EXACT_ARGS | 19,900 | 0.2% |
| LOAD_FAST_LOAD_FAST | 5,540 | 0.1% |
| LOAD_CONST | 1,260 | 0.0% |
| CALL | 620 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 97,520 | 93.1% |
| LOAD_NAME | 3,380 | 3.2% |
| LOAD_FAST | 2,720 | 2.6% |
| LOAD_ATTR | 1,040 | 1.0% |
| LOAD_ATTR_MODULE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 29,020 | 27.7% |
| PUSH_NULL | 18,740 | 17.9% |
| LOAD_FAST | 13,360 | 12.8% |
| LOAD_ATTR_SLOT | 12,200 | 11.7% |
| LOAD_CONST | 8,960 | 8.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,140 | 83.5% |
| LOAD_CONST | 600 | 16.0% |
| LOAD_ATTR | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,160 | 84.0% |
| LOAD_GLOBAL_BUILTIN | 600 | 16.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280 | 51.9% |
| LOAD_FAST_LOAD_FAST | 240 | 44.4% |
| LOAD_ATTR | 20 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 240 | 44.4% |
| LOAD_GLOBAL_BUILTIN | 240 | 44.4% |
| LOAD_FAST | 60 | 11.1% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,300 | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 8.3% |
| LOAD_ATTR | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,800 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 12,200 | 49.6% |
| LOAD_FAST | 9,780 | 39.8% |
| RETURN_VALUE | 1,700 | 6.9% |
| LOAD_ATTR | 360 | 1.5% |
| CALL_BUILTIN_FAST | 300 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,040 | 48.9% |
| LOAD_CONST | 4,500 | 18.3% |
| CALL_BUILTIN_FAST | 3,700 | 15.0% |
| STORE_FAST | 1,700 | 6.9% |
| LOAD_FAST_LOAD_FAST | 600 | 2.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,058,860 | 98.7% |
| STORE_FAST | 38,700 | 0.2% |
| POP_JUMP_IF_FALSE | 32,140 | 0.2% |
| LOAD_FAST | 27,380 | 0.2% |
| POP_TOP | 20,640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,150,900 | 99.3% |
| LOAD_DEREF | 30,000 | 0.2% |
| CALL_ISINSTANCE | 25,940 | 0.2% |
| LOAD_FAST_LOAD_FAST | 14,580 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 10,560 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,039,260 | 24.8% |
| LOAD_ATTR_METHOD_NO_DICT | 8,012,760 | 24.7% |
| LOAD_GLOBAL_MODULE | 8,009,040 | 24.7% |
| BINARY_SUBSCR | 7,999,960 | 24.7% |
| LOAD_FAST | 100,200 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 16,023,540 | 49.5% |
| LOAD_FAST | 8,081,860 | 25.0% |
| LOAD_GLOBAL_MODULE | 8,009,040 | 24.7% |
| LOAD_ATTR_MODULE | 97,520 | 0.3% |
| IS_OP | 35,160 | 0.1% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,120 | 82.4% |
| LOAD_DEREF | 140 | 10.3% |
| LOAD_SUPER_ATTR | 100 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,360 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,580 | 99.1% |
| LOAD_SUPER_ATTR | 240 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 23,280 | 90.2% |
| LOAD_FAST | 2,060 | 8.0% |
| CALL | 280 | 1.1% |
| CALL_PY_EXACT_ARGS | 200 | 0.8% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 141,577,220 | 77.9% |
| CALL_PY_EXACT_ARGS | 24,123,660 | 13.3% |
| CALL_ALLOC_AND_ENTER_INIT | 8,009,500 | 4.4% |
| POP_TOP | 8,003,700 | 4.4% |
| COPY_FREE_VARS | 32,900 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 125,521,160 | 69.0% |
| LOAD_FAST | 32,102,660 | 17.7% |
| LOAD_GLOBAL_BUILTIN | 16,058,860 | 8.8% |
| LOAD_FAST_LOAD_FAST | 8,029,920 | 4.4% |
| LOAD_GLOBAL_MODULE | 79,380 | 0.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| SEND | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 24,058,660 | 99.7% |
| LOAD_FAST | 66,920 | 0.3% |
| STORE_ATTR | 1,240 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 16,031,680 | 66.4% |
| RETURN_CONST | 8,033,980 | 33.3% |
| LOAD_FAST | 34,940 | 0.1% |
| LOAD_CONST | 9,380 | 0.0% |
| LOAD_GLOBAL_MODULE | 5,620 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,780 | 59.5% |
| LOAD_FAST | 2,620 | 32.6% |
| STORE_ATTR | 340 | 4.2% |
| LOAD_ATTR_SLOT | 300 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,940 | 73.9% |
| RETURN_CONST | 720 | 9.0% |
| LOAD_FAST_LOAD_FAST | 660 | 8.2% |
| LOAD_CONST | 640 | 8.0% |
| LOAD_GLOBAL_BUILTIN | 80 | 1.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,000 | 57.1% |
| LOAD_CONST | 5,240 | 17.6% |
| LOAD_FAST_LOAD_FAST | 3,100 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,440 | 8.2% |
| BINARY_OP_ADD_UNICODE | 1,360 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,580 | 38.9% |
| ENTER_EXECUTOR | 6,040 | 20.3% |
| LOAD_GLOBAL_MODULE | 3,220 | 10.8% |
| NOP | 2,400 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 1,120 | 3.8% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,740 | 68.2% |
| LOAD_FAST | 640 | 15.9% |
| LOAD_NAME | 600 | 14.9% |
| STORE_SUBSCR | 40 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 1,780 | 44.3% |
| ENTER_EXECUTOR | 940 | 23.4% |
| RETURN_CONST | 540 | 13.4% |
| JUMP_BACKWARD | 320 | 8.0% |
| LOAD_NAME | 320 | 8.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,001,020 | 99.1% |
| TO_BOOL_NONE | 68,840 | 0.9% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,001,040 | 99.1% |
| TO_BOOL_NONE | 68,860 | 0.9% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,002,480 | 97.5% |
| COPY | 49,460 | 0.6% |
| RETURN_VALUE | 42,940 | 0.5% |
| CALL_ISINSTANCE | 39,520 | 0.5% |
| LOAD_FAST | 26,300 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,134,740 | 99.1% |
| POP_JUMP_IF_TRUE | 67,480 | 0.8% |
| EXTENDED_ARG | 3,420 | 0.0% |
| UNARY_NOT | 60 | 0.0% |
| TO_BOOL_INT | 20 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 11,760 | 49.5% |
| LOAD_FAST | 5,420 | 22.8% |
| CALL_LEN | 3,700 | 15.6% |
| COPY | 1,240 | 5.2% |
| CALL_BUILTIN_O | 1,220 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,960 | 63.0% |
| POP_JUMP_IF_TRUE | 7,580 | 31.9% |
| UNARY_NOT | 1,180 | 5.0% |
| TO_BOOL_BOOL | 20 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,000,580 | 99.9% |
| LOAD_FAST | 4,820 | 0.1% |
| LOAD_ATTR | 280 | 0.0% |
| TO_BOOL | 100 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,003,260 | 100.0% |
| POP_JUMP_IF_TRUE | 2,340 | 0.0% |
| UNARY_NOT | 240 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,998,960 | 98.9% |
| TO_BOOL_ALWAYS_TRUE | 68,860 | 0.9% |
| LOAD_FAST | 11,760 | 0.1% |
| COPY | 3,800 | 0.0% |
| TO_BOOL | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,010,740 | 99.1% |
| TO_BOOL_ALWAYS_TRUE | 68,840 | 0.9% |
| POP_JUMP_IF_TRUE | 4,360 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 9,200 | 47.2% |
| COPY | 5,240 | 26.9% |
| LOAD_FAST | 4,900 | 25.2% |
| TO_BOOL | 60 | 0.3% |
| LOAD_GLOBAL_MODULE | 60 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,900 | 71.4% |
| POP_JUMP_IF_TRUE | 5,580 | 28.6% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 2,000 | 53.2% |
| LOAD_FAST | 920 | 24.5% |
| RETURN_VALUE | 420 | 11.2% |
| BUILD_TUPLE | 300 | 8.0% |
| BINARY_SUBSCR_TUPLE_INT | 120 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,380 | 63.3% |
| STORE_FAST | 1,080 | 28.7% |
| STORE_DEREF | 300 | 8.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,220 | 41.2% |
| FOR_ITER_LIST | 6,720 | 30.1% |
| FOR_ITER | 5,500 | 24.6% |
| UNPACK_SEQUENCE | 320 | 1.4% |
| LOAD_CONST | 260 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 16,740 | 74.9% |
| STORE_FAST | 4,680 | 20.9% |
| STORE_NAME | 820 | 3.7% |
| LOAD_FAST | 60 | 0.3% |
| STORE_DEREF | 60 | 0.3% |


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
|     deferred | 8,027,960 | 49.9% |
|          hit | 8,056,200 | 50.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 500 | 11.8% |
| Failure | 3,720 | 88.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 2,240 | 60.2% |
| and int | 740 | 19.9% |
| or | 300 | 8.1% |
| add other | 220 | 5.9% |
| power | 80 | 2.2% |
| add different types | 60 | 1.6% |
| multiply different types | 60 | 1.6% |
| and different types | 20 | 0.5% |


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
|     deferred | 8,010,400 | 98.9% |
|          hit | 84,760 | 1.0% |
|         miss | 2,440 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 13.0% |
| Failure | 2,280 | 87.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence int | 2,140 | 93.9% |
| out of range | 80 | 3.5% |
| code complex parameters | 40 | 1.8% |
| other | 20 | 0.9% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 16,194,180 | 20.1% |
|          hit | 64,482,240 | 79.9% |
|         miss | 26,520 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,460 | 43.6% |
| Failure | 8,360 | 56.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class no vectorcall | 2,660 | 31.8% |
| other | 2,280 | 27.3% |
| meth descr varargs | 1,380 | 16.5% |
| code complex parameters | 460 | 5.5% |
| cfunc noargs | 440 | 5.3% |
| cfunc varargs keywords | 240 | 2.9% |
| method wrapper | 200 | 2.4% |
| wrong number arguments | 140 | 1.7% |
| class mutable | 140 | 1.7% |
| cfunc varargs | 100 | 1.2% |
| no dict | 60 | 0.7% |
| meth descr method fastcall keywords | 60 | 0.7% |
| operator wrapper | 60 | 0.7% |
| init not simple | 60 | 0.7% |
| meth descr varargs keywords | 40 | 0.5% |
| cmethod | 20 | 0.2% |
| init not python | 20 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 16,580 | 0.1% |
|          hit | 16,121,420 | 99.9% |
|         miss | 360 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 780 | 66.1% |
| Failure | 400 | 33.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 140 | 35.0% |
| list | 60 | 15.0% |
| other | 40 | 10.0% |
| different types | 40 | 10.0% |
| tuple | 40 | 10.0% |
| bool | 40 | 10.0% |
| set | 20 | 5.0% |
| baseobject | 20 | 5.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 17,220 | 20.3% |
|          hit | 65,560 | 77.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 28.0% |
| Failure | 1,540 | 72.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 540 | 35.1% |
| dict values | 500 | 32.5% |
| set | 180 | 11.7% |
| itertools | 160 | 10.4% |
| map | 60 | 3.9% |
| seq iter | 40 | 2.6% |
| dict keys | 20 | 1.3% |
| enumerate | 20 | 1.3% |
| zip | 20 | 1.3% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 99,140 | 0.1% |
|        deopt | 360 | 0.0% |
|          hit | 107,254,060 | 99.9% |
|         miss | 14,640 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,280 | 60.5% |
| Failure | 4,100 | 39.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 2,500 | 61.0% |
| method | 460 | 11.2% |
| not managed dict | 360 | 8.8% |
| module attr not found | 200 | 4.9% |
| has managed dict | 160 | 3.9% |
| shadowed | 120 | 2.9% |
| class attr descriptor | 80 | 2.0% |
| class method obj | 60 | 1.5% |
| non overriding descriptor | 40 | 1.0% |
| builtin class method | 40 | 1.0% |
| class attr simple | 40 | 1.0% |
| overridden | 20 | 0.5% |
| mutable class | 20 | 0.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,080 | 0.0% |
|        deopt | 2,620 | 0.0% |
|          hit | 48,525,860 | 99.7% |
|         miss | 130,160 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,380 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 400 | 1.4% |
|          hit | 27,180 | 97.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 100.0% |
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
|     deferred | 133,515,700 | 100.0% |
|          hit | 60 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.1% |
| Failure | 33,180 | 99.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| async generator send | 33,180 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 31,460 | 0.1% |
|          hit | 24,122,680 | 99.8% |
|         miss | 12,680 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,760 | 45.8% |
| Failure | 2,080 | 54.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overridden | 1,540 | 74.0% |
| not in keys | 160 | 7.7% |
| overriding descriptor | 140 | 6.7% |
| no dict | 80 | 3.8% |
| not managed dict | 80 | 3.8% |
| class attr simple | 60 | 2.9% |
| mutable class | 20 | 1.0% |


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
|     deferred | 5,540 | 13.9% |
|          hit | 33,800 | 84.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 42.9% |
| Failure | 320 | 57.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytearray int | 280 | 87.5% |
| py simple | 40 | 12.5% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,872,920 | 19.5% |
|          hit | 25,102,260 | 62.1% |
|         miss | 7,306,360 | 18.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140,420 | 98.3% |
| Failure | 2,380 | 1.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 2,180 | 91.6% |
| mapping | 60 | 2.5% |
| dict | 40 | 1.7% |
| sequence | 40 | 1.7% |
| tuple | 40 | 1.7% |
| number | 20 | 0.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 300 | 1.1% |
|          hit | 26,120 | 97.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 320 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,478,418,320 | 66.7% |
| Not specialized | 254,659,260 | 11.5% |
| Specialized hits | 475,694,280 | 21.5% |
| Specialized misses | 7,504,580 | 0.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| SEND | 133,515,700 | 76.8% |
| CALL | 16,194,180 | 9.3% |
| BINARY_OP | 8,027,960 | 4.6% |
| BINARY_SUBSCR | 8,010,400 | 4.6% |
| TO_BOOL | 7,872,920 | 4.5% |
| LOAD_ATTR | 99,140 | 0.1% |
| STORE_ATTR | 31,460 | 0.0% |
| FOR_ITER | 17,220 | 0.0% |
| COMPARE_OP | 16,580 | 0.0% |
| LOAD_GLOBAL | 9,080 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_NONE | 3,653,900 | 48.6% |
| TO_BOOL_ALWAYS_TRUE | 3,650,500 | 48.6% |
| LOAD_GLOBAL_MODULE | 73,640 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 56,520 | 0.8% |
| STORE_ATTR_INSTANCE_VALUE | 12,620 | 0.2% |
| RESUME | 11,420 | 0.2% |
| RESUME_CHECK | 11,420 | 0.2% |
| LOAD_ATTR_MODULE | 9,260 | 0.1% |
| CALL_PY_EXACT_ARGS | 8,920 | 0.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,860 | 0.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 157,618,720 | 83.0% |
| Calls to Python functions inlined | 32,219,380 | 17.0% |
| Calls via PyEval_EvalFrame (total) | 157,618,720 | 83.0% |
| Calls via PyEval_EvalFrame (vector) | 24,093,980 | 12.7% |
| Calls via PyEval_EvalFrame (generator) | 133,524,740 | 70.3% |
| Calls via PyEval_EvalFrame (legacy) | 1,320 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 24,088,520 | 12.7% |
| Calls via PyEval_EvalFrame (build class) | 4,140 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 30,240 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 1,580 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 16,013,620 | 8.4% |
| Calls via PyEval_EvalFrame (method) | 2,800 | 0.0% |
| Frame objects created | 5,255,320 | 2.8% |
| Frames pushed | 40,209,140 | 21.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 259,447,300 | 52.3% |
| Frees to freelist | 259,444,140 |  |
| Allocations | 236,283,580 | 47.7% |
| Allocations to 512 bytes | 236,243,120 | 47.7% |
| Allocations to 4 kbytes | 37,580 | 0.0% |
| Allocations over 4 kbytes | 2,880 | 0.0% |
| Frees | 235,700,924 |  |
| New values | 13,460 |  |
| Interpreter increfs | 1,139,882,720 | 61.6% |
| Interpreter decrefs | 1,594,389,020 | 64.1% |
| Increfs | 710,343,944 | 38.4% |
| Decrefs | 891,889,960 | 35.9% |
| Materialize dict (on request) | 240 | 1.8% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 100 | 0.7% |
| Method cache hits | 180,918 |  |
| Method cache misses | 53,582 |  |
| Method cache collisions | 62,133 |  |
| Method cache dunder hits | 8,335,000 |  |
| Method cache dunder misses | 22,160 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 10,660 | 3,600 | 60,631,080 |
| 1 | 960 | 0 | 62,009,640 |
| 2 | 80 | 0 | 49,981,040 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 2,620 |  |
| Traces created | 1,160 | 44.3% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 1,460 | 55.7% |
| Trace too long | 100 | 3.8% |
| Trace too short | 1,460 | 55.7% |
| Inner loop found | 100 | 3.8% |
| Recursive call | 0 | 0.0% |
| Traces executed | 130,861,540 |  |
| Uops executed | 673,015,000 | 5.14 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 80 | 6.9% |
| <= 32 | 380 | 32.8% |
| <= 64 | 340 | 29.3% |
| <= 128 | 360 | 31.0% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 80 | 6.9% |
| <= 16 | 160 | 13.8% |
| <= 32 | 500 | 43.1% |
| <= 64 | 360 | 31.0% |
| <= 128 | 60 | 5.2% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 1,000 | 0.0% |
| <= 2 | 14,300 | 0.0% |
| <= 4 | 1,920 | 0.0% |
| <= 8 | 130,766,100 | 99.9% |
| <= 16 | 33,220 | 0.0% |
| <= 32 | 20,820 | 0.0% |
| <= 64 | 5,360 | 0.0% |
| <= 128 | 17,780 | 0.0% |
| <= 256 | 360 | 0.0% |
| <= 512 | 340 | 0.0% |
| <= 1,024 | 180 | 0.0% |
| <= 2,048 | 40 | 0.0% |
| <= 4,096 | 60 | 0.0% |
| <= 8,192 | 20 | 0.0% |
| <= 16,384 | 40 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 131,232,440 | 19.5% | 19.5% |  |
| _CHECK_VALIDITY | 131,150,480 | 19.5% | 39.0% |  |
| _EXIT_TRACE | 130,796,160 | 19.4% | 58.4% |  |
| LOAD_CONST | 125,613,980 | 18.7% | 77.1% |  |
| GET_ANEXT | 125,514,720 | 18.6% | 95.7% |  |
| LOAD_FAST | 5,727,460 | 0.9% | 96.6% |  |
| _GUARD_TYPE_VERSION | 5,368,760 | 0.8% | 97.4% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 5,312,940 | 0.8% | 98.2% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 5,312,940 | 0.8% | 99.0% |  |
| CALL_INTRINSIC_1 | 5,242,820 | 0.8% | 99.7% |  |
| STORE_FAST | 224,100 | 0.0% | 99.8% |  |
| _JUMP_TO_TOP | 63,200 | 0.0% | 99.8% |  |
| _GUARD_IS_FALSE_POP | 62,120 | 0.0% | 99.8% | 8.8% |
| _GUARD_GLOBALS_VERSION | 57,160 | 0.0% | 99.8% | 19.6% |
| PUSH_NULL | 55,800 | 0.0% | 99.8% |  |
| _FOR_ITER_TIER_TWO | 54,140 | 0.0% | 99.8% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 48,980 | 0.0% | 99.8% | 30.1% |
| _CHECK_PEP_523 | 48,980 | 0.0% | 99.8% |  |
| LOAD_NAME | 41,200 | 0.0% | 99.8% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 40,660 | 0.0% | 99.8% | 39.9% |
| _ITER_CHECK_TUPLE | 40,660 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 37,620 | 0.0% | 99.9% |  |
| _LOAD_GLOBAL_MODULE | 35,620 | 0.0% | 99.9% |  |
| _CHECK_STACK_SPACE | 34,220 | 0.0% | 99.9% |  |
| _INIT_CALL_PY_EXACT_ARGS | 34,220 | 0.0% | 99.9% |  |
| _PUSH_FRAME | 34,220 | 0.0% | 99.9% |  |
| _SAVE_RETURN_OFFSET | 34,220 | 0.0% | 99.9% |  |
| RESUME_CHECK | 33,200 | 0.0% | 99.9% |  |
| _GUARD_IS_TRUE_POP | 30,760 | 0.0% | 99.9% | 3.8% |
| _ITER_CHECK_LIST | 28,100 | 0.0% | 99.9% | 3.6% |
| CONTAINS_OP | 27,380 | 0.0% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 27,100 | 0.0% | 99.9% | 23.6% |
| _ITER_NEXT_TUPLE | 24,440 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 24,400 | 0.0% | 99.9% |  |
| TO_BOOL_BOOL | 21,940 | 0.0% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 20,980 | 0.0% | 99.9% | 7.6% |
| _ITER_CHECK_RANGE | 20,980 | 0.0% | 99.9% |  |
| _GUARD_BOTH_INT | 20,760 | 0.0% | 99.9% |  |
| _ITER_NEXT_LIST | 20,700 | 0.0% | 99.9% |  |
| LIST_APPEND | 20,200 | 0.0% | 99.9% |  |
| _ITER_NEXT_RANGE | 19,380 | 0.0% | 99.9% |  |
| _CHECK_ATTR_MODULE | 19,020 | 0.0% | 99.9% |  |
| _LOAD_ATTR_MODULE | 19,020 | 0.0% | 99.9% |  |
| _BINARY_OP_ADD_INT | 17,920 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 17,360 | 0.0% | 99.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 17,060 | 0.0% | 99.9% |  |
| _GUARD_KEYS_VERSION | 17,060 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 17,060 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 16,900 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 16,040 | 0.0% | 100.0% | 0.7% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 16,040 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 16,040 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 15,100 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 14,360 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 14,360 | 0.0% | 100.0% |  |
| BINARY_SLICE | 13,040 | 0.0% | 100.0% |  |
| _STORE_SUBSCR | 12,800 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 11,440 | 0.0% | 100.0% |  |
| _GUARD_IS_NOT_NONE_POP | 11,380 | 0.0% | 100.0% | 2.1% |
| TO_BOOL_STR | 11,200 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 10,380 | 0.0% | 100.0% |  |
| _GUARD_BUILTINS_VERSION | 10,340 | 0.0% | 100.0% | 5.8% |
| IS_OP | 10,020 | 0.0% | 100.0% |  |
| _BINARY_OP | 9,860 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_BUILTINS | 9,740 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 9,000 | 0.0% | 100.0% | 2.0% |
| BUILD_STRING | 8,880 | 0.0% | 100.0% |  |
| STORE_NAME | 8,600 | 0.0% | 100.0% |  |
| _POP_FRAME | 7,680 | 0.0% | 100.0% |  |
| _LOAD_ATTR | 7,240 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 6,360 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 6,360 | 0.0% | 100.0% |  |
| POP_TOP | 5,240 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 5,020 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 4,400 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 4,160 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 3,700 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 3,540 | 0.0% | 100.0% | 41.8% |
| BINARY_SUBSCR_TUPLE_INT | 2,840 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 2,840 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 2,640 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 2,400 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 2,320 | 0.0% | 100.0% |  |
| MAP_ADD | 2,100 | 0.0% | 100.0% |  |
| CALL_LEN | 2,060 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 1,700 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,660 | 0.0% | 100.0% |  |
| _STORE_ATTR | 1,500 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 1,480 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 1,440 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 1,400 | 0.0% | 100.0% |  |
| GET_ITER | 1,320 | 0.0% | 100.0% |  |
| LOAD_DEREF | 920 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 500 | 0.0% | 100.0% |  |
| UNARY_NOT | 380 | 0.0% | 100.0% |  |
| COPY | 380 | 0.0% | 100.0% |  |
| BUILD_LIST | 340 | 0.0% | 100.0% |  |
| LIST_EXTEND | 340 | 0.0% | 100.0% |  |
| _TO_BOOL | 180 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 120 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 120 | 0.0% | 100.0% |  |
| STORE_DEREF | 120 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 20 | 0.0% | 100.0% | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 20 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 80 |
| SEND | 60 |
| CALL_LIST_APPEND | 60 |
| YIELD_VALUE | 40 |
| BINARY_SUBSCR_GETITEM | 40 |


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
