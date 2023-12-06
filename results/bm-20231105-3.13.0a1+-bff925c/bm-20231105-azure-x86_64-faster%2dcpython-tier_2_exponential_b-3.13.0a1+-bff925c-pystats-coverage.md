
# Pystats results

- benchmark: coverage
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 50,566,880 | 20.6% | 20.6% |  |
| LOAD_CONST | 39,093,520 | 15.9% | 36.5% |  |
| CALL_PY_EXACT_ARGS | 19,645,660 | 8.0% | 44.5% |  |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 19,465,840 | 7.9% | 52.5% |  |
| INSTRUMENTED_RESUME | 19,443,620 | 7.9% | 60.4% |  |
| INSTRUMENTED_RETURN_VALUE | 19,434,720 | 7.9% | 68.3% |  |
| COMPARE_OP_INT | 19,431,780 | 7.9% | 76.2% |  |
| BINARY_OP_SUBTRACT_INT | 19,431,580 | 7.9% | 84.2% |  |
| LOAD_GLOBAL_MODULE | 10,308,480 | 4.2% | 88.4% |  |
| LOAD_GLOBAL | 9,774,060 | 4.0% | 92.3% |  |
| BINARY_OP_ADD_INT | 9,717,540 | 4.0% | 96.3% |  |
| LOAD_FAST_LOAD_FAST | 815,060 | 0.3% | 96.6% |  |
| POP_JUMP_IF_FALSE | 743,100 | 0.3% | 96.9% |  |
| STORE_FAST | 676,400 | 0.3% | 97.2% |  |
| FOR_ITER | 431,740 | 0.2% | 97.4% |  |
| JUMP_BACKWARD | 395,900 | 0.2% | 97.5% |  |
| LOAD_ATTR_MODULE | 391,020 | 0.2% | 97.7% | 3.2% |
| STORE_FAST_STORE_FAST | 359,900 | 0.1% | 97.9% |  |
| TO_BOOL_BOOL | 346,300 | 0.1% | 98.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 341,440 | 0.1% | 98.1% |  |
| CONTAINS_OP | 340,920 | 0.1% | 98.3% |  |
| STORE_SUBSCR_DICT | 338,720 | 0.1% | 98.4% |  |
| LOAD_GLOBAL_BUILTIN | 334,520 | 0.1% | 98.5% | 0.7% |
| RESUME_CHECK | 325,980 | 0.1% | 98.7% | 2.4% |
| CALL | 271,645 | 0.1% | 98.8% |  |
| PUSH_NULL | 236,040 | 0.1% | 98.9% |  |
| RETURN_VALUE | 202,220 | 0.1% | 99.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 179,360 | 0.1% | 99.0% |  |
| NOP | 174,740 | 0.1% | 99.1% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 174,000 | 0.1% | 99.2% | 0.0% |
| POP_JUMP_IF_TRUE | 150,800 | 0.1% | 99.2% |  |
| CALL_ISINSTANCE | 135,880 | 0.1% | 99.3% |  |
| TO_BOOL_STR | 107,660 | 0.0% | 99.3% | 0.5% |
| ENTER_EXECUTOR | 99,580 | 0.0% | 99.4% |  |
| RETURN_CONST | 92,580 | 0.0% | 99.4% |  |
| LOAD_ATTR | 76,640 | 0.0% | 99.5% |  |
| POP_TOP | 74,180 | 0.0% | 99.5% |  |
| GET_ITER | 73,060 | 0.0% | 99.5% |  |
| CALL_BUILTIN_O | 69,360 | 0.0% | 99.5% |  |
| TO_BOOL | 64,080 | 0.0% | 99.6% |  |
| LOAD_ATTR_SLOT | 58,880 | 0.0% | 99.6% |  |
| INTERPRETER_EXIT | 55,060 | 0.0% | 99.6% |  |
| CALL_BUILTIN_CLASS | 54,640 | 0.0% | 99.6% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 51,620 | 0.0% | 99.7% |  |
| BINARY_OP_ADD_UNICODE | 48,740 | 0.0% | 99.7% |  |
| EXTENDED_ARG | 39,400 | 0.0% | 99.7% |  |
| LOAD_DEREF | 37,660 | 0.0% | 99.7% |  |
| COMPARE_OP_STR | 35,780 | 0.0% | 99.7% | 0.1% |
| YIELD_VALUE | 32,620 | 0.0% | 99.7% |  |
| BUILD_TUPLE | 32,480 | 0.0% | 99.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 32,280 | 0.0% | 99.8% |  |
| BINARY_SLICE | 29,800 | 0.0% | 99.8% |  |
| FOR_ITER_LIST | 26,240 | 0.0% | 99.8% |  |
| TO_BOOL_NONE | 24,860 | 0.0% | 99.8% | 7.3% |
| COPY | 24,540 | 0.0% | 99.8% |  |
| MAP_ADD | 21,000 | 0.0% | 99.8% |  |
| CALL_BUILTIN_FAST | 20,400 | 0.0% | 99.8% | 0.1% |
| STORE_ATTR | 20,040 | 0.0% | 99.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 19,780 | 0.0% | 99.8% |  |
| BINARY_OP | 17,380 | 0.0% | 99.8% |  |
| COPY_FREE_VARS | 17,380 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 15,080 | 0.0% | 99.9% | 0.1% |
| UNPACK_SEQUENCE_TUPLE | 14,900 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 14,460 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 14,260 | 0.0% | 99.9% |  |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 13,440 | 0.0% | 99.9% |  |
| RETURN_GENERATOR | 13,200 | 0.0% | 99.9% |  |
| BUILD_MAP | 12,700 | 0.0% | 99.9% |  |
| POP_JUMP_IF_NOT_NONE | 11,800 | 0.0% | 99.9% |  |
| INSTRUMENTED_FOR_ITER | 11,280 | 0.0% | 99.9% |  |
| BUILD_LIST | 10,040 | 0.0% | 99.9% |  |
| INSTRUMENTED_JUMP_BACKWARD | 10,000 | 0.0% | 99.9% |  |
| CALL_LEN | 9,520 | 0.0% | 99.9% |  |
| SWAP | 9,440 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 9,320 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 8,740 | 0.0% | 99.9% | 1.1% |
| JUMP_FORWARD | 8,480 | 0.0% | 99.9% |  |
| INSTRUMENTED_RETURN_CONST | 7,200 | 0.0% | 99.9% |  |
| MAKE_CELL | 6,940 | 0.0% | 99.9% |  |
| IS_OP | 6,860 | 0.0% | 99.9% |  |
| STORE_DEREF | 6,620 | 0.0% | 99.9% |  |
| LIST_APPEND | 6,360 | 0.0% | 99.9% |  |
| CALL_PY_WITH_DEFAULTS | 6,180 | 0.0% | 99.9% | 1.3% |
| CALL_FUNCTION_EX | 5,940 | 0.0% | 99.9% |  |
| COMPARE_OP | 5,740 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,500 | 0.0% | 100.0% | 1.1% |
| CALL_KW | 5,500 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 5,300 | 0.0% | 100.0% |  |
| POP_EXCEPT | 5,300 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 5,300 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 5,280 | 0.0% | 100.0% | 6.8% |
| BINARY_SUBSCR_TUPLE_INT | 4,480 | 0.0% | 100.0% |  |
| RESUME | 4,180 | 0.0% | 100.0% | 186.1% |
| STORE_ATTR_SLOT | 4,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 3,760 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 3,680 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,380 | 0.0% | 100.0% |  |
| LOAD_ATTR_WITH_HINT | 3,300 | 0.0% | 100.0% |  |
| DICT_MERGE | 3,120 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 3,040 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 3,000 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NONE | 2,980 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 2,900 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 2,740 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 2,620 | 0.0% | 100.0% | 44.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,200 | 0.0% | 100.0% | 11.8% |
| CALL_TYPE_1 | 2,080 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,060 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 1,900 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 1,880 | 0.0% | 100.0% | 2.1% |
| EXIT_INIT_CHECK | 1,800 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 1,800 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,780 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 1,720 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 1,680 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 1,460 | 0.0% | 100.0% |  |
| LIST_EXTEND | 1,460 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 1,340 | 0.0% | 100.0% |  |
| UNPACK_EX | 1,280 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 1,200 | 0.0% | 100.0% |  |
| DICT_UPDATE | 1,160 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 980 | 0.0% | 100.0% |  |
| BUILD_STRING | 980 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 780 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_NONE | 720 | 0.0% | 100.0% |  |
| LOAD_ATTR_PROPERTY | 640 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 580 | 0.0% | 100.0% |  |
| BEFORE_WITH | 560 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 560 | 0.0% | 100.0% |  |
| STORE_ATTR_WITH_HINT | 520 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 500 | 0.0% | 100.0% |  |
| DELETE_ATTR | 480 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 400 | 0.0% | 100.0% |  |
| INSTRUMENTED_JUMP_FORWARD | 400 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_NOT_NONE | 400 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 360 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 360 | 0.0% | 100.0% |  |
| BUILD_SLICE | 340 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 300 | 0.0% | 100.0% |  |
| RERAISE | 300 | 0.0% | 100.0% |  |
| UNARY_NOT | 280 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 260 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 220 | 0.0% | 100.0% |  |
| IMPORT_NAME | 200 | 0.0% | 100.0% |  |
| UNARY_INVERT | 160 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 160 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 120 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| CALL_STR_1 | 60 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 20 | 0.0% | 100.0% |  |
| STORE_NAME | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_CONST | 38,905,080 | 15.9% | 15.9% |
| CALL_PY_EXACT_ARGS INSTRUMENTED_RESUME | 19,436,580 | 7.9% | 23.8% |
| LOAD_CONST COMPARE_OP_INT | 19,429,120 | 7.9% | 31.7% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 19,426,780 | 7.9% | 39.6% |
| INSTRUMENTED_RESUME LOAD_FAST | 19,425,760 | 7.9% | 47.5% |
| COMPARE_OP_INT INSTRUMENTED_POP_JUMP_IF_FALSE | 19,422,780 | 7.9% | 55.4% |
| BINARY_OP_SUBTRACT_INT CALL_PY_EXACT_ARGS | 19,422,640 | 7.9% | 63.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 9,899,420 | 4.0% | 67.4% |
| LOAD_GLOBAL LOAD_FAST | 9,733,500 | 4.0% | 71.4% |
| INSTRUMENTED_POP_JUMP_IF_FALSE LOAD_FAST | 9,729,360 | 4.0% | 75.3% |
| LOAD_FAST INSTRUMENTED_RETURN_VALUE | 9,717,760 | 4.0% | 79.3% |
| INSTRUMENTED_POP_JUMP_IF_FALSE LOAD_GLOBAL | 9,716,800 | 4.0% | 83.2% |
| BINARY_OP_ADD_INT INSTRUMENTED_RETURN_VALUE | 9,711,340 | 4.0% | 87.2% |
| INSTRUMENTED_RETURN_VALUE BINARY_OP_ADD_INT | 9,711,320 | 4.0% | 91.2% |
| INSTRUMENTED_RETURN_VALUE LOAD_GLOBAL_MODULE | 9,711,320 | 4.0% | 95.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 389,920 | 0.2% | 95.3% |
| JUMP_BACKWARD FOR_ITER | 379,520 | 0.2% | 95.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 376,300 | 0.2% | 95.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 340,460 | 0.1% | 95.7% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 337,220 | 0.1% | 95.9% |
| LOAD_FAST STORE_SUBSCR_DICT | 330,200 | 0.1% | 96.0% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 329,820 | 0.1% | 96.1% |
| STORE_SUBSCR_DICT JUMP_BACKWARD | 328,620 | 0.1% | 96.3% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 323,740 | 0.1% | 96.4% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 322,880 | 0.1% | 96.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 312,480 | 0.1% | 96.6% |
| STORE_FAST LOAD_FAST | 275,720 | 0.1% | 96.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 244,180 | 0.1% | 96.9% |
| PUSH_NULL LOAD_FAST | 222,980 | 0.1% | 97.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 222,240 | 0.1% | 97.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 188,420 | 0.1% | 97.1% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 173,580 | 0.1% | 97.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 172,760 | 0.1% | 97.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 171,220 | 0.1% | 97.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 164,800 | 0.1% | 97.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 157,920 | 0.1% | 97.5% |
| LOAD_FAST CALL | 154,620 | 0.1% | 97.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 152,420 | 0.1% | 97.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 152,200 | 0.1% | 97.6% |
| STORE_FAST LOAD_GLOBAL_MODULE | 150,200 | 0.1% | 97.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 121,700 | 0.0% | 97.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 117,920 | 0.0% | 97.8% |
| CALL TO_BOOL_BOOL | 109,780 | 0.0% | 97.9% |
| LOAD_FAST STORE_FAST | 108,960 | 0.0% | 97.9% |
| NOP LOAD_FAST | 108,340 | 0.0% | 97.9% |
| STORE_FAST NOP | 106,280 | 0.0% | 98.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 99,740 | 0.0% | 98.0% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 97,980 | 0.0% | 98.1% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 96,780 | 0.0% | 98.1% |
| LOAD_FAST TO_BOOL_STR | 83,720 | 0.0% | 98.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 76,840 | 0.0% | 98.2% |
| ENTER_EXECUTOR CALL | 75,740 | 0.0% | 98.2% |
| RETURN_VALUE STORE_FAST | 70,120 | 0.0% | 98.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 69,580 | 0.0% | 98.3% |
| LOAD_ATTR_MODULE LOAD_FAST | 67,620 | 0.0% | 98.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 66,660 | 0.0% | 98.3% |
| TO_BOOL_STR POP_JUMP_IF_FALSE | 66,420 | 0.0% | 98.3% |
| RETURN_CONST STORE_FAST | 64,360 | 0.0% | 98.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 58,640 | 0.0% | 98.4% |
| LOAD_FAST RETURN_VALUE | 58,600 | 0.0% | 98.4% |
| LOAD_FAST TO_BOOL | 57,440 | 0.0% | 98.4% |
| NOP LOAD_GLOBAL_MODULE | 55,580 | 0.0% | 98.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 55,480 | 0.0% | 98.5% |
| LOAD_FAST LOAD_ATTR_SLOT | 54,760 | 0.0% | 98.5% |
| CALL RESUME_CHECK | 54,440 | 0.0% | 98.5% |
| LOAD_FAST TO_BOOL_BOOL | 54,340 | 0.0% | 98.5% |
| RETURN_VALUE TO_BOOL_BOOL | 53,280 | 0.0% | 98.6% |
| LOAD_FAST CALL_BUILTIN_CLASS | 53,080 | 0.0% | 98.6% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 51,880 | 0.0% | 98.6% |
| CALL_BUILTIN_CLASS GET_ITER | 51,360 | 0.0% | 98.6% |
| CALL_BUILTIN_O STORE_FAST | 51,160 | 0.0% | 98.7% |
| LOAD_ATTR_SLOT CALL_BUILTIN_O | 51,140 | 0.0% | 98.7% |
| FOR_ITER STORE_FAST | 50,380 | 0.0% | 98.7% |
| LOAD_CONST LOAD_CONST | 49,620 | 0.0% | 98.7% |
| GET_ITER FOR_ITER | 48,980 | 0.0% | 98.7% |
| TO_BOOL POP_JUMP_IF_TRUE | 48,680 | 0.0% | 98.8% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 48,420 | 0.0% | 98.8% |
| LOAD_FAST BINARY_OP_ADD_UNICODE | 48,040 | 0.0% | 98.8% |
| FOR_ITER NOP | 47,300 | 0.0% | 98.8% |
| BINARY_OP_INPLACE_ADD_UNICODE JUMP_BACKWARD | 47,280 | 0.0% | 98.8% |
| BINARY_OP_ADD_UNICODE BINARY_OP_INPLACE_ADD_UNICODE | 46,640 | 0.0% | 98.9% |
| LOAD_ATTR_MODULE LOAD_ATTR_MODULE | 44,920 | 0.0% | 98.9% |
| STORE_FAST ENTER_EXECUTOR | 42,860 | 0.0% | 98.9% |
| CALL_ISINSTANCE RETURN_VALUE | 38,820 | 0.0% | 98.9% |
| CACHE RESUME_CHECK | 38,580 | 0.0% | 98.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 36,740 | 0.0% | 98.9% |
| LOAD_ATTR CALL_ISINSTANCE | 34,840 | 0.0% | 98.9% |
| YIELD_VALUE INTERPRETER_EXIT | 32,620 | 0.0% | 99.0% |
| RESUME_CHECK POP_TOP | 31,940 | 0.0% | 99.0% |
| CALL YIELD_VALUE | 30,860 | 0.0% | 99.0% |
| RESUME_CHECK LOAD_FAST | 30,340 | 0.0% | 99.0% |
| POP_TOP ENTER_EXECUTOR | 29,020 | 0.0% | 99.0% |
| LOAD_FAST LOAD_ATTR | 28,200 | 0.0% | 99.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 27,300 | 0.0% | 99.0% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_STR | 27,240 | 0.0% | 99.0% |
| CALL STORE_FAST | 26,900 | 0.0% | 99.1% |
| LOAD_CONST BINARY_SLICE | 26,260 | 0.0% | 99.1% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 25,680 | 0.0% | 99.1% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 24,900 | 0.0% | 99.1% |
| LOAD_CONST LOAD_FAST | 23,840 | 0.0% | 99.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 26,260 | 88.1% |
| LOAD_FAST | 2,020 | 6.8% |
| BINARY_OP_ADD_INT | 1,480 | 5.0% |
| BINARY_OP | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,640 | 42.4% |
| LOAD_FAST_LOAD_FAST | 6,600 | 22.1% |
| BINARY_OP | 6,380 | 21.4% |
| STORE_FAST_STORE_FAST | 1,560 | 5.2% |
| LOAD_FAST | 1,260 | 4.2% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 38,580 | 69.6% |
| POP_TOP | 13,200 | 23.8% |
| COPY_FREE_VARS | 2,640 | 4.8% |
| RESUME | 600 | 1.1% |
| INSTRUMENTED_RESUME | 300 | 0.5% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 320 | 57.1% |
| LOAD_ATTR_INSTANCE_VALUE | 100 | 17.9% |
| CALL | 80 | 14.3% |
| LOAD_ATTR | 20 | 3.6% |
| LOAD_GLOBAL | 20 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 420 | 75.0% |
| STORE_FAST | 140 | 25.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 46,640 | 90.4% |
| LOAD_FAST_LOAD_FAST | 4,720 | 9.1% |
| BINARY_SUBSCR_STR_INT | 180 | 0.3% |
| LOAD_ATTR_MODULE | 60 | 0.1% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 47,280 | 91.6% |
| INSTRUMENTED_JUMP_BACKWARD | 4,080 | 7.9% |
| LOAD_FAST | 180 | 0.3% |
| LOAD_GLOBAL_MODULE | 60 | 0.1% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,560 | 68.1% |
| LOAD_FAST | 380 | 10.1% |
| BINARY_SUBSCR | 360 | 9.6% |
| BUILD_SLICE | 340 | 9.0% |
| LOAD_FAST_LOAD_FAST | 80 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,520 | 40.4% |
| BUILD_TUPLE | 640 | 17.0% |
| BINARY_SUBSCR | 360 | 9.6% |
| GET_ITER | 260 | 6.9% |
| STORE_FAST | 180 | 4.8% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,200 | 98.1% |
| LOAD_GLOBAL | 100 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,300 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,800 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 560 | 41.8% |
| LOAD_ATTR_INSTANCE_VALUE | 360 | 26.9% |
| LOAD_FAST | 340 | 25.4% |
| LOAD_ATTR | 80 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 680 | 50.7% |
| BUILD_STRING | 660 | 49.3% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 51,360 | 70.3% |
| LOAD_FAST | 10,040 | 13.7% |
| LOAD_ATTR_MODULE | 6,420 | 8.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,740 | 2.4% |
| RETURN_VALUE | 940 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 48,980 | 67.0% |
| CALL_PY_EXACT_ARGS | 12,840 | 17.6% |
| INSTRUMENTED_FOR_ITER | 5,280 | 7.2% |
| FOR_ITER_LIST | 2,740 | 3.8% |
| LOAD_FAST_AND_CLEAR | 1,520 | 2.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 32,620 | 59.2% |
| RETURN_CONST | 14,440 | 26.2% |
| RETURN_VALUE | 7,680 | 13.9% |
| INSTRUMENTED_RETURN_VALUE | 320 | 0.6% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,460 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 14,180 | 98.1% |
| LOAD_FAST | 160 | 1.1% |
| LOAD_GLOBAL | 40 | 0.3% |
| LOAD_GLOBAL_MODULE | 40 | 0.3% |
| STORE_FAST | 20 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 106,280 | 60.8% |
| FOR_ITER | 47,300 | 27.1% |
| RESUME_CHECK | 8,960 | 5.1% |
| POP_JUMP_IF_FALSE | 4,780 | 2.7% |
| INSTRUMENTED_FOR_ITER | 4,080 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,340 | 62.0% |
| LOAD_GLOBAL_MODULE | 55,580 | 31.8% |
| LOAD_GLOBAL | 4,680 | 2.7% |
| LOAD_FAST_LOAD_FAST | 2,940 | 1.7% |
| LOAD_GLOBAL_BUILTIN | 2,120 | 1.2% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,460 | 84.2% |
| POP_TOP | 440 | 8.3% |
| COPY | 300 | 5.7% |
| STORE_FAST | 40 | 0.8% |
| STORE_ATTR_INSTANCE_VALUE | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,460 | 84.2% |
| RERAISE | 300 | 5.7% |
| JUMP_BACKWARD | 280 | 5.3% |
| RETURN_CONST | 200 | 3.8% |
| JUMP_FORWARD | 40 | 0.8% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 31,940 | 43.1% |
| CACHE | 13,200 | 17.8% |
| RETURN_CONST | 6,900 | 9.3% |
| POP_JUMP_IF_FALSE | 5,440 | 7.3% |
| CALL_BUILTIN_O | 3,660 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 29,020 | 39.1% |
| RESUME_CHECK | 13,060 | 17.6% |
| LOAD_FAST | 11,240 | 15.2% |
| JUMP_BACKWARD | 6,100 | 8.2% |
| RETURN_CONST | 5,100 | 6.9% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,880 | 54.3% |
| CALL_BUILTIN_CLASS | 1,180 | 22.3% |
| BINARY_SUBSCR_DICT | 380 | 7.2% |
| CALL_KW | 320 | 6.0% |
| RERAISE | 300 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,120 | 96.6% |
| LOAD_GLOBAL | 180 | 3.4% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 222,240 | 94.2% |
| LOAD_FAST | 7,920 | 3.4% |
| LOAD_ATTR | 3,340 | 1.4% |
| STORE_FAST_LOAD_FAST | 2,060 | 0.9% |
| LOAD_DEREF | 460 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 222,980 | 94.5% |
| LOAD_CONST | 6,360 | 2.7% |
| LOAD_FAST_LOAD_FAST | 2,920 | 1.2% |
| LOAD_GLOBAL_MODULE | 1,820 | 0.8% |
| CALL | 1,220 | 0.5% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 12,800 | 97.0% |
| CALL_PY_EXACT_ARGS | 180 | 1.4% |
| CALL_FUNCTION_EX | 160 | 1.2% |
| CALL | 60 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 12,680 | 96.1% |
| CALL | 240 | 1.8% |
| LOAD_FAST | 160 | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.9% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,600 | 29.0% |
| CALL_ISINSTANCE | 38,820 | 19.2% |
| RETURN_VALUE | 21,240 | 10.5% |
| CALL | 18,840 | 9.3% |
| POP_JUMP_IF_TRUE | 11,700 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 70,120 | 34.7% |
| TO_BOOL_BOOL | 53,280 | 26.3% |
| RETURN_VALUE | 21,240 | 10.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,100 | 4.5% |
| CALL_PY_EXACT_ARGS | 8,600 | 4.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 420 | 42.9% |
| LOAD_FAST | 380 | 38.8% |
| LOAD_FAST_LOAD_FAST | 80 | 8.2% |
| RETURN_VALUE | 40 | 4.1% |
| CALL | 40 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 320 | 32.7% |
| STORE_SUBSCR_DICT | 220 | 22.4% |
| RETURN_CONST | 140 | 14.3% |
| EXTENDED_ARG | 120 | 12.2% |
| JUMP_BACKWARD | 80 | 8.2% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,440 | 89.6% |
| CALL | 1,100 | 1.7% |
| RETURN_VALUE | 1,080 | 1.7% |
| COPY | 920 | 1.4% |
| TO_BOOL | 800 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 48,680 | 76.0% |
| POP_JUMP_IF_FALSE | 6,200 | 9.7% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 4,280 | 6.7% |
| TO_BOOL_BOOL | 2,080 | 3.2% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 840 | 1.3% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 160 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 380 | 95.0% |
| CALL | 20 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 180 | 64.3% |
| TO_BOOL_LIST | 100 | 35.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 180 | 64.3% |
| CALL_PY_EXACT_ARGS | 100 | 35.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 6,380 | 36.7% |
| LOAD_CONST | 2,380 | 13.7% |
| LOAD_GLOBAL_MODULE | 2,200 | 12.7% |
| LOAD_FAST | 2,020 | 11.6% |
| CALL_LEN | 1,580 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,900 | 51.2% |
| TO_BOOL_INT | 1,900 | 10.9% |
| COMPARE_OP_STR | 1,560 | 9.0% |
| BINARY_OP_SUBTRACT_INT | 1,400 | 8.1% |
| BINARY_OP | 900 | 5.2% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20 | 33.3% |
| DICT_UPDATE | 20 | 33.3% |
| STORE_FAST | 20 | 33.3% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,900 | 28.9% |
| STORE_ATTR_INSTANCE_VALUE | 2,100 | 20.9% |
| SWAP | 1,440 | 14.3% |
| RESUME_CHECK | 920 | 9.2% |
| STORE_FAST | 500 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,320 | 43.0% |
| STORE_FAST | 3,500 | 34.9% |
| SWAP | 1,520 | 15.1% |
| GET_ITER | 240 | 2.4% |
| LOAD_DEREF | 240 | 2.4% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,800 | 37.8% |
| LOAD_CONST | 2,820 | 22.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,260 | 9.9% |
| DICT_UPDATE | 1,120 | 8.8% |
| STORE_ATTR_INSTANCE_VALUE | 680 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,800 | 37.8% |
| LOAD_FAST | 4,540 | 35.7% |
| CALL_FUNCTION_EX | 1,280 | 10.1% |
| EXTENDED_ARG | 920 | 7.2% |
| STORE_FAST | 640 | 5.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 340 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 660 | 67.3% |
| LOAD_CONST | 320 | 32.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 320 | 32.7% |
| YIELD_VALUE | 320 | 32.7% |
| CALL | 180 | 18.4% |
| CALL_PY_EXACT_ARGS | 160 | 16.3% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,780 | 54.7% |
| LOAD_FAST_LOAD_FAST | 6,680 | 20.6% |
| LOAD_CONST | 5,380 | 16.6% |
| BINARY_SUBSCR | 640 | 2.0% |
| CALL | 380 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,220 | 40.7% |
| RETURN_VALUE | 8,540 | 26.3% |
| CALL | 3,960 | 12.2% |
| BINARY_SUBSCR_DICT | 2,000 | 6.2% |
| LOAD_FAST | 1,780 | 5.5% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 154,620 | 56.9% |
| ENTER_EXECUTOR | 75,740 | 27.9% |
| LOAD_FAST_LOAD_FAST | 13,440 | 4.9% |
| LOAD_CONST | 7,700 | 2.8% |
| CALL | 5,265 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 109,780 | 40.4% |
| RESUME_CHECK | 54,440 | 20.0% |
| YIELD_VALUE | 30,860 | 11.4% |
| STORE_FAST | 26,900 | 9.9% |
| RETURN_VALUE | 18,840 | 6.9% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 3,120 | 52.5% |
| LOAD_FAST | 1,380 | 23.2% |
| BUILD_MAP | 1,280 | 21.5% |
| CALL_INTRINSIC_1 | 80 | 1.3% |
| MAP_ADD | 80 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,760 | 46.5% |
| LOAD_CONST | 1,280 | 21.5% |
| CALL_LIST_APPEND | 1,240 | 20.9% |
| RETURN_GENERATOR | 160 | 2.7% |
| RESUME_CHECK | 160 | 2.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,460 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_EX | 1,280 | 87.7% |
| BUILD_MAP | 100 | 6.8% |
| CALL_FUNCTION_EX | 80 | 5.5% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,460 | 99.3% |
| ENTER_EXECUTOR | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,660 | 30.2% |
| RETURN_VALUE | 1,600 | 29.1% |
| STORE_FAST | 1,580 | 28.7% |
| PUSH_EXC_INFO | 320 | 5.8% |
| LOAD_FAST | 240 | 4.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 3,800 | 66.2% |
| LOAD_CONST | 960 | 16.7% |
| LOAD_GLOBAL_MODULE | 240 | 4.2% |
| COMPARE_OP | 220 | 3.8% |
| LOAD_FAST_LOAD_FAST | 160 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,800 | 83.6% |
| COMPARE_OP_STR | 280 | 4.9% |
| COMPARE_OP | 220 | 3.8% |
| COMPARE_OP_INT | 200 | 3.5% |
| POP_JUMP_IF_TRUE | 100 | 1.7% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 322,880 | 94.7% |
| LOAD_GLOBAL_MODULE | 6,500 | 1.9% |
| LOAD_ATTR_MODULE | 5,860 | 1.7% |
| LOAD_CONST | 3,080 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,020 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 337,220 | 98.9% |
| EXTENDED_ARG | 1,200 | 0.4% |
| POP_JUMP_IF_TRUE | 1,000 | 0.3% |
| RETURN_VALUE | 840 | 0.2% |
| INSTRUMENTED_RETURN_VALUE | 320 | 0.1% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 480 | 85.7% |
| LOAD_ATTR | 80 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 560 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,320 | 50.2% |
| RETURN_VALUE | 4,540 | 18.5% |
| LOAD_ATTR_MODULE | 3,780 | 15.4% |
| LOAD_FAST | 1,080 | 4.4% |
| RETURN_CONST | 560 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 17,900 | 72.9% |
| LOAD_GLOBAL_MODULE | 3,780 | 15.4% |
| TO_BOOL | 920 | 3.7% |
| STORE_FAST_STORE_FAST | 380 | 1.5% |
| POP_EXCEPT | 300 | 1.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 13,720 | 78.9% |
| CACHE | 2,640 | 15.2% |
| CALL | 500 | 2.9% |
| CALL_ALLOC_AND_ENTER_INIT | 220 | 1.3% |
| CALL_PY_WITH_DEFAULTS | 220 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 12,800 | 73.6% |
| RESUME_CHECK | 4,320 | 24.9% |
| RESUME | 260 | 1.5% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320 | 66.7% |
| NOP | 160 | 33.3% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,100 | 99.4% |
| CALL | 20 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 3,120 | 100.0% |


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 1,140 | 98.3% |
| BUILD_CONST_KEY_MAP | 20 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 1,120 | 96.6% |
| EXTENDED_ARG | 20 | 1.7% |
| STORE_NAME | 20 | 1.7% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 42,860 | 43.0% |
| POP_TOP | 29,020 | 29.1% |
| POP_JUMP_IF_FALSE | 20,840 | 20.9% |
| LIST_APPEND | 3,280 | 3.3% |
| EXTENDED_ARG | 1,580 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 75,740 | 76.1% |
| RETURN_CONST | 11,820 | 11.9% |
| LOAD_FAST | 5,060 | 5.1% |
| PUSH_EXC_INFO | 2,880 | 2.9% |
| EXTENDED_ARG | 940 | 0.9% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 14,760 | 37.5% |
| TO_BOOL_STR | 13,920 | 35.3% |
| LOAD_CONST | 3,160 | 8.0% |
| CONTAINS_OP | 1,200 | 3.0% |
| GET_ITER | 940 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,860 | 47.9% |
| POP_JUMP_IF_FALSE | 11,380 | 28.9% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 4,400 | 11.2% |
| ENTER_EXECUTOR | 1,580 | 4.0% |
| FOR_ITER | 1,260 | 3.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 379,520 | 87.9% |
| GET_ITER | 48,980 | 11.3% |
| FOR_ITER | 1,400 | 0.3% |
| EXTENDED_ARG | 1,260 | 0.3% |
| SWAP | 420 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 329,820 | 76.4% |
| STORE_FAST | 50,380 | 11.7% |
| NOP | 47,300 | 11.0% |
| FOR_ITER | 1,400 | 0.3% |
| RETURN_CONST | 1,280 | 0.3% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,200 | 90.4% |
| LOAD_CONST | 320 | 4.7% |
| LOAD_FAST | 280 | 4.1% |
| LOAD_GLOBAL | 40 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,460 | 79.6% |
| POP_JUMP_IF_TRUE | 1,000 | 14.6% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 160 | 2.3% |
| LOAD_FAST | 80 | 1.2% |
| STORE_FAST | 80 | 1.2% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 328,620 | 83.0% |
| BINARY_OP_INPLACE_ADD_UNICODE | 47,280 | 11.9% |
| POP_TOP | 6,100 | 1.5% |
| STORE_FAST | 4,140 | 1.0% |
| LIST_APPEND | 2,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 379,520 | 95.9% |
| FOR_ITER_LIST | 9,000 | 2.3% |
| LOAD_FAST | 4,600 | 1.2% |
| FOR_ITER_TUPLE | 1,260 | 0.3% |
| ENTER_EXECUTOR | 660 | 0.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,780 | 56.4% |
| POP_TOP | 1,800 | 21.2% |
| EXTENDED_ARG | 1,080 | 12.7% |
| STORE_ATTR | 260 | 3.1% |
| POP_JUMP_IF_FALSE | 220 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,460 | 40.8% |
| LOAD_GLOBAL_MODULE | 3,000 | 35.4% |
| EXTENDED_ARG | 900 | 10.6% |
| LOAD_GLOBAL_BUILTIN | 760 | 9.0% |
| LOAD_GLOBAL | 220 | 2.6% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,280 | 83.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 680 | 10.7% |
| BUILD_TUPLE | 400 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,280 | 51.6% |
| JUMP_BACKWARD | 2,680 | 42.1% |
| INSTRUMENTED_JUMP_BACKWARD | 400 | 6.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,380 | 94.5% |
| LOAD_DEREF | 80 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,460 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 36,740 | 47.9% |
| LOAD_FAST | 28,200 | 36.8% |
| LOAD_ATTR | 4,780 | 6.2% |
| LOAD_GLOBAL | 2,160 | 2.8% |
| LOAD_FAST_LOAD_FAST | 1,540 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 34,840 | 45.5% |
| STORE_FAST | 7,920 | 10.3% |
| LOAD_ATTR | 4,780 | 6.2% |
| LOAD_FAST | 3,740 | 4.9% |
| PUSH_NULL | 3,340 | 4.4% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,905,080 | 99.5% |
| LOAD_CONST | 49,620 | 0.1% |
| EXTENDED_ARG | 18,860 | 0.0% |
| STORE_FAST | 17,240 | 0.0% |
| LOAD_ATTR_MODULE | 16,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 19,429,120 | 49.7% |
| BINARY_OP_SUBTRACT_INT | 19,426,780 | 49.7% |
| LOAD_CONST | 49,620 | 0.1% |
| BINARY_SLICE | 26,260 | 0.1% |
| LOAD_FAST | 23,840 | 0.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,240 | 37.8% |
| POP_JUMP_IF_FALSE | 11,940 | 31.7% |
| LOAD_ATTR_MODULE | 3,480 | 9.2% |
| LOAD_GLOBAL_BUILTIN | 3,000 | 8.0% |
| LOAD_GLOBAL_MODULE | 620 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 14,160 | 37.6% |
| RETURN_VALUE | 5,820 | 15.5% |
| LOAD_GLOBAL_MODULE | 5,780 | 15.3% |
| CALL_PY_EXACT_ARGS | 3,460 | 9.2% |
| LOAD_FAST | 3,120 | 8.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RESUME | 19,425,760 | 38.4% |
| LOAD_GLOBAL_MODULE | 9,899,420 | 19.6% |
| LOAD_GLOBAL | 9,733,500 | 19.2% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 9,729,360 | 19.2% |
| LOAD_FAST_LOAD_FAST | 376,300 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 38,905,080 | 76.9% |
| INSTRUMENTED_RETURN_VALUE | 9,717,760 | 19.2% |
| STORE_SUBSCR_DICT | 330,200 | 0.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 173,580 | 0.3% |
| CALL_PY_EXACT_ARGS | 172,760 | 0.3% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,520 | 90.5% |
| LOAD_FAST_AND_CLEAR | 160 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,520 | 90.5% |
| LOAD_FAST_AND_CLEAR | 160 | 9.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 200 | 90.9% |
| POP_JUMP_IF_FALSE | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 100 | 45.5% |
| TO_BOOL_LIST | 80 | 36.4% |
| TO_BOOL | 40 | 18.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 389,920 | 47.8% |
| STORE_FAST_STORE_FAST | 323,740 | 39.7% |
| LOAD_GLOBAL_MODULE | 21,900 | 2.7% |
| LOAD_FAST_LOAD_FAST | 13,300 | 1.6% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 12,560 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 376,300 | 46.2% |
| CONTAINS_OP | 322,880 | 39.6% |
| COMPARE_OP_STR | 27,240 | 3.3% |
| CALL | 13,440 | 1.6% |
| LOAD_FAST_LOAD_FAST | 13,300 | 1.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 9,716,800 | 99.4% |
| STORE_FAST | 16,280 | 0.2% |
| INSTRUMENTED_RESUME | 16,000 | 0.2% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 5,360 | 0.1% |
| NOP | 4,680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,733,500 | 99.6% |
| LOAD_ATTR_MODULE | 18,380 | 0.2% |
| LOAD_GLOBAL_MODULE | 10,240 | 0.1% |
| LOAD_FAST_LOAD_FAST | 5,120 | 0.1% |
| LOAD_ATTR | 2,160 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 80 | 50.0% |
| LOAD_FAST_LOAD_FAST | 40 | 25.0% |
| LOAD_CONST | 20 | 12.5% |
| LOAD_FAST | 20 | 12.5% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 6,520 | 93.9% |
| MAKE_CELL | 240 | 3.5% |
| CALL | 100 | 1.4% |
| CACHE | 80 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,620 | 95.4% |
| MAKE_CELL | 240 | 3.5% |
| RESUME | 80 | 1.2% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 19,720 | 93.9% |
| LOAD_FAST | 1,120 | 5.3% |
| LOAD_ATTR | 80 | 0.4% |
| RETURN_CONST | 80 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 14,760 | 70.3% |
| LOAD_CONST | 5,000 | 23.8% |
| DICT_UPDATE | 1,140 | 5.4% |
| CALL_FUNCTION_EX | 80 | 0.4% |
| BUILD_MAP | 20 | 0.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 337,220 | 45.4% |
| TO_BOOL_BOOL | 244,180 | 32.9% |
| TO_BOOL_STR | 66,420 | 8.9% |
| COMPARE_OP_STR | 25,680 | 3.5% |
| TO_BOOL_NONE | 23,080 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 389,920 | 52.5% |
| LOAD_FAST | 157,920 | 21.3% |
| RETURN_CONST | 66,660 | 9.0% |
| LOAD_GLOBAL_MODULE | 55,480 | 7.5% |
| ENTER_EXECUTOR | 20,840 | 2.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,300 | 77.2% |
| LOAD_ATTR_INSTANCE_VALUE | 620 | 20.8% |
| LOAD_ATTR_MODULE | 40 | 1.3% |
| RETURN_VALUE | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,100 | 70.5% |
| LOAD_CONST | 480 | 16.1% |
| ENTER_EXECUTOR | 120 | 4.0% |
| LOAD_GLOBAL_MODULE | 120 | 4.0% |
| RETURN_CONST | 80 | 2.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,500 | 80.5% |
| BINARY_SUBSCR_TUPLE_INT | 1,260 | 10.7% |
| LOAD_ATTR_INSTANCE_VALUE | 340 | 2.9% |
| LOAD_ATTR_WITH_HINT | 220 | 1.9% |
| CALL_BUILTIN_FAST | 120 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,320 | 36.6% |
| LOAD_FAST | 3,580 | 30.3% |
| NOP | 1,380 | 11.7% |
| JUMP_BACKWARD | 1,180 | 10.0% |
| BUILD_MAP | 320 | 2.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 76,840 | 51.0% |
| TO_BOOL | 48,680 | 32.3% |
| TO_BOOL_STR | 17,320 | 11.5% |
| TO_BOOL_LIST | 2,060 | 1.4% |
| COMPARE_OP_INT | 1,220 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,640 | 38.9% |
| LOAD_GLOBAL_BUILTIN | 51,880 | 34.4% |
| LOAD_GLOBAL_MODULE | 12,500 | 8.3% |
| RETURN_VALUE | 11,700 | 7.8% |
| STORE_FAST | 4,540 | 3.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 300 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 300 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 66,660 | 72.0% |
| ENTER_EXECUTOR | 11,820 | 12.8% |
| POP_TOP | 5,100 | 5.5% |
| STORE_ATTR_INSTANCE_VALUE | 2,300 | 2.5% |
| FOR_ITER_LIST | 2,200 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 64,360 | 69.5% |
| INTERPRETER_EXIT | 14,440 | 15.6% |
| POP_TOP | 6,900 | 7.5% |
| TO_BOOL_BOOL | 4,300 | 4.6% |
| EXIT_INIT_CHECK | 1,800 | 1.9% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 14,180 | 99.4% |
| SET_FUNCTION_ATTRIBUTE | 80 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,380 | 44.7% |
| LOAD_GLOBAL_MODULE | 6,380 | 44.7% |
| STORE_FAST | 1,380 | 9.7% |
| SET_FUNCTION_ATTRIBUTE | 80 | 0.6% |
| LOAD_GLOBAL | 40 | 0.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,840 | 59.1% |
| LOAD_FAST_LOAD_FAST | 5,120 | 25.5% |
| STORE_ATTR | 2,080 | 10.4% |
| LOAD_DEREF | 880 | 4.4% |
| LOAD_ATTR | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,680 | 23.4% |
| LOAD_CONST | 4,600 | 23.0% |
| STORE_ATTR_INSTANCE_VALUE | 3,300 | 16.5% |
| STORE_ATTR | 2,080 | 10.4% |
| LOAD_FAST_LOAD_FAST | 1,560 | 7.8% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,380 | 96.4% |
| LOAD_ATTR | 120 | 1.8% |
| LOAD_CONST | 120 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,340 | 95.8% |
| LOAD_CONST | 240 | 3.6% |
| LOAD_GLOBAL | 40 | 0.6% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 152,200 | 22.5% |
| LOAD_FAST | 108,960 | 16.1% |
| RETURN_VALUE | 70,120 | 10.4% |
| RETURN_CONST | 64,360 | 9.5% |
| CALL_BUILTIN_O | 51,160 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 275,720 | 40.8% |
| LOAD_GLOBAL_MODULE | 150,200 | 22.2% |
| NOP | 106,280 | 15.7% |
| ENTER_EXECUTOR | 42,860 | 6.3% |
| LOAD_GLOBAL_BUILTIN | 27,300 | 4.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,660 | 60.6% |
| FOR_ITER_TUPLE | 680 | 24.8% |
| CALL_LEN | 380 | 13.9% |
| FOR_ITER | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,060 | 75.2% |
| TO_BOOL_STR | 680 | 24.8% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 340,460 | 94.6% |
| UNPACK_SEQUENCE_TUPLE | 14,660 | 4.1% |
| BINARY_SLICE | 1,560 | 0.4% |
| UNPACK_EX | 1,280 | 0.4% |
| STORE_FAST_STORE_FAST | 1,200 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 323,740 | 90.0% |
| STORE_FAST | 13,500 | 3.8% |
| LOAD_GLOBAL_MODULE | 11,340 | 3.2% |
| LOAD_FAST | 7,780 | 2.2% |
| LOAD_GLOBAL_BUILTIN | 1,320 | 0.4% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 44.4% |
| BUILD_MAP | 100 | 27.8% |
| RETURN_VALUE | 80 | 22.2% |
| LOAD_CONST | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 180 | 50.0% |
| BUILD_MAP | 80 | 22.2% |
| INSTRUMENTED_RETURN_CONST | 80 | 22.2% |
| LOAD_GLOBAL | 20 | 5.6% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_UPDATE | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 20 | 100.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,580 | 48.5% |
| BUILD_LIST | 1,520 | 16.1% |
| LOAD_FAST_AND_CLEAR | 1,520 | 16.1% |
| ENTER_EXECUTOR | 480 | 5.1% |
| FOR_ITER | 400 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 4,460 | 47.2% |
| BUILD_LIST | 1,440 | 15.3% |
| STORE_FAST | 1,440 | 15.3% |
| FOR_ITER_LIST | 700 | 7.4% |
| FOR_ITER | 420 | 4.4% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,280 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 220 | 44.0% |
| FOR_ITER | 180 | 36.0% |
| LOAD_FAST | 40 | 8.0% |
| INSTRUMENTED_FOR_ITER | 40 | 8.0% |
| FOR_ITER_LIST | 20 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 240 | 48.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 220 | 44.0% |
| UNPACK_SEQUENCE_TUPLE | 40 | 8.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 30,860 | 94.6% |
| BINARY_OP | 640 | 2.0% |
| ENTER_EXECUTOR | 640 | 2.0% |
| BUILD_STRING | 320 | 1.0% |
| LOAD_CONST | 160 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 32,620 | 100.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,660 | 39.7% |
| INSTRUMENTED_RESUME | 960 | 23.0% |
| CACHE | 600 | 14.4% |
| COPY_FREE_VARS | 260 | 6.2% |
| CALL_PY_EXACT_ARGS | 240 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 1,640 | 39.2% |
| LOAD_FAST | 1,260 | 30.1% |
| INSTRUMENTED_RESUME | 520 | 12.4% |
| LOAD_FAST_LOAD_FAST | 160 | 3.8% |
| POP_TOP | 120 | 2.9% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RETURN_VALUE | 9,711,320 | 99.9% |
| LOAD_CONST | 4,460 | 0.0% |
| LOAD_FAST_LOAD_FAST | 1,520 | 0.0% |
| BINARY_OP | 120 | 0.0% |
| BINARY_OP_MULTIPLY_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RETURN_VALUE | 9,711,340 | 99.9% |
| STORE_FAST | 3,580 | 0.0% |
| BINARY_SLICE | 1,480 | 0.0% |
| LOAD_FAST | 840 | 0.0% |
| CALL_PY_EXACT_ARGS | 140 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,040 | 98.6% |
| LOAD_FAST_LOAD_FAST | 560 | 1.1% |
| BINARY_OP | 40 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 40 | 0.1% |
| CALL_METHOD_DESCRIPTOR_O | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 46,640 | 95.7% |
| STORE_FAST | 1,460 | 3.0% |
| CALL | 300 | 0.6% |
| LOAD_FAST | 280 | 0.6% |
| CALL_PY_EXACT_ARGS | 40 | 0.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 66.7% |
| BINARY_SUBSCR_TUPLE_INT | 120 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 33.3% |
| BINARY_OP_ADD_INT | 120 | 33.3% |
| CALL_BUILTIN_O | 120 | 33.3% |


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
| RETURN_VALUE | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 19,426,780 | 100.0% |
| LOAD_FAST | 2,960 | 0.0% |
| BINARY_OP | 1,400 | 0.0% |
| CALL_LEN | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 19,422,640 | 100.0% |
| STORE_FAST | 3,920 | 0.0% |
| LOAD_FAST | 2,580 | 0.0% |
| CALL | 1,300 | 0.0% |
| RETURN_VALUE | 440 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000 | 64.4% |
| BUILD_TUPLE | 2,000 | 21.5% |
| LOAD_FAST_LOAD_FAST | 800 | 8.6% |
| RETURN_VALUE | 340 | 3.6% |
| BINARY_SUBSCR | 140 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,520 | 27.0% |
| STORE_FAST | 2,380 | 25.5% |
| LOAD_CONST | 1,260 | 13.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,220 | 13.1% |
| CALL_METHOD_DESCRIPTOR_O | 680 | 7.3% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 640 | 37.2% |
| ENTER_EXECUTOR | 500 | 29.1% |
| LOAD_FAST_LOAD_FAST | 320 | 18.6% |
| LOAD_FAST | 260 | 15.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,720 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,560 | 48.5% |
| LOAD_CONST | 1,500 | 28.4% |
| LOAD_FAST_LOAD_FAST | 1,160 | 22.0% |
| BINARY_SUBSCR | 40 | 0.8% |
| BINARY_SUBSCR_LIST_INT | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,440 | 49.4% |
| RETURN_VALUE | 2,360 | 47.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 1.2% |
| BINARY_OP_ADD_UNICODE | 40 | 0.8% |
| LOAD_CONST | 20 | 0.4% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 880 | 46.8% |
| LOAD_FAST | 780 | 41.5% |
| CALL_LEN | 200 | 10.6% |
| BINARY_SUBSCR | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 880 | 46.8% |
| STORE_FAST | 560 | 29.8% |
| LOAD_GLOBAL_MODULE | 200 | 10.6% |
| BINARY_OP_INPLACE_ADD_UNICODE | 180 | 9.6% |
| PUSH_EXC_INFO | 40 | 2.1% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,420 | 98.7% |
| BINARY_SUBSCR | 60 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 1,260 | 28.1% |
| RETURN_VALUE | 1,160 | 25.9% |
| STORE_FAST | 600 | 13.4% |
| LOAD_GLOBAL_MODULE | 500 | 11.2% |
| CALL_BUILTIN_O | 360 | 8.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 520 | 28.9% |
| LOAD_FAST_LOAD_FAST | 360 | 20.0% |
| CALL | 320 | 17.8% |
| LOAD_GLOBAL_MODULE | 240 | 13.3% |
| LOAD_CONST | 160 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,580 | 87.8% |
| COPY_FREE_VARS | 220 | 12.2% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 820 | 37.3% |
| BUILD_TUPLE | 560 | 25.5% |
| LOAD_FAST | 340 | 15.5% |
| PUSH_NULL | 320 | 14.5% |
| CALL | 80 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,000 | 90.9% |
| POP_TOP | 200 | 9.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,080 | 97.1% |
| LOAD_ATTR_INSTANCE_VALUE | 440 | 0.8% |
| CALL | 300 | 0.5% |
| CALL_LEN | 260 | 0.5% |
| LOAD_ATTR_WITH_HINT | 200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 51,360 | 94.0% |
| PUSH_EXC_INFO | 1,180 | 2.2% |
| LOAD_FAST | 840 | 1.5% |
| RETURN_VALUE | 500 | 0.9% |
| LOAD_CONST | 260 | 0.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,840 | 62.9% |
| LOAD_FAST | 3,560 | 17.5% |
| CALL | 1,800 | 8.8% |
| LOAD_FAST_LOAD_FAST | 1,580 | 7.7% |
| LOAD_ATTR_INSTANCE_VALUE | 440 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 8,260 | 40.5% |
| TO_BOOL_STR | 4,340 | 21.3% |
| RETURN_VALUE | 1,840 | 9.0% |
| POP_TOP | 1,460 | 7.2% |
| LOAD_CONST | 1,420 | 7.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 173,580 | 99.8% |
| CALL | 180 | 0.1% |
| LOAD_CONST | 140 | 0.1% |
| CALL_TUPLE_1 | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 152,200 | 87.5% |
| COPY | 12,320 | 7.1% |
| RETURN_VALUE | 4,840 | 2.8% |
| POP_TOP | 3,500 | 2.0% |
| INSTRUMENTED_RETURN_VALUE | 560 | 0.3% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 51,140 | 73.7% |
| RETURN_GENERATOR | 12,680 | 18.3% |
| LOAD_FAST | 1,600 | 2.3% |
| CALL_BUILTIN_FAST | 1,400 | 2.0% |
| LOAD_GLOBAL_MODULE | 900 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 51,160 | 73.8% |
| TO_BOOL_BOOL | 14,080 | 20.3% |
| POP_TOP | 3,660 | 5.3% |
| BUILD_TUPLE | 380 | 0.5% |
| TO_BOOL | 60 | 0.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 97,980 | 72.1% |
| LOAD_ATTR | 34,840 | 25.6% |
| LOAD_GLOBAL_MODULE | 2,300 | 1.7% |
| CALL | 380 | 0.3% |
| BUILD_TUPLE | 340 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 96,780 | 71.2% |
| RETURN_VALUE | 38,820 | 28.6% |
| TO_BOOL | 240 | 0.2% |
| LOAD_FAST | 40 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,660 | 80.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,200 | 12.6% |
| POP_JUMP_IF_TRUE | 440 | 4.6% |
| CALL | 140 | 1.5% |
| LOAD_GLOBAL_MODULE | 80 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,840 | 29.8% |
| LOAD_FAST | 1,720 | 18.1% |
| BINARY_OP | 1,580 | 16.6% |
| RETURN_VALUE | 1,140 | 12.0% |
| BINARY_OP_SUBTRACT_INT | 440 | 4.6% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,240 | 40.8% |
| LOAD_FAST | 1,200 | 39.5% |
| BUILD_TUPLE | 240 | 7.9% |
| LOAD_CONST | 180 | 5.9% |
| CALL | 120 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,540 | 50.7% |
| RETURN_CONST | 880 | 28.9% |
| NOP | 320 | 10.5% |
| EXTENDED_ARG | 180 | 5.9% |
| INSTRUMENTED_RETURN_CONST | 60 | 2.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,500 | 51.5% |
| LOAD_FAST | 1,780 | 20.4% |
| BINARY_SUBSCR_DICT | 1,220 | 14.0% |
| LOAD_GLOBAL_MODULE | 720 | 8.2% |
| CALL | 220 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 3,800 | 43.5% |
| STORE_FAST | 2,740 | 31.4% |
| RETURN_VALUE | 1,240 | 14.2% |
| LIST_APPEND | 680 | 7.8% |
| POP_TOP | 240 | 2.7% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 60.2% |
| LOAD_FAST_LOAD_FAST | 680 | 33.0% |
| CALL | 100 | 4.9% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,080 | 52.4% |
| CONTAINS_OP | 700 | 34.0% |
| STORE_FAST | 160 | 7.8% |
| POP_TOP | 120 | 5.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,640 | 92.1% |
| CALL | 140 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 960 | 53.9% |
| GET_ITER | 820 | 46.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,160 | 87.3% |
| BINARY_SUBSCR_DICT | 680 | 4.5% |
| RETURN_VALUE | 440 | 2.9% |
| STORE_FAST | 320 | 2.1% |
| CALL | 140 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 13,120 | 87.0% |
| POP_TOP | 1,400 | 9.3% |
| RETURN_VALUE | 380 | 2.5% |
| LOAD_CONST | 80 | 0.5% |
| STORE_FAST | 40 | 0.3% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 19,422,640 | 98.9% |
| LOAD_FAST | 172,760 | 0.9% |
| GET_ITER | 12,840 | 0.1% |
| LOAD_FAST_LOAD_FAST | 10,020 | 0.1% |
| RETURN_VALUE | 8,600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RESUME | 19,436,580 | 98.9% |
| RESUME_CHECK | 188,420 | 1.0% |
| COPY_FREE_VARS | 13,720 | 0.1% |
| MAKE_CELL | 6,520 | 0.0% |
| RESUME | 240 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,500 | 72.8% |
| LOAD_CONST | 1,360 | 22.0% |
| CALL | 180 | 2.9% |
| LOAD_FAST_LOAD_FAST | 60 | 1.0% |
| PUSH_NULL | 40 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,940 | 96.1% |
| COPY_FREE_VARS | 220 | 3.6% |
| RESUME | 20 | 0.3% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 66.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20 | 33.3% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 30.8% |
| LOAD_CONST | 200 | 25.6% |
| POP_JUMP_IF_TRUE | 200 | 25.6% |
| CALL | 80 | 10.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 660 | 84.6% |
| RETURN_VALUE | 60 | 7.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 5.1% |
| CALL | 20 | 2.6% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,060 | 99.0% |
| LOAD_GLOBAL_MODULE | 20 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,040 | 98.1% |
| PUSH_NULL | 20 | 1.0% |
| LOAD_FAST | 20 | 1.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 1,120 | 93.3% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 5.0% |
| COMPARE_OP | 20 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,140 | 95.0% |
| POP_JUMP_IF_FALSE | 60 | 5.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 19,429,120 | 100.0% |
| LOAD_ATTR_SLOT | 1,120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 560 | 0.0% |
| LOAD_FAST | 380 | 0.0% |
| COMPARE_OP | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 19,422,780 | 100.0% |
| POP_JUMP_IF_FALSE | 7,740 | 0.0% |
| POP_JUMP_IF_TRUE | 1,220 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |
| STORE_FAST | 20 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 27,240 | 76.1% |
| LOAD_CONST | 5,220 | 14.6% |
| BINARY_OP | 1,560 | 4.4% |
| LOAD_ATTR_INSTANCE_VALUE | 780 | 2.2% |
| COMPARE_OP | 280 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 25,680 | 71.8% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 9,300 | 26.0% |
| EXTENDED_ARG | 520 | 1.5% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 280 | 0.8% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,880 | 49.1% |
| JUMP_BACKWARD | 9,000 | 34.3% |
| GET_ITER | 2,740 | 10.4% |
| SWAP | 700 | 2.7% |
| EXTENDED_ARG | 560 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 19,840 | 75.6% |
| RETURN_CONST | 2,200 | 8.4% |
| STORE_FAST_LOAD_FAST | 1,660 | 6.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,100 | 4.2% |
| LOAD_FAST | 440 | 1.7% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 260 | 100.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,260 | 66.3% |
| SWAP | 320 | 16.8% |
| GET_ITER | 300 | 15.8% |
| FOR_ITER | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 700 | 36.8% |
| STORE_FAST_LOAD_FAST | 680 | 35.8% |
| SWAP | 320 | 16.8% |
| JUMP_BACKWARD | 200 | 10.5% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |
| LOAD_FAST_LOAD_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 50.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 40 | 33.3% |
| CALL | 20 | 16.7% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,900 | 77.1% |
| LOAD_ATTR | 2,780 | 8.6% |
| LOAD_FAST_LOAD_FAST | 2,760 | 8.6% |
| LOAD_DEREF | 1,160 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 680 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,120 | 31.4% |
| GET_ITER | 1,740 | 5.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,600 | 5.0% |
| STORE_FAST | 1,480 | 4.6% |
| TO_BOOL_NONE | 1,280 | 4.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 152,420 | 85.0% |
| LOAD_DEREF | 14,160 | 7.9% |
| LOAD_GLOBAL_MODULE | 4,600 | 2.6% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 2,760 | 1.5% |
| LOAD_ATTR | 1,480 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 164,800 | 91.9% |
| LOAD_CONST | 6,500 | 3.6% |
| LOAD_GLOBAL_MODULE | 3,760 | 2.1% |
| LOAD_FAST_LOAD_FAST | 1,640 | 0.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,640 | 0.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,720 | 49.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,600 | 29.1% |
| LOAD_ATTR | 780 | 14.2% |
| BINARY_SUBSCR_TUPLE_INT | 140 | 2.5% |
| BINARY_SUBSCR | 120 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,120 | 38.5% |
| LOAD_FAST | 1,460 | 26.5% |
| LOAD_CONST | 1,160 | 21.1% |
| CALL | 360 | 6.5% |
| LOAD_FAST_LOAD_FAST | 360 | 6.5% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 312,480 | 79.9% |
| LOAD_ATTR_MODULE | 44,920 | 11.5% |
| LOAD_GLOBAL | 18,380 | 4.7% |
| LOAD_FAST | 12,840 | 3.3% |
| LOAD_ATTR | 2,320 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 222,240 | 56.8% |
| LOAD_FAST | 67,620 | 17.3% |
| LOAD_ATTR_MODULE | 44,920 | 11.5% |
| LOAD_CONST | 16,100 | 4.1% |
| LOAD_GLOBAL_MODULE | 7,340 | 1.9% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,060 | 90.5% |
| LOAD_ATTR | 260 | 7.7% |
| LOAD_FAST_LOAD_FAST | 60 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,760 | 81.7% |
| LOAD_CONST | 180 | 5.3% |
| TO_BOOL_LIST | 160 | 4.7% |
| LOAD_ATTR | 100 | 3.0% |
| TO_BOOL | 80 | 2.4% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 84.4% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 12.5% |
| LOAD_ATTR | 20 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 640 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,760 | 93.0% |
| LOAD_FAST_LOAD_FAST | 2,260 | 3.8% |
| LOAD_ATTR | 1,420 | 2.4% |
| LOAD_ATTR_MODULE | 380 | 0.6% |
| RETURN_VALUE | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 51,140 | 86.9% |
| RETURN_VALUE | 2,540 | 4.3% |
| LOAD_FAST | 2,020 | 3.4% |
| COMPARE_OP_FLOAT | 1,120 | 1.9% |
| COMPARE_OP_INT | 1,120 | 1.9% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 58.2% |
| LOAD_ATTR | 700 | 21.2% |
| LOAD_ATTR_INSTANCE_VALUE | 640 | 19.4% |
| COPY | 40 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 580 | 17.6% |
| LOAD_GLOBAL_MODULE | 400 | 12.1% |
| LOAD_ATTR_METHOD_NO_DICT | 360 | 10.9% |
| CALL_PY_EXACT_ARGS | 280 | 8.5% |
| RETURN_VALUE | 220 | 6.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 117,920 | 35.3% |
| LOAD_FAST | 99,740 | 29.8% |
| POP_JUMP_IF_TRUE | 51,880 | 15.5% |
| STORE_FAST | 27,300 | 8.2% |
| POP_JUMP_IF_FALSE | 14,760 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 171,220 | 51.2% |
| CALL_ISINSTANCE | 97,980 | 29.3% |
| LOAD_GLOBAL_MODULE | 48,420 | 14.5% |
| CHECK_EXC_MATCH | 5,200 | 1.6% |
| LOAD_FAST_LOAD_FAST | 3,360 | 1.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RETURN_VALUE | 9,711,320 | 94.2% |
| STORE_FAST | 150,200 | 1.5% |
| RESUME_CHECK | 121,700 | 1.2% |
| LOAD_FAST | 69,580 | 0.7% |
| NOP | 55,580 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,899,420 | 96.0% |
| LOAD_ATTR_MODULE | 312,480 | 3.0% |
| LOAD_ATTR | 36,740 | 0.4% |
| LOAD_FAST_LOAD_FAST | 21,900 | 0.2% |
| CONTAINS_OP | 6,500 | 0.1% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,920 | 97.3% |
| LOAD_SUPER_ATTR | 80 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,560 | 85.3% |
| LOAD_CONST | 220 | 7.3% |
| LOAD_FAST | 220 | 7.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 188,420 | 57.8% |
| CALL | 54,440 | 16.7% |
| CACHE | 38,580 | 11.8% |
| POP_TOP | 13,060 | 4.0% |
| RESUME_CHECK | 6,720 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 121,700 | 37.3% |
| LOAD_GLOBAL_BUILTIN | 117,920 | 36.2% |
| POP_TOP | 31,940 | 9.8% |
| LOAD_FAST | 30,340 | 9.3% |
| NOP | 8,960 | 2.7% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,660 | 58.9% |
| LOAD_FAST_LOAD_FAST | 3,820 | 19.3% |
| STORE_ATTR | 3,300 | 16.7% |
| LOAD_DEREF | 880 | 4.4% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,140 | 26.0% |
| LOAD_FAST | 4,700 | 23.8% |
| RETURN_CONST | 2,300 | 11.6% |
| LOAD_FAST_LOAD_FAST | 2,180 | 11.0% |
| BUILD_LIST | 2,100 | 10.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,320 | 56.3% |
| LOAD_FAST_LOAD_FAST | 1,340 | 32.5% |
| STORE_ATTR | 460 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,800 | 43.7% |
| LOAD_FAST | 1,140 | 27.7% |
| LOAD_FAST_LOAD_FAST | 820 | 19.9% |
| LOAD_GLOBAL | 360 | 8.7% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 69.2% |
| STORE_ATTR | 120 | 23.1% |
| SWAP | 40 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 46.2% |
| LOAD_GLOBAL_BUILTIN | 200 | 38.5% |
| RETURN_CONST | 60 | 11.5% |
| LOAD_GLOBAL | 20 | 3.8% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 330,200 | 97.5% |
| RETURN_VALUE | 3,780 | 1.1% |
| LOAD_FAST_LOAD_FAST | 3,080 | 0.9% |
| CALL | 1,400 | 0.4% |
| STORE_SUBSCR | 220 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 328,620 | 97.0% |
| LOAD_GLOBAL_MODULE | 8,480 | 2.5% |
| LOAD_FAST | 660 | 0.2% |
| LOAD_GLOBAL | 540 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 240 | 0.1% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 440 | 75.9% |
| LOAD_FAST | 140 | 24.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 320 | 55.2% |
| RETURN_CONST | 160 | 27.6% |
| ENTER_EXECUTOR | 100 | 17.2% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,240 | 47.3% |
| LOAD_FAST | 1,120 | 42.7% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 4.6% |
| TO_BOOL | 80 | 3.1% |
| COPY | 40 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,300 | 87.8% |
| POP_JUMP_IF_TRUE | 160 | 6.1% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 140 | 5.3% |
| TO_BOOL_NONE | 20 | 0.8% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 109,780 | 31.7% |
| CALL_ISINSTANCE | 96,780 | 27.9% |
| LOAD_FAST | 54,340 | 15.7% |
| RETURN_VALUE | 53,280 | 15.4% |
| CALL_BUILTIN_O | 14,080 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 244,180 | 70.5% |
| POP_JUMP_IF_TRUE | 76,840 | 22.2% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 18,040 | 5.2% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 7,100 | 2.1% |
| EXTENDED_ARG | 140 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,900 | 51.6% |
| LOAD_FAST | 1,500 | 40.8% |
| COPY | 240 | 6.5% |
| CALL_BUILTIN_O | 20 | 0.5% |
| CALL_LEN | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,660 | 72.3% |
| POP_JUMP_IF_TRUE | 840 | 22.8% |
| UNARY_NOT | 180 | 4.9% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,760 | 60.7% |
| TO_BOOL | 340 | 11.7% |
| LOAD_ATTR_INSTANCE_VALUE | 320 | 11.0% |
| COPY | 200 | 6.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 160 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,060 | 71.0% |
| POP_JUMP_IF_FALSE | 620 | 21.4% |
| UNARY_NOT | 100 | 3.4% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 60 | 2.1% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 60 | 2.1% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,800 | 91.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,280 | 5.1% |
| TO_BOOL | 480 | 1.9% |
| COPY | 240 | 1.0% |
| LOAD_ATTR_WITH_HINT | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,080 | 92.8% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 960 | 3.9% |
| POP_JUMP_IF_TRUE | 440 | 1.8% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 360 | 1.4% |
| TO_BOOL_ALWAYS_TRUE | 20 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 83,720 | 77.8% |
| COPY | 17,900 | 16.6% |
| CALL_BUILTIN_FAST | 4,340 | 4.0% |
| STORE_FAST_LOAD_FAST | 680 | 0.6% |
| LOAD_ATTR_MODULE | 440 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 66,420 | 61.7% |
| POP_JUMP_IF_TRUE | 17,320 | 16.1% |
| EXTENDED_ARG | 13,920 | 12.9% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 8,760 | 8.1% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 1,240 | 1.2% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 13,120 | 88.1% |
| LOAD_FAST | 1,400 | 9.4% |
| FOR_ITER_LIST | 280 | 1.9% |
| RETURN_VALUE | 60 | 0.4% |
| UNPACK_SEQUENCE | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 14,660 | 98.4% |
| STORE_FAST | 240 | 1.6% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 329,820 | 96.6% |
| RETURN_VALUE | 9,100 | 2.7% |
| FOR_ITER_LIST | 1,100 | 0.3% |
| CALL_BUILTIN_FAST | 540 | 0.2% |
| INSTRUMENTED_RETURN_VALUE | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 340,460 | 99.7% |
| STORE_FAST | 980 | 0.3% |


