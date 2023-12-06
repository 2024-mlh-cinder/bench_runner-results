
# Pystats results

- benchmark: async_tree_io
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 591,733,200 | 18.7% | 18.7% |  |
| RESUME_CHECK | 191,265,600 | 6.0% | 24.7% | 0.0% |
| POP_JUMP_IF_FALSE | 175,029,300 | 5.5% | 30.3% |  |
| LOAD_ATTR_SLOT | 155,765,320 | 4.9% | 35.2% | 0.0% |
| TO_BOOL_BOOL | 131,913,000 | 4.2% | 39.3% |  |
| LOAD_FAST_LOAD_FAST | 117,016,140 | 3.7% | 43.0% |  |
| LOAD_CONST | 114,786,420 | 3.6% | 46.7% |  |
| RETURN_VALUE | 110,637,420 | 3.5% | 50.2% |  |
| STORE_ATTR_SLOT | 106,937,220 | 3.4% | 53.5% | 0.0% |
| LOAD_GLOBAL_MODULE | 101,120,980 | 3.2% | 56.7% |  |
| POP_TOP | 100,783,440 | 3.2% | 59.9% |  |
| INTERPRETER_EXIT | 95,515,920 | 3.0% | 62.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 87,922,200 | 2.8% | 65.7% |  |
| STORE_FAST | 79,524,600 | 2.5% | 68.2% |  |
| RETURN_CONST | 78,947,160 | 2.5% | 70.7% |  |
| CALL_PY_EXACT_ARGS | 75,032,280 | 2.4% | 73.1% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 66,631,380 | 2.1% | 75.2% |  |
| LOAD_GLOBAL_BUILTIN | 56,332,440 | 1.8% | 77.0% | 0.0% |
| PUSH_NULL | 53,752,320 | 1.7% | 78.7% |  |
| CALL | 48,726,060 | 1.5% | 80.2% |  |
| LOAD_ATTR_MODULE | 47,032,720 | 1.5% | 81.7% |  |
| CALL_ISINSTANCE | 42,888,000 | 1.4% | 83.0% |  |
| COMPARE_OP_FLOAT | 42,887,820 | 1.4% | 84.4% |  |
| LOAD_DEREF | 35,832,060 | 1.1% | 85.5% |  |
| LOAD_ATTR | 33,045,820 | 1.0% | 86.6% |  |
| POP_JUMP_IF_NOT_NONE | 32,474,400 | 1.0% | 87.6% |  |
| TO_BOOL_NONE | 31,912,620 | 1.0% | 88.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 29,118,760 | 0.9% | 89.5% | 0.0% |
| ENTER_EXECUTOR | 22,955,940 | 0.7% | 90.2% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 16,862,740 | 0.5% | 90.8% | 20.3% |
| SEND_GEN | 16,796,400 | 0.5% | 91.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 16,796,340 | 0.5% | 91.8% | 0.0% |
| CALL_FUNCTION_EX | 16,236,420 | 0.5% | 92.3% |  |
| POP_JUMP_IF_TRUE | 12,880,320 | 0.4% | 92.7% |  |
| END_SEND | 11,757,420 | 0.4% | 93.1% |  |
| RETURN_GENERATOR | 11,757,420 | 0.4% | 93.5% |  |
| GET_AWAITABLE | 11,757,420 | 0.4% | 93.9% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 11,757,420 | 0.4% | 94.2% |  |
| YIELD_VALUE | 11,757,420 | 0.4% | 94.6% |  |
| CALL_KW | 10,637,580 | 0.3% | 94.9% |  |
| POP_JUMP_IF_NONE | 10,078,200 | 0.3% | 95.3% |  |
| NOP | 9,521,640 | 0.3% | 95.6% |  |
| COPY_FREE_VARS | 9,518,520 | 0.3% | 95.9% |  |
| STORE_DEREF | 9,517,620 | 0.3% | 96.2% |  |
| BUILD_LIST | 7,841,040 | 0.2% | 96.4% |  |
| COMPARE_OP_INT | 6,721,560 | 0.2% | 96.6% |  |
| SEND | 6,720,100 | 0.2% | 96.8% |  |
| BINARY_OP_ADD_INT | 6,718,380 | 0.2% | 97.0% |  |
| CALL_LIST_APPEND | 6,718,320 | 0.2% | 97.3% |  |
| LOAD_SUPER_ATTR_METHOD | 6,159,180 | 0.2% | 97.5% |  |
| CALL_BUILTIN_FAST | 6,158,700 | 0.2% | 97.6% |  |
| CALL_INTRINSIC_1 | 5,600,040 | 0.2% | 97.8% |  |
| LIST_EXTEND | 5,600,040 | 0.2% | 98.0% |  |
| TO_BOOL | 3,922,000 | 0.1% | 98.1% |  |
| STORE_ATTR | 3,921,140 | 0.1% | 98.2% |  |
| CONTAINS_OP | 3,919,140 | 0.1% | 98.4% |  |
| JUMP_FORWARD | 3,362,340 | 0.1% | 98.5% |  |
| TO_BOOL_LIST | 3,362,220 | 0.1% | 98.6% |  |
| COPY | 3,361,080 | 0.1% | 98.7% |  |
| BUILD_MAP | 3,359,460 | 0.1% | 98.8% |  |
| IS_OP | 3,359,460 | 0.1% | 98.9% |  |
| CALL_TYPE_1 | 3,359,220 | 0.1% | 99.0% |  |
| STORE_SUBSCR_DICT | 3,359,220 | 0.1% | 99.1% |  |
| LIST_APPEND | 3,359,160 | 0.1% | 99.2% |  |
| BINARY_OP_ADD_FLOAT | 2,800,740 | 0.1% | 99.3% |  |
| COMPARE_OP | 2,800,200 | 0.1% | 99.4% |  |
| CALL_PY_WITH_DEFAULTS | 2,799,720 | 0.1% | 99.5% |  |
| CALL_BUILTIN_O | 2,799,600 | 0.1% | 99.6% |  |
| MAKE_CELL | 2,799,360 | 0.1% | 99.7% |  |
| GET_ITER | 2,243,760 | 0.1% | 99.7% |  |
| SWAP | 1,679,820 | 0.1% | 99.8% |  |
| FOR_ITER_LIST | 1,122,540 | 0.0% | 99.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 562,740 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 561,840 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 561,240 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 560,340 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 560,040 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 560,040 | 0.0% | 99.9% |  |
| BINARY_OP_SUBTRACT_INT | 559,920 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 559,860 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 559,860 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 559,860 | 0.0% | 100.0% |  |
| CALL_LEN | 4,140 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 1,740 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,560 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,220 | 0.0% | 100.0% |  |
| BINARY_OP | 700 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 300 | 0.0% | 100.0% |  |
| FOR_ITER | 180 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 180 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 160 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 120 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 120 | 0.0% | 100.0% |  |
| POP_EXCEPT | 120 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 120 | 0.0% | 100.0% |  |
| UNARY_INVERT | 120 | 0.0% | 100.0% |  |
| UNARY_NOT | 120 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 120 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 120 | 0.0% | 100.0% |  |
| DICT_MERGE | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 60 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 60 | 0.0% | 100.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 40 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 152,965,540 | 4.8% | 4.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 119,595,300 | 3.8% | 8.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 104,478,780 | 3.3% | 11.9% |
| RESUME_CHECK LOAD_FAST | 98,542,560 | 3.1% | 15.0% |
| CACHE RESUME_CHECK | 85,438,260 | 2.7% | 17.7% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 84,002,100 | 2.7% | 20.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 66,073,680 | 2.1% | 22.5% |
| RETURN_VALUE INTERPRETER_EXIT | 62,483,160 | 2.0% | 24.4% |
| LOAD_CONST LOAD_FAST | 59,348,700 | 1.9% | 26.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 54,307,680 | 1.7% | 28.0% |
| STORE_FAST LOAD_FAST | 52,641,240 | 1.7% | 29.7% |
| LOAD_FAST STORE_ATTR_SLOT | 52,628,700 | 1.7% | 31.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 52,407,660 | 1.7% | 33.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 49,612,500 | 1.6% | 34.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 47,032,020 | 1.5% | 36.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 45,688,560 | 1.4% | 37.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 44,232,700 | 1.4% | 38.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 43,673,820 | 1.4% | 40.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 43,112,580 | 1.4% | 41.6% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 42,887,960 | 1.4% | 43.0% |
| LOAD_ATTR_SLOT LOAD_FAST | 42,887,700 | 1.4% | 44.3% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 42,887,620 | 1.4% | 45.7% |
| COMPARE_OP_FLOAT RETURN_VALUE | 42,887,580 | 1.4% | 47.0% |
| LOAD_ATTR_SLOT COMPARE_OP_FLOAT | 42,887,580 | 1.4% | 48.4% |
| RETURN_CONST POP_TOP | 40,315,440 | 1.3% | 49.7% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 38,631,240 | 1.2% | 50.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 32,475,520 | 1.0% | 51.9% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 31,912,620 | 1.0% | 52.9% |
| STORE_ATTR_SLOT LOAD_CONST | 31,353,060 | 1.0% | 53.9% |
| LOAD_FAST LOAD_ATTR | 30,235,020 | 1.0% | 54.9% |
| RETURN_CONST INTERPRETER_EXIT | 29,673,540 | 0.9% | 55.8% |
| POP_TOP LOAD_FAST | 29,116,080 | 0.9% | 56.7% |
| LOAD_FAST RETURN_VALUE | 29,115,300 | 0.9% | 57.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 29,114,940 | 0.9% | 58.6% |
| CALL STORE_FAST | 29,113,680 | 0.9% | 59.5% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 28,553,400 | 0.9% | 60.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 25,194,540 | 0.8% | 61.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 22,397,760 | 0.7% | 61.9% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 22,395,240 | 0.7% | 62.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 21,836,960 | 0.7% | 63.3% |
| POP_TOP RETURN_CONST | 21,835,740 | 0.7% | 64.0% |
| PUSH_NULL LOAD_FAST | 21,276,960 | 0.7% | 64.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 20,159,100 | 0.6% | 65.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 20,155,500 | 0.6% | 65.9% |
| RETURN_VALUE STORE_FAST | 19,597,380 | 0.6% | 66.5% |
| RETURN_VALUE TO_BOOL_BOOL | 19,036,160 | 0.6% | 67.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 19,035,900 | 0.6% | 67.7% |
| STORE_ATTR_SLOT LOAD_FAST | 18,476,100 | 0.6% | 68.3% |
| STORE_ATTR_SLOT RETURN_CONST | 18,475,980 | 0.6% | 68.9% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 18,475,860 | 0.6% | 69.5% |
| LOAD_CONST STORE_FAST | 16,802,940 | 0.5% | 70.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 16,799,620 | 0.5% | 70.6% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 16,796,340 | 0.5% | 71.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 16,236,540 | 0.5% | 71.6% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 16,236,420 | 0.5% | 72.1% |
| POP_TOP LOAD_CONST | 15,678,240 | 0.5% | 72.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 13,437,000 | 0.4% | 73.0% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 13,436,820 | 0.4% | 73.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 13,436,780 | 0.4% | 73.9% |
| PUSH_NULL CALL | 12,879,340 | 0.4% | 74.3% |
| STORE_FAST RETURN_CONST | 12,878,400 | 0.4% | 74.7% |
| LOAD_FAST CALL | 12,877,600 | 0.4% | 75.1% |
| CALL_FUNCTION_EX POP_TOP | 12,877,140 | 0.4% | 75.5% |
| LOAD_FAST_LOAD_FAST CALL | 12,877,080 | 0.4% | 75.9% |
| POP_TOP ENTER_EXECUTOR | 12,877,020 | 0.4% | 76.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 12,876,960 | 0.4% | 76.7% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 12,317,640 | 0.4% | 77.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 12,317,480 | 0.4% | 77.5% |
| POP_TOP RESUME_CHECK | 11,757,420 | 0.4% | 77.9% |
| GET_AWAITABLE LOAD_CONST | 11,757,420 | 0.4% | 78.2% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 11,757,420 | 0.4% | 78.6% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 11,198,940 | 0.4% | 79.0% |
| LOAD_FAST LOAD_CONST | 10,639,320 | 0.3% | 79.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 10,081,260 | 0.3% | 79.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 10,077,900 | 0.3% | 79.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 10,077,660 | 0.3% | 80.3% |
| ENTER_EXECUTOR CALL_FUNCTION_EX | 10,076,340 | 0.3% | 80.6% |
| NOP LOAD_FAST | 9,521,100 | 0.3% | 80.9% |
| COPY_FREE_VARS RESUME_CHECK | 9,518,400 | 0.3% | 81.2% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 8,959,540 | 0.3% | 81.5% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 8,959,440 | 0.3% | 81.7% |
| END_SEND POP_TOP | 8,958,060 | 0.3% | 82.0% |
| RETURN_GENERATOR GET_AWAITABLE | 8,398,200 | 0.3% | 82.3% |
| JUMP_BACKWARD_NO_INTERRUPT SEND_GEN | 8,398,200 | 0.3% | 82.6% |
| LOAD_CONST SEND_GEN | 8,398,200 | 0.3% | 82.8% |
| YIELD_VALUE YIELD_VALUE | 8,398,200 | 0.3% | 83.1% |
| SEND_GEN POP_TOP | 8,398,200 | 0.3% | 83.4% |
| SEND_GEN RESUME_CHECK | 8,398,200 | 0.3% | 83.6% |
| LOAD_CONST CALL_KW | 7,838,280 | 0.2% | 83.9% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 7,278,700 | 0.2% | 84.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 6,721,560 | 0.2% | 84.3% |
| LOAD_DEREF LOAD_FAST | 6,719,040 | 0.2% | 84.5% |
| LOAD_FAST POP_JUMP_IF_NONE | 6,718,740 | 0.2% | 84.7% |
| CALL POP_TOP | 6,718,680 | 0.2% | 84.9% |
| CACHE COPY_FREE_VARS | 6,718,440 | 0.2% | 85.2% |
| LOAD_DEREF LOAD_CONST | 6,718,440 | 0.2% | 85.4% |
| LOAD_CONST BINARY_OP_ADD_INT | 6,718,360 | 0.2% | 85.6% |
| LOAD_FAST CALL_LIST_APPEND | 6,718,320 | 0.2% | 85.8% |
| POP_JUMP_IF_NONE LOAD_DEREF | 6,718,320 | 0.2% | 86.0% |
| BINARY_OP_ADD_INT STORE_DEREF | 6,718,320 | 0.2% | 86.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 85,438,260 | 89.4% |
| COPY_FREE_VARS | 6,718,440 | 7.0% |
| POP_TOP | 3,359,220 | 3.5% |


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
| LOAD_GLOBAL_BUILTIN | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,598,840 | 47.6% |
| SEND | 3,359,220 | 28.6% |
| RETURN_VALUE | 2,799,360 | 23.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,958,060 | 76.2% |
| LOAD_FAST | 2,799,360 | 23.8% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,122,480 | 50.0% |
| CALL_BUILTIN_CLASS | 561,300 | 25.0% |
| LOAD_DEREF | 559,860 | 25.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,122,520 | 50.0% |
| LOAD_FAST_AND_CLEAR | 559,860 | 25.0% |
| FOR_ITER_TUPLE | 559,860 | 25.0% |
| FOR_ITER_RANGE | 1,380 | 0.1% |
| FOR_ITER | 140 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 62,483,160 | 65.4% |
| RETURN_CONST | 29,673,540 | 31.1% |
| YIELD_VALUE | 3,359,220 | 3.5% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 560,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 560,040 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,361,020 | 35.3% |
| STORE_FAST | 3,360,780 | 35.3% |
| POP_JUMP_IF_NOT_NONE | 2,799,420 | 29.4% |
| POP_TOP | 300 | 0.0% |
| JUMP_FORWARD | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,521,100 | 100.0% |
| LOAD_GLOBAL_MODULE | 320 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 60 | 50.0% |
| SWAP | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| RERAISE | 60 | 50.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 40,315,440 | 40.0% |
| CALL_METHOD_DESCRIPTOR_O | 16,796,340 | 16.7% |
| CALL_FUNCTION_EX | 12,877,140 | 12.8% |
| END_SEND | 8,958,060 | 8.9% |
| SEND_GEN | 8,398,200 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,116,080 | 28.9% |
| RETURN_CONST | 21,835,740 | 21.7% |
| LOAD_CONST | 15,678,240 | 15.6% |
| ENTER_EXECUTOR | 12,877,020 | 12.8% |
| RESUME_CHECK | 11,757,420 | 11.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 60 | 50.0% |
| BINARY_SUBSCR_DICT | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 44,232,700 | 82.3% |
| LOAD_ATTR | 5,600,180 | 10.4% |
| LOAD_FAST | 3,919,380 | 7.3% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,276,960 | 39.6% |
| LOAD_FAST_LOAD_FAST | 16,236,420 | 30.2% |
| CALL | 12,879,340 | 24.0% |
| LOAD_GLOBAL_MODULE | 2,799,360 | 5.2% |
| LOAD_GLOBAL_BUILTIN | 559,860 | 1.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 6,158,640 | 52.4% |
| CALL_PY_WITH_DEFAULTS | 2,799,360 | 23.8% |
| ENTER_EXECUTOR | 2,799,300 | 23.8% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 8,398,200 | 71.4% |
| LIST_APPEND | 3,359,160 | 28.6% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 42,887,580 | 38.8% |
| LOAD_FAST | 29,115,300 | 26.3% |
| LOAD_ATTR_INSTANCE_VALUE | 22,395,240 | 20.2% |
| CALL | 3,360,840 | 3.0% |
| RETURN_VALUE | 3,359,520 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 62,483,160 | 56.5% |
| STORE_FAST | 19,597,380 | 17.7% |
| TO_BOOL_BOOL | 19,036,160 | 17.2% |
| RETURN_VALUE | 3,359,520 | 3.0% |
| LOAD_FAST | 2,800,800 | 2.5% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,360,700 | 85.7% |
| LOAD_FAST | 559,920 | 14.3% |
| TO_BOOL | 1,000 | 0.0% |
| RETURN_VALUE | 160 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,359,220 | 85.7% |
| POP_JUMP_IF_TRUE | 561,240 | 14.3% |
| TO_BOOL | 1,000 | 0.0% |
| TO_BOOL_BOOL | 400 | 0.0% |
| TO_BOOL_INT | 120 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 60 | 50.0% |
| LOAD_ATTR_MODULE | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 120 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 60 | 50.0% |
| TO_BOOL_INT | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180 | 25.7% |
| BINARY_OP | 140 | 20.0% |
| LOAD_FAST | 140 | 20.0% |
| UNARY_INVERT | 120 | 17.1% |
| POP_JUMP_IF_FALSE | 60 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 140 | 20.0% |
| COPY | 120 | 17.1% |
| STORE_FAST | 120 | 17.1% |
| LOAD_GLOBAL_MODULE | 120 | 17.1% |
| UNARY_INVERT | 60 | 8.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,800,680 | 35.7% |
| LOAD_FAST | 2,799,360 | 35.7% |
| STORE_FAST | 561,240 | 7.2% |
| POP_JUMP_IF_FALSE | 559,860 | 7.1% |
| STORE_DEREF | 559,860 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,600,220 | 71.4% |
| STORE_FAST | 1,121,100 | 14.3% |
| STORE_DEREF | 559,860 | 7.1% |
| SWAP | 559,860 | 7.1% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,799,360 | 83.3% |
| STORE_FAST | 559,860 | 16.7% |
| POP_TOP | 60 | 0.0% |
| BUILD_TUPLE | 60 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 2,799,360 | 83.3% |
| STORE_FAST | 559,860 | 16.7% |
| LOAD_FAST | 240 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,040 | 99.9% |
| CALL | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 560,040 | 99.9% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |
| BUILD_MAP | 60 | 0.0% |
| CALL_ISINSTANCE | 40 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 12,879,340 | 26.4% |
| LOAD_FAST | 12,877,600 | 26.4% |
| LOAD_FAST_LOAD_FAST | 12,877,080 | 26.4% |
| LOAD_ATTR | 3,919,400 | 8.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,359,260 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,113,680 | 59.7% |
| POP_TOP | 6,718,680 | 13.8% |
| RESUME_CHECK | 6,158,700 | 12.6% |
| RETURN_VALUE | 3,360,840 | 6.9% |
| CALL_METHOD_DESCRIPTOR_O | 3,359,260 | 6.9% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 10,076,340 | 62.1% |
| CALL_INTRINSIC_1 | 2,800,680 | 17.2% |
| BUILD_MAP | 2,799,360 | 17.2% |
| STORE_FAST | 559,860 | 3.4% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,877,140 | 79.3% |
| STORE_FAST | 2,799,360 | 17.2% |
| MAKE_CELL | 559,860 | 3.4% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 5,600,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 2,800,680 | 50.0% |
| LOAD_CONST | 2,799,360 | 50.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,838,280 | 73.7% |
| ENTER_EXECUTOR | 2,799,300 | 26.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,359,220 | 31.6% |
| RESUME_CHECK | 3,359,220 | 31.6% |
| RETURN_VALUE | 2,799,360 | 26.3% |
| POP_TOP | 559,920 | 5.3% |
| STORE_DEREF | 559,860 | 5.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,799,380 | 100.0% |
| COMPARE_OP | 700 | 0.0% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,799,480 | 100.0% |
| COMPARE_OP | 700 | 0.0% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,359,220 | 85.7% |
| LOAD_FAST_LOAD_FAST | 559,860 | 14.3% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,919,140 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 3,359,280 | 99.9% |
| CALL_LEN | 1,380 | 0.0% |
| BINARY_OP | 120 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| UNARY_NOT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,359,360 | 99.9% |
| TO_BOOL_INT | 1,460 | 0.0% |
| TO_BOOL | 80 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| POP_EXCEPT | 60 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 6,718,440 | 70.6% |
| CALL_PY_EXACT_ARGS | 2,799,960 | 29.4% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,518,400 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,877,020 | 56.1% |
| CALL_LIST_APPEND | 6,718,320 | 29.3% |
| LIST_APPEND | 3,359,160 | 14.6% |
| POP_JUMP_IF_FALSE | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 10,076,340 | 43.9% |
| RETURN_GENERATOR | 2,799,300 | 12.2% |
| CALL | 2,799,300 | 12.2% |
| CALL_KW | 2,799,300 | 12.2% |
| LOAD_ATTR_SLOT | 2,799,300 | 12.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 140 | 77.8% |
| FOR_ITER | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 33.3% |
| RETURN_CONST | 60 | 33.3% |
| FOR_ITER | 40 | 22.2% |
| FOR_ITER_LIST | 20 | 11.1% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 8,398,200 | 71.4% |
| LOAD_FAST | 2,799,360 | 23.8% |
| RETURN_VALUE | 559,860 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 11,757,420 | 100.0% |


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
| LOAD_FAST_LOAD_FAST | 3,359,160 | 100.0% |
| LOAD_CONST | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,359,160 | 100.0% |
| RETURN_VALUE | 300 | 0.0% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,757,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 8,398,200 | 71.4% |
| SEND | 3,359,220 | 28.6% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,359,220 | 99.9% |
| STORE_FAST | 3,000 | 0.1% |
| ENTER_EXECUTOR | 60 | 0.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 3,359,160 | 99.9% |
| LOAD_FAST | 1,680 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,440 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 3,359,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,359,160 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 2,800,680 | 50.0% |
| LOAD_FAST | 2,799,360 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 5,600,040 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,235,020 | 91.5% |
| LOAD_ATTR_SLOT | 2,800,740 | 8.5% |
| LOAD_ATTR | 8,540 | 0.0% |
| LOAD_GLOBAL_MODULE | 580 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 13,436,820 | 40.7% |
| LOAD_FAST | 6,158,820 | 18.6% |
| PUSH_NULL | 5,600,180 | 16.9% |
| CALL | 3,919,400 | 11.9% |
| TO_BOOL_NONE | 3,359,220 | 10.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 31,353,060 | 27.3% |
| POP_JUMP_IF_FALSE | 22,397,760 | 19.5% |
| POP_TOP | 15,678,240 | 13.7% |
| GET_AWAITABLE | 11,757,420 | 10.2% |
| LOAD_FAST | 10,639,320 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,348,700 | 51.7% |
| STORE_FAST | 16,802,940 | 14.6% |
| SEND_GEN | 8,398,200 | 7.3% |
| CALL_KW | 7,838,280 | 6.8% |
| BINARY_OP_ADD_INT | 6,718,360 | 5.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,718,320 | 18.7% |
| LOAD_GLOBAL_BUILTIN | 6,159,180 | 17.2% |
| POP_JUMP_IF_FALSE | 3,919,020 | 10.9% |
| RESUME_CHECK | 3,359,220 | 9.4% |
| JUMP_FORWARD | 3,359,160 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,719,040 | 18.8% |
| LOAD_CONST | 6,718,440 | 18.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,919,020 | 10.9% |
| LOAD_DEREF | 3,359,160 | 9.4% |
| POP_JUMP_IF_NONE | 3,359,160 | 9.4% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 104,478,780 | 17.7% |
| RESUME_CHECK | 98,542,560 | 16.7% |
| LOAD_CONST | 59,348,700 | 10.0% |
| STORE_FAST | 52,641,240 | 8.9% |
| LOAD_GLOBAL_BUILTIN | 49,612,500 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 152,965,540 | 25.9% |
| LOAD_ATTR_INSTANCE_VALUE | 84,002,100 | 14.2% |
| STORE_ATTR_SLOT | 52,628,700 | 8.9% |
| LOAD_GLOBAL_MODULE | 45,688,560 | 7.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 43,673,820 | 7.4% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 559,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 559,860 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 38,631,240 | 33.0% |
| LOAD_FAST_LOAD_FAST | 19,035,900 | 16.3% |
| PUSH_NULL | 16,236,420 | 13.9% |
| POP_JUMP_IF_NOT_NONE | 12,876,960 | 11.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,077,660 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 54,307,680 | 46.4% |
| LOAD_FAST_LOAD_FAST | 19,035,900 | 16.3% |
| LOAD_FAST | 16,236,540 | 13.9% |
| CALL | 12,877,080 | 11.0% |
| LOAD_CONST | 3,919,140 | 3.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 220 | 18.0% |
| RESUME_CHECK | 220 | 18.0% |
| LOAD_FAST | 140 | 11.5% |
| STORE_FAST | 120 | 9.8% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 880 | 72.1% |
| LOAD_GLOBAL_BUILTIN | 320 | 26.2% |
| LOAD_ATTR | 20 | 1.6% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 160 | 100.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,239,440 | 80.0% |
| CALL_FUNCTION_EX | 559,860 | 20.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,239,440 | 80.0% |
| RESUME_CHECK | 559,920 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 119,595,300 | 68.3% |
| TO_BOOL_NONE | 31,912,620 | 18.2% |
| COMPARE_OP_INT | 6,721,560 | 3.8% |
| CONTAINS_OP | 3,919,140 | 2.2% |
| TO_BOOL_LIST | 3,362,220 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 104,478,780 | 59.7% |
| RETURN_CONST | 25,194,540 | 14.4% |
| LOAD_CONST | 22,397,760 | 12.8% |
| LOAD_GLOBAL_MODULE | 12,317,480 | 7.0% |
| LOAD_DEREF | 3,919,020 | 2.2% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,718,740 | 66.7% |
| LOAD_DEREF | 3,359,160 | 33.3% |
| LOAD_ATTR_INSTANCE_VALUE | 180 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 6,718,320 | 66.7% |
| LOAD_FAST | 3,359,340 | 33.3% |
| RETURN_CONST | 360 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,114,940 | 89.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,359,220 | 10.3% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 12,876,960 | 39.7% |
| LOAD_FAST | 8,959,440 | 27.6% |
| LOAD_GLOBAL_MODULE | 7,278,700 | 22.4% |
| NOP | 2,799,420 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 559,860 | 1.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 12,317,640 | 95.6% |
| TO_BOOL | 561,240 | 4.4% |
| TO_BOOL_INT | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,077,900 | 78.2% |
| LOAD_CONST | 2,800,740 | 21.7% |
| STORE_FAST | 1,380 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| POP_TOP | 60 | 0.0% |


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
| POP_JUMP_IF_FALSE | 25,194,540 | 31.9% |
| POP_TOP | 21,835,740 | 27.7% |
| STORE_ATTR_SLOT | 18,475,980 | 23.4% |
| STORE_FAST | 12,878,400 | 16.3% |
| STORE_ATTR_INSTANCE_VALUE | 560,460 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 40,315,440 | 51.1% |
| INTERPRETER_EXIT | 29,673,540 | 37.6% |
| END_SEND | 5,598,840 | 7.1% |
| TO_BOOL_BOOL | 3,359,220 | 4.3% |
| EXIT_INIT_CHECK | 120 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 3,359,220 | 50.0% |
| LOAD_CONST | 3,359,220 | 50.0% |
| SEND | 1,660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 3,359,220 | 50.0% |
| YIELD_VALUE | 3,359,220 | 50.0% |
| SEND | 1,660 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 560,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 560,040 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,920 | 85.7% |
| LOAD_FAST_LOAD_FAST | 559,920 | 14.3% |
| STORE_ATTR | 1,020 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 0.0% |
| SWAP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 3,359,160 | 85.7% |
| LOAD_CONST | 559,860 | 14.3% |
| STORE_ATTR | 1,020 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 800 | 0.0% |
| LOAD_FAST | 180 | 0.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 6,718,320 | 70.6% |
| LOAD_CONST | 1,679,580 | 17.6% |
| BUILD_LIST | 559,860 | 5.9% |
| CALL_KW | 559,860 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 3,359,160 | 35.3% |
| LOAD_FAST_LOAD_FAST | 3,359,160 | 35.3% |
| LOAD_CONST | 1,119,720 | 11.8% |
| LOAD_FAST | 1,119,720 | 11.8% |
| BUILD_LIST | 559,860 | 5.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 29,113,680 | 36.6% |
| RETURN_VALUE | 19,597,380 | 24.6% |
| LOAD_CONST | 16,802,940 | 21.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,360,540 | 4.2% |
| CALL_KW | 3,359,220 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,641,240 | 66.2% |
| RETURN_CONST | 12,878,400 | 16.2% |
| LOAD_FAST_LOAD_FAST | 3,919,320 | 4.9% |
| NOP | 3,360,780 | 4.2% |
| LOAD_GLOBAL_MODULE | 3,359,380 | 4.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 559,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 559,860 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 33.3% |
| LOAD_GLOBAL | 20 | 16.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 559,860 | 33.3% |
| ENTER_EXECUTOR | 559,860 | 33.3% |
| LOAD_FAST_AND_CLEAR | 559,860 | 33.3% |
| LOAD_ATTR | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,920 | 33.3% |
| BUILD_LIST | 559,860 | 33.3% |
| FOR_ITER_RANGE | 559,860 | 33.3% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| POP_EXCEPT | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20 | 33.3% |
| CALL | 20 | 33.3% |
| STORE_FAST | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 100.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 8,398,200 | 71.4% |
| SEND | 3,359,220 | 28.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 8,398,200 | 71.4% |
| INTERPRETER_EXIT | 3,359,220 | 28.6% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,799,360 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,799,360 | 100.0% |
| STORE_FAST | 1,380 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,718,360 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 6,718,320 | 100.0% |
| SWAP | 60 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 33.3% |
| BINARY_OP | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 559,900 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 559,860 | 100.0% |
| SWAP | 60 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| LOAD_FAST | 40 | 33.3% |
| BINARY_SUBSCR | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 60 | 50.0% |
| RETURN_VALUE | 60 | 50.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280 | 93.3% |
| BINARY_SUBSCR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 160 | 53.3% |
| STORE_FAST | 120 | 40.0% |
| LOAD_ATTR | 20 | 6.7% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 40 | 33.3% |
| CALL | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 50.0% |
| RESUME_CHECK | 60 | 50.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 60 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 559,860 | 99.6% |
| LOAD_FAST | 1,560 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 561,300 | 99.9% |
| LOAD_FAST | 180 | 0.0% |
| COMPARE_OP | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,359,340 | 54.5% |
| LOAD_FAST | 2,799,360 | 45.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 3,359,280 | 54.5% |
| POP_TOP | 2,799,360 | 45.5% |
| TO_BOOL_BOOL | 60 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,799,400 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| CALL | 40 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,799,360 | 100.0% |
| POP_TOP | 120 | 0.0% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 42,887,620 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| BUILD_TUPLE | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 42,887,960 | 100.0% |
| TO_BOOL | 40 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,760 | 66.7% |
| COPY | 1,380 | 33.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,718,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,718,320 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 120 | 66.7% |
| RETURN_VALUE | 40 | 22.2% |
| CALL | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 66.7% |
| STORE_FAST | 60 | 33.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,380 | 88.5% |
| LOAD_CONST | 60 | 3.8% |
| CALL | 40 | 2.6% |
| LOAD_ATTR | 40 | 2.6% |
| LOAD_FAST | 40 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,380 | 88.5% |
| POP_TOP | 120 | 7.7% |
| RETURN_VALUE | 60 | 3.8% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 13,436,820 | 79.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,359,160 | 19.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,600 | 0.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,820 | 0.0% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 13,436,780 | 79.7% |
| STORE_FAST | 3,360,540 | 19.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,600 | 0.4% |
| POP_TOP | 360 | 0.0% |
| CALL | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,437,000 | 80.0% |
| CALL | 3,359,260 | 20.0% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 16,796,340 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 43,112,580 | 57.5% |
| LOAD_FAST | 20,159,100 | 26.9% |
| LOAD_ATTR_METHOD_NO_DICT | 5,600,160 | 7.5% |
| LOAD_SUPER_ATTR_METHOD | 2,799,560 | 3.7% |
| LOAD_FAST_LOAD_FAST | 2,799,360 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 66,073,680 | 88.1% |
| RETURN_GENERATOR | 6,158,640 | 8.2% |
| COPY_FREE_VARS | 2,799,960 | 3.7% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,799,360 | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% |
| CALL | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| PUSH_NULL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 2,799,360 | 100.0% |
| RESUME_CHECK | 360 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,359,220 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 42,887,580 | 100.0% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 42,887,580 | 100.0% |
| POP_JUMP_IF_FALSE | 240 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,361,000 | 50.0% |
| LOAD_DEREF | 3,359,160 | 50.0% |
| LOAD_GLOBAL_MODULE | 1,380 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,721,560 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,122,520 | 100.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 559,860 | 49.9% |
| STORE_FAST | 559,860 | 49.9% |
| RETURN_CONST | 1,440 | 0.1% |
| LOAD_FAST | 1,380 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 559,860 | 99.8% |
| GET_ITER | 1,380 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 559,860 | 99.8% |
| STORE_FAST | 1,380 | 0.2% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 559,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 100.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,002,100 | 95.5% |
| LOAD_FAST_LOAD_FAST | 3,359,380 | 3.8% |
| LOAD_DEREF | 559,860 | 0.6% |
| LOAD_ATTR | 660 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 32,475,520 | 36.9% |
| RETURN_VALUE | 22,395,240 | 25.5% |
| LOAD_ATTR_METHOD_NO_DICT | 16,799,620 | 19.1% |
| TO_BOOL_LIST | 3,362,200 | 3.8% |
| TO_BOOL | 3,360,700 | 3.8% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,799,620 | 57.7% |
| LOAD_FAST | 8,959,540 | 30.8% |
| LOAD_DEREF | 3,359,160 | 11.5% |
| LOAD_ATTR | 320 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,155,500 | 69.2% |
| CALL_PY_EXACT_ARGS | 5,600,160 | 19.2% |
| LOAD_GLOBAL_MODULE | 3,359,220 | 11.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,820 | 0.0% |
| LOAD_FAST_LOAD_FAST | 1,500 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,673,820 | 65.5% |
| LOAD_ATTR_SLOT | 18,475,860 | 27.7% |
| LOAD_DEREF | 3,919,020 | 5.9% |
| STORE_FAST_LOAD_FAST | 559,860 | 0.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 43,112,580 | 64.7% |
| LOAD_FAST | 10,081,260 | 15.1% |
| LOAD_FAST_LOAD_FAST | 10,077,660 | 15.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,359,160 | 5.0% |
| CALL | 420 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 47,032,020 | 100.0% |
| LOAD_ATTR | 580 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 44,232,700 | 94.0% |
| LOAD_FAST_LOAD_FAST | 2,799,360 | 6.0% |
| LOAD_ATTR | 260 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| UNARY_INVERT | 60 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| LOAD_ATTR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 152,965,540 | 98.2% |
| ENTER_EXECUTOR | 2,799,300 | 1.8% |
| LOAD_ATTR_SLOT | 280 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 160 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,887,700 | 27.5% |
| COMPARE_OP_FLOAT | 42,887,580 | 27.5% |
| TO_BOOL_NONE | 28,553,400 | 18.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 18,475,860 | 11.9% |
| TO_BOOL_BOOL | 11,198,940 | 7.2% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 52,407,660 | 93.0% |
| POP_TOP | 2,799,540 | 5.0% |
| PUSH_NULL | 559,860 | 1.0% |
| POP_JUMP_IF_NOT_NONE | 559,860 | 1.0% |
| STORE_FAST | 1,460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,612,500 | 88.1% |
| LOAD_DEREF | 6,159,180 | 10.9% |
| LOAD_GLOBAL_MODULE | 559,900 | 1.0% |
| CALL_ISINSTANCE | 300 | 0.0% |
| CALL_BUILTIN_CLASS | 180 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,688,560 | 45.2% |
| RESUME_CHECK | 21,836,960 | 21.6% |
| POP_JUMP_IF_FALSE | 12,317,480 | 12.2% |
| POP_JUMP_IF_NOT_NONE | 7,278,700 | 7.2% |
| STORE_FAST | 3,359,380 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 47,032,020 | 46.5% |
| CALL_ISINSTANCE | 42,887,620 | 42.4% |
| LOAD_FAST_LOAD_FAST | 3,919,320 | 3.9% |
| CONTAINS_OP | 3,359,220 | 3.3% |
| CALL_PY_WITH_DEFAULTS | 2,799,360 | 2.8% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,159,020 | 100.0% |
| LOAD_SUPER_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,799,560 | 45.5% |
| LOAD_FAST_LOAD_FAST | 2,799,420 | 45.5% |
| LOAD_FAST | 560,100 | 9.1% |
| CALL | 100 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 85,438,260 | 44.7% |
| CALL_PY_EXACT_ARGS | 66,073,680 | 34.5% |
| POP_TOP | 11,757,420 | 6.1% |
| COPY_FREE_VARS | 9,518,400 | 5.0% |
| SEND_GEN | 8,398,200 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,542,560 | 51.5% |
| LOAD_GLOBAL_BUILTIN | 52,407,660 | 27.4% |
| LOAD_GLOBAL_MODULE | 21,836,960 | 11.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 11,757,420 | 6.1% |
| NOP | 3,361,020 | 1.8% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 8,398,200 | 50.0% |
| LOAD_CONST | 8,398,200 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,398,200 | 50.0% |
| RESUME_CHECK | 8,398,200 | 50.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 561,620 | 99.8% |
| STORE_ATTR | 800 | 0.1% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |
| SWAP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 560,460 | 99.6% |
| LOAD_CONST | 780 | 0.1% |
| LOAD_FAST | 720 | 0.1% |
| LOAD_GLOBAL_MODULE | 300 | 0.1% |
| BUILD_LIST | 180 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 54,307,680 | 50.8% |
| LOAD_FAST | 52,628,700 | 49.2% |
| STORE_ATTR_SLOT | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 38,631,240 | 36.1% |
| LOAD_CONST | 31,353,060 | 29.3% |
| LOAD_FAST | 18,476,100 | 17.3% |
| RETURN_CONST | 18,475,980 | 17.3% |
| STORE_ATTR_SLOT | 840 | 0.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,160 | 100.0% |
| LOAD_ATTR | 40 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,359,220 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 42,887,960 | 32.5% |
| LOAD_ATTR_INSTANCE_VALUE | 32,475,520 | 24.6% |
| RETURN_VALUE | 19,036,160 | 14.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 13,436,780 | 10.2% |
| LOAD_ATTR_SLOT | 11,198,940 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 119,595,300 | 90.7% |
| POP_JUMP_IF_TRUE | 12,317,640 | 9.3% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,460 | 83.9% |
| TO_BOOL | 120 | 6.9% |
| LOAD_FAST | 80 | 4.6% |
| BINARY_OP | 40 | 2.3% |
| LOAD_ATTR | 40 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,440 | 82.8% |
| POP_JUMP_IF_FALSE | 240 | 13.8% |
| UNARY_NOT | 60 | 3.4% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,362,200 | 100.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,362,220 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 28,553,400 | 89.5% |
| LOAD_ATTR | 3,359,220 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 31,912,620 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE | 60 | 33.3% |
| RETURN_VALUE | 40 | 22.2% |
| CALL | 40 | 22.2% |
| STORE_FAST | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 120 | 66.7% |
| LOAD_FAST | 60 | 33.3% |


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
|     deferred | 480 | 0.0% |
|          hit | 10,079,160 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 36.4% |
| Failure | 140 | 63.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 80 | 57.1% |
| or | 40 | 28.6% |
| true divide other | 20 | 14.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 480 | 92.3% |

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
|     deferred | 48,712,020 | 21.9% |
|        deopt | 64,600 | 0.0% |
|          hit | 170,558,760 | 76.6% |
|         miss | 3,424,120 | 1.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 66,200 | 84.2% |
| Failure | 12,440 | 15.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 3,340 | 26.8% |
| no dict | 3,160 | 25.4% |
| cfunc noargs | 2,320 | 18.6% |
| code complex parameters | 1,540 | 12.4% |
| class no vectorcall | 860 | 6.9% |
| other | 820 | 6.6% |
| cmethod | 140 | 1.1% |
| class mutable | 80 | 0.6% |
| cfunc varargs keywords | 60 | 0.5% |
| wrong number arguments | 40 | 0.3% |
| cfunc varargs | 40 | 0.3% |
| operator wrapper | 20 | 0.2% |
| init not simple | 20 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,799,480 | 5.3% |
|          hit | 49,609,380 | 94.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 2.8% |
| Failure | 700 | 97.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 680 | 97.1% |
| bool | 20 | 2.9% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120 | 0.0% |
|          hit | 2,243,640 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 33.3% |
| Failure | 40 | 66.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 40 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 33,034,940 | 7.9% |
|        deopt | 320 | 0.0% |
|          hit | 386,453,480 | 92.1% |
|         miss | 17,080 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,660 | 23.8% |
| Failure | 8,540 | 76.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 5,860 | 68.6% |
| method | 1,600 | 18.7% |
| class attr descriptor | 820 | 9.6% |
| not managed dict | 140 | 1.6% |
| non object slot | 40 | 0.5% |
| metaclass attribute | 40 | 0.5% |
| class attr simple | 40 | 0.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 157,453,360 | 100.0% |
|         miss | 60 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 6,159,180 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
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
|     deferred | 6,718,440 | 28.6% |
|          hit | 16,796,400 | 71.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 1,660 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 1,660 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,919,320 | 3.5% |
|        deopt | 840 | 0.0% |
|          hit | 107,455,260 | 96.4% |
|         miss | 44,700 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,640 | 61.7% |
| Failure | 1,020 | 38.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overriding descriptor | 840 | 82.4% |
| no dict | 140 | 13.7% |
| overridden | 40 | 3.9% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 3,359,220 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,920,460 | 2.3% |
|          hit | 167,189,580 | 97.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 540 | 35.1% |
| Failure | 1,000 | 64.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 820 | 82.0% |
| tuple | 140 | 14.0% |
| sequence | 40 | 4.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 180 | 75.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,564,989,420 | 49.4% |
| Not specialized | 333,153,359 | 10.5% |
| Specialized | 1,268,556,141 | 40.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,190,964,841 | 100.0% |
| CALL | 48,712,020 | 0.0% |
| LOAD_ATTR | 33,034,940 | 0.0% |
| SEND | 6,718,440 | 0.0% |
| TO_BOOL | 3,920,460 | 0.0% |
| STORE_ATTR | 3,919,320 | 0.0% |
| COMPARE_OP | 2,799,480 | 0.0% |
| BINARY_OP | 480 | 0.0% |
| FOR_ITER | 120 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,424,000 | 94.6% |
| RESUME | 67,479 | 1.9% |
| RESUME_CHECK | 67,479 | 1.9% |
| STORE_ATTR_SLOT | 44,700 | 1.2% |
| LOAD_ATTR_SLOT | 14,960 | 0.4% |
| LOAD_ATTR_METHOD_NO_DICT | 2,120 | 0.1% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |
| CACHE | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 95,515,920 | 47.7% |
| Calls to Python functions inlined | 104,706,480 | 52.3% |
| Calls via PyEval_EvalFrame (total) | 95,515,920 | 47.7% |
| Calls via PyEval_EvalFrame (vector) | 88,797,480 | 44.3% |
| Calls via PyEval_EvalFrame (generator) | 6,718,440 | 3.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 88,797,480 | 44.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 42,887,580 | 21.4% |
| Calls via PyEval_EvalFrame (function ex) | 559,920 | 0.3% |
| Calls via PyEval_EvalFrame (api) | 3,359,280 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 20,155,320 | 10.1% |
| Frame objects created | 120 | 0.0% |
| Frames pushed | 189,584,640 | 94.7% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 85,782,010 | 39.1% |
| Frees to freelist | 86,161,210 |  |
| Allocations | 133,389,487 | 60.9% |
| Allocations to 512 bytes | 133,302,902 | 60.8% |
| Allocations to 4 kbytes | 86,580 | 0.0% |
| Allocations over 4 kbytes | 5 | 0.0% |
| Frees | 135,065,797 |  |
| New values | 180 |  |
| Interpreter increfs | 1,789,799,380 | 69.8% |
| Interpreter decrefs | 1,873,834,980 | 68.1% |
| Increfs | 775,794,418 | 30.2% |
| Decrefs | 875,918,013 | 31.9% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 81,137,962 |  |
| Method cache misses | 1,238,218 |  |
| Method cache collisions | 1,251,899 |  |
| Method cache dunder hits | 56,310,836 |  |
| Method cache dunder misses | 14,804 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 69,681 | 0 | 480,941,956 |
| 1 | 6,320 | 0 | 530,083,282 |
| 2 | 500 | 0 | 1,733,529,998 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 22,955,940 |  |
| Uops executed | 1,110,152,100 | 48.36 |
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
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,680,960 | 7.3% |
| <= 16 | 1,320 | 0.0% |
| <= 32 | 11,197,200 | 48.8% |
| <= 64 | 0 | 0.0% |
| <= 128 | 10,076,340 | 43.9% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 0 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 0 | 0.0% |
| <= 65,536 | 0 | 0.0% |
| <= 131,072 | 0 | 0.0% |
| <= 262,144 | 0 | 0.0% |
| <= 524,288 | 60 | 0.0% |
| <= 1,048,576 | 0 | 0.0% |
| <= 2,097,152 | 0 | 0.0% |
| <= 4,194,304 | 60 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 305,668,200 | 27.5% | 27.5% |  |
| LOAD_FAST | 120,922,800 | 10.9% | 38.4% |  |
| _GUARD_TYPE_VERSION | 111,404,040 | 10.0% | 48.5% | 2.5% |
| _POP_JUMP_IF_TRUE | 48,705,780 | 4.4% | 52.8% |  |
| _LOAD_ATTR_SLOT | 43,104,660 | 3.9% | 56.7% |  |
| STORE_FAST | 39,747,720 | 3.6% | 60.3% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 34,149,000 | 3.1% | 63.4% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 34,149,000 | 3.1% | 66.5% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 25,751,220 | 2.3% | 68.8% |  |
| TO_BOOL_BOOL | 22,951,980 | 2.1% | 70.9% |  |
| _EXIT_TRACE | 20,156,640 | 1.8% | 72.7% |  |
| _ITER_CHECK_RANGE | 16,236,180 | 1.5% | 74.1% |  |
| _IS_ITER_EXHAUSTED_RANGE | 16,236,180 | 1.5% | 75.6% |  |
| LOAD_ATTR | 15,674,940 | 1.4% | 77.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 15,674,940 | 1.4% | 78.4% |  |
| _ITER_NEXT_RANGE | 15,674,940 | 1.4% | 79.8% |  |
| _CHECK_PEP_523 | 12,876,960 | 1.2% | 81.0% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 12,876,960 | 1.2% | 82.1% |  |
| _CHECK_STACK_SPACE | 12,876,960 | 1.2% | 83.3% |  |
| _INIT_CALL_PY_EXACT_ARGS | 12,876,960 | 1.2% | 84.5% |  |
| _PUSH_FRAME | 12,876,960 | 1.2% | 85.6% |  |
| _SAVE_CURRENT_IP | 12,876,960 | 1.2% | 86.8% |  |
| PUSH_NULL | 12,875,580 | 1.2% | 87.9% |  |
| LOAD_CONST | 11,197,140 | 1.0% | 89.0% |  |
| BUILD_LIST | 10,076,340 | 0.9% | 89.9% |  |
| CALL_INTRINSIC_1 | 10,076,340 | 0.9% | 90.8% |  |
| LIST_EXTEND | 10,076,340 | 0.9% | 91.7% |  |
| RESUME_CHECK | 10,076,340 | 0.9% | 92.6% |  |
| _GUARD_GLOBALS_VERSION | 5,598,540 | 0.5% | 93.1% |  |
| _LOAD_GLOBAL_MODULE | 5,598,540 | 0.5% | 93.6% |  |
| _POP_JUMP_IF_FALSE | 5,598,540 | 0.5% | 94.1% |  |
| POP_TOP | 4,480,200 | 0.4% | 94.5% |  |
| _ITER_CHECK_LIST | 3,359,160 | 0.3% | 94.8% |  |
| _IS_ITER_EXHAUSTED_LIST | 3,359,160 | 0.3% | 95.1% |  |
| _ITER_CHECK_TUPLE | 3,359,160 | 0.3% | 95.4% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 3,359,160 | 0.3% | 95.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 2,800,620 | 0.3% | 96.0% |  |
| _GUARD_KEYS_VERSION | 2,800,620 | 0.3% | 96.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 2,800,620 | 0.3% | 96.5% |  |
| CONTAINS_OP | 2,799,300 | 0.3% | 96.7% |  |
| BINARY_SUBSCR_LIST_INT | 2,799,300 | 0.3% | 97.0% |  |
| COMPARE_OP_FLOAT | 2,799,300 | 0.3% | 97.2% |  |
| _GUARD_BOTH_INT | 2,799,300 | 0.3% | 97.5% |  |
| _BINARY_OP_SUBTRACT_INT | 2,799,300 | 0.3% | 97.7% |  |
| _ITER_NEXT_LIST | 2,799,300 | 0.3% | 98.0% |  |
| _ITER_NEXT_TUPLE | 2,799,300 | 0.3% | 98.2% |  |
| CALL_BUILTIN_O | 2,799,240 | 0.3% | 98.5% |  |
| CALL_METHOD_DESCRIPTOR_O | 2,799,240 | 0.3% | 98.7% |  |
| TO_BOOL_LIST | 2,799,240 | 0.3% | 99.0% |  |
| _CHECK_ATTR_MODULE | 2,799,240 | 0.3% | 99.2% |  |
| _LOAD_ATTR_MODULE | 2,799,240 | 0.3% | 99.5% |  |
| _STORE_ATTR_SLOT | 2,799,240 | 0.3% | 99.7% |  |
| _JUMP_TO_TOP | 2,799,180 | 0.3% | 100.0% |  |


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
