
# Pystats results

- benchmark: async_tree_tg
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 376,300,480 | 20.8% | 20.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 122,448,980 | 6.8% | 27.5% |  |
| POP_JUMP_IF_FALSE | 94,819,720 | 5.2% | 32.7% |  |
| RESUME_CHECK | 93,325,740 | 5.1% | 37.9% | 0.0% |
| POP_TOP | 90,333,940 | 5.0% | 42.9% |  |
| LOAD_FAST_LOAD_FAST | 81,371,880 | 4.5% | 47.4% |  |
| STORE_ATTR_SLOT | 67,931,820 | 3.7% | 51.1% |  |
| LOAD_CONST | 67,200,540 | 3.7% | 54.8% |  |
| TO_BOOL_BOOL | 58,233,620 | 3.2% | 58.0% |  |
| RETURN_CONST | 56,740,460 | 3.1% | 61.2% |  |
| STORE_FAST | 49,296,360 | 2.7% | 63.9% |  |
| LOAD_ATTR_SLOT | 48,526,160 | 2.7% | 66.6% |  |
| RETURN_VALUE | 45,542,900 | 2.5% | 69.1% |  |
| INTERPRETER_EXIT | 44,790,380 | 2.5% | 71.5% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 44,051,300 | 2.4% | 74.0% |  |
| LOAD_ATTR | 42,573,680 | 2.3% | 76.3% |  |
| CALL_PY_EXACT_ARGS | 38,829,180 | 2.1% | 78.5% |  |
| CALL | 38,092,260 | 2.1% | 80.6% |  |
| CALL_METHOD_DESCRIPTOR_O | 32,099,000 | 1.8% | 82.3% | 0.0% |
| PUSH_NULL | 31,356,900 | 1.7% | 84.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 27,626,800 | 1.5% | 85.6% |  |
| POP_JUMP_IF_NOT_NONE | 25,383,160 | 1.4% | 87.0% |  |
| TO_BOOL_NONE | 24,634,160 | 1.4% | 88.3% |  |
| LOAD_GLOBAL_MODULE | 23,148,420 | 1.3% | 89.6% |  |
| LOAD_ATTR_MODULE | 17,919,400 | 1.0% | 90.6% |  |
| ENTER_EXECUTOR | 14,183,860 | 0.8% | 91.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 11,946,580 | 0.7% | 92.0% |  |
| POP_JUMP_IF_NONE | 11,944,720 | 0.7% | 92.7% |  |
| TO_BOOL | 11,205,020 | 0.6% | 93.3% |  |
| BUILD_LIST | 10,452,720 | 0.6% | 93.9% |  |
| POP_JUMP_IF_TRUE | 9,708,340 | 0.5% | 94.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,707,000 | 0.5% | 95.0% | 0.0% |
| CALL_FUNCTION_EX | 9,704,640 | 0.5% | 95.5% |  |
| RETURN_GENERATOR | 9,704,560 | 0.5% | 96.0% |  |
| CALL_INTRINSIC_1 | 9,704,400 | 0.5% | 96.6% |  |
| LIST_EXTEND | 9,704,400 | 0.5% | 97.1% |  |
| SEND_GEN | 5,972,140 | 0.3% | 97.4% |  |
| END_SEND | 5,972,080 | 0.3% | 97.8% |  |
| GET_AWAITABLE | 5,972,080 | 0.3% | 98.1% |  |
| TO_BOOL_LIST | 5,228,660 | 0.3% | 98.4% |  |
| CALL_KW | 5,225,600 | 0.3% | 98.7% |  |
| JUMP_FORWARD | 4,482,660 | 0.2% | 98.9% |  |
| COMPARE_OP_INT | 4,482,600 | 0.2% | 99.2% |  |
| LOAD_GLOBAL_BUILTIN | 1,502,160 | 0.1% | 99.3% | 0.0% |
| CALL_BUILTIN_CLASS | 1,495,220 | 0.1% | 99.3% |  |
| SEND | 1,493,720 | 0.1% | 99.4% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 1,493,120 | 0.1% | 99.5% |  |
| YIELD_VALUE | 1,493,120 | 0.1% | 99.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 760,860 | 0.0% | 99.6% | 100.0% |
| NOP | 751,560 | 0.0% | 99.7% |  |
| GET_ITER | 751,540 | 0.0% | 99.7% |  |
| FOR_ITER_RANGE | 748,680 | 0.0% | 99.8% |  |
| IS_OP | 746,880 | 0.0% | 99.8% |  |
| BINARY_OP_SUBTRACT_INT | 746,800 | 0.0% | 99.8% |  |
| EXIT_INIT_CHECK | 746,580 | 0.0% | 99.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 746,580 | 0.0% | 99.9% |  |
| BEFORE_ASYNC_WITH | 746,480 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 746,460 | 0.0% | 100.0% |  |
| CALL_LEN | 4,740 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 3,940 | 0.0% | 100.0% |  |
| STORE_ATTR | 3,500 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 3,220 | 0.0% | 100.0% |  |
| COPY | 2,340 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 1,960 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,780 | 0.0% | 100.0% |  |
| RESUME | 1,720 | 0.0% | 100.0% | 1,533.7% |
| BINARY_OP_ADD_FLOAT | 1,580 | 0.0% | 100.0% |  |
| LOAD_DEREF | 1,220 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 1,060 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 1,040 | 0.0% | 100.0% |  |
| BINARY_OP | 800 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 640 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 620 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 520 | 0.0% | 100.0% |  |
| COMPARE_OP | 500 | 0.0% | 100.0% |  |
| FOR_ITER | 440 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 380 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 380 | 0.0% | 100.0% |  |
| SWAP | 340 | 0.0% | 100.0% |  |
| BUILD_MAP | 320 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 240 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 240 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 240 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 200 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 180 | 0.0% | 100.0% |  |
| POP_EXCEPT | 180 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 180 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |  |
| UNARY_INVERT | 160 | 0.0% | 100.0% |  |
| UNARY_NOT | 160 | 0.0% | 100.0% |  |
| CONTAINS_OP | 160 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 160 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 140 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 140 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 120 | 0.0% | 100.0% |  |
| IMPORT_NAME | 100 | 0.0% | 100.0% |  |
| DICT_MERGE | 80 | 0.0% | 100.0% |  |
| MAKE_CELL | 80 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 80 | 0.0% | 100.0% |  |
| RERAISE | 80 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 80 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 60 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_INT | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 60 | 0.0% | 100.0% |  |
| BEFORE_WITH | 40 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 40 | 0.0% | 100.0% |  |
| IMPORT_FROM | 20 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 20 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 20 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 20 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 20 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 20 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 117,967,880 | 6.5% | 6.5% |
| RESUME_CHECK LOAD_FAST | 76,148,020 | 4.2% | 10.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 68,683,900 | 3.8% | 14.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 53,007,580 | 2.9% | 17.4% |
| LOAD_FAST LOAD_ATTR_SLOT | 48,525,920 | 2.7% | 20.1% |
| POP_TOP LOAD_FAST | 42,553,240 | 2.3% | 22.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 38,820,880 | 2.1% | 24.6% |
| CACHE RESUME_CHECK | 38,818,080 | 2.1% | 26.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 38,817,760 | 2.1% | 28.9% |
| LOAD_CONST LOAD_FAST | 37,327,780 | 2.1% | 30.9% |
| STORE_FAST LOAD_FAST | 34,355,280 | 1.9% | 32.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 34,349,280 | 1.9% | 34.7% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 32,098,980 | 1.8% | 36.5% |
| LOAD_FAST LOAD_ATTR | 31,359,500 | 1.7% | 38.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 29,118,200 | 1.6% | 39.8% |
| LOAD_FAST RETURN_VALUE | 29,115,620 | 1.6% | 41.4% |
| LOAD_FAST STORE_ATTR_SLOT | 29,113,800 | 1.6% | 43.0% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 29,113,380 | 1.6% | 44.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 28,369,560 | 1.6% | 46.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 27,623,980 | 1.5% | 47.7% |
| RETURN_CONST INTERPRETER_EXIT | 27,620,880 | 1.5% | 49.3% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 27,619,800 | 1.5% | 50.8% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 24,634,160 | 1.4% | 52.1% |
| RETURN_CONST POP_TOP | 23,893,800 | 1.3% | 53.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 23,141,220 | 1.3% | 54.7% |
| STORE_ATTR_SLOT LOAD_CONST | 19,409,120 | 1.1% | 55.8% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 19,408,720 | 1.1% | 56.9% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 18,664,400 | 1.0% | 57.9% |
| CALL STORE_FAST | 18,662,920 | 1.0% | 58.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 17,918,440 | 1.0% | 59.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 17,172,260 | 0.9% | 60.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 14,930,460 | 0.8% | 61.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 14,930,340 | 0.8% | 62.5% |
| RETURN_VALUE INTERPRETER_EXIT | 14,930,060 | 0.8% | 63.3% |
| RETURN_VALUE STORE_FAST | 14,185,660 | 0.8% | 64.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 14,183,760 | 0.8% | 64.9% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 14,183,600 | 0.8% | 65.7% |
| POP_TOP ENTER_EXECUTOR | 14,182,600 | 0.8% | 66.5% |
| POP_TOP RETURN_CONST | 13,438,040 | 0.7% | 67.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 11,944,980 | 0.7% | 67.9% |
| POP_JUMP_IF_NONE LOAD_FAST | 11,943,920 | 0.7% | 68.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 11,199,120 | 0.6% | 69.1% |
| PUSH_NULL LOAD_FAST | 11,198,080 | 0.6% | 69.8% |
| LOAD_CONST STORE_FAST | 10,458,960 | 0.6% | 70.3% |
| POP_JUMP_IF_FALSE LOAD_CONST | 10,454,480 | 0.6% | 70.9% |
| POP_TOP LOAD_CONST | 10,453,220 | 0.6% | 71.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 10,452,980 | 0.6% | 72.1% |
| BUILD_LIST LOAD_FAST | 10,451,120 | 0.6% | 72.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 9,708,640 | 0.5% | 73.2% |
| STORE_FAST RETURN_CONST | 9,706,000 | 0.5% | 73.7% |
| LOAD_ATTR PUSH_NULL | 9,705,180 | 0.5% | 74.3% |
| RETURN_VALUE TO_BOOL_BOOL | 9,704,960 | 0.5% | 74.8% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 9,704,880 | 0.5% | 75.3% |
| POP_JUMP_IF_TRUE LOAD_FAST | 9,704,660 | 0.5% | 75.9% |
| STORE_ATTR_SLOT LOAD_FAST | 9,704,660 | 0.5% | 76.4% |
| STORE_ATTR_SLOT RETURN_CONST | 9,704,660 | 0.5% | 76.9% |
| CALL_FUNCTION_EX POP_TOP | 9,704,560 | 0.5% | 77.5% |
| LOAD_FAST_LOAD_FAST CALL | 9,704,560 | 0.5% | 78.0% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 9,704,480 | 0.5% | 78.5% |
| POP_TOP RESUME_CHECK | 9,704,440 | 0.5% | 79.1% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 9,704,400 | 0.5% | 79.6% |
| LIST_EXTEND CALL_INTRINSIC_1 | 9,704,400 | 0.5% | 80.1% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 9,704,400 | 0.5% | 80.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 9,704,380 | 0.5% | 81.2% |
| LOAD_ATTR_SLOT BUILD_LIST | 9,704,380 | 0.5% | 81.7% |
| LOAD_ATTR_SLOT LIST_EXTEND | 9,704,380 | 0.5% | 82.3% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 9,704,240 | 0.5% | 82.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 9,704,200 | 0.5% | 83.4% |
| ENTER_EXECUTOR LOAD_ATTR | 9,702,520 | 0.5% | 83.9% |
| LOAD_ATTR CALL | 8,959,540 | 0.5% | 84.4% |
| LOAD_ATTR LOAD_FAST | 8,958,820 | 0.5% | 84.9% |
| CALL RESUME_CHECK | 8,958,340 | 0.5% | 85.4% |
| TO_BOOL POP_JUMP_IF_FALSE | 6,719,300 | 0.4% | 85.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 6,718,880 | 0.4% | 86.1% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NOT_NONE | 6,718,340 | 0.4% | 86.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 5,976,440 | 0.3% | 86.8% |
| LOAD_FAST LOAD_CONST | 5,974,380 | 0.3% | 87.1% |
| GET_AWAITABLE LOAD_CONST | 5,972,080 | 0.3% | 87.5% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 5,228,660 | 0.3% | 87.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 5,228,580 | 0.3% | 88.0% |
| PUSH_NULL CALL | 5,228,340 | 0.3% | 88.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 5,227,220 | 0.3% | 88.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 5,227,160 | 0.3% | 88.9% |
| CALL POP_TOP | 5,226,140 | 0.3% | 89.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 5,226,060 | 0.3% | 89.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,225,980 | 0.3% | 89.8% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 5,225,760 | 0.3% | 90.1% |
| END_SEND POP_TOP | 5,225,600 | 0.3% | 90.4% |
| LOAD_CONST CALL_KW | 5,225,600 | 0.3% | 90.6% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 5,225,580 | 0.3% | 90.9% |
| SEND_GEN POP_TOP | 5,225,500 | 0.3% | 91.2% |
| LOAD_CONST SEND_GEN | 5,225,440 | 0.3% | 91.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 4,482,600 | 0.2% | 91.8% |
| STORE_FAST JUMP_FORWARD | 4,482,480 | 0.2% | 92.0% |
| JUMP_FORWARD LOAD_FAST | 4,480,960 | 0.2% | 92.2% |
| LOAD_CONST COMPARE_OP_INT | 4,480,920 | 0.2% | 92.5% |
| LOAD_FAST CALL | 4,480,760 | 0.2% | 92.7% |
| TO_BOOL POP_JUMP_IF_TRUE | 4,480,720 | 0.2% | 93.0% |
| LOAD_FAST PUSH_NULL | 4,479,380 | 0.2% | 93.2% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 4,479,260 | 0.2% | 93.5% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 38,818,080 | 86.7% |
| POP_TOP | 4,478,960 | 10.0% |
| RETURN_GENERATOR | 1,492,960 | 3.3% |
| RESUME | 260 | 0.0% |
| COPY_FREE_VARS | 120 | 0.0% |


