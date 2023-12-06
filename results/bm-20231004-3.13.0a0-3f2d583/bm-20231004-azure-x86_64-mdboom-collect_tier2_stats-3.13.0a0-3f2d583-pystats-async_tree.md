
# Pystats results

- benchmark: async_tree
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 255,911,400 | 17.9% | 17.9% |  |
| POP_JUMP_IF_FALSE | 81,751,500 | 5.7% | 23.7% |  |
| RESUME_CHECK | 75,593,760 | 5.3% | 29.0% | 0.0% |
| LOAD_FAST_LOAD_FAST | 69,426,780 | 4.9% | 33.8% |  |
| LOAD_CONST | 61,597,080 | 4.3% | 38.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 57,126,060 | 4.0% | 42.1% |  |
| POP_TOP | 53,193,840 | 3.7% | 45.9% |  |
| STORE_FAST | 51,528,000 | 3.6% | 49.5% |  |
| STORE_ATTR_SLOT | 50,949,060 | 3.6% | 53.1% |  |
| TO_BOOL_BOOL | 49,833,780 | 3.5% | 56.6% |  |
| RETURN_CONST | 45,354,480 | 3.2% | 59.7% |  |
| RETURN_VALUE | 36,956,460 | 2.6% | 62.3% |  |
| CALL_PY_EXACT_ARGS | 35,840,520 | 2.5% | 64.8% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 35,837,820 | 2.5% | 67.3% |  |
| INTERPRETER_EXIT | 33,032,820 | 2.3% | 69.7% |  |
| LOAD_DEREF | 30,233,340 | 2.1% | 71.8% |  |
| CALL | 29,125,440 | 2.0% | 73.8% |  |
| LOAD_GLOBAL_MODULE | 27,439,720 | 1.9% | 75.7% |  |
| LOAD_ATTR_SLOT | 25,199,340 | 1.8% | 77.5% |  |
| PUSH_NULL | 22,958,880 | 1.6% | 79.1% |  |
| LOAD_ATTR | 21,845,540 | 1.5% | 80.6% |  |
| POP_JUMP_IF_NOT_NONE | 21,276,780 | 1.5% | 82.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 20,720,040 | 1.5% | 83.6% |  |
| LOAD_ATTR_MODULE | 19,038,760 | 1.3% | 84.9% |  |
| TO_BOOL_NONE | 17,915,820 | 1.3% | 86.2% |  |
| ENTER_EXECUTOR | 17,356,920 | 1.2% | 87.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 14,063,200 | 1.0% | 88.4% | 24.3% |
| CALL_METHOD_DESCRIPTOR_O | 13,996,860 | 1.0% | 89.4% | 0.0% |
| POP_JUMP_IF_NONE | 10,078,200 | 0.7% | 90.1% |  |
| STORE_DEREF | 9,517,620 | 0.7% | 90.7% |  |
| LOAD_GLOBAL_BUILTIN | 7,845,300 | 0.5% | 91.3% | 0.0% |
| CALL_FUNCTION_EX | 7,838,340 | 0.5% | 91.8% |  |
| CALL_KW | 7,838,220 | 0.5% | 92.4% |  |
| POP_JUMP_IF_TRUE | 7,281,240 | 0.5% | 92.9% |  |
| COMPARE_OP_INT | 6,721,200 | 0.5% | 93.4% |  |
| BINARY_OP_ADD_INT | 6,718,380 | 0.5% | 93.8% |  |
| CALL_LIST_APPEND | 6,718,320 | 0.5% | 94.3% |  |
| RETURN_GENERATOR | 6,158,700 | 0.4% | 94.7% |  |
| NOP | 3,922,620 | 0.3% | 95.0% |  |
| TO_BOOL | 3,921,820 | 0.3% | 95.3% |  |
| STORE_ATTR | 3,921,200 | 0.3% | 95.6% |  |
| COPY_FREE_VARS | 3,919,800 | 0.3% | 95.8% |  |
| CONTAINS_OP | 3,919,140 | 0.3% | 96.1% |  |
| JUMP_FORWARD | 3,361,980 | 0.2% | 96.3% |  |
| TO_BOOL_LIST | 3,361,680 | 0.2% | 96.6% |  |
| COPY | 3,360,900 | 0.2% | 96.8% |  |
| IS_OP | 3,359,460 | 0.2% | 97.1% |  |
| GET_AWAITABLE | 3,359,340 | 0.2% | 97.3% |  |
| END_SEND | 3,359,340 | 0.2% | 97.5% |  |
| CALL_BUILTIN_FAST | 3,359,340 | 0.2% | 97.8% |  |
| STORE_SUBSCR_DICT | 3,359,220 | 0.2% | 98.0% |  |
| CALL_TYPE_1 | 3,359,220 | 0.2% | 98.2% |  |
| LIST_APPEND | 3,359,160 | 0.2% | 98.5% |  |
| SEND_GEN | 2,799,600 | 0.2% | 98.7% |  |
| MAKE_CELL | 2,799,360 | 0.2% | 98.9% |  |
| GET_ITER | 2,243,220 | 0.2% | 99.0% |  |
| BUILD_LIST | 2,242,020 | 0.2% | 99.2% |  |
| SWAP | 1,679,820 | 0.1% | 99.3% |  |
| FOR_ITER_LIST | 1,122,180 | 0.1% | 99.4% |  |
| SEND | 1,120,000 | 0.1% | 99.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 562,740 | 0.0% | 99.5% |  |
| CALL_BUILTIN_CLASS | 561,660 | 0.0% | 99.5% |  |
| FOR_ITER_RANGE | 561,060 | 0.0% | 99.6% |  |
| LOAD_SUPER_ATTR_METHOD | 560,460 | 0.0% | 99.6% |  |
| BUILD_TUPLE | 560,340 | 0.0% | 99.6% |  |
| BUILD_MAP | 560,100 | 0.0% | 99.7% |  |
| SET_FUNCTION_ATTRIBUTE | 560,040 | 0.0% | 99.7% |  |
| MAKE_FUNCTION | 560,040 | 0.0% | 99.8% |  |
| YIELD_VALUE | 559,980 | 0.0% | 99.8% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 559,980 | 0.0% | 99.8% |  |
| BINARY_OP_SUBTRACT_INT | 559,920 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 559,860 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 559,860 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 559,860 | 0.0% | 100.0% |  |
| CALL_LEN | 3,600 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 1,560 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,380 | 0.0% | 100.0% |  |
| LIST_EXTEND | 1,200 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 1,200 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 1,200 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,180 | 0.0% | 100.0% |  |
| BINARY_OP | 540 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 420 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 360 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |  |
| FOR_ITER | 180 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 160 | 0.0% | 100.0% |  |
| COMPARE_OP | 160 | 0.0% | 100.0% |  |
| UNARY_NOT | 120 | 0.0% | 100.0% |  |
| UNARY_INVERT | 120 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 120 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 120 | 0.0% | 100.0% |  |
| POP_EXCEPT | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 120 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 120 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 60 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| DICT_MERGE | 60 | 0.0% | 100.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 20 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 53,206,020 | 3.7% | 3.7% |
| RESUME_CHECK LOAD_FAST | 50,953,080 | 3.6% | 7.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 43,114,800 | 3.0% | 10.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 41,994,780 | 2.9% | 13.3% |
| STORE_FAST LOAD_FAST | 35,843,280 | 2.5% | 15.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 32,480,640 | 2.3% | 18.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 29,113,440 | 2.0% | 20.1% |
| LOAD_CONST LOAD_FAST | 25,756,260 | 1.8% | 21.9% |
| CACHE RESUME_CHECK | 25,754,520 | 1.8% | 23.7% |
| LOAD_FAST LOAD_ATTR_SLOT | 25,199,280 | 1.8% | 25.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 24,077,940 | 1.7% | 27.2% |
| LOAD_FAST LOAD_ATTR | 21,836,920 | 1.5% | 28.7% |
| LOAD_FAST STORE_ATTR_SLOT | 21,835,560 | 1.5% | 30.2% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 21,835,080 | 1.5% | 31.7% |
| RETURN_CONST INTERPRETER_EXIT | 21,275,460 | 1.5% | 33.2% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 20,717,460 | 1.5% | 34.7% |
| LOAD_ATTR_MODULE PUSH_NULL | 19,038,100 | 1.3% | 36.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 19,038,040 | 1.3% | 37.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 18,478,380 | 1.3% | 38.7% |
| RETURN_CONST POP_TOP | 17,920,200 | 1.3% | 39.9% |
| POP_TOP LOAD_FAST | 17,918,340 | 1.3% | 41.2% |
| LOAD_FAST RETURN_VALUE | 17,917,680 | 1.3% | 42.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 17,917,320 | 1.3% | 43.7% |
| CALL STORE_FAST | 17,916,180 | 1.3% | 44.9% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 17,915,820 | 1.3% | 46.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 17,356,020 | 1.2% | 47.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 16,796,460 | 1.2% | 48.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 14,560,020 | 1.0% | 49.6% |
| STORE_ATTR_SLOT LOAD_CONST | 14,556,900 | 1.0% | 50.6% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 14,556,600 | 1.0% | 51.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 13,999,780 | 1.0% | 52.6% |
| POP_JUMP_IF_FALSE LOAD_CONST | 13,999,320 | 1.0% | 53.6% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 13,996,860 | 1.0% | 54.6% |
| LOAD_CONST STORE_FAST | 11,203,380 | 0.8% | 55.4% |
| RETURN_VALUE STORE_FAST | 11,199,120 | 0.8% | 56.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 11,197,800 | 0.8% | 56.9% |
| RETURN_VALUE INTERPRETER_EXIT | 11,197,500 | 0.8% | 57.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 10,639,280 | 0.7% | 58.5% |
| POP_TOP RETURN_CONST | 10,638,300 | 0.7% | 59.2% |
| RETURN_VALUE TO_BOOL_BOOL | 10,638,060 | 0.7% | 60.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 10,637,820 | 0.7% | 60.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 10,637,820 | 0.7% | 61.5% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 10,637,700 | 0.7% | 62.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 10,637,520 | 0.7% | 62.9% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 10,637,460 | 0.7% | 63.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 10,637,420 | 0.7% | 64.4% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 10,077,600 | 0.7% | 65.1% |
| POP_TOP LOAD_CONST | 7,279,980 | 0.5% | 65.7% |
| PUSH_NULL LOAD_FAST | 7,279,920 | 0.5% | 66.2% |
| STORE_FAST RETURN_CONST | 7,279,500 | 0.5% | 66.7% |
| LOAD_FAST CALL | 7,278,880 | 0.5% | 67.2% |
| STORE_ATTR_SLOT RETURN_CONST | 7,278,540 | 0.5% | 67.7% |
| STORE_ATTR_SLOT LOAD_FAST | 7,278,540 | 0.5% | 68.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 7,278,480 | 0.5% | 68.7% |
| CALL_FUNCTION_EX POP_TOP | 7,278,420 | 0.5% | 69.2% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 7,278,400 | 0.5% | 69.7% |
| LOAD_FAST_LOAD_FAST CALL | 7,278,360 | 0.5% | 70.2% |
| POP_TOP ENTER_EXECUTOR | 7,278,300 | 0.5% | 70.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 7,278,300 | 0.5% | 71.3% |
| ENTER_EXECUTOR CALL_FUNCTION_EX | 7,277,100 | 0.5% | 71.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 6,724,200 | 0.5% | 72.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 6,721,200 | 0.5% | 72.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 6,720,540 | 0.5% | 73.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 6,718,920 | 0.5% | 73.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 6,718,740 | 0.5% | 74.1% |
| LOAD_DEREF LOAD_CONST | 6,718,440 | 0.5% | 74.6% |
| LOAD_CONST BINARY_OP_ADD_INT | 6,718,360 | 0.5% | 75.1% |
| POP_JUMP_IF_NONE LOAD_DEREF | 6,718,320 | 0.5% | 75.5% |
| LOAD_FAST CALL_LIST_APPEND | 6,718,320 | 0.5% | 76.0% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 6,718,320 | 0.5% | 76.5% |
| BINARY_OP_ADD_INT STORE_DEREF | 6,718,320 | 0.5% | 77.0% |
| POP_TOP RESUME_CHECK | 6,158,700 | 0.4% | 77.4% |
| LOAD_FAST LOAD_CONST | 5,040,420 | 0.4% | 77.7% |
| LOAD_CONST CALL_KW | 5,038,920 | 0.4% | 78.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 4,482,180 | 0.3% | 78.4% |
| PUSH_NULL CALL | 4,481,020 | 0.3% | 78.7% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 4,479,320 | 0.3% | 79.0% |
| NOP LOAD_FAST | 3,922,080 | 0.3% | 79.3% |
| COPY_FREE_VARS RESUME_CHECK | 3,919,680 | 0.3% | 79.6% |
| LOAD_ATTR CALL | 3,919,400 | 0.3% | 79.9% |
| LOAD_FAST PUSH_NULL | 3,919,380 | 0.3% | 80.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 3,919,320 | 0.3% | 80.4% |
| CALL POP_TOP | 3,919,320 | 0.3% | 80.7% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 3,919,140 | 0.3% | 81.0% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 3,919,140 | 0.3% | 81.2% |
| CACHE COPY_FREE_VARS | 3,919,080 | 0.3% | 81.5% |
| POP_JUMP_IF_FALSE LOAD_DEREF | 3,919,020 | 0.3% | 81.8% |
| LOAD_DEREF LOAD_ATTR_METHOD_WITH_VALUES | 3,919,020 | 0.3% | 82.1% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 3,361,680 | 0.2% | 82.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 3,361,680 | 0.2% | 82.5% |
| LOAD_CONST COMPARE_OP_INT | 3,360,820 | 0.2% | 82.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 3,360,700 | 0.2% | 83.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 3,360,540 | 0.2% | 83.2% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 3,360,480 | 0.2% | 83.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS STORE_FAST | 3,360,360 | 0.2% | 83.7% |
| LOAD_FAST STORE_ATTR | 3,359,980 | 0.2% | 83.9% |
| RETURN_VALUE RETURN_VALUE | 3,359,520 | 0.2% | 84.2% |
| LOAD_ATTR LOAD_FAST | 3,359,460 | 0.2% | 84.4% |
| LOAD_ATTR_SLOT LOAD_CONST | 3,359,400 | 0.2% | 84.6% |
| STORE_FAST LOAD_GLOBAL_MODULE | 3,359,380 | 0.2% | 84.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 25,754,520 | 78.0% |
| COPY_FREE_VARS | 3,919,080 | 11.9% |
| POP_TOP | 3,359,220 | 10.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 20 | 100.0% |


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
| RETURN_CONST | 2,799,480 | 83.3% |
| SEND | 559,860 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,359,340 | 100.0% |


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
| LOAD_FAST | 1,122,120 | 50.0% |
| CALL_BUILTIN_CLASS | 561,120 | 25.0% |
| LOAD_DEREF | 559,860 | 25.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,122,160 | 50.0% |
| LOAD_FAST_AND_CLEAR | 559,860 | 25.0% |
| FOR_ITER_TUPLE | 559,860 | 25.0% |
| FOR_ITER_RANGE | 1,200 | 0.1% |
| FOR_ITER | 140 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 21,275,460 | 64.4% |
| RETURN_VALUE | 11,197,500 | 33.9% |
| YIELD_VALUE | 559,860 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|


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
| POP_JUMP_IF_NOT_NONE | 2,799,420 | 71.4% |
| RESUME_CHECK | 561,540 | 14.3% |
| STORE_FAST | 561,240 | 14.3% |
| POP_TOP | 300 | 0.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,922,080 | 100.0% |
| LOAD_GLOBAL_MODULE | 320 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 50.0% |
| COPY | 60 | 50.0% |

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
| RETURN_CONST | 17,920,200 | 33.7% |
| CALL_METHOD_DESCRIPTOR_O | 13,996,860 | 26.3% |
| CALL_FUNCTION_EX | 7,278,420 | 13.7% |
| CALL | 3,919,320 | 7.4% |
| END_SEND | 3,359,340 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,918,340 | 33.7% |
| RETURN_CONST | 10,638,300 | 20.0% |
| LOAD_CONST | 7,279,980 | 13.7% |
| ENTER_EXECUTOR | 7,278,300 | 13.7% |
| RESUME_CHECK | 6,158,700 | 11.6% |


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
| LOAD_ATTR_MODULE | 19,038,100 | 82.9% |
| LOAD_FAST | 3,919,380 | 17.1% |
| LOAD_ATTR | 1,340 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,637,700 | 46.3% |
| LOAD_FAST | 7,279,920 | 31.7% |
| CALL | 4,481,020 | 19.5% |
| LOAD_GLOBAL_BUILTIN | 559,860 | 2.4% |
| LOAD_CONST | 180 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,359,280 | 54.5% |
| ENTER_EXECUTOR | 2,799,300 | 45.5% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 3,359,160 | 54.5% |
| GET_AWAITABLE | 2,799,480 | 45.5% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,917,680 | 48.5% |
| LOAD_ATTR_INSTANCE_VALUE | 11,197,800 | 30.3% |
| RETURN_VALUE | 3,359,520 | 9.1% |
| POP_JUMP_IF_FALSE | 3,359,280 | 9.1% |
| CALL | 561,240 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 11,199,120 | 30.3% |
| INTERPRETER_EXIT | 11,197,500 | 30.3% |
| TO_BOOL_BOOL | 10,638,060 | 28.8% |
| RETURN_VALUE | 3,359,520 | 9.1% |
| GET_AWAITABLE | 559,860 | 1.5% |


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
| LOAD_ATTR_INSTANCE_VALUE | 3,360,480 | 85.7% |
| LOAD_FAST | 559,920 | 14.3% |
| TO_BOOL | 1,000 | 0.0% |
| RETURN_VALUE | 180 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,359,220 | 85.7% |
| POP_JUMP_IF_TRUE | 561,060 | 14.3% |
| TO_BOOL | 1,000 | 0.0% |
| TO_BOOL_BOOL | 420 | 0.0% |
| TO_BOOL_INT | 120 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 60 | 50.0% |
| BINARY_OP | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 120 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 60 | 50.0% |
| TO_BOOL_BOOL | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| COPY | 60 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180 | 33.3% |
| UNARY_INVERT | 120 | 22.2% |
| BINARY_OP | 120 | 22.2% |
| POP_JUMP_IF_FALSE | 60 | 11.1% |
| LOAD_CONST | 40 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 22.2% |
| COPY | 120 | 22.2% |
| BINARY_OP | 120 | 22.2% |
| UNARY_INVERT | 60 | 11.1% |
| TO_BOOL_INT | 40 | 7.4% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 561,060 | 25.0% |
| SWAP | 559,860 | 25.0% |
| STORE_DEREF | 559,860 | 25.0% |
| POP_JUMP_IF_FALSE | 559,860 | 25.0% |
| LOAD_ATTR_SLOT | 1,200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,120,920 | 50.0% |
| SWAP | 559,860 | 25.0% |
| STORE_DEREF | 559,860 | 25.0% |
| LOAD_FAST | 1,380 | 0.1% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 100.0% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| BUILD_TUPLE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 100.0% |
| LOAD_FAST | 240 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,040 | 99.9% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 560,040 | 99.9% |
| CALL | 100 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |
| BUILD_MAP | 60 | 0.0% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,278,880 | 25.0% |
| LOAD_FAST_LOAD_FAST | 7,278,360 | 25.0% |
| PUSH_NULL | 4,481,020 | 15.4% |
| LOAD_ATTR | 3,919,400 | 13.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,359,260 | 11.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,916,180 | 61.5% |
| POP_TOP | 3,919,320 | 13.5% |
| RESUME_CHECK | 3,359,340 | 11.5% |
| CALL_METHOD_DESCRIPTOR_O | 3,359,260 | 11.5% |
| RETURN_VALUE | 561,240 | 1.9% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,277,100 | 92.8% |
| STORE_FAST | 559,860 | 7.1% |
| CALL_INTRINSIC_1 | 1,200 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| DICT_MERGE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,278,420 | 92.9% |
| MAKE_CELL | 559,860 | 7.1% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 1,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,200 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,038,920 | 64.3% |
| ENTER_EXECUTOR | 2,799,300 | 35.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,359,220 | 42.9% |
| RESUME_CHECK | 3,359,220 | 42.9% |
| POP_TOP | 559,920 | 7.1% |
| STORE_DEREF | 559,860 | 7.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 120 | 75.0% |
| LOAD_CONST | 20 | 12.5% |
| COMPARE_OP | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 75.0% |
| COMPARE_OP_INT | 20 | 12.5% |
| COMPARE_OP | 20 | 12.5% |


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
| CALL_BUILTIN_FAST | 3,359,280 | 100.0% |
| CALL_LEN | 1,200 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| BINARY_OP | 120 | 0.0% |
| UNARY_NOT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,359,360 | 100.0% |
| TO_BOOL_INT | 1,280 | 0.0% |
| TO_BOOL | 80 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| POP_EXCEPT | 60 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 3,919,080 | 100.0% |
| CALL_PY_EXACT_ARGS | 600 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,919,680 | 100.0% |
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
| POP_TOP | 7,278,300 | 41.9% |
| CALL_LIST_APPEND | 6,718,320 | 38.7% |
| LIST_APPEND | 3,359,160 | 19.4% |
| POP_JUMP_IF_FALSE | 1,140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 7,277,100 | 41.9% |
| RETURN_GENERATOR | 2,799,300 | 16.1% |
| CALL_KW | 2,799,300 | 16.1% |
| CALL | 2,799,300 | 16.1% |
| SWAP | 559,860 | 3.2% |


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
| RETURN_CONST | 60 | 33.3% |
| LOAD_FAST | 60 | 33.3% |
| FOR_ITER | 40 | 22.2% |
| FOR_ITER_LIST | 20 | 11.1% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 2,799,480 | 83.3% |
| RETURN_VALUE | 559,860 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,359,340 | 100.0% |


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
| RESUME_CHECK | 559,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 559,860 | 100.0% |
| SEND_GEN | 120 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,359,220 | 99.9% |
| STORE_FAST | 2,700 | 0.1% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 3,359,160 | 99.9% |
| LOAD_FAST | 1,560 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,200 | 0.0% |
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
| LOAD_ATTR_SLOT | 1,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 1,200 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,836,920 | 100.0% |
| LOAD_ATTR | 5,840 | 0.0% |
| LOAD_ATTR_SLOT | 1,280 | 0.0% |
| LOAD_GLOBAL_MODULE | 600 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,637,460 | 48.7% |
| CALL | 3,919,400 | 17.9% |
| LOAD_FAST | 3,359,460 | 15.4% |
| TO_BOOL_NONE | 3,359,220 | 15.4% |
| STORE_FAST | 559,920 | 2.6% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 14,556,900 | 23.6% |
| POP_JUMP_IF_FALSE | 13,999,320 | 22.7% |
| POP_TOP | 7,279,980 | 11.8% |
| LOAD_DEREF | 6,718,440 | 10.9% |
| LOAD_FAST | 5,040,420 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,756,260 | 41.8% |
| STORE_FAST | 11,203,380 | 18.2% |
| BINARY_OP_ADD_INT | 6,718,360 | 10.9% |
| CALL_KW | 5,038,920 | 8.2% |
| COMPARE_OP_INT | 3,360,820 | 5.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,718,320 | 22.2% |
| POP_JUMP_IF_FALSE | 3,919,020 | 13.0% |
| RESUME_CHECK | 3,359,220 | 11.1% |
| STORE_DEREF | 3,359,160 | 11.1% |
| STORE_ATTR | 3,359,160 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,718,440 | 22.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,919,020 | 13.0% |
| TO_BOOL_BOOL | 3,359,160 | 11.1% |
| POP_JUMP_IF_NONE | 3,359,160 | 11.1% |
| LOAD_DEREF | 3,359,160 | 11.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 50,953,080 | 19.9% |
| POP_JUMP_IF_FALSE | 41,994,780 | 16.4% |
| STORE_FAST | 35,843,280 | 14.0% |
| LOAD_CONST | 25,756,260 | 10.1% |
| POP_TOP | 17,918,340 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 53,206,020 | 20.8% |
| LOAD_ATTR_SLOT | 25,199,280 | 9.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 24,077,940 | 9.4% |
| LOAD_ATTR | 21,836,920 | 8.5% |
| STORE_ATTR_SLOT | 21,835,560 | 8.5% |


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
| STORE_ATTR_SLOT | 21,835,080 | 31.5% |
| LOAD_FAST_LOAD_FAST | 10,637,820 | 15.3% |
| PUSH_NULL | 10,637,700 | 15.3% |
| POP_JUMP_IF_NOT_NONE | 10,077,600 | 14.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,278,300 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 29,113,440 | 41.9% |
| LOAD_FAST_LOAD_FAST | 10,637,820 | 15.3% |
| LOAD_FAST | 10,637,820 | 15.3% |
| CALL | 7,278,360 | 10.5% |
| LOAD_CONST | 3,919,140 | 5.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 220 | 18.6% |
| POP_TOP | 220 | 18.6% |
| LOAD_FAST | 140 | 11.9% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 10.2% |
| STORE_FAST | 100 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 880 | 74.6% |
| LOAD_GLOBAL_BUILTIN | 280 | 23.7% |
| LOAD_ATTR | 20 | 1.7% |


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
| TO_BOOL_BOOL | 43,114,800 | 52.7% |
| TO_BOOL_NONE | 17,915,820 | 21.9% |
| COMPARE_OP_INT | 6,721,200 | 8.2% |
| CONTAINS_OP | 3,919,140 | 4.8% |
| TO_BOOL_LIST | 3,361,680 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,994,780 | 51.4% |
| RETURN_CONST | 16,796,460 | 20.5% |
| LOAD_CONST | 13,999,320 | 17.1% |
| LOAD_DEREF | 3,919,020 | 4.8% |
| RETURN_VALUE | 3,359,280 | 4.1% |


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
| LOAD_FAST | 17,917,320 | 84.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,359,220 | 15.8% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,077,600 | 47.4% |
| LOAD_GLOBAL_MODULE | 4,479,320 | 21.1% |
| LOAD_FAST | 3,360,540 | 15.8% |
| NOP | 2,799,420 | 13.2% |
| LOAD_GLOBAL_BUILTIN | 559,860 | 2.6% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 6,718,920 | 92.3% |
| TO_BOOL | 561,060 | 7.7% |
| TO_BOOL_INT | 1,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,278,480 | 100.0% |
| LOAD_CONST | 1,260 | 0.0% |
| STORE_FAST | 1,200 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| RETURN_CONST | 60 | 0.0% |


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
| POP_JUMP_IF_FALSE | 16,796,460 | 37.0% |
| POP_TOP | 10,638,300 | 23.5% |
| STORE_FAST | 7,279,500 | 16.1% |
| STORE_ATTR_SLOT | 7,278,540 | 16.0% |
| RESUME_CHECK | 2,799,360 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 21,275,460 | 46.9% |
| POP_TOP | 17,920,200 | 39.5% |
| TO_BOOL_BOOL | 3,359,220 | 7.4% |
| END_SEND | 2,799,480 | 6.2% |
| EXIT_INIT_CHECK | 120 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 559,860 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 559,860 | 50.0% |
| SEND | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 559,860 | 50.0% |
| END_SEND | 559,860 | 50.0% |
| SEND | 280 | 0.0% |


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
| LOAD_FAST | 3,359,980 | 85.7% |
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
| CALL_KW | 559,860 | 5.9% |
| BUILD_LIST | 559,860 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,359,160 | 35.3% |
| LOAD_DEREF | 3,359,160 | 35.3% |
| LOAD_FAST | 1,119,720 | 11.8% |
| LOAD_CONST | 1,119,720 | 11.8% |
| BUILD_LIST | 559,860 | 5.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 17,916,180 | 34.8% |
| LOAD_CONST | 11,203,380 | 21.7% |
| RETURN_VALUE | 11,199,120 | 21.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,360,360 | 6.5% |
| CALL_KW | 3,359,220 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,843,280 | 69.6% |
| RETURN_CONST | 7,279,500 | 14.1% |
| LOAD_GLOBAL_MODULE | 3,359,380 | 6.5% |
| LOAD_FAST_LOAD_FAST | 1,119,960 | 2.2% |
| LOAD_CONST | 1,119,780 | 2.2% |


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
| LOAD_FAST_AND_CLEAR | 559,860 | 33.3% |
| ENTER_EXECUTOR | 559,860 | 33.3% |
| BUILD_LIST | 559,860 | 33.3% |
| LOAD_FAST | 60 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,920 | 33.3% |
| FOR_ITER_RANGE | 559,860 | 33.3% |
| BUILD_LIST | 559,860 | 33.3% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| POP_EXCEPT | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20 | 33.3% |
| RETURN_VALUE | 20 | 33.3% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 100.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 559,860 | 100.0% |
| YIELD_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 559,860 | 100.0% |
| YIELD_VALUE | 120 | 0.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200 | 100.0% |


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
| RETURN_VALUE | 60 | 50.0% |
| PUSH_EXC_INFO | 60 | 50.0% |


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

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 50.0% |
| COPY_FREE_VARS | 60 | 50.0% |


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
| LOAD_GLOBAL_MODULE | 559,860 | 99.7% |
| LOAD_FAST | 1,380 | 0.2% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 561,120 | 99.9% |
| LOAD_FAST | 180 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| COMPARE_OP | 120 | 0.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,359,340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 3,359,280 | 100.0% |
| TO_BOOL_BOOL | 60 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 33.3% |
| LOAD_CONST | 40 | 33.3% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 300 | 71.4% |
| LOAD_GLOBAL_MODULE | 40 | 9.5% |
| CALL | 40 | 9.5% |
| BUILD_TUPLE | 40 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 380 | 90.5% |
| TO_BOOL | 40 | 9.5% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,400 | 66.7% |
| COPY | 1,200 | 33.3% |


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
| LOAD_FAST_LOAD_FAST | 1,200 | 87.0% |
| LOAD_CONST | 60 | 4.3% |
| LOAD_FAST | 40 | 2.9% |
| LOAD_ATTR | 40 | 2.9% |
| CALL | 40 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200 | 87.0% |
| POP_TOP | 120 | 8.7% |
| RETURN_VALUE | 60 | 4.3% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 10,637,460 | 75.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,359,160 | 23.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,600 | 0.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,640 | 0.0% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,637,420 | 75.6% |
| STORE_FAST | 3,360,360 | 23.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 64,600 | 0.5% |
| POP_TOP | 360 | 0.0% |
| CALL | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,637,520 | 76.0% |
| CALL | 3,359,260 | 24.0% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 13,996,860 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 20,717,460 | 57.8% |
| LOAD_FAST | 14,560,020 | 40.6% |
| BINARY_OP_SUBTRACT_INT | 559,860 | 1.6% |
| LOAD_ATTR_METHOD_NO_DICT | 1,320 | 0.0% |
| CALL | 1,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 32,480,640 | 90.6% |
| RETURN_GENERATOR | 3,359,280 | 9.4% |
| COPY_FREE_VARS | 600 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 120 | 33.3% |
| LOAD_FAST | 80 | 22.2% |
| CALL | 80 | 22.2% |
| PUSH_NULL | 40 | 11.1% |
| LOAD_CONST | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 360 | 100.0% |


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

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,360,820 | 50.0% |
| LOAD_DEREF | 3,359,160 | 50.0% |
| LOAD_GLOBAL_MODULE | 1,200 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,721,200 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,122,160 | 100.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 559,860 | 49.9% |
| LOAD_DEREF | 559,860 | 49.9% |
| RETURN_CONST | 1,260 | 0.1% |
| LOAD_FAST | 1,200 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 559,860 | 99.8% |
| GET_ITER | 1,200 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 559,860 | 99.8% |
| STORE_FAST | 1,200 | 0.2% |


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
| LOAD_FAST | 53,206,020 | 93.1% |
| LOAD_FAST_LOAD_FAST | 3,359,380 | 5.9% |
| LOAD_DEREF | 559,860 | 1.0% |
| LOAD_ATTR | 600 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 18,478,380 | 32.3% |
| LOAD_ATTR_METHOD_NO_DICT | 13,999,780 | 24.5% |
| RETURN_VALUE | 11,197,800 | 19.6% |
| TO_BOOL_LIST | 3,361,680 | 5.9% |
| TO_BOOL | 3,360,480 | 5.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 13,999,780 | 67.6% |
| LOAD_FAST | 3,360,700 | 16.2% |
| LOAD_DEREF | 3,359,160 | 16.2% |
| LOAD_ATTR | 320 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,356,020 | 83.8% |
| LOAD_GLOBAL_MODULE | 3,359,220 | 16.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,640 | 0.0% |
| LOAD_FAST_LOAD_FAST | 1,320 | 0.0% |
| CALL_PY_EXACT_ARGS | 1,320 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,077,940 | 67.2% |
| LOAD_ATTR_SLOT | 7,278,400 | 20.3% |
| LOAD_DEREF | 3,919,020 | 10.9% |
| STORE_FAST_LOAD_FAST | 559,860 | 1.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 20,717,460 | 57.8% |
| LOAD_FAST_LOAD_FAST | 7,278,300 | 20.3% |
| LOAD_FAST | 4,482,180 | 12.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,359,160 | 9.4% |
| CALL | 420 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 19,038,040 | 100.0% |
| LOAD_ATTR | 600 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 19,038,100 | 100.0% |
| LOAD_ATTR | 260 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| UNARY_INVERT | 60 | 0.0% |
| STORE_FAST | 60 | 0.0% |


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
| LOAD_FAST | 25,199,280 | 100.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 14,556,600 | 57.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,278,400 | 28.9% |
| LOAD_CONST | 3,359,400 | 13.3% |
| LOAD_ATTR | 1,280 | 0.0% |
| TO_BOOL_BOOL | 1,240 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,720,540 | 85.7% |
| PUSH_NULL | 559,860 | 7.1% |
| POP_JUMP_IF_NOT_NONE | 559,860 | 7.1% |
| STORE_FAST | 1,240 | 0.0% |
| POP_JUMP_IF_FALSE | 1,200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,724,200 | 85.7% |
| LOAD_DEREF | 560,460 | 7.1% |
| LOAD_GLOBAL_MODULE | 559,900 | 7.1% |
| CALL_ISINSTANCE | 300 | 0.0% |
| CALL_BUILTIN_CLASS | 180 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,639,280 | 38.8% |
| POP_JUMP_IF_NOT_NONE | 4,479,320 | 16.3% |
| STORE_FAST | 3,359,380 | 12.2% |
| LOAD_ATTR_METHOD_NO_DICT | 3,359,220 | 12.2% |
| CALL_TYPE_1 | 3,359,220 | 12.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 19,038,040 | 69.4% |
| LOAD_FAST_LOAD_FAST | 3,919,320 | 14.3% |
| CONTAINS_OP | 3,359,220 | 12.2% |
| LOAD_DEREF | 559,860 | 2.0% |
| CALL_BUILTIN_CLASS | 559,860 | 2.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,300 | 100.0% |
| LOAD_SUPER_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560,100 | 99.9% |
| CALL_PY_EXACT_ARGS | 200 | 0.0% |
| CALL | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 32,480,640 | 43.0% |
| CACHE | 25,754,520 | 34.1% |
| POP_TOP | 6,158,700 | 8.1% |
| COPY_FREE_VARS | 3,919,680 | 5.2% |
| CALL | 3,359,340 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,953,080 | 67.4% |
| LOAD_GLOBAL_MODULE | 10,639,280 | 14.1% |
| LOAD_GLOBAL_BUILTIN | 6,720,540 | 8.9% |
| LOAD_DEREF | 3,359,220 | 4.4% |
| RETURN_CONST | 2,799,360 | 3.7% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,799,480 | 100.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,799,480 | 100.0% |
| RESUME_CHECK | 120 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 29,113,440 | 57.1% |
| LOAD_FAST | 21,835,560 | 42.9% |
| STORE_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 21,835,080 | 42.9% |
| LOAD_CONST | 14,556,900 | 28.6% |
| RETURN_CONST | 7,278,540 | 14.3% |
| LOAD_FAST | 7,278,540 | 14.3% |


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
| LOAD_ATTR_INSTANCE_VALUE | 18,478,380 | 37.1% |
| RETURN_VALUE | 10,638,060 | 21.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,637,420 | 21.3% |
| COPY | 3,359,360 | 6.7% |
| RETURN_CONST | 3,359,220 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 43,114,800 | 86.5% |
| POP_JUMP_IF_TRUE | 6,718,920 | 13.5% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,280 | 82.1% |
| TO_BOOL | 120 | 7.7% |
| LOAD_FAST | 80 | 5.1% |
| LOAD_ATTR | 40 | 2.6% |
| BINARY_OP | 40 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,260 | 80.8% |
| POP_JUMP_IF_FALSE | 240 | 15.4% |
| UNARY_NOT | 60 | 3.8% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,361,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,361,680 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 14,556,600 | 81.2% |
| LOAD_ATTR | 3,359,220 | 18.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,915,820 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE | 60 | 33.3% |
| STORE_FAST | 40 | 22.2% |
| RETURN_VALUE | 40 | 22.2% |
| CALL | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 120 | 66.7% |
| LOAD_FAST | 60 | 33.3% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          180 | 90.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      3359220 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3920280 | 5.2% |
|          hit |     71112840 | 94.8% |

