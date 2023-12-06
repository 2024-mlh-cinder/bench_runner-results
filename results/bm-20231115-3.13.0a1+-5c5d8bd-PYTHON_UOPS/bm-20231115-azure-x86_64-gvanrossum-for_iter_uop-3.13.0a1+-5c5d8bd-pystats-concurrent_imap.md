
# Pystats results

- benchmark: concurrent_imap
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 70,681,494 | 17.6% | 17.6% |  |
| RESUME_CHECK | 28,907,480 | 7.2% | 24.8% | 0.0% |
| STORE_FAST | 21,881,441 | 5.4% | 30.2% |  |
| POP_TOP | 19,172,402 | 4.8% | 35.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 19,149,114 | 4.8% | 39.7% | 1.1% |
| RETURN_VALUE | 16,797,362 | 4.2% | 43.9% |  |
| POP_JUMP_IF_FALSE | 13,345,784 | 3.3% | 47.2% |  |
| LOAD_CONST | 12,189,407 | 3.0% | 50.2% |  |
| INTERPRETER_EXIT | 10,586,707 | 2.6% | 52.9% |  |
| LOAD_GLOBAL_MODULE | 10,428,528 | 2.6% | 55.5% | 0.0% |
| ENTER_EXECUTOR | 10,009,450 | 2.5% | 58.0% |  |
| CALL | 8,710,501 | 2.2% | 60.1% |  |
| LOAD_FAST_LOAD_FAST | 8,571,632 | 2.1% | 62.3% |  |
| CALL_PY_EXACT_ARGS | 7,918,639 | 2.0% | 64.2% | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,099,658 | 1.8% | 66.0% | 1.2% |
| LOAD_ATTR | 6,601,088 | 1.6% | 67.6% |  |
| RETURN_CONST | 6,564,137 | 1.6% | 69.3% |  |
| NOP | 6,530,309 | 1.6% | 70.9% |  |
| YIELD_VALUE | 6,529,020 | 1.6% | 72.5% |  |
| COPY | 5,999,430 | 1.5% | 74.0% |  |
| JUMP_BACKWARD | 5,999,418 | 1.5% | 75.5% |  |
| FOR_ITER_GEN | 5,994,800 | 1.5% | 77.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,091,305 | 1.3% | 78.3% |  |
| TO_BOOL_BOOL | 4,984,360 | 1.2% | 79.5% |  |
| LOAD_GLOBAL_BUILTIN | 4,909,158 | 1.2% | 80.7% | 0.0% |
| PUSH_NULL | 4,520,604 | 1.1% | 81.8% |  |
| BINARY_OP | 4,273,650 | 1.1% | 82.9% |  |
| STORE_FAST_STORE_FAST | 3,779,989 | 0.9% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,757,139 | 0.9% | 84.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,361,874 | 0.8% | 85.6% | 7.3% |
| TO_BOOL_INT | 3,132,592 | 0.8% | 86.4% |  |
| COMPARE_OP_INT | 2,674,527 | 0.7% | 87.1% | 0.3% |
| BUILD_TUPLE | 2,539,385 | 0.6% | 87.7% |  |
| CALL_FUNCTION_EX | 2,308,018 | 0.6% | 88.3% |  |
| POP_JUMP_IF_TRUE | 2,242,368 | 0.6% | 88.8% |  |
| FOR_ITER_LIST | 2,239,172 | 0.6% | 89.4% |  |
| CALL_PY_WITH_DEFAULTS | 2,001,351 | 0.5% | 89.9% |  |
| SWAP | 1,820,105 | 0.5% | 90.3% |  |
| BEFORE_WITH | 1,585,524 | 0.4% | 90.7% |  |
| LOAD_ATTR_MODULE | 1,568,815 | 0.4% | 91.1% | 0.1% |
| TO_BOOL | 1,410,060 | 0.4% | 91.5% |  |
| COMPARE_OP_STR | 1,316,892 | 0.3% | 91.8% |  |
| JUMP_FORWARD | 1,257,558 | 0.3% | 92.1% |  |
| CONTAINS_OP | 1,247,297 | 0.3% | 92.4% |  |
| CALL_BUILTIN_CLASS | 1,165,640 | 0.3% | 92.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,162,462 | 0.3% | 93.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,156,029 | 0.3% | 93.3% |  |
| LOAD_DEREF | 1,134,077 | 0.3% | 93.6% |  |
| UNPACK_SEQUENCE_TUPLE | 1,104,457 | 0.3% | 93.8% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,094,017 | 0.3% | 94.1% | 0.0% |
| COPY_FREE_VARS | 1,085,657 | 0.3% | 94.4% |  |
| BINARY_OP_ADD_INT | 1,077,196 | 0.3% | 94.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,057,629 | 0.3% | 94.9% |  |
| CALL_BUILTIN_FAST | 1,031,290 | 0.3% | 95.2% |  |
| LOAD_SUPER_ATTR_METHOD | 1,024,217 | 0.3% | 95.4% |  |
| UNARY_INVERT | 1,022,089 | 0.3% | 95.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,009,239 | 0.3% | 95.9% | 0.0% |
| GET_ITER | 1,003,523 | 0.2% | 96.2% |  |
| BUILD_LIST | 945,023 | 0.2% | 96.4% |  |
| BUILD_MAP | 908,596 | 0.2% | 96.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 831,968 | 0.2% | 96.8% | 0.0% |
| POP_JUMP_IF_NONE | 793,103 | 0.2% | 97.0% |  |
| STORE_SUBSCR_DICT | 787,707 | 0.2% | 97.2% |  |
| CALL_ISINSTANCE | 720,401 | 0.2% | 97.4% |  |
| LOAD_FAST_CHECK | 704,430 | 0.2% | 97.6% |  |
| EXIT_INIT_CHECK | 671,052 | 0.2% | 97.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 671,052 | 0.2% | 97.9% |  |
| LOAD_ATTR_PROPERTY | 648,128 | 0.2% | 98.1% | 1.9% |
| BINARY_SUBSCR | 591,851 | 0.1% | 98.2% |  |
| DICT_MERGE | 561,380 | 0.1% | 98.4% |  |
| CALL_TUPLE_1 | 550,160 | 0.1% | 98.5% |  |
| LIST_APPEND | 524,414 | 0.1% | 98.6% |  |
| LOAD_FAST_AND_CLEAR | 475,035 | 0.1% | 98.7% |  |
| COMPARE_OP | 360,010 | 0.1% | 98.8% |  |
| TO_BOOL_LIST | 353,256 | 0.1% | 98.9% |  |
| LIST_EXTEND | 287,654 | 0.1% | 99.0% |  |
| CALL_LEN | 257,781 | 0.1% | 99.1% |  |
| CALL_KW | 248,433 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 242,528 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 225,236 | 0.1% | 99.2% | 0.1% |
| BINARY_OP_SUBTRACT_INT | 214,885 | 0.1% | 99.3% |  |
| FOR_ITER_RANGE | 184,586 | 0.0% | 99.3% |  |
| CALL_LIST_APPEND | 170,544 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 159,609 | 0.0% | 99.4% |  |
| UNARY_NOT | 159,265 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 143,772 | 0.0% | 99.5% |  |
| CALL_BUILTIN_O | 136,160 | 0.0% | 99.5% |  |
| MAKE_CELL | 133,100 | 0.0% | 99.6% |  |
| STORE_DEREF | 132,820 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 109,120 | 0.0% | 99.6% |  |
| BINARY_OP_MULTIPLY_FLOAT | 97,240 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_STR_INT | 97,240 | 0.0% | 99.7% |  |
| STORE_ATTR | 95,261 | 0.0% | 99.7% |  |
| DELETE_ATTR | 81,588 | 0.0% | 99.7% |  |
| DELETE_SUBSCR | 75,012 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 63,600 | 0.0% | 99.7% |  |
| STORE_ATTR_SLOT | 61,820 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 59,800 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 58,437 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 50,880 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 44,840 | 0.0% | 99.8% | 13.5% |
| IS_OP | 44,181 | 0.0% | 99.8% |  |
| BUILD_STRING | 38,720 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 38,560 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 38,040 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 37,100 | 0.0% | 99.9% |  |
| POP_EXCEPT | 36,351 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 36,351 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 35,320 | 0.0% | 99.9% |  |
| FOR_ITER | 33,480 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 30,911 | 0.0% | 99.9% |  |
| IMPORT_NAME | 30,240 | 0.0% | 99.9% |  |
| IMPORT_FROM | 29,900 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 28,979 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 26,520 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 25,360 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 24,320 | 0.0% | 100.0% |  |
| BINARY_SLICE | 18,220 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,852 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 17,440 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 17,300 | 0.0% | 100.0% |  |
| RERAISE | 16,320 | 0.0% | 100.0% |  |
| CALL_STR_1 | 11,260 | 0.0% | 100.0% |  |
| END_FOR | 10,880 | 0.0% | 100.0% |  |
| STORE_NAME | 7,480 | 0.0% | 100.0% |  |
| RESUME | 5,980 | 0.0% | 100.0% | 0.1% |
| RAISE_VARARGS | 5,460 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,440 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,200 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 2,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,660 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 800 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 560 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 520 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 464 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 280 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 140 | 0.0% | 100.0% | 14.3% |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,513,189 | 4.4% | 4.4% |
| RESUME_CHECK LOAD_FAST | 16,497,810 | 4.1% | 8.5% |
| CACHE RESUME_CHECK | 10,510,271 | 2.6% | 11.1% |
| RETURN_VALUE INTERPRETER_EXIT | 9,400,963 | 2.3% | 13.4% |
| LOAD_FAST RETURN_VALUE | 8,706,656 | 2.2% | 15.6% |
| STORE_FAST LOAD_FAST | 8,462,835 | 2.1% | 17.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,874,639 | 2.0% | 19.6% |
| POP_TOP ENTER_EXECUTOR | 7,255,081 | 1.8% | 21.4% |
| RESUME_CHECK POP_TOP | 6,528,880 | 1.6% | 23.1% |
| JUMP_BACKWARD FOR_ITER_GEN | 5,983,920 | 1.5% | 24.5% |
| YIELD_VALUE STORE_FAST | 5,983,920 | 1.5% | 26.0% |
| FOR_ITER_GEN RESUME_CHECK | 5,983,920 | 1.5% | 27.5% |
| ENTER_EXECUTOR YIELD_VALUE | 5,971,280 | 1.5% | 29.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,495,895 | 1.4% | 30.4% |
| STORE_FAST JUMP_BACKWARD | 5,440,000 | 1.4% | 31.7% |
| POP_TOP LOAD_FAST | 5,046,355 | 1.3% | 33.0% |
| LOAD_FAST LOAD_ATTR | 4,830,209 | 1.2% | 34.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,720,671 | 1.2% | 35.4% |
| RETURN_CONST POP_TOP | 4,526,855 | 1.1% | 36.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,494,478 | 1.1% | 37.6% |
| NOP LOAD_FAST | 3,877,089 | 1.0% | 38.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,716,260 | 0.9% | 39.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,329,805 | 0.8% | 40.3% |
| LOAD_CONST LOAD_CONST | 3,240,923 | 0.8% | 41.1% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,132,452 | 0.8% | 41.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,047,908 | 0.8% | 42.7% |
| STORE_FAST NOP | 2,953,539 | 0.7% | 43.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,906,476 | 0.7% | 44.1% |
| PUSH_NULL LOAD_FAST | 2,901,290 | 0.7% | 44.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,672,149 | 0.7% | 45.5% |
| COPY STORE_FAST | 2,597,760 | 0.6% | 46.1% |
| STORE_FAST COPY | 2,597,440 | 0.6% | 46.8% |
| LOAD_FAST LOAD_CONST | 2,558,825 | 0.6% | 47.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,548,540 | 0.6% | 48.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,450,849 | 0.6% | 48.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,400,818 | 0.6% | 49.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,355,624 | 0.6% | 49.8% |
| LOAD_CONST CALL | 2,270,422 | 0.6% | 50.4% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,269,487 | 0.6% | 51.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,233,222 | 0.6% | 51.5% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,163,189 | 0.5% | 52.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,121,006 | 0.5% | 52.6% |
| LOAD_FAST PUSH_NULL | 2,099,429 | 0.5% | 53.1% |
| CALL STORE_FAST | 2,040,154 | 0.5% | 53.6% |
| LOAD_ATTR LOAD_FAST | 1,996,598 | 0.5% | 54.1% |
| CALL RETURN_VALUE | 1,905,601 | 0.5% | 54.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,889,799 | 0.5% | 55.1% |
| CALL POP_TOP | 1,876,003 | 0.5% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,750,633 | 0.4% | 56.0% |
| LOAD_FAST CALL_FUNCTION_EX | 1,746,618 | 0.4% | 56.4% |
| BINARY_OP COPY | 1,725,530 | 0.4% | 56.8% |
| COPY TO_BOOL_INT | 1,725,210 | 0.4% | 57.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,698,317 | 0.4% | 57.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,689,747 | 0.4% | 58.1% |
| ENTER_EXECUTOR CALL | 1,676,394 | 0.4% | 58.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,606,389 | 0.4% | 58.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,565,574 | 0.4% | 59.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,543,033 | 0.4% | 59.7% |
| POP_TOP RETURN_CONST | 1,537,307 | 0.4% | 60.1% |
| POP_TOP LOAD_CONST | 1,509,167 | 0.4% | 60.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,495,330 | 0.4% | 60.8% |
| RETURN_VALUE STORE_FAST | 1,423,402 | 0.4% | 61.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,413,624 | 0.4% | 61.5% |
| LOAD_CONST LOAD_FAST | 1,402,193 | 0.3% | 61.9% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,374,928 | 0.3% | 62.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,374,826 | 0.3% | 62.6% |
| LOAD_FAST TO_BOOL | 1,352,271 | 0.3% | 62.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,330,573 | 0.3% | 63.2% |
| ENTER_EXECUTOR FOR_ITER_LIST | 1,312,218 | 0.3% | 63.6% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,297,910 | 0.3% | 63.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,284,976 | 0.3% | 64.2% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,282,127 | 0.3% | 64.5% |
| BEFORE_WITH POP_TOP | 1,276,928 | 0.3% | 64.8% |
| LOAD_FAST BUILD_TUPLE | 1,261,001 | 0.3% | 65.1% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,257,815 | 0.3% | 65.5% |
| LOAD_CONST COMPARE_OP_INT | 1,250,854 | 0.3% | 65.8% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,246,677 | 0.3% | 66.1% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,246,017 | 0.3% | 66.4% |
| LOAD_ATTR PUSH_NULL | 1,211,703 | 0.3% | 66.7% |
| CALL_FUNCTION_EX RETURN_VALUE | 1,196,038 | 0.3% | 67.0% |
| RETURN_VALUE RETURN_VALUE | 1,180,761 | 0.3% | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 1,179,852 | 0.3% | 67.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,149,969 | 0.3% | 67.9% |
| POP_TOP NOP | 1,143,031 | 0.3% | 68.1% |
| NOP LOAD_GLOBAL_MODULE | 1,119,969 | 0.3% | 68.4% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,119,872 | 0.3% | 68.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,116,358 | 0.3% | 69.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,096,707 | 0.3% | 69.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,087,121 | 0.3% | 69.5% |
| COPY_FREE_VARS RESUME_CHECK | 1,084,997 | 0.3% | 69.8% |
| LOAD_DEREF LOAD_FAST | 1,079,697 | 0.3% | 70.1% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,079,177 | 0.3% | 70.3% |
| LOAD_CONST COPY | 1,067,520 | 0.3% | 70.6% |
| COPY STORE_FAST_STORE_FAST | 1,061,440 | 0.3% | 70.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,060,157 | 0.3% | 71.1% |
| STORE_FAST_STORE_FAST STORE_FAST | 1,056,280 | 0.3% | 71.4% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,056,220 | 0.3% | 71.6% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 1,055,880 | 0.3% | 71.9% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,050,409 | 0.3% | 72.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 1,043,660 | 0.3% | 72.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 16,920 | 92.9% |
| LOAD_CONST | 980 | 5.4% |
| LOAD_FAST | 280 | 1.5% |
| BINARY_OP | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 17,300 | 95.0% |
| BUILD_TUPLE | 280 | 1.5% |
| LOAD_DEREF | 280 | 1.5% |
| STORE_FAST | 280 | 1.5% |
| CALL | 80 | 0.4% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,510,271 | 99.2% |
| COPY_FREE_VARS | 73,100 | 0.7% |
| POP_TOP | 6,500 | 0.1% |
| RESUME | 2,280 | 0.0% |
| MAKE_CELL | 20 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,179,852 | 74.4% |
| RETURN_VALUE | 303,256 | 19.1% |
| LOAD_GLOBAL_MODULE | 79,556 | 5.0% |
| LOAD_FAST | 16,320 | 1.0% |
| CALL | 6,040 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,276,928 | 80.5% |
| STORE_FAST | 308,596 | 19.5% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 26,480 | 99.8% |
| BINARY_OP | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,520 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 544,080 | 91.9% |
| LOAD_CONST | 46,851 | 7.9% |
| BINARY_SUBSCR | 840 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 543,920 | 91.9% |
| STORE_FAST | 46,571 | 7.9% |
| BINARY_SUBSCR | 840 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,751 | 83.3% |
| LOAD_ATTR_MODULE | 5,100 | 16.5% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,911 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,936 | 49.2% |
| CALL | 26,556 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,438 | 15.2% |
| LOAD_ATTR | 82 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,556 | 78.1% |
| RETURN_CONST | 10,236 | 13.6% |
| LOAD_FAST | 6,080 | 8.1% |
| LOAD_GLOBAL_MODULE | 140 | 0.2% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 10,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 5,440 | 50.0% |
| LOAD_FAST | 5,440 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 671,052 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 671,052 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,560 | 52.2% |
| CONVERT_VALUE | 24,320 | 47.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 38,720 | 76.1% |
| BUILD_STRING | 12,160 | 23.9% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 938,123 | 93.5% |
| CALL_BUILTIN_CLASS | 34,980 | 3.5% |
| CALL | 12,420 | 1.2% |
| STORE_FAST_LOAD_FAST | 6,080 | 0.6% |
| RETURN_VALUE | 5,440 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 619,032 | 61.7% |
| LOAD_FAST_AND_CLEAR | 315,711 | 31.5% |
| FOR_ITER_RANGE | 29,024 | 2.9% |
| FOR_ITER | 11,476 | 1.1% |
| FOR_ITER_TUPLE | 11,100 | 1.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,400,963 | 88.8% |
| RETURN_CONST | 640,644 | 6.1% |
| YIELD_VALUE | 545,100 | 5.1% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 500 | 89.3% |
| POP_TOP | 60 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 560 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 59,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 38,040 | 63.6% |
| STORE_FAST | 12,160 | 20.3% |
| LOAD_FAST | 6,080 | 10.2% |
| STORE_NAME | 2,480 | 4.1% |
| LOAD_CONST | 560 | 0.9% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,953,539 | 45.2% |
| POP_TOP | 1,143,031 | 17.5% |
| POP_JUMP_IF_FALSE | 1,017,567 | 15.6% |
| RESUME_CHECK | 896,501 | 13.7% |
| POP_JUMP_IF_NOT_NONE | 310,244 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,877,089 | 59.4% |
| LOAD_GLOBAL_MODULE | 1,119,969 | 17.2% |
| LOAD_FAST_LOAD_FAST | 550,360 | 8.4% |
| LOAD_CONST | 529,060 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 442,231 | 6.8% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 19,971 | 54.9% |
| COPY | 10,880 | 29.9% |
| POP_TOP | 5,200 | 14.3% |
| STORE_FAST | 280 | 0.8% |
| STORE_SUBSCR_DICT | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 19,571 | 53.8% |
| RERAISE | 10,880 | 29.9% |
| JUMP_FORWARD | 5,120 | 14.1% |
| JUMP_BACKWARD | 700 | 1.9% |
| RETURN_CONST | 60 | 0.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,528,880 | 34.1% |
| RETURN_CONST | 4,526,855 | 23.6% |
| CALL | 1,876,003 | 9.8% |
| BEFORE_WITH | 1,276,928 | 6.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,043,660 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,255,081 | 37.8% |
| LOAD_FAST | 5,046,355 | 26.3% |
| RETURN_CONST | 1,537,307 | 8.0% |
| LOAD_CONST | 1,509,167 | 7.9% |
| NOP | 1,143,031 | 6.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 25,371 | 69.8% |
| RERAISE | 5,440 | 15.0% |
| CALL_KW | 5,120 | 14.1% |
| BINARY_SUBSCR_DICT | 300 | 0.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,711 | 70.7% |
| WITH_EXCEPT_START | 5,440 | 15.0% |
| LOAD_GLOBAL_MODULE | 5,080 | 14.0% |
| LOAD_GLOBAL | 120 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,099,429 | 46.4% |
| LOAD_ATTR | 1,211,703 | 26.8% |
| LOAD_ATTR_MODULE | 1,119,872 | 24.8% |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,901,290 | 64.2% |
| LOAD_FAST_LOAD_FAST | 713,214 | 15.8% |
| CALL | 601,084 | 13.3% |
| LOAD_CONST | 237,533 | 5.3% |
| CALL_PY_EXACT_ARGS | 44,840 | 1.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 16,820 | 97.2% |
| COPY_FREE_VARS | 340 | 2.0% |
| CALL | 140 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,440 | 31.4% |
| LOAD_FAST | 5,440 | 31.4% |
| STORE_FAST | 5,440 | 31.4% |
| CALL_METHOD_DESCRIPTOR_O | 660 | 3.8% |
| CALL | 320 | 1.8% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,706,656 | 51.8% |
| CALL | 1,905,601 | 11.3% |
| CALL_FUNCTION_EX | 1,196,038 | 7.1% |
| RETURN_VALUE | 1,180,761 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 996,742 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,400,963 | 56.0% |
| STORE_FAST | 1,423,402 | 8.5% |
| RETURN_VALUE | 1,180,761 | 7.0% |
| POP_TOP | 915,016 | 5.4% |
| LOAD_FAST_LOAD_FAST | 703,441 | 4.2% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 12,160 | 42.0% |
| LOAD_FAST | 10,439 | 36.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,480 | 18.9% |
| STORE_SUBSCR | 620 | 2.1% |
| LOAD_ATTR | 200 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 17,720 | 61.1% |
| LOAD_GLOBAL_MODULE | 10,200 | 35.2% |
| STORE_SUBSCR | 620 | 2.1% |
| STORE_SUBSCR_DICT | 259 | 0.9% |
| LOAD_GLOBAL | 80 | 0.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,352,271 | 95.9% |
| LOAD_ATTR_INSTANCE_VALUE | 49,976 | 3.5% |
| TO_BOOL | 3,442 | 0.2% |
| LOAD_ATTR | 886 | 0.1% |
| RETURN_VALUE | 765 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 715,390 | 50.7% |
| POP_JUMP_IF_FALSE | 688,183 | 48.8% |
| TO_BOOL | 3,442 | 0.2% |
| TO_BOOL_BOOL | 2,165 | 0.2% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 703,441 | 68.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 318,568 | 31.2% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,022,089 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 159,225 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 159,265 | 100.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 5,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 5,360 | 98.5% |
| TO_BOOL | 80 | 1.5% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,269,487 | 53.1% |
| UNARY_INVERT | 1,022,089 | 23.9% |
| POP_JUMP_IF_FALSE | 703,441 | 16.5% |
| LOAD_ATTR | 171,504 | 4.0% |
| LOAD_FAST_LOAD_FAST | 49,920 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,725,530 | 40.4% |
| STORE_FAST | 875,265 | 20.5% |
| TO_BOOL_INT | 703,501 | 16.5% |
| UNARY_INVERT | 703,441 | 16.5% |
| BUILD_TUPLE | 159,324 | 3.7% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 140 | 50.0% |
| STORE_FAST | 140 | 50.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 315,711 | 33.4% |
| JUMP_FORWARD | 303,016 | 32.1% |
| LOAD_FAST | 159,669 | 16.9% |
| POP_TOP | 143,367 | 15.2% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 319,616 | 33.8% |
| SWAP | 315,711 | 33.4% |
| STORE_FAST | 303,836 | 32.2% |
| RETURN_VALUE | 5,120 | 0.5% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 528,600 | 58.2% |
| RESUME_CHECK | 313,216 | 34.5% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 3.6% |
| POP_JUMP_IF_NOT_NONE | 16,320 | 1.8% |
| POP_TOP | 6,080 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 886,176 | 97.5% |
| STORE_FAST | 16,320 | 1.8% |
| BUILD_TUPLE | 6,100 | 0.7% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 26,560 | 68.6% |
| FORMAT_SIMPLE | 12,160 | 31.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 26,480 | 68.4% |
| RETURN_VALUE | 12,160 | 31.4% |
| BINARY_OP | 80 | 0.2% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,261,001 | 49.7% |
| LOAD_FAST_LOAD_FAST | 556,800 | 21.9% |
| RETURN_VALUE | 512,000 | 20.2% |
| BINARY_OP | 159,324 | 6.3% |
| LOAD_ATTR_INSTANCE_VALUE | 21,600 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 704,361 | 27.7% |
| YIELD_VALUE | 550,140 | 21.7% |
| STORE_FAST | 512,000 | 20.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 20.2% |
| CALL_LIST_APPEND | 159,244 | 6.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,270,422 | 26.1% |
| ENTER_EXECUTOR | 1,676,394 | 19.2% |
| LOAD_ATTR_METHOD_NO_DICT | 1,330,573 | 15.3% |
| LOAD_FAST_LOAD_FAST | 829,537 | 9.5% |
| BUILD_TUPLE | 704,361 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,040,154 | 23.4% |
| RETURN_VALUE | 1,905,601 | 21.9% |
| POP_TOP | 1,876,003 | 21.5% |
| LOAD_FAST | 756,885 | 8.7% |
| TO_BOOL_BOOL | 683,343 | 7.8% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,746,618 | 75.7% |
| DICT_MERGE | 561,380 | 24.3% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,196,038 | 51.8% |
| RESUME_CHECK | 533,760 | 23.1% |
| CALL_BUILTIN_CLASS | 511,960 | 22.2% |
| POP_TOP | 60,480 | 2.6% |
| STORE_FAST | 5,440 | 0.2% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 140 | 87.5% |
| CALL_FUNCTION_EX | 20 | 12.5% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 243,312 | 97.9% |
| ENTER_EXECUTOR | 5,121 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 185,207 | 74.6% |
| LOAD_FAST | 27,200 | 10.9% |
| RETURN_VALUE | 18,240 | 7.3% |
| STORE_FAST | 12,300 | 5.0% |
| PUSH_EXC_INFO | 5,120 | 2.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 354,815 | 98.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,981 | 0.6% |
| COMPARE_OP | 1,264 | 0.4% |
| LOAD_GLOBAL_MODULE | 377 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 356,752 | 99.1% |
| COMPARE_OP | 1,264 | 0.4% |
| COMPARE_OP_INT | 1,198 | 0.3% |
| COMPARE_OP_STR | 437 | 0.1% |
| POP_JUMP_IF_TRUE | 279 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,246,017 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,246,677 | 100.0% |
| POP_JUMP_IF_TRUE | 480 | 0.0% |
| STORE_FAST | 140 | 0.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 12,120 | 49.8% |
| CALL_BUILTIN_FAST | 12,120 | 49.8% |
| BINARY_SUBSCR | 40 | 0.2% |
| CALL | 40 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 24,320 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,597,440 | 43.3% |
| BINARY_OP | 1,725,530 | 28.8% |
| LOAD_CONST | 1,067,520 | 17.8% |
| LOAD_FAST | 554,856 | 9.2% |
| STORE_ATTR_INSTANCE_VALUE | 18,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,597,760 | 43.3% |
| TO_BOOL_INT | 1,725,210 | 28.8% |
| STORE_FAST_STORE_FAST | 1,061,440 | 17.7% |
| LOAD_ATTR_INSTANCE_VALUE | 542,557 | 9.0% |
| LOAD_FAST | 24,320 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 703,441 | 64.8% |
| CALL_ALLOC_AND_ENTER_INIT | 302,976 | 27.9% |
| CACHE | 73,100 | 6.7% |
| CALL | 5,620 | 0.5% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,084,997 | 99.9% |
| RETURN_GENERATOR | 340 | 0.0% |
| RESUME | 320 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,588 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,392 | 66.7% |
| RETURN_CONST | 26,556 | 32.5% |
| LOAD_GLOBAL_MODULE | 600 | 0.7% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 528,740 | 94.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 5.8% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 561,380 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,255,081 | 72.5% |
| POP_JUMP_IF_NOT_NONE | 798,134 | 8.0% |
| STORE_FAST_STORE_FAST | 548,100 | 5.5% |
| FOR_ITER_LIST | 543,320 | 5.4% |
| LIST_APPEND | 522,714 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,971,280 | 59.7% |
| CALL | 1,676,394 | 16.7% |
| FOR_ITER_LIST | 1,312,218 | 13.1% |
| CALL_PY_WITH_DEFAULTS | 436,951 | 4.4% |
| LOAD_ATTR_PROPERTY | 413,708 | 4.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 12,240 | 36.6% |
| GET_ITER | 11,476 | 34.3% |
| LOAD_FAST | 5,740 | 17.1% |
| JUMP_BACKWARD | 3,104 | 9.3% |
| FOR_ITER | 920 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 18,840 | 56.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,360 | 33.9% |
| FOR_ITER | 920 | 2.7% |
| STORE_FAST | 760 | 2.3% |
| LOAD_GLOBAL_MODULE | 560 | 1.7% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 29,560 | 98.9% |
| STORE_NAME | 340 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,120 | 97.4% |
| STORE_NAME | 780 | 2.6% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 30,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 29,560 | 97.8% |
| STORE_NAME | 680 | 2.2% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 26,560 | 60.1% |
| LOAD_FAST | 16,460 | 37.3% |
| LOAD_GLOBAL_MODULE | 1,121 | 2.5% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,041 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,440,000 | 90.7% |
| POP_TOP | 550,416 | 9.2% |
| LIST_APPEND | 1,700 | 0.0% |
| POP_JUMP_IF_NOT_NONE | 1,340 | 0.0% |
| STORE_FAST_STORE_FAST | 1,340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 5,983,920 | 99.7% |
| FOR_ITER_LIST | 4,951 | 0.1% |
| FOR_ITER | 3,104 | 0.1% |
| FOR_ITER_RANGE | 2,155 | 0.0% |
| LOAD_FAST | 1,651 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 653,848 | 52.0% |
| POP_TOP | 586,770 | 46.7% |
| STORE_ATTR_INSTANCE_VALUE | 6,060 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 5,400 | 0.4% |
| POP_EXCEPT | 5,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 894,635 | 71.1% |
| BUILD_LIST | 303,016 | 24.1% |
| LOAD_GLOBAL_MODULE | 22,576 | 1.8% |
| POP_EXCEPT | 19,971 | 1.6% |
| LOAD_FAST_LOAD_FAST | 6,360 | 0.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 266,930 | 50.9% |
| LOAD_ATTR | 159,344 | 30.4% |
| BINARY_SUBSCR_STR_INT | 97,240 | 18.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 860 | 0.2% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 522,714 | 99.7% |
| JUMP_BACKWARD | 1,700 | 0.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 144,147 | 50.1% |
| RETURN_VALUE | 143,367 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,687 | 50.0% |
| STORE_FAST | 143,367 | 49.8% |
| RETURN_VALUE | 320 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.1% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,830,209 | 73.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,543,033 | 23.4% |
| LOAD_GLOBAL_MODULE | 121,561 | 1.8% |
| CALL | 49,620 | 0.8% |
| LOAD_ATTR | 20,762 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,996,598 | 30.2% |
| PUSH_NULL | 1,211,703 | 18.4% |
| STORE_SUBSCR_DICT | 703,361 | 10.7% |
| POP_JUMP_IF_NOT_NONE | 662,417 | 10.0% |
| STORE_FAST | 476,810 | 7.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,240,923 | 26.6% |
| LOAD_FAST | 2,558,825 | 21.0% |
| POP_TOP | 1,509,167 | 12.4% |
| POP_JUMP_IF_FALSE | 785,353 | 6.4% |
| LOAD_ATTR_METHOD_NO_DICT | 684,072 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,240,923 | 26.6% |
| CALL | 2,270,422 | 18.6% |
| LOAD_FAST | 1,402,193 | 11.5% |
| COMPARE_OP_INT | 1,250,854 | 10.3% |
| COPY | 1,067,520 | 8.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,079,177 | 95.2% |
| POP_JUMP_IF_NOT_NONE | 26,560 | 2.3% |
| STORE_DEREF | 26,560 | 2.3% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,079,697 | 95.2% |
| POP_JUMP_IF_NOT_NONE | 53,120 | 4.7% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,497,810 | 23.3% |
| STORE_FAST | 8,462,835 | 12.0% |
| POP_JUMP_IF_FALSE | 5,495,895 | 7.8% |
| POP_TOP | 5,046,355 | 7.1% |
| NOP | 3,877,089 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,513,189 | 24.8% |
| RETURN_VALUE | 8,706,656 | 12.3% |
| LOAD_ATTR | 4,830,209 | 6.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,720,671 | 6.7% |
| CALL_PY_EXACT_ARGS | 3,047,908 | 4.3% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 315,711 | 66.5% |
| LOAD_FAST_AND_CLEAR | 159,324 | 33.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 315,711 | 66.5% |
| LOAD_FAST_AND_CLEAR | 159,324 | 33.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 544,560 | 77.3% |
| POP_JUMP_IF_NONE | 143,692 | 20.4% |
| LOAD_ATTR_CLASS | 15,858 | 2.3% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 543,920 | 77.2% |
| LOAD_GLOBAL_MODULE | 143,612 | 20.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 15,818 | 2.2% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,606,389 | 18.7% |
| POP_JUMP_IF_FALSE | 908,131 | 10.6% |
| LOAD_FAST_LOAD_FAST | 770,341 | 9.0% |
| POP_JUMP_IF_TRUE | 716,264 | 8.4% |
| LOAD_SUPER_ATTR_METHOD | 715,801 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,121,006 | 24.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,050,409 | 12.3% |
| CALL | 829,537 | 9.7% |
| LOAD_FAST_LOAD_FAST | 770,341 | 9.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 703,361 | 8.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.2% |
| RESUME_CHECK | 1,720 | 9.6% |
| POP_JUMP_IF_FALSE | 1,712 | 9.6% |
| LOAD_FAST | 1,600 | 9.0% |
| RESUME | 1,520 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,818 | 38.2% |
| LOAD_ATTR | 3,325 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 2,744 | 15.4% |
| LOAD_FAST | 2,166 | 12.1% |
| CALL | 740 | 4.1% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 820 | 37.3% |
| LOAD_CONST | 600 | 27.3% |
| RESUME | 560 | 25.5% |
| PUSH_NULL | 120 | 5.5% |
| POP_TOP | 80 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 640 | 29.1% |
| CALL | 500 | 22.7% |
| LOAD_ATTR | 420 | 19.1% |
| LOAD_CONST | 380 | 17.3% |
| PUSH_NULL | 220 | 10.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 200 | 38.5% |
| PUSH_NULL | 80 | 15.4% |
| LOAD_FAST_LOAD_FAST | 80 | 15.4% |
| LOAD_SUPER_ATTR_ATTR | 80 | 15.4% |
| CALL | 40 | 7.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 106,240 | 79.8% |
| CALL_PY_EXACT_ARGS | 26,840 | 20.2% |
| CACHE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 106,240 | 79.8% |
| RESUME_CHECK | 26,860 | 20.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,329,805 | 25.0% |
| TO_BOOL_INT | 3,132,452 | 23.5% |
| COMPARE_OP_INT | 2,672,149 | 20.0% |
| COMPARE_OP_STR | 1,282,127 | 9.6% |
| CONTAINS_OP | 1,246,677 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,495,895 | 41.2% |
| RETURN_CONST | 2,355,624 | 17.7% |
| NOP | 1,017,567 | 7.6% |
| LOAD_GLOBAL_MODULE | 934,182 | 7.0% |
| LOAD_FAST_LOAD_FAST | 908,131 | 6.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 722,983 | 91.2% |
| LOAD_ATTR_INSTANCE_VALUE | 44,600 | 5.6% |
| LOAD_ATTR | 24,460 | 3.1% |
| RETURN_VALUE | 760 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229,738 | 29.0% |
| LOAD_GLOBAL_MODULE | 193,653 | 24.4% |
| NOP | 180,327 | 22.7% |
| LOAD_FAST_CHECK | 143,692 | 18.1% |
| RETURN_CONST | 22,420 | 2.8% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,163,189 | 57.6% |
| LOAD_ATTR | 662,417 | 17.6% |
| LOAD_ATTR_INSTANCE_VALUE | 589,859 | 15.7% |
| RETURN_VALUE | 267,250 | 7.1% |
| LOAD_DEREF | 53,120 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,698,317 | 45.2% |
| ENTER_EXECUTOR | 798,134 | 21.2% |
| RETURN_CONST | 663,089 | 17.6% |
| NOP | 310,244 | 8.3% |
| LOAD_CONST | 143,647 | 3.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,495,330 | 66.7% |
| TO_BOOL | 715,390 | 31.9% |
| TO_BOOL_NONE | 17,460 | 0.8% |
| COMPARE_OP_STR | 10,525 | 0.5% |
| COMPARE_OP_INT | 1,964 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 909,834 | 40.6% |
| LOAD_FAST_LOAD_FAST | 716,264 | 31.9% |
| RETURN_CONST | 462,841 | 20.6% |
| LOAD_GLOBAL_MODULE | 57,862 | 2.6% |
| RETURN_VALUE | 46,531 | 2.1% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,440 | 99.6% |
| CALL_KW | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 5,440 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 10,880 | 66.7% |
| POP_JUMP_IF_TRUE | 5,440 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 5,440 | 50.0% |
| COPY | 5,440 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,355,624 | 35.9% |
| POP_TOP | 1,537,307 | 23.4% |
| STORE_ATTR_INSTANCE_VALUE | 1,413,624 | 21.5% |
| POP_JUMP_IF_NOT_NONE | 663,089 | 10.1% |
| POP_JUMP_IF_TRUE | 462,841 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,526,855 | 69.0% |
| EXIT_INIT_CHECK | 671,052 | 10.2% |
| TO_BOOL_BOOL | 641,391 | 9.8% |
| INTERPRETER_EXIT | 640,644 | 9.8% |
| STORE_FAST | 47,731 | 0.7% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 38,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,960 | 97.2% |
| STORE_NAME | 780 | 2.1% |
| LOAD_GLOBAL_MODULE | 280 | 0.7% |
| LOAD_FAST | 20 | 0.1% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,322 | 59.1% |
| LOAD_FAST_LOAD_FAST | 19,800 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 16,320 | 17.1% |
| STORE_ATTR | 2,360 | 2.5% |
| LOAD_ATTR | 240 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 42,920 | 45.1% |
| LOAD_FAST | 12,980 | 13.6% |
| LOAD_FAST_LOAD_FAST | 12,840 | 13.5% |
| LOAD_CONST | 12,002 | 12.6% |
| LOAD_GLOBAL_BUILTIN | 5,360 | 5.6% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 53,120 | 40.0% |
| LOAD_GLOBAL_MODULE | 53,120 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 26,560 | 20.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 53,040 | 39.9% |
| LOAD_DEREF | 26,560 | 20.0% |
| LOAD_FAST | 26,560 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 26,520 | 20.0% |
| LOAD_GLOBAL | 120 | 0.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,983,920 | 27.3% |
| COPY | 2,597,760 | 11.9% |
| CALL | 2,040,154 | 9.3% |
| RETURN_VALUE | 1,423,402 | 6.5% |
| STORE_FAST_STORE_FAST | 1,056,280 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,462,835 | 38.7% |
| JUMP_BACKWARD | 5,440,000 | 24.9% |
| NOP | 2,953,539 | 13.5% |
| COPY | 2,597,440 | 11.9% |
| JUMP_FORWARD | 653,848 | 3.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 18,840 | 48.9% |
| COPY | 12,160 | 31.5% |
| FOR_ITER_LIST | 6,700 | 17.4% |
| FOR_ITER_TUPLE | 860 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,720 | 33.0% |
| STORE_ATTR_INSTANCE_VALUE | 12,080 | 31.3% |
| YIELD_VALUE | 6,680 | 17.3% |
| GET_ITER | 6,080 | 15.8% |
| TO_BOOL_STR | 860 | 2.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,149,969 | 30.4% |
| COPY | 1,061,440 | 28.1% |
| UNPACK_SEQUENCE_TUPLE | 1,056,220 | 27.9% |
| STORE_FAST_STORE_FAST | 512,000 | 13.5% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,374,928 | 36.4% |
| STORE_FAST | 1,056,280 | 27.9% |
| ENTER_EXECUTOR | 548,100 | 14.5% |
| STORE_FAST_STORE_FAST | 512,000 | 13.5% |
| LOAD_FAST_LOAD_FAST | 274,401 | 7.3% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 2,480 | 33.2% |
| CALL | 1,200 | 16.0% |
| IMPORT_FROM | 780 | 10.4% |
| SET_FUNCTION_ATTRIBUTE | 780 | 10.4% |
| IMPORT_NAME | 680 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,640 | 62.0% |
| LOAD_NAME | 820 | 11.0% |
| RETURN_CONST | 700 | 9.4% |
| LOAD_BUILD_CLASS | 500 | 6.7% |
| POP_TOP | 440 | 5.9% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 542,616 | 29.8% |
| BUILD_LIST | 315,711 | 17.3% |
| LOAD_FAST_AND_CLEAR | 315,711 | 17.3% |
| FOR_ITER_LIST | 302,691 | 16.6% |
| LOAD_FAST | 170,532 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 542,557 | 29.8% |
| LOAD_CONST | 329,856 | 18.1% |
| BUILD_LIST | 315,711 | 17.3% |
| STORE_FAST | 315,711 | 17.3% |
| FOR_ITER_LIST | 302,611 | 16.6% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 260 | 28.3% |
| FOR_ITER | 240 | 26.1% |
| LOAD_FAST | 120 | 13.0% |
| RETURN_VALUE | 80 | 8.7% |
| LOAD_FAST_CHECK | 80 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 360 | 39.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 340 | 37.0% |
| UNPACK_SEQUENCE_TUPLE | 100 | 10.9% |
| LOAD_FAST | 40 | 4.3% |
| STORE_FAST | 40 | 4.3% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,971,280 | 91.5% |
| BUILD_TUPLE | 550,140 | 8.4% |
| STORE_FAST_LOAD_FAST | 6,680 | 0.1% |
| CALL_STR_1 | 620 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,983,920 | 91.7% |
| INTERPRETER_EXIT | 545,100 | 8.3% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,820 | 47.2% |
| CACHE | 2,280 | 38.1% |
| COPY_FREE_VARS | 320 | 5.4% |
| CALL_KW | 200 | 3.3% |
| POP_TOP | 140 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,880 | 48.2% |
| LOAD_GLOBAL | 1,520 | 25.4% |
| LOAD_NAME | 560 | 9.4% |
| NOP | 280 | 4.7% |
| LOAD_CONST | 240 | 4.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,569 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,609 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,060,157 | 98.4% |
| LOAD_FAST_LOAD_FAST | 16,880 | 1.6% |
| BINARY_OP | 159 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 542,616 | 50.4% |
| STORE_FAST | 511,980 | 47.5% |
| BINARY_SLICE | 16,920 | 1.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,360 | 0.5% |
| LOAD_CONST | 280 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 600 | 28.0% |
| LOAD_FAST_LOAD_FAST | 600 | 28.0% |
| CALL_METHOD_DESCRIPTOR_O | 600 | 28.0% |
| BINARY_SUBSCR_LIST_INT | 280 | 13.1% |
| BINARY_OP | 40 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,100 | 51.4% |
| LOAD_CONST | 620 | 29.0% |
| STORE_FAST | 300 | 14.0% |
| CALL | 120 | 5.6% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 97,200 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 97,200 | 100.0% |
| CALL | 40 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 143,612 | 99.9% |
| BINARY_OP | 80 | 0.1% |
| LOAD_FAST | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 143,772 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 162,874 | 75.8% |
| LOAD_CONST | 46,451 | 21.6% |
| CALL_LEN | 5,360 | 2.5% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 209,485 | 97.5% |
| CALL_BUILTIN_CLASS | 5,360 | 2.5% |
| CALL | 40 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 96,020 | 88.0% |
| LOAD_CONST | 12,360 | 11.3% |
| LOAD_FAST | 700 | 0.6% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 96,020 | 88.0% |
| CONVERT_VALUE | 12,120 | 11.1% |
| STORE_FAST | 400 | 0.4% |
| PUSH_EXC_INFO | 300 | 0.3% |
| LOAD_FAST | 140 | 0.1% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,000 | 63.1% |
| LOAD_FAST_LOAD_FAST | 6,320 | 36.2% |
| BINARY_SUBSCR | 120 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,800 | 61.9% |
| STORE_FAST | 6,360 | 36.5% |
| BINARY_OP_ADD_UNICODE | 280 | 1.6% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 97,200 | 100.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 97,240 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 35,280 | 99.9% |
| BINARY_SUBSCR | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 29,500 | 83.5% |
| JUMP_FORWARD | 5,400 | 15.3% |
| STORE_FAST | 420 | 1.2% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 329,456 | 49.1% |
| LOAD_FAST | 309,036 | 46.1% |
| CALL | 32,140 | 4.8% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |
| ENTER_EXECUTOR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 368,076 | 54.9% |
| COPY_FREE_VARS | 302,976 | 45.1% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,240 | 71.9% |
| LOAD_CONST | 6,360 | 14.2% |
| BINARY_OP_ADD_INT | 5,360 | 12.0% |
| PUSH_NULL | 623 | 1.4% |
| CALL | 157 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 38,780 | 86.5% |
| POP_TOP | 5,960 | 13.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 511,960 | 43.9% |
| RETURN_VALUE | 436,411 | 37.4% |
| LOAD_FAST | 176,069 | 15.1% |
| LOAD_CONST | 12,360 | 1.1% |
| LOAD_GLOBAL_BUILTIN | 10,260 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 671,589 | 57.6% |
| STORE_FAST | 436,711 | 37.5% |
| GET_ITER | 34,980 | 3.0% |
| LOAD_FAST | 16,320 | 1.4% |
| CALL_BUILTIN_CLASS | 6,000 | 0.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 532,252 | 51.6% |
| LOAD_CONST | 294,527 | 28.6% |
| LOAD_FAST_LOAD_FAST | 107,074 | 10.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,197 | 4.7% |
| LOAD_GLOBAL_MODULE | 24,040 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 360,938 | 35.0% |
| TO_BOOL_BOOL | 286,707 | 27.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 268,281 | 26.0% |
| UNPACK_SEQUENCE_TUPLE | 48,197 | 4.7% |
| POP_TOP | 12,747 | 1.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 515,460 | 47.1% |
| BUILD_TUPLE | 511,960 | 46.8% |
| CALL | 32,599 | 3.0% |
| LOAD_FAST_CHECK | 15,818 | 1.4% |
| LOAD_ATTR | 12,080 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,043,660 | 95.4% |
| RETURN_VALUE | 49,097 | 4.5% |
| LOAD_FAST | 620 | 0.1% |
| STORE_FAST | 440 | 0.0% |
| BEFORE_WITH | 140 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 97,200 | 71.4% |
| LOAD_ATTR | 26,480 | 19.4% |
| LOAD_FAST | 12,360 | 9.1% |
| CALL | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 97,200 | 71.4% |
| LOAD_FAST | 38,640 | 28.4% |
| STORE_FAST | 140 | 0.1% |
| TO_BOOL_INT | 140 | 0.1% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 719,941 | 99.9% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 720,221 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 230,457 | 89.4% |
| LOAD_ATTR_INSTANCE_VALUE | 26,940 | 10.5% |
| CALL | 384 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 207,754 | 80.6% |
| CALL_PY_EXACT_ARGS | 31,880 | 12.4% |
| CALL_BUILTIN_CLASS | 6,000 | 2.3% |
| LOAD_FAST | 5,400 | 2.1% |
| BINARY_OP_SUBTRACT_INT | 5,360 | 2.1% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 159,244 | 93.4% |
| LOAD_FAST | 10,800 | 6.3% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 158,644 | 93.0% |
| LOAD_GLOBAL_MODULE | 10,800 | 6.3% |
| JUMP_BACKWARD | 640 | 0.4% |
| NOP | 280 | 0.2% |
| RETURN_CONST | 140 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,006,437 | 99.7% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.1% |
| LOAD_CONST | 600 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 483 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 703,721 | 69.7% |
| STORE_FAST | 303,758 | 30.1% |
| LIST_APPEND | 860 | 0.1% |
| TO_BOOL_NONE | 600 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 31,560 | 85.1% |
| BUILD_TUPLE | 5,360 | 14.4% |
| CALL | 180 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 26,260 | 70.8% |
| LOAD_FAST | 10,840 | 29.2% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,096,707 | 94.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 64,015 | 5.5% |
| LOAD_ATTR | 1,200 | 0.1% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 543,960 | 46.8% |
| POP_TOP | 429,758 | 37.0% |
| LOAD_FAST | 50,180 | 4.3% |
| RETURN_VALUE | 48,676 | 4.2% |
| CALL_BUILTIN_FAST | 48,197 | 4.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 760,209 | 91.4% |
| LOAD_CONST | 30,200 | 3.6% |
| CALL | 27,539 | 3.3% |
| RETURN_VALUE | 12,080 | 1.5% |
| STORE_FAST | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 787,888 | 94.7% |
| LOAD_CONST | 29,920 | 3.6% |
| RETURN_VALUE | 12,980 | 1.6% |
| BINARY_OP_ADD_UNICODE | 600 | 0.1% |
| STORE_FAST | 280 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,716,260 | 46.9% |
| LOAD_FAST | 3,047,908 | 38.5% |
| LOAD_FAST_LOAD_FAST | 562,280 | 7.1% |
| LOAD_SUPER_ATTR_METHOD | 302,936 | 3.8% |
| LOAD_GLOBAL_MODULE | 90,380 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,874,639 | 99.4% |
| MAKE_CELL | 26,840 | 0.3% |
| RETURN_GENERATOR | 16,820 | 0.2% |
| COPY_FREE_VARS | 320 | 0.0% |
| PUSH_EXC_INFO | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 923,598 | 46.1% |
| ENTER_EXECUTOR | 436,951 | 21.8% |
| LOAD_ATTR_MODULE | 303,136 | 15.1% |
| LOAD_FAST | 208,364 | 10.4% |
| LOAD_CONST | 73,661 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,297,910 | 64.9% |
| COPY_FREE_VARS | 703,441 | 35.1% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,220 | 99.6% |
| CALL | 40 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,220 | 90.8% |
| YIELD_VALUE | 620 | 5.5% |
| STORE_FAST | 280 | 2.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 140 | 1.2% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 549,420 | 99.9% |
| LOAD_FAST | 600 | 0.1% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 549,400 | 99.9% |
| LOAD_FAST | 620 | 0.1% |
| CALL | 140 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 75.0% |
| LOAD_GLOBAL_MODULE | 140 | 17.5% |
| CALL | 60 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 620 | 77.5% |
| PUSH_NULL | 140 | 17.5% |
| LOAD_GLOBAL | 40 | 5.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 140 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,250,854 | 46.8% |
| LOAD_ATTR_INSTANCE_VALUE | 841,051 | 31.4% |
| LOAD_FAST | 544,980 | 20.4% |
| LOAD_FAST_LOAD_FAST | 16,880 | 0.6% |
| CALL_BUILTIN_FAST | 12,080 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,672,149 | 99.9% |
| POP_JUMP_IF_TRUE | 1,964 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 114 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,257,815 | 95.5% |
| LOAD_CONST | 53,140 | 4.0% |
| LOAD_FAST | 5,500 | 0.4% |
| COMPARE_OP | 437 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,282,127 | 97.4% |
| COPY | 12,120 | 0.9% |
| LOAD_FAST | 12,120 | 0.9% |
| POP_JUMP_IF_TRUE | 10,525 | 0.8% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,983,920 | 99.8% |
| GET_ITER | 10,800 | 0.2% |
| FOR_ITER | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,983,920 | 99.8% |
| POP_TOP | 10,800 | 0.2% |
| RESUME | 80 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,312,218 | 58.6% |
| GET_ITER | 619,032 | 27.6% |
| SWAP | 302,611 | 13.5% |
| JUMP_BACKWARD | 4,951 | 0.2% |
| FOR_ITER | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 606,032 | 27.1% |
| ENTER_EXECUTOR | 543,320 | 24.3% |
| STORE_FAST | 454,281 | 20.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 318,628 | 14.2% |
| SWAP | 302,691 | 13.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 153,207 | 83.0% |
| GET_ITER | 29,024 | 15.7% |
| JUMP_BACKWARD | 2,155 | 1.2% |
| FOR_ITER | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,527 | 77.8% |
| STORE_FAST | 30,499 | 16.5% |
| RETURN_CONST | 10,560 | 5.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,140 | 47.9% |
| GET_ITER | 11,100 | 43.8% |
| SWAP | 860 | 3.4% |
| LOAD_FAST | 620 | 2.4% |
| JUMP_BACKWARD | 600 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,860 | 46.8% |
| LOAD_FAST | 10,460 | 41.2% |
| RETURN_CONST | 1,280 | 5.0% |
| STORE_FAST_LOAD_FAST | 860 | 3.4% |
| SWAP | 860 | 3.4% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 48,157 | 82.4% |
| LOAD_ATTR_MODULE | 10,200 | 17.5% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,579 | 72.9% |
| LOAD_FAST_CHECK | 15,858 | 27.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,513,189 | 91.5% |
| LOAD_FAST_LOAD_FAST | 1,050,409 | 5.5% |
| COPY | 542,557 | 2.8% |
| LOAD_ATTR_INSTANCE_VALUE | 21,264 | 0.1% |
| RETURN_VALUE | 12,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,494,478 | 23.5% |
| LOAD_FAST | 2,906,476 | 15.2% |
| LOAD_ATTR | 1,543,033 | 8.1% |
| LOAD_GLOBAL_MODULE | 1,284,976 | 6.7% |
| CONTAINS_OP | 1,246,017 | 6.5% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,348 | 99.9% |
| LOAD_ATTR | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,514 | 39.8% |
| CALL | 81,999 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,015 | 26.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,494,478 | 88.3% |
| LOAD_FAST | 469,609 | 9.2% |
| LOAD_ATTR | 51,038 | 1.0% |
| LOAD_ATTR_SLOT | 49,520 | 1.0% |
| LOAD_CONST | 12,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,750,633 | 34.4% |
| CALL | 1,330,573 | 26.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,096,707 | 21.5% |
| LOAD_CONST | 684,072 | 13.4% |
| LOAD_FAST_LOAD_FAST | 200,520 | 3.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,720,671 | 66.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,087,121 | 15.3% |
| LOAD_FAST_LOAD_FAST | 703,361 | 9.9% |
| BINARY_SUBSCR | 543,920 | 7.7% |
| LOAD_GLOBAL_MODULE | 27,260 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,716,260 | 52.3% |
| LOAD_FAST | 1,689,747 | 23.8% |
| CALL_PY_WITH_DEFAULTS | 923,598 | 13.0% |
| LOAD_FAST_LOAD_FAST | 610,720 | 8.6% |
| LOAD_CONST | 90,541 | 1.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,565,574 | 99.8% |
| LOAD_ATTR | 2,821 | 0.2% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,119,872 | 71.4% |
| CALL_PY_WITH_DEFAULTS | 303,136 | 19.3% |
| STORE_DEREF | 53,120 | 3.4% |
| LOAD_CONST | 31,040 | 2.0% |
| LOAD_FAST | 27,840 | 1.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 738,841 | 69.9% |
| LOAD_FAST_LOAD_FAST | 318,488 | 30.1% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 703,401 | 66.5% |
| UNARY_INVERT | 318,568 | 30.1% |
| RETURN_VALUE | 12,120 | 1.1% |
| LOAD_CONST | 12,120 | 1.1% |
| LOAD_FAST_LOAD_FAST | 5,400 | 0.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 413,708 | 63.8% |
| LOAD_FAST | 206,800 | 31.9% |
| RETURN_VALUE | 26,480 | 4.1% |
| LOAD_GLOBAL_MODULE | 600 | 0.1% |
| LOAD_ATTR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 635,748 | 98.1% |
| TO_BOOL_BOOL | 12,160 | 1.9% |
| LOAD_ATTR_PROPERTY | 220 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,200 | 97.8% |
| LOAD_ATTR_MODULE | 1,180 | 1.9% |
| RETURN_VALUE | 140 | 0.2% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 49,520 | 77.9% |
| CALL_BUILTIN_FAST | 12,220 | 19.2% |
| LOAD_FAST | 1,040 | 1.6% |
| LOAD_CONST | 600 | 0.9% |
| STORE_FAST | 140 | 0.2% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,400,818 | 48.9% |
| LOAD_FAST | 743,381 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.7% |
| STORE_FAST | 462,490 | 9.4% |
| NOP | 442,231 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,450,849 | 49.9% |
| LOAD_DEREF | 1,079,177 | 22.0% |
| CALL_ISINSTANCE | 719,941 | 14.7% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.7% |
| LOAD_GLOBAL_MODULE | 43,000 | 0.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,548,540 | 24.4% |
| RESUME_CHECK | 1,889,799 | 18.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,284,976 | 12.3% |
| NOP | 1,119,969 | 10.7% |
| POP_JUMP_IF_FALSE | 934,182 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,269,487 | 21.8% |
| LOAD_FAST_LOAD_FAST | 1,606,389 | 15.4% |
| LOAD_ATTR_MODULE | 1,565,574 | 15.0% |
| LOAD_FAST | 1,374,826 | 13.2% |
| COMPARE_OP_STR | 1,257,815 | 12.1% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,880 | 99.9% |
| LOAD_SUPER_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 54,960 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,024,017 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 715,801 | 69.9% |
| CALL_PY_EXACT_ARGS | 302,936 | 29.6% |
| LOAD_FAST | 5,440 | 0.5% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 10,510,271 | 36.4% |
| CALL_PY_EXACT_ARGS | 7,874,639 | 27.2% |
| FOR_ITER_GEN | 5,983,920 | 20.7% |
| CALL_PY_WITH_DEFAULTS | 1,297,910 | 4.5% |
| COPY_FREE_VARS | 1,084,997 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,497,810 | 57.1% |
| POP_TOP | 6,528,880 | 22.6% |
| LOAD_GLOBAL_BUILTIN | 2,400,818 | 8.3% |
| LOAD_GLOBAL_MODULE | 1,889,799 | 6.5% |
| NOP | 896,501 | 3.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,233,222 | 66.4% |
| LOAD_FAST_LOAD_FAST | 549,036 | 16.3% |
| SWAP | 542,557 | 16.1% |
| LOAD_ATTR_INSTANCE_VALUE | 16,080 | 0.5% |
| STORE_FAST_LOAD_FAST | 12,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,413,624 | 42.0% |
| LOAD_FAST | 881,036 | 26.2% |
| LOAD_GLOBAL_MODULE | 529,076 | 15.7% |
| LOAD_CONST | 289,418 | 8.6% |
| LOAD_FAST_LOAD_FAST | 121,160 | 3.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,520 | 80.1% |
| LOAD_FAST_LOAD_FAST | 12,220 | 19.8% |
| STORE_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,820 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 703,361 | 89.3% |
| LOAD_FAST | 40,527 | 5.1% |
| LOAD_ATTR_INSTANCE_VALUE | 32,760 | 4.2% |
| CALL | 10,200 | 1.3% |
| LOAD_CONST | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 705,227 | 89.5% |
| RETURN_CONST | 29,000 | 3.7% |
| LOAD_GLOBAL_MODULE | 26,760 | 3.4% |
| LOAD_CONST | 26,520 | 3.4% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,116,358 | 22.4% |
| CALL_ISINSTANCE | 720,221 | 14.4% |
| CALL | 683,343 | 13.7% |
| LOAD_FAST | 668,531 | 13.4% |
| RETURN_CONST | 641,391 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,329,805 | 66.8% |
| POP_JUMP_IF_TRUE | 1,495,330 | 30.0% |
| UNARY_NOT | 159,225 | 3.2% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,725,210 | 55.1% |
| BINARY_OP | 703,501 | 22.5% |
| LOAD_FAST | 703,361 | 22.5% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,132,452 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 313,796 | 88.8% |
| LOAD_ATTR_INSTANCE_VALUE | 39,240 | 11.1% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 353,096 | 100.0% |
| POP_JUMP_IF_TRUE | 160 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180,016 | 79.9% |
| LOAD_FAST | 26,940 | 12.0% |
| COPY | 11,960 | 5.3% |
| WITH_EXCEPT_START | 5,360 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 207,776 | 92.2% |
| POP_JUMP_IF_TRUE | 17,460 | 7.8% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 860 | 51.8% |
| LOAD_FAST | 620 | 37.3% |
| COPY | 160 | 9.6% |
| LOAD_GLOBAL_MODULE | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,460 | 88.0% |
| POP_JUMP_IF_TRUE | 200 | 12.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,055,880 | 95.6% |
| CALL_BUILTIN_FAST | 48,197 | 4.4% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,056,220 | 95.6% |
| STORE_FAST | 48,237 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_CHECK | 543,920 | 47.1% |
| FOR_ITER_LIST | 318,628 | 27.6% |
| CALL_BUILTIN_FAST | 268,281 | 23.2% |
| FOR_ITER | 11,360 | 1.0% |
| CALL | 7,200 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,149,969 | 99.5% |
| LOAD_FAST | 6,040 | 0.5% |
| STORE_DEREF | 20 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 60.3% |
| COPY | 144 | 31.0% |
| TO_BOOL | 40 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 300 | 64.7% |
| POP_JUMP_IF_FALSE | 164 | 35.3% |


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
|     deferred | 4,267,381 | 71.2% |
|          hit | 1,721,362 | 28.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 599 | 9.6% |
| Failure | 5,670 | 90.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 2,802 | 49.4% |
| or | 1,466 | 25.9% |
| remainder | 722 | 12.7% |
| add different types | 600 | 10.6% |
| add other | 80 | 1.4% |


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
|     deferred | 590,771 | 69.4% |
|          hit | 259,120 | 30.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 22.2% |
| Failure | 840 | 77.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 840 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,673,239 | 31.5% |
|          hit | 18,845,964 | 68.4% |
|         miss | 7,520 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,284 | 24.9% |
| Failure | 27,978 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,289 | 26.1% |
| cfunc noargs | 5,803 | 20.7% |
| class no vectorcall | 3,780 | 13.5% |
| meth descr varargs keywords | 3,060 | 10.9% |
| class mutable | 1,132 | 4.0% |
| other | 1,100 | 3.9% |
| bound method | 1,042 | 3.7% |
| cfunc varargs | 1,020 | 3.6% |
| meth descr method fastcall keywords | 860 | 3.1% |
| cfunc varargs keywords | 792 | 2.8% |
| operator wrapper | 720 | 2.6% |
| cmethod | 640 | 2.3% |
| wrong number arguments | 440 | 1.6% |
| method wrapper | 260 | 0.9% |
| meth descr varargs | 40 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 356,997 | 8.2% |
|          hit | 3,984,072 | 91.6% |
|         miss | 7,487 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,635 | 54.3% |
| Failure | 1,378 | 45.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 765 | 55.5% |
| big int | 340 | 24.7% |
| different types | 273 | 19.8% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 31,940 | 0.4% |
|          hit | 8,443,918 | 99.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 620 | 40.3% |
| Failure | 920 | 59.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| itertools | 260 | 28.3% |
| other | 220 | 23.9% |
| enumerate | 220 | 23.9% |
| callable | 220 | 23.9% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,560,153 | 15.8% |
|          hit | 34,669,764 | 83.4% |
|         miss | 309,450 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,419 | 54.8% |
| Failure | 18,516 | 45.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,316 | 23.3% |
| shadowed | 3,920 | 21.2% |
| not managed dict | 3,280 | 17.7% |
| non overriding descriptor | 1,984 | 10.7% |
| has managed dict | 1,060 | 5.7% |
| class attr descriptor | 940 | 5.1% |
| metaclass attribute | 900 | 4.9% |
| class method obj | 840 | 4.5% |
| non object slot | 520 | 2.8% |
| class attr simple | 436 | 2.4% |
| mutable class | 260 | 1.4% |
| overridden | 60 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,381 | 0.1% |
|        deopt | 100 | 0.0% |
|          hit | 15,335,421 | 99.9% |
|         miss | 2,265 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,571 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 1,079,177 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 100.0% |
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
|     deferred | 83,922 | 2.4% |
|          hit | 3,178,434 | 90.3% |
|         miss | 245,260 | 7.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,979 | 79.2% |
| Failure | 2,360 | 20.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 1,080 | 45.8% |
| not in keys | 520 | 22.0% |
| class attr simple | 520 | 22.0% |
| no dict | 240 | 10.2% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 28,100 | 3.4% |
|          hit | 787,707 | 96.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 259 | 29.5% |
| Failure | 620 | 70.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 420 | 67.7% |
| other | 200 | 32.3% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,403,613 | 13.9% |
|          hit | 8,697,288 | 86.0% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,005 | 46.6% |
| Failure | 3,442 | 53.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,002 | 29.1% |
| sequence | 840 | 24.4% |
| set | 700 | 20.3% |
| tuple | 700 | 20.3% |
| other | 200 | 5.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 480 | 0.0% |
|          hit | 2,260,486 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 440 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 231,254,151 | 57.5% |
| Not specialized | 42,307,306 | 10.5% |
| Specialized hits | 128,104,889 | 31.8% |
| Specialized misses | 572,266 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,673,239 | 39.4% |
| LOAD_ATTR | 6,560,153 | 29.8% |
| BINARY_OP | 4,267,381 | 19.4% |
| TO_BOOL | 1,403,613 | 6.4% |
| BINARY_SUBSCR | 590,771 | 2.7% |
| COMPARE_OP | 356,997 | 1.6% |
| STORE_ATTR | 83,922 | 0.4% |
| FOR_ITER | 31,940 | 0.1% |
| STORE_SUBSCR | 28,100 | 0.1% |
| LOAD_GLOBAL | 8,381 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 245,260 | 42.9% |
| LOAD_ATTR_INSTANCE_VALUE | 213,976 | 37.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 81,994 | 14.3% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.2% |
| COMPARE_OP_INT | 7,467 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,060 | 1.1% |
| LOAD_GLOBAL_MODULE | 1,925 | 0.3% |
| LOAD_ATTR_MODULE | 1,100 | 0.2% |
| CALL_PY_EXACT_ARGS | 860 | 0.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 420 | 0.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 10,592,171 | 36.6% |
| Calls to Python functions inlined | 18,338,549 | 63.4% |
| Calls via PyEval_EvalFrame (total) | 10,592,171 | 36.6% |
| Calls via PyEval_EvalFrame (vector) | 10,040,651 | 34.7% |
| Calls via PyEval_EvalFrame (generator) | 551,520 | 1.9% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 10,039,951 | 34.7% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 589,440 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 534,060 | 1.8% |
| Calls via PyEval_EvalFrame (api) | 430,382 | 1.5% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 36,451 | 0.1% |
| Frames pushed | 12,311,108 | 42.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,465,376 | 40.9% |
| Frees to freelist | 14,477,406 |  |
| Allocations | 20,945,091 | 59.1% |
| Allocations to 512 bytes | 20,761,981 | 58.6% |
| Allocations to 4 kbytes | 83,602 | 0.2% |
| Allocations over 4 kbytes | 99,508 | 0.3% |
| Frees | 21,845,080 |  |
| New values | 80,340 |  |
| Interpreter increfs | 180,568,433 | 78.6% |
| Interpreter decrefs | 196,169,519 | 74.9% |
| Increfs | 49,032,269 | 21.4% |
| Decrefs | 65,656,659 | 25.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 7,904,210 |  |
| Method cache misses | 49,458 |  |
| Method cache collisions | 109,198 |  |
| Method cache dunder hits | 9,103,482 |  |
| Method cache dunder misses | 63,416 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 30 | 450 | 223,754 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 4,197 |  |
| Traces created | 797 | 19.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 20 | 0.5% |
| Trace too short | 3,400 | 81.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 10,009,450 |  |
| Uops executed | 84,440,529 | 8.44 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 141 | 17.7% |
| <= 32 | 420 | 52.7% |
| <= 64 | 80 | 10.0% |
| <= 128 | 156 | 19.6% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 80 | 10.0% |
| <= 8 | 61 | 7.7% |
| <= 16 | 340 | 42.7% |
| <= 32 | 140 | 17.6% |
| <= 64 | 56 | 7.0% |
| <= 128 | 120 | 15.1% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,336,366 | 13.4% |
| <= 4 | 1,190,938 | 11.9% |
| <= 8 | 4,895,880 | 48.9% |
| <= 16 | 1,452,202 | 14.5% |
| <= 32 | 959,437 | 9.6% |
| <= 64 | 5,452 | 0.1% |
| <= 128 | 169,139 | 1.7% |
| <= 256 | 11 | 0.0% |
| <= 512 | 2 | 0.0% |
| <= 1,024 | 1 | 0.0% |
| <= 2,048 | 8 | 0.0% |
| <= 4,096 | 6 | 0.0% |
| <= 8,192 | 8 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 14,465,906 | 17.1% | 17.1% |  |
| _EXIT_TRACE | 8,503,794 | 10.1% | 27.2% |  |
| STORE_FAST | 8,397,273 | 9.9% | 37.1% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 7,294,952 | 8.6% | 45.8% | 18.0% |
| _ITER_CHECK_LIST | 7,294,952 | 8.6% | 54.4% |  |
| _ITER_NEXT_LIST | 5,982,734 | 7.1% | 61.5% |  |
| _SET_IP | 5,771,297 | 6.8% | 68.3% |  |
| _CHECK_VALIDITY | 5,312,972 | 6.3% | 74.6% |  |
| _GUARD_GLOBALS_VERSION | 2,187,326 | 2.6% | 77.2% |  |
| PUSH_NULL | 1,783,043 | 2.1% | 79.3% |  |
| _FOR_ITER_TIER_TWO | 1,188,440 | 1.4% | 80.7% |  |
| _GUARD_BUILTINS_VERSION | 1,098,268 | 1.3% | 82.0% |  |
| _LOAD_GLOBAL_BUILTINS | 1,098,268 | 1.3% | 83.3% |  |
| _LOAD_GLOBAL_MODULE | 1,089,058 | 1.3% | 84.6% |  |
| BUILD_TUPLE | 1,081,040 | 1.3% | 85.9% |  |
| _CHECK_ATTR_MODULE | 944,148 | 1.1% | 87.0% |  |
| _LOAD_ATTR_MODULE | 944,148 | 1.1% | 88.2% |  |
| GET_ITER | 675,247 | 0.8% | 89.0% |  |
| _GUARD_TYPE_VERSION | 566,798 | 0.7% | 89.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 538,380 | 0.6% | 90.3% |  |
| BUILD_MAP | 537,920 | 0.6% | 90.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 506,003 | 0.6% | 91.5% |  |
| _GUARD_KEYS_VERSION | 506,003 | 0.6% | 92.1% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 506,003 | 0.6% | 92.7% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 448,341 | 0.5% | 93.2% | 34.2% |
| _ITER_CHECK_RANGE | 448,341 | 0.5% | 93.8% |  |
| LOAD_CONST | 418,716 | 0.5% | 94.3% |  |
| _CHECK_PEP_523 | 375,346 | 0.4% | 94.7% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 375,346 | 0.4% | 95.1% |  |
| _CHECK_STACK_SPACE | 375,346 | 0.4% | 95.6% |  |
| _INIT_CALL_PY_EXACT_ARGS | 375,346 | 0.4% | 96.0% |  |
| _PUSH_FRAME | 375,346 | 0.4% | 96.5% |  |
| _SAVE_RETURN_OFFSET | 375,346 | 0.4% | 96.9% |  |
| RESUME_CHECK | 375,306 | 0.4% | 97.4% |  |
| _LOAD_ATTR | 306,574 | 0.4% | 97.7% |  |
| _ITER_NEXT_RANGE | 295,134 | 0.3% | 98.1% |  |
| BINARY_SUBSCR_LIST_INT | 280,334 | 0.3% | 98.4% |  |
| CALL_BUILTIN_CLASS | 274,574 | 0.3% | 98.7% |  |
| TO_BOOL_BOOL | 174,970 | 0.2% | 98.9% |  |
| _GUARD_IS_TRUE_POP | 167,619 | 0.2% | 99.1% | 0.0% |
| CALL_BUILTIN_FAST | 143,047 | 0.2% | 99.3% |  |
| CALL_LEN | 137,287 | 0.2% | 99.5% |  |
| POP_TOP | 80,533 | 0.1% | 99.6% |  |
| _POP_FRAME | 63,763 | 0.1% | 99.6% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 50,682 | 0.1% | 99.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 50,682 | 0.1% | 99.8% |  |
| _GUARD_IS_NOT_NONE_POP | 31,980 | 0.0% | 99.8% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.9% |  |
| _JUMP_TO_TOP | 22,545 | 0.0% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 13,800 | 0.0% | 99.9% | 88.0% |
| _ITER_CHECK_TUPLE | 13,800 | 0.0% | 99.9% |  |
| _GUARD_IS_FALSE_POP | 10,038 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 8,789 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,440 | 0.0% | 100.0% |  |
| BEFORE_WITH | 5,046 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,960 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,464 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 1,660 | 0.0% | 100.0% |  |
| CONTAINS_OP | 1,324 | 0.0% | 100.0% |  |
| COPY | 1,324 | 0.0% | 100.0% |  |
| SWAP | 1,324 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,324 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 1,324 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 1,324 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 1,324 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 1,324 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,140 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 420 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 420 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 280 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 140 | 0.0% | 100.0% |  |
| IS_OP | 83 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 40 | 0.0% | 100.0% |  |
| LOAD_DEREF | 40 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 40 | 0.0% | 100.0% |  |
| STORE_DEREF | 40 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER_GEN | 3,420 |
| CALL | 200 |
| YIELD_VALUE | 140 |
| LOAD_ATTR_PROPERTY | 120 |
| CALL_PY_WITH_DEFAULTS | 80 |
| CALL_KW | 41 |
| CALL_LIST_APPEND | 40 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 40 |


</details>

---
Stats gathered on: 2023-11-16
