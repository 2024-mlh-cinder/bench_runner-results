
# Pystats results

- benchmark: deltablue
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 96,699,120 | 21.6% | 21.6% |  |
| LOAD_ATTR_INSTANCE_VALUE | 67,375,680 | 15.0% | 36.6% | 3.0% |
| RESUME_CHECK | 25,550,360 | 5.7% | 42.3% | 0.0% |
| CALL_PY_EXACT_ARGS | 21,437,480 | 4.8% | 47.0% | 7.1% |
| LOAD_GLOBAL_MODULE | 20,490,100 | 4.6% | 51.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 20,296,300 | 4.5% | 56.1% | 15.2% |
| POP_JUMP_IF_FALSE | 19,948,600 | 4.4% | 60.6% |  |
| COMPARE_OP_INT | 16,782,320 | 3.7% | 64.3% |  |
| STORE_ATTR_INSTANCE_VALUE | 14,572,160 | 3.2% | 67.6% | 6.4% |
| RETURN_VALUE | 14,569,140 | 3.2% | 70.8% |  |
| POP_TOP | 13,705,840 | 3.1% | 73.9% |  |
| LOAD_ATTR_CLASS | 13,008,760 | 2.9% | 76.8% |  |
| RETURN_CONST | 12,702,020 | 2.8% | 79.6% |  |
| STORE_FAST | 12,086,040 | 2.7% | 82.3% |  |
| TO_BOOL_BOOL | 8,589,060 | 1.9% | 84.2% |  |
| LOAD_FAST_LOAD_FAST | 8,567,820 | 1.9% | 86.1% |  |
| LOAD_ATTR | 7,861,100 | 1.8% | 87.9% |  |
| ENTER_EXECUTOR | 7,215,840 | 1.6% | 89.5% |  |
| POP_JUMP_IF_TRUE | 4,575,180 | 1.0% | 90.5% |  |
| LOAD_GLOBAL_BUILTIN | 3,935,600 | 0.9% | 91.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 3,351,160 | 0.7% | 92.1% |  |
| BINARY_OP_ADD_INT | 3,332,340 | 0.7% | 92.9% |  |
| CALL_LIST_APPEND | 2,998,820 | 0.7% | 93.5% |  |
| LOAD_CONST | 2,965,980 | 0.7% | 94.2% |  |
| BINARY_OP_MULTIPLY_INT | 2,933,020 | 0.7% | 94.9% |  |
| COPY | 2,328,320 | 0.5% | 95.4% |  |
| CALL_LEN | 2,223,240 | 0.5% | 95.9% |  |
| TO_BOOL_INT | 2,223,240 | 0.5% | 96.4% |  |
| CALL | 1,994,560 | 0.4% | 96.8% |  |
| GET_ITER | 1,856,660 | 0.4% | 97.2% |  |
| FOR_ITER_LIST | 1,848,240 | 0.4% | 97.6% |  |
| COPY_FREE_VARS | 1,701,200 | 0.4% | 98.0% |  |
| LOAD_SUPER_ATTR_METHOD | 1,700,900 | 0.4% | 98.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,592,840 | 0.4% | 98.8% | 100.0% |
| COMPARE_OP | 1,585,200 | 0.4% | 99.1% |  |
| POP_JUMP_IF_NONE | 1,434,880 | 0.3% | 99.4% |  |
| EXIT_INIT_CHECK | 658,940 | 0.1% | 99.6% |  |
| CALL_ALLOC_AND_ENTER_INIT | 658,940 | 0.1% | 99.7% |  |
| SWAP | 398,080 | 0.1% | 99.8% |  |
| JUMP_FORWARD | 257,280 | 0.1% | 99.9% |  |
| BINARY_OP | 174,500 | 0.0% | 99.9% |  |
| UNARY_NOT | 135,680 | 0.0% | 99.9% |  |
| INTERPRETER_EXIT | 130,820 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 44,740 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 30,600 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 13,560 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 11,460 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 7,040 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 5,180 | 0.0% | 100.0% | 100.0% |
| BUILD_CONST_KEY_MAP | 5,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 5,100 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 4,080 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 3,400 | 0.0% | 100.0% |  |
| STORE_GLOBAL | 2,560 | 0.0% | 100.0% |  |
| STORE_ATTR | 2,200 | 0.0% | 100.0% |  |
| TO_BOOL | 1,280 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 1,280 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 1,280 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 1,260 | 0.0% | 100.0% |  |
| RESUME | 1,200 | 0.0% | 100.0% | 146.7% |
| PUSH_NULL | 700 | 0.0% | 100.0% |  |
| FOR_ITER | 520 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 440 | 0.0% | 100.0% |  |
| LOAD_DEREF | 160 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 120 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 52,056,800 | 11.6% | 11.6% |
| RESUME_CHECK LOAD_FAST | 21,855,200 | 4.9% | 16.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 20,496,120 | 4.6% | 21.0% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 14,734,440 | 3.3% | 24.3% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 14,656,940 | 3.3% | 27.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 14,366,900 | 3.2% | 30.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_CLASS | 13,008,520 | 2.9% | 33.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 12,968,980 | 2.9% | 36.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 12,137,240 | 2.7% | 39.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 11,776,240 | 2.6% | 41.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 11,343,520 | 2.5% | 44.4% |
| LOAD_ATTR_CLASS COMPARE_OP_INT | 11,341,000 | 2.5% | 47.0% |
| RETURN_CONST POP_TOP | 11,112,260 | 2.5% | 49.5% |
| STORE_FAST LOAD_FAST | 9,162,040 | 2.0% | 51.5% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 7,694,800 | 1.7% | 53.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 6,115,900 | 1.4% | 54.6% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 5,977,520 | 1.3% | 55.9% |
| LOAD_ATTR LOAD_FAST | 5,746,080 | 1.3% | 57.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 5,573,300 | 1.2% | 58.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,504,840 | 1.2% | 59.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 4,853,960 | 1.1% | 60.7% |
| RETURN_VALUE TO_BOOL_BOOL | 4,686,320 | 1.0% | 61.8% |
| POP_TOP LOAD_FAST | 4,663,040 | 1.0% | 62.8% |
| RETURN_VALUE STORE_FAST | 4,183,160 | 0.9% | 63.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 4,167,940 | 0.9% | 64.7% |
| COMPARE_OP_INT RETURN_VALUE | 4,127,440 | 0.9% | 65.6% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 3,510,960 | 0.8% | 66.4% |
| LOAD_ATTR_INSTANCE_VALUE STORE_ATTR_INSTANCE_VALUE | 3,501,840 | 0.8% | 67.2% |
| LOAD_FAST LOAD_ATTR | 3,398,260 | 0.8% | 67.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,375,400 | 0.8% | 68.7% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 3,351,160 | 0.7% | 69.4% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 3,119,660 | 0.7% | 70.1% |
| BINARY_OP_ADD_INT LOAD_FAST | 2,929,900 | 0.7% | 70.8% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 2,929,900 | 0.7% | 71.4% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_ADD_INT | 2,929,880 | 0.7% | 72.1% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 2,929,880 | 0.7% | 72.7% |
| POP_TOP ENTER_EXECUTOR | 2,898,500 | 0.6% | 73.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 2,880,100 | 0.6% | 74.0% |
| LOAD_FAST CALL_LIST_APPEND | 2,740,080 | 0.6% | 74.6% |
| LOAD_FAST COMPARE_OP_INT | 2,729,500 | 0.6% | 75.2% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 2,713,300 | 0.6% | 75.8% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 2,448,560 | 0.5% | 76.4% |
| RETURN_VALUE LOAD_FAST | 2,328,320 | 0.5% | 76.9% |
| LOAD_ATTR_INSTANCE_VALUE CALL_BOUND_METHOD_EXACT_ARGS | 2,321,900 | 0.5% | 77.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,228,340 | 0.5% | 77.9% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,223,240 | 0.5% | 78.4% |
| LOAD_FAST CALL_LEN | 2,223,120 | 0.5% | 78.9% |
| CALL_LEN TO_BOOL_INT | 2,223,120 | 0.5% | 79.4% |
| POP_TOP RETURN_CONST | 1,958,440 | 0.4% | 79.8% |
| POP_TOP LOAD_FAST_LOAD_FAST | 1,953,280 | 0.4% | 80.3% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,941,540 | 0.4% | 80.7% |
| COPY TO_BOOL_BOOL | 1,930,080 | 0.4% | 81.1% |
| FOR_ITER_LIST STORE_FAST | 1,846,640 | 0.4% | 81.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,845,620 | 0.4% | 82.0% |
| GET_ITER FOR_ITER_LIST | 1,844,940 | 0.4% | 82.4% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 1,810,100 | 0.4% | 82.8% |
| LOAD_CONST LOAD_FAST | 1,735,000 | 0.4% | 83.2% |
| COPY_FREE_VARS RESUME_CHECK | 1,700,960 | 0.4% | 83.6% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,700,680 | 0.4% | 83.9% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 1,700,680 | 0.4% | 84.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,690,640 | 0.4% | 84.7% |
| LOAD_FAST RETURN_VALUE | 1,689,680 | 0.4% | 85.1% |
| LOAD_ATTR_CLASS LOAD_FAST | 1,667,680 | 0.4% | 85.4% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,580,300 | 0.4% | 85.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,572,720 | 0.4% | 86.1% |
| COMPARE_OP POP_JUMP_IF_TRUE | 1,563,820 | 0.3% | 86.5% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 1,563,800 | 0.3% | 86.8% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 1,562,820 | 0.3% | 87.2% |
| RETURN_VALUE LOAD_ATTR_INSTANCE_VALUE | 1,555,380 | 0.3% | 87.5% |
| LOAD_ATTR_INSTANCE_VALUE COPY | 1,543,620 | 0.3% | 87.9% |
| ENTER_EXECUTOR RETURN_CONST | 1,480,380 | 0.3% | 88.2% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,471,320 | 0.3% | 88.5% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,429,760 | 0.3% | 88.9% |
| LOAD_FAST GET_ITER | 1,310,800 | 0.3% | 89.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,304,160 | 0.3% | 89.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,302,240 | 0.3% | 89.7% |
| POP_TOP LOAD_GLOBAL_BUILTIN | 1,301,600 | 0.3% | 90.0% |
| CALL_LIST_APPEND RETURN_CONST | 1,296,600 | 0.3% | 90.3% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,185,400 | 0.3% | 90.6% |
| ENTER_EXECUTOR LOAD_FAST | 1,175,620 | 0.3% | 90.8% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,164,680 | 0.3% | 91.1% |
| RETURN_VALUE STORE_ATTR_INSTANCE_VALUE | 1,162,420 | 0.3% | 91.3% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 1,160,200 | 0.3% | 91.6% |
| POP_JUMP_IF_FALSE POP_TOP | 1,157,120 | 0.3% | 91.9% |
| LOAD_GLOBAL_MODULE CALL | 1,067,400 | 0.2% | 92.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_WITH_VALUES | 1,051,960 | 0.2% | 92.3% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,049,600 | 0.2% | 92.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,049,320 | 0.2% | 92.8% |
| LOAD_ATTR LOAD_FAST_LOAD_FAST | 1,029,140 | 0.2% | 93.0% |
| LOAD_FAST_LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 1,029,080 | 0.2% | 93.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 1,029,020 | 0.2% | 93.5% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 912,640 | 0.2% | 93.7% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 912,540 | 0.2% | 93.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 908,560 | 0.2% | 94.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 906,160 | 0.2% | 94.3% |
| ENTER_EXECUTOR CALL_METHOD_DESCRIPTOR_FAST | 901,500 | 0.2% | 94.5% |
| CALL STORE_FAST | 802,860 | 0.2% | 94.7% |
| RETURN_CONST TO_BOOL_BOOL | 797,300 | 0.2% | 94.9% |
| CALL POP_TOP | 790,160 | 0.2% | 95.0% |
| LOAD_SUPER_ATTR_METHOD CALL | 788,420 | 0.2% | 95.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 129,540 | 99.0% |
| RESUME_CHECK | 1,260 | 1.0% |
| RESUME | 20 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,160 | 92.9% |
| BINARY_SUBSCR | 200 | 5.9% |
| LOAD_ATTR | 20 | 0.6% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,080 | 90.6% |
| BINARY_SUBSCR | 200 | 5.9% |
| LOAD_ATTR | 80 | 2.4% |
| RETURN_VALUE | 20 | 0.6% |
| BINARY_SUBSCR_DICT | 20 | 0.6% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 658,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 658,940 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,310,800 | 70.6% |
| LOAD_ATTR_INSTANCE_VALUE | 534,280 | 28.8% |
| CALL_BUILTIN_CLASS | 11,400 | 0.6% |
| CALL | 120 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,844,940 | 99.4% |
| FOR_ITER_RANGE | 11,460 | 0.6% |
| FOR_ITER | 260 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 130,820 | 100.0% |


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
| RETURN_CONST | 11,112,260 | 81.1% |
| POP_JUMP_IF_FALSE | 1,157,120 | 8.4% |
| CALL | 790,160 | 5.8% |
| RETURN_VALUE | 385,200 | 2.8% |
| POP_JUMP_IF_TRUE | 256,000 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,663,040 | 34.0% |
| ENTER_EXECUTOR | 2,898,500 | 21.1% |
| RETURN_CONST | 1,958,440 | 14.3% |
| LOAD_FAST_LOAD_FAST | 1,953,280 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 1,301,600 | 9.5% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 77.1% |
| LOAD_DEREF | 80 | 11.4% |
| LOAD_ATTR_MODULE | 60 | 8.6% |
| LOAD_ATTR | 20 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 620 | 88.6% |
| LOAD_FAST | 80 | 11.4% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 7,694,800 | 52.8% |
| COMPARE_OP_INT | 4,127,440 | 28.3% |
| LOAD_FAST | 1,689,680 | 11.6% |
| EXIT_INIT_CHECK | 658,940 | 4.5% |
| POP_JUMP_IF_TRUE | 386,560 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,686,320 | 32.2% |
| STORE_FAST | 4,183,160 | 28.7% |
| LOAD_FAST | 2,328,320 | 16.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,555,380 | 10.7% |
| STORE_ATTR_INSTANCE_VALUE | 1,162,420 | 8.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 540 | 42.2% |
| COPY | 160 | 12.5% |
| RETURN_CONST | 140 | 10.9% |
| CALL | 120 | 9.4% |
| CALL_LEN | 120 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 520 | 40.6% |
| POP_JUMP_IF_FALSE | 460 | 35.9% |
| POP_JUMP_IF_TRUE | 160 | 12.5% |
| TO_BOOL_INT | 120 | 9.4% |
| UNARY_NOT | 20 | 1.6% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 135,660 | 100.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 135,680 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 131,200 | 75.2% |
| LOAD_ATTR_INSTANCE_VALUE | 42,280 | 24.2% |
| BINARY_OP | 620 | 0.4% |
| LOAD_CONST | 320 | 0.2% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 171,880 | 98.5% |
| STORE_FAST | 1,600 | 0.9% |
| BINARY_OP | 620 | 0.4% |
| BINARY_OP_ADD_INT | 100 | 0.1% |
| CALL | 60 | 0.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,120 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,067,400 | 53.5% |
| LOAD_SUPER_ATTR_METHOD | 788,420 | 39.5% |
| ENTER_EXECUTOR | 128,600 | 6.4% |
| LOAD_FAST | 3,460 | 0.2% |
| CALL | 2,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 802,860 | 40.3% |
| POP_TOP | 790,160 | 39.6% |
| LOAD_FAST | 394,320 | 19.8% |
| CALL | 2,720 | 0.1% |
| CALL_PY_EXACT_ARGS | 1,520 | 0.1% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,563,800 | 98.7% |
| LOAD_FAST | 10,600 | 0.7% |
| LOAD_ATTR | 7,800 | 0.5% |
| COMPARE_OP | 1,400 | 0.1% |
| LOAD_CONST | 1,400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,563,820 | 98.7% |
| POP_JUMP_IF_FALSE | 14,360 | 0.9% |
| STORE_FAST | 5,120 | 0.3% |
| COMPARE_OP | 1,400 | 0.1% |
| COMPARE_OP_INT | 420 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,543,620 | 66.3% |
| LOAD_FAST | 398,080 | 17.1% |
| COMPARE_OP_INT | 386,540 | 16.6% |
| LOAD_ATTR | 60 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,930,080 | 82.9% |
| LOAD_ATTR_INSTANCE_VALUE | 398,040 | 17.1% |
| TO_BOOL | 160 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 912,540 | 53.6% |
| CALL_ALLOC_AND_ENTER_INIT | 658,940 | 38.7% |
| CACHE | 129,540 | 7.6% |
| CALL | 100 | 0.0% |
| CALL_FUNCTION_EX | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,700,960 | 100.0% |
| RESUME | 240 | 0.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,898,500 | 40.2% |
| POP_JUMP_IF_TRUE | 1,810,100 | 25.1% |
| POP_JUMP_IF_FALSE | 1,160,200 | 16.1% |
| CALL_LIST_APPEND | 912,640 | 12.6% |
| POP_JUMP_IF_NONE | 254,400 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 2,713,300 | 37.6% |
| RETURN_CONST | 1,480,380 | 20.5% |
| LOAD_FAST | 1,175,620 | 16.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 901,500 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 263,340 | 3.6% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 260 | 50.0% |
| JUMP_BACKWARD | 260 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 260 | 50.0% |
| FOR_ITER_RANGE | 140 | 26.9% |
| FOR_ITER_LIST | 120 | 23.1% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,240 | 31.8% |
| POP_TOP | 1,360 | 19.3% |
| POP_JUMP_IF_FALSE | 1,280 | 18.2% |
| CALL_LIST_APPEND | 1,200 | 17.0% |
| STORE_FAST | 640 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 3,180 | 45.2% |
| FOR_ITER_RANGE | 1,960 | 27.8% |
| LOAD_FAST | 1,200 | 17.0% |
| ENTER_EXECUTOR | 440 | 6.2% |
| FOR_ITER | 260 | 3.7% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 257,240 | 100.0% |
| STORE_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 129,280 | 50.2% |
| LOAD_FAST | 128,000 | 49.8% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,398,260 | 43.2% |
| LOAD_GLOBAL_MODULE | 3,119,660 | 39.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,302,240 | 16.6% |
| LOAD_ATTR_SLOT | 30,600 | 0.4% |
| LOAD_ATTR | 9,100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,746,080 | 73.1% |
| LOAD_FAST_LOAD_FAST | 1,029,140 | 13.1% |
| LOAD_CONST | 666,560 | 8.5% |
| CALL_ALLOC_AND_ENTER_INIT | 391,440 | 5.0% |
| LOAD_ATTR | 9,100 | 0.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,304,160 | 44.0% |
| LOAD_ATTR | 666,560 | 22.5% |
| LOAD_ATTR_INSTANCE_VALUE | 400,580 | 13.5% |
| POP_TOP | 143,360 | 4.8% |
| POP_JUMP_IF_FALSE | 143,360 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,735,000 | 58.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 661,260 | 22.3% |
| BINARY_OP_ADD_INT | 402,360 | 13.6% |
| COMPARE_OP_INT | 130,520 | 4.4% |
| STORE_FAST | 6,400 | 0.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,855,200 | 22.6% |
| POP_JUMP_IF_FALSE | 14,366,900 | 14.9% |
| LOAD_ATTR_INSTANCE_VALUE | 11,776,240 | 12.2% |
| STORE_FAST | 9,162,040 | 9.5% |
| LOAD_ATTR | 5,746,080 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 52,056,800 | 53.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 14,656,940 | 15.2% |
| STORE_ATTR_INSTANCE_VALUE | 6,115,900 | 6.3% |
| CALL_PY_EXACT_ARGS | 5,504,840 | 5.7% |
| LOAD_ATTR | 3,398,260 | 3.5% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,240 | 96.9% |
| LOAD_ATTR | 40 | 3.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,953,280 | 22.8% |
| STORE_FAST | 1,580,300 | 18.4% |
| LOAD_ATTR | 1,029,140 | 12.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,029,020 | 12.0% |
| POP_JUMP_IF_TRUE | 648,960 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 3,375,400 | 39.4% |
| COMPARE_OP | 1,563,800 | 18.3% |
| CALL_BOUND_METHOD_EXACT_ARGS | 1,029,080 | 12.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 906,160 | 10.6% |
| CALL_PY_EXACT_ARGS | 784,520 | 9.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 680 | 16.7% |
| POP_JUMP_IF_FALSE | 560 | 13.7% |
| POP_TOP | 500 | 12.3% |
| RESUME | 380 | 9.3% |
| RESUME_CHECK | 380 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,560 | 38.2% |
| LOAD_ATTR | 760 | 18.6% |
| LOAD_FAST | 660 | 16.2% |
| LOAD_GLOBAL_BUILTIN | 480 | 11.8% |
| CALL | 240 | 5.9% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 220 | 50.0% |
| CALL | 100 | 22.7% |
| LOAD_FAST | 60 | 13.6% |
| LOAD_FAST_LOAD_FAST | 60 | 13.6% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 12,137,240 | 60.8% |
| TO_BOOL_BOOL | 5,573,300 | 27.9% |
| TO_BOOL_INT | 2,223,240 | 11.1% |
| COMPARE_OP | 14,360 | 0.1% |
| TO_BOOL | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,366,900 | 72.0% |
| LOAD_GLOBAL_MODULE | 1,941,540 | 9.7% |
| ENTER_EXECUTOR | 1,160,200 | 5.8% |
| POP_TOP | 1,157,120 | 5.8% |
| RETURN_CONST | 1,049,600 | 5.3% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,429,760 | 99.6% |
| LOAD_ATTR_INSTANCE_VALUE | 5,100 | 0.4% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 391,680 | 27.3% |
| LOAD_FAST_LOAD_FAST | 389,120 | 27.1% |
| LOAD_FAST | 271,360 | 18.9% |
| ENTER_EXECUTOR | 254,400 | 17.7% |
| LOAD_GLOBAL_MODULE | 127,960 | 8.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,880,100 | 63.0% |
| COMPARE_OP | 1,563,820 | 34.2% |
| COMPARE_OP_INT | 131,100 | 2.9% |
| TO_BOOL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,810,100 | 39.6% |
| LOAD_FAST | 1,471,320 | 32.2% |
| LOAD_FAST_LOAD_FAST | 648,960 | 14.2% |
| RETURN_VALUE | 386,560 | 8.4% |
| POP_TOP | 256,000 | 5.6% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,977,520 | 47.1% |
| POP_TOP | 1,958,440 | 15.4% |
| ENTER_EXECUTOR | 1,480,380 | 11.7% |
| CALL_LIST_APPEND | 1,296,600 | 10.2% |
| POP_JUMP_IF_FALSE | 1,049,600 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 11,112,260 | 87.5% |
| TO_BOOL_BOOL | 797,300 | 6.3% |
| EXIT_INIT_CHECK | 658,940 | 5.2% |
| INTERPRETER_EXIT | 130,820 | 1.0% |
| STORE_FAST | 2,560 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,220 | 55.5% |
| LOAD_FAST_LOAD_FAST | 540 | 24.5% |
| RETURN_VALUE | 120 | 5.5% |
| LOAD_ATTR | 120 | 5.5% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,020 | 46.4% |
| RETURN_CONST | 380 | 17.3% |
| LOAD_FAST | 320 | 14.5% |
| LOAD_CONST | 160 | 7.3% |
| LOAD_GLOBAL | 140 | 6.4% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,183,160 | 34.6% |
| LOAD_ATTR_INSTANCE_VALUE | 3,510,960 | 29.0% |
| FOR_ITER_LIST | 1,846,640 | 15.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,562,820 | 12.9% |
| CALL | 802,860 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,162,040 | 75.8% |
| LOAD_FAST_LOAD_FAST | 1,580,300 | 13.1% |
| LOAD_GLOBAL_MODULE | 1,185,400 | 9.8% |
| ENTER_EXECUTOR | 133,760 | 1.1% |
| LOAD_GLOBAL_BUILTIN | 15,160 | 0.1% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,260 | 98.4% |
| UNPACK_SEQUENCE | 20 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,280 | 100.0% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,520 | 98.4% |
| CALL | 40 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,280 | 50.0% |
| LOAD_GLOBAL_MODULE | 1,240 | 48.4% |
| LOAD_GLOBAL | 40 | 1.6% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 398,060 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 398,040 | 100.0% |
| STORE_ATTR | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20 | 50.0% |
| UNPACK_SEQUENCE_TUPLE | 20 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 740 | 61.7% |
| COPY_FREE_VARS | 240 | 20.0% |
| CALL_PY_EXACT_ARGS | 200 | 16.7% |
| CACHE | 20 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 53.3% |
| LOAD_GLOBAL | 380 | 31.7% |
| RETURN_CONST | 120 | 10.0% |
| LOAD_CONST | 40 | 3.3% |
| LOAD_FAST_LOAD_FAST | 20 | 1.7% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,929,880 | 87.9% |
| LOAD_CONST | 402,360 | 12.1% |
| BINARY_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,929,900 | 87.9% |
| SWAP | 398,060 | 11.9% |
| COMPARE_OP_INT | 3,080 | 0.1% |
| CALL_BUILTIN_CLASS | 1,240 | 0.0% |
| COMPARE_OP | 40 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,929,880 | 99.9% |
| LOAD_CONST | 3,080 | 0.1% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,929,900 | 99.9% |
| LOAD_CONST | 3,120 | 0.1% |


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
| LOAD_ATTR_INSTANCE_VALUE | 42,200 | 94.3% |
| LOAD_CONST | 2,480 | 5.5% |
| BINARY_OP | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,220 | 94.4% |
| CALL_BUILTIN_CLASS | 2,480 | 5.5% |
| CALL | 40 | 0.1% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,080 | 99.6% |
| BINARY_SUBSCR | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,100 | 100.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 391,440 | 59.4% |
| LOAD_FAST | 129,500 | 19.7% |
| ENTER_EXECUTOR | 126,420 | 19.2% |
| LOAD_GLOBAL_MODULE | 8,840 | 1.3% |
| LOAD_CONST | 2,480 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 658,940 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,321,900 | 69.3% |
| LOAD_FAST_LOAD_FAST | 1,029,080 | 30.7% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,351,160 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,320 | 55.1% |
| BINARY_OP_SUBTRACT_INT | 2,480 | 21.6% |
| LOAD_FAST | 1,280 | 11.2% |
| BINARY_OP_ADD_INT | 1,240 | 10.8% |
| CALL | 140 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 11,400 | 99.5% |
| STORE_FAST | 60 | 0.5% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,223,120 | 100.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 2,223,120 | 100.0% |
| TO_BOOL | 120 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,740,080 | 91.4% |
| RETURN_VALUE | 258,520 | 8.6% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,296,600 | 43.2% |
| ENTER_EXECUTOR | 912,640 | 30.4% |
| LOAD_GLOBAL_BUILTIN | 654,000 | 21.8% |
| LOAD_GLOBAL_MODULE | 134,280 | 4.5% |
| JUMP_BACKWARD | 1,200 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 901,500 | 56.6% |
| LOAD_CONST | 661,260 | 41.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 30,020 | 1.9% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,562,820 | 98.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 30,020 | 1.9% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,080 | 98.1% |
| CALL_METHOD_DESCRIPTOR_O | 80 | 1.5% |
| CALL | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,100 | 98.5% |
| CALL_METHOD_DESCRIPTOR_O | 80 | 1.5% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 14,734,440 | 68.7% |
| LOAD_FAST | 5,504,840 | 25.7% |
| LOAD_FAST_LOAD_FAST | 784,520 | 3.7% |
| ENTER_EXECUTOR | 250,620 | 1.2% |
| LOAD_SUPER_ATTR_METHOD | 127,960 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 20,496,120 | 95.6% |
| COPY_FREE_VARS | 912,540 | 4.3% |
| CALL_PY_EXACT_ARGS | 28,620 | 0.1% |
| RESUME | 200 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 11,341,000 | 67.6% |
| LOAD_FAST | 2,729,500 | 16.3% |
| LOAD_ATTR_INSTANCE_VALUE | 2,448,560 | 14.6% |
| LOAD_CONST | 130,520 | 0.8% |
| LOAD_FAST_LOAD_FAST | 129,240 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,137,240 | 72.3% |
| RETURN_VALUE | 4,127,440 | 24.6% |
| COPY | 386,540 | 2.3% |
| POP_JUMP_IF_TRUE | 131,100 | 0.8% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,844,940 | 99.8% |
| JUMP_BACKWARD | 3,180 | 0.2% |
| FOR_ITER | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,846,640 | 99.9% |
| LOAD_FAST | 680 | 0.0% |
| RETURN_CONST | 580 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 11,460 | 84.5% |
| JUMP_BACKWARD | 1,960 | 14.5% |
| FOR_ITER | 140 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,540 | 99.9% |
| LOAD_FAST | 20 | 0.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,008,520 | 100.0% |
| LOAD_ATTR | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 11,341,000 | 87.2% |
| LOAD_FAST | 1,667,680 | 12.8% |
| COMPARE_OP | 80 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,056,800 | 77.3% |
| LOAD_ATTR_INSTANCE_VALUE | 12,968,980 | 19.2% |
| RETURN_VALUE | 1,555,380 | 2.3% |
| COPY | 398,040 | 0.6% |
| LOAD_FAST_LOAD_FAST | 263,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 12,968,980 | 19.2% |
| LOAD_FAST | 11,776,240 | 17.5% |
| LOAD_GLOBAL_MODULE | 11,343,520 | 16.8% |
| RETURN_VALUE | 7,694,800 | 11.4% |
| STORE_FAST | 3,510,960 | 5.2% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,656,940 | 72.2% |
| ENTER_EXECUTOR | 2,713,300 | 13.4% |
| LOAD_GLOBAL_MODULE | 1,051,960 | 5.2% |
| LOAD_ATTR_INSTANCE_VALUE | 908,560 | 4.5% |
| LOAD_FAST_LOAD_FAST | 906,160 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 14,734,440 | 72.6% |
| LOAD_FAST | 4,853,960 | 23.9% |
| LOAD_FAST_LOAD_FAST | 648,940 | 3.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 58,120 | 0.3% |
| CALL | 840 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 66.7% |
| LOAD_ATTR | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,480 | 99.6% |
| LOAD_ATTR | 120 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 30,600 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,572,720 | 40.0% |
| POP_TOP | 1,301,600 | 33.1% |
| CALL_LIST_APPEND | 654,000 | 16.6% |
| ENTER_EXECUTOR | 263,340 | 6.7% |
| STORE_ATTR_INSTANCE_VALUE | 127,960 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,228,340 | 56.6% |
| LOAD_GLOBAL_MODULE | 1,700,680 | 43.2% |
| LOAD_CONST | 6,360 | 0.2% |
| LOAD_GLOBAL | 220 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 11,343,520 | 55.4% |
| POP_JUMP_IF_FALSE | 1,941,540 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 1,700,680 | 8.3% |
| STORE_ATTR_INSTANCE_VALUE | 1,690,640 | 8.3% |
| STORE_FAST | 1,185,400 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 13,008,520 | 63.5% |
| LOAD_ATTR | 3,119,660 | 15.2% |
| LOAD_FAST | 1,845,620 | 9.0% |
| CALL | 1,067,400 | 5.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,051,960 | 5.1% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,700,680 | 100.0% |
| LOAD_SUPER_ATTR | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 788,420 | 46.4% |
| LOAD_FAST | 520,900 | 30.6% |
| LOAD_FAST_LOAD_FAST | 263,620 | 15.5% |
| CALL_PY_EXACT_ARGS | 127,960 | 7.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 20,496,120 | 80.2% |
| CALL_BOUND_METHOD_EXACT_ARGS | 3,351,160 | 13.1% |
| COPY_FREE_VARS | 1,700,960 | 6.7% |
| CACHE | 1,260 | 0.0% |
| CALL | 860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,855,200 | 85.5% |
| LOAD_GLOBAL_BUILTIN | 1,572,720 | 6.2% |
| LOAD_GLOBAL_MODULE | 1,049,320 | 4.1% |
| RETURN_CONST | 546,720 | 2.1% |
| LOAD_FAST_LOAD_FAST | 513,260 | 2.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,115,900 | 42.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,501,840 | 24.0% |
| LOAD_FAST_LOAD_FAST | 3,375,400 | 23.2% |
| RETURN_VALUE | 1,162,420 | 8.0% |
| SWAP | 398,040 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,977,520 | 41.0% |
| LOAD_FAST | 4,167,940 | 28.6% |
| LOAD_GLOBAL_MODULE | 1,690,640 | 11.6% |
| LOAD_CONST | 1,304,160 | 8.9% |
| LOAD_FAST_LOAD_FAST | 1,029,020 | 7.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,686,320 | 54.6% |
| COPY | 1,930,080 | 22.5% |
| LOAD_ATTR_INSTANCE_VALUE | 1,164,680 | 13.6% |
| RETURN_CONST | 797,300 | 9.3% |
| LOAD_FAST | 10,160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,573,300 | 64.9% |
| POP_JUMP_IF_TRUE | 2,880,100 | 33.5% |
| UNARY_NOT | 135,660 | 1.6% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 2,223,120 | 100.0% |
| TO_BOOL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,223,240 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 98.4% |
| UNPACK_SEQUENCE | 20 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,260 | 100.0% |


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
|     deferred | 173,640 | 2.7% |
|          hit | 6,310,160 | 97.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 27.9% |
| Failure | 620 | 72.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 420 | 67.7% |
| true divide other | 200 | 32.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,180 | 37.4% |
|          hit | 5,100 | 60.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 9.1% |
| Failure | 200 | 90.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 200 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,930,600 | 5.1% |
|          hit | 32,502,840 | 86.4% |
|         miss | 3,127,440 | 8.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 61,240 | 95.7% |
| Failure | 2,720 | 4.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class mutable | 1,520 | 55.9% |
| operator wrapper | 820 | 30.1% |
| wrong number arguments | 220 | 8.1% |
| other | 100 | 3.7% |
| cfunc noargs | 60 | 2.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,583,380 | 8.6% |
|          hit | 16,782,320 | 91.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 420 | 23.1% |
| Failure | 1,400 | 76.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 1,240 | 88.6% |
| float long | 100 | 7.1% |
| different types | 60 | 4.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 260 | 0.0% |
|          hit | 1,861,800 | 100.0% |

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
|     deferred | 7,752,700 | 7.1% |
|          hit | 95,594,720 | 88.0% |
|         miss | 5,116,740 | 4.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100,020 | 92.3% |
| Failure | 8,380 | 7.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 3,280 | 39.1% |
| mutable class | 2,660 | 31.7% |
| class method obj | 2,440 | 29.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,040 | 0.0% |
|          hit | 24,425,700 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,040 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 220 | 0.0% |
|          hit | 1,700,900 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 100.0% |
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

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 368,934,881,474,191,015,920 | 2,531,396,791,860,438.5% |
|          hit | 13,637,440 | 93.6% |
|         miss | 934,720 | 6.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 18,560 | 99.8% |
| Failure | 40 | 0.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in keys | 40 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 640 | 0.0% |
|          hit | 10,812,300 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 640 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 1.5% |
|          hit | 1,260 | 96.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 175,998,280 | 39.2% |
| Not specialized | 37,585,980 | 8.4% |
| Specialized hits | 225,831,980 | 50.3% |
| Specialized misses | 9,180,660 | 2.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR | 368,934,881,474,191,015,920 | 100.0% |
| LOAD_ATTR | 7,752,700 | 0.0% |
| CALL | 1,930,600 | 0.0% |
| COMPARE_OP | 1,583,380 | 0.0% |
| BINARY_OP | 173,640 | 0.0% |
| BINARY_SUBSCR | 3,180 | 0.0% |
| LOAD_GLOBAL | 2,040 | 0.0% |
| TO_BOOL | 640 | 0.0% |
| FOR_ITER | 260 | 0.0% |
| LOAD_SUPER_ATTR | 220 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 3,090,060 | 33.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,026,680 | 22.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,592,840 | 17.3% |
| CALL_PY_EXACT_ARGS | 1,529,420 | 16.7% |
| STORE_ATTR_INSTANCE_VALUE | 934,720 | 10.2% |
| CALL_METHOD_DESCRIPTOR_O | 5,180 | 0.1% |
| RESUME | 1,760 | 0.0% |
| RESUME_CHECK | 1,760 | 0.0% |
| CACHE | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 130,820 | 0.5% |
| Calls to Python functions inlined | 25,420,740 | 99.5% |
| Calls via PyEval_EvalFrame (total) | 130,820 | 0.5% |
| Calls via PyEval_EvalFrame (vector) | 130,820 | 0.5% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 130,820 | 0.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 64,844,500 | 253.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 965,160 | 6.6% |
| Frees to freelist | 965,900 |  |
| Allocations | 13,678,900 | 93.4% |
| Allocations to 512 bytes | 13,678,620 | 93.4% |
| Allocations to 4 kbytes | 280 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 14,713,137 |  |
| New values | 129,540 |  |
| Interpreter increfs | 477,583,040 | 93.3% |
| Interpreter decrefs | 500,149,000 | 95.2% |
| Increfs | 34,066,929 | 6.7% |
| Decrefs | 25,042,911 | 4.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 19,073,264 |  |
| Method cache misses | 180,636 |  |
| Method cache collisions | 179,800 |  |
| Method cache dunder hits | 383,822 |  |
| Method cache dunder misses | 198 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 1,520 | 281,200 | 11,685,800 |
| 1 | 140 | 810,320 | 9,902,520 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 440 |  |
| Traces created | 440 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 100 | 22.7% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 40 | 9.1% |
| Recursive call | 0 | 0.0% |
| Traces executed | 7,215,840 |  |
| Uops executed | 1,460,593,040 | 202.41 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 4.5% |
| <= 32 | 140 | 31.8% |
| <= 64 | 80 | 18.2% |
| <= 128 | 200 | 45.5% |


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
| <= 16 | 20 | 4.5% |
| <= 32 | 140 | 31.8% |
| <= 64 | 120 | 27.3% |
| <= 128 | 160 | 36.4% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 1,280 | 0.0% |
| <= 8 | 2,639,040 | 36.6% |
| <= 16 | 3,479,560 | 48.2% |
| <= 32 | 279,480 | 3.9% |
| <= 64 | 303,760 | 4.2% |
| <= 128 | 379,600 | 5.3% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 5,120 | 0.1% |
| <= 8,192 | 0 | 0.0% |
| <= 16,384 | 128,000 | 1.8% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 325,209,260 | 22.3% | 22.3% |  |
| _GUARD_TYPE_VERSION | 122,904,060 | 8.4% | 30.7% | 2.2% |
| LOAD_FAST | 102,237,560 | 7.0% | 37.7% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 66,827,240 | 4.6% | 42.3% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 66,827,240 | 4.6% | 46.8% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 40,391,600 | 2.8% | 49.6% |  |
| _GUARD_KEYS_VERSION | 40,391,600 | 2.8% | 52.4% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 40,391,600 | 2.8% | 55.1% |  |
| RESUME_CHECK | 40,267,400 | 2.8% | 57.9% |  |
| _CHECK_PEP_523 | 40,267,400 | 2.8% | 60.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 40,267,400 | 2.8% | 63.4% |  |
| _CHECK_STACK_SPACE | 40,267,400 | 2.8% | 66.2% |  |
| _INIT_CALL_PY_EXACT_ARGS | 40,267,400 | 2.8% | 68.9% |  |
| _PUSH_FRAME | 40,267,400 | 2.8% | 71.7% |  |
| _SAVE_RETURN_OFFSET | 40,267,400 | 2.8% | 74.4% |  |
| _POP_FRAME | 39,206,740 | 2.7% | 77.1% |  |
| COMPARE_OP_INT | 27,120,060 | 1.9% | 79.0% |  |
| _POP_JUMP_IF_FALSE | 26,869,820 | 1.8% | 80.8% |  |
| _GUARD_GLOBALS_VERSION | 26,744,340 | 1.8% | 82.6% |  |
| _LOAD_GLOBAL_MODULE | 26,744,340 | 1.8% | 84.5% |  |
| _CHECK_ATTR_CLASS | 26,363,800 | 1.8% | 86.3% |  |
| _LOAD_ATTR_CLASS | 26,363,800 | 1.8% | 88.1% |  |
| _POP_JUMP_IF_TRUE | 21,113,780 | 1.4% | 89.5% |  |
| _ITER_CHECK_LIST | 19,002,840 | 1.3% | 90.8% |  |
| _IS_ITER_EXHAUSTED_LIST | 19,002,840 | 1.3% | 92.1% |  |
| STORE_FAST | 18,043,000 | 1.2% | 93.4% |  |
| _ITER_NEXT_LIST | 16,987,160 | 1.2% | 94.5% |  |
| POP_TOP | 14,872,760 | 1.0% | 95.5% |  |
| LOAD_CONST | 14,501,680 | 1.0% | 96.5% |  |
| _JUMP_TO_TOP | 13,459,800 | 0.9% | 97.5% |  |
| _GUARD_DORV_VALUES | 12,971,920 | 0.9% | 98.3% |  |
| _STORE_ATTR_INSTANCE_VALUE | 12,971,920 | 0.9% | 99.2% |  |
| _EXIT_TRACE | 3,601,040 | 0.2% | 99.5% |  |
| _COMPARE_OP | 1,171,600 | 0.1% | 99.6% |  |
| _LOAD_ATTR | 1,027,920 | 0.1% | 99.6% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 901,500 | 0.1% | 99.7% | 100.0% |
| _ITER_CHECK_RANGE | 689,100 | 0.0% | 99.7% |  |
| _IS_ITER_EXHAUSTED_RANGE | 689,100 | 0.0% | 99.8% |  |
| _ITER_NEXT_RANGE | 677,520 | 0.0% | 99.8% |  |
| TO_BOOL_BOOL | 511,220 | 0.0% | 99.9% |  |
| _GUARD_BOTH_INT | 500,560 | 0.0% | 99.9% |  |
| _BINARY_OP | 254,120 | 0.0% | 99.9% |  |
| _BINARY_OP_MULTIPLY_INT | 250,280 | 0.0% | 99.9% |  |
| _BINARY_OP_ADD_INT | 250,280 | 0.0% | 100.0% |  |
| _BINARY_SUBSCR | 250,280 | 0.0% | 100.0% |  |
| GET_ITER | 172,220 | 0.0% | 100.0% |  |
| _CHECK_CALL_BOUND_METHOD_EXACT_ARGS | 126,420 | 0.0% | 100.0% |  |
| _INIT_CALL_BOUND_METHOD_EXACT_ARGS | 126,420 | 0.0% | 100.0% |  |
| PUSH_NULL | 900 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 40 |
| CALL_ALLOC_AND_ENTER_INIT | 20 |
| CALL_LIST_APPEND | 20 |


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
Stats gathered on: 2023-11-08
