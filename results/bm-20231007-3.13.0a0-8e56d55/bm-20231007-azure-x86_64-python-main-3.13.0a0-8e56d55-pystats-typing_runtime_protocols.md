
# Pystats results

- benchmark: typing_runtime_protocols
- fork: python
- ref: main
- commit hash: 8e56d55
- commit date: 2023-10-07T17:07:36-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_GLOBAL_MODULE | 49,890,520 | 13.6% | 13.6% |  |
| LOAD_FAST | 45,896,940 | 12.5% | 26.0% |  |
| STORE_FAST | 24,684,840 | 6.7% | 32.8% |  |
| LOAD_GLOBAL_BUILTIN | 22,410,600 | 6.1% | 38.9% |  |
| CALL | 20,895,750 | 5.7% | 44.5% |  |
| LOAD_FAST_LOAD_FAST | 17,034,540 | 4.6% | 49.2% |  |
| IS_OP | 16,419,840 | 4.5% | 53.6% |  |
| RESUME_CHECK | 15,652,260 | 4.3% | 57.9% |  |
| POP_JUMP_IF_FALSE | 15,267,840 | 4.2% | 62.0% |  |
| POP_JUMP_IF_TRUE | 14,837,760 | 4.0% | 66.1% |  |
| RETURN_VALUE | 12,272,760 | 3.3% | 69.4% |  |
| CALL_PY_EXACT_ARGS | 9,876,480 | 2.7% | 72.1% |  |
| LOAD_CONST | 9,769,560 | 2.7% | 74.8% |  |
| LOAD_ATTR | 7,943,160 | 2.2% | 76.9% |  |
| JUMP_BACKWARD | 7,020,600 | 1.9% | 78.8% |  |
| CONTAINS_OP | 6,312,960 | 1.7% | 80.5% |  |
| CALL_TYPE_1 | 6,312,960 | 1.7% | 82.3% |  |
| FOR_ITER_TUPLE | 6,221,640 | 1.7% | 84.0% |  |
| CALL_BUILTIN_FAST | 5,990,700 | 1.6% | 85.6% |  |
| TO_BOOL_BOOL | 5,990,400 | 1.6% | 87.2% |  |
| POP_TOP | 4,854,120 | 1.3% | 88.5% |  |
| NOP | 3,563,580 | 1.0% | 89.5% |  |
| GET_ITER | 3,502,260 | 1.0% | 90.5% |  |
| FOR_ITER_LIST | 2,334,720 | 0.6% | 91.1% |  |
| RETURN_CONST | 1,997,100 | 0.5% | 91.6% |  |
| INTERPRETER_EXIT | 1,997,100 | 0.5% | 92.2% |  |
| LOAD_DEREF | 1,996,980 | 0.5% | 92.7% |  |
| COPY_FREE_VARS | 1,996,860 | 0.5% | 93.3% |  |
| LOAD_SUPER_ATTR_METHOD | 1,996,800 | 0.5% | 93.8% |  |
| CALL_ISINSTANCE | 1,996,800 | 0.5% | 94.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 0.5% | 94.9% |  |
| FOR_ITER | 1,936,220 | 0.5% | 95.4% |  |
| PUSH_NULL | 1,782,840 | 0.5% | 95.9% |  |
| LOAD_ATTR_CLASS | 1,781,760 | 0.5% | 96.4% |  |
| JUMP_FORWARD | 1,781,760 | 0.5% | 96.9% |  |
| CALL_PY_WITH_DEFAULTS | 1,781,760 | 0.5% | 97.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,781,760 | 0.5% | 97.8% |  |
| BUILD_MAP | 1,781,760 | 0.5% | 98.3% |  |
| RAISE_VARARGS | 1,382,400 | 0.4% | 98.7% |  |
| PUSH_EXC_INFO | 1,382,400 | 0.4% | 99.1% |  |
| POP_EXCEPT | 1,382,400 | 0.4% | 99.5% |  |
| CHECK_EXC_MATCH | 1,382,400 | 0.4% | 99.8% |  |
| POP_JUMP_IF_NONE | 399,360 | 0.1% | 99.9% |  |
| SWAP | 92,280 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 92,200 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 30,780 | 0.0% | 100.0% |  |
| LIST_APPEND | 780 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 460 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% | 100.0% |  |
| BUILD_LIST | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| STORE_ATTR | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
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
| LOAD_GLOBAL_MODULE IS_OP | 15,037,440 | 4.1% | 4.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 11,873,320 | 3.2% | 7.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 11,689,020 | 3.2% | 10.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 11,658,240 | 3.2% | 13.7% |
| LOAD_FAST CALL | 11,258,900 | 3.1% | 16.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 10,506,240 | 2.9% | 19.6% |
| IS_OP POP_JUMP_IF_FALSE | 10,106,880 | 2.7% | 22.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 9,876,480 | 2.7% | 25.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 7,342,420 | 2.0% | 27.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 7,127,040 | 1.9% | 29.0% |
| CALL CALL | 6,318,130 | 1.7% | 30.7% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 6,313,600 | 1.7% | 32.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 6,313,040 | 1.7% | 34.1% |
| LOAD_FAST CALL_TYPE_1 | 6,312,960 | 1.7% | 35.8% |
| IS_OP POP_JUMP_IF_TRUE | 6,312,960 | 1.7% | 37.5% |
| CALL RETURN_VALUE | 6,312,960 | 1.7% | 39.3% |
| LOAD_FAST LOAD_CONST | 5,775,360 | 1.6% | 40.8% |
| RETURN_VALUE STORE_FAST | 5,744,640 | 1.6% | 42.4% |
| STORE_FAST LOAD_FAST | 5,683,980 | 1.5% | 43.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 5,560,320 | 1.5% | 45.4% |
| FOR_ITER_TUPLE STORE_FAST | 4,532,040 | 1.2% | 46.7% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 4,531,220 | 1.2% | 47.9% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 4,531,200 | 1.2% | 49.1% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 4,531,200 | 1.2% | 50.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR | 4,531,200 | 1.2% | 51.6% |
| LOAD_ATTR CONTAINS_OP | 4,531,200 | 1.2% | 52.8% |
| CONTAINS_OP POP_JUMP_IF_TRUE | 4,531,200 | 1.2% | 54.1% |
| CALL_TYPE_1 CALL_PY_EXACT_ARGS | 4,531,200 | 1.2% | 55.3% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 4,439,820 | 1.2% | 56.5% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 4,439,040 | 1.2% | 57.7% |
| LOAD_CONST CALL_BUILTIN_FAST | 3,993,900 | 1.1% | 58.8% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 3,993,600 | 1.1% | 59.9% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 3,993,600 | 1.1% | 61.0% |
| LOAD_CONST LOAD_CONST | 3,993,600 | 1.1% | 62.1% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 3,993,600 | 1.1% | 63.2% |
| STORE_FAST NOP | 3,563,520 | 1.0% | 64.1% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 3,563,520 | 1.0% | 65.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 3,379,200 | 0.9% | 66.0% |
| CALL STORE_FAST | 3,317,820 | 0.9% | 66.9% |
| JUMP_BACKWARD FOR_ITER_LIST | 2,150,400 | 0.6% | 67.5% |
| FOR_ITER_LIST STORE_FAST | 2,150,400 | 0.6% | 68.1% |
| RETURN_CONST INTERPRETER_EXIT | 1,997,100 | 0.5% | 68.6% |
| POP_TOP JUMP_BACKWARD | 1,997,100 | 0.5% | 69.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 1,997,100 | 0.5% | 69.7% |
| COPY_FREE_VARS RESUME_CHECK | 1,996,860 | 0.5% | 70.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 1,996,800 | 0.5% | 70.8% |
| RETURN_VALUE TO_BOOL_BOOL | 1,996,800 | 0.5% | 71.3% |
| RESUME_CHECK LOAD_FAST | 1,996,800 | 0.5% | 71.9% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST | 1,996,800 | 0.5% | 72.4% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,996,800 | 0.5% | 73.0% |
| LOAD_FAST_LOAD_FAST CALL_ISINSTANCE | 1,996,800 | 0.5% | 73.5% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 1,996,800 | 0.5% | 74.1% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,996,800 | 0.5% | 74.6% |
| LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 0.5% | 75.1% |
| LOAD_DEREF LOAD_FAST | 1,996,800 | 0.5% | 75.7% |
| CALL_ISINSTANCE POP_TOP | 1,996,800 | 0.5% | 76.2% |
| CALL_BUILTIN_FAST RETURN_VALUE | 1,996,800 | 0.5% | 76.8% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 1,996,800 | 0.5% | 77.3% |
| CACHE COPY_FREE_VARS | 1,996,800 | 0.5% | 77.9% |
| LOAD_ATTR LOAD_FAST | 1,873,920 | 0.5% | 78.4% |
| LOAD_FAST PUSH_NULL | 1,782,540 | 0.5% | 78.9% |
| FOR_ITER STORE_FAST | 1,782,060 | 0.5% | 79.3% |
| STORE_FAST JUMP_FORWARD | 1,781,760 | 0.5% | 79.8% |
| RESUME_CHECK BUILD_MAP | 1,781,760 | 0.5% | 80.3% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,781,760 | 0.5% | 80.8% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_MODULE | 1,781,760 | 0.5% | 81.3% |
| NOP LOAD_GLOBAL_BUILTIN | 1,781,760 | 0.5% | 81.8% |
| NOP LOAD_FAST | 1,781,760 | 0.5% | 82.2% |
| LOAD_GLOBAL_MODULE STORE_FAST | 1,781,760 | 0.5% | 82.7% |
| LOAD_GLOBAL_MODULE CALL_METHOD_DESCRIPTOR_FAST | 1,781,760 | 0.5% | 83.2% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 1,781,760 | 0.5% | 83.7% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR_CLASS | 1,781,760 | 0.5% | 84.2% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 1,781,760 | 0.5% | 84.7% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 1,781,760 | 0.5% | 85.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 1,781,760 | 0.5% | 85.6% |
| LOAD_FAST STORE_FAST | 1,781,760 | 0.5% | 86.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,781,760 | 0.5% | 86.6% |
| LOAD_CONST CALL | 1,781,760 | 0.5% | 87.1% |
| LOAD_ATTR_CLASS LOAD_FAST_LOAD_FAST | 1,781,760 | 0.5% | 87.6% |
| JUMP_FORWARD LOAD_GLOBAL_MODULE | 1,781,760 | 0.5% | 88.1% |
| GET_ITER FOR_ITER_TUPLE | 1,781,760 | 0.5% | 88.5% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,781,760 | 0.5% | 89.0% |
| CALL_TYPE_1 STORE_FAST | 1,781,760 | 0.5% | 89.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,781,760 | 0.5% | 90.0% |
| CALL_METHOD_DESCRIPTOR_FAST RETURN_VALUE | 1,781,760 | 0.5% | 90.5% |
| CALL GET_ITER | 1,781,760 | 0.5% | 91.0% |
| CALL CONTAINS_OP | 1,781,760 | 0.5% | 91.5% |
| BUILD_MAP STORE_FAST | 1,781,760 | 0.5% | 91.9% |
| LOAD_GLOBAL_MODULE RETURN_VALUE | 1,689,600 | 0.5% | 92.4% |
| FOR_ITER_TUPLE LOAD_GLOBAL_MODULE | 1,689,600 | 0.5% | 92.9% |
| LOAD_FAST LOAD_ATTR | 1,628,160 | 0.4% | 93.3% |
| GET_ITER FOR_ITER | 1,536,060 | 0.4% | 93.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,536,000 | 0.4% | 94.1% |
| LOAD_GLOBAL_MODULE CALL | 1,536,000 | 0.4% | 94.5% |
| LOAD_ATTR GET_ITER | 1,536,000 | 0.4% | 95.0% |
| RAISE_VARARGS PUSH_EXC_INFO | 1,382,400 | 0.4% | 95.3% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 1,382,400 | 0.4% | 95.7% |
| POP_TOP RETURN_CONST | 1,382,400 | 0.4% | 96.1% |
| POP_TOP POP_EXCEPT | 1,382,400 | 0.4% | 96.5% |
| POP_JUMP_IF_FALSE POP_TOP | 1,382,400 | 0.4% | 96.8% |


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
| CALL | 1,781,760 | 50.9% |
| LOAD_ATTR | 1,536,000 | 43.9% |
| LOAD_FAST | 184,320 | 5.3% |
| LOAD_CONST | 60 | 0.0% |
| CALL_BUILTIN_CLASS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 1,781,760 | 50.9% |
| FOR_ITER | 1,536,060 | 43.9% |
| FOR_ITER_LIST | 184,320 | 5.3% |
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
| STORE_FAST | 3,563,520 | 100.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,781,760 | 50.0% |
| LOAD_FAST | 1,781,760 | 50.0% |
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
| CALL_ISINSTANCE | 1,996,800 | 41.1% |
| POP_JUMP_IF_FALSE | 1,382,400 | 28.5% |
| POP_EXCEPT | 1,382,400 | 28.5% |
| SWAP | 92,160 | 1.9% |
| CALL_BUILTIN_FAST | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,997,100 | 41.1% |
| RETURN_CONST | 1,382,400 | 28.5% |
| POP_EXCEPT | 1,382,400 | 28.5% |
| RETURN_VALUE | 92,160 | 1.9% |
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
| LOAD_FAST | 1,782,540 | 100.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,781,760 | 99.9% |
| CALL | 960 | 0.1% |
| LOAD_FAST | 120 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 6,312,960 | 51.4% |
| CALL_BUILTIN_FAST | 1,996,800 | 16.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,781,760 | 14.5% |
| LOAD_GLOBAL_MODULE | 1,689,600 | 13.8% |
| LOAD_FAST | 399,360 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,744,640 | 46.8% |
| LOAD_GLOBAL_MODULE | 4,531,220 | 36.9% |
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
| RESUME_CHECK | 1,781,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,781,760 | 100.0% |


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
| LOAD_FAST | 11,258,900 | 53.9% |
| CALL | 6,318,130 | 30.2% |
| LOAD_CONST | 1,781,760 | 8.5% |
| LOAD_GLOBAL_MODULE | 1,536,000 | 7.4% |
| PUSH_NULL | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 6,318,130 | 30.2% |
| RETURN_VALUE | 6,312,960 | 30.2% |
| STORE_FAST | 3,317,820 | 15.9% |
| GET_ITER | 1,781,760 | 8.5% |
| CONTAINS_OP | 1,781,760 | 8.5% |


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
| LOAD_ATTR | 4,531,200 | 71.8% |
| CALL | 1,781,760 | 28.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,531,200 | 71.8% |
| POP_JUMP_IF_FALSE | 1,781,760 | 28.2% |


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

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,536,060 | 79.3% |
| JUMP_BACKWARD | 399,660 | 20.6% |
| FOR_ITER | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,782,060 | 92.0% |
| RETURN_CONST | 153,660 | 7.9% |
| FOR_ITER | 500 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 15,037,440 | 91.6% |
| LOAD_FAST_LOAD_FAST | 1,382,400 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,106,880 | 61.6% |
| POP_JUMP_IF_TRUE | 6,312,960 | 38.4% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,439,040 | 63.2% |
| POP_TOP | 1,997,100 | 28.4% |
| POP_JUMP_IF_NONE | 399,360 | 5.7% |
| FOR_ITER_LIST | 184,320 | 2.6% |
| LIST_APPEND | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 4,439,820 | 63.2% |
| FOR_ITER_LIST | 2,150,400 | 30.6% |
| FOR_ITER | 399,660 | 5.7% |
| FOR_ITER_RANGE | 30,720 | 0.4% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,781,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,781,760 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 780 | 100.0% |


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
| LOAD_FAST_LOAD_FAST | 4,531,200 | 57.0% |
| LOAD_GLOBAL_BUILTIN | 1,781,760 | 22.4% |
| LOAD_FAST | 1,628,160 | 20.5% |
| LOAD_ATTR | 1,960 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 4,531,200 | 57.0% |
| LOAD_FAST | 1,873,920 | 23.6% |
| GET_ITER | 1,536,000 | 19.3% |
| LOAD_ATTR | 1,960 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,775,360 | 59.1% |
| LOAD_CONST | 3,993,600 | 40.9% |
| RESUME_CHECK | 300 | 0.0% |
| LOAD_FAST_LOAD_FAST | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 3,993,900 | 40.9% |
| LOAD_CONST | 3,993,600 | 40.9% |
| CALL | 1,781,760 | 18.2% |
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
| LOAD_GLOBAL_BUILTIN | 11,689,020 | 25.5% |
| LOAD_GLOBAL_MODULE | 11,658,240 | 25.4% |
| POP_JUMP_IF_FALSE | 7,127,040 | 15.5% |
| STORE_FAST | 5,683,980 | 12.4% |
| RESUME_CHECK | 1,996,800 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 11,258,900 | 24.5% |
| LOAD_GLOBAL_MODULE | 10,506,240 | 22.9% |
| CALL_TYPE_1 | 6,312,960 | 13.8% |
| LOAD_CONST | 5,775,360 | 12.6% |
| LOAD_SUPER_ATTR_METHOD | 1,996,800 | 4.4% |


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
| LOAD_GLOBAL_MODULE | 5,560,320 | 32.6% |
| POP_JUMP_IF_TRUE | 4,531,200 | 26.6% |
| LOAD_GLOBAL_BUILTIN | 1,997,100 | 11.7% |
| PUSH_NULL | 1,781,760 | 10.5% |
| LOAD_ATTR_CLASS | 1,781,760 | 10.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 4,531,200 | 26.6% |
| CALL_PY_EXACT_ARGS | 3,563,520 | 20.9% |
| CALL_ISINSTANCE | 1,996,800 | 11.7% |
| CALL_BUILTIN_FAST | 1,996,800 | 11.7% |
| LOAD_GLOBAL_MODULE | 1,781,760 | 10.5% |


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
| FOR_ITER_RANGE | 20 | 4.3% |

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
| IS_OP | 10,106,880 | 66.2% |
| TO_BOOL_BOOL | 1,996,800 | 13.1% |
| CONTAINS_OP | 1,781,760 | 11.7% |
| CHECK_EXC_MATCH | 1,382,400 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,127,040 | 46.7% |
| LOAD_GLOBAL_BUILTIN | 3,379,200 | 22.1% |
| LOAD_GLOBAL_MODULE | 1,536,000 | 10.1% |
| POP_TOP | 1,382,400 | 9.1% |
| LOAD_FAST_LOAD_FAST | 1,382,400 | 9.1% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 399,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 399,360 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 6,312,960 | 42.5% |
| CONTAINS_OP | 4,531,200 | 30.5% |
| TO_BOOL_BOOL | 3,993,600 | 26.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,531,200 | 30.5% |
| JUMP_BACKWARD | 4,439,040 | 29.9% |
| LOAD_GLOBAL_BUILTIN | 3,993,600 | 26.9% |
| LOAD_GLOBAL_MODULE | 1,781,760 | 12.0% |
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
| RETURN_VALUE | 5,744,640 | 23.3% |
| FOR_ITER_TUPLE | 4,532,040 | 18.4% |
| CALL | 3,317,820 | 13.4% |
| FOR_ITER_LIST | 2,150,400 | 8.7% |
| FOR_ITER | 1,782,060 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 7,342,420 | 29.7% |
| LOAD_GLOBAL_MODULE | 6,313,040 | 25.6% |
| LOAD_FAST | 5,683,980 | 23.0% |
| NOP | 3,563,520 | 14.4% |
| JUMP_FORWARD | 1,781,760 | 7.2% |


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
| LOAD_FAST_LOAD_FAST | 1,996,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,996,800 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,781,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,781,760 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TYPE_1 | 4,531,200 | 45.9% |
| LOAD_FAST_LOAD_FAST | 3,563,520 | 36.1% |
| LOAD_FAST | 1,781,760 | 18.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,876,480 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,781,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,781,760 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,312,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,531,200 | 71.8% |
| STORE_FAST | 1,781,760 | 28.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,150,400 | 92.1% |
| GET_ITER | 184,320 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,150,400 | 92.1% |
| JUMP_BACKWARD | 184,320 | 7.9% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 30,720 | 99.8% |
| GET_ITER | 60 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,720 | 99.8% |
| LOAD_GLOBAL_MODULE | 40 | 0.1% |
| LOAD_GLOBAL | 20 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 4,439,820 | 71.4% |
| GET_ITER | 1,781,760 | 28.6% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,532,040 | 72.8% |
| LOAD_GLOBAL_MODULE | 1,689,600 | 27.2% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,781,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,781,760 | 100.0% |


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
| STORE_FAST | 7,342,420 | 32.8% |
| LOAD_GLOBAL_MODULE | 4,531,200 | 20.2% |
| POP_JUMP_IF_TRUE | 3,993,600 | 17.8% |
| POP_JUMP_IF_FALSE | 3,379,200 | 15.1% |
| NOP | 1,781,760 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,689,020 | 52.2% |
| LOAD_FAST_LOAD_FAST | 1,997,100 | 8.9% |
| LOAD_DEREF | 1,996,800 | 8.9% |
| LOAD_GLOBAL_MODULE | 1,781,760 | 8.0% |
| LOAD_ATTR_CLASS | 1,781,760 | 8.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 11,873,320 | 23.8% |
| LOAD_FAST | 10,506,240 | 21.1% |
| LOAD_GLOBAL_MODULE | 6,313,600 | 12.7% |
| STORE_FAST | 6,313,040 | 12.7% |
| RETURN_VALUE | 4,531,220 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 15,037,440 | 30.1% |
| LOAD_FAST | 11,658,240 | 23.4% |
| LOAD_GLOBAL_MODULE | 6,313,600 | 12.7% |
| LOAD_FAST_LOAD_FAST | 5,560,320 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 4,531,200 | 9.1% |


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
| CALL_PY_EXACT_ARGS | 9,876,480 | 63.1% |
| COPY_FREE_VARS | 1,996,860 | 12.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,996,800 | 12.8% |
| CALL_PY_WITH_DEFAULTS | 1,781,760 | 11.4% |
| CACHE | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 11,873,320 | 75.9% |
| LOAD_FAST | 1,996,800 | 12.8% |
| BUILD_MAP | 1,781,760 | 11.4% |
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
| specialization.deferred |     20890560 | 39.7% |
|          hit |     31734120 | 60.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.4% |
| Failure | 5,170 | 99.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method wrapper | 2,400 | 46.4% |
| other | 1,920 | 37.1% |
| operator wrapper | 430 | 8.3% |
| class no vectorcall | 340 | 6.6% |
| cfunc noargs | 60 | 1.2% |
| init not python | 20 | 0.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1935720 | 18.4% |
|          hit |      8587140 | 81.6% |

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
| specialization.deferred |      7941140 | 81.7% |
|          hit |      1781920 | 18.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.0% |
| Failure | 1,960 | 97.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 1,960 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     72301120 | 100.0% |

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
| Basic | 163,269,000 | 44.4% |
| Not specialized | 68,393,450 | 18.6% |
| Specialized | 136,047,260 | 37.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 20,890,560 | 67.7% |
| LOAD_ATTR | 7,941,140 | 25.7% |
| FOR_ITER | 1,935,720 | 6.3% |
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
| Calls to PyEval_EvalDefault | 1,997,100 | 12.8% |
| Calls to Python functions inlined | 13,655,160 | 87.2% |
| Calls via PyEval_EvalFrame (total) | 1,997,100 | 12.8% |
| Calls via PyEval_EvalFrame (vector) | 1,997,100 | 12.8% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,997,100 | 12.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 15,652,260 | 100.0% |
| Frame objects created | 2,764,800 | 17.7% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 22,918,280 | 54.6% |
| Frees to freelist | 22,918,260 |  |
| Allocations | 19,048,360 | 45.4% |
| Allocations to 512 bytes | 19,048,360 | 45.4% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 19,048,388 |  |
| New values | 780 |  |
| Interpreter increfs | 159,795,580 | 60.5% |
| Interpreter decrefs | 186,214,260 | 60.8% |
| Increfs | 104,403,821 | 39.5% |
| Decrefs | 119,950,843 | 39.2% |
| Materialize dict (on request) | 780 | 100.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 11,896,537 |  |
| Method cache misses | 84,663 |  |
| Method cache collisions | 169,202 |  |
| Method cache dunder hits | 16,951,260 |  |
| Method cache dunder misses | 84,600 |  |


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
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
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
| <= 1 | 0 |  |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

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
Stats gathered on: 2023-10-08