</details>

### INSTRUMENTED_RESUME

<details>
<summary> Successors and predecessors for INSTRUMENTED_RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 19,436,580 | 100.0% |
| CALL | 4,500 | 0.0% |
| RESUME_CHECK | 1,060 | 0.0% |
| INSTRUMENTED_RESUME | 660 | 0.0% |
| RESUME | 520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,425,760 | 99.9% |
| LOAD_GLOBAL | 16,000 | 0.1% |
| RESUME | 960 | 0.0% |
| INSTRUMENTED_RESUME | 660 | 0.0% |
| LOAD_CONST | 240 | 0.0% |


</details>

### INSTRUMENTED_RETURN_VALUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,717,760 | 50.0% |
| BINARY_OP_ADD_INT | 9,711,340 | 50.0% |
| CALL | 1,280 | 0.0% |
| INSTRUMENTED_RETURN_VALUE | 1,280 | 0.0% |
| BINARY_SLICE | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 9,711,320 | 50.0% |
| LOAD_GLOBAL_MODULE | 9,711,320 | 50.0% |
| STORE_FAST | 7,040 | 0.0% |
| TO_BOOL_BOOL | 1,560 | 0.0% |
| INSTRUMENTED_RETURN_VALUE | 1,280 | 0.0% |


</details>

