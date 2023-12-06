
# Pystats results

- benchmark: concurrent_imap
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 2dde229
- commit date: 2023-10-19T19:17:27-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 76,003,580 | 17.6% | 17.6% |  |
| RESUME_CHECK | 28,023,170 | 6.5% | 24.2% |  |
| STORE_FAST | 22,266,332 | 5.2% | 29.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,415,367 | 4.3% | 33.6% | 0.9% |
| POP_TOP | 18,125,713 | 4.2% | 37.8% |  |
| RETURN_VALUE | 16,651,122 | 3.9% | 41.7% |  |
| POP_JUMP_IF_FALSE | 14,522,094 | 3.4% | 45.0% |  |
| JUMP_BACKWARD | 13,526,010 | 3.1% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 12,849,897 | 3.0% | 51.2% | 0.0% |
| LOAD_FAST_LOAD_FAST | 11,850,538 | 2.8% | 53.9% |  |
| LOAD_CONST | 11,553,084 | 2.7% | 56.6% |  |
| CALL_PY_EXACT_ARGS | 9,443,674 | 2.2% | 58.8% |  |
| INTERPRETER_EXIT | 8,944,500 | 2.1% | 60.9% |  |
| CALL | 8,770,141 | 2.0% | 62.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,417,261 | 2.0% | 64.9% | 0.7% |
| LOAD_ATTR | 7,805,266 | 1.8% | 66.7% |  |
| NOP | 7,550,621 | 1.8% | 68.4% |  |
| FOR_ITER_LIST | 7,532,904 | 1.7% | 70.2% |  |
| RETURN_CONST | 6,982,054 | 1.6% | 71.8% |  |
| LOAD_GLOBAL_BUILTIN | 6,593,887 | 1.5% | 73.3% |  |
| PUSH_NULL | 5,533,932 | 1.3% | 74.6% |  |
| COPY | 5,461,280 | 1.3% | 75.9% |  |
| BINARY_OP | 5,358,568 | 1.2% | 77.1% |  |
| TO_BOOL_BOOL | 5,281,843 | 1.2% | 78.4% |  |
| YIELD_VALUE | 5,184,960 | 1.2% | 79.6% |  |
| STORE_FAST_LOAD_FAST | 4,847,040 | 1.1% | 80.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,830,224 | 1.1% | 81.8% |  |
| FOR_ITER_GEN | 4,760,640 | 1.1% | 82.9% |  |
| TO_BOOL_INT | 3,962,560 | 0.9% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,811,923 | 0.9% | 84.7% |  |
| STORE_FAST_STORE_FAST | 3,630,809 | 0.8% | 85.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,234,086 | 0.8% | 86.3% | 4.6% |
| BUILD_TUPLE | 3,232,796 | 0.8% | 87.1% |  |
| COMPARE_OP_INT | 2,823,274 | 0.7% | 87.7% | 0.2% |
| LOAD_ATTR_MODULE | 2,723,230 | 0.6% | 88.3% |  |
| CALL_PY_WITH_DEFAULTS | 2,220,787 | 0.5% | 88.9% |  |
| POP_JUMP_IF_TRUE | 2,042,460 | 0.5% | 89.3% |  |
| SWAP | 1,979,661 | 0.5% | 89.8% |  |
| CALL_FUNCTION_EX | 1,810,151 | 0.4% | 90.2% |  |
| GET_ITER | 1,802,034 | 0.4% | 90.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,615,769 | 0.4% | 91.0% |  |
| LOAD_DEREF | 1,391,883 | 0.3% | 91.3% |  |
| CALL_BUILTIN_FAST | 1,384,498 | 0.3% | 91.7% |  |
| BEFORE_WITH | 1,380,712 | 0.3% | 92.0% |  |
| COPY_FREE_VARS | 1,354,803 | 0.3% | 92.3% |  |
| CONTAINS_OP | 1,326,084 | 0.3% | 92.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,311,028 | 0.3% | 92.9% |  |
| LOAD_SUPER_ATTR_METHOD | 1,283,163 | 0.3% | 93.2% |  |
| UNARY_INVERT | 1,280,308 | 0.3% | 93.5% |  |
| JUMP_FORWARD | 1,271,664 | 0.3% | 93.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,271,556 | 0.3% | 94.1% |  |
| BUILD_MAP | 1,259,319 | 0.3% | 94.4% |  |
| TO_BOOL | 1,187,965 | 0.3% | 94.7% |  |
| BUILD_LIST | 1,149,952 | 0.3% | 94.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,118,482 | 0.3% | 95.2% |  |
| COMPARE_OP_STR | 1,114,753 | 0.3% | 95.4% |  |
| FOR_ITER | 976,760 | 0.2% | 95.7% |  |
| CALL_BUILTIN_CLASS | 976,361 | 0.2% | 95.9% |  |
| STORE_SUBSCR_DICT | 962,157 | 0.2% | 96.1% |  |
| CALL_ISINSTANCE | 907,044 | 0.2% | 96.3% |  |
| UNPACK_SEQUENCE_TUPLE | 876,990 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 852,510 | 0.2% | 96.7% |  |
| POP_JUMP_IF_NONE | 840,567 | 0.2% | 96.9% |  |
| BINARY_OP_ADD_INT | 834,232 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 799,278 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 799,278 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 783,642 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 726,528 | 0.2% | 97.8% |  |
| LOAD_FAST_CHECK | 625,518 | 0.1% | 98.0% |  |
| LIST_APPEND | 624,182 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 581,845 | 0.1% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 577,386 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 477,935 | 0.1% | 98.5% |  |
| CALL_LEN | 472,900 | 0.1% | 98.6% |  |
| COMPARE_OP | 438,894 | 0.1% | 98.7% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.8% |  |
| DICT_MERGE | 422,880 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 414,999 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 369,844 | 0.1% | 99.1% |  |
| LIST_EXTEND | 362,164 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,840 | 0.1% | 99.3% |  |
| CALL_KW | 267,542 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 248,817 | 0.1% | 99.4% |  |
| UNARY_NOT | 212,447 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 201,752 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT_LHS | 193,597 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT_RHS | 181,087 | 0.0% | 99.6% |  |
| TO_BOOL_NONE | 180,332 | 0.0% | 99.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 106,214 | 0.0% | 99.6% | 4.1% |
| STORE_DEREF | 103,200 | 0.0% | 99.7% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT_LHS | 84,480 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,670 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,416 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,806 | 0.0% | 99.9% |  |
| DELETE_SUBSCR | 58,564 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 37,557 | 0.0% | 99.9% |  |
| POP_EXCEPT | 37,557 | 0.0% | 99.9% |  |
| IS_OP | 34,888 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 33,237 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 32,640 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 100.0% |  |
| IMPORT_NAME | 24,480 | 0.0% | 100.0% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,775 | 0.0% | 100.0% |  |
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
| TO_BOOL_ALWAYS_TRUE | 808 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 194 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 120 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,644,199 | 3.9% | 3.9% |
| RESUME_CHECK LOAD_FAST | 15,689,961 | 3.6% | 7.5% |
| STORE_FAST LOAD_FAST | 9,710,285 | 2.3% | 9.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,409,114 | 2.2% | 11.9% |
| CACHE RESUME_CHECK | 8,861,458 | 2.1% | 14.0% |
| LOAD_FAST RETURN_VALUE | 8,073,992 | 1.9% | 15.9% |
| RETURN_VALUE INTERPRETER_EXIT | 7,843,575 | 1.8% | 17.7% |
| POP_TOP JUMP_BACKWARD | 6,543,098 | 1.5% | 19.2% |
| LOAD_FAST LOAD_ATTR | 6,054,430 | 1.4% | 20.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 6,048,259 | 1.4% | 22.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 5,972,552 | 1.4% | 23.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,940,837 | 1.4% | 24.8% |
| POP_TOP LOAD_FAST | 5,672,711 | 1.3% | 26.1% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.2% | 27.3% |
| RETURN_CONST POP_TOP | 4,943,563 | 1.1% | 28.5% |
| NOP LOAD_FAST | 4,795,951 | 1.1% | 29.6% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.1% | 30.7% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.1% | 31.8% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.1% | 32.9% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 4,320,000 | 1.0% | 33.9% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.0% | 34.9% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 4,320,000 | 1.0% | 35.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,241,836 | 1.0% | 36.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,206,191 | 1.0% | 37.9% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,962,560 | 0.9% | 38.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,953,202 | 0.9% | 39.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,688,504 | 0.9% | 40.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,686,534 | 0.9% | 41.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,041,559 | 0.7% | 42.1% |
| LOAD_FAST LOAD_CONST | 2,979,301 | 0.7% | 42.8% |
| STORE_FAST NOP | 2,885,431 | 0.7% | 43.5% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,875,364 | 0.7% | 44.1% |
| LOAD_CONST LOAD_CONST | 2,841,644 | 0.7% | 44.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,820,959 | 0.7% | 45.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,795,559 | 0.6% | 46.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,760,447 | 0.6% | 46.7% |
| LOAD_FAST PUSH_NULL | 2,760,055 | 0.6% | 47.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,758,644 | 0.6% | 48.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,723,140 | 0.6% | 48.7% |
| LOAD_ATTR LOAD_FAST | 2,634,807 | 0.6% | 49.3% |
| PUSH_NULL LOAD_FAST | 2,614,955 | 0.6% | 49.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,572,835 | 0.6% | 50.5% |
| CALL STORE_FAST | 2,537,249 | 0.6% | 51.1% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,371,923 | 0.6% | 51.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,349,158 | 0.5% | 52.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,205,275 | 0.5% | 52.7% |
| COPY TO_BOOL_INT | 2,174,392 | 0.5% | 53.2% |
| BINARY_OP COPY | 2,174,392 | 0.5% | 53.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,017,250 | 0.5% | 54.2% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 54.6% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 55.1% |
| LOAD_CONST CALL | 1,963,151 | 0.5% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,903,944 | 0.4% | 56.0% |
| CALL RETURN_VALUE | 1,870,884 | 0.4% | 56.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,802,407 | 0.4% | 56.8% |
| RETURN_VALUE STORE_FAST | 1,731,499 | 0.4% | 57.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,718,239 | 0.4% | 57.6% |
| CALL POP_TOP | 1,699,911 | 0.4% | 58.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,656,636 | 0.4% | 58.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,624,120 | 0.4% | 58.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,610,489 | 0.4% | 59.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,550,366 | 0.4% | 59.5% |
| LOAD_CONST COMPARE_OP_INT | 1,545,288 | 0.4% | 59.9% |
| PUSH_NULL CALL | 1,528,891 | 0.4% | 60.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,527,319 | 0.4% | 60.6% |
| RETURN_VALUE RETURN_VALUE | 1,497,509 | 0.3% | 60.9% |
| LOAD_FAST_LOAD_FAST CALL | 1,448,303 | 0.3% | 61.3% |
| POP_TOP RETURN_CONST | 1,430,644 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,415,474 | 0.3% | 61.9% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,271 | 0.3% | 62.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,382,862 | 0.3% | 62.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,360,085 | 0.3% | 62.9% |
| NOP LOAD_GLOBAL_MODULE | 1,359,856 | 0.3% | 63.2% |
| COPY_FREE_VARS RESUME_CHECK | 1,354,803 | 0.3% | 63.5% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,350,363 | 0.3% | 63.8% |
| LOAD_DEREF LOAD_FAST | 1,350,363 | 0.3% | 64.1% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,326,703 | 0.3% | 64.5% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,326,084 | 0.3% | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,326,076 | 0.3% | 65.1% |
| LOAD_FAST BUILD_TUPLE | 1,318,884 | 0.3% | 65.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,307,535 | 0.3% | 65.7% |
| POP_TOP LOAD_CONST | 1,304,076 | 0.3% | 66.0% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,283,163 | 0.3% | 66.3% |
| UNARY_INVERT BINARY_OP | 1,280,308 | 0.3% | 66.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,268,283 | 0.3% | 66.9% |
| FOR_ITER_LIST STORE_FAST | 1,266,328 | 0.3% | 67.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,202,224 | 0.3% | 67.4% |
| LOAD_CONST LOAD_FAST | 1,199,199 | 0.3% | 67.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,195,200 | 0.3% | 68.0% |
| GET_ITER FOR_ITER_LIST | 1,186,638 | 0.3% | 68.3% |
| POP_TOP NOP | 1,185,417 | 0.3% | 68.5% |
| LOAD_FAST TO_BOOL | 1,147,069 | 0.3% | 68.8% |
| LOAD_FAST GET_ITER | 1,144,792 | 0.3% | 69.1% |
| RETURN_VALUE POP_TOP | 1,137,233 | 0.3% | 69.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,124,077 | 0.3% | 69.6% |
| POP_JUMP_IF_FALSE POP_TOP | 1,120,761 | 0.3% | 69.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,101,364 | 0.3% | 70.1% |
| BINARY_OP STORE_FAST | 1,097,756 | 0.3% | 70.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,087,712 | 0.3% | 70.6% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,085,402 | 0.3% | 70.9% |


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
| RESUME_CHECK | 8,861,458 | 99.0% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 940,271 | 68.1% |
| RETURN_VALUE | 374,199 | 27.1% |
| LOAD_GLOBAL_MODULE | 61,922 | 4.5% |
| CALL | 4,320 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,193 | 72.6% |
| STORE_FAST | 378,519 | 27.4% |


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
| LOAD_CONST | 45,717 | 9.6% |
| BINARY_SUBSCR | 218 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.4% |
| STORE_FAST | 45,717 | 9.6% |
| BINARY_SUBSCR | 218 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 29,397 | 88.4% |
| LOAD_ATTR_MODULE | 3,840 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,237 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,322 | 48.4% |
| CALL | 20,642 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,599 | 16.4% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,602 | 77.9% |
| RETURN_CONST | 7,682 | 13.1% |
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
| RETURN_CONST | 799,278 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 799,278 | 100.0% |


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
| LOAD_FAST | 1,144,792 | 63.5% |
| STORE_FAST_LOAD_FAST | 432,000 | 24.0% |
| CALL_BUILTIN_CLASS | 205,082 | 11.4% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,186,638 | 65.8% |
| LOAD_FAST_AND_CLEAR | 384,274 | 21.3% |
| FOR_ITER_RANGE | 199,922 | 11.1% |
| FOR_ITER_TUPLE | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,843,575 | 87.7% |
| RETURN_CONST | 667,965 | 7.5% |
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
| STORE_FAST | 2,885,431 | 38.2% |
| POP_TOP | 1,185,417 | 15.7% |
| RESUME_CHECK | 1,045,284 | 13.8% |
| POP_JUMP_IF_FALSE | 1,007,816 | 13.3% |
| JUMP_BACKWARD | 816,000 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,795,951 | 63.5% |
| LOAD_GLOBAL_MODULE | 1,359,856 | 18.0% |
| LOAD_GLOBAL_BUILTIN | 552,294 | 7.3% |
| LOAD_FAST_LOAD_FAST | 437,280 | 5.8% |
| LOAD_CONST | 396,960 | 5.3% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 25,077 | 66.8% |
| COPY | 8,640 | 23.0% |
| POP_TOP | 3,840 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 25,077 | 66.8% |
| RERAISE | 8,640 | 23.0% |
| JUMP_FORWARD | 3,840 | 10.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,184,960 | 28.6% |
| RETURN_CONST | 4,943,563 | 27.3% |
| CALL | 1,699,911 | 9.4% |
| RETURN_VALUE | 1,137,233 | 6.3% |
| POP_JUMP_IF_FALSE | 1,120,761 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,543,098 | 36.1% |
| LOAD_FAST | 5,672,711 | 31.3% |
| RETURN_CONST | 1,430,644 | 7.9% |
| LOAD_CONST | 1,304,076 | 7.2% |
| NOP | 1,185,417 | 6.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,397 | 78.3% |
| RERAISE | 4,320 | 11.5% |
| CALL_KW | 3,840 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 29,397 | 78.3% |
| WITH_EXCEPT_START | 4,320 | 11.5% |
| LOAD_GLOBAL_MODULE | 3,840 | 10.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,760,055 | 49.9% |
| LOAD_ATTR_MODULE | 1,718,239 | 31.0% |
| LOAD_ATTR | 961,438 | 17.4% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,614,955 | 47.3% |
| CALL | 1,528,891 | 27.6% |
| LOAD_FAST_LOAD_FAST | 1,046,460 | 18.9% |
| LOAD_CONST | 240,362 | 4.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 48,544 | 0.9% |


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
| LOAD_FAST | 8,073,992 | 48.5% |
| CALL | 1,870,884 | 11.2% |
| RETURN_VALUE | 1,497,509 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,195,200 | 7.2% |
| CALL_FUNCTION_EX | 948,911 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,843,575 | 47.1% |
| STORE_FAST | 1,731,499 | 10.4% |
| RETURN_VALUE | 1,497,509 | 9.0% |
| POP_TOP | 1,137,233 | 6.8% |
| LOAD_FAST_LOAD_FAST | 894,084 | 5.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,695 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.3% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| LOAD_FAST | 8 | 0.0% |
| STORE_SUBSCR_DICT | 7 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,147,069 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,845 | 3.4% |
| TO_BOOL | 1,044 | 0.1% |
| RETURN_VALUE | 5 | 0.0% |
| LOAD_ATTR | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 633,754 | 53.3% |
| POP_JUMP_IF_FALSE | 553,165 | 46.6% |
| TO_BOOL | 1,044 | 0.1% |
| TO_BOOL_BOOL | 2 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 894,084 | 69.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 386,224 | 30.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,280,308 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 212,447 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 212,447 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,875,364 | 53.7% |
| UNARY_INVERT | 1,280,308 | 23.9% |
| POP_JUMP_IF_FALSE | 894,084 | 16.7% |
| LOAD_ATTR | 203,672 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,174,392 | 40.6% |
| STORE_FAST | 1,097,756 | 20.5% |
| UNARY_INVERT | 894,084 | 16.7% |
| TO_BOOL_INT | 894,084 | 16.7% |
| BUILD_TUPLE | 193,112 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 384,274 | 33.4% |
| JUMP_FORWARD | 374,199 | 32.5% |
| LOAD_FAST | 193,597 | 16.8% |
| POP_TOP | 180,602 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 386,679 | 33.6% |
| SWAP | 384,274 | 33.4% |
| STORE_FAST | 375,159 | 32.6% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 432,000 | 34.3% |
| LOAD_FAST | 396,960 | 31.5% |
| RESUME_CHECK | 381,879 | 30.3% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.1% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 814,359 | 64.7% |
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
| LOAD_FAST | 1,318,884 | 40.8% |
| LOAD_FAST_LOAD_FAST | 870,240 | 26.9% |
| BUILD_MAP | 432,000 | 13.4% |
| RETURN_VALUE | 384,000 | 11.9% |
| BINARY_OP | 193,112 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 895,044 | 27.7% |
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
| LOAD_CONST | 1,963,151 | 22.4% |
| PUSH_NULL | 1,528,891 | 17.4% |
| LOAD_FAST_LOAD_FAST | 1,448,303 | 16.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,082,271 | 12.3% |
| BUILD_TUPLE | 895,044 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,537,249 | 28.9% |
| RETURN_VALUE | 1,870,884 | 21.3% |
| POP_TOP | 1,699,911 | 19.4% |
| LOAD_FAST | 787,276 | 9.0% |
| TO_BOOL_BOOL | 548,176 | 6.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,271 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,911 | 52.4% |
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
| LOAD_CONST | 267,542 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 215,642 | 80.6% |
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
| LOAD_CONST | 437,935 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 592 | 0.1% |
| COMPARE_OP | 286 | 0.1% |
| COMPARE_OP_INT | 67 | 0.0% |
| LOAD_GLOBAL_MODULE | 9 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 438,486 | 99.9% |
| COMPARE_OP | 286 | 0.1% |
| COMPARE_OP_INT | 108 | 0.0% |
| COMPARE_OP_STR | 9 | 0.0% |
| POP_JUMP_IF_TRUE | 5 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,326,076 | 100.0% |
| LOAD_ATTR | 8 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,326,084 | 100.0% |


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
| BINARY_OP | 2,174,392 | 39.8% |
| STORE_FAST | 1,972,320 | 36.1% |
| LOAD_CONST | 825,600 | 15.1% |
| LOAD_FAST | 442,560 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,174,392 | 39.8% |
| STORE_FAST | 1,972,800 | 36.1% |
| STORE_FAST_STORE_FAST | 820,320 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 431,985 | 7.9% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 894,084 | 66.0% |
| CALL_ALLOC_AND_ENTER_INIT | 374,199 | 27.6% |
| CACHE | 82,080 | 6.1% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,354,803 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,806 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,204 | 66.7% |
| RETURN_CONST | 20,642 | 31.9% |
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
| LOAD_FAST | 12,960 | 37.1% |
| LOAD_GLOBAL_MODULE | 1,288 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,888 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,543,098 | 48.4% |
| STORE_FAST | 4,320,000 | 31.9% |
| POP_JUMP_IF_NOT_NONE | 745,684 | 5.5% |
| LIST_APPEND | 624,182 | 4.6% |
| STORE_FAST_STORE_FAST | 436,320 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,972,552 | 44.2% |
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
| STORE_FAST | 805,503 | 63.3% |
| POP_TOP | 452,721 | 35.6% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 840,226 | 66.1% |
| BUILD_LIST | 374,199 | 29.4% |
| POP_EXCEPT | 25,077 | 2.0% |
| LOAD_GLOBAL_MODULE | 18,722 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 346,590 | 55.5% |
| LOAD_ATTR | 193,112 | 30.9% |
| BINARY_SUBSCR_STR_INT | 84,480 | 13.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 624,182 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,562 | 50.1% |
| RETURN_VALUE | 180,602 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,082 | 50.0% |
| STORE_FAST | 180,602 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,054,430 | 77.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,360,085 | 17.4% |
| LOAD_GLOBAL_MODULE | 296,372 | 3.8% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,895 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,634,807 | 33.8% |
| PUSH_NULL | 961,438 | 12.3% |
| STORE_SUBSCR_DICT | 894,084 | 11.5% |
| POP_JUMP_IF_NOT_NONE | 864,961 | 11.1% |
| STORE_FAST | 556,659 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,979,301 | 25.8% |
| LOAD_CONST | 2,841,644 | 24.6% |
| POP_TOP | 1,304,076 | 11.3% |
| POP_JUMP_IF_FALSE | 689,765 | 6.0% |
| LOAD_ATTR_METHOD_NO_DICT | 554,657 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,841,644 | 24.6% |
| CALL | 1,963,151 | 17.0% |
| COMPARE_OP_INT | 1,545,288 | 13.4% |
| LOAD_FAST | 1,199,199 | 10.4% |
| COPY | 825,600 | 7.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,350,363 | 97.0% |
| STORE_DEREF | 20,640 | 1.5% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.5% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,350,363 | 97.0% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 3.0% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,689,961 | 20.6% |
| STORE_FAST | 9,710,285 | 12.8% |
| POP_JUMP_IF_FALSE | 5,940,837 | 7.8% |
| POP_TOP | 5,672,711 | 7.5% |
| NOP | 4,795,951 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,644,199 | 21.9% |
| RETURN_VALUE | 8,073,992 | 10.6% |
| LOAD_ATTR | 6,054,430 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,048,259 | 8.0% |
| CALL_PY_EXACT_ARGS | 3,953,202 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 384,274 | 66.6% |
| LOAD_FAST_AND_CLEAR | 193,112 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 384,274 | 66.6% |
| LOAD_FAST_AND_CLEAR | 193,112 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 69.1% |
| POP_JUMP_IF_NONE | 181,087 | 28.9% |
| LOAD_ATTR_CLASS | 12,431 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 69.1% |
| LOAD_GLOBAL_MODULE | 181,087 | 28.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,431 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,017,250 | 17.0% |
| LOAD_FAST_LOAD_FAST | 1,550,366 | 13.1% |
| POP_JUMP_IF_FALSE | 1,124,077 | 9.5% |
| PUSH_NULL | 1,046,460 | 8.8% |
| LOAD_SUPER_ATTR_METHOD | 904,644 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,758,644 | 23.3% |
| LOAD_FAST_LOAD_FAST | 1,550,366 | 13.1% |
| CALL | 1,448,303 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,307,535 | 11.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 894,084 | 7.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 41.2% |
| RESUME_CHECK | 40 | 20.6% |
| POP_JUMP_IF_FALSE | 40 | 20.6% |
| POP_JUMP_IF_TRUE | 17 | 8.8% |
| LOAD_ATTR_INSTANCE_VALUE | 9 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 99 | 51.0% |
| LOAD_ATTR | 47 | 24.2% |
| LOAD_GLOBAL_BUILTIN | 41 | 21.1% |
| COMPARE_OP | 5 | 2.6% |
| LOAD_FAST | 2 | 1.0% |


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
| TO_BOOL_INT | 3,962,560 | 27.3% |
| TO_BOOL_BOOL | 3,686,534 | 25.4% |
| COMPARE_OP_INT | 2,820,959 | 19.4% |
| CONTAINS_OP | 1,326,084 | 9.1% |
| COMPARE_OP_STR | 1,085,402 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,940,837 | 40.9% |
| RETURN_CONST | 2,371,923 | 16.3% |
| LOAD_FAST_LOAD_FAST | 1,124,077 | 7.7% |
| POP_TOP | 1,120,761 | 7.7% |
| LOAD_GLOBAL_MODULE | 1,101,364 | 7.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 795,927 | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.7% |
| LOAD_ATTR | 21,120 | 2.5% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 220,805 | 26.3% |
| NOP | 208,922 | 24.9% |
| LOAD_FAST | 192,700 | 22.9% |
| LOAD_FAST_CHECK | 181,087 | 21.5% |
| RETURN_CONST | 18,240 | 2.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,802,407 | 47.3% |
| LOAD_ATTR | 864,961 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 741,591 | 19.5% |
| RETURN_VALUE | 347,070 | 9.1% |
| LOAD_DEREF | 41,280 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,527,319 | 40.1% |
| RETURN_CONST | 865,289 | 22.7% |
| JUMP_BACKWARD | 745,684 | 19.6% |
| NOP | 380,631 | 10.0% |
| LOAD_CONST | 180,602 | 4.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,382,862 | 67.7% |
| TO_BOOL | 633,754 | 31.0% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,231 | 0.4% |
| COMPARE_OP_INT | 2,248 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 714,615 | 35.0% |
| LOAD_FAST_LOAD_FAST | 636,632 | 31.2% |
| RETURN_CONST | 551,478 | 27.0% |
| LOAD_GLOBAL_MODULE | 54,827 | 2.7% |
| RETURN_VALUE | 45,717 | 2.2% |


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
| POP_JUMP_IF_FALSE | 2,371,923 | 34.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,656,636 | 23.7% |
| POP_TOP | 1,430,644 | 20.5% |
| POP_JUMP_IF_NOT_NONE | 865,289 | 12.4% |
| POP_JUMP_IF_TRUE | 551,478 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,943,563 | 70.8% |
| EXIT_INIT_CHECK | 799,278 | 11.4% |
| INTERPRETER_EXIT | 667,965 | 9.6% |
| TO_BOOL_BOOL | 496,997 | 7.1% |
| STORE_FAST | 46,677 | 0.7% |


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
| SWAP | 15 | 0.0% |

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
| CALL | 2,537,249 | 11.4% |
| COPY | 1,972,800 | 8.9% |
| RETURN_VALUE | 1,731,499 | 7.8% |
| FOR_ITER_LIST | 1,266,328 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,710,285 | 43.6% |
| JUMP_BACKWARD | 4,320,000 | 19.4% |
| NOP | 2,885,431 | 13.0% |
| COPY | 1,972,320 | 8.9% |
| LOAD_GLOBAL_BUILTIN | 903,463 | 4.1% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,610,489 | 44.4% |
| COPY | 820,320 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 22.5% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,202,224 | 33.1% |
| STORE_FAST | 816,000 | 22.5% |
| LOAD_FAST_LOAD_FAST | 780,745 | 21.5% |
| JUMP_BACKWARD | 436,320 | 12.0% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 431,992 | 21.8% |
| LOAD_FAST_AND_CLEAR | 384,274 | 19.4% |
| BUILD_LIST | 384,274 | 19.4% |
| FOR_ITER_LIST | 373,714 | 18.9% |
| LOAD_FAST | 201,727 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 431,985 | 21.8% |
| LOAD_CONST | 394,839 | 19.9% |
| STORE_FAST | 384,274 | 19.4% |
| BUILD_LIST | 384,274 | 19.4% |
| FOR_ITER_LIST | 373,714 | 18.9% |


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
| LOAD_FAST | 193,597 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 193,597 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 820,305 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 431,992 | 51.8% |
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
| CALL | 181,087 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 181,087 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,780 | 79.9% |
| LOAD_CONST | 45,717 | 18.4% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 244,497 | 98.3% |
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
| LOAD_FAST_LOAD_FAST | 361,204 | 97.7% |
| LOAD_CONST | 8,640 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 361,204 | 97.7% |
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
| LOAD_GLOBAL_MODULE | 394,839 | 49.4% |
| LOAD_FAST | 379,479 | 47.5% |
| CALL | 24,960 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 425,079 | 53.2% |
| COPY_FREE_VARS | 374,199 | 46.8% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 48,544 | 45.7% |
| LOAD_FAST | 48,000 | 45.2% |
| LOAD_CONST | 5,280 | 5.0% |
| BINARY_OP_ADD_INT | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 101,834 | 95.9% |
| POP_TOP | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 39.3% |
| LOAD_FAST | 207,117 | 21.2% |
| CALL_LEN | 180,602 | 18.5% |
| CALL_BUILTIN_CLASS | 180,602 | 18.5% |
| LOAD_CONST | 11,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 577,597 | 59.2% |
| GET_ITER | 205,082 | 21.0% |
| CALL_BUILTIN_CLASS | 180,602 | 18.5% |
| LOAD_FAST | 12,960 | 1.3% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 672,324 | 48.6% |
| LOAD_CONST | 479,284 | 34.6% |
| LOAD_FAST_LOAD_FAST | 129,660 | 9.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60,990 | 4.4% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 472,084 | 34.1% |
| STORE_FAST | 446,132 | 32.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 348,745 | 25.2% |
| UNPACK_SEQUENCE_TUPLE | 60,990 | 4.4% |
| POP_TOP | 10,947 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,800 | 45.6% |
| BUILD_TUPLE | 384,000 | 45.0% |
| CALL | 48,559 | 5.7% |
| LOAD_FAST_CHECK | 12,431 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 790,560 | 92.7% |
| RETURN_VALUE | 60,990 | 7.2% |
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
| LOAD_GLOBAL_BUILTIN | 907,044 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 907,044 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 452,259 | 95.6% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 4.4% |
| CALL | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,300 | 54.6% |
| CALL_BUILTIN_CLASS | 180,602 | 38.2% |
| CALL_PY_EXACT_ARGS | 24,960 | 5.3% |
| LOAD_FAST | 4,320 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 193,112 | 95.7% |
| LOAD_FAST | 8,640 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 193,112 | 95.7% |
| LOAD_GLOBAL_MODULE | 8,640 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,268,283 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,306 | 0.2% |
| LOAD_CONST | 960 | 0.1% |
| CALL | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 894,084 | 70.3% |
| STORE_FAST | 376,512 | 29.6% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,043,141 | 93.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,421 | 6.6% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 480,513 | 43.0% |
| STORE_FAST | 432,000 | 38.6% |
| LOAD_FAST | 63,840 | 5.7% |
| CALL_BUILTIN_FAST | 60,990 | 5.5% |
| RETURN_VALUE | 38,782 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 668,921 | 92.1% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,607 | 3.0% |
| RETURN_VALUE | 10,560 | 1.5% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 690,528 | 95.0% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.5% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,241,836 | 44.9% |
| LOAD_FAST | 3,953,202 | 41.9% |
| LOAD_FAST_LOAD_FAST | 623,162 | 6.6% |
| LOAD_SUPER_ATTR_METHOD | 374,199 | 4.0% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,409,114 | 99.6% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 924,066 | 41.6% |
| LOAD_ATTR_MODULE | 894,084 | 40.3% |
| LOAD_FAST | 255,512 | 11.5% |
| LOAD_CONST | 80,404 | 3.6% |
| BINARY_OP | 62,880 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,326,703 | 59.7% |
| COPY_FREE_VARS | 894,084 | 40.3% |


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
| LOAD_CONST | 1,545,288 | 54.7% |
| LOAD_ATTR_INSTANCE_VALUE | 813,870 | 28.8% |
| LOAD_FAST | 432,000 | 15.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,820,959 | 99.9% |
| POP_JUMP_IF_TRUE | 2,248 | 0.1% |
| COMPARE_OP | 67 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,065,784 | 95.6% |
| LOAD_CONST | 44,640 | 4.0% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 9 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,085,402 | 97.4% |
| LOAD_FAST | 10,560 | 0.9% |
| COPY | 10,560 | 0.9% |
| POP_JUMP_IF_TRUE | 8,231 | 0.7% |


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
| JUMP_BACKWARD | 5,972,552 | 79.3% |
| GET_ITER | 1,186,638 | 15.8% |
| SWAP | 373,714 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,320,000 | 57.3% |
| STORE_FAST | 1,266,328 | 16.8% |
| LOAD_FAST | 748,398 | 9.9% |
| JUMP_BACKWARD | 432,000 | 5.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 386,224 | 5.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 381,923 | 65.6% |
| GET_ITER | 199,922 | 34.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 392,963 | 67.5% |
| LOAD_FAST | 180,722 | 31.1% |
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
| LOAD_GLOBAL_MODULE | 60,990 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,239 | 81.9% |
| LOAD_FAST_CHECK | 12,431 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,644,199 | 90.4% |
| LOAD_FAST_LOAD_FAST | 1,307,535 | 7.1% |
| COPY | 431,985 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 18,148 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,206,191 | 22.8% |
| LOAD_FAST | 2,795,559 | 15.2% |
| TO_BOOL_BOOL | 1,415,474 | 7.7% |
| LOAD_ATTR | 1,360,085 | 7.4% |
| CONTAINS_OP | 1,326,076 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 121,980 | 39.8% |
| CALL | 111,439 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,421 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,206,191 | 87.1% |
| LOAD_FAST | 476,179 | 9.9% |
| LOAD_ATTR | 62,894 | 1.3% |
| LOAD_ATTR_SLOT | 62,880 | 1.3% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,903,944 | 39.4% |
| CALL | 1,082,271 | 22.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,043,141 | 21.6% |
| LOAD_CONST | 554,657 | 11.5% |
| LOAD_FAST_LOAD_FAST | 224,611 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,048,259 | 71.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,009,665 | 12.0% |
| LOAD_FAST_LOAD_FAST | 894,084 | 10.6% |
| BINARY_SUBSCR | 432,000 | 5.1% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,241,836 | 50.4% |
| LOAD_FAST | 2,572,835 | 30.6% |
| CALL_PY_WITH_DEFAULTS | 924,066 | 11.0% |
| LOAD_FAST_LOAD_FAST | 508,800 | 6.0% |
| LOAD_CONST | 94,324 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,723,140 | 100.0% |
| LOAD_ATTR | 90 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,718,239 | 63.1% |
| CALL_PY_WITH_DEFAULTS | 894,084 | 32.8% |
| STORE_DEREF | 41,280 | 1.5% |
| LOAD_CONST | 26,400 | 1.0% |
| LOAD_FAST | 20,640 | 0.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 924,804 | 70.5% |
| LOAD_FAST_LOAD_FAST | 386,224 | 29.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 894,084 | 68.2% |
| UNARY_INVERT | 386,224 | 29.5% |
| RETURN_VALUE | 10,560 | 0.8% |
| LOAD_CONST | 10,560 | 0.8% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 761,882 | 97.2% |
| RETURN_VALUE | 20,640 | 2.6% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 774,522 | 98.8% |
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
| RESUME_CHECK | 2,760,447 | 41.9% |
| LOAD_FAST | 927,204 | 14.1% |
| STORE_FAST | 903,463 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 745,204 | 11.3% |
| NOP | 552,294 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,041,559 | 46.1% |
| LOAD_DEREF | 1,350,363 | 20.5% |
| CALL_ISINSTANCE | 907,044 | 13.8% |
| LOAD_GLOBAL_BUILTIN | 745,204 | 11.3% |
| LOAD_GLOBAL_MODULE | 468,960 | 7.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,688,504 | 28.7% |
| RESUME_CHECK | 2,349,158 | 18.3% |
| NOP | 1,359,856 | 10.6% |
| POP_JUMP_IF_FALSE | 1,101,364 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,087,712 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,875,364 | 22.4% |
| LOAD_ATTR_MODULE | 2,723,140 | 21.2% |
| LOAD_FAST_LOAD_FAST | 2,017,250 | 15.7% |
| LOAD_FAST | 1,624,120 | 12.6% |
| COMPARE_OP_STR | 1,065,784 | 8.3% |


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
| LOAD_FAST | 1,283,163 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 904,644 | 70.5% |
| CALL_PY_EXACT_ARGS | 374,199 | 29.2% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 9,409,114 | 33.6% |
| CACHE | 8,861,458 | 31.6% |
| FOR_ITER_GEN | 4,752,000 | 17.0% |
| COPY_FREE_VARS | 1,354,803 | 4.8% |
| CALL_PY_WITH_DEFAULTS | 1,326,703 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,689,961 | 56.0% |
| POP_TOP | 5,184,960 | 18.5% |
| LOAD_GLOBAL_BUILTIN | 2,760,447 | 9.9% |
| LOAD_GLOBAL_MODULE | 2,349,158 | 8.4% |
| NOP | 1,045,284 | 3.7% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,205,275 | 68.2% |
| LOAD_FAST_LOAD_FAST | 570,519 | 17.6% |
| SWAP | 431,985 | 13.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,656,636 | 51.2% |
| LOAD_FAST | 684,952 | 21.2% |
| LOAD_GLOBAL_MODULE | 533,559 | 16.5% |
| LOAD_CONST | 160,319 | 5.0% |
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
| LOAD_ATTR | 894,084 | 92.9% |
| LOAD_FAST | 33,506 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.7% |
| CALL | 7,680 | 0.8% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 896,397 | 93.2% |
| RETURN_CONST | 24,480 | 2.5% |
| LOAD_GLOBAL_MODULE | 20,640 | 2.1% |
| LOAD_CONST | 20,640 | 2.1% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 59.4% |
| COPY | 328 | 40.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 59.4% |
| POP_JUMP_IF_FALSE | 328 | 40.6% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,415,474 | 26.8% |
| CALL_ISINSTANCE | 907,044 | 17.2% |
| RETURN_VALUE | 684,935 | 13.0% |
| CALL | 548,176 | 10.4% |
| LOAD_FAST | 540,117 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,686,534 | 69.8% |
| POP_JUMP_IF_TRUE | 1,382,862 | 26.2% |
| UNARY_NOT | 212,447 | 4.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,174,392 | 54.9% |
| LOAD_FAST | 894,084 | 22.6% |
| BINARY_OP | 894,084 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,962,560 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 382,839 | 92.3% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 414,999 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,852 | 79.8% |
| LOAD_FAST | 20,640 | 11.4% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,452 | 91.7% |
| POP_JUMP_IF_TRUE | 14,880 | 8.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,000 | 93.0% |
| CALL_BUILTIN_FAST | 60,990 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 60,990 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 436,320 | 27.0% |
| LOAD_FAST_CHECK | 432,000 | 26.7% |
| FOR_ITER_LIST | 386,224 | 23.9% |
| CALL_BUILTIN_FAST | 348,745 | 21.6% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,610,489 | 99.7% |
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
| specialization.deferred |       477717 | 45.6% |
|          hit |       568564 | 54.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 218 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 218 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        22568 | 2.3% |
|          hit |       962157 | 97.7% |

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
| specialization.deferred |      1186919 | 10.8% |
|          hit |      9840542 | 89.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2 | 0.2% |
| Failure | 1,044 | 99.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 326 | 31.2% |
| tuple | 220 | 21.1% |
| sequence | 218 | 20.9% |
| set | 200 | 19.2% |
| other | 80 | 7.7% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5356486 | 77.4% |
|          hit |      1564893 | 22.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 47 | 2.3% |
| Failure | 2,035 | 97.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,017 | 50.0% |
| or | 592 | 29.1% |
| remainder | 226 | 11.1% |
| add different types | 160 | 7.9% |
| add other | 40 | 2.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8761087 | 29.3% |
| specialization.deopt |           60 | 0.0% |
|          hit |     21153598 | 70.7% |
|         miss |         4380 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 126 | 1.4% |
| Failure | 8,988 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,515 | 28.0% |
| cfunc noargs | 1,780 | 19.8% |
| class no vectorcall | 1,264 | 14.1% |
| meth descr varargs keywords | 837 | 9.3% |
| class mutable | 413 | 4.6% |
| other | 360 | 4.0% |
| cfunc varargs keywords | 333 | 3.7% |
| cfunc varargs | 320 | 3.6% |
| bound method | 286 | 3.2% |
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
| specialization.deferred |       438491 | 10.0% |
| specialization.deopt |           67 | 0.0% |
|          hit |      3933245 | 89.9% |
|         miss |         4782 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 117 | 24.9% |
| Failure | 353 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 153 | 43.3% |
| different types | 120 | 34.0% |
| big int | 80 | 22.7% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       976320 | 7.0% |
|          hit |     12895549 | 93.0% |

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
| specialization.deferred |      7799140 | 17.4% |
| specialization.deopt |         4192 | 0.0% |
|          hit |     36699830 | 82.0% |
|         miss |       229872 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,357 | 42.2% |
| Failure | 5,961 | 57.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,403 | 23.5% |
| not managed dict | 1,211 | 20.3% |
| shadowed | 1,196 | 20.1% |
| non overriding descriptor | 588 | 9.9% |
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
| specialization.deferred |           54 | 0.0% |
| specialization.deopt |           42 | 0.0% |
|          hit |     19438194 | 100.0% |
|         miss |         5590 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 182 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1350363 | 100.0% |


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
|          hit |      3159406 | 93.6% |
|         miss |       148120 | 4.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,787 | 81.3% |
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
|          hit |      2492759 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 228,449,018 | 53.0% |
| Not specialized | 60,254,632 | 14.0% |
| Specialized | 141,980,436 | 33.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,761,087 | 34.9% |
| LOAD_ATTR | 7,799,140 | 31.1% |
| BINARY_OP | 5,356,486 | 21.4% |
| TO_BOOL | 1,186,919 | 4.7% |
| FOR_ITER | 976,320 | 3.9% |
| BINARY_SUBSCR | 477,717 | 1.9% |
| COMPARE_OP | 438,491 | 1.7% |
| STORE_ATTR | 65,769 | 0.3% |
| STORE_SUBSCR | 22,568 | 0.1% |
| LOAD_GLOBAL | 54 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,078 | 40.8% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,674 | 15.4% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| LOAD_GLOBAL_MODULE | 5,590 | 1.4% |
| COMPARE_OP_INT | 4,782 | 1.2% |
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
| Calls to PyEval_EvalDefault | 8,948,818 | 31.9% |
| Calls to Python functions inlined | 19,088,272 | 68.1% |
| Calls via PyEval_EvalFrame (total) | 8,948,818 | 31.9% |
| Calls via PyEval_EvalFrame (vector) | 8,510,578 | 30.4% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,510,578 | 30.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 476,994 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 23,637,488 | 84.3% |
| Frame objects created | 37,592 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 15,062,474 | 42.8% |
| Frees to freelist | 15,063,934 |  |
| Allocations | 20,102,182 | 57.2% |
| Allocations to 512 bytes | 19,890,378 | 56.6% |
| Allocations to 4 kbytes | 86,031 | 0.2% |
| Allocations over 4 kbytes | 125,773 | 0.4% |
| Frees | 21,258,667 |  |
| New values | 65,280 |  |
| Interpreter increfs | 168,797,435 | 77.0% |
| Interpreter decrefs | 184,925,555 | 73.7% |
| Increfs | 50,423,972 | 23.0% |
| Decrefs | 66,002,667 | 26.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 9,159,782 |  |
| Method cache misses | 35,007 |  |
| Method cache collisions | 57,972 |  |
| Method cache dunder hits | 8,588,122 |  |
| Method cache dunder misses | 22,965 |  |


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
Stats gathered on: 2023-10-20
