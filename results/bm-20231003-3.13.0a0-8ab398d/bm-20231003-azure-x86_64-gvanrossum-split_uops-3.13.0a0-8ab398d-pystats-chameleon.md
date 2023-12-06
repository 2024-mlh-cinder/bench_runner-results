
# Pystats results

- benchmark: chameleon
- fork: gvanrossum
- ref: split-uops
- commit hash: 8ab398d
- commit date: 2023-10-03T16:05:03-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 274,630,560 | 21.8% | 21.8% |  |
| LOAD_CONST | 145,949,820 | 11.6% | 33.3% |  |
| STORE_FAST | 126,274,860 | 10.0% | 43.3% |  |
| PUSH_NULL | 75,372,720 | 6.0% | 49.3% |  |
| IS_OP | 68,646,720 | 5.4% | 54.8% |  |
| LOAD_GLOBAL_MODULE | 66,745,060 | 5.3% | 60.1% |  |
| LOAD_GLOBAL_BUILTIN | 65,289,660 | 5.2% | 65.2% |  |
| POP_JUMP_IF_FALSE | 54,247,740 | 4.3% | 69.5% |  |
| POP_TOP | 39,368,700 | 3.1% | 72.6% |  |
| CALL_BUILTIN_O | 39,361,920 | 3.1% | 75.8% |  |
| LOAD_FAST_LOAD_FAST | 27,852,480 | 2.2% | 78.0% |  |
| RESUME_CHECK | 26,414,460 | 2.1% | 80.1% |  |
| RETURN_VALUE | 25,930,620 | 2.1% | 82.1% |  |
| POP_JUMP_IF_TRUE | 19,680,960 | 1.6% | 83.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 15,663,180 | 1.2% | 84.9% | 100.0% |
| LOAD_ATTR_CLASS | 15,365,760 | 1.2% | 86.1% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 15,361,920 | 1.2% | 87.4% |  |
| POP_JUMP_IF_NONE | 14,883,840 | 1.2% | 88.5% |  |
| STORE_SUBSCR | 11,044,680 | 0.9% | 89.4% |  |
| CALL_PY_EXACT_ARGS | 10,081,920 | 0.8% | 90.2% |  |
| COPY_FREE_VARS | 9,601,020 | 0.8% | 91.0% |  |
| TO_BOOL_BOOL | 9,600,960 | 0.8% | 91.7% |  |
| POP_JUMP_IF_NOT_NONE | 9,600,960 | 0.8% | 92.5% |  |
| CALL_TYPE_1 | 9,600,000 | 0.8% | 93.3% |  |
| CALL_STR_1 | 9,600,000 | 0.8% | 94.0% |  |
| CALL | 6,246,760 | 0.5% | 94.5% |  |
| CALL_BUILTIN_FAST | 6,246,720 | 0.5% | 95.0% |  |
| JUMP_FORWARD | 5,761,920 | 0.5% | 95.5% |  |
| FOR_ITER_LIST | 5,760,960 | 0.5% | 95.9% |  |
| NOP | 5,282,940 | 0.4% | 96.3% |  |
| JUMP_BACKWARD | 5,280,960 | 0.4% | 96.8% |  |
| DELETE_SUBSCR | 5,280,960 | 0.4% | 97.2% |  |
| COMPARE_OP_INT | 5,280,060 | 0.4% | 97.6% |  |
| BINARY_OP_SUBTRACT_INT | 5,280,000 | 0.4% | 98.0% |  |
| BINARY_OP | 4,801,200 | 0.4% | 98.4% |  |
| LOAD_DEREF | 4,800,120 | 0.4% | 98.8% |  |
| BINARY_OP_ADD_UNICODE | 4,800,000 | 0.4% | 99.2% |  |
| BINARY_OP_ADD_INT | 4,800,000 | 0.4% | 99.5% |  |
| INTERPRETER_EXIT | 965,760 | 0.1% | 99.6% |  |
| STORE_ATTR_SLOT | 963,840 | 0.1% | 99.7% |  |
| EXTENDED_ARG | 960,960 | 0.1% | 99.8% |  |
| RETURN_CONST | 483,840 | 0.0% | 99.8% |  |
| BUILD_TUPLE | 482,880 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 481,980 | 0.0% | 99.9% |  |
| GET_ITER | 481,020 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 480,960 | 0.0% | 100.0% |  |
| CALL_LEN | 480,960 | 0.0% | 100.0% |  |
| LOAD_ATTR | 10,060 | 0.0% | 100.0% |  |
| BUILD_MAP | 3,840 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 3,840 | 0.0% | 100.0% |  |
| STORE_DEREF | 2,880 | 0.0% | 100.0% |  |
| MAKE_CELL | 2,880 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 1,980 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 1,920 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 1,920 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,920 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,920 | 0.0% | 100.0% |  |
| DICT_MERGE | 1,920 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 1,020 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 960 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 960 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 960 | 0.0% | 100.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 960 | 0.0% | 100.0% |  |
| CONTAINS_OP | 960 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 960 | 0.0% | 100.0% |  |
| CALL_KW | 960 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 960 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 98,902,320 | 7.8% | 7.8% |
| LOAD_FAST PUSH_NULL | 69,609,720 | 5.5% | 13.4% |
| PUSH_NULL LOAD_CONST | 55,691,520 | 4.4% | 17.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 44,646,720 | 3.5% | 21.3% |
| IS_OP POP_JUMP_IF_FALSE | 44,646,720 | 3.5% | 24.8% |
| CALL_BUILTIN_O POP_TOP | 39,360,960 | 3.1% | 28.0% |
| LOAD_FAST LOAD_CONST | 36,006,780 | 2.9% | 30.8% |
| LOAD_CONST CALL_BUILTIN_O | 29,760,960 | 2.4% | 33.2% |
| LOAD_GLOBAL_BUILTIN IS_OP | 28,800,000 | 2.3% | 35.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 28,800,000 | 2.3% | 37.7% |
| LOAD_FAST RETURN_VALUE | 24,965,820 | 2.0% | 39.7% |
| LOAD_CONST LOAD_CONST | 24,000,960 | 1.9% | 41.6% |
| LOAD_GLOBAL_MODULE IS_OP | 20,646,720 | 1.6% | 43.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 20,646,720 | 1.6% | 44.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 20,642,940 | 1.6% | 46.5% |
| STORE_FAST LOAD_CONST | 20,162,880 | 1.6% | 48.1% |
| POP_TOP LOAD_FAST | 19,684,800 | 1.6% | 49.7% |
| LOAD_GLOBAL_MODULE STORE_FAST | 19,683,840 | 1.6% | 51.3% |
| PUSH_NULL LOAD_FAST | 19,200,060 | 1.5% | 52.8% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 15,367,680 | 1.2% | 54.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 15,365,760 | 1.2% | 55.2% |
| LOAD_GLOBAL_MODULE CALL_METHOD_DESCRIPTOR_FAST | 15,365,760 | 1.2% | 56.4% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR_CLASS | 15,365,760 | 1.2% | 57.7% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 15,365,760 | 1.2% | 58.9% |
| LOAD_ATTR_CLASS LOAD_FAST_LOAD_FAST | 15,365,760 | 1.2% | 60.1% |
| LOAD_CONST CALL_BOUND_METHOD_EXACT_ARGS | 15,361,920 | 1.2% | 61.3% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 15,361,920 | 1.2% | 62.5% |
| LOAD_FAST POP_JUMP_IF_NONE | 14,883,840 | 1.2% | 63.7% |
| LOAD_FAST LOAD_FAST | 14,882,880 | 1.2% | 64.9% |
| LOAD_CONST STORE_FAST | 14,882,880 | 1.2% | 66.1% |
| POP_TOP LOAD_GLOBAL_MODULE | 14,881,920 | 1.2% | 67.2% |
| RETURN_VALUE STORE_FAST | 14,401,920 | 1.1% | 68.4% |
| IS_OP POP_JUMP_IF_TRUE | 14,400,000 | 1.1% | 69.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 14,399,040 | 1.1% | 70.7% |
| STORE_SUBSCR LOAD_FAST | 10,560,960 | 0.8% | 71.5% |
| LOAD_CONST STORE_SUBSCR | 10,560,960 | 0.8% | 72.3% |
| RESUME_CHECK LOAD_FAST | 10,085,760 | 0.8% | 73.1% |
| LOAD_CONST LOAD_GLOBAL_MODULE | 10,081,920 | 0.8% | 73.9% |
| COPY_FREE_VARS RESUME_CHECK | 9,601,020 | 0.8% | 74.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 9,600,960 | 0.8% | 75.5% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 9,600,960 | 0.8% | 76.2% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 9,600,040 | 0.8% | 77.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 9,600,000 | 0.8% | 77.7% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 9,600,000 | 0.8% | 78.5% |
| LOAD_FAST_LOAD_FAST IS_OP | 9,600,000 | 0.8% | 79.3% |
| LOAD_FAST TO_BOOL_BOOL | 9,600,000 | 0.8% | 80.0% |
| LOAD_FAST STORE_FAST | 9,600,000 | 0.8% | 80.8% |
| LOAD_FAST CALL_TYPE_1 | 9,600,000 | 0.8% | 81.5% |
| IS_OP STORE_FAST | 9,600,000 | 0.8% | 82.3% |
| CALL_TYPE_1 STORE_FAST | 9,600,000 | 0.8% | 83.1% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 9,600,000 | 0.8% | 83.8% |
| LOAD_CONST LOAD_FAST | 5,765,760 | 0.5% | 84.3% |
| STORE_FAST LOAD_GLOBAL_MODULE | 5,763,840 | 0.5% | 84.7% |
| CALL_BUILTIN_FAST STORE_FAST | 5,761,920 | 0.5% | 85.2% |
| LOAD_FAST CALL | 5,281,940 | 0.4% | 85.6% |
| RETURN_VALUE LOAD_CONST | 5,280,960 | 0.4% | 86.0% |
| LOAD_GLOBAL_MODULE CALL_BUILTIN_FAST | 5,280,960 | 0.4% | 86.5% |
| LOAD_CONST DELETE_SUBSCR | 5,280,960 | 0.4% | 86.9% |
| JUMP_FORWARD LOAD_FAST | 5,280,960 | 0.4% | 87.3% |
| DELETE_SUBSCR JUMP_FORWARD | 5,280,960 | 0.4% | 87.7% |
| LOAD_CONST COMPARE_OP_INT | 5,280,040 | 0.4% | 88.1% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 5,280,000 | 0.4% | 88.5% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 5,280,000 | 0.4% | 89.0% |
| FOR_ITER_LIST STORE_FAST | 5,280,000 | 0.4% | 89.4% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 5,280,000 | 0.4% | 89.8% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 5,280,000 | 0.4% | 90.2% |
| LOAD_FAST CALL_BUILTIN_O | 4,800,960 | 0.4% | 90.6% |
| NOP LOAD_DEREF | 4,800,060 | 0.4% | 91.0% |
| LOAD_DEREF PUSH_NULL | 4,800,060 | 0.4% | 91.4% |
| LOAD_FAST BINARY_OP | 4,800,020 | 0.4% | 91.7% |
| RETURN_VALUE CALL_STR_1 | 4,800,000 | 0.4% | 92.1% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 4,800,000 | 0.4% | 92.5% |
| POP_JUMP_IF_NONE NOP | 4,800,000 | 0.4% | 92.9% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 4,800,000 | 0.4% | 93.3% |
| LOAD_FAST IS_OP | 4,800,000 | 0.4% | 93.6% |
| LOAD_FAST CALL_STR_1 | 4,800,000 | 0.4% | 94.0% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 4,800,000 | 0.4% | 94.4% |
| LOAD_CONST IS_OP | 4,800,000 | 0.4% | 94.8% |
| LOAD_CONST BINARY_OP_ADD_INT | 4,800,000 | 0.4% | 95.2% |
| JUMP_BACKWARD FOR_ITER_LIST | 4,800,000 | 0.4% | 95.5% |
| CALL_STR_1 STORE_FAST | 4,800,000 | 0.4% | 95.9% |
| CALL_STR_1 BINARY_OP_ADD_UNICODE | 4,800,000 | 0.4% | 96.3% |
| CALL LOAD_CONST | 4,800,000 | 0.4% | 96.7% |
| BINARY_OP_ADD_UNICODE STORE_FAST | 4,800,000 | 0.4% | 97.1% |
| BINARY_OP_ADD_INT STORE_FAST | 4,800,000 | 0.4% | 97.5% |
| BINARY_OP CALL_BUILTIN_O | 4,800,000 | 0.4% | 97.8% |
| POP_TOP JUMP_BACKWARD | 4,320,960 | 0.3% | 98.2% |
| CACHE RESUME_CHECK | 964,800 | 0.1% | 98.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 961,920 | 0.1% | 98.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 961,920 | 0.1% | 98.4% |
| RETURN_VALUE PUSH_NULL | 960,960 | 0.1% | 98.5% |
| RETURN_VALUE INTERPRETER_EXIT | 483,840 | 0.0% | 98.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 483,840 | 0.0% | 98.6% |
| LOAD_FAST CALL_BUILTIN_FAST | 482,880 | 0.0% | 98.6% |
| STORE_ATTR_SLOT RETURN_CONST | 481,920 | 0.0% | 98.6% |
| RETURN_CONST INTERPRETER_EXIT | 481,920 | 0.0% | 98.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 481,920 | 0.0% | 98.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 481,920 | 0.0% | 98.7% |
| PUSH_NULL CALL | 481,140 | 0.0% | 98.8% |
| LOAD_FAST GET_ITER | 481,020 | 0.0% | 98.8% |


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
| RESUME_CHECK | 964,800 | 99.9% |
| COPY_FREE_VARS | 960 | 0.1% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,280,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 5,280,960 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 481,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 480,000 | 99.8% |
| EXTENDED_ARG | 960 | 0.2% |
| FOR_ITER_RANGE | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 483,840 | 50.1% |
| RETURN_CONST | 481,920 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,920 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 4,800,000 | 90.9% |
| RESUME_CHECK | 480,960 | 9.1% |
| STORE_FAST | 1,920 | 0.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 4,800,060 | 90.9% |
| LOAD_GLOBAL_BUILTIN | 480,000 | 9.1% |
| LOAD_FAST | 1,920 | 0.0% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 39,360,960 | 100.0% |
| CALL_BUILTIN_FAST | 4,800 | 0.0% |
| RETURN_CONST | 1,920 | 0.0% |
| CALL | 1,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,684,800 | 50.0% |
| LOAD_GLOBAL_MODULE | 14,881,920 | 37.8% |
| JUMP_BACKWARD | 4,320,960 | 11.0% |
| EXTENDED_ARG | 479,040 | 1.2% |
| RETURN_CONST | 960 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 69,609,720 | 92.4% |
| LOAD_DEREF | 4,800,060 | 6.4% |
| RETURN_VALUE | 960,960 | 1.3% |
| LOAD_ATTR | 980 | 0.0% |
| LOAD_SUPER_ATTR_ATTR | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 55,691,520 | 73.9% |
| LOAD_FAST | 19,200,060 | 25.5% |
| CALL | 481,140 | 0.6% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,965,820 | 96.3% |
| BUILD_TUPLE | 480,960 | 1.9% |
| CALL_BUILTIN_FAST | 480,000 | 1.9% |
| CALL_FUNCTION_EX | 1,920 | 0.0% |
| RETURN_VALUE | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,401,920 | 55.5% |
| LOAD_CONST | 5,280,960 | 20.4% |
| CALL_STR_1 | 4,800,000 | 18.5% |
| PUSH_NULL | 960,960 | 3.7% |
| INTERPRETER_EXIT | 483,840 | 1.9% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,560,960 | 95.6% |
| LOAD_FAST_LOAD_FAST | 480,960 | 4.4% |
| STORE_SUBSCR | 2,760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,560,960 | 95.6% |
| LOAD_FAST_LOAD_FAST | 480,960 | 4.4% |
| STORE_SUBSCR | 2,760 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800,020 | 100.0% |
| BINARY_OP | 1,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 4,800,000 | 100.0% |
| BINARY_OP | 1,180 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920 | 50.0% |
| STORE_FAST | 960 | 25.0% |
| LOAD_GLOBAL_MODULE | 960 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 50.0% |
| STORE_FAST | 960 | 25.0% |
| CALL | 960 | 25.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 480,960 | 99.6% |
| LOAD_FAST | 1,920 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 480,960 | 99.6% |
| LOAD_CONST | 1,920 | 0.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,281,940 | 84.6% |
| PUSH_NULL | 481,140 | 7.7% |
| LOAD_FAST_LOAD_FAST | 480,960 | 7.7% |
| CALL | 1,760 | 0.0% |
| BUILD_MAP | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,800,000 | 76.8% |
| STORE_FAST | 481,020 | 7.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 480,960 | 7.7% |
| LOAD_FAST_LOAD_FAST | 480,960 | 7.7% |
| CALL | 1,760 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 1,920 | 97.0% |
| LOAD_FAST | 60 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,920 | 97.0% |
| COPY_FREE_VARS | 60 | 3.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 960 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 20 | 100.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 960 | 100.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 9,600,000 | 100.0% |
| CACHE | 960 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,601,020 | 100.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,920 | 100.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 480,000 | 50.0% |
| POP_TOP | 479,040 | 49.9% |
| POP_JUMP_IF_TRUE | 960 | 0.1% |
| GET_ITER | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 480,960 | 50.0% |
| JUMP_BACKWARD | 480,000 | 50.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 28,800,000 | 42.0% |
| LOAD_GLOBAL_MODULE | 20,646,720 | 30.1% |
| LOAD_FAST_LOAD_FAST | 9,600,000 | 14.0% |
| LOAD_FAST | 4,800,000 | 7.0% |
| LOAD_CONST | 4,800,000 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,646,720 | 65.0% |
| POP_JUMP_IF_TRUE | 14,400,000 | 21.0% |
| STORE_FAST | 9,600,000 | 14.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,320,960 | 81.8% |
| POP_JUMP_IF_TRUE | 480,000 | 9.1% |
| EXTENDED_ARG | 480,000 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 4,800,000 | 90.9% |
| EXTENDED_ARG | 480,000 | 9.1% |
| FOR_ITER_RANGE | 960 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 5,280,960 | 91.7% |
| CALL_BUILTIN_CLASS | 480,960 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,280,960 | 91.7% |
| STORE_FAST | 480,960 | 8.3% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,600 | 95.4% |
| LOAD_ATTR | 400 | 4.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.4% |
| LOAD_GLOBAL | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,800 | 47.7% |
| LOAD_FAST | 1,920 | 19.1% |
| PUSH_NULL | 980 | 9.7% |
| TO_BOOL_BOOL | 960 | 9.5% |
| CALL_BUILTIN_CLASS | 960 | 9.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 55,691,520 | 38.2% |
| LOAD_FAST | 36,006,780 | 24.7% |
| LOAD_CONST | 24,000,960 | 16.4% |
| STORE_FAST | 20,162,880 | 13.8% |
| RETURN_VALUE | 5,280,960 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 29,760,960 | 20.4% |
| LOAD_CONST | 24,000,960 | 16.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 15,361,920 | 10.5% |
| STORE_FAST | 14,882,880 | 10.2% |
| STORE_SUBSCR | 10,560,960 | 7.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 4,800,060 | 100.0% |
| STORE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 4,800,060 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 98,902,320 | 36.0% |
| POP_JUMP_IF_FALSE | 44,646,720 | 16.3% |
| LOAD_GLOBAL_BUILTIN | 20,642,940 | 7.5% |
| POP_TOP | 19,684,800 | 7.2% |
| PUSH_NULL | 19,200,060 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 69,609,720 | 25.3% |
| LOAD_CONST | 36,006,780 | 13.1% |
| LOAD_GLOBAL_BUILTIN | 28,800,000 | 10.5% |
| RETURN_VALUE | 24,965,820 | 9.1% |
| LOAD_GLOBAL_MODULE | 20,646,720 | 7.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 15,365,760 | 55.2% |
| POP_JUMP_IF_NOT_NONE | 9,600,000 | 34.5% |
| LOAD_GLOBAL_MODULE | 481,920 | 1.7% |
| STORE_SUBSCR | 480,960 | 1.7% |
| STORE_ATTR_SLOT | 480,960 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 15,365,760 | 55.2% |
| IS_OP | 9,600,000 | 34.5% |
| STORE_ATTR_SLOT | 961,920 | 3.5% |
| STORE_SUBSCR | 480,960 | 1.7% |
| CALL | 480,960 | 1.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 50.0% |
| RESUME_CHECK | 20 | 25.0% |
| POP_JUMP_IF_FALSE | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 20 | 25.0% |
| LOAD_ATTR | 20 | 25.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 1,920 | 66.7% |
| CALL_PY_WITH_DEFAULTS | 960 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 1,920 | 66.7% |
| RESUME_CHECK | 960 | 33.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 44,646,720 | 82.3% |
| TO_BOOL_BOOL | 9,600,000 | 17.7% |
| CONTAINS_OP | 960 | 0.0% |
| COMPARE_OP_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,646,720 | 82.3% |
| LOAD_GLOBAL_BUILTIN | 9,600,040 | 17.7% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,883,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,600,960 | 64.5% |
| NOP | 4,800,000 | 32.2% |
| LOAD_GLOBAL_BUILTIN | 480,960 | 3.2% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |
| LOAD_CONST | 960 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,600,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,600,000 | 100.0% |
| LOAD_FAST | 960 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 14,400,000 | 73.2% |
| COMPARE_OP_INT | 5,280,000 | 26.8% |
| TO_BOOL_BOOL | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,399,040 | 73.2% |
| LOAD_GLOBAL_BUILTIN | 4,800,000 | 24.4% |
| JUMP_BACKWARD | 480,000 | 2.4% |
| RETURN_CONST | 960 | 0.0% |
| EXTENDED_ARG | 960 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 481,920 | 99.6% |
| POP_TOP | 960 | 0.2% |
| POP_JUMP_IF_TRUE | 960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 481,920 | 99.6% |
| POP_TOP | 1,920 | 0.4% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,920 | 66.7% |
| LOAD_GLOBAL_MODULE | 960 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,880 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 19,683,840 | 15.6% |
| CALL_METHOD_DESCRIPTOR_FAST | 15,367,680 | 12.2% |
| LOAD_CONST | 14,882,880 | 11.8% |
| RETURN_VALUE | 14,401,920 | 11.4% |
| LOAD_FAST | 9,600,000 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,902,320 | 78.3% |
| LOAD_CONST | 20,162,880 | 16.0% |
| LOAD_GLOBAL_MODULE | 5,763,840 | 4.6% |
| LOAD_GLOBAL_BUILTIN | 961,920 | 0.8% |
| STORE_FAST | 480,960 | 0.4% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,800,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,800,000 | 100.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_STR_1 | 4,800,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,800,000 | 100.0% |


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
| LOAD_CONST | 5,280,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,280,000 | 100.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 960 | 100.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,840 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 15,361,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 15,361,920 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 481,000 | 99.8% |
| LOAD_ATTR | 960 | 0.2% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 480,960 | 99.8% |
| STORE_FAST | 1,020 | 0.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 5,280,960 | 84.5% |
| LOAD_FAST | 482,880 | 7.7% |
| LOAD_FAST_LOAD_FAST | 480,000 | 7.7% |
| LOAD_CONST | 960 | 0.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,761,920 | 92.2% |
| RETURN_VALUE | 480,000 | 7.7% |
| POP_TOP | 4,800 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,760,960 | 75.6% |
| LOAD_FAST | 4,800,960 | 12.2% |
| BINARY_OP | 4,800,000 | 12.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 39,360,960 | 100.0% |
| RETURN_VALUE | 960 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480,960 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 15,365,760 | 98.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 295,500 | 1.9% |
| LOAD_CONST | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,367,680 | 98.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 295,500 | 1.9% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,280,000 | 52.4% |
| LOAD_GLOBAL_MODULE | 4,800,000 | 47.6% |
| LOAD_FAST | 960 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 9,600,000 | 95.2% |
| RESUME_CHECK | 481,920 | 4.8% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 960 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,800,000 | 50.0% |
| LOAD_FAST | 4,800,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,800,000 | 50.0% |
| BINARY_OP_ADD_UNICODE | 4,800,000 | 50.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,600,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,600,000 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,280,040 | 100.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,280,000 | 100.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,800,000 | 83.3% |
| EXTENDED_ARG | 480,960 | 8.3% |
| GET_ITER | 480,000 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,280,000 | 91.7% |
| LOAD_FAST | 480,960 | 8.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 960 | 94.1% |
| GET_ITER | 60 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 960 | 94.1% |
| LOAD_FAST | 60 | 5.9% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 15,365,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 15,365,760 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 960 | 100.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920 | 100.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 960 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_ATTR | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 60.0% |
| PUSH_NULL | 40 | 40.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 960 | 50.0% |
| CALL_BUILTIN_FAST | 960 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,800,000 | 44.1% |
| RESUME_CHECK | 15,365,760 | 23.5% |
| POP_JUMP_IF_FALSE | 9,600,040 | 14.7% |
| POP_JUMP_IF_TRUE | 4,800,000 | 7.4% |
| LOAD_CONST | 4,800,000 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 28,800,000 | 44.1% |
| LOAD_FAST | 20,642,940 | 31.6% |
| LOAD_ATTR_CLASS | 15,365,760 | 23.5% |
| LOAD_FAST_LOAD_FAST | 480,000 | 0.7% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,646,720 | 30.9% |
| LOAD_FAST_LOAD_FAST | 15,365,760 | 23.0% |
| POP_TOP | 14,881,920 | 22.3% |
| LOAD_CONST | 10,081,920 | 15.1% |
| STORE_FAST | 5,763,840 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 20,646,720 | 30.9% |
| STORE_FAST | 19,683,840 | 29.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 15,365,760 | 23.0% |
| CALL_BUILTIN_FAST | 5,280,960 | 7.9% |
| CALL_PY_EXACT_ARGS | 4,800,000 | 7.2% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 960 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 15,361,920 | 58.2% |
| COPY_FREE_VARS | 9,601,020 | 36.3% |
| CACHE | 964,800 | 3.7% |
| CALL_PY_EXACT_ARGS | 481,920 | 1.8% |
| BINARY_SUBSCR_GETITEM | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 15,365,760 | 58.2% |
| LOAD_FAST | 10,085,760 | 38.2% |
| NOP | 480,960 | 1.8% |
| LOAD_FAST_LOAD_FAST | 480,960 | 1.8% |
| LOAD_GLOBAL_MODULE | 1,000 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 961,920 | 99.8% |
| LOAD_FAST | 1,920 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 481,920 | 50.0% |
| LOAD_FAST_LOAD_FAST | 480,960 | 49.9% |
| LOAD_FAST | 960 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 960 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,600,000 | 100.0% |
| LOAD_ATTR | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,600,000 | 100.0% |
| POP_JUMP_IF_TRUE | 960 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 480,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480,960 | 100.0% |


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
|          hit |         4800 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     11041920 | 100.0% |
|          hit |          960 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 2,760 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 2,640 | 95.7% |
| other | 120 | 4.3% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      9600960 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4800000 | 24.4% |
|          hit |     14880060 | 75.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 1.7% |
| Failure | 1,180 | 98.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 1,180 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6244980 | 4.9% |
| specialization.deopt |       295500 | 0.2% |
|          hit |    106580220 | 82.9% |
|         miss |     15661260 | 12.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 295,520 | 99.4% |
| Failure | 1,760 | 0.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cmethod | 1,180 | 67.0% |
| other | 200 | 11.4% |
| cfunc noargs | 180 | 10.2% |
| no dict | 160 | 9.1% |
| class mutable | 40 | 2.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      5280060 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      5761980 | 100.0% |


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
| specialization.deferred |         9620 | 0.1% |
|          hit |     15371620 | 99.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 9.1% |
| Failure | 400 | 90.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 280 | 70.0% |
| class attr descriptor | 40 | 10.0% |
| class attr simple | 40 | 10.0% |
| shadowed | 40 | 10.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |    132034720 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          960 | 100.0% |


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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       963840 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       480960 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 818,147,160 | 64.8% |
| Not specialized | 141,458,520 | 11.2% |
| Specialized | 302,013,680 | 23.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_SUBSCR | 11,041,920 | 50.0% |
| CALL | 6,244,980 | 28.3% |
| BINARY_OP | 4,800,000 | 21.7% |
| LOAD_ATTR | 9,620 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR_DICT | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 15,661,260 | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| STORE_SUBSCR_DICT | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_DEREF | 0 | 0.0% |
| STORE_ATTR_SLOT | 0 | 0.0% |
| SET_FUNCTION_ATTRIBUTE | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RETURN_CONST | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 965,760 | 3.7% |
| Calls to Python functions inlined | 25,448,700 | 96.3% |
| Calls via PyEval_EvalFrame (total) | 965,760 | 3.7% |
| Calls via PyEval_EvalFrame (vector) | 965,760 | 3.7% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 965,760 | 3.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 26,414,460 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,945,080 | 4.9% |
| Frees to freelist | 1,945,020 |  |
| Allocations | 37,660,920 | 95.1% |
| Allocations to 512 bytes | 37,659,000 | 95.1% |
| Allocations to 4 kbytes | 960 | 0.0% |
| Allocations over 4 kbytes | 960 | 0.0% |
| Frees | 37,661,885 |  |
| New values | 0 |  |
| Interpreter increfs | 400,000,240 | 88.2% |
| Interpreter decrefs | 428,579,640 | 88.0% |
| Increfs | 53,372,200 | 11.8% |
| Decrefs | 58,667,545 | 12.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 487,007 |  |
| Method cache misses | 13 |  |
| Method cache collisions | 13 |  |
| Method cache dunder hits | 1,447,920 |  |
| Method cache dunder misses | 0 |  |


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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-10-04
