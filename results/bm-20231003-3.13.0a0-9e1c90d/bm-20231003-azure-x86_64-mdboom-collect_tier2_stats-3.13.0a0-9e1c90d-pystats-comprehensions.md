
# Pystats results

- benchmark: comprehensions
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 70,537,820 | 14.2% | 14.2% |  |
| ENTER_EXECUTOR | 49,401,580 | 10.0% | 24.2% |  |
| LIST_APPEND | 35,635,860 | 7.2% | 31.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 30,720,660 | 6.2% | 37.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 26,789,280 | 5.4% | 42.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 26,542,080 | 5.3% | 48.3% |  |
| RESUME_CHECK | 18,188,580 | 3.7% | 51.9% |  |
| CALL_PY_EXACT_ARGS | 14,991,600 | 3.0% | 55.0% |  |
| POP_JUMP_IF_FALSE | 12,042,240 | 2.4% | 57.4% |  |
| TO_BOOL_BOOL | 11,796,480 | 2.4% | 59.8% |  |
| POP_JUMP_IF_TRUE | 11,550,780 | 2.3% | 62.1% |  |
| POP_TOP | 10,814,040 | 2.2% | 64.3% |  |
| RETURN_VALUE | 10,569,480 | 2.1% | 66.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 10,567,680 | 2.1% | 68.5% |  |
| LOAD_FAST_LOAD_FAST | 9,106,080 | 1.8% | 70.4% |  |
| LOAD_GLOBAL_BUILTIN | 9,093,300 | 1.8% | 72.2% |  |
| BINARY_SUBSCR_DICT | 9,093,300 | 1.8% | 74.0% |  |
| STORE_FAST | 7,624,760 | 1.5% | 75.6% |  |
| SWAP | 7,619,360 | 1.5% | 77.1% |  |
| INTERPRETER_EXIT | 7,372,980 | 1.5% | 78.6% |  |
| TO_BOOL_ALWAYS_TRUE | 7,178,440 | 1.4% | 80.0% | 38.5% |
| YIELD_VALUE | 7,127,400 | 1.4% | 81.5% |  |
| LOAD_ATTR | 5,900,160 | 1.2% | 82.7% |  |
| LOAD_GLOBAL_MODULE | 5,900,140 | 1.2% | 83.8% |  |
| GET_ITER | 5,899,880 | 1.2% | 85.0% |  |
| COMPARE_OP | 5,899,700 | 1.2% | 86.2% |  |
| FOR_ITER_LIST | 5,898,820 | 1.2% | 87.4% |  |
| COPY | 5,898,240 | 1.2% | 88.6% |  |
| STORE_FAST_LOAD_FAST | 5,407,060 | 1.1% | 89.7% |  |
| LOAD_CONST | 4,919,020 | 1.0% | 90.7% |  |
| CALL_LEN | 4,669,500 | 0.9% | 91.6% |  |
| MAP_ADD | 4,669,440 | 0.9% | 92.6% |  |
| TO_BOOL_NONE | 4,476,560 | 0.9% | 93.5% | 61.7% |
| RETURN_GENERATOR | 4,423,860 | 0.9% | 94.4% |  |
| MAKE_FUNCTION | 4,423,860 | 0.9% | 95.2% |  |
| BUILD_TUPLE | 4,423,860 | 0.9% | 96.1% |  |
| CALL_BUILTIN_O | 4,423,680 | 0.9% | 97.0% |  |
| CALL_INTRINSIC_1 | 4,177,980 | 0.8% | 97.9% |  |
| RERAISE | 4,177,920 | 0.8% | 98.7% |  |
| LOAD_FAST_AND_CLEAR | 1,720,720 | 0.3% | 99.1% |  |
| BUILD_LIST | 1,229,320 | 0.2% | 99.3% |  |
| STORE_ATTR_INSTANCE_VALUE | 745,920 | 0.2% | 99.5% |  |
| RETURN_CONST | 738,900 | 0.1% | 99.6% |  |
| COMPARE_OP_INT | 491,580 | 0.1% | 99.7% |  |
| BUILD_MAP | 491,520 | 0.1% | 99.8% |  |
| EXIT_INIT_CHECK | 247,200 | 0.0% | 99.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 247,200 | 0.0% | 99.9% |  |
| BINARY_SUBSCR | 246,240 | 0.0% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 245,760 | 0.0% | 100.0% |  |
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
| LIST_APPEND ENTER_EXECUTOR | 35,635,860 | 7.2% | 7.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 26,542,080 | 5.3% | 12.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 26,542,080 | 5.3% | 17.9% |
| CALL_METHOD_DESCRIPTOR_FAST LIST_APPEND | 26,542,080 | 5.3% | 23.2% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_NO_DICT | 26,296,320 | 5.3% | 28.5% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 21,626,880 | 4.4% | 32.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 11,796,480 | 2.4% | 35.3% |
| RESUME_CHECK LOAD_FAST | 10,568,040 | 2.1% | 37.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 10,567,740 | 2.1% | 39.5% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 9,830,400 | 2.0% | 41.5% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 8,847,360 | 1.8% | 43.3% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_SUBSCR_DICT | 8,847,360 | 1.8% | 45.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 7,127,100 | 1.4% | 46.5% |
| YIELD_VALUE INTERPRETER_EXIT | 7,127,040 | 1.4% | 47.9% |
| LOAD_ATTR_INSTANCE_VALUE YIELD_VALUE | 7,127,040 | 1.4% | 49.4% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_TRUE | 7,126,300 | 1.4% | 50.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 6,144,000 | 1.2% | 52.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 6,144,000 | 1.2% | 53.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 5,898,300 | 1.2% | 54.5% |
| RETURN_VALUE TO_BOOL_BOOL | 5,898,240 | 1.2% | 55.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 5,898,240 | 1.2% | 56.8% |
| LOAD_ATTR COMPARE_OP | 5,898,240 | 1.2% | 58.0% |
| COPY TO_BOOL_BOOL | 5,898,240 | 1.2% | 59.2% |
| COMPARE_OP COPY | 5,898,240 | 1.2% | 60.4% |
| LOAD_FAST GET_ITER | 5,652,540 | 1.1% | 61.5% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 5,407,060 | 1.1% | 62.6% |
| SWAP STORE_FAST | 4,669,440 | 0.9% | 63.6% |
| MAP_ADD ENTER_EXECUTOR | 4,669,440 | 0.9% | 64.5% |
| ENTER_EXECUTOR SWAP | 4,669,440 | 0.9% | 65.5% |
| TO_BOOL_NONE POP_JUMP_IF_TRUE | 4,424,420 | 0.9% | 66.3% |
| POP_TOP RESUME_CHECK | 4,423,860 | 0.9% | 67.2% |
| LOAD_FAST FOR_ITER_LIST | 4,423,860 | 0.9% | 68.1% |
| LOAD_CONST MAKE_FUNCTION | 4,423,860 | 0.9% | 69.0% |
| GET_ITER CALL_PY_EXACT_ARGS | 4,423,860 | 0.9% | 69.9% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 4,423,740 | 0.9% | 70.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 4,423,720 | 0.9% | 71.7% |
| STORE_FAST MAP_ADD | 4,423,680 | 0.9% | 72.6% |
| RETURN_VALUE LOAD_GLOBAL_BUILTIN | 4,423,680 | 0.9% | 73.5% |
| RETURN_GENERATOR CALL_BUILTIN_O | 4,423,680 | 0.9% | 74.4% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 4,423,680 | 0.9% | 75.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 4,423,680 | 0.9% | 76.1% |
| MAKE_FUNCTION LOAD_FAST | 4,423,680 | 0.9% | 77.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 4,423,680 | 0.9% | 77.9% |
| LOAD_FAST LIST_APPEND | 4,423,680 | 0.9% | 78.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 4,423,680 | 0.9% | 79.7% |
| LOAD_ATTR_INSTANCE_VALUE BUILD_TUPLE | 4,423,680 | 0.9% | 80.6% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 4,423,680 | 0.9% | 81.5% |
| CALL_LEN LOAD_FAST | 4,423,680 | 0.9% | 82.4% |
| CALL_BUILTIN_O RETURN_VALUE | 4,423,680 | 0.9% | 83.3% |
| CACHE POP_TOP | 4,423,680 | 0.9% | 84.2% |
| BUILD_TUPLE LIST_APPEND | 4,423,680 | 0.9% | 85.1% |
| BINARY_SUBSCR_DICT CALL_PY_EXACT_ARGS | 4,423,680 | 0.9% | 86.0% |
| BINARY_SUBSCR_DICT CALL_LEN | 4,423,680 | 0.9% | 86.8% |
| ENTER_EXECUTOR TO_BOOL_ALWAYS_TRUE | 4,363,620 | 0.9% | 87.7% |
| CALL_INTRINSIC_1 RERAISE | 4,177,920 | 0.8% | 88.6% |
| CACHE CALL_INTRINSIC_1 | 4,177,920 | 0.8% | 89.4% |
| POP_TOP LOAD_FAST | 3,194,880 | 0.6% | 90.1% |
| RESUME_CHECK POP_TOP | 2,949,480 | 0.6% | 90.6% |
| POP_TOP ENTER_EXECUTOR | 2,949,480 | 0.6% | 91.2% |
| POP_JUMP_IF_FALSE RETURN_VALUE | 2,949,120 | 0.6% | 91.8% |
| POP_JUMP_IF_FALSE POP_TOP | 2,949,120 | 0.6% | 92.4% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 2,949,120 | 0.6% | 93.0% |
| CACHE RESUME_CHECK | 2,949,120 | 0.6% | 93.6% |
| ENTER_EXECUTOR TO_BOOL_NONE | 2,763,420 | 0.6% | 94.2% |
| STORE_FAST_LOAD_FAST TO_BOOL_ALWAYS_TRUE | 2,762,680 | 0.6% | 94.7% |
| STORE_FAST LOAD_FAST | 1,722,220 | 0.3% | 95.1% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 1,720,320 | 0.3% | 95.4% |
| STORE_FAST_LOAD_FAST TO_BOOL_NONE | 1,661,000 | 0.3% | 95.8% |
| SWAP FOR_ITER_LIST | 1,474,960 | 0.3% | 96.1% |
| LOAD_FAST_AND_CLEAR SWAP | 1,474,960 | 0.3% | 96.4% |
| GET_ITER LOAD_FAST_AND_CLEAR | 1,474,960 | 0.3% | 96.6% |
| STORE_FAST STORE_FAST | 1,230,240 | 0.2% | 96.9% |
| ENTER_EXECUTOR STORE_FAST | 984,420 | 0.2% | 97.1% |
| SWAP BUILD_LIST | 983,440 | 0.2% | 97.3% |
| BUILD_LIST SWAP | 983,440 | 0.2% | 97.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 737,280 | 0.1% | 97.6% |
| FOR_ITER_LIST STORE_FAST | 491,760 | 0.1% | 97.7% |
| SWAP BUILD_MAP | 491,520 | 0.1% | 97.8% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 491,520 | 0.1% | 97.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 491,520 | 0.1% | 98.0% |
| BUILD_MAP SWAP | 491,520 | 0.1% | 98.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 254,400 | 0.1% | 98.2% |
| LOAD_FAST LOAD_CONST | 248,000 | 0.0% | 98.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 247,200 | 0.0% | 98.3% |
| RETURN_CONST EXIT_INIT_CHECK | 247,200 | 0.0% | 98.3% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 247,200 | 0.0% | 98.4% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 247,200 | 0.0% | 98.4% |
| EXIT_INIT_CHECK RETURN_VALUE | 247,200 | 0.0% | 98.5% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 247,200 | 0.0% | 98.5% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 246,100 | 0.0% | 98.6% |
| ENTER_EXECUTOR RETURN_CONST | 245,940 | 0.0% | 98.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 245,880 | 0.0% | 98.7% |
| RETURN_VALUE STORE_FAST | 245,820 | 0.0% | 98.7% |
| CALL_LEN LOAD_CONST | 245,820 | 0.0% | 98.8% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 245,800 | 0.0% | 98.8% |
| LOAD_CONST COMPARE_OP_INT | 245,800 | 0.0% | 98.9% |
| STORE_FAST_LOAD_FAST LOAD_FAST | 245,760 | 0.0% | 98.9% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 245,760 | 0.0% | 99.0% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 245,760 | 0.0% | 99.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 245,760 | 0.0% | 99.1% |


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
| LOAD_FAST | 5,652,540 | 95.8% |
| LOAD_ATTR_INSTANCE_VALUE | 245,760 | 4.2% |
| LOAD_CONST | 760 | 0.0% |
| BINARY_SUBSCR | 400 | 0.0% |
| LOAD_GLOBAL_MODULE | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,423,860 | 75.0% |
| LOAD_FAST_AND_CLEAR | 1,474,960 | 25.0% |
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
| ENTER_EXECUTOR | 2,949,480 | 27.3% |
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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 35,635,860 | 72.1% |
| MAP_ADD | 4,669,440 | 9.5% |
| POP_JUMP_IF_TRUE | 4,423,680 | 9.0% |
| POP_TOP | 2,949,480 | 6.0% |
| POP_JUMP_IF_FALSE | 1,720,320 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 26,296,320 | 53.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 9,830,400 | 19.9% |
| SWAP | 4,669,440 | 9.5% |
| TO_BOOL_ALWAYS_TRUE | 4,363,620 | 8.8% |
| TO_BOOL_NONE | 2,763,420 | 5.6% |


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
| CALL_METHOD_DESCRIPTOR_FAST | 26,542,080 | 74.5% |
| LOAD_FAST | 4,423,680 | 12.4% |
| BUILD_TUPLE | 4,423,680 | 12.4% |
| BINARY_SUBSCR_DICT | 245,760 | 0.7% |
| LOAD_ATTR_INSTANCE_VALUE | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 35,635,860 | 100.0% |


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
| LOAD_ATTR | 1,480 | 0.0% |
| LOAD_DEREF | 360 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 5,898,240 | 100.0% |
| LOAD_ATTR | 1,480 | 0.0% |
| LOAD_FAST | 180 | 0.0% |
| GET_ITER | 180 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,423,740 | 89.9% |
| LOAD_FAST | 248,000 | 5.0% |
| CALL_LEN | 245,820 | 5.0% |
| STORE_FAST | 760 | 0.0% |
| LOAD_CONST | 400 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 4,423,860 | 89.9% |
| COMPARE_OP_INT | 245,800 | 5.0% |
| BINARY_SUBSCR | 245,760 | 5.0% |
| BINARY_OP_ADD_INT | 1,840 | 0.0% |
| GET_ITER | 760 | 0.0% |


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
| LOAD_ATTR_METHOD_NO_DICT | 26,542,080 | 37.6% |
| RESUME_CHECK | 10,568,040 | 15.0% |
| POP_JUMP_IF_TRUE | 7,127,100 | 10.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,144,000 | 8.7% |
| POP_JUMP_IF_FALSE | 4,423,680 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 26,542,080 | 37.6% |
| LOAD_ATTR_INSTANCE_VALUE | 21,626,880 | 30.7% |
| CALL_PY_EXACT_ARGS | 6,144,000 | 8.7% |
| GET_ITER | 5,652,540 | 8.0% |
| FOR_ITER_LIST | 4,423,860 | 6.3% |


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
| TO_BOOL_BOOL | 11,796,480 | 98.0% |
| COMPARE_OP_INT | 245,760 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,423,680 | 36.7% |
| RETURN_VALUE | 2,949,120 | 24.5% |
| POP_TOP | 2,949,120 | 24.5% |
| ENTER_EXECUTOR | 1,720,320 | 14.3% |


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
| LOAD_ATTR_INSTANCE_VALUE | 8,847,360 | 97.3% |
| BINARY_SUBSCR | 245,760 | 2.7% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,423,680 | 48.6% |
| CALL_LEN | 4,423,680 | 48.6% |
| LIST_APPEND | 245,760 | 2.7% |
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
| LOAD_FAST | 21,626,880 | 70.4% |
| LOAD_FAST_LOAD_FAST | 8,847,360 | 28.8% |
| STORE_FAST_LOAD_FAST | 246,100 | 0.8% |
| ENTER_EXECUTOR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 8,847,360 | 28.8% |
| YIELD_VALUE | 7,127,040 | 23.2% |
| LOAD_GLOBAL_MODULE | 5,898,240 | 19.2% |
| BUILD_TUPLE | 4,423,680 | 14.4% |
| RETURN_VALUE | 2,949,120 | 9.6% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 26,296,320 | 98.2% |
| LOAD_FAST | 247,200 | 0.9% |
| STORE_FAST_LOAD_FAST | 245,760 | 0.9% |

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
| ENTER_EXECUTOR | 9,830,400 | 93.0% |
| LOAD_FAST | 491,520 | 4.7% |
| STORE_FAST_LOAD_FAST | 245,760 | 2.3% |

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
| LOAD_ATTR_INSTANCE_VALUE | 5,898,240 | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,440 | 0.0% |
| STORE_FAST | 320 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 5,898,300 | 100.0% |
| LOAD_FAST_LOAD_FAST | 1,440 | 0.0% |
| GET_ITER | 180 | 0.0% |
| LOAD_ATTR_MODULE | 100 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


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
| specialization.deferred |       246160 | 2.6% |
|          hit |      9093300 | 97.4% |

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
|          hit |     17925380 | 76.4% |
|         miss |      5526100 | 23.6% |

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
|          hit |         1900 | 99.0% |

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
| specialization.deferred |      5898240 | 92.3% |
|          hit |       491580 | 7.7% |

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
| specialization.deferred |      5898620 | 8.0% |
|          hit |     68077780 | 92.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.9% |
| Failure | 1,480 | 96.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 1,480 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     14993440 | 100.0% |

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
| Basic | 268,660,400 | 54.1% |
| Not specialized | 41,166,360 | 8.3% |
| Specialized | 186,539,760 | 37.6% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 5,898,620 | 49.0% |
| COMPARE_OP | 5,898,240 | 49.0% |
| BINARY_SUBSCR | 246,160 | 2.0% |
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
| Interpreter increfs | 222,691,380 | 55.1% |
| Interpreter decrefs | 224,164,260 | 49.7% |
| Increfs | 181,647,260 | 44.9% |
| Decrefs | 226,617,320 | 50.3% |
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

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 40 |  |
| Traces created | 20 | 50.0% |
| Traces executed | 49,401,580 |  |
| Uops executed | 735,719,980 | 14 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 20 |  |
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
| <= 64 | 20 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 100.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 5,408,060 | 10.9% |
| <= 16 | 33,669,240 | 68.2% |
| <= 32 | 9,830,460 | 19.9% |
| <= 64 | 1,220 | 0.0% |
| <= 128 | 1,080 | 0.0% |
| <= 256 | 0 | 0.0% |
| <= 512 | 491,520 | 1.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 174,531,960 | 23.7% | 23.7% |
| LOAD_FAST | 78,407,160 | 10.7% | 34.4% |
| _POP_JUMP_IF_TRUE | 64,892,300 | 8.8% | 43.2% |
| _ITER_CHECK_LIST | 63,169,580 | 8.6% | 51.8% |
| _IS_ITER_EXHAUSTED_LIST | 63,169,580 | 8.6% | 60.4% |
| STORE_FAST | 57,516,840 | 7.8% | 68.2% |
| _ITER_NEXT_LIST | 57,269,780 | 7.8% | 76.0% |
| _EXIT_TRACE | 42,274,540 | 5.7% | 81.7% |
| _LOAD_ATTR_INSTANCE_VALUE | 20,896,800 | 2.8% | 84.6% |
| _GUARD_TYPE_VERSION | 20,896,800 | 2.8% | 87.4% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 20,896,800 | 2.8% | 90.2% |
| _JUMP_TO_TOP | 9,836,880 | 1.3% | 91.6% |
| TO_BOOL_NONE | 8,601,600 | 1.2% | 92.7% |
| SWAP | 8,357,920 | 1.1% | 93.9% |
| POP_TOP | 5,900,900 | 0.8% | 94.7% |
| LOAD_CONST | 4,427,060 | 0.6% | 95.3% |
| LIST_APPEND | 4,185,120 | 0.6% | 95.9% |
| GET_ITER | 4,179,280 | 0.6% | 96.4% |
| LOAD_FAST_AND_CLEAR | 4,178,960 | 0.6% | 97.0% |
| BUILD_LIST | 4,178,960 | 0.6% | 97.6% |
| BINARY_SUBSCR | 4,178,960 | 0.6% | 98.1% |
| BINARY_SUBSCR_DICT | 4,178,100 | 0.6% | 98.7% |
| MAP_ADD | 4,177,920 | 0.6% | 99.3% |
| COMPARE_OP_INT | 4,177,920 | 0.6% | 99.8% |
| _ITER_CHECK_RANGE | 245,760 | 0.0% | 99.9% |
| _IS_ITER_EXHAUSTED_RANGE | 245,760 | 0.0% | 99.9% |
| _LOAD_GLOBAL_MODULE | 245,700 | 0.0% | 99.9% |
| _ITER_NEXT_RANGE | 245,700 | 0.0% | 100.0% |
| _GUARD_GLOBALS_VERSION | 245,700 | 0.0% | 100.0% |
| _ITER_CHECK_TUPLE | 2,400 | 0.0% | 100.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 2,400 | 0.0% | 100.0% |
| _ITER_NEXT_TUPLE | 1,360 | 0.0% | 100.0% |
| _GUARD_BOTH_INT | 1,040 | 0.0% | 100.0% |
| _BINARY_OP_ADD_INT | 1,040 | 0.0% | 100.0% |
| BUILD_SLICE | 1,040 | 0.0% | 100.0% |
| LOAD_DEREF | 180 | 0.0% | 100.0% |
| LOAD_ATTR | 180 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| FOR_ITER_GEN | 20 |


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
