
# Pystats results

- benchmark: coverage
- fork: gvanrossum
- ref: load-attr-uops
- commit hash: b54eee3
- commit date: 2023-09-26T21:26:46-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 809,226,768 | 24.1% | 24.1% |  |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 349,645,080 | 10.4% | 34.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 349,630,380 | 10.4% | 45.0% |  |
| LOAD_ATTR | 247,758,260 | 7.4% | 52.3% |  |
| LOAD_CONST | 204,023,580 | 6.1% | 58.4% |  |
| TO_BOOL_BOOL | 145,758,004 | 4.3% | 62.8% |  |
| COMPARE_OP_STR | 131,122,200 | 3.9% | 66.7% | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 131,122,140 | 3.9% | 70.6% |  |
| STORE_FAST | 87,590,604 | 2.6% | 73.2% |  |
| LOAD_GLOBAL | 80,160,240 | 2.4% | 75.6% |  |
| INSTRUMENTED_RESUME | 72,852,120 | 2.2% | 77.7% |  |
| INSTRUMENTED_RETURN_VALUE | 72,844,800 | 2.2% | 79.9% |  |
| EXTENDED_ARG | 72,843,780 | 2.2% | 82.1% |  |
| LOAD_FAST_LOAD_FAST | 58,822,560 | 1.8% | 83.8% |  |
| CONTAINS_OP | 58,516,320 | 1.7% | 85.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 58,336,704 | 1.7% | 87.3% |  |
| INTERPRETER_EXIT | 58,288,680 | 1.7% | 89.1% |  |
| POP_TOP | 43,728,060 | 1.3% | 90.4% |  |
| INSTRUMENTED_POP_JUMP_IF_NONE | 43,702,080 | 1.3% | 91.7% |  |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 29,144,364 | 0.9% | 92.5% |  |
| CALL_METHOD_DESCRIPTOR_O | 29,142,780 | 0.9% | 93.4% |  |
| COMPARE_OP_INT | 29,140,740 | 0.9% | 94.3% |  |
| BINARY_OP_ADD_INT | 21,853,260 | 0.7% | 94.9% |  |
| CALL_PY_EXACT_ARGS | 14,647,440 | 0.4% | 95.4% |  |
| CALL | 14,645,584 | 0.4% | 95.8% |  |
| TO_BOOL_NONE | 14,585,720 | 0.4% | 96.2% | 0.0% |
| TO_BOOL | 14,583,560 | 0.4% | 96.7% |  |
| BUILD_TUPLE | 14,580,420 | 0.4% | 97.1% |  |
| BINARY_SUBSCR | 14,574,060 | 0.4% | 97.5% |  |
| BINARY_OP_SUBTRACT_INT | 14,572,800 | 0.4% | 98.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 14,569,560 | 0.4% | 98.4% |  |
| INSTRUMENTED_JUMP_FORWARD | 14,567,880 | 0.4% | 98.8% |  |
| UNARY_NEGATIVE | 14,567,640 | 0.4% | 99.3% |  |
| UNPACK_SEQUENCE | 14,567,240 | 0.4% | 99.7% |  |
| LOAD_GLOBAL_MODULE | 7,437,660 | 0.2% | 99.9% |  |
| POP_JUMP_IF_FALSE | 356,820 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 287,100 | 0.0% | 99.9% |  |
| STORE_FAST_STORE_FAST | 254,100 | 0.0% | 100.0% |  |
| FOR_ITER | 252,960 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 243,360 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 242,520 | 0.0% | 100.0% |  |
| RESUME_CHECK | 102,180 | 0.0% | 100.0% | 7.6% |
| LOAD_GLOBAL_BUILTIN | 95,700 | 0.0% | 100.0% | 0.2% |
| LOAD_ATTR_MODULE | 87,280 | 0.0% | 100.0% | 0.7% |
| RETURN_VALUE | 69,780 | 0.0% | 100.0% |  |
| PUSH_NULL | 51,960 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 43,380 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 40,740 | 0.0% | 100.0% |  |
| NOP | 35,520 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,920 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 29,700 | 0.0% | 100.0% |  |
| POP_JUMP_IF_TRUE | 25,980 | 0.0% | 100.0% |  |
| LOAD_DEREF | 18,480 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 17,280 | 0.0% | 100.0% |  |
| RETURN_CONST | 16,080 | 0.0% | 100.0% |  |
| GET_ITER | 15,900 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 12,180 | 0.0% | 100.0% |  |
| STORE_ATTR | 11,000 | 0.0% | 100.0% |  |
| YIELD_VALUE | 10,920 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 8,820 | 0.0% | 100.0% |  |
| BINARY_SLICE | 8,520 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 8,400 | 0.0% | 100.0% |  |
| INSTRUMENTED_FOR_ITER | 8,364 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 8,340 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 7,800 | 0.0% | 100.0% |  |
| INSTRUMENTED_JUMP_BACKWARD | 7,344 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 7,260 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 7,260 | 0.0% | 100.0% |  |
| BINARY_OP | 6,840 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 6,480 | 0.0% | 100.0% |  |
| COPY | 6,300 | 0.0% | 100.0% |  |
| INSTRUMENTED_RETURN_CONST | 5,460 | 0.0% | 100.0% |  |
| LIST_APPEND | 5,340 | 0.0% | 100.0% |  |
| BUILD_MAP | 5,280 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 5,160 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 5,040 | 0.0% | 100.0% |  |
| BUILD_LIST | 4,980 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 4,860 | 0.0% | 100.0% |  |
| SWAP | 4,800 | 0.0% | 100.0% |  |
| JUMP_FORWARD | 4,560 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 4,380 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 4,200 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 3,960 | 0.0% | 100.0% |  |
| CALL_LEN | 3,840 | 0.0% | 100.0% |  |
| CALL_KW | 3,540 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 3,480 | 0.0% | 100.0% |  |
| POP_EXCEPT | 3,480 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 3,480 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,340 | 0.0% | 100.0% | 1.8% |
| LOAD_ATTR_WITH_HINT | 2,760 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 2,340 | 0.0% | 100.0% |  |
| DICT_MERGE | 2,280 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 2,180 | 0.0% | 100.0% | 48.6% |
| MAKE_CELL | 2,100 | 0.0% | 100.0% |  |
| STORE_DEREF | 1,920 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 1,920 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 1,860 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,860 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 1,860 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 1,740 | 0.0% | 100.0% | 3.4% |
| RESUME | 1,560 | 0.0% | 100.0% | 500.0% |
| CALL_TYPE_1 | 1,440 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 1,440 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,320 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 1,200 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 1,200 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NONE | 1,140 | 0.0% | 100.0% |  |
| LIST_EXTEND | 1,080 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 1,080 | 0.0% | 100.0% |  |
| UNPACK_EX | 960 | 0.0% | 100.0% |  |
| MAP_ADD | 960 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 960 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 960 | 0.0% | 100.0% |  |
| IS_OP | 840 | 0.0% | 100.0% |  |
| FORMAT_SIMPLE | 840 | 0.0% | 100.0% |  |
| BUILD_STRING | 660 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 600 | 0.0% | 100.0% |  |
| COMPARE_OP | 580 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 540 | 0.0% | 100.0% |  |
| INSTRUMENTED_POP_JUMP_IF_NOT_NONE | 480 | 0.0% | 100.0% |  |
| STORE_ATTR_WITH_HINT | 420 | 0.0% | 100.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 420 | 0.0% | 100.0% | 28.6% |
| DELETE_ATTR | 360 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 360 | 0.0% | 100.0% |  |
| LOAD_ATTR_PROPERTY | 300 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 240 | 0.0% | 100.0% |  |
| RERAISE | 180 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 180 | 0.0% | 100.0% |  |
| BEFORE_WITH | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| BUILD_SLICE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 335,058,120 | 10.0% | 10.0% |
| INSTRUMENTED_POP_JUMP_IF_FALSE LOAD_FAST | 327,774,960 | 9.8% | 19.8% |
| LOAD_FAST LOAD_CONST | 160,259,700 | 4.8% | 24.5% |
| LOAD_FAST LOAD_ATTR | 145,698,220 | 4.3% | 28.9% |
| TO_BOOL_BOOL INSTRUMENTED_POP_JUMP_IF_FALSE | 145,685,880 | 4.3% | 33.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 116,541,900 | 3.5% | 36.7% |
| LOAD_CONST COMPARE_OP_STR | 116,539,300 | 3.5% | 40.2% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 116,538,040 | 3.5% | 43.6% |
| LOAD_ATTR LOAD_ATTR | 102,033,820 | 3.0% | 46.7% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 87,413,160 | 2.6% | 49.3% |
| EXTENDED_ARG INSTRUMENTED_POP_JUMP_IF_FALSE | 72,839,160 | 2.2% | 51.4% |
| COMPARE_OP_STR EXTENDED_ARG | 72,835,860 | 2.2% | 53.6% |
| LOAD_GLOBAL LOAD_FAST | 65,567,400 | 2.0% | 55.6% |
| INSTRUMENTED_RESUME LOAD_GLOBAL | 58,280,880 | 1.7% | 57.3% |
| CONTAINS_OP INSTRUMENTED_POP_JUMP_IF_FALSE | 58,269,120 | 1.7% | 59.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 58,269,100 | 1.7% | 60.8% |
| LOAD_ATTR CONTAINS_OP | 58,268,820 | 1.7% | 62.5% |
| LOAD_ATTR_INSTANCE_VALUE INSTRUMENTED_RETURN_VALUE | 58,268,760 | 1.7% | 64.3% |
| CACHE INSTRUMENTED_RESUME | 58,268,760 | 1.7% | 66.0% |
| INSTRUMENTED_RETURN_VALUE INTERPRETER_EXIT | 58,268,700 | 1.7% | 67.7% |
| STORE_FAST LOAD_FAST | 43,794,324 | 1.3% | 69.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 43,759,104 | 1.3% | 70.3% |
| COMPARE_OP_STR INSTRUMENTED_POP_JUMP_IF_FALSE | 43,708,380 | 1.3% | 71.6% |
| LOAD_ATTR STORE_FAST | 43,706,340 | 1.3% | 72.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 43,706,280 | 1.3% | 74.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 43,704,620 | 1.3% | 75.5% |
| INSTRUMENTED_POP_JUMP_IF_NONE LOAD_FAST | 43,702,080 | 1.3% | 76.8% |
| LOAD_FAST TO_BOOL_BOOL | 29,143,320 | 0.9% | 77.7% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 29,141,440 | 0.9% | 78.6% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 29,140,800 | 0.9% | 79.5% |
| LOAD_CONST COMPARE_OP_INT | 29,139,280 | 0.9% | 80.3% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 29,135,460 | 0.9% | 81.2% |
| POP_TOP LOAD_FAST_LOAD_FAST | 29,134,260 | 0.9% | 82.1% |
| LOAD_ATTR_INSTANCE_VALUE INSTRUMENTED_POP_JUMP_IF_NONE | 29,134,200 | 0.9% | 82.9% |
| LOAD_CONST LOAD_FAST | 14,583,060 | 0.4% | 83.4% |
| CALL_PY_EXACT_ARGS INSTRUMENTED_RESUME | 14,577,960 | 0.4% | 83.8% |
| LOAD_FAST BUILD_TUPLE | 14,574,540 | 0.4% | 84.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 14,573,520 | 0.4% | 84.7% |
| LOAD_CONST STORE_FAST | 14,572,740 | 0.4% | 85.1% |
| POP_TOP LOAD_FAST | 14,572,260 | 0.4% | 85.5% |
| INSTRUMENTED_POP_JUMP_IF_TRUE LOAD_FAST | 14,571,360 | 0.4% | 86.0% |
| INSTRUMENTED_POP_JUMP_IF_TRUE LOAD_GLOBAL | 14,571,060 | 0.4% | 86.4% |
| LOAD_ATTR LOAD_FAST | 14,570,420 | 0.4% | 86.8% |
| BUILD_TUPLE CALL | 14,570,240 | 0.4% | 87.3% |
| TO_BOOL INSTRUMENTED_POP_JUMP_IF_TRUE | 14,570,160 | 0.4% | 87.7% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 14,569,920 | 0.4% | 88.1% |
| INSTRUMENTED_RESUME LOAD_FAST | 14,569,320 | 0.4% | 88.6% |
| LOAD_CONST BINARY_OP_ADD_INT | 14,568,780 | 0.4% | 89.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 14,568,440 | 0.4% | 89.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_NONE | 14,568,380 | 0.4% | 89.9% |
| LOAD_ATTR LOAD_CONST | 14,568,300 | 0.4% | 90.3% |
| TO_BOOL_NONE INSTRUMENTED_POP_JUMP_IF_FALSE | 14,568,120 | 0.4% | 90.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 14,567,760 | 0.4% | 91.2% |
| INSTRUMENTED_POP_JUMP_IF_FALSE LOAD_CONST | 14,567,760 | 0.4% | 91.6% |
| UNARY_NEGATIVE LOAD_FAST | 14,567,640 | 0.4% | 92.0% |
| COMPARE_OP_STR INSTRUMENTED_POP_JUMP_IF_TRUE | 14,567,580 | 0.4% | 92.5% |
| CALL POP_TOP | 14,567,580 | 0.4% | 92.9% |
| STORE_FAST INSTRUMENTED_JUMP_FORWARD | 14,567,400 | 0.4% | 93.3% |
| BINARY_SUBSCR STORE_FAST | 14,567,400 | 0.4% | 93.8% |
| LOAD_GLOBAL INSTRUMENTED_POP_JUMP_IF_NONE | 14,567,340 | 0.4% | 94.2% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_STR | 14,567,340 | 0.4% | 94.6% |
| LOAD_ATTR UNARY_NEGATIVE | 14,567,340 | 0.4% | 95.1% |
| INSTRUMENTED_JUMP_FORWARD LOAD_FAST | 14,567,340 | 0.4% | 95.5% |
| COMPARE_OP_INT STORE_FAST | 14,567,340 | 0.4% | 96.0% |
| BINARY_OP_ADD_INT BINARY_SUBSCR | 14,567,340 | 0.4% | 96.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_FAST | 14,567,280 | 0.4% | 96.8% |
| CALL_METHOD_DESCRIPTOR_FAST UNPACK_SEQUENCE | 14,567,240 | 0.4% | 97.3% |
| UNPACK_SEQUENCE LOAD_FAST | 14,567,220 | 0.4% | 97.7% |
| COMPARE_OP_INT INSTRUMENTED_POP_JUMP_IF_FALSE | 14,567,100 | 0.4% | 98.1% |
| BINARY_OP_SUBTRACT_INT CALL_PY_EXACT_ARGS | 14,567,040 | 0.4% | 98.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 7,334,340 | 0.2% | 98.8% |
| LOAD_FAST INSTRUMENTED_RETURN_VALUE | 7,288,320 | 0.2% | 99.0% |
| INSTRUMENTED_POP_JUMP_IF_FALSE LOAD_GLOBAL | 7,287,680 | 0.2% | 99.2% |
| INSTRUMENTED_RETURN_VALUE LOAD_GLOBAL_MODULE | 7,283,520 | 0.2% | 99.4% |
| INSTRUMENTED_RETURN_VALUE BINARY_OP_ADD_INT | 7,283,520 | 0.2% | 99.6% |
| BINARY_OP_ADD_INT INSTRUMENTED_RETURN_VALUE | 7,283,520 | 0.2% | 99.9% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 252,120 | 0.0% | 99.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 250,380 | 0.0% | 99.9% |
| JUMP_BACKWARD FOR_ITER | 247,020 | 0.0% | 99.9% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 245,880 | 0.0% | 99.9% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 243,360 | 0.0% | 99.9% |
| STORE_SUBSCR_DICT JUMP_BACKWARD | 241,380 | 0.0% | 99.9% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 241,140 | 0.0% | 99.9% |
| LOAD_FAST STORE_SUBSCR_DICT | 239,440 | 0.0% | 99.9% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 238,320 | 0.0% | 99.9% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 238,320 | 0.0% | 99.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 62,640 | 0.0% | 99.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 58,560 | 0.0% | 99.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 58,080 | 0.0% | 99.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 57,300 | 0.0% | 99.9% |
| LOAD_FAST CALL | 56,064 | 0.0% | 99.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 53,800 | 0.0% | 99.9% |
| PUSH_NULL LOAD_FAST | 44,580 | 0.0% | 99.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 43,780 | 0.0% | 99.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 38,604 | 0.0% | 99.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 34,660 | 0.0% | 99.9% |
| JUMP_BACKWARD FOR_ITER_LIST | 34,320 | 0.0% | 99.9% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 31,840 | 0.0% | 99.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 30,280 | 0.0% | 99.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 29,880 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,660 | 78.2% |
| BINARY_OP_ADD_INT | 1,140 | 13.4% |
| LOAD_FAST | 720 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,600 | 42.3% |
| BINARY_OP | 1,920 | 22.5% |
| LOAD_FAST_LOAD_FAST | 1,320 | 15.5% |
| INSTRUMENTED_RETURN_VALUE | 540 | 6.3% |
| STORE_FAST_STORE_FAST | 420 | 4.9% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RESUME | 58,268,760 | 100.0% |
| RESUME_CHECK | 13,740 | 0.0% |
| POP_TOP | 4,200 | 0.0% |
| COPY_FREE_VARS | 1,920 | 0.0% |
| RESUME | 60 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 180 | 100.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 6,600 | 90.9% |
| LOAD_FAST_LOAD_FAST | 660 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,200 | 57.9% |
| INSTRUMENTED_JUMP_BACKWARD | 3,060 | 42.1% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 14,567,340 | 100.0% |
| BINARY_SUBSCR | 3,760 | 0.0% |
| LOAD_CONST | 2,880 | 0.0% |
| BUILD_SLICE | 60 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,567,400 | 100.0% |
| BINARY_SUBSCR | 3,760 | 0.0% |
| LOAD_FAST | 1,980 | 0.0% |
| BUILD_TUPLE | 900 | 0.0% |
| BINARY_SUBSCR_DICT | 20 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,480 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,200 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 360 | 42.9% |
| LOAD_FAST | 300 | 35.7% |
| LOAD_ATTR_INSTANCE_VALUE | 180 | 21.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 480 | 57.1% |
| LOAD_CONST | 360 | 42.9% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 7,260 | 45.7% |
| LOAD_FAST | 3,600 | 22.6% |
| LOAD_ATTR_MODULE | 1,980 | 12.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,020 | 6.4% |
| RETURN_VALUE | 660 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 5,220 | 32.8% |
| INSTRUMENTED_FOR_ITER | 4,020 | 25.3% |
| CALL_PY_EXACT_ARGS | 4,000 | 25.2% |
| FOR_ITER_LIST | 1,800 | 11.3% |
| LOAD_FAST_AND_CLEAR | 540 | 3.4% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RETURN_VALUE | 58,268,700 | 100.0% |
| YIELD_VALUE | 10,920 | 0.0% |
| RETURN_CONST | 4,680 | 0.0% |
| RETURN_VALUE | 4,320 | 0.0% |
| INSTRUMENTED_RETURN_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 3,960 | 81.5% |
| STORE_FAST | 720 | 14.8% |
| LOAD_FAST | 120 | 2.5% |
| LOAD_GLOBAL_MODULE | 40 | 0.8% |
| LOAD_GLOBAL | 20 | 0.4% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,720 | 44.3% |
| RESUME_CHECK | 7,500 | 21.1% |
| FOR_ITER | 4,200 | 11.8% |
| POP_JUMP_IF_FALSE | 3,300 | 9.3% |
| INSTRUMENTED_FOR_ITER | 3,060 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,040 | 48.0% |
| LOAD_GLOBAL_MODULE | 7,440 | 20.9% |
| LOAD_GLOBAL_BUILTIN | 5,500 | 15.5% |
| LOAD_GLOBAL | 3,260 | 9.2% |
| LOAD_FAST_LOAD_FAST | 1,980 | 5.6% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,000 | 86.2% |
| POP_TOP | 300 | 8.6% |
| COPY | 180 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,000 | 86.2% |
| RERAISE | 180 | 5.2% |
| JUMP_BACKWARD | 180 | 5.2% |
| RETURN_CONST | 120 | 3.4% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 29,135,460 | 66.6% |
| CALL | 14,567,580 | 33.3% |
| RESUME_CHECK | 10,920 | 0.0% |
| CACHE | 4,200 | 0.0% |
| POP_JUMP_IF_FALSE | 3,480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 29,134,260 | 66.6% |
| LOAD_FAST | 14,572,260 | 33.3% |
| JUMP_BACKWARD | 12,960 | 0.0% |
| RESUME_CHECK | 4,200 | 0.0% |
| JUMP_FORWARD | 960 | 0.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,760 | 79.3% |
| CALL_KW | 240 | 6.9% |
| RERAISE | 180 | 5.2% |
| BINARY_SUBSCR_DICT | 180 | 5.2% |
| CALL_BUILTIN_FAST | 120 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,460 | 99.4% |
| LOAD_GLOBAL | 20 | 0.6% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 43,780 | 84.3% |
| STORE_FAST_LOAD_FAST | 5,040 | 9.7% |
| LOAD_ATTR | 2,120 | 4.1% |
| LOAD_FAST | 840 | 1.6% |
| LOAD_DEREF | 180 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,580 | 85.8% |
| LOAD_CONST | 3,840 | 7.4% |
| LOAD_FAST_LOAD_FAST | 2,340 | 4.5% |
| CALL | 1,020 | 2.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.1% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 3,900 | 92.9% |
| CALL_PY_EXACT_ARGS | 180 | 4.3% |
| CALL_FUNCTION_EX | 120 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 3,840 | 91.4% |
| LOAD_FAST | 120 | 2.9% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 2.9% |
| CALL | 120 | 2.9% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 23,040 | 33.0% |
| LOAD_FAST | 10,980 | 15.7% |
| CALL | 7,080 | 10.1% |
| RETURN_VALUE | 4,020 | 5.8% |
| POP_JUMP_IF_TRUE | 3,000 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 25,280 | 36.2% |
| STORE_FAST | 16,440 | 23.6% |
| LIST_APPEND | 5,040 | 7.2% |
| INTERPRETER_EXIT | 4,320 | 6.2% |
| RETURN_VALUE | 4,020 | 5.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 14,567,760 | 99.9% |
| LOAD_FAST | 10,560 | 0.1% |
| TO_BOOL | 4,020 | 0.0% |
| COPY | 560 | 0.0% |
| RETURN_VALUE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_TRUE | 14,570,160 | 99.9% |
| POP_JUMP_IF_TRUE | 4,500 | 0.0% |
| TO_BOOL | 4,020 | 0.0% |
| POP_JUMP_IF_FALSE | 3,080 | 0.0% |
| TO_BOOL_BOOL | 840 | 0.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 14,567,340 | 100.0% |
| CALL_LEN | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,567,640 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920 | 28.1% |
| BINARY_SLICE | 1,920 | 28.1% |
| LOAD_FAST | 980 | 14.3% |
| BUILD_TUPLE | 900 | 13.2% |
| CALL_LEN | 420 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,060 | 44.7% |
| LOAD_CONST | 960 | 14.0% |
| BINARY_OP_SUBTRACT_INT | 960 | 14.0% |
| YIELD_VALUE | 900 | 13.2% |
| COMPARE_OP_STR | 420 | 6.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,220 | 44.6% |
| STORE_ATTR_INSTANCE_VALUE | 1,020 | 20.5% |
| SWAP | 540 | 10.8% |
| RESUME_CHECK | 300 | 6.0% |
| POP_TOP | 300 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,280 | 45.8% |
| STORE_FAST | 1,860 | 37.3% |
| SWAP | 600 | 12.0% |
| GET_ITER | 180 | 3.6% |
| LOAD_DEREF | 60 | 1.2% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,100 | 39.8% |
| LOAD_ATTR_INSTANCE_VALUE | 960 | 18.2% |
| LOAD_FAST_LOAD_FAST | 720 | 13.6% |
| STORE_ATTR_INSTANCE_VALUE | 420 | 8.0% |
| RESUME_CHECK | 300 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,000 | 56.8% |
| CALL_FUNCTION_EX | 960 | 18.2% |
| CALL_PY_EXACT_ARGS | 720 | 13.6% |
| STORE_FAST | 480 | 9.1% |
| STORE_GLOBAL | 60 | 1.1% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 60 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 480 | 72.7% |
| LOAD_CONST | 180 | 27.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 300 | 45.5% |
| RETURN_VALUE | 180 | 27.3% |
| CALL_PY_EXACT_ARGS | 120 | 18.2% |
| CALL | 60 | 9.1% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,574,540 | 100.0% |
| LOAD_FAST_LOAD_FAST | 3,780 | 0.0% |
| BINARY_SUBSCR | 900 | 0.0% |
| LOAD_CONST | 720 | 0.0% |
| LOAD_ATTR_MODULE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 14,570,240 | 99.9% |
| LOAD_CONST | 4,020 | 0.0% |
| RETURN_VALUE | 2,100 | 0.0% |
| BINARY_SUBSCR_DICT | 1,440 | 0.0% |
| LOAD_FAST | 960 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 14,570,240 | 99.5% |
| LOAD_FAST | 56,064 | 0.4% |
| LOAD_FAST_LOAD_FAST | 7,280 | 0.0% |
| LOAD_CONST | 5,080 | 0.0% |
| CALL | 2,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,567,580 | 99.5% |
| TO_BOOL_BOOL | 19,944 | 0.1% |
| STORE_FAST | 18,600 | 0.1% |
| YIELD_VALUE | 9,600 | 0.1% |
| RETURN_VALUE | 7,080 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 2,280 | 52.1% |
| LOAD_FAST | 1,020 | 23.3% |
| BUILD_MAP | 960 | 21.9% |
| MAP_ADD | 60 | 1.4% |
| CALL_INTRINSIC_1 | 60 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,040 | 46.6% |
| LOAD_CONST | 960 | 21.9% |
| CALL_LIST_APPEND | 960 | 21.9% |
| RETURN_GENERATOR | 120 | 2.7% |
| RESUME_CHECK | 120 | 2.7% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_EX | 960 | 88.9% |
| CALL_FUNCTION_EX | 60 | 5.6% |
| BUILD_MAP | 60 | 5.6% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,140 | 32.2% |
| STORE_FAST | 1,080 | 30.5% |
| RESUME_CHECK | 900 | 25.4% |
| PUSH_EXC_INFO | 240 | 6.8% |
| LOAD_FAST | 180 | 5.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280 | 48.3% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 20.7% |
| COMPARE_OP | 120 | 20.7% |
| RETURN_VALUE | 60 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 360 | 62.1% |
| COMPARE_OP | 120 | 20.7% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 60 | 10.3% |
| COMPARE_OP_STR | 20 | 3.4% |
| COMPARE_OP_INT | 20 | 3.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 58,268,820 | 99.6% |
| LOAD_FAST_LOAD_FAST | 238,320 | 0.4% |
| LOAD_GLOBAL_MODULE | 3,540 | 0.0% |
| LOAD_CONST | 2,040 | 0.0% |
| LOAD_ATTR_MODULE | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 58,269,120 | 99.6% |
| POP_JUMP_IF_FALSE | 245,880 | 0.4% |
| RETURN_VALUE | 540 | 0.0% |
| POP_JUMP_IF_TRUE | 540 | 0.0% |
| INSTRUMENTED_RETURN_VALUE | 240 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 360 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,480 | 55.2% |
| RETURN_VALUE | 960 | 15.2% |
| LOAD_FAST | 660 | 10.5% |
| LOAD_CONST | 360 | 5.7% |
| LOAD_ATTR | 240 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 4,480 | 71.1% |
| TO_BOOL | 560 | 8.9% |
| LOAD_FAST | 540 | 8.6% |
| TO_BOOL_NONE | 460 | 7.3% |
| POP_EXCEPT | 180 | 2.9% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,320 | 66.7% |
| CACHE | 1,920 | 29.6% |
| CALL | 180 | 2.8% |
| CALL_FUNCTION_EX | 60 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 3,900 | 60.2% |
| RESUME_CHECK | 2,520 | 38.9% |
| RESUME | 60 | 0.9% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 66.7% |
| NOP | 120 | 33.3% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 2,280 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_STR | 72,835,860 | 100.0% |
| TO_BOOL_STR | 7,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 72,839,160 | 100.0% |
| POP_JUMP_IF_FALSE | 4,620 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 247,020 | 97.7% |
| GET_ITER | 5,220 | 2.1% |
| FOR_ITER | 640 | 0.3% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 241,140 | 95.3% |
| STORE_FAST | 5,820 | 2.3% |
| NOP | 4,200 | 1.7% |
| RETURN_CONST | 660 | 0.3% |
| FOR_ITER | 640 | 0.3% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 480 | 57.1% |
| LOAD_FAST | 180 | 21.4% |
| LOAD_CONST | 180 | 21.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 540 | 64.3% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 120 | 14.3% |
| STORE_FAST | 60 | 7.1% |
| LOAD_FAST | 60 | 7.1% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 60 | 7.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 241,380 | 84.1% |
| POP_JUMP_IF_FALSE | 16,440 | 5.7% |
| POP_TOP | 12,960 | 4.5% |
| LIST_APPEND | 5,040 | 1.8% |
| BINARY_OP_INPLACE_ADD_UNICODE | 4,200 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 247,020 | 86.0% |
| FOR_ITER_LIST | 34,320 | 12.0% |
| LOAD_FAST | 4,140 | 1.4% |
| LOAD_GLOBAL_MODULE | 900 | 0.3% |
| FOR_ITER_TUPLE | 720 | 0.3% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,360 | 73.7% |
| POP_TOP | 960 | 21.1% |
| STORE_ATTR | 180 | 3.9% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,280 | 50.0% |
| LOAD_FAST | 2,040 | 44.7% |
| LOAD_GLOBAL_BUILTIN | 180 | 3.9% |
| LOAD_GLOBAL | 60 | 1.3% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,040 | 94.4% |
| BUILD_TUPLE | 300 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,040 | 94.4% |
| INSTRUMENTED_JUMP_BACKWARD | 300 | 5.6% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020 | 94.4% |
| LOAD_DEREF | 60 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,080 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 145,698,220 | 58.8% |
| LOAD_ATTR | 102,033,820 | 41.2% |
| LOAD_GLOBAL_MODULE | 20,840 | 0.0% |
| LOAD_FAST_LOAD_FAST | 2,940 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 102,033,820 | 41.2% |
| CONTAINS_OP | 58,268,820 | 23.5% |
| STORE_FAST | 43,706,340 | 17.6% |
| LOAD_FAST | 14,570,420 | 5.9% |
| LOAD_CONST | 14,568,300 | 5.9% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160,259,700 | 78.5% |
| STORE_ATTR_INSTANCE_VALUE | 14,573,520 | 7.1% |
| LOAD_ATTR | 14,568,300 | 7.1% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 14,567,760 | 7.1% |
| LOAD_CONST | 7,380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_STR | 116,539,300 | 57.1% |
| COMPARE_OP_INT | 29,139,280 | 14.3% |
| LOAD_FAST | 14,583,060 | 7.1% |
| STORE_FAST | 14,572,740 | 7.1% |
| BINARY_OP_SUBTRACT_INT | 14,569,920 | 7.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,600 | 51.9% |
| POP_JUMP_IF_FALSE | 4,020 | 21.8% |
| LOAD_GLOBAL_BUILTIN | 1,920 | 10.4% |
| RETURN_VALUE | 480 | 2.6% |
| LOAD_GLOBAL_MODULE | 480 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 9,600 | 51.9% |
| RETURN_VALUE | 1,920 | 10.4% |
| LOAD_GLOBAL_MODULE | 1,920 | 10.4% |
| LOAD_FAST | 1,920 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 960 | 5.2% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 327,774,960 | 40.5% |
| STORE_ATTR_INSTANCE_VALUE | 116,541,900 | 14.4% |
| LOAD_GLOBAL | 65,567,400 | 8.1% |
| STORE_FAST | 43,794,324 | 5.4% |
| LOAD_ATTR_METHOD_NO_DICT | 43,759,104 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 335,058,120 | 41.4% |
| LOAD_CONST | 160,259,700 | 19.8% |
| LOAD_ATTR | 145,698,220 | 18.0% |
| STORE_ATTR_INSTANCE_VALUE | 87,413,160 | 10.8% |
| TO_BOOL_BOOL | 29,143,320 | 3.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 540 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,140,800 | 49.5% |
| POP_TOP | 29,134,260 | 49.5% |
| POP_JUMP_IF_FALSE | 252,120 | 0.4% |
| STORE_FAST_STORE_FAST | 238,320 | 0.4% |
| LOAD_GLOBAL_MODULE | 13,680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 43,704,620 | 74.3% |
| LOAD_ATTR_INSTANCE_VALUE | 14,568,440 | 24.8% |
| LOAD_FAST | 250,380 | 0.4% |
| CONTAINS_OP | 238,320 | 0.4% |
| COMPARE_OP_STR | 14,520 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RESUME | 58,280,880 | 72.7% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 14,571,060 | 18.2% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 7,287,680 | 9.1% |
| STORE_FAST | 11,620 | 0.0% |
| NOP | 3,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 65,567,400 | 81.8% |
| INSTRUMENTED_POP_JUMP_IF_NONE | 14,567,340 | 18.2% |
| LOAD_ATTR_MODULE | 14,260 | 0.0% |
| LOAD_GLOBAL_MODULE | 6,480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 3,600 | 0.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,100 | 100.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 840 | 87.5% |
| RETURN_CONST | 60 | 6.2% |
| LOAD_ATTR | 60 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 900 | 93.8% |
| CALL_FUNCTION_EX | 60 | 6.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 245,880 | 68.9% |
| TO_BOOL_BOOL | 53,800 | 15.1% |
| TO_BOOL_NONE | 16,740 | 4.7% |
| COMPARE_OP_STR | 10,380 | 2.9% |
| TO_BOOL_STR | 10,200 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 252,120 | 70.7% |
| LOAD_GLOBAL_MODULE | 30,280 | 8.5% |
| LOAD_FAST | 29,880 | 8.4% |
| JUMP_BACKWARD | 16,440 | 4.6% |
| RETURN_CONST | 7,740 | 2.2% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020 | 89.5% |
| RETURN_CONST | 60 | 5.3% |
| LOAD_GLOBAL_MODULE | 40 | 3.5% |
| LOAD_GLOBAL | 20 | 1.8% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840 | 74.4% |
| BINARY_SUBSCR_TUPLE_INT | 960 | 18.6% |
| LOAD_ATTR_WITH_HINT | 180 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 2.3% |
| LOAD_GLOBAL_MODULE | 60 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,980 | 38.4% |
| NOP | 1,080 | 20.9% |
| JUMP_BACKWARD | 960 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 600 | 11.6% |
| BUILD_MAP | 240 | 4.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 13,020 | 50.1% |
| TO_BOOL | 4,500 | 17.3% |
| TO_BOOL_STR | 4,020 | 15.5% |
| TO_BOOL_LIST | 1,320 | 5.1% |
| COMPARE_OP_INT | 960 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,820 | 33.9% |
| LOAD_GLOBAL_BUILTIN | 4,080 | 15.7% |
| LOAD_GLOBAL_MODULE | 3,520 | 13.5% |
| RETURN_VALUE | 3,000 | 11.5% |
| JUMP_BACKWARD | 1,620 | 6.2% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 180 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 180 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,740 | 48.1% |
| FOR_ITER_LIST | 5,340 | 33.2% |
| STORE_ATTR_INSTANCE_VALUE | 900 | 5.6% |
| FOR_ITER | 660 | 4.1% |
| POP_TOP | 420 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,960 | 43.3% |
| INTERPRETER_EXIT | 4,680 | 29.1% |
| POP_TOP | 3,120 | 19.4% |
| EXIT_INIT_CHECK | 1,200 | 7.5% |
| SWAP | 60 | 0.4% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 3,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,920 | 48.5% |
| LOAD_FAST | 1,920 | 48.5% |
| STORE_FAST | 60 | 1.5% |
| LOAD_DEREF | 60 | 1.5% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,240 | 56.7% |
| LOAD_FAST_LOAD_FAST | 3,340 | 30.4% |
| STORE_ATTR | 1,120 | 10.2% |
| LOAD_DEREF | 260 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 3,920 | 35.6% |
| LOAD_FAST | 2,640 | 24.0% |
| LOAD_CONST | 1,140 | 10.4% |
| STORE_ATTR | 1,120 | 10.2% |
| LOAD_FAST_LOAD_FAST | 900 | 8.2% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,920 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 43,706,340 | 49.9% |
| LOAD_CONST | 14,572,740 | 16.6% |
| BINARY_SUBSCR | 14,567,400 | 16.6% |
| COMPARE_OP_INT | 14,567,340 | 16.6% |
| FOR_ITER_LIST | 29,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,794,324 | 50.0% |
| LOAD_FAST_LOAD_FAST | 29,140,800 | 33.3% |
| INSTRUMENTED_JUMP_FORWARD | 14,567,400 | 16.6% |
| LOAD_GLOBAL_MODULE | 23,860 | 0.0% |
| NOP | 15,720 | 0.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 5,040 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 243,360 | 95.8% |
| UNPACK_SEQUENCE_TUPLE | 8,400 | 3.3% |
| UNPACK_EX | 960 | 0.4% |
| STORE_FAST_STORE_FAST | 960 | 0.4% |
| BINARY_SLICE | 420 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 238,320 | 93.8% |
| STORE_FAST | 7,440 | 2.9% |
| LOAD_FAST | 3,720 | 1.5% |
| LOAD_GLOBAL_MODULE | 2,340 | 0.9% |
| STORE_FAST_STORE_FAST | 960 | 0.4% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 50.0% |
| RETURN_VALUE | 60 | 25.0% |
| BUILD_MAP | 60 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 50.0% |
| INSTRUMENTED_RETURN_CONST | 60 | 25.0% |
| BUILD_MAP | 60 | 25.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,060 | 63.7% |
| BUILD_LIST | 600 | 12.5% |
| LOAD_FAST_AND_CLEAR | 540 | 11.2% |
| FOR_ITER_LIST | 480 | 10.0% |
| RETURN_CONST | 60 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 3,000 | 62.5% |
| BUILD_LIST | 540 | 11.2% |
| STORE_FAST | 480 | 10.0% |
| FOR_ITER_LIST | 480 | 10.0% |
| LOAD_FAST | 120 | 2.5% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 960 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 14,567,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,567,220 | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 9,600 | 87.9% |
| BINARY_OP | 900 | 8.2% |
| BUILD_STRING | 300 | 2.7% |
| LOAD_CONST | 120 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 10,920 | 100.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RESUME | 1,080 | 69.2% |
| CALL_PY_EXACT_ARGS | 240 | 15.4% |
| LOAD_ATTR_PROPERTY | 60 | 3.8% |
| COPY_FREE_VARS | 60 | 3.8% |
| CALL_FUNCTION_EX | 60 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 600 | 38.5% |
| LOAD_FAST | 540 | 34.6% |
| INSTRUMENTED_RESUME | 300 | 19.2% |
| LOAD_DEREF | 60 | 3.8% |
| LOAD_CONST | 60 | 3.8% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,568,780 | 66.7% |
| INSTRUMENTED_RETURN_VALUE | 7,283,520 | 33.3% |
| LOAD_FAST_LOAD_FAST | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 14,567,340 | 66.7% |
| INSTRUMENTED_RETURN_VALUE | 7,283,520 | 33.3% |
| STORE_FAST | 1,260 | 0.0% |
| BINARY_SLICE | 1,140 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,680 | 98.5% |
| LOAD_ATTR_MODULE | 60 | 0.8% |
| CALL_METHOD_DESCRIPTOR_O | 40 | 0.5% |
| BINARY_OP | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 6,600 | 84.6% |
| STORE_FAST | 1,080 | 13.8% |
| CALL_PY_EXACT_ARGS | 100 | 1.3% |
| CALL | 20 | 0.3% |


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
| LOAD_CONST | 14,569,920 | 100.0% |
| LOAD_FAST | 1,920 | 0.0% |
| BINARY_OP | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 14,567,040 | 100.0% |
| STORE_FAST | 2,880 | 0.0% |
| LOAD_FAST | 1,920 | 0.0% |
| CALL | 960 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,780 | 65.8% |
| BUILD_TUPLE | 1,440 | 19.8% |
| LOAD_FAST_LOAD_FAST | 720 | 9.9% |
| RETURN_VALUE | 180 | 2.5% |
| CALL | 120 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,980 | 27.3% |
| STORE_FAST | 1,920 | 26.4% |
| LOAD_CONST | 960 | 13.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 13.2% |
| CALL_METHOD_DESCRIPTOR_O | 720 | 9.9% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 180 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 51.6% |
| LOAD_FAST_LOAD_FAST | 900 | 48.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,860 | 100.0% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 960 | 41.0% |
| POP_JUMP_IF_NOT_NONE | 960 | 41.0% |
| STORE_FAST | 420 | 17.9% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 33.3% |
| LOAD_FAST_LOAD_FAST | 300 | 25.0% |
| CALL | 180 | 15.0% |
| LOAD_CONST | 120 | 10.0% |
| LOAD_GLOBAL_MODULE | 80 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,200 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 240 | 57.1% |
| LOAD_CONST | 80 | 19.0% |
| CALL | 60 | 14.3% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RESUME | 240 | 57.1% |
| POP_TOP | 120 | 28.6% |
| RESUME_CHECK | 60 | 14.3% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,520 | 85.3% |
| LOAD_ATTR_INSTANCE_VALUE | 400 | 4.5% |
| CALL | 220 | 2.5% |
| LOAD_ATTR_WITH_HINT | 180 | 2.0% |
| CALL_BUILTIN_CLASS | 180 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 7,260 | 82.3% |
| LOAD_FAST | 960 | 10.9% |
| STORE_FAST | 180 | 2.0% |
| LOAD_DEREF | 180 | 2.0% |
| CALL_BUILTIN_CLASS | 180 | 2.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,200 | 38.4% |
| LOAD_FAST | 2,340 | 28.1% |
| LOAD_FAST_LOAD_FAST | 1,240 | 14.9% |
| CALL | 1,140 | 13.7% |
| LOAD_ATTR_INSTANCE_VALUE | 420 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,120 | 37.4% |
| RETURN_VALUE | 1,260 | 15.1% |
| POP_TOP | 1,080 | 12.9% |
| LOAD_CONST | 1,080 | 12.9% |
| CALL_BUILTIN_O | 1,080 | 12.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,840 | 99.7% |
| LOAD_GLOBAL_MODULE | 40 | 0.1% |
| CALL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 27,420 | 85.9% |
| COPY | 3,480 | 10.9% |
| RETURN_VALUE | 540 | 1.7% |
| INSTRUMENTED_RETURN_VALUE | 420 | 1.3% |
| CALL_TUPLE_1 | 40 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 7,140 | 58.6% |
| RETURN_GENERATOR | 3,840 | 31.5% |
| CALL_BUILTIN_FAST | 1,080 | 8.9% |
| LOAD_CONST | 40 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,140 | 58.6% |
| TO_BOOL_BOOL | 4,920 | 40.4% |
| POP_TOP | 120 | 1.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 21,260 | 49.0% |
| LOAD_ATTR | 20,200 | 46.6% |
| LOAD_GLOBAL_MODULE | 1,620 | 3.7% |
| BUILD_TUPLE | 220 | 0.5% |
| CALL | 80 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 23,040 | 53.1% |
| TO_BOOL_BOOL | 20,260 | 46.7% |
| TO_BOOL | 80 | 0.2% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,820 | 99.5% |
| CALL | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,980 | 51.6% |
| LOAD_FAST | 960 | 25.0% |
| BINARY_OP | 420 | 10.9% |
| UNARY_NEGATIVE | 300 | 7.8% |
| BINARY_SUBSCR_STR_INT | 180 | 4.7% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 960 | 66.7% |
| LOAD_FAST | 360 | 25.0% |
| CALL | 80 | 5.6% |
| LOAD_CONST | 40 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,080 | 75.0% |
| NOP | 240 | 16.7% |
| RETURN_CONST | 60 | 4.2% |
| INSTRUMENTED_RETURN_CONST | 60 | 4.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 14,567,280 | 100.0% |
| BINARY_SUBSCR_DICT | 960 | 0.0% |
| LOAD_FAST | 660 | 0.0% |
| LOAD_CONST | 560 | 0.0% |
| CALL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE | 14,567,240 | 100.0% |
| STORE_FAST | 1,200 | 0.0% |
| RETURN_VALUE | 960 | 0.0% |
| POP_TOP | 120 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 760 | 57.6% |
| LOAD_FAST_LOAD_FAST | 480 | 36.4% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 3.0% |
| CALL | 40 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 660 | 50.0% |
| CONTAINS_OP | 540 | 40.9% |
| POP_TOP | 120 | 9.1% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,760 | 94.6% |
| CALL | 60 | 3.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 40 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200 | 64.5% |
| GET_ITER | 660 | 35.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,141,440 | 100.0% |
| BINARY_SUBSCR_DICT | 720 | 0.0% |
| RETURN_VALUE | 360 | 0.0% |
| RETURN_GENERATOR | 120 | 0.0% |
| CALL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 29,135,460 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 7,200 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |
| BINARY_OP_ADD_UNICODE | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 14,567,040 | 99.5% |
| LOAD_FAST | 58,560 | 0.4% |
| LOAD_FAST_LOAD_FAST | 7,200 | 0.0% |
| GET_ITER | 4,000 | 0.0% |
| RETURN_VALUE | 3,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RESUME | 14,577,960 | 99.5% |
| RESUME_CHECK | 62,640 | 0.4% |
| COPY_FREE_VARS | 4,320 | 0.0% |
| MAKE_CELL | 2,100 | 0.0% |
| RESUME | 240 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,080 | 62.1% |
| LOAD_FAST | 480 | 27.6% |
| CALL | 100 | 5.7% |
| PUSH_NULL | 40 | 2.3% |
| LOAD_GLOBAL_MODULE | 40 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,740 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 180 | 30.0% |
| LOAD_FAST | 180 | 30.0% |
| LOAD_CONST | 180 | 30.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 6.7% |
| CALL | 20 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 90.0% |
| RETURN_VALUE | 60 | 10.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,440 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 960 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,139,280 | 100.0% |
| LOAD_ATTR | 960 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,567,340 | 50.0% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 14,567,100 | 50.0% |
| POP_JUMP_IF_FALSE | 5,340 | 0.0% |
| POP_JUMP_IF_TRUE | 960 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 116,539,300 | 88.9% |
| LOAD_ATTR_INSTANCE_VALUE | 14,567,340 | 11.1% |
| LOAD_FAST_LOAD_FAST | 14,520 | 0.0% |
| BINARY_OP | 420 | 0.0% |
| INSTRUMENTED_RETURN_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 72,835,860 | 55.5% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 43,708,380 | 33.3% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 14,567,580 | 11.1% |
| POP_JUMP_IF_FALSE | 10,380 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 34,320 | 84.2% |
| LOAD_FAST | 4,000 | 9.8% |
| GET_ITER | 1,800 | 4.4% |
| SWAP | 480 | 1.2% |
| FOR_ITER | 140 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,040 | 71.3% |
| RETURN_CONST | 5,340 | 13.1% |
| STORE_FAST_LOAD_FAST | 5,040 | 12.4% |
| SWAP | 480 | 1.2% |
| LOAD_FAST | 300 | 0.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 720 | 75.0% |
| GET_ITER | 240 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 720 | 75.0% |
| JUMP_BACKWARD | 240 | 25.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |
| LOAD_ATTR | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 50.0% |
| BINARY_OP | 60 | 50.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 335,058,120 | 95.8% |
| LOAD_FAST_LOAD_FAST | 14,568,440 | 4.2% |
| LOAD_ATTR | 2,420 | 0.0% |
| LOAD_DEREF | 960 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 116,538,040 | 33.3% |
| LOAD_ATTR_METHOD_NO_DICT | 58,269,100 | 16.7% |
| INSTRUMENTED_RETURN_VALUE | 58,268,760 | 16.7% |
| LOAD_FAST | 43,706,280 | 12.5% |
| INSTRUMENTED_POP_JUMP_IF_NONE | 29,134,200 | 8.3% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 40 | 66.7% |
| LOAD_ATTR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 66.7% |
| CALL | 20 | 33.3% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 58,269,100 | 99.9% |
| LOAD_FAST | 38,604 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 16,720 | 0.0% |
| LOAD_DEREF | 9,600 | 0.0% |
| LOAD_ATTR_MODULE | 1,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,759,104 | 75.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 14,567,280 | 25.0% |
| LOAD_CONST | 4,740 | 0.0% |
| LOAD_GLOBAL_MODULE | 2,280 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,760 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,440 | 43.1% |
| LOAD_FAST | 1,040 | 31.1% |
| LOAD_ATTR | 740 | 22.2% |
| LOAD_ATTR_MODULE | 120 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,000 | 29.9% |
| LOAD_CONST | 960 | 28.7% |
| CALL_PY_EXACT_ARGS | 720 | 21.6% |
| CALL | 420 | 12.6% |
| LOAD_FAST_LOAD_FAST | 240 | 7.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 57,300 | 65.7% |
| LOAD_GLOBAL | 14,260 | 16.3% |
| LOAD_ATTR_MODULE | 13,960 | 16.0% |
| LOAD_ATTR | 880 | 1.0% |
| LOAD_FAST | 720 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 43,780 | 50.2% |
| LOAD_ATTR_MODULE | 13,960 | 16.0% |
| LOAD_FAST | 13,320 | 15.3% |
| LOAD_CONST | 6,120 | 7.0% |
| LOAD_GLOBAL_MODULE | 2,760 | 3.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,000 | 98.4% |
| LOAD_ATTR | 240 | 1.4% |
| LOAD_FAST_LOAD_FAST | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 16,720 | 96.8% |
| LOAD_CONST | 180 | 1.0% |
| TO_BOOL_LIST | 160 | 0.9% |
| TO_BOOL | 80 | 0.5% |
| LOAD_ATTR | 80 | 0.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 60.0% |
| RETURN_VALUE | 40 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 13.3% |
| LOAD_ATTR | 40 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240 | 80.0% |
| RESUME | 60 | 20.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,560 | 56.5% |
| LOAD_ATTR_INSTANCE_VALUE | 560 | 20.3% |
| LOAD_ATTR | 480 | 17.4% |
| LOAD_DEREF | 160 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 17.4% |
| LOAD_GLOBAL_MODULE | 360 | 13.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 10.1% |
| CALL_PY_EXACT_ARGS | 280 | 10.1% |
| RETURN_VALUE | 180 | 6.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 34,660 | 36.2% |
| LOAD_FAST | 22,580 | 23.6% |
| STORE_FAST | 11,200 | 11.7% |
| NOP | 5,500 | 5.7% |
| POP_JUMP_IF_FALSE | 4,960 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,080 | 60.7% |
| CALL_ISINSTANCE | 21,260 | 22.2% |
| LOAD_GLOBAL_MODULE | 5,700 | 6.0% |
| CHECK_EXC_MATCH | 3,480 | 3.6% |
| LOAD_FAST_LOAD_FAST | 2,340 | 2.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_RETURN_VALUE | 7,283,520 | 97.9% |
| POP_JUMP_IF_FALSE | 30,280 | 0.4% |
| LOAD_FAST | 29,640 | 0.4% |
| RESUME_CHECK | 26,320 | 0.4% |
| STORE_FAST | 23,860 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,334,340 | 98.6% |
| LOAD_ATTR_MODULE | 57,300 | 0.8% |
| LOAD_ATTR | 20,840 | 0.3% |
| LOAD_FAST_LOAD_FAST | 13,680 | 0.2% |
| CONTAINS_OP | 3,540 | 0.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,920 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 62,640 | 61.3% |
| CACHE | 13,740 | 13.4% |
| RESUME_CHECK | 6,900 | 6.8% |
| CALL | 5,640 | 5.5% |
| POP_TOP | 4,200 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 34,660 | 33.9% |
| LOAD_GLOBAL_MODULE | 26,320 | 25.8% |
| LOAD_FAST | 11,460 | 11.2% |
| POP_TOP | 10,920 | 10.7% |
| NOP | 7,500 | 7.3% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 87,413,160 | 66.7% |
| LOAD_FAST_LOAD_FAST | 43,704,620 | 33.3% |
| STORE_ATTR | 3,920 | 0.0% |
| LOAD_DEREF | 360 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 116,541,900 | 88.9% |
| LOAD_CONST | 14,573,520 | 11.1% |
| LOAD_FAST_LOAD_FAST | 1,860 | 0.0% |
| BUILD_LIST | 1,020 | 0.0% |
| LOAD_GLOBAL_MODULE | 940 | 0.0% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 42.9% |
| LOAD_DEREF | 160 | 38.1% |
| STORE_ATTR | 80 | 19.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 42.9% |
| LOAD_DEREF | 120 | 28.6% |
| RETURN_CONST | 60 | 14.3% |
| LOAD_GLOBAL_MODULE | 40 | 9.5% |
| LOAD_GLOBAL | 20 | 4.8% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 239,440 | 98.7% |
| LOAD_FAST_LOAD_FAST | 1,980 | 0.8% |
| CALL | 1,080 | 0.4% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 241,380 | 99.5% |
| LOAD_GLOBAL | 360 | 0.1% |
| LOAD_GLOBAL_MODULE | 300 | 0.1% |
| LOAD_CONST | 240 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,080 | 49.5% |
| CALL | 900 | 41.3% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 5.5% |
| COPY | 40 | 1.8% |
| TO_BOOL_NONE | 20 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,980 | 90.8% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 120 | 5.5% |
| POP_JUMP_IF_TRUE | 60 | 2.8% |
| TO_BOOL_NONE | 20 | 0.9% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 116,538,040 | 80.0% |
| LOAD_FAST | 29,143,320 | 20.0% |
| RETURN_VALUE | 25,280 | 0.0% |
| CALL_ISINSTANCE | 20,260 | 0.0% |
| CALL | 19,944 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 145,685,880 | 100.0% |
| POP_JUMP_IF_FALSE | 53,800 | 0.0% |
| POP_JUMP_IF_TRUE | 13,020 | 0.0% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 5,304 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 64.5% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 12.9% |
| TO_BOOL | 220 | 11.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 160 | 8.6% |
| LOAD_DEREF | 40 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,320 | 71.0% |
| POP_JUMP_IF_FALSE | 420 | 22.6% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 60 | 3.2% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 60 | 3.2% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 14,568,380 | 99.9% |
| LOAD_FAST | 16,460 | 0.1% |
| COPY | 460 | 0.0% |
| TO_BOOL | 320 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 14,568,120 | 99.9% |
| POP_JUMP_IF_FALSE | 16,740 | 0.1% |
| POP_JUMP_IF_TRUE | 600 | 0.0% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 240 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 20 | 0.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,580 | 82.8% |
| COPY | 4,480 | 15.1% |
| LOAD_ATTR_MODULE | 360 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 0.8% |
| TO_BOOL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,200 | 34.3% |
| EXTENDED_ARG | 7,920 | 26.7% |
| INSTRUMENTED_POP_JUMP_IF_FALSE | 6,600 | 22.2% |
| POP_JUMP_IF_TRUE | 4,020 | 13.5% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 960 | 3.2% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 7,200 | 85.7% |
| LOAD_FAST | 960 | 11.4% |
| FOR_ITER_LIST | 240 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 8,400 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 241,140 | 99.1% |
| RETURN_VALUE | 1,680 | 0.7% |
| INSTRUMENTED_RETURN_VALUE | 240 | 0.1% |
| INSTRUMENTED_FOR_ITER | 240 | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 243,360 | 100.0% |


