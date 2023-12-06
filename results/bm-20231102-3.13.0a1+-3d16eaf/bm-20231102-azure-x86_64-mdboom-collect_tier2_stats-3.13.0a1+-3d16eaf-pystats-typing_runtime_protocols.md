
# Pystats results

- benchmark: typing_runtime_protocols
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_GLOBAL_MODULE | 55,185,735 | 12.9% | 12.9% | 0.0% |
| LOAD_FAST | 53,602,230 | 12.5% | 25.5% |  |
| CALL | 27,648,565 | 6.5% | 31.9% |  |
| STORE_FAST | 26,215,220 | 6.1% | 38.1% |  |
| LOAD_GLOBAL_BUILTIN | 23,515,040 | 5.5% | 43.6% | 0.0% |
| IS_OP | 21,750,500 | 5.1% | 48.7% |  |
| POP_JUMP_IF_FALSE | 20,348,585 | 4.8% | 53.4% |  |
| LOAD_FAST_LOAD_FAST | 19,947,025 | 4.7% | 58.1% |  |
| POP_JUMP_IF_TRUE | 19,673,900 | 4.6% | 62.7% |  |
| RESUME_CHECK | 17,161,775 | 4.0% | 66.7% |  |
| RETURN_VALUE | 16,248,695 | 3.8% | 70.5% |  |
| LOAD_CONST | 13,149,545 | 3.1% | 73.6% |  |
| LOAD_ATTR | 10,540,165 | 2.5% | 76.0% |  |
| CALL_PY_EXACT_ARGS | 9,438,520 | 2.2% | 78.3% | 0.0% |
| CONTAINS_OP | 8,346,020 | 2.0% | 80.2% |  |
| TO_BOOL_BOOL | 8,051,825 | 1.9% | 82.1% |  |
| CALL_BUILTIN_FAST | 8,008,180 | 1.9% | 84.0% | 0.0% |
| ENTER_EXECUTOR | 6,318,970 | 1.5% | 85.4% |  |
| NOP | 4,725,260 | 1.1% | 86.5% |  |
| CALL_TYPE_1 | 4,711,980 | 1.1% | 87.6% |  |
| GET_ITER | 4,418,090 | 1.0% | 88.7% |  |
| POP_TOP | 3,852,670 | 0.9% | 89.6% |  |
| INTERPRETER_EXIT | 2,686,235 | 0.6% | 90.2% |  |
| RETURN_CONST | 2,686,000 | 0.6% | 90.8% |  |
| LOAD_DEREF | 2,673,900 | 0.6% | 91.5% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,669,080 | 0.6% | 92.1% | 0.1% |
| COPY_FREE_VARS | 2,669,040 | 0.6% | 92.7% |  |
| LOAD_SUPER_ATTR_METHOD | 2,667,960 | 0.6% | 93.3% |  |
| FOR_ITER | 2,601,715 | 0.6% | 93.9% |  |
| PUSH_NULL | 2,400,240 | 0.6% | 94.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,367,100 | 0.6% | 95.1% | 0.0% |
| FOR_ITER_TUPLE | 2,365,355 | 0.6% | 95.6% |  |
| BUILD_MAP | 2,362,855 | 0.6% | 96.2% |  |
| JUMP_FORWARD | 2,360,160 | 0.6% | 96.7% |  |
| CALL_PY_WITH_DEFAULTS | 2,358,240 | 0.6% | 97.3% |  |
| LOAD_ATTR_CLASS | 2,355,260 | 0.6% | 97.8% |  |
| CHECK_EXC_MATCH | 1,844,780 | 0.4% | 98.3% |  |
| POP_EXCEPT | 1,844,780 | 0.4% | 98.7% |  |
| PUSH_EXC_INFO | 1,844,780 | 0.4% | 99.1% |  |
| RAISE_VARARGS | 1,843,200 | 0.4% | 99.6% |  |
| JUMP_BACKWARD | 552,655 | 0.1% | 99.7% |  |
| POP_JUMP_IF_NONE | 518,280 | 0.1% | 99.8% |  |
| SWAP | 137,940 | 0.0% | 99.8% |  |
| BINARY_SUBSCR | 126,270 | 0.0% | 99.9% |  |
| LOAD_NAME | 66,520 | 0.0% | 99.9% |  |
| LOAD_ATTR_MODULE | 47,610 | 0.0% | 99.9% | 2.6% |
| LOAD_ATTR_METHOD_NO_DICT | 30,680 | 0.0% | 99.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 30,440 | 0.0% | 99.9% | 1.6% |
| STORE_NAME | 28,860 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 25,280 | 0.0% | 99.9% | 2.2% |
| STORE_ATTR_INSTANCE_VALUE | 17,840 | 0.0% | 99.9% | 14.5% |
| COPY | 14,040 | 0.0% | 99.9% |  |
| POP_JUMP_IF_NOT_NONE | 13,710 | 0.0% | 99.9% |  |
| CALL_ISINSTANCE | 13,375 | 0.0% | 99.9% |  |
| COMPARE_OP_INT | 12,880 | 0.0% | 99.9% |  |
| CALL_LEN | 12,180 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,980 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 11,680 | 0.0% | 99.9% | 2.4% |
| EXTENDED_ARG | 11,420 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 10,440 | 0.0% | 99.9% |  |
| STORE_SUBSCR_DICT | 9,300 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 8,480 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 8,460 | 0.0% | 100.0% | 0.7% |
| BUILD_LIST | 8,380 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 7,740 | 0.0% | 100.0% |  |
| STORE_ATTR | 7,600 | 0.0% | 100.0% |  |
| MAP_ADD | 7,460 | 0.0% | 100.0% |  |
| LIST_APPEND | 7,200 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 7,100 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 6,760 | 0.0% | 100.0% | 21.0% |
| BINARY_OP | 6,500 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 6,340 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 5,600 | 0.0% | 100.0% |  |
| BUILD_STRING | 5,420 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 5,320 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,220 | 0.0% | 100.0% | 10.0% |
| STORE_SUBSCR_LIST_INT | 4,820 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 4,300 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_INT | 3,900 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 3,840 | 0.0% | 100.0% |  |
| BINARY_SLICE | 3,760 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 3,500 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 3,380 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 3,320 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 3,280 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 3,180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 3,080 | 0.0% | 100.0% | 1.9% |
| CALL_LIST_APPEND | 3,040 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 2,860 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 2,740 | 0.0% | 100.0% |  |
| CALL_KW | 2,720 | 0.0% | 100.0% |  |
| MAKE_CELL | 2,620 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 2,440 | 0.0% | 100.0% |  |
| STORE_DEREF | 2,400 | 0.0% | 100.0% |  |
| TO_BOOL | 2,380 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 2,360 | 0.0% | 100.0% | 11.0% |
| BINARY_SUBSCR_LIST_INT | 2,340 | 0.0% | 100.0% | 13.7% |
| BEFORE_WITH | 2,160 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 1,700 | 0.0% | 100.0% | 1.2% |
| BUILD_CONST_KEY_MAP | 1,700 | 0.0% | 100.0% |  |
| RESUME | 1,700 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,680 | 0.0% | 100.0% | 2.4% |
| EXIT_INIT_CHECK | 1,680 | 0.0% | 100.0% |  |
| YIELD_VALUE | 1,620 | 0.0% | 100.0% |  |
| LIST_EXTEND | 1,580 | 0.0% | 100.0% |  |
| COMPARE_OP | 1,560 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 1,380 | 0.0% | 100.0% |  |
| IMPORT_NAME | 1,280 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 1,200 | 0.0% | 100.0% | 3.3% |
| CALL_INTRINSIC_1 | 1,200 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 1,140 | 0.0% | 100.0% |  |
| LOAD_ATTR_PROPERTY | 1,100 | 0.0% | 100.0% |  |
| DICT_MERGE | 1,060 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 1,020 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 1,020 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 1,000 | 0.0% | 100.0% |  |
| IMPORT_FROM | 900 | 0.0% | 100.0% |  |
| RERAISE | 880 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 780 | 0.0% | 100.0% |  |
| CALL_STR_1 | 760 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 720 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 600 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 520 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 440 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 420 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 400 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 380 | 0.0% | 100.0% |  |
| DICT_UPDATE | 300 | 0.0% | 100.0% |  |
| BUILD_SLICE | 280 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 260 | 0.0% | 100.0% |  |
| STORE_ATTR_SLOT | 260 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 240 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 240 | 0.0% | 100.0% |  |
| UNARY_NOT | 200 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 200 | 0.0% | 100.0% |  |
| BUILD_SET | 160 | 0.0% | 100.0% |  |
| DELETE_NAME | 160 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 120 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 80 | 0.0% | 100.0% |  |
| UNARY_NEGATIVE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 60 | 0.0% | 100.0% |  |
| STORE_SLICE | 40 | 0.0% | 100.0% |  |
| UNARY_INVERT | 40 | 0.0% | 100.0% |  |
| END_FOR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_MODULE IS_OP | 19,903,820 | 4.7% | 4.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 13,946,420 | 3.3% | 7.9% |
| IS_OP POP_JUMP_IF_FALSE | 13,423,760 | 3.1% | 11.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 12,102,015 | 2.8% | 13.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 11,915,640 | 2.8% | 16.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 11,793,420 | 2.8% | 19.4% |
| LOAD_FAST CALL | 11,271,540 | 2.6% | 22.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 9,450,350 | 2.2% | 24.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,437,560 | 2.2% | 26.5% |
| CALL CALL | 8,334,305 | 2.0% | 28.4% |
| IS_OP POP_JUMP_IF_TRUE | 8,326,280 | 1.9% | 30.4% |
| CALL RETURN_VALUE | 8,325,740 | 1.9% | 32.3% |
| LOAD_FAST LOAD_CONST | 7,714,660 | 1.8% | 34.1% |
| RETURN_VALUE STORE_FAST | 7,586,200 | 1.8% | 35.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 7,380,775 | 1.7% | 37.7% |
| STORE_FAST LOAD_FAST | 7,303,370 | 1.7% | 39.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 7,078,435 | 1.7% | 41.0% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 5,975,955 | 1.4% | 42.4% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 5,974,535 | 1.4% | 43.8% |
| LOAD_ATTR CONTAINS_OP | 5,973,845 | 1.4% | 45.2% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR | 5,973,175 | 1.4% | 46.6% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 5,969,960 | 1.4% | 48.0% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 5,853,350 | 1.4% | 49.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,364,125 | 1.3% | 50.6% |
| LOAD_CONST LOAD_CONST | 5,348,705 | 1.3% | 51.9% |
| LOAD_CONST CALL_BUILTIN_FAST | 5,332,585 | 1.2% | 53.1% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 5,328,950 | 1.2% | 54.4% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 5,328,930 | 1.2% | 55.6% |
| STORE_FAST LOAD_GLOBAL_MODULE | 4,719,800 | 1.1% | 56.7% |
| STORE_FAST NOP | 4,714,780 | 1.1% | 57.8% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 4,712,500 | 1.1% | 58.9% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 4,712,020 | 1.1% | 60.0% |
| LOAD_FAST CALL_TYPE_1 | 4,711,700 | 1.1% | 61.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 4,516,855 | 1.1% | 62.2% |
| CALL STORE_FAST | 4,407,740 | 1.0% | 63.2% |
| ENTER_EXECUTOR CALL | 3,618,620 | 0.8% | 64.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 2,687,280 | 0.6% | 64.7% |
| RESUME_CHECK LOAD_FAST | 2,680,240 | 0.6% | 65.3% |
| RETURN_CONST INTERPRETER_EXIT | 2,674,000 | 0.6% | 66.0% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 2,669,100 | 0.6% | 66.6% |
| LOAD_DEREF LOAD_FAST | 2,668,740 | 0.6% | 67.2% |
| COPY_FREE_VARS RESUME_CHECK | 2,668,600 | 0.6% | 67.8% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 2,668,375 | 0.6% | 68.5% |
| CACHE COPY_FREE_VARS | 2,668,320 | 0.6% | 69.1% |
| RETURN_VALUE TO_BOOL_BOOL | 2,668,180 | 0.6% | 69.7% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 2,668,080 | 0.6% | 70.3% |
| CALL_BUILTIN_FAST RETURN_VALUE | 2,667,975 | 0.6% | 71.0% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 2,667,920 | 0.6% | 71.6% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 2,666,060 | 0.6% | 72.2% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST | 2,664,740 | 0.6% | 72.8% |
| LOAD_ATTR LOAD_FAST | 2,485,650 | 0.6% | 73.4% |
| FOR_ITER STORE_FAST | 2,381,070 | 0.6% | 74.0% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 2,367,625 | 0.6% | 74.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,364,380 | 0.6% | 75.1% |
| LOAD_FAST PUSH_NULL | 2,364,200 | 0.6% | 75.6% |
| NOP LOAD_FAST | 2,361,520 | 0.6% | 76.2% |
| FOR_ITER_TUPLE STORE_FAST | 2,359,975 | 0.6% | 76.7% |
| GET_ITER FOR_ITER_TUPLE | 2,359,270 | 0.6% | 77.3% |
| LOAD_CONST CALL | 2,359,080 | 0.6% | 77.8% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 2,358,240 | 0.6% | 78.4% |
| LOAD_GLOBAL_MODULE CALL_METHOD_DESCRIPTOR_FAST | 2,357,960 | 0.6% | 78.9% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_MODULE | 2,357,680 | 0.6% | 79.5% |
| STORE_FAST JUMP_FORWARD | 2,357,200 | 0.6% | 80.0% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 2,357,160 | 0.6% | 80.6% |
| LOAD_GLOBAL_MODULE STORE_FAST | 2,356,880 | 0.6% | 81.1% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 2,356,260 | 0.6% | 81.7% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 2,356,100 | 0.6% | 82.2% |
| CALL GET_ITER | 2,355,860 | 0.6% | 82.8% |
| LOAD_FAST STORE_FAST | 2,355,800 | 0.6% | 83.3% |
| NOP LOAD_GLOBAL_BUILTIN | 2,355,580 | 0.6% | 83.9% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 2,355,500 | 0.6% | 84.4% |
| BUILD_MAP STORE_FAST | 2,355,460 | 0.6% | 85.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 2,355,420 | 0.6% | 85.5% |
| JUMP_FORWARD LOAD_GLOBAL_MODULE | 2,355,400 | 0.6% | 86.1% |
| CALL_TYPE_1 CALL_PY_EXACT_ARGS | 2,355,360 | 0.6% | 86.7% |
| CALL CONTAINS_OP | 2,355,200 | 0.6% | 87.2% |
| CALL_METHOD_DESCRIPTOR_FAST RETURN_VALUE | 2,355,180 | 0.6% | 87.8% |
| CALL_TYPE_1 STORE_FAST | 2,355,180 | 0.6% | 88.3% |
| LOAD_ATTR_CLASS LOAD_FAST_LOAD_FAST | 2,355,180 | 0.6% | 88.9% |
| RESUME_CHECK BUILD_MAP | 2,355,180 | 0.6% | 89.4% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 2,355,160 | 0.6% | 90.0% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR_CLASS | 2,355,160 | 0.6% | 90.5% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 2,232,800 | 0.5% | 91.0% |
| LOAD_GLOBAL_MODULE RETURN_VALUE | 2,232,580 | 0.5% | 91.6% |
| LOAD_FAST LOAD_ATTR | 2,191,560 | 0.5% | 92.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 2,056,020 | 0.5% | 92.5% |
| LOAD_ATTR GET_ITER | 2,050,990 | 0.5% | 93.0% |
| GET_ITER FOR_ITER | 2,050,940 | 0.5% | 93.5% |
| LOAD_GLOBAL_MODULE CALL | 2,050,200 | 0.5% | 94.0% |
| POP_TOP RETURN_CONST | 1,851,620 | 0.4% | 94.4% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,847,660 | 0.4% | 94.9% |
| POP_JUMP_IF_FALSE POP_TOP | 1,847,120 | 0.4% | 95.3% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 1,844,780 | 0.4% | 95.7% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 1,844,760 | 0.4% | 96.1% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 1,844,740 | 0.4% | 96.6% |
| POP_TOP POP_EXCEPT | 1,843,340 | 0.4% | 97.0% |
| POP_EXCEPT POP_TOP | 1,843,200 | 0.4% | 97.4% |
| CALL RAISE_VARARGS | 1,843,200 | 0.4% | 97.9% |
| LOAD_FAST_LOAD_FAST IS_OP | 1,843,200 | 0.4% | 98.3% |
| RAISE_VARARGS PUSH_EXC_INFO | 1,843,200 | 0.4% | 98.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,340 | 88.8% |
| LOAD_FAST | 420 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 740 | 19.7% |
| SWAP | 740 | 19.7% |
| CALL_PY_EXACT_ARGS | 540 | 14.4% |
| GET_ITER | 480 | 12.8% |
| STORE_FAST | 480 | 12.8% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 40 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 2,668,320 | 99.3% |
| RESUME_CHECK | 16,275 | 0.6% |
| RESUME | 1,300 | 0.0% |
| POP_TOP | 580 | 0.0% |
| MAKE_CELL | 80 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 940 | 43.5% |
| RETURN_VALUE | 520 | 24.1% |
| LOAD_ATTR_INSTANCE_VALUE | 520 | 24.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 180 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,980 | 91.7% |
| STORE_FAST | 180 | 8.3% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 123,450 | 97.8% |
| LOAD_CONST | 2,160 | 1.7% |
| BINARY_SUBSCR | 380 | 0.3% |
| BUILD_SLICE | 280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 123,880 | 98.1% |
| STORE_FAST | 480 | 0.4% |
| POP_JUMP_IF_NOT_NONE | 450 | 0.4% |
| BINARY_SUBSCR | 380 | 0.3% |
| STORE_NAME | 360 | 0.3% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,844,760 | 100.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,844,780 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 260 | 100.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,680 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,400 | 53.6% |
| CONVERT_VALUE | 1,380 | 21.8% |
| LOAD_ATTR | 1,320 | 20.8% |
| STORE_FAST_LOAD_FAST | 220 | 3.5% |
| LOAD_ATTR_MODULE | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,600 | 56.8% |
| BUILD_STRING | 2,700 | 42.6% |
| LOAD_FAST | 40 | 0.6% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,355,860 | 53.3% |
| LOAD_ATTR | 2,050,990 | 46.4% |
| LOAD_FAST | 6,100 | 0.1% |
| BUILD_TUPLE | 1,340 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 2,359,270 | 53.4% |
| FOR_ITER | 2,050,940 | 46.4% |
| LOAD_FAST_AND_CLEAR | 3,100 | 0.1% |
| FOR_ITER_LIST | 3,080 | 0.1% |
| EXTENDED_ARG | 820 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,674,000 | 99.5% |
| RETURN_VALUE | 10,715 | 0.4% |
| YIELD_VALUE | 1,520 | 0.1% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 640 | 88.9% |
| STORE_ATTR | 40 | 5.6% |
| RETURN_VALUE | 20 | 2.8% |
| DELETE_NAME | 20 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 720 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 5,500 | 52.7% |
| SET_FUNCTION_ATTRIBUTE | 3,100 | 29.7% |
| LOAD_CONST | 760 | 7.3% |
| CALL | 380 | 3.6% |
| CALL_BUILTIN_FAST | 240 | 2.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,714,780 | 99.8% |
| POP_TOP | 1,820 | 0.0% |
| RESUME_CHECK | 1,820 | 0.0% |
| POP_JUMP_IF_FALSE | 1,680 | 0.0% |
| NOP | 980 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,361,520 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 2,355,580 | 49.9% |
| LOAD_GLOBAL_MODULE | 4,760 | 0.1% |
| LOAD_CONST | 1,380 | 0.0% |
| NOP | 980 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,843,340 | 99.9% |
| STORE_FAST | 520 | 0.0% |
| COPY | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 240 | 0.0% |
| JUMP_FORWARD | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,843,200 | 99.9% |
| ENTER_EXECUTOR | 520 | 0.0% |
| EXTENDED_ARG | 440 | 0.0% |
| RERAISE | 440 | 0.0% |
| RETURN_CONST | 120 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,847,120 | 47.9% |
| POP_EXCEPT | 1,843,200 | 47.8% |
| SWAP | 126,040 | 3.3% |
| CALL | 8,060 | 0.2% |
| RETURN_CONST | 6,040 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,851,620 | 48.1% |
| POP_EXCEPT | 1,843,340 | 47.8% |
| RETURN_VALUE | 125,060 | 3.2% |
| LOAD_FAST | 8,740 | 0.2% |
| ENTER_EXECUTOR | 4,140 | 0.1% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RAISE_VARARGS | 1,843,200 | 99.9% |
| BINARY_SUBSCR_DICT | 1,020 | 0.1% |
| RERAISE | 440 | 0.0% |
| BINARY_SUBSCR_STR_INT | 60 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,844,740 | 100.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,364,200 | 98.5% |
| LOAD_ATTR_MODULE | 26,920 | 1.1% |
| LOAD_NAME | 4,880 | 0.2% |
| LOAD_ATTR | 2,300 | 0.1% |
| LOAD_BUILD_CLASS | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,357,160 | 98.2% |
| LOAD_FAST | 32,800 | 1.4% |
| LOAD_CONST | 4,220 | 0.2% |
| LOAD_NAME | 1,940 | 0.1% |
| CALL | 1,840 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 380 | 63.3% |
| CALL_PY_EXACT_ARGS | 220 | 36.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 360 | 60.0% |
| CALL_METHOD_DESCRIPTOR_O | 220 | 36.7% |
| RETURN_VALUE | 20 | 3.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 8,325,740 | 51.2% |
| CALL_BUILTIN_FAST | 2,667,975 | 16.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,355,180 | 14.5% |
| LOAD_GLOBAL_MODULE | 2,232,580 | 13.7% |
| LOAD_FAST | 517,420 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,586,200 | 46.7% |
| LOAD_GLOBAL_MODULE | 5,969,960 | 36.7% |
| TO_BOOL_BOOL | 2,668,180 | 16.4% |
| INTERPRETER_EXIT | 10,715 | 0.1% |
| RETURN_VALUE | 3,580 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 300 | 30.0% |
| LOAD_CONST | 200 | 20.0% |
| LOAD_FAST | 160 | 16.0% |
| LOAD_NAME | 120 | 12.0% |
| BINARY_OP | 100 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 300 | 30.0% |
| RETURN_CONST | 160 | 16.0% |
| EXTENDED_ARG | 120 | 12.0% |
| STORE_SUBSCR_DICT | 120 | 12.0% |
| LOAD_NAME | 100 | 10.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800 | 33.6% |
| CALL | 480 | 20.2% |
| LOAD_ATTR_INSTANCE_VALUE | 260 | 10.9% |
| CALL_BUILTIN_FAST | 140 | 5.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 140 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,140 | 47.9% |
| POP_JUMP_IF_TRUE | 540 | 22.7% |
| TO_BOOL_BOOL | 480 | 20.2% |
| TO_BOOL | 120 | 5.0% |
| TO_BOOL_INT | 40 | 1.7% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 40 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 60 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 140 | 70.0% |
| TO_BOOL_LIST | 60 | 30.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 140 | 70.0% |
| CALL_PY_EXACT_ARGS | 60 | 30.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 940 | 58.0% |
| CALL | 360 | 22.2% |
| BUILD_STRING | 220 | 13.6% |
| BINARY_SUBSCR_DICT | 100 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,520 | 93.8% |
| STORE_FAST | 100 | 6.2% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,700 | 26.2% |
| LOAD_GLOBAL_MODULE | 1,540 | 23.7% |
| BINARY_OP_SUBTRACT_INT | 680 | 10.5% |
| LOAD_FAST | 600 | 9.2% |
| LOAD_NAME | 380 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,540 | 23.7% |
| STORE_FAST | 980 | 15.1% |
| LOAD_CONST | 660 | 10.2% |
| SWAP | 500 | 7.7% |
| STORE_NAME | 400 | 6.2% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 620 | 36.5% |
| LOAD_CONST | 520 | 30.6% |
| RETURN_VALUE | 180 | 10.6% |
| STORE_NAME | 180 | 10.6% |
| MAP_ADD | 100 | 5.9% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,020 | 36.0% |
| LOAD_FAST | 1,160 | 13.8% |
| STORE_ATTR_INSTANCE_VALUE | 820 | 9.8% |
| LOAD_FAST_LOAD_FAST | 600 | 7.2% |
| RESUME_CHECK | 520 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,020 | 36.0% |
| LOAD_FAST | 2,140 | 25.5% |
| STORE_FAST | 1,380 | 16.5% |
| LOAD_CONST | 500 | 6.0% |
| COMPARE_OP | 460 | 5.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,355,180 | 99.7% |
| LOAD_CONST | 5,435 | 0.2% |
| LOAD_FAST | 560 | 0.0% |
| ENTER_EXECUTOR | 220 | 0.0% |
| LOAD_DEREF | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,355,460 | 99.7% |
| CALL_BUILTIN_FAST | 2,955 | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,020 | 0.1% |
| LOAD_FAST | 1,060 | 0.0% |
| LOAD_CONST | 440 | 0.0% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100 | 62.5% |
| LOAD_ATTR | 60 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 60 | 37.5% |
| STORE_FAST | 60 | 37.5% |
| BINARY_OP | 40 | 25.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 280 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,720 | 50.2% |
| FORMAT_SIMPLE | 2,700 | 49.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,980 | 36.5% |
| STORE_FAST | 1,280 | 23.6% |
| CALL_BUILTIN_O | 1,160 | 21.4% |
| LOAD_CONST | 440 | 8.1% |
| LIST_APPEND | 340 | 6.3% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,980 | 46.9% |
| BINARY_OP_ADD_UNICODE | 960 | 11.3% |
| LOAD_GLOBAL_BUILTIN | 560 | 6.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 540 | 6.4% |
| LOAD_FAST_LOAD_FAST | 440 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,980 | 23.3% |
| GET_ITER | 1,340 | 15.8% |
| STORE_FAST | 1,060 | 12.5% |
| LOAD_FAST | 700 | 8.3% |
| RETURN_VALUE | 640 | 7.5% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,271,540 | 40.8% |
| CALL | 8,334,305 | 30.1% |
| ENTER_EXECUTOR | 3,618,620 | 13.1% |
| LOAD_CONST | 2,359,080 | 8.5% |
| LOAD_GLOBAL_MODULE | 2,050,200 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 8,334,305 | 30.1% |
| RETURN_VALUE | 8,325,740 | 30.1% |
| STORE_FAST | 4,407,740 | 15.9% |
| GET_ITER | 2,355,860 | 8.5% |
| CONTAINS_OP | 2,355,200 | 8.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 1,060 | 30.3% |
| LOAD_FAST | 1,000 | 28.6% |
| CALL_INTRINSIC_1 | 920 | 26.3% |
| STORE_FAST | 480 | 13.7% |
| RETURN_VALUE | 20 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,020 | 29.1% |
| RETURN_VALUE | 580 | 16.6% |
| POP_TOP | 500 | 14.3% |
| GET_ITER | 480 | 13.7% |
| RESUME_CHECK | 400 | 11.4% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,140 | 95.0% |
| IMPORT_NAME | 60 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 920 | 76.7% |
| BUILD_MAP | 200 | 16.7% |
| POP_TOP | 60 | 5.0% |
| STORE_NAME | 20 | 1.7% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,200 | 80.9% |
| STORE_FAST | 220 | 8.1% |
| RETURN_VALUE | 120 | 4.4% |
| STORE_NAME | 100 | 3.7% |
| MAKE_CELL | 40 | 1.5% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 460 | 29.5% |
| LOAD_GLOBAL_MODULE | 380 | 24.4% |
| LOAD_FAST | 300 | 19.2% |
| BINARY_OP | 180 | 11.5% |
| LOAD_CONST | 120 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,160 | 74.4% |
| POP_JUMP_IF_TRUE | 320 | 20.5% |
| COMPARE_OP_INT | 40 | 2.6% |
| COMPARE_OP | 20 | 1.3% |
| COMPARE_OP_STR | 20 | 1.3% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 5,973,845 | 71.6% |
| CALL | 2,355,200 | 28.2% |
| LOAD_FAST_LOAD_FAST | 7,915 | 0.1% |
| LOAD_FAST | 3,260 | 0.0% |
| LOAD_CONST | 2,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,975,955 | 71.6% |
| POP_JUMP_IF_FALSE | 2,367,625 | 28.4% |
| RETURN_VALUE | 1,420 | 0.0% |
| EXTENDED_ARG | 760 | 0.0% |
| STORE_FAST | 260 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,380 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 1,380 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 2,080 | 14.8% |
| COMPARE_OP_STR | 2,060 | 14.7% |
| SWAP | 1,740 | 12.4% |
| CALL_BUILTIN_FAST | 1,740 | 12.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,500 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,800 | 55.6% |
| TO_BOOL_STR | 2,360 | 16.8% |
| COMPARE_OP_STR | 1,740 | 12.4% |
| LOAD_ATTR | 500 | 3.6% |
| TO_BOOL_NONE | 500 | 3.6% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 2,668,320 | 100.0% |
| CALL_PY_EXACT_ARGS | 380 | 0.0% |
| CALL | 220 | 0.0% |
| CALL_FUNCTION_EX | 80 | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,668,600 | 100.0% |
| RETURN_GENERATOR | 380 | 0.0% |
| RESUME | 60 | 0.0% |


