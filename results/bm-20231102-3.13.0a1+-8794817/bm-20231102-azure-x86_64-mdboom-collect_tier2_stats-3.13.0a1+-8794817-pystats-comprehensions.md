
# Pystats results

- benchmark: comprehensions
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| ENTER_EXECUTOR | 41,944,960 | 10.9% | 10.9% |  |
| LOAD_FAST | 38,350,320 | 10.0% | 20.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 27,857,160 | 7.3% | 28.2% |  |
| LIST_APPEND | 18,025,020 | 4.7% | 32.9% |  |
| POP_JUMP_IF_FALSE | 16,056,320 | 4.2% | 37.1% |  |
| TO_BOOL_BOOL | 15,728,600 | 4.1% | 41.2% |  |
| POP_JUMP_IF_TRUE | 15,401,140 | 4.0% | 45.2% |  |
| POP_TOP | 14,418,740 | 3.8% | 48.9% |  |
| RETURN_VALUE | 14,092,600 | 3.7% | 52.6% |  |
| BINARY_SUBSCR_DICT | 12,124,900 | 3.2% | 55.8% |  |
| RESUME_CHECK | 11,145,000 | 2.9% | 58.7% |  |
| STORE_FAST | 10,167,680 | 2.7% | 61.3% |  |
| SWAP | 10,162,560 | 2.6% | 64.0% |  |
| INTERPRETER_EXIT | 9,830,700 | 2.6% | 66.5% |  |
| TO_BOOL_ALWAYS_TRUE | 9,571,180 | 2.5% | 69.0% | 38.5% |
| YIELD_VALUE | 9,503,200 | 2.5% | 71.5% |  |
| FOR_ITER_LIST | 7,869,840 | 2.1% | 73.6% |  |
| LOAD_ATTR | 7,868,060 | 2.1% | 75.6% |  |
| COMPARE_OP | 7,866,560 | 2.1% | 77.7% |  |
| COPY | 7,864,320 | 2.0% | 79.7% |  |
| STORE_FAST_LOAD_FAST | 7,213,480 | 1.9% | 81.6% |  |
| LOAD_FAST_LOAD_FAST | 6,571,200 | 1.7% | 83.3% |  |
| LOAD_GLOBAL_BUILTIN | 6,554,040 | 1.7% | 85.0% |  |
| MAP_ADD | 6,226,240 | 1.6% | 86.6% |  |
| CALL_LEN | 6,225,940 | 1.6% | 88.3% |  |
| TO_BOOL_NONE | 5,968,880 | 1.6% | 89.8% | 61.7% |
| BINARY_SUBSCR | 5,902,020 | 1.5% | 91.4% |  |
| RETURN_GENERATOR | 5,898,480 | 1.5% | 92.9% |  |
| BUILD_TUPLE | 5,898,480 | 1.5% | 94.4% |  |
| CALL_BUILTIN_O | 5,898,220 | 1.5% | 96.0% |  |
| GET_ITER | 2,298,080 | 0.6% | 96.6% |  |
| LOAD_FAST_AND_CLEAR | 2,296,000 | 0.6% | 97.2% |  |
| BUILD_LIST | 1,640,800 | 0.4% | 97.6% |  |
| CALL_PY_EXACT_ARGS | 1,312,220 | 0.3% | 97.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 994,380 | 0.3% | 98.2% |  |
| LOAD_CONST | 990,000 | 0.3% | 98.5% |  |
| RETURN_CONST | 985,200 | 0.3% | 98.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 983,940 | 0.3% | 99.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 657,780 | 0.2% | 99.1% |  |
| COMPARE_OP_INT | 655,700 | 0.2% | 99.3% |  |
| BUILD_MAP | 655,360 | 0.2% | 99.5% |  |
| LOAD_GLOBAL_MODULE | 331,040 | 0.1% | 99.6% |  |
| EXIT_INIT_CHECK | 329,560 | 0.1% | 99.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 329,560 | 0.1% | 99.7% |  |
| MAKE_FUNCTION | 328,240 | 0.1% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 328,220 | 0.1% | 99.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 327,660 | 0.1% | 100.0% |  |
| JUMP_BACKWARD | 5,140 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_INT | 2,680 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 1,900 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 1,720 | 0.0% | 100.0% |  |
| CALL | 940 | 0.0% | 100.0% |  |
| BUILD_SLICE | 800 | 0.0% | 100.0% |  |
| LOAD_DEREF | 720 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 700 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 680 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 560 | 0.0% | 100.0% |  |
| FOR_ITER | 520 | 0.0% | 100.0% |  |
| PUSH_NULL | 400 | 0.0% | 100.0% |  |
| STORE_ATTR | 360 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 320 | 0.0% | 100.0% |  |
| END_FOR | 240 | 0.0% | 100.0% |  |
| MAKE_CELL | 240 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 240 | 0.0% | 100.0% |  |
| RESUME | 200 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 180 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| TO_BOOL | 120 | 0.0% | 100.0% |  |
| BINARY_OP | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 21,300,760 | 5.6% | 5.6% |
| LIST_APPEND ENTER_EXECUTOR | 18,023,320 | 4.7% | 10.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 15,728,600 | 4.1% | 14.3% |
| POP_JUMP_IF_TRUE LOAD_FAST | 9,502,800 | 2.5% | 16.8% |
| YIELD_VALUE INTERPRETER_EXIT | 9,502,740 | 2.5% | 19.3% |
| LOAD_ATTR_INSTANCE_VALUE YIELD_VALUE | 9,502,700 | 2.5% | 21.8% |
| TO_BOOL_ALWAYS_TRUE POP_JUMP_IF_TRUE | 9,501,680 | 2.5% | 24.3% |
| LOAD_ATTR COMPARE_OP | 7,864,340 | 2.0% | 26.3% |
| COMPARE_OP COPY | 7,864,320 | 2.0% | 28.4% |
| RETURN_VALUE TO_BOOL_BOOL | 7,864,280 | 2.0% | 30.4% |
| COPY TO_BOOL_BOOL | 7,864,280 | 2.0% | 32.5% |
| ENTER_EXECUTOR LOAD_ATTR | 7,536,240 | 2.0% | 34.4% |
| FOR_ITER_LIST STORE_FAST_LOAD_FAST | 7,213,380 | 1.9% | 36.3% |
| RESUME_CHECK LOAD_FAST | 6,554,660 | 1.7% | 38.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 6,226,160 | 1.6% | 39.6% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_SUBSCR_DICT | 6,226,160 | 1.6% | 41.3% |
| SWAP STORE_FAST | 6,225,920 | 1.6% | 42.9% |
| ENTER_EXECUTOR SWAP | 6,225,840 | 1.6% | 44.5% |
| MAP_ADD ENTER_EXECUTOR | 6,225,560 | 1.6% | 46.1% |
| TO_BOOL_NONE POP_JUMP_IF_TRUE | 5,899,360 | 1.5% | 47.7% |
| POP_TOP RESUME_CHECK | 5,898,460 | 1.5% | 49.2% |
| LOAD_FAST FOR_ITER_LIST | 5,898,460 | 1.5% | 50.7% |
| CACHE POP_TOP | 5,898,260 | 1.5% | 52.3% |
| BINARY_SUBSCR BINARY_SUBSCR_DICT | 5,898,260 | 1.5% | 53.8% |
| BUILD_TUPLE LIST_APPEND | 5,898,240 | 1.5% | 55.3% |
| LOAD_FAST LIST_APPEND | 5,898,240 | 1.5% | 56.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 5,898,240 | 1.5% | 58.4% |
| STORE_FAST MAP_ADD | 5,898,240 | 1.5% | 60.0% |
| BINARY_SUBSCR_DICT LIST_APPEND | 5,898,220 | 1.5% | 61.5% |
| CALL_BUILTIN_O RETURN_VALUE | 5,898,220 | 1.5% | 63.0% |
| CALL_LEN LOAD_FAST | 5,898,220 | 1.5% | 64.6% |
| LOAD_ATTR_INSTANCE_VALUE BUILD_TUPLE | 5,898,220 | 1.5% | 66.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 5,898,220 | 1.5% | 67.6% |
| RETURN_GENERATOR CALL_BUILTIN_O | 5,898,200 | 1.5% | 69.2% |
| RETURN_VALUE LOAD_GLOBAL_BUILTIN | 5,898,200 | 1.5% | 70.7% |
| BINARY_SUBSCR_DICT CALL_LEN | 5,898,200 | 1.5% | 72.3% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 5,898,000 | 1.5% | 73.8% |
| ENTER_EXECUTOR TO_BOOL_ALWAYS_TRUE | 5,818,160 | 1.5% | 75.3% |
| ENTER_EXECUTOR BINARY_SUBSCR | 5,571,360 | 1.5% | 76.8% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 5,570,860 | 1.5% | 78.2% |
| ENTER_EXECUTOR RETURN_GENERATOR | 5,570,240 | 1.5% | 79.7% |
| POP_TOP LOAD_FAST | 4,259,860 | 1.1% | 80.8% |
| RESUME_CHECK POP_TOP | 3,932,620 | 1.0% | 81.8% |
| POP_TOP ENTER_EXECUTOR | 3,932,300 | 1.0% | 82.8% |
| POP_JUMP_IF_FALSE POP_TOP | 3,932,160 | 1.0% | 83.9% |
| POP_JUMP_IF_FALSE RETURN_VALUE | 3,932,160 | 1.0% | 84.9% |
| CACHE RESUME_CHECK | 3,932,140 | 1.0% | 85.9% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 3,932,140 | 1.0% | 86.9% |
| ENTER_EXECUTOR TO_BOOL_NONE | 3,684,040 | 1.0% | 87.9% |
| STORE_FAST_LOAD_FAST TO_BOOL_ALWAYS_TRUE | 3,683,500 | 1.0% | 88.8% |
| STORE_FAST LOAD_FAST | 2,297,200 | 0.6% | 89.4% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 2,293,080 | 0.6% | 90.0% |
| STORE_FAST_LOAD_FAST TO_BOOL_NONE | 2,215,320 | 0.6% | 90.6% |
| GET_ITER LOAD_FAST_AND_CLEAR | 1,968,320 | 0.5% | 91.1% |
| LOAD_FAST_AND_CLEAR SWAP | 1,968,320 | 0.5% | 91.6% |
| SWAP FOR_ITER_LIST | 1,968,160 | 0.5% | 92.2% |
| LOAD_FAST GET_ITER | 1,966,480 | 0.5% | 92.7% |
| STORE_FAST STORE_FAST | 1,640,320 | 0.4% | 93.1% |
| BUILD_LIST SWAP | 1,312,960 | 0.3% | 93.4% |
| SWAP BUILD_LIST | 1,312,960 | 0.3% | 93.8% |
| ENTER_EXECUTOR STORE_FAST | 1,312,460 | 0.3% | 94.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 984,000 | 0.3% | 94.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 983,940 | 0.3% | 94.6% |
| FOR_ITER_LIST STORE_FAST | 656,360 | 0.2% | 94.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 655,960 | 0.2% | 95.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 655,920 | 0.2% | 95.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 655,600 | 0.2% | 95.3% |
| BUILD_MAP SWAP | 655,360 | 0.2% | 95.5% |
| SWAP BUILD_MAP | 655,360 | 0.2% | 95.7% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 655,280 | 0.2% | 95.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 338,920 | 0.1% | 95.9% |
| LOAD_FAST LOAD_CONST | 331,520 | 0.1% | 96.0% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 329,980 | 0.1% | 96.1% |
| EXIT_INIT_CHECK RETURN_VALUE | 329,560 | 0.1% | 96.2% |
| RETURN_CONST EXIT_INIT_CHECK | 329,560 | 0.1% | 96.3% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 329,560 | 0.1% | 96.4% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 329,560 | 0.1% | 96.4% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 329,560 | 0.1% | 96.5% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 329,520 | 0.1% | 96.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 328,360 | 0.1% | 96.7% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 328,280 | 0.1% | 96.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 328,280 | 0.1% | 96.9% |
| LOAD_CONST MAKE_FUNCTION | 328,240 | 0.1% | 97.0% |
| CALL_METHOD_DESCRIPTOR_FAST LIST_APPEND | 328,220 | 0.1% | 97.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 328,220 | 0.1% | 97.1% |
| GET_ITER CALL_PY_EXACT_ARGS | 328,200 | 0.1% | 97.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 328,200 | 0.1% | 97.3% |
| STORE_FAST_LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 328,200 | 0.1% | 97.4% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 328,040 | 0.1% | 97.5% |
| MAKE_FUNCTION LOAD_FAST | 328,000 | 0.1% | 97.6% |
| LOAD_CONST BINARY_SUBSCR | 328,000 | 0.1% | 97.6% |
| LOAD_FAST MAP_ADD | 328,000 | 0.1% | 97.7% |
| STORE_FAST_LOAD_FAST LOAD_FAST | 328,000 | 0.1% | 97.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 328,000 | 0.1% | 97.9% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 327,980 | 0.1% | 98.0% |
| COMPARE_OP_INT LOAD_FAST | 327,980 | 0.1% | 98.1% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 327,980 | 0.1% | 98.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 327,980 | 0.1% | 98.2% |
| BINARY_SUBSCR_DICT CALL_PY_EXACT_ARGS | 327,960 | 0.1% | 98.3% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 327,960 | 0.1% | 98.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,898,260 | 60.0% |
| RESUME_CHECK | 3,932,140 | 40.0% |
| MAKE_CELL | 240 | 0.0% |
| RESUME | 60 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,571,360 | 94.4% |
| LOAD_CONST | 328,000 | 5.6% |
| BINARY_SUBSCR | 1,780 | 0.0% |
| BUILD_SLICE | 800 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 5,898,260 | 99.9% |
| GET_ITER | 1,920 | 0.0% |
| BINARY_SUBSCR | 1,780 | 0.0% |
| CALL | 40 | 0.0% |
| LIST_APPEND | 20 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 329,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 329,560 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,480 | 85.6% |
| LOAD_ATTR_INSTANCE_VALUE | 327,980 | 14.3% |
| BINARY_SUBSCR | 1,920 | 0.1% |
| LOAD_CONST | 1,120 | 0.0% |
| LOAD_ATTR | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 1,968,320 | 85.7% |
| CALL_PY_EXACT_ARGS | 328,200 | 14.3% |
| FOR_ITER_TUPLE | 1,080 | 0.0% |
| FOR_ITER_GEN | 220 | 0.0% |
| FOR_ITER_RANGE | 120 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 9,502,740 | 96.7% |
| RETURN_CONST | 327,720 | 3.3% |
| RETURN_VALUE | 240 | 0.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 328,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 328,000 | 99.9% |
| SET_FUNCTION_ATTRIBUTE | 240 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 5,898,260 | 40.9% |
| RESUME_CHECK | 3,932,620 | 27.3% |
| POP_JUMP_IF_FALSE | 3,932,160 | 27.3% |
| RETURN_CONST | 327,680 | 2.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 327,660 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,898,460 | 40.9% |
| LOAD_FAST | 4,259,860 | 29.5% |
| ENTER_EXECUTOR | 3,932,300 | 27.3% |
| RETURN_CONST | 327,680 | 2.3% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 180 | 45.0% |
| LOAD_DEREF | 160 | 40.0% |
| LOAD_ATTR | 60 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 60.0% |
| LOAD_FAST | 160 | 40.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,570,240 | 94.4% |
| CALL_PY_EXACT_ARGS | 327,980 | 5.6% |
| COPY_FREE_VARS | 240 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 5,898,200 | 100.0% |
| RETURN_VALUE | 240 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 5,898,220 | 41.9% |
| POP_JUMP_IF_FALSE | 3,932,160 | 27.9% |
| LOAD_ATTR_INSTANCE_VALUE | 3,932,140 | 27.9% |
| EXIT_INIT_CHECK | 329,560 | 2.3% |
| RETURN_GENERATOR | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,864,280 | 55.8% |
| LOAD_GLOBAL_BUILTIN | 5,898,200 | 41.9% |
| STORE_FAST | 327,740 | 2.3% |
| CALL_LIST_APPEND | 1,880 | 0.0% |
| INTERPRETER_EXIT | 240 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 33.3% |
| COPY | 40 | 33.3% |
| STORE_FAST_LOAD_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 40 | 33.3% |
| TO_BOOL_BOOL | 40 | 33.3% |
| POP_JUMP_IF_TRUE | 20 | 16.7% |
| TO_BOOL_NONE | 20 | 16.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 66.7% |
| LOAD_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 40 | 33.3% |
| RETURN_VALUE | 20 | 16.7% |
| BUILD_SLICE | 20 | 16.7% |
| STORE_FAST | 20 | 16.7% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 16.7% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,312,960 | 80.0% |
| STORE_ATTR_INSTANCE_VALUE | 327,660 | 20.0% |
| LOAD_FAST | 80 | 0.0% |
| STORE_FAST | 80 | 0.0% |
| STORE_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,312,960 | 80.0% |
| LOAD_FAST | 327,680 | 20.0% |
| LOAD_DEREF | 80 | 0.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 655,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 655,360 | 100.0% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 780 | 97.5% |
| BINARY_OP | 20 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 800 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,898,220 | 100.0% |
| LOAD_FAST | 240 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 5,898,240 | 100.0% |
| LOAD_CONST | 240 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 240 | 25.5% |
| LOAD_FAST | 240 | 25.5% |
| CALL | 80 | 8.5% |
| BINARY_SUBSCR | 40 | 4.3% |
| GET_ITER | 40 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 12.8% |
| STORE_FAST | 120 | 12.8% |
| LOAD_FAST | 100 | 10.6% |
| CALL_PY_EXACT_ARGS | 100 | 10.6% |
| CALL | 80 | 8.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 50.0% |
| LOAD_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 50.0% |
| RESUME_CHECK | 60 | 37.5% |
| RESUME | 20 | 12.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 7,864,340 | 100.0% |
| COMPARE_OP | 2,120 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 7,864,320 | 100.0% |
| COMPARE_OP | 2,120 | 0.0% |
| COMPARE_OP_INT | 60 | 0.0% |
| LOAD_FAST | 20 | 0.0% |
| POP_JUMP_IF_FALSE | 20 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 7,864,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 7,864,280 | 100.0% |
| TO_BOOL | 40 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 240 | 75.0% |
| CALL_FUNCTION_EX | 80 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 240 | 75.0% |
| RESUME_CHECK | 60 | 18.8% |
| RESUME | 20 | 6.2% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 18,023,320 | 43.0% |
| MAP_ADD | 6,225,560 | 14.8% |
| POP_JUMP_IF_TRUE | 5,898,000 | 14.1% |
| ENTER_EXECUTOR | 5,570,860 | 13.3% |
| POP_TOP | 3,932,300 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 7,536,240 | 18.0% |
| SWAP | 6,225,840 | 14.8% |
| TO_BOOL_ALWAYS_TRUE | 5,818,160 | 13.9% |
| BINARY_SUBSCR | 5,571,360 | 13.3% |
| ENTER_EXECUTOR | 5,570,860 | 13.3% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 46.2% |
| SWAP | 160 | 30.8% |
| GET_ITER | 100 | 19.2% |
| LOAD_FAST | 20 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 160 | 30.8% |
| FOR_ITER_LIST | 160 | 30.8% |
| STORE_FAST_LOAD_FAST | 100 | 19.2% |
| FOR_ITER_RANGE | 40 | 7.7% |
| FOR_ITER_TUPLE | 40 | 7.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 1,700 | 33.1% |
| MAP_ADD | 680 | 13.2% |
| POP_JUMP_IF_FALSE | 680 | 13.2% |
| ENTER_EXECUTOR | 500 | 9.7% |
| POP_TOP | 340 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 3,060 | 59.5% |
| FOR_ITER_TUPLE | 600 | 11.7% |
| FOR_ITER_RANGE | 520 | 10.1% |
| FOR_ITER_GEN | 460 | 8.9% |
| ENTER_EXECUTOR | 260 | 5.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 5,898,240 | 32.7% |
| LOAD_FAST | 5,898,240 | 32.7% |
| BINARY_SUBSCR_DICT | 5,898,220 | 32.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 328,220 | 1.8% |
| LOAD_ATTR_INSTANCE_VALUE | 2,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 18,023,320 | 100.0% |
| JUMP_BACKWARD | 1,700 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,536,240 | 95.8% |
| LOAD_GLOBAL_MODULE | 328,360 | 4.2% |
| LOAD_ATTR | 2,140 | 0.0% |
| LOAD_FAST | 520 | 0.0% |
| LOAD_DEREF | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 7,864,340 | 100.0% |
| LOAD_ATTR | 2,140 | 0.0% |
| LOAD_FAST | 600 | 0.0% |
| GET_ITER | 260 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 260 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 331,520 | 33.5% |
| LOAD_GLOBAL_BUILTIN | 328,040 | 33.1% |
| CALL_LEN | 327,720 | 33.1% |
| STORE_FAST | 1,120 | 0.1% |
| LOAD_CONST | 800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 328,240 | 33.2% |
| BINARY_SUBSCR | 328,000 | 33.1% |
| COMPARE_OP_INT | 327,680 | 33.1% |
| BINARY_OP_ADD_INT | 2,640 | 0.3% |
| LOAD_FAST | 1,200 | 0.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 240 | 33.3% |
| STORE_FAST | 240 | 33.3% |
| NOP | 80 | 11.1% |
| BUILD_LIST | 80 | 11.1% |
| RESUME_CHECK | 60 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 480 | 66.7% |
| PUSH_NULL | 160 | 22.2% |
| LIST_EXTEND | 80 | 11.1% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 9,502,800 | 24.8% |
| RESUME_CHECK | 6,554,660 | 17.1% |
| POP_JUMP_IF_FALSE | 5,898,240 | 15.4% |
| CALL_LEN | 5,898,220 | 15.4% |
| POP_TOP | 4,259,860 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 21,300,760 | 55.5% |
| FOR_ITER_LIST | 5,898,460 | 15.4% |
| LIST_APPEND | 5,898,240 | 15.4% |
| GET_ITER | 1,966,480 | 5.1% |
| CALL_PY_EXACT_ARGS | 655,920 | 1.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,968,320 | 85.7% |
| LOAD_FAST_AND_CLEAR | 327,680 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,968,320 | 85.7% |
| LOAD_FAST_AND_CLEAR | 327,680 | 14.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 5,898,220 | 89.8% |
| RESUME_CHECK | 329,560 | 5.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 327,980 | 5.0% |
| STORE_ATTR_INSTANCE_VALUE | 9,500 | 0.1% |
| LOAD_FAST_LOAD_FAST | 3,840 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 6,226,160 | 94.7% |
| STORE_ATTR_INSTANCE_VALUE | 338,920 | 5.2% |
| LOAD_FAST_LOAD_FAST | 3,840 | 0.1% |
| CALL_ALLOC_AND_ENTER_INIT | 1,880 | 0.0% |
| STORE_ATTR | 280 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 42.9% |
| RETURN_VALUE | 80 | 14.3% |
| ENTER_EXECUTOR | 40 | 7.1% |
| LOAD_ATTR | 40 | 7.1% |
| RESUME | 40 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 160 | 28.6% |
| LOAD_GLOBAL_BUILTIN | 120 | 21.4% |
| LOAD_ATTR | 80 | 14.3% |
| LOAD_CONST | 60 | 10.7% |
| LOAD_FAST | 60 | 10.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240 | 100.0% |


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,898,240 | 94.7% |
| LOAD_FAST | 328,000 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,225,560 | 100.0% |
| JUMP_BACKWARD | 680 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 15,728,600 | 98.0% |
| COMPARE_OP_INT | 327,660 | 2.0% |
| TO_BOOL | 40 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,898,240 | 36.7% |
| POP_TOP | 3,932,160 | 24.5% |
| RETURN_VALUE | 3,932,160 | 24.5% |
| ENTER_EXECUTOR | 2,293,080 | 14.3% |
| JUMP_BACKWARD | 680 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 9,501,680 | 61.7% |
| TO_BOOL_NONE | 5,899,360 | 38.3% |
| COMPARE_OP_INT | 60 | 0.0% |
| TO_BOOL | 20 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,502,800 | 61.7% |
| ENTER_EXECUTOR | 5,898,000 | 38.3% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 329,560 | 33.5% |
| ENTER_EXECUTOR | 327,900 | 33.3% |
| POP_TOP | 327,680 | 33.3% |
| STORE_ATTR | 40 | 0.0% |
| FOR_ITER_LIST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXIT_INIT_CHECK | 329,560 | 33.5% |
| INTERPRETER_EXIT | 327,720 | 33.3% |
| POP_TOP | 327,680 | 33.3% |
| END_FOR | 240 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 240 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 280 | 77.8% |
| LOAD_FAST | 80 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 180 | 50.0% |
| LOAD_FAST_LOAD_FAST | 100 | 27.8% |
| RETURN_CONST | 40 | 11.1% |
| BUILD_LIST | 20 | 5.6% |
| LOAD_FAST | 20 | 5.6% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 6,225,920 | 61.2% |
| STORE_FAST | 1,640,320 | 16.1% |
| ENTER_EXECUTOR | 1,312,460 | 12.9% |
| FOR_ITER_LIST | 656,360 | 6.5% |
| RETURN_VALUE | 327,740 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAP_ADD | 5,898,240 | 58.0% |
| LOAD_FAST | 2,297,200 | 22.6% |
| STORE_FAST | 1,640,320 | 16.1% |
| LOAD_GLOBAL_BUILTIN | 327,680 | 3.2% |
| ENTER_EXECUTOR | 1,580 | 0.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 7,213,380 | 100.0% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_ALWAYS_TRUE | 3,683,500 | 51.1% |
| TO_BOOL_NONE | 2,215,320 | 30.7% |
| LOAD_ATTR_INSTANCE_VALUE | 329,980 | 4.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 328,280 | 4.6% |
| LOAD_ATTR_METHOD_NO_DICT | 328,200 | 4.5% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,225,840 | 61.3% |
| LOAD_FAST_AND_CLEAR | 1,968,320 | 19.4% |
| BUILD_LIST | 1,312,960 | 12.9% |
| BUILD_MAP | 655,360 | 6.4% |
| FOR_ITER_LIST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,225,920 | 61.3% |
| FOR_ITER_LIST | 1,968,160 | 19.4% |
| BUILD_LIST | 1,312,960 | 12.9% |
| BUILD_MAP | 655,360 | 6.4% |
| FOR_ITER | 160 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 9,502,700 | 100.0% |
| BINARY_SUBSCR_DICT | 480 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 9,502,740 | 100.0% |
| STORE_FAST | 460 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 40.0% |
| CACHE | 60 | 30.0% |
| POP_TOP | 20 | 10.0% |
| CALL_FUNCTION_EX | 20 | 10.0% |
| COPY_FREE_VARS | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 30.0% |
| LOAD_FAST_LOAD_FAST | 40 | 20.0% |
| LOAD_GLOBAL | 40 | 20.0% |
| POP_TOP | 20 | 10.0% |
| LOAD_CONST | 20 | 10.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,640 | 98.5% |
| BINARY_OP | 40 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,900 | 70.9% |
| BUILD_SLICE | 780 | 29.1% |


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
| LOAD_ATTR_INSTANCE_VALUE | 6,226,160 | 51.4% |
| BINARY_SUBSCR | 5,898,260 | 48.6% |
| LOAD_FAST | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 5,898,220 | 48.6% |
| CALL_LEN | 5,898,200 | 48.6% |
| CALL_PY_EXACT_ARGS | 327,960 | 2.7% |
| YIELD_VALUE | 480 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 327,280 | 99.3% |
| LOAD_FAST_LOAD_FAST | 1,880 | 0.6% |
| LOAD_FAST | 360 | 0.1% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 329,560 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 40 | 33.3% |
| LOAD_CONST | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 5,898,200 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,898,220 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 5,898,200 | 94.7% |
| LOAD_ATTR_INSTANCE_VALUE | 327,640 | 5.3% |
| CALL | 60 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,898,220 | 94.7% |
| LOAD_CONST | 327,720 | 5.3% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,880 | 98.9% |
| CALL | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,900 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 328,200 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 328,220 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 327,640 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 327,660 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 655,920 | 50.0% |
| GET_ITER | 328,200 | 25.0% |
| BINARY_SUBSCR_DICT | 327,960 | 25.0% |
| CALL | 100 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 984,000 | 75.0% |
| RETURN_GENERATOR | 327,980 | 25.0% |
| COPY_FREE_VARS | 240 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 327,960 | 50.0% |
| LOAD_CONST | 327,680 | 50.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 327,980 | 50.0% |
| POP_JUMP_IF_FALSE | 327,660 | 50.0% |
| POP_JUMP_IF_TRUE | 60 | 0.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 460 | 65.7% |
| GET_ITER | 220 | 31.4% |
| FOR_ITER | 20 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 480 | 68.6% |
| POP_TOP | 220 | 31.4% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,898,460 | 75.0% |
| SWAP | 1,968,160 | 25.0% |
| JUMP_BACKWARD | 3,060 | 0.0% |
| FOR_ITER | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 7,213,380 | 91.7% |
| STORE_FAST | 656,360 | 8.3% |
| SWAP | 80 | 0.0% |
| RETURN_CONST | 20 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 520 | 76.5% |
| GET_ITER | 120 | 17.6% |
| FOR_ITER | 40 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600 | 88.2% |
| LOAD_GLOBAL | 40 | 5.9% |
| LOAD_GLOBAL_BUILTIN | 40 | 5.9% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,080 | 62.8% |
| JUMP_BACKWARD | 600 | 34.9% |
| FOR_ITER | 40 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,400 | 81.4% |
| JUMP_BACKWARD | 320 | 18.6% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,300,760 | 76.5% |
| LOAD_FAST_LOAD_FAST | 6,226,160 | 22.4% |
| STORE_FAST_LOAD_FAST | 329,980 | 1.2% |
| LOAD_ATTR | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 9,502,700 | 34.1% |
| BINARY_SUBSCR_DICT | 6,226,160 | 22.4% |
| BUILD_TUPLE | 5,898,220 | 21.2% |
| RETURN_VALUE | 3,932,140 | 14.1% |
| LOAD_FAST | 983,940 | 3.5% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 329,520 | 50.1% |
| STORE_FAST_LOAD_FAST | 328,200 | 49.9% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 328,220 | 49.9% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 327,640 | 49.8% |
| LOAD_GLOBAL_MODULE | 1,880 | 0.3% |
| CALL | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 655,600 | 66.6% |
| STORE_FAST_LOAD_FAST | 328,280 | 33.4% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 655,960 | 66.7% |
| LOAD_FAST_LOAD_FAST | 327,980 | 33.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 66.7% |
| LOAD_ATTR | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,898,200 | 90.0% |
| RESUME_CHECK | 328,000 | 5.0% |
| STORE_FAST | 327,680 | 5.0% |
| LOAD_GLOBAL | 120 | 0.0% |
| FOR_ITER_RANGE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,898,220 | 90.0% |
| LOAD_CONST | 328,040 | 5.0% |
| LOAD_FAST | 327,780 | 5.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 328,280 | 99.2% |
| LOAD_ATTR_METHOD_NO_DICT | 1,880 | 0.6% |
| STORE_FAST | 640 | 0.2% |
| LOAD_GLOBAL | 160 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 328,360 | 99.2% |
| LOAD_FAST_LOAD_FAST | 1,900 | 0.6% |
| LOAD_CONST | 380 | 0.1% |
| GET_ITER | 220 | 0.1% |
| LOAD_ATTR_MODULE | 120 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,898,460 | 52.9% |
| CACHE | 3,932,140 | 35.3% |
| CALL_PY_EXACT_ARGS | 984,000 | 8.8% |
| CALL_ALLOC_AND_ENTER_INIT | 329,560 | 3.0% |
| FOR_ITER_GEN | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,554,660 | 58.8% |
| POP_TOP | 3,932,620 | 35.3% |
| LOAD_FAST_LOAD_FAST | 329,560 | 3.0% |
| LOAD_GLOBAL_BUILTIN | 328,000 | 2.9% |
| LOAD_CONST | 60 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 655,280 | 65.9% |
| LOAD_FAST_LOAD_FAST | 338,920 | 34.1% |
| STORE_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 329,560 | 33.1% |
| BUILD_LIST | 327,660 | 33.0% |
| LOAD_FAST | 327,660 | 33.0% |
| LOAD_FAST_LOAD_FAST | 9,500 | 1.0% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,818,160 | 60.8% |
| STORE_FAST_LOAD_FAST | 3,683,500 | 38.5% |
| TO_BOOL_NONE | 69,520 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 9,501,680 | 99.3% |
| TO_BOOL_NONE | 69,500 | 0.7% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,864,280 | 50.0% |
| COPY | 7,864,280 | 50.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,728,600 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,684,040 | 61.7% |
| STORE_FAST_LOAD_FAST | 2,215,320 | 37.1% |
| TO_BOOL_ALWAYS_TRUE | 69,500 | 1.2% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,899,360 | 98.8% |
| TO_BOOL_ALWAYS_TRUE | 69,520 | 1.2% |


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
|     deferred | 60 | 2.1% |
|          hit | 2,740 | 95.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,900,220 | 32.7% |
|          hit | 12,124,900 | 67.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.3% |
| Failure | 1,740 | 96.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 1,640 | 94.3% |
| list slice | 100 | 5.7% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 560 | 0.0% |
|          hit | 14,423,840 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 320 | 84.2% |
| Failure | 60 | 15.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,864,380 | 92.3% |
|          hit | 655,700 | 7.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 2.8% |
| Failure | 2,120 | 97.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 2,120 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 260 | 0.0% |
|          hit | 7,872,940 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,865,480 | 21.0% |
|          hit | 29,499,060 | 78.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 440 | 17.1% |
| Failure | 2,140 | 82.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 2,140 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 280 | 0.0% |
|          hit | 6,885,080 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


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
|     deferred | 180 | 0.0% |
|          hit | 994,380 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 368,934,881,474,190,893,360 | 1,179,882,558,495,057.5% |
|          hit | 23,900,600 | 76.4% |
|         miss | 7,368,060 | 23.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 139,080 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 215,699,920 | 56.2% |
| Not specialized | 53,096,720 | 13.8% |
| Specialized hits | 107,504,240 | 28.0% |
| Specialized misses | 7,368,060 | 1.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL | 368,934,881,474,190,893,360 | 100.0% |
| LOAD_ATTR | 7,865,480 | 0.0% |
| COMPARE_OP | 7,864,380 | 0.0% |
| BINARY_SUBSCR | 5,900,220 | 0.0% |
| CALL | 560 | 0.0% |
| LOAD_GLOBAL | 280 | 0.0% |
| FOR_ITER | 260 | 0.0% |
| STORE_ATTR | 180 | 0.0% |
| BINARY_OP | 60 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_NONE | 3,684,560 | 50.0% |
| TO_BOOL_ALWAYS_TRUE | 3,683,500 | 50.0% |
| CACHE | 0 | 0.0% |
| END_FOR | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| MAKE_FUNCTION | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 9,830,700 | 85.7% |
| Calls to Python functions inlined | 1,642,740 | 14.3% |
| Calls via PyEval_EvalFrame (total) | 9,830,700 | 85.7% |
| Calls via PyEval_EvalFrame (vector) | 280 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 9,830,420 | 85.7% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 280 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 20,647,820 | 180.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 13,766,160 | 32.8% |
| Frees to freelist | 13,767,020 |  |
| Allocations | 28,171,620 | 67.2% |
| Allocations to 512 bytes | 27,516,160 | 65.6% |
| Allocations to 4 kbytes | 655,460 | 1.6% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 35,053,636 |  |
| New values | 40 |  |
| Interpreter increfs | 404,091,900 | 83.9% |
| Interpreter decrefs | 429,641,740 | 82.4% |
| Increfs | 77,680,148 | 16.1% |
| Decrefs | 91,772,067 | 17.6% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 15,730,964 |  |
| Method cache misses | 296 |  |
| Method cache collisions | 283 |  |
| Method cache dunder hits | 272 |  |
| Method cache dunder misses | 48 |  |


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
| Optimization attempts | 280 |  |
| Traces created | 260 | 92.9% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 20 | 7.1% |
| Inner loop found | 20 | 7.1% |
| Recursive call | 0 | 0.0% |
| Traces executed | 41,944,960 |  |
| Uops executed | 1,618,508,540 | 38.59 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 160 | 61.5% |
| <= 64 | 80 | 30.8% |
| <= 128 | 20 | 7.7% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 40 | 15.4% |
| <= 32 | 120 | 46.2% |
| <= 64 | 100 | 38.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,967,540 | 4.7% |
| <= 16 | 13,433,980 | 32.0% |
| <= 32 | 9,503,180 | 22.7% |
| <= 64 | 11,796,020 | 28.1% |
| <= 128 | 4,916,580 | 11.7% |
| <= 256 | 0 | 0.0% |
| <= 512 | 327,660 | 0.8% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 408,972,500 | 25.3% | 25.3% |  |
| LOAD_FAST | 171,379,400 | 10.6% | 35.9% |  |
| _GUARD_TYPE_VERSION | 89,133,300 | 5.5% | 41.4% |  |
| _POP_JUMP_IF_TRUE | 86,517,100 | 5.3% | 46.7% |  |
| _ITER_CHECK_LIST | 84,221,200 | 5.2% | 51.9% |  |
| _IS_ITER_EXHAUSTED_LIST | 84,221,200 | 5.2% | 57.1% |  |
| STORE_FAST | 76,683,720 | 4.7% | 61.9% |  |
| _ITER_NEXT_LIST | 76,355,000 | 4.7% | 66.6% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 40,965,860 | 2.5% | 69.1% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 40,965,860 | 2.5% | 71.6% |  |
| _JUMP_TO_TOP | 37,035,600 | 2.3% | 73.9% |  |
| LIST_APPEND | 35,069,620 | 2.2% | 76.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 35,061,200 | 2.2% | 78.3% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 35,061,200 | 2.2% | 80.4% |  |
| _EXIT_TRACE | 32,442,760 | 2.0% | 82.4% |  |
| _CHECK_PEP_523 | 18,676,480 | 1.2% | 83.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 18,676,480 | 1.2% | 84.7% |  |
| _CHECK_STACK_SPACE | 18,676,480 | 1.2% | 85.9% |  |
| _INIT_CALL_PY_EXACT_ARGS | 18,676,480 | 1.2% | 87.0% |  |
| _PUSH_FRAME | 18,676,480 | 1.2% | 88.2% |  |
| _SAVE_RETURN_OFFSET | 18,676,480 | 1.2% | 89.4% |  |
| _GUARD_GLOBALS_VERSION | 13,433,520 | 0.8% | 90.2% |  |
| RESUME_CHECK | 13,106,240 | 0.8% | 91.0% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 13,106,240 | 0.8% | 91.8% |  |
| _GUARD_KEYS_VERSION | 13,106,240 | 0.8% | 92.6% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 13,106,240 | 0.8% | 93.4% |  |
| LOAD_CONST | 11,471,440 | 0.7% | 94.1% |  |
| TO_BOOL_NONE | 11,468,180 | 0.7% | 94.8% | 82.9% |
| GET_ITER | 11,140,800 | 0.7% | 95.5% |  |
| SWAP | 11,140,480 | 0.7% | 96.2% |  |
| POP_TOP | 7,867,400 | 0.5% | 96.7% |  |
| _LOAD_GLOBAL_MODULE | 7,863,280 | 0.5% | 97.2% |  |
| MAKE_FUNCTION | 5,570,240 | 0.3% | 97.5% |  |
| BUILD_LIST | 5,570,240 | 0.3% | 97.9% |  |
| LOAD_FAST_AND_CLEAR | 5,570,240 | 0.3% | 98.2% |  |
| MAP_ADD | 5,570,240 | 0.3% | 98.6% |  |
| BINARY_SUBSCR_DICT | 5,570,240 | 0.3% | 98.9% |  |
| COMPARE_OP_INT | 5,570,240 | 0.3% | 99.3% |  |
| _GUARD_BUILTINS_VERSION | 5,570,240 | 0.3% | 99.6% |  |
| _LOAD_GLOBAL_BUILTINS | 5,570,240 | 0.3% | 99.9% |  |
| _ITER_CHECK_RANGE | 327,360 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_RANGE | 327,360 | 0.0% | 100.0% |  |
| _ITER_NEXT_RANGE | 327,280 | 0.0% | 100.0% |  |
| _ITER_CHECK_TUPLE | 2,560 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 2,560 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 1,440 | 0.0% | 100.0% |  |
| BUILD_SLICE | 1,120 | 0.0% | 100.0% |  |
| _GUARD_BOTH_INT | 1,120 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_INT | 1,120 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| BINARY_SUBSCR | 60 |
| LOAD_ATTR | 40 |
| YIELD_VALUE | 20 |
| CALL_ALLOC_AND_ENTER_INIT | 20 |
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
Stats gathered on: 2023-11-03