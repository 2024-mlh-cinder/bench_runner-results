
# Pystats results

- benchmark: typing_runtime_protocols
- fork: brandtbucher
- ref: justin
- commit hash: 07fb485
- commit date: 2023-10-11T15:47:19+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_GLOBAL_MODULE | 41,831,128 | 13.0% | 13.0% |  |
| LOAD_FAST | 40,360,656 | 12.5% | 25.5% |  |
| CALL | 21,006,375 | 6.5% | 32.0% |  |
| STORE_FAST | 19,855,176 | 6.2% | 38.2% |  |
| LOAD_GLOBAL_BUILTIN | 17,710,500 | 5.5% | 43.7% |  |
| IS_OP | 16,488,960 | 5.1% | 48.8% |  |
| POP_JUMP_IF_FALSE | 15,304,704 | 4.7% | 53.5% |  |
| LOAD_FAST_LOAD_FAST | 15,106,920 | 4.7% | 58.2% |  |
| POP_JUMP_IF_TRUE | 14,911,488 | 4.6% | 62.9% |  |
| RESUME_CHECK | 12,948,900 | 4.0% | 66.9% |  |
| RETURN_VALUE | 12,341,880 | 3.8% | 70.7% |  |
| LOAD_CONST | 9,778,776 | 3.0% | 73.7% |  |
| LOAD_ATTR | 7,984,644 | 2.5% | 76.2% |  |
| CALL_PY_EXACT_ARGS | 7,163,904 | 2.2% | 78.4% |  |
| CONTAINS_OP | 6,354,432 | 2.0% | 80.4% |  |
| CALL_BUILTIN_FAST | 5,990,700 | 1.9% | 82.3% |  |
| TO_BOOL_BOOL | 5,990,400 | 1.9% | 84.1% |  |
| ENTER_EXECUTOR | 4,809,936 | 1.5% | 85.6% |  |
| NOP | 3,582,012 | 1.1% | 86.7% |  |
| CALL_TYPE_1 | 3,581,952 | 1.1% | 87.8% |  |
| GET_ITER | 3,327,276 | 1.0% | 88.9% |  |
| POP_TOP | 2,857,380 | 0.9% | 89.8% |  |
| RETURN_CONST | 1,997,100 | 0.6% | 90.4% |  |
| INTERPRETER_EXIT | 1,997,100 | 0.6% | 91.0% |  |
| LOAD_DEREF | 1,996,980 | 0.6% | 91.6% |  |
| COPY_FREE_VARS | 1,996,860 | 0.6% | 92.2% |  |
| LOAD_SUPER_ATTR_METHOD | 1,996,800 | 0.6% | 92.9% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 0.6% | 93.5% |  |
| FOR_ITER | 1,945,436 | 0.6% | 94.1% |  |
| PUSH_NULL | 1,791,396 | 0.6% | 94.6% |  |
| FOR_ITER_TUPLE | 1,791,096 | 0.6% | 95.2% |  |
| LOAD_ATTR_CLASS | 1,790,976 | 0.6% | 95.7% |  |
| JUMP_FORWARD | 1,790,976 | 0.6% | 96.3% |  |
| CALL_PY_WITH_DEFAULTS | 1,790,976 | 0.6% | 96.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,790,976 | 0.6% | 97.4% |  |
| BUILD_MAP | 1,790,976 | 0.6% | 98.0% |  |
| RAISE_VARARGS | 1,382,400 | 0.4% | 98.4% |  |
| PUSH_EXC_INFO | 1,382,400 | 0.4% | 98.8% |  |
| POP_EXCEPT | 1,382,400 | 0.4% | 99.3% |  |
| CHECK_EXC_MATCH | 1,382,400 | 0.4% | 99.7% |  |
| JUMP_BACKWARD | 408,956 | 0.1% | 99.8% |  |
| POP_JUMP_IF_NONE | 408,576 | 0.1% | 99.9% |  |
| SWAP | 92,280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 92,200 | 0.0% | 100.0% |  |
| LIST_APPEND | 780 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 460 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% | 100.0% |  |
| BUILD_LIST | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| STORE_ATTR | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_MODULE IS_OP | 15,106,560 | 4.7% | 4.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 10,543,104 | 3.3% | 8.0% |
| IS_OP POP_JUMP_IF_FALSE | 10,134,528 | 3.1% | 11.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 9,160,744 | 2.8% | 13.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 8,958,012 | 2.8% | 16.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 8,954,880 | 2.8% | 19.5% |
| LOAD_FAST CALL | 8,546,324 | 2.7% | 22.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,163,904 | 2.2% | 24.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,163,904 | 2.2% | 26.6% |
| CALL CALL | 6,359,635 | 2.0% | 28.6% |
| IS_OP POP_JUMP_IF_TRUE | 6,354,432 | 2.0% | 30.5% |
| CALL RETURN_VALUE | 6,354,432 | 2.0% | 32.5% |
| LOAD_FAST LOAD_CONST | 5,784,576 | 1.8% | 34.3% |
| RETURN_VALUE STORE_FAST | 5,781,504 | 1.8% | 36.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 5,578,752 | 1.7% | 37.8% |
| STORE_FAST LOAD_FAST | 5,526,768 | 1.7% | 39.6% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 5,373,328 | 1.7% | 41.2% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 4,563,476 | 1.4% | 42.6% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 4,563,456 | 1.4% | 44.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR | 4,563,456 | 1.4% | 45.5% |
| LOAD_ATTR CONTAINS_OP | 4,563,456 | 1.4% | 46.9% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 4,563,456 | 1.4% | 48.3% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 4,471,296 | 1.4% | 49.7% |
| LOAD_CONST CALL_BUILTIN_FAST | 3,993,900 | 1.2% | 50.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 3,993,600 | 1.2% | 52.2% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 3,993,600 | 1.2% | 53.4% |
| LOAD_CONST LOAD_CONST | 3,993,600 | 1.2% | 54.6% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 3,993,600 | 1.2% | 55.9% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 3,582,592 | 1.1% | 57.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 3,582,032 | 1.1% | 58.1% |
| STORE_FAST NOP | 3,581,952 | 1.1% | 59.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 3,581,952 | 1.1% | 60.3% |
| LOAD_FAST CALL_TYPE_1 | 3,581,952 | 1.1% | 61.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 3,379,200 | 1.0% | 62.5% |
| CALL STORE_FAST | 3,327,036 | 1.0% | 63.5% |
| ENTER_EXECUTOR CALL | 2,773,140 | 0.9% | 64.4% |
| RETURN_CONST INTERPRETER_EXIT | 1,997,100 | 0.6% | 65.0% |
| COPY_FREE_VARS RESUME_CHECK | 1,996,860 | 0.6% | 65.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 1,996,800 | 0.6% | 66.2% |
| RETURN_VALUE TO_BOOL_BOOL | 1,996,800 | 0.6% | 66.9% |
| RESUME_CHECK LOAD_FAST | 1,996,800 | 0.6% | 67.5% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST | 1,996,800 | 0.6% | 68.1% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,996,800 | 0.6% | 68.7% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 1,996,800 | 0.6% | 69.3% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,996,800 | 0.6% | 70.0% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 0.6% | 70.6% |
| LOAD_DEREF LOAD_FAST | 1,996,800 | 0.6% | 71.2% |
| CALL_BUILTIN_FAST RETURN_VALUE | 1,996,800 | 0.6% | 71.8% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 1,996,800 | 0.6% | 72.4% |
| CACHE COPY_FREE_VARS | 1,996,800 | 0.6% | 73.1% |
| LOAD_ATTR LOAD_FAST | 1,883,136 | 0.6% | 73.6% |
| FOR_ITER STORE_FAST | 1,791,276 | 0.6% | 74.2% |
| LOAD_FAST PUSH_NULL | 1,791,096 | 0.6% | 74.8% |
| FOR_ITER_TUPLE STORE_FAST | 1,791,096 | 0.6% | 75.3% |
| STORE_FAST JUMP_FORWARD | 1,790,976 | 0.6% | 75.9% |
| RESUME_CHECK BUILD_MAP | 1,790,976 | 0.6% | 76.4% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,790,976 | 0.6% | 77.0% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_MODULE | 1,790,976 | 0.6% | 77.5% |
| NOP LOAD_GLOBAL_BUILTIN | 1,790,976 | 0.6% | 78.1% |
| NOP LOAD_FAST | 1,790,976 | 0.6% | 78.6% |
| LOAD_GLOBAL_MODULE STORE_FAST | 1,790,976 | 0.6% | 79.2% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 1,790,976 | 0.6% | 79.8% |
| LOAD_GLOBAL_MODULE CALL_METHOD_DESCRIPTOR_FAST | 1,790,976 | 0.6% | 80.3% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 1,790,976 | 0.6% | 80.9% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR_CLASS | 1,790,976 | 0.6% | 81.4% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 1,790,976 | 0.6% | 82.0% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 1,790,976 | 0.6% | 82.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 1,790,976 | 0.6% | 83.1% |
| LOAD_FAST STORE_FAST | 1,790,976 | 0.6% | 83.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,790,976 | 0.6% | 84.2% |
| LOAD_CONST CALL | 1,790,976 | 0.6% | 84.8% |
| LOAD_ATTR_CLASS LOAD_FAST_LOAD_FAST | 1,790,976 | 0.6% | 85.3% |
| JUMP_FORWARD LOAD_GLOBAL_MODULE | 1,790,976 | 0.6% | 85.9% |
| GET_ITER FOR_ITER_TUPLE | 1,790,976 | 0.6% | 86.4% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,790,976 | 0.6% | 87.0% |
| CALL_TYPE_1 STORE_FAST | 1,790,976 | 0.6% | 87.5% |
| CALL_TYPE_1 CALL_PY_EXACT_ARGS | 1,790,976 | 0.6% | 88.1% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,790,976 | 0.6% | 88.6% |
| CALL_METHOD_DESCRIPTOR_FAST RETURN_VALUE | 1,790,976 | 0.6% | 89.2% |
| CALL GET_ITER | 1,790,976 | 0.6% | 89.8% |
| CALL CONTAINS_OP | 1,790,976 | 0.6% | 90.3% |
| BUILD_MAP STORE_FAST | 1,790,976 | 0.6% | 90.9% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 1,698,856 | 0.5% | 91.4% |
| LOAD_GLOBAL_MODULE RETURN_VALUE | 1,698,816 | 0.5% | 91.9% |
| LOAD_FAST LOAD_ATTR | 1,628,160 | 0.5% | 92.4% |
| GET_ITER FOR_ITER | 1,536,060 | 0.5% | 92.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,536,000 | 0.5% | 93.4% |
| LOAD_GLOBAL_MODULE CALL | 1,536,000 | 0.5% | 93.9% |
| LOAD_ATTR GET_ITER | 1,536,000 | 0.5% | 94.3% |
| RAISE_VARARGS PUSH_EXC_INFO | 1,382,400 | 0.4% | 94.8% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 1,382,400 | 0.4% | 95.2% |
| POP_TOP RETURN_CONST | 1,382,400 | 0.4% | 95.6% |
| POP_TOP POP_EXCEPT | 1,382,400 | 0.4% | 96.0% |
| POP_JUMP_IF_FALSE POP_TOP | 1,382,400 | 0.4% | 96.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,382,400 | 0.4% | 96.9% |
| POP_EXCEPT POP_TOP | 1,382,400 | 0.4% | 97.3% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 1,382,400 | 0.4% | 97.8% |
| LOAD_FAST_LOAD_FAST IS_OP | 1,382,400 | 0.4% | 98.2% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 1,382,400 | 0.4% | 98.6% |
| CALL RAISE_VARARGS | 1,382,400 | 0.4% | 99.1% |


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
| CALL | 1,790,976 | 53.8% |
| LOAD_ATTR | 1,536,000 | 46.2% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| CALL_BUILTIN_CLASS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 1,790,976 | 53.8% |
| FOR_ITER | 1,536,060 | 46.2% |
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

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,581,952 | 100.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,790,976 | 50.0% |
| LOAD_FAST | 1,790,976 | 50.0% |
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
| POP_JUMP_IF_FALSE | 1,382,400 | 48.4% |
| POP_EXCEPT | 1,382,400 | 48.4% |
| SWAP | 92,160 | 3.2% |
| CALL_BUILTIN_FAST | 300 | 0.0% |
| CALL_ISINSTANCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,382,400 | 48.4% |
| POP_EXCEPT | 1,382,400 | 48.4% |
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
| LOAD_FAST | 1,791,096 | 100.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,790,976 | 100.0% |
| CALL | 300 | 0.0% |
| LOAD_FAST | 120 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 6,354,432 | 51.5% |
| CALL_BUILTIN_FAST | 1,996,800 | 16.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,790,976 | 14.5% |
| LOAD_GLOBAL_MODULE | 1,698,816 | 13.8% |
| LOAD_FAST | 408,576 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,781,504 | 46.8% |
| LOAD_GLOBAL_MODULE | 4,563,476 | 37.0% |
| TO_BOOL_BOOL | 1,996,800 | 16.2% |
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
| SWAP | 60 | 33.3% |
| LOAD_GLOBAL_MODULE | 60 | 33.3% |
| LOAD_FAST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 33.3% |
| STORE_FAST | 60 | 33.3% |
| LOAD_DEREF | 60 | 33.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,790,976 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,790,976 | 100.0% |


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
| LOAD_FAST | 8,546,324 | 40.7% |
| CALL | 6,359,635 | 30.3% |
| ENTER_EXECUTOR | 2,773,140 | 13.2% |
| LOAD_CONST | 1,790,976 | 8.5% |
| LOAD_GLOBAL_MODULE | 1,536,000 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 6,359,635 | 30.3% |
| RETURN_VALUE | 6,354,432 | 30.3% |
| STORE_FAST | 3,327,036 | 15.8% |
| GET_ITER | 1,790,976 | 8.5% |
| CONTAINS_OP | 1,790,976 | 8.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| CALL_INTRINSIC_1 | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 50.0% |
| COPY_FREE_VARS | 60 | 50.0% |


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
| LOAD_ATTR | 4,563,456 | 71.8% |
| CALL | 1,790,976 | 28.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,563,456 | 71.8% |
| POP_JUMP_IF_FALSE | 1,790,976 | 28.2% |


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
| POP_JUMP_IF_TRUE | 4,471,296 | 93.0% |
| ENTER_EXECUTOR | 337,860 | 7.0% |
| LIST_APPEND | 700 | 0.0% |
| POP_TOP | 60 | 0.0% |
| JUMP_BACKWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,773,140 | 57.7% |
| LOAD_GLOBAL_MODULE | 1,698,856 | 35.3% |
| ENTER_EXECUTOR | 337,860 | 7.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,536,060 | 79.0% |
| JUMP_BACKWARD | 408,876 | 21.0% |
| FOR_ITER | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,791,276 | 92.1% |
| RETURN_CONST | 153,660 | 7.9% |
| FOR_ITER | 500 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 15,106,560 | 91.6% |
| LOAD_FAST_LOAD_FAST | 1,382,400 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,134,528 | 61.5% |
| POP_JUMP_IF_TRUE | 6,354,432 | 38.5% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 408,576 | 99.9% |
| POP_TOP | 300 | 0.1% |
| LIST_APPEND | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 408,876 | 100.0% |
| FOR_ITER_TUPLE | 60 | 0.0% |
| ENTER_EXECUTOR | 20 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,790,976 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,790,976 | 100.0% |


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
| LOAD_FAST_LOAD_FAST | 4,563,456 | 57.2% |
| LOAD_GLOBAL_BUILTIN | 1,790,976 | 22.4% |
| LOAD_FAST | 1,628,160 | 20.4% |
| LOAD_ATTR | 1,972 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 4,563,456 | 57.2% |
| LOAD_FAST | 1,883,136 | 23.6% |
| GET_ITER | 1,536,000 | 19.2% |
| LOAD_ATTR | 1,972 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,784,576 | 59.2% |
| LOAD_CONST | 3,993,600 | 40.8% |
| RESUME_CHECK | 300 | 0.0% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 3,993,900 | 40.8% |
| LOAD_CONST | 3,993,600 | 40.8% |
| CALL | 1,790,976 | 18.3% |
| LOAD_FAST | 240 | 0.0% |
| GET_ITER | 60 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,996,800 | 100.0% |
| RESUME_CHECK | 60 | 0.0% |
| NOP | 60 | 0.0% |
| BUILD_LIST | 60 | 0.0% |

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
| LOAD_GLOBAL_BUILTIN | 8,958,012 | 22.2% |
| LOAD_GLOBAL_MODULE | 8,954,880 | 22.2% |
| POP_JUMP_IF_FALSE | 7,163,904 | 17.7% |
| STORE_FAST | 5,526,768 | 13.7% |
| RESUME_CHECK | 1,996,800 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 10,543,104 | 26.1% |
| CALL | 8,546,324 | 21.2% |
| LOAD_CONST | 5,784,576 | 14.3% |
| CALL_TYPE_1 | 3,581,952 | 8.9% |
| LOAD_SUPER_ATTR_METHOD | 1,996,800 | 4.9% |


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
| LOAD_GLOBAL_MODULE | 5,578,752 | 36.9% |
| POP_JUMP_IF_TRUE | 4,563,456 | 30.2% |
| PUSH_NULL | 1,790,976 | 11.9% |
| LOAD_ATTR_CLASS | 1,790,976 | 11.9% |
| POP_JUMP_IF_FALSE | 1,382,400 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,563,456 | 30.2% |
| CALL_PY_EXACT_ARGS | 3,581,952 | 23.7% |
| CALL_BUILTIN_FAST | 1,996,800 | 13.2% |
| LOAD_GLOBAL_MODULE | 1,790,976 | 11.9% |
| CALL_PY_WITH_DEFAULTS | 1,790,976 | 11.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 320 | 69.6% |
| STORE_FAST | 60 | 13.0% |
| RETURN_VALUE | 40 | 8.7% |
| RESUME_CHECK | 20 | 4.3% |
| ENTER_EXECUTOR | 20 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 420 | 91.3% |
| LOAD_GLOBAL_BUILTIN | 20 | 4.3% |
| LOAD_ATTR | 20 | 4.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 10,134,528 | 66.2% |
| TO_BOOL_BOOL | 1,996,800 | 13.0% |
| CONTAINS_OP | 1,790,976 | 11.7% |
| CHECK_EXC_MATCH | 1,382,400 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,163,904 | 46.8% |
| LOAD_GLOBAL_BUILTIN | 3,379,200 | 22.1% |
| LOAD_GLOBAL_MODULE | 1,536,000 | 10.0% |
| POP_TOP | 1,382,400 | 9.0% |
| LOAD_FAST_LOAD_FAST | 1,382,400 | 9.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 408,576 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 408,576 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 6,354,432 | 42.6% |
| CONTAINS_OP | 4,563,456 | 30.6% |
| TO_BOOL_BOOL | 3,993,600 | 26.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,563,456 | 30.6% |
| ENTER_EXECUTOR | 4,471,296 | 30.0% |
| LOAD_GLOBAL_BUILTIN | 3,993,600 | 26.8% |
| LOAD_GLOBAL_MODULE | 1,790,976 | 12.0% |
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
| RETURN_VALUE | 5,781,504 | 29.1% |
| CALL | 3,327,036 | 16.8% |
| FOR_ITER | 1,791,276 | 9.0% |
| FOR_ITER_TUPLE | 1,791,096 | 9.0% |
| LOAD_GLOBAL_MODULE | 1,790,976 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,526,768 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 5,373,328 | 27.1% |
| LOAD_GLOBAL_MODULE | 3,582,032 | 18.0% |
| NOP | 3,581,952 | 18.0% |
| JUMP_FORWARD | 1,790,976 | 9.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 92,160 | 99.9% |
| LOAD_FAST_AND_CLEAR | 60 | 0.1% |
| BUILD_LIST | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 92,160 | 99.9% |
| FOR_ITER_TUPLE | 60 | 0.1% |
| BUILD_LIST | 60 | 0.1% |


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
| LOAD_GLOBAL_MODULE | 1,790,976 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,790,976 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,581,952 | 50.0% |
| LOAD_FAST | 1,790,976 | 25.0% |
| CALL_TYPE_1 | 1,790,976 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,163,904 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,790,976 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,790,976 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,581,952 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,790,976 | 50.0% |
| CALL_PY_EXACT_ARGS | 1,790,976 | 50.0% |


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
| GET_ITER | 1,790,976 | 100.0% |
| SWAP | 60 | 0.0% |
| JUMP_BACKWARD | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,791,096 | 100.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,790,976 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,790,976 | 100.0% |


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
| STORE_FAST | 5,373,328 | 30.3% |
| POP_JUMP_IF_TRUE | 3,993,600 | 22.5% |
| POP_JUMP_IF_FALSE | 3,379,200 | 19.1% |
| NOP | 1,790,976 | 10.1% |
| LOAD_GLOBAL_MODULE | 1,790,976 | 10.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,958,012 | 50.6% |
| LOAD_DEREF | 1,996,800 | 11.3% |
| LOAD_GLOBAL_MODULE | 1,790,976 | 10.1% |
| LOAD_ATTR_CLASS | 1,790,976 | 10.1% |
| LOAD_ATTR | 1,790,976 | 10.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,543,104 | 25.2% |
| RESUME_CHECK | 9,160,744 | 21.9% |
| RETURN_VALUE | 4,563,476 | 10.9% |
| LOAD_GLOBAL_MODULE | 3,582,592 | 8.6% |
| STORE_FAST | 3,582,032 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 15,106,560 | 36.1% |
| LOAD_FAST | 8,954,880 | 21.4% |
| LOAD_FAST_LOAD_FAST | 5,578,752 | 13.3% |
| LOAD_GLOBAL_MODULE | 3,582,592 | 8.6% |
| STORE_FAST | 1,790,976 | 4.3% |


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
| CALL_PY_EXACT_ARGS | 7,163,904 | 55.3% |
| COPY_FREE_VARS | 1,996,860 | 15.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 15.4% |
| CALL_PY_WITH_DEFAULTS | 1,790,976 | 13.8% |
| CACHE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 9,160,744 | 70.7% |
| LOAD_FAST | 1,996,800 | 15.4% |
| BUILD_MAP | 1,790,976 | 13.8% |
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

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        92160 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 40 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 40 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      5990400 | 100.0% |


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
| specialization.deferred |     21001152 | 39.7% |
|          hit |     31853928 | 60.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.4% |
| Failure | 5,203 | 99.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method wrapper | 2,418 | 46.5% |
| other | 1,932 | 37.1% |
| operator wrapper | 433 | 8.3% |
| class no vectorcall | 340 | 6.5% |
| cfunc noargs | 60 | 1.2% |
| init not python | 20 | 0.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1944936 | 52.0% |
|          hit |      1791276 | 47.9% |

