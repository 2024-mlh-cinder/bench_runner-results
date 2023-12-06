
# Pystats results

- benchmark: asyncio_tcp
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 67,035,883 | 21.4% | 21.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 22,793,313 | 7.3% | 28.7% |  |
| RESUME_CHECK | 16,213,931 | 5.2% | 33.9% |  |
| STORE_FAST | 14,798,324 | 4.7% | 38.6% |  |
| POP_JUMP_IF_FALSE | 13,694,457 | 4.4% | 43.0% |  |
| CALL_PY_EXACT_ARGS | 12,233,917 | 3.9% | 46.9% |  |
| LOAD_CONST | 10,886,208 | 3.5% | 50.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,730,581 | 3.4% | 53.8% |  |
| TO_BOOL_BOOL | 9,986,396 | 3.2% | 57.0% |  |
| POP_TOP | 9,632,796 | 3.1% | 60.1% |  |
| RETURN_VALUE | 9,411,505 | 3.0% | 63.1% |  |
| LOAD_GLOBAL_MODULE | 6,623,074 | 2.1% | 65.2% |  |
| LOAD_FAST_LOAD_FAST | 6,072,417 | 1.9% | 67.1% |  |
| RETURN_CONST | 5,821,730 | 1.9% | 69.0% |  |
| LOAD_GLOBAL_BUILTIN | 5,788,884 | 1.8% | 70.8% | 0.0% |
| LOAD_ATTR_SLOT | 5,217,320 | 1.7% | 72.5% |  |
| POP_JUMP_IF_TRUE | 5,059,571 | 1.6% | 74.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,728,543 | 1.5% | 75.6% |  |
| STORE_ATTR_SLOT | 4,209,223 | 1.3% | 77.0% |  |
| LOAD_ATTR | 4,176,069 | 1.3% | 78.3% |  |
| NOP | 3,766,055 | 1.2% | 79.5% |  |
| CALL | 3,270,732 | 1.0% | 80.6% |  |
| BINARY_OP | 3,170,318 | 1.0% | 81.6% |  |
| TO_BOOL_INT | 3,163,435 | 1.0% | 82.6% |  |
| COMPARE_OP_INT | 2,783,834 | 0.9% | 83.5% |  |
| LOAD_ATTR_MODULE | 2,567,347 | 0.8% | 84.3% |  |
| PUSH_NULL | 2,316,535 | 0.7% | 85.0% |  |
| CALL_LEN | 2,214,712 | 0.7% | 85.7% |  |
| COPY | 2,026,153 | 0.6% | 86.4% |  |
| INTERPRETER_EXIT | 1,999,312 | 0.6% | 87.0% |  |
| JUMP_FORWARD | 1,960,362 | 0.6% | 87.7% |  |
| TO_BOOL | 1,833,885 | 0.6% | 88.2% |  |
| POP_JUMP_IF_NOT_NONE | 1,750,876 | 0.6% | 88.8% |  |
| POP_JUMP_IF_NONE | 1,721,277 | 0.5% | 89.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 1,703,157 | 0.5% | 89.9% |  |
| GET_ITER | 1,449,957 | 0.5% | 90.4% |  |
| BUILD_LIST | 1,249,933 | 0.4% | 90.8% |  |
| SEND_GEN | 1,227,715 | 0.4% | 91.2% |  |
| TO_BOOL_LIST | 1,196,698 | 0.4% | 91.5% |  |
| ENTER_EXECUTOR | 1,093,724 | 0.3% | 91.9% |  |
| STORE_FAST_STORE_FAST | 1,092,547 | 0.3% | 92.2% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,427 | 0.3% | 92.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,012,897 | 0.3% | 92.9% |  |
| CALL_ISINSTANCE | 992,204 | 0.3% | 93.2% |  |
| YIELD_VALUE | 980,756 | 0.3% | 93.5% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 980,636 | 0.3% | 93.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 973,341 | 0.3% | 94.2% |  |
| FOR_ITER_LIST | 962,938 | 0.3% | 94.5% |  |
| UNARY_NOT | 960,120 | 0.3% | 94.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 820,728 | 0.3% | 95.0% | 0.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 816,348 | 0.3% | 95.3% | 0.2% |
| BUILD_TUPLE | 779,857 | 0.2% | 95.6% |  |
| CALL_FUNCTION_EX | 768,254 | 0.2% | 95.8% |  |
| LIST_EXTEND | 767,894 | 0.2% | 96.0% |  |
| CALL_INTRINSIC_1 | 767,894 | 0.2% | 96.3% |  |
| GET_AWAITABLE | 740,277 | 0.2% | 96.5% |  |
| END_SEND | 740,277 | 0.2% | 96.8% |  |
| JUMP_BACKWARD | 727,697 | 0.2% | 97.0% |  |
| LOAD_DEREF | 543,770 | 0.2% | 97.2% |  |
| CALL_BUILTIN_CLASS | 539,197 | 0.2% | 97.3% |  |
| SWAP | 532,837 | 0.2% | 97.5% |  |
| COPY_FREE_VARS | 518,526 | 0.2% | 97.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 498,362 | 0.2% | 97.8% |  |
| TO_BOOL_NONE | 496,498 | 0.2% | 98.0% |  |
| RETURN_GENERATOR | 493,978 | 0.2% | 98.1% |  |
| SEND | 493,598 | 0.2% | 98.3% |  |
| CALL_PY_WITH_DEFAULTS | 493,282 | 0.2% | 98.5% |  |
| UNARY_INVERT | 486,401 | 0.2% | 98.6% |  |
| LOAD_SUPER_ATTR_METHOD | 482,100 | 0.2% | 98.8% |  |
| FOR_ITER_RANGE | 481,199 | 0.2% | 98.9% |  |
| BINARY_OP_ADD_FLOAT | 480,959 | 0.2% | 99.1% |  |
| CALL_LIST_APPEND | 280,335 | 0.1% | 99.2% |  |
| BINARY_SLICE | 280,215 | 0.1% | 99.3% |  |
| CALL_KW | 260,121 | 0.1% | 99.3% |  |
| STORE_SUBSCR_DICT | 252,562 | 0.1% | 99.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 252,081 | 0.1% | 99.5% |  |
| CONTAINS_OP | 241,080 | 0.1% | 99.6% |  |
| LOAD_ATTR_PROPERTY | 241,019 | 0.1% | 99.7% |  |
| BINARY_OP_ADD_INT | 240,539 | 0.1% | 99.7% |  |
| DELETE_SUBSCR | 240,239 | 0.1% | 99.8% |  |
| BUILD_SLICE | 240,239 | 0.1% | 99.9% |  |
| BINARY_OP_MULTIPLY_INT | 240,239 | 0.1% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,616 | 0.0% | 100.0% |  |
| COMPARE_OP | 13,462 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 12,742 | 0.0% | 100.0% |  |
| FOR_ITER | 12,420 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 22,046,509 | 7.0% | 7.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 11,247,317 | 3.6% | 10.6% |
| RESUME_CHECK LOAD_FAST | 10,196,301 | 3.3% | 13.9% |
| STORE_FAST LOAD_FAST | 8,961,212 | 2.9% | 16.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,419,013 | 2.4% | 19.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,793,743 | 2.2% | 21.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,762,587 | 1.8% | 23.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,543,953 | 1.8% | 24.9% |
| LOAD_FAST LOAD_ATTR_SLOT | 5,211,220 | 1.7% | 26.6% |
| RETURN_CONST POP_TOP | 4,791,236 | 1.5% | 28.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,714,214 | 1.5% | 29.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 4,428,488 | 1.4% | 31.0% |
| LOAD_CONST LOAD_FAST | 4,412,638 | 1.4% | 32.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 4,225,915 | 1.4% | 33.8% |
| POP_TOP LOAD_FAST | 4,000,452 | 1.3% | 35.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,969,549 | 1.3% | 36.3% |
| LOAD_FAST RETURN_VALUE | 3,444,987 | 1.1% | 37.4% |
| LOAD_FAST LOAD_ATTR | 3,378,671 | 1.1% | 38.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 2,973,875 | 1.0% | 39.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 2,973,623 | 1.0% | 40.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,832,784 | 0.9% | 41.3% |
| POP_JUMP_IF_TRUE LOAD_FAST | 2,832,199 | 0.9% | 42.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,783,594 | 0.9% | 43.1% |
| NOP LOAD_FAST | 2,780,271 | 0.9% | 44.0% |
| LOAD_CONST STORE_FAST | 2,734,995 | 0.9% | 44.9% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,710,283 | 0.9% | 45.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,566,007 | 0.8% | 46.6% |
| RETURN_VALUE STORE_FAST | 2,477,485 | 0.8% | 47.4% |
| LOAD_FAST LOAD_CONST | 2,459,743 | 0.8% | 48.1% |
| RETURN_VALUE TO_BOOL_BOOL | 2,445,062 | 0.8% | 48.9% |
| LOAD_FAST STORE_ATTR_SLOT | 2,233,143 | 0.7% | 49.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,232,593 | 0.7% | 50.4% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,156,220 | 0.7% | 51.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 2,084,926 | 0.7% | 51.7% |
| POP_TOP RETURN_CONST | 2,040,867 | 0.7% | 52.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,000,279 | 0.6% | 53.0% |
| CACHE RESUME_CHECK | 1,998,172 | 0.6% | 53.6% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,976,080 | 0.6% | 54.3% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 1,922,996 | 0.6% | 54.9% |
| TO_BOOL POP_JUMP_IF_TRUE | 1,819,223 | 0.6% | 55.5% |
| RESUME_CHECK NOP | 1,765,580 | 0.6% | 56.0% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,732,601 | 0.6% | 56.6% |
| STORE_FAST JUMP_FORWARD | 1,719,282 | 0.5% | 57.1% |
| LOAD_CONST COMPARE_OP_INT | 1,713,301 | 0.5% | 57.7% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,699,617 | 0.5% | 58.2% |
| COPY TO_BOOL_INT | 1,545,193 | 0.5% | 58.7% |
| LOAD_GLOBAL_MODULE BINARY_OP | 1,544,833 | 0.5% | 59.2% |
| CALL STORE_FAST | 1,520,138 | 0.5% | 59.7% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,511,235 | 0.5% | 60.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,509,677 | 0.5% | 60.7% |
| POP_TOP LOAD_CONST | 1,501,894 | 0.5% | 61.1% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 1,481,640 | 0.5% | 61.6% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,479,058 | 0.5% | 62.1% |
| JUMP_FORWARD LOAD_FAST | 1,478,923 | 0.5% | 62.6% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 1,472,463 | 0.5% | 63.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,421,037 | 0.5% | 63.5% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 1,379,561 | 0.4% | 63.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 1,299,153 | 0.4% | 64.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,262,076 | 0.4% | 64.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,256,693 | 0.4% | 65.1% |
| STORE_ATTR_SLOT LOAD_CONST | 1,234,261 | 0.4% | 65.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,231,963 | 0.4% | 65.9% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 1,196,578 | 0.4% | 66.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 1,196,578 | 0.4% | 66.7% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,092,307 | 0.3% | 67.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,091,947 | 0.3% | 67.4% |
| BINARY_OP COPY | 1,064,234 | 0.3% | 67.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,026,856 | 0.3% | 68.1% |
| LOAD_ATTR LOAD_FAST | 1,025,879 | 0.3% | 68.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,024,920 | 0.3% | 68.7% |
| LOAD_FAST TO_BOOL | 1,024,775 | 0.3% | 69.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,020,876 | 0.3% | 69.4% |
| POP_JUMP_IF_FALSE POP_TOP | 1,018,638 | 0.3% | 69.7% |
| STORE_FAST RETURN_CONST | 1,008,733 | 0.3% | 70.0% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 1,007,155 | 0.3% | 70.3% |
| CALL RETURN_VALUE | 1,002,014 | 0.3% | 70.7% |
| CALL_LEN STORE_FAST | 1,001,613 | 0.3% | 71.0% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 992,104 | 0.3% | 71.3% |
| RETURN_VALUE RETURN_VALUE | 986,204 | 0.3% | 71.6% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 985,744 | 0.3% | 71.9% |
| NOP LOAD_GLOBAL_MODULE | 985,164 | 0.3% | 72.2% |
| LOAD_FAST STORE_FAST | 985,064 | 0.3% | 72.6% |
| POP_JUMP_IF_TRUE LOAD_CONST | 985,060 | 0.3% | 72.9% |
| LOAD_FAST POP_JUMP_IF_NONE | 981,559 | 0.3% | 73.2% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 980,636 | 0.3% | 73.5% |
| RETURN_VALUE INTERPRETER_EXIT | 975,298 | 0.3% | 73.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 974,999 | 0.3% | 74.1% |
| STORE_FAST NOP | 974,361 | 0.3% | 74.4% |
| LOAD_FAST GET_ITER | 962,578 | 0.3% | 74.7% |
| GET_ITER FOR_ITER_LIST | 962,498 | 0.3% | 75.0% |
| TO_BOOL_BOOL UNARY_NOT | 960,060 | 0.3% | 75.4% |
| PUSH_NULL LOAD_FAST | 839,833 | 0.3% | 75.6% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 820,668 | 0.3% | 75.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 807,150 | 0.3% | 76.1% |
| BINARY_OP TO_BOOL_INT | 800,310 | 0.3% | 76.4% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 786,313 | 0.3% | 76.6% |
| BINARY_OP STORE_FAST | 778,458 | 0.2% | 76.9% |
| RETURN_CONST INTERPRETER_EXIT | 776,995 | 0.2% | 77.1% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 774,215 | 0.2% | 77.4% |
| LOAD_ATTR PUSH_NULL | 768,154 | 0.2% | 77.6% |


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
| LOAD_CONST | 39,976 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,239 | 85.7% |
| CALL_METHOD_DESCRIPTOR_O | 33,695 | 12.0% |
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
| RESUME_CHECK | 1,998,172 | 99.9% |
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
| RETURN_CONST | 776,995 | 38.9% |
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
| RESUME_CHECK | 1,765,580 | 46.9% |
| STORE_FAST | 974,361 | 25.9% |
| POP_JUMP_IF_FALSE | 520,875 | 13.8% |
| POP_JUMP_IF_TRUE | 246,340 | 6.5% |
| STORE_ATTR_INSTANCE_VALUE | 240,239 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,780,271 | 73.8% |
| LOAD_GLOBAL_MODULE | 985,164 | 26.2% |
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
| RETURN_CONST | 4,791,236 | 49.7% |
| POP_JUMP_IF_FALSE | 1,018,638 | 10.6% |
| CALL_METHOD_DESCRIPTOR_O | 820,668 | 8.5% |
| CALL_FUNCTION_EX | 767,834 | 8.0% |
| END_SEND | 499,378 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,000,452 | 41.5% |
| RETURN_CONST | 2,040,867 | 21.2% |
| LOAD_CONST | 1,501,894 | 15.6% |
| ENTER_EXECUTOR | 573,390 | 6.0% |
| LOAD_GLOBAL_MODULE | 527,096 | 5.5% |


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
| LOAD_ATTR_MODULE | 1,511,235 | 65.2% |
| LOAD_ATTR | 768,154 | 33.2% |
| LOAD_DEREF | 35,586 | 1.5% |
| LOAD_FAST | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 839,833 | 36.3% |
| LOAD_FAST_LOAD_FAST | 746,582 | 32.2% |
| CALL | 729,460 | 31.5% |
| LOAD_CONST | 360 | 0.0% |
| CALL_PY_EXACT_ARGS | 160 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 493,078 | 99.8% |
| CALL_KW | 300 | 0.1% |
| CACHE | 240 | 0.0% |
| MAKE_CELL | 180 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 120 | 0.0% |

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
| LOAD_FAST | 3,444,987 | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,710,283 | 28.8% |
| CALL | 1,002,014 | 10.6% |
| RETURN_VALUE | 986,204 | 10.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,622 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,477,485 | 26.3% |
| TO_BOOL_BOOL | 2,445,062 | 26.0% |
| RETURN_VALUE | 986,204 | 10.5% |
| INTERPRETER_EXIT | 975,298 | 10.4% |
| LOAD_FAST | 761,474 | 8.1% |


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
| LOAD_FAST | 1,024,775 | 55.9% |
| LOAD_ATTR_INSTANCE_VALUE | 807,150 | 44.0% |
| TO_BOOL | 780 | 0.0% |
| LOAD_ATTR | 560 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,819,223 | 99.2% |
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
| LOAD_GLOBAL_MODULE | 1,544,833 | 48.7% |
| LOAD_ATTR_MODULE | 565,991 | 17.9% |
| UNARY_INVERT | 486,401 | 15.3% |
| POP_JUMP_IF_FALSE | 285,837 | 9.0% |
| LOAD_ATTR | 280,035 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,064,234 | 33.6% |
| TO_BOOL_INT | 800,310 | 25.2% |
| STORE_FAST | 778,458 | 24.6% |
| BUILD_TUPLE | 280,035 | 8.8% |
| UNARY_INVERT | 240,240 | 7.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 527,654 | 42.2% |
| STORE_FAST | 481,079 | 38.5% |
| LOAD_FAST_LOAD_FAST | 240,060 | 19.2% |
| LOAD_FAST | 480 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 768,134 | 61.5% |
| STORE_FAST | 481,439 | 38.5% |
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
| BINARY_OP | 280,035 | 35.9% |
| LOAD_CONST | 246,101 | 31.6% |
| LOAD_FAST | 240,720 | 30.9% |
| LOAD_FAST_LOAD_FAST | 6,521 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 6,180 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 280,035 | 35.9% |
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
| PUSH_NULL | 729,460 | 22.3% |
| LOAD_FAST_LOAD_FAST | 500,181 | 15.3% |
| LOAD_CONST | 493,500 | 15.1% |
| LOAD_ATTR_INSTANCE_VALUE | 487,119 | 14.9% |
| LOAD_ATTR | 240,760 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,520,138 | 46.5% |
| RETURN_VALUE | 1,002,014 | 30.6% |
| POP_TOP | 247,979 | 7.6% |
| RESUME_CHECK | 247,001 | 7.6% |
| LOAD_CONST | 240,299 | 7.3% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 767,894 | 100.0% |
| LOAD_FAST | 180 | 0.0% |
| DICT_MERGE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 767,834 | 99.9% |
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
| LIST_EXTEND | 767,894 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 767,894 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 260,121 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 246,659 | 94.8% |
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
| BINARY_OP | 1,064,234 | 52.5% |
| CALL_LEN | 480,959 | 23.7% |
| UNARY_NOT | 480,060 | 23.7% |
| LOAD_FAST | 360 | 0.0% |
| CALL_BUILTIN_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,545,193 | 76.3% |
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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 573,390 | 52.4% |
| CALL_LIST_APPEND | 280,035 | 25.6% |
| POP_JUMP_IF_TRUE | 240,299 | 22.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480,899 | 44.0% |
| LOAD_FAST | 279,975 | 25.6% |
| RETURN_CONST | 279,915 | 25.6% |
| LOAD_ATTR_METHOD_NO_DICT | 46,875 | 4.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,940 | 0.5% |


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
| POP_JUMP_IF_FALSE | 481,038 | 66.1% |
| STORE_FAST | 240,179 | 33.0% |
| POP_TOP | 6,300 | 0.9% |
| CALL_LIST_APPEND | 120 | 0.0% |
| LIST_APPEND | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 721,157 | 99.1% |
| FOR_ITER | 6,060 | 0.8% |
| FOR_ITER_LIST | 300 | 0.0% |
| FOR_ITER_RANGE | 120 | 0.0% |
| FOR_ITER_TUPLE | 60 | 0.0% |


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
| STORE_FAST | 1,719,282 | 87.7% |
| POP_TOP | 240,600 | 12.3% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| STORE_ATTR | 120 | 0.0% |
| CALL_LIST_APPEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,478,923 | 75.4% |
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
| LOAD_ATTR_SLOT | 527,654 | 68.7% |
| LOAD_FAST | 240,060 | 31.3% |
| BINARY_SLICE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 767,894 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,378,671 | 80.9% |
| LOAD_ATTR_SLOT | 767,814 | 18.4% |
| LOAD_FAST_LOAD_FAST | 23,844 | 0.6% |
| LOAD_ATTR | 2,760 | 0.1% |
| LOAD_GLOBAL_MODULE | 1,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,025,879 | 24.6% |
| PUSH_NULL | 768,154 | 18.4% |
| SWAP | 531,997 | 12.7% |
| LOAD_ATTR_METHOD_NO_DICT | 286,516 | 6.9% |
| BINARY_OP | 280,035 | 6.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,459,743 | 22.6% |
| POP_JUMP_IF_FALSE | 1,732,601 | 15.9% |
| POP_TOP | 1,501,894 | 13.8% |
| STORE_ATTR_SLOT | 1,234,261 | 11.3% |
| POP_JUMP_IF_TRUE | 985,060 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,412,638 | 40.5% |
| STORE_FAST | 2,734,995 | 25.1% |
| COMPARE_OP_INT | 1,713,301 | 15.7% |
| SEND_GEN | 493,558 | 4.5% |
| CALL | 493,500 | 4.5% |


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
| RESUME_CHECK | 10,196,301 | 15.2% |
| STORE_FAST | 8,961,212 | 13.4% |
| POP_JUMP_IF_FALSE | 7,419,013 | 11.1% |
| LOAD_CONST | 4,412,638 | 6.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,225,915 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 22,046,509 | 32.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,543,953 | 8.3% |
| LOAD_ATTR_SLOT | 5,211,220 | 7.8% |
| CALL_PY_EXACT_ARGS | 4,714,214 | 7.0% |
| RETURN_VALUE | 3,444,987 | 5.1% |


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
| STORE_ATTR_SLOT | 1,481,640 | 24.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,299,153 | 21.4% |
| PUSH_NULL | 746,582 | 12.3% |
| LOAD_FAST_LOAD_FAST | 489,419 | 8.1% |
| LOAD_GLOBAL_MODULE | 481,620 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,976,080 | 32.5% |
| LOAD_FAST | 1,262,076 | 20.8% |
| CALL | 500,181 | 8.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 492,622 | 8.1% |
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
| TO_BOOL_BOOL | 6,793,743 | 49.6% |
| COMPARE_OP_INT | 2,783,594 | 20.3% |
| TO_BOOL_INT | 2,156,220 | 15.7% |
| TO_BOOL_LIST | 1,196,578 | 8.7% |
| TO_BOOL_NONE | 496,498 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,419,013 | 54.2% |
| LOAD_CONST | 1,732,601 | 12.7% |
| RETURN_CONST | 1,026,856 | 7.5% |
| POP_TOP | 1,018,638 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 721,119 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 981,559 | 57.0% |
| LOAD_ATTR_INSTANCE_VALUE | 739,358 | 43.0% |
| LOAD_ATTR | 120 | 0.0% |
| CALL | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,479,058 | 85.9% |
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
| LOAD_FAST | 1,509,677 | 86.2% |
| LOAD_ATTR_INSTANCE_VALUE | 240,899 | 13.8% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020,876 | 58.3% |
| LOAD_FAST_LOAD_FAST | 247,619 | 14.1% |
| LOAD_GLOBAL_MODULE | 247,461 | 14.1% |
| LOAD_CONST | 234,120 | 13.4% |
| RETURN_CONST | 240 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,232,593 | 44.1% |
| TO_BOOL | 1,819,223 | 36.0% |
| TO_BOOL_INT | 1,007,155 | 19.9% |
| COMPARE_OP_INT | 240 | 0.0% |
| CONTAINS_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,832,199 | 56.0% |
| LOAD_CONST | 985,060 | 19.5% |
| STORE_FAST | 480,959 | 9.5% |
| NOP | 246,340 | 4.9% |
| ENTER_EXECUTOR | 240,299 | 4.7% |


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
| POP_TOP | 2,040,867 | 35.1% |
| POP_JUMP_IF_FALSE | 1,026,856 | 17.6% |
| STORE_FAST | 1,008,733 | 17.3% |
| STORE_ATTR_SLOT | 740,661 | 12.7% |
| STORE_ATTR_INSTANCE_VALUE | 481,679 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,791,236 | 82.3% |
| INTERPRETER_EXIT | 776,995 | 13.3% |
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
| LOAD_CONST | 2,734,995 | 18.5% |
| RETURN_VALUE | 2,477,485 | 16.7% |
| CALL | 1,520,138 | 10.3% |
| CALL_LEN | 1,001,613 | 6.8% |
| LOAD_FAST | 985,064 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,961,212 | 60.6% |
| JUMP_FORWARD | 1,719,282 | 11.6% |
| RETURN_CONST | 1,008,733 | 6.8% |
| NOP | 974,361 | 6.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 531,997 | 3.6% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,092,307 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,091,947 | 99.9% |
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
| LOAD_ATTR | 531,997 | 99.8% |
| BINARY_OP_ADD_INT | 240 | 0.0% |
| BUILD_TUPLE | 180 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 531,997 | 99.8% |
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
| LOAD_ATTR_INSTANCE_VALUE | 240,239 | 95.3% |
| CALL_BUILTIN_CLASS | 11,842 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240,239 | 95.3% |
| COPY_FREE_VARS | 11,842 | 4.7% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 493,021 | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE | 45,776 | 8.5% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 481,139 | 89.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 45,616 | 8.5% |
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
| CALL_BUILTIN_CLASS | 45,616 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 45,616 | 100.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 1,922,996 | 86.8% |
| LOAD_FAST | 291,716 | 13.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,001,613 | 45.2% |
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
| BUILD_TUPLE | 280,035 | 99.9% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 280,035 | 99.9% |
| JUMP_FORWARD | 120 | 0.0% |
| JUMP_BACKWARD | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 492,622 | 48.6% |
| LOAD_FAST | 280,035 | 27.6% |
| RETURN_VALUE | 240,240 | 23.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 520,275 | 51.4% |
| RETURN_VALUE | 492,622 | 48.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 480,959 | 49.4% |
| LOAD_FAST | 252,082 | 25.9% |
| LOAD_ATTR | 240,240 | 24.7% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 492,322 | 50.6% |
| STORE_FAST | 480,959 | 49.4% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 568,529 | 69.6% |
| LOAD_ATTR | 247,039 | 30.3% |
| CALL | 440 | 0.1% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 567,529 | 69.5% |
| TO_BOOL_BOOL | 246,999 | 30.3% |
| POP_TOP | 540 | 0.1% |
| LOAD_FAST | 420 | 0.1% |
| CALL | 280 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 786,313 | 95.8% |
| BINARY_SLICE | 33,695 | 4.1% |
| CALL | 480 | 0.1% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 820,668 | 100.0% |
| PUSH_EXC_INFO | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,762,587 | 47.1% |
| LOAD_FAST | 4,714,214 | 38.5% |
| LOAD_ATTR_METHOD_NO_DICT | 774,215 | 6.3% |
| BUILD_TUPLE | 252,062 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 246,261 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,247,317 | 91.9% |
| COPY_FREE_VARS | 493,522 | 4.0% |
| RETURN_GENERATOR | 493,078 | 4.0% |


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
| LOAD_CONST | 1,713,301 | 61.5% |
| LOAD_GLOBAL_MODULE | 480,959 | 17.3% |
| BINARY_OP_MULTIPLY_INT | 240,219 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 239,940 | 8.6% |
| LOAD_ATTR_SLOT | 45,616 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,783,594 | 100.0% |
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
| UNPACK_SEQUENCE_TWO_TUPLE | 559,830 | 58.1% |
| RETURN_CONST | 201,224 | 20.9% |
| LOAD_FAST | 201,044 | 20.9% |
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
| LOAD_FAST | 22,046,509 | 96.7% |
| LOAD_ATTR_INSTANCE_VALUE | 492,502 | 2.2% |
| LOAD_FAST_LOAD_FAST | 252,822 | 1.1% |
| LOAD_ATTR | 1,120 | 0.0% |
| COPY | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,428,488 | 19.4% |
| LOAD_ATTR_METHOD_NO_DICT | 2,973,875 | 13.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,973,623 | 13.0% |
| RETURN_VALUE | 2,710,283 | 11.9% |
| CALL_LEN | 1,922,996 | 8.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,973,875 | 62.9% |
| LOAD_FAST | 1,421,037 | 30.1% |
| LOAD_ATTR | 286,516 | 6.1% |
| ENTER_EXECUTOR | 46,875 | 1.0% |
| LOAD_ATTR_SLOT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,084,926 | 44.1% |
| LOAD_FAST_LOAD_FAST | 1,299,153 | 27.5% |
| CALL_PY_EXACT_ARGS | 774,215 | 16.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 568,529 | 12.0% |
| LOAD_GLOBAL_MODULE | 620 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,543,953 | 51.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,973,623 | 27.7% |
| LOAD_ATTR_SLOT | 1,472,463 | 13.7% |
| RETURN_VALUE | 492,702 | 4.6% |
| LOAD_FAST_LOAD_FAST | 240,240 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,762,587 | 53.7% |
| LOAD_FAST | 4,225,915 | 39.4% |
| LOAD_FAST_LOAD_FAST | 260,181 | 2.4% |
| LOAD_CONST | 240,479 | 2.2% |
| LOAD_GLOBAL_MODULE | 240,439 | 2.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,566,007 | 99.9% |
| LOAD_ATTR | 1,100 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| ENTER_EXECUTOR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,511,235 | 58.9% |
| BINARY_OP | 565,991 | 22.0% |
| UNARY_INVERT | 246,161 | 9.6% |
| LOAD_FAST | 240,360 | 9.4% |
| COMPARE_OP | 780 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 498,342 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,142 | 50.6% |
| CALL | 240,239 | 48.2% |
| BINARY_OP | 5,981 | 1.2% |


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
| LOAD_FAST | 5,211,220 | 99.9% |
| LOAD_FAST_LOAD_FAST | 6,000 | 0.1% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,472,463 | 28.2% |
| TO_BOOL_BOOL | 1,379,561 | 26.4% |
| LOAD_ATTR | 767,814 | 14.7% |
| LIST_EXTEND | 527,654 | 10.1% |
| BUILD_LIST | 527,654 | 10.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,000,279 | 34.6% |
| LOAD_FAST | 1,231,963 | 21.3% |
| POP_JUMP_IF_FALSE | 721,119 | 12.5% |
| STORE_FAST | 526,995 | 9.1% |
| JUMP_FORWARD | 481,199 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,969,549 | 68.6% |
| CALL_ISINSTANCE | 985,744 | 17.0% |
| LOAD_DEREF | 482,640 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 343,631 | 5.9% |
| BUILD_TUPLE | 6,180 | 0.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,832,784 | 42.8% |
| RESUME_CHECK | 1,256,693 | 19.0% |
| NOP | 985,164 | 14.9% |
| POP_TOP | 527,096 | 8.0% |
| POP_JUMP_IF_NOT_NONE | 247,461 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,566,007 | 38.7% |
| BINARY_OP | 1,544,833 | 23.3% |
| LOAD_FAST | 1,024,920 | 15.5% |
| LOAD_FAST_LOAD_FAST | 481,620 | 7.3% |
| COMPARE_OP_INT | 480,959 | 7.3% |


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
| CALL_PY_EXACT_ARGS | 11,247,317 | 69.4% |
| CACHE | 1,998,172 | 12.3% |
| SEND_GEN | 734,037 | 4.5% |
| COPY_FREE_VARS | 518,406 | 3.2% |
| POP_TOP | 493,978 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,196,301 | 62.9% |
| LOAD_GLOBAL_BUILTIN | 2,000,279 | 12.3% |
| NOP | 1,765,580 | 10.9% |
| LOAD_GLOBAL_MODULE | 1,256,693 | 7.8% |
| JUMP_BACKWARD_NO_INTERRUPT | 980,636 | 6.0% |


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
| LOAD_FAST | 2,233,143 | 53.1% |
| LOAD_FAST_LOAD_FAST | 1,976,080 | 46.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,481,640 | 35.2% |
| LOAD_CONST | 1,234,261 | 29.3% |
| RETURN_CONST | 740,661 | 17.6% |
| LOAD_FAST | 740,661 | 17.6% |
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
| LOAD_ATTR_INSTANCE_VALUE | 4,428,488 | 44.3% |
| RETURN_VALUE | 2,445,062 | 24.5% |
| LOAD_ATTR_SLOT | 1,379,561 | 13.8% |
| CALL_ISINSTANCE | 992,104 | 9.9% |
| COPY | 480,300 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,793,743 | 68.0% |
| POP_JUMP_IF_TRUE | 2,232,593 | 22.4% |
| UNARY_NOT | 960,060 | 9.6% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,545,193 | 48.8% |
| BINARY_OP | 800,310 | 25.3% |
| LOAD_FAST | 532,017 | 16.8% |
| LOAD_ATTR_INSTANCE_VALUE | 285,855 | 9.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,156,220 | 68.2% |
| POP_JUMP_IF_TRUE | 1,007,155 | 31.8% |
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
| FOR_ITER_LIST | 559,830 | 51.2% |
| STORE_FAST | 531,997 | 48.7% |
| BINARY_SLICE | 180 | 0.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |
| END_SEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,092,307 | 100.0% |
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
| specialization.deferred |      1832085 | 11.0% |
|          hit |     14843027 | 89.0% |

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
| specialization.deferred |      3169198 | 76.6% |
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
| specialization.deferred |      3265392 | 13.5% |
|          hit |     20926859 | 86.5% |
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
| specialization.deferred |        12982 | 0.5% |
|          hit |      2784014 | 99.5% |

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
| specialization.deferred |      4168809 | 8.2% |
|          hit |     46776785 | 91.8% |

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
|          hit |     12411898 | 100.0% |
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
|          hit |      5912380 | 100.0% |

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
|          hit |      1092607 | 100.0% |

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
| Basic | 151,663,077 | 48.5% |
| Not specialized | 36,211,297 | 11.6% |
| Specialized | 125,097,613 | 40.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 4,168,809 | 32.2% |
| CALL | 3,265,392 | 25.2% |
| BINARY_OP | 3,169,198 | 24.5% |
| TO_BOOL | 1,832,085 | 14.1% |
| SEND | 493,198 | 3.8% |
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
| Calls to PyEval_EvalDefault | 1,999,312 | 12.0% |
| Calls to Python functions inlined | 14,708,597 | 88.0% |
| Calls via PyEval_EvalFrame (total) | 1,999,312 | 12.0% |
| Calls via PyEval_EvalFrame (vector) | 1,752,293 | 10.5% |
| Calls via PyEval_EvalFrame (generator) | 247,019 | 1.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,752,293 | 10.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 300 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 840 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 494,518 | 3.0% |
| Frames pushed | 15,233,595 | 91.2% |
| Frame objects created | 780 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 7,207,908 | 43.1% |
| Frees to freelist | 7,219,870 |  |
| Allocations | 9,523,889 | 56.9% |
| Allocations to 512 bytes | 9,042,577 | 54.0% |
| Allocations to 4 kbytes | 360 | 0.0% |
| Allocations over 4 kbytes | 480,952 | 2.9% |
| Frees | 9,871,317 |  |
| New values | 420 |  |
| Interpreter increfs | 131,092,022 | 84.3% |
| Interpreter decrefs | 140,390,988 | 82.2% |
| Increfs | 24,332,624 | 15.7% |
| Decrefs | 30,298,415 | 17.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 4,616,424 |  |
| Method cache misses | 56,483 |  |
| Method cache collisions | 56,584 |  |
| Method cache dunder hits | 1,271,676 |  |
| Method cache dunder misses | 121 |  |


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

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 42,760 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 1,093,724 |  |
| Uops executed | 7,951,478 | 7 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
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
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,040,789 | 95.2% |
| <= 16 | 52,815 | 4.8% |
| <= 32 | 120 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 2,234,923 | 28.1% | 28.1% |
| _POP_JUMP_IF_TRUE | 1,093,724 | 13.8% | 41.9% |
| _EXIT_TRACE | 1,093,724 | 13.8% | 55.6% |
| POP_TOP | 1,040,789 | 13.1% | 68.7% |
| _ITER_CHECK_LIST | 560,070 | 7.0% | 75.7% |
| _IS_ITER_EXHAUSTED_LIST | 560,070 | 7.0% | 82.8% |
| _ITER_CHECK_RANGE | 533,654 | 6.7% | 89.5% |
| _IS_ITER_EXHAUSTED_RANGE | 533,654 | 6.7% | 96.2% |
| STORE_FAST | 53,535 | 0.7% | 96.9% |
| LOAD_FAST | 53,175 | 0.7% | 97.6% |
| _ITER_NEXT_RANGE | 52,695 | 0.7% | 98.2% |
| _LOAD_ATTR_INSTANCE_VALUE | 46,755 | 0.6% | 98.8% |
| _GUARD_TYPE_VERSION | 46,755 | 0.6% | 99.4% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 46,755 | 0.6% | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 360 | 0.0% | 100.0% |
| _ITER_NEXT_LIST | 240 | 0.0% | 100.0% |
| LOAD_ATTR | 240 | 0.0% | 100.0% |
| _LOAD_GLOBAL_MODULE | 120 | 0.0% | 100.0% |
| _GUARD_GLOBALS_VERSION | 120 | 0.0% | 100.0% |
| SWAP | 120 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| LOAD_ATTR_METHOD_WITH_VALUES | 42,400 |
| FOR_ITER | 360 |


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
Stats gathered on: 2023-10-03
