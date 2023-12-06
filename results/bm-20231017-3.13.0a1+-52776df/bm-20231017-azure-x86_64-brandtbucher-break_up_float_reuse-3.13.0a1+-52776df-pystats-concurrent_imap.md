
# Pystats results

- benchmark: concurrent_imap
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 52776df
- commit date: 2023-10-17T21:47:13-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 76,063,350 | 17.6% | 17.6% |  |
| RESUME_CHECK | 28,030,898 | 6.5% | 24.2% |  |
| STORE_FAST | 22,280,700 | 5.2% | 29.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,434,928 | 4.3% | 33.6% | 0.9% |
| POP_TOP | 18,152,202 | 4.2% | 37.8% |  |
| RETURN_VALUE | 16,650,488 | 3.9% | 41.7% |  |
| POP_JUMP_IF_FALSE | 14,533,089 | 3.4% | 45.1% |  |
| JUMP_BACKWARD | 13,527,854 | 3.1% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 12,848,634 | 3.0% | 51.2% | 0.0% |
| LOAD_FAST_LOAD_FAST | 11,847,162 | 2.7% | 53.9% |  |
| LOAD_CONST | 11,569,869 | 2.7% | 56.6% |  |
| CALL_PY_EXACT_ARGS | 9,452,935 | 2.2% | 58.8% |  |
| INTERPRETER_EXIT | 8,943,670 | 2.1% | 60.9% |  |
| CALL | 8,783,753 | 2.0% | 62.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,427,400 | 2.0% | 64.9% | 0.7% |
| LOAD_ATTR | 7,803,475 | 1.8% | 66.7% |  |
| NOP | 7,560,379 | 1.8% | 68.4% |  |
| FOR_ITER_LIST | 7,532,175 | 1.7% | 70.2% |  |
| RETURN_CONST | 6,990,286 | 1.6% | 71.8% |  |
| LOAD_GLOBAL_BUILTIN | 6,595,045 | 1.5% | 73.3% |  |
| PUSH_NULL | 5,533,482 | 1.3% | 74.6% |  |
| COPY | 5,460,339 | 1.3% | 75.9% |  |
| BINARY_OP | 5,356,251 | 1.2% | 77.1% |  |
| TO_BOOL_BOOL | 5,291,113 | 1.2% | 78.4% |  |
| YIELD_VALUE | 5,184,960 | 1.2% | 79.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,855,731 | 1.1% | 80.7% |  |
| STORE_FAST_LOAD_FAST | 4,847,040 | 1.1% | 81.8% |  |
| FOR_ITER_GEN | 4,760,640 | 1.1% | 82.9% |  |
| TO_BOOL_INT | 3,960,776 | 0.9% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,814,079 | 0.9% | 84.7% |  |
| STORE_FAST_STORE_FAST | 3,630,472 | 0.8% | 85.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,233,781 | 0.8% | 86.3% | 4.6% |
| BUILD_TUPLE | 3,232,334 | 0.8% | 87.1% |  |
| COMPARE_OP_INT | 2,828,481 | 0.7% | 87.7% | 0.2% |
| LOAD_ATTR_MODULE | 2,722,390 | 0.6% | 88.3% |  |
| CALL_PY_WITH_DEFAULTS | 2,220,601 | 0.5% | 88.9% |  |
| POP_JUMP_IF_TRUE | 2,049,219 | 0.5% | 89.3% |  |
| SWAP | 1,979,423 | 0.5% | 89.8% |  |
| CALL_FUNCTION_EX | 1,810,138 | 0.4% | 90.2% |  |
| GET_ITER | 1,801,826 | 0.4% | 90.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,615,432 | 0.4% | 91.0% |  |
| LOAD_DEREF | 1,391,392 | 0.3% | 91.3% |  |
| CALL_BUILTIN_FAST | 1,384,114 | 0.3% | 91.7% |  |
| BEFORE_WITH | 1,380,636 | 0.3% | 92.0% |  |
| COPY_FREE_VARS | 1,354,312 | 0.3% | 92.3% |  |
| CONTAINS_OP | 1,325,654 | 0.3% | 92.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,310,534 | 0.3% | 92.9% |  |
| LOAD_SUPER_ATTR_METHOD | 1,282,672 | 0.3% | 93.2% |  |
| UNARY_INVERT | 1,279,814 | 0.3% | 93.5% |  |
| JUMP_FORWARD | 1,277,459 | 0.3% | 93.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,270,716 | 0.3% | 94.1% |  |
| BUILD_MAP | 1,259,258 | 0.3% | 94.4% |  |
| TO_BOOL | 1,191,160 | 0.3% | 94.7% |  |
| BUILD_LIST | 1,149,771 | 0.3% | 94.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,127,021 | 0.3% | 95.2% |  |
| COMPARE_OP_STR | 1,114,734 | 0.3% | 95.4% |  |
| FOR_ITER | 976,760 | 0.2% | 95.7% |  |
| CALL_BUILTIN_CLASS | 976,273 | 0.2% | 95.9% |  |
| STORE_SUBSCR_DICT | 961,378 | 0.2% | 96.1% |  |
| CALL_ISINSTANCE | 906,614 | 0.2% | 96.3% |  |
| UNPACK_SEQUENCE_TUPLE | 876,985 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 852,505 | 0.2% | 96.7% |  |
| POP_JUMP_IF_NONE | 840,421 | 0.2% | 96.9% |  |
| BINARY_OP_ADD_INT | 834,233 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 799,156 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 799,156 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 783,325 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 732,271 | 0.2% | 97.8% |  |
| LOAD_FAST_CHECK | 625,476 | 0.1% | 98.0% |  |
| LIST_APPEND | 623,904 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 581,772 | 0.1% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 577,295 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 480,814 | 0.1% | 98.5% |  |
| CALL_LEN | 472,858 | 0.1% | 98.6% |  |
| COMPARE_OP | 438,601 | 0.1% | 98.7% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.8% |  |
| DICT_MERGE | 422,880 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 414,938 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 369,790 | 0.1% | 99.1% |  |
| LIST_EXTEND | 362,110 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,820 | 0.1% | 99.3% |  |
| CALL_KW | 267,532 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 251,684 | 0.1% | 99.4% |  |
| UNARY_NOT | 212,599 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 201,720 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT_LHS | 193,563 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT_RHS | 181,058 | 0.0% | 99.6% |  |
| TO_BOOL_NONE | 180,311 | 0.0% | 99.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 106,223 | 0.0% | 99.6% | 4.1% |
| STORE_DEREF | 103,200 | 0.0% | 99.7% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT_LHS | 84,480 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,665 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,419 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,800 | 0.0% | 99.9% |  |
| DELETE_SUBSCR | 58,560 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 40,434 | 0.0% | 99.9% |  |
| POP_EXCEPT | 40,434 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 36,114 | 0.0% | 99.9% |  |
| IS_OP | 34,871 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 32,640 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 100.0% |  |
| IMPORT_NAME | 24,480 | 0.0% | 100.0% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,777 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 21,120 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 20,160 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 13,920 | 0.0% | 100.0% |  |
| BINARY_SLICE | 13,920 | 0.0% | 100.0% |  |
| RERAISE | 12,960 | 0.0% | 100.0% |  |
| END_FOR | 8,640 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,640 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,320 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 1,920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 791 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 198 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 120 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,664,813 | 3.9% | 3.9% |
| RESUME_CHECK LOAD_FAST | 15,699,801 | 3.6% | 7.5% |
| STORE_FAST LOAD_FAST | 9,711,380 | 2.3% | 9.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,418,375 | 2.2% | 11.9% |
| CACHE RESUME_CHECK | 8,860,630 | 2.1% | 14.0% |
| LOAD_FAST RETURN_VALUE | 8,072,543 | 1.9% | 15.9% |
| RETURN_VALUE INTERPRETER_EXIT | 7,842,812 | 1.8% | 17.7% |
| POP_TOP JUMP_BACKWARD | 6,542,666 | 1.5% | 19.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 6,055,687 | 1.4% | 20.6% |
| LOAD_FAST LOAD_ATTR | 6,052,722 | 1.4% | 22.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 5,972,004 | 1.4% | 23.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,948,568 | 1.4% | 24.8% |
| POP_TOP LOAD_FAST | 5,688,575 | 1.3% | 26.1% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.2% | 27.3% |
| RETURN_CONST POP_TOP | 4,945,687 | 1.1% | 28.5% |
| NOP LOAD_FAST | 4,806,606 | 1.1% | 29.6% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.1% | 30.7% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.1% | 31.8% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.1% | 32.9% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 4,320,000 | 1.0% | 33.9% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.0% | 34.9% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 4,320,000 | 1.0% | 35.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,246,961 | 1.0% | 36.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,220,006 | 1.0% | 37.9% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,960,776 | 0.9% | 38.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,957,453 | 0.9% | 39.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,688,853 | 0.9% | 40.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,686,767 | 0.9% | 41.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,040,815 | 0.7% | 42.1% |
| LOAD_FAST LOAD_CONST | 2,987,333 | 0.7% | 42.8% |
| STORE_FAST NOP | 2,893,537 | 0.7% | 43.5% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,874,042 | 0.7% | 44.1% |
| LOAD_CONST LOAD_CONST | 2,841,509 | 0.7% | 44.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,826,184 | 0.7% | 45.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,797,372 | 0.6% | 46.1% |
| LOAD_FAST PUSH_NULL | 2,760,017 | 0.6% | 46.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,759,526 | 0.6% | 47.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,757,698 | 0.6% | 48.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,722,299 | 0.6% | 48.7% |
| LOAD_ATTR LOAD_FAST | 2,633,863 | 0.6% | 49.3% |
| PUSH_NULL LOAD_FAST | 2,614,627 | 0.6% | 49.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,577,582 | 0.6% | 50.5% |
| CALL STORE_FAST | 2,539,495 | 0.6% | 51.1% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,374,865 | 0.6% | 51.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,348,546 | 0.5% | 52.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,205,030 | 0.5% | 52.7% |
| COPY TO_BOOL_INT | 2,173,468 | 0.5% | 53.2% |
| BINARY_OP COPY | 2,173,468 | 0.5% | 53.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,016,363 | 0.5% | 54.1% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 54.6% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 55.1% |
| LOAD_CONST CALL | 1,966,301 | 0.5% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,908,857 | 0.4% | 56.0% |
| CALL RETURN_VALUE | 1,870,454 | 0.4% | 56.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,805,393 | 0.4% | 56.8% |
| RETURN_VALUE STORE_FAST | 1,730,934 | 0.4% | 57.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,717,839 | 0.4% | 57.6% |
| CALL POP_TOP | 1,708,465 | 0.4% | 58.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,656,392 | 0.4% | 58.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,623,595 | 0.4% | 58.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,610,152 | 0.4% | 59.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,549,909 | 0.4% | 59.5% |
| LOAD_CONST COMPARE_OP_INT | 1,547,696 | 0.4% | 59.9% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,529,878 | 0.4% | 60.2% |
| PUSH_NULL CALL | 1,528,797 | 0.4% | 60.6% |
| RETURN_VALUE RETURN_VALUE | 1,496,777 | 0.3% | 60.9% |
| LOAD_FAST_LOAD_FAST CALL | 1,448,066 | 0.3% | 61.3% |
| POP_TOP RETURN_CONST | 1,436,297 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,415,227 | 0.3% | 61.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,389,661 | 0.3% | 62.2% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,258 | 0.3% | 62.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,360,016 | 0.3% | 62.9% |
| NOP LOAD_GLOBAL_MODULE | 1,359,143 | 0.3% | 63.2% |
| COPY_FREE_VARS RESUME_CHECK | 1,354,312 | 0.3% | 63.5% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,349,872 | 0.3% | 63.8% |
| LOAD_DEREF LOAD_FAST | 1,349,872 | 0.3% | 64.1% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,326,947 | 0.3% | 64.4% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,325,654 | 0.3% | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,325,647 | 0.3% | 65.1% |
| LOAD_FAST BUILD_TUPLE | 1,318,454 | 0.3% | 65.4% |
| POP_TOP LOAD_CONST | 1,306,892 | 0.3% | 65.7% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,306,480 | 0.3% | 66.0% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,282,672 | 0.3% | 66.3% |
| UNARY_INVERT BINARY_OP | 1,279,814 | 0.3% | 66.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,267,792 | 0.3% | 66.9% |
| FOR_ITER_LIST STORE_FAST | 1,265,844 | 0.3% | 67.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,202,160 | 0.3% | 67.4% |
| LOAD_CONST LOAD_FAST | 1,199,114 | 0.3% | 67.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,194,620 | 0.3% | 68.0% |
| POP_TOP NOP | 1,187,802 | 0.3% | 68.3% |
| GET_ITER FOR_ITER_LIST | 1,186,516 | 0.3% | 68.5% |
| LOAD_FAST TO_BOOL | 1,150,265 | 0.3% | 68.8% |
| LOAD_FAST GET_ITER | 1,144,611 | 0.3% | 69.1% |
| RETURN_VALUE POP_TOP | 1,139,648 | 0.3% | 69.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,123,265 | 0.3% | 69.6% |
| POP_JUMP_IF_FALSE POP_TOP | 1,123,159 | 0.3% | 69.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,100,931 | 0.3% | 70.1% |
| BINARY_OP STORE_FAST | 1,097,294 | 0.3% | 70.4% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,090,902 | 0.3% | 70.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,087,674 | 0.3% | 70.9% |


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

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,860,630 | 99.0% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 940,258 | 68.1% |
| RETURN_VALUE | 374,138 | 27.1% |
| LOAD_GLOBAL_MODULE | 61,920 | 4.5% |
| CALL | 4,320 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,178 | 72.6% |
| STORE_FAST | 378,458 | 27.4% |


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
| LOAD_FAST_LOAD_FAST | 432,000 | 89.8% |
| LOAD_CONST | 48,594 | 10.1% |
| BINARY_SUBSCR | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 89.8% |
| STORE_FAST | 48,594 | 10.1% |
| BINARY_SUBSCR | 220 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 32,274 | 89.4% |
| LOAD_ATTR_MODULE | 3,840 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 36,114 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,320 | 48.4% |
| CALL | 20,640 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,598 | 16.4% |
| LOAD_ATTR | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,600 | 77.9% |
| RETURN_CONST | 7,680 | 13.1% |
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
| RETURN_CONST | 799,156 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 799,156 | 100.0% |


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
| LOAD_FAST | 1,144,611 | 63.5% |
| STORE_FAST_LOAD_FAST | 432,000 | 24.0% |
| CALL_BUILTIN_CLASS | 205,055 | 11.4% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,186,516 | 65.9% |
| LOAD_FAST_AND_CLEAR | 384,215 | 21.3% |
| FOR_ITER_RANGE | 199,895 | 11.1% |
| FOR_ITER_TUPLE | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,842,812 | 87.7% |
| RETURN_CONST | 667,898 | 7.5% |
| YIELD_VALUE | 432,960 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|


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
| STORE_FAST | 2,893,537 | 38.3% |
| POP_TOP | 1,187,802 | 15.7% |
| RESUME_CHECK | 1,044,854 | 13.8% |
| POP_JUMP_IF_FALSE | 1,007,630 | 13.3% |
| JUMP_BACKWARD | 816,000 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,806,606 | 63.6% |
| LOAD_GLOBAL_MODULE | 1,359,143 | 18.0% |
| LOAD_GLOBAL_BUILTIN | 552,110 | 7.3% |
| LOAD_FAST_LOAD_FAST | 437,280 | 5.8% |
| LOAD_CONST | 396,960 | 5.3% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 27,954 | 69.1% |
| COPY | 8,640 | 21.4% |
| POP_TOP | 3,840 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 27,954 | 69.1% |
| RERAISE | 8,640 | 21.4% |
| JUMP_FORWARD | 3,840 | 9.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,184,960 | 28.6% |
| RETURN_CONST | 4,945,687 | 27.2% |
| CALL | 1,708,465 | 9.4% |
| RETURN_VALUE | 1,139,648 | 6.3% |
| POP_JUMP_IF_FALSE | 1,123,159 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,542,666 | 36.0% |
| LOAD_FAST | 5,688,575 | 31.3% |
| RETURN_CONST | 1,436,297 | 7.9% |
| LOAD_CONST | 1,306,892 | 7.2% |
| NOP | 1,187,802 | 6.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 32,274 | 79.8% |
| RERAISE | 4,320 | 10.7% |
| CALL_KW | 3,840 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 32,274 | 79.8% |
| WITH_EXCEPT_START | 4,320 | 10.7% |
| LOAD_GLOBAL_MODULE | 3,840 | 9.5% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,760,017 | 49.9% |
| LOAD_ATTR_MODULE | 1,717,839 | 31.0% |
| LOAD_ATTR | 961,426 | 17.4% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,614,627 | 47.3% |
| CALL | 1,528,797 | 27.6% |
| LOAD_FAST_LOAD_FAST | 1,046,450 | 18.9% |
| LOAD_CONST | 240,336 | 4.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 48,552 | 0.9% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 13,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,320 | 31.0% |
| RETURN_VALUE | 4,320 | 31.0% |
| LOAD_FAST | 4,320 | 31.0% |
| CALL_METHOD_DESCRIPTOR_O | 960 | 6.9% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,072,543 | 48.5% |
| CALL | 1,870,454 | 11.2% |
| RETURN_VALUE | 1,496,777 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,194,620 | 7.2% |
| CALL_FUNCTION_EX | 948,898 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,842,812 | 47.1% |
| STORE_FAST | 1,730,934 | 10.4% |
| RETURN_VALUE | 1,496,777 | 9.0% |
| POP_TOP | 1,139,648 | 6.8% |
| LOAD_FAST_LOAD_FAST | 893,654 | 5.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,697 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.3% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 10 | 0.0% |
| LOAD_FAST | 7 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,150,265 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,840 | 3.3% |
| TO_BOOL | 1,048 | 0.1% |
| LOAD_ATTR | 4 | 0.0% |
| RETURN_VALUE | 3 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 633,724 | 53.2% |
| POP_JUMP_IF_FALSE | 556,388 | 46.7% |
| TO_BOOL | 1,048 | 0.1% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 893,654 | 69.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 386,160 | 30.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,279,814 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 212,599 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 212,599 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,874,042 | 53.7% |
| UNARY_INVERT | 1,279,814 | 23.9% |
| POP_JUMP_IF_FALSE | 893,654 | 16.7% |
| LOAD_ATTR | 203,640 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,173,468 | 40.6% |
| STORE_FAST | 1,097,294 | 20.5% |
| UNARY_INVERT | 893,654 | 16.7% |
| TO_BOOL_INT | 893,654 | 16.7% |
| BUILD_TUPLE | 193,080 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 384,215 | 33.4% |
| JUMP_FORWARD | 374,138 | 32.5% |
| LOAD_FAST | 193,563 | 16.8% |
| POP_TOP | 180,575 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 386,618 | 33.6% |
| SWAP | 384,215 | 33.4% |
| STORE_FAST | 375,098 | 32.6% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 432,000 | 34.3% |
| LOAD_FAST | 396,960 | 31.5% |
| RESUME_CHECK | 381,818 | 30.3% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.1% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 814,298 | 64.7% |
| BUILD_TUPLE | 432,000 | 34.3% |
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
| LOAD_FAST | 1,318,454 | 40.8% |
| LOAD_FAST_LOAD_FAST | 870,240 | 26.9% |
| BUILD_MAP | 432,000 | 13.4% |
| RETURN_VALUE | 384,000 | 11.9% |
| BINARY_OP | 193,080 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 894,614 | 27.7% |
| YIELD_VALUE | 864,000 | 26.7% |
| BUILD_MAP | 432,000 | 13.4% |
| STORE_FAST | 384,000 | 11.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 11.9% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,966,301 | 22.4% |
| PUSH_NULL | 1,528,797 | 17.4% |
| LOAD_FAST_LOAD_FAST | 1,448,066 | 16.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,090,902 | 12.4% |
| BUILD_TUPLE | 894,614 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,539,495 | 28.9% |
| RETURN_VALUE | 1,870,454 | 21.3% |
| POP_TOP | 1,708,465 | 19.5% |
| LOAD_FAST | 787,181 | 9.0% |
| TO_BOOL_BOOL | 551,597 | 6.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,258 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,898 | 52.4% |
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
| LOAD_CONST | 267,532 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 215,615 | 80.6% |
| LOAD_FAST | 21,600 | 8.1% |
| RETURN_VALUE | 15,840 | 5.9% |
| STORE_FAST | 10,560 | 3.9% |
| PUSH_EXC_INFO | 3,840 | 1.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 437,856 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 378 | 0.1% |
| COMPARE_OP | 286 | 0.1% |
| COMPARE_OP_INT | 66 | 0.0% |
| LOAD_GLOBAL_MODULE | 11 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 438,194 | 99.9% |
| COMPARE_OP | 286 | 0.1% |
| COMPARE_OP_INT | 106 | 0.0% |
| COMPARE_OP_STR | 11 | 0.0% |
| POP_JUMP_IF_TRUE | 4 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,325,647 | 100.0% |
| LOAD_ATTR | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,325,654 | 100.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 10,560 | 50.0% |
| BINARY_SUBSCR_DICT | 10,560 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 21,120 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,173,468 | 39.8% |
| STORE_FAST | 1,972,320 | 36.1% |
| LOAD_CONST | 825,600 | 15.1% |
| LOAD_FAST | 442,560 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,173,468 | 39.8% |
| STORE_FAST | 1,972,800 | 36.1% |
| STORE_FAST_STORE_FAST | 820,320 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 431,983 | 7.9% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 893,654 | 66.0% |
| CALL_ALLOC_AND_ENTER_INIT | 374,138 | 27.6% |
| CACHE | 82,080 | 6.1% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,354,312 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,200 | 66.7% |
| RETURN_CONST | 20,640 | 31.9% |
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
| LOAD_GLOBAL_MODULE | 1,271 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,871 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,542,666 | 48.4% |
| STORE_FAST | 4,320,000 | 31.9% |
| POP_JUMP_IF_NOT_NONE | 745,630 | 5.5% |
| LIST_APPEND | 623,904 | 4.6% |
| STORE_FAST_STORE_FAST | 436,320 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,972,004 | 44.1% |
| FOR_ITER_GEN | 4,752,000 | 35.1% |
| FOR_ITER | 952,800 | 7.0% |
| NOP | 816,000 | 6.0% |
| LOAD_GLOBAL_BUILTIN | 432,000 | 3.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 810,950 | 63.5% |
| POP_TOP | 453,069 | 35.5% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 843,207 | 66.0% |
| BUILD_LIST | 374,138 | 29.3% |
| POP_EXCEPT | 27,954 | 2.2% |
| LOAD_GLOBAL_MODULE | 18,720 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 346,344 | 55.5% |
| LOAD_ATTR | 193,080 | 30.9% |
| BINARY_SUBSCR_STR_INT | 84,480 | 13.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 623,904 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,535 | 50.1% |
| RETURN_VALUE | 180,575 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,055 | 50.0% |
| STORE_FAST | 180,575 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,052,722 | 77.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,360,016 | 17.4% |
| LOAD_GLOBAL_MODULE | 296,346 | 3.8% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,897 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,633,863 | 33.8% |
| PUSH_NULL | 961,426 | 12.3% |
| STORE_SUBSCR_DICT | 893,654 | 11.5% |
| POP_JUMP_IF_NOT_NONE | 864,738 | 11.1% |
| STORE_FAST | 556,588 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,987,333 | 25.8% |
| LOAD_CONST | 2,841,509 | 24.6% |
| POP_TOP | 1,306,892 | 11.3% |
| POP_JUMP_IF_FALSE | 689,714 | 6.0% |
| LOAD_ATTR_METHOD_NO_DICT | 557,902 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,841,509 | 24.6% |
| CALL | 1,966,301 | 17.0% |
| COMPARE_OP_INT | 1,547,696 | 13.4% |
| LOAD_FAST | 1,199,114 | 10.4% |
| COPY | 825,600 | 7.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,349,872 | 97.0% |
| STORE_DEREF | 20,640 | 1.5% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.5% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,349,872 | 97.0% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 3.0% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,699,801 | 20.6% |
| STORE_FAST | 9,711,380 | 12.8% |
| POP_JUMP_IF_FALSE | 5,948,568 | 7.8% |
| POP_TOP | 5,688,575 | 7.5% |
| NOP | 4,806,606 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,664,813 | 21.9% |
| RETURN_VALUE | 8,072,543 | 10.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,055,687 | 8.0% |
| LOAD_ATTR | 6,052,722 | 8.0% |
| CALL_PY_EXACT_ARGS | 3,957,453 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 384,215 | 66.6% |
| LOAD_FAST_AND_CLEAR | 193,080 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 384,215 | 66.6% |
| LOAD_FAST_AND_CLEAR | 193,080 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 69.1% |
| POP_JUMP_IF_NONE | 181,058 | 28.9% |
| LOAD_ATTR_CLASS | 12,418 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 69.1% |
| LOAD_GLOBAL_MODULE | 181,058 | 28.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,418 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,016,363 | 17.0% |
| LOAD_FAST_LOAD_FAST | 1,549,909 | 13.1% |
| POP_JUMP_IF_FALSE | 1,123,265 | 9.5% |
| PUSH_NULL | 1,046,450 | 8.8% |
| LOAD_SUPER_ATTR_METHOD | 904,214 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,757,698 | 23.3% |
| LOAD_FAST_LOAD_FAST | 1,549,909 | 13.1% |
| CALL | 1,448,066 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,306,480 | 11.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 893,654 | 7.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 40.4% |
| RESUME_CHECK | 40 | 20.2% |
| POP_JUMP_IF_FALSE | 40 | 20.2% |
| POP_JUMP_IF_TRUE | 19 | 9.6% |
| LOAD_ATTR_INSTANCE_VALUE | 11 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 102 | 51.5% |
| LOAD_ATTR | 48 | 24.2% |
| LOAD_GLOBAL_BUILTIN | 40 | 20.2% |
| LOAD_FAST | 4 | 2.0% |
| COMPARE_OP | 4 | 2.0% |


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
| TO_BOOL_INT | 3,960,776 | 27.3% |
| TO_BOOL_BOOL | 3,688,853 | 25.4% |
| COMPARE_OP_INT | 2,826,184 | 19.4% |
| CONTAINS_OP | 1,325,654 | 9.1% |
| COMPARE_OP_STR | 1,085,375 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,948,568 | 40.9% |
| RETURN_CONST | 2,374,865 | 16.3% |
| LOAD_FAST_LOAD_FAST | 1,123,265 | 7.7% |
| POP_TOP | 1,123,159 | 7.7% |
| LOAD_GLOBAL_MODULE | 1,100,931 | 7.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 795,781 | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.7% |
| LOAD_ATTR | 21,120 | 2.5% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 220,754 | 26.3% |
| NOP | 208,895 | 24.9% |
| LOAD_FAST | 192,651 | 22.9% |
| LOAD_FAST_CHECK | 181,058 | 21.5% |
| RETURN_CONST | 18,240 | 2.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,805,393 | 47.3% |
| LOAD_ATTR | 864,738 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 741,038 | 19.4% |
| RETURN_VALUE | 346,824 | 9.1% |
| LOAD_DEREF | 41,280 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,529,878 | 40.1% |
| RETURN_CONST | 865,049 | 22.7% |
| JUMP_BACKWARD | 745,630 | 19.5% |
| NOP | 380,541 | 10.0% |
| LOAD_CONST | 180,575 | 4.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,389,661 | 67.8% |
| TO_BOOL | 633,724 | 30.9% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,239 | 0.4% |
| COMPARE_OP_INT | 2,231 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 715,620 | 34.9% |
| LOAD_FAST_LOAD_FAST | 636,600 | 31.1% |
| RETURN_CONST | 551,603 | 26.9% |
| LOAD_GLOBAL_MODULE | 57,696 | 2.8% |
| RETURN_VALUE | 48,594 | 2.4% |


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
| POP_JUMP_IF_FALSE | 2,374,865 | 34.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,656,392 | 23.7% |
| POP_TOP | 1,436,297 | 20.5% |
| POP_JUMP_IF_NOT_NONE | 865,049 | 12.4% |
| POP_JUMP_IF_TRUE | 551,603 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,945,687 | 70.8% |
| EXIT_INIT_CHECK | 799,156 | 11.4% |
| INTERPRETER_EXIT | 667,898 | 9.6% |
| TO_BOOL_BOOL | 500,225 | 7.2% |
| STORE_FAST | 49,554 | 0.7% |


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
| LOAD_FAST | 37,922 | 57.1% |
| LOAD_FAST_LOAD_FAST | 14,880 | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 19.5% |
| STORE_ATTR | 640 | 1.0% |
| SWAP | 17 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_FAST | 8,647 | 13.0% |
| LOAD_CONST | 8,642 | 13.0% |
| LOAD_GLOBAL_BUILTIN | 4,320 | 6.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,280 | 40.0% |
| LOAD_ATTR_MODULE | 41,280 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 20,640 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,280 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 20,640 | 20.0% |
| LOAD_FAST | 20,640 | 20.0% |
| LOAD_DEREF | 20,640 | 20.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,752,000 | 21.3% |
| CALL | 2,539,495 | 11.4% |
| COPY | 1,972,800 | 8.9% |
| RETURN_VALUE | 1,730,934 | 7.8% |
| FOR_ITER_LIST | 1,265,844 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,711,380 | 43.6% |
| JUMP_BACKWARD | 4,320,000 | 19.4% |
| NOP | 2,893,537 | 13.0% |
| COPY | 1,972,320 | 8.9% |
| LOAD_GLOBAL_BUILTIN | 903,338 | 4.1% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,610,152 | 44.4% |
| COPY | 820,320 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 22.5% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,202,160 | 33.1% |
| STORE_FAST | 816,000 | 22.5% |
| LOAD_FAST_LOAD_FAST | 780,472 | 21.5% |
| JUMP_BACKWARD | 436,320 | 12.0% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 431,993 | 21.8% |
| LOAD_FAST_AND_CLEAR | 384,215 | 19.4% |
| BUILD_LIST | 384,215 | 19.4% |
| FOR_ITER_LIST | 373,655 | 18.9% |
| LOAD_FAST | 201,698 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 431,983 | 21.8% |
| LOAD_CONST | 394,778 | 19.9% |
| STORE_FAST | 384,215 | 19.4% |
| BUILD_LIST | 384,215 | 19.4% |
| FOR_ITER_LIST | 373,655 | 18.9% |


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

