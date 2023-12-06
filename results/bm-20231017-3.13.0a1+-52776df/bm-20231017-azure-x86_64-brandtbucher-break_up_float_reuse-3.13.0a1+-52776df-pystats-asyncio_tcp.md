
# Pystats results

- benchmark: asyncio_tcp
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 52776df
- commit date: 2023-10-17T21:47:13-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 67,089,930 | 21.4% | 21.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 22,840,313 | 7.3% | 28.6% |  |
| RESUME_CHECK | 16,214,141 | 5.2% | 33.8% |  |
| STORE_FAST | 14,851,199 | 4.7% | 38.5% |  |
| POP_JUMP_IF_FALSE | 13,694,582 | 4.4% | 42.9% |  |
| CALL_PY_EXACT_ARGS | 12,234,108 | 3.9% | 46.8% |  |
| LOAD_CONST | 10,886,370 | 3.5% | 50.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,730,761 | 3.4% | 53.6% |  |
| TO_BOOL_BOOL | 9,986,458 | 3.2% | 56.8% |  |
| POP_TOP | 9,633,010 | 3.1% | 59.9% |  |
| RETURN_VALUE | 9,411,532 | 3.0% | 62.9% |  |
| LOAD_GLOBAL_MODULE | 6,623,267 | 2.1% | 65.0% |  |
| LOAD_FAST_LOAD_FAST | 6,072,453 | 1.9% | 66.9% |  |
| RETURN_CONST | 5,821,909 | 1.9% | 68.8% |  |
| LOAD_GLOBAL_BUILTIN | 5,788,928 | 1.8% | 70.6% | 0.0% |
| LOAD_ATTR_SLOT | 5,217,405 | 1.7% | 72.3% |  |
| POP_JUMP_IF_TRUE | 5,059,628 | 1.6% | 73.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,728,626 | 1.5% | 75.4% |  |
| STORE_ATTR_SLOT | 4,209,230 | 1.3% | 76.7% |  |
| LOAD_ATTR | 4,176,442 | 1.3% | 78.1% |  |
| NOP | 3,766,079 | 1.2% | 79.3% |  |
| CALL | 3,270,797 | 1.0% | 80.3% |  |
| BINARY_OP | 3,170,378 | 1.0% | 81.3% |  |
| TO_BOOL_INT | 3,163,495 | 1.0% | 82.3% |  |
| COMPARE_OP_INT | 2,783,857 | 0.9% | 83.2% |  |
| LOAD_ATTR_MODULE | 2,567,379 | 0.8% | 84.0% |  |
| PUSH_NULL | 2,316,558 | 0.7% | 84.8% |  |
| CALL_LEN | 2,214,726 | 0.7% | 85.5% |  |
| COPY | 2,026,174 | 0.6% | 86.1% |  |
| INTERPRETER_EXIT | 1,999,326 | 0.6% | 86.7% |  |
| JUMP_FORWARD | 1,960,364 | 0.6% | 87.4% |  |
| TO_BOOL | 1,833,918 | 0.6% | 87.9% |  |
| JUMP_BACKWARD | 1,821,454 | 0.6% | 88.5% |  |
| POP_JUMP_IF_NOT_NONE | 1,750,888 | 0.6% | 89.1% |  |
| POP_JUMP_IF_NONE | 1,721,343 | 0.5% | 89.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,703,340 | 0.5% | 90.2% |  |
| FOR_ITER_LIST | 1,523,030 | 0.5% | 90.7% |  |
| GET_ITER | 1,449,960 | 0.5% | 91.1% |  |
| BUILD_LIST | 1,249,945 | 0.4% | 91.5% |  |
| SEND_GEN | 1,227,720 | 0.4% | 91.9% |  |
| TO_BOOL_LIST | 1,196,700 | 0.4% | 92.3% |  |
| STORE_FAST_STORE_FAST | 1,092,937 | 0.3% | 92.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,817 | 0.3% | 93.0% |  |
| FOR_ITER_RANGE | 1,014,865 | 0.3% | 93.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,012,907 | 0.3% | 93.6% |  |
| CALL_ISINSTANCE | 992,204 | 0.3% | 93.9% |  |
| YIELD_VALUE | 980,760 | 0.3% | 94.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 980,640 | 0.3% | 94.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 973,342 | 0.3% | 94.9% |  |
| UNARY_NOT | 960,120 | 0.3% | 95.2% |  |
| CALL_METHOD_DESCRIPTOR_O | 820,749 | 0.3% | 95.4% | 0.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 816,369 | 0.3% | 95.7% | 0.2% |
| BUILD_TUPLE | 779,867 | 0.2% | 96.0% |  |
| CALL_FUNCTION_EX | 768,265 | 0.2% | 96.2% |  |
| LIST_EXTEND | 767,905 | 0.2% | 96.4% |  |
| CALL_INTRINSIC_1 | 767,905 | 0.2% | 96.7% |  |
| GET_AWAITABLE | 740,280 | 0.2% | 96.9% |  |
| END_SEND | 740,280 | 0.2% | 97.2% |  |
| LOAD_DEREF | 543,770 | 0.2% | 97.3% |  |
| CALL_BUILTIN_CLASS | 539,207 | 0.2% | 97.5% |  |
| SWAP | 532,967 | 0.2% | 97.7% |  |
| COPY_FREE_VARS | 518,526 | 0.2% | 97.8% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 498,363 | 0.2% | 98.0% |  |
| TO_BOOL_NONE | 496,500 | 0.2% | 98.2% |  |
| RETURN_GENERATOR | 493,980 | 0.2% | 98.3% |  |
| SEND | 493,600 | 0.2% | 98.5% |  |
| CALL_PY_WITH_DEFAULTS | 493,282 | 0.2% | 98.6% |  |
| UNARY_INVERT | 486,401 | 0.2% | 98.8% |  |
| LOAD_SUPER_ATTR_METHOD | 482,100 | 0.2% | 98.9% |  |
| BINARY_OP_ADD_FLOAT_LHS | 480,960 | 0.2% | 99.1% |  |
| CALL_LIST_APPEND | 280,345 | 0.1% | 99.2% |  |
| BINARY_SLICE | 280,225 | 0.1% | 99.3% |  |
| CALL_KW | 260,122 | 0.1% | 99.3% |  |
| STORE_SUBSCR_DICT | 252,562 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 252,082 | 0.1% | 99.5% |  |
| CONTAINS_OP | 241,080 | 0.1% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 241,020 | 0.1% | 99.7% |  |
| BINARY_OP_ADD_INT | 240,540 | 0.1% | 99.7% |  |
| DELETE_SUBSCR | 240,240 | 0.1% | 99.8% |  |
| BUILD_SLICE | 240,240 | 0.1% | 99.9% |  |
| BINARY_OP_MULTIPLY_INT | 240,240 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,625 | 0.0% | 100.0% |  |
| COMPARE_OP | 13,462 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 12,742 | 0.0% | 100.0% |  |
| FOR_ITER | 12,420 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 6,120 | 0.0% | 100.0% |  |
| STORE_ATTR | 2,260 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,100 | 0.0% | 100.0% |  |
| IS_OP | 1,020 | 0.0% | 100.0% |  |
| MAKE_CELL | 840 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 720 | 0.0% | 100.0% |  |
| STORE_DEREF | 660 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 540 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 540 | 0.0% | 100.0% |  |
| BUILD_MAP | 540 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 480 | 0.0% | 100.0% |  |
| POP_EXCEPT | 480 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 480 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 420 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 420 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 360 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 360 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 300 | 0.0% | 100.0% |  |
| BUILD_SET | 300 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 300 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 240 | 0.0% | 100.0% | 25.0% |
| UNPACK_SEQUENCE | 200 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 180 | 0.0% | 100.0% |  |
| DICT_MERGE | 180 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 140 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 120 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% | 100.0% |  |
| LIST_APPEND | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 60 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 22,093,469 | 7.0% | 7.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 11,247,506 | 3.6% | 10.6% |
| RESUME_CHECK LOAD_FAST | 10,196,354 | 3.2% | 13.9% |
| STORE_FAST LOAD_FAST | 9,013,981 | 2.9% | 16.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,419,092 | 2.4% | 19.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,793,792 | 2.2% | 21.2% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,762,701 | 1.8% | 23.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,550,029 | 1.8% | 24.8% |
| LOAD_FAST LOAD_ATTR_SLOT | 5,211,305 | 1.7% | 26.5% |
| RETURN_CONST POP_TOP | 4,791,403 | 1.5% | 28.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,714,238 | 1.5% | 29.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 4,428,508 | 1.4% | 30.9% |
| LOAD_CONST LOAD_FAST | 4,412,766 | 1.4% | 32.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 4,225,938 | 1.3% | 33.7% |
| POP_TOP LOAD_FAST | 4,000,537 | 1.3% | 35.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,969,574 | 1.3% | 36.2% |
| LOAD_FAST RETURN_VALUE | 3,444,991 | 1.1% | 37.3% |
| LOAD_FAST LOAD_ATTR | 3,379,033 | 1.1% | 38.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 3,020,654 | 1.0% | 39.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 2,973,626 | 0.9% | 40.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,832,945 | 0.9% | 41.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 2,832,242 | 0.9% | 42.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,783,617 | 0.9% | 43.0% |
| NOP LOAD_FAST | 2,780,415 | 0.9% | 43.9% |
| LOAD_CONST STORE_FAST | 2,735,011 | 0.9% | 44.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,710,285 | 0.9% | 45.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,566,159 | 0.8% | 46.4% |
| RETURN_VALUE STORE_FAST | 2,477,488 | 0.8% | 47.2% |
| LOAD_FAST LOAD_CONST | 2,459,747 | 0.8% | 48.0% |
| RETURN_VALUE TO_BOOL_BOOL | 2,445,063 | 0.8% | 48.8% |
| LOAD_FAST STORE_ATTR_SLOT | 2,233,146 | 0.7% | 49.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,232,606 | 0.7% | 50.2% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,156,269 | 0.7% | 50.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,084,958 | 0.7% | 51.5% |
| POP_TOP RETURN_CONST | 2,040,950 | 0.6% | 52.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,000,289 | 0.6% | 52.8% |
| CACHE RESUME_CHECK | 1,998,186 | 0.6% | 53.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,976,084 | 0.6% | 54.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,923,000 | 0.6% | 54.7% |
| TO_BOOL POP_JUMP_IF_TRUE | 1,819,256 | 0.6% | 55.3% |
| RESUME_CHECK NOP | 1,765,651 | 0.6% | 55.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,732,604 | 0.6% | 56.4% |
| STORE_FAST JUMP_FORWARD | 1,719,284 | 0.5% | 57.0% |
| LOAD_CONST COMPARE_OP_INT | 1,713,304 | 0.5% | 57.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,699,740 | 0.5% | 58.0% |
| COPY TO_BOOL_INT | 1,545,214 | 0.5% | 58.5% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,544,854 | 0.5% | 59.0% |
| CALL STORE_FAST | 1,520,090 | 0.5% | 59.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,511,247 | 0.5% | 60.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,509,688 | 0.5% | 60.5% |
| POP_TOP LOAD_CONST | 1,501,967 | 0.5% | 60.9% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,481,643 | 0.5% | 61.4% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,479,063 | 0.5% | 61.9% |
| JUMP_FORWARD LOAD_FAST | 1,478,924 | 0.5% | 62.4% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 1,472,464 | 0.5% | 62.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,421,206 | 0.5% | 63.3% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,379,601 | 0.4% | 63.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 1,299,173 | 0.4% | 64.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,262,087 | 0.4% | 64.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,256,705 | 0.4% | 64.9% |
| STORE_ATTR_SLOT LOAD_CONST | 1,234,263 | 0.4% | 65.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,231,964 | 0.4% | 65.7% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 1,196,580 | 0.4% | 66.1% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 1,196,580 | 0.4% | 66.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,092,697 | 0.3% | 66.8% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,092,337 | 0.3% | 67.2% |
| BINARY_OP COPY | 1,064,254 | 0.3% | 67.5% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,026,868 | 0.3% | 67.8% |
| LOAD_ATTR LOAD_FAST | 1,026,009 | 0.3% | 68.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,024,929 | 0.3% | 68.5% |
| LOAD_FAST TO_BOOL | 1,024,788 | 0.3% | 68.8% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,020,887 | 0.3% | 69.1% |
| POP_JUMP_IF_FALSE POP_TOP | 1,018,648 | 0.3% | 69.5% |
| STORE_FAST RETURN_CONST | 1,008,745 | 0.3% | 69.8% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 1,007,166 | 0.3% | 70.1% |
| CALL RETURN_VALUE | 1,002,025 | 0.3% | 70.4% |
| CALL_LEN STORE_FAST | 1,001,624 | 0.3% | 70.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 992,104 | 0.3% | 71.1% |
| RETURN_VALUE RETURN_VALUE | 986,204 | 0.3% | 71.4% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 985,744 | 0.3% | 71.7% |
| NOP LOAD_GLOBAL_MODULE | 985,124 | 0.3% | 72.0% |
| LOAD_FAST STORE_FAST | 985,064 | 0.3% | 72.3% |
| POP_JUMP_IF_TRUE LOAD_CONST | 985,061 | 0.3% | 72.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 981,562 | 0.3% | 72.9% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 980,640 | 0.3% | 73.3% |
| RETURN_VALUE INTERPRETER_EXIT | 975,300 | 0.3% | 73.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 975,000 | 0.3% | 73.9% |
| STORE_FAST NOP | 974,302 | 0.3% | 74.2% |
| LOAD_FAST GET_ITER | 962,580 | 0.3% | 74.5% |
| GET_ITER FOR_ITER_LIST | 962,500 | 0.3% | 74.8% |
| TO_BOOL_BOOL UNARY_NOT | 960,060 | 0.3% | 75.1% |
| PUSH_NULL LOAD_FAST | 839,854 | 0.3% | 75.4% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 820,689 | 0.3% | 75.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 807,170 | 0.3% | 75.9% |
| BINARY_OP TO_BOOL_INT | 800,330 | 0.3% | 76.1% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 786,325 | 0.3% | 76.4% |
| BINARY_OP STORE_FAST | 778,468 | 0.2% | 76.6% |
| RETURN_CONST INTERPRETER_EXIT | 777,006 | 0.2% | 76.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 774,226 | 0.2% | 77.1% |
| LOAD_ATTR PUSH_NULL | 768,165 | 0.2% | 77.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,240 | 85.7% |
| LOAD_CONST | 39,985 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,240 | 85.7% |
| CALL_METHOD_DESCRIPTOR_O | 33,704 | 12.0% |
| STORE_FAST | 5,921 | 2.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.1% |
| LIST_EXTEND | 180 | 0.1% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,998,186 | 99.9% |
| COPY_FREE_VARS | 540 | 0.0% |
| POP_TOP | 300 | 0.0% |
| RETURN_GENERATOR | 240 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 60 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 50.0% |
| LOAD_CONST | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 20 | 50.0% |
| BINARY_SUBSCR_DICT | 20 | 50.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 360 | 75.0% |
| BUILD_TUPLE | 120 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 480 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 240,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,240 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 252,660 | 34.1% |
| SEND | 246,600 | 33.3% |
| RETURN_VALUE | 241,020 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 499,380 | 67.5% |
| STORE_FAST | 240,600 | 32.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 0.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 420 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 962,580 | 66.4% |
| CALL_BUILTIN_CLASS | 481,140 | 33.2% |
| LOAD_ATTR_INSTANCE_VALUE | 6,060 | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 962,500 | 66.4% |
| FOR_ITER_RANGE | 481,080 | 33.2% |
| FOR_ITER | 6,260 | 0.4% |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% |
| FOR_ITER_TUPLE | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 975,300 | 48.8% |
| RETURN_CONST | 777,006 | 38.9% |
| YIELD_VALUE | 246,720 | 12.3% |
| RETURN_GENERATOR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 360 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,765,651 | 46.9% |
| STORE_FAST | 974,302 | 25.9% |
| POP_JUMP_IF_FALSE | 520,885 | 13.8% |
| POP_JUMP_IF_TRUE | 246,341 | 6.5% |
| STORE_ATTR_INSTANCE_VALUE | 240,240 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,780,415 | 73.8% |
| LOAD_GLOBAL_MODULE | 985,124 | 26.2% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 360 | 75.0% |
| SWAP | 60 | 12.5% |
| COPY | 60 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240 | 50.0% |
| RETURN_VALUE | 60 | 12.5% |
| RERAISE | 60 | 12.5% |
| POP_TOP | 60 | 12.5% |
| LOAD_CONST | 60 | 12.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,791,403 | 49.7% |
| POP_JUMP_IF_FALSE | 1,018,648 | 10.6% |
| CALL_METHOD_DESCRIPTOR_O | 820,689 | 8.5% |
| CALL_FUNCTION_EX | 767,845 | 8.0% |
| END_SEND | 499,380 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,000,537 | 41.5% |
| RETURN_CONST | 2,040,950 | 21.2% |
| LOAD_CONST | 1,501,967 | 15.6% |
| JUMP_BACKWARD | 579,710 | 6.0% |
| LOAD_GLOBAL_MODULE | 527,066 | 5.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 300 | 62.5% |
| RERAISE | 60 | 12.5% |
| CALL_METHOD_DESCRIPTOR_O | 60 | 12.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 440 | 91.7% |
| LOAD_GLOBAL | 40 | 8.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,511,247 | 65.2% |
| LOAD_ATTR | 768,165 | 33.2% |
| LOAD_DEREF | 35,586 | 1.5% |
| LOAD_FAST | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 839,854 | 36.3% |
| LOAD_FAST_LOAD_FAST | 746,583 | 32.2% |
| CALL | 729,461 | 31.5% |
| LOAD_CONST | 360 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 493,080 | 99.8% |
| CALL_KW | 300 | 0.1% |
| CACHE | 240 | 0.0% |
| MAKE_CELL | 180 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 493,380 | 99.9% |
| INTERPRETER_EXIT | 300 | 0.1% |
| STORE_FAST | 120 | 0.0% |
| CALL | 80 | 0.0% |
| LIST_APPEND | 60 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,444,991 | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,710,285 | 28.8% |
| CALL | 1,002,025 | 10.6% |
| RETURN_VALUE | 986,204 | 10.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,622 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,477,488 | 26.3% |
| TO_BOOL_BOOL | 2,445,063 | 26.0% |
| RETURN_VALUE | 986,204 | 10.5% |
| INTERPRETER_EXIT | 975,300 | 10.4% |
| LOAD_FAST | 761,485 | 8.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 120 | 66.7% |
| STORE_SUBSCR | 20 | 11.1% |
| LOAD_FAST | 20 | 11.1% |
| LOAD_CONST | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 66.7% |
| STORE_SUBSCR_DICT | 40 | 22.2% |
| STORE_SUBSCR | 20 | 11.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,024,788 | 55.9% |
| LOAD_ATTR_INSTANCE_VALUE | 807,170 | 44.0% |
| TO_BOOL | 780 | 0.0% |
| LOAD_ATTR | 560 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,819,256 | 99.2% |
| POP_JUMP_IF_FALSE | 12,862 | 0.7% |
| TO_BOOL_BOOL | 860 | 0.0% |
| TO_BOOL | 780 | 0.0% |
| TO_BOOL_NONE | 100 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 246,161 | 50.6% |
| BINARY_OP | 240,240 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 486,401 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 960,060 | 100.0% |
| TO_BOOL_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 480,060 | 50.0% |
| RETURN_VALUE | 480,000 | 50.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,544,854 | 48.7% |
| LOAD_ATTR_MODULE | 566,011 | 17.9% |
| UNARY_INVERT | 486,401 | 15.3% |
| POP_JUMP_IF_FALSE | 285,846 | 9.0% |
| LOAD_ATTR | 280,045 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,064,254 | 33.6% |
| TO_BOOL_INT | 800,330 | 25.2% |
| STORE_FAST | 778,468 | 24.6% |
| BUILD_TUPLE | 280,045 | 8.8% |
| UNARY_INVERT | 240,240 | 7.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 527,665 | 42.2% |
| STORE_FAST | 481,080 | 38.5% |
| LOAD_FAST_LOAD_FAST | 240,060 | 19.2% |
| LOAD_FAST | 480 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 768,145 | 61.5% |
| STORE_FAST | 481,440 | 38.5% |
| RETURN_VALUE | 180 | 0.0% |
| STORE_DEREF | 120 | 0.0% |
| SWAP | 60 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 180 | 33.3% |
| STORE_FAST | 60 | 11.1% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 11.1% |
| RESUME_CHECK | 60 | 11.1% |
| POP_TOP | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 66.7% |
| STORE_FAST | 180 | 33.3% |


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 300 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 240,240 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 280,045 | 35.9% |
| LOAD_CONST | 246,101 | 31.6% |
| LOAD_FAST | 240,720 | 30.9% |
| LOAD_FAST_LOAD_FAST | 6,521 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 6,180 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 280,045 | 35.9% |
| CALL_PY_EXACT_ARGS | 252,062 | 32.3% |
| CALL | 240,280 | 30.8% |
| CALL_ISINSTANCE | 6,040 | 0.8% |
| LOAD_CONST | 360 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 729,461 | 22.3% |
| LOAD_FAST_LOAD_FAST | 500,182 | 15.3% |
| LOAD_CONST | 493,501 | 15.1% |
| LOAD_ATTR_INSTANCE_VALUE | 487,121 | 14.9% |
| LOAD_ATTR | 240,760 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,520,090 | 46.5% |
| RETURN_VALUE | 1,002,025 | 30.6% |
| POP_TOP | 247,980 | 7.6% |
| RESUME_CHECK | 247,001 | 7.6% |
| LOAD_CONST | 240,300 | 7.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 767,905 | 100.0% |
| DICT_MERGE | 180 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 767,845 | 99.9% |
| RESUME_CHECK | 180 | 0.0% |
| GET_AWAITABLE | 120 | 0.0% |
| MAKE_CELL | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 767,905 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 767,905 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 260,122 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 246,660 | 94.8% |
| COPY_FREE_VARS | 11,842 | 4.6% |
| STORE_FAST | 600 | 0.2% |
| RETURN_GENERATOR | 300 | 0.1% |
| RESUME_CHECK | 300 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 11,842 | 88.0% |
| LOAD_ATTR_MODULE | 780 | 5.8% |
| LOAD_CONST | 400 | 3.0% |
| COMPARE_OP | 280 | 2.1% |
| CALL_BUILTIN_CLASS | 120 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,922 | 96.0% |
| COMPARE_OP | 280 | 2.1% |
| COMPARE_OP_INT | 140 | 1.0% |
| POP_JUMP_IF_TRUE | 60 | 0.4% |
| COMPARE_OP_STR | 60 | 0.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,240 | 99.7% |
| BUILD_SET | 300 | 0.1% |
| LOAD_GLOBAL_MODULE | 180 | 0.1% |
| LOAD_FAST | 180 | 0.1% |
| LOAD_ATTR_SLOT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 240,900 | 99.9% |
| POP_JUMP_IF_TRUE | 180 | 0.1% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,064,254 | 52.5% |
| CALL_LEN | 480,960 | 23.7% |
| UNARY_NOT | 480,060 | 23.7% |
| LOAD_FAST | 360 | 0.0% |
| CALL_BUILTIN_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,545,214 | 76.3% |
| TO_BOOL_BOOL | 480,300 | 23.7% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 0.0% |
| COMPARE_OP_INT | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 493,522 | 95.2% |
| CALL_KW | 11,842 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 11,842 | 2.3% |
| LOAD_ATTR_PROPERTY | 540 | 0.1% |
| CACHE | 540 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 518,406 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 180 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 6,260 | 50.4% |
| JUMP_BACKWARD | 6,060 | 48.8% |
| FOR_ITER | 100 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,060 | 48.8% |
| RETURN_CONST | 6,060 | 48.8% |
| FOR_ITER | 100 | 0.8% |
| FOR_ITER_LIST | 80 | 0.6% |
| LOAD_FAST | 60 | 0.5% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 493,380 | 66.6% |
| LOAD_ATTR_INSTANCE_VALUE | 240,240 | 32.5% |
| LOAD_FAST | 6,180 | 0.8% |
| RETURN_VALUE | 180 | 0.0% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 740,280 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 52.9% |
| LOAD_CONST | 420 | 41.2% |
| LOAD_FAST_LOAD_FAST | 60 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 600 | 58.8% |
| RETURN_VALUE | 300 | 29.4% |
| LOAD_FAST | 120 | 11.8% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 579,710 | 31.8% |
| POP_JUMP_IF_FALSE | 481,039 | 26.4% |
| CALL_LIST_APPEND | 280,165 | 15.4% |
| POP_JUMP_IF_TRUE | 240,300 | 13.2% |
| STORE_FAST | 240,180 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 721,159 | 39.6% |
| FOR_ITER_LIST | 560,390 | 30.8% |
| FOR_ITER_RANGE | 533,785 | 29.3% |
| FOR_ITER | 6,060 | 0.3% |
| FOR_ITER_TUPLE | 60 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 980,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 734,040 | 74.9% |
| SEND | 246,600 | 25.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,719,284 | 87.7% |
| POP_TOP | 240,600 | 12.3% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| STORE_ATTR | 120 | 0.0% |
| CALL_LIST_APPEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,478,924 | 75.4% |
| LOAD_GLOBAL_BUILTIN | 481,200 | 24.5% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| NOP | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 60 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 527,665 | 68.7% |
| LOAD_FAST | 240,060 | 31.3% |
| BINARY_SLICE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 767,905 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,379,033 | 80.9% |
| LOAD_ATTR_SLOT | 767,825 | 18.4% |
| LOAD_FAST_LOAD_FAST | 23,844 | 0.6% |
| LOAD_ATTR | 2,760 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,026,009 | 24.6% |
| PUSH_NULL | 768,165 | 18.4% |
| SWAP | 532,127 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 286,526 | 6.9% |
| BINARY_OP | 280,045 | 6.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,459,747 | 22.6% |
| POP_JUMP_IF_FALSE | 1,732,604 | 15.9% |
| POP_TOP | 1,501,967 | 13.8% |
| STORE_ATTR_SLOT | 1,234,263 | 11.3% |
| POP_JUMP_IF_TRUE | 985,061 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,412,766 | 40.5% |
| STORE_FAST | 2,735,011 | 25.1% |
| COMPARE_OP_INT | 1,713,304 | 15.7% |
| SEND_GEN | 493,560 | 4.5% |
| CALL | 493,501 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 482,640 | 88.8% |
| LOAD_ATTR | 23,684 | 4.4% |
| STORE_FAST | 12,142 | 2.2% |
| RESUME_CHECK | 12,022 | 2.2% |
| CALL_LEN | 11,842 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 494,602 | 91.0% |
| PUSH_NULL | 35,586 | 6.5% |
| COMPARE_OP_INT | 11,882 | 2.2% |
| LOAD_CONST | 420 | 0.1% |
| LOAD_ATTR | 220 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,196,354 | 15.2% |
| STORE_FAST | 9,013,981 | 13.4% |
| POP_JUMP_IF_FALSE | 7,419,092 | 11.1% |
| LOAD_CONST | 4,412,766 | 6.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,225,938 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 22,093,469 | 32.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,550,029 | 8.3% |
| LOAD_ATTR_SLOT | 5,211,305 | 7.8% |
| CALL_PY_EXACT_ARGS | 4,714,238 | 7.0% |
| RETURN_VALUE | 3,444,991 | 5.1% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,481,643 | 24.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,299,173 | 21.4% |
| PUSH_NULL | 746,583 | 12.3% |
| LOAD_FAST_LOAD_FAST | 489,420 | 8.1% |
| LOAD_GLOBAL_MODULE | 481,620 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,976,084 | 32.5% |
| LOAD_FAST | 1,262,087 | 20.8% |
| CALL | 500,182 | 8.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,622 | 8.1% |
| LOAD_FAST_LOAD_FAST | 489,420 | 8.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320 | 15.2% |
| STORE_FAST | 280 | 13.3% |
| POP_TOP | 280 | 13.3% |
| LOAD_FAST | 200 | 9.5% |
| STORE_ATTR_INSTANCE_VALUE | 140 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,560 | 74.3% |
| LOAD_GLOBAL_BUILTIN | 520 | 24.8% |
| LOAD_ATTR | 20 | 1.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 140 | 100.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 540 | 64.3% |
| CALL_KW | 120 | 14.3% |
| COPY_FREE_VARS | 60 | 7.1% |
| CALL_FUNCTION_EX | 60 | 7.1% |
| CACHE | 60 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 540 | 64.3% |
| RETURN_GENERATOR | 180 | 21.4% |
| RESUME_CHECK | 120 | 14.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 6,793,792 | 49.6% |
| COMPARE_OP_INT | 2,783,617 | 20.3% |
| TO_BOOL_INT | 2,156,269 | 15.7% |
| TO_BOOL_LIST | 1,196,580 | 8.7% |
| TO_BOOL_NONE | 496,500 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,419,092 | 54.2% |
| LOAD_CONST | 1,732,604 | 12.7% |
| RETURN_CONST | 1,026,868 | 7.5% |
| POP_TOP | 1,018,648 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 721,120 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 981,562 | 57.0% |
| LOAD_ATTR_INSTANCE_VALUE | 739,421 | 43.0% |
| LOAD_ATTR | 120 | 0.0% |
| CALL | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,479,063 | 85.9% |
| LOAD_CONST | 240,360 | 14.0% |
| RETURN_CONST | 900 | 0.1% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 260 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,509,688 | 86.2% |
| LOAD_ATTR_INSTANCE_VALUE | 240,900 | 13.8% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020,887 | 58.3% |
| LOAD_FAST_LOAD_FAST | 247,620 | 14.1% |
| LOAD_GLOBAL_MODULE | 247,461 | 14.1% |
| LOAD_CONST | 234,120 | 13.4% |
| RETURN_CONST | 240 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,232,606 | 44.1% |
| TO_BOOL | 1,819,256 | 36.0% |
| TO_BOOL_INT | 1,007,166 | 19.9% |
| COMPARE_OP_INT | 240 | 0.0% |
| CONTAINS_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,832,242 | 56.0% |
| LOAD_CONST | 985,061 | 19.5% |
| STORE_FAST | 480,960 | 9.5% |
| NOP | 246,341 | 4.9% |
| JUMP_BACKWARD | 240,300 | 4.7% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 60 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 60 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,040,950 | 35.1% |
| POP_JUMP_IF_FALSE | 1,026,868 | 17.6% |
| STORE_FAST | 1,008,745 | 17.3% |
| STORE_ATTR_SLOT | 740,662 | 12.7% |
| STORE_ATTR_INSTANCE_VALUE | 481,740 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,791,403 | 82.3% |
| INTERPRETER_EXIT | 777,006 | 13.3% |
| END_SEND | 252,660 | 4.3% |
| EXIT_INIT_CHECK | 420 | 0.0% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 246,720 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 246,600 | 50.0% |
| SEND | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 246,600 | 50.0% |
| END_SEND | 246,600 | 50.0% |
| SEND | 280 | 0.1% |
| SEND_GEN | 120 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 300 | 83.3% |
| LOAD_FAST_LOAD_FAST | 60 | 16.7% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,380 | 61.1% |
| LOAD_FAST_LOAD_FAST | 400 | 17.7% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 10.6% |
| STORE_ATTR | 160 | 7.1% |
| SWAP | 80 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,320 | 58.4% |
| LOAD_FAST | 300 | 13.3% |
| LOAD_CONST | 180 | 8.0% |
| STORE_ATTR | 160 | 7.1% |
| RETURN_CONST | 120 | 5.3% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 36.4% |
| CALL_KW | 120 | 18.2% |
| BUILD_LIST | 120 | 18.2% |
| BINARY_OP_ADD_INT | 120 | 18.2% |
| CALL | 60 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 54.5% |
| LOAD_CONST | 120 | 18.2% |
| LOAD_FAST_LOAD_FAST | 60 | 9.1% |
| LOAD_DEREF | 60 | 9.1% |
| BUILD_LIST | 60 | 9.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,735,011 | 18.4% |
| RETURN_VALUE | 2,477,488 | 16.7% |
| CALL | 1,520,090 | 10.2% |
| CALL_LEN | 1,001,624 | 6.7% |
| LOAD_FAST | 985,064 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,013,981 | 60.7% |
| JUMP_FORWARD | 1,719,284 | 11.6% |
| RETURN_CONST | 1,008,745 | 6.8% |
| NOP | 974,302 | 6.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 532,127 | 3.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,697 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,092,337 | 99.9% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| STORE_FAST | 60 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 532,127 | 99.8% |
| BINARY_OP_ADD_INT | 240 | 0.0% |
| BUILD_TUPLE | 180 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 532,127 | 99.8% |
| STORE_ATTR_INSTANCE_VALUE | 280 | 0.1% |
| POP_TOP | 180 | 0.0% |
| COPY | 120 | 0.0% |
| STORE_ATTR | 80 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 60 | 30.0% |
| RETURN_VALUE | 40 | 20.0% |
| LOAD_FAST | 40 | 20.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 20 | 10.0% |
| CALL | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 140 | 70.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 30.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 734,040 | 74.8% |
| SEND | 246,600 | 25.1% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 734,040 | 74.8% |
| INTERPRETER_EXIT | 246,720 | 25.2% |


