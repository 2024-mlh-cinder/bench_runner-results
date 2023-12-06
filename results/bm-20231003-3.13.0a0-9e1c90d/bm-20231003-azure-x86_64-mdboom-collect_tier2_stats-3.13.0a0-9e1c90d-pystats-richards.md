
# Pystats results

- benchmark: richards
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 264,298,800 | 22.4% | 22.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 120,406,660 | 10.2% | 32.6% | 39.0% |
| TO_BOOL_BOOL | 90,269,400 | 7.7% | 40.3% |  |
| POP_JUMP_IF_FALSE | 65,261,880 | 5.5% | 45.8% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 58,293,880 | 4.9% | 50.8% | 48.9% |
| CALL_PY_EXACT_ARGS | 57,855,600 | 4.9% | 55.7% | 9.1% |
| RESUME_CHECK | 57,759,780 | 4.9% | 60.6% | 0.0% |
| RETURN_VALUE | 57,758,820 | 4.9% | 65.5% |  |
| STORE_FAST | 49,252,620 | 4.2% | 69.7% |  |
| STORE_ATTR_INSTANCE_VALUE | 44,710,440 | 3.8% | 73.5% | 14.5% |
| COPY | 43,742,100 | 3.7% | 77.2% |  |
| LOAD_CONST | 41,134,380 | 3.5% | 80.7% |  |
| POP_TOP | 32,248,980 | 2.7% | 83.4% |  |
| LOAD_GLOBAL_MODULE | 31,797,100 | 2.7% | 86.1% |  |
| POP_JUMP_IF_NOT_NONE | 23,066,160 | 2.0% | 88.1% |  |
| POP_JUMP_IF_TRUE | 20,690,520 | 1.8% | 89.8% |  |
| POP_JUMP_IF_NONE | 16,842,120 | 1.4% | 91.2% |  |
| LOAD_FAST_LOAD_FAST | 15,352,440 | 1.3% | 92.5% |  |
| UNARY_NOT | 14,916,780 | 1.3% | 93.8% |  |
| ENTER_EXECUTOR | 13,912,560 | 1.2% | 95.0% |  |
| COMPARE_OP_INT | 10,599,780 | 0.9% | 95.9% |  |
| JUMP_FORWARD | 8,109,840 | 0.7% | 96.6% |  |
| LOAD_GLOBAL_BUILTIN | 7,894,980 | 0.7% | 97.2% |  |
| CALL_ISINSTANCE | 7,894,800 | 0.7% | 97.9% |  |
| BINARY_OP_ADD_INT | 6,417,360 | 0.5% | 98.5% |  |
| SWAP | 5,985,240 | 0.5% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 5,105,400 | 0.4% | 99.4% |  |
| BINARY_OP | 3,000,540 | 0.3% | 99.7% |  |
| BINARY_OP_SUBTRACT_INT | 2,316,960 | 0.2% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 1,117,680 | 0.1% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 101,649,720 | 8.6% | 8.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 57,756,480 | 4.9% | 13.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 54,662,100 | 4.6% | 18.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 44,959,320 | 3.8% | 22.0% |
| RESUME_CHECK LOAD_FAST | 44,656,440 | 3.8% | 25.8% |
| COPY TO_BOOL_BOOL | 37,756,860 | 3.2% | 29.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 35,283,600 | 3.0% | 32.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 33,098,040 | 2.8% | 34.8% |
| STORE_FAST LOAD_FAST | 32,187,000 | 2.7% | 37.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 31,323,000 | 2.7% | 40.2% |
| POP_TOP LOAD_FAST | 29,178,000 | 2.5% | 42.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 25,904,640 | 2.2% | 44.8% |
| LOAD_ATTR_INSTANCE_VALUE COPY | 25,630,080 | 2.2% | 47.0% |
| LOAD_CONST LOAD_FAST | 21,893,880 | 1.9% | 48.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 20,690,520 | 1.8% | 50.6% |
| RETURN_VALUE TO_BOOL_BOOL | 20,690,520 | 1.8% | 52.4% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 19,064,280 | 1.6% | 54.0% |
| RETURN_VALUE RETURN_VALUE | 18,579,120 | 1.6% | 55.6% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 18,563,280 | 1.6% | 57.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 17,486,640 | 1.5% | 58.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 16,842,120 | 1.4% | 60.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 16,169,280 | 1.4% | 61.4% |
| LOAD_FAST RETURN_VALUE | 15,973,020 | 1.4% | 62.8% |
| TO_BOOL_BOOL UNARY_NOT | 14,916,780 | 1.3% | 64.1% |
| POP_JUMP_IF_FALSE POP_TOP | 14,916,780 | 1.3% | 65.3% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 14,916,780 | 1.3% | 66.6% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 13,098,000 | 1.1% | 67.7% |
| POP_JUMP_IF_NONE ENTER_EXECUTOR | 12,795,600 | 1.1% | 68.8% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 12,795,600 | 1.1% | 69.9% |
| UNARY_NOT COPY | 12,126,780 | 1.0% | 70.9% |
| POP_JUMP_IF_TRUE POP_TOP | 12,126,780 | 1.0% | 71.9% |
| RETURN_VALUE STORE_FAST | 11,885,160 | 1.0% | 72.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 11,540,880 | 1.0% | 73.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 10,684,320 | 0.9% | 74.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 10,599,780 | 0.9% | 75.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 10,587,840 | 0.9% | 76.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 10,334,520 | 0.9% | 77.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 10,101,360 | 0.9% | 78.4% |
| POP_JUMP_IF_FALSE RETURN_VALUE | 10,044,360 | 0.9% | 79.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 9,700,260 | 0.8% | 80.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 9,248,280 | 0.8% | 80.8% |
| LOAD_FAST STORE_FAST | 9,150,840 | 0.8% | 81.6% |
| LOAD_GLOBAL_MODULE TO_BOOL_BOOL | 9,010,440 | 0.8% | 82.4% |
| RESUME_CHECK LOAD_CONST | 7,995,480 | 0.7% | 83.0% |
| JUMP_FORWARD LOAD_FAST | 7,970,160 | 0.7% | 83.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 7,894,980 | 0.7% | 84.4% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 7,894,800 | 0.7% | 85.0% |
| POP_JUMP_IF_TRUE LOAD_FAST | 7,894,800 | 0.7% | 85.7% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 7,894,800 | 0.7% | 86.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 7,894,800 | 0.7% | 87.1% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 7,894,800 | 0.7% | 87.7% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 5,985,240 | 0.5% | 88.2% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 5,985,240 | 0.5% | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NOT_NONE | 5,579,520 | 0.5% | 89.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,384,640 | 0.5% | 89.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 5,300,400 | 0.4% | 90.1% |
| RETURN_VALUE POP_TOP | 5,204,400 | 0.4% | 90.6% |
| POP_JUMP_IF_FALSE LOAD_CONST | 5,147,640 | 0.4% | 91.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 5,106,760 | 0.4% | 91.4% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 5,105,400 | 0.4% | 91.9% |
| LOAD_CONST STORE_FAST | 5,104,920 | 0.4% | 92.3% |
| STORE_FAST JUMP_FORWARD | 5,040,600 | 0.4% | 92.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 4,666,080 | 0.4% | 93.1% |
| BINARY_OP_ADD_INT SWAP | 4,184,400 | 0.4% | 93.5% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 4,111,680 | 0.3% | 93.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_INSTANCE_VALUE | 3,991,200 | 0.3% | 94.2% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 3,989,400 | 0.3% | 94.5% |
| LOAD_GLOBAL_MODULE COPY | 3,905,160 | 0.3% | 94.8% |
| LOAD_CONST COMPARE_OP_INT | 3,517,120 | 0.3% | 95.1% |
| POP_TOP JUMP_FORWARD | 3,069,240 | 0.3% | 95.4% |
| LOAD_CONST BINARY_OP | 2,998,800 | 0.3% | 95.6% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 2,970,960 | 0.3% | 95.9% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 2,886,600 | 0.2% | 96.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 2,831,040 | 0.2% | 96.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,790,600 | 0.2% | 96.6% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 2,790,240 | 0.2% | 96.9% |
| UNARY_NOT RETURN_VALUE | 2,790,000 | 0.2% | 97.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 2,316,960 | 0.2% | 97.3% |
| LOAD_FAST COPY | 2,080,080 | 0.2% | 97.5% |
| BINARY_OP LOAD_CONST | 1,798,920 | 0.2% | 97.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,674,480 | 0.1% | 97.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,437,720 | 0.1% | 97.9% |
| RETURN_VALUE LOAD_FAST | 1,397,400 | 0.1% | 98.0% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 1,215,240 | 0.1% | 98.1% |
| STORE_FAST LOAD_CONST | 1,200,000 | 0.1% | 98.2% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 1,200,000 | 0.1% | 98.3% |
| BINARY_OP_SUBTRACT_INT SWAP | 1,200,000 | 0.1% | 98.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_MODULE | 1,199,880 | 0.1% | 98.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,117,680 | 0.1% | 98.6% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 1,117,680 | 0.1% | 98.7% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 1,116,960 | 0.1% | 98.8% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_ADD_INT | 1,116,960 | 0.1% | 98.9% |
| BINARY_OP_SUBTRACT_INT LOAD_FAST | 1,116,960 | 0.1% | 99.0% |
| BINARY_OP_ADD_INT LOAD_CONST | 1,116,960 | 0.1% | 99.1% |
| LOAD_FAST LOAD_CONST | 1,116,180 | 0.1% | 99.2% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 1,116,000 | 0.1% | 99.3% |
| BINARY_OP_ADD_INT LOAD_FAST | 1,116,000 | 0.1% | 99.4% |
| POP_JUMP_IF_NOT_NONE LOAD_CONST | 1,115,280 | 0.1% | 99.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 885,700 | 0.1% | 99.5% |
| ENTER_EXECUTOR STORE_ATTR_INSTANCE_VALUE | 837,720 | 0.1% | 99.6% |


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
| POP_JUMP_IF_FALSE | 14,916,780 | 46.3% |
| POP_JUMP_IF_TRUE | 12,126,780 | 37.6% |
| RETURN_VALUE | 5,204,400 | 16.1% |
| RETURN_CONST | 840 | 0.0% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,178,000 | 90.5% |
| JUMP_FORWARD | 3,069,240 | 9.5% |
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
| RETURN_VALUE | 18,579,120 | 32.2% |
| LOAD_FAST | 15,973,020 | 27.7% |
| POP_JUMP_IF_FALSE | 10,044,360 | 17.4% |
| LOAD_ATTR_INSTANCE_VALUE | 9,700,260 | 16.8% |
| UNARY_NOT | 2,790,000 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 20,690,520 | 35.8% |
| RETURN_VALUE | 18,579,120 | 32.2% |
| STORE_FAST | 11,885,160 | 20.6% |
| POP_TOP | 5,204,400 | 9.0% |
| LOAD_FAST | 1,397,400 | 2.4% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 14,916,780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 12,126,780 | 81.3% |
| RETURN_VALUE | 2,790,000 | 18.7% |


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
| LOAD_ATTR_INSTANCE_VALUE | 25,630,080 | 58.6% |
| UNARY_NOT | 12,126,780 | 27.7% |
| LOAD_GLOBAL_MODULE | 3,905,160 | 8.9% |
| LOAD_FAST | 2,080,080 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 37,756,860 | 86.3% |
| LOAD_ATTR_INSTANCE_VALUE | 5,985,240 | 13.7% |


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
| POP_JUMP_IF_NONE | 12,795,600 | 92.0% |
| STORE_SUBSCR_LIST_INT | 1,116,960 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 12,795,600 | 92.0% |
| STORE_ATTR_INSTANCE_VALUE | 837,720 | 6.0% |
| LOAD_FAST | 279,240 | 2.0% |


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
| STORE_ATTR_INSTANCE_VALUE | 11,540,880 | 28.1% |
| LOAD_ATTR_INSTANCE_VALUE | 10,101,360 | 24.6% |
| RESUME_CHECK | 7,995,480 | 19.4% |
| POP_JUMP_IF_FALSE | 5,147,640 | 12.5% |
| BINARY_OP | 1,798,920 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,893,880 | 53.2% |
| BINARY_OP_ADD_INT | 5,300,400 | 12.9% |
| STORE_FAST | 5,104,920 | 12.4% |
| COMPARE_OP_INT | 3,517,120 | 8.6% |
| BINARY_OP | 2,998,800 | 7.3% |


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
| RESUME_CHECK | 44,656,440 | 16.9% |
| STORE_FAST | 32,187,000 | 12.2% |
| STORE_ATTR_INSTANCE_VALUE | 31,323,000 | 11.9% |
| POP_TOP | 29,178,000 | 11.0% |
| POP_JUMP_IF_FALSE | 25,904,640 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 101,649,720 | 38.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 44,959,320 | 17.0% |
| STORE_ATTR_INSTANCE_VALUE | 33,098,040 | 12.5% |
| POP_JUMP_IF_NOT_NONE | 17,486,640 | 6.6% |
| POP_JUMP_IF_NONE | 16,842,120 | 6.4% |


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
| TO_BOOL_BOOL | 54,662,100 | 83.8% |
| COMPARE_OP_INT | 10,599,780 | 16.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,904,640 | 39.7% |
| POP_TOP | 14,916,780 | 22.9% |
| RETURN_VALUE | 10,044,360 | 15.4% |
| LOAD_GLOBAL_MODULE | 9,248,280 | 14.2% |
| LOAD_CONST | 5,147,640 | 7.9% |


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
| TO_BOOL_BOOL | 20,690,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,126,780 | 58.6% |
| LOAD_FAST | 7,894,800 | 38.2% |
| RETURN_VALUE | 668,940 | 3.2% |


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
| LOAD_CONST | 5,300,400 | 82.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,116,960 | 17.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,184,400 | 65.2% |
| LOAD_CONST | 1,116,960 | 17.4% |
| LOAD_FAST | 1,116,000 | 17.4% |


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
| LOAD_CONST | 2,316,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,200,000 | 51.8% |
| LOAD_FAST | 1,116,960 | 48.2% |


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
| LOAD_ATTR_METHOD_WITH_VALUES | 35,283,600 | 61.0% |
| LOAD_ATTR_INSTANCE_VALUE | 13,098,000 | 22.6% |
| LOAD_FAST | 5,384,640 | 9.3% |
| LOAD_FAST_LOAD_FAST | 2,790,240 | 4.8% |
| LOAD_GLOBAL_MODULE | 1,200,000 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 57,756,480 | 99.8% |
| CALL_PY_EXACT_ARGS | 99,120 | 0.2% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 4,111,680 | 38.8% |
| LOAD_CONST | 3,517,120 | 33.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,970,960 | 28.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 10,599,780 | 100.0% |


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
| LOAD_FAST | 101,649,720 | 84.4% |
| LOAD_FAST_LOAD_FAST | 7,894,800 | 6.6% |
| COPY | 5,985,240 | 5.0% |
| LOAD_GLOBAL_MODULE | 3,991,200 | 3.3% |
| LOAD_ATTR_INSTANCE_VALUE | 885,700 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 25,630,080 | 21.3% |
| STORE_FAST | 18,563,280 | 15.4% |
| LOAD_FAST | 16,169,280 | 13.4% |
| TO_BOOL_BOOL | 14,916,780 | 12.4% |
| CALL_PY_EXACT_ARGS | 13,098,000 | 10.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,959,320 | 77.1% |
| ENTER_EXECUTOR | 12,795,600 | 22.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 538,240 | 0.9% |
| RETURN_VALUE | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 35,283,600 | 60.5% |
| LOAD_FAST_LOAD_FAST | 10,684,320 | 18.3% |
| LOAD_FAST | 10,587,840 | 18.2% |
| LOAD_GLOBAL_MODULE | 1,199,880 | 2.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 538,240 | 0.9% |


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
| LOAD_FAST | 10,334,520 | 32.5% |
| POP_JUMP_IF_FALSE | 9,248,280 | 29.1% |
| RESUME_CHECK | 5,106,760 | 16.1% |
| STORE_FAST | 2,790,600 | 8.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,674,480 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 9,010,440 | 28.3% |
| CALL_ISINSTANCE | 7,894,800 | 24.8% |
| COMPARE_OP_INT | 4,111,680 | 12.9% |
| LOAD_ATTR_INSTANCE_VALUE | 3,991,200 | 12.6% |
| COPY | 3,905,160 | 12.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 57,756,480 | 100.0% |
| CALL_ALLOC_AND_ENTER_INIT | 3,120 | 0.0% |
| CACHE | 120 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,656,440 | 77.3% |
| LOAD_CONST | 7,995,480 | 13.8% |
| LOAD_GLOBAL_MODULE | 5,106,760 | 8.8% |
| LOAD_FAST_LOAD_FAST | 960 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,098,040 | 74.0% |
| SWAP | 5,985,240 | 13.4% |
| LOAD_FAST_LOAD_FAST | 4,666,080 | 10.4% |
| ENTER_EXECUTOR | 837,720 | 1.9% |
| STORE_ATTR_INSTANCE_VALUE | 122,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,323,000 | 70.1% |
| LOAD_CONST | 11,540,880 | 25.8% |
| LOAD_GLOBAL_MODULE | 1,437,720 | 3.2% |
| LOAD_FAST_LOAD_FAST | 284,040 | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 122,400 | 0.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,117,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,116,960 | 99.9% |
| RETURN_CONST | 720 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 37,756,860 | 41.8% |
| RETURN_VALUE | 20,690,520 | 22.9% |
| LOAD_ATTR_INSTANCE_VALUE | 14,916,780 | 16.5% |
| LOAD_GLOBAL_MODULE | 9,010,440 | 10.0% |
| CALL_ISINSTANCE | 7,894,800 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 54,662,100 | 60.6% |
| POP_JUMP_IF_TRUE | 20,690,520 | 22.9% |
| UNARY_NOT | 14,916,780 | 16.5% |


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
|          hit |     90269400 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2999760 | 25.6% |
|          hit |      8734380 | 74.4% |

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
| specialization.deopt |      1423940 | 0.8% |
|          hit |    103230440 | 57.8% |
|         miss |     75470200 | 42.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,423,980 | 100.0% |
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
|          hit |     39692080 | 100.0% |

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
| Basic | 547,001,280 | 46.4% |
| Not specialized | 216,079,400 | 18.3% |
| Specialized | 415,506,400 | 35.3% |

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
| LOAD_ATTR_INSTANCE_VALUE | 46,942,400 | 53.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 28,527,800 | 32.7% |
| STORE_ATTR_INSTANCE_VALUE | 6,492,960 | 7.4% |
| CALL_PY_EXACT_ARGS | 5,253,360 | 6.0% |
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
| Interpreter increfs | 442,894,100 | 87.2% |
| Interpreter decrefs | 489,217,920 | 95.0% |
| Increfs | 65,081,148 | 12.8% |
| Decrefs | 25,839,828 | 5.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 79,141,970 |  |
| Method cache misses | 2,821,210 |  |
| Method cache collisions | 2,821,210 |  |
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
| Traces executed | 13,912,560 |  |
| Uops executed | 133,031,760 | 9 |
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
| <= 8 | 279,240 | 2.0% |
| <= 16 | 12,795,600 | 92.0% |
| <= 32 | 837,720 | 6.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 42,296,160 | 31.8% | 31.8% |
| _POP_JUMP_IF_TRUE | 13,912,560 | 10.5% | 42.3% |
| _EXIT_TRACE | 13,912,560 | 10.5% | 52.7% |
| LOAD_FAST | 13,633,320 | 10.2% | 63.0% |
| _LOAD_GLOBAL_MODULE | 12,795,600 | 9.6% | 72.6% |
| _GUARD_GLOBALS_VERSION | 12,795,600 | 9.6% | 82.2% |
| TO_BOOL_BOOL | 12,795,600 | 9.6% | 91.8% |
| _ITER_CHECK_RANGE | 1,116,960 | 0.8% | 92.7% |
| _IS_ITER_EXHAUSTED_RANGE | 1,116,960 | 0.8% | 93.5% |
| _LOAD_ATTR_INSTANCE_VALUE | 837,720 | 0.6% | 94.1% |
| _ITER_NEXT_RANGE | 837,720 | 0.6% | 94.8% |
| _GUARD_TYPE_VERSION | 837,720 | 0.6% | 95.4% |
| _GUARD_BOTH_INT | 837,720 | 0.6% | 96.0% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 837,720 | 0.6% | 96.6% |
| _BINARY_OP_ADD_INT | 837,720 | 0.6% | 97.3% |
| SWAP | 837,720 | 0.6% | 97.9% |
| STORE_FAST | 837,720 | 0.6% | 98.5% |
| LOAD_CONST | 837,720 | 0.6% | 99.2% |
| COPY | 837,720 | 0.6% | 99.8% |
| POP_TOP | 279,240 | 0.2% | 100.0% |


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
Stats gathered on: 2023-10-03