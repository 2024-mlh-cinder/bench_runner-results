
# Pystats results

- benchmark: typing_runtime_protocols
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 14aea56
- commit date: 2023-11-17T15:11:51-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_GLOBAL_MODULE | 55,769,100 | 12.9% | 12.9% | 0.0% |
| LOAD_FAST | 53,685,016 | 12.4% | 25.4% |  |
| CALL | 27,992,760 | 6.5% | 31.9% |  |
| STORE_FAST | 26,168,208 | 6.1% | 37.9% |  |
| LOAD_GLOBAL_BUILTIN | 23,655,132 | 5.5% | 43.4% | 0.0% |
| IS_OP | 21,965,560 | 5.1% | 48.5% |  |
| POP_JUMP_IF_FALSE | 20,460,068 | 4.7% | 53.3% |  |
| POP_JUMP_IF_TRUE | 19,882,200 | 4.6% | 57.9% |  |
| LOAD_FAST_LOAD_FAST | 19,824,144 | 4.6% | 62.5% |  |
| RESUME_CHECK | 17,304,288 | 4.0% | 66.5% | 0.0% |
| RETURN_VALUE | 16,463,328 | 3.8% | 70.3% |  |
| LOAD_CONST | 13,170,400 | 3.1% | 73.4% |  |
| LOAD_ATTR | 10,657,920 | 2.5% | 75.8% |  |
| CALL_PY_EXACT_ARGS | 9,552,628 | 2.2% | 78.0% | 0.0% |
| CONTAINS_OP | 8,471,220 | 2.0% | 80.0% |  |
| TO_BOOL_BOOL | 8,031,488 | 1.9% | 81.9% |  |
| CALL_BUILTIN_FAST | 8,006,516 | 1.9% | 83.7% | 0.0% |
| ENTER_EXECUTOR | 6,960,580 | 1.6% | 85.3% |  |
| CALL_TYPE_1 | 4,769,324 | 1.1% | 86.4% |  |
| FOR_ITER_TUPLE | 4,659,736 | 1.1% | 87.5% |  |
| NOP | 4,446,524 | 1.0% | 88.6% |  |
| GET_ITER | 4,446,072 | 1.0% | 89.6% |  |
| POP_TOP | 3,851,036 | 0.9% | 90.5% |  |
| INTERPRETER_EXIT | 2,686,228 | 0.6% | 91.1% |  |
| RETURN_CONST | 2,685,800 | 0.6% | 91.7% |  |
| LOAD_DEREF | 2,673,900 | 0.6% | 92.4% |  |
| COPY_FREE_VARS | 2,669,040 | 0.6% | 93.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,668,840 | 0.6% | 93.6% | 0.1% |
| LOAD_SUPER_ATTR_METHOD | 2,667,960 | 0.6% | 94.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,393,032 | 0.6% | 94.8% | 0.0% |
| BUILD_MAP | 2,389,916 | 0.6% | 95.3% |  |
| JUMP_FORWARD | 2,388,832 | 0.6% | 95.9% |  |
| CALL_PY_WITH_DEFAULTS | 2,386,912 | 0.6% | 96.4% |  |
| LOAD_ATTR_CLASS | 2,383,932 | 0.6% | 97.0% |  |
| PUSH_NULL | 2,072,172 | 0.5% | 97.5% |  |
| FOR_ITER | 2,062,160 | 0.5% | 97.9% |  |
| CHECK_EXC_MATCH | 1,844,780 | 0.4% | 98.4% |  |
| POP_EXCEPT | 1,844,780 | 0.4% | 98.8% |  |
| PUSH_EXC_INFO | 1,844,780 | 0.4% | 99.2% |  |
| RAISE_VARARGS | 1,843,200 | 0.4% | 99.6% |  |
| POP_JUMP_IF_NONE | 546,952 | 0.1% | 99.8% |  |
| FOR_ITER_LIST | 252,440 | 0.1% | 99.8% |  |
| SWAP | 137,940 | 0.0% | 99.9% |  |
| BINARY_SUBSCR | 126,256 | 0.0% | 99.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 30,000 | 0.0% | 99.9% | 1.6% |
| LOAD_NAME | 26,720 | 0.0% | 99.9% |  |
| LOAD_ATTR_MODULE | 25,708 | 0.0% | 99.9% | 4.7% |
| LOAD_ATTR_METHOD_NO_DICT | 24,840 | 0.0% | 99.9% |  |
| STORE_NAME | 20,980 | 0.0% | 99.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 17,840 | 0.0% | 99.9% | 14.5% |
| JUMP_BACKWARD | 14,092 | 0.0% | 99.9% |  |
| COPY | 13,840 | 0.0% | 99.9% |  |
| COMPARE_OP_INT | 11,820 | 0.0% | 99.9% |  |
| EXTENDED_ARG | 11,420 | 0.0% | 99.9% |  |
| CALL_LEN | 11,120 | 0.0% | 99.9% |  |
| POP_JUMP_IF_NOT_NONE | 10,816 | 0.0% | 99.9% |  |
| CALL_ISINSTANCE | 10,564 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 10,480 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 9,800 | 0.0% | 100.0% | 2.9% |
| BUILD_LIST | 8,380 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 8,280 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 8,080 | 0.0% | 100.0% | 0.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 7,720 | 0.0% | 100.0% | 7.3% |
| STORE_SUBSCR_DICT | 7,600 | 0.0% | 100.0% |  |
| MAP_ADD | 7,440 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 6,780 | 0.0% | 100.0% |  |
| BINARY_OP | 6,400 | 0.0% | 100.0% |  |
| STORE_ATTR | 5,840 | 0.0% | 100.0% |  |
| LIST_APPEND | 5,740 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 5,580 | 0.0% | 100.0% | 25.4% |
| TO_BOOL_STR | 5,400 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 5,280 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,020 | 0.0% | 100.0% | 10.4% |
| LOAD_ATTR_SLOT | 4,940 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 4,460 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 4,300 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 4,300 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_INT | 3,900 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 3,840 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 3,500 | 0.0% | 100.0% |  |
| BUILD_STRING | 3,380 | 0.0% | 100.0% |  |
| BINARY_SLICE | 3,320 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 3,300 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 3,180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 3,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 3,080 | 0.0% | 100.0% | 1.9% |
| CALL_LIST_APPEND | 3,040 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 2,840 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 2,740 | 0.0% | 100.0% |  |
| CALL_KW | 2,720 | 0.0% | 100.0% |  |
| MAKE_CELL | 2,620 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 2,440 | 0.0% | 100.0% |  |
| STORE_DEREF | 2,400 | 0.0% | 100.0% |  |
| TO_BOOL | 2,380 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 2,360 | 0.0% | 100.0% | 11.0% |
| BINARY_SUBSCR_LIST_INT | 2,340 | 0.0% | 100.0% | 13.7% |
| BEFORE_WITH | 2,160 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 2,140 | 0.0% | 100.0% |  |
| RESUME | 1,700 | 0.0% | 100.0% | 1.2% |
| CALL_ALLOC_AND_ENTER_INIT | 1,700 | 0.0% | 100.0% | 1.2% |
| BUILD_CONST_KEY_MAP | 1,700 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 1,680 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,660 | 0.0% | 100.0% | 2.4% |
| YIELD_VALUE | 1,620 | 0.0% | 100.0% |  |
| LIST_EXTEND | 1,580 | 0.0% | 100.0% |  |
| COMPARE_OP | 1,560 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 1,400 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 1,380 | 0.0% | 100.0% |  |
| IMPORT_NAME | 1,280 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 1,200 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 1,160 | 0.0% | 100.0% | 3.4% |
| BINARY_SUBSCR_GETITEM | 1,140 | 0.0% | 100.0% |  |
| LOAD_ATTR_PROPERTY | 1,100 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 1,100 | 0.0% | 100.0% |  |
| DICT_MERGE | 1,060 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 1,020 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 1,000 | 0.0% | 100.0% |  |
| STORE_ATTR_SLOT | 920 | 0.0% | 100.0% |  |
| IMPORT_FROM | 900 | 0.0% | 100.0% |  |
| RERAISE | 880 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 780 | 0.0% | 100.0% |  |
| CALL_STR_1 | 760 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 720 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 600 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 520 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 440 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 400 | 0.0% | 100.0% |  |
| DICT_UPDATE | 300 | 0.0% | 100.0% |  |
| BUILD_SLICE | 280 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 260 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 240 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 240 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 220 | 0.0% | 100.0% |  |
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
| LOAD_GLOBAL_MODULE IS_OP | 20,118,880 | 4.7% | 4.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 14,059,424 | 3.3% | 7.9% |
| IS_OP POP_JUMP_IF_FALSE | 13,509,796 | 3.1% | 11.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 12,216,496 | 2.8% | 13.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 11,969,776 | 2.8% | 16.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 11,935,600 | 2.8% | 19.4% |
| LOAD_FAST CALL | 11,385,288 | 2.6% | 22.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 9,564,084 | 2.2% | 24.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,551,648 | 2.2% | 26.5% |
| CALL CALL | 8,463,420 | 2.0% | 28.5% |
| IS_OP POP_JUMP_IF_TRUE | 8,455,304 | 2.0% | 30.4% |
| CALL RETURN_VALUE | 8,454,764 | 2.0% | 32.4% |
| LOAD_FAST LOAD_CONST | 7,741,028 | 1.8% | 34.2% |
| RETURN_VALUE STORE_FAST | 7,700,688 | 1.8% | 36.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 7,438,112 | 1.7% | 37.7% |
| STORE_FAST LOAD_FAST | 7,384,276 | 1.7% | 39.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 7,162,440 | 1.7% | 41.1% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 6,074,696 | 1.4% | 42.5% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR | 6,073,444 | 1.4% | 43.9% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 6,073,276 | 1.4% | 45.3% |
| LOAD_ATTR CONTAINS_OP | 6,072,504 | 1.4% | 46.7% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 6,070,312 | 1.4% | 48.1% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 5,952,756 | 1.4% | 49.5% |
| LOAD_CONST LOAD_CONST | 5,348,292 | 1.2% | 50.7% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,345,188 | 1.2% | 52.0% |
| LOAD_CONST CALL_BUILTIN_FAST | 5,332,532 | 1.2% | 53.2% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 5,328,964 | 1.2% | 54.4% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 5,328,944 | 1.2% | 55.7% |
| STORE_FAST LOAD_GLOBAL_MODULE | 4,775,724 | 1.1% | 56.8% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 4,769,644 | 1.1% | 57.9% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 4,769,364 | 1.1% | 59.0% |
| LOAD_FAST CALL_TYPE_1 | 4,769,044 | 1.1% | 60.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 4,515,244 | 1.0% | 61.2% |
| CALL STORE_FAST | 4,436,412 | 1.0% | 62.2% |
| STORE_FAST NOP | 4,436,224 | 1.0% | 63.2% |
| ENTER_EXECUTOR CALL | 3,692,440 | 0.9% | 64.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 2,685,880 | 0.6% | 64.7% |
| RESUME_CHECK LOAD_FAST | 2,680,040 | 0.6% | 65.3% |
| RETURN_CONST INTERPRETER_EXIT | 2,674,000 | 0.6% | 65.9% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 2,669,100 | 0.6% | 66.6% |
| LOAD_DEREF LOAD_FAST | 2,668,740 | 0.6% | 67.2% |
| COPY_FREE_VARS RESUME_CHECK | 2,668,600 | 0.6% | 67.8% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 2,668,368 | 0.6% | 68.4% |
| CACHE COPY_FREE_VARS | 2,668,320 | 0.6% | 69.0% |
| RETURN_VALUE TO_BOOL_BOOL | 2,668,180 | 0.6% | 69.6% |
| CALL_BUILTIN_FAST RETURN_VALUE | 2,667,968 | 0.6% | 70.3% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 2,667,920 | 0.6% | 70.9% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 2,667,840 | 0.6% | 71.5% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 2,665,840 | 0.6% | 72.1% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST | 2,664,740 | 0.6% | 72.7% |
| LOAD_ATTR LOAD_FAST | 2,510,928 | 0.6% | 73.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 2,394,104 | 0.6% | 73.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,393,072 | 0.6% | 74.4% |
| FOR_ITER_TUPLE STORE_FAST | 2,388,184 | 0.6% | 75.0% |
| GET_ITER FOR_ITER_TUPLE | 2,387,252 | 0.6% | 75.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 2,386,912 | 0.6% | 76.1% |
| LOAD_GLOBAL_MODULE CALL_METHOD_DESCRIPTOR_FAST | 2,386,632 | 0.6% | 76.6% |
| LOAD_CONST CALL | 2,386,552 | 0.6% | 77.2% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_MODULE | 2,386,352 | 0.6% | 77.8% |
| STORE_FAST JUMP_FORWARD | 2,385,872 | 0.6% | 78.3% |
| LOAD_GLOBAL_MODULE STORE_FAST | 2,385,552 | 0.6% | 78.9% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 2,384,932 | 0.6% | 79.4% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 2,384,772 | 0.6% | 80.0% |
| CALL GET_ITER | 2,384,532 | 0.6% | 80.5% |
| LOAD_FAST STORE_FAST | 2,384,472 | 0.6% | 81.1% |
| NOP LOAD_GLOBAL_BUILTIN | 2,384,252 | 0.6% | 81.6% |
| BUILD_MAP STORE_FAST | 2,384,132 | 0.6% | 82.2% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 2,384,092 | 0.6% | 82.7% |
| JUMP_FORWARD LOAD_GLOBAL_MODULE | 2,384,072 | 0.6% | 83.3% |
| CALL_TYPE_1 CALL_PY_EXACT_ARGS | 2,384,032 | 0.6% | 83.8% |
| CALL CONTAINS_OP | 2,383,872 | 0.6% | 84.4% |
| CALL_METHOD_DESCRIPTOR_FAST RETURN_VALUE | 2,383,852 | 0.6% | 84.9% |
| CALL_TYPE_1 STORE_FAST | 2,383,852 | 0.6% | 85.5% |
| LOAD_ATTR_CLASS LOAD_FAST_LOAD_FAST | 2,383,852 | 0.6% | 86.0% |
| RESUME_CHECK BUILD_MAP | 2,383,852 | 0.6% | 86.6% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 2,383,832 | 0.6% | 87.2% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR_CLASS | 2,383,832 | 0.6% | 87.7% |
| ENTER_EXECUTOR FOR_ITER_TUPLE | 2,266,392 | 0.5% | 88.2% |
| FOR_ITER_TUPLE LOAD_GLOBAL_MODULE | 2,261,272 | 0.5% | 88.8% |
| LOAD_GLOBAL_MODULE RETURN_VALUE | 2,261,252 | 0.5% | 89.3% |
| LOAD_FAST LOAD_ATTR | 2,189,496 | 0.5% | 89.8% |
| LOAD_FAST PUSH_NULL | 2,056,892 | 0.5% | 90.3% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 2,055,460 | 0.5% | 90.7% |
| FOR_ITER STORE_FAST | 2,055,312 | 0.5% | 91.2% |
| NOP LOAD_FAST | 2,054,492 | 0.5% | 91.7% |
| GET_ITER FOR_ITER | 2,050,940 | 0.5% | 92.2% |
| LOAD_ATTR GET_ITER | 2,050,900 | 0.5% | 92.6% |
| LOAD_GLOBAL_MODULE CALL | 2,050,200 | 0.5% | 93.1% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 2,050,132 | 0.5% | 93.6% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 2,048,472 | 0.5% | 94.1% |
| POP_TOP RETURN_CONST | 1,851,620 | 0.4% | 94.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,847,660 | 0.4% | 94.9% |
| POP_JUMP_IF_FALSE POP_TOP | 1,847,120 | 0.4% | 95.4% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 1,844,780 | 0.4% | 95.8% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 1,844,760 | 0.4% | 96.2% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 1,844,740 | 0.4% | 96.6% |
| POP_TOP POP_EXCEPT | 1,843,340 | 0.4% | 97.1% |
| POP_EXCEPT POP_TOP | 1,843,200 | 0.4% | 97.5% |
| CALL RAISE_VARARGS | 1,843,200 | 0.4% | 97.9% |
| LOAD_FAST_LOAD_FAST IS_OP | 1,843,200 | 0.4% | 98.3% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,900 | 87.3% |
| LOAD_FAST | 420 | 12.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 740 | 22.3% |
| SWAP | 740 | 22.3% |
| CALL_PY_EXACT_ARGS | 540 | 16.3% |
| STORE_FAST | 480 | 14.5% |
| BUILD_TUPLE | 360 | 10.8% |


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
| RESUME_CHECK | 16,268 | 0.6% |
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
| LOAD_FAST | 123,436 | 97.8% |
| LOAD_CONST | 2,160 | 1.7% |
| BINARY_SUBSCR | 380 | 0.3% |
| BUILD_SLICE | 280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 123,880 | 98.1% |
| STORE_FAST | 480 | 0.4% |
| POP_JUMP_IF_NOT_NONE | 436 | 0.3% |
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
| LOAD_FAST | 2,460 | 57.2% |
| CONVERT_VALUE | 1,380 | 32.1% |
| LOAD_ATTR | 220 | 5.1% |
| STORE_FAST_LOAD_FAST | 220 | 5.1% |
| LOAD_ATTR_MODULE | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,600 | 83.7% |
| BUILD_STRING | 660 | 15.3% |
| LOAD_FAST | 40 | 0.9% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,384,532 | 53.6% |
| LOAD_ATTR | 2,050,900 | 46.1% |
| LOAD_FAST | 6,100 | 0.1% |
| BUILD_TUPLE | 1,180 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 2,387,252 | 53.7% |
| FOR_ITER | 2,050,940 | 46.1% |
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
| RETURN_VALUE | 10,708 | 0.4% |
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
| LOAD_CONST | 10,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 5,500 | 52.5% |
| SET_FUNCTION_ATTRIBUTE | 3,120 | 29.8% |
| LOAD_CONST | 760 | 7.3% |
| CALL | 400 | 3.8% |
| CALL_BUILTIN_FAST | 240 | 2.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,436,224 | 99.8% |
| POP_TOP | 1,820 | 0.0% |
| RESUME_CHECK | 1,820 | 0.0% |
| POP_JUMP_IF_FALSE | 1,480 | 0.0% |
| NOP | 980 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,384,252 | 53.6% |
| LOAD_FAST | 2,054,492 | 46.2% |
| LOAD_GLOBAL_MODULE | 4,360 | 0.1% |
| LOAD_CONST | 1,400 | 0.0% |
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
| POP_JUMP_IF_FALSE | 1,847,120 | 48.0% |
| POP_EXCEPT | 1,843,200 | 47.9% |
| SWAP | 126,040 | 3.3% |
| CALL | 8,060 | 0.2% |
| RETURN_CONST | 6,040 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,851,620 | 48.1% |
| POP_EXCEPT | 1,843,340 | 47.9% |
| RETURN_VALUE | 125,060 | 3.2% |
| LOAD_FAST | 8,200 | 0.2% |
| ENTER_EXECUTOR | 4,676 | 0.1% |


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
| LOAD_FAST | 2,056,892 | 99.3% |
| LOAD_ATTR_MODULE | 8,440 | 0.4% |
| LOAD_NAME | 2,600 | 0.1% |
| LOAD_ATTR | 2,300 | 0.1% |
| LOAD_BUILD_CLASS | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,050,132 | 98.9% |
| LOAD_FAST | 13,800 | 0.7% |
| LOAD_CONST | 3,240 | 0.2% |
| CALL | 1,840 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,260 | 0.1% |


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
| CALL | 8,454,764 | 51.4% |
| CALL_BUILTIN_FAST | 2,667,968 | 16.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,383,852 | 14.5% |
| LOAD_GLOBAL_MODULE | 2,261,252 | 13.7% |
| LOAD_FAST | 545,892 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,700,688 | 46.8% |
| LOAD_GLOBAL_MODULE | 6,070,312 | 36.9% |
| TO_BOOL_BOOL | 2,668,180 | 16.2% |
| INTERPRETER_EXIT | 10,708 | 0.1% |
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

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,700 | 26.6% |
| LOAD_GLOBAL_MODULE | 1,440 | 22.5% |
| BINARY_OP_SUBTRACT_INT | 680 | 10.6% |
| LOAD_FAST | 600 | 9.4% |
| LOAD_NAME | 380 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,440 | 22.5% |
| STORE_FAST | 980 | 15.3% |
| LOAD_CONST | 660 | 10.3% |
| SWAP | 500 | 7.8% |
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
| RESUME_CHECK | 2,383,852 | 99.7% |
| LOAD_CONST | 3,824 | 0.2% |
| LOAD_FAST | 560 | 0.0% |
| LOAD_DEREF | 220 | 0.0% |
| FOR_ITER_LIST | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,384,132 | 99.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,020 | 0.1% |
| CALL_BUILTIN_FAST | 1,344 | 0.1% |
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
| LOAD_CONST | 2,720 | 80.5% |
| FORMAT_SIMPLE | 660 | 19.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,280 | 37.9% |
| LOAD_FAST | 880 | 26.0% |
| LOAD_CONST | 440 | 13.0% |
| LIST_APPEND | 340 | 10.1% |
| YIELD_VALUE | 220 | 6.5% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,980 | 48.1% |
| BINARY_OP_ADD_UNICODE | 800 | 9.7% |
| LOAD_GLOBAL_BUILTIN | 560 | 6.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 540 | 6.5% |
| LOAD_FAST_LOAD_FAST | 440 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,980 | 23.9% |
| GET_ITER | 1,180 | 14.3% |
| STORE_FAST | 1,020 | 12.3% |
| LOAD_FAST | 700 | 8.5% |
| RETURN_VALUE | 640 | 7.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,385,288 | 40.7% |
| CALL | 8,463,420 | 30.2% |
| ENTER_EXECUTOR | 3,692,440 | 13.2% |
| LOAD_CONST | 2,386,552 | 8.5% |
| LOAD_GLOBAL_MODULE | 2,050,200 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 8,463,420 | 30.2% |
| RETURN_VALUE | 8,454,764 | 30.2% |
| STORE_FAST | 4,436,412 | 15.8% |
| GET_ITER | 2,384,532 | 8.5% |
| CONTAINS_OP | 2,383,872 | 8.5% |


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
| LOAD_ATTR | 6,072,504 | 71.7% |
| CALL | 2,383,872 | 28.1% |
| LOAD_FAST_LOAD_FAST | 6,284 | 0.1% |
| LOAD_FAST | 3,260 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,800 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,074,696 | 71.7% |
| POP_JUMP_IF_FALSE | 2,394,104 | 28.3% |
| RETURN_VALUE | 1,420 | 0.0% |
| EXTENDED_ARG | 740 | 0.0% |
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
| COMPARE_OP_INT | 2,080 | 15.0% |
| COMPARE_OP_STR | 2,060 | 14.9% |
| SWAP | 1,740 | 12.6% |
| CALL_BUILTIN_FAST | 1,740 | 12.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,500 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,800 | 56.4% |
| TO_BOOL_STR | 2,160 | 15.6% |
| COMPARE_OP_STR | 1,740 | 12.6% |
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
| ENTER_EXECUTOR | 40 | 25.0% |
| STORE_NAME | 40 | 25.0% |
| FOR_ITER | 20 | 12.5% |

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
| POP_JUMP_IF_TRUE | 5,952,756 | 85.5% |
| POP_JUMP_IF_NONE | 540,372 | 7.8% |
| FOR_ITER_LIST | 245,080 | 3.5% |
| ENTER_EXECUTOR | 204,936 | 2.9% |
| POP_TOP | 4,676 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,692,440 | 53.0% |
| FOR_ITER_TUPLE | 2,266,392 | 32.6% |
| CALL_PY_WITH_DEFAULTS | 335,700 | 4.8% |
| FOR_ITER_LIST | 246,740 | 3.5% |
| RETURN_CONST | 205,172 | 2.9% |


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
| ENTER_EXECUTOR | 2,600 | 22.8% |
| POP_JUMP_IF_FALSE | 2,000 | 17.5% |
| JUMP_FORWARD | 1,040 | 9.1% |
| FOR_ITER_LIST | 960 | 8.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,050,940 | 99.5% |
| JUMP_BACKWARD | 7,840 | 0.4% |
| FOR_ITER | 2,020 | 0.1% |
| EXTENDED_ARG | 700 | 0.0% |
| LOAD_FAST | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,055,312 | 99.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,300 | 0.1% |
| FOR_ITER | 2,020 | 0.1% |
| STORE_NAME | 720 | 0.0% |
| RETURN_CONST | 668 | 0.0% |


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
| LOAD_GLOBAL_MODULE | 20,118,880 | 91.6% |
| LOAD_FAST_LOAD_FAST | 1,843,200 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 1,860 | 0.0% |
| LOAD_FAST | 620 | 0.0% |
| LOAD_CONST | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,509,796 | 61.5% |
| POP_JUMP_IF_TRUE | 8,455,304 | 38.5% |
| LOAD_FAST | 380 | 0.0% |
| COPY | 40 | 0.0% |
| STORE_FAST | 40 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 3,572 | 25.3% |
| LIST_APPEND | 2,460 | 17.5% |
| POP_TOP | 2,380 | 16.9% |
| STORE_SUBSCR_DICT | 980 | 7.0% |
| FOR_ITER_LIST | 960 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 7,840 | 55.6% |
| FOR_ITER_TUPLE | 2,952 | 20.9% |
| FOR_ITER_LIST | 1,560 | 11.1% |
| ENTER_EXECUTOR | 700 | 5.0% |
| FOR_ITER_RANGE | 640 | 4.5% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,385,872 | 99.9% |
| EXTENDED_ARG | 1,040 | 0.0% |
| POP_TOP | 480 | 0.0% |
| LOAD_FAST | 360 | 0.0% |
| COMPARE_OP_STR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,384,072 | 99.8% |
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
| CALL_METHOD_DESCRIPTOR_FAST | 2,220 | 38.7% |
| LOAD_FAST | 1,420 | 24.7% |
| CALL | 1,040 | 18.1% |
| BUILD_TUPLE | 560 | 9.8% |
| BUILD_STRING | 340 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,280 | 57.1% |
| JUMP_BACKWARD | 2,460 | 42.9% |


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
| LOAD_FAST_LOAD_FAST | 6,073,444 | 57.0% |
| LOAD_GLOBAL_BUILTIN | 2,384,932 | 22.4% |
| LOAD_FAST | 2,189,496 | 20.5% |
| LOAD_ATTR | 5,068 | 0.0% |
| LOAD_NAME | 1,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 6,072,504 | 57.0% |
| LOAD_FAST | 2,510,928 | 23.6% |
| GET_ITER | 2,050,900 | 19.2% |
| LOAD_ATTR_METHOD_NO_DICT | 5,240 | 0.0% |
| LOAD_ATTR | 5,068 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,741,028 | 58.8% |
| LOAD_CONST | 5,348,292 | 40.6% |
| STORE_NAME | 10,940 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 7,400 | 0.1% |
| STORE_FAST | 6,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,348,292 | 40.6% |
| CALL_BUILTIN_FAST | 5,332,532 | 40.5% |
| CALL | 2,386,552 | 18.1% |
| LOAD_FAST | 12,560 | 0.1% |
| MAKE_FUNCTION | 10,480 | 0.1% |


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
| LOAD_GLOBAL_BUILTIN | 11,969,776 | 22.3% |
| LOAD_GLOBAL_MODULE | 11,935,600 | 22.2% |
| POP_JUMP_IF_FALSE | 9,564,084 | 17.8% |
| STORE_FAST | 7,384,276 | 13.8% |
| RESUME_CHECK | 2,680,040 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 14,059,424 | 26.2% |
| CALL | 11,385,288 | 21.2% |
| LOAD_CONST | 7,741,028 | 14.4% |
| CALL_TYPE_1 | 4,769,044 | 8.9% |
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
| LOAD_GLOBAL_MODULE | 7,438,112 | 37.5% |
| POP_JUMP_IF_TRUE | 6,073,276 | 30.6% |
| LOAD_ATTR_CLASS | 2,383,852 | 12.0% |
| PUSH_NULL | 2,050,132 | 10.3% |
| POP_JUMP_IF_FALSE | 1,847,660 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 6,073,444 | 30.6% |
| CALL_PY_EXACT_ARGS | 4,769,644 | 24.1% |
| CALL_BUILTIN_FAST | 2,668,368 | 13.5% |
| LOAD_GLOBAL_MODULE | 2,383,832 | 12.0% |
| CALL_PY_WITH_DEFAULTS | 2,048,472 | 10.3% |


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
| LOAD_NAME | 6,520 | 24.4% |
| STORE_NAME | 6,260 | 23.4% |
| STORE_FAST | 3,660 | 13.7% |
| LOAD_CONST | 2,160 | 8.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,120 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 6,520 | 24.4% |
| LOAD_CONST | 4,800 | 18.0% |
| LOAD_ATTR_MODULE | 3,380 | 12.6% |
| PUSH_NULL | 2,600 | 9.7% |
| LOAD_ATTR | 1,840 | 6.9% |


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
| LOAD_CONST | 4,080 | 54.8% |
| LOAD_FAST_LOAD_FAST | 1,360 | 18.3% |
| LOAD_NAME | 680 | 9.1% |
| LOAD_FAST | 540 | 7.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 320 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,260 | 43.8% |
| EXTENDED_ARG | 1,560 | 21.0% |
| ENTER_EXECUTOR | 1,400 | 18.8% |
| JUMP_BACKWARD | 940 | 12.6% |
| DICT_UPDATE | 220 | 3.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 13,509,796 | 66.0% |
| TO_BOOL_BOOL | 2,685,880 | 13.1% |
| CONTAINS_OP | 2,394,104 | 11.7% |
| CHECK_EXC_MATCH | 1,844,780 | 9.0% |
| COMPARE_OP_INT | 7,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,564,084 | 46.7% |
| LOAD_GLOBAL_BUILTIN | 4,515,244 | 22.1% |
| LOAD_GLOBAL_MODULE | 2,055,460 | 10.0% |
| LOAD_FAST_LOAD_FAST | 1,847,660 | 9.0% |
| POP_TOP | 1,847,120 | 9.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 543,172 | 99.3% |
| LOAD_GLOBAL_MODULE | 1,420 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,400 | 0.3% |
| LOAD_ATTR | 380 | 0.1% |
| LOAD_ATTR_MODULE | 360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 540,372 | 98.8% |
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
| LOAD_FAST | 6,240 | 57.7% |
| CALL_BUILTIN_FAST | 1,440 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,340 | 12.4% |
| LOAD_FAST_CHECK | 940 | 8.7% |
| BINARY_SUBSCR | 436 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,500 | 50.9% |
| LOAD_GLOBAL_MODULE | 1,600 | 14.8% |
| ENTER_EXECUTOR | 1,140 | 10.5% |
| NOP | 940 | 8.7% |
| POP_TOP | 456 | 4.2% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 8,455,304 | 42.5% |
| CONTAINS_OP | 6,074,696 | 30.6% |
| TO_BOOL_BOOL | 5,345,188 | 26.9% |
| TO_BOOL_STR | 2,260 | 0.0% |
| COMPARE_OP_INT | 1,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,073,276 | 30.5% |
| ENTER_EXECUTOR | 5,952,756 | 29.9% |
| LOAD_GLOBAL_BUILTIN | 5,328,944 | 26.8% |
| LOAD_GLOBAL_MODULE | 2,386,352 | 12.0% |
| LOAD_FAST | 130,680 | 0.7% |


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
| ENTER_EXECUTOR | 205,172 | 7.6% |
| STORE_ATTR_INSTANCE_VALUE | 4,240 | 0.2% |
| RESUME_CHECK | 1,520 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,674,000 | 99.6% |
| POP_TOP | 6,040 | 0.2% |
| TO_BOOL_BOOL | 2,640 | 0.1% |
| EXIT_INIT_CHECK | 1,680 | 0.1% |
| STORE_FAST | 1,020 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,120 | 94.5% |
| SET_FUNCTION_ATTRIBUTE | 180 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,180 | 35.8% |
| STORE_NAME | 1,140 | 34.5% |
| CALL | 380 | 11.5% |
| LOAD_GLOBAL_MODULE | 360 | 10.9% |
| SET_FUNCTION_ATTRIBUTE | 180 | 5.5% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,660 | 62.7% |
| LOAD_FAST_LOAD_FAST | 840 | 14.4% |
| SWAP | 500 | 8.6% |
| STORE_ATTR | 440 | 7.5% |
| LOAD_ATTR | 220 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,860 | 49.0% |
| NOP | 680 | 11.6% |
| LOAD_CONST | 580 | 9.9% |
| STORE_ATTR | 440 | 7.5% |
| LOAD_GLOBAL_MODULE | 380 | 6.5% |


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
| RETURN_VALUE | 7,700,688 | 29.4% |
| CALL | 4,436,412 | 17.0% |
| FOR_ITER_TUPLE | 2,388,184 | 9.1% |
| LOAD_GLOBAL_MODULE | 2,385,552 | 9.1% |
| LOAD_FAST | 2,384,472 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,384,276 | 28.2% |
| LOAD_GLOBAL_BUILTIN | 7,162,440 | 27.4% |
| LOAD_GLOBAL_MODULE | 4,775,724 | 18.3% |
| NOP | 4,436,224 | 17.0% |
| JUMP_FORWARD | 2,385,872 | 9.1% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 3,660 | 82.1% |
| UNPACK_SEQUENCE_TUPLE | 400 | 9.0% |
| COPY | 340 | 7.6% |
| UNPACK_SEQUENCE | 60 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,240 | 50.2% |
| LOAD_FAST_LOAD_FAST | 580 | 13.0% |
| NOP | 520 | 11.7% |
| STORE_FAST | 400 | 9.0% |
| LOAD_NAME | 340 | 7.6% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 5,500 | 26.2% |
| LOAD_CONST | 3,800 | 18.1% |
| CALL | 1,600 | 7.6% |
| LOAD_NAME | 1,160 | 5.5% |
| SET_FUNCTION_ATTRIBUTE | 1,140 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,940 | 52.1% |
| LOAD_NAME | 6,260 | 29.8% |
| STORE_NAME | 880 | 4.2% |
| RETURN_CONST | 760 | 3.6% |
| LOAD_BUILD_CLASS | 640 | 3.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 123,880 | 89.8% |
| LOAD_FAST_AND_CLEAR | 3,100 | 2.2% |
| BUILD_LIST | 3,020 | 2.2% |
| FOR_ITER_TUPLE | 2,720 | 2.0% |
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

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,020 | 63.0% |
| CALL | 360 | 22.2% |
| BUILD_STRING | 220 | 13.6% |
| BINARY_SUBSCR_DICT | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,520 | 93.8% |
| STORE_FAST | 100 | 6.2% |


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
| LOAD_CONST | 3,280 | 48.4% |
| LOAD_FAST_LOAD_FAST | 2,160 | 31.9% |
| CALL_METHOD_DESCRIPTOR_O | 560 | 8.3% |
| BINARY_SUBSCR_LIST_INT | 360 | 5.3% |
| BINARY_OP | 240 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,760 | 26.0% |
| STORE_SUBSCR_DICT | 1,360 | 20.1% |
| BUILD_TUPLE | 800 | 11.8% |
| LOAD_NAME | 800 | 11.8% |
| LOAD_CONST | 580 | 8.6% |


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
| LOAD_FAST | 1,600 | 74.8% |
| LOAD_CONST | 360 | 16.8% |
| LOAD_FAST_LOAD_FAST | 120 | 5.6% |
| BUILD_TUPLE | 60 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,020 | 47.7% |
| STORE_FAST | 560 | 26.2% |
| LOAD_FAST | 180 | 8.4% |
| CALL_BUILTIN_CLASS | 180 | 8.4% |
| LOAD_CONST | 120 | 5.6% |


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
| LOAD_CONST | 3,080 | 98.7% |
| BINARY_SUBSCR | 40 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 860 | 27.6% |
| LOAD_GLOBAL_MODULE | 820 | 26.3% |
| RETURN_VALUE | 460 | 14.7% |
| CALL_BUILTIN_O | 400 | 12.8% |
| LOAD_FAST | 120 | 3.8% |


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
| LOAD_FAST | 2,665,840 | 99.9% |
| LOAD_CONST | 1,840 | 0.1% |
| BUILD_TUPLE | 460 | 0.0% |
| PUSH_NULL | 380 | 0.0% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,667,840 | 100.0% |
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
| LOAD_CONST | 5,332,532 | 66.6% |
| LOAD_FAST_LOAD_FAST | 2,668,368 | 33.3% |
| LOAD_FAST | 2,200 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,372 | 0.0% |
| BUILD_MAP | 1,344 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,328,964 | 66.6% |
| RETURN_VALUE | 2,667,968 | 33.3% |
| STORE_FAST | 2,904 | 0.0% |
| POP_TOP | 2,560 | 0.0% |
| COPY | 1,740 | 0.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,900 | 63.5% |
| BINARY_OP_ADD_INT | 1,260 | 16.3% |
| LOAD_CONST | 760 | 9.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 300 | 3.9% |
| CALL | 220 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,380 | 43.8% |
| COPY | 1,500 | 19.4% |
| RETURN_VALUE | 1,200 | 15.5% |
| STORE_FAST | 560 | 7.3% |
| MAP_ADD | 320 | 4.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,020 | 36.2% |
| ENTER_EXECUTOR | 1,160 | 20.8% |
| LOAD_GLOBAL_MODULE | 660 | 11.8% |
| LOAD_CONST | 420 | 7.5% |
| BINARY_SUBSCR_TUPLE_INT | 400 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,000 | 53.8% |
| TO_BOOL_BOOL | 1,380 | 24.7% |
| STORE_FAST | 620 | 11.1% |
| BUILD_TUPLE | 260 | 4.7% |
| TO_BOOL_INT | 260 | 4.7% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,060 | 47.9% |
| LOAD_GLOBAL_MODULE | 2,540 | 24.0% |
| LOAD_ATTR_MODULE | 1,244 | 11.8% |
| LOAD_FAST_LOAD_FAST | 920 | 8.7% |
| BUILD_TUPLE | 300 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 9,384 | 88.8% |
| POP_TOP | 940 | 8.9% |
| RETURN_VALUE | 120 | 1.1% |
| TO_BOOL | 60 | 0.6% |
| LOAD_FAST | 60 | 0.6% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,640 | 68.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,740 | 15.6% |
| LOAD_ATTR | 540 | 4.9% |
| POP_JUMP_IF_TRUE | 460 | 4.1% |
| LOAD_NAME | 300 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,220 | 37.9% |
| LOAD_FAST | 2,640 | 23.7% |
| STORE_FAST | 1,120 | 10.1% |
| RETURN_VALUE | 960 | 8.6% |
| BINARY_OP_SUBTRACT_INT | 460 | 4.1% |


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
| LOAD_GLOBAL_MODULE | 2,386,632 | 99.7% |
| BUILD_MAP | 2,020 | 0.1% |
| LOAD_CONST | 2,020 | 0.1% |
| LOAD_FAST | 680 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,383,852 | 99.6% |
| STORE_FAST | 3,800 | 0.2% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,560 | 94.0% |
| CALL | 60 | 3.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 540 | 32.5% |
| BINARY_OP | 360 | 21.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 300 | 18.1% |
| TO_BOOL_BOOL | 220 | 13.3% |
| GET_ITER | 100 | 6.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,300 | 23.5% |
| STORE_FAST | 2,220 | 22.7% |
| LOAD_CONST | 1,320 | 13.5% |
| LOAD_NAME | 1,080 | 11.0% |
| LOAD_GLOBAL_MODULE | 920 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,480 | 35.5% |
| RETURN_VALUE | 3,160 | 32.2% |
| LOAD_CONST | 960 | 9.8% |
| CALL_METHOD_DESCRIPTOR_O | 660 | 6.7% |
| STORE_FAST | 580 | 5.9% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,769,644 | 49.9% |
| LOAD_FAST | 2,393,072 | 25.1% |
| CALL_TYPE_1 | 2,384,032 | 25.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,960 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,551,648 | 100.0% |
| COPY_FREE_VARS | 380 | 0.0% |
| MAKE_CELL | 360 | 0.0% |
| RETURN_GENERATOR | 220 | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,048,472 | 85.8% |
| ENTER_EXECUTOR | 335,700 | 14.1% |
| LOAD_FAST | 1,360 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,260 | 0.1% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,386,912 | 100.0% |


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
| LOAD_FAST | 4,769,044 | 100.0% |
| LOAD_GLOBAL_MODULE | 200 | 0.0% |
| CALL | 60 | 0.0% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,384,032 | 50.0% |
| STORE_FAST | 2,383,852 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 740 | 0.0% |
| LOAD_GLOBAL_MODULE | 260 | 0.0% |
| PUSH_NULL | 220 | 0.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 220 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,420 | 62.8% |
| LOAD_FAST | 3,660 | 31.0% |
| CALL_LEN | 360 | 3.0% |
| BINARY_OP | 180 | 1.5% |
| LOAD_GLOBAL_MODULE | 160 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,560 | 64.0% |
| COPY | 2,080 | 17.6% |
| POP_JUMP_IF_TRUE | 1,120 | 9.5% |
| RETURN_VALUE | 880 | 7.4% |
| STORE_FAST | 180 | 1.5% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,140 | 63.6% |
| COPY | 1,740 | 21.5% |
| LOAD_ATTR_INSTANCE_VALUE | 980 | 12.1% |
| LOAD_FAST | 180 | 2.2% |
| COMPARE_OP | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,700 | 58.2% |
| COPY | 2,060 | 25.5% |
| EXTENDED_ARG | 760 | 9.4% |
| JUMP_FORWARD | 360 | 4.5% |
| RETURN_VALUE | 200 | 2.5% |


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
| ENTER_EXECUTOR | 246,740 | 97.7% |
| GET_ITER | 3,080 | 1.2% |
| JUMP_BACKWARD | 1,560 | 0.6% |
| EXTENDED_ARG | 960 | 0.4% |
| FOR_ITER | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 245,080 | 97.1% |
| STORE_FAST | 3,120 | 1.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,220 | 0.5% |
| JUMP_BACKWARD | 960 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 560 | 0.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 640 | 45.7% |
| ENTER_EXECUTOR | 380 | 27.1% |
| GET_ITER | 280 | 20.0% |
| SWAP | 60 | 4.3% |
| FOR_ITER | 40 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,020 | 72.9% |
| LOAD_FAST | 220 | 15.7% |
| SWAP | 80 | 5.7% |
| LOAD_GLOBAL | 40 | 2.9% |
| LOAD_GLOBAL_MODULE | 40 | 2.9% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,387,252 | 51.2% |
| ENTER_EXECUTOR | 2,266,392 | 48.6% |
| JUMP_BACKWARD | 2,952 | 0.1% |
| SWAP | 2,740 | 0.1% |
| LOAD_FAST | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,388,184 | 51.3% |
| LOAD_GLOBAL_MODULE | 2,261,272 | 48.5% |
| STORE_FAST_LOAD_FAST | 2,980 | 0.1% |
| SWAP | 2,720 | 0.1% |
| STORE_NAME | 1,120 | 0.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,383,832 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,383,852 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| LOAD_FAST | 20 | 0.0% |
| STORE_FAST | 20 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,940 | 89.8% |
| LOAD_FAST_LOAD_FAST | 2,680 | 8.9% |
| LOAD_ATTR_INSTANCE_VALUE | 320 | 1.1% |
| LOAD_ATTR | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,700 | 22.3% |
| STORE_FAST | 3,460 | 11.5% |
| LOAD_ATTR_METHOD_NO_DICT | 2,120 | 7.1% |
| CALL_LEN | 1,740 | 5.8% |
| POP_JUMP_IF_NONE | 1,400 | 4.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,780 | 39.4% |
| LOAD_ATTR | 5,240 | 21.1% |
| LOAD_GLOBAL_MODULE | 2,880 | 11.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,120 | 8.5% |
| LOAD_CONST | 1,780 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,160 | 36.9% |
| LOAD_CONST | 7,400 | 29.8% |
| LOAD_GLOBAL_MODULE | 3,660 | 14.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,560 | 6.3% |
| LOAD_NAME | 1,120 | 4.5% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,560 | 70.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,040 | 20.7% |
| LOAD_GLOBAL_MODULE | 260 | 5.2% |
| BINARY_SUBSCR_TUPLE_INT | 120 | 2.4% |
| BINARY_SUBSCR | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,980 | 39.4% |
| CALL_PY_EXACT_ARGS | 1,960 | 39.0% |
| LOAD_FAST_LOAD_FAST | 800 | 15.9% |
| LOAD_CONST | 200 | 4.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20,544 | 79.9% |
| LOAD_NAME | 3,380 | 13.1% |
| LOAD_ATTR_MODULE | 1,244 | 4.8% |
| LOAD_ATTR | 300 | 1.2% |
| LOAD_FAST | 240 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 8,440 | 32.8% |
| CALL | 3,980 | 15.5% |
| LOAD_ATTR_SLOT | 2,780 | 10.8% |
| LOAD_CONST | 2,160 | 8.4% |
| LOAD_FAST | 2,060 | 8.0% |


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
| LOAD_ATTR_MODULE | 2,780 | 56.3% |
| LOAD_FAST | 1,840 | 37.2% |
| RETURN_VALUE | 220 | 4.5% |
| LOAD_FAST_LOAD_FAST | 60 | 1.2% |
| LOAD_ATTR | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,100 | 62.8% |
| LOAD_CONST | 1,020 | 20.6% |
| CALL_BUILTIN_FAST | 260 | 5.3% |
| STORE_FAST | 220 | 4.5% |
| STORE_ATTR_SLOT | 220 | 4.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,162,440 | 30.3% |
| POP_JUMP_IF_TRUE | 5,328,944 | 22.5% |
| POP_JUMP_IF_FALSE | 4,515,244 | 19.1% |
| NOP | 2,384,252 | 10.1% |
| LOAD_GLOBAL_MODULE | 2,384,092 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,969,776 | 50.6% |
| LOAD_DEREF | 2,669,100 | 11.3% |
| LOAD_ATTR | 2,384,932 | 10.1% |
| LOAD_GLOBAL_MODULE | 2,384,772 | 10.1% |
| LOAD_ATTR_CLASS | 2,383,832 | 10.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,059,424 | 25.2% |
| RESUME_CHECK | 12,216,496 | 21.9% |
| RETURN_VALUE | 6,070,312 | 10.9% |
| STORE_FAST | 4,775,724 | 8.6% |
| LOAD_GLOBAL_MODULE | 4,769,364 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 20,118,880 | 36.1% |
| LOAD_FAST | 11,935,600 | 21.4% |
| LOAD_FAST_LOAD_FAST | 7,438,112 | 13.3% |
| LOAD_GLOBAL_MODULE | 4,769,364 | 8.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,386,632 | 4.3% |


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
| CALL_PY_EXACT_ARGS | 9,551,648 | 55.2% |
| COPY_FREE_VARS | 2,668,600 | 15.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 2,667,840 | 15.4% |
| CALL_PY_WITH_DEFAULTS | 2,386,912 | 13.8% |
| CACHE | 16,268 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,216,496 | 70.6% |
| LOAD_FAST | 2,680,040 | 15.5% |
| BUILD_MAP | 2,383,852 | 13.8% |
| LOAD_GLOBAL_BUILTIN | 10,620 | 0.1% |
| LOAD_FAST_LOAD_FAST | 4,720 | 0.0% |


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
| LOAD_FAST | 440 | 47.8% |
| LOAD_FAST_LOAD_FAST | 260 | 28.3% |
| LOAD_ATTR_SLOT | 220 | 23.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 920 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,180 | 55.0% |
| BINARY_OP_ADD_UNICODE | 1,360 | 17.9% |
| LOAD_CONST | 740 | 9.7% |
| LOAD_ATTR_INSTANCE_VALUE | 520 | 6.8% |
| LOAD_FAST_LOAD_FAST | 380 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,080 | 27.4% |
| LOAD_FAST | 1,720 | 22.6% |
| JUMP_BACKWARD | 980 | 12.9% |
| LOAD_NAME | 960 | 12.6% |
| NOP | 780 | 10.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_NAME | 600 | 54.5% |
| LOAD_FAST_LOAD_FAST | 380 | 34.5% |
| LOAD_FAST | 80 | 7.3% |
| STORE_SUBSCR | 40 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 320 | 29.1% |
| LOAD_NAME | 320 | 29.1% |
| EXTENDED_ARG | 240 | 21.8% |
| ENTER_EXECUTOR | 160 | 14.5% |
| RETURN_CONST | 60 | 5.5% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 5,328,964 | 66.4% |
| RETURN_VALUE | 2,668,180 | 33.2% |
| CALL_ISINSTANCE | 9,384 | 0.1% |
| COPY | 7,800 | 0.1% |
| LOAD_FAST | 3,380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,345,188 | 66.6% |
| POP_JUMP_IF_FALSE | 2,685,880 | 33.4% |
| EXTENDED_ARG | 420 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,440 | 50.7% |
| LOAD_FAST | 680 | 23.9% |
| CALL_BUILTIN_O | 260 | 9.2% |
| CALL_LEN | 260 | 9.2% |
| COPY | 160 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,040 | 71.8% |
| POP_JUMP_IF_TRUE | 660 | 23.2% |
| UNARY_NOT | 140 | 4.9% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 980 | 84.5% |
| LOAD_ATTR | 140 | 12.1% |
| TO_BOOL | 20 | 1.7% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 780 | 67.2% |
| POP_JUMP_IF_FALSE | 320 | 27.6% |
| UNARY_NOT | 60 | 5.2% |


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
| STORE_FAST_LOAD_FAST | 2,220 | 41.1% |
| COPY | 2,160 | 40.0% |
| LOAD_FAST | 980 | 18.1% |
| TO_BOOL | 20 | 0.4% |
| CALL_BUILTIN_FAST | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,140 | 58.1% |
| POP_JUMP_IF_TRUE | 2,260 | 41.9% |


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
| FOR_ITER | 2,300 | 43.6% |
| RETURN_VALUE | 1,620 | 30.7% |
| FOR_ITER_LIST | 1,220 | 23.1% |
| UNPACK_SEQUENCE | 120 | 2.3% |
| BINARY_SUBSCR_LIST_INT | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 3,660 | 69.3% |
| STORE_NAME | 820 | 15.5% |
| STORE_FAST | 800 | 15.2% |


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
|     deferred | 5,760 | 28.8% |
|          hit | 13,620 | 68.0% |

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
|     deferred | 125,816 | 91.1% |
|          hit | 11,440 | 8.3% |
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
|     deferred | 27,982,204 | 46.3% |
|          hit | 32,496,316 | 53.7% |
|         miss | 4,420 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,500 | 14.2% |
| Failure | 9,056 | 85.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method wrapper | 3,924 | 43.3% |
| other | 2,980 | 32.9% |
| class no vectorcall | 820 | 9.1% |
| operator wrapper | 772 | 8.5% |
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
|     deferred | 1,480 | 6.8% |
|          hit | 20,060 | 92.5% |
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
|     deferred | 2,059,820 | 29.5% |
|          hit | 4,913,696 | 70.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 320 | 13.7% |
| Failure | 2,020 | 86.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 920 | 45.5% |
| dict values | 500 | 24.8% |
| dict items | 360 | 17.8% |
| itertools | 160 | 7.9% |
| ascii string | 60 | 3.0% |
| enumerate | 20 | 1.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 10,652,352 | 81.1% |
|        deopt | 20 | 0.0% |
|          hit | 2,473,880 | 18.8% |
|         miss | 2,220 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 760 | 13.6% |
| Failure | 4,828 | 86.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 4,528 | 93.8% |
| shadowed | 120 | 2.5% |
| method | 60 | 1.2% |
| module attr not found | 60 | 1.2% |
| overridden | 20 | 0.4% |
| not managed dict | 20 | 0.4% |
| builtin class method | 20 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,280 | 0.0% |
|        deopt | 620 | 0.0% |
|          hit | 79,406,792 | 100.0% |
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
|     deferred | 5,220 | 21.2% |
|          hit | 16,180 | 65.8% |
|         miss | 2,580 | 10.5% |

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
|     deferred | 820 | 8.5% |
|          hit | 8,700 | 89.7% |

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
|          hit | 8,042,948 | 100.0% |
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
|     deferred | 120 | 1.9% |
|          hit | 6,060 | 96.2% |

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
| Basic | 204,715,488 | 47.5% |
| Not specialized | 81,764,532 | 19.0% |
| Specialized hits | 144,713,860 | 33.6% |
| Specialized misses | 27,420 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 27,982,204 | 68.5% |
| LOAD_ATTR | 10,652,352 | 26.1% |
| FOR_ITER | 2,059,820 | 5.0% |
| BINARY_SUBSCR | 125,816 | 0.3% |
| BINARY_OP | 5,760 | 0.0% |
| STORE_ATTR | 5,220 | 0.0% |
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
| LOAD_GLOBAL_MODULE | 9,460 | 34.5% |
| LOAD_GLOBAL_BUILTIN | 7,980 | 29.1% |
| STORE_ATTR_INSTANCE_VALUE | 2,580 | 9.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,640 | 6.0% |
| CALL_BUILTIN_O | 1,420 | 5.2% |
| LOAD_ATTR_MODULE | 1,220 | 4.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 560 | 2.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 520 | 1.9% |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 1.7% |
| BINARY_SUBSCR_LIST_INT | 320 | 1.2% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 2,686,548 | 15.5% |
| Calls to Python functions inlined | 14,619,880 | 84.5% |
| Calls via PyEval_EvalFrame (total) | 2,686,548 | 15.5% |
| Calls via PyEval_EvalFrame (vector) | 2,684,448 | 15.5% |
| Calls via PyEval_EvalFrame (generator) | 2,100 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 420 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 2,683,308 | 15.5% |
| Calls via PyEval_EvalFrame (build class) | 720 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 5,020 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 540 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 1,540 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 3,688,240 | 21.3% |
| Frames pushed | 18,300,980 | 105.7% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 30,776,596 | 54.3% |
| Frees to freelist | 30,773,556 |  |
| Allocations | 25,870,408 | 45.7% |
| Allocations to 512 bytes | 25,856,768 | 45.6% |
| Allocations to 4 kbytes | 12,700 | 0.0% |
| Allocations over 4 kbytes | 940 | 0.0% |
| Frees | 25,711,279 |  |
| New values | 3,280 |  |
| Interpreter increfs | 221,264,976 | 61.1% |
| Interpreter decrefs | 256,840,296 | 61.4% |
| Increfs | 140,599,445 | 38.9% |
| Decrefs | 161,310,408 | 38.6% |
| Materialize dict (on request) | 1,040 | 31.7% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 15,929,303 |  |
| Method cache misses | 116,337 |  |
| Method cache collisions | 225,468 |  |
| Method cache dunder hits | 22,755,250 |  |
| Method cache dunder misses | 115,674 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 80 | 2,400 | 777,640 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 700 |  |
| Traces created | 700 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 120 | 17.1% |
| Recursive call | 0 | 0.0% |
| Traces executed | 6,960,580 |  |
| Uops executed | 144,730,504 | 20.79 |

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
| <= 32 | 360 | 51.4% |
| <= 64 | 260 | 37.1% |
| <= 128 | 80 | 11.4% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 40 | 5.7% |
| <= 16 | 100 | 14.3% |
| <= 32 | 400 | 57.1% |
| <= 64 | 120 | 17.1% |
| <= 128 | 40 | 5.7% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 120 | 0.0% |
| <= 2 | 2,509,404 | 36.1% |
| <= 4 | 380 | 0.0% |
| <= 8 | 2,520 | 0.0% |
| <= 16 | 339,928 | 4.9% |
| <= 32 | 3,898,460 | 56.0% |
| <= 64 | 1,908 | 0.0% |
| <= 128 | 1,992 | 0.0% |
| <= 256 | 205,388 | 3.0% |
| <= 512 | 220 | 0.0% |
| <= 1,024 | 140 | 0.0% |
| <= 2,048 | 40 | 0.0% |
| <= 4,096 | 60 | 0.0% |
| <= 8,192 | 20 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _GUARD_GLOBALS_VERSION | 17,427,512 | 12.0% | 12.0% | 0.0% |
| LOAD_FAST | 14,045,836 | 9.7% | 21.7% |  |
| _LOAD_GLOBAL_MODULE | 11,070,824 | 7.6% | 29.4% |  |
| _SET_IP | 7,373,440 | 5.1% | 34.5% |  |
| _CHECK_VALIDITY | 7,148,728 | 4.9% | 39.4% |  |
| STORE_FAST | 6,990,052 | 4.8% | 44.3% |  |
| _GUARD_BUILTINS_VERSION | 6,354,868 | 4.4% | 48.6% | 0.0% |
| _LOAD_GLOBAL_BUILTINS | 6,354,648 | 4.4% | 53.0% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 5,964,164 | 4.1% | 57.2% | 38.0% |
| _ITER_CHECK_TUPLE | 5,964,164 | 4.1% | 61.3% |  |
| _EXIT_TRACE | 4,234,796 | 2.9% | 64.2% |  |
| _ITER_NEXT_TUPLE | 3,697,772 | 2.6% | 66.8% |  |
| _CHECK_PEP_523 | 3,688,820 | 2.5% | 69.3% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 3,688,820 | 2.5% | 71.9% |  |
| _CHECK_STACK_SPACE | 3,688,820 | 2.5% | 74.4% |  |
| _INIT_CALL_PY_EXACT_ARGS | 3,688,820 | 2.5% | 77.0% |  |
| _PUSH_FRAME | 3,688,820 | 2.5% | 79.5% |  |
| _SAVE_RETURN_OFFSET | 3,688,820 | 2.5% | 82.1% |  |
| RESUME_CHECK | 3,688,660 | 2.5% | 84.6% |  |
| CALL_TYPE_1 | 3,687,360 | 2.5% | 87.2% |  |
| _ITER_CHECK_LIST | 3,119,380 | 2.2% | 89.3% | 0.0% |
| _GUARD_NOT_EXHAUSTED_LIST | 3,119,260 | 2.2% | 91.5% | 7.9% |
| _ITER_NEXT_LIST | 2,872,100 | 2.0% | 93.4% |  |
| POP_TOP | 2,665,020 | 1.8% | 95.3% |  |
| CALL_ISINSTANCE | 2,664,444 | 1.8% | 97.1% |  |
| _JUMP_TO_TOP | 2,494,116 | 1.7% | 98.9% |  |
| _FOR_ITER_TIER_TWO | 567,628 | 0.4% | 99.2% | 36.3% |
| PUSH_NULL | 358,900 | 0.2% | 99.5% |  |
| GET_ITER | 245,376 | 0.2% | 99.7% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 46,660 | 0.0% | 99.7% | 0.8% |
| _ITER_CHECK_RANGE | 46,660 | 0.0% | 99.7% |  |
| _ITER_NEXT_RANGE | 46,280 | 0.0% | 99.8% |  |
| LOAD_NAME | 41,200 | 0.0% | 99.8% |  |
| LOAD_CONST | 26,824 | 0.0% | 99.8% |  |
| _GUARD_IS_FALSE_POP | 24,836 | 0.0% | 99.8% | 6.2% |
| _CHECK_ATTR_MODULE | 21,888 | 0.0% | 99.8% |  |
| _LOAD_ATTR_MODULE | 21,888 | 0.0% | 99.9% |  |
| TO_BOOL_BOOL | 21,784 | 0.0% | 99.9% |  |
| _GUARD_TYPE_VERSION | 19,500 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 17,560 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 11,600 | 0.0% | 99.9% |  |
| _GUARD_IS_TRUE_POP | 10,684 | 0.0% | 99.9% | 6.9% |
| LIST_APPEND | 9,680 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 9,100 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 8,820 | 0.0% | 99.9% |  |
| STORE_NAME | 8,600 | 0.0% | 99.9% |  |
| BUILD_STRING | 8,000 | 0.0% | 99.9% |  |
| _LOAD_ATTR | 6,308 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,320 | 0.0% | 99.9% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 5,260 | 0.0% | 100.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 5,260 | 0.0% | 100.0% |  |
| CONTAINS_OP | 5,156 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 5,020 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 3,800 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 3,260 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 2,780 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 2,664 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 2,560 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 2,420 | 0.0% | 100.0% | 47.9% |
| _GUARD_BOTH_UNICODE | 2,380 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 2,380 | 0.0% | 100.0% |  |
| IS_OP | 2,280 | 0.0% | 100.0% |  |
| _POP_FRAME | 2,000 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 1,700 | 0.0% | 100.0% |  |
| BUILD_MAP | 1,604 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 1,600 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 1,400 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 1,400 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 1,400 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,340 | 0.0% | 100.0% |  |
| _GUARD_IS_NOT_NONE_POP | 1,300 | 0.0% | 100.0% | 4.6% |
| CALL_LEN | 1,240 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 1,100 | 0.0% | 100.0% |  |
| _STORE_ATTR | 1,100 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 1,080 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 1,040 | 0.0% | 100.0% |  |
| _GUARD_KEYS_VERSION | 1,040 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 1,040 | 0.0% | 100.0% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 1,000 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 1,000 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 900 | 0.0% | 100.0% |  |
| MAP_ADD | 880 | 0.0% | 100.0% |  |
| BINARY_SLICE | 860 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 720 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 620 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 500 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 420 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 380 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 300 | 0.0% | 100.0% |  |
| COPY | 280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 220 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 200 | 0.0% | 100.0% |  |
| _LOAD_ATTR_SLOT | 200 | 0.0% | 100.0% |  |
| _BINARY_OP | 100 | 0.0% | 100.0% |  |
| UNARY_NOT | 80 | 0.0% | 100.0% |  |
| LOAD_DEREF | 80 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 100 |
| CALL_PY_WITH_DEFAULTS | 20 |


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