</details>

### INSTRUMENTED_RESUME

<details>
<summary> Successors and predecessors for INSTRUMENTED_RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 58,268,760 | 80.0% |
| CALL_PY_EXACT_ARGS | 14,577,960 | 20.0% |
| CALL | 3,300 | 0.0% |
| RESUME_CHECK | 900 | 0.0% |
| INSTRUMENTED_RESUME | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 58,280,880 | 80.0% |
| LOAD_FAST | 14,569,320 | 20.0% |
| RESUME | 1,080 | 0.0% |
| INSTRUMENTED_RESUME | 660 | 0.0% |
| LOAD_CONST | 180 | 0.0% |


</details>

### INSTRUMENTED_RETURN_VALUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 58,268,760 | 80.0% |
| LOAD_FAST | 7,288,320 | 10.0% |
| BINARY_OP_ADD_INT | 7,283,520 | 10.0% |
| INSTRUMENTED_RETURN_VALUE | 960 | 0.0% |
| CALL | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 58,268,700 | 80.0% |
| LOAD_GLOBAL_MODULE | 7,283,520 | 10.0% |
| BINARY_OP_ADD_INT | 7,283,520 | 10.0% |
| STORE_FAST | 5,640 | 0.0% |
| TO_BOOL_BOOL | 1,200 | 0.0% |