#### Specialization attempts

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

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          360 | 0.0% |
|          hit |      7279560 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 33.3% |
| Failure | 120 | 66.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 80 | 66.7% |
| or | 40 | 33.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     29116140 | 27.2% |
| specialization.deopt |        64600 | 0.1% |
|          hit |     74481300 | 69.6% |
|         miss |      3424120 | 3.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 66,200 | 89.6% |
| Failure | 7,700 | 10.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 2,660 | 34.5% |
| no dict | 1,800 | 23.4% |
| class no vectorcall | 860 | 11.2% |
| code complex parameters | 860 | 11.2% |
| other | 820 | 10.6% |
| cfunc noargs | 340 | 4.4% |
| cmethod | 140 | 1.8% |
| class mutable | 80 | 1.0% |
| cfunc varargs | 40 | 0.5% |
| wrong number arguments | 40 | 0.5% |
| init not simple | 20 | 0.3% |
| operator wrapper | 20 | 0.3% |
| cfunc varargs keywords | 20 | 0.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          120 | 0.0% |
|          hit |      6721200 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 50.0% |
| Failure | 20 | 50.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bool | 20 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          120 | 0.0% |
|          hit |      2243100 | 100.0% |

#### Specialization attempts

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
|---|---|---|
| specialization.deferred |     21837380 | 12.1% |
|          hit |    157922200 | 87.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,320 | 28.4% |
| Failure | 5,840 | 71.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 4,500 | 77.1% |
| class attr descriptor | 820 | 14.0% |
| method | 260 | 4.5% |
| not managed dict | 140 | 2.4% |
| class attr simple | 40 | 0.7% |
| metaclass attribute | 40 | 0.7% |
| non object slot | 40 | 0.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     35284960 | 100.0% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,160 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       560460 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
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
| specialization.deferred |      1119720 | 28.6% |
|          hit |      2799600 | 71.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 280 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 280 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3919320 | 7.1% |
|          hit |     51511800 | 92.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 860 | 45.7% |
| Failure | 1,020 | 54.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overriding descriptor | 840 | 82.4% |
| no dict | 140 | 13.7% |
| overridden | 40 | 3.9% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          180 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
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
| Basic | 754,272,720 | 52.9% |
| Not specialized | 183,779,860 | 12.9% |
| Specialized | 488,838,660 | 34.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,000,680 | 100.0% |
| CALL | 29,116,140 | 0.0% |
| LOAD_ATTR | 21,837,380 | 0.0% |
| TO_BOOL | 3,920,280 | 0.0% |
| STORE_ATTR | 3,919,320 | 0.0% |
| SEND | 1,119,720 | 0.0% |
| BINARY_OP | 360 | 0.0% |
| FOR_ITER | 120 | 0.0% |
| COMPARE_OP | 120 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,424,000 | 98.2% |
| RESUME_CHECK | 31,640 | 0.9% |
| RESUME | 31,640 | 0.9% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
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
| Calls to PyEval_EvalDefault | 33,032,820 | 41.8% |
| Calls to Python functions inlined | 45,919,200 | 58.2% |
| Calls via PyEval_EvalFrame (total) | 33,032,820 | 41.8% |
| Calls via PyEval_EvalFrame (vector) | 29,113,740 | 36.9% |
| Calls via PyEval_EvalFrame (generator) | 3,919,080 | 5.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 29,113,740 | 36.9% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 559,920 | 0.7% |
| Calls via PyEval_EvalFrame (api) | 3,359,280 | 4.3% |
| Calls via PyEval_EvalFrame (method) | 14,556,600 | 18.4% |
| Frames pushed | 82,311,000 | 104.3% |
| Frame objects created | 120 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 43,780,420 | 37.2% |
| Frees to freelist | 43,947,720 |  |
| Allocations | 73,972,702 | 62.8% |
| Allocations to 512 bytes | 73,928,900 | 62.8% |
| Allocations to 4 kbytes | 43,800 | 0.0% |
| Allocations over 4 kbytes | 2 | 0.0% |
| Frees | 75,650,756 |  |
| New values | 180 |  |
| Interpreter increfs | 746,967,640 | 66.9% |
| Interpreter decrefs | 791,770,740 | 64.9% |
| Increfs | 369,501,724 | 33.1% |
| Decrefs | 427,639,544 | 35.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 62,154,465 |  |
| Method cache misses | 561,735 |  |
| Method cache collisions | 563,088 |  |
| Method cache dunder hits | 7,837,596 |  |
| Method cache dunder misses | 1,744 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 36,900 | 0 | 193,312,040 |
| 1 | 3,360 | 0 | 209,016,160 |
| 2 | 280 | 0 | 545,913,000 |


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
| Traces executed | 17,356,920 |  |
| Uops executed | 695,858,100 | 40 |
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
| <= 8 | 1,680,780 | 9.7% |
| <= 16 | 1,140 | 0.0% |
| <= 32 | 8,397,900 | 48.4% |
| <= 64 | 0 | 0.0% |
| <= 128 | 7,277,100 | 41.9% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 193,696,920 | 27.8% | 27.8% |
| LOAD_FAST | 73,335,240 | 10.5% | 38.4% |
| _GUARD_TYPE_VERSION | 61,017,240 | 8.8% | 47.1% |
| _POP_JUMP_IF_TRUE | 34,709,280 | 5.0% | 52.1% |
| _LOAD_ATTR_SLOT | 29,108,400 | 4.2% | 56.3% |
| STORE_FAST | 22,952,100 | 3.3% | 59.6% |
| _EXIT_TRACE | 17,356,920 | 2.5% | 62.1% |
| TO_BOOL_BOOL | 17,353,500 | 2.5% | 64.6% |
| _LOAD_ATTR_METHOD_NO_DICT | 14,554,200 | 2.1% | 66.7% |
| _LOAD_ATTR_INSTANCE_VALUE | 14,554,200 | 2.1% | 68.8% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 14,554,200 | 2.1% | 70.9% |
| LOAD_ATTR | 12,875,700 | 1.9% | 72.7% |
| _ITER_CHECK_RANGE | 10,637,460 | 1.5% | 74.3% |
| _IS_ITER_EXHAUSTED_RANGE | 10,637,460 | 1.5% | 75.8% |
| _SAVE_CURRENT_IP | 10,077,540 | 1.4% | 77.2% |
| _PUSH_FRAME | 10,077,540 | 1.4% | 78.7% |
| _INIT_CALL_PY_EXACT_ARGS | 10,077,540 | 1.4% | 80.1% |
| _CHECK_STACK_SPACE | 10,077,540 | 1.4% | 81.6% |
| _CHECK_PEP_523 | 10,077,540 | 1.4% | 83.0% |
| _CHECK_FUNCTION_EXACT_ARGS | 10,077,540 | 1.4% | 84.5% |
| _ITER_NEXT_RANGE | 10,076,400 | 1.4% | 85.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 10,076,400 | 1.4% | 87.4% |
| RESUME_CHECK | 7,277,100 | 1.0% | 88.4% |
| PUSH_NULL | 7,277,100 | 1.0% | 89.5% |
| LIST_EXTEND | 7,277,100 | 1.0% | 90.5% |
| CALL_INTRINSIC_1 | 7,277,100 | 1.0% | 91.6% |
| BUILD_LIST | 7,277,100 | 1.0% | 92.6% |
| LOAD_CONST | 5,598,600 | 0.8% | 93.4% |
| _ITER_CHECK_TUPLE | 3,359,160 | 0.5% | 93.9% |
| _ITER_CHECK_LIST | 3,359,160 | 0.5% | 94.4% |
| _IS_ITER_EXHAUSTED_TUPLE | 3,359,160 | 0.5% | 94.9% |
| _IS_ITER_EXHAUSTED_LIST | 3,359,160 | 0.5% | 95.3% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 2,800,440 | 0.4% | 95.7% |
| _GUARD_KEYS_VERSION | 2,800,440 | 0.4% | 96.1% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 2,800,440 | 0.4% | 96.5% |
| _POP_JUMP_IF_FALSE | 2,799,300 | 0.4% | 96.9% |
| _LOAD_GLOBAL_MODULE | 2,799,300 | 0.4% | 97.3% |
| _ITER_NEXT_TUPLE | 2,799,300 | 0.4% | 97.7% |
| _ITER_NEXT_LIST | 2,799,300 | 0.4% | 98.1% |
| _GUARD_GLOBALS_VERSION | 2,799,300 | 0.4% | 98.6% |
| _GUARD_BOTH_INT | 2,799,300 | 0.4% | 99.0% |
| _BINARY_OP_SUBTRACT_INT | 2,799,300 | 0.4% | 99.4% |
| CONTAINS_OP | 2,799,300 | 0.4% | 99.8% |
| POP_TOP | 1,680,780 | 0.2% | 100.0% |


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
Stats gathered on: 2023-10-04
