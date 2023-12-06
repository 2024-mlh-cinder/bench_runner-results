
# Pystats results

- benchmark: async_generators
- fork: gvanrossum
- ref: split-uops
- commit hash: 8ab398d
- commit date: 2023-10-03T16:05:03-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 214,160,760 | 11.5% | 11.5% |  |
| RESUME_CHECK | 136,143,840 | 7.3% | 18.9% | 0.0% |
| LOAD_CONST | 136,142,700 | 7.3% | 26.2% |  |
| STORE_FAST | 118,141,500 | 6.4% | 32.6% |  |
| POP_TOP | 118,141,500 | 6.4% | 38.9% |  |
| INTERPRETER_EXIT | 118,137,840 | 6.4% | 45.3% |  |
| SEND | 100,161,220 | 5.4% | 50.7% |  |
| JUMP_BACKWARD | 100,136,880 | 5.4% | 56.1% |  |
| GET_ANEXT | 100,136,760 | 5.4% | 61.5% |  |
| CALL_INTRINSIC_1 | 94,136,880 | 5.1% | 66.6% |  |
| END_SEND | 94,136,820 | 5.1% | 71.6% |  |
| YIELD_VALUE | 94,136,760 | 5.1% | 76.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 66,006,240 | 3.6% | 80.3% |  |
| POP_JUMP_IF_FALSE | 42,004,380 | 2.3% | 82.5% |  |
| RETURN_CONST | 36,003,600 | 1.9% | 84.5% |  |
| LOAD_FAST_LOAD_FAST | 36,003,060 | 1.9% | 86.4% |  |
| LOAD_GLOBAL_MODULE | 24,004,420 | 1.3% | 87.7% |  |
| CALL_PY_EXACT_ARGS | 18,005,220 | 1.0% | 88.7% |  |
| STORE_ATTR_INSTANCE_VALUE | 18,002,880 | 1.0% | 89.6% |  |
| CALL | 12,007,580 | 0.6% | 90.3% |  |
| RETURN_VALUE | 12,003,540 | 0.6% | 90.9% |  |
| LOAD_GLOBAL_BUILTIN | 12,003,060 | 0.6% | 91.6% | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 12,001,980 | 0.6% | 92.2% |  |
| COMPARE_OP_INT | 12,000,720 | 0.6% | 92.9% |  |
| CALL_LEN | 12,000,420 | 0.6% | 93.5% |  |
| CALL_METHOD_DESCRIPTOR_O | 12,000,360 | 0.6% | 94.2% | 0.0% |
| BINARY_SLICE | 12,000,000 | 0.6% | 94.8% |  |
| TO_BOOL_ALWAYS_TRUE | 6,052,180 | 0.3% | 95.1% | 45.2% |
| TO_BOOL_NONE | 6,051,420 | 0.3% | 95.5% | 45.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,003,480 | 0.3% | 95.8% |  |
| TO_BOOL_BOOL | 6,003,000 | 0.3% | 96.1% |  |
| PUSH_NULL | 6,002,460 | 0.3% | 96.4% |  |
| TO_BOOL | 6,002,260 | 0.3% | 96.8% |  |
| BINARY_OP | 6,002,000 | 0.3% | 97.1% |  |
| BINARY_SUBSCR | 6,001,480 | 0.3% | 97.4% |  |
| POP_JUMP_IF_NONE | 6,000,720 | 0.3% | 97.7% |  |
| TO_BOOL_LIST | 6,000,360 | 0.3% | 98.1% |  |
| RETURN_GENERATOR | 6,000,120 | 0.3% | 98.4% |  |
| EXIT_INIT_CHECK | 6,000,120 | 0.3% | 98.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 6,000,120 | 0.3% | 99.0% |  |
| BINARY_OP_ADD_INT | 6,000,060 | 0.3% | 99.4% |  |
| GET_AITER | 6,000,000 | 0.3% | 99.7% |  |
| END_ASYNC_FOR | 6,000,000 | 0.3% | 100.0% |  |
| LOAD_ATTR | 4,720 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 2,440 | 0.0% | 100.0% |  |
| STORE_ATTR_SLOT | 1,800 | 0.0% | 100.0% |  |
| NOP | 1,440 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 1,320 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,300 | 0.0% | 100.0% |  |
| STORE_ATTR | 1,220 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 1,020 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,020 | 0.0% | 100.0% | 23.5% |
| POP_JUMP_IF_TRUE | 900 | 0.0% | 100.0% |  |
| LOAD_DEREF | 900 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 780 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 780 | 0.0% | 100.0% |  |
| JUMP_FORWARD | 660 | 0.0% | 100.0% |  |
| COPY | 660 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 600 | 0.0% | 100.0% |  |
| GET_ITER | 540 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 480 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 480 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 420 | 0.0% | 100.0% |  |
| BUILD_LIST | 420 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 360 | 0.0% | 100.0% |  |
| IS_OP | 300 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 300 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 300 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 300 | 0.0% | 100.0% |  |
| SWAP | 240 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 240 | 0.0% | 100.0% |  |
| BUILD_MAP | 240 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 180 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 180 | 0.0% | 100.0% |  |
| FOR_ITER | 180 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 180 | 0.0% | 100.0% |  |
| CALL_KW | 180 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 180 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 160 | 0.0% | 100.0% |  |
| COMPARE_OP | 160 | 0.0% | 100.0% |  |
| UNARY_NOT | 120 | 0.0% | 100.0% |  |
| UNARY_INVERT | 120 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 120 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 120 | 0.0% | 100.0% |  |
| POP_EXCEPT | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 120 | 0.0% | 100.0% |  |
| LIST_EXTEND | 120 | 0.0% | 100.0% |  |
| CONTAINS_OP | 120 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 120 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 60 | 0.0% | 100.0% |  |
| SEND_GEN | 60 | 0.0% | 100.0% |  |
| RERAISE | 60 | 0.0% | 100.0% |  |
| RAISE_VARARGS | 60 | 0.0% | 100.0% |  |
| MAKE_CELL | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |
| IMPORT_NAME | 60 | 0.0% | 100.0% |  |
| GET_AWAITABLE | 60 | 0.0% | 100.0% |  |
| DICT_MERGE | 60 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 106,139,340 | 5.7% | 5.7% |
| CACHE RESUME_CHECK | 106,137,720 | 5.7% | 11.4% |
| LOAD_CONST SEND | 100,136,780 | 5.4% | 16.8% |
| GET_ANEXT LOAD_CONST | 100,136,760 | 5.4% | 22.2% |
| YIELD_VALUE INTERPRETER_EXIT | 94,136,760 | 5.1% | 27.3% |
| SEND END_SEND | 94,136,760 | 5.1% | 32.4% |
| RESUME_CHECK POP_TOP | 94,136,760 | 5.1% | 37.4% |
| JUMP_BACKWARD GET_ANEXT | 94,136,760 | 5.1% | 42.5% |
| END_SEND STORE_FAST | 94,136,760 | 5.1% | 47.6% |
| CALL_INTRINSIC_1 YIELD_VALUE | 94,136,760 | 5.1% | 52.7% |
| POP_TOP JUMP_BACKWARD | 88,136,880 | 4.7% | 57.4% |
| LOAD_FAST CALL_INTRINSIC_1 | 88,136,760 | 4.7% | 62.2% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 60,005,200 | 3.2% | 65.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 32,069,820 | 1.7% | 67.1% |
| RESUME_CHECK LOAD_FAST | 24,003,540 | 1.3% | 68.4% |
| LOAD_FAST LOAD_CONST | 24,000,600 | 1.3% | 69.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 18,004,560 | 1.0% | 70.7% |
| POP_TOP RETURN_CONST | 18,000,840 | 1.0% | 71.6% |
| RETURN_CONST INTERPRETER_EXIT | 18,000,780 | 1.0% | 72.6% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 18,000,240 | 1.0% | 73.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 12,001,620 | 0.6% | 74.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 12,001,180 | 0.6% | 74.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 12,001,120 | 0.6% | 75.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 12,000,720 | 0.6% | 76.2% |
| LOAD_CONST COMPARE_OP_INT | 12,000,580 | 0.6% | 76.8% |
| CALL_METHOD_DESCRIPTOR_O POP_TOP | 12,000,360 | 0.6% | 77.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 12,000,300 | 0.6% | 78.1% |
| CALL_LEN STORE_FAST | 12,000,300 | 0.6% | 78.8% |
| LOAD_FAST CALL_LEN | 12,000,060 | 0.6% | 79.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 12,000,000 | 0.6% | 80.1% |
| BINARY_SLICE CALL_PY_EXACT_ARGS | 12,000,000 | 0.6% | 80.7% |
| POP_JUMP_IF_FALSE RETURN_CONST | 9,932,880 | 0.5% | 81.2% |
| LOAD_CONST LOAD_FAST | 6,002,700 | 0.3% | 81.6% |
| RETURN_CONST POP_TOP | 6,002,520 | 0.3% | 81.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,002,340 | 0.3% | 82.2% |
| POP_TOP LOAD_FAST | 6,001,740 | 0.3% | 82.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 6,001,460 | 0.3% | 82.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 6,001,140 | 0.3% | 83.2% |
| PUSH_NULL CALL | 6,001,060 | 0.3% | 83.5% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 6,000,840 | 0.3% | 83.8% |
| CALL STORE_FAST | 6,000,660 | 0.3% | 84.1% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 6,000,600 | 0.3% | 84.5% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_FALSE | 6,000,540 | 0.3% | 84.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_ALWAYS_TRUE | 6,000,520 | 0.3% | 85.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 6,000,440 | 0.3% | 85.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 6,000,420 | 0.3% | 85.8% |
| LOAD_FAST POP_JUMP_IF_NONE | 6,000,420 | 0.3% | 86.1% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 6,000,360 | 0.3% | 86.4% |
| RETURN_VALUE RETURN_VALUE | 6,000,360 | 0.3% | 86.7% |
| LOAD_FAST PUSH_NULL | 6,000,360 | 0.3% | 87.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 6,000,360 | 0.3% | 87.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_LIST | 6,000,360 | 0.3% | 87.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL | 6,000,240 | 0.3% | 88.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 6,000,220 | 0.3% | 88.3% |
| STORE_FAST LOAD_GLOBAL_MODULE | 6,000,200 | 0.3% | 88.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 6,000,180 | 0.3% | 89.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 6,000,180 | 0.3% | 89.3% |
| RETURN_CONST EXIT_INIT_CHECK | 6,000,120 | 0.3% | 89.6% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 6,000,120 | 0.3% | 90.0% |
| POP_TOP RESUME_CHECK | 6,000,120 | 0.3% | 90.3% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 6,000,120 | 0.3% | 90.6% |
| EXIT_INIT_CHECK RETURN_VALUE | 6,000,120 | 0.3% | 90.9% |
| BINARY_OP STORE_FAST | 6,000,120 | 0.3% | 91.3% |
| LOAD_ATTR_INSTANCE_VALUE CALL | 6,000,100 | 0.3% | 91.6% |
| CALL CALL_METHOD_DESCRIPTOR_O | 6,000,100 | 0.3% | 91.9% |
| TO_BOOL POP_JUMP_IF_FALSE | 6,000,060 | 0.3% | 92.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 6,000,060 | 0.3% | 92.6% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 6,000,060 | 0.3% | 92.9% |
| CACHE POP_TOP | 6,000,060 | 0.3% | 93.2% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 6,000,040 | 0.3% | 93.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 6,000,040 | 0.3% | 93.8% |
| LOAD_CONST BINARY_OP | 6,000,040 | 0.3% | 94.2% |
| STORE_FAST JUMP_BACKWARD | 6,000,000 | 0.3% | 94.5% |
| SEND END_ASYNC_FOR | 6,000,000 | 0.3% | 94.8% |
| RETURN_GENERATOR INTERPRETER_EXIT | 6,000,000 | 0.3% | 95.1% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR | 6,000,000 | 0.3% | 95.5% |
| LOAD_FAST BINARY_SLICE | 6,000,000 | 0.3% | 95.8% |
| LOAD_CONST BINARY_SLICE | 6,000,000 | 0.3% | 96.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_INTRINSIC_1 | 6,000,000 | 0.3% | 96.4% |
| GET_AITER GET_ANEXT | 6,000,000 | 0.3% | 96.8% |
| CACHE RETURN_GENERATOR | 6,000,000 | 0.3% | 97.1% |
| BINARY_SUBSCR LOAD_GLOBAL_MODULE | 6,000,000 | 0.3% | 97.4% |
| BINARY_OP_ADD_INT LOAD_CONST | 6,000,000 | 0.3% | 97.7% |
| LOAD_ATTR_INSTANCE_VALUE GET_AITER | 5,999,940 | 0.3% | 98.0% |
| END_ASYNC_FOR JUMP_BACKWARD | 5,999,940 | 0.3% | 98.4% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 5,999,760 | 0.3% | 98.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_NONE | 5,999,480 | 0.3% | 99.0% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 3,932,160 | 0.2% | 99.2% |
| RETURN_CONST CALL_ALLOC_AND_ENTER_INIT | 3,932,160 | 0.2% | 99.4% |
| JUMP_BACKWARD LOAD_FAST | 3,932,160 | 0.2% | 99.7% |
| RETURN_CONST LOAD_FAST_LOAD_FAST | 2,067,900 | 0.1% | 99.8% |
| RETURN_VALUE CALL_ALLOC_AND_ENTER_INIT | 2,067,840 | 0.1% | 99.9% |
| JUMP_BACKWARD RETURN_CONST | 2,067,840 | 0.1% | 100.0% |
| TO_BOOL_NONE TO_BOOL_ALWAYS_TRUE | 51,660 | 0.0% | 100.0% |
| TO_BOOL_ALWAYS_TRUE TO_BOOL_NONE | 51,640 | 0.0% | 100.0% |
| SEND SEND | 24,440 | 0.0% | 100.0% |
| CALL CALL | 3,540 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 2,420 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,780 | 0.0% | 100.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 1,760 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000,000 | 50.0% |
| LOAD_CONST | 6,000,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,000,000 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 106,137,720 | 89.8% |
| POP_TOP | 6,000,060 | 5.1% |
| RETURN_GENERATOR | 6,000,000 | 5.1% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,000,000 | 100.0% |
| BINARY_SUBSCR | 1,460 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,000,000 | 100.0% |
| BINARY_SUBSCR | 1,460 | 0.0% |
| BINARY_SUBSCR_DICT | 20 | 0.0% |


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

