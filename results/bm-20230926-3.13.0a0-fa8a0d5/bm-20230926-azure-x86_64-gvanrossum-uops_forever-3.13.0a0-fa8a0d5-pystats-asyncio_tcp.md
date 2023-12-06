
# Pystats results

- benchmark: asyncio_tcp
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 65,981,345 | 21.3% | 21.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 22,722,984 | 7.4% | 28.7% |  |
| RESUME_CHECK | 16,155,468 | 5.2% | 33.9% |  |
| STORE_FAST | 14,751,587 | 4.8% | 38.7% |  |
| POP_JUMP_IF_FALSE | 13,589,151 | 4.4% | 43.1% |  |
| CALL_PY_EXACT_ARGS | 11,454,350 | 3.7% | 46.8% |  |
| LOAD_CONST | 10,886,268 | 3.5% | 50.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,997,705 | 3.2% | 53.6% |  |
| TO_BOOL_BOOL | 9,881,122 | 3.2% | 56.8% |  |
| POP_TOP | 9,632,896 | 3.1% | 59.9% |  |
| RETURN_VALUE | 9,411,569 | 3.0% | 62.9% |  |
| LOAD_GLOBAL_MODULE | 6,382,869 | 2.1% | 65.0% |  |
| LOAD_FAST_LOAD_FAST | 6,072,483 | 2.0% | 66.9% |  |
| RETURN_CONST | 5,821,788 | 1.9% | 68.8% |  |
| LOAD_GLOBAL_BUILTIN | 5,765,180 | 1.9% | 70.7% | 0.0% |
| POP_JUMP_IF_TRUE | 5,047,627 | 1.6% | 72.3% |  |
| LOAD_ATTR_SLOT | 5,030,530 | 1.6% | 74.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,635,045 | 1.5% | 75.4% |  |
| STORE_ATTR_SLOT | 4,209,243 | 1.4% | 76.8% |  |
| LOAD_ATTR | 4,129,448 | 1.3% | 78.1% |  |
| NOP | 3,719,388 | 1.2% | 79.4% |  |
| CALL | 3,270,766 | 1.1% | 80.4% |  |
| BINARY_OP | 3,170,274 | 1.0% | 81.4% |  |
| TO_BOOL_INT | 3,157,445 | 1.0% | 82.5% |  |
| COMPARE_OP_INT | 2,783,868 | 0.9% | 83.4% |  |
| LOAD_ATTR_MODULE | 2,567,385 | 0.8% | 84.2% |  |
| PUSH_NULL | 2,269,866 | 0.7% | 84.9% |  |
| CALL_LEN | 2,214,724 | 0.7% | 85.6% |  |
| COPY | 2,026,061 | 0.7% | 86.3% |  |
| INTERPRETER_EXIT | 1,999,324 | 0.6% | 86.9% |  |
| JUMP_FORWARD | 1,960,370 | 0.6% | 87.6% |  |
| TO_BOOL | 1,827,821 | 0.6% | 88.2% |  |
| ENTER_EXECUTOR | 1,814,832 | 0.6% | 88.8% |  |
| POP_JUMP_IF_NOT_NONE | 1,750,892 | 0.6% | 89.3% |  |
| POP_JUMP_IF_NONE | 1,715,343 | 0.6% | 89.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,703,157 | 0.6% | 90.4% |  |
| GET_ITER | 1,449,957 | 0.5% | 90.9% |  |
| SEND_GEN | 1,227,715 | 0.4% | 91.3% |  |
| BUILD_LIST | 1,203,238 | 0.4% | 91.7% |  |
| TO_BOOL_LIST | 1,196,698 | 0.4% | 92.1% |  |
| STORE_FAST_STORE_FAST | 1,092,581 | 0.4% | 92.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,461 | 0.4% | 92.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,012,791 | 0.3% | 93.1% |  |
| CALL_ISINSTANCE | 986,272 | 0.3% | 93.4% |  |
| YIELD_VALUE | 980,756 | 0.3% | 93.7% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 980,636 | 0.3% | 94.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 973,345 | 0.3% | 94.4% |  |
| FOR_ITER_LIST | 962,938 | 0.3% | 94.7% |  |
| UNARY_NOT | 960,120 | 0.3% | 95.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 820,746 | 0.3% | 95.3% | 0.1% |
| BUILD_TUPLE | 773,931 | 0.3% | 95.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 769,601 | 0.2% | 95.8% | 0.2% |
| CALL_FUNCTION_EX | 768,264 | 0.2% | 96.0% |  |
| GET_AWAITABLE | 740,277 | 0.2% | 96.2% |  |
| END_SEND | 740,277 | 0.2% | 96.5% |  |
| LIST_EXTEND | 721,199 | 0.2% | 96.7% |  |
| CALL_INTRINSIC_1 | 721,199 | 0.2% | 97.0% |  |
| LOAD_DEREF | 543,790 | 0.2% | 97.1% |  |
| CALL_BUILTIN_CLASS | 539,211 | 0.2% | 97.3% |  |
| SWAP | 532,851 | 0.2% | 97.5% |  |
| COPY_FREE_VARS | 518,538 | 0.2% | 97.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 498,368 | 0.2% | 97.8% |  |
| TO_BOOL_NONE | 496,498 | 0.2% | 98.0% |  |
| RETURN_GENERATOR | 493,978 | 0.2% | 98.1% |  |
| SEND | 493,598 | 0.2% | 98.3% |  |
| CALL_PY_WITH_DEFAULTS | 493,286 | 0.2% | 98.4% |  |
| UNARY_INVERT | 486,403 | 0.2% | 98.6% |  |
| LOAD_SUPER_ATTR_METHOD | 482,100 | 0.2% | 98.8% |  |
| FOR_ITER_RANGE | 481,199 | 0.2% | 98.9% |  |
| BINARY_OP_ADD_FLOAT | 480,959 | 0.2% | 99.1% |  |
| CALL_LIST_APPEND | 280,345 | 0.1% | 99.2% |  |
| BINARY_SLICE | 280,225 | 0.1% | 99.2% |  |
| CALL_KW | 260,125 | 0.1% | 99.3% |  |
| STORE_SUBSCR_DICT | 252,566 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 252,085 | 0.1% | 99.5% |  |
| CONTAINS_OP | 241,080 | 0.1% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 241,019 | 0.1% | 99.7% |  |
| BINARY_OP_ADD_INT | 240,539 | 0.1% | 99.7% |  |
| DELETE_SUBSCR | 240,239 | 0.1% | 99.8% |  |
| BUILD_SLICE | 240,239 | 0.1% | 99.9% |  |
| BINARY_OP_MULTIPLY_INT | 240,239 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,626 | 0.0% | 100.0% |  |
| COMPARE_OP | 13,466 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 12,746 | 0.0% | 100.0% |  |
| FOR_ITER | 12,420 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 6,617 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 6,120 | 0.0% | 100.0% |  |
| STORE_ATTR | 2,200 | 0.0% | 100.0% |  |
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
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BEFORE_ASYNC_WITH | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 21,970,232 | 7.1% | 7.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,707,925 | 3.5% | 10.6% |
| RESUME_CHECK LOAD_FAST | 10,190,429 | 3.3% | 13.9% |
| STORE_FAST LOAD_FAST | 8,914,399 | 2.9% | 16.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,313,827 | 2.4% | 19.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,694,397 | 2.2% | 21.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,281,730 | 1.7% | 23.0% |
| LOAD_FAST LOAD_ATTR_SLOT | 5,024,430 | 1.6% | 24.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,822,933 | 1.6% | 26.2% |
| RETURN_CONST POP_TOP | 4,791,282 | 1.6% | 27.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,702,370 | 1.5% | 29.3% |
| LOAD_CONST LOAD_FAST | 4,412,650 | 1.4% | 30.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 4,375,859 | 1.4% | 32.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 4,214,071 | 1.4% | 33.5% |
| POP_TOP LOAD_FAST | 4,000,486 | 1.3% | 34.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,963,637 | 1.3% | 36.0% |
| LOAD_FAST RETURN_VALUE | 3,445,009 | 1.1% | 37.1% |
| LOAD_FAST LOAD_ATTR | 3,378,737 | 1.1% | 38.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,973,893 | 1.0% | 39.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 2,967,695 | 1.0% | 40.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,832,714 | 0.9% | 41.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 2,820,243 | 0.9% | 42.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,783,628 | 0.9% | 42.9% |
| LOAD_CONST STORE_FAST | 2,735,017 | 0.9% | 43.8% |
| NOP LOAD_FAST | 2,733,596 | 0.9% | 44.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,710,293 | 0.9% | 45.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,566,045 | 0.8% | 46.4% |
| RETURN_VALUE STORE_FAST | 2,477,501 | 0.8% | 47.2% |
| LOAD_FAST LOAD_CONST | 2,459,757 | 0.8% | 48.0% |
| RETURN_VALUE TO_BOOL_BOOL | 2,445,068 | 0.8% | 48.8% |
| LOAD_FAST STORE_ATTR_SLOT | 2,233,155 | 0.7% | 49.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,226,665 | 0.7% | 50.2% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,150,218 | 0.7% | 50.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,084,842 | 0.7% | 51.6% |
| POP_TOP RETURN_CONST | 2,040,887 | 0.7% | 52.2% |
| CACHE RESUME_CHECK | 1,998,184 | 0.6% | 52.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,994,357 | 0.6% | 53.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,976,088 | 0.6% | 54.2% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,922,996 | 0.6% | 54.8% |
| TO_BOOL POP_JUMP_IF_TRUE | 1,813,195 | 0.6% | 55.4% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,732,609 | 0.6% | 55.9% |
| STORE_FAST JUMP_FORWARD | 1,719,290 | 0.6% | 56.5% |
| RESUME_CHECK NOP | 1,718,897 | 0.6% | 57.0% |
| LOAD_CONST COMPARE_OP_INT | 1,713,309 | 0.6% | 57.6% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,699,617 | 0.5% | 58.1% |
| COPY TO_BOOL_INT | 1,545,101 | 0.5% | 58.6% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,544,741 | 0.5% | 59.1% |
| CALL STORE_FAST | 1,520,158 | 0.5% | 59.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,511,249 | 0.5% | 60.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,509,693 | 0.5% | 60.6% |
| POP_TOP LOAD_CONST | 1,501,908 | 0.5% | 61.1% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,481,646 | 0.5% | 61.6% |
| JUMP_FORWARD LOAD_FAST | 1,478,931 | 0.5% | 62.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,473,124 | 0.5% | 62.5% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 1,472,471 | 0.5% | 63.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,374,384 | 0.4% | 63.5% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,332,838 | 0.4% | 63.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 1,299,179 | 0.4% | 64.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,262,090 | 0.4% | 64.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,256,703 | 0.4% | 65.1% |
| STORE_ATTR_SLOT LOAD_CONST | 1,234,267 | 0.4% | 65.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,226,031 | 0.4% | 65.9% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 1,196,578 | 0.4% | 66.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 1,196,578 | 0.4% | 66.7% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,092,341 | 0.4% | 67.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,091,981 | 0.4% | 67.4% |
| BINARY_OP COPY | 1,064,142 | 0.3% | 67.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,026,872 | 0.3% | 68.1% |
| LOAD_ATTR LOAD_FAST | 1,025,897 | 0.3% | 68.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,024,938 | 0.3% | 68.7% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,020,890 | 0.3% | 69.1% |
| LOAD_FAST TO_BOOL | 1,018,731 | 0.3% | 69.4% |
| POP_JUMP_IF_FALSE POP_TOP | 1,018,534 | 0.3% | 69.7% |
| STORE_FAST RETURN_CONST | 1,008,743 | 0.3% | 70.1% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 1,007,167 | 0.3% | 70.4% |
| CALL RETURN_VALUE | 1,002,024 | 0.3% | 70.7% |
| CALL_LEN STORE_FAST | 1,001,621 | 0.3% | 71.0% |
| RETURN_VALUE RETURN_VALUE | 986,212 | 0.3% | 71.3% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 986,172 | 0.3% | 71.7% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 985,752 | 0.3% | 72.0% |
| NOP LOAD_GLOBAL_MODULE | 985,172 | 0.3% | 72.3% |
| LOAD_FAST STORE_FAST | 985,072 | 0.3% | 72.6% |
| POP_JUMP_IF_TRUE LOAD_CONST | 985,062 | 0.3% | 72.9% |
| LOAD_FAST POP_JUMP_IF_NONE | 981,563 | 0.3% | 73.3% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 980,636 | 0.3% | 73.6% |
| RETURN_VALUE INTERPRETER_EXIT | 975,298 | 0.3% | 73.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 974,999 | 0.3% | 74.2% |
| STORE_FAST NOP | 974,365 | 0.3% | 74.5% |
| LOAD_FAST GET_ITER | 962,578 | 0.3% | 74.8% |
| GET_ITER FOR_ITER_LIST | 962,498 | 0.3% | 75.1% |
| TO_BOOL_BOOL UNARY_NOT | 960,060 | 0.3% | 75.5% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 820,686 | 0.3% | 75.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 807,170 | 0.3% | 76.0% |
| BINARY_OP TO_BOOL_INT | 800,330 | 0.3% | 76.2% |
| PUSH_NULL LOAD_FAST | 793,156 | 0.3% | 76.5% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 786,323 | 0.3% | 76.8% |
| BINARY_OP STORE_FAST | 778,474 | 0.3% | 77.0% |
| RETURN_CONST INTERPRETER_EXIT | 777,007 | 0.3% | 77.3% |
| CALL_FUNCTION_EX POP_TOP | 767,844 | 0.2% | 77.5% |
| RETURN_VALUE LOAD_FAST | 761,484 | 0.2% | 77.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,239 | 85.7% |
| LOAD_CONST | 39,986 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,239 | 85.7% |
| CALL_METHOD_DESCRIPTOR_O | 33,703 | 12.0% |
| STORE_FAST | 5,923 | 2.1% |
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
| RESUME_CHECK | 1,998,184 | 99.9% |
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
| BUILD_SLICE | 240,239 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,239 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 252,659 | 34.1% |
| SEND | 246,599 | 33.3% |
| RETURN_VALUE | 241,019 | 32.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 499,378 | 67.5% |
| STORE_FAST | 240,599 | 32.5% |
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
| LOAD_FAST | 962,578 | 66.4% |
| CALL_BUILTIN_CLASS | 481,139 | 33.2% |
| LOAD_ATTR_INSTANCE_VALUE | 6,060 | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 962,498 | 66.4% |
| FOR_ITER_RANGE | 481,079 | 33.2% |
| FOR_ITER | 6,260 | 0.4% |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% |
| FOR_ITER_TUPLE | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 975,298 | 48.8% |
| RETURN_CONST | 777,007 | 38.9% |
| YIELD_VALUE | 246,719 | 12.3% |
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
| RESUME_CHECK | 1,718,897 | 46.2% |
| STORE_FAST | 974,365 | 26.2% |
| POP_JUMP_IF_FALSE | 520,885 | 14.0% |
| POP_JUMP_IF_TRUE | 246,342 | 6.6% |
| STORE_ATTR_INSTANCE_VALUE | 240,239 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,733,596 | 73.5% |
| LOAD_GLOBAL_MODULE | 985,172 | 26.5% |
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
| RETURN_CONST | 4,791,282 | 49.7% |
| POP_JUMP_IF_FALSE | 1,018,534 | 10.6% |
| CALL_METHOD_DESCRIPTOR_O | 820,686 | 8.5% |
| CALL_FUNCTION_EX | 767,844 | 8.0% |
| END_SEND | 499,378 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,000,486 | 41.5% |
| RETURN_CONST | 2,040,887 | 21.2% |
| LOAD_CONST | 1,501,908 | 15.6% |
| ENTER_EXECUTOR | 573,410 | 6.0% |
| LOAD_GLOBAL_MODULE | 527,108 | 5.5% |


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
| LOAD_ATTR_MODULE | 1,511,249 | 66.6% |
| LOAD_ATTR | 721,459 | 31.8% |
| LOAD_DEREF | 35,598 | 1.6% |
| LOAD_FAST | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 793,156 | 34.9% |
| LOAD_FAST_LOAD_FAST | 746,588 | 32.9% |
| CALL | 729,462 | 32.1% |
| LOAD_CONST | 360 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 252,899 | 51.2% |
| ENTER_EXECUTOR | 240,179 | 48.6% |
| CALL_KW | 300 | 0.1% |
| CACHE | 240 | 0.0% |
| MAKE_CELL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 493,378 | 99.9% |
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
| LOAD_FAST | 3,445,009 | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,710,293 | 28.8% |
| CALL | 1,002,024 | 10.6% |
| RETURN_VALUE | 986,212 | 10.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,626 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,477,501 | 26.3% |
| TO_BOOL_BOOL | 2,445,068 | 26.0% |
| RETURN_VALUE | 986,212 | 10.5% |
| INTERPRETER_EXIT | 975,298 | 10.4% |
| LOAD_FAST | 761,484 | 8.1% |


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
| LOAD_FAST | 1,018,731 | 55.7% |
| LOAD_ATTR_INSTANCE_VALUE | 807,170 | 44.2% |
| TO_BOOL | 740 | 0.0% |
| LOAD_ATTR | 560 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,813,195 | 99.2% |
| POP_JUMP_IF_FALSE | 12,866 | 0.7% |
| TO_BOOL_BOOL | 860 | 0.0% |
| TO_BOOL | 740 | 0.0% |
| TO_BOOL_NONE | 100 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 246,163 | 50.6% |
| BINARY_OP | 240,240 | 49.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 486,403 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 1,544,741 | 48.7% |
| LOAD_ATTR_MODULE | 566,013 | 17.9% |
| UNARY_INVERT | 486,403 | 15.3% |
| POP_JUMP_IF_FALSE | 285,849 | 9.0% |
| LOAD_ATTR | 280,045 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,064,142 | 33.6% |
| TO_BOOL_INT | 800,330 | 25.2% |
| STORE_FAST | 778,474 | 24.6% |
| BUILD_TUPLE | 280,045 | 8.8% |
| UNARY_INVERT | 240,240 | 7.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 481,079 | 40.0% |
| LOAD_ATTR_SLOT | 480,959 | 40.0% |
| LOAD_FAST_LOAD_FAST | 240,060 | 20.0% |
| LOAD_FAST | 480 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 721,439 | 60.0% |
| STORE_FAST | 481,439 | 40.0% |
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
| LOAD_FAST | 240,239 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 240,239 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 280,045 | 36.2% |
| LOAD_CONST | 246,103 | 31.8% |
| LOAD_FAST | 240,720 | 31.1% |
| LOAD_FAST_LOAD_FAST | 6,523 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 280,045 | 36.2% |
| CALL_PY_EXACT_ARGS | 252,066 | 32.6% |
| CALL | 240,280 | 31.0% |
| LOAD_CONST | 360 | 0.0% |
| RETURN_VALUE | 300 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 729,462 | 22.3% |
| LOAD_FAST_LOAD_FAST | 500,185 | 15.3% |
| LOAD_CONST | 493,502 | 15.1% |
| LOAD_ATTR_INSTANCE_VALUE | 487,121 | 14.9% |
| LOAD_ATTR | 240,760 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,520,158 | 46.5% |
| RETURN_VALUE | 1,002,024 | 30.6% |
| POP_TOP | 247,979 | 7.6% |
| RESUME_CHECK | 247,003 | 7.6% |
| LOAD_CONST | 240,299 | 7.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 721,199 | 93.9% |
| ENTER_EXECUTOR | 46,705 | 6.1% |
| LOAD_FAST | 180 | 0.0% |
| DICT_MERGE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 767,844 | 99.9% |
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
| LIST_EXTEND | 721,199 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 721,199 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 260,125 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 246,659 | 94.8% |
| COPY_FREE_VARS | 11,846 | 4.6% |
| STORE_FAST | 600 | 0.2% |
| RETURN_GENERATOR | 300 | 0.1% |
| RESUME_CHECK | 300 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 11,846 | 88.0% |
| LOAD_ATTR_MODULE | 780 | 5.8% |
| LOAD_CONST | 400 | 3.0% |
| COMPARE_OP | 280 | 2.1% |
| CALL_BUILTIN_CLASS | 120 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,926 | 96.0% |
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
| BINARY_OP | 1,064,142 | 52.5% |
| CALL_LEN | 480,959 | 23.7% |
| UNARY_NOT | 480,060 | 23.7% |
| LOAD_FAST | 360 | 0.0% |
| CALL_BUILTIN_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,545,101 | 76.3% |
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
| CALL_PY_EXACT_ARGS | 493,526 | 95.2% |
| CALL_KW | 11,846 | 2.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 11,846 | 2.3% |
| LOAD_ATTR_PROPERTY | 540 | 0.1% |
| CACHE | 540 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 518,418 | 100.0% |
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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 573,410 | 31.6% |
| POP_JUMP_IF_FALSE | 480,899 | 26.5% |
| CALL_LIST_APPEND | 280,045 | 15.4% |
| POP_JUMP_IF_TRUE | 240,299 | 13.2% |
| STORE_FAST | 240,179 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 480,899 | 26.5% |
| LOAD_CONST | 480,899 | 26.5% |
| LOAD_FAST | 279,985 | 15.4% |
| RETURN_CONST | 279,925 | 15.4% |
| RETURN_GENERATOR | 240,179 | 13.2% |


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
| RETURN_GENERATOR | 493,378 | 66.6% |
| LOAD_ATTR_INSTANCE_VALUE | 240,239 | 32.5% |
| LOAD_FAST | 6,180 | 0.8% |
| RETURN_VALUE | 180 | 0.0% |
| CALL_FUNCTION_EX | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 740,277 | 100.0% |


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
| POP_TOP | 6,300 | 95.2% |
| CALL_LIST_APPEND | 120 | 1.8% |
| POP_JUMP_IF_FALSE | 77 | 1.2% |
| LIST_APPEND | 60 | 0.9% |
| ENTER_EXECUTOR | 60 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 6,060 | 91.6% |
| FOR_ITER_LIST | 300 | 4.5% |
| FOR_ITER_RANGE | 120 | 1.8% |
| LOAD_FAST | 77 | 1.2% |
| FOR_ITER_TUPLE | 60 | 0.9% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 980,636 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 734,037 | 74.9% |
| SEND | 246,599 | 25.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,719,290 | 87.7% |
| POP_TOP | 240,600 | 12.3% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| STORE_ATTR | 120 | 0.0% |
| CALL_LIST_APPEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,478,931 | 75.4% |
| LOAD_GLOBAL_BUILTIN | 481,199 | 24.5% |
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
| LOAD_ATTR_SLOT | 480,959 | 66.7% |
| LOAD_FAST | 240,060 | 33.3% |
| BINARY_SLICE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 721,199 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,378,737 | 81.8% |
| LOAD_ATTR_SLOT | 721,119 | 17.5% |
| LOAD_FAST_LOAD_FAST | 23,852 | 0.6% |
| LOAD_ATTR | 2,760 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,025,897 | 24.8% |
| PUSH_NULL | 721,459 | 17.5% |
| SWAP | 532,011 | 12.9% |
| LOAD_ATTR_METHOD_NO_DICT | 286,528 | 6.9% |
| BINARY_OP | 280,045 | 6.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,459,757 | 22.6% |
| POP_JUMP_IF_FALSE | 1,732,609 | 15.9% |
| POP_TOP | 1,501,908 | 13.8% |
| STORE_ATTR_SLOT | 1,234,267 | 11.3% |
| POP_JUMP_IF_TRUE | 985,062 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,412,650 | 40.5% |
| STORE_FAST | 2,735,017 | 25.1% |
| COMPARE_OP_INT | 1,713,309 | 15.7% |
| SEND_GEN | 493,558 | 4.5% |
| CALL | 493,502 | 4.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 482,640 | 88.8% |
| LOAD_ATTR | 23,692 | 4.4% |
| STORE_FAST | 12,146 | 2.2% |
| RESUME_CHECK | 12,026 | 2.2% |
| CALL_LEN | 11,846 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 494,606 | 91.0% |
| PUSH_NULL | 35,598 | 6.5% |
| COMPARE_OP_INT | 11,886 | 2.2% |
| LOAD_CONST | 420 | 0.1% |
| LOAD_ATTR | 220 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,190,429 | 15.4% |
| STORE_FAST | 8,914,399 | 13.5% |
| POP_JUMP_IF_FALSE | 7,313,827 | 11.1% |
| LOAD_CONST | 4,412,650 | 6.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,214,071 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 21,970,232 | 33.3% |
| LOAD_ATTR_SLOT | 5,024,430 | 7.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,822,933 | 7.3% |
| CALL_PY_EXACT_ARGS | 4,702,370 | 7.1% |
| RETURN_VALUE | 3,445,009 | 5.2% |


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
| STORE_ATTR_SLOT | 1,481,646 | 24.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,299,179 | 21.4% |
| PUSH_NULL | 746,588 | 12.3% |
| LOAD_FAST_LOAD_FAST | 489,419 | 8.1% |
| LOAD_GLOBAL_MODULE | 481,620 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,976,088 | 32.5% |
| LOAD_FAST | 1,262,090 | 20.8% |
| CALL | 500,185 | 8.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,626 | 8.1% |
| LOAD_FAST_LOAD_FAST | 489,419 | 8.1% |


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
| STORE_ATTR_INSTANCE_VALUE | 120 | 5.7% |

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
| TO_BOOL_BOOL | 6,694,397 | 49.3% |
| COMPARE_OP_INT | 2,783,628 | 20.5% |
| TO_BOOL_INT | 2,150,218 | 15.8% |
| TO_BOOL_LIST | 1,196,578 | 8.8% |
| TO_BOOL_NONE | 496,498 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,313,827 | 53.8% |
| LOAD_CONST | 1,732,609 | 12.7% |
| RETURN_CONST | 1,026,872 | 7.6% |
| POP_TOP | 1,018,534 | 7.5% |
| LOAD_GLOBAL_BUILTIN | 721,119 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 981,563 | 57.2% |
| LOAD_ATTR_INSTANCE_VALUE | 733,420 | 42.8% |
| LOAD_ATTR | 120 | 0.0% |
| CALL | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,473,124 | 85.9% |
| LOAD_CONST | 240,359 | 14.0% |
| RETURN_CONST | 900 | 0.1% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 260 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,509,693 | 86.2% |
| LOAD_ATTR_INSTANCE_VALUE | 240,899 | 13.8% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020,890 | 58.3% |
| LOAD_FAST_LOAD_FAST | 247,619 | 14.1% |
| LOAD_GLOBAL_MODULE | 247,463 | 14.1% |
| LOAD_CONST | 234,120 | 13.4% |
| RETURN_CONST | 240 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,226,665 | 44.1% |
| TO_BOOL | 1,813,195 | 35.9% |
| TO_BOOL_INT | 1,007,167 | 20.0% |
| COMPARE_OP_INT | 240 | 0.0% |
| CONTAINS_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,820,243 | 55.9% |
| LOAD_CONST | 985,062 | 19.5% |
| STORE_FAST | 480,959 | 9.5% |
| NOP | 246,342 | 4.9% |
| ENTER_EXECUTOR | 240,299 | 4.8% |


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
| POP_TOP | 2,040,887 | 35.1% |
| POP_JUMP_IF_FALSE | 1,026,872 | 17.6% |
| STORE_FAST | 1,008,743 | 17.3% |
| STORE_ATTR_SLOT | 740,665 | 12.7% |
| STORE_ATTR_INSTANCE_VALUE | 481,679 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,791,282 | 82.3% |
| INTERPRETER_EXIT | 777,007 | 13.3% |
| END_SEND | 252,659 | 4.3% |
| EXIT_INIT_CHECK | 420 | 0.0% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 246,719 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 246,599 | 50.0% |
| SEND | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 246,599 | 50.0% |
| END_SEND | 246,599 | 50.0% |
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
| RETURN_CONST | 120 | 5.5% |


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
| LOAD_CONST | 2,735,017 | 18.5% |
| RETURN_VALUE | 2,477,501 | 16.8% |
| CALL | 1,520,158 | 10.3% |
| CALL_LEN | 1,001,621 | 6.8% |
| LOAD_FAST | 985,072 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,914,399 | 60.4% |
| JUMP_FORWARD | 1,719,290 | 11.7% |
| RETURN_CONST | 1,008,743 | 6.8% |
| NOP | 974,365 | 6.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 532,011 | 3.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,341 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,091,981 | 99.9% |
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
| LOAD_ATTR | 532,011 | 99.8% |
| BINARY_OP_ADD_INT | 240 | 0.0% |
| BUILD_TUPLE | 180 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 532,011 | 99.8% |
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
| YIELD_VALUE | 734,037 | 74.8% |
| SEND | 246,599 | 25.1% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 734,037 | 74.8% |
| INTERPRETER_EXIT | 246,719 | 25.2% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 480,959 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480,959 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 240,179 | 99.9% |
| LOAD_CONST | 280 | 0.1% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,179 | 99.9% |
| SWAP | 240 | 0.1% |
| STORE_DEREF | 120 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 240,179 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 240,219 | 100.0% |
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
| RETURN_VALUE | 11,906 | 93.4% |
| LOAD_FAST | 820 | 6.4% |
| BINARY_SUBSCR | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,846 | 92.9% |
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
| LOAD_ATTR_INSTANCE_VALUE | 240,239 | 95.3% |
| CALL_BUILTIN_CLASS | 11,846 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,239 | 95.3% |
| COPY_FREE_VARS | 11,846 | 4.7% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 493,025 | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE | 45,786 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 481,139 | 89.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,626 | 8.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 11,846 | 2.2% |
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
| CALL_BUILTIN_CLASS | 45,626 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,626 | 100.0% |


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
| LOAD_GLOBAL_BUILTIN | 985,752 | 99.9% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| CALL | 100 | 0.0% |
| BUILD_TUPLE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 986,172 | 100.0% |
| TO_BOOL | 100 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,922,996 | 86.8% |
| LOAD_FAST | 291,728 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,001,621 | 45.2% |
| COPY | 480,959 | 21.7% |
| LOAD_CONST | 240,179 | 10.8% |
| BINARY_OP_ADD_INT | 240,179 | 10.8% |
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
| ENTER_EXECUTOR | 280,045 | 99.9% |
| JUMP_FORWARD | 120 | 0.0% |
| JUMP_BACKWARD | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 492,626 | 48.6% |
| LOAD_FAST | 279,925 | 27.6% |
| RETURN_VALUE | 240,240 | 23.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 520,165 | 51.4% |
| RETURN_VALUE | 492,626 | 48.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 480,959 | 49.4% |
| LOAD_FAST | 252,086 | 25.9% |
| LOAD_ATTR | 240,240 | 24.7% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 492,326 | 50.6% |
| STORE_FAST | 480,959 | 49.4% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 521,782 | 67.8% |
| LOAD_ATTR | 247,039 | 32.1% |
| CALL | 440 | 0.1% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 520,782 | 67.7% |
| TO_BOOL_BOOL | 246,999 | 32.1% |
| POP_TOP | 540 | 0.1% |
| LOAD_FAST | 420 | 0.1% |
| CALL | 280 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 786,323 | 95.8% |
| BINARY_SLICE | 33,703 | 4.1% |
| CALL | 480 | 0.1% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 820,686 | 100.0% |
| PUSH_EXC_INFO | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,281,730 | 46.1% |
| LOAD_FAST | 4,702,370 | 41.1% |
| LOAD_ATTR_METHOD_NO_DICT | 727,522 | 6.4% |
| BUILD_TUPLE | 252,066 | 2.2% |
| LOAD_ATTR_INSTANCE_VALUE | 246,263 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,707,925 | 93.5% |
| COPY_FREE_VARS | 493,526 | 4.3% |
| RETURN_GENERATOR | 252,899 | 2.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 492,506 | 99.8% |
| LOAD_ATTR_METHOD_NO_DICT | 300 | 0.1% |
| LOAD_CONST | 240 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 493,166 | 100.0% |
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
| LOAD_CONST | 1,713,309 | 61.5% |
| LOAD_GLOBAL_MODULE | 480,959 | 17.3% |
| BINARY_OP_MULTIPLY_INT | 240,219 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 239,940 | 8.6% |
| LOAD_ATTR_SLOT | 45,626 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,783,628 | 100.0% |
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
| GET_ITER | 962,498 | 100.0% |
| JUMP_BACKWARD | 300 | 0.0% |
| FOR_ITER | 80 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 559,850 | 58.1% |
| RETURN_CONST | 201,214 | 20.9% |
| LOAD_FAST | 201,034 | 20.9% |
| STORE_FAST | 600 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 481,079 | 100.0% |
| JUMP_BACKWARD | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 481,139 | 100.0% |
| LOAD_CONST | 60 | 0.0% |


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
| LOAD_FAST | 21,970,232 | 96.7% |
| LOAD_ATTR_INSTANCE_VALUE | 492,506 | 2.2% |
| LOAD_FAST_LOAD_FAST | 252,826 | 1.1% |
| ENTER_EXECUTOR | 5,940 | 0.0% |
| LOAD_ATTR | 1,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,375,859 | 19.3% |
| LOAD_ATTR_METHOD_NO_DICT | 2,973,893 | 13.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,967,695 | 13.1% |
| RETURN_VALUE | 2,710,293 | 11.9% |
| CALL_LEN | 1,922,996 | 8.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,973,893 | 64.2% |
| LOAD_FAST | 1,374,384 | 29.7% |
| LOAD_ATTR | 286,528 | 6.2% |
| LOAD_ATTR_SLOT | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,084,842 | 45.0% |
| LOAD_FAST_LOAD_FAST | 1,299,179 | 28.0% |
| CALL_PY_EXACT_ARGS | 727,522 | 15.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 521,782 | 11.3% |
| LOAD_GLOBAL_MODULE | 620 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,822,933 | 48.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,967,695 | 29.7% |
| LOAD_ATTR_SLOT | 1,472,471 | 14.7% |
| RETURN_VALUE | 492,706 | 4.9% |
| LOAD_FAST_LOAD_FAST | 240,240 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,281,730 | 52.8% |
| LOAD_FAST | 4,214,071 | 42.2% |
| LOAD_FAST_LOAD_FAST | 260,185 | 2.6% |
| LOAD_CONST | 240,479 | 2.4% |
| CALL | 720 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,566,045 | 99.9% |
| LOAD_ATTR | 1,100 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| ENTER_EXECUTOR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,511,249 | 58.9% |
| BINARY_OP | 566,013 | 22.0% |
| UNARY_INVERT | 246,163 | 9.6% |
| LOAD_FAST | 240,360 | 9.4% |
| COMPARE_OP | 780 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 498,348 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,146 | 50.6% |
| CALL | 240,239 | 48.2% |
| BINARY_OP | 5,983 | 1.2% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,859 | 99.9% |
| LOAD_ATTR | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,479 | 99.8% |
| COPY_FREE_VARS | 540 | 0.2% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,024,430 | 99.9% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.1% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,472,471 | 29.3% |
| TO_BOOL_BOOL | 1,332,838 | 26.5% |
| LOAD_ATTR | 721,119 | 14.3% |
| TO_BOOL_NONE | 495,358 | 9.8% |
| LIST_EXTEND | 480,959 | 9.6% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,994,357 | 34.6% |
| LOAD_FAST | 1,226,031 | 21.3% |
| POP_JUMP_IF_FALSE | 721,119 | 12.5% |
| STORE_FAST | 527,005 | 9.1% |
| JUMP_FORWARD | 481,199 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,963,637 | 68.8% |
| CALL_ISINSTANCE | 985,752 | 17.1% |
| LOAD_DEREF | 482,640 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 331,771 | 5.8% |
| CHECK_EXC_MATCH | 360 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,832,714 | 44.4% |
| RESUME_CHECK | 1,256,703 | 19.7% |
| NOP | 985,172 | 15.4% |
| POP_TOP | 527,108 | 8.3% |
| POP_JUMP_IF_NOT_NONE | 247,463 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,566,045 | 40.2% |
| BINARY_OP | 1,544,741 | 24.2% |
| LOAD_FAST | 1,024,938 | 16.1% |
| LOAD_FAST_LOAD_FAST | 481,620 | 7.5% |
| COMPARE_OP_INT | 480,959 | 7.5% |


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
| CALL_PY_EXACT_ARGS | 10,707,925 | 66.3% |
| CACHE | 1,998,184 | 12.4% |
| SEND_GEN | 734,037 | 4.5% |
| COPY_FREE_VARS | 518,418 | 3.2% |
| POP_TOP | 493,978 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,190,429 | 63.1% |
| LOAD_GLOBAL_BUILTIN | 1,994,357 | 12.3% |
| NOP | 1,718,897 | 10.6% |
| LOAD_GLOBAL_MODULE | 1,256,703 | 7.8% |
| JUMP_BACKWARD_NO_INTERRUPT | 980,636 | 6.1% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 734,037 | 59.8% |
| LOAD_CONST | 493,558 | 40.2% |
| SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 734,037 | 59.8% |
| POP_TOP | 493,678 | 40.2% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,699,617 | 99.8% |
| LOAD_FAST_LOAD_FAST | 2,000 | 0.1% |
| STORE_ATTR | 1,260 | 0.1% |
| SWAP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 974,999 | 57.2% |
| RETURN_CONST | 481,679 | 28.3% |
| NOP | 240,239 | 14.1% |
| LOAD_CONST | 3,720 | 0.2% |
| LOAD_FAST_LOAD_FAST | 720 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,233,155 | 53.1% |
| LOAD_FAST_LOAD_FAST | 1,976,088 | 46.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,481,646 | 35.2% |
| LOAD_CONST | 1,234,267 | 29.3% |
| RETURN_CONST | 740,665 | 17.6% |
| LOAD_FAST | 740,665 | 17.6% |
| NOP | 12,000 | 0.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 252,086 | 99.8% |
| LOAD_CONST | 280 | 0.1% |
| LOAD_FAST | 160 | 0.1% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,146 | 99.8% |
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
| LOAD_ATTR_INSTANCE_VALUE | 4,375,859 | 44.3% |
| RETURN_VALUE | 2,445,068 | 24.7% |
| LOAD_ATTR_SLOT | 1,332,838 | 13.5% |
| CALL_ISINSTANCE | 986,172 | 10.0% |
| COPY | 480,300 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,694,397 | 67.7% |
| POP_JUMP_IF_TRUE | 2,226,665 | 22.5% |
| UNARY_NOT | 960,060 | 9.7% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,545,101 | 48.9% |
| BINARY_OP | 800,330 | 25.3% |
| LOAD_FAST | 532,029 | 16.8% |
| LOAD_ATTR_INSTANCE_VALUE | 279,925 | 8.9% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,150,218 | 68.1% |
| POP_JUMP_IF_TRUE | 1,007,167 | 31.9% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,196,578 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,196,578 | 100.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 495,358 | 99.8% |
| LOAD_FAST | 740 | 0.1% |
| LOAD_ATTR | 300 | 0.1% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 496,498 | 100.0% |


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
| FOR_ITER_LIST | 559,850 | 51.2% |
| STORE_FAST | 532,011 | 48.7% |
| BINARY_SLICE | 180 | 0.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |
| END_SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,092,341 | 100.0% |
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
|          hit |        13106 | 99.7% |

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
|          hit |       252566 | 99.9% |

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
| specialization.deferred |      1826061 | 11.0% |
|          hit |     14843173 | 89.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,020 | 58.0% |
| Failure | 740 | 42.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence | 260 | 35.1% |
| bytes | 180 | 24.3% |
| mapping | 60 | 8.1% |
| dict | 60 | 8.1% |
| bytearray | 60 | 8.1% |
| set | 40 | 5.4% |
| memory view | 40 | 5.4% |
| tuple | 20 | 2.7% |
| float | 20 | 2.7% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3169154 | 76.6% |
|          hit |       967917 | 23.4% |

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
| specialization.deferred |      3265426 | 13.5% |
|          hit |     20927075 | 86.5% |
|         miss |         1800 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,720 | 50.9% |
| Failure | 2,620 | 49.1% |

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
| specialization.deferred |        12986 | 0.5% |
|          hit |      2784048 | 99.5% |

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
| specialization.deferred |        12240 | 0.8% |
|          hit |      1444257 | 99.1% |

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
| specialization.deferred |      4122188 | 8.1% |
|          hit |     46823994 | 91.9% |