### INSTRUMENTED_RETURN_CONST

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 6,320 | 87.8% |
| POP_TOP | 420 | 5.8% |
| INSTRUMENTED_FOR_ITER | 320 | 4.4% |
| STORE_GLOBAL | 80 | 1.1% |
| CALL_LIST_APPEND | 60 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,400 | 88.9% |
| TO_BOOL_BOOL | 440 | 6.1% |
| POP_TOP | 240 | 3.3% |
| TO_BOOL | 120 | 1.7% |


</details>

### INSTRUMENTED_FOR_ITER

<details>
<summary> Successors and predecessors for INSTRUMENTED_FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_JUMP_BACKWARD | 5,920 | 52.5% |
| GET_ITER | 5,280 | 46.8% |
| SWAP | 80 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000 | 53.2% |
| NOP | 4,080 | 36.2% |
| LOAD_CONST | 320 | 2.8% |
| INSTRUMENTED_RETURN_CONST | 320 | 2.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 280 | 2.5% |


</details>

### INSTRUMENTED_JUMP_FORWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 320 | 80.0% |
| STORE_FAST | 80 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320 | 80.0% |
| LOAD_GLOBAL | 80 | 20.0% |


</details>

### INSTRUMENTED_JUMP_BACKWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 4,080 | 40.8% |
| STORE_FAST | 4,080 | 40.8% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 1,280 | 12.8% |
| LIST_APPEND | 400 | 4.0% |
| POP_TOP | 80 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_FOR_ITER | 5,920 | 59.2% |
| LOAD_FAST | 4,080 | 40.8% |