### END_ASYNC_FOR

<details>
<summary> Successors and predecessors for END_ASYNC_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 6,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 5,999,940 | 100.0% |
| RETURN_CONST | 60 | 0.0% |


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND | 94,136,760 | 100.0% |
| RETURN_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 94,136,760 | 100.0% |
| POP_TOP | 60 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,000,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,000,120 | 100.0% |


</details>

### GET_AITER

<details>
<summary> Successors and predecessors for GET_AITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,999,940 | 100.0% |
| RETURN_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ANEXT | 6,000,000 | 100.0% |


</details>

### GET_ANEXT

<details>
<summary> Successors and predecessors for GET_ANEXT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 94,136,760 | 94.0% |
| GET_AITER | 6,000,000 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100,136,760 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 44.4% |
| CALL_BUILTIN_CLASS | 180 | 33.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 280 | 51.9% |
| FOR_ITER | 140 | 25.9% |
| FOR_ITER_RANGE | 120 | 22.2% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 94,136,760 | 79.7% |
| RETURN_CONST | 18,000,780 | 15.2% |
| RETURN_GENERATOR | 6,000,000 | 5.1% |
| RETURN_VALUE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 180 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 600 | 41.7% |
| STORE_FAST | 300 | 20.8% |
| POP_TOP | 300 | 20.8% |
| POP_JUMP_IF_NOT_NONE | 120 | 8.3% |
| POP_JUMP_IF_FALSE | 60 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 900 | 62.5% |
| LOAD_GLOBAL_MODULE | 320 | 22.2% |
| LOAD_FAST_LOAD_FAST | 60 | 4.2% |
| LOAD_DEREF | 60 | 4.2% |
| LOAD_CONST | 60 | 4.2% |


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
| RESUME_CHECK | 94,136,760 | 79.7% |
| CALL_METHOD_DESCRIPTOR_O | 12,000,360 | 10.2% |
| RETURN_CONST | 6,002,520 | 5.1% |
| CACHE | 6,000,060 | 5.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 88,136,880 | 74.6% |
| RETURN_CONST | 18,000,840 | 15.2% |
| LOAD_FAST | 6,001,740 | 5.1% |
| RESUME_CHECK | 6,000,120 | 5.1% |
| LOAD_CONST | 720 | 0.0% |


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
| LOAD_FAST | 6,000,360 | 100.0% |
| LOAD_ATTR_MODULE | 1,780 | 0.0% |
| LOAD_ATTR | 260 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 6,001,060 | 100.0% |
| LOAD_FAST | 660 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_CONST | 180 | 0.0% |
| CALL_PY_EXACT_ARGS | 120 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 6,000,000 | 100.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_PY_EXACT_ARGS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 6,000,000 | 100.0% |
| GET_AWAITABLE | 60 | 0.0% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,000,360 | 50.0% |
| EXIT_INIT_CHECK | 6,000,120 | 50.0% |
| LOAD_FAST | 1,080 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 600 | 0.0% |
| IS_OP | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,000,360 | 50.0% |
| LOAD_FAST_LOAD_FAST | 3,932,160 | 32.8% |
| CALL_ALLOC_AND_ENTER_INIT | 2,067,840 | 17.2% |
| STORE_FAST | 840 | 0.0% |
| TO_BOOL_BOOL | 700 | 0.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 6,000,240 | 100.0% |
| TO_BOOL | 1,480 | 0.0% |
| RETURN_VALUE | 200 | 0.0% |
| COPY | 80 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,000,060 | 100.0% |
| TO_BOOL | 1,480 | 0.0% |
| TO_BOOL_BOOL | 460 | 0.0% |
| TO_BOOL_INT | 120 | 0.0% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


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
| LOAD_CONST | 6,000,040 | 100.0% |
| BINARY_OP | 1,580 | 0.0% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |
| UNARY_INVERT | 120 | 0.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000,120 | 100.0% |
| BINARY_OP | 1,580 | 0.0% |
| COPY | 120 | 0.0% |
| UNARY_INVERT | 60 | 0.0% |
| TO_BOOL_INT | 40 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 180 | 42.9% |
| STORE_FAST | 120 | 28.6% |
| LOAD_ATTR_SLOT | 120 | 28.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 71.4% |
| STORE_FAST | 120 | 28.6% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 60 | 25.0% |
| RESUME_CHECK | 60 | 25.0% |
| POP_TOP | 60 | 25.0% |
| BUILD_TUPLE | 60 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 37.5% |
| LOAD_GLOBAL_MODULE | 60 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 60 | 12.5% |
| LOAD_FAST_LOAD_FAST | 60 | 12.5% |
| LOAD_CONST | 60 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 37.5% |
| CALL | 100 | 20.8% |
| RETURN_VALUE | 60 | 12.5% |
| BUILD_MAP | 60 | 12.5% |
| CALL_PY_EXACT_ARGS | 40 | 8.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 6,001,060 | 50.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,000,100 | 50.0% |
| CALL | 3,540 | 0.0% |
| LOAD_FAST | 760 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000,660 | 50.0% |
| CALL_METHOD_DESCRIPTOR_O | 6,000,100 | 50.0% |
| CALL | 3,540 | 0.0% |
| CALL_PY_EXACT_ARGS | 1,100 | 0.0% |
| LOAD_FAST | 360 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 40.0% |
| CALL_INTRINSIC_1 | 120 | 40.0% |
| DICT_MERGE | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 240 | 80.0% |
| COPY_FREE_VARS | 60 | 20.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,136,760 | 93.6% |
| LOAD_ATTR_INSTANCE_VALUE | 6,000,000 | 6.4% |
| LIST_EXTEND | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 94,136,760 | 100.0% |
| CALL_FUNCTION_EX | 120 | 0.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| RESUME_CHECK | 60 | 33.3% |
| POP_TOP | 60 | 33.3% |


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
| LOAD_GLOBAL_MODULE | 60 | 50.0% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 18.2% |
| CALL_LEN | 120 | 18.2% |
| CALL_BUILTIN_FAST | 120 | 18.2% |
| BINARY_OP | 120 | 18.2% |
| UNARY_NOT | 60 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 200 | 30.3% |
| TO_BOOL_BOOL | 200 | 30.3% |
| TO_BOOL | 80 | 12.1% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 12.1% |
| POP_EXCEPT | 60 | 9.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 600 | 76.9% |
| CALL_FUNCTION_EX | 60 | 7.7% |
| CALL_ALLOC_AND_ENTER_INIT | 60 | 7.7% |
| CACHE | 60 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 660 | 84.6% |
| RETURN_GENERATOR | 60 | 7.7% |
| MAKE_CELL | 60 | 7.7% |


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
| RETURN_GENERATOR | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |


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
| LOAD_CONST | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 300 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 88,136,880 | 88.0% |
| STORE_FAST | 6,000,000 | 6.0% |
| END_ASYNC_FOR | 5,999,940 | 6.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ANEXT | 94,136,760 | 94.0% |
| LOAD_FAST | 3,932,160 | 3.9% |
| RETURN_CONST | 2,067,840 | 2.1% |
| FOR_ITER_RANGE | 120 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 540 | 81.8% |
| POP_TOP | 60 | 9.1% |
| POP_JUMP_IF_FALSE | 60 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 72.7% |
| LOAD_GLOBAL_BUILTIN | 120 | 18.2% |
| NOP | 60 | 9.1% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 120 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,420 | 51.3% |
| LOAD_GLOBAL_MODULE | 660 | 14.0% |
| LOAD_ATTR | 540 | 11.4% |
| LOAD_ATTR_INSTANCE_VALUE | 360 | 7.6% |
| LOAD_ATTR_MODULE | 260 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 740 | 15.7% |
| LOAD_ATTR_MODULE | 660 | 14.0% |
| LOAD_ATTR_INSTANCE_VALUE | 620 | 13.1% |
| LOAD_ATTR | 540 | 11.4% |
| CALL | 380 | 8.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ANEXT | 100,136,760 | 73.6% |
| LOAD_FAST | 24,000,600 | 17.6% |
| LOAD_FAST_LOAD_FAST | 6,000,120 | 4.4% |
| BINARY_OP_ADD_INT | 6,000,000 | 4.4% |
| STORE_ATTR_INSTANCE_VALUE | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SEND | 100,136,780 | 73.6% |
| COMPARE_OP_INT | 12,000,580 | 8.8% |
| LOAD_FAST | 6,002,700 | 4.4% |
| BINARY_OP_ADD_INT | 6,000,040 | 4.4% |
| BINARY_OP | 6,000,040 | 4.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 600 | 66.7% |
| STORE_FAST | 120 | 13.3% |
| RESUME_CHECK | 60 | 6.7% |
| NOP | 60 | 6.7% |
| LOAD_ATTR_METHOD_NO_DICT | 60 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 66.7% |
| LOAD_CONST | 120 | 13.3% |
| STORE_FAST | 60 | 6.7% |
| PUSH_NULL | 60 | 6.7% |
| POP_JUMP_IF_NOT_NONE | 60 | 6.7% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 106,139,340 | 49.6% |
| POP_JUMP_IF_FALSE | 32,069,820 | 15.0% |
| RESUME_CHECK | 24,003,540 | 11.2% |
| LOAD_GLOBAL_BUILTIN | 12,001,620 | 5.6% |
| LOAD_CONST | 6,002,700 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 88,136,760 | 41.2% |
| LOAD_ATTR_INSTANCE_VALUE | 60,005,200 | 28.0% |
| LOAD_CONST | 24,000,600 | 11.2% |
| CALL_LEN | 12,000,060 | 5.6% |
| CALL_PY_EXACT_ARGS | 6,001,460 | 2.8% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,000,300 | 33.3% |
| STORE_ATTR_INSTANCE_VALUE | 12,000,000 | 33.3% |
| RESUME_CHECK | 6,000,120 | 16.7% |
| RETURN_VALUE | 3,932,160 | 10.9% |
| RETURN_CONST | 2,067,900 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 18,000,240 | 50.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,000,220 | 16.7% |
| LOAD_CONST | 6,000,120 | 16.7% |
| BINARY_SUBSCR | 6,000,000 | 16.7% |
| STORE_ATTR_SLOT | 720 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 280 | 21.5% |
| POP_TOP | 220 | 16.9% |
| LOAD_FAST | 140 | 10.8% |
| STORE_FAST | 120 | 9.2% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 960 | 73.8% |
| LOAD_GLOBAL_BUILTIN | 320 | 24.6% |
| LOAD_ATTR | 20 | 1.5% |


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
| COPY_FREE_VARS | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 12,000,720 | 28.6% |
| TO_BOOL_BOOL | 6,002,340 | 14.3% |
| TO_BOOL_ALWAYS_TRUE | 6,000,540 | 14.3% |
| TO_BOOL_LIST | 6,000,360 | 14.3% |
| TO_BOOL | 6,000,060 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,069,820 | 76.3% |
| RETURN_CONST | 9,932,880 | 23.6% |
| LOAD_CONST | 660 | 0.0% |
| POP_TOP | 240 | 0.0% |
| LOAD_GLOBAL_MODULE | 200 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000,420 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 180 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000,180 | 100.0% |
| RETURN_CONST | 360 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 70.6% |
| LOAD_GLOBAL_MODULE | 180 | 17.6% |
| LOAD_DEREF | 60 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 420 | 41.2% |
| LOAD_FAST | 300 | 29.4% |
| NOP | 120 | 11.8% |
| LOAD_FAST_LOAD_FAST | 120 | 11.8% |
| LOAD_GLOBAL | 60 | 5.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 600 | 66.7% |
| TO_BOOL_INT | 180 | 20.0% |
| TO_BOOL | 120 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 33.3% |
| LOAD_CONST | 180 | 20.0% |
| STORE_FAST | 120 | 13.3% |
| LOAD_GLOBAL_BUILTIN | 100 | 11.1% |
| RETURN_CONST | 60 | 6.7% |


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
| POP_TOP | 18,000,840 | 50.0% |
| POP_JUMP_IF_FALSE | 9,932,880 | 27.6% |
| STORE_ATTR_INSTANCE_VALUE | 6,000,600 | 16.7% |
| JUMP_BACKWARD | 2,067,840 | 5.7% |
| STORE_ATTR_SLOT | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 18,000,780 | 50.0% |
| POP_TOP | 6,002,520 | 16.7% |
| EXIT_INIT_CHECK | 6,000,120 | 16.7% |
| CALL_ALLOC_AND_ENTER_INIT | 3,932,160 | 10.9% |
| LOAD_FAST_LOAD_FAST | 2,067,900 | 5.7% |


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 100,136,780 | 100.0% |
| SEND | 24,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 94,136,760 | 94.0% |
| END_ASYNC_FOR | 6,000,000 | 6.0% |
| SEND | 24,440 | 0.0% |
| SEND_GEN | 20 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 820 | 67.2% |
| LOAD_ATTR_INSTANCE_VALUE | 240 | 19.7% |
| STORE_ATTR | 60 | 4.9% |
| LOAD_FAST_LOAD_FAST | 60 | 4.9% |
| SWAP | 40 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 800 | 65.6% |
| LOAD_FAST | 180 | 14.8% |
| RETURN_CONST | 120 | 9.8% |
| STORE_ATTR_SLOT | 60 | 4.9% |
| STORE_ATTR | 60 | 4.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 94,136,760 | 79.7% |
| CALL_LEN | 12,000,300 | 10.2% |
| CALL | 6,000,660 | 5.1% |
| BINARY_OP | 6,000,120 | 5.1% |
| RETURN_VALUE | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 106,139,340 | 89.8% |
| LOAD_GLOBAL_MODULE | 6,000,200 | 5.1% |
| JUMP_BACKWARD | 6,000,000 | 5.1% |
| JUMP_FORWARD | 540 | 0.0% |
| NOP | 300 | 0.0% |


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
| LOAD_FAST | 60 | 25.0% |
| LOAD_ATTR | 60 | 25.0% |
| BINARY_OP_SUBTRACT_INT | 60 | 25.0% |
| BINARY_OP_ADD_INT | 60 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 80 | 33.3% |
| STORE_FAST | 60 | 25.0% |
| POP_EXCEPT | 60 | 25.0% |
| STORE_ATTR | 40 | 16.7% |


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
| CALL_INTRINSIC_1 | 94,136,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 94,136,760 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,000,040 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,000,000 | 100.0% |
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
| LOAD_CONST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 100.0% |


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
| RETURN_CONST | 3,932,160 | 65.5% |
| RETURN_VALUE | 2,067,840 | 34.5% |
| PUSH_NULL | 40 | 0.0% |
| LOAD_FAST | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,000,060 | 100.0% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 38.5% |
| LOAD_GLOBAL_BUILTIN | 180 | 23.1% |
| LOAD_ATTR_INSTANCE_VALUE | 160 | 20.5% |
| CALL | 60 | 7.7% |
| RETURN_VALUE | 40 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 23.1% |
| GET_ITER | 180 | 23.1% |
| LOAD_GLOBAL_BUILTIN | 120 | 15.4% |
| COMPARE_OP | 120 | 15.4% |
| STORE_FAST | 60 | 7.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 120 | 66.7% |
| TO_BOOL_BOOL | 60 | 33.3% |


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
| LOAD_FAST | 12,000,060 | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,000,300 | 100.0% |
| COPY | 120 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 120 | 40.0% |
| LOAD_CONST | 60 | 20.0% |
| LOAD_FAST | 40 | 13.3% |
| LOAD_ATTR | 40 | 13.3% |
| CALL | 40 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 40.0% |
| POP_TOP | 120 | 40.0% |
| RETURN_VALUE | 60 | 20.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 560 | 54.9% |
| CALL | 220 | 21.6% |
| LOAD_FAST | 120 | 11.8% |
| LOAD_ATTR | 120 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 360 | 35.3% |
| CALL | 140 | 13.7% |
| STORE_FAST | 120 | 11.8% |
| GET_ITER | 120 | 11.8% |
| TO_BOOL_BOOL | 80 | 7.8% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000,180 | 50.0% |
| CALL | 6,000,100 | 50.0% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,000,360 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 12,000,000 | 66.6% |
| LOAD_FAST | 6,001,460 | 33.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,540 | 0.0% |
| CALL | 1,100 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,004,560 | 100.0% |
| COPY_FREE_VARS | 600 | 0.0% |
| RETURN_GENERATOR | 60 | 0.0% |


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
| LOAD_CONST | 12,000,580 | 100.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,000,720 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 280 | 93.3% |
| FOR_ITER | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 180 | 60.0% |
| LOAD_FAST | 120 | 40.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 120 | 50.0% |
| GET_ITER | 120 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 50.0% |
| LOAD_CONST | 120 | 50.0% |


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
| LOAD_FAST | 60,005,200 | 90.9% |
| LOAD_FAST_LOAD_FAST | 6,000,220 | 9.1% |
| LOAD_ATTR | 620 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 12,001,120 | 18.2% |
| TO_BOOL_BOOL | 6,000,840 | 9.1% |
| TO_BOOL_ALWAYS_TRUE | 6,000,520 | 9.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,000,440 | 9.1% |
| TO_BOOL_LIST | 6,000,360 | 9.1% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 12,001,120 | 100.0% |
| LOAD_FAST | 460 | 0.0% |
| LOAD_ATTR | 320 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000,360 | 50.0% |
| LOAD_GLOBAL_MODULE | 6,000,060 | 50.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 560 | 0.0% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |
| CALL_PY_EXACT_ARGS | 240 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,000,440 | 99.9% |
| LOAD_FAST | 1,720 | 0.0% |
| LOAD_ATTR | 740 | 0.0% |
| RETURN_VALUE | 280 | 0.0% |
| LOAD_ATTR_SLOT | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,001,140 | 100.0% |
| CALL_PY_EXACT_ARGS | 1,540 | 0.0% |
| CALL | 440 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| LOAD_CONST | 120 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,660 | 68.0% |
| LOAD_ATTR | 660 | 27.0% |
| LOAD_FAST | 120 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,780 | 73.0% |
| LOAD_ATTR | 260 | 10.7% |
| LOAD_FAST | 120 | 4.9% |
| UNARY_INVERT | 60 | 2.5% |
| STORE_FAST | 60 | 2.5% |


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
| LOAD_FAST | 1,260 | 95.5% |
| LOAD_ATTR | 60 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 240 | 18.2% |
| LOAD_CONST | 240 | 18.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 220 | 16.7% |
| LOAD_ATTR | 200 | 15.2% |
| TO_BOOL_BOOL | 160 | 12.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,001,180 | 100.0% |
| LOAD_FAST | 340 | 0.0% |
| LOAD_GLOBAL | 320 | 0.0% |
| POP_TOP | 180 | 0.0% |
| STORE_FAST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,001,620 | 100.0% |
| LOAD_DEREF | 600 | 0.0% |
| CALL_ISINSTANCE | 300 | 0.0% |
| CALL_BUILTIN_CLASS | 180 | 0.0% |
| CHECK_EXC_MATCH | 120 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000,200 | 25.0% |
| LOAD_ATTR_METHOD_NO_DICT | 6,000,060 | 25.0% |
| LOAD_GLOBAL_MODULE | 6,000,040 | 25.0% |
| BINARY_SUBSCR | 6,000,000 | 25.0% |
| LOAD_GLOBAL | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 12,000,300 | 50.0% |
| LOAD_FAST | 6,000,420 | 25.0% |
| LOAD_GLOBAL_MODULE | 6,000,040 | 25.0% |
| LOAD_ATTR_MODULE | 1,660 | 0.0% |
| LOAD_ATTR | 660 | 0.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 440 | 73.3% |
| LOAD_SUPER_ATTR | 160 | 26.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 40.0% |
| CALL_PY_EXACT_ARGS | 200 | 33.3% |
| CALL | 100 | 16.7% |
| LOAD_FAST_LOAD_FAST | 60 | 10.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 106,137,720 | 78.0% |
| CALL_PY_EXACT_ARGS | 18,004,560 | 13.2% |
| POP_TOP | 6,000,120 | 4.4% |
| CALL_ALLOC_AND_ENTER_INIT | 6,000,060 | 4.4% |
| COPY_FREE_VARS | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 94,136,760 | 69.1% |
| LOAD_FAST | 24,003,540 | 17.6% |
| LOAD_GLOBAL_BUILTIN | 12,001,180 | 8.8% |
| LOAD_FAST_LOAD_FAST | 6,000,120 | 4.4% |
| LOAD_GLOBAL_MODULE | 880 | 0.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| SEND | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 18,000,240 | 100.0% |
| LOAD_FAST | 1,760 | 0.0% |
| STORE_ATTR | 800 | 0.0% |
| SWAP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 12,000,000 | 66.7% |
| RETURN_CONST | 6,000,600 | 33.3% |
| LOAD_CONST | 780 | 0.0% |
| LOAD_FAST | 720 | 0.0% |
| LOAD_GLOBAL_MODULE | 300 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020 | 56.7% |
| LOAD_FAST_LOAD_FAST | 720 | 40.0% |
| STORE_ATTR | 60 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 540 | 30.0% |
| LOAD_CONST | 540 | 30.0% |
| RETURN_CONST | 360 | 20.0% |
| LOAD_FAST | 360 | 20.0% |


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

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,000,520 | 99.1% |
| TO_BOOL_NONE | 51,660 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,000,540 | 99.1% |
| TO_BOOL_NONE | 51,640 | 0.9% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,000,840 | 100.0% |
| RETURN_VALUE | 700 | 0.0% |
| TO_BOOL | 460 | 0.0% |
| CALL_ISINSTANCE | 380 | 0.0% |
| COPY | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,002,340 | 100.0% |
| POP_JUMP_IF_TRUE | 600 | 0.0% |
| UNARY_NOT | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 200 | 41.7% |
| TO_BOOL | 120 | 25.0% |
| LOAD_FAST | 80 | 16.7% |
| LOAD_ATTR | 40 | 8.3% |
| BINARY_OP | 40 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 240 | 50.0% |
| POP_JUMP_IF_TRUE | 180 | 37.5% |
| UNARY_NOT | 60 | 12.5% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,000,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,000,360 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,999,480 | 99.1% |
| TO_BOOL_ALWAYS_TRUE | 51,640 | 0.9% |
| LOAD_ATTR_SLOT | 240 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,999,760 | 99.1% |
| TO_BOOL_ALWAYS_TRUE | 51,660 | 0.9% |


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
| specialization.deferred |      6000000 | 100.0% |
|          hit |          180 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 1.4% |
| Failure | 1,460 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| sequence int | 1,460 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |           60 | 75.0% |

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
| specialization.deferred |      6000180 | 19.9% |
| specialization.deopt |       103300 | 0.3% |
|          hit |     18632340 | 61.9% |
|         miss |      5475100 | 18.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 103,900 | 98.6% |
| Failure | 1,480 | 1.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 1,460 | 98.6% |
| sequence | 20 | 1.4% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6000360 | 50.0% |
|          hit |      6000300 | 50.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.7% |
| Failure | 1,580 | 96.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| floor divide | 1,460 | 92.4% |
| and int | 80 | 5.1% |
| or | 40 | 2.5% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     12002340 | 20.0% |
|          hit |     48009180 | 80.0% |
|         miss |          360 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,700 | 32.4% |
| Failure | 3,540 | 67.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class no vectorcall | 1,500 | 42.4% |
| other | 1,460 | 41.2% |
| cfunc noargs | 180 | 5.1% |
| class mutable | 80 | 2.3% |
| meth descr method fastcall keywords | 60 | 1.7% |
| code complex parameters | 60 | 1.7% |
| cfunc varargs | 40 | 1.1% |
| wrong number arguments | 40 | 1.1% |
| no dict | 40 | 1.1% |
| init not simple | 20 | 0.6% |
| operator wrapper | 20 | 0.6% |
| cfunc varargs keywords | 20 | 0.6% |
| cmethod | 20 | 0.6% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          120 | 0.0% |
|          hit |     12000720 | 100.0% |

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
| specialization.deferred |          120 | 16.7% |
|          hit |          540 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 33.3% |
| Failure | 40 | 66.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 40 | 100.0% |


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
| specialization.deferred |         1760 | 0.0% |
|          hit |     84015640 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,420 | 81.8% |
| Failure | 540 | 18.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 140 | 25.9% |
| method | 140 | 25.9% |
| has managed dict | 120 | 22.2% |
| class attr simple | 40 | 7.4% |
| metaclass attribute | 40 | 7.4% |
| non object slot | 40 | 7.4% |
| class attr descriptor | 20 | 3.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     36007420 | 100.0% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,280 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          600 | 78.9% |

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
| specialization.deferred |    100136760 | 100.0% |
|          hit |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.1% |
| Failure | 24,440 | 99.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| async generator send | 24,440 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          300 | 0.0% |
|          hit |     18004680 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 860 | 93.5% |
| Failure | 60 | 6.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| overridden | 40 | 66.7% |
| overriding descriptor | 20 | 33.3% |


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
| Basic | 1,201,293,240 | 64.7% |
| Not specialized | 295,810,300 | 15.9% |
| Specialized | 358,807,220 | 19.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,023,800 | 100.0% |
| SEND | 100,136,760 | 0.0% |
| CALL | 12,002,340 | 0.0% |
| BINARY_OP | 6,000,360 | 0.0% |
| TO_BOOL | 6,000,180 | 0.0% |
| BINARY_SUBSCR | 6,000,000 | 0.0% |
| LOAD_ATTR | 1,760 | 0.0% |
| STORE_ATTR | 300 | 0.0% |
| FOR_ITER | 120 | 0.0% |
| COMPARE_OP | 120 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 2,737,840 | 49.8% |
| TO_BOOL_NONE | 2,737,260 | 49.8% |
| RESUME_CHECK | 8,520 | 0.2% |
| RESUME | 8,520 | 0.2% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 240 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNARY_NOT | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 118,137,840 | 83.1% |
| Calls to Python functions inlined | 24,006,120 | 16.9% |
| Calls via PyEval_EvalFrame (total) | 118,137,840 | 83.1% |
| Calls via PyEval_EvalFrame (vector) | 18,001,020 | 12.7% |
| Calls via PyEval_EvalFrame (generator) | 100,136,820 | 70.4% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 18,001,020 | 12.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 12,000,120 | 8.4% |
| Calls via PyEval_EvalFrame (method) | 240 | 0.0% |
| Frames pushed | 48,007,200 | 33.8% |
| Frame objects created | 3,932,280 | 2.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 194,276,660 | 52.5% |
| Frees to freelist | 194,277,660 |  |
| Allocations | 176,107,660 | 47.5% |
| Allocations to 512 bytes | 176,107,480 | 47.5% |
| Allocations to 4 kbytes | 180 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 176,107,540 |  |
| New values | 180 |  |
| Interpreter increfs | 753,966,880 | 58.7% |
| Interpreter decrefs | 1,094,344,800 | 62.2% |
| Increfs | 530,124,582 | 41.3% |
| Decrefs | 666,265,642 | 37.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 5,495 |  |
| Method cache misses | 165 |  |
| Method cache collisions | 176 |  |
| Method cache dunder hits | 6,002,749 |  |
| Method cache dunder misses | 11 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 7,760 | 0 | 43,471,120 |
| 1 | 700 | 0 | 44,746,960 |
| 2 | 60 | 0 | 35,851,920 |


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
