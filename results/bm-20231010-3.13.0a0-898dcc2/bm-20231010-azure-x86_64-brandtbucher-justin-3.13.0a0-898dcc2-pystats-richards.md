
# Pystats results

- benchmark: richards
- fork: brandtbucher
- ref: justin
- commit hash: 898dcc2
- commit date: 2023-10-10T14:45:03+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 250,056,840 | 23.2% | 23.2% |  |
| LOAD_ATTR_INSTANCE_VALUE | 110,085,620 | 10.2% | 33.3% | 34.9% |
| TO_BOOL_BOOL | 72,537,840 | 6.7% | 40.1% |  |
| RETURN_VALUE | 54,493,860 | 5.0% | 45.1% |  |
| POP_JUMP_IF_FALSE | 54,383,160 | 5.0% | 50.1% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 54,030,520 | 5.0% | 55.1% | 44.6% |
| CALL_PY_EXACT_ARGS | 53,676,120 | 5.0% | 60.1% | 9.8% |
| RESUME_CHECK | 53,580,300 | 5.0% | 65.1% | 0.0% |
| STORE_FAST | 49,252,620 | 4.6% | 69.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 43,872,720 | 4.1% | 73.7% | 14.8% |
| LOAD_CONST | 39,480,420 | 3.7% | 77.4% |  |
| COPY | 36,051,540 | 3.3% | 80.7% |  |
| POP_TOP | 28,737,900 | 2.7% | 83.4% |  |
| LOAD_GLOBAL_MODULE | 27,715,900 | 2.6% | 85.9% |  |
| POP_JUMP_IF_NOT_NONE | 23,066,160 | 2.1% | 88.1% |  |
| POP_JUMP_IF_NONE | 16,842,120 | 1.6% | 89.6% |  |
| POP_JUMP_IF_TRUE | 16,511,040 | 1.5% | 91.1% |  |
| LOAD_FAST_LOAD_FAST | 15,352,440 | 1.4% | 92.6% |  |
| ENTER_EXECUTOR | 13,096,320 | 1.2% | 93.8% |  |
| UNARY_NOT | 11,405,700 | 1.1% | 94.8% |  |
| COMPARE_OP_INT | 9,762,060 | 0.9% | 95.7% |  |
| JUMP_FORWARD | 8,109,840 | 0.8% | 96.5% |  |
| LOAD_GLOBAL_BUILTIN | 7,894,980 | 0.7% | 97.2% |  |
| CALL_ISINSTANCE | 7,894,800 | 0.7% | 98.0% |  |
| SWAP | 5,985,240 | 0.6% | 98.5% |  |
| BINARY_OP_ADD_INT | 5,601,120 | 0.5% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 5,105,400 | 0.5% | 99.5% |  |
| BINARY_OP | 3,000,540 | 0.3% | 99.8% |  |
| BINARY_OP_SUBTRACT_INT | 1,500,720 | 0.1% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 301,440 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 279,660 | 0.0% | 100.0% |  |
| GET_ITER | 279,420 | 0.0% | 100.0% |  |
| RETURN_CONST | 4,080 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 3,120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 3,120 | 0.0% | 100.0% |  |
| BUILD_LIST | 960 | 0.0% | 100.0% |  |
| LOAD_ATTR | 900 | 0.0% | 100.0% |  |
| CALL | 400 | 0.0% | 100.0% |  |
| PUSH_NULL | 360 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 360 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 240 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 120 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 80 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 91,488,960 | 8.5% | 8.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 53,577,000 | 5.0% | 13.4% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 44,621,100 | 4.1% | 17.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 41,694,360 | 3.9% | 21.4% |
| RESUME_CHECK LOAD_FAST | 40,476,960 | 3.7% | 25.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 33,098,040 | 3.1% | 28.2% |
| STORE_FAST LOAD_FAST | 32,187,000 | 3.0% | 31.2% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 31,104,120 | 2.9% | 34.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 30,485,280 | 2.8% | 36.9% |
| COPY TO_BOOL_BOOL | 30,066,300 | 2.8% | 39.7% |
| POP_TOP LOAD_FAST | 25,666,920 | 2.4% | 42.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 22,639,680 | 2.1% | 44.2% |
| LOAD_CONST LOAD_FAST | 21,893,880 | 2.0% | 46.2% |
| LOAD_ATTR_INSTANCE_VALUE COPY | 21,450,600 | 2.0% | 48.2% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 19,064,280 | 1.8% | 50.0% |
| RETURN_VALUE RETURN_VALUE | 18,579,120 | 1.7% | 51.7% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 18,563,280 | 1.7% | 53.4% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 17,486,640 | 1.6% | 55.0% |
| RETURN_VALUE TO_BOOL_BOOL | 17,425,560 | 1.6% | 56.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 16,842,120 | 1.6% | 58.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 16,511,040 | 1.5% | 59.7% |
| LOAD_FAST RETURN_VALUE | 15,973,020 | 1.5% | 61.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 15,353,040 | 1.4% | 62.6% |
| POP_JUMP_IF_FALSE POP_TOP | 14,670,660 | 1.4% | 64.0% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 13,098,000 | 1.2% | 65.2% |
| POP_JUMP_IF_NONE ENTER_EXECUTOR | 12,795,600 | 1.2% | 66.4% |
| RETURN_VALUE STORE_FAST | 11,885,160 | 1.1% | 67.5% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 11,881,080 | 1.1% | 68.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 11,540,880 | 1.1% | 69.6% |
| TO_BOOL_BOOL UNARY_NOT | 11,405,700 | 1.1% | 70.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 11,405,700 | 1.1% | 71.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 10,684,320 | 1.0% | 72.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 10,587,840 | 1.0% | 73.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 10,334,520 | 1.0% | 74.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 9,762,060 | 0.9% | 75.6% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 9,700,260 | 0.9% | 76.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 9,263,640 | 0.9% | 77.3% |
| LOAD_FAST STORE_FAST | 9,150,840 | 0.8% | 78.2% |
| UNARY_NOT COPY | 8,615,700 | 0.8% | 79.0% |
| POP_JUMP_IF_TRUE POP_TOP | 8,615,700 | 0.8% | 79.8% |
| RESUME_CHECK LOAD_CONST | 7,995,480 | 0.7% | 80.5% |
| JUMP_FORWARD LOAD_FAST | 7,970,160 | 0.7% | 81.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 7,894,980 | 0.7% | 82.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 7,894,800 | 0.7% | 82.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 7,894,800 | 0.7% | 83.5% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 7,894,800 | 0.7% | 84.2% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 7,894,800 | 0.7% | 84.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 7,894,800 | 0.7% | 85.6% |
| POP_JUMP_IF_FALSE RETURN_VALUE | 6,779,400 | 0.6% | 86.3% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 5,985,240 | 0.6% | 86.8% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 5,985,240 | 0.6% | 87.4% |
| LOAD_GLOBAL_MODULE TO_BOOL_BOOL | 5,745,480 | 0.5% | 87.9% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NOT_NONE | 5,579,520 | 0.5% | 88.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,384,640 | 0.5% | 88.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 5,300,400 | 0.5% | 89.4% |
| RETURN_VALUE POP_TOP | 5,204,400 | 0.5% | 89.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 5,167,080 | 0.5% | 90.4% |
| POP_JUMP_IF_FALSE LOAD_CONST | 5,126,160 | 0.5% | 90.9% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 5,106,760 | 0.5% | 91.3% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 5,105,400 | 0.5% | 91.8% |
| LOAD_CONST STORE_FAST | 5,104,920 | 0.5% | 92.3% |
| STORE_FAST JUMP_FORWARD | 5,040,600 | 0.5% | 92.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 4,666,080 | 0.4% | 93.2% |
| BINARY_OP_ADD_INT SWAP | 4,184,400 | 0.4% | 93.6% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 4,111,680 | 0.4% | 93.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_INSTANCE_VALUE | 3,991,200 | 0.4% | 94.3% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 3,989,400 | 0.4% | 94.7% |
| LOAD_GLOBAL_MODULE COPY | 3,905,160 | 0.4% | 95.0% |
| POP_TOP JUMP_FORWARD | 3,069,240 | 0.3% | 95.3% |
| LOAD_CONST BINARY_OP | 2,998,800 | 0.3% | 95.6% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 2,970,960 | 0.3% | 95.9% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 2,886,600 | 0.3% | 96.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 2,831,040 | 0.3% | 96.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,790,600 | 0.3% | 96.7% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 2,790,240 | 0.3% | 96.9% |
| UNARY_NOT RETURN_VALUE | 2,790,000 | 0.3% | 97.2% |
| LOAD_CONST COMPARE_OP_INT | 2,679,400 | 0.2% | 97.4% |
| LOAD_FAST COPY | 2,080,080 | 0.2% | 97.6% |
| BINARY_OP LOAD_CONST | 1,798,920 | 0.2% | 97.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,674,480 | 0.2% | 97.9% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 1,500,720 | 0.1% | 98.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,437,720 | 0.1% | 98.2% |
| RETURN_VALUE LOAD_FAST | 1,397,400 | 0.1% | 98.4% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 1,215,240 | 0.1% | 98.5% |
| STORE_FAST LOAD_CONST | 1,200,000 | 0.1% | 98.6% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 1,200,000 | 0.1% | 98.7% |
| BINARY_OP_SUBTRACT_INT SWAP | 1,200,000 | 0.1% | 98.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_MODULE | 1,199,880 | 0.1% | 98.9% |
| LOAD_FAST LOAD_CONST | 1,116,180 | 0.1% | 99.0% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 1,116,000 | 0.1% | 99.1% |
| BINARY_OP_ADD_INT LOAD_FAST | 1,116,000 | 0.1% | 99.2% |
| POP_JUMP_IF_NOT_NONE LOAD_CONST | 1,115,280 | 0.1% | 99.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 725,420 | 0.1% | 99.4% |
| ENTER_EXECUTOR RETURN_VALUE | 668,400 | 0.1% | 99.4% |
| BINARY_OP SWAP | 600,840 | 0.1% | 99.5% |
| BINARY_OP LOAD_FAST | 600,000 | 0.1% | 99.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_ATTR_METHOD_WITH_VALUES | 454,360 | 0.0% | 99.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 301,440 | 0.0% | 99.6% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 301,440 | 0.0% | 99.7% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 300,720 | 0.0% | 99.7% |


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
| RESUME_CHECK | 120 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,120 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 279,240 | 99.9% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 279,300 | 100.0% |
| EXTENDED_ARG | 120 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 14,670,660 | 51.0% |
| POP_JUMP_IF_TRUE | 8,615,700 | 30.0% |
| RETURN_VALUE | 5,204,400 | 18.1% |
| ENTER_EXECUTOR | 246,120 | 0.9% |
| RETURN_CONST | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,666,920 | 89.3% |
| JUMP_FORWARD | 3,069,240 | 10.7% |
| RETURN_CONST | 720 | 0.0% |
| LOAD_GLOBAL_MODULE | 720 | 0.0% |
| LOAD_CONST | 120 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 66.7% |
| LOAD_DEREF | 60 | 16.7% |
| LOAD_ATTR_MODULE | 40 | 11.1% |
| LOAD_ATTR | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 300 | 83.3% |
| LOAD_FAST | 60 | 16.7% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 18,579,120 | 34.1% |
| LOAD_FAST | 15,973,020 | 29.3% |
| LOAD_ATTR_INSTANCE_VALUE | 9,700,260 | 17.8% |
| POP_JUMP_IF_FALSE | 6,779,400 | 12.4% |
| UNARY_NOT | 2,790,000 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 18,579,120 | 34.1% |
| TO_BOOL_BOOL | 17,425,560 | 32.0% |
| STORE_FAST | 11,885,160 | 21.8% |
| POP_TOP | 5,204,400 | 9.6% |
| LOAD_FAST | 1,397,400 | 2.6% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 11,405,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 8,615,700 | 75.5% |
| RETURN_VALUE | 2,790,000 | 24.5% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,998,800 | 99.9% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |
| BINARY_OP | 760 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,798,920 | 60.0% |
| SWAP | 600,840 | 20.0% |
| LOAD_FAST | 600,000 | 20.0% |
| BINARY_OP | 760 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 960 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 300 | 75.0% |
| CALL | 80 | 20.0% |
| LOAD_FAST | 20 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 180 | 45.0% |
| CALL | 80 | 20.0% |
| STORE_FAST | 60 | 15.0% |
| LOAD_FAST | 60 | 15.0% |
| CALL_BUILTIN_CLASS | 20 | 5.0% |


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

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 21,450,600 | 59.5% |
| UNARY_NOT | 8,615,700 | 23.9% |
| LOAD_GLOBAL_MODULE | 3,905,160 | 10.8% |
| LOAD_FAST | 2,080,080 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 30,066,300 | 83.4% |
| LOAD_ATTR_INSTANCE_VALUE | 5,985,240 | 16.6% |


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
| POP_JUMP_IF_NONE | 12,795,600 | 97.7% |
| STORE_SUBSCR_LIST_INT | 300,720 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 11,881,080 | 90.7% |
| RETURN_VALUE | 668,400 | 5.1% |
| LOAD_FAST | 279,240 | 2.1% |
| POP_TOP | 246,120 | 1.9% |
| LOAD_CONST | 21,480 | 0.2% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 33.3% |
| JUMP_BACKWARD | 120 | 33.3% |
| GET_ITER | 120 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 240 | 66.7% |
| JUMP_BACKWARD | 120 | 33.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 50.0% |
| EXTENDED_ARG | 120 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 120 | 50.0% |
| EXTENDED_ARG | 120 | 50.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,040,600 | 62.2% |
| POP_TOP | 3,069,240 | 37.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,970,160 | 98.3% |
| LOAD_FAST_LOAD_FAST | 139,680 | 1.7% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 760 | 84.4% |
| LOAD_ATTR | 120 | 13.3% |
| LOAD_GLOBAL | 20 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 720 | 80.0% |
| LOAD_ATTR | 120 | 13.3% |
| LOAD_ATTR_MODULE | 40 | 4.4% |
| PUSH_NULL | 20 | 2.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 11,540,880 | 29.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,263,640 | 23.5% |
| RESUME_CHECK | 7,995,480 | 20.3% |
| POP_JUMP_IF_FALSE | 5,126,160 | 13.0% |
| BINARY_OP | 1,798,920 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,893,880 | 55.5% |
| BINARY_OP_ADD_INT | 5,300,400 | 13.4% |
| STORE_FAST | 5,104,920 | 12.9% |
| BINARY_OP | 2,998,800 | 7.6% |
| COMPARE_OP_INT | 2,679,400 | 6.8% |


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
| RESUME_CHECK | 40,476,960 | 16.2% |
| STORE_FAST | 32,187,000 | 12.9% |
| STORE_ATTR_INSTANCE_VALUE | 30,485,280 | 12.2% |
| POP_TOP | 25,666,920 | 10.3% |
| POP_JUMP_IF_FALSE | 22,639,680 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 91,488,960 | 36.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 41,694,360 | 16.7% |
| STORE_ATTR_INSTANCE_VALUE | 33,098,040 | 13.2% |
| POP_JUMP_IF_NOT_NONE | 17,486,640 | 7.0% |
| POP_JUMP_IF_NONE | 16,842,120 | 6.7% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 10,684,320 | 69.6% |
| POP_JUMP_IF_NOT_NONE | 2,886,600 | 18.8% |
| POP_JUMP_IF_NONE | 1,215,240 | 7.9% |
| STORE_ATTR_INSTANCE_VALUE | 284,040 | 1.9% |
| JUMP_FORWARD | 139,680 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,894,800 | 51.4% |
| STORE_ATTR_INSTANCE_VALUE | 4,666,080 | 30.4% |
| CALL_PY_EXACT_ARGS | 2,790,240 | 18.2% |
| LOAD_FAST_LOAD_FAST | 1,200 | 0.0% |
| LOAD_CONST | 120 | 0.0% |


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
| TO_BOOL_BOOL | 44,621,100 | 82.0% |
| COMPARE_OP_INT | 9,762,060 | 18.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,639,680 | 41.6% |
| POP_TOP | 14,670,660 | 27.0% |
| RETURN_VALUE | 6,779,400 | 12.5% |
| LOAD_GLOBAL_MODULE | 5,167,080 | 9.5% |
| LOAD_CONST | 5,126,160 | 9.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,842,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,795,600 | 76.0% |
| LOAD_FAST | 2,831,040 | 16.8% |
| LOAD_FAST_LOAD_FAST | 1,215,240 | 7.2% |
| RETURN_CONST | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,486,640 | 75.8% |
| LOAD_ATTR_INSTANCE_VALUE | 5,579,520 | 24.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,064,280 | 82.7% |
| LOAD_FAST_LOAD_FAST | 2,886,600 | 12.5% |
| LOAD_CONST | 1,115,280 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 16,511,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,615,700 | 52.2% |
| LOAD_FAST | 7,894,800 | 47.8% |
| RETURN_VALUE | 540 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 2,400 | 58.8% |
| STORE_SUBSCR_LIST_INT | 720 | 17.6% |
| POP_TOP | 720 | 17.6% |
| POP_JUMP_IF_NONE | 120 | 2.9% |
| FOR_ITER_RANGE | 120 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXIT_INIT_CHECK | 3,120 | 76.5% |
| POP_TOP | 840 | 20.6% |
| INTERPRETER_EXIT | 120 | 2.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 18,563,280 | 37.7% |
| RETURN_VALUE | 11,885,160 | 24.1% |
| LOAD_FAST | 9,150,840 | 18.6% |
| LOAD_CONST | 5,104,920 | 10.4% |
| BINARY_SUBSCR_LIST_INT | 3,989,400 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,187,000 | 65.4% |
| LOAD_GLOBAL_BUILTIN | 7,894,800 | 16.0% |
| JUMP_FORWARD | 5,040,600 | 10.2% |
| LOAD_GLOBAL_MODULE | 2,790,600 | 5.7% |
| LOAD_CONST | 1,200,000 | 2.4% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,184,400 | 69.9% |
| BINARY_OP_SUBTRACT_INT | 1,200,000 | 20.0% |
| BINARY_OP | 600,840 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,985,240 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,300,400 | 94.6% |
| LOAD_ATTR_INSTANCE_VALUE | 300,720 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,184,400 | 74.7% |
| LOAD_FAST | 1,116,000 | 19.9% |
| LOAD_CONST | 300,720 | 5.4% |


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

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,500,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,200,000 | 80.0% |
| LOAD_FAST | 300,720 | 20.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,105,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,989,400 | 78.1% |
| LOAD_FAST | 1,116,000 | 21.9% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,400 | 76.9% |
| RETURN_VALUE | 720 | 23.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,120 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 88.9% |
| CALL | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 120 | 66.7% |
| STORE_FAST | 60 | 33.3% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,894,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,894,800 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 31,104,120 | 57.9% |
| LOAD_ATTR_INSTANCE_VALUE | 13,098,000 | 24.4% |
| LOAD_FAST | 5,384,640 | 10.0% |
| LOAD_FAST_LOAD_FAST | 2,790,240 | 5.2% |
| LOAD_GLOBAL_MODULE | 1,200,000 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 53,577,000 | 99.8% |
| CALL_PY_EXACT_ARGS | 99,120 | 0.2% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,111,680 | 42.1% |
| LOAD_ATTR_INSTANCE_VALUE | 2,970,960 | 30.4% |
| LOAD_CONST | 2,679,400 | 27.4% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,762,060 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 279,300 | 99.9% |
| EXTENDED_ARG | 240 | 0.1% |
| JUMP_BACKWARD | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 279,480 | 99.9% |
| RETURN_CONST | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 91,488,960 | 83.1% |
| LOAD_FAST_LOAD_FAST | 7,894,800 | 7.2% |
| COPY | 5,985,240 | 5.4% |
| LOAD_GLOBAL_MODULE | 3,991,200 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 725,420 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 21,450,600 | 19.5% |
| STORE_FAST | 18,563,280 | 16.9% |
| LOAD_FAST | 15,353,040 | 13.9% |
| CALL_PY_EXACT_ARGS | 13,098,000 | 11.9% |
| TO_BOOL_BOOL | 11,405,700 | 10.4% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,694,360 | 77.2% |
| ENTER_EXECUTOR | 11,881,080 | 22.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 454,360 | 0.8% |
| RETURN_VALUE | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 31,104,120 | 57.6% |
| LOAD_FAST_LOAD_FAST | 10,684,320 | 19.8% |
| LOAD_FAST | 10,587,840 | 19.6% |
| LOAD_GLOBAL_MODULE | 1,199,880 | 2.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 454,360 | 0.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_ATTR | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 60.0% |
| PUSH_NULL | 40 | 40.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,894,800 | 100.0% |
| RESUME_CHECK | 120 | 0.0% |
| POP_JUMP_IF_FALSE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,894,980 | 100.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,334,520 | 37.3% |
| POP_JUMP_IF_FALSE | 5,167,080 | 18.6% |
| RESUME_CHECK | 5,106,760 | 18.4% |
| STORE_FAST | 2,790,600 | 10.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,674,480 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 7,894,800 | 28.5% |
| TO_BOOL_BOOL | 5,745,480 | 20.7% |
| COMPARE_OP_INT | 4,111,680 | 14.8% |
| LOAD_ATTR_INSTANCE_VALUE | 3,991,200 | 14.4% |
| COPY | 3,905,160 | 14.1% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 53,577,000 | 100.0% |
| CALL_ALLOC_AND_ENTER_INIT | 3,120 | 0.0% |
| CACHE | 120 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,476,960 | 75.5% |
| LOAD_CONST | 7,995,480 | 14.9% |
| LOAD_GLOBAL_MODULE | 5,106,760 | 9.5% |
| LOAD_FAST_LOAD_FAST | 960 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,098,040 | 75.4% |
| SWAP | 5,985,240 | 13.6% |
| LOAD_FAST_LOAD_FAST | 4,666,080 | 10.6% |
| STORE_ATTR_INSTANCE_VALUE | 122,400 | 0.3% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,485,280 | 69.5% |
| LOAD_CONST | 11,540,880 | 26.3% |
| LOAD_GLOBAL_MODULE | 1,437,720 | 3.3% |
| LOAD_FAST_LOAD_FAST | 284,040 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 122,400 | 0.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 301,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 300,720 | 99.8% |
| RETURN_CONST | 720 | 0.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 30,066,300 | 41.4% |
| RETURN_VALUE | 17,425,560 | 24.0% |
| LOAD_ATTR_INSTANCE_VALUE | 11,405,700 | 15.7% |
| CALL_ISINSTANCE | 7,894,800 | 10.9% |
| LOAD_GLOBAL_MODULE | 5,745,480 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 44,621,100 | 61.5% |
| POP_JUMP_IF_TRUE | 16,511,040 | 22.8% |
| UNARY_NOT | 11,405,700 | 15.7% |


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
|          hit |      5105400 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1117680 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |    103065000 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2999760 | 23.9% |
|          hit |      9572100 | 76.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 2.6% |
| Failure | 760 | 97.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 300 | 39.5% |
| floor divide | 280 | 36.8% |
| xor | 140 | 18.4% |
| multiply different types | 40 | 5.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          300 | 0.0% |
| specialization.deopt |        99120 | 0.2% |
|          hit |     60500340 | 92.0% |
|         miss |      5253360 | 8.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 99,140 | 99.9% |
| Failure | 80 | 0.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 75.0% |
| other | 20 | 25.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     10599780 | 100.0% |

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
|          hit |       279660 | 100.0% |


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
| specialization.deferred |          740 | 0.0% |
| specialization.deopt |      1179780 | 0.7% |
|          hit |    116764960 | 65.1% |
|         miss |     62529240 | 34.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,179,820 | 100.0% |
| Failure | 120 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 120 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     52487680 | 100.0% |

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
| specialization.deopt |       122400 | 0.3% |
|          hit |     38217480 | 85.5% |
|         miss |      6492960 | 14.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 122,400 | 100.0% |
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
| Basic | 512,311,440 | 47.4% |
| Not specialized | 188,080,240 | 17.4% |
| Specialized | 379,567,080 | 35.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,032,300 | 100.0% |
| BINARY_OP | 2,999,760 | 0.0% |
| LOAD_ATTR | 740 | 0.0% |
| CALL | 300 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| UNARY_NOT | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 38,447,320 | 51.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 24,081,920 | 32.4% |
| STORE_ATTR_INSTANCE_VALUE | 6,492,960 | 8.7% |
| CALL_PY_EXACT_ARGS | 5,253,360 | 7.1% |
| RESUME_CHECK | 20 | 0.0% |
| RESUME | 20 | 0.0% |
| UNARY_NOT | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 120 | 0.0% |
| Calls to Python functions inlined | 57,759,660 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 57,762,900 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,240 | 0.0% |
| Frees to freelist | 1,660 |  |
| Allocations | 7,088,280 | 100.0% |
| Allocations to 512 bytes | 7,088,280 | 100.0% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 7,084,160 |  |
| New values | 0 |  |
| Interpreter increfs | 423,838,940 | 83.5% |
| Interpreter decrefs | 477,403,200 | 92.7% |
| Increfs | 83,934,684 | 16.5% |
| Decrefs | 37,452,924 | 7.3% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 65,586,396 |  |
| Method cache misses | 3,435,824 |  |
| Method cache collisions | 3,435,824 |  |
| Method cache dunder hits | 1,560 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 1,920 | 166,520 |
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
Stats gathered on: 2023-10-11
