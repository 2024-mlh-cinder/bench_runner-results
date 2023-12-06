
# Pystats results

- benchmark: concurrent_imap
- fork: python
- ref: main
- commit hash: 8e56d55
- commit date: 2023-10-07T17:07:36-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 76,633,838 | 17.7% | 17.7% |  |
| RESUME_CHECK | 28,202,728 | 6.5% | 24.2% |  |
| STORE_FAST | 22,405,943 | 5.2% | 29.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,536,181 | 4.3% | 33.6% | 0.9% |
| POP_TOP | 18,226,550 | 4.2% | 37.8% |  |
| RETURN_VALUE | 16,781,861 | 3.9% | 41.7% |  |
| POP_JUMP_IF_FALSE | 14,657,251 | 3.4% | 45.1% |  |
| JUMP_BACKWARD | 13,558,070 | 3.1% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 12,984,837 | 3.0% | 51.2% | 0.0% |
| LOAD_FAST_LOAD_FAST | 11,963,654 | 2.8% | 53.9% |  |
| LOAD_CONST | 11,609,861 | 2.7% | 56.6% |  |
| CALL_PY_EXACT_ARGS | 9,549,807 | 2.2% | 58.8% |  |
| INTERPRETER_EXIT | 8,972,481 | 2.1% | 60.9% |  |
| CALL | 8,823,124 | 2.0% | 62.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,499,510 | 2.0% | 64.9% | 0.7% |
| LOAD_ATTR | 7,887,612 | 1.8% | 66.7% |  |
| NOP | 7,610,786 | 1.8% | 68.4% |  |
| FOR_ITER_LIST | 7,571,694 | 1.7% | 70.2% |  |
| RETURN_CONST | 7,041,341 | 1.6% | 71.8% |  |
| LOAD_GLOBAL_BUILTIN | 6,660,754 | 1.5% | 73.3% |  |
| PUSH_NULL | 5,546,793 | 1.3% | 74.6% |  |
| COPY | 5,491,719 | 1.3% | 75.9% |  |
| BINARY_OP | 5,432,054 | 1.3% | 77.1% |  |
| TO_BOOL_BOOL | 5,326,690 | 1.2% | 78.4% |  |
| YIELD_VALUE | 5,184,960 | 1.2% | 79.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,860,313 | 1.1% | 80.7% |  |
| STORE_FAST_LOAD_FAST | 4,847,040 | 1.1% | 81.8% |  |
| FOR_ITER_GEN | 4,760,640 | 1.1% | 82.9% |  |
| TO_BOOL_INT | 4,018,180 | 0.9% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,843,287 | 0.9% | 84.7% |  |
| STORE_FAST_STORE_FAST | 3,640,961 | 0.8% | 85.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,260,290 | 0.8% | 86.3% | 4.5% |
| BUILD_TUPLE | 3,248,016 | 0.7% | 87.1% |  |
| COMPARE_OP_INT | 2,841,925 | 0.7% | 87.7% | 0.2% |
| LOAD_ATTR_MODULE | 2,745,994 | 0.6% | 88.3% |  |
| CALL_PY_WITH_DEFAULTS | 2,240,397 | 0.5% | 88.9% |  |
| POP_JUMP_IF_TRUE | 2,051,673 | 0.5% | 89.3% |  |
| SWAP | 2,000,621 | 0.5% | 89.8% |  |
| GET_ITER | 1,820,364 | 0.4% | 90.2% |  |
| CALL_FUNCTION_EX | 1,810,161 | 0.4% | 90.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,625,921 | 0.4% | 91.0% |  |
| LOAD_DEREF | 1,409,713 | 0.3% | 91.3% |  |
| CALL_BUILTIN_FAST | 1,397,293 | 0.3% | 91.7% |  |
| BEFORE_WITH | 1,385,959 | 0.3% | 92.0% |  |
| COPY_FREE_VARS | 1,372,633 | 0.3% | 92.3% |  |
| CONTAINS_OP | 1,338,674 | 0.3% | 92.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,328,878 | 0.3% | 92.9% |  |
| LOAD_SUPER_ATTR_METHOD | 1,300,993 | 0.3% | 93.2% |  |
| UNARY_INVERT | 1,298,158 | 0.3% | 93.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,290,268 | 0.3% | 93.8% |  |
| JUMP_FORWARD | 1,281,826 | 0.3% | 94.1% |  |
| BUILD_MAP | 1,264,559 | 0.3% | 94.4% |  |
| TO_BOOL | 1,190,165 | 0.3% | 94.7% |  |
| BUILD_LIST | 1,165,672 | 0.3% | 94.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,125,118 | 0.3% | 95.2% |  |
| COMPARE_OP_STR | 1,117,372 | 0.3% | 95.4% |  |
| CALL_BUILTIN_CLASS | 984,211 | 0.2% | 95.7% |  |
| FOR_ITER | 976,760 | 0.2% | 95.9% |  |
| STORE_SUBSCR_DICT | 975,629 | 0.2% | 96.1% |  |
| CALL_ISINSTANCE | 919,634 | 0.2% | 96.3% |  |
| UNPACK_SEQUENCE_TUPLE | 877,010 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 852,530 | 0.2% | 96.7% |  |
| POP_JUMP_IF_NONE | 848,439 | 0.2% | 96.9% |  |
| BINARY_OP_ADD_INT | 834,235 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 809,758 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 809,758 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 793,761 | 0.2% | 97.7% | 1.1% |
| CALL_METHOD_DESCRIPTOR_O | 727,472 | 0.2% | 97.8% |  |
| LIST_APPEND | 631,712 | 0.1% | 98.0% |  |
| LOAD_FAST_CHECK | 628,138 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 589,685 | 0.1% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 585,256 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 478,390 | 0.1% | 98.5% |  |
| CALL_LEN | 475,545 | 0.1% | 98.6% |  |
| COMPARE_OP | 444,013 | 0.1% | 98.7% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.8% |  |
| DICT_MERGE | 422,880 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 420,239 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 375,064 | 0.1% | 99.1% |  |
| LIST_EXTEND | 367,384 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,920 | 0.1% | 99.3% |  |
| CALL_KW | 270,136 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 249,309 | 0.1% | 99.4% |  |
| UNARY_NOT | 215,387 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 204,382 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 196,227 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 183,817 | 0.0% | 99.6% |  |
| TO_BOOL_NONE | 180,325 | 0.0% | 99.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 106,228 | 0.0% | 99.6% | 4.1% |
| STORE_DEREF | 103,200 | 0.0% | 99.7% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,690 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,410 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,797 | 0.0% | 99.9% |  |
| DELETE_SUBSCR | 58,558 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 38,009 | 0.0% | 99.9% |  |
| POP_EXCEPT | 38,009 | 0.0% | 99.9% |  |
| IS_OP | 34,887 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 33,689 | 0.0% | 99.9% |  |
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
| RERAISE | 12,960 | 0.0% | 100.0% |  |
| END_FOR | 8,640 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,640 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,320 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,320 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 1,920 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 960 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 807 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 184 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,746,658 | 3.9% | 3.9% |
| RESUME_CHECK LOAD_FAST | 15,787,709 | 3.6% | 7.5% |
| STORE_FAST LOAD_FAST | 9,793,406 | 2.3% | 9.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,515,247 | 2.2% | 12.0% |
| CACHE RESUME_CHECK | 8,889,442 | 2.0% | 14.0% |
| LOAD_FAST RETURN_VALUE | 8,124,892 | 1.9% | 15.9% |
| RETURN_VALUE INTERPRETER_EXIT | 7,866,325 | 1.8% | 17.7% |
| POP_TOP JUMP_BACKWARD | 6,555,674 | 1.5% | 19.2% |
| LOAD_FAST LOAD_ATTR | 6,128,887 | 1.4% | 20.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 6,113,117 | 1.4% | 22.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 5,995,622 | 1.4% | 23.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,988,631 | 1.4% | 24.8% |
| POP_TOP LOAD_FAST | 5,729,275 | 1.3% | 26.1% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.2% | 27.3% |
| RETURN_CONST POP_TOP | 4,986,795 | 1.1% | 28.4% |
| NOP LOAD_FAST | 4,830,951 | 1.1% | 29.6% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.1% | 30.7% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.1% | 31.8% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.1% | 32.8% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 4,320,000 | 1.0% | 33.8% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.0% | 34.8% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 4,320,000 | 1.0% | 35.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,285,724 | 1.0% | 36.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,231,537 | 1.0% | 37.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 4,018,180 | 0.9% | 38.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,007,605 | 0.9% | 39.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,738,863 | 0.9% | 40.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,721,862 | 0.9% | 41.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,072,334 | 0.7% | 42.1% |
| LOAD_FAST LOAD_CONST | 3,003,846 | 0.7% | 42.8% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,915,764 | 0.7% | 43.4% |
| STORE_FAST NOP | 2,907,247 | 0.7% | 44.1% |
| LOAD_CONST LOAD_CONST | 2,852,122 | 0.7% | 44.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,839,606 | 0.7% | 45.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,814,369 | 0.6% | 46.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,791,674 | 0.6% | 46.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,790,867 | 0.6% | 47.4% |
| LOAD_FAST PUSH_NULL | 2,762,729 | 0.6% | 48.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,745,905 | 0.6% | 48.6% |
| LOAD_ATTR LOAD_FAST | 2,667,804 | 0.6% | 49.2% |
| PUSH_NULL LOAD_FAST | 2,622,480 | 0.6% | 49.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,606,817 | 0.6% | 50.4% |
| CALL STORE_FAST | 2,558,009 | 0.6% | 51.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,388,234 | 0.6% | 51.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,374,868 | 0.5% | 52.1% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,226,236 | 0.5% | 52.7% |
| COPY TO_BOOL_INT | 2,204,832 | 0.5% | 53.2% |
| BINARY_OP COPY | 2,204,832 | 0.5% | 53.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,045,040 | 0.5% | 54.1% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 54.6% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 55.0% |
| LOAD_CONST CALL | 1,967,967 | 0.5% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,923,560 | 0.4% | 55.9% |
| CALL RETURN_VALUE | 1,883,474 | 0.4% | 56.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,808,421 | 0.4% | 56.8% |
| RETURN_VALUE STORE_FAST | 1,752,008 | 0.4% | 57.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,728,420 | 0.4% | 57.6% |
| CALL POP_TOP | 1,706,511 | 0.4% | 58.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,677,596 | 0.4% | 58.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,644,580 | 0.4% | 58.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,620,641 | 0.4% | 59.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,565,566 | 0.4% | 59.5% |
| LOAD_CONST COMPARE_OP_INT | 1,558,465 | 0.4% | 59.9% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,535,311 | 0.4% | 60.2% |
| PUSH_NULL CALL | 1,534,159 | 0.4% | 60.6% |
| RETURN_VALUE RETURN_VALUE | 1,517,648 | 0.3% | 60.9% |
| LOAD_FAST_LOAD_FAST CALL | 1,461,218 | 0.3% | 61.2% |
| POP_TOP RETURN_CONST | 1,436,752 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,433,770 | 0.3% | 61.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,389,441 | 0.3% | 62.2% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,281 | 0.3% | 62.5% |
| NOP LOAD_GLOBAL_MODULE | 1,377,331 | 0.3% | 62.9% |
| COPY_FREE_VARS RESUME_CHECK | 1,372,633 | 0.3% | 63.2% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,368,193 | 0.3% | 63.5% |
| LOAD_DEREF LOAD_FAST | 1,368,193 | 0.3% | 63.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,365,331 | 0.3% | 64.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,338,674 | 0.3% | 64.4% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,338,669 | 0.3% | 64.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,333,723 | 0.3% | 65.1% |
| LOAD_FAST BUILD_TUPLE | 1,331,474 | 0.3% | 65.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,325,901 | 0.3% | 65.7% |
| POP_TOP LOAD_CONST | 1,309,768 | 0.3% | 66.0% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,300,993 | 0.3% | 66.3% |
| UNARY_INVERT BINARY_OP | 1,298,158 | 0.3% | 66.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,286,113 | 0.3% | 66.9% |
| FOR_ITER_LIST STORE_FAST | 1,284,138 | 0.3% | 67.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,210,218 | 0.3% | 67.4% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,207,484 | 0.3% | 67.7% |
| LOAD_CONST LOAD_FAST | 1,204,455 | 0.3% | 68.0% |
| GET_ITER FOR_ITER_LIST | 1,197,118 | 0.3% | 68.3% |
| POP_TOP NOP | 1,195,669 | 0.3% | 68.5% |
| LOAD_FAST GET_ITER | 1,160,512 | 0.3% | 68.8% |
| RETURN_VALUE POP_TOP | 1,152,905 | 0.3% | 69.1% |
| LOAD_FAST TO_BOOL | 1,149,271 | 0.3% | 69.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,140,176 | 0.3% | 69.6% |
| POP_JUMP_IF_FALSE POP_TOP | 1,136,432 | 0.3% | 69.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,113,949 | 0.3% | 70.1% |
| BINARY_OP STORE_FAST | 1,112,976 | 0.3% | 70.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,090,331 | 0.3% | 70.6% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,088,012 | 0.3% | 70.9% |


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
| RESUME_CHECK | 8,889,442 | 99.0% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 940,281 | 67.8% |
| RETURN_VALUE | 379,439 | 27.4% |
| LOAD_GLOBAL_MODULE | 61,919 | 4.5% |
| CALL | 4,320 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,200 | 72.3% |
| STORE_FAST | 383,759 | 27.7% |


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
| LOAD_FAST_LOAD_FAST | 432,000 | 90.3% |
| LOAD_CONST | 46,169 | 9.7% |
| BINARY_SUBSCR | 221 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.3% |
| STORE_FAST | 46,169 | 9.7% |
| BINARY_SUBSCR | 221 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 29,849 | 88.6% |
| LOAD_ATTR_MODULE | 3,840 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,689 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,319 | 48.4% |
| CALL | 20,639 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,600 | 16.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,599 | 77.9% |
| RETURN_CONST | 7,679 | 13.1% |
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
| RETURN_CONST | 809,758 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 809,758 | 100.0% |


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
| LOAD_FAST | 1,160,512 | 63.8% |
| STORE_FAST_LOAD_FAST | 432,000 | 23.7% |
| CALL_BUILTIN_CLASS | 207,692 | 11.4% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,197,118 | 65.8% |
| LOAD_FAST_AND_CLEAR | 389,514 | 21.4% |
| FOR_ITER_RANGE | 202,532 | 11.1% |
| FOR_ITER_TUPLE | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,866,325 | 87.7% |
| RETURN_CONST | 673,196 | 7.5% |
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
| STORE_FAST | 2,907,247 | 38.2% |
| POP_TOP | 1,195,669 | 15.7% |
| RESUME_CHECK | 1,057,874 | 13.9% |
| POP_JUMP_IF_FALSE | 1,015,503 | 13.3% |
| JUMP_BACKWARD | 816,000 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,830,951 | 63.5% |
| LOAD_GLOBAL_MODULE | 1,377,331 | 18.1% |
| LOAD_GLOBAL_BUILTIN | 559,984 | 7.4% |
| LOAD_FAST_LOAD_FAST | 437,280 | 5.7% |
| LOAD_CONST | 396,960 | 5.2% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 25,529 | 67.2% |
| COPY | 8,640 | 22.7% |
| POP_TOP | 3,840 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 25,529 | 67.2% |
| RERAISE | 8,640 | 22.7% |
| JUMP_FORWARD | 3,840 | 10.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,184,960 | 28.4% |
| RETURN_CONST | 4,986,795 | 27.4% |
| CALL | 1,706,511 | 9.4% |
| RETURN_VALUE | 1,152,905 | 6.3% |
| POP_JUMP_IF_FALSE | 1,136,432 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,555,674 | 36.0% |
| LOAD_FAST | 5,729,275 | 31.4% |
| RETURN_CONST | 1,436,752 | 7.9% |
| LOAD_CONST | 1,309,768 | 7.2% |
| NOP | 1,195,669 | 6.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,849 | 78.5% |
| RERAISE | 4,320 | 11.4% |
| CALL_KW | 3,840 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 29,849 | 78.5% |
| WITH_EXCEPT_START | 4,320 | 11.4% |
| LOAD_GLOBAL_MODULE | 3,840 | 10.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,762,729 | 49.8% |
| LOAD_ATTR_MODULE | 1,728,420 | 31.2% |
| LOAD_ATTR | 961,444 | 17.3% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,622,480 | 47.3% |
| CALL | 1,534,159 | 27.7% |
| LOAD_FAST_LOAD_FAST | 1,046,500 | 18.9% |
| LOAD_CONST | 240,375 | 4.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 48,559 | 0.9% |


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
| LOAD_FAST | 8,124,892 | 48.4% |
| CALL | 1,883,474 | 11.2% |
| RETURN_VALUE | 1,517,648 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,210,218 | 7.2% |
| CALL_FUNCTION_EX | 948,921 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,866,325 | 46.9% |
| STORE_FAST | 1,752,008 | 10.4% |
| RETURN_VALUE | 1,517,648 | 9.0% |
| POP_TOP | 1,152,905 | 6.9% |
| LOAD_FAST_LOAD_FAST | 906,674 | 5.4% |


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
| STORE_SUBSCR_DICT | 5 | 0.0% |
| LOAD_FAST | 5 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,149,271 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,839 | 3.3% |
| TO_BOOL | 1,048 | 0.1% |
| RETURN_VALUE | 5 | 0.0% |
| LOAD_ATTR | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 636,384 | 53.5% |
| POP_JUMP_IF_FALSE | 552,731 | 46.4% |
| TO_BOOL | 1,048 | 0.1% |
| TO_BOOL_BOOL | 2 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 906,674 | 69.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 391,484 | 30.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,298,158 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 215,387 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 215,387 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,915,764 | 53.7% |
| UNARY_INVERT | 1,298,158 | 23.9% |
| POP_JUMP_IF_FALSE | 906,674 | 16.7% |
| LOAD_ATTR | 206,302 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,204,832 | 40.6% |
| STORE_FAST | 1,112,976 | 20.5% |
| UNARY_INVERT | 906,674 | 16.7% |
| TO_BOOL_INT | 906,674 | 16.7% |
| BUILD_TUPLE | 195,742 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 389,514 | 33.4% |
| JUMP_FORWARD | 379,439 | 32.6% |
| LOAD_FAST | 196,227 | 16.8% |
| POP_TOP | 183,212 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 391,919 | 33.6% |
| SWAP | 389,514 | 33.4% |
| STORE_FAST | 380,399 | 32.6% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 432,000 | 34.2% |
| LOAD_FAST | 396,960 | 31.4% |
| RESUME_CHECK | 387,119 | 30.6% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.0% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 819,599 | 64.8% |
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
| LOAD_FAST | 1,331,474 | 41.0% |
| LOAD_FAST_LOAD_FAST | 870,240 | 26.8% |
| BUILD_MAP | 432,000 | 13.3% |
| RETURN_VALUE | 384,000 | 11.8% |
| BINARY_OP | 195,742 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 907,634 | 27.9% |
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
| LOAD_CONST | 1,967,967 | 22.3% |
| PUSH_NULL | 1,534,159 | 17.4% |
| LOAD_FAST_LOAD_FAST | 1,461,218 | 16.6% |
| LOAD_ATTR_METHOD_NO_DICT | 1,083,627 | 12.3% |
| BUILD_TUPLE | 907,634 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,558,009 | 29.0% |
| RETURN_VALUE | 1,883,474 | 21.3% |
| POP_TOP | 1,706,511 | 19.3% |
| LOAD_FAST | 795,146 | 9.0% |
| TO_BOOL_BOOL | 548,073 | 6.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,281 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,921 | 52.4% |
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
| LOAD_CONST | 270,136 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 218,252 | 80.8% |
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
| LOAD_CONST | 443,174 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 467 | 0.1% |
| COMPARE_OP | 291 | 0.1% |
| COMPARE_OP_INT | 72 | 0.0% |
| LOAD_GLOBAL_MODULE | 8 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 443,599 | 99.9% |
| COMPARE_OP | 291 | 0.1% |
| COMPARE_OP_INT | 114 | 0.0% |
| COMPARE_OP_STR | 8 | 0.0% |
| POP_JUMP_IF_TRUE | 1 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,338,669 | 100.0% |
| LOAD_ATTR | 5 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,338,674 | 100.0% |


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
| BINARY_OP | 2,204,832 | 40.1% |
| STORE_FAST | 1,972,320 | 35.9% |
| LOAD_CONST | 825,600 | 15.0% |
| LOAD_FAST | 442,560 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,204,832 | 40.1% |
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
| CALL_PY_WITH_DEFAULTS | 906,674 | 66.1% |
| CALL_ALLOC_AND_ENTER_INIT | 379,439 | 27.6% |
| CACHE | 82,080 | 6.0% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,372,633 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,797 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,198 | 66.7% |
| RETURN_CONST | 20,639 | 31.9% |
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
| LOAD_GLOBAL_MODULE | 1,287 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,887 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,555,674 | 48.4% |
| STORE_FAST | 4,320,000 | 31.9% |
| POP_JUMP_IF_NOT_NONE | 750,904 | 5.5% |
| LIST_APPEND | 631,712 | 4.7% |
| STORE_FAST_STORE_FAST | 436,320 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,995,622 | 44.2% |
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
| STORE_FAST | 816,547 | 63.7% |
| POP_TOP | 451,839 | 35.2% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 844,699 | 65.9% |
| BUILD_LIST | 379,439 | 29.6% |
| POP_EXCEPT | 25,529 | 2.0% |
| LOAD_GLOBAL_MODULE | 18,719 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 351,490 | 55.6% |
| LOAD_ATTR | 195,742 | 31.0% |
| BINARY_SUBSCR_STR_INT | 84,480 | 13.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 631,712 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 184,172 | 50.1% |
| RETURN_VALUE | 183,212 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 183,692 | 50.0% |
| STORE_FAST | 183,212 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,128,887 | 77.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,365,331 | 17.3% |
| LOAD_GLOBAL_MODULE | 298,981 | 3.8% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,890 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,667,804 | 33.8% |
| PUSH_NULL | 961,444 | 12.2% |
| STORE_SUBSCR_DICT | 906,674 | 11.5% |
| POP_JUMP_IF_NOT_NONE | 875,301 | 11.1% |
| STORE_FAST | 561,939 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,003,846 | 25.9% |
| LOAD_CONST | 2,852,122 | 24.6% |
| POP_TOP | 1,309,768 | 11.3% |
| POP_JUMP_IF_FALSE | 692,394 | 6.0% |
| LOAD_ATTR_METHOD_NO_DICT | 554,213 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,852,122 | 24.6% |
| CALL | 1,967,967 | 17.0% |
| COMPARE_OP_INT | 1,558,465 | 13.4% |
| LOAD_FAST | 1,204,455 | 10.4% |
| COPY | 825,600 | 7.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,368,193 | 97.1% |
| STORE_DEREF | 20,640 | 1.5% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.5% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,368,193 | 97.1% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 2.9% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,787,709 | 20.6% |
| STORE_FAST | 9,793,406 | 12.8% |
| POP_JUMP_IF_FALSE | 5,988,631 | 7.8% |
| POP_TOP | 5,729,275 | 7.5% |
| NOP | 4,830,951 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,746,658 | 21.9% |
| RETURN_VALUE | 8,124,892 | 10.6% |
| LOAD_ATTR | 6,128,887 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,113,117 | 8.0% |
| CALL_PY_EXACT_ARGS | 4,007,605 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 389,514 | 66.6% |
| LOAD_FAST_AND_CLEAR | 195,742 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 389,514 | 66.6% |
| LOAD_FAST_AND_CLEAR | 195,742 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 68.8% |
| POP_JUMP_IF_NONE | 183,697 | 29.2% |
| LOAD_ATTR_CLASS | 12,441 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 68.8% |
| LOAD_GLOBAL_MODULE | 183,697 | 29.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,441 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,045,040 | 17.1% |
| LOAD_FAST_LOAD_FAST | 1,565,566 | 13.1% |
| POP_JUMP_IF_FALSE | 1,140,176 | 9.5% |
| PUSH_NULL | 1,046,500 | 8.7% |
| LOAD_SUPER_ATTR_METHOD | 917,234 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,791,674 | 23.3% |
| LOAD_FAST_LOAD_FAST | 1,565,566 | 13.1% |
| CALL | 1,461,218 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,325,901 | 11.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 906,674 | 7.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 43.5% |
| RESUME_CHECK | 40 | 21.7% |
| POP_JUMP_IF_FALSE | 40 | 21.7% |
| POP_JUMP_IF_TRUE | 12 | 6.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 97 | 52.7% |
| LOAD_ATTR | 43 | 23.4% |
| LOAD_GLOBAL_BUILTIN | 41 | 22.3% |
| LOAD_FAST | 2 | 1.1% |
| COMPARE_OP | 1 | 0.5% |


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
| TO_BOOL_INT | 4,018,180 | 27.4% |
| TO_BOOL_BOOL | 3,721,862 | 25.4% |
| COMPARE_OP_INT | 2,839,606 | 19.4% |
| CONTAINS_OP | 1,338,674 | 9.1% |
| COMPARE_OP_STR | 1,088,012 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,988,631 | 40.9% |
| RETURN_CONST | 2,388,234 | 16.3% |
| LOAD_FAST_LOAD_FAST | 1,140,176 | 7.8% |
| POP_TOP | 1,136,432 | 7.8% |
| LOAD_GLOBAL_MODULE | 1,113,949 | 7.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 803,799 | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.7% |
| LOAD_ATTR | 21,120 | 2.5% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 223,434 | 26.3% |
| NOP | 211,532 | 24.9% |
| LOAD_FAST | 192,716 | 22.7% |
| LOAD_FAST_CHECK | 183,697 | 21.7% |
| RETURN_CONST | 18,240 | 2.1% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,808,421 | 47.1% |
| LOAD_ATTR | 875,301 | 22.8% |
| LOAD_ATTR_INSTANCE_VALUE | 751,381 | 19.6% |
| RETURN_VALUE | 351,970 | 9.2% |
| LOAD_DEREF | 41,280 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,535,311 | 39.9% |
| RETURN_CONST | 875,628 | 22.8% |
| JUMP_BACKWARD | 750,904 | 19.5% |
| NOP | 385,841 | 10.0% |
| LOAD_CONST | 183,212 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,389,441 | 67.7% |
| TO_BOOL | 636,384 | 31.0% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,240 | 0.4% |
| COMPARE_OP_INT | 2,247 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 714,861 | 34.8% |
| LOAD_FAST_LOAD_FAST | 639,262 | 31.2% |
| RETURN_CONST | 557,053 | 27.2% |
| LOAD_GLOBAL_MODULE | 55,293 | 2.7% |
| RETURN_VALUE | 46,169 | 2.3% |


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
| POP_JUMP_IF_FALSE | 2,388,234 | 33.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,677,596 | 23.8% |
| POP_TOP | 1,436,752 | 20.4% |
| POP_JUMP_IF_NOT_NONE | 875,628 | 12.4% |
| POP_JUMP_IF_TRUE | 557,053 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,986,795 | 70.8% |
| EXIT_INIT_CHECK | 809,758 | 11.5% |
| INTERPRETER_EXIT | 673,196 | 9.6% |
| TO_BOOL_BOOL | 496,569 | 7.1% |
| STORE_FAST | 47,129 | 0.7% |


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
| SWAP | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_FAST | 8,645 | 13.0% |
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
| YIELD_VALUE | 4,752,000 | 21.2% |
| CALL | 2,558,009 | 11.4% |
| COPY | 1,972,800 | 8.8% |
| RETURN_VALUE | 1,752,008 | 7.8% |
| FOR_ITER_LIST | 1,284,138 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,793,406 | 43.7% |
| JUMP_BACKWARD | 4,320,000 | 19.3% |
| NOP | 2,907,247 | 13.0% |
| COPY | 1,972,320 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 913,963 | 4.1% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,620,641 | 44.5% |
| COPY | 820,320 | 22.5% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 22.4% |
| STORE_FAST_STORE_FAST | 384,000 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,207,484 | 33.2% |
| STORE_FAST | 816,000 | 22.4% |
| LOAD_FAST_LOAD_FAST | 785,637 | 21.6% |
| JUMP_BACKWARD | 436,320 | 12.0% |
| STORE_FAST_STORE_FAST | 384,000 | 10.5% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 431,995 | 21.6% |
| LOAD_FAST_AND_CLEAR | 389,514 | 19.5% |
| BUILD_LIST | 389,514 | 19.5% |
| FOR_ITER_LIST | 378,954 | 18.9% |
| LOAD_FAST | 204,337 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 431,990 | 21.6% |
| LOAD_CONST | 400,079 | 20.0% |
| STORE_FAST | 389,514 | 19.5% |
| BUILD_LIST | 389,514 | 19.5% |
| FOR_ITER_LIST | 378,954 | 18.9% |


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
| LOAD_FAST | 196,227 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 196,227 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 820,310 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 5 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 431,995 | 51.8% |
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
| CALL | 183,697 | 99.9% |
| LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 183,817 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,820 | 79.7% |
| LOAD_CONST | 46,169 | 18.5% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 244,989 | 98.3% |
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
| LOAD_FAST_LOAD_FAST | 366,424 | 97.7% |
| LOAD_CONST | 8,640 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 366,424 | 97.7% |
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
| LOAD_GLOBAL_MODULE | 400,079 | 49.4% |
| LOAD_FAST | 384,719 | 47.5% |
| CALL | 24,960 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 430,319 | 53.1% |
| COPY_FREE_VARS | 379,439 | 46.9% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 48,559 | 45.7% |
| LOAD_FAST | 48,000 | 45.2% |
| LOAD_CONST | 5,280 | 5.0% |
| BINARY_OP_ADD_INT | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 101,848 | 95.9% |
| POP_TOP | 4,320 | 4.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.1% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 384,000 | 39.0% |
| LOAD_FAST | 209,747 | 21.3% |
| CALL_LEN | 183,212 | 18.6% |
| CALL_BUILTIN_CLASS | 183,212 | 18.6% |
| LOAD_CONST | 11,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 580,227 | 59.0% |
| GET_ITER | 207,692 | 21.1% |
| CALL_BUILTIN_CLASS | 183,212 | 18.6% |
| LOAD_FAST | 12,960 | 1.3% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 679,839 | 48.7% |
| LOAD_CONST | 484,504 | 34.7% |
| LOAD_FAST_LOAD_FAST | 129,700 | 9.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 61,010 | 4.4% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 477,304 | 34.2% |
| STORE_FAST | 448,802 | 32.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 353,637 | 25.3% |
| UNPACK_SEQUENCE_TUPLE | 61,010 | 4.4% |
| POP_TOP | 10,940 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,800 | 45.6% |
| BUILD_TUPLE | 384,000 | 45.0% |
| CALL | 48,569 | 5.7% |
| LOAD_FAST_CHECK | 12,441 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 790,560 | 92.7% |
| RETURN_VALUE | 61,010 | 7.2% |
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
| LOAD_GLOBAL_BUILTIN | 919,634 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 919,634 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 454,904 | 95.7% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 4.3% |
| CALL | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,340 | 54.3% |
| CALL_BUILTIN_CLASS | 183,212 | 38.5% |
| CALL_PY_EXACT_ARGS | 24,960 | 5.2% |
| LOAD_FAST | 4,320 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 195,742 | 95.8% |
| LOAD_FAST | 8,640 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 195,742 | 95.8% |
| LOAD_GLOBAL_MODULE | 8,640 | 4.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,286,113 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,190 | 0.2% |
| LOAD_CONST | 960 | 0.1% |
| CALL | 5 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 906,674 | 70.3% |
| STORE_FAST | 382,634 | 29.7% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,049,747 | 93.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,451 | 6.5% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 486,657 | 43.3% |
| STORE_FAST | 432,000 | 38.4% |
| LOAD_FAST | 63,840 | 5.7% |
| CALL_BUILTIN_FAST | 61,010 | 5.4% |
| RETURN_VALUE | 38,802 | 3.4% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 669,867 | 92.1% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,605 | 3.0% |
| RETURN_VALUE | 10,560 | 1.5% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 691,472 | 95.1% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.5% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,285,724 | 44.9% |
| LOAD_FAST | 4,007,605 | 42.0% |
| LOAD_FAST_LOAD_FAST | 625,772 | 6.6% |
| LOAD_SUPER_ATTR_METHOD | 379,439 | 4.0% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,515,247 | 99.6% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 928,116 | 41.4% |
| LOAD_ATTR_MODULE | 906,674 | 40.5% |
| LOAD_FAST | 258,142 | 11.5% |
| LOAD_CONST | 80,744 | 3.6% |
| BINARY_OP | 62,880 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,333,723 | 59.5% |
| COPY_FREE_VARS | 906,674 | 40.5% |


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
| LOAD_CONST | 1,558,465 | 54.8% |
| LOAD_ATTR_INSTANCE_VALUE | 819,339 | 28.8% |
| LOAD_FAST | 432,000 | 15.2% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,839,606 | 99.9% |
| POP_JUMP_IF_TRUE | 2,247 | 0.1% |
| COMPARE_OP | 72 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,068,404 | 95.6% |
| LOAD_CONST | 44,640 | 4.0% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 8 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,088,012 | 97.4% |
| LOAD_FAST | 10,560 | 0.9% |
| COPY | 10,560 | 0.9% |
| POP_JUMP_IF_TRUE | 8,240 | 0.7% |


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
| JUMP_BACKWARD | 5,995,622 | 79.2% |
| GET_ITER | 1,197,118 | 15.8% |
| SWAP | 378,954 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,320,000 | 57.1% |
| STORE_FAST | 1,284,138 | 17.0% |
| LOAD_FAST | 758,878 | 10.0% |
| JUMP_BACKWARD | 432,000 | 5.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 391,484 | 5.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 387,153 | 65.7% |
| GET_ITER | 202,532 | 34.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 398,193 | 67.5% |
| LOAD_FAST | 183,332 | 31.1% |
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
| LOAD_GLOBAL_MODULE | 61,010 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,249 | 81.9% |
| LOAD_FAST_CHECK | 12,441 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,746,658 | 90.3% |
| LOAD_FAST_LOAD_FAST | 1,325,901 | 7.2% |
| COPY | 431,990 | 2.3% |
| LOAD_ATTR_INSTANCE_VALUE | 18,147 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,231,537 | 22.8% |
| LOAD_FAST | 2,814,369 | 15.2% |
| TO_BOOL_BOOL | 1,433,770 | 7.7% |
| LOAD_ATTR | 1,365,331 | 7.4% |
| CONTAINS_OP | 1,338,669 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,020 | 39.8% |
| CALL | 111,449 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,451 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,231,537 | 87.1% |
| LOAD_FAST | 480,926 | 9.9% |
| LOAD_ATTR | 62,890 | 1.3% |
| LOAD_ATTR_SLOT | 62,880 | 1.3% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,923,560 | 39.6% |
| CALL | 1,083,627 | 22.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,049,747 | 21.6% |
| LOAD_CONST | 554,213 | 11.4% |
| LOAD_FAST_LOAD_FAST | 227,566 | 4.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,113,117 | 71.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,014,470 | 11.9% |
| LOAD_FAST_LOAD_FAST | 906,674 | 10.7% |
| BINARY_SUBSCR | 432,000 | 5.1% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,285,724 | 50.4% |
| LOAD_FAST | 2,606,817 | 30.7% |
| CALL_PY_WITH_DEFAULTS | 928,116 | 10.9% |
| LOAD_FAST_LOAD_FAST | 508,800 | 6.0% |
| LOAD_CONST | 94,664 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,745,905 | 100.0% |
| LOAD_ATTR | 89 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,728,420 | 62.9% |
| CALL_PY_WITH_DEFAULTS | 906,674 | 33.0% |
| STORE_DEREF | 41,280 | 1.5% |
| LOAD_CONST | 26,400 | 1.0% |
| LOAD_FAST | 20,640 | 0.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 937,394 | 70.5% |
| LOAD_FAST_LOAD_FAST | 391,484 | 29.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 906,674 | 68.2% |
| UNARY_INVERT | 391,484 | 29.5% |
| RETURN_VALUE | 10,560 | 0.8% |
| LOAD_CONST | 10,560 | 0.8% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 772,001 | 97.3% |
| RETURN_VALUE | 20,640 | 2.6% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 784,641 | 98.9% |
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
| RESUME_CHECK | 2,790,867 | 41.9% |
| LOAD_FAST | 939,794 | 14.1% |
| STORE_FAST | 913,963 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 750,424 | 11.3% |
| NOP | 559,984 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,072,334 | 46.1% |
| LOAD_DEREF | 1,368,193 | 20.5% |
| CALL_ISINSTANCE | 919,634 | 13.8% |
| LOAD_GLOBAL_BUILTIN | 750,424 | 11.3% |
| LOAD_GLOBAL_MODULE | 468,960 | 7.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,738,863 | 28.8% |
| RESUME_CHECK | 2,374,868 | 18.3% |
| NOP | 1,377,331 | 10.6% |
| POP_JUMP_IF_FALSE | 1,113,949 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,090,331 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,915,764 | 22.5% |
| LOAD_ATTR_MODULE | 2,745,905 | 21.1% |
| LOAD_FAST_LOAD_FAST | 2,045,040 | 15.7% |
| LOAD_FAST | 1,644,580 | 12.7% |
| COMPARE_OP_STR | 1,068,404 | 8.2% |


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
| LOAD_FAST | 1,300,993 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 917,234 | 70.5% |
| CALL_PY_EXACT_ARGS | 379,439 | 29.2% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 9,515,247 | 33.7% |
| CACHE | 8,889,442 | 31.5% |
| FOR_ITER_GEN | 4,752,000 | 16.8% |
| COPY_FREE_VARS | 1,372,633 | 4.9% |
| CALL_PY_WITH_DEFAULTS | 1,333,723 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,787,709 | 56.0% |
| POP_TOP | 5,184,960 | 18.4% |
| LOAD_GLOBAL_BUILTIN | 2,790,867 | 9.9% |
| LOAD_GLOBAL_MODULE | 2,374,868 | 8.4% |
| NOP | 1,057,874 | 3.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,226,236 | 68.3% |
| LOAD_FAST_LOAD_FAST | 575,759 | 17.7% |
| SWAP | 431,990 | 13.3% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,677,596 | 51.5% |
| LOAD_FAST | 684,955 | 21.0% |
| LOAD_GLOBAL_MODULE | 538,799 | 16.5% |
| LOAD_CONST | 160,320 | 4.9% |
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
| LOAD_ATTR | 906,674 | 92.9% |
| LOAD_FAST | 34,390 | 3.5% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.7% |
| CALL | 7,680 | 0.8% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 909,869 | 93.3% |
| RETURN_CONST | 24,480 | 2.5% |
| LOAD_GLOBAL_MODULE | 20,640 | 2.1% |
| LOAD_CONST | 20,640 | 2.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,433,770 | 26.9% |
| CALL_ISINSTANCE | 919,634 | 17.3% |
| RETURN_VALUE | 693,435 | 13.0% |
| CALL | 548,073 | 10.3% |
| LOAD_FAST | 540,569 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,721,862 | 69.9% |
| POP_JUMP_IF_TRUE | 1,389,441 | 26.1% |
| UNARY_NOT | 215,387 | 4.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,204,832 | 54.9% |
| LOAD_FAST | 906,674 | 22.6% |
| BINARY_OP | 906,674 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,018,180 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,079 | 92.3% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 420,239 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,845 | 79.8% |
| LOAD_FAST | 20,640 | 11.4% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,445 | 91.7% |
| POP_JUMP_IF_TRUE | 14,880 | 8.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,000 | 93.0% |
| CALL_BUILTIN_FAST | 61,010 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 61,010 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 436,320 | 26.8% |
| LOAD_FAST_CHECK | 432,000 | 26.6% |
| FOR_ITER_LIST | 391,484 | 24.1% |
| CALL_BUILTIN_FAST | 353,637 | 21.7% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,620,641 | 99.7% |
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
| STORE_FAST | 480 | 59.5% |
| COPY | 327 | 40.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 59.5% |
| POP_JUMP_IF_FALSE | 327 | 40.5% |


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
| specialization.deferred |       478169 | 45.4% |
|          hit |       573784 | 54.5% |

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
| specialization.deferred |        22565 | 2.3% |
|          hit |       975629 | 97.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5 | 2.4% |
| Failure | 200 | 97.6% |

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
| specialization.deferred |      1189115 | 10.7% |
|          hit |      9946241 | 89.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2 | 0.2% |
| Failure | 1,048 | 99.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 327 | 31.2% |
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
| specialization.deferred |      5429949 | 77.5% |
|          hit |      1570628 | 22.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 45 | 2.1% |
| Failure | 2,060 | 97.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,032 | 50.1% |
| or | 601 | 29.2% |
| remainder | 227 | 11.0% |
| add different types | 160 | 7.8% |
| add other | 40 | 1.9% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8814031 | 29.2% |
| specialization.deopt |           60 | 0.0% |
|          hit |     21354671 | 70.8% |
|         miss |         4380 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 121 | 1.3% |
| Failure | 9,032 | 98.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,522 | 27.9% |
| cfunc noargs | 1,795 | 19.9% |
| class no vectorcall | 1,271 | 14.1% |
| meth descr varargs keywords | 843 | 9.3% |
| class mutable | 417 | 4.6% |
| other | 360 | 4.0% |
| cfunc varargs keywords | 337 | 3.7% |
| cfunc varargs | 320 | 3.5% |
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
| specialization.deferred |       443600 | 10.1% |
| specialization.deopt |           72 | 0.0% |
|          hit |      3954323 | 89.8% |
|         miss |         4974 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 122 | 25.2% |
| Failure | 363 | 74.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 161 | 44.4% |
| different types | 122 | 33.6% |
| big int | 80 | 22.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       976320 | 7.0% |
|          hit |     12942179 | 93.0% |

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
| specialization.deferred |      7881451 | 17.5% |
| specialization.deopt |         4188 | 0.0% |
|          hit |     36983446 | 82.0% |
|         miss |       230241 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,333 | 41.9% |
| Failure | 6,016 | 58.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,406 | 23.4% |
| not managed dict | 1,225 | 20.4% |
| shadowed | 1,207 | 20.1% |
| non overriding descriptor | 612 | 10.2% |
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
| specialization.deferred |           46 | 0.0% |
| specialization.deopt |           54 | 0.0% |
|          hit |     19639873 | 100.0% |
|         miss |         5718 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 192 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1368193 | 100.0% |


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
| specialization.deferred |        65765 | 1.9% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      3185610 | 93.7% |
|         miss |       148120 | 4.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,785 | 81.3% |
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
|          hit |      2502931 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 230,018,824 | 53.0% |
| Not specialized | 60,687,555 | 14.0% |
| Specialized | 143,098,388 | 33.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,814,031 | 34.8% |
| LOAD_ATTR | 7,881,451 | 31.2% |
| BINARY_OP | 5,429,949 | 21.5% |
| TO_BOOL | 1,189,115 | 4.7% |
| FOR_ITER | 976,320 | 3.9% |
| BINARY_SUBSCR | 478,169 | 1.9% |
| COMPARE_OP | 443,600 | 1.8% |
| STORE_ATTR | 65,765 | 0.3% |
| STORE_SUBSCR | 22,565 | 0.1% |
| LOAD_GLOBAL | 46 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,440 | 40.8% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,681 | 15.4% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| LOAD_GLOBAL_MODULE | 5,718 | 1.5% |
| COMPARE_OP_INT | 4,974 | 1.3% |
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
| Calls to PyEval_EvalDefault | 8,976,802 | 31.8% |
| Calls to Python functions inlined | 19,239,846 | 68.2% |
| Calls via PyEval_EvalFrame (total) | 8,976,802 | 31.8% |
| Calls via PyEval_EvalFrame (vector) | 8,538,562 | 30.3% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,538,562 | 30.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 481,888 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 23,827,526 | 84.4% |
| Frame objects created | 38,063 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 15,172,872 | 42.9% |
| Frees to freelist | 15,174,300 |  |
| Allocations | 20,201,573 | 57.1% |
| Allocations to 512 bytes | 19,989,620 | 56.5% |
| Allocations to 4 kbytes | 86,172 | 0.2% |
| Allocations over 4 kbytes | 125,781 | 0.4% |
| Frees | 21,371,497 |  |
| New values | 65,280 |  |
| Interpreter increfs | 170,026,265 | 77.0% |
| Interpreter decrefs | 186,288,896 | 73.7% |
| Increfs | 50,747,996 | 23.0% |
| Decrefs | 66,373,302 | 26.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 9,267,402 |  |
| Method cache misses | 25,800 |  |
| Method cache collisions | 36,748 |  |
| Method cache dunder hits | 8,646,164 |  |
| Method cache dunder misses | 10,948 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 11 | 264 | 81,242 |
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
Stats gathered on: 2023-10-08