### BINARY_OP_ADD_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 193,563 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 193,563 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 820,303 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 431,993 | 51.8% |
| STORE_FAST | 384,000 | 46.0% |
| BINARY_SLICE | 13,920 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,320 | 0.5% |


</details>

### BINARY_OP_MULTIPLY_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 84,480 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 66.7% |
| BINARY_OP | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT_RHS

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT_RHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 181,058 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 181,058 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,770 | 79.0% |
| LOAD_CONST | 48,594 | 19.3% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 247,364 | 98.3% |
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
| LOAD_FAST_LOAD_FAST | 361,150 | 97.7% |
| LOAD_CONST | 8,640 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 361,150 | 97.7% |
| LOAD_CONST | 8,640 | 2.3% |


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
| LOAD_GLOBAL_MODULE | 394,778 | 49.4% |
| LOAD_FAST | 379,418 | 47.5% |
| CALL | 24,960 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 425,018 | 53.2% |
| COPY_FREE_VARS | 374,138 | 46.8% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 48,552 | 45.7% |
| LOAD_FAST | 48,000 | 45.2% |
| LOAD_CONST | 5,280 | 5.0% |
| BINARY_OP_ADD_INT | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 101,843 | 95.9% |
| POP_TOP | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 39.3% |
| LOAD_FAST | 207,083 | 21.2% |
| CALL_LEN | 180,575 | 18.5% |
| CALL_BUILTIN_CLASS | 180,575 | 18.5% |
| LOAD_CONST | 11,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 577,563 | 59.2% |
| GET_ITER | 205,055 | 21.0% |
| CALL_BUILTIN_CLASS | 180,575 | 18.5% |
| LOAD_FAST | 12,960 | 1.3% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 672,009 | 48.6% |
| LOAD_CONST | 479,230 | 34.6% |
| LOAD_FAST_LOAD_FAST | 129,650 | 9.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60,985 | 4.4% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 472,030 | 34.1% |
| STORE_FAST | 446,090 | 32.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 348,472 | 25.2% |
| UNPACK_SEQUENCE_TUPLE | 60,985 | 4.4% |
| POP_TOP | 10,937 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,800 | 45.6% |
| BUILD_TUPLE | 384,000 | 45.0% |
| CALL | 48,567 | 5.7% |
| LOAD_FAST_CHECK | 12,418 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 790,560 | 92.7% |
| RETURN_VALUE | 60,985 | 7.2% |
| LOAD_FAST | 960 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT_LHS | 84,480 | 88.9% |
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
| LOAD_GLOBAL_BUILTIN | 906,614 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 906,614 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 452,218 | 95.6% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,290 | 54.6% |
| CALL_BUILTIN_CLASS | 180,575 | 38.2% |
| CALL_PY_EXACT_ARGS | 24,960 | 5.3% |
| LOAD_FAST | 4,320 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 193,080 | 95.7% |
| LOAD_FAST | 8,640 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 193,080 | 95.7% |
| LOAD_GLOBAL_MODULE | 8,640 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,267,792 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,954 | 0.2% |
| LOAD_CONST | 960 | 0.1% |
| CALL | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 893,654 | 70.3% |
| STORE_FAST | 376,102 | 29.6% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,051,698 | 93.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,403 | 6.5% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 486,206 | 43.1% |
| STORE_FAST | 432,000 | 38.3% |
| LOAD_FAST | 63,840 | 5.7% |
| CALL_BUILTIN_FAST | 60,985 | 5.4% |
| RETURN_VALUE | 38,756 | 3.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 674,661 | 92.1% |
| LOAD_CONST | 24,480 | 3.3% |
| CALL | 21,610 | 3.0% |
| RETURN_VALUE | 10,560 | 1.4% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 696,271 | 95.1% |
| LOAD_CONST | 24,480 | 3.3% |
| RETURN_VALUE | 10,560 | 1.4% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,246,961 | 44.9% |
| LOAD_FAST | 3,957,453 | 41.9% |
| LOAD_FAST_LOAD_FAST | 623,135 | 6.6% |
| LOAD_SUPER_ATTR_METHOD | 374,138 | 4.0% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,418,375 | 99.6% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 924,156 | 41.6% |
| LOAD_ATTR_MODULE | 893,654 | 40.2% |
| LOAD_FAST | 255,480 | 11.5% |
| LOAD_CONST | 80,591 | 3.6% |
| BINARY_OP | 62,880 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,326,947 | 59.8% |
| COPY_FREE_VARS | 893,654 | 40.2% |


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
| LOAD_CONST | 1,547,696 | 54.7% |
| LOAD_ATTR_INSTANCE_VALUE | 816,688 | 28.9% |
| LOAD_FAST | 432,000 | 15.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,826,184 | 99.9% |
| POP_JUMP_IF_TRUE | 2,231 | 0.1% |
| COMPARE_OP | 66 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,065,763 | 95.6% |
| LOAD_CONST | 44,640 | 4.0% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 11 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,085,375 | 97.4% |
| LOAD_FAST | 10,560 | 0.9% |
| COPY | 10,560 | 0.9% |
| POP_JUMP_IF_TRUE | 8,239 | 0.7% |


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
| JUMP_BACKWARD | 5,972,004 | 79.3% |
| GET_ITER | 1,186,516 | 15.8% |
| SWAP | 373,655 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,320,000 | 57.4% |
| STORE_FAST | 1,265,844 | 16.8% |
| LOAD_FAST | 748,276 | 9.9% |
| JUMP_BACKWARD | 432,000 | 5.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 386,160 | 5.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 381,877 | 65.6% |
| GET_ITER | 199,895 | 34.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 392,917 | 67.5% |
| LOAD_FAST | 180,695 | 31.1% |
| RETURN_CONST | 8,160 | 1.4% |


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
| LOAD_GLOBAL_MODULE | 60,985 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,247 | 81.9% |
| LOAD_FAST_CHECK | 12,418 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,664,813 | 90.4% |
| LOAD_FAST_LOAD_FAST | 1,306,480 | 7.1% |
| COPY | 431,983 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 18,131 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,220,006 | 22.9% |
| LOAD_FAST | 2,797,372 | 15.2% |
| TO_BOOL_BOOL | 1,415,227 | 7.7% |
| LOAD_ATTR | 1,360,016 | 7.4% |
| CONTAINS_OP | 1,325,647 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 121,970 | 39.8% |
| CALL | 111,447 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,403 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,220,006 | 86.9% |
| LOAD_FAST | 487,865 | 10.0% |
| LOAD_ATTR | 62,900 | 1.3% |
| LOAD_ATTR_SLOT | 62,880 | 1.3% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,908,857 | 39.3% |
| CALL | 1,090,902 | 22.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,051,698 | 21.7% |
| LOAD_CONST | 557,902 | 11.5% |
| LOAD_FAST_LOAD_FAST | 224,772 | 4.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,055,687 | 71.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,012,806 | 12.0% |
| LOAD_FAST_LOAD_FAST | 893,654 | 10.6% |
| BINARY_SUBSCR | 432,000 | 5.1% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,246,961 | 50.4% |
| LOAD_FAST | 2,577,582 | 30.6% |
| CALL_PY_WITH_DEFAULTS | 924,156 | 11.0% |
| LOAD_FAST_LOAD_FAST | 508,800 | 6.0% |
| LOAD_CONST | 94,511 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,722,299 | 100.0% |
| LOAD_ATTR | 91 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,717,839 | 63.1% |
| CALL_PY_WITH_DEFAULTS | 893,654 | 32.8% |
| STORE_DEREF | 41,280 | 1.5% |
| LOAD_CONST | 26,400 | 1.0% |
| LOAD_FAST | 20,640 | 0.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 924,374 | 70.5% |
| LOAD_FAST_LOAD_FAST | 386,160 | 29.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 893,654 | 68.2% |
| UNARY_INVERT | 386,160 | 29.5% |
| RETURN_VALUE | 10,560 | 0.8% |
| LOAD_CONST | 10,560 | 0.8% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 761,565 | 97.2% |
| RETURN_VALUE | 20,640 | 2.6% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 774,205 | 98.8% |
| TO_BOOL_BOOL | 8,960 | 1.1% |
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
| RESUME_CHECK | 2,759,526 | 41.8% |
| LOAD_FAST | 926,774 | 14.1% |
| STORE_FAST | 903,338 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 745,150 | 11.3% |
| NOP | 552,110 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,040,815 | 46.1% |
| LOAD_DEREF | 1,349,872 | 20.5% |
| CALL_ISINSTANCE | 906,614 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 745,150 | 11.3% |
| LOAD_GLOBAL_MODULE | 468,960 | 7.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,686,767 | 28.7% |
| RESUME_CHECK | 2,348,546 | 18.3% |
| NOP | 1,359,143 | 10.6% |
| POP_JUMP_IF_FALSE | 1,100,931 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,087,674 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,874,042 | 22.4% |
| LOAD_ATTR_MODULE | 2,722,299 | 21.2% |
| LOAD_FAST_LOAD_FAST | 2,016,363 | 15.7% |
| LOAD_FAST | 1,623,595 | 12.6% |
| COMPARE_OP_STR | 1,065,763 | 8.3% |


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
| LOAD_FAST | 1,282,672 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 904,214 | 70.5% |
| CALL_PY_EXACT_ARGS | 374,138 | 29.2% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 9,418,375 | 33.6% |
| CACHE | 8,860,630 | 31.6% |
| FOR_ITER_GEN | 4,752,000 | 17.0% |
| COPY_FREE_VARS | 1,354,312 | 4.8% |
| CALL_PY_WITH_DEFAULTS | 1,326,947 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,699,801 | 56.0% |
| POP_TOP | 5,184,960 | 18.5% |
| LOAD_GLOBAL_BUILTIN | 2,759,526 | 9.8% |
| LOAD_GLOBAL_MODULE | 2,348,546 | 8.4% |
| NOP | 1,044,854 | 3.7% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,205,030 | 68.2% |
| LOAD_FAST_LOAD_FAST | 570,458 | 17.6% |
| SWAP | 431,983 | 13.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,656,392 | 51.2% |
| LOAD_FAST | 684,953 | 21.2% |
| LOAD_GLOBAL_MODULE | 533,498 | 16.5% |
| LOAD_CONST | 160,318 | 5.0% |
| LOAD_FAST_LOAD_FAST | 96,960 | 3.0% |


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
| LOAD_ATTR | 893,654 | 93.0% |
| LOAD_FAST | 33,154 | 3.4% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.7% |
| CALL | 7,680 | 0.8% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 895,618 | 93.2% |
| RETURN_CONST | 24,480 | 2.5% |
| LOAD_GLOBAL_MODULE | 20,640 | 2.1% |
| LOAD_CONST | 20,640 | 2.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,415,227 | 26.7% |
| CALL_ISINSTANCE | 906,614 | 17.1% |
| RETURN_VALUE | 685,220 | 13.0% |
| CALL | 551,597 | 10.4% |
| LOAD_FAST | 542,994 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,688,853 | 69.7% |
| POP_JUMP_IF_TRUE | 1,389,661 | 26.3% |
| UNARY_NOT | 212,599 | 4.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,173,468 | 54.9% |
| LOAD_FAST | 893,654 | 22.6% |
| BINARY_OP | 893,654 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,960,776 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 382,778 | 92.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 414,938 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,831 | 79.8% |
| LOAD_FAST | 20,640 | 11.4% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,431 | 91.7% |
| POP_JUMP_IF_TRUE | 14,880 | 8.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,000 | 93.0% |
| CALL_BUILTIN_FAST | 60,985 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 60,985 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 436,320 | 27.0% |
| LOAD_FAST_CHECK | 432,000 | 26.7% |
| FOR_ITER_LIST | 386,160 | 23.9% |
| CALL_BUILTIN_FAST | 348,472 | 21.6% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,610,152 | 99.7% |
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
| LOAD_FAST | 960 | 50.0% |
| LOAD_CONST | 960 | 50.0% |


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
| STORE_FAST | 480 | 60.7% |
| COPY | 311 | 39.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 60.7% |
| POP_JUMP_IF_FALSE | 311 | 39.3% |


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
| specialization.deferred |       480594 | 45.8% |
|          hit |       568510 | 54.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 220 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 220 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        22567 | 2.3% |
|          hit |       961378 | 97.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 10 | 4.8% |
| Failure | 200 | 95.2% |

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
| specialization.deferred |      1190112 | 10.8% |
|          hit |      9847929 | 89.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 1,048 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 328 | 31.3% |
| tuple | 220 | 21.0% |
| sequence | 220 | 21.0% |
| set | 200 | 19.1% |
| other | 80 | 7.6% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5354188 | 77.3% |
|          hit |      1567698 | 22.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 50 | 2.4% |
| Failure | 2,013 | 97.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,005 | 49.9% |
| or | 582 | 28.9% |
| remainder | 226 | 11.2% |
| add different types | 160 | 7.9% |
| add other | 40 | 2.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8774685 | 29.3% |
| specialization.deopt |           60 | 0.0% |
|          hit |     21175030 | 70.7% |
|         miss |         4380 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 131 | 1.4% |
| Failure | 8,997 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,520 | 28.0% |
| cfunc noargs | 1,790 | 19.9% |
| class no vectorcall | 1,267 | 14.1% |
| meth descr varargs keywords | 838 | 9.3% |
| class mutable | 407 | 4.5% |
| other | 360 | 4.0% |
| cfunc varargs keywords | 327 | 3.6% |
| cfunc varargs | 320 | 3.6% |
| bound method | 288 | 3.2% |
| operator wrapper | 240 | 2.7% |
| meth descr method fastcall keywords | 200 | 2.2% |
| cmethod | 200 | 2.2% |
| wrong number arguments | 160 | 1.8% |
| method wrapper | 80 | 0.9% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       438198 | 10.0% |
| specialization.deopt |           66 | 0.0% |
|          hit |      3938405 | 89.9% |
|         miss |         4810 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 117 | 24.9% |
| Failure | 352 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 160 | 45.5% |
| different types | 112 | 31.8% |
| big int | 80 | 22.7% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       976320 | 7.0% |
|          hit |     12894747 | 93.0% |

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
| specialization.deferred |      7797313 | 17.4% |
| specialization.deopt |         4193 | 0.0% |
|          hit |     36753065 | 82.1% |
|         miss |       230168 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,385 | 42.3% |
| Failure | 5,970 | 57.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,404 | 23.5% |
| shadowed | 1,201 | 20.1% |
| not managed dict | 1,197 | 20.1% |
| non overriding descriptor | 604 | 10.1% |
| class attr descriptor | 360 | 6.0% |
| metaclass attribute | 280 | 4.7% |
| class method obj | 280 | 4.7% |
| has managed dict | 240 | 4.0% |
| non object slot | 160 | 2.7% |
| class attr simple | 124 | 2.1% |
| mutable class | 80 | 1.3% |
| overridden | 40 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           56 | 0.0% |
| specialization.deopt |           62 | 0.0% |
|          hit |     19438339 | 100.0% |
|         miss |         5340 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 204 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1349872 | 100.0% |


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
| specialization.deferred |        65769 | 1.9% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      3159101 | 93.6% |
|         miss |       148120 | 4.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,790 | 81.3% |
| Failure | 640 | 18.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| property | 400 | 62.5% |
| class attr simple | 160 | 25.0% |
| no dict | 80 | 12.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2492417 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 228,588,661 | 53.0% |
| Not specialized | 60,291,608 | 14.0% |
| Specialized | 142,075,546 | 33.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,774,685 | 35.0% |
| LOAD_ATTR | 7,797,313 | 31.1% |
| BINARY_OP | 5,354,188 | 21.3% |
| TO_BOOL | 1,190,112 | 4.7% |
| FOR_ITER | 976,320 | 3.9% |
| BINARY_SUBSCR | 480,594 | 1.9% |
| COMPARE_OP | 438,198 | 1.7% |
| STORE_ATTR | 65,769 | 0.3% |
| STORE_SUBSCR | 22,567 | 0.1% |
| LOAD_GLOBAL | 56 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,326 | 40.8% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,722 | 15.5% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| LOAD_GLOBAL_MODULE | 5,340 | 1.4% |
| COMPARE_OP_INT | 4,810 | 1.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,380 | 1.1% |
| YIELD_VALUE | 0 | 0.0% |
| WITH_EXCEPT_START | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 8,947,990 | 31.9% |
| Calls to Python functions inlined | 19,096,828 | 68.1% |
| Calls via PyEval_EvalFrame (total) | 8,947,990 | 31.9% |
| Calls via PyEval_EvalFrame (vector) | 8,509,750 | 30.3% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,509,750 | 30.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 476,744 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 23,645,094 | 84.3% |
| Frame objects created | 40,493 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 15,066,213 | 42.8% |
| Frees to freelist | 15,067,646 |  |
| Allocations | 20,114,973 | 57.2% |
| Allocations to 512 bytes | 19,903,196 | 56.6% |
| Allocations to 4 kbytes | 86,005 | 0.2% |
| Allocations over 4 kbytes | 125,772 | 0.4% |
| Frees | 21,271,050 |  |
| New values | 65,280 |  |
| Interpreter increfs | 168,896,420 | 77.0% |
| Interpreter decrefs | 185,033,917 | 73.7% |
| Increfs | 50,428,013 | 23.0% |
| Decrefs | 66,014,085 | 26.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 9,167,179 |  |
| Method cache misses | 26,026 |  |
| Method cache collisions | 44,277 |  |
| Method cache dunder hits | 8,591,650 |  |
| Method cache dunder misses | 18,251 |  |


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

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 0 |  |
| Uops executed | 0 | 0 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |


</details>

**Trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|


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
Stats gathered on: 2023-10-19
