
# Pystats results

- benchmark: concurrent_imap
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 53,153,751 | 17.3% | 17.3% |  |
| RESUME_CHECK | 21,608,484 | 7.0% | 24.3% | 0.0% |
| STORE_FAST | 16,518,486 | 5.4% | 29.7% |  |
| POP_TOP | 14,329,643 | 4.7% | 34.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 14,269,455 | 4.6% | 39.0% | 1.1% |
| RETURN_VALUE | 12,537,487 | 4.1% | 43.0% |  |
| POP_JUMP_IF_FALSE | 9,908,393 | 3.2% | 46.3% |  |
| LOAD_CONST | 9,009,078 | 2.9% | 49.2% |  |
| LOAD_GLOBAL_MODULE | 8,015,344 | 2.6% | 51.8% | 0.0% |
| INTERPRETER_EXIT | 7,920,532 | 2.6% | 54.4% |  |
| LOAD_FAST_LOAD_FAST | 7,684,135 | 2.5% | 56.9% |  |
| CALL | 6,778,719 | 2.2% | 59.1% |  |
| ENTER_EXECUTOR | 6,603,809 | 2.1% | 61.2% |  |
| CALL_PY_EXACT_ARGS | 5,913,754 | 1.9% | 63.1% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,640,349 | 1.8% | 65.0% | 1.1% |
| JUMP_BACKWARD | 5,387,387 | 1.8% | 66.7% |  |
| LOAD_ATTR | 4,896,742 | 1.6% | 68.3% |  |
| YIELD_VALUE | 4,896,480 | 1.6% | 69.9% |  |
| RETURN_CONST | 4,896,185 | 1.6% | 71.5% |  |
| NOP | 4,854,192 | 1.6% | 73.1% |  |
| FOR_ITER_GEN | 4,496,160 | 1.5% | 74.5% |  |
| COPY | 4,483,412 | 1.5% | 76.0% |  |
| PUSH_NULL | 3,914,344 | 1.3% | 77.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,781,052 | 1.2% | 78.5% |  |
| LOAD_GLOBAL_BUILTIN | 3,745,641 | 1.2% | 79.7% |  |
| TO_BOOL_BOOL | 3,720,199 | 1.2% | 80.9% |  |
| STORE_FAST_STORE_FAST | 3,232,260 | 1.1% | 82.0% |  |
| BINARY_OP | 3,159,930 | 1.0% | 83.0% |  |
| POP_JUMP_IF_NOT_NONE | 2,806,991 | 0.9% | 83.9% |  |
| BUILD_TUPLE | 2,701,913 | 0.9% | 84.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 2,404,417 | 0.8% | 85.6% | 6.2% |
| TO_BOOL_INT | 2,317,974 | 0.8% | 86.3% |  |
| COMPARE_OP_INT | 1,992,238 | 0.6% | 87.0% | 0.3% |
| LOAD_ATTR_MODULE | 1,866,902 | 0.6% | 87.6% |  |
| CALL_FUNCTION_EX | 1,730,699 | 0.6% | 88.2% |  |
| POP_JUMP_IF_TRUE | 1,676,016 | 0.5% | 88.7% |  |
| CALL_PY_WITH_DEFAULTS | 1,489,477 | 0.5% | 89.2% |  |
| SWAP | 1,352,511 | 0.4% | 89.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,264,740 | 0.4% | 90.0% |  |
| GET_ITER | 1,247,955 | 0.4% | 90.4% |  |
| BEFORE_WITH | 1,176,997 | 0.4% | 90.8% |  |
| FOR_ITER_LIST | 1,087,424 | 0.4% | 91.2% |  |
| BUILD_MAP | 1,081,770 | 0.4% | 91.5% |  |
| TO_BOOL | 1,048,040 | 0.3% | 91.9% |  |
| COMPARE_OP_STR | 986,005 | 0.3% | 92.2% |  |
| CONTAINS_OP | 928,434 | 0.3% | 92.5% |  |
| JUMP_FORWARD | 920,758 | 0.3% | 92.8% |  |
| FOR_ITER | 914,840 | 0.3% | 93.1% |  |
| STORE_FAST_LOAD_FAST | 898,080 | 0.3% | 93.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 852,556 | 0.3% | 93.7% |  |
| LOAD_DEREF | 839,484 | 0.3% | 93.9% |  |
| UNPACK_SEQUENCE_TUPLE | 828,231 | 0.3% | 94.2% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 819,831 | 0.3% | 94.5% |  |
| BINARY_OP_ADD_INT | 808,788 | 0.3% | 94.7% |  |
| COPY_FREE_VARS | 803,604 | 0.3% | 95.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 783,552 | 0.3% | 95.2% |  |
| CALL_BUILTIN_FAST | 766,902 | 0.2% | 95.5% |  |
| LOAD_SUPER_ATTR_METHOD | 758,124 | 0.2% | 95.7% |  |
| UNARY_INVERT | 756,672 | 0.2% | 96.0% |  |
| CALL_BUILTIN_CLASS | 748,818 | 0.2% | 96.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 747,466 | 0.2% | 96.5% |  |
| BUILD_LIST | 698,667 | 0.2% | 96.7% |  |
| CALL_METHOD_DESCRIPTOR_O | 620,296 | 0.2% | 96.9% |  |
| STORE_SUBSCR_DICT | 584,176 | 0.2% | 97.1% |  |
| POP_JUMP_IF_NONE | 577,099 | 0.2% | 97.3% |  |
| CALL_ISINSTANCE | 532,674 | 0.2% | 97.5% |  |
| LOAD_FAST_CHECK | 526,310 | 0.2% | 97.6% |  |
| EXIT_INIT_CHECK | 497,460 | 0.2% | 97.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 497,460 | 0.2% | 97.9% |  |
| LOAD_ATTR_PROPERTY | 480,178 | 0.2% | 98.1% | 1.9% |
| BINARY_SUBSCR | 441,542 | 0.1% | 98.2% |  |
| DICT_MERGE | 420,720 | 0.1% | 98.4% |  |
| CALL_TUPLE_1 | 412,560 | 0.1% | 98.5% |  |
| LIST_APPEND | 388,375 | 0.1% | 98.6% |  |
| LOAD_FAST_AND_CLEAR | 351,486 | 0.1% | 98.8% |  |
| CALL_LEN | 294,462 | 0.1% | 98.9% |  |
| COMPARE_OP | 263,142 | 0.1% | 98.9% |  |
| TO_BOOL_LIST | 262,170 | 0.1% | 99.0% |  |
| LIST_EXTEND | 212,736 | 0.1% | 99.1% |  |
| CALL_KW | 184,204 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 182,124 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 168,882 | 0.1% | 99.3% |  |
| BINARY_OP_SUBTRACT_INT | 159,781 | 0.1% | 99.3% |  |
| UNARY_NOT | 137,347 | 0.0% | 99.4% |  |
| CALL_LIST_APPEND | 126,279 | 0.0% | 99.4% |  |
| FOR_ITER_RANGE | 123,980 | 0.0% | 99.4% |  |
| BINARY_OP_ADD_FLOAT | 118,362 | 0.0% | 99.5% |  |
| BINARY_SUBSCR_LIST_INT | 114,288 | 0.0% | 99.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 106,491 | 0.0% | 99.6% |  |
| STORE_DEREF | 99,600 | 0.0% | 99.6% |  |
| MAKE_CELL | 99,600 | 0.0% | 99.6% |  |
| CALL_BUILTIN_O | 82,080 | 0.0% | 99.6% |  |
| BINARY_SUBSCR_DICT | 81,120 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_STR_INT | 72,960 | 0.0% | 99.7% |  |
| BINARY_OP_MULTIPLY_FLOAT | 72,960 | 0.0% | 99.7% |  |
| STORE_ATTR | 62,325 | 0.0% | 99.7% |  |
| DELETE_ATTR | 61,224 | 0.0% | 99.8% |  |
| DELETE_SUBSCR | 56,176 | 0.0% | 99.8% |  |
| STORE_ATTR_SLOT | 46,320 | 0.0% | 99.8% |  |
| LOAD_ATTR_SLOT | 46,320 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 43,911 | 0.0% | 99.8% |  |
| MAKE_FUNCTION | 41,280 | 0.0% | 99.8% |  |
| LOAD_SUPER_ATTR_ATTR | 41,280 | 0.0% | 99.8% |  |
| FORMAT_SIMPLE | 38,160 | 0.0% | 99.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 32,827 | 0.0% | 99.9% | 12.6% |
| IS_OP | 32,786 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 31,680 | 0.0% | 99.9% |  |
| BUILD_STRING | 29,040 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 27,600 | 0.0% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 25,920 | 0.0% | 99.9% |  |
| PUSH_EXC_INFO | 25,399 | 0.0% | 99.9% |  |
| POP_EXCEPT | 25,399 | 0.0% | 99.9% |  |
| IMPORT_NAME | 21,840 | 0.0% | 99.9% |  |
| IMPORT_FROM | 21,840 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 21,319 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 21,104 | 0.0% | 100.0% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 19,920 | 0.0% | 100.0% |  |
| CONVERT_VALUE | 18,240 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 12,720 | 0.0% | 100.0% |  |
| BINARY_SLICE | 12,720 | 0.0% | 100.0% |  |
| RERAISE | 12,240 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 8,800 | 0.0% | 100.0% |  |
| END_FOR | 8,160 | 0.0% | 100.0% |  |
| CALL_STR_1 | 8,160 | 0.0% | 100.0% |  |
| WITH_EXCEPT_START | 4,080 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 4,080 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 960 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 480 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 386 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 227 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 13,055,634 | 4.2% | 4.2% |
| RESUME_CHECK LOAD_FAST | 12,349,786 | 4.0% | 8.3% |
| CACHE RESUME_CHECK | 7,865,564 | 2.6% | 10.8% |
| RETURN_VALUE INTERPRETER_EXIT | 7,036,978 | 2.3% | 13.1% |
| LOAD_FAST RETURN_VALUE | 6,500,112 | 2.1% | 15.2% |
| STORE_FAST LOAD_FAST | 6,392,151 | 2.1% | 17.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 5,881,114 | 1.9% | 19.2% |
| POP_TOP ENTER_EXECUTOR | 5,033,314 | 1.6% | 20.8% |
| RESUME_CHECK POP_TOP | 4,896,480 | 1.6% | 22.4% |
| YIELD_VALUE STORE_FAST | 4,488,000 | 1.5% | 23.9% |
| JUMP_BACKWARD FOR_ITER_GEN | 4,488,000 | 1.5% | 25.4% |
| FOR_ITER_GEN RESUME_CHECK | 4,488,000 | 1.5% | 26.8% |
| STORE_FAST JUMP_BACKWARD | 4,080,000 | 1.3% | 28.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 4,075,503 | 1.3% | 29.5% |
| POP_TOP LOAD_FAST | 3,805,327 | 1.2% | 30.7% |
| ENTER_EXECUTOR YIELD_VALUE | 3,672,000 | 1.2% | 31.9% |
| LOAD_FAST LOAD_ATTR | 3,589,586 | 1.2% | 33.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,546,312 | 1.2% | 34.2% |
| RETURN_CONST POP_TOP | 3,403,006 | 1.1% | 35.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 3,338,494 | 1.1% | 36.4% |
| NOP LOAD_FAST | 2,880,778 | 0.9% | 37.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 2,801,398 | 0.9% | 38.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 2,463,626 | 0.8% | 39.1% |
| LOAD_CONST LOAD_CONST | 2,398,072 | 0.8% | 39.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,317,974 | 0.8% | 40.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,252,722 | 0.7% | 41.3% |
| PUSH_NULL LOAD_FAST | 2,234,140 | 0.7% | 42.0% |
| STORE_FAST NOP | 2,197,803 | 0.7% | 42.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,181,797 | 0.7% | 43.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,170,812 | 0.7% | 44.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,991,055 | 0.6% | 44.8% |
| COPY STORE_FAST | 1,948,320 | 0.6% | 45.5% |
| STORE_FAST COPY | 1,948,080 | 0.6% | 46.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,923,284 | 0.6% | 46.7% |
| LOAD_FAST LOAD_CONST | 1,898,975 | 0.6% | 47.3% |
| CALL STORE_FAST | 1,843,509 | 0.6% | 47.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,783,278 | 0.6% | 48.5% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,752,751 | 0.6% | 49.1% |
| LOAD_CONST CALL | 1,704,377 | 0.6% | 49.6% |
| LOAD_FAST PUSH_NULL | 1,698,069 | 0.6% | 50.2% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,679,421 | 0.5% | 50.7% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,603,714 | 0.5% | 51.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,572,667 | 0.5% | 51.8% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,563,239 | 0.5% | 52.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,545,620 | 0.5% | 52.8% |
| LOAD_ATTR LOAD_FAST | 1,476,853 | 0.5% | 53.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,458,316 | 0.5% | 53.7% |
| CALL RETURN_VALUE | 1,421,634 | 0.5% | 54.2% |
| CALL POP_TOP | 1,404,526 | 0.5% | 54.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,401,646 | 0.5% | 55.1% |
| LOAD_FAST CALL_FUNCTION_EX | 1,309,979 | 0.4% | 55.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,301,540 | 0.4% | 56.0% |
| COPY TO_BOOL_INT | 1,277,106 | 0.4% | 56.4% |
| BINARY_OP COPY | 1,277,106 | 0.4% | 56.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,260,180 | 0.4% | 57.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,253,540 | 0.4% | 57.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,242,968 | 0.4% | 58.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,188,356 | 0.4% | 58.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,153,266 | 0.4% | 58.8% |
| POP_TOP RETURN_CONST | 1,132,668 | 0.4% | 59.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,119,226 | 0.4% | 59.5% |
| POP_TOP LOAD_CONST | 1,114,609 | 0.4% | 59.9% |
| RETURN_VALUE STORE_FAST | 1,053,673 | 0.3% | 60.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,048,920 | 0.3% | 60.5% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,028,238 | 0.3% | 60.9% |
| LOAD_FAST_LOAD_FAST CALL | 1,022,162 | 0.3% | 61.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,017,366 | 0.3% | 61.5% |
| LOAD_FAST TO_BOOL | 1,009,765 | 0.3% | 61.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 992,997 | 0.3% | 62.2% |
| LOAD_CONST LOAD_FAST | 982,555 | 0.3% | 62.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 973,554 | 0.3% | 62.8% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 969,043 | 0.3% | 63.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 962,854 | 0.3% | 63.5% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 959,808 | 0.3% | 63.8% |
| BEFORE_WITH POP_TOP | 948,427 | 0.3% | 64.1% |
| LOAD_GLOBAL_MODULE COMPARE_OP_STR | 942,313 | 0.3% | 64.4% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 941,742 | 0.3% | 64.7% |
| LOAD_FAST BUILD_TUPLE | 938,114 | 0.3% | 65.0% |
| LOAD_CONST COMPARE_OP_INT | 929,319 | 0.3% | 65.3% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 928,434 | 0.3% | 65.6% |
| LOAD_ATTR_INSTANCE_VALUE CONTAINS_OP | 928,422 | 0.3% | 65.9% |
| LOAD_ATTR PUSH_NULL | 906,947 | 0.3% | 66.2% |
| CALL_FUNCTION_EX RETURN_VALUE | 896,819 | 0.3% | 66.5% |
| JUMP_BACKWARD FOR_ITER | 893,040 | 0.3% | 66.8% |
| LOAD_ATTR_INSTANCE_VALUE BEFORE_WITH | 888,659 | 0.3% | 67.1% |
| RETURN_VALUE RETURN_VALUE | 873,429 | 0.3% | 67.3% |
| GET_ITER FOR_ITER_LIST | 862,020 | 0.3% | 67.6% |
| POP_TOP NOP | 848,991 | 0.3% | 67.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 839,540 | 0.3% | 68.2% |
| NOP LOAD_GLOBAL_MODULE | 829,115 | 0.3% | 68.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 821,040 | 0.3% | 68.7% |
| POP_TOP JUMP_BACKWARD | 817,254 | 0.3% | 69.0% |
| BUILD_TUPLE YIELD_VALUE | 816,000 | 0.3% | 69.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 814,772 | 0.3% | 69.5% |
| COPY_FREE_VARS RESUME_CHECK | 803,604 | 0.3% | 69.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 803,426 | 0.3% | 70.0% |
| LOAD_CONST COPY | 800,640 | 0.3% | 70.3% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 799,404 | 0.3% | 70.6% |
| LOAD_DEREF LOAD_FAST | 799,404 | 0.3% | 70.8% |
| COPY STORE_FAST_STORE_FAST | 796,080 | 0.3% | 71.1% |


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
| RESUME_CHECK | 7,865,564 | 99.3% |
| COPY_FREE_VARS | 54,480 | 0.7% |
| POP_TOP | 4,560 | 0.1% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 888,659 | 75.5% |
| RETURN_VALUE | 224,490 | 19.1% |
| LOAD_GLOBAL_MODULE | 59,768 | 5.1% |
| CALL | 4,080 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 948,427 | 80.6% |
| STORE_FAST | 228,570 | 19.4% |


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
| LOAD_FAST_LOAD_FAST | 408,000 | 92.4% |
| LOAD_CONST | 33,319 | 7.5% |
| BINARY_SUBSCR | 223 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 408,000 | 92.4% |
| STORE_FAST | 33,319 | 7.5% |
| BINARY_SUBSCR | 223 | 0.1% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 17,479 | 82.0% |
| LOAD_ATTR_MODULE | 3,840 | 18.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 21,319 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,608 | 49.1% |
| CALL | 19,928 | 35.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8,639 | 15.4% |
| LOAD_ATTR | 1 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 43,928 | 78.2% |
| RETURN_CONST | 7,688 | 13.7% |
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
| RETURN_CONST | 497,460 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 497,460 | 100.0% |


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
| LOAD_FAST | 694,227 | 55.6% |
| STORE_FAST_LOAD_FAST | 408,000 | 32.7% |
| CALL_BUILTIN_CLASS | 127,968 | 10.3% |
| CALL | 9,120 | 0.7% |
| RETURN_VALUE | 4,080 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 862,020 | 69.1% |
| LOAD_FAST_AND_CLEAR | 233,367 | 18.7% |
| FOR_ITER_RANGE | 123,528 | 9.9% |
| FOR_ITER_TUPLE | 8,160 | 0.7% |
| FOR_ITER_GEN | 8,160 | 0.7% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,036,978 | 88.8% |
| RETURN_CONST | 475,074 | 6.0% |
| YIELD_VALUE | 408,480 | 5.2% |

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
| STORE_FAST | 2,197,803 | 45.3% |
| POP_TOP | 848,991 | 17.5% |
| POP_JUMP_IF_FALSE | 758,746 | 15.6% |
| RESUME_CHECK | 665,154 | 13.7% |
| POP_JUMP_IF_NOT_NONE | 229,610 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,880,778 | 59.3% |
| LOAD_GLOBAL_MODULE | 829,115 | 17.1% |
| LOAD_FAST_LOAD_FAST | 412,560 | 8.5% |
| LOAD_CONST | 396,240 | 8.2% |
| LOAD_GLOBAL_BUILTIN | 327,458 | 6.7% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 13,399 | 52.8% |
| COPY | 8,160 | 32.1% |
| POP_TOP | 3,840 | 15.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 13,399 | 52.8% |
| RERAISE | 8,160 | 32.1% |
| JUMP_FORWARD | 3,840 | 15.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,896,480 | 34.2% |
| RETURN_CONST | 3,403,006 | 23.7% |
| CALL | 1,404,526 | 9.8% |
| BEFORE_WITH | 948,427 | 6.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 783,120 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,033,314 | 35.1% |
| LOAD_FAST | 3,805,327 | 26.6% |
| RETURN_CONST | 1,132,668 | 7.9% |
| LOAD_CONST | 1,114,609 | 7.8% |
| NOP | 848,991 | 5.9% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 17,479 | 68.8% |
| RERAISE | 4,080 | 16.1% |
| CALL_KW | 3,840 | 15.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 17,479 | 68.8% |
| WITH_EXCEPT_START | 4,080 | 16.1% |
| LOAD_GLOBAL_MODULE | 3,840 | 15.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,698,069 | 43.4% |
| LOAD_ATTR_MODULE | 1,242,968 | 31.8% |
| LOAD_ATTR | 906,947 | 23.2% |
| LOAD_SUPER_ATTR_ATTR | 41,280 | 1.1% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,234,140 | 57.1% |
| LOAD_FAST_LOAD_FAST | 941,742 | 24.1% |
| CALL | 510,194 | 13.0% |
| LOAD_CONST | 177,593 | 4.5% |
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
| LOAD_FAST | 6,500,112 | 51.8% |
| CALL | 1,421,634 | 11.3% |
| CALL_FUNCTION_EX | 896,819 | 7.2% |
| RETURN_VALUE | 873,429 | 7.0% |
| LOAD_ATTR_INSTANCE_VALUE | 738,660 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,036,978 | 56.1% |
| STORE_FAST | 1,053,673 | 8.4% |
| RETURN_VALUE | 873,429 | 7.0% |
| POP_TOP | 675,952 | 5.4% |
| LOAD_FAST_LOAD_FAST | 520,434 | 4.2% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 9,120 | 43.2% |
| LOAD_FAST | 7,704 | 36.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,080 | 19.3% |
| STORE_SUBSCR | 200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 13,200 | 62.5% |
| LOAD_GLOBAL_MODULE | 7,680 | 36.4% |
| STORE_SUBSCR | 200 | 0.9% |
| STORE_SUBSCR_DICT | 12 | 0.1% |
| LOAD_FAST | 12 | 0.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,009,765 | 96.3% |
| LOAD_ATTR_INSTANCE_VALUE | 37,218 | 3.6% |
| TO_BOOL | 1,046 | 0.1% |
| COPY | 5 | 0.0% |
| RETURN_VALUE | 3 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 534,282 | 51.0% |
| POP_JUMP_IF_FALSE | 512,703 | 48.9% |
| TO_BOOL | 1,046 | 0.1% |
| TO_BOOL_ALWAYS_TRUE | 5 | 0.0% |
| TO_BOOL_BOOL | 4 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 520,434 | 68.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 236,238 | 31.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 756,672 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 137,347 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 137,347 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 1,679,421 | 53.1% |
| UNARY_INVERT | 756,672 | 23.9% |
| POP_JUMP_IF_FALSE | 520,434 | 16.5% |
| LOAD_ATTR | 127,239 | 4.0% |
| LOAD_FAST_LOAD_FAST | 37,200 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,277,106 | 40.4% |
| STORE_FAST | 647,673 | 20.5% |
| UNARY_INVERT | 520,434 | 16.5% |
| TO_BOOL_INT | 520,434 | 16.5% |
| BUILD_TUPLE | 118,119 | 3.7% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 233,367 | 33.4% |
| JUMP_FORWARD | 224,490 | 32.1% |
| LOAD_FAST | 118,362 | 16.9% |
| POP_TOP | 106,128 | 15.2% |
| STORE_ATTR_INSTANCE_VALUE | 7,680 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 236,490 | 33.8% |
| SWAP | 233,367 | 33.4% |
| STORE_FAST | 224,970 | 32.2% |
| RETURN_VALUE | 3,840 | 0.5% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 408,000 | 37.7% |
| LOAD_FAST | 396,240 | 36.6% |
| RESUME_CHECK | 232,170 | 21.5% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 2.3% |
| POP_JUMP_IF_NOT_NONE | 12,240 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 661,530 | 61.2% |
| BUILD_TUPLE | 408,000 | 37.7% |
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
| LOAD_FAST | 938,114 | 34.7% |
| LOAD_FAST_LOAD_FAST | 821,040 | 30.4% |
| BUILD_MAP | 408,000 | 15.1% |
| RETURN_VALUE | 384,000 | 14.2% |
| BINARY_OP | 118,119 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 816,000 | 30.2% |
| CALL | 520,914 | 19.3% |
| BUILD_MAP | 408,000 | 15.1% |
| STORE_FAST | 384,000 | 14.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 384,000 | 14.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,704,377 | 25.1% |
| LOAD_FAST_LOAD_FAST | 1,022,162 | 15.1% |
| LOAD_ATTR_METHOD_NO_DICT | 992,997 | 14.6% |
| ENTER_EXECUTOR | 785,179 | 11.6% |
| BUILD_TUPLE | 520,914 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,843,509 | 27.2% |
| RETURN_VALUE | 1,421,634 | 21.0% |
| POP_TOP | 1,404,526 | 20.7% |
| LOAD_FAST | 542,892 | 8.0% |
| TO_BOOL_BOOL | 510,174 | 7.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,309,979 | 75.7% |
| DICT_MERGE | 420,720 | 24.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 896,819 | 51.8% |
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
| LOAD_CONST | 180,204 | 97.8% |
| ENTER_EXECUTOR | 4,000 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 137,088 | 74.4% |
| LOAD_FAST | 20,400 | 11.1% |
| RETURN_VALUE | 13,680 | 7.4% |
| STORE_FAST | 9,120 | 5.0% |
| PUSH_EXC_INFO | 3,840 | 2.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 262,125 | 99.6% |
| LOAD_ATTR_INSTANCE_VALUE | 609 | 0.2% |
| COMPARE_OP | 309 | 0.1% |
| COMPARE_OP_INT | 77 | 0.0% |
| LOAD_GLOBAL_MODULE | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 262,690 | 99.8% |
| COMPARE_OP | 309 | 0.1% |
| COMPARE_OP_INT | 126 | 0.0% |
| COMPARE_OP_STR | 12 | 0.0% |
| POP_JUMP_IF_TRUE | 5 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 928,422 | 100.0% |
| LOAD_ATTR | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 928,434 | 100.0% |


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
| STORE_FAST | 1,948,080 | 43.5% |
| BINARY_OP | 1,277,106 | 28.5% |
| LOAD_CONST | 800,640 | 17.9% |
| LOAD_FAST | 417,120 | 9.3% |
| STORE_ATTR_INSTANCE_VALUE | 13,680 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,948,320 | 43.5% |
| TO_BOOL_INT | 1,277,106 | 28.5% |
| STORE_FAST_STORE_FAST | 796,080 | 17.8% |
| LOAD_ATTR_INSTANCE_VALUE | 407,976 | 9.1% |
| LOAD_FAST | 18,240 | 0.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 520,434 | 64.8% |
| CALL_ALLOC_AND_ENTER_INIT | 224,490 | 27.9% |
| CACHE | 54,480 | 6.8% |
| CALL | 4,080 | 0.5% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 803,604 | 100.0% |


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,224 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,816 | 66.7% |
| RETURN_CONST | 19,928 | 32.5% |
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
| POP_TOP | 5,033,314 | 76.2% |
| POP_JUMP_IF_NOT_NONE | 596,256 | 9.0% |
| STORE_FAST_STORE_FAST | 408,000 | 6.2% |
| LIST_APPEND | 315,415 | 4.8% |
| POP_JUMP_IF_FALSE | 119,012 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 3,672,000 | 55.6% |
| CALL | 785,179 | 11.9% |
| LOAD_FAST | 456,477 | 6.9% |
| LOAD_ATTR_MODULE | 408,480 | 6.2% |
| JUMP_BACKWARD | 408,000 | 6.2% |


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
| RETURN_VALUE | 19,920 | 60.8% |
| LOAD_FAST | 12,240 | 37.3% |
| LOAD_GLOBAL_MODULE | 626 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 32,786 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,080,000 | 75.7% |
| POP_TOP | 817,254 | 15.2% |
| ENTER_EXECUTOR | 408,000 | 7.6% |
| LIST_APPEND | 72,960 | 1.4% |
| POP_JUMP_IF_TRUE | 4,405 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 4,488,000 | 83.3% |
| FOR_ITER | 893,040 | 16.6% |
| LOAD_FAST | 4,448 | 0.1% |
| FOR_ITER_LIST | 1,157 | 0.0% |
| FOR_ITER_RANGE | 452 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 481,224 | 52.3% |
| POP_TOP | 427,054 | 46.4% |
| STORE_ATTR_INSTANCE_VALUE | 4,560 | 0.5% |
| BINARY_SUBSCR_TUPLE_INT | 4,080 | 0.4% |
| POP_EXCEPT | 3,840 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 653,341 | 71.0% |
| BUILD_LIST | 224,490 | 24.4% |
| LOAD_GLOBAL_MODULE | 17,048 | 1.9% |
| POP_EXCEPT | 13,399 | 1.5% |
| LOAD_FAST_LOAD_FAST | 4,560 | 0.5% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 197,296 | 50.8% |
| LOAD_ATTR | 118,119 | 30.4% |
| BINARY_SUBSCR_STR_INT | 72,960 | 18.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 315,415 | 81.2% |
| JUMP_BACKWARD | 72,960 | 18.8% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 106,608 | 50.1% |
| RETURN_VALUE | 106,128 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 106,368 | 50.0% |
| STORE_FAST | 106,128 | 49.9% |
| RETURN_VALUE | 240 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,589,586 | 73.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,153,266 | 23.6% |
| LOAD_GLOBAL_MODULE | 88,911 | 1.8% |
| CALL | 37,200 | 0.8% |
| LOAD_FAST_LOAD_FAST | 13,224 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,476,853 | 30.2% |
| PUSH_NULL | 906,947 | 18.5% |
| STORE_SUBSCR_DICT | 520,434 | 10.6% |
| POP_JUMP_IF_NOT_NONE | 514,931 | 10.5% |
| STORE_FAST | 354,072 | 7.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,398,072 | 26.6% |
| LOAD_FAST | 1,898,975 | 21.1% |
| POP_TOP | 1,114,609 | 12.4% |
| POP_JUMP_IF_FALSE | 587,228 | 6.5% |
| LOAD_ATTR_METHOD_NO_DICT | 513,482 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,398,072 | 26.6% |
| CALL | 1,704,377 | 18.9% |
| LOAD_FAST | 982,555 | 10.9% |
| COMPARE_OP_INT | 929,319 | 10.3% |
| COPY | 800,640 | 8.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 799,404 | 95.2% |
| STORE_DEREF | 19,920 | 2.4% |
| POP_JUMP_IF_NOT_NONE | 19,920 | 2.4% |
| STORE_FAST | 120 | 0.0% |
| NOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 799,404 | 95.2% |
| POP_JUMP_IF_NOT_NONE | 39,840 | 4.7% |
| STORE_FAST | 120 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,349,786 | 23.2% |
| STORE_FAST | 6,392,151 | 12.0% |
| POP_JUMP_IF_FALSE | 4,075,503 | 7.7% |
| POP_TOP | 3,805,327 | 7.2% |
| NOP | 2,880,778 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 13,055,634 | 24.6% |
| RETURN_VALUE | 6,500,112 | 12.2% |
| LOAD_ATTR | 3,589,586 | 6.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,546,312 | 6.7% |
| CALL_PY_EXACT_ARGS | 2,252,722 | 4.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 233,367 | 66.4% |
| LOAD_FAST_AND_CLEAR | 118,119 | 33.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 233,367 | 66.4% |
| LOAD_FAST_AND_CLEAR | 118,119 | 33.6% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 408,000 | 77.5% |
| POP_JUMP_IF_NONE | 106,371 | 20.2% |
| LOAD_ATTR_CLASS | 11,939 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 408,000 | 77.5% |
| LOAD_GLOBAL_MODULE | 106,371 | 20.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 11,939 | 2.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,188,356 | 15.5% |
| LOAD_FAST_LOAD_FAST | 973,554 | 12.7% |
| PUSH_NULL | 941,742 | 12.3% |
| POP_JUMP_IF_FALSE | 673,267 | 8.8% |
| STORE_FAST_STORE_FAST | 606,342 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,572,667 | 20.5% |
| CALL | 1,022,162 | 13.3% |
| LOAD_FAST_LOAD_FAST | 973,554 | 12.7% |
| BUILD_TUPLE | 821,040 | 10.7% |
| LOAD_ATTR_INSTANCE_VALUE | 778,906 | 10.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 35.2% |
| RESUME_CHECK | 40 | 17.6% |
| POP_JUMP_IF_FALSE | 40 | 17.6% |
| POP_JUMP_IF_TRUE | 28 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 17 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 128 | 56.4% |
| LOAD_ATTR | 48 | 21.1% |
| LOAD_GLOBAL_BUILTIN | 43 | 18.9% |
| COMPARE_OP | 5 | 2.2% |
| LOAD_FAST | 3 | 1.3% |


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
| TO_BOOL_BOOL | 2,463,626 | 24.9% |
| TO_BOOL_INT | 2,317,974 | 23.4% |
| COMPARE_OP_INT | 1,991,055 | 20.1% |
| COMPARE_OP_STR | 959,808 | 9.7% |
| CONTAINS_OP | 928,434 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,075,503 | 41.1% |
| RETURN_CONST | 1,752,751 | 17.7% |
| NOP | 758,746 | 7.7% |
| LOAD_GLOBAL_MODULE | 693,189 | 7.0% |
| LOAD_FAST_LOAD_FAST | 673,267 | 6.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 537,499 | 93.1% |
| LOAD_ATTR_INSTANCE_VALUE | 20,880 | 3.6% |
| LOAD_ATTR | 18,240 | 3.2% |
| RETURN_VALUE | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,632 | 27.7% |
| LOAD_GLOBAL_MODULE | 143,463 | 24.9% |
| NOP | 133,728 | 23.2% |
| LOAD_FAST_CHECK | 106,371 | 18.4% |
| RETURN_CONST | 16,800 | 2.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,603,714 | 57.1% |
| LOAD_ATTR | 514,931 | 18.3% |
| LOAD_ATTR_INSTANCE_VALUE | 436,010 | 15.5% |
| RETURN_VALUE | 197,536 | 7.0% |
| LOAD_DEREF | 39,840 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,253,540 | 44.7% |
| ENTER_EXECUTOR | 596,256 | 21.2% |
| RETURN_CONST | 515,077 | 18.3% |
| NOP | 229,610 | 8.2% |
| LOAD_CONST | 106,128 | 3.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,119,226 | 66.8% |
| TO_BOOL | 534,282 | 31.9% |
| TO_BOOL_NONE | 13,200 | 0.8% |
| COMPARE_OP_STR | 7,957 | 0.5% |
| COMPARE_OP_INT | 1,106 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680,766 | 40.6% |
| LOAD_FAST_LOAD_FAST | 535,719 | 32.0% |
| RETURN_CONST | 349,553 | 20.9% |
| LOAD_GLOBAL_MODULE | 41,690 | 2.5% |
| RETURN_VALUE | 33,319 | 2.0% |


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
| POP_JUMP_IF_FALSE | 1,752,751 | 35.8% |
| POP_TOP | 1,132,668 | 23.1% |
| STORE_ATTR_INSTANCE_VALUE | 1,048,920 | 21.4% |
| POP_JUMP_IF_NOT_NONE | 515,077 | 10.5% |
| POP_JUMP_IF_TRUE | 349,553 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,403,006 | 69.5% |
| EXIT_INIT_CHECK | 497,460 | 10.2% |
| INTERPRETER_EXIT | 475,074 | 9.7% |
| TO_BOOL_BOOL | 459,646 | 9.4% |
| STORE_FAST | 33,799 | 0.7% |


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
| LOAD_FAST | 36,241 | 58.1% |
| LOAD_FAST_LOAD_FAST | 13,200 | 21.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,240 | 19.6% |
| STORE_ATTR | 620 | 1.0% |
| SWAP | 24 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 32,160 | 51.6% |
| LOAD_FAST_LOAD_FAST | 9,120 | 14.6% |
| LOAD_FAST | 8,172 | 13.1% |
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
| YIELD_VALUE | 4,488,000 | 27.2% |
| COPY | 1,948,320 | 11.8% |
| CALL | 1,843,509 | 11.2% |
| RETURN_VALUE | 1,053,673 | 6.4% |
| STORE_FAST_STORE_FAST | 792,000 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,392,151 | 38.7% |
| JUMP_BACKWARD | 4,080,000 | 24.7% |
| NOP | 2,197,803 | 13.3% |
| COPY | 1,948,080 | 11.8% |
| JUMP_FORWARD | 481,224 | 2.9% |


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
| UNPACK_SEQUENCE_TWO_TUPLE | 1,260,180 | 39.0% |
| COPY | 796,080 | 24.6% |
| UNPACK_SEQUENCE_TUPLE | 792,000 | 24.5% |
| STORE_FAST_STORE_FAST | 384,000 | 11.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,028,238 | 31.8% |
| STORE_FAST | 792,000 | 24.5% |
| LOAD_FAST_LOAD_FAST | 606,342 | 18.8% |
| ENTER_EXECUTOR | 408,000 | 12.6% |
| STORE_FAST_STORE_FAST | 384,000 | 11.9% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 407,988 | 30.2% |
| LOAD_FAST_AND_CLEAR | 233,367 | 17.3% |
| BUILD_LIST | 233,367 | 17.3% |
| ENTER_EXECUTOR | 224,247 | 16.6% |
| LOAD_FAST | 126,291 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 407,976 | 30.2% |
| LOAD_CONST | 244,410 | 18.1% |
| STORE_FAST | 233,367 | 17.3% |
| BUILD_LIST | 233,367 | 17.3% |
| FOR_ITER_LIST | 224,247 | 16.6% |


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
| LOAD_FAST | 118,362 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 118,362 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 796,056 | 98.4% |
| LOAD_FAST_LOAD_FAST | 12,720 | 1.6% |
| BINARY_OP | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 407,988 | 50.4% |
| STORE_FAST | 384,000 | 47.5% |
| BINARY_SLICE | 12,720 | 1.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,080 | 0.5% |


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
| CALL | 106,371 | 99.9% |
| LOAD_FAST | 80 | 0.1% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 106,491 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 122,382 | 76.6% |
| LOAD_CONST | 33,319 | 20.9% |
| CALL_LEN | 4,080 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 155,701 | 97.4% |
| CALL_BUILTIN_CLASS | 4,080 | 2.6% |


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
| LOAD_FAST_LOAD_FAST | 106,128 | 92.9% |
| LOAD_CONST | 8,160 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 106,128 | 92.9% |
| LOAD_CONST | 8,160 | 7.1% |


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
| LOAD_GLOBAL_MODULE | 244,410 | 49.1% |
| LOAD_FAST | 229,050 | 46.0% |
| CALL | 24,000 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 272,970 | 54.9% |
| COPY_FREE_VARS | 224,490 | 45.1% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,000 | 73.1% |
| LOAD_CONST | 4,400 | 13.4% |
| BINARY_OP_ADD_INT | 4,080 | 12.4% |
| PUSH_NULL | 275 | 0.8% |
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
| CALL_FUNCTION_EX | 384,000 | 51.3% |
| LOAD_FAST | 130,922 | 17.5% |
| CALL_LEN | 106,128 | 14.2% |
| CALL_BUILTIN_CLASS | 106,128 | 14.2% |
| LOAD_CONST | 9,360 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 502,362 | 67.1% |
| GET_ITER | 127,968 | 17.1% |
| CALL_BUILTIN_CLASS | 106,128 | 14.2% |
| LOAD_FAST | 12,240 | 1.6% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 395,120 | 51.5% |
| LOAD_CONST | 218,928 | 28.5% |
| LOAD_FAST_LOAD_FAST | 80,142 | 10.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 36,231 | 4.7% |
| LOAD_GLOBAL_MODULE | 18,240 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 269,541 | 35.1% |
| TO_BOOL_BOOL | 213,408 | 27.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 198,342 | 25.9% |
| UNPACK_SEQUENCE_TUPLE | 36,231 | 4.7% |
| POP_TOP | 9,300 | 1.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 386,400 | 47.1% |
| BUILD_TUPLE | 384,000 | 46.8% |
| CALL | 24,292 | 3.0% |
| LOAD_FAST_CHECK | 11,939 | 1.5% |
| LOAD_ATTR | 9,120 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 783,120 | 95.5% |
| RETURN_VALUE | 36,231 | 4.4% |
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
| LOAD_GLOBAL_BUILTIN | 532,674 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 532,674 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 274,539 | 93.2% |
| LOAD_ATTR_INSTANCE_VALUE | 19,920 | 6.8% |
| CALL | 3 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 155,982 | 53.0% |
| CALL_BUILTIN_CLASS | 106,128 | 36.0% |
| CALL_PY_EXACT_ARGS | 24,000 | 8.2% |
| LOAD_FAST | 4,080 | 1.4% |
| BINARY_OP_SUBTRACT_INT | 4,080 | 1.4% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 118,119 | 93.5% |
| LOAD_FAST | 8,160 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 118,119 | 93.5% |
| LOAD_GLOBAL_MODULE | 8,160 | 6.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 744,924 | 99.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,050 | 0.3% |
| LOAD_CONST | 480 | 0.1% |
| CALL | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 520,434 | 69.6% |
| STORE_FAST | 226,552 | 30.3% |
| TO_BOOL_NONE | 480 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,600 | 87.1% |
| BUILD_TUPLE | 4,080 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 23,520 | 74.2% |
| LOAD_FAST | 8,160 | 25.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 803,426 | 94.2% |
| LOAD_ATTR_METHOD_LAZY_DICT | 48,170 | 5.7% |
| LOAD_ATTR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 408,000 | 47.9% |
| POP_TOP | 304,328 | 35.7% |
| LOAD_FAST | 37,680 | 4.4% |
| RETURN_VALUE | 36,598 | 4.3% |
| CALL_BUILTIN_FAST | 36,231 | 4.2% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 568,439 | 91.6% |
| LOAD_CONST | 21,840 | 3.5% |
| CALL | 20,417 | 3.3% |
| RETURN_VALUE | 9,120 | 1.5% |
| RETURN_GENERATOR | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 588,856 | 94.9% |
| LOAD_CONST | 21,840 | 3.5% |
| RETURN_VALUE | 9,120 | 1.5% |
| BINARY_OP_ADD_UNICODE | 480 | 0.1% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 2,801,398 | 47.4% |
| LOAD_FAST | 2,252,722 | 38.1% |
| LOAD_FAST_LOAD_FAST | 421,200 | 7.1% |
| LOAD_SUPER_ATTR_METHOD | 224,490 | 3.8% |
| LOAD_GLOBAL_MODULE | 67,920 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,881,114 | 99.4% |
| MAKE_CELL | 19,920 | 0.3% |
| RETURN_GENERATOR | 12,720 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 717,406 | 48.2% |
| LOAD_ATTR_MODULE | 520,434 | 34.9% |
| LOAD_FAST | 155,079 | 10.4% |
| LOAD_CONST | 55,511 | 3.7% |
| BINARY_OP | 37,200 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 969,043 | 65.1% |
| COPY_FREE_VARS | 520,434 | 34.9% |


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

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 929,319 | 46.6% |
| LOAD_ATTR_INSTANCE_VALUE | 627,292 | 31.5% |
| LOAD_FAST | 408,000 | 20.5% |
| LOAD_FAST_LOAD_FAST | 12,720 | 0.6% |
| CALL_BUILTIN_FAST | 9,120 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,991,055 | 99.9% |
| POP_JUMP_IF_TRUE | 1,106 | 0.1% |
| COMPARE_OP | 77 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 942,313 | 95.6% |
| LOAD_CONST | 39,600 | 4.0% |
| LOAD_FAST | 4,080 | 0.4% |
| COMPARE_OP | 12 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 959,808 | 97.3% |
| LOAD_FAST | 9,120 | 0.9% |
| COPY | 9,120 | 0.9% |
| POP_JUMP_IF_TRUE | 7,957 | 0.8% |


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
| GET_ITER | 862,020 | 79.3% |
| SWAP | 224,247 | 20.6% |
| JUMP_BACKWARD | 1,157 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 408,000 | 37.5% |
| STORE_FAST | 335,846 | 30.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 236,238 | 21.7% |
| LOAD_FAST | 106,371 | 9.8% |
| RETURN_CONST | 675 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 123,528 | 99.6% |
| JUMP_BACKWARD | 452 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 123,840 | 99.9% |
| RETURN_CONST | 80 | 0.1% |
| LOAD_FAST | 60 | 0.0% |


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
| LOAD_GLOBAL_MODULE | 36,231 | 82.5% |
| LOAD_ATTR_MODULE | 7,680 | 17.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,972 | 72.8% |
| LOAD_FAST_CHECK | 11,939 | 27.2% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,055,634 | 91.5% |
| LOAD_FAST_LOAD_FAST | 778,906 | 5.5% |
| COPY | 407,976 | 2.9% |
| LOAD_ATTR_INSTANCE_VALUE | 16,241 | 0.1% |
| RETURN_VALUE | 9,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,338,494 | 23.4% |
| LOAD_FAST | 2,170,812 | 15.2% |
| LOAD_ATTR | 1,153,266 | 8.1% |
| LOAD_GLOBAL_MODULE | 962,854 | 6.7% |
| CONTAINS_OP | 928,422 | 6.5% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 182,124 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,462 | 39.8% |
| CALL | 61,492 | 33.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 48,170 | 26.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,338,494 | 88.3% |
| LOAD_FAST | 343,759 | 9.1% |
| LOAD_ATTR | 37,229 | 1.0% |
| LOAD_ATTR_SLOT | 37,200 | 1.0% |
| LOAD_CONST | 9,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,301,540 | 34.4% |
| CALL | 992,997 | 26.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 803,426 | 21.2% |
| LOAD_CONST | 513,482 | 13.6% |
| LOAD_FAST_LOAD_FAST | 149,207 | 3.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,546,312 | 62.9% |
| LOAD_ATTR_INSTANCE_VALUE | 814,772 | 14.4% |
| LOAD_FAST_LOAD_FAST | 520,434 | 9.2% |
| BINARY_SUBSCR | 408,000 | 7.2% |
| ENTER_EXECUTOR | 320,186 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,801,398 | 49.7% |
| LOAD_FAST | 1,545,620 | 27.4% |
| CALL_PY_WITH_DEFAULTS | 717,406 | 12.7% |
| LOAD_FAST_LOAD_FAST | 457,920 | 8.1% |
| LOAD_CONST | 68,231 | 1.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,458,316 | 78.1% |
| ENTER_EXECUTOR | 408,480 | 21.9% |
| LOAD_ATTR | 106 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,242,968 | 66.6% |
| CALL_PY_WITH_DEFAULTS | 520,434 | 27.9% |
| STORE_DEREF | 39,840 | 2.1% |
| LOAD_CONST | 22,800 | 1.2% |
| LOAD_FAST | 19,920 | 1.1% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 547,314 | 69.9% |
| LOAD_FAST_LOAD_FAST | 236,238 | 30.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 520,434 | 66.4% |
| UNARY_INVERT | 236,238 | 30.1% |
| RETURN_VALUE | 9,120 | 1.2% |
| LOAD_CONST | 9,120 | 1.2% |
| LOAD_FAST_LOAD_FAST | 4,080 | 0.5% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 254,787 | 53.1% |
| ENTER_EXECUTOR | 204,826 | 42.7% |
| RETURN_VALUE | 19,920 | 4.1% |
| LOAD_GLOBAL_MODULE | 480 | 0.1% |
| LOAD_ATTR_PROPERTY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 471,058 | 98.1% |
| TO_BOOL_BOOL | 8,960 | 1.9% |
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
| RESUME_CHECK | 1,783,278 | 47.6% |
| LOAD_FAST | 550,434 | 14.7% |
| LOAD_GLOBAL_BUILTIN | 392,160 | 10.5% |
| STORE_FAST | 343,272 | 9.2% |
| NOP | 327,458 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,923,284 | 51.3% |
| LOAD_DEREF | 799,404 | 21.3% |
| CALL_ISINSTANCE | 532,674 | 14.2% |
| LOAD_GLOBAL_BUILTIN | 392,160 | 10.5% |
| LOAD_GLOBAL_MODULE | 31,920 | 0.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,181,797 | 27.2% |
| RESUME_CHECK | 1,401,646 | 17.5% |
| LOAD_ATTR_INSTANCE_VALUE | 962,854 | 12.0% |
| NOP | 829,115 | 10.3% |
| POP_JUMP_IF_FALSE | 693,189 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,679,421 | 21.0% |
| LOAD_ATTR_MODULE | 1,458,316 | 18.2% |
| LOAD_FAST_LOAD_FAST | 1,188,356 | 14.8% |
| LOAD_FAST | 1,017,366 | 12.7% |
| COMPARE_OP_STR | 942,313 | 11.8% |


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
| LOAD_FAST | 758,124 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 529,554 | 69.9% |
| CALL_PY_EXACT_ARGS | 224,490 | 29.6% |
| LOAD_FAST | 4,080 | 0.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 7,865,564 | 36.4% |
| CALL_PY_EXACT_ARGS | 5,881,114 | 27.2% |
| FOR_ITER_GEN | 4,488,000 | 20.8% |
| CALL_PY_WITH_DEFAULTS | 969,043 | 4.5% |
| COPY_FREE_VARS | 803,604 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,349,786 | 57.2% |
| POP_TOP | 4,896,480 | 22.7% |
| LOAD_GLOBAL_BUILTIN | 1,783,278 | 8.3% |
| LOAD_GLOBAL_MODULE | 1,401,646 | 6.5% |
| NOP | 665,154 | 3.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,563,239 | 65.0% |
| LOAD_FAST_LOAD_FAST | 409,050 | 17.0% |
| SWAP | 407,976 | 17.0% |
| LOAD_ATTR_INSTANCE_VALUE | 12,240 | 0.5% |
| STORE_FAST_LOAD_FAST | 9,120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,048,920 | 43.6% |
| LOAD_FAST | 641,988 | 26.7% |
| LOAD_GLOBAL_MODULE | 375,210 | 15.6% |
| LOAD_CONST | 153,119 | 6.4% |
| LOAD_FAST_LOAD_FAST | 90,720 | 3.8% |


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
| LOAD_ATTR | 520,434 | 89.1% |
| LOAD_FAST | 31,090 | 5.3% |
| LOAD_ATTR_INSTANCE_VALUE | 24,480 | 4.2% |
| CALL | 7,680 | 1.3% |
| LOAD_CONST | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 522,496 | 89.4% |
| RETURN_CONST | 21,840 | 3.7% |
| LOAD_GLOBAL_MODULE | 19,920 | 3.4% |
| LOAD_CONST | 19,920 | 3.4% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 62.2% |
| COPY | 141 | 36.5% |
| TO_BOOL | 5 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 240 | 62.2% |
| POP_JUMP_IF_FALSE | 146 | 37.8% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 839,540 | 22.6% |
| CALL_ISINSTANCE | 532,674 | 14.3% |
| CALL | 510,174 | 13.7% |
| LOAD_FAST | 499,399 | 13.4% |
| RETURN_CONST | 459,646 | 12.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,463,626 | 66.2% |
| POP_JUMP_IF_TRUE | 1,119,226 | 30.1% |
| UNARY_NOT | 137,347 | 3.7% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,277,106 | 55.1% |
| LOAD_FAST | 520,434 | 22.5% |
| BINARY_OP | 520,434 | 22.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,317,974 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 232,650 | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE | 29,520 | 11.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 262,170 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 135,282 | 80.1% |
| LOAD_FAST | 19,920 | 11.8% |
| COPY | 9,120 | 5.4% |
| WITH_EXCEPT_START | 4,080 | 2.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 480 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 155,682 | 92.2% |
| POP_JUMP_IF_TRUE | 13,200 | 7.8% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 792,000 | 95.6% |
| CALL_BUILTIN_FAST | 36,231 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 792,000 | 95.6% |
| STORE_FAST | 36,231 | 4.4% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 412,080 | 32.6% |
| LOAD_FAST_CHECK | 408,000 | 32.3% |
| FOR_ITER_LIST | 236,238 | 18.7% |
| CALL_BUILTIN_FAST | 198,342 | 15.7% |
| CALL | 5,520 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,260,180 | 99.6% |
| LOAD_FAST | 4,560 | 0.4% |


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
| specialization.deferred |       441319 | 60.0% |
|          hit |       294288 | 40.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 223 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 223 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        20892 | 3.5% |
|          hit |       584176 | 96.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 12 | 5.7% |
| Failure | 200 | 94.3% |

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
| specialization.deferred |      1046985 | 13.9% |
|          hit |      6469611 | 86.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 9 | 0.9% |
| Failure | 1,046 | 99.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 323 | 30.9% |
| sequence | 223 | 21.3% |
| tuple | 220 | 21.0% |
| set | 200 | 19.1% |
| other | 80 | 7.6% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3158332 | 71.0% |
|          hit |      1287262 | 28.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 52 | 3.3% |
| Failure | 1,546 | 96.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 732 | 47.3% |
| or | 405 | 26.2% |
| remainder | 209 | 13.5% |
| add different types | 160 | 10.3% |
| add other | 40 | 2.6% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6770263 | 32.6% |
| specialization.deopt |           60 | 0.0% |
|          hit |     14002309 | 67.4% |
|         miss |         4140 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 176 | 2.1% |
| Failure | 8,340 | 97.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 2,455 | 29.4% |
| cfunc noargs | 1,579 | 18.9% |
| class no vectorcall | 1,190 | 14.3% |
| meth descr varargs keywords | 811 | 9.7% |
| other | 360 | 4.3% |
| class mutable | 321 | 3.8% |
| bound method | 283 | 3.4% |
| cfunc varargs keywords | 241 | 2.9% |
| operator wrapper | 240 | 2.9% |
| cfunc varargs | 240 | 2.9% |
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
| specialization.deferred |       262695 | 8.1% |
| specialization.deopt |           77 | 0.0% |
|          hit |      2973074 | 91.7% |
|         miss |         5169 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 138 | 26.3% |
| Failure | 386 | 73.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| different types | 155 | 40.2% |
| float long | 151 | 39.1% |
| big int | 80 | 20.7% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       914400 | 13.8% |
|          hit |      5716364 | 86.2% |

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
| specialization.deferred |      4891096 | 15.3% |
| specialization.deopt |         4154 | 0.0% |
|          hit |     26864837 | 84.0% |
|         miss |       229006 | 0.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,463 | 45.5% |
| Failure | 5,337 | 54.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 1,316 | 24.7% |
| shadowed | 998 | 18.7% |
| not managed dict | 929 | 17.4% |
| non overriding descriptor | 578 | 10.8% |
| class attr descriptor | 360 | 6.7% |
| metaclass attribute | 280 | 5.2% |
| class method obj | 280 | 5.2% |
| has managed dict | 240 | 4.5% |
| non object slot | 160 | 3.0% |
| class attr simple | 96 | 1.8% |
| mutable class | 80 | 1.5% |
| overridden | 20 | 0.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           56 | 0.0% |
| specialization.deopt |            8 | 0.0% |
|          hit |     11758599 | 100.0% |
|         miss |         2386 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 179 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       799404 | 100.0% |


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
| specialization.deferred |        61693 | 2.5% |
| specialization.deopt |         2780 | 0.1% |
|          hit |      2302617 | 91.6% |
|         miss |       148120 | 5.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,792 | 81.8% |
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
|          hit |      2092971 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 172,550,759 | 56.1% |
| Not specialized | 38,344,039 | 12.5% |
| Specialized | 96,725,308 | 31.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 18,446,744,073,709,551,615 | 100.0% |
| CALL | 6,770,263 | 0.0% |
| LOAD_ATTR | 4,891,096 | 0.0% |
| BINARY_OP | 3,158,332 | 0.0% |
| TO_BOOL | 1,046,985 | 0.0% |
| FOR_ITER | 914,400 | 0.0% |
| BINARY_SUBSCR | 441,319 | 0.0% |
| COMPARE_OP | 262,695 | 0.0% |
| STORE_ATTR | 61,693 | 0.0% |
| STORE_SUBSCR | 20,892 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 159,132 | 40.9% |
| STORE_ATTR_INSTANCE_VALUE | 148,120 | 38.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60,754 | 15.6% |
| LOAD_ATTR_PROPERTY | 9,120 | 2.3% |
| COMPARE_OP_INT | 5,169 | 1.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 4,140 | 1.1% |
| LOAD_GLOBAL_MODULE | 2,386 | 0.6% |
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
| Calls to PyEval_EvalDefault | 7,924,604 | 36.7% |
| Calls to Python functions inlined | 13,696,600 | 63.3% |
| Calls via PyEval_EvalFrame (total) | 7,924,604 | 36.7% |
| Calls via PyEval_EvalFrame (vector) | 7,511,564 | 34.7% |
| Calls via PyEval_EvalFrame (generator) | 413,040 | 1.9% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 7,511,564 | 34.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 442,080 | 2.0% |
| Calls via PyEval_EvalFrame (function ex) | 400,440 | 1.9% |
| Calls via PyEval_EvalFrame (api) | 318,832 | 1.5% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 17,437,720 | 80.7% |
| Frame objects created | 25,421 | 0.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 11,111,387 | 41.7% |
| Frees to freelist | 11,112,647 |  |
| Allocations | 15,529,871 | 58.3% |
| Allocations to 512 bytes | 15,394,731 | 57.8% |
| Allocations to 4 kbytes | 60,728 | 0.2% |
| Allocations over 4 kbytes | 74,412 | 0.3% |
| Frees | 16,235,806 |  |
| New values | 59,520 |  |
| Interpreter increfs | 124,428,352 | 73.4% |
| Interpreter decrefs | 132,631,034 | 68.4% |
| Increfs | 45,149,782 | 26.6% |
| Decrefs | 61,275,819 | 31.6% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 5,796,116 |  |
| Method cache misses | 29,582 |  |
| Method cache collisions | 44,976 |  |
| Method cache dunder hits | 6,795,040 |  |
| Method cache dunder misses | 15,394 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 12 | 288 | 91,184 |
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
| Optimization attempts | 316,888 |  |
| Traces created | 130 | 0.0% |
| Traces executed | 6,603,809 |  |
| Uops executed | 59,686,989 | 9 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |


