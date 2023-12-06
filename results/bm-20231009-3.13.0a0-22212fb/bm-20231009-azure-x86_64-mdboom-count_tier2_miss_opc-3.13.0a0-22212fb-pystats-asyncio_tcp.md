
# Pystats results

- benchmark: asyncio_tcp
- fork: mdboom
- ref: count-tier2-miss-opcodes
- commit hash: 22212fb
- commit date: 2023-10-09T12:01:25-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 67,090,526 | 21.4% | 21.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 22,840,381 | 7.3% | 28.6% |  |
| RESUME_CHECK | 16,214,207 | 5.2% | 33.8% |  |
| STORE_FAST | 14,851,493 | 4.7% | 38.5% |  |
| POP_JUMP_IF_FALSE | 13,694,824 | 4.4% | 42.9% |  |
| CALL_PY_EXACT_ARGS | 12,234,134 | 3.9% | 46.8% |  |
| LOAD_CONST | 10,886,346 | 3.5% | 50.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,730,767 | 3.4% | 53.6% |  |
| TO_BOOL_BOOL | 9,986,562 | 3.2% | 56.8% |  |
| POP_TOP | 9,633,002 | 3.1% | 59.9% |  |
| RETURN_VALUE | 9,411,670 | 3.0% | 62.9% |  |
| LOAD_GLOBAL_MODULE | 6,623,403 | 2.1% | 65.0% |  |
| LOAD_FAST_LOAD_FAST | 6,072,579 | 1.9% | 66.9% |  |
| RETURN_CONST | 5,821,845 | 1.9% | 68.8% |  |
| LOAD_GLOBAL_BUILTIN | 5,789,008 | 1.8% | 70.6% | 0.0% |
| LOAD_ATTR_SLOT | 5,217,505 | 1.7% | 72.3% |  |
| POP_JUMP_IF_TRUE | 5,059,682 | 1.6% | 73.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,728,736 | 1.5% | 75.4% |  |
| STORE_ATTR_SLOT | 4,209,276 | 1.3% | 76.7% |  |
| LOAD_ATTR | 4,176,508 | 1.3% | 78.1% |  |
| NOP | 3,766,145 | 1.2% | 79.3% |  |
| CALL | 3,270,809 | 1.0% | 80.3% |  |
| BINARY_OP | 3,170,486 | 1.0% | 81.3% |  |
| TO_BOOL_INT | 3,163,585 | 1.0% | 82.3% |  |
| COMPARE_OP_INT | 2,783,913 | 0.9% | 83.2% |  |
| LOAD_ATTR_MODULE | 2,567,429 | 0.8% | 84.0% |  |
| PUSH_NULL | 2,316,620 | 0.7% | 84.8% |  |
| CALL_LEN | 2,214,734 | 0.7% | 85.5% |  |
| COPY | 2,026,216 | 0.6% | 86.1% |  |
| INTERPRETER_EXIT | 1,999,334 | 0.6% | 86.7% |  |
| JUMP_FORWARD | 1,960,384 | 0.6% | 87.4% |  |
| TO_BOOL | 1,833,960 | 0.6% | 87.9% |  |
| JUMP_BACKWARD | 1,821,472 | 0.6% | 88.5% |  |
| POP_JUMP_IF_NOT_NONE | 1,750,912 | 0.6% | 89.1% |  |
| POP_JUMP_IF_NONE | 1,721,289 | 0.5% | 89.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,703,154 | 0.5% | 90.2% |  |
| FOR_ITER_LIST | 1,523,046 | 0.5% | 90.7% |  |
| GET_ITER | 1,449,954 | 0.5% | 91.1% |  |
| BUILD_LIST | 1,249,951 | 0.4% | 91.5% |  |
| SEND_GEN | 1,227,710 | 0.4% | 91.9% |  |
| TO_BOOL_LIST | 1,196,696 | 0.4% | 92.3% |  |
| STORE_FAST_STORE_FAST | 1,092,979 | 0.3% | 92.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,859 | 0.3% | 93.0% |  |
| FOR_ITER_RANGE | 1,014,871 | 0.3% | 93.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,012,929 | 0.3% | 93.6% |  |
| CALL_ISINSTANCE | 992,228 | 0.3% | 93.9% |  |
| YIELD_VALUE | 980,752 | 0.3% | 94.3% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 980,632 | 0.3% | 94.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 973,352 | 0.3% | 94.9% |  |
| UNARY_NOT | 960,120 | 0.3% | 95.2% |  |
| CALL_METHOD_DESCRIPTOR_O | 820,761 | 0.3% | 95.4% | 0.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 816,381 | 0.3% | 95.7% | 0.2% |
| BUILD_TUPLE | 779,889 | 0.2% | 96.0% |  |
| CALL_FUNCTION_EX | 768,273 | 0.2% | 96.2% |  |
| CALL_INTRINSIC_1 | 767,913 | 0.2% | 96.4% |  |
| LIST_EXTEND | 767,913 | 0.2% | 96.7% |  |
| END_SEND | 740,274 | 0.2% | 96.9% |  |
| GET_AWAITABLE | 740,274 | 0.2% | 97.2% |  |
| LOAD_DEREF | 543,830 | 0.2% | 97.3% |  |
| CALL_BUILTIN_CLASS | 539,229 | 0.2% | 97.5% |  |
| SWAP | 532,989 | 0.2% | 97.7% |  |
| COPY_FREE_VARS | 518,562 | 0.2% | 97.8% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 498,379 | 0.2% | 98.0% |  |
| TO_BOOL_NONE | 496,496 | 0.2% | 98.2% |  |
| RETURN_GENERATOR | 493,976 | 0.2% | 98.3% |  |
| SEND | 493,596 | 0.2% | 98.5% |  |
| CALL_PY_WITH_DEFAULTS | 493,294 | 0.2% | 98.6% |  |
| UNARY_INVERT | 486,407 | 0.2% | 98.8% |  |
| LOAD_SUPER_ATTR_METHOD | 482,100 | 0.2% | 98.9% |  |
| BINARY_OP_ADD_FLOAT | 480,958 | 0.2% | 99.1% |  |
| CALL_LIST_APPEND | 280,355 | 0.1% | 99.2% |  |
| BINARY_SLICE | 280,235 | 0.1% | 99.3% |  |
| CALL_KW | 260,132 | 0.1% | 99.3% |  |
| STORE_SUBSCR_DICT | 252,574 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 252,092 | 0.1% | 99.5% |  |
| CONTAINS_OP | 241,080 | 0.1% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 241,018 | 0.1% | 99.7% |  |
| BINARY_OP_ADD_INT | 240,538 | 0.1% | 99.7% |  |
| DELETE_SUBSCR | 240,238 | 0.1% | 99.8% |  |
| BUILD_SLICE | 240,238 | 0.1% | 99.9% |  |
| BINARY_OP_MULTIPLY_INT | 240,238 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,637 | 0.0% | 100.0% |  |
| COMPARE_OP | 13,474 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 12,754 | 0.0% | 100.0% |  |
| FOR_ITER | 12,420 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 6,120 | 0.0% | 100.0% |  |
| STORE_ATTR | 2,200 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,100 | 0.0% | 100.0% |  |
| IS_OP | 1,020 | 0.0% | 100.0% |  |
| MAKE_CELL | 840 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 720 | 0.0% | 100.0% |  |
| STORE_DEREF | 660 | 0.0% | 100.0% |  |
| BUILD_MAP | 540 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 540 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 540 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 480 | 0.0% | 100.0% |  |
| POP_EXCEPT | 480 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 480 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 420 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 420 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 360 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 360 | 0.0% | 100.0% |  |
| BUILD_SET | 300 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 300 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 300 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 240 | 0.0% | 100.0% | 25.0% |
| UNPACK_SEQUENCE | 200 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 180 | 0.0% | 100.0% |  |
| DICT_MERGE | 180 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 180 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 140 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 120 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| LIST_APPEND | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 60 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 22,093,553 | 7.0% | 7.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 11,247,524 | 3.6% | 10.6% |
| RESUME_CHECK LOAD_FAST | 10,196,452 | 3.2% | 13.9% |
| STORE_FAST LOAD_FAST | 9,014,079 | 2.9% | 16.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,419,246 | 2.4% | 19.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,793,886 | 2.2% | 21.2% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,762,679 | 1.8% | 23.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,550,011 | 1.8% | 24.8% |
| LOAD_FAST LOAD_ATTR_SLOT | 5,211,405 | 1.7% | 26.5% |
| RETURN_CONST POP_TOP | 4,791,327 | 1.5% | 28.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,714,298 | 1.5% | 29.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 4,428,516 | 1.4% | 30.9% |
| LOAD_CONST LOAD_FAST | 4,412,666 | 1.4% | 32.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 4,226,000 | 1.3% | 33.7% |
| POP_TOP LOAD_FAST | 4,000,529 | 1.3% | 35.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,969,608 | 1.3% | 36.2% |
| LOAD_FAST RETURN_VALUE | 3,445,049 | 1.1% | 37.3% |
| LOAD_FAST LOAD_ATTR | 3,379,067 | 1.1% | 38.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 3,020,690 | 1.0% | 39.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 2,973,656 | 0.9% | 40.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,833,013 | 0.9% | 41.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 2,832,288 | 0.9% | 42.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,783,673 | 0.9% | 43.0% |
| NOP LOAD_FAST | 2,780,337 | 0.9% | 43.9% |
| LOAD_CONST STORE_FAST | 2,735,045 | 0.9% | 44.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,710,311 | 0.9% | 45.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,566,209 | 0.8% | 46.4% |
| RETURN_VALUE STORE_FAST | 2,477,530 | 0.8% | 47.2% |
| LOAD_FAST LOAD_CONST | 2,459,781 | 0.8% | 48.0% |
| RETURN_VALUE TO_BOOL_BOOL | 2,445,079 | 0.8% | 48.8% |
| LOAD_FAST STORE_ATTR_SLOT | 2,233,176 | 0.7% | 49.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,232,616 | 0.7% | 50.2% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,156,345 | 0.7% | 50.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,085,002 | 0.7% | 51.5% |
| POP_TOP RETURN_CONST | 2,040,904 | 0.6% | 52.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,000,323 | 0.6% | 52.8% |
| CACHE RESUME_CHECK | 1,998,194 | 0.6% | 53.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,976,100 | 0.6% | 54.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,922,992 | 0.6% | 54.7% |
| TO_BOOL POP_JUMP_IF_TRUE | 1,819,286 | 0.6% | 55.3% |
| RESUME_CHECK NOP | 1,765,635 | 0.6% | 55.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,732,622 | 0.6% | 56.4% |
| STORE_FAST JUMP_FORWARD | 1,719,304 | 0.5% | 57.0% |
| LOAD_CONST COMPARE_OP_INT | 1,713,322 | 0.5% | 57.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,699,614 | 0.5% | 58.0% |
| COPY TO_BOOL_INT | 1,545,256 | 0.5% | 58.5% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,544,896 | 0.5% | 59.0% |
| CALL STORE_FAST | 1,520,186 | 0.5% | 59.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,511,265 | 0.5% | 60.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,509,714 | 0.5% | 60.5% |
| POP_TOP LOAD_CONST | 1,501,923 | 0.5% | 60.9% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,481,655 | 0.5% | 61.4% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,479,071 | 0.5% | 61.9% |
| JUMP_FORWARD LOAD_FAST | 1,478,946 | 0.5% | 62.4% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 1,472,486 | 0.5% | 62.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,421,264 | 0.5% | 63.3% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,379,647 | 0.4% | 63.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 1,299,211 | 0.4% | 64.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,262,107 | 0.4% | 64.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,256,711 | 0.4% | 64.9% |
| STORE_ATTR_SLOT LOAD_CONST | 1,234,277 | 0.4% | 65.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,231,986 | 0.4% | 65.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 1,196,576 | 0.4% | 66.1% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 1,196,576 | 0.4% | 66.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,092,739 | 0.3% | 66.8% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,092,379 | 0.3% | 67.2% |
| BINARY_OP COPY | 1,064,298 | 0.3% | 67.5% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,026,892 | 0.3% | 67.8% |
| LOAD_ATTR LOAD_FAST | 1,026,043 | 0.3% | 68.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,024,965 | 0.3% | 68.5% |
| LOAD_FAST TO_BOOL | 1,024,810 | 0.3% | 68.8% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,020,907 | 0.3% | 69.1% |
| POP_JUMP_IF_FALSE POP_TOP | 1,018,676 | 0.3% | 69.5% |
| STORE_FAST RETURN_CONST | 1,008,751 | 0.3% | 69.8% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 1,007,180 | 0.3% | 70.1% |
| CALL RETURN_VALUE | 1,002,033 | 0.3% | 70.4% |
| CALL_LEN STORE_FAST | 1,001,626 | 0.3% | 70.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 992,128 | 0.3% | 71.1% |
| RETURN_VALUE RETURN_VALUE | 986,228 | 0.3% | 71.4% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 985,768 | 0.3% | 71.7% |
| NOP LOAD_GLOBAL_MODULE | 985,188 | 0.3% | 72.0% |
| LOAD_FAST STORE_FAST | 985,088 | 0.3% | 72.3% |
| POP_JUMP_IF_TRUE LOAD_CONST | 985,065 | 0.3% | 72.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 981,568 | 0.3% | 72.9% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 980,632 | 0.3% | 73.3% |
| RETURN_VALUE INTERPRETER_EXIT | 975,296 | 0.3% | 73.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 974,998 | 0.3% | 73.9% |
| STORE_FAST NOP | 974,372 | 0.3% | 74.2% |
| LOAD_FAST GET_ITER | 962,576 | 0.3% | 74.5% |
| GET_ITER FOR_ITER_LIST | 962,496 | 0.3% | 74.8% |
| TO_BOOL_BOOL UNARY_NOT | 960,060 | 0.3% | 75.1% |
| PUSH_NULL LOAD_FAST | 839,896 | 0.3% | 75.4% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 820,701 | 0.3% | 75.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 807,190 | 0.3% | 75.9% |
| BINARY_OP TO_BOOL_INT | 800,350 | 0.3% | 76.1% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 786,331 | 0.3% | 76.4% |
| BINARY_OP STORE_FAST | 778,496 | 0.2% | 76.6% |
| RETURN_CONST INTERPRETER_EXIT | 777,020 | 0.2% | 76.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 774,240 | 0.2% | 77.1% |
| LOAD_ATTR PUSH_NULL | 768,173 | 0.2% | 77.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,238 | 85.7% |
| LOAD_CONST | 39,997 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,238 | 85.7% |
| CALL_METHOD_DESCRIPTOR_O | 33,710 | 12.0% |
| STORE_FAST | 5,927 | 2.1% |
| LIST_EXTEND | 180 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.1% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,998,194 | 99.9% |
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
| LOAD_CONST | 20 | 50.0% |
| LOAD_FAST | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 20 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 20 | 50.0% |


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
| BUILD_SLICE | 240,238 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,238 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 252,658 | 34.1% |
| SEND | 246,598 | 33.3% |
| RETURN_VALUE | 241,018 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 499,376 | 67.5% |
| STORE_FAST | 240,598 | 32.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


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
| LOAD_FAST | 962,576 | 66.4% |
| CALL_BUILTIN_CLASS | 481,138 | 33.2% |
| LOAD_ATTR_INSTANCE_VALUE | 6,060 | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 962,496 | 66.4% |
| FOR_ITER_RANGE | 481,078 | 33.2% |
| FOR_ITER | 6,260 | 0.4% |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% |
| FOR_ITER_TUPLE | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 975,296 | 48.8% |
| RETURN_CONST | 777,020 | 38.9% |
| YIELD_VALUE | 246,718 | 12.3% |
| RETURN_GENERATOR | 300 | 0.0% |


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
| RESUME_CHECK | 1,765,635 | 46.9% |
| STORE_FAST | 974,372 | 25.9% |
| POP_JUMP_IF_FALSE | 520,895 | 13.8% |
| POP_JUMP_IF_TRUE | 246,345 | 6.5% |
| STORE_ATTR_INSTANCE_VALUE | 240,238 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,780,337 | 73.8% |
| LOAD_GLOBAL_MODULE | 985,188 | 26.2% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 360 | 75.0% |
| COPY | 60 | 12.5% |
| SWAP | 60 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240 | 50.0% |
| POP_TOP | 60 | 12.5% |
| RETURN_VALUE | 60 | 12.5% |
| LOAD_CONST | 60 | 12.5% |
| RERAISE | 60 | 12.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,791,327 | 49.7% |
| POP_JUMP_IF_FALSE | 1,018,676 | 10.6% |
| CALL_METHOD_DESCRIPTOR_O | 820,701 | 8.5% |
| CALL_FUNCTION_EX | 767,853 | 8.0% |
| END_SEND | 499,376 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,000,529 | 41.5% |
| RETURN_CONST | 2,040,904 | 21.2% |
| LOAD_CONST | 1,501,923 | 15.6% |
| JUMP_BACKWARD | 579,730 | 6.0% |
| LOAD_GLOBAL_MODULE | 527,122 | 5.5% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 300 | 62.5% |
| RERAISE | 60 | 12.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60 | 12.5% |
| CALL_METHOD_DESCRIPTOR_O | 60 | 12.5% |

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
| LOAD_ATTR_MODULE | 1,511,265 | 65.2% |
| LOAD_ATTR | 768,173 | 33.2% |
| LOAD_DEREF | 35,622 | 1.5% |
| LOAD_FAST | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 839,896 | 36.3% |
| LOAD_FAST_LOAD_FAST | 746,599 | 32.2% |
| CALL | 729,465 | 31.5% |
| LOAD_CONST | 360 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 493,076 | 99.8% |
| CALL_KW | 300 | 0.1% |
| CACHE | 240 | 0.0% |
| MAKE_CELL | 180 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 493,376 | 99.9% |
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
| LOAD_FAST | 3,445,049 | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,710,311 | 28.8% |
| CALL | 1,002,033 | 10.6% |
| RETURN_VALUE | 986,228 | 10.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,634 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,477,530 | 26.3% |
| TO_BOOL_BOOL | 2,445,079 | 26.0% |
| RETURN_VALUE | 986,228 | 10.5% |
| INTERPRETER_EXIT | 975,296 | 10.4% |
| LOAD_FAST | 761,493 | 8.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 120 | 66.7% |
| STORE_SUBSCR | 20 | 11.1% |
| LOAD_CONST | 20 | 11.1% |
| LOAD_FAST | 20 | 11.1% |

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
| LOAD_FAST | 1,024,810 | 55.9% |
| LOAD_ATTR_INSTANCE_VALUE | 807,190 | 44.0% |
| TO_BOOL | 780 | 0.0% |
| LOAD_ATTR | 560 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,819,286 | 99.2% |
| POP_JUMP_IF_FALSE | 12,874 | 0.7% |
| TO_BOOL_BOOL | 860 | 0.0% |
| TO_BOOL | 780 | 0.0% |
| TO_BOOL_NONE | 100 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 246,167 | 50.6% |
| BINARY_OP | 240,240 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 486,407 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 1,544,896 | 48.7% |
| LOAD_ATTR_MODULE | 566,037 | 17.9% |
| UNARY_INVERT | 486,407 | 15.3% |
| POP_JUMP_IF_FALSE | 285,864 | 9.0% |
| LOAD_ATTR | 280,055 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,064,298 | 33.6% |
| TO_BOOL_INT | 800,350 | 25.2% |
| STORE_FAST | 778,496 | 24.6% |
| BUILD_TUPLE | 280,055 | 8.8% |
| UNARY_INVERT | 240,240 | 7.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 527,673 | 42.2% |
| STORE_FAST | 481,078 | 38.5% |
| LOAD_FAST_LOAD_FAST | 240,060 | 19.2% |
| LOAD_FAST | 480 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 768,153 | 61.5% |
| STORE_FAST | 481,438 | 38.5% |
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
| POP_TOP | 60 | 11.1% |
| LOAD_FAST | 60 | 11.1% |
| POP_JUMP_IF_NOT_NONE | 60 | 11.1% |
| STORE_FAST | 60 | 11.1% |

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
| LOAD_FAST | 240,238 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 240,238 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 280,055 | 35.9% |
| LOAD_CONST | 246,107 | 31.6% |
| LOAD_FAST | 240,720 | 30.9% |
| LOAD_FAST_LOAD_FAST | 6,527 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 6,180 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 280,055 | 35.9% |
| CALL_PY_EXACT_ARGS | 252,074 | 32.3% |
| CALL | 240,280 | 30.8% |
| CALL_ISINSTANCE | 6,040 | 0.8% |
| LOAD_CONST | 360 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 729,465 | 22.3% |
| LOAD_FAST_LOAD_FAST | 500,192 | 15.3% |
| LOAD_CONST | 493,505 | 15.1% |
| LOAD_ATTR_INSTANCE_VALUE | 487,123 | 14.9% |
| LOAD_ATTR | 240,760 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,520,186 | 46.5% |
| RETURN_VALUE | 1,002,033 | 30.6% |
| POP_TOP | 247,978 | 7.6% |
| RESUME_CHECK | 247,007 | 7.6% |
| LOAD_CONST | 240,298 | 7.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 767,913 | 100.0% |
| DICT_MERGE | 180 | 0.0% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 767,853 | 99.9% |
| RESUME_CHECK | 180 | 0.0% |
| GET_AWAITABLE | 120 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 767,913 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 767,913 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 260,132 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 246,658 | 94.8% |
| COPY_FREE_VARS | 11,854 | 4.6% |
| STORE_FAST | 600 | 0.2% |
| RETURN_GENERATOR | 300 | 0.1% |
| RESUME_CHECK | 300 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 11,854 | 88.0% |
| LOAD_ATTR_MODULE | 780 | 5.8% |
| LOAD_CONST | 400 | 3.0% |
| COMPARE_OP | 280 | 2.1% |
| CALL_BUILTIN_CLASS | 120 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,934 | 96.0% |
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
| LOAD_FAST | 180 | 0.1% |
| LOAD_GLOBAL_MODULE | 180 | 0.1% |
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
| BINARY_OP | 1,064,298 | 52.5% |
| CALL_LEN | 480,958 | 23.7% |
| UNARY_NOT | 480,060 | 23.7% |
| LOAD_FAST | 360 | 0.0% |
| CALL_BUILTIN_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,545,256 | 76.3% |
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
| CALL_PY_EXACT_ARGS | 493,534 | 95.2% |
| CALL_KW | 11,854 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 11,854 | 2.3% |
| CACHE | 540 | 0.1% |
| LOAD_ATTR_PROPERTY | 540 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 518,442 | 100.0% |
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
| RETURN_CONST | 6,060 | 48.8% |
| STORE_FAST | 6,060 | 48.8% |
| FOR_ITER | 100 | 0.8% |
| FOR_ITER_LIST | 80 | 0.6% |
| LOAD_CONST | 60 | 0.5% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 493,376 | 66.6% |
| LOAD_ATTR_INSTANCE_VALUE | 240,238 | 32.5% |
| LOAD_FAST | 6,180 | 0.8% |
| RETURN_VALUE | 180 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 740,274 | 100.0% |


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
| POP_TOP | 579,730 | 31.8% |
| POP_JUMP_IF_FALSE | 481,031 | 26.4% |
| CALL_LIST_APPEND | 280,175 | 15.4% |
| POP_JUMP_IF_TRUE | 240,298 | 13.2% |
| STORE_FAST | 240,178 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 721,149 | 39.6% |
| FOR_ITER_LIST | 560,410 | 30.8% |
| FOR_ITER_RANGE | 533,793 | 29.3% |
| FOR_ITER | 6,060 | 0.3% |
| FOR_ITER_TUPLE | 60 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 980,632 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 734,034 | 74.9% |
| SEND | 246,598 | 25.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,719,304 | 87.7% |
| POP_TOP | 240,600 | 12.3% |
| STORE_ATTR | 120 | 0.0% |
| CALL_LIST_APPEND | 120 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,478,946 | 75.4% |
| LOAD_GLOBAL_BUILTIN | 481,198 | 24.5% |
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
| LOAD_ATTR_SLOT | 527,673 | 68.7% |
| LOAD_FAST | 240,060 | 31.3% |
| BINARY_SLICE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 767,913 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,379,067 | 80.9% |
| LOAD_ATTR_SLOT | 767,833 | 18.4% |
| LOAD_FAST_LOAD_FAST | 23,868 | 0.6% |
| LOAD_ATTR | 2,760 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,026,043 | 24.6% |
| PUSH_NULL | 768,173 | 18.4% |
| SWAP | 532,149 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 286,542 | 6.9% |
| BINARY_OP | 280,055 | 6.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,459,781 | 22.6% |
| POP_JUMP_IF_FALSE | 1,732,622 | 15.9% |
| POP_TOP | 1,501,923 | 13.8% |
| STORE_ATTR_SLOT | 1,234,277 | 11.3% |
| POP_JUMP_IF_TRUE | 985,065 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,412,666 | 40.5% |
| STORE_FAST | 2,735,045 | 25.1% |
| COMPARE_OP_INT | 1,713,322 | 15.7% |
| SEND_GEN | 493,556 | 4.5% |
| CALL | 493,505 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 482,640 | 88.7% |
| LOAD_ATTR | 23,708 | 4.4% |
| STORE_FAST | 12,154 | 2.2% |
| RESUME_CHECK | 12,034 | 2.2% |
| CALL_LEN | 11,854 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 494,614 | 91.0% |
| PUSH_NULL | 35,622 | 6.6% |
| COMPARE_OP_INT | 11,894 | 2.2% |
| LOAD_CONST | 420 | 0.1% |
| LOAD_ATTR | 220 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,196,452 | 15.2% |
| STORE_FAST | 9,014,079 | 13.4% |
| POP_JUMP_IF_FALSE | 7,419,246 | 11.1% |
| LOAD_CONST | 4,412,666 | 6.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,226,000 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 22,093,553 | 32.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,550,011 | 8.3% |
| LOAD_ATTR_SLOT | 5,211,405 | 7.8% |
| CALL_PY_EXACT_ARGS | 4,714,298 | 7.0% |
| RETURN_VALUE | 3,445,049 | 5.1% |


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
| STORE_ATTR_SLOT | 1,481,655 | 24.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,299,211 | 21.4% |
| PUSH_NULL | 746,599 | 12.3% |
| LOAD_FAST_LOAD_FAST | 489,418 | 8.1% |
| LOAD_GLOBAL_MODULE | 481,620 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,976,100 | 32.5% |
| LOAD_FAST | 1,262,107 | 20.8% |
| CALL | 500,192 | 8.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,634 | 8.1% |
| LOAD_FAST_LOAD_FAST | 489,418 | 8.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 320 | 15.2% |
| POP_TOP | 300 | 14.3% |
| STORE_FAST | 280 | 13.3% |
| LOAD_FAST | 200 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 120 | 5.7% |

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
| CACHE | 60 | 7.1% |
| CALL_FUNCTION_EX | 60 | 7.1% |
| COPY_FREE_VARS | 60 | 7.1% |

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
| TO_BOOL_BOOL | 6,793,886 | 49.6% |
| COMPARE_OP_INT | 2,783,673 | 20.3% |
| TO_BOOL_INT | 2,156,345 | 15.7% |
| TO_BOOL_LIST | 1,196,576 | 8.7% |
| TO_BOOL_NONE | 496,496 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,419,246 | 54.2% |
| LOAD_CONST | 1,732,622 | 12.7% |
| RETURN_CONST | 1,026,892 | 7.5% |
| POP_TOP | 1,018,676 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 721,118 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 981,568 | 57.0% |
| LOAD_ATTR_INSTANCE_VALUE | 739,361 | 43.0% |
| CALL | 120 | 0.0% |
| LOAD_ATTR | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,479,071 | 85.9% |
| LOAD_CONST | 240,358 | 14.0% |
| RETURN_CONST | 900 | 0.1% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 260 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,509,714 | 86.2% |
| LOAD_ATTR_INSTANCE_VALUE | 240,898 | 13.8% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| CALL | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020,907 | 58.3% |
| LOAD_FAST_LOAD_FAST | 247,618 | 14.1% |
| LOAD_GLOBAL_MODULE | 247,467 | 14.1% |
| LOAD_CONST | 234,120 | 13.4% |
| RETURN_CONST | 240 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,232,616 | 44.1% |
| TO_BOOL | 1,819,286 | 36.0% |
| TO_BOOL_INT | 1,007,180 | 19.9% |
| COMPARE_OP_INT | 240 | 0.0% |
| CONTAINS_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,832,288 | 56.0% |
| LOAD_CONST | 985,065 | 19.5% |
| STORE_FAST | 480,958 | 9.5% |
| NOP | 246,345 | 4.9% |
| JUMP_BACKWARD | 240,298 | 4.7% |


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
| POP_TOP | 2,040,904 | 35.1% |
| POP_JUMP_IF_FALSE | 1,026,892 | 17.6% |
| STORE_FAST | 1,008,751 | 17.3% |
| STORE_ATTR_SLOT | 740,672 | 12.7% |
| STORE_ATTR_INSTANCE_VALUE | 481,678 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,791,327 | 82.3% |
| INTERPRETER_EXIT | 777,020 | 13.3% |
| END_SEND | 252,658 | 4.3% |
| EXIT_INIT_CHECK | 420 | 0.0% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 246,718 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 246,598 | 50.0% |
| SEND | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 246,598 | 50.0% |
| YIELD_VALUE | 246,598 | 50.0% |
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
| LOAD_FAST | 1,320 | 60.0% |
| LOAD_FAST_LOAD_FAST | 400 | 18.2% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 10.9% |
| STORE_ATTR | 160 | 7.3% |
| SWAP | 80 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,260 | 57.3% |
| LOAD_FAST | 300 | 13.6% |
| LOAD_CONST | 180 | 8.2% |
| STORE_ATTR | 160 | 7.3% |
| JUMP_FORWARD | 120 | 5.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 36.4% |
| BUILD_LIST | 120 | 18.2% |
| CALL_KW | 120 | 18.2% |
| BINARY_OP_ADD_INT | 120 | 18.2% |
| CALL | 60 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 54.5% |
| LOAD_CONST | 120 | 18.2% |
| BUILD_LIST | 60 | 9.1% |
| LOAD_DEREF | 60 | 9.1% |
| LOAD_FAST_LOAD_FAST | 60 | 9.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,735,045 | 18.4% |
| RETURN_VALUE | 2,477,530 | 16.7% |
| CALL | 1,520,186 | 10.2% |
| CALL_LEN | 1,001,626 | 6.7% |
| LOAD_FAST | 985,088 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,014,079 | 60.7% |
| JUMP_FORWARD | 1,719,304 | 11.6% |
| RETURN_CONST | 1,008,751 | 6.8% |
| NOP | 974,372 | 6.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 532,149 | 3.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,739 | 100.0% |
| POP_TOP | 60 | 0.0% |
| COPY | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,092,379 | 99.9% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 532,149 | 99.8% |
| BINARY_OP_ADD_INT | 240 | 0.0% |
| BUILD_TUPLE | 180 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 532,149 | 99.8% |
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
| CALL | 20 | 10.0% |
| BINARY_SUBSCR_LIST_INT | 20 | 10.0% |

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
| YIELD_VALUE | 734,034 | 74.8% |
| SEND | 246,598 | 25.1% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 734,034 | 74.8% |
| INTERPRETER_EXIT | 246,718 | 25.2% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 480,958 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480,958 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 240,178 | 99.9% |
| LOAD_CONST | 280 | 0.1% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,178 | 99.9% |
| SWAP | 240 | 0.1% |
| STORE_DEREF | 120 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,178 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 240,218 | 100.0% |
| COMPARE_OP | 20 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

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
| RETURN_VALUE | 11,914 | 93.4% |
| LOAD_FAST | 820 | 6.4% |
| BINARY_SUBSCR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,854 | 92.9% |
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
| LOAD_ATTR_INSTANCE_VALUE | 240,238 | 95.3% |
| CALL_BUILTIN_CLASS | 11,854 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,238 | 95.3% |
| COPY_FREE_VARS | 11,854 | 4.7% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 493,032 | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE | 45,797 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 481,138 | 89.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,637 | 8.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 11,854 | 2.2% |
| LOAD_FAST | 180 | 0.0% |
| COMPARE_OP | 120 | 0.0% |


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
| CALL_BUILTIN_CLASS | 45,637 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,637 | 100.0% |


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
| LOAD_GLOBAL_BUILTIN | 985,768 | 99.3% |
| BUILD_TUPLE | 6,040 | 0.6% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |
| CALL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 992,128 | 100.0% |
| TO_BOOL | 100 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,922,992 | 86.8% |
| LOAD_FAST | 291,742 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,001,626 | 45.2% |
| COPY | 480,958 | 21.7% |
| LOAD_CONST | 240,178 | 10.8% |
| BINARY_OP_ADD_INT | 240,178 | 10.8% |
| LOAD_FAST | 239,940 | 10.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 280,055 | 99.9% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 280,175 | 99.9% |
| JUMP_FORWARD | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 492,634 | 48.6% |
| LOAD_FAST | 280,055 | 27.6% |
| RETURN_VALUE | 240,240 | 23.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 520,295 | 51.4% |
| RETURN_VALUE | 492,634 | 48.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 480,958 | 49.4% |
| LOAD_FAST | 252,094 | 25.9% |
| LOAD_ATTR | 240,240 | 24.7% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 492,334 | 50.6% |
| STORE_FAST | 480,958 | 49.4% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 568,563 | 69.6% |
| LOAD_ATTR | 247,038 | 30.3% |
| CALL | 440 | 0.1% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 567,563 | 69.5% |
| TO_BOOL_BOOL | 246,998 | 30.3% |
| POP_TOP | 540 | 0.1% |
| LOAD_FAST | 420 | 0.1% |
| CALL | 280 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 786,331 | 95.8% |
| BINARY_SLICE | 33,710 | 4.1% |
| CALL | 480 | 0.1% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 820,701 | 100.0% |
| PUSH_EXC_INFO | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,762,679 | 47.1% |
| LOAD_FAST | 4,714,298 | 38.5% |
| LOAD_ATTR_METHOD_NO_DICT | 774,240 | 6.3% |
| BUILD_TUPLE | 252,074 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 246,267 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,247,524 | 91.9% |
| COPY_FREE_VARS | 493,534 | 4.0% |
| RETURN_GENERATOR | 493,076 | 4.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 492,514 | 99.8% |
| LOAD_ATTR_METHOD_NO_DICT | 300 | 0.1% |
| LOAD_CONST | 240 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 493,174 | 100.0% |
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
| LOAD_CONST | 1,713,322 | 61.5% |
| LOAD_GLOBAL_MODULE | 480,958 | 17.3% |
| BINARY_OP_MULTIPLY_INT | 240,218 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 239,940 | 8.6% |
| LOAD_ATTR_SLOT | 45,637 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,783,673 | 100.0% |
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
| COPY | 60 | 33.3% |
| POP_JUMP_IF_FALSE | 60 | 33.3% |
| STORE_FAST | 60 | 33.3% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 962,496 | 63.2% |
| JUMP_BACKWARD | 560,410 | 36.8% |
| FOR_ITER | 80 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 560,110 | 36.8% |
| RETURN_CONST | 481,138 | 31.6% |
| LOAD_FAST | 480,958 | 31.6% |
| STORE_FAST | 600 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 533,793 | 52.6% |
| GET_ITER | 481,078 | 47.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 533,853 | 52.6% |
| LOAD_CONST | 480,958 | 47.4% |
| LOAD_FAST | 60 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 50.0% |
| JUMP_BACKWARD | 60 | 50.0% |

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
| LOAD_FAST | 22,093,553 | 96.7% |
| LOAD_ATTR_INSTANCE_VALUE | 492,514 | 2.2% |
| LOAD_FAST_LOAD_FAST | 252,834 | 1.1% |
| LOAD_ATTR | 1,120 | 0.0% |
| COPY | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,428,516 | 19.4% |
| LOAD_ATTR_METHOD_NO_DICT | 3,020,690 | 13.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,973,656 | 13.0% |
| RETURN_VALUE | 2,710,311 | 11.9% |
| CALL_LEN | 1,922,992 | 8.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,020,690 | 63.9% |
| LOAD_FAST | 1,421,264 | 30.1% |
| LOAD_ATTR | 286,542 | 6.1% |
| LOAD_ATTR_SLOT | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,085,002 | 44.1% |
| LOAD_FAST_LOAD_FAST | 1,299,211 | 27.5% |
| CALL_PY_EXACT_ARGS | 774,240 | 16.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 568,563 | 12.0% |
| LOAD_GLOBAL_MODULE | 620 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,550,011 | 51.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,973,656 | 27.7% |
| LOAD_ATTR_SLOT | 1,472,486 | 13.7% |
| RETURN_VALUE | 492,714 | 4.6% |
| LOAD_FAST_LOAD_FAST | 240,240 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,762,679 | 53.7% |
| LOAD_FAST | 4,226,000 | 39.4% |
| LOAD_FAST_LOAD_FAST | 260,192 | 2.4% |
| LOAD_CONST | 240,478 | 2.2% |
| LOAD_GLOBAL_MODULE | 240,438 | 2.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,566,209 | 100.0% |
| LOAD_ATTR | 1,100 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,511,265 | 58.9% |
| BINARY_OP | 566,037 | 22.0% |
| UNARY_INVERT | 246,167 | 9.6% |
| LOAD_FAST | 240,360 | 9.4% |
| COMPARE_OP | 780 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 498,359 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,154 | 50.6% |
| CALL | 240,238 | 48.2% |
| BINARY_OP | 5,987 | 1.2% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,858 | 99.9% |
| LOAD_ATTR | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,478 | 99.8% |
| COPY_FREE_VARS | 540 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,211,405 | 99.9% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.1% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,472,486 | 28.2% |
| TO_BOOL_BOOL | 1,379,647 | 26.4% |
| LOAD_ATTR | 767,833 | 14.7% |
| BUILD_LIST | 527,673 | 10.1% |
| LIST_EXTEND | 527,673 | 10.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,000,323 | 34.6% |
| LOAD_FAST | 1,231,986 | 21.3% |
| POP_JUMP_IF_FALSE | 721,118 | 12.5% |
| STORE_FAST | 527,015 | 9.1% |
| JUMP_FORWARD | 481,198 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,969,608 | 68.6% |
| CALL_ISINSTANCE | 985,768 | 17.0% |
| LOAD_DEREF | 482,640 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 343,672 | 5.9% |
| BUILD_TUPLE | 6,180 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,833,013 | 42.8% |
| RESUME_CHECK | 1,256,711 | 19.0% |
| NOP | 985,188 | 14.9% |
| POP_TOP | 527,122 | 8.0% |
| POP_JUMP_IF_NOT_NONE | 247,467 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,566,209 | 38.7% |
| BINARY_OP | 1,544,896 | 23.3% |
| LOAD_FAST | 1,024,965 | 15.5% |
| LOAD_FAST_LOAD_FAST | 481,620 | 7.3% |
| COMPARE_OP_INT | 480,958 | 7.3% |


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
| CALL_PY_EXACT_ARGS | 11,247,524 | 69.4% |
| CACHE | 1,998,194 | 12.3% |
| SEND_GEN | 734,034 | 4.5% |
| COPY_FREE_VARS | 518,442 | 3.2% |
| POP_TOP | 493,976 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,196,452 | 62.9% |
| LOAD_GLOBAL_BUILTIN | 2,000,323 | 12.3% |
| NOP | 1,765,635 | 10.9% |
| LOAD_GLOBAL_MODULE | 1,256,711 | 7.8% |
| JUMP_BACKWARD_NO_INTERRUPT | 980,632 | 6.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 734,034 | 59.8% |
| LOAD_CONST | 493,556 | 40.2% |
| SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 734,034 | 59.8% |
| POP_TOP | 493,676 | 40.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,699,614 | 99.8% |
| LOAD_FAST_LOAD_FAST | 2,000 | 0.1% |
| STORE_ATTR | 1,260 | 0.1% |
| SWAP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 974,998 | 57.2% |
| RETURN_CONST | 481,678 | 28.3% |
| NOP | 240,238 | 14.1% |
| LOAD_CONST | 3,720 | 0.2% |
| LOAD_FAST_LOAD_FAST | 720 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,233,176 | 53.1% |
| LOAD_FAST_LOAD_FAST | 1,976,100 | 46.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,481,655 | 35.2% |
| LOAD_CONST | 1,234,277 | 29.3% |
| LOAD_FAST | 740,672 | 17.6% |
| RETURN_CONST | 740,672 | 17.6% |
| NOP | 12,000 | 0.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 252,094 | 99.8% |
| LOAD_CONST | 280 | 0.1% |
| LOAD_FAST | 160 | 0.1% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,154 | 99.8% |
| NOP | 120 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| RETURN_CONST | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,428,516 | 44.3% |
| RETURN_VALUE | 2,445,079 | 24.5% |
| LOAD_ATTR_SLOT | 1,379,647 | 13.8% |
| CALL_ISINSTANCE | 992,128 | 9.9% |
| COPY | 480,300 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,793,886 | 68.0% |
| POP_JUMP_IF_TRUE | 2,232,616 | 22.4% |
| UNARY_NOT | 960,060 | 9.6% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,545,256 | 48.8% |
| BINARY_OP | 800,350 | 25.3% |
| LOAD_FAST | 532,044 | 16.8% |
| LOAD_ATTR_INSTANCE_VALUE | 285,875 | 9.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,156,345 | 68.2% |
| POP_JUMP_IF_TRUE | 1,007,180 | 31.8% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,196,576 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,196,576 | 100.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 495,356 | 99.8% |
| LOAD_FAST | 740 | 0.1% |
| LOAD_ATTR | 300 | 0.1% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 496,496 | 100.0% |


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
| POP_TOP | 60 | 33.3% |
| STORE_FAST | 60 | 33.3% |
| STORE_FAST_STORE_FAST | 60 | 33.3% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 560,110 | 51.3% |
| STORE_FAST | 532,149 | 48.7% |
| BINARY_SLICE | 180 | 0.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |
| END_SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,092,739 | 100.0% |
| LOAD_FAST | 60 | 0.0% |
| STORE_FAST | 60 | 0.0% |


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
|     deferred | 3,169,366 | 76.6% |
|          hit | 967,914 | 23.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 14.3% |
| Failure | 960 | 85.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 660 | 68.8% |
| or | 260 | 27.1% |
| floor divide | 20 | 2.1% |
| multiply different types | 20 | 2.1% |


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
|          hit | 13,114 | 99.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,265,469 | 13.5% |
|          hit | 20,927,338 | 86.5% |
|         miss | 1,800 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,720 | 50.9% |
| Failure | 2,620 | 49.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 420 | 16.0% |
| code complex parameters | 400 | 15.3% |
| class no vectorcall | 400 | 15.3% |
| meth descr method fastcall keywords | 360 | 13.7% |
| meth descr varargs | 220 | 8.4% |
| class mutable | 200 | 7.6% |
| no dict | 180 | 6.9% |
| other | 120 | 4.6% |
| cfunc varargs keywords | 120 | 4.6% |
| cfunc varargs | 80 | 3.1% |
| wrong number arguments | 40 | 1.5% |
| operator wrapper | 40 | 1.5% |
| cmethod | 20 | 0.8% |
| init not simple | 20 | 0.8% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 12,994 | 0.5% |
|          hit | 2,784,093 | 99.5% |

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
|---|---:|---:|
|     deferred | 12,240 | 0.5% |
|          hit | 2,538,037 | 99.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 44.4% |
| Failure | 100 | 55.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 40 | 40.0% |
| dict items | 40 | 40.0% |
| set | 20 | 20.0% |


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
|     deferred | 4,169,248 | 8.2% |
|          hit | 46,824,515 | 91.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,500 | 62.0% |
| Failure | 2,760 | 38.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 880 | 31.9% |
| has managed dict | 700 | 25.4% |
| method | 640 | 23.2% |
| shadowed | 200 | 7.2% |
| metaclass attribute | 120 | 4.3% |
| non object slot | 100 | 3.6% |
| class method obj | 40 | 1.4% |
| class attr simple | 40 | 1.4% |
| builtin class method | 20 | 0.7% |
| class attr descriptor | 20 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 12,412,351 | 100.0% |
|         miss | 60 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,080 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 482,640 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
| Failure | 0 | 0.0% |


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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 493,196 | 28.7% |
|          hit | 1,227,710 | 71.3% |

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
|---|---:|---:|
|     deferred | 780 | 0.0% |
|          hit | 5,912,430 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,260 | 88.7% |
| Failure | 160 | 11.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 60 | 37.5% |
| overridden | 40 | 25.0% |
| overriding descriptor | 40 | 25.0% |
| no dict | 20 | 12.5% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120 | 0.0% |
|          hit | 252,574 | 99.9% |

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
|---|---:|---:|
|     deferred | 1,832,160 | 11.0% |
|          hit | 14,843,339 | 89.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,020 | 56.7% |
| Failure | 780 | 43.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 260 | 33.3% |
| bytes | 220 | 28.2% |
| bytearray | 60 | 7.7% |
| dict | 60 | 7.7% |
| mapping | 60 | 7.7% |
| memory view | 40 | 5.1% |
| set | 40 | 5.1% |
| float | 20 | 2.6% |
| tuple | 20 | 2.6% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,093,039 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 150,679,016 | 48.0% |
| Not specialized | 37,306,387 | 11.9% |
| Specialized | 126,241,209 | 40.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 4,169,248 | 32.2% |
| CALL | 3,265,469 | 25.2% |
| BINARY_OP | 3,169,366 | 24.5% |
| TO_BOOL | 1,832,160 | 14.1% |
| SEND | 493,196 | 3.8% |
| COMPARE_OP | 12,994 | 0.1% |
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
| CALL_BUILTIN_O | 60 | 3.2% |
| LOAD_GLOBAL_BUILTIN | 60 | 3.2% |
| CACHE | 0 | 0.0% |
| BEFORE_ASYNC_WITH | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |
| DELETE_SUBSCR | 0 | 0.0% |
| END_SEND | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 1,999,334 | 12.0% |
| Calls to Python functions inlined | 14,708,849 | 88.0% |
| Calls via PyEval_EvalFrame (total) | 1,999,334 | 12.0% |
| Calls via PyEval_EvalFrame (vector) | 1,752,316 | 10.5% |
| Calls via PyEval_EvalFrame (generator) | 247,018 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,752,316 | 10.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 840 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 494,516 | 3.0% |
| Frame objects created | 780 | 0.0% |
| Frames pushed | 15,233,875 | 91.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 7,208,156 | 43.1% |
| Frees to freelist | 7,220,130 |  |
| Allocations | 9,524,258 | 56.9% |
| Allocations to 512 bytes | 9,042,984 | 54.0% |
| Allocations to 4 kbytes | 360 | 0.0% |
| Allocations over 4 kbytes | 480,914 | 2.9% |
| Frees | 9,871,733 |  |
| New values | 420 |  |
| Interpreter increfs | 130,101,651 | 84.3% |
| Interpreter decrefs | 142,042,379 | 83.8% |
| Increfs | 24,205,262 | 15.7% |
| Decrefs | 27,529,812 | 16.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 4,672,441 |  |
| Method cache misses | 663 |  |
| Method cache collisions | 710 |  |
| Method cache dunder hits | 1,271,761 |  |
| Method cache dunder misses | 73 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 0 | 19,200 |
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
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-10-09