#### Specialization attempts

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

|Kind | Count | Ratio | 
|---|---|---|


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      7982612 | 81.7% |
|          hit |      1791136 | 18.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.0% |
| Failure | 1,972 | 97.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 1,972 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     72628288 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 440 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1996800 | 100.0% |


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
|          hit |          240 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
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
| Basic | 153,847,992 | 47.7% |
| Not specialized | 62,062,939 | 19.3% |
| Specialized | 106,375,868 | 33.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 21,001,152 | 67.7% |
| LOAD_ATTR | 7,982,612 | 25.7% |
| FOR_ITER | 1,944,936 | 6.3% |
| BINARY_SUBSCR | 92,160 | 0.3% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 1,997,100 | 12.7% |
| Calls to Python functions inlined | 13,724,280 | 87.3% |
| Calls via PyEval_EvalFrame (total) | 1,997,100 | 12.7% |
| Calls via PyEval_EvalFrame (vector) | 1,997,100 | 12.7% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,997,100 | 12.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 15,721,380 | 100.0% |
| Frame objects created | 2,764,800 | 17.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 23,047,304 | 54.7% |
| Frees to freelist | 23,047,284 |  |
| Allocations | 19,089,872 | 45.3% |
| Allocations to 512 bytes | 19,089,872 | 45.3% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 19,089,891 |  |
| New values | 780 |  |
| Interpreter increfs | 142,168,264 | 52.7% |
| Interpreter decrefs | 170,970,696 | 54.8% |
| Increfs | 127,742,725 | 47.3% |
| Decrefs | 141,076,502 | 45.2% |
| Materialize dict (on request) | 780 | 100.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 11,894,997 |  |
| Method cache misses | 86,203 |  |
| Method cache collisions | 172,258 |  |
| Method cache dunder hits | 17,009,657 |  |
| Method cache dunder misses | 86,137 |  |


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
| Optimization attempts | 24,073 |  |
| Traces created | 20 | 0.1% |
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
| FOR_ITER | 24,053 |
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
Stats gathered on: 2023-10-12
