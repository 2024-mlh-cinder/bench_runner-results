
# Pystats results

- benchmark: richards_super
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 128,973,720 | 22.0% | 22.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 55,040,320 | 9.4% | 31.3% | 34.9% |
| TO_BOOL_BOOL | 36,266,520 | 6.2% | 37.5% |  |
| CALL_PY_EXACT_ARGS | 30,784,860 | 5.2% | 42.7% | 8.5% |
| RESUME_CHECK | 30,736,980 | 5.2% | 48.0% |  |
| RETURN_VALUE | 27,246,060 | 4.6% | 52.6% |  |
| POP_JUMP_IF_FALSE | 27,190,260 | 4.6% | 57.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 27,014,540 | 4.6% | 61.8% | 44.5% |
| STORE_ATTR_INSTANCE_VALUE | 25,932,780 | 4.4% | 66.3% | 22.6% |
| STORE_FAST | 24,625,440 | 4.2% | 70.4% |  |
| LOAD_CONST | 19,740,600 | 3.4% | 73.8% |  |
| POP_TOP | 18,315,480 | 3.1% | 76.9% |  |
| COPY | 18,024,720 | 3.1% | 80.0% |  |
| LOAD_FAST_LOAD_FAST | 15,570,660 | 2.7% | 82.6% |  |
| LOAD_GLOBAL_MODULE | 13,857,640 | 2.4% | 85.0% |  |
| POP_JUMP_IF_NOT_NONE | 11,533,080 | 2.0% | 87.0% |  |
| POP_JUMP_IF_NONE | 8,420,160 | 1.4% | 88.4% |  |
| POP_JUMP_IF_TRUE | 8,254,920 | 1.4% | 89.8% |  |
| LOAD_GLOBAL_BUILTIN | 7,895,220 | 1.3% | 91.2% |  |
| ENTER_EXECUTOR | 6,547,260 | 1.1% | 92.3% |  |
| UNARY_NOT | 5,702,400 | 1.0% | 93.2% |  |
| COMPARE_OP_INT | 4,881,060 | 0.8% | 94.1% |  |
| JUMP_FORWARD | 4,054,020 | 0.7% | 94.8% |  |
| RETURN_CONST | 3,949,440 | 0.7% | 95.4% |  |
| LOAD_DEREF | 3,947,880 | 0.7% | 96.1% |  |
| COPY_FREE_VARS | 3,947,820 | 0.7% | 96.8% |  |
| LOAD_SUPER_ATTR_METHOD | 3,947,760 | 0.7% | 97.4% |  |
| CALL_ISINSTANCE | 3,947,400 | 0.7% | 98.1% |  |
| SWAP | 2,992,620 | 0.5% | 98.6% |  |
| BINARY_OP_ADD_INT | 2,800,560 | 0.5% | 99.1% |  |
| BINARY_SUBSCR_LIST_INT | 2,552,700 | 0.4% | 99.5% |  |
| BINARY_OP | 1,500,260 | 0.3% | 99.8% |  |
| BINARY_OP_SUBTRACT_INT | 750,360 | 0.1% | 99.9% |  |
| STORE_SUBSCR_LIST_INT | 150,720 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 139,740 | 0.0% | 100.0% |  |
| GET_ITER | 139,680 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 1,560 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 1,560 | 0.0% | 100.0% |  |
| STORE_ATTR | 1,200 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,180 | 0.0% | 100.0% |  |
| CALL | 1,060 | 0.0% | 100.0% |  |
| BUILD_LIST | 480 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| LOAD_ATTR | 260 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 60 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 60 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 45,742,080 | 7.8% | 7.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 26,787,900 | 4.6% | 12.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 22,309,200 | 3.8% | 16.1% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 20,847,160 | 3.5% | 19.7% |
| RESUME_CHECK LOAD_FAST | 20,237,880 | 3.4% | 23.1% |
| POP_TOP LOAD_FAST | 16,780,020 | 2.9% | 26.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 16,548,700 | 2.8% | 28.8% |
| STORE_FAST LOAD_FAST | 16,093,500 | 2.7% | 31.6% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 15,551,320 | 2.6% | 34.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 15,242,240 | 2.6% | 36.8% |
| COPY TO_BOOL_BOOL | 15,032,100 | 2.6% | 39.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 11,319,000 | 1.9% | 41.3% |
| LOAD_CONST LOAD_FAST | 10,947,300 | 1.9% | 43.1% |
| LOAD_ATTR_INSTANCE_VALUE COPY | 10,724,700 | 1.8% | 45.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 9,532,140 | 1.6% | 46.6% |
| RETURN_VALUE RETURN_VALUE | 9,289,560 | 1.6% | 48.2% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 9,280,740 | 1.6% | 49.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 8,743,320 | 1.5% | 51.2% |
| RETURN_VALUE TO_BOOL_BOOL | 8,711,880 | 1.5% | 52.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 8,420,160 | 1.4% | 54.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 8,254,920 | 1.4% | 55.6% |
| LOAD_FAST RETURN_VALUE | 7,986,540 | 1.4% | 56.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 7,676,520 | 1.3% | 58.2% |
| POP_JUMP_IF_FALSE POP_TOP | 7,334,880 | 1.2% | 59.5% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 6,549,000 | 1.1% | 60.6% |
| POP_JUMP_IF_NONE ENTER_EXECUTOR | 6,396,900 | 1.1% | 61.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 6,279,960 | 1.1% | 62.8% |
| RETURN_VALUE STORE_FAST | 5,942,580 | 1.0% | 63.8% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 5,939,940 | 1.0% | 64.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 5,770,440 | 1.0% | 65.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 5,702,400 | 1.0% | 66.7% |
| TO_BOOL_BOOL UNARY_NOT | 5,702,400 | 1.0% | 67.7% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 5,342,200 | 0.9% | 68.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 5,342,160 | 0.9% | 69.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 5,293,920 | 0.9% | 70.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 5,167,080 | 0.9% | 71.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 4,881,060 | 0.8% | 72.1% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 4,849,680 | 0.8% | 73.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 4,631,820 | 0.8% | 73.7% |
| LOAD_FAST STORE_FAST | 4,575,420 | 0.8% | 74.5% |
| UNARY_NOT COPY | 4,307,400 | 0.7% | 75.3% |
| POP_JUMP_IF_TRUE POP_TOP | 4,307,400 | 0.7% | 76.0% |
| RESUME_CHECK LOAD_CONST | 3,997,740 | 0.7% | 76.7% |
| JUMP_FORWARD LOAD_FAST | 3,984,180 | 0.7% | 77.4% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 3,948,860 | 0.7% | 78.0% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 3,947,880 | 0.7% | 78.7% |
| COPY_FREE_VARS RESUME_CHECK | 3,947,820 | 0.7% | 79.4% |
| RETURN_CONST POP_TOP | 3,947,820 | 0.7% | 80.0% |
| LOAD_DEREF LOAD_FAST | 3,947,760 | 0.7% | 80.7% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 3,947,760 | 0.7% | 81.4% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 3,947,720 | 0.7% | 82.1% |
| LOAD_SUPER_ATTR_METHOD LOAD_FAST_LOAD_FAST | 3,947,700 | 0.7% | 82.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,947,460 | 0.7% | 83.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 3,947,400 | 0.7% | 84.1% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 3,947,400 | 0.7% | 84.7% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 3,947,400 | 0.7% | 85.4% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 3,947,400 | 0.7% | 86.1% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 3,947,400 | 0.7% | 86.8% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 3,947,400 | 0.7% | 87.4% |
| POP_JUMP_IF_FALSE RETURN_VALUE | 3,389,700 | 0.6% | 88.0% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 2,992,620 | 0.5% | 88.5% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 2,992,620 | 0.5% | 89.0% |
| LOAD_GLOBAL_MODULE TO_BOOL_BOOL | 2,872,740 | 0.5% | 89.5% |
| LOAD_ATTR_INSTANCE_VALUE POP_JUMP_IF_NOT_NONE | 2,789,760 | 0.5% | 90.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,692,600 | 0.5% | 90.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 2,650,200 | 0.5% | 90.9% |
| RETURN_VALUE POP_TOP | 2,602,200 | 0.4% | 91.3% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 2,583,520 | 0.4% | 91.8% |
| POP_JUMP_IF_FALSE LOAD_CONST | 2,563,080 | 0.4% | 92.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,553,000 | 0.4% | 92.7% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 2,552,700 | 0.4% | 93.1% |
| LOAD_CONST STORE_FAST | 2,552,460 | 0.4% | 93.5% |
| STORE_FAST JUMP_FORWARD | 2,519,400 | 0.4% | 94.0% |
| BINARY_OP_ADD_INT SWAP | 2,092,200 | 0.4% | 94.3% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 2,055,840 | 0.3% | 94.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_INSTANCE_VALUE | 1,995,540 | 0.3% | 95.0% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 1,994,700 | 0.3% | 95.3% |
| LOAD_GLOBAL_MODULE COPY | 1,952,580 | 0.3% | 95.7% |
| POP_TOP JUMP_FORWARD | 1,534,620 | 0.3% | 95.9% |
| LOAD_CONST BINARY_OP | 1,499,400 | 0.3% | 96.2% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 1,485,480 | 0.3% | 96.4% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 1,443,300 | 0.2% | 96.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,415,520 | 0.2% | 96.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,395,120 | 0.2% | 97.2% |
| UNARY_NOT RETURN_VALUE | 1,395,000 | 0.2% | 97.4% |
| LOAD_CONST COMPARE_OP_INT | 1,339,680 | 0.2% | 97.6% |
| LOAD_FAST COPY | 1,040,040 | 0.2% | 97.8% |
| BINARY_OP LOAD_CONST | 899,460 | 0.2% | 98.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 837,240 | 0.1% | 98.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 750,360 | 0.1% | 98.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 718,840 | 0.1% | 98.4% |
| RETURN_VALUE LOAD_FAST | 698,700 | 0.1% | 98.5% |
| POP_JUMP_IF_NONE LOAD_FAST_LOAD_FAST | 607,620 | 0.1% | 98.6% |
| STORE_FAST LOAD_CONST | 600,000 | 0.1% | 98.7% |
| BINARY_OP_SUBTRACT_INT SWAP | 600,000 | 0.1% | 98.8% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 599,980 | 0.1% | 98.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_MODULE | 599,940 | 0.1% | 99.0% |
| LOAD_FAST LOAD_CONST | 558,180 | 0.1% | 99.1% |
| BINARY_OP_ADD_INT LOAD_FAST | 558,000 | 0.1% | 99.2% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 558,000 | 0.1% | 99.3% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,560 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 139,620 | 100.0% |
| CALL_BUILTIN_CLASS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 139,620 | 100.0% |
| EXTENDED_ARG | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 60 | 100.0% |


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
| POP_JUMP_IF_FALSE | 7,334,880 | 40.0% |
| POP_JUMP_IF_TRUE | 4,307,400 | 23.5% |
| RETURN_CONST | 3,947,820 | 21.6% |
| RETURN_VALUE | 2,602,200 | 14.2% |
| ENTER_EXECUTOR | 123,060 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,780,020 | 91.6% |
| JUMP_FORWARD | 1,534,620 | 8.4% |
| RETURN_CONST | 360 | 0.0% |
| LOAD_GLOBAL_MODULE | 240 | 0.0% |
| LOAD_GLOBAL | 120 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 60.0% |
| LOAD_DEREF | 60 | 20.0% |
| LOAD_ATTR_MODULE | 40 | 13.3% |
| LOAD_ATTR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 80.0% |
| LOAD_FAST | 60 | 20.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,289,560 | 34.1% |
| LOAD_FAST | 7,986,540 | 29.3% |
| LOAD_ATTR_INSTANCE_VALUE | 4,849,680 | 17.8% |
| POP_JUMP_IF_FALSE | 3,389,700 | 12.4% |
| UNARY_NOT | 1,395,000 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 9,289,560 | 34.1% |
| TO_BOOL_BOOL | 8,711,880 | 32.0% |
| STORE_FAST | 5,942,580 | 21.8% |
| POP_TOP | 2,602,200 | 9.6% |
| LOAD_FAST | 698,700 | 2.6% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,702,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 4,307,400 | 75.5% |
| RETURN_VALUE | 1,395,000 | 24.5% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,499,400 | 99.9% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |
| BINARY_OP | 360 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 899,460 | 60.0% |
| SWAP | 300,420 | 20.0% |
| LOAD_FAST | 300,000 | 20.0% |
| BINARY_OP | 360 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 480 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 420 | 39.6% |
| PUSH_NULL | 240 | 22.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 140 | 13.2% |
| RETURN_VALUE | 120 | 11.3% |
| CALL | 80 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ALLOC_AND_ENTER_INIT | 520 | 49.1% |
| CALL_PY_EXACT_ARGS | 200 | 18.9% |
| POP_TOP | 120 | 11.3% |
| CALL | 80 | 7.5% |
| LOAD_FAST | 60 | 5.7% |


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
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 60 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 10,724,700 | 59.5% |
| UNARY_NOT | 4,307,400 | 23.9% |
| LOAD_GLOBAL_MODULE | 1,952,580 | 10.8% |
| LOAD_FAST | 1,040,040 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 15,032,100 | 83.4% |
| LOAD_ATTR_INSTANCE_VALUE | 2,992,620 | 16.6% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,947,400 | 100.0% |
| CALL_ALLOC_AND_ENTER_INIT | 360 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,947,820 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 6,396,900 | 97.7% |
| STORE_SUBSCR_LIST_INT | 150,360 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,939,940 | 90.7% |
| RETURN_VALUE | 333,900 | 5.1% |
| LOAD_FAST | 139,620 | 2.1% |
| POP_TOP | 123,060 | 1.9% |
| LOAD_CONST | 10,740 | 0.2% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 33.3% |
| JUMP_BACKWARD | 60 | 33.3% |
| POP_JUMP_IF_FALSE | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 120 | 66.7% |
| JUMP_BACKWARD | 60 | 33.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 60 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,519,400 | 62.1% |
| POP_TOP | 1,534,620 | 37.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,984,180 | 98.3% |
| LOAD_FAST_LOAD_FAST | 69,840 | 1.7% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 46.2% |
| LOAD_GLOBAL_MODULE | 100 | 38.5% |
| LOAD_FAST | 20 | 7.7% |
| LOAD_GLOBAL | 20 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 140 | 53.8% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 23.1% |
| LOAD_ATTR_MODULE | 40 | 15.4% |
| PUSH_NULL | 20 | 7.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,770,440 | 29.2% |
| LOAD_ATTR_INSTANCE_VALUE | 4,631,820 | 23.5% |
| RESUME_CHECK | 3,997,740 | 20.3% |
| POP_JUMP_IF_FALSE | 2,563,080 | 13.0% |
| BINARY_OP | 899,460 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,947,300 | 55.5% |
| BINARY_OP_ADD_INT | 2,650,200 | 13.4% |
| STORE_FAST | 2,552,460 | 12.9% |
| BINARY_OP | 1,499,400 | 7.6% |
| COMPARE_OP_INT | 1,339,680 | 6.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,947,760 | 100.0% |
| NOP | 60 | 0.0% |
| STORE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,947,760 | 100.0% |
| PUSH_NULL | 60 | 0.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 20,237,880 | 15.7% |
| POP_TOP | 16,780,020 | 13.0% |
| STORE_FAST | 16,093,500 | 12.5% |
| STORE_ATTR_INSTANCE_VALUE | 15,242,240 | 11.8% |
| POP_JUMP_IF_FALSE | 11,319,000 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 45,742,080 | 35.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 20,847,160 | 16.2% |
| STORE_ATTR_INSTANCE_VALUE | 16,548,700 | 12.8% |
| POP_JUMP_IF_NOT_NONE | 8,743,320 | 6.8% |
| POP_JUMP_IF_NONE | 8,420,160 | 6.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 5,342,160 | 34.3% |
| RESUME_CHECK | 3,947,880 | 25.4% |
| LOAD_SUPER_ATTR_METHOD | 3,947,700 | 25.4% |
| POP_JUMP_IF_NOT_NONE | 1,443,300 | 9.3% |
| POP_JUMP_IF_NONE | 607,620 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 6,279,960 | 40.3% |
| CALL_PY_EXACT_ARGS | 5,342,200 | 34.3% |
| LOAD_ATTR_INSTANCE_VALUE | 3,947,400 | 25.4% |
| STORE_ATTR | 480 | 0.0% |
| LOAD_FAST | 300 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 240 | 20.3% |
| LOAD_FAST | 180 | 15.3% |
| STORE_FAST | 180 | 15.3% |
| RETURN_VALUE | 160 | 13.6% |
| LOAD_CONST | 140 | 11.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,100 | 93.2% |
| LOAD_GLOBAL_BUILTIN | 60 | 5.1% |
| LOAD_ATTR | 20 | 1.7% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 40 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 22,309,200 | 82.0% |
| COMPARE_OP_INT | 4,881,060 | 18.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,319,000 | 41.6% |
| POP_TOP | 7,334,880 | 27.0% |
| RETURN_VALUE | 3,389,700 | 12.5% |
| LOAD_GLOBAL_MODULE | 2,583,520 | 9.5% |
| LOAD_CONST | 2,563,080 | 9.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,420,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,396,900 | 76.0% |
| LOAD_FAST | 1,415,520 | 16.8% |
| LOAD_FAST_LOAD_FAST | 607,620 | 7.2% |
| RETURN_CONST | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,743,320 | 75.8% |
| LOAD_ATTR_INSTANCE_VALUE | 2,789,760 | 24.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,532,140 | 82.7% |
| LOAD_FAST_LOAD_FAST | 1,443,300 | 12.5% |
| LOAD_CONST | 557,640 | 4.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 8,254,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,307,400 | 52.2% |
| LOAD_GLOBAL_BUILTIN | 3,947,400 | 47.8% |
| RETURN_VALUE | 120 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 3,948,860 | 100.0% |
| POP_TOP | 360 | 0.0% |
| STORE_ATTR | 100 | 0.0% |
| POP_JUMP_IF_NONE | 60 | 0.0% |
| FOR_ITER_RANGE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,947,820 | 100.0% |
| EXIT_INIT_CHECK | 1,560 | 0.0% |
| INTERPRETER_EXIT | 60 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680 | 56.7% |
| LOAD_FAST_LOAD_FAST | 480 | 40.0% |
| LOAD_GLOBAL_MODULE | 40 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 33.3% |
| LOAD_FAST_LOAD_FAST | 400 | 33.3% |
| STORE_ATTR_INSTANCE_VALUE | 300 | 25.0% |
| RETURN_CONST | 100 | 8.3% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 9,280,740 | 37.7% |
| RETURN_VALUE | 5,942,580 | 24.1% |
| LOAD_FAST | 4,575,420 | 18.6% |
| LOAD_CONST | 2,552,460 | 10.4% |
| BINARY_SUBSCR_LIST_INT | 1,994,700 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,093,500 | 65.4% |
| LOAD_GLOBAL_BUILTIN | 3,947,400 | 16.0% |
| JUMP_FORWARD | 2,519,400 | 10.2% |
| LOAD_GLOBAL_MODULE | 1,395,120 | 5.7% |
| LOAD_CONST | 600,000 | 2.4% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,092,200 | 69.9% |
| BINARY_OP_SUBTRACT_INT | 600,000 | 20.0% |
| BINARY_OP | 300,420 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 2,992,620 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,650,200 | 94.6% |
| LOAD_ATTR_INSTANCE_VALUE | 150,360 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,092,200 | 74.7% |
| LOAD_FAST | 558,000 | 19.9% |
| LOAD_CONST | 150,360 | 5.4% |


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
| LOAD_CONST | 750,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 600,000 | 80.0% |
| LOAD_FAST | 150,360 | 20.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,552,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,994,700 | 78.1% |
| LOAD_FAST | 558,000 | 21.9% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 800 | 51.3% |
| CALL | 520 | 33.3% |
| RETURN_VALUE | 240 | 15.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,200 | 76.9% |
| COPY_FREE_VARS | 360 | 23.1% |


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
| GET_ITER | 60 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,947,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,947,400 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 15,551,320 | 50.5% |
| LOAD_ATTR_INSTANCE_VALUE | 6,549,000 | 21.3% |
| LOAD_FAST_LOAD_FAST | 5,342,200 | 17.4% |
| LOAD_FAST | 2,692,600 | 8.7% |
| LOAD_GLOBAL_MODULE | 599,980 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 26,787,900 | 87.0% |
| COPY_FREE_VARS | 3,947,400 | 12.8% |
| CALL_PY_EXACT_ARGS | 49,560 | 0.2% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,055,840 | 42.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,485,480 | 30.4% |
| LOAD_CONST | 1,339,680 | 27.4% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,881,060 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 139,620 | 99.9% |
| EXTENDED_ARG | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 139,680 | 100.0% |
| RETURN_CONST | 60 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,742,080 | 83.1% |
| LOAD_FAST_LOAD_FAST | 3,947,400 | 7.2% |
| COPY | 2,992,620 | 5.4% |
| LOAD_GLOBAL_MODULE | 1,995,540 | 3.6% |
| LOAD_ATTR_INSTANCE_VALUE | 362,620 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 10,724,700 | 19.5% |
| STORE_FAST | 9,280,740 | 16.9% |
| LOAD_FAST | 7,676,520 | 13.9% |
| CALL_PY_EXACT_ARGS | 6,549,000 | 11.9% |
| TO_BOOL_BOOL | 5,702,400 | 10.4% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,847,160 | 77.2% |
| ENTER_EXECUTOR | 5,939,940 | 22.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 227,060 | 0.8% |
| RETURN_VALUE | 240 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 15,551,320 | 57.6% |
| LOAD_FAST_LOAD_FAST | 5,342,160 | 19.8% |
| LOAD_FAST | 5,293,920 | 19.6% |
| LOAD_GLOBAL_MODULE | 599,940 | 2.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 227,060 | 0.8% |


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
| POP_JUMP_IF_TRUE | 3,947,400 | 50.0% |
| STORE_FAST | 3,947,400 | 50.0% |
| RESUME_CHECK | 360 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 3,947,760 | 50.0% |
| LOAD_FAST | 3,947,460 | 50.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,167,080 | 37.3% |
| POP_JUMP_IF_FALSE | 2,583,520 | 18.6% |
| RESUME_CHECK | 2,553,000 | 18.4% |
| STORE_FAST | 1,395,120 | 10.1% |
| LOAD_ATTR_INSTANCE_VALUE | 837,240 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 3,947,400 | 28.5% |
| TO_BOOL_BOOL | 2,872,740 | 20.7% |
| COMPARE_OP_INT | 2,055,840 | 14.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,995,540 | 14.4% |
| COPY | 1,952,580 | 14.1% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,947,720 | 100.0% |
| LOAD_SUPER_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,947,700 | 100.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 26,787,900 | 87.2% |
| COPY_FREE_VARS | 3,947,820 | 12.8% |
| CALL_ALLOC_AND_ENTER_INIT | 1,200 | 0.0% |
| CACHE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,237,880 | 65.8% |
| LOAD_CONST | 3,997,740 | 13.0% |
| LOAD_FAST_LOAD_FAST | 3,947,880 | 12.8% |
| LOAD_GLOBAL_MODULE | 2,553,000 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 360 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,548,700 | 63.8% |
| LOAD_FAST_LOAD_FAST | 6,279,960 | 24.2% |
| SWAP | 2,992,620 | 11.5% |
| STORE_ATTR_INSTANCE_VALUE | 110,760 | 0.4% |
| LOAD_GLOBAL_MODULE | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,242,240 | 58.8% |
| LOAD_CONST | 5,770,440 | 22.3% |
| RETURN_CONST | 3,948,860 | 15.2% |
| LOAD_GLOBAL_MODULE | 718,840 | 2.8% |
| LOAD_FAST_LOAD_FAST | 141,620 | 0.5% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 150,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 150,360 | 99.8% |
| LOAD_CONST | 360 | 0.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 15,032,100 | 41.4% |
| RETURN_VALUE | 8,711,880 | 24.0% |
| LOAD_ATTR_INSTANCE_VALUE | 5,702,400 | 15.7% |
| CALL_ISINSTANCE | 3,947,400 | 10.9% |
| LOAD_GLOBAL_MODULE | 2,872,740 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 22,309,200 | 61.5% |
| POP_JUMP_IF_TRUE | 8,254,920 | 22.8% |
| UNARY_NOT | 5,702,400 | 15.7% |


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
|     deferred | 1,499,880 | 29.7% |
|          hit | 3,550,980 | 70.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 5.3% |
| Failure | 360 | 94.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 140 | 38.9% |
| floor divide | 120 | 33.3% |
| xor | 60 | 16.7% |
| multiply different types | 40 | 11.1% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 2,552,700 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|        deopt | 49,560 | 0.1% |
|          hit | 32,107,200 | 92.4% |
|         miss | 2,626,680 | 7.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 50,300 | 99.8% |
| Failure | 80 | 0.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 75.0% |
| other | 20 | 25.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 4,881,060 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 139,740 | 100.0% |


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
|     deferred | 20 | 0.0% |
|        deopt | 589,680 | 0.7% |
|          hit | 50,802,400 | 61.9% |
|         miss | 31,252,560 | 38.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 589,920 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 21,752,860 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,160 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 3,947,760 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
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

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 900 | 0.0% |
|        deopt | 110,760 | 0.4% |
|          hit | 20,060,100 | 77.4% |
|         miss | 5,872,680 | 22.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 111,060 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 150,720 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 36,266,520 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 283,780,500 | 48.3% |
| Not specialized | 96,654,460 | 16.5% |
| Specialized | 206,949,020 | 35.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 1,499,880 | 99.9% |
| STORE_ATTR | 900 | 0.1% |
| CALL | 240 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| CACHE | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 19,218,320 | 48.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,034,240 | 30.3% |
| STORE_ATTR_INSTANCE_VALUE | 5,872,680 | 14.8% |
| CALL_PY_EXACT_ARGS | 2,626,680 | 6.6% |
| CACHE | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 60 | 0.0% |
| Calls to Python functions inlined | 30,736,920 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 32,827,980 | 106.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 680 | 0.0% |
| Frees to freelist | 540 |  |
| Allocations | 3,544,060 | 100.0% |
| Allocations to 512 bytes | 3,544,060 | 100.0% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 3,540,720 |  |
| New values | 0 |  |
| Interpreter increfs | 238,393,140 | 80.5% |
| Interpreter decrefs | 269,113,080 | 89.8% |
| Increfs | 57,910,163 | 19.5% |
| Decrefs | 30,728,303 | 10.2% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 34,740,997 |  |
| Method cache misses | 2,385,663 |  |
| Method cache collisions | 2,385,663 |  |
| Method cache dunder hits | 520 |  |
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
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 6,547,260 |  |
| Uops executed | 175,530,540 | 26.81 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 4,307,460 | 65.8% |
| <= 32 | 0 | 0.0% |
| <= 64 | 2,100,180 | 32.1% |
| <= 128 | 10,740 | 0.2% |
| <= 256 | 128,880 | 2.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 49,183,860 | 28.0% | 28.0% |  |
| TO_BOOL_BOOL | 15,262,380 | 8.7% | 36.7% |  |
| _POP_JUMP_IF_TRUE | 14,484,180 | 8.3% | 45.0% |  |
| _GUARD_TYPE_VERSION | 13,947,180 | 7.9% | 52.9% | 42.6% |
| LOAD_FAST | 13,936,440 | 7.9% | 60.9% |  |
| _GUARD_GLOBALS_VERSION | 8,437,500 | 4.8% | 65.7% |  |
| _LOAD_GLOBAL_MODULE | 8,437,500 | 4.8% | 70.5% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 5,498,940 | 3.1% | 73.6% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 5,498,940 | 3.1% | 76.7% |  |
| COPY | 4,263,840 | 2.4% | 79.2% |  |
| _SAVE_CURRENT_IP | 3,721,920 | 2.1% | 81.3% |  |
| RESUME_CHECK | 2,089,440 | 1.2% | 82.5% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 2,089,440 | 1.2% | 83.7% |  |
| _GUARD_KEYS_VERSION | 2,089,440 | 1.2% | 84.9% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 2,089,440 | 1.2% | 86.0% |  |
| _CHECK_PEP_523 | 2,089,440 | 1.2% | 87.2% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 2,089,440 | 1.2% | 88.4% |  |
| _CHECK_STACK_SPACE | 2,089,440 | 1.2% | 89.6% |  |
| _INIT_CALL_PY_EXACT_ARGS | 2,089,440 | 1.2% | 90.8% |  |
| _PUSH_FRAME | 2,089,440 | 1.2% | 92.0% |  |
| POP_TOP | 1,895,160 | 1.1% | 93.1% |  |
| UNARY_NOT | 1,755,540 | 1.0% | 94.1% |  |
| _POP_FRAME | 1,632,480 | 0.9% | 95.0% |  |
| LOAD_CONST | 1,245,840 | 0.7% | 95.7% |  |
| _GUARD_BOTH_INT | 1,235,100 | 0.7% | 96.4% |  |
| _BINARY_OP_ADD_INT | 826,980 | 0.5% | 96.9% |  |
| _EXIT_TRACE | 607,320 | 0.3% | 97.2% |  |
| _ITER_CHECK_RANGE | 558,480 | 0.3% | 97.6% |  |
| _IS_ITER_EXHAUSTED_RANGE | 558,480 | 0.3% | 97.9% |  |
| STORE_FAST | 418,860 | 0.2% | 98.1% |  |
| SWAP | 418,860 | 0.2% | 98.3% |  |
| COMPARE_OP_INT | 418,860 | 0.2% | 98.6% |  |
| _GUARD_DORV_VALUES | 418,860 | 0.2% | 98.8% |  |
| _STORE_ATTR_INSTANCE_VALUE | 418,860 | 0.2% | 99.1% |  |
| _ITER_NEXT_RANGE | 418,860 | 0.2% | 99.3% |  |
| STORE_SUBSCR_LIST_INT | 408,120 | 0.2% | 99.5% |  |
| _BINARY_OP_SUBTRACT_INT | 408,120 | 0.2% | 99.8% |  |
| _JUMP_TO_TOP | 408,120 | 0.2% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


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
