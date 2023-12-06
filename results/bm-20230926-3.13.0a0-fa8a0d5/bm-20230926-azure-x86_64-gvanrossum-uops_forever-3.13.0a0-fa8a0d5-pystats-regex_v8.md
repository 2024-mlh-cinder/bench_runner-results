
# Pystats results

- benchmark: regex_v8
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_CONST | 15,639,920 | 20.8% | 20.8% |  |
| LOAD_GLOBAL_MODULE | 9,728,360 | 13.0% | 33.8% |  |
| BINARY_SUBSCR_LIST_INT | 6,838,600 | 9.1% | 42.9% |  |
| POP_TOP | 6,203,820 | 8.3% | 51.2% |  |
| CALL | 6,197,640 | 8.3% | 59.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,569,580 | 7.4% | 66.9% |  |
| LOAD_FAST | 3,938,640 | 5.2% | 72.1% |  |
| ENTER_EXECUTOR | 3,315,840 | 4.4% | 76.5% |  |
| LOAD_GLOBAL_BUILTIN | 1,602,300 | 2.1% | 78.7% |  |
| LOAD_FAST_LOAD_FAST | 1,587,360 | 2.1% | 80.8% |  |
| RESUME_CHECK | 1,501,080 | 2.0% | 82.8% |  |
| RETURN_VALUE | 1,498,200 | 2.0% | 84.8% |  |
| POP_JUMP_IF_FALSE | 1,495,680 | 2.0% | 86.8% |  |
| LOAD_ATTR_MODULE | 1,030,000 | 1.4% | 88.2% |  |
| CALL_PY_EXACT_ARGS | 847,680 | 1.1% | 89.3% |  |
| PUSH_NULL | 653,580 | 0.9% | 90.2% |  |
| NOP | 653,340 | 0.9% | 91.0% |  |
| TO_BOOL_BOOL | 653,280 | 0.9% | 91.9% |  |
| CALL_TYPE_1 | 653,280 | 0.9% | 92.8% |  |
| CALL_ISINSTANCE | 653,280 | 0.9% | 93.6% |  |
| BUILD_TUPLE | 653,280 | 0.9% | 94.5% |  |
| BINARY_SUBSCR_DICT | 653,280 | 0.9% | 95.4% |  |
| STORE_FAST | 391,880 | 0.5% | 95.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 287,280 | 0.4% | 96.3% |  |
| TO_BOOL | 280,860 | 0.4% | 96.7% |  |
| UNPACK_EX | 280,800 | 0.4% | 97.0% |  |
| TO_BOOL_LIST | 280,800 | 0.4% | 97.4% |  |
| STORE_FAST_STORE_FAST | 280,800 | 0.4% | 97.8% |  |
| IS_OP | 280,800 | 0.4% | 98.2% |  |
| IMPORT_NAME | 280,800 | 0.4% | 98.5% |  |
| CALL_KW | 280,800 | 0.4% | 98.9% |  |
| CALL_PY_WITH_DEFAULTS | 276,720 | 0.4% | 99.3% |  |
| LOAD_ATTR | 95,880 | 0.1% | 99.4% |  |
| POP_JUMP_IF_NOT_NONE | 95,760 | 0.1% | 99.5% |  |
| POP_JUMP_IF_NONE | 95,760 | 0.1% | 99.7% |  |
| INTERPRETER_EXIT | 95,760 | 0.1% | 99.8% |  |
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
| LOAD_GLOBAL_MODULE LOAD_CONST | 6,838,600 | 9.1% | 9.1% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 6,838,600 | 9.1% | 18.2% |
| CALL POP_TOP | 5,222,940 | 7.0% | 25.2% |
| BINARY_SUBSCR_LIST_INT LOAD_ATTR_METHOD_NO_DICT | 4,916,300 | 6.6% | 31.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 4,742,300 | 6.3% | 38.1% |
| LOAD_CONST CALL | 3,737,760 | 5.0% | 43.0% |
| POP_TOP ENTER_EXECUTOR | 3,255,120 | 4.3% | 47.4% |
| POP_TOP LOAD_GLOBAL_MODULE | 2,887,440 | 3.8% | 51.2% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 2,847,600 | 3.8% | 55.0% |
| LOAD_CONST LOAD_CONST | 2,414,060 | 3.2% | 58.2% |
| LOAD_CONST LOAD_GLOBAL_MODULE | 1,628,300 | 2.2% | 60.4% |
| BINARY_SUBSCR_LIST_INT CALL | 1,415,420 | 1.9% | 62.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,306,620 | 1.7% | 64.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 934,080 | 1.2% | 65.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 847,680 | 1.1% | 66.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 657,360 | 0.9% | 67.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 656,160 | 0.9% | 68.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 653,440 | 0.9% | 69.0% |
| LOAD_FAST CALL | 653,300 | 0.9% | 69.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 653,280 | 0.9% | 70.8% |
| RETURN_VALUE POP_TOP | 653,280 | 0.9% | 71.6% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 653,280 | 0.9% | 72.5% |
| PUSH_NULL LOAD_CONST | 653,280 | 0.9% | 73.4% |
| NOP LOAD_GLOBAL_MODULE | 653,280 | 0.9% | 74.3% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_BUILTIN | 653,280 | 0.9% | 75.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 653,280 | 0.9% | 76.0% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 653,280 | 0.9% | 76.9% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 653,280 | 0.9% | 77.7% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 653,280 | 0.9% | 78.6% |
| LOAD_FAST CALL_TYPE_1 | 653,280 | 0.9% | 79.5% |
| CALL_TYPE_1 LOAD_FAST_LOAD_FAST | 653,280 | 0.9% | 80.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 653,280 | 0.9% | 81.2% |
| CALL RETURN_VALUE | 653,280 | 0.9% | 82.1% |
| BUILD_TUPLE BINARY_SUBSCR_DICT | 653,280 | 0.9% | 83.0% |
| BINARY_SUBSCR_DICT RETURN_VALUE | 653,280 | 0.9% | 83.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 646,180 | 0.9% | 84.7% |
| POP_JUMP_IF_FALSE NOP | 557,520 | 0.7% | 85.4% |
| RESUME_CHECK LOAD_FAST | 472,320 | 0.6% | 86.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 372,520 | 0.5% | 86.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 372,480 | 0.5% | 87.1% |
| ENTER_EXECUTOR CALL | 350,500 | 0.5% | 87.5% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 295,680 | 0.4% | 87.9% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 287,280 | 0.4% | 88.3% |
| UNPACK_EX STORE_FAST_STORE_FAST | 280,800 | 0.4% | 88.7% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 280,800 | 0.4% | 89.1% |
| TO_BOOL POP_JUMP_IF_FALSE | 280,800 | 0.4% | 89.4% |
| STORE_FAST_STORE_FAST LOAD_FAST | 280,800 | 0.4% | 89.8% |
| STORE_FAST LOAD_FAST | 280,800 | 0.4% | 90.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 280,800 | 0.4% | 90.6% |
| LOAD_GLOBAL_MODULE IS_OP | 280,800 | 0.4% | 90.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 280,800 | 0.4% | 91.3% |
| LOAD_FAST UNPACK_EX | 280,800 | 0.4% | 91.7% |
| LOAD_FAST TO_BOOL_LIST | 280,800 | 0.4% | 92.1% |
| LOAD_FAST TO_BOOL | 280,800 | 0.4% | 92.4% |
| LOAD_FAST LOAD_ATTR_MODULE | 280,800 | 0.4% | 92.8% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 280,800 | 0.4% | 93.2% |
| LOAD_CONST IMPORT_NAME | 280,800 | 0.4% | 93.5% |
| LOAD_CONST CALL_KW | 280,800 | 0.4% | 93.9% |
| LOAD_ATTR_MODULE LOAD_CONST | 280,800 | 0.4% | 94.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 280,800 | 0.4% | 94.7% |
| IS_OP POP_JUMP_IF_FALSE | 280,800 | 0.4% | 95.0% |
| IMPORT_NAME STORE_FAST | 280,800 | 0.4% | 95.4% |
| CALL_KW POP_TOP | 280,800 | 0.4% | 95.8% |
| CALL RESUME_CHECK | 280,800 | 0.4% | 96.2% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 276,720 | 0.4% | 96.5% |
| BINARY_SUBSCR_LIST_INT LOAD_GLOBAL_MODULE | 215,760 | 0.3% | 96.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_GLOBAL_MODULE | 174,000 | 0.2% | 97.1% |
| LOAD_CONST CALL_PY_WITH_DEFAULTS | 138,720 | 0.2% | 97.2% |
| BINARY_SUBSCR_LIST_INT CALL_PY_WITH_DEFAULTS | 138,000 | 0.2% | 97.4% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 134,400 | 0.2% | 97.6% |
| ENTER_EXECUTOR LOAD_ATTR_MODULE | 102,960 | 0.1% | 97.7% |
| RETURN_VALUE RETURN_VALUE | 95,820 | 0.1% | 97.9% |
| STORE_FAST NOP | 95,760 | 0.1% | 98.0% |
| RETURN_VALUE INTERPRETER_EXIT | 95,760 | 0.1% | 98.1% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 95,760 | 0.1% | 98.3% |
| POP_JUMP_IF_NONE LOAD_FAST | 95,760 | 0.1% | 98.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 95,760 | 0.1% | 98.5% |
| LOAD_FAST LOAD_ATTR | 95,760 | 0.1% | 98.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 95,760 | 0.1% | 98.8% |
| LOAD_ATTR_MODULE CALL_PY_EXACT_ARGS | 95,760 | 0.1% | 98.9% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 95,760 | 0.1% | 99.0% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NONE | 95,760 | 0.1% | 99.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 95,760 | 0.1% | 99.3% |
| LOAD_ATTR STORE_FAST | 95,760 | 0.1% | 99.4% |
| CACHE RESUME_CHECK | 95,760 | 0.1% | 99.5% |
| POP_TOP EXTENDED_ARG | 60,960 | 0.1% | 99.6% |
| EXTENDED_ARG ENTER_EXECUTOR | 60,660 | 0.1% | 99.7% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS POP_TOP | 43,920 | 0.1% | 99.7% |
| CALL CALL | 40,480 | 0.1% | 99.8% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 25,200 | 0.0% | 99.8% |
| BINARY_SUBSCR_LIST_INT CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 18,720 | 0.0% | 99.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 15,260 | 0.0% | 99.9% |
| FOR_ITER_RANGE STORE_FAST | 15,260 | 0.0% | 99.9% |
| CALL_BUILTIN_CLASS GET_ITER | 14,940 | 0.0% | 99.9% |
| LOAD_CONST CALL_BUILTIN_CLASS | 14,880 | 0.0% | 99.9% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 12,000 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 10,620 | 0.0% | 100.0% |
| EXTENDED_ARG FOR_ITER_RANGE | 4,560 | 0.0% | 100.0% |
| GET_ITER EXTENDED_ARG | 4,320 | 0.0% | 100.0% |
| RETURN_CONST POP_TOP | 2,880 | 0.0% | 100.0% |


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
| POP_JUMP_IF_FALSE | 557,520 | 85.3% |
| STORE_FAST | 95,760 | 14.7% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 653,280 | 100.0% |
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
| LOAD_ATTR_MODULE | 653,440 | 100.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 653,280 | 100.0% |
| CALL | 180 | 0.0% |
| LOAD_FAST | 120 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 653,280 | 43.6% |
| BINARY_SUBSCR_DICT | 653,280 | 43.6% |
| RETURN_VALUE | 95,820 | 6.4% |
| LOAD_ATTR_INSTANCE_VALUE | 95,760 | 6.4% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 653,280 | 43.6% |
| LOAD_ATTR_METHOD_NO_DICT | 653,280 | 43.6% |
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
| LOAD_FAST_LOAD_FAST | 653,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 653,280 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,737,760 | 60.3% |
| BINARY_SUBSCR_LIST_INT | 1,415,420 | 22.8% |
| LOAD_FAST | 653,300 | 10.5% |
| ENTER_EXECUTOR | 350,500 | 5.7% |
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
| CALL | 350,500 | 10.6% |
| LOAD_ATTR_MODULE | 102,960 | 3.1% |
| LOAD_GLOBAL_BUILTIN | 12,000 | 0.4% |
| RETURN_CONST | 2,780 | 0.1% |


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
| LOAD_FAST | 95,760 | 99.9% |
| LOAD_GLOBAL_MODULE | 60 | 0.1% |
| LOAD_ATTR | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 95,760 | 99.9% |
| LOAD_ATTR_MODULE | 60 | 0.1% |
| LOAD_ATTR | 40 | 0.0% |
| PUSH_NULL | 20 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,838,600 | 43.7% |
| LOAD_ATTR_METHOD_NO_DICT | 4,742,300 | 30.3% |
| LOAD_CONST | 2,414,060 | 15.4% |
| PUSH_NULL | 653,280 | 4.2% |
| LOAD_GLOBAL_BUILTIN | 295,680 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 6,838,600 | 43.7% |
| CALL | 3,737,760 | 23.9% |
| LOAD_CONST | 2,414,060 | 15.4% |
| LOAD_GLOBAL_MODULE | 1,628,300 | 10.4% |
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
| LOAD_GLOBAL_BUILTIN | 1,306,620 | 33.2% |
| POP_JUMP_IF_FALSE | 657,360 | 16.7% |
| RESUME_CHECK | 472,320 | 12.0% |
| LOAD_ATTR_METHOD_NO_DICT | 372,480 | 9.5% |
| STORE_FAST_STORE_FAST | 280,800 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 934,080 | 23.7% |
| CALL | 653,300 | 16.6% |
| CALL_TYPE_1 | 653,280 | 16.6% |
| LOAD_ATTR_INSTANCE_VALUE | 287,280 | 7.3% |
| UNPACK_EX | 280,800 | 7.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 653,280 | 41.2% |
| CALL_TYPE_1 | 653,280 | 41.2% |
| LOAD_ATTR_METHOD_NO_DICT | 280,800 | 17.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 653,280 | 41.2% |
| BUILD_TUPLE | 653,280 | 41.2% |
| LOAD_FAST | 280,800 | 17.7% |


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
| TO_BOOL_BOOL | 653,280 | 43.7% |
| TO_BOOL_LIST | 280,800 | 18.8% |
| TO_BOOL | 280,800 | 18.8% |
| IS_OP | 280,800 | 18.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 657,360 | 44.0% |
| NOP | 557,520 | 37.3% |
| LOAD_CONST | 280,800 | 18.8% |


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
| IMPORT_NAME | 280,800 | 71.7% |
| LOAD_ATTR | 95,760 | 24.4% |
| FOR_ITER_RANGE | 15,260 | 3.9% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280,800 | 71.7% |
| NOP | 95,760 | 24.4% |
| LOAD_GLOBAL_MODULE | 15,260 | 3.9% |
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
| BUILD_TUPLE | 653,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 653,280 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,838,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,916,300 | 71.9% |
| CALL | 1,415,420 | 20.7% |
| LOAD_GLOBAL_MODULE | 215,760 | 3.2% |
| CALL_PY_WITH_DEFAULTS | 138,000 | 2.0% |
| LOAD_CONST | 134,400 | 2.0% |


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
| LOAD_GLOBAL_MODULE | 653,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 653,280 | 100.0% |


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
| LOAD_FAST_LOAD_FAST | 653,280 | 77.1% |
| LOAD_FAST | 95,760 | 11.3% |
| LOAD_ATTR_MODULE | 95,760 | 11.3% |
| LOAD_GLOBAL_MODULE | 2,880 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 847,680 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 138,720 | 50.1% |
| BINARY_SUBSCR_LIST_INT | 138,000 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 276,720 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 653,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 653,280 | 100.0% |


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
| BINARY_SUBSCR_LIST_INT | 4,916,300 | 88.3% |
| RETURN_VALUE | 653,280 | 11.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,742,300 | 85.1% |
| LOAD_FAST | 372,480 | 6.7% |
| LOAD_FAST_LOAD_FAST | 280,800 | 5.0% |
| LOAD_GLOBAL_MODULE | 174,000 | 3.1% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 646,180 | 62.7% |
| LOAD_FAST | 280,800 | 27.3% |
| ENTER_EXECUTOR | 102,960 | 10.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 653,440 | 63.4% |
| LOAD_CONST | 280,800 | 27.3% |
| CALL_PY_EXACT_ARGS | 95,760 | 9.3% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 656,160 | 41.0% |
| LOAD_GLOBAL_MODULE | 653,280 | 40.8% |
| LOAD_CONST | 280,800 | 17.5% |
| ENTER_EXECUTOR | 12,000 | 0.7% |
| STORE_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,306,620 | 81.5% |
| LOAD_CONST | 295,680 | 18.5% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,887,440 | 29.7% |
| ENTER_EXECUTOR | 2,847,600 | 29.3% |
| LOAD_CONST | 1,628,300 | 16.7% |
| LOAD_FAST | 934,080 | 9.6% |
| NOP | 653,280 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,838,600 | 70.3% |
| LOAD_GLOBAL_BUILTIN | 653,280 | 6.7% |
| LOAD_FAST_LOAD_FAST | 653,280 | 6.7% |
| CALL_ISINSTANCE | 653,280 | 6.7% |
| LOAD_ATTR_MODULE | 646,180 | 6.6% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 847,680 | 56.5% |
| CALL | 280,800 | 18.7% |
| CALL_PY_WITH_DEFAULTS | 276,720 | 18.4% |
| CACHE | 95,760 | 6.4% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 656,160 | 43.7% |
| LOAD_FAST | 472,320 | 31.5% |
| LOAD_GLOBAL_MODULE | 372,520 | 24.8% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 653,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 653,280 | 100.0% |


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
| specialization.deferred |        95780 | 1.3% |
|          hit |      7255120 | 98.7% |

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
| Basic | 36,119,500 | 48.1% |
| Not specialized | 8,262,240 | 11.0% |
| Specialized | 30,649,860 | 40.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 6,157,140 | 94.2% |
| TO_BOOL | 280,800 | 4.3% |
| LOAD_ATTR | 95,780 | 1.5% |
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
| Allocations | 18,711,160 | 83.8% |
| Allocations to 512 bytes | 18,577,240 | 83.2% |
| Allocations to 4 kbytes | 117,120 | 0.5% |
| Allocations over 4 kbytes | 16,800 | 0.1% |
| Frees | 26,249,940 |  |
| New values | 0 |  |
| Interpreter increfs | 37,390,940 | 60.1% |
| Interpreter decrefs | 39,132,860 | 52.0% |
| Increfs | 24,863,880 | 39.9% |
| Decrefs | 36,158,580 | 48.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 376,619 |  |
| Method cache misses | 1 |  |
| Method cache collisions | 1 |  |
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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
