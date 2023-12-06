
# Pystats results

- benchmark: pathlib
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 58,489,100 | 22.0% | 22.0% |  |
| RESUME_CHECK | 18,493,020 | 7.0% | 29.0% |  |
| STORE_FAST | 16,696,500 | 6.3% | 35.3% |  |
| RETURN_VALUE | 14,530,380 | 5.5% | 40.8% |  |
| LOAD_GLOBAL_BUILTIN | 10,571,220 | 4.0% | 44.8% |  |
| NOP | 9,245,220 | 3.5% | 48.2% |  |
| LOAD_ATTR_SLOT | 8,884,860 | 3.3% | 51.6% | 0.0% |
| INTERPRETER_EXIT | 8,044,740 | 3.0% | 54.6% |  |
| STORE_ATTR_SLOT | 7,922,280 | 3.0% | 57.6% |  |
| LOAD_FAST_LOAD_FAST | 6,606,180 | 2.5% | 60.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 6,605,640 | 2.5% | 62.6% |  |
| FORMAT_SIMPLE | 6,600,000 | 2.5% | 65.1% |  |
| PUSH_NULL | 6,245,040 | 2.4% | 67.4% |  |
| POP_JUMP_IF_FALSE | 5,291,400 | 2.0% | 69.4% |  |
| LOAD_GLOBAL_MODULE | 5,287,080 | 2.0% | 71.4% |  |
| LOAD_ATTR_PROPERTY | 5,282,100 | 2.0% | 73.4% |  |
| CALL | 4,925,940 | 1.9% | 75.3% |  |
| LOAD_CONST | 3,974,360 | 1.5% | 76.8% |  |
| LOAD_ATTR_MODULE | 3,966,640 | 1.5% | 78.3% |  |
| POP_TOP | 3,963,780 | 1.5% | 79.8% |  |
| ENTER_EXECUTOR | 3,481,340 | 1.3% | 81.1% |  |
| TO_BOOL_BOOL | 2,643,540 | 1.0% | 82.1% |  |
| RETURN_CONST | 2,642,640 | 1.0% | 83.1% |  |
| CALL_STR_1 | 2,642,160 | 1.0% | 84.1% |  |
| CALL_ISINSTANCE | 2,641,620 | 1.0% | 85.0% |  |
| BUILD_LIST | 2,641,620 | 1.0% | 86.0% |  |
| CALL_FUNCTION_EX | 2,641,140 | 1.0% | 87.0% |  |
| BUILD_STRING | 2,640,000 | 1.0% | 88.0% |  |
| POP_JUMP_IF_TRUE | 2,283,940 | 0.9% | 88.9% |  |
| GET_ITER | 1,323,660 | 0.5% | 89.4% |  |
| CALL_PY_EXACT_ARGS | 1,323,600 | 0.5% | 89.9% |  |
| LOAD_ATTR | 1,322,400 | 0.5% | 90.4% |  |
| LOAD_DEREF | 1,322,280 | 0.5% | 90.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,322,100 | 0.5% | 91.4% |  |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,321,500 | 0.5% | 91.9% |  |
| COPY_FREE_VARS | 1,321,140 | 0.5% | 92.4% |  |
| JUMP_FORWARD | 1,321,020 | 0.5% | 92.9% |  |
| IS_OP | 1,321,020 | 0.5% | 93.4% |  |
| CALL_KW | 1,320,960 | 0.5% | 93.9% |  |
| TO_BOOL | 1,320,920 | 0.5% | 94.4% |  |
| LOAD_SUPER_ATTR_ATTR | 1,320,540 | 0.5% | 94.9% |  |
| FOR_ITER_TUPLE | 1,320,540 | 0.5% | 95.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,320,540 | 0.5% | 95.9% |  |
| CALL_LIST_APPEND | 1,320,540 | 0.5% | 96.4% |  |
| TO_BOOL_LIST | 1,320,480 | 0.5% | 96.9% |  |
| CALL_TYPE_1 | 1,320,480 | 0.5% | 97.4% |  |
| BINARY_OP | 1,320,380 | 0.5% | 97.9% |  |
| YIELD_VALUE | 1,320,000 | 0.5% | 98.4% |  |
| FOR_ITER_GEN | 1,200,960 | 0.5% | 98.8% |  |
| JUMP_BACKWARD | 1,200,560 | 0.5% | 99.3% |  |
| POP_JUMP_IF_NONE | 960,000 | 0.4% | 99.6% |  |
| TO_BOOL_NONE | 723,900 | 0.3% | 99.9% | 24.6% |
| TO_BOOL_ALWAYS_TRUE | 243,360 | 0.1% | 100.0% | 73.2% |
| COMPARE_OP_STR | 3,200 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 2,780 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 2,580 | 0.0% | 100.0% |  |
| CALL_LEN | 2,580 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 2,380 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 2,100 | 0.0% | 100.0% |  |
| SWAP | 1,740 | 0.0% | 100.0% |  |
| LOAD_ATTR_CLASS | 1,680 | 0.0% | 100.0% |  |
| MAKE_CELL | 1,500 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TUPLE | 1,080 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 1,080 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 1,080 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 1,080 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 1,060 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 1,020 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 1,020 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 960 | 0.0% | 100.0% |  |
| END_FOR | 960 | 0.0% | 100.0% |  |
| CONTAINS_OP | 960 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 960 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 660 | 0.0% | 100.0% |  |
| POP_EXCEPT | 660 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 660 | 0.0% | 100.0% |  |
| BINARY_SLICE | 660 | 0.0% | 100.0% |  |
| LIST_APPEND | 600 | 0.0% | 100.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 600 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 560 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 540 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 540 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 540 | 0.0% | 100.0% |  |
| COPY | 540 | 0.0% | 100.0% |  |
| STORE_DEREF | 480 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 480 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 480 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_INT | 480 | 0.0% | 100.0% |  |
| BEFORE_WITH | 480 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 300 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 300 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 120 | 0.0% | 100.0% |  |
| COMPARE_OP | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| STORE_ATTR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 10,087,560 | 3.8% | 3.8% |
| LOAD_FAST LOAD_ATTR_SLOT | 7,925,300 | 3.0% | 6.8% |
| RESUME_CHECK NOP | 7,924,140 | 3.0% | 9.8% |
| NOP LOAD_FAST | 7,924,140 | 3.0% | 12.8% |
| LOAD_ATTR_SLOT RETURN_VALUE | 7,923,000 | 3.0% | 15.7% |
| CACHE RESUME_CHECK | 6,724,140 | 2.5% | 18.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 6,608,400 | 2.5% | 20.8% |
| LOAD_FAST FORMAT_SIMPLE | 6,600,000 | 2.5% | 23.3% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 5,405,600 | 2.0% | 25.3% |
| RETURN_VALUE INTERPRETER_EXIT | 5,283,600 | 2.0% | 27.3% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 5,282,100 | 2.0% | 29.3% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 5,282,040 | 2.0% | 31.3% |
| PUSH_NULL LOAD_FAST | 4,922,760 | 1.9% | 33.1% |
| RESUME_CHECK LOAD_FAST | 3,964,260 | 1.5% | 34.6% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 3,963,220 | 1.5% | 36.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 3,962,640 | 1.5% | 37.6% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 3,962,160 | 1.5% | 39.1% |
| RETURN_VALUE STORE_FAST | 3,960,480 | 1.5% | 40.6% |
| STORE_ATTR_SLOT LOAD_FAST | 3,960,120 | 1.5% | 42.1% |
| LOAD_FAST STORE_ATTR_SLOT | 3,960,080 | 1.5% | 43.6% |
| LOAD_FAST CALL | 3,601,660 | 1.4% | 44.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 2,643,880 | 1.0% | 45.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,643,800 | 1.0% | 46.9% |
| LOAD_FAST CALL_STR_1 | 2,642,140 | 1.0% | 47.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,641,980 | 1.0% | 48.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 2,641,620 | 1.0% | 49.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 2,641,560 | 1.0% | 50.9% |
| CALL RESUME_CHECK | 2,641,440 | 1.0% | 51.9% |
| RETURN_CONST INTERPRETER_EXIT | 2,641,140 | 1.0% | 52.9% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 2,641,080 | 1.0% | 53.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,641,080 | 1.0% | 54.9% |
| LOAD_FAST CALL_FUNCTION_EX | 2,641,080 | 1.0% | 55.9% |
| LOAD_CONST LOAD_FAST | 2,640,480 | 1.0% | 56.9% |
| RETURN_VALUE LOAD_FAST | 2,640,120 | 1.0% | 57.9% |
| FORMAT_SIMPLE LOAD_FAST | 2,640,000 | 1.0% | 58.9% |
| FORMAT_SIMPLE BUILD_STRING | 2,640,000 | 1.0% | 59.9% |
| BUILD_STRING STORE_FAST | 2,640,000 | 1.0% | 60.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 1,562,780 | 0.6% | 61.4% |
| POP_TOP ENTER_EXECUTOR | 1,440,000 | 0.5% | 62.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 1,325,940 | 0.5% | 62.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 1,323,000 | 0.5% | 63.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 1,322,520 | 0.5% | 63.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,322,020 | 0.5% | 64.0% |
| LOAD_FAST CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,321,560 | 0.5% | 64.5% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 1,321,560 | 0.5% | 65.0% |
| CALL_STR_1 RETURN_VALUE | 1,321,500 | 0.5% | 65.5% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,321,480 | 0.5% | 66.0% |
| LOAD_FAST GET_ITER | 1,321,140 | 0.5% | 66.5% |
| LOAD_ATTR LOAD_FAST | 1,321,140 | 0.5% | 67.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,321,080 | 0.5% | 67.5% |
| STORE_ATTR_SLOT RETURN_CONST | 1,321,080 | 0.5% | 68.0% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 1,321,080 | 0.5% | 68.5% |
| LOAD_ATTR_MODULE STORE_FAST | 1,321,080 | 0.5% | 69.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 1,321,080 | 0.5% | 69.5% |
| NOP LOAD_GLOBAL_MODULE | 1,321,020 | 0.5% | 70.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,321,020 | 0.5% | 70.5% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT LOAD_ATTR_MODULE | 1,321,000 | 0.5% | 71.0% |
| LOAD_CONST CALL_KW | 1,320,960 | 0.5% | 71.5% |
| COPY_FREE_VARS RESUME_CHECK | 1,320,600 | 0.5% | 71.9% |
| LOAD_FAST TO_BOOL | 1,320,580 | 0.5% | 72.4% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,320,540 | 0.5% | 72.9% |
| TO_BOOL POP_JUMP_IF_FALSE | 1,320,540 | 0.5% | 73.4% |
| STORE_FAST JUMP_FORWARD | 1,320,540 | 0.5% | 73.9% |
| RESUME_CHECK BUILD_LIST | 1,320,540 | 0.5% | 74.4% |
| POP_TOP RETURN_CONST | 1,320,540 | 0.5% | 74.9% |
| POP_JUMP_IF_FALSE NOP | 1,320,540 | 0.5% | 75.4% |
| LOAD_SUPER_ATTR_ATTR PUSH_NULL | 1,320,540 | 0.5% | 75.9% |
| LOAD_GLOBAL_MODULE IS_OP | 1,320,540 | 0.5% | 76.4% |
| LOAD_GLOBAL_MODULE CALL_ISINSTANCE | 1,320,540 | 0.5% | 76.9% |
| LOAD_GLOBAL_BUILTIN LOAD_DEREF | 1,320,540 | 0.5% | 77.4% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 1,320,540 | 0.5% | 77.9% |
| LOAD_FAST LOAD_SUPER_ATTR_ATTR | 1,320,540 | 0.5% | 78.4% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,320,540 | 0.5% | 78.9% |
| LOAD_FAST CALL_LIST_APPEND | 1,320,540 | 0.5% | 79.4% |
| LOAD_DEREF LOAD_FAST | 1,320,540 | 0.5% | 79.9% |
| JUMP_FORWARD LOAD_FAST | 1,320,540 | 0.5% | 80.4% |
| IS_OP POP_JUMP_IF_FALSE | 1,320,540 | 0.5% | 80.9% |
| GET_ITER FOR_ITER_TUPLE | 1,320,540 | 0.5% | 81.4% |
| FOR_ITER_TUPLE STORE_FAST | 1,320,540 | 0.5% | 81.9% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 1,320,540 | 0.5% | 82.4% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 1,320,540 | 0.5% | 82.9% |
| CALL_FUNCTION_EX POP_TOP | 1,320,540 | 0.5% | 83.4% |
| CALL RETURN_VALUE | 1,320,540 | 0.5% | 83.9% |
| CACHE COPY_FREE_VARS | 1,320,540 | 0.5% | 84.4% |
| BUILD_LIST STORE_FAST | 1,320,540 | 0.5% | 84.9% |
| LOAD_ATTR_METHOD_NO_DICT CALL | 1,320,500 | 0.5% | 85.4% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,320,480 | 0.5% | 85.9% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 1,320,480 | 0.5% | 86.4% |
| LOAD_FAST RETURN_VALUE | 1,320,480 | 0.5% | 86.9% |
| LOAD_FAST CALL_TYPE_1 | 1,320,480 | 0.5% | 87.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 1,320,480 | 0.5% | 87.9% |
| CALL_TYPE_1 PUSH_NULL | 1,320,480 | 0.5% | 88.4% |
| CALL_KW RETURN_VALUE | 1,320,480 | 0.5% | 88.9% |
| CALL_FUNCTION_EX RETURN_VALUE | 1,320,480 | 0.5% | 89.4% |
| CALL_STR_1 STORE_FAST | 1,320,060 | 0.5% | 89.9% |
| TO_BOOL_LIST POP_JUMP_IF_FALSE | 1,320,000 | 0.5% | 90.4% |
| RETURN_VALUE YIELD_VALUE | 1,320,000 | 0.5% | 90.9% |
| RETURN_VALUE POP_TOP | 1,320,000 | 0.5% | 91.4% |
| RESUME_CHECK POP_TOP | 1,320,000 | 0.5% | 91.9% |
| LOAD_FAST_LOAD_FAST BUILD_LIST | 1,320,000 | 0.5% | 92.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 90.9% |
| BUILD_TUPLE | 60 | 9.1% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,724,140 | 83.6% |
| COPY_FREE_VARS | 1,320,540 | 16.4% |
| POP_TOP | 60 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 90.6% |
| BINARY_SUBSCR | 80 | 7.5% |
| LOAD_ATTR_MODULE | 20 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 45.3% |
| LOAD_CONST | 480 | 45.3% |
| BINARY_SUBSCR | 80 | 7.5% |
| BINARY_SUBSCR_DICT | 20 | 1.9% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 660 | 100.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 75.0% |
| JUMP_BACKWARD | 240 | 25.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,600,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,640,000 | 40.0% |
| BUILD_STRING | 2,640,000 | 40.0% |
| LOAD_CONST | 1,320,000 | 20.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,321,140 | 99.8% |
| RETURN_VALUE | 960 | 0.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 540 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 540 | 0.0% |
| LOAD_FAST_CHECK | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 1,320,540 | 99.8% |
| FOR_ITER_LIST | 1,020 | 0.1% |
| FOR_ITER_GEN | 960 | 0.1% |
| LOAD_FAST_AND_CLEAR | 540 | 0.0% |
| CALL_PY_EXACT_ARGS | 540 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,283,600 | 65.7% |
| RETURN_CONST | 2,641,140 | 32.8% |
| YIELD_VALUE | 120,000 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 540 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,924,140 | 85.7% |
| POP_JUMP_IF_FALSE | 1,320,540 | 14.3% |
| STORE_FAST | 480 | 0.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,924,140 | 85.7% |
| LOAD_GLOBAL_MODULE | 1,321,020 | 14.3% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 660 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,320,540 | 33.3% |
| RETURN_VALUE | 1,320,000 | 33.3% |
| RESUME_CHECK | 1,320,000 | 33.3% |
| FOR_ITER_GEN | 960 | 0.0% |
| POP_JUMP_IF_FALSE | 660 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,440,000 | 36.3% |
| RETURN_CONST | 1,320,540 | 33.3% |
| JUMP_BACKWARD | 1,200,000 | 30.3% |
| LOAD_FAST | 1,620 | 0.0% |
| RESUME_CHECK | 1,020 | 0.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 620 | 93.9% |
| LOAD_GLOBAL | 40 | 6.1% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,643,880 | 42.3% |
| LOAD_SUPER_ATTR_ATTR | 1,320,540 | 21.1% |
| CALL_TYPE_1 | 1,320,480 | 21.1% |
| LOAD_FAST | 960,000 | 15.4% |
| LOAD_DEREF | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,922,760 | 78.8% |
| LOAD_FAST_LOAD_FAST | 1,320,480 | 21.1% |
| LOAD_GLOBAL_BUILTIN | 600 | 0.0% |
| LOAD_DEREF | 540 | 0.0% |
| LOAD_CONST | 480 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 540 | 52.9% |
| CALL_PY_EXACT_ARGS | 480 | 47.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 540 | 52.9% |
| STORE_FAST | 480 | 47.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 7,923,000 | 54.5% |
| CALL_STR_1 | 1,321,500 | 9.1% |
| CALL | 1,320,540 | 9.1% |
| LOAD_FAST | 1,320,480 | 9.1% |
| CALL_KW | 1,320,480 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 5,283,600 | 36.4% |
| STORE_FAST | 3,960,480 | 27.3% |
| LOAD_FAST | 2,640,120 | 18.2% |
| YIELD_VALUE | 1,320,000 | 9.1% |
| POP_TOP | 1,320,000 | 9.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320,580 | 100.0% |
| TO_BOOL | 320 | 0.0% |
| COPY | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,320,540 | 100.0% |
| TO_BOOL | 320 | 0.0% |
| TO_BOOL_STR | 60 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 1,320,000 | 100.0% |
| BINARY_OP | 320 | 0.0% |
| LOAD_FAST_LOAD_FAST | 20 | 0.0% |
| LOAD_FAST | 20 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320,000 | 100.0% |
| BINARY_OP | 320 | 0.0% |
| BINARY_OP_ADD_UNICODE | 40 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,320,540 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,320,000 | 50.0% |
| SWAP | 540 | 0.0% |
| LOAD_FAST | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,320,540 | 50.0% |
| BINARY_OP | 1,320,000 | 50.0% |
| SWAP | 540 | 0.0% |
| JUMP_FORWARD | 480 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 2,640,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,640,000 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,560 | 74.3% |
| LOAD_ATTR_MODULE | 480 | 22.9% |
| BINARY_SLICE | 60 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,080 | 51.4% |
| LOAD_CONST | 540 | 25.7% |
| CONTAINS_OP | 480 | 22.9% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,601,660 | 73.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,320,500 | 26.8% |
| CALL | 1,640 | 0.0% |
| LOAD_CONST | 960 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,641,440 | 53.6% |
| RETURN_VALUE | 1,320,540 | 26.8% |
| TO_BOOL_NONE | 720,000 | 14.6% |
| TO_BOOL_ALWAYS_TRUE | 240,000 | 4.9% |
| CALL | 1,640 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,641,080 | 100.0% |
| CALL_INTRINSIC_1 | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,320,540 | 50.0% |
| RETURN_VALUE | 1,320,480 | 50.0% |
| RESUME_CHECK | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |


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
| LOAD_CONST | 1,320,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,320,480 | 100.0% |
| RESUME_CHECK | 480 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 50.0% |
| LOAD_GLOBAL_MODULE | 20 | 25.0% |
| LOAD_FAST | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_STR | 60 | 75.0% |
| COMPARE_OP_INT | 20 | 25.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 50.0% |
| BUILD_TUPLE | 480 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 960 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 480 | 88.9% |
| RETURN_VALUE | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 480 | 88.9% |
| TO_BOOL_STR | 40 | 7.4% |
| TO_BOOL | 20 | 3.7% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 1,320,540 | 100.0% |
| CALL_PY_EXACT_ARGS | 540 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,320,600 | 100.0% |
| RETURN_GENERATOR | 540 | 0.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,440,000 | 41.4% |
| CALL_LIST_APPEND | 1,320,540 | 37.9% |
| POP_JUMP_IF_TRUE | 720,000 | 20.7% |
| LIST_APPEND | 460 | 0.0% |
| ENTER_EXECUTOR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,320,540 | 37.9% |
| LOAD_ATTR_METHOD_NO_DICT | 1,199,400 | 34.5% |
| LOAD_ATTR_SLOT | 959,520 | 27.6% |
| RETURN_CONST | 860 | 0.0% |
| STORE_FAST | 440 | 0.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 480 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,320,540 | 100.0% |
| LOAD_CONST | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,320,540 | 100.0% |
| COPY | 480 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,200,000 | 100.0% |
| END_FOR | 240 | 0.0% |
| ENTER_EXECUTOR | 180 | 0.0% |
| LIST_APPEND | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 1,200,000 | 100.0% |
| FOR_ITER_LIST | 280 | 0.0% |
| FOR_ITER_RANGE | 240 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,320,540 | 100.0% |
| BUILD_LIST | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320,540 | 100.0% |
| CALL_BUILTIN_FAST | 480 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 460 | 76.7% |
| JUMP_BACKWARD | 140 | 23.3% |


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
| LOAD_GLOBAL_BUILTIN | 1,320,540 | 99.9% |
| LOAD_FAST | 780 | 0.1% |
| RETURN_VALUE | 480 | 0.0% |
| LOAD_ATTR | 420 | 0.0% |
| LOAD_GLOBAL_MODULE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,321,140 | 99.9% |
| CALL_BUILTIN_O | 480 | 0.0% |
| LOAD_ATTR | 420 | 0.0% |
| LOAD_ATTR_MODULE | 140 | 0.0% |
| LOAD_ATTR_PROPERTY | 60 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,320,480 | 33.2% |
| LOAD_ATTR_METHOD_NO_DICT | 1,320,480 | 33.2% |
| FORMAT_SIMPLE | 1,320,000 | 33.2% |
| LOAD_FAST | 5,660 | 0.1% |
| STORE_FAST | 1,980 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,640,480 | 66.4% |
| CALL_KW | 1,320,960 | 33.2% |
| COMPARE_OP_STR | 2,560 | 0.1% |
| STORE_FAST | 2,520 | 0.1% |
| LOAD_CONST | 1,620 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,320,540 | 99.9% |
| STORE_FAST | 540 | 0.0% |
| PUSH_NULL | 540 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320,540 | 99.9% |
| LOAD_ATTR_METHOD_NO_DICT | 540 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 540 | 0.0% |
| CALL_PY_EXACT_ARGS | 480 | 0.0% |
| PUSH_NULL | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,087,560 | 17.2% |
| NOP | 7,924,140 | 13.5% |
| LOAD_GLOBAL_BUILTIN | 6,608,400 | 11.3% |
| PUSH_NULL | 4,922,760 | 8.4% |
| RESUME_CHECK | 3,964,260 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 7,925,300 | 13.6% |
| FORMAT_SIMPLE | 6,600,000 | 11.3% |
| LOAD_ATTR_METHOD_NO_DICT | 5,405,600 | 9.2% |
| LOAD_ATTR_PROPERTY | 5,282,040 | 9.0% |
| STORE_ATTR_SLOT | 3,960,080 | 6.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 540 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 480 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 2,641,080 | 40.0% |
| STORE_FAST | 1,321,080 | 20.0% |
| ENTER_EXECUTOR | 1,320,540 | 20.0% |
| PUSH_NULL | 1,320,480 | 20.0% |
| POP_JUMP_IF_FALSE | 1,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 3,962,160 | 60.0% |
| LOAD_CONST | 1,320,480 | 20.0% |
| BUILD_LIST | 1,320,000 | 20.0% |
| LOAD_FAST | 2,040 | 0.0% |
| CALL_BUILTIN_FAST | 480 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 20.0% |
| STORE_FAST | 40 | 13.3% |
| RETURN_VALUE | 40 | 13.3% |
| PUSH_EXC_INFO | 40 | 13.3% |
| RESUME_CHECK | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 160 | 53.3% |
| LOAD_GLOBAL_BUILTIN | 120 | 40.0% |
| LOAD_ATTR | 20 | 6.7% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,020 | 68.0% |
| MAKE_CELL | 480 | 32.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,020 | 68.0% |
| MAKE_CELL | 480 | 32.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,323,000 | 25.0% |
| TO_BOOL | 1,320,540 | 25.0% |
| IS_OP | 1,320,540 | 25.0% |
| TO_BOOL_LIST | 1,320,000 | 24.9% |
| COMPARE_OP_STR | 2,580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,641,560 | 49.9% |
| LOAD_FAST | 1,325,940 | 25.1% |
| NOP | 1,320,540 | 25.0% |
| LOAD_FAST_LOAD_FAST | 1,020 | 0.0% |
| LOAD_CONST | 1,020 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960,000 | 100.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 480 | 50.0% |
| LOAD_CONST | 480 | 50.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,320,540 | 57.8% |
| TO_BOOL_NONE | 720,000 | 31.5% |
| TO_BOOL_ALWAYS_TRUE | 240,000 | 10.5% |
| TO_BOOL_STR | 2,240 | 0.1% |
| COMPARE_OP_STR | 620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,562,780 | 68.4% |
| ENTER_EXECUTOR | 720,000 | 31.5% |
| LOAD_GLOBAL_MODULE | 560 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 520 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,321,080 | 50.0% |
| POP_TOP | 1,320,540 | 50.0% |
| ENTER_EXECUTOR | 860 | 0.0% |
| FOR_ITER_LIST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,641,140 | 99.9% |
| END_FOR | 960 | 0.0% |
| POP_TOP | 540 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 540 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 40 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 480 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,960,480 | 23.7% |
| BUILD_STRING | 2,640,000 | 15.8% |
| LOAD_ATTR_MODULE | 1,321,080 | 7.9% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,321,080 | 7.9% |
| FOR_ITER_TUPLE | 1,320,540 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,087,560 | 60.4% |
| LOAD_GLOBAL_BUILTIN | 3,963,220 | 23.7% |
| LOAD_FAST_LOAD_FAST | 1,321,080 | 7.9% |
| JUMP_FORWARD | 1,320,540 | 7.9% |
| LOAD_CONST | 1,980 | 0.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 560 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,080 | 100.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 660 | 37.9% |
| LOAD_FAST_AND_CLEAR | 540 | 31.0% |
| BUILD_LIST | 540 | 31.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 660 | 37.9% |
| FOR_ITER_LIST | 540 | 31.0% |
| BUILD_LIST | 540 | 31.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,320,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200,000 | 90.9% |
| INTERPRETER_EXIT | 120,000 | 9.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 100.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40 | 33.3% |
| CALL_METHOD_DESCRIPTOR_O | 40 | 33.3% |
| BINARY_OP | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |


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
| LOAD_ATTR_MODULE | 40 | 66.7% |
| BINARY_SUBSCR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 540 | 52.9% |
| LOAD_FAST_LOAD_FAST | 480 | 47.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,020 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 90.0% |
| RETURN_VALUE | 40 | 6.7% |
| CALL | 20 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 600 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 520 | 48.1% |
| LOAD_FAST | 520 | 48.1% |
| CALL | 40 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,080 | 100.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 480 | 50.0% |
| JUMP_FORWARD | 480 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 50.0% |
| POP_TOP | 480 | 50.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,321,560 | 100.0% |
| LOAD_DEREF | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,321,080 | 99.9% |
| GET_ITER | 540 | 0.0% |
| RETURN_VALUE | 480 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_STR_1 | 600 | 55.6% |
| LOAD_ATTR | 480 | 44.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 600 | 55.6% |
| RETURN_VALUE | 480 | 44.4% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,321,080 | 50.0% |
| LOAD_GLOBAL_MODULE | 1,320,540 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,641,620 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,560 | 99.2% |
| CALL | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 1,440 | 55.8% |
| LOAD_CONST | 1,080 | 41.9% |
| LOAD_GLOBAL_MODULE | 40 | 1.6% |
| LOAD_GLOBAL | 20 | 0.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,320,540 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,320,000 | 100.0% |
| GET_ITER | 540 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 66.7% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| BINARY_OP_ADD_UNICODE | 40 | 33.3% |
| BINARY_OP | 20 | 16.7% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,321,020 | 99.8% |
| LOAD_ATTR_METHOD_NO_DICT | 1,540 | 0.1% |
| GET_ITER | 540 | 0.0% |
| LOAD_DEREF | 480 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,321,560 | 99.8% |
| MAKE_CELL | 1,020 | 0.1% |
| COPY_FREE_VARS | 540 | 0.0% |
| RETURN_GENERATOR | 480 | 0.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,642,140 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,321,500 | 50.0% |
| STORE_FAST | 1,320,060 | 50.0% |
| CALL_BUILTIN_O | 600 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,320,480 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,440 | 55.8% |
| LOAD_CONST | 1,080 | 41.9% |
| LOAD_GLOBAL_MODULE | 40 | 1.6% |
| COMPARE_OP | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,560 | 60.5% |
| STORE_FAST | 480 | 18.6% |
| EXTENDED_ARG | 480 | 18.6% |
| POP_JUMP_IF_TRUE | 60 | 2.3% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,560 | 80.0% |
| LOAD_FAST | 580 | 18.1% |
| COMPARE_OP | 60 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,580 | 80.6% |
| POP_JUMP_IF_TRUE | 620 | 19.4% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,200,000 | 99.9% |
| GET_ITER | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,200,000 | 99.9% |
| POP_TOP | 960 | 0.1% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,020 | 42.9% |
| SWAP | 540 | 22.7% |
| LOAD_FAST | 540 | 22.7% |
| JUMP_BACKWARD | 280 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,660 | 69.7% |
| STORE_FAST_LOAD_FAST | 560 | 23.5% |
| RETURN_CONST | 160 | 6.7% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 80.0% |
| GET_ITER | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 80.0% |
| LOAD_GLOBAL_MODULE | 40 | 13.3% |
| LOAD_GLOBAL | 20 | 6.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,320,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,320,540 | 100.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,660 | 98.8% |
| LOAD_ATTR | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,660 | 98.8% |
| LOAD_ATTR | 20 | 1.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,405,600 | 81.8% |
| ENTER_EXECUTOR | 1,199,400 | 18.2% |
| LOAD_DEREF | 540 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |
| LOAD_ATTR_MODULE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,962,640 | 60.0% |
| CALL | 1,320,500 | 20.0% |
| LOAD_CONST | 1,320,480 | 20.0% |
| CALL_PY_EXACT_ARGS | 1,540 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,643,800 | 66.7% |
| LOAD_ATTR_NONDESCRIPTOR_NO_DICT | 1,321,000 | 33.3% |
| LOAD_ATTR_CLASS | 1,660 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,643,880 | 66.7% |
| STORE_FAST | 1,321,080 | 33.3% |
| LOAD_FAST | 1,020 | 0.0% |
| BUILD_TUPLE | 480 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,321,480 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,321,000 | 100.0% |
| CALL | 480 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,282,040 | 100.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,282,100 | 100.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,925,300 | 89.2% |
| ENTER_EXECUTOR | 959,520 | 10.8% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 7,923,000 | 89.2% |
| STORE_FAST | 960,540 | 10.8% |
| SWAP | 660 | 0.0% |
| PUSH_EXC_INFO | 660 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,963,220 | 37.5% |
| RESUME_CHECK | 2,641,980 | 25.0% |
| POP_JUMP_IF_FALSE | 2,641,560 | 25.0% |
| LOAD_FAST | 1,322,520 | 12.5% |
| PUSH_EXC_INFO | 620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,608,400 | 62.5% |
| CALL_ISINSTANCE | 1,321,080 | 12.5% |
| LOAD_DEREF | 1,320,540 | 12.5% |
| LOAD_ATTR | 1,320,540 | 12.5% |
| CHECK_EXC_MATCH | 660 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,641,080 | 50.0% |
| RESUME_CHECK | 1,322,020 | 25.0% |
| NOP | 1,321,020 | 25.0% |
| POP_JUMP_IF_TRUE | 560 | 0.0% |
| SET_FUNCTION_ATTRIBUTE | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,643,800 | 50.0% |
| IS_OP | 1,320,540 | 25.0% |
| CALL_ISINSTANCE | 1,320,540 | 25.0% |
| LOAD_FAST | 1,020 | 0.0% |
| LOAD_FAST_LOAD_FAST | 960 | 0.0% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,320,540 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 6,724,140 | 36.4% |
| LOAD_ATTR_PROPERTY | 5,282,100 | 28.6% |
| CALL | 2,641,440 | 14.3% |
| CALL_PY_EXACT_ARGS | 1,321,560 | 7.1% |
| COPY_FREE_VARS | 1,320,600 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 7,924,140 | 42.8% |
| LOAD_FAST | 3,964,260 | 21.4% |
| LOAD_GLOBAL_BUILTIN | 2,641,980 | 14.3% |
| LOAD_GLOBAL_MODULE | 1,322,020 | 7.1% |
| BUILD_LIST | 1,320,540 | 7.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,962,160 | 50.0% |
| LOAD_FAST | 3,960,080 | 50.0% |
| STORE_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,960,120 | 50.0% |
| LOAD_FAST_LOAD_FAST | 2,641,080 | 33.3% |
| RETURN_CONST | 1,321,080 | 16.7% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,000 | 98.6% |
| TO_BOOL_NONE | 3,360 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 240,000 | 98.6% |
| TO_BOOL_NONE | 3,360 | 1.4% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 2,641,620 | 99.9% |
| RETURN_VALUE | 480 | 0.0% |
| LOAD_FAST | 480 | 0.0% |
| COPY | 480 | 0.0% |
| CALL | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,323,000 | 50.0% |
| POP_JUMP_IF_TRUE | 1,320,540 | 50.0% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,320,000 | 100.0% |
| RETURN_VALUE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,320,000 | 100.0% |
| POP_JUMP_IF_TRUE | 480 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 720,000 | 99.5% |
| TO_BOOL_ALWAYS_TRUE | 3,360 | 0.5% |
| LOAD_FAST | 540 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 720,000 | 99.5% |
| TO_BOOL_ALWAYS_TRUE | 3,360 | 0.5% |
| POP_JUMP_IF_FALSE | 540 | 0.1% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,160 | 41.7% |
| RETURN_VALUE | 960 | 34.5% |
| STORE_FAST_LOAD_FAST | 560 | 20.1% |
| TO_BOOL | 60 | 2.2% |
| COPY | 40 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,240 | 80.6% |
| POP_JUMP_IF_FALSE | 540 | 19.4% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,080 | 100.0% |


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
| specialization.deferred |          960 | 44.9% |
|          hit |         1080 | 50.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 20.0% |
| Failure | 80 | 80.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 80 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1320540 | 21.1% |
| specialization.deopt |         6720 | 0.1% |
|          hit |      4577900 | 73.2% |
|         miss |       356160 | 5.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,780 | 95.5% |
| Failure | 320 | 4.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 320 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1320000 | 99.9% |
|          hit |          660 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 15.8% |
| Failure | 320 | 84.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 320 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4924140 | 29.3% |
|          hit |     11898060 | 70.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 8.9% |
| Failure | 1,640 | 91.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| code complex parameters | 840 | 51.2% |
| cfunc varargs keywords | 320 | 19.5% |
| cmethod | 240 | 14.6% |
| other | 80 | 4.9% |
| cfunc noargs | 60 | 3.7% |
| meth descr varargs | 40 | 2.4% |
| cfunc varargs | 40 | 2.4% |
| class mutable | 20 | 1.2% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         5780 | 98.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2524180 | 100.0% |


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
| specialization.deferred |      1321640 | 4.8% |
|          hit |     26061760 | 95.2% |
|         miss |          660 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 44.7% |
| Failure | 420 | 55.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 320 | 76.2% |
| class method obj | 60 | 14.3% |
| non object slot | 40 | 9.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     15858300 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1320540 | 100.0% |


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
|          hit |      7922280 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         1080 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 157,708,820 | 59.4% |
| Not specialized | 18,985,460 | 7.2% |
| Specialized | 88,664,040 | 33.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 4,924,140 | 55.4% |
| LOAD_ATTR | 1,321,640 | 14.9% |
| TO_BOOL | 1,320,540 | 14.9% |
| BINARY_OP | 1,320,000 | 14.9% |
| BINARY_SUBSCR | 960 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_STR | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_NONE | 178,080 | 49.9% |
| TO_BOOL_ALWAYS_TRUE | 178,080 | 49.9% |
| LOAD_ATTR_SLOT | 660 | 0.2% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| TO_BOOL_STR | 0 | 0.0% |
| TO_BOOL_LIST | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 8,044,740 | 43.5% |
| Calls to Python functions inlined | 10,449,300 | 56.5% |
| Calls via PyEval_EvalFrame (total) | 8,044,740 | 43.5% |
| Calls via PyEval_EvalFrame (vector) | 7,924,680 | 42.8% |
| Calls via PyEval_EvalFrame (generator) | 120,060 | 0.6% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 7,924,680 | 42.8% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 2,641,560 | 14.3% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 17,173,020 | 92.9% |
| Frame objects created | 660 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 16,937,634 | 28.1% |
| Frees to freelist | 16,937,634 |  |
| Allocations | 43,344,334 | 71.9% |
| Allocations to 512 bytes | 43,344,334 | 71.9% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 46,947,834 |  |
| New values | 0 |  |
| Interpreter increfs | 144,816,740 | 77.9% |
| Interpreter decrefs | 151,551,160 | 62.7% |
| Increfs | 41,074,544 | 22.1% |
| Decrefs | 90,060,552 | 37.3% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 3,433 |  |
| Method cache misses | 7 |  |
| Method cache collisions | 11 |  |
| Method cache dunder hits | 11,888,656 |  |
| Method cache dunder misses | 4 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 440 | 0 | 2,560,800 |
| 1 | 40 | 0 | 1,080,680 |
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
| Optimization attempts | 70,640 |  |
| Traces created | 40 | 0.1% |
| Traces executed | 3,481,340 |  |
| Uops executed | 33,605,280 | 9 |
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
| <= 16 | 20 | 50.0% |
| <= 32 | 20 | 50.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 50.0% |
| <= 32 | 20 | 50.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,322,380 | 38.0% |
| <= 16 | 2,158,920 | 62.0% |
| <= 32 | 40 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 9,001,780 | 26.8% | 26.8% |
| _POP_JUMP_IF_TRUE | 4,440,860 | 13.2% | 40.0% |
| _EXIT_TRACE | 3,481,340 | 10.4% | 50.4% |
| _ITER_CHECK_LIST | 2,160,800 | 6.4% | 56.8% |
| _IS_ITER_EXHAUSTED_LIST | 2,160,800 | 6.4% | 63.2% |
| _ITER_NEXT_LIST | 2,158,960 | 6.4% | 69.6% |
| STORE_FAST | 2,158,960 | 6.4% | 76.1% |
| LOAD_FAST | 2,039,060 | 6.1% | 82.1% |
| POP_TOP | 1,322,380 | 3.9% | 86.1% |
| _ITER_CHECK_TUPLE | 1,320,540 | 3.9% | 90.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 1,320,540 | 3.9% | 93.9% |
| LOAD_DEREF | 1,079,460 | 3.2% | 97.1% |
| TO_BOOL_BOOL | 959,520 | 2.9% | 100.0% |
| _POP_JUMP_IF_FALSE | 80 | 0.0% | 100.0% |
| _LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| _GUARD_GLOBALS_VERSION | 40 | 0.0% | 100.0% |
| TO_BOOL_STR | 40 | 0.0% | 100.0% |
| LOAD_CONST | 40 | 0.0% | 100.0% |
| COMPARE_OP_STR | 40 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| FOR_ITER_GEN | 70,600 |
| LOAD_ATTR_MODULE | 20 |
| LOAD_ATTR_METHOD_NO_DICT | 20 |


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
