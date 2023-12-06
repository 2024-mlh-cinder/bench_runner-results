
# Pystats results

- benchmark: pprint
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 3,402,006,240 | 19.2% | 19.2% |  |
| STORE_FAST | 1,596,002,880 | 9.0% | 28.3% |  |
| LOAD_GLOBAL_BUILTIN | 1,428,001,980 | 8.1% | 36.3% |  |
| LOAD_CONST | 1,170,002,100 | 6.6% | 43.0% |  |
| POP_JUMP_IF_FALSE | 1,074,001,620 | 6.1% | 49.0% |  |
| TO_BOOL_BOOL | 978,000,900 | 5.5% | 54.6% |  |
| LOAD_FAST_LOAD_FAST | 846,001,980 | 4.8% | 59.3% |  |
| RETURN_VALUE | 528,000,420 | 3.0% | 62.3% |  |
| POP_JUMP_IF_TRUE | 486,000,360 | 2.7% | 65.1% |  |
| CALL_BUILTIN_FAST | 468,000,780 | 2.6% | 67.7% |  |
| CALL_BUILTIN_O | 426,000,420 | 2.4% | 70.1% |  |
| RESUME_CHECK | 414,000,840 | 2.3% | 72.5% |  |
| CALL_PY_EXACT_ARGS | 288,000,600 | 1.6% | 74.1% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 282,000,660 | 1.6% | 75.7% |  |
| POP_TOP | 276,000,720 | 1.6% | 77.3% |  |
| BUILD_TUPLE | 270,000,120 | 1.5% | 78.8% |  |
| LOAD_ATTR | 252,062,300 | 1.4% | 80.2% |  |
| LOAD_GLOBAL_MODULE | 234,000,380 | 1.3% | 81.5% |  |
| UNPACK_SEQUENCE_TUPLE | 234,000,060 | 1.3% | 82.9% |  |
| CONTAINS_OP | 216,000,420 | 1.2% | 84.1% |  |
| ENTER_EXECUTOR | 197,999,940 | 1.1% | 85.2% |  |
| PUSH_NULL | 192,000,780 | 1.1% | 86.3% |  |
| IS_OP | 180,000,120 | 1.0% | 87.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 174,000,420 | 1.0% | 88.3% |  |
| CALL_TYPE_1 | 144,000,180 | 0.8% | 89.1% |  |
| INTERPRETER_EXIT | 126,000,120 | 0.7% | 89.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 96,000,240 | 0.5% | 90.4% |  |
| EXTENDED_ARG | 90,000,120 | 0.5% | 90.9% |  |
| FOR_ITER_LIST | 84,436,840 | 0.5% | 91.3% | 27.4% |
| CALL_METHOD_DESCRIPTOR_O | 78,000,240 | 0.4% | 91.8% |  |
| RETURN_CONST | 78,000,180 | 0.4% | 92.2% |  |
| CALL | 72,018,520 | 0.4% | 92.6% |  |
| BINARY_OP | 72,018,000 | 0.4% | 93.0% |  |
| BINARY_OP_ADD_INT | 72,000,360 | 0.4% | 93.4% |  |
| STORE_SUBSCR_DICT | 72,000,180 | 0.4% | 93.9% |  |
| DELETE_SUBSCR | 72,000,180 | 0.4% | 94.3% |  |
| TO_BOOL_NONE | 72,000,120 | 0.4% | 94.7% |  |
| GET_ITER | 72,000,120 | 0.4% | 95.1% |  |
| BUILD_LIST | 72,000,120 | 0.4% | 95.5% |  |
| COPY | 72,000,060 | 0.4% | 95.9% |  |
| STORE_ATTR_SLOT | 72,000,000 | 0.4% | 96.3% |  |
| FORMAT_SIMPLE | 72,000,000 | 0.4% | 96.7% |  |
| CONVERT_VALUE | 72,000,000 | 0.4% | 97.1% |  |
| BINARY_SUBSCR_TUPLE_INT | 72,000,000 | 0.4% | 97.5% |  |
| COMPARE_OP_INT | 60,000,240 | 0.3% | 97.9% |  |
| TO_BOOL | 54,013,220 | 0.3% | 98.2% |  |
| CALL_LEN | 42,000,060 | 0.2% | 98.4% |  |
| FOR_ITER_TUPLE | 36,436,000 | 0.2% | 98.6% | 63.5% |
| JUMP_FORWARD | 36,000,180 | 0.2% | 98.8% |  |
| LOAD_ATTR_SLOT | 36,000,000 | 0.2% | 99.0% |  |
| BUILD_STRING | 36,000,000 | 0.2% | 99.2% |  |
| STORE_FAST_STORE_FAST | 24,000,120 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,000,120 | 0.1% | 99.5% |  |
| NOP | 18,000,240 | 0.1% | 99.6% |  |
| TO_BOOL_LIST | 18,000,120 | 0.1% | 99.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 18,000,000 | 0.1% | 99.8% |  |
| CALL_KW | 18,000,000 | 0.1% | 99.9% |  |
| BINARY_OP_SUBTRACT_INT | 12,000,300 | 0.1% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 6,000,180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 220 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 200 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 60 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NONE | 60 | 0.0% | 100.0% |  |
| POP_EXCEPT | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 60 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 60 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 60 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 0.0% | 100.0% |  |
| BUILD_MAP | 60 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_UNICODE | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 906,001,320 | 5.1% | 5.1% |
| STORE_FAST LOAD_FAST | 792,001,560 | 4.5% | 9.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 522,000,600 | 3.0% | 12.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 510,000,660 | 2.9% | 15.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 486,000,360 | 2.7% | 18.2% |
| STORE_FAST STORE_FAST | 456,000,000 | 2.6% | 20.8% |
| LOAD_FAST TO_BOOL_BOOL | 402,000,280 | 2.3% | 23.0% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 396,000,120 | 2.2% | 25.3% |
| LOAD_FAST CALL_BUILTIN_O | 390,000,420 | 2.2% | 27.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 372,000,840 | 2.1% | 29.6% |
| LOAD_GLOBAL_BUILTIN CALL_BUILTIN_FAST | 342,000,480 | 1.9% | 31.5% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 342,000,480 | 1.9% | 33.5% |
| LOAD_FAST LOAD_CONST | 324,000,540 | 1.8% | 35.3% |
| LOAD_CONST LOAD_CONST | 306,000,240 | 1.7% | 37.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 288,000,600 | 1.6% | 38.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 282,000,620 | 1.6% | 40.2% |
| POP_TOP LOAD_FAST | 270,000,420 | 1.5% | 41.8% |
| BUILD_TUPLE RETURN_VALUE | 270,000,120 | 1.5% | 43.3% |
| RETURN_VALUE UNPACK_SEQUENCE_TUPLE | 234,000,060 | 1.3% | 44.6% |
| RETURN_VALUE RETURN_VALUE | 234,000,060 | 1.3% | 45.9% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST | 228,000,000 | 1.3% | 47.2% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 216,000,420 | 1.2% | 48.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 198,000,660 | 1.1% | 49.6% |
| LOAD_CONST STORE_FAST | 198,000,540 | 1.1% | 50.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 198,000,240 | 1.1% | 51.8% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 198,000,220 | 1.1% | 52.9% |
| POP_JUMP_IF_TRUE LOAD_FAST | 198,000,120 | 1.1% | 54.1% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 197,999,940 | 1.1% | 55.2% |
| LOAD_FAST PUSH_NULL | 192,000,540 | 1.1% | 56.3% |
| PUSH_NULL LOAD_FAST | 192,000,240 | 1.1% | 57.3% |
| CALL_BUILTIN_O POP_TOP | 192,000,120 | 1.1% | 58.4% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR | 180,000,120 | 1.0% | 59.4% |
| LOAD_ATTR IS_OP | 180,000,120 | 1.0% | 60.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 168,000,180 | 1.0% | 61.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 162,000,120 | 0.9% | 62.3% |
| LOAD_CONST BUILD_TUPLE | 162,000,000 | 0.9% | 63.2% |
| CALL_BUILTIN_O LOAD_CONST | 162,000,000 | 0.9% | 64.2% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 156,000,320 | 0.9% | 65.0% |
| RESUME_CHECK LOAD_FAST | 144,000,360 | 0.8% | 65.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 144,000,300 | 0.8% | 66.7% |
| LOAD_FAST CALL_TYPE_1 | 144,000,160 | 0.8% | 67.5% |
| LOAD_GLOBAL_MODULE CONTAINS_OP | 144,000,120 | 0.8% | 68.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 144,000,120 | 0.8% | 69.1% |
| CALL_TYPE_1 STORE_FAST | 144,000,120 | 0.8% | 69.9% |
| IS_OP POP_JUMP_IF_FALSE | 144,000,000 | 0.8% | 70.7% |
| CALL_BUILTIN_FAST STORE_FAST | 126,000,300 | 0.7% | 71.5% |
| LOAD_CONST CALL_BUILTIN_FAST | 126,000,120 | 0.7% | 72.2% |
| CACHE RESUME_CHECK | 126,000,120 | 0.7% | 72.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 90,000,240 | 0.5% | 73.4% |
| EXTENDED_ARG POP_JUMP_IF_FALSE | 90,000,120 | 0.5% | 73.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 84,000,360 | 0.5% | 74.4% |
| LOAD_FAST LOAD_FAST_LOAD_FAST | 84,000,000 | 0.5% | 74.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 84,000,000 | 0.5% | 75.3% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_O | 78,000,120 | 0.4% | 75.8% |
| LOAD_FAST LOAD_ATTR | 72,000,340 | 0.4% | 76.2% |
| LOAD_FAST_LOAD_FAST CONTAINS_OP | 72,000,300 | 0.4% | 76.6% |
| CALL_BUILTIN_O STORE_FAST | 72,000,300 | 0.4% | 77.0% |
| STORE_FAST LOAD_CONST | 72,000,240 | 0.4% | 77.4% |
| POP_JUMP_IF_FALSE LOAD_CONST | 72,000,240 | 0.4% | 77.8% |
| LOAD_CONST LOAD_FAST_LOAD_FAST | 72,000,240 | 0.4% | 78.2% |
| LOAD_CONST BINARY_OP_ADD_INT | 72,000,240 | 0.4% | 78.6% |
| LOAD_FAST_LOAD_FAST DELETE_SUBSCR | 72,000,180 | 0.4% | 79.0% |
| LOAD_ATTR STORE_FAST | 72,000,180 | 0.4% | 79.4% |
| BINARY_OP_ADD_INT STORE_FAST | 72,000,180 | 0.4% | 79.8% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_DICT | 72,000,160 | 0.4% | 80.2% |
| TO_BOOL_NONE POP_JUMP_IF_FALSE | 72,000,120 | 0.4% | 80.7% |
| TO_BOOL_BOOL EXTENDED_ARG | 72,000,120 | 0.4% | 81.1% |
| STORE_SUBSCR_DICT LOAD_CONST | 72,000,120 | 0.4% | 81.5% |
| STORE_FAST BUILD_LIST | 72,000,120 | 0.4% | 81.9% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 72,000,120 | 0.4% | 82.3% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 72,000,120 | 0.4% | 82.7% |
| LOAD_FAST TO_BOOL_NONE | 72,000,120 | 0.4% | 83.1% |
| LOAD_FAST GET_ITER | 72,000,120 | 0.4% | 83.5% |
| LOAD_CONST LOAD_ATTR_METHOD_NO_DICT | 72,000,120 | 0.4% | 83.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 72,000,120 | 0.4% | 84.3% |
| CALL_METHOD_DESCRIPTOR_O BINARY_OP | 72,000,120 | 0.4% | 84.7% |
| BUILD_LIST STORE_FAST | 72,000,120 | 0.4% | 85.1% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 72,000,120 | 0.4% | 85.5% |
| POP_JUMP_IF_FALSE POP_TOP | 72,000,060 | 0.4% | 85.9% |
| STORE_ATTR_SLOT RETURN_CONST | 72,000,000 | 0.4% | 86.4% |
| RETURN_CONST INTERPRETER_EXIT | 72,000,000 | 0.4% | 86.8% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 72,000,000 | 0.4% | 87.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 72,000,000 | 0.4% | 87.6% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 72,000,000 | 0.4% | 88.0% |
| LOAD_FAST COPY | 72,000,000 | 0.4% | 88.4% |
| LOAD_FAST CONVERT_VALUE | 72,000,000 | 0.4% | 88.8% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 72,000,000 | 0.4% | 89.2% |
| COPY TO_BOOL_BOOL | 72,000,000 | 0.4% | 89.6% |
| CONVERT_VALUE FORMAT_SIMPLE | 72,000,000 | 0.4% | 90.0% |
| BINARY_SUBSCR_TUPLE_INT CALL | 72,000,000 | 0.4% | 90.4% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 59,999,880 | 0.3% | 90.8% |
| FOR_ITER_LIST STORE_FAST | 54,218,500 | 0.3% | 91.1% |
| RETURN_VALUE INTERPRETER_EXIT | 54,000,120 | 0.3% | 91.4% |
| POP_JUMP_IF_TRUE LOAD_CONST | 54,000,120 | 0.3% | 91.7% |
| DELETE_SUBSCR LOAD_FAST | 54,000,120 | 0.3% | 92.0% |
| LOAD_FAST TO_BOOL | 54,000,020 | 0.3% | 92.3% |
| TO_BOOL POP_JUMP_IF_TRUE | 54,000,000 | 0.3% | 92.6% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 54,000,000 | 0.3% | 92.9% |
| GET_ITER FOR_ITER_LIST | 52,473,080 | 0.3% | 93.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 42,000,240 | 0.2% | 93.4% |


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
| RESUME_CHECK | 126,000,120 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 72,000,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,000,120 | 75.0% |
| LOAD_CONST | 18,000,000 | 25.0% |
| RETURN_CONST | 60 | 0.0% |


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CONVERT_VALUE | 72,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 36,000,000 | 50.0% |
| BUILD_STRING | 36,000,000 | 50.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,000,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 52,473,080 | 72.9% |
| FOR_ITER_TUPLE | 19,527,040 | 27.1% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 72,000,000 | 57.1% |
| RETURN_VALUE | 54,000,120 | 42.9% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,000,000 | 100.0% |
| STORE_FAST | 120 | 0.0% |
| POP_TOP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,000,000 | 100.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 100 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 192,000,120 | 69.6% |
| POP_JUMP_IF_FALSE | 72,000,060 | 26.1% |
| RETURN_CONST | 6,000,180 | 2.2% |
| CALL_METHOD_DESCRIPTOR_O | 6,000,120 | 2.2% |
| CALL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 270,000,420 | 97.8% |
| RETURN_CONST | 6,000,060 | 2.2% |
| NOP | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 192,000,540 | 100.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR_MODULE | 80 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 192,000,240 | 100.0% |
| CALL | 480 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 270,000,120 | 51.1% |
| RETURN_VALUE | 234,000,060 | 44.3% |
| COMPARE_OP_INT | 18,000,000 | 3.4% |
| LOAD_FAST | 6,000,180 | 1.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 234,000,060 | 44.3% |
| RETURN_VALUE | 234,000,060 | 44.3% |
| INTERPRETER_EXIT | 54,000,120 | 10.2% |
| STORE_FAST | 6,000,060 | 1.1% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,000,020 | 100.0% |
| TO_BOOL | 13,200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 54,000,000 | 100.0% |
| TO_BOOL | 13,200 | 0.0% |
| TO_BOOL_BOOL | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 72,000,120 | 100.0% |
| BINARY_OP | 17,640 | 0.0% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 72,000,120 | 100.0% |
| BINARY_OP | 17,640 | 0.0% |
| BINARY_OP_ADD_INT | 80 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 60 | 0.0% |
| BINARY_OP_ADD_UNICODE | 60 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 72,000,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 72,000,120 | 100.0% |


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 36,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 36,000,000 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 162,000,000 | 60.0% |
| LOAD_FAST_LOAD_FAST | 72,000,120 | 26.7% |
| CALL | 36,000,000 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 270,000,120 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 72,000,000 | 100.0% |
| CALL | 17,780 | 0.0% |
| PUSH_NULL | 480 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 36,000,000 | 50.0% |
| BUILD_TUPLE | 36,000,000 | 50.0% |
| CALL | 17,780 | 0.0% |
| POP_TOP | 240 | 0.0% |
| STORE_FAST | 180 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 120 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 18,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 18,000,000 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 60 | 100.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 144,000,120 | 66.7% |
| LOAD_FAST_LOAD_FAST | 72,000,300 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 216,000,420 | 100.0% |


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FORMAT_SIMPLE | 72,000,000 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,000,000 | 100.0% |
| BINARY_OP_ADD_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 72,000,000 | 100.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 197,999,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 59,999,880 | 30.3% |
| LOAD_GLOBAL_BUILTIN | 54,000,000 | 27.3% |
| FOR_ITER_LIST | 31,527,400 | 15.9% |
| LOAD_FAST | 18,000,000 | 9.1% |
| LOAD_ATTR_INSTANCE_VALUE | 18,000,000 | 9.1% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 72,000,120 | 80.0% |
| IS_OP | 18,000,000 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 90,000,120 | 100.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 180,000,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 144,000,000 | 80.0% |
| POP_JUMP_IF_TRUE | 18,000,120 | 10.0% |
| EXTENDED_ARG | 18,000,000 | 10.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 36,000,120 | 100.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 18,000,120 | 50.0% |
| LOAD_FAST | 18,000,000 | 50.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 180,000,120 | 71.4% |
| LOAD_FAST | 72,000,340 | 28.6% |
| LOAD_ATTR | 61,620 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| CALL_TYPE_1 | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 180,000,120 | 71.4% |
| STORE_FAST | 72,000,180 | 28.6% |
| LOAD_ATTR | 61,620 | 0.0% |
| LOAD_ATTR_MODULE | 80 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 324,000,540 | 27.7% |
| LOAD_CONST | 306,000,240 | 26.2% |
| CALL_BUILTIN_O | 162,000,000 | 13.8% |
| STORE_FAST | 72,000,240 | 6.2% |
| POP_JUMP_IF_FALSE | 72,000,240 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 306,000,240 | 26.2% |
| STORE_FAST | 198,000,540 | 16.9% |
| BUILD_TUPLE | 162,000,000 | 13.8% |
| CALL_BUILTIN_FAST | 126,000,120 | 10.8% |
| LOAD_FAST_LOAD_FAST | 72,000,240 | 6.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 50.0% |
| NOP | 120 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 50.0% |
| PUSH_NULL | 120 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 906,001,320 | 26.6% |
| STORE_FAST | 792,001,560 | 23.3% |
| POP_JUMP_IF_FALSE | 372,000,840 | 10.9% |
| POP_TOP | 270,000,420 | 7.9% |
| POP_JUMP_IF_TRUE | 198,000,120 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 522,000,600 | 15.3% |
| TO_BOOL_BOOL | 402,000,280 | 11.8% |
| CALL_BUILTIN_O | 390,000,420 | 11.5% |
| LOAD_CONST | 324,000,540 | 9.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 282,000,620 | 8.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 198,000,660 | 23.4% |
| LOAD_FAST_LOAD_FAST | 198,000,240 | 23.4% |
| LOAD_FAST | 84,000,000 | 9.9% |
| LOAD_CONST | 72,000,240 | 8.5% |
| POP_JUMP_IF_FALSE | 72,000,120 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,000,240 | 23.4% |
| CALL_PY_EXACT_ARGS | 198,000,220 | 23.4% |
| LOAD_FAST | 84,000,360 | 9.9% |
| CONTAINS_OP | 72,000,300 | 8.5% |
| DELETE_SUBSCR | 72,000,180 | 8.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 36.4% |
| RESUME_CHECK | 60 | 27.3% |
| STORE_FAST_STORE_FAST | 20 | 9.1% |
| PUSH_EXC_INFO | 20 | 9.1% |
| NOP | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 100 | 45.5% |
| LOAD_GLOBAL_BUILTIN | 80 | 36.4% |
| LOAD_ATTR | 40 | 18.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 510,000,660 | 47.5% |
| CONTAINS_OP | 216,000,420 | 20.1% |
| IS_OP | 144,000,000 | 13.4% |
| EXTENDED_ARG | 90,000,120 | 8.4% |
| TO_BOOL_NONE | 72,000,120 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 486,000,360 | 45.3% |
| LOAD_FAST | 372,000,840 | 34.6% |
| LOAD_CONST | 72,000,240 | 6.7% |
| LOAD_FAST_LOAD_FAST | 72,000,120 | 6.7% |
| POP_TOP | 72,000,060 | 6.7% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 396,000,120 | 81.5% |
| TO_BOOL | 54,000,000 | 11.1% |
| TO_BOOL_LIST | 18,000,120 | 3.7% |
| IS_OP | 18,000,120 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 198,000,120 | 40.7% |
| ENTER_EXECUTOR | 197,999,940 | 40.7% |
| LOAD_CONST | 54,000,120 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 36,000,120 | 7.4% |
| RETURN_CONST | 60 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 72,000,000 | 92.3% |
| POP_TOP | 6,000,060 | 7.7% |
| POP_JUMP_IF_TRUE | 60 | 0.0% |
| DELETE_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 72,000,000 | 92.3% |
| POP_TOP | 6,000,180 | 7.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 456,000,000 | 28.6% |
| UNPACK_SEQUENCE_TUPLE | 228,000,000 | 14.3% |
| LOAD_CONST | 198,000,540 | 12.4% |
| CALL_TYPE_1 | 144,000,120 | 9.0% |
| CALL_BUILTIN_FAST | 126,000,300 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 792,001,560 | 49.6% |
| STORE_FAST | 456,000,000 | 28.6% |
| LOAD_GLOBAL_BUILTIN | 168,000,180 | 10.5% |
| LOAD_CONST | 72,000,240 | 4.5% |
| BUILD_LIST | 72,000,120 | 4.5% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 18,000,000 | 75.0% |
| UNPACK_SEQUENCE_TUPLE | 6,000,060 | 25.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,000,000 | 75.0% |
| STORE_FAST | 6,000,060 | 25.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 72,000,240 | 100.0% |
| BINARY_OP | 80 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 72,000,180 | 100.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| COPY | 60 | 0.0% |
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
| LOAD_CONST | 72,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 72,000,000 | 100.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 342,000,480 | 73.1% |
| LOAD_CONST | 126,000,120 | 26.9% |
| LOAD_FAST | 140 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 342,000,480 | 73.1% |
| STORE_FAST | 126,000,300 | 26.9% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 390,000,420 | 91.5% |
| BUILD_STRING | 36,000,000 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 192,000,120 | 45.1% |
| LOAD_CONST | 162,000,000 | 38.0% |
| STORE_FAST | 72,000,300 | 16.9% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,000,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 36,000,000 | 85.7% |
| LOAD_FAST | 6,000,060 | 14.3% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 24,000,060 | 100.0% |
| LOAD_ATTR_METHOD_LAZY_DICT | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 18,000,000 | 75.0% |
| LOAD_FAST | 6,000,060 | 25.0% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 78,000,120 | 100.0% |
| LOAD_CONST | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 72,000,120 | 92.3% |
| POP_TOP | 6,000,120 | 7.7% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,000,220 | 68.7% |
| LOAD_FAST | 90,000,240 | 31.3% |
| CALL | 60 | 0.0% |
| LOAD_CONST | 40 | 0.0% |
| BINARY_OP_ADD_INT | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 288,000,600 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 144,000,160 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 144,000,120 | 100.0% |
| LOAD_ATTR | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 36,000,120 | 60.0% |
| LOAD_ATTR_SLOT | 18,000,000 | 30.0% |
| LOAD_FAST | 6,000,060 | 10.0% |
| COMPARE_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 42,000,240 | 70.0% |
| RETURN_VALUE | 18,000,000 | 30.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 52,473,080 | 62.1% |
| ENTER_EXECUTOR | 31,527,400 | 37.3% |
| FOR_ITER_TUPLE | 436,360 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 54,218,500 | 64.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 18,000,000 | 21.3% |
| LOAD_FAST_LOAD_FAST | 11,781,980 | 14.0% |
| FOR_ITER_TUPLE | 436,360 | 0.5% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 19,527,040 | 53.6% |
| ENTER_EXECUTOR | 16,472,600 | 45.2% |
| FOR_ITER_LIST | 436,360 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,781,500 | 81.7% |
| LOAD_FAST_LOAD_FAST | 6,218,140 | 17.1% |
| FOR_ITER_LIST | 436,360 | 1.2% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 156,000,320 | 89.7% |
| ENTER_EXECUTOR | 18,000,000 | 10.3% |
| LOAD_ATTR | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 162,000,120 | 93.1% |
| LOAD_FAST | 12,000,180 | 6.9% |
| LOAD_CONST | 60 | 0.0% |
| BINARY_OP_ADD_INT | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 72,000,120 | 75.0% |
| LOAD_FAST | 18,000,000 | 18.7% |
| LOAD_FAST_LOAD_FAST | 6,000,060 | 6.3% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 40 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,000,120 | 75.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 24,000,060 | 25.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 282,000,620 | 100.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 198,000,660 | 70.2% |
| LOAD_FAST | 84,000,000 | 29.8% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 60.0% |
| LOAD_ATTR | 80 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 60.0% |
| PUSH_NULL | 80 | 40.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,000,000 | 50.0% |
| COMPARE_OP_INT | 18,000,000 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 522,000,600 | 36.6% |
| POP_JUMP_IF_FALSE | 486,000,360 | 34.0% |
| STORE_FAST | 168,000,180 | 11.8% |
| RESUME_CHECK | 144,000,300 | 10.1% |
| ENTER_EXECUTOR | 54,000,000 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 906,001,320 | 63.4% |
| CALL_BUILTIN_FAST | 342,000,480 | 23.9% |
| LOAD_ATTR | 180,000,120 | 12.6% |
| CHECK_EXC_MATCH | 60 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 144,000,120 | 61.5% |
| RESUME_CHECK | 36,000,120 | 15.4% |
| CALL | 36,000,000 | 15.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 18,000,000 | 7.7% |
| LOAD_GLOBAL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CONTAINS_OP | 144,000,120 | 61.5% |
| LOAD_FAST | 72,000,000 | 30.8% |
| LOAD_CONST | 18,000,000 | 7.7% |
| LOAD_ATTR_MODULE | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 288,000,600 | 69.6% |
| CACHE | 126,000,120 | 30.4% |
| COPY_FREE_VARS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 144,000,360 | 34.8% |
| LOAD_GLOBAL_BUILTIN | 144,000,300 | 34.8% |
| LOAD_FAST_LOAD_FAST | 72,000,000 | 17.4% |
| LOAD_GLOBAL_MODULE | 36,000,120 | 8.7% |
| NOP | 18,000,000 | 4.3% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 72,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 72,000,000 | 100.0% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 72,000,160 | 100.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 72,000,120 | 100.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 402,000,280 | 41.1% |
| CALL_BUILTIN_FAST | 342,000,480 | 35.0% |
| LOAD_ATTR_INSTANCE_VALUE | 162,000,120 | 16.6% |
| COPY | 72,000,000 | 7.4% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 510,000,660 | 52.1% |
| POP_JUMP_IF_TRUE | 396,000,120 | 40.5% |
| EXTENDED_ARG | 72,000,120 | 7.4% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,000,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 18,000,120 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,000,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 72,000,120 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 234,000,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 228,000,000 | 97.4% |
| STORE_FAST_STORE_FAST | 6,000,060 | 2.6% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 18,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 18,000,000 | 100.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 60 | 100.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |


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
| LOAD_FAST | 12,000,160 | 100.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000,180 | 50.0% |
| LOAD_FAST | 6,000,060 | 50.0% |
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
| LOAD_FAST | 6,000,120 | 100.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000,000 | 100.0% |
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

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     72000000 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     72000180 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     54000000 | 4.8% |
|          hit |   1068001140 | 95.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.2% |
| Failure | 13,200 | 99.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 8,800 | 66.7% |
| dict | 4,400 | 33.3% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     72000180 | 46.1% |
|          hit |     84000840 | 53.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 1.1% |
| Failure | 17,620 | 98.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 17,600 | 99.9% |
| multiply different types | 20 | 0.1% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     72000540 | 4.7% |
|          hit |   1470002460 | 95.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 1.1% |
| Failure | 17,780 | 98.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| no dict | 17,600 | 99.0% |
| cfunc noargs | 120 | 0.7% |
| other | 40 | 0.2% |
| class no vectorcall | 20 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     60000240 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |       872720 | 0.7% |
|          hit |     74618320 | 61.7% |
|         miss |     46254520 | 38.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 872,720 | 100.0% |
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
| specialization.deferred |    252000400 | 29.8% |
|          hit |    594001760 | 70.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 0.5% |
| Failure | 61,620 | 99.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 44,000 | 71.4% |
| method | 17,620 | 28.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           40 | 0.0% |
|          hit |   1662002360 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
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
|          hit |     72000000 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |    252000060 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 9,732,017,880 | 55.0% |
| Not specialized | 2,056,368,960 | 11.6% |
| Specialized | 5,894,628,200 | 33.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR | 252,000,400 | 56.0% |
| CALL | 72,000,540 | 16.0% |
| BINARY_OP | 72,000,180 | 16.0% |
| TO_BOOL | 54,000,000 | 12.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |
| TO_BOOL_LIST | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER_LIST | 23,127,440 | 50.0% |
| FOR_ITER_TUPLE | 23,127,080 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |
| TO_BOOL_LIST | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| STORE_SUBSCR_DICT | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 126,000,120 | 30.4% |
| Calls to Python functions inlined | 288,000,720 | 69.6% |
| Calls via PyEval_EvalFrame (total) | 126,000,120 | 30.4% |
| Calls via PyEval_EvalFrame (vector) | 126,000,120 | 30.4% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 126,000,120 | 30.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 18,000,000 | 4.3% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 36,000,000 | 8.7% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 606,000,600 | 146.4% |
| Frame objects created | 60 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 546,000,560 | 38.7% |
| Frees to freelist | 546,000,480 |  |
| Allocations | 864,001,480 | 61.3% |
| Allocations to 512 bytes | 864,001,300 | 61.3% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 180 | 0.0% |
| Frees | 936,001,560 |  |
| New values | 0 |  |
| Interpreter increfs | 5,204,111,900 | 57.4% |
| Interpreter decrefs | 6,983,794,220 | 66.9% |
| Increfs | 3,855,899,361 | 42.6% |
| Decrefs | 3,456,218,781 | 33.1% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 90,018,037 |  |
| Method cache misses | 3 |  |
| Method cache collisions | 4 |  |
| Method cache dunder hits | 990,044,599 |  |
| Method cache dunder misses | 1 |  |


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
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 197,999,940 |  |
| Uops executed | 9,251,989,500 | 46 |
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
| <= 2 | 48,000,000 | 24.2% |
| <= 4 | 0 | 0.0% |
| <= 8 | 54,000,000 | 27.3% |
| <= 16 | 60 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 95,999,880 | 48.5% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 2,159,997,840 | 23.3% | 23.3% |
| LOAD_FAST | 1,439,997,600 | 15.6% | 38.9% |
| _GUARD_GLOBALS_VERSION | 497,999,820 | 5.4% | 44.3% |
| _LOAD_GLOBAL_BUILTINS | 407,999,820 | 4.4% | 48.7% |
| _GUARD_BUILTINS_VERSION | 407,999,820 | 4.4% | 53.1% |
| STORE_FAST | 311,999,580 | 3.4% | 56.5% |
| _POP_JUMP_IF_TRUE | 251,999,640 | 2.7% | 59.2% |
| _GUARD_TYPE_VERSION | 203,999,520 | 2.2% | 61.4% |
| _LOAD_ATTR_METHOD_WITH_VALUES | 197,999,640 | 2.1% | 63.6% |
| _GUARD_KEYS_VERSION | 197,999,640 | 2.1% | 65.7% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 197,999,640 | 2.1% | 67.8% |
| _SAVE_CURRENT_IP | 191,999,760 | 2.1% | 69.9% |
| _PUSH_FRAME | 191,999,760 | 2.1% | 72.0% |
| _INIT_CALL_PY_EXACT_ARGS | 191,999,760 | 2.1% | 74.1% |
| _CHECK_STACK_SPACE | 191,999,760 | 2.1% | 76.1% |
| _CHECK_PEP_523 | 191,999,760 | 2.1% | 78.2% |
| _CHECK_FUNCTION_EXACT_ARGS | 191,999,760 | 2.1% | 80.3% |
| RESUME_CHECK | 191,999,760 | 2.1% | 82.4% |
| CALL_BUILTIN_FAST | 185,999,940 | 2.0% | 84.4% |
| LOAD_CONST | 185,999,880 | 2.0% | 86.4% |
| _ITER_CHECK_TUPLE | 156,000,000 | 1.7% | 88.1% |
| _EXIT_TRACE | 149,999,880 | 1.6% | 89.7% |
| _POP_JUMP_IF_FALSE | 126,000,000 | 1.4% | 91.1% |
| _IS_ITER_EXHAUSTED_TUPLE | 108,000,000 | 1.2% | 92.2% |
| TO_BOOL_BOOL | 101,999,760 | 1.1% | 93.3% |
| CONTAINS_OP | 95,999,880 | 1.0% | 94.4% |
| _LOAD_GLOBAL_MODULE | 90,000,000 | 1.0% | 95.3% |
| CALL_TYPE_1 | 90,000,000 | 1.0% | 96.3% |
| _ITER_NEXT_TUPLE | 72,000,000 | 0.8% | 97.1% |
| POP_TOP | 59,999,880 | 0.6% | 97.7% |
| _ITER_CHECK_LIST | 36,000,000 | 0.4% | 98.1% |
| _IS_ITER_EXHAUSTED_LIST | 36,000,000 | 0.4% | 98.5% |
| LOAD_ATTR | 36,000,000 | 0.4% | 98.9% |
| IS_OP | 36,000,000 | 0.4% | 99.3% |
| _ITER_NEXT_LIST | 18,000,000 | 0.2% | 99.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 18,000,000 | 0.2% | 99.7% |
| CALL_BUILTIN_O | 11,999,760 | 0.1% | 99.8% |
| _LOAD_ATTR_INSTANCE_VALUE | 5,999,880 | 0.1% | 99.9% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 5,999,880 | 0.1% | 99.9% |
| PUSH_NULL | 5,999,880 | 0.1% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|


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
Stats gathered on: 2023-10-04
