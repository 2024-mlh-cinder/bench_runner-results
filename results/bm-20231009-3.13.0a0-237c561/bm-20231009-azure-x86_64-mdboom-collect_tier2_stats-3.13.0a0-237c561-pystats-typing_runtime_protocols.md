
# Pystats results

- benchmark: typing_runtime_protocols
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_GLOBAL_MODULE | 41,579,224 | 13.0% | 13.0% |  |
| LOAD_FAST | 40,164,048 | 12.5% | 25.5% |  |
| CALL | 20,858,875 | 6.5% | 32.0% |  |
| STORE_FAST | 19,720,008 | 6.2% | 38.2% |  |
| LOAD_GLOBAL_BUILTIN | 17,649,060 | 5.5% | 43.7% |  |
| IS_OP | 16,396,800 | 5.1% | 48.8% |  |
| POP_JUMP_IF_FALSE | 15,255,552 | 4.8% | 53.5% |  |
| LOAD_FAST_LOAD_FAST | 15,014,760 | 4.7% | 58.2% |  |
| POP_JUMP_IF_TRUE | 14,813,184 | 4.6% | 62.8% |  |
| RESUME_CHECK | 12,887,460 | 4.0% | 66.9% |  |
| RETURN_VALUE | 12,249,720 | 3.8% | 70.7% |  |
| LOAD_CONST | 9,766,488 | 3.0% | 73.7% |  |
| LOAD_ATTR | 7,929,332 | 2.5% | 76.2% |  |
| CALL_PY_EXACT_ARGS | 7,114,752 | 2.2% | 78.4% |  |
| CONTAINS_OP | 6,299,136 | 2.0% | 80.4% |  |
| CALL_BUILTIN_FAST | 5,990,700 | 1.9% | 82.2% |  |
| TO_BOOL_BOOL | 5,990,400 | 1.9% | 84.1% |  |
| ENTER_EXECUTOR | 4,766,928 | 1.5% | 85.6% |  |
| NOP | 3,557,436 | 1.1% | 86.7% |  |
| CALL_TYPE_1 | 3,557,376 | 1.1% | 87.8% |  |
| GET_ITER | 3,314,988 | 1.0% | 88.9% |  |
| POP_TOP | 2,857,380 | 0.9% | 89.7% |  |
| INTERPRETER_EXIT | 1,997,100 | 0.6% | 90.4% |  |
| RETURN_CONST | 1,997,100 | 0.6% | 91.0% |  |
| LOAD_DEREF | 1,996,980 | 0.6% | 91.6% |  |
| COPY_FREE_VARS | 1,996,860 | 0.6% | 92.2% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 0.6% | 92.9% |  |
| LOAD_SUPER_ATTR_METHOD | 1,996,800 | 0.6% | 93.5% |  |
| FOR_ITER | 1,933,148 | 0.6% | 94.1% |  |
| PUSH_NULL | 1,779,108 | 0.6% | 94.6% |  |
| FOR_ITER_TUPLE | 1,778,808 | 0.6% | 95.2% |  |
| BUILD_MAP | 1,778,688 | 0.6% | 95.8% |  |
| JUMP_FORWARD | 1,778,688 | 0.6% | 96.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,778,688 | 0.6% | 96.9% |  |
| CALL_PY_WITH_DEFAULTS | 1,778,688 | 0.6% | 97.4% |  |
| LOAD_ATTR_CLASS | 1,778,688 | 0.6% | 98.0% |  |
| CHECK_EXC_MATCH | 1,382,400 | 0.4% | 98.4% |  |
| POP_EXCEPT | 1,382,400 | 0.4% | 98.8% |  |
| PUSH_EXC_INFO | 1,382,400 | 0.4% | 99.3% |  |
| RAISE_VARARGS | 1,382,400 | 0.4% | 99.7% |  |
| JUMP_BACKWARD | 396,668 | 0.1% | 99.8% |  |
| POP_JUMP_IF_NONE | 396,288 | 0.1% | 99.9% |  |
| SWAP | 92,280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 92,200 | 0.0% | 100.0% |  |
| LIST_APPEND | 780 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 460 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% | 100.0% |  |
| BUILD_LIST | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 120 | 0.0% | 100.0% |  |
| STORE_ATTR | 80 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 60 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_MODULE IS_OP | 15,014,400 | 4.7% | 4.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 10,493,952 | 3.3% | 8.0% |
| IS_OP POP_JUMP_IF_FALSE | 10,097,664 | 3.1% | 11.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 9,111,592 | 2.8% | 13.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 8,933,436 | 2.8% | 16.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 8,893,440 | 2.8% | 19.5% |
| LOAD_FAST CALL | 8,497,172 | 2.7% | 22.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,114,752 | 2.2% | 24.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,114,752 | 2.2% | 26.6% |
| CALL CALL | 6,304,295 | 2.0% | 28.6% |
| CALL RETURN_VALUE | 6,299,136 | 2.0% | 30.5% |
| IS_OP POP_JUMP_IF_TRUE | 6,299,136 | 2.0% | 32.5% |
| LOAD_FAST LOAD_CONST | 5,772,288 | 1.8% | 34.3% |
| RETURN_VALUE STORE_FAST | 5,732,352 | 1.8% | 36.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 5,554,176 | 1.7% | 37.8% |
| STORE_FAST LOAD_FAST | 5,489,904 | 1.7% | 39.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 5,336,464 | 1.7% | 41.2% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 4,520,468 | 1.4% | 42.6% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 4,520,448 | 1.4% | 44.0% |
| LOAD_ATTR CONTAINS_OP | 4,520,448 | 1.4% | 45.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR | 4,520,448 | 1.4% | 46.8% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 4,520,448 | 1.4% | 48.2% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 4,428,288 | 1.4% | 49.6% |
| LOAD_CONST CALL_BUILTIN_FAST | 3,993,900 | 1.2% | 50.9% |
| LOAD_CONST LOAD_CONST | 3,993,600 | 1.2% | 52.1% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 3,993,600 | 1.2% | 53.4% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 3,993,600 | 1.2% | 54.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 3,993,600 | 1.2% | 55.8% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 3,558,016 | 1.1% | 57.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 3,557,456 | 1.1% | 58.1% |
| LOAD_FAST CALL_TYPE_1 | 3,557,376 | 1.1% | 59.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 3,557,376 | 1.1% | 60.3% |
| STORE_FAST NOP | 3,557,376 | 1.1% | 61.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 3,379,200 | 1.1% | 62.5% |
| CALL STORE_FAST | 3,314,748 | 1.0% | 63.5% |
| ENTER_EXECUTOR CALL | 2,742,420 | 0.9% | 64.3% |
| RETURN_CONST INTERPRETER_EXIT | 1,997,100 | 0.6% | 65.0% |
| COPY_FREE_VARS RESUME_CHECK | 1,996,860 | 0.6% | 65.6% |
| CACHE COPY_FREE_VARS | 1,996,800 | 0.6% | 66.2% |
| RETURN_VALUE TO_BOOL_BOOL | 1,996,800 | 0.6% | 66.8% |
| LOAD_DEREF LOAD_FAST | 1,996,800 | 0.6% | 67.5% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 0.6% | 68.1% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,996,800 | 0.6% | 68.7% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 1,996,800 | 0.6% | 69.3% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 1,996,800 | 0.6% | 69.9% |
| CALL_BUILTIN_FAST RETURN_VALUE | 1,996,800 | 0.6% | 70.6% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,996,800 | 0.6% | 71.2% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST | 1,996,800 | 0.6% | 71.8% |
| RESUME_CHECK LOAD_FAST | 1,996,800 | 0.6% | 72.4% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 1,996,800 | 0.6% | 73.1% |
| LOAD_ATTR LOAD_FAST | 1,870,848 | 0.6% | 73.6% |
| FOR_ITER STORE_FAST | 1,778,988 | 0.6% | 74.2% |
| LOAD_FAST PUSH_NULL | 1,778,808 | 0.6% | 74.8% |
| FOR_ITER_TUPLE STORE_FAST | 1,778,808 | 0.6% | 75.3% |
| GET_ITER FOR_ITER_TUPLE | 1,778,688 | 0.6% | 75.9% |
| NOP LOAD_FAST | 1,778,688 | 0.6% | 76.4% |
| NOP LOAD_GLOBAL_BUILTIN | 1,778,688 | 0.6% | 77.0% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,778,688 | 0.6% | 77.5% |
| BUILD_MAP STORE_FAST | 1,778,688 | 0.6% | 78.1% |
| CALL GET_ITER | 1,778,688 | 0.6% | 78.6% |
| CALL CONTAINS_OP | 1,778,688 | 0.6% | 79.2% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,778,688 | 0.6% | 79.7% |
| JUMP_FORWARD LOAD_GLOBAL_MODULE | 1,778,688 | 0.6% | 80.3% |
| LOAD_CONST CALL | 1,778,688 | 0.6% | 80.9% |
| LOAD_FAST STORE_FAST | 1,778,688 | 0.6% | 81.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,778,688 | 0.6% | 82.0% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 1,778,688 | 0.6% | 82.5% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 1,778,688 | 0.6% | 83.1% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_MODULE | 1,778,688 | 0.6% | 83.6% |
| STORE_FAST JUMP_FORWARD | 1,778,688 | 0.6% | 84.2% |
| CALL_METHOD_DESCRIPTOR_FAST RETURN_VALUE | 1,778,688 | 0.6% | 84.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,778,688 | 0.6% | 85.3% |
| CALL_TYPE_1 STORE_FAST | 1,778,688 | 0.6% | 85.8% |
| CALL_TYPE_1 CALL_PY_EXACT_ARGS | 1,778,688 | 0.6% | 86.4% |
| LOAD_ATTR_CLASS LOAD_FAST_LOAD_FAST | 1,778,688 | 0.6% | 87.0% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 1,778,688 | 0.6% | 87.5% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR_CLASS | 1,778,688 | 0.6% | 88.1% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 1,778,688 | 0.6% | 88.6% |
| LOAD_GLOBAL_MODULE STORE_FAST | 1,778,688 | 0.6% | 89.2% |
| LOAD_GLOBAL_MODULE CALL_METHOD_DESCRIPTOR_FAST | 1,778,688 | 0.6% | 89.7% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 1,778,688 | 0.6% | 90.3% |
| RESUME_CHECK BUILD_MAP | 1,778,688 | 0.6% | 90.8% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 1,686,568 | 0.5% | 91.4% |
| LOAD_GLOBAL_MODULE RETURN_VALUE | 1,686,528 | 0.5% | 91.9% |
| LOAD_FAST LOAD_ATTR | 1,628,160 | 0.5% | 92.4% |
| GET_ITER FOR_ITER | 1,536,060 | 0.5% | 92.9% |
| LOAD_ATTR GET_ITER | 1,536,000 | 0.5% | 93.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,536,000 | 0.5% | 93.8% |
| LOAD_GLOBAL_MODULE CALL | 1,536,000 | 0.5% | 94.3% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 1,382,400 | 0.4% | 94.7% |
| POP_EXCEPT POP_TOP | 1,382,400 | 0.4% | 95.2% |
| POP_TOP POP_EXCEPT | 1,382,400 | 0.4% | 95.6% |
| POP_TOP RETURN_CONST | 1,382,400 | 0.4% | 96.0% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 1,382,400 | 0.4% | 96.5% |
| CALL RAISE_VARARGS | 1,382,400 | 0.4% | 96.9% |
| LOAD_FAST_LOAD_FAST IS_OP | 1,382,400 | 0.4% | 97.3% |
| POP_JUMP_IF_FALSE POP_TOP | 1,382,400 | 0.4% | 97.8% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,382,400 | 0.4% | 98.2% |
| RAISE_VARARGS PUSH_EXC_INFO | 1,382,400 | 0.4% | 98.6% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 1,382,400 | 0.4% | 99.1% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 1,996,800 | 100.0% |
| RESUME_CHECK | 300 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,160 | 100.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 92,160 | 100.0% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,382,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,382,400 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,778,688 | 53.7% |
| LOAD_ATTR | 1,536,000 | 46.3% |
| LOAD_FAST | 120 | 0.0% |
| BUILD_TUPLE | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 1,778,688 | 53.7% |
| FOR_ITER | 1,536,060 | 46.3% |
| FOR_ITER_LIST | 120 | 0.0% |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% |
| FOR_ITER_RANGE | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,997,100 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,557,376 | 100.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,778,688 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 1,778,688 | 50.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,382,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,382,400 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 1,382,400 | 48.4% |
| POP_JUMP_IF_FALSE | 1,382,400 | 48.4% |
| SWAP | 92,160 | 3.2% |
| CALL_BUILTIN_FAST | 300 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 1,382,400 | 48.4% |
| RETURN_CONST | 1,382,400 | 48.4% |
| RETURN_VALUE | 92,160 | 3.2% |
| JUMP_BACKWARD | 300 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RAISE_VARARGS | 1,382,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,382,400 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,778,808 | 100.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,778,688 | 100.0% |
| CALL | 300 | 0.0% |
| LOAD_FAST | 120 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 6,299,136 | 51.4% |
| CALL_BUILTIN_FAST | 1,996,800 | 16.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,778,688 | 14.5% |
| LOAD_GLOBAL_MODULE | 1,686,528 | 13.8% |
| LOAD_FAST | 396,288 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,732,352 | 46.8% |
| LOAD_GLOBAL_MODULE | 4,520,468 | 36.9% |
| TO_BOOL_BOOL | 1,996,800 | 16.3% |
| RETURN_VALUE | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


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

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 33.3% |
| SWAP | 60 | 33.3% |
| LOAD_GLOBAL_MODULE | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 33.3% |
| STORE_FAST | 60 | 33.3% |
| SWAP | 60 | 33.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,778,688 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,778,688 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,497,172 | 40.7% |
| CALL | 6,304,295 | 30.2% |
| ENTER_EXECUTOR | 2,742,420 | 13.1% |
| LOAD_CONST | 1,778,688 | 8.5% |
| LOAD_GLOBAL_MODULE | 1,536,000 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 6,304,295 | 30.2% |
| RETURN_VALUE | 6,299,136 | 30.2% |
| STORE_FAST | 3,314,748 | 15.9% |
| GET_ITER | 1,778,688 | 8.5% |
| CONTAINS_OP | 1,778,688 | 8.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 50.0% |
| RESUME_CHECK | 60 | 50.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,520,448 | 71.8% |
| CALL | 1,778,688 | 28.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,520,448 | 71.8% |
| POP_JUMP_IF_FALSE | 1,778,688 | 28.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 1,996,800 | 100.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,996,860 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,428,288 | 92.9% |
| ENTER_EXECUTOR | 337,860 | 7.1% |
| LIST_APPEND | 700 | 0.0% |
| POP_TOP | 60 | 0.0% |
| JUMP_BACKWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,742,420 | 57.5% |
| LOAD_GLOBAL_MODULE | 1,686,568 | 35.4% |
| ENTER_EXECUTOR | 337,860 | 7.1% |
| STORE_FAST | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,536,060 | 79.5% |
| JUMP_BACKWARD | 396,588 | 20.5% |
| FOR_ITER | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,778,988 | 92.0% |
| RETURN_CONST | 153,660 | 7.9% |
| FOR_ITER | 500 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 15,014,400 | 91.6% |
| LOAD_FAST_LOAD_FAST | 1,382,400 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,097,664 | 61.6% |
| POP_JUMP_IF_TRUE | 6,299,136 | 38.4% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 396,288 | 99.9% |
| POP_TOP | 300 | 0.1% |
| LIST_APPEND | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 396,588 | 100.0% |
| FOR_ITER_TUPLE | 60 | 0.0% |
| ENTER_EXECUTOR | 20 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,778,688 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,778,688 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 700 | 89.7% |
| JUMP_BACKWARD | 80 | 10.3% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,520,448 | 57.0% |
| LOAD_GLOBAL_BUILTIN | 1,778,688 | 22.4% |
| LOAD_FAST | 1,628,160 | 20.5% |
| LOAD_ATTR | 1,956 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 4,520,448 | 57.0% |
| LOAD_FAST | 1,870,848 | 23.6% |
| GET_ITER | 1,536,000 | 19.4% |
| LOAD_ATTR | 1,956 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,772,288 | 59.1% |
| LOAD_CONST | 3,993,600 | 40.9% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |
| RESUME_CHECK | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 3,993,900 | 40.9% |
| LOAD_CONST | 3,993,600 | 40.9% |
| CALL | 1,778,688 | 18.2% |
| LOAD_FAST | 240 | 0.0% |
| GET_ITER | 60 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,996,800 | 100.0% |
| NOP | 60 | 0.0% |
| BUILD_LIST | 60 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,996,800 | 100.0% |
| PUSH_NULL | 120 | 0.0% |
| LIST_EXTEND | 60 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 8,933,436 | 22.2% |
| LOAD_GLOBAL_MODULE | 8,893,440 | 22.1% |
| POP_JUMP_IF_FALSE | 7,114,752 | 17.7% |
| STORE_FAST | 5,489,904 | 13.7% |
| LOAD_DEREF | 1,996,800 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 10,493,952 | 26.1% |
| CALL | 8,497,172 | 21.2% |
| LOAD_CONST | 5,772,288 | 14.4% |
| CALL_TYPE_1 | 3,557,376 | 8.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 5.0% |


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
| LOAD_GLOBAL_MODULE | 5,554,176 | 37.0% |
| POP_JUMP_IF_TRUE | 4,520,448 | 30.1% |
| PUSH_NULL | 1,778,688 | 11.8% |
| LOAD_ATTR_CLASS | 1,778,688 | 11.8% |
| POP_JUMP_IF_FALSE | 1,382,400 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,520,448 | 30.1% |
| CALL_PY_EXACT_ARGS | 3,557,376 | 23.7% |
| CALL_BUILTIN_FAST | 1,996,800 | 13.3% |
| CALL_PY_WITH_DEFAULTS | 1,778,688 | 11.8% |
| LOAD_GLOBAL_MODULE | 1,778,688 | 11.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 320 | 69.6% |
| STORE_FAST | 60 | 13.0% |
| RETURN_VALUE | 40 | 8.7% |
| ENTER_EXECUTOR | 20 | 4.3% |
| RESUME_CHECK | 20 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 420 | 91.3% |
| LOAD_ATTR | 20 | 4.3% |
| LOAD_GLOBAL_BUILTIN | 20 | 4.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 10,097,664 | 66.2% |
| TO_BOOL_BOOL | 1,996,800 | 13.1% |
| CONTAINS_OP | 1,778,688 | 11.7% |
| CHECK_EXC_MATCH | 1,382,400 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,114,752 | 46.6% |
| LOAD_GLOBAL_BUILTIN | 3,379,200 | 22.2% |
| LOAD_GLOBAL_MODULE | 1,536,000 | 10.1% |
| POP_TOP | 1,382,400 | 9.1% |
| LOAD_FAST_LOAD_FAST | 1,382,400 | 9.1% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 396,288 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 396,288 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 6,299,136 | 42.5% |
| CONTAINS_OP | 4,520,448 | 30.5% |
| TO_BOOL_BOOL | 3,993,600 | 27.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,520,448 | 30.5% |
| ENTER_EXECUTOR | 4,428,288 | 29.9% |
| LOAD_GLOBAL_BUILTIN | 3,993,600 | 27.0% |
| LOAD_GLOBAL_MODULE | 1,778,688 | 12.0% |
| LOAD_FAST | 92,160 | 0.6% |


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,382,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 1,382,400 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,382,400 | 69.2% |
| POP_JUMP_IF_FALSE | 460,800 | 23.1% |
| FOR_ITER | 153,660 | 7.7% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,997,100 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 80 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,732,352 | 29.1% |
| CALL | 3,314,748 | 16.8% |
| FOR_ITER | 1,778,988 | 9.0% |
| FOR_ITER_TUPLE | 1,778,808 | 9.0% |
| BUILD_MAP | 1,778,688 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,489,904 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 5,336,464 | 27.1% |
| LOAD_GLOBAL_MODULE | 3,557,456 | 18.0% |
| NOP | 3,557,376 | 18.0% |
| JUMP_FORWARD | 1,778,688 | 9.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 92,160 | 99.9% |
| BUILD_LIST | 60 | 0.1% |
| LOAD_FAST_AND_CLEAR | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 92,160 | 99.9% |
| BUILD_LIST | 60 | 0.1% |
| FOR_ITER_TUPLE | 60 | 0.1% |


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
| RETURN_VALUE | 60 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,996,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,996,800 | 100.0% |


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
| GET_ITER | 60 | 100.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,993,900 | 66.7% |
| LOAD_FAST_LOAD_FAST | 1,996,800 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,993,600 | 66.7% |
| RETURN_VALUE | 1,996,800 | 33.3% |
| POP_TOP | 300 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,778,688 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,778,688 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,557,376 | 50.0% |
| LOAD_FAST | 1,778,688 | 25.0% |
| CALL_TYPE_1 | 1,778,688 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,114,752 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,778,688 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,778,688 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,557,376 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,778,688 | 50.0% |
| CALL_PY_EXACT_ARGS | 1,778,688 | 50.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 100.0% |


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

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,778,688 | 100.0% |
| JUMP_BACKWARD | 60 | 0.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,778,808 | 100.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,778,688 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,778,688 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 100 | 62.5% |
| LOAD_ATTR | 60 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,336,464 | 30.2% |
| POP_JUMP_IF_TRUE | 3,993,600 | 22.6% |
| POP_JUMP_IF_FALSE | 3,379,200 | 19.1% |
| NOP | 1,778,688 | 10.1% |
| LOAD_GLOBAL_MODULE | 1,778,688 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,933,436 | 50.6% |
| LOAD_DEREF | 1,996,800 | 11.3% |
| LOAD_ATTR | 1,778,688 | 10.1% |
| LOAD_ATTR_CLASS | 1,778,688 | 10.1% |
| LOAD_GLOBAL_MODULE | 1,778,688 | 10.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,493,952 | 25.2% |
| RESUME_CHECK | 9,111,592 | 21.9% |
| RETURN_VALUE | 4,520,468 | 10.9% |
| LOAD_GLOBAL_MODULE | 3,558,016 | 8.6% |
| STORE_FAST | 3,557,456 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 15,014,400 | 36.1% |
| LOAD_FAST | 8,893,440 | 21.4% |
| LOAD_FAST_LOAD_FAST | 5,554,176 | 13.4% |
| LOAD_GLOBAL_MODULE | 3,558,016 | 8.6% |
| STORE_FAST | 1,778,688 | 4.3% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,996,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,996,800 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 7,114,752 | 55.2% |
| COPY_FREE_VARS | 1,996,860 | 15.5% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 15.5% |
| CALL_PY_WITH_DEFAULTS | 1,778,688 | 13.8% |
| CACHE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,111,592 | 70.7% |
| LOAD_FAST | 1,996,800 | 15.5% |
| BUILD_MAP | 1,778,688 | 13.8% |
| LOAD_CONST | 300 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 66.7% |
| STORE_ATTR | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 3,993,600 | 66.7% |
| RETURN_VALUE | 1,996,800 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 3,993,600 | 66.7% |
| POP_JUMP_IF_FALSE | 1,996,800 | 33.3% |


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
|          hit | 60 | 75.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 92,160 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 40 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 40 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20,853,696 | 46.3% |
|          hit | 24,213,924 | 53.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.4% |
| Failure | 5,159 | 99.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method wrapper | 2,394 | 46.4% |
| other | 1,916 | 37.1% |
| operator wrapper | 429 | 8.3% |
| class no vectorcall | 340 | 6.6% |
| cfunc noargs | 60 | 1.2% |
| init not python | 20 | 0.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,932,648 | 52.1% |
|          hit | 1,778,988 | 47.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 500 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| set | 480 | 96.0% |
| ascii string | 20 | 4.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,927,316 | 81.7% |
|          hit | 1,778,848 | 18.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.0% |
| Failure | 1,956 | 97.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 1,956 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 59,228,284 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 440 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,996,800 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>


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
|          hit | 240 | 75.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 5,990,400 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 153,055,416 | 47.7% |
| Not specialized | 61,675,807 | 19.2% |
| Specialized | 105,878,204 | 33.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 20,853,696 | 67.7% |
| LOAD_ATTR | 7,927,316 | 25.7% |
| FOR_ITER | 1,932,648 | 6.3% |
| BINARY_SUBSCR | 92,160 | 0.3% |
| LOAD_GLOBAL | 20 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| CACHE | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 1,997,100 | 15.5% |
| Calls to Python functions inlined | 10,890,360 | 84.5% |
| Calls via PyEval_EvalFrame (total) | 1,997,100 | 15.5% |
| Calls via PyEval_EvalFrame (vector) | 1,997,100 | 15.5% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,997,100 | 15.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 2,764,800 | 21.5% |
| Frames pushed | 15,629,220 | 121.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 22,875,272 | 54.6% |
| Frees to freelist | 22,875,252 |  |
| Allocations | 19,034,556 | 45.4% |
| Allocations to 512 bytes | 19,034,556 | 45.4% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 19,034,568 |  |
| New values | 780 |  |
| Interpreter increfs | 141,566,152 | 52.7% |
| Interpreter decrefs | 170,098,248 | 54.8% |
| Increfs | 127,054,646 | 47.3% |
| Decrefs | 140,431,428 | 45.2% |
| Materialize dict (on request) | 780 | 100.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 11,919,574 |  |
| Method cache misses | 61,626 |  |
| Method cache collisions | 123,135 |  |
| Method cache dunder hits | 16,954,272 |  |
| Method cache dunder misses | 61,610 |  |


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
| Optimization attempts | 23,349 |  |
| Traces created | 20 | 0.1% |
| Traces executed | 4,766,928 |  |
| Uops executed | 144,667,356 | 30.35 |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 23,329 | 116,645.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 100.0% |


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
| <= 16 | 20 | 100.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,717,368 | 36.0% |
| <= 16 | 660 | 0.0% |
| <= 32 | 122,880 | 2.6% |
| <= 64 | 2,772,420 | 58.2% |
| <= 128 | 0 | 0.0% |
| <= 256 | 153,600 | 3.2% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 39,516,216 | 27.3% | 27.3% |  |
| _GUARD_GLOBALS_VERSION | 12,963,780 | 9.0% | 36.3% |  |
| LOAD_FAST | 9,661,860 | 6.7% | 43.0% |  |
| _LOAD_GLOBAL_MODULE | 8,225,280 | 5.7% | 48.6% |  |
| _POP_JUMP_IF_TRUE | 6,794,328 | 4.7% | 53.3% |  |
| STORE_FAST | 4,923,360 | 3.4% | 56.7% |  |
| _EXIT_TRACE | 4,766,928 | 3.3% | 60.0% |  |
| _GUARD_BUILTINS_VERSION | 4,738,500 | 3.3% | 63.3% |  |
| _LOAD_GLOBAL_BUILTINS | 4,738,500 | 3.3% | 66.6% |  |
| _ITER_CHECK_TUPLE | 4,429,008 | 3.1% | 69.6% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 4,429,008 | 3.1% | 72.7% |  |
| POP_TOP | 3,867,708 | 2.7% | 75.4% |  |
| _ITER_NEXT_TUPLE | 2,742,420 | 1.9% | 77.3% |  |
| CALL_TYPE_1 | 2,741,760 | 1.9% | 79.2% |  |
| RESUME_CHECK | 2,741,760 | 1.9% | 81.1% |  |
| _CHECK_PEP_523 | 2,741,760 | 1.9% | 83.0% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 2,741,760 | 1.9% | 84.9% |  |
| _CHECK_STACK_SPACE | 2,741,760 | 1.9% | 86.8% |  |
| _INIT_CALL_PY_EXACT_ARGS | 2,741,760 | 1.9% | 88.6% |  |
| _PUSH_FRAME | 2,741,760 | 1.9% | 90.5% |  |
| _SAVE_CURRENT_IP | 2,741,760 | 1.9% | 92.4% |  |
| _ITER_CHECK_LIST | 2,334,600 | 1.6% | 94.1% |  |
| _IS_ITER_EXHAUSTED_LIST | 2,334,600 | 1.6% | 95.7% |  |
| _ITER_NEXT_LIST | 2,150,280 | 1.5% | 97.2% |  |
| CALL_ISINSTANCE | 1,996,740 | 1.4% | 98.5% |  |
| _JUMP_TO_TOP | 1,843,200 | 1.3% | 99.8% |  |
| GET_ITER | 184,200 | 0.1% | 99.9% |  |
| _ITER_CHECK_RANGE | 30,720 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_RANGE | 30,720 | 0.0% | 100.0% |  |
| _ITER_NEXT_RANGE | 30,660 | 0.0% | 100.0% |  |
| PUSH_NULL | 660 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 23,329 |
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
Stats gathered on: 2023-10-09