</details>

### BEFORE_ASYNC_WITH

<details>
<summary> Successors and predecessors for BEFORE_ASYNC_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 746,460 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 746,480 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 40 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 20 | 50.0% |
| BINARY_SUBSCR_DICT | 20 | 50.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160 | 88.9% |
| LOAD_GLOBAL | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 180 | 100.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,479,120 | 75.0% |
| RETURN_VALUE | 746,480 | 12.5% |
| SEND | 746,480 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,225,600 | 87.5% |
| STORE_FAST | 746,480 | 12.5% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 746,580 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 746,580 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 748,100 | 99.5% |
| LOAD_FAST | 3,220 | 0.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 160 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 748,040 | 99.5% |
| FOR_ITER_LIST | 3,160 | 0.4% |
| FOR_ITER | 320 | 0.0% |
| FOR_ITER_TUPLE | 20 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 27,620,880 | 61.7% |
| RETURN_VALUE | 14,930,060 | 33.3% |
| RETURN_GENERATOR | 1,492,960 | 3.3% |
| YIELD_VALUE | 746,480 | 1.7% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 240 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 746,460 | 99.3% |
| RESUME_CHECK | 2,500 | 0.3% |
| STORE_FAST | 1,760 | 0.2% |
| POP_TOP | 400 | 0.1% |
| POP_JUMP_IF_NOT_NONE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 751,000 | 99.9% |
| LOAD_GLOBAL_MODULE | 320 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 100 | 55.6% |
| COPY | 80 | 44.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 100 | 55.6% |
| RERAISE | 80 | 44.4% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 32,098,980 | 35.5% |
| RETURN_CONST | 23,893,800 | 26.5% |
| CALL_FUNCTION_EX | 9,704,560 | 10.7% |
| CALL | 5,226,140 | 5.8% |
| END_SEND | 5,225,600 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,553,240 | 47.1% |
| ENTER_EXECUTOR | 14,182,600 | 15.7% |
| RETURN_CONST | 13,438,040 | 14.9% |
| LOAD_CONST | 10,453,220 | 11.6% |
| RESUME_CHECK | 9,704,440 | 10.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 80 | 44.4% |
| BINARY_SUBSCR_DICT | 80 | 44.4% |
| BINARY_SUBSCR | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160 | 88.9% |
| LOAD_GLOBAL | 20 | 11.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 17,172,260 | 54.8% |
| LOAD_ATTR | 9,705,180 | 31.0% |
| LOAD_FAST | 4,479,380 | 14.3% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 14,183,600 | 45.2% |
| LOAD_FAST | 11,198,080 | 35.7% |
| CALL | 5,228,340 | 16.7% |
| CALL_ALLOC_AND_ENTER_INIT | 746,480 | 2.4% |
| LOAD_CONST | 240 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,479,260 | 46.2% |
| ENTER_EXECUTOR | 3,732,120 | 38.5% |
| CACHE | 1,492,960 | 15.4% |
| CALL | 80 | 0.0% |
| COPY_FREE_VARS | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 4,478,920 | 46.2% |
| GET_AWAITABLE | 3,732,640 | 38.5% |
| INTERPRETER_EXIT | 1,492,960 | 15.4% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,115,620 | 63.9% |
| LOAD_ATTR_INSTANCE_VALUE | 14,930,340 | 32.8% |
| EXIT_INIT_CHECK | 746,580 | 1.6% |
| CALL_KW | 746,480 | 1.6% |
| CALL | 1,900 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 14,930,060 | 32.8% |
| STORE_FAST | 14,185,660 | 31.1% |
| TO_BOOL_BOOL | 9,704,960 | 21.3% |
| POP_TOP | 4,479,120 | 9.8% |
| LOAD_FAST | 748,140 | 1.6% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 40 | 66.7% |
| LOAD_FAST | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 33.3% |
| LOAD_FAST | 20 | 33.3% |
| STORE_SUBSCR_DICT | 20 | 33.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 11,199,120 | 99.9% |
| TO_BOOL | 3,800 | 0.0% |
| LOAD_ATTR | 620 | 0.0% |
| RETURN_VALUE | 480 | 0.0% |
| COPY | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,719,300 | 60.0% |
| POP_JUMP_IF_TRUE | 4,480,720 | 40.0% |
| TO_BOOL | 3,800 | 0.0% |
| TO_BOOL_BOOL | 840 | 0.0% |
| TO_BOOL_INT | 160 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 80 | 50.0% |
| LOAD_ATTR_MODULE | 60 | 37.5% |
| LOAD_ATTR | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 160 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 60 | 37.5% |
| TO_BOOL_INT | 60 | 37.5% |
| TO_BOOL | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180 | 22.5% |
| UNARY_INVERT | 160 | 20.0% |
| BINARY_OP | 120 | 15.0% |
| LOAD_CONST | 120 | 15.0% |
| POP_JUMP_IF_FALSE | 80 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 25.0% |
| COPY | 160 | 20.0% |
| BINARY_OP | 120 | 15.0% |
| UNARY_INVERT | 80 | 10.0% |
| TO_BOOL | 40 | 5.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 9,704,380 | 92.8% |
| STORE_ATTR_INSTANCE_VALUE | 746,680 | 7.1% |
| STORE_FAST | 1,600 | 0.0% |
| STORE_ATTR | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,451,120 | 100.0% |
| STORE_FAST | 1,600 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 80 | 25.0% |
| BUILD_TUPLE | 80 | 25.0% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 25.0% |
| RESUME_CHECK | 60 | 18.8% |
| RESUME | 20 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 37.5% |
| CALL | 80 | 12.5% |
| LOAD_CONST | 80 | 12.5% |
| LOAD_FAST_LOAD_FAST | 80 | 12.5% |
| LOAD_GLOBAL_MODULE | 80 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 37.5% |
| CALL | 160 | 25.0% |
| RETURN_VALUE | 80 | 12.5% |
| BUILD_MAP | 80 | 12.5% |
| CALL_ISINSTANCE | 40 | 6.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,704,560 | 25.5% |
| LOAD_ATTR | 8,959,540 | 23.5% |
| PUSH_NULL | 5,228,340 | 13.7% |
| LOAD_FAST | 4,480,760 | 11.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,479,100 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,662,920 | 49.0% |
| RESUME_CHECK | 8,958,340 | 23.5% |
| POP_TOP | 5,226,140 | 13.7% |
| CALL_METHOD_DESCRIPTOR_O | 4,479,100 | 11.8% |
| LOAD_FAST | 747,140 | 2.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 9,704,400 | 100.0% |
| DICT_MERGE | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 9,704,560 | 100.0% |
| COPY_FREE_VARS | 80 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 9,704,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 9,704,400 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,225,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,478,960 | 85.7% |
| RETURN_VALUE | 746,480 | 14.3% |
| POP_TOP | 80 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |
| RESUME | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 220 | 44.0% |
| CALL_BUILTIN_CLASS | 140 | 28.0% |
| COMPARE_OP | 40 | 8.0% |
| RETURN_VALUE | 20 | 4.0% |
| CALL | 20 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 320 | 64.0% |
| COMPARE_OP_INT | 120 | 24.0% |
| COMPARE_OP | 40 | 8.0% |
| COPY | 20 | 4.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 60 | 37.5% |
| LOAD_GLOBAL_MODULE | 60 | 37.5% |
| LOAD_ATTR | 20 | 12.5% |
| LOAD_GLOBAL | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 160 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,580 | 67.5% |
| BINARY_OP | 160 | 6.8% |
| LOAD_FAST | 160 | 6.8% |
| CALL_BUILTIN_FAST | 140 | 6.0% |
| UNARY_NOT | 80 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 1,640 | 70.1% |
| TO_BOOL | 240 | 10.3% |
| TO_BOOL_BOOL | 200 | 8.5% |
| POP_EXCEPT | 80 | 3.4% |
| LOAD_ATTR | 80 | 3.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 640 | 60.4% |
| CALL | 160 | 15.1% |
| CACHE | 120 | 11.3% |
| CALL_FUNCTION_EX | 80 | 7.5% |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 700 | 66.0% |
| RESUME | 200 | 18.9% |
| RETURN_GENERATOR | 80 | 7.5% |
| MAKE_CELL | 80 | 7.5% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,182,600 | 100.0% |
| POP_JUMP_IF_FALSE | 1,200 | 0.0% |
| JUMP_BACKWARD | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 9,702,520 | 68.4% |
| RETURN_GENERATOR | 3,732,120 | 26.3% |
| LOAD_CONST | 748,000 | 5.3% |
| RESUME_CHECK | 1,200 | 0.0% |
| LOAD_FAST | 20 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 320 | 72.7% |
| FOR_ITER | 80 | 18.2% |
| JUMP_BACKWARD | 40 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 27.3% |
| LOAD_FAST | 100 | 22.7% |
| FOR_ITER | 80 | 18.2% |
| FOR_ITER_LIST | 60 | 13.6% |
| STORE_FAST | 40 | 9.1% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 3,732,640 | 62.5% |
| BEFORE_ASYNC_WITH | 746,480 | 12.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 746,460 | 12.5% |
| LOAD_ATTR_INSTANCE_VALUE | 746,460 | 12.5% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,972,080 | 100.0% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20 | 100.0% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 80.0% |
| IMPORT_FROM | 20 | 20.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 746,460 | 99.9% |
| LOAD_CONST | 400 | 0.1% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 746,480 | 99.9% |
| RETURN_VALUE | 400 | 0.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 680 | 65.4% |
| POP_JUMP_IF_FALSE | 360 | 34.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 600 | 57.7% |
| LOAD_FAST | 340 | 32.7% |
| ENTER_EXECUTOR | 60 | 5.8% |
| FOR_ITER | 40 | 3.8% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,493,040 | 100.0% |
| RESUME | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 746,600 | 50.0% |
| SEND | 746,520 | 50.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,482,480 | 100.0% |
| POP_TOP | 100 | 0.0% |
| POP_JUMP_IF_FALSE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,480,960 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 1,560 | 0.0% |
| NOP | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_FAST_CHECK | 20 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 9,704,380 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 9,704,400 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,359,500 | 73.7% |
| ENTER_EXECUTOR | 9,702,520 | 22.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,493,520 | 3.5% |
| LOAD_ATTR | 13,640 | 0.0% |
| LOAD_ATTR_SLOT | 1,960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 9,705,180 | 22.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,704,240 | 22.8% |
| CALL | 8,959,540 | 21.0% |
| LOAD_FAST | 8,958,820 | 21.0% |
| TO_BOOL_NONE | 4,478,920 | 10.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 19,409,120 | 28.9% |
| POP_JUMP_IF_FALSE | 10,454,480 | 15.6% |
| POP_TOP | 10,453,220 | 15.6% |
| LOAD_FAST | 5,974,380 | 8.9% |
| GET_AWAITABLE | 5,972,080 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,327,780 | 55.5% |
| STORE_FAST | 10,458,960 | 15.6% |
| CALL_KW | 5,225,600 | 7.8% |
| SEND_GEN | 5,225,440 | 7.8% |
| COMPARE_OP_INT | 4,480,920 | 6.7% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 620 | 50.8% |
| LOAD_GLOBAL | 200 | 16.4% |
| STORE_FAST | 160 | 13.1% |
| NOP | 80 | 6.6% |
| LOAD_ATTR_METHOD_NO_DICT | 80 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 820 | 67.2% |
| LOAD_CONST | 160 | 13.1% |
| PUSH_NULL | 80 | 6.6% |
| POP_JUMP_IF_NOT_NONE | 80 | 6.6% |
| STORE_FAST | 80 | 6.6% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 76,148,020 | 20.2% |
| POP_JUMP_IF_FALSE | 68,683,900 | 18.3% |
| POP_TOP | 42,553,240 | 11.3% |
| LOAD_CONST | 37,327,780 | 9.9% |
| STORE_FAST | 34,355,280 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 117,967,880 | 31.3% |
| LOAD_ATTR_SLOT | 48,525,920 | 12.9% |
| LOAD_ATTR | 31,359,500 | 8.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 29,118,200 | 7.7% |
| RETURN_VALUE | 29,115,620 | 7.7% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 20 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 29,113,380 | 35.8% |
| LOAD_FAST_LOAD_FAST | 14,183,760 | 17.4% |
| PUSH_NULL | 14,183,600 | 17.4% |
| POP_JUMP_IF_NOT_NONE | 9,704,400 | 11.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,704,380 | 11.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 38,817,760 | 47.7% |
| LOAD_FAST_LOAD_FAST | 14,183,760 | 17.4% |
| LOAD_FAST | 9,704,880 | 11.9% |
| CALL | 9,704,560 | 11.9% |
| LOAD_ATTR_INSTANCE_VALUE | 4,479,120 | 5.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME | 500 | 12.7% |
| RESUME_CHECK | 480 | 12.2% |
| POP_TOP | 460 | 11.7% |
| LOAD_FAST | 420 | 10.7% |
| STORE_FAST | 320 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,300 | 33.0% |
| LOAD_ATTR | 820 | 20.8% |
| LOAD_GLOBAL_BUILTIN | 600 | 15.2% |
| LOAD_FAST | 320 | 8.1% |
| CALL | 260 | 6.6% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 180 | 47.4% |
| CALL | 120 | 31.6% |
| LOAD_FAST | 60 | 15.8% |
| LOAD_FAST_LOAD_FAST | 20 | 5.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 53,007,580 | 55.9% |
| TO_BOOL_NONE | 24,634,160 | 26.0% |
| TO_BOOL | 6,719,300 | 7.1% |
| TO_BOOL_LIST | 5,228,660 | 5.5% |
| COMPARE_OP_INT | 4,482,600 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 68,683,900 | 72.4% |
| RETURN_CONST | 14,930,460 | 15.7% |
| LOAD_CONST | 10,454,480 | 11.0% |
| LOAD_GLOBAL_MODULE | 746,640 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 1,580 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,718,880 | 56.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,225,580 | 43.7% |
| CALL | 160 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,943,920 | 100.0% |
| RETURN_CONST | 480 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,664,400 | 73.5% |
| LOAD_ATTR_INSTANCE_VALUE | 6,718,340 | 26.5% |
| LOAD_GLOBAL_MODULE | 220 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,704,400 | 38.2% |
| LOAD_FAST | 5,227,220 | 20.6% |
| LOAD_GLOBAL_MODULE | 5,225,760 | 20.6% |
| RETURN_CONST | 4,478,880 | 17.6% |
| LOAD_CONST | 746,500 | 2.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,225,980 | 53.8% |
| TO_BOOL | 4,480,720 | 46.2% |
| TO_BOOL_INT | 1,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,704,660 | 100.0% |
| LOAD_CONST | 1,680 | 0.0% |
| STORE_FAST | 1,600 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| POP_TOP | 80 | 0.0% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 80 | 100.0% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 80 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,930,460 | 26.3% |
| POP_TOP | 13,438,040 | 23.7% |
| STORE_FAST | 9,706,000 | 17.1% |
| STORE_ATTR_SLOT | 9,704,660 | 17.1% |
| POP_JUMP_IF_NOT_NONE | 4,478,880 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 27,620,880 | 48.7% |
| POP_TOP | 23,893,800 | 42.1% |
| END_SEND | 4,479,120 | 7.9% |
| EXIT_INIT_CHECK | 746,580 | 1.3% |
| TO_BOOL | 40 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 746,640 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 746,520 | 50.0% |
| SEND | 560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 746,480 | 50.0% |
| YIELD_VALUE | 746,480 | 50.0% |
| SEND | 560 | 0.0% |
| POP_TOP | 100 | 0.0% |
| SEND_GEN | 100 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,700 | 77.1% |
| LOAD_FAST_LOAD_FAST | 300 | 8.6% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 8.0% |
| STORE_ATTR | 100 | 2.9% |
| SWAP | 80 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,260 | 36.0% |
| LOAD_FAST | 580 | 16.6% |
| LOAD_CONST | 500 | 14.3% |
| RETURN_CONST | 500 | 14.3% |
| STORE_ATTR_SLOT | 260 | 7.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 18,662,920 | 37.9% |
| RETURN_VALUE | 14,185,660 | 28.8% |
| LOAD_CONST | 10,458,960 | 21.2% |
| CALL_KW | 4,478,960 | 9.1% |
| FOR_ITER_RANGE | 748,600 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,355,280 | 69.7% |
| RETURN_CONST | 9,706,000 | 19.7% |
| JUMP_FORWARD | 4,482,480 | 9.1% |
| LOAD_GLOBAL_BUILTIN | 748,060 | 1.5% |
| NOP | 1,760 | 0.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 20 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 75.0% |
| UNPACK_SEQUENCE | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 50.0% |
| LOAD_GLOBAL | 40 | 25.0% |
| LOAD_GLOBAL_MODULE | 40 | 25.0% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 80 | 23.5% |
| LOAD_FAST | 80 | 23.5% |
| BINARY_OP_ADD_INT | 60 | 17.6% |
| BINARY_OP_SUBTRACT_INT | 60 | 17.6% |
| BINARY_OP | 40 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 100 | 29.4% |
| STORE_ATTR | 80 | 23.5% |
| STORE_FAST | 80 | 23.5% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 23.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 33.3% |
| CALL | 40 | 33.3% |
| STORE_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 50.0% |
| STORE_FAST_STORE_FAST | 40 | 33.3% |
| LOAD_FAST | 20 | 16.7% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 746,640 | 50.0% |
| SEND | 746,480 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 746,640 | 50.0% |
| INTERPRETER_EXIT | 746,480 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,060 | 61.6% |
| CACHE | 260 | 15.1% |
| COPY_FREE_VARS | 200 | 11.6% |
| POP_TOP | 120 | 7.0% |
| SEND_GEN | 40 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800 | 46.5% |
| LOAD_GLOBAL | 500 | 29.1% |
| LOAD_CONST | 140 | 8.1% |
| NOP | 100 | 5.8% |
| JUMP_BACKWARD_NO_INTERRUPT | 80 | 4.7% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,560 | 98.7% |
| BINARY_OP | 20 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,580 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 100.0% |


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
| LOAD_CONST | 746,760 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 746,720 | 100.0% |
| SWAP | 60 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 57.1% |
| LOAD_FAST | 40 | 28.6% |
| BINARY_SUBSCR | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 80 | 57.1% |
| RETURN_VALUE | 60 | 42.9% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20 | 100.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 746,480 | 100.0% |
| CALL | 60 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 746,520 | 100.0% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 746,440 | 98.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,340 | 1.9% |
| PUSH_NULL | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 746,460 | 98.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 14,340 | 1.9% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 746,660 | 49.9% |
| LOAD_GLOBAL_MODULE | 746,440 | 49.9% |
| LOAD_FAST | 1,740 | 0.1% |
| CALL | 180 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 748,100 | 50.0% |
| LOAD_FAST | 746,700 | 49.9% |
| COMPARE_OP | 140 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 75.0% |
| CALL | 40 | 16.7% |
| LOAD_FAST_LOAD_FAST | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 140 | 58.3% |
| TO_BOOL_BOOL | 80 | 33.3% |
| TO_BOOL | 20 | 8.3% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 746,440 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 746,460 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 40 | 33.3% |
| LOAD_CONST | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 380 | 73.1% |
| CALL | 60 | 11.5% |
| BUILD_TUPLE | 40 | 7.7% |
| LOAD_GLOBAL_MODULE | 40 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 460 | 88.5% |
| TO_BOOL | 60 | 11.5% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,680 | 98.7% |
| CALL | 60 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,160 | 66.7% |
| COPY | 1,580 | 33.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 120 | 60.0% |
| RETURN_VALUE | 40 | 20.0% |
| CALL | 40 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 140 | 70.0% |
| STORE_FAST | 60 | 30.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,560 | 87.6% |
| LOAD_CONST | 80 | 4.5% |
| CALL | 60 | 3.4% |
| LOAD_ATTR | 40 | 2.2% |
| LOAD_FAST | 40 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,580 | 88.8% |
| POP_TOP | 120 | 6.7% |
| RETURN_VALUE | 80 | 4.5% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 9,704,240 | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT | 2,280 | 0.0% |
| CALL | 360 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 9,704,200 | 100.0% |
| STORE_FAST | 1,860 | 0.0% |
| POP_TOP | 380 | 0.0% |
| GET_ITER | 160 | 0.0% |
| CALL | 140 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,619,800 | 86.0% |
| CALL | 4,479,100 | 14.0% |
| LOAD_CONST | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 32,098,980 | 100.0% |
| LOAD_CONST | 20 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 28,369,560 | 73.1% |
| LOAD_FAST | 9,708,640 | 25.0% |
| BINARY_OP_SUBTRACT_INT | 746,720 | 1.9% |
| LOAD_ATTR_METHOD_NO_DICT | 1,960 | 0.0% |
| CALL | 1,460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 34,349,280 | 88.5% |
| RETURN_GENERATOR | 4,479,260 | 11.5% |
| COPY_FREE_VARS | 640 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 120 | 31.6% |
| CALL | 100 | 26.3% |
| LOAD_FAST | 80 | 21.1% |
| PUSH_NULL | 40 | 10.5% |
| LOAD_CONST | 40 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 380 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,480,920 | 100.0% |
| LOAD_GLOBAL_MODULE | 1,560 | 0.0% |
| COMPARE_OP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,482,600 | 100.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,160 | 98.1% |
| FOR_ITER | 60 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,640 | 50.9% |
| LOAD_FAST | 1,580 | 49.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 748,040 | 99.9% |
| JUMP_BACKWARD | 600 | 0.1% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 748,600 | 100.0% |
| LOAD_CONST | 80 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20 | 100.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 85.7% |
| LOAD_ATTR | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,967,880 | 96.3% |
| LOAD_FAST_LOAD_FAST | 4,479,120 | 3.7% |
| LOAD_ATTR | 1,780 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 38,820,880 | 31.7% |
| LOAD_ATTR_METHOD_NO_DICT | 27,623,980 | 22.6% |
| RETURN_VALUE | 14,930,340 | 12.2% |
| TO_BOOL | 11,199,120 | 9.1% |
| POP_JUMP_IF_NOT_NONE | 6,718,340 | 5.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 27,623,980 | 100.0% |
| LOAD_FAST | 2,200 | 0.0% |
| LOAD_ATTR | 540 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,141,220 | 83.8% |
| LOAD_GLOBAL_MODULE | 4,478,960 | 16.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,280 | 0.0% |
| CALL_PY_EXACT_ARGS | 1,960 | 0.0% |
| LOAD_FAST_LOAD_FAST | 1,720 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,118,200 | 66.1% |
| LOAD_ATTR_SLOT | 9,704,480 | 22.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,227,160 | 11.9% |
| LOAD_ATTR | 1,100 | 0.0% |
| RETURN_VALUE | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 28,369,560 | 64.4% |
| LOAD_FAST_LOAD_FAST | 9,704,380 | 22.0% |
| LOAD_FAST | 5,976,440 | 13.6% |
| CALL | 620 | 0.0% |
| LOAD_CONST | 120 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 17,918,440 | 100.0% |
| LOAD_ATTR | 840 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 17,172,260 | 95.8% |
| IS_OP | 746,460 | 4.2% |
| LOAD_ATTR | 280 | 0.0% |
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
| LOAD_FAST | 48,525,920 | 100.0% |
| LOAD_ATTR | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 19,408,720 | 40.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,704,480 | 20.0% |
| BUILD_LIST | 9,704,380 | 20.0% |
| LIST_EXTEND | 9,704,380 | 20.0% |
| LOAD_ATTR | 1,960 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 748,060 | 49.8% |
| STORE_ATTR_INSTANCE_VALUE | 746,580 | 49.7% |
| RESUME_CHECK | 2,640 | 0.2% |
| POP_JUMP_IF_FALSE | 1,580 | 0.1% |
| JUMP_FORWARD | 1,560 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 746,660 | 49.7% |
| LOAD_GLOBAL_MODULE | 746,480 | 49.7% |
| LOAD_FAST | 7,620 | 0.5% |
| LOAD_DEREF | 620 | 0.0% |
| CALL_ISINSTANCE | 380 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,452,980 | 45.2% |
| POP_JUMP_IF_NOT_NONE | 5,225,760 | 22.6% |
| LOAD_ATTR_METHOD_NO_DICT | 4,478,960 | 19.3% |
| LOAD_FAST | 748,240 | 3.2% |
| STORE_ATTR_INSTANCE_VALUE | 746,800 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 17,918,440 | 77.4% |
| LOAD_FAST_LOAD_FAST | 4,479,200 | 19.3% |
| CALL_BUILTIN_CLASS | 746,440 | 3.2% |
| COMPARE_OP_INT | 1,560 | 0.0% |
| LOAD_ATTR | 840 | 0.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 440 | 71.0% |
| LOAD_SUPER_ATTR | 180 | 29.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 260 | 41.9% |
| CALL_PY_EXACT_ARGS | 200 | 32.3% |
| CALL | 100 | 16.1% |
| LOAD_FAST_LOAD_FAST | 60 | 9.7% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 38,818,080 | 41.6% |
| CALL_PY_EXACT_ARGS | 34,349,280 | 36.8% |
| POP_TOP | 9,704,440 | 10.4% |
| CALL | 8,958,340 | 9.6% |
| SEND_GEN | 746,600 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 76,148,020 | 81.6% |
| LOAD_GLOBAL_MODULE | 10,452,980 | 11.2% |
| RETURN_CONST | 3,732,460 | 4.0% |
| LOAD_CONST | 1,493,380 | 1.6% |
| JUMP_BACKWARD_NO_INTERRUPT | 1,493,040 | 1.6% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,225,440 | 87.5% |
| JUMP_BACKWARD_NO_INTERRUPT | 746,600 | 12.5% |
| SEND | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,225,500 | 87.5% |
| RESUME_CHECK | 746,600 | 12.5% |
| RESUME | 40 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,944,980 | 100.0% |
| STORE_ATTR | 1,260 | 0.0% |
| LOAD_FAST_LOAD_FAST | 260 | 0.0% |
| SWAP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,226,060 | 43.7% |
| LOAD_FAST | 2,986,600 | 25.0% |
| RETURN_CONST | 747,120 | 6.3% |
| LOAD_GLOBAL_MODULE | 746,800 | 6.3% |
| BUILD_LIST | 746,680 | 6.3% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 38,817,760 | 57.1% |
| LOAD_FAST | 29,113,800 | 42.9% |
| STORE_ATTR | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 29,113,380 | 42.9% |
| LOAD_CONST | 19,409,120 | 28.6% |
| LOAD_FAST | 9,704,660 | 14.3% |
| RETURN_CONST | 9,704,660 | 14.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 40 | 66.7% |
| STORE_SUBSCR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 38,820,880 | 66.7% |
| RETURN_VALUE | 9,704,960 | 16.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,704,200 | 16.7% |
| LOAD_ATTR_SLOT | 1,880 | 0.0% |
| TO_BOOL | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 53,007,580 | 91.0% |
| POP_JUMP_IF_TRUE | 5,225,980 | 9.0% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,640 | 83.7% |
| TO_BOOL | 160 | 8.2% |
| LOAD_FAST | 80 | 4.1% |
| BINARY_OP | 40 | 2.0% |
| LOAD_ATTR | 40 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,640 | 83.7% |
| POP_JUMP_IF_FALSE | 260 | 13.3% |
| UNARY_NOT | 60 | 3.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,228,580 | 100.0% |
| TO_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,228,660 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 19,408,720 | 78.8% |
| LOAD_ATTR | 4,478,920 | 18.2% |
| LOAD_FAST | 746,440 | 3.0% |
| TO_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 24,634,160 | 100.0% |


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
|     deferred | 580 | 0.1% |
|          hit | 748,500 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 45.5% |
| Failure | 120 | 54.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 80 | 66.7% |
| or | 40 | 33.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 7.1% |
|          hit | 240 | 85.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 38,063,500 | 31.1% |
|          hit | 83,631,220 | 68.3% |
|         miss | 761,180 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 17,020 | 59.2% |
| Failure | 11,740 | 40.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 3,000 | 25.6% |
| code complex parameters | 2,620 | 22.3% |
| no dict | 2,580 | 22.0% |
| class no vectorcall | 1,340 | 11.4% |
| other | 1,280 | 10.9% |
| cfunc noargs | 660 | 5.6% |
| class mutable | 80 | 0.7% |
| wrong number arguments | 40 | 0.3% |
| cfunc varargs | 40 | 0.3% |
| operator wrapper | 40 | 0.3% |
| cmethod | 20 | 0.2% |
| cfunc varargs keywords | 20 | 0.2% |
| init not simple | 20 | 0.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 340 | 0.0% |
|          hit | 4,482,620 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 75.0% |
| Failure | 40 | 25.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bool | 40 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 260 | 0.0% |
|          hit | 751,920 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 55.6% |
| Failure | 80 | 44.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 80 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 42,556,320 | 14.0% |
|          hit | 260,572,840 | 86.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 4,540 | 26.2% |
| Failure | 12,820 | 73.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 7,280 | 56.8% |
| method | 3,980 | 31.0% |
| class attr descriptor | 1,280 | 10.0% |
| not managed dict | 140 | 1.1% |
| metaclass attribute | 60 | 0.5% |
| non object slot | 40 | 0.3% |
| class attr simple | 40 | 0.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,120 | 0.0% |
|        deopt | 80 | 0.0% |
|          hit | 24,650,500 | 100.0% |
|         miss | 80 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,900 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 20.0% |
|          hit | 620 | 62.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
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
|     deferred | 1,493,060 | 20.0% |
|          hit | 5,972,140 | 80.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 15.2% |
| Failure | 560 | 84.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 560 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,880 | 0.0% |
|          hit | 79,878,400 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,520 | 93.8% |
| Failure | 100 | 6.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overridden | 80 | 80.0% |
| overriding descriptor | 20 | 20.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 33.3% |
|          hit | 60 | 50.0% |

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
|     deferred | 11,200,060 | 11.3% |
|          hit | 88,098,400 | 88.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,160 | 23.4% |
| Failure | 3,800 | 76.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 3,700 | 97.4% |
| sequence | 100 | 2.6% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 20.0% |
|          hit | 180 | 60.0% |

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
| Basic | 934,781,000 | 51.6% |
| Not specialized | 235,230,400 | 13.0% |
| Specialized hits | 642,086,940 | 35.4% |
| Specialized misses | 787,640 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 42,556,320 | 45.6% |
| CALL | 38,063,500 | 40.8% |
| TO_BOOL | 11,200,060 | 12.0% |
| SEND | 1,493,060 | 1.6% |
| LOAD_GLOBAL | 2,120 | 0.0% |
| STORE_ATTR | 1,880 | 0.0% |
| BINARY_OP | 580 | 0.0% |
| COMPARE_OP | 340 | 0.0% |
| FOR_ITER | 260 | 0.0% |
| LOAD_SUPER_ATTR | 200 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 760,800 | 93.5% |
| RESUME | 26,380 | 3.2% |
| RESUME_CHECK | 26,380 | 3.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 260 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| CACHE | 0 | 0.0% |
| BEFORE_ASYNC_WITH | 0 | 0.0% |
| BEFORE_WITH | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 44,790,380 | 45.1% |
| Calls to Python functions inlined | 54,508,320 | 54.9% |
| Calls via PyEval_EvalFrame (total) | 44,790,380 | 45.1% |
| Calls via PyEval_EvalFrame (vector) | 39,564,940 | 39.8% |
| Calls via PyEval_EvalFrame (generator) | 5,225,440 | 5.3% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 39,564,940 | 39.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 4,479,100 | 4.5% |
| Calls via PyEval_EvalFrame (method) | 19,408,800 | 19.5% |
| Frame objects created | 180 | 0.0% |
| Frames pushed | 53,758,700 | 54.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 50,789,300 | 34.0% |
| Frees to freelist | 50,957,040 |  |
| Allocations | 98,756,106 | 66.0% |
| Allocations to 512 bytes | 97,951,040 | 65.5% |
| Allocations to 4 kbytes | 804,960 | 0.5% |
| Allocations over 4 kbytes | 106 | 0.0% |
| Frees | 98,712,955 |  |
| New values | 320 |  |
| Interpreter increfs | 1,079,545,340 | 79.4% |
| Interpreter decrefs | 1,141,301,460 | 76.5% |
| Increfs | 280,697,275 | 20.6% |
| Decrefs | 350,973,744 | 23.5% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 61,981,758 |  |
| Method cache misses | 3,622 |  |
| Method cache collisions | 3,360 |  |
| Method cache dunder hits | 11,198,763 |  |
| Method cache dunder misses | 437 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 51,300 | 2,040 | 274,615,160 |
| 1 | 4,660 | 0 | 297,804,000 |
| 2 | 400 | 0 | 829,001,600 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 60 |  |
| Traces created | 60 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 20 | 33.3% |
| Traces executed | 14,183,860 |  |
| Uops executed | 619,510,500 | 43.68 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 33.3% |
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 33.3% |
| <= 128 | 20 | 33.3% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 33.3% |
| <= 32 | 0 | 0.0% |
| <= 64 | 40 | 66.7% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 748,020 | 5.3% |
| <= 16 | 1,200 | 0.0% |
| <= 32 | 3,732,120 | 26.3% |
| <= 64 | 9,702,520 | 68.4% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 150,025,120 | 24.2% | 24.2% |  |
| _GUARD_TYPE_VERSION | 65,680,560 | 10.6% | 34.8% |  |
| LOAD_FAST | 59,710,160 | 9.6% | 44.5% |  |
| _POP_JUMP_IF_TRUE | 33,587,700 | 5.4% | 49.9% |  |
| STORE_FAST | 23,137,160 | 3.7% | 53.6% |  |
| TO_BOOL_BOOL | 19,405,040 | 3.1% | 56.7% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 19,405,040 | 3.1% | 59.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 19,405,040 | 3.1% | 63.0% |  |
| _LOAD_ATTR_SLOT | 19,405,040 | 3.1% | 66.1% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 19,405,040 | 3.1% | 69.3% |  |
| _EXIT_TRACE | 14,183,860 | 2.3% | 71.6% |  |
| _ITER_CHECK_RANGE | 14,182,640 | 2.3% | 73.9% |  |
| _IS_ITER_EXHAUSTED_RANGE | 14,182,640 | 2.3% | 76.1% |  |
| _CHECK_PEP_523 | 13,435,840 | 2.2% | 78.3% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 13,435,840 | 2.2% | 80.5% |  |
| _CHECK_STACK_SPACE | 13,435,840 | 2.2% | 82.6% |  |
| _INIT_CALL_PY_EXACT_ARGS | 13,435,840 | 2.2% | 84.8% |  |
| _PUSH_FRAME | 13,435,840 | 2.2% | 87.0% |  |
| _SAVE_RETURN_OFFSET | 13,435,840 | 2.2% | 89.2% |  |
| _ITER_NEXT_RANGE | 13,434,640 | 2.2% | 91.3% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 9,702,520 | 1.6% | 92.9% |  |
| RESUME_CHECK | 9,702,520 | 1.6% | 94.5% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 7,465,440 | 1.2% | 95.7% |  |
| _GUARD_KEYS_VERSION | 7,465,440 | 1.2% | 96.9% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 7,465,440 | 1.2% | 98.1% |  |
| LOAD_CONST | 3,732,120 | 0.6% | 98.7% |  |
| _GUARD_BOTH_INT | 3,732,120 | 0.6% | 99.3% |  |
| _BINARY_OP_SUBTRACT_INT | 3,732,120 | 0.6% | 99.9% |  |
| POP_TOP | 748,020 | 0.1% | 100.0% |  |
| _ITER_CHECK_TUPLE | 20 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 20 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| LOAD_ATTR | 20 |


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
Stats gathered on: 2023-11-03