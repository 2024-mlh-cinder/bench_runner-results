
# Pystats results

- benchmark: pprint
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 4,632,015,520 | 18.9% | 18.9% |  |
| STORE_FAST | 2,128,006,720 | 8.7% | 27.6% |  |
| LOAD_GLOBAL_BUILTIN | 2,072,004,180 | 8.5% | 36.1% |  |
| POP_JUMP_IF_FALSE | 1,600,003,760 | 6.5% | 42.7% |  |
| LOAD_CONST | 1,560,004,400 | 6.4% | 49.0% |  |
| TO_BOOL_BOOL | 1,424,001,200 | 5.8% | 54.9% |  |
| LOAD_FAST_LOAD_FAST | 1,136,005,680 | 4.6% | 59.5% |  |
| CALL_BUILTIN_FAST | 744,001,700 | 3.0% | 62.5% |  |
| RETURN_VALUE | 704,000,560 | 2.9% | 65.4% |  |
| POP_JUMP_IF_TRUE | 648,000,480 | 2.6% | 68.1% |  |
| CALL_BUILTIN_O | 568,000,920 | 2.3% | 70.4% |  |
| RESUME_CHECK | 560,002,220 | 2.3% | 72.7% |  |
| CALL_PY_EXACT_ARGS | 392,001,960 | 1.6% | 74.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 392,001,900 | 1.6% | 75.9% |  |
| LOAD_ATTR | 384,098,340 | 1.6% | 77.5% |  |
| POP_TOP | 368,001,280 | 1.5% | 79.0% |  |
| BUILD_TUPLE | 360,000,160 | 1.5% | 80.4% |  |
| LOAD_GLOBAL_MODULE | 312,000,940 | 1.3% | 81.7% |  |
| UNPACK_SEQUENCE_TUPLE | 311,999,940 | 1.3% | 83.0% |  |
| CONTAINS_OP | 288,001,520 | 1.2% | 84.2% |  |
| IS_OP | 288,000,160 | 1.2% | 85.3% |  |
| ENTER_EXECUTOR | 263,998,320 | 1.1% | 86.4% |  |
| PUSH_NULL | 256,001,360 | 1.0% | 87.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 232,000,680 | 0.9% | 88.4% |  |
| CALL_TYPE_1 | 192,000,820 | 0.8% | 89.2% |  |
| INTERPRETER_EXIT | 168,000,160 | 0.7% | 89.9% |  |
| FOR_ITER_LIST | 136,860,620 | 0.6% | 90.4% | 33.4% |
| LOAD_ATTR_METHOD_NO_DICT | 128,000,160 | 0.5% | 91.0% |  |
| EXTENDED_ARG | 120,000,160 | 0.5% | 91.5% |  |
| RETURN_CONST | 104,000,240 | 0.4% | 91.9% |  |
| CALL_METHOD_DESCRIPTOR_O | 104,000,180 | 0.4% | 92.3% |  |
| FOR_ITER_TUPLE | 96,863,760 | 0.4% | 92.7% | 47.2% |
| CALL | 96,027,540 | 0.4% | 93.1% |  |
| BINARY_OP | 96,025,120 | 0.4% | 93.5% |  |
| BINARY_OP_ADD_INT | 96,000,320 | 0.4% | 93.9% |  |
| DELETE_SUBSCR | 96,000,240 | 0.4% | 94.3% |  |
| GET_ITER | 96,000,160 | 0.4% | 94.7% |  |
| BUILD_LIST | 96,000,160 | 0.4% | 95.1% |  |
| STORE_SUBSCR_DICT | 96,000,140 | 0.4% | 95.5% |  |
| COPY | 96,000,080 | 0.4% | 95.8% |  |
| TO_BOOL_NONE | 96,000,080 | 0.4% | 96.2% |  |
| FORMAT_SIMPLE | 96,000,000 | 0.4% | 96.6% |  |
| CONVERT_VALUE | 96,000,000 | 0.4% | 97.0% |  |
| STORE_ATTR_SLOT | 95,999,960 | 0.4% | 97.4% |  |
| BINARY_SUBSCR_TUPLE_INT | 95,999,920 | 0.4% | 97.8% |  |
| COMPARE_OP_INT | 80,000,160 | 0.3% | 98.1% |  |
| TO_BOOL | 72,019,860 | 0.3% | 98.4% |  |
| CALL_LEN | 56,000,020 | 0.2% | 98.7% |  |
| JUMP_FORWARD | 48,000,240 | 0.2% | 98.9% |  |
| BUILD_STRING | 48,000,000 | 0.2% | 99.1% |  |
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
| POP_JUMP_IF_NONE | 80 | 0.0% | 100.0% |  |
| STORE_ATTR | 80 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 80 | 0.0% | 100.0% |  |
| POP_EXCEPT | 80 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 80 | 0.0% | 100.0% |  |
| BUILD_MAP | 80 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 60 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,208,003,680 | 4.9% | 4.9% |
| STORE_FAST LOAD_FAST | 1,056,003,680 | 4.3% | 9.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 800,001,140 | 3.3% | 12.5% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 744,000,720 | 3.0% | 15.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 720,000,440 | 2.9% | 18.5% |
| STORE_FAST STORE_FAST | 608,000,000 | 2.5% | 21.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 592,001,760 | 2.4% | 23.4% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 576,000,240 | 2.4% | 25.8% |
| LOAD_GLOBAL_BUILTIN CALL_BUILTIN_FAST | 576,000,240 | 2.4% | 28.1% |
| LOAD_FAST TO_BOOL_BOOL | 536,000,200 | 2.2% | 30.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 527,999,940 | 2.2% | 32.5% |
| LOAD_FAST CALL_BUILTIN_O | 520,000,720 | 2.1% | 34.6% |
| LOAD_FAST LOAD_CONST | 432,001,360 | 1.8% | 36.4% |
| LOAD_CONST LOAD_CONST | 408,000,960 | 1.7% | 38.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 392,001,960 | 1.6% | 39.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 392,001,640 | 1.6% | 41.2% |
| POP_TOP LOAD_FAST | 360,000,880 | 1.5% | 42.7% |
| BUILD_TUPLE RETURN_VALUE | 360,000,160 | 1.5% | 44.2% |
| RETURN_VALUE RETURN_VALUE | 312,000,080 | 1.3% | 45.5% |
| RETURN_VALUE UNPACK_SEQUENCE_TUPLE | 311,999,800 | 1.3% | 46.7% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST | 303,999,880 | 1.2% | 48.0% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 288,001,520 | 1.2% | 49.2% |
| LOAD_ATTR IS_OP | 288,000,160 | 1.2% | 50.3% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 288,000,000 | 1.2% | 51.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 280,001,620 | 1.1% | 52.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 264,001,280 | 1.1% | 53.7% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 264,001,280 | 1.1% | 54.8% |
| LOAD_CONST STORE_FAST | 264,000,720 | 1.1% | 55.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 264,000,160 | 1.1% | 57.0% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 263,998,220 | 1.1% | 58.1% |
| LOAD_FAST PUSH_NULL | 256,001,040 | 1.0% | 59.1% |
| PUSH_NULL LOAD_FAST | 256,000,640 | 1.0% | 60.2% |
| CALL_BUILTIN_O POP_TOP | 256,000,380 | 1.0% | 61.2% |
| IS_OP POP_JUMP_IF_FALSE | 240,000,000 | 1.0% | 62.2% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 232,000,440 | 0.9% | 63.1% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 224,000,720 | 0.9% | 64.0% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 216,000,280 | 0.9% | 64.9% |
| LOAD_CONST BUILD_TUPLE | 216,000,000 | 0.9% | 65.8% |
| CALL_BUILTIN_O LOAD_CONST | 215,999,920 | 0.9% | 66.7% |
| RESUME_CHECK LOAD_FAST | 200,000,860 | 0.8% | 67.5% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 192,001,240 | 0.8% | 68.3% |
| LOAD_FAST CALL_TYPE_1 | 192,000,760 | 0.8% | 69.1% |
| CALL_TYPE_1 STORE_FAST | 192,000,760 | 0.8% | 69.9% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 192,000,760 | 0.8% | 70.7% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 192,000,720 | 0.8% | 71.4% |
| CALL_BUILTIN_FAST STORE_FAST | 168,001,260 | 0.7% | 72.1% |
| LOAD_CONST CALL_BUILTIN_FAST | 168,000,720 | 0.7% | 72.8% |
| CACHE RESUME_CHECK | 168,000,000 | 0.7% | 73.5% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 128,000,320 | 0.5% | 74.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 120,000,960 | 0.5% | 74.5% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 120,000,160 | 0.5% | 75.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 119,999,360 | 0.5% | 75.5% |
| LOAD_FAST LOAD_FAST_LOAD_FAST | 112,000,320 | 0.5% | 76.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 112,000,280 | 0.5% | 76.4% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 103,999,960 | 0.4% | 76.8% |
| LOAD_FAST LOAD_ATTR | 96,001,560 | 0.4% | 77.2% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 96,000,720 | 0.4% | 77.6% |
| LOAD_CONST LOAD_FAST_LOAD_FAST | 96,000,640 | 0.4% | 78.0% |
| POP_JUMP_IF_FALSE LOAD_CONST | 96,000,640 | 0.4% | 78.4% |
| CALL_BUILTIN_O STORE_FAST | 96,000,620 | 0.4% | 78.8% |
| STORE_FAST LOAD_CONST | 96,000,320 | 0.4% | 79.2% |
| LOAD_ATTR STORE_FAST | 96,000,280 | 0.4% | 79.6% |
| LOAD_FAST_LOAD_FAST DELETE_SUBSCR | 96,000,240 | 0.4% | 80.0% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 96,000,180 | 0.4% | 80.4% |
| BUILD_LIST STORE_FAST | 96,000,160 | 0.4% | 80.8% |
| LOAD_FAST GET_ITER | 96,000,160 | 0.4% | 81.2% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 96,000,160 | 0.4% | 81.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 96,000,160 | 0.4% | 81.9% |
| STORE_FAST BUILD_LIST | 96,000,160 | 0.4% | 82.3% |
| BINARY_OP_ADD_INT STORE_FAST | 96,000,140 | 0.4% | 82.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 96,000,120 | 0.4% | 83.1% |
| TO_BOOL_BOOL EXTENDED_ARG | 96,000,120 | 0.4% | 83.5% |
| POP_JUMP_IF_FALSE POP_TOP | 96,000,080 | 0.4% | 83.9% |
| CALL_METHOD_DESCRIPTOR_O BINARY_OP | 96,000,080 | 0.4% | 84.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 96,000,080 | 0.4% | 84.7% |
| STORE_SUBSCR_DICT LOAD_CONST | 96,000,080 | 0.4% | 85.1% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 96,000,080 | 0.4% | 85.5% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_DICT | 96,000,040 | 0.4% | 85.9% |
| CONVERT_VALUE FORMAT_SIMPLE | 96,000,000 | 0.4% | 86.3% |
| LOAD_CONST LOAD_ATTR_METHOD_NO_DICT | 96,000,000 | 0.4% | 86.6% |
| LOAD_FAST CONVERT_VALUE | 96,000,000 | 0.4% | 87.0% |
| LOAD_FAST COPY | 96,000,000 | 0.4% | 87.4% |
| LOAD_FAST TO_BOOL_NONE | 96,000,000 | 0.4% | 87.8% |
| RETURN_CONST INTERPRETER_EXIT | 96,000,000 | 0.4% | 88.2% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 95,999,960 | 0.4% | 88.6% |
| STORE_ATTR_SLOT RETURN_CONST | 95,999,960 | 0.4% | 89.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 95,999,920 | 0.4% | 89.4% |
| BINARY_SUBSCR_TUPLE_INT CALL | 95,999,920 | 0.4% | 89.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 95,999,920 | 0.4% | 90.2% |
| COPY TO_BOOL_BOOL | 95,999,840 | 0.4% | 90.6% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 95,999,840 | 0.4% | 91.0% |
| ENTER_EXECUTOR FOR_ITER_LIST | 78,085,140 | 0.3% | 91.3% |
| LOAD_FAST TO_BOOL | 72,000,760 | 0.3% | 91.6% |
| TO_BOOL POP_JUMP_IF_TRUE | 72,000,260 | 0.3% | 91.9% |
| DELETE_SUBSCR LOAD_FAST | 72,000,160 | 0.3% | 92.2% |
| RETURN_VALUE INTERPRETER_EXIT | 72,000,160 | 0.3% | 92.5% |
| POP_JUMP_IF_TRUE LOAD_CONST | 72,000,160 | 0.3% | 92.8% |
| FOR_ITER_TUPLE STORE_FAST | 58,172,940 | 0.2% | 93.0% |
| FOR_ITER_LIST LOAD_FAST_LOAD_FAST | 58,171,180 | 0.2% | 93.2% |
| ENTER_EXECUTOR FOR_ITER_TUPLE | 57,914,220 | 0.2% | 93.5% |


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
| FOR_ITER_LIST | 57,913,000 | 60.3% |
| FOR_ITER_TUPLE | 38,087,040 | 39.7% |
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
| LOAD_GLOBAL_BUILTIN | 119,999,360 | 45.5% |
| FOR_ITER_LIST | 78,085,140 | 29.6% |
| FOR_ITER_TUPLE | 57,914,220 | 21.9% |
| LOAD_FAST | 7,999,520 | 3.0% |
| PUSH_EXC_INFO | 80 | 0.0% |


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
| LOAD_GLOBAL_BUILTIN | 288,000,000 | 75.0% |
| LOAD_FAST | 96,001,560 | 25.0% |
| LOAD_ATTR | 96,120 | 0.0% |
| LOAD_GLOBAL | 240 | 0.0% |
| LOAD_CONST | 160 | 0.0% |

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
| LOAD_GLOBAL_BUILTIN | 1,208,003,680 | 26.1% |
| STORE_FAST | 1,056,003,680 | 22.8% |
| POP_JUMP_IF_FALSE | 592,001,760 | 12.8% |
| POP_TOP | 360,000,880 | 7.8% |
| POP_JUMP_IF_TRUE | 264,000,160 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 744,000,720 | 16.1% |
| TO_BOOL_BOOL | 536,000,200 | 11.6% |
| CALL_BUILTIN_O | 520,000,720 | 11.2% |
| LOAD_CONST | 432,001,360 | 9.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 392,001,640 | 8.5% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 280,001,620 | 24.6% |
| LOAD_FAST_LOAD_FAST | 264,001,280 | 23.2% |
| LOAD_FAST | 112,000,320 | 9.9% |
| LOAD_CONST | 96,000,640 | 8.5% |
| BINARY_OP | 96,000,180 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 264,001,280 | 23.2% |
| CALL_PY_EXACT_ARGS | 264,001,280 | 23.2% |
| LOAD_FAST | 120,000,960 | 10.6% |
| CONTAINS_OP | 96,000,720 | 8.5% |
| DELETE_SUBSCR | 96,000,240 | 8.5% |


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
| TO_BOOL_BOOL | 800,001,140 | 50.0% |
| CONTAINS_OP | 288,001,520 | 18.0% |
| IS_OP | 240,000,000 | 15.0% |
| EXTENDED_ARG | 120,000,160 | 7.5% |
| TO_BOOL_NONE | 96,000,080 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 720,000,440 | 45.0% |
| LOAD_FAST | 592,001,760 | 37.0% |
| LOAD_CONST | 96,000,640 | 6.0% |
| LOAD_FAST_LOAD_FAST | 96,000,160 | 6.0% |
| POP_TOP | 96,000,080 | 6.0% |


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
| LOAD_GLOBAL_BUILTIN | 576,000,240 | 77.4% |
| LOAD_CONST | 168,000,720 | 22.6% |
| LOAD_FAST | 440 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 576,000,240 | 77.4% |
| STORE_FAST | 168,001,260 | 22.6% |
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
| LOAD_FAST_LOAD_FAST | 264,001,280 | 67.3% |
| LOAD_FAST | 128,000,320 | 32.7% |
| CALL | 280 | 0.0% |
| LOAD_CONST | 40 | 0.0% |
| BINARY_OP_ADD_INT | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 392,001,960 | 100.0% |


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
| ENTER_EXECUTOR | 78,085,140 | 57.1% |
| GET_ITER | 57,913,000 | 42.3% |
| FOR_ITER_TUPLE | 861,840 | 0.6% |
| JUMP_BACKWARD | 600 | 0.0% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 58,171,180 | 42.5% |
| STORE_FAST | 53,827,340 | 39.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 24,000,240 | 17.5% |
| FOR_ITER_TUPLE | 861,820 | 0.6% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 57,914,220 | 59.8% |
| GET_ITER | 38,087,040 | 39.3% |
| FOR_ITER_LIST | 861,820 | 0.9% |
| JUMP_BACKWARD | 640 | 0.0% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 58,172,940 | 60.1% |
| LOAD_FAST_LOAD_FAST | 37,828,980 | 39.1% |
| FOR_ITER_LIST | 861,840 | 0.9% |


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

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 96,000,000 | 75.0% |
| LOAD_FAST | 23,999,920 | 18.7% |
| LOAD_FAST_LOAD_FAST | 8,000,040 | 6.3% |
| LOAD_ATTR | 160 | 0.0% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 40 | 0.0% |

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
| LOAD_FAST | 392,001,640 | 100.0% |
| LOAD_ATTR | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 280,001,620 | 71.4% |
| LOAD_FAST | 112,000,280 | 28.6% |


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
| LOAD_FAST | 744,000,720 | 35.9% |
| POP_JUMP_IF_FALSE | 720,000,440 | 34.7% |
| STORE_FAST | 224,000,720 | 10.8% |
| RESUME_CHECK | 192,001,240 | 9.3% |
| ENTER_EXECUTOR | 119,999,360 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,208,003,680 | 58.3% |
| CALL_BUILTIN_FAST | 576,000,240 | 27.8% |
| LOAD_ATTR | 288,000,000 | 13.9% |
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
| CALL_PY_EXACT_ARGS | 392,001,960 | 70.0% |
| CACHE | 168,000,000 | 30.0% |
| CALL | 140 | 0.0% |
| COPY_FREE_VARS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200,000,860 | 35.7% |
| LOAD_GLOBAL_BUILTIN | 192,001,240 | 34.3% |
| LOAD_FAST_LOAD_FAST | 95,999,960 | 17.1% |
| LOAD_GLOBAL_MODULE | 48,000,040 | 8.6% |
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
| CALL_BUILTIN_FAST | 576,000,240 | 40.4% |
| LOAD_FAST | 536,000,200 | 37.6% |
| LOAD_ATTR_INSTANCE_VALUE | 216,000,280 | 15.2% |
| COPY | 95,999,840 | 6.7% |
| TO_BOOL | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 800,001,140 | 56.2% |
| POP_JUMP_IF_TRUE | 527,999,940 | 37.1% |
| EXTENDED_ARG | 96,000,120 | 6.7% |


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
|     deferred | 96,001,940 | 4.4% |
|          hit | 2,088,005,740 | 95.6% |

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
|     deferred | 737,869,762,948,380,341,060 | 315,700,594,789,225.1% |
|          hit | 142,369,480 | 60.9% |
|         miss | 91,354,900 | 39.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,723,740 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 384,001,360 | 32.2% |
|          hit | 808,003,120 | 67.8% |

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
|          hit | 2,384,005,120 | 100.0% |

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
|     deferred | 72,000,760 | 4.5% |
|          hit | 1,544,001,400 | 95.5% |

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
| Basic | 13,128,041,320 | 53.7% |
| Not specialized | 2,896,179,020 | 11.8% |
| Specialized hits | 8,342,388,280 | 34.1% |
| Specialized misses | 91,354,900 | 0.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER | 737,869,762,948,380,341,060 | 100.0% |
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
| FOR_ITER_TUPLE | 45,678,260 | 50.0% |
| FOR_ITER_LIST | 45,676,640 | 50.0% |
| CACHE | 0 | 0.0% |
| DELETE_SUBSCR | 0 | 0.0% |
| FORMAT_SIMPLE | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 168,000,160 | 30.0% |
| Calls to Python functions inlined | 392,002,400 | 70.0% |
| Calls via PyEval_EvalFrame (total) | 168,000,160 | 30.0% |
| Calls via PyEval_EvalFrame (vector) | 168,000,160 | 30.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 168,000,160 | 30.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 24,000,000 | 4.3% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 48,000,000 | 8.6% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 80 | 0.0% |
| Frames pushed | 640,000,200 | 114.3% |


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
| Interpreter increfs | 8,832,160,700 | 73.1% |
| Interpreter decrefs | 10,389,369,620 | 74.6% |
| Increfs | 3,247,853,631 | 26.9% |
| Decrefs | 3,530,647,300 | 25.4% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 120,025,949 |  |
| Method cache misses | 291 |  |
| Method cache collisions | 319 |  |
| Method cache dunder hits | 1,320,072,529 |  |
| Method cache dunder misses | 131 |  |


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
| Trace too long | 100 | 100.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 263,998,320 |  |
| Uops executed | 9,415,921,640 | 35.67 |

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
| <= 1 | 63,999,800 | 24.2% |
| <= 2 | 71,999,560 | 27.3% |
| <= 4 | 0 | 0.0% |
| <= 8 | 80 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 127,998,880 | 48.5% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,807,983,520 | 19.2% | 19.2% |  |
| _SET_IP | 767,993,360 | 8.2% | 27.4% |  |
| _CHECK_VALIDITY | 767,993,280 | 8.2% | 35.5% |  |
| _GUARD_GLOBALS_VERSION | 495,996,560 | 5.3% | 40.8% |  |
| STORE_FAST | 415,995,920 | 4.4% | 45.2% |  |
| _GUARD_BUILTINS_VERSION | 375,997,200 | 4.0% | 49.2% |  |
| _LOAD_GLOBAL_BUILTINS | 375,997,200 | 4.0% | 53.2% |  |
| _GUARD_TYPE_VERSION | 255,997,760 | 2.7% | 55.9% |  |
| LOAD_CONST | 247,998,240 | 2.6% | 58.5% |  |
| RESUME_CHECK | 247,998,240 | 2.6% | 61.2% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 247,998,240 | 2.6% | 63.8% |  |
| _GUARD_KEYS_VERSION | 247,998,240 | 2.6% | 66.4% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 247,998,240 | 2.6% | 69.1% |  |
| _CHECK_PEP_523 | 247,998,240 | 2.6% | 71.7% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 247,998,240 | 2.6% | 74.3% |  |
| _CHECK_STACK_SPACE | 247,998,240 | 2.6% | 77.0% |  |
| _INIT_CALL_PY_EXACT_ARGS | 247,998,240 | 2.6% | 79.6% |  |
| _PUSH_FRAME | 247,998,240 | 2.6% | 82.2% |  |
| _SAVE_RETURN_OFFSET | 247,998,240 | 2.6% | 84.9% |  |
| _ITER_CHECK_TUPLE | 207,999,360 | 2.2% | 87.1% | 30.8% |
| _GUARD_NOT_EXHAUSTED_TUPLE | 143,999,560 | 1.5% | 88.6% | 33.3% |
| _GUARD_IS_FALSE_POP | 143,997,920 | 1.5% | 90.1% |  |
| CALL_BUILTIN_FAST | 127,998,960 | 1.4% | 91.5% |  |
| CONTAINS_OP | 127,998,880 | 1.4% | 92.9% |  |
| _EXIT_TRACE | 127,998,880 | 1.4% | 94.2% |  |
| CALL_TYPE_1 | 119,999,360 | 1.3% | 95.5% |  |
| _LOAD_GLOBAL_MODULE | 119,999,360 | 1.3% | 96.8% |  |
| _ITER_NEXT_TUPLE | 95,999,680 | 1.0% | 97.8% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 47,999,360 | 0.5% | 98.3% | 50.0% |
| _ITER_CHECK_LIST | 47,999,360 | 0.5% | 98.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 23,999,680 | 0.3% | 99.1% |  |
| _ITER_NEXT_LIST | 23,999,680 | 0.3% | 99.3% |  |
| CALL_BUILTIN_O | 15,999,040 | 0.2% | 99.5% |  |
| TO_BOOL_BOOL | 15,999,040 | 0.2% | 99.7% |  |
| POP_TOP | 7,999,520 | 0.1% | 99.7% |  |
| PUSH_NULL | 7,999,520 | 0.1% | 99.8% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 7,999,520 | 0.1% | 99.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 7,999,520 | 0.1% | 100.0% |  |


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
| Number of data files | 40 |


</details>

---
Stats gathered on: 2023-11-16
