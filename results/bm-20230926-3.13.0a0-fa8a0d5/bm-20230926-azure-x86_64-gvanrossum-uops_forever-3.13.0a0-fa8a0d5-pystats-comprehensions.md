
# Pystats results

- benchmark: comprehensions
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| ENTER_EXECUTOR | 25,808,620 | 11.2% | 11.2% |  |
| LOAD_FAST | 24,580,700 | 10.7% | 21.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 18,186,580 | 7.9% | 29.8% |  |
| POP_JUMP_IF_TRUE | 11,550,780 | 5.0% | 34.8% |  |
| RESUME_CHECK | 8,358,180 | 3.6% | 38.4% |  |
| POP_TOP | 8,110,680 | 3.5% | 41.9% |  |
| RETURN_VALUE | 7,866,120 | 3.4% | 45.3% |  |
| LIST_APPEND | 7,864,660 | 3.4% | 48.7% |  |
| STORE_FAST | 7,624,760 | 3.3% | 52.1% |  |
| SWAP | 7,619,360 | 3.3% | 55.4% |  |
| INTERPRETER_EXIT | 7,372,980 | 3.2% | 58.6% |  |
| TO_BOOL_ALWAYS_TRUE | 7,178,440 | 3.1% | 61.7% | 38.5% |
| YIELD_VALUE | 7,127,400 | 3.1% | 64.8% |  |
| FOR_ITER_LIST | 5,898,820 | 2.6% | 67.3% |  |
| STORE_FAST_LOAD_FAST | 5,407,060 | 2.3% | 69.7% |  |
| LOAD_FAST_LOAD_FAST | 4,928,160 | 2.1% | 71.8% |  |
| LOAD_GLOBAL_BUILTIN | 4,915,380 | 2.1% | 73.9% |  |
| BINARY_SUBSCR_DICT | 4,915,380 | 2.1% | 76.1% |  |
| CALL_LEN | 4,669,500 | 2.0% | 78.1% |  |
| MAP_ADD | 4,669,440 | 2.0% | 80.1% |  |
| TO_BOOL_NONE | 4,476,560 | 1.9% | 82.1% | 61.7% |
| RETURN_GENERATOR | 4,423,860 | 1.9% | 84.0% |  |
| BUILD_TUPLE | 4,423,860 | 1.9% | 85.9% |  |
| CALL_BUILTIN_O | 4,423,680 | 1.9% | 87.8% |  |
| CALL_INTRINSIC_1 | 4,177,980 | 1.8% | 89.6% |  |
| RERAISE | 4,177,920 | 1.8% | 91.5% |  |
| POP_JUMP_IF_FALSE | 3,686,400 | 1.6% | 93.1% |  |
| TO_BOOL_BOOL | 3,440,640 | 1.5% | 94.5% |  |
| GET_ITER | 1,721,960 | 0.7% | 95.3% |  |
| LOAD_FAST_AND_CLEAR | 1,720,720 | 0.7% | 96.0% |  |
| BUILD_LIST | 1,229,320 | 0.5% | 96.6% |  |
| CALL_PY_EXACT_ARGS | 983,280 | 0.4% | 97.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 745,920 | 0.3% | 97.3% |  |
| LOAD_CONST | 741,100 | 0.3% | 97.6% |  |
| RETURN_CONST | 738,900 | 0.3% | 98.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 737,280 | 0.3% | 98.3% |  |
| LOAD_ATTR_METHOD_NO_DICT | 492,960 | 0.2% | 98.5% |  |
| COMPARE_OP_INT | 491,580 | 0.2% | 98.7% |  |
| BUILD_MAP | 491,520 | 0.2% | 98.9% |  |
| LOAD_GLOBAL_MODULE | 247,660 | 0.1% | 99.0% |  |
| EXIT_INIT_CHECK | 247,200 | 0.1% | 99.1% |  |
| CALL_ALLOC_AND_ENTER_INIT | 247,200 | 0.1% | 99.2% |  |
| LOAD_ATTR | 246,300 | 0.1% | 99.4% |  |
| BINARY_SUBSCR | 246,240 | 0.1% | 99.5% |  |
| MAKE_FUNCTION | 245,940 | 0.1% | 99.6% |  |
| COMPARE_OP | 245,840 | 0.1% | 99.7% |  |
| COPY | 245,760 | 0.1% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 245,760 | 0.1% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 245,760 | 0.1% | 100.0% |  |
| BINARY_OP_ADD_INT | 1,840 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 1,440 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 840 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 640 | 0.0% | 100.0% |  |
| LOAD_DEREF | 540 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 540 | 0.0% | 100.0% |  |
| BUILD_SLICE | 400 | 0.0% | 100.0% |  |
| CALL | 320 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 300 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 240 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 180 | 0.0% | 100.0% |  |
| MAKE_CELL | 180 | 0.0% | 100.0% |  |
| END_FOR | 180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 160 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 13,271,040 | 5.8% | 5.8% |
| LIST_APPEND ENTER_EXECUTOR | 7,864,660 | 3.4% | 9.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 7,127,100 | 3.1% | 12.3% |
| YIELD_VALUE INTERPRETER_EXIT | 7,127,040 | 3.1% | 15.4% |
| LOAD_ATTR_INSTANCE_VALUE YIELD_VALUE | 7,127,040 | 3.1% | 18.4% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_TRUE | 7,126,300 | 3.1% | 21.5% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 5,408,380 | 2.3% | 23.9% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 5,407,060 | 2.3% | 26.2% |
| RESUME_CHECK LOAD_FAST | 4,915,560 | 2.1% | 28.4% |
| SWAP STORE_FAST | 4,669,440 | 2.0% | 30.4% |
| MAP_ADD ENTER_EXECUTOR | 4,669,440 | 2.0% | 32.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 4,669,440 | 2.0% | 34.4% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_SUBSCR_DICT | 4,669,440 | 2.0% | 36.5% |
| ENTER_EXECUTOR SWAP | 4,669,440 | 2.0% | 38.5% |
| TO_BOOL_NONE POP_JUMP_IF_TRUE | 4,424,420 | 1.9% | 40.4% |
| POP_TOP RESUME_CHECK | 4,423,860 | 1.9% | 42.3% |
| LOAD_FAST FOR_ITER_LIST | 4,423,860 | 1.9% | 44.3% |
| STORE_FAST MAP_ADD | 4,423,680 | 1.9% | 46.2% |
| RETURN_VALUE LOAD_GLOBAL_BUILTIN | 4,423,680 | 1.9% | 48.1% |
| RETURN_GENERATOR CALL_BUILTIN_O | 4,423,680 | 1.9% | 50.0% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 4,423,680 | 1.9% | 51.9% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 4,423,680 | 1.9% | 53.9% |
| LOAD_ATTR_INSTANCE_VALUE BUILD_TUPLE | 4,423,680 | 1.9% | 55.8% |
| CALL_LEN LOAD_FAST | 4,423,680 | 1.9% | 57.7% |
| CALL_BUILTIN_O RETURN_VALUE | 4,423,680 | 1.9% | 59.6% |
| CACHE POP_TOP | 4,423,680 | 1.9% | 61.5% |
| BUILD_TUPLE LIST_APPEND | 4,423,680 | 1.9% | 63.5% |
| BINARY_SUBSCR_DICT CALL_LEN | 4,423,680 | 1.9% | 65.4% |
| ENTER_EXECUTOR TO_BOOL_ALWAYS_TRUE | 4,363,620 | 1.9% | 67.3% |
| ENTER_EXECUTOR RETURN_GENERATOR | 4,177,920 | 1.8% | 69.1% |
| CALL_INTRINSIC_1 RERAISE | 4,177,920 | 1.8% | 70.9% |
| CACHE CALL_INTRINSIC_1 | 4,177,920 | 1.8% | 72.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,440,640 | 1.5% | 74.2% |
| RETURN_VALUE TO_BOOL_BOOL | 3,194,880 | 1.4% | 75.6% |
| RESUME_CHECK POP_TOP | 2,949,480 | 1.3% | 76.9% |
| POP_TOP ENTER_EXECUTOR | 2,949,480 | 1.3% | 78.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 2,949,120 | 1.3% | 79.4% |
| LOAD_FAST LIST_APPEND | 2,949,120 | 1.3% | 80.7% |
| ENTER_EXECUTOR RETURN_VALUE | 2,949,120 | 1.3% | 82.0% |
| CACHE RESUME_CHECK | 2,949,120 | 1.3% | 83.3% |
| ENTER_EXECUTOR TO_BOOL_NONE | 2,763,420 | 1.2% | 84.5% |
| STORE_FAST_LOAD_FAST TO_BOOL_ALWAYS_TRUE | 2,762,680 | 1.2% | 85.7% |
| STORE_FAST LOAD_FAST | 1,722,220 | 0.7% | 86.4% |
| STORE_FAST_LOAD_FAST TO_BOOL_NONE | 1,661,000 | 0.7% | 87.1% |
| SWAP FOR_ITER_LIST | 1,474,960 | 0.6% | 87.8% |
| LOAD_FAST_AND_CLEAR SWAP | 1,474,960 | 0.6% | 88.4% |
| GET_ITER LOAD_FAST_AND_CLEAR | 1,474,960 | 0.6% | 89.1% |
| LOAD_FAST GET_ITER | 1,474,620 | 0.6% | 89.7% |
| STORE_FAST STORE_FAST | 1,230,240 | 0.5% | 90.2% |
| ENTER_EXECUTOR STORE_FAST | 984,420 | 0.4% | 90.7% |
| SWAP BUILD_LIST | 983,440 | 0.4% | 91.1% |
| BUILD_LIST SWAP | 983,440 | 0.4% | 91.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 737,340 | 0.3% | 91.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 737,280 | 0.3% | 92.1% |
| FOR_ITER_LIST STORE_FAST | 491,760 | 0.2% | 92.4% |
| SWAP BUILD_MAP | 491,520 | 0.2% | 92.6% |
| POP_TOP LOAD_FAST | 491,520 | 0.2% | 92.8% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 491,520 | 0.2% | 93.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 491,520 | 0.2% | 93.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 491,520 | 0.2% | 93.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 491,520 | 0.2% | 93.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 491,520 | 0.2% | 93.9% |
| BUILD_MAP SWAP | 491,520 | 0.2% | 94.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 254,400 | 0.1% | 94.2% |
| LOAD_FAST LOAD_CONST | 248,000 | 0.1% | 94.3% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 247,200 | 0.1% | 94.4% |
| RETURN_CONST EXIT_INIT_CHECK | 247,200 | 0.1% | 94.5% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 247,200 | 0.1% | 94.6% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 247,200 | 0.1% | 94.7% |
| EXIT_INIT_CHECK RETURN_VALUE | 247,200 | 0.1% | 94.8% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 247,200 | 0.1% | 94.9% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 246,100 | 0.1% | 95.0% |
| LOAD_CONST MAKE_FUNCTION | 245,940 | 0.1% | 95.1% |
| GET_ITER CALL_PY_EXACT_ARGS | 245,940 | 0.1% | 95.2% |
| ENTER_EXECUTOR RETURN_CONST | 245,940 | 0.1% | 95.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 245,880 | 0.1% | 95.5% |
| RETURN_VALUE STORE_FAST | 245,820 | 0.1% | 95.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 245,820 | 0.1% | 95.7% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 245,820 | 0.1% | 95.8% |
| CALL_LEN LOAD_CONST | 245,820 | 0.1% | 95.9% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 245,800 | 0.1% | 96.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 245,800 | 0.1% | 96.1% |
| LOAD_CONST COMPARE_OP_INT | 245,800 | 0.1% | 96.2% |
| STORE_FAST_LOAD_FAST LOAD_FAST | 245,760 | 0.1% | 96.3% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 245,760 | 0.1% | 96.4% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 245,760 | 0.1% | 96.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 245,760 | 0.1% | 96.6% |
| STORE_ATTR_INSTANCE_VALUE BUILD_LIST | 245,760 | 0.1% | 96.7% |
| RETURN_CONST POP_TOP | 245,760 | 0.1% | 96.8% |
| RETURN_CONST INTERPRETER_EXIT | 245,760 | 0.1% | 97.0% |
| POP_TOP RETURN_CONST | 245,760 | 0.1% | 97.1% |
| POP_JUMP_IF_FALSE POP_TOP | 245,760 | 0.1% | 97.2% |
| MAKE_FUNCTION LOAD_FAST | 245,760 | 0.1% | 97.3% |
| LOAD_FAST_AND_CLEAR LOAD_FAST_AND_CLEAR | 245,760 | 0.1% | 97.4% |
| LOAD_FAST MAP_ADD | 245,760 | 0.1% | 97.5% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 245,760 | 0.1% | 97.6% |
| LOAD_CONST BINARY_SUBSCR | 245,760 | 0.1% | 97.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 245,760 | 0.1% | 97.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 245,760 | 0.1% | 97.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 245,760 | 0.1% | 98.0% |


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
| POP_TOP | 4,423,680 | 38.3% |
| CALL_INTRINSIC_1 | 4,177,920 | 36.2% |
| RESUME_CHECK | 2,949,120 | 25.5% |
| MAKE_CELL | 180 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 245,760 | 99.8% |
| BUILD_SLICE | 400 | 0.2% |
| BINARY_SUBSCR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 245,760 | 99.8% |
| GET_ITER | 400 | 0.2% |
| BINARY_SUBSCR | 80 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 180 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 247,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 247,200 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,474,620 | 85.6% |
| LOAD_ATTR_INSTANCE_VALUE | 245,760 | 14.3% |
| LOAD_CONST | 760 | 0.0% |
| BINARY_SUBSCR | 400 | 0.0% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 1,474,960 | 85.7% |
| CALL_PY_EXACT_ARGS | 245,940 | 14.3% |
| FOR_ITER_TUPLE | 760 | 0.0% |
| FOR_ITER_GEN | 180 | 0.0% |
| FOR_ITER_RANGE | 120 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 7,127,040 | 96.7% |
| RETURN_CONST | 245,760 | 3.3% |
| RETURN_VALUE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 245,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 245,760 | 99.9% |
| SET_FUNCTION_ATTRIBUTE | 180 | 0.1% |


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
| CACHE | 4,423,680 | 54.5% |
| RESUME_CHECK | 2,949,480 | 36.4% |
| RETURN_CONST | 245,760 | 3.0% |
| POP_JUMP_IF_FALSE | 245,760 | 3.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 245,760 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,423,860 | 54.5% |
| ENTER_EXECUTOR | 2,949,480 | 36.4% |
| LOAD_FAST | 491,520 | 6.1% |
| RETURN_CONST | 245,760 | 3.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 160 | 53.3% |
| LOAD_DEREF | 120 | 40.0% |
| LOAD_ATTR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 180 | 60.0% |
| LOAD_FAST | 120 | 40.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,177,920 | 94.4% |
| CALL_PY_EXACT_ARGS | 245,760 | 5.6% |
| COPY_FREE_VARS | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 4,423,680 | 100.0% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 4,423,680 | 56.2% |
| ENTER_EXECUTOR | 2,949,120 | 37.5% |
| EXIT_INIT_CHECK | 247,200 | 3.1% |
| LOAD_ATTR_INSTANCE_VALUE | 245,760 | 3.1% |
| RETURN_GENERATOR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,423,680 | 56.2% |
| TO_BOOL_BOOL | 3,194,880 | 40.6% |
| STORE_FAST | 245,820 | 3.1% |
| CALL_LIST_APPEND | 1,440 | 0.0% |
| INTERPRETER_EXIT | 180 | 0.0% |


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
| SWAP | 983,440 | 80.0% |
| STORE_ATTR_INSTANCE_VALUE | 245,760 | 20.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 983,440 | 80.0% |
| LOAD_FAST | 245,760 | 20.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 491,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 491,520 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 400 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,423,680 | 100.0% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 4,423,680 | 100.0% |
| LOAD_CONST | 180 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 56.2% |
| CALL | 60 | 18.8% |
| LOAD_FAST | 40 | 12.5% |
| LOAD_GLOBAL_MODULE | 20 | 6.2% |
| LOAD_CONST | 20 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 18.8% |
| POP_TOP | 60 | 18.8% |
| LOAD_FAST | 60 | 18.8% |
| CALL | 60 | 18.8% |
| CALL_BUILTIN_CLASS | 40 | 12.5% |


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
| CACHE | 4,177,920 | 100.0% |
| LIST_EXTEND | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RERAISE | 4,177,920 | 100.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 245,760 | 100.0% |
| COMPARE_OP | 60 | 0.0% |
| LOAD_CONST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 245,760 | 100.0% |
| COMPARE_OP | 60 | 0.0% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 245,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 245,760 | 100.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 180 | 75.0% |
| CALL_FUNCTION_EX | 60 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 180 | 75.0% |
| RESUME_CHECK | 60 | 25.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 7,864,660 | 30.5% |
| ENTER_EXECUTOR | 5,408,380 | 21.0% |
| MAP_ADD | 4,669,440 | 18.1% |
| POP_JUMP_IF_TRUE | 4,423,680 | 17.1% |
| POP_TOP | 2,949,480 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,408,380 | 21.0% |
| SWAP | 4,669,440 | 18.1% |
| TO_BOOL_ALWAYS_TRUE | 4,363,620 | 16.9% |
| RETURN_GENERATOR | 4,177,920 | 16.2% |
| RETURN_VALUE | 2,949,120 | 11.4% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 420 | 65.6% |
| END_FOR | 180 | 28.1% |
| FOR_ITER_TUPLE | 40 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 360 | 56.2% |
| FOR_ITER_RANGE | 180 | 28.1% |
| FOR_ITER_TUPLE | 80 | 12.5% |
| ENTER_EXECUTOR | 20 | 3.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 4,423,680 | 56.2% |
| LOAD_FAST | 2,949,120 | 37.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 245,760 | 3.1% |
| BINARY_SUBSCR_DICT | 245,760 | 3.1% |
| LOAD_ATTR_INSTANCE_VALUE | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,864,660 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 245,820 | 99.8% |
| LOAD_DEREF | 360 | 0.1% |
| LOAD_ATTR | 100 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 245,760 | 99.8% |
| LOAD_FAST | 180 | 0.1% |
| GET_ITER | 180 | 0.1% |
| LOAD_ATTR | 100 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 248,000 | 33.5% |
| LOAD_GLOBAL_BUILTIN | 245,820 | 33.2% |
| CALL_LEN | 245,820 | 33.2% |
| STORE_FAST | 760 | 0.1% |
| LOAD_CONST | 400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 245,940 | 33.2% |
| COMPARE_OP_INT | 245,800 | 33.2% |
| BINARY_SUBSCR | 245,760 | 33.2% |
| BINARY_OP_ADD_INT | 1,840 | 0.2% |
| GET_ITER | 760 | 0.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 33.3% |
| SET_FUNCTION_ATTRIBUTE | 180 | 33.3% |
| RESUME_CHECK | 60 | 11.1% |
| NOP | 60 | 11.1% |
| BUILD_LIST | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 360 | 66.7% |
| PUSH_NULL | 120 | 22.2% |
| LIST_EXTEND | 60 | 11.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 7,127,100 | 29.0% |
| RESUME_CHECK | 4,915,560 | 20.0% |
| CALL_LEN | 4,423,680 | 18.0% |
| POP_JUMP_IF_FALSE | 2,949,120 | 12.0% |
| STORE_FAST | 1,722,220 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 13,271,040 | 54.0% |
| FOR_ITER_LIST | 4,423,860 | 18.0% |
| LIST_APPEND | 2,949,120 | 12.0% |
| GET_ITER | 1,474,620 | 6.0% |
| STORE_ATTR_INSTANCE_VALUE | 491,520 | 2.0% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,474,960 | 85.7% |
| LOAD_FAST_AND_CLEAR | 245,760 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,474,960 | 85.7% |
| LOAD_FAST_AND_CLEAR | 245,760 | 14.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,423,680 | 89.8% |
| RESUME_CHECK | 247,200 | 5.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 245,760 | 5.0% |
| STORE_ATTR_INSTANCE_VALUE | 7,200 | 0.1% |
| LOAD_FAST_LOAD_FAST | 2,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,669,440 | 94.8% |
| STORE_ATTR_INSTANCE_VALUE | 254,400 | 5.2% |
| LOAD_FAST_LOAD_FAST | 2,880 | 0.1% |
| CALL_ALLOC_AND_ENTER_INIT | 1,440 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 37.5% |
| RETURN_VALUE | 40 | 25.0% |
| RESUME_CHECK | 20 | 12.5% |
| FOR_ITER_RANGE | 20 | 12.5% |
| ENTER_EXECUTOR | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 37.5% |
| LOAD_ATTR | 20 | 12.5% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 180 | 100.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,423,680 | 94.7% |
| LOAD_FAST | 245,760 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,669,440 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,440,640 | 93.3% |
| COMPARE_OP_INT | 245,760 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,949,120 | 80.0% |
| ENTER_EXECUTOR | 491,520 | 13.3% |
| POP_TOP | 245,760 | 6.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 7,126,300 | 61.7% |
| TO_BOOL_NONE | 4,424,420 | 38.3% |
| COMPARE_OP_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,127,100 | 61.7% |
| ENTER_EXECUTOR | 4,423,680 | 38.3% |


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 4,177,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 247,200 | 33.5% |
| ENTER_EXECUTOR | 245,940 | 33.3% |
| POP_TOP | 245,760 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXIT_INIT_CHECK | 247,200 | 33.5% |
| POP_TOP | 245,760 | 33.3% |
| INTERPRETER_EXIT | 245,760 | 33.3% |
| END_FOR | 180 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 180 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 4,669,440 | 61.2% |
| STORE_FAST | 1,230,240 | 16.1% |
| ENTER_EXECUTOR | 984,420 | 12.9% |
| FOR_ITER_LIST | 491,760 | 6.4% |
| RETURN_VALUE | 245,820 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 4,423,680 | 58.0% |
| LOAD_FAST | 1,722,220 | 22.6% |
| STORE_FAST | 1,230,240 | 16.1% |
| LOAD_GLOBAL_BUILTIN | 245,800 | 3.2% |
| ENTER_EXECUTOR | 1,440 | 0.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,407,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 2,762,680 | 51.1% |
| TO_BOOL_NONE | 1,661,000 | 30.7% |
| LOAD_ATTR_INSTANCE_VALUE | 246,100 | 4.6% |
| LOAD_FAST | 245,760 | 4.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 245,760 | 4.5% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,669,440 | 61.3% |
| LOAD_FAST_AND_CLEAR | 1,474,960 | 19.4% |
| BUILD_LIST | 983,440 | 12.9% |
| BUILD_MAP | 491,520 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,669,440 | 61.3% |
| FOR_ITER_LIST | 1,474,960 | 19.4% |
| BUILD_LIST | 983,440 | 12.9% |
| BUILD_MAP | 491,520 | 6.5% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,127,040 | 100.0% |
| ENTER_EXECUTOR | 180 | 0.0% |
| BINARY_SUBSCR_DICT | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 7,127,040 | 100.0% |
| STORE_FAST | 360 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,440 | 78.3% |
| BUILD_SLICE | 400 | 21.7% |


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
| LOAD_ATTR_INSTANCE_VALUE | 4,669,440 | 95.0% |
| BINARY_SUBSCR | 245,760 | 5.0% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 4,423,680 | 90.0% |
| LIST_APPEND | 245,760 | 5.0% |
| CALL_PY_EXACT_ARGS | 245,760 | 5.0% |
| YIELD_VALUE | 180 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 245,700 | 99.4% |
| LOAD_FAST_LOAD_FAST | 1,440 | 0.6% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 247,200 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 33.3% |
| LOAD_CONST | 40 | 33.3% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| GET_ITER | 60 | 50.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 4,423,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,423,680 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 4,423,680 | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE | 245,760 | 5.3% |
| LOAD_FAST | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,423,680 | 94.7% |
| LOAD_CONST | 245,820 | 5.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,440 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 245,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 245,760 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 245,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 245,760 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 491,520 | 50.0% |
| GET_ITER | 245,940 | 25.0% |
| BINARY_SUBSCR_DICT | 245,760 | 25.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 737,340 | 75.0% |
| RETURN_GENERATOR | 245,760 | 25.0% |
| COPY_FREE_VARS | 180 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 245,800 | 50.0% |
| LOAD_ATTR_INSTANCE_VALUE | 245,760 | 50.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 245,760 | 50.0% |
| LOAD_FAST | 245,760 | 50.0% |
| POP_JUMP_IF_TRUE | 60 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 360 | 66.7% |
| GET_ITER | 180 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 360 | 66.7% |
| POP_TOP | 180 | 33.3% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,423,860 | 75.0% |
| SWAP | 1,474,960 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 5,407,060 | 91.7% |
| STORE_FAST | 491,760 | 8.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 180 | 60.0% |
| GET_ITER | 120 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 80.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 13.3% |
| LOAD_GLOBAL | 20 | 6.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 760 | 90.5% |
| JUMP_BACKWARD | 80 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 800 | 95.2% |
| JUMP_BACKWARD | 40 | 4.8% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,271,040 | 73.0% |
| LOAD_FAST_LOAD_FAST | 4,669,440 | 25.7% |
| STORE_FAST_LOAD_FAST | 246,100 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 7,127,040 | 39.2% |
| BINARY_SUBSCR_DICT | 4,669,440 | 25.7% |
| BUILD_TUPLE | 4,423,680 | 24.3% |
| LOAD_FAST | 737,280 | 4.1% |
| RETURN_VALUE | 245,760 | 1.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 247,200 | 50.1% |
| STORE_FAST_LOAD_FAST | 245,760 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 245,760 | 49.9% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 245,760 | 49.9% |
| LOAD_GLOBAL_MODULE | 1,440 | 0.3% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 491,520 | 66.7% |
| STORE_FAST_LOAD_FAST | 245,760 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 491,520 | 66.7% |
| LOAD_FAST_LOAD_FAST | 245,760 | 33.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 100 | 62.5% |
| LOAD_ATTR | 60 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,423,680 | 90.0% |
| STORE_FAST | 245,800 | 5.0% |
| RESUME_CHECK | 245,800 | 5.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| FOR_ITER_RANGE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,423,680 | 90.0% |
| LOAD_FAST | 245,880 | 5.0% |
| LOAD_CONST | 245,820 | 5.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 245,760 | 99.2% |
| LOAD_ATTR_METHOD_NO_DICT | 1,440 | 0.6% |
| STORE_FAST | 320 | 0.1% |
| LOAD_GLOBAL | 80 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 245,820 | 99.3% |
| LOAD_FAST_LOAD_FAST | 1,440 | 0.6% |
| GET_ITER | 180 | 0.1% |
| LOAD_ATTR_MODULE | 100 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,423,860 | 52.9% |
| CACHE | 2,949,120 | 35.3% |
| CALL_PY_EXACT_ARGS | 737,340 | 8.8% |
| CALL_ALLOC_AND_ENTER_INIT | 247,200 | 3.0% |
| FOR_ITER_GEN | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,915,560 | 58.8% |
| POP_TOP | 2,949,480 | 35.3% |
| LOAD_FAST_LOAD_FAST | 247,200 | 3.0% |
| LOAD_GLOBAL_BUILTIN | 245,800 | 2.9% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 491,520 | 65.9% |
| LOAD_FAST_LOAD_FAST | 254,400 | 34.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 247,200 | 33.1% |
| LOAD_FAST | 245,760 | 32.9% |
| BUILD_LIST | 245,760 | 32.9% |
| LOAD_FAST_LOAD_FAST | 7,200 | 1.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,363,620 | 60.8% |
| STORE_FAST_LOAD_FAST | 2,762,680 | 38.5% |
| TO_BOOL_NONE | 52,140 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 7,126,300 | 99.3% |
| TO_BOOL_NONE | 52,140 | 0.7% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,194,880 | 92.9% |
| COPY | 245,760 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,440,640 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,763,420 | 61.7% |
| STORE_FAST_LOAD_FAST | 1,661,000 | 37.1% |
| TO_BOOL_ALWAYS_TRUE | 52,140 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,424,420 | 98.8% |
| TO_BOOL_ALWAYS_TRUE | 52,140 | 1.2% |


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
| specialization.deferred |       246160 | 1.8% |
|          hit |     13271400 | 98.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 80 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 60 | 75.0% |
| list slice | 20 | 25.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |       104280 | 0.4% |
|          hit |     19399940 | 77.8% |
|         miss |      5526100 | 22.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 104,280 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         2940 | 99.3% |

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
| specialization.deferred |          180 | 0.0% |
|          hit |     51121380 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 57.1% |
| Failure | 60 | 42.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       245760 | 5.0% |
|          hit |      4669500 | 95.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 25.0% |
| Failure | 60 | 75.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 60 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      5900500 | 100.0% |


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
| specialization.deferred |       246140 | 0.3% |
|          hit |     88974580 | 99.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 37.5% |
| Failure | 100 | 62.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 100 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     15239140 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
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
|          hit |       745920 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 143,568,240 | 62.3% |
| Not specialized | 21,502,800 | 9.3% |
| Specialized | 65,379,760 | 28.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 246,160 | 33.3% |
| LOAD_ATTR | 246,140 | 33.3% |
| COMPARE_OP | 245,760 | 33.3% |
| CALL | 180 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| TO_BOOL_ALWAYS_TRUE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_NONE | 2,763,420 | 50.0% |
| TO_BOOL_ALWAYS_TRUE | 2,762,680 | 50.0% |
| YIELD_VALUE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_FAST_LOAD_FAST | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 0 | 0.0% |
| SET_FUNCTION_ATTRIBUTE | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 11,550,900 | 43.1% |
| Calls to Python functions inlined | 15,239,460 | 56.9% |
| Calls via PyEval_EvalFrame (total) | 11,550,900 | 43.1% |
| Calls via PyEval_EvalFrame (vector) | 180 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 11,550,720 | 43.1% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 180 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 180 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 15,486,300 | 57.8% |
| Frame objects created | 8,355,840 | 31.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 10,325,260 | 21.4% |
| Frees to freelist | 10,325,220 |  |
| Allocations | 37,839,520 | 78.6% |
| Allocations to 512 bytes | 37,347,980 | 77.5% |
| Allocations to 4 kbytes | 491,540 | 1.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 43,001,880 |  |
| New values | 0 |  |
| Interpreter increfs | 97,108,020 | 25.5% |
| Interpreter decrefs | 129,546,340 | 30.3% |
| Increfs | 283,637,660 | 74.5% |
| Decrefs | 297,642,280 | 69.7% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 11,797,579 |  |
| Method cache misses | 1 |  |
| Method cache collisions | 1 |  |
| Method cache dunder hits | 180 |  |
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