</details>

### INSTRUMENTED_RETURN_CONST

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_POP_JUMP_IF_FALSE | 4,800 | 87.9% |
| POP_TOP | 300 | 5.5% |
| INSTRUMENTED_FOR_ITER | 240 | 4.4% |
| STORE_GLOBAL | 60 | 1.1% |
| CALL_LIST_APPEND | 60 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,800 | 87.9% |
| TO_BOOL_BOOL | 400 | 7.3% |
| POP_TOP | 180 | 3.3% |
| INTERPRETER_EXIT | 60 | 1.1% |
| TO_BOOL | 20 | 0.4% |


</details>

### INSTRUMENTED_FOR_ITER

<details>
<summary> Successors and predecessors for INSTRUMENTED_FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_JUMP_BACKWARD | 4,284 | 51.2% |
| GET_ITER | 4,020 | 48.1% |
| SWAP | 60 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,404 | 52.7% |
| NOP | 3,060 | 36.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 240 | 2.9% |
| LOAD_CONST | 240 | 2.9% |
| INSTRUMENTED_RETURN_CONST | 240 | 2.9% |


</details>

### INSTRUMENTED_JUMP_FORWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,567,400 | 100.0% |
| LOAD_ATTR | 240 | 0.0% |
| STORE_ATTR | 180 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,567,340 | 100.0% |
| LOAD_GLOBAL | 300 | 0.0% |
| STORE_FAST | 240 | 0.0% |


