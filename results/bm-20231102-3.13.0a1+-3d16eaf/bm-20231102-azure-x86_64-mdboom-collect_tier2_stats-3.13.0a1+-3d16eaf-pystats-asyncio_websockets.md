
# Pystats results

- benchmark: asyncio_websockets
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 4,819,150 | 18.4% | 18.4% |  |
| POP_JUMP_IF_FALSE | 1,433,382 | 5.5% | 23.9% |  |
| LOAD_ATTR_SLOT | 1,248,099 | 4.8% | 28.7% | 0.4% |
| LOAD_CONST | 1,139,340 | 4.4% | 33.0% |  |
| LOAD_FAST_LOAD_FAST | 1,071,530 | 4.1% | 37.1% |  |
| LOAD_GLOBAL_MODULE | 1,044,719 | 4.0% | 41.1% | 0.1% |
| STORE_FAST | 897,782 | 3.4% | 44.6% |  |
| RESUME_CHECK | 865,936 | 3.3% | 47.9% | 0.0% |
| TO_BOOL_BOOL | 808,442 | 3.1% | 51.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 778,013 | 3.0% | 53.9% | 0.1% |
| LOAD_GLOBAL_BUILTIN | 743,531 | 2.8% | 56.8% | 0.4% |
| LOAD_ATTR | 731,617 | 2.8% | 59.6% |  |
| POP_JUMP_IF_TRUE | 580,893 | 2.2% | 61.8% |  |
| POP_TOP | 565,822 | 2.2% | 64.0% |  |
| RETURN_VALUE | 519,733 | 2.0% | 66.0% |  |
| CALL_PY_EXACT_ARGS | 440,881 | 1.7% | 67.6% | 0.1% |
| IS_OP | 418,440 | 1.6% | 69.2% |  |
| RETURN_CONST | 384,181 | 1.5% | 70.7% |  |
| CALL | 359,683 | 1.4% | 72.1% |  |
| PUSH_NULL | 309,523 | 1.2% | 73.3% |  |
| LOAD_ATTR_MODULE | 279,923 | 1.1% | 74.3% | 0.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 268,313 | 1.0% | 75.4% | 0.0% |
| CALL_BUILTIN_FAST | 266,263 | 1.0% | 76.4% | 0.0% |
| FOR_ITER | 250,843 | 1.0% | 77.3% |  |
| COMPARE_OP_INT | 247,288 | 0.9% | 78.3% | 0.1% |
| CONTAINS_OP | 242,860 | 0.9% | 79.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 236,086 | 0.9% | 80.1% | 0.4% |
| LOAD_ATTR_WITH_HINT | 229,640 | 0.9% | 81.0% | 3.2% |
| BINARY_OP | 225,762 | 0.9% | 81.9% |  |
| STORE_ATTR | 225,381 | 0.9% | 82.7% |  |
| JUMP_BACKWARD | 221,621 | 0.8% | 83.6% |  |
| INTERPRETER_EXIT | 209,667 | 0.8% | 84.4% |  |
| CALL_LEN | 192,386 | 0.7% | 85.1% |  |
| STORE_ATTR_SLOT | 180,220 | 0.7% | 85.8% | 4.7% |
| STORE_SUBSCR_DICT | 170,203 | 0.7% | 86.4% |  |
| POP_JUMP_IF_NONE | 165,766 | 0.6% | 87.1% |  |
| RETURN_GENERATOR | 159,800 | 0.6% | 87.7% |  |
| SEND_GEN | 154,200 | 0.6% | 88.3% |  |
| GET_AWAITABLE | 151,360 | 0.6% | 88.9% |  |
| END_SEND | 151,040 | 0.6% | 89.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 149,221 | 0.6% | 90.0% | 0.8% |
| POP_JUMP_IF_NOT_NONE | 130,968 | 0.5% | 90.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 123,185 | 0.5% | 91.0% | 8.1% |
| JUMP_FORWARD | 108,506 | 0.4% | 91.4% |  |
| NOP | 99,854 | 0.4% | 91.8% |  |
| CALL_KW | 99,321 | 0.4% | 92.2% |  |
| CALL_FUNCTION_EX | 93,763 | 0.4% | 92.5% |  |
| BUILD_TUPLE | 90,584 | 0.3% | 92.9% |  |
| LOAD_DEREF | 88,322 | 0.3% | 93.2% |  |
| TO_BOOL_NONE | 83,442 | 0.3% | 93.5% | 0.1% |
| TO_BOOL | 83,303 | 0.3% | 93.8% |  |
| ENTER_EXECUTOR | 81,360 | 0.3% | 94.1% |  |
| CALL_METHOD_DESCRIPTOR_O | 79,047 | 0.3% | 94.5% | 1.0% |
| BUILD_MAP | 71,402 | 0.3% | 94.7% |  |
| GET_ITER | 70,861 | 0.3% | 95.0% |  |
| BINARY_SLICE | 70,220 | 0.3% | 95.3% |  |
| DICT_MERGE | 67,601 | 0.3% | 95.5% |  |
| TO_BOOL_INT | 61,740 | 0.2% | 95.8% | 0.1% |
| CALL_TYPE_1 | 59,480 | 0.2% | 96.0% |  |
| COMPARE_OP | 59,458 | 0.2% | 96.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 51,940 | 0.2% | 96.4% | 19.1% |
| CALL_ISINSTANCE | 44,480 | 0.2% | 96.6% |  |
| BUILD_LIST | 40,001 | 0.2% | 96.7% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 35,500 | 0.1% | 96.9% | 93.7% |
| DELETE_SUBSCR | 33,921 | 0.1% | 97.0% |  |
| BUILD_SLICE | 33,660 | 0.1% | 97.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 32,460 | 0.1% | 97.3% |  |
| LOAD_GLOBAL | 31,820 | 0.1% | 97.4% |  |
| MAKE_CELL | 31,325 | 0.1% | 97.5% |  |
| STORE_FAST_STORE_FAST | 28,140 | 0.1% | 97.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 26,021 | 0.1% | 97.7% |  |
| EXTENDED_ARG | 26,000 | 0.1% | 97.8% |  |
| CALL_INTRINSIC_1 | 24,820 | 0.1% | 97.9% |  |
| LIST_EXTEND | 24,740 | 0.1% | 98.0% |  |
| COPY | 24,080 | 0.1% | 98.1% |  |
| FOR_ITER_LIST | 23,999 | 0.1% | 98.2% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 23,600 | 0.1% | 98.3% |  |
| CALL_LIST_APPEND | 23,479 | 0.1% | 98.4% |  |
| STORE_DEREF | 21,725 | 0.1% | 98.4% |  |
| BINARY_OP_ADD_INT | 21,480 | 0.1% | 98.5% |  |
| CALL_ALLOC_AND_ENTER_INIT | 19,082 | 0.1% | 98.6% | 0.2% |
| EXIT_INIT_CHECK | 19,042 | 0.1% | 98.7% |  |
| COPY_FREE_VARS | 18,780 | 0.1% | 98.7% |  |
| LOAD_FAST_CHECK | 16,820 | 0.1% | 98.8% |  |
| MAP_ADD | 16,040 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 15,960 | 0.1% | 98.9% |  |
| CALL_BUILTIN_CLASS | 15,640 | 0.1% | 99.0% |  |
| STORE_SUBSCR | 13,722 | 0.1% | 99.0% |  |
| SWAP | 13,702 | 0.1% | 99.1% |  |
| BINARY_SUBSCR_DICT | 13,061 | 0.0% | 99.1% |  |
| YIELD_VALUE | 12,980 | 0.0% | 99.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 11,760 | 0.0% | 99.2% |  |
| CALL_BUILTIN_O | 11,759 | 0.0% | 99.3% | 1.7% |
| LOAD_ATTR_PROPERTY | 11,462 | 0.0% | 99.3% |  |
| RESUME | 10,340 | 0.0% | 99.4% | 1.0% |
| LIST_APPEND | 10,180 | 0.0% | 99.4% |  |
| UNPACK_SEQUENCE_TUPLE | 10,040 | 0.0% | 99.4% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 9,760 | 0.0% | 99.5% |  |
| SEND | 9,400 | 0.0% | 99.5% |  |
| BEFORE_ASYNC_WITH | 9,120 | 0.0% | 99.5% |  |
| UNARY_NOT | 9,000 | 0.0% | 99.6% |  |
| MAKE_FUNCTION | 6,862 | 0.0% | 99.6% |  |
| FOR_ITER_RANGE | 5,820 | 0.0% | 99.6% |  |
| COMPARE_OP_FLOAT | 5,700 | 0.0% | 99.7% |  |
| COMPARE_OP_STR | 5,320 | 0.0% | 99.7% | 4.1% |
| LOAD_SUPER_ATTR_METHOD | 5,300 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_LIST_INT | 4,299 | 0.0% | 99.7% |  |
| BEFORE_WITH | 3,765 | 0.0% | 99.7% |  |
| BINARY_OP_ADD_FLOAT | 3,740 | 0.0% | 99.7% |  |
| FOR_ITER_TUPLE | 3,660 | 0.0% | 99.8% |  |
| CALL_PY_WITH_DEFAULTS | 3,641 | 0.0% | 99.8% |  |
| TO_BOOL_STR | 3,562 | 0.0% | 99.8% |  |
| SET_FUNCTION_ATTRIBUTE | 3,422 | 0.0% | 99.8% |  |
| BINARY_OP_SUBTRACT_INT | 3,300 | 0.0% | 99.8% |  |
| CHECK_EXC_MATCH | 3,060 | 0.0% | 99.8% |  |
| PUSH_EXC_INFO | 3,060 | 0.0% | 99.8% |  |
| POP_EXCEPT | 3,039 | 0.0% | 99.8% |  |
| STORE_NAME | 3,020 | 0.0% | 99.9% |  |
| STORE_ATTR_WITH_HINT | 2,620 | 0.0% | 99.9% | 11.5% |
| BINARY_SUBSCR | 2,482 | 0.0% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 2,460 | 0.0% | 99.9% | 6.5% |
| LOAD_FAST_AND_CLEAR | 2,361 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 2,342 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE | 2,100 | 0.0% | 99.9% |  |
| BINARY_OP_ADD_UNICODE | 1,960 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 1,700 | 0.0% | 99.9% |  |
| LOAD_NAME | 1,460 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_STR_INT | 1,400 | 0.0% | 99.9% | 11.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,340 | 0.0% | 99.9% |  |
| LOAD_SUPER_ATTR_ATTR | 1,340 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_LIST | 1,140 | 0.0% | 99.9% |  |
| UNARY_INVERT | 1,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 1,020 | 0.0% | 100.0% | 2.0% |
| LOAD_SUPER_ATTR | 1,020 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,020 | 0.0% | 100.0% |  |
| BUILD_STRING | 940 | 0.0% | 100.0% |  |
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
| DELETE_ATTR | 180 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_SLOT | 925,800 | 3.5% | 3.5% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 753,150 | 2.9% | 6.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 729,861 | 2.8% | 9.2% |
| STORE_FAST LOAD_FAST | 657,470 | 2.5% | 11.7% |
| LOAD_FAST LOAD_ATTR | 532,973 | 2.0% | 13.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 469,810 | 1.8% | 15.6% |
| RESUME_CHECK LOAD_FAST | 469,106 | 1.8% | 17.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 451,447 | 1.7% | 19.1% |
| IS_OP POP_JUMP_IF_FALSE | 416,180 | 1.6% | 20.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 401,110 | 1.5% | 22.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 355,361 | 1.4% | 23.6% |
| LOAD_GLOBAL_MODULE IS_OP | 353,600 | 1.4% | 24.9% |
| LOAD_ATTR_SLOT LOAD_GLOBAL_MODULE | 351,920 | 1.3% | 26.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 329,732 | 1.3% | 27.5% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_SLOT | 320,060 | 1.2% | 28.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 306,787 | 1.2% | 29.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 275,383 | 1.1% | 31.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 244,608 | 0.9% | 31.9% |
| LOAD_FAST LOAD_CONST | 240,926 | 0.9% | 32.8% |
| LOAD_FAST LOAD_ATTR_WITH_HINT | 226,920 | 0.9% | 33.7% |
| LOAD_CONST LOAD_FAST | 213,148 | 0.8% | 34.5% |
| JUMP_BACKWARD FOR_ITER | 204,582 | 0.8% | 35.3% |
| FOR_ITER STORE_FAST | 204,541 | 0.8% | 36.1% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 201,680 | 0.8% | 36.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR | 201,460 | 0.8% | 37.6% |
| LOAD_ATTR_SLOT LOAD_FAST | 197,419 | 0.8% | 38.4% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 194,960 | 0.7% | 39.1% |
| LOAD_FAST CONTAINS_OP | 194,080 | 0.7% | 39.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 179,286 | 0.7% | 40.5% |
| RETURN_CONST POP_TOP | 179,211 | 0.7% | 41.2% |
| POP_TOP LOAD_FAST | 177,618 | 0.7% | 41.9% |
| LOAD_ATTR LOAD_FAST | 175,424 | 0.7% | 42.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 174,080 | 0.7% | 43.2% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 166,448 | 0.6% | 43.9% |
| CACHE RESUME_CHECK | 164,628 | 0.6% | 44.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 160,300 | 0.6% | 45.1% |
| STORE_SUBSCR_DICT JUMP_BACKWARD | 160,120 | 0.6% | 45.7% |
| LOAD_ATTR_SLOT CALL_BUILTIN_FAST | 160,080 | 0.6% | 46.4% |
| CALL_BUILTIN_FAST LOAD_FAST_LOAD_FAST | 159,980 | 0.6% | 47.0% |
| LOAD_ATTR_SLOT STORE_SUBSCR_DICT | 159,960 | 0.6% | 47.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 159,139 | 0.6% | 48.2% |
| POP_TOP RESUME_CHECK | 158,280 | 0.6% | 48.8% |
| GET_AWAITABLE LOAD_CONST | 151,360 | 0.6% | 49.4% |
| STORE_ATTR LOAD_FAST_LOAD_FAST | 148,860 | 0.6% | 49.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 148,503 | 0.6% | 50.5% |
| SEND_GEN POP_TOP | 147,080 | 0.6% | 51.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 146,960 | 0.6% | 51.6% |
| LOAD_CONST SEND_GEN | 146,220 | 0.6% | 52.2% |
| LOAD_ATTR TO_BOOL_BOOL | 145,743 | 0.6% | 52.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 140,984 | 0.5% | 53.3% |
| LOAD_FAST RETURN_VALUE | 139,881 | 0.5% | 53.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 139,105 | 0.5% | 54.4% |
| CALL STORE_FAST | 137,744 | 0.5% | 54.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 137,045 | 0.5% | 55.4% |
| RETURN_GENERATOR GET_AWAITABLE | 130,160 | 0.5% | 55.9% |
| LOAD_CONST COMPARE_OP_INT | 127,863 | 0.5% | 56.4% |
| PUSH_NULL LOAD_FAST | 123,443 | 0.5% | 56.9% |
| RETURN_VALUE STORE_FAST | 122,981 | 0.5% | 57.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 117,866 | 0.5% | 57.8% |
| LOAD_CONST BINARY_OP | 116,959 | 0.4% | 58.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 113,583 | 0.4% | 58.7% |
| POP_TOP RETURN_CONST | 109,572 | 0.4% | 59.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 106,523 | 0.4% | 59.5% |
| RETURN_CONST INTERPRETER_EXIT | 106,283 | 0.4% | 59.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 106,065 | 0.4% | 60.3% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 105,120 | 0.4% | 60.7% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 103,143 | 0.4% | 61.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 102,366 | 0.4% | 61.5% |
| RETURN_VALUE RETURN_VALUE | 98,960 | 0.4% | 61.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 98,480 | 0.4% | 62.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 96,026 | 0.4% | 62.6% |
| POP_JUMP_IF_NONE LOAD_FAST | 93,244 | 0.4% | 63.0% |
| CALL_LEN LOAD_FAST | 92,084 | 0.4% | 63.3% |
| LOAD_CONST CALL_KW | 91,701 | 0.4% | 63.7% |
| PUSH_NULL LOAD_CONST | 90,960 | 0.3% | 64.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 87,320 | 0.3% | 64.4% |
| LOAD_CONST STORE_FAST | 81,484 | 0.3% | 64.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 81,414 | 0.3% | 65.0% |
| LOAD_FAST STORE_ATTR_SLOT | 80,960 | 0.3% | 65.3% |
| RETURN_VALUE END_SEND | 80,400 | 0.3% | 65.6% |
| RETURN_VALUE TO_BOOL_BOOL | 79,682 | 0.3% | 65.9% |
| END_SEND POP_TOP | 79,440 | 0.3% | 66.2% |
| RETURN_VALUE INTERPRETER_EXIT | 79,284 | 0.3% | 66.5% |
| NOP LOAD_FAST | 76,750 | 0.3% | 66.8% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 75,387 | 0.3% | 67.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 75,382 | 0.3% | 67.4% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 75,102 | 0.3% | 67.7% |
| LOAD_FAST CALL_LEN | 72,720 | 0.3% | 67.9% |
| LOAD_FAST CALL | 72,502 | 0.3% | 68.2% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 72,420 | 0.3% | 68.5% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 71,800 | 0.3% | 68.8% |
| END_SEND STORE_FAST | 69,920 | 0.3% | 69.0% |
| LOAD_CONST LOAD_CONST | 69,530 | 0.3% | 69.3% |
| RETURN_CONST END_SEND | 68,080 | 0.3% | 69.6% |
| LOAD_FAST COMPARE_OP_INT | 67,880 | 0.3% | 69.8% |
| DICT_MERGE CALL_FUNCTION_EX | 67,601 | 0.3% | 70.1% |
| BUILD_MAP LOAD_FAST | 67,561 | 0.3% | 70.3% |
| CALL_KW RESUME_CHECK | 67,260 | 0.3% | 70.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 67,200 | 0.3% | 70.9% |
| LOAD_FAST DICT_MERGE | 66,320 | 0.3% | 71.1% |


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
| RESUME_CHECK | 164,628 | 78.3% |
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
| LOAD_GLOBAL_MODULE | 763 | 20.3% |
| CALL | 480 | 12.7% |
| RETURN_VALUE | 240 | 6.4% |
| LOAD_ATTR | 240 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,685 | 97.9% |
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
| BUILD_SLICE | 33,600 | 99.1% |
| LOAD_FAST | 261 | 0.8% |
| CALL | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,600 | 99.1% |
| LOAD_CONST | 141 | 0.4% |
| LOAD_GLOBAL_MODULE | 120 | 0.4% |
| RETURN_CONST | 60 | 0.2% |


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
| LOAD_FAST | 1,440 | 84.7% |
| LOAD_ATTR | 100 | 5.9% |
| CONVERT_VALUE | 80 | 4.7% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 3.5% |
| LOAD_FAST_LOAD_FAST | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,460 | 85.9% |
| BUILD_STRING | 240 | 14.1% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 32,600 | 46.0% |
| LOAD_FAST | 22,800 | 32.2% |
| CALL_BUILTIN_CLASS | 12,540 | 17.7% |
| LOAD_ATTR_INSTANCE_VALUE | 820 | 1.2% |
| CALL | 560 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 43,660 | 61.6% |
| FOR_ITER_LIST | 17,460 | 24.6% |
| FOR_ITER_RANGE | 4,100 | 5.8% |
| LOAD_FAST_AND_CLEAR | 2,201 | 3.1% |
| CALL_PY_EXACT_ARGS | 1,560 | 2.2% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 106,283 | 50.7% |
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
| STORE_FAST | 28,843 | 28.9% |
| RESUME_CHECK | 28,644 | 28.7% |
| POP_JUMP_IF_FALSE | 14,362 | 14.4% |
| POP_JUMP_IF_TRUE | 9,681 | 9.7% |
| POP_JUMP_IF_NOT_NONE | 8,760 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,750 | 76.9% |
| LOAD_GLOBAL_MODULE | 15,282 | 15.3% |
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
| STORE_FAST | 419 | 13.8% |
| COPY | 400 | 13.2% |
| STORE_SUBSCR | 240 | 7.9% |
| SWAP | 240 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 520 | 17.1% |
| RETURN_CONST | 500 | 16.5% |
| RERAISE | 400 | 13.2% |
| JUMP_BACKWARD | 379 | 12.5% |
| LOAD_FAST | 260 | 8.6% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 179,211 | 31.7% |
| SEND_GEN | 147,080 | 26.0% |
| END_SEND | 79,440 | 14.0% |
| CALL_METHOD_DESCRIPTOR_O | 75,387 | 13.3% |
| CALL_FUNCTION_EX | 24,800 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 177,618 | 31.4% |
| RESUME_CHECK | 158,280 | 28.0% |
| RETURN_CONST | 109,572 | 19.4% |
| LOAD_CONST | 42,724 | 7.6% |
| ENTER_EXECUTOR | 31,480 | 5.6% |


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
| LOAD_ATTR_MODULE | 174,080 | 56.2% |
| LOAD_FAST | 63,260 | 20.4% |
| LOAD_ATTR | 37,822 | 12.2% |
| LOAD_ATTR_SLOT | 31,980 | 10.3% |
| LOAD_NAME | 560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 123,443 | 39.9% |
| LOAD_CONST | 90,960 | 29.4% |
| LOAD_FAST_LOAD_FAST | 60,221 | 19.5% |
| CALL | 31,359 | 10.1% |
| LOAD_DEREF | 800 | 0.3% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 71,800 | 44.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 32,320 | 20.2% |
| CACHE | 18,320 | 11.5% |
| CALL_KW | 17,200 | 10.8% |
| CALL | 9,260 | 5.8% |

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
| BINARY_OP | 10,240 | 74.6% |
| LOAD_FAST | 1,581 | 11.5% |
| LOAD_CONST | 920 | 6.7% |
| STORE_SUBSCR | 421 | 3.1% |
| LOAD_FAST_LOAD_FAST | 200 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 10,780 | 78.6% |
| LOAD_FAST | 520 | 3.8% |
| STORE_SUBSCR | 421 | 3.1% |
| RETURN_CONST | 381 | 2.8% |
| JUMP_BACKWARD | 380 | 2.8% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 28,760 | 34.5% |
| LOAD_FAST | 22,942 | 27.5% |
| LOAD_ATTR_INSTANCE_VALUE | 19,940 | 23.9% |
| ENTER_EXECUTOR | 2,160 | 2.6% |
| CALL | 1,960 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 40,562 | 48.7% |
| POP_JUMP_IF_TRUE | 33,800 | 40.6% |
| TO_BOOL_BOOL | 5,500 | 6.6% |
| TO_BOOL | 1,561 | 1.9% |
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

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 7,280 | 56.1% |
| SEND | 2,800 | 21.6% |
| RETURN_CONST | 720 | 5.5% |
| ENTER_EXECUTOR | 600 | 4.6% |
| BUILD_STRING | 440 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 7,280 | 56.1% |
| INTERPRETER_EXIT | 5,700 | 43.9% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 116,959 | 51.8% |
| BINARY_OP | 21,041 | 9.3% |
| LOAD_FAST_LOAD_FAST | 16,380 | 7.3% |
| BINARY_SLICE | 16,240 | 7.2% |
| LOAD_GLOBAL_MODULE | 12,820 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,021 | 23.5% |
| LOAD_FAST | 49,180 | 21.8% |
| TO_BOOL_INT | 43,460 | 19.3% |
| BINARY_OP | 21,041 | 9.3% |
| BINARY_SLICE | 16,200 | 7.2% |


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
| LOAD_ATTR_SLOT | 23,260 | 58.1% |
| STORE_FAST | 5,060 | 12.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,680 | 6.7% |
| SWAP | 2,201 | 5.5% |
| LOAD_FAST | 1,280 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,280 | 65.7% |
| STORE_FAST | 6,500 | 16.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,640 | 6.6% |
| SWAP | 2,201 | 5.5% |
| BUILD_TUPLE | 320 | 0.8% |


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
| LOAD_CONST | 700 | 74.5% |
| FORMAT_SIMPLE | 240 | 25.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 440 | 46.8% |
| STORE_FAST | 240 | 25.5% |
| LIST_APPEND | 160 | 17.0% |
| CALL | 100 | 10.6% |


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
| LOAD_FAST | 72,502 | 20.2% |
| LOAD_ATTR_INSTANCE_VALUE | 50,562 | 14.1% |
| LOAD_FAST_LOAD_FAST | 46,421 | 12.9% |
| LOAD_ATTR | 35,200 | 9.8% |
| BINARY_SLICE | 32,320 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 137,744 | 38.3% |
| RETURN_VALUE | 37,741 | 10.5% |
| LOAD_CONST | 32,880 | 9.1% |
| LOAD_FAST | 29,066 | 8.1% |
| POP_TOP | 22,933 | 6.4% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 67,601 | 72.1% |
| CALL_INTRINSIC_1 | 23,920 | 25.5% |
| LOAD_FAST | 1,762 | 1.9% |
| BUILD_MAP | 160 | 0.2% |
| MAP_ADD | 160 | 0.2% |

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
| LIST_EXTEND | 24,500 | 98.7% |
| RERAISE | 320 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 23,920 | 96.4% |
| BUILD_MAP | 420 | 1.7% |
| RERAISE | 320 | 1.3% |
| LOAD_CONST | 160 | 0.6% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 91,701 | 92.3% |
| ENTER_EXECUTOR | 7,620 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 67,260 | 67.7% |
| RETURN_GENERATOR | 17,200 | 17.3% |
| STORE_FAST | 10,040 | 10.1% |
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
| POP_JUMP_IF_FALSE | 47,440 | 19.5% |
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
| CALL_BUILTIN_FAST | 10,440 | 43.4% |
| CALL_LEN | 3,740 | 15.5% |
| BINARY_OP | 3,040 | 12.6% |
| LOAD_FAST | 2,959 | 12.3% |
| SWAP | 1,280 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 11,320 | 47.0% |
| TO_BOOL_INT | 6,840 | 28.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,039 | 8.5% |
| TO_BOOL | 820 | 3.4% |
| COMPARE_OP_INT | 800 | 3.3% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 13,340 | 71.0% |
| CALL_PY_EXACT_ARGS | 3,699 | 19.7% |
| LOAD_ATTR_PROPERTY | 800 | 4.3% |
| CALL | 661 | 3.5% |
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
| LOAD_FAST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 66.7% |
| RETURN_CONST | 60 | 33.3% |


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
| POP_TOP | 31,480 | 38.7% |
| CALL_LIST_APPEND | 16,220 | 19.9% |
| STORE_SUBSCR | 10,780 | 13.2% |
| LIST_APPEND | 8,820 | 10.8% |
| STORE_FAST | 7,820 | 9.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 42,380 | 52.1% |
| BINARY_OP | 10,000 | 12.3% |
| LOAD_GLOBAL_MODULE | 8,540 | 10.5% |
| CALL_KW | 7,620 | 9.4% |
| LOAD_CONST | 4,420 | 5.4% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 9,480 | 36.5% |
| POP_JUMP_IF_NONE | 7,680 | 29.5% |
| LOAD_CONST | 5,420 | 20.8% |
| BUILD_MAP | 580 | 2.2% |
| POP_EXCEPT | 520 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 16,080 | 61.8% |
| JUMP_BACKWARD | 8,600 | 33.1% |
| FOR_ITER_LIST | 420 | 1.6% |
| ENTER_EXECUTOR | 300 | 1.2% |
| POP_JUMP_IF_FALSE | 280 | 1.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 204,582 | 81.6% |
| GET_ITER | 43,660 | 17.4% |
| FOR_ITER | 1,260 | 0.5% |
| LOAD_FAST | 920 | 0.4% |
| SWAP | 361 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 204,541 | 81.5% |
| LOAD_FAST | 40,680 | 16.2% |
| RETURN_CONST | 1,520 | 0.6% |
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
| STORE_SUBSCR_DICT | 160,120 | 72.2% |
| POP_JUMP_IF_TRUE | 33,000 | 14.9% |
| STORE_FAST | 8,960 | 4.0% |
| EXTENDED_ARG | 8,600 | 3.9% |
| POP_TOP | 6,399 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 204,582 | 92.3% |
| LOAD_FAST | 8,940 | 4.0% |
| FOR_ITER_LIST | 3,939 | 1.8% |
| FOR_ITER_RANGE | 1,500 | 0.7% |
| FOR_ITER_TUPLE | 840 | 0.4% |


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
| LOAD_CONST | 48,640 | 44.8% |
| STORE_FAST | 36,685 | 33.8% |
| POP_TOP | 17,380 | 16.0% |
| POP_JUMP_IF_FALSE | 4,661 | 4.3% |
| LOAD_FAST | 240 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,163 | 53.6% |
| STORE_FAST | 24,400 | 22.5% |
| LOAD_DEREF | 8,240 | 7.6% |
| BINARY_OP | 8,000 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 6,361 | 5.9% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 8,080 | 79.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,120 | 11.0% |
| RETURN_VALUE | 560 | 5.5% |
| BUILD_STRING | 160 | 1.6% |
| BUILD_TUPLE | 80 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 8,820 | 86.6% |
| JUMP_BACKWARD | 1,360 | 13.4% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 23,260 | 94.0% |
| LOAD_FAST | 980 | 4.0% |
| BINARY_SLICE | 240 | 1.0% |
| LOAD_CONST | 240 | 1.0% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 24,500 | 99.0% |
| LOAD_FAST | 160 | 0.6% |
| LOAD_NAME | 60 | 0.2% |
| STORE_NAME | 20 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 532,973 | 72.8% |
| ENTER_EXECUTOR | 42,380 | 5.8% |
| LOAD_ATTR_WITH_HINT | 34,180 | 4.7% |
| LOAD_GLOBAL_BUILTIN | 32,880 | 4.5% |
| LOAD_GLOBAL_MODULE | 30,920 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 175,424 | 24.0% |
| TO_BOOL_BOOL | 145,743 | 19.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 54,880 | 7.5% |
| CALL_PY_EXACT_ARGS | 50,345 | 6.9% |
| LOAD_GLOBAL_MODULE | 49,480 | 6.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,926 | 21.1% |
| GET_AWAITABLE | 151,360 | 13.3% |
| POP_JUMP_IF_FALSE | 148,503 | 13.0% |
| PUSH_NULL | 90,960 | 8.0% |
| LOAD_CONST | 69,530 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 213,148 | 18.7% |
| SEND_GEN | 146,220 | 12.8% |
| COMPARE_OP_INT | 127,863 | 11.2% |
| BINARY_OP | 116,959 | 10.3% |
| CALL_KW | 91,701 | 8.0% |


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
| POP_JUMP_IF_FALSE | 729,861 | 15.1% |
| STORE_FAST | 657,470 | 13.6% |
| RESUME_CHECK | 469,106 | 9.7% |
| POP_JUMP_IF_TRUE | 451,447 | 9.4% |
| LOAD_GLOBAL_BUILTIN | 401,110 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 925,800 | 19.2% |
| LOAD_ATTR_INSTANCE_VALUE | 753,150 | 15.6% |
| LOAD_ATTR | 532,973 | 11.1% |
| LOAD_CONST | 240,926 | 5.0% |
| LOAD_ATTR_WITH_HINT | 226,920 | 4.7% |


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
| LOAD_GLOBAL_BUILTIN | 160,300 | 15.0% |
| CALL_BUILTIN_FAST | 159,980 | 14.9% |
| STORE_ATTR | 148,860 | 13.9% |
| STORE_ATTR_INSTANCE_VALUE | 103,143 | 9.6% |
| LOAD_FAST_LOAD_FAST | 87,320 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 320,060 | 29.9% |
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
| LOAD_GLOBAL_MODULE | 11,400 | 35.8% |
| LOAD_ATTR | 4,880 | 15.3% |
| LOAD_GLOBAL_BUILTIN | 4,640 | 14.6% |
| LOAD_FAST | 4,480 | 14.1% |
| CALL | 1,300 | 4.1% |


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
| MAKE_CELL | 20,804 | 66.4% |
| CALL_PY_EXACT_ARGS | 9,801 | 31.3% |
| CALL | 220 | 0.7% |
| CALL_FUNCTION_EX | 160 | 0.5% |
| CALL_KW | 160 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 20,804 | 66.4% |
| RETURN_GENERATOR | 8,640 | 27.6% |
| RESUME_CHECK | 1,721 | 5.5% |
| RESUME | 160 | 0.5% |


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
| TO_BOOL_BOOL | 469,810 | 32.8% |
| IS_OP | 416,180 | 29.0% |
| COMPARE_OP_INT | 244,608 | 17.1% |
| TO_BOOL_NONE | 75,102 | 5.2% |
| TO_BOOL_INT | 55,620 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 729,861 | 50.9% |
| LOAD_GLOBAL_BUILTIN | 306,787 | 21.4% |
| LOAD_CONST | 148,503 | 10.4% |
| RETURN_CONST | 113,583 | 7.9% |
| LOAD_GLOBAL_MODULE | 75,382 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 57,120 | 34.5% |
| LOAD_ATTR_INSTANCE_VALUE | 53,801 | 32.5% |
| LOAD_FAST | 44,165 | 26.6% |
| LOAD_DEREF | 9,120 | 5.5% |
| LOAD_ATTR | 800 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,244 | 56.3% |
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
| LOAD_FAST | 117,866 | 90.0% |
| LOAD_ATTR_INSTANCE_VALUE | 10,080 | 7.7% |
| CALL_BUILTIN_FAST | 720 | 0.5% |
| LOAD_GLOBAL_MODULE | 620 | 0.5% |
| LOAD_FAST_CHECK | 480 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 55,143 | 42.1% |
| LOAD_FAST_LOAD_FAST | 30,161 | 23.0% |
| LOAD_GLOBAL_MODULE | 23,582 | 18.0% |
| LOAD_GLOBAL_BUILTIN | 8,780 | 6.7% |
| NOP | 8,760 | 6.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 329,732 | 56.8% |
| CONTAINS_OP | 194,960 | 33.6% |
| TO_BOOL | 33,800 | 5.8% |
| TO_BOOL_NONE | 8,340 | 1.4% |
| TO_BOOL_INT | 6,040 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 451,447 | 77.7% |
| LOAD_GLOBAL_MODULE | 42,103 | 7.2% |
| JUMP_BACKWARD | 33,000 | 5.7% |
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
| POP_TOP | 109,572 | 28.5% |
| STORE_ATTR | 50,240 | 13.1% |
| STORE_ATTR_SLOT | 27,960 | 7.3% |
| STORE_FAST | 27,200 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 179,211 | 46.6% |
| INTERPRETER_EXIT | 106,283 | 27.7% |
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
| LOAD_FAST_LOAD_FAST | 201,460 | 89.4% |
| LOAD_FAST | 20,001 | 8.9% |
| STORE_ATTR | 3,120 | 1.4% |
| SWAP | 360 | 0.2% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 148,860 | 66.0% |
| RETURN_CONST | 50,240 | 22.3% |
| LOAD_DEREF | 8,080 | 3.6% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 2.3% |
| LOAD_FAST | 3,560 | 1.6% |


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
| FOR_ITER | 204,541 | 22.8% |
| CALL | 137,744 | 15.3% |
| RETURN_VALUE | 122,981 | 13.7% |
| LOAD_CONST | 81,484 | 9.1% |
| END_SEND | 69,920 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 657,470 | 73.2% |
| LOAD_GLOBAL_BUILTIN | 43,640 | 4.9% |
| LOAD_GLOBAL_MODULE | 40,622 | 4.5% |
| JUMP_FORWARD | 36,685 | 4.1% |
| NOP | 28,843 | 3.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 1,120 | 47.8% |
| FOR_ITER_RANGE | 380 | 16.2% |
| FOR_ITER_LIST | 260 | 11.1% |
| FOR_ITER | 222 | 9.5% |
| COPY | 160 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 1,120 | 47.8% |
| LOAD_ATTR | 600 | 25.6% |
| LOAD_ATTR_METHOD_NO_DICT | 182 | 7.8% |
| LOAD_ATTR_PROPERTY | 120 | 5.1% |
| STORE_ATTR | 80 | 3.4% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 23,300 | 82.8% |
| UNPACK_SEQUENCE_TUPLE | 1,380 | 4.9% |
| UNPACK_SEQUENCE_LIST | 1,140 | 4.1% |
| UNPACK_SEQUENCE | 900 | 3.2% |
| STORE_FAST_STORE_FAST | 400 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,800 | 81.0% |
| LOAD_GLOBAL_MODULE | 2,000 | 7.1% |
| STORE_FAST | 1,800 | 6.4% |
| LOAD_GLOBAL | 400 | 1.4% |
| STORE_FAST_STORE_FAST | 400 | 1.4% |


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
| LOAD_ATTR | 1,540 | 11.2% |
| BINARY_OP_ADD_INT | 1,340 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,480 | 25.4% |
| BUILD_LIST | 2,201 | 16.1% |
| STORE_ATTR_INSTANCE_VALUE | 2,039 | 14.9% |
| LOAD_CONST | 1,321 | 9.6% |
| COPY | 1,280 | 9.3% |


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
| LOAD_FAST_LOAD_FAST | 1,200 | 61.2% |
| LOAD_FAST | 240 | 12.2% |
| BINARY_SUBSCR_LIST_INT | 160 | 8.2% |
| LOAD_CONST | 120 | 6.1% |
| LOAD_GLOBAL_MODULE | 120 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,100 | 56.1% |
| RETURN_VALUE | 300 | 15.3% |
| CALL | 240 | 12.2% |
| STORE_FAST | 160 | 8.2% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 6.1% |


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
| LOAD_FAST_LOAD_FAST | 1,480 | 44.8% |
| LOAD_CONST | 1,380 | 41.8% |
| BINARY_OP | 200 | 6.1% |
| LOAD_FAST | 200 | 6.1% |
| CALL_LEN | 40 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,560 | 47.3% |
| SWAP | 879 | 26.6% |
| STORE_DEREF | 460 | 13.9% |
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
| LOAD_CONST | 3,999 | 93.0% |
| BINARY_SUBSCR | 240 | 5.6% |
| BINARY_OP_SUBTRACT_INT | 40 | 0.9% |
| LOAD_FAST | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,540 | 59.1% |
| LOAD_ATTR_SLOT | 959 | 22.3% |
| RETURN_VALUE | 260 | 6.0% |
| BINARY_OP_ADD_UNICODE | 160 | 3.7% |
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
| LOAD_FAST | 9,340 | 79.4% |
| LOAD_ATTR_INSTANCE_VALUE | 680 | 5.8% |
| RETURN_GENERATOR | 600 | 5.1% |
| CALL | 440 | 3.7% |
| LOAD_CONST | 240 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,300 | 70.6% |
| TO_BOOL_BOOL | 1,000 | 8.5% |
| STORE_FAST | 780 | 6.6% |
| POP_TOP | 500 | 4.3% |
| LOAD_CONST | 359 | 3.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 16,440 | 37.0% |
| LOAD_GLOBAL_BUILTIN | 13,780 | 31.0% |
| LOAD_GLOBAL_MODULE | 12,480 | 28.1% |
| LOAD_ATTR | 880 | 2.0% |
| CALL | 700 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 43,380 | 97.5% |
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
| LOAD_ATTR_INSTANCE_VALUE | 102,366 | 53.2% |
| LOAD_FAST | 72,720 | 37.8% |
| LOAD_ATTR_WITH_HINT | 16,400 | 8.5% |
| CALL | 740 | 0.4% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,084 | 47.9% |
| LOAD_CONST | 59,240 | 30.8% |
| LOAD_GLOBAL_MODULE | 17,480 | 9.1% |
| STORE_FAST | 16,521 | 8.6% |
| COPY | 3,740 | 1.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,219 | 81.9% |
| BUILD_TUPLE | 3,400 | 14.5% |
| CALL | 360 | 1.5% |
| LOAD_CONST | 160 | 0.7% |
| CALL_KW | 120 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 16,220 | 69.1% |
| LOAD_FAST | 2,600 | 11.1% |
| RETURN_CONST | 2,200 | 9.4% |
| JUMP_BACKWARD | 1,180 | 5.0% |
| LOAD_GLOBAL_MODULE | 640 | 2.7% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 2,640 | 22.4% |
| LOAD_ATTR_METHOD_NO_DICT | 2,360 | 20.1% |
| LOAD_GLOBAL_MODULE | 1,600 | 13.6% |
| LOAD_CONST | 1,540 | 13.1% |
| LOAD_FAST_LOAD_FAST | 1,240 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,620 | 30.8% |
| RETURN_VALUE | 3,300 | 28.1% |
| LOAD_ATTR_METHOD_NO_DICT | 2,040 | 17.3% |
| LIST_APPEND | 1,120 | 9.5% |
| BUILD_TUPLE | 840 | 7.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 16,120 | 61.9% |
| LOAD_CONST | 3,821 | 14.7% |
| LOAD_FAST_LOAD_FAST | 3,720 | 14.3% |
| LOAD_ATTR | 640 | 2.5% |
| LOAD_FAST | 640 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 16,420 | 63.1% |
| STORE_FAST | 6,440 | 24.7% |
| POP_TOP | 1,581 | 6.1% |
| UNPACK_SEQUENCE_LIST | 1,080 | 4.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 120 | 0.5% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 54,880 | 44.6% |
| LOAD_ATTR_METHOD_NO_DICT | 50,085 | 40.7% |
| LOAD_ATTR_METHOD_LAZY_DICT | 8,120 | 6.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,040 | 6.5% |
| CALL | 1,480 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 53,822 | 43.7% |
| GET_ITER | 32,600 | 26.5% |
| STORE_FAST | 20,160 | 16.4% |
| RETURN_VALUE | 8,520 | 6.9% |
| BUILD_LIST | 2,680 | 2.2% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,345 | 72.5% |
| CALL | 9,781 | 12.4% |
| CALL_BUILTIN_FAST | 8,080 | 10.2% |
| LOAD_CONST | 1,980 | 2.5% |
| STORE_FAST | 1,120 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 75,387 | 95.4% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 166,448 | 37.8% |
| LOAD_FAST | 140,984 | 32.0% |
| LOAD_ATTR | 50,345 | 11.4% |
| LOAD_FAST_LOAD_FAST | 22,760 | 5.2% |
| LOAD_FAST_CHECK | 16,080 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 355,361 | 80.6% |
| RETURN_GENERATOR | 71,800 | 16.3% |
| MAKE_CELL | 9,801 | 2.2% |
| COPY_FREE_VARS | 3,699 | 0.8% |
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
| LOAD_CONST | 127,863 | 51.7% |
| LOAD_FAST | 67,880 | 27.4% |
| LOAD_ATTR_INSTANCE_VALUE | 20,165 | 8.2% |
| LOAD_ATTR_WITH_HINT | 8,160 | 3.3% |
| LOAD_FAST_LOAD_FAST | 8,140 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 244,608 | 98.9% |
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
| YIELD_VALUE | 120 | 2.3% |
| STORE_FAST | 120 | 2.3% |
| COPY | 60 | 1.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 17,460 | 72.8% |
| JUMP_BACKWARD | 3,939 | 16.4% |
| FOR_ITER | 840 | 3.5% |
| LOAD_FAST | 720 | 3.0% |
| SWAP | 620 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,759 | 44.8% |
| RETURN_CONST | 4,420 | 18.4% |
| LOAD_FAST | 3,800 | 15.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,120 | 13.0% |
| SWAP | 720 | 3.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,100 | 70.4% |
| JUMP_BACKWARD | 1,500 | 25.8% |
| FOR_ITER | 120 | 2.1% |
| SWAP | 100 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,120 | 88.0% |
| STORE_FAST_LOAD_FAST | 380 | 6.5% |
| LOAD_CONST | 280 | 4.8% |
| LOAD_GLOBAL_MODULE | 40 | 0.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,160 | 31.7% |
| SWAP | 1,120 | 30.6% |
| JUMP_BACKWARD | 840 | 23.0% |
| LOAD_FAST | 400 | 10.9% |
| FOR_ITER | 140 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,300 | 35.5% |
| STORE_FAST_LOAD_FAST | 1,120 | 30.6% |
| LOAD_FAST | 620 | 16.9% |
| RETURN_CONST | 340 | 9.3% |
| LOAD_GLOBAL_BUILTIN | 140 | 3.8% |


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
| LOAD_FAST | 753,150 | 96.8% |
| LOAD_FAST_LOAD_FAST | 12,424 | 1.6% |
| LOAD_ATTR | 7,780 | 1.0% |
| COPY | 2,039 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,340 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 159,139 | 20.5% |
| CALL_LEN | 102,366 | 13.2% |
| LOAD_ATTR_METHOD_NO_DICT | 81,414 | 10.5% |
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
| LOAD_ATTR_INSTANCE_VALUE | 81,414 | 34.5% |
| LOAD_FAST | 54,308 | 23.0% |
| CALL_BUILTIN_FAST | 31,960 | 13.5% |
| BINARY_OP | 16,120 | 6.8% |
| LOAD_ATTR_WITH_HINT | 16,040 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,026 | 40.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 50,085 | 21.2% |
| LOAD_GLOBAL_MODULE | 27,021 | 11.4% |
| LOAD_FAST_LOAD_FAST | 19,820 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 16,280 | 6.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 179,286 | 66.8% |
| LOAD_ATTR_SLOT | 27,240 | 10.2% |
| LOAD_ATTR_WITH_HINT | 18,440 | 6.9% |
| LOAD_ATTR_INSTANCE_VALUE | 10,226 | 3.8% |
| RETURN_VALUE | 9,520 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 166,448 | 62.0% |
| LOAD_FAST | 55,443 | 20.7% |
| LOAD_FAST_LOAD_FAST | 32,700 | 12.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 8,040 | 3.0% |
| CALL | 2,660 | 1.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 275,383 | 98.4% |
| LOAD_ATTR | 4,220 | 1.5% |
| LOAD_FAST | 280 | 0.1% |
| LOAD_ATTR_MODULE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 174,080 | 62.2% |
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
| LOAD_FAST | 925,800 | 74.2% |
| LOAD_FAST_LOAD_FAST | 320,060 | 25.6% |
| LOAD_ATTR | 1,240 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 959 | 0.1% |
| LOAD_ATTR_SLOT | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 351,920 | 28.2% |
| TO_BOOL_BOOL | 201,680 | 16.2% |
| LOAD_FAST | 197,419 | 15.8% |
| CALL_BUILTIN_FAST | 160,080 | 12.8% |
| STORE_SUBSCR_DICT | 159,960 | 12.8% |


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
| POP_JUMP_IF_FALSE | 306,787 | 41.3% |
| RESUME_CHECK | 146,960 | 19.8% |
| LOAD_GLOBAL_BUILTIN | 105,120 | 14.1% |
| LOAD_FAST | 48,460 | 6.5% |
| STORE_FAST | 43,640 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 401,110 | 53.9% |
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
| LOAD_ATTR_SLOT | 351,920 | 33.7% |
| RESUME_CHECK | 139,105 | 13.3% |
| LOAD_FAST | 106,523 | 10.2% |
| POP_JUMP_IF_FALSE | 75,382 | 7.2% |
| LOAD_ATTR_INSTANCE_VALUE | 54,082 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 353,600 | 33.8% |
| LOAD_ATTR_MODULE | 275,383 | 26.4% |
| LOAD_FAST | 137,045 | 13.1% |
| CALL_BUILTIN_FAST | 63,920 | 6.1% |
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
| CALL_PY_EXACT_ARGS | 355,361 | 41.0% |
| CACHE | 164,628 | 19.0% |
| POP_TOP | 158,280 | 18.3% |
| CALL_KW | 67,260 | 7.8% |
| CALL_FUNCTION_EX | 32,481 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 469,106 | 54.2% |
| LOAD_GLOBAL_BUILTIN | 146,960 | 17.0% |
| LOAD_GLOBAL_MODULE | 139,105 | 16.1% |
| LOAD_FAST_LOAD_FAST | 51,001 | 5.9% |
| NOP | 28,644 | 3.3% |


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
| LOAD_FAST_LOAD_FAST | 106,065 | 71.1% |
| LOAD_FAST | 35,817 | 24.0% |
| STORE_ATTR | 5,280 | 3.5% |
| SWAP | 2,039 | 1.4% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 103,143 | 69.1% |
| LOAD_FAST | 17,285 | 11.6% |
| RETURN_CONST | 16,084 | 10.8% |
| LOAD_CONST | 6,744 | 4.5% |
| LOAD_GLOBAL_MODULE | 2,344 | 1.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 98,480 | 54.6% |
| LOAD_FAST | 80,960 | 44.9% |
| STORE_ATTR | 700 | 0.4% |
| STORE_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 72,420 | 40.2% |
| LOAD_CONST | 50,840 | 28.2% |
| LOAD_FAST | 28,700 | 15.9% |
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
| LOAD_ATTR_SLOT | 201,680 | 24.9% |
| LOAD_ATTR_INSTANCE_VALUE | 159,139 | 19.7% |
| LOAD_ATTR | 145,743 | 18.0% |
| RETURN_VALUE | 79,682 | 9.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 53,822 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 469,810 | 58.1% |
| POP_JUMP_IF_TRUE | 329,732 | 40.8% |
| UNARY_NOT | 8,800 | 1.1% |
| EXTENDED_ARG | 100 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 43,460 | 70.4% |
| LOAD_ATTR_INSTANCE_VALUE | 8,920 | 14.4% |
| COPY | 6,840 | 11.1% |
| LOAD_FAST | 1,580 | 2.6% |
| TO_BOOL | 660 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 55,620 | 90.1% |
| POP_JUMP_IF_TRUE | 6,040 | 9.8% |
| UNARY_NOT | 80 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 14,560 | 91.2% |
| LOAD_FAST | 1,060 | 6.6% |
| TO_BOOL | 340 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,280 | 95.7% |
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
| LOAD_FAST | 1,761 | 49.4% |
| STORE_FAST_LOAD_FAST | 1,120 | 31.4% |
| COPY | 361 | 10.1% |
| TO_BOOL | 240 | 6.7% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,421 | 68.0% |
| POP_JUMP_IF_TRUE | 1,141 | 32.0% |


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
| RETURN_VALUE | 9,640 | 40.8% |
| CALL_BUILTIN_FAST | 8,120 | 34.4% |
| FOR_ITER_LIST | 3,120 | 13.2% |
| STORE_FAST | 1,400 | 5.9% |
| UNPACK_SEQUENCE | 620 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 23,300 | 98.7% |
| STORE_FAST_LOAD_FAST | 140 | 0.6% |
| STORE_FAST | 100 | 0.4% |
| LOAD_FAST | 60 | 0.3% |


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
|     deferred | 220,321 | 85.6% |
|          hit | 31,639 | 12.3% |

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
|          hit | 20,620 | 88.6% |
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
|     deferred | 330,553 | 18.3% |
|          hit | 1,393,725 | 77.1% |
|         miss | 54,800 | 3.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 17,760 | 61.0% |
| Failure | 11,370 | 39.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 2,340 | 20.6% |
| code complex parameters | 1,881 | 16.5% |
| class no vectorcall | 1,382 | 12.2% |
| cfunc noargs | 1,242 | 10.9% |
| meth descr varargs | 1,020 | 9.0% |
| class mutable | 1,020 | 9.0% |
| no dict | 580 | 5.1% |
| cfunc varargs keywords | 400 | 3.5% |
| cfunc varargs | 383 | 3.4% |
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
|          hit | 257,849 | 81.1% |
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
|     deferred | 248,483 | 87.4% |
|          hit | 33,479 | 11.8% |

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
|     deferred | 688,035 | 18.0% |
|        deopt | 80 | 0.0% |
|          hit | 3,071,775 | 80.5% |
|         miss | 14,281 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 25,820 | 59.1% |
| Failure | 17,842 | 40.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 6,160 | 34.5% |
| not managed dict | 3,120 | 17.5% |
| shadowed | 3,081 | 17.3% |
| method | 1,781 | 10.0% |
| metaclass attribute | 1,740 | 9.8% |
| non object slot | 460 | 2.6% |
| module attr not found | 400 | 2.2% |
| builtin class method | 400 | 2.2% |
| class attr descriptor | 320 | 1.8% |
| class method obj | 220 | 1.2% |
| mutable class | 80 | 0.4% |
| class attr simple | 80 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 15,900 | 0.9% |
|        deopt | 160 | 0.0% |
|          hit | 1,785,030 | 98.1% |
|         miss | 3,220 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 16,080 | 100.0% |
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
|     deferred | 215,941 | 38.7% |
|          hit | 322,181 | 57.8% |
|         miss | 9,880 | 1.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,320 | 66.9% |
| Failure | 3,120 | 33.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 960 | 30.8% |
| not in keys | 840 | 26.9% |
| not in dict | 740 | 23.7% |
| overriding descriptor | 200 | 6.4% |
| method | 120 | 3.8% |
| not managed dict | 120 | 3.8% |
| overridden | 80 | 2.6% |
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
|     deferred | 13,021 | 7.1% |
|          hit | 170,243 | 92.5% |

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
|     deferred | 74,462 | 7.0% |
|          hit | 975,326 | 92.1% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,280 | 82.3% |
| Failure | 1,561 | 17.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 460 | 29.5% |
| sequence | 401 | 25.7% |
| set | 240 | 15.4% |
| dict | 160 | 10.2% |
| memory view | 140 | 9.0% |
| mapping | 80 | 5.1% |
| tuple | 60 | 3.8% |
| float | 20 | 1.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,100 | 3.0% |
|          hit | 34,780 | 94.3% |

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
| Basic | 12,609,030 | 48.2% |
| Not specialized | 4,377,980 | 16.7% |
| Specialized hits | 9,080,844 | 34.7% |
| Specialized misses | 83,199 | 0.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 688,035 | 36.7% |
| CALL | 330,553 | 17.7% |
| FOR_ITER | 248,483 | 13.3% |
| BINARY_OP | 220,321 | 11.8% |
| STORE_ATTR | 215,941 | 11.5% |
| TO_BOOL | 74,462 | 4.0% |
| COMPARE_OP | 55,499 | 3.0% |
| LOAD_GLOBAL | 15,900 | 0.8% |
| STORE_SUBSCR | 13,021 | 0.7% |
| SEND | 6,920 | 0.4% |


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
| Calls to PyEval_EvalDefault | 210,248 | 20.3% |
| Calls to Python functions inlined | 825,428 | 79.7% |
| Calls via PyEval_EvalFrame (total) | 210,248 | 20.3% |
| Calls via PyEval_EvalFrame (vector) | 193,388 | 18.7% |
| Calls via PyEval_EvalFrame (generator) | 16,860 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 193,048 | 18.6% |
| Calls via PyEval_EvalFrame (build class) | 260 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 5,601 | 0.5% |
| Calls via PyEval_EvalFrame (function ex) | 33,441 | 3.2% |
| Calls via PyEval_EvalFrame (api) | 10,001 | 1.0% |
| Calls via PyEval_EvalFrame (method) | 42,400 | 4.1% |
| Frame objects created | 4,221 | 0.4% |
| Frames pushed | 560,128 | 54.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 776,522 | 32.7% |
| Frees to freelist | 780,682 |  |
| Allocations | 1,598,068 | 67.3% |
| Allocations to 512 bytes | 1,407,981 | 59.3% |
| Allocations to 4 kbytes | 132,285 | 5.6% |
| Allocations over 4 kbytes | 57,802 | 2.4% |
| Frees | 1,537,412 |  |
| New values | 34,781 |  |
| Interpreter increfs | 12,301,897 | 76.8% |
| Interpreter decrefs | 14,096,305 | 78.2% |
| Increfs | 3,716,049 | 23.2% |
| Decrefs | 3,925,504 | 21.8% |
| Materialize dict (on request) | 20 | 0.1% |
| Materialize dict (new key) | 160 | 0.5% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 20 | 0.1% |
| Method cache hits | 1,237,637 |  |
| Method cache misses | 33,223 |  |
| Method cache collisions | 36,952 |  |
| Method cache dunder hits | 357,636 |  |
| Method cache dunder misses | 6,280 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 100 | 540 | 744,436 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 12,640 |  |
| Traces created | 260 | 2.1% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 12,380 | 97.9% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 81,360 |  |
| Uops executed | 2,078,680 | 25.55 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 60 | 23.1% |
| <= 32 | 120 | 46.2% |
| <= 64 | 0 | 0.0% |
| <= 128 | 80 | 30.8% |


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
| <= 16 | 80 | 30.8% |
| <= 32 | 100 | 38.5% |
| <= 64 | 40 | 15.4% |
| <= 128 | 40 | 15.4% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 13,980 | 17.2% |
| <= 16 | 23,040 | 28.3% |
| <= 32 | 21,200 | 26.1% |
| <= 64 | 20,920 | 25.7% |
| <= 128 | 2,140 | 2.6% |
| <= 256 | 20 | 0.0% |
| <= 512 | 20 | 0.0% |
| <= 1,024 | 40 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 11,920 |
| LOAD_ATTR | 580 |
| TO_BOOL | 40 |
| CALL_KW | 40 |
| RETURN_GENERATOR | 20 |
| YIELD_VALUE | 20 |


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
Stats gathered on: 2023-11-02
