
# Pystats results

- benchmark: chameleon
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 250,634,460 | 22.0% | 22.0% |  |
| LOAD_CONST | 121,954,620 | 10.7% | 32.7% |  |
| STORE_FAST | 107,077,800 | 9.4% | 42.1% |  |
| IS_OP | 68,646,720 | 6.0% | 48.1% |  |
| LOAD_GLOBAL_BUILTIN | 65,289,660 | 5.7% | 53.8% |  |
| PUSH_NULL | 60,974,700 | 5.3% | 59.2% |  |
| LOAD_GLOBAL_MODULE | 56,667,940 | 5.0% | 64.1% |  |
| POP_JUMP_IF_FALSE | 54,247,740 | 4.8% | 68.9% |  |
| POP_TOP | 34,569,660 | 3.0% | 71.9% |  |
| CALL_BUILTIN_O | 34,562,880 | 3.0% | 75.0% |  |
| LOAD_FAST_LOAD_FAST | 27,852,480 | 2.4% | 77.4% |  |
| RESUME_CHECK | 26,414,460 | 2.3% | 79.7% |  |
| RETURN_VALUE | 25,930,620 | 2.3% | 82.0% |  |
| POP_JUMP_IF_TRUE | 19,680,960 | 1.7% | 83.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 15,663,180 | 1.4% | 85.1% | 100.0% |
| LOAD_ATTR_CLASS | 15,365,760 | 1.3% | 86.4% |  |
| POP_JUMP_IF_NONE | 14,883,840 | 1.3% | 87.7% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 10,562,880 | 0.9% | 88.7% |  |
| CALL_PY_EXACT_ARGS | 10,081,920 | 0.9% | 89.6% |  |
| COPY_FREE_VARS | 9,601,020 | 0.8% | 90.4% |  |
| TO_BOOL_BOOL | 9,600,960 | 0.8% | 91.2% |  |
| POP_JUMP_IF_NOT_NONE | 9,600,960 | 0.8% | 92.1% |  |
| CALL_TYPE_1 | 9,600,000 | 0.8% | 92.9% |  |
| CALL_STR_1 | 9,600,000 | 0.8% | 93.8% |  |
| CALL | 6,246,760 | 0.5% | 94.3% |  |
| STORE_SUBSCR | 6,244,480 | 0.5% | 94.9% |  |
| JUMP_FORWARD | 5,761,920 | 0.5% | 95.4% |  |
| NOP | 5,282,940 | 0.5% | 95.8% |  |
| ENTER_EXECUTOR | 5,280,960 | 0.5% | 96.3% |  |
| DELETE_SUBSCR | 5,280,960 | 0.5% | 96.8% |  |
| COMPARE_OP_INT | 5,280,060 | 0.5% | 97.2% |  |
| BINARY_OP_SUBTRACT_INT | 5,280,000 | 0.5% | 97.7% |  |
| BINARY_OP | 4,801,200 | 0.4% | 98.1% |  |
| LOAD_DEREF | 4,800,120 | 0.4% | 98.5% |  |
| BINARY_OP_ADD_UNICODE | 4,800,000 | 0.4% | 98.9% |  |
| BINARY_OP_ADD_INT | 4,800,000 | 0.4% | 99.4% |  |
| CALL_BUILTIN_FAST | 1,447,680 | 0.1% | 99.5% |  |
| INTERPRETER_EXIT | 965,760 | 0.1% | 99.6% |  |
| STORE_ATTR_SLOT | 963,840 | 0.1% | 99.7% |  |
| RETURN_CONST | 483,840 | 0.0% | 99.7% |  |
| BUILD_TUPLE | 482,880 | 0.0% | 99.7% |  |
| CALL_BUILTIN_CLASS | 481,980 | 0.0% | 99.8% |  |
| GET_ITER | 481,020 | 0.0% | 99.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 480,960 | 0.0% | 99.9% |  |
| FOR_ITER_LIST | 480,960 | 0.0% | 99.9% |  |
| EXTENDED_ARG | 480,960 | 0.0% | 100.0% |  |
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
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 40 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 84,983,340 | 7.5% | 7.5% |
| LOAD_FAST PUSH_NULL | 55,211,700 | 4.8% | 12.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 44,646,720 | 3.9% | 16.2% |
| IS_OP POP_JUMP_IF_FALSE | 44,646,720 | 3.9% | 20.1% |
| PUSH_NULL LOAD_CONST | 41,294,400 | 3.6% | 23.7% |
| CALL_BUILTIN_O POP_TOP | 34,561,920 | 3.0% | 26.8% |
| LOAD_FAST LOAD_CONST | 31,207,740 | 2.7% | 29.5% |
| LOAD_GLOBAL_BUILTIN IS_OP | 28,800,000 | 2.5% | 32.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 28,800,000 | 2.5% | 34.6% |
| LOAD_FAST RETURN_VALUE | 24,965,820 | 2.2% | 36.8% |
| LOAD_CONST CALL_BUILTIN_O | 24,961,920 | 2.2% | 38.9% |
| LOAD_CONST LOAD_CONST | 24,000,960 | 2.1% | 41.1% |
| LOAD_GLOBAL_MODULE IS_OP | 20,646,720 | 1.8% | 42.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 20,646,720 | 1.8% | 44.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 20,642,940 | 1.8% | 46.5% |
| POP_TOP LOAD_FAST | 19,684,800 | 1.7% | 48.2% |
| PUSH_NULL LOAD_FAST | 19,200,060 | 1.7% | 49.9% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 15,367,680 | 1.3% | 51.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 15,365,760 | 1.3% | 52.6% |
| LOAD_GLOBAL_MODULE CALL_METHOD_DESCRIPTOR_FAST | 15,365,760 | 1.3% | 53.9% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR_CLASS | 15,365,760 | 1.3% | 55.3% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 15,365,760 | 1.3% | 56.6% |
| LOAD_ATTR_CLASS LOAD_FAST_LOAD_FAST | 15,365,760 | 1.3% | 58.0% |
| STORE_FAST LOAD_CONST | 15,363,840 | 1.3% | 59.3% |
| LOAD_GLOBAL_MODULE STORE_FAST | 14,884,800 | 1.3% | 60.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 14,883,840 | 1.3% | 61.9% |
| RETURN_VALUE STORE_FAST | 14,401,920 | 1.3% | 63.2% |
| IS_OP POP_JUMP_IF_TRUE | 14,400,000 | 1.3% | 64.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 14,399,040 | 1.3% | 65.7% |
| LOAD_CONST CALL_BOUND_METHOD_EXACT_ARGS | 10,562,880 | 0.9% | 66.7% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 10,562,880 | 0.9% | 67.6% |
| RESUME_CHECK LOAD_FAST | 10,085,760 | 0.9% | 68.5% |
| LOAD_FAST LOAD_FAST | 10,083,840 | 0.9% | 69.4% |
| LOAD_CONST STORE_FAST | 10,083,840 | 0.9% | 70.2% |
| POP_TOP LOAD_GLOBAL_MODULE | 10,082,880 | 0.9% | 71.1% |
| COPY_FREE_VARS RESUME_CHECK | 9,601,020 | 0.8% | 72.0% |
| POP_JUMP_IF_NONE LOAD_FAST | 9,600,960 | 0.8% | 72.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 9,600,960 | 0.8% | 73.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 9,600,040 | 0.8% | 74.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 9,600,000 | 0.8% | 75.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 9,600,000 | 0.8% | 76.2% |
| LOAD_FAST_LOAD_FAST IS_OP | 9,600,000 | 0.8% | 77.0% |
| LOAD_FAST TO_BOOL_BOOL | 9,600,000 | 0.8% | 77.9% |
| LOAD_FAST STORE_FAST | 9,600,000 | 0.8% | 78.7% |
| LOAD_FAST CALL_TYPE_1 | 9,600,000 | 0.8% | 79.5% |
| IS_OP STORE_FAST | 9,600,000 | 0.8% | 80.4% |
| CALL_TYPE_1 STORE_FAST | 9,600,000 | 0.8% | 81.2% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 9,600,000 | 0.8% | 82.1% |
| LOAD_CONST LOAD_FAST | 5,765,760 | 0.5% | 82.6% |
| STORE_SUBSCR LOAD_FAST | 5,761,920 | 0.5% | 83.1% |
| LOAD_CONST STORE_SUBSCR | 5,761,920 | 0.5% | 83.6% |
| STORE_FAST LOAD_GLOBAL_MODULE | 5,284,800 | 0.5% | 84.0% |
| LOAD_CONST LOAD_GLOBAL_MODULE | 5,282,880 | 0.5% | 84.5% |
| LOAD_FAST CALL | 5,281,940 | 0.5% | 85.0% |
| RETURN_VALUE LOAD_CONST | 5,280,960 | 0.5% | 85.4% |
| LOAD_CONST DELETE_SUBSCR | 5,280,960 | 0.5% | 85.9% |
| JUMP_FORWARD LOAD_FAST | 5,280,960 | 0.5% | 86.4% |
| DELETE_SUBSCR JUMP_FORWARD | 5,280,960 | 0.5% | 86.8% |
| LOAD_CONST COMPARE_OP_INT | 5,280,040 | 0.5% | 87.3% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 5,280,000 | 0.5% | 87.7% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 5,280,000 | 0.5% | 88.2% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 5,280,000 | 0.5% | 88.7% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 5,280,000 | 0.5% | 89.1% |
| LOAD_FAST CALL_BUILTIN_O | 4,800,960 | 0.4% | 89.6% |
| NOP LOAD_DEREF | 4,800,060 | 0.4% | 90.0% |
| LOAD_DEREF PUSH_NULL | 4,800,060 | 0.4% | 90.4% |
| LOAD_FAST BINARY_OP | 4,800,020 | 0.4% | 90.8% |
| RETURN_VALUE CALL_STR_1 | 4,800,000 | 0.4% | 91.2% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 4,800,000 | 0.4% | 91.7% |
| POP_JUMP_IF_NONE NOP | 4,800,000 | 0.4% | 92.1% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 4,800,000 | 0.4% | 92.5% |
| LOAD_FAST IS_OP | 4,800,000 | 0.4% | 92.9% |
| LOAD_FAST CALL_STR_1 | 4,800,000 | 0.4% | 93.3% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 4,800,000 | 0.4% | 93.8% |
| LOAD_CONST IS_OP | 4,800,000 | 0.4% | 94.2% |
| LOAD_CONST BINARY_OP_ADD_INT | 4,800,000 | 0.4% | 94.6% |
| CALL_STR_1 STORE_FAST | 4,800,000 | 0.4% | 95.0% |
| CALL_STR_1 BINARY_OP_ADD_UNICODE | 4,800,000 | 0.4% | 95.5% |
| CALL LOAD_CONST | 4,800,000 | 0.4% | 95.9% |
| BINARY_OP_ADD_UNICODE STORE_FAST | 4,800,000 | 0.4% | 96.3% |
| BINARY_OP_ADD_INT STORE_FAST | 4,800,000 | 0.4% | 96.7% |
| BINARY_OP CALL_BUILTIN_O | 4,800,000 | 0.4% | 97.1% |
| ENTER_EXECUTOR RESUME_CHECK | 4,799,040 | 0.4% | 97.6% |
| POP_TOP ENTER_EXECUTOR | 4,320,940 | 0.4% | 97.9% |
| CACHE RESUME_CHECK | 964,800 | 0.1% | 98.0% |
| CALL_BUILTIN_FAST STORE_FAST | 962,880 | 0.1% | 98.1% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 961,920 | 0.1% | 98.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 961,920 | 0.1% | 98.3% |
| RETURN_VALUE PUSH_NULL | 960,960 | 0.1% | 98.4% |
| RETURN_VALUE INTERPRETER_EXIT | 483,840 | 0.0% | 98.4% |
| LOAD_FAST CALL_BUILTIN_FAST | 482,880 | 0.0% | 98.4% |
| STORE_ATTR_SLOT RETURN_CONST | 481,920 | 0.0% | 98.5% |
| RETURN_CONST INTERPRETER_EXIT | 481,920 | 0.0% | 98.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 481,920 | 0.0% | 98.6% |
| LOAD_GLOBAL_MODULE CALL_BUILTIN_FAST | 481,920 | 0.0% | 98.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 481,920 | 0.0% | 98.7% |
| LOAD_FAST GET_ITER | 481,020 | 0.0% | 98.7% |
| ENTER_EXECUTOR LOAD_FAST | 481,020 | 0.0% | 98.7% |
| CALL STORE_FAST | 481,020 | 0.0% | 98.8% |
| LOAD_FAST CALL_BUILTIN_CLASS | 481,000 | 0.0% | 98.8% |


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
| CALL_BUILTIN_O | 34,561,920 | 100.0% |
| CALL_BUILTIN_FAST | 4,800 | 0.0% |
| RETURN_CONST | 1,920 | 0.0% |
| CALL | 1,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,684,800 | 56.9% |
| LOAD_GLOBAL_MODULE | 10,082,880 | 29.2% |
| ENTER_EXECUTOR | 4,320,940 | 12.5% |
| EXTENDED_ARG | 479,040 | 1.4% |
| RETURN_CONST | 960 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 55,211,700 | 90.5% |
| LOAD_DEREF | 4,800,060 | 7.9% |
| RETURN_VALUE | 960,960 | 1.6% |
| LOAD_ATTR | 980 | 0.0% |
| LOAD_SUPER_ATTR_ATTR | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 41,294,400 | 67.7% |
| LOAD_FAST | 19,200,060 | 31.5% |
| CALL | 480,240 | 0.8% |


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
| LOAD_CONST | 5,761,920 | 92.3% |
| LOAD_FAST_LOAD_FAST | 480,960 | 7.7% |
| STORE_SUBSCR | 1,600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,761,920 | 92.3% |
| LOAD_FAST_LOAD_FAST | 480,960 | 7.7% |
| STORE_SUBSCR | 1,600 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 480,960 | 7.7% |
| PUSH_NULL | 480,240 | 7.7% |
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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,320,940 | 81.8% |
| POP_JUMP_IF_TRUE | 480,000 | 9.1% |
| EXTENDED_ARG | 479,980 | 9.1% |
| JUMP_BACKWARD | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,799,040 | 90.9% |
| LOAD_FAST | 481,020 | 9.1% |
| CALL | 900 | 0.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 479,040 | 99.6% |
| POP_JUMP_IF_TRUE | 960 | 0.2% |
| GET_ITER | 960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 479,980 | 99.8% |
| FOR_ITER_LIST | 960 | 0.2% |
| JUMP_BACKWARD | 20 | 0.0% |


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
| POP_TOP | 20 | 50.0% |
| EXTENDED_ARG | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 40 | 100.0% |


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
| PUSH_NULL | 41,294,400 | 33.9% |
| LOAD_FAST | 31,207,740 | 25.6% |
| LOAD_CONST | 24,000,960 | 19.7% |
| STORE_FAST | 15,363,840 | 12.6% |
| RETURN_VALUE | 5,280,960 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 24,961,920 | 20.5% |
| LOAD_CONST | 24,000,960 | 19.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 10,562,880 | 8.7% |
| STORE_FAST | 10,083,840 | 8.3% |
| LOAD_FAST | 5,765,760 | 4.7% |


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
| STORE_FAST | 84,983,340 | 33.9% |
| POP_JUMP_IF_FALSE | 44,646,720 | 17.8% |
| LOAD_GLOBAL_BUILTIN | 20,642,940 | 8.2% |
| POP_TOP | 19,684,800 | 7.9% |
| PUSH_NULL | 19,200,060 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 55,211,700 | 22.0% |
| LOAD_CONST | 31,207,740 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 28,800,000 | 11.5% |
| RETURN_VALUE | 24,965,820 | 10.0% |
| LOAD_GLOBAL_MODULE | 20,646,720 | 8.2% |


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
| ENTER_EXECUTOR | 480,000 | 2.4% |
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
| CALL_METHOD_DESCRIPTOR_FAST | 15,367,680 | 14.4% |
| LOAD_GLOBAL_MODULE | 14,884,800 | 13.9% |
| RETURN_VALUE | 14,401,920 | 13.4% |
| LOAD_CONST | 10,083,840 | 9.4% |
| LOAD_FAST | 9,600,000 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,983,340 | 79.4% |
| LOAD_CONST | 15,363,840 | 14.3% |
| LOAD_GLOBAL_MODULE | 5,284,800 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 961,920 | 0.9% |
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
| LOAD_CONST | 10,562,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,562,880 | 100.0% |


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
| LOAD_FAST | 482,880 | 33.4% |
| LOAD_GLOBAL_MODULE | 481,920 | 33.3% |
| LOAD_FAST_LOAD_FAST | 480,000 | 33.2% |
| LOAD_CONST | 960 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 962,880 | 66.5% |
| RETURN_VALUE | 480,000 | 33.2% |
| POP_TOP | 4,800 | 0.3% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,961,920 | 72.2% |
| LOAD_FAST | 4,800,960 | 13.9% |
| BINARY_OP | 4,800,000 | 13.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 34,561,920 | 100.0% |
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
| GET_ITER | 480,000 | 99.8% |
| EXTENDED_ARG | 960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480,960 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


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
| LOAD_FAST | 20,646,720 | 36.4% |
| LOAD_FAST_LOAD_FAST | 15,365,760 | 27.1% |
| POP_TOP | 10,082,880 | 17.8% |
| STORE_FAST | 5,284,800 | 9.3% |
| LOAD_CONST | 5,282,880 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 20,646,720 | 36.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 15,365,760 | 27.1% |
| STORE_FAST | 14,884,800 | 26.3% |
| CALL_PY_EXACT_ARGS | 4,800,000 | 8.5% |
| LOAD_FAST_LOAD_FAST | 481,920 | 0.9% |


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
| CALL_BOUND_METHOD_EXACT_ARGS | 10,562,880 | 40.0% |
| COPY_FREE_VARS | 9,601,020 | 36.3% |
| ENTER_EXECUTOR | 4,799,040 | 18.2% |
| CACHE | 964,800 | 3.7% |
| CALL_PY_EXACT_ARGS | 481,920 | 1.8% |

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
| specialization.deferred |      6242880 | 100.0% |
|          hit |          960 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 1,600 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 1,480 | 92.5% |
| other | 120 | 7.5% |


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
| specialization.deferred |      6244980 | 5.7% |
| specialization.deopt |       295500 | 0.3% |
|          hit |     87384060 | 80.0% |
|         miss |     15661260 | 14.3% |

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
|          hit |       481020 | 100.0% |


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
|          hit |    121957600 | 100.0% |

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
| Basic | 736,562,700 | 64.6% |
| Not specialized | 131,377,400 | 11.5% |
| Specialized | 272,258,480 | 23.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 6,244,980 | 36.1% |
| STORE_SUBSCR | 6,242,880 | 36.1% |
| BINARY_OP | 4,800,000 | 27.7% |
| LOAD_ATTR | 9,620 | 0.1% |
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
| Calls to PyEval_EvalDefault | 965,760 | 4.5% |
| Calls to Python functions inlined | 20,649,660 | 95.5% |
| Calls via PyEval_EvalFrame (total) | 965,760 | 4.5% |
| Calls via PyEval_EvalFrame (vector) | 965,760 | 4.5% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 965,760 | 4.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 26,414,460 | 122.2% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,945,080 | 4.9% |
| Frees to freelist | 1,945,020 |  |
| Allocations | 37,660,960 | 95.1% |
| Allocations to 512 bytes | 37,659,020 | 95.1% |
| Allocations to 4 kbytes | 980 | 0.0% |
| Allocations over 4 kbytes | 960 | 0.0% |
| Frees | 37,661,881 |  |
| New values | 0 |  |
| Interpreter increfs | 355,852,780 | 77.6% |
| Interpreter decrefs | 383,947,260 | 78.0% |
| Increfs | 102,800,660 | 22.4% |
| Decrefs | 108,580,921 | 22.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 487,012 |  |
| Method cache misses | 8 |  |
| Method cache collisions | 8 |  |
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

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 40 |  |
| Traces created | 40 | 100.0% |
| Traces executed | 5,280,960 |  |
| Uops executed | 230,368,140 | 43 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |


