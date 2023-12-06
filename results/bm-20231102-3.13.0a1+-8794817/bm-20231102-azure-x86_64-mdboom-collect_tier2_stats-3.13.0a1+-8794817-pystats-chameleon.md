
# Pystats results

- benchmark: chameleon
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 176,689,640 | 21.4% | 21.4% |  |
| LOAD_CONST | 94,101,200 | 11.4% | 32.8% |  |
| STORE_FAST | 80,984,440 | 9.8% | 42.7% |  |
| PUSH_NULL | 50,248,360 | 6.1% | 48.8% |  |
| IS_OP | 45,764,480 | 5.6% | 54.3% |  |
| LOAD_GLOBAL_MODULE | 44,496,240 | 5.4% | 59.7% |  |
| LOAD_GLOBAL_BUILTIN | 43,526,180 | 5.3% | 65.0% |  |
| POP_JUMP_IF_FALSE | 36,165,200 | 4.4% | 69.4% |  |
| POP_TOP | 26,245,840 | 3.2% | 72.6% |  |
| CALL_BUILTIN_O | 26,241,020 | 3.2% | 75.7% |  |
| LOAD_FAST_LOAD_FAST | 18,568,320 | 2.3% | 78.0% |  |
| RESUME_CHECK | 17,609,440 | 2.1% | 80.1% |  |
| RETURN_VALUE | 17,287,120 | 2.1% | 82.2% |  |
| POP_JUMP_IF_TRUE | 13,120,640 | 1.6% | 83.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 10,442,040 | 1.3% | 85.1% | 100.0% |
| LOAD_ATTR_CLASS | 10,243,820 | 1.2% | 86.3% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 10,241,140 | 1.2% | 87.6% |  |
| POP_JUMP_IF_NONE | 9,922,560 | 1.2% | 88.8% |  |
| STORE_SUBSCR | 7,364,140 | 0.9% | 89.7% |  |
| CALL_PY_EXACT_ARGS | 6,721,180 | 0.8% | 90.5% |  |
| COPY_FREE_VARS | 6,400,720 | 0.8% | 91.3% |  |
| POP_JUMP_IF_NOT_NONE | 6,400,640 | 0.8% | 92.0% |  |
| TO_BOOL_BOOL | 6,400,580 | 0.8% | 92.8% |  |
| CALL_TYPE_1 | 6,399,980 | 0.8% | 93.6% |  |
| CALL_STR_1 | 6,399,960 | 0.8% | 94.4% |  |
| CALL | 4,167,420 | 0.5% | 94.9% |  |
| CALL_BUILTIN_FAST | 4,164,280 | 0.5% | 95.4% |  |
| JUMP_FORWARD | 3,841,280 | 0.5% | 95.8% |  |
| NOP | 3,522,000 | 0.4% | 96.3% |  |
| DELETE_SUBSCR | 3,520,640 | 0.4% | 96.7% |  |
| COMPARE_OP_INT | 3,520,020 | 0.4% | 97.1% |  |
| BINARY_OP_SUBTRACT_INT | 3,519,960 | 0.4% | 97.5% |  |
| ENTER_EXECUTOR | 3,519,040 | 0.4% | 98.0% |  |
| BINARY_OP | 3,201,180 | 0.4% | 98.4% |  |
| LOAD_DEREF | 3,200,160 | 0.4% | 98.8% |  |
| BINARY_OP_ADD_INT | 3,199,980 | 0.4% | 99.1% |  |
| BINARY_OP_ADD_UNICODE | 3,199,980 | 0.4% | 99.5% |  |
| INTERPRETER_EXIT | 643,920 | 0.1% | 99.6% |  |
| STORE_ATTR_SLOT | 642,480 | 0.1% | 99.7% |  |
| RETURN_CONST | 322,560 | 0.0% | 99.7% |  |
| BUILD_TUPLE | 321,920 | 0.0% | 99.8% |  |
| FOR_ITER_LIST | 321,880 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 321,300 | 0.0% | 99.8% |  |
| EXTENDED_ARG | 321,280 | 0.0% | 99.9% |  |
| GET_ITER | 320,720 | 0.0% | 99.9% |  |
| CALL_LEN | 320,620 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 320,600 | 0.0% | 100.0% |  |
| LOAD_ATTR | 7,560 | 0.0% | 100.0% |  |
| BUILD_MAP | 2,560 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 2,480 | 0.0% | 100.0% |  |
| MAKE_CELL | 1,920 | 0.0% | 100.0% |  |
| STORE_DEREF | 1,920 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,720 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 1,700 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 1,360 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 1,280 | 0.0% | 100.0% |  |
| DICT_MERGE | 1,280 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 1,280 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 1,240 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 1,240 | 0.0% | 100.0% |  |
| CALL_KW | 640 | 0.0% | 100.0% |  |
| CONTAINS_OP | 640 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 620 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 620 | 0.0% | 100.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 620 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 620 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 620 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 620 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 380 | 0.0% | 100.0% |  |
| RESUME | 240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 200 | 0.0% | 100.0% |  |
| STORE_ATTR | 160 | 0.0% | 100.0% |  |
| TO_BOOL | 120 | 0.0% | 100.0% |  |
| COMPARE_OP | 120 | 0.0% | 100.0% |  |
| FOR_ITER | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 62,736,040 | 7.6% | 7.6% |
| LOAD_FAST PUSH_NULL | 46,406,280 | 5.6% | 13.2% |
| PUSH_NULL LOAD_CONST | 37,127,680 | 4.5% | 17.7% |
| IS_OP POP_JUMP_IF_FALSE | 29,764,480 | 3.6% | 21.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 29,764,480 | 3.6% | 25.0% |
| CALL_BUILTIN_O POP_TOP | 26,240,380 | 3.2% | 28.1% |
| LOAD_FAST LOAD_CONST | 20,805,840 | 2.5% | 30.7% |
| LOAD_CONST CALL_BUILTIN_O | 19,840,200 | 2.4% | 33.1% |
| LOAD_GLOBAL_BUILTIN IS_OP | 19,199,900 | 2.3% | 35.4% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 19,199,800 | 2.3% | 37.7% |
| LOAD_FAST RETURN_VALUE | 16,643,920 | 2.0% | 39.8% |
| LOAD_CONST LOAD_CONST | 16,000,640 | 1.9% | 41.7% |
| LOAD_GLOBAL_MODULE IS_OP | 13,764,400 | 1.7% | 43.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 13,764,320 | 1.7% | 45.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 13,761,860 | 1.7% | 46.7% |
| STORE_FAST LOAD_CONST | 13,441,920 | 1.6% | 48.3% |
| POP_TOP LOAD_FAST | 13,123,200 | 1.6% | 49.9% |
| LOAD_GLOBAL_MODULE STORE_FAST | 13,122,380 | 1.6% | 51.5% |
| PUSH_NULL LOAD_FAST | 12,800,080 | 1.6% | 53.1% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 10,245,060 | 1.2% | 54.3% |
| LOAD_ATTR_CLASS LOAD_FAST_LOAD_FAST | 10,243,820 | 1.2% | 55.6% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 10,243,800 | 1.2% | 56.8% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR_CLASS | 10,243,800 | 1.2% | 58.0% |
| LOAD_GLOBAL_MODULE CALL_METHOD_DESCRIPTOR_FAST | 10,243,800 | 1.2% | 59.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 10,243,800 | 1.2% | 60.5% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 10,241,140 | 1.2% | 61.8% |
| LOAD_CONST CALL_BOUND_METHOD_EXACT_ARGS | 10,241,000 | 1.2% | 63.0% |
| LOAD_FAST POP_JUMP_IF_NONE | 9,922,560 | 1.2% | 64.2% |
| LOAD_CONST STORE_FAST | 9,921,920 | 1.2% | 65.4% |
| POP_TOP LOAD_GLOBAL_MODULE | 9,921,040 | 1.2% | 66.6% |
| RETURN_VALUE STORE_FAST | 9,601,240 | 1.2% | 67.8% |
| IS_OP POP_JUMP_IF_TRUE | 9,600,000 | 1.2% | 68.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 9,599,360 | 1.2% | 70.1% |
| STORE_SUBSCR LOAD_FAST | 7,040,640 | 0.9% | 71.0% |
| RESUME_CHECK LOAD_FAST | 6,723,700 | 0.8% | 71.8% |
| LOAD_FAST LOAD_FAST | 6,723,200 | 0.8% | 72.6% |
| LOAD_CONST LOAD_GLOBAL_MODULE | 6,721,080 | 0.8% | 73.4% |
| COPY_FREE_VARS RESUME_CHECK | 6,400,660 | 0.8% | 74.2% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 6,400,640 | 0.8% | 75.0% |
| POP_JUMP_IF_NONE LOAD_FAST | 6,400,640 | 0.8% | 75.7% |
| IS_OP STORE_FAST | 6,400,000 | 0.8% | 76.5% |
| LOAD_FAST STORE_FAST | 6,400,000 | 0.8% | 77.3% |
| LOAD_FAST_LOAD_FAST IS_OP | 6,400,000 | 0.8% | 78.1% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 6,400,000 | 0.8% | 78.8% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 6,400,000 | 0.8% | 79.6% |
| CALL_TYPE_1 STORE_FAST | 6,399,980 | 0.8% | 80.4% |
| LOAD_FAST CALL_TYPE_1 | 6,399,960 | 0.8% | 81.2% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 6,399,960 | 0.8% | 81.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 6,399,960 | 0.8% | 82.7% |
| LOAD_FAST TO_BOOL_BOOL | 6,399,920 | 0.8% | 83.5% |
| LOAD_CONST LOAD_FAST | 3,843,840 | 0.5% | 84.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 3,842,320 | 0.5% | 84.4% |
| LOAD_CONST STORE_SUBSCR | 3,841,960 | 0.5% | 84.9% |
| CALL_BUILTIN_FAST STORE_FAST | 3,841,200 | 0.5% | 85.4% |
| LOAD_FAST CALL | 3,521,720 | 0.4% | 85.8% |
| DELETE_SUBSCR JUMP_FORWARD | 3,520,640 | 0.4% | 86.2% |
| RETURN_VALUE LOAD_CONST | 3,520,640 | 0.4% | 86.6% |
| JUMP_FORWARD LOAD_FAST | 3,520,640 | 0.4% | 87.1% |
| LOAD_CONST DELETE_SUBSCR | 3,520,640 | 0.4% | 87.5% |
| LOAD_GLOBAL_MODULE CALL_BUILTIN_FAST | 3,520,520 | 0.4% | 87.9% |
| LOAD_CONST COMPARE_OP_INT | 3,519,960 | 0.4% | 88.4% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 3,519,960 | 0.4% | 88.8% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 3,519,960 | 0.4% | 89.2% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 3,519,920 | 0.4% | 89.6% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 3,519,920 | 0.4% | 90.1% |
| LOAD_FAST CALL_BUILTIN_O | 3,200,600 | 0.4% | 90.5% |
| NOP LOAD_DEREF | 3,200,080 | 0.4% | 90.8% |
| LOAD_DEREF PUSH_NULL | 3,200,080 | 0.4% | 91.2% |
| LOAD_FAST BINARY_OP | 3,200,040 | 0.4% | 91.6% |
| CALL LOAD_CONST | 3,200,000 | 0.4% | 92.0% |
| LOAD_CONST IS_OP | 3,200,000 | 0.4% | 92.4% |
| LOAD_FAST IS_OP | 3,200,000 | 0.4% | 92.8% |
| POP_JUMP_IF_NONE NOP | 3,200,000 | 0.4% | 93.2% |
| BINARY_OP_ADD_INT STORE_FAST | 3,199,980 | 0.4% | 93.6% |
| BINARY_OP_ADD_UNICODE STORE_FAST | 3,199,980 | 0.4% | 93.9% |
| CALL_STR_1 STORE_FAST | 3,199,980 | 0.4% | 94.3% |
| RETURN_VALUE CALL_STR_1 | 3,199,960 | 0.4% | 94.7% |
| BINARY_OP CALL_BUILTIN_O | 3,199,960 | 0.4% | 95.1% |
| LOAD_CONST BINARY_OP_ADD_INT | 3,199,960 | 0.4% | 95.5% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 3,199,960 | 0.4% | 95.9% |
| LOAD_FAST CALL_STR_1 | 3,199,960 | 0.4% | 96.3% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 3,199,960 | 0.4% | 96.7% |
| CALL_STR_1 BINARY_OP_ADD_UNICODE | 3,199,960 | 0.4% | 97.0% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 3,199,960 | 0.4% | 97.4% |
| ENTER_EXECUTOR STORE_SUBSCR | 3,198,720 | 0.4% | 97.8% |
| POP_TOP ENTER_EXECUTOR | 2,879,960 | 0.3% | 98.2% |
| CACHE RESUME_CHECK | 643,160 | 0.1% | 98.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 641,200 | 0.1% | 98.3% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 641,200 | 0.1% | 98.4% |
| RETURN_VALUE PUSH_NULL | 640,640 | 0.1% | 98.5% |
| RETURN_VALUE INTERPRETER_EXIT | 322,640 | 0.0% | 98.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 322,480 | 0.0% | 98.6% |
| LOAD_FAST CALL_BUILTIN_FAST | 321,800 | 0.0% | 98.6% |
| RETURN_CONST INTERPRETER_EXIT | 321,280 | 0.0% | 98.6% |
| FOR_ITER_LIST STORE_FAST | 321,240 | 0.0% | 98.7% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 321,240 | 0.0% | 98.7% |
| STORE_ATTR_SLOT RETURN_CONST | 321,240 | 0.0% | 98.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 321,220 | 0.0% | 98.8% |
| CALL STORE_FAST | 320,960 | 0.0% | 98.8% |
| LOAD_FAST GET_ITER | 320,720 | 0.0% | 98.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 643,160 | 99.9% |
| COPY_FREE_VARS | 640 | 0.1% |
| RESUME | 120 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 80 | 40.0% |
| STORE_FAST | 60 | 30.0% |
| STORE_DEREF | 40 | 20.0% |
| BINARY_SUBSCR_DICT | 20 | 10.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,520,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 3,520,640 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 319,980 | 99.8% |
| EXTENDED_ARG | 640 | 0.2% |
| FOR_ITER_RANGE | 60 | 0.0% |
| FOR_ITER | 40 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 322,640 | 50.1% |
| RETURN_CONST | 321,280 | 49.9% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 1,280 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 3,200,000 | 90.9% |
| RESUME_CHECK | 320,620 | 9.1% |
| STORE_FAST | 1,280 | 0.0% |
| POP_TOP | 80 | 0.0% |
| RESUME | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 3,200,080 | 90.9% |
| LOAD_GLOBAL_BUILTIN | 319,960 | 9.1% |
| LOAD_FAST | 1,280 | 0.0% |
| LOAD_GLOBAL_MODULE | 640 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 26,240,380 | 100.0% |
| CALL_BUILTIN_FAST | 3,100 | 0.0% |
| RETURN_CONST | 1,280 | 0.0% |
| CALL | 1,080 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,123,200 | 50.0% |
| LOAD_GLOBAL_MODULE | 9,921,040 | 37.8% |
| ENTER_EXECUTOR | 2,879,960 | 11.0% |
| EXTENDED_ARG | 319,360 | 1.2% |
| JUMP_BACKWARD | 680 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,406,280 | 92.4% |
| LOAD_DEREF | 3,200,080 | 6.4% |
| RETURN_VALUE | 640,640 | 1.3% |
| LOAD_ATTR | 660 | 0.0% |
| LOAD_SUPER_ATTR_ATTR | 620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 37,127,680 | 73.9% |
| LOAD_FAST | 12,800,080 | 25.5% |
| CALL | 320,600 | 0.6% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,643,920 | 96.3% |
| BUILD_TUPLE | 320,640 | 1.9% |
| CALL_BUILTIN_FAST | 319,980 | 1.9% |
| CALL_FUNCTION_EX | 1,280 | 0.0% |
| RETURN_VALUE | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,601,240 | 55.5% |
| LOAD_CONST | 3,520,640 | 20.4% |
| CALL_STR_1 | 3,199,960 | 18.5% |
| PUSH_NULL | 640,640 | 3.7% |
| INTERPRETER_EXIT | 322,640 | 1.9% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,841,960 | 52.2% |
| ENTER_EXECUTOR | 3,198,720 | 43.4% |
| LOAD_FAST_LOAD_FAST | 320,640 | 4.4% |
| STORE_SUBSCR | 2,820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,040,640 | 95.6% |
| LOAD_FAST_LOAD_FAST | 320,640 | 4.4% |
| STORE_SUBSCR | 2,820 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| STORE_SUBSCR_DICT | 20 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 66.7% |
| LOAD_ATTR | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 60 | 50.0% |
| POP_JUMP_IF_FALSE | 40 | 33.3% |
| POP_JUMP_IF_TRUE | 20 | 16.7% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,200,040 | 100.0% |
| BINARY_OP | 980 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| CALL | 20 | 0.0% |
| CALL_STR_1 | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 3,199,960 | 100.0% |
| BINARY_OP | 980 | 0.0% |
| STORE_FAST | 100 | 0.0% |
| CALL | 40 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 40 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,280 | 50.0% |
| STORE_FAST | 640 | 25.0% |
| LOAD_GLOBAL_MODULE | 620 | 24.2% |
| LOAD_GLOBAL | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,280 | 50.0% |
| CALL | 640 | 25.0% |
| STORE_FAST | 640 | 25.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 320,640 | 99.6% |
| LOAD_FAST | 1,280 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 320,640 | 99.6% |
| LOAD_CONST | 1,280 | 0.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,521,720 | 84.5% |
| LOAD_FAST_LOAD_FAST | 320,680 | 7.7% |
| PUSH_NULL | 320,600 | 7.7% |
| CALL | 2,140 | 0.1% |
| LOAD_CONST | 920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,200,000 | 76.8% |
| STORE_FAST | 320,960 | 7.7% |
| LOAD_FAST_LOAD_FAST | 320,640 | 7.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 320,560 | 7.7% |
| CALL | 2,140 | 0.1% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 1,280 | 94.1% |
| LOAD_FAST | 80 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,280 | 94.1% |
| COPY_FREE_VARS | 80 | 5.9% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 600 | 93.8% |
| CALL | 40 | 6.2% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 60 | 50.0% |
| POP_JUMP_IF_TRUE | 40 | 33.3% |
| POP_JUMP_IF_FALSE | 20 | 16.7% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 640 | 100.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 6,399,960 | 100.0% |
| CACHE | 640 | 0.0% |
| CALL_FUNCTION_EX | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,400,660 | 100.0% |
| RESUME | 60 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 1,280 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,879,960 | 81.8% |
| POP_JUMP_IF_TRUE | 319,660 | 9.1% |
| EXTENDED_ARG | 319,320 | 9.1% |
| JUMP_BACKWARD | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 3,198,720 | 90.9% |
| LOAD_FAST | 320,040 | 9.1% |
| CALL | 280 | 0.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 319,360 | 99.4% |
| GET_ITER | 640 | 0.2% |
| JUMP_BACKWARD | 640 | 0.2% |
| POP_JUMP_IF_TRUE | 640 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 319,320 | 99.4% |
| FOR_ITER_LIST | 1,240 | 0.4% |
| JUMP_BACKWARD | 680 | 0.2% |
| FOR_ITER | 40 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 40 | 33.3% |
| EXTENDED_ARG | 40 | 33.3% |
| JUMP_BACKWARD | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| FOR_ITER_LIST | 40 | 33.3% |
| FOR_ITER_RANGE | 20 | 16.7% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 19,199,900 | 42.0% |
| LOAD_GLOBAL_MODULE | 13,764,400 | 30.1% |
| LOAD_FAST_LOAD_FAST | 6,400,000 | 14.0% |
| LOAD_CONST | 3,200,000 | 7.0% |
| LOAD_FAST | 3,200,000 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,764,480 | 65.0% |
| POP_JUMP_IF_TRUE | 9,600,000 | 21.0% |
| STORE_FAST | 6,400,000 | 14.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 680 | 40.0% |
| EXTENDED_ARG | 680 | 40.0% |
| POP_JUMP_IF_TRUE | 340 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 640 | 37.6% |
| FOR_ITER_LIST | 620 | 36.5% |
| FOR_ITER_RANGE | 300 | 17.6% |
| ENTER_EXECUTOR | 100 | 5.9% |
| FOR_ITER | 40 | 2.4% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 3,520,640 | 91.7% |
| CALL_BUILTIN_CLASS | 320,620 | 8.3% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,520,640 | 91.7% |
| STORE_FAST | 320,640 | 8.3% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,640 | 87.8% |
| LOAD_ATTR | 800 | 10.6% |
| LOAD_GLOBAL | 60 | 0.8% |
| LOAD_GLOBAL_MODULE | 40 | 0.5% |
| LOAD_GLOBAL_BUILTIN | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,240 | 42.9% |
| LOAD_FAST | 1,280 | 16.9% |
| LOAD_ATTR | 800 | 10.6% |
| PUSH_NULL | 660 | 8.7% |
| CALL_BUILTIN_CLASS | 600 | 7.9% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 37,127,680 | 39.5% |
| LOAD_FAST | 20,805,840 | 22.1% |
| LOAD_CONST | 16,000,640 | 17.0% |
| STORE_FAST | 13,441,920 | 14.3% |
| RETURN_VALUE | 3,520,640 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 19,840,200 | 21.1% |
| LOAD_CONST | 16,000,640 | 17.0% |
| CALL_BOUND_METHOD_EXACT_ARGS | 10,241,000 | 10.9% |
| STORE_FAST | 9,921,920 | 10.5% |
| LOAD_GLOBAL_MODULE | 6,721,080 | 7.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 3,200,080 | 100.0% |
| STORE_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,200,080 | 100.0% |
| STORE_FAST | 80 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 62,736,040 | 35.5% |
| POP_JUMP_IF_FALSE | 29,764,480 | 16.8% |
| LOAD_GLOBAL_BUILTIN | 13,761,860 | 7.8% |
| POP_TOP | 13,123,200 | 7.4% |
| PUSH_NULL | 12,800,080 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 46,406,280 | 26.3% |
| LOAD_CONST | 20,805,840 | 11.8% |
| LOAD_GLOBAL_BUILTIN | 19,199,800 | 10.9% |
| RETURN_VALUE | 16,643,920 | 9.4% |
| LOAD_GLOBAL_MODULE | 13,764,320 | 7.8% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 10,243,820 | 55.2% |
| POP_JUMP_IF_NOT_NONE | 6,400,000 | 34.5% |
| LOAD_GLOBAL_MODULE | 321,240 | 1.7% |
| STORE_SUBSCR | 320,640 | 1.7% |
| CALL | 320,640 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 10,243,800 | 55.2% |
| IS_OP | 6,400,000 | 34.5% |
| STORE_ATTR_SLOT | 641,200 | 3.5% |
| CALL | 320,680 | 1.7% |
| STORE_SUBSCR | 320,640 | 1.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 20.9% |
| STORE_FAST | 320 | 18.6% |
| POP_TOP | 240 | 14.0% |
| LOAD_CONST | 240 | 14.0% |
| POP_JUMP_IF_FALSE | 120 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 560 | 32.6% |
| LOAD_GLOBAL_BUILTIN | 300 | 17.4% |
| LOAD_FAST | 220 | 12.8% |
| IS_OP | 180 | 10.5% |
| STORE_FAST | 180 | 10.5% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 20 | 50.0% |
| LOAD_SUPER_ATTR_ATTR | 20 | 50.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 1,280 | 66.7% |
| CALL_PY_WITH_DEFAULTS | 620 | 32.3% |
| CALL | 20 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 1,280 | 66.7% |
| RESUME_CHECK | 620 | 32.3% |
| RESUME | 20 | 1.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 29,764,480 | 82.3% |
| TO_BOOL_BOOL | 6,399,960 | 17.7% |
| CONTAINS_OP | 640 | 0.0% |
| COMPARE_OP_INT | 60 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,764,480 | 82.3% |
| LOAD_GLOBAL_BUILTIN | 6,400,000 | 17.7% |
| LOAD_GLOBAL_MODULE | 600 | 0.0% |
| LOAD_GLOBAL | 120 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,922,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,400,640 | 64.5% |
| NOP | 3,200,000 | 32.2% |
| LOAD_GLOBAL_BUILTIN | 320,600 | 3.2% |
| LOAD_CONST | 640 | 0.0% |
| LOAD_GLOBAL_MODULE | 600 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,400,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,400,000 | 100.0% |
| LOAD_FAST | 640 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 9,600,000 | 73.2% |
| COMPARE_OP_INT | 3,519,960 | 26.8% |
| TO_BOOL_BOOL | 620 | 0.0% |
| COMPARE_OP | 40 | 0.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,599,360 | 73.2% |
| LOAD_GLOBAL_BUILTIN | 3,199,960 | 24.4% |
| ENTER_EXECUTOR | 319,660 | 2.4% |
| EXTENDED_ARG | 640 | 0.0% |
| RETURN_CONST | 640 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 321,240 | 99.6% |
| POP_TOP | 640 | 0.2% |
| POP_JUMP_IF_TRUE | 640 | 0.2% |
| STORE_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 321,280 | 99.6% |
| POP_TOP | 1,280 | 0.4% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 1,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,280 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 50.0% |
| LOAD_FAST_LOAD_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 80 | 50.0% |
| RETURN_CONST | 40 | 25.0% |
| LOAD_FAST | 20 | 12.5% |
| LOAD_FAST_LOAD_FAST | 20 | 12.5% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,240 | 64.6% |
| LOAD_GLOBAL_MODULE | 620 | 32.3% |
| BINARY_SUBSCR | 40 | 2.1% |
| LOAD_GLOBAL | 20 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 13,122,380 | 16.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 10,245,060 | 12.7% |
| LOAD_CONST | 9,921,920 | 12.3% |
| RETURN_VALUE | 9,601,240 | 11.9% |
| IS_OP | 6,400,000 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,736,040 | 77.5% |
| LOAD_CONST | 13,441,920 | 16.6% |
| LOAD_GLOBAL_MODULE | 3,842,320 | 4.7% |
| LOAD_GLOBAL_BUILTIN | 641,200 | 0.8% |
| STORE_FAST | 320,640 | 0.4% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 120 | 50.0% |
| COPY_FREE_VARS | 60 | 25.0% |
| CALL | 40 | 16.7% |
| MAKE_CELL | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 58.3% |
| LOAD_GLOBAL | 60 | 25.0% |
| NOP | 20 | 8.3% |
| LOAD_FAST_LOAD_FAST | 20 | 8.3% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,199,960 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,199,980 | 100.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_STR_1 | 3,199,960 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,199,980 | 100.0% |


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
| LOAD_CONST | 3,519,920 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,519,960 | 100.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 600 | 96.8% |
| BINARY_SUBSCR | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 620 | 100.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,400 | 96.8% |
| BINARY_SUBSCR | 80 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,480 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 10,241,000 | 100.0% |
| CALL | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 10,241,140 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,640 | 99.8% |
| LOAD_ATTR | 600 | 0.2% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 320,620 | 99.8% |
| STORE_FAST | 680 | 0.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,520,520 | 84.5% |
| LOAD_FAST | 321,800 | 7.7% |
| LOAD_FAST_LOAD_FAST | 319,960 | 7.7% |
| CALL_KW | 600 | 0.0% |
| LOAD_CONST | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,841,200 | 92.2% |
| RETURN_VALUE | 319,980 | 7.7% |
| POP_TOP | 3,100 | 0.1% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 19,840,200 | 75.6% |
| LOAD_FAST | 3,200,600 | 12.2% |
| BINARY_OP | 3,199,960 | 12.2% |
| CALL | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 26,240,380 | 100.0% |
| RETURN_VALUE | 640 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 320,600 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320,620 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 10,243,800 | 98.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 196,980 | 1.9% |
| LOAD_CONST | 1,200 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 10,245,060 | 98.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 196,980 | 1.9% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,519,920 | 52.4% |
| LOAD_GLOBAL_MODULE | 3,199,960 | 47.6% |
| LOAD_FAST | 600 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 600 | 0.0% |
| CALL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 6,399,960 | 95.2% |
| RESUME_CHECK | 321,220 | 4.8% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 96.8% |
| CALL | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 620 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,199,960 | 50.0% |
| LOAD_FAST | 3,199,960 | 50.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,199,980 | 50.0% |
| BINARY_OP_ADD_UNICODE | 3,199,960 | 50.0% |
| BINARY_OP | 20 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,399,960 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,399,980 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,519,960 | 100.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 3,519,960 | 100.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 319,980 | 99.4% |
| EXTENDED_ARG | 1,240 | 0.4% |
| JUMP_BACKWARD | 620 | 0.2% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 321,240 | 99.8% |
| LOAD_FAST | 640 | 0.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 300 | 78.9% |
| GET_ITER | 60 | 15.8% |
| FOR_ITER | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 340 | 89.5% |
| LOAD_FAST | 40 | 10.5% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 10,243,800 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 10,243,820 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 96.8% |
| LOAD_ATTR | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 620 | 100.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 96.8% |
| LOAD_ATTR | 40 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,240 | 100.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 96.8% |
| LOAD_ATTR | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 600 | 96.8% |
| CALL | 20 | 3.2% |


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

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200 | 96.8% |
| LOAD_ATTR | 40 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 620 | 50.0% |
| CALL_BUILTIN_FAST | 600 | 48.4% |
| CALL | 20 | 1.6% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 19,199,800 | 44.1% |
| RESUME_CHECK | 10,243,800 | 23.5% |
| POP_JUMP_IF_FALSE | 6,400,000 | 14.7% |
| LOAD_CONST | 3,199,960 | 7.4% |
| POP_JUMP_IF_TRUE | 3,199,960 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 19,199,900 | 44.1% |
| LOAD_FAST | 13,761,860 | 31.6% |
| LOAD_ATTR_CLASS | 10,243,800 | 23.5% |
| LOAD_FAST_LOAD_FAST | 319,980 | 0.7% |
| LOAD_GLOBAL_MODULE | 600 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,764,320 | 30.9% |
| LOAD_FAST_LOAD_FAST | 10,243,800 | 23.0% |
| POP_TOP | 9,921,040 | 22.3% |
| LOAD_CONST | 6,721,080 | 15.1% |
| STORE_FAST | 3,842,320 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 13,764,400 | 30.9% |
| STORE_FAST | 13,122,380 | 29.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 10,243,800 | 23.0% |
| CALL_BUILTIN_FAST | 3,520,520 | 7.9% |
| CALL_PY_EXACT_ARGS | 3,199,960 | 7.2% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 96.8% |
| LOAD_SUPER_ATTR | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 620 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 10,241,140 | 58.2% |
| COPY_FREE_VARS | 6,400,660 | 36.3% |
| CACHE | 643,160 | 3.7% |
| CALL_PY_EXACT_ARGS | 321,220 | 1.8% |
| BINARY_SUBSCR_GETITEM | 2,480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 10,243,800 | 58.2% |
| LOAD_FAST | 6,723,700 | 38.2% |
| NOP | 320,620 | 1.8% |
| LOAD_FAST_LOAD_FAST | 320,620 | 1.8% |
| LOAD_GLOBAL_MODULE | 640 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 641,200 | 99.8% |
| LOAD_FAST | 1,200 | 0.2% |
| STORE_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 321,240 | 50.0% |
| LOAD_FAST_LOAD_FAST | 320,620 | 49.9% |
| LOAD_FAST | 620 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 600 | 96.8% |
| STORE_SUBSCR | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 600 | 96.8% |
| LOAD_GLOBAL | 20 | 3.2% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,399,920 | 100.0% |
| LOAD_ATTR | 600 | 0.0% |
| TO_BOOL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,399,960 | 100.0% |
| POP_JUMP_IF_TRUE | 620 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 320,560 | 100.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 320,600 | 100.0% |


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
|     deferred | 3,200,100 | 24.4% |
|          hit | 9,919,980 | 75.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 9.3% |
| Failure | 980 | 90.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 980 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 3.0% |
|          hit | 3,100 | 93.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,967,380 | 4.6% |
|          hit | 71,052,480 | 82.9% |
|         miss | 10,440,800 | 12.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 197,900 | 98.9% |
| Failure | 2,140 | 1.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cmethod | 980 | 45.8% |
| other | 420 | 19.6% |
| no dict | 340 | 15.9% |
| cfunc noargs | 320 | 15.0% |
| class mutable | 80 | 3.7% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 0.0% |
|          hit | 3,520,020 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 0.0% |
|          hit | 322,260 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 6,580 | 0.1% |
|          hit | 10,247,660 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 18.4% |
| Failure | 800 | 81.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 560 | 70.0% |
| shadowed | 80 | 10.0% |
| class attr simple | 80 | 10.0% |
| class attr descriptor | 80 | 10.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 860 | 0.0% |
|          hit | 88,022,420 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 860 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 3.0% |
|          hit | 620 | 93.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
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

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>


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
|     deferred | 80 | 0.0% |
|          hit | 642,480 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 7,361,300 | 100.0% |
|          hit | 620 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.7% |
| Failure | 2,820 | 99.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 2,560 | 90.8% |
| other | 260 | 9.2% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 0.0% |
|          hit | 6,400,580 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 320,600 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 535,838,460 | 65.0% |
| Not specialized | 80,351,900 | 9.7% |
| Specialized hits | 197,821,120 | 24.0% |
| Specialized misses | 10,440,800 | 1.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_SUBSCR | 7,361,300 | 50.6% |
| CALL | 3,967,380 | 27.3% |
| BINARY_OP | 3,200,100 | 22.0% |
| LOAD_ATTR | 6,580 | 0.0% |
| LOAD_GLOBAL | 860 | 0.0% |
| BINARY_SUBSCR | 100 | 0.0% |
| STORE_ATTR | 80 | 0.0% |
| TO_BOOL | 60 | 0.0% |
| COMPARE_OP | 60 | 0.0% |
| FOR_ITER | 60 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 10,440,800 | 100.0% |
| CACHE | 0 | 0.0% |
| DELETE_SUBSCR | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| MAKE_FUNCTION | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 643,920 | 3.7% |
| Calls to Python functions inlined | 16,965,760 | 96.3% |
| Calls via PyEval_EvalFrame (total) | 643,920 | 3.7% |
| Calls via PyEval_EvalFrame (vector) | 643,920 | 3.7% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 643,920 | 3.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 16,965,420 | 96.3% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 1,296,860 | 4.9% |
| Frees to freelist | 1,296,900 |  |
| Allocations | 25,107,520 | 95.1% |
| Allocations to 512 bytes | 25,106,240 | 95.1% |
| Allocations to 4 kbytes | 640 | 0.0% |
| Allocations over 4 kbytes | 640 | 0.0% |
| Frees | 25,108,060 |  |
| New values | 0 |  |
| Interpreter increfs | 270,186,320 | 88.4% |
| Interpreter decrefs | 289,239,780 | 88.1% |
| Increfs | 35,582,780 | 11.6% |
| Decrefs | 39,112,841 | 11.9% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 20 | 20 / 0 !! |
| Method cache hits | 325,243 |  |
| Method cache misses | 237 |  |
| Method cache collisions | 376 |  |
| Method cache dunder hits | 965,680 |  |
| Method cache dunder misses | 180 |  |


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
| Optimization attempts | 100 |  |
| Traces created | 100 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 3,519,040 |  |
| Uops executed | 37,429,000 | 10.64 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 20.0% |
| <= 32 | 80 | 80.0% |


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
| <= 16 | 100 | 100.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 320,040 | 9.1% |
| <= 16 | 3,199,000 | 90.9% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 7,038,080 | 18.8% | 18.8% |  |
| LOAD_FAST | 6,397,720 | 17.1% | 35.9% |  |
| _EXIT_TRACE | 3,519,040 | 9.4% | 45.3% |  |
| _POP_JUMP_IF_TRUE | 3,519,040 | 9.4% | 54.7% |  |
| _ITER_CHECK_LIST | 3,518,720 | 9.4% | 64.1% |  |
| _IS_ITER_EXHAUSTED_LIST | 3,518,720 | 9.4% | 73.5% |  |
| STORE_FAST | 3,199,000 | 8.5% | 82.0% |  |
| LOAD_CONST | 3,198,720 | 8.5% | 90.6% |  |
| _ITER_NEXT_LIST | 3,198,720 | 8.5% | 99.1% |  |
| POP_TOP | 320,040 | 0.9% | 100.0% |  |
| _ITER_CHECK_RANGE | 320 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_RANGE | 320 | 0.0% | 100.0% |  |
| PUSH_NULL | 280 | 0.0% | 100.0% |  |
| _ITER_NEXT_RANGE | 280 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| STORE_SUBSCR | 80 |
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
Stats gathered on: 2023-11-03
