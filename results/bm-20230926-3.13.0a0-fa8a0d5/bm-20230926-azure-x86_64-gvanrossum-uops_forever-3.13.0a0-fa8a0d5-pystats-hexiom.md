
# Pystats results

- benchmark: hexiom
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 36,613,560 | 13.4% | 13.4% |  |
| RESUME_CHECK | 22,666,560 | 8.3% | 21.7% |  |
| ENTER_EXECUTOR | 21,010,960 | 7.7% | 29.4% |  |
| LOAD_CONST | 18,483,960 | 6.8% | 36.2% |  |
| POP_TOP | 14,750,340 | 5.4% | 41.6% |  |
| INTERPRETER_EXIT | 14,362,440 | 5.3% | 46.9% |  |
| YIELD_VALUE | 13,643,820 | 5.0% | 51.9% |  |
| BINARY_SUBSCR_LIST_INT | 13,121,280 | 4.8% | 56.7% |  |
| STORE_FAST | 12,166,820 | 4.5% | 61.2% |  |
| LOAD_ATTR_INSTANCE_VALUE | 12,155,040 | 4.5% | 65.6% |  |
| COMPARE_OP_INT | 9,144,000 | 3.4% | 69.0% |  |
| RETURN_VALUE | 7,357,560 | 2.7% | 71.7% |  |
| POP_JUMP_IF_FALSE | 6,627,420 | 2.4% | 74.1% |  |
| LOAD_FAST_LOAD_FAST | 6,306,300 | 2.3% | 76.4% |  |
| POP_JUMP_IF_TRUE | 5,834,880 | 2.1% | 78.6% |  |
| CALL_PY_EXACT_ARGS | 5,096,700 | 1.9% | 80.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,459,680 | 1.6% | 82.1% |  |
| LOAD_GLOBAL_BUILTIN | 4,413,180 | 1.6% | 83.7% |  |
| TO_BOOL_BOOL | 3,750,720 | 1.4% | 85.1% |  |
| CALL_LEN | 3,536,640 | 1.3% | 86.4% |  |
| BINARY_SUBSCR_GETITEM | 3,467,040 | 1.3% | 87.6% |  |
| BINARY_OP_ADD_INT | 3,381,600 | 1.2% | 88.9% |  |
| LOAD_GLOBAL_MODULE | 3,327,000 | 1.2% | 90.1% |  |
| JUMP_FORWARD | 3,119,040 | 1.1% | 91.2% |  |
| GET_ITER | 2,494,200 | 0.9% | 92.2% |  |
| FOR_ITER_LIST | 2,268,080 | 0.8% | 93.0% | 0.1% |
| LOAD_DEREF | 2,221,140 | 0.8% | 93.8% |  |
| CONTAINS_OP | 2,102,400 | 0.8% | 94.6% |  |
| RETURN_CONST | 1,865,820 | 0.7% | 95.3% |  |
| SWAP | 1,522,080 | 0.6% | 95.8% |  |
| COPY | 1,226,880 | 0.4% | 96.3% |  |
| CALL_BUILTIN_CLASS | 1,038,300 | 0.4% | 96.7% |  |
| FOR_ITER_RANGE | 991,700 | 0.4% | 97.0% | 0.2% |
| RETURN_GENERATOR | 718,140 | 0.3% | 97.3% |  |
| COPY_FREE_VARS | 718,140 | 0.3% | 97.5% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 718,080 | 0.3% | 97.8% |  |
| STORE_SUBSCR_LIST_INT | 703,200 | 0.3% | 98.1% |  |
| BINARY_OP_SUBTRACT_INT | 613,440 | 0.2% | 98.3% |  |
| BUILD_TUPLE | 504,000 | 0.2% | 98.5% |  |
| MAKE_FUNCTION | 462,300 | 0.2% | 98.6% |  |
| SET_FUNCTION_ATTRIBUTE | 462,240 | 0.2% | 98.8% |  |
| BUILD_LIST | 364,860 | 0.1% | 98.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 354,240 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 345,120 | 0.1% | 99.2% |  |
| POP_JUMP_IF_NOT_NONE | 261,600 | 0.1% | 99.3% |  |
| CALL_LIST_APPEND | 224,160 | 0.1% | 99.4% |  |
| BINARY_SLICE | 212,640 | 0.1% | 99.5% |  |
| CALL_METHOD_DESCRIPTOR_O | 174,780 | 0.1% | 99.5% |  |
| EXTENDED_ARG | 123,840 | 0.0% | 99.6% |  |
| EXIT_INIT_CHECK | 117,600 | 0.0% | 99.6% |  |
| CALL_ALLOC_AND_ENTER_INIT | 117,600 | 0.0% | 99.7% |  |
| STORE_DEREF | 103,680 | 0.0% | 99.7% |  |
| MAKE_CELL | 103,680 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_TUPLE_INT | 95,520 | 0.0% | 99.8% |  |
| LOAD_ATTR_CLASS | 94,140 | 0.0% | 99.8% |  |
| LOAD_FAST_AND_CLEAR | 78,240 | 0.0% | 99.8% |  |
| LIST_APPEND | 78,240 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 78,000 | 0.0% | 99.9% |  |
| CALL_PY_WITH_DEFAULTS | 77,280 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 53,820 | 0.0% | 99.9% |  |
| STORE_FAST_STORE_FAST | 53,820 | 0.0% | 100.0% |  |
| NOP | 42,780 | 0.0% | 100.0% |  |
| CALL_KW | 14,400 | 0.0% | 100.0% |  |
| BINARY_OP | 11,260 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 9,120 | 0.0% | 100.0% |  |
| CALL | 7,840 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 7,740 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 7,680 | 0.0% | 100.0% |  |
| CALL_STR_1 | 5,760 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 2,940 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 2,880 | 0.0% | 100.0% |  |
| PUSH_NULL | 840 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 840 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 700 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 480 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 480 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 480 | 0.0% | 100.0% |  |
| BUILD_MAP | 480 | 0.0% | 100.0% |  |
| LOAD_ATTR | 200 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 180 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 20 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_TOP ENTER_EXECUTOR | 13,658,920 | 5.0% | 5.0% |
| CACHE RESUME_CHECK | 13,644,300 | 5.0% | 10.0% |
| YIELD_VALUE INTERPRETER_EXIT | 13,643,820 | 5.0% | 15.0% |
| RESUME_CHECK POP_TOP | 13,643,820 | 5.0% | 20.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 10,451,520 | 3.8% | 23.9% |
| ENTER_EXECUTOR YIELD_VALUE | 9,886,140 | 3.6% | 27.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 8,432,160 | 3.1% | 30.6% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 8,284,800 | 3.0% | 33.6% |
| STORE_FAST LOAD_FAST | 6,559,860 | 2.4% | 36.0% |
| RESUME_CHECK LOAD_FAST | 5,202,300 | 1.9% | 37.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 4,538,880 | 1.7% | 39.6% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 4,230,240 | 1.6% | 41.1% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 4,224,000 | 1.5% | 42.7% |
| LOAD_CONST COMPARE_OP_INT | 4,166,880 | 1.5% | 44.2% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,971,580 | 1.5% | 45.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,964,320 | 1.5% | 47.1% |
| CALL_LEN LOAD_CONST | 3,471,360 | 1.3% | 48.4% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 3,467,040 | 1.3% | 49.7% |
| LOAD_FAST LOAD_CONST | 3,349,440 | 1.2% | 50.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 3,349,440 | 1.2% | 52.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,328,320 | 1.2% | 53.4% |
| LOAD_CONST BINARY_OP_ADD_INT | 3,311,040 | 1.2% | 54.6% |
| BINARY_OP_ADD_INT STORE_FAST | 3,304,800 | 1.2% | 55.8% |
| LOAD_CONST JUMP_FORWARD | 3,071,040 | 1.1% | 56.9% |
| JUMP_FORWARD YIELD_VALUE | 3,071,040 | 1.1% | 58.0% |
| ENTER_EXECUTOR LOAD_CONST | 3,041,280 | 1.1% | 59.1% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 2,832,000 | 1.0% | 60.2% |
| RETURN_VALUE TO_BOOL_BOOL | 2,757,600 | 1.0% | 61.2% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 2,744,160 | 1.0% | 62.2% |
| RETURN_VALUE LOAD_CONST | 2,701,920 | 1.0% | 63.2% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 2,643,360 | 1.0% | 64.2% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 2,600,160 | 1.0% | 65.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,568,000 | 0.9% | 66.1% |
| COMPARE_OP_INT RETURN_VALUE | 2,542,080 | 0.9% | 67.0% |
| BINARY_SUBSCR_LIST_INT CALL_LEN | 2,542,080 | 0.9% | 67.9% |
| STORE_FAST ENTER_EXECUTOR | 2,482,840 | 0.9% | 68.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,371,680 | 0.9% | 69.7% |
| LOAD_CONST STORE_FAST | 2,366,400 | 0.9% | 70.6% |
| FOR_ITER_LIST STORE_FAST | 2,141,240 | 0.8% | 71.4% |
| BINARY_SUBSCR_LIST_INT LOAD_GLOBAL_MODULE | 2,115,840 | 0.8% | 72.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,952,160 | 0.7% | 72.8% |
| ENTER_EXECUTOR BINARY_SUBSCR_GETITEM | 1,847,040 | 0.7% | 73.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 1,766,460 | 0.6% | 74.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 1,667,040 | 0.6% | 74.8% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_GETITEM | 1,611,360 | 0.6% | 75.4% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,611,360 | 0.6% | 76.0% |
| ENTER_EXECUTOR LOAD_FAST | 1,476,960 | 0.5% | 76.5% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 1,339,200 | 0.5% | 77.0% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 1,281,120 | 0.5% | 77.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,247,040 | 0.5% | 77.9% |
| LOAD_FAST CONTAINS_OP | 1,189,920 | 0.4% | 78.4% |
| LOAD_DEREF LOAD_FAST | 1,189,920 | 0.4% | 78.8% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,107,360 | 0.4% | 79.2% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 1,000,800 | 0.4% | 79.6% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 995,520 | 0.4% | 79.9% |
| CALL_BUILTIN_CLASS GET_ITER | 989,280 | 0.4% | 80.3% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 988,320 | 0.4% | 80.7% |
| STORE_FAST LOAD_CONST | 985,500 | 0.4% | 81.0% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 981,120 | 0.4% | 81.4% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 955,660 | 0.4% | 81.7% |
| GET_ITER FOR_ITER_RANGE | 935,340 | 0.3% | 82.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 926,880 | 0.3% | 82.4% |
| GET_ITER FOR_ITER_LIST | 914,640 | 0.3% | 82.8% |
| LOAD_FAST GET_ITER | 913,980 | 0.3% | 83.1% |
| LOAD_DEREF BINARY_SUBSCR_LIST_INT | 911,520 | 0.3% | 83.4% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 892,320 | 0.3% | 83.8% |
| RETURN_CONST TO_BOOL_BOOL | 891,360 | 0.3% | 84.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 889,920 | 0.3% | 84.4% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 873,120 | 0.3% | 84.7% |
| BINARY_SUBSCR_LIST_INT CONTAINS_OP | 869,760 | 0.3% | 85.0% |
| FOR_ITER_RANGE STORE_FAST | 834,000 | 0.3% | 85.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_DEREF | 821,760 | 0.3% | 85.7% |
| LOAD_FAST COMPARE_OP_INT | 792,000 | 0.3% | 85.9% |
| RETURN_VALUE LOAD_ATTR_INSTANCE_VALUE | 759,360 | 0.3% | 86.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 750,240 | 0.3% | 86.5% |
| ENTER_EXECUTOR RETURN_CONST | 721,940 | 0.3% | 86.8% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 720,000 | 0.3% | 87.0% |
| POP_JUMP_IF_FALSE RETURN_CONST | 719,040 | 0.3% | 87.3% |
| RETURN_CONST INTERPRETER_EXIT | 718,620 | 0.3% | 87.6% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 718,560 | 0.3% | 87.8% |
| POP_TOP RESUME_CHECK | 718,140 | 0.3% | 88.1% |
| LOAD_FAST FOR_ITER_LIST | 718,140 | 0.3% | 88.3% |
| CACHE POP_TOP | 718,140 | 0.3% | 88.6% |
| STORE_FAST LOAD_DEREF | 718,080 | 0.3% | 88.9% |
| RETURN_GENERATOR CALL_BUILTIN_FAST_WITH_KEYWORDS | 718,080 | 0.3% | 89.1% |
| COPY_FREE_VARS RETURN_GENERATOR | 718,080 | 0.3% | 89.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 718,080 | 0.3% | 89.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 713,820 | 0.3% | 89.9% |
| RETURN_VALUE CALL_LEN | 699,360 | 0.3% | 90.2% |
| LOAD_CONST YIELD_VALUE | 686,400 | 0.3% | 90.4% |
| LOAD_ATTR_INSTANCE_VALUE CALL_BUILTIN_CLASS | 666,240 | 0.2% | 90.7% |
| SWAP SWAP | 613,440 | 0.2% | 90.9% |
| SWAP STORE_SUBSCR_LIST_INT | 613,440 | 0.2% | 91.1% |
| COPY COPY | 613,440 | 0.2% | 91.3% |
| COPY BINARY_SUBSCR_LIST_INT | 613,440 | 0.2% | 91.6% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 612,480 | 0.2% | 91.8% |
| BINARY_OP_SUBTRACT_INT SWAP | 607,200 | 0.2% | 92.0% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 588,000 | 0.2% | 92.2% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 566,400 | 0.2% | 92.4% |
| ENTER_EXECUTOR FOR_ITER_LIST | 508,440 | 0.2% | 92.6% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 211,680 | 99.5% |
| BINARY_OP_ADD_INT | 960 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 158,880 | 74.7% |
| LIST_APPEND | 53,760 | 25.3% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 13,644,300 | 95.0% |
| POP_TOP | 718,140 | 5.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 20 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 117,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 117,600 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 989,280 | 39.7% |
| LOAD_FAST | 913,980 | 36.6% |
| LOAD_ATTR_INSTANCE_VALUE | 566,400 | 22.7% |
| RETURN_VALUE | 23,520 | 0.9% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 935,340 | 37.5% |
| FOR_ITER_LIST | 914,640 | 36.7% |
| CALL_PY_EXACT_ARGS | 462,280 | 18.5% |
| EXTENDED_ARG | 103,680 | 4.2% |
| LOAD_FAST_AND_CLEAR | 78,240 | 3.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 13,643,820 | 95.0% |
| RETURN_CONST | 718,620 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 462,300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 462,240 | 100.0% |
| LOAD_FAST_CHECK | 60 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 42,720 | 99.9% |
| POP_TOP | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 42,720 | 99.9% |
| LOAD_DEREF | 60 | 0.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 13,643,820 | 92.5% |
| CACHE | 718,140 | 4.9% |
| CALL_METHOD_DESCRIPTOR_O | 174,720 | 1.2% |
| RETURN_CONST | 138,240 | 0.9% |
| SWAP | 60,960 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 13,658,920 | 92.6% |
| RESUME_CHECK | 718,140 | 4.9% |
| RETURN_CONST | 228,480 | 1.5% |
| RETURN_VALUE | 60,960 | 0.4% |
| LOAD_GLOBAL_MODULE | 54,720 | 0.4% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 700 | 83.3% |
| LOAD_DEREF | 120 | 14.3% |
| LOAD_ATTR | 20 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 720 | 85.7% |
| LOAD_FAST | 120 | 14.3% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 718,080 | 100.0% |
| CALL_PY_EXACT_ARGS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 718,080 | 100.0% |
| CALL_METHOD_DESCRIPTOR_O | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 4,224,000 | 57.4% |
| COMPARE_OP_INT | 2,542,080 | 34.6% |
| LOAD_FAST | 292,380 | 4.0% |
| EXIT_INIT_CHECK | 117,600 | 1.6% |
| RETURN_VALUE | 78,300 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,757,600 | 37.5% |
| LOAD_CONST | 2,701,920 | 36.7% |
| LOAD_ATTR_INSTANCE_VALUE | 759,360 | 10.3% |
| CALL_LEN | 699,360 | 9.5% |
| STORE_FAST | 240,960 | 3.3% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,620 | 85.4% |
| BUILD_LIST | 960 | 8.5% |
| BINARY_OP_SUBTRACT_INT | 480 | 4.3% |
| BINARY_OP | 200 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,080 | 89.5% |
| STORE_FAST | 480 | 4.3% |
| LOAD_FAST | 480 | 4.3% |
| BINARY_OP | 200 | 1.8% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.2% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,500 | 49.7% |
| STORE_FAST | 102,720 | 28.2% |
| SWAP | 78,240 | 21.4% |
| LOAD_FAST_LOAD_FAST | 960 | 0.3% |
| LOAD_CONST | 960 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 205,440 | 56.3% |
| LOAD_FAST | 78,720 | 21.6% |
| SWAP | 78,240 | 21.4% |
| CALL_ALLOC_AND_ENTER_INIT | 960 | 0.3% |
| BINARY_OP | 960 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 462,240 | 91.7% |
| LOAD_FAST_LOAD_FAST | 27,840 | 5.5% |
| LOAD_GLOBAL_MODULE | 13,920 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 462,240 | 91.7% |
| LIST_APPEND | 23,520 | 4.7% |
| CALL_LIST_APPEND | 13,920 | 2.8% |
| STORE_FAST | 3,360 | 0.7% |
| CALL_PY_EXACT_ARGS | 480 | 0.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,380 | 43.1% |
| ENTER_EXECUTOR | 2,400 | 30.6% |
| PUSH_NULL | 720 | 9.2% |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 6.1% |
| BINARY_SUBSCR_LIST_INT | 480 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,320 | 93.4% |
| CALL | 280 | 3.6% |
| POP_TOP | 60 | 0.8% |
| LOAD_FAST | 60 | 0.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 40 | 0.5% |


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
| LIST_EXTEND | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,960 | 90.0% |
| ENTER_EXECUTOR | 1,440 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 13,920 | 96.7% |
| RESUME_CHECK | 480 | 3.3% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_STR | 20 | 100.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,189,920 | 56.6% |
| BINARY_SUBSCR_LIST_INT | 869,760 | 41.4% |
| RETURN_VALUE | 42,240 | 2.0% |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,611,360 | 76.6% |
| POP_JUMP_IF_TRUE | 490,560 | 23.3% |
| RETURN_VALUE | 480 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 613,440 | 50.0% |
| LOAD_FAST_LOAD_FAST | 483,840 | 39.4% |
| BINARY_SUBSCR_LIST_INT | 129,600 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 613,440 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 613,440 | 50.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 462,240 | 64.4% |
| ENTER_EXECUTOR | 255,840 | 35.6% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 718,080 | 100.0% |
| RESUME_CHECK | 60 | 0.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 13,658,920 | 65.0% |
| POP_JUMP_IF_TRUE | 2,600,160 | 12.4% |
| STORE_FAST | 2,482,840 | 11.8% |
| ENTER_EXECUTOR | 955,660 | 4.5% |
| POP_JUMP_IF_FALSE | 873,120 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 9,886,140 | 47.1% |
| LOAD_CONST | 3,041,280 | 14.5% |
| BINARY_SUBSCR_GETITEM | 1,847,040 | 8.8% |
| LOAD_FAST | 1,476,960 | 7.0% |
| ENTER_EXECUTOR | 955,660 | 4.5% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 103,680 | 83.7% |
| ENTER_EXECUTOR | 20,160 | 16.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 102,600 | 82.8% |
| ENTER_EXECUTOR | 20,160 | 16.3% |
| FOR_ITER_RANGE | 1,080 | 0.9% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 260 | 54.2% |
| STORE_FAST | 200 | 41.7% |
| ENTER_EXECUTOR | 20 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 220 | 45.8% |
| FOR_ITER_RANGE | 160 | 33.3% |
| ENTER_EXECUTOR | 100 | 20.8% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,071,040 | 98.5% |
| STORE_FAST | 39,840 | 1.3% |
| CALL_STR_1 | 5,760 | 0.2% |
| CALL_BUILTIN_CLASS | 1,920 | 0.1% |
| POP_JUMP_IF_FALSE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 3,071,040 | 98.5% |
| LOAD_FAST | 30,240 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 9,120 | 0.3% |
| STORE_FAST | 7,680 | 0.2% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 53,760 | 68.7% |
| BUILD_TUPLE | 23,520 | 30.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 480 | 0.6% |
| BUILD_LIST | 480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 78,240 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 100 | 50.0% |
| LOAD_FAST | 40 | 20.0% |
| LOAD_GLOBAL | 20 | 10.0% |
| LOAD_FAST_CHECK | 20 | 10.0% |
| LOAD_CONST | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 80 | 40.0% |
| LOAD_ATTR_METHOD_NO_DICT | 80 | 40.0% |
| PUSH_NULL | 20 | 10.0% |
| LOAD_ATTR_CLASS | 20 | 10.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 3,471,360 | 18.8% |
| LOAD_FAST | 3,349,440 | 18.1% |
| ENTER_EXECUTOR | 3,041,280 | 16.5% |
| RETURN_VALUE | 2,701,920 | 14.6% |
| POP_JUMP_IF_FALSE | 1,667,040 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 4,166,880 | 22.5% |
| BINARY_OP_ADD_INT | 3,311,040 | 17.9% |
| JUMP_FORWARD | 3,071,040 | 16.6% |
| BINARY_SUBSCR_LIST_INT | 2,832,000 | 15.3% |
| STORE_FAST | 2,366,400 | 12.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 821,760 | 37.0% |
| STORE_FAST | 718,080 | 32.3% |
| ENTER_EXECUTOR | 468,000 | 21.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 111,360 | 5.0% |
| LOAD_FAST | 97,920 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,189,920 | 53.6% |
| BINARY_SUBSCR_LIST_INT | 911,520 | 41.0% |
| CALL_PY_EXACT_ARGS | 119,520 | 5.4% |
| PUSH_NULL | 120 | 0.0% |
| LIST_EXTEND | 60 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 8,432,160 | 23.0% |
| STORE_FAST | 6,559,860 | 17.9% |
| RESUME_CHECK | 5,202,300 | 14.2% |
| LOAD_GLOBAL_BUILTIN | 3,971,580 | 10.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,349,440 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 10,451,520 | 28.5% |
| BINARY_SUBSCR_LIST_INT | 8,284,800 | 22.6% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,964,320 | 10.8% |
| LOAD_CONST | 3,349,440 | 9.1% |
| CALL_PY_EXACT_ARGS | 3,328,320 | 9.1% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 78,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 78,240 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 40 | 66.7% |
| LOAD_ATTR | 20 | 33.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,247,040 | 19.8% |
| RESUME_CHECK | 988,320 | 15.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 926,880 | 14.7% |
| ENTER_EXECUTOR | 892,320 | 14.1% |
| STORE_FAST | 713,820 | 11.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 1,611,360 | 25.6% |
| COMPARE_OP_INT | 1,281,120 | 20.3% |
| CALL_PY_EXACT_ARGS | 981,120 | 15.6% |
| LOAD_ATTR_INSTANCE_VALUE | 889,920 | 14.1% |
| COPY | 483,840 | 7.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 44.4% |
| RETURN_VALUE | 40 | 22.2% |
| STORE_FAST_STORE_FAST | 20 | 11.1% |
| RESUME_CHECK | 20 | 11.1% |
| FOR_ITER_RANGE | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 140 | 77.8% |
| LOAD_GLOBAL_BUILTIN | 20 | 11.1% |
| LOAD_ATTR | 20 | 11.1% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 95,520 | 92.1% |
| ENTER_EXECUTOR | 7,200 | 6.9% |
| CALL_PY_WITH_DEFAULTS | 960 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 103,680 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,643,360 | 39.9% |
| COMPARE_OP_INT | 2,371,680 | 35.8% |
| CONTAINS_OP | 1,611,360 | 24.3% |
| COMPARE_OP_STR | 1,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,766,460 | 26.7% |
| LOAD_CONST | 1,667,040 | 25.2% |
| LOAD_FAST_LOAD_FAST | 1,247,040 | 18.8% |
| ENTER_EXECUTOR | 873,120 | 13.2% |
| RETURN_CONST | 719,040 | 10.8% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 261,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 259,680 | 99.3% |
| LOAD_GLOBAL_BUILTIN | 1,920 | 0.7% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 4,230,240 | 72.5% |
| TO_BOOL_BOOL | 1,107,360 | 19.0% |
| CONTAINS_OP | 490,560 | 8.4% |
| COMPARE_OP_STR | 6,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,600,160 | 44.6% |
| LOAD_FAST | 1,952,160 | 33.5% |
| LOAD_FAST_LOAD_FAST | 588,000 | 10.1% |
| LOAD_GLOBAL_BUILTIN | 420,480 | 7.2% |
| LOAD_CONST | 246,240 | 4.2% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 721,940 | 38.7% |
| POP_JUMP_IF_FALSE | 719,040 | 38.5% |
| POP_TOP | 228,480 | 12.2% |
| STORE_ATTR_INSTANCE_VALUE | 117,600 | 6.3% |
| STORE_SUBSCR_LIST_INT | 78,720 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 891,360 | 47.8% |
| INTERPRETER_EXIT | 718,620 | 38.5% |
| POP_TOP | 138,240 | 7.4% |
| EXIT_INIT_CHECK | 117,600 | 6.3% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 462,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 462,240 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 103,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 103,680 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 3,304,800 | 27.2% |
| LOAD_CONST | 2,366,400 | 19.4% |
| FOR_ITER_LIST | 2,141,240 | 17.6% |
| BINARY_SUBSCR_LIST_INT | 1,000,800 | 8.2% |
| LOAD_ATTR_INSTANCE_VALUE | 995,520 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,559,860 | 53.9% |
| ENTER_EXECUTOR | 2,482,840 | 20.4% |
| LOAD_CONST | 985,500 | 8.1% |
| LOAD_DEREF | 718,080 | 5.9% |
| LOAD_FAST_LOAD_FAST | 713,820 | 5.9% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 53,760 | 68.9% |
| FOR_ITER_LIST | 24,240 | 31.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 53,760 | 68.9% |
| LOAD_GLOBAL_MODULE | 23,520 | 30.2% |
| LOAD_ATTR_METHOD_NO_DICT | 720 | 0.9% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 53,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,280 | 99.0% |
| LOAD_GLOBAL_MODULE | 520 | 1.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 613,440 | 40.3% |
| BINARY_OP_SUBTRACT_INT | 607,200 | 39.9% |
| LOAD_FAST_AND_CLEAR | 78,240 | 5.1% |
| BUILD_LIST | 78,240 | 5.1% |
| ENTER_EXECUTOR | 77,760 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 613,440 | 40.3% |
| STORE_SUBSCR_LIST_INT | 613,440 | 40.3% |
| BUILD_LIST | 78,240 | 5.1% |
| STORE_FAST | 77,760 | 5.1% |
| POP_TOP | 60,960 | 4.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 100.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,886,140 | 72.5% |
| JUMP_FORWARD | 3,071,040 | 22.5% |
| LOAD_CONST | 686,400 | 5.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 13,643,820 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,311,040 | 97.9% |
| CALL_LEN | 65,280 | 1.9% |
| LOAD_FAST_LOAD_FAST | 3,840 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 960 | 0.0% |
| LOAD_FAST | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,304,800 | 97.7% |
| COMPARE_OP_INT | 65,280 | 1.9% |
| SWAP | 6,240 | 0.2% |
| CALL_BUILTIN_CLASS | 2,400 | 0.1% |
| LOAD_CONST | 1,440 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920 | 66.7% |
| LOAD_FAST | 480 | 16.7% |
| BINARY_OP_SUBTRACT_INT | 480 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,400 | 83.3% |
| LOAD_FAST | 480 | 16.7% |


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
| LOAD_CONST | 612,480 | 99.8% |
| LOAD_FAST_LOAD_FAST | 960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 607,200 | 99.0% |
| CALL_BUILTIN_CLASS | 1,920 | 0.3% |
| STORE_FAST | 1,440 | 0.2% |
| LOAD_CONST | 1,440 | 0.2% |
| LOAD_FAST | 480 | 0.1% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,440 | 83.0% |
| BUILD_TUPLE | 480 | 16.3% |
| BINARY_SUBSCR | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,400 | 81.6% |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 16.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 1.4% |
| UNPACK_SEQUENCE | 20 | 0.7% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,847,040 | 53.3% |
| LOAD_FAST_LOAD_FAST | 1,611,360 | 46.5% |
| LOAD_FAST | 8,640 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,467,040 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,284,800 | 63.1% |
| LOAD_CONST | 2,832,000 | 21.6% |
| LOAD_DEREF | 911,520 | 6.9% |
| COPY | 613,440 | 4.7% |
| LOAD_FAST_LOAD_FAST | 479,520 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,224,000 | 32.2% |
| CALL_LEN | 2,542,080 | 19.4% |
| LOAD_GLOBAL_MODULE | 2,115,840 | 16.1% |
| LOAD_CONST | 1,339,200 | 10.2% |
| STORE_FAST | 1,000,800 | 7.6% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,680 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 95,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 95,520 | 100.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 53,760 | 45.7% |
| ENTER_EXECUTOR | 37,920 | 32.2% |
| LOAD_CONST | 24,000 | 20.4% |
| LOAD_FAST | 960 | 0.8% |
| BUILD_LIST | 960 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 117,600 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 666,240 | 64.2% |
| LOAD_CONST | 317,280 | 30.6% |
| STORE_FAST | 23,520 | 2.3% |
| CALL_BUILTIN_CLASS | 23,520 | 2.3% |
| LOAD_FAST | 3,400 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 989,280 | 95.3% |
| STORE_FAST | 23,580 | 2.3% |
| CALL_BUILTIN_CLASS | 23,520 | 2.3% |
| JUMP_FORWARD | 1,920 | 0.2% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 718,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 718,080 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 2,542,080 | 71.9% |
| RETURN_VALUE | 699,360 | 19.8% |
| LOAD_FAST | 295,200 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,471,360 | 98.2% |
| BINARY_OP_ADD_INT | 65,280 | 1.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 154,560 | 69.0% |
| ENTER_EXECUTOR | 55,200 | 24.6% |
| BUILD_TUPLE | 13,920 | 6.2% |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 210,240 | 93.8% |
| LOAD_FAST | 13,920 | 6.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 57.1% |
| LOAD_ATTR_METHOD_NO_DICT | 320 | 38.1% |
| CALL | 40 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 480 | 57.1% |
| YIELD_VALUE | 240 | 28.6% |
| STORE_FAST | 120 | 14.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 520 | 96.3% |
| CALL | 20 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 540 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_LAZY_DICT | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 174,720 | 100.0% |
| RETURN_GENERATOR | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 174,720 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,328,320 | 65.3% |
| LOAD_FAST_LOAD_FAST | 981,120 | 19.3% |
| GET_ITER | 462,280 | 9.1% |
| LOAD_DEREF | 119,520 | 2.3% |
| BINARY_SUBSCR_TUPLE_INT | 95,520 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,538,880 | 89.1% |
| COPY_FREE_VARS | 462,240 | 9.1% |
| MAKE_CELL | 95,520 | 1.9% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 76,320 | 98.8% |
| LOAD_FAST | 960 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 76,320 | 98.8% |
| MAKE_CELL | 960 | 1.2% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 5,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 5,760 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,166,880 | 45.6% |
| LOAD_GLOBAL_MODULE | 2,744,160 | 30.0% |
| LOAD_FAST_LOAD_FAST | 1,281,120 | 14.0% |
| LOAD_FAST | 792,000 | 8.7% |
| LOAD_ATTR_CLASS | 94,080 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,230,240 | 46.3% |
| RETURN_VALUE | 2,542,080 | 27.8% |
| POP_JUMP_IF_FALSE | 2,371,680 | 25.9% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,680 | 99.2% |
| LOAD_FAST_LOAD_FAST | 40 | 0.5% |
| COMPARE_OP | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,720 | 86.8% |
| POP_JUMP_IF_FALSE | 1,020 | 13.2% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 914,640 | 40.3% |
| LOAD_FAST | 718,140 | 31.7% |
| ENTER_EXECUTOR | 508,440 | 22.4% |
| EXTENDED_ARG | 102,600 | 4.5% |
| SWAP | 24,000 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,141,240 | 94.4% |
| LOAD_FAST | 102,520 | 4.5% |
| STORE_FAST_LOAD_FAST | 24,240 | 1.1% |
| RETURN_CONST | 40 | 0.0% |
| FOR_ITER_RANGE | 40 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 935,340 | 94.3% |
| SWAP | 54,240 | 5.5% |
| EXTENDED_ARG | 1,080 | 0.1% |
| ENTER_EXECUTOR | 840 | 0.1% |
| JUMP_BACKWARD | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 834,000 | 84.1% |
| STORE_DEREF | 103,680 | 10.5% |
| STORE_FAST_LOAD_FAST | 53,760 | 5.4% |
| LOAD_FAST | 200 | 0.0% |
| FOR_ITER_LIST | 40 | 0.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 94,120 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 94,080 | 99.9% |
| STORE_FAST | 60 | 0.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,451,520 | 86.0% |
| LOAD_FAST_LOAD_FAST | 889,920 | 7.3% |
| RETURN_VALUE | 759,360 | 6.2% |
| STORE_FAST_LOAD_FAST | 53,760 | 0.4% |
| BINARY_SUBSCR_DICT | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,432,160 | 69.4% |
| STORE_FAST | 995,520 | 8.2% |
| LOAD_DEREF | 821,760 | 6.8% |
| CALL_BUILTIN_CLASS | 666,240 | 5.5% |
| GET_ITER | 566,400 | 4.7% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 480 | 100.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 174,720 | 50.6% |
| LOAD_FAST | 169,040 | 49.0% |
| STORE_FAST_LOAD_FAST | 720 | 0.2% |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 0.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 343,680 | 99.6% |
| LOAD_CONST | 540 | 0.2% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 520 | 0.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 320 | 0.1% |
| CALL | 60 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,964,320 | 88.9% |
| LOAD_ATTR_INSTANCE_VALUE | 478,080 | 10.7% |
| ENTER_EXECUTOR | 17,280 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,349,440 | 75.1% |
| LOAD_FAST_LOAD_FAST | 926,880 | 20.8% |
| LOAD_DEREF | 111,360 | 2.5% |
| CALL_PY_EXACT_ARGS | 72,000 | 1.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 340 | 48.6% |
| ENTER_EXECUTOR | 280 | 40.0% |
| LOAD_ATTR | 80 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 700 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,568,000 | 58.2% |
| ENTER_EXECUTOR | 720,000 | 16.3% |
| POP_JUMP_IF_TRUE | 420,480 | 9.5% |
| STORE_FAST | 404,200 | 9.2% |
| POP_JUMP_IF_FALSE | 198,240 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,971,580 | 90.0% |
| LOAD_CONST | 331,200 | 7.5% |
| LOAD_FAST_LOAD_FAST | 86,880 | 2.0% |
| LOAD_GLOBAL_BUILTIN | 23,520 | 0.5% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 2,115,840 | 63.6% |
| LOAD_FAST | 750,240 | 22.6% |
| STORE_FAST | 135,680 | 4.1% |
| POP_JUMP_IF_FALSE | 109,440 | 3.3% |
| POP_TOP | 54,720 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 2,744,160 | 82.5% |
| LOAD_FAST_LOAD_FAST | 275,520 | 8.3% |
| LOAD_ATTR_CLASS | 94,120 | 2.8% |
| LOAD_FAST | 59,580 | 1.8% |
| RETURN_VALUE | 39,360 | 1.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 13,644,300 | 60.2% |
| CALL_PY_EXACT_ARGS | 4,538,880 | 20.0% |
| BINARY_SUBSCR_GETITEM | 3,467,040 | 15.3% |
| POP_TOP | 718,140 | 3.2% |
| CALL_ALLOC_AND_ENTER_INIT | 117,600 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 13,643,820 | 60.2% |
| LOAD_FAST | 5,202,300 | 23.0% |
| LOAD_GLOBAL_BUILTIN | 2,568,000 | 11.3% |
| LOAD_FAST_LOAD_FAST | 988,320 | 4.4% |
| LOAD_CONST | 215,040 | 0.9% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 190,560 | 53.8% |
| LOAD_FAST | 163,680 | 46.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 162,720 | 45.9% |
| RETURN_CONST | 117,600 | 33.2% |
| LOAD_FAST_LOAD_FAST | 72,480 | 20.5% |
| LOAD_CONST | 960 | 0.3% |
| BUILD_MAP | 480 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,120 | 100.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 613,440 | 87.2% |
| LOAD_FAST | 78,720 | 11.2% |
| LOAD_ATTR_INSTANCE_VALUE | 9,120 | 1.3% |
| LOAD_FAST_LOAD_FAST | 1,920 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 477,600 | 67.9% |
| ENTER_EXECUTOR | 131,520 | 18.7% |
| RETURN_CONST | 78,720 | 11.2% |
| LOAD_FAST | 15,360 | 2.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,757,600 | 73.5% |
| RETURN_CONST | 891,360 | 23.8% |
| LOAD_FAST | 101,760 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,643,360 | 70.5% |
| POP_JUMP_IF_TRUE | 1,107,360 | 29.5% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,280 | 99.0% |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 0.9% |
| BINARY_SUBSCR_DICT | 40 | 0.1% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 53,820 | 100.0% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     41109660 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1747200 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     16381920 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        11040 | 0.2% |
|          hit |      5621340 | 99.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 9.1% |
| Failure | 200 | 90.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 120 | 60.0% |
| remainder | 80 | 40.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         7440 | 0.0% |
|          hit |     38133780 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 30.0% |
| Failure | 280 | 70.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class no vectorcall | 180 | 64.3% |
| cfunc noargs | 60 | 21.4% |
| wrong number arguments | 40 | 14.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     26766300 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |           80 | 0.0% |
|          hit |      3255780 | 99.9% |
|         miss |         4000 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


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
| specialization.deferred |           20 | 0.0% |
|          hit |     52582900 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     22909420 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
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
|          hit |       354240 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |        62460 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 163,272,900 | 59.9% |
| Not specialized | 12,960,560 | 4.8% |
| Specialized | 96,424,120 | 35.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 11,040 | 59.6% |
| CALL | 7,440 | 40.2% |
| LOAD_GLOBAL | 20 | 0.1% |
| LOAD_ATTR | 20 | 0.1% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER_RANGE | 2,120 | 53.0% |
| FOR_ITER_LIST | 1,880 | 47.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |
| STORE_SUBSCR_DICT | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |
| STORE_FAST_LOAD_FAST | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 14,362,440 | 39.7% |
| Calls to Python functions inlined | 21,795,060 | 60.3% |
| Calls via PyEval_EvalFrame (total) | 14,362,440 | 39.7% |
| Calls via PyEval_EvalFrame (vector) | 480 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 14,361,960 | 39.7% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 480 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 21,913,140 | 60.6% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 2,184,820 | 22.8% |
| Frees to freelist | 2,184,780 |  |
| Allocations | 7,395,360 | 77.2% |
| Allocations to 512 bytes | 7,394,840 | 77.2% |
| Allocations to 4 kbytes | 520 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 7,557,060 |  |
| New values | 480 |  |
| Interpreter increfs | 88,518,460 | 34.9% |
| Interpreter decrefs | 112,188,680 | 42.7% |
| Increfs | 164,957,340 | 65.1% |
| Decrefs | 150,542,480 | 57.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 25,566 |  |
| Method cache misses | 14 |  |
| Method cache collisions | 14 |  |
| Method cache dunder hits | 53,860 |  |
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
