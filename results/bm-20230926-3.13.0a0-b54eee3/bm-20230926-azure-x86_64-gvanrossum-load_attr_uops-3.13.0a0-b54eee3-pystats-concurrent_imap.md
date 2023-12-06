
# Pystats results

- benchmark: concurrent_imap
- fork: gvanrossum
- ref: load-attr-uops
- commit hash: b54eee3
- commit date: 2023-09-26T21:26:46-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 76,822,319 | 17.7% | 17.7% |  |
| RESUME_CHECK | 28,253,720 | 6.5% | 24.2% | 0.0% |
| STORE_FAST | 22,447,184 | 5.2% | 29.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,575,304 | 4.3% | 33.6% | 0.9% |
| POP_TOP | 18,262,190 | 4.2% | 37.8% |  |
| RETURN_VALUE | 16,817,162 | 3.9% | 41.7% |  |
| POP_JUMP_IF_FALSE | 14,698,221 | 3.4% | 45.1% |  |
| JUMP_BACKWARD | 13,567,169 | 3.1% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 13,021,700 | 3.0% | 51.2% | 0.0% |
| LOAD_FAST_LOAD_FAST | 11,993,278 | 2.8% | 53.9% |  |
| LOAD_CONST | 11,629,700 | 2.7% | 56.6% |  |
| CALL_PY_EXACT_ARGS | 9,581,328 | 2.2% | 58.8% |  |
| INTERPRETER_EXIT | 8,979,896 | 2.1% | 60.9% |  |
| CALL | 8,841,534 | 2.0% | 62.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,524,971 | 2.0% | 64.9% | 0.7% |
| LOAD_ATTR | 7,908,988 | 1.8% | 66.7% |  |
| NOP | 7,630,438 | 1.8% | 68.4% |  |
| FOR_ITER_LIST | 7,581,675 | 1.7% | 70.2% |  |
| RETURN_CONST | 7,059,652 | 1.6% | 71.8% |  |
| LOAD_GLOBAL_BUILTIN | 6,679,292 | 1.5% | 73.4% |  |
| PUSH_NULL | 5,550,028 | 1.3% | 74.6% |  |
| COPY | 5,499,848 | 1.3% | 75.9% |  |
| BINARY_OP | 5,451,729 | 1.3% | 77.1% |  |
| TO_BOOL_BOOL | 5,340,840 | 1.2% | 78.4% |  |
| YIELD_VALUE | 5,184,960 | 1.2% | 79.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,876,068 | 1.1% | 80.7% |  |
| STORE_FAST_LOAD_FAST | 4,847,040 | 1.1% | 81.8% |  |
| FOR_ITER_GEN | 4,760,640 | 1.1% | 82.9% |  |
| TO_BOOL_INT | 4,033,148 | 0.9% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,852,296 | 0.9% | 84.7% |  |
| STORE_FAST_STORE_FAST | 3,643,652 | 0.8% | 85.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,266,849 | 0.8% | 86.3% | 4.5% |
| BUILD_TUPLE | 3,252,082 | 0.7% | 87.1% |  |
| COMPARE_OP_INT | 2,848,522 | 0.7% | 87.7% | 0.2% |
| LOAD_ATTR_MODULE | 2,752,041 | 0.6% | 88.3% |  |
| CALL_PY_WITH_DEFAULTS | 2,245,792 | 0.5% | 88.9% |  |
| POP_JUMP_IF_TRUE | 2,055,375 | 0.5% | 89.3% |  |
| SWAP | 2,005,872 | 0.5% | 89.8% |  |
| GET_ITER | 1,824,966 | 0.4% | 90.2% |  |
| CALL_FUNCTION_EX | 1,810,147 | 0.4% | 90.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,628,612 | 0.4% | 91.0% |  |
| LOAD_DEREF | 1,414,443 | 0.3% | 91.3% |  |
| CALL_BUILTIN_FAST | 1,400,610 | 0.3% | 91.6% |  |
| BEFORE_WITH | 1,387,256 | 0.3% | 92.0% |  |
| COPY_FREE_VARS | 1,377,363 | 0.3% | 92.3% |  |
| CONTAINS_OP | 1,342,092 | 0.3% | 92.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,333,592 | 0.3% | 92.9% |  |
| LOAD_SUPER_ATTR_METHOD | 1,305,723 | 0.3% | 93.2% |  |
| UNARY_INVERT | 1,302,872 | 0.3% | 93.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,294,960 | 0.3% | 93.8% |  |
| JUMP_FORWARD | 1,286,611 | 0.3% | 94.1% |  |
| BUILD_MAP | 1,265,871 | 0.3% | 94.4% |  |
| TO_BOOL | 1,191,869 | 0.3% | 94.7% |  |
| BUILD_LIST | 1,169,609 | 0.3% | 94.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,129,433 | 0.3% | 95.2% |  |
| COMPARE_OP_STR | 1,118,028 | 0.3% | 95.4% |  |
| CALL_BUILTIN_CLASS | 986,188 | 0.2% | 95.7% |  |
| STORE_SUBSCR_DICT | 979,009 | 0.2% | 95.9% |  |
| FOR_ITER | 976,760 | 0.2% | 96.1% |  |
| CALL_ISINSTANCE | 923,052 | 0.2% | 96.3% |  |
| UNPACK_SEQUENCE_TUPLE | 876,993 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 852,513 | 0.2% | 96.7% |  |
| POP_JUMP_IF_NONE | 850,374 | 0.2% | 96.9% |  |
| BINARY_OP_ADD_INT | 834,236 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 812,382 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 812,382 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 796,491 | 0.2% | 97.7% | 1.1% |
| CALL_METHOD_DESCRIPTOR_O | 729,470 | 0.2% | 97.8% |  |
| LIST_APPEND | 633,764 | 0.1% | 98.0% |  |
| LOAD_FAST_CHECK | 628,788 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 591,677 | 0.1% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 587,217 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 479,405 | 0.1% | 98.5% |  |
| CALL_LEN | 476,182 | 0.1% | 98.6% |  |
| COMPARE_OP | 445,479 | 0.1% | 98.7% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.8% |  |
| DICT_MERGE | 422,880 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 421,551 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 376,394 | 0.1% | 99.1% |  |
| LIST_EXTEND | 368,714 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,852 | 0.1% | 99.3% |  |
| CALL_KW | 270,817 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 250,291 | 0.1% | 99.4% |  |
| UNARY_NOT | 215,964 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 205,030 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 196,874 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 184,481 | 0.0% | 99.6% |  |
| TO_BOOL_NONE | 180,319 | 0.0% | 99.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 106,221 | 0.0% | 99.6% | 4.1% |
| STORE_DEREF | 103,200 | 0.0% | 99.7% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,673 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,412 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,794 | 0.0% | 99.9% |  |
| DELETE_SUBSCR | 58,556 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 39,025 | 0.0% | 99.9% |  |
| POP_EXCEPT | 39,025 | 0.0% | 99.9% |  |
| IS_OP | 34,883 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 34,705 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 32,640 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 100.0% |  |
| IMPORT_NAME | 24,480 | 0.0% | 100.0% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,770 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 21,120 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 20,640 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 20,160 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 13,920 | 0.0% | 100.0% |  |
| BINARY_SLICE | 13,920 | 0.0% | 100.0% |  |
| RERAISE | 12,961 | 0.0% | 100.0% |  |
| END_FOR | 8,640 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,640 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,320 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 1,920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 803 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 204 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,781,000 | 3.9% | 3.9% |
| RESUME_CHECK LOAD_FAST | 15,817,180 | 3.6% | 7.5% |
| STORE_FAST LOAD_FAST | 9,815,609 | 2.3% | 9.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,546,768 | 2.2% | 12.0% |
| CACHE RESUME_CHECK | 8,896,858 | 2.0% | 14.0% |
| LOAD_FAST RETURN_VALUE | 8,138,401 | 1.9% | 15.9% |
| RETURN_VALUE INTERPRETER_EXIT | 7,872,431 | 1.8% | 17.7% |
| POP_TOP JUMP_BACKWARD | 6,559,096 | 1.5% | 19.2% |
| LOAD_FAST LOAD_ATTR | 6,148,307 | 1.4% | 20.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 6,132,800 | 1.4% | 22.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 6,004,529 | 1.4% | 23.4% |
| JUMP_BACKWARD FOR_ITER_LIST | 6,001,666 | 1.4% | 24.8% |
| POP_TOP LOAD_FAST | 5,749,403 | 1.3% | 26.1% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.2% | 27.3% |
| RETURN_CONST POP_TOP | 4,999,175 | 1.1% | 28.4% |
| NOP LOAD_FAST | 4,843,781 | 1.1% | 29.6% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.1% | 30.6% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.1% | 31.7% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.1% | 32.8% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 4,320,000 | 1.0% | 33.8% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.0% | 34.8% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 4,320,000 | 1.0% | 35.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,299,073 | 1.0% | 36.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,242,645 | 1.0% | 37.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 4,033,148 | 0.9% | 38.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,023,809 | 0.9% | 39.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,752,531 | 0.9% | 40.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,732,374 | 0.9% | 41.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,080,380 | 0.7% | 42.1% |
| LOAD_FAST LOAD_CONST | 3,012,830 | 0.7% | 42.8% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,926,666 | 0.7% | 43.4% |
| STORE_FAST NOP | 2,915,672 | 0.7% | 44.1% |
| LOAD_CONST LOAD_CONST | 2,854,732 | 0.7% | 44.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,846,205 | 0.7% | 45.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,820,153 | 0.6% | 46.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,800,488 | 0.6% | 46.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,799,015 | 0.6% | 47.4% |
| LOAD_FAST PUSH_NULL | 2,763,338 | 0.6% | 48.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,751,949 | 0.6% | 48.6% |
| LOAD_ATTR LOAD_FAST | 2,676,633 | 0.6% | 49.2% |
| PUSH_NULL LOAD_FAST | 2,624,504 | 0.6% | 49.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,617,605 | 0.6% | 50.4% |
| CALL STORE_FAST | 2,564,419 | 0.6% | 51.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,394,105 | 0.6% | 51.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,381,534 | 0.5% | 52.1% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,231,482 | 0.5% | 52.6% |
| COPY TO_BOOL_INT | 2,212,964 | 0.5% | 53.2% |
| BINARY_OP COPY | 2,212,964 | 0.5% | 53.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,052,541 | 0.5% | 54.1% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 54.6% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 55.0% |
| LOAD_CONST CALL | 1,970,319 | 0.5% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,930,284 | 0.4% | 55.9% |
| CALL RETURN_VALUE | 1,886,892 | 0.4% | 56.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,810,665 | 0.4% | 56.8% |
| RETURN_VALUE STORE_FAST | 1,757,333 | 0.4% | 57.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,731,054 | 0.4% | 57.6% |
| CALL POP_TOP | 1,710,855 | 0.4% | 58.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,682,844 | 0.4% | 58.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,649,957 | 0.4% | 58.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,623,332 | 0.4% | 59.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,569,649 | 0.4% | 59.5% |
| LOAD_CONST COMPARE_OP_INT | 1,562,784 | 0.4% | 59.8% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,538,370 | 0.4% | 60.2% |
| PUSH_NULL CALL | 1,535,434 | 0.4% | 60.6% |
| RETURN_VALUE RETURN_VALUE | 1,523,096 | 0.4% | 60.9% |
| LOAD_FAST_LOAD_FAST CALL | 1,464,553 | 0.3% | 61.2% |
| POP_TOP RETURN_CONST | 1,440,076 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,438,382 | 0.3% | 61.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,392,502 | 0.3% | 62.2% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,267 | 0.3% | 62.5% |
| NOP LOAD_GLOBAL_MODULE | 1,382,139 | 0.3% | 62.9% |
| COPY_FREE_VARS RESUME_CHECK | 1,377,363 | 0.3% | 63.2% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,372,923 | 0.3% | 63.5% |
| LOAD_DEREF LOAD_FAST | 1,372,923 | 0.3% | 63.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,366,632 | 0.3% | 64.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,342,092 | 0.3% | 64.4% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,342,088 | 0.3% | 64.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,335,700 | 0.3% | 65.0% |
| LOAD_FAST BUILD_TUPLE | 1,334,892 | 0.3% | 65.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,330,675 | 0.3% | 65.7% |
| POP_TOP LOAD_CONST | 1,312,096 | 0.3% | 66.0% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,305,723 | 0.3% | 66.3% |
| UNARY_INVERT BINARY_OP | 1,302,872 | 0.3% | 66.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,290,843 | 0.3% | 66.9% |
| FOR_ITER_LIST STORE_FAST | 1,288,886 | 0.3% | 67.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,214,348 | 0.3% | 67.4% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,208,780 | 0.3% | 67.7% |
| LOAD_CONST LOAD_FAST | 1,205,745 | 0.3% | 68.0% |
| GET_ITER FOR_ITER_LIST | 1,199,742 | 0.3% | 68.3% |
| POP_TOP NOP | 1,199,493 | 0.3% | 68.5% |
| LOAD_FAST GET_ITER | 1,164,449 | 0.3% | 68.8% |
| RETURN_VALUE POP_TOP | 1,157,987 | 0.3% | 69.1% |
| LOAD_FAST TO_BOOL | 1,150,975 | 0.3% | 69.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,144,203 | 0.3% | 69.6% |
| POP_JUMP_IF_FALSE POP_TOP | 1,141,510 | 0.3% | 69.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,117,375 | 0.3% | 70.1% |
| BINARY_OP STORE_FAST | 1,117,042 | 0.3% | 70.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,090,982 | 0.3% | 70.6% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,088,677 | 0.3% | 70.9% |


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
| RESUME_CHECK | 8,896,858 | 99.0% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 940,267 | 67.8% |
| RETURN_VALUE | 380,751 | 27.4% |
| LOAD_GLOBAL_MODULE | 61,918 | 4.5% |
| CALL | 4,320 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,185 | 72.2% |
| STORE_FAST | 385,071 | 27.8% |


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
| LOAD_FAST_LOAD_FAST | 432,000 | 90.1% |
| LOAD_CONST | 47,185 | 9.8% |
| BINARY_SUBSCR | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.1% |
| STORE_FAST | 47,185 | 9.8% |
| BINARY_SUBSCR | 220 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 30,864 | 88.9% |
| LOAD_ATTR_MODULE | 3,840 | 11.1% |
| LOAD_GLOBAL | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,705 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,318 | 48.4% |
| CALL | 20,638 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,599 | 16.4% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,598 | 77.9% |
| RETURN_CONST | 7,678 | 13.1% |
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
| RETURN_CONST | 812,382 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 812,382 | 100.0% |


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
| LOAD_FAST | 1,164,449 | 63.8% |
| STORE_FAST_LOAD_FAST | 432,000 | 23.7% |
| CALL_BUILTIN_CLASS | 208,357 | 11.4% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,199,742 | 65.7% |
| LOAD_FAST_AND_CLEAR | 390,827 | 21.4% |
| FOR_ITER_RANGE | 203,197 | 11.1% |
| FOR_ITER_TUPLE | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,872,431 | 87.7% |
| RETURN_CONST | 674,505 | 7.5% |
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
| STORE_FAST | 2,915,672 | 38.2% |
| POP_TOP | 1,199,493 | 15.7% |
| RESUME_CHECK | 1,061,292 | 13.9% |
| POP_JUMP_IF_FALSE | 1,017,516 | 13.3% |
| JUMP_BACKWARD | 816,000 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,843,781 | 63.5% |
| LOAD_GLOBAL_MODULE | 1,382,139 | 18.1% |
| LOAD_GLOBAL_BUILTIN | 561,998 | 7.4% |
| LOAD_FAST_LOAD_FAST | 437,280 | 5.7% |
| LOAD_CONST | 396,960 | 5.2% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 26,544 | 68.0% |
| COPY | 8,641 | 22.1% |
| POP_TOP | 3,840 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 26,544 | 68.0% |
| RERAISE | 8,641 | 22.1% |
| JUMP_FORWARD | 3,840 | 9.8% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,184,960 | 28.4% |
| RETURN_CONST | 4,999,175 | 27.4% |
| CALL | 1,710,855 | 9.4% |
| RETURN_VALUE | 1,157,987 | 6.3% |
| POP_JUMP_IF_FALSE | 1,141,510 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,559,096 | 35.9% |
| LOAD_FAST | 5,749,403 | 31.5% |
| RETURN_CONST | 1,440,076 | 7.9% |
| LOAD_CONST | 1,312,096 | 7.2% |
| NOP | 1,199,493 | 6.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 30,865 | 79.1% |
| RERAISE | 4,320 | 11.1% |
| CALL_KW | 3,840 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 30,864 | 79.1% |
| WITH_EXCEPT_START | 4,320 | 11.1% |
| LOAD_GLOBAL_MODULE | 3,840 | 9.8% |
| LOAD_GLOBAL | 1 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,763,338 | 49.8% |
| LOAD_ATTR_MODULE | 1,731,054 | 31.2% |
| LOAD_ATTR | 961,436 | 17.3% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,624,504 | 47.3% |
| CALL | 1,535,434 | 27.7% |
| LOAD_FAST_LOAD_FAST | 1,046,466 | 18.9% |
| LOAD_CONST | 240,352 | 4.3% |
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
| LOAD_FAST | 8,138,401 | 48.4% |
| CALL | 1,886,892 | 11.2% |
| RETURN_VALUE | 1,523,096 | 9.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,214,348 | 7.2% |
| CALL_FUNCTION_EX | 948,907 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,872,431 | 46.8% |
| STORE_FAST | 1,757,333 | 10.4% |
| RETURN_VALUE | 1,523,096 | 9.1% |
| POP_TOP | 1,157,987 | 6.9% |
| LOAD_FAST_LOAD_FAST | 910,092 | 5.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,690 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.3% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 6 | 0.0% |
| LOAD_FAST | 4 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,150,975 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,839 | 3.3% |
| TO_BOOL | 1,047 | 0.1% |
| RETURN_VALUE | 4 | 0.0% |
| LOAD_ATTR | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 637,034 | 53.4% |
| POP_JUMP_IF_FALSE | 553,783 | 46.5% |
| TO_BOOL | 1,047 | 0.1% |
| TO_BOOL_BOOL | 5 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 910,092 | 69.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 392,780 | 30.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,302,872 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 215,964 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 215,964 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,926,666 | 53.7% |
| UNARY_INVERT | 1,302,872 | 23.9% |
| POP_JUMP_IF_FALSE | 910,092 | 16.7% |
| LOAD_ATTR | 206,950 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,212,964 | 40.6% |
| STORE_FAST | 1,117,042 | 20.5% |
| UNARY_INVERT | 910,092 | 16.7% |
| TO_BOOL_INT | 910,092 | 16.7% |
| BUILD_TUPLE | 196,390 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 390,827 | 33.4% |
| JUMP_FORWARD | 380,751 | 32.6% |
| LOAD_FAST | 196,874 | 16.8% |
| POP_TOP | 183,877 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 393,231 | 33.6% |
| SWAP | 390,827 | 33.4% |
| STORE_FAST | 381,711 | 32.6% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 432,000 | 34.1% |
| LOAD_FAST | 396,960 | 31.4% |
| RESUME_CHECK | 388,431 | 30.7% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 820,911 | 64.8% |
| BUILD_TUPLE | 432,000 | 34.1% |
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
| LOAD_FAST | 1,334,892 | 41.0% |
| LOAD_FAST_LOAD_FAST | 870,240 | 26.8% |
| BUILD_MAP | 432,000 | 13.3% |
| RETURN_VALUE | 384,000 | 11.8% |
| BINARY_OP | 196,390 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 911,052 | 28.0% |
| YIELD_VALUE | 864,000 | 26.6% |
| BUILD_MAP | 432,000 | 13.3% |
| STORE_FAST | 384,000 | 11.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 11.8% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,970,319 | 22.3% |
| PUSH_NULL | 1,535,434 | 17.4% |
| LOAD_FAST_LOAD_FAST | 1,464,553 | 16.6% |
| LOAD_ATTR_METHOD_NO_DICT | 1,086,675 | 12.3% |
| BUILD_TUPLE | 911,052 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,564,419 | 29.0% |
| RETURN_VALUE | 1,886,892 | 21.3% |
| POP_TOP | 1,710,855 | 19.4% |
| LOAD_FAST | 797,105 | 9.0% |
| TO_BOOL_BOOL | 549,046 | 6.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,267 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,907 | 52.4% |
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
| LOAD_CONST | 270,817 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 218,917 | 80.8% |
| LOAD_FAST | 21,600 | 8.0% |
| RETURN_VALUE | 15,840 | 5.8% |
| STORE_FAST | 10,560 | 3.9% |
| PUSH_EXC_INFO | 3,840 | 1.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 444,485 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 596 | 0.1% |
| COMPARE_OP | 309 | 0.1% |
| COMPARE_OP_INT | 74 | 0.0% |
| LOAD_GLOBAL_MODULE | 9 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 445,041 | 99.9% |
| COMPARE_OP | 309 | 0.1% |
| COMPARE_OP_INT | 115 | 0.0% |
| COMPARE_OP_STR | 9 | 0.0% |
| POP_JUMP_IF_TRUE | 5 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,342,088 | 100.0% |
| LOAD_ATTR | 4 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,342,092 | 100.0% |


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
| BINARY_OP | 2,212,964 | 40.2% |
| STORE_FAST | 1,972,320 | 35.9% |
| LOAD_CONST | 825,600 | 15.0% |
| LOAD_FAST | 442,560 | 8.0% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,212,964 | 40.2% |
| STORE_FAST | 1,972,800 | 35.9% |
| STORE_FAST_STORE_FAST | 820,320 | 14.9% |
| LOAD_ATTR_INSTANCE_VALUE | 431,990 | 7.9% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 910,092 | 66.1% |
| CALL_ALLOC_AND_ENTER_INIT | 380,751 | 27.6% |
| CACHE | 82,080 | 6.0% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,377,363 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,794 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,196 | 66.7% |
| RETURN_CONST | 20,638 | 31.9% |
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
| LOAD_GLOBAL_MODULE | 1,283 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,883 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,559,096 | 48.3% |
| STORE_FAST | 4,320,000 | 31.8% |
| POP_JUMP_IF_NOT_NONE | 752,234 | 5.5% |
| LIST_APPEND | 633,764 | 4.7% |
| STORE_FAST_STORE_FAST | 436,320 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 6,001,666 | 44.2% |
| FOR_ITER_GEN | 4,752,000 | 35.0% |
| FOR_ITER | 952,800 | 7.0% |
| NOP | 816,000 | 6.0% |
| LOAD_GLOBAL_BUILTIN | 432,000 | 3.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 821,294 | 63.8% |
| POP_TOP | 451,877 | 35.1% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 847,158 | 65.8% |
| BUILD_LIST | 380,751 | 29.6% |
| POP_EXCEPT | 26,544 | 2.1% |
| LOAD_GLOBAL_MODULE | 18,718 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 352,894 | 55.7% |
| LOAD_ATTR | 196,390 | 31.0% |
| BINARY_SUBSCR_STR_INT | 84,480 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 633,764 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 184,837 | 50.1% |
| RETURN_VALUE | 183,877 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 184,357 | 50.0% |
| STORE_FAST | 183,877 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,148,307 | 77.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,366,632 | 17.3% |
| LOAD_GLOBAL_MODULE | 299,649 | 3.8% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,890 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,676,633 | 33.8% |
| PUSH_NULL | 961,436 | 12.2% |
| STORE_SUBSCR_DICT | 910,092 | 11.5% |
| POP_JUMP_IF_NOT_NONE | 877,945 | 11.1% |
| STORE_FAST | 563,217 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,012,830 | 25.9% |
| LOAD_CONST | 2,854,732 | 24.5% |
| POP_TOP | 1,312,096 | 11.3% |
| POP_JUMP_IF_FALSE | 693,037 | 6.0% |
| LOAD_ATTR_METHOD_NO_DICT | 555,285 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,854,732 | 24.5% |
| CALL | 1,970,319 | 16.9% |
| COMPARE_OP_INT | 1,562,784 | 13.4% |
| LOAD_FAST | 1,205,745 | 10.4% |
| COPY | 825,600 | 7.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,372,923 | 97.1% |
| STORE_DEREF | 20,640 | 1.5% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.5% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,372,923 | 97.1% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 2.9% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,817,180 | 20.6% |
| STORE_FAST | 9,815,609 | 12.8% |
| POP_JUMP_IF_FALSE | 6,004,529 | 7.8% |
| POP_TOP | 5,749,403 | 7.5% |
| NOP | 4,843,781 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,781,000 | 21.8% |
| RETURN_VALUE | 8,138,401 | 10.6% |
| LOAD_ATTR | 6,148,307 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,132,800 | 8.0% |
| CALL_PY_EXACT_ARGS | 4,023,809 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 390,827 | 66.6% |
| LOAD_FAST_AND_CLEAR | 196,390 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 390,827 | 66.6% |
| LOAD_FAST_AND_CLEAR | 196,390 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 68.7% |
| POP_JUMP_IF_NONE | 184,361 | 29.3% |
| LOAD_ATTR_CLASS | 12,427 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 68.7% |
| LOAD_GLOBAL_MODULE | 184,361 | 29.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,427 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,052,541 | 17.1% |
| LOAD_FAST_LOAD_FAST | 1,569,649 | 13.1% |
| POP_JUMP_IF_FALSE | 1,144,203 | 9.5% |
| PUSH_NULL | 1,046,466 | 8.7% |
| LOAD_SUPER_ATTR_METHOD | 920,652 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,800,488 | 23.4% |
| LOAD_FAST_LOAD_FAST | 1,569,649 | 13.1% |
| CALL | 1,464,553 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,330,675 | 11.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 910,092 | 7.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 39.2% |
| RESUME_CHECK | 40 | 19.6% |
| POP_JUMP_IF_FALSE | 40 | 19.6% |
| POP_JUMP_IF_TRUE | 21 | 10.3% |
| LOAD_ATTR_INSTANCE_VALUE | 9 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 101 | 49.5% |
| LOAD_ATTR | 49 | 24.0% |
| LOAD_GLOBAL_BUILTIN | 43 | 21.1% |
| COMPARE_OP | 5 | 2.5% |
| LOAD_FAST | 4 | 2.0% |


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
| TO_BOOL_INT | 4,033,148 | 27.4% |
| TO_BOOL_BOOL | 3,732,374 | 25.4% |
| COMPARE_OP_INT | 2,846,205 | 19.4% |
| CONTAINS_OP | 1,342,092 | 9.1% |
| COMPARE_OP_STR | 1,088,677 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,004,529 | 40.9% |
| RETURN_CONST | 2,394,105 | 16.3% |
| LOAD_FAST_LOAD_FAST | 1,144,203 | 7.8% |
| POP_TOP | 1,141,510 | 7.8% |
| LOAD_GLOBAL_MODULE | 1,117,375 | 7.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 805,734 | 94.8% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.7% |
| LOAD_ATTR | 21,120 | 2.5% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 224,077 | 26.4% |
| NOP | 212,197 | 25.0% |
| LOAD_FAST | 192,674 | 22.7% |
| LOAD_FAST_CHECK | 184,361 | 21.7% |
| RETURN_CONST | 18,240 | 2.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,810,665 | 47.0% |
| LOAD_ATTR | 877,945 | 22.8% |
| LOAD_ATTR_INSTANCE_VALUE | 754,172 | 19.6% |
| RETURN_VALUE | 353,374 | 9.2% |
| LOAD_DEREF | 41,280 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,538,370 | 39.9% |
| RETURN_CONST | 878,268 | 22.8% |
| JUMP_BACKWARD | 752,234 | 19.5% |
| NOP | 387,148 | 10.0% |
| LOAD_CONST | 183,877 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,392,502 | 67.7% |
| TO_BOOL | 637,034 | 31.0% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,231 | 0.4% |
| COMPARE_OP_INT | 2,243 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 714,631 | 34.8% |
| LOAD_FAST_LOAD_FAST | 639,910 | 31.1% |
| RETURN_CONST | 558,283 | 27.2% |
| LOAD_GLOBAL_MODULE | 56,287 | 2.7% |
| RETURN_VALUE | 47,185 | 2.3% |


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
| POP_EXCEPT | 8,641 | 66.7% |
| POP_JUMP_IF_TRUE | 4,320 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,321 | 50.0% |
| PUSH_EXC_INFO | 4,320 | 50.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,394,105 | 33.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,682,844 | 23.8% |
| POP_TOP | 1,440,076 | 20.4% |
| POP_JUMP_IF_NOT_NONE | 878,268 | 12.4% |
| POP_JUMP_IF_TRUE | 558,283 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,999,175 | 70.8% |
| EXIT_INIT_CHECK | 812,382 | 11.5% |
| INTERPRETER_EXIT | 674,505 | 9.6% |
| TO_BOOL_BOOL | 497,625 | 7.0% |
| STORE_FAST | 48,145 | 0.7% |


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
| SWAP | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_FAST | 8,644 | 13.0% |
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
| YIELD_VALUE | 4,752,000 | 21.2% |
| CALL | 2,564,419 | 11.4% |
| COPY | 1,972,800 | 8.8% |
| RETURN_VALUE | 1,757,333 | 7.8% |
| FOR_ITER_LIST | 1,288,886 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,815,609 | 43.7% |
| JUMP_BACKWARD | 4,320,000 | 19.2% |
| NOP | 2,915,672 | 13.0% |
| COPY | 1,972,320 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 916,571 | 4.1% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,623,332 | 44.6% |
| COPY | 820,320 | 22.5% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 22.4% |
| STORE_FAST_STORE_FAST | 384,000 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,208,780 | 33.2% |
| STORE_FAST | 816,000 | 22.4% |
| LOAD_FAST_LOAD_FAST | 787,032 | 21.6% |
| JUMP_BACKWARD | 436,320 | 12.0% |
| STORE_FAST_STORE_FAST | 384,000 | 10.5% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 431,996 | 21.5% |
| LOAD_FAST_AND_CLEAR | 390,827 | 19.5% |
| BUILD_LIST | 390,827 | 19.5% |
| FOR_ITER_LIST | 380,267 | 19.0% |
| LOAD_FAST | 205,001 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 431,990 | 21.5% |
| LOAD_CONST | 401,391 | 20.0% |
| STORE_FAST | 390,827 | 19.5% |
| BUILD_LIST | 390,827 | 19.5% |
| FOR_ITER_LIST | 380,267 | 19.0% |


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
| LOAD_FAST | 196,874 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 196,874 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 820,310 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 6 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 431,996 | 51.8% |
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
| CALL | 184,361 | 99.9% |
| LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 184,481 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,786 | 79.4% |
| LOAD_CONST | 47,185 | 18.9% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 245,971 | 98.3% |
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
| LOAD_FAST_LOAD_FAST | 367,754 | 97.7% |
| LOAD_CONST | 8,640 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 367,754 | 97.7% |
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
| LOAD_GLOBAL_MODULE | 401,391 | 49.4% |
| LOAD_FAST | 386,031 | 47.5% |
| CALL | 24,960 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 431,631 | 53.1% |
| COPY_FREE_VARS | 380,751 | 46.9% |


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
| RESUME_CHECK | 101,841 | 95.9% |
| POP_TOP | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 38.9% |
| LOAD_FAST | 210,394 | 21.3% |
| CALL_LEN | 183,877 | 18.6% |
| CALL_BUILTIN_CLASS | 183,877 | 18.6% |
| LOAD_CONST | 11,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 580,874 | 58.9% |
| GET_ITER | 208,357 | 21.1% |
| CALL_BUILTIN_CLASS | 183,877 | 18.6% |
| LOAD_FAST | 12,960 | 1.3% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 681,877 | 48.7% |
| LOAD_CONST | 485,834 | 34.7% |
| LOAD_FAST_LOAD_FAST | 129,666 | 9.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60,993 | 4.4% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 478,634 | 34.2% |
| STORE_FAST | 449,416 | 32.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 355,032 | 25.3% |
| UNPACK_SEQUENCE_TUPLE | 60,993 | 4.4% |
| POP_TOP | 10,935 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,800 | 45.6% |
| BUILD_TUPLE | 384,000 | 45.0% |
| CALL | 48,566 | 5.7% |
| LOAD_FAST_CHECK | 12,427 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 790,560 | 92.7% |
| RETURN_VALUE | 60,993 | 7.2% |
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
| LOAD_GLOBAL_BUILTIN | 923,052 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 923,052 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 455,539 | 95.7% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 4.3% |
| CALL | 3 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,306 | 54.2% |
| CALL_BUILTIN_CLASS | 183,877 | 38.6% |
| CALL_PY_EXACT_ARGS | 24,960 | 5.2% |
| LOAD_FAST | 4,320 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 196,390 | 95.8% |
| LOAD_FAST | 8,640 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 196,390 | 95.8% |
| LOAD_GLOBAL_MODULE | 8,640 | 4.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,290,843 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,151 | 0.2% |
| LOAD_CONST | 960 | 0.1% |
| CALL | 6 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 910,092 | 70.3% |
| STORE_FAST | 383,908 | 29.6% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,054,093 | 93.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,420 | 6.5% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 490,001 | 43.4% |
| STORE_FAST | 432,000 | 38.2% |
| LOAD_FAST | 63,840 | 5.7% |
| CALL_BUILTIN_FAST | 60,993 | 5.4% |
| RETURN_VALUE | 38,774 | 3.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 671,864 | 92.1% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,606 | 3.0% |
| RETURN_VALUE | 10,560 | 1.4% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 693,470 | 95.1% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.4% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,299,073 | 44.9% |
| LOAD_FAST | 4,023,809 | 42.0% |
| LOAD_FAST_LOAD_FAST | 626,437 | 6.5% |
| LOAD_SUPER_ATTR_METHOD | 380,751 | 4.0% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,546,768 | 99.6% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 929,535 | 41.4% |
| LOAD_ATTR_MODULE | 910,092 | 40.5% |
| LOAD_FAST | 258,790 | 11.5% |
| LOAD_CONST | 80,653 | 3.6% |
| BINARY_OP | 62,880 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,335,700 | 59.5% |
| COPY_FREE_VARS | 910,092 | 40.5% |


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
| LOAD_CONST | 1,562,784 | 54.9% |
| LOAD_ATTR_INSTANCE_VALUE | 821,620 | 28.8% |
| LOAD_FAST | 432,000 | 15.2% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,846,205 | 99.9% |
| POP_JUMP_IF_TRUE | 2,243 | 0.1% |
| COMPARE_OP | 74 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,069,059 | 95.6% |
| LOAD_CONST | 44,640 | 4.0% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 9 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,088,677 | 97.4% |
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
| JUMP_BACKWARD | 6,001,666 | 79.2% |
| GET_ITER | 1,199,742 | 15.8% |
| SWAP | 380,267 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,320,000 | 57.0% |
| STORE_FAST | 1,288,886 | 17.0% |
| LOAD_FAST | 761,502 | 10.0% |
| JUMP_BACKWARD | 432,000 | 5.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 392,780 | 5.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 388,480 | 65.7% |
| GET_ITER | 203,197 | 34.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 399,520 | 67.5% |
| LOAD_FAST | 183,997 | 31.1% |
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
| LOAD_GLOBAL_MODULE | 60,993 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,246 | 81.9% |
| LOAD_FAST_CHECK | 12,427 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,781,000 | 90.3% |
| LOAD_FAST_LOAD_FAST | 1,330,675 | 7.2% |
| COPY | 431,990 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 18,143 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,242,645 | 22.8% |
| LOAD_FAST | 2,820,153 | 15.2% |
| TO_BOOL_BOOL | 1,438,382 | 7.7% |
| LOAD_ATTR | 1,366,632 | 7.4% |
| CONTAINS_OP | 1,342,088 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,852 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 121,986 | 39.8% |
| CALL | 111,446 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,420 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,242,645 | 87.0% |
| LOAD_FAST | 485,571 | 10.0% |
| LOAD_ATTR | 62,892 | 1.3% |
| LOAD_ATTR_SLOT | 62,880 | 1.3% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,930,284 | 39.6% |
| CALL | 1,086,675 | 22.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,054,093 | 21.6% |
| LOAD_CONST | 555,285 | 11.4% |
| LOAD_FAST_LOAD_FAST | 228,131 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,132,800 | 71.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,016,829 | 11.9% |
| LOAD_FAST_LOAD_FAST | 910,092 | 10.7% |
| BINARY_SUBSCR | 432,000 | 5.1% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,299,073 | 50.4% |
| LOAD_FAST | 2,617,605 | 30.7% |
| CALL_PY_WITH_DEFAULTS | 929,535 | 10.9% |
| LOAD_FAST_LOAD_FAST | 508,800 | 6.0% |
| LOAD_CONST | 94,573 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,751,949 | 100.0% |
| LOAD_ATTR | 92 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,731,054 | 62.9% |
| CALL_PY_WITH_DEFAULTS | 910,092 | 33.1% |
| STORE_DEREF | 41,280 | 1.5% |
| LOAD_CONST | 26,400 | 1.0% |
| LOAD_FAST | 20,640 | 0.7% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 940,812 | 70.5% |
| LOAD_FAST_LOAD_FAST | 392,780 | 29.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 910,092 | 68.2% |
| UNARY_INVERT | 392,780 | 29.5% |
| RETURN_VALUE | 10,560 | 0.8% |
| LOAD_CONST | 10,560 | 0.8% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 774,731 | 97.3% |
| RETURN_VALUE | 20,640 | 2.6% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 787,371 | 98.9% |
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
| RESUME_CHECK | 2,799,015 | 41.9% |
| LOAD_FAST | 943,212 | 14.1% |
| STORE_FAST | 916,571 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 751,754 | 11.3% |
| NOP | 561,998 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,080,380 | 46.1% |
| LOAD_DEREF | 1,372,923 | 20.6% |
| CALL_ISINSTANCE | 923,052 | 13.8% |
| LOAD_GLOBAL_BUILTIN | 751,754 | 11.3% |
| LOAD_GLOBAL_MODULE | 468,960 | 7.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,752,531 | 28.8% |
| RESUME_CHECK | 2,381,534 | 18.3% |
| NOP | 1,382,139 | 10.6% |
| POP_JUMP_IF_FALSE | 1,117,375 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,090,982 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,926,666 | 22.5% |
| LOAD_ATTR_MODULE | 2,751,949 | 21.1% |
| LOAD_FAST_LOAD_FAST | 2,052,541 | 15.8% |
| LOAD_FAST | 1,649,957 | 12.7% |
| COMPARE_OP_STR | 1,069,059 | 8.2% |


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
| LOAD_FAST | 1,305,723 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 920,652 | 70.5% |
| CALL_PY_EXACT_ARGS | 380,751 | 29.2% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 9,546,768 | 33.8% |
| CACHE | 8,896,858 | 31.5% |
| FOR_ITER_GEN | 4,752,000 | 16.8% |
| COPY_FREE_VARS | 1,377,363 | 4.9% |
| CALL_PY_WITH_DEFAULTS | 1,335,700 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,817,180 | 56.0% |
| POP_TOP | 5,184,960 | 18.4% |
| LOAD_GLOBAL_BUILTIN | 2,799,015 | 9.9% |
| LOAD_GLOBAL_MODULE | 2,381,534 | 8.4% |
| NOP | 1,061,292 | 3.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,231,482 | 68.3% |
| LOAD_FAST_LOAD_FAST | 577,071 | 17.7% |
| SWAP | 431,990 | 13.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,682,844 | 51.5% |
| LOAD_FAST | 684,956 | 21.0% |
| LOAD_GLOBAL_MODULE | 540,111 | 16.5% |
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
| LOAD_ATTR | 910,092 | 93.0% |
| LOAD_FAST | 34,351 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.6% |
| CALL | 7,680 | 0.8% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 913,249 | 93.3% |
| RETURN_CONST | 24,480 | 2.5% |
| LOAD_GLOBAL_MODULE | 20,640 | 2.1% |
| LOAD_CONST | 20,640 | 2.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,438,382 | 26.9% |
| CALL_ISINSTANCE | 923,052 | 17.3% |
| RETURN_VALUE | 695,251 | 13.0% |
| CALL | 549,046 | 10.3% |
| LOAD_FAST | 541,585 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,732,374 | 69.9% |
| POP_JUMP_IF_TRUE | 1,392,502 | 26.1% |
| UNARY_NOT | 215,964 | 4.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,212,964 | 54.9% |
| LOAD_FAST | 910,092 | 22.6% |
| BINARY_OP | 910,092 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,033,148 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 389,391 | 92.4% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 421,551 | 100.0% |


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
| CALL_BUILTIN_FAST | 60,993 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 60,993 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 436,320 | 26.8% |
| LOAD_FAST_CHECK | 432,000 | 26.5% |
| FOR_ITER_LIST | 392,780 | 24.1% |
| CALL_BUILTIN_FAST | 355,032 | 21.8% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,623,332 | 99.7% |
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
| STORE_FAST | 480 | 59.8% |
| COPY | 323 | 40.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 59.8% |
| POP_JUMP_IF_FALSE | 323 | 40.2% |


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
| specialization.deferred |       479185 | 45.4% |
|          hit |       575114 | 54.5% |

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
| specialization.deferred |        22564 | 2.3% |
|          hit |       979009 | 97.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 6 | 2.9% |
| Failure | 200 | 97.1% |

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
| specialization.deferred |      1190817 | 10.7% |
|          hit |      9976661 | 89.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5 | 0.5% |
| Failure | 1,047 | 99.5% |

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
| specialization.deferred |      5449625 | 77.6% |
|          hit |      1572922 | 22.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 46 | 2.2% |
| Failure | 2,058 | 97.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,029 | 50.0% |
| or | 599 | 29.1% |
| remainder | 230 | 11.2% |
| add different types | 160 | 7.8% |
| add other | 40 | 1.9% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8832442 | 29.2% |
| specialization.deopt |           60 | 0.0% |
|          hit |     21415182 | 70.8% |
|         miss |         4380 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 126 | 1.4% |
| Failure | 9,026 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,524 | 28.0% |
| cfunc noargs | 1,795 | 19.9% |
| class no vectorcall | 1,269 | 14.1% |
| meth descr varargs keywords | 838 | 9.3% |
| class mutable | 416 | 4.6% |
| other | 360 | 4.0% |
| cfunc varargs keywords | 336 | 3.7% |
| cfunc varargs | 320 | 3.5% |
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
| specialization.deferred |       445046 | 10.1% |
| specialization.deopt |           74 | 0.0% |
|          hit |      3961704 | 89.8% |
|         miss |         4846 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 124 | 24.5% |
| Failure | 383 | 75.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 159 | 41.5% |
| different types | 144 | 37.6% |
| big int | 80 | 20.9% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       976320 | 7.0% |
|          hit |     12954152 | 93.0% |

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
| specialization.deferred |      7902826 | 17.5% |
| specialization.deopt |         4188 | 0.0% |
|          hit |     37077262 | 82.0% |
|         miss |       230170 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,350 | 42.0% |
| Failure | 6,000 | 58.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,406 | 23.4% |
| not managed dict | 1,222 | 20.4% |
| shadowed | 1,206 | 20.1% |
| non overriding descriptor | 600 | 10.0% |
| class attr descriptor | 360 | 6.0% |
| metaclass attribute | 280 | 4.7% |
| class method obj | 280 | 4.7% |
| has managed dict | 240 | 4.0% |
| non object slot | 160 | 2.7% |
| class attr simple | 126 | 2.1% |
| mutable class | 80 | 1.3% |
| overridden | 40 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 0.0% |
| specialization.deopt |           53 | 0.0% |
|          hit |     19695667 | 100.0% |
|         miss |         5325 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 197 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1372923 | 100.0% |


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
| specialization.deferred |        65766 | 1.9% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      3192169 | 93.7% |
|         miss |       148120 | 4.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,786 | 81.3% |
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
|          hit |      2505605 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 230,484,126 | 53.0% |
| Not specialized | 60,815,347 | 14.0% |
| Specialized | 143,430,248 | 33.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 18,446,744,073,709,551,615 | 100.0% |
| CALL | 8,832,442 | 0.0% |
| LOAD_ATTR | 7,902,826 | 0.0% |
| BINARY_OP | 5,449,625 | 0.0% |
| TO_BOOL | 1,190,817 | 0.0% |
| FOR_ITER | 976,320 | 0.0% |
| BINARY_SUBSCR | 479,185 | 0.0% |
| COMPARE_OP | 445,046 | 0.0% |
| STORE_ATTR | 65,766 | 0.0% |
| STORE_SUBSCR | 22,564 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,388 | 40.8% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,662 | 15.4% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| LOAD_GLOBAL_MODULE | 5,325 | 1.4% |
| COMPARE_OP_INT | 4,846 | 1.2% |
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
| Calls to PyEval_EvalDefault | 8,984,218 | 31.8% |
| Calls to Python functions inlined | 19,283,422 | 68.2% |
| Calls via PyEval_EvalFrame (total) | 8,984,218 | 31.8% |
| Calls via PyEval_EvalFrame (vector) | 8,545,978 | 30.2% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,545,978 | 30.2% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 483,290 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 23,881,142 | 84.5% |
| Frame objects created | 39,076 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 15,203,574 | 42.9% |
| Frees to freelist | 15,205,222 |  |
| Allocations | 20,230,763 | 57.1% |
| Allocations to 512 bytes | 20,018,842 | 56.5% |
| Allocations to 4 kbytes | 86,136 | 0.2% |
| Allocations over 4 kbytes | 125,785 | 0.4% |
| Frees | 21,403,934 |  |
| New values | 65,280 |  |
| Interpreter increfs | 170,387,068 | 77.0% |
| Interpreter decrefs | 186,687,355 | 73.7% |
| Increfs | 50,843,062 | 23.0% |
| Decrefs | 66,483,989 | 26.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 9,305,279 |  |
| Method cache misses | 13,212 |  |
| Method cache collisions | 28,264 |  |
| Method cache dunder hits | 8,654,150 |  |
| Method cache dunder misses | 15,052 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 18 | 432 | 132,724 |
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