#### Specialization attempts

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
|          hit |     12412168 | 100.0% |
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
| specialization.deferred |       493198 | 28.7% |
|          hit |      1227715 | 71.3% |

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
|          hit |      5912400 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,260 | 88.7% |
| Failure | 160 | 11.3% |

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
|          hit |      1093001 | 100.0% |

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
| Basic | 151,043,935 | 48.9% |
| Not specialized | 35,314,368 | 11.4% |
| Specialized | 122,748,348 | 39.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 4,122,188 | 31.9% |
| CALL | 3,265,426 | 25.3% |
| BINARY_OP | 3,169,154 | 24.6% |
| TO_BOOL | 1,826,061 | 14.2% |
| SEND | 493,198 | 3.8% |
| COMPARE_OP | 12,986 | 0.1% |
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
| Calls to PyEval_EvalDefault | 1,999,324 | 12.0% |
| Calls to Python functions inlined | 14,708,707 | 88.0% |
| Calls via PyEval_EvalFrame (total) | 1,999,324 | 12.0% |
| Calls via PyEval_EvalFrame (vector) | 1,752,305 | 10.5% |
| Calls via PyEval_EvalFrame (generator) | 247,019 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,752,305 | 10.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 840 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 494,518 | 3.0% |
| Frames pushed | 15,233,717 | 91.2% |
| Frame objects created | 780 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 7,208,020 | 43.1% |
| Frees to freelist | 7,219,986 |  |
| Allocations | 9,524,080 | 56.9% |
| Allocations to 512 bytes | 9,042,780 | 54.0% |
| Allocations to 4 kbytes | 360 | 0.0% |
| Allocations over 4 kbytes | 480,940 | 2.9% |
| Frees | 9,871,522 |  |
| New values | 420 |  |
| Interpreter increfs | 128,807,072 | 82.5% |
| Interpreter decrefs | 139,876,382 | 81.6% |
| Increfs | 27,312,539 | 17.5% |
| Decrefs | 31,508,232 | 18.4% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 4,672,476 |  |
| Method cache misses | 515 |  |
| Method cache collisions | 695 |  |
| Method cache dunder hits | 1,271,610 |  |
| Method cache dunder misses | 203 |  |


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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