</details>

**Trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 50.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 20 | 50.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 50.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 50.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 481,020 | 9.1% |
| <= 16 | 900 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 4,799,040 | 90.9% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 44,634,240 | 19.4% | 19.4% |
| LOAD_FAST | 23,996,100 | 10.4% | 29.8% |
| LOAD_CONST | 23,995,200 | 10.4% | 40.2% |
| STORE_FAST | 19,197,060 | 8.3% | 48.5% |
| PUSH_NULL | 14,398,020 | 6.3% | 54.8% |
| _LOAD_GLOBAL_MODULE | 10,077,120 | 4.4% | 59.2% |
| _GUARD_GLOBALS_VERSION | 10,077,120 | 4.4% | 63.5% |
| _POP_JUMP_IF_TRUE | 5,280,960 | 2.3% | 65.8% |
| _EXIT_TRACE | 5,280,960 | 2.3% | 68.1% |
| POP_TOP | 5,280,060 | 2.3% | 70.4% |
| _ITER_CHECK_LIST | 5,280,000 | 2.3% | 72.7% |
| _IS_ITER_EXHAUSTED_LIST | 5,280,000 | 2.3% | 75.0% |
| _SAVE_CURRENT_IP | 4,799,040 | 2.1% | 77.1% |
| _PUSH_FRAME | 4,799,040 | 2.1% | 79.2% |
| _ITER_NEXT_LIST | 4,799,040 | 2.1% | 81.2% |
| _INIT_CALL_PY_EXACT_ARGS | 4,799,040 | 2.1% | 83.3% |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 4,799,040 | 2.1% | 85.4% |
| _CHECK_STACK_SPACE | 4,799,040 | 2.1% | 87.5% |
| _CHECK_PEP_523 | 4,799,040 | 2.1% | 89.6% |
| _CHECK_FUNCTION_EXACT_ARGS | 4,799,040 | 2.1% | 91.7% |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 4,799,040 | 2.1% | 93.7% |
| STORE_SUBSCR | 4,799,040 | 2.1% | 95.8% |
| CALL_BUILTIN_O | 4,799,040 | 2.1% | 97.9% |
| CALL_BUILTIN_FAST | 4,799,040 | 2.1% | 100.0% |
| _ITER_CHECK_RANGE | 960 | 0.0% | 100.0% |
| _IS_ITER_EXHAUSTED_RANGE | 960 | 0.0% | 100.0% |
| _ITER_NEXT_RANGE | 900 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| CALL | 20 |


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
