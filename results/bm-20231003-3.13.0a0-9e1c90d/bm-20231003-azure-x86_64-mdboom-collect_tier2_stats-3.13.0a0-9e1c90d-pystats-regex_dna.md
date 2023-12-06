
# Pystats results

- benchmark: regex_dna
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 6,200 | 12.4% | 12.4% |  |
| LOAD_GLOBAL_MODULE | 4,880 | 9.7% | 22.1% |  |
| LOAD_FAST_LOAD_FAST | 4,500 | 9.0% | 31.0% |  |
| LOAD_GLOBAL_BUILTIN | 3,300 | 6.6% | 37.6% |  |
| RETURN_VALUE | 2,700 | 5.4% | 43.0% |  |
| RESUME_CHECK | 2,700 | 5.4% | 48.4% |  |
| POP_JUMP_IF_FALSE | 2,040 | 4.1% | 52.5% |  |
| CALL | 1,860 | 3.7% | 56.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,800 | 3.6% | 59.7% |  |
| PUSH_NULL | 1,560 | 3.1% | 62.9% |  |
| LOAD_ATTR_MODULE | 1,420 | 2.8% | 65.7% |  |
| STORE_FAST | 1,400 | 2.8% | 68.5% |  |
| NOP | 1,320 | 2.6% | 71.1% |  |
| CALL_PY_EXACT_ARGS | 1,320 | 2.6% | 73.7% |  |
| BUILD_TUPLE | 1,320 | 2.6% | 76.4% |  |
| TO_BOOL_BOOL | 1,260 | 2.5% | 78.9% |  |
| CALL_TYPE_1 | 1,260 | 2.5% | 81.4% |  |
| CALL_ISINSTANCE | 1,260 | 2.5% | 83.9% |  |
| BINARY_SUBSCR_DICT | 1,260 | 2.5% | 86.4% |  |
| ENTER_EXECUTOR | 960 | 1.9% | 88.3% |  |
| TO_BOOL | 740 | 1.5% | 89.8% |  |
| CALL_LEN | 720 | 1.4% | 91.2% |  |
| CALL_PY_WITH_DEFAULTS | 540 | 1.1% | 92.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 1.1% | 93.4% |  |
| CALL_LIST_APPEND | 540 | 1.1% | 94.5% |  |
| FOR_ITER_TUPLE | 360 | 0.7% | 95.2% |  |
| JUMP_BACKWARD | 340 | 0.7% | 95.9% |  |
| LOAD_GLOBAL | 240 | 0.5% | 96.3% |  |
| LOAD_DEREF | 180 | 0.4% | 96.7% |  |
| GET_ITER | 180 | 0.4% | 97.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 160 | 0.3% | 97.4% |  |
| STORE_FAST_STORE_FAST | 160 | 0.3% | 97.7% |  |
| LOAD_CONST | 120 | 0.2% | 97.9% |  |
| FOR_ITER_RANGE | 120 | 0.2% | 98.2% |  |
| CALL_FUNCTION_EX | 120 | 0.2% | 98.4% |  |
| BUILD_LIST | 120 | 0.2% | 98.6% |  |
| LOAD_ATTR | 100 | 0.2% | 98.8% |  |
| COMPARE_OP | 80 | 0.2% | 99.0% |  |
| POP_TOP | 60 | 0.1% | 99.1% |  |
| POP_JUMP_IF_NONE | 60 | 0.1% | 99.2% |  |
| LOAD_FAST_CHECK | 60 | 0.1% | 99.4% |  |
| LIST_EXTEND | 60 | 0.1% | 99.5% |  |
| COPY_FREE_VARS | 60 | 0.1% | 99.6% |  |
| CALL_INTRINSIC_1 | 60 | 0.1% | 99.7% |  |
| CALL_BUILTIN_CLASS | 60 | 0.1% | 99.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.1% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,760 | 5.5% | 5.5% |
| LOAD_FAST CALL | 1,540 | 3.1% | 8.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,440 | 2.9% | 11.4% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,420 | 2.8% | 14.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,340 | 2.7% | 16.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,320 | 2.6% | 19.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 1,260 | 2.5% | 22.1% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 1,260 | 2.5% | 24.6% |
| POP_JUMP_IF_FALSE NOP | 1,260 | 2.5% | 27.1% |
| NOP LOAD_GLOBAL_MODULE | 1,260 | 2.5% | 29.6% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 1,260 | 2.5% | 32.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,260 | 2.5% | 34.6% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 1,260 | 2.5% | 37.1% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 1,260 | 2.5% | 39.7% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,260 | 2.5% | 42.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,260 | 2.5% | 44.7% |
| LOAD_FAST CALL_TYPE_1 | 1,260 | 2.5% | 47.2% |
| CALL_TYPE_1 LOAD_FAST_LOAD_FAST | 1,260 | 2.5% | 49.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,260 | 2.5% | 52.2% |
| BUILD_TUPLE BINARY_SUBSCR_DICT | 1,260 | 2.5% | 54.7% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 1,260 | 2.5% | 57.2% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,200 | 2.4% | 59.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 840 | 1.7% | 61.3% |
| RETURN_VALUE STORE_FAST | 780 | 1.6% | 62.9% |
| TO_BOOL POP_JUMP_IF_FALSE | 720 | 1.4% | 64.3% |
| RESUME_CHECK LOAD_FAST | 720 | 1.4% | 65.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 720 | 1.4% | 67.2% |
| LOAD_FAST TO_BOOL | 720 | 1.4% | 68.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 720 | 1.4% | 70.0% |
| CALL RETURN_VALUE | 720 | 1.4% | 71.5% |
| CALL RESUME_CHECK | 720 | 1.4% | 72.9% |
| STORE_FAST ENTER_EXECUTOR | 540 | 1.1% | 74.0% |
| RETURN_VALUE CALL_LEN | 540 | 1.1% | 75.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 540 | 1.1% | 76.1% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 540 | 1.1% | 77.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 540 | 1.1% | 78.3% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 1.1% | 79.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_BUILTIN | 540 | 1.1% | 80.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 540 | 1.1% | 81.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 540 | 1.1% | 82.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS RETURN_VALUE | 540 | 1.1% | 83.7% |
| CALL_LEN CALL_LIST_APPEND | 540 | 1.1% | 84.7% |
| ENTER_EXECUTOR LOAD_ATTR_MODULE | 500 | 1.0% | 85.7% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 380 | 0.8% | 86.5% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_NO_DICT | 340 | 0.7% | 87.2% |
| STORE_FAST LOAD_FAST | 320 | 0.6% | 87.8% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 240 | 0.5% | 88.3% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 200 | 0.4% | 88.7% |
| FOR_ITER_TUPLE STORE_FAST | 200 | 0.4% | 89.1% |
| STORE_FAST JUMP_BACKWARD | 180 | 0.4% | 89.4% |
| PUSH_NULL CALL | 180 | 0.4% | 89.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 160 | 0.3% | 90.1% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_MODULE | 160 | 0.3% | 90.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 160 | 0.3% | 90.8% |
| FOR_ITER_TUPLE UNPACK_SEQUENCE_TWO_TUPLE | 160 | 0.3% | 91.1% |
| CALL_LIST_APPEND JUMP_BACKWARD | 160 | 0.3% | 91.4% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 140 | 0.3% | 91.7% |
| CALL CALL | 140 | 0.3% | 91.9% |
| PUSH_NULL LOAD_FAST | 120 | 0.2% | 92.2% |
| LOAD_GLOBAL_MODULE GET_ITER | 120 | 0.2% | 92.4% |
| LOAD_FAST CALL_LEN | 120 | 0.2% | 92.7% |
| LOAD_DEREF PUSH_NULL | 120 | 0.2% | 92.9% |
| GET_ITER FOR_ITER_TUPLE | 120 | 0.2% | 93.1% |
| CALL_LEN STORE_FAST | 120 | 0.2% | 93.4% |
| STORE_FAST LOAD_GLOBAL | 100 | 0.2% | 93.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 80 | 0.2% | 93.7% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 80 | 0.2% | 93.9% |
| LOAD_ATTR LOAD_ATTR_MODULE | 80 | 0.2% | 94.1% |
| STORE_FAST BUILD_LIST | 60 | 0.1% | 94.2% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.1% | 94.3% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.1% | 94.4% |
| PUSH_NULL LOAD_CONST | 60 | 0.1% | 94.5% |
| POP_TOP NOP | 60 | 0.1% | 94.7% |
| POP_JUMP_IF_NONE LOAD_FAST_CHECK | 60 | 0.1% | 94.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 60 | 0.1% | 94.9% |
| NOP LOAD_DEREF | 60 | 0.1% | 95.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 60 | 0.1% | 95.1% |
| LOAD_FAST_CHECK LOAD_FAST | 60 | 0.1% | 95.3% |
| LOAD_FAST RETURN_VALUE | 60 | 0.1% | 95.4% |
| LOAD_FAST POP_JUMP_IF_NONE | 60 | 0.1% | 95.5% |
| LOAD_FAST GET_ITER | 60 | 0.1% | 95.6% |
| LOAD_FAST COMPARE_OP | 60 | 0.1% | 95.7% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.1% | 95.9% |
| LOAD_FAST BUILD_LIST | 60 | 0.1% | 96.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.1% | 96.1% |
| LOAD_CONST LOAD_FAST | 60 | 0.1% | 96.2% |
| LOAD_CONST LOAD_CONST | 60 | 0.1% | 96.3% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.1% | 96.5% |
| JUMP_BACKWARD FOR_ITER_RANGE | 60 | 0.1% | 96.6% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.1% | 96.7% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.1% | 96.8% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 60 | 0.1% | 96.9% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.1% | 97.1% |
| COMPARE_OP POP_JUMP_IF_FALSE | 60 | 0.1% | 97.2% |
| CALL_LEN BUILD_TUPLE | 60 | 0.1% | 97.3% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.1% | 97.4% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.1% | 97.5% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.1% | 97.6% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.1% | 97.8% |
| CALL STORE_FAST | 60 | 0.1% | 97.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 66.7% |
| LOAD_FAST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 120 | 66.7% |
| FOR_ITER_RANGE | 60 | 33.3% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,260 | 95.5% |
| POP_TOP | 60 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260 | 95.5% |
| LOAD_DEREF | 60 | 4.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,420 | 91.0% |
| LOAD_DEREF | 120 | 7.7% |
| LOAD_ATTR | 20 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,200 | 76.9% |
| CALL | 180 | 11.5% |
| LOAD_FAST | 120 | 7.7% |
| LOAD_CONST | 60 | 3.8% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 1,260 | 46.7% |
| CALL | 720 | 26.7% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 20.0% |
| RETURN_VALUE | 60 | 2.2% |
| LOAD_FAST | 60 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,260 | 46.7% |
| STORE_FAST | 780 | 28.9% |
| CALL_LEN | 540 | 20.0% |
| RETURN_VALUE | 60 | 2.2% |
| LOAD_GLOBAL | 40 | 1.5% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 97.3% |
| TO_BOOL | 20 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 720 | 97.3% |
| TO_BOOL | 20 | 2.7% |


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
| STORE_FAST | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| LOAD_DEREF | 60 | 50.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,260 | 95.5% |
| CALL_LEN | 60 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 1,260 | 95.5% |
| RETURN_VALUE | 60 | 4.5% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,540 | 82.8% |
| PUSH_NULL | 180 | 9.7% |
| CALL | 140 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 720 | 38.7% |
| RESUME_CHECK | 720 | 38.7% |
| CALL | 140 | 7.5% |
| STORE_FAST | 60 | 3.2% |
| POP_TOP | 60 | 3.2% |


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

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 75.0% |
| COMPARE_OP | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 75.0% |
| COMPARE_OP | 20 | 25.0% |


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
| STORE_FAST | 540 | 56.2% |
| CALL_LIST_APPEND | 380 | 39.6% |
| JUMP_BACKWARD | 40 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 500 | 52.1% |
| LOAD_ATTR_METHOD_NO_DICT | 340 | 35.4% |
| LOAD_FAST_LOAD_FAST | 60 | 6.2% |
| LOAD_GLOBAL_MODULE | 40 | 4.2% |
| LOAD_GLOBAL | 20 | 2.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 52.9% |
| CALL_LIST_APPEND | 160 | 47.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 240 | 70.6% |
| FOR_ITER_RANGE | 60 | 17.6% |
| ENTER_EXECUTOR | 40 | 11.8% |


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
| LOAD_GLOBAL_MODULE | 80 | 80.0% |
| LOAD_GLOBAL | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 80 | 80.0% |
| PUSH_NULL | 20 | 20.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 50.0% |
| LOAD_CONST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| LOAD_CONST | 60 | 50.0% |


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
| LOAD_GLOBAL_BUILTIN | 2,760 | 44.5% |
| LOAD_FAST_LOAD_FAST | 1,440 | 23.2% |
| RESUME_CHECK | 720 | 11.6% |
| LOAD_ATTR_METHOD_NO_DICT | 540 | 8.7% |
| STORE_FAST | 320 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,540 | 24.8% |
| LOAD_GLOBAL_MODULE | 1,260 | 20.3% |
| CALL_TYPE_1 | 1,260 | 20.3% |
| TO_BOOL | 720 | 11.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 8.7% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,260 | 28.0% |
| CALL_TYPE_1 | 1,260 | 28.0% |
| PUSH_NULL | 1,200 | 26.7% |
| LOAD_ATTR_METHOD_NO_DICT | 720 | 16.0% |
| ENTER_EXECUTOR | 60 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,440 | 32.0% |
| CALL_PY_EXACT_ARGS | 1,260 | 28.0% |
| BUILD_TUPLE | 1,260 | 28.0% |
| CALL_PY_WITH_DEFAULTS | 540 | 12.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 100 | 41.7% |
| RETURN_VALUE | 40 | 16.7% |
| RESUME_CHECK | 40 | 16.7% |
| LOAD_FAST | 20 | 8.3% |
| FOR_ITER_RANGE | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 140 | 58.3% |
| LOAD_GLOBAL_BUILTIN | 80 | 33.3% |
| LOAD_ATTR | 20 | 8.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,260 | 61.8% |
| TO_BOOL | 720 | 35.3% |
| COMPARE_OP | 60 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 1,260 | 61.8% |
| LOAD_GLOBAL_MODULE | 720 | 35.3% |
| LOAD_FAST | 60 | 2.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_CHECK | 60 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 780 | 55.7% |
| FOR_ITER_TUPLE | 200 | 14.3% |
| CALL_LEN | 120 | 8.6% |
| FOR_ITER_RANGE | 60 | 4.3% |
| CALL_BUILTIN_CLASS | 60 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 540 | 38.6% |
| LOAD_FAST | 320 | 22.9% |
| JUMP_BACKWARD | 180 | 12.9% |
| LOAD_GLOBAL_MODULE | 160 | 11.4% |
| LOAD_GLOBAL | 100 | 7.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 160 | 100.0% |


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

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,260 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 1,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,260 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 540 | 75.0% |
| LOAD_FAST | 120 | 16.7% |
| CALL | 60 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 540 | 75.0% |
| STORE_FAST | 120 | 16.7% |
| BUILD_TUPLE | 60 | 8.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 380 | 70.4% |
| JUMP_BACKWARD | 160 | 29.6% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 540 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,260 | 95.5% |
| LOAD_FAST | 40 | 3.0% |
| CALL | 20 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,320 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 540 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,260 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 60 | 50.0% |
| GET_ITER | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 33.3% |
| LOAD_GLOBAL | 20 | 16.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 66.7% |
| GET_ITER | 120 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 55.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 160 | 44.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,260 | 70.0% |
| ENTER_EXECUTOR | 340 | 18.9% |
| LOAD_FAST | 200 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 720 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 540 | 30.0% |
| LOAD_FAST | 540 | 30.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 840 | 59.2% |
| ENTER_EXECUTOR | 500 | 35.2% |
| LOAD_ATTR | 80 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,420 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,340 | 40.6% |
| LOAD_GLOBAL_MODULE | 1,260 | 38.2% |
| LOAD_ATTR_METHOD_NO_DICT | 540 | 16.4% |
| LOAD_GLOBAL | 80 | 2.4% |
| STORE_FAST | 40 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,760 | 83.6% |
| LOAD_GLOBAL_MODULE | 540 | 16.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 1,260 | 25.8% |
| LOAD_FAST | 1,260 | 25.8% |
| POP_JUMP_IF_FALSE | 720 | 14.8% |
| RESUME_CHECK | 540 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 540 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,260 | 25.8% |
| LOAD_FAST_LOAD_FAST | 1,260 | 25.8% |
| CALL_ISINSTANCE | 1,260 | 25.8% |
| LOAD_ATTR_MODULE | 840 | 17.2% |
| GET_ITER | 120 | 2.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,320 | 48.9% |
| CALL | 720 | 26.7% |
| CALL_PY_WITH_DEFAULTS | 540 | 20.0% |
| COPY_FREE_VARS | 60 | 2.2% |
| CALL_FUNCTION_EX | 60 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,340 | 49.6% |
| LOAD_FAST | 720 | 26.7% |
| LOAD_GLOBAL_MODULE | 540 | 20.0% |
| LOAD_DEREF | 60 | 2.2% |
| LOAD_GLOBAL | 40 | 1.5% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 1,260 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,260 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 160 | 100.0% |


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
|          hit |         1260 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          720 | 36.0% |
|          hit |         1260 | 63.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 20 | 100.0% |


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
| specialization.deferred |         1620 | 20.0% |
|          hit |         6240 | 77.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 41.7% |
| Failure | 140 | 58.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 42.9% |
| code complex parameters | 60 | 42.9% |
| meth descr method fastcall keywords | 20 | 14.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 20 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          480 | 100.0% |


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
| specialization.deferred |           20 | 0.6% |
|          hit |         3220 | 97.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.2% |
|          hit |         8180 | 97.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 100.0% |
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

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          160 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 21,140 | 42.1% |
| Not specialized | 5,480 | 10.9% |
| Specialized | 23,560 | 47.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 1,620 | 66.4% |
| TO_BOOL | 720 | 29.5% |
| COMPARE_OP | 60 | 2.5% |
| LOAD_GLOBAL | 20 | 0.8% |
| LOAD_ATTR | 20 | 0.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
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
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 2,700 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 4.4% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 2,700 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 2,880 | 0.1% |
| Frees to freelist | 2,820 |  |
| Allocations | 4,847,560 | 99.9% |
| Allocations to 512 bytes | 4,831,420 | 99.6% |
| Allocations to 4 kbytes | 13,380 | 0.3% |
| Allocations over 4 kbytes | 2,760 | 0.1% |
| Frees | 5,875,200 |  |
| New values | 0 |  |
| Interpreter increfs | 27,620 | 0.1% |
| Interpreter decrefs | 29,080 | 0.1% |
| Increfs | 21,568,000 | 99.9% |
| Decrefs | 26,414,840 | 99.9% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 18 |  |
| Method cache misses | 2 |  |
| Method cache collisions | 2 |  |
| Method cache dunder hits | 2,520 |  |
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
| Traces executed | 960 |  |
| Uops executed | 10,900 | 11 |
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
| <= 32 | 20 | 50.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 50.0% |
| <= 32 | 20 | 50.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 120 | 12.5% |
| <= 16 | 840 | 87.5% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 2,920 | 26.8% | 26.8% |
| STORE_FAST | 1,340 | 12.3% | 39.1% |
| _POP_JUMP_IF_TRUE | 960 | 8.8% | 47.9% |
| _ITER_CHECK_TUPLE | 960 | 8.8% | 56.7% |
| _IS_ITER_EXHAUSTED_TUPLE | 960 | 8.8% | 65.5% |
| _EXIT_TRACE | 960 | 8.8% | 74.3% |
| _ITER_NEXT_TUPLE | 840 | 7.7% | 82.0% |
| _LOAD_GLOBAL_MODULE | 500 | 4.6% | 86.6% |
| _GUARD_GLOBALS_VERSION | 500 | 4.6% | 91.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 500 | 4.6% | 95.8% |
| LOAD_FAST | 340 | 3.1% | 98.9% |
| POP_TOP | 120 | 1.1% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| LOAD_ATTR_MODULE | 20 |
| LOAD_ATTR_METHOD_NO_DICT | 20 |


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
Stats gathered on: 2023-10-03
