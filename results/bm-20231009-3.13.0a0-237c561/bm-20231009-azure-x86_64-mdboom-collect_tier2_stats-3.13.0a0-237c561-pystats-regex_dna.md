
# Pystats results

- benchmark: regex_dna
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 5,700 | 12.4% | 12.4% |  |
| LOAD_GLOBAL_MODULE | 4,540 | 9.8% | 22.2% |  |
| LOAD_FAST_LOAD_FAST | 3,660 | 7.9% | 30.1% |  |
| LOAD_GLOBAL_BUILTIN | 2,960 | 6.4% | 36.5% |  |
| RETURN_VALUE | 2,700 | 5.9% | 42.4% |  |
| RESUME_CHECK | 2,700 | 5.9% | 48.2% |  |
| POP_JUMP_IF_FALSE | 2,040 | 4.4% | 52.7% |  |
| CALL | 1,860 | 4.0% | 56.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,460 | 3.2% | 59.9% |  |
| STORE_FAST | 1,400 | 3.0% | 62.9% |  |
| NOP | 1,320 | 2.9% | 65.8% |  |
| BUILD_TUPLE | 1,320 | 2.9% | 68.6% |  |
| CALL_PY_EXACT_ARGS | 1,320 | 2.9% | 71.5% |  |
| BINARY_SUBSCR_DICT | 1,260 | 2.7% | 74.2% |  |
| CALL_ISINSTANCE | 1,260 | 2.7% | 76.9% |  |
| CALL_TYPE_1 | 1,260 | 2.7% | 79.7% |  |
| TO_BOOL_BOOL | 1,260 | 2.7% | 82.4% |  |
| ENTER_EXECUTOR | 960 | 2.1% | 84.5% |  |
| TO_BOOL | 740 | 1.6% | 86.1% |  |
| PUSH_NULL | 720 | 1.6% | 87.6% |  |
| CALL_LEN | 720 | 1.6% | 89.2% |  |
| LOAD_ATTR_MODULE | 580 | 1.3% | 90.5% |  |
| CALL_LIST_APPEND | 540 | 1.2% | 91.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 1.2% | 92.8% |  |
| CALL_PY_WITH_DEFAULTS | 540 | 1.2% | 94.0% |  |
| FOR_ITER_TUPLE | 360 | 0.8% | 94.8% |  |
| JUMP_BACKWARD | 340 | 0.7% | 95.5% |  |
| LOAD_GLOBAL | 240 | 0.5% | 96.0% |  |
| GET_ITER | 180 | 0.4% | 96.4% |  |
| LOAD_DEREF | 180 | 0.4% | 96.8% |  |
| STORE_FAST_STORE_FAST | 160 | 0.3% | 97.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 160 | 0.3% | 97.5% |  |
| BUILD_LIST | 120 | 0.3% | 97.7% |  |
| CALL_FUNCTION_EX | 120 | 0.3% | 98.0% |  |
| LOAD_CONST | 120 | 0.3% | 98.3% |  |
| FOR_ITER_RANGE | 120 | 0.3% | 98.5% |  |
| LOAD_ATTR | 100 | 0.2% | 98.7% |  |
| COMPARE_OP | 80 | 0.2% | 98.9% |  |
| POP_TOP | 60 | 0.1% | 99.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.1% | 99.2% |  |
| COPY_FREE_VARS | 60 | 0.1% | 99.3% |  |
| LIST_EXTEND | 60 | 0.1% | 99.4% |  |
| LOAD_FAST_CHECK | 60 | 0.1% | 99.6% |  |
| POP_JUMP_IF_NONE | 60 | 0.1% | 99.7% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.1% | 99.8% |  |
| CALL_BUILTIN_CLASS | 60 | 0.1% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,760 | 6.0% | 6.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,340 | 2.9% | 8.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,320 | 2.9% | 11.7% |
| NOP LOAD_GLOBAL_MODULE | 1,260 | 2.7% | 14.5% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 1,260 | 2.7% | 17.2% |
| BUILD_TUPLE BINARY_SUBSCR_DICT | 1,260 | 2.7% | 19.9% |
| LOAD_FAST CALL_TYPE_1 | 1,260 | 2.7% | 22.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,260 | 2.7% | 25.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,260 | 2.7% | 28.1% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 1,260 | 2.7% | 30.9% |
| POP_JUMP_IF_FALSE NOP | 1,260 | 2.7% | 33.6% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 1,260 | 2.7% | 36.3% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,260 | 2.7% | 39.1% |
| CALL_TYPE_1 LOAD_FAST_LOAD_FAST | 1,260 | 2.7% | 41.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,260 | 2.7% | 44.5% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 1,260 | 2.7% | 47.2% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 1,260 | 2.7% | 50.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 1,260 | 2.7% | 52.7% |
| LOAD_FAST CALL | 1,040 | 2.3% | 55.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 940 | 2.0% | 57.0% |
| RETURN_VALUE STORE_FAST | 780 | 1.7% | 58.7% |
| TO_BOOL POP_JUMP_IF_FALSE | 720 | 1.6% | 60.3% |
| CALL RETURN_VALUE | 720 | 1.6% | 61.8% |
| CALL RESUME_CHECK | 720 | 1.6% | 63.4% |
| LOAD_FAST TO_BOOL | 720 | 1.6% | 64.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 720 | 1.6% | 66.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 720 | 1.6% | 68.1% |
| RESUME_CHECK LOAD_FAST | 720 | 1.6% | 69.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 580 | 1.3% | 70.9% |
| RETURN_VALUE CALL_LEN | 540 | 1.2% | 72.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 1.2% | 73.2% |
| STORE_FAST ENTER_EXECUTOR | 540 | 1.2% | 74.4% |
| CALL_LEN CALL_LIST_APPEND | 540 | 1.2% | 75.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS RETURN_VALUE | 540 | 1.2% | 76.7% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 540 | 1.2% | 77.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 540 | 1.2% | 79.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 540 | 1.2% | 80.2% |
| ENTER_EXECUTOR CALL | 500 | 1.1% | 81.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 500 | 1.1% | 82.4% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 380 | 0.8% | 83.2% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 360 | 0.8% | 84.0% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 340 | 0.7% | 84.7% |
| STORE_FAST LOAD_FAST | 320 | 0.7% | 85.4% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 240 | 0.5% | 86.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 200 | 0.4% | 86.4% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 200 | 0.4% | 86.8% |
| FOR_ITER_TUPLE STORE_FAST | 200 | 0.4% | 87.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_BUILTIN | 200 | 0.4% | 87.7% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 200 | 0.4% | 88.1% |
| PUSH_NULL CALL | 180 | 0.4% | 88.5% |
| STORE_FAST JUMP_BACKWARD | 180 | 0.4% | 88.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 160 | 0.3% | 89.3% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_MODULE | 160 | 0.3% | 89.6% |
| CALL_LIST_APPEND JUMP_BACKWARD | 160 | 0.3% | 89.9% |
| FOR_ITER_TUPLE UNPACK_SEQUENCE_TWO_TUPLE | 160 | 0.3% | 90.3% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 160 | 0.3% | 90.6% |
| CALL CALL | 140 | 0.3% | 90.9% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 140 | 0.3% | 91.2% |
| GET_ITER FOR_ITER_TUPLE | 120 | 0.3% | 91.5% |
| PUSH_NULL LOAD_FAST | 120 | 0.3% | 91.8% |
| LOAD_DEREF PUSH_NULL | 120 | 0.3% | 92.0% |
| LOAD_FAST CALL_LEN | 120 | 0.3% | 92.3% |
| CALL_LEN STORE_FAST | 120 | 0.3% | 92.5% |
| LOAD_GLOBAL_MODULE GET_ITER | 120 | 0.3% | 92.8% |
| STORE_FAST LOAD_GLOBAL | 100 | 0.2% | 93.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 80 | 0.2% | 93.2% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 80 | 0.2% | 93.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 80 | 0.2% | 93.5% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.1% | 93.7% |
| NOP LOAD_DEREF | 60 | 0.1% | 93.8% |
| POP_TOP NOP | 60 | 0.1% | 93.9% |
| PUSH_NULL LOAD_CONST | 60 | 0.1% | 94.1% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.1% | 94.2% |
| BUILD_LIST LOAD_DEREF | 60 | 0.1% | 94.3% |
| BUILD_LIST STORE_FAST | 60 | 0.1% | 94.5% |
| BUILD_TUPLE RETURN_VALUE | 60 | 0.1% | 94.6% |
| CALL POP_TOP | 60 | 0.1% | 94.7% |
| CALL LOAD_FAST | 60 | 0.1% | 94.8% |
| CALL STORE_FAST | 60 | 0.1% | 95.0% |
| CALL CALL_LEN | 60 | 0.1% | 95.1% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.1% | 95.2% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.1% | 95.4% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.1% | 95.5% |
| COMPARE_OP POP_JUMP_IF_FALSE | 60 | 0.1% | 95.6% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.1% | 95.8% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 60 | 0.1% | 95.9% |
| JUMP_BACKWARD FOR_ITER_RANGE | 60 | 0.1% | 96.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.1% | 96.1% |
| LOAD_CONST LOAD_CONST | 60 | 0.1% | 96.3% |
| LOAD_CONST LOAD_FAST | 60 | 0.1% | 96.4% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.1% | 96.5% |
| LOAD_FAST GET_ITER | 60 | 0.1% | 96.7% |
| LOAD_FAST RETURN_VALUE | 60 | 0.1% | 96.8% |
| LOAD_FAST BUILD_LIST | 60 | 0.1% | 96.9% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.1% | 97.1% |
| LOAD_FAST COMPARE_OP | 60 | 0.1% | 97.2% |
| LOAD_FAST POP_JUMP_IF_NONE | 60 | 0.1% | 97.3% |
| LOAD_FAST_CHECK LOAD_FAST | 60 | 0.1% | 97.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 60 | 0.1% | 97.6% |
| POP_JUMP_IF_NONE LOAD_FAST_CHECK | 60 | 0.1% | 97.7% |


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
| LOAD_ATTR_MODULE | 580 | 80.6% |
| LOAD_DEREF | 120 | 16.7% |
| LOAD_ATTR | 20 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 360 | 50.0% |
| CALL | 180 | 25.0% |
| LOAD_FAST | 120 | 16.7% |
| LOAD_CONST | 60 | 8.3% |


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
| BUILD_TUPLE | 60 | 2.2% |

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
| LOAD_FAST | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


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
| LOAD_FAST | 1,040 | 55.9% |
| ENTER_EXECUTOR | 500 | 26.9% |
| PUSH_NULL | 180 | 9.7% |
| CALL | 140 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 720 | 38.7% |
| RESUME_CHECK | 720 | 38.7% |
| CALL | 140 | 7.5% |
| POP_TOP | 60 | 3.2% |
| LOAD_FAST | 60 | 3.2% |


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
| CALL | 500 | 52.1% |
| CALL_PY_WITH_DEFAULTS | 340 | 35.4% |
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
| LOAD_CONST | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |
| RESUME_CHECK | 60 | 33.3% |

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
| LOAD_GLOBAL_BUILTIN | 2,760 | 48.4% |
| LOAD_FAST_LOAD_FAST | 940 | 16.5% |
| RESUME_CHECK | 720 | 12.6% |
| LOAD_ATTR_METHOD_NO_DICT | 540 | 9.5% |
| STORE_FAST | 320 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_TYPE_1 | 1,260 | 22.1% |
| LOAD_GLOBAL_MODULE | 1,260 | 22.1% |
| CALL | 1,040 | 18.2% |
| TO_BOOL | 720 | 12.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 9.5% |


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
| CALL_TYPE_1 | 1,260 | 34.4% |
| LOAD_GLOBAL_MODULE | 1,260 | 34.4% |
| LOAD_ATTR_METHOD_NO_DICT | 720 | 19.7% |
| PUSH_NULL | 360 | 9.8% |
| ENTER_EXECUTOR | 60 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 1,260 | 34.4% |
| CALL_PY_EXACT_ARGS | 1,260 | 34.4% |
| LOAD_FAST | 940 | 25.7% |
| CALL_PY_WITH_DEFAULTS | 200 | 5.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 100 | 41.7% |
| RETURN_VALUE | 40 | 16.7% |
| RESUME_CHECK | 40 | 16.7% |
| ENTER_EXECUTOR | 20 | 8.3% |
| LOAD_FAST | 20 | 8.3% |

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
| BUILD_LIST | 60 | 4.3% |
| CALL | 60 | 4.3% |

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
| ENTER_EXECUTOR | 340 | 63.0% |
| LOAD_FAST_LOAD_FAST | 200 | 37.0% |

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
| GET_ITER | 60 | 50.0% |
| JUMP_BACKWARD | 60 | 50.0% |

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
| RETURN_VALUE | 1,260 | 86.3% |
| LOAD_FAST | 200 | 13.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 720 | 49.3% |
| LOAD_FAST | 540 | 37.0% |
| LOAD_GLOBAL_BUILTIN | 200 | 13.7% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 500 | 86.2% |
| LOAD_ATTR | 80 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 580 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,340 | 45.3% |
| LOAD_GLOBAL_MODULE | 1,260 | 42.6% |
| LOAD_ATTR_METHOD_NO_DICT | 200 | 6.8% |
| LOAD_GLOBAL | 80 | 2.7% |
| LOAD_FAST | 40 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,760 | 93.2% |
| LOAD_GLOBAL_MODULE | 200 | 6.8% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 1,260 | 27.8% |
| LOAD_FAST | 1,260 | 27.8% |
| POP_JUMP_IF_FALSE | 720 | 15.9% |
| RESUME_CHECK | 540 | 11.9% |
| LOAD_GLOBAL_BUILTIN | 200 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,260 | 27.8% |
| CALL_ISINSTANCE | 1,260 | 27.8% |
| LOAD_GLOBAL_BUILTIN | 1,260 | 27.8% |
| LOAD_ATTR_MODULE | 500 | 11.0% |
| GET_ITER | 120 | 2.6% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,320 | 48.9% |
| CALL | 720 | 26.7% |
| CALL_PY_WITH_DEFAULTS | 540 | 20.0% |
| CALL_FUNCTION_EX | 60 | 2.2% |
| COPY_FREE_VARS | 60 | 2.2% |

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
|          hit | 1,260 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,620 | 20.0% |
|          hit | 6,240 | 77.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 41.7% |
| Failure | 140 | 58.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 60 | 42.9% |
| cfunc noargs | 60 | 42.9% |
| meth descr method fastcall keywords | 20 | 14.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 75.0% |

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
|---|---:|---:|
|          hit | 480 | 100.0% |


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
|     deferred | 20 | 0.9% |
|          hit | 2,040 | 95.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.3% |
|          hit | 7,500 | 96.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 100.0% |
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

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 720 | 36.0% |
|          hit | 1,260 | 63.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 20 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 160 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 18,960 | 41.1% |
| Not specialized | 5,480 | 11.9% |
| Specialized | 21,700 | 47.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 1,620 | 66.4% |
| TO_BOOL | 720 | 29.5% |
| COMPARE_OP | 60 | 2.5% |
| LOAD_ATTR | 20 | 0.8% |
| LOAD_GLOBAL | 20 | 0.8% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| NOP | 0 | 0.0% |


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
| Frame objects created | 0 | 0.0% |
| Frames pushed | 2,700 | 100.0% |


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
| Interpreter increfs | 24,080 | 0.1% |
| Interpreter decrefs | 28,240 | 0.1% |
| Increfs | 21,571,540 | 99.9% |
| Decrefs | 26,415,680 | 99.9% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 20 |  |
| Method cache misses | 0 |  |
| Method cache collisions | 0 |  |
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

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 40 |  |
| Traces created | 40 | 100.0% |
| Traces executed | 960 |  |
| Uops executed | 19,840 | 20.67 |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
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
| <= 16 | 0 | 0.0% |
| <= 32 | 40 | 100.0% |


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
| <= 16 | 0 | 0.0% |
| <= 32 | 40 | 100.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 120 | 12.5% |
| <= 16 | 0 | 0.0% |
| <= 32 | 840 | 87.5% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 4,780 | 24.1% | 24.1% |  |
| LOAD_FAST | 2,520 | 12.7% | 36.8% |  |
| STORE_FAST | 1,340 | 6.8% | 43.5% |  |
| _GUARD_GLOBALS_VERSION | 1,180 | 5.9% | 49.5% |  |
| _EXIT_TRACE | 960 | 4.8% | 54.3% |  |
| _ITER_CHECK_TUPLE | 960 | 4.8% | 59.2% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 960 | 4.8% | 64.0% |  |
| _POP_JUMP_IF_TRUE | 960 | 4.8% | 68.9% |  |
| PUSH_NULL | 840 | 4.2% | 73.1% |  |
| _LOAD_GLOBAL_MODULE | 840 | 4.2% | 77.3% |  |
| _CHECK_ATTR_MODULE | 840 | 4.2% | 81.6% |  |
| _LOAD_ATTR_MODULE | 840 | 4.2% | 85.8% |  |
| _ITER_NEXT_TUPLE | 840 | 4.2% | 90.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 500 | 2.5% | 92.5% |  |
| _GUARD_BUILTINS_VERSION | 340 | 1.7% | 94.3% |  |
| _LOAD_GLOBAL_BUILTINS | 340 | 1.7% | 96.0% |  |
| _GUARD_TYPE_VERSION | 340 | 1.7% | 97.7% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 340 | 1.7% | 99.4% |  |
| POP_TOP | 120 | 0.6% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 20 |
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
Stats gathered on: 2023-10-09
