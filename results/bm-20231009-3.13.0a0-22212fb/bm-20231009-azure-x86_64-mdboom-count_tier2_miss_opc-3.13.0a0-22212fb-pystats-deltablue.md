
# Pystats results

- benchmark: deltablue
- fork: mdboom
- ref: count-tier2-miss-opcodes
- commit hash: 22212fb
- commit date: 2023-10-09T12:01:25-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 293,622,240 | 20.2% | 20.2% |  |
| LOAD_ATTR_INSTANCE_VALUE | 201,308,560 | 13.9% | 34.1% | 1.5% |
| RESUME_CHECK | 98,728,380 | 6.8% | 40.9% | 0.0% |
| CALL_PY_EXACT_ARGS | 92,376,480 | 6.4% | 47.3% | 2.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 91,040,480 | 6.3% | 53.6% | 5.5% |
| LOAD_GLOBAL_MODULE | 70,853,860 | 4.9% | 58.4% |  |
| POP_JUMP_IF_FALSE | 69,847,740 | 4.8% | 63.3% |  |
| COMPARE_OP_INT | 65,854,140 | 4.5% | 67.8% |  |
| RETURN_VALUE | 61,395,900 | 4.2% | 72.0% |  |
| LOAD_ATTR_CLASS | 59,059,200 | 4.1% | 76.1% |  |
| STORE_FAST | 45,193,260 | 3.1% | 79.2% |  |
| STORE_ATTR_INSTANCE_VALUE | 41,318,260 | 2.8% | 82.1% | 3.4% |
| POP_TOP | 39,826,620 | 2.7% | 84.8% |  |
| RETURN_CONST | 38,321,280 | 2.6% | 87.4% |  |
| FOR_ITER_LIST | 31,276,800 | 2.2% | 89.6% |  |
| JUMP_BACKWARD | 31,023,360 | 2.1% | 91.7% |  |
| LOAD_FAST_LOAD_FAST | 15,242,880 | 1.1% | 92.8% |  |
| TO_BOOL_BOOL | 13,651,200 | 0.9% | 93.7% |  |
| LOAD_ATTR | 13,313,600 | 0.9% | 94.6% |  |
| POP_JUMP_IF_TRUE | 9,375,360 | 0.6% | 95.3% |  |
| LOAD_CONST | 6,933,180 | 0.5% | 95.8% |  |
| LOAD_GLOBAL_BUILTIN | 5,904,060 | 0.4% | 96.2% |  |
| BINARY_OP_ADD_INT | 5,374,080 | 0.4% | 96.5% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,216,640 | 0.4% | 96.9% |  |
| BINARY_OP_MULTIPLY_INT | 4,775,040 | 0.3% | 97.2% |  |
| CALL_LIST_APPEND | 4,498,560 | 0.3% | 97.5% |  |
| COMPARE_OP | 4,133,060 | 0.3% | 97.8% |  |
| COPY | 3,492,480 | 0.2% | 98.1% |  |
| CALL_LEN | 3,335,040 | 0.2% | 98.3% |  |
| TO_BOOL_INT | 3,335,040 | 0.2% | 98.5% |  |
| GET_ITER | 3,043,260 | 0.2% | 98.7% |  |
| CALL | 2,981,220 | 0.2% | 98.9% |  |
| COPY_FREE_VARS | 2,551,740 | 0.2% | 99.1% |  |
| LOAD_SUPER_ATTR_METHOD | 2,551,680 | 0.2% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,389,420 | 0.2% | 99.5% | 100.0% |
| POP_JUMP_IF_NONE | 2,152,320 | 0.1% | 99.6% |  |
| FOR_ITER_RANGE | 1,054,140 | 0.1% | 99.7% |  |
| EXIT_INIT_CHECK | 988,800 | 0.1% | 99.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 988,800 | 0.1% | 99.8% |  |
| BINARY_OP | 641,520 | 0.0% | 99.9% |  |
| SWAP | 597,120 | 0.0% | 99.9% |  |
| JUMP_FORWARD | 385,920 | 0.0% | 99.9% |  |
| BINARY_SUBSCR | 380,280 | 0.0% | 100.0% |  |
| UNARY_NOT | 203,520 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 195,840 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 67,200 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 46,080 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 17,340 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 7,820 | 0.0% | 100.0% | 100.0% |
| BUILD_CONST_KEY_MAP | 7,680 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 7,680 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 3,840 | 0.0% | 100.0% |  |
| PUSH_NULL | 2,160 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 1,920 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 1,920 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 1,920 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 157,996,800 | 10.9% | 10.9% |
| RESUME_CHECK LOAD_FAST | 93,116,160 | 6.4% | 17.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 90,958,080 | 6.3% | 23.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 86,645,760 | 6.0% | 29.5% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 81,932,160 | 5.6% | 35.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 60,898,560 | 4.2% | 39.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_CLASS | 59,059,200 | 4.1% | 43.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 57,744,060 | 4.0% | 47.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 56,561,280 | 3.9% | 51.3% |
| LOAD_ATTR_CLASS COMPARE_OP_INT | 56,557,440 | 3.9% | 55.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 50,317,440 | 3.5% | 58.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 38,188,800 | 2.6% | 61.3% |
| STORE_FAST LOAD_FAST | 37,843,440 | 2.6% | 63.9% |
| RETURN_CONST POP_TOP | 35,936,640 | 2.5% | 66.4% |
| JUMP_BACKWARD FOR_ITER_LIST | 28,250,880 | 1.9% | 68.4% |
| FOR_ITER_LIST STORE_FAST | 28,250,880 | 1.9% | 70.3% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 28,166,400 | 1.9% | 72.3% |
| POP_TOP JUMP_BACKWARD | 23,617,920 | 1.6% | 73.9% |
| RETURN_VALUE LOAD_ATTR_INSTANCE_VALUE | 21,532,800 | 1.5% | 75.4% |
| RETURN_VALUE STORE_ATTR_INSTANCE_VALUE | 20,943,360 | 1.4% | 76.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 20,404,240 | 1.4% | 78.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 9,175,680 | 0.6% | 78.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 9,018,240 | 0.6% | 79.5% |
| LOAD_ATTR LOAD_FAST | 8,807,040 | 0.6% | 80.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 8,747,520 | 0.6% | 80.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 8,040,960 | 0.6% | 81.2% |
| RETURN_VALUE TO_BOOL_BOOL | 7,797,120 | 0.5% | 81.8% |
| POP_TOP LOAD_FAST | 6,994,560 | 0.5% | 82.3% |
| COMPARE_OP_INT RETURN_VALUE | 6,958,080 | 0.5% | 82.7% |
| RETURN_VALUE STORE_FAST | 6,650,880 | 0.5% | 83.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 6,510,720 | 0.4% | 83.6% |
| LOAD_FAST LOAD_ATTR | 6,441,600 | 0.4% | 84.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 5,322,240 | 0.4% | 84.5% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 5,266,560 | 0.4% | 84.8% |
| LOAD_ATTR_INSTANCE_VALUE STORE_ATTR_INSTANCE_VALUE | 5,253,120 | 0.4% | 85.2% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 5,216,640 | 0.4% | 85.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 4,869,160 | 0.3% | 85.9% |
| LOAD_FAST COMPARE_OP_INT | 4,853,760 | 0.3% | 86.2% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 4,761,600 | 0.3% | 86.5% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 4,700,160 | 0.3% | 86.9% |
| BINARY_OP_ADD_INT LOAD_FAST | 4,394,880 | 0.3% | 87.2% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 4,394,880 | 0.3% | 87.5% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_ADD_INT | 4,394,880 | 0.3% | 87.8% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 4,394,880 | 0.3% | 88.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 4,116,480 | 0.3% | 88.4% |
| LOAD_FAST CALL_LIST_APPEND | 4,110,720 | 0.3% | 88.6% |
| COMPARE_OP POP_JUMP_IF_TRUE | 4,103,040 | 0.3% | 88.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 4,103,040 | 0.3% | 89.2% |
| LOAD_ATTR_INSTANCE_VALUE CALL_BOUND_METHOD_EXACT_ARGS | 3,672,960 | 0.3% | 89.5% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 3,672,960 | 0.3% | 89.7% |
| RETURN_VALUE LOAD_FAST | 3,492,480 | 0.2% | 90.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,342,780 | 0.2% | 90.2% |
| LOAD_FAST CALL_LEN | 3,335,040 | 0.2% | 90.4% |
| CALL_LEN TO_BOOL_INT | 3,335,040 | 0.2% | 90.6% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 3,335,040 | 0.2% | 90.9% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 3,321,600 | 0.2% | 91.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 3,102,720 | 0.2% | 91.3% |
| GET_ITER FOR_ITER_LIST | 3,025,920 | 0.2% | 91.5% |
| LOAD_CONST LOAD_FAST | 2,983,680 | 0.2% | 91.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,960,640 | 0.2% | 91.9% |
| POP_TOP RETURN_CONST | 2,937,600 | 0.2% | 92.1% |
| POP_TOP LOAD_FAST_LOAD_FAST | 2,929,920 | 0.2% | 92.3% |
| COPY TO_BOOL_BOOL | 2,895,360 | 0.2% | 92.5% |
| COPY_FREE_VARS RESUME_CHECK | 2,551,740 | 0.2% | 92.7% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 2,551,680 | 0.2% | 92.9% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 2,551,680 | 0.2% | 93.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 2,536,320 | 0.2% | 93.2% |
| LOAD_FAST RETURN_VALUE | 2,534,460 | 0.2% | 93.4% |
| LOAD_ATTR_CLASS LOAD_FAST | 2,501,760 | 0.2% | 93.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,359,680 | 0.2% | 93.8% |
| LOAD_ATTR LOAD_CONST | 2,352,000 | 0.2% | 93.9% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST | 2,344,320 | 0.2% | 94.1% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 2,344,320 | 0.2% | 94.2% |
| LOAD_ATTR_INSTANCE_VALUE COPY | 2,315,520 | 0.2% | 94.4% |
| FOR_ITER_LIST RETURN_CONST | 2,217,600 | 0.2% | 94.6% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,160,000 | 0.1% | 94.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 2,144,640 | 0.1% | 94.8% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 2,129,280 | 0.1% | 95.0% |
| LOAD_FAST GET_ITER | 1,966,140 | 0.1% | 95.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,956,480 | 0.1% | 95.3% |
| POP_TOP LOAD_GLOBAL_BUILTIN | 1,952,640 | 0.1% | 95.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,952,640 | 0.1% | 95.5% |
| CALL_LIST_APPEND RETURN_CONST | 1,944,960 | 0.1% | 95.7% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,747,200 | 0.1% | 95.8% |
| JUMP_BACKWARD LOAD_FAST | 1,735,680 | 0.1% | 95.9% |
| POP_JUMP_IF_FALSE POP_TOP | 1,735,680 | 0.1% | 96.0% |
| LOAD_GLOBAL_MODULE CALL | 1,601,280 | 0.1% | 96.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_WITH_VALUES | 1,578,240 | 0.1% | 96.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,574,440 | 0.1% | 96.4% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,574,400 | 0.1% | 96.5% |
| LOAD_ATTR LOAD_FAST_LOAD_FAST | 1,543,680 | 0.1% | 96.6% |
| LOAD_FAST_LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 1,543,680 | 0.1% | 96.7% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 1,543,680 | 0.1% | 96.8% |
| CALL_LIST_APPEND JUMP_BACKWARD | 1,370,880 | 0.1% | 96.9% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 1,368,960 | 0.1% | 97.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 1,363,200 | 0.1% | 97.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,359,360 | 0.1% | 97.2% |
| CALL STORE_FAST | 1,203,900 | 0.1% | 97.2% |
| RETURN_CONST TO_BOOL_BOOL | 1,196,160 | 0.1% | 97.3% |
| CALL POP_TOP | 1,184,700 | 0.1% | 97.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

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
| LOAD_FAST_LOAD_FAST | 380,160 | 100.0% |
| BINARY_SUBSCR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 380,160 | 100.0% |
| BINARY_SUBSCR | 120 | 0.0% |


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
| JUMP_BACKWARD | 23,617,920 | 59.3% |
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
| LOAD_FAST | 2,040 | 94.4% |
| LOAD_DEREF | 60 | 2.8% |
| LOAD_ATTR_MODULE | 40 | 1.9% |
| LOAD_ATTR | 20 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,100 | 97.2% |
| LOAD_FAST | 60 | 2.8% |


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
| LOAD_FAST | 577,940 | 90.1% |
| LOAD_ATTR_INSTANCE_VALUE | 63,360 | 9.9% |
| BINARY_OP | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 447,360 | 69.7% |
| STORE_FAST | 193,920 | 30.2% |
| BINARY_OP | 220 | 0.0% |
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
| LOAD_FAST | 193,940 | 6.5% |
| PUSH_NULL | 2,100 | 0.1% |
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
| LOAD_FAST_LOAD_FAST | 4,103,040 | 99.3% |
| LOAD_FAST | 15,360 | 0.4% |
| LOAD_ATTR | 11,520 | 0.3% |
| LOAD_CONST | 1,940 | 0.0% |
| COMPARE_OP | 1,200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,103,040 | 99.3% |
| POP_JUMP_IF_FALSE | 21,120 | 0.5% |
| STORE_FAST | 7,680 | 0.2% |
| COMPARE_OP | 1,200 | 0.0% |
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

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 23,617,920 | 76.1% |
| POP_JUMP_IF_TRUE | 3,321,600 | 10.7% |
| POP_JUMP_IF_FALSE | 2,129,280 | 6.9% |
| CALL_LIST_APPEND | 1,370,880 | 4.4% |
| POP_JUMP_IF_NONE | 382,080 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 28,250,880 | 91.1% |
| LOAD_FAST | 1,735,680 | 5.6% |
| FOR_ITER_RANGE | 1,036,800 | 3.3% |


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
| LOAD_FAST | 6,441,600 | 48.4% |
| LOAD_GLOBAL_MODULE | 4,869,160 | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,952,640 | 14.7% |
| LOAD_ATTR_SLOT | 46,080 | 0.3% |
| LOAD_ATTR | 4,100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,807,040 | 66.2% |
| LOAD_CONST | 2,352,000 | 17.7% |
| LOAD_FAST_LOAD_FAST | 1,543,680 | 11.6% |
| CALL_ALLOC_AND_ENTER_INIT | 587,520 | 4.4% |
| COMPARE_OP | 11,520 | 0.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 2,352,000 | 33.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,956,480 | 28.2% |
| LOAD_ATTR_INSTANCE_VALUE | 600,960 | 8.7% |
| LOAD_FAST | 587,580 | 8.5% |
| LOAD_GLOBAL_MODULE | 387,840 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,983,680 | 43.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,344,320 | 33.8% |
| BINARY_OP_ADD_INT | 979,200 | 14.1% |
| BINARY_OP_MULTIPLY_INT | 380,160 | 5.5% |
| COMPARE_OP_INT | 195,880 | 2.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 93,116,160 | 31.7% |
| POP_JUMP_IF_FALSE | 60,898,560 | 20.7% |
| LOAD_ATTR_INSTANCE_VALUE | 38,188,800 | 13.0% |
| STORE_FAST | 37,843,440 | 12.9% |
| LOAD_ATTR | 8,807,040 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 157,996,800 | 53.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 86,645,760 | 29.5% |
| STORE_ATTR_INSTANCE_VALUE | 9,175,680 | 3.1% |
| CALL_PY_EXACT_ARGS | 9,018,240 | 3.1% |
| LOAD_ATTR | 6,441,600 | 2.2% |


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
| STORE_FAST | 4,761,600 | 31.2% |
| POP_TOP | 2,929,920 | 19.2% |
| LOAD_ATTR | 1,543,680 | 10.1% |
| STORE_ATTR_INSTANCE_VALUE | 1,543,680 | 10.1% |
| POP_JUMP_IF_TRUE | 973,440 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,322,240 | 34.9% |
| COMPARE_OP | 4,103,040 | 26.9% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,543,680 | 10.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,359,360 | 8.9% |
| CALL_PY_EXACT_ARGS | 1,176,960 | 7.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 50.0% |
| POP_JUMP_IF_FALSE | 20 | 25.0% |
| RESUME_CHECK | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 50.0% |
| LOAD_ATTR | 20 | 25.0% |
| LOAD_GLOBAL_BUILTIN | 20 | 25.0% |


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
| JUMP_BACKWARD | 2,129,280 | 3.0% |
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
| TO_BOOL_BOOL | 4,700,160 | 50.1% |
| COMPARE_OP | 4,103,040 | 43.8% |
| COMPARE_OP_INT | 572,160 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,116,480 | 43.9% |
| JUMP_BACKWARD | 3,321,600 | 35.4% |
| LOAD_FAST_LOAD_FAST | 973,440 | 10.4% |
| RETURN_VALUE | 579,840 | 6.2% |
| POP_TOP | 384,000 | 4.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 28,166,400 | 73.5% |
| POP_TOP | 2,937,600 | 7.7% |
| FOR_ITER_LIST | 2,217,600 | 5.8% |
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
| FOR_ITER_LIST | 28,250,880 | 62.5% |
| RETURN_VALUE | 6,650,880 | 14.7% |
| LOAD_ATTR_INSTANCE_VALUE | 5,266,560 | 11.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,344,320 | 5.2% |
| CALL | 1,203,900 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,843,440 | 83.7% |
| LOAD_FAST_LOAD_FAST | 4,761,600 | 10.5% |
| LOAD_GLOBAL_MODULE | 2,160,000 | 4.8% |
| LOAD_CONST | 203,520 | 0.5% |
| JUMP_BACKWARD | 201,600 | 0.4% |


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
| LOAD_CONST | 1,920 | 50.0% |
| LOAD_GLOBAL_MODULE | 1,920 | 50.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 4,394,880 | 81.8% |
| LOAD_CONST | 979,200 | 18.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,394,880 | 81.8% |
| SWAP | 597,120 | 11.1% |
| COMPARE_OP_INT | 380,160 | 7.1% |
| CALL_BUILTIN_CLASS | 1,920 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,394,880 | 92.0% |
| LOAD_CONST | 380,160 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,394,880 | 92.0% |
| LOAD_CONST | 380,160 | 8.0% |


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
| LOAD_FAST | 384,000 | 38.8% |
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
| JUMP_BACKWARD | 1,370,880 | 30.5% |
| LOAD_GLOBAL_BUILTIN | 981,120 | 21.8% |
| LOAD_GLOBAL_MODULE | 201,600 | 4.5% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,344,320 | 98.1% |
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
| LOAD_ATTR_CLASS | 56,557,440 | 85.9% |
| LOAD_FAST | 4,853,760 | 7.4% |
| LOAD_ATTR_INSTANCE_VALUE | 3,672,960 | 5.6% |
| BINARY_OP_ADD_INT | 380,160 | 0.6% |
| LOAD_CONST | 195,880 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 57,744,060 | 87.7% |
| RETURN_VALUE | 6,958,080 | 10.6% |
| COPY | 579,840 | 0.9% |
| POP_JUMP_IF_TRUE | 572,160 | 0.9% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 28,250,880 | 90.3% |
| GET_ITER | 3,025,920 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 28,250,880 | 90.3% |
| RETURN_CONST | 2,217,600 | 7.1% |
| LOAD_FAST | 412,800 | 1.3% |
| LOAD_GLOBAL_BUILTIN | 395,520 | 1.3% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,036,800 | 98.4% |
| GET_ITER | 17,340 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,036,800 | 98.4% |
| LOAD_FAST | 7,740 | 0.7% |
| LOAD_GLOBAL_MODULE | 5,760 | 0.5% |
| RETURN_CONST | 3,840 | 0.4% |


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
| LOAD_FAST | 157,996,800 | 78.5% |
| RETURN_VALUE | 21,532,800 | 10.7% |
| LOAD_ATTR_INSTANCE_VALUE | 20,404,240 | 10.1% |
| COPY | 597,120 | 0.3% |
| LOAD_FAST_LOAD_FAST | 395,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 56,561,280 | 28.1% |
| RETURN_VALUE | 50,317,440 | 25.0% |
| LOAD_FAST | 38,188,800 | 19.0% |
| LOAD_ATTR_INSTANCE_VALUE | 20,404,240 | 10.1% |
| STORE_FAST | 5,266,560 | 2.6% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,645,760 | 95.2% |
| LOAD_GLOBAL_MODULE | 1,578,240 | 1.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,363,200 | 1.5% |
| LOAD_FAST_LOAD_FAST | 1,359,360 | 1.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 93,920 | 0.1% |

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
| FOR_ITER_LIST | 395,520 | 6.7% |
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
| LOAD_ATTR_INSTANCE_VALUE | 56,561,280 | 79.8% |
| POP_JUMP_IF_FALSE | 3,102,720 | 4.4% |
| LOAD_GLOBAL_BUILTIN | 2,551,680 | 3.6% |
| STORE_ATTR_INSTANCE_VALUE | 2,536,320 | 3.6% |
| STORE_FAST | 2,160,000 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 59,059,200 | 83.4% |
| LOAD_ATTR | 4,869,160 | 6.9% |
| LOAD_FAST | 2,960,640 | 4.2% |
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
| LOAD_FAST_LOAD_FAST | 5,322,240 | 12.9% |
| LOAD_ATTR_INSTANCE_VALUE | 5,253,120 | 12.7% |
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

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 641,280 | 5.9% |
|          hit | 10,216,380 | 94.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 8.3% |
| Failure | 220 | 91.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 180 | 81.8% |
| true divide other | 40 | 18.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 380,160 | 98.0% |
|          hit | 7,680 | 2.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 120 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 120 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,980,020 | 2.5% |
|        deopt | 94,680 | 0.1% |
|          hit | 109,030,720 | 93.2% |
|         miss | 5,016,020 | 4.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 94,700 | 98.8% |
| Failure | 1,180 | 1.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 660 | 55.9% |
| operator wrapper | 360 | 30.5% |
| wrong number arguments | 60 | 5.1% |
| cfunc noargs | 60 | 5.1% |
| other | 40 | 3.4% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,131,840 | 5.9% |
|          hit | 65,854,140 | 94.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 1.6% |
| Failure | 1,200 | 98.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 860 | 71.7% |
| different types | 300 | 25.0% |
| float long | 40 | 3.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 32,330,940 | 100.0% |


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
|     deferred | 13,309,460 | 3.6% |
|        deopt | 151,920 | 0.0% |
|          hit | 343,407,900 | 94.1% |
|         miss | 8,046,520 | 2.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 151,960 | 97.4% |
| Failure | 4,100 | 2.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 1,940 | 47.3% |
| class method obj | 1,320 | 32.2% |
| mutable class | 840 | 20.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 76,757,920 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 2,551,680 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>


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
|        deopt | 26,740 | 0.1% |
|          hit | 39,902,920 | 96.6% |
|         miss | 1,415,340 | 3.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 26,740 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 16,986,240 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,920 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 512,011,800 | 35.3% |
| Not specialized | 148,329,160 | 10.2% |
| Specialized | 790,557,440 | 54.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,029,580 | 100.0% |
| LOAD_ATTR | 13,309,460 | 0.0% |
| COMPARE_OP | 4,131,840 | 0.0% |
| CALL | 2,980,020 | 0.0% |
| BINARY_OP | 641,280 | 0.0% |
| BINARY_SUBSCR | 380,160 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| CACHE | 0 | 0.0% |


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
| RESUME | 2,740 | 0.0% |
| RESUME_CHECK | 2,740 | 0.0% |
| CACHE | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |


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
| Frame objects created | 0 | 0.0% |
| Frames pushed | 99,717,180 | 101.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,447,320 | 6.6% |
| Frees to freelist | 1,447,620 |  |
| Allocations | 20,516,920 | 93.4% |
| Allocations to 512 bytes | 20,516,920 | 93.4% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 22,156,200 |  |
| New values | 193,920 |  |
| Interpreter increfs | 705,194,280 | 93.2% |
| Interpreter decrefs | 739,401,900 | 95.2% |
| Increfs | 51,266,782 | 6.8% |
| Decrefs | 37,507,862 | 4.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 29,211,460 |  |
| Method cache misses | 25,000 |  |
| Method cache collisions | 25,000 |  |
| Method cache dunder hits | 574,260 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 2,260 | 430,960 | 17,375,760 |
| 1 | 200 | 1,161,200 | 14,018,320 |
| 2 | 20 | 78,720 | 3,686,640 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 0 |  |
| Uops executed | 0 |  |
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
| <= 1 | 0 |  |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


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