</details>

### INSTRUMENTED_JUMP_BACKWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,060 | 41.7% |
| BINARY_OP_INPLACE_ADD_UNICODE | 3,060 | 41.7% |
| INSTRUMENTED_POP_JUMP_IF_TRUE | 804 | 10.9% |
| LIST_APPEND | 300 | 4.1% |
| POP_TOP | 60 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INSTRUMENTED_FOR_ITER | 4,284 | 58.3% |
| LOAD_FAST | 3,060 | 41.7% |


</details>

### INSTRUMENTED_POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 14,570,160 | 50.0% |
| COMPARE_OP_STR | 14,567,580 | 50.0% |
| TO_BOOL_BOOL | 5,304 | 0.0% |
| TO_BOOL_STR | 960 | 0.0% |
| TO_BOOL_NONE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,571,360 | 50.0% |
| LOAD_GLOBAL | 14,571,060 | 50.0% |
| INSTRUMENTED_JUMP_BACKWARD | 804 | 0.0% |
| INSTRUMENTED_RETURN_VALUE | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 420 | 0.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 145,685,880 | 41.7% |
| EXTENDED_ARG | 72,839,160 | 20.8% |
| CONTAINS_OP | 58,269,120 | 16.7% |
| COMPARE_OP_STR | 43,708,380 | 12.5% |
| TO_BOOL_NONE | 14,568,120 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 327,774,960 | 93.7% |
| LOAD_CONST | 14,567,760 | 4.2% |
| LOAD_GLOBAL | 7,287,680 | 2.1% |
| LOAD_FAST_LOAD_FAST | 9,420 | 0.0% |
| INSTRUMENTED_RETURN_CONST | 4,800 | 0.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 29,134,200 | 66.7% |
| LOAD_GLOBAL | 14,567,340 | 33.3% |
| LOAD_FAST | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,702,080 | 100.0% |


