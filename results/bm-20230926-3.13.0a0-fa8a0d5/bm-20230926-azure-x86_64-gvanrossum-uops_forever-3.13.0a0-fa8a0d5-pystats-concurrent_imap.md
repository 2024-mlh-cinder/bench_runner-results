
# Pystats results

- benchmark: concurrent_imap
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 55,256,764 | 17.4% | 17.4% |  |
| RESUME_CHECK | 22,360,970 | 7.0% | 24.4% | 0.0% |
| STORE_FAST | 16,841,868 | 5.3% | 29.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 14,790,750 | 4.6% | 34.3% | 1.1% |
| POP_TOP | 14,744,720 | 4.6% | 38.9% |  |
| RETURN_VALUE | 13,135,993 | 4.1% | 43.1% |  |
| POP_JUMP_IF_FALSE | 10,527,264 | 3.3% | 46.4% |  |
| LOAD_CONST | 9,233,345 | 2.9% | 49.3% |  |
| LOAD_GLOBAL_MODULE | 8,294,090 | 2.6% | 51.9% | 0.0% |
| INTERPRETER_EXIT | 8,049,086 | 2.5% | 54.4% |  |
| LOAD_FAST_LOAD_FAST | 8,025,947 | 2.5% | 56.9% |  |
| CALL | 7,025,109 | 2.2% | 59.1% |  |
| ENTER_EXECUTOR | 6,744,915 | 2.1% | 61.2% |  |
| CALL_PY_EXACT_ARGS | 6,327,084 | 2.0% | 63.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,616,984 | 1.8% | 65.0% | 1.1% |
| JUMP_BACKWARD | 5,383,316 | 1.7% | 66.7% |  |
| LOAD_ATTR | 5,223,180 | 1.6% | 68.3% |  |
| NOP | 5,132,808 | 1.6% | 69.9% |  |
| RETURN_CONST | 5,124,320 | 1.6% | 71.5% |  |
| YIELD_VALUE | 4,896,480 | 1.5% | 73.1% |  |
| COPY | 4,622,128 | 1.5% | 74.5% |  |
| FOR_ITER_GEN | 4,496,160 | 1.4% | 75.9% |  |
| PUSH_NULL | 3,972,771 | 1.2% | 77.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,913,092 | 1.2% | 78.4% |  |
| LOAD_GLOBAL_BUILTIN | 3,903,200 | 1.2% | 79.6% |  |
| TO_BOOL_BOOL | 3,890,677 | 1.2% | 80.9% |  |
| BINARY_OP | 3,498,968 | 1.1% | 82.0% |  |
| STORE_FAST_STORE_FAST | 3,279,007 | 1.0% | 83.0% |  |
| POP_JUMP_IF_NOT_NONE | 2,925,475 | 0.9% | 83.9% |  |
| BUILD_TUPLE | 2,772,046 | 0.9% | 84.8% |  |
| TO_BOOL_INT | 2,575,132 | 0.8% | 85.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 2,519,701 | 0.8% | 86.4% | 5.9% |
| COMPARE_OP_INT | 2,078,376 | 0.7% | 87.0% | 0.3% |
| LOAD_ATTR_MODULE | 1,972,053 | 0.6% | 87.7% |  |
| CALL_FUNCTION_EX | 1,730,708 | 0.5% | 88.2% |  |
| POP_JUMP_IF_TRUE | 1,691,994 | 0.5% | 88.7% |  |
| CALL_PY_WITH_DEFAULTS | 1,583,270 | 0.5% | 89.2% |  |
| SWAP | 1,444,423 | 0.5% | 89.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,311,487 | 0.4% | 90.1% |  |
| GET_ITER | 1,215,998 | 0.4% | 90.5% |  |
| BEFORE_WITH | 1,200,360 | 0.4% | 90.9% |  |
| FOR_ITER_LIST | 1,157,491 | 0.4% | 91.2% |  |
| BUILD_MAP | 1,105,134 | 0.3% | 91.6% |  |
| TO_BOOL | 1,062,487 | 0.3% | 91.9% |  |
| COMPARE_OP_STR | 997,675 | 0.3% | 92.2% |  |
| CONTAINS_OP | 985,339 | 0.3% | 92.5% |  |
| JUMP_FORWARD | 972,717 | 0.3% | 92.8% |  |
| LOAD_DEREF | 921,294 | 0.3% | 93.1% |  |
| FOR_ITER | 914,840 | 0.3% | 93.4% |  |
| STORE_FAST_LOAD_FAST | 898,080 | 0.3% | 93.7% |  |
| COPY_FREE_VARS | 885,414 | 0.3% | 94.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 883,332 | 0.3% | 94.2% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 865,372 | 0.3% | 94.5% |  |
| LOAD_SUPER_ATTR_METHOD | 839,934 | 0.3% | 94.8% |  |
| UNARY_INVERT | 838,492 | 0.3% | 95.0% |  |
| UNPACK_SEQUENCE_TUPLE | 828,242 | 0.3% | 95.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 827,445 | 0.3% | 95.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 819,842 | 0.3% | 95.8% |  |
| CALL_BUILTIN_FAST | 813,664 | 0.3% | 96.1% |  |
| BINARY_OP_ADD_INT | 807,252 | 0.3% | 96.3% |  |
| BUILD_LIST | 768,758 | 0.2% | 96.6% |  |
| STORE_SUBSCR_DICT | 642,332 | 0.2% | 96.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 623,690 | 0.2% | 97.0% |  |
| POP_JUMP_IF_NONE | 612,122 | 0.2% | 97.2% |  |
| CALL_ISINSTANCE | 591,120 | 0.2% | 97.3% |  |
| CALL_BUILTIN_CLASS | 556,410 | 0.2% | 97.5% |  |
| EXIT_INIT_CHECK | 544,188 | 0.2% | 97.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 544,188 | 0.2% | 97.9% |  |
| LOAD_FAST_CHECK | 537,996 | 0.2% | 98.0% |  |
| LOAD_ATTR_PROPERTY | 526,905 | 0.2% | 98.2% | 1.7% |
| BINARY_SUBSCR | 444,010 | 0.1% | 98.3% |  |
| LIST_APPEND | 423,450 | 0.1% | 98.5% |  |
| DICT_MERGE | 420,720 | 0.1% | 98.6% |  |
| CALL_TUPLE_1 | 412,560 | 0.1% | 98.7% |  |
| LOAD_FAST_AND_CLEAR | 386,536 | 0.1% | 98.9% |  |
| COMPARE_OP | 287,260 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 285,534 | 0.1% | 99.0% |  |
| LIST_EXTEND | 236,088 | 0.1% | 99.1% |  |
| CALL_KW | 195,864 | 0.1% | 99.2% |  |
| CALL_LEN | 192,436 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 182,168 | 0.1% | 99.3% |  |
| TO_BOOL_NONE | 168,853 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 162,264 | 0.1% | 99.4% |  |
| UNARY_NOT | 148,996 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 137,966 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 130,050 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 118,168 | 0.0% | 99.6% |  |
| STORE_DEREF | 99,600 | 0.0% | 99.6% |  |
| MAKE_CELL | 99,600 | 0.0% | 99.6% |  |
| CALL_BUILTIN_O | 82,080 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 81,120 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 72,960 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 72,960 | 0.0% | 99.7% |  |
| STORE_ATTR | 62,317 | 0.0% | 99.7% |  |
| DELETE_ATTR | 61,194 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 56,156 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 46,320 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 46,320 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 43,922 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 41,280 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 41,280 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 38,160 | 0.0% | 99.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 32,827 | 0.0% | 99.9% | 12.6% |
| IS_OP | 32,685 | 0.0% | 99.9% |  |
| BUILD_STRING | 29,040 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 27,860 | 0.0% | 99.9% |  |
| POP_EXCEPT | 27,860 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 27,840 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 27,600 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 25,920 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 23,780 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 21,934 | 0.0% | 99.9% |  |
| IMPORT_NAME | 21,840 | 0.0% | 99.9% |  |
| IMPORT_FROM | 21,840 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 21,094 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 19,920 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 18,240 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 12,720 | 0.0% | 100.0% |  |
| BINARY_SLICE | 12,720 | 0.0% | 100.0% |  |
| RERAISE | 12,240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 12,240 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 8,800 | 0.0% | 100.0% |  |
| END_FOR | 8,160 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,160 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,080 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,080 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 960 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 480 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 373 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 285 | 0.0% | 100.0% |  |
| RESUME | 15 | 0.0% | 100.0% | 13.3% |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 13,496,941 | 4.2% | 4.2% |
| RESUME_CHECK LOAD_FAST | 12,751,685 | 4.0% | 8.2% |
| CACHE RESUME_CHECK | 7,994,124 | 2.5% | 10.8% |
| RETURN_VALUE INTERPRETER_EXIT | 7,142,198 | 2.2% | 13.0% |
| LOAD_FAST RETURN_VALUE | 6,733,876 | 2.1% | 15.1% |
| STORE_FAST LOAD_FAST | 6,606,568 | 2.1% | 17.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 6,294,444 | 2.0% | 19.2% |
| POP_TOP ENTER_EXECUTOR | 5,087,920 | 1.6% | 20.8% |
| RESUME_CHECK POP_TOP | 4,896,480 | 1.5% | 22.3% |
| YIELD_VALUE STORE_FAST | 4,488,000 | 1.4% | 23.7% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,488,000 | 1.4% | 25.1% |
| FOR_ITER_GEN RESUME_CHECK | 4,488,000 | 1.4% | 26.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 4,293,773 | 1.3% | 27.9% |
| STORE_FAST JUMP_BACKWARD | 4,080,000 | 1.3% | 29.2% |
| POP_TOP LOAD_FAST | 4,015,514 | 1.3% | 30.4% |
| LOAD_FAST LOAD_ATTR | 3,892,716 | 1.2% | 31.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,758,574 | 1.2% | 32.8% |
| ENTER_EXECUTOR YIELD_VALUE | 3,672,000 | 1.2% | 34.0% |
| RETURN_CONST POP_TOP | 3,555,896 | 1.1% | 35.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 3,454,727 | 1.1% | 36.2% |
| NOP LOAD_FAST | 3,042,523 | 1.0% | 37.1% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 2,952,700 | 0.9% | 38.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 2,618,155 | 0.8% | 38.9% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,575,132 | 0.8% | 39.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,491,391 | 0.8% | 40.5% |
| LOAD_CONST LOAD_CONST | 2,439,860 | 0.8% | 41.2% |
| STORE_FAST NOP | 2,298,684 | 0.7% | 42.0% |
| PUSH_NULL LOAD_FAST | 2,269,203 | 0.7% | 42.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,253,249 | 0.7% | 43.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,084,447 | 0.7% | 44.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,077,191 | 0.7% | 44.7% |
| LOAD_FAST LOAD_CONST | 1,999,913 | 0.6% | 45.3% |
| COPY STORE_FAST | 1,948,320 | 0.6% | 45.9% |
| STORE_FAST COPY | 1,948,080 | 0.6% | 46.5% |
| CALL STORE_FAST | 1,939,461 | 0.6% | 47.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,938,126 | 0.6% | 47.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,923,534 | 0.6% | 48.4% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,866,446 | 0.6% | 48.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,837,462 | 0.6% | 49.5% |
| LOAD_CONST CALL | 1,728,034 | 0.5% | 50.1% |
| LOAD_FAST PUSH_NULL | 1,709,760 | 0.5% | 50.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,701,246 | 0.5% | 51.1% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,656,693 | 0.5% | 51.7% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,629,506 | 0.5% | 52.2% |
| LOAD_ATTR LOAD_FAST | 1,616,930 | 0.5% | 52.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,506,803 | 0.5% | 53.1% |
| CALL RETURN_VALUE | 1,480,080 | 0.5% | 53.6% |
| CALL POP_TOP | 1,435,272 | 0.5% | 54.1% |
| COPY TO_BOOL_INT | 1,417,372 | 0.4% | 54.5% |
| BINARY_OP COPY | 1,417,372 | 0.4% | 55.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,384,891 | 0.4% | 55.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,371,454 | 0.4% | 55.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,316,924 | 0.4% | 56.2% |
| LOAD_FAST CALL_FUNCTION_EX | 1,309,988 | 0.4% | 56.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,306,927 | 0.4% | 57.1% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,291,077 | 0.4% | 57.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,289,680 | 0.4% | 57.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,232,333 | 0.4% | 58.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,176,639 | 0.4% | 58.6% |
| POP_TOP RETURN_CONST | 1,160,886 | 0.4% | 59.0% |
| RETURN_VALUE STORE_FAST | 1,147,193 | 0.4% | 59.3% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,142,376 | 0.4% | 59.7% |
| POP_TOP LOAD_CONST | 1,140,434 | 0.4% | 60.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,123,526 | 0.4% | 60.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,110,864 | 0.3% | 60.8% |
| LOAD_FAST_LOAD_FAST CALL | 1,080,569 | 0.3% | 61.1% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,051,612 | 0.3% | 61.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,032,000 | 0.3% | 61.8% |
| LOAD_FAST TO_BOOL | 1,024,210 | 0.3% | 62.1% |
| LOAD_CONST LOAD_FAST | 1,005,911 | 0.3% | 62.4% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,004,390 | 0.3% | 62.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,000,380 | 0.3% | 63.0% |
| LOAD_FAST BUILD_TUPLE | 996,560 | 0.3% | 63.3% |
| LOAD_CONST COMPARE_OP_INT | 990,299 | 0.3% | 63.6% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 985,339 | 0.3% | 64.0% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 985,332 | 0.3% | 64.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 974,414 | 0.3% | 64.6% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 971,484 | 0.3% | 64.9% |
| RETURN_VALUE RETURN_VALUE | 966,953 | 0.3% | 65.2% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 953,981 | 0.3% | 65.5% |
| BEFORE_WITH POP_TOP | 948,426 | 0.3% | 65.8% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 941,764 | 0.3% | 66.1% |
| NOP LOAD_GLOBAL_MODULE | 910,925 | 0.3% | 66.4% |
| GET_ITER FOR_ITER_LIST | 908,748 | 0.3% | 66.6% |
| LOAD_ATTR PUSH_NULL | 906,971 | 0.3% | 66.9% |
| POP_TOP NOP | 898,228 | 0.3% | 67.2% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 897,017 | 0.3% | 67.5% |
| CALL_FUNCTION_EX RETURN_VALUE | 896,828 | 0.3% | 67.8% |
| JUMP_BACKWARD FOR_ITER | 893,040 | 0.3% | 68.1% |
| COPY_FREE_VARS RESUME_CHECK | 885,414 | 0.3% | 68.3% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 884,660 | 0.3% | 68.6% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 881,214 | 0.3% | 68.9% |
| LOAD_DEREF LOAD_FAST | 881,214 | 0.3% | 69.2% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 860,440 | 0.3% | 69.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 840,866 | 0.3% | 69.7% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 839,934 | 0.3% | 70.0% |
| UNARY_INVERT BINARY_OP | 838,492 | 0.3% | 70.2% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 834,182 | 0.3% | 70.5% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 826,734 | 0.3% | 70.7% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 821,040 | 0.3% | 71.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 12,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,720 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,994,124 | 99.3% |
| COPY_FREE_VARS | 54,480 | 0.7% |
| POP_TOP | 4,560 | 0.1% |
| RESUME | 4 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 884,660 | 73.7% |
| RETURN_VALUE | 247,854 | 20.6% |
| LOAD_GLOBAL_MODULE | 59,758 | 5.0% |
| CALL | 4,080 | 0.3% |
| ENTER_EXECUTOR | 4,008 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 948,426 | 79.0% |
| STORE_FAST | 251,934 | 21.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 19,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 19,920 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 408,000 | 91.9% |
| LOAD_CONST | 35,780 | 8.1% |
| BINARY_SUBSCR | 230 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 408,000 | 91.9% |
| STORE_FAST | 35,780 | 8.1% |
| BINARY_SUBSCR | 230 | 0.1% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 19,940 | 83.9% |
| LOAD_ATTR_MODULE | 3,840 | 16.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,780 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,598 | 49.1% |
| CALL | 19,918 | 35.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8,639 | 15.4% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 43,918 | 78.2% |
| RETURN_CONST | 7,678 | 13.7% |
| LOAD_FAST | 4,560 | 8.1% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 4,080 | 50.0% |
| LOAD_FAST | 4,080 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 544,188 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 544,188 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,920 | 52.2% |
| CONVERT_VALUE | 18,240 | 47.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,040 | 76.1% |
| BUILD_STRING | 9,120 | 23.9% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 764,318 | 62.9% |
| STORE_FAST_LOAD_FAST | 408,000 | 33.6% |
| CALL_BUILTIN_CLASS | 25,920 | 2.1% |
| CALL | 9,120 | 0.8% |
| RETURN_VALUE | 4,080 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 908,748 | 74.7% |
| LOAD_FAST_AND_CLEAR | 256,730 | 21.1% |
| FOR_ITER_RANGE | 21,480 | 1.8% |
| FOR_ITER_TUPLE | 8,160 | 0.7% |
| FOR_ITER_GEN | 8,160 | 0.7% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,142,198 | 88.7% |
| RETURN_CONST | 498,408 | 6.2% |
| YIELD_VALUE | 408,480 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 41,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 27,600 | 66.9% |
| STORE_FAST | 9,120 | 22.1% |
| LOAD_FAST | 4,560 | 11.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,298,684 | 44.8% |
| POP_TOP | 898,228 | 17.5% |
| POP_JUMP_IF_FALSE | 793,794 | 15.5% |
| RESUME_CHECK | 723,600 | 14.1% |
| POP_JUMP_IF_NOT_NONE | 252,938 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,042,523 | 59.3% |
| LOAD_GLOBAL_MODULE | 910,925 | 17.7% |
| LOAD_FAST_LOAD_FAST | 412,560 | 8.0% |
| LOAD_CONST | 396,240 | 7.7% |
| LOAD_GLOBAL_BUILTIN | 362,516 | 7.1% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 15,860 | 56.9% |
| COPY | 8,160 | 29.3% |
| POP_TOP | 3,840 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,860 | 56.9% |
| RERAISE | 8,160 | 29.3% |
| JUMP_FORWARD | 3,840 | 13.8% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,896,480 | 33.2% |
| RETURN_CONST | 3,555,896 | 24.1% |
| CALL | 1,435,272 | 9.7% |
| BEFORE_WITH | 948,426 | 6.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 783,120 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,087,920 | 34.5% |
| LOAD_FAST | 4,015,514 | 27.2% |
| RETURN_CONST | 1,160,886 | 7.9% |
| LOAD_CONST | 1,140,434 | 7.7% |
| NOP | 898,228 | 6.1% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 19,940 | 71.6% |
| RERAISE | 4,080 | 14.6% |
| CALL_KW | 3,840 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 19,940 | 71.6% |
| WITH_EXCEPT_START | 4,080 | 14.6% |
| LOAD_GLOBAL_MODULE | 3,840 | 13.8% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,709,760 | 43.0% |
| LOAD_ATTR_MODULE | 1,289,680 | 32.5% |
| LOAD_ATTR | 906,971 | 22.8% |
| LOAD_SUPER_ATTR_ATTR | 41,280 | 1.0% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,269,203 | 57.1% |
| LOAD_FAST_LOAD_FAST | 941,764 | 23.7% |
| CALL | 533,556 | 13.4% |
| LOAD_CONST | 177,575 | 4.5% |
| CALL_PY_EXACT_ARGS | 34,080 | 0.9% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,080 | 32.1% |
| RETURN_VALUE | 4,080 | 32.1% |
| LOAD_FAST | 4,080 | 32.1% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 3.8% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,733,876 | 51.3% |
| CALL | 1,480,080 | 11.3% |
| RETURN_VALUE | 966,953 | 7.4% |
| CALL_FUNCTION_EX | 896,828 | 6.8% |
| LOAD_ATTR_INSTANCE_VALUE | 808,766 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,142,198 | 54.4% |
| STORE_FAST | 1,147,193 | 8.7% |
| RETURN_VALUE | 966,953 | 7.4% |
| POP_TOP | 748,546 | 5.7% |
| LOAD_FAST_LOAD_FAST | 578,880 | 4.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 9,120 | 43.2% |
| LOAD_FAST | 7,694 | 36.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,080 | 19.3% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 13,200 | 62.6% |
| LOAD_GLOBAL_MODULE | 7,680 | 36.4% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 7 | 0.0% |
| LOAD_FAST | 7 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,024,210 | 96.4% |
| LOAD_ATTR_INSTANCE_VALUE | 37,199 | 3.5% |
| TO_BOOL | 1,055 | 0.1% |
| COPY | 12 | 0.0% |
| LOAD_ATTR | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 545,973 | 51.4% |
| POP_JUMP_IF_FALSE | 515,446 | 48.5% |
| TO_BOOL | 1,055 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 8 | 0.0% |
| TO_BOOL_BOOL | 5 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 578,880 | 69.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 259,612 | 31.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 838,492 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 148,996 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 148,996 | 100.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 4,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 4,080 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,866,446 | 53.3% |
| UNARY_INVERT | 838,492 | 24.0% |
| POP_JUMP_IF_FALSE | 578,880 | 16.5% |
| LOAD_ATTR | 138,930 | 4.0% |
| LOAD_FAST_LOAD_FAST | 37,200 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,417,372 | 40.5% |
| STORE_FAST | 717,806 | 20.5% |
| UNARY_INVERT | 578,880 | 16.5% |
| TO_BOOL_INT | 578,880 | 16.5% |
| BUILD_TUPLE | 129,806 | 3.7% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 256,730 | 33.4% |
| JUMP_FORWARD | 247,854 | 32.2% |
| LOAD_FAST | 130,050 | 16.9% |
| POP_TOP | 117,804 | 15.3% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 259,854 | 33.8% |
| SWAP | 256,730 | 33.4% |
| STORE_FAST | 248,334 | 32.3% |
| RETURN_VALUE | 3,840 | 0.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 408,000 | 36.9% |
| LOAD_FAST | 396,240 | 35.9% |
| RESUME_CHECK | 255,534 | 23.1% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 2.2% |
| POP_JUMP_IF_NOT_NONE | 12,240 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 684,894 | 62.0% |
| BUILD_TUPLE | 408,000 | 36.9% |
| STORE_FAST | 12,240 | 1.1% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 19,920 | 68.6% |
| FORMAT_SIMPLE | 9,120 | 31.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 19,920 | 68.6% |
| RETURN_VALUE | 9,120 | 31.4% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 996,560 | 36.0% |
| LOAD_FAST_LOAD_FAST | 821,040 | 29.6% |
| BUILD_MAP | 408,000 | 14.7% |
| RETURN_VALUE | 384,000 | 13.9% |
| BINARY_OP | 129,806 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 816,000 | 29.4% |
| CALL | 579,360 | 20.9% |
| BUILD_MAP | 408,000 | 14.7% |
| STORE_FAST | 384,000 | 13.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 13.9% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,728,034 | 24.6% |
| LOAD_FAST_LOAD_FAST | 1,080,569 | 15.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,000,380 | 14.2% |
| ENTER_EXECUTOR | 787,800 | 11.2% |
| BUILD_TUPLE | 579,360 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,939,461 | 27.6% |
| RETURN_VALUE | 1,480,080 | 21.1% |
| POP_TOP | 1,435,272 | 20.4% |
| LOAD_FAST | 577,944 | 8.2% |
| TO_BOOL_BOOL | 512,893 | 7.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,309,988 | 75.7% |
| DICT_MERGE | 420,720 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 896,828 | 51.8% |
| RESUME_CHECK | 400,320 | 23.1% |
| CALL_BUILTIN_CLASS | 384,000 | 22.2% |
| POP_TOP | 45,360 | 2.6% |
| STORE_FAST | 4,080 | 0.2% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 191,864 | 98.0% |
| ENTER_EXECUTOR | 4,000 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 148,764 | 76.0% |
| LOAD_FAST | 20,400 | 10.4% |
| RETURN_VALUE | 13,680 | 7.0% |
| STORE_FAST | 9,120 | 4.7% |
| PUSH_EXC_INFO | 3,840 | 2.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 285,489 | 99.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,292 | 0.4% |
| COMPARE_OP | 354 | 0.1% |
| COMPARE_OP_INT | 92 | 0.0% |
| LOAD_GLOBAL_MODULE | 14 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 286,732 | 99.8% |
| COMPARE_OP | 354 | 0.1% |
| COMPARE_OP_INT | 149 | 0.1% |
| COMPARE_OP_STR | 14 | 0.0% |
| POP_JUMP_IF_TRUE | 11 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 985,332 | 100.0% |
| LOAD_ATTR | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 985,339 | 100.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 9,120 | 50.0% |
| BINARY_SUBSCR_DICT | 9,120 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 18,240 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,948,080 | 42.1% |
| BINARY_OP | 1,417,372 | 30.7% |
| LOAD_CONST | 800,640 | 17.3% |
| LOAD_FAST | 415,579 | 9.0% |
| STORE_ATTR_INSTANCE_VALUE | 13,680 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,948,320 | 42.2% |
| TO_BOOL_INT | 1,417,372 | 30.7% |
| STORE_FAST_STORE_FAST | 796,080 | 17.2% |
| LOAD_ATTR_INSTANCE_VALUE | 406,445 | 8.8% |
| LOAD_FAST | 18,240 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 578,880 | 65.4% |
| CALL_ALLOC_AND_ENTER_INIT | 247,854 | 28.0% |
| CACHE | 54,480 | 6.2% |
| CALL | 4,080 | 0.5% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 885,414 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,194 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,796 | 66.7% |
| RETURN_CONST | 19,918 | 32.5% |
| LOAD_GLOBAL_MODULE | 480 | 0.8% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 396,240 | 94.2% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 420,720 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,087,920 | 75.4% |
| POP_JUMP_IF_NOT_NONE | 619,608 | 9.2% |
| STORE_FAST_STORE_FAST | 408,000 | 6.0% |
| LIST_APPEND | 350,490 | 5.2% |
| CALL_LIST_APPEND | 129,806 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 3,672,000 | 54.4% |
| CALL | 787,800 | 11.7% |
| LOAD_ATTR_MODULE | 739,598 | 11.0% |
| LOAD_FAST | 503,254 | 7.5% |
| JUMP_BACKWARD | 408,000 | 6.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 893,040 | 97.6% |
| SWAP | 9,120 | 1.0% |
| GET_ITER | 8,160 | 0.9% |
| LOAD_FAST | 4,080 | 0.4% |
| FOR_ITER | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 480,960 | 52.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 412,080 | 45.0% |
| SWAP | 9,120 | 1.0% |
| RETURN_CONST | 8,160 | 0.9% |
| LOAD_GLOBAL_MODULE | 4,080 | 0.4% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 21,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 21,840 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 21,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 21,840 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 19,920 | 60.9% |
| LOAD_FAST | 12,240 | 37.4% |
| LOAD_GLOBAL_MODULE | 521 | 1.6% |
| LOAD_GLOBAL | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 32,685 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,080,000 | 75.8% |
| POP_TOP | 817,225 | 15.2% |
| ENTER_EXECUTOR | 408,000 | 7.6% |
| LIST_APPEND | 72,960 | 1.4% |
| STORE_FAST_STORE_FAST | 4,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 4,488,000 | 83.4% |
| FOR_ITER | 893,040 | 16.6% |
| FOR_ITER_LIST | 1,133 | 0.0% |
| FOR_ITER_RANGE | 454 | 0.0% |
| LOAD_FAST | 399 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 532,898 | 54.8% |
| POP_TOP | 427,339 | 43.9% |
| STORE_ATTR_INSTANCE_VALUE | 4,560 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 4,080 | 0.4% |
| POP_EXCEPT | 3,840 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 679,485 | 69.9% |
| BUILD_LIST | 247,854 | 25.5% |
| LOAD_GLOBAL_MODULE | 17,038 | 1.8% |
| POP_EXCEPT | 15,860 | 1.6% |
| LOAD_FAST_LOAD_FAST | 4,560 | 0.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 220,684 | 52.1% |
| LOAD_ATTR | 129,806 | 30.7% |
| BINARY_SUBSCR_STR_INT | 72,960 | 17.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 350,490 | 82.8% |
| JUMP_BACKWARD | 72,960 | 17.2% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 118,284 | 50.1% |
| RETURN_VALUE | 117,804 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 118,044 | 50.0% |
| STORE_FAST | 117,804 | 49.9% |
| RETURN_VALUE | 240 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,892,716 | 74.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,176,639 | 22.5% |
| LOAD_GLOBAL_MODULE | 88,770 | 1.7% |
| CALL | 37,200 | 0.7% |
| LOAD_FAST_LOAD_FAST | 13,214 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,616,930 | 31.0% |
| PUSH_NULL | 906,971 | 17.4% |
| STORE_SUBSCR_DICT | 578,880 | 11.1% |
| POP_JUMP_IF_NOT_NONE | 537,537 | 10.3% |
| STORE_FAST | 377,458 | 7.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,439,860 | 26.4% |
| LOAD_FAST | 1,999,913 | 21.7% |
| POP_TOP | 1,140,434 | 12.4% |
| POP_JUMP_IF_FALSE | 598,907 | 6.5% |
| LOAD_ATTR_METHOD_NO_DICT | 512,384 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,439,860 | 26.4% |
| CALL | 1,728,034 | 18.7% |
| LOAD_FAST | 1,005,911 | 10.9% |
| COMPARE_OP_INT | 990,299 | 10.7% |
| COPY | 800,640 | 8.7% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 881,214 | 95.6% |
| STORE_DEREF | 19,920 | 2.2% |
| POP_JUMP_IF_NOT_NONE | 19,920 | 2.2% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 881,214 | 95.6% |
| POP_JUMP_IF_NOT_NONE | 39,840 | 4.3% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,751,685 | 23.1% |
| STORE_FAST | 6,606,568 | 12.0% |
| POP_JUMP_IF_FALSE | 4,293,773 | 7.8% |
| POP_TOP | 4,015,514 | 7.3% |
| NOP | 3,042,523 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 13,496,941 | 24.4% |
| RETURN_VALUE | 6,733,876 | 12.2% |
| LOAD_ATTR | 3,892,716 | 7.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,758,574 | 6.8% |
| CALL_PY_EXACT_ARGS | 2,491,391 | 4.5% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 256,730 | 66.4% |
| LOAD_FAST_AND_CLEAR | 129,806 | 33.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 256,730 | 66.4% |
| LOAD_FAST_AND_CLEAR | 129,806 | 33.6% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 408,000 | 75.8% |
| POP_JUMP_IF_NONE | 118,048 | 21.9% |
| LOAD_ATTR_CLASS | 11,948 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 408,000 | 75.8% |
| LOAD_GLOBAL_MODULE | 118,048 | 21.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 11,948 | 2.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,316,924 | 16.4% |
| LOAD_FAST_LOAD_FAST | 1,032,000 | 12.9% |
| PUSH_NULL | 941,764 | 11.7% |
| POP_JUMP_IF_FALSE | 743,105 | 9.3% |
| STORE_FAST_STORE_FAST | 629,715 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,701,246 | 21.2% |
| CALL | 1,080,569 | 13.5% |
| LOAD_FAST_LOAD_FAST | 1,032,000 | 12.9% |
| LOAD_ATTR_INSTANCE_VALUE | 860,440 | 10.7% |
| BUILD_TUPLE | 821,040 | 10.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 28.1% |
| POP_JUMP_IF_TRUE | 47 | 16.5% |
| RESUME_CHECK | 40 | 14.0% |
| POP_JUMP_IF_FALSE | 40 | 14.0% |
| LOAD_ATTR_INSTANCE_VALUE | 22 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 152 | 53.3% |
| LOAD_ATTR | 68 | 23.9% |
| LOAD_GLOBAL_BUILTIN | 47 | 16.5% |
| LOAD_FAST | 7 | 2.5% |
| COMPARE_OP | 7 | 2.5% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 79,680 | 80.0% |
| CALL_PY_EXACT_ARGS | 19,920 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 79,680 | 80.0% |
| RESUME_CHECK | 19,920 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,618,155 | 24.9% |
| TO_BOOL_INT | 2,575,132 | 24.5% |
| COMPARE_OP_INT | 2,077,191 | 19.7% |
| CONTAINS_OP | 985,339 | 9.4% |
| COMPARE_OP_STR | 971,484 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,293,773 | 40.8% |
| RETURN_CONST | 1,837,462 | 17.5% |
| NOP | 793,794 | 7.5% |
| LOAD_GLOBAL_MODULE | 751,639 | 7.1% |
| LOAD_FAST_LOAD_FAST | 743,105 | 7.1% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 572,522 | 93.5% |
| LOAD_ATTR_INSTANCE_VALUE | 20,880 | 3.4% |
| LOAD_ATTR | 18,240 | 3.0% |
| RETURN_VALUE | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,617 | 26.1% |
| LOAD_GLOBAL_MODULE | 155,135 | 25.3% |
| NOP | 145,404 | 23.8% |
| LOAD_FAST_CHECK | 118,048 | 19.3% |
| RETURN_CONST | 16,800 | 2.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,629,506 | 55.7% |
| LOAD_ATTR | 537,537 | 18.4% |
| LOAD_ATTR_INSTANCE_VALUE | 482,744 | 16.5% |
| RETURN_VALUE | 220,924 | 7.6% |
| LOAD_DEREF | 39,840 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,291,077 | 44.1% |
| ENTER_EXECUTOR | 619,608 | 21.2% |
| RETURN_CONST | 537,665 | 18.4% |
| NOP | 252,938 | 8.6% |
| LOAD_CONST | 117,804 | 4.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,123,526 | 66.4% |
| TO_BOOL | 545,973 | 32.3% |
| TO_BOOL_NONE | 13,200 | 0.8% |
| COMPARE_OP_STR | 7,951 | 0.5% |
| COMPARE_OP_INT | 1,093 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680,933 | 40.2% |
| LOAD_FAST_LOAD_FAST | 547,406 | 32.4% |
| RETURN_CONST | 348,735 | 20.6% |
| LOAD_GLOBAL_MODULE | 44,123 | 2.6% |
| RETURN_VALUE | 35,780 | 2.1% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,080 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 8,160 | 66.7% |
| POP_JUMP_IF_TRUE | 4,080 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 4,080 | 50.0% |
| COPY | 4,080 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,837,462 | 35.9% |
| POP_TOP | 1,160,886 | 22.7% |
| STORE_ATTR_INSTANCE_VALUE | 1,142,376 | 22.3% |
| POP_JUMP_IF_NOT_NONE | 537,665 | 10.5% |
| POP_JUMP_IF_TRUE | 348,735 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,555,896 | 69.4% |
| EXIT_INIT_CHECK | 544,188 | 10.6% |
| INTERPRETER_EXIT | 498,408 | 9.7% |
| TO_BOOL_BOOL | 462,404 | 9.0% |
| STORE_FAST | 36,260 | 0.7% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 27,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 27,600 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,243 | 58.2% |
| LOAD_FAST_LOAD_FAST | 13,200 | 21.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,240 | 19.6% |
| STORE_ATTR | 620 | 1.0% |
| SWAP | 14 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 32,160 | 51.6% |
| LOAD_FAST_LOAD_FAST | 9,120 | 14.6% |
| LOAD_FAST | 8,167 | 13.1% |
| LOAD_CONST | 8,161 | 13.1% |
| LOAD_GLOBAL_BUILTIN | 4,080 | 6.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 39,840 | 40.0% |
| LOAD_ATTR_MODULE | 39,840 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 19,920 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 39,840 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 19,920 | 20.0% |
| LOAD_FAST | 19,920 | 20.0% |
| LOAD_DEREF | 19,920 | 20.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,488,000 | 26.6% |
| COPY | 1,948,320 | 11.6% |
| CALL | 1,939,461 | 11.5% |
| RETURN_VALUE | 1,147,193 | 6.8% |
| STORE_FAST_STORE_FAST | 792,000 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,606,568 | 39.2% |
| JUMP_BACKWARD | 4,080,000 | 24.2% |
| NOP | 2,298,684 | 13.6% |
| COPY | 1,948,080 | 11.6% |
| JUMP_FORWARD | 532,898 | 3.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 480,960 | 53.6% |
| FOR_ITER_LIST | 408,000 | 45.4% |
| COPY | 9,120 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 408,000 | 45.4% |
| GET_ITER | 408,000 | 45.4% |
| LOAD_FAST | 72,960 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 9,120 | 1.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,306,927 | 39.9% |
| COPY | 796,080 | 24.3% |
| UNPACK_SEQUENCE_TUPLE | 792,000 | 24.2% |
| STORE_FAST_STORE_FAST | 384,000 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,051,612 | 32.1% |
| STORE_FAST | 792,000 | 24.2% |
| LOAD_FAST_LOAD_FAST | 629,715 | 19.2% |
| ENTER_EXECUTOR | 408,000 | 12.4% |
| STORE_FAST_STORE_FAST | 384,000 | 11.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 406,452 | 28.1% |
| LOAD_FAST_AND_CLEAR | 256,730 | 17.8% |
| BUILD_LIST | 256,730 | 17.8% |
| ENTER_EXECUTOR | 247,610 | 17.1% |
| LOAD_FAST | 137,968 | 9.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 406,445 | 28.1% |
| LOAD_CONST | 267,774 | 18.5% |
| STORE_FAST | 256,730 | 17.8% |
| BUILD_LIST | 256,730 | 17.8% |
| FOR_ITER_LIST | 247,610 | 17.1% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,672,000 | 75.0% |
| BUILD_TUPLE | 816,000 | 16.7% |
| STORE_FAST_LOAD_FAST | 408,000 | 8.3% |
| CALL_STR_1 | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,488,000 | 91.7% |
| INTERPRETER_EXIT | 408,480 | 8.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 130,050 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 130,050 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 794,525 | 98.4% |
| LOAD_FAST_LOAD_FAST | 12,720 | 1.6% |
| BINARY_OP | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 406,452 | 50.4% |
| STORE_FAST | 384,000 | 47.6% |
| BINARY_SLICE | 12,720 | 1.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,080 | 0.5% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 72,960 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 118,048 | 99.9% |
| LOAD_FAST | 80 | 0.1% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 118,168 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 122,404 | 75.4% |
| LOAD_CONST | 35,780 | 22.1% |
| CALL_LEN | 4,080 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 158,184 | 97.5% |
| CALL_BUILTIN_CLASS | 4,080 | 2.5% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 72,000 | 88.8% |
| LOAD_CONST | 9,120 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 72,000 | 88.8% |
| CONVERT_VALUE | 9,120 | 11.2% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,160 | 66.7% |
| LOAD_FAST_LOAD_FAST | 4,080 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,160 | 66.7% |
| STORE_FAST | 4,080 | 33.3% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 72,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 72,960 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 25,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 21,840 | 84.3% |
| JUMP_FORWARD | 4,080 | 15.7% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 267,774 | 49.2% |
| LOAD_FAST | 252,414 | 46.4% |
| CALL | 24,000 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 296,334 | 54.5% |
| COPY_FREE_VARS | 247,854 | 45.5% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,000 | 73.1% |
| LOAD_CONST | 4,400 | 13.4% |
| BINARY_OP_ADD_INT | 4,080 | 12.4% |
| PUSH_NULL | 273 | 0.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 28,687 | 87.4% |
| POP_TOP | 4,080 | 12.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 69.0% |
| LOAD_FAST | 142,610 | 25.6% |
| LOAD_CONST | 9,360 | 1.7% |
| LOAD_GLOBAL_BUILTIN | 7,680 | 1.4% |
| CALL_LEN | 4,080 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 514,050 | 92.4% |
| GET_ITER | 25,920 | 4.7% |
| LOAD_FAST | 12,240 | 2.2% |
| CALL_BUILTIN_CLASS | 4,080 | 0.7% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 430,171 | 52.9% |
| LOAD_CONST | 230,604 | 28.3% |
| LOAD_FAST_LOAD_FAST | 80,164 | 9.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 36,242 | 4.5% |
| LOAD_GLOBAL_MODULE | 18,240 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 281,250 | 34.6% |
| TO_BOOL_BOOL | 225,084 | 27.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 221,715 | 27.2% |
| UNPACK_SEQUENCE_TUPLE | 36,242 | 4.5% |
| POP_TOP | 9,293 | 1.1% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 386,400 | 47.1% |
| BUILD_TUPLE | 384,000 | 46.8% |
| CALL | 24,294 | 3.0% |
| LOAD_FAST_CHECK | 11,948 | 1.5% |
| LOAD_ATTR | 9,120 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 783,120 | 95.5% |
| RETURN_VALUE | 36,242 | 4.4% |
| LOAD_FAST | 480 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 72,960 | 88.9% |
| LOAD_FAST | 9,120 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 72,960 | 88.9% |
| LOAD_FAST | 9,120 | 11.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 591,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 591,120 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 172,509 | 89.6% |
| LOAD_ATTR_INSTANCE_VALUE | 19,920 | 10.4% |
| CALL | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 156,004 | 81.1% |
| CALL_PY_EXACT_ARGS | 24,000 | 12.5% |
| LOAD_FAST | 4,080 | 2.1% |
| CALL_BUILTIN_CLASS | 4,080 | 2.1% |
| BINARY_OP_SUBTRACT_INT | 4,080 | 2.1% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 129,806 | 94.1% |
| LOAD_FAST | 8,160 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 129,806 | 94.1% |
| LOAD_GLOBAL_MODULE | 8,160 | 5.9% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 826,734 | 99.9% |
| LOAD_CONST | 480 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 224 | 0.0% |
| CALL | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 578,880 | 70.0% |
| STORE_FAST | 248,085 | 30.0% |
| TO_BOOL_NONE | 480 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 23,760 | 85.3% |
| BUILD_TUPLE | 4,080 | 14.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 19,680 | 70.7% |
| LOAD_FAST | 8,160 | 29.3% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 834,182 | 94.4% |
| LOAD_ATTR_METHOD_LAZY_DICT | 48,190 | 5.5% |
| LOAD_ATTR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 408,000 | 46.2% |
| POP_TOP | 332,614 | 37.7% |
| LOAD_FAST | 37,680 | 4.3% |
| RETURN_VALUE | 36,616 | 4.1% |
| CALL_BUILTIN_FAST | 36,242 | 4.1% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 571,835 | 91.7% |
| LOAD_CONST | 21,840 | 3.5% |
| CALL | 20,415 | 3.3% |
| RETURN_VALUE | 9,120 | 1.5% |
| RETURN_GENERATOR | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 592,250 | 95.0% |
| LOAD_CONST | 21,840 | 3.5% |
| RETURN_VALUE | 9,120 | 1.5% |
| BINARY_OP_ADD_UNICODE | 480 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 2,952,700 | 46.7% |
| LOAD_FAST | 2,491,391 | 39.4% |
| LOAD_FAST_LOAD_FAST | 421,200 | 6.7% |
| LOAD_SUPER_ATTR_METHOD | 247,854 | 3.9% |
| LOAD_GLOBAL_MODULE | 67,920 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,294,444 | 99.5% |
| MAKE_CELL | 19,920 | 0.3% |
| RETURN_GENERATOR | 12,720 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 717,086 | 45.3% |
| LOAD_ATTR_MODULE | 578,880 | 36.6% |
| LOAD_FAST | 166,766 | 10.5% |
| LOAD_CONST | 55,486 | 3.5% |
| BINARY_OP | 37,200 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,004,390 | 63.4% |
| COPY_FREE_VARS | 578,880 | 36.6% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,680 | 94.1% |
| YIELD_VALUE | 480 | 5.9% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 412,080 | 99.9% |
| LOAD_FAST | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 412,080 | 99.9% |
| LOAD_FAST | 480 | 0.1% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 990,299 | 47.6% |
| LOAD_ATTR_INSTANCE_VALUE | 652,443 | 31.4% |
| LOAD_FAST | 408,000 | 19.6% |
| LOAD_FAST_LOAD_FAST | 12,720 | 0.6% |
| CALL_BUILTIN_FAST | 9,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,077,191 | 99.9% |
| POP_JUMP_IF_TRUE | 1,093 | 0.1% |
| COMPARE_OP | 92 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 953,981 | 95.6% |
| LOAD_CONST | 39,600 | 4.0% |
| LOAD_FAST | 4,080 | 0.4% |
| COMPARE_OP | 14 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 971,484 | 97.4% |
| LOAD_FAST | 9,120 | 0.9% |
| COPY | 9,120 | 0.9% |
| POP_JUMP_IF_TRUE | 7,951 | 0.8% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,488,000 | 99.8% |
| GET_ITER | 8,160 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,488,000 | 99.8% |
| POP_TOP | 8,160 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 908,748 | 78.5% |
| SWAP | 247,610 | 21.4% |
| JUMP_BACKWARD | 1,133 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 408,000 | 35.2% |
| STORE_FAST | 370,875 | 32.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 259,612 | 22.4% |
| LOAD_FAST | 118,048 | 10.2% |
| RETURN_CONST | 668 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 21,480 | 97.9% |
| JUMP_BACKWARD | 454 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 21,794 | 99.4% |
| RETURN_CONST | 80 | 0.4% |
| LOAD_FAST | 60 | 0.3% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,160 | 92.7% |
| LOAD_FAST | 480 | 5.5% |
| JUMP_BACKWARD | 160 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,640 | 98.2% |
| RETURN_CONST | 160 | 1.8% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 36,242 | 82.5% |
| LOAD_ATTR_MODULE | 7,680 | 17.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,974 | 72.8% |
| LOAD_FAST_CHECK | 11,948 | 27.2% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,496,941 | 91.3% |
| LOAD_FAST_LOAD_FAST | 860,440 | 5.8% |
| COPY | 406,445 | 2.7% |
| LOAD_ATTR_INSTANCE_VALUE | 16,225 | 0.1% |
| RETURN_VALUE | 9,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,454,727 | 23.4% |
| LOAD_FAST | 2,253,249 | 15.2% |
| LOAD_ATTR | 1,176,639 | 8.0% |
| CONTAINS_OP | 985,332 | 6.7% |
| LOAD_GLOBAL_MODULE | 974,414 | 6.6% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 182,168 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,484 | 39.8% |
| CALL | 61,494 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,190 | 26.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,454,727 | 88.3% |
| LOAD_FAST | 365,235 | 9.3% |
| LOAD_ATTR | 37,222 | 1.0% |
| LOAD_ATTR_SLOT | 37,200 | 1.0% |
| LOAD_CONST | 9,600 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,384,891 | 35.4% |
| CALL | 1,000,380 | 25.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 834,182 | 21.3% |
| LOAD_CONST | 512,384 | 13.1% |
| LOAD_FAST_LOAD_FAST | 160,855 | 4.1% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,758,574 | 66.9% |
| LOAD_ATTR_INSTANCE_VALUE | 840,866 | 15.0% |
| LOAD_FAST_LOAD_FAST | 578,880 | 10.3% |
| BINARY_SUBSCR | 408,000 | 7.3% |
| LOAD_GLOBAL_MODULE | 20,400 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,952,700 | 52.6% |
| LOAD_FAST | 1,371,454 | 24.4% |
| CALL_PY_WITH_DEFAULTS | 717,086 | 12.8% |
| LOAD_FAST_LOAD_FAST | 457,920 | 8.2% |
| LOAD_CONST | 68,206 | 1.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,232,333 | 62.5% |
| ENTER_EXECUTOR | 739,598 | 37.5% |
| LOAD_ATTR | 122 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,289,680 | 65.4% |
| CALL_PY_WITH_DEFAULTS | 578,880 | 29.4% |
| STORE_DEREF | 39,840 | 2.0% |
| LOAD_CONST | 22,800 | 1.2% |
| LOAD_FAST | 19,920 | 1.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 605,760 | 70.0% |
| LOAD_FAST_LOAD_FAST | 259,612 | 30.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 578,880 | 66.9% |
| UNARY_INVERT | 259,612 | 30.0% |
| RETURN_VALUE | 9,120 | 1.1% |
| LOAD_CONST | 9,120 | 1.1% |
| LOAD_FAST_LOAD_FAST | 4,080 | 0.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 341,921 | 64.9% |
| LOAD_FAST | 164,416 | 31.2% |
| RETURN_VALUE | 19,920 | 3.8% |
| LOAD_GLOBAL_MODULE | 480 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 517,785 | 98.3% |
| TO_BOOL_BOOL | 8,960 | 1.7% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 37,200 | 80.3% |
| CALL_BUILTIN_FAST | 9,120 | 19.7% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,923,534 | 49.3% |
| LOAD_FAST | 608,880 | 15.6% |
| LOAD_GLOBAL_BUILTIN | 392,160 | 10.0% |
| STORE_FAST | 366,658 | 9.4% |
| NOP | 362,516 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,938,126 | 49.7% |
| LOAD_DEREF | 881,214 | 22.6% |
| CALL_ISINSTANCE | 591,120 | 15.1% |
| LOAD_GLOBAL_BUILTIN | 392,160 | 10.0% |
| LOAD_GLOBAL_MODULE | 31,920 | 0.8% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,084,447 | 25.1% |
| RESUME_CHECK | 1,506,803 | 18.2% |
| LOAD_ATTR_INSTANCE_VALUE | 974,414 | 11.7% |
| NOP | 910,925 | 11.0% |
| POP_JUMP_IF_FALSE | 751,639 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,866,446 | 22.5% |
| LOAD_FAST_LOAD_FAST | 1,316,924 | 15.9% |
| LOAD_ATTR_MODULE | 1,232,333 | 14.9% |
| LOAD_FAST | 1,110,864 | 13.4% |
| COMPARE_OP_STR | 953,981 | 11.5% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 41,280 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 839,934 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 588,000 | 70.0% |
| CALL_PY_EXACT_ARGS | 247,854 | 29.5% |
| LOAD_FAST | 4,080 | 0.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 7,994,124 | 35.8% |
| CALL_PY_EXACT_ARGS | 6,294,444 | 28.1% |
| FOR_ITER_GEN | 4,488,000 | 20.1% |
| CALL_PY_WITH_DEFAULTS | 1,004,390 | 4.5% |
| COPY_FREE_VARS | 885,414 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,751,685 | 57.0% |
| POP_TOP | 4,896,480 | 21.9% |
| LOAD_GLOBAL_BUILTIN | 1,923,534 | 8.6% |
| LOAD_GLOBAL_MODULE | 1,506,803 | 6.7% |
| NOP | 723,600 | 3.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,656,693 | 65.7% |
| LOAD_FAST_LOAD_FAST | 432,414 | 17.2% |
| SWAP | 406,445 | 16.1% |
| LOAD_ATTR_INSTANCE_VALUE | 12,240 | 0.5% |
| STORE_FAST_LOAD_FAST | 9,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,142,376 | 45.3% |
| LOAD_FAST | 640,452 | 25.4% |
| LOAD_GLOBAL_MODULE | 398,574 | 15.8% |
| LOAD_CONST | 153,119 | 6.1% |
| LOAD_FAST_LOAD_FAST | 90,720 | 3.6% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,200 | 80.3% |
| LOAD_FAST_LOAD_FAST | 9,120 | 19.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,320 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 578,880 | 90.1% |
| LOAD_FAST | 30,805 | 4.8% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 3.8% |
| CALL | 7,680 | 1.2% |
| LOAD_CONST | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 580,652 | 90.4% |
| RETURN_CONST | 21,840 | 3.4% |
| LOAD_GLOBAL_MODULE | 19,920 | 3.1% |
| LOAD_CONST | 19,920 | 3.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 897,017 | 23.1% |
| CALL_ISINSTANCE | 591,120 | 15.2% |
| CALL | 512,893 | 13.2% |
| LOAD_FAST | 501,860 | 12.9% |
| RETURN_VALUE | 491,370 | 12.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,618,155 | 67.3% |
| POP_JUMP_IF_TRUE | 1,123,526 | 28.9% |
| UNARY_NOT | 148,996 | 3.8% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,417,372 | 55.0% |
| LOAD_FAST | 578,880 | 22.5% |
| BINARY_OP | 578,880 | 22.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,575,132 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 256,014 | 89.7% |
| LOAD_ATTR_INSTANCE_VALUE | 29,520 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 285,534 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 135,253 | 80.1% |
| LOAD_FAST | 19,920 | 11.8% |
| COPY | 9,120 | 5.4% |
| WITH_EXCEPT_START | 4,080 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 480 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 155,653 | 92.2% |
| POP_JUMP_IF_TRUE | 13,200 | 7.8% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 792,000 | 95.6% |
| CALL_BUILTIN_FAST | 36,242 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 792,000 | 95.6% |
| STORE_FAST | 36,242 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 412,080 | 31.4% |
| LOAD_FAST_CHECK | 408,000 | 31.1% |
| FOR_ITER_LIST | 259,612 | 19.8% |
| CALL_BUILTIN_FAST | 221,715 | 16.9% |
| CALL | 5,520 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,306,927 | 99.7% |
| LOAD_FAST | 4,560 | 0.3% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 50.0% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 50.0% |
| LOAD_CONST | 480 | 50.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 480 | 100.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 64.3% |
| COPY | 125 | 33.5% |
| TO_BOOL | 8 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 240 | 64.3% |
| POP_JUMP_IF_FALSE | 133 | 35.7% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 11 | 73.3% |
| CACHE | 4 | 26.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15 | 100.0% |


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
| specialization.deferred |       443780 | 51.1% |
|          hit |       423768 | 48.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 230 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 230 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        20887 | 3.1% |
|          hit |       642332 | 96.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 7 | 3.4% |
| Failure | 200 | 96.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 120 | 60.0% |
| other | 80 | 40.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1061419 | 13.1% |
|          hit |      7062625 | 86.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 13 | 1.2% |
| Failure | 1,055 | 98.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 324 | 30.7% |
| sequence | 231 | 21.9% |
| tuple | 220 | 20.9% |
| set | 200 | 19.0% |
| other | 80 | 7.6% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3497286 | 72.7% |
|          hit |      1313115 | 27.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 47 | 2.8% |
| Failure | 1,635 | 97.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 786 | 48.1% |
| or | 440 | 26.9% |
| remainder | 209 | 12.8% |
| add different types | 160 | 9.8% |
| add other | 40 | 2.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      7016535 | 31.4% |
| specialization.deopt |           60 | 0.0% |
|          hit |     15286959 | 68.5% |
|         miss |         4140 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 202 | 2.3% |
| Failure | 8,432 | 97.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,461 | 29.2% |
| cfunc noargs | 1,591 | 18.9% |
| class no vectorcall | 1,199 | 14.2% |
| meth descr varargs keywords | 841 | 10.0% |
| other | 360 | 4.3% |
| class mutable | 338 | 4.0% |
| bound method | 284 | 3.4% |
| cfunc varargs keywords | 258 | 3.1% |
| operator wrapper | 240 | 2.8% |
| cfunc varargs | 240 | 2.8% |
| meth descr method fastcall keywords | 200 | 2.4% |
| cmethod | 200 | 2.4% |
| wrong number arguments | 160 | 1.9% |
| method wrapper | 60 | 0.7% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       286743 | 8.5% |
| specialization.deopt |           92 | 0.0% |
|          hit |      3070294 | 91.3% |
|         miss |         5757 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 163 | 26.8% |
| Failure | 446 | 73.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 215 | 48.2% |
| float long | 151 | 33.9% |
| big int | 80 | 17.9% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       914400 | 13.9% |
|          hit |      5684385 | 86.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 440 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 140 | 31.8% |
| other | 140 | 31.8% |
| callable | 80 | 18.2% |
| itertools | 80 | 18.2% |


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
| specialization.deferred |      5217420 | 15.5% |
| specialization.deopt |         4148 | 0.0% |
|          hit |     28180900 | 83.8% |
|         miss |       228884 | 0.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,495 | 45.4% |
| Failure | 5,413 | 54.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,322 | 24.4% |
| shadowed | 1,014 | 18.7% |
| not managed dict | 982 | 18.1% |
| non overriding descriptor | 574 | 10.6% |
| class attr descriptor | 360 | 6.7% |
| metaclass attribute | 280 | 5.2% |
| class method obj | 280 | 5.2% |
| has managed dict | 240 | 4.4% |
| non object slot | 160 | 3.0% |
| class attr simple | 101 | 1.9% |
| mutable class | 80 | 1.5% |
| overridden | 20 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           86 | 0.0% |
| specialization.deopt |            6 | 0.0% |
|          hit |     13919684 | 100.0% |
|         miss |         2156 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 205 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       881214 | 100.0% |


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
| specialization.deferred |        61688 | 2.3% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      2419442 | 92.0% |
|         miss |       148120 | 5.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,789 | 81.8% |
| Failure | 620 | 18.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 400 | 64.5% |
| class attr simple | 140 | 22.6% |
| no dict | 80 | 12.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2139729 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 178,360,783 | 56.0% |
| Not specialized | 40,081,500 | 12.6% |
| Specialized | 100,005,276 | 31.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 36,893,488,147,419,103,230 | 100.0% |
| CALL | 7,016,535 | 0.0% |
| LOAD_ATTR | 5,217,420 | 0.0% |
| BINARY_OP | 3,497,286 | 0.0% |
| TO_BOOL | 1,061,419 | 0.0% |
| FOR_ITER | 914,400 | 0.0% |
| BINARY_SUBSCR | 443,780 | 0.0% |
| COMPARE_OP | 286,743 | 0.0% |
| STORE_ATTR | 61,688 | 0.0% |
| STORE_SUBSCR | 20,887 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 159,064 | 40.9% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 38.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,700 | 15.6% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| COMPARE_OP_INT | 5,757 | 1.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,140 | 1.1% |
| LOAD_GLOBAL_MODULE | 2,156 | 0.6% |
| RESUME_CHECK | 2 | 0.0% |
| RESUME | 2 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 8,053,168 | 35.5% |
| Calls to Python functions inlined | 14,624,657 | 64.5% |
| Calls via PyEval_EvalFrame (total) | 8,053,168 | 35.5% |
| Calls via PyEval_EvalFrame (vector) | 7,640,128 | 33.7% |
| Calls via PyEval_EvalFrame (generator) | 413,040 | 1.8% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 7,640,128 | 33.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 442,080 | 1.9% |
| Calls via PyEval_EvalFrame (function ex) | 400,440 | 1.8% |
| Calls via PyEval_EvalFrame (api) | 342,204 | 1.5% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 18,312,813 | 80.8% |
| Frame objects created | 27,890 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,619,268 | 42.1% |
| Frees to freelist | 11,620,250 |  |
| Allocations | 15,974,311 | 57.9% |
| Allocations to 512 bytes | 15,839,152 | 57.4% |
| Allocations to 4 kbytes | 60,747 | 0.2% |
| Allocations over 4 kbytes | 74,412 | 0.3% |
| Frees | 16,738,933 |  |
| New values | 59,520 |  |
| Interpreter increfs | 128,239,073 | 72.5% |
| Interpreter decrefs | 138,002,469 | 68.3% |
| Increfs | 48,717,115 | 27.5% |
| Decrefs | 64,105,469 | 31.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 6,234,794 |  |
| Method cache misses | 34,896 |  |
| Method cache collisions | 48,310 |  |
| Method cache dunder hits | 7,007,397 |  |
| Method cache dunder misses | 13,422 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 14 | 336 | 101,866 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 40 |


</details>

---
Stats gathered on: 2023-09-27