</details>

**Trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 11 | 8.5% |
| <= 16 | 59 | 45.4% |
| <= 32 | 40 | 30.8% |
| <= 64 | 20 | 15.4% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 11 | 8.5% |
| <= 16 | 59 | 45.4% |
| <= 32 | 60 | 46.2% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 768,000 | 11.6% |
| <= 8 | 1,105,329 | 16.7% |
| <= 16 | 4,490,304 | 68.0% |
| <= 32 | 138,128 | 2.1% |
| <= 64 | 102,048 | 1.5% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 14,362,651 | 24.1% | 24.1% |
| _EXIT_TRACE | 6,603,809 | 11.1% | 35.1% |
| LOAD_FAST | 6,577,407 | 11.0% | 46.1% |
| _POP_JUMP_IF_TRUE | 5,305,347 | 8.9% | 55.0% |
| _ITER_CHECK_LIST | 5,057,131 | 8.5% | 63.5% |
| _IS_ITER_EXHAUSTED_LIST | 5,057,131 | 8.5% | 72.0% |
| STORE_FAST | 4,404,608 | 7.4% | 79.4% |
| _ITER_NEXT_LIST | 4,078,204 | 6.8% | 86.2% |
| _GUARD_GLOBALS_VERSION | 1,232,752 | 2.1% | 88.3% |
| POP_TOP | 1,105,275 | 1.9% | 90.1% |
| PUSH_NULL | 803,780 | 1.3% | 91.5% |
| _LOAD_GLOBAL_BUILTINS | 718,224 | 1.2% | 92.7% |
| _GUARD_BUILTINS_VERSION | 718,224 | 1.2% | 93.9% |
| _LOAD_GLOBAL_MODULE | 514,528 | 0.9% | 94.7% |
| LOAD_CONST | 256,373 | 0.4% | 95.2% |
| _ITER_CHECK_RANGE | 231,776 | 0.4% | 95.5% |
| _IS_ITER_EXHAUSTED_RANGE | 231,776 | 0.4% | 95.9% |
| _SAVE_CURRENT_IP | 228,256 | 0.4% | 96.3% |
| _PUSH_FRAME | 228,256 | 0.4% | 96.7% |
| _INIT_CALL_PY_EXACT_ARGS | 228,256 | 0.4% | 97.1% |
| _CHECK_STACK_SPACE | 228,256 | 0.4% | 97.5% |
| _CHECK_PEP_523 | 228,256 | 0.4% | 97.8% |
| _CHECK_FUNCTION_EXACT_ARGS | 228,256 | 0.4% | 98.2% |
| RESUME_CHECK | 228,256 | 0.4% | 98.6% |
| LOAD_ATTR | 204,096 | 0.3% | 99.0% |
| _ITER_NEXT_RANGE | 117,748 | 0.2% | 99.1% |
| TO_BOOL_BOOL | 106,128 | 0.2% | 99.3% |
| CALL_BUILTIN_FAST | 106,128 | 0.2% | 99.5% |
| BINARY_SUBSCR_LIST_INT | 106,128 | 0.2% | 99.7% |
| _POP_JUMP_IF_FALSE | 98,648 | 0.2% | 99.8% |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 24,160 | 0.0% | 99.9% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 24,160 | 0.0% | 99.9% |
| _JUMP_TO_TOP | 11,320 | 0.0% | 99.9% |
| _ITER_CHECK_TUPLE | 8,960 | 0.0% | 100.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 8,960 | 0.0% | 100.0% |
| BUILD_TUPLE | 4,000 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,840 | 0.0% | 100.0% |
| _LOAD_ATTR_INSTANCE_VALUE | 1,815 | 0.0% | 100.0% |
| _GUARD_TYPE_VERSION | 1,815 | 0.0% | 100.0% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,815 | 0.0% | 100.0% |
| _ITER_NEXT_TUPLE | 480 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| FOR_ITER_GEN | 264,000 |
| FOR_ITER | 52,520 |
| LOAD_ATTR_METHOD_WITH_VALUES | 278 |
| YIELD_VALUE | 20 |
| LOAD_ATTR_MODULE | 20 |
| CALL_KW | 20 |
| LOAD_ATTR_PROPERTY | 19 |
| LOAD_ATTR_METHOD_NO_DICT | 11 |


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
Stats gathered on: 2023-10-03