</details>

### INSTRUMENTED_POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,100 | 52.8% |
| TO_BOOL | 4,280 | 31.8% |
| TO_BOOL_STR | 1,240 | 9.2% |
| TO_BOOL_NONE | 360 | 2.7% |
| COMPARE_OP_STR | 280 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,680 | 42.3% |
| LOAD_GLOBAL | 5,360 | 39.9% |
| INSTRUMENTED_JUMP_BACKWARD | 1,280 | 9.5% |
| INSTRUMENTED_RETURN_VALUE | 640 | 4.8% |
| POP_TOP | 240 | 1.8% |


</details>

### INSTRUMENTED_POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 19,422,780 | 99.8% |
| TO_BOOL_BOOL | 18,040 | 0.1% |
| COMPARE_OP_STR | 9,300 | 0.0% |
| TO_BOOL_STR | 8,760 | 0.0% |
| EXTENDED_ARG | 4,400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,729,360 | 50.0% |
| LOAD_GLOBAL | 9,716,800 | 49.9% |
| LOAD_FAST_LOAD_FAST | 12,560 | 0.1% |
| INSTRUMENTED_RETURN_CONST | 6,320 | 0.0% |
| POP_TOP | 320 | 0.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 100.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 360 | 90.0% |
| LOAD_ATTR | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 100.0% |


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
|     deferred | 16,160 | 0.1% |
|          hit | 29,249,900 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 360 | 29.5% |
| Failure | 860 | 70.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 260 | 30.2% |
| floor divide | 180 | 20.9% |
| multiply different types | 120 | 14.0% |
| add different types | 100 | 11.6% |
| remainder | 80 | 9.3% |
| and different types | 40 | 4.7% |
| subtract other | 40 | 4.7% |
| and int | 20 | 2.3% |
| and other | 20 | 2.3% |


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
|     deferred | 3,120 | 11.8% |
|          hit | 22,280 | 84.3% |
|         miss | 400 | 1.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 43.8% |
| Failure | 360 | 56.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 240 | 66.7% |
| out of range | 100 | 27.8% |
| list slice | 20 | 5.6% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 261,780 | 1.3% |
|          hit | 20,154,720 | 98.7% |
|         miss | 540 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,960 | 60.4% |
| Failure | 3,905 | 39.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs | 1,905 | 48.8% |
| code complex parameters | 620 | 15.9% |
| cfunc varargs keywords | 520 | 13.3% |
| meth descr method fastcall keywords | 360 | 9.2% |
| class no vectorcall | 180 | 4.6% |
| cfunc varargs | 120 | 3.1% |
| cfunc noargs | 120 | 3.1% |
| init not python | 60 | 1.5% |
| wrong number arguments | 20 | 0.5% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,020 | 0.0% |
|          hit | 19,468,720 | 100.0% |
|         miss | 40 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 500 | 69.4% |
| Failure | 220 | 30.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 140 | 63.6% |
| tuple | 60 | 27.3% |
| big int | 20 | 9.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 429,960 | 93.4% |
|          hit | 28,400 | 6.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 21.3% |
| Failure | 1,400 | 78.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 620 | 44.3% |
| map | 480 | 34.3% |
| set | 180 | 12.9% |
| dict keys | 100 | 7.1% |
| dict values | 20 | 1.4% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 65,300 | 8.7% |
|          hit | 661,840 | 88.1% |
|         miss | 12,640 | 1.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,440 | 74.4% |
| Failure | 2,900 | 25.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 1,000 | 34.5% |
| module attr not found | 940 | 32.4% |
| method | 480 | 16.6% |
| has managed dict | 240 | 8.3% |
| non object slot | 100 | 3.4% |
| class method obj | 60 | 2.1% |
| metaclass attribute | 40 | 1.4% |
| class attr simple | 40 | 1.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,766,640 | 47.8% |
|        deopt | 300 | 0.0% |
|          hit | 10,640,780 | 52.1% |
|         miss | 2,220 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,720 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 80 | 2.5% |
|          hit | 3,000 | 94.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 14,080 | 31.7% |
|          hit | 24,420 | 54.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,880 | 65.1% |
| Failure | 2,080 | 34.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 1,700 | 81.7% |
| no dict | 200 | 9.6% |
| not in keys | 100 | 4.8% |
| not managed dict | 40 | 1.9% |
| class attr simple | 40 | 1.9% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 760 | 0.2% |
|          hit | 339,300 | 99.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 59,960 | 10.9% |
|          hit | 484,480 | 87.8% |
|         miss | 3,540 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,320 | 80.6% |
| Failure | 800 | 19.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 340 | 42.5% |
| other | 260 | 32.5% |
| dict | 80 | 10.0% |
| bytes | 60 | 7.5% |
| set | 60 | 7.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.1% |
|          hit | 356,340 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 152,010,900 | 61.9% |
| Not specialized | 11,656,825 | 4.8% |
| Specialized hits | 81,698,760 | 33.3% |
| Specialized misses | 27,160 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_GLOBAL | 9,766,640 | 91.9% |
| FOR_ITER | 429,960 | 4.0% |
| CALL | 261,780 | 2.5% |
| LOAD_ATTR | 65,300 | 0.6% |
| TO_BOOL | 59,960 | 0.6% |
| BINARY_OP | 16,160 | 0.2% |
| STORE_ATTR | 14,080 | 0.1% |
| COMPARE_OP | 5,020 | 0.0% |
| BINARY_SUBSCR | 3,120 | 0.0% |
| STORE_SUBSCR | 760 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 12,580 | 36.0% |
| RESUME | 7,780 | 22.3% |
| RESUME_CHECK | 7,780 | 22.3% |
| LOAD_GLOBAL_BUILTIN | 2,220 | 6.4% |
| TO_BOOL_NONE | 1,820 | 5.2% |
| TO_BOOL_ALWAYS_TRUE | 1,160 | 3.3% |
| TO_BOOL_STR | 560 | 1.6% |
| BINARY_SUBSCR_LIST_INT | 360 | 1.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 260 | 0.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 100 | 0.3% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 55,400 | 0.3% |
| Calls to Python functions inlined | 19,721,540 | 99.7% |
| Calls via PyEval_EvalFrame (total) | 55,400 | 0.3% |
| Calls via PyEval_EvalFrame (vector) | 10,140 | 0.1% |
| Calls via PyEval_EvalFrame (generator) | 45,260 | 0.2% |
| Calls via PyEval_EvalFrame (legacy) | 20 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 10,120 | 0.1% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 2,260 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 520 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,900 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 19,430,100 | 98.2% |
| Frames pushed | 19,668,600 | 99.5% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 741,160 | 1.8% |
| Frees to freelist | 738,200 |  |
| Allocations | 40,946,000 | 98.2% |
| Allocations to 512 bytes | 40,934,060 | 98.2% |
| Allocations to 4 kbytes | 6,900 | 0.0% |
| Allocations over 4 kbytes | 5,040 | 0.0% |
| Frees | 40,923,570 |  |
| New values | 1,420 |  |
| Interpreter increfs | 44,028,580 | 15.7% |
| Interpreter decrefs | 64,367,060 | 24.5% |
| Increfs | 235,599,131 | 84.3% |
| Decrefs | 198,439,838 | 75.5% |
| Materialize dict (on request) | 240 | 16.9% |
| Materialize dict (new key) | 220 | 15.5% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 60 | 4.2% |
| Method cache hits | 19,529,341 |  |
| Method cache misses | 10,639 |  |
| Method cache collisions | 9,423 |  |
| Method cache dunder hits | 176,346 |  |
| Method cache dunder misses | 1,074 |  |


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
| Optimization attempts | 860 |  |
| Traces created | 660 | 76.7% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 200 | 23.3% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 99,580 |  |
| Uops executed | 2,488,700 | 24.99 |

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
| <= 32 | 400 | 60.6% |
| <= 64 | 160 | 24.2% |
| <= 128 | 100 | 15.2% |


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
| <= 32 | 440 | 66.7% |
| <= 64 | 120 | 18.2% |
| <= 128 | 100 | 15.2% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 660 | 0.7% |
| <= 4 | 0 | 0.0% |
| <= 8 | 17,300 | 17.4% |
| <= 16 | 17,540 | 17.6% |
| <= 32 | 20,820 | 20.9% |
| <= 64 | 41,920 | 42.1% |
| <= 128 | 1,260 | 1.3% |
| <= 256 | 40 | 0.0% |
| <= 512 | 40 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 607,140 | 24.4% | 24.4% |  |
| LOAD_FAST | 492,460 | 19.8% | 44.2% |  |
| STORE_FAST | 167,120 | 6.7% | 50.9% |  |
| _POP_JUMP_IF_TRUE | 141,800 | 5.7% | 56.6% |  |
| _GUARD_TYPE_VERSION | 100,400 | 4.0% | 60.6% |  |
| _EXIT_TRACE | 96,000 | 3.9% | 64.5% |  |
| _POP_JUMP_IF_FALSE | 82,900 | 3.3% | 67.8% |  |
| TO_BOOL_STR | 82,280 | 3.3% | 71.1% |  |
| COMPARE_OP_STR | 78,920 | 3.2% | 74.3% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 76,380 | 3.1% | 77.4% |  |
| _ITER_CHECK_LIST | 57,360 | 2.3% | 79.7% | 1.2% |
| _IS_ITER_EXHAUSTED_LIST | 56,700 | 2.3% | 81.9% |  |
| _GUARD_GLOBALS_VERSION | 51,680 | 2.1% | 84.0% |  |
| _LOAD_GLOBAL_MODULE | 44,600 | 1.8% | 85.8% |  |
| _ITER_NEXT_LIST | 43,560 | 1.8% | 87.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 39,420 | 1.6% | 89.2% |  |
| UNPACK_SEQUENCE_TUPLE | 39,160 | 1.6% | 90.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 20,360 | 0.8% | 91.5% |  |
| _GUARD_KEYS_VERSION | 20,360 | 0.8% | 92.4% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 19,680 | 0.8% | 93.2% |  |
| LOAD_DEREF | 16,620 | 0.7% | 93.8% |  |
| POP_TOP | 14,340 | 0.6% | 94.4% |  |
| _CHECK_PEP_523 | 8,940 | 0.4% | 94.8% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 8,940 | 0.4% | 95.1% |  |
| _CHECK_STACK_SPACE | 8,940 | 0.4% | 95.5% |  |
| _INIT_CALL_PY_EXACT_ARGS | 8,940 | 0.4% | 95.8% |  |
| _PUSH_FRAME | 8,940 | 0.4% | 96.2% |  |
| _SAVE_RETURN_OFFSET | 8,940 | 0.4% | 96.6% |  |
| RESUME_CHECK | 8,820 | 0.4% | 96.9% |  |
| LOAD_CONST | 7,700 | 0.3% | 97.2% |  |
| PUSH_NULL | 7,240 | 0.3% | 97.5% |  |
| _GUARD_BUILTINS_VERSION | 7,080 | 0.3% | 97.8% | 0.6% |
| _LOAD_GLOBAL_BUILTINS | 7,040 | 0.3% | 98.1% |  |
| CALL_BUILTIN_CLASS | 5,760 | 0.2% | 98.3% |  |
| _POP_FRAME | 4,500 | 0.2% | 98.5% |  |
| _JUMP_TO_TOP | 3,580 | 0.1% | 98.6% |  |
| LIST_APPEND | 2,880 | 0.1% | 98.7% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 2,660 | 0.1% | 98.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 2,660 | 0.1% | 99.0% |  |
| _LOAD_ATTR | 2,420 | 0.1% | 99.1% |  |
| CONTAINS_OP | 1,680 | 0.1% | 99.1% |  |
| _BINARY_SUBSCR | 1,680 | 0.1% | 99.2% |  |
| IS_OP | 1,660 | 0.1% | 99.3% |  |
| _GUARD_BOTH_INT | 1,440 | 0.1% | 99.3% |  |
| _BINARY_OP_ADD_INT | 1,380 | 0.1% | 99.4% |  |
| _BINARY_OP | 1,200 | 0.0% | 99.4% |  |
| _GUARD_DORV_VALUES | 1,000 | 0.0% | 99.5% |  |
| _STORE_ATTR_INSTANCE_VALUE | 1,000 | 0.0% | 99.5% |  |
| _IS_NONE | 920 | 0.0% | 99.5% |  |
| _ITER_CHECK_RANGE | 760 | 0.0% | 99.6% |  |
| _IS_ITER_EXHAUSTED_RANGE | 760 | 0.0% | 99.6% |  |
| TO_BOOL_BOOL | 740 | 0.0% | 99.6% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 680 | 0.0% | 99.7% |  |
| CALL_ISINSTANCE | 620 | 0.0% | 99.7% |  |
| _CHECK_ATTR_MODULE | 620 | 0.0% | 99.7% |  |
| _LOAD_ATTR_MODULE | 620 | 0.0% | 99.7% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 620 | 0.0% | 99.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 620 | 0.0% | 99.8% |  |
| BINARY_SUBSCR_STR_INT | 600 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 600 | 0.0% | 99.8% |  |
| COMPARE_OP_INT | 600 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 560 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 540 | 0.0% | 99.9% |  |
| _ITER_NEXT_RANGE | 500 | 0.0% | 99.9% |  |
| _ITER_CHECK_TUPLE | 360 | 0.0% | 99.9% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 360 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_DICT | 260 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 240 | 0.0% | 100.0% |  |
| CALL_LEN | 120 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 120 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 80 | 0.0% | 100.0% |  |
| UNARY_NOT | 80 | 0.0% | 100.0% |  |
| BUILD_STRING | 80 | 0.0% | 100.0% |  |
| COPY | 80 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 80 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 40 | 0.0% | 100.0% |  |
| _TO_BOOL | 40 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 20 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 380 |
| FOR_ITER | 200 |
| YIELD_VALUE | 60 |
| CALL_KW | 40 |


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
