
# Pystats results

- benchmark: concurrent_imap
- fork: gvanrossum
- ref: split-uops
- commit hash: 8ab398d
- commit date: 2023-10-03T16:05:03-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 75,827,113 | 17.6% | 17.6% |  |
| RESUME_CHECK | 27,972,407 | 6.5% | 24.1% |  |
| STORE_FAST | 22,228,553 | 5.2% | 29.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,381,191 | 4.3% | 33.6% | 0.9% |
| POP_TOP | 18,099,113 | 4.2% | 37.8% |  |
| RETURN_VALUE | 16,612,597 | 3.9% | 41.7% |  |
| POP_JUMP_IF_FALSE | 14,483,146 | 3.4% | 45.0% |  |
| JUMP_BACKWARD | 13,516,668 | 3.1% | 48.2% |  |
| LOAD_GLOBAL_MODULE | 12,809,095 | 3.0% | 51.2% | 0.0% |
| LOAD_FAST_LOAD_FAST | 11,816,591 | 2.7% | 53.9% |  |
| LOAD_CONST | 11,539,751 | 2.7% | 56.6% |  |
| CALL_PY_EXACT_ARGS | 9,414,172 | 2.2% | 58.8% |  |
| INTERPRETER_EXIT | 8,936,029 | 2.1% | 60.9% |  |
| CALL | 8,756,754 | 2.0% | 62.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,395,097 | 2.0% | 64.9% | 0.7% |
| LOAD_ATTR | 7,781,611 | 1.8% | 66.7% |  |
| NOP | 7,533,537 | 1.8% | 68.4% |  |
| FOR_ITER_LIST | 7,521,996 | 1.8% | 70.2% |  |
| RETURN_CONST | 6,967,000 | 1.6% | 71.8% |  |
| LOAD_GLOBAL_BUILTIN | 6,574,391 | 1.5% | 73.3% |  |
| PUSH_NULL | 5,530,130 | 1.3% | 74.6% |  |
| COPY | 5,451,997 | 1.3% | 75.9% |  |
| BINARY_OP | 5,336,061 | 1.2% | 77.1% |  |
| TO_BOOL_BOOL | 5,272,175 | 1.2% | 78.3% |  |
| YIELD_VALUE | 5,184,960 | 1.2% | 79.6% |  |
| STORE_FAST_LOAD_FAST | 4,847,040 | 1.1% | 80.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,824,553 | 1.1% | 81.8% |  |
| FOR_ITER_GEN | 4,760,640 | 1.1% | 82.9% |  |
| TO_BOOL_INT | 3,945,430 | 0.9% | 83.8% |  |
| POP_JUMP_IF_NOT_NONE | 3,803,128 | 0.9% | 84.7% |  |
| STORE_FAST_STORE_FAST | 3,627,704 | 0.8% | 85.6% |  |
| BUILD_TUPLE | 3,228,169 | 0.8% | 86.3% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,227,117 | 0.8% | 87.1% | 4.6% |
| COMPARE_OP_INT | 2,818,143 | 0.7% | 87.7% | 0.2% |
| LOAD_ATTR_MODULE | 2,716,140 | 0.6% | 88.4% |  |
| CALL_PY_WITH_DEFAULTS | 2,215,349 | 0.5% | 88.9% |  |
| POP_JUMP_IF_TRUE | 2,042,414 | 0.5% | 89.3% |  |
| SWAP | 1,974,085 | 0.5% | 89.8% |  |
| CALL_FUNCTION_EX | 1,810,137 | 0.4% | 90.2% |  |
| GET_ITER | 1,797,147 | 0.4% | 90.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,612,664 | 0.4% | 91.0% |  |
| LOAD_DEREF | 1,386,551 | 0.3% | 91.3% |  |
| CALL_BUILTIN_FAST | 1,380,718 | 0.3% | 91.7% |  |
| BEFORE_WITH | 1,379,297 | 0.3% | 92.0% |  |
| COPY_FREE_VARS | 1,349,471 | 0.3% | 92.3% |  |
| CONTAINS_OP | 1,322,146 | 0.3% | 92.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,305,712 | 0.3% | 92.9% |  |
| LOAD_SUPER_ATTR_METHOD | 1,277,831 | 0.3% | 93.2% |  |
| UNARY_INVERT | 1,274,992 | 0.3% | 93.5% |  |
| JUMP_FORWARD | 1,269,455 | 0.3% | 93.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,265,660 | 0.3% | 94.1% |  |
| BUILD_MAP | 1,257,925 | 0.3% | 94.4% |  |
| TO_BOOL | 1,187,995 | 0.3% | 94.7% |  |
| BUILD_LIST | 1,145,770 | 0.3% | 94.9% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,117,559 | 0.3% | 95.2% |  |
| COMPARE_OP_STR | 1,114,071 | 0.3% | 95.4% |  |
| FOR_ITER | 976,760 | 0.2% | 95.7% |  |
| CALL_BUILTIN_CLASS | 974,262 | 0.2% | 95.9% |  |
| STORE_SUBSCR_DICT | 957,655 | 0.2% | 96.1% |  |
| CALL_ISINSTANCE | 903,106 | 0.2% | 96.3% |  |
| UNPACK_SEQUENCE_TUPLE | 877,006 | 0.2% | 96.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 852,526 | 0.2% | 96.7% |  |
| POP_JUMP_IF_NONE | 838,398 | 0.2% | 96.9% |  |
| BINARY_OP_ADD_INT | 834,234 | 0.2% | 97.1% |  |
| EXIT_INIT_CHECK | 796,490 | 0.2% | 97.3% |  |
| CALL_ALLOC_AND_ENTER_INIT | 796,490 | 0.2% | 97.5% |  |
| LOAD_ATTR_PROPERTY | 780,507 | 0.2% | 97.7% | 1.2% |
| CALL_METHOD_DESCRIPTOR_O | 726,877 | 0.2% | 97.8% |  |
| LOAD_FAST_CHECK | 624,799 | 0.1% | 98.0% |  |
| LIST_APPEND | 621,797 | 0.1% | 98.1% |  |
| FOR_ITER_RANGE | 579,760 | 0.1% | 98.3% |  |
| LOAD_FAST_AND_CLEAR | 575,303 | 0.1% | 98.4% |  |
| BINARY_SUBSCR | 478,097 | 0.1% | 98.5% |  |
| CALL_LEN | 472,202 | 0.1% | 98.6% |  |
| COMPARE_OP | 437,328 | 0.1% | 98.7% |  |
| CALL_TUPLE_1 | 437,280 | 0.1% | 98.8% |  |
| DICT_MERGE | 422,880 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 413,605 | 0.1% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 368,434 | 0.1% | 99.1% |  |
| LIST_EXTEND | 360,754 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 306,904 | 0.1% | 99.3% |  |
| CALL_KW | 266,842 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 249,010 | 0.1% | 99.4% |  |
| UNARY_NOT | 212,014 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 201,063 | 0.0% | 99.5% |  |
| BINARY_OP_ADD_FLOAT | 192,908 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 180,502 | 0.0% | 99.6% |  |
| TO_BOOL_NONE | 180,289 | 0.0% | 99.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 106,246 | 0.0% | 99.6% | 4.1% |
| STORE_DEREF | 103,200 | 0.0% | 99.7% |  |
| MAKE_CELL | 103,200 | 0.0% | 99.7% |  |
| CALL_BUILTIN_O | 95,040 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_DICT | 85,440 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 84,480 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 84,480 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 73,440 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 68,686 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 0.0% | 99.8% |  |
| STORE_ATTR | 66,415 | 0.0% | 99.8% |  |
| DELETE_ATTR | 64,785 | 0.0% | 99.9% |  |
| DELETE_SUBSCR | 58,550 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 44,160 | 0.0% | 99.9% |  |
| FORMAT_SIMPLE | 41,760 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 37,718 | 0.0% | 99.9% |  |
| POP_EXCEPT | 37,718 | 0.0% | 99.9% |  |
| IS_OP | 34,859 | 0.0% | 99.9% |  |
| CHECK_EXC_MATCH | 33,398 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 32,640 | 0.0% | 99.9% |  |
| BUILD_STRING | 31,200 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 28,800 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 28,320 | 0.0% | 100.0% |  |
| IMPORT_NAME | 24,480 | 0.0% | 100.0% |  |
| IMPORT_FROM | 24,480 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 22,773 | 0.0% | 100.0% |  |
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
| TO_BOOL_ALWAYS_TRUE | 779 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 202 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,616,278 | 3.9% | 3.9% |
| RESUME_CHECK LOAD_FAST | 15,663,348 | 3.6% | 7.5% |
| STORE_FAST LOAD_FAST | 9,687,045 | 2.3% | 9.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,379,612 | 2.2% | 11.9% |
| CACHE RESUME_CHECK | 8,852,994 | 2.1% | 14.0% |
| LOAD_FAST RETURN_VALUE | 8,058,717 | 1.9% | 15.9% |
| RETURN_VALUE INTERPRETER_EXIT | 7,836,519 | 1.8% | 17.7% |
| POP_TOP JUMP_BACKWARD | 6,539,164 | 1.5% | 19.2% |
| LOAD_FAST LOAD_ATTR | 6,032,887 | 1.4% | 20.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 6,030,734 | 1.4% | 22.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 5,965,826 | 1.4% | 23.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,927,700 | 1.4% | 24.8% |
| POP_TOP LOAD_FAST | 5,657,840 | 1.3% | 26.1% |
| RESUME_CHECK POP_TOP | 5,184,960 | 1.2% | 27.3% |
| RETURN_CONST POP_TOP | 4,931,537 | 1.1% | 28.5% |
| NOP LOAD_FAST | 4,786,776 | 1.1% | 29.6% |
| YIELD_VALUE STORE_FAST | 4,752,000 | 1.1% | 30.7% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,752,000 | 1.1% | 31.8% |
| FOR_ITER_GEN RESUME_CHECK | 4,752,000 | 1.1% | 32.9% |
| STORE_FAST_LOAD_FAST YIELD_VALUE | 4,320,000 | 1.0% | 33.9% |
| STORE_FAST JUMP_BACKWARD | 4,320,000 | 1.0% | 34.9% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 4,320,000 | 1.0% | 35.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,230,181 | 1.0% | 36.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,200,254 | 1.0% | 37.9% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,945,430 | 0.9% | 38.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,937,485 | 0.9% | 39.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,676,653 | 0.9% | 40.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,672,723 | 0.9% | 41.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,032,582 | 0.7% | 42.1% |
| LOAD_FAST LOAD_CONST | 2,973,125 | 0.7% | 42.8% |
| STORE_FAST NOP | 2,879,893 | 0.7% | 43.5% |
| LOAD_GLOBAL_MODULE BINARY_OP | 2,862,861 | 0.7% | 44.2% |
| LOAD_CONST LOAD_CONST | 2,838,819 | 0.7% | 44.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,815,856 | 0.7% | 45.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,789,483 | 0.6% | 46.1% |
| LOAD_FAST PUSH_NULL | 2,759,414 | 0.6% | 46.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,751,177 | 0.6% | 47.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,748,669 | 0.6% | 48.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,716,049 | 0.6% | 48.7% |
| LOAD_ATTR LOAD_FAST | 2,624,809 | 0.6% | 49.3% |
| PUSH_NULL LOAD_FAST | 2,612,523 | 0.6% | 49.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 2,563,142 | 0.6% | 50.5% |
| CALL STORE_FAST | 2,531,239 | 0.6% | 51.1% |
| POP_JUMP_IF_FALSE RETURN_CONST | 2,367,628 | 0.6% | 51.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,341,709 | 0.5% | 52.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 2,199,698 | 0.5% | 52.7% |
| COPY TO_BOOL_INT | 2,165,138 | 0.5% | 53.2% |
| BINARY_OP COPY | 2,165,138 | 0.5% | 53.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 2,008,669 | 0.5% | 54.2% |
| COPY STORE_FAST | 1,972,800 | 0.5% | 54.6% |
| STORE_FAST COPY | 1,972,320 | 0.5% | 55.1% |
| LOAD_CONST CALL | 1,962,457 | 0.5% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,898,365 | 0.4% | 56.0% |
| CALL RETURN_VALUE | 1,866,946 | 0.4% | 56.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,801,418 | 0.4% | 56.8% |
| RETURN_VALUE STORE_FAST | 1,725,467 | 0.4% | 57.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,715,089 | 0.4% | 57.6% |
| CALL POP_TOP | 1,698,977 | 0.4% | 58.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,651,060 | 0.4% | 58.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,618,099 | 0.4% | 58.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,607,384 | 0.4% | 59.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 1,545,723 | 0.4% | 59.5% |
| LOAD_CONST COMPARE_OP_INT | 1,541,598 | 0.4% | 59.9% |
| PUSH_NULL CALL | 1,527,484 | 0.4% | 60.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,525,005 | 0.4% | 60.6% |
| RETURN_VALUE RETURN_VALUE | 1,491,173 | 0.3% | 60.9% |
| LOAD_FAST_LOAD_FAST CALL | 1,444,671 | 0.3% | 61.3% |
| POP_TOP RETURN_CONST | 1,429,531 | 0.3% | 61.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,410,486 | 0.3% | 61.9% |
| LOAD_FAST CALL_FUNCTION_EX | 1,387,257 | 0.3% | 62.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,383,508 | 0.3% | 62.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,358,677 | 0.3% | 62.9% |
| NOP LOAD_GLOBAL_MODULE | 1,354,189 | 0.3% | 63.2% |
| COPY_FREE_VARS RESUME_CHECK | 1,349,471 | 0.3% | 63.5% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,345,031 | 0.3% | 63.8% |
| LOAD_DEREF LOAD_FAST | 1,345,031 | 0.3% | 64.1% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,325,203 | 0.3% | 64.5% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,322,146 | 0.3% | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 1,322,140 | 0.3% | 65.1% |
| LOAD_FAST BUILD_TUPLE | 1,314,946 | 0.3% | 65.4% |
| POP_TOP LOAD_CONST | 1,302,843 | 0.3% | 65.7% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,301,306 | 0.3% | 66.0% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,277,831 | 0.3% | 66.3% |
| UNARY_INVERT BINARY_OP | 1,274,992 | 0.3% | 66.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,262,951 | 0.3% | 66.9% |
| FOR_ITER_LIST STORE_FAST | 1,260,980 | 0.3% | 67.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,200,846 | 0.3% | 67.4% |
| LOAD_CONST LOAD_FAST | 1,197,785 | 0.3% | 67.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 1,190,340 | 0.3% | 68.0% |
| GET_ITER FOR_ITER_LIST | 1,183,850 | 0.3% | 68.3% |
| POP_TOP NOP | 1,182,186 | 0.3% | 68.5% |
| LOAD_FAST TO_BOOL | 1,147,108 | 0.3% | 68.8% |
| LOAD_FAST GET_ITER | 1,140,610 | 0.3% | 69.1% |
| RETURN_VALUE POP_TOP | 1,132,767 | 0.3% | 69.3% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,118,884 | 0.3% | 69.6% |
| POP_JUMP_IF_FALSE POP_TOP | 1,116,266 | 0.3% | 69.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,097,406 | 0.3% | 70.1% |
| BINARY_OP STORE_FAST | 1,093,129 | 0.3% | 70.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,087,000 | 0.3% | 70.6% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 1,084,697 | 0.3% | 70.9% |


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
| RESUME_CHECK | 8,852,994 | 99.0% |
| COPY_FREE_VARS | 82,080 | 0.9% |
| POP_TOP | 5,280 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 940,257 | 68.2% |
| RETURN_VALUE | 372,805 | 27.0% |
| LOAD_GLOBAL_MODULE | 61,915 | 4.5% |
| CALL | 4,320 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,002,172 | 72.7% |
| STORE_FAST | 377,125 | 27.3% |


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
| LOAD_CONST | 45,878 | 9.6% |
| BINARY_SUBSCR | 219 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 432,000 | 90.4% |
| STORE_FAST | 45,878 | 9.6% |
| BINARY_SUBSCR | 219 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 29,558 | 88.5% |
| LOAD_ATTR_MODULE | 3,840 | 11.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 33,398 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,315 | 48.4% |
| CALL | 20,635 | 35.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,598 | 16.4% |
| LOAD_ATTR | 2 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 45,595 | 77.9% |
| RETURN_CONST | 7,675 | 13.1% |
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
| RETURN_CONST | 796,490 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 796,490 | 100.0% |


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
| LOAD_FAST | 1,140,610 | 63.5% |
| STORE_FAST_LOAD_FAST | 432,000 | 24.0% |
| CALL_BUILTIN_CLASS | 204,377 | 11.4% |
| CALL | 10,560 | 0.6% |
| RETURN_VALUE | 4,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,183,850 | 65.9% |
| LOAD_FAST_AND_CLEAR | 382,880 | 21.3% |
| FOR_ITER_RANGE | 199,217 | 11.1% |
| FOR_ITER_TUPLE | 8,640 | 0.5% |
| FOR_ITER_GEN | 8,640 | 0.5% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,836,519 | 87.7% |
| RETURN_CONST | 666,550 | 7.5% |
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
| STORE_FAST | 2,879,893 | 38.2% |
| POP_TOP | 1,182,186 | 15.7% |
| RESUME_CHECK | 1,041,346 | 13.8% |
| POP_JUMP_IF_FALSE | 1,005,567 | 13.3% |
| JUMP_BACKWARD | 816,000 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,786,776 | 63.5% |
| LOAD_GLOBAL_MODULE | 1,354,189 | 18.0% |
| LOAD_GLOBAL_BUILTIN | 550,052 | 7.3% |
| LOAD_FAST_LOAD_FAST | 437,280 | 5.8% |
| LOAD_CONST | 396,960 | 5.3% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 25,238 | 66.9% |
| COPY | 8,640 | 22.9% |
| POP_TOP | 3,840 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 25,238 | 66.9% |
| RERAISE | 8,640 | 22.9% |
| JUMP_FORWARD | 3,840 | 10.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,184,960 | 28.6% |
| RETURN_CONST | 4,931,537 | 27.2% |
| CALL | 1,698,977 | 9.4% |
| RETURN_VALUE | 1,132,767 | 6.3% |
| POP_JUMP_IF_FALSE | 1,116,266 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,539,164 | 36.1% |
| LOAD_FAST | 5,657,840 | 31.3% |
| RETURN_CONST | 1,429,531 | 7.9% |
| LOAD_CONST | 1,302,843 | 7.2% |
| NOP | 1,182,186 | 6.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 29,558 | 78.4% |
| RERAISE | 4,320 | 11.5% |
| CALL_KW | 3,840 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 29,558 | 78.4% |
| WITH_EXCEPT_START | 4,320 | 11.5% |
| LOAD_GLOBAL_MODULE | 3,840 | 10.2% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,759,414 | 49.9% |
| LOAD_ATTR_MODULE | 1,715,089 | 31.0% |
| LOAD_ATTR | 961,427 | 17.4% |
| LOAD_SUPER_ATTR_ATTR | 67,200 | 1.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,612,523 | 47.2% |
| CALL | 1,527,484 | 27.6% |
| LOAD_FAST_LOAD_FAST | 1,046,492 | 18.9% |
| LOAD_CONST | 240,335 | 4.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 48,576 | 0.9% |


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
| LOAD_FAST | 8,058,717 | 48.5% |
| CALL | 1,866,946 | 11.2% |
| RETURN_VALUE | 1,491,173 | 9.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,190,340 | 7.2% |
| CALL_FUNCTION_EX | 948,897 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,836,519 | 47.2% |
| STORE_FAST | 1,725,467 | 10.4% |
| RETURN_VALUE | 1,491,173 | 9.0% |
| POP_TOP | 1,132,767 | 6.8% |
| LOAD_FAST_LOAD_FAST | 890,146 | 5.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 10,560 | 46.4% |
| LOAD_FAST | 7,693 | 33.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,320 | 19.0% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,880 | 65.3% |
| LOAD_GLOBAL_MODULE | 7,680 | 33.7% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 7 | 0.0% |
| LOAD_FAST | 6 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,147,108 | 96.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,831 | 3.4% |
| TO_BOOL | 1,044 | 0.1% |
| LOAD_ATTR | 7 | 0.0% |
| RETURN_VALUE | 5 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 633,070 | 53.3% |
| POP_JUMP_IF_FALSE | 553,879 | 46.6% |
| TO_BOOL | 1,044 | 0.1% |
| TO_BOOL_BOOL | 2 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 890,146 | 69.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 384,846 | 30.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,274,992 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 212,014 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 212,014 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 2,862,861 | 53.7% |
| UNARY_INVERT | 1,274,992 | 23.9% |
| POP_JUMP_IF_FALSE | 890,146 | 16.7% |
| LOAD_ATTR | 202,983 | 3.8% |
| LOAD_FAST_LOAD_FAST | 62,880 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,165,138 | 40.6% |
| STORE_FAST | 1,093,129 | 20.5% |
| UNARY_INVERT | 890,146 | 16.7% |
| TO_BOOL_INT | 890,146 | 16.7% |
| BUILD_TUPLE | 192,423 | 3.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 382,880 | 33.4% |
| JUMP_FORWARD | 372,805 | 32.5% |
| LOAD_FAST | 192,908 | 16.8% |
| POP_TOP | 179,897 | 15.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 385,285 | 33.6% |
| SWAP | 382,880 | 33.4% |
| STORE_FAST | 373,765 | 32.6% |
| RETURN_VALUE | 3,840 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 432,000 | 34.3% |
| LOAD_FAST | 396,960 | 31.6% |
| RESUME_CHECK | 380,485 | 30.2% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.1% |
| POP_JUMP_IF_NOT_NONE | 12,960 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 812,965 | 64.6% |
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
| LOAD_FAST | 1,314,946 | 40.7% |
| LOAD_FAST_LOAD_FAST | 870,240 | 27.0% |
| BUILD_MAP | 432,000 | 13.4% |
| RETURN_VALUE | 384,000 | 11.9% |
| BINARY_OP | 192,423 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 891,106 | 27.6% |
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
| LOAD_CONST | 1,962,457 | 22.4% |
| PUSH_NULL | 1,527,484 | 17.4% |
| LOAD_FAST_LOAD_FAST | 1,444,671 | 16.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,082,754 | 12.4% |
| BUILD_TUPLE | 891,106 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,531,239 | 28.9% |
| RETURN_VALUE | 1,866,946 | 21.3% |
| POP_TOP | 1,698,977 | 19.4% |
| LOAD_FAST | 785,193 | 9.0% |
| TO_BOOL_BOOL | 549,210 | 6.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,387,257 | 76.6% |
| DICT_MERGE | 422,880 | 23.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 948,897 | 52.4% |
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
| LOAD_CONST | 266,842 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 214,937 | 80.5% |
| LOAD_FAST | 21,600 | 8.1% |
| RETURN_VALUE | 15,840 | 5.9% |
| STORE_FAST | 10,560 | 4.0% |
| PUSH_EXC_INFO | 3,840 | 1.4% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 436,517 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 439 | 0.1% |
| COMPARE_OP | 291 | 0.1% |
| COMPARE_OP_INT | 68 | 0.0% |
| LOAD_GLOBAL_MODULE | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 436,915 | 99.9% |
| COMPARE_OP | 291 | 0.1% |
| COMPARE_OP_INT | 109 | 0.0% |
| COMPARE_OP_STR | 10 | 0.0% |
| POP_JUMP_IF_TRUE | 3 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,322,140 | 100.0% |
| LOAD_ATTR | 6 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,322,146 | 100.0% |


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
| BINARY_OP | 2,165,138 | 39.7% |
| STORE_FAST | 1,972,320 | 36.2% |
| LOAD_CONST | 825,600 | 15.1% |
| LOAD_FAST | 442,560 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 15,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,165,138 | 39.7% |
| STORE_FAST | 1,972,800 | 36.2% |
| STORE_FAST_STORE_FAST | 820,320 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 431,987 | 7.9% |
| LOAD_FAST | 21,120 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 890,146 | 66.0% |
| CALL_ALLOC_AND_ENTER_INIT | 372,805 | 27.6% |
| CACHE | 82,080 | 6.1% |
| CALL | 4,320 | 0.3% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,349,471 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,785 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,190 | 66.7% |
| RETURN_CONST | 20,635 | 31.9% |
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
| LOAD_GLOBAL_MODULE | 1,259 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 34,859 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,539,164 | 48.4% |
| STORE_FAST | 4,320,000 | 32.0% |
| POP_JUMP_IF_NOT_NONE | 744,274 | 5.5% |
| LIST_APPEND | 621,797 | 4.6% |
| STORE_FAST_STORE_FAST | 436,320 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,965,826 | 44.1% |
| FOR_ITER_GEN | 4,752,000 | 35.2% |
| FOR_ITER | 952,800 | 7.0% |
| NOP | 816,000 | 6.0% |
| LOAD_GLOBAL_BUILTIN | 432,000 | 3.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 802,735 | 63.2% |
| POP_TOP | 453,280 | 35.7% |
| STORE_ATTR_INSTANCE_VALUE | 5,280 | 0.4% |
| BINARY_SUBSCR_TUPLE_INT | 4,320 | 0.3% |
| POP_EXCEPT | 3,840 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 839,257 | 66.1% |
| BUILD_LIST | 372,805 | 29.4% |
| POP_EXCEPT | 25,238 | 2.0% |
| LOAD_GLOBAL_MODULE | 18,715 | 1.5% |
| LOAD_FAST_LOAD_FAST | 5,280 | 0.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 344,894 | 55.5% |
| LOAD_ATTR | 192,423 | 30.9% |
| BINARY_SUBSCR_STR_INT | 84,480 | 13.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 621,797 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180,857 | 50.1% |
| RETURN_VALUE | 179,897 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180,377 | 50.0% |
| STORE_FAST | 179,897 | 49.9% |
| RETURN_VALUE | 480 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,032,887 | 77.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,358,677 | 17.5% |
| LOAD_GLOBAL_MODULE | 295,668 | 3.8% |
| CALL | 62,880 | 0.8% |
| LOAD_FAST_LOAD_FAST | 14,893 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,624,809 | 33.7% |
| PUSH_NULL | 961,427 | 12.4% |
| STORE_SUBSCR_DICT | 890,146 | 11.4% |
| POP_JUMP_IF_NOT_NONE | 862,046 | 11.1% |
| STORE_FAST | 555,297 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,973,125 | 25.8% |
| LOAD_CONST | 2,838,819 | 24.6% |
| POP_TOP | 1,302,843 | 11.3% |
| POP_JUMP_IF_FALSE | 689,047 | 6.0% |
| LOAD_ATTR_METHOD_NO_DICT | 555,390 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,838,819 | 24.6% |
| CALL | 1,962,457 | 17.0% |
| COMPARE_OP_INT | 1,541,598 | 13.4% |
| LOAD_FAST | 1,197,785 | 10.4% |
| COPY | 825,600 | 7.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,345,031 | 97.0% |
| STORE_DEREF | 20,640 | 1.5% |
| POP_JUMP_IF_NOT_NONE | 20,640 | 1.5% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,345,031 | 97.0% |
| POP_JUMP_IF_NOT_NONE | 41,280 | 3.0% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,663,348 | 20.7% |
| STORE_FAST | 9,687,045 | 12.8% |
| POP_JUMP_IF_FALSE | 5,927,700 | 7.8% |
| POP_TOP | 5,657,840 | 7.5% |
| NOP | 4,786,776 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,616,278 | 21.9% |
| RETURN_VALUE | 8,058,717 | 10.6% |
| LOAD_ATTR | 6,032,887 | 8.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,030,734 | 8.0% |
| CALL_PY_EXACT_ARGS | 3,937,485 | 5.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 382,880 | 66.6% |
| LOAD_FAST_AND_CLEAR | 192,423 | 33.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 382,880 | 66.6% |
| LOAD_FAST_AND_CLEAR | 192,423 | 33.4% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 432,000 | 69.1% |
| POP_JUMP_IF_NONE | 180,382 | 28.9% |
| LOAD_ATTR_CLASS | 12,417 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 432,000 | 69.1% |
| LOAD_GLOBAL_MODULE | 180,382 | 28.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 12,417 | 2.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,008,669 | 17.0% |
| LOAD_FAST_LOAD_FAST | 1,545,723 | 13.1% |
| POP_JUMP_IF_FALSE | 1,118,884 | 9.5% |
| PUSH_NULL | 1,046,492 | 8.9% |
| LOAD_SUPER_ATTR_METHOD | 900,706 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,748,669 | 23.3% |
| LOAD_FAST_LOAD_FAST | 1,545,723 | 13.1% |
| CALL | 1,444,671 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,301,306 | 11.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 890,146 | 7.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 39.6% |
| RESUME_CHECK | 40 | 19.8% |
| POP_JUMP_IF_FALSE | 40 | 19.8% |
| POP_JUMP_IF_TRUE | 21 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 10 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 101 | 50.0% |
| LOAD_ATTR | 50 | 24.8% |
| LOAD_GLOBAL_BUILTIN | 41 | 20.3% |
| LOAD_FAST | 7 | 3.5% |
| COMPARE_OP | 3 | 1.5% |


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
| TO_BOOL_INT | 3,945,430 | 27.2% |
| TO_BOOL_BOOL | 3,676,653 | 25.4% |
| COMPARE_OP_INT | 2,815,856 | 19.4% |
| CONTAINS_OP | 1,322,146 | 9.1% |
| COMPARE_OP_STR | 1,084,697 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,927,700 | 40.9% |
| RETURN_CONST | 2,367,628 | 16.3% |
| LOAD_FAST_LOAD_FAST | 1,118,884 | 7.7% |
| POP_TOP | 1,116,266 | 7.7% |
| LOAD_GLOBAL_MODULE | 1,097,406 | 7.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 793,758 | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE | 22,560 | 2.7% |
| LOAD_ATTR | 21,120 | 2.5% |
| RETURN_VALUE | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 220,087 | 26.3% |
| NOP | 208,217 | 24.8% |
| LOAD_FAST | 192,657 | 23.0% |
| LOAD_FAST_CHECK | 180,382 | 21.5% |
| RETURN_CONST | 18,240 | 2.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,801,418 | 47.4% |
| LOAD_ATTR | 862,046 | 22.7% |
| LOAD_ATTR_INSTANCE_VALUE | 738,110 | 19.4% |
| RETURN_VALUE | 345,374 | 9.1% |
| LOAD_DEREF | 41,280 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,525,005 | 40.1% |
| RETURN_CONST | 862,345 | 22.7% |
| JUMP_BACKWARD | 744,274 | 19.6% |
| NOP | 379,208 | 10.0% |
| LOAD_CONST | 179,897 | 4.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,383,508 | 67.7% |
| TO_BOOL | 633,070 | 31.0% |
| TO_BOOL_NONE | 14,880 | 0.7% |
| COMPARE_OP_STR | 8,254 | 0.4% |
| COMPARE_OP_INT | 2,219 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 716,178 | 35.1% |
| LOAD_FAST_LOAD_FAST | 635,943 | 31.1% |
| RETURN_CONST | 550,366 | 26.9% |
| LOAD_GLOBAL_MODULE | 55,001 | 2.7% |
| RETURN_VALUE | 45,878 | 2.2% |


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
| POP_JUMP_IF_FALSE | 2,367,628 | 34.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,651,060 | 23.7% |
| POP_TOP | 1,429,531 | 20.5% |
| POP_JUMP_IF_NOT_NONE | 862,345 | 12.4% |
| POP_JUMP_IF_TRUE | 550,366 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,931,537 | 70.8% |
| EXIT_INIT_CHECK | 796,490 | 11.4% |
| INTERPRETER_EXIT | 666,550 | 9.6% |
| TO_BOOL_BOOL | 497,725 | 7.1% |
| STORE_FAST | 46,838 | 0.7% |


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
| SWAP | 13 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 33,600 | 50.6% |
| LOAD_FAST_LOAD_FAST | 10,560 | 15.9% |
| LOAD_FAST | 8,646 | 13.0% |
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
| YIELD_VALUE | 4,752,000 | 21.4% |
| CALL | 2,531,239 | 11.4% |
| COPY | 1,972,800 | 8.9% |
| RETURN_VALUE | 1,725,467 | 7.8% |
| FOR_ITER_LIST | 1,260,980 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,687,045 | 43.6% |
| JUMP_BACKWARD | 4,320,000 | 19.4% |
| NOP | 2,879,893 | 13.0% |
| COPY | 1,972,320 | 8.9% |
| LOAD_GLOBAL_BUILTIN | 900,691 | 4.1% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,607,384 | 44.3% |
| COPY | 820,320 | 22.6% |
| UNPACK_SEQUENCE_TUPLE | 816,000 | 22.5% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200,846 | 33.1% |
| STORE_FAST | 816,000 | 22.5% |
| LOAD_FAST_LOAD_FAST | 779,018 | 21.5% |
| JUMP_BACKWARD | 436,320 | 12.0% |
| STORE_FAST_STORE_FAST | 384,000 | 10.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 431,994 | 21.9% |
| LOAD_FAST_AND_CLEAR | 382,880 | 19.4% |
| BUILD_LIST | 382,880 | 19.4% |
| FOR_ITER_LIST | 372,320 | 18.9% |
| LOAD_FAST | 201,022 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 431,987 | 21.9% |
| LOAD_CONST | 393,445 | 19.9% |
| STORE_FAST | 382,880 | 19.4% |
| BUILD_LIST | 382,880 | 19.4% |
| FOR_ITER_LIST | 372,320 | 18.9% |


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
| LOAD_FAST | 192,908 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 192,908 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 820,307 | 98.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 1.7% |
| BINARY_OP | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 431,994 | 51.8% |
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
| CALL | 180,382 | 99.9% |
| LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180,502 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,812 | 79.8% |
| LOAD_CONST | 45,878 | 18.4% |
| CALL_LEN | 4,320 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 244,690 | 98.3% |
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
| LOAD_FAST_LOAD_FAST | 359,794 | 97.7% |
| LOAD_CONST | 8,640 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 359,794 | 97.7% |
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
| LOAD_GLOBAL_MODULE | 393,445 | 49.4% |
| LOAD_FAST | 378,085 | 47.5% |
| CALL | 24,960 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 423,685 | 53.2% |
| COPY_FREE_VARS | 372,805 | 46.8% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 48,576 | 45.7% |
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
| CALL_FUNCTION_EX | 384,000 | 39.4% |
| LOAD_FAST | 206,428 | 21.2% |
| CALL_LEN | 179,897 | 18.5% |
| CALL_BUILTIN_CLASS | 179,897 | 18.5% |
| LOAD_CONST | 11,040 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 576,908 | 59.2% |
| GET_ITER | 204,377 | 21.0% |
| CALL_BUILTIN_CLASS | 179,897 | 18.5% |
| LOAD_FAST | 12,960 | 1.3% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 669,906 | 48.5% |
| LOAD_CONST | 477,874 | 34.6% |
| LOAD_FAST_LOAD_FAST | 129,692 | 9.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 61,006 | 4.4% |
| LOAD_GLOBAL_MODULE | 21,120 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 470,674 | 34.1% |
| STORE_FAST | 445,475 | 32.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 347,018 | 25.1% |
| UNPACK_SEQUENCE_TUPLE | 61,006 | 4.4% |
| POP_TOP | 10,945 | 0.8% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 388,800 | 45.6% |
| BUILD_TUPLE | 384,000 | 45.0% |
| CALL | 48,589 | 5.7% |
| LOAD_FAST_CHECK | 12,417 | 1.5% |
| LOAD_ATTR | 10,560 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 790,560 | 92.7% |
| RETURN_VALUE | 61,006 | 7.2% |
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
| LOAD_GLOBAL_BUILTIN | 903,106 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 903,106 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 451,561 | 95.6% |
| LOAD_ATTR_INSTANCE_VALUE | 20,640 | 4.4% |
| CALL | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 258,332 | 54.7% |
| CALL_BUILTIN_CLASS | 179,897 | 38.1% |
| CALL_PY_EXACT_ARGS | 24,960 | 5.3% |
| LOAD_FAST | 4,320 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 4,320 | 0.9% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 192,423 | 95.7% |
| LOAD_FAST | 8,640 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 192,423 | 95.7% |
| LOAD_GLOBAL_MODULE | 8,640 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,262,951 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,742 | 0.1% |
| LOAD_CONST | 960 | 0.1% |
| CALL | 7 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 890,146 | 70.3% |
| STORE_FAST | 374,554 | 29.6% |
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
| LOAD_ATTR_METHOD_NO_DICT | 1,042,216 | 93.3% |
| LOAD_ATTR_METHOD_LAZY_DICT | 73,423 | 6.6% |
| LOAD_ATTR | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 479,441 | 42.9% |
| STORE_FAST | 432,000 | 38.7% |
| LOAD_FAST | 63,840 | 5.7% |
| CALL_BUILTIN_FAST | 61,006 | 5.5% |
| RETURN_VALUE | 38,754 | 3.5% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 669,270 | 92.1% |
| LOAD_CONST | 24,480 | 3.4% |
| CALL | 21,607 | 3.0% |
| RETURN_VALUE | 10,560 | 1.5% |
| RETURN_GENERATOR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 690,877 | 95.0% |
| LOAD_CONST | 24,480 | 3.4% |
| RETURN_VALUE | 10,560 | 1.5% |
| BINARY_OP_ADD_UNICODE | 960 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,230,181 | 44.9% |
| LOAD_FAST | 3,937,485 | 41.8% |
| LOAD_FAST_LOAD_FAST | 622,457 | 6.6% |
| LOAD_SUPER_ATTR_METHOD | 372,805 | 4.0% |
| LOAD_GLOBAL_MODULE | 70,560 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,379,612 | 99.6% |
| MAKE_CELL | 20,640 | 0.2% |
| RETURN_GENERATOR | 13,920 | 0.1% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 922,953 | 41.7% |
| LOAD_ATTR_MODULE | 890,146 | 40.2% |
| LOAD_FAST | 254,823 | 11.5% |
| LOAD_CONST | 80,706 | 3.6% |
| BINARY_OP | 62,880 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,325,203 | 59.8% |
| COPY_FREE_VARS | 890,146 | 40.2% |


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
| LOAD_CONST | 1,541,598 | 54.7% |
| LOAD_ATTR_INSTANCE_VALUE | 812,457 | 28.8% |
| LOAD_FAST | 432,000 | 15.3% |
| LOAD_FAST_LOAD_FAST | 13,920 | 0.5% |
| CALL_BUILTIN_FAST | 10,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,815,856 | 99.9% |
| POP_JUMP_IF_TRUE | 2,219 | 0.1% |
| COMPARE_OP | 68 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,065,101 | 95.6% |
| LOAD_CONST | 44,640 | 4.0% |
| LOAD_FAST | 4,320 | 0.4% |
| COMPARE_OP | 10 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,084,697 | 97.4% |
| LOAD_FAST | 10,560 | 0.9% |
| COPY | 10,560 | 0.9% |
| POP_JUMP_IF_TRUE | 8,254 | 0.7% |


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
| JUMP_BACKWARD | 5,965,826 | 79.3% |
| GET_ITER | 1,183,850 | 15.7% |
| SWAP | 372,320 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 4,320,000 | 57.4% |
| STORE_FAST | 1,260,980 | 16.8% |
| LOAD_FAST | 745,610 | 9.9% |
| JUMP_BACKWARD | 432,000 | 5.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 384,846 | 5.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 380,543 | 65.6% |
| GET_ITER | 199,217 | 34.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 391,583 | 67.5% |
| LOAD_FAST | 180,017 | 31.1% |
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
| LOAD_GLOBAL_MODULE | 61,006 | 88.8% |
| LOAD_ATTR_MODULE | 7,680 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,269 | 81.9% |
| LOAD_FAST_CHECK | 12,417 | 18.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,616,278 | 90.4% |
| LOAD_FAST_LOAD_FAST | 1,301,306 | 7.1% |
| COPY | 431,987 | 2.4% |
| LOAD_ATTR_INSTANCE_VALUE | 18,119 | 0.1% |
| RETURN_VALUE | 10,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,200,254 | 22.9% |
| LOAD_FAST | 2,789,483 | 15.2% |
| TO_BOOL_BOOL | 1,410,486 | 7.7% |
| LOAD_ATTR | 1,358,677 | 7.4% |
| CONTAINS_OP | 1,322,140 | 7.2% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 306,904 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,012 | 39.8% |
| CALL | 111,469 | 36.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 73,423 | 23.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,200,254 | 87.1% |
| LOAD_FAST | 476,445 | 9.9% |
| LOAD_ATTR | 62,894 | 1.3% |
| LOAD_ATTR_SLOT | 62,880 | 1.3% |
| LOAD_CONST | 11,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,898,365 | 39.3% |
| CALL | 1,082,754 | 22.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,042,216 | 21.6% |
| LOAD_CONST | 555,390 | 11.5% |
| LOAD_FAST_LOAD_FAST | 224,228 | 4.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,030,734 | 71.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,008,967 | 12.0% |
| LOAD_FAST_LOAD_FAST | 890,146 | 10.6% |
| BINARY_SUBSCR | 432,000 | 5.1% |
| LOAD_GLOBAL_MODULE | 21,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,230,181 | 50.4% |
| LOAD_FAST | 2,563,142 | 30.5% |
| CALL_PY_WITH_DEFAULTS | 922,953 | 11.0% |
| LOAD_FAST_LOAD_FAST | 508,800 | 6.1% |
| LOAD_CONST | 94,626 | 1.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,716,049 | 100.0% |
| LOAD_ATTR | 91 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,715,089 | 63.1% |
| CALL_PY_WITH_DEFAULTS | 890,146 | 32.8% |
| STORE_DEREF | 41,280 | 1.5% |
| LOAD_CONST | 26,400 | 1.0% |
| LOAD_FAST | 20,640 | 0.8% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 920,866 | 70.5% |
| LOAD_FAST_LOAD_FAST | 384,846 | 29.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 890,146 | 68.2% |
| UNARY_INVERT | 384,846 | 29.5% |
| RETURN_VALUE | 10,560 | 0.8% |
| LOAD_CONST | 10,560 | 0.8% |
| LOAD_FAST_LOAD_FAST | 4,320 | 0.3% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 758,747 | 97.2% |
| RETURN_VALUE | 20,640 | 2.6% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 771,387 | 98.8% |
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
| RESUME_CHECK | 2,751,177 | 41.8% |
| LOAD_FAST | 923,266 | 14.0% |
| STORE_FAST | 900,691 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 743,794 | 11.3% |
| NOP | 550,052 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,032,582 | 46.1% |
| LOAD_DEREF | 1,345,031 | 20.5% |
| CALL_ISINSTANCE | 903,106 | 13.7% |
| LOAD_GLOBAL_BUILTIN | 743,794 | 11.3% |
| LOAD_GLOBAL_MODULE | 468,960 | 7.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,672,723 | 28.7% |
| RESUME_CHECK | 2,341,709 | 18.3% |
| NOP | 1,354,189 | 10.6% |
| POP_JUMP_IF_FALSE | 1,097,406 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,087,000 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,862,861 | 22.4% |
| LOAD_ATTR_MODULE | 2,716,049 | 21.2% |
| LOAD_FAST_LOAD_FAST | 2,008,669 | 15.7% |
| LOAD_FAST | 1,618,099 | 12.6% |
| COMPARE_OP_STR | 1,065,101 | 8.3% |


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
| LOAD_FAST | 1,277,831 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 900,706 | 70.5% |
| CALL_PY_EXACT_ARGS | 372,805 | 29.2% |
| LOAD_FAST | 4,320 | 0.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 9,379,612 | 33.5% |
| CACHE | 8,852,994 | 31.6% |
| FOR_ITER_GEN | 4,752,000 | 17.0% |
| COPY_FREE_VARS | 1,349,471 | 4.8% |
| CALL_PY_WITH_DEFAULTS | 1,325,203 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,663,348 | 56.0% |
| POP_TOP | 5,184,960 | 18.5% |
| LOAD_GLOBAL_BUILTIN | 2,751,177 | 9.8% |
| LOAD_GLOBAL_MODULE | 2,341,709 | 8.4% |
| NOP | 1,041,346 | 3.7% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,199,698 | 68.2% |
| LOAD_FAST_LOAD_FAST | 569,125 | 17.6% |
| SWAP | 431,987 | 13.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,960 | 0.4% |
| STORE_FAST_LOAD_FAST | 10,560 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,651,060 | 51.2% |
| LOAD_FAST | 684,954 | 21.2% |
| LOAD_GLOBAL_MODULE | 532,165 | 16.5% |
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
| LOAD_ATTR | 890,146 | 93.0% |
| LOAD_FAST | 32,942 | 3.4% |
| LOAD_ATTR_INSTANCE_VALUE | 25,920 | 2.7% |
| CALL | 7,680 | 0.8% |
| LOAD_CONST | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 891,895 | 93.1% |
| RETURN_CONST | 24,480 | 2.6% |
| LOAD_GLOBAL_MODULE | 20,640 | 2.2% |
| LOAD_CONST | 20,640 | 2.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,410,486 | 26.8% |
| CALL_ISINSTANCE | 903,106 | 17.1% |
| RETURN_VALUE | 683,394 | 13.0% |
| CALL | 549,210 | 10.4% |
| LOAD_FAST | 540,278 | 10.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,676,653 | 69.7% |
| POP_JUMP_IF_TRUE | 1,383,508 | 26.2% |
| UNARY_NOT | 212,014 | 4.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,165,138 | 54.9% |
| LOAD_FAST | 890,146 | 22.6% |
| BINARY_OP | 890,146 | 22.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,945,430 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 381,445 | 92.2% |
| LOAD_ATTR_INSTANCE_VALUE | 32,160 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 413,605 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 143,809 | 79.8% |
| LOAD_FAST | 20,640 | 11.4% |
| COPY | 10,560 | 5.9% |
| WITH_EXCEPT_START | 4,320 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,409 | 91.7% |
| POP_JUMP_IF_TRUE | 14,880 | 8.3% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 816,000 | 93.0% |
| CALL_BUILTIN_FAST | 61,006 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 816,000 | 93.0% |
| STORE_FAST | 61,006 | 7.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 436,320 | 27.1% |
| LOAD_FAST_CHECK | 432,000 | 26.8% |
| FOR_ITER_LIST | 384,846 | 23.9% |
| CALL_BUILTIN_FAST | 347,018 | 21.5% |
| CALL | 7,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,607,384 | 99.7% |
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
| STORE_FAST | 480 | 61.6% |
| COPY | 299 | 38.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 480 | 61.6% |
| POP_JUMP_IF_FALSE | 299 | 38.4% |


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
| specialization.deferred |       477878 | 45.7% |
|          hit |       567154 | 54.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 219 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 219 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        22566 | 2.3% |
|          hit |       957655 | 97.7% |

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
| specialization.deferred |      1186949 | 10.8% |
|          hit |      9812278 | 89.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2 | 0.2% |
| Failure | 1,044 | 99.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 325 | 31.1% |
| tuple | 220 | 21.1% |
| sequence | 219 | 21.0% |
| set | 200 | 19.2% |
| other | 80 | 7.7% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5334002 | 77.3% |
|          hit |      1563694 | 22.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 47 | 2.3% |
| Failure | 2,012 | 97.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,002 | 49.8% |
| or | 583 | 29.0% |
| remainder | 227 | 11.3% |
| add different types | 160 | 8.0% |
| add other | 40 | 2.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      8747694 | 29.3% |
| specialization.deopt |           60 | 0.0% |
|          hit |     21098276 | 70.7% |
|         miss |         4380 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 126 | 1.4% |
| Failure | 8,994 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,520 | 28.0% |
| cfunc noargs | 1,785 | 19.8% |
| class no vectorcall | 1,268 | 14.1% |
| meth descr varargs keywords | 838 | 9.3% |
| class mutable | 409 | 4.5% |
| other | 360 | 4.0% |
| cfunc varargs keywords | 329 | 3.7% |
| cfunc varargs | 320 | 3.6% |
| bound method | 285 | 3.2% |
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
| specialization.deferred |       436918 | 10.0% |
| specialization.deopt |           68 | 0.0% |
|          hit |      3927394 | 89.9% |
|         miss |         4820 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 119 | 24.9% |
| Failure | 359 | 75.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 155 | 43.2% |
| different types | 124 | 34.5% |
| big int | 80 | 22.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       976320 | 7.0% |
|          hit |     12882556 | 93.0% |

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
| specialization.deferred |      7775479 | 17.4% |
| specialization.deopt |         4189 | 0.0% |
|          hit |     36621918 | 82.0% |
|         miss |       230312 | 0.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,356 | 42.2% |
| Failure | 5,965 | 57.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,404 | 23.5% |
| shadowed | 1,200 | 20.1% |
| not managed dict | 1,197 | 20.1% |
| non overriding descriptor | 600 | 10.1% |
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
| specialization.deferred |           60 | 0.0% |
| specialization.deopt |           70 | 0.0% |
|          hit |     19377710 | 100.0% |
|         miss |         5776 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 212 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1345031 | 100.0% |


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
| specialization.deferred |        65768 | 2.0% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      3152437 | 93.6% |
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
|          hit |      2489670 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 228,011,247 | 53.0% |
| Not specialized | 60,135,078 | 14.0% |
| Specialized | 141,666,314 | 33.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 8,747,694 | 35.0% |
| LOAD_ATTR | 7,775,479 | 31.1% |
| BINARY_OP | 5,334,002 | 21.3% |
| TO_BOOL | 1,186,949 | 4.7% |
| FOR_ITER | 976,320 | 3.9% |
| BINARY_SUBSCR | 477,878 | 1.9% |
| COMPARE_OP | 436,918 | 1.7% |
| STORE_ATTR | 65,768 | 0.3% |
| STORE_SUBSCR | 22,566 | 0.1% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 160,490 | 40.8% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 37.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,702 | 15.4% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| LOAD_GLOBAL_MODULE | 5,776 | 1.5% |
| COMPARE_OP_INT | 4,820 | 1.2% |
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
| Calls to PyEval_EvalDefault | 8,940,354 | 31.9% |
| Calls to Python functions inlined | 19,045,973 | 68.1% |
| Calls via PyEval_EvalFrame (total) | 8,940,354 | 31.9% |
| Calls via PyEval_EvalFrame (vector) | 8,502,114 | 30.4% |
| Calls via PyEval_EvalFrame (generator) | 438,240 | 1.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,502,114 | 30.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 469,440 | 1.7% |
| Calls via PyEval_EvalFrame (function ex) | 401,400 | 1.4% |
| Calls via PyEval_EvalFrame (api) | 475,284 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 23,583,937 | 84.3% |
| Frame objects created | 37,777 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 15,031,695 | 42.8% |
| Frees to freelist | 15,033,084 |  |
| Allocations | 20,076,853 | 57.2% |
| Allocations to 512 bytes | 19,864,976 | 56.6% |
| Allocations to 4 kbytes | 86,108 | 0.2% |
| Allocations over 4 kbytes | 125,769 | 0.4% |
| Frees | 21,230,217 |  |
| New values | 65,280 |  |
| Interpreter increfs | 168,454,142 | 77.0% |
| Interpreter decrefs | 184,546,345 | 73.7% |
| Increfs | 50,362,372 | 23.0% |
| Decrefs | 65,928,739 | 26.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 9,093,743 |  |
| Method cache misses | 73,652 |  |
| Method cache collisions | 144,457 |  |
| Method cache dunder hits | 8,526,664 |  |
| Method cache dunder misses | 70,805 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 14 | 336 | 89,156 |
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
Stats gathered on: 2023-10-04
