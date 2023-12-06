
# Pystats results

- benchmark: concurrent_imap
- fork: python
- ref: dabc0d77b21d8cc619a2ffcf859f684b6c1c7020
- commit hash: dabc0d7
- commit date: 2023-11-17T15:11:30-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 72,330,637 | 17.3% | 17.3% |  |
| RESUME_CHECK | 29,352,280 | 7.0% | 24.4% | 0.0% |
| STORE_FAST | 22,169,101 | 5.3% | 29.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 19,444,301 | 4.7% | 34.3% | 1.1% |
| POP_TOP | 19,418,413 | 4.7% | 39.0% |  |
| RETURN_VALUE | 17,132,555 | 4.1% | 43.1% |  |
| POP_JUMP_IF_FALSE | 13,683,708 | 3.3% | 46.4% |  |
| LOAD_CONST | 12,312,198 | 3.0% | 49.3% |  |
| LOAD_GLOBAL_MODULE | 10,750,393 | 2.6% | 51.9% | 0.0% |
| INTERPRETER_EXIT | 10,659,034 | 2.6% | 54.5% |  |
| LOAD_FAST_LOAD_FAST | 9,898,238 | 2.4% | 56.8% |  |
| ENTER_EXECUTOR | 8,899,790 | 2.1% | 59.0% |  |
| CALL | 8,820,569 | 2.1% | 61.1% |  |
| CALL_PY_EXACT_ARGS | 8,173,513 | 2.0% | 63.1% | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,287,951 | 1.7% | 64.8% | 1.1% |
| JUMP_BACKWARD | 7,187,696 | 1.7% | 66.5% |  |
| LOAD_ATTR | 6,798,712 | 1.6% | 68.2% |  |
| RETURN_CONST | 6,713,312 | 1.6% | 69.8% |  |
| NOP | 6,680,689 | 1.6% | 71.4% |  |
| YIELD_VALUE | 6,529,020 | 1.6% | 72.9% |  |
| COPY | 6,077,371 | 1.5% | 74.4% |  |
| FOR_ITER_GEN | 5,994,800 | 1.4% | 75.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,153,581 | 1.2% | 77.1% |  |
| TO_BOOL_BOOL | 5,087,774 | 1.2% | 78.3% |  |
| LOAD_GLOBAL_BUILTIN | 5,053,630 | 1.2% | 79.5% | 0.0% |
| PUSH_NULL | 4,722,483 | 1.1% | 80.6% |  |
| BINARY_OP | 4,464,295 | 1.1% | 81.7% |  |
| STORE_FAST_STORE_FAST | 4,344,155 | 1.0% | 82.7% |  |
| POP_JUMP_IF_NOT_NONE | 3,835,908 | 0.9% | 83.7% |  |
| BUILD_TUPLE | 3,654,667 | 0.9% | 84.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,426,989 | 0.8% | 85.4% | 7.2% |
| TO_BOOL_INT | 3,277,164 | 0.8% | 86.1% |  |
| FOR_ITER_LIST | 2,849,708 | 0.7% | 86.8% |  |
| COMPARE_OP_INT | 2,720,324 | 0.7% | 87.5% | 0.3% |
| CALL_FUNCTION_EX | 2,308,004 | 0.6% | 88.0% |  |
| POP_JUMP_IF_TRUE | 2,261,399 | 0.5% | 88.6% |  |
| CALL_PY_WITH_DEFAULTS | 2,053,045 | 0.5% | 89.1% |  |
| SWAP | 1,871,996 | 0.4% | 89.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,720,195 | 0.4% | 89.9% |  |
| LOAD_ATTR_MODULE | 1,608,177 | 0.4% | 90.3% | 0.1% |
| BEFORE_WITH | 1,598,792 | 0.4% | 90.7% |  |
| GET_ITER | 1,581,065 | 0.4% | 91.1% |  |
| BUILD_MAP | 1,459,725 | 0.3% | 91.4% |  |
| TO_BOOL | 1,415,521 | 0.3% | 91.8% |  |
| COMPARE_OP_STR | 1,323,502 | 0.3% | 92.1% |  |
| JUMP_FORWARD | 1,282,509 | 0.3% | 92.4% |  |
| CONTAINS_OP | 1,279,211 | 0.3% | 92.7% |  |
| FOR_ITER | 1,222,620 | 0.3% | 93.0% |  |
| STORE_FAST_LOAD_FAST | 1,198,960 | 0.3% | 93.3% |  |
| CALL_BUILTIN_CLASS | 1,191,997 | 0.3% | 93.6% |  |
| LOAD_DEREF | 1,180,130 | 0.3% | 93.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,175,020 | 0.3% | 94.1% |  |
| COPY_FREE_VARS | 1,131,710 | 0.3% | 94.4% |  |
| UNPACK_SEQUENCE_TUPLE | 1,104,449 | 0.3% | 94.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,103,669 | 0.3% | 94.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,094,009 | 0.3% | 95.2% | 0.0% |
| BINARY_OP_ADD_INT | 1,076,266 | 0.3% | 95.4% |  |
| LOAD_SUPER_ATTR_METHOD | 1,070,270 | 0.3% | 95.7% |  |
| UNARY_INVERT | 1,068,129 | 0.3% | 96.0% |  |
| CALL_BUILTIN_FAST | 1,057,493 | 0.3% | 96.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,055,301 | 0.3% | 96.5% | 0.0% |
| BUILD_LIST | 984,645 | 0.2% | 96.7% |  |
| CALL_METHOD_DESCRIPTOR_O | 830,613 | 0.2% | 96.9% | 0.0% |
| STORE_SUBSCR_DICT | 821,490 | 0.2% | 97.1% |  |
| POP_JUMP_IF_NONE | 812,877 | 0.2% | 97.3% |  |
| CALL_ISINSTANCE | 753,245 | 0.2% | 97.5% |  |
| LOAD_FAST_CHECK | 711,027 | 0.2% | 97.6% |  |
| EXIT_INIT_CHECK | 697,470 | 0.2% | 97.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 697,470 | 0.2% | 98.0% |  |
| LOAD_ATTR_PROPERTY | 674,417 | 0.2% | 98.1% | 1.8% |
| BINARY_SUBSCR | 591,646 | 0.1% | 98.3% |  |
| DICT_MERGE | 561,380 | 0.1% | 98.4% |  |
| CALL_TUPLE_1 | 550,160 | 0.1% | 98.5% |  |
| LIST_APPEND | 544,102 | 0.1% | 98.7% |  |
| LOAD_FAST_AND_CLEAR | 494,837 | 0.1% | 98.8% |  |
| COMPARE_OP | 372,812 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 366,465 | 0.1% | 99.0% |  |
| LIST_EXTEND | 300,866 | 0.1% | 99.0% |  |
| CALL_LEN | 257,754 | 0.1% | 99.1% |  |
| CALL_KW | 255,039 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 242,496 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 225,225 | 0.1% | 99.3% | 0.1% |
| BINARY_OP_SUBTRACT_INT | 214,664 | 0.1% | 99.3% |  |
| FOR_ITER_RANGE | 191,198 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 177,142 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 166,212 | 0.0% | 99.5% |  |
| UNARY_NOT | 165,857 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 150,383 | 0.0% | 99.5% |  |
| CALL_BUILTIN_O | 136,160 | 0.0% | 99.6% |  |
| MAKE_CELL | 133,100 | 0.0% | 99.6% |  |
| STORE_DEREF | 132,820 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 109,120 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 97,240 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 97,240 | 0.0% | 99.7% |  |
| STORE_ATTR | 95,263 | 0.0% | 99.7% |  |
| DELETE_ATTR | 81,591 | 0.0% | 99.7% |  |
| DELETE_SUBSCR | 75,014 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 63,600 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 61,820 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 59,800 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 58,429 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 50,880 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 44,845 | 0.0% | 99.9% | 13.5% |
| IS_OP | 44,162 | 0.0% | 99.9% |  |
| BUILD_STRING | 38,720 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 38,040 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 37,100 | 0.0% | 99.9% |  |
| POP_EXCEPT | 36,146 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 36,146 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 35,320 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 30,706 | 0.0% | 99.9% |  |
| IMPORT_NAME | 30,240 | 0.0% | 99.9% |  |
| IMPORT_FROM | 29,900 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 28,980 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 26,520 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 25,360 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 24,320 | 0.0% | 100.0% |  |
| BINARY_SLICE | 18,220 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,856 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 17,440 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 17,300 | 0.0% | 100.0% |  |
| RERAISE | 16,320 | 0.0% | 100.0% |  |
| CALL_STR_1 | 11,260 | 0.0% | 100.0% |  |
| END_FOR | 10,880 | 0.0% | 100.0% |  |
| STORE_NAME | 7,480 | 0.0% | 100.0% |  |
| RESUME | 5,980 | 0.0% | 100.0% | 0.0% |
| RAISE_VARARGS | 5,460 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,440 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,200 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 2,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,660 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 800 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 560 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 520 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 451 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 280 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 140 | 0.0% | 100.0% | 14.3% |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 17,762,478 | 4.3% | 4.3% |
| RESUME_CHECK LOAD_FAST | 16,745,215 | 4.0% | 8.3% |
| CACHE RESUME_CHECK | 10,582,597 | 2.5% | 10.8% |
| RETURN_VALUE INTERPRETER_EXIT | 9,460,078 | 2.3% | 13.1% |
| LOAD_FAST RETURN_VALUE | 8,838,196 | 2.1% | 15.2% |
| STORE_FAST LOAD_FAST | 8,639,586 | 2.1% | 17.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,129,513 | 1.9% | 19.2% |
| POP_TOP ENTER_EXECUTOR | 6,744,328 | 1.6% | 20.8% |
| RESUME_CHECK POP_TOP | 6,528,880 | 1.6% | 22.4% |
| JUMP_BACKWARD FOR_ITER_GEN | 5,983,920 | 1.4% | 23.8% |
| YIELD_VALUE STORE_FAST | 5,983,920 | 1.4% | 25.3% |
| FOR_ITER_GEN RESUME_CHECK | 5,983,920 | 1.4% | 26.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,611,646 | 1.3% | 28.0% |
| STORE_FAST JUMP_BACKWARD | 5,440,000 | 1.3% | 29.3% |
| POP_TOP LOAD_FAST | 5,182,422 | 1.2% | 30.6% |
| LOAD_FAST LOAD_ATTR | 5,014,582 | 1.2% | 31.8% |
| ENTER_EXECUTOR YIELD_VALUE | 4,895,440 | 1.2% | 33.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,864,028 | 1.2% | 34.1% |
| RETURN_CONST POP_TOP | 4,637,504 | 1.1% | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,550,841 | 1.1% | 36.3% |
| NOP LOAD_FAST | 3,961,848 | 0.9% | 37.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,826,851 | 0.9% | 38.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,414,188 | 0.8% | 39.0% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,277,024 | 0.8% | 39.8% |
| LOAD_CONST LOAD_CONST | 3,267,722 | 0.8% | 40.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,179,024 | 0.8% | 41.4% |
| STORE_FAST NOP | 3,005,580 | 0.7% | 42.1% |
| PUSH_NULL LOAD_FAST | 3,005,457 | 0.7% | 42.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,952,148 | 0.7% | 43.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,717,957 | 0.7% | 44.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,660,262 | 0.6% | 44.8% |
| LOAD_FAST LOAD_CONST | 2,610,805 | 0.6% | 45.4% |
| COPY STORE_FAST | 2,597,760 | 0.6% | 46.0% |
| STORE_FAST COPY | 2,597,440 | 0.6% | 46.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,516,629 | 0.6% | 47.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,479,715 | 0.6% | 47.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,399,485 | 0.6% | 48.4% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,374,617 | 0.6% | 49.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,286,057 | 0.5% | 49.6% |
| LOAD_CONST CALL | 2,282,681 | 0.5% | 50.1% |
| LOAD_FAST PUSH_NULL | 2,275,139 | 0.5% | 50.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,193,292 | 0.5% | 51.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,176,283 | 0.5% | 51.7% |
| LOAD_ATTR LOAD_FAST | 2,075,498 | 0.5% | 52.2% |
| CALL STORE_FAST | 2,072,780 | 0.5% | 52.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,949,035 | 0.5% | 53.2% |
| CALL RETURN_VALUE | 1,938,445 | 0.5% | 53.6% |
| CALL POP_TOP | 1,888,584 | 0.5% | 54.1% |
| BINARY_OP COPY | 1,804,414 | 0.4% | 54.5% |
| COPY TO_BOOL_INT | 1,804,094 | 0.4% | 54.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,795,356 | 0.4% | 55.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,755,154 | 0.4% | 55.8% |
| LOAD_FAST CALL_FUNCTION_EX | 1,746,604 | 0.4% | 56.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,717,778 | 0.4% | 56.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,714,135 | 0.4% | 57.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,678,683 | 0.4% | 57.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,604,937 | 0.4% | 57.8% |
| ENTER_EXECUTOR CALL | 1,591,795 | 0.4% | 58.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,556,232 | 0.4% | 58.6% |
| POP_TOP RETURN_CONST | 1,550,016 | 0.4% | 58.9% |
| POP_TOP LOAD_CONST | 1,522,171 | 0.4% | 59.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,507,769 | 0.4% | 59.7% |
| RETURN_VALUE STORE_FAST | 1,476,015 | 0.4% | 60.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,466,460 | 0.4% | 60.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,427,482 | 0.3% | 60.7% |
| LOAD_CONST LOAD_FAST | 1,415,382 | 0.3% | 61.1% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,388,124 | 0.3% | 61.4% |
| LOAD_FAST TO_BOOL | 1,357,726 | 0.3% | 61.7% |
| ENTER_EXECUTOR FOR_ITER_LIST | 1,345,252 | 0.3% | 62.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,341,105 | 0.3% | 62.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,329,958 | 0.3% | 62.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,316,760 | 0.3% | 63.0% |
| LOAD_FAST BUILD_TUPLE | 1,293,845 | 0.3% | 63.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,291,566 | 0.3% | 63.6% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,288,733 | 0.3% | 63.9% |
| LOAD_CONST COMPARE_OP_INT | 1,283,428 | 0.3% | 64.2% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,278,591 | 0.3% | 64.5% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,277,931 | 0.3% | 64.8% |
| BEFORE_WITH POP_TOP | 1,276,987 | 0.3% | 65.1% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,264,424 | 0.3% | 65.4% |
| RETURN_VALUE RETURN_VALUE | 1,233,277 | 0.3% | 65.7% |
| LOAD_ATTR PUSH_NULL | 1,211,692 | 0.3% | 66.0% |
| CALL_FUNCTION_EX RETURN_VALUE | 1,196,024 | 0.3% | 66.3% |
| JUMP_BACKWARD FOR_ITER | 1,191,547 | 0.3% | 66.6% |
| GET_ITER FOR_ITER_LIST | 1,183,370 | 0.3% | 66.9% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 1,179,910 | 0.3% | 67.2% |
| POP_TOP NOP | 1,169,006 | 0.3% | 67.5% |
| NOP LOAD_GLOBAL_MODULE | 1,165,836 | 0.3% | 67.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,162,516 | 0.3% | 68.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,146,052 | 0.3% | 68.3% |
| COPY_FREE_VARS RESUME_CHECK | 1,131,050 | 0.3% | 68.6% |
| LOAD_DEREF LOAD_FAST | 1,125,750 | 0.3% | 68.8% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,125,230 | 0.3% | 69.1% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,109,287 | 0.3% | 69.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,099,213 | 0.3% | 69.6% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,097,241 | 0.3% | 69.9% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,094,720 | 0.3% | 70.2% |
| POP_TOP JUMP_BACKWARD | 1,093,979 | 0.3% | 70.4% |
| BUILD_TUPLE YIELD_VALUE | 1,088,060 | 0.3% | 70.7% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,070,070 | 0.3% | 70.9% |


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
| RESUME_CHECK | 10,582,597 | 99.2% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,179,910 | 73.8% |
| RETURN_VALUE | 316,465 | 19.8% |
| LOAD_GLOBAL_MODULE | 79,557 | 5.0% |
| LOAD_FAST | 16,320 | 1.0% |
| CALL | 6,040 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,276,987 | 79.9% |
| STORE_FAST | 321,805 | 20.1% |


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
| LOAD_FAST_LOAD_FAST | 544,080 | 92.0% |
| LOAD_CONST | 46,646 | 7.9% |
| BINARY_SUBSCR | 840 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 543,920 | 91.9% |
| STORE_FAST | 46,366 | 7.8% |
| BINARY_SUBSCR | 840 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,546 | 83.2% |
| LOAD_ATTR_MODULE | 5,100 | 16.6% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,706 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,937 | 49.2% |
| CALL | 26,557 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,438 | 15.2% |
| LOAD_ATTR | 82 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,557 | 78.1% |
| RETURN_CONST | 10,237 | 13.6% |
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
| RETURN_CONST | 697,470 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 697,470 | 100.0% |


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
| LOAD_FAST | 977,745 | 61.8% |
| STORE_FAST_LOAD_FAST | 544,000 | 34.4% |
| CALL_BUILTIN_CLASS | 34,980 | 2.2% |
| CALL | 12,420 | 0.8% |
| RETURN_VALUE | 5,440 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,183,370 | 74.8% |
| LOAD_FAST_AND_CLEAR | 328,915 | 20.8% |
| FOR_ITER_RANGE | 29,027 | 1.8% |
| FOR_ITER | 11,473 | 0.7% |
| FOR_ITER_TUPLE | 11,100 | 0.7% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,460,078 | 88.8% |
| RETURN_CONST | 653,856 | 6.1% |
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
| STORE_FAST | 3,005,580 | 45.0% |
| POP_TOP | 1,169,006 | 17.5% |
| POP_JUMP_IF_FALSE | 1,037,322 | 15.5% |
| RESUME_CHECK | 929,345 | 13.9% |
| POP_JUMP_IF_NOT_NONE | 323,403 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,961,848 | 59.3% |
| LOAD_GLOBAL_MODULE | 1,165,836 | 17.5% |
| LOAD_FAST_LOAD_FAST | 550,360 | 8.2% |
| LOAD_CONST | 529,060 | 7.9% |
| LOAD_GLOBAL_BUILTIN | 461,985 | 6.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 19,766 | 54.7% |
| COPY | 10,880 | 30.1% |
| POP_TOP | 5,200 | 14.4% |
| STORE_FAST | 280 | 0.8% |
| STORE_SUBSCR_DICT | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 19,366 | 53.6% |
| RERAISE | 10,880 | 30.1% |
| JUMP_FORWARD | 5,120 | 14.2% |
| JUMP_BACKWARD | 700 | 1.9% |
| RETURN_CONST | 60 | 0.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,528,880 | 33.6% |
| RETURN_CONST | 4,637,504 | 23.9% |
| CALL | 1,888,584 | 9.7% |
| BEFORE_WITH | 1,276,987 | 6.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,043,660 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,744,328 | 34.7% |
| LOAD_FAST | 5,182,422 | 26.7% |
| RETURN_CONST | 1,550,016 | 8.0% |
| LOAD_CONST | 1,522,171 | 7.8% |
| NOP | 1,169,006 | 6.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 25,166 | 69.6% |
| RERAISE | 5,440 | 15.1% |
| CALL_KW | 5,120 | 14.2% |
| BINARY_SUBSCR_DICT | 300 | 0.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,506 | 70.6% |
| WITH_EXCEPT_START | 5,440 | 15.1% |
| LOAD_GLOBAL_MODULE | 5,080 | 14.1% |
| LOAD_GLOBAL | 120 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,275,139 | 48.2% |
| LOAD_ATTR | 1,211,692 | 25.7% |
| LOAD_ATTR_MODULE | 1,146,052 | 24.3% |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,005,457 | 63.6% |
| LOAD_FAST_LOAD_FAST | 713,198 | 15.1% |
| CALL | 698,828 | 14.8% |
| LOAD_CONST | 237,514 | 5.0% |
| CALL_PY_EXACT_ARGS | 44,840 | 0.9% |


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
| LOAD_FAST | 8,838,196 | 51.6% |
| CALL | 1,938,445 | 11.3% |
| RETURN_VALUE | 1,233,277 | 7.2% |
| CALL_FUNCTION_EX | 1,196,024 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,036,108 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,460,078 | 55.2% |
| STORE_FAST | 1,476,015 | 8.6% |
| RETURN_VALUE | 1,233,277 | 7.2% |
| POP_TOP | 954,253 | 5.6% |
| LOAD_FAST_LOAD_FAST | 736,285 | 4.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 12,160 | 42.0% |
| LOAD_FAST | 10,440 | 36.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,480 | 18.9% |
| STORE_SUBSCR | 620 | 2.1% |
| LOAD_ATTR | 200 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 17,720 | 61.1% |
| LOAD_GLOBAL_MODULE | 10,200 | 35.2% |
| STORE_SUBSCR | 620 | 2.1% |
| STORE_SUBSCR_DICT | 260 | 0.9% |
| LOAD_GLOBAL | 80 | 0.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,357,726 | 95.9% |
| LOAD_ATTR_INSTANCE_VALUE | 49,976 | 3.5% |
| TO_BOOL | 3,441 | 0.2% |
| LOAD_ATTR | 888 | 0.1% |
| RETURN_VALUE | 770 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 721,990 | 51.0% |
| POP_JUMP_IF_FALSE | 687,046 | 48.5% |
| TO_BOOL | 3,441 | 0.2% |
| TO_BOOL_BOOL | 2,164 | 0.2% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 736,285 | 68.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 331,764 | 31.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,068,129 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 165,817 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 165,857 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,374,617 | 53.2% |
| UNARY_INVERT | 1,068,129 | 23.9% |
| POP_JUMP_IF_FALSE | 736,285 | 16.5% |
| LOAD_ATTR | 178,102 | 4.0% |
| LOAD_FAST_LOAD_FAST | 49,920 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,804,414 | 40.4% |
| STORE_FAST | 914,707 | 20.5% |
| TO_BOOL_INT | 736,345 | 16.5% |
| UNARY_INVERT | 736,285 | 16.5% |
| BUILD_TUPLE | 165,922 | 3.7% |


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
| SWAP | 328,915 | 33.4% |
| JUMP_FORWARD | 316,225 | 32.1% |
| LOAD_FAST | 166,272 | 16.9% |
| POP_TOP | 149,973 | 15.2% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 332,825 | 33.8% |
| SWAP | 328,915 | 33.4% |
| STORE_FAST | 317,045 | 32.2% |
| RETURN_VALUE | 5,120 | 0.5% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 544,000 | 37.3% |
| LOAD_FAST | 528,600 | 36.2% |
| RESUME_CHECK | 326,425 | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 2.2% |
| POP_JUMP_IF_NOT_NONE | 16,320 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 899,385 | 61.6% |
| BUILD_TUPLE | 544,020 | 37.3% |
| STORE_FAST | 16,320 | 1.1% |


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
| LOAD_FAST | 1,293,845 | 35.4% |
| LOAD_FAST_LOAD_FAST | 1,094,720 | 30.0% |
| BUILD_MAP | 544,020 | 14.9% |
| RETURN_VALUE | 512,000 | 14.0% |
| BINARY_OP | 165,922 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 1,088,060 | 29.8% |
| CALL | 737,205 | 20.2% |
| BUILD_MAP | 544,000 | 14.9% |
| STORE_FAST | 512,000 | 14.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 14.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,282,681 | 25.9% |
| ENTER_EXECUTOR | 1,591,795 | 18.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,329,958 | 15.1% |
| LOAD_FAST_LOAD_FAST | 862,517 | 9.8% |
| BUILD_TUPLE | 737,205 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,072,780 | 23.5% |
| RETURN_VALUE | 1,938,445 | 22.0% |
| POP_TOP | 1,888,584 | 21.4% |
| LOAD_FAST | 776,697 | 8.8% |
| TO_BOOL_BOOL | 682,336 | 7.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,746,604 | 75.7% |
| DICT_MERGE | 561,380 | 24.3% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,196,024 | 51.8% |
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
| LOAD_CONST | 249,915 | 98.0% |
| ENTER_EXECUTOR | 5,124 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 191,813 | 75.2% |
| LOAD_FAST | 27,200 | 10.7% |
| RETURN_VALUE | 18,240 | 7.2% |
| STORE_FAST | 12,300 | 4.8% |
| PUSH_EXC_INFO | 5,120 | 2.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 368,016 | 98.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,588 | 0.4% |
| COMPARE_OP | 1,254 | 0.3% |
| LOAD_GLOBAL_MODULE | 378 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 369,564 | 99.1% |
| COMPARE_OP | 1,254 | 0.3% |
| COMPARE_OP_INT | 1,196 | 0.3% |
| COMPARE_OP_STR | 438 | 0.1% |
| POP_JUMP_IF_TRUE | 280 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,277,931 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,278,591 | 100.0% |
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
| STORE_FAST | 2,597,440 | 42.7% |
| BINARY_OP | 1,804,414 | 29.7% |
| LOAD_CONST | 1,067,520 | 17.6% |
| LOAD_FAST | 553,926 | 9.1% |
| STORE_ATTR_INSTANCE_VALUE | 18,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,597,760 | 42.7% |
| TO_BOOL_INT | 1,804,094 | 29.7% |
| STORE_FAST_STORE_FAST | 1,061,440 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 541,626 | 8.9% |
| LOAD_FAST | 24,320 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 736,285 | 65.1% |
| CALL_ALLOC_AND_ENTER_INIT | 316,185 | 27.9% |
| CACHE | 73,100 | 6.5% |
| CALL | 5,620 | 0.5% |
| CALL_PY_EXACT_ARGS | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,131,050 | 99.9% |
| RETURN_GENERATOR | 340 | 0.0% |
| RESUME | 320 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,591 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,394 | 66.7% |
| RETURN_CONST | 26,557 | 32.5% |
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
| POP_TOP | 6,744,328 | 75.8% |
| POP_JUMP_IF_NOT_NONE | 811,346 | 9.1% |
| STORE_FAST_STORE_FAST | 543,320 | 6.1% |
| LIST_APPEND | 445,802 | 5.0% |
| CALL_LIST_APPEND | 165,242 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,895,440 | 55.0% |
| CALL | 1,591,795 | 17.9% |
| FOR_ITER_LIST | 1,345,252 | 15.1% |
| CALL_PY_WITH_DEFAULTS | 456,514 | 5.1% |
| LOAD_ATTR_PROPERTY | 433,476 | 4.9% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,191,547 | 97.5% |
| SWAP | 12,240 | 1.0% |
| GET_ITER | 11,473 | 0.9% |
| LOAD_FAST | 5,740 | 0.5% |
| FOR_ITER | 1,620 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 641,320 | 52.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 549,280 | 44.9% |
| SWAP | 12,160 | 1.0% |
| RETURN_CONST | 11,180 | 0.9% |
| LOAD_GLOBAL_MODULE | 5,360 | 0.4% |


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
| LOAD_GLOBAL_MODULE | 1,102 | 2.5% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,022 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,440,000 | 75.7% |
| POP_TOP | 1,093,979 | 15.2% |
| FOR_ITER_LIST | 544,000 | 7.6% |
| LIST_APPEND | 98,300 | 1.4% |
| STORE_FAST_STORE_FAST | 6,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 5,983,920 | 83.3% |
| FOR_ITER | 1,191,547 | 16.6% |
| FOR_ITER_LIST | 4,911 | 0.1% |
| FOR_ITER_RANGE | 2,158 | 0.0% |
| LOAD_FAST | 1,663 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 679,737 | 53.0% |
| POP_TOP | 585,832 | 45.7% |
| STORE_ATTR_INSTANCE_VALUE | 6,060 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 5,400 | 0.4% |
| POP_EXCEPT | 5,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 906,581 | 70.7% |
| BUILD_LIST | 316,225 | 24.7% |
| LOAD_GLOBAL_MODULE | 22,577 | 1.8% |
| POP_EXCEPT | 19,766 | 1.5% |
| LOAD_FAST_LOAD_FAST | 6,360 | 0.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 280,020 | 51.5% |
| LOAD_ATTR | 165,942 | 30.5% |
| BINARY_SUBSCR_STR_INT | 97,240 | 17.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 860 | 0.2% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 445,802 | 81.9% |
| JUMP_BACKWARD | 98,300 | 18.1% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 150,753 | 50.1% |
| RETURN_VALUE | 149,973 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 150,293 | 50.0% |
| STORE_FAST | 149,973 | 49.8% |
| RETURN_VALUE | 320 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.1% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,014,582 | 73.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,556,232 | 22.9% |
| LOAD_GLOBAL_MODULE | 121,560 | 1.8% |
| CALL | 49,620 | 0.7% |
| LOAD_ATTR | 20,810 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,075,498 | 30.5% |
| PUSH_NULL | 1,211,692 | 17.8% |
| STORE_SUBSCR_DICT | 736,205 | 10.8% |
| POP_JUMP_IF_NOT_NONE | 688,766 | 10.1% |
| STORE_FAST | 490,003 | 7.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,267,722 | 26.5% |
| LOAD_FAST | 2,610,805 | 21.2% |
| POP_TOP | 1,522,171 | 12.4% |
| POP_JUMP_IF_FALSE | 791,943 | 6.4% |
| LOAD_ATTR_METHOD_NO_DICT | 682,926 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,267,722 | 26.5% |
| CALL | 2,282,681 | 18.5% |
| LOAD_FAST | 1,415,382 | 11.5% |
| COMPARE_OP_INT | 1,283,428 | 10.4% |
| COPY | 1,067,520 | 8.7% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,125,230 | 95.3% |
| POP_JUMP_IF_NOT_NONE | 26,560 | 2.3% |
| STORE_DEREF | 26,560 | 2.3% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,125,750 | 95.4% |
| POP_JUMP_IF_NOT_NONE | 53,120 | 4.5% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 16,745,215 | 23.2% |
| STORE_FAST | 8,639,586 | 11.9% |
| POP_JUMP_IF_FALSE | 5,611,646 | 7.8% |
| POP_TOP | 5,182,422 | 7.2% |
| NOP | 3,961,848 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 17,762,478 | 24.6% |
| RETURN_VALUE | 8,838,196 | 12.2% |
| LOAD_ATTR | 5,014,582 | 6.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,864,028 | 6.7% |
| CALL_PY_EXACT_ARGS | 3,179,024 | 4.4% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 328,915 | 66.5% |
| LOAD_FAST_AND_CLEAR | 165,922 | 33.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 328,915 | 66.5% |
| LOAD_FAST_AND_CLEAR | 165,922 | 33.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 544,560 | 76.6% |
| POP_JUMP_IF_NONE | 150,303 | 21.1% |
| LOAD_ATTR_CLASS | 15,844 | 2.2% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 543,920 | 76.5% |
| LOAD_GLOBAL_MODULE | 150,223 | 21.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 15,804 | 2.2% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,678,683 | 17.0% |
| LOAD_FAST_LOAD_FAST | 1,341,105 | 13.5% |
| POP_JUMP_IF_FALSE | 948,512 | 9.6% |
| STORE_FAST_STORE_FAST | 825,371 | 8.3% |
| LOAD_SUPER_ATTR_METHOD | 748,645 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,193,292 | 22.2% |
| LOAD_FAST_LOAD_FAST | 1,341,105 | 13.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,097,241 | 11.1% |
| BUILD_TUPLE | 1,094,720 | 11.1% |
| CALL | 862,517 | 8.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.2% |
| RESUME_CHECK | 1,720 | 9.6% |
| POP_JUMP_IF_FALSE | 1,707 | 9.6% |
| LOAD_FAST | 1,600 | 9.0% |
| RESUME | 1,520 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,818 | 38.2% |
| LOAD_ATTR | 3,328 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 2,742 | 15.4% |
| LOAD_FAST | 2,168 | 12.1% |
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
| TO_BOOL_BOOL | 3,414,188 | 25.0% |
| TO_BOOL_INT | 3,277,024 | 23.9% |
| COMPARE_OP_INT | 2,717,957 | 19.9% |
| COMPARE_OP_STR | 1,288,733 | 9.4% |
| CONTAINS_OP | 1,278,591 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,611,646 | 41.0% |
| RETURN_CONST | 2,399,485 | 17.5% |
| NOP | 1,037,322 | 7.6% |
| LOAD_GLOBAL_MODULE | 967,022 | 7.1% |
| LOAD_FAST_LOAD_FAST | 948,512 | 6.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 742,757 | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE | 44,600 | 5.5% |
| LOAD_ATTR | 24,460 | 3.0% |
| RETURN_VALUE | 760 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229,678 | 28.3% |
| LOAD_GLOBAL_MODULE | 200,243 | 24.6% |
| NOP | 186,933 | 23.0% |
| LOAD_FAST_CHECK | 150,303 | 18.5% |
| RETURN_CONST | 22,420 | 2.8% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,176,283 | 56.7% |
| LOAD_ATTR | 688,766 | 18.0% |
| LOAD_ATTR_INSTANCE_VALUE | 615,973 | 16.1% |
| RETURN_VALUE | 280,340 | 7.3% |
| LOAD_DEREF | 53,120 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,717,778 | 44.8% |
| ENTER_EXECUTOR | 811,346 | 21.2% |
| RETURN_CONST | 689,411 | 18.0% |
| NOP | 323,403 | 8.4% |
| LOAD_CONST | 150,253 | 3.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,507,769 | 66.7% |
| TO_BOOL | 721,990 | 31.9% |
| TO_BOOL_NONE | 17,460 | 0.8% |
| COMPARE_OP_STR | 10,529 | 0.5% |
| COMPARE_OP_INT | 1,951 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 909,295 | 40.2% |
| LOAD_FAST_LOAD_FAST | 722,862 | 32.0% |
| RETURN_CONST | 476,286 | 21.1% |
| LOAD_GLOBAL_MODULE | 57,651 | 2.5% |
| RETURN_VALUE | 46,326 | 2.0% |


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
| POP_JUMP_IF_FALSE | 2,399,485 | 35.7% |
| POP_TOP | 1,550,016 | 23.1% |
| STORE_ATTR_INSTANCE_VALUE | 1,466,460 | 21.8% |
| POP_JUMP_IF_NOT_NONE | 689,411 | 10.3% |
| POP_JUMP_IF_TRUE | 476,286 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,637,504 | 69.1% |
| EXIT_INIT_CHECK | 697,470 | 10.4% |
| INTERPRETER_EXIT | 653,856 | 9.7% |
| TO_BOOL_BOOL | 640,370 | 9.5% |
| STORE_FAST | 47,526 | 0.7% |


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
| LOAD_FAST | 56,323 | 59.1% |
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
| YIELD_VALUE | 5,983,920 | 27.0% |
| COPY | 2,597,760 | 11.7% |
| CALL | 2,072,780 | 9.3% |
| RETURN_VALUE | 1,476,015 | 6.7% |
| STORE_FAST_STORE_FAST | 1,056,280 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,639,586 | 39.0% |
| JUMP_BACKWARD | 5,440,000 | 24.5% |
| NOP | 3,005,580 | 13.6% |
| COPY | 2,597,440 | 11.7% |
| JUMP_FORWARD | 679,737 | 3.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 641,320 | 53.5% |
| FOR_ITER_LIST | 544,620 | 45.4% |
| COPY | 12,160 | 1.0% |
| FOR_ITER_TUPLE | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 544,600 | 45.4% |
| GET_ITER | 544,000 | 45.4% |
| LOAD_FAST | 97,280 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 12,080 | 1.0% |
| TO_BOOL_STR | 860 | 0.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,714,135 | 39.5% |
| COPY | 1,061,440 | 24.4% |
| UNPACK_SEQUENCE_TUPLE | 1,056,220 | 24.3% |
| STORE_FAST_STORE_FAST | 512,000 | 11.8% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,388,124 | 32.0% |
| STORE_FAST | 1,056,280 | 24.3% |
| LOAD_FAST_LOAD_FAST | 825,371 | 19.0% |
| ENTER_EXECUTOR | 543,320 | 12.5% |
| STORE_FAST_STORE_FAST | 512,000 | 11.8% |


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
| BINARY_OP_ADD_INT | 541,686 | 28.9% |
| BUILD_LIST | 328,915 | 17.6% |
| LOAD_FAST_AND_CLEAR | 328,915 | 17.6% |
| FOR_ITER_LIST | 315,895 | 16.9% |
| LOAD_FAST | 177,143 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 541,626 | 28.9% |
| LOAD_CONST | 343,065 | 18.3% |
| BUILD_LIST | 328,915 | 17.6% |
| STORE_FAST | 328,915 | 17.6% |
| FOR_ITER_LIST | 315,815 | 16.9% |


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
| ENTER_EXECUTOR | 4,895,440 | 75.0% |
| BUILD_TUPLE | 1,088,060 | 16.7% |
| STORE_FAST_LOAD_FAST | 544,600 | 8.3% |
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
| LOAD_FAST | 166,172 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 166,212 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,059,226 | 98.4% |
| LOAD_FAST_LOAD_FAST | 16,880 | 1.6% |
| BINARY_OP | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 541,686 | 50.3% |
| STORE_FAST | 511,980 | 47.6% |
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
| CALL | 150,223 | 99.9% |
| BINARY_OP | 80 | 0.1% |
| LOAD_FAST | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 150,383 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 162,858 | 75.9% |
| LOAD_CONST | 46,246 | 21.5% |
| CALL_LEN | 5,360 | 2.5% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 209,264 | 97.5% |
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
| LOAD_GLOBAL_MODULE | 342,665 | 49.1% |
| LOAD_FAST | 322,245 | 46.2% |
| CALL | 32,140 | 4.6% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |
| ENTER_EXECUTOR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 381,285 | 54.7% |
| COPY_FREE_VARS | 316,185 | 45.3% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,240 | 71.9% |
| LOAD_CONST | 6,360 | 14.2% |
| BINARY_OP_ADD_INT | 5,360 | 12.0% |
| PUSH_NULL | 626 | 1.4% |
| CALL | 159 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 38,785 | 86.5% |
| POP_TOP | 5,960 | 13.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 100 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 511,960 | 42.9% |
| RETURN_VALUE | 456,165 | 38.3% |
| LOAD_FAST | 182,672 | 15.3% |
| LOAD_CONST | 12,360 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 10,260 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 678,192 | 56.9% |
| STORE_FAST | 456,465 | 38.3% |
| GET_ITER | 34,980 | 2.9% |
| LOAD_FAST | 16,320 | 1.4% |
| CALL_BUILTIN_CLASS | 6,000 | 0.5% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 551,873 | 52.2% |
| LOAD_CONST | 301,133 | 28.5% |
| LOAD_FAST_LOAD_FAST | 107,058 | 10.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,189 | 4.6% |
| LOAD_GLOBAL_MODULE | 24,040 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 367,520 | 34.8% |
| TO_BOOL_BOOL | 293,313 | 27.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 281,331 | 26.6% |
| UNPACK_SEQUENCE_TUPLE | 48,189 | 4.6% |
| POP_TOP | 12,720 | 1.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 515,460 | 47.1% |
| BUILD_TUPLE | 511,960 | 46.8% |
| CALL | 32,605 | 3.0% |
| LOAD_FAST_CHECK | 15,804 | 1.4% |
| LOAD_ATTR | 12,080 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,043,660 | 95.4% |
| RETURN_VALUE | 49,089 | 4.5% |
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
| LOAD_GLOBAL_BUILTIN | 752,785 | 99.9% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 753,065 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 230,432 | 89.4% |
| LOAD_ATTR_INSTANCE_VALUE | 26,940 | 10.5% |
| CALL | 382 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 207,738 | 80.6% |
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
| BUILD_TUPLE | 165,842 | 93.6% |
| LOAD_FAST | 10,800 | 6.1% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 165,242 | 93.3% |
| LOAD_GLOBAL_MODULE | 10,800 | 6.1% |
| JUMP_BACKWARD | 640 | 0.4% |
| NOP | 280 | 0.2% |
| RETURN_CONST | 140 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,052,490 | 99.7% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.1% |
| LOAD_CONST | 600 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 491 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 736,565 | 69.8% |
| STORE_FAST | 316,976 | 30.0% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,109,287 | 94.4% |
| LOAD_ATTR_METHOD_LAZY_DICT | 63,993 | 5.4% |
| LOAD_ATTR | 1,200 | 0.1% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 543,960 | 46.3% |
| POP_TOP | 442,557 | 37.7% |
| LOAD_FAST | 50,180 | 4.3% |
| RETURN_VALUE | 48,648 | 4.1% |
| CALL_BUILTIN_FAST | 48,189 | 4.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 758,853 | 91.4% |
| LOAD_CONST | 30,200 | 3.6% |
| CALL | 27,540 | 3.3% |
| RETURN_VALUE | 12,080 | 1.5% |
| STORE_FAST | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 786,533 | 94.7% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 3,826,851 | 46.8% |
| LOAD_FAST | 3,179,024 | 38.9% |
| LOAD_FAST_LOAD_FAST | 562,280 | 6.9% |
| LOAD_SUPER_ATTR_METHOD | 316,145 | 3.9% |
| LOAD_GLOBAL_MODULE | 90,380 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,129,513 | 99.5% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 935,806 | 45.6% |
| ENTER_EXECUTOR | 456,514 | 22.2% |
| LOAD_ATTR_MODULE | 316,345 | 15.4% |
| LOAD_FAST | 214,962 | 10.5% |
| LOAD_CONST | 73,775 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,316,760 | 64.1% |
| COPY_FREE_VARS | 736,285 | 35.9% |


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
| LOAD_CONST | 1,283,428 | 47.2% |
| LOAD_ATTR_INSTANCE_VALUE | 854,289 | 31.4% |
| LOAD_FAST | 544,980 | 20.0% |
| LOAD_FAST_LOAD_FAST | 16,880 | 0.6% |
| CALL_BUILTIN_FAST | 12,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,717,957 | 99.9% |
| POP_JUMP_IF_TRUE | 1,951 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 116 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,264,424 | 95.5% |
| LOAD_CONST | 53,140 | 4.0% |
| LOAD_FAST | 5,500 | 0.4% |
| COMPARE_OP | 438 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,288,733 | 97.4% |
| COPY | 12,120 | 0.9% |
| LOAD_FAST | 12,120 | 0.9% |
| POP_JUMP_IF_TRUE | 10,529 | 0.8% |


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
| ENTER_EXECUTOR | 1,345,252 | 47.2% |
| GET_ITER | 1,183,370 | 41.5% |
| SWAP | 315,815 | 11.1% |
| JUMP_BACKWARD | 4,911 | 0.2% |
| FOR_ITER | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 632,450 | 22.2% |
| STORE_FAST_LOAD_FAST | 544,620 | 19.1% |
| JUMP_BACKWARD | 544,000 | 19.1% |
| STORE_FAST | 474,079 | 16.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 331,824 | 11.6% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 159,813 | 83.6% |
| GET_ITER | 29,027 | 15.2% |
| JUMP_BACKWARD | 2,158 | 1.1% |
| FOR_ITER | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 150,133 | 78.5% |
| STORE_FAST | 30,505 | 16.0% |
| RETURN_CONST | 10,560 | 5.5% |


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
| LOAD_GLOBAL_MODULE | 48,149 | 82.4% |
| LOAD_ATTR_MODULE | 10,200 | 17.5% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,585 | 72.9% |
| LOAD_FAST_CHECK | 15,844 | 27.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,762,478 | 91.4% |
| LOAD_FAST_LOAD_FAST | 1,097,241 | 5.6% |
| COPY | 541,626 | 2.8% |
| LOAD_ATTR_INSTANCE_VALUE | 21,251 | 0.1% |
| RETURN_VALUE | 12,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,550,841 | 23.4% |
| LOAD_FAST | 2,952,148 | 15.2% |
| LOAD_ATTR | 1,556,232 | 8.0% |
| LOAD_GLOBAL_MODULE | 1,291,566 | 6.6% |
| CONTAINS_OP | 1,277,931 | 6.6% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,316 | 99.9% |
| LOAD_ATTR | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,498 | 39.8% |
| CALL | 82,005 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 63,993 | 26.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,550,841 | 88.3% |
| LOAD_FAST | 475,520 | 9.2% |
| LOAD_ATTR | 51,040 | 1.0% |
| LOAD_ATTR_SLOT | 49,520 | 1.0% |
| LOAD_CONST | 12,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,795,356 | 34.8% |
| CALL | 1,329,958 | 25.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,109,287 | 21.5% |
| LOAD_CONST | 682,926 | 13.3% |
| LOAD_FAST_LOAD_FAST | 207,254 | 4.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,864,028 | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,099,213 | 15.1% |
| LOAD_FAST_LOAD_FAST | 736,205 | 10.1% |
| BINARY_SUBSCR | 543,920 | 7.5% |
| LOAD_GLOBAL_MODULE | 27,260 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,826,851 | 52.5% |
| LOAD_FAST | 1,755,154 | 24.1% |
| CALL_PY_WITH_DEFAULTS | 935,806 | 12.8% |
| LOAD_FAST_LOAD_FAST | 610,720 | 8.4% |
| LOAD_CONST | 90,655 | 1.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,604,937 | 99.8% |
| LOAD_ATTR | 2,820 | 0.2% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,146,052 | 71.3% |
| CALL_PY_WITH_DEFAULTS | 316,345 | 19.7% |
| STORE_DEREF | 53,120 | 3.3% |
| LOAD_CONST | 31,040 | 1.9% |
| LOAD_FAST | 27,840 | 1.7% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 771,685 | 69.9% |
| LOAD_FAST_LOAD_FAST | 331,684 | 30.1% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 736,245 | 66.7% |
| UNARY_INVERT | 331,764 | 30.1% |
| RETURN_VALUE | 12,120 | 1.1% |
| LOAD_CONST | 12,120 | 1.1% |
| LOAD_FAST_LOAD_FAST | 5,400 | 0.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 433,476 | 64.3% |
| LOAD_FAST | 213,321 | 31.6% |
| RETURN_VALUE | 26,480 | 3.9% |
| LOAD_GLOBAL_MODULE | 600 | 0.1% |
| LOAD_ATTR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 662,037 | 98.2% |
| TO_BOOL_BOOL | 12,160 | 1.8% |
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
| RESUME_CHECK | 2,479,715 | 49.1% |
| LOAD_FAST | 776,225 | 15.4% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.4% |
| STORE_FAST | 475,683 | 9.4% |
| NOP | 461,985 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,516,629 | 49.8% |
| LOAD_DEREF | 1,125,230 | 22.3% |
| CALL_ISINSTANCE | 752,785 | 14.9% |
| LOAD_GLOBAL_BUILTIN | 523,960 | 10.4% |
| LOAD_GLOBAL_MODULE | 43,000 | 0.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,660,262 | 24.7% |
| RESUME_CHECK | 1,949,035 | 18.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,291,566 | 12.0% |
| NOP | 1,165,836 | 10.8% |
| POP_JUMP_IF_FALSE | 967,022 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,374,617 | 22.1% |
| LOAD_FAST_LOAD_FAST | 1,678,683 | 15.6% |
| LOAD_ATTR_MODULE | 1,604,937 | 14.9% |
| LOAD_FAST | 1,427,482 | 13.3% |
| COMPARE_OP_STR | 1,264,424 | 11.8% |


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
| LOAD_FAST | 1,070,070 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 748,645 | 69.9% |
| CALL_PY_EXACT_ARGS | 316,145 | 29.5% |
| LOAD_FAST | 5,440 | 0.5% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 10,582,597 | 36.1% |
| CALL_PY_EXACT_ARGS | 8,129,513 | 27.7% |
| FOR_ITER_GEN | 5,983,920 | 20.4% |
| CALL_PY_WITH_DEFAULTS | 1,316,760 | 4.5% |
| COPY_FREE_VARS | 1,131,050 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,745,215 | 57.0% |
| POP_TOP | 6,528,880 | 22.2% |
| LOAD_GLOBAL_BUILTIN | 2,479,715 | 8.4% |
| LOAD_GLOBAL_MODULE | 1,949,035 | 6.6% |
| NOP | 929,345 | 3.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,286,057 | 66.7% |
| LOAD_FAST_LOAD_FAST | 562,245 | 16.4% |
| SWAP | 541,626 | 15.8% |
| LOAD_ATTR_INSTANCE_VALUE | 16,080 | 0.5% |
| STORE_FAST_LOAD_FAST | 12,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,466,460 | 42.8% |
| LOAD_FAST | 880,106 | 25.7% |
| LOAD_GLOBAL_MODULE | 542,285 | 15.8% |
| LOAD_CONST | 289,418 | 8.4% |
| LOAD_FAST_LOAD_FAST | 121,160 | 3.5% |


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
| LOAD_ATTR | 736,205 | 89.6% |
| LOAD_FAST | 41,465 | 5.0% |
| LOAD_ATTR_INSTANCE_VALUE | 32,760 | 4.0% |
| CALL | 10,200 | 1.2% |
| LOAD_CONST | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 739,010 | 90.0% |
| RETURN_CONST | 29,000 | 3.5% |
| LOAD_GLOBAL_MODULE | 26,760 | 3.3% |
| LOAD_CONST | 26,520 | 3.2% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 62.1% |
| COPY | 131 | 29.0% |
| TO_BOOL | 40 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 300 | 66.5% |
| POP_JUMP_IF_FALSE | 151 | 33.5% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,162,516 | 22.8% |
| CALL_ISINSTANCE | 753,065 | 14.8% |
| CALL | 682,336 | 13.4% |
| LOAD_FAST | 668,326 | 13.1% |
| RETURN_CONST | 640,370 | 12.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,414,188 | 67.1% |
| POP_JUMP_IF_TRUE | 1,507,769 | 29.6% |
| UNARY_NOT | 165,817 | 3.3% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,804,094 | 55.1% |
| BINARY_OP | 736,345 | 22.5% |
| LOAD_FAST | 736,205 | 22.5% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,277,024 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 327,005 | 89.2% |
| LOAD_ATTR_INSTANCE_VALUE | 39,240 | 10.7% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 366,305 | 100.0% |
| POP_JUMP_IF_TRUE | 160 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180,005 | 79.9% |
| LOAD_FAST | 26,940 | 12.0% |
| COPY | 11,960 | 5.3% |
| WITH_EXCEPT_START | 5,360 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 207,765 | 92.2% |
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
| CALL_BUILTIN_FAST | 48,189 | 4.4% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,056,220 | 95.6% |
| STORE_FAST | 48,229 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 549,280 | 31.9% |
| LOAD_FAST_CHECK | 543,920 | 31.6% |
| FOR_ITER_LIST | 331,824 | 19.3% |
| CALL_BUILTIN_FAST | 281,331 | 16.4% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,714,135 | 99.6% |
| LOAD_FAST | 6,040 | 0.4% |
| STORE_DEREF | 20 | 0.0% |


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
|     deferred | 4,457,981 | 71.9% |
|          hit | 1,733,425 | 28.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 600 | 9.5% |
| Failure | 5,714 | 90.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 2,829 | 49.5% |
| or | 1,485 | 26.0% |
| remainder | 720 | 12.6% |
| add different types | 600 | 10.5% |
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
|     deferred | 590,566 | 69.4% |
|          hit | 259,120 | 30.5% |

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
|     deferred | 8,783,289 | 31.2% |
|          hit | 19,328,192 | 68.6% |
|         miss | 7,520 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,286 | 24.9% |
| Failure | 27,994 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,286 | 26.0% |
| cfunc noargs | 5,804 | 20.7% |
| class no vectorcall | 3,780 | 13.5% |
| meth descr varargs keywords | 3,059 | 10.9% |
| class mutable | 1,142 | 4.1% |
| other | 1,100 | 3.9% |
| bound method | 1,041 | 3.7% |
| cfunc varargs | 1,020 | 3.6% |
| meth descr method fastcall keywords | 860 | 3.1% |
| cfunc varargs keywords | 802 | 2.9% |
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
|     deferred | 369,808 | 8.4% |
|          hit | 4,036,401 | 91.4% |
|         miss | 7,565 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,634 | 54.4% |
| Failure | 1,370 | 45.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 765 | 55.8% |
| big int | 340 | 24.8% |
| different types | 265 | 19.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,220,380 | 11.9% |
|          hit | 9,061,066 | 88.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 620 | 27.7% |
| Failure | 1,620 | 72.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 500 | 30.9% |
| enumerate | 500 | 30.9% |
| itertools | 380 | 23.5% |
| callable | 240 | 14.8% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,757,722 | 15.9% |
|          hit | 35,327,013 | 83.2% |
|         miss | 309,608 | 0.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,430 | 54.7% |
| Failure | 18,560 | 45.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,319 | 23.3% |
| shadowed | 3,926 | 21.2% |
| not managed dict | 3,308 | 17.8% |
| non overriding descriptor | 1,988 | 10.7% |
| has managed dict | 1,060 | 5.7% |
| class attr descriptor | 940 | 5.1% |
| metaclass attribute | 900 | 4.8% |
| class method obj | 840 | 4.5% |
| non object slot | 520 | 2.8% |
| class attr simple | 439 | 2.4% |
| mutable class | 260 | 1.4% |
| overridden | 60 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,387 | 0.1% |
|        deopt | 100 | 0.0% |
|          hit | 15,801,714 | 99.9% |
|         miss | 2,309 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,569 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 1,125,230 | 100.0% |

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
|     deferred | 83,922 | 2.3% |
|          hit | 3,243,549 | 90.5% |
|         miss | 245,260 | 6.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,981 | 79.2% |
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
|     deferred | 28,100 | 3.3% |
|          hit | 821,490 | 96.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 29.5% |
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
|     deferred | 1,409,076 | 13.6% |
|          hit | 8,958,459 | 86.4% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,004 | 46.6% |
| Failure | 3,441 | 53.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,001 | 29.1% |
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
|          hit | 2,824,644 | 100.0% |

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
| Basic | 240,318,458 | 57.6% |
| Not specialized | 44,468,346 | 10.7% |
| Specialized hits | 131,807,276 | 31.6% |
| Specialized misses | 572,544 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,783,289 | 37.0% |
| LOAD_ATTR | 6,757,722 | 28.5% |
| BINARY_OP | 4,457,981 | 18.8% |
| TO_BOOL | 1,409,076 | 5.9% |
| FOR_ITER | 1,220,380 | 5.1% |
| BINARY_SUBSCR | 590,566 | 2.5% |
| COMPARE_OP | 369,808 | 1.6% |
| STORE_ATTR | 83,922 | 0.4% |
| STORE_SUBSCR | 28,100 | 0.1% |
| LOAD_GLOBAL | 8,387 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 245,260 | 42.8% |
| LOAD_ATTR_INSTANCE_VALUE | 214,090 | 37.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,038 | 14.3% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.2% |
| COMPARE_OP_INT | 7,545 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,060 | 1.1% |
| LOAD_GLOBAL_MODULE | 1,969 | 0.3% |
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
| Calls to PyEval_EvalDefault | 10,664,497 | 36.3% |
| Calls to Python functions inlined | 18,711,023 | 63.7% |
| Calls via PyEval_EvalFrame (total) | 10,664,497 | 36.3% |
| Calls via PyEval_EvalFrame (vector) | 10,112,977 | 34.4% |
| Calls via PyEval_EvalFrame (generator) | 551,520 | 1.9% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 10,112,277 | 34.4% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 589,440 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 534,060 | 1.8% |
| Calls via PyEval_EvalFrame (api) | 443,474 | 1.5% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 36,262 | 0.1% |
| Frames pushed | 12,709,958 | 43.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,727,208 | 41.0% |
| Frees to freelist | 14,739,229 |  |
| Allocations | 21,188,339 | 59.0% |
| Allocations to 512 bytes | 21,005,224 | 58.5% |
| Allocations to 4 kbytes | 83,597 | 0.2% |
| Allocations over 4 kbytes | 99,518 | 0.3% |
| Frees | 22,121,335 |  |
| New values | 80,340 |  |
| Interpreter increfs | 182,557,138 | 78.5% |
| Interpreter decrefs | 198,493,824 | 74.9% |
| Increfs | 49,871,237 | 21.5% |
| Decrefs | 66,592,448 | 25.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 8,170,482 |  |
| Method cache misses | 33,872 |  |
| Method cache collisions | 71,077 |  |
| Method cache dunder hits | 9,244,459 |  |
| Method cache dunder misses | 40,897 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 26 | 390 | 191,686 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 5,457 |  |
| Traces created | 657 | 12.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 4,800 | 88.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 8,899,790 |  |
| Uops executed | 66,380,076 | 7.46 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 140 | 21.3% |
| <= 32 | 280 | 42.6% |
| <= 64 | 80 | 12.2% |
| <= 128 | 137 | 20.9% |
| <= 256 | 20 | 3.0% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 80 | 12.2% |
| <= 8 | 60 | 9.1% |
| <= 16 | 240 | 36.5% |
| <= 32 | 100 | 15.2% |
| <= 64 | 57 | 8.7% |
| <= 128 | 120 | 18.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 1,341,299 | 15.1% |
| <= 4 | 1,197,339 | 13.5% |
| <= 8 | 4,895,894 | 55.0% |
| <= 16 | 842,873 | 9.5% |
| <= 32 | 441,213 | 5.0% |
| <= 64 | 5,390 | 0.1% |
| <= 128 | 175,746 | 2.0% |
| <= 256 | 2 | 0.0% |
| <= 512 | 2 | 0.0% |
| <= 1,024 | 1 | 0.0% |
| <= 2,048 | 4 | 0.0% |
| <= 4,096 | 7 | 0.0% |
| <= 8,192 | 20 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 11,169,139 | 16.8% | 16.8% |  |
| _EXIT_TRACE | 7,382,529 | 11.1% | 27.9% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 6,816,324 | 10.3% | 38.2% | 19.7% |
| _ITER_CHECK_LIST | 6,816,324 | 10.3% | 48.5% |  |
| STORE_FAST | 6,221,251 | 9.4% | 57.9% |  |
| _ITER_NEXT_LIST | 5,471,072 | 8.2% | 66.1% |  |
| _SET_IP | 2,536,339 | 3.8% | 69.9% |  |
| _GUARD_GLOBALS_VERSION | 2,240,003 | 3.4% | 73.3% |  |
| _CHECK_VALIDITY | 2,085,306 | 3.1% | 76.4% |  |
| PUSH_NULL | 1,613,929 | 2.4% | 78.9% |  |
| _GUARD_BUILTINS_VERSION | 1,124,692 | 1.7% | 80.6% |  |
| _LOAD_GLOBAL_BUILTINS | 1,124,692 | 1.7% | 82.3% |  |
| _LOAD_GLOBAL_MODULE | 1,115,311 | 1.7% | 83.9% |  |
| _CHECK_ATTR_MODULE | 963,789 | 1.5% | 85.4% |  |
| _LOAD_ATTR_MODULE | 963,789 | 1.5% | 86.8% |  |
| _GUARD_TYPE_VERSION | 594,542 | 0.9% | 87.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 525,506 | 0.8% | 88.5% |  |
| _GUARD_KEYS_VERSION | 525,506 | 0.8% | 89.3% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 525,506 | 0.8% | 90.1% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 468,159 | 0.7% | 90.8% | 34.1% |
| _ITER_CHECK_RANGE | 468,159 | 0.7% | 91.5% |  |
| LOAD_CONST | 432,255 | 0.7% | 92.2% |  |
| _CHECK_PEP_523 | 388,498 | 0.6% | 92.8% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 388,498 | 0.6% | 93.3% |  |
| _CHECK_STACK_SPACE | 388,498 | 0.6% | 93.9% |  |
| _INIT_CALL_PY_EXACT_ARGS | 388,498 | 0.6% | 94.5% |  |
| _PUSH_FRAME | 388,498 | 0.6% | 95.1% |  |
| _SAVE_RETURN_OFFSET | 388,498 | 0.6% | 95.7% |  |
| RESUME_CHECK | 388,458 | 0.6% | 96.3% |  |
| _LOAD_ATTR | 319,786 | 0.5% | 96.8% |  |
| _ITER_NEXT_RANGE | 308,346 | 0.5% | 97.2% |  |
| BINARY_SUBSCR_LIST_INT | 293,546 | 0.4% | 97.7% |  |
| CALL_BUILTIN_CLASS | 287,786 | 0.4% | 98.1% |  |
| TO_BOOL_BOOL | 181,582 | 0.3% | 98.4% |  |
| _GUARD_IS_TRUE_POP | 175,094 | 0.3% | 98.6% | 0.0% |
| CALL_BUILTIN_FAST | 149,653 | 0.2% | 98.9% |  |
| GET_ITER | 143,933 | 0.2% | 99.1% |  |
| CALL_LEN | 143,893 | 0.2% | 99.3% |  |
| POP_TOP | 81,397 | 0.1% | 99.4% |  |
| _POP_FRAME | 63,769 | 0.1% | 99.5% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 56,130 | 0.1% | 99.6% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 56,130 | 0.1% | 99.7% |  |
| _GUARD_IS_NOT_NONE_POP | 31,980 | 0.0% | 99.7% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.8% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 31,840 | 0.0% | 99.8% |  |
| _JUMP_TO_TOP | 23,531 | 0.0% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 13,800 | 0.0% | 99.9% | 88.0% |
| _ITER_CHECK_TUPLE | 13,800 | 0.0% | 99.9% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 10,652 | 0.0% | 99.9% |  |
| _GUARD_IS_FALSE_POP | 10,111 | 0.0% | 99.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 5,440 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 5,200 | 0.0% | 99.9% |  |
| BEFORE_WITH | 4,974 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 4,960 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,394 | 0.0% | 100.0% |  |
| CONTAINS_OP | 2,254 | 0.0% | 100.0% |  |
| COPY | 2,254 | 0.0% | 100.0% |  |
| SWAP | 2,254 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 2,254 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 2,254 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 2,254 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 2,254 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 2,254 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 1,660 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,140 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 1,140 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 460 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 420 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 420 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 280 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 140 | 0.0% | 100.0% |  |
| IS_OP | 89 | 0.0% | 100.0% |  |
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
| FOR_ITER_GEN | 3,400 |
| FOR_ITER | 1,400 |
| CALL | 180 |
| LOAD_ATTR_PROPERTY | 119 |
| CALL_PY_WITH_DEFAULTS | 80 |
| YIELD_VALUE | 60 |
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
Stats gathered on: 2023-11-18
