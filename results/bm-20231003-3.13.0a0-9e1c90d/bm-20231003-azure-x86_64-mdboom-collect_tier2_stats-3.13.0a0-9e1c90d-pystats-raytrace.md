
# Pystats results

- benchmark: raytrace
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 587,738,340 | 22.7% | 22.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 391,763,220 | 15.1% | 37.8% | 0.1% |
| RESUME_CHECK | 172,022,640 | 6.6% | 44.4% |  |
| RETURN_VALUE | 141,958,140 | 5.5% | 49.9% |  |
| LOAD_FAST_LOAD_FAST | 140,516,640 | 5.4% | 55.3% |  |
| BINARY_OP_MULTIPLY_FLOAT | 129,093,900 | 5.0% | 60.3% | 5.4% |
| CALL_PY_EXACT_ARGS | 119,576,560 | 4.6% | 64.9% | 2.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 117,702,520 | 4.5% | 69.5% | 2.5% |
| STORE_ATTR_INSTANCE_VALUE | 96,107,880 | 3.7% | 73.2% | 0.0% |
| BINARY_OP_ADD_FLOAT | 69,208,300 | 2.7% | 75.8% | 8.7% |
| RETURN_CONST | 63,452,700 | 2.4% | 78.3% |  |
| STORE_FAST | 54,722,400 | 2.1% | 80.4% |  |
| BINARY_OP | 54,501,600 | 2.1% | 82.5% |  |
| BINARY_OP_SUBTRACT_FLOAT | 50,859,000 | 2.0% | 84.5% | 29.7% |
| LOAD_GLOBAL_MODULE | 44,451,880 | 1.7% | 86.2% |  |
| LOAD_CONST | 41,072,820 | 1.6% | 87.8% |  |
| EXIT_INIT_CHECK | 33,388,200 | 1.3% | 89.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 33,388,200 | 1.3% | 90.3% |  |
| POP_JUMP_IF_FALSE | 32,280,780 | 1.2% | 91.6% |  |
| POP_TOP | 32,090,820 | 1.2% | 92.8% |  |
| INTERPRETER_EXIT | 19,112,340 | 0.7% | 93.6% |  |
| TO_BOOL_BOOL | 18,511,860 | 0.7% | 94.3% |  |
| ENTER_EXECUTOR | 16,037,320 | 0.6% | 94.9% |  |
| BINARY_OP_MULTIPLY_INT | 13,592,880 | 0.5% | 95.4% | 63.4% |
| COMPARE_OP | 12,344,560 | 0.5% | 95.9% |  |
| BUILD_TUPLE | 8,288,040 | 0.3% | 96.2% |  |
| CALL_BUILTIN_O | 7,703,580 | 0.3% | 96.5% |  |
| PUSH_NULL | 7,609,740 | 0.3% | 96.8% |  |
| LIST_APPEND | 7,327,200 | 0.3% | 97.1% |  |
| LOAD_GLOBAL_BUILTIN | 7,108,800 | 0.3% | 97.4% |  |
| LOAD_ATTR_MODULE | 7,009,600 | 0.3% | 97.6% |  |
| POP_JUMP_IF_NOT_NONE | 6,802,080 | 0.3% | 97.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 6,693,900 | 0.3% | 98.1% |  |
| CALL | 6,416,740 | 0.2% | 98.4% |  |
| BINARY_OP_SUBTRACT_INT | 4,877,700 | 0.2% | 98.6% | 7.2% |
| POP_JUMP_IF_TRUE | 3,218,580 | 0.1% | 98.7% |  |
| BINARY_OP_ADD_INT | 3,178,800 | 0.1% | 98.8% |  |
| GET_ITER | 3,112,020 | 0.1% | 99.0% |  |
| FOR_ITER_LIST | 3,111,720 | 0.1% | 99.1% |  |
| UNARY_NEGATIVE | 2,650,380 | 0.1% | 99.2% |  |
| COMPARE_OP_FLOAT | 1,964,460 | 0.1% | 99.2% |  |
| STORE_FAST_STORE_FAST | 1,875,840 | 0.1% | 99.3% |  |
| BUILD_LIST | 1,836,120 | 0.1% | 99.4% |  |
| SWAP | 1,831,800 | 0.1% | 99.5% |  |
| LOAD_FAST_AND_CLEAR | 1,831,800 | 0.1% | 99.5% |  |
| STORE_SUBSCR | 1,800,480 | 0.1% | 99.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,555,860 | 0.1% | 99.7% |  |
| TO_BOOL | 1,530,440 | 0.1% | 99.7% |  |
| NOP | 1,511,880 | 0.1% | 99.8% |  |
| COMPARE_OP_INT | 919,980 | 0.0% | 99.8% |  |
| LOAD_ATTR | 832,520 | 0.0% | 99.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 616,320 | 0.0% | 99.9% |  |
| CALL_LIST_APPEND | 614,760 | 0.0% | 99.9% |  |
| CALL_FUNCTION_EX | 600,180 | 0.0% | 99.9% |  |
| LIST_EXTEND | 600,060 | 0.0% | 99.9% |  |
| CALL_INTRINSIC_1 | 600,060 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NONE | 338,340 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 319,980 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 231,420 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,560 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 560 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 560 | 0.0% | 100.0% |  |
| CALL_KW | 420 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 300 | 0.0% | 100.0% |  |
| STORE_ATTR | 280 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 280 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 180 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 60 | 0.0% | 100.0% |  |
| DICT_MERGE | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| BUILD_MAP | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 363,429,940 | 14.0% | 14.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 173,728,020 | 6.7% | 20.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 119,521,920 | 4.6% | 25.3% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_FLOAT | 118,163,280 | 4.6% | 29.9% |
| RESUME_CHECK LOAD_FAST | 103,860,420 | 4.0% | 33.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 100,941,320 | 3.9% | 37.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 88,383,160 | 3.4% | 41.2% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 62,291,040 | 2.4% | 43.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 54,995,040 | 2.1% | 45.7% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 52,575,180 | 2.0% | 47.8% |
| STORE_FAST LOAD_FAST | 48,312,300 | 1.9% | 49.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 41,079,420 | 1.6% | 51.2% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 38,641,980 | 1.5% | 52.7% |
| BINARY_OP_ADD_FLOAT LOAD_FAST | 35,208,720 | 1.4% | 54.1% |
| RETURN_VALUE RETURN_VALUE | 34,178,400 | 1.3% | 55.4% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 33,984,720 | 1.3% | 56.7% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 33,476,280 | 1.3% | 58.0% |
| RETURN_CONST EXIT_INIT_CHECK | 33,388,200 | 1.3% | 59.3% |
| EXIT_INIT_CHECK RETURN_VALUE | 33,388,200 | 1.3% | 60.6% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 33,388,200 | 1.3% | 61.8% |
| LOAD_FAST RETURN_VALUE | 32,788,680 | 1.3% | 63.1% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP | 32,650,260 | 1.3% | 64.4% |
| RETURN_VALUE POP_TOP | 31,464,180 | 1.2% | 65.6% |
| POP_TOP LOAD_FAST | 30,592,560 | 1.2% | 66.8% |
| BINARY_OP_ADD_FLOAT RETURN_VALUE | 30,513,000 | 1.2% | 67.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 30,337,720 | 1.2% | 69.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 28,322,300 | 1.1% | 70.2% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_SUBTRACT_FLOAT | 27,452,940 | 1.1% | 71.3% |
| BINARY_OP_SUBTRACT_FLOAT LOAD_FAST | 27,133,200 | 1.0% | 72.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 20,028,300 | 0.8% | 73.1% |
| BINARY_OP CALL_ALLOC_AND_ENTER_INIT | 19,910,120 | 0.8% | 73.8% |
| CACHE RESUME_CHECK | 19,112,340 | 0.7% | 74.6% |
| RETURN_VALUE STORE_FAST | 19,013,460 | 0.7% | 75.3% |
| RETURN_VALUE INTERPRETER_EXIT | 18,511,860 | 0.7% | 76.0% |
| RETURN_CONST TO_BOOL_BOOL | 18,511,860 | 0.7% | 76.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 18,511,860 | 0.7% | 77.5% |
| LOAD_FAST LOAD_CONST | 18,178,560 | 0.7% | 78.2% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 17,957,080 | 0.7% | 78.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 17,871,900 | 0.7% | 79.5% |
| RESUME_CHECK RETURN_CONST | 17,871,900 | 0.7% | 80.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 15,577,920 | 0.6% | 80.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 15,234,840 | 0.6% | 81.4% |
| LOAD_CONST COMPARE_OP | 12,341,520 | 0.5% | 81.9% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 12,297,520 | 0.5% | 82.4% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_WITH_VALUES | 11,961,060 | 0.5% | 82.8% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 11,781,120 | 0.5% | 83.3% |
| COMPARE_OP POP_JUMP_IF_FALSE | 11,727,360 | 0.5% | 83.7% |
| BINARY_OP STORE_FAST | 11,048,680 | 0.4% | 84.2% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 10,767,780 | 0.4% | 84.6% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 10,767,420 | 0.4% | 85.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 10,767,420 | 0.4% | 85.4% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 10,737,480 | 0.4% | 85.8% |
| BINARY_OP_SUBTRACT_FLOAT BINARY_OP_SUBTRACT_FLOAT | 10,737,420 | 0.4% | 86.2% |
| POP_JUMP_IF_FALSE RETURN_CONST | 10,355,460 | 0.4% | 86.6% |
| BINARY_OP LOAD_FAST | 9,238,980 | 0.4% | 87.0% |
| BINARY_OP_MULTIPLY_FLOAT CALL_ALLOC_AND_ENTER_INIT | 8,978,540 | 0.3% | 87.3% |
| LOAD_CONST LOAD_FAST | 8,676,120 | 0.3% | 87.7% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_FLOAT | 8,437,640 | 0.3% | 88.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 7,724,440 | 0.3% | 88.3% |
| RETURN_VALUE LOAD_FAST | 7,330,740 | 0.3% | 88.6% |
| LOAD_FAST BUILD_TUPLE | 7,327,260 | 0.3% | 88.9% |
| LIST_APPEND ENTER_EXECUTOR | 7,327,200 | 0.3% | 89.2% |
| BUILD_TUPLE LIST_APPEND | 7,327,200 | 0.3% | 89.4% |
| RETURN_VALUE BINARY_OP | 7,233,180 | 0.3% | 89.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_CONST | 7,144,620 | 0.3% | 90.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 7,009,540 | 0.3% | 90.3% |
| PUSH_NULL LOAD_FAST | 7,009,500 | 0.3% | 90.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 7,009,480 | 0.3% | 90.8% |
| BINARY_OP CALL_PY_EXACT_ARGS | 6,824,640 | 0.3% | 91.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 6,807,300 | 0.3% | 91.3% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 6,802,080 | 0.3% | 91.6% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 6,693,900 | 0.3% | 91.8% |
| RETURN_VALUE CALL_BUILTIN_O | 6,593,220 | 0.3% | 92.1% |
| CALL_BUILTIN_O RETURN_VALUE | 6,593,220 | 0.3% | 92.4% |
| LOAD_FAST BINARY_OP | 6,490,300 | 0.3% | 92.6% |
| RETURN_CONST LOAD_FAST | 6,206,880 | 0.2% | 92.8% |
| RETURN_VALUE CALL_PY_EXACT_ARGS | 5,610,360 | 0.2% | 93.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_GLOBAL_MODULE | 4,970,880 | 0.2% | 93.3% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 4,970,280 | 0.2% | 93.4% |
| POP_JUMP_IF_NOT_NONE ENTER_EXECUTOR | 4,929,480 | 0.2% | 93.6% |
| RETURN_CONST STORE_FAST | 4,744,500 | 0.2% | 93.8% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 3,920,040 | 0.2% | 94.0% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_ADD_FLOAT | 3,919,980 | 0.2% | 94.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 3,711,900 | 0.1% | 94.3% |
| CALL CALL | 3,601,640 | 0.1% | 94.4% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 3,600,000 | 0.1% | 94.5% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 3,297,240 | 0.1% | 94.7% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 3,056,820 | 0.1% | 94.8% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 2,898,180 | 0.1% | 94.9% |
| BINARY_SUBSCR_TUPLE_INT LOAD_FAST_LOAD_FAST | 2,879,820 | 0.1% | 95.0% |
| BINARY_SUBSCR_TUPLE_INT BINARY_OP | 2,847,420 | 0.1% | 95.1% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_SUBTRACT_INT | 2,755,080 | 0.1% | 95.2% |
| BINARY_OP_SUBTRACT_INT CALL_ALLOC_AND_ENTER_INIT | 2,658,120 | 0.1% | 95.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,593,560 | 0.1% | 95.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,494,440 | 0.1% | 95.5% |
| BINARY_OP RETURN_VALUE | 2,249,280 | 0.1% | 95.6% |
| ENTER_EXECUTOR LOAD_FAST | 2,225,320 | 0.1% | 95.7% |
| GET_ITER FOR_ITER_LIST | 2,195,820 | 0.1% | 95.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 2,170,060 | 0.1% | 95.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 2,159,940 | 0.1% | 95.9% |


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
| RESUME_CHECK | 19,112,340 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 33,388,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 33,388,200 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,875,840 | 60.3% |
| LOAD_FAST | 915,960 | 29.4% |
| RETURN_VALUE | 319,980 | 10.3% |
| CALL_BUILTIN_CLASS | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 2,195,820 | 70.6% |
| LOAD_FAST_AND_CLEAR | 915,900 | 29.4% |
| FOR_ITER_RANGE | 240 | 0.0% |
| EXTENDED_ARG | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 18,511,860 | 96.9% |
| RETURN_CONST | 600,480 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 915,900 | 60.6% |
| POP_JUMP_IF_NOT_NONE | 595,920 | 39.4% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,511,820 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 31,464,180 | 98.0% |
| CALL_FUNCTION_EX | 600,000 | 1.9% |
| POP_JUMP_IF_TRUE | 25,800 | 0.1% |
| RETURN_CONST | 780 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,592,560 | 95.3% |
| LOAD_GLOBAL_MODULE | 640,080 | 2.0% |
| ENTER_EXECUTOR | 600,140 | 1.9% |
| LOAD_GLOBAL_BUILTIN | 231,460 | 0.7% |
| RETURN_CONST | 25,800 | 0.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 7,009,540 | 92.1% |
| LOAD_ATTR | 600,080 | 7.9% |
| LOAD_DEREF | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,009,500 | 92.1% |
| LOAD_FAST_LOAD_FAST | 600,000 | 7.9% |
| CALL | 180 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 34,178,400 | 24.1% |
| EXIT_INIT_CHECK | 33,388,200 | 23.5% |
| LOAD_FAST | 32,788,680 | 23.1% |
| BINARY_OP_ADD_FLOAT | 30,513,000 | 21.5% |
| CALL_BUILTIN_O | 6,593,220 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 34,178,400 | 24.1% |
| POP_TOP | 31,464,180 | 22.2% |
| STORE_FAST | 19,013,460 | 13.4% |
| INTERPRETER_EXIT | 18,511,860 | 13.0% |
| LOAD_FAST_LOAD_FAST | 10,767,420 | 7.6% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,200,060 | 66.7% |
| LOAD_FAST | 600,000 | 33.3% |
| STORE_SUBSCR | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,200,000 | 66.6% |
| RETURN_CONST | 600,000 | 33.3% |
| STORE_SUBSCR | 420 | 0.0% |
| ENTER_EXECUTOR | 60 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,530,080 | 100.0% |
| TO_BOOL | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,530,060 | 100.0% |
| TO_BOOL | 360 | 0.0% |
| TO_BOOL_NONE | 20 | 0.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,530,060 | 57.7% |
| LOAD_GLOBAL_MODULE | 1,120,320 | 42.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,530,060 | 57.7% |
| COMPARE_OP_FLOAT | 1,120,320 | 42.3% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 32,650,260 | 59.9% |
| RETURN_VALUE | 7,233,180 | 13.3% |
| LOAD_FAST | 6,490,300 | 11.9% |
| BINARY_SUBSCR_TUPLE_INT | 2,847,420 | 5.2% |
| LOAD_FAST_LOAD_FAST | 1,534,340 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ALLOC_AND_ENTER_INIT | 19,910,120 | 36.5% |
| STORE_FAST | 11,048,680 | 20.3% |
| LOAD_FAST | 9,238,980 | 17.0% |
| CALL_PY_EXACT_ARGS | 6,824,640 | 12.5% |
| BINARY_OP_ADD_FLOAT | 3,056,820 | 5.6% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 915,900 | 49.9% |
| LOAD_FAST_LOAD_FAST | 600,000 | 32.7% |
| RESUME_CHECK | 320,040 | 17.4% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 915,900 | 49.9% |
| LOAD_FAST | 600,120 | 32.7% |
| STORE_FAST | 319,980 | 17.4% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,327,260 | 88.4% |
| BINARY_OP_ADD_FLOAT | 953,900 | 11.5% |
| BINARY_OP | 6,040 | 0.1% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| LOAD_CONST | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 7,327,200 | 88.4% |
| RETURN_VALUE | 959,940 | 11.6% |
| CALL_LIST_APPEND | 480 | 0.0% |
| LOAD_CONST | 360 | 0.0% |
| BUILD_MAP | 60 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,601,640 | 56.1% |
| BINARY_OP_MULTIPLY_INT | 1,049,060 | 16.3% |
| BINARY_OP | 751,040 | 11.7% |
| BINARY_OP_ADD_FLOAT | 694,260 | 10.8% |
| LOAD_FAST | 320,040 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,601,640 | 56.1% |
| LOAD_FAST | 1,800,120 | 28.1% |
| BINARY_OP_ADD_INT | 462,840 | 7.2% |
| STORE_FAST | 320,040 | 5.0% |
| LOAD_GLOBAL_BUILTIN | 231,420 | 3.6% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 600,060 | 100.0% |
| LOAD_FAST | 60 | 0.0% |
| DICT_MERGE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 600,000 | 100.0% |
| RESUME_CHECK | 120 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 600,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 600,060 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 400 | 95.2% |
| CALL | 20 | 4.8% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,341,520 | 100.0% |
| COMPARE_OP | 3,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 11,727,360 | 95.0% |
| POP_JUMP_IF_TRUE | 614,160 | 5.0% |
| COMPARE_OP | 3,040 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 7,327,200 | 45.7% |
| POP_JUMP_IF_NOT_NONE | 4,929,480 | 30.7% |
| POP_JUMP_IF_TRUE | 1,693,200 | 10.6% |
| STORE_FAST | 867,060 | 5.4% |
| CALL_LIST_APPEND | 614,160 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 11,961,060 | 74.6% |
| LOAD_FAST | 2,225,320 | 13.9% |
| STORE_FAST | 915,900 | 5.7% |
| RETURN_CONST | 614,220 | 3.8% |
| LOAD_GLOBAL_BUILTIN | 314,760 | 2.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 33.3% |
| JUMP_BACKWARD | 60 | 33.3% |
| GET_ITER | 60 | 33.3% |

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
| POP_TOP | 220 | 78.6% |
| EXTENDED_ARG | 60 | 21.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 200 | 71.4% |
| EXTENDED_ARG | 60 | 21.4% |
| ENTER_EXECUTOR | 20 | 7.1% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 7,327,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,327,200 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600,000 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 600,060 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600,340 | 72.1% |
| LOAD_GLOBAL_MODULE | 231,780 | 27.8% |
| LOAD_ATTR | 280 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 600,080 | 72.1% |
| BINARY_OP | 231,420 | 27.8% |
| LOAD_ATTR | 280 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 220 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 180 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,178,560 | 44.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,144,620 | 17.4% |
| LOAD_GLOBAL_BUILTIN | 3,920,040 | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,711,900 | 9.0% |
| LOAD_FAST_LOAD_FAST | 2,898,180 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 12,341,520 | 30.0% |
| LOAD_FAST | 8,676,120 | 21.1% |
| BINARY_SUBSCR_TUPLE_INT | 6,693,900 | 16.3% |
| LOAD_GLOBAL_BUILTIN | 3,600,000 | 8.8% |
| BINARY_OP_ADD_INT | 2,115,960 | 5.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 33.3% |
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 66.7% |
| LIST_EXTEND | 60 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 173,728,020 | 29.6% |
| RESUME_CHECK | 103,860,420 | 17.7% |
| STORE_FAST | 48,312,300 | 8.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 41,079,420 | 7.0% |
| BINARY_OP_MULTIPLY_FLOAT | 38,641,980 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 363,429,940 | 61.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 100,941,320 | 17.2% |
| RETURN_VALUE | 32,788,680 | 5.6% |
| CALL_PY_EXACT_ARGS | 30,337,720 | 5.2% |
| LOAD_CONST | 18,178,560 | 3.1% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 915,900 | 50.0% |
| GET_ITER | 915,900 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 915,900 | 50.0% |
| LOAD_FAST_AND_CLEAR | 915,900 | 50.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 54,995,040 | 39.1% |
| RESUME_CHECK | 33,476,280 | 23.8% |
| BINARY_OP_MULTIPLY_FLOAT | 17,957,080 | 12.8% |
| LOAD_GLOBAL_MODULE | 15,234,840 | 10.8% |
| RETURN_VALUE | 10,767,420 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 88,383,160 | 62.9% |
| LOAD_ATTR_INSTANCE_VALUE | 28,322,300 | 20.2% |
| BINARY_OP_MULTIPLY_FLOAT | 10,767,420 | 7.7% |
| LOAD_FAST | 4,970,280 | 3.5% |
| LOAD_CONST | 2,898,180 | 2.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 21.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 21.4% |
| RETURN_VALUE | 100 | 17.9% |
| RESUME_CHECK | 80 | 14.3% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 10.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 460 | 82.1% |
| LOAD_GLOBAL_BUILTIN | 80 | 14.3% |
| LOAD_ATTR | 20 | 3.6% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 17,871,900 | 55.4% |
| COMPARE_OP | 11,727,360 | 36.3% |
| TO_BOOL | 1,530,060 | 4.7% |
| COMPARE_OP_INT | 919,980 | 2.8% |
| TO_BOOL_INT | 231,420 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 18,511,860 | 57.3% |
| RETURN_CONST | 10,355,460 | 32.1% |
| LOAD_CONST | 1,850,040 | 5.7% |
| NOP | 915,900 | 2.8% |
| LOAD_FAST | 647,520 | 2.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 338,340 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 319,980 | 94.6% |
| LOAD_FAST_LOAD_FAST | 18,360 | 5.4% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,802,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,929,480 | 72.5% |
| LOAD_FAST | 1,276,680 | 18.8% |
| NOP | 595,920 | 8.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 1,964,460 | 61.0% |
| TO_BOOL_BOOL | 639,960 | 19.9% |
| COMPARE_OP | 614,160 | 19.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,693,200 | 52.6% |
| LOAD_FAST | 955,620 | 29.7% |
| LOAD_FAST_LOAD_FAST | 543,960 | 16.9% |
| POP_TOP | 25,800 | 0.8% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 33,984,720 | 53.6% |
| RESUME_CHECK | 17,871,900 | 28.2% |
| POP_JUMP_IF_FALSE | 10,355,460 | 16.3% |
| ENTER_EXECUTOR | 614,220 | 1.0% |
| STORE_SUBSCR | 600,000 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXIT_INIT_CHECK | 33,388,200 | 52.6% |
| TO_BOOL_BOOL | 18,511,860 | 29.2% |
| LOAD_FAST | 6,206,880 | 9.8% |
| STORE_FAST | 4,744,500 | 7.5% |
| INTERPRETER_EXIT | 600,480 | 0.9% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 71.4% |
| LOAD_FAST_LOAD_FAST | 80 | 28.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 280 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 19,013,460 | 34.7% |
| BINARY_OP | 11,048,680 | 20.2% |
| BINARY_OP_SUBTRACT_FLOAT | 10,737,480 | 19.6% |
| RETURN_CONST | 4,744,500 | 8.7% |
| STORE_FAST | 1,831,800 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,312,300 | 88.3% |
| LOAD_GLOBAL_MODULE | 2,156,060 | 3.9% |
| STORE_FAST | 1,831,800 | 3.3% |
| ENTER_EXECUTOR | 867,060 | 1.6% |
| LOAD_FAST_LOAD_FAST | 634,860 | 1.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,555,860 | 82.9% |
| UNPACK_SEQUENCE_TUPLE | 319,980 | 17.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 915,900 | 48.8% |
| LOAD_FAST | 639,960 | 34.1% |
| STORE_FAST | 319,980 | 17.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 915,900 | 50.0% |
| BUILD_LIST | 915,900 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 915,900 | 50.0% |
| BUILD_LIST | 915,900 | 50.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 52,575,180 | 76.0% |
| BINARY_OP_MULTIPLY_INT | 8,437,640 | 12.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,919,980 | 5.7% |
| BINARY_OP | 3,056,820 | 4.4% |
| LOAD_CONST | 694,260 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,208,720 | 50.9% |
| RETURN_VALUE | 30,513,000 | 44.1% |
| CALL_ALLOC_AND_ENTER_INIT | 1,200,000 | 1.7% |
| BUILD_TUPLE | 953,900 | 1.4% |
| CALL | 694,260 | 1.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,115,960 | 66.6% |
| LOAD_FAST | 600,000 | 18.9% |
| CALL | 462,840 | 14.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 1,200,060 | 37.8% |
| LOAD_FAST | 915,900 | 28.8% |
| LOAD_CONST | 831,420 | 26.2% |
| LOAD_GLOBAL_BUILTIN | 231,420 | 7.3% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 118,163,280 | 91.5% |
| LOAD_FAST_LOAD_FAST | 10,767,420 | 8.3% |
| BINARY_OP_MULTIPLY_INT | 112,140 | 0.1% |
| BINARY_SUBSCR_TUPLE_INT | 32,400 | 0.0% |
| BINARY_OP | 18,620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 52,575,180 | 40.7% |
| LOAD_FAST | 38,641,980 | 29.9% |
| LOAD_FAST_LOAD_FAST | 17,957,080 | 13.9% |
| BINARY_OP_SUBTRACT_FLOAT | 10,767,780 | 8.3% |
| CALL_ALLOC_AND_ENTER_INIT | 8,978,540 | 7.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 11,781,120 | 86.7% |
| LOAD_CONST | 1,649,140 | 12.1% |
| BINARY_OP | 137,100 | 1.0% |
| BINARY_OP_MULTIPLY_FLOAT | 25,440 | 0.2% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 8,437,640 | 62.1% |
| LOAD_FAST | 3,297,240 | 24.3% |
| CALL | 1,049,060 | 7.7% |
| STORE_FAST | 600,000 | 4.4% |
| BINARY_OP_MULTIPLY_FLOAT | 112,140 | 0.8% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 27,452,940 | 54.0% |
| BINARY_OP_MULTIPLY_FLOAT | 10,767,780 | 21.2% |
| BINARY_OP_SUBTRACT_FLOAT | 10,737,420 | 21.1% |
| LOAD_FAST | 1,200,040 | 2.4% |
| CALL_BUILTIN_O | 416,040 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,133,200 | 53.3% |
| STORE_FAST | 10,737,480 | 21.1% |
| BINARY_OP_SUBTRACT_FLOAT | 10,737,420 | 21.1% |
| CALL_PY_EXACT_ARGS | 1,200,000 | 2.4% |
| RETURN_VALUE | 416,040 | 0.8% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,755,080 | 56.5% |
| LOAD_CONST | 1,515,980 | 31.1% |
| LOAD_FAST | 600,000 | 12.3% |
| BINARY_OP | 6,100 | 0.1% |
| BINARY_OP_SUBTRACT_FLOAT | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ALLOC_AND_ENTER_INIT | 2,658,120 | 54.5% |
| LOAD_FAST | 1,612,860 | 33.1% |
| LOAD_CONST | 600,000 | 12.3% |
| BINARY_OP | 6,240 | 0.1% |
| BINARY_OP_SUBTRACT_FLOAT | 480 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,693,900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,879,820 | 43.0% |
| BINARY_OP | 2,847,420 | 42.5% |
| STORE_FAST | 915,900 | 13.7% |
| BINARY_OP_MULTIPLY_FLOAT | 32,400 | 0.5% |
| COMPARE_OP_FLOAT | 18,360 | 0.3% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 19,910,120 | 59.6% |
| BINARY_OP_MULTIPLY_FLOAT | 8,978,540 | 26.9% |
| BINARY_OP_SUBTRACT_INT | 2,658,120 | 8.0% |
| BINARY_OP_ADD_FLOAT | 1,200,000 | 3.6% |
| BINARY_OP_SUBTRACT_FLOAT | 320,100 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 33,388,200 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 100 | 33.3% |
| CALL | 80 | 26.7% |
| LOAD_FAST | 40 | 13.3% |
| LOAD_CONST | 40 | 13.3% |
| BINARY_OP_MULTIPLY_INT | 40 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 240 | 80.0% |
| STORE_FAST | 60 | 20.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,593,220 | 85.6% |
| LOAD_ATTR_INSTANCE_VALUE | 694,260 | 9.0% |
| LOAD_FAST | 416,080 | 5.4% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 6,593,220 | 85.6% |
| LOAD_CONST | 694,260 | 9.0% |
| BINARY_OP_SUBTRACT_FLOAT | 416,040 | 5.4% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 614,280 | 99.9% |
| BUILD_TUPLE | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 614,160 | 99.9% |
| RETURN_CONST | 600 | 0.1% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,520 | 97.4% |
| CALL | 40 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,560 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 62,291,040 | 52.1% |
| LOAD_FAST | 30,337,720 | 25.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,297,520 | 10.3% |
| BINARY_OP | 6,824,640 | 5.7% |
| RETURN_VALUE | 5,610,360 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 119,521,920 | 100.0% |
| CALL_PY_EXACT_ARGS | 54,640 | 0.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNARY_NEGATIVE | 1,120,320 | 57.0% |
| LOAD_GLOBAL_MODULE | 825,780 | 42.0% |
| BINARY_SUBSCR_TUPLE_INT | 18,360 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,964,460 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 919,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 919,980 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,195,820 | 70.6% |
| SWAP | 915,900 | 29.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,555,860 | 50.0% |
| STORE_FAST | 1,550,640 | 49.8% |
| LOAD_GLOBAL_BUILTIN | 5,220 | 0.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 240 | 42.9% |
| JUMP_BACKWARD | 200 | 35.7% |
| EXTENDED_ARG | 120 | 21.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 85.7% |
| LOAD_GLOBAL_MODULE | 40 | 7.1% |
| LOAD_GLOBAL | 20 | 3.6% |
| LOAD_FAST | 20 | 3.6% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 363,429,940 | 92.8% |
| LOAD_FAST_LOAD_FAST | 28,322,300 | 7.2% |
| LOAD_ATTR_INSTANCE_VALUE | 10,800 | 0.0% |
| LOAD_ATTR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 173,728,020 | 44.3% |
| BINARY_OP_MULTIPLY_FLOAT | 118,163,280 | 30.2% |
| BINARY_OP | 32,650,260 | 8.3% |
| BINARY_OP_SUBTRACT_FLOAT | 27,452,940 | 7.0% |
| CALL_PY_EXACT_ARGS | 12,297,520 | 3.1% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 615,680 | 99.9% |
| LOAD_ATTR_INSTANCE_VALUE | 600 | 0.1% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 614,280 | 99.7% |
| LOAD_CONST | 1,560 | 0.3% |
| LOAD_FAST_LOAD_FAST | 480 | 0.1% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,941,320 | 85.8% |
| ENTER_EXECUTOR | 11,961,060 | 10.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,170,060 | 1.8% |
| LOAD_FAST_LOAD_FAST | 1,555,860 | 1.3% |
| RETURN_VALUE | 614,240 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 62,291,040 | 52.9% |
| LOAD_FAST | 41,079,420 | 34.9% |
| LOAD_CONST | 7,144,620 | 6.1% |
| LOAD_GLOBAL_MODULE | 4,970,880 | 4.2% |
| LOAD_FAST_LOAD_FAST | 2,159,940 | 1.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,009,480 | 100.0% |
| LOAD_ATTR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 7,009,540 | 100.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,600,000 | 50.6% |
| STORE_SUBSCR | 1,200,000 | 16.9% |
| LOAD_GLOBAL_BUILTIN | 694,260 | 9.8% |
| STORE_FAST | 600,100 | 8.4% |
| ENTER_EXECUTOR | 314,760 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,920,040 | 55.1% |
| LOAD_FAST | 2,494,440 | 35.1% |
| LOAD_GLOBAL_BUILTIN | 694,260 | 9.8% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 18,511,860 | 41.6% |
| RESUME_CHECK | 15,577,920 | 35.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,970,880 | 11.2% |
| LOAD_FAST | 2,593,560 | 5.8% |
| STORE_FAST | 2,156,060 | 4.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,028,300 | 45.1% |
| LOAD_FAST_LOAD_FAST | 15,234,840 | 34.3% |
| LOAD_ATTR_MODULE | 7,009,480 | 15.8% |
| UNARY_NEGATIVE | 1,120,320 | 2.5% |
| COMPARE_OP_FLOAT | 825,780 | 1.9% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 119,521,920 | 69.5% |
| CALL_ALLOC_AND_ENTER_INIT | 33,388,200 | 19.4% |
| CACHE | 19,112,340 | 11.1% |
| CALL_FUNCTION_EX | 120 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 103,860,420 | 60.4% |
| LOAD_FAST_LOAD_FAST | 33,476,280 | 19.5% |
| RETURN_CONST | 17,871,900 | 10.4% |
| LOAD_GLOBAL_MODULE | 15,577,920 | 9.1% |
| LOAD_CONST | 915,900 | 0.5% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 88,383,160 | 92.0% |
| LOAD_FAST | 7,724,440 | 8.0% |
| STORE_ATTR | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 54,995,040 | 57.2% |
| RETURN_CONST | 33,984,720 | 35.4% |
| LOAD_FAST | 6,807,300 | 7.1% |
| RETURN_VALUE | 319,980 | 0.3% |
| LOAD_CONST | 600 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 18,511,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,871,900 | 96.5% |
| POP_JUMP_IF_TRUE | 639,960 | 3.5% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 231,420 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 231,420 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| TO_BOOL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 319,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 319,980 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,555,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,555,860 | 100.0% |


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
|          hit |      6693900 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1800060 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 420 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 420 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1530060 | 7.5% |
|          hit |     18743340 | 92.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 5.3% |
| Failure | 360 | 94.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float | 360 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     53640200 | 16.5% |
| specialization.deopt |       698520 | 0.2% |
|          hit |    233789520 | 71.9% |
|         miss |     37021060 | 11.4% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 698,680 | 44.8% |
| Failure | 861,240 | 55.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| subtract different types | 576,380 | 66.9% |
| multiply different types | 162,320 | 18.8% |
| add different types | 115,920 | 13.5% |
| subtract other | 4,120 | 0.5% |
| true divide float | 1,640 | 0.2% |
| true divide different types | 520 | 0.1% |
| add other | 280 | 0.0% |
| remainder | 60 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6414540 | 3.8% |
| specialization.deopt |        54640 | 0.0% |
|          hit |    158389540 | 94.4% |
|         miss |      2895420 | 1.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 55,220 | 97.1% |
| Failure | 1,620 | 2.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc varargs keywords | 920 | 56.8% |
| class no vectorcall | 620 | 38.3% |
| cfunc noargs | 60 | 3.7% |
| init not simple | 20 | 1.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     12341520 | 81.0% |
|          hit |      2884440 | 18.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 3,040 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 3,040 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      3112280 | 100.0% |


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
| specialization.deferred |       831680 | 0.2% |
| specialization.deopt |        67240 | 0.0% |
|          hit |    513528320 | 99.2% |
|         miss |      3563340 | 0.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 67,800 | 99.6% |
| Failure | 280 | 0.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 140 | 50.0% |
| mutable class | 120 | 42.9% |
| metaclass attribute | 20 | 7.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     51560680 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 540 | 100.0% |
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
|          hit |     96107640 | 100.0% |
|         miss |          240 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1875840 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,169,765,800 | 45.1% |
| Not specialized | 163,547,300 | 6.3% |
| Specialized | 1,258,708,140 | 48.6% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 53,640,200 | 70.1% |
| COMPARE_OP | 12,341,520 | 16.1% |
| CALL | 6,414,540 | 8.4% |
| STORE_SUBSCR | 1,800,060 | 2.4% |
| TO_BOOL | 1,530,060 | 2.0% |
| LOAD_ATTR | 831,680 | 1.1% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 15,092,840 | 34.7% |
| BINARY_OP_MULTIPLY_INT | 8,611,440 | 19.8% |
| BINARY_OP_MULTIPLY_FLOAT | 6,926,340 | 15.9% |
| BINARY_OP_ADD_FLOAT | 6,040,640 | 13.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,990,820 | 6.9% |
| CALL_PY_EXACT_ARGS | 2,895,420 | 6.7% |
| LOAD_ATTR_INSTANCE_VALUE | 572,520 | 1.3% |
| BINARY_OP_SUBTRACT_INT | 349,800 | 0.8% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 19,112,340 | 11.1% |
| Calls to Python functions inlined | 152,910,300 | 88.9% |
| Calls via PyEval_EvalFrame (total) | 19,112,340 | 11.1% |
| Calls via PyEval_EvalFrame (vector) | 19,112,340 | 11.1% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 19,112,340 | 11.1% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 18,511,860 | 10.8% |
| Calls via PyEval_EvalFrame (function ex) | 180 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 205,410,840 | 119.4% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 233,438,920 | 73.3% |
| Frees to freelist | 233,438,960 |  |
| Allocations | 85,159,080 | 26.7% |
| Allocations to 512 bytes | 85,158,960 | 26.7% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 120 | 0.0% |
| Frees | 86,389,740 |  |
| New values | 480 |  |
| Interpreter increfs | 1,703,333,340 | 92.4% |
| Interpreter decrefs | 1,858,487,860 | 87.4% |
| Increfs | 139,160,211 | 7.6% |
| Decrefs | 268,013,431 | 12.6% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 4,627,869 |  |
| Method cache misses | 31 |  |
| Method cache collisions | 31 |  |
| Method cache dunder hits | 18,512,720 |  |
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
| Optimization attempts | 20 |  |
| Traces created | 20 | 100.0% |
| Traces executed | 16,037,320 |  |
| Uops executed | 286,484,080 | 17 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
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
| <= 16 | 20 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 100.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 3,086,800 | 19.2% |
| <= 16 | 12,006,780 | 74.9% |
| <= 32 | 19,500 | 0.1% |
| <= 64 | 27,720 | 0.2% |
| <= 128 | 896,460 | 5.6% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1024 | 0 | 0.0% |
| <= 2048 | 0 | 0.0% |
| <= 4096 | 0 | 0.0% |
| <= 8192 | 0 | 0.0% |
| <= 16384 | 0 | 0.0% |
| <= 32768 | 0 | 0.0% |
| <= 65536 | 0 | 0.0% |
| <= 131072 | 0 | 0.0% |
| <= 262144 | 60 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 64,000,100 | 22.3% | 22.3% |
| STORE_FAST | 36,131,160 | 12.6% | 35.0% |
| LOAD_FAST | 32,700,180 | 11.4% | 46.4% |
| _POP_JUMP_IF_TRUE | 22,065,100 | 7.7% | 54.1% |
| _ITER_CHECK_LIST | 20,853,000 | 7.3% | 61.3% |
| _IS_ITER_EXHAUSTED_LIST | 20,853,000 | 7.3% | 68.6% |
| _ITER_NEXT_LIST | 17,772,300 | 6.2% | 74.8% |
| _EXIT_TRACE | 16,037,320 | 5.6% | 80.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 10,741,620 | 3.7% | 84.2% |
| LOAD_CONST | 8,211,120 | 2.9% | 87.0% |
| _POP_JUMP_IF_FALSE | 6,411,300 | 2.2% | 89.3% |
| _IS_NONE | 6,411,300 | 2.2% | 91.5% |
| BINARY_SUBSCR_TUPLE_INT | 6,411,300 | 2.2% | 93.8% |
| _JUMP_TO_TOP | 6,021,840 | 2.1% | 95.9% |
| POP_TOP | 3,086,860 | 1.1% | 96.9% |
| _ITER_CHECK_RANGE | 1,212,100 | 0.4% | 97.4% |
| _IS_ITER_EXHAUSTED_RANGE | 1,212,100 | 0.4% | 97.8% |
| _ITER_NEXT_RANGE | 1,205,940 | 0.4% | 98.2% |
| _GUARD_BOTH_INT | 1,199,880 | 0.4% | 98.6% |
| _LOAD_ATTR_INSTANCE_VALUE | 605,880 | 0.2% | 98.8% |
| _GUARD_TYPE_VERSION | 605,880 | 0.2% | 99.0% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 605,880 | 0.2% | 99.3% |
| _BINARY_OP_MULTIPLY_INT | 599,940 | 0.2% | 99.5% |
| _BINARY_OP_ADD_INT | 599,940 | 0.2% | 99.7% |
| STORE_SUBSCR | 599,940 | 0.2% | 99.9% |
| BINARY_OP | 299,400 | 0.1% | 100.0% |
| _LOAD_GLOBAL_BUILTINS | 5,940 | 0.0% | 100.0% |
| _GUARD_GLOBALS_VERSION | 5,940 | 0.0% | 100.0% |
| _GUARD_BUILTINS_VERSION | 5,940 | 0.0% | 100.0% |
| GET_ITER | 5,940 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS | 5,940 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| LOAD_ATTR_METHOD_WITH_VALUES | 20 |


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
