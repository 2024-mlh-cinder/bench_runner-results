
# Pystats results

- benchmark: async_tree_io
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 820,333,120 | 18.8% | 18.8% |  |
| RESUME_CHECK | 255,019,460 | 5.8% | 24.6% | 0.0% |
| POP_JUMP_IF_FALSE | 237,106,720 | 5.4% | 30.1% |  |
| LOAD_ATTR_SLOT | 234,558,300 | 5.4% | 35.4% | 0.0% |
| TO_BOOL_BOOL | 179,616,140 | 4.1% | 39.5% |  |
| LOAD_FAST_LOAD_FAST | 156,022,040 | 3.6% | 43.1% |  |
| LOAD_CONST | 153,050,260 | 3.5% | 46.6% |  |
| RETURN_VALUE | 147,516,600 | 3.4% | 50.0% |  |
| STORE_ATTR_SLOT | 142,582,940 | 3.3% | 53.3% | 0.0% |
| LOAD_GLOBAL_MODULE | 134,827,100 | 3.1% | 56.4% |  |
| POP_TOP | 134,378,620 | 3.1% | 59.4% |  |
| INTERPRETER_EXIT | 127,354,680 | 2.9% | 62.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 117,230,240 | 2.7% | 65.0% |  |
| STORE_FAST | 106,781,320 | 2.4% | 67.5% |  |
| RETURN_CONST | 105,263,100 | 2.4% | 69.9% |  |
| CALL_PY_EXACT_ARGS | 100,042,440 | 2.3% | 72.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 88,841,380 | 2.0% | 74.2% |  |
| PUSH_NULL | 85,105,220 | 1.9% | 76.2% |  |
| LOAD_GLOBAL_BUILTIN | 75,109,220 | 1.7% | 77.9% | 0.0% |
| LOAD_ATTR | 64,975,040 | 1.5% | 79.4% |  |
| CALL | 64,974,680 | 1.5% | 80.9% |  |
| LOAD_ATTR_MODULE | 62,709,680 | 1.4% | 82.3% |  |
| COMPARE_OP_FLOAT | 57,184,020 | 1.3% | 83.6% |  |
| CALL_ISINSTANCE | 57,183,940 | 1.3% | 84.9% |  |
| LOAD_DEREF | 47,776,100 | 1.1% | 86.0% |  |
| POP_JUMP_IF_NOT_NONE | 43,299,240 | 1.0% | 87.0% |  |
| TO_BOOL_NONE | 42,550,040 | 1.0% | 88.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 38,825,380 | 0.9% | 88.9% | 0.0% |
| ENTER_EXECUTOR | 30,606,340 | 0.7% | 89.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 26,215,940 | 0.6% | 90.2% | 17.4% |
| BUILD_LIST | 23,889,840 | 0.5% | 90.7% |  |
| CALL_METHOD_DESCRIPTOR_O | 22,395,360 | 0.5% | 91.2% | 0.0% |
| SEND_GEN | 22,395,100 | 0.5% | 91.7% |  |
| CALL_FUNCTION_EX | 21,648,560 | 0.5% | 92.2% |  |
| CALL_INTRINSIC_1 | 20,901,840 | 0.5% | 92.7% |  |
| LIST_EXTEND | 20,901,840 | 0.5% | 93.2% |  |
| POP_JUMP_IF_TRUE | 17,173,780 | 0.4% | 93.6% |  |
| END_SEND | 15,676,560 | 0.4% | 93.9% |  |
| RETURN_GENERATOR | 15,676,560 | 0.4% | 94.3% |  |
| GET_AWAITABLE | 15,676,560 | 0.4% | 94.7% |  |
| JUMP_BACKWARD_NO_INTERRUPT | 15,676,560 | 0.4% | 95.0% |  |
| YIELD_VALUE | 15,676,560 | 0.4% | 95.4% |  |
| CALL_KW | 14,183,440 | 0.3% | 95.7% |  |
| POP_JUMP_IF_NONE | 13,437,680 | 0.3% | 96.0% |  |
| NOP | 12,695,800 | 0.3% | 96.3% |  |
| COPY_FREE_VARS | 12,691,380 | 0.3% | 96.6% |  |
| STORE_DEREF | 12,690,160 | 0.3% | 96.9% |  |
| COMPARE_OP_INT | 8,961,940 | 0.2% | 97.1% |  |
| SEND | 8,960,700 | 0.2% | 97.3% |  |
| BINARY_OP_ADD_INT | 8,957,780 | 0.2% | 97.5% |  |
| CALL_LIST_APPEND | 8,957,720 | 0.2% | 97.7% |  |
| LOAD_SUPER_ATTR_METHOD | 8,212,000 | 0.2% | 97.9% |  |
| CALL_BUILTIN_FAST | 8,211,580 | 0.2% | 98.1% |  |
| TO_BOOL | 5,231,740 | 0.1% | 98.2% |  |
| STORE_ATTR | 5,230,080 | 0.1% | 98.3% |  |
| CONTAINS_OP | 5,225,800 | 0.1% | 98.4% |  |
| TO_BOOL_LIST | 4,483,200 | 0.1% | 98.5% |  |
| JUMP_FORWARD | 4,483,140 | 0.1% | 98.6% |  |
| COPY | 4,481,460 | 0.1% | 98.8% |  |
| BUILD_MAP | 4,479,280 | 0.1% | 98.9% |  |
| IS_OP | 4,479,280 | 0.1% | 99.0% |  |
| CALL_TYPE_1 | 4,478,940 | 0.1% | 99.1% |  |
| STORE_SUBSCR_DICT | 4,478,920 | 0.1% | 99.2% |  |
| LIST_APPEND | 4,478,880 | 0.1% | 99.3% |  |
| COMPARE_OP | 3,734,440 | 0.1% | 99.3% |  |
| BINARY_OP_ADD_FLOAT | 3,734,280 | 0.1% | 99.4% |  |
| CALL_BUILTIN_O | 3,733,040 | 0.1% | 99.5% |  |
| CALL_PY_WITH_DEFAULTS | 3,732,840 | 0.1% | 99.6% |  |
| MAKE_CELL | 3,732,480 | 0.1% | 99.7% |  |
| GET_ITER | 2,991,700 | 0.1% | 99.8% |  |
| SWAP | 2,239,780 | 0.1% | 99.8% |  |
| FOR_ITER_LIST | 1,496,940 | 0.0% | 99.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 749,680 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 749,000 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 748,920 | 0.0% | 99.9% |  |
| BUILD_TUPLE | 747,120 | 0.0% | 99.9% |  |
| BINARY_OP_SUBTRACT_INT | 746,800 | 0.0% | 99.9% |  |
| FOR_ITER_TUPLE | 746,800 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 746,720 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 746,720 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 746,480 | 0.0% | 100.0% |  |
| CALL_LEN | 5,460 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 4,540 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 2,200 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 2,060 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,020 | 0.0% | 100.0% |  |
| RESUME | 1,920 | 0.0% | 100.0% | 4,761.8% |
| BINARY_OP | 1,160 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 660 | 0.0% | 100.0% |  |
| FOR_ITER | 560 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 500 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 200 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 180 | 0.0% | 100.0% |  |
| POP_EXCEPT | 180 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 180 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 160 | 0.0% | 100.0% |  |
| UNARY_INVERT | 160 | 0.0% | 100.0% |  |
| UNARY_NOT | 160 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 160 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 140 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 140 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 120 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 100 | 0.0% | 100.0% |  |
| IMPORT_NAME | 100 | 0.0% | 100.0% |  |
| DICT_MERGE | 80 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 80 | 0.0% | 100.0% |  |
| RERAISE | 80 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 80 | 0.0% | 100.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |
| BEFORE_WITH | 40 | 0.0% | 100.0% |  |
| IMPORT_FROM | 20 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 20 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 20 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 20 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 20 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_SLOT | 230,824,360 | 5.3% | 5.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 163,192,740 | 3.7% | 9.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 143,038,220 | 3.3% | 12.3% |
| RESUME_CHECK LOAD_FAST | 131,389,260 | 3.0% | 15.3% |
| CACHE RESUME_CHECK | 113,917,460 | 2.6% | 17.9% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 112,002,920 | 2.6% | 20.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 88,097,620 | 2.0% | 22.5% |
| RETURN_VALUE INTERPRETER_EXIT | 83,310,940 | 1.9% | 24.4% |
| LOAD_CONST LOAD_FAST | 79,132,100 | 1.8% | 26.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 72,410,040 | 1.7% | 27.9% |
| STORE_FAST LOAD_FAST | 70,936,360 | 1.6% | 29.5% |
| LOAD_FAST STORE_ATTR_SLOT | 70,171,440 | 1.6% | 31.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 69,876,480 | 1.6% | 32.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 66,149,760 | 1.5% | 34.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 62,708,600 | 1.4% | 35.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 60,917,920 | 1.4% | 37.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 58,978,040 | 1.4% | 38.4% |
| LOAD_ATTR_MODULE PUSH_NULL | 58,976,540 | 1.4% | 39.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 57,483,080 | 1.3% | 41.1% |
| LOAD_ATTR_SLOT LOAD_FAST | 57,183,940 | 1.3% | 42.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 57,183,860 | 1.3% | 43.7% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 57,183,440 | 1.3% | 45.0% |
| COMPARE_OP_FLOAT RETURN_VALUE | 57,183,420 | 1.3% | 46.3% |
| LOAD_ATTR_SLOT COMPARE_OP_FLOAT | 57,183,400 | 1.3% | 47.6% |
| RETURN_CONST POP_TOP | 53,754,120 | 1.2% | 48.9% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 51,508,260 | 1.2% | 50.0% |
| LOAD_FAST LOAD_ATTR | 44,050,340 | 1.0% | 51.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 43,300,720 | 1.0% | 52.0% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 42,550,040 | 1.0% | 53.0% |
| PUSH_NULL LOAD_FAST | 41,804,720 | 1.0% | 54.0% |
| STORE_ATTR_SLOT LOAD_CONST | 41,803,980 | 1.0% | 54.9% |
| RETURN_CONST INTERPRETER_EXIT | 39,564,780 | 0.9% | 55.8% |
| POP_TOP LOAD_FAST | 38,821,880 | 0.9% | 56.7% |
| LOAD_FAST RETURN_VALUE | 38,820,420 | 0.9% | 57.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 38,819,920 | 0.9% | 58.5% |
| CALL STORE_FAST | 38,818,240 | 0.9% | 59.4% |
| LOAD_ATTR_SLOT TO_BOOL_NONE | 38,071,000 | 0.9% | 60.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 33,592,700 | 0.8% | 61.0% |
| POP_JUMP_IF_FALSE LOAD_CONST | 29,863,760 | 0.7% | 61.7% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 29,860,260 | 0.7% | 62.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 29,115,580 | 0.7% | 63.1% |
| POP_TOP RETURN_CONST | 29,114,440 | 0.7% | 63.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 26,878,240 | 0.6% | 64.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 26,874,160 | 0.6% | 65.0% |
| RETURN_VALUE STORE_FAST | 26,129,820 | 0.6% | 65.6% |
| RETURN_VALUE TO_BOOL_BOOL | 25,381,280 | 0.6% | 66.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 25,381,200 | 0.6% | 66.7% |
| STORE_ATTR_SLOT LOAD_FAST | 24,635,020 | 0.6% | 67.3% |
| STORE_ATTR_SLOT RETURN_CONST | 24,634,560 | 0.6% | 67.9% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_WITH_VALUES | 24,634,360 | 0.6% | 68.4% |
| LOAD_CONST STORE_FAST | 22,404,000 | 0.5% | 68.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 22,399,700 | 0.5% | 69.4% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 22,395,340 | 0.5% | 70.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 21,648,720 | 0.5% | 70.4% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 21,648,560 | 0.5% | 70.9% |
| LOAD_ATTR CALL_METHOD_DESCRIPTOR_NOARGS | 21,647,920 | 0.5% | 71.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS TO_BOOL_BOOL | 21,647,880 | 0.5% | 71.9% |
| POP_TOP LOAD_CONST | 20,904,420 | 0.5% | 72.4% |
| LOAD_ATTR PUSH_NULL | 20,902,740 | 0.5% | 72.9% |
| BUILD_LIST LOAD_FAST | 20,902,080 | 0.5% | 73.4% |
| LIST_EXTEND CALL_INTRINSIC_1 | 20,901,840 | 0.5% | 73.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 17,916,200 | 0.4% | 74.3% |
| PUSH_NULL CALL | 17,172,540 | 0.4% | 74.7% |
| LOAD_FAST CALL | 17,171,240 | 0.4% | 75.0% |
| STORE_FAST RETURN_CONST | 17,171,200 | 0.4% | 75.4% |
| LOAD_FAST_LOAD_FAST CALL | 17,169,560 | 0.4% | 75.8% |
| CALL_FUNCTION_EX POP_TOP | 17,169,520 | 0.4% | 76.2% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 17,169,360 | 0.4% | 76.6% |
| LOAD_ATTR_SLOT BUILD_LIST | 17,169,340 | 0.4% | 77.0% |
| LOAD_ATTR_SLOT LIST_EXTEND | 17,169,340 | 0.4% | 77.4% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 17,169,280 | 0.4% | 77.8% |
| POP_TOP ENTER_EXECUTOR | 17,169,020 | 0.4% | 78.2% |
| ENTER_EXECUTOR LOAD_ATTR | 17,166,960 | 0.4% | 78.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 16,423,560 | 0.4% | 79.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 16,423,340 | 0.4% | 79.3% |
| GET_AWAITABLE LOAD_CONST | 15,676,560 | 0.4% | 79.7% |
| POP_TOP RESUME_CHECK | 15,676,440 | 0.4% | 80.1% |
| RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT | 15,676,420 | 0.4% | 80.4% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 14,932,000 | 0.3% | 80.8% |
| LOAD_FAST LOAD_CONST | 14,186,140 | 0.3% | 81.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 13,441,580 | 0.3% | 81.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 13,437,220 | 0.3% | 81.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 13,436,860 | 0.3% | 82.0% |
| NOP LOAD_FAST | 12,695,240 | 0.3% | 82.3% |
| COPY_FREE_VARS RESUME_CHECK | 12,690,940 | 0.3% | 82.6% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 11,946,120 | 0.3% | 82.9% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 11,945,940 | 0.3% | 83.1% |
| END_SEND POP_TOP | 11,944,080 | 0.3% | 83.4% |
| RETURN_GENERATOR GET_AWAITABLE | 11,197,600 | 0.3% | 83.7% |
| YIELD_VALUE YIELD_VALUE | 11,197,600 | 0.3% | 83.9% |
| JUMP_BACKWARD_NO_INTERRUPT SEND_GEN | 11,197,560 | 0.3% | 84.2% |
| SEND_GEN RESUME_CHECK | 11,197,520 | 0.3% | 84.4% |
| SEND_GEN POP_TOP | 11,197,500 | 0.3% | 84.7% |
| LOAD_CONST SEND_GEN | 11,197,440 | 0.3% | 84.9% |
| LOAD_CONST CALL_KW | 10,451,320 | 0.2% | 85.2% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 9,704,680 | 0.2% | 85.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 8,961,940 | 0.2% | 85.6% |
| LOAD_ATTR CALL | 8,959,740 | 0.2% | 85.8% |
| LOAD_DEREF LOAD_FAST | 8,958,740 | 0.2% | 86.0% |
| CALL POP_TOP | 8,958,640 | 0.2% | 86.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 113,917,460 | 89.4% |
| COPY_FREE_VARS | 8,957,960 | 7.0% |
| POP_TOP | 4,478,960 | 3.5% |
| RESUME | 300 | 0.0% |


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
| LOAD_CONST | 120 | 75.0% |
| LOAD_FAST | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 60 | 37.5% |
| LOAD_ATTR | 40 | 25.0% |
| PUSH_EXC_INFO | 20 | 12.5% |
| STORE_FAST | 20 | 12.5% |
| BINARY_SUBSCR_DICT | 20 | 12.5% |


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
| RETURN_CONST | 7,465,120 | 47.6% |
| SEND | 4,478,960 | 28.6% |
| RETURN_VALUE | 3,732,480 | 23.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 11,944,080 | 76.2% |
| LOAD_FAST | 3,732,480 | 23.8% |


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
| LOAD_FAST | 1,496,660 | 50.0% |
| CALL_BUILTIN_CLASS | 748,340 | 25.0% |
| LOAD_DEREF | 746,480 | 25.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 160 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,496,540 | 50.0% |
| LOAD_FAST_AND_CLEAR | 746,480 | 25.0% |
| FOR_ITER_TUPLE | 746,480 | 25.0% |
| FOR_ITER_RANGE | 1,820 | 0.1% |
| FOR_ITER | 380 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 83,310,940 | 65.4% |
| RETURN_CONST | 39,564,780 | 31.1% |
| YIELD_VALUE | 4,478,960 | 3.5% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 746,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 746,720 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,481,620 | 35.3% |
| STORE_FAST | 4,480,960 | 35.3% |
| POP_JUMP_IF_NOT_NONE | 3,732,560 | 29.4% |
| POP_TOP | 400 | 0.0% |
| RESUME | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,695,240 | 100.0% |
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
| RETURN_CONST | 53,754,120 | 40.0% |
| CALL_METHOD_DESCRIPTOR_O | 22,395,340 | 16.7% |
| CALL_FUNCTION_EX | 17,169,520 | 12.8% |
| END_SEND | 11,944,080 | 8.9% |
| SEND_GEN | 11,197,500 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,821,880 | 28.9% |
| RETURN_CONST | 29,114,440 | 21.7% |
| LOAD_CONST | 20,904,420 | 15.6% |
| ENTER_EXECUTOR | 17,169,020 | 12.8% |
| RESUME_CHECK | 15,676,440 | 11.7% |


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
| LOAD_ATTR_MODULE | 58,976,540 | 69.3% |
| LOAD_ATTR | 20,902,740 | 24.6% |
| LOAD_FAST | 5,225,860 | 6.1% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,804,720 | 49.1% |
| LOAD_FAST_LOAD_FAST | 21,648,560 | 25.4% |
| CALL | 17,172,540 | 20.2% |
| LOAD_GLOBAL_MODULE | 3,732,440 | 4.4% |
| LOAD_GLOBAL_BUILTIN | 746,440 | 0.9% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 8,211,720 | 52.4% |
| CALL_PY_WITH_DEFAULTS | 3,732,460 | 23.8% |
| ENTER_EXECUTOR | 3,732,120 | 23.8% |
| CALL | 120 | 0.0% |
| COPY_FREE_VARS | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 11,197,600 | 71.4% |
| LIST_APPEND | 4,478,880 | 28.6% |
| CALL | 40 | 0.0% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 57,183,420 | 38.8% |
| LOAD_FAST | 38,820,420 | 26.3% |
| LOAD_ATTR_INSTANCE_VALUE | 29,860,260 | 20.2% |
| CALL | 4,481,180 | 3.0% |
| RETURN_VALUE | 4,479,360 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 83,310,940 | 56.5% |
| STORE_FAST | 26,129,820 | 17.7% |
| TO_BOOL_BOOL | 25,381,280 | 17.2% |
| RETURN_VALUE | 4,479,360 | 3.0% |
| LOAD_FAST | 3,734,380 | 2.5% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 60.0% |
| LOAD_ATTR | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 40.0% |
| STORE_SUBSCR_DICT | 40 | 40.0% |
| LOAD_CONST | 20 | 20.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,481,100 | 85.7% |
| LOAD_FAST | 746,640 | 14.3% |
| TO_BOOL | 1,760 | 0.0% |
| LOAD_ATTR | 640 | 0.0% |
| RETURN_VALUE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,480,040 | 85.6% |
| POP_JUMP_IF_TRUE | 748,560 | 14.3% |
| TO_BOOL | 1,760 | 0.0% |
| TO_BOOL_BOOL | 960 | 0.0% |
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
| LOAD_FAST | 240 | 20.7% |
| LOAD_CONST | 200 | 17.2% |
| LOAD_GLOBAL_MODULE | 180 | 15.5% |
| UNARY_INVERT | 160 | 13.8% |
| BINARY_OP | 160 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 220 | 19.0% |
| BINARY_OP | 160 | 13.8% |
| COPY | 160 | 13.8% |
| LOAD_GLOBAL_MODULE | 120 | 10.3% |
| UNARY_INVERT | 80 | 6.9% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 17,169,340 | 71.9% |
| LOAD_FAST | 3,732,480 | 15.6% |
| STORE_FAST | 748,320 | 3.1% |
| POP_JUMP_IF_FALSE | 746,480 | 3.1% |
| STORE_DEREF | 746,480 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,902,080 | 87.5% |
| STORE_FAST | 1,494,800 | 6.3% |
| STORE_DEREF | 746,480 | 3.1% |
| SWAP | 746,480 | 3.1% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,732,480 | 83.3% |
| STORE_FAST | 746,480 | 16.7% |
| POP_TOP | 80 | 0.0% |
| BUILD_TUPLE | 80 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 3,732,480 | 83.3% |
| STORE_FAST | 746,480 | 16.7% |
| LOAD_FAST | 320 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 746,720 | 99.9% |
| CALL | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 746,720 | 99.9% |
| CALL | 160 | 0.0% |
| RETURN_VALUE | 80 | 0.0% |
| BUILD_MAP | 80 | 0.0% |
| CALL_ISINSTANCE | 40 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 17,172,540 | 26.4% |
| LOAD_FAST | 17,171,240 | 26.4% |
| LOAD_FAST_LOAD_FAST | 17,169,560 | 26.4% |
| LOAD_ATTR | 8,959,740 | 13.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,479,100 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 38,818,240 | 59.7% |
| POP_TOP | 8,958,640 | 13.8% |
| RESUME_CHECK | 8,212,060 | 12.6% |
| RETURN_VALUE | 4,481,180 | 6.9% |
| CALL_METHOD_DESCRIPTOR_O | 4,479,060 | 6.9% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 17,169,360 | 79.3% |
| BUILD_MAP | 3,732,480 | 17.2% |
| STORE_FAST | 746,480 | 3.4% |
| DICT_MERGE | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 17,169,520 | 79.3% |
| STORE_FAST | 3,732,480 | 17.2% |
| MAKE_CELL | 746,480 | 3.4% |
| COPY_FREE_VARS | 80 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 20,901,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 17,169,360 | 82.1% |
| LOAD_CONST | 3,732,480 | 17.9% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,451,320 | 73.7% |
| ENTER_EXECUTOR | 3,732,120 | 26.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,478,960 | 31.6% |
| RESUME_CHECK | 4,478,940 | 31.6% |
| RETURN_VALUE | 3,732,480 | 26.3% |
| POP_TOP | 746,560 | 5.3% |
| STORE_DEREF | 746,480 | 5.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,732,780 | 100.0% |
| COMPARE_OP | 1,180 | 0.0% |
| CALL_BUILTIN_CLASS | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 100 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,733,020 | 100.0% |
| COMPARE_OP | 1,180 | 0.0% |
| COMPARE_OP_INT | 140 | 0.0% |
| COMPARE_OP_FLOAT | 60 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,478,940 | 85.7% |
| LOAD_FAST_LOAD_FAST | 746,760 | 14.3% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,225,800 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 4,479,020 | 99.9% |
| CALL_LEN | 1,820 | 0.0% |
| BINARY_OP | 160 | 0.0% |
| LOAD_FAST | 160 | 0.0% |
| UNARY_NOT | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,479,080 | 99.9% |
| TO_BOOL_INT | 1,880 | 0.0% |
| TO_BOOL | 240 | 0.0% |
| POP_EXCEPT | 80 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 8,957,960 | 70.6% |
| CALL_PY_EXACT_ARGS | 3,733,100 | 29.4% |
| CALL | 180 | 0.0% |
| CALL_FUNCTION_EX | 80 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,690,940 | 100.0% |
| RESUME | 280 | 0.0% |
| RETURN_GENERATOR | 80 | 0.0% |
| MAKE_CELL | 80 | 0.0% |


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
| POP_TOP | 17,169,020 | 56.1% |
| CALL_LIST_APPEND | 8,957,080 | 29.3% |
| LIST_APPEND | 4,478,540 | 14.6% |
| POP_JUMP_IF_FALSE | 1,580 | 0.0% |
| JUMP_BACKWARD | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 17,166,960 | 56.1% |
| LOAD_ATTR_SLOT | 3,732,400 | 12.2% |
| RETURN_GENERATOR | 3,732,120 | 12.2% |
| CALL_KW | 3,732,120 | 12.2% |
| LOAD_DEREF | 746,440 | 2.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 380 | 67.9% |
| FOR_ITER | 80 | 14.3% |
| JUMP_BACKWARD | 80 | 14.3% |
| SWAP | 20 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 21.4% |
| LOAD_FAST | 100 | 17.9% |
| FOR_ITER_LIST | 100 | 17.9% |
| FOR_ITER | 80 | 14.3% |
| STORE_FAST | 80 | 14.3% |


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 11,197,600 | 71.4% |
| LOAD_FAST | 3,732,480 | 23.8% |
| RETURN_VALUE | 746,480 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 15,676,560 | 100.0% |


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
| LOAD_FAST_LOAD_FAST | 4,478,880 | 100.0% |
| LOAD_CONST | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,478,880 | 100.0% |
| RETURN_VALUE | 400 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 700 | 34.0% |
| CALL_LIST_APPEND | 640 | 31.1% |
| POP_TOP | 380 | 18.4% |
| LIST_APPEND | 340 | 16.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 660 | 32.0% |
| FOR_ITER_RANGE | 600 | 29.1% |
| FOR_ITER_LIST | 300 | 14.6% |
| FOR_ITER_TUPLE | 300 | 14.6% |
| ENTER_EXECUTOR | 120 | 5.8% |


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,676,420 | 100.0% |
| RESUME | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 11,197,560 | 71.4% |
| SEND | 4,479,000 | 28.6% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,478,980 | 99.9% |
| STORE_FAST | 4,000 | 0.1% |
| ENTER_EXECUTOR | 80 | 0.0% |
| POP_JUMP_IF_FALSE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 4,478,880 | 99.9% |
| LOAD_FAST | 2,240 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,880 | 0.0% |
| NOP | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 4,478,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,478,540 | 100.0% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 17,169,340 | 82.1% |
| LOAD_FAST | 3,732,480 | 17.9% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 20,901,840 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,050,340 | 67.8% |
| ENTER_EXECUTOR | 17,166,960 | 26.4% |
| LOAD_ATTR_SLOT | 3,734,620 | 5.7% |
| LOAD_ATTR | 19,560 | 0.0% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 21,647,920 | 33.3% |
| PUSH_NULL | 20,902,740 | 32.2% |
| CALL | 8,959,740 | 13.8% |
| LOAD_FAST | 8,212,560 | 12.6% |
| TO_BOOL_NONE | 4,478,920 | 6.9% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 41,803,980 | 27.3% |
| POP_JUMP_IF_FALSE | 29,863,760 | 19.5% |
| POP_TOP | 20,904,420 | 13.7% |
| GET_AWAITABLE | 15,676,560 | 10.2% |
| LOAD_FAST | 14,186,140 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,132,100 | 51.7% |
| STORE_FAST | 22,404,000 | 14.6% |
| SEND_GEN | 11,197,440 | 7.3% |
| CALL_KW | 10,451,320 | 6.8% |
| BINARY_OP_ADD_INT | 8,957,720 | 5.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 8,957,760 | 18.7% |
| LOAD_GLOBAL_BUILTIN | 8,212,000 | 17.2% |
| POP_JUMP_IF_FALSE | 5,225,360 | 10.9% |
| RESUME_CHECK | 4,478,920 | 9.4% |
| JUMP_FORWARD | 4,478,880 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,958,740 | 18.8% |
| LOAD_CONST | 8,957,920 | 18.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,225,280 | 10.9% |
| LOAD_DEREF | 4,478,880 | 9.4% |
| POP_JUMP_IF_NONE | 4,478,880 | 9.4% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 143,038,220 | 17.4% |
| RESUME_CHECK | 131,389,260 | 16.0% |
| LOAD_CONST | 79,132,100 | 9.6% |
| STORE_FAST | 70,936,360 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 66,149,760 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 230,824,360 | 28.1% |
| LOAD_ATTR_INSTANCE_VALUE | 112,002,920 | 13.7% |
| STORE_ATTR_SLOT | 70,171,440 | 8.6% |
| LOAD_GLOBAL_MODULE | 60,917,920 | 7.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 58,978,040 | 7.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 746,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 746,480 | 100.0% |


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
| STORE_ATTR_SLOT | 51,508,260 | 33.0% |
| LOAD_FAST_LOAD_FAST | 25,381,200 | 16.3% |
| PUSH_NULL | 21,648,560 | 13.9% |
| POP_JUMP_IF_NOT_NONE | 17,169,280 | 11.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 13,436,860 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 72,410,040 | 46.4% |
| LOAD_FAST_LOAD_FAST | 25,381,200 | 16.3% |
| LOAD_FAST | 21,648,720 | 13.9% |
| CALL | 17,169,560 | 11.0% |
| LOAD_CONST | 5,225,800 | 3.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME | 560 | 12.3% |
| RESUME_CHECK | 540 | 11.9% |
| POP_TOP | 500 | 11.0% |
| LOAD_FAST | 500 | 11.0% |
| POP_JUMP_IF_FALSE | 500 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,540 | 33.9% |
| LOAD_ATTR | 940 | 20.7% |
| LOAD_GLOBAL_BUILTIN | 660 | 14.5% |
| LOAD_FAST | 340 | 7.5% |
| CALL | 280 | 6.2% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 500 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 240 | 48.0% |
| CALL | 140 | 28.0% |
| LOAD_FAST | 80 | 16.0% |
| LOAD_FAST_LOAD_FAST | 40 | 8.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,985,920 | 80.0% |
| CALL_FUNCTION_EX | 746,480 | 20.0% |
| COPY_FREE_VARS | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,985,920 | 80.0% |
| RESUME_CHECK | 746,520 | 20.0% |
| RESUME | 40 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 163,192,740 | 68.8% |
| TO_BOOL_NONE | 42,550,040 | 17.9% |
| COMPARE_OP_INT | 8,961,940 | 3.8% |
| CONTAINS_OP | 5,225,800 | 2.2% |
| TO_BOOL_LIST | 4,483,200 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 143,038,220 | 60.3% |
| RETURN_CONST | 33,592,700 | 14.2% |
| LOAD_CONST | 29,863,760 | 12.6% |
| LOAD_GLOBAL_MODULE | 16,423,560 | 6.9% |
| LOAD_DEREF | 5,225,360 | 2.2% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,958,320 | 66.7% |
| LOAD_DEREF | 4,478,880 | 33.3% |
| LOAD_ATTR_INSTANCE_VALUE | 260 | 0.0% |
| CALL | 160 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 8,957,760 | 66.7% |
| LOAD_FAST | 4,479,120 | 33.3% |
| RETURN_CONST | 480 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,819,920 | 89.7% |
| LOAD_ATTR_INSTANCE_VALUE | 4,478,960 | 10.3% |
| LOAD_GLOBAL_MODULE | 220 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 17,169,280 | 39.7% |
| LOAD_FAST | 11,945,940 | 27.6% |
| LOAD_GLOBAL_MODULE | 9,704,680 | 22.4% |
| NOP | 3,732,560 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 746,440 | 1.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 16,423,340 | 95.6% |
| TO_BOOL | 748,560 | 4.4% |
| TO_BOOL_INT | 1,880 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,437,220 | 78.2% |
| LOAD_CONST | 3,734,320 | 21.7% |
| STORE_FAST | 1,840 | 0.0% |
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
| POP_JUMP_IF_FALSE | 33,592,700 | 31.9% |
| POP_TOP | 29,114,440 | 27.7% |
| STORE_ATTR_SLOT | 24,634,560 | 23.4% |
| STORE_FAST | 17,171,200 | 16.3% |
| STORE_ATTR_INSTANCE_VALUE | 747,120 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 53,754,120 | 51.1% |
| INTERPRETER_EXIT | 39,564,780 | 37.6% |
| END_SEND | 7,465,120 | 7.1% |
| TO_BOOL_BOOL | 4,478,920 | 4.3% |
| EXIT_INIT_CHECK | 120 | 0.0% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,479,120 | 50.0% |
| JUMP_BACKWARD_NO_INTERRUPT | 4,479,000 | 50.0% |
| SEND | 2,580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 4,478,960 | 50.0% |
| YIELD_VALUE | 4,478,960 | 50.0% |
| SEND | 2,580 | 0.0% |
| POP_TOP | 100 | 0.0% |
| SEND_GEN | 100 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 746,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 746,720 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,481,100 | 85.7% |
| LOAD_FAST_LOAD_FAST | 746,820 | 14.3% |
| STORE_ATTR | 1,760 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 280 | 0.0% |
| SWAP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 4,478,880 | 85.6% |
| LOAD_CONST | 746,860 | 14.3% |
| STORE_ATTR | 1,760 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 960 | 0.0% |
| LOAD_FAST | 540 | 0.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 8,957,720 | 70.6% |
| LOAD_CONST | 2,239,440 | 17.6% |
| BUILD_LIST | 746,480 | 5.9% |
| CALL_KW | 746,480 | 5.9% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 4,478,880 | 35.3% |
| LOAD_FAST_LOAD_FAST | 4,478,880 | 35.3% |
| LOAD_CONST | 1,492,960 | 11.8% |
| LOAD_FAST | 1,492,960 | 11.8% |
| BUILD_LIST | 746,480 | 5.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 38,818,240 | 36.4% |
| RETURN_VALUE | 26,129,820 | 24.5% |
| LOAD_CONST | 22,404,000 | 21.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,480,960 | 4.2% |
| CALL_KW | 4,478,960 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,936,360 | 66.4% |
| RETURN_CONST | 17,171,200 | 16.1% |
| LOAD_FAST_LOAD_FAST | 5,226,040 | 4.9% |
| NOP | 4,480,960 | 4.2% |
| LOAD_GLOBAL_MODULE | 4,479,080 | 4.2% |


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
| BUILD_LIST | 746,480 | 33.3% |
| LOAD_FAST_AND_CLEAR | 746,480 | 33.3% |
| ENTER_EXECUTOR | 746,440 | 33.3% |
| LOAD_ATTR | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 746,560 | 33.3% |
| BUILD_LIST | 746,480 | 33.3% |
| FOR_ITER_RANGE | 746,460 | 33.3% |
| POP_EXCEPT | 100 | 0.0% |
| STORE_ATTR | 80 | 0.0% |


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
| YIELD_VALUE | 11,197,600 | 71.4% |
| SEND | 4,478,960 | 28.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 11,197,600 | 71.4% |
| INTERPRETER_EXIT | 4,478,960 | 28.6% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,080 | 56.2% |
| CACHE | 300 | 15.6% |
| COPY_FREE_VARS | 280 | 14.6% |
| POP_TOP | 120 | 6.2% |
| SEND_GEN | 80 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 920 | 47.9% |
| LOAD_GLOBAL | 560 | 29.2% |
| JUMP_BACKWARD_NO_INTERRUPT | 140 | 7.3% |
| NOP | 100 | 5.2% |
| LOAD_CONST | 100 | 5.2% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,732,440 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,800 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,732,460 | 100.0% |
| STORE_FAST | 1,820 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,957,720 | 100.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 8,957,720 | 100.0% |
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
| STORE_FAST | 120 | 100.0% |


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

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 600 | 90.9% |
| BINARY_SUBSCR | 60 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 460 | 69.7% |
| LOAD_ATTR_SLOT | 160 | 24.2% |
| LOAD_ATTR | 40 | 6.1% |


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
| LOAD_GLOBAL_MODULE | 746,440 | 99.7% |
| LOAD_FAST | 1,980 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 220 | 0.0% |
| CALL | 160 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 748,340 | 99.9% |
| LOAD_FAST | 240 | 0.0% |
| COMPARE_OP | 140 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,479,060 | 54.5% |
| LOAD_FAST | 3,732,440 | 45.5% |
| CALL | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,479,020 | 54.5% |
| POP_TOP | 3,732,460 | 45.5% |
| TO_BOOL_BOOL | 80 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,732,480 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 440 | 0.0% |
| CALL | 80 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,732,440 | 100.0% |
| STORE_FAST | 460 | 0.0% |
| POP_TOP | 120 | 0.0% |
| TO_BOOL | 20 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 57,183,440 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 380 | 0.0% |
| CALL | 80 | 0.0% |
| BUILD_TUPLE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 57,183,860 | 100.0% |
| TO_BOOL | 80 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,400 | 98.9% |
| CALL | 60 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,640 | 66.7% |
| COPY | 1,820 | 33.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,957,680 | 100.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 8,957,080 | 100.0% |
| JUMP_BACKWARD | 640 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 1,800 | 89.1% |
| LOAD_CONST | 80 | 4.0% |
| CALL | 60 | 3.0% |
| LOAD_ATTR | 40 | 2.0% |
| LOAD_FAST | 40 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,820 | 90.1% |
| POP_TOP | 120 | 5.9% |
| RETURN_VALUE | 80 | 4.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 21,647,920 | 82.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,478,840 | 17.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 86,120 | 0.3% |
| LOAD_ATTR_METHOD_NO_DICT | 2,520 | 0.0% |
| CALL | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 21,647,880 | 82.6% |
| STORE_FAST | 4,480,960 | 17.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 86,120 | 0.3% |
| POP_TOP | 380 | 0.0% |
| GET_ITER | 160 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,916,200 | 80.0% |
| CALL | 4,479,060 | 20.0% |
| LOAD_CONST | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 22,395,340 | 100.0% |
| LOAD_CONST | 20 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 57,483,080 | 57.5% |
| LOAD_FAST | 26,878,240 | 26.9% |
| LOAD_ATTR_METHOD_NO_DICT | 7,467,040 | 7.5% |
| LOAD_SUPER_ATTR_METHOD | 3,732,640 | 3.7% |
| LOAD_FAST_LOAD_FAST | 3,732,440 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 88,097,620 | 88.1% |
| RETURN_GENERATOR | 8,211,720 | 8.2% |
| COPY_FREE_VARS | 3,733,100 | 3.7% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,732,440 | 100.0% |
| CALL | 120 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| PUSH_NULL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 3,732,460 | 100.0% |
| RESUME_CHECK | 380 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,478,920 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,478,920 | 100.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 57,183,400 | 100.0% |
| LOAD_FAST | 440 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 57,183,420 | 100.0% |
| POP_JUMP_IF_FALSE | 600 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,481,160 | 50.0% |
| LOAD_DEREF | 4,478,840 | 50.0% |
| LOAD_GLOBAL_MODULE | 1,800 | 0.0% |
| COMPARE_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,961,940 | 100.0% |


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
| GET_ITER | 1,496,540 | 100.0% |
| JUMP_BACKWARD | 300 | 0.0% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 746,740 | 49.9% |
| LOAD_DEREF | 746,500 | 49.9% |
| RETURN_CONST | 1,880 | 0.1% |
| LOAD_FAST | 1,820 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 746,460 | 99.7% |
| GET_ITER | 1,820 | 0.2% |
| JUMP_BACKWARD | 600 | 0.1% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 748,840 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| SWAP | 40 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 746,480 | 100.0% |
| JUMP_BACKWARD | 300 | 0.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 746,760 | 100.0% |
| LOAD_GLOBAL | 40 | 0.0% |


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
| LOAD_FAST | 112,002,920 | 95.5% |
| LOAD_FAST_LOAD_FAST | 4,479,120 | 3.8% |
| LOAD_DEREF | 746,440 | 0.6% |
| LOAD_ATTR | 1,560 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 43,300,720 | 36.9% |
| RETURN_VALUE | 29,860,260 | 25.5% |
| LOAD_ATTR_METHOD_NO_DICT | 22,399,700 | 19.1% |
| TO_BOOL_LIST | 4,483,100 | 3.8% |
| TO_BOOL | 4,481,100 | 3.8% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 22,399,700 | 57.7% |
| LOAD_FAST | 11,946,120 | 30.8% |
| LOAD_DEREF | 4,478,840 | 11.5% |
| LOAD_ATTR | 580 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,874,160 | 69.2% |
| CALL_PY_EXACT_ARGS | 7,467,040 | 19.2% |
| LOAD_GLOBAL_MODULE | 4,478,960 | 11.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,520 | 0.0% |
| LOAD_FAST_LOAD_FAST | 1,960 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,978,040 | 66.4% |
| LOAD_ATTR_SLOT | 24,634,360 | 27.7% |
| LOAD_DEREF | 5,225,280 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,120 | 0.0% |
| LOAD_ATTR | 1,220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 57,483,080 | 64.7% |
| LOAD_FAST | 13,441,580 | 15.1% |
| LOAD_FAST_LOAD_FAST | 13,436,860 | 15.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,478,840 | 5.0% |
| CALL | 720 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 62,708,600 | 100.0% |
| LOAD_ATTR | 960 | 0.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 58,976,540 | 94.0% |
| LOAD_FAST_LOAD_FAST | 3,732,460 | 6.0% |
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
| LOAD_FAST | 230,824,360 | 98.4% |
| ENTER_EXECUTOR | 3,732,400 | 1.6% |
| LOAD_ATTR_SLOT | 920 | 0.0% |
| LOAD_ATTR | 460 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,183,940 | 24.4% |
| COMPARE_OP_FLOAT | 57,183,400 | 24.4% |
| TO_BOOL_NONE | 38,071,000 | 16.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 24,634,360 | 10.5% |
| BUILD_LIST | 17,169,340 | 7.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 69,876,480 | 93.0% |
| POP_TOP | 3,732,640 | 5.0% |
| PUSH_NULL | 746,440 | 1.0% |
| POP_JUMP_IF_NOT_NONE | 746,440 | 1.0% |
| JUMP_FORWARD | 1,880 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 66,149,760 | 88.1% |
| LOAD_DEREF | 8,212,000 | 10.9% |
| LOAD_GLOBAL_MODULE | 746,480 | 1.0% |
| CALL_ISINSTANCE | 380 | 0.0% |
| CALL_BUILTIN_CLASS | 220 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,917,920 | 45.2% |
| RESUME_CHECK | 29,115,580 | 21.6% |
| POP_JUMP_IF_FALSE | 16,423,560 | 12.2% |
| POP_JUMP_IF_NOT_NONE | 9,704,680 | 7.2% |
| STORE_FAST | 4,479,080 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 62,708,600 | 46.5% |
| CALL_ISINSTANCE | 57,183,440 | 42.4% |
| LOAD_FAST_LOAD_FAST | 5,225,940 | 3.9% |
| CONTAINS_OP | 4,478,940 | 3.3% |
| CALL_PY_WITH_DEFAULTS | 3,732,440 | 2.8% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,211,760 | 100.0% |
| LOAD_SUPER_ATTR | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,732,640 | 45.5% |
| LOAD_FAST_LOAD_FAST | 3,732,520 | 45.5% |
| LOAD_FAST | 746,720 | 9.1% |
| CALL | 120 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 113,917,460 | 44.7% |
| CALL_PY_EXACT_ARGS | 88,097,620 | 34.5% |
| POP_TOP | 15,676,440 | 6.1% |
| COPY_FREE_VARS | 12,690,940 | 5.0% |
| SEND_GEN | 11,197,520 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 131,389,260 | 51.5% |
| LOAD_GLOBAL_BUILTIN | 69,876,480 | 27.4% |
| LOAD_GLOBAL_MODULE | 29,115,580 | 11.4% |
| JUMP_BACKWARD_NO_INTERRUPT | 15,676,420 | 6.1% |
| NOP | 4,481,620 | 1.8% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD_NO_INTERRUPT | 11,197,560 | 50.0% |
| LOAD_CONST | 11,197,440 | 50.0% |
| SEND | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,197,520 | 50.0% |
| POP_TOP | 11,197,500 | 50.0% |
| RESUME | 80 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 748,380 | 99.8% |
| STORE_ATTR | 960 | 0.1% |
| LOAD_FAST_LOAD_FAST | 260 | 0.0% |
| SWAP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 747,120 | 99.7% |
| LOAD_CONST | 840 | 0.1% |
| LOAD_FAST | 760 | 0.1% |
| LOAD_GLOBAL_MODULE | 360 | 0.0% |
| BUILD_LIST | 220 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 72,410,040 | 50.8% |
| LOAD_FAST | 70,171,440 | 49.2% |
| STORE_ATTR_SLOT | 1,120 | 0.0% |
| STORE_ATTR | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 51,508,260 | 36.1% |
| LOAD_CONST | 41,803,980 | 29.3% |
| LOAD_FAST | 24,635,020 | 17.3% |
| RETURN_CONST | 24,634,560 | 17.3% |
| STORE_ATTR_SLOT | 1,120 | 0.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,478,840 | 100.0% |
| STORE_SUBSCR | 40 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,478,920 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 57,183,860 | 31.8% |
| LOAD_ATTR_INSTANCE_VALUE | 43,300,720 | 24.1% |
| RETURN_VALUE | 25,381,280 | 14.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 21,647,880 | 12.1% |
| LOAD_ATTR_SLOT | 14,932,000 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 163,192,740 | 90.9% |
| POP_JUMP_IF_TRUE | 16,423,340 | 9.1% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,880 | 85.5% |
| TO_BOOL | 160 | 7.3% |
| LOAD_FAST | 80 | 3.6% |
| BINARY_OP | 40 | 1.8% |
| LOAD_ATTR | 40 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,880 | 85.5% |
| POP_JUMP_IF_FALSE | 260 | 11.8% |
| UNARY_NOT | 60 | 2.7% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,483,100 | 100.0% |
| TO_BOOL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,483,200 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 38,071,000 | 89.5% |
| LOAD_ATTR | 4,478,920 | 10.5% |
| TO_BOOL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 42,550,040 | 100.0% |


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
|     deferred | 820 | 0.0% |
|          hit | 13,438,980 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 52.9% |
| Failure | 160 | 47.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 80 | 50.0% |
| or | 40 | 25.0% |
| true divide other | 40 | 25.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 80 | 7.5% |
|          hit | 900 | 84.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 64,866,140 | 21.6% |
|          hit | 231,143,360 | 76.9% |
|         miss | 4,565,360 | 1.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 89,060 | 82.1% |
| Failure | 19,480 | 17.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 5,380 | 27.6% |
| no dict | 4,600 | 23.6% |
| cfunc noargs | 3,840 | 19.7% |
| code complex parameters | 2,420 | 12.4% |
| class no vectorcall | 1,340 | 6.9% |
| other | 1,280 | 6.6% |
| cmethod | 380 | 2.0% |
| class mutable | 80 | 0.4% |
| wrong number arguments | 40 | 0.2% |
| cfunc varargs | 40 | 0.2% |
| operator wrapper | 40 | 0.2% |
| cfunc varargs keywords | 20 | 0.1% |
| init not simple | 20 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,733,060 | 5.3% |
|          hit | 66,145,980 | 94.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 14.5% |
| Failure | 1,180 | 85.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 1,140 | 96.6% |
| bool | 40 | 3.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 320 | 0.0% |
|          hit | 2,992,660 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 66.7% |
| Failure | 80 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 80 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 64,950,420 | 10.7% |
|          hit | 542,112,180 | 89.3% |
|         miss | 53,000 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,800 | 23.6% |
| Failure | 18,820 | 76.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 11,280 | 59.9% |
| method | 5,980 | 31.8% |
| class attr descriptor | 1,280 | 6.8% |
| not managed dict | 140 | 0.7% |
| metaclass attribute | 60 | 0.3% |
| non object slot | 40 | 0.2% |
| class attr simple | 40 | 0.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,420 | 0.0% |
|        deopt | 80 | 0.0% |
|          hit | 209,936,240 | 100.0% |
|         miss | 80 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 260 | 0.0% |
|          hit | 8,212,000 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 100.0% |
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
|     deferred | 8,958,020 | 28.6% |
|          hit | 22,395,100 | 71.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 3.7% |
| Failure | 2,580 | 96.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 2,580 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,225,900 | 3.5% |
|          hit | 143,273,020 | 96.4% |
|         miss | 59,600 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,420 | 57.9% |
| Failure | 1,760 | 42.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overriding descriptor | 1,300 | 73.9% |
| no dict | 380 | 21.6% |
| overridden | 80 | 4.5% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 0.0% |
|          hit | 4,478,920 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,228,640 | 2.3% |
|          hit | 226,651,580 | 97.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,340 | 43.2% |
| Failure | 1,760 | 56.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 1,280 | 72.7% |
| tuple | 380 | 21.6% |
| sequence | 100 | 5.7% |


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
| Basic | 2,171,757,480 | 49.7% |
| Not specialized | 464,131,240 | 10.6% |
| Specialized hits | 1,725,709,074 | 39.5% |
| Specialized misses | 4,769,466 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 64,950,420 | 42.5% |
| CALL | 64,866,140 | 42.4% |
| SEND | 8,958,020 | 5.9% |
| TO_BOOL | 5,228,640 | 3.4% |
| STORE_ATTR | 5,225,900 | 3.4% |
| COMPARE_OP | 3,733,060 | 2.4% |
| LOAD_GLOBAL | 2,420 | 0.0% |
| BINARY_OP | 820 | 0.0% |
| FOR_ITER | 320 | 0.0% |
| LOAD_SUPER_ATTR | 260 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,565,240 | 93.9% |
| RESUME | 91,426 | 1.9% |
| RESUME_CHECK | 91,426 | 1.9% |
| STORE_ATTR_SLOT | 59,600 | 1.2% |
| LOAD_ATTR_SLOT | 49,520 | 1.0% |
| LOAD_ATTR_METHOD_NO_DICT | 3,480 | 0.1% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| CACHE | 0 | 0.0% |
| BEFORE_WITH | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 127,354,680 | 47.7% |
| Calls to Python functions inlined | 139,609,700 | 52.3% |
| Calls via PyEval_EvalFrame (total) | 127,354,680 | 47.7% |
| Calls via PyEval_EvalFrame (vector) | 118,396,760 | 44.3% |
| Calls via PyEval_EvalFrame (generator) | 8,957,920 | 3.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 118,396,760 | 44.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 57,183,440 | 21.4% |
| Calls via PyEval_EvalFrame (function ex) | 746,560 | 0.3% |
| Calls via PyEval_EvalFrame (api) | 4,479,100 | 1.7% |
| Calls via PyEval_EvalFrame (method) | 26,873,760 | 10.1% |
| Frame objects created | 180 | 0.0% |
| Frames pushed | 120,944,060 | 45.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 114,342,493 | 39.1% |
| Frees to freelist | 114,850,379 |  |
| Allocations | 177,888,087 | 60.9% |
| Allocations to 512 bytes | 177,772,444 | 60.8% |
| Allocations to 4 kbytes | 115,540 | 0.0% |
| Allocations over 4 kbytes | 103 | 0.0% |
| Frees | 179,991,171 |  |
| New values | 300 |  |
| Interpreter increfs | 2,696,885,920 | 78.8% |
| Interpreter decrefs | 2,810,935,041 | 76.7% |
| Increfs | 723,505,528 | 21.2% |
| Decrefs | 854,992,306 | 23.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 109,128,472 |  |
| Method cache misses | 752,448 |  |
| Method cache collisions | 777,866 |  |
| Method cache dunder hits | 75,071,142 |  |
| Method cache dunder misses | 29,938 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 92,958 | 2,040 | 647,258,430 |
| 1 | 8,440 | 0 | 709,691,164 |
| 2 | 660 | 0 | 2,276,865,212 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 120 |  |
| Traces created | 120 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 20 | 16.7% |
| Traces executed | 30,606,340 |  |
| Uops executed | 1,197,258,420 | 39.12 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 40 | 33.3% |
| <= 32 | 20 | 16.7% |
| <= 64 | 20 | 16.7% |
| <= 128 | 40 | 33.3% |


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
| <= 16 | 40 | 33.3% |
| <= 32 | 40 | 33.3% |
| <= 64 | 40 | 33.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,241,140 | 7.3% |
| <= 16 | 3,733,560 | 12.2% |
| <= 32 | 11,196,640 | 36.6% |
| <= 64 | 13,434,840 | 43.9% |
| <= 128 | 0 | 0.0% |
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
| <= 262,144 | 20 | 0.0% |
| <= 524,288 | 60 | 0.0% |
| <= 1,048,576 | 0 | 0.0% |
| <= 2,097,152 | 0 | 0.0% |
| <= 4,194,304 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 294,835,240 | 24.6% | 24.6% |  |
| LOAD_FAST | 130,621,520 | 10.9% | 35.5% |  |
| _GUARD_TYPE_VERSION | 121,663,960 | 10.2% | 45.7% | 3.1% |
| _POP_JUMP_IF_TRUE | 61,206,500 | 5.1% | 50.8% |  |
| STORE_FAST | 52,994,920 | 4.4% | 55.2% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 45,530,160 | 3.8% | 59.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 45,530,160 | 3.8% | 62.8% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 34,334,080 | 2.9% | 65.7% |  |
| _LOAD_ATTR_SLOT | 30,601,760 | 2.6% | 68.3% |  |
| _EXIT_TRACE | 26,873,940 | 2.2% | 70.5% |  |
| TO_BOOL_BOOL | 26,869,680 | 2.2% | 72.8% |  |
| _ITER_CHECK_RANGE | 21,647,600 | 1.8% | 74.6% |  |
| _IS_ITER_EXHAUSTED_RANGE | 21,647,600 | 1.8% | 76.4% |  |
| _ITER_NEXT_RANGE | 20,899,360 | 1.7% | 78.1% |  |
| _CHECK_PEP_523 | 17,168,400 | 1.4% | 79.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 17,168,400 | 1.4% | 81.0% |  |
| _CHECK_STACK_SPACE | 17,168,400 | 1.4% | 82.4% |  |
| _INIT_CALL_PY_EXACT_ARGS | 17,168,400 | 1.4% | 83.9% |  |
| _PUSH_FRAME | 17,168,400 | 1.4% | 85.3% |  |
| _SAVE_RETURN_OFFSET | 17,168,400 | 1.4% | 86.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 17,167,240 | 1.4% | 88.2% |  |
| LOAD_CONST | 14,928,320 | 1.2% | 89.4% |  |
| RESUME_CHECK | 13,434,840 | 1.1% | 90.5% |  |
| _GUARD_GLOBALS_VERSION | 7,464,120 | 0.6% | 91.1% |  |
| _LOAD_GLOBAL_MODULE | 7,464,120 | 0.6% | 91.8% |  |
| _POP_JUMP_IF_FALSE | 7,464,120 | 0.6% | 92.4% |  |
| POP_TOP | 5,973,140 | 0.5% | 92.9% |  |
| _ITER_CHECK_TUPLE | 4,478,580 | 0.4% | 93.3% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 4,478,580 | 0.4% | 93.6% |  |
| _ITER_CHECK_LIST | 4,478,560 | 0.4% | 94.0% |  |
| _IS_ITER_EXHAUSTED_LIST | 4,478,560 | 0.4% | 94.4% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 3,733,560 | 0.3% | 94.7% |  |
| _GUARD_KEYS_VERSION | 3,733,560 | 0.3% | 95.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 3,733,560 | 0.3% | 95.3% |  |
| CONTAINS_OP | 3,732,120 | 0.3% | 95.6% |  |
| _GUARD_BOTH_INT | 3,732,120 | 0.3% | 95.9% |  |
| _BINARY_OP_SUBTRACT_INT | 3,732,120 | 0.3% | 96.3% |  |
| _ITER_NEXT_LIST | 3,732,120 | 0.3% | 96.6% |  |
| _ITER_NEXT_TUPLE | 3,732,120 | 0.3% | 96.9% |  |
| BINARY_SUBSCR_LIST_INT | 3,732,080 | 0.3% | 97.2% |  |
| COMPARE_OP_FLOAT | 3,732,080 | 0.3% | 97.5% |  |
| PUSH_NULL | 3,732,000 | 0.3% | 97.8% |  |
| CALL_BUILTIN_O | 3,732,000 | 0.3% | 98.1% |  |
| CALL_METHOD_DESCRIPTOR_O | 3,732,000 | 0.3% | 98.4% |  |
| TO_BOOL_LIST | 3,732,000 | 0.3% | 98.8% |  |
| _CHECK_ATTR_MODULE | 3,732,000 | 0.3% | 99.1% |  |
| _LOAD_ATTR_MODULE | 3,732,000 | 0.3% | 99.4% |  |
| _STORE_ATTR_SLOT | 3,732,000 | 0.3% | 99.7% |  |
| _JUMP_TO_TOP | 3,731,920 | 0.3% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| LOAD_ATTR | 40 |
| CALL_KW | 20 |


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