</details>

### INSTRUMENTED_POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for INSTRUMENTED_POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |


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
| specialization.deferred |     14570280 | 99.9% |
|          hit |        11820 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.5% |
| Failure | 3,760 | 99.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 3,680 | 97.9% |
| out of range | 60 | 1.6% |
| list slice | 20 | 0.5% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       242520 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     14578100 | 8.3% |
| specialization.deopt |           40 | 0.0% |
|          hit |    160375164 | 91.7% |
|         miss |         2300 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,480 | 26.9% |
| Failure | 4,020 | 73.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 3,620 | 90.0% |
| other | 200 | 5.0% |
| tuple | 140 | 3.5% |
| dict | 60 | 1.5% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         6480 | 0.0% |
|          hit |     36441180 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 11.1% |
| Failure | 320 | 88.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 80 | 25.0% |
| add other | 80 | 25.0% |
| subtract other | 40 | 12.5% |
| remainder | 40 | 12.5% |
| add different types | 40 | 12.5% |
| multiply different types | 20 | 6.2% |
| and other | 20 | 6.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     14641344 | 20.0% |
|          hit |     58478400 | 80.0% |
|         miss |          180 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,680 | 63.2% |
| Failure | 1,560 | 36.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs | 580 | 37.2% |
| cfunc varargs keywords | 240 | 15.4% |
| code complex parameters | 240 | 15.4% |
| cfunc noargs | 180 | 11.5% |
| class no vectorcall | 120 | 7.7% |
| meth descr method fastcall keywords | 80 | 5.1% |
| cfunc varargs | 60 | 3.8% |
| init not python | 40 | 2.6% |
| wrong number arguments | 20 | 1.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          420 | 0.0% |
|          hit |    160263720 | 100.0% |
|         miss |          180 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 25.0% |
| Failure | 120 | 75.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 40 | 33.3% |
| other | 40 | 33.3% |
| big int | 20 | 16.7% |
| different types | 20 | 16.7% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       252180 | 85.6% |
|          hit |        41700 | 14.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 17.9% |
| Failure | 640 | 82.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| map | 360 | 56.2% |
| dict items | 140 | 21.9% |
| set | 60 | 9.4% |
| dict keys | 40 | 6.2% |
| dict values | 20 | 3.1% |
| other | 20 | 3.1% |


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
| specialization.deferred |    247691020 | 37.8% |
|          hit |    408077564 | 62.2% |
|         miss |          660 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,220 | 7.8% |
| Failure | 62,020 | 92.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 39,540 | 63.8% |
| non object slot | 21,540 | 34.7% |
| method | 300 | 0.5% |
| module attr not found | 280 | 0.5% |
| has managed dict | 180 | 0.3% |
| metaclass attribute | 80 | 0.1% |
| class method obj | 40 | 0.1% |
| mutable class | 40 | 0.1% |
| shadowed | 20 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     80156460 | 91.4% |
|          hit |      7533180 | 8.6% |
|         miss |          180 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,780 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         1920 | 100.0% |


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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         5880 | 0.0% |
|          hit |    131122560 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,000 | 78.1% |
| Failure | 1,120 | 21.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 900 | 80.4% |
| no dict | 80 | 7.1% |
| not in keys | 60 | 5.4% |
| non object slot | 60 | 5.4% |
| class attr simple | 20 | 1.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     14567220 | 98.3% |
|          hit |       251760 | 1.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 2,005,530,924 | 59.8% |
| Not specialized | 387,256,364 | 11.5% |
| Specialized | 962,935,568 | 28.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,024,520 | 100.0% |
| LOAD_ATTR | 247,691,020 | 0.0% |
| LOAD_GLOBAL | 80,156,460 | 0.0% |
| CALL | 14,641,344 | 0.0% |
| TO_BOOL | 14,578,100 | 0.0% |
| BINARY_SUBSCR | 14,570,280 | 0.0% |
| UNPACK_SEQUENCE | 14,567,220 | 0.0% |
| FOR_ITER | 252,180 | 0.0% |
| BINARY_OP | 6,480 | 0.0% |
| STORE_ATTR | 5,880 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME_CHECK | 7,800 | 40.8% |
| RESUME | 7,800 | 40.8% |
| TO_BOOL_NONE | 1,240 | 6.5% |
| TO_BOOL_ALWAYS_TRUE | 1,060 | 5.5% |
| LOAD_ATTR_MODULE | 600 | 3.1% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.9% |
| COMPARE_OP_STR | 180 | 0.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 120 | 0.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60 | 0.3% |
| CALL_PY_WITH_DEFAULTS | 60 | 0.3% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 58,288,680 | 79.9% |
| Calls to Python functions inlined | 14,661,540 | 20.1% |
| Calls via PyEval_EvalFrame (total) | 58,288,680 | 79.9% |
| Calls via PyEval_EvalFrame (vector) | 58,273,560 | 79.9% |
| Calls via PyEval_EvalFrame (generator) | 15,120 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 58,273,560 | 79.9% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 360 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 840 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 72,936,300 | 100.0% |
| Frame objects created | 14,571,560 | 20.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,818,944 | 3.5% |
| Frees to freelist | 14,821,084 |  |
| Allocations | 408,448,480 | 96.5% |
| Allocations to 512 bytes | 408,443,200 | 96.5% |
| Allocations to 4 kbytes | 2,460 | 0.0% |
| Allocations over 4 kbytes | 2,820 | 0.0% |
| Frees | 408,468,897 |  |
| New values | 480 |  |
| Interpreter increfs | 1,225,431,452 | 68.8% |
| Interpreter decrefs | 1,429,751,916 | 64.9% |
| Increfs | 554,822,732 | 31.2% |
| Decrefs | 773,716,475 | 35.1% |
| Materialize dict (on request) | 180 | 37.5% |
| Materialize dict (new key) | 100 | 20.8% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 8.3% |
| Method cache hits | 247,774,767 |  |
| Method cache misses | 2,193 |  |
| Method cache collisions | 2,058 |  |
| Method cache dunder hits | 64,551 |  |
| Method cache dunder misses | 169 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 7,200 | 226,880 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


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
