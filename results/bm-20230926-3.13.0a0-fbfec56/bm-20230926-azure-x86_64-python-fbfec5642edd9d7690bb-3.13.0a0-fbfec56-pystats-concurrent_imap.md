
# Pystats results

- benchmark: concurrent_imap
- fork: python
- ref: fbfec5642edd9d7690bbff088ee43c08e8067044
- commit hash: fbfec56
- commit date: 2023-09-26T20:46:52+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 75,610,048 | 17.6% | 17.6% |  |
| RESUME_CHECK | 27,908,571 | 6.5% | 24.1% | 0.0% |
| STORE_FAST | 22,181,357 | 5.2% | 29.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,340,036 | 4.3% | 33.6% | 0.9% |
| POP_TOP | 18,063,294 | 4.2% | 37.8% |  |
| RETURN_VALUE | 16,568,120 | 3.9% | 41.7% |  |
| POP_JUMP_IF_FALSE | 14,434,019 | 3.4% | 45.0% |  |
| JUMP_BACKWARD | 13,507,212 | 3.2% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 12,762,977 | 3.0% | 51.2% | 0.1% |
| LOAD_FAST_LOAD_FAST | 11,779,498 | 2.7% | 53.9% |  |
| LOAD_CONST | 11,519,278 | 2.7% | 56.6% |  |
| CALL_PY_EXACT_ARGS | 9,376,667 | 2.2% | 58.8% |  |
| INTERPRETER_EXIT | 8,926,514 | 2.1% | 60.9% |  |
| CALL | 8,737,371 | 2.0% | 62.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,364,274 | 2.0% | 64.9% | 0.7% |
| LOAD_ATTR | 7,753,670 | 1.8% | 66.7% |  |
| NOP | 7,512,875 | 1.8% | 68.4% |  |
| FOR_ITER_LIST | 7,508,910 | 1.8% | 70.2% |  |
| RETURN_CONST | 6,944,177 | 1.6% | 71.8% |  |
| LOAD_GLOBAL_BUILTIN | 6,551,605 | 1.5% | 73.3% |  |
| PUSH_NULL | 5,525,849 | 1.3% | 74.6% |  |
| COPY | 5,441,589 | 1.3% | 75.9% |  |
| BINARY_OP | 5,310,910 | 1.2% | 77.1% |  |
| TO_BOOL_BOOL | 5,254,410 | 1.2% | 78.3% |  |
| YIELD_VALUE | 5,184,960 | 1.2% | 79.6% |  |
| STORE_FAST_LOAD_FAST | 4,847,040 | 1.1% | 80.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,814,273 | 1.1% | 81.8% |  |
| FOR_ITER_GEN | 4,760,640 | 1.1% | 82.9% |  |
| TO_BOOL_INT | 3,926,342 | 0.9% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,792,540 | 0.9% | 84.7% |  |
| STORE_FAST_STORE_FAST | 3,624,241 | 0.8% | 85.6% |  |
| BUILD_TUPLE | 3,222,960 | 0.8% | 86.3% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,218,363 | 0.8% | 87.1% | 4.6% |
| COMPARE_OP_INT | 2,812,031 | 0.7% | 87.7% | 0.2% |
| LOAD_ATTR_MODULE | 2,708,373 | 0.6% | 88.4% |  |
| CALL_PY_WITH_DEFAULTS | 2,207,232 | 0.5% | 88.9% |  |
| POP_JUMP_IF_TRUE | 2,038,185 | 0.5% | 89.3% |  |
| SWAP | 1,967,086 | 0.5% | 89.8% |  |
| CALL_FUNCTION_EX | 1,810,145 | 0.4% | 90.2% |  |
| GET_ITER | 1,791,019 | 0.4% | 90.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,609,201 | 0.4% | 91.0% |  |
| LOAD_DEREF | 1,380,464 | 0.3% | 91.3% |  |
| BEFORE_WITH | 1,377,563 | 0.3% | 91.7% |  |
| CALL_BUILTIN_FAST | 1,376,379 | 0.3% | 92.0% |  |
| COPY_FREE_VARS | 1,343,384 | 0.3% | 92.3% |  |
| CONTAINS_OP | 1,317,811 | 0.3% | 92.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,299,629 | 0.3% | 92.9% |  |
| LOAD_SUPER_ATTR_METHOD | 1,271,744 | 0.3% | 93.2% |  |
| UNARY_INVERT | 1,268,909 | 0.3% | 93.5% |  |
| JUMP_FORWARD | 1,264,485 | 0.3% | 93.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,260,739 | 0.3% | 94.1% |  |
| BUILD_MAP | 1,256,173 | 0.3% | 94.4% |  |
| TO_BOOL | 1,185,805 | 0.3% | 94.7% |  |
| BUILD_LIST | 1,140,517 | 0.3% | 94.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,115,308 | 0.3% | 95.2% |  |
| COMPARE_OP_STR | 1,113,193 | 0.3% | 95.4% |  |
| FOR_ITER | 976,760 | 0.2% | 95.7% |  |
| CALL_BUILTIN_CLASS | 971,635 | 0.2% | 95.9% |  |
| STORE_SUBSCR_DICT | 954,486 | 0.2% | 96.1% |  |
| CALL_ISINSTANCE | 898,771 | 0.2% | 96.3% |  |
| UNPACK_SEQUENCE_TUPLE | 877,007 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 852,527 | 0.2% | 96.7% |  |
| POP_JUMP_IF_NONE | 835,817 | 0.2% | 96.9% |  |
| BINARY_OP_ADD_INT | 834,238 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 792,986 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 792,986 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 777,045 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 726,549 | 0.2% | 97.8% |  |
| LOAD_FAST_CHECK | 623,929 | 0.1% | 98.0% |  |
| LIST_APPEND | 619,201 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 577,128 | 0.1% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 572,680 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 477,926 | 0.1% | 98.5% |  |
| CALL_LEN | 471,335 | 0.1% | 98.6% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.7% |  |
| COMPARE_OP | 435,304 | 0.1% | 98.8% |  |
| DICT_MERGE | 422,880 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 411,853 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 366,684 | 0.1% | 99.1% |  |
| LIST_EXTEND | 359,004 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,908 | 0.1% | 99.3% |  |
| CALL_KW | 265,959 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 248,840 | 0.1% | 99.4% |  |
| UNARY_NOT | 211,119 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 200,189 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 192,031 | 0.0% | 99.5% |  |
| TO_BOOL_NONE | 180,319 | 0.0% | 99.6% |  |
| BINARY_OP_SUBTRACT_FLOAT | 179,624 | 0.0% | 99.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 106,238 | 0.0% | 99.6% | 4.1% |
| STORE_DEREF | 103,200 | 0.0% | 99.7% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,687 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,405 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,815 | 0.0% | 99.9% |  |
| DELETE_SUBSCR | 58,570 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 37,546 | 0.0% | 99.9% |  |
| POP_EXCEPT | 37,546 | 0.0% | 99.9% |  |
| IS_OP | 34,869 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 33,226 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 32,640 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 100.0% |  |
| IMPORT_NAME | 24,480 | 0.0% | 100.0% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,765 | 0.0% | 100.0% |  |
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
| TO_BOOL_ALWAYS_TRUE | 789 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 206 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,580,007 | 3.9% | 3.9% |
| RESUME_CHECK LOAD_FAST | 15,627,320 | 3.6% | 7.5% |
| STORE_FAST LOAD_FAST | 9,659,018 | 2.3% | 9.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,342,107 | 2.2% | 11.9% |
| CACHE RESUME_CHECK | 8,843,469 | 2.1% | 14.0% |
| LOAD_FAST RETURN_VALUE | 8,041,335 | 1.9% | 15.9% |
| RETURN_VALUE INTERPRETER_EXIT | 7,828,726 | 1.8% | 17.7% |
| POP_TOP JUMP_BACKWARD | 6,534,821 | 1.5% | 19.2% |
| LOAD_FAST LOAD_ATTR | 6,007,591 | 1.4% | 20.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 6,007,319 | 1.4% | 22.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 5,957,993 | 1.4% | 23.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,908,402 | 1.4% | 24.8% |
| POP_TOP LOAD_FAST | 5,638,592 | 1.3% | 26.1% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.2% | 27.3% |
| RETURN_CONST POP_TOP | 4,915,476 | 1.1% | 28.5% |
| NOP LOAD_FAST | 4,774,780 | 1.1% | 29.6% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.1% | 30.7% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.1% | 31.8% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.1% | 32.9% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 4,320,000 | 1.0% | 33.9% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.0% | 34.9% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 4,320,000 | 1.0% | 35.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,213,881 | 1.0% | 36.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,191,587 | 1.0% | 37.9% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,926,342 | 0.9% | 38.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,918,897 | 0.9% | 39.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,663,144 | 0.9% | 40.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,655,392 | 0.9% | 41.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,022,140 | 0.7% | 42.1% |
| LOAD_FAST LOAD_CONST | 2,964,786 | 0.7% | 42.8% |
| STORE_FAST NOP | 2,872,413 | 0.7% | 43.5% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,848,982 | 0.7% | 44.2% |
| LOAD_CONST LOAD_CONST | 2,835,343 | 0.7% | 44.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,809,738 | 0.7% | 45.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,784,440 | 0.6% | 46.1% |
| LOAD_FAST PUSH_NULL | 2,758,555 | 0.6% | 46.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,740,755 | 0.6% | 47.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,737,375 | 0.6% | 48.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,708,279 | 0.6% | 48.7% |
| LOAD_ATTR LOAD_FAST | 2,613,496 | 0.6% | 49.3% |
| PUSH_NULL LOAD_FAST | 2,609,939 | 0.6% | 49.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,551,528 | 0.6% | 50.5% |
| CALL STORE_FAST | 2,524,147 | 0.6% | 51.1% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,359,099 | 0.6% | 51.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,333,037 | 0.5% | 52.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,192,692 | 0.5% | 52.7% |
| COPY TO_BOOL_INT | 2,154,720 | 0.5% | 53.2% |
| BINARY_OP COPY | 2,154,720 | 0.5% | 53.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,999,124 | 0.5% | 54.2% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 54.6% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 55.1% |
| LOAD_CONST CALL | 1,959,398 | 0.5% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,893,114 | 0.4% | 56.0% |
| CALL RETURN_VALUE | 1,862,611 | 0.4% | 56.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,799,486 | 0.4% | 56.8% |
| RETURN_VALUE STORE_FAST | 1,718,523 | 0.4% | 57.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,711,660 | 0.4% | 57.6% |
| CALL POP_TOP | 1,696,723 | 0.4% | 58.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,644,052 | 0.4% | 58.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,611,135 | 0.4% | 58.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,603,921 | 0.4% | 59.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,540,513 | 0.4% | 59.5% |
| LOAD_CONST COMPARE_OP_INT | 1,537,103 | 0.4% | 59.9% |
| PUSH_NULL CALL | 1,525,762 | 0.4% | 60.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,522,272 | 0.4% | 60.6% |
| RETURN_VALUE RETURN_VALUE | 1,484,250 | 0.3% | 60.9% |
| LOAD_FAST_LOAD_FAST CALL | 1,440,301 | 0.3% | 61.3% |
| POP_TOP RETURN_CONST | 1,427,476 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,404,385 | 0.3% | 61.9% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,265 | 0.3% | 62.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,380,147 | 0.3% | 62.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,356,926 | 0.3% | 62.9% |
| NOP LOAD_GLOBAL_MODULE | 1,348,136 | 0.3% | 63.2% |
| COPY_FREE_VARS RESUME_CHECK | 1,343,384 | 0.3% | 63.5% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,338,944 | 0.3% | 63.8% |
| LOAD_DEREF LOAD_FAST | 1,338,944 | 0.3% | 64.2% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,321,421 | 0.3% | 64.5% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,317,811 | 0.3% | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,317,809 | 0.3% | 65.1% |
| LOAD_FAST BUILD_TUPLE | 1,310,611 | 0.3% | 65.4% |
| POP_TOP LOAD_CONST | 1,300,919 | 0.3% | 65.7% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,296,426 | 0.3% | 66.0% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,271,744 | 0.3% | 66.3% |
| UNARY_INVERT BINARY_OP | 1,268,909 | 0.3% | 66.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,256,864 | 0.3% | 66.9% |
| FOR_ITER_LIST STORE_FAST | 1,254,895 | 0.3% | 67.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,199,098 | 0.3% | 67.4% |
| LOAD_CONST LOAD_FAST | 1,196,054 | 0.3% | 67.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,185,166 | 0.3% | 68.0% |
| GET_ITER FOR_ITER_LIST | 1,180,346 | 0.3% | 68.3% |
| POP_TOP NOP | 1,178,570 | 0.3% | 68.5% |
| LOAD_FAST TO_BOOL | 1,144,898 | 0.3% | 68.8% |
| LOAD_FAST GET_ITER | 1,135,357 | 0.3% | 69.1% |
| RETURN_VALUE POP_TOP | 1,127,386 | 0.3% | 69.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,114,837 | 0.3% | 69.6% |
| POP_JUMP_IF_FALSE POP_TOP | 1,110,895 | 0.3% | 69.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,093,075 | 0.3% | 70.1% |
| BINARY_OP STORE_FAST | 1,087,920 | 0.3% | 70.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,086,131 | 0.3% | 70.6% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,083,822 | 0.3% | 70.9% |


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
| RESUME_CHECK | 8,843,469 | 99.0% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 940,265 | 68.3% |
| RETURN_VALUE | 371,053 | 26.9% |
| LOAD_GLOBAL_MODULE | 61,925 | 4.5% |
| CALL | 4,320 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,190 | 72.8% |
| STORE_FAST | 375,373 | 27.2% |


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
| LOAD_FAST_LOAD_FAST | 432,000 | 90.4% |
| LOAD_CONST | 45,706 | 9.6% |
| BINARY_SUBSCR | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.4% |
| STORE_FAST | 45,706 | 9.6% |
| BINARY_SUBSCR | 220 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 29,386 | 88.4% |
| LOAD_ATTR_MODULE | 3,840 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,226 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,325 | 48.4% |
| CALL | 20,645 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,600 | 16.4% |

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
| RETURN_CONST | 792,986 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 792,986 | 100.0% |


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
| LOAD_FAST | 1,135,357 | 63.4% |
| STORE_FAST_LOAD_FAST | 432,000 | 24.1% |
| CALL_BUILTIN_CLASS | 203,502 | 11.4% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,180,346 | 65.9% |
| LOAD_FAST_AND_CLEAR | 381,131 | 21.3% |
| FOR_ITER_RANGE | 198,342 | 11.1% |
| FOR_ITER_TUPLE | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,828,726 | 87.7% |
| RETURN_CONST | 664,828 | 7.4% |
| YIELD_VALUE | 432,960 | 4.9% |

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
| STORE_FAST | 2,872,413 | 38.2% |
| POP_TOP | 1,178,570 | 15.7% |
| RESUME_CHECK | 1,037,011 | 13.8% |
| POP_JUMP_IF_FALSE | 1,002,964 | 13.3% |
| JUMP_BACKWARD | 816,000 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,774,780 | 63.6% |
| LOAD_GLOBAL_MODULE | 1,348,136 | 17.9% |
| LOAD_GLOBAL_BUILTIN | 547,439 | 7.3% |
| LOAD_FAST_LOAD_FAST | 437,280 | 5.8% |
| LOAD_CONST | 396,960 | 5.3% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 25,066 | 66.8% |
| COPY | 8,640 | 23.0% |
| POP_TOP | 3,840 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 25,066 | 66.8% |
| RERAISE | 8,640 | 23.0% |
| JUMP_FORWARD | 3,840 | 10.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,184,960 | 28.7% |
| RETURN_CONST | 4,915,476 | 27.2% |
| CALL | 1,696,723 | 9.4% |
| RETURN_VALUE | 1,127,386 | 6.2% |
| POP_JUMP_IF_FALSE | 1,110,895 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,534,821 | 36.2% |
| LOAD_FAST | 5,638,592 | 31.2% |
| RETURN_CONST | 1,427,476 | 7.9% |
| LOAD_CONST | 1,300,919 | 7.2% |
| NOP | 1,178,570 | 6.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,386 | 78.3% |
| RERAISE | 4,320 | 11.5% |
| CALL_KW | 3,840 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 29,386 | 78.3% |
| WITH_EXCEPT_START | 4,320 | 11.5% |
| LOAD_GLOBAL_MODULE | 3,840 | 10.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,758,555 | 49.9% |
| LOAD_ATTR_MODULE | 1,711,660 | 31.0% |
| LOAD_ATTR | 961,434 | 17.4% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,609,939 | 47.2% |
| CALL | 1,525,762 | 27.6% |
| LOAD_FAST_LOAD_FAST | 1,046,494 | 18.9% |
| LOAD_CONST | 240,366 | 4.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 48,568 | 0.9% |


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
| LOAD_FAST | 8,041,335 | 48.5% |
| CALL | 1,862,611 | 11.2% |
| RETURN_VALUE | 1,484,250 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,185,166 | 7.2% |
| CALL_FUNCTION_EX | 948,905 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,828,726 | 47.3% |
| STORE_FAST | 1,718,523 | 10.4% |
| RETURN_VALUE | 1,484,250 | 9.0% |
| POP_TOP | 1,127,386 | 6.8% |
| LOAD_FAST_LOAD_FAST | 885,811 | 5.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,685 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.4% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 3 | 0.0% |
| LOAD_FAST | 2 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,144,898 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,852 | 3.4% |
| TO_BOOL | 1,047 | 0.1% |
| LOAD_ATTR | 5 | 0.0% |
| RETURN_VALUE | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 632,194 | 53.3% |
| POP_JUMP_IF_FALSE | 552,561 | 46.6% |
| TO_BOOL | 1,047 | 0.1% |
| TO_BOOL_BOOL | 2 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 1 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 885,811 | 69.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 383,098 | 30.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,268,909 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 211,119 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 211,119 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,848,982 | 53.6% |
| UNARY_INVERT | 1,268,909 | 23.9% |
| POP_JUMP_IF_FALSE | 885,811 | 16.7% |
| LOAD_ATTR | 202,109 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,154,720 | 40.6% |
| STORE_FAST | 1,087,920 | 20.5% |
| UNARY_INVERT | 885,811 | 16.7% |
| TO_BOOL_INT | 885,811 | 16.7% |
| BUILD_TUPLE | 191,549 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 381,131 | 33.4% |
| JUMP_FORWARD | 371,053 | 32.5% |
| LOAD_FAST | 192,031 | 16.8% |
| POP_TOP | 179,022 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 383,533 | 33.6% |
| SWAP | 381,131 | 33.4% |
| STORE_FAST | 372,013 | 32.6% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 432,000 | 34.4% |
| LOAD_FAST | 396,960 | 31.6% |
| RESUME_CHECK | 378,733 | 30.1% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.1% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 811,213 | 64.6% |
| BUILD_TUPLE | 432,000 | 34.4% |
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
| LOAD_FAST | 1,310,611 | 40.7% |
| LOAD_FAST_LOAD_FAST | 870,240 | 27.0% |
| BUILD_MAP | 432,000 | 13.4% |
| RETURN_VALUE | 384,000 | 11.9% |
| BINARY_OP | 191,549 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 886,771 | 27.5% |
| YIELD_VALUE | 864,000 | 26.8% |
| BUILD_MAP | 432,000 | 13.4% |
| STORE_FAST | 384,000 | 11.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 11.9% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,959,398 | 22.4% |
| PUSH_NULL | 1,525,762 | 17.5% |
| LOAD_FAST_LOAD_FAST | 1,440,301 | 16.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,082,238 | 12.4% |
| BUILD_TUPLE | 886,771 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,524,147 | 28.9% |
| RETURN_VALUE | 1,862,611 | 21.3% |
| POP_TOP | 1,696,723 | 19.4% |
| LOAD_FAST | 782,564 | 9.0% |
| TO_BOOL_BOOL | 547,839 | 6.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,265 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,905 | 52.4% |
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
| LOAD_CONST | 265,959 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 214,062 | 80.5% |
| LOAD_FAST | 21,600 | 8.1% |
| RETURN_VALUE | 15,840 | 6.0% |
| STORE_FAST | 10,560 | 4.0% |
| PUSH_EXC_INFO | 3,840 | 1.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 434,771 | 99.9% |
| COMPARE_OP | 278 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 176 | 0.0% |
| COMPARE_OP_INT | 64 | 0.0% |
| LOAD_GLOBAL_MODULE | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 434,905 | 99.9% |
| COMPARE_OP | 278 | 0.1% |
| COMPARE_OP_INT | 107 | 0.0% |
| COMPARE_OP_STR | 10 | 0.0% |
| POP_JUMP_IF_TRUE | 4 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,317,809 | 100.0% |
| LOAD_ATTR | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,317,811 | 100.0% |


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
| BINARY_OP | 2,154,720 | 39.6% |
| STORE_FAST | 1,972,320 | 36.2% |
| LOAD_CONST | 825,600 | 15.2% |
| LOAD_FAST | 442,560 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,154,720 | 39.6% |
| STORE_FAST | 1,972,800 | 36.3% |
| STORE_FAST_STORE_FAST | 820,320 | 15.1% |
| LOAD_ATTR_INSTANCE_VALUE | 431,995 | 7.9% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 885,811 | 65.9% |
| CALL_ALLOC_AND_ENTER_INIT | 371,053 | 27.6% |
| CACHE | 82,080 | 6.1% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,343,384 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 1,269 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,869 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,534,821 | 48.4% |
| STORE_FAST | 4,320,000 | 32.0% |
| POP_JUMP_IF_NOT_NONE | 742,524 | 5.5% |
| LIST_APPEND | 619,201 | 4.6% |
| STORE_FAST_STORE_FAST | 436,320 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,957,993 | 44.1% |
| FOR_ITER_GEN | 4,752,000 | 35.2% |
| FOR_ITER | 952,800 | 7.1% |
| NOP | 816,000 | 6.0% |
| LOAD_GLOBAL_BUILTIN | 432,000 | 3.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 798,917 | 63.2% |
| POP_TOP | 452,128 | 35.8% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 836,201 | 66.1% |
| BUILD_LIST | 371,053 | 29.3% |
| POP_EXCEPT | 25,066 | 2.0% |
| LOAD_GLOBAL_MODULE | 18,725 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 343,172 | 55.4% |
| LOAD_ATTR | 191,549 | 30.9% |
| BINARY_SUBSCR_STR_INT | 84,480 | 13.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 619,201 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 179,982 | 50.1% |
| RETURN_VALUE | 179,022 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 179,502 | 50.0% |
| STORE_FAST | 179,022 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,007,591 | 77.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,356,926 | 17.5% |
| LOAD_GLOBAL_MODULE | 294,797 | 3.8% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,885 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,613,496 | 33.7% |
| PUSH_NULL | 961,434 | 12.4% |
| STORE_SUBSCR_DICT | 885,811 | 11.4% |
| POP_JUMP_IF_NOT_NONE | 858,557 | 11.1% |
| STORE_FAST | 553,547 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,964,786 | 25.7% |
| LOAD_CONST | 2,835,343 | 24.6% |
| POP_TOP | 1,300,919 | 11.3% |
| POP_JUMP_IF_FALSE | 688,180 | 6.0% |
| LOAD_ATTR_METHOD_NO_DICT | 554,046 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,835,343 | 24.6% |
| CALL | 1,959,398 | 17.0% |
| COMPARE_OP_INT | 1,537,103 | 13.3% |
| LOAD_FAST | 1,196,054 | 10.4% |
| COPY | 825,600 | 7.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,338,944 | 97.0% |
| STORE_DEREF | 20,640 | 1.5% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.5% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,338,944 | 97.0% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 3.0% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,627,320 | 20.7% |
| STORE_FAST | 9,659,018 | 12.8% |
| POP_JUMP_IF_FALSE | 5,908,402 | 7.8% |
| POP_TOP | 5,638,592 | 7.5% |
| NOP | 4,774,780 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,580,007 | 21.9% |
| RETURN_VALUE | 8,041,335 | 10.6% |
| LOAD_ATTR | 6,007,591 | 7.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,007,319 | 7.9% |
| CALL_PY_EXACT_ARGS | 3,918,897 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 381,131 | 66.6% |
| LOAD_FAST_AND_CLEAR | 191,549 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 381,131 | 66.6% |
| LOAD_FAST_AND_CLEAR | 191,549 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 69.2% |
| POP_JUMP_IF_NONE | 179,504 | 28.8% |
| LOAD_ATTR_CLASS | 12,425 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 69.2% |
| LOAD_GLOBAL_MODULE | 179,504 | 28.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,425 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,999,124 | 17.0% |
| LOAD_FAST_LOAD_FAST | 1,540,513 | 13.1% |
| POP_JUMP_IF_FALSE | 1,114,837 | 9.5% |
| PUSH_NULL | 1,046,494 | 8.9% |
| LOAD_SUPER_ATTR_METHOD | 896,371 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,737,375 | 23.2% |
| LOAD_FAST_LOAD_FAST | 1,540,513 | 13.1% |
| CALL | 1,440,301 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,296,426 | 11.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 885,811 | 7.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 38.8% |
| RESUME_CHECK | 40 | 19.4% |
| POP_JUMP_IF_FALSE | 40 | 19.4% |
| POP_JUMP_IF_TRUE | 22 | 10.7% |
| LOAD_ATTR_INSTANCE_VALUE | 11 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 106 | 51.5% |
| LOAD_ATTR | 49 | 23.8% |
| LOAD_GLOBAL_BUILTIN | 42 | 20.4% |
| LOAD_FAST | 5 | 2.4% |
| COMPARE_OP | 4 | 1.9% |


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
| TO_BOOL_INT | 3,926,342 | 27.2% |
| TO_BOOL_BOOL | 3,663,144 | 25.4% |
| COMPARE_OP_INT | 2,809,738 | 19.5% |
| CONTAINS_OP | 1,317,811 | 9.1% |
| COMPARE_OP_STR | 1,083,822 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,908,402 | 40.9% |
| RETURN_CONST | 2,359,099 | 16.3% |
| LOAD_FAST_LOAD_FAST | 1,114,837 | 7.7% |
| POP_TOP | 1,110,895 | 7.7% |
| LOAD_GLOBAL_MODULE | 1,093,075 | 7.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 791,177 | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.7% |
| LOAD_ATTR | 21,120 | 2.5% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 219,219 | 26.2% |
| NOP | 207,342 | 24.8% |
| LOAD_FAST | 192,693 | 23.1% |
| LOAD_FAST_CHECK | 179,504 | 21.5% |
| RETURN_CONST | 18,240 | 2.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,799,486 | 47.4% |
| LOAD_ATTR | 858,557 | 22.6% |
| LOAD_ATTR_INSTANCE_VALUE | 734,693 | 19.4% |
| RETURN_VALUE | 343,652 | 9.1% |
| LOAD_DEREF | 41,280 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,522,272 | 40.1% |
| RETURN_CONST | 858,866 | 22.6% |
| JUMP_BACKWARD | 742,524 | 19.6% |
| NOP | 377,455 | 10.0% |
| LOAD_CONST | 179,022 | 4.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,380,147 | 67.7% |
| TO_BOOL | 632,194 | 31.0% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,251 | 0.4% |
| COMPARE_OP_INT | 2,229 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 714,909 | 35.1% |
| LOAD_FAST_LOAD_FAST | 635,069 | 31.2% |
| RETURN_CONST | 548,594 | 26.9% |
| LOAD_GLOBAL_MODULE | 54,831 | 2.7% |
| RETURN_VALUE | 45,706 | 2.2% |


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
| POP_JUMP_IF_FALSE | 2,359,099 | 34.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,644,052 | 23.7% |
| POP_TOP | 1,427,476 | 20.6% |
| POP_JUMP_IF_NOT_NONE | 858,866 | 12.4% |
| POP_JUMP_IF_TRUE | 548,594 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,915,476 | 70.8% |
| EXIT_INIT_CHECK | 792,986 | 11.4% |
| INTERPRETER_EXIT | 664,828 | 9.6% |
| TO_BOOL_BOOL | 496,389 | 7.1% |
| STORE_FAST | 46,666 | 0.7% |


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
| LOAD_FAST | 37,920 | 57.1% |
| LOAD_FAST_LOAD_FAST | 14,880 | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 19.5% |
| STORE_ATTR | 640 | 1.0% |
| SWAP | 5 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_FAST | 8,642 | 13.0% |
| LOAD_CONST | 8,640 | 13.0% |
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
| YIELD_VALUE | 4,752,000 | 21.4% |
| CALL | 2,524,147 | 11.4% |
| COPY | 1,972,800 | 8.9% |
| RETURN_VALUE | 1,718,523 | 7.7% |
| FOR_ITER_LIST | 1,254,895 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,659,018 | 43.5% |
| JUMP_BACKWARD | 4,320,000 | 19.5% |
| NOP | 2,872,413 | 12.9% |
| COPY | 1,972,320 | 8.9% |
| LOAD_GLOBAL_BUILTIN | 897,191 | 4.0% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,603,921 | 44.3% |
| COPY | 820,320 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 22.5% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,199,098 | 33.1% |
| STORE_FAST | 816,000 | 22.5% |
| LOAD_FAST_LOAD_FAST | 777,303 | 21.4% |
| JUMP_BACKWARD | 436,320 | 12.0% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 431,998 | 22.0% |
| LOAD_FAST_AND_CLEAR | 381,131 | 19.4% |
| BUILD_LIST | 381,131 | 19.4% |
| FOR_ITER_LIST | 370,571 | 18.8% |
| LOAD_FAST | 200,144 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 431,995 | 22.0% |
| LOAD_CONST | 391,693 | 19.9% |
| STORE_FAST | 381,131 | 19.4% |
| BUILD_LIST | 381,131 | 19.4% |
| FOR_ITER_LIST | 370,571 | 18.8% |


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
| LOAD_FAST | 192,031 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 192,031 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 820,315 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 3 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 431,998 | 51.8% |
| STORE_FAST | 384,000 | 46.0% |
| BINARY_SLICE | 13,920 | 1.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,320 | 0.5% |


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
| CALL | 179,504 | 99.9% |
| LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 179,624 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,814 | 79.9% |
| LOAD_CONST | 45,706 | 18.4% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 244,520 | 98.3% |
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
| LOAD_FAST_LOAD_FAST | 358,044 | 97.6% |
| LOAD_CONST | 8,640 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 358,044 | 97.6% |
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
| LOAD_GLOBAL_MODULE | 391,693 | 49.4% |
| LOAD_FAST | 376,333 | 47.5% |
| CALL | 24,960 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 421,933 | 53.2% |
| COPY_FREE_VARS | 371,053 | 46.8% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 48,568 | 45.7% |
| LOAD_FAST | 48,000 | 45.2% |
| LOAD_CONST | 5,280 | 5.0% |
| BINARY_OP_ADD_INT | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 101,858 | 95.9% |
| POP_TOP | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 39.5% |
| LOAD_FAST | 205,551 | 21.2% |
| CALL_LEN | 179,022 | 18.4% |
| CALL_BUILTIN_CLASS | 179,022 | 18.4% |
| LOAD_CONST | 11,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 576,031 | 59.3% |
| GET_ITER | 203,502 | 20.9% |
| CALL_BUILTIN_CLASS | 179,022 | 18.4% |
| LOAD_FAST | 12,960 | 1.3% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 667,314 | 48.5% |
| LOAD_CONST | 476,124 | 34.6% |
| LOAD_FAST_LOAD_FAST | 129,694 | 9.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 61,007 | 4.4% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 468,924 | 34.1% |
| STORE_FAST | 444,603 | 32.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 345,303 | 25.1% |
| UNPACK_SEQUENCE_TUPLE | 61,007 | 4.4% |
| POP_TOP | 10,942 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,800 | 45.6% |
| BUILD_TUPLE | 384,000 | 45.0% |
| CALL | 48,582 | 5.7% |
| LOAD_FAST_CHECK | 12,425 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 790,560 | 92.7% |
| RETURN_VALUE | 61,007 | 7.2% |
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
| LOAD_GLOBAL_BUILTIN | 898,771 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 898,771 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 450,693 | 95.6% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 4.4% |
| CALL | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,334 | 54.8% |
| CALL_BUILTIN_CLASS | 179,022 | 38.0% |
| CALL_PY_EXACT_ARGS | 24,960 | 5.3% |
| LOAD_FAST | 4,320 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 191,549 | 95.7% |
| LOAD_FAST | 8,640 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 191,549 | 95.7% |
| LOAD_GLOBAL_MODULE | 8,640 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,256,864 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,912 | 0.2% |
| LOAD_CONST | 960 | 0.1% |
| CALL | 3 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 885,811 | 70.3% |
| STORE_FAST | 373,968 | 29.7% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,039,956 | 93.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,432 | 6.6% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 477,345 | 42.8% |
| STORE_FAST | 432,000 | 38.7% |
| LOAD_FAST | 63,840 | 5.7% |
| CALL_BUILTIN_FAST | 61,007 | 5.5% |
| RETURN_VALUE | 38,770 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 668,945 | 92.1% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,604 | 3.0% |
| RETURN_VALUE | 10,560 | 1.5% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 690,549 | 95.0% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.5% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,213,881 | 44.9% |
| LOAD_FAST | 3,918,897 | 41.8% |
| LOAD_FAST_LOAD_FAST | 621,582 | 6.6% |
| LOAD_SUPER_ATTR_METHOD | 371,053 | 4.0% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,342,107 | 99.6% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 920,072 | 41.7% |
| LOAD_ATTR_MODULE | 885,811 | 40.1% |
| LOAD_FAST | 253,949 | 11.5% |
| LOAD_CONST | 80,679 | 3.7% |
| BINARY_OP | 62,880 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,321,421 | 59.9% |
| COPY_FREE_VARS | 885,811 | 40.1% |


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

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,537,103 | 54.7% |
| LOAD_ATTR_INSTANCE_VALUE | 810,833 | 28.8% |
| LOAD_FAST | 432,000 | 15.4% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,809,738 | 99.9% |
| POP_JUMP_IF_TRUE | 2,229 | 0.1% |
| COMPARE_OP | 64 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,064,223 | 95.6% |
| LOAD_CONST | 44,640 | 4.0% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,083,822 | 97.4% |
| LOAD_FAST | 10,560 | 0.9% |
| COPY | 10,560 | 0.9% |
| POP_JUMP_IF_TRUE | 8,251 | 0.7% |


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
| JUMP_BACKWARD | 5,957,993 | 79.3% |
| GET_ITER | 1,180,346 | 15.7% |
| SWAP | 370,571 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,320,000 | 57.5% |
| STORE_FAST | 1,254,895 | 16.7% |
| LOAD_FAST | 742,106 | 9.9% |
| JUMP_BACKWARD | 432,000 | 5.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 383,098 | 5.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 378,786 | 65.6% |
| GET_ITER | 198,342 | 34.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 389,826 | 67.5% |
| LOAD_FAST | 179,142 | 31.0% |
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
| LOAD_GLOBAL_MODULE | 61,007 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,262 | 81.9% |
| LOAD_FAST_CHECK | 12,425 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,580,007 | 90.4% |
| LOAD_FAST_LOAD_FAST | 1,296,426 | 7.1% |
| COPY | 431,995 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 18,128 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,191,587 | 22.9% |
| LOAD_FAST | 2,784,440 | 15.2% |
| TO_BOOL_BOOL | 1,404,385 | 7.7% |
| LOAD_ATTR | 1,356,926 | 7.4% |
| CONTAINS_OP | 1,317,809 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,908 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,014 | 39.8% |
| CALL | 111,462 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,432 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,191,587 | 87.1% |
| LOAD_FAST | 474,840 | 9.9% |
| LOAD_ATTR | 62,887 | 1.3% |
| LOAD_ATTR_SLOT | 62,880 | 1.3% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,893,114 | 39.3% |
| CALL | 1,082,238 | 22.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,039,956 | 21.6% |
| LOAD_CONST | 554,046 | 11.5% |
| LOAD_FAST_LOAD_FAST | 223,319 | 4.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,007,319 | 71.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,005,890 | 12.0% |
| LOAD_FAST_LOAD_FAST | 885,811 | 10.6% |
| BINARY_SUBSCR | 432,000 | 5.2% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,213,881 | 50.4% |
| LOAD_FAST | 2,551,528 | 30.5% |
| CALL_PY_WITH_DEFAULTS | 920,072 | 11.0% |
| LOAD_FAST_LOAD_FAST | 508,800 | 6.1% |
| LOAD_CONST | 94,599 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,708,279 | 100.0% |
| LOAD_ATTR | 94 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,711,660 | 63.2% |
| CALL_PY_WITH_DEFAULTS | 885,811 | 32.7% |
| STORE_DEREF | 41,280 | 1.5% |
| LOAD_CONST | 26,400 | 1.0% |
| LOAD_FAST | 20,640 | 0.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 916,531 | 70.5% |
| LOAD_FAST_LOAD_FAST | 383,098 | 29.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 885,811 | 68.2% |
| UNARY_INVERT | 383,098 | 29.5% |
| RETURN_VALUE | 10,560 | 0.8% |
| LOAD_CONST | 10,560 | 0.8% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 755,284 | 97.2% |
| RETURN_VALUE | 20,640 | 2.7% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 767,925 | 98.8% |
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
| RESUME_CHECK | 2,740,755 | 41.8% |
| LOAD_FAST | 918,931 | 14.0% |
| STORE_FAST | 897,191 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 742,044 | 11.3% |
| NOP | 547,439 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,022,140 | 46.1% |
| LOAD_DEREF | 1,338,944 | 20.4% |
| CALL_ISINSTANCE | 898,771 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 742,044 | 11.3% |
| LOAD_GLOBAL_MODULE | 468,960 | 7.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,655,392 | 28.6% |
| RESUME_CHECK | 2,333,037 | 18.3% |
| NOP | 1,348,136 | 10.6% |
| POP_JUMP_IF_FALSE | 1,093,075 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,086,131 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,848,982 | 22.3% |
| LOAD_ATTR_MODULE | 2,708,279 | 21.2% |
| LOAD_FAST_LOAD_FAST | 1,999,124 | 15.7% |
| LOAD_FAST | 1,611,135 | 12.6% |
| COMPARE_OP_STR | 1,064,223 | 8.3% |


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
| LOAD_FAST | 1,271,744 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 896,371 | 70.5% |
| CALL_PY_EXACT_ARGS | 371,053 | 29.2% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 9,342,107 | 33.5% |
| CACHE | 8,843,469 | 31.7% |
| FOR_ITER_GEN | 4,752,000 | 17.0% |
| COPY_FREE_VARS | 1,343,384 | 4.8% |
| CALL_PY_WITH_DEFAULTS | 1,321,421 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,627,320 | 56.0% |
| POP_TOP | 5,184,960 | 18.6% |
| LOAD_GLOBAL_BUILTIN | 2,740,755 | 9.8% |
| LOAD_GLOBAL_MODULE | 2,333,037 | 8.4% |
| NOP | 1,037,011 | 3.7% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,192,692 | 68.1% |
| LOAD_FAST_LOAD_FAST | 567,373 | 17.6% |
| SWAP | 431,995 | 13.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,644,052 | 51.1% |
| LOAD_FAST | 684,958 | 21.3% |
| LOAD_GLOBAL_MODULE | 530,413 | 16.5% |
| LOAD_CONST | 160,320 | 5.0% |
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
| LOAD_ATTR | 885,811 | 92.8% |
| LOAD_FAST | 34,112 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.7% |
| CALL | 7,680 | 0.8% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 888,726 | 93.1% |
| RETURN_CONST | 24,480 | 2.6% |
| LOAD_GLOBAL_MODULE | 20,640 | 2.2% |
| LOAD_CONST | 20,640 | 2.2% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 60.8% |
| COPY | 308 | 39.0% |
| TO_BOOL | 1 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 60.8% |
| POP_JUMP_IF_FALSE | 309 | 39.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,404,385 | 26.7% |
| CALL_ISINSTANCE | 898,771 | 17.1% |
| RETURN_VALUE | 680,722 | 13.0% |
| CALL | 547,839 | 10.4% |
| LOAD_FAST | 540,106 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,663,144 | 69.7% |
| POP_JUMP_IF_TRUE | 1,380,147 | 26.3% |
| UNARY_NOT | 211,119 | 4.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,154,720 | 54.9% |
| LOAD_FAST | 885,811 | 22.6% |
| BINARY_OP | 885,811 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,926,342 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 379,693 | 92.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 411,853 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,839 | 79.8% |
| LOAD_FAST | 20,640 | 11.4% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,439 | 91.7% |
| POP_JUMP_IF_TRUE | 14,880 | 8.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,000 | 93.0% |
| CALL_BUILTIN_FAST | 61,007 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 61,007 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 436,320 | 27.1% |
| LOAD_FAST_CHECK | 432,000 | 26.8% |
| FOR_ITER_LIST | 383,098 | 23.8% |
| CALL_BUILTIN_FAST | 345,303 | 21.5% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,603,921 | 99.7% |
| LOAD_FAST | 5,280 | 0.3% |


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
| specialization.deferred |       477706 | 45.8% |
|          hit |       565404 | 54.2% |

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
| specialization.deferred |        22562 | 2.3% |
|          hit |       954486 | 97.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 3 | 1.5% |
| Failure | 200 | 98.5% |

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
| specialization.deferred |      1184755 | 10.8% |
|          hit |      9773713 | 89.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 3 | 0.3% |
| Failure | 1,047 | 99.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 327 | 31.2% |
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
| specialization.deferred |      5308847 | 77.2% |
|          hit |      1561773 | 22.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 43 | 2.1% |
| Failure | 2,020 | 97.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,005 | 49.8% |
| or | 583 | 28.9% |
| remainder | 232 | 11.5% |
| add different types | 160 | 7.9% |
| add other | 40 | 2.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8728296 | 29.3% |
| specialization.deopt |           60 | 0.0% |
|          hit |     21028593 | 70.6% |
|         miss |         4380 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 124 | 1.4% |
| Failure | 9,011 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,525 | 28.0% |
| cfunc noargs | 1,793 | 19.9% |
| class no vectorcall | 1,268 | 14.1% |
| meth descr varargs keywords | 842 | 9.3% |
| class mutable | 408 | 4.5% |
| other | 360 | 4.0% |
| cfunc varargs keywords | 328 | 3.6% |
| cfunc varargs | 320 | 3.6% |
| bound method | 287 | 3.2% |
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
| specialization.deferred |       434909 | 10.0% |
| specialization.deopt |           64 | 0.0% |
|          hit |      3920504 | 89.9% |
|         miss |         4720 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 117 | 25.5% |
| Failure | 342 | 74.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 158 | 46.2% |
| different types | 104 | 30.4% |
| big int | 80 | 23.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       976320 | 7.1% |
|          hit |     12866838 | 92.9% |

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
| specialization.deferred |      7747552 | 17.4% |
| specialization.deopt |         4189 | 0.0% |
|          hit |     36522449 | 82.1% |
|         miss |       230216 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,336 | 42.1% |
| Failure | 5,971 | 57.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,403 | 23.5% |
| shadowed | 1,203 | 20.1% |
| not managed dict | 1,198 | 20.1% |
| non overriding descriptor | 604 | 10.1% |
| class attr descriptor | 360 | 6.0% |
| metaclass attribute | 280 | 4.7% |
| class method obj | 280 | 4.7% |
| has managed dict | 240 | 4.0% |
| non object slot | 160 | 2.7% |
| class attr simple | 123 | 2.1% |
| mutable class | 80 | 1.3% |
| overridden | 40 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           58 | 0.0% |
| specialization.deopt |           48 | 0.0% |
|          hit |     19307766 | 100.0% |
|         miss |         6816 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 196 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1338944 | 100.0% |


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
| specialization.deferred |        65762 | 2.0% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      3143683 | 93.6% |
|         miss |       148120 | 4.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,783 | 81.3% |
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
|          hit |      2486208 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 227,469,766 | 53.1% |
| Not specialized | 59,983,069 | 14.0% |
| Specialized | 141,277,072 | 33.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 36,893,488,147,419,103,230 | 100.0% |
| CALL | 8,728,296 | 0.0% |
| LOAD_ATTR | 7,747,552 | 0.0% |
| BINARY_OP | 5,308,847 | 0.0% |
| TO_BOOL | 1,184,755 | 0.0% |
| FOR_ITER | 976,320 | 0.0% |
| BINARY_SUBSCR | 477,706 | 0.0% |
| COMPARE_OP | 434,909 | 0.0% |
| STORE_ATTR | 65,762 | 0.0% |
| STORE_SUBSCR | 22,562 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,416 | 40.7% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,680 | 15.4% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| LOAD_GLOBAL_MODULE | 6,816 | 1.7% |
| COMPARE_OP_INT | 4,720 | 1.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,380 | 1.1% |
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
| Calls to PyEval_EvalDefault | 8,930,829 | 32.0% |
| Calls to Python functions inlined | 18,991,662 | 68.0% |
| Calls via PyEval_EvalFrame (total) | 8,930,829 | 32.0% |
| Calls via PyEval_EvalFrame (vector) | 8,492,589 | 30.4% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,492,589 | 30.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 473,582 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 23,516,597 | 84.2% |
| Frame objects created | 37,606 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 14,992,516 | 42.8% |
| Frees to freelist | 14,993,965 |  |
| Allocations | 20,043,901 | 57.2% |
| Allocations to 512 bytes | 19,831,959 | 56.6% |
| Allocations to 4 kbytes | 86,163 | 0.2% |
| Allocations over 4 kbytes | 125,779 | 0.4% |
| Frees | 21,193,331 |  |
| New values | 65,280 |  |
| Interpreter increfs | 168,028,336 | 77.0% |
| Interpreter decrefs | 184,075,486 | 73.7% |
| Increfs | 50,255,985 | 23.0% |
| Decrefs | 65,805,542 | 26.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 9,040,890 |  |
| Method cache misses | 93,233 |  |
| Method cache collisions | 109,372 |  |
| Method cache dunder hits | 8,565,715 |  |
| Method cache dunder misses | 16,139 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 12 | 288 | 84,170 |
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