</details>

### BINARY_OP_ADD_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 480,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480,960 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 240,180 | 99.9% |
| LOAD_CONST | 280 | 0.1% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,180 | 99.9% |
| SWAP | 240 | 0.1% |
| STORE_DEREF | 120 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,180 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 240,220 | 100.0% |
| COMPARE_OP | 20 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,000 | 98.0% |
| LOAD_CONST | 80 | 1.3% |
| BINARY_OP | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000 | 98.0% |
| SWAP | 120 | 2.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 11,902 | 93.4% |
| LOAD_FAST | 820 | 6.4% |
| BINARY_SUBSCR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,842 | 92.9% |
| RETURN_VALUE | 600 | 4.7% |
| PUSH_EXC_INFO | 300 | 2.4% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 80.0% |
| LOAD_FAST_LOAD_FAST | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 300 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| BINARY_SUBSCR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 40 | 66.7% |
| UNPACK_SEQUENCE | 20 | 33.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 160 | 38.1% |
| CALL | 100 | 23.8% |
| LOAD_FAST | 80 | 19.0% |
| PUSH_NULL | 40 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240 | 57.1% |
| COPY_FREE_VARS | 180 | 42.9% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,240 | 95.3% |
| CALL_BUILTIN_CLASS | 11,842 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,240 | 95.3% |
| COPY_FREE_VARS | 11,842 | 4.7% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 493,022 | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE | 45,785 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 481,140 | 89.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,625 | 8.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 11,842 | 2.2% |
| LOAD_FAST | 180 | 0.0% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 420 | 77.8% |
| LOAD_ATTR_SLOT | 120 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 240 | 44.4% |
| COPY | 180 | 33.3% |
| POP_TOP | 120 | 22.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 45,625 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,625 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 50.0% |
| CALL | 80 | 33.3% |
| LOAD_CONST | 40 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 180 | 75.0% |
| CALL_BUILTIN_CLASS | 40 | 16.7% |
| CALL | 20 | 8.3% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 985,744 | 99.3% |
| BUILD_TUPLE | 6,040 | 0.6% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| CALL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 992,104 | 100.0% |
| TO_BOOL | 100 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,923,000 | 86.8% |
| LOAD_FAST | 291,726 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,001,624 | 45.2% |
| COPY | 480,960 | 21.7% |
| LOAD_CONST | 240,180 | 10.8% |
| BINARY_OP_ADD_INT | 240,180 | 10.8% |
| LOAD_FAST | 239,940 | 10.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 280,045 | 99.9% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 280,165 | 99.9% |
| JUMP_FORWARD | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 492,622 | 48.6% |
| LOAD_FAST | 280,045 | 27.6% |
| RETURN_VALUE | 240,240 | 23.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 520,285 | 51.4% |
| RETURN_VALUE | 492,622 | 48.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 480,960 | 49.4% |
| LOAD_FAST | 252,082 | 25.9% |
| LOAD_ATTR | 240,240 | 24.7% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 492,322 | 50.6% |
| STORE_FAST | 480,960 | 49.4% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 568,549 | 69.6% |
| LOAD_ATTR | 247,040 | 30.3% |
| CALL | 440 | 0.1% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 567,549 | 69.5% |
| TO_BOOL_BOOL | 247,000 | 30.3% |
| POP_TOP | 540 | 0.1% |
| LOAD_FAST | 420 | 0.1% |
| CALL | 280 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 786,325 | 95.8% |
| BINARY_SLICE | 33,704 | 4.1% |
| CALL | 480 | 0.1% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 820,689 | 100.0% |
| PUSH_EXC_INFO | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,762,701 | 47.1% |
| LOAD_FAST | 4,714,238 | 38.5% |
| LOAD_ATTR_METHOD_NO_DICT | 774,226 | 6.3% |
| BUILD_TUPLE | 252,062 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 246,261 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,247,506 | 91.9% |
| COPY_FREE_VARS | 493,522 | 4.0% |
| RETURN_GENERATOR | 493,080 | 4.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 492,502 | 99.8% |
| LOAD_ATTR_METHOD_NO_DICT | 300 | 0.1% |
| LOAD_CONST | 240 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 493,162 | 100.0% |
| RETURN_GENERATOR | 120 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 75.0% |
| LOAD_GLOBAL_MODULE | 180 | 25.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,713,304 | 61.5% |
| LOAD_GLOBAL_MODULE | 480,960 | 17.3% |
| BINARY_OP_MULTIPLY_INT | 240,220 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 239,940 | 8.6% |
| LOAD_ATTR_SLOT | 45,625 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,783,617 | 100.0% |
| POP_JUMP_IF_TRUE | 240 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 66.7% |
| COMPARE_OP | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| POP_JUMP_IF_FALSE | 60 | 33.3% |
| COPY | 60 | 33.3% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 962,500 | 63.2% |
| JUMP_BACKWARD | 560,390 | 36.8% |
| FOR_ITER | 80 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 560,090 | 36.8% |
| RETURN_CONST | 481,140 | 31.6% |
| LOAD_FAST | 480,960 | 31.6% |
| STORE_FAST | 600 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 533,785 | 52.6% |
| GET_ITER | 481,080 | 47.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 533,845 | 52.6% |
| LOAD_CONST | 480,960 | 47.4% |
| LOAD_FAST | 60 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 60 | 50.0% |
| GET_ITER | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 33.3% |
| LOAD_GLOBAL | 20 | 16.7% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,093,469 | 96.7% |
| LOAD_ATTR_INSTANCE_VALUE | 492,502 | 2.2% |
| LOAD_FAST_LOAD_FAST | 252,822 | 1.1% |
| LOAD_ATTR | 1,160 | 0.0% |
| COPY | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,428,508 | 19.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,020,654 | 13.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,973,626 | 13.0% |
| RETURN_VALUE | 2,710,285 | 11.9% |
| CALL_LEN | 1,923,000 | 8.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,020,654 | 63.9% |
| LOAD_FAST | 1,421,206 | 30.1% |
| LOAD_ATTR | 286,526 | 6.1% |
| LOAD_ATTR_SLOT | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,084,958 | 44.1% |
| LOAD_FAST_LOAD_FAST | 1,299,173 | 27.5% |
| CALL_PY_EXACT_ARGS | 774,226 | 16.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 568,549 | 12.0% |
| LOAD_GLOBAL_MODULE | 620 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,550,029 | 51.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,973,626 | 27.7% |
| LOAD_ATTR_SLOT | 1,472,464 | 13.7% |
| RETURN_VALUE | 492,702 | 4.6% |
| LOAD_FAST_LOAD_FAST | 240,240 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,762,701 | 53.7% |
| LOAD_FAST | 4,225,938 | 39.4% |
| LOAD_FAST_LOAD_FAST | 260,182 | 2.4% |
| LOAD_CONST | 240,480 | 2.2% |
| LOAD_GLOBAL_MODULE | 240,440 | 2.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,566,159 | 100.0% |
| LOAD_ATTR | 1,100 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,511,247 | 58.9% |
| BINARY_OP | 566,011 | 22.0% |
| UNARY_INVERT | 246,161 | 9.6% |
| LOAD_FAST | 240,360 | 9.4% |
| COMPARE_OP | 780 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 498,343 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,142 | 50.6% |
| CALL | 240,240 | 48.2% |
| BINARY_OP | 5,981 | 1.2% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,860 | 99.9% |
| LOAD_ATTR | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,480 | 99.8% |
| COPY_FREE_VARS | 540 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,211,305 | 99.9% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.1% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,472,464 | 28.2% |
| TO_BOOL_BOOL | 1,379,601 | 26.4% |
| LOAD_ATTR | 767,825 | 14.7% |
| LIST_EXTEND | 527,665 | 10.1% |
| BUILD_LIST | 527,665 | 10.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,000,289 | 34.6% |
| LOAD_FAST | 1,231,964 | 21.3% |
| POP_JUMP_IF_FALSE | 721,120 | 12.5% |
| STORE_FAST | 527,005 | 9.1% |
| JUMP_FORWARD | 481,200 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,969,574 | 68.6% |
| CALL_ISINSTANCE | 985,744 | 17.0% |
| LOAD_DEREF | 482,640 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 343,650 | 5.9% |
| BUILD_TUPLE | 6,180 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,832,945 | 42.8% |
| RESUME_CHECK | 1,256,705 | 19.0% |
| NOP | 985,124 | 14.9% |
| POP_TOP | 527,066 | 8.0% |
| POP_JUMP_IF_NOT_NONE | 247,461 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,566,159 | 38.7% |
| BINARY_OP | 1,544,854 | 23.3% |
| LOAD_FAST | 1,024,929 | 15.5% |
| LOAD_FAST_LOAD_FAST | 481,620 | 7.3% |
| COMPARE_OP_INT | 480,960 | 7.3% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 540 | 100.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 481,960 | 100.0% |
| LOAD_SUPER_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,080 | 50.0% |
| LOAD_FAST_LOAD_FAST | 240,600 | 49.9% |
| CALL_PY_EXACT_ARGS | 320 | 0.1% |
| CALL | 100 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 11,247,506 | 69.4% |
| CACHE | 1,998,186 | 12.3% |
| SEND_GEN | 734,040 | 4.5% |
| COPY_FREE_VARS | 518,406 | 3.2% |
| POP_TOP | 493,980 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,196,354 | 62.9% |
| LOAD_GLOBAL_BUILTIN | 2,000,289 | 12.3% |
| NOP | 1,765,651 | 10.9% |
| LOAD_GLOBAL_MODULE | 1,256,705 | 7.8% |
| JUMP_BACKWARD_NO_INTERRUPT | 980,640 | 6.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 734,040 | 59.8% |
| LOAD_CONST | 493,560 | 40.2% |
| SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 734,040 | 59.8% |
| POP_TOP | 493,680 | 40.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,699,740 | 99.8% |
| LOAD_FAST_LOAD_FAST | 2,000 | 0.1% |
| STORE_ATTR | 1,320 | 0.1% |
| SWAP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 975,000 | 57.2% |
| RETURN_CONST | 481,740 | 28.3% |
| NOP | 240,240 | 14.1% |
| LOAD_CONST | 3,780 | 0.2% |
| LOAD_FAST_LOAD_FAST | 720 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,233,146 | 53.1% |
| LOAD_FAST_LOAD_FAST | 1,976,084 | 46.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,481,643 | 35.2% |
| LOAD_CONST | 1,234,263 | 29.3% |
| RETURN_CONST | 740,662 | 17.6% |
| LOAD_FAST | 740,662 | 17.6% |
| NOP | 12,000 | 0.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 252,082 | 99.8% |
| LOAD_CONST | 280 | 0.1% |
| LOAD_FAST | 160 | 0.1% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,142 | 99.8% |
| RETURN_CONST | 120 | 0.0% |
| NOP | 120 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,428,508 | 44.3% |
| RETURN_VALUE | 2,445,063 | 24.5% |
| LOAD_ATTR_SLOT | 1,379,601 | 13.8% |
| CALL_ISINSTANCE | 992,104 | 9.9% |
| COPY | 480,300 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,793,792 | 68.0% |
| POP_JUMP_IF_TRUE | 2,232,606 | 22.4% |
| UNARY_NOT | 960,060 | 9.6% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,545,214 | 48.8% |
| BINARY_OP | 800,330 | 25.3% |
| LOAD_FAST | 532,026 | 16.8% |
| LOAD_ATTR_INSTANCE_VALUE | 285,865 | 9.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,156,269 | 68.2% |
| POP_JUMP_IF_TRUE | 1,007,166 | 31.8% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,196,580 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,196,580 | 100.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 495,360 | 99.8% |
| LOAD_FAST | 740 | 0.1% |
| LOAD_ATTR | 300 | 0.1% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 496,500 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 44.4% |
| UNPACK_SEQUENCE | 60 | 33.3% |
| BINARY_SUBSCR_LIST_INT | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60 | 33.3% |
| STORE_FAST | 60 | 33.3% |
| POP_TOP | 60 | 33.3% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 560,090 | 51.3% |
| STORE_FAST | 532,127 | 48.7% |
| BINARY_SLICE | 180 | 0.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |
| END_SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,092,697 | 100.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


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
|          hit |        13102 | 99.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          120 | 0.0% |
|          hit |       252562 | 99.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 66.7% |
| Failure | 20 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1832118 | 11.0% |
|          hit |     14843153 | 89.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,020 | 56.7% |
| Failure | 780 | 43.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 260 | 33.3% |
| bytes | 220 | 28.2% |
| mapping | 60 | 7.7% |
| dict | 60 | 7.7% |
| bytearray | 60 | 7.7% |
| set | 40 | 5.1% |
| memory view | 40 | 5.1% |
| tuple | 20 | 2.6% |
| float | 20 | 2.6% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3169258 | 76.6% |
|          hit |       967920 | 23.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 14.3% |
| Failure | 960 | 85.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 660 | 68.8% |
| or | 260 | 27.1% |
| multiply different types | 20 | 2.1% |
| floor divide | 20 | 2.1% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3265417 | 13.5% |
|          hit |     20927148 | 86.5% |
|         miss |         1800 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,760 | 51.3% |
| Failure | 2,620 | 48.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 420 | 16.0% |
| class no vectorcall | 400 | 15.3% |
| code complex parameters | 400 | 15.3% |
| meth descr method fastcall keywords | 360 | 13.7% |
| meth descr varargs | 220 | 8.4% |
| class mutable | 200 | 7.6% |
| no dict | 180 | 6.9% |
| cfunc varargs keywords | 120 | 4.6% |
| other | 120 | 4.6% |
| cfunc varargs | 80 | 3.1% |
| operator wrapper | 40 | 1.5% |
| wrong number arguments | 40 | 1.5% |
| init not simple | 20 | 0.8% |
| cmethod | 20 | 0.8% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        12982 | 0.5% |
|          hit |      2784037 | 99.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 41.7% |
| Failure | 280 | 58.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 160 | 57.1% |
| different types | 60 | 21.4% |
| tuple | 40 | 14.3% |
| bool | 20 | 7.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        12240 | 0.5% |
|          hit |      2538015 | 99.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 44.4% |
| Failure | 100 | 55.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 40 | 40.0% |
| other | 40 | 40.0% |
| set | 20 | 20.0% |


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
| specialization.deferred |      4169102 | 8.2% |
|          hit |     46824167 | 91.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,580 | 62.4% |
| Failure | 2,760 | 37.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 880 | 31.9% |
| has managed dict | 700 | 25.4% |
| method | 640 | 23.2% |
| shadowed | 200 | 7.2% |
| metaclass attribute | 120 | 4.3% |
| non object slot | 100 | 3.6% |
| class attr simple | 40 | 1.4% |
| class method obj | 40 | 1.4% |
| class attr descriptor | 20 | 0.7% |
| builtin class method | 20 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     12412135 | 100.0% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,080 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       482640 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       493200 | 28.7% |
|          hit |      1227720 | 71.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 30.0% |
| Failure | 280 | 70.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 280 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          780 | 0.0% |
|          hit |      5912570 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,320 | 89.2% |
| Failure | 160 | 10.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 60 | 37.5% |
| overriding descriptor | 40 | 25.0% |
| overridden | 40 | 25.0% |
| no dict | 20 | 12.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1092997 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 150,677,574 | 48.0% |
| Not specialized | 37,305,917 | 11.9% |
| Specialized | 126,240,225 | 40.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 4,169,102 | 32.2% |
| CALL | 3,265,417 | 25.2% |
| BINARY_OP | 3,169,258 | 24.5% |
| TO_BOOL | 1,832,118 | 14.1% |
| SEND | 493,200 | 3.8% |
| COMPARE_OP | 12,982 | 0.1% |
| FOR_ITER | 12,240 | 0.1% |
| STORE_ATTR | 780 | 0.0% |
| STORE_SUBSCR | 120 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,260 | 67.7% |
| CALL_METHOD_DESCRIPTOR_O | 480 | 25.8% |
| LOAD_GLOBAL_BUILTIN | 60 | 3.2% |
| CALL_BUILTIN_O | 60 | 3.2% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNARY_NOT | 0 | 0.0% |
| UNARY_INVERT | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 1,999,326 | 12.0% |
| Calls to Python functions inlined | 14,708,795 | 88.0% |
| Calls via PyEval_EvalFrame (total) | 1,999,326 | 12.0% |
| Calls via PyEval_EvalFrame (vector) | 1,752,306 | 10.5% |
| Calls via PyEval_EvalFrame (generator) | 247,020 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,752,306 | 10.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 840 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 494,520 | 3.0% |
| Frames pushed | 15,233,801 | 91.2% |
| Frame objects created | 780 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 7,207,996 | 43.1% |
| Frees to freelist | 7,219,958 |  |
| Allocations | 9,524,053 | 56.9% |
| Allocations to 512 bytes | 9,042,739 | 54.0% |
| Allocations to 4 kbytes | 360 | 0.0% |
| Allocations over 4 kbytes | 480,954 | 2.9% |
| Frees | 9,871,508 |  |
| New values | 420 |  |
| Interpreter increfs | 130,100,535 | 84.3% |
| Interpreter decrefs | 142,041,107 | 83.8% |
| Increfs | 24,205,002 | 15.7% |
| Decrefs | 27,529,399 | 16.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 4,671,790 |  |
| Method cache misses | 1,312 |  |
| Method cache collisions | 1,423 |  |
| Method cache dunder hits | 1,271,673 |  |
| Method cache dunder misses | 135 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 0 | 19,240 |
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
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-10-19
