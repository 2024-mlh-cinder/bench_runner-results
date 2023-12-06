
# Pystats results

- benchmark: concurrent_imap
- fork: brandtbucher
- ref: justin
- commit hash: 07fb485
- commit date: 2023-10-11T15:47:19+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 72,496,059 | 17.9% | 17.9% |  |
| RESUME_CHECK | 27,598,018 | 6.8% | 24.7% | 0.0% |
| STORE_FAST | 20,701,444 | 5.1% | 29.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,390,699 | 4.5% | 34.4% | 0.9% |
| POP_TOP | 18,048,537 | 4.5% | 38.9% |  |
| RETURN_VALUE | 16,713,046 | 4.1% | 43.0% |  |
| POP_JUMP_IF_FALSE | 14,393,337 | 3.6% | 46.5% |  |
| LOAD_GLOBAL_MODULE | 11,774,127 | 2.9% | 49.4% | 0.0% |
| LOAD_CONST | 11,125,170 | 2.7% | 52.2% |  |
| LOAD_FAST_LOAD_FAST | 10,395,319 | 2.6% | 54.8% |  |
| CALL_PY_EXACT_ARGS | 9,031,271 | 2.2% | 57.0% |  |
| INTERPRETER_EXIT | 8,958,080 | 2.2% | 59.2% |  |
| CALL | 8,787,189 | 2.2% | 61.4% |  |
| ENTER_EXECUTOR | 7,815,210 | 1.9% | 63.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,776,353 | 1.9% | 65.2% | 0.8% |
| LOAD_ATTR | 7,441,325 | 1.8% | 67.1% |  |
| RETURN_CONST | 6,908,434 | 1.7% | 68.8% |  |
| NOP | 6,756,837 | 1.7% | 70.5% |  |
| JUMP_BACKWARD | 5,706,396 | 1.4% | 71.9% |  |
| LOAD_GLOBAL_BUILTIN | 5,478,097 | 1.4% | 73.2% |  |
| COPY | 5,473,371 | 1.4% | 74.6% |  |
| BINARY_OP | 5,394,156 | 1.3% | 75.9% |  |
| YIELD_VALUE | 5,184,960 | 1.3% | 77.2% |  |
| TO_BOOL_BOOL | 5,068,155 | 1.3% | 78.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,820,101 | 1.2% | 79.6% |  |
| FOR_ITER_GEN | 4,760,640 | 1.2% | 80.8% |  |
| PUSH_NULL | 4,278,074 | 1.1% | 81.9% |  |
| TO_BOOL_INT | 3,989,486 | 1.0% | 82.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,777,061 | 0.9% | 83.8% |  |
| STORE_FAST_STORE_FAST | 3,635,726 | 0.9% | 84.7% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,244,413 | 0.8% | 85.5% | 4.6% |
| BUILD_TUPLE | 3,235,858 | 0.8% | 86.3% |  |
| COMPARE_OP_INT | 2,828,771 | 0.7% | 87.0% | 0.2% |
| CALL_PY_WITH_DEFAULTS | 2,230,226 | 0.6% | 87.5% |  |
| POP_JUMP_IF_TRUE | 1,995,384 | 0.5% | 88.0% |  |
| SWAP | 1,987,395 | 0.5% | 88.5% |  |
| CALL_FUNCTION_EX | 1,810,143 | 0.4% | 89.0% |  |
| LOAD_ATTR_MODULE | 1,777,486 | 0.4% | 89.4% |  |
| GET_ITER | 1,633,550 | 0.4% | 89.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,620,686 | 0.4% | 90.2% |  |
| FOR_ITER_LIST | 1,568,948 | 0.4% | 90.6% |  |
| LOAD_DEREF | 1,400,562 | 0.3% | 90.9% |  |
| BEFORE_WITH | 1,383,301 | 0.3% | 91.3% |  |
| COPY_FREE_VARS | 1,363,482 | 0.3% | 91.6% |  |
| CONTAINS_OP | 1,329,495 | 0.3% | 91.9% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,319,711 | 0.3% | 92.3% |  |
| LOAD_SUPER_ATTR_METHOD | 1,291,842 | 0.3% | 92.6% |  |
| UNARY_INVERT | 1,288,991 | 0.3% | 92.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,278,121 | 0.3% | 93.2% |  |
| JUMP_FORWARD | 1,272,966 | 0.3% | 93.5% |  |
| BUILD_MAP | 1,261,917 | 0.3% | 93.8% |  |
| CALL_BUILTIN_FAST | 1,208,809 | 0.3% | 94.1% |  |
| TO_BOOL | 1,187,181 | 0.3% | 94.4% |  |
| BUILD_LIST | 1,157,750 | 0.3% | 94.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,116,462 | 0.3% | 95.0% |  |
| COMPARE_OP_STR | 1,116,065 | 0.3% | 95.3% |  |
| FOR_ITER | 976,760 | 0.2% | 95.5% |  |
| STORE_SUBSCR_DICT | 968,794 | 0.2% | 95.8% |  |
| STORE_FAST_LOAD_FAST | 959,040 | 0.2% | 96.0% |  |
| CALL_ISINSTANCE | 913,125 | 0.2% | 96.2% |  |
| UNPACK_SEQUENCE_TUPLE | 876,990 | 0.2% | 96.4% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 847,710 | 0.2% | 96.6% |  |
| POP_JUMP_IF_NONE | 844,446 | 0.2% | 96.9% |  |
| BINARY_OP_ADD_INT | 831,569 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 804,474 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 804,474 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 788,563 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 720,796 | 0.2% | 97.8% |  |
| LIST_APPEND | 627,805 | 0.2% | 98.0% |  |
| LOAD_FAST_CHECK | 626,807 | 0.2% | 98.1% |  |
| CALL_BUILTIN_CLASS | 625,094 | 0.2% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 581,289 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 476,404 | 0.1% | 98.6% |  |
| COMPARE_OP | 441,318 | 0.1% | 98.7% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.8% |  |
| DICT_MERGE | 422,880 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 417,597 | 0.1% | 99.0% |  |
| LIST_EXTEND | 364,766 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,840 | 0.1% | 99.1% |  |
| CALL_LEN | 296,612 | 0.1% | 99.2% |  |
| CALL_KW | 268,842 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 247,283 | 0.1% | 99.3% |  |
| UNARY_NOT | 214,020 | 0.1% | 99.4% |  |
| CALL_LIST_APPEND | 203,053 | 0.1% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 194,894 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 182,504 | 0.0% | 99.5% |  |
| TO_BOOL_NONE | 180,327 | 0.0% | 99.6% |  |
| STORE_DEREF | 103,200 | 0.0% | 99.6% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.6% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 0.0% | 99.7% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,670 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,404 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,803 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 58,562 | 0.0% | 99.8% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 57,747 | 0.0% | 99.9% | 7.6% |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 36,023 | 0.0% | 99.9% |  |
| POP_EXCEPT | 36,023 | 0.0% | 99.9% |  |
| IS_OP | 34,491 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 31,703 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 28,800 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 99.9% |  |
| IMPORT_NAME | 24,480 | 0.0% | 99.9% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 23,887 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,763 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 21,120 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 13,920 | 0.0% | 100.0% |  |
| BINARY_SLICE | 13,920 | 0.0% | 100.0% |  |
| RERAISE | 12,960 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 12,960 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 9,600 | 0.0% | 100.0% |  |
| END_FOR | 8,640 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,640 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,320 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 1,920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 805 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 188 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,613,270 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_FAST | 15,580,065 | 3.8% | 8.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,996,711 | 2.2% | 10.2% |
| CACHE RESUME_CHECK | 8,875,039 | 2.2% | 12.4% |
| STORE_FAST LOAD_FAST | 8,846,398 | 2.2% | 14.6% |
| LOAD_FAST RETURN_VALUE | 8,098,732 | 2.0% | 16.6% |
| RETURN_VALUE INTERPRETER_EXIT | 7,854,560 | 1.9% | 18.5% |
| LOAD_FAST LOAD_ATTR | 5,864,741 | 1.4% | 19.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,783,497 | 1.4% | 21.4% |
| POP_TOP ENTER_EXECUTOR | 5,675,670 | 1.4% | 22.8% |
| POP_TOP LOAD_FAST | 5,589,766 | 1.4% | 24.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,400,760 | 1.3% | 25.5% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.3% | 26.8% |
| RETURN_CONST POP_TOP | 4,865,489 | 1.2% | 28.0% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.2% | 29.2% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.2% | 30.3% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.2% | 31.5% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.1% | 32.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,204,473 | 1.0% | 33.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,157,749 | 1.0% | 34.6% |
| NOP LOAD_FAST | 3,990,016 | 1.0% | 35.6% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,989,486 | 1.0% | 36.6% |
| ENTER_EXECUTOR YIELD_VALUE | 3,888,000 | 1.0% | 37.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,798,577 | 0.9% | 38.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,519,654 | 0.9% | 39.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,184,743 | 0.8% | 40.2% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,894,908 | 0.7% | 40.9% |
| STORE_FAST NOP | 2,890,805 | 0.7% | 41.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,826,456 | 0.7% | 42.3% |
| LOAD_FAST LOAD_CONST | 2,804,070 | 0.7% | 43.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,800,309 | 0.7% | 43.7% |
| LOAD_CONST LOAD_CONST | 2,799,735 | 0.7% | 44.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,775,207 | 0.7% | 45.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,697,107 | 0.7% | 45.7% |
| PUSH_NULL LOAD_FAST | 2,613,279 | 0.6% | 46.4% |
| CALL STORE_FAST | 2,545,545 | 0.6% | 47.0% |
| LOAD_ATTR LOAD_FAST | 2,472,781 | 0.6% | 47.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,410,903 | 0.6% | 48.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,377,430 | 0.6% | 48.8% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,215,667 | 0.5% | 49.3% |
| COPY TO_BOOL_INT | 2,189,156 | 0.5% | 49.9% |
| BINARY_OP COPY | 2,189,156 | 0.5% | 50.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,184,147 | 0.5% | 51.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,062,442 | 0.5% | 51.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,026,393 | 0.5% | 52.0% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 52.5% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 52.9% |
| LOAD_CONST CALL | 1,940,113 | 0.5% | 53.4% |
| LOAD_FAST PUSH_NULL | 1,932,662 | 0.5% | 53.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,904,777 | 0.5% | 54.4% |
| CALL RETURN_VALUE | 1,876,965 | 0.5% | 54.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,803,736 | 0.4% | 55.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,777,395 | 0.4% | 55.7% |
| RETURN_VALUE STORE_FAST | 1,741,464 | 0.4% | 56.1% |
| CALL POP_TOP | 1,697,891 | 0.4% | 56.6% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,667,028 | 0.4% | 57.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,634,096 | 0.4% | 57.4% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,615,406 | 0.4% | 57.8% |
| LOAD_CONST COMPARE_OP_INT | 1,549,829 | 0.4% | 58.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,529,393 | 0.4% | 58.5% |
| RETURN_VALUE RETURN_VALUE | 1,507,206 | 0.4% | 58.9% |
| POP_TOP RETURN_CONST | 1,430,157 | 0.4% | 59.3% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,263 | 0.3% | 59.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,380,165 | 0.3% | 60.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,375,691 | 0.3% | 60.3% |
| NOP LOAD_GLOBAL_MODULE | 1,368,248 | 0.3% | 60.6% |
| COPY_FREE_VARS RESUME_CHECK | 1,363,482 | 0.3% | 61.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,362,664 | 0.3% | 61.3% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,359,042 | 0.3% | 61.6% |
| LOAD_DEREF LOAD_FAST | 1,359,042 | 0.3% | 62.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,334,481 | 0.3% | 62.3% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,330,061 | 0.3% | 62.6% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,329,495 | 0.3% | 63.0% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,329,494 | 0.3% | 63.3% |
| LOAD_FAST BUILD_TUPLE | 1,320,645 | 0.3% | 63.6% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,316,492 | 0.3% | 63.9% |
| POP_TOP LOAD_CONST | 1,305,140 | 0.3% | 64.3% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,291,842 | 0.3% | 64.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,289,786 | 0.3% | 64.9% |
| UNARY_INVERT BINARY_OP | 1,288,991 | 0.3% | 65.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,276,962 | 0.3% | 65.5% |
| ENTER_EXECUTOR CALL | 1,228,477 | 0.3% | 65.8% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,204,826 | 0.3% | 66.1% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,202,440 | 0.3% | 66.4% |
| LOAD_CONST LOAD_FAST | 1,201,793 | 0.3% | 66.7% |
| GET_ITER FOR_ITER_LIST | 1,191,834 | 0.3% | 67.0% |
| POP_TOP NOP | 1,188,527 | 0.3% | 67.3% |
| LOAD_FAST GET_ITER | 1,152,590 | 0.3% | 67.6% |
| LOAD_FAST TO_BOOL | 1,146,287 | 0.3% | 67.9% |
| RETURN_VALUE POP_TOP | 1,143,081 | 0.3% | 68.2% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,132,008 | 0.3% | 68.5% |
| POP_JUMP_IF_FALSE POP_TOP | 1,126,606 | 0.3% | 68.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,107,440 | 0.3% | 69.0% |
| BINARY_OP STORE_FAST | 1,105,138 | 0.3% | 69.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,088,626 | 0.3% | 69.5% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,086,703 | 0.3% | 69.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,077,669 | 0.3% | 70.1% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 1,067,095 | 0.3% | 70.3% |
| RESUME_CHECK NOP | 1,051,365 | 0.3% | 70.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 1,041,129 | 0.3% | 70.9% |


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
| RESUME_CHECK | 8,875,039 | 99.0% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 936,039 | 67.7% |
| RETURN_VALUE | 376,797 | 27.2% |
| LOAD_GLOBAL_MODULE | 61,921 | 4.5% |
| CALL | 4,320 | 0.3% |
| ENTER_EXECUTOR | 4,224 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,184 | 72.4% |
| STORE_FAST | 381,117 | 27.6% |


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
| LOAD_FAST_LOAD_FAST | 432,000 | 90.7% |
| LOAD_CONST | 44,183 | 9.3% |
| BINARY_SUBSCR | 221 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.7% |
| STORE_FAST | 44,183 | 9.3% |
| BINARY_SUBSCR | 221 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 27,863 | 87.9% |
| LOAD_ATTR_MODULE | 3,840 | 12.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 31,703 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,321 | 48.4% |
| CALL | 20,641 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,599 | 16.4% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,601 | 77.9% |
| RETURN_CONST | 7,681 | 13.1% |
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
| RETURN_CONST | 804,474 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 804,474 | 100.0% |


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
| LOAD_FAST | 1,152,590 | 70.6% |
| STORE_FAST_LOAD_FAST | 432,000 | 26.4% |
| CALL_BUILTIN_CLASS | 28,800 | 1.8% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,191,834 | 73.0% |
| LOAD_FAST_AND_CLEAR | 386,876 | 23.7% |
| FOR_ITER_RANGE | 23,640 | 1.4% |
| FOR_ITER_TUPLE | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,854,560 | 87.7% |
| RETURN_CONST | 670,560 | 7.5% |
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
| STORE_FAST | 2,890,805 | 42.8% |
| POP_TOP | 1,188,527 | 17.6% |
| RESUME_CHECK | 1,051,365 | 15.6% |
| POP_JUMP_IF_FALSE | 1,011,574 | 15.0% |
| POP_JUMP_IF_NOT_NONE | 383,223 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,990,016 | 59.1% |
| LOAD_GLOBAL_MODULE | 1,368,248 | 20.2% |
| LOAD_GLOBAL_BUILTIN | 556,053 | 8.2% |
| LOAD_FAST_LOAD_FAST | 437,280 | 6.5% |
| LOAD_CONST | 396,960 | 5.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 23,543 | 65.4% |
| COPY | 8,640 | 24.0% |
| POP_TOP | 3,840 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 23,543 | 65.4% |
| RERAISE | 8,640 | 24.0% |
| JUMP_FORWARD | 3,840 | 10.7% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,184,960 | 28.7% |
| RETURN_CONST | 4,865,489 | 27.0% |
| CALL | 1,697,891 | 9.4% |
| RETURN_VALUE | 1,143,081 | 6.3% |
| POP_JUMP_IF_FALSE | 1,126,606 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,675,670 | 31.4% |
| LOAD_FAST | 5,589,766 | 31.0% |
| RETURN_CONST | 1,430,157 | 7.9% |
| LOAD_CONST | 1,305,140 | 7.2% |
| NOP | 1,188,527 | 6.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 27,863 | 77.3% |
| RERAISE | 4,320 | 12.0% |
| CALL_KW | 3,840 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 27,863 | 77.3% |
| WITH_EXCEPT_START | 4,320 | 12.0% |
| LOAD_GLOBAL_MODULE | 3,840 | 10.7% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,932,662 | 45.2% |
| LOAD_ATTR_MODULE | 1,289,786 | 30.1% |
| LOAD_ATTR | 961,426 | 22.5% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,613,279 | 61.1% |
| CALL | 759,022 | 17.7% |
| LOAD_FAST_LOAD_FAST | 614,460 | 14.4% |
| LOAD_CONST | 236,037 | 5.5% |
| CALL_PY_EXACT_ARGS | 37,440 | 0.9% |


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
| LOAD_FAST | 8,098,732 | 48.5% |
| CALL | 1,876,965 | 11.2% |
| RETURN_VALUE | 1,507,206 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,202,440 | 7.2% |
| CALL_FUNCTION_EX | 948,903 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,854,560 | 47.0% |
| STORE_FAST | 1,741,464 | 10.4% |
| RETURN_VALUE | 1,507,206 | 9.0% |
| POP_TOP | 1,143,081 | 6.8% |
| LOAD_FAST_LOAD_FAST | 900,165 | 5.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,683 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.4% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 2 | 0.0% |
| LOAD_FAST | 1 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,146,287 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,843 | 3.4% |
| TO_BOOL | 1,047 | 0.1% |
| LOAD_ATTR | 3 | 0.0% |
| RETURN_VALUE | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 635,056 | 53.5% |
| POP_JUMP_IF_FALSE | 551,077 | 46.4% |
| TO_BOOL | 1,047 | 0.1% |
| TO_BOOL_BOOL | 1 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 900,165 | 69.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 388,826 | 30.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,288,991 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 214,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 214,020 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,894,908 | 53.7% |
| UNARY_INVERT | 1,288,991 | 23.9% |
| POP_JUMP_IF_FALSE | 900,165 | 16.7% |
| LOAD_ATTR | 204,973 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,189,156 | 40.6% |
| STORE_FAST | 1,105,138 | 20.5% |
| UNARY_INVERT | 900,165 | 16.7% |
| TO_BOOL_INT | 900,165 | 16.7% |
| BUILD_TUPLE | 194,413 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 386,876 | 33.4% |
| JUMP_FORWARD | 376,797 | 32.5% |
| LOAD_FAST | 194,894 | 16.8% |
| POP_TOP | 181,903 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 389,277 | 33.6% |
| SWAP | 386,876 | 33.4% |
| STORE_FAST | 377,757 | 32.6% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 432,000 | 34.2% |
| LOAD_FAST | 396,960 | 31.5% |
| RESUME_CHECK | 384,477 | 30.5% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.1% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,957 | 64.7% |
| BUILD_TUPLE | 432,000 | 34.2% |
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
| LOAD_FAST | 1,320,645 | 40.8% |
| LOAD_FAST_LOAD_FAST | 870,240 | 26.9% |
| BUILD_MAP | 432,000 | 13.4% |
| RETURN_VALUE | 384,000 | 11.9% |
| BINARY_OP | 194,413 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 901,125 | 27.8% |
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
| LOAD_CONST | 1,940,113 | 22.1% |
| ENTER_EXECUTOR | 1,228,477 | 14.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,077,669 | 12.3% |
| LOAD_FAST_LOAD_FAST | 1,022,665 | 11.6% |
| BUILD_TUPLE | 901,125 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,545,545 | 29.0% |
| RETURN_VALUE | 1,876,965 | 21.4% |
| POP_TOP | 1,697,891 | 19.3% |
| LOAD_FAST | 791,171 | 9.0% |
| TO_BOOL_BOOL | 546,374 | 6.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,263 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,903 | 52.4% |
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
| LOAD_CONST | 264,522 | 98.4% |
| ENTER_EXECUTOR | 4,320 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 216,943 | 80.7% |
| LOAD_FAST | 21,600 | 8.0% |
| RETURN_VALUE | 15,840 | 5.9% |
| STORE_FAST | 10,560 | 3.9% |
| PUSH_EXC_INFO | 3,840 | 1.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 440,527 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 417 | 0.1% |
| COMPARE_OP | 294 | 0.1% |
| COMPARE_OP_INT | 70 | 0.0% |
| LOAD_GLOBAL_MODULE | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 440,903 | 99.9% |
| COMPARE_OP | 294 | 0.1% |
| COMPARE_OP_INT | 111 | 0.0% |
| COMPARE_OP_STR | 10 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,329,494 | 100.0% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,329,495 | 100.0% |


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
| BINARY_OP | 2,189,156 | 40.0% |
| STORE_FAST | 1,972,320 | 36.0% |
| LOAD_CONST | 825,600 | 15.1% |
| LOAD_FAST | 439,890 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,189,156 | 40.0% |
| STORE_FAST | 1,972,800 | 36.0% |
| STORE_FAST_STORE_FAST | 820,320 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 429,327 | 7.8% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 900,165 | 66.0% |
| CALL_ALLOC_AND_ENTER_INIT | 376,797 | 27.6% |
| CACHE | 82,080 | 6.0% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,363,482 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,803 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,202 | 66.7% |
| RETURN_CONST | 20,641 | 31.9% |
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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,675,670 | 72.6% |
| POP_JUMP_IF_NOT_NONE | 748,106 | 9.6% |
| LIST_APPEND | 543,325 | 7.0% |
| STORE_FAST_STORE_FAST | 432,000 | 5.5% |
| CALL_LIST_APPEND | 194,413 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 3,888,000 | 49.7% |
| CALL | 1,228,477 | 15.7% |
| LOAD_FAST | 760,955 | 9.7% |
| CALL_PY_WITH_DEFAULTS | 571,368 | 7.3% |
| LOAD_ATTR_PROPERTY | 534,307 | 6.8% |


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
| RETURN_VALUE | 20,640 | 59.8% |
| LOAD_FAST | 12,960 | 37.6% |
| LOAD_GLOBAL_MODULE | 891 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,491 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,320,000 | 75.7% |
| POP_TOP | 864,869 | 15.2% |
| ENTER_EXECUTOR | 432,000 | 7.6% |
| LIST_APPEND | 84,480 | 1.5% |
| STORE_FAST_STORE_FAST | 4,320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 4,752,000 | 83.3% |
| FOR_ITER | 952,800 | 16.7% |
| FOR_ITER_LIST | 798 | 0.0% |
| LOAD_FAST | 345 | 0.0% |
| FOR_ITER_RANGE | 247 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 807,355 | 63.4% |
| POP_TOP | 452,171 | 35.5% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 840,465 | 66.0% |
| BUILD_LIST | 376,797 | 29.6% |
| POP_EXCEPT | 23,543 | 1.8% |
| LOAD_GLOBAL_MODULE | 18,721 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 348,912 | 55.6% |
| LOAD_ATTR | 194,413 | 31.0% |
| BINARY_SUBSCR_STR_INT | 84,480 | 13.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 543,325 | 86.5% |
| JUMP_BACKWARD | 84,480 | 13.5% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 182,863 | 50.1% |
| RETURN_VALUE | 181,903 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 182,383 | 50.0% |
| STORE_FAST | 181,903 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,864,741 | 78.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,362,664 | 18.3% |
| LOAD_GLOBAL_MODULE | 119,611 | 1.6% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,883 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,472,781 | 33.2% |
| PUSH_NULL | 961,426 | 12.9% |
| STORE_SUBSCR_DICT | 900,165 | 12.1% |
| POP_JUMP_IF_NOT_NONE | 821,537 | 11.0% |
| STORE_FAST | 559,257 | 7.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,804,070 | 25.2% |
| LOAD_CONST | 2,799,735 | 25.2% |
| POP_TOP | 1,305,140 | 11.7% |
| POP_JUMP_IF_FALSE | 691,059 | 6.2% |
| LOAD_ATTR_METHOD_NO_DICT | 548,733 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,799,735 | 25.2% |
| CALL | 1,940,113 | 17.4% |
| COMPARE_OP_INT | 1,549,829 | 13.9% |
| LOAD_FAST | 1,201,793 | 10.8% |
| COPY | 825,600 | 7.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,359,042 | 97.0% |
| STORE_DEREF | 20,640 | 1.5% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.5% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,359,042 | 97.0% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 2.9% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,580,065 | 21.5% |
| STORE_FAST | 8,846,398 | 12.2% |
| POP_JUMP_IF_FALSE | 5,783,497 | 8.0% |
| POP_TOP | 5,589,766 | 7.7% |
| NOP | 3,990,016 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,613,270 | 22.9% |
| RETURN_VALUE | 8,098,732 | 11.2% |
| LOAD_ATTR | 5,864,741 | 8.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,400,760 | 7.4% |
| CALL_PY_EXACT_ARGS | 3,798,577 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 386,876 | 66.6% |
| LOAD_FAST_AND_CLEAR | 194,413 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 386,876 | 66.6% |
| LOAD_FAST_AND_CLEAR | 194,413 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 68.9% |
| POP_JUMP_IF_NONE | 182,384 | 29.1% |
| LOAD_ATTR_CLASS | 12,423 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 68.9% |
| LOAD_GLOBAL_MODULE | 182,384 | 29.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,423 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,026,393 | 19.5% |
| LOAD_FAST_LOAD_FAST | 1,380,165 | 13.3% |
| POP_JUMP_IF_FALSE | 1,132,008 | 10.9% |
| LOAD_SUPER_ATTR_METHOD | 910,725 | 8.8% |
| RETURN_VALUE | 900,165 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,410,903 | 23.2% |
| LOAD_FAST_LOAD_FAST | 1,380,165 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,316,492 | 12.7% |
| CALL | 1,022,665 | 9.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 900,165 | 8.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 42.6% |
| RESUME_CHECK | 40 | 21.3% |
| POP_JUMP_IF_FALSE | 40 | 21.3% |
| POP_JUMP_IF_TRUE | 14 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 10 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 101 | 53.7% |
| LOAD_ATTR | 43 | 22.9% |
| LOAD_GLOBAL_BUILTIN | 41 | 21.8% |
| LOAD_FAST | 3 | 1.6% |


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
| TO_BOOL_INT | 3,989,486 | 27.7% |
| TO_BOOL_BOOL | 3,519,654 | 24.5% |
| COMPARE_OP_INT | 2,826,456 | 19.6% |
| CONTAINS_OP | 1,329,495 | 9.2% |
| COMPARE_OP_STR | 1,086,703 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,783,497 | 40.2% |
| RETURN_CONST | 2,377,430 | 16.5% |
| LOAD_FAST_LOAD_FAST | 1,132,008 | 7.9% |
| POP_TOP | 1,126,606 | 7.8% |
| LOAD_GLOBAL_MODULE | 1,107,440 | 7.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 799,806 | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.7% |
| LOAD_ATTR | 21,120 | 2.5% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 222,099 | 26.3% |
| NOP | 210,223 | 24.9% |
| LOAD_FAST | 192,683 | 22.8% |
| LOAD_FAST_CHECK | 182,384 | 21.6% |
| RETURN_CONST | 18,240 | 2.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,803,736 | 47.8% |
| LOAD_ATTR | 821,537 | 21.8% |
| LOAD_ATTR_INSTANCE_VALUE | 746,222 | 19.8% |
| RETURN_VALUE | 349,392 | 9.3% |
| LOAD_DEREF | 41,280 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,529,393 | 40.5% |
| RETURN_CONST | 821,862 | 21.8% |
| ENTER_EXECUTOR | 748,106 | 19.8% |
| NOP | 383,223 | 10.1% |
| LOAD_CONST | 181,903 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,334,481 | 66.9% |
| TO_BOOL | 635,056 | 31.8% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,242 | 0.4% |
| COMPARE_OP_INT | 2,245 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 715,044 | 35.8% |
| LOAD_FAST_LOAD_FAST | 637,933 | 32.0% |
| RETURN_CONST | 505,875 | 25.4% |
| LOAD_GLOBAL_MODULE | 53,305 | 2.7% |
| RETURN_VALUE | 44,183 | 2.2% |


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
| POP_JUMP_IF_FALSE | 2,377,430 | 34.4% |
| STORE_ATTR_INSTANCE_VALUE | 1,667,028 | 24.1% |
| POP_TOP | 1,430,157 | 20.7% |
| POP_JUMP_IF_NOT_NONE | 821,862 | 11.9% |
| POP_JUMP_IF_TRUE | 505,875 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,865,489 | 70.4% |
| EXIT_INIT_CHECK | 804,474 | 11.6% |
| INTERPRETER_EXIT | 670,560 | 9.7% |
| TO_BOOL_BOOL | 494,914 | 7.2% |
| STORE_FAST | 45,143 | 0.7% |


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
| SWAP | 3 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_FAST | 8,641 | 13.0% |
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
| YIELD_VALUE | 4,752,000 | 23.0% |
| CALL | 2,545,545 | 12.3% |
| COPY | 1,972,800 | 9.5% |
| RETURN_VALUE | 1,741,464 | 8.4% |
| BINARY_OP | 1,105,138 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,846,398 | 42.7% |
| JUMP_BACKWARD | 4,320,000 | 20.9% |
| NOP | 2,890,805 | 14.0% |
| COPY | 1,972,320 | 9.5% |
| JUMP_FORWARD | 807,355 | 3.9% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 516,480 | 53.9% |
| FOR_ITER_LIST | 432,000 | 45.0% |
| COPY | 10,560 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 432,000 | 45.0% |
| GET_ITER | 432,000 | 45.0% |
| LOAD_FAST | 84,480 | 8.8% |
| STORE_ATTR_INSTANCE_VALUE | 10,560 | 1.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,615,406 | 44.4% |
| COPY | 820,320 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 22.4% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,204,826 | 33.1% |
| STORE_FAST | 816,000 | 22.4% |
| LOAD_FAST_LOAD_FAST | 783,060 | 21.5% |
| ENTER_EXECUTOR | 432,000 | 11.9% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 429,329 | 21.6% |
| LOAD_FAST_AND_CLEAR | 386,876 | 19.5% |
| BUILD_LIST | 386,876 | 19.5% |
| ENTER_EXECUTOR | 376,316 | 18.9% |
| LOAD_FAST | 203,024 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 429,327 | 21.6% |
| LOAD_CONST | 397,437 | 20.0% |
| STORE_FAST | 386,876 | 19.5% |
| BUILD_LIST | 386,876 | 19.5% |
| FOR_ITER_LIST | 376,316 | 18.9% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,888,000 | 75.0% |
| BUILD_TUPLE | 864,000 | 16.7% |
| STORE_FAST_LOAD_FAST | 432,000 | 8.3% |
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
| LOAD_FAST | 194,894 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 194,894 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 817,647 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 429,329 | 51.6% |
| STORE_FAST | 384,000 | 46.2% |
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
| CALL | 182,384 | 99.9% |
| LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 182,504 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,780 | 80.4% |
| LOAD_CONST | 44,183 | 17.9% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 242,963 | 98.3% |
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
| LOAD_CONST | 8,640 | 66.7% |
| LOAD_FAST_LOAD_FAST | 4,320 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,640 | 66.7% |
| STORE_FAST | 4,320 | 33.3% |


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
| LOAD_GLOBAL_MODULE | 397,437 | 49.4% |
| LOAD_FAST | 382,077 | 47.5% |
| CALL | 24,960 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 427,677 | 53.2% |
| COPY_FREE_VARS | 376,797 | 46.8% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,000 | 83.1% |
| LOAD_CONST | 4,800 | 8.3% |
| BINARY_OP_ADD_INT | 4,320 | 7.5% |
| PUSH_NULL | 556 | 1.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 53,367 | 92.4% |
| POP_TOP | 4,320 | 7.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 61.4% |
| LOAD_FAST | 208,414 | 33.3% |
| LOAD_CONST | 11,040 | 1.8% |
| LOAD_GLOBAL_BUILTIN | 7,680 | 1.2% |
| CALL_LEN | 4,320 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 578,894 | 92.6% |
| GET_ITER | 28,800 | 4.6% |
| LOAD_FAST | 12,960 | 2.1% |
| CALL_BUILTIN_CLASS | 4,320 | 0.7% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 675,936 | 55.9% |
| LOAD_CONST | 299,983 | 24.8% |
| LOAD_FAST_LOAD_FAST | 129,660 | 10.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60,990 | 5.0% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 447,433 | 37.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 351,060 | 29.0% |
| TO_BOOL_BOOL | 292,783 | 24.2% |
| UNPACK_SEQUENCE_TUPLE | 60,990 | 5.0% |
| POP_TOP | 10,943 | 0.9% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 387,840 | 45.8% |
| BUILD_TUPLE | 384,000 | 45.3% |
| CALL | 48,567 | 5.7% |
| LOAD_FAST_CHECK | 12,423 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 785,760 | 92.7% |
| RETURN_VALUE | 60,990 | 7.2% |
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
| LOAD_GLOBAL_BUILTIN | 913,125 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 913,125 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 275,971 | 93.0% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 7.0% |
| CALL | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,300 | 87.1% |
| CALL_PY_EXACT_ARGS | 24,960 | 8.4% |
| LOAD_FAST | 4,320 | 1.5% |
| CALL_BUILTIN_CLASS | 4,320 | 1.5% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 1.5% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 194,413 | 95.7% |
| LOAD_FAST | 8,640 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 194,413 | 95.7% |
| LOAD_GLOBAL_MODULE | 8,640 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,276,962 | 99.9% |
| LOAD_CONST | 960 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 197 | 0.0% |
| CALL | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 900,165 | 70.4% |
| STORE_FAST | 376,996 | 29.5% |
| TO_BOOL_NONE | 960 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,480 | 85.0% |
| BUILD_TUPLE | 4,320 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 20,160 | 70.0% |
| LOAD_FAST | 8,640 | 30.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,041,129 | 93.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,413 | 6.6% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 480,043 | 43.0% |
| STORE_FAST | 432,000 | 38.7% |
| LOAD_FAST | 63,840 | 5.7% |
| CALL_BUILTIN_FAST | 60,990 | 5.5% |
| RETURN_VALUE | 38,766 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 663,194 | 92.0% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,602 | 3.0% |
| RETURN_VALUE | 10,560 | 1.5% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 684,796 | 95.0% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.5% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,157,749 | 46.0% |
| LOAD_FAST | 3,798,577 | 42.1% |
| LOAD_FAST_LOAD_FAST | 446,880 | 4.9% |
| LOAD_SUPER_ATTR_METHOD | 376,797 | 4.2% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,996,711 | 99.6% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 877,844 | 39.4% |
| ENTER_EXECUTOR | 571,368 | 25.6% |
| LOAD_ATTR_MODULE | 376,797 | 16.9% |
| LOAD_FAST | 256,813 | 11.5% |
| LOAD_CONST | 80,684 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,330,061 | 59.6% |
| COPY_FREE_VARS | 900,165 | 40.4% |


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
| LOAD_CONST | 1,549,829 | 54.8% |
| LOAD_ATTR_INSTANCE_VALUE | 814,826 | 28.8% |
| LOAD_FAST | 432,000 | 15.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,826,456 | 99.9% |
| POP_JUMP_IF_TRUE | 2,245 | 0.1% |
| COMPARE_OP | 70 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,067,095 | 95.6% |
| LOAD_CONST | 44,640 | 4.0% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,086,703 | 97.4% |
| LOAD_FAST | 10,560 | 0.9% |
| COPY | 10,560 | 0.9% |
| POP_JUMP_IF_TRUE | 8,242 | 0.7% |


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
| GET_ITER | 1,191,834 | 76.0% |
| SWAP | 376,316 | 24.0% |
| JUMP_BACKWARD | 798 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 564,661 | 36.0% |
| STORE_FAST_LOAD_FAST | 432,000 | 27.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 388,826 | 24.8% |
| LOAD_FAST | 182,384 | 11.6% |
| RETURN_CONST | 872 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 23,640 | 99.0% |
| JUMP_BACKWARD | 247 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 23,867 | 99.9% |
| LOAD_FAST | 20 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 8,640 | 90.0% |
| LOAD_FAST | 960 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,600 | 100.0% |


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
| LOAD_FAST | 56,247 | 81.9% |
| LOAD_FAST_CHECK | 12,423 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,613,270 | 90.3% |
| LOAD_FAST_LOAD_FAST | 1,316,492 | 7.2% |
| COPY | 429,327 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 18,145 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,204,473 | 22.9% |
| LOAD_FAST | 2,800,309 | 15.2% |
| TO_BOOL_BOOL | 1,375,691 | 7.5% |
| LOAD_ATTR | 1,362,664 | 7.4% |
| CONTAINS_OP | 1,329,494 | 7.2% |


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
| CALL | 111,447 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,413 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,204,473 | 87.2% |
| LOAD_FAST | 467,784 | 9.7% |
| LOAD_ATTR | 62,884 | 1.3% |
| LOAD_ATTR_SLOT | 62,880 | 1.3% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,904,777 | 39.5% |
| CALL | 1,077,669 | 22.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,041,129 | 21.6% |
| LOAD_CONST | 548,733 | 11.4% |
| LOAD_FAST_LOAD_FAST | 226,193 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,400,760 | 69.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,010,177 | 13.0% |
| LOAD_FAST_LOAD_FAST | 900,165 | 11.6% |
| BINARY_SUBSCR | 432,000 | 5.6% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,157,749 | 53.5% |
| LOAD_FAST | 2,062,442 | 26.5% |
| CALL_PY_WITH_DEFAULTS | 877,844 | 11.3% |
| LOAD_FAST_LOAD_FAST | 508,800 | 6.5% |
| LOAD_CONST | 94,604 | 1.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,777,395 | 100.0% |
| LOAD_ATTR | 91 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,289,786 | 72.6% |
| CALL_PY_WITH_DEFAULTS | 376,797 | 21.2% |
| STORE_DEREF | 41,280 | 2.3% |
| LOAD_CONST | 26,400 | 1.5% |
| LOAD_FAST | 20,640 | 1.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 930,885 | 70.5% |
| LOAD_FAST_LOAD_FAST | 388,826 | 29.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 900,165 | 68.2% |
| UNARY_INVERT | 388,826 | 29.5% |
| RETURN_VALUE | 10,560 | 0.8% |
| LOAD_CONST | 10,560 | 0.8% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 534,307 | 67.8% |
| LOAD_FAST | 232,496 | 29.5% |
| RETURN_VALUE | 20,640 | 2.6% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 779,443 | 98.8% |
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
| RESUME_CHECK | 2,775,207 | 50.7% |
| LOAD_FAST | 933,285 | 17.0% |
| NOP | 556,053 | 10.2% |
| STORE_FAST | 549,177 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 392,640 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,697,107 | 49.2% |
| LOAD_DEREF | 1,359,042 | 24.8% |
| CALL_ISINSTANCE | 913,125 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 392,640 | 7.2% |
| LOAD_GLOBAL_MODULE | 36,960 | 0.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,184,743 | 27.0% |
| RESUME_CHECK | 2,184,147 | 18.6% |
| NOP | 1,368,248 | 11.6% |
| POP_JUMP_IF_FALSE | 1,107,440 | 9.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,088,626 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,894,908 | 24.6% |
| LOAD_FAST_LOAD_FAST | 2,026,393 | 17.2% |
| LOAD_ATTR_MODULE | 1,777,395 | 15.1% |
| LOAD_FAST | 1,634,096 | 13.9% |
| COMPARE_OP_STR | 1,067,095 | 9.1% |


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
| LOAD_FAST | 1,291,842 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 910,725 | 70.5% |
| CALL_PY_EXACT_ARGS | 376,797 | 29.2% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 8,996,711 | 32.6% |
| CACHE | 8,875,039 | 32.2% |
| FOR_ITER_GEN | 4,752,000 | 17.2% |
| COPY_FREE_VARS | 1,363,482 | 4.9% |
| CALL_PY_WITH_DEFAULTS | 1,330,061 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,580,065 | 56.5% |
| POP_TOP | 5,184,960 | 18.8% |
| LOAD_GLOBAL_BUILTIN | 2,775,207 | 10.1% |
| LOAD_GLOBAL_MODULE | 2,184,147 | 7.9% |
| NOP | 1,051,365 | 3.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,215,667 | 68.3% |
| LOAD_FAST_LOAD_FAST | 573,117 | 17.7% |
| SWAP | 429,327 | 13.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,667,028 | 51.4% |
| LOAD_FAST | 682,289 | 21.0% |
| LOAD_GLOBAL_MODULE | 536,157 | 16.5% |
| LOAD_CONST | 160,319 | 4.9% |
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
| LOAD_ATTR | 900,165 | 92.9% |
| LOAD_FAST | 34,067 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.7% |
| CALL | 7,680 | 0.8% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 903,034 | 93.2% |
| RETURN_CONST | 24,480 | 2.5% |
| LOAD_GLOBAL_MODULE | 20,640 | 2.1% |
| LOAD_CONST | 20,640 | 2.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,375,691 | 27.1% |
| CALL_ISINSTANCE | 913,125 | 18.0% |
| RETURN_VALUE | 689,390 | 13.6% |
| CALL | 546,374 | 10.8% |
| LOAD_FAST | 538,583 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,519,654 | 69.4% |
| POP_JUMP_IF_TRUE | 1,334,481 | 26.3% |
| UNARY_NOT | 214,020 | 4.2% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,189,156 | 54.9% |
| LOAD_FAST | 900,165 | 22.6% |
| BINARY_OP | 900,165 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,989,486 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 385,437 | 92.3% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 417,597 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,847 | 79.8% |
| LOAD_FAST | 20,640 | 11.4% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,447 | 91.7% |
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
| FOR_ITER | 436,320 | 26.9% |
| LOAD_FAST_CHECK | 432,000 | 26.7% |
| FOR_ITER_LIST | 388,826 | 24.0% |
| CALL_BUILTIN_FAST | 351,060 | 21.7% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,615,406 | 99.7% |
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
| STORE_FAST | 480 | 59.6% |
| COPY | 325 | 40.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 59.6% |
| POP_JUMP_IF_FALSE | 325 | 40.4% |


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
| specialization.deferred |       476183 | 45.5% |
|          hit |       571166 | 54.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 221 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 221 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        22561 | 2.3% |
|          hit |       968794 | 97.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2 | 1.0% |
| Failure | 200 | 99.0% |

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
| specialization.deferred |      1186133 | 10.7% |
|          hit |      9887147 | 89.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1 | 0.1% |
| Failure | 1,047 | 99.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 326 | 31.1% |
| sequence | 221 | 21.1% |
| tuple | 220 | 21.0% |
| set | 200 | 19.1% |
| other | 80 | 7.6% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5392084 | 77.5% |
|          hit |      1565960 | 22.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 42 | 2.0% |
| Failure | 2,030 | 98.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,011 | 49.8% |
| or | 588 | 29.0% |
| remainder | 231 | 11.4% |
| add different types | 160 | 7.9% |
| add other | 40 | 2.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8778120 | 29.2% |
| specialization.deopt |           60 | 0.0% |
|          hit |     21235937 | 70.7% |
|         miss |         4380 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 116 | 1.3% |
| Failure | 9,013 | 98.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,521 | 28.0% |
| cfunc noargs | 1,792 | 19.9% |
| class no vectorcall | 1,266 | 14.0% |
| meth descr varargs keywords | 846 | 9.4% |
| class mutable | 411 | 4.6% |
| other | 360 | 4.0% |
| cfunc varargs keywords | 331 | 3.7% |
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
| specialization.deferred |       440903 | 10.1% |
| specialization.deopt |           70 | 0.0% |
|          hit |      3939897 | 89.8% |
|         miss |         4939 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 121 | 24.9% |
| Failure | 364 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 158 | 43.4% |
| different types | 126 | 34.6% |
| big int | 80 | 22.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       976320 | 13.3% |
|          hit |      6363075 | 86.7% |

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
| specialization.deferred |      7435269 | 16.7% |
| specialization.deopt |         4191 | 0.0% |
|          hit |     36800805 | 82.7% |
|         miss |       230292 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,311 | 42.1% |
| Failure | 5,936 | 57.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,402 | 23.6% |
| not managed dict | 1,205 | 20.3% |
| shadowed | 1,189 | 20.0% |
| non overriding descriptor | 578 | 9.7% |
| class attr descriptor | 360 | 6.1% |
| metaclass attribute | 280 | 4.7% |
| class method obj | 280 | 4.7% |
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
|---|---|---|
| specialization.deferred |           46 | 0.0% |
| specialization.deopt |           63 | 0.0% |
|          hit |     19532594 | 100.0% |
|         miss |         5781 | 0.0% |

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
|          hit |      1359042 | 100.0% |


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
| specialization.deferred |        65762 | 1.9% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      3172403 | 93.7% |
|         miss |       148120 | 4.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,782 | 81.3% |
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
|          hit |      2497676 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 223,213,285 | 55.2% |
| Not specialized | 51,917,745 | 12.8% |
| Specialized | 129,565,428 | 32.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 18,446,744,073,709,551,615 | 100.0% |
| CALL | 8,778,120 | 0.0% |
| LOAD_ATTR | 7,435,269 | 0.0% |
| BINARY_OP | 5,392,084 | 0.0% |
| TO_BOOL | 1,186,133 | 0.0% |
| FOR_ITER | 976,320 | 0.0% |
| BINARY_SUBSCR | 476,183 | 0.0% |
| COMPARE_OP | 440,903 | 0.0% |
| STORE_ATTR | 65,762 | 0.0% |
| STORE_SUBSCR | 22,561 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,450 | 40.8% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,722 | 15.4% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| LOAD_GLOBAL_MODULE | 5,781 | 1.5% |
| COMPARE_OP_INT | 4,939 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,380 | 1.1% |
| RESUME_CHECK | 1 | 0.0% |
| RESUME | 1 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 8,962,399 | 31.9% |
| Calls to Python functions inlined | 19,155,157 | 68.1% |
| Calls via PyEval_EvalFrame (total) | 8,962,399 | 31.9% |
| Calls via PyEval_EvalFrame (vector) | 8,524,159 | 30.3% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,524,159 | 30.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 479,314 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 23,723,150 | 84.4% |
| Frame objects created | 36,064 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 15,112,492 | 42.9% |
| Frees to freelist | 15,113,926 |  |
| Allocations | 20,143,251 | 57.1% |
| Allocations to 512 bytes | 19,931,116 | 56.5% |
| Allocations to 4 kbytes | 86,355 | 0.2% |
| Allocations over 4 kbytes | 125,780 | 0.4% |
| Frees | 21,306,992 |  |
| New values | 65,280 |  |
| Interpreter increfs | 162,304,504 | 71.3% |
| Interpreter decrefs | 176,152,522 | 67.9% |
| Increfs | 65,388,057 | 28.7% |
| Decrefs | 83,323,870 | 32.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 9,221,132 |  |
| Method cache misses | 22,062 |  |
| Method cache collisions | 38,052 |  |
| Method cache dunder hits | 8,617,504 |  |
| Method cache dunder misses | 15,990 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 14 | 336 | 105,068 |
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
| Optimization attempts | 335,746 |  |
| Traces created | 206 | 0.1% |
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
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 60 | 29.1% |
| <= 32 | 40 | 19.4% |
| <= 64 | 40 | 19.4% |
| <= 128 | 66 | 32.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 60 | 29.1% |
| <= 32 | 80 | 38.8% |
| <= 64 | 8 | 3.9% |
| <= 128 | 58 | 28.2% |

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
| FOR_ITER_GEN | 279,520 |
| FOR_ITER | 56,020 |
| CALL | 78 |
| LOAD_ATTR_PROPERTY | 40 |
| YIELD_VALUE | 20 |
| CALL_PY_WITH_DEFAULTS | 20 |
| CALL_KW | 20 |
| BEFORE_WITH | 20 |


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
Stats gathered on: 2023-10-12
