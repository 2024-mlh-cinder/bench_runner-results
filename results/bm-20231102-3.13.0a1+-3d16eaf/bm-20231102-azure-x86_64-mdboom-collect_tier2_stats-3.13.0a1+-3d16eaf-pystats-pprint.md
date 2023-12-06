
# Pystats results

- benchmark: pprint
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 4,560,017,360 | 19.2% | 19.2% |  |
| STORE_FAST | 2,128,006,720 | 9.0% | 28.2% |  |
| LOAD_GLOBAL_BUILTIN | 1,904,005,220 | 8.0% | 36.2% |  |
| LOAD_CONST | 1,560,004,400 | 6.6% | 42.8% |  |
| POP_JUMP_IF_FALSE | 1,480,004,400 | 6.2% | 49.0% |  |
| TO_BOOL_BOOL | 1,304,001,840 | 5.5% | 54.5% |  |
| LOAD_FAST_LOAD_FAST | 1,120,006,640 | 4.7% | 59.2% |  |
| RETURN_VALUE | 704,000,560 | 3.0% | 62.2% |  |
| POP_JUMP_IF_TRUE | 648,000,480 | 2.7% | 64.9% |  |
| CALL_BUILTIN_FAST | 624,002,340 | 2.6% | 67.5% |  |
| CALL_BUILTIN_O | 568,000,920 | 2.4% | 69.9% |  |
| RESUME_CHECK | 552,002,700 | 2.3% | 72.3% |  |
| LOAD_ATTR | 384,098,340 | 1.6% | 73.9% |  |
| CALL_PY_EXACT_ARGS | 384,002,440 | 1.6% | 75.5% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 376,002,860 | 1.6% | 77.1% |  |
| POP_TOP | 368,001,280 | 1.6% | 78.6% |  |
| BUILD_TUPLE | 360,000,160 | 1.5% | 80.1% |  |
| LOAD_GLOBAL_MODULE | 312,000,940 | 1.3% | 81.5% |  |
| UNPACK_SEQUENCE_TUPLE | 311,999,940 | 1.3% | 82.8% |  |
| CONTAINS_OP | 288,001,520 | 1.2% | 84.0% |  |
| IS_OP | 288,000,160 | 1.2% | 85.2% |  |
| ENTER_EXECUTOR | 263,998,320 | 1.1% | 86.3% |  |
| PUSH_NULL | 256,001,360 | 1.1% | 87.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 232,000,680 | 1.0% | 88.4% |  |
| CALL_TYPE_1 | 192,000,820 | 0.8% | 89.2% |  |
| INTERPRETER_EXIT | 168,000,160 | 0.7% | 89.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 128,000,160 | 0.5% | 90.4% |  |
| EXTENDED_ARG | 120,000,160 | 0.5% | 90.9% |  |
| FOR_ITER_LIST | 112,582,380 | 0.5% | 91.4% | 27.4% |
| RETURN_CONST | 104,000,240 | 0.4% | 91.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 104,000,180 | 0.4% | 92.3% |  |
| CALL | 96,027,540 | 0.4% | 92.7% |  |
| BINARY_OP | 96,025,120 | 0.4% | 93.1% |  |
| BINARY_OP_ADD_INT | 96,000,320 | 0.4% | 93.5% |  |
| DELETE_SUBSCR | 96,000,240 | 0.4% | 93.9% |  |
| GET_ITER | 96,000,160 | 0.4% | 94.3% |  |
| BUILD_LIST | 96,000,160 | 0.4% | 94.7% |  |
| STORE_SUBSCR_DICT | 96,000,140 | 0.4% | 95.1% |  |
| COPY | 96,000,080 | 0.4% | 95.5% |  |
| TO_BOOL_NONE | 96,000,080 | 0.4% | 95.9% |  |
| FORMAT_SIMPLE | 96,000,000 | 0.4% | 96.3% |  |
| CONVERT_VALUE | 96,000,000 | 0.4% | 96.7% |  |
| STORE_ATTR_SLOT | 95,999,960 | 0.4% | 97.1% |  |
| BINARY_SUBSCR_TUPLE_INT | 95,999,920 | 0.4% | 97.5% |  |
| COMPARE_OP_INT | 80,000,160 | 0.3% | 97.9% |  |
| TO_BOOL | 72,019,860 | 0.3% | 98.2% |  |
| CALL_LEN | 56,000,020 | 0.2% | 98.4% |  |
| FOR_ITER_TUPLE | 48,582,380 | 0.2% | 98.6% | 63.5% |
| JUMP_FORWARD | 48,000,240 | 0.2% | 98.8% |  |
| BUILD_STRING | 48,000,000 | 0.2% | 99.0% |  |
| LOAD_ATTR_SLOT | 47,999,920 | 0.2% | 99.2% |  |
| STORE_FAST_STORE_FAST | 32,000,480 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 32,000,080 | 0.1% | 99.5% |  |
| NOP | 24,000,640 | 0.1% | 99.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 24,000,280 | 0.1% | 99.7% |  |
| TO_BOOL_LIST | 24,000,120 | 0.1% | 99.8% |  |
| CALL_KW | 24,000,000 | 0.1% | 99.9% |  |
| BINARY_OP_SUBTRACT_INT | 16,000,300 | 0.1% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 8,000,160 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,560 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 1,780 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 360 | 0.0% | 100.0% |  |
| RESUME | 340 | 0.0% | 100.0% |  |
| COMPARE_OP | 320 | 0.0% | 100.0% |  |
| LOAD_DEREF | 320 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 200 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 160 | 0.0% | 100.0% |  |
| FOR_ITER | 160 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 80 | 0.0% | 100.0% |  |
| POP_EXCEPT | 80 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 80 | 0.0% | 100.0% |  |
| BUILD_MAP | 80 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NONE | 80 | 0.0% | 100.0% |  |
| STORE_ATTR | 80 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 60 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,208,003,680 | 5.1% | 5.1% |
| STORE_FAST LOAD_FAST | 1,056,003,680 | 4.4% | 9.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 696,001,120 | 2.9% | 12.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 680,001,780 | 2.9% | 15.3% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 648,000,680 | 2.7% | 18.1% |
| STORE_FAST STORE_FAST | 608,000,000 | 2.6% | 20.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 544,002,160 | 2.3% | 22.9% |
| LOAD_FAST TO_BOOL_BOOL | 536,000,200 | 2.3% | 25.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 527,999,940 | 2.2% | 27.4% |
| LOAD_FAST CALL_BUILTIN_O | 520,000,720 | 2.2% | 29.6% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 456,000,880 | 1.9% | 31.5% |
| LOAD_GLOBAL_BUILTIN CALL_BUILTIN_FAST | 456,000,880 | 1.9% | 33.4% |
| LOAD_FAST LOAD_CONST | 432,001,360 | 1.8% | 35.3% |
| LOAD_CONST LOAD_CONST | 408,000,960 | 1.7% | 37.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 384,002,440 | 1.6% | 38.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 376,002,600 | 1.6% | 40.2% |
| POP_TOP LOAD_FAST | 360,000,880 | 1.5% | 41.7% |
| BUILD_TUPLE RETURN_VALUE | 360,000,160 | 1.5% | 43.2% |
| RETURN_VALUE RETURN_VALUE | 312,000,080 | 1.3% | 44.5% |
| RETURN_VALUE UNPACK_SEQUENCE_TUPLE | 311,999,800 | 1.3% | 45.8% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST | 303,999,880 | 1.3% | 47.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 288,001,520 | 1.2% | 48.3% |
| LOAD_ATTR IS_OP | 288,000,160 | 1.2% | 49.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 264,002,580 | 1.1% | 50.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 264,001,280 | 1.1% | 51.8% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 264,001,280 | 1.1% | 52.9% |
| LOAD_CONST STORE_FAST | 264,000,720 | 1.1% | 54.0% |
| POP_JUMP_IF_TRUE LOAD_FAST | 264,000,160 | 1.1% | 55.1% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 263,998,220 | 1.1% | 56.2% |
| LOAD_FAST PUSH_NULL | 256,001,040 | 1.1% | 57.3% |
| PUSH_NULL LOAD_FAST | 256,000,640 | 1.1% | 58.4% |
| CALL_BUILTIN_O POP_TOP | 256,000,380 | 1.1% | 59.5% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 240,000,400 | 1.0% | 60.5% |
| IS_OP POP_JUMP_IF_FALSE | 240,000,000 | 1.0% | 61.5% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 232,000,440 | 1.0% | 62.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 224,000,720 | 0.9% | 63.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 216,000,280 | 0.9% | 64.3% |
| LOAD_CONST BUILD_TUPLE | 216,000,000 | 0.9% | 65.2% |
| CALL_BUILTIN_O LOAD_CONST | 215,999,920 | 0.9% | 66.1% |
| RESUME_CHECK LOAD_FAST | 192,001,340 | 0.8% | 66.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 192,001,240 | 0.8% | 67.7% |
| LOAD_FAST CALL_TYPE_1 | 192,000,760 | 0.8% | 68.6% |
| CALL_TYPE_1 STORE_FAST | 192,000,760 | 0.8% | 69.4% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 192,000,760 | 0.8% | 70.2% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 192,000,720 | 0.8% | 71.0% |
| CALL_BUILTIN_FAST STORE_FAST | 168,001,260 | 0.7% | 71.7% |
| LOAD_CONST CALL_BUILTIN_FAST | 168,000,720 | 0.7% | 72.4% |
| CACHE RESUME_CHECK | 168,000,000 | 0.7% | 73.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 120,000,800 | 0.5% | 73.6% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 120,000,160 | 0.5% | 74.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 112,001,440 | 0.5% | 74.6% |
| LOAD_FAST LOAD_FAST_LOAD_FAST | 112,000,320 | 0.5% | 75.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 112,000,280 | 0.5% | 75.5% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 103,999,960 | 0.4% | 76.0% |
| LOAD_FAST LOAD_ATTR | 96,001,560 | 0.4% | 76.4% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 96,000,720 | 0.4% | 76.8% |
| LOAD_CONST LOAD_FAST_LOAD_FAST | 96,000,640 | 0.4% | 77.2% |
| POP_JUMP_IF_FALSE LOAD_CONST | 96,000,640 | 0.4% | 77.6% |
| CALL_BUILTIN_O STORE_FAST | 96,000,620 | 0.4% | 78.0% |
| STORE_FAST LOAD_CONST | 96,000,320 | 0.4% | 78.4% |
| LOAD_ATTR STORE_FAST | 96,000,280 | 0.4% | 78.8% |
| LOAD_FAST_LOAD_FAST DELETE_SUBSCR | 96,000,240 | 0.4% | 79.2% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 96,000,180 | 0.4% | 79.6% |
| BUILD_LIST STORE_FAST | 96,000,160 | 0.4% | 80.0% |
| LOAD_FAST GET_ITER | 96,000,160 | 0.4% | 80.4% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 96,000,160 | 0.4% | 80.8% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 96,000,160 | 0.4% | 81.2% |
| STORE_FAST BUILD_LIST | 96,000,160 | 0.4% | 81.6% |
| BINARY_OP_ADD_INT STORE_FAST | 96,000,140 | 0.4% | 82.0% |
| LOAD_CONST BINARY_OP_ADD_INT | 96,000,120 | 0.4% | 82.4% |
| TO_BOOL_BOOL EXTENDED_ARG | 96,000,120 | 0.4% | 82.8% |
| POP_JUMP_IF_FALSE POP_TOP | 96,000,080 | 0.4% | 83.2% |
| CALL_METHOD_DESCRIPTOR_O BINARY_OP | 96,000,080 | 0.4% | 83.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 96,000,080 | 0.4% | 84.1% |
| STORE_SUBSCR_DICT LOAD_CONST | 96,000,080 | 0.4% | 84.5% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 96,000,080 | 0.4% | 84.9% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_DICT | 96,000,040 | 0.4% | 85.3% |
| CONVERT_VALUE FORMAT_SIMPLE | 96,000,000 | 0.4% | 85.7% |
| LOAD_CONST LOAD_ATTR_METHOD_NO_DICT | 96,000,000 | 0.4% | 86.1% |
| LOAD_FAST CONVERT_VALUE | 96,000,000 | 0.4% | 86.5% |
| LOAD_FAST COPY | 96,000,000 | 0.4% | 86.9% |
| LOAD_FAST TO_BOOL_NONE | 96,000,000 | 0.4% | 87.3% |
| RETURN_CONST INTERPRETER_EXIT | 96,000,000 | 0.4% | 87.7% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 95,999,960 | 0.4% | 88.1% |
| STORE_ATTR_SLOT RETURN_CONST | 95,999,960 | 0.4% | 88.5% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 95,999,920 | 0.4% | 88.9% |
| BINARY_SUBSCR_TUPLE_INT CALL | 95,999,920 | 0.4% | 89.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 95,999,920 | 0.4% | 89.7% |
| COPY TO_BOOL_BOOL | 95,999,840 | 0.4% | 90.1% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 95,999,840 | 0.4% | 90.5% |
| FOR_ITER_LIST STORE_FAST | 72,290,800 | 0.3% | 90.8% |
| LOAD_FAST TO_BOOL | 72,000,760 | 0.3% | 91.1% |
| TO_BOOL POP_JUMP_IF_TRUE | 72,000,260 | 0.3% | 91.4% |
| DELETE_SUBSCR LOAD_FAST | 72,000,160 | 0.3% | 91.7% |
| RETURN_VALUE INTERPRETER_EXIT | 72,000,160 | 0.3% | 92.0% |
| POP_JUMP_IF_TRUE LOAD_CONST | 72,000,160 | 0.3% | 92.3% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 71,999,760 | 0.3% | 92.6% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 71,999,560 | 0.3% | 93.0% |
| GET_ITER FOR_ITER_LIST | 69,963,620 | 0.3% | 93.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 56,000,200 | 0.2% | 93.5% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 168,000,000 | 100.0% |
| RESUME | 160 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 50.0% |
| BINARY_SUBSCR_TUPLE_INT | 80 | 50.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60 | 75.0% |
| LOAD_GLOBAL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 80 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 96,000,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,000,160 | 75.0% |
| LOAD_CONST | 24,000,000 | 25.0% |
| RETURN_CONST | 80 | 0.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 96,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_STRING | 48,000,000 | 50.0% |
| LOAD_CONST | 48,000,000 | 50.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,000,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 69,963,620 | 72.9% |
| FOR_ITER_TUPLE | 26,036,420 | 27.1% |
| FOR_ITER | 120 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 96,000,000 | 57.1% |
| RETURN_VALUE | 72,000,160 | 42.9% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 23,999,960 | 100.0% |
| STORE_FAST | 480 | 0.0% |
| POP_TOP | 160 | 0.0% |
| RESUME | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,000,000 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 400 | 0.0% |
| LOAD_DEREF | 160 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 80 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 256,000,380 | 69.6% |
| POP_JUMP_IF_FALSE | 96,000,080 | 26.1% |
| RETURN_CONST | 8,000,240 | 2.2% |
| CALL_METHOD_DESCRIPTOR_O | 8,000,100 | 2.2% |
| CALL | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360,000,880 | 97.8% |
| RETURN_CONST | 8,000,080 | 2.2% |
| NOP | 160 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 50.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 256,001,040 | 100.0% |
| LOAD_DEREF | 160 | 0.0% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 256,000,640 | 100.0% |
| CALL | 640 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 360,000,160 | 51.1% |
| RETURN_VALUE | 312,000,080 | 44.3% |
| COMPARE_OP_INT | 23,999,960 | 3.4% |
| LOAD_FAST | 8,000,240 | 1.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 312,000,080 | 44.3% |
| UNPACK_SEQUENCE_TUPLE | 311,999,800 | 44.3% |
| INTERPRETER_EXIT | 72,000,160 | 10.2% |
| STORE_FAST | 8,000,080 | 1.1% |
| UNPACK_SEQUENCE | 280 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 100 | 50.0% |
| LOAD_CONST | 80 | 40.0% |
| LOAD_FAST | 20 | 10.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,000,760 | 100.0% |
| TO_BOOL | 18,340 | 0.0% |
| CALL | 200 | 0.0% |
| CALL_BUILTIN_FAST | 200 | 0.0% |
| COPY | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 72,000,260 | 100.0% |
| TO_BOOL | 18,340 | 0.0% |
| TO_BOOL_BOOL | 640 | 0.0% |
| POP_JUMP_IF_FALSE | 460 | 0.0% |
| TO_BOOL_NONE | 80 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 96,000,080 | 100.0% |
| BINARY_OP | 24,280 | 0.0% |
| LOAD_CONST | 280 | 0.0% |
| LOAD_FAST | 280 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 96,000,180 | 100.0% |
| BINARY_OP | 24,280 | 0.0% |
| STORE_FAST | 220 | 0.0% |
| BINARY_OP_ADD_INT | 160 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 100 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,000,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,000,160 | 100.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 48,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 47,999,920 | 100.0% |
| CALL | 80 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 216,000,000 | 60.0% |
| LOAD_FAST_LOAD_FAST | 96,000,160 | 26.7% |
| CALL | 48,000,000 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 360,000,160 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 95,999,920 | 100.0% |
| CALL | 24,380 | 0.0% |
| LOAD_FAST | 1,200 | 0.0% |
| PUSH_NULL | 640 | 0.0% |
| LOAD_FAST_LOAD_FAST | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 48,000,000 | 50.0% |
| LOAD_GLOBAL_MODULE | 47,999,920 | 50.0% |
| CALL | 24,380 | 0.0% |
| STORE_FAST | 500 | 0.0% |
| POP_TOP | 480 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 160 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,000,000 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 200 | 62.5% |
| LOAD_ATTR | 40 | 12.5% |
| LOAD_FAST | 40 | 12.5% |
| LOAD_ATTR_SLOT | 40 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 160 | 50.0% |
| POP_JUMP_IF_FALSE | 120 | 37.5% |
| RETURN_VALUE | 40 | 12.5% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 192,000,760 | 66.7% |
| LOAD_FAST_LOAD_FAST | 96,000,720 | 33.3% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 288,001,520 | 100.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 96,000,000 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,000,000 | 100.0% |
| BINARY_OP_ADD_INT | 60 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 95,999,840 | 100.0% |
| TO_BOOL | 160 | 0.0% |
| STORE_FAST_STORE_FAST | 80 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 75.0% |
| RESUME | 40 | 25.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 263,998,220 | 100.0% |
| JUMP_BACKWARD | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 71,999,760 | 27.3% |
| LOAD_FAST_LOAD_FAST | 71,999,560 | 27.3% |
| LOAD_ATTR | 47,999,600 | 18.2% |
| FOR_ITER_LIST | 42,036,300 | 15.9% |
| FOR_ITER_TUPLE | 21,963,500 | 8.3% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 96,000,120 | 80.0% |
| IS_OP | 24,000,000 | 20.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120,000,160 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 120 | 75.0% |
| JUMP_BACKWARD | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 25.0% |
| UNPACK_SEQUENCE | 40 | 25.0% |
| FOR_ITER_LIST | 40 | 25.0% |
| FOR_ITER_TUPLE | 40 | 25.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 288,000,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 240,000,000 | 83.3% |
| POP_JUMP_IF_TRUE | 24,000,160 | 8.3% |
| EXTENDED_ARG | 24,000,000 | 8.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,700 | 95.5% |
| POP_EXCEPT | 80 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 640 | 36.0% |
| FOR_ITER_LIST | 600 | 33.7% |
| LOAD_FAST | 400 | 22.5% |
| ENTER_EXECUTOR | 100 | 5.6% |
| FOR_ITER | 40 | 2.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 48,000,160 | 100.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 24,000,120 | 50.0% |
| LOAD_FAST | 24,000,000 | 50.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 240,000,400 | 62.5% |
| LOAD_FAST | 96,001,560 | 25.0% |
| ENTER_EXECUTOR | 47,999,600 | 12.5% |
| LOAD_ATTR | 96,120 | 0.0% |
| LOAD_GLOBAL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 288,000,160 | 75.0% |
| STORE_FAST | 96,000,280 | 25.0% |
| LOAD_ATTR | 96,120 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 260 | 0.0% |
| LOAD_FAST | 240 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 432,001,360 | 27.7% |
| LOAD_CONST | 408,000,960 | 26.2% |
| CALL_BUILTIN_O | 215,999,920 | 13.8% |
| POP_JUMP_IF_FALSE | 96,000,640 | 6.2% |
| STORE_FAST | 96,000,320 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 408,000,960 | 26.2% |
| STORE_FAST | 264,000,720 | 16.9% |
| BUILD_TUPLE | 216,000,000 | 13.8% |
| CALL_BUILTIN_FAST | 168,000,720 | 10.8% |
| LOAD_FAST_LOAD_FAST | 96,000,640 | 6.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 160 | 50.0% |
| STORE_FAST | 160 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 50.0% |
| STORE_FAST | 160 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,208,003,680 | 26.5% |
| STORE_FAST | 1,056,003,680 | 23.2% |
| POP_JUMP_IF_FALSE | 544,002,160 | 11.9% |
| POP_TOP | 360,000,880 | 7.9% |
| POP_JUMP_IF_TRUE | 264,000,160 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 696,001,120 | 15.3% |
| TO_BOOL_BOOL | 536,000,200 | 11.8% |
| CALL_BUILTIN_O | 520,000,720 | 11.4% |
| LOAD_CONST | 432,001,360 | 9.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 376,002,600 | 8.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 264,002,580 | 23.6% |
| LOAD_FAST_LOAD_FAST | 264,001,280 | 23.6% |
| LOAD_FAST | 112,000,320 | 10.0% |
| LOAD_CONST | 96,000,640 | 8.6% |
| BINARY_OP | 96,000,180 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 264,001,280 | 23.6% |
| CALL_PY_EXACT_ARGS | 264,001,280 | 23.6% |
| LOAD_FAST | 112,001,440 | 10.0% |
| CONTAINS_OP | 96,000,720 | 8.6% |
| DELETE_SUBSCR | 96,000,240 | 8.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800 | 31.2% |
| POP_JUMP_IF_FALSE | 680 | 26.6% |
| STORE_FAST | 160 | 6.2% |
| RESUME | 160 | 6.2% |
| RESUME_CHECK | 160 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,020 | 39.8% |
| LOAD_FAST | 720 | 28.1% |
| LOAD_GLOBAL_MODULE | 260 | 10.2% |
| LOAD_ATTR | 240 | 9.4% |
| CALL | 220 | 8.6% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 680,001,780 | 45.9% |
| CONTAINS_OP | 288,001,520 | 19.5% |
| IS_OP | 240,000,000 | 16.2% |
| EXTENDED_ARG | 120,000,160 | 8.1% |
| TO_BOOL_NONE | 96,000,080 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 648,000,680 | 43.8% |
| LOAD_FAST | 544,002,160 | 36.8% |
| LOAD_CONST | 96,000,640 | 6.5% |
| LOAD_FAST_LOAD_FAST | 96,000,160 | 6.5% |
| POP_TOP | 96,000,080 | 6.5% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 527,999,940 | 81.5% |
| TO_BOOL | 72,000,260 | 11.1% |
| IS_OP | 24,000,160 | 3.7% |
| TO_BOOL_LIST | 24,000,120 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 264,000,160 | 40.7% |
| ENTER_EXECUTOR | 263,998,220 | 40.7% |
| LOAD_CONST | 72,000,160 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 48,000,040 | 7.4% |
| JUMP_BACKWARD | 1,700 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 95,999,960 | 92.3% |
| POP_TOP | 8,000,080 | 7.7% |
| DELETE_SUBSCR | 80 | 0.0% |
| POP_JUMP_IF_TRUE | 80 | 0.0% |
| STORE_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 96,000,000 | 92.3% |
| POP_TOP | 8,000,240 | 7.7% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 40 | 50.0% |
| STORE_ATTR_SLOT | 40 | 50.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 608,000,000 | 28.6% |
| UNPACK_SEQUENCE_TUPLE | 303,999,880 | 14.3% |
| LOAD_CONST | 264,000,720 | 12.4% |
| CALL_TYPE_1 | 192,000,760 | 9.0% |
| CALL_BUILTIN_FAST | 168,001,260 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,056,003,680 | 49.6% |
| STORE_FAST | 608,000,000 | 28.6% |
| LOAD_GLOBAL_BUILTIN | 224,000,720 | 10.5% |
| LOAD_CONST | 96,000,320 | 4.5% |
| BUILD_LIST | 96,000,160 | 4.5% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 24,000,280 | 75.0% |
| UNPACK_SEQUENCE_TUPLE | 8,000,060 | 25.0% |
| COPY | 80 | 0.0% |
| UNPACK_SEQUENCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,000,320 | 75.0% |
| STORE_FAST | 8,000,080 | 25.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 280 | 77.8% |
| FOR_ITER | 40 | 11.1% |
| FOR_ITER_LIST | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 140 | 38.9% |
| STORE_FAST | 120 | 33.3% |
| STORE_FAST_STORE_FAST | 60 | 16.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 11.1% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 160 | 47.1% |
| CALL | 140 | 41.2% |
| COPY_FREE_VARS | 40 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 160 | 47.1% |
| LOAD_FAST | 100 | 29.4% |
| NOP | 40 | 11.8% |
| LOAD_FAST_LOAD_FAST | 40 | 11.8% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 96,000,120 | 100.0% |
| BINARY_OP | 160 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 96,000,140 | 100.0% |
| COPY | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 66.7% |
| BINARY_OP | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,000,120 | 100.0% |
| BINARY_OP | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,000,180 | 50.0% |
| LOAD_FAST | 8,000,060 | 50.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 95,999,840 | 100.0% |
| BINARY_SUBSCR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 95,999,920 | 100.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 456,000,880 | 73.1% |
| LOAD_CONST | 168,000,720 | 26.9% |
| LOAD_FAST | 440 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 456,000,880 | 73.1% |
| STORE_FAST | 168,001,260 | 26.9% |
| TO_BOOL | 200 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 520,000,720 | 91.5% |
| BUILD_STRING | 47,999,920 | 8.5% |
| CALL | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 256,000,380 | 45.1% |
| LOAD_CONST | 215,999,920 | 38.0% |
| STORE_FAST | 96,000,620 | 16.9% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 55,999,960 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 47,999,960 | 85.7% |
| LOAD_FAST | 8,000,060 | 14.3% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 31,999,960 | 100.0% |
| CALL | 80 | 0.0% |
| LOAD_ATTR_METHOD_LAZY_DICT | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 23,999,920 | 75.0% |
| LOAD_FAST | 8,000,060 | 25.0% |
| RETURN_VALUE | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 103,999,960 | 100.0% |
| CALL | 140 | 0.0% |
| LOAD_CONST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 96,000,080 | 92.3% |
| POP_TOP | 8,000,100 | 7.7% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 264,001,280 | 68.7% |
| LOAD_FAST | 120,000,800 | 31.3% |
| CALL | 280 | 0.0% |
| LOAD_CONST | 40 | 0.0% |
| BINARY_OP_ADD_INT | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 384,002,440 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 192,000,760 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 192,000,760 | 100.0% |
| LOAD_ATTR | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 48,000,040 | 60.0% |
| LOAD_ATTR_SLOT | 23,999,920 | 30.0% |
| LOAD_FAST | 8,000,040 | 10.0% |
| COMPARE_OP | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 56,000,200 | 70.0% |
| RETURN_VALUE | 23,999,960 | 30.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 69,963,620 | 62.1% |
| ENTER_EXECUTOR | 42,036,300 | 37.3% |
| FOR_ITER_TUPLE | 581,820 | 0.5% |
| JUMP_BACKWARD | 600 | 0.0% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 72,290,800 | 64.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 24,000,240 | 21.3% |
| LOAD_FAST_LOAD_FAST | 15,709,520 | 14.0% |
| FOR_ITER_TUPLE | 581,780 | 0.5% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 26,036,420 | 53.6% |
| ENTER_EXECUTOR | 21,963,500 | 45.2% |
| FOR_ITER_LIST | 581,780 | 1.2% |
| JUMP_BACKWARD | 640 | 0.0% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 39,709,480 | 81.7% |
| LOAD_FAST_LOAD_FAST | 8,291,080 | 17.1% |
| FOR_ITER_LIST | 581,820 | 1.2% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 232,000,440 | 100.0% |
| LOAD_ATTR | 200 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 216,000,280 | 93.1% |
| LOAD_FAST | 16,000,180 | 6.9% |
| TO_BOOL | 100 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| BINARY_OP_ADD_INT | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,000,080 | 100.0% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,999,980 | 100.0% |
| LOAD_CONST | 120 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 96,000,000 | 75.0% |
| LOAD_FAST | 23,999,920 | 18.7% |
| ENTER_EXECUTOR | 7,999,520 | 6.2% |
| LOAD_FAST_LOAD_FAST | 520 | 0.0% |
| LOAD_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,000,080 | 75.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 31,999,960 | 25.0% |
| CALL | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 376,002,600 | 100.0% |
| LOAD_ATTR | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 264,002,580 | 70.2% |
| LOAD_FAST | 112,000,280 | 29.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 160 | 66.7% |
| LOAD_ATTR | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 50.0% |
| STORE_FAST | 120 | 50.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| LOAD_ATTR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 40 | 66.7% |
| LOAD_ATTR | 20 | 33.3% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,999,840 | 100.0% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,999,960 | 50.0% |
| COMPARE_OP_INT | 23,999,920 | 50.0% |
| COMPARE_OP | 40 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 696,001,120 | 36.6% |
| POP_JUMP_IF_FALSE | 648,000,680 | 34.0% |
| STORE_FAST | 224,000,720 | 11.8% |
| RESUME_CHECK | 192,001,240 | 10.1% |
| ENTER_EXECUTOR | 71,999,760 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,208,003,680 | 63.4% |
| CALL_BUILTIN_FAST | 456,000,880 | 23.9% |
| LOAD_ATTR | 240,000,400 | 12.6% |
| CALL | 200 | 0.0% |
| CHECK_EXC_MATCH | 60 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 192,000,720 | 61.5% |
| RESUME_CHECK | 48,000,040 | 15.4% |
| CALL | 47,999,920 | 15.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 23,999,920 | 7.7% |
| LOAD_GLOBAL | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 192,000,760 | 61.5% |
| LOAD_FAST | 95,999,920 | 30.8% |
| LOAD_CONST | 23,999,960 | 7.7% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 384,002,440 | 69.6% |
| CACHE | 168,000,000 | 30.4% |
| CALL | 140 | 0.0% |
| COPY_FREE_VARS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 192,001,340 | 34.8% |
| LOAD_GLOBAL_BUILTIN | 192,001,240 | 34.8% |
| LOAD_FAST_LOAD_FAST | 95,999,960 | 17.4% |
| LOAD_GLOBAL_MODULE | 48,000,040 | 8.7% |
| NOP | 23,999,960 | 4.3% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 95,999,920 | 100.0% |
| STORE_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 95,999,960 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 96,000,040 | 100.0% |
| STORE_SUBSCR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 96,000,080 | 100.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 536,000,200 | 41.1% |
| CALL_BUILTIN_FAST | 456,000,880 | 35.0% |
| LOAD_ATTR_INSTANCE_VALUE | 216,000,280 | 16.6% |
| COPY | 95,999,840 | 7.4% |
| TO_BOOL | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 680,001,780 | 52.1% |
| POP_JUMP_IF_TRUE | 527,999,940 | 40.5% |
| EXTENDED_ARG | 96,000,120 | 7.4% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,000,080 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 24,000,120 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 96,000,000 | 100.0% |
| TO_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 96,000,080 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 311,999,800 | 100.0% |
| UNPACK_SEQUENCE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 303,999,880 | 97.4% |
| STORE_FAST_STORE_FAST | 8,000,060 | 2.6% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 24,000,240 | 100.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 24,000,280 | 100.0% |


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
|     deferred | 96,000,560 | 46.1% |
|          hit | 112,000,800 | 53.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 320 | 1.3% |
| Failure | 24,240 | 98.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 24,220 | 99.9% |
| multiply different types | 20 | 0.1% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 80 | 0.0% |
|          hit | 95,999,920 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 96,001,940 | 4.7% |
|          hit | 1,960,006,860 | 95.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,220 | 4.8% |
| Failure | 24,380 | 95.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| no dict | 24,200 | 99.3% |
| cfunc noargs | 120 | 0.5% |
| other | 40 | 0.2% |
| class no vectorcall | 20 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 160 | 0.0% |
|          hit | 80,000,160 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 737,869,762,948,380,901,120 | 457,835,218,078,711.5% |
|          hit | 99,492,000 | 61.7% |
|         miss | 61,672,760 | 38.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,163,680 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 384,001,360 | 32.7% |
|          hit | 792,004,080 | 67.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 880 | 0.9% |
| Failure | 96,100 | 99.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 71,860 | 74.8% |
| method | 24,240 | 25.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,280 | 0.0% |
|          hit | 2,216,006,160 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,280 | 100.0% |
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
|     deferred | 40 | 0.0% |
|          hit | 95,999,960 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 0.0% |
|          hit | 96,000,140 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 72,000,760 | 4.8% |
|          hit | 1,424,002,040 | 95.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 760 | 4.0% |
| Failure | 18,340 | 96.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 12,100 | 66.0% |
| dict | 6,240 | 34.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 180 | 0.0% |
|          hit | 336,000,220 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 13,040,044,120 | 54.9% |
| Not specialized | 2,776,179,660 | 11.7% |
| Specialized hits | 7,859,515,040 | 33.1% |
| Specialized misses | 61,672,760 | 0.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER | 737,869,762,948,380,901,120 | 100.0% |
| LOAD_ATTR | 384,001,360 | 0.0% |
| CALL | 96,001,940 | 0.0% |
| BINARY_OP | 96,000,560 | 0.0% |
| TO_BOOL | 72,000,760 | 0.0% |
| LOAD_GLOBAL | 1,280 | 0.0% |
| UNPACK_SEQUENCE | 180 | 0.0% |
| COMPARE_OP | 160 | 0.0% |
| STORE_SUBSCR | 100 | 0.0% |
| BINARY_SUBSCR | 80 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER_TUPLE | 30,836,460 | 50.0% |
| FOR_ITER_LIST | 30,836,300 | 50.0% |
| CACHE | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |
| DELETE_SUBSCR | 0 | 0.0% |
| FORMAT_SIMPLE | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_EXCEPT | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 168,000,160 | 30.4% |
| Calls to Python functions inlined | 384,002,880 | 69.6% |
| Calls via PyEval_EvalFrame (total) | 168,000,160 | 30.4% |
| Calls via PyEval_EvalFrame (vector) | 168,000,160 | 30.4% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 168,000,160 | 30.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 24,000,000 | 4.3% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 48,000,000 | 8.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 80 | 0.0% |
| Frames pushed | 640,000,200 | 115.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 728,000,800 | 38.7% |
| Frees to freelist | 728,000,680 |  |
| Allocations | 1,152,002,260 | 61.3% |
| Allocations to 512 bytes | 1,152,001,920 | 61.3% |
| Allocations to 4 kbytes | 100 | 0.0% |
| Allocations over 4 kbytes | 240 | 0.0% |
| Frees | 1,248,002,272 |  |
| New values | 0 |  |
| Interpreter increfs | 8,834,809,900 | 73.1% |
| Interpreter decrefs | 10,415,722,480 | 74.8% |
| Increfs | 3,245,204,438 | 26.9% |
| Decrefs | 3,504,294,448 | 25.2% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 120,025,943 |  |
| Method cache misses | 297 |  |
| Method cache collisions | 395 |  |
| Method cache dunder hits | 1,320,072,476 |  |
| Method cache dunder misses | 184 |  |


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
| Trace too long | 20 | 20.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 263,998,320 |  |
| Uops executed | 11,879,895,720 | 45.00 |

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
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 100 | 100.0% |


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
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 100 | 100.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 63,999,800 | 24.2% |
| <= 4 | 0 | 0.0% |
| <= 8 | 71,999,560 | 27.3% |
| <= 16 | 80 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 127,998,880 | 48.5% |


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
| LOAD_ATTR | 80 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 40 |


</details>

---
Stats gathered on: 2023-11-02
