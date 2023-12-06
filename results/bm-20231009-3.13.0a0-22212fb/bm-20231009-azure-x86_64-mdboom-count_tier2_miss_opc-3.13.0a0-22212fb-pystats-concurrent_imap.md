
# Pystats results

- benchmark: concurrent_imap
- fork: mdboom
- ref: count-tier2-miss-opcodes
- commit hash: 22212fb
- commit date: 2023-10-09T12:01:25-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 74,381,034 | 17.6% | 17.6% |  |
| RESUME_CHECK | 27,556,788 | 6.5% | 24.1% | 0.0% |
| STORE_FAST | 21,911,989 | 5.2% | 29.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,102,774 | 4.3% | 33.6% | 0.9% |
| POP_TOP | 17,862,615 | 4.2% | 37.8% |  |
| RETURN_VALUE | 16,314,921 | 3.9% | 41.7% |  |
| POP_JUMP_IF_FALSE | 14,165,038 | 3.4% | 45.0% |  |
| JUMP_BACKWARD | 13,447,084 | 3.2% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 12,500,071 | 3.0% | 51.2% | 0.1% |
| LOAD_FAST_LOAD_FAST | 11,562,638 | 2.7% | 53.9% |  |
| LOAD_CONST | 11,407,485 | 2.7% | 56.6% |  |
| CALL_PY_EXACT_ARGS | 9,168,637 | 2.2% | 58.8% |  |
| INTERPRETER_EXIT | 8,872,180 | 2.1% | 60.9% |  |
| CALL | 8,631,779 | 2.0% | 62.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,200,273 | 1.9% | 64.9% | 0.7% |
| LOAD_ATTR | 7,595,609 | 1.8% | 66.6% |  |
| FOR_ITER_LIST | 7,434,768 | 1.8% | 68.4% |  |
| NOP | 7,394,256 | 1.7% | 70.2% |  |
| RETURN_CONST | 6,825,813 | 1.6% | 71.8% |  |
| LOAD_GLOBAL_BUILTIN | 6,421,882 | 1.5% | 73.3% |  |
| PUSH_NULL | 5,501,258 | 1.3% | 74.6% |  |
| COPY | 5,382,328 | 1.3% | 75.9% |  |
| YIELD_VALUE | 5,184,960 | 1.2% | 77.1% |  |
| BINARY_OP | 5,167,679 | 1.2% | 78.3% |  |
| TO_BOOL_BOOL | 5,165,499 | 1.2% | 79.5% |  |
| STORE_FAST_LOAD_FAST | 4,847,040 | 1.1% | 80.7% |  |
| FOR_ITER_GEN | 4,760,640 | 1.1% | 81.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,753,491 | 1.1% | 82.9% |  |
| TO_BOOL_INT | 3,817,694 | 0.9% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,731,996 | 0.9% | 84.7% |  |
| STORE_FAST_STORE_FAST | 3,604,515 | 0.9% | 85.6% |  |
| BUILD_TUPLE | 3,193,328 | 0.8% | 86.3% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,168,906 | 0.7% | 87.1% | 4.7% |
| COMPARE_OP_INT | 2,774,821 | 0.7% | 87.7% | 0.2% |
| LOAD_ATTR_MODULE | 2,664,021 | 0.6% | 88.4% |  |
| CALL_PY_WITH_DEFAULTS | 2,167,244 | 0.5% | 88.9% |  |
| POP_JUMP_IF_TRUE | 2,020,244 | 0.5% | 89.4% |  |
| SWAP | 1,927,526 | 0.5% | 89.8% |  |
| CALL_FUNCTION_EX | 1,810,148 | 0.4% | 90.2% |  |
| GET_ITER | 1,756,399 | 0.4% | 90.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,589,475 | 0.4% | 91.0% |  |
| BEFORE_WITH | 1,367,676 | 0.3% | 91.4% |  |
| CALL_BUILTIN_FAST | 1,351,742 | 0.3% | 91.7% |  |
| LOAD_DEREF | 1,345,882 | 0.3% | 92.0% |  |
| COPY_FREE_VARS | 1,308,802 | 0.3% | 92.3% |  |
| CONTAINS_OP | 1,293,119 | 0.3% | 92.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,265,057 | 0.3% | 92.9% |  |
| BUILD_MAP | 1,246,283 | 0.3% | 93.2% |  |
| JUMP_FORWARD | 1,241,721 | 0.3% | 93.5% |  |
| LOAD_SUPER_ATTR_METHOD | 1,237,162 | 0.3% | 93.8% |  |
| UNARY_INVERT | 1,234,337 | 0.3% | 94.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,226,637 | 0.3% | 94.4% |  |
| TO_BOOL | 1,179,120 | 0.3% | 94.7% |  |
| BUILD_LIST | 1,110,847 | 0.3% | 94.9% |  |
| COMPARE_OP_STR | 1,108,247 | 0.3% | 95.2% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,101,654 | 0.3% | 95.4% |  |
| FOR_ITER | 976,760 | 0.2% | 95.7% |  |
| CALL_BUILTIN_CLASS | 956,795 | 0.2% | 95.9% |  |
| STORE_SUBSCR_DICT | 930,274 | 0.2% | 96.1% |  |
| UNPACK_SEQUENCE_TUPLE | 877,017 | 0.2% | 96.3% |  |
| CALL_ISINSTANCE | 874,079 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 852,537 | 0.2% | 96.7% |  |
| BINARY_OP_ADD_INT | 834,232 | 0.2% | 96.9% |  |
| POP_JUMP_IF_NONE | 820,996 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 773,206 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 773,206 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 757,280 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 724,043 | 0.2% | 97.8% |  |
| LOAD_FAST_CHECK | 618,982 | 0.1% | 98.0% |  |
| LIST_APPEND | 604,393 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 562,285 | 0.1% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 557,850 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 476,666 | 0.1% | 98.5% |  |
| CALL_LEN | 466,402 | 0.1% | 98.6% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.7% |  |
| COMPARE_OP | 425,664 | 0.1% | 98.8% |  |
| DICT_MERGE | 422,880 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 401,963 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 356,784 | 0.1% | 99.1% |  |
| LIST_EXTEND | 349,104 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,948 | 0.1% | 99.3% |  |
| CALL_KW | 261,015 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 247,600 | 0.1% | 99.4% |  |
| UNARY_NOT | 206,140 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 195,249 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 187,091 | 0.0% | 99.5% |  |
| TO_BOOL_NONE | 180,322 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_FLOAT | 174,674 | 0.0% | 99.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 106,246 | 0.0% | 99.6% | 4.1% |
| MAKE_CELL | 103,200 | 0.0% | 99.7% |  |
| STORE_DEREF | 103,200 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,697 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,417 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,815 | 0.0% | 99.9% |  |
| DELETE_SUBSCR | 58,570 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| POP_EXCEPT | 36,286 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 36,286 | 0.0% | 99.9% |  |
| IS_OP | 34,872 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 32,640 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 31,966 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 100.0% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| IMPORT_NAME | 24,480 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,776 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 21,120 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 20,160 | 0.0% | 100.0% |  |
| BINARY_SLICE | 13,920 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 13,920 | 0.0% | 100.0% |  |
| RERAISE | 12,960 | 0.0% | 100.0% |  |
| END_FOR | 8,640 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,640 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,320 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 1,920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 792 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 208 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,376,778 | 3.9% | 3.9% |
| RESUME_CHECK LOAD_FAST | 15,433,632 | 3.7% | 7.5% |
| STORE_FAST LOAD_FAST | 9,499,710 | 2.2% | 9.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,134,077 | 2.2% | 11.9% |
| CACHE RESUME_CHECK | 8,789,135 | 2.1% | 14.0% |
| LOAD_FAST RETURN_VALUE | 7,942,549 | 1.9% | 15.9% |
| RETURN_VALUE INTERPRETER_EXIT | 7,784,282 | 1.8% | 17.7% |
| POP_TOP JUMP_BACKWARD | 6,510,164 | 1.5% | 19.3% |
| JUMP_BACKWARD FOR_ITER_LIST | 5,913,521 | 1.4% | 20.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,879,621 | 1.4% | 22.1% |
| LOAD_FAST LOAD_ATTR | 5,864,364 | 1.4% | 23.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,809,935 | 1.4% | 24.8% |
| POP_TOP LOAD_FAST | 5,527,312 | 1.3% | 26.1% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.2% | 27.4% |
| RETURN_CONST POP_TOP | 4,829,819 | 1.1% | 28.5% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.1% | 29.6% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.1% | 30.8% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.1% | 31.9% |
| NOP LOAD_FAST | 4,705,504 | 1.1% | 33.0% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.0% | 34.0% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 4,320,000 | 1.0% | 35.0% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 4,320,000 | 1.0% | 36.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,140,797 | 1.0% | 37.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,126,929 | 1.0% | 38.0% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,817,694 | 0.9% | 38.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,812,637 | 0.9% | 39.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,592,218 | 0.8% | 40.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,556,627 | 0.8% | 41.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,962,851 | 0.7% | 42.2% |
| LOAD_FAST LOAD_CONST | 2,916,597 | 0.7% | 42.9% |
| STORE_FAST NOP | 2,829,111 | 0.7% | 43.6% |
| LOAD_CONST LOAD_CONST | 2,815,575 | 0.7% | 44.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,772,521 | 0.7% | 44.9% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,769,966 | 0.7% | 45.6% |
| LOAD_FAST PUSH_NULL | 2,753,642 | 0.7% | 46.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,749,134 | 0.7% | 46.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,681,481 | 0.6% | 47.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,673,151 | 0.6% | 48.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,663,924 | 0.6% | 48.7% |
| PUSH_NULL LOAD_FAST | 2,595,175 | 0.6% | 49.4% |
| LOAD_ATTR LOAD_FAST | 2,549,287 | 0.6% | 50.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,484,813 | 0.6% | 50.6% |
| CALL STORE_FAST | 2,483,397 | 0.6% | 51.1% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,322,315 | 0.5% | 51.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,283,638 | 0.5% | 52.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,153,131 | 0.5% | 52.7% |
| BINARY_OP COPY | 2,095,456 | 0.5% | 53.2% |
| COPY TO_BOOL_INT | 2,095,456 | 0.5% | 53.7% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 54.2% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 54.7% |
| LOAD_CONST CALL | 1,947,766 | 0.5% | 55.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,944,790 | 0.5% | 55.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,856,486 | 0.4% | 56.0% |
| CALL RETURN_VALUE | 1,837,919 | 0.4% | 56.5% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,788,304 | 0.4% | 56.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,691,981 | 0.4% | 57.3% |
| CALL POP_TOP | 1,683,062 | 0.4% | 57.7% |
| RETURN_VALUE STORE_FAST | 1,679,027 | 0.4% | 58.1% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,604,492 | 0.4% | 58.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,584,195 | 0.4% | 58.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,571,613 | 0.4% | 59.2% |
| PUSH_NULL CALL | 1,515,895 | 0.4% | 59.6% |
| LOAD_CONST COMPARE_OP_INT | 1,511,216 | 0.4% | 59.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,510,871 | 0.4% | 60.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,506,190 | 0.4% | 60.6% |
| RETURN_VALUE RETURN_VALUE | 1,444,763 | 0.3% | 61.0% |
| LOAD_FAST_LOAD_FAST CALL | 1,415,581 | 0.3% | 61.3% |
| POP_TOP RETURN_CONST | 1,415,123 | 0.3% | 61.6% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,268 | 0.3% | 62.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,369,775 | 0.3% | 62.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,367,141 | 0.3% | 62.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,347,049 | 0.3% | 62.9% |
| NOP LOAD_GLOBAL_MODULE | 1,313,617 | 0.3% | 63.3% |
| COPY_FREE_VARS RESUME_CHECK | 1,308,802 | 0.3% | 63.6% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,306,125 | 0.3% | 63.9% |
| LOAD_DEREF LOAD_FAST | 1,304,362 | 0.3% | 64.2% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,304,362 | 0.3% | 64.5% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,293,119 | 0.3% | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,293,111 | 0.3% | 65.1% |
| POP_TOP LOAD_CONST | 1,289,769 | 0.3% | 65.4% |
| LOAD_FAST BUILD_TUPLE | 1,285,919 | 0.3% | 65.7% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,262,363 | 0.3% | 66.0% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,237,162 | 0.3% | 66.3% |
| UNARY_INVERT BINARY_OP | 1,234,337 | 0.3% | 66.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,222,282 | 0.3% | 66.9% |
| FOR_ITER_LIST STORE_FAST | 1,220,303 | 0.3% | 67.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,189,218 | 0.3% | 67.5% |
| LOAD_CONST LOAD_FAST | 1,186,177 | 0.3% | 67.7% |
| GET_ITER FOR_ITER_LIST | 1,160,566 | 0.3% | 68.0% |
| POP_TOP NOP | 1,157,574 | 0.3% | 68.3% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,155,536 | 0.3% | 68.6% |
| LOAD_FAST TO_BOOL | 1,138,213 | 0.3% | 68.8% |
| LOAD_FAST GET_ITER | 1,105,687 | 0.3% | 69.1% |
| RETURN_VALUE POP_TOP | 1,096,494 | 0.3% | 69.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,085,691 | 0.3% | 69.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,081,187 | 0.3% | 69.9% |
| POP_JUMP_IF_FALSE POP_TOP | 1,080,006 | 0.3% | 70.1% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,078,872 | 0.3% | 70.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,078,458 | 0.3% | 70.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,068,379 | 0.3% | 70.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 13,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 13,920 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,789,135 | 99.0% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 940,268 | 68.7% |
| RETURN_VALUE | 361,163 | 26.4% |
| LOAD_GLOBAL_MODULE | 61,925 | 4.5% |
| CALL | 4,320 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,193 | 73.3% |
| STORE_FAST | 365,483 | 26.7% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 20,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,640 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 432,000 | 90.6% |
| LOAD_CONST | 44,446 | 9.3% |
| BINARY_SUBSCR | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.6% |
| STORE_FAST | 44,446 | 9.3% |
| BINARY_SUBSCR | 220 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 28,126 | 88.0% |
| LOAD_ATTR_MODULE | 3,840 | 12.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 31,966 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,325 | 48.4% |
| CALL | 20,645 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,599 | 16.4% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,605 | 77.9% |
| RETURN_CONST | 7,685 | 13.1% |
| LOAD_FAST | 5,280 | 9.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 4,320 | 50.0% |
| LOAD_FAST | 4,320 | 50.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 773,206 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 773,206 | 100.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 21,120 | 50.6% |
| LOAD_FAST | 20,640 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 31,200 | 74.7% |
| BUILD_STRING | 10,560 | 25.3% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,105,687 | 63.0% |
| STORE_FAST_LOAD_FAST | 432,000 | 24.6% |
| CALL_BUILTIN_CLASS | 198,552 | 11.3% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,160,566 | 66.1% |
| LOAD_FAST_AND_CLEAR | 371,241 | 21.1% |
| FOR_ITER_RANGE | 193,392 | 11.0% |
| FOR_ITER | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,784,282 | 87.7% |
| RETURN_CONST | 654,938 | 7.4% |
| YIELD_VALUE | 432,960 | 4.9% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 44,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 28,320 | 64.1% |
| STORE_FAST | 10,560 | 23.9% |
| LOAD_FAST | 5,280 | 12.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,829,111 | 38.3% |
| POP_TOP | 1,157,574 | 15.7% |
| RESUME_CHECK | 1,012,319 | 13.7% |
| POP_JUMP_IF_FALSE | 988,140 | 13.4% |
| JUMP_BACKWARD | 816,000 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,705,504 | 63.6% |
| LOAD_GLOBAL_MODULE | 1,313,617 | 17.8% |
| LOAD_GLOBAL_BUILTIN | 532,615 | 7.2% |
| LOAD_FAST_LOAD_FAST | 437,280 | 5.9% |
| LOAD_CONST | 396,960 | 5.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 23,806 | 65.6% |
| COPY | 8,640 | 23.8% |
| POP_TOP | 3,840 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 23,806 | 65.6% |
| RERAISE | 8,640 | 23.8% |
| JUMP_FORWARD | 3,840 | 10.6% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,184,960 | 29.0% |
| RETURN_CONST | 4,829,819 | 27.0% |
| CALL | 1,683,062 | 9.4% |
| RETURN_VALUE | 1,096,494 | 6.1% |
| POP_JUMP_IF_FALSE | 1,080,006 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,510,164 | 36.4% |
| LOAD_FAST | 5,527,312 | 30.9% |
| RETURN_CONST | 1,415,123 | 7.9% |
| LOAD_CONST | 1,289,769 | 7.2% |
| NOP | 1,157,574 | 6.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 28,126 | 77.5% |
| RERAISE | 4,320 | 11.9% |
| CALL_KW | 3,840 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 28,126 | 77.5% |
| WITH_EXCEPT_START | 4,320 | 11.9% |
| LOAD_GLOBAL_MODULE | 3,840 | 10.6% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,753,642 | 50.1% |
| LOAD_ATTR_MODULE | 1,691,981 | 30.8% |
| LOAD_ATTR | 961,435 | 17.5% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,595,175 | 47.2% |
| CALL | 1,515,895 | 27.6% |
| LOAD_FAST_LOAD_FAST | 1,046,514 | 19.0% |
| LOAD_CONST | 240,379 | 4.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 48,575 | 0.9% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 13,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,320 | 31.0% |
| LOAD_FAST | 4,320 | 31.0% |
| STORE_FAST | 4,320 | 31.0% |
| CALL_METHOD_DESCRIPTOR_O | 960 | 6.9% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,942,549 | 48.7% |
| CALL | 1,837,919 | 11.3% |
| RETURN_VALUE | 1,444,763 | 8.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,155,536 | 7.1% |
| CALL_FUNCTION_EX | 948,908 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,784,282 | 47.7% |
| STORE_FAST | 1,679,027 | 10.3% |
| RETURN_VALUE | 1,444,763 | 8.9% |
| POP_TOP | 1,096,494 | 6.7% |
| LOAD_FAST_LOAD_FAST | 861,119 | 5.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,696 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.3% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| LOAD_FAST | 8 | 0.0% |
| STORE_SUBSCR_DICT | 8 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,138,213 | 96.5% |
| LOAD_ATTR_INSTANCE_VALUE | 39,854 | 3.4% |
| TO_BOOL | 1,046 | 0.1% |
| LOAD_ATTR | 4 | 0.0% |
| RETURN_VALUE | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 627,253 | 53.2% |
| POP_JUMP_IF_FALSE | 550,816 | 46.7% |
| TO_BOOL | 1,046 | 0.1% |
| TO_BOOL_BOOL | 4 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 1 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 861,119 | 69.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 373,218 | 30.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,234,337 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 206,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 206,140 | 100.0% |


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 4,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 4,320 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,769,966 | 53.6% |
| UNARY_INVERT | 1,234,337 | 23.9% |
| POP_JUMP_IF_FALSE | 861,119 | 16.7% |
| LOAD_ATTR | 197,169 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,095,456 | 40.5% |
| STORE_FAST | 1,058,288 | 20.5% |
| UNARY_INVERT | 861,119 | 16.7% |
| TO_BOOL_INT | 861,119 | 16.7% |
| BUILD_TUPLE | 186,609 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 371,241 | 33.4% |
| JUMP_FORWARD | 361,163 | 32.5% |
| LOAD_FAST | 187,091 | 16.8% |
| POP_TOP | 174,072 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 373,643 | 33.6% |
| SWAP | 371,241 | 33.4% |
| STORE_FAST | 362,123 | 32.6% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 432,000 | 34.7% |
| LOAD_FAST | 396,960 | 31.9% |
| RESUME_CHECK | 368,843 | 29.6% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.1% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 801,323 | 64.3% |
| BUILD_TUPLE | 432,000 | 34.7% |
| STORE_FAST | 12,960 | 1.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,640 | 66.2% |
| FORMAT_SIMPLE | 10,560 | 33.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 66.2% |
| RETURN_VALUE | 10,560 | 33.8% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,285,919 | 40.3% |
| LOAD_FAST_LOAD_FAST | 870,240 | 27.3% |
| BUILD_MAP | 432,000 | 13.5% |
| RETURN_VALUE | 384,000 | 12.0% |
| BINARY_OP | 186,609 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 864,000 | 27.1% |
| CALL | 862,079 | 27.0% |
| BUILD_MAP | 432,000 | 13.5% |
| STORE_FAST | 384,000 | 12.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 12.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,947,766 | 22.6% |
| PUSH_NULL | 1,515,895 | 17.6% |
| LOAD_FAST_LOAD_FAST | 1,415,581 | 16.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,078,458 | 12.5% |
| BUILD_TUPLE | 862,079 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,483,397 | 28.8% |
| RETURN_VALUE | 1,837,919 | 21.3% |
| POP_TOP | 1,683,062 | 19.5% |
| LOAD_FAST | 767,734 | 8.9% |
| TO_BOOL_BOOL | 546,066 | 6.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,268 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,908 | 52.4% |
| RESUME_CHECK | 401,280 | 22.2% |
| CALL_BUILTIN_CLASS | 384,000 | 21.2% |
| POP_TOP | 71,520 | 4.0% |
| STORE_FAST | 4,320 | 0.2% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 261,015 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 209,112 | 80.1% |
| LOAD_FAST | 21,600 | 8.3% |
| RETURN_VALUE | 15,840 | 6.1% |
| STORE_FAST | 10,560 | 4.0% |
| PUSH_EXC_INFO | 3,840 | 1.5% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 424,885 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 404 | 0.1% |
| COMPARE_OP | 292 | 0.1% |
| COMPARE_OP_INT | 68 | 0.0% |
| LOAD_GLOBAL_MODULE | 11 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 425,243 | 99.9% |
| COMPARE_OP | 292 | 0.1% |
| COMPARE_OP_INT | 115 | 0.0% |
| COMPARE_OP_STR | 11 | 0.0% |
| POP_JUMP_IF_TRUE | 3 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,293,111 | 100.0% |
| LOAD_ATTR | 8 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,293,119 | 100.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 10,560 | 50.0% |
| CALL_BUILTIN_FAST | 10,560 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 21,120 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,095,456 | 38.9% |
| STORE_FAST | 1,972,320 | 36.6% |
| LOAD_CONST | 825,600 | 15.3% |
| LOAD_FAST | 442,560 | 8.2% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,095,456 | 38.9% |
| STORE_FAST | 1,972,800 | 36.7% |
| STORE_FAST_STORE_FAST | 820,320 | 15.2% |
| LOAD_ATTR_INSTANCE_VALUE | 431,984 | 8.0% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 861,119 | 65.8% |
| CALL_ALLOC_AND_ENTER_INIT | 361,163 | 27.6% |
| CACHE | 82,080 | 6.3% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,308,802 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,815 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,210 | 66.7% |
| RETURN_CONST | 20,645 | 31.9% |
| LOAD_GLOBAL_MODULE | 960 | 1.5% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 396,960 | 93.9% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 422,880 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 952,800 | 97.5% |
| SWAP | 10,560 | 1.1% |
| GET_ITER | 8,640 | 0.9% |
| LOAD_FAST | 4,320 | 0.4% |
| FOR_ITER | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 516,480 | 52.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 436,320 | 44.7% |
| SWAP | 10,560 | 1.1% |
| RETURN_CONST | 8,640 | 0.9% |
| LOAD_GLOBAL_MODULE | 4,320 | 0.4% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 24,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,480 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 24,480 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20,640 | 59.2% |
| LOAD_FAST | 12,960 | 37.2% |
| LOAD_GLOBAL_MODULE | 1,272 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,872 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,510,164 | 48.4% |
| STORE_FAST | 4,320,000 | 32.1% |
| POP_JUMP_IF_NOT_NONE | 732,624 | 5.4% |
| LIST_APPEND | 604,393 | 4.5% |
| STORE_FAST_STORE_FAST | 436,320 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,913,521 | 44.0% |
| FOR_ITER_GEN | 4,752,000 | 35.3% |
| FOR_ITER | 952,800 | 7.1% |
| NOP | 816,000 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 432,000 | 3.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 776,639 | 62.5% |
| POP_TOP | 451,642 | 36.4% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 824,587 | 66.4% |
| BUILD_LIST | 361,163 | 29.1% |
| POP_EXCEPT | 23,806 | 1.9% |
| LOAD_GLOBAL_MODULE | 18,725 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 333,304 | 55.1% |
| LOAD_ATTR | 186,609 | 30.9% |
| BINARY_SUBSCR_STR_INT | 84,480 | 14.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 604,393 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 175,032 | 50.1% |
| RETURN_VALUE | 174,072 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 174,552 | 50.0% |
| STORE_FAST | 174,072 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,864,364 | 77.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,347,049 | 17.7% |
| LOAD_GLOBAL_MODULE | 289,850 | 3.8% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,896 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,549,287 | 33.6% |
| PUSH_NULL | 961,435 | 12.7% |
| STORE_SUBSCR_DICT | 861,119 | 11.3% |
| POP_JUMP_IF_NOT_NONE | 838,803 | 11.0% |
| STORE_FAST | 543,677 | 7.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,916,597 | 25.6% |
| LOAD_CONST | 2,815,575 | 24.7% |
| POP_TOP | 1,289,769 | 11.3% |
| POP_JUMP_IF_FALSE | 683,243 | 6.0% |
| LOAD_ATTR_METHOD_NO_DICT | 552,307 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,815,575 | 24.7% |
| CALL | 1,947,766 | 17.1% |
| COMPARE_OP_INT | 1,511,216 | 13.2% |
| LOAD_FAST | 1,186,177 | 10.4% |
| COPY | 825,600 | 7.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,304,362 | 96.9% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.5% |
| STORE_DEREF | 20,640 | 1.5% |
| NOP | 120 | 0.0% |
| STORE_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,304,362 | 96.9% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 3.1% |
| PUSH_NULL | 120 | 0.0% |
| STORE_FAST | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,433,632 | 20.7% |
| STORE_FAST | 9,499,710 | 12.8% |
| POP_JUMP_IF_FALSE | 5,809,935 | 7.8% |
| POP_TOP | 5,527,312 | 7.4% |
| NOP | 4,705,504 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,376,778 | 22.0% |
| RETURN_VALUE | 7,942,549 | 10.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,879,621 | 7.9% |
| LOAD_ATTR | 5,864,364 | 7.9% |
| CALL_PY_EXACT_ARGS | 3,812,637 | 5.1% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 371,241 | 66.5% |
| LOAD_FAST_AND_CLEAR | 186,609 | 33.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 371,241 | 66.5% |
| LOAD_FAST_AND_CLEAR | 186,609 | 33.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 69.8% |
| POP_JUMP_IF_NONE | 174,554 | 28.2% |
| LOAD_ATTR_CLASS | 12,428 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 69.8% |
| LOAD_GLOBAL_MODULE | 174,554 | 28.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,428 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,944,790 | 16.8% |
| LOAD_FAST_LOAD_FAST | 1,510,871 | 13.1% |
| POP_JUMP_IF_FALSE | 1,085,691 | 9.4% |
| PUSH_NULL | 1,046,514 | 9.1% |
| LOAD_SUPER_ATTR_METHOD | 871,679 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,673,151 | 23.1% |
| LOAD_FAST_LOAD_FAST | 1,510,871 | 13.1% |
| CALL | 1,415,581 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,262,363 | 10.9% |
| BUILD_TUPLE | 870,240 | 7.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 38.5% |
| POP_JUMP_IF_FALSE | 40 | 19.2% |
| RESUME_CHECK | 40 | 19.2% |
| POP_JUMP_IF_TRUE | 23 | 11.1% |
| LOAD_ATTR_INSTANCE_VALUE | 12 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 110 | 52.9% |
| LOAD_ATTR | 47 | 22.6% |
| LOAD_GLOBAL_BUILTIN | 44 | 21.2% |
| LOAD_FAST | 4 | 1.9% |
| COMPARE_OP | 3 | 1.4% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 82,560 | 80.0% |
| CALL_PY_EXACT_ARGS | 20,640 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 82,560 | 80.0% |
| RESUME_CHECK | 20,640 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 3,817,694 | 27.0% |
| TO_BOOL_BOOL | 3,592,218 | 25.4% |
| COMPARE_OP_INT | 2,772,521 | 19.6% |
| CONTAINS_OP | 1,293,119 | 9.1% |
| COMPARE_OP_STR | 1,078,872 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,809,935 | 41.0% |
| RETURN_CONST | 2,322,315 | 16.4% |
| LOAD_FAST_LOAD_FAST | 1,085,691 | 7.7% |
| POP_TOP | 1,080,006 | 7.6% |
| LOAD_GLOBAL_MODULE | 1,068,379 | 7.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 776,356 | 94.6% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.7% |
| LOAD_ATTR | 21,120 | 2.6% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 214,282 | 26.1% |
| NOP | 202,392 | 24.7% |
| LOAD_FAST | 192,728 | 23.5% |
| LOAD_FAST_CHECK | 174,554 | 21.3% |
| RETURN_CONST | 18,240 | 2.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,788,304 | 47.9% |
| LOAD_ATTR | 838,803 | 22.5% |
| LOAD_ATTR_INSTANCE_VALUE | 714,985 | 19.2% |
| RETURN_VALUE | 333,784 | 8.9% |
| LOAD_DEREF | 41,280 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,506,190 | 40.4% |
| RETURN_CONST | 839,115 | 22.5% |
| JUMP_BACKWARD | 732,624 | 19.6% |
| NOP | 367,600 | 9.8% |
| LOAD_CONST | 174,072 | 4.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,367,141 | 67.7% |
| TO_BOOL | 627,253 | 31.0% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,255 | 0.4% |
| COMPARE_OP_INT | 2,232 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 714,336 | 35.4% |
| LOAD_FAST_LOAD_FAST | 630,129 | 31.2% |
| RETURN_CONST | 538,678 | 26.7% |
| LOAD_GLOBAL_MODULE | 53,581 | 2.7% |
| RETURN_VALUE | 44,446 | 2.2% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,320 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 8,640 | 66.7% |
| POP_JUMP_IF_TRUE | 4,320 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 4,320 | 50.0% |
| COPY | 4,320 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,322,315 | 34.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,604,492 | 23.5% |
| POP_TOP | 1,415,123 | 20.7% |
| POP_JUMP_IF_NOT_NONE | 839,115 | 12.3% |
| POP_JUMP_IF_TRUE | 538,678 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,829,819 | 70.8% |
| EXIT_INIT_CHECK | 773,206 | 11.3% |
| INTERPRETER_EXIT | 654,938 | 9.6% |
| TO_BOOL_BOOL | 494,644 | 7.2% |
| STORE_FAST | 45,406 | 0.7% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 28,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,320 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,921 | 57.1% |
| LOAD_FAST_LOAD_FAST | 14,880 | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 19.5% |
| STORE_ATTR | 640 | 1.0% |
| SWAP | 16 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_FAST | 8,648 | 13.0% |
| LOAD_CONST | 8,641 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 4,320 | 6.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 41,280 | 40.0% |
| LOAD_GLOBAL_MODULE | 41,280 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 20,640 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,280 | 40.0% |
| LOAD_DEREF | 20,640 | 20.0% |
| LOAD_FAST | 20,640 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 20,640 | 20.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,752,000 | 21.7% |
| CALL | 2,483,397 | 11.3% |
| COPY | 1,972,800 | 9.0% |
| RETURN_VALUE | 1,679,027 | 7.7% |
| FOR_ITER_LIST | 1,220,303 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,499,710 | 43.4% |
| JUMP_BACKWARD | 4,320,000 | 19.7% |
| NOP | 2,829,111 | 12.9% |
| COPY | 1,972,320 | 9.0% |
| LOAD_GLOBAL_BUILTIN | 877,421 | 4.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 4,320,000 | 89.1% |
| FOR_ITER | 516,480 | 10.7% |
| COPY | 10,560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,320,000 | 89.1% |
| GET_ITER | 432,000 | 8.9% |
| LOAD_FAST | 84,480 | 1.7% |
| STORE_ATTR_INSTANCE_VALUE | 10,560 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,584,195 | 44.0% |
| COPY | 820,320 | 22.8% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 22.6% |
| STORE_FAST_STORE_FAST | 384,000 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,189,218 | 33.0% |
| STORE_FAST | 816,000 | 22.6% |
| LOAD_FAST_LOAD_FAST | 767,457 | 21.3% |
| JUMP_BACKWARD | 436,320 | 12.1% |
| STORE_FAST_STORE_FAST | 384,000 | 10.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 431,992 | 22.4% |
| BUILD_LIST | 371,241 | 19.3% |
| LOAD_FAST_AND_CLEAR | 371,241 | 19.3% |
| FOR_ITER_LIST | 360,681 | 18.7% |
| LOAD_FAST | 195,194 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 431,984 | 22.4% |
| LOAD_CONST | 381,803 | 19.8% |
| BUILD_LIST | 371,241 | 19.3% |
| STORE_FAST | 371,241 | 19.3% |
| FOR_ITER_LIST | 360,681 | 18.7% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,320,000 | 83.3% |
| BUILD_TUPLE | 864,000 | 16.7% |
| CALL_STR_1 | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,752,000 | 91.6% |
| INTERPRETER_EXIT | 432,960 | 8.4% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 187,091 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 187,091 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 820,304 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 8 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 431,992 | 51.8% |
| STORE_FAST | 384,000 | 46.0% |
| BINARY_SLICE | 13,920 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,320 | 0.5% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 84,480 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 174,554 | 99.9% |
| LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 174,674 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,834 | 80.3% |
| LOAD_CONST | 44,446 | 18.0% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 243,280 | 98.3% |
| CALL_BUILTIN_CLASS | 4,320 | 1.7% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 74,880 | 87.6% |
| LOAD_CONST | 10,560 | 12.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 74,880 | 87.6% |
| CONVERT_VALUE | 10,560 | 12.4% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 348,144 | 97.6% |
| LOAD_CONST | 8,640 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 348,144 | 97.6% |
| LOAD_CONST | 8,640 | 2.4% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 84,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 84,480 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 24,480 | 85.0% |
| JUMP_FORWARD | 4,320 | 15.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 381,803 | 49.4% |
| LOAD_FAST | 366,443 | 47.4% |
| CALL | 24,960 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 412,043 | 53.3% |
| COPY_FREE_VARS | 361,163 | 46.7% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 48,575 | 45.7% |
| LOAD_FAST | 48,000 | 45.2% |
| LOAD_CONST | 5,280 | 5.0% |
| BINARY_OP_ADD_INT | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 101,866 | 95.9% |
| POP_TOP | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 40.1% |
| LOAD_FAST | 200,611 | 21.0% |
| CALL_BUILTIN_CLASS | 174,072 | 18.2% |
| CALL_LEN | 174,072 | 18.2% |
| LOAD_CONST | 11,040 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 571,091 | 59.7% |
| GET_ITER | 198,552 | 20.8% |
| CALL_BUILTIN_CLASS | 174,072 | 18.2% |
| LOAD_FAST | 12,960 | 1.4% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 652,547 | 48.3% |
| LOAD_CONST | 466,224 | 34.5% |
| LOAD_FAST_LOAD_FAST | 129,714 | 9.6% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 61,017 | 4.5% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 459,024 | 34.0% |
| STORE_FAST | 439,683 | 32.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 335,457 | 24.8% |
| UNPACK_SEQUENCE_TUPLE | 61,017 | 4.5% |
| POP_TOP | 10,961 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,800 | 45.6% |
| BUILD_TUPLE | 384,000 | 45.0% |
| CALL | 48,589 | 5.7% |
| LOAD_FAST_CHECK | 12,428 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 790,560 | 92.7% |
| RETURN_VALUE | 61,017 | 7.2% |
| LOAD_FAST | 960 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 88.9% |
| LOAD_FAST | 10,560 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_STR_INT | 84,480 | 88.9% |
| LOAD_FAST | 10,560 | 11.1% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 874,079 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 874,079 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 445,758 | 95.6% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 4.4% |
| CALL | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,354 | 55.4% |
| CALL_BUILTIN_CLASS | 174,072 | 37.3% |
| CALL_PY_EXACT_ARGS | 24,960 | 5.4% |
| LOAD_FAST | 4,320 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 186,609 | 95.6% |
| LOAD_FAST | 8,640 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 186,609 | 95.6% |
| LOAD_GLOBAL_MODULE | 8,640 | 4.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,222,282 | 99.6% |
| LOAD_ATTR_INSTANCE_VALUE | 3,387 | 0.3% |
| LOAD_CONST | 960 | 0.1% |
| CALL | 8 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 861,119 | 70.2% |
| STORE_FAST | 364,558 | 29.7% |
| TO_BOOL_NONE | 960 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,320 | 86.8% |
| BUILD_TUPLE | 4,320 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 24,000 | 73.5% |
| LOAD_FAST | 8,640 | 26.5% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,026,289 | 93.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,445 | 6.7% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 464,935 | 42.2% |
| STORE_FAST | 432,000 | 39.2% |
| LOAD_FAST | 63,840 | 5.8% |
| CALL_BUILTIN_FAST | 61,017 | 5.5% |
| RETURN_VALUE | 38,776 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 666,434 | 92.0% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,609 | 3.0% |
| RETURN_VALUE | 10,560 | 1.5% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 688,043 | 95.0% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.5% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,126,929 | 45.0% |
| LOAD_FAST | 3,812,637 | 41.6% |
| LOAD_FAST_LOAD_FAST | 616,632 | 6.7% |
| LOAD_SUPER_ATTR_METHOD | 361,163 | 3.9% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,134,077 | 99.6% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 909,738 | 42.0% |
| LOAD_ATTR_MODULE | 861,119 | 39.7% |
| LOAD_FAST | 249,009 | 11.5% |
| LOAD_CONST | 80,657 | 3.7% |
| BINARY_OP | 62,880 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,306,125 | 60.3% |
| COPY_FREE_VARS | 861,119 | 39.7% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,680 | 88.9% |
| YIELD_VALUE | 960 | 11.1% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 436,320 | 99.8% |
| LOAD_FAST | 960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 436,320 | 99.8% |
| LOAD_FAST | 960 | 0.2% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,511,216 | 54.5% |
| LOAD_ATTR_INSTANCE_VALUE | 799,499 | 28.8% |
| LOAD_FAST | 432,000 | 15.6% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,772,521 | 99.9% |
| POP_JUMP_IF_TRUE | 2,232 | 0.1% |
| COMPARE_OP | 68 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,059,276 | 95.6% |
| LOAD_CONST | 44,640 | 4.0% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 11 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,078,872 | 97.3% |
| COPY | 10,560 | 1.0% |
| LOAD_FAST | 10,560 | 1.0% |
| POP_JUMP_IF_TRUE | 8,255 | 0.7% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,752,000 | 99.8% |
| GET_ITER | 8,640 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,752,000 | 99.8% |
| POP_TOP | 8,640 | 0.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,913,521 | 79.5% |
| GET_ITER | 1,160,566 | 15.6% |
| SWAP | 360,681 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,320,000 | 58.1% |
| STORE_FAST | 1,220,303 | 16.4% |
| LOAD_FAST | 722,326 | 9.7% |
| JUMP_BACKWARD | 432,000 | 5.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 373,218 | 5.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 368,893 | 65.6% |
| GET_ITER | 193,392 | 34.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 379,933 | 67.6% |
| LOAD_FAST | 174,192 | 31.0% |
| RETURN_CONST | 8,160 | 1.5% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 10,560 | 52.4% |
| GET_ITER | 8,640 | 42.9% |
| LOAD_FAST | 960 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,560 | 52.4% |
| LOAD_FAST | 7,680 | 38.1% |
| RETURN_CONST | 1,920 | 9.5% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 61,017 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,269 | 81.9% |
| LOAD_FAST_CHECK | 12,428 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,376,778 | 90.5% |
| LOAD_FAST_LOAD_FAST | 1,262,363 | 7.0% |
| COPY | 431,984 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 18,131 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,140,797 | 22.9% |
| LOAD_FAST | 2,749,134 | 15.2% |
| TO_BOOL_BOOL | 1,369,775 | 7.6% |
| LOAD_ATTR | 1,347,049 | 7.4% |
| CONTAINS_OP | 1,293,111 | 7.1% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,948 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,034 | 39.8% |
| CALL | 111,469 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,445 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,140,797 | 87.1% |
| LOAD_FAST | 464,838 | 9.8% |
| LOAD_ATTR | 62,897 | 1.3% |
| LOAD_ATTR_SLOT | 62,880 | 1.3% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,856,486 | 39.1% |
| CALL | 1,078,458 | 22.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,026,289 | 21.6% |
| LOAD_CONST | 552,307 | 11.6% |
| LOAD_FAST_LOAD_FAST | 218,351 | 4.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,879,621 | 71.7% |
| LOAD_ATTR_INSTANCE_VALUE | 994,276 | 12.1% |
| LOAD_FAST_LOAD_FAST | 861,119 | 10.5% |
| BINARY_SUBSCR | 432,000 | 5.3% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,126,929 | 50.3% |
| LOAD_FAST | 2,484,813 | 30.3% |
| CALL_PY_WITH_DEFAULTS | 909,738 | 11.1% |
| LOAD_FAST_LOAD_FAST | 508,800 | 6.2% |
| LOAD_CONST | 94,577 | 1.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,663,924 | 100.0% |
| LOAD_ATTR | 97 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,691,981 | 63.5% |
| CALL_PY_WITH_DEFAULTS | 861,119 | 32.3% |
| STORE_DEREF | 41,280 | 1.5% |
| LOAD_CONST | 26,400 | 1.0% |
| LOAD_FAST | 20,640 | 0.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 891,839 | 70.5% |
| LOAD_FAST_LOAD_FAST | 373,218 | 29.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 861,119 | 68.1% |
| UNARY_INVERT | 373,218 | 29.5% |
| RETURN_VALUE | 10,560 | 0.8% |
| LOAD_CONST | 10,560 | 0.8% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 735,519 | 97.1% |
| RETURN_VALUE | 20,640 | 2.7% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 748,160 | 98.8% |
| TO_BOOL_BOOL | 8,960 | 1.2% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 62,880 | 85.6% |
| CALL_BUILTIN_FAST | 10,560 | 14.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,681,481 | 41.8% |
| LOAD_FAST | 894,239 | 13.9% |
| STORE_FAST | 877,421 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 732,144 | 11.4% |
| NOP | 532,615 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,962,851 | 46.1% |
| LOAD_DEREF | 1,304,362 | 20.3% |
| CALL_ISINSTANCE | 874,079 | 13.6% |
| LOAD_GLOBAL_BUILTIN | 732,144 | 11.4% |
| LOAD_GLOBAL_MODULE | 468,960 | 7.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,556,627 | 28.5% |
| RESUME_CHECK | 2,283,638 | 18.3% |
| NOP | 1,313,617 | 10.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,081,187 | 8.6% |
| POP_JUMP_IF_FALSE | 1,068,379 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,769,966 | 22.2% |
| LOAD_ATTR_MODULE | 2,663,924 | 21.3% |
| LOAD_FAST_LOAD_FAST | 1,944,790 | 15.6% |
| LOAD_FAST | 1,571,613 | 12.6% |
| COMPARE_OP_STR | 1,059,276 | 8.5% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 67,200 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,237,162 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 871,679 | 70.5% |
| CALL_PY_EXACT_ARGS | 361,163 | 29.2% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 9,134,077 | 33.1% |
| CACHE | 8,789,135 | 31.9% |
| FOR_ITER_GEN | 4,752,000 | 17.2% |
| COPY_FREE_VARS | 1,308,802 | 4.7% |
| CALL_PY_WITH_DEFAULTS | 1,306,125 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,433,632 | 56.0% |
| POP_TOP | 5,184,960 | 18.8% |
| LOAD_GLOBAL_BUILTIN | 2,681,481 | 9.7% |
| LOAD_GLOBAL_MODULE | 2,283,638 | 8.3% |
| NOP | 1,012,319 | 3.7% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,153,131 | 67.9% |
| LOAD_FAST_LOAD_FAST | 557,483 | 17.6% |
| SWAP | 431,984 | 13.6% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,604,492 | 50.6% |
| LOAD_FAST | 684,952 | 21.6% |
| LOAD_GLOBAL_MODULE | 520,523 | 16.4% |
| LOAD_CONST | 160,319 | 5.1% |
| LOAD_FAST_LOAD_FAST | 96,960 | 3.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,880 | 85.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 14.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,440 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 861,119 | 92.6% |
| LOAD_FAST | 34,587 | 3.7% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.8% |
| CALL | 7,680 | 0.8% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 864,514 | 92.9% |
| RETURN_CONST | 24,480 | 2.6% |
| LOAD_CONST | 20,640 | 2.2% |
| LOAD_GLOBAL_MODULE | 20,640 | 2.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,369,775 | 26.5% |
| CALL_ISINSTANCE | 874,079 | 16.9% |
| RETURN_VALUE | 665,821 | 12.9% |
| CALL | 546,066 | 10.6% |
| LOAD_FAST | 538,846 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,592,218 | 69.5% |
| POP_JUMP_IF_TRUE | 1,367,141 | 26.5% |
| UNARY_NOT | 206,140 | 4.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,095,456 | 54.9% |
| BINARY_OP | 861,119 | 22.6% |
| LOAD_FAST | 861,119 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,817,694 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 369,803 | 92.0% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 401,963 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,842 | 79.8% |
| LOAD_FAST | 20,640 | 11.4% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,442 | 91.7% |
| POP_JUMP_IF_TRUE | 14,880 | 8.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,000 | 93.0% |
| CALL_BUILTIN_FAST | 61,017 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 61,017 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 436,320 | 27.5% |
| LOAD_FAST_CHECK | 432,000 | 27.2% |
| FOR_ITER_LIST | 373,218 | 23.5% |
| CALL_BUILTIN_FAST | 335,457 | 21.1% |
| CALL | 7,200 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,584,195 | 99.7% |
| LOAD_FAST | 5,280 | 0.3% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 50.0% |
| CALL_METHOD_DESCRIPTOR_O | 960 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 50.0% |
| LOAD_FAST | 960 | 50.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 960 | 100.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 60.6% |
| COPY | 311 | 39.3% |
| TO_BOOL | 1 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 60.6% |
| POP_JUMP_IF_FALSE | 312 | 39.4% |


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
|     deferred | 5,165,636 | 76.9% |
|          hit | 1,550,637 | 23.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 48 | 2.3% |
| Failure | 1,995 | 97.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 990 | 49.6% |
| or | 574 | 28.8% |
| remainder | 231 | 11.6% |
| add different types | 160 | 8.0% |
| add other | 40 | 2.0% |


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
|     deferred | 476,446 | 46.2% |
|          hit | 555,504 | 53.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 220 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 220 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,622,705 | 29.5% |
|        deopt | 60 | 0.0% |
|          hit | 20,636,517 | 70.5% |
|         miss | 4,380 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 137 | 1.5% |
| Failure | 8,997 | 98.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,527 | 28.1% |
| cfunc noargs | 1,788 | 19.9% |
| class no vectorcall | 1,262 | 14.0% |
| meth descr varargs keywords | 845 | 9.4% |
| class mutable | 404 | 4.5% |
| other | 360 | 4.0% |
| cfunc varargs keywords | 324 | 3.6% |
| cfunc varargs | 320 | 3.6% |
| bound method | 287 | 3.2% |
| operator wrapper | 240 | 2.7% |
| cmethod | 200 | 2.2% |
| meth descr method fastcall keywords | 200 | 2.2% |
| wrong number arguments | 160 | 1.8% |
| method wrapper | 80 | 0.9% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 425,246 | 9.9% |
|        deopt | 68 | 0.0% |
|          hit | 3,878,172 | 90.0% |
|         miss | 4,896 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 126 | 25.9% |
| Failure | 360 | 74.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 155 | 43.1% |
| different types | 125 | 34.7% |
| big int | 80 | 22.2% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 976,320 | 7.1% |
|          hit | 12,777,853 | 92.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 440 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 140 | 31.8% |
| enumerate | 140 | 31.8% |
| itertools | 80 | 18.2% |
| callable | 80 | 18.2% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,589,483 | 17.3% |
|        deopt | 4,192 | 0.0% |
|          hit | 35,961,726 | 82.1% |
|         miss | 230,255 | 0.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,390 | 42.5% |
| Failure | 5,928 | 57.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,402 | 23.7% |
| shadowed | 1,188 | 20.0% |
| not managed dict | 1,184 | 20.0% |
| non overriding descriptor | 592 | 10.0% |
| class attr descriptor | 360 | 6.1% |
| class method obj | 280 | 4.7% |
| metaclass attribute | 280 | 4.7% |
| has managed dict | 240 | 4.0% |
| non object slot | 160 | 2.7% |
| class attr simple | 122 | 2.1% |
| mutable class | 80 | 1.3% |
| overridden | 40 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 54 | 0.0% |
|        deopt | 88 | 0.0% |
|          hit | 18,915,639 | 100.0% |
|         miss | 6,314 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 242 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,304,362 | 100.0% |


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
|     deferred | 65,769 | 2.0% |
|        deopt | 2,780 | 0.1% |
|          hit | 3,094,226 | 93.5% |
|         miss | 148,120 | 4.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,788 | 81.3% |
| Failure | 640 | 18.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 400 | 62.5% |
| class attr simple | 160 | 25.0% |
| no dict | 80 | 12.5% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 22,568 | 2.4% |
|          hit | 930,274 | 97.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 8 | 3.8% |
| Failure | 200 | 96.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 120 | 60.0% |
| other | 80 | 40.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,178,069 | 11.0% |
|          hit | 9,566,270 | 89.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5 | 0.5% |
| Failure | 1,046 | 99.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 326 | 31.2% |
| sequence | 220 | 21.0% |
| tuple | 220 | 21.0% |
| set | 200 | 19.1% |
| other | 80 | 7.6% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 2,466,492 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 224,411,545 | 53.1% |
| Not specialized | 59,135,923 | 14.0% |
| Specialized | 139,092,592 | 32.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 36,893,488,147,419,103,230 | 100.0% |
| CALL | 8,622,705 | 0.0% |
| LOAD_ATTR | 7,589,483 | 0.0% |
| BINARY_OP | 5,165,636 | 0.0% |
| TO_BOOL | 1,178,069 | 0.0% |
| FOR_ITER | 976,320 | 0.0% |
| BINARY_SUBSCR | 476,446 | 0.0% |
| COMPARE_OP | 425,246 | 0.0% |
| STORE_ATTR | 65,769 | 0.0% |
| STORE_SUBSCR | 22,568 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,412 | 40.7% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,723 | 15.4% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| LOAD_GLOBAL_MODULE | 6,314 | 1.6% |
| COMPARE_OP_INT | 4,896 | 1.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,380 | 1.1% |
| RESUME_CHECK | 2 | 0.0% |
| RESUME | 2 | 0.0% |
| CACHE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 8,876,495 | 32.2% |
| Calls to Python functions inlined | 18,694,213 | 67.8% |
| Calls via PyEval_EvalFrame (total) | 8,876,495 | 32.2% |
| Calls via PyEval_EvalFrame (vector) | 8,438,255 | 30.6% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,438,255 | 30.6% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.5% |
| Calls via PyEval_EvalFrame (api) | 463,714 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 36,342 | 0.1% |
| Frames pushed | 23,145,034 | 83.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,776,556 | 42.7% |
| Frees to freelist | 14,778,303 |  |
| Allocations | 19,855,534 | 57.3% |
| Allocations to 512 bytes | 19,643,616 | 56.7% |
| Allocations to 4 kbytes | 86,136 | 0.2% |
| Allocations over 4 kbytes | 125,782 | 0.4% |
| Frees | 20,980,074 |  |
| New values | 65,280 |  |
| Interpreter increfs | 165,633,801 | 77.0% |
| Interpreter decrefs | 181,423,923 | 73.6% |
| Increfs | 49,508,550 | 23.0% |
| Decrefs | 64,965,239 | 26.4% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 8,919,176 |  |
| Method cache misses | 27,211 |  |
| Method cache collisions | 41,767 |  |
| Method cache dunder hits | 8,478,361 |  |
| Method cache dunder misses | 14,556 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 15 | 360 | 112,784 |
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
| Traces executed | 0 |  |
| Uops executed | 0 |  |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |

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
Stats gathered on: 2023-10-09
