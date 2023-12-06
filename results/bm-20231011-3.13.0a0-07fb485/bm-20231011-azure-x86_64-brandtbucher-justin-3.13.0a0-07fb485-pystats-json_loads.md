
# Pystats results

- benchmark: json_loads
- fork: brandtbucher
- ref: justin
- commit hash: 07fb485
- commit date: 2023-10-11T15:47:19+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 8,287,260 | 22.7% | 22.7% |  |
| POP_JUMP_IF_NOT_NONE | 2,764,800 | 7.6% | 30.3% |  |
| CALL | 2,313,260 | 6.3% | 36.6% |  |
| LOAD_FAST_LOAD_FAST | 1,843,200 | 5.1% | 41.7% |  |
| RESUME_CHECK | 1,390,140 | 3.8% | 45.5% |  |
| RETURN_VALUE | 1,382,460 | 3.8% | 49.3% |  |
| POP_JUMP_IF_FALSE | 1,382,460 | 3.8% | 53.1% |  |
| LOAD_GLOBAL_BUILTIN | 1,382,460 | 3.8% | 56.9% |  |
| LOAD_CONST | 1,382,460 | 3.8% | 60.7% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,382,400 | 3.8% | 64.5% |  |
| PUSH_NULL | 1,367,340 | 3.7% | 68.2% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 921,600 | 2.5% | 70.7% |  |
| TO_BOOL_BOOL | 921,600 | 2.5% | 73.3% |  |
| STORE_FAST_STORE_FAST | 921,600 | 2.5% | 75.8% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 921,600 | 2.5% | 78.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 921,600 | 2.5% | 80.8% |  |
| LOAD_GLOBAL_MODULE | 906,340 | 2.5% | 83.3% |  |
| STORE_FAST | 468,840 | 1.3% | 84.6% |  |
| POP_TOP | 468,540 | 1.3% | 85.9% |  |
| TO_BOOL | 460,920 | 1.3% | 87.2% |  |
| NOP | 460,860 | 1.3% | 88.4% |  |
| COMPARE_OP_INT | 460,860 | 1.3% | 89.7% |  |
| POP_JUMP_IF_TRUE | 460,800 | 1.3% | 90.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 460,800 | 1.3% | 92.2% |  |
| CALL_PY_WITH_DEFAULTS | 460,800 | 1.3% | 93.5% |  |
| CALL_LEN | 460,800 | 1.3% | 94.7% |  |
| CALL_KW | 460,800 | 1.3% | 96.0% |  |
| CALL_ISINSTANCE | 460,800 | 1.3% | 97.3% |  |
| BUILD_TUPLE | 460,800 | 1.3% | 98.5% |  |
| LOAD_ATTR_MODULE | 445,540 | 1.2% | 99.7% |  |
| EXTENDED_ARG | 30,720 | 0.1% | 99.8% |  |
| ENTER_EXECUTOR | 30,720 | 0.1% | 99.9% |  |
| GET_ITER | 7,740 | 0.0% | 99.9% |  |
| RETURN_CONST | 7,680 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 7,680 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 7,680 | 0.0% | 100.0% |  |
| LOAD_DEREF | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 80 | 0.0% | 100.0% |  |
| LOAD_ATTR | 60 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
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
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 2,764,800 | 7.6% | 7.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,764,800 | 7.6% | 15.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 1,382,400 | 3.8% | 18.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 921,660 | 2.5% | 21.5% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 921,600 | 2.5% | 24.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 921,600 | 2.5% | 26.5% |
| LOAD_FAST_LOAD_FAST CALL | 921,600 | 2.5% | 29.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 921,600 | 2.5% | 31.6% |
| LOAD_CONST CALL | 921,600 | 2.5% | 34.1% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_FAST | 921,600 | 2.5% | 36.6% |
| CALL LOAD_ATTR_METHOD_NO_DICT | 921,600 | 2.5% | 39.2% |
| PUSH_NULL LOAD_FAST | 906,300 | 2.5% | 41.6% |
| RESUME_CHECK LOAD_FAST | 468,480 | 1.3% | 42.9% |
| STORE_FAST LOAD_FAST | 461,100 | 1.3% | 44.2% |
| LOAD_FAST PUSH_NULL | 460,980 | 1.3% | 45.5% |
| LOAD_FAST RETURN_VALUE | 460,860 | 1.3% | 46.7% |
| LOAD_FAST LOAD_CONST | 460,860 | 1.3% | 48.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 460,860 | 1.3% | 49.2% |
| TO_BOOL POP_JUMP_IF_TRUE | 460,800 | 1.3% | 50.5% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 460,800 | 1.3% | 51.8% |
| STORE_FAST_STORE_FAST LOAD_FAST | 460,800 | 1.3% | 53.0% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 460,800 | 1.3% | 54.3% |
| RETURN_VALUE RETURN_VALUE | 460,800 | 1.3% | 55.6% |
| RETURN_VALUE POP_TOP | 460,800 | 1.3% | 56.8% |
| RESUME_CHECK NOP | 460,800 | 1.3% | 58.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 460,800 | 1.3% | 59.4% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 460,800 | 1.3% | 60.6% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_MODULE | 460,800 | 1.3% | 61.9% |
| NOP LOAD_FAST | 460,800 | 1.3% | 63.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_WITH_VALUES | 460,800 | 1.3% | 64.4% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 460,800 | 1.3% | 65.7% |
| LOAD_FAST_LOAD_FAST PUSH_NULL | 460,800 | 1.3% | 66.9% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 460,800 | 1.3% | 68.2% |
| LOAD_FAST TO_BOOL | 460,800 | 1.3% | 69.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 460,800 | 1.3% | 70.7% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 460,800 | 1.3% | 72.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 460,800 | 1.3% | 73.3% |
| LOAD_FAST CALL_PY_WITH_DEFAULTS | 460,800 | 1.3% | 74.5% |
| LOAD_FAST CALL_LEN | 460,800 | 1.3% | 75.8% |
| LOAD_CONST CALL_KW | 460,800 | 1.3% | 77.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 460,800 | 1.3% | 78.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 460,800 | 1.3% | 79.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 460,800 | 1.3% | 80.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 460,800 | 1.3% | 82.1% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 460,800 | 1.3% | 83.4% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 460,800 | 1.3% | 84.6% |
| CALL_METHOD_DESCRIPTOR_FAST LOAD_CONST | 460,800 | 1.3% | 85.9% |
| CALL_LEN COMPARE_OP_INT | 460,800 | 1.3% | 87.1% |
| CALL_KW RESUME_CHECK | 460,800 | 1.3% | 88.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 460,800 | 1.3% | 89.7% |
| CALL UNPACK_SEQUENCE_TWO_TUPLE | 460,800 | 1.3% | 90.9% |
| CALL TO_BOOL_BOOL | 460,800 | 1.3% | 92.2% |
| CALL RESUME_CHECK | 460,800 | 1.3% | 93.5% |
| BUILD_TUPLE RETURN_VALUE | 460,800 | 1.3% | 94.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 445,500 | 1.2% | 95.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 445,480 | 1.2% | 97.2% |
| LOAD_FAST CALL | 445,460 | 1.2% | 98.4% |
| POP_TOP LOAD_GLOBAL_MODULE | 437,760 | 1.2% | 99.6% |
| POP_TOP EXTENDED_ARG | 23,040 | 0.1% | 99.7% |
| EXTENDED_ARG ENTER_EXECUTOR | 23,040 | 0.1% | 99.7% |
| ENTER_EXECUTOR CALL | 22,980 | 0.1% | 99.8% |
| LOAD_FAST GET_ITER | 7,740 | 0.0% | 99.8% |
| CALL POP_TOP | 7,740 | 0.0% | 99.8% |
| STORE_FAST LOAD_GLOBAL_MODULE | 7,680 | 0.0% | 99.8% |
| RETURN_CONST INTERPRETER_EXIT | 7,680 | 0.0% | 99.9% |
| POP_TOP ENTER_EXECUTOR | 7,680 | 0.0% | 99.9% |
| GET_ITER EXTENDED_ARG | 7,680 | 0.0% | 99.9% |
| FOR_ITER_TUPLE STORE_FAST | 7,680 | 0.0% | 99.9% |
| EXTENDED_ARG FOR_ITER_TUPLE | 7,680 | 0.0% | 99.9% |
| ENTER_EXECUTOR RETURN_CONST | 7,680 | 0.0% | 100.0% |
| CACHE RESUME_CHECK | 7,680 | 0.0% | 100.0% |
| CALL CALL | 1,380 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| TO_BOOL TO_BOOL | 120 | 0.0% | 100.0% |
| STORE_FAST LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_DEREF STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 60 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_FAST | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 60 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.0% | 100.0% |
| LOAD_CONST COMPARE_OP_INT | 40 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |


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
| RESUME_CHECK | 7,680 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,740 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 7,680 | 99.2% |
| FOR_ITER_RANGE | 60 | 0.8% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 7,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 460,800 | 100.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,800 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 460,800 | 98.3% |
| CALL | 7,740 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 437,760 | 93.4% |
| EXTENDED_ARG | 23,040 | 4.9% |
| ENTER_EXECUTOR | 7,680 | 1.6% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,980 | 33.7% |
| LOAD_FAST_LOAD_FAST | 460,800 | 33.7% |
| LOAD_ATTR_MODULE | 445,480 | 32.6% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 906,300 | 66.3% |
| LOAD_FAST_LOAD_FAST | 460,800 | 33.7% |
| CALL | 240 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,860 | 33.3% |
| RETURN_VALUE | 460,800 | 33.3% |
| BUILD_TUPLE | 460,800 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 460,800 | 33.3% |
| RETURN_VALUE | 460,800 | 33.3% |
| POP_TOP | 460,800 | 33.3% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 20 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,800 | 100.0% |
| TO_BOOL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 460,800 | 100.0% |
| TO_BOOL | 120 | 0.0% |


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

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 460,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 460,800 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 921,600 | 39.8% |
| LOAD_CONST | 921,600 | 39.8% |
| LOAD_FAST | 445,460 | 19.3% |
| ENTER_EXECUTOR | 22,980 | 1.0% |
| CALL | 1,380 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 921,600 | 39.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 460,800 | 19.9% |
| TO_BOOL_BOOL | 460,800 | 19.9% |
| RESUME_CHECK | 460,800 | 19.9% |
| POP_TOP | 7,740 | 0.3% |


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
| LOAD_CONST | 460,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 460,800 | 100.0% |


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
| EXTENDED_ARG | 23,040 | 75.0% |
| POP_TOP | 7,680 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 22,980 | 74.8% |
| RETURN_CONST | 7,680 | 25.0% |
| LOAD_FAST | 60 | 0.2% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 23,040 | 75.0% |
| GET_ITER | 7,680 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 23,040 | 75.0% |
| FOR_ITER_TUPLE | 7,680 | 25.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 40 | 66.7% |
| PUSH_NULL | 20 | 33.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,860 | 33.3% |
| LOAD_ATTR_METHOD_NO_DICT | 460,800 | 33.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 460,800 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 921,600 | 66.7% |
| CALL_KW | 460,800 | 33.3% |
| COMPARE_OP_INT | 40 | 0.0% |
| COMPARE_OP | 20 | 0.0% |


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
| POP_JUMP_IF_NOT_NONE | 2,764,800 | 33.4% |
| POP_JUMP_IF_FALSE | 1,382,400 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 921,660 | 11.1% |
| PUSH_NULL | 906,300 | 10.9% |
| RESUME_CHECK | 468,480 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 2,764,800 | 33.4% |
| LOAD_GLOBAL_BUILTIN | 921,600 | 11.1% |
| PUSH_NULL | 460,980 | 5.6% |
| RETURN_VALUE | 460,860 | 5.6% |
| LOAD_CONST | 460,860 | 5.6% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 460,800 | 25.0% |
| PUSH_NULL | 460,800 | 25.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 460,800 | 25.0% |
| LOAD_ATTR_INSTANCE_VALUE | 460,800 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 921,600 | 50.0% |
| PUSH_NULL | 460,800 | 25.0% |
| BUILD_TUPLE | 460,800 | 25.0% |


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
| TO_BOOL_BOOL | 921,600 | 66.7% |
| COMPARE_OP_INT | 460,860 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,382,400 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,764,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,764,800 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 460,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 460,800 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,680 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 460,800 | 98.3% |
| FOR_ITER_TUPLE | 7,680 | 1.6% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| FOR_ITER_RANGE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 461,100 | 98.3% |
| LOAD_GLOBAL_MODULE | 7,680 | 1.6% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 921,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 460,800 | 50.0% |
| LOAD_FAST | 460,800 | 50.0% |


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
| LOAD_GLOBAL_BUILTIN | 460,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 460,800 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 460,800 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 921,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 460,800 | 50.0% |
| LOAD_CONST | 460,800 | 50.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 460,800 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 460,800 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 460,860 | 100.0% |


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
| EXTENDED_ARG | 7,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,680 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 460,800 | 100.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 921,600 | 66.7% |
| LOAD_FAST | 460,800 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 921,600 | 66.7% |
| LOAD_CONST | 460,800 | 33.3% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 460,800 | 50.0% |
| LOAD_FAST | 460,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 460,800 | 50.0% |
| LOAD_FAST | 460,800 | 50.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 445,500 | 100.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 445,480 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 921,600 | 66.7% |
| RESUME_CHECK | 460,800 | 33.3% |
| POP_JUMP_IF_FALSE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 921,660 | 66.7% |
| CALL_ISINSTANCE | 460,800 | 33.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 460,800 | 50.8% |
| POP_TOP | 437,760 | 48.3% |
| STORE_FAST | 7,680 | 0.8% |
| RESUME_CHECK | 40 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 460,800 | 50.8% |
| LOAD_ATTR_MODULE | 445,500 | 49.2% |
| LOAD_ATTR | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 460,800 | 33.1% |
| CALL_KW | 460,800 | 33.1% |
| CALL | 460,800 | 33.1% |
| CACHE | 7,680 | 0.6% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 468,480 | 33.7% |
| NOP | 460,800 | 33.1% |
| LOAD_GLOBAL_BUILTIN | 460,800 | 33.1% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 460,800 | 50.0% |
| CALL | 460,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 921,600 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 460,800 | 50.0% |
| CALL | 460,800 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 921,600 | 100.0% |


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
| specialization.deferred |       460800 | 33.3% |
|          hit |       921600 | 66.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 120 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 120 | 100.0% |


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
| specialization.deferred |      2311860 | 50.1% |
|          hit |      2304060 | 49.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 1.4% |
| Failure | 1,380 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 800 | 58.0% |
| cmethod | 240 | 17.4% |
| other | 160 | 11.6% |
| meth descr varargs | 120 | 8.7% |
| cfunc noargs | 60 | 4.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       460860 | 100.0% |

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
|          hit |         7740 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |      3225700 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |      2304160 | 100.0% |

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
|          hit |       921600 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 17,588,940 | 48.2% |
| Not specialized | 7,382,420 | 20.2% |
| Specialized | 11,505,200 | 31.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 2,311,860 | 83.4% |
| TO_BOOL | 460,800 | 16.6% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 7,680 | 0.6% |
| Calls to Python functions inlined | 1,382,460 | 99.4% |
| Calls via PyEval_EvalFrame (total) | 7,680 | 0.6% |
| Calls via PyEval_EvalFrame (vector) | 7,680 | 0.6% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 7,680 | 0.6% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 1,390,140 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 4,454,500 | 7.8% |
| Frees to freelist | 4,454,460 |  |
| Allocations | 52,999,820 | 92.2% |
| Allocations to 512 bytes | 52,078,220 | 90.6% |
| Allocations to 4 kbytes | 921,600 | 1.6% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 54,535,800 |  |
| New values | 0 |  |
| Interpreter increfs | 17,687,980 | 17.2% |
| Interpreter decrefs | 19,846,140 | 12.8% |
| Increfs | 84,863,980 | 82.8% |
| Decrefs | 135,552,080 | 87.2% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 14 |  |
| Method cache misses | 6 |  |
| Method cache collisions | 6 |  |
| Method cache dunder hits | 0 |  |
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
Stats gathered on: 2023-10-12
