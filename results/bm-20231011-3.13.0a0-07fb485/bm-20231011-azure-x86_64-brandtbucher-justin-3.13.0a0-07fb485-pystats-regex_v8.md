
# Pystats results

- benchmark: regex_v8
- fork: brandtbucher
- ref: justin
- commit hash: 07fb485
- commit date: 2023-10-11T15:47:19+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_CONST | 15,298,640 | 20.6% | 20.6% |  |
| LOAD_GLOBAL_MODULE | 9,650,120 | 13.0% | 33.6% |  |
| BINARY_SUBSCR_LIST_INT | 6,801,640 | 9.2% | 42.8% |  |
| POP_TOP | 6,203,820 | 8.4% | 51.2% |  |
| CALL | 6,197,640 | 8.4% | 59.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,562,140 | 7.5% | 67.0% |  |
| LOAD_FAST | 3,905,040 | 5.3% | 72.3% |  |
| ENTER_EXECUTOR | 3,315,840 | 4.5% | 76.8% |  |
| LOAD_GLOBAL_BUILTIN | 1,583,580 | 2.1% | 78.9% |  |
| LOAD_FAST_LOAD_FAST | 1,568,640 | 2.1% | 81.0% |  |
| RETURN_VALUE | 1,490,760 | 2.0% | 83.0% |  |
| POP_JUMP_IF_FALSE | 1,484,400 | 2.0% | 85.0% |  |
| RESUME_CHECK | 1,478,520 | 2.0% | 87.0% |  |
| LOAD_ATTR_MODULE | 915,760 | 1.2% | 88.3% |  |
| CALL_PY_EXACT_ARGS | 825,120 | 1.1% | 89.4% |  |
| NOP | 645,900 | 0.9% | 90.3% |  |
| CALL_TYPE_1 | 645,840 | 0.9% | 91.1% |  |
| BUILD_TUPLE | 645,840 | 0.9% | 92.0% |  |
| BINARY_SUBSCR_DICT | 645,840 | 0.9% | 92.9% |  |
| TO_BOOL_BOOL | 642,000 | 0.9% | 93.7% |  |
| CALL_ISINSTANCE | 642,000 | 0.9% | 94.6% |  |
| PUSH_NULL | 550,620 | 0.7% | 95.3% |  |
| STORE_FAST | 384,440 | 0.5% | 95.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 287,280 | 0.4% | 96.3% |  |
| TO_BOOL | 280,860 | 0.4% | 96.6% |  |
| UNPACK_EX | 280,800 | 0.4% | 97.0% |  |
| TO_BOOL_LIST | 280,800 | 0.4% | 97.4% |  |
| STORE_FAST_STORE_FAST | 280,800 | 0.4% | 97.8% |  |
| IS_OP | 280,800 | 0.4% | 98.1% |  |
| IMPORT_NAME | 280,800 | 0.4% | 98.5% |  |
| CALL_KW | 280,800 | 0.4% | 98.9% |  |
| CALL_PY_WITH_DEFAULTS | 276,720 | 0.4% | 99.3% |  |
| POP_JUMP_IF_NOT_NONE | 95,760 | 0.1% | 99.4% |  |
| POP_JUMP_IF_NONE | 95,760 | 0.1% | 99.5% |  |
| INTERPRETER_EXIT | 95,760 | 0.1% | 99.7% |  |
| LOAD_ATTR | 88,440 | 0.1% | 99.8% |  |
| EXTENDED_ARG | 65,520 | 0.1% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 43,920 | 0.1% | 99.9% |  |
| FOR_ITER_RANGE | 15,420 | 0.0% | 100.0% |  |
| GET_ITER | 14,940 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 14,940 | 0.0% | 100.0% |  |
| RETURN_CONST | 2,880 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 540 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 100 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_MODULE LOAD_CONST | 6,801,640 | 9.2% | 9.2% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 6,801,640 | 9.2% | 18.3% |
| CALL POP_TOP | 5,222,940 | 7.0% | 25.4% |
| BINARY_SUBSCR_LIST_INT LOAD_ATTR_METHOD_NO_DICT | 4,916,300 | 6.6% | 32.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 4,742,300 | 6.4% | 38.4% |
| LOAD_CONST CALL | 3,670,080 | 4.9% | 43.4% |
| POP_TOP ENTER_EXECUTOR | 3,255,120 | 4.4% | 47.8% |
| POP_TOP LOAD_GLOBAL_MODULE | 2,887,440 | 3.9% | 51.6% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 2,847,600 | 3.8% | 55.5% |
| LOAD_CONST LOAD_CONST | 2,236,940 | 3.0% | 58.5% |
| LOAD_CONST LOAD_GLOBAL_MODULE | 1,591,340 | 2.1% | 60.7% |
| BINARY_SUBSCR_LIST_INT CALL | 1,415,420 | 1.9% | 62.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,287,900 | 1.7% | 64.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 922,800 | 1.2% | 65.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 825,120 | 1.1% | 66.7% |
| RETURN_VALUE POP_TOP | 653,280 | 0.9% | 67.5% |
| CALL RETURN_VALUE | 653,280 | 0.9% | 68.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 646,080 | 0.9% | 69.3% |
| LOAD_FAST CALL | 645,860 | 0.9% | 70.2% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 645,840 | 0.9% | 71.0% |
| NOP LOAD_GLOBAL_MODULE | 645,840 | 0.9% | 71.9% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 645,840 | 0.9% | 72.8% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 645,840 | 0.9% | 73.6% |
| LOAD_FAST CALL_TYPE_1 | 645,840 | 0.9% | 74.5% |
| CALL_TYPE_1 LOAD_FAST_LOAD_FAST | 645,840 | 0.9% | 75.4% |
| BUILD_TUPLE BINARY_SUBSCR_DICT | 645,840 | 0.9% | 76.3% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 645,840 | 0.9% | 77.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 644,880 | 0.9% | 78.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 642,000 | 0.9% | 78.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 642,000 | 0.9% | 79.7% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 642,000 | 0.9% | 80.6% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 642,000 | 0.9% | 81.5% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 642,000 | 0.9% | 82.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 634,900 | 0.9% | 83.2% |
| POP_JUMP_IF_FALSE NOP | 557,520 | 0.8% | 83.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 550,480 | 0.7% | 84.7% |
| PUSH_NULL LOAD_CONST | 550,320 | 0.7% | 85.4% |
| RESUME_CHECK LOAD_FAST | 472,320 | 0.6% | 86.1% |
| ENTER_EXECUTOR CALL | 425,620 | 0.6% | 86.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 365,040 | 0.5% | 87.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 361,240 | 0.5% | 87.6% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 295,680 | 0.4% | 88.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 287,280 | 0.4% | 88.4% |
| UNPACK_EX STORE_FAST_STORE_FAST | 280,800 | 0.4% | 88.8% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 280,800 | 0.4% | 89.2% |
| TO_BOOL POP_JUMP_IF_FALSE | 280,800 | 0.4% | 89.5% |
| STORE_FAST_STORE_FAST LOAD_FAST | 280,800 | 0.4% | 89.9% |
| STORE_FAST LOAD_FAST | 280,800 | 0.4% | 90.3% |
| POP_JUMP_IF_FALSE LOAD_CONST | 280,800 | 0.4% | 90.7% |
| LOAD_GLOBAL_MODULE IS_OP | 280,800 | 0.4% | 91.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 280,800 | 0.4% | 91.4% |
| LOAD_FAST UNPACK_EX | 280,800 | 0.4% | 91.8% |
| LOAD_FAST TO_BOOL_LIST | 280,800 | 0.4% | 92.2% |
| LOAD_FAST TO_BOOL | 280,800 | 0.4% | 92.6% |
| LOAD_FAST LOAD_ATTR_MODULE | 280,800 | 0.4% | 92.9% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 280,800 | 0.4% | 93.3% |
| LOAD_CONST IMPORT_NAME | 280,800 | 0.4% | 93.7% |
| LOAD_CONST CALL_KW | 280,800 | 0.4% | 94.1% |
| LOAD_ATTR_MODULE LOAD_CONST | 280,800 | 0.4% | 94.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 280,800 | 0.4% | 94.8% |
| IS_OP POP_JUMP_IF_FALSE | 280,800 | 0.4% | 95.2% |
| IMPORT_NAME STORE_FAST | 280,800 | 0.4% | 95.6% |
| CALL_KW POP_TOP | 280,800 | 0.4% | 96.0% |
| CALL RESUME_CHECK | 280,800 | 0.4% | 96.3% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 276,720 | 0.4% | 96.7% |
| BINARY_SUBSCR_LIST_INT LOAD_GLOBAL_MODULE | 204,480 | 0.3% | 97.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 174,000 | 0.2% | 97.2% |
| BINARY_SUBSCR_LIST_INT CALL_PY_WITH_DEFAULTS | 136,560 | 0.2% | 97.4% |
| LOAD_CONST CALL_PY_WITH_DEFAULTS | 116,160 | 0.2% | 97.6% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 110,160 | 0.1% | 97.7% |
| RETURN_VALUE RETURN_VALUE | 95,820 | 0.1% | 97.9% |
| RETURN_VALUE INTERPRETER_EXIT | 95,760 | 0.1% | 98.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 95,760 | 0.1% | 98.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 95,760 | 0.1% | 98.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 95,760 | 0.1% | 98.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 95,760 | 0.1% | 98.5% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 95,760 | 0.1% | 98.6% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 95,760 | 0.1% | 98.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 95,760 | 0.1% | 98.9% |
| CACHE RESUME_CHECK | 95,760 | 0.1% | 99.0% |
| STORE_FAST NOP | 88,320 | 0.1% | 99.1% |
| LOAD_FAST LOAD_ATTR | 88,320 | 0.1% | 99.3% |
| LOAD_ATTR STORE_FAST | 88,320 | 0.1% | 99.4% |
| LOAD_ATTR_MODULE CALL_PY_EXACT_ARGS | 84,480 | 0.1% | 99.5% |
| POP_TOP EXTENDED_ARG | 60,960 | 0.1% | 99.6% |
| EXTENDED_ARG ENTER_EXECUTOR | 60,660 | 0.1% | 99.6% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS POP_TOP | 43,920 | 0.1% | 99.7% |
| CALL CALL | 40,480 | 0.1% | 99.8% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 25,200 | 0.0% | 99.8% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 24,000 | 0.0% | 99.8% |
| BINARY_SUBSCR_LIST_INT CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 18,720 | 0.0% | 99.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 15,260 | 0.0% | 99.9% |
| FOR_ITER_RANGE STORE_FAST | 15,260 | 0.0% | 99.9% |
| CALL_BUILTIN_CLASS GET_ITER | 14,940 | 0.0% | 99.9% |
| LOAD_CONST CALL_BUILTIN_CLASS | 14,880 | 0.0% | 99.9% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 12,000 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 10,620 | 0.0% | 100.0% |
| EXTENDED_ARG FOR_ITER_RANGE | 4,560 | 0.0% | 100.0% |
| GET_ITER EXTENDED_ARG | 4,320 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_FAST | 3,840 | 0.0% | 100.0% |


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
| RESUME_CHECK | 95,760 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 14,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 10,620 | 71.1% |
| EXTENDED_ARG | 4,320 | 28.9% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 95,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 557,520 | 86.3% |
| STORE_FAST | 88,320 | 13.7% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 645,840 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 5,222,940 | 84.2% |
| RETURN_VALUE | 653,280 | 10.5% |
| CALL_KW | 280,800 | 4.5% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 43,920 | 0.7% |
| RETURN_CONST | 2,880 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,255,120 | 52.5% |
| LOAD_GLOBAL_MODULE | 2,887,440 | 46.5% |
| EXTENDED_ARG | 60,960 | 1.0% |
| JUMP_BACKWARD | 240 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 550,480 | 100.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 550,320 | 99.9% |
| CALL | 180 | 0.0% |
| LOAD_FAST | 120 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 653,280 | 43.8% |
| BINARY_SUBSCR_DICT | 645,840 | 43.3% |
| RETURN_VALUE | 95,820 | 6.4% |
| LOAD_ATTR_INSTANCE_VALUE | 95,760 | 6.4% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 653,280 | 43.8% |
| LOAD_ATTR_METHOD_NO_DICT | 645,840 | 43.3% |
| RETURN_VALUE | 95,820 | 6.4% |
| INTERPRETER_EXIT | 95,760 | 6.4% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,800 | 100.0% |
| TO_BOOL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 280,800 | 100.0% |
| TO_BOOL | 60 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 645,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 645,840 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,670,080 | 59.2% |
| BINARY_SUBSCR_LIST_INT | 1,415,420 | 22.8% |
| LOAD_FAST | 645,860 | 10.4% |
| ENTER_EXECUTOR | 425,620 | 6.9% |
| CALL | 40,480 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,222,940 | 84.3% |
| RETURN_VALUE | 653,280 | 10.5% |
| RESUME_CHECK | 280,800 | 4.5% |
| CALL | 40,480 | 0.7% |
| STORE_FAST | 60 | 0.0% |


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

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 280,800 | 100.0% |


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
| POP_TOP | 3,255,120 | 98.2% |
| EXTENDED_ARG | 60,660 | 1.8% |
| JUMP_BACKWARD | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,847,600 | 85.9% |
| CALL | 425,620 | 12.8% |
| CALL_PY_WITH_DEFAULTS | 24,000 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 12,000 | 0.4% |
| LOAD_FAST | 3,840 | 0.1% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60,960 | 93.0% |
| GET_ITER | 4,320 | 6.6% |
| JUMP_BACKWARD | 240 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 60,660 | 92.6% |
| FOR_ITER_RANGE | 4,560 | 7.0% |
| JUMP_BACKWARD | 300 | 0.5% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280,800 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 280,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 280,800 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 300 | 55.6% |
| POP_TOP | 240 | 44.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 240 | 44.4% |
| EXTENDED_ARG | 240 | 44.4% |
| ENTER_EXECUTOR | 60 | 11.1% |


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
| LOAD_FAST | 88,320 | 99.9% |
| LOAD_GLOBAL_MODULE | 60 | 0.1% |
| LOAD_ATTR | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 88,320 | 99.9% |
| LOAD_ATTR_MODULE | 60 | 0.1% |
| LOAD_ATTR | 40 | 0.0% |
| PUSH_NULL | 20 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,801,640 | 44.5% |
| LOAD_ATTR_METHOD_NO_DICT | 4,742,300 | 31.0% |
| LOAD_CONST | 2,236,940 | 14.6% |
| PUSH_NULL | 550,320 | 3.6% |
| LOAD_GLOBAL_BUILTIN | 295,680 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 6,801,640 | 44.5% |
| CALL | 3,670,080 | 24.0% |
| LOAD_CONST | 2,236,940 | 14.6% |
| LOAD_GLOBAL_MODULE | 1,591,340 | 10.4% |
| LOAD_GLOBAL_BUILTIN | 280,800 | 1.8% |


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
| LOAD_GLOBAL_BUILTIN | 1,287,900 | 33.0% |
| POP_JUMP_IF_FALSE | 646,080 | 16.5% |
| RESUME_CHECK | 472,320 | 12.1% |
| LOAD_ATTR_METHOD_NO_DICT | 365,040 | 9.3% |
| STORE_FAST_STORE_FAST | 280,800 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 922,800 | 23.6% |
| CALL | 645,860 | 16.5% |
| CALL_TYPE_1 | 645,840 | 16.5% |
| LOAD_ATTR_INSTANCE_VALUE | 287,280 | 7.4% |
| UNPACK_EX | 280,800 | 7.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_TYPE_1 | 645,840 | 41.2% |
| LOAD_GLOBAL_MODULE | 642,000 | 40.9% |
| LOAD_ATTR_METHOD_NO_DICT | 280,800 | 17.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 645,840 | 41.2% |
| CALL_PY_EXACT_ARGS | 642,000 | 40.9% |
| LOAD_FAST | 280,800 | 17.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 40.0% |
| STORE_FAST | 20 | 20.0% |
| RESUME_CHECK | 20 | 20.0% |
| FOR_ITER_RANGE | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_GLOBAL_BUILTIN | 20 | 20.0% |
| LOAD_ATTR | 20 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 642,000 | 43.2% |
| TO_BOOL_LIST | 280,800 | 18.9% |
| TO_BOOL | 280,800 | 18.9% |
| IS_OP | 280,800 | 18.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 646,080 | 43.5% |
| NOP | 557,520 | 37.6% |
| LOAD_CONST | 280,800 | 18.9% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 95,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 95,760 | 100.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 95,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 95,760 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,780 | 96.5% |
| FOR_ITER_RANGE | 100 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,880 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 280,800 | 73.0% |
| LOAD_ATTR | 88,320 | 23.0% |
| FOR_ITER_RANGE | 15,260 | 4.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,800 | 73.0% |
| NOP | 88,320 | 23.0% |
| LOAD_GLOBAL_MODULE | 15,260 | 4.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_EX | 280,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,800 | 100.0% |


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 280,800 | 100.0% |


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

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 645,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 645,840 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,801,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,916,300 | 72.3% |
| CALL | 1,415,420 | 20.8% |
| LOAD_GLOBAL_MODULE | 204,480 | 3.0% |
| CALL_PY_WITH_DEFAULTS | 136,560 | 2.0% |
| LOAD_CONST | 110,160 | 1.6% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,880 | 99.6% |
| LOAD_FAST | 40 | 0.3% |
| CALL | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 14,940 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 642,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 642,000 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 25,200 | 57.4% |
| BINARY_SUBSCR_LIST_INT | 18,720 | 42.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 43,920 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 642,000 | 77.8% |
| LOAD_FAST | 95,760 | 11.6% |
| LOAD_ATTR_MODULE | 84,480 | 10.2% |
| LOAD_GLOBAL_MODULE | 2,880 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 825,120 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 136,560 | 49.3% |
| LOAD_CONST | 116,160 | 42.0% |
| ENTER_EXECUTOR | 24,000 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 276,720 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 645,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 645,840 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 10,620 | 68.9% |
| EXTENDED_ARG | 4,560 | 29.6% |
| JUMP_BACKWARD | 240 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 15,260 | 99.0% |
| RETURN_CONST | 100 | 0.6% |
| LOAD_GLOBAL_MODULE | 40 | 0.3% |
| LOAD_GLOBAL | 20 | 0.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 287,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 95,760 | 33.3% |
| POP_JUMP_IF_NONE | 95,760 | 33.3% |
| LOAD_FAST | 95,760 | 33.3% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 4,916,300 | 88.4% |
| RETURN_VALUE | 645,840 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,742,300 | 85.3% |
| LOAD_FAST | 365,040 | 6.6% |
| LOAD_FAST_LOAD_FAST | 280,800 | 5.0% |
| LOAD_GLOBAL_MODULE | 174,000 | 3.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 634,900 | 69.3% |
| LOAD_FAST | 280,800 | 30.7% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 550,480 | 60.1% |
| LOAD_CONST | 280,800 | 30.7% |
| CALL_PY_EXACT_ARGS | 84,480 | 9.2% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 645,840 | 40.8% |
| RESUME_CHECK | 644,880 | 40.7% |
| LOAD_CONST | 280,800 | 17.7% |
| ENTER_EXECUTOR | 12,000 | 0.8% |
| STORE_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,287,900 | 81.3% |
| LOAD_CONST | 295,680 | 18.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,887,440 | 29.9% |
| ENTER_EXECUTOR | 2,847,600 | 29.5% |
| LOAD_CONST | 1,591,340 | 16.5% |
| LOAD_FAST | 922,800 | 9.6% |
| NOP | 645,840 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,801,640 | 70.5% |
| LOAD_GLOBAL_BUILTIN | 645,840 | 6.7% |
| LOAD_FAST_LOAD_FAST | 642,000 | 6.7% |
| CALL_ISINSTANCE | 642,000 | 6.7% |
| LOAD_ATTR_MODULE | 634,900 | 6.6% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 825,120 | 55.8% |
| CALL | 280,800 | 19.0% |
| CALL_PY_WITH_DEFAULTS | 276,720 | 18.7% |
| CACHE | 95,760 | 6.5% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 644,880 | 43.6% |
| LOAD_FAST | 472,320 | 31.9% |
| LOAD_GLOBAL_MODULE | 361,240 | 24.4% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 642,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 642,000 | 100.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 280,800 | 100.0% |


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
|          hit |      8148000 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       280800 | 23.1% |
|          hit |       934080 | 76.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 60 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 60 | 100.0% |


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
| specialization.deferred |      6157140 | 70.7% |
|          hit |      2507580 | 28.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.0% |
| Failure | 40,480 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr method fastcall keywords | 38,280 | 94.6% |
| code complex parameters | 2,140 | 5.3% |
| cfunc noargs | 60 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |        15420 | 100.0% |


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
| specialization.deferred |        88340 | 1.2% |
|          hit |      7255120 | 98.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 60.0% |
| Failure | 40 | 40.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| mutable class | 40 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     12089740 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
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


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 35,593,180 | 48.0% |
| Not specialized | 8,243,520 | 11.1% |
| Specialized | 30,311,700 | 40.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 6,157,140 | 94.3% |
| TO_BOOL | 280,800 | 4.3% |
| LOAD_ATTR | 88,340 | 1.4% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| UNPACK_EX | 0 | 0.0% |
| TO_BOOL_LIST | 0 | 0.0% |
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
| Calls to PyEval_EvalDefault | 95,760 | 6.4% |
| Calls to Python functions inlined | 1,405,320 | 93.6% |
| Calls via PyEval_EvalFrame (total) | 95,760 | 6.4% |
| Calls via PyEval_EvalFrame (vector) | 95,760 | 6.4% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 95,760 | 6.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 1,501,080 | 100.0% |
| Frame objects created | 283,440 | 18.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 3,628,280 | 16.2% |
| Frees to freelist | 3,628,260 |  |
| Allocations | 18,711,220 | 83.8% |
| Allocations to 512 bytes | 18,577,300 | 83.2% |
| Allocations to 4 kbytes | 117,120 | 0.5% |
| Allocations over 4 kbytes | 16,800 | 0.1% |
| Frees | 26,250,000 |  |
| New values | 0 |  |
| Interpreter increfs | 36,928,700 | 59.3% |
| Interpreter decrefs | 38,918,060 | 51.7% |
| Increfs | 25,326,120 | 40.7% |
| Decrefs | 36,373,380 | 48.3% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 376,620 |  |
| Method cache misses | 0 |  |
| Method cache collisions | 0 |  |
| Method cache dunder hits | 2,334,000 |  |
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
| Optimization attempts | 60 |  |
| Traces created | 60 | 100.0% |
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
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 60 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 60 | 100.0% |

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
| CALL | 60 |


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
