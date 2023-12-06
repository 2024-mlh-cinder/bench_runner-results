
# Pystats results

- benchmark: deltablue
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 100,252,000 | 21.5% | 21.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 68,762,540 | 14.7% | 36.2% | 3.0% |
| RESUME_CHECK | 26,436,520 | 5.7% | 41.9% | 0.0% |
| CALL_PY_EXACT_ARGS | 22,197,300 | 4.8% | 46.7% | 6.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 21,306,740 | 4.6% | 51.2% | 14.5% |
| LOAD_GLOBAL_MODULE | 21,124,280 | 4.5% | 55.8% |  |
| POP_JUMP_IF_FALSE | 20,201,920 | 4.3% | 60.1% |  |
| COMPARE_OP_INT | 17,539,100 | 3.8% | 63.9% |  |
| RETURN_VALUE | 15,073,020 | 3.2% | 67.1% |  |
| STORE_ATTR_INSTANCE_VALUE | 14,572,220 | 3.1% | 70.2% | 6.4% |
| POP_TOP | 13,705,880 | 2.9% | 73.2% |  |
| LOAD_ATTR_CLASS | 13,515,200 | 2.9% | 76.1% |  |
| RETURN_CONST | 12,702,060 | 2.7% | 78.8% |  |
| STORE_FAST | 12,464,640 | 2.7% | 81.5% |  |
| LOAD_ATTR | 8,889,460 | 1.9% | 83.4% |  |
| TO_BOOL_BOOL | 8,842,280 | 1.9% | 85.3% |  |
| LOAD_FAST_LOAD_FAST | 8,567,960 | 1.8% | 87.1% |  |
| ENTER_EXECUTOR | 6,716,080 | 1.4% | 88.5% |  |
| POP_JUMP_IF_TRUE | 6,250,240 | 1.3% | 89.9% |  |
| LOAD_CONST | 4,368,080 | 0.9% | 90.8% |  |
| LOAD_GLOBAL_BUILTIN | 3,935,600 | 0.8% | 91.7% |  |
| BINARY_OP_ADD_INT | 3,582,620 | 0.8% | 92.4% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 3,477,580 | 0.7% | 93.2% |  |
| BINARY_OP_MULTIPLY_INT | 3,183,300 | 0.7% | 93.9% |  |
| CALL_LIST_APPEND | 2,998,820 | 0.6% | 94.5% |  |
| COMPARE_OP | 2,757,100 | 0.6% | 95.1% |  |
| COPY | 2,328,320 | 0.5% | 95.6% |  |
| CALL_LEN | 2,223,240 | 0.5% | 96.1% |  |
| TO_BOOL_INT | 2,223,240 | 0.5% | 96.5% |  |
| CALL | 1,994,560 | 0.4% | 97.0% |  |
| GET_ITER | 1,856,700 | 0.4% | 97.4% |  |
| FOR_ITER_LIST | 1,848,500 | 0.4% | 97.8% |  |
| COPY_FREE_VARS | 1,701,200 | 0.4% | 98.1% |  |
| LOAD_SUPER_ATTR_METHOD | 1,700,900 | 0.4% | 98.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,592,840 | 0.3% | 98.8% | 100.0% |
| POP_JUMP_IF_NONE | 1,434,880 | 0.3% | 99.1% |  |
| JUMP_BACKWARD | 908,860 | 0.2% | 99.3% |  |
| EXIT_INIT_CHECK | 658,940 | 0.1% | 99.5% |  |
| CALL_ALLOC_AND_ENTER_INIT | 658,940 | 0.1% | 99.6% |  |
| BINARY_OP | 428,860 | 0.1% | 99.7% |  |
| SWAP | 398,080 | 0.1% | 99.8% |  |
| JUMP_FORWARD | 257,280 | 0.1% | 99.9% |  |
| BINARY_SUBSCR | 253,920 | 0.1% | 99.9% |  |
| UNARY_NOT | 135,680 | 0.0% | 99.9% |  |
| INTERPRETER_EXIT | 130,820 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_INT | 44,740 | 0.0% | 100.0% |  |
| LOAD_ATTR_SLOT | 30,600 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 13,700 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 11,460 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 5,180 | 0.0% | 100.0% | 100.0% |
| BUILD_CONST_KEY_MAP | 5,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 5,100 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 4,080 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 53,193,260 | 11.4% | 11.4% |
| RESUME_CHECK LOAD_FAST | 22,741,340 | 4.9% | 16.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 21,255,860 | 4.6% | 20.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 15,744,760 | 3.4% | 24.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 15,667,320 | 3.4% | 27.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 14,620,160 | 3.1% | 30.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_CLASS | 13,514,960 | 2.9% | 33.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 13,095,500 | 2.8% | 36.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 12,390,520 | 2.7% | 39.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 12,153,020 | 2.6% | 41.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 11,849,960 | 2.5% | 44.2% |
| LOAD_ATTR_CLASS COMPARE_OP_INT | 11,847,440 | 2.5% | 46.8% |
| RETURN_CONST POP_TOP | 11,112,300 | 2.4% | 49.2% |
| STORE_FAST LOAD_FAST | 9,412,760 | 2.0% | 51.2% |
| LOAD_ATTR_INSTANCE_VALUE RETURN_VALUE | 7,945,460 | 1.7% | 52.9% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 6,115,900 | 1.3% | 54.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 5,977,540 | 1.3% | 55.5% |
| LOAD_ATTR LOAD_FAST | 5,872,500 | 1.3% | 56.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 5,573,340 | 1.2% | 57.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,504,880 | 1.2% | 59.1% |
| RETURN_VALUE TO_BOOL_BOOL | 4,939,540 | 1.1% | 60.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 4,854,000 | 1.0% | 61.2% |
| POP_TOP LOAD_FAST | 4,663,040 | 1.0% | 62.2% |
| RETURN_VALUE STORE_FAST | 4,433,780 | 1.0% | 63.2% |
| COMPARE_OP_INT RETURN_VALUE | 4,380,660 | 0.9% | 64.1% |
| LOAD_FAST LOAD_ATTR | 4,299,760 | 0.9% | 65.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 4,167,980 | 0.9% | 65.9% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 3,510,960 | 0.8% | 66.7% |
| LOAD_ATTR_INSTANCE_VALUE STORE_ATTR_INSTANCE_VALUE | 3,501,840 | 0.8% | 67.4% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 3,477,580 | 0.7% | 68.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,375,440 | 0.7% | 68.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 3,133,280 | 0.7% | 69.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 3,119,680 | 0.7% | 70.2% |
| BINARY_OP_ADD_INT LOAD_FAST | 2,929,900 | 0.6% | 70.9% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 2,929,900 | 0.6% | 71.5% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_ADD_INT | 2,929,880 | 0.6% | 72.1% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 2,929,880 | 0.6% | 72.7% |
| POP_TOP ENTER_EXECUTOR | 2,898,460 | 0.6% | 73.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 2,744,320 | 0.6% | 73.9% |
| LOAD_FAST CALL_LIST_APPEND | 2,740,080 | 0.6% | 74.5% |
| COMPARE_OP POP_JUMP_IF_TRUE | 2,735,420 | 0.6% | 75.1% |
| LOAD_FAST COMPARE_OP_INT | 2,729,560 | 0.6% | 75.7% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 2,713,280 | 0.6% | 76.3% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 2,448,560 | 0.5% | 76.8% |
| LOAD_ATTR_INSTANCE_VALUE CALL_BOUND_METHOD_EXACT_ARGS | 2,448,320 | 0.5% | 77.3% |
| RETURN_VALUE LOAD_FAST | 2,328,320 | 0.5% | 77.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,228,340 | 0.5% | 78.3% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,223,240 | 0.5% | 78.8% |
| LOAD_FAST CALL_LEN | 2,223,120 | 0.5% | 79.3% |
| CALL_LEN TO_BOOL_INT | 2,223,120 | 0.5% | 79.7% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 2,212,020 | 0.5% | 80.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,973,320 | 0.4% | 80.6% |
| POP_TOP RETURN_CONST | 1,958,440 | 0.4% | 81.1% |
| POP_TOP LOAD_FAST_LOAD_FAST | 1,953,280 | 0.4% | 81.5% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 1,941,560 | 0.4% | 81.9% |
| COPY TO_BOOL_BOOL | 1,930,080 | 0.4% | 82.3% |
| FOR_ITER_LIST STORE_FAST | 1,846,800 | 0.4% | 82.7% |
| GET_ITER FOR_ITER_LIST | 1,844,980 | 0.4% | 83.1% |
| LOAD_CONST LOAD_FAST | 1,735,040 | 0.4% | 83.5% |
| COPY_FREE_VARS RESUME_CHECK | 1,700,960 | 0.4% | 83.8% |
| LOAD_FAST LOAD_SUPER_ATTR_METHOD | 1,700,680 | 0.4% | 84.2% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_MODULE | 1,700,680 | 0.4% | 84.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_GLOBAL_MODULE | 1,690,640 | 0.4% | 84.9% |
| LOAD_FAST RETURN_VALUE | 1,689,680 | 0.4% | 85.3% |
| LOAD_ATTR_CLASS LOAD_FAST | 1,667,680 | 0.4% | 85.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,580,440 | 0.3% | 86.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,572,720 | 0.3% | 86.3% |
| LOAD_ATTR LOAD_CONST | 1,568,060 | 0.3% | 86.7% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 1,563,860 | 0.3% | 87.0% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 1,562,820 | 0.3% | 87.3% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST | 1,562,760 | 0.3% | 87.7% |
| RETURN_VALUE LOAD_ATTR_INSTANCE_VALUE | 1,555,400 | 0.3% | 88.0% |
| LOAD_ATTR_INSTANCE_VALUE COPY | 1,543,620 | 0.3% | 88.3% |
| ENTER_EXECUTOR RETURN_CONST | 1,480,340 | 0.3% | 88.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,429,760 | 0.3% | 89.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,313,120 | 0.3% | 89.2% |
| LOAD_FAST GET_ITER | 1,310,800 | 0.3% | 89.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 1,304,160 | 0.3% | 89.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR | 1,302,240 | 0.3% | 90.1% |
| POP_TOP LOAD_GLOBAL_BUILTIN | 1,301,600 | 0.3% | 90.4% |
| CALL_LIST_APPEND RETURN_CONST | 1,296,600 | 0.3% | 90.6% |
| ENTER_EXECUTOR COMPARE_OP | 1,171,540 | 0.3% | 90.9% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 1,164,680 | 0.2% | 91.1% |
| RETURN_VALUE STORE_ATTR_INSTANCE_VALUE | 1,162,440 | 0.2% | 91.4% |
| POP_JUMP_IF_FALSE POP_TOP | 1,157,120 | 0.2% | 91.6% |
| LOAD_GLOBAL_MODULE CALL | 1,067,400 | 0.2% | 91.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_WITH_VALUES | 1,051,960 | 0.2% | 92.1% |
| POP_JUMP_IF_FALSE RETURN_CONST | 1,049,600 | 0.2% | 92.3% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,049,320 | 0.2% | 92.5% |
| LOAD_ATTR LOAD_FAST_LOAD_FAST | 1,029,140 | 0.2% | 92.8% |
| LOAD_FAST_LOAD_FAST CALL_BOUND_METHOD_EXACT_ARGS | 1,029,080 | 0.2% | 93.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 1,029,020 | 0.2% | 93.2% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 912,560 | 0.2% | 93.4% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 912,540 | 0.2% | 93.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 908,560 | 0.2% | 93.8% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 906,160 | 0.2% | 94.0% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 902,740 | 0.2% | 94.2% |
| JUMP_BACKWARD LOAD_FAST | 902,720 | 0.2% | 94.4% |
| CALL STORE_FAST | 802,860 | 0.2% | 94.5% |
| RETURN_CONST TO_BOOL_BOOL | 797,300 | 0.2% | 94.7% |


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
| ENTER_EXECUTOR | 250,240 | 98.6% |
| LOAD_FAST_LOAD_FAST | 3,200 | 1.3% |
| BINARY_SUBSCR | 440 | 0.2% |
| LOAD_ATTR | 20 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 253,360 | 99.8% |
| BINARY_SUBSCR | 440 | 0.2% |
| LOAD_ATTR | 80 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |
| BINARY_SUBSCR_DICT | 20 | 0.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 534,320 | 28.8% |
| CALL_BUILTIN_CLASS | 11,400 | 0.6% |
| CALL | 120 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,844,980 | 99.4% |
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
| RETURN_CONST | 11,112,300 | 81.1% |
| POP_JUMP_IF_FALSE | 1,157,120 | 8.4% |
| CALL | 790,160 | 5.8% |
| RETURN_VALUE | 385,200 | 2.8% |
| POP_JUMP_IF_TRUE | 256,000 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,663,040 | 34.0% |
| ENTER_EXECUTOR | 2,898,460 | 21.1% |
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
| LOAD_ATTR_INSTANCE_VALUE | 7,945,460 | 52.7% |
| COMPARE_OP_INT | 4,380,660 | 29.1% |
| LOAD_FAST | 1,689,680 | 11.2% |
| EXIT_INIT_CHECK | 658,940 | 4.4% |
| POP_JUMP_IF_TRUE | 386,560 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 4,939,540 | 32.8% |
| STORE_FAST | 4,433,780 | 29.4% |
| LOAD_FAST | 2,328,320 | 15.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,555,400 | 10.3% |
| STORE_ATTR_INSTANCE_VALUE | 1,162,440 | 7.7% |


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
| ENTER_EXECUTOR | 254,080 | 59.2% |
| LOAD_FAST | 131,240 | 30.6% |
| LOAD_ATTR_INSTANCE_VALUE | 42,280 | 9.9% |
| BINARY_OP | 860 | 0.2% |
| LOAD_CONST | 320 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 298,300 | 69.6% |
| STORE_FAST | 129,300 | 30.1% |
| BINARY_OP | 860 | 0.2% |
| BINARY_OP_ADD_INT | 100 | 0.0% |
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
| LOAD_FAST | 131,160 | 6.6% |
| CALL | 2,720 | 0.1% |
| LOAD_ATTR | 1,240 | 0.1% |

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
| LOAD_FAST_LOAD_FAST | 1,563,860 | 56.7% |
| ENTER_EXECUTOR | 1,171,540 | 42.5% |
| LOAD_FAST | 10,600 | 0.4% |
| LOAD_ATTR | 7,800 | 0.3% |
| COMPARE_OP | 1,700 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,735,420 | 99.2% |
| POP_JUMP_IF_FALSE | 14,360 | 0.5% |
| STORE_FAST | 5,120 | 0.2% |
| COMPARE_OP | 1,700 | 0.1% |
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
| POP_TOP | 2,898,460 | 43.2% |
| POP_JUMP_IF_TRUE | 2,212,020 | 32.9% |
| CALL_LIST_APPEND | 912,560 | 13.6% |
| POP_JUMP_IF_FALSE | 258,780 | 3.9% |
| POP_JUMP_IF_NONE | 254,380 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 2,713,280 | 40.4% |
| RETURN_CONST | 1,480,340 | 22.0% |
| COMPARE_OP | 1,171,540 | 17.4% |
| LOAD_FAST | 406,360 | 6.1% |
| LOAD_GLOBAL_BUILTIN | 263,320 | 3.9% |


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
| POP_JUMP_IF_FALSE | 902,740 | 99.3% |
| POP_JUMP_IF_TRUE | 2,380 | 0.3% |
| POP_TOP | 1,440 | 0.2% |
| CALL_LIST_APPEND | 1,280 | 0.1% |
| STORE_FAST | 680 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 902,720 | 99.3% |
| FOR_ITER_LIST | 3,400 | 0.4% |
| FOR_ITER_RANGE | 2,100 | 0.2% |
| ENTER_EXECUTOR | 380 | 0.0% |
| FOR_ITER | 260 | 0.0% |


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
| LOAD_FAST | 4,299,760 | 48.4% |
| LOAD_GLOBAL_MODULE | 3,119,680 | 35.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,302,240 | 14.6% |
| ENTER_EXECUTOR | 126,400 | 1.4% |
| LOAD_ATTR_SLOT | 30,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,872,500 | 66.1% |
| LOAD_CONST | 1,568,060 | 17.6% |
| LOAD_FAST_LOAD_FAST | 1,029,140 | 11.6% |
| CALL_ALLOC_AND_ENTER_INIT | 391,440 | 4.4% |
| LOAD_ATTR | 9,540 | 0.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 1,568,060 | 35.9% |
| STORE_ATTR_INSTANCE_VALUE | 1,304,160 | 29.9% |
| LOAD_ATTR_INSTANCE_VALUE | 400,580 | 9.2% |
| LOAD_FAST | 391,760 | 9.0% |
| BINARY_OP_MULTIPLY_INT | 253,400 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,735,040 | 39.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,562,760 | 35.8% |
| BINARY_OP_ADD_INT | 652,640 | 14.9% |
| BINARY_OP_MULTIPLY_INT | 253,360 | 5.8% |
| COMPARE_OP_INT | 130,520 | 3.0% |


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
| RESUME_CHECK | 22,741,340 | 22.7% |
| POP_JUMP_IF_FALSE | 14,620,160 | 14.6% |
| LOAD_ATTR_INSTANCE_VALUE | 12,153,020 | 12.1% |
| STORE_FAST | 9,412,760 | 9.4% |
| LOAD_ATTR | 5,872,500 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 53,193,260 | 53.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 15,667,320 | 15.6% |
| STORE_ATTR_INSTANCE_VALUE | 6,115,900 | 6.1% |
| CALL_PY_EXACT_ARGS | 5,504,880 | 5.5% |
| LOAD_ATTR | 4,299,760 | 4.3% |


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
| STORE_FAST | 1,580,440 | 18.4% |
| LOAD_ATTR | 1,029,140 | 12.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,029,020 | 12.0% |
| POP_JUMP_IF_TRUE | 648,960 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 3,375,440 | 39.4% |
| COMPARE_OP | 1,563,860 | 18.3% |
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
| COMPARE_OP_INT | 12,390,520 | 61.3% |
| TO_BOOL_BOOL | 5,573,340 | 27.6% |
| TO_BOOL_INT | 2,223,240 | 11.0% |
| COMPARE_OP | 14,360 | 0.1% |
| TO_BOOL | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,620,160 | 72.4% |
| LOAD_GLOBAL_MODULE | 1,941,560 | 9.6% |
| POP_TOP | 1,157,120 | 5.7% |
| RETURN_CONST | 1,049,600 | 5.2% |
| JUMP_BACKWARD | 902,740 | 4.5% |


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
| ENTER_EXECUTOR | 254,380 | 17.7% |
| LOAD_GLOBAL_MODULE | 127,960 | 8.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,133,280 | 50.1% |
| COMPARE_OP | 2,735,420 | 43.8% |
| COMPARE_OP_INT | 381,380 | 6.1% |
| TO_BOOL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,744,320 | 43.9% |
| ENTER_EXECUTOR | 2,212,020 | 35.4% |
| LOAD_FAST_LOAD_FAST | 648,960 | 10.4% |
| RETURN_VALUE | 386,560 | 6.2% |
| POP_TOP | 256,000 | 4.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,977,540 | 47.1% |
| POP_TOP | 1,958,440 | 15.4% |
| ENTER_EXECUTOR | 1,480,340 | 11.7% |
| CALL_LIST_APPEND | 1,296,600 | 10.2% |
| POP_JUMP_IF_FALSE | 1,049,600 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 11,112,300 | 87.5% |
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
| RETURN_VALUE | 4,433,780 | 35.6% |
| LOAD_ATTR_INSTANCE_VALUE | 3,510,960 | 28.2% |
| FOR_ITER_LIST | 1,846,800 | 14.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,562,820 | 12.5% |
| CALL | 802,860 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,412,760 | 75.5% |
| LOAD_FAST_LOAD_FAST | 1,580,440 | 12.7% |
| LOAD_GLOBAL_MODULE | 1,313,120 | 10.5% |
| ENTER_EXECUTOR | 133,720 | 1.1% |
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
| LOAD_ATTR_INSTANCE_VALUE | 2,929,880 | 81.8% |
| LOAD_CONST | 652,640 | 18.2% |
| BINARY_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,929,900 | 81.8% |
| SWAP | 398,060 | 11.1% |
| COMPARE_OP_INT | 253,360 | 7.1% |
| CALL_BUILTIN_CLASS | 1,240 | 0.0% |
| COMPARE_OP | 40 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,929,880 | 92.0% |
| LOAD_CONST | 253,360 | 8.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,929,900 | 92.0% |
| LOAD_CONST | 253,400 | 8.0% |


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
| LOAD_FAST | 255,920 | 38.8% |
| LOAD_GLOBAL_MODULE | 8,840 | 1.3% |
| LOAD_CONST | 2,480 | 0.4% |
| CALL | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 658,940 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,448,320 | 70.4% |
| LOAD_FAST_LOAD_FAST | 1,029,080 | 29.6% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,477,580 | 100.0% |


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
| ENTER_EXECUTOR | 912,560 | 30.4% |
| LOAD_GLOBAL_BUILTIN | 654,000 | 21.8% |
| LOAD_GLOBAL_MODULE | 134,280 | 4.5% |
| JUMP_BACKWARD | 1,280 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,562,760 | 98.1% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 15,744,760 | 70.9% |
| LOAD_FAST | 5,504,880 | 24.8% |
| LOAD_FAST_LOAD_FAST | 784,520 | 3.5% |
| LOAD_SUPER_ATTR_METHOD | 127,960 | 0.6% |
| CALL_PY_EXACT_ARGS | 28,700 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 21,255,860 | 95.8% |
| COPY_FREE_VARS | 912,540 | 4.1% |
| CALL_PY_EXACT_ARGS | 28,700 | 0.1% |
| RESUME | 200 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 11,847,440 | 67.5% |
| LOAD_FAST | 2,729,560 | 15.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,448,560 | 14.0% |
| BINARY_OP_ADD_INT | 253,360 | 1.4% |
| LOAD_CONST | 130,520 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,390,520 | 70.6% |
| RETURN_VALUE | 4,380,660 | 25.0% |
| COPY | 386,540 | 2.2% |
| POP_JUMP_IF_TRUE | 381,380 | 2.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,844,980 | 99.8% |
| JUMP_BACKWARD | 3,400 | 0.2% |
| FOR_ITER | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,846,800 | 99.9% |
| LOAD_FAST | 720 | 0.0% |
| RETURN_CONST | 620 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 320 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 11,460 | 83.6% |
| JUMP_BACKWARD | 2,100 | 15.3% |
| FOR_ITER | 140 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 13,660 | 99.7% |
| LOAD_FAST | 40 | 0.3% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,514,960 | 100.0% |
| LOAD_ATTR | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 11,847,440 | 87.7% |
| LOAD_FAST | 1,667,680 | 12.3% |
| COMPARE_OP | 80 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,193,260 | 77.4% |
| LOAD_ATTR_INSTANCE_VALUE | 13,095,500 | 19.0% |
| RETURN_VALUE | 1,555,400 | 2.3% |
| COPY | 398,040 | 0.6% |
| LOAD_FAST_LOAD_FAST | 263,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 13,095,500 | 19.0% |
| LOAD_FAST | 12,153,020 | 17.7% |
| LOAD_GLOBAL_MODULE | 11,849,960 | 17.2% |
| RETURN_VALUE | 7,945,460 | 11.6% |
| STORE_FAST | 3,510,960 | 5.1% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,667,320 | 73.5% |
| ENTER_EXECUTOR | 2,713,280 | 12.7% |
| LOAD_GLOBAL_MODULE | 1,051,960 | 4.9% |
| LOAD_ATTR_INSTANCE_VALUE | 908,560 | 4.3% |
| LOAD_FAST_LOAD_FAST | 906,160 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 15,744,760 | 73.9% |
| LOAD_FAST | 4,854,000 | 22.8% |
| LOAD_FAST_LOAD_FAST | 648,940 | 3.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 58,200 | 0.3% |
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
| ENTER_EXECUTOR | 263,320 | 6.7% |
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
| LOAD_ATTR_INSTANCE_VALUE | 11,849,960 | 56.1% |
| POP_JUMP_IF_FALSE | 1,941,560 | 9.2% |
| LOAD_GLOBAL_BUILTIN | 1,700,680 | 8.1% |
| STORE_ATTR_INSTANCE_VALUE | 1,690,640 | 8.0% |
| STORE_FAST | 1,313,120 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 13,514,960 | 64.0% |
| LOAD_ATTR | 3,119,680 | 14.8% |
| LOAD_FAST | 1,973,320 | 9.3% |
| CALL | 1,067,400 | 5.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,051,960 | 5.0% |


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
| CALL_PY_EXACT_ARGS | 21,255,860 | 80.4% |
| CALL_BOUND_METHOD_EXACT_ARGS | 3,477,580 | 13.2% |
| COPY_FREE_VARS | 1,700,960 | 6.4% |
| CACHE | 1,260 | 0.0% |
| CALL | 860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,741,340 | 86.0% |
| LOAD_GLOBAL_BUILTIN | 1,572,720 | 5.9% |
| LOAD_GLOBAL_MODULE | 1,049,320 | 4.0% |
| RETURN_CONST | 546,740 | 2.1% |
| LOAD_FAST_LOAD_FAST | 513,260 | 1.9% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,115,900 | 42.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,501,840 | 24.0% |
| LOAD_FAST_LOAD_FAST | 3,375,440 | 23.2% |
| RETURN_VALUE | 1,162,440 | 8.0% |
| SWAP | 398,040 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,977,540 | 41.0% |
| LOAD_FAST | 4,167,980 | 28.6% |
| LOAD_GLOBAL_MODULE | 1,690,640 | 11.6% |
| LOAD_CONST | 1,304,160 | 8.9% |
| LOAD_FAST_LOAD_FAST | 1,029,020 | 7.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,939,540 | 55.9% |
| COPY | 1,930,080 | 21.8% |
| LOAD_ATTR_INSTANCE_VALUE | 1,164,680 | 13.2% |
| RETURN_CONST | 797,300 | 9.0% |
| LOAD_FAST | 10,160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,573,340 | 63.0% |
| POP_JUMP_IF_TRUE | 3,133,280 | 35.4% |
| UNARY_NOT | 135,660 | 1.5% |


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
|     deferred | 427,760 | 5.9% |
|          hit | 6,810,720 | 94.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 21.8% |
| Failure | 860 | 78.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 660 | 76.7% |
| true divide other | 200 | 23.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 253,460 | 97.9% |
|          hit | 5,100 | 2.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 4.3% |
| Failure | 440 | 95.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 440 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,930,520 | 5.0% |
|          hit | 33,511,340 | 86.7% |
|         miss | 3,131,600 | 8.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 61,320 | 95.8% |
| Failure | 2,720 | 4.2% |

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
|     deferred | 2,754,980 | 13.6% |
|          hit | 17,539,100 | 86.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 420 | 19.8% |
| Failure | 1,700 | 80.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| baseobject | 1,160 | 68.2% |
| different types | 440 | 25.9% |
| float long | 100 | 5.9% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 260 | 0.0% |
|          hit | 1,862,200 | 100.0% |

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
|     deferred | 8,780,500 | 7.8% |
|          hit | 98,492,180 | 87.5% |
|         miss | 5,123,020 | 4.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100,140 | 91.9% |
| Failure | 8,820 | 8.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 3,620 | 41.0% |
| mutable class | 2,660 | 30.2% |
| class method obj | 2,540 | 28.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,040 | 0.0% |
|          hit | 25,059,880 | 100.0% |

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
|     deferred | 368,934,881,474,191,015,920 | 2,531,386,370,601,307.0% |
|          hit | 13,637,500 | 93.6% |
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
|          hit | 11,065,520 | 100.0% |

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
| Basic | 182,238,060 | 39.1% |
| Not specialized | 42,219,500 | 9.1% |
| Specialized hits | 232,642,880 | 49.9% |
| Specialized misses | 9,191,100 | 2.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR | 368,934,881,474,191,015,920 | 100.0% |
| LOAD_ATTR | 8,780,500 | 0.0% |
| COMPARE_OP | 2,754,980 | 0.0% |
| CALL | 1,930,520 | 0.0% |
| BINARY_OP | 427,760 | 0.0% |
| BINARY_SUBSCR | 253,460 | 0.0% |
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
| LOAD_ATTR_METHOD_WITH_VALUES | 3,094,220 | 33.7% |
| LOAD_ATTR_INSTANCE_VALUE | 2,028,800 | 22.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,592,840 | 17.3% |
| CALL_PY_EXACT_ARGS | 1,533,580 | 16.7% |
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
| Calls to Python functions inlined | 26,306,900 | 99.5% |
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
| Frames pushed | 64,840,420 | 245.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 965,160 | 6.6% |
| Frees to freelist | 965,900 |  |
| Allocations | 13,678,840 | 93.4% |
| Allocations to 512 bytes | 13,678,700 | 93.4% |
| Allocations to 4 kbytes | 140 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 14,713,144 |  |
| New values | 129,540 |  |
| Interpreter increfs | 477,077,120 | 93.4% |
| Interpreter decrefs | 499,649,240 | 95.3% |
| Increfs | 33,918,072 | 6.6% |
| Decrefs | 24,887,904 | 4.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 19,255,556 |  |
| Method cache misses | 5,164 |  |
| Method cache collisions | 4,299 |  |
| Method cache dunder hits | 383,949 |  |
| Method cache dunder misses | 311 |  |


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
| Optimization attempts | 53,420 |  |
| Traces created | 380 | 0.7% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 20 | 0.0% |
| Trace too short | 53,040 | 99.3% |
| Inner loop found | 20 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 6,716,080 |  |
| Uops executed | 1,419,841,980 | 211.41 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 200 | 52.6% |
| <= 32 | 40 | 10.5% |
| <= 64 | 40 | 10.5% |
| <= 128 | 100 | 26.3% |


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
| <= 16 | 220 | 57.9% |
| <= 32 | 20 | 5.3% |
| <= 64 | 60 | 15.8% |
| <= 128 | 80 | 21.1% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 1,280 | 0.0% |
| <= 8 | 1,891,780 | 28.2% |
| <= 16 | 4,262,360 | 63.5% |
| <= 32 | 0 | 0.0% |
| <= 64 | 303,700 | 4.5% |
| <= 128 | 126,400 | 1.9% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 2,560 | 0.0% |
| <= 8,192 | 0 | 0.0% |
| <= 16,384 | 128,000 | 1.9% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| LOAD_ATTR | 53,080 |
| COMPARE_OP | 140 |
| BINARY_SUBSCR | 40 |
| BINARY_OP | 40 |
| CALL | 20 |


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
Stats gathered on: 2023-11-02