</details>

### DELETE_NAME

<details>
<summary> Successors and predecessors for DELETE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 60 | 37.5% |
| FOR_ITER | 60 | 37.5% |
| STORE_NAME | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_NAME | 60 | 37.5% |
| LOAD_CONST | 40 | 25.0% |
| LOAD_NAME | 40 | 25.0% |
| LOAD_BUILD_CLASS | 20 | 12.5% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 820 | 77.4% |
| CALL | 240 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,060 | 100.0% |


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
| POP_JUMP_IF_TRUE | 5,853,350 | 92.6% |
| ENTER_EXECUTOR | 449,220 | 7.1% |
| POP_TOP | 4,140 | 0.1% |
| POP_JUMP_IF_NOT_NONE | 3,880 | 0.1% |
| LIST_APPEND | 3,200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,618,620 | 57.3% |
| LOAD_GLOBAL_MODULE | 2,232,800 | 35.3% |
| ENTER_EXECUTOR | 449,220 | 7.1% |
| LOAD_ATTR | 5,730 | 0.1% |
| SWAP | 2,540 | 0.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,940 | 17.0% |
| MAP_ADD | 1,560 | 13.7% |
| JUMP_FORWARD | 960 | 8.4% |
| POP_TOP | 900 | 7.9% |
| GET_ITER | 820 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,620 | 31.7% |
| ENTER_EXECUTOR | 2,120 | 18.6% |
| POP_JUMP_IF_FALSE | 1,940 | 17.0% |
| FOR_ITER | 1,140 | 10.0% |
| JUMP_FORWARD | 1,040 | 9.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,050,940 | 78.8% |
| JUMP_BACKWARD | 546,330 | 21.0% |
| FOR_ITER | 2,645 | 0.1% |
| EXTENDED_ARG | 1,140 | 0.0% |
| LOAD_FAST | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,381,070 | 91.5% |
| RETURN_CONST | 205,800 | 7.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,000 | 0.3% |
| FOR_ITER | 2,645 | 0.1% |
| STORE_NAME | 1,040 | 0.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 500 | 55.6% |
| STORE_NAME | 400 | 44.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 880 | 97.8% |
| STORE_FAST | 20 | 2.2% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 720 | 56.2% |
| IMPORT_FROM | 500 | 39.1% |
| CALL_INTRINSIC_1 | 60 | 4.7% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 19,903,820 | 91.5% |
| LOAD_FAST_LOAD_FAST | 1,843,200 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 1,860 | 0.0% |
| LOAD_FAST | 620 | 0.0% |
| LOAD_CONST | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,423,760 | 61.7% |
| POP_JUMP_IF_TRUE | 8,326,280 | 38.3% |
| LOAD_FAST | 380 | 0.0% |
| COPY | 40 | 0.0% |
| STORE_FAST | 40 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 512,000 | 92.6% |
| POP_JUMP_IF_TRUE | 19,285 | 3.5% |
| STORE_SUBSCR_DICT | 4,280 | 0.8% |
| POP_TOP | 4,010 | 0.7% |
| LIST_APPEND | 4,000 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 546,330 | 98.9% |
| FOR_ITER_TUPLE | 2,945 | 0.5% |
| FOR_ITER_LIST | 1,560 | 0.3% |
| EXTENDED_ARG | 780 | 0.1% |
| FOR_ITER_RANGE | 640 | 0.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,357,200 | 99.9% |
| EXTENDED_ARG | 1,040 | 0.0% |
| POP_TOP | 480 | 0.0% |
| LOAD_FAST | 360 | 0.0% |
| COMPARE_OP_STR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,355,400 | 99.8% |
| LOAD_FAST | 2,020 | 0.1% |
| EXTENDED_ARG | 960 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 820 | 0.0% |
| LOAD_FAST_LOAD_FAST | 380 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,880 | 40.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,220 | 30.8% |
| CALL | 1,040 | 14.4% |
| BUILD_TUPLE | 560 | 7.8% |
| BUILD_STRING | 340 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,000 | 55.6% |
| ENTER_EXECUTOR | 3,200 | 44.4% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,040 | 65.8% |
| LOAD_CONST | 420 | 26.6% |
| LOAD_DEREF | 80 | 5.1% |
| LOAD_NAME | 40 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,140 | 72.2% |
| BUILD_LIST | 120 | 7.6% |
| LOAD_CONST | 100 | 6.3% |
| STORE_NAME | 100 | 6.3% |
| STORE_FAST | 60 | 3.8% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,973,175 | 56.7% |
| LOAD_GLOBAL_BUILTIN | 2,356,260 | 22.4% |
| LOAD_FAST | 2,191,560 | 20.8% |
| ENTER_EXECUTOR | 5,730 | 0.1% |
| LOAD_ATTR | 5,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 5,973,845 | 56.7% |
| LOAD_FAST | 2,485,650 | 23.6% |
| GET_ITER | 2,050,990 | 19.5% |
| LOAD_ATTR_METHOD_NO_DICT | 7,980 | 0.1% |
| LOAD_ATTR | 5,260 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,714,660 | 58.7% |
| LOAD_CONST | 5,348,705 | 40.7% |
| STORE_NAME | 10,940 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 9,560 | 0.1% |
| STORE_FAST | 6,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,348,705 | 40.7% |
| CALL_BUILTIN_FAST | 5,332,585 | 40.6% |
| CALL | 2,359,080 | 17.9% |
| LOAD_FAST | 13,500 | 0.1% |
| MAKE_FUNCTION | 10,440 | 0.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,669,100 | 99.8% |
| POP_JUMP_IF_FALSE | 1,140 | 0.0% |
| STORE_FAST | 860 | 0.0% |
| BINARY_SLICE | 360 | 0.0% |
| RESUME_CHECK | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,668,740 | 99.8% |
| LOAD_CONST | 860 | 0.0% |
| CALL_BUILTIN_CLASS | 660 | 0.0% |
| PUSH_NULL | 640 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 520 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 11,915,640 | 22.2% |
| LOAD_GLOBAL_MODULE | 11,793,420 | 22.0% |
| POP_JUMP_IF_FALSE | 9,450,350 | 17.6% |
| STORE_FAST | 7,303,370 | 13.6% |
| RESUME_CHECK | 2,680,240 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,946,420 | 26.0% |
| CALL | 11,271,540 | 21.0% |
| LOAD_CONST | 7,714,660 | 14.4% |
| CALL_TYPE_1 | 4,711,700 | 8.8% |
| LOAD_SUPER_ATTR_METHOD | 2,667,920 | 5.0% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,100 | 97.5% |
| LOAD_FAST_AND_CLEAR | 80 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,100 | 97.5% |
| LOAD_FAST_AND_CLEAR | 80 | 2.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 940 | 92.2% |
| LOAD_ATTR_METHOD_NO_DICT | 60 | 5.9% |
| LOAD_FAST | 20 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 940 | 92.2% |
| LOAD_ATTR | 40 | 3.9% |
| LOAD_FAST | 20 | 2.0% |
| CALL_LIST_APPEND | 20 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,380,775 | 37.0% |
| POP_JUMP_IF_TRUE | 5,974,535 | 30.0% |
| PUSH_NULL | 2,357,160 | 11.8% |
| LOAD_ATTR_CLASS | 2,355,180 | 11.8% |
| POP_JUMP_IF_FALSE | 1,847,660 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 5,973,175 | 29.9% |
| CALL_PY_EXACT_ARGS | 4,712,500 | 23.6% |
| CALL_BUILTIN_FAST | 2,668,375 | 13.4% |
| CALL_PY_WITH_DEFAULTS | 2,355,500 | 11.8% |
| LOAD_GLOBAL_MODULE | 2,355,160 | 11.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 680 | 15.8% |
| LOAD_FAST | 560 | 13.0% |
| LOAD_GLOBAL | 460 | 10.7% |
| POP_JUMP_IF_FALSE | 420 | 9.8% |
| LOAD_GLOBAL_MODULE | 360 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,300 | 30.2% |
| LOAD_GLOBAL_BUILTIN | 820 | 19.1% |
| LOAD_FAST | 640 | 14.9% |
| LOAD_GLOBAL | 460 | 10.7% |
| IS_OP | 240 | 5.6% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 21,000 | 31.6% |
| LOAD_NAME | 18,420 | 27.7% |
| STORE_NAME | 10,420 | 15.7% |
| LOAD_CONST | 2,160 | 3.2% |
| LOAD_FAST | 2,000 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 20,720 | 31.1% |
| LOAD_NAME | 18,420 | 27.7% |
| LOAD_CONST | 5,740 | 8.6% |
| PUSH_NULL | 4,880 | 7.3% |
| STORE_SUBSCR_LIST_INT | 4,320 | 6.5% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 50.0% |
| LOAD_SUPER_ATTR_METHOD | 40 | 50.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 1,840 | 70.2% |
| CALL_PY_EXACT_ARGS | 360 | 13.7% |
| CALL | 300 | 11.5% |
| CACHE | 80 | 3.1% |
| CALL_KW | 40 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 1,840 | 70.2% |
| RESUME_CHECK | 720 | 27.5% |
| RESUME | 60 | 2.3% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,080 | 54.7% |
| LOAD_FAST_LOAD_FAST | 1,360 | 18.2% |
| LOAD_NAME | 680 | 9.1% |
| LOAD_FAST | 540 | 7.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 340 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,260 | 43.7% |
| JUMP_BACKWARD | 2,160 | 29.0% |
| EXTENDED_ARG | 1,560 | 20.9% |
| DICT_UPDATE | 220 | 2.9% |
| ENTER_EXECUTOR | 200 | 2.7% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 13,423,760 | 66.0% |
| TO_BOOL_BOOL | 2,687,280 | 13.2% |
| CONTAINS_OP | 2,367,625 | 11.6% |
| CHECK_EXC_MATCH | 1,844,780 | 9.1% |
| COMPARE_OP_INT | 7,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,450,350 | 46.4% |
| LOAD_GLOBAL_BUILTIN | 4,516,855 | 22.2% |
| LOAD_GLOBAL_MODULE | 2,056,020 | 10.1% |
| LOAD_FAST_LOAD_FAST | 1,847,660 | 9.1% |
| POP_TOP | 1,847,120 | 9.1% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 514,500 | 99.3% |
| LOAD_GLOBAL_MODULE | 1,420 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,400 | 0.3% |
| LOAD_ATTR | 380 | 0.1% |
| LOAD_ATTR_MODULE | 360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 512,000 | 98.8% |
| LOAD_GLOBAL_BUILTIN | 2,060 | 0.4% |
| LOAD_FAST | 2,020 | 0.4% |
| LOAD_GLOBAL_MODULE | 1,160 | 0.2% |
| LOAD_CONST | 580 | 0.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,180 | 67.0% |
| CALL_BUILTIN_FAST | 1,440 | 10.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,340 | 9.8% |
| LOAD_FAST_CHECK | 940 | 6.9% |
| BINARY_SUBSCR | 450 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,700 | 41.6% |
| ENTER_EXECUTOR | 3,880 | 28.3% |
| LOAD_GLOBAL_MODULE | 1,600 | 11.7% |
| NOP | 940 | 6.9% |
| POP_TOP | 470 | 3.4% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 8,326,280 | 42.3% |
| CONTAINS_OP | 5,975,955 | 30.4% |
| TO_BOOL_BOOL | 5,364,125 | 27.3% |
| TO_BOOL_STR | 2,460 | 0.0% |
| COMPARE_OP_INT | 2,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,974,535 | 30.4% |
| ENTER_EXECUTOR | 5,853,350 | 29.8% |
| LOAD_GLOBAL_BUILTIN | 5,328,930 | 27.1% |
| LOAD_GLOBAL_MODULE | 2,357,680 | 12.0% |
| LOAD_FAST | 132,240 | 0.7% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,843,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,843,200 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 440 | 50.0% |
| POP_JUMP_IF_FALSE | 440 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 440 | 50.0% |
| COPY | 440 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,851,620 | 68.9% |
| POP_JUMP_IF_FALSE | 619,420 | 23.1% |
| FOR_ITER | 205,800 | 7.7% |
| STORE_ATTR_INSTANCE_VALUE | 4,240 | 0.2% |
| RESUME_CHECK | 1,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,674,000 | 99.6% |
| POP_TOP | 6,040 | 0.2% |
| TO_BOOL_BOOL | 2,840 | 0.1% |
| EXIT_INIT_CHECK | 1,680 | 0.1% |
| STORE_FAST | 1,020 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,100 | 94.5% |
| SET_FUNCTION_ATTRIBUTE | 180 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,180 | 36.0% |
| STORE_NAME | 1,140 | 34.8% |
| CALL | 360 | 11.0% |
| LOAD_GLOBAL_MODULE | 360 | 11.0% |
| SET_FUNCTION_ATTRIBUTE | 180 | 5.5% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,200 | 68.4% |
| LOAD_FAST_LOAD_FAST | 840 | 11.1% |
| SWAP | 500 | 6.6% |
| LOAD_ATTR | 440 | 5.8% |
| STORE_ATTR | 440 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,520 | 46.3% |
| ENTER_EXECUTOR | 1,320 | 17.4% |
| NOP | 680 | 8.9% |
| LOAD_CONST | 580 | 7.6% |
| STORE_ATTR | 440 | 5.8% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 880 | 36.7% |
| LOAD_ATTR | 240 | 10.0% |
| BINARY_OP_ADD_UNICODE | 220 | 9.2% |
| CALL_BUILTIN_CLASS | 220 | 9.2% |
| CALL_LEN | 220 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 880 | 36.7% |
| LOAD_GLOBAL_BUILTIN | 820 | 34.2% |
| LOAD_CONST | 220 | 9.2% |
| LOAD_DEREF | 220 | 9.2% |
| LOAD_GLOBAL_MODULE | 220 | 9.2% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,586,200 | 28.9% |
| CALL | 4,407,740 | 16.8% |
| FOR_ITER | 2,381,070 | 9.1% |
| FOR_ITER_TUPLE | 2,359,975 | 9.0% |
| LOAD_GLOBAL_MODULE | 2,356,880 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,303,370 | 27.9% |
| LOAD_GLOBAL_BUILTIN | 7,078,435 | 27.0% |
| LOAD_GLOBAL_MODULE | 4,719,800 | 18.0% |
| NOP | 4,714,780 | 18.0% |
| JUMP_FORWARD | 2,357,200 | 9.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 2,980 | 77.6% |
| FOR_ITER_LIST | 520 | 13.5% |
| CALL_LEN | 300 | 7.8% |
| FOR_ITER | 40 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 2,220 | 57.8% |
| LOAD_FAST | 1,100 | 28.6% |
| PUSH_NULL | 300 | 7.8% |
| FORMAT_SIMPLE | 220 | 5.7% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 6,300 | 88.7% |
| UNPACK_SEQUENCE_TUPLE | 400 | 5.6% |
| COPY | 340 | 4.8% |
| UNPACK_SEQUENCE | 60 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,720 | 38.3% |
| LOAD_NAME | 1,540 | 21.7% |
| LOAD_GLOBAL_MODULE | 1,160 | 16.3% |
| LOAD_FAST_LOAD_FAST | 600 | 8.5% |
| NOP | 520 | 7.3% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 5,500 | 19.1% |
| STORE_NAME | 4,600 | 15.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,540 | 15.7% |
| LOAD_CONST | 3,800 | 13.2% |
| CALL | 1,560 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,940 | 37.9% |
| LOAD_NAME | 10,420 | 36.1% |
| STORE_NAME | 4,600 | 15.9% |
| RETURN_CONST | 760 | 2.6% |
| LOAD_BUILD_CLASS | 640 | 2.2% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 123,880 | 89.8% |
| LOAD_FAST_AND_CLEAR | 3,100 | 2.2% |
| BUILD_LIST | 3,020 | 2.2% |
| ENTER_EXECUTOR | 2,540 | 1.8% |
| POP_JUMP_IF_FALSE | 1,380 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 126,040 | 91.4% |
| BUILD_LIST | 3,020 | 2.2% |
| STORE_FAST | 3,020 | 2.2% |
| FOR_ITER_TUPLE | 2,740 | 2.0% |
| COPY | 1,740 | 1.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 50.0% |
| STORE_FAST_STORE_FAST | 60 | 25.0% |
| STORE_NAME | 60 | 25.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 1,300 | 76.5% |
| CALL | 220 | 12.9% |
| CALL_FUNCTION_EX | 60 | 3.5% |
| COPY_FREE_VARS | 60 | 3.5% |
| MAKE_CELL | 60 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 720 | 42.4% |
| LOAD_CONST | 580 | 34.1% |
| LOAD_GLOBAL | 220 | 12.9% |
| LOAD_FAST | 100 | 5.9% |
| NOP | 20 | 1.2% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,560 | 91.3% |
| LOAD_FAST_LOAD_FAST | 160 | 4.1% |
| BINARY_OP_MULTIPLY_INT | 120 | 3.1% |
| BINARY_OP | 60 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,260 | 32.3% |
| STORE_FAST | 960 | 24.6% |
| LOAD_FAST | 820 | 21.0% |
| LOAD_CONST | 360 | 9.2% |
| RETURN_VALUE | 320 | 8.2% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,240 | 54.8% |
| LOAD_FAST_LOAD_FAST | 2,160 | 27.9% |
| CALL_METHOD_DESCRIPTOR_O | 560 | 7.2% |
| BINARY_SUBSCR_LIST_INT | 360 | 4.7% |
| BINARY_OP | 240 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 2,000 | 25.8% |
| LOAD_FAST | 1,760 | 22.7% |
| BUILD_TUPLE | 960 | 12.4% |
| LOAD_NAME | 960 | 12.4% |
| LOAD_CONST | 580 | 7.5% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 120 | 60.0% |
| LOAD_CONST | 80 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 120 | 60.0% |
| LOAD_CONST | 40 | 20.0% |
| CALL_BUILTIN_O | 40 | 20.0% |


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
| LOAD_CONST | 1,380 | 56.6% |
| LOAD_FAST | 580 | 23.8% |
| CALL_LEN | 460 | 18.9% |
| BINARY_OP | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 680 | 27.9% |
| LOAD_FAST | 520 | 21.3% |
| RETURN_VALUE | 460 | 18.9% |
| LOAD_FAST_LOAD_FAST | 380 | 15.6% |
| STORE_FAST | 200 | 8.2% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,320 | 81.1% |
| LOAD_CONST | 360 | 12.6% |
| LOAD_FAST_LOAD_FAST | 120 | 4.2% |
| BUILD_TUPLE | 60 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200 | 42.0% |
| PUSH_EXC_INFO | 1,020 | 35.7% |
| LOAD_FAST | 180 | 6.3% |
| CALL_BUILTIN_CLASS | 180 | 6.3% |
| LOAD_CONST | 120 | 4.2% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 580 | 50.9% |
| ENTER_EXECUTOR | 300 | 26.3% |
| LOAD_FAST | 260 | 22.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,140 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,820 | 77.8% |
| LOAD_CONST | 500 | 21.4% |
| BINARY_SUBSCR | 20 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,600 | 79.2% |
| BINARY_OP_ADD_UNICODE | 360 | 17.8% |
| LOAD_CONST | 20 | 1.0% |
| STORE_FAST | 20 | 1.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 1.0% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,160 | 70.1% |
| LOAD_FAST | 920 | 29.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,160 | 37.7% |
| LOAD_FAST | 1,000 | 32.5% |
| STORE_FAST | 620 | 20.1% |
| BINARY_OP_INPLACE_ADD_UNICODE | 240 | 7.8% |
| PUSH_EXC_INFO | 60 | 1.9% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,280 | 98.8% |
| BINARY_SUBSCR | 40 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,060 | 31.9% |
| LOAD_GLOBAL_MODULE | 820 | 24.7% |
| RETURN_VALUE | 460 | 13.9% |
| CALL_BUILTIN_O | 400 | 12.0% |
| LOAD_FAST | 120 | 3.6% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 880 | 51.8% |
| LOAD_FAST_LOAD_FAST | 460 | 27.1% |
| ENTER_EXECUTOR | 180 | 10.6% |
| BINARY_SUBSCR | 120 | 7.1% |
| LOAD_GLOBAL_MODULE | 60 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,680 | 98.8% |
| STORE_FAST | 20 | 1.2% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,666,060 | 99.9% |
| LOAD_CONST | 1,880 | 0.1% |
| BUILD_TUPLE | 460 | 0.0% |
| PUSH_NULL | 380 | 0.0% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,668,080 | 100.0% |
| POP_TOP | 940 | 0.0% |
| COPY_FREE_VARS | 40 | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 20 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 660 | 24.1% |
| CALL_BUILTIN_FAST | 500 | 18.2% |
| LOAD_GLOBAL_BUILTIN | 380 | 13.9% |
| LOAD_FAST | 300 | 10.9% |
| CALL_BUILTIN_CLASS | 220 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 840 | 30.7% |
| LOAD_FAST | 380 | 13.9% |
| GET_ITER | 340 | 12.4% |
| LOAD_CONST | 260 | 9.5% |
| STORE_DEREF | 220 | 8.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,332,585 | 66.6% |
| LOAD_FAST_LOAD_FAST | 2,668,375 | 33.3% |
| BUILD_MAP | 2,955 | 0.0% |
| LOAD_FAST | 2,200 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,365 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,328,950 | 66.5% |
| RETURN_VALUE | 2,667,975 | 33.3% |
| STORE_FAST | 4,515 | 0.1% |
| POP_TOP | 2,620 | 0.0% |
| COPY | 1,740 | 0.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,440 | 88.8% |
| BINARY_OP_ADD_INT | 1,260 | 5.0% |
| LOAD_CONST | 760 | 3.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 320 | 1.3% |
| CALL | 220 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 20,720 | 82.0% |
| COPY | 1,500 | 5.9% |
| RETURN_VALUE | 1,400 | 5.5% |
| STORE_FAST | 560 | 2.2% |
| MAP_ADD | 340 | 1.3% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,260 | 33.4% |
| BUILD_STRING | 1,160 | 17.2% |
| ENTER_EXECUTOR | 1,160 | 17.2% |
| LOAD_GLOBAL_MODULE | 660 | 9.8% |
| LOAD_CONST | 420 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,200 | 47.3% |
| STORE_FAST | 1,560 | 23.1% |
| TO_BOOL_BOOL | 1,380 | 20.4% |
| BUILD_TUPLE | 300 | 4.4% |
| TO_BOOL_INT | 260 | 3.8% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,060 | 37.8% |
| LOAD_ATTR_MODULE | 2,855 | 21.3% |
| LOAD_GLOBAL_MODULE | 2,540 | 19.0% |
| LOAD_NAME | 1,500 | 11.2% |
| LOAD_FAST_LOAD_FAST | 920 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 12,195 | 91.2% |
| POP_TOP | 940 | 7.0% |
| RETURN_VALUE | 120 | 0.9% |
| TO_BOOL | 60 | 0.4% |
| LOAD_FAST | 60 | 0.4% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,640 | 62.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,740 | 14.3% |
| LOAD_NAME | 1,360 | 11.2% |
| LOAD_ATTR | 540 | 4.4% |
| POP_JUMP_IF_TRUE | 460 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,220 | 34.6% |
| LOAD_FAST | 2,640 | 21.7% |
| COMPARE_OP_INT | 1,420 | 11.7% |
| STORE_FAST | 1,120 | 9.2% |
| RETURN_VALUE | 960 | 7.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,940 | 63.8% |
| BUILD_TUPLE | 380 | 12.5% |
| LOAD_CONST | 340 | 11.2% |
| LOAD_ATTR_INSTANCE_VALUE | 260 | 8.6% |
| LOAD_GLOBAL_MODULE | 60 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 840 | 27.6% |
| LOAD_FAST | 500 | 16.4% |
| LOAD_GLOBAL_BUILTIN | 480 | 15.8% |
| EXTENDED_ARG | 380 | 12.5% |
| NOP | 280 | 9.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,357,960 | 99.6% |
| LOAD_FAST | 3,420 | 0.1% |
| BUILD_MAP | 2,020 | 0.1% |
| LOAD_CONST | 2,020 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,355,180 | 99.5% |
| STORE_FAST | 6,540 | 0.3% |
| LIST_APPEND | 2,220 | 0.1% |
| TO_BOOL_BOOL | 1,760 | 0.1% |
| POP_TOP | 800 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 40.0% |
| LOAD_ATTR_METHOD_NO_DICT | 160 | 40.0% |
| LOAD_GLOBAL_MODULE | 60 | 15.0% |
| LOAD_FAST | 20 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 160 | 40.0% |
| LOAD_ATTR_METHOD_NO_DICT | 160 | 40.0% |
| LOAD_CONST | 60 | 15.0% |
| STORE_FAST | 20 | 5.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,580 | 94.0% |
| CALL | 60 | 3.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 540 | 32.1% |
| BINARY_OP | 360 | 21.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 320 | 19.0% |
| TO_BOOL_BOOL | 220 | 13.1% |
| GET_ITER | 100 | 6.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,060 | 26.2% |
| STORE_FAST | 2,220 | 19.0% |
| LOAD_CONST | 1,520 | 13.0% |
| CALL_METHOD_DESCRIPTOR_O | 1,420 | 12.2% |
| LOAD_NAME | 1,240 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,400 | 37.7% |
| RETURN_VALUE | 3,160 | 27.1% |
| CALL_METHOD_DESCRIPTOR_O | 1,420 | 12.2% |
| LOAD_CONST | 1,160 | 9.9% |
| STORE_FAST | 580 | 5.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,712,500 | 49.9% |
| LOAD_FAST | 2,364,380 | 25.1% |
| CALL_TYPE_1 | 2,355,360 | 25.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,960 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,437,560 | 100.0% |
| COPY_FREE_VARS | 380 | 0.0% |
| MAKE_CELL | 360 | 0.0% |
| RETURN_GENERATOR | 220 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,355,500 | 99.9% |
| LOAD_FAST | 1,360 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,260 | 0.1% |
| CALL | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,358,240 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 360 | 47.4% |
| CALL_BUILTIN_O | 220 | 28.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 180 | 23.7% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 220 | 42.3% |
| LOAD_GLOBAL_MODULE | 220 | 42.3% |
| LOAD_FAST | 60 | 11.5% |
| CALL | 20 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 220 | 42.3% |
| STORE_DEREF | 220 | 42.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 11.5% |
| STORE_FAST | 20 | 3.8% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,711,700 | 100.0% |
| LOAD_GLOBAL_MODULE | 200 | 0.0% |
| CALL | 60 | 0.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,355,360 | 50.0% |
| STORE_FAST | 2,355,180 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 740 | 0.0% |
| LOAD_GLOBAL_MODULE | 260 | 0.0% |
| PUSH_NULL | 220 | 0.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 420 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,420 | 57.6% |
| LOAD_FAST | 3,660 | 28.4% |
| CALL_LEN | 1,420 | 11.0% |
| BINARY_OP | 180 | 1.4% |
| LOAD_GLOBAL_MODULE | 160 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,560 | 58.7% |
| POP_JUMP_IF_TRUE | 2,180 | 16.9% |
| COPY | 2,080 | 16.1% |
| RETURN_VALUE | 880 | 6.8% |
| STORE_FAST | 180 | 1.4% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,480 | 64.8% |
| COPY | 1,740 | 20.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,020 | 12.1% |
| LOAD_FAST | 180 | 2.1% |
| COMPARE_OP | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,080 | 60.0% |
| COPY | 2,060 | 24.3% |
| EXTENDED_ARG | 760 | 9.0% |
| JUMP_FORWARD | 360 | 4.3% |
| RETURN_VALUE | 200 | 2.4% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 100 | 83.3% |
| FOR_ITER | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 100 | 83.3% |
| POP_TOP | 20 | 16.7% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,080 | 57.9% |
| JUMP_BACKWARD | 1,560 | 29.3% |
| EXTENDED_ARG | 580 | 10.9% |
| FOR_ITER | 80 | 1.5% |
| LOAD_FAST | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,120 | 58.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,220 | 22.9% |
| STORE_FAST_LOAD_FAST | 520 | 9.8% |
| LOAD_FAST | 180 | 3.4% |
| JUMP_BACKWARD | 140 | 2.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 640 | 62.7% |
| GET_ITER | 280 | 27.5% |
| SWAP | 60 | 5.9% |
| FOR_ITER | 40 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,020 | 100.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,359,270 | 99.7% |
| JUMP_BACKWARD | 2,945 | 0.1% |
| SWAP | 2,740 | 0.1% |
| LOAD_FAST | 220 | 0.0% |
| FOR_ITER | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,359,975 | 99.8% |
| STORE_FAST_LOAD_FAST | 2,980 | 0.1% |
| STORE_NAME | 1,280 | 0.1% |
| SWAP | 260 | 0.0% |
| LOAD_GLOBAL_MODULE | 240 | 0.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,355,160 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,355,180 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| LOAD_FAST | 20 | 0.0% |
| STORE_FAST | 20 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,140 | 89.2% |
| LOAD_FAST_LOAD_FAST | 2,920 | 9.6% |
| LOAD_ATTR_INSTANCE_VALUE | 320 | 1.1% |
| LOAD_ATTR | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,700 | 22.0% |
| STORE_FAST | 3,460 | 11.4% |
| LOAD_ATTR_METHOD_NO_DICT | 2,120 | 7.0% |
| CALL_LEN | 1,740 | 5.7% |
| POP_JUMP_IF_NONE | 1,400 | 4.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,960 | 39.0% |
| LOAD_ATTR | 7,980 | 26.0% |
| LOAD_GLOBAL_MODULE | 2,880 | 9.4% |
| LOAD_CONST | 2,540 | 8.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,120 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,660 | 41.3% |
| LOAD_CONST | 9,560 | 31.2% |
| LOAD_GLOBAL_MODULE | 3,660 | 11.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,580 | 5.1% |
| LOAD_NAME | 1,280 | 4.2% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,760 | 72.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,040 | 19.9% |
| LOAD_GLOBAL_MODULE | 260 | 5.0% |
| BINARY_SUBSCR_TUPLE_INT | 120 | 2.3% |
| BINARY_SUBSCR | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,980 | 37.9% |
| CALL_PY_EXACT_ARGS | 1,960 | 37.5% |
| LOAD_FAST_LOAD_FAST | 1,000 | 19.2% |
| LOAD_CONST | 200 | 3.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 23,495 | 49.3% |
| LOAD_NAME | 20,720 | 43.5% |
| LOAD_ATTR_MODULE | 2,855 | 6.0% |
| LOAD_ATTR | 300 | 0.6% |
| LOAD_FAST | 240 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 26,920 | 56.5% |
| CALL | 3,980 | 8.4% |
| LOAD_ATTR | 3,160 | 6.6% |
| CALL_ISINSTANCE | 2,855 | 6.0% |
| LOAD_ATTR_MODULE | 2,855 | 6.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380 | 86.4% |
| LOAD_CONST | 60 | 13.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380 | 86.4% |
| LOAD_GLOBAL_BUILTIN | 60 | 13.6% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| LOAD_FAST_LOAD_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 60 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 50.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 980 | 89.1% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,100 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320 | 84.2% |
| LOAD_FAST_LOAD_FAST | 60 | 15.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 260 | 68.4% |
| LOAD_FAST_LOAD_FAST | 60 | 15.8% |
| CALL_ISINSTANCE | 60 | 15.8% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,078,435 | 30.1% |
| POP_JUMP_IF_TRUE | 5,328,930 | 22.7% |
| POP_JUMP_IF_FALSE | 4,516,855 | 19.2% |
| NOP | 2,355,580 | 10.0% |
| LOAD_GLOBAL_MODULE | 2,355,420 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,915,640 | 50.7% |
| LOAD_DEREF | 2,669,100 | 11.4% |
| LOAD_ATTR | 2,356,260 | 10.0% |
| LOAD_GLOBAL_MODULE | 2,356,100 | 10.0% |
| LOAD_ATTR_CLASS | 2,355,160 | 10.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,946,420 | 25.3% |
| RESUME_CHECK | 12,102,015 | 21.9% |
| RETURN_VALUE | 5,969,960 | 10.8% |
| STORE_FAST | 4,719,800 | 8.6% |
| LOAD_GLOBAL_MODULE | 4,712,020 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 19,903,820 | 36.1% |
| LOAD_FAST | 11,793,420 | 21.4% |
| LOAD_FAST_LOAD_FAST | 7,380,775 | 13.4% |
| LOAD_GLOBAL_MODULE | 4,712,020 | 8.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,357,960 | 4.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,667,920 | 100.0% |
| LOAD_SUPER_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,664,740 | 99.9% |
| LOAD_FAST_LOAD_FAST | 3,180 | 0.1% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 9,437,560 | 55.0% |
| COPY_FREE_VARS | 2,668,600 | 15.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,668,080 | 15.5% |
| CALL_PY_WITH_DEFAULTS | 2,358,240 | 13.7% |
| CACHE | 16,275 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,102,015 | 70.5% |
| LOAD_FAST | 2,680,240 | 15.6% |
| BUILD_MAP | 2,355,180 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 10,620 | 0.1% |
| LOAD_FAST_LOAD_FAST | 4,760 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,560 | 53.6% |
| LOAD_FAST_LOAD_FAST | 8,040 | 45.1% |
| STORE_ATTR | 120 | 0.7% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.3% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,240 | 29.4% |
| RETURN_CONST | 4,240 | 23.8% |
| LOAD_FAST_LOAD_FAST | 3,540 | 19.8% |
| LOAD_CONST | 1,700 | 9.5% |
| LOAD_GLOBAL_MODULE | 1,160 | 6.5% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 260 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,180 | 44.9% |
| BINARY_OP_ADD_UNICODE | 2,000 | 21.5% |
| LOAD_NAME | 1,360 | 14.6% |
| LOAD_CONST | 740 | 8.0% |
| LOAD_ATTR_INSTANCE_VALUE | 520 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,280 | 46.0% |
| LOAD_FAST | 1,720 | 18.5% |
| LOAD_NAME | 1,440 | 15.5% |
| NOP | 780 | 8.4% |
| LOAD_GLOBAL_MODULE | 520 | 5.6% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 4,320 | 89.6% |
| LOAD_FAST_LOAD_FAST | 380 | 7.9% |
| LOAD_FAST | 80 | 1.7% |
| STORE_SUBSCR | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,980 | 61.8% |
| LOAD_NAME | 1,380 | 28.6% |
| EXTENDED_ARG | 240 | 5.0% |
| ENTER_EXECUTOR | 160 | 3.3% |
| RETURN_CONST | 60 | 1.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 5,328,950 | 66.2% |
| RETURN_VALUE | 2,668,180 | 33.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20,720 | 0.3% |
| CALL_ISINSTANCE | 12,195 | 0.2% |
| COPY | 7,800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,364,125 | 66.6% |
| POP_JUMP_IF_FALSE | 2,687,280 | 33.4% |
| EXTENDED_ARG | 420 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,540 | 45.6% |
| LOAD_FAST | 1,120 | 33.1% |
| CALL_BUILTIN_O | 260 | 7.7% |
| CALL_LEN | 260 | 7.7% |
| COPY | 160 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,480 | 73.4% |
| POP_JUMP_IF_TRUE | 760 | 22.5% |
| UNARY_NOT | 140 | 4.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020 | 85.0% |
| LOAD_ATTR | 140 | 11.7% |
| TO_BOOL | 20 | 1.7% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 780 | 65.0% |
| POP_JUMP_IF_FALSE | 360 | 30.0% |
| UNARY_NOT | 60 | 5.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,840 | 78.0% |
| COPY | 500 | 21.2% |
| TO_BOOL | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,860 | 78.8% |
| POP_JUMP_IF_TRUE | 500 | 21.2% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,360 | 42.1% |
| STORE_FAST_LOAD_FAST | 2,220 | 39.6% |
| LOAD_FAST | 980 | 17.5% |
| TO_BOOL | 20 | 0.4% |
| CALL_BUILTIN_FAST | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,140 | 56.1% |
| POP_JUMP_IF_TRUE | 2,460 | 43.9% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 360 | 46.2% |
| BUILD_TUPLE | 220 | 28.2% |
| LOAD_FAST | 140 | 17.9% |
| RETURN_VALUE | 60 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 400 | 51.3% |
| STORE_DEREF | 220 | 28.2% |
| STORE_FAST | 160 | 20.5% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 9,000 | 75.1% |
| RETURN_VALUE | 1,620 | 13.5% |
| FOR_ITER_LIST | 1,220 | 10.2% |
| UNPACK_SEQUENCE | 120 | 1.0% |
| BINARY_SUBSCR_LIST_INT | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 6,300 | 52.6% |
| STORE_NAME | 4,540 | 37.9% |
| STORE_FAST | 1,140 | 9.5% |


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
|     deferred | 5,860 | 27.8% |
|          hit | 14,580 | 69.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 53.1% |
| Failure | 300 | 46.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 140 | 46.7% |
| or | 100 | 33.3% |
| power | 60 | 20.0% |


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
|     deferred | 125,830 | 90.5% |
|          hit | 12,360 | 8.9% |
|         miss | 380 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 13.6% |
| Failure | 380 | 86.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 340 | 89.5% |
| out of range | 40 | 10.5% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 27,638,120 | 46.1% |
|          hit | 32,296,935 | 53.9% |
|         miss | 4,400 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,480 | 14.2% |
| Failure | 8,965 | 85.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method wrapper | 3,875 | 43.2% |
| other | 2,945 | 32.8% |
| class no vectorcall | 820 | 9.1% |
| operator wrapper | 765 | 8.5% |
| cfunc noargs | 160 | 1.8% |
| meth descr varargs | 120 | 1.3% |
| code complex parameters | 80 | 0.9% |
| cfunc varargs keywords | 80 | 0.9% |
| init not python | 60 | 0.7% |
| wrong number arguments | 40 | 0.4% |
| init not simple | 20 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,480 | 6.3% |
|          hit | 21,700 | 93.1% |
|         miss | 60 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 75.0% |
| Failure | 20 | 25.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| list | 20 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,598,750 | 52.3% |
|          hit | 2,371,815 | 47.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 320 | 10.8% |
| Failure | 2,645 | 89.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 1,045 | 39.5% |
| dict values | 840 | 31.8% |
| dict items | 480 | 18.1% |
| itertools | 180 | 6.8% |
| ascii string | 80 | 3.0% |
| enumerate | 20 | 0.8% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 10,534,445 | 81.0% |
|        deopt | 20 | 0.0% |
|          hit | 2,469,030 | 19.0% |
|         miss | 2,220 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 720 | 12.5% |
| Failure | 5,020 | 87.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 4,560 | 90.8% |
| non object slot | 140 | 2.8% |
| shadowed | 120 | 2.4% |
| method | 60 | 1.2% |
| module attr not found | 60 | 1.2% |
| overridden | 20 | 0.4% |
| not managed dict | 20 | 0.4% |
| builtin class method | 20 | 0.4% |
| class method obj | 20 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,280 | 0.0% |
|        deopt | 620 | 0.0% |
|          hit | 78,683,335 | 100.0% |
|         miss | 17,440 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,640 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 2,668,020 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
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
|     deferred | 6,980 | 27.2% |
|          hit | 15,520 | 60.4% |
|         miss | 2,580 | 10.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 29.0% |
| Failure | 440 | 71.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overridden | 300 | 68.2% |
| no dict | 60 | 13.6% |
| overriding descriptor | 40 | 9.1% |
| not managed dict | 20 | 4.5% |
| class attr simple | 20 | 4.5% |


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
|     deferred | 820 | 5.4% |
|          hit | 14,120 | 93.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 88.9% |
| Failure | 20 | 11.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,680 | 0.0% |
|          hit | 8,064,065 | 100.0% |
|         miss | 300 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 580 | 82.9% |
| Failure | 120 | 17.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 60 | 50.0% |
| dict | 20 | 16.7% |
| mapping | 20 | 16.7% |
| set | 20 | 16.7% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120 | 0.9% |
|          hit | 12,760 | 98.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 204,704,950 | 47.9% |
| Not specialized | 81,498,890 | 19.1% |
| Specialized hits | 141,137,655 | 33.0% |
| Specialized misses | 27,380 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 27,638,120 | 67.5% |
| LOAD_ATTR | 10,534,445 | 25.7% |
| FOR_ITER | 2,598,750 | 6.4% |
| BINARY_SUBSCR | 125,830 | 0.3% |
| STORE_ATTR | 6,980 | 0.0% |
| BINARY_OP | 5,860 | 0.0% |
| LOAD_GLOBAL | 2,280 | 0.0% |
| TO_BOOL | 1,680 | 0.0% |
| COMPARE_OP | 1,480 | 0.0% |
| STORE_SUBSCR | 820 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,460 | 34.6% |
| LOAD_GLOBAL_BUILTIN | 7,980 | 29.1% |
| STORE_ATTR_INSTANCE_VALUE | 2,580 | 9.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,640 | 6.0% |
| CALL_BUILTIN_O | 1,420 | 5.2% |
| LOAD_ATTR_MODULE | 1,220 | 4.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 560 | 2.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 520 | 1.9% |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 1.8% |
| BINARY_SUBSCR_LIST_INT | 320 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 2,686,555 | 15.7% |
| Calls to Python functions inlined | 14,477,360 | 84.3% |
| Calls via PyEval_EvalFrame (total) | 2,686,555 | 15.7% |
| Calls via PyEval_EvalFrame (vector) | 2,684,455 | 15.6% |
| Calls via PyEval_EvalFrame (generator) | 2,100 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 420 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 2,683,315 | 15.6% |
| Calls via PyEval_EvalFrame (build class) | 720 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 5,020 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 540 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,540 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 3,688,240 | 21.5% |
| Frames pushed | 18,085,940 | 105.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 30,375,115 | 54.1% |
| Frees to freelist | 30,372,115 |  |
| Allocations | 25,740,500 | 45.9% |
| Allocations to 512 bytes | 25,727,040 | 45.8% |
| Allocations to 4 kbytes | 12,520 | 0.0% |
| Allocations over 4 kbytes | 940 | 0.0% |
| Frees | 25,582,045 |  |
| New values | 3,280 |  |
| Interpreter increfs | 218,889,750 | 61.1% |
| Interpreter decrefs | 253,990,480 | 61.3% |
| Increfs | 139,499,825 | 38.9% |
| Decrefs | 160,155,139 | 38.7% |
| Materialize dict (on request) | 1,040 | 31.7% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 15,949,551 |  |
| Method cache misses | 99,909 |  |
| Method cache collisions | 187,000 |  |
| Method cache dunder hits | 22,593,438 |  |
| Method cache dunder misses | 92,357 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 80 | 2,400 | 774,680 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 32,205 |  |
| Traces created | 300 | 0.9% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 31,905 | 99.1% |
| Inner loop found | 40 | 0.1% |
| Recursive call | 0 | 0.0% |
| Traces executed | 6,318,970 |  |
| Uops executed | 188,233,060 | 29.79 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 60 | 20.0% |
| <= 32 | 180 | 60.0% |
| <= 64 | 60 | 20.0% |


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
| <= 16 | 120 | 40.0% |
| <= 32 | 140 | 46.7% |
| <= 64 | 40 | 13.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 120 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,277,760 | 36.0% |
| <= 16 | 9,730 | 0.2% |
| <= 32 | 168,640 | 2.7% |
| <= 64 | 3,656,960 | 57.9% |
| <= 128 | 740 | 0.0% |
| <= 256 | 204,980 | 3.2% |
| <= 512 | 20 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 20 | 0.0% |


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
| FOR_ITER | 31,905 |
| CALL | 80 |
| LOAD_ATTR | 60 |


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
