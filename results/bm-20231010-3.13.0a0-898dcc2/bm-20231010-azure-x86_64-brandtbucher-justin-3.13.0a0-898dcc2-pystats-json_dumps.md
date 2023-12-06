
# Pystats results

- benchmark: json_dumps
- fork: brandtbucher
- ref: justin
- commit hash: 898dcc2
- commit date: 2023-10-10T14:45:03+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 53,775,560 | 23.1% | 23.1% |  |
| TO_BOOL_BOOL | 19,204,800 | 8.3% | 31.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 15,363,840 | 6.6% | 38.0% |  |
| POP_JUMP_IF_FALSE | 13,443,420 | 5.8% | 43.8% |  |
| LOAD_GLOBAL_MODULE | 11,523,460 | 5.0% | 48.8% |  |
| LOAD_GLOBAL_BUILTIN | 11,522,940 | 5.0% | 53.7% |  |
| STORE_FAST | 9,603,380 | 4.1% | 57.8% |  |
| LOAD_CONST | 9,602,460 | 4.1% | 62.0% |  |
| POP_JUMP_IF_NOT_NONE | 9,602,400 | 4.1% | 66.1% |  |
| POP_JUMP_IF_TRUE | 7,681,920 | 3.3% | 69.4% |  |
| CALL | 5,763,660 | 2.5% | 71.9% |  |
| RESUME_CHECK | 5,761,980 | 2.5% | 74.4% |  |
| RETURN_VALUE | 5,761,500 | 2.5% | 76.9% |  |
| JUMP_FORWARD | 5,761,440 | 2.5% | 79.3% |  |
| LOAD_ATTR | 3,841,980 | 1.7% | 81.0% |  |
| LOAD_FAST_LOAD_FAST | 3,840,960 | 1.7% | 82.6% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,840,960 | 1.7% | 84.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,840,960 | 1.7% | 85.9% |  |
| CALL_ISINSTANCE | 3,840,960 | 1.7% | 87.6% |  |
| BUILD_TUPLE | 3,840,960 | 1.7% | 89.3% |  |
| ENTER_EXECUTOR | 1,922,720 | 0.8% | 90.1% |  |
| PUSH_NULL | 1,921,400 | 0.8% | 90.9% |  |
| POP_TOP | 1,921,020 | 0.8% | 91.7% |  |
| TO_BOOL | 1,920,960 | 0.8% | 92.6% |  |
| UNARY_NEGATIVE | 1,920,480 | 0.8% | 93.4% |  |
| SET_FUNCTION_ATTRIBUTE | 1,920,480 | 0.8% | 94.2% |  |
| POP_JUMP_IF_NONE | 1,920,480 | 0.8% | 95.0% |  |
| MAKE_FUNCTION | 1,920,480 | 0.8% | 95.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,920,480 | 0.8% | 96.7% |  |
| CALL_PY_EXACT_ARGS | 1,920,480 | 0.8% | 97.5% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,920,480 | 0.8% | 98.3% |  |
| CALL_KW | 1,920,480 | 0.8% | 99.2% |  |
| BUILD_MAP | 1,920,480 | 0.8% | 100.0% |  |
| GET_ITER | 1,020 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 700 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 580 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 480 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 480 | 0.0% | 100.0% |  |
| RETURN_CONST | 480 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 480 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 480 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 80 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 13,443,360 | 5.8% | 5.8% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 13,443,360 | 5.8% | 11.6% |
| LOAD_FAST TO_BOOL_BOOL | 11,522,880 | 5.0% | 16.5% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 7,681,920 | 3.3% | 19.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,681,920 | 3.3% | 23.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 7,681,920 | 3.3% | 26.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,761,440 | 2.5% | 28.9% |
| STORE_FAST JUMP_FORWARD | 5,761,440 | 2.5% | 31.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 5,761,440 | 2.5% | 33.9% |
| JUMP_FORWARD LOAD_FAST | 5,761,440 | 2.5% | 36.4% |
| RESUME_CHECK LOAD_FAST | 3,841,440 | 1.7% | 38.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,841,020 | 1.7% | 39.7% |
| LOAD_FAST LOAD_CONST | 3,841,020 | 1.7% | 41.3% |
| POP_JUMP_IF_TRUE LOAD_FAST | 3,840,960 | 1.7% | 43.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 3,840,960 | 1.7% | 44.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 3,840,960 | 1.7% | 46.3% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,840,960 | 1.7% | 47.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_FAST | 3,840,960 | 1.7% | 49.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 3,840,960 | 1.7% | 51.2% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 3,840,960 | 1.7% | 52.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 3,840,960 | 1.7% | 54.5% |
| PUSH_NULL LOAD_FAST | 1,921,020 | 0.8% | 55.4% |
| STORE_FAST LOAD_FAST | 1,920,920 | 0.8% | 56.2% |
| LOAD_FAST PUSH_NULL | 1,920,800 | 0.8% | 57.0% |
| POP_TOP ENTER_EXECUTOR | 1,920,780 | 0.8% | 57.8% |
| CALL STORE_FAST | 1,920,540 | 0.8% | 58.7% |
| UNARY_NEGATIVE BUILD_TUPLE | 1,920,480 | 0.8% | 59.5% |
| TO_BOOL POP_JUMP_IF_TRUE | 1,920,480 | 0.8% | 60.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 1,920,480 | 0.8% | 61.2% |
| SET_FUNCTION_ATTRIBUTE STORE_FAST | 1,920,480 | 0.8% | 62.0% |
| RETURN_VALUE STORE_FAST | 1,920,480 | 0.8% | 62.8% |
| RETURN_VALUE RETURN_VALUE | 1,920,480 | 0.8% | 63.6% |
| RETURN_VALUE POP_TOP | 1,920,480 | 0.8% | 64.5% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,920,480 | 0.8% | 65.3% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_MODULE | 1,920,480 | 0.8% | 66.1% |
| POP_JUMP_IF_TRUE LOAD_CONST | 1,920,480 | 0.8% | 66.9% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 1,920,480 | 0.8% | 67.8% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,920,480 | 0.8% | 68.6% |
| POP_JUMP_IF_FALSE BUILD_MAP | 1,920,480 | 0.8% | 69.4% |
| MAKE_FUNCTION SET_FUNCTION_ATTRIBUTE | 1,920,480 | 0.8% | 70.2% |
| LOAD_GLOBAL_MODULE UNARY_NEGATIVE | 1,920,480 | 0.8% | 71.1% |
| LOAD_GLOBAL_MODULE STORE_FAST | 1,920,480 | 0.8% | 71.9% |
| LOAD_GLOBAL_MODULE POP_JUMP_IF_NONE | 1,920,480 | 0.8% | 72.7% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 1,920,480 | 0.8% | 73.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,920,480 | 0.8% | 74.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_WITH_VALUES | 1,920,480 | 0.8% | 75.2% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 1,920,480 | 0.8% | 76.0% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 1,920,480 | 0.8% | 76.9% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 1,920,480 | 0.8% | 77.7% |
| LOAD_GLOBAL_BUILTIN BUILD_TUPLE | 1,920,480 | 0.8% | 78.5% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,920,480 | 0.8% | 79.3% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR | 1,920,480 | 0.8% | 80.2% |
| LOAD_FAST TO_BOOL | 1,920,480 | 0.8% | 81.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,920,480 | 0.8% | 81.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,920,480 | 0.8% | 82.6% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 1,920,480 | 0.8% | 83.5% |
| LOAD_CONST MAKE_FUNCTION | 1,920,480 | 0.8% | 84.3% |
| LOAD_CONST LOAD_CONST | 1,920,480 | 0.8% | 85.1% |
| LOAD_CONST LOAD_ATTR_METHOD_NO_DICT | 1,920,480 | 0.8% | 85.9% |
| LOAD_CONST CALL_KW | 1,920,480 | 0.8% | 86.8% |
| LOAD_CONST CALL | 1,920,480 | 0.8% | 87.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,920,480 | 0.8% | 88.4% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NOT_NONE | 1,920,480 | 0.8% | 89.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_BUILTIN | 1,920,480 | 0.8% | 90.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL | 1,920,480 | 0.8% | 90.9% |
| LOAD_ATTR LOAD_GLOBAL_MODULE | 1,920,480 | 0.8% | 91.7% |
| LOAD_ATTR LOAD_FAST_LOAD_FAST | 1,920,480 | 0.8% | 92.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,920,480 | 0.8% | 93.4% |
| CALL_METHOD_DESCRIPTOR_O RETURN_VALUE | 1,920,480 | 0.8% | 94.2% |
| CALL_KW RESUME_CHECK | 1,920,480 | 0.8% | 95.0% |
| CALL RETURN_VALUE | 1,920,480 | 0.8% | 95.9% |
| CALL RESUME_CHECK | 1,920,480 | 0.8% | 96.7% |
| BUILD_TUPLE LOAD_CONST | 1,920,480 | 0.8% | 97.5% |
| BUILD_TUPLE CALL_ISINSTANCE | 1,920,480 | 0.8% | 98.3% |
| BUILD_MAP STORE_FAST | 1,920,480 | 0.8% | 99.2% |
| ENTER_EXECUTOR CALL | 1,920,280 | 0.8% | 100.0% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 1,920 | 0.0% | 100.0% |
| CALL CALL | 1,540 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 1,020 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR | 960 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 680 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 540 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 540 | 0.0% | 100.0% |
| CALL POP_TOP | 540 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 520 | 0.0% | 100.0% |
| LOAD_FAST CALL | 500 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 480 | 0.0% | 100.0% |
| TO_BOOL TO_BOOL | 480 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 480 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 480 | 0.0% | 100.0% |
| RETURN_CONST INTERPRETER_EXIT | 480 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_LIST | 480 | 0.0% | 100.0% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE | 480 | 0.0% | 100.0% |
| ENTER_EXECUTOR RETURN_CONST | 480 | 0.0% | 100.0% |
| CACHE RESUME_CHECK | 480 | 0.0% | 100.0% |
| PUSH_NULL CALL | 380 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 180 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 160 | 0.0% | 100.0% |
| STORE_FAST LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |


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
| RESUME_CHECK | 480 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 540 | 52.9% |
| FOR_ITER_LIST | 480 | 47.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,920,480 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,920,480 | 100.0% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,920,780 | 100.0% |
| JUMP_BACKWARD | 180 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920,800 | 100.0% |
| LOAD_ATTR_MODULE | 520 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,921,020 | 100.0% |
| CALL | 380 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,920,480 | 33.3% |
| CALL_METHOD_DESCRIPTOR_O | 1,920,480 | 33.3% |
| CALL | 1,920,480 | 33.3% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920,480 | 33.3% |
| RETURN_VALUE | 1,920,480 | 33.3% |
| POP_TOP | 1,920,480 | 33.3% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 20 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920,480 | 100.0% |
| TO_BOOL | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,920,480 | 100.0% |
| TO_BOOL | 480 | 0.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,920,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,920,480 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 20 | 100.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,920,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920,480 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNARY_NEGATIVE | 1,920,480 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 1,920,480 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920,480 | 50.0% |
| CALL_ISINSTANCE | 1,920,480 | 50.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920,480 | 33.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,920,480 | 33.3% |
| ENTER_EXECUTOR | 1,920,280 | 33.3% |
| CALL | 1,540 | 0.0% |
| LOAD_FAST | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920,540 | 33.3% |
| RETURN_VALUE | 1,920,480 | 33.3% |
| RESUME_CHECK | 1,920,480 | 33.3% |
| CALL | 1,540 | 0.0% |
| POP_TOP | 540 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,920,480 | 100.0% |


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

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,920,780 | 99.9% |
| ENTER_EXECUTOR | 1,920 | 0.1% |
| JUMP_BACKWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,920,280 | 99.9% |
| ENTER_EXECUTOR | 1,920 | 0.1% |
| RETURN_CONST | 480 | 0.0% |
| LOAD_FAST | 40 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 160 | 88.9% |
| ENTER_EXECUTOR | 20 | 11.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,761,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,761,440 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,920,480 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,920,480 | 50.0% |
| LOAD_ATTR | 960 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,920,480 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,920,480 | 50.0% |
| LOAD_ATTR | 960 | 0.0% |
| LOAD_ATTR_MODULE | 40 | 0.0% |
| PUSH_NULL | 20 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,841,020 | 40.0% |
| POP_JUMP_IF_TRUE | 1,920,480 | 20.0% |
| LOAD_CONST | 1,920,480 | 20.0% |
| BUILD_TUPLE | 1,920,480 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,920,480 | 20.0% |
| LOAD_CONST | 1,920,480 | 20.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,920,480 | 20.0% |
| CALL_KW | 1,920,480 | 20.0% |
| CALL | 1,920,480 | 20.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| NOP | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| PUSH_NULL | 60 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 7,681,920 | 14.3% |
| POP_JUMP_IF_FALSE | 7,681,920 | 14.3% |
| LOAD_ATTR_INSTANCE_VALUE | 5,761,440 | 10.7% |
| JUMP_FORWARD | 5,761,440 | 10.7% |
| RESUME_CHECK | 3,841,440 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 13,443,360 | 25.0% |
| TO_BOOL_BOOL | 11,522,880 | 21.4% |
| POP_JUMP_IF_NOT_NONE | 7,681,920 | 14.3% |
| LOAD_CONST | 3,841,020 | 7.1% |
| LOAD_GLOBAL_BUILTIN | 3,840,960 | 7.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,920,480 | 50.0% |
| LOAD_ATTR | 1,920,480 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,920,480 | 50.0% |
| LOAD_ATTR | 1,920,480 | 50.0% |


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

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 13,443,360 | 100.0% |
| COMPARE_OP_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,681,920 | 57.1% |
| LOAD_GLOBAL_MODULE | 3,840,960 | 28.6% |
| BUILD_MAP | 1,920,480 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,920,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920,480 | 100.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,681,920 | 80.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,920,480 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,681,920 | 80.0% |
| LOAD_GLOBAL_MODULE | 1,920,480 | 20.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,761,440 | 75.0% |
| TO_BOOL | 1,920,480 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840,960 | 50.0% |
| LOAD_GLOBAL_MODULE | 1,920,480 | 25.0% |
| LOAD_CONST | 1,920,480 | 25.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 480 | 100.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,920,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920,480 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,920,540 | 20.0% |
| SET_FUNCTION_ATTRIBUTE | 1,920,480 | 20.0% |
| RETURN_VALUE | 1,920,480 | 20.0% |
| LOAD_GLOBAL_MODULE | 1,920,480 | 20.0% |
| BUILD_MAP | 1,920,480 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 5,761,440 | 60.0% |
| LOAD_FAST | 1,920,920 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 1,920,480 | 20.0% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |


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

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,920,480 | 50.0% |
| BUILD_TUPLE | 1,920,480 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,840,960 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,920,480 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,920,480 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| COMPARE_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 480 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 540 | 77.1% |
| JUMP_BACKWARD | 160 | 22.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 680 | 97.1% |
| LOAD_FAST | 20 | 2.9% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,443,360 | 87.5% |
| LOAD_FAST_LOAD_FAST | 1,920,480 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,761,440 | 37.5% |
| TO_BOOL_BOOL | 3,840,960 | 25.0% |
| POP_JUMP_IF_NOT_NONE | 1,920,480 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 1,920,480 | 12.5% |
| CALL | 1,920,480 | 12.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920,480 | 100.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,920,480 | 50.0% |
| LOAD_FAST | 1,920,480 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840,960 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 540 | 93.1% |
| LOAD_ATTR | 40 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 520 | 89.7% |
| STORE_FAST | 60 | 10.3% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840,960 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840,960 | 33.3% |
| STORE_FAST | 1,920,480 | 16.7% |
| RESUME_CHECK | 1,920,480 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 1,920,480 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,920,480 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,841,020 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 1,920,480 | 16.7% |
| LOAD_ATTR | 1,920,480 | 16.7% |
| CALL_ISINSTANCE | 1,920,480 | 16.7% |
| BUILD_TUPLE | 1,920,480 | 16.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,840,960 | 33.3% |
| POP_JUMP_IF_TRUE | 1,920,480 | 16.7% |
| POP_JUMP_IF_NOT_NONE | 1,920,480 | 16.7% |
| LOAD_GLOBAL_MODULE | 1,920,480 | 16.7% |
| LOAD_ATTR | 1,920,480 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNARY_NEGATIVE | 1,920,480 | 16.7% |
| STORE_FAST | 1,920,480 | 16.7% |
| POP_JUMP_IF_NONE | 1,920,480 | 16.7% |
| LOAD_GLOBAL_MODULE | 1,920,480 | 16.7% |
| LOAD_FAST_LOAD_FAST | 1,920,480 | 16.7% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,920,480 | 33.3% |
| CALL_KW | 1,920,480 | 33.3% |
| CALL | 1,920,480 | 33.3% |
| CACHE | 480 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,841,440 | 66.7% |
| LOAD_GLOBAL_BUILTIN | 1,920,480 | 33.3% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,522,880 | 60.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,840,960 | 20.0% |
| CALL_ISINSTANCE | 3,840,960 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,443,360 | 70.0% |
| POP_JUMP_IF_TRUE | 5,761,440 | 30.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 480 | 100.0% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1920480 | 9.1% |
|          hit |     19204800 | 90.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 480 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 480 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

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

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5762100 | 42.9% |
|          hit |      7681980 | 57.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 1.3% |
| Failure | 1,540 | 98.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 520 | 33.8% |
| class mutable | 480 | 31.2% |
| code complex parameters | 480 | 31.2% |
| cfunc noargs | 60 | 3.9% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

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

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         1180 | 100.0% |


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
| specialization.deferred |      3840980 | 12.5% |
|          hit |     26886820 | 87.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 4.0% |
| Failure | 960 | 96.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 480 | 50.0% |
| method | 480 | 50.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     24966400 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
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

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         1920 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 107,556,560 | 46.3% |
| Not specialized | 44,175,120 | 19.0% |
| Specialized | 80,663,760 | 34.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 5,762,100 | 50.0% |
| LOAD_ATTR | 3,840,980 | 33.3% |
| TO_BOOL | 1,920,480 | 16.7% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| UNARY_NEGATIVE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 480 | 0.0% |
| Calls to Python functions inlined | 5,761,500 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 480 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 480 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 480 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 5,761,980 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 15,363,940 | 20.4% |
| Frees to freelist | 15,363,900 |  |
| Allocations | 59,875,860 | 79.6% |
| Allocations to 512 bytes | 59,875,860 | 79.6% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 59,875,820 |  |
| New values | 0 |  |
| Interpreter increfs | 78,748,280 | 50.3% |
| Interpreter decrefs | 94,109,360 | 41.2% |
| Increfs | 77,783,860 | 49.7% |
| Decrefs | 134,541,520 | 58.8% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 1,920,980 |  |
| Method cache misses | 0 |  |
| Method cache collisions | 0 |  |
| Method cache dunder hits | 7,682,400 |  |
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
| Optimization attempts | 20 |  |
| Traces created | 20 | 100.0% |
| Traces executed | 0 |  |
| Uops executed | 0 | 0 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
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
| <= 16 | 20 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 100.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|


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
Stats gathered on: 2023-10-11
