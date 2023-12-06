
# Pystats results

- benchmark: richards_super
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 257,953,800 | 22.0% | 22.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 110,085,620 | 9.4% | 31.3% | 34.9% |
| TO_BOOL_BOOL | 72,537,840 | 6.2% | 37.5% |  |
| CALL_PY_EXACT_ARGS | 61,570,920 | 5.2% | 42.7% | 8.5% |
| RESUME_CHECK | 61,475,100 | 5.2% | 48.0% | 0.0% |
| RETURN_VALUE | 54,493,860 | 4.6% | 52.6% |  |
| POP_JUMP_IF_FALSE | 54,383,160 | 4.6% | 57.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 54,030,520 | 4.6% | 61.8% | 44.6% |
| STORE_ATTR_INSTANCE_VALUE | 51,867,360 | 4.4% | 66.3% | 22.6% |
| STORE_FAST | 49,252,620 | 4.2% | 70.5% |  |
| LOAD_CONST | 39,481,140 | 3.4% | 73.8% |  |
| POP_TOP | 36,632,700 | 3.1% | 76.9% |  |
| COPY | 36,051,540 | 3.1% | 80.0% |  |
| LOAD_FAST_LOAD_FAST | 31,141,320 | 2.7% | 82.6% |  |
| LOAD_GLOBAL_MODULE | 27,715,180 | 2.4% | 85.0% |  |
| POP_JUMP_IF_NOT_NONE | 23,066,160 | 2.0% | 87.0% |  |
| POP_JUMP_IF_NONE | 16,842,120 | 1.4% | 88.4% |  |
| POP_JUMP_IF_TRUE | 16,511,040 | 1.4% | 89.8% |  |
| LOAD_GLOBAL_BUILTIN | 15,790,500 | 1.3% | 91.2% |  |
| ENTER_EXECUTOR | 13,096,320 | 1.1% | 92.3% |  |
| UNARY_NOT | 11,405,700 | 1.0% | 93.2% |  |
| COMPARE_OP_INT | 9,762,060 | 0.8% | 94.1% |  |
| JUMP_FORWARD | 8,109,840 | 0.7% | 94.8% |  |
| RETURN_CONST | 7,898,880 | 0.7% | 95.4% |  |
| LOAD_DEREF | 7,895,640 | 0.7% | 96.1% |  |
| COPY_FREE_VARS | 7,895,580 | 0.7% | 96.8% |  |
| LOAD_SUPER_ATTR_METHOD | 7,895,520 | 0.7% | 97.4% |  |
| CALL_ISINSTANCE | 7,894,800 | 0.7% | 98.1% |  |
| SWAP | 5,985,240 | 0.5% | 98.6% |  |
| BINARY_OP_ADD_INT | 5,601,120 | 0.5% | 99.1% |  |
| BINARY_SUBSCR_LIST_INT | 5,105,400 | 0.4% | 99.5% |  |
| BINARY_OP | 3,000,540 | 0.3% | 99.8% |  |
| BINARY_OP_SUBTRACT_INT | 1,500,720 | 0.1% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 301,440 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 279,660 | 0.0% | 100.0% |  |
| GET_ITER | 279,420 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 3,120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 3,120 | 0.0% | 100.0% |  |
| BUILD_LIST | 960 | 0.0% | 100.0% |  |
| CALL | 400 | 0.0% | 100.0% |  |
| PUSH_NULL | 360 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 360 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 240 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 180 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 80 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 91,488,960 | 7.8% | 7.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 53,577,000 | 4.6% | 12.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 44,621,100 | 3.8% | 16.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 41,694,360 | 3.5% | 19.7% |
| RESUME_CHECK LOAD_FAST | 40,476,960 | 3.4% | 23.1% |
| POP_TOP LOAD_FAST | 33,561,720 | 2.9% | 26.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 33,098,760 | 2.8% | 28.8% |
| STORE_FAST LOAD_FAST | 32,187,000 | 2.7% | 31.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 31,104,120 | 2.6% | 34.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 30,485,280 | 2.6% | 36.8% |
| COPY TO_BOOL_BOOL | 30,066,300 | 2.6% | 39.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 22,639,680 | 1.9% | 41.3% |
| LOAD_CONST LOAD_FAST | 21,894,600 | 1.9% | 43.1% |
| LOAD_ATTR_INSTANCE_VALUE COPY | 21,450,600 | 1.8% | 45.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 19,064,280 | 1.6% | 46.6% |
| RETURN_VALUE RETURN_VALUE | 18,579,120 | 1.6% | 48.2% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 18,563,280 | 1.6% | 49.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 17,486,640 | 1.5% | 51.2% |
| RETURN_VALUE TO_BOOL_BOOL | 17,425,560 | 1.5% | 52.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 16,842,120 | 1.4% | 54.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 16,511,040 | 1.4% | 55.6% |
| LOAD_FAST RETURN_VALUE | 15,973,020 | 1.4% | 56.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 15,353,040 | 1.3% | 58.2% |
| POP_JUMP_IF_FALSE POP_TOP | 14,670,660 | 1.2% | 59.5% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 13,098,000 | 1.1% | 60.6% |
| POP_JUMP_IF_NONE ENTER_EXECUTOR | 12,795,600 | 1.1% | 61.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 12,560,880 | 1.1% | 62.8% |
| RETURN_VALUE STORE_FAST | 11,885,160 | 1.0% | 63.8% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 11,881,080 | 1.0% | 64.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 11,540,880 | 1.0% | 65.8% |
| TO_BOOL_BOOL UNARY_NOT | 11,405,700 | 1.0% | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 11,405,700 | 1.0% | 67.7% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 10,684,440 | 0.9% | 68.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 10,684,320 | 0.9% | 69.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 10,587,840 | 0.9% | 70.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 10,334,520 | 0.9% | 71.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 9,762,060 | 0.8% | 72.1% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 9,700,260 | 0.8% | 73.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 9,263,640 | 0.8% | 73.7% |
| LOAD_FAST STORE_FAST | 9,150,840 | 0.8% | 74.5% |
| UNARY_NOT COPY | 8,615,700 | 0.7% | 75.3% |
| POP_JUMP_IF_TRUE POP_TOP | 8,615,700 | 0.7% | 76.0% |
| RESUME_CHECK LOAD_CONST | 7,995,480 | 0.7% | 76.7% |
| JUMP_FORWARD LOAD_FAST | 7,970,160 | 0.7% | 77.4% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 7,897,920 | 0.7% | 78.0% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 7,895,760 | 0.7% | 78.7% |
| RETURN_CONST POP_TOP | 7,895,640 | 0.7% | 79.4% |
| COPY_FREE_VARS RESUME_CHECK | 7,895,580 | 0.7% | 80.0% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 7,895,520 | 0.7% | 80.7% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 7,895,520 | 0.7% | 81.4% |
| LOAD_DEREF LOAD_FAST | 7,895,520 | 0.7% | 82.1% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 7,895,400 | 0.7% | 82.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 7,894,980 | 0.7% | 83.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 7,894,800 | 0.7% | 84.1% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 7,894,800 | 0.7% | 84.7% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 7,894,800 | 0.7% | 85.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 7,894,800 | 0.7% | 86.1% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 7,894,800 | 0.7% | 86.8% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 7,894,800 | 0.7% | 87.4% |
| POP_JUMP_IF_FALSE RETURN_VALUE | 6,779,400 | 0.6% | 88.0% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 5,985,240 | 0.5% | 88.5% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 5,985,240 | 0.5% | 89.0% |
| LOAD_GLOBAL_MODULE TO_BOOL_BOOL | 5,745,480 | 0.5% | 89.5% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NOT_NONE | 5,579,520 | 0.5% | 90.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,385,240 | 0.5% | 90.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 5,300,400 | 0.5% | 90.9% |
| RETURN_VALUE POP_TOP | 5,204,400 | 0.4% | 91.3% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 5,167,080 | 0.4% | 91.8% |
| POP_JUMP_IF_FALSE LOAD_CONST | 5,126,160 | 0.4% | 92.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 5,106,040 | 0.4% | 92.7% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 5,105,400 | 0.4% | 93.1% |
| LOAD_CONST STORE_FAST | 5,104,920 | 0.4% | 93.5% |
| STORE_FAST JUMP_FORWARD | 5,040,600 | 0.4% | 94.0% |
| BINARY_OP_ADD_INT SWAP | 4,184,400 | 0.4% | 94.3% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 4,111,680 | 0.3% | 94.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_INSTANCE_VALUE | 3,991,200 | 0.3% | 95.0% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 3,989,400 | 0.3% | 95.3% |
| LOAD_GLOBAL_MODULE COPY | 3,905,160 | 0.3% | 95.7% |
| POP_TOP JUMP_FORWARD | 3,069,240 | 0.3% | 95.9% |
| LOAD_CONST BINARY_OP | 2,998,800 | 0.3% | 96.2% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 2,970,960 | 0.3% | 96.4% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 2,886,600 | 0.2% | 96.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 2,831,040 | 0.2% | 96.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,790,600 | 0.2% | 97.2% |
| UNARY_NOT RETURN_VALUE | 2,790,000 | 0.2% | 97.4% |
| LOAD_CONST COMPARE_OP_INT | 2,679,400 | 0.2% | 97.6% |
| LOAD_FAST COPY | 2,080,080 | 0.2% | 97.8% |
| BINARY_OP LOAD_CONST | 1,798,920 | 0.2% | 98.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,674,480 | 0.1% | 98.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 1,500,720 | 0.1% | 98.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,437,720 | 0.1% | 98.4% |
| RETURN_VALUE LOAD_FAST | 1,397,400 | 0.1% | 98.5% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 1,215,240 | 0.1% | 98.6% |
| STORE_FAST LOAD_CONST | 1,200,000 | 0.1% | 98.7% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 1,200,000 | 0.1% | 98.8% |
| BINARY_OP_SUBTRACT_INT SWAP | 1,200,000 | 0.1% | 98.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_MODULE | 1,199,880 | 0.1% | 99.0% |
| LOAD_FAST LOAD_CONST | 1,116,300 | 0.1% | 99.1% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 1,116,000 | 0.1% | 99.2% |
| BINARY_OP_ADD_INT LOAD_FAST | 1,116,000 | 0.1% | 99.3% |


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
| POP_JUMP_IF_FALSE | 14,670,660 | 40.0% |
| POP_JUMP_IF_TRUE | 8,615,700 | 23.5% |
| RETURN_CONST | 7,895,640 | 21.6% |
| RETURN_VALUE | 5,204,400 | 14.2% |
| ENTER_EXECUTOR | 246,120 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,561,720 | 91.6% |
| JUMP_FORWARD | 3,069,240 | 8.4% |
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
| CALL_PY_EXACT_ARGS | 7,894,800 | 100.0% |
| CALL_ALLOC_AND_ENTER_INIT | 720 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,895,580 | 100.0% |


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
| STORE_ATTR_INSTANCE_VALUE | 11,540,880 | 29.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,263,640 | 23.5% |
| RESUME_CHECK | 7,995,480 | 20.3% |
| POP_JUMP_IF_FALSE | 5,126,160 | 13.0% |
| BINARY_OP | 1,798,920 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,894,600 | 55.5% |
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
| LOAD_GLOBAL_BUILTIN | 7,895,520 | 100.0% |
| STORE_FAST | 60 | 0.0% |
| NOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,895,520 | 100.0% |
| STORE_FAST | 60 | 0.0% |
| PUSH_NULL | 60 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 40,476,960 | 15.7% |
| POP_TOP | 33,561,720 | 13.0% |
| STORE_FAST | 32,187,000 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 30,485,280 | 11.8% |
| POP_JUMP_IF_FALSE | 22,639,680 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 91,488,960 | 35.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 41,694,360 | 16.2% |
| STORE_ATTR_INSTANCE_VALUE | 33,098,760 | 12.8% |
| POP_JUMP_IF_NOT_NONE | 17,486,640 | 6.8% |
| POP_JUMP_IF_NONE | 16,842,120 | 6.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 10,684,320 | 34.3% |
| RESUME_CHECK | 7,895,760 | 25.4% |
| LOAD_SUPER_ATTR_METHOD | 7,895,400 | 25.4% |
| POP_JUMP_IF_NOT_NONE | 2,886,600 | 9.3% |
| POP_JUMP_IF_NONE | 1,215,240 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 12,560,880 | 40.3% |
| CALL_PY_EXACT_ARGS | 10,684,440 | 34.3% |
| LOAD_ATTR_INSTANCE_VALUE | 7,894,800 | 25.4% |
| LOAD_FAST_LOAD_FAST | 600 | 0.0% |
| LOAD_FAST | 600 | 0.0% |


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
| LOAD_GLOBAL_BUILTIN | 7,894,800 | 47.8% |
| RETURN_VALUE | 540 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 7,897,920 | 100.0% |
| POP_TOP | 720 | 0.0% |
| POP_JUMP_IF_NONE | 120 | 0.0% |
| FOR_ITER_RANGE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,895,640 | 100.0% |
| EXIT_INIT_CHECK | 3,120 | 0.0% |
| INTERPRETER_EXIT | 120 | 0.0% |


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
| RESUME_CHECK | 2,400 | 76.9% |
| COPY_FREE_VARS | 720 | 23.1% |


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
| LOAD_ATTR_METHOD_WITH_VALUES | 31,104,120 | 50.5% |
| LOAD_ATTR_INSTANCE_VALUE | 13,098,000 | 21.3% |
| LOAD_FAST_LOAD_FAST | 10,684,440 | 17.4% |
| LOAD_FAST | 5,385,240 | 8.7% |
| LOAD_GLOBAL_MODULE | 1,200,000 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 53,577,000 | 87.0% |
| COPY_FREE_VARS | 7,894,800 | 12.8% |
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
| STORE_FAST | 7,894,800 | 50.0% |
| POP_JUMP_IF_TRUE | 7,894,800 | 50.0% |
| RESUME_CHECK | 840 | 0.0% |
| POP_JUMP_IF_FALSE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 7,895,520 | 50.0% |
| LOAD_FAST | 7,894,980 | 50.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,334,520 | 37.3% |
| POP_JUMP_IF_FALSE | 5,167,080 | 18.6% |
| RESUME_CHECK | 5,106,040 | 18.4% |
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

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,895,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,895,400 | 100.0% |
| LOAD_FAST | 120 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 53,577,000 | 87.2% |
| COPY_FREE_VARS | 7,895,580 | 12.8% |
| CALL_ALLOC_AND_ENTER_INIT | 2,400 | 0.0% |
| CACHE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,476,960 | 65.8% |
| LOAD_CONST | 7,995,480 | 13.0% |
| LOAD_FAST_LOAD_FAST | 7,895,760 | 12.8% |
| LOAD_GLOBAL_MODULE | 5,106,040 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 840 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,098,760 | 63.8% |
| LOAD_FAST_LOAD_FAST | 12,560,880 | 24.2% |
| SWAP | 5,985,240 | 11.5% |
| STORE_ATTR_INSTANCE_VALUE | 221,520 | 0.4% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,485,280 | 58.8% |
| LOAD_CONST | 11,540,880 | 22.3% |
| RETURN_CONST | 7,897,920 | 15.2% |
| LOAD_GLOBAL_MODULE | 1,437,720 | 2.8% |
| LOAD_FAST_LOAD_FAST | 284,040 | 0.5% |


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
| LOAD_CONST | 720 | 0.2% |


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
|          hit |       301440 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     72537840 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2999760 | 29.7% |
|          hit |      7101900 | 70.3% |

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
| specialization.deopt |        99120 | 0.1% |
|          hit |     64215660 | 92.4% |
|         miss |      5253360 | 7.6% |

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
|          hit |      9762060 | 100.0% |

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
| specialization.deferred |           20 | 0.0% |
| specialization.deopt |      1179780 | 0.7% |
|          hit |    101587000 | 61.9% |
|         miss |     62529240 | 38.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,179,820 | 100.0% |
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
|          hit |     43505680 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      7895520 | 100.0% |


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
| specialization.deopt |       221520 | 0.4% |
|          hit |     40120560 | 77.4% |
|         miss |     11746800 | 22.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 221,520 | 100.0% |
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
| Basic | 567,578,640 | 48.3% |
| Not specialized | 193,333,240 | 16.5% |
| Specialized | 413,887,800 | 35.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,032,300 | 100.0% |
| BINARY_OP | 2,999,760 | 0.0% |
| CALL | 300 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
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
| LOAD_ATTR_INSTANCE_VALUE | 38,447,320 | 48.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 24,081,920 | 30.3% |
| STORE_ATTR_INSTANCE_VALUE | 11,746,800 | 14.8% |
| CALL_PY_EXACT_ARGS | 5,253,360 | 6.6% |
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
| Calls to Python functions inlined | 61,474,980 | 100.0% |
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
| Frames pushed | 65,657,700 | 106.8% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,320 | 0.0% |
| Frees to freelist | 1,660 |  |
| Allocations | 7,088,200 | 100.0% |
| Allocations to 512 bytes | 7,088,200 | 100.0% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 7,084,160 |  |
| New values | 0 |  |
| Interpreter increfs | 476,789,180 | 80.9% |
| Interpreter decrefs | 538,239,120 | 90.3% |
| Increfs | 112,496,383 | 19.1% |
| Decrefs | 58,128,463 | 9.7% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 72,841,333 |  |
| Method cache misses | 1,434,727 |  |
| Method cache collisions | 1,434,727 |  |
| Method cache dunder hits | 0 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 1,920 | 165,960 |
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
| Traces executed | 13,096,320 |  |
| Uops executed | 351,091,680 | 26 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
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
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 8,616,120 | 65.8% |
| <= 32 | 0 | 0.0% |
| <= 64 | 4,200,960 | 32.1% |
| <= 128 | 21,480 | 0.2% |
| <= 256 | 257,760 | 2.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 98,376,720 | 28.0% | 28.0% |
| TO_BOOL_BOOL | 30,527,160 | 8.7% | 36.7% |
| _POP_JUMP_IF_TRUE | 28,970,760 | 8.3% | 45.0% |
| _GUARD_TYPE_VERSION | 27,896,760 | 7.9% | 52.9% |
| LOAD_FAST | 27,875,280 | 7.9% | 60.9% |
| _LOAD_GLOBAL_MODULE | 16,876,800 | 4.8% | 65.7% |
| _GUARD_GLOBALS_VERSION | 16,876,800 | 4.8% | 70.5% |
| _LOAD_ATTR_INSTANCE_VALUE | 10,998,480 | 3.1% | 73.6% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 10,998,480 | 3.1% | 76.7% |
| COPY | 8,528,280 | 2.4% | 79.2% |
| _SAVE_CURRENT_IP | 7,444,440 | 2.1% | 81.3% |
| _PUSH_FRAME | 4,179,480 | 1.2% | 82.5% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 4,179,480 | 1.2% | 83.7% |
| _INIT_CALL_PY_EXACT_ARGS | 4,179,480 | 1.2% | 84.9% |
| _GUARD_KEYS_VERSION | 4,179,480 | 1.2% | 86.0% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 4,179,480 | 1.2% | 87.2% |
| _CHECK_STACK_SPACE | 4,179,480 | 1.2% | 88.4% |
| _CHECK_PEP_523 | 4,179,480 | 1.2% | 89.6% |
| _CHECK_FUNCTION_EXACT_ARGS | 4,179,480 | 1.2% | 90.8% |
| RESUME_CHECK | 4,179,480 | 1.2% | 92.0% |
| POP_TOP | 3,790,320 | 1.1% | 93.1% |
| UNARY_NOT | 3,511,080 | 1.0% | 94.1% |
| _POP_FRAME | 3,264,960 | 0.9% | 95.0% |
| LOAD_CONST | 2,491,680 | 0.7% | 95.7% |
| _GUARD_BOTH_INT | 2,470,200 | 0.7% | 96.4% |
| _BINARY_OP_ADD_INT | 1,653,960 | 0.5% | 96.9% |
| _EXIT_TRACE | 1,215,240 | 0.3% | 97.2% |
| _ITER_CHECK_RANGE | 1,116,960 | 0.3% | 97.6% |
| _IS_ITER_EXHAUSTED_RANGE | 1,116,960 | 0.3% | 97.9% |
| _STORE_ATTR_INSTANCE_VALUE | 837,720 | 0.2% | 98.1% |
| _ITER_NEXT_RANGE | 837,720 | 0.2% | 98.3% |
| _GUARD_DORV_VALUES | 837,720 | 0.2% | 98.6% |
| SWAP | 837,720 | 0.2% | 98.8% |
| STORE_FAST | 837,720 | 0.2% | 99.1% |
| COMPARE_OP_INT | 837,720 | 0.2% | 99.3% |
| _JUMP_TO_TOP | 816,240 | 0.2% | 99.5% |
| _BINARY_OP_SUBTRACT_INT | 816,240 | 0.2% | 99.8% |
| STORE_SUBSCR_LIST_INT | 816,240 | 0.2% | 100.0% |


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
Stats gathered on: 2023-10-04
