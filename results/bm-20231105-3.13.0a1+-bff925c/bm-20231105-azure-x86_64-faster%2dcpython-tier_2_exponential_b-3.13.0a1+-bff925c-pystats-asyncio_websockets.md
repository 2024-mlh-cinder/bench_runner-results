
# Pystats results

- benchmark: asyncio_websockets
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 4,763,687 | 18.5% | 18.5% |  |
| POP_JUMP_IF_FALSE | 1,426,992 | 5.5% | 24.0% |  |
| LOAD_ATTR_SLOT | 1,219,279 | 4.7% | 28.7% | 0.4% |
| LOAD_CONST | 1,137,307 | 4.4% | 33.1% |  |
| LOAD_FAST_LOAD_FAST | 1,072,370 | 4.2% | 37.3% |  |
| LOAD_GLOBAL_MODULE | 1,039,004 | 4.0% | 41.3% | 0.1% |
| STORE_FAST | 896,046 | 3.5% | 44.8% |  |
| RESUME_CHECK | 865,899 | 3.4% | 48.1% | 0.0% |
| TO_BOOL_BOOL | 800,823 | 3.1% | 51.2% |  |
| LOAD_ATTR_INSTANCE_VALUE | 776,950 | 3.0% | 54.2% | 0.1% |
| LOAD_GLOBAL_BUILTIN | 743,779 | 2.9% | 57.1% | 0.4% |
| LOAD_ATTR | 663,217 | 2.6% | 59.7% |  |
| POP_JUMP_IF_TRUE | 578,794 | 2.2% | 61.9% |  |
| POP_TOP | 565,749 | 2.2% | 64.1% |  |
| RETURN_VALUE | 519,733 | 2.0% | 66.1% |  |
| IS_OP | 418,440 | 1.6% | 67.7% |  |
| CALL_PY_EXACT_ARGS | 415,921 | 1.6% | 69.3% | 0.1% |
| RETURN_CONST | 384,188 | 1.5% | 70.8% |  |
| CALL | 359,729 | 1.4% | 72.2% |  |
| PUSH_NULL | 290,086 | 1.1% | 73.4% |  |
| LOAD_ATTR_MODULE | 279,863 | 1.1% | 74.4% | 0.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 266,334 | 1.0% | 75.5% | 0.0% |
| CALL_BUILTIN_FAST | 266,263 | 1.0% | 76.5% | 0.0% |
| FOR_ITER | 250,864 | 1.0% | 77.5% |  |
| COMPARE_OP_INT | 247,337 | 1.0% | 78.4% | 0.1% |
| CONTAINS_OP | 242,840 | 0.9% | 79.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 237,328 | 0.9% | 80.3% | 0.4% |
| LOAD_ATTR_WITH_HINT | 229,640 | 0.9% | 81.2% | 3.2% |
| STORE_ATTR | 225,661 | 0.9% | 82.1% |  |
| JUMP_BACKWARD | 217,602 | 0.8% | 82.9% |  |
| BINARY_OP | 215,682 | 0.8% | 83.7% |  |
| INTERPRETER_EXIT | 209,670 | 0.8% | 84.5% |  |
| CALL_LEN | 192,434 | 0.7% | 85.3% |  |
| STORE_ATTR_SLOT | 180,200 | 0.7% | 86.0% | 4.7% |
| STORE_SUBSCR_DICT | 170,203 | 0.7% | 86.6% |  |
| POP_JUMP_IF_NONE | 165,771 | 0.6% | 87.3% |  |
| RETURN_GENERATOR | 159,800 | 0.6% | 87.9% |  |
| SEND_GEN | 154,200 | 0.6% | 88.5% |  |
| GET_AWAITABLE | 151,360 | 0.6% | 89.1% |  |
| END_SEND | 151,040 | 0.6% | 89.7% |  |
| STORE_ATTR_INSTANCE_VALUE | 149,365 | 0.6% | 90.3% | 0.8% |
| POP_JUMP_IF_NOT_NONE | 131,208 | 0.5% | 90.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 115,526 | 0.4% | 91.2% | 8.6% |
| JUMP_FORWARD | 106,547 | 0.4% | 91.6% |  |
| NOP | 100,535 | 0.4% | 92.0% |  |
| CALL_KW | 99,321 | 0.4% | 92.4% |  |
| CALL_FUNCTION_EX | 93,763 | 0.4% | 92.8% |  |
| BUILD_TUPLE | 90,584 | 0.4% | 93.1% |  |
| LOAD_DEREF | 88,322 | 0.3% | 93.5% |  |
| TO_BOOL_NONE | 83,442 | 0.3% | 93.8% | 0.1% |
| TO_BOOL | 81,105 | 0.3% | 94.1% |  |
| CALL_METHOD_DESCRIPTOR_O | 79,048 | 0.3% | 94.4% | 1.0% |
| ENTER_EXECUTOR | 76,660 | 0.3% | 94.7% |  |
| BUILD_MAP | 71,402 | 0.3% | 95.0% |  |
| GET_ITER | 70,901 | 0.3% | 95.2% |  |
| BINARY_SLICE | 70,220 | 0.3% | 95.5% |  |
| DICT_MERGE | 67,601 | 0.3% | 95.8% |  |
| TO_BOOL_INT | 61,660 | 0.2% | 96.0% | 0.1% |
| CALL_TYPE_1 | 59,480 | 0.2% | 96.2% |  |
| COMPARE_OP | 59,458 | 0.2% | 96.5% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 51,940 | 0.2% | 96.7% | 19.1% |
| CALL_ISINSTANCE | 44,580 | 0.2% | 96.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 35,500 | 0.1% | 97.0% | 93.7% |
| DELETE_SUBSCR | 33,923 | 0.1% | 97.1% |  |
| BUILD_SLICE | 33,660 | 0.1% | 97.3% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 32,460 | 0.1% | 97.4% |  |
| LOAD_GLOBAL | 31,860 | 0.1% | 97.5% |  |
| STORE_FAST_STORE_FAST | 28,800 | 0.1% | 97.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 26,022 | 0.1% | 97.7% |  |
| EXTENDED_ARG | 26,020 | 0.1% | 97.8% |  |
| FOR_ITER_LIST | 25,098 | 0.1% | 97.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 24,260 | 0.1% | 98.0% |  |
| COPY | 24,020 | 0.1% | 98.1% |  |
| CALL_LIST_APPEND | 23,478 | 0.1% | 98.2% |  |
| STORE_DEREF | 21,725 | 0.1% | 98.3% |  |
| BINARY_OP_ADD_INT | 21,480 | 0.1% | 98.4% |  |
| BUILD_LIST | 20,581 | 0.1% | 98.4% |  |
| CALL_ALLOC_AND_ENTER_INIT | 19,082 | 0.1% | 98.5% | 0.2% |
| EXIT_INIT_CHECK | 19,042 | 0.1% | 98.6% |  |
| COPY_FREE_VARS | 18,780 | 0.1% | 98.7% |  |
| LOAD_FAST_CHECK | 16,820 | 0.1% | 98.7% |  |
| MAP_ADD | 16,040 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 16,039 | 0.1% | 98.8% |  |
| CALL_BUILTIN_CLASS | 15,640 | 0.1% | 98.9% |  |
| SWAP | 13,642 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_DICT | 13,061 | 0.1% | 99.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 13,040 | 0.1% | 99.1% |  |
| YIELD_VALUE | 12,980 | 0.1% | 99.1% |  |
| CALL_BUILTIN_O | 11,800 | 0.0% | 99.2% | 1.7% |
| LOAD_ATTR_PROPERTY | 11,462 | 0.0% | 99.2% |  |
| LIST_APPEND | 11,461 | 0.0% | 99.2% |  |
| RESUME | 10,340 | 0.0% | 99.3% | 0.8% |
| UNPACK_SEQUENCE_TUPLE | 10,040 | 0.0% | 99.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 9,760 | 0.0% | 99.4% |  |
| SEND | 9,400 | 0.0% | 99.4% |  |
| BEFORE_ASYNC_WITH | 9,120 | 0.0% | 99.4% |  |
| UNARY_NOT | 9,000 | 0.0% | 99.5% |  |
| MAKE_CELL | 8,225 | 0.0% | 99.5% |  |
| MAKE_FUNCTION | 6,862 | 0.0% | 99.5% |  |
| FOR_ITER_TUPLE | 6,140 | 0.0% | 99.5% |  |
| FOR_ITER_RANGE | 5,740 | 0.0% | 99.6% |  |
| COMPARE_OP_FLOAT | 5,700 | 0.0% | 99.6% |  |
| CALL_INTRINSIC_1 | 5,400 | 0.0% | 99.6% |  |
| COMPARE_OP_STR | 5,320 | 0.0% | 99.6% | 4.1% |
| LIST_EXTEND | 5,320 | 0.0% | 99.7% |  |
| LOAD_SUPER_ATTR_METHOD | 5,300 | 0.0% | 99.7% |  |
| TO_BOOL_STR | 4,842 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_LIST_INT | 4,259 | 0.0% | 99.7% |  |
| BEFORE_WITH | 3,766 | 0.0% | 99.7% |  |
| BINARY_OP_ADD_FLOAT | 3,740 | 0.0% | 99.7% |  |
| STORE_SUBSCR | 3,722 | 0.0% | 99.8% |  |
| CALL_PY_WITH_DEFAULTS | 3,641 | 0.0% | 99.8% |  |
| STORE_FAST_LOAD_FAST | 3,603 | 0.0% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 3,422 | 0.0% | 99.8% |  |
| BINARY_OP_SUBTRACT_INT | 3,280 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 3,060 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 3,060 | 0.0% | 99.8% |  |
| POP_EXCEPT | 3,040 | 0.0% | 99.8% |  |
| STORE_NAME | 3,020 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 2,680 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 2,620 | 0.0% | 99.9% | 11.5% |
| BINARY_SUBSCR | 2,482 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 2,460 | 0.0% | 99.9% | 6.5% |
| LOAD_FAST_AND_CLEAR | 2,361 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE | 2,100 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 1,660 | 0.0% | 99.9% |  |
| LOAD_NAME | 1,460 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_STR_INT | 1,400 | 0.0% | 99.9% | 11.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,340 | 0.0% | 99.9% |  |
| LOAD_SUPER_ATTR_ATTR | 1,340 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_LIST | 1,140 | 0.0% | 99.9% |  |
| UNARY_INVERT | 1,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 1,020 | 0.0% | 100.0% | 2.0% |
| LOAD_SUPER_ATTR | 1,020 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,020 | 0.0% | 100.0% |  |
| BUILD_STRING | 920 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 900 | 0.0% | 100.0% |  |
| RERAISE | 880 | 0.0% | 100.0% |  |
| DICT_UPDATE | 760 | 0.0% | 100.0% |  |
| CALL_STR_1 | 721 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 720 | 0.0% | 100.0% |  |
| BUILD_SET | 560 | 0.0% | 100.0% |  |
| IMPORT_NAME | 500 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 500 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 420 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 400 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 360 | 0.0% | 100.0% |  |
| CLEANUP_THROW | 320 | 0.0% | 100.0% |  |
| DELETE_FAST | 320 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 260 | 0.0% | 100.0% |  |
| IMPORT_FROM | 220 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 219 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 200 | 0.0% | 100.0% |  |
| DELETE_ATTR | 183 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 140 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 120 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 80 | 0.0% | 100.0% |  |
| STORE_SLICE | 40 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 887,200 | 3.4% | 3.4% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 752,107 | 2.9% | 6.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 723,480 | 2.8% | 9.2% |
| STORE_FAST LOAD_FAST | 657,392 | 2.5% | 11.7% |
| LOAD_FAST LOAD_ATTR | 517,353 | 2.0% | 13.7% |
| RESUME_CHECK LOAD_FAST | 469,108 | 1.8% | 15.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 462,110 | 1.8% | 17.3% |
| POP_JUMP_IF_TRUE LOAD_FAST | 451,307 | 1.7% | 19.1% |
| IS_OP POP_JUMP_IF_FALSE | 416,180 | 1.6% | 20.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 401,258 | 1.6% | 22.2% |
| LOAD_GLOBAL_MODULE IS_OP | 353,600 | 1.4% | 23.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 353,362 | 1.4% | 25.0% |
| LOAD_ATTR_SLOT LOAD_GLOBAL_MODULE | 351,920 | 1.4% | 26.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 329,813 | 1.3% | 27.6% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_SLOT | 320,060 | 1.2% | 28.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 306,855 | 1.2% | 30.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 275,323 | 1.1% | 31.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 244,657 | 0.9% | 32.0% |
| LOAD_FAST LOAD_CONST | 240,927 | 0.9% | 33.0% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 226,920 | 0.9% | 33.9% |
| LOAD_CONST LOAD_FAST | 213,270 | 0.8% | 34.7% |
| JUMP_BACKWARD FOR_ITER | 204,582 | 0.8% | 35.5% |
| FOR_ITER STORE_FAST | 204,540 | 0.8% | 36.3% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 201,620 | 0.8% | 37.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR | 201,460 | 0.8% | 37.8% |
| LOAD_ATTR_SLOT LOAD_FAST | 198,819 | 0.8% | 38.6% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 194,960 | 0.8% | 39.4% |
| LOAD_FAST CONTAINS_OP | 194,080 | 0.8% | 40.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 179,267 | 0.7% | 40.8% |
| RETURN_CONST POP_TOP | 179,215 | 0.7% | 41.5% |
| POP_TOP LOAD_FAST | 177,539 | 0.7% | 42.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 174,060 | 0.7% | 42.9% |
| LOAD_ATTR LOAD_FAST | 173,984 | 0.7% | 43.5% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 166,429 | 0.6% | 44.2% |
| CACHE RESUME_CHECK | 164,630 | 0.6% | 44.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 160,300 | 0.6% | 45.4% |
| STORE_SUBSCR_DICT JUMP_BACKWARD | 160,120 | 0.6% | 46.1% |
| LOAD_ATTR_SLOT CALL_BUILTIN_FAST | 160,080 | 0.6% | 46.7% |
| CALL_BUILTIN_FAST LOAD_FAST_LOAD_FAST | 159,980 | 0.6% | 47.3% |
| LOAD_ATTR_SLOT STORE_SUBSCR_DICT | 159,960 | 0.6% | 47.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 159,118 | 0.6% | 48.5% |
| POP_TOP RESUME_CHECK | 158,280 | 0.6% | 49.1% |
| GET_AWAITABLE LOAD_CONST | 151,360 | 0.6% | 49.7% |
| STORE_ATTR LOAD_FAST_LOAD_FAST | 148,860 | 0.6% | 50.3% |
| POP_JUMP_IF_FALSE LOAD_CONST | 148,484 | 0.6% | 50.9% |
| SEND_GEN POP_TOP | 147,080 | 0.6% | 51.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 146,940 | 0.6% | 52.0% |
| LOAD_CONST SEND_GEN | 146,220 | 0.6% | 52.6% |
| LOAD_ATTR TO_BOOL_BOOL | 145,743 | 0.6% | 53.1% |
| LOAD_FAST RETURN_VALUE | 139,881 | 0.5% | 53.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 139,106 | 0.5% | 54.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 139,003 | 0.5% | 54.8% |
| CALL STORE_FAST | 137,747 | 0.5% | 55.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 137,745 | 0.5% | 55.8% |
| RETURN_GENERATOR GET_AWAITABLE | 130,160 | 0.5% | 56.3% |
| LOAD_CONST COMPARE_OP_INT | 127,864 | 0.5% | 56.8% |
| RETURN_VALUE STORE_FAST | 122,981 | 0.5% | 57.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 118,106 | 0.5% | 57.8% |
| LOAD_CONST BINARY_OP | 116,959 | 0.5% | 58.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 113,583 | 0.4% | 58.7% |
| POP_TOP RETURN_CONST | 109,577 | 0.4% | 59.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 106,423 | 0.4% | 59.5% |
| RETURN_CONST INTERPRETER_EXIT | 106,286 | 0.4% | 59.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 106,065 | 0.4% | 60.3% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 105,120 | 0.4% | 60.7% |
| PUSH_NULL LOAD_FAST | 104,003 | 0.4% | 61.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 103,143 | 0.4% | 61.5% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 102,414 | 0.4% | 61.9% |
| RETURN_VALUE RETURN_VALUE | 98,960 | 0.4% | 62.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 98,480 | 0.4% | 62.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 96,026 | 0.4% | 63.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 93,249 | 0.4% | 63.4% |
| CALL_LEN LOAD_FAST | 92,152 | 0.4% | 63.8% |
| LOAD_CONST CALL_KW | 91,681 | 0.4% | 64.1% |
| PUSH_NULL LOAD_CONST | 90,960 | 0.4% | 64.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 87,320 | 0.3% | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 81,394 | 0.3% | 65.1% |
| LOAD_FAST STORE_ATTR_SLOT | 80,940 | 0.3% | 65.5% |
| RETURN_VALUE END_SEND | 80,400 | 0.3% | 65.8% |
| RETURN_VALUE TO_BOOL_BOOL | 79,682 | 0.3% | 66.1% |
| LOAD_CONST STORE_FAST | 79,505 | 0.3% | 66.4% |
| END_SEND POP_TOP | 79,440 | 0.3% | 66.7% |
| RETURN_VALUE INTERPRETER_EXIT | 79,284 | 0.3% | 67.0% |
| NOP LOAD_FAST | 76,731 | 0.3% | 67.3% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 75,388 | 0.3% | 67.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 75,362 | 0.3% | 67.9% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 75,102 | 0.3% | 68.2% |
| LOAD_FAST CALL_LEN | 72,720 | 0.3% | 68.5% |
| LOAD_FAST CALL | 72,503 | 0.3% | 68.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 72,420 | 0.3% | 69.0% |
| END_SEND STORE_FAST | 69,920 | 0.3% | 69.3% |
| LOAD_CONST LOAD_CONST | 69,532 | 0.3% | 69.6% |
| RETURN_CONST END_SEND | 68,080 | 0.3% | 69.8% |
| LOAD_FAST COMPARE_OP_INT | 67,880 | 0.3% | 70.1% |
| DICT_MERGE CALL_FUNCTION_EX | 67,601 | 0.3% | 70.3% |
| BUILD_MAP LOAD_FAST | 67,561 | 0.3% | 70.6% |
| CALL_KW RESUME_CHECK | 67,260 | 0.3% | 70.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 67,200 | 0.3% | 71.1% |
| LOAD_FAST DICT_MERGE | 66,320 | 0.3% | 71.4% |
| LOAD_GLOBAL_MODULE CALL_BUILTIN_FAST | 63,920 | 0.2% | 71.6% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,860 | 46.8% |
| LOAD_CONST | 19,520 | 27.8% |
| BINARY_OP | 16,200 | 23.1% |
| BINARY_OP_ADD_INT | 1,640 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 32,320 | 46.0% |
| STORE_FAST | 18,360 | 26.1% |
| BINARY_OP | 16,240 | 23.1% |
| RETURN_VALUE | 1,360 | 1.9% |
| GET_ITER | 360 | 0.5% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 164,630 | 78.3% |
| RETURN_GENERATOR | 18,320 | 8.7% |
| COPY_FREE_VARS | 13,340 | 6.3% |
| POP_TOP | 11,160 | 5.3% |
| RESUME | 2,380 | 1.1% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 8,140 | 89.3% |
| RETURN_VALUE | 800 | 8.8% |
| CALL | 160 | 1.8% |
| LOAD_ATTR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 9,120 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,842 | 48.9% |
| LOAD_GLOBAL_MODULE | 764 | 20.3% |
| CALL | 480 | 12.7% |
| RETURN_VALUE | 240 | 6.4% |
| LOAD_ATTR | 240 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,686 | 97.9% |
| STORE_FAST | 80 | 2.1% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_STR_1 | 80 | 66.7% |
| BINARY_OP | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,441 | 58.1% |
| BINARY_SUBSCR | 281 | 11.3% |
| LOAD_FAST | 240 | 9.7% |
| LOAD_GLOBAL_MODULE | 200 | 8.1% |
| LOAD_FAST_LOAD_FAST | 80 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 440 | 18.0% |
| BINARY_SUBSCR | 281 | 11.5% |
| STORE_FAST | 281 | 11.5% |
| BINARY_SUBSCR_LIST_INT | 240 | 9.8% |
| BUILD_TUPLE | 160 | 6.6% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,200 | 71.9% |
| BUILD_TUPLE | 320 | 10.5% |
| LOAD_ATTR_MODULE | 280 | 9.2% |
| LOAD_GLOBAL | 220 | 7.2% |
| LOAD_ATTR | 40 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,900 | 94.8% |
| EXTENDED_ARG | 160 | 5.2% |


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 320 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 33,600 | 99.0% |
| LOAD_FAST | 262 | 0.8% |
| CALL | 61 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,600 | 99.0% |
| LOAD_CONST | 142 | 0.4% |
| LOAD_GLOBAL_MODULE | 120 | 0.4% |
| RETURN_CONST | 61 | 0.2% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80,400 | 53.2% |
| RETURN_CONST | 68,080 | 45.1% |
| SEND | 2,560 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 79,440 | 52.6% |
| STORE_FAST | 69,920 | 46.3% |
| RETURN_VALUE | 880 | 0.6% |
| UNPACK_SEQUENCE | 240 | 0.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 200 | 0.1% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 19,042 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 19,042 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,400 | 84.3% |
| LOAD_ATTR | 100 | 6.0% |
| CONVERT_VALUE | 80 | 4.8% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 3.6% |
| LOAD_FAST_LOAD_FAST | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,420 | 85.5% |
| BUILD_STRING | 240 | 14.5% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 32,600 | 46.0% |
| LOAD_FAST | 22,840 | 32.2% |
| CALL_BUILTIN_CLASS | 12,540 | 17.7% |
| LOAD_ATTR_INSTANCE_VALUE | 820 | 1.2% |
| CALL | 560 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 43,661 | 61.6% |
| FOR_ITER_LIST | 17,459 | 24.6% |
| FOR_ITER_RANGE | 4,100 | 5.8% |
| LOAD_FAST_AND_CLEAR | 2,201 | 3.1% |
| CALL_PY_EXACT_ARGS | 1,560 | 2.2% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 106,286 | 50.7% |
| RETURN_VALUE | 79,284 | 37.8% |
| RETURN_GENERATOR | 18,400 | 8.8% |
| YIELD_VALUE | 5,700 | 2.7% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 220 | 84.6% |
| POP_TOP | 40 | 15.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 260 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,862 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 3,402 | 49.6% |
| LOAD_FAST | 1,680 | 24.5% |
| STORE_NAME | 1,120 | 16.3% |
| LOAD_CONST | 420 | 6.1% |
| STORE_DEREF | 160 | 2.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,822 | 28.7% |
| RESUME_CHECK | 28,624 | 28.5% |
| POP_JUMP_IF_FALSE | 14,364 | 14.3% |
| POP_JUMP_IF_TRUE | 9,681 | 9.6% |
| POP_JUMP_IF_NOT_NONE | 8,760 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,731 | 76.3% |
| LOAD_GLOBAL_MODULE | 15,982 | 15.9% |
| LOAD_GLOBAL_BUILTIN | 2,640 | 2.6% |
| LOAD_GLOBAL | 1,420 | 1.4% |
| NOP | 1,262 | 1.3% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,560 | 51.3% |
| STORE_FAST | 420 | 13.8% |
| COPY | 400 | 13.2% |
| STORE_SUBSCR | 240 | 7.9% |
| SWAP | 240 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 620 | 20.4% |
| EXTENDED_ARG | 520 | 17.1% |
| RETURN_CONST | 500 | 16.4% |
| RERAISE | 400 | 13.2% |
| LOAD_FAST | 260 | 8.6% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 179,215 | 31.7% |
| SEND_GEN | 147,080 | 26.0% |
| END_SEND | 79,440 | 14.0% |
| CALL_METHOD_DESCRIPTOR_O | 75,388 | 13.3% |
| CALL_FUNCTION_EX | 24,800 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 177,539 | 31.4% |
| RESUME_CHECK | 158,280 | 28.0% |
| RETURN_CONST | 109,577 | 19.4% |
| LOAD_CONST | 42,724 | 7.6% |
| ENTER_EXECUTOR | 31,500 | 5.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 980 | 32.0% |
| CALL | 680 | 22.2% |
| LOAD_ATTR | 340 | 11.1% |
| CLEANUP_THROW | 320 | 10.5% |
| CALL_BUILTIN_FAST | 300 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,920 | 62.7% |
| LOAD_GLOBAL | 660 | 21.6% |
| LOAD_GLOBAL_MODULE | 320 | 10.5% |
| LOAD_FAST | 160 | 5.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 174,060 | 60.0% |
| LOAD_FAST | 63,263 | 21.8% |
| LOAD_ATTR_SLOT | 31,980 | 11.0% |
| LOAD_ATTR | 18,402 | 6.3% |
| LOAD_NAME | 560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 104,003 | 35.9% |
| LOAD_CONST | 90,960 | 31.4% |
| LOAD_FAST_LOAD_FAST | 60,221 | 20.8% |
| CALL | 31,362 | 10.8% |
| LOAD_DEREF | 800 | 0.3% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 56,540 | 35.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 32,320 | 20.2% |
| ENTER_EXECUTOR | 23,680 | 14.8% |
| CACHE | 18,320 | 11.5% |
| CALL_KW | 17,200 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 130,160 | 81.5% |
| INTERPRETER_EXIT | 18,400 | 11.5% |
| LIST_APPEND | 8,080 | 5.1% |
| CALL | 1,520 | 1.0% |
| CALL_BUILTIN_O | 600 | 0.4% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 139,881 | 26.9% |
| RETURN_VALUE | 98,960 | 19.0% |
| LOAD_ATTR_INSTANCE_VALUE | 58,123 | 11.2% |
| CALL | 37,741 | 7.3% |
| CALL_FUNCTION_EX | 34,462 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 122,981 | 23.7% |
| RETURN_VALUE | 98,960 | 19.0% |
| END_SEND | 80,400 | 15.5% |
| TO_BOOL_BOOL | 79,682 | 15.3% |
| INTERPRETER_EXIT | 79,284 | 15.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,581 | 42.5% |
| LOAD_CONST | 920 | 24.7% |
| STORE_SUBSCR | 421 | 11.3% |
| BINARY_OP | 240 | 6.4% |
| LOAD_FAST_LOAD_FAST | 200 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 800 | 21.5% |
| LOAD_FAST | 520 | 14.0% |
| STORE_SUBSCR | 421 | 11.3% |
| RETURN_CONST | 381 | 10.2% |
| JUMP_BACKWARD | 360 | 9.7% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,942 | 28.3% |
| LOAD_ATTR | 20,760 | 25.6% |
| LOAD_ATTR_INSTANCE_VALUE | 19,922 | 24.6% |
| LOAD_ATTR_SLOT | 8,320 | 10.3% |
| CALL | 1,960 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 40,564 | 50.0% |
| POP_JUMP_IF_TRUE | 31,620 | 39.0% |
| TO_BOOL_BOOL | 5,500 | 6.8% |
| TO_BOOL | 1,541 | 1.9% |
| TO_BOOL_INT | 660 | 0.8% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 560 | 50.0% |
| LOAD_ATTR_MODULE | 520 | 46.4% |
| LOAD_ATTR | 40 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,120 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 280 | 77.8% |
| LOAD_ATTR | 40 | 11.1% |
| LOAD_FAST | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 160 | 44.4% |
| LOAD_CONST | 160 | 44.4% |
| CALL_BUILTIN_CLASS | 40 | 11.1% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 8,800 | 97.8% |
| TO_BOOL | 100 | 1.1% |
| TO_BOOL_INT | 80 | 0.9% |
| TO_BOOL_LIST | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,160 | 90.7% |
| COPY | 420 | 4.7% |
| RETURN_VALUE | 320 | 3.6% |
| STORE_FAST | 80 | 0.9% |
| CALL_PY_EXACT_ARGS | 20 | 0.2% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 116,959 | 54.2% |
| BINARY_OP | 21,041 | 9.8% |
| LOAD_FAST_LOAD_FAST | 16,380 | 7.6% |
| BINARY_SLICE | 16,240 | 7.5% |
| LOAD_GLOBAL_MODULE | 12,780 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,021 | 24.6% |
| LOAD_FAST | 49,180 | 22.8% |
| TO_BOOL_INT | 43,420 | 20.1% |
| BINARY_OP | 21,041 | 9.8% |
| BINARY_SLICE | 16,200 | 7.5% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 40.0% |
| STORE_FAST | 80 | 40.0% |
| DICT_UPDATE | 20 | 10.0% |
| LOAD_CONST | 20 | 10.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,060 | 24.6% |
| LOAD_ATTR_SLOT | 3,840 | 18.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,680 | 13.0% |
| SWAP | 2,201 | 10.7% |
| LOAD_FAST | 1,280 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,860 | 33.3% |
| STORE_FAST | 6,500 | 31.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,640 | 12.8% |
| SWAP | 2,201 | 10.7% |
| BUILD_TUPLE | 320 | 1.6% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 32,640 | 45.7% |
| LOAD_CONST | 32,500 | 45.5% |
| LOAD_FAST | 2,220 | 3.1% |
| RESUME_CHECK | 1,280 | 1.8% |
| DICT_UPDATE | 720 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,561 | 94.6% |
| RETURN_VALUE | 800 | 1.1% |
| STORE_FAST | 761 | 1.1% |
| LOAD_GLOBAL_MODULE | 600 | 0.8% |
| EXTENDED_ARG | 580 | 0.8% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 360 | 64.3% |
| LOAD_GLOBAL_MODULE | 140 | 25.0% |
| LOAD_ATTR | 40 | 7.1% |
| LOAD_GLOBAL | 20 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 560 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,240 | 95.8% |
| BINARY_OP_ADD_INT | 1,340 | 4.0% |
| LOAD_CONST | 60 | 0.2% |
| BINARY_OP | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 33,600 | 99.8% |
| BINARY_SUBSCR | 60 | 0.2% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 680 | 73.9% |
| FORMAT_SIMPLE | 240 | 26.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 420 | 45.7% |
| STORE_FAST | 240 | 26.1% |
| LIST_APPEND | 160 | 17.4% |
| CALL | 100 | 10.9% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,342 | 68.8% |
| LOAD_GLOBAL_BUILTIN | 16,500 | 18.2% |
| LOAD_FAST_LOAD_FAST | 4,280 | 4.7% |
| LOAD_GLOBAL_MODULE | 2,060 | 2.3% |
| BINARY_OP | 960 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 32,640 | 36.0% |
| CALL | 17,440 | 19.3% |
| CALL_ISINSTANCE | 16,440 | 18.1% |
| RETURN_VALUE | 11,600 | 12.8% |
| LOAD_CONST | 3,623 | 4.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,503 | 20.2% |
| LOAD_ATTR_INSTANCE_VALUE | 50,562 | 14.1% |
| LOAD_FAST_LOAD_FAST | 46,541 | 12.9% |
| BINARY_SLICE | 32,320 | 9.0% |
| PUSH_NULL | 31,362 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 137,747 | 38.3% |
| RETURN_VALUE | 37,741 | 10.5% |
| LOAD_CONST | 32,880 | 9.1% |
| LOAD_FAST | 29,167 | 8.1% |
| POP_TOP | 22,853 | 6.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 67,601 | 72.1% |
| ENTER_EXECUTOR | 19,420 | 20.7% |
| CALL_INTRINSIC_1 | 4,500 | 4.8% |
| LOAD_FAST | 1,762 | 1.9% |
| BUILD_MAP | 160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 34,462 | 36.8% |
| RESUME_CHECK | 32,481 | 34.6% |
| POP_TOP | 24,800 | 26.4% |
| RETURN_GENERATOR | 640 | 0.7% |
| STORE_FAST | 580 | 0.6% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 5,080 | 94.1% |
| RERAISE | 320 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 4,500 | 83.3% |
| BUILD_MAP | 420 | 7.8% |
| RERAISE | 320 | 5.9% |
| LOAD_CONST | 160 | 3.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 91,681 | 92.3% |
| ENTER_EXECUTOR | 7,640 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 67,260 | 67.7% |
| RETURN_GENERATOR | 17,200 | 17.3% |
| STORE_FAST | 10,041 | 10.1% |
| RETURN_VALUE | 3,200 | 3.2% |
| LOAD_FAST | 320 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40,679 | 68.4% |
| LOAD_FAST | 8,600 | 14.5% |
| LOAD_CONST | 5,280 | 8.9% |
| COMPARE_OP | 1,699 | 2.9% |
| LOAD_ATTR_MODULE | 900 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 54,679 | 92.0% |
| COMPARE_OP | 1,699 | 2.9% |
| COMPARE_OP_INT | 1,580 | 2.7% |
| POP_JUMP_IF_TRUE | 680 | 1.1% |
| COMPARE_OP_STR | 620 | 1.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 194,080 | 79.9% |
| LOAD_GLOBAL_MODULE | 26,320 | 10.8% |
| LOAD_ATTR_MODULE | 16,600 | 6.8% |
| BUILD_TUPLE | 2,340 | 1.0% |
| LOAD_ATTR_INSTANCE_VALUE | 900 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 194,960 | 80.3% |
| POP_JUMP_IF_FALSE | 47,420 | 19.5% |
| SWAP | 320 | 0.1% |
| STORE_FAST | 120 | 0.0% |
| EXTENDED_ARG | 20 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 80 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,440 | 43.5% |
| CALL_LEN | 3,740 | 15.6% |
| BINARY_OP | 3,000 | 12.5% |
| LOAD_FAST | 2,939 | 12.2% |
| SWAP | 1,280 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 11,320 | 47.1% |
| TO_BOOL_INT | 6,800 | 28.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,019 | 8.4% |
| TO_BOOL | 820 | 3.4% |
| COMPARE_OP_INT | 800 | 3.3% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 13,340 | 71.0% |
| CALL_PY_EXACT_ARGS | 3,698 | 19.7% |
| LOAD_ATTR_PROPERTY | 800 | 4.3% |
| CALL | 662 | 3.5% |
| CALL_ALLOC_AND_ENTER_INIT | 200 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 17,580 | 93.6% |
| RESUME | 680 | 3.6% |
| RETURN_GENERATOR | 440 | 2.3% |
| MAKE_CELL | 80 | 0.4% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 183 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122 | 66.7% |
| RETURN_CONST | 61 | 33.3% |


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 160 | 50.0% |
| LOAD_FAST | 160 | 50.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,320 | 98.1% |
| RETURN_VALUE | 800 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 341 | 0.5% |
| CALL | 80 | 0.1% |
| LOAD_ATTR | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 67,601 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 740 | 97.4% |
| BUILD_CONST_KEY_MAP | 20 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 720 | 94.7% |
| EXTENDED_ARG | 20 | 2.6% |
| STORE_NAME | 20 | 2.6% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 31,500 | 41.1% |
| CALL_LIST_APPEND | 16,280 | 21.2% |
| EXTENDED_ARG | 7,960 | 10.4% |
| STORE_FAST | 7,840 | 10.2% |
| LIST_APPEND | 7,720 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 23,680 | 30.9% |
| CALL_FUNCTION_EX | 19,420 | 25.3% |
| LOAD_GLOBAL_MODULE | 8,080 | 10.5% |
| CALL | 7,720 | 10.1% |
| CALL_KW | 7,640 | 10.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 9,480 | 36.4% |
| POP_JUMP_IF_NONE | 7,680 | 29.5% |
| LOAD_CONST | 5,420 | 20.8% |
| BUILD_MAP | 580 | 2.2% |
| POP_EXCEPT | 520 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,080 | 61.8% |
| ENTER_EXECUTOR | 7,960 | 30.6% |
| JUMP_BACKWARD | 940 | 3.6% |
| FOR_ITER_LIST | 420 | 1.6% |
| POP_JUMP_IF_FALSE | 280 | 1.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 204,582 | 81.6% |
| GET_ITER | 43,661 | 17.4% |
| FOR_ITER | 1,260 | 0.5% |
| LOAD_FAST | 920 | 0.4% |
| SWAP | 361 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 204,540 | 81.5% |
| LOAD_FAST | 40,680 | 16.2% |
| RETURN_CONST | 1,541 | 0.6% |
| FOR_ITER | 1,260 | 0.5% |
| FOR_ITER_LIST | 840 | 0.3% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 130,160 | 86.0% |
| BEFORE_ASYNC_WITH | 9,120 | 6.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 8,960 | 5.9% |
| RETURN_VALUE | 1,040 | 0.7% |
| LOAD_FAST | 640 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 151,360 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 200 | 90.9% |
| STORE_NAME | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 180 | 81.8% |
| STORE_FAST | 40 | 18.2% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 500 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 220 | 44.0% |
| IMPORT_FROM | 200 | 40.0% |
| STORE_FAST | 80 | 16.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 353,600 | 84.5% |
| LOAD_FAST | 26,220 | 6.3% |
| LOAD_ATTR_MODULE | 15,960 | 3.8% |
| LOAD_ATTR | 12,120 | 2.9% |
| LOAD_FAST_LOAD_FAST | 8,080 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 416,180 | 99.5% |
| RETURN_VALUE | 1,600 | 0.4% |
| POP_JUMP_IF_TRUE | 580 | 0.1% |
| STORE_FAST | 80 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 160,120 | 73.6% |
| POP_JUMP_IF_TRUE | 33,820 | 15.5% |
| STORE_FAST | 8,940 | 4.1% |
| POP_TOP | 6,378 | 2.9% |
| LIST_APPEND | 3,741 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 204,582 | 94.0% |
| FOR_ITER_LIST | 5,039 | 2.3% |
| FOR_ITER_TUPLE | 3,280 | 1.5% |
| LOAD_FAST | 1,441 | 0.7% |
| FOR_ITER_RANGE | 1,420 | 0.7% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,560 | 87.7% |
| RESUME | 1,200 | 12.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 6,420 | 65.8% |
| SEND | 3,340 | 34.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 48,640 | 45.7% |
| STORE_FAST | 34,726 | 32.6% |
| POP_TOP | 17,380 | 16.3% |
| POP_JUMP_IF_FALSE | 4,661 | 4.4% |
| LOAD_FAST | 240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,204 | 52.8% |
| STORE_FAST | 24,400 | 22.9% |
| LOAD_DEREF | 8,240 | 7.7% |
| BINARY_OP | 8,000 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 6,361 | 6.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 8,080 | 70.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,400 | 20.9% |
| RETURN_VALUE | 560 | 4.9% |
| BUILD_STRING | 160 | 1.4% |
| BUILD_TUPLE | 80 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,720 | 67.4% |
| JUMP_BACKWARD | 3,741 | 32.6% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 3,840 | 72.2% |
| LOAD_FAST | 980 | 18.4% |
| BINARY_SLICE | 240 | 4.5% |
| LOAD_CONST | 240 | 4.5% |
| LOAD_ATTR | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 5,080 | 95.5% |
| LOAD_FAST | 160 | 3.0% |
| LOAD_NAME | 60 | 1.1% |
| STORE_NAME | 20 | 0.4% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 517,353 | 78.0% |
| LOAD_ATTR_WITH_HINT | 34,180 | 5.2% |
| LOAD_GLOBAL_BUILTIN | 32,880 | 5.0% |
| LOAD_GLOBAL_MODULE | 30,920 | 4.7% |
| LOAD_ATTR | 20,822 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 173,984 | 26.2% |
| TO_BOOL_BOOL | 145,743 | 22.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 47,240 | 7.1% |
| LOAD_GLOBAL_MODULE | 41,860 | 6.3% |
| CALL_PY_EXACT_ARGS | 35,025 | 5.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,927 | 21.2% |
| GET_AWAITABLE | 151,360 | 13.3% |
| POP_JUMP_IF_FALSE | 148,484 | 13.1% |
| PUSH_NULL | 90,960 | 8.0% |
| LOAD_CONST | 69,532 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 213,270 | 18.8% |
| SEND_GEN | 146,220 | 12.9% |
| COMPARE_OP_INT | 127,864 | 11.2% |
| BINARY_OP | 116,959 | 10.3% |
| CALL_KW | 91,681 | 8.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 17,520 | 19.8% |
| RESUME_CHECK | 10,220 | 11.6% |
| POP_JUMP_IF_FALSE | 9,440 | 10.7% |
| STORE_DEREF | 9,361 | 10.6% |
| LOAD_DEREF | 8,400 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 17,520 | 19.8% |
| POP_JUMP_IF_NONE | 9,120 | 10.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,640 | 9.8% |
| LOAD_DEREF | 8,400 | 9.5% |
| LOAD_ATTR_METHOD_NO_DICT | 8,200 | 9.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 723,480 | 15.2% |
| STORE_FAST | 657,392 | 13.8% |
| RESUME_CHECK | 469,108 | 9.8% |
| POP_JUMP_IF_TRUE | 451,307 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 401,258 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 887,200 | 18.6% |
| LOAD_ATTR_INSTANCE_VALUE | 752,107 | 15.8% |
| LOAD_ATTR | 517,353 | 10.9% |
| LOAD_CONST | 240,927 | 5.1% |
| LOAD_ATTR_WITH_HINT | 226,920 | 4.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,201 | 93.2% |
| LOAD_FAST_AND_CLEAR | 160 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,201 | 93.2% |
| LOAD_FAST_AND_CLEAR | 160 | 6.8% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,120 | 48.3% |
| LOAD_ATTR_INSTANCE_VALUE | 8,060 | 47.9% |
| POP_TOP | 480 | 2.9% |
| JUMP_FORWARD | 80 | 0.5% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 16,080 | 95.6% |
| POP_JUMP_IF_NOT_NONE | 480 | 2.9% |
| CALL | 80 | 0.5% |
| SWAP | 80 | 0.5% |
| LOAD_FAST | 40 | 0.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160,300 | 14.9% |
| CALL_BUILTIN_FAST | 159,980 | 14.9% |
| STORE_ATTR | 148,860 | 13.9% |
| STORE_ATTR_INSTANCE_VALUE | 103,143 | 9.6% |
| LOAD_FAST_LOAD_FAST | 87,320 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 320,060 | 29.8% |
| STORE_ATTR | 201,460 | 18.8% |
| STORE_ATTR_INSTANCE_VALUE | 106,065 | 9.9% |
| STORE_ATTR_SLOT | 98,480 | 9.2% |
| LOAD_FAST_LOAD_FAST | 87,320 | 8.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,720 | 11.7% |
| LOAD_FAST | 3,500 | 11.0% |
| STORE_FAST | 3,340 | 10.5% |
| RESUME_CHECK | 2,380 | 7.5% |
| RESUME | 2,320 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 11,420 | 35.8% |
| LOAD_ATTR | 4,880 | 15.3% |
| LOAD_GLOBAL_BUILTIN | 4,640 | 14.6% |
| LOAD_FAST | 4,480 | 14.1% |
| CALL | 1,320 | 4.1% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 320 | 21.9% |
| STORE_NAME | 300 | 20.5% |
| RESUME | 260 | 17.8% |
| LOAD_CONST | 200 | 13.7% |
| BINARY_OP | 80 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 560 | 38.4% |
| LOAD_ATTR | 440 | 30.1% |
| STORE_NAME | 260 | 17.8% |
| CALL | 80 | 5.5% |
| LOAD_NAME | 40 | 2.7% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 400 | 39.2% |
| CALL | 160 | 15.7% |
| LOAD_FAST | 160 | 15.7% |
| LOAD_FAST_LOAD_FAST | 100 | 9.8% |
| LOAD_SUPER_ATTR_ATTR | 100 | 9.8% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 5,404 | 65.7% |
| CALL_PY_EXACT_ARGS | 2,101 | 25.5% |
| CALL | 220 | 2.7% |
| CALL_FUNCTION_EX | 160 | 1.9% |
| CALL_KW | 160 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 5,404 | 65.7% |
| RESUME_CHECK | 1,721 | 20.9% |
| RETURN_GENERATOR | 940 | 11.4% |
| RESUME | 160 | 1.9% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,920 | 80.5% |
| LOAD_FAST | 2,880 | 18.0% |
| LOAD_ATTR_INSTANCE_VALUE | 180 | 1.1% |
| LOAD_ATTR | 60 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 9,480 | 59.1% |
| LOAD_CONST | 5,640 | 35.2% |
| DICT_UPDATE | 740 | 4.6% |
| CALL_FUNCTION_EX | 160 | 1.0% |
| BUILD_MAP | 20 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 462,110 | 32.4% |
| IS_OP | 416,180 | 29.2% |
| COMPARE_OP_INT | 244,657 | 17.1% |
| TO_BOOL_NONE | 75,102 | 5.3% |
| TO_BOOL_INT | 55,540 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 723,480 | 50.7% |
| LOAD_GLOBAL_BUILTIN | 306,855 | 21.5% |
| LOAD_CONST | 148,484 | 10.4% |
| RETURN_CONST | 113,583 | 8.0% |
| LOAD_GLOBAL_MODULE | 75,362 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 57,120 | 34.5% |
| LOAD_ATTR_INSTANCE_VALUE | 53,801 | 32.5% |
| LOAD_FAST | 44,170 | 26.6% |
| LOAD_DEREF | 9,120 | 5.5% |
| LOAD_ATTR | 800 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,249 | 56.3% |
| LOAD_GLOBAL_BUILTIN | 24,700 | 14.9% |
| LOAD_DEREF | 17,520 | 10.6% |
| LOAD_CONST | 10,900 | 6.6% |
| LOAD_FAST_LOAD_FAST | 8,640 | 5.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 118,106 | 90.0% |
| LOAD_ATTR_INSTANCE_VALUE | 10,080 | 7.7% |
| CALL_BUILTIN_FAST | 720 | 0.5% |
| LOAD_GLOBAL_MODULE | 620 | 0.5% |
| LOAD_FAST_CHECK | 480 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 55,264 | 42.1% |
| LOAD_FAST_LOAD_FAST | 30,161 | 23.0% |
| LOAD_GLOBAL_MODULE | 23,702 | 18.1% |
| LOAD_GLOBAL_BUILTIN | 8,780 | 6.7% |
| NOP | 8,760 | 6.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 329,813 | 57.0% |
| CONTAINS_OP | 194,960 | 33.7% |
| TO_BOOL | 31,620 | 5.5% |
| TO_BOOL_NONE | 8,340 | 1.4% |
| TO_BOOL_INT | 6,040 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 451,307 | 78.0% |
| LOAD_GLOBAL_MODULE | 42,103 | 7.3% |
| JUMP_BACKWARD | 33,820 | 5.8% |
| RETURN_CONST | 26,220 | 4.5% |
| NOP | 9,681 | 1.7% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 260 | 52.0% |
| POP_TOP | 160 | 32.0% |
| LOAD_CONST | 80 | 16.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 240 | 75.0% |
| PUSH_EXC_INFO | 80 | 25.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 400 | 45.5% |
| CALL_INTRINSIC_1 | 320 | 36.4% |
| POP_TOP | 160 | 18.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 320 | 57.1% |
| COPY | 160 | 28.6% |
| PUSH_EXC_INFO | 80 | 14.3% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 113,583 | 29.6% |
| POP_TOP | 109,577 | 28.5% |
| STORE_ATTR | 50,240 | 13.1% |
| STORE_ATTR_SLOT | 27,960 | 7.3% |
| STORE_FAST | 27,200 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 179,215 | 46.6% |
| INTERPRETER_EXIT | 106,286 | 27.7% |
| END_SEND | 68,080 | 17.7% |
| EXIT_INIT_CHECK | 19,042 | 5.0% |
| TO_BOOL_BOOL | 9,323 | 2.4% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,140 | 54.7% |
| JUMP_BACKWARD_NO_INTERRUPT | 3,340 | 35.5% |
| SEND | 920 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 2,800 | 29.8% |
| END_SEND | 2,560 | 27.2% |
| POP_TOP | 1,560 | 16.6% |
| SEND_GEN | 1,560 | 16.6% |
| SEND | 920 | 9.8% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,402 | 99.4% |
| SET_FUNCTION_ATTRIBUTE | 20 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,222 | 64.9% |
| STORE_DEREF | 640 | 18.7% |
| LOAD_FAST | 200 | 5.8% |
| STORE_NAME | 180 | 5.3% |
| LOAD_GLOBAL_MODULE | 160 | 4.7% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 201,460 | 89.3% |
| LOAD_FAST | 20,241 | 9.0% |
| STORE_ATTR | 3,160 | 1.4% |
| SWAP | 360 | 0.2% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 148,860 | 66.0% |
| RETURN_CONST | 50,240 | 22.3% |
| LOAD_DEREF | 8,080 | 3.6% |
| STORE_ATTR_INSTANCE_VALUE | 5,360 | 2.4% |
| LOAD_FAST | 3,580 | 1.6% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 16,120 | 74.2% |
| RETURN_VALUE | 1,760 | 8.1% |
| LOAD_CONST | 1,160 | 5.3% |
| SET_FUNCTION_ATTRIBUTE | 640 | 2.9% |
| BINARY_OP_SUBTRACT_INT | 460 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 9,361 | 43.1% |
| LOAD_FAST_LOAD_FAST | 8,080 | 37.2% |
| LOAD_FAST | 2,801 | 12.9% |
| LOAD_CONST | 880 | 4.1% |
| LOAD_GLOBAL_MODULE | 242 | 1.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 204,540 | 22.8% |
| CALL | 137,747 | 15.4% |
| RETURN_VALUE | 122,981 | 13.7% |
| LOAD_CONST | 79,505 | 8.9% |
| END_SEND | 69,920 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 657,392 | 73.4% |
| LOAD_GLOBAL_BUILTIN | 43,640 | 4.9% |
| LOAD_GLOBAL_MODULE | 40,983 | 4.6% |
| JUMP_FORWARD | 34,726 | 3.9% |
| NOP | 28,822 | 3.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 2,400 | 66.6% |
| FOR_ITER_RANGE | 360 | 10.0% |
| FOR_ITER_LIST | 260 | 7.2% |
| FOR_ITER | 223 | 6.2% |
| COPY | 160 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 2,400 | 66.6% |
| LOAD_ATTR | 580 | 16.1% |
| LOAD_ATTR_METHOD_NO_DICT | 183 | 5.1% |
| LOAD_ATTR_PROPERTY | 120 | 3.3% |
| STORE_ATTR | 80 | 2.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 23,960 | 83.2% |
| UNPACK_SEQUENCE_TUPLE | 1,380 | 4.8% |
| UNPACK_SEQUENCE_LIST | 1,140 | 4.0% |
| UNPACK_SEQUENCE | 900 | 3.1% |
| STORE_FAST_STORE_FAST | 400 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,740 | 79.0% |
| LOAD_GLOBAL_MODULE | 2,000 | 6.9% |
| STORE_FAST | 1,800 | 6.2% |
| NOP | 1,000 | 3.5% |
| LOAD_GLOBAL | 400 | 1.4% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 42.9% |
| CALL | 40 | 28.6% |
| LOAD_CONST | 20 | 14.3% |
| LOAD_FAST | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 28.6% |
| LOAD_GLOBAL_MODULE | 40 | 28.6% |
| LOAD_CONST | 20 | 14.3% |
| LOAD_FAST | 20 | 14.3% |
| LOAD_NAME | 20 | 14.3% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,120 | 37.1% |
| LOAD_CONST | 500 | 16.6% |
| CALL | 480 | 15.9% |
| LOAD_NAME | 260 | 8.6% |
| IMPORT_NAME | 220 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,620 | 53.6% |
| EXTENDED_ARG | 360 | 11.9% |
| LOAD_NAME | 300 | 9.9% |
| RETURN_CONST | 280 | 9.3% |
| LOAD_BUILD_CLASS | 220 | 7.3% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 2,201 | 16.1% |
| LOAD_FAST_AND_CLEAR | 2,201 | 16.1% |
| LOAD_FAST | 1,681 | 12.3% |
| LOAD_ATTR | 1,500 | 11.0% |
| BINARY_OP_ADD_INT | 1,340 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,440 | 25.2% |
| BUILD_LIST | 2,201 | 16.1% |
| STORE_ATTR_INSTANCE_VALUE | 2,019 | 14.8% |
| LOAD_CONST | 1,321 | 9.7% |
| COPY | 1,280 | 9.4% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 600 | 28.6% |
| CALL | 280 | 13.3% |
| END_SEND | 240 | 11.4% |
| LOAD_FAST | 200 | 9.5% |
| FOR_ITER_LIST | 200 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 900 | 42.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 620 | 29.5% |
| UNPACK_SEQUENCE_TUPLE | 300 | 14.3% |
| STORE_FAST | 120 | 5.7% |
| UNPACK_SEQUENCE_LIST | 60 | 2.9% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 7,280 | 56.1% |
| SEND | 2,800 | 21.6% |
| RETURN_CONST | 720 | 5.5% |
| ENTER_EXECUTOR | 620 | 4.8% |
| BUILD_STRING | 420 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 7,280 | 56.1% |
| INTERPRETER_EXIT | 5,700 | 43.9% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 4,240 | 41.0% |
| CACHE | 2,380 | 23.0% |
| POP_TOP | 1,520 | 14.7% |
| SEND_GEN | 920 | 8.9% |
| COPY_FREE_VARS | 680 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,680 | 45.3% |
| LOAD_GLOBAL | 2,320 | 22.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 1,200 | 11.6% |
| NOP | 560 | 5.4% |
| LOAD_CONST | 520 | 5.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,720 | 99.5% |
| BINARY_OP | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,740 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,320 | 85.3% |
| LOAD_FAST_LOAD_FAST | 2,760 | 12.8% |
| BINARY_OP | 280 | 1.3% |
| LOAD_FAST | 120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 16,120 | 75.0% |
| BINARY_SLICE | 1,640 | 7.6% |
| BUILD_SLICE | 1,340 | 6.2% |
| SWAP | 1,340 | 6.2% |
| CALL_PY_EXACT_ARGS | 320 | 1.5% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,920 | 71.6% |
| LOAD_FAST | 240 | 9.0% |
| BINARY_SUBSCR_LIST_INT | 160 | 6.0% |
| LOAD_CONST | 120 | 4.5% |
| LOAD_GLOBAL_MODULE | 120 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,100 | 41.0% |
| CALL | 960 | 35.8% |
| RETURN_VALUE | 300 | 11.2% |
| STORE_FAST | 160 | 6.0% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 4.5% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 199 | 90.9% |
| BINARY_OP | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 199 | 90.9% |
| CALL | 20 | 9.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 360 | 85.7% |
| LOAD_ATTR | 40 | 9.5% |
| BINARY_OP | 20 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 360 | 85.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 9.5% |
| COMPARE_OP | 20 | 4.8% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 199 | 49.8% |
| BINARY_OP | 80 | 20.0% |
| LOAD_FAST | 80 | 20.0% |
| CALL | 41 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 340 | 85.0% |
| RETURN_VALUE | 60 | 15.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,480 | 45.1% |
| LOAD_CONST | 1,360 | 41.5% |
| BINARY_OP | 200 | 6.1% |
| LOAD_FAST | 200 | 6.1% |
| CALL_LEN | 40 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,560 | 47.6% |
| SWAP | 859 | 26.2% |
| STORE_DEREF | 460 | 14.0% |
| STORE_FAST | 221 | 6.7% |
| RETURN_VALUE | 40 | 1.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,700 | 89.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 520 | 4.0% |
| LOAD_DEREF | 420 | 3.2% |
| LOAD_CONST | 160 | 1.2% |
| CALL | 81 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 10,501 | 80.5% |
| PUSH_EXC_INFO | 980 | 7.5% |
| STORE_FAST | 900 | 6.9% |
| PUSH_NULL | 420 | 3.2% |
| LOAD_FAST | 160 | 1.2% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 360 | 35.3% |
| LOAD_FAST | 300 | 29.4% |
| BINARY_SUBSCR | 120 | 11.8% |
| BUILD_TUPLE | 120 | 11.8% |
| LOAD_CONST | 120 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,000 | 98.0% |
| PUSH_EXC_INFO | 20 | 2.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,959 | 93.0% |
| BINARY_SUBSCR | 240 | 5.6% |
| BINARY_OP_SUBTRACT_INT | 40 | 0.9% |
| LOAD_FAST | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,540 | 59.6% |
| LOAD_ATTR_SLOT | 919 | 21.6% |
| RETURN_VALUE | 260 | 6.1% |
| BINARY_OP_ADD_UNICODE | 160 | 3.8% |
| LOAD_FAST | 120 | 2.8% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,000 | 71.4% |
| LOAD_CONST | 200 | 14.3% |
| ENTER_EXECUTOR | 80 | 5.7% |
| LOAD_FAST | 60 | 4.3% |
| BINARY_SUBSCR | 40 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,020 | 72.9% |
| LOAD_CONST | 240 | 17.1% |
| STORE_FAST | 100 | 7.1% |
| PUSH_EXC_INFO | 20 | 1.4% |
| BINARY_SUBSCR_STR_INT | 20 | 1.4% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 920 | 90.2% |
| BINARY_SUBSCR | 100 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 58.8% |
| RETURN_VALUE | 260 | 25.5% |
| LOAD_GLOBAL_MODULE | 80 | 7.8% |
| LOAD_GLOBAL_BUILTIN | 60 | 5.9% |
| LOAD_GLOBAL | 20 | 2.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,920 | 46.7% |
| LOAD_ATTR | 8,120 | 42.6% |
| BINARY_OP | 760 | 4.0% |
| CALL | 501 | 2.6% |
| LOAD_FAST | 380 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,842 | 98.7% |
| COPY_FREE_VARS | 200 | 1.0% |
| STORE_FAST | 40 | 0.2% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 33,520 | 64.5% |
| LOAD_FAST | 9,160 | 17.6% |
| RETURN_VALUE | 8,120 | 15.6% |
| LOAD_ATTR_INSTANCE_VALUE | 520 | 1.0% |
| CALL | 300 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 32,320 | 62.2% |
| RESUME_CHECK | 10,020 | 19.3% |
| GET_AWAITABLE | 8,960 | 17.3% |
| POP_TOP | 480 | 0.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 140 | 0.3% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,960 | 82.9% |
| LOAD_GLOBAL_BUILTIN | 1,020 | 6.5% |
| CALL | 580 | 3.7% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 1.8% |
| LOAD_CONST | 160 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 12,540 | 80.2% |
| STORE_FAST | 1,140 | 7.3% |
| LOAD_GLOBAL_BUILTIN | 480 | 3.1% |
| STORE_FAST_STORE_FAST | 380 | 2.4% |
| LOAD_FAST | 360 | 2.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 160,080 | 60.1% |
| LOAD_GLOBAL_MODULE | 63,920 | 24.0% |
| LOAD_FAST | 25,660 | 9.6% |
| LOAD_CONST | 13,563 | 5.1% |
| LOAD_FAST_LOAD_FAST | 1,880 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 159,980 | 60.1% |
| RETURN_VALUE | 33,800 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 31,960 | 12.0% |
| COPY | 10,440 | 3.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 8,120 | 3.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 32,240 | 90.8% |
| LOAD_FAST | 840 | 2.4% |
| PUSH_NULL | 760 | 2.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 600 | 1.7% |
| BUILD_LIST | 240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 33,840 | 95.3% |
| RETURN_VALUE | 840 | 2.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 600 | 1.7% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.3% |
| BEFORE_WITH | 80 | 0.2% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,340 | 79.2% |
| LOAD_ATTR_INSTANCE_VALUE | 660 | 5.6% |
| RETURN_GENERATOR | 600 | 5.1% |
| CALL | 460 | 3.9% |
| LOAD_CONST | 240 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,300 | 70.3% |
| TO_BOOL_BOOL | 1,000 | 8.5% |
| STORE_FAST | 760 | 6.4% |
| POP_TOP | 500 | 4.2% |
| LOAD_CONST | 359 | 3.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 16,440 | 36.9% |
| LOAD_GLOBAL_BUILTIN | 13,880 | 31.1% |
| LOAD_GLOBAL_MODULE | 12,480 | 28.0% |
| LOAD_ATTR | 880 | 2.0% |
| CALL | 700 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 43,480 | 97.5% |
| TO_BOOL | 660 | 1.5% |
| RETURN_VALUE | 340 | 0.8% |
| STORE_FAST | 80 | 0.2% |
| LOAD_FAST | 20 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 102,414 | 53.2% |
| LOAD_FAST | 72,720 | 37.8% |
| LOAD_ATTR_WITH_HINT | 16,400 | 8.5% |
| CALL | 740 | 0.4% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,152 | 47.9% |
| LOAD_CONST | 59,240 | 30.8% |
| LOAD_GLOBAL_MODULE | 17,480 | 9.1% |
| STORE_FAST | 16,501 | 8.6% |
| COPY | 3,740 | 1.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,218 | 81.9% |
| BUILD_TUPLE | 3,400 | 14.5% |
| CALL | 360 | 1.5% |
| LOAD_CONST | 160 | 0.7% |
| CALL_KW | 120 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 16,280 | 69.3% |
| LOAD_FAST | 2,600 | 11.1% |
| RETURN_CONST | 2,200 | 9.4% |
| JUMP_BACKWARD | 1,120 | 4.8% |
| LOAD_GLOBAL_MODULE | 640 | 2.7% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,880 | 22.1% |
| BUILD_LIST | 2,640 | 20.2% |
| LOAD_ATTR_METHOD_NO_DICT | 2,360 | 18.1% |
| LOAD_CONST | 1,540 | 11.8% |
| LOAD_FAST_LOAD_FAST | 1,240 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,620 | 27.8% |
| RETURN_VALUE | 3,300 | 25.3% |
| LIST_APPEND | 2,400 | 18.4% |
| LOAD_ATTR_METHOD_NO_DICT | 2,040 | 15.6% |
| BUILD_TUPLE | 840 | 6.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 16,120 | 61.9% |
| LOAD_CONST | 3,822 | 14.7% |
| LOAD_FAST_LOAD_FAST | 3,720 | 14.3% |
| LOAD_ATTR | 640 | 2.5% |
| LOAD_FAST | 640 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 16,420 | 63.1% |
| STORE_FAST | 6,440 | 24.7% |
| POP_TOP | 1,582 | 6.1% |
| UNPACK_SEQUENCE_LIST | 1,080 | 4.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 120 | 0.5% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 50,066 | 43.3% |
| LOAD_ATTR | 47,240 | 40.9% |
| LOAD_ATTR_METHOD_LAZY_DICT | 8,120 | 7.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,040 | 7.0% |
| CALL | 1,480 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 46,183 | 40.0% |
| GET_ITER | 32,600 | 28.2% |
| STORE_FAST | 20,140 | 17.4% |
| RETURN_VALUE | 8,520 | 7.4% |
| BUILD_LIST | 2,680 | 2.3% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,346 | 72.5% |
| CALL | 9,781 | 12.4% |
| CALL_BUILTIN_FAST | 8,080 | 10.2% |
| LOAD_CONST | 1,980 | 2.5% |
| STORE_FAST | 1,120 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 75,388 | 95.4% |
| RETURN_VALUE | 1,420 | 1.8% |
| UNPACK_SEQUENCE_TUPLE | 1,080 | 1.4% |
| LOAD_CONST | 840 | 1.1% |
| STORE_FAST | 160 | 0.2% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 166,429 | 40.0% |
| LOAD_FAST | 139,003 | 33.4% |
| LOAD_ATTR | 35,025 | 8.4% |
| LOAD_FAST_LOAD_FAST | 22,760 | 5.5% |
| LOAD_FAST_CHECK | 16,080 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 353,362 | 85.0% |
| RETURN_GENERATOR | 56,540 | 13.6% |
| COPY_FREE_VARS | 3,698 | 0.9% |
| MAKE_CELL | 2,101 | 0.5% |
| TO_BOOL_BOOL | 160 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,420 | 39.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 561 | 15.4% |
| CALL | 480 | 13.2% |
| LOAD_ATTR_METHOD_NO_DICT | 440 | 12.1% |
| RETURN_VALUE | 200 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,181 | 87.4% |
| RETURN_GENERATOR | 460 | 12.6% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 621 | 86.1% |
| CALL | 100 | 13.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 401 | 55.6% |
| BUILD_TUPLE | 120 | 16.6% |
| BINARY_OP_INPLACE_ADD_UNICODE | 80 | 11.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 80 | 11.1% |
| BINARY_OP | 40 | 5.5% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 440 | 48.9% |
| LOAD_FAST | 240 | 26.7% |
| LOAD_GLOBAL_MODULE | 160 | 17.8% |
| CALL | 40 | 4.4% |
| RETURN_VALUE | 20 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 360 | 40.0% |
| LOAD_FAST | 220 | 24.4% |
| CALL | 160 | 17.8% |
| RETURN_VALUE | 140 | 15.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20 | 2.2% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,300 | 99.7% |
| LOAD_GLOBAL_MODULE | 80 | 0.1% |
| CALL | 60 | 0.1% |
| LOAD_CONST | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,200 | 69.3% |
| LOAD_FAST | 17,960 | 30.2% |
| PUSH_NULL | 80 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.1% |
| LOAD_FAST_LOAD_FAST | 40 | 0.1% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,520 | 44.2% |
| LOAD_ATTR_SLOT | 2,120 | 37.2% |
| RETURN_VALUE | 760 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 4.2% |
| COMPARE_OP | 60 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,560 | 62.5% |
| RETURN_VALUE | 2,140 | 37.5% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 127,864 | 51.7% |
| LOAD_FAST | 67,880 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 20,233 | 8.2% |
| LOAD_ATTR_WITH_HINT | 8,160 | 3.3% |
| LOAD_FAST_LOAD_FAST | 8,140 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 244,657 | 98.9% |
| POP_JUMP_IF_TRUE | 2,420 | 1.0% |
| RETURN_VALUE | 120 | 0.0% |
| STORE_FAST | 80 | 0.0% |
| COPY | 60 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,300 | 62.0% |
| LOAD_GLOBAL_MODULE | 760 | 14.3% |
| COMPARE_OP | 620 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 440 | 8.3% |
| LOAD_FAST | 160 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,580 | 86.1% |
| POP_JUMP_IF_TRUE | 420 | 7.9% |
| STORE_FAST | 120 | 2.3% |
| YIELD_VALUE | 120 | 2.3% |
| COPY | 60 | 1.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 17,459 | 69.6% |
| JUMP_BACKWARD | 5,039 | 20.1% |
| FOR_ITER | 840 | 3.3% |
| LOAD_FAST | 720 | 2.9% |
| SWAP | 620 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,099 | 44.2% |
| RETURN_CONST | 4,399 | 17.5% |
| LOAD_FAST | 3,900 | 15.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,820 | 15.2% |
| SWAP | 720 | 2.9% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,100 | 71.4% |
| JUMP_BACKWARD | 1,420 | 24.7% |
| FOR_ITER | 120 | 2.1% |
| SWAP | 100 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,060 | 88.2% |
| STORE_FAST_LOAD_FAST | 360 | 6.3% |
| LOAD_CONST | 280 | 4.9% |
| LOAD_GLOBAL_MODULE | 40 | 0.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,280 | 53.4% |
| GET_ITER | 1,200 | 19.5% |
| SWAP | 1,120 | 18.2% |
| LOAD_FAST | 400 | 6.5% |
| FOR_ITER | 140 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 2,400 | 39.1% |
| STORE_FAST | 1,360 | 22.1% |
| SWAP | 1,120 | 18.2% |
| LOAD_FAST | 620 | 10.1% |
| RETURN_CONST | 360 | 5.9% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560 | 77.8% |
| LOAD_ATTR | 80 | 11.1% |
| LOAD_ATTR_MODULE | 80 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460 | 63.9% |
| STORE_FAST | 140 | 19.4% |
| CALL | 60 | 8.3% |
| COMPARE_OP | 60 | 8.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 752,107 | 96.8% |
| LOAD_FAST_LOAD_FAST | 12,424 | 1.6% |
| LOAD_ATTR | 7,780 | 1.0% |
| COPY | 2,019 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,340 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 159,118 | 20.5% |
| CALL_LEN | 102,414 | 13.2% |
| LOAD_ATTR_METHOD_NO_DICT | 81,394 | 10.5% |
| RETURN_VALUE | 58,123 | 7.5% |
| LOAD_GLOBAL_MODULE | 54,082 | 7.0% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,360 | 99.7% |
| LOAD_ATTR | 100 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,200 | 49.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 8,120 | 25.0% |
| LOAD_GLOBAL_MODULE | 8,080 | 24.9% |
| LOAD_GLOBAL | 40 | 0.1% |
| CALL | 20 | 0.1% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 81,394 | 34.3% |
| LOAD_FAST | 55,569 | 23.4% |
| CALL_BUILTIN_FAST | 31,960 | 13.5% |
| BINARY_OP | 16,120 | 6.8% |
| LOAD_ATTR_WITH_HINT | 16,040 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,026 | 40.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 50,066 | 21.1% |
| LOAD_GLOBAL_MODULE | 28,301 | 11.9% |
| LOAD_FAST_LOAD_FAST | 19,820 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 16,280 | 6.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 179,267 | 67.3% |
| LOAD_ATTR_SLOT | 27,240 | 10.2% |
| LOAD_ATTR_WITH_HINT | 18,440 | 6.9% |
| RETURN_VALUE | 9,520 | 3.6% |
| LOAD_DEREF | 8,640 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 166,429 | 62.5% |
| LOAD_FAST | 53,483 | 20.1% |
| LOAD_FAST_LOAD_FAST | 32,700 | 12.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 8,040 | 3.0% |
| CALL | 2,660 | 1.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 275,323 | 98.4% |
| LOAD_ATTR | 4,220 | 1.5% |
| LOAD_FAST | 280 | 0.1% |
| LOAD_ATTR_MODULE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 174,060 | 62.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 32,240 | 11.5% |
| CONTAINS_OP | 16,600 | 5.9% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 16,120 | 5.8% |
| IS_OP | 15,960 | 5.7% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,180 | 88.1% |
| LOAD_ATTR | 140 | 10.4% |
| LOAD_FAST_LOAD_FAST | 20 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 47.8% |
| CALL | 560 | 41.8% |
| BINARY_OP | 60 | 4.5% |
| CALL_BUILTIN_CLASS | 40 | 3.0% |
| CALL_ISINSTANCE | 20 | 1.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,341 | 90.2% |
| LOAD_ATTR | 680 | 5.9% |
| LOAD_ATTR_SLOT | 200 | 1.7% |
| STORE_FAST_LOAD_FAST | 120 | 1.0% |
| RETURN_VALUE | 41 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,662 | 93.0% |
| COPY_FREE_VARS | 800 | 7.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 887,200 | 72.8% |
| LOAD_FAST_LOAD_FAST | 320,060 | 26.2% |
| LOAD_ATTR_INSTANCE_VALUE | 7,960 | 0.7% |
| LOAD_ATTR_MODULE | 1,560 | 0.1% |
| LOAD_ATTR | 1,300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 351,920 | 28.9% |
| TO_BOOL_BOOL | 201,620 | 16.5% |
| LOAD_FAST | 198,819 | 16.3% |
| CALL_BUILTIN_FAST | 160,080 | 13.1% |
| STORE_SUBSCR_DICT | 159,960 | 13.1% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 226,920 | 98.8% |
| LOAD_ATTR | 2,340 | 1.0% |
| LOAD_FAST_LOAD_FAST | 320 | 0.1% |
| LOAD_ATTR_WITH_HINT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 57,120 | 24.9% |
| LOAD_ATTR | 34,180 | 14.9% |
| TO_BOOL_BOOL | 24,920 | 10.9% |
| LOAD_CONST | 24,540 | 10.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 18,440 | 8.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 306,855 | 41.3% |
| RESUME_CHECK | 146,940 | 19.8% |
| LOAD_GLOBAL_BUILTIN | 105,120 | 14.1% |
| LOAD_FAST | 48,560 | 6.5% |
| STORE_FAST | 43,640 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 401,258 | 53.9% |
| LOAD_FAST_LOAD_FAST | 160,300 | 21.6% |
| LOAD_GLOBAL_BUILTIN | 105,120 | 14.1% |
| LOAD_ATTR | 32,880 | 4.4% |
| BUILD_TUPLE | 16,500 | 2.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 351,920 | 33.9% |
| RESUME_CHECK | 139,106 | 13.4% |
| LOAD_FAST | 106,423 | 10.2% |
| POP_JUMP_IF_FALSE | 75,362 | 7.3% |
| LOAD_ATTR_INSTANCE_VALUE | 54,082 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 353,600 | 34.0% |
| LOAD_ATTR_MODULE | 275,323 | 26.5% |
| LOAD_FAST | 137,745 | 13.3% |
| CALL_BUILTIN_FAST | 63,920 | 6.2% |
| COMPARE_OP | 40,679 | 3.9% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,240 | 92.5% |
| LOAD_SUPER_ATTR | 100 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 880 | 65.7% |
| PUSH_NULL | 420 | 31.3% |
| LOAD_GLOBAL | 40 | 3.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,900 | 92.5% |
| LOAD_SUPER_ATTR | 400 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,560 | 48.3% |
| LOAD_FAST | 1,360 | 25.7% |
| CALL_PY_EXACT_ARGS | 1,240 | 23.4% |
| CALL | 140 | 2.6% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 353,362 | 40.8% |
| CACHE | 164,630 | 19.0% |
| POP_TOP | 158,280 | 18.3% |
| CALL_KW | 67,260 | 7.8% |
| CALL_FUNCTION_EX | 32,481 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 469,108 | 54.2% |
| LOAD_GLOBAL_BUILTIN | 146,940 | 17.0% |
| LOAD_GLOBAL_MODULE | 139,106 | 16.1% |
| LOAD_FAST_LOAD_FAST | 51,001 | 5.9% |
| NOP | 28,624 | 3.3% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 146,220 | 94.8% |
| JUMP_BACKWARD_NO_INTERRUPT | 6,420 | 4.2% |
| SEND | 1,560 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 147,080 | 95.4% |
| RESUME_CHECK | 6,200 | 4.0% |
| RESUME | 920 | 0.6% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 106,065 | 71.0% |
| LOAD_FAST | 35,901 | 24.0% |
| STORE_ATTR | 5,360 | 3.6% |
| SWAP | 2,019 | 1.4% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 103,143 | 69.1% |
| LOAD_FAST | 17,346 | 11.6% |
| RETURN_CONST | 16,084 | 10.8% |
| LOAD_CONST | 6,786 | 4.5% |
| LOAD_GLOBAL_MODULE | 2,365 | 1.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 98,480 | 54.7% |
| LOAD_FAST | 80,940 | 44.9% |
| STORE_ATTR | 700 | 0.4% |
| STORE_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 72,420 | 40.2% |
| LOAD_CONST | 50,840 | 28.2% |
| LOAD_FAST | 28,680 | 15.9% |
| RETURN_CONST | 27,960 | 15.5% |
| BUILD_LIST | 300 | 0.2% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,800 | 68.7% |
| LOAD_FAST_LOAD_FAST | 400 | 15.3% |
| STORE_ATTR | 340 | 13.0% |
| STORE_FAST_LOAD_FAST | 80 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,460 | 55.7% |
| NOP | 580 | 22.1% |
| EXTENDED_ARG | 300 | 11.5% |
| LOAD_GLOBAL_BUILTIN | 200 | 7.6% |
| LOAD_GLOBAL | 40 | 1.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 159,960 | 94.0% |
| LOAD_FAST | 8,721 | 5.1% |
| LOAD_ATTR | 520 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 281 | 0.2% |
| STORE_SUBSCR | 280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 160,120 | 94.1% |
| LOAD_FAST | 8,940 | 5.3% |
| LOAD_GLOBAL_MODULE | 281 | 0.2% |
| NOP | 280 | 0.2% |
| LOAD_CONST | 261 | 0.2% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 20 | 50.0% |
| RETURN_CONST | 20 | 50.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,040 | 82.9% |
| LOAD_FAST | 320 | 13.0% |
| TO_BOOL | 100 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,100 | 85.4% |
| POP_JUMP_IF_FALSE | 360 | 14.6% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 201,620 | 25.2% |
| LOAD_ATTR_INSTANCE_VALUE | 159,118 | 19.9% |
| LOAD_ATTR | 145,743 | 18.2% |
| RETURN_VALUE | 79,682 | 10.0% |
| LOAD_FAST | 51,965 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 462,110 | 57.7% |
| POP_JUMP_IF_TRUE | 329,813 | 41.2% |
| UNARY_NOT | 8,800 | 1.1% |
| EXTENDED_ARG | 100 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 43,420 | 70.4% |
| LOAD_ATTR_INSTANCE_VALUE | 8,920 | 14.5% |
| COPY | 6,800 | 11.0% |
| LOAD_FAST | 1,580 | 2.6% |
| TO_BOOL | 660 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 55,540 | 90.1% |
| POP_JUMP_IF_TRUE | 6,040 | 9.8% |
| UNARY_NOT | 80 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 14,639 | 91.3% |
| LOAD_FAST | 1,060 | 6.6% |
| TO_BOOL | 340 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,359 | 95.8% |
| POP_JUMP_IF_TRUE | 660 | 4.1% |
| UNARY_NOT | 20 | 0.1% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 46,640 | 55.9% |
| LOAD_FAST | 19,040 | 22.8% |
| LOAD_ATTR | 8,920 | 10.7% |
| LOAD_ATTR_INSTANCE_VALUE | 8,240 | 9.9% |
| TO_BOOL | 440 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 75,102 | 90.0% |
| POP_JUMP_IF_TRUE | 8,340 | 10.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 2,400 | 49.6% |
| LOAD_FAST | 1,761 | 36.4% |
| COPY | 361 | 7.5% |
| TO_BOOL | 240 | 5.0% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,701 | 76.4% |
| POP_JUMP_IF_TRUE | 1,141 | 23.6% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,080 | 94.7% |
| UNPACK_SEQUENCE | 60 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,140 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 8,080 | 80.5% |
| CALL_METHOD_DESCRIPTOR_O | 1,080 | 10.8% |
| LOAD_FAST | 360 | 3.6% |
| UNPACK_SEQUENCE | 300 | 3.0% |
| RETURN_VALUE | 140 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,380 | 83.5% |
| STORE_FAST_STORE_FAST | 1,380 | 13.7% |
| POP_TOP | 280 | 2.8% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,640 | 39.7% |
| CALL_BUILTIN_FAST | 8,120 | 33.5% |
| FOR_ITER_LIST | 3,820 | 15.7% |
| STORE_FAST | 1,360 | 5.6% |
| UNPACK_SEQUENCE | 620 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 23,960 | 98.8% |
| STORE_FAST_LOAD_FAST | 140 | 0.6% |
| STORE_FAST | 100 | 0.4% |
| LOAD_FAST | 60 | 0.2% |


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
|     deferred | 210,241 | 84.8% |
|          hit | 32,339 | 13.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 760 | 14.0% |
| Failure | 4,681 | 86.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,860 | 39.7% |
| or | 1,060 | 22.6% |
| add other | 580 | 12.4% |
| remainder | 281 | 6.0% |
| floor divide | 280 | 6.0% |
| multiply different types | 219 | 4.7% |
| add different types | 161 | 3.4% |
| xor | 160 | 3.4% |
| lshift | 80 | 1.7% |


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
|     deferred | 1,681 | 7.2% |
|          hit | 20,580 | 88.5% |
|         miss | 180 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 560 | 69.9% |
| Failure | 241 | 30.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 161 | 66.8% |
| code complex parameters | 60 | 24.9% |
| out of range | 20 | 8.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 330,579 | 18.6% |
|          hit | 1,362,576 | 76.7% |
|         miss | 54,800 | 3.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 17,780 | 61.0% |
| Failure | 11,370 | 39.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 2,340 | 20.6% |
| code complex parameters | 1,881 | 16.5% |
| class no vectorcall | 1,382 | 12.2% |
| cfunc noargs | 1,263 | 11.1% |
| meth descr varargs | 1,020 | 9.0% |
| class mutable | 1,020 | 9.0% |
| no dict | 580 | 5.1% |
| cfunc varargs keywords | 400 | 3.5% |
| cfunc varargs | 362 | 3.2% |
| meth descr varargs keywords | 322 | 2.8% |
| other | 320 | 2.8% |
| operator wrapper | 220 | 1.9% |
| wrong number arguments | 120 | 1.1% |
| cmethod | 80 | 0.7% |
| init not simple | 60 | 0.5% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 55,499 | 17.5% |
|          hit | 257,898 | 81.1% |
|         miss | 459 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,260 | 57.1% |
| Failure | 1,699 | 42.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 1,000 | 58.9% |
| bool | 180 | 10.6% |
| bytes | 160 | 9.4% |
| different types | 140 | 8.2% |
| float long | 139 | 8.2% |
| big int | 80 | 4.7% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 248,504 | 86.3% |
|          hit | 36,978 | 12.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,100 | 46.6% |
| Failure | 1,260 | 53.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 480 | 38.1% |
| dict values | 280 | 22.2% |
| reversed list | 160 | 12.7% |
| dict items | 140 | 11.1% |
| bytes | 60 | 4.8% |
| itertools | 40 | 3.2% |
| enumerate | 40 | 3.2% |
| ascii string | 40 | 3.2% |
| other | 20 | 1.6% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 620,215 | 16.7% |
|        deopt | 80 | 0.0% |
|          hit | 3,041,095 | 81.8% |
|         miss | 14,281 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 25,880 | 60.1% |
| Failure | 17,202 | 39.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 5,760 | 33.5% |
| not managed dict | 3,120 | 18.1% |
| shadowed | 3,081 | 17.9% |
| metaclass attribute | 1,740 | 10.1% |
| method | 1,721 | 10.0% |
| module attr not found | 400 | 2.3% |
| builtin class method | 400 | 2.3% |
| class attr descriptor | 320 | 1.9% |
| non object slot | 280 | 1.6% |
| class method obj | 220 | 1.3% |
| mutable class | 80 | 0.5% |
| class attr simple | 80 | 0.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 15,920 | 0.9% |
|        deopt | 160 | 0.0% |
|          hit | 1,779,563 | 98.1% |
|         miss | 3,220 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 16,100 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 520 | 6.8% |
|          hit | 6,640 | 86.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 500 | 100.0% |
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
|     deferred | 6,920 | 4.2% |
|          hit | 154,200 | 94.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,560 | 62.9% |
| Failure | 920 | 37.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 920 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 216,101 | 38.7% |
|          hit | 322,305 | 57.8% |
|         miss | 9,880 | 1.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,400 | 66.9% |
| Failure | 3,160 | 33.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 960 | 30.4% |
| not in keys | 880 | 27.8% |
| not in dict | 740 | 23.4% |
| overriding descriptor | 200 | 6.3% |
| method | 120 | 3.8% |
| not managed dict | 120 | 3.8% |
| overridden | 80 | 2.5% |
| no dict | 60 | 1.9% |


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
|     deferred | 3,021 | 1.7% |
|          hit | 170,243 | 97.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 39.9% |
| Failure | 421 | 60.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 401 | 95.2% |
| bytearray int | 20 | 4.8% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 72,284 | 6.9% |
|          hit | 968,986 | 92.3% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,280 | 82.5% |
| Failure | 1,541 | 17.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 460 | 29.9% |
| sequence | 381 | 24.7% |
| set | 240 | 15.6% |
| dict | 160 | 10.4% |
| memory view | 140 | 9.1% |
| mapping | 80 | 5.2% |
| tuple | 60 | 3.9% |
| float | 20 | 1.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,100 | 2.9% |
|          hit | 35,440 | 94.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 980 | 98.0% |
| Failure | 20 | 2.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 20 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 12,442,850 | 48.2% |
| Not specialized | 4,279,445 | 16.6% |
| Specialized hits | 9,012,182 | 34.9% |
| Specialized misses | 83,180 | 0.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 620,215 | 34.8% |
| CALL | 330,579 | 18.5% |
| FOR_ITER | 248,504 | 13.9% |
| STORE_ATTR | 216,101 | 12.1% |
| BINARY_OP | 210,241 | 11.8% |
| TO_BOOL | 72,284 | 4.1% |
| COMPARE_OP | 55,499 | 3.1% |
| LOAD_GLOBAL | 15,920 | 0.9% |
| SEND | 6,920 | 0.4% |
| STORE_SUBSCR | 3,021 | 0.2% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 33,260 | 39.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,940 | 11.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 9,920 | 11.9% |
| STORE_ATTR_SLOT | 8,420 | 10.1% |
| LOAD_ATTR_WITH_HINT | 7,280 | 8.7% |
| LOAD_ATTR_SLOT | 4,940 | 5.9% |
| LOAD_GLOBAL_BUILTIN | 2,620 | 3.1% |
| STORE_ATTR_INSTANCE_VALUE | 1,160 | 1.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,060 | 1.3% |
| CALL_METHOD_DESCRIPTOR_O | 820 | 1.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 210,250 | 20.8% |
| Calls to Python functions inlined | 800,469 | 79.2% |
| Calls via PyEval_EvalFrame (total) | 210,250 | 20.8% |
| Calls via PyEval_EvalFrame (vector) | 193,390 | 19.1% |
| Calls via PyEval_EvalFrame (generator) | 16,860 | 1.7% |
| Calls via PyEval_EvalFrame (legacy) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 193,050 | 19.1% |
| Calls via PyEval_EvalFrame (build class) | 260 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 5,601 | 0.6% |
| Calls via PyEval_EvalFrame (function ex) | 33,441 | 3.3% |
| Calls via PyEval_EvalFrame (api) | 10,003 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 42,400 | 4.2% |
| Frame objects created | 4,221 | 0.4% |
| Frames pushed | 560,128 | 55.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 776,445 | 32.7% |
| Frees to freelist | 780,606 |  |
| Allocations | 1,598,227 | 67.3% |
| Allocations to 512 bytes | 1,408,095 | 59.3% |
| Allocations to 4 kbytes | 132,331 | 5.6% |
| Allocations over 4 kbytes | 57,801 | 2.4% |
| Frees | 1,537,569 |  |
| New values | 34,781 |  |
| Interpreter increfs | 12,298,493 | 76.8% |
| Interpreter decrefs | 14,092,410 | 78.2% |
| Increfs | 3,710,229 | 23.2% |
| Decrefs | 3,920,208 | 21.8% |
| Materialize dict (on request) | 20 | 0.1% |
| Materialize dict (new key) | 160 | 0.5% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 20 | 0.1% |
| Method cache hits | 1,224,325 |  |
| Method cache misses | 36,138 |  |
| Method cache collisions | 40,637 |  |
| Method cache dunder hits | 356,809 |  |
| Method cache dunder misses | 7,109 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 100 | 540 | 744,534 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 400 |  |
| Traces created | 260 | 65.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 20 | 5.0% |
| Trace too short | 140 | 35.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 76,660 |  |
| Uops executed | 2,812,820 | 36.69 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 140 | 53.8% |
| <= 64 | 0 | 0.0% |
| <= 128 | 120 | 46.2% |


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
| <= 16 | 0 | 0.0% |
| <= 32 | 140 | 53.8% |
| <= 64 | 20 | 7.7% |
| <= 128 | 100 | 38.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 13,440 | 17.5% |
| <= 16 | 260 | 0.3% |
| <= 32 | 39,780 | 51.9% |
| <= 64 | 1,440 | 1.9% |
| <= 128 | 21,580 | 28.2% |
| <= 256 | 0 | 0.0% |
| <= 512 | 40 | 0.1% |
| <= 1,024 | 40 | 0.1% |
| <= 2,048 | 40 | 0.1% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 40 | 0.1% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 745,880 | 26.5% | 26.5% |  |
| LOAD_FAST | 328,100 | 11.7% | 38.2% |  |
| _GUARD_TYPE_VERSION | 179,040 | 6.4% | 44.5% |  |
| _POP_JUMP_IF_TRUE | 129,260 | 4.6% | 49.1% |  |
| STORE_FAST | 101,740 | 3.6% | 52.8% |  |
| _LOAD_ATTR_SLOT | 80,480 | 2.9% | 55.6% |  |
| _EXIT_TRACE | 76,260 | 2.7% | 58.3% |  |
| _LOAD_ATTR | 57,720 | 2.1% | 60.4% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 53,540 | 1.9% | 62.3% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 53,540 | 1.9% | 64.2% |  |
| _ITER_CHECK_RANGE | 50,500 | 1.8% | 66.0% |  |
| _IS_ITER_EXHAUSTED_RANGE | 50,500 | 1.8% | 67.8% |  |
| TO_BOOL_BOOL | 49,280 | 1.8% | 69.5% |  |
| _CHECK_PEP_523 | 48,600 | 1.7% | 71.3% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 48,600 | 1.7% | 73.0% |  |
| _CHECK_STACK_SPACE | 48,600 | 1.7% | 74.7% |  |
| _INIT_CALL_PY_EXACT_ARGS | 48,600 | 1.7% | 76.4% |  |
| _PUSH_FRAME | 48,600 | 1.7% | 78.2% |  |
| _SAVE_RETURN_OFFSET | 48,600 | 1.7% | 79.9% |  |
| _ITER_NEXT_RANGE | 46,800 | 1.7% | 81.6% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 39,040 | 1.4% | 83.0% |  |
| LOAD_CONST | 37,720 | 1.3% | 84.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 27,140 | 1.0% | 85.3% |  |
| _POP_JUMP_IF_FALSE | 23,760 | 0.8% | 86.1% |  |
| _GUARD_GLOBALS_VERSION | 23,540 | 0.8% | 86.9% | 0.5% |
| MAKE_CELL | 23,100 | 0.8% | 87.8% |  |
| RESUME_CHECK | 22,960 | 0.8% | 88.6% |  |
| PUSH_NULL | 21,000 | 0.7% | 89.3% |  |
| _LOAD_GLOBAL_MODULE | 19,840 | 0.7% | 90.0% |  |
| BUILD_LIST | 19,420 | 0.7% | 90.7% |  |
| CALL_INTRINSIC_1 | 19,420 | 0.7% | 91.4% |  |
| LIST_EXTEND | 19,420 | 0.7% | 92.1% |  |
| _ITER_CHECK_LIST | 17,920 | 0.6% | 92.7% |  |
| _IS_ITER_EXHAUSTED_LIST | 17,920 | 0.6% | 93.4% |  |
| CONTAINS_OP | 17,720 | 0.6% | 94.0% |  |
| POP_TOP | 13,340 | 0.5% | 94.5% |  |
| _GUARD_BOTH_INT | 11,600 | 0.4% | 94.9% |  |
| _JUMP_TO_TOP | 11,400 | 0.4% | 95.3% |  |
| BINARY_SLICE | 11,320 | 0.4% | 95.7% |  |
| _BINARY_OP_ADD_INT | 10,100 | 0.4% | 96.1% |  |
| _BINARY_OP | 10,080 | 0.4% | 96.4% |  |
| BINARY_SUBSCR_DICT | 10,000 | 0.4% | 96.8% |  |
| _STORE_SUBSCR | 10,000 | 0.4% | 97.1% |  |
| _ITER_NEXT_LIST | 8,660 | 0.3% | 97.4% |  |
| _ITER_CHECK_TUPLE | 8,120 | 0.3% | 97.7% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 8,120 | 0.3% | 98.0% |  |
| _ITER_NEXT_TUPLE | 7,760 | 0.3% | 98.3% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 5,420 | 0.2% | 98.5% |  |
| _GUARD_KEYS_VERSION | 5,420 | 0.2% | 98.7% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 5,420 | 0.2% | 98.9% |  |
| TO_BOOL_LIST | 3,640 | 0.1% | 99.0% |  |
| _GUARD_BUILTINS_VERSION | 3,580 | 0.1% | 99.1% | 5.6% |
| CALL_LEN | 3,380 | 0.1% | 99.2% |  |
| COMPARE_OP_INT | 3,380 | 0.1% | 99.4% |  |
| _LOAD_GLOBAL_BUILTINS | 3,380 | 0.1% | 99.5% |  |
| BINARY_SUBSCR_LIST_INT | 2,720 | 0.1% | 99.6% |  |
| _TO_BOOL | 2,180 | 0.1% | 99.7% |  |
| _BINARY_OP_SUBTRACT_INT | 1,500 | 0.1% | 99.7% |  |
| FORMAT_SIMPLE | 1,240 | 0.0% | 99.8% |  |
| LIST_APPEND | 1,240 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 1,240 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 860 | 0.0% | 99.9% |  |
| BUILD_STRING | 620 | 0.0% | 99.9% |  |
| COPY | 300 | 0.0% | 99.9% |  |
| SWAP | 300 | 0.0% | 99.9% |  |
| _CHECK_ATTR_MODULE | 300 | 0.0% | 99.9% |  |
| _LOAD_ATTR_MODULE | 300 | 0.0% | 99.9% |  |
| _GUARD_DORV_VALUES | 300 | 0.0% | 99.9% |  |
| _STORE_ATTR_INSTANCE_VALUE | 300 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 260 | 0.0% | 100.0% |  |
| _STORE_ATTR_SLOT | 260 | 0.0% | 100.0% |  |
| IS_OP | 120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 100 | 0.0% | 100.0% | 80.0% |
| TO_BOOL_INT | 80 | 0.0% | 100.0% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 80 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 80 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 40 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 40 | 0.0% | 100.0% |  |
| _POP_FRAME | 40 | 0.0% | 100.0% |  |
| _IS_NONE | 40 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 140 |
| RETURN_GENERATOR | 80 |
| CALL_KW | 40 |
| CALL | 20 |
| CALL_FUNCTION_EX | 20 |
| YIELD_VALUE | 20 |
| CALL_LIST_APPEND | 20 |


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
Stats gathered on: 2023-11-08
