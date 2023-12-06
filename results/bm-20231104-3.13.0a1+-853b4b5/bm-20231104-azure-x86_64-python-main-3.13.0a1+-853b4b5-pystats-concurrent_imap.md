
# Pystats results

- benchmark: concurrent_imap
- fork: python
- ref: main
- commit hash: 853b4b5
- commit date: 2023-11-04T23:05:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 68,998,993 | 16.8% | 16.8% |  |
| RESUME_CHECK | 27,787,616 | 6.8% | 23.6% | 0.0% |
| STORE_FAST | 22,012,100 | 5.4% | 29.0% |  |
| POP_TOP | 18,438,501 | 4.5% | 33.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,215,838 | 4.4% | 37.9% | 1.2% |
| JUMP_BACKWARD | 15,774,518 | 3.8% | 41.8% |  |
| RETURN_VALUE | 15,708,974 | 3.8% | 45.6% |  |
| POP_JUMP_IF_FALSE | 12,358,660 | 3.0% | 48.6% |  |
| LOAD_CONST | 12,094,017 | 2.9% | 51.6% |  |
| LOAD_GLOBAL_MODULE | 10,386,518 | 2.5% | 54.1% | 0.0% |
| INTERPRETER_EXIT | 10,352,026 | 2.5% | 56.6% |  |
| LOAD_FAST_LOAD_FAST | 10,092,607 | 2.5% | 59.1% |  |
| CALL | 8,345,724 | 2.0% | 61.1% |  |
| FOR_ITER_LIST | 7,901,887 | 1.9% | 63.0% |  |
| CALL_PY_EXACT_ARGS | 7,385,866 | 1.8% | 64.8% | 0.0% |
| NOP | 7,093,602 | 1.7% | 66.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,921,168 | 1.7% | 68.3% | 1.2% |
| YIELD_VALUE | 6,529,020 | 1.6% | 69.8% |  |
| LOAD_ATTR | 6,226,795 | 1.5% | 71.4% |  |
| PUSH_NULL | 6,196,983 | 1.5% | 72.9% |  |
| RETURN_CONST | 6,135,772 | 1.5% | 74.4% |  |
| STORE_FAST_LOAD_FAST | 6,095,540 | 1.5% | 75.9% |  |
| FOR_ITER_GEN | 5,994,800 | 1.5% | 77.3% |  |
| COPY | 5,744,743 | 1.4% | 78.7% |  |
| LOAD_GLOBAL_BUILTIN | 5,452,357 | 1.3% | 80.1% | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 4,883,558 | 1.2% | 81.2% |  |
| TO_BOOL_BOOL | 4,795,239 | 1.2% | 82.4% |  |
| STORE_FAST_STORE_FAST | 4,233,004 | 1.0% | 83.4% |  |
| BINARY_OP | 3,654,799 | 0.9% | 84.3% |  |
| POP_JUMP_IF_NOT_NONE | 3,533,086 | 0.9% | 85.2% |  |
| BUILD_TUPLE | 3,492,411 | 0.9% | 86.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,149,858 | 0.8% | 86.8% | 7.8% |
| TO_BOOL_INT | 2,663,210 | 0.6% | 87.5% |  |
| COMPARE_OP_INT | 2,525,636 | 0.6% | 88.1% | 0.2% |
| LOAD_ATTR_MODULE | 2,320,985 | 0.6% | 88.6% | 0.0% |
| CALL_FUNCTION_EX | 2,308,024 | 0.6% | 89.2% |  |
| POP_JUMP_IF_TRUE | 2,209,324 | 0.5% | 89.8% |  |
| CALL_PY_WITH_DEFAULTS | 1,830,452 | 0.4% | 90.2% |  |
| SWAP | 1,650,756 | 0.4% | 90.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,609,084 | 0.4% | 91.0% |  |
| BEFORE_WITH | 1,547,905 | 0.4% | 91.4% |  |
| GET_ITER | 1,529,433 | 0.4% | 91.7% |  |
| BUILD_MAP | 1,403,847 | 0.3% | 92.1% |  |
| TO_BOOL | 1,388,136 | 0.3% | 92.4% |  |
| CALL_BUILTIN_CLASS | 1,312,209 | 0.3% | 92.7% |  |
| COMPARE_OP_STR | 1,295,561 | 0.3% | 93.1% |  |
| FOR_ITER | 1,222,620 | 0.3% | 93.4% |  |
| JUMP_FORWARD | 1,171,285 | 0.3% | 93.6% |  |
| CONTAINS_OP | 1,141,944 | 0.3% | 93.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,118,728 | 0.3% | 94.2% |  |
| UNPACK_SEQUENCE_TUPLE | 1,104,451 | 0.3% | 94.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,099,451 | 0.3% | 94.7% | 0.0% |
| BINARY_OP_ADD_INT | 1,078,523 | 0.3% | 95.0% |  |
| CALL_BUILTIN_FAST | 1,067,673 | 0.3% | 95.3% |  |
| LOAD_DEREF | 984,771 | 0.2% | 95.5% |  |
| COPY_FREE_VARS | 936,311 | 0.2% | 95.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 908,278 | 0.2% | 95.9% |  |
| LOAD_SUPER_ATTR_METHOD | 874,871 | 0.2% | 96.2% |  |
| UNARY_INVERT | 872,738 | 0.2% | 96.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 862,576 | 0.2% | 96.6% | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 832,567 | 0.2% | 96.8% | 0.0% |
| BUILD_LIST | 817,017 | 0.2% | 97.0% |  |
| POP_JUMP_IF_NONE | 729,132 | 0.2% | 97.2% |  |
| LOAD_FAST_CHECK | 683,104 | 0.2% | 97.3% |  |
| STORE_SUBSCR_DICT | 681,249 | 0.2% | 97.5% |  |
| CALL_ISINSTANCE | 613,724 | 0.1% | 97.6% |  |
| BINARY_SUBSCR | 591,493 | 0.1% | 97.8% |  |
| EXIT_INIT_CHECK | 585,714 | 0.1% | 97.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 585,714 | 0.1% | 98.1% |  |
| LOAD_ATTR_PROPERTY | 562,811 | 0.1% | 98.2% | 2.2% |
| DICT_MERGE | 561,380 | 0.1% | 98.3% |  |
| CALL_TUPLE_1 | 550,160 | 0.1% | 98.5% |  |
| LIST_APPEND | 461,545 | 0.1% | 98.6% |  |
| FOR_ITER_RANGE | 415,715 | 0.1% | 98.7% |  |
| LOAD_FAST_AND_CLEAR | 411,030 | 0.1% | 98.8% |  |
| CALL_LEN | 373,723 | 0.1% | 98.9% |  |
| COMPARE_OP | 316,052 | 0.1% | 99.0% |  |
| TO_BOOL_LIST | 310,727 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 255,112 | 0.1% | 99.1% |  |
| LIST_EXTEND | 244,992 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 242,504 | 0.1% | 99.2% |  |
| CALL_KW | 227,112 | 0.1% | 99.3% |  |
| TO_BOOL_NONE | 225,249 | 0.1% | 99.3% | 0.1% |
| BINARY_OP_SUBTRACT_INT | 214,516 | 0.1% | 99.4% |  |
| CALL_LIST_APPEND | 149,207 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 138,271 | 0.0% | 99.5% |  |
| UNARY_NOT | 137,940 | 0.0% | 99.5% |  |
| CALL_BUILTIN_O | 136,160 | 0.0% | 99.5% |  |
| MAKE_CELL | 133,100 | 0.0% | 99.6% |  |
| STORE_DEREF | 132,860 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_FLOAT | 122,440 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 109,120 | 0.0% | 99.6% |  |
| BINARY_OP_MULTIPLY_FLOAT | 97,240 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 97,240 | 0.0% | 99.7% |  |
| STORE_ATTR | 95,252 | 0.0% | 99.7% |  |
| DELETE_ATTR | 81,582 | 0.0% | 99.7% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 76,689 | 0.0% | 99.8% | 7.9% |
| DELETE_SUBSCR | 75,008 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 61,820 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 61,820 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 59,840 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 58,431 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 50,880 | 0.0% | 99.9% |  |
| IS_OP | 44,281 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 42,060 | 0.0% | 99.9% |  |
| BUILD_STRING | 38,720 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 38,080 | 0.0% | 99.9% |  |
| POP_EXCEPT | 35,994 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 35,994 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 35,320 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 30,554 | 0.0% | 99.9% |  |
| IMPORT_NAME | 30,240 | 0.0% | 99.9% |  |
| IMPORT_FROM | 29,900 | 0.0% | 99.9% |  |
| STORE_SUBSCR | 28,972 | 0.0% | 99.9% |  |
| FOR_ITER_TUPLE | 27,020 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 26,520 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 24,320 | 0.0% | 100.0% |  |
| BINARY_SLICE | 18,220 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 17,840 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 17,300 | 0.0% | 100.0% |  |
| RERAISE | 16,320 | 0.0% | 100.0% |  |
| CALL_STR_1 | 11,260 | 0.0% | 100.0% |  |
| END_FOR | 10,880 | 0.0% | 100.0% |  |
| STORE_NAME | 7,480 | 0.0% | 100.0% |  |
| RESUME | 5,980 | 0.0% | 100.0% | 0.1% |
| RAISE_VARARGS | 5,460 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 5,440 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 2,800 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 2,560 | 0.0% | 100.0% |  |
| LOAD_NAME | 2,200 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 800 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 560 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 520 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 481 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 280 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 160 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 140 | 0.0% | 100.0% | 14.3% |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,727,704 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_FAST | 15,786,088 | 3.8% | 7.9% |
| CACHE RESUME_CHECK | 10,275,592 | 2.5% | 10.4% |
| RETURN_VALUE INTERPRETER_EXIT | 9,208,957 | 2.2% | 12.7% |
| STORE_FAST LOAD_FAST | 8,481,698 | 2.1% | 14.7% |
| LOAD_FAST RETURN_VALUE | 8,279,944 | 2.0% | 16.8% |
| POP_TOP JUMP_BACKWARD | 7,709,239 | 1.9% | 18.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,341,826 | 1.8% | 20.4% |
| JUMP_BACKWARD FOR_ITER_LIST | 6,569,970 | 1.6% | 22.0% |
| RESUME_CHECK POP_TOP | 6,528,880 | 1.6% | 23.6% |
| JUMP_BACKWARD FOR_ITER_GEN | 5,983,920 | 1.5% | 25.1% |
| YIELD_VALUE STORE_FAST | 5,983,920 | 1.5% | 26.6% |
| FOR_ITER_GEN RESUME_CHECK | 5,983,920 | 1.5% | 28.0% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 5,440,060 | 1.3% | 29.3% |
| STORE_FAST JUMP_BACKWARD | 5,440,000 | 1.3% | 30.7% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 5,440,000 | 1.3% | 32.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,223,650 | 1.3% | 33.3% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,687,036 | 1.1% | 34.4% |
| POP_TOP LOAD_FAST | 4,666,384 | 1.1% | 35.5% |
| NOP LOAD_FAST | 4,653,351 | 1.1% | 36.7% |
| LOAD_FAST LOAD_ATTR | 4,381,021 | 1.1% | 37.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,303,342 | 1.0% | 38.8% |
| RETURN_CONST POP_TOP | 4,227,415 | 1.0% | 39.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 3,421,585 | 0.8% | 40.7% |
| LOAD_FAST PUSH_NULL | 3,317,184 | 0.8% | 41.5% |
| LOAD_CONST LOAD_CONST | 3,194,266 | 0.8% | 42.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,173,733 | 0.8% | 43.0% |
| PUSH_NULL LOAD_FAST | 2,927,472 | 0.7% | 43.7% |
| STORE_FAST NOP | 2,781,784 | 0.7% | 44.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,758,341 | 0.7% | 45.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,736,466 | 0.7% | 45.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,663,070 | 0.6% | 46.4% |
| COPY STORE_FAST | 2,597,760 | 0.6% | 47.0% |
| STORE_FAST COPY | 2,597,440 | 0.6% | 47.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,527,277 | 0.6% | 48.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,523,266 | 0.6% | 48.9% |
| LOAD_FAST LOAD_CONST | 2,508,767 | 0.6% | 49.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,475,156 | 0.6% | 50.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,317,750 | 0.6% | 50.7% |
| LOAD_CONST CALL | 2,246,511 | 0.5% | 51.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,205,629 | 0.5% | 51.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,144,795 | 0.5% | 52.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,128,467 | 0.5% | 52.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,120,456 | 0.5% | 53.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,062,548 | 0.5% | 53.8% |
| CALL STORE_FAST | 1,933,099 | 0.5% | 54.3% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,928,119 | 0.5% | 54.8% |
| LOAD_ATTR LOAD_FAST | 1,857,724 | 0.5% | 55.2% |
| CALL POP_TOP | 1,832,264 | 0.4% | 55.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,813,739 | 0.4% | 56.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,811,931 | 0.4% | 56.6% |
| CALL RETURN_VALUE | 1,798,924 | 0.4% | 57.0% |
| LOAD_FAST CALL_FUNCTION_EX | 1,746,624 | 0.4% | 57.4% |
| PUSH_NULL CALL | 1,671,135 | 0.4% | 57.8% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,634,125 | 0.4% | 58.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,603,481 | 0.4% | 58.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,602,984 | 0.4% | 59.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,578,490 | 0.4% | 59.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,500,362 | 0.4% | 59.8% |
| POP_TOP RETURN_CONST | 1,493,925 | 0.4% | 60.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,483,606 | 0.4% | 60.5% |
| BINARY_OP COPY | 1,469,502 | 0.4% | 60.9% |
| COPY TO_BOOL_INT | 1,469,182 | 0.4% | 61.2% |
| POP_TOP LOAD_CONST | 1,466,141 | 0.4% | 61.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,376,884 | 0.3% | 61.9% |
| LOAD_CONST LOAD_FAST | 1,359,593 | 0.3% | 62.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,332,254 | 0.3% | 62.6% |
| LOAD_FAST TO_BOOL | 1,330,359 | 0.3% | 62.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,329,502 | 0.3% | 63.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,317,540 | 0.3% | 63.5% |
| BEFORE_WITH POP_TOP | 1,281,978 | 0.3% | 63.8% |
| LOAD_FAST_LOAD_FAST CALL | 1,266,431 | 0.3% | 64.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,263,747 | 0.3% | 64.5% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,260,796 | 0.3% | 64.8% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,256,562 | 0.3% | 65.1% |
| RETURN_VALUE STORE_FAST | 1,252,729 | 0.3% | 65.4% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,242,948 | 0.3% | 65.7% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,236,486 | 0.3% | 66.0% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,233,688 | 0.3% | 66.3% |
| LOAD_ATTR PUSH_NULL | 1,211,709 | 0.3% | 66.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,204,642 | 0.3% | 66.9% |
| CALL_FUNCTION_EX RETURN_VALUE | 1,196,044 | 0.3% | 67.2% |
| JUMP_BACKWARD FOR_ITER | 1,191,545 | 0.3% | 67.5% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 1,184,904 | 0.3% | 67.7% |
| LOAD_FAST BUILD_TUPLE | 1,159,484 | 0.3% | 68.0% |
| LOAD_CONST COMPARE_OP_INT | 1,143,780 | 0.3% | 68.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,141,324 | 0.3% | 68.6% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,140,667 | 0.3% | 68.9% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,094,720 | 0.3% | 69.1% |
| BUILD_TUPLE YIELD_VALUE | 1,088,100 | 0.3% | 69.4% |
| GET_ITER FOR_ITER_LIST | 1,071,614 | 0.3% | 69.7% |
| LOAD_CONST COPY | 1,067,520 | 0.3% | 69.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,061,488 | 0.3% | 70.2% |
| COPY STORE_FAST_STORE_FAST | 1,061,440 | 0.3% | 70.4% |
| POP_TOP NOP | 1,057,330 | 0.3% | 70.7% |
| STORE_FAST_STORE_FAST STORE_FAST | 1,056,280 | 0.3% | 70.9% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,056,220 | 0.3% | 71.2% |
| JUMP_BACKWARD NOP | 1,056,000 | 0.3% | 71.5% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 1,055,880 | 0.3% | 71.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,052,973 | 0.3% | 72.0% |


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
| RESUME_CHECK | 10,275,592 | 99.2% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,184,904 | 76.5% |
| RETURN_VALUE | 260,587 | 16.8% |
| LOAD_GLOBAL_MODULE | 79,554 | 5.1% |
| LOAD_FAST | 16,320 | 1.1% |
| CALL | 6,040 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,281,978 | 82.8% |
| STORE_FAST | 265,927 | 17.2% |


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
| LOAD_CONST | 46,494 | 7.9% |
| BINARY_SUBSCR | 839 | 0.1% |
| CALL | 40 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 543,920 | 92.0% |
| STORE_FAST | 46,214 | 7.8% |
| BINARY_SUBSCR | 839 | 0.1% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,394 | 83.1% |
| LOAD_ATTR_MODULE | 5,100 | 16.7% |
| LOAD_GLOBAL | 40 | 0.1% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,554 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,934 | 49.2% |
| CALL | 26,554 | 35.4% |
| LOAD_ATTR_INSTANCE_VALUE | 11,440 | 15.3% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,554 | 78.1% |
| RETURN_CONST | 10,234 | 13.6% |
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
| RETURN_CONST | 585,714 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 585,714 | 100.0% |


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
| LOAD_FAST | 810,157 | 53.0% |
| STORE_FAST_LOAD_FAST | 544,000 | 35.6% |
| CALL_BUILTIN_CLASS | 150,936 | 9.9% |
| CALL | 12,420 | 0.8% |
| RETURN_VALUE | 5,440 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,071,614 | 70.1% |
| LOAD_FAST_AND_CLEAR | 273,043 | 17.9% |
| FOR_ITER_RANGE | 144,981 | 9.5% |
| FOR_ITER | 11,475 | 0.8% |
| FOR_ITER_TUPLE | 11,100 | 0.7% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,208,957 | 89.0% |
| RETURN_CONST | 597,969 | 5.8% |
| YIELD_VALUE | 545,100 | 5.3% |


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
| LOAD_CONST | 59,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 38,080 | 63.6% |
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
| STORE_FAST | 2,781,784 | 39.2% |
| POP_TOP | 1,057,330 | 14.9% |
| JUMP_BACKWARD | 1,056,000 | 14.9% |
| POP_JUMP_IF_FALSE | 953,560 | 13.4% |
| RESUME_CHECK | 789,824 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,653,351 | 65.6% |
| LOAD_GLOBAL_MODULE | 971,005 | 13.7% |
| LOAD_FAST_LOAD_FAST | 550,360 | 7.8% |
| LOAD_CONST | 529,060 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 378,226 | 5.3% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 19,614 | 54.5% |
| COPY | 10,880 | 30.2% |
| POP_TOP | 5,200 | 14.4% |
| STORE_FAST | 280 | 0.8% |
| STORE_SUBSCR_DICT | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 19,914 | 55.3% |
| RERAISE | 10,880 | 30.2% |
| JUMP_FORWARD | 5,120 | 14.2% |
| RETURN_CONST | 60 | 0.2% |
| LOAD_FAST | 20 | 0.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,528,880 | 35.4% |
| RETURN_CONST | 4,227,415 | 22.9% |
| CALL | 1,832,264 | 9.9% |
| BEFORE_WITH | 1,281,978 | 7.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,049,100 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,709,239 | 41.8% |
| LOAD_FAST | 4,666,384 | 25.3% |
| RETURN_CONST | 1,493,925 | 8.1% |
| LOAD_CONST | 1,466,141 | 8.0% |
| NOP | 1,057,330 | 5.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 25,014 | 69.5% |
| RERAISE | 5,440 | 15.1% |
| CALL_KW | 5,120 | 14.2% |
| BINARY_SUBSCR_DICT | 300 | 0.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 25,354 | 70.4% |
| WITH_EXCEPT_START | 5,440 | 15.1% |
| LOAD_GLOBAL_MODULE | 5,080 | 14.1% |
| LOAD_GLOBAL | 120 | 0.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,317,184 | 53.5% |
| LOAD_ATTR_MODULE | 1,578,490 | 25.5% |
| LOAD_ATTR | 1,211,709 | 19.6% |
| LOAD_SUPER_ATTR_ATTR | 54,960 | 0.9% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,927,472 | 47.2% |
| CALL | 1,671,135 | 27.0% |
| LOAD_FAST_LOAD_FAST | 1,256,562 | 20.3% |
| LOAD_CONST | 242,660 | 3.9% |
| CALL_PY_EXACT_ARGS | 44,840 | 0.7% |


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
| LOAD_FAST | 8,279,944 | 52.7% |
| CALL | 1,798,924 | 11.5% |
| CALL_FUNCTION_EX | 1,196,044 | 7.6% |
| RETURN_VALUE | 1,010,085 | 6.4% |
| LOAD_ATTR_INSTANCE_VALUE | 868,770 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,208,957 | 58.6% |
| STORE_FAST | 1,252,729 | 8.0% |
| RETURN_VALUE | 1,010,085 | 6.4% |
| POP_TOP | 786,645 | 5.0% |
| LOAD_FAST_LOAD_FAST | 596,764 | 3.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 12,160 | 42.0% |
| LOAD_FAST | 10,432 | 36.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,480 | 18.9% |
| STORE_SUBSCR | 620 | 2.1% |
| LOAD_ATTR | 200 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 17,720 | 61.2% |
| LOAD_GLOBAL_MODULE | 10,200 | 35.2% |
| STORE_SUBSCR | 620 | 2.1% |
| STORE_SUBSCR_DICT | 255 | 0.9% |
| LOAD_GLOBAL | 80 | 0.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,330,359 | 95.8% |
| LOAD_ATTR_INSTANCE_VALUE | 49,968 | 3.6% |
| TO_BOOL | 3,439 | 0.2% |
| LOAD_ATTR | 886 | 0.1% |
| RETURN_VALUE | 764 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 694,053 | 50.0% |
| POP_JUMP_IF_FALSE | 687,603 | 49.5% |
| TO_BOOL | 3,439 | 0.2% |
| TO_BOOL_BOOL | 2,161 | 0.2% |
| TO_BOOL_NONE | 360 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 596,764 | 68.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 275,894 | 31.6% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 872,738 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 137,900 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 137,940 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 1,928,119 | 52.8% |
| UNARY_INVERT | 872,738 | 23.9% |
| POP_JUMP_IF_FALSE | 596,764 | 16.3% |
| LOAD_ATTR | 150,167 | 4.1% |
| LOAD_FAST_LOAD_FAST | 49,920 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,469,502 | 40.2% |
| STORE_FAST | 747,251 | 20.4% |
| TO_BOOL_INT | 596,824 | 16.3% |
| UNARY_INVERT | 596,764 | 16.3% |
| BUILD_TUPLE | 137,987 | 3.8% |


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
| SWAP | 273,043 | 33.4% |
| JUMP_FORWARD | 260,347 | 31.9% |
| LOAD_FAST | 138,331 | 16.9% |
| POP_TOP | 122,036 | 14.9% |
| STORE_ATTR_INSTANCE_VALUE | 10,660 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 276,947 | 33.9% |
| SWAP | 273,043 | 33.4% |
| STORE_FAST | 261,167 | 32.0% |
| RETURN_VALUE | 5,120 | 0.6% |
| COMPARE_OP | 280 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 544,000 | 38.8% |
| LOAD_FAST | 528,600 | 37.7% |
| RESUME_CHECK | 270,547 | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE | 32,560 | 2.3% |
| POP_JUMP_IF_NOT_NONE | 16,320 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 843,507 | 60.1% |
| BUILD_TUPLE | 544,020 | 38.8% |
| STORE_FAST | 16,320 | 1.2% |


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
| LOAD_FAST | 1,159,484 | 33.2% |
| LOAD_FAST_LOAD_FAST | 1,094,720 | 31.3% |
| BUILD_MAP | 544,020 | 15.6% |
| RETURN_VALUE | 512,000 | 14.7% |
| BINARY_OP | 137,987 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 1,088,100 | 31.2% |
| CALL | 597,684 | 17.1% |
| BUILD_MAP | 544,000 | 15.6% |
| STORE_FAST | 512,000 | 14.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 511,960 | 14.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,246,511 | 26.9% |
| PUSH_NULL | 1,671,135 | 20.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,329,502 | 15.9% |
| LOAD_FAST_LOAD_FAST | 1,266,431 | 15.2% |
| BUILD_TUPLE | 597,684 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,933,099 | 23.2% |
| POP_TOP | 1,832,264 | 22.0% |
| RETURN_VALUE | 1,798,924 | 21.6% |
| LOAD_FAST | 692,878 | 8.3% |
| TO_BOOL_BOOL | 682,779 | 8.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,746,624 | 75.7% |
| DICT_MERGE | 561,380 | 24.3% |
| CALL_INTRINSIC_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,196,044 | 51.8% |
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
| LOAD_CONST | 227,112 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 163,876 | 72.2% |
| LOAD_FAST | 27,200 | 12.0% |
| RETURN_VALUE | 18,240 | 8.0% |
| STORE_FAST | 12,300 | 5.4% |
| PUSH_EXC_INFO | 5,120 | 2.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 312,158 | 98.8% |
| COMPARE_OP | 1,193 | 0.4% |
| LOAD_ATTR_INSTANCE_VALUE | 778 | 0.2% |
| LOAD_GLOBAL_MODULE | 375 | 0.1% |
| LOAD_FAST | 300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 312,896 | 99.0% |
| COMPARE_OP | 1,193 | 0.4% |
| COMPARE_OP_INT | 1,169 | 0.4% |
| COMPARE_OP_STR | 435 | 0.1% |
| POP_JUMP_IF_TRUE | 279 | 0.1% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,140,667 | 99.9% |
| LOAD_ATTR_MODULE | 560 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR | 97 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,141,324 | 99.9% |
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
| STORE_FAST | 2,597,440 | 45.2% |
| BINARY_OP | 1,469,502 | 25.6% |
| LOAD_CONST | 1,067,520 | 18.6% |
| LOAD_FAST | 556,180 | 9.7% |
| STORE_ATTR_INSTANCE_VALUE | 18,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,597,760 | 45.2% |
| TO_BOOL_INT | 1,469,182 | 25.6% |
| STORE_FAST_STORE_FAST | 1,061,440 | 18.5% |
| LOAD_ATTR_INSTANCE_VALUE | 543,888 | 9.5% |
| LOAD_FAST | 24,320 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 596,764 | 63.7% |
| CALL_ALLOC_AND_ENTER_INIT | 260,307 | 27.8% |
| CACHE | 73,100 | 7.8% |
| CALL | 5,620 | 0.6% |
| CALL_PY_EXACT_ARGS | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 935,651 | 99.9% |
| RETURN_GENERATOR | 340 | 0.0% |
| RESUME | 320 | 0.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,582 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,388 | 66.7% |
| RETURN_CONST | 26,554 | 32.5% |
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

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,191,545 | 97.5% |
| SWAP | 12,240 | 1.0% |
| GET_ITER | 11,475 | 0.9% |
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
| RETURN_VALUE | 26,560 | 60.0% |
| LOAD_FAST | 16,460 | 37.2% |
| LOAD_GLOBAL_MODULE | 1,221 | 2.8% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,141 | 99.7% |
| POP_JUMP_IF_TRUE | 140 | 0.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,709,239 | 48.9% |
| STORE_FAST | 5,440,000 | 34.5% |
| POP_JUMP_IF_NOT_NONE | 756,812 | 4.8% |
| STORE_FAST_STORE_FAST | 549,440 | 3.5% |
| FOR_ITER_LIST | 544,000 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 6,569,970 | 41.6% |
| FOR_ITER_GEN | 5,983,920 | 37.9% |
| FOR_ITER | 1,191,545 | 7.6% |
| NOP | 1,056,000 | 6.7% |
| LOAD_GLOBAL_BUILTIN | 543,960 | 3.4% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 586,552 | 50.1% |
| STORE_FAST | 567,793 | 48.5% |
| STORE_ATTR_INSTANCE_VALUE | 6,060 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 5,400 | 0.5% |
| POP_EXCEPT | 5,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 851,390 | 72.7% |
| BUILD_LIST | 260,347 | 22.2% |
| LOAD_GLOBAL_MODULE | 22,574 | 1.9% |
| POP_EXCEPT | 19,614 | 1.7% |
| LOAD_FAST_LOAD_FAST | 6,360 | 0.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 224,258 | 48.6% |
| LOAD_ATTR | 138,007 | 29.9% |
| BINARY_SUBSCR_STR_INT | 97,240 | 21.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,000 | 0.4% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 461,545 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,816 | 50.1% |
| RETURN_VALUE | 122,036 | 49.8% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_DEREF | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,356 | 49.9% |
| STORE_FAST | 122,036 | 49.8% |
| RETURN_VALUE | 320 | 0.1% |
| CALL_INTRINSIC_1 | 160 | 0.1% |
| STORE_NAME | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,381,021 | 70.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,500,362 | 24.1% |
| LOAD_GLOBAL_MODULE | 237,671 | 3.8% |
| CALL | 49,620 | 0.8% |
| LOAD_ATTR | 20,912 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,857,724 | 29.8% |
| PUSH_NULL | 1,211,709 | 19.5% |
| POP_JUMP_IF_NOT_NONE | 608,908 | 9.8% |
| STORE_SUBSCR_DICT | 596,684 | 9.6% |
| STORE_FAST | 434,269 | 7.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,194,266 | 26.4% |
| LOAD_FAST | 2,508,767 | 20.7% |
| POP_TOP | 1,466,141 | 12.1% |
| POP_JUMP_IF_FALSE | 764,032 | 6.3% |
| LOAD_ATTR_METHOD_NO_DICT | 688,468 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,194,266 | 26.4% |
| CALL | 2,246,511 | 18.6% |
| LOAD_FAST | 1,359,593 | 11.2% |
| COMPARE_OP_INT | 1,143,780 | 9.5% |
| COPY | 1,067,520 | 8.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 929,831 | 94.4% |
| POP_JUMP_IF_NOT_NONE | 26,560 | 2.7% |
| STORE_DEREF | 26,560 | 2.7% |
| STORE_FAST | 440 | 0.0% |
| POP_JUMP_IF_FALSE | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 930,351 | 94.5% |
| POP_JUMP_IF_NOT_NONE | 53,120 | 5.4% |
| PUSH_NULL | 460 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,786,088 | 22.9% |
| STORE_FAST | 8,481,698 | 12.3% |
| POP_JUMP_IF_FALSE | 5,223,650 | 7.6% |
| POP_TOP | 4,666,384 | 6.8% |
| NOP | 4,653,351 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,727,704 | 24.2% |
| RETURN_VALUE | 8,279,944 | 12.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,687,036 | 6.8% |
| LOAD_ATTR | 4,381,021 | 6.3% |
| PUSH_NULL | 3,317,184 | 4.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 273,043 | 66.4% |
| LOAD_FAST_AND_CLEAR | 137,987 | 33.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 273,043 | 66.4% |
| LOAD_FAST_AND_CLEAR | 137,987 | 33.6% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 544,560 | 79.7% |
| POP_JUMP_IF_NONE | 122,360 | 17.9% |
| LOAD_ATTR_CLASS | 15,864 | 2.3% |
| LOAD_FAST | 140 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 543,920 | 79.6% |
| LOAD_GLOBAL_MODULE | 122,280 | 17.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 15,824 | 2.3% |
| POP_JUMP_IF_NOT_NONE | 560 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,376,884 | 13.6% |
| LOAD_FAST_LOAD_FAST | 1,317,540 | 13.1% |
| PUSH_NULL | 1,256,562 | 12.5% |
| POP_JUMP_IF_FALSE | 780,333 | 7.7% |
| STORE_FAST_STORE_FAST | 769,670 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,128,467 | 21.1% |
| LOAD_FAST_LOAD_FAST | 1,317,540 | 13.1% |
| CALL | 1,266,431 | 12.5% |
| BUILD_TUPLE | 1,094,720 | 10.8% |
| LOAD_ATTR_INSTANCE_VALUE | 901,304 | 8.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,000 | 11.2% |
| RESUME_CHECK | 1,720 | 9.6% |
| POP_JUMP_IF_FALSE | 1,709 | 9.6% |
| LOAD_FAST | 1,600 | 9.0% |
| RESUME | 1,520 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,810 | 38.2% |
| LOAD_ATTR | 3,325 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 2,740 | 15.4% |
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
| TO_BOOL_BOOL | 3,173,733 | 25.7% |
| TO_BOOL_INT | 2,663,070 | 21.5% |
| COMPARE_OP_INT | 2,523,266 | 20.4% |
| COMPARE_OP_STR | 1,260,796 | 10.2% |
| CONTAINS_OP | 1,141,324 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,223,650 | 42.3% |
| RETURN_CONST | 2,205,629 | 17.8% |
| NOP | 953,560 | 7.7% |
| LOAD_GLOBAL_MODULE | 827,506 | 6.7% |
| LOAD_FAST_LOAD_FAST | 780,333 | 6.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 659,012 | 90.4% |
| LOAD_ATTR_INSTANCE_VALUE | 44,600 | 6.1% |
| LOAD_ATTR | 24,460 | 3.4% |
| RETURN_VALUE | 760 | 0.1% |
| LOAD_ATTR_MODULE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 229,755 | 31.5% |
| LOAD_GLOBAL_MODULE | 172,332 | 23.6% |
| NOP | 158,996 | 21.8% |
| LOAD_FAST_CHECK | 122,360 | 16.8% |
| RETURN_CONST | 22,420 | 3.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,120,456 | 60.0% |
| LOAD_ATTR | 608,908 | 17.2% |
| LOAD_ATTR_INSTANCE_VALUE | 504,570 | 14.3% |
| RETURN_VALUE | 224,578 | 6.4% |
| LOAD_DEREF | 53,120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,634,125 | 46.3% |
| JUMP_BACKWARD | 756,812 | 21.4% |
| RETURN_CONST | 609,596 | 17.3% |
| NOP | 267,608 | 7.6% |
| LOAD_CONST | 122,316 | 3.5% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,483,606 | 67.2% |
| TO_BOOL | 694,053 | 31.4% |
| TO_BOOL_NONE | 17,460 | 0.8% |
| COMPARE_OP_STR | 10,525 | 0.5% |
| COMPARE_OP_INT | 1,981 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 909,657 | 41.2% |
| LOAD_FAST_LOAD_FAST | 694,927 | 31.5% |
| RETURN_CONST | 452,026 | 20.5% |
| LOAD_GLOBAL_MODULE | 57,523 | 2.6% |
| RETURN_VALUE | 46,174 | 2.1% |


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
| POP_JUMP_IF_FALSE | 2,205,629 | 35.9% |
| POP_TOP | 1,493,925 | 24.3% |
| STORE_ATTR_INSTANCE_VALUE | 1,242,948 | 20.3% |
| POP_JUMP_IF_NOT_NONE | 609,596 | 9.9% |
| POP_JUMP_IF_TRUE | 452,026 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,227,415 | 68.9% |
| TO_BOOL_BOOL | 640,826 | 10.4% |
| INTERPRETER_EXIT | 597,969 | 9.7% |
| EXIT_INIT_CHECK | 585,714 | 9.5% |
| STORE_FAST | 47,374 | 0.8% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 38,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,960 | 97.1% |
| STORE_NAME | 780 | 2.0% |
| LOAD_GLOBAL_MODULE | 280 | 0.7% |
| LOAD_FAST | 60 | 0.2% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,320 | 59.1% |
| LOAD_FAST_LOAD_FAST | 19,800 | 20.8% |
| LOAD_ATTR_INSTANCE_VALUE | 16,320 | 17.1% |
| STORE_ATTR | 2,360 | 2.5% |
| LOAD_ATTR | 240 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 42,920 | 45.1% |
| LOAD_FAST | 12,977 | 13.6% |
| LOAD_FAST_LOAD_FAST | 12,840 | 13.5% |
| LOAD_CONST | 12,000 | 12.6% |
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
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 0.0% |

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
| YIELD_VALUE | 5,983,920 | 27.2% |
| COPY | 2,597,760 | 11.8% |
| CALL | 1,933,099 | 8.8% |
| RETURN_VALUE | 1,252,729 | 5.7% |
| STORE_FAST_STORE_FAST | 1,056,280 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,481,698 | 38.5% |
| JUMP_BACKWARD | 5,440,000 | 24.7% |
| NOP | 2,781,784 | 12.6% |
| COPY | 2,597,440 | 11.8% |
| LOAD_GLOBAL_BUILTIN | 657,481 | 3.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,440,060 | 89.2% |
| FOR_ITER | 641,320 | 10.5% |
| COPY | 12,160 | 0.2% |
| FOR_ITER_TUPLE | 2,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 5,440,000 | 89.2% |
| GET_ITER | 544,000 | 8.9% |
| LOAD_FAST | 97,280 | 1.6% |
| STORE_ATTR_INSTANCE_VALUE | 12,080 | 0.2% |
| TO_BOOL_STR | 2,000 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,602,984 | 37.9% |
| COPY | 1,061,440 | 25.1% |
| UNPACK_SEQUENCE_TUPLE | 1,056,220 | 25.0% |
| STORE_FAST_STORE_FAST | 512,000 | 12.1% |
| UNPACK_SEQUENCE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,332,254 | 31.5% |
| STORE_FAST | 1,056,280 | 25.0% |
| LOAD_FAST_LOAD_FAST | 769,670 | 18.2% |
| JUMP_BACKWARD | 549,440 | 13.0% |
| STORE_FAST_STORE_FAST | 512,000 | 12.1% |


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
| BINARY_OP_ADD_INT | 543,943 | 33.0% |
| BUILD_LIST | 273,043 | 16.5% |
| LOAD_FAST_AND_CLEAR | 273,043 | 16.5% |
| FOR_ITER_LIST | 260,023 | 15.8% |
| LOAD_FAST | 149,200 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 543,888 | 32.9% |
| LOAD_CONST | 287,187 | 17.4% |
| BUILD_LIST | 273,043 | 16.5% |
| STORE_FAST | 273,043 | 16.5% |
| FOR_ITER_LIST | 259,943 | 15.7% |


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
| STORE_FAST_LOAD_FAST | 5,440,000 | 83.3% |
| BUILD_TUPLE | 1,088,100 | 16.7% |
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
| LOAD_FAST | 138,231 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 138,271 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,061,488 | 98.4% |
| LOAD_FAST_LOAD_FAST | 16,880 | 1.6% |
| BINARY_OP | 155 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 543,943 | 50.4% |
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
| LOAD_FAST_LOAD_FAST | 960 | 37.5% |
| LOAD_CONST | 600 | 23.4% |
| CALL_METHOD_DESCRIPTOR_O | 600 | 23.4% |
| BINARY_SUBSCR_LIST_INT | 280 | 10.9% |
| LOAD_FAST | 80 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,100 | 43.0% |
| LOAD_CONST | 620 | 24.2% |
| CALL | 480 | 18.8% |
| STORE_FAST | 360 | 14.1% |


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
| CALL | 122,280 | 99.9% |
| BINARY_OP | 80 | 0.1% |
| LOAD_FAST | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 122,440 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 162,862 | 75.9% |
| LOAD_CONST | 46,094 | 21.5% |
| CALL_LEN | 5,360 | 2.5% |
| BINARY_OP | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 209,116 | 97.5% |
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
| LOAD_FAST_LOAD_FAST | 243,992 | 95.6% |
| LOAD_CONST | 11,000 | 4.3% |
| BINARY_SUBSCR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 244,032 | 95.7% |
| LOAD_CONST | 10,800 | 4.2% |
| BINARY_OP_ADD_UNICODE | 280 | 0.1% |


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
| LOAD_GLOBAL_MODULE | 286,787 | 49.0% |
| LOAD_FAST | 266,507 | 45.5% |
| CALL | 32,140 | 5.5% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 325,407 | 55.6% |
| COPY_FREE_VARS | 260,307 | 44.4% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 32,294 | 42.1% |
| LOAD_FAST | 32,240 | 42.0% |
| LOAD_CONST | 6,520 | 8.5% |
| BINARY_OP_ADD_INT | 5,360 | 7.0% |
| CALL | 155 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 70,609 | 92.1% |
| POP_TOP | 5,960 | 7.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 120 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 511,960 | 39.0% |
| RETURN_VALUE | 372,406 | 28.4% |
| LOAD_FAST | 154,731 | 11.8% |
| CALL_BUILTIN_CLASS | 121,956 | 9.3% |
| CALL_LEN | 121,956 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 650,251 | 49.6% |
| STORE_FAST | 372,706 | 28.4% |
| GET_ITER | 150,936 | 11.5% |
| CALL_BUILTIN_CLASS | 121,956 | 9.3% |
| LOAD_FAST | 16,320 | 1.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 468,268 | 43.9% |
| LOAD_CONST | 394,912 | 37.0% |
| LOAD_FAST_LOAD_FAST | 107,062 | 10.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,191 | 4.5% |
| LOAD_GLOBAL_MODULE | 24,040 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 387,092 | 36.3% |
| STORE_FAST | 339,589 | 31.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 225,630 | 21.1% |
| UNPACK_SEQUENCE_TUPLE | 48,191 | 4.5% |
| POP_TOP | 12,751 | 1.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 515,940 | 46.9% |
| BUILD_TUPLE | 511,960 | 46.6% |
| CALL | 32,587 | 3.0% |
| LOAD_FAST_CHECK | 15,824 | 1.4% |
| LOAD_ATTR | 12,080 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,049,100 | 95.4% |
| RETURN_VALUE | 49,091 | 4.5% |
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
| LOAD_GLOBAL_BUILTIN | 613,264 | 99.9% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 613,544 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 346,403 | 92.7% |
| LOAD_ATTR_INSTANCE_VALUE | 26,940 | 7.2% |
| CALL | 380 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 207,742 | 55.6% |
| CALL_BUILTIN_CLASS | 121,956 | 32.6% |
| CALL_PY_EXACT_ARGS | 31,880 | 8.5% |
| LOAD_FAST | 5,400 | 1.4% |
| BINARY_OP_SUBTRACT_INT | 5,360 | 1.4% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 137,907 | 92.4% |
| LOAD_FAST | 10,800 | 7.2% |
| LOAD_CONST | 140 | 0.1% |
| LOAD_FAST_CHECK | 140 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 137,947 | 92.5% |
| LOAD_GLOBAL_MODULE | 10,800 | 7.2% |
| NOP | 280 | 0.2% |
| RETURN_CONST | 140 | 0.1% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 857,091 | 99.4% |
| LOAD_GLOBAL_MODULE | 2,280 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,030 | 0.2% |
| LOAD_CONST | 600 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 597,044 | 69.2% |
| STORE_FAST | 262,632 | 30.4% |
| LIST_APPEND | 2,000 | 0.2% |
| TO_BOOL_NONE | 600 | 0.1% |
| LOAD_FAST | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 36,520 | 86.8% |
| BUILD_TUPLE | 5,360 | 12.7% |
| CALL | 180 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 31,220 | 74.2% |
| LOAD_FAST | 10,840 | 25.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,052,973 | 94.1% |
| LOAD_ATTR_METHOD_LAZY_DICT | 64,015 | 5.7% |
| LOAD_ATTR | 1,200 | 0.1% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 543,960 | 48.6% |
| POP_TOP | 386,375 | 34.5% |
| LOAD_FAST | 50,180 | 4.5% |
| RETURN_VALUE | 48,688 | 4.4% |
| CALL_BUILTIN_FAST | 48,191 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 760,812 | 91.4% |
| LOAD_CONST | 30,200 | 3.6% |
| CALL | 27,535 | 3.3% |
| RETURN_VALUE | 12,080 | 1.5% |
| STORE_FAST | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 788,487 | 94.7% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 3,421,585 | 46.3% |
| LOAD_FAST | 2,736,466 | 37.1% |
| LOAD_FAST_LOAD_FAST | 678,236 | 9.2% |
| LOAD_SUPER_ATTR_METHOD | 260,267 | 3.5% |
| LOAD_GLOBAL_MODULE | 90,380 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,341,826 | 99.4% |
| MAKE_CELL | 26,840 | 0.4% |
| RETURN_GENERATOR | 16,820 | 0.2% |
| COPY_FREE_VARS | 360 | 0.0% |
| PUSH_EXC_INFO | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 917,435 | 50.1% |
| LOAD_ATTR_MODULE | 596,684 | 32.6% |
| LOAD_FAST | 187,027 | 10.2% |
| LOAD_CONST | 73,665 | 4.0% |
| BINARY_OP | 49,520 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,233,688 | 67.4% |
| COPY_FREE_VARS | 596,764 | 32.6% |


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
| LOAD_CONST | 1,143,780 | 45.3% |
| LOAD_ATTR_INSTANCE_VALUE | 799,246 | 31.6% |
| LOAD_FAST | 544,980 | 21.6% |
| LOAD_FAST_LOAD_FAST | 16,880 | 0.7% |
| CALL_BUILTIN_FAST | 12,080 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,523,266 | 99.9% |
| POP_JUMP_IF_TRUE | 1,981 | 0.1% |
| RETURN_VALUE | 160 | 0.0% |
| STORE_FAST | 140 | 0.0% |
| COMPARE_OP | 89 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,236,486 | 95.4% |
| LOAD_CONST | 53,140 | 4.1% |
| LOAD_FAST | 5,500 | 0.4% |
| COMPARE_OP | 435 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,260,796 | 97.3% |
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
| JUMP_BACKWARD | 6,569,970 | 83.1% |
| GET_ITER | 1,071,614 | 13.6% |
| SWAP | 259,943 | 3.3% |
| FOR_ITER | 300 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 5,440,060 | 68.8% |
| STORE_FAST | 853,896 | 10.8% |
| JUMP_BACKWARD | 544,000 | 6.9% |
| LOAD_FAST | 520,694 | 6.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 276,374 | 3.5% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 270,534 | 65.1% |
| GET_ITER | 144,981 | 34.9% |
| FOR_ITER | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 282,959 | 68.1% |
| LOAD_FAST | 122,196 | 29.4% |
| RETURN_CONST | 10,560 | 2.5% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 14,400 | 53.3% |
| GET_ITER | 11,100 | 41.1% |
| SWAP | 860 | 3.2% |
| LOAD_FAST | 620 | 2.3% |
| FOR_ITER | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,340 | 45.7% |
| LOAD_FAST | 10,460 | 38.7% |
| STORE_FAST_LOAD_FAST | 2,000 | 7.4% |
| RETURN_CONST | 1,280 | 4.7% |
| SWAP | 860 | 3.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 48,151 | 82.4% |
| LOAD_ATTR_MODULE | 10,200 | 17.5% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,567 | 72.9% |
| LOAD_FAST_CHECK | 15,864 | 27.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,727,704 | 91.8% |
| LOAD_FAST_LOAD_FAST | 901,304 | 4.9% |
| COPY | 543,888 | 3.0% |
| LOAD_ATTR_INSTANCE_VALUE | 21,281 | 0.1% |
| RETURN_VALUE | 12,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,303,342 | 23.6% |
| LOAD_FAST | 2,758,341 | 15.1% |
| LOAD_ATTR | 1,500,362 | 8.2% |
| LOAD_GLOBAL_MODULE | 1,263,747 | 6.9% |
| BEFORE_WITH | 1,184,904 | 6.5% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,324 | 99.9% |
| LOAD_ATTR | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,502 | 39.8% |
| CALL | 81,987 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,015 | 26.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,303,342 | 88.1% |
| LOAD_FAST | 453,006 | 9.3% |
| LOAD_ATTR | 51,030 | 1.0% |
| LOAD_ATTR_SLOT | 49,520 | 1.0% |
| LOAD_CONST | 12,960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,603,481 | 32.8% |
| CALL | 1,329,502 | 27.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,052,973 | 21.6% |
| LOAD_CONST | 688,468 | 14.1% |
| LOAD_FAST_LOAD_FAST | 179,194 | 3.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,687,036 | 67.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,048,947 | 15.2% |
| LOAD_FAST_LOAD_FAST | 596,684 | 8.6% |
| BINARY_SUBSCR | 543,920 | 7.9% |
| LOAD_GLOBAL_MODULE | 27,260 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,421,585 | 49.4% |
| LOAD_FAST | 1,811,931 | 26.2% |
| CALL_PY_WITH_DEFAULTS | 917,435 | 13.3% |
| LOAD_FAST_LOAD_FAST | 610,720 | 8.8% |
| LOAD_CONST | 90,545 | 1.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,317,750 | 99.9% |
| LOAD_ATTR | 2,815 | 0.1% |
| LOAD_FAST | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,578,490 | 68.0% |
| CALL_PY_WITH_DEFAULTS | 596,684 | 25.7% |
| STORE_DEREF | 53,120 | 2.3% |
| LOAD_CONST | 31,040 | 1.3% |
| LOAD_FAST | 27,840 | 1.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 632,164 | 69.6% |
| LOAD_FAST_LOAD_FAST | 275,814 | 30.4% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 596,724 | 65.7% |
| UNARY_INVERT | 275,894 | 30.4% |
| RETURN_VALUE | 12,120 | 1.3% |
| LOAD_CONST | 12,120 | 1.3% |
| LOAD_FAST_LOAD_FAST | 5,400 | 0.6% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 535,191 | 95.1% |
| RETURN_VALUE | 26,480 | 4.7% |
| LOAD_GLOBAL_MODULE | 600 | 0.1% |
| LOAD_ATTR | 320 | 0.1% |
| LOAD_ATTR_PROPERTY | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 550,431 | 97.8% |
| TO_BOOL_BOOL | 12,160 | 2.2% |
| LOAD_ATTR_PROPERTY | 220 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,740 | 99.9% |
| LOAD_ATTR | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 49,520 | 80.1% |
| CALL_BUILTIN_FAST | 12,220 | 19.8% |
| CALL | 40 | 0.1% |
| LOAD_ATTR | 40 | 0.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,144,795 | 39.3% |
| LOAD_GLOBAL_BUILTIN | 755,872 | 13.9% |
| STORE_FAST | 657,481 | 12.1% |
| LOAD_FAST | 636,704 | 11.7% |
| JUMP_BACKWARD | 543,960 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,475,156 | 45.4% |
| LOAD_DEREF | 929,831 | 17.1% |
| LOAD_GLOBAL_BUILTIN | 755,872 | 13.9% |
| CALL_ISINSTANCE | 613,264 | 11.2% |
| LOAD_GLOBAL_MODULE | 586,360 | 10.8% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,527,277 | 24.3% |
| RESUME_CHECK | 1,813,739 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,263,747 | 12.2% |
| NOP | 971,005 | 9.3% |
| POP_JUMP_IF_FALSE | 827,506 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,317,750 | 22.3% |
| BINARY_OP | 1,928,119 | 18.6% |
| LOAD_FAST_LOAD_FAST | 1,376,884 | 13.3% |
| COMPARE_OP_STR | 1,236,486 | 11.9% |
| LOAD_FAST | 1,204,642 | 11.6% |


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
| LOAD_FAST | 874,671 | 100.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 609,124 | 69.6% |
| CALL_PY_EXACT_ARGS | 260,267 | 29.7% |
| LOAD_FAST | 5,440 | 0.6% |
| CALL | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 10,275,592 | 37.0% |
| CALL_PY_EXACT_ARGS | 7,341,826 | 26.4% |
| FOR_ITER_GEN | 5,983,920 | 21.5% |
| CALL_PY_WITH_DEFAULTS | 1,233,688 | 4.4% |
| COPY_FREE_VARS | 935,651 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,786,088 | 56.8% |
| POP_TOP | 6,528,880 | 23.5% |
| LOAD_GLOBAL_BUILTIN | 2,144,795 | 7.7% |
| LOAD_GLOBAL_MODULE | 1,813,739 | 6.5% |
| NOP | 789,824 | 2.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,062,548 | 65.5% |
| SWAP | 543,888 | 17.3% |
| LOAD_FAST_LOAD_FAST | 506,367 | 16.1% |
| LOAD_ATTR_INSTANCE_VALUE | 16,080 | 0.5% |
| STORE_FAST_LOAD_FAST | 12,080 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,242,948 | 39.5% |
| LOAD_FAST | 882,363 | 28.0% |
| LOAD_GLOBAL_MODULE | 486,407 | 15.4% |
| LOAD_CONST | 289,420 | 9.2% |
| LOAD_FAST_LOAD_FAST | 121,160 | 3.8% |


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
| LOAD_ATTR | 596,684 | 87.6% |
| LOAD_FAST | 40,750 | 6.0% |
| LOAD_ATTR_INSTANCE_VALUE | 32,760 | 4.8% |
| CALL | 10,200 | 1.5% |
| LOAD_CONST | 600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 598,769 | 87.9% |
| RETURN_CONST | 29,000 | 4.3% |
| LOAD_GLOBAL_MODULE | 26,760 | 3.9% |
| LOAD_CONST | 26,520 | 3.9% |
| NOP | 140 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 998,992 | 20.8% |
| CALL | 682,779 | 14.2% |
| LOAD_FAST | 668,174 | 13.9% |
| RETURN_CONST | 640,826 | 13.4% |
| CALL_ISINSTANCE | 613,544 | 12.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,173,733 | 66.2% |
| POP_JUMP_IF_TRUE | 1,483,606 | 30.9% |
| UNARY_NOT | 137,900 | 2.9% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,469,182 | 55.2% |
| BINARY_OP | 596,824 | 22.4% |
| LOAD_FAST | 596,684 | 22.4% |
| TO_BOOL | 240 | 0.0% |
| CALL_BUILTIN_O | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,663,070 | 100.0% |
| POP_JUMP_IF_TRUE | 140 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 271,127 | 87.3% |
| LOAD_ATTR_INSTANCE_VALUE | 39,380 | 12.7% |
| TO_BOOL | 200 | 0.1% |
| LOAD_ATTR_MODULE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 310,567 | 99.9% |
| POP_JUMP_IF_TRUE | 160 | 0.1% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180,029 | 79.9% |
| LOAD_FAST | 26,940 | 12.0% |
| COPY | 11,960 | 5.3% |
| WITH_EXCEPT_START | 5,360 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 207,789 | 92.2% |
| POP_JUMP_IF_TRUE | 17,460 | 7.8% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 2,000 | 71.4% |
| LOAD_FAST | 620 | 22.1% |
| COPY | 160 | 5.7% |
| LOAD_GLOBAL_MODULE | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,600 | 92.9% |
| POP_JUMP_IF_TRUE | 200 | 7.1% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,055,880 | 95.6% |
| CALL_BUILTIN_FAST | 48,191 | 4.4% |
| CALL_METHOD_DESCRIPTOR_O | 280 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,056,220 | 95.6% |
| STORE_FAST | 48,231 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 549,280 | 34.1% |
| LOAD_FAST_CHECK | 543,920 | 33.8% |
| FOR_ITER_LIST | 276,374 | 17.2% |
| CALL_BUILTIN_FAST | 225,630 | 14.0% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,602,984 | 99.6% |
| LOAD_FAST | 6,040 | 0.4% |
| STORE_DEREF | 60 | 0.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 58.2% |
| COPY | 161 | 33.5% |
| TO_BOOL | 40 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 300 | 62.4% |
| POP_JUMP_IF_FALSE | 181 | 37.6% |


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
|     deferred | 3,648,660 | 68.4% |
|          hit | 1,680,070 | 31.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 595 | 9.7% |
| Failure | 5,544 | 90.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 2,724 | 49.1% |
| or | 1,416 | 25.5% |
| remainder | 724 | 13.1% |
| add different types | 600 | 10.8% |
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
|     deferred | 590,414 | 54.3% |
|          hit | 496,792 | 45.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 22.2% |
| Failure | 839 | 77.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 839 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,308,534 | 31.4% |
|          hit | 18,112,088 | 68.4% |
|         miss | 7,540 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,286 | 25.0% |
| Failure | 27,904 | 75.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 7,281 | 26.1% |
| cfunc noargs | 5,791 | 20.8% |
| class no vectorcall | 3,780 | 13.5% |
| meth descr varargs keywords | 3,056 | 11.0% |
| class mutable | 1,108 | 4.0% |
| other | 1,100 | 3.9% |
| bound method | 1,040 | 3.7% |
| cfunc varargs | 1,020 | 3.7% |
| meth descr method fastcall keywords | 860 | 3.1% |
| cfunc varargs keywords | 768 | 2.8% |
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
|     deferred | 313,166 | 7.6% |
|          hit | 3,815,391 | 92.2% |
|         miss | 5,946 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,604 | 55.6% |
| Failure | 1,282 | 44.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 762 | 59.4% |
| big int | 340 | 26.5% |
| different types | 180 | 14.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,220,380 | 7.8% |
|          hit | 14,339,422 | 92.1% |

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
|     deferred | 6,185,753 | 15.3% |
|          hit | 33,865,857 | 83.8% |
|         miss | 309,536 | 0.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 22,367 | 54.5% |
| Failure | 18,675 | 45.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 4,306 | 23.1% |
| shadowed | 3,891 | 20.8% |
| not managed dict | 3,204 | 17.2% |
| non overriding descriptor | 2,268 | 12.1% |
| has managed dict | 1,060 | 5.7% |
| class attr descriptor | 940 | 5.0% |
| metaclass attribute | 900 | 4.8% |
| class method obj | 840 | 4.5% |
| non object slot | 520 | 2.8% |
| class attr simple | 426 | 2.3% |
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
|          hit | 15,837,848 | 99.9% |
|         miss | 1,027 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 9,553 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 929,831 | 99.9% |

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
|     deferred | 83,917 | 2.5% |
|          hit | 2,966,418 | 89.7% |
|         miss | 245,260 | 7.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8,975 | 79.2% |
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
|     deferred | 28,097 | 4.0% |
|          hit | 681,249 | 95.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 255 | 29.1% |
| Failure | 620 | 70.9% |

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
|     deferred | 1,381,696 | 14.7% |
|          hit | 7,997,426 | 85.2% |
|         miss | 280 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,001 | 46.6% |
| Failure | 3,439 | 53.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 1,000 | 29.1% |
| sequence | 839 | 24.4% |
| set | 700 | 20.4% |
| tuple | 700 | 20.4% |
| other | 200 | 5.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 480 | 0.0% |
|          hit | 2,713,535 | 100.0% |

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
| Basic | 237,583,072 | 57.9% |
| Not specialized | 40,764,065 | 9.9% |
| Specialized hits | 131,126,410 | 32.0% |
| Specialized misses | 569,593 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,308,534 | 38.2% |
| LOAD_ATTR | 6,185,753 | 28.4% |
| BINARY_OP | 3,648,660 | 16.8% |
| TO_BOOL | 1,381,696 | 6.3% |
| FOR_ITER | 1,220,380 | 5.6% |
| BINARY_SUBSCR | 590,414 | 2.7% |
| COMPARE_OP | 313,166 | 1.4% |
| STORE_ATTR | 83,917 | 0.4% |
| STORE_SUBSCR | 28,097 | 0.1% |
| LOAD_GLOBAL | 8,387 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 245,260 | 43.1% |
| LOAD_ATTR_INSTANCE_VALUE | 214,038 | 37.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 82,018 | 14.4% |
| LOAD_ATTR_PROPERTY | 12,380 | 2.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 6,080 | 1.1% |
| COMPARE_OP_INT | 5,926 | 1.0% |
| LOAD_ATTR_MODULE | 1,100 | 0.2% |
| CALL_PY_EXACT_ARGS | 860 | 0.2% |
| LOAD_GLOBAL_MODULE | 687 | 0.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 420 | 0.1% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 10,357,492 | 37.2% |
| Calls to Python functions inlined | 17,453,404 | 62.8% |
| Calls via PyEval_EvalFrame (total) | 10,357,492 | 37.2% |
| Calls via PyEval_EvalFrame (vector) | 9,805,972 | 35.3% |
| Calls via PyEval_EvalFrame (generator) | 551,520 | 2.0% |
| Calls via PyEval_EvalFrame (legacy) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 9,805,272 | 35.3% |
| Calls via PyEval_EvalFrame (build class) | 560 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 589,440 | 2.1% |
| Calls via PyEval_EvalFrame (function ex) | 534,060 | 1.9% |
| Calls via PyEval_EvalFrame (api) | 387,706 | 1.4% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 36,088 | 0.1% |
| Frames pushed | 11,007,926 | 39.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 13,611,177 | 40.3% |
| Frees to freelist | 13,623,191 |  |
| Allocations | 20,152,927 | 59.7% |
| Allocations to 512 bytes | 19,970,032 | 59.1% |
| Allocations to 4 kbytes | 83,382 | 0.2% |
| Allocations over 4 kbytes | 99,513 | 0.3% |
| Frees | 20,946,486 |  |
| New values | 80,340 |  |
| Interpreter increfs | 160,560,409 | 77.7% |
| Interpreter decrefs | 174,932,898 | 73.7% |
| Increfs | 45,955,014 | 22.3% |
| Decrefs | 62,396,689 | 26.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 40 | 0.0% |
| Method cache hits | 7,097,610 |  |
| Method cache misses | 47,548 |  |
| Method cache collisions | 89,237 |  |
| Method cache dunder hits | 8,737,449 |  |
| Method cache dunder misses | 45,422 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 24 | 360 | 175,542 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |
| Traces executed | 0 |  |
| Uops executed | 0 |  |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


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
Stats gathered on: 2023-11-05
