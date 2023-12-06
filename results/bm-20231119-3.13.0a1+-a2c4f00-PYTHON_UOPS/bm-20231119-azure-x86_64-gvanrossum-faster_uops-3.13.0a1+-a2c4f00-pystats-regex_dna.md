
# Pystats results

- benchmark: regex_dna
- fork: gvanrossum
- ref: faster-uops
- commit hash: a2c4f00
- commit date: 2023-11-19T11:22:02-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 210,060 | 19.7% | 19.7% |  |
| POP_JUMP_IF_FALSE | 65,820 | 6.2% | 25.9% |  |
| STORE_FAST | 61,580 | 5.8% | 31.7% |  |
| LOAD_GLOBAL_MODULE | 59,660 | 5.6% | 37.3% |  |
| LOAD_CONST | 49,480 | 4.6% | 41.9% |  |
| LOAD_GLOBAL_BUILTIN | 42,480 | 4.0% | 45.9% |  |
| RESUME_CHECK | 32,380 | 3.0% | 48.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 31,640 | 3.0% | 51.9% |  |
| PUSH_NULL | 28,020 | 2.6% | 54.5% |  |
| LOAD_FAST_LOAD_FAST | 27,920 | 2.6% | 57.2% |  |
| POP_TOP | 24,800 | 2.3% | 59.5% |  |
| EXTENDED_ARG | 24,560 | 2.3% | 61.8% |  |
| RETURN_VALUE | 22,760 | 2.1% | 63.9% |  |
| ENTER_EXECUTOR | 19,440 | 1.8% | 65.7% |  |
| CALL_BUILTIN_O | 17,340 | 1.6% | 67.4% |  |
| TO_BOOL_BOOL | 14,840 | 1.4% | 68.8% |  |
| IS_OP | 12,440 | 1.2% | 69.9% |  |
| CALL_LEN | 12,400 | 1.2% | 71.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 11,880 | 1.1% | 72.2% |  |
| CALL_PY_EXACT_ARGS | 11,820 | 1.1% | 73.3% |  |
| CALL_ISINSTANCE | 11,600 | 1.1% | 74.4% |  |
| CONTAINS_OP | 11,440 | 1.1% | 75.5% |  |
| POP_JUMP_IF_TRUE | 11,320 | 1.1% | 76.5% |  |
| RETURN_CONST | 11,160 | 1.0% | 77.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,120 | 1.0% | 78.6% |  |
| BINARY_OP | 10,820 | 1.0% | 79.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 10,680 | 1.0% | 80.7% |  |
| BUILD_TUPLE | 10,560 | 1.0% | 81.6% |  |
| CALL | 9,840 | 0.9% | 82.6% |  |
| JUMP_FORWARD | 9,360 | 0.9% | 83.4% |  |
| STORE_FAST_STORE_FAST | 8,660 | 0.8% | 84.3% |  |
| BINARY_OP_ADD_INT | 8,480 | 0.8% | 85.1% |  |
| TO_BOOL_INT | 8,160 | 0.8% | 85.8% |  |
| BINARY_SUBSCR_LIST_INT | 7,880 | 0.7% | 86.6% | 5.6% |
| FOR_ITER_LIST | 7,300 | 0.7% | 87.2% |  |
| COMPARE_OP_STR | 7,220 | 0.7% | 87.9% | 5.8% |
| LOAD_ATTR | 7,040 | 0.7% | 88.6% |  |
| NOP | 6,900 | 0.6% | 89.2% |  |
| BUILD_LIST | 6,820 | 0.6% | 89.9% |  |
| GET_ITER | 6,660 | 0.6% | 90.5% |  |
| COMPARE_OP_INT | 6,620 | 0.6% | 91.1% |  |
| CALL_LIST_APPEND | 6,100 | 0.6% | 91.7% |  |
| INTERPRETER_EXIT | 5,860 | 0.5% | 92.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,420 | 0.5% | 92.7% |  |
| BINARY_SUBSCR_STR_INT | 5,260 | 0.5% | 93.2% | 8.0% |
| FOR_ITER | 4,520 | 0.4% | 93.7% |  |
| BINARY_SUBSCR_GETITEM | 4,040 | 0.4% | 94.0% |  |
| POP_JUMP_IF_NOT_NONE | 3,900 | 0.4% | 94.4% |  |
| BINARY_OP_SUBTRACT_INT | 3,420 | 0.3% | 94.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,140 | 0.3% | 95.0% |  |
| TO_BOOL_LIST | 3,120 | 0.3% | 95.3% | 2.6% |
| LOAD_ATTR_MODULE | 2,640 | 0.2% | 95.6% |  |
| TO_BOOL | 2,480 | 0.2% | 95.8% |  |
| CALL_TYPE_1 | 2,280 | 0.2% | 96.0% |  |
| FOR_ITER_RANGE | 2,240 | 0.2% | 96.2% |  |
| COPY | 2,020 | 0.2% | 96.4% |  |
| TO_BOOL_NONE | 2,000 | 0.2% | 96.6% |  |
| JUMP_BACKWARD | 1,940 | 0.2% | 96.8% |  |
| BINARY_SUBSCR_DICT | 1,880 | 0.2% | 97.0% |  |
| CALL_BUILTIN_CLASS | 1,860 | 0.2% | 97.1% |  |
| POP_JUMP_IF_NONE | 1,820 | 0.2% | 97.3% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,760 | 0.2% | 97.5% |  |
| CALL_PY_WITH_DEFAULTS | 1,600 | 0.2% | 97.6% |  |
| STORE_SUBSCR_LIST_INT | 1,360 | 0.1% | 97.7% |  |
| STORE_SUBSCR | 1,340 | 0.1% | 97.9% |  |
| COMPARE_OP | 1,200 | 0.1% | 98.0% |  |
| BINARY_SUBSCR | 1,040 | 0.1% | 98.1% |  |
| UNARY_NOT | 1,040 | 0.1% | 98.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,020 | 0.1% | 98.3% |  |
| STORE_FAST_LOAD_FAST | 960 | 0.1% | 98.4% |  |
| SWAP | 960 | 0.1% | 98.5% |  |
| BUILD_SLICE | 940 | 0.1% | 98.5% |  |
| FOR_ITER_TUPLE | 880 | 0.1% | 98.6% |  |
| EXIT_INIT_CHECK | 860 | 0.1% | 98.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 860 | 0.1% | 98.8% |  |
| CHECK_EXC_MATCH | 840 | 0.1% | 98.9% |  |
| POP_EXCEPT | 840 | 0.1% | 98.9% |  |
| PUSH_EXC_INFO | 840 | 0.1% | 99.0% |  |
| BUILD_MAP | 840 | 0.1% | 99.1% |  |
| LOAD_ATTR_PROPERTY | 840 | 0.1% | 99.2% |  |
| STORE_SUBSCR_DICT | 840 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 760 | 0.1% | 99.3% |  |
| TO_BOOL_STR | 760 | 0.1% | 99.4% |  |
| LOAD_GLOBAL | 700 | 0.1% | 99.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 420 | 0.0% | 99.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 420 | 0.0% | 99.6% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 420 | 0.0% | 99.6% |  |
| CALL_TUPLE_1 | 420 | 0.0% | 99.6% |  |
| UNPACK_SEQUENCE_TUPLE | 420 | 0.0% | 99.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 360 | 0.0% | 99.7% |  |
| LOAD_ATTR_SLOT | 360 | 0.0% | 99.7% |  |
| BINARY_SLICE | 340 | 0.0% | 99.8% |  |
| CALL_BUILTIN_FAST | 320 | 0.0% | 99.8% | 100.0% |
| UNARY_NEGATIVE | 320 | 0.0% | 99.8% |  |
| LIST_APPEND | 320 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 320 | 0.0% | 99.9% |  |
| LOAD_FAST_CHECK | 300 | 0.0% | 99.9% |  |
| LOAD_DEREF | 240 | 0.0% | 99.9% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| RESUME | 100 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_FALSE LOAD_FAST | 50,700 | 4.8% | 4.8% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 31,500 | 3.0% | 7.7% |
| STORE_FAST LOAD_FAST | 29,180 | 2.7% | 10.5% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 27,380 | 2.6% | 13.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 24,760 | 2.3% | 15.3% |
| LOAD_FAST PUSH_NULL | 24,140 | 2.3% | 17.6% |
| LOAD_FAST LOAD_CONST | 20,280 | 1.9% | 19.5% |
| PUSH_NULL LOAD_FAST | 15,720 | 1.5% | 21.0% |
| CALL_BUILTIN_O POP_TOP | 14,180 | 1.3% | 22.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 14,100 | 1.3% | 23.6% |
| LOAD_FAST CALL_BUILTIN_O | 12,500 | 1.2% | 24.8% |
| LOAD_GLOBAL_MODULE IS_OP | 12,080 | 1.1% | 25.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 11,940 | 1.1% | 27.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 11,820 | 1.1% | 28.2% |
| RESUME_CHECK LOAD_FAST | 11,700 | 1.1% | 29.3% |
| POP_TOP LOAD_FAST | 10,880 | 1.0% | 30.3% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 10,340 | 1.0% | 31.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 9,900 | 0.9% | 32.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 9,600 | 0.9% | 33.1% |
| EXTENDED_ARG ENTER_EXECUTOR | 9,000 | 0.8% | 33.9% |
| IS_OP POP_JUMP_IF_FALSE | 8,940 | 0.8% | 34.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 8,620 | 0.8% | 35.6% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 8,300 | 0.8% | 36.4% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 8,260 | 0.8% | 37.1% |
| LOAD_GLOBAL_MODULE BINARY_OP | 8,140 | 0.8% | 37.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 8,060 | 0.8% | 38.7% |
| LOAD_FAST CALL_LEN | 7,540 | 0.7% | 39.4% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 7,440 | 0.7% | 40.1% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 7,380 | 0.7% | 40.8% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 7,240 | 0.7% | 41.4% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 7,080 | 0.7% | 42.1% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 7,080 | 0.7% | 42.8% |
| RETURN_CONST POP_TOP | 6,860 | 0.6% | 43.4% |
| COMPARE_OP_STR POP_JUMP_IF_FALSE | 6,860 | 0.6% | 44.1% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 6,780 | 0.6% | 44.7% |
| BINARY_OP TO_BOOL_INT | 6,740 | 0.6% | 45.3% |
| BINARY_OP_ADD_INT STORE_FAST | 6,740 | 0.6% | 46.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 6,620 | 0.6% | 46.6% |
| CACHE RESUME_CHECK | 6,280 | 0.6% | 47.2% |
| LOAD_FAST LOAD_ATTR | 6,160 | 0.6% | 47.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 6,000 | 0.6% | 48.3% |
| LOAD_CONST COMPARE_OP_STR | 5,920 | 0.6% | 48.9% |
| LOAD_CONST COMPARE_OP_INT | 5,620 | 0.5% | 49.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 5,620 | 0.5% | 49.9% |
| LOAD_ATTR STORE_FAST | 5,580 | 0.5% | 50.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 5,480 | 0.5% | 51.0% |
| PUSH_NULL LOAD_GLOBAL_MODULE | 5,460 | 0.5% | 51.5% |
| LOAD_CONST STORE_FAST | 5,460 | 0.5% | 52.0% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 5,420 | 0.5% | 52.5% |
| BUILD_LIST STORE_FAST | 5,360 | 0.5% | 53.0% |
| RETURN_VALUE STORE_FAST | 5,340 | 0.5% | 53.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 5,220 | 0.5% | 54.0% |
| CALL STORE_FAST | 5,060 | 0.5% | 54.5% |
| RETURN_VALUE INTERPRETER_EXIT | 5,020 | 0.5% | 54.9% |
| LOAD_CONST LOAD_FAST | 4,980 | 0.5% | 55.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 4,940 | 0.5% | 55.9% |
| STORE_FAST LOAD_CONST | 4,940 | 0.5% | 56.3% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 4,880 | 0.5% | 56.8% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 4,760 | 0.4% | 57.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 4,680 | 0.4% | 57.7% |
| JUMP_FORWARD EXTENDED_ARG | 4,480 | 0.4% | 58.1% |
| ENTER_EXECUTOR EXTENDED_ARG | 4,320 | 0.4% | 58.5% |
| NOP LOAD_FAST | 4,260 | 0.4% | 58.9% |
| POP_TOP EXTENDED_ARG | 4,160 | 0.4% | 59.3% |
| EXTENDED_ARG JUMP_FORWARD | 4,160 | 0.4% | 59.7% |
| LOAD_FAST RETURN_VALUE | 4,080 | 0.4% | 60.1% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 4,080 | 0.4% | 60.4% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 4,040 | 0.4% | 60.8% |
| LOAD_FAST CALL | 3,920 | 0.4% | 61.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 3,880 | 0.4% | 61.6% |
| STORE_FAST_STORE_FAST LOAD_FAST | 3,840 | 0.4% | 61.9% |
| LOAD_GLOBAL_MODULE STORE_FAST | 3,840 | 0.4% | 62.3% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 3,760 | 0.4% | 62.6% |
| STORE_FAST STORE_FAST | 3,760 | 0.4% | 63.0% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 3,740 | 0.4% | 63.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 3,740 | 0.4% | 63.7% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST | 3,740 | 0.4% | 64.0% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 3,720 | 0.3% | 64.4% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 3,660 | 0.3% | 64.7% |
| STORE_FAST NOP | 3,600 | 0.3% | 65.1% |
| LOAD_CONST BINARY_SUBSCR_STR_INT | 3,520 | 0.3% | 65.4% |
| BINARY_SUBSCR_STR_INT LOAD_CONST | 3,520 | 0.3% | 65.7% |
| IS_OP POP_JUMP_IF_TRUE | 3,500 | 0.3% | 66.1% |
| EXTENDED_ARG FOR_ITER | 3,480 | 0.3% | 66.4% |
| LOAD_FAST CALL_LIST_APPEND | 3,380 | 0.3% | 66.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 3,380 | 0.3% | 67.0% |
| CALL_LIST_APPEND RETURN_CONST | 3,380 | 0.3% | 67.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 3,380 | 0.3% | 67.7% |
| POP_TOP ENTER_EXECUTOR | 3,360 | 0.3% | 68.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 3,360 | 0.3% | 68.3% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,260 | 0.3% | 68.6% |
| BUILD_TUPLE CALL_BOUND_METHOD_EXACT_ARGS | 3,180 | 0.3% | 68.9% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 3,180 | 0.3% | 69.2% |
| STORE_FAST EXTENDED_ARG | 3,180 | 0.3% | 69.5% |
| CONTAINS_OP EXTENDED_ARG | 3,160 | 0.3% | 69.8% |
| CALL_BUILTIN_O BUILD_TUPLE | 3,160 | 0.3% | 70.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,140 | 0.3% | 70.4% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 3,140 | 0.3% | 70.7% |
| EXTENDED_ARG FOR_ITER_LIST | 3,000 | 0.3% | 70.9% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 2,940 | 0.3% | 71.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320 | 94.1% |
| LOAD_CONST | 20 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 320 | 94.1% |
| STORE_FAST | 20 | 5.9% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,280 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 940 | 90.4% |
| BINARY_SUBSCR | 40 | 3.8% |
| LOAD_CONST | 40 | 3.8% |
| LOAD_FAST | 20 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 620 | 59.6% |
| STORE_FAST | 320 | 30.8% |
| BINARY_SUBSCR | 40 | 3.8% |
| BINARY_SUBSCR_GETITEM | 20 | 1.9% |
| BINARY_SUBSCR_TUPLE_INT | 20 | 1.9% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 840 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 860 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,640 | 39.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,680 | 25.2% |
| BINARY_SUBSCR | 620 | 9.3% |
| BINARY_SUBSCR_TUPLE_INT | 600 | 9.0% |
| CALL_BUILTIN_CLASS | 540 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 2,240 | 33.6% |
| EXTENDED_ARG | 2,160 | 32.4% |
| FOR_ITER | 920 | 13.8% |
| FOR_ITER_RANGE | 900 | 13.5% |
| LOAD_FAST_AND_CLEAR | 320 | 4.8% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,020 | 85.7% |
| RETURN_CONST | 840 | 14.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,600 | 52.2% |
| POP_JUMP_IF_FALSE | 1,860 | 27.0% |
| NOP | 480 | 7.0% |
| STORE_FAST_STORE_FAST | 480 | 7.0% |
| JUMP_FORWARD | 200 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,260 | 61.7% |
| LOAD_GLOBAL_MODULE | 1,680 | 24.3% |
| NOP | 480 | 7.0% |
| BUILD_LIST | 200 | 2.9% |
| LOAD_CONST | 200 | 2.9% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 420 | 50.0% |
| STORE_ATTR_INSTANCE_VALUE | 420 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 420 | 50.0% |
| RETURN_CONST | 420 | 50.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 14,180 | 57.2% |
| RETURN_CONST | 6,860 | 27.7% |
| POP_JUMP_IF_FALSE | 1,900 | 7.7% |
| RETURN_VALUE | 780 | 3.1% |
| CALL_METHOD_DESCRIPTOR_O | 760 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,880 | 43.9% |
| EXTENDED_ARG | 4,160 | 16.8% |
| ENTER_EXECUTOR | 3,360 | 13.5% |
| JUMP_FORWARD | 1,560 | 6.3% |
| RETURN_CONST | 1,140 | 4.6% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 420 | 50.0% |
| BINARY_SUBSCR_STR_INT | 420 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 840 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,140 | 86.2% |
| LOAD_ATTR_MODULE | 2,640 | 9.4% |
| STORE_FAST_LOAD_FAST | 960 | 3.4% |
| LOAD_DEREF | 160 | 0.6% |
| LOAD_ATTR | 120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,720 | 56.1% |
| LOAD_GLOBAL_MODULE | 5,460 | 19.5% |
| LOAD_CONST | 2,740 | 9.8% |
| LOAD_FAST_LOAD_FAST | 2,700 | 9.6% |
| CALL_BOUND_METHOD_EXACT_ARGS | 940 | 3.4% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 7,240 | 31.8% |
| LOAD_FAST | 4,080 | 17.9% |
| CALL_LEN | 2,500 | 11.0% |
| BINARY_SUBSCR_DICT | 1,440 | 6.3% |
| CALL | 1,160 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,340 | 23.5% |
| INTERPRETER_EXIT | 5,020 | 22.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,880 | 21.4% |
| LOAD_ATTR_METHOD_NO_DICT | 1,600 | 7.0% |
| TO_BOOL_BOOL | 860 | 3.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,280 | 95.5% |
| STORE_SUBSCR | 20 | 1.5% |
| LOAD_CONST | 20 | 1.5% |
| LOAD_FAST | 20 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 1,280 | 95.5% |
| STORE_SUBSCR | 20 | 1.5% |
| EXTENDED_ARG | 20 | 1.5% |
| RETURN_CONST | 20 | 1.5% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,680 | 67.7% |
| BINARY_OP | 420 | 16.9% |
| TO_BOOL | 200 | 8.1% |
| LOAD_ATTR | 180 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,620 | 65.3% |
| POP_JUMP_IF_TRUE | 640 | 25.8% |
| TO_BOOL | 200 | 8.1% |
| TO_BOOL_NONE | 20 | 0.8% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 320 | 100.0% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_LIST | 620 | 59.6% |
| TO_BOOL_INT | 420 | 40.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 620 | 59.6% |
| COPY | 420 | 40.4% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,140 | 75.2% |
| LOAD_FAST_LOAD_FAST | 660 | 6.1% |
| BINARY_OP | 480 | 4.4% |
| LOAD_FAST | 460 | 4.3% |
| RETURN_VALUE | 420 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 6,740 | 62.3% |
| STORE_FAST | 2,140 | 19.8% |
| BINARY_OP | 480 | 4.4% |
| TO_BOOL | 420 | 3.9% |
| LOAD_CONST | 420 | 3.9% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,720 | 25.2% |
| RESUME_CHECK | 1,320 | 19.4% |
| LOAD_CONST | 1,060 | 15.5% |
| POP_JUMP_IF_NOT_NONE | 820 | 12.0% |
| POP_JUMP_IF_FALSE | 620 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,360 | 78.6% |
| LOAD_FAST | 840 | 12.3% |
| SWAP | 320 | 4.7% |
| LOAD_GLOBAL_BUILTIN | 220 | 3.2% |
| LOAD_DEREF | 80 | 1.2% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 840 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 940 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 3,160 | 29.9% |
| LOAD_FAST_LOAD_FAST | 2,920 | 27.7% |
| LOAD_FAST | 2,060 | 19.5% |
| CALL | 860 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 840 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 3,180 | 30.1% |
| BINARY_SUBSCR_DICT | 1,680 | 15.9% |
| CALL_LIST_APPEND | 1,520 | 14.4% |
| RETURN_VALUE | 980 | 9.3% |
| LOAD_FAST | 860 | 8.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,920 | 39.8% |
| LOAD_GLOBAL_MODULE | 1,680 | 17.1% |
| ENTER_EXECUTOR | 1,460 | 14.8% |
| LOAD_FAST_LOAD_FAST | 920 | 9.3% |
| LOAD_CONST | 900 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,060 | 51.4% |
| RETURN_VALUE | 1,160 | 11.8% |
| RESUME_CHECK | 980 | 10.0% |
| BUILD_TUPLE | 860 | 8.7% |
| LOAD_GLOBAL_BUILTIN | 840 | 8.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 50.0% |
| LOAD_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 50.0% |
| RESUME_CHECK | 60 | 37.5% |
| RESUME | 20 | 12.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 860 | 71.7% |
| LOAD_FAST | 280 | 23.3% |
| COMPARE_OP | 60 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 940 | 78.3% |
| POP_JUMP_IF_TRUE | 200 | 16.7% |
| COMPARE_OP | 60 | 5.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,080 | 61.9% |
| LOAD_FAST_LOAD_FAST | 3,740 | 32.7% |
| LOAD_CONST | 620 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,260 | 72.2% |
| EXTENDED_ARG | 3,160 | 27.6% |
| RETURN_VALUE | 20 | 0.2% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 840 | 41.6% |
| LOAD_ATTR_INSTANCE_VALUE | 760 | 37.6% |
| UNARY_NOT | 420 | 20.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 840 | 41.6% |
| TO_BOOL_STR | 760 | 37.6% |
| TO_BOOL_BOOL | 420 | 20.8% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 9,000 | 46.3% |
| POP_TOP | 3,360 | 17.3% |
| POP_JUMP_IF_TRUE | 3,180 | 16.4% |
| CALL_LIST_APPEND | 1,500 | 7.7% |
| STORE_FAST | 1,300 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,080 | 36.4% |
| EXTENDED_ARG | 4,320 | 22.2% |
| BINARY_SUBSCR_GETITEM | 2,580 | 13.3% |
| CALL | 1,460 | 7.5% |
| FOR_ITER_LIST | 1,260 | 6.5% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 4,480 | 18.2% |
| ENTER_EXECUTOR | 4,320 | 17.6% |
| POP_TOP | 4,160 | 16.9% |
| STORE_FAST | 3,180 | 12.9% |
| CONTAINS_OP | 3,160 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,000 | 36.6% |
| POP_JUMP_IF_FALSE | 4,760 | 19.4% |
| JUMP_FORWARD | 4,160 | 16.9% |
| FOR_ITER | 3,480 | 14.2% |
| FOR_ITER_LIST | 3,000 | 12.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,480 | 77.0% |
| GET_ITER | 920 | 20.4% |
| FOR_ITER | 60 | 1.3% |
| JUMP_BACKWARD | 60 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,940 | 65.0% |
| RETURN_CONST | 520 | 11.5% |
| LOAD_FAST | 420 | 9.3% |
| LOAD_GLOBAL_MODULE | 420 | 9.3% |
| FOR_ITER | 60 | 1.3% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,080 | 97.1% |
| LOAD_FAST | 180 | 1.4% |
| LOAD_GLOBAL_BUILTIN | 180 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,940 | 71.9% |
| POP_JUMP_IF_TRUE | 3,500 | 28.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 680 | 35.1% |
| POP_TOP | 620 | 32.0% |
| CALL_LIST_APPEND | 480 | 24.7% |
| EXTENDED_ARG | 160 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 760 | 39.2% |
| FOR_ITER_TUPLE | 600 | 30.9% |
| EXTENDED_ARG | 280 | 14.4% |
| ENTER_EXECUTOR | 180 | 9.3% |
| FOR_ITER | 60 | 3.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 4,160 | 44.4% |
| POP_TOP | 1,560 | 16.7% |
| STORE_SUBSCR | 1,280 | 13.7% |
| STORE_FAST | 1,160 | 12.4% |
| POP_EXCEPT | 420 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 4,480 | 47.9% |
| LOAD_FAST | 1,860 | 19.9% |
| LOAD_GLOBAL_BUILTIN | 1,680 | 17.9% |
| LOAD_GLOBAL_MODULE | 940 | 10.0% |
| NOP | 200 | 2.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 320 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,160 | 87.5% |
| LOAD_GLOBAL_BUILTIN | 320 | 4.5% |
| LOAD_ATTR | 240 | 3.4% |
| LOAD_GLOBAL | 120 | 1.7% |
| LOAD_GLOBAL_MODULE | 120 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,580 | 79.3% |
| LOAD_FAST | 520 | 7.4% |
| LOAD_ATTR | 240 | 3.4% |
| LOAD_FAST_LOAD_FAST | 200 | 2.8% |
| TO_BOOL | 180 | 2.6% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,280 | 41.0% |
| STORE_FAST | 4,940 | 10.0% |
| BINARY_SUBSCR_STR_INT | 3,520 | 7.1% |
| CALL_LEN | 2,880 | 5.8% |
| PUSH_NULL | 2,740 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 8,060 | 16.3% |
| COMPARE_OP_STR | 5,920 | 12.0% |
| COMPARE_OP_INT | 5,620 | 11.4% |
| STORE_FAST | 5,460 | 11.0% |
| LOAD_FAST | 4,980 | 10.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 33.3% |
| BUILD_LIST | 80 | 33.3% |
| RESUME_CHECK | 60 | 25.0% |
| RESUME | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 66.7% |
| LIST_EXTEND | 80 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 50,700 | 24.1% |
| STORE_FAST | 29,180 | 13.9% |
| LOAD_GLOBAL_BUILTIN | 24,760 | 11.8% |
| PUSH_NULL | 15,720 | 7.5% |
| RESUME_CHECK | 11,700 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 31,500 | 15.0% |
| LOAD_ATTR_INSTANCE_VALUE | 27,380 | 13.0% |
| PUSH_NULL | 24,140 | 11.5% |
| LOAD_CONST | 20,280 | 9.7% |
| CALL_BUILTIN_O | 12,500 | 6.0% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 320 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 220 | 73.3% |
| POP_JUMP_IF_NONE | 80 | 26.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 220 | 73.3% |
| LOAD_FAST | 80 | 26.7% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 5,480 | 19.6% |
| STORE_FAST_STORE_FAST | 3,140 | 11.2% |
| PUSH_NULL | 2,700 | 9.7% |
| STORE_FAST | 2,180 | 7.8% |
| RESUME_CHECK | 2,160 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 4,680 | 16.8% |
| CALL_PY_EXACT_ARGS | 3,880 | 13.9% |
| CONTAINS_OP | 3,740 | 13.4% |
| LOAD_FAST | 3,380 | 12.1% |
| BUILD_TUPLE | 2,920 | 10.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 28.6% |
| LOAD_FAST | 100 | 14.3% |
| RESUME | 60 | 8.6% |
| RESUME_CHECK | 60 | 8.6% |
| RETURN_VALUE | 40 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 260 | 37.1% |
| LOAD_ATTR | 120 | 17.1% |
| LOAD_FAST | 100 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 100 | 14.3% |
| GET_ITER | 40 | 5.7% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 11,940 | 18.1% |
| IS_OP | 8,940 | 13.6% |
| CONTAINS_OP | 8,260 | 12.5% |
| ENTER_EXECUTOR | 7,080 | 10.8% |
| COMPARE_OP_STR | 6,860 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,700 | 77.0% |
| LOAD_GLOBAL_MODULE | 3,760 | 5.7% |
| LOAD_GLOBAL_BUILTIN | 1,920 | 2.9% |
| POP_TOP | 1,900 | 2.9% |
| NOP | 1,860 | 2.8% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,260 | 69.2% |
| LOAD_FAST | 560 | 30.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 840 | 46.2% |
| LOAD_FAST | 580 | 31.9% |
| LOAD_GLOBAL_BUILTIN | 320 | 17.6% |
| LOAD_FAST_CHECK | 80 | 4.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,360 | 86.2% |
| ENTER_EXECUTOR | 540 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,360 | 34.9% |
| BUILD_LIST | 820 | 21.0% |
| LOAD_GLOBAL_BUILTIN | 640 | 16.4% |
| EXTENDED_ARG | 420 | 10.8% |
| LOAD_GLOBAL_MODULE | 420 | 10.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 3,660 | 32.3% |
| IS_OP | 3,500 | 30.9% |
| TO_BOOL_BOOL | 1,940 | 17.1% |
| TO_BOOL_STR | 760 | 6.7% |
| TO_BOOL | 640 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,940 | 43.6% |
| ENTER_EXECUTOR | 3,180 | 28.1% |
| CALL_LEN | 760 | 6.7% |
| RETURN_CONST | 620 | 5.5% |
| LOAD_GLOBAL_MODULE | 620 | 5.5% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 3,380 | 30.3% |
| STORE_ATTR_INSTANCE_VALUE | 2,580 | 23.1% |
| POP_JUMP_IF_FALSE | 1,740 | 15.6% |
| POP_TOP | 1,140 | 10.2% |
| POP_JUMP_IF_TRUE | 620 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,860 | 61.5% |
| TO_BOOL_BOOL | 1,620 | 14.5% |
| STORE_FAST | 980 | 8.8% |
| EXIT_INIT_CHECK | 860 | 7.7% |
| INTERPRETER_EXIT | 840 | 7.5% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 6,740 | 10.9% |
| LOAD_ATTR | 5,580 | 9.1% |
| LOAD_CONST | 5,460 | 8.9% |
| BUILD_LIST | 5,360 | 8.7% |
| RETURN_VALUE | 5,340 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,180 | 47.4% |
| LOAD_GLOBAL_MODULE | 5,620 | 9.1% |
| LOAD_CONST | 4,940 | 8.0% |
| STORE_FAST | 3,760 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 3,740 | 6.1% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 960 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 7,380 | 85.2% |
| COPY | 840 | 9.7% |
| UNPACK_SEQUENCE_TUPLE | 420 | 4.8% |
| UNPACK_SEQUENCE | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840 | 44.3% |
| LOAD_FAST_LOAD_FAST | 3,140 | 36.3% |
| NOP | 480 | 5.5% |
| STORE_FAST | 420 | 4.8% |
| LOAD_GLOBAL_BUILTIN | 400 | 4.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 320 | 33.3% |
| LOAD_FAST_AND_CLEAR | 320 | 33.3% |
| FOR_ITER_RANGE | 320 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 320 | 33.3% |
| STORE_FAST | 320 | 33.3% |
| FOR_ITER_RANGE | 320 | 33.3% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20 | 33.3% |
| FOR_ITER | 20 | 33.3% |
| FOR_ITER_TUPLE | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 66.7% |
| STORE_FAST_STORE_FAST | 20 | 33.3% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 60.0% |
| CALL_FUNCTION_EX | 20 | 20.0% |
| COPY_FREE_VARS | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 60 | 60.0% |
| LOAD_DEREF | 20 | 20.0% |
| LOAD_FAST | 20 | 20.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,060 | 95.0% |
| LOAD_FAST_LOAD_FAST | 400 | 4.7% |
| BINARY_OP_MULTIPLY_INT | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,740 | 79.5% |
| LOAD_FAST | 1,740 | 20.5% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 20 | 100.0% |


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
| LOAD_FAST | 1,920 | 56.1% |
| CALL_LEN | 760 | 22.2% |
| LOAD_CONST | 740 | 21.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,160 | 33.9% |
| LOAD_FAST | 940 | 27.5% |
| RETURN_VALUE | 760 | 22.2% |
| STORE_FAST | 320 | 9.4% |
| LOAD_CONST | 240 | 7.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,680 | 89.4% |
| LOAD_FAST | 180 | 9.6% |
| LOAD_FAST_LOAD_FAST | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,440 | 76.6% |
| PUSH_EXC_INFO | 420 | 22.3% |
| LOAD_CONST | 20 | 1.1% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,580 | 63.9% |
| LOAD_CONST | 820 | 20.3% |
| LOAD_FAST | 620 | 15.3% |
| BINARY_SUBSCR | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,040 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,440 | 94.4% |
| LOAD_CONST | 420 | 5.3% |
| BINARY_SUBSCR_LIST_INT | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,240 | 97.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 200 | 2.7% |
| BINARY_SUBSCR_LIST_INT | 20 | 0.3% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,520 | 66.9% |
| LOAD_FAST | 1,560 | 29.7% |
| ENTER_EXECUTOR | 180 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,520 | 66.9% |
| STORE_FAST | 1,320 | 25.1% |
| PUSH_EXC_INFO | 420 | 8.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,740 | 98.9% |
| BINARY_SUBSCR | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,040 | 59.1% |
| GET_ITER | 600 | 34.1% |
| CALL_BUILTIN_O | 60 | 3.4% |
| LOAD_FAST | 20 | 1.1% |
| BINARY_OP_MULTIPLY_INT | 20 | 1.1% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 420 | 48.8% |
| LOAD_GLOBAL_MODULE | 420 | 48.8% |
| BINARY_SUBSCR | 20 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 860 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 3,180 | 58.7% |
| LOAD_CONST | 1,300 | 24.0% |
| PUSH_NULL | 940 | 17.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,420 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 840 | 45.2% |
| UNARY_NEGATIVE | 320 | 17.2% |
| LOAD_CONST | 320 | 17.2% |
| CALL_BUILTIN_FAST | 320 | 17.2% |
| LOAD_FAST | 40 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 620 | 33.3% |
| GET_ITER | 540 | 29.0% |
| RETURN_VALUE | 320 | 17.2% |
| LIST_APPEND | 320 | 17.2% |
| STORE_FAST | 60 | 3.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 320 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TUPLE_1 | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 420 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,500 | 72.1% |
| LOAD_GLOBAL_MODULE | 1,860 | 10.7% |
| LOAD_CONST | 1,360 | 7.8% |
| RETURN_VALUE | 620 | 3.6% |
| CALL_LEN | 620 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,180 | 81.8% |
| BUILD_TUPLE | 3,160 | 18.2% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 8,300 | 71.6% |
| LOAD_GLOBAL_MODULE | 2,100 | 18.1% |
| BUILD_TUPLE | 840 | 7.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 180 | 1.6% |
| LOAD_ATTR_SLOT | 180 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 10,340 | 89.1% |
| RETURN_VALUE | 840 | 7.2% |
| LOAD_FAST | 420 | 3.6% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,540 | 60.8% |
| LOAD_ATTR_INSTANCE_VALUE | 2,500 | 20.2% |
| LOAD_GLOBAL_MODULE | 840 | 6.8% |
| POP_JUMP_IF_TRUE | 760 | 6.1% |
| RETURN_VALUE | 680 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,880 | 23.2% |
| RETURN_VALUE | 2,500 | 20.2% |
| LOAD_FAST | 1,360 | 11.0% |
| STORE_FAST_LOAD_FAST | 960 | 7.7% |
| CALL_BUILTIN_CLASS | 840 | 6.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,380 | 55.4% |
| BUILD_TUPLE | 1,520 | 24.9% |
| CALL_LEN | 680 | 11.1% |
| LOAD_GLOBAL_MODULE | 420 | 6.9% |
| ENTER_EXECUTOR | 80 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,380 | 55.4% |
| ENTER_EXECUTOR | 1,500 | 24.6% |
| JUMP_BACKWARD | 480 | 7.9% |
| LOAD_FAST | 420 | 6.9% |
| LOAD_FAST_LOAD_FAST | 320 | 5.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 420 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680 | 66.7% |
| LOAD_GLOBAL_MODULE | 320 | 31.4% |
| CALL | 20 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 700 | 68.6% |
| LOAD_CONST | 320 | 31.4% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 420 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 71.1% |
| RETURN_VALUE | 220 | 28.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 760 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,880 | 32.8% |
| LOAD_FAST | 3,260 | 27.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,940 | 24.9% |
| UNARY_NOT | 620 | 5.2% |
| LOAD_CONST | 420 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,820 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 760 | 47.5% |
| LOAD_FAST | 480 | 30.0% |
| ENTER_EXECUTOR | 340 | 21.2% |
| CALL | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,600 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 420 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,100 | 92.1% |
| LOAD_FAST | 180 | 7.9% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,620 | 84.9% |
| LOAD_GLOBAL_MODULE | 840 | 12.7% |
| CALL_LEN | 160 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,620 | 100.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,920 | 82.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,300 | 18.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,860 | 95.0% |
| EXTENDED_ARG | 360 | 5.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 3,000 | 41.1% |
| GET_ITER | 2,240 | 30.7% |
| ENTER_EXECUTOR | 1,260 | 17.3% |
| JUMP_BACKWARD | 760 | 10.4% |
| FOR_ITER | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,720 | 37.3% |
| STORE_FAST | 1,440 | 19.7% |
| LOAD_FAST | 840 | 11.5% |
| LOAD_GLOBAL_BUILTIN | 840 | 11.5% |
| LOAD_FAST_LOAD_FAST | 580 | 7.9% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 940 | 42.0% |
| GET_ITER | 900 | 40.2% |
| SWAP | 320 | 14.3% |
| JUMP_BACKWARD | 60 | 2.7% |
| FOR_ITER | 20 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,000 | 44.6% |
| LOAD_FAST | 840 | 37.5% |
| SWAP | 320 | 14.3% |
| LOAD_GLOBAL | 40 | 1.8% |
| LOAD_GLOBAL_MODULE | 40 | 1.8% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 600 | 68.2% |
| GET_ITER | 120 | 13.6% |
| ENTER_EXECUTOR | 120 | 13.6% |
| FOR_ITER | 40 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 360 | 40.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 340 | 38.6% |
| LOAD_FAST_LOAD_FAST | 80 | 9.1% |
| LOAD_GLOBAL | 40 | 4.5% |
| LOAD_GLOBAL_MODULE | 40 | 4.5% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,380 | 86.5% |
| LOAD_FAST_LOAD_FAST | 2,160 | 6.8% |
| LOAD_ATTR_INSTANCE_VALUE | 2,100 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,900 | 31.3% |
| STORE_FAST | 3,720 | 11.8% |
| LOAD_ATTR_METHOD_NO_DICT | 3,380 | 10.7% |
| CALL_LEN | 2,500 | 7.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,100 | 6.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,220 | 48.9% |
| LOAD_ATTR_INSTANCE_VALUE | 3,380 | 31.6% |
| RETURN_VALUE | 1,600 | 15.0% |
| LOAD_GLOBAL_MODULE | 420 | 3.9% |
| LOAD_ATTR | 60 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000 | 56.2% |
| LOAD_GLOBAL_MODULE | 1,520 | 14.2% |
| LOAD_CONST | 1,440 | 13.5% |
| LOAD_FAST_LOAD_FAST | 940 | 8.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 420 | 3.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,940 | 93.6% |
| LOAD_GLOBAL_MODULE | 200 | 6.4% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,520 | 95.5% |
| LOAD_ATTR | 120 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,640 | 100.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 50.0% |
| LOAD_FAST_LOAD_FAST | 180 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 180 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 180 | 50.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 840 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 50.0% |
| LOAD_FAST_LOAD_FAST | 180 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 180 | 50.0% |
| CALL_ISINSTANCE | 180 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 14,100 | 33.2% |
| LOAD_FAST | 9,600 | 22.6% |
| STORE_FAST | 3,740 | 8.8% |
| LOAD_GLOBAL_BUILTIN | 2,100 | 4.9% |
| POP_JUMP_IF_FALSE | 1,920 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,760 | 58.3% |
| CALL_ISINSTANCE | 8,300 | 19.5% |
| LOAD_GLOBAL_BUILTIN | 2,100 | 4.9% |
| STORE_FAST | 2,080 | 4.9% |
| LOAD_GLOBAL_MODULE | 1,180 | 2.8% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,500 | 52.8% |
| STORE_FAST | 5,620 | 9.4% |
| PUSH_NULL | 5,460 | 9.2% |
| POP_JUMP_IF_FALSE | 3,760 | 6.3% |
| RESUME_CHECK | 2,140 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 12,080 | 20.2% |
| LOAD_FAST | 8,620 | 14.4% |
| BINARY_OP | 8,140 | 13.6% |
| CONTAINS_OP | 7,080 | 11.9% |
| LOAD_FAST_LOAD_FAST | 5,480 | 9.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 11,820 | 36.5% |
| CACHE | 6,280 | 19.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,420 | 16.7% |
| BINARY_SUBSCR_GETITEM | 4,040 | 12.5% |
| CALL_PY_WITH_DEFAULTS | 1,600 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 14,100 | 43.5% |
| LOAD_FAST | 11,700 | 36.1% |
| LOAD_FAST_LOAD_FAST | 2,160 | 6.7% |
| LOAD_GLOBAL_MODULE | 2,140 | 6.6% |
| BUILD_LIST | 1,320 | 4.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,780 | 57.1% |
| LOAD_FAST_LOAD_FAST | 4,680 | 39.4% |
| LOAD_ATTR_INSTANCE_VALUE | 420 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,940 | 24.7% |
| RETURN_CONST | 2,580 | 21.7% |
| LOAD_CONST | 2,520 | 21.2% |
| LOAD_FAST_LOAD_FAST | 2,160 | 18.2% |
| BUILD_MAP | 840 | 7.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 420 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 420 | 50.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,160 | 85.3% |
| LOAD_FAST | 200 | 14.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 600 | 44.1% |
| RETURN_CONST | 420 | 30.9% |
| EXTENDED_ARG | 340 | 25.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 10,340 | 69.7% |
| RETURN_CONST | 1,620 | 10.9% |
| LOAD_FAST | 960 | 6.5% |
| RETURN_VALUE | 860 | 5.8% |
| COPY | 420 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 11,940 | 80.5% |
| POP_JUMP_IF_TRUE | 1,940 | 13.1% |
| EXTENDED_ARG | 960 | 6.5% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 6,740 | 82.6% |
| LOAD_FAST | 1,420 | 17.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,080 | 50.0% |
| POP_JUMP_IF_TRUE | 3,660 | 44.9% |
| UNARY_NOT | 420 | 5.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,920 | 93.6% |
| LOAD_ATTR_INSTANCE_VALUE | 200 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,880 | 60.3% |
| UNARY_NOT | 620 | 19.9% |
| POP_JUMP_IF_TRUE | 620 | 19.9% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,980 | 99.0% |
| TO_BOOL | 20 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,000 | 100.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 760 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 420 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,880 | 43.9% |
| FOR_ITER | 2,940 | 26.4% |
| FOR_ITER_LIST | 2,720 | 24.5% |
| FOR_ITER_TUPLE | 340 | 3.1% |
| BINARY_SUBSCR_LIST_INT | 200 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 7,380 | 66.4% |
| STORE_FAST | 3,740 | 33.6% |


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
|     deferred | 10,320 | 45.3% |
|          hit | 11,980 | 52.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 4.0% |
| Failure | 480 | 96.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 260 | 54.2% |
| or | 100 | 20.8% |
| and different types | 60 | 12.5% |
| multiply different types | 40 | 8.3% |
| add other | 20 | 4.2% |


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
|     deferred | 940 | 4.3% |
|          hit | 19,960 | 91.3% |
|         miss | 860 | 3.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 60.0% |
| Failure | 40 | 40.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 20 | 50.0% |
| buffer slice | 20 | 50.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 9,180 | 10.2% |
|          hit | 80,160 | 88.8% |
|         miss | 320 | 0.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 36.4% |
| Failure | 420 | 63.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 100 | 23.8% |
| meth descr method fastcall keywords | 80 | 19.0% |
| cfunc noargs | 60 | 14.3% |
| wrong number arguments | 40 | 9.5% |
| cfunc varargs keywords | 40 | 9.5% |
| meth descr varargs | 40 | 9.5% |
| str | 40 | 9.5% |
| class mutable | 20 | 4.8% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,140 | 7.6% |
|          hit | 13,420 | 89.2% |
|         miss | 420 | 2.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 60 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 40 | 66.7% |
| tuple | 20 | 33.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,360 | 29.2% |
|          hit | 10,420 | 69.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 62.5% |
| Failure | 60 | 37.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict keys | 20 | 33.3% |
| dict items | 20 | 33.3% |
| seq iter | 20 | 33.3% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,620 | 11.7% |
|          hit | 49,660 | 87.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 42.9% |
| Failure | 240 | 57.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 160 | 66.7% |
| metaclass attribute | 60 | 25.0% |
| builtin class method | 20 | 8.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 340 | 0.3% |
|          hit | 102,140 | 99.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 360 | 100.0% |
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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 11,880 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,320 | 37.3% |
|          hit | 2,200 | 62.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytearray int | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,260 | 7.2% |
|          hit | 28,800 | 91.8% |
|         miss | 80 | 0.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 9.1% |
| Failure | 200 | 90.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mapping | 80 | 40.0% |
| tuple | 80 | 40.0% |
| dict | 20 | 10.0% |
| number | 20 | 10.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.2% |
|          hit | 11,540 | 99.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 572,560 | 53.7% |
| Not specialized | 122,240 | 11.5% |
| Specialized hits | 369,120 | 34.6% |
| Specialized misses | 1,680 | 0.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 10,320 | 28.3% |
| CALL | 9,180 | 25.2% |
| LOAD_ATTR | 6,620 | 18.1% |
| FOR_ITER | 4,360 | 11.9% |
| TO_BOOL | 2,260 | 6.2% |
| STORE_SUBSCR | 1,320 | 3.6% |
| COMPARE_OP | 1,140 | 3.1% |
| BINARY_SUBSCR | 940 | 2.6% |
| LOAD_GLOBAL | 340 | 0.9% |
| UNPACK_SEQUENCE | 20 | 0.1% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 440 | 26.2% |
| BINARY_SUBSCR_STR_INT | 420 | 25.0% |
| COMPARE_OP_STR | 420 | 25.0% |
| CALL_BUILTIN_FAST | 320 | 19.0% |
| TO_BOOL_LIST | 80 | 4.8% |
| CACHE | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 6,280 | 19.6% |
| Calls to Python functions inlined | 25,780 | 80.4% |
| Calls via PyEval_EvalFrame (total) | 6,280 | 19.6% |
| Calls via PyEval_EvalFrame (vector) | 6,280 | 19.6% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 6,280 | 19.6% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 5,280 | 16.5% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.5% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 1,680 | 5.2% |
| Frames pushed | 33,580 | 104.7% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 30,160 | 0.5% |
| Frees to freelist | 30,560 |  |
| Allocations | 6,503,080 | 99.5% |
| Allocations to 512 bytes | 6,481,420 | 99.2% |
| Allocations to 4 kbytes | 17,980 | 0.3% |
| Allocations over 4 kbytes | 3,680 | 0.1% |
| Frees | 7,876,163 |  |
| New values | 820 |  |
| Interpreter increfs | 503,680 | 1.7% |
| Interpreter decrefs | 538,660 | 1.5% |
| Increfs | 28,826,938 | 98.3% |
| Decrefs | 35,315,721 | 98.5% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 7,272 |  |
| Method cache misses | 108 |  |
| Method cache collisions | 126 |  |
| Method cache dunder hits | 19,956 |  |
| Method cache dunder misses | 44 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 0 | 0 | 0 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 180 |  |
| Traces created | 180 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 19,440 |  |
| Uops executed | 582,540 | 29.97 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 40 | 22.2% |
| <= 64 | 60 | 33.3% |
| <= 128 | 80 | 44.4% |


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
| <= 16 | 60 | 33.3% |
| <= 32 | 80 | 44.4% |
| <= 64 | 40 | 22.2% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 2,640 | 13.6% |
| <= 2 | 2,600 | 13.4% |
| <= 4 | 620 | 3.2% |
| <= 8 | 1,380 | 7.1% |
| <= 16 | 4,480 | 23.0% |
| <= 32 | 3,740 | 19.2% |
| <= 64 | 300 | 1.5% |
| <= 128 | 2,720 | 14.0% |
| <= 256 | 960 | 4.9% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 97,120 | 16.7% | 16.7% |  |
| _SET_IP | 60,100 | 10.3% | 27.0% |  |
| _CHECK_VALIDITY | 48,020 | 8.2% | 35.2% |  |
| STORE_FAST | 29,940 | 5.1% | 40.4% |  |
| _GUARD_TYPE_VERSION | 26,320 | 4.5% | 44.9% |  |
| LOAD_CONST | 20,120 | 3.5% | 48.3% |  |
| _GUARD_IS_FALSE_POP | 17,420 | 3.0% | 51.3% | 10.2% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 14,460 | 2.5% | 53.8% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 14,460 | 2.5% | 56.3% |  |
| _GUARD_GLOBALS_VERSION | 13,520 | 2.3% | 58.6% |  |
| _LOAD_GLOBAL_MODULE | 13,180 | 2.3% | 60.9% |  |
| _ITER_CHECK_LIST | 9,560 | 1.6% | 62.5% | 27.6% |
| PUSH_NULL | 8,860 | 1.5% | 64.0% |  |
| IS_OP | 8,640 | 1.5% | 65.5% |  |
| _CHECK_PEP_523 | 8,140 | 1.4% | 66.9% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 8,140 | 1.4% | 68.3% |  |
| _CHECK_STACK_SPACE | 8,140 | 1.4% | 69.7% |  |
| _INIT_CALL_PY_EXACT_ARGS | 8,140 | 1.4% | 71.1% |  |
| _PUSH_FRAME | 8,140 | 1.4% | 72.5% |  |
| _SAVE_RETURN_OFFSET | 8,140 | 1.4% | 73.9% |  |
| RESUME_CHECK | 7,720 | 1.3% | 75.2% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 6,920 | 1.2% | 76.4% | 38.4% |
| _POP_FRAME | 6,720 | 1.2% | 77.6% |  |
| _GUARD_DORV_VALUES | 6,720 | 1.2% | 78.7% |  |
| _STORE_ATTR_INSTANCE_VALUE | 6,720 | 1.2% | 79.9% |  |
| _GUARD_IS_TRUE_POP | 6,560 | 1.1% | 81.0% | 85.1% |
| CONTAINS_OP | 6,280 | 1.1% | 82.1% |  |
| POP_TOP | 6,140 | 1.1% | 83.1% |  |
| _GUARD_BOTH_INT | 6,120 | 1.1% | 84.2% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 5,740 | 1.0% | 85.2% | 16.4% |
| _ITER_CHECK_RANGE | 5,740 | 1.0% | 86.2% |  |
| COMPARE_OP_STR | 5,580 | 1.0% | 87.1% |  |
| _EXIT_TRACE | 4,880 | 0.8% | 88.0% |  |
| _ITER_NEXT_RANGE | 4,800 | 0.8% | 88.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 4,300 | 0.7% | 89.5% |  |
| _ITER_NEXT_LIST | 4,260 | 0.7% | 90.3% |  |
| BINARY_SUBSCR_STR_INT | 4,180 | 0.7% | 91.0% | 4.3% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 4,180 | 0.7% | 91.7% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 4,180 | 0.7% | 92.4% |  |
| _GUARD_IS_NOT_NONE_POP | 4,140 | 0.7% | 93.1% | 10.1% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 3,760 | 0.6% | 93.8% |  |
| _GUARD_KEYS_VERSION | 3,760 | 0.6% | 94.4% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 3,760 | 0.6% | 95.1% |  |
| _BINARY_OP_ADD_INT | 3,600 | 0.6% | 95.7% |  |
| TO_BOOL_INT | 2,620 | 0.4% | 96.1% |  |
| _JUMP_TO_TOP | 2,540 | 0.4% | 96.6% |  |
| _BINARY_OP_SUBTRACT_INT | 2,520 | 0.4% | 97.0% |  |
| BINARY_SLICE | 2,240 | 0.4% | 97.4% |  |
| LIST_APPEND | 2,240 | 0.4% | 97.8% |  |
| CALL_BUILTIN_CLASS | 2,240 | 0.4% | 98.1% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 1,380 | 0.2% | 98.4% |  |
| CALL_BUILTIN_O | 1,000 | 0.2% | 98.6% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 960 | 0.2% | 98.7% | 12.5% |
| _ITER_CHECK_TUPLE | 960 | 0.2% | 98.9% |  |
| _CHECK_ATTR_MODULE | 840 | 0.1% | 99.0% |  |
| _LOAD_ATTR_MODULE | 840 | 0.1% | 99.2% |  |
| _ITER_NEXT_TUPLE | 840 | 0.1% | 99.3% |  |
| BUILD_TUPLE | 720 | 0.1% | 99.4% |  |
| TO_BOOL_LIST | 640 | 0.1% | 99.5% |  |
| _FOR_ITER_TIER_TWO | 400 | 0.1% | 99.6% | 30.0% |
| CALL_LEN | 400 | 0.1% | 99.7% |  |
| _GUARD_BUILTINS_VERSION | 340 | 0.1% | 99.7% |  |
| _LOAD_GLOBAL_BUILTINS | 340 | 0.1% | 99.8% |  |
| UNARY_NOT | 200 | 0.0% | 99.8% |  |
| COPY | 200 | 0.0% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 200 | 0.0% | 99.9% |  |
| TO_BOOL_BOOL | 200 | 0.0% | 99.9% |  |
| _TO_BOOL | 140 | 0.0% | 100.0% |  |
| _GUARD_IS_NONE_POP | 120 | 0.0% | 100.0% | 100.0% |
| COMPARE_OP_INT | 80 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 20 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| BINARY_SUBSCR_GETITEM | 40 |
| CALL | 20 |
| CALL_LIST_APPEND | 20 |
| CALL_PY_WITH_DEFAULTS | 20 |


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
Stats gathered on: 2023-11-19
