
# Pystats results

- benchmark: deltablue
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 267,279,900 | 19.7% | 19.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 200,932,240 | 14.8% | 34.5% | 1.5% |
| RESUME_CHECK | 98,728,380 | 7.3% | 41.8% | 0.0% |
| CALL_PY_EXACT_ARGS | 92,376,480 | 6.8% | 48.6% | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 91,040,480 | 6.7% | 55.4% | 5.5% |
| LOAD_GLOBAL_MODULE | 70,471,780 | 5.2% | 60.6% |  |
| POP_JUMP_IF_FALSE | 69,847,740 | 5.2% | 65.7% |  |
| COMPARE_OP_INT | 65,477,820 | 4.8% | 70.5% |  |
| RETURN_VALUE | 61,395,900 | 4.5% | 75.1% |  |
| LOAD_ATTR_CLASS | 59,059,200 | 4.4% | 79.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 41,318,260 | 3.0% | 82.5% | 3.4% |
| POP_TOP | 39,826,620 | 2.9% | 85.4% |  |
| RETURN_CONST | 38,321,280 | 2.8% | 88.2% |  |
| ENTER_EXECUTOR | 30,036,480 | 2.2% | 90.5% |  |
| STORE_FAST | 18,756,840 | 1.4% | 91.8% |  |
| TO_BOOL_BOOL | 13,651,200 | 1.0% | 92.8% |  |
| LOAD_FAST_LOAD_FAST | 12,848,640 | 0.9% | 93.8% |  |
| LOAD_ATTR | 11,959,740 | 0.9% | 94.7% |  |
| POP_JUMP_IF_TRUE | 7,240,320 | 0.5% | 95.2% |  |
| LOAD_GLOBAL_BUILTIN | 5,904,060 | 0.4% | 95.6% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,216,640 | 0.4% | 96.0% |  |
| BINARY_OP_ADD_INT | 4,997,760 | 0.4% | 96.4% |  |
| CALL_LIST_APPEND | 4,498,560 | 0.3% | 96.7% |  |
| LOAD_CONST | 4,444,860 | 0.3% | 97.1% |  |
| BINARY_OP_MULTIPLY_INT | 4,398,720 | 0.3% | 97.4% |  |
| COPY | 3,492,480 | 0.3% | 97.6% |  |
| TO_BOOL_INT | 3,335,040 | 0.2% | 97.9% |  |
| CALL_LEN | 3,335,040 | 0.2% | 98.1% |  |
| GET_ITER | 3,043,260 | 0.2% | 98.4% |  |
| FOR_ITER_LIST | 3,025,920 | 0.2% | 98.6% |  |
| CALL | 2,981,220 | 0.2% | 98.8% |  |
| COPY_FREE_VARS | 2,551,740 | 0.2% | 99.0% |  |
| LOAD_SUPER_ATTR_METHOD | 2,551,680 | 0.2% | 99.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,389,420 | 0.2% | 99.4% | 100.0% |
| COMPARE_OP | 2,373,920 | 0.2% | 99.5% |  |
| POP_JUMP_IF_NONE | 2,152,320 | 0.2% | 99.7% |  |
| EXIT_INIT_CHECK | 988,800 | 0.1% | 99.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 988,800 | 0.1% | 99.8% |  |
| SWAP | 597,120 | 0.0% | 99.9% |  |
| JUMP_FORWARD | 385,920 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 382,080 | 0.0% | 99.9% |  |
| BINARY_OP | 259,400 | 0.0% | 100.0% |  |
| UNARY_NOT | 203,520 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 195,840 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 67,200 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 46,080 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 17,340 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 17,340 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 7,820 | 0.0% | 100.0% | 100.0% |
| BUILD_CONST_KEY_MAP | 7,680 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 7,680 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 3,920 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 3,840 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 1,920 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 1,920 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 1,920 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| LOAD_DEREF | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 80 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 157,996,800 | 11.7% | 11.7% |
| RESUME_CHECK LOAD_FAST | 93,116,160 | 6.9% | 18.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 90,958,080 | 6.7% | 25.2% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 81,932,160 | 6.0% | 31.3% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 62,799,360 | 4.6% | 35.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 60,898,560 | 4.5% | 40.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_CLASS | 59,059,200 | 4.4% | 44.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 57,744,060 | 4.3% | 49.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 56,561,280 | 4.2% | 53.2% |
| LOAD_ATTR_CLASS COMPARE_OP_INT | 56,557,440 | 4.2% | 57.4% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 50,317,440 | 3.7% | 61.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 37,812,480 | 2.8% | 63.9% |
| RETURN_CONST POP_TOP | 35,936,640 | 2.7% | 66.5% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 28,166,400 | 2.1% | 68.6% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 23,846,400 | 1.8% | 70.4% |
| POP_TOP ENTER_EXECUTOR | 23,617,920 | 1.7% | 72.1% |
| RETURN_VALUE LOAD_ATTR_INSTANCE_VALUE | 21,532,800 | 1.6% | 73.7% |
| RETURN_VALUE STORE_ATTR_INSTANCE_VALUE | 20,943,360 | 1.5% | 75.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 20,404,240 | 1.5% | 76.7% |
| STORE_FAST LOAD_FAST | 14,375,340 | 1.1% | 77.8% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 9,175,680 | 0.7% | 78.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 9,018,240 | 0.7% | 79.1% |
| LOAD_ATTR LOAD_FAST | 8,807,040 | 0.6% | 79.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 8,747,520 | 0.6% | 80.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 8,040,960 | 0.6% | 81.0% |
| RETURN_VALUE TO_BOOL_BOOL | 7,797,120 | 0.6% | 81.6% |
| POP_TOP LOAD_FAST | 6,994,560 | 0.5% | 82.1% |
| COMPARE_OP_INT RETURN_VALUE | 6,958,080 | 0.5% | 82.6% |
| RETURN_VALUE STORE_FAST | 6,650,880 | 0.5% | 83.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 6,510,720 | 0.5% | 83.6% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 5,266,560 | 0.4% | 84.0% |
| LOAD_ATTR_INSTANCE_VALUE STORE_ATTR_INSTANCE_VALUE | 5,253,120 | 0.4% | 84.4% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 5,216,640 | 0.4% | 84.8% |
| LOAD_FAST LOAD_ATTR | 5,088,000 | 0.4% | 85.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 5,063,040 | 0.4% | 85.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 4,869,160 | 0.4% | 85.9% |
| LOAD_FAST COMPARE_OP_INT | 4,853,760 | 0.4% | 86.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 4,700,160 | 0.3% | 86.6% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 4,394,880 | 0.3% | 86.9% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_ADD_INT | 4,394,880 | 0.3% | 87.2% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 4,394,880 | 0.3% | 87.6% |
| BINARY_OP_ADD_INT LOAD_FAST | 4,394,880 | 0.3% | 87.9% |
| LOAD_FAST CALL_LIST_APPEND | 4,110,720 | 0.3% | 88.2% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 3,672,960 | 0.3% | 88.5% |
| LOAD_ATTR_INSTANCE_VALUE CALL_BOUND_METHOD_EXACT_ARGS | 3,672,960 | 0.3% | 88.7% |
| RETURN_VALUE LOAD_FAST | 3,492,480 | 0.3% | 89.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,342,780 | 0.2% | 89.2% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,335,040 | 0.2% | 89.5% |
| LOAD_FAST CALL_LEN | 3,335,040 | 0.2% | 89.7% |
| CALL_LEN TO_BOOL_INT | 3,335,040 | 0.2% | 90.0% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 3,102,720 | 0.2% | 90.2% |
| GET_ITER FOR_ITER_LIST | 3,025,920 | 0.2% | 90.4% |
| FOR_ITER_LIST STORE_FAST | 3,025,920 | 0.2% | 90.6% |
| POP_TOP RETURN_CONST | 2,937,600 | 0.2% | 90.9% |
| POP_TOP LOAD_FAST_LOAD_FAST | 2,929,920 | 0.2% | 91.1% |
| COPY TO_BOOL_BOOL | 2,895,360 | 0.2% | 91.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,768,640 | 0.2% | 91.5% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 2,716,800 | 0.2% | 91.7% |
| LOAD_CONST LOAD_FAST | 2,601,600 | 0.2% | 91.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 2,586,240 | 0.2% | 92.1% |
| COPY_FREE_VARS RESUME_CHECK | 2,551,740 | 0.2% | 92.3% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 2,551,680 | 0.2% | 92.5% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 2,551,680 | 0.2% | 92.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 2,536,320 | 0.2% | 92.8% |
| LOAD_FAST RETURN_VALUE | 2,534,460 | 0.2% | 93.0% |
| LOAD_ATTR_CLASS LOAD_FAST | 2,501,760 | 0.2% | 93.2% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 2,367,360 | 0.2% | 93.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,359,680 | 0.2% | 93.5% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 2,344,320 | 0.2% | 93.7% |
| COMPARE_OP POP_JUMP_IF_TRUE | 2,344,320 | 0.2% | 93.9% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 2,344,320 | 0.2% | 94.1% |
| LOAD_ATTR_INSTANCE_VALUE COPY | 2,315,520 | 0.2% | 94.2% |
| ENTER_EXECUTOR RETURN_CONST | 2,221,440 | 0.2% | 94.4% |
| LOAD_FAST POP_JUMP_IF_NONE | 2,144,640 | 0.2% | 94.6% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 2,129,280 | 0.2% | 94.7% |
| LOAD_FAST GET_ITER | 1,966,140 | 0.1% | 94.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,956,480 | 0.1% | 95.0% |
| POP_TOP LOAD_GLOBAL_BUILTIN | 1,952,640 | 0.1% | 95.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,952,640 | 0.1% | 95.3% |
| CALL_LIST_APPEND RETURN_CONST | 1,944,960 | 0.1% | 95.4% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,777,920 | 0.1% | 95.6% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,747,200 | 0.1% | 95.7% |
| POP_JUMP_IF_FALSE POP_TOP | 1,735,680 | 0.1% | 95.8% |
| LOAD_GLOBAL_MODULE CALL | 1,601,280 | 0.1% | 95.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_WITH_VALUES | 1,578,240 | 0.1% | 96.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,574,440 | 0.1% | 96.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,574,400 | 0.1% | 96.3% |
| ENTER_EXECUTOR LOAD_FAST | 1,570,620 | 0.1% | 96.4% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 1,543,680 | 0.1% | 96.5% |
| LOAD_FAST_LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 1,543,680 | 0.1% | 96.6% |
| LOAD_ATTR LOAD_FAST_LOAD_FAST | 1,543,680 | 0.1% | 96.8% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 1,370,880 | 0.1% | 96.9% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 1,368,960 | 0.1% | 97.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,363,200 | 0.1% | 97.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,359,360 | 0.1% | 97.2% |
| ENTER_EXECUTOR CALL_METHOD_DESCRIPTOR_FAST | 1,353,600 | 0.1% | 97.3% |
| CALL STORE_FAST | 1,203,900 | 0.1% | 97.3% |
| RETURN_CONST TO_BOOL_BOOL | 1,196,160 | 0.1% | 97.4% |
| CALL POP_TOP | 1,184,700 | 0.1% | 97.5% |
| LOAD_SUPER_ATTR_METHOD CALL | 1,182,720 | 0.1% | 97.6% |


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
| COPY_FREE_VARS | 193,920 | 99.0% |
| RESUME_CHECK | 1,920 | 1.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,840 | 98.0% |
| BINARY_SUBSCR | 80 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,840 | 98.0% |
| BINARY_SUBSCR | 80 | 2.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 988,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 988,800 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,140 | 64.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,059,840 | 34.8% |
| CALL_BUILTIN_CLASS | 17,280 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 3,025,920 | 99.4% |
| FOR_ITER_RANGE | 17,340 | 0.6% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 195,840 | 100.0% |

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
| RETURN_CONST | 35,936,640 | 90.2% |
| POP_JUMP_IF_FALSE | 1,735,680 | 4.4% |
| CALL | 1,184,700 | 3.0% |
| RETURN_VALUE | 577,920 | 1.5% |
| POP_JUMP_IF_TRUE | 384,000 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 23,617,920 | 59.3% |
| LOAD_FAST | 6,994,560 | 17.6% |
| RETURN_CONST | 2,937,600 | 7.4% |
| LOAD_FAST_LOAD_FAST | 2,929,920 | 7.4% |
| LOAD_GLOBAL_BUILTIN | 1,952,640 | 4.9% |


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
| LOAD_ATTR_INSTANCE_VALUE | 50,317,440 | 82.0% |
| COMPARE_OP_INT | 6,958,080 | 11.3% |
| LOAD_FAST | 2,534,460 | 4.1% |
| EXIT_INIT_CHECK | 988,800 | 1.6% |
| POP_JUMP_IF_TRUE | 579,840 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 21,532,800 | 35.1% |
| STORE_ATTR_INSTANCE_VALUE | 20,943,360 | 34.1% |
| TO_BOOL_BOOL | 7,797,120 | 12.7% |
| STORE_FAST | 6,650,880 | 10.8% |
| LOAD_FAST | 3,492,480 | 5.7% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 203,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 203,520 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 195,860 | 75.5% |
| LOAD_ATTR_INSTANCE_VALUE | 63,360 | 24.4% |
| BINARY_OP | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 257,280 | 99.2% |
| STORE_FAST | 1,920 | 0.7% |
| BINARY_OP | 180 | 0.1% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,680 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,601,280 | 53.7% |
| LOAD_SUPER_ATTR_METHOD | 1,182,720 | 39.7% |
| ENTER_EXECUTOR | 193,860 | 6.5% |
| LOAD_FAST | 1,940 | 0.1% |
| CALL | 1,180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,203,900 | 40.4% |
| POP_TOP | 1,184,700 | 39.7% |
| LOAD_FAST | 591,420 | 19.8% |
| CALL | 1,180 | 0.0% |
| CALL_BUILTIN_CLASS | 20 | 0.0% |


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
| LOAD_FAST_LOAD_FAST | 2,344,320 | 98.8% |
| LOAD_FAST | 15,360 | 0.6% |
| LOAD_ATTR | 11,520 | 0.5% |
| LOAD_CONST | 1,940 | 0.1% |
| COMPARE_OP | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,344,320 | 98.8% |
| POP_JUMP_IF_FALSE | 21,120 | 0.9% |
| STORE_FAST | 7,680 | 0.3% |
| COMPARE_OP | 780 | 0.0% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,315,520 | 66.3% |
| LOAD_FAST | 597,120 | 17.1% |
| COMPARE_OP_INT | 579,840 | 16.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,895,360 | 82.9% |
| LOAD_ATTR_INSTANCE_VALUE | 597,120 | 17.1% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,368,960 | 53.6% |
| CALL_ALLOC_AND_ENTER_INIT | 988,800 | 38.8% |
| CACHE | 193,920 | 7.6% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,551,740 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 23,617,920 | 78.6% |
| POP_JUMP_IF_TRUE | 2,716,800 | 9.0% |
| POP_JUMP_IF_FALSE | 2,129,280 | 7.1% |
| CALL_LIST_APPEND | 1,370,880 | 4.6% |
| STORE_FAST | 201,600 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 23,846,400 | 79.4% |
| RETURN_CONST | 2,221,440 | 7.4% |
| LOAD_FAST | 1,570,620 | 5.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,353,600 | 4.5% |
| LOAD_GLOBAL_BUILTIN | 395,520 | 1.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 382,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 382,080 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 385,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 193,920 | 50.2% |
| LOAD_FAST | 192,000 | 49.8% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,088,000 | 42.5% |
| LOAD_GLOBAL_MODULE | 4,869,160 | 40.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,952,640 | 16.3% |
| LOAD_ATTR_SLOT | 46,080 | 0.4% |
| LOAD_ATTR | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,807,040 | 73.6% |
| LOAD_FAST_LOAD_FAST | 1,543,680 | 12.9% |
| LOAD_CONST | 998,400 | 8.3% |
| CALL_ALLOC_AND_ENTER_INIT | 587,520 | 4.9% |
| COMPARE_OP | 11,520 | 0.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,956,480 | 44.0% |
| LOAD_ATTR | 998,400 | 22.5% |
| LOAD_ATTR_INSTANCE_VALUE | 600,960 | 13.5% |
| POP_TOP | 215,040 | 4.8% |
| POP_JUMP_IF_FALSE | 215,040 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,601,600 | 58.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 990,720 | 22.3% |
| BINARY_OP_ADD_INT | 602,880 | 13.6% |
| COMPARE_OP_INT | 195,880 | 4.4% |
| STORE_FAST | 9,600 | 0.2% |


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
| RESUME_CHECK | 93,116,160 | 34.8% |
| POP_JUMP_IF_FALSE | 60,898,560 | 22.8% |
| LOAD_ATTR_INSTANCE_VALUE | 37,812,480 | 14.1% |
| STORE_FAST | 14,375,340 | 5.4% |
| LOAD_ATTR | 8,807,040 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 157,996,800 | 59.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 62,799,360 | 23.5% |
| STORE_ATTR_INSTANCE_VALUE | 9,175,680 | 3.4% |
| CALL_PY_EXACT_ARGS | 9,018,240 | 3.4% |
| LOAD_ATTR | 5,088,000 | 1.9% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,920 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,929,920 | 22.8% |
| STORE_FAST | 2,367,360 | 18.4% |
| STORE_ATTR_INSTANCE_VALUE | 1,543,680 | 12.0% |
| LOAD_ATTR | 1,543,680 | 12.0% |
| POP_JUMP_IF_TRUE | 973,440 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,063,040 | 39.4% |
| COMPARE_OP | 2,344,320 | 18.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,543,680 | 12.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,359,360 | 10.6% |
| CALL_PY_EXACT_ARGS | 1,176,960 | 9.2% |


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
| COMPARE_OP_INT | 57,744,060 | 82.7% |
| TO_BOOL_BOOL | 8,747,520 | 12.5% |
| TO_BOOL_INT | 3,335,040 | 4.8% |
| COMPARE_OP | 21,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,898,560 | 87.2% |
| LOAD_GLOBAL_MODULE | 3,102,720 | 4.4% |
| ENTER_EXECUTOR | 2,129,280 | 3.0% |
| POP_TOP | 1,735,680 | 2.5% |
| RETURN_CONST | 1,574,400 | 2.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,144,640 | 99.6% |
| LOAD_ATTR_INSTANCE_VALUE | 7,680 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 587,520 | 27.3% |
| LOAD_FAST_LOAD_FAST | 583,680 | 27.1% |
| LOAD_FAST | 407,040 | 18.9% |
| JUMP_BACKWARD | 382,080 | 17.8% |
| LOAD_GLOBAL_MODULE | 192,000 | 8.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,700,160 | 64.9% |
| COMPARE_OP | 2,344,320 | 32.4% |
| COMPARE_OP_INT | 195,840 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,716,800 | 37.5% |
| LOAD_FAST | 2,586,240 | 35.7% |
| LOAD_FAST_LOAD_FAST | 973,440 | 13.4% |
| RETURN_VALUE | 579,840 | 8.0% |
| POP_TOP | 384,000 | 5.3% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 28,166,400 | 73.5% |
| POP_TOP | 2,937,600 | 7.7% |
| ENTER_EXECUTOR | 2,221,440 | 5.8% |
| CALL_LIST_APPEND | 1,944,960 | 5.1% |
| POP_JUMP_IF_FALSE | 1,574,400 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 35,936,640 | 93.8% |
| TO_BOOL_BOOL | 1,196,160 | 3.1% |
| EXIT_INIT_CHECK | 988,800 | 2.6% |
| INTERPRETER_EXIT | 195,840 | 0.5% |
| STORE_FAST | 3,840 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,650,880 | 35.5% |
| LOAD_ATTR_INSTANCE_VALUE | 5,266,560 | 28.1% |
| FOR_ITER_LIST | 3,025,920 | 16.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,344,320 | 12.5% |
| CALL | 1,203,900 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,375,340 | 76.6% |
| LOAD_FAST_LOAD_FAST | 2,367,360 | 12.6% |
| LOAD_GLOBAL_MODULE | 1,777,920 | 9.5% |
| ENTER_EXECUTOR | 201,600 | 1.1% |
| LOAD_GLOBAL_BUILTIN | 23,040 | 0.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920 | 100.0% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,920 | 50.0% |
| LOAD_CONST | 1,920 | 50.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 597,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 597,120 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,394,880 | 87.9% |
| LOAD_CONST | 602,880 | 12.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,394,880 | 87.9% |
| SWAP | 597,120 | 11.9% |
| COMPARE_OP_INT | 3,840 | 0.1% |
| CALL_BUILTIN_CLASS | 1,920 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,394,880 | 99.9% |
| LOAD_CONST | 3,840 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,394,880 | 99.9% |
| LOAD_CONST | 3,840 | 0.1% |


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
| LOAD_ATTR_INSTANCE_VALUE | 63,360 | 94.3% |
| LOAD_CONST | 3,840 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 63,360 | 94.3% |
| CALL_BUILTIN_CLASS | 3,840 | 5.7% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,680 | 100.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 587,520 | 59.4% |
| LOAD_FAST | 193,920 | 19.6% |
| ENTER_EXECUTOR | 190,080 | 19.2% |
| LOAD_GLOBAL_MODULE | 13,440 | 1.4% |
| LOAD_CONST | 3,840 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 988,800 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,672,960 | 70.4% |
| LOAD_FAST_LOAD_FAST | 1,543,680 | 29.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,216,640 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,600 | 55.4% |
| BINARY_OP_SUBTRACT_INT | 3,840 | 22.1% |
| LOAD_FAST | 1,960 | 11.3% |
| BINARY_OP_ADD_INT | 1,920 | 11.1% |
| CALL | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 17,280 | 99.7% |
| STORE_FAST | 60 | 0.3% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,335,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 3,335,040 | 100.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,110,720 | 91.4% |
| RETURN_VALUE | 387,840 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,944,960 | 43.2% |
| ENTER_EXECUTOR | 1,370,880 | 30.5% |
| LOAD_GLOBAL_BUILTIN | 981,120 | 21.8% |
| LOAD_GLOBAL_MODULE | 201,600 | 4.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,353,600 | 56.6% |
| LOAD_CONST | 990,720 | 41.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 45,100 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,344,320 | 98.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 45,100 | 1.9% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,680 | 98.2% |
| CALL_METHOD_DESCRIPTOR_O | 140 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 7,680 | 98.2% |
| CALL_METHOD_DESCRIPTOR_O | 140 | 1.8% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 81,932,160 | 88.7% |
| LOAD_FAST | 9,018,240 | 9.8% |
| LOAD_FAST_LOAD_FAST | 1,176,960 | 1.3% |
| LOAD_SUPER_ATTR_METHOD | 192,000 | 0.2% |
| CALL_PY_EXACT_ARGS | 49,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 90,958,080 | 98.5% |
| COPY_FREE_VARS | 1,368,960 | 1.5% |
| CALL_PY_EXACT_ARGS | 49,440 | 0.1% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 56,557,440 | 86.4% |
| LOAD_FAST | 4,853,760 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 3,672,960 | 5.6% |
| LOAD_CONST | 195,880 | 0.3% |
| LOAD_FAST_LOAD_FAST | 193,920 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,744,060 | 88.2% |
| RETURN_VALUE | 6,958,080 | 10.6% |
| COPY | 579,840 | 0.9% |
| POP_JUMP_IF_TRUE | 195,840 | 0.3% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,025,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,025,920 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 17,340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 17,340 | 100.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 59,059,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 56,557,440 | 95.8% |
| LOAD_FAST | 2,501,760 | 4.2% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 157,996,800 | 78.6% |
| RETURN_VALUE | 21,532,800 | 10.7% |
| LOAD_ATTR_INSTANCE_VALUE | 20,404,240 | 10.2% |
| COPY | 597,120 | 0.3% |
| LOAD_FAST_LOAD_FAST | 395,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 56,561,280 | 28.1% |
| RETURN_VALUE | 50,317,440 | 25.0% |
| LOAD_FAST | 37,812,480 | 18.8% |
| LOAD_ATTR_INSTANCE_VALUE | 20,404,240 | 10.2% |
| STORE_FAST | 5,266,560 | 2.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,799,360 | 69.0% |
| ENTER_EXECUTOR | 23,846,400 | 26.2% |
| LOAD_GLOBAL_MODULE | 1,578,240 | 1.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,363,200 | 1.5% |
| LOAD_FAST_LOAD_FAST | 1,359,360 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 81,932,160 | 90.0% |
| LOAD_FAST | 8,040,960 | 8.8% |
| LOAD_FAST_LOAD_FAST | 973,440 | 1.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 93,920 | 0.1% |


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

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 46,080 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,359,680 | 40.0% |
| POP_TOP | 1,952,640 | 33.1% |
| CALL_LIST_APPEND | 981,120 | 16.6% |
| ENTER_EXECUTOR | 395,520 | 6.7% |
| STORE_ATTR_INSTANCE_VALUE | 192,000 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,342,780 | 56.6% |
| LOAD_GLOBAL_MODULE | 2,551,680 | 43.2% |
| LOAD_CONST | 9,600 | 0.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 56,561,280 | 80.3% |
| POP_JUMP_IF_FALSE | 3,102,720 | 4.4% |
| LOAD_GLOBAL_BUILTIN | 2,551,680 | 3.6% |
| STORE_ATTR_INSTANCE_VALUE | 2,536,320 | 3.6% |
| STORE_FAST | 1,777,920 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 59,059,200 | 83.8% |
| LOAD_ATTR | 4,869,160 | 6.9% |
| LOAD_FAST | 2,768,640 | 3.9% |
| CALL | 1,601,280 | 2.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,578,240 | 2.2% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,551,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,182,720 | 46.4% |
| LOAD_FAST | 781,440 | 30.6% |
| LOAD_FAST_LOAD_FAST | 395,520 | 15.5% |
| CALL_PY_EXACT_ARGS | 192,000 | 7.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 90,958,080 | 92.1% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,216,640 | 5.3% |
| COPY_FREE_VARS | 2,551,740 | 2.6% |
| CACHE | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 93,116,160 | 94.3% |
| LOAD_GLOBAL_BUILTIN | 2,359,680 | 2.4% |
| LOAD_GLOBAL_MODULE | 1,574,440 | 1.6% |
| RETURN_CONST | 888,960 | 0.9% |
| LOAD_FAST_LOAD_FAST | 769,920 | 0.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20,943,360 | 50.7% |
| LOAD_FAST | 9,175,680 | 22.2% |
| LOAD_ATTR_INSTANCE_VALUE | 5,253,120 | 12.7% |
| LOAD_FAST_LOAD_FAST | 5,063,040 | 12.3% |
| SWAP | 597,120 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 28,166,400 | 68.2% |
| LOAD_FAST | 6,510,720 | 15.8% |
| LOAD_GLOBAL_MODULE | 2,536,320 | 6.1% |
| LOAD_CONST | 1,956,480 | 4.7% |
| LOAD_FAST_LOAD_FAST | 1,543,680 | 3.7% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,797,120 | 57.1% |
| COPY | 2,895,360 | 21.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,747,200 | 12.8% |
| RETURN_CONST | 1,196,160 | 8.8% |
| LOAD_FAST | 15,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 8,747,520 | 64.1% |
| POP_JUMP_IF_TRUE | 4,700,160 | 34.4% |
| UNARY_NOT | 203,520 | 1.5% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 3,335,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,335,040 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,920 | 100.0% |


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
| specialization.deferred |         3840 | 33.1% |
|          hit |         7680 | 66.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 80 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 80 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     16986240 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       259200 | 2.7% |
|          hit |      9463740 | 97.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 10.0% |
| Failure | 180 | 90.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 140 | 77.8% |
| true divide other | 40 | 22.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2980020 | 2.5% |
| specialization.deopt |        94680 | 0.1% |
|          hit |    109030720 | 93.2% |
|         miss |      5016020 | 4.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 94,700 | 98.8% |
| Failure | 1,180 | 1.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 660 | 55.9% |
| operator wrapper | 360 | 30.5% |
| cfunc noargs | 60 | 5.1% |
| wrong number arguments | 60 | 5.1% |
| other | 40 | 3.4% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2373120 | 3.5% |
|          hit |     65477820 | 96.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 2.5% |
| Failure | 780 | 97.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 740 | 94.9% |
| float long | 40 | 5.1% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      3043260 | 100.0% |


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
| specialization.deferred |     11955860 | 3.3% |
| specialization.deopt |       151920 | 0.0% |
|          hit |    343031580 | 94.5% |
|         miss |      8046520 | 2.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 151,960 | 97.5% |
| Failure | 3,840 | 2.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 1,680 | 43.8% |
| class method obj | 1,320 | 34.4% |
| mutable class | 840 | 21.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     76375840 | 100.0% |

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
|          hit |      2551680 | 100.0% |


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
| specialization.deopt |        26740 | 0.1% |
|          hit |     39902920 | 96.6% |
|         miss |      1415340 | 3.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 26,740 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         1920 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 484,385,100 | 35.7% |
| Not specialized | 111,681,300 | 8.2% |
| Specialized | 759,382,460 | 56.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,029,640 | 100.0% |
| LOAD_ATTR | 11,955,860 | 0.0% |
| CALL | 2,980,020 | 0.0% |
| COMPARE_OP | 2,373,120 | 0.0% |
| BINARY_OP | 259,200 | 0.0% |
| BINARY_SUBSCR | 3,840 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| UNARY_NOT | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 4,975,920 | 34.4% |
| LOAD_ATTR_INSTANCE_VALUE | 3,070,600 | 21.2% |
| CALL_PY_EXACT_ARGS | 2,618,780 | 18.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,389,420 | 16.5% |
| STORE_ATTR_INSTANCE_VALUE | 1,415,340 | 9.8% |
| CALL_METHOD_DESCRIPTOR_O | 7,820 | 0.1% |
| RESUME_CHECK | 2,680 | 0.0% |
| RESUME | 2,680 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNARY_NOT | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 195,840 | 0.2% |
| Calls to Python functions inlined | 98,532,540 | 99.8% |
| Calls via PyEval_EvalFrame (total) | 195,840 | 0.2% |
| Calls via PyEval_EvalFrame (vector) | 195,840 | 0.2% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 195,840 | 0.2% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 99,717,180 | 101.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,447,360 | 6.6% |
| Frees to freelist | 1,447,620 |  |
| Allocations | 20,516,880 | 93.4% |
| Allocations to 512 bytes | 20,516,880 | 93.4% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 22,156,180 |  |
| New values | 193,920 |  |
| Interpreter increfs | 679,289,700 | 86.4% |
| Interpreter decrefs | 702,336,240 | 87.0% |
| Increfs | 107,296,444 | 13.6% |
| Decrefs | 104,698,604 | 13.0% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 29,064,158 |  |
| Method cache misses | 172,042 |  |
| Method cache collisions | 172,042 |  |
| Method cache dunder hits | 574,220 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 2,260 | 424,800 | 17,379,920 |
| 1 | 200 | 1,155,280 | 14,009,920 |
| 2 | 20 | 90,800 | 3,786,400 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 22,480 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 30,036,480 |  |
| Uops executed | 283,316,940 | 9 |
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
| <= 8 | 4,164,540 | 13.9% |
| <= 16 | 25,447,620 | 84.7% |
| <= 32 | 420,480 | 1.4% |
| <= 64 | 0 | 0.0% |
| <= 128 | 0 | 0.0% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1024 | 0 | 0.0% |
| <= 2048 | 0 | 0.0% |
| <= 4096 | 3,840 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 65,687,040 | 23.2% | 23.2% |
| LOAD_FAST | 31,130,820 | 11.0% | 34.2% |
| _POP_JUMP_IF_TRUE | 31,042,560 | 11.0% | 45.1% |
| _EXIT_TRACE | 28,682,880 | 10.1% | 55.3% |
| _ITER_CHECK_LIST | 28,250,880 | 10.0% | 65.2% |
| _IS_ITER_EXHAUSTED_LIST | 28,250,880 | 10.0% | 75.2% |
| STORE_FAST | 26,436,420 | 9.3% | 84.5% |
| _ITER_NEXT_LIST | 25,224,960 | 8.9% | 93.4% |
| POP_TOP | 3,043,260 | 1.1% | 94.5% |
| LOAD_CONST | 2,488,320 | 0.9% | 95.4% |
| COMPARE_OP | 1,758,720 | 0.6% | 96.0% |
| LOAD_ATTR | 1,353,600 | 0.5% | 96.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,353,600 | 0.5% | 97.0% |
| _ITER_CHECK_RANGE | 1,036,800 | 0.4% | 97.3% |
| _IS_ITER_EXHAUSTED_RANGE | 1,036,800 | 0.4% | 97.7% |
| _ITER_NEXT_RANGE | 1,019,460 | 0.4% | 98.1% |
| _GUARD_BOTH_INT | 752,640 | 0.3% | 98.3% |
| _JUMP_TO_TOP | 604,800 | 0.2% | 98.5% |
| _LOAD_GLOBAL_MODULE | 382,080 | 0.1% | 98.7% |
| _GUARD_GLOBALS_VERSION | 382,080 | 0.1% | 98.8% |
| BINARY_OP | 382,080 | 0.1% | 98.9% |
| _POP_JUMP_IF_FALSE | 380,160 | 0.1% | 99.1% |
| _LOAD_ATTR_INSTANCE_VALUE | 376,320 | 0.1% | 99.2% |
| _GUARD_TYPE_VERSION | 376,320 | 0.1% | 99.3% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 376,320 | 0.1% | 99.5% |
| _BINARY_OP_MULTIPLY_INT | 376,320 | 0.1% | 99.6% |
| _BINARY_OP_ADD_INT | 376,320 | 0.1% | 99.7% |
| COMPARE_OP_INT | 376,320 | 0.1% | 99.9% |
| BINARY_SUBSCR | 376,320 | 0.1% | 100.0% |
| PUSH_NULL | 1,860 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| LOAD_ATTR_METHOD_WITH_VALUES | 22,480 |


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
