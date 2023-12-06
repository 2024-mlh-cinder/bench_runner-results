
# Pystats results

- benchmark: regex_effbot
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 2dde229
- commit date: 2023-10-19T19:17:27-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 3,528,540 | 16.6% | 16.6% |  |
| LOAD_GLOBAL_MODULE | 1,764,340 | 8.3% | 24.8% |  |
| LOAD_GLOBAL_BUILTIN | 1,764,060 | 8.3% | 33.1% |  |
| POP_JUMP_IF_FALSE | 1,411,200 | 6.6% | 39.7% |  |
| LOAD_FAST_LOAD_FAST | 1,411,200 | 6.6% | 46.4% |  |
| STORE_FAST | 706,080 | 3.3% | 49.7% |  |
| RETURN_VALUE | 705,720 | 3.3% | 53.0% |  |
| RESUME_CHECK | 705,720 | 3.3% | 56.3% |  |
| POP_TOP | 705,660 | 3.3% | 59.6% |  |
| TO_BOOL_BOOL | 705,600 | 3.3% | 62.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 705,600 | 3.3% | 66.2% |  |
| CALL_TYPE_1 | 705,600 | 3.3% | 69.5% |  |
| CALL_ISINSTANCE | 705,600 | 3.3% | 72.8% |  |
| BUILD_TUPLE | 705,600 | 3.3% | 76.1% |  |
| CALL | 353,140 | 1.7% | 77.8% |  |
| PUSH_NULL | 353,100 | 1.7% | 79.5% |  |
| POP_JUMP_IF_NOT_NONE | 352,860 | 1.7% | 81.1% |  |
| NOP | 352,860 | 1.7% | 82.8% |  |
| TO_BOOL_INT | 352,800 | 1.7% | 84.4% |  |
| PUSH_EXC_INFO | 352,800 | 1.7% | 86.1% |  |
| POP_EXCEPT | 352,800 | 1.7% | 87.7% |  |
| LOAD_CONST | 352,800 | 1.7% | 89.4% |  |
| JUMP_FORWARD | 352,800 | 1.7% | 91.1% |  |
| CHECK_EXC_MATCH | 352,800 | 1.7% | 92.7% |  |
| CALL_PY_WITH_DEFAULTS | 352,800 | 1.7% | 94.4% |  |
| CALL_PY_EXACT_ARGS | 352,800 | 1.7% | 96.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 352,800 | 1.7% | 97.7% |  |
| BINARY_SUBSCR_DICT | 352,800 | 1.7% | 99.3% |  |
| JUMP_BACKWARD | 35,520 | 0.2% | 99.5% |  |
| FOR_ITER_LIST | 35,520 | 0.2% | 99.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 35,280 | 0.2% | 99.8% |  |
| STORE_FAST_STORE_FAST | 35,280 | 0.2% | 100.0% |  |
| GET_ITER | 300 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 300 | 0.0% | 100.0% |  |
| LOAD_ATTR | 260 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 220 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,411,260 | 6.6% | 6.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 705,600 | 3.3% | 9.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 705,600 | 3.3% | 13.2% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 705,600 | 3.3% | 16.6% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 705,600 | 3.3% | 19.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 705,600 | 3.3% | 23.2% |
| LOAD_FAST CALL_TYPE_1 | 705,600 | 3.3% | 26.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 705,600 | 3.3% | 29.8% |
| CALL_TYPE_1 LOAD_FAST_LOAD_FAST | 705,600 | 3.3% | 33.1% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 705,600 | 3.3% | 36.4% |
| STORE_FAST LOAD_FAST | 353,100 | 1.7% | 38.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 352,880 | 1.7% | 39.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 352,840 | 1.7% | 41.4% |
| LOAD_FAST CALL | 352,820 | 1.7% | 43.0% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 352,800 | 1.7% | 44.7% |
| RETURN_VALUE POP_TOP | 352,800 | 1.7% | 46.3% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 352,800 | 1.7% | 48.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 352,800 | 1.7% | 49.7% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 352,800 | 1.7% | 51.3% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 352,800 | 1.7% | 53.0% |
| POP_TOP POP_EXCEPT | 352,800 | 1.7% | 54.6% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_BUILTIN | 352,800 | 1.7% | 56.3% |
| POP_JUMP_IF_FALSE POP_TOP | 352,800 | 1.7% | 57.9% |
| POP_JUMP_IF_FALSE NOP | 352,800 | 1.7% | 59.6% |
| POP_EXCEPT JUMP_FORWARD | 352,800 | 1.7% | 61.2% |
| NOP LOAD_GLOBAL_MODULE | 352,800 | 1.7% | 62.9% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 352,800 | 1.7% | 64.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 352,800 | 1.7% | 66.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_NO_DICT | 352,800 | 1.7% | 67.9% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 352,800 | 1.7% | 69.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 352,800 | 1.7% | 71.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 352,800 | 1.7% | 72.8% |
| LOAD_FAST TO_BOOL_INT | 352,800 | 1.7% | 74.5% |
| LOAD_FAST RETURN_VALUE | 352,800 | 1.7% | 76.1% |
| LOAD_FAST PUSH_NULL | 352,800 | 1.7% | 77.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 352,800 | 1.7% | 79.5% |
| LOAD_FAST LOAD_CONST | 352,800 | 1.7% | 81.1% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST | 352,800 | 1.7% | 82.8% |
| JUMP_FORWARD LOAD_GLOBAL_BUILTIN | 352,800 | 1.7% | 84.4% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 352,800 | 1.7% | 86.1% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 352,800 | 1.7% | 87.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 352,800 | 1.7% | 89.4% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 352,800 | 1.7% | 91.0% |
| CALL RETURN_VALUE | 352,800 | 1.7% | 92.7% |
| BUILD_TUPLE STORE_FAST | 352,800 | 1.7% | 94.4% |
| BUILD_TUPLE BINARY_SUBSCR_DICT | 352,800 | 1.7% | 96.0% |
| BINARY_SUBSCR_DICT PUSH_EXC_INFO | 352,800 | 1.7% | 97.7% |
| POP_TOP LOAD_FAST | 317,520 | 1.5% | 99.2% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 35,280 | 0.2% | 99.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 35,280 | 0.2% | 99.5% |
| POP_TOP JUMP_BACKWARD | 35,280 | 0.2% | 99.6% |
| JUMP_BACKWARD FOR_ITER_LIST | 35,280 | 0.2% | 99.8% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE | 35,280 | 0.2% | 100.0% |
| LOAD_FAST GET_ITER | 300 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 240 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_LIST | 240 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 240 | 0.0% | 100.0% |
| FOR_ITER_LIST JUMP_BACKWARD | 240 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 200 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 140 | 0.0% | 100.0% |
| CALL CALL | 140 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 60 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_ATTR STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_ATTR POP_JUMP_IF_NOT_NONE | 60 | 0.0% | 100.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL POP_TOP | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT_LHS RETURN_VALUE | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT_LHS | 40 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR | 40 | 0.0% | 100.0% |
| FOR_ITER_RANGE LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL | 20 | 0.0% | 100.0% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL | 20 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 352,800 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 240 | 80.0% |
| FOR_ITER_RANGE | 60 | 20.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 352,800 | 100.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 352,800 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 352,800 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 352,800 | 50.0% |
| POP_JUMP_IF_FALSE | 352,800 | 50.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 352,800 | 50.0% |
| LOAD_FAST | 317,520 | 45.0% |
| JUMP_BACKWARD | 35,280 | 5.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 352,800 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 352,800 | 99.9% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 352,800 | 99.9% |
| CALL | 180 | 0.1% |
| LOAD_FAST | 120 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 352,800 | 50.0% |
| CALL | 352,800 | 50.0% |
| RETURN_VALUE | 60 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 352,800 | 50.0% |
| LOAD_ATTR_METHOD_NO_DICT | 352,800 | 50.0% |
| RETURN_VALUE | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT_LHS | 20 | 100.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 705,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 352,800 | 50.0% |
| BINARY_SUBSCR_DICT | 352,800 | 50.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 352,820 | 99.9% |
| PUSH_NULL | 180 | 0.1% |
| CALL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 352,800 | 99.9% |
| CALL | 140 | 0.0% |
| STORE_FAST | 60 | 0.0% |
| POP_TOP | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


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

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 35,280 | 99.3% |
| FOR_ITER_LIST | 240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 35,280 | 99.3% |
| FOR_ITER_RANGE | 240 | 0.7% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 352,800 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 200 | 76.9% |
| LOAD_ATTR | 40 | 15.4% |
| LOAD_GLOBAL | 20 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 80 | 30.8% |
| STORE_FAST | 60 | 23.1% |
| POP_JUMP_IF_NOT_NONE | 60 | 23.1% |
| LOAD_ATTR | 40 | 15.4% |
| PUSH_NULL | 20 | 7.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 352,800 | 100.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 33.3% |
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 66.7% |
| LIST_EXTEND | 60 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,411,260 | 40.0% |
| POP_JUMP_IF_FALSE | 705,600 | 20.0% |
| LOAD_ATTR_METHOD_NO_DICT | 705,600 | 20.0% |
| STORE_FAST | 353,100 | 10.0% |
| POP_TOP | 317,520 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 705,600 | 20.0% |
| CALL_TYPE_1 | 705,600 | 20.0% |
| CALL | 352,820 | 10.0% |
| TO_BOOL_INT | 352,800 | 10.0% |
| RETURN_VALUE | 352,800 | 10.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TYPE_1 | 705,600 | 50.0% |
| PUSH_NULL | 352,800 | 25.0% |
| LOAD_GLOBAL_MODULE | 352,800 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 705,600 | 50.0% |
| CALL_PY_WITH_DEFAULTS | 352,800 | 25.0% |
| CALL_PY_EXACT_ARGS | 352,800 | 25.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 37.5% |
| RETURN_VALUE | 40 | 25.0% |
| RESUME_CHECK | 20 | 12.5% |
| POP_JUMP_IF_NOT_NONE | 20 | 12.5% |
| FOR_ITER_RANGE | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 75.0% |
| LOAD_GLOBAL_BUILTIN | 20 | 12.5% |
| LOAD_ATTR | 20 | 12.5% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 705,600 | 50.0% |
| TO_BOOL_INT | 352,800 | 25.0% |
| CHECK_EXC_MATCH | 352,800 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 705,600 | 50.0% |
| POP_TOP | 352,800 | 25.0% |
| NOP | 352,800 | 25.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 352,800 | 100.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 352,800 | 100.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 352,800 | 50.0% |
| BUILD_TUPLE | 352,800 | 50.0% |
| FOR_ITER_RANGE | 240 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 353,100 | 50.0% |
| LOAD_GLOBAL_MODULE | 352,880 | 50.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 35,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,280 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT_LHS

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT_LHS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 100.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 352,800 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 705,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 705,600 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 352,800 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 352,800 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 352,800 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 705,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 705,600 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 35,280 | 99.3% |
| GET_ITER | 240 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 35,280 | 99.3% |
| JUMP_BACKWARD | 240 | 0.7% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 80.0% |
| GET_ITER | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 80.0% |
| LOAD_GLOBAL_MODULE | 40 | 13.3% |
| LOAD_GLOBAL | 20 | 6.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 352,800 | 50.0% |
| LOAD_GLOBAL_MODULE | 352,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 705,600 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 140 | 63.6% |
| LOAD_ATTR | 80 | 36.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 72.7% |
| STORE_FAST | 60 | 27.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 352,800 | 20.0% |
| PUSH_EXC_INFO | 352,800 | 20.0% |
| POP_JUMP_IF_NOT_NONE | 352,800 | 20.0% |
| LOAD_GLOBAL_MODULE | 352,800 | 20.0% |
| JUMP_FORWARD | 352,800 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,411,260 | 80.0% |
| CHECK_EXC_MATCH | 352,800 | 20.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 705,600 | 40.0% |
| STORE_FAST | 352,880 | 20.0% |
| RESUME_CHECK | 352,840 | 20.0% |
| NOP | 352,800 | 20.0% |
| LOAD_GLOBAL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 705,600 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 352,800 | 20.0% |
| LOAD_FAST_LOAD_FAST | 352,800 | 20.0% |
| LOAD_ATTR_METHOD_NO_DICT | 352,800 | 20.0% |
| LOAD_ATTR | 200 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 352,800 | 50.0% |
| CALL_PY_EXACT_ARGS | 352,800 | 50.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 352,840 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 352,800 | 50.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 705,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 705,600 | 100.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 352,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 352,800 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 35,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 35,280 | 100.0% |


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
|          hit |       352800 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1058400 | 100.0% |


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
| specialization.deferred |       352980 | 12.5% |
|          hit |      2469660 | 87.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 12.5% |
| Failure | 140 | 87.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 80 | 57.1% |
| cfunc noargs | 60 | 42.9% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |        35820 | 100.0% |


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
| specialization.deferred |          140 | 0.0% |
|          hit |       705820 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 66.7% |
| Failure | 40 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 40 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |      3528400 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
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

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |        35280 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 10,268,880 | 48.2% |
| Not specialized | 2,153,160 | 10.1% |
| Specialized | 8,891,960 | 41.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 352,980 | 100.0% |
| LOAD_ATTR | 140 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_INT | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 705,720 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 705,720 | 100.0% |
| Frame objects created | 352,800 | 50.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,058,620 | 0.7% |
| Frees to freelist | 1,058,580 |  |
| Allocations | 158,712,440 | 99.3% |
| Allocations to 512 bytes | 158,712,440 | 99.3% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 159,031,620 |  |
| New values | 0 |  |
| Interpreter increfs | 9,194,380 | 68.9% |
| Interpreter decrefs | 9,548,100 | 59.0% |
| Increfs | 4,152,520 | 31.1% |
| Decrefs | 6,621,740 | 41.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 180 |  |
| Method cache misses | 0 |  |
| Method cache collisions | 0 |  |
| Method cache dunder hits | 705,600 |  |
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
Stats gathered on: 2023-10-20
