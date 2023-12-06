
# Pystats results

- benchmark: richards_super
- fork: gvanrossum
- ref: load-attr-uops
- commit hash: b54eee3
- commit date: 2023-09-26T21:26:46-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 285,829,080 | 21.5% | 21.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 121,244,380 | 9.1% | 30.6% | 38.7% |
| TO_BOOL_BOOL | 103,065,000 | 7.7% | 38.3% |  |
| POP_JUMP_IF_FALSE | 78,057,480 | 5.9% | 44.2% |  |
| CALL_PY_EXACT_ARGS | 65,750,400 | 4.9% | 49.1% | 8.0% |
| RESUME_CHECK | 65,654,580 | 4.9% | 54.0% | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 58,293,880 | 4.4% | 58.4% | 48.9% |
| RETURN_VALUE | 57,758,820 | 4.3% | 62.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 52,705,080 | 4.0% | 66.7% | 22.3% |
| STORE_FAST | 50,090,340 | 3.8% | 70.5% |  |
| LOAD_GLOBAL_MODULE | 44,591,980 | 3.3% | 73.8% |  |
| COPY | 44,579,820 | 3.3% | 77.2% |  |
| LOAD_CONST | 41,972,820 | 3.2% | 80.3% |  |
| POP_TOP | 40,143,780 | 3.0% | 83.3% |  |
| LOAD_FAST_LOAD_FAST | 31,141,320 | 2.3% | 85.7% |  |
| POP_JUMP_IF_NOT_NONE | 23,066,160 | 1.7% | 87.4% |  |
| POP_JUMP_IF_TRUE | 20,690,520 | 1.6% | 89.0% |  |
| POP_JUMP_IF_NONE | 16,842,120 | 1.3% | 90.2% |  |
| LOAD_GLOBAL_BUILTIN | 15,790,500 | 1.2% | 91.4% |  |
| UNARY_NOT | 14,916,780 | 1.1% | 92.5% |  |
| JUMP_BACKWARD | 13,912,800 | 1.0% | 93.6% |  |
| COMPARE_OP_INT | 10,599,780 | 0.8% | 94.4% |  |
| JUMP_FORWARD | 8,109,840 | 0.6% | 95.0% |  |
| RETURN_CONST | 7,898,880 | 0.6% | 95.6% |  |
| LOAD_DEREF | 7,895,640 | 0.6% | 96.2% |  |
| COPY_FREE_VARS | 7,895,580 | 0.6% | 96.8% |  |
| LOAD_SUPER_ATTR_METHOD | 7,895,520 | 0.6% | 97.4% |  |
| CALL_ISINSTANCE | 7,894,800 | 0.6% | 97.9% |  |
| BINARY_OP_ADD_INT | 7,255,080 | 0.5% | 98.5% |  |
| SWAP | 6,822,960 | 0.5% | 99.0% |  |
| BINARY_SUBSCR_LIST_INT | 5,105,400 | 0.4% | 99.4% |  |
| BINARY_OP | 3,000,540 | 0.2% | 99.6% |  |
| BINARY_OP_SUBTRACT_INT | 2,316,960 | 0.2% | 99.8% |  |
| FOR_ITER_RANGE | 1,396,620 | 0.1% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 1,117,680 | 0.1% | 100.0% |  |
| GET_ITER | 279,420 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 3,120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 3,120 | 0.0% | 100.0% |  |
| BUILD_LIST | 960 | 0.0% | 100.0% |  |
| CALL | 400 | 0.0% | 100.0% |  |
| PUSH_NULL | 360 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 360 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 101,649,720 | 7.6% | 7.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 67,457,700 | 5.1% | 12.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 57,756,480 | 4.3% | 17.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 57,754,920 | 4.3% | 21.4% |
| RESUME_CHECK LOAD_FAST | 44,656,440 | 3.4% | 24.7% |
| POP_JUMP_IF_FALSE LOAD_FAST | 38,700,240 | 2.9% | 27.6% |
| COPY TO_BOOL_BOOL | 37,756,860 | 2.8% | 30.5% |
| POP_TOP LOAD_FAST | 37,072,800 | 2.8% | 33.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 35,283,600 | 2.6% | 35.9% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 33,098,760 | 2.5% | 38.4% |
| STORE_FAST LOAD_FAST | 33,024,720 | 2.5% | 40.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 31,323,000 | 2.4% | 43.2% |
| LOAD_ATTR_INSTANCE_VALUE COPY | 25,630,080 | 1.9% | 45.1% |
| LOAD_CONST LOAD_FAST | 21,894,600 | 1.6% | 46.8% |
| LOAD_GLOBAL_MODULE TO_BOOL_BOOL | 21,806,040 | 1.6% | 48.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 20,690,520 | 1.6% | 50.0% |
| RETURN_VALUE TO_BOOL_BOOL | 20,690,520 | 1.6% | 51.5% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 19,064,280 | 1.4% | 53.0% |
| RETURN_VALUE RETURN_VALUE | 18,579,120 | 1.4% | 54.4% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 18,563,280 | 1.4% | 55.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 17,486,640 | 1.3% | 57.1% |
| LOAD_FAST POP_JUMP_IF_NONE | 16,842,120 | 1.3% | 58.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 16,169,280 | 1.2% | 59.5% |
| LOAD_FAST RETURN_VALUE | 15,973,020 | 1.2% | 60.7% |
| TO_BOOL_BOOL UNARY_NOT | 14,916,780 | 1.1% | 61.9% |
| POP_JUMP_IF_FALSE POP_TOP | 14,916,780 | 1.1% | 63.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 14,916,780 | 1.1% | 64.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 13,098,000 | 1.0% | 65.1% |
| POP_JUMP_IF_NONE JUMP_BACKWARD | 12,795,600 | 1.0% | 66.1% |
| JUMP_BACKWARD LOAD_GLOBAL_MODULE | 12,795,600 | 1.0% | 67.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 12,560,880 | 0.9% | 68.0% |
| UNARY_NOT COPY | 12,126,780 | 0.9% | 68.9% |
| POP_JUMP_IF_TRUE POP_TOP | 12,126,780 | 0.9% | 69.8% |
| RETURN_VALUE STORE_FAST | 11,885,160 | 0.9% | 70.7% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 11,540,880 | 0.9% | 71.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 10,939,080 | 0.8% | 72.4% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 10,684,440 | 0.8% | 73.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 10,684,320 | 0.8% | 74.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 10,599,780 | 0.8% | 74.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 10,587,840 | 0.8% | 75.6% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 10,334,520 | 0.8% | 76.3% |
| POP_JUMP_IF_FALSE RETURN_VALUE | 10,044,360 | 0.8% | 77.1% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 9,700,260 | 0.7% | 77.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 9,248,280 | 0.7% | 78.5% |
| LOAD_FAST STORE_FAST | 9,150,840 | 0.7% | 79.2% |
| RESUME_CHECK LOAD_CONST | 7,995,480 | 0.6% | 79.8% |
| JUMP_FORWARD LOAD_FAST | 7,970,160 | 0.6% | 80.4% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 7,897,920 | 0.6% | 81.0% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 7,895,760 | 0.6% | 81.6% |
| RETURN_CONST POP_TOP | 7,895,640 | 0.6% | 82.2% |
| COPY_FREE_VARS RESUME_CHECK | 7,895,580 | 0.6% | 82.8% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 7,895,520 | 0.6% | 83.4% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 7,895,520 | 0.6% | 84.0% |
| LOAD_DEREF LOAD_FAST | 7,895,520 | 0.6% | 84.5% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 7,895,400 | 0.6% | 85.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 7,894,980 | 0.6% | 85.7% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 7,894,800 | 0.6% | 86.3% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 7,894,800 | 0.6% | 86.9% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 7,894,800 | 0.6% | 87.5% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 7,894,800 | 0.6% | 88.1% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 7,894,800 | 0.6% | 88.7% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 7,894,800 | 0.6% | 89.3% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 6,822,960 | 0.5% | 89.8% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 6,822,960 | 0.5% | 90.3% |
| LOAD_CONST BINARY_OP_ADD_INT | 6,138,120 | 0.5% | 90.8% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NOT_NONE | 5,579,520 | 0.4% | 91.2% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,385,240 | 0.4% | 91.6% |
| RETURN_VALUE POP_TOP | 5,204,400 | 0.4% | 92.0% |
| POP_JUMP_IF_FALSE LOAD_CONST | 5,147,640 | 0.4% | 92.4% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 5,106,040 | 0.4% | 92.8% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 5,105,400 | 0.4% | 93.1% |
| LOAD_CONST STORE_FAST | 5,104,920 | 0.4% | 93.5% |
| STORE_FAST JUMP_FORWARD | 5,040,600 | 0.4% | 93.9% |
| BINARY_OP_ADD_INT SWAP | 5,022,120 | 0.4% | 94.3% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 4,111,680 | 0.3% | 94.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_INSTANCE_VALUE | 3,991,200 | 0.3% | 94.9% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 3,989,400 | 0.3% | 95.2% |
| LOAD_GLOBAL_MODULE COPY | 3,905,160 | 0.3% | 95.5% |
| LOAD_CONST COMPARE_OP_INT | 3,517,120 | 0.3% | 95.7% |
| POP_TOP JUMP_FORWARD | 3,069,240 | 0.2% | 96.0% |
| LOAD_CONST BINARY_OP | 2,998,800 | 0.2% | 96.2% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 2,970,960 | 0.2% | 96.4% |
| LOAD_FAST COPY | 2,917,800 | 0.2% | 96.6% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 2,886,600 | 0.2% | 96.9% |
| POP_JUMP_IF_NONE LOAD_FAST | 2,831,040 | 0.2% | 97.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,790,600 | 0.2% | 97.3% |
| UNARY_NOT RETURN_VALUE | 2,790,000 | 0.2% | 97.5% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 2,316,960 | 0.2% | 97.7% |
| BINARY_OP LOAD_CONST | 1,798,920 | 0.1% | 97.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,674,480 | 0.1% | 97.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,437,720 | 0.1% | 98.0% |
| RETURN_VALUE LOAD_FAST | 1,397,400 | 0.1% | 98.1% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 1,215,240 | 0.1% | 98.2% |
| STORE_FAST LOAD_CONST | 1,200,000 | 0.1% | 98.3% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 1,200,000 | 0.1% | 98.4% |
| BINARY_OP_SUBTRACT_INT SWAP | 1,200,000 | 0.1% | 98.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_MODULE | 1,199,880 | 0.1% | 98.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,117,680 | 0.1% | 98.7% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 1,117,680 | 0.1% | 98.8% |
| FOR_ITER_RANGE STORE_FAST | 1,117,200 | 0.1% | 98.8% |


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
| POP_JUMP_IF_FALSE | 14,916,780 | 37.2% |
| POP_JUMP_IF_TRUE | 12,126,780 | 30.2% |
| RETURN_CONST | 7,895,640 | 19.7% |
| RETURN_VALUE | 5,204,400 | 13.0% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,072,800 | 92.4% |
| JUMP_FORWARD | 3,069,240 | 7.6% |
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
| LOAD_ATTR_INSTANCE_VALUE | 25,630,080 | 57.5% |
| UNARY_NOT | 12,126,780 | 27.2% |
| LOAD_GLOBAL_MODULE | 3,905,160 | 8.8% |
| LOAD_FAST | 2,917,800 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 37,756,860 | 84.7% |
| LOAD_ATTR_INSTANCE_VALUE | 6,822,960 | 15.3% |


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
| POP_JUMP_IF_NONE | 12,795,600 | 92.0% |
| STORE_SUBSCR_LIST_INT | 1,116,960 | 8.0% |
| POP_TOP | 120 | 0.0% |
| EXTENDED_ARG | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,795,600 | 92.0% |
| FOR_ITER_RANGE | 1,117,080 | 8.0% |
| EXTENDED_ARG | 120 | 0.0% |


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
| STORE_ATTR_INSTANCE_VALUE | 11,540,880 | 27.5% |
| LOAD_ATTR_INSTANCE_VALUE | 10,939,080 | 26.1% |
| RESUME_CHECK | 7,995,480 | 19.0% |
| POP_JUMP_IF_FALSE | 5,147,640 | 12.3% |
| BINARY_OP | 1,798,920 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,894,600 | 52.2% |
| BINARY_OP_ADD_INT | 6,138,120 | 14.6% |
| STORE_FAST | 5,104,920 | 12.2% |
| COMPARE_OP_INT | 3,517,120 | 8.4% |
| BINARY_OP | 2,998,800 | 7.1% |


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
| RESUME_CHECK | 44,656,440 | 15.6% |
| POP_JUMP_IF_FALSE | 38,700,240 | 13.5% |
| POP_TOP | 37,072,800 | 13.0% |
| STORE_FAST | 33,024,720 | 11.6% |
| STORE_ATTR_INSTANCE_VALUE | 31,323,000 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 101,649,720 | 35.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 57,754,920 | 20.2% |
| STORE_ATTR_INSTANCE_VALUE | 33,098,760 | 11.6% |
| POP_JUMP_IF_NOT_NONE | 17,486,640 | 6.1% |
| POP_JUMP_IF_NONE | 16,842,120 | 5.9% |


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
| TO_BOOL_BOOL | 67,457,700 | 86.4% |
| COMPARE_OP_INT | 10,599,780 | 13.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,700,240 | 49.6% |
| POP_TOP | 14,916,780 | 19.1% |
| RETURN_VALUE | 10,044,360 | 12.9% |
| LOAD_GLOBAL_MODULE | 9,248,280 | 11.8% |
| LOAD_CONST | 5,147,640 | 6.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,842,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 12,795,600 | 76.0% |
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
| LOAD_GLOBAL_BUILTIN | 7,894,800 | 38.2% |
| RETURN_VALUE | 668,940 | 3.2% |


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
| LOAD_ATTR_INSTANCE_VALUE | 18,563,280 | 37.1% |
| RETURN_VALUE | 11,885,160 | 23.7% |
| LOAD_FAST | 9,150,840 | 18.3% |
| LOAD_CONST | 5,104,920 | 10.2% |
| BINARY_SUBSCR_LIST_INT | 3,989,400 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,024,720 | 65.9% |
| LOAD_GLOBAL_BUILTIN | 7,894,800 | 15.8% |
| JUMP_FORWARD | 5,040,600 | 10.1% |
| LOAD_GLOBAL_MODULE | 2,790,600 | 5.6% |
| LOAD_CONST | 1,200,000 | 2.4% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 5,022,120 | 73.6% |
| BINARY_OP_SUBTRACT_INT | 1,200,000 | 17.6% |
| BINARY_OP | 600,840 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 6,822,960 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,138,120 | 84.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,116,960 | 15.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 5,022,120 | 69.2% |
| LOAD_CONST | 1,116,960 | 15.4% |
| LOAD_FAST | 1,116,000 | 15.4% |


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
| LOAD_ATTR_METHOD_WITH_VALUES | 35,283,600 | 53.7% |
| LOAD_ATTR_INSTANCE_VALUE | 13,098,000 | 19.9% |
| LOAD_FAST_LOAD_FAST | 10,684,440 | 16.2% |
| LOAD_FAST | 5,385,240 | 8.2% |
| LOAD_GLOBAL_MODULE | 1,200,000 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 57,756,480 | 87.8% |
| COPY_FREE_VARS | 7,894,800 | 12.0% |
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
| JUMP_BACKWARD | 1,117,080 | 80.0% |
| GET_ITER | 279,300 | 20.0% |
| EXTENDED_ARG | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,117,200 | 80.0% |
| LOAD_FAST | 279,300 | 20.0% |
| RETURN_CONST | 120 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 101,649,720 | 83.8% |
| LOAD_FAST_LOAD_FAST | 7,894,800 | 6.5% |
| COPY | 6,822,960 | 5.6% |
| LOAD_GLOBAL_MODULE | 3,991,200 | 3.3% |
| LOAD_ATTR_INSTANCE_VALUE | 885,700 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 25,630,080 | 21.1% |
| STORE_FAST | 18,563,280 | 15.3% |
| LOAD_FAST | 16,169,280 | 13.3% |
| TO_BOOL_BOOL | 14,916,780 | 12.3% |
| CALL_PY_EXACT_ARGS | 13,098,000 | 10.8% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 57,754,920 | 99.1% |
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
| JUMP_BACKWARD | 12,795,600 | 28.7% |
| LOAD_FAST | 10,334,520 | 23.2% |
| POP_JUMP_IF_FALSE | 9,248,280 | 20.7% |
| RESUME_CHECK | 5,106,040 | 11.5% |
| STORE_FAST | 2,790,600 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 21,806,040 | 48.9% |
| CALL_ISINSTANCE | 7,894,800 | 17.7% |
| COMPARE_OP_INT | 4,111,680 | 9.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,991,200 | 9.0% |
| COPY | 3,905,160 | 8.8% |


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
| CALL_PY_EXACT_ARGS | 57,756,480 | 88.0% |
| COPY_FREE_VARS | 7,895,580 | 12.0% |
| CALL_ALLOC_AND_ENTER_INIT | 2,400 | 0.0% |
| CACHE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,656,440 | 68.0% |
| LOAD_CONST | 7,995,480 | 12.2% |
| LOAD_FAST_LOAD_FAST | 7,895,760 | 12.0% |
| LOAD_GLOBAL_MODULE | 5,106,040 | 7.8% |
| LOAD_GLOBAL_BUILTIN | 840 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,098,760 | 62.8% |
| LOAD_FAST_LOAD_FAST | 12,560,880 | 23.8% |
| SWAP | 6,822,960 | 12.9% |
| STORE_ATTR_INSTANCE_VALUE | 221,520 | 0.4% |
| LOAD_GLOBAL_MODULE | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,323,000 | 59.4% |
| LOAD_CONST | 11,540,880 | 21.9% |
| RETURN_CONST | 7,897,920 | 15.0% |
| LOAD_GLOBAL_MODULE | 1,437,720 | 2.7% |
| LOAD_FAST_LOAD_FAST | 284,040 | 0.5% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,117,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,116,960 | 99.9% |
| LOAD_CONST | 720 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 37,756,860 | 36.6% |
| LOAD_GLOBAL_MODULE | 21,806,040 | 21.2% |
| RETURN_VALUE | 20,690,520 | 20.1% |
| LOAD_ATTR_INSTANCE_VALUE | 14,916,780 | 14.5% |
| CALL_ISINSTANCE | 7,894,800 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 67,457,700 | 65.5% |
| POP_JUMP_IF_TRUE | 20,690,520 | 20.1% |
| UNARY_NOT | 14,916,780 | 14.5% |


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
| specialization.deopt |        99120 | 0.1% |
|          hit |     68395140 | 92.9% |
|         miss |      5253360 | 7.1% |

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
|          hit |      1396620 | 100.0% |


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
| specialization.deopt |      1423940 | 0.8% |
|          hit |    104068160 | 58.0% |
|         miss |     75470200 | 42.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,423,980 | 100.0% |
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
|          hit |     60382480 | 100.0% |

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
|          hit |     40958280 | 77.7% |
|         miss |     11746800 | 22.3% |

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
| Basic | 605,340,120 | 45.5% |
| Not specialized | 248,040,560 | 18.6% |
| Specialized | 478,210,720 | 35.9% |

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
| LOAD_ATTR_INSTANCE_VALUE | 46,942,400 | 50.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 28,527,800 | 30.9% |
| STORE_ATTR_INSTANCE_VALUE | 11,746,800 | 12.7% |
| CALL_PY_EXACT_ARGS | 5,253,360 | 5.7% |
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
| Calls to Python functions inlined | 65,654,460 | 100.0% |
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
| Frames pushed | 65,657,700 | 100.0% |
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
| Interpreter increfs | 496,402,820 | 85.8% |
| Interpreter decrefs | 551,170,800 | 94.2% |
| Increfs | 81,892,548 | 14.2% |
| Decrefs | 34,206,588 | 5.8% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 83,676,168 |  |
| Method cache misses | 3,540,852 |  |
| Method cache collisions | 3,540,852 |  |
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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
