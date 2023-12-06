
# Pystats results

- benchmark: comprehensions
- fork: gvanrossum
- ref: load-attr-uops
- commit hash: b54eee3
- commit date: 2023-09-26T21:26:46-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 100,031,220 | 13.8% | 13.8% |  |
| FOR_ITER_LIST | 69,068,400 | 9.5% | 23.3% |  |
| JUMP_BACKWARD | 59,239,080 | 8.1% | 31.4% |  |
| STORE_FAST_LOAD_FAST | 54,320,820 | 7.5% | 38.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 51,617,460 | 7.1% | 46.0% |  |
| LIST_APPEND | 39,820,980 | 5.5% | 51.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 26,789,280 | 3.7% | 55.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 26,542,080 | 3.7% | 58.8% |  |
| RESUME_CHECK | 18,188,580 | 2.5% | 61.3% |  |
| STORE_FAST | 16,227,840 | 2.2% | 63.5% |  |
| SWAP | 15,977,280 | 2.2% | 65.7% |  |
| CALL_PY_EXACT_ARGS | 14,991,600 | 2.1% | 67.8% |  |
| BINARY_SUBSCR_DICT | 13,271,400 | 1.8% | 69.6% |  |
| POP_JUMP_IF_TRUE | 13,025,340 | 1.8% | 71.4% |  |
| POP_JUMP_IF_FALSE | 12,042,240 | 1.7% | 73.1% |  |
| TO_BOOL_BOOL | 11,796,480 | 1.6% | 74.7% |  |
| POP_TOP | 10,814,040 | 1.5% | 76.2% |  |
| RETURN_VALUE | 10,569,480 | 1.5% | 77.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,567,680 | 1.5% | 79.1% |  |
| GET_ITER | 10,079,160 | 1.4% | 80.5% |  |
| LOAD_CONST | 9,346,080 | 1.3% | 81.8% |  |
| LOAD_FAST_LOAD_FAST | 9,106,080 | 1.3% | 83.0% |  |
| LOAD_GLOBAL_BUILTIN | 9,093,300 | 1.3% | 84.3% |  |
| MAP_ADD | 8,847,360 | 1.2% | 85.5% |  |
| INTERPRETER_EXIT | 7,372,980 | 1.0% | 86.5% |  |
| TO_BOOL_ALWAYS_TRUE | 7,188,480 | 1.0% | 87.5% | 45.3% |
| YIELD_VALUE | 7,127,400 | 1.0% | 88.5% |  |
| LOAD_GLOBAL_MODULE | 6,145,840 | 0.8% | 89.3% |  |
| TO_BOOL_NONE | 5,959,680 | 0.8% | 90.1% | 54.6% |
| LOAD_ATTR | 5,900,320 | 0.8% | 90.9% |  |
| COMPARE_OP | 5,899,700 | 0.8% | 91.7% |  |
| LOAD_FAST_AND_CLEAR | 5,899,680 | 0.8% | 92.6% |  |
| COPY | 5,898,240 | 0.8% | 93.4% |  |
| BUILD_LIST | 5,408,280 | 0.7% | 94.1% |  |
| COMPARE_OP_INT | 4,669,500 | 0.6% | 94.8% |  |
| CALL_LEN | 4,669,500 | 0.6% | 95.4% |  |
| BINARY_SUBSCR | 4,426,240 | 0.6% | 96.0% |  |
| RETURN_GENERATOR | 4,423,860 | 0.6% | 96.6% |  |
| MAKE_FUNCTION | 4,423,860 | 0.6% | 97.2% |  |
| BUILD_TUPLE | 4,423,860 | 0.6% | 97.8% |  |
| CALL_BUILTIN_O | 4,423,680 | 0.6% | 98.4% |  |
| CALL_INTRINSIC_1 | 4,177,980 | 0.6% | 99.0% |  |
| RERAISE | 4,177,920 | 0.6% | 99.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 745,920 | 0.1% | 99.7% |  |
| RETURN_CONST | 738,900 | 0.1% | 99.8% |  |
| BUILD_MAP | 491,520 | 0.1% | 99.9% |  |
| EXIT_INIT_CHECK | 247,200 | 0.0% | 99.9% |  |
| CALL_ALLOC_AND_ENTER_INIT | 247,200 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 246,060 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 245,760 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 3,240 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_INT | 2,880 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 1,440 | 0.0% | 100.0% |  |
| BUILD_SLICE | 1,440 | 0.0% | 100.0% |  |
| LOAD_DEREF | 720 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 540 | 0.0% | 100.0% |  |
| CALL | 320 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
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
| JUMP_BACKWARD FOR_ITER_LIST | 58,990,620 | 8.1% | 8.1% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 54,320,820 | 7.5% | 15.6% |
| LIST_APPEND JUMP_BACKWARD | 39,820,980 | 5.5% | 21.1% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 38,338,560 | 5.3% | 26.3% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 26,542,080 | 3.7% | 30.0% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 26,542,080 | 3.7% | 33.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 26,542,080 | 3.7% | 37.3% |
| CALL_METHOD_DESCRIPTOR_FAST LIST_APPEND | 26,542,080 | 3.7% | 40.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 13,271,040 | 1.8% | 42.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 11,796,480 | 1.6% | 44.4% |
| RESUME_CHECK LOAD_FAST | 10,568,040 | 1.5% | 45.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,567,740 | 1.5% | 47.3% |
| STORE_FAST LOAD_FAST | 10,079,100 | 1.4% | 48.7% |
| FOR_ITER_LIST STORE_FAST | 9,832,200 | 1.4% | 50.0% |
| MAP_ADD JUMP_BACKWARD | 8,847,360 | 1.2% | 51.3% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 8,847,360 | 1.2% | 52.5% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_SUBSCR_DICT | 8,847,360 | 1.2% | 53.7% |
| POP_JUMP_IF_TRUE LOAD_FAST | 7,127,100 | 1.0% | 54.7% |
| YIELD_VALUE INTERPRETER_EXIT | 7,127,040 | 1.0% | 55.6% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_TRUE | 7,127,040 | 1.0% | 56.6% |
| STORE_FAST_LOAD_FAST TO_BOOL_ALWAYS_TRUE | 7,127,040 | 1.0% | 57.6% |
| LOAD_ATTR_INSTANCE_VALUE YIELD_VALUE | 7,127,040 | 1.0% | 58.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 6,144,000 | 0.8% | 59.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 6,144,000 | 0.8% | 60.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 5,898,300 | 0.8% | 61.1% |
| TO_BOOL_NONE POP_JUMP_IF_TRUE | 5,898,240 | 0.8% | 61.9% |
| STORE_FAST_LOAD_FAST TO_BOOL_NONE | 5,898,240 | 0.8% | 62.7% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,898,240 | 0.8% | 63.5% |
| RETURN_VALUE TO_BOOL_BOOL | 5,898,240 | 0.8% | 64.3% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 5,898,240 | 0.8% | 65.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 5,898,240 | 0.8% | 66.0% |
| LOAD_ATTR COMPARE_OP | 5,898,240 | 0.8% | 66.8% |
| COPY TO_BOOL_BOOL | 5,898,240 | 0.8% | 67.6% |
| COMPARE_OP COPY | 5,898,240 | 0.8% | 68.4% |
| SWAP FOR_ITER_LIST | 5,653,920 | 0.8% | 69.2% |
| LOAD_FAST_AND_CLEAR SWAP | 5,653,920 | 0.8% | 69.9% |
| GET_ITER LOAD_FAST_AND_CLEAR | 5,653,920 | 0.8% | 70.7% |
| LOAD_FAST GET_ITER | 5,652,540 | 0.8% | 71.5% |
| SWAP BUILD_LIST | 5,162,400 | 0.7% | 72.2% |
| BUILD_LIST SWAP | 5,162,400 | 0.7% | 72.9% |
| SWAP STORE_FAST | 4,669,440 | 0.6% | 73.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 4,669,440 | 0.6% | 74.2% |
| FOR_ITER_LIST SWAP | 4,669,440 | 0.6% | 74.9% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 4,431,540 | 0.6% | 75.5% |
| LOAD_FAST LOAD_CONST | 4,428,000 | 0.6% | 76.1% |
| POP_TOP RESUME_CHECK | 4,423,860 | 0.6% | 76.7% |
| LOAD_FAST FOR_ITER_LIST | 4,423,860 | 0.6% | 77.3% |
| LOAD_CONST MAKE_FUNCTION | 4,423,860 | 0.6% | 77.9% |
| GET_ITER CALL_PY_EXACT_ARGS | 4,423,860 | 0.6% | 78.5% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 4,423,740 | 0.6% | 79.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 4,423,720 | 0.6% | 79.7% |
| STORE_FAST_LOAD_FAST LOAD_FAST | 4,423,680 | 0.6% | 80.3% |
| STORE_FAST MAP_ADD | 4,423,680 | 0.6% | 80.9% |
| RETURN_VALUE LOAD_GLOBAL_BUILTIN | 4,423,680 | 0.6% | 81.5% |
| RETURN_GENERATOR CALL_BUILTIN_O | 4,423,680 | 0.6% | 82.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 4,423,680 | 0.6% | 82.8% |
| MAKE_FUNCTION LOAD_FAST | 4,423,680 | 0.6% | 83.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 4,423,680 | 0.6% | 84.0% |
| LOAD_FAST MAP_ADD | 4,423,680 | 0.6% | 84.6% |
| LOAD_FAST LIST_APPEND | 4,423,680 | 0.6% | 85.2% |
| LOAD_CONST BINARY_SUBSCR | 4,423,680 | 0.6% | 85.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 4,423,680 | 0.6% | 86.4% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 4,423,680 | 0.6% | 87.0% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 4,423,680 | 0.6% | 87.6% |
| LOAD_ATTR_INSTANCE_VALUE BUILD_TUPLE | 4,423,680 | 0.6% | 88.2% |
| COMPARE_OP_INT LOAD_FAST | 4,423,680 | 0.6% | 88.8% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 4,423,680 | 0.6% | 89.5% |
| CALL_LEN LOAD_FAST | 4,423,680 | 0.6% | 90.1% |
| CALL_BUILTIN_O RETURN_VALUE | 4,423,680 | 0.6% | 90.7% |
| CACHE POP_TOP | 4,423,680 | 0.6% | 91.3% |
| BUILD_TUPLE LIST_APPEND | 4,423,680 | 0.6% | 91.9% |
| BINARY_SUBSCR_DICT LIST_APPEND | 4,423,680 | 0.6% | 92.5% |
| BINARY_SUBSCR_DICT CALL_PY_EXACT_ARGS | 4,423,680 | 0.6% | 93.1% |
| BINARY_SUBSCR_DICT CALL_LEN | 4,423,680 | 0.6% | 93.7% |
| BINARY_SUBSCR BINARY_SUBSCR_DICT | 4,423,680 | 0.6% | 94.3% |
| CALL_INTRINSIC_1 RERAISE | 4,177,920 | 0.6% | 94.9% |
| CACHE CALL_INTRINSIC_1 | 4,177,920 | 0.6% | 95.5% |
| POP_TOP LOAD_FAST | 3,194,880 | 0.4% | 95.9% |
| RESUME_CHECK POP_TOP | 2,949,480 | 0.4% | 96.3% |
| POP_TOP JUMP_BACKWARD | 2,949,480 | 0.4% | 96.7% |
| POP_JUMP_IF_FALSE RETURN_VALUE | 2,949,120 | 0.4% | 97.1% |
| POP_JUMP_IF_FALSE POP_TOP | 2,949,120 | 0.4% | 97.5% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,949,120 | 0.4% | 97.9% |
| CACHE RESUME_CHECK | 2,949,120 | 0.4% | 98.3% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 1,720,320 | 0.2% | 98.6% |
| STORE_FAST STORE_FAST | 1,230,240 | 0.2% | 98.8% |
| SWAP BUILD_MAP | 491,520 | 0.1% | 98.8% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 491,520 | 0.1% | 98.9% |
| BUILD_MAP SWAP | 491,520 | 0.1% | 99.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 254,400 | 0.0% | 99.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 247,200 | 0.0% | 99.0% |
| RETURN_CONST EXIT_INIT_CHECK | 247,200 | 0.0% | 99.1% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 247,200 | 0.0% | 99.1% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 247,200 | 0.0% | 99.1% |
| LOAD_CONST LOAD_FAST | 247,200 | 0.0% | 99.2% |
| EXIT_INIT_CHECK RETURN_VALUE | 247,200 | 0.0% | 99.2% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 247,200 | 0.0% | 99.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 246,020 | 0.0% | 99.3% |
| JUMP_BACKWARD FOR_ITER_RANGE | 245,940 | 0.0% | 99.3% |
| FOR_ITER_RANGE STORE_FAST | 245,940 | 0.0% | 99.3% |


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
| LOAD_CONST | 4,423,680 | 99.9% |
| BUILD_SLICE | 1,440 | 0.0% |
| BINARY_SUBSCR | 1,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 4,423,680 | 99.9% |
| GET_ITER | 1,440 | 0.0% |
| BINARY_SUBSCR | 1,120 | 0.0% |


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
| LOAD_FAST | 5,652,540 | 56.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,423,680 | 43.9% |
| BINARY_SUBSCR | 1,440 | 0.0% |
| LOAD_CONST | 1,080 | 0.0% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 5,653,920 | 56.1% |
| CALL_PY_EXACT_ARGS | 4,423,860 | 43.9% |
| FOR_ITER_TUPLE | 1,080 | 0.0% |
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
| LOAD_CONST | 4,423,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,423,680 | 100.0% |
| SET_FUNCTION_ATTRIBUTE | 180 | 0.0% |


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
| CACHE | 4,423,680 | 40.9% |
| RESUME_CHECK | 2,949,480 | 27.3% |
| POP_JUMP_IF_FALSE | 2,949,120 | 27.3% |
| RETURN_CONST | 245,760 | 2.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 245,760 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,423,860 | 40.9% |
| LOAD_FAST | 3,194,880 | 29.5% |
| JUMP_BACKWARD | 2,949,480 | 27.3% |
| RETURN_CONST | 245,760 | 2.3% |
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
| CALL_PY_EXACT_ARGS | 4,423,680 | 100.0% |
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
| CALL_BUILTIN_O | 4,423,680 | 41.9% |
| POP_JUMP_IF_FALSE | 2,949,120 | 27.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,949,120 | 27.9% |
| EXIT_INIT_CHECK | 247,200 | 2.3% |
| RETURN_GENERATOR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,898,240 | 55.8% |
| LOAD_GLOBAL_BUILTIN | 4,423,680 | 41.9% |
| STORE_FAST | 245,820 | 2.3% |
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
| SWAP | 5,162,400 | 95.5% |
| STORE_ATTR_INSTANCE_VALUE | 245,760 | 4.5% |
| STORE_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 5,162,400 | 95.5% |
| LOAD_FAST | 245,760 | 4.5% |
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
| BINARY_OP_ADD_INT | 1,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 1,440 | 100.0% |


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
| LOAD_ATTR | 5,898,240 | 100.0% |
| COMPARE_OP | 1,440 | 0.0% |
| LOAD_CONST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 5,898,240 | 100.0% |
| COMPARE_OP | 1,440 | 0.0% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 5,898,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 5,898,240 | 100.0% |


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

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 39,820,980 | 67.2% |
| MAP_ADD | 8,847,360 | 14.9% |
| POP_JUMP_IF_TRUE | 5,898,240 | 10.0% |
| POP_TOP | 2,949,480 | 5.0% |
| POP_JUMP_IF_FALSE | 1,720,320 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 58,990,620 | 99.6% |
| FOR_ITER_RANGE | 245,940 | 0.4% |
| FOR_ITER_TUPLE | 2,160 | 0.0% |
| FOR_ITER_GEN | 360 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 26,542,080 | 66.7% |
| LOAD_FAST | 4,423,680 | 11.1% |
| BUILD_TUPLE | 4,423,680 | 11.1% |
| BINARY_SUBSCR_DICT | 4,423,680 | 11.1% |
| LOAD_ATTR_INSTANCE_VALUE | 7,860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 39,820,980 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 5,898,300 | 100.0% |
| LOAD_ATTR | 1,460 | 0.0% |
| LOAD_DEREF | 540 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 5,898,240 | 100.0% |
| LOAD_ATTR | 1,460 | 0.0% |
| LOAD_FAST | 360 | 0.0% |
| GET_ITER | 180 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,428,000 | 47.4% |
| LOAD_GLOBAL_BUILTIN | 4,423,740 | 47.3% |
| CALL_LEN | 245,820 | 2.6% |
| LOAD_GLOBAL_MODULE | 245,760 | 2.6% |
| LOAD_CONST | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 4,423,860 | 47.3% |
| BINARY_SUBSCR | 4,423,680 | 47.3% |
| LOAD_FAST | 247,200 | 2.6% |
| COMPARE_OP_INT | 245,800 | 2.6% |
| BINARY_OP_ADD_INT | 2,880 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 360 | 50.0% |
| SET_FUNCTION_ATTRIBUTE | 180 | 25.0% |
| RESUME_CHECK | 60 | 8.3% |
| NOP | 60 | 8.3% |
| BUILD_LIST | 60 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 540 | 75.0% |
| PUSH_NULL | 120 | 16.7% |
| LIST_EXTEND | 60 | 8.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 26,542,080 | 26.5% |
| LOAD_ATTR_INSTANCE_VALUE | 13,271,040 | 13.3% |
| RESUME_CHECK | 10,568,040 | 10.6% |
| STORE_FAST | 10,079,100 | 10.1% |
| POP_JUMP_IF_TRUE | 7,127,100 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 38,338,560 | 38.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 26,542,080 | 26.5% |
| CALL_PY_EXACT_ARGS | 6,144,000 | 6.1% |
| GET_ITER | 5,652,540 | 5.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,669,440 | 4.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,653,920 | 95.8% |
| LOAD_FAST_AND_CLEAR | 245,760 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 5,653,920 | 95.8% |
| LOAD_FAST_AND_CLEAR | 245,760 | 4.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,423,680 | 48.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,423,680 | 48.6% |
| RESUME_CHECK | 247,200 | 2.7% |
| STORE_ATTR_INSTANCE_VALUE | 7,200 | 0.1% |
| LOAD_FAST_LOAD_FAST | 2,880 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,847,360 | 97.2% |
| STORE_ATTR_INSTANCE_VALUE | 254,400 | 2.8% |
| LOAD_FAST_LOAD_FAST | 2,880 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 1,440 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 37.5% |
| RETURN_VALUE | 40 | 25.0% |
| FOR_ITER_RANGE | 40 | 25.0% |
| RESUME_CHECK | 20 | 12.5% |

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
| STORE_FAST | 4,423,680 | 50.0% |
| LOAD_FAST | 4,423,680 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 8,847,360 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 11,796,480 | 98.0% |
| COMPARE_OP_INT | 245,760 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,423,680 | 36.7% |
| RETURN_VALUE | 2,949,120 | 24.5% |
| POP_TOP | 2,949,120 | 24.5% |
| JUMP_BACKWARD | 1,720,320 | 14.3% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 7,127,040 | 54.7% |
| TO_BOOL_NONE | 5,898,240 | 45.3% |
| COMPARE_OP_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,127,100 | 54.7% |
| JUMP_BACKWARD | 5,898,240 | 45.3% |


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
| FOR_ITER_LIST | 245,940 | 33.3% |
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
| FOR_ITER_LIST | 9,832,200 | 60.6% |
| SWAP | 4,669,440 | 28.8% |
| STORE_FAST | 1,230,240 | 7.6% |
| FOR_ITER_RANGE | 245,940 | 1.5% |
| RETURN_VALUE | 245,820 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,079,100 | 62.1% |
| MAP_ADD | 4,423,680 | 27.3% |
| STORE_FAST | 1,230,240 | 7.6% |
| LOAD_GLOBAL_MODULE | 246,020 | 1.5% |
| LOAD_GLOBAL_BUILTIN | 245,800 | 1.5% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 54,320,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 26,542,080 | 48.9% |
| TO_BOOL_ALWAYS_TRUE | 7,127,040 | 13.1% |
| TO_BOOL_NONE | 5,898,240 | 10.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,898,240 | 10.9% |
| LOAD_ATTR_INSTANCE_VALUE | 4,431,540 | 8.2% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 5,653,920 | 35.4% |
| BUILD_LIST | 5,162,400 | 32.3% |
| FOR_ITER_LIST | 4,669,440 | 29.2% |
| BUILD_MAP | 491,520 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,653,920 | 35.4% |
| BUILD_LIST | 5,162,400 | 32.3% |
| STORE_FAST | 4,669,440 | 29.2% |
| BUILD_MAP | 491,520 | 3.1% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,127,040 | 100.0% |
| BINARY_SUBSCR_DICT | 360 | 0.0% |

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
| LOAD_CONST | 2,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,440 | 50.0% |
| BUILD_SLICE | 1,440 | 50.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 8,847,360 | 66.7% |
| BINARY_SUBSCR | 4,423,680 | 33.3% |
| LOAD_FAST | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 4,423,680 | 33.3% |
| CALL_PY_EXACT_ARGS | 4,423,680 | 33.3% |
| CALL_LEN | 4,423,680 | 33.3% |
| YIELD_VALUE | 360 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 245,760 | 99.4% |
| LOAD_FAST_LOAD_FAST | 1,440 | 0.6% |

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
| LOAD_FAST | 26,542,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 26,542,080 | 100.0% |


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
| LOAD_FAST | 6,144,000 | 41.0% |
| GET_ITER | 4,423,860 | 29.5% |
| BINARY_SUBSCR_DICT | 4,423,680 | 29.5% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,567,740 | 70.5% |
| RETURN_GENERATOR | 4,423,680 | 29.5% |
| COPY_FREE_VARS | 180 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,423,680 | 94.7% |
| LOAD_CONST | 245,800 | 5.3% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,423,680 | 94.7% |
| POP_JUMP_IF_FALSE | 245,760 | 5.3% |
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
| JUMP_BACKWARD | 58,990,620 | 85.4% |
| SWAP | 5,653,920 | 8.2% |
| LOAD_FAST | 4,423,860 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 54,320,820 | 78.6% |
| STORE_FAST | 9,832,200 | 14.2% |
| SWAP | 4,669,440 | 6.8% |
| RETURN_CONST | 245,940 | 0.4% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 245,940 | 100.0% |
| GET_ITER | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 245,940 | 100.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,160 | 66.7% |
| GET_ITER | 1,080 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,160 | 66.7% |
| JUMP_BACKWARD | 1,080 | 33.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,338,560 | 74.3% |
| LOAD_FAST_LOAD_FAST | 8,847,360 | 17.1% |
| STORE_FAST_LOAD_FAST | 4,431,540 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,271,040 | 25.7% |
| BINARY_SUBSCR_DICT | 8,847,360 | 17.1% |
| YIELD_VALUE | 7,127,040 | 13.8% |
| LOAD_GLOBAL_MODULE | 5,898,240 | 11.4% |
| GET_ITER | 4,423,680 | 8.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 26,542,080 | 99.1% |
| LOAD_FAST | 247,200 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,542,080 | 99.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 245,760 | 0.9% |
| LOAD_GLOBAL_MODULE | 1,440 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 5,898,240 | 55.8% |
| LOAD_FAST | 4,669,440 | 44.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,144,000 | 58.1% |
| LOAD_FAST_LOAD_FAST | 4,423,680 | 41.9% |


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
| RESUME_CHECK | 4,423,720 | 48.6% |
| RETURN_VALUE | 4,423,680 | 48.6% |
| STORE_FAST | 245,800 | 2.7% |
| LOAD_GLOBAL | 60 | 0.0% |
| FOR_ITER_RANGE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,423,740 | 48.6% |
| LOAD_FAST_LOAD_FAST | 4,423,680 | 48.6% |
| LOAD_FAST | 245,880 | 2.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,898,240 | 96.0% |
| STORE_FAST | 246,020 | 4.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,440 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |
| FOR_ITER_RANGE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 5,898,300 | 96.0% |
| LOAD_CONST | 245,760 | 4.0% |
| LOAD_FAST_LOAD_FAST | 1,440 | 0.0% |
| GET_ITER | 180 | 0.0% |
| LOAD_ATTR_MODULE | 100 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 10,567,740 | 58.1% |
| POP_TOP | 4,423,860 | 24.3% |
| CACHE | 2,949,120 | 16.2% |
| CALL_ALLOC_AND_ENTER_INIT | 247,200 | 1.4% |
| FOR_ITER_GEN | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,568,040 | 58.1% |
| LOAD_GLOBAL_BUILTIN | 4,423,720 | 24.3% |
| POP_TOP | 2,949,480 | 16.2% |
| LOAD_FAST_LOAD_FAST | 247,200 | 1.4% |
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
| STORE_FAST_LOAD_FAST | 7,127,040 | 99.1% |
| TO_BOOL_NONE | 61,440 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 7,127,040 | 99.1% |
| TO_BOOL_NONE | 61,440 | 0.9% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,898,240 | 50.0% |
| COPY | 5,898,240 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 11,796,480 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 5,898,240 | 99.0% |
| TO_BOOL_ALWAYS_TRUE | 61,440 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,898,240 | 99.0% |
| TO_BOOL_ALWAYS_TRUE | 61,440 | 1.0% |


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
| specialization.deferred |      4425120 | 25.0% |
|          hit |     13271400 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 1,120 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 1,080 | 96.4% |
| list slice | 40 | 3.6% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |       122880 | 0.5% |
|          hit |     18432000 | 73.9% |
|         miss |      6512640 | 26.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 122,880 | 100.0% |
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
| specialization.deferred |      5898240 | 55.8% |
|          hit |      4669500 | 44.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 1.4% |
| Failure | 1,440 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 1,440 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     69318240 | 100.0% |


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
| specialization.deferred |      5898800 | 6.2% |
|          hit |     88974580 | 93.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.9% |
| Failure | 1,460 | 96.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 1,460 | 100.0% |


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
| Basic | 339,955,500 | 46.8% |
| Not specialized | 107,046,060 | 14.7% |
| Specialized | 279,963,680 | 38.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 5,898,800 | 36.4% |
| COMPARE_OP | 5,898,240 | 36.4% |
| BINARY_SUBSCR | 4,425,120 | 27.3% |
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
| TO_BOOL_NONE | 3,256,320 | 50.0% |
| TO_BOOL_ALWAYS_TRUE | 3,256,320 | 50.0% |
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
| Allocations | 37,839,500 | 78.6% |
| Allocations to 512 bytes | 37,347,980 | 77.5% |
| Allocations to 4 kbytes | 491,520 | 1.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 43,001,880 |  |
| New values | 0 |  |
| Interpreter increfs | 288,322,120 | 81.2% |
| Interpreter decrefs | 294,950,400 | 73.5% |
| Increfs | 66,614,920 | 18.8% |
| Decrefs | 106,429,580 | 26.5% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 11,797,580 |  |
| Method cache misses | 0 |  |
| Method cache collisions | 0 |  |
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
