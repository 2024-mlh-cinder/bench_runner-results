
# Pystats results

- benchmark: regex_dna
- fork: brandtbucher
- ref: break-up-float-reuse
- commit hash: 2dde229
- commit date: 2023-10-19T19:17:27-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 6,540 | 12.3% | 12.3% |  |
| LOAD_GLOBAL_MODULE | 5,380 | 10.1% | 22.4% |  |
| LOAD_FAST_LOAD_FAST | 4,500 | 8.4% | 30.8% |  |
| LOAD_GLOBAL_BUILTIN | 3,300 | 6.2% | 37.0% |  |
| RETURN_VALUE | 2,700 | 5.1% | 42.1% |  |
| RESUME_CHECK | 2,700 | 5.1% | 47.1% |  |
| POP_JUMP_IF_FALSE | 2,040 | 3.8% | 51.0% |  |
| CALL | 1,860 | 3.5% | 54.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,800 | 3.4% | 57.8% |  |
| STORE_FAST | 1,740 | 3.3% | 61.1% |  |
| PUSH_NULL | 1,560 | 2.9% | 64.0% |  |
| LOAD_ATTR_MODULE | 1,420 | 2.7% | 66.7% |  |
| NOP | 1,320 | 2.5% | 69.2% |  |
| FOR_ITER_TUPLE | 1,320 | 2.5% | 71.7% |  |
| CALL_PY_EXACT_ARGS | 1,320 | 2.5% | 74.1% |  |
| BUILD_TUPLE | 1,320 | 2.5% | 76.6% |  |
| TO_BOOL_BOOL | 1,260 | 2.4% | 79.0% |  |
| JUMP_BACKWARD | 1,260 | 2.4% | 81.3% |  |
| CALL_TYPE_1 | 1,260 | 2.4% | 83.7% |  |
| CALL_ISINSTANCE | 1,260 | 2.4% | 86.1% |  |
| BINARY_SUBSCR_DICT | 1,260 | 2.4% | 88.4% |  |
| TO_BOOL | 740 | 1.4% | 89.8% |  |
| CALL_LEN | 720 | 1.4% | 91.2% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 660 | 1.2% | 92.4% |  |
| STORE_FAST_STORE_FAST | 660 | 1.2% | 93.7% |  |
| CALL_PY_WITH_DEFAULTS | 540 | 1.0% | 94.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 1.0% | 95.7% |  |
| CALL_LIST_APPEND | 540 | 1.0% | 96.7% |  |
| LOAD_GLOBAL | 240 | 0.5% | 97.1% |  |
| LOAD_DEREF | 180 | 0.3% | 97.5% |  |
| GET_ITER | 180 | 0.3% | 97.8% |  |
| LOAD_CONST | 120 | 0.2% | 98.0% |  |
| FOR_ITER_RANGE | 120 | 0.2% | 98.3% |  |
| CALL_FUNCTION_EX | 120 | 0.2% | 98.5% |  |
| BUILD_LIST | 120 | 0.2% | 98.7% |  |
| LOAD_ATTR | 100 | 0.2% | 98.9% |  |
| COMPARE_OP | 80 | 0.2% | 99.1% |  |
| POP_TOP | 60 | 0.1% | 99.2% |  |
| POP_JUMP_IF_NONE | 60 | 0.1% | 99.3% |  |
| LOAD_FAST_CHECK | 60 | 0.1% | 99.4% |  |
| LIST_EXTEND | 60 | 0.1% | 99.5% |  |
| COPY_FREE_VARS | 60 | 0.1% | 99.6% |  |
| CALL_INTRINSIC_1 | 60 | 0.1% | 99.7% |  |
| CALL_BUILTIN_CLASS | 60 | 0.1% | 99.8% |  |
| BINARY_OP_SUBTRACT_FLOAT_LHS | 60 | 0.1% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,760 | 5.2% | 5.2% |
| LOAD_FAST CALL | 1,540 | 2.9% | 8.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,440 | 2.7% | 10.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,420 | 2.7% | 13.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,340 | 2.5% | 16.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,340 | 2.5% | 18.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,320 | 2.5% | 20.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 1,260 | 2.4% | 23.3% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 1,260 | 2.4% | 25.7% |
| POP_JUMP_IF_FALSE NOP | 1,260 | 2.4% | 28.0% |
| NOP LOAD_GLOBAL_MODULE | 1,260 | 2.4% | 30.4% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 1,260 | 2.4% | 32.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 1,260 | 2.4% | 35.1% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 1,260 | 2.4% | 37.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 1,260 | 2.4% | 39.9% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,260 | 2.4% | 42.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,260 | 2.4% | 44.6% |
| LOAD_FAST CALL_TYPE_1 | 1,260 | 2.4% | 47.0% |
| CALL_TYPE_1 LOAD_FAST_LOAD_FAST | 1,260 | 2.4% | 49.3% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,260 | 2.4% | 51.7% |
| BUILD_TUPLE BINARY_SUBSCR_DICT | 1,260 | 2.4% | 54.1% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 1,260 | 2.4% | 56.4% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,200 | 2.3% | 58.7% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 1,200 | 2.3% | 60.9% |
| RETURN_VALUE STORE_FAST | 780 | 1.5% | 62.4% |
| TO_BOOL POP_JUMP_IF_FALSE | 720 | 1.4% | 63.7% |
| STORE_FAST JUMP_BACKWARD | 720 | 1.4% | 65.1% |
| RESUME_CHECK LOAD_FAST | 720 | 1.4% | 66.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 720 | 1.4% | 67.8% |
| LOAD_FAST TO_BOOL | 720 | 1.4% | 69.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 720 | 1.4% | 70.5% |
| CALL RETURN_VALUE | 720 | 1.4% | 71.8% |
| CALL RESUME_CHECK | 720 | 1.4% | 73.2% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 660 | 1.2% | 74.4% |
| STORE_FAST_STORE_FAST LOAD_GLOBAL_MODULE | 660 | 1.2% | 75.7% |
| STORE_FAST LOAD_FAST | 660 | 1.2% | 76.9% |
| FOR_ITER_TUPLE UNPACK_SEQUENCE_TWO_TUPLE | 660 | 1.2% | 78.2% |
| RETURN_VALUE CALL_LEN | 540 | 1.0% | 79.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 540 | 1.0% | 80.2% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 540 | 1.0% | 81.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 540 | 1.0% | 82.2% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 540 | 1.0% | 83.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 1.0% | 84.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_BUILTIN | 540 | 1.0% | 85.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 540 | 1.0% | 86.3% |
| FOR_ITER_TUPLE STORE_FAST | 540 | 1.0% | 87.3% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 540 | 1.0% | 88.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS RETURN_VALUE | 540 | 1.0% | 89.3% |
| CALL_LIST_APPEND JUMP_BACKWARD | 540 | 1.0% | 90.3% |
| CALL_LEN CALL_LIST_APPEND | 540 | 1.0% | 91.3% |
| PUSH_NULL CALL | 180 | 0.3% | 91.7% |
| STORE_FAST LOAD_GLOBAL_MODULE | 160 | 0.3% | 92.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 140 | 0.3% | 92.2% |
| CALL CALL | 140 | 0.3% | 92.5% |
| PUSH_NULL LOAD_FAST | 120 | 0.2% | 92.7% |
| LOAD_GLOBAL_MODULE GET_ITER | 120 | 0.2% | 92.9% |
| LOAD_FAST CALL_LEN | 120 | 0.2% | 93.2% |
| LOAD_DEREF PUSH_NULL | 120 | 0.2% | 93.4% |
| GET_ITER FOR_ITER_TUPLE | 120 | 0.2% | 93.6% |
| CALL_LEN STORE_FAST | 120 | 0.2% | 93.8% |
| STORE_FAST LOAD_GLOBAL | 100 | 0.2% | 94.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 80 | 0.2% | 94.2% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 80 | 0.2% | 94.3% |
| LOAD_ATTR LOAD_ATTR_MODULE | 80 | 0.2% | 94.5% |
| STORE_FAST BUILD_LIST | 60 | 0.1% | 94.6% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.1% | 94.7% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.1% | 94.8% |
| PUSH_NULL LOAD_CONST | 60 | 0.1% | 94.9% |
| POP_TOP NOP | 60 | 0.1% | 95.0% |
| POP_JUMP_IF_NONE LOAD_FAST_CHECK | 60 | 0.1% | 95.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 60 | 0.1% | 95.3% |
| NOP LOAD_DEREF | 60 | 0.1% | 95.4% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 60 | 0.1% | 95.5% |
| LOAD_FAST_CHECK LOAD_FAST | 60 | 0.1% | 95.6% |
| LOAD_FAST RETURN_VALUE | 60 | 0.1% | 95.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 60 | 0.1% | 95.8% |
| LOAD_FAST GET_ITER | 60 | 0.1% | 95.9% |
| LOAD_FAST COMPARE_OP | 60 | 0.1% | 96.1% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.1% | 96.2% |
| LOAD_FAST BUILD_LIST | 60 | 0.1% | 96.3% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.1% | 96.4% |
| LOAD_CONST LOAD_FAST | 60 | 0.1% | 96.5% |
| LOAD_CONST LOAD_CONST | 60 | 0.1% | 96.6% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.1% | 96.7% |
| JUMP_BACKWARD FOR_ITER_RANGE | 60 | 0.1% | 96.8% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.1% | 97.0% |
| FOR_ITER_TUPLE LOAD_FAST_LOAD_FAST | 60 | 0.1% | 97.1% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.1% | 97.2% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.1% | 97.3% |
| COMPARE_OP POP_JUMP_IF_FALSE | 60 | 0.1% | 97.4% |
| CALL_LEN BUILD_TUPLE | 60 | 0.1% | 97.5% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.1% | 97.6% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.1% | 97.7% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.1% | 97.9% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.1% | 98.0% |
| CALL STORE_FAST | 60 | 0.1% | 98.1% |
| CALL POP_TOP | 60 | 0.1% | 98.2% |
| CALL LOAD_FAST | 60 | 0.1% | 98.3% |
| CALL CALL_LEN | 60 | 0.1% | 98.4% |
| BUILD_TUPLE RETURN_VALUE | 60 | 0.1% | 98.5% |


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
| BINARY_OP_SUBTRACT_FLOAT_LHS | 20 | 100.0% |


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

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 720 | 57.1% |
| CALL_LIST_APPEND | 540 | 42.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 1,200 | 95.2% |
| FOR_ITER_RANGE | 60 | 4.8% |


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
| LOAD_GLOBAL_BUILTIN | 2,760 | 42.2% |
| LOAD_FAST_LOAD_FAST | 1,440 | 22.0% |
| RESUME_CHECK | 720 | 11.0% |
| STORE_FAST | 660 | 10.1% |
| LOAD_ATTR_METHOD_NO_DICT | 540 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,540 | 23.5% |
| LOAD_GLOBAL_MODULE | 1,260 | 19.3% |
| CALL_TYPE_1 | 1,260 | 19.3% |
| TO_BOOL | 720 | 11.0% |
| LOAD_ATTR_METHOD_NO_DICT | 540 | 8.3% |


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
| FOR_ITER_TUPLE | 60 | 1.3% |

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
| FOR_ITER_TUPLE | 20 | 8.3% |

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
| RETURN_VALUE | 780 | 44.8% |
| FOR_ITER_TUPLE | 540 | 31.0% |
| CALL_LEN | 120 | 6.9% |
| FOR_ITER_RANGE | 60 | 3.4% |
| CALL_BUILTIN_CLASS | 60 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 720 | 41.4% |
| LOAD_FAST | 660 | 37.9% |
| LOAD_GLOBAL_MODULE | 160 | 9.2% |
| LOAD_GLOBAL | 100 | 5.7% |
| BUILD_LIST | 60 | 3.4% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 660 | 100.0% |


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
| JUMP_BACKWARD | 540 | 100.0% |


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
| JUMP_BACKWARD | 1,200 | 90.9% |
| GET_ITER | 120 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 660 | 50.0% |
| STORE_FAST | 540 | 40.9% |
| LOAD_FAST_LOAD_FAST | 60 | 4.5% |
| LOAD_GLOBAL_MODULE | 40 | 3.0% |
| LOAD_GLOBAL | 20 | 1.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,260 | 70.0% |
| LOAD_FAST | 540 | 30.0% |

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
| LOAD_GLOBAL_MODULE | 1,340 | 94.4% |
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
| NOP | 1,260 | 23.4% |
| LOAD_FAST | 1,260 | 23.4% |
| POP_JUMP_IF_FALSE | 720 | 13.4% |
| STORE_FAST_STORE_FAST | 660 | 12.3% |
| RESUME_CHECK | 540 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,340 | 24.9% |
| LOAD_GLOBAL_BUILTIN | 1,260 | 23.4% |
| LOAD_FAST_LOAD_FAST | 1,260 | 23.4% |
| CALL_ISINSTANCE | 1,260 | 23.4% |
| GET_ITER | 120 | 2.2% |


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
| FOR_ITER_TUPLE | 660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 660 | 100.0% |


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
|          hit |         1440 | 100.0% |


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
|          hit |         8680 | 97.3% |

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
|          hit |          660 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 21,360 | 40.1% |
| Not specialized | 6,400 | 12.0% |
| Specialized | 25,520 | 47.9% |

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
| Allocations | 4,847,520 | 99.9% |
| Allocations to 512 bytes | 4,831,380 | 99.6% |
| Allocations to 4 kbytes | 13,380 | 0.3% |
| Allocations over 4 kbytes | 2,760 | 0.1% |
| Frees | 5,875,200 |  |
| New values | 0 |  |
| Interpreter increfs | 28,840 | 0.1% |
| Interpreter decrefs | 30,660 | 0.1% |
| Increfs | 21,565,780 | 99.9% |
| Decrefs | 26,412,260 | 99.9% |
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
