
# Pystats results

- benchmark: deepcopy
- fork: python
- ref: eb3c94ea669561a0dfacaca715d4b2723bb2c6f4
- commit hash: eb3c94e
- commit date: 2023-11-17T20:58:13-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 704,802,320 | 20.7% | 20.7% |  |
| STORE_FAST | 333,807,740 | 9.8% | 30.5% |  |
| LOAD_FAST_LOAD_FAST | 293,583,040 | 8.6% | 39.1% |  |
| LOAD_GLOBAL_BUILTIN | 173,240,020 | 5.1% | 44.2% |  |
| POP_JUMP_IF_FALSE | 147,046,400 | 4.3% | 48.5% |  |
| RESUME_CHECK | 139,059,280 | 4.1% | 52.6% | 0.0% |
| CALL_BUILTIN_O | 132,341,320 | 3.9% | 56.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 129,187,560 | 3.8% | 60.2% |  |
| RETURN_VALUE | 123,003,460 | 3.6% | 63.9% |  |
| IS_OP | 120,995,840 | 3.6% | 67.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 115,752,840 | 3.4% | 70.8% |  |
| PUSH_NULL | 90,157,500 | 2.6% | 73.4% |  |
| CALL_PY_WITH_DEFAULTS | 75,564,840 | 2.2% | 75.7% | 8.4% |
| LOAD_GLOBAL_MODULE | 70,412,140 | 2.1% | 77.7% |  |
| POP_JUMP_IF_NONE | 68,935,700 | 2.0% | 79.8% |  |
| POP_JUMP_IF_NOT_NONE | 68,239,360 | 2.0% | 81.8% |  |
| JUMP_FORWARD | 58,941,460 | 1.7% | 83.5% |  |
| POP_TOP | 58,695,980 | 1.7% | 85.2% |  |
| CALL_PY_EXACT_ARGS | 54,012,040 | 1.6% | 86.8% | 10.4% |
| CALL_TYPE_1 | 51,527,620 | 1.5% | 88.3% |  |
| ENTER_EXECUTOR | 44,417,280 | 1.3% | 89.6% |  |
| STORE_SUBSCR_DICT | 33,504,960 | 1.0% | 90.6% |  |
| LOAD_CONST | 31,951,520 | 0.9% | 91.5% |  |
| TO_BOOL_BOOL | 20,029,180 | 0.6% | 92.1% |  |
| FOR_ITER | 17,741,480 | 0.5% | 92.6% |  |
| LOAD_DEREF | 16,794,400 | 0.5% | 93.1% |  |
| CALL_BUILTIN_FAST | 16,179,000 | 0.5% | 93.6% |  |
| RETURN_CONST | 15,442,160 | 0.5% | 94.1% |  |
| STORE_FAST_STORE_FAST | 12,492,800 | 0.4% | 94.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,492,700 | 0.4% | 94.8% |  |
| JUMP_BACKWARD | 12,333,040 | 0.4% | 95.2% |  |
| LOAD_ATTR | 11,269,600 | 0.3% | 95.5% |  |
| NOP | 10,363,140 | 0.3% | 95.8% |  |
| BINARY_SUBSCR_DICT | 10,362,780 | 0.3% | 96.1% |  |
| BUILD_LIST | 10,199,620 | 0.3% | 96.4% |  |
| BUILD_MAP | 8,642,640 | 0.3% | 96.6% |  |
| GET_ITER | 8,500,100 | 0.2% | 96.9% |  |
| CALL_FUNCTION_EX | 7,086,560 | 0.2% | 97.1% |  |
| CALL | 6,478,900 | 0.2% | 97.3% |  |
| INTERPRETER_EXIT | 6,471,860 | 0.2% | 97.5% |  |
| MAKE_CELL | 6,471,760 | 0.2% | 97.7% |  |
| STORE_ATTR_INSTANCE_VALUE | 5,680,520 | 0.2% | 97.8% | 6.6% |
| CALL_LIST_APPEND | 5,570,500 | 0.2% | 98.0% |  |
| CHECK_EXC_MATCH | 4,792,320 | 0.1% | 98.1% |  |
| POP_EXCEPT | 4,792,320 | 0.1% | 98.3% |  |
| PUSH_EXC_INFO | 4,792,320 | 0.1% | 98.4% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,628,420 | 0.1% | 98.6% |  |
| LIST_EXTEND | 3,850,640 | 0.1% | 98.7% |  |
| CALL_INTRINSIC_1 | 3,850,480 | 0.1% | 98.8% |  |
| CALL_ISINSTANCE | 3,850,180 | 0.1% | 98.9% |  |
| TO_BOOL | 3,237,640 | 0.1% | 99.0% |  |
| COPY_FREE_VARS | 3,236,160 | 0.1% | 99.1% |  |
| BUILD_TUPLE | 3,236,080 | 0.1% | 99.2% |  |
| TO_BOOL_NONE | 3,235,800 | 0.1% | 99.3% |  |
| FOR_ITER_TUPLE | 3,195,860 | 0.1% | 99.4% |  |
| FOR_ITER_LIST | 3,113,480 | 0.1% | 99.5% |  |
| LOAD_ATTR_MODULE | 2,828,280 | 0.1% | 99.5% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,621,480 | 0.1% | 99.6% | 0.1% |
| LIST_APPEND | 2,334,720 | 0.1% | 99.7% |  |
| POP_JUMP_IF_TRUE | 2,007,060 | 0.1% | 99.7% |  |
| SWAP | 1,556,480 | 0.0% | 99.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 1,228,880 | 0.0% | 99.8% |  |
| BINARY_OP_ADD_FLOAT | 1,228,760 | 0.0% | 99.9% | 0.0% |
| STORE_FAST_LOAD_FAST | 778,680 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 778,240 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 614,720 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 614,560 | 0.0% | 99.9% |  |
| RETURN_GENERATOR | 614,400 | 0.0% | 100.0% |  |
| YIELD_VALUE | 614,400 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 163,820 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 145,680 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 61,980 | 0.0% | 100.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 61,680 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 61,680 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 3,100 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 680 | 0.0% | 100.0% |  |
| RESUME | 660 | 0.0% | 100.0% | 3.0% |
| BINARY_OP | 440 | 0.0% | 100.0% |  |
| STORE_NAME | 400 | 0.0% | 100.0% |  |
| STORE_ATTR | 300 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 200 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 200 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 160 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% | 100.0% | 33.3% |
| EXIT_INIT_CHECK | 80 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 80 | 0.0% | 100.0% |  |
| LOAD_NAME | 80 | 0.0% | 100.0% |  |
| STORE_DEREF | 80 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 160,521,760 | 4.7% | 4.7% |
| STORE_FAST LOAD_FAST | 142,131,940 | 4.2% | 8.9% |
| LOAD_FAST RETURN_VALUE | 119,767,300 | 3.5% | 12.4% |
| LOAD_FAST_LOAD_FAST IS_OP | 117,760,000 | 3.5% | 15.9% |
| IS_OP POP_JUMP_IF_FALSE | 115,752,960 | 3.4% | 19.2% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 115,752,840 | 3.4% | 22.6% |
| LOAD_FAST CALL_BUILTIN_O | 92,036,400 | 2.7% | 25.3% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 75,445,040 | 2.2% | 27.6% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 73,790,420 | 2.2% | 29.7% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 71,599,080 | 2.1% | 31.8% |
| CALL_BUILTIN_O STORE_FAST | 71,475,100 | 2.1% | 33.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 70,983,680 | 2.1% | 36.0% |
| LOAD_FAST POP_JUMP_IF_NONE | 68,935,700 | 2.0% | 38.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 68,853,520 | 2.0% | 40.0% |
| LOAD_FAST PUSH_NULL | 68,363,360 | 2.0% | 42.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 68,239,360 | 2.0% | 44.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 68,239,240 | 2.0% | 46.1% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 64,225,280 | 1.9% | 47.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 64,225,220 | 1.9% | 49.8% |
| LOAD_FAST_LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 64,225,160 | 1.9% | 51.7% |
| POP_JUMP_IF_NONE LOAD_FAST | 62,464,000 | 1.8% | 53.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 60,333,920 | 1.8% | 55.3% |
| RETURN_VALUE STORE_FAST | 59,392,080 | 1.7% | 57.1% |
| STORE_FAST JUMP_FORWARD | 55,541,760 | 1.6% | 58.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 54,599,420 | 1.6% | 60.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 53,291,620 | 1.6% | 61.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 52,757,800 | 1.5% | 63.4% |
| CALL_TYPE_1 STORE_FAST | 51,527,620 | 1.5% | 64.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 51,527,560 | 1.5% | 66.4% |
| LOAD_FAST CALL_TYPE_1 | 51,527,560 | 1.5% | 67.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_NO_DICT | 51,527,560 | 1.5% | 69.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 50,670,120 | 1.5% | 70.9% |
| JUMP_FORWARD LOAD_FAST_LOAD_FAST | 48,291,840 | 1.4% | 72.4% |
| RESUME_CHECK LOAD_FAST | 45,956,960 | 1.3% | 73.7% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 39,852,280 | 1.2% | 74.9% |
| POP_TOP ENTER_EXECUTOR | 37,682,180 | 1.1% | 76.0% |
| CALL_BUILTIN_O POP_TOP | 37,068,760 | 1.1% | 77.1% |
| RETURN_VALUE CALL_BUILTIN_O | 37,068,720 | 1.1% | 78.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 30,512,960 | 0.9% | 79.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 21,462,520 | 0.6% | 79.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 20,029,180 | 0.6% | 80.3% |
| POP_TOP LOAD_FAST | 14,376,960 | 0.4% | 80.7% |
| PUSH_NULL LOAD_FAST | 13,723,520 | 0.4% | 81.1% |
| CALL_BUILTIN_O STORE_SUBSCR_DICT | 13,434,480 | 0.4% | 81.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 12,820,380 | 0.4% | 81.9% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 12,492,700 | 0.4% | 82.2% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 12,492,600 | 0.4% | 82.6% |
| JUMP_BACKWARD FOR_ITER | 12,329,200 | 0.4% | 83.0% |
| RETURN_CONST POP_TOP | 12,206,080 | 0.4% | 83.3% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 10,485,760 | 0.3% | 83.6% |
| LOAD_FAST_LOAD_FAST PUSH_NULL | 10,485,760 | 0.3% | 83.9% |
| STORE_FAST_STORE_FAST LOAD_FAST | 10,485,760 | 0.3% | 84.2% |
| STORE_SUBSCR_DICT JUMP_BACKWARD | 10,485,700 | 0.3% | 84.5% |
| RETURN_VALUE STORE_SUBSCR_DICT | 10,485,640 | 0.3% | 84.9% |
| NOP LOAD_FAST | 10,362,880 | 0.3% | 85.2% |
| CALL_BUILTIN_O BINARY_SUBSCR_DICT | 10,362,680 | 0.3% | 85.5% |
| LOAD_FAST LOAD_CONST | 9,707,540 | 0.3% | 85.7% |
| CALL_BUILTIN_FAST STORE_FAST | 9,707,400 | 0.3% | 86.0% |
| LOAD_CONST CALL_BUILTIN_FAST | 9,707,280 | 0.3% | 86.3% |
| LOAD_FAST TO_BOOL_BOOL | 9,707,280 | 0.3% | 86.6% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 9,584,720 | 0.3% | 86.9% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 9,584,640 | 0.3% | 87.2% |
| RESUME_CHECK NOP | 9,584,580 | 0.3% | 87.4% |
| LOAD_FAST STORE_SUBSCR_DICT | 9,584,520 | 0.3% | 87.7% |
| STORE_SUBSCR_DICT LOAD_GLOBAL_MODULE | 9,584,520 | 0.3% | 88.0% |
| STORE_SUBSCR_DICT LOAD_FAST | 9,420,660 | 0.3% | 88.3% |
| BUILD_MAP STORE_FAST | 8,642,560 | 0.3% | 88.5% |
| LOAD_FAST LOAD_ATTR | 8,028,460 | 0.2% | 88.8% |
| JUMP_FORWARD LOAD_GLOBAL_BUILTIN | 8,027,940 | 0.2% | 89.0% |
| LOAD_CONST LOAD_FAST | 7,864,480 | 0.2% | 89.2% |
| BUILD_LIST LOAD_FAST | 7,864,320 | 0.2% | 89.5% |
| LOAD_FAST LOAD_DEREF | 7,086,080 | 0.2% | 89.7% |
| LOAD_CONST LOAD_CONST | 6,471,920 | 0.2% | 89.9% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 6,471,520 | 0.2% | 90.1% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_BUILTIN | 6,184,760 | 0.2% | 90.2% |
| RESUME_CHECK LOAD_DEREF | 5,857,400 | 0.2% | 90.4% |
| LOAD_DEREF LOAD_CONST | 5,857,280 | 0.2% | 90.6% |
| CALL_LIST_APPEND RETURN_CONST | 5,570,500 | 0.2% | 90.7% |
| LOAD_FAST CALL_LIST_APPEND | 5,570,440 | 0.2% | 90.9% |
| BINARY_SUBSCR_DICT LOAD_ATTR_METHOD_NO_DICT | 5,570,440 | 0.2% | 91.1% |
| GET_ITER FOR_ITER | 5,406,900 | 0.2% | 91.2% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 5,242,960 | 0.2% | 91.4% |
| FOR_ITER LOAD_FAST | 5,242,880 | 0.2% | 91.5% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 4,792,320 | 0.1% | 91.7% |
| POP_JUMP_IF_FALSE POP_TOP | 4,792,320 | 0.1% | 91.8% |
| BINARY_SUBSCR_DICT PUSH_EXC_INFO | 4,792,220 | 0.1% | 92.0% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 4,792,220 | 0.1% | 92.1% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 4,792,120 | 0.1% | 92.2% |
| LOAD_FAST BUILD_LIST | 4,628,800 | 0.1% | 92.4% |
| CALL_METHOD_DESCRIPTOR_NOARGS GET_ITER | 4,628,420 | 0.1% | 92.5% |
| RESUME_CHECK BUILD_MAP | 4,628,420 | 0.1% | 92.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 4,628,360 | 0.1% | 92.8% |
| POP_EXCEPT RETURN_CONST | 4,014,080 | 0.1% | 92.9% |
| POP_JUMP_IF_NOT_NONE BUILD_MAP | 4,014,080 | 0.1% | 93.0% |
| STORE_SUBSCR_DICT POP_EXCEPT | 4,014,020 | 0.1% | 93.1% |
| STORE_FAST ENTER_EXECUTOR | 4,012,720 | 0.1% | 93.3% |
| LOAD_DEREF PUSH_NULL | 3,850,800 | 0.1% | 93.4% |
| LOAD_ATTR PUSH_NULL | 3,850,540 | 0.1% | 93.5% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 3,850,480 | 0.1% | 93.6% |
| LIST_EXTEND CALL_INTRINSIC_1 | 3,850,480 | 0.1% | 93.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,235,860 | 50.0% |
| COPY_FREE_VARS | 2,621,520 | 40.5% |
| POP_TOP | 614,400 | 9.5% |
| RESUME | 80 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 100 | 50.0% |
| CALL_BUILTIN_O | 100 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 100 | 50.0% |
| BINARY_SUBSCR_DICT | 100 | 50.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,792,220 | 100.0% |
| LOAD_GLOBAL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,792,320 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,628,420 | 54.5% |
| LOAD_FAST | 2,949,120 | 34.7% |
| CALL | 778,400 | 9.2% |
| LOAD_CONST | 82,180 | 1.0% |
| CALL_BUILTIN_CLASS | 61,980 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 5,406,900 | 63.6% |
| FOR_ITER_LIST | 1,556,440 | 18.3% |
| LOAD_FAST_AND_CLEAR | 778,240 | 9.2% |
| CALL_PY_EXACT_ARGS | 614,360 | 7.2% |
| FOR_ITER_TUPLE | 82,140 | 1.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,236,000 | 50.0% |
| RETURN_VALUE | 2,621,460 | 40.5% |
| YIELD_VALUE | 614,400 | 9.5% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 614,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 614,560 | 100.0% |
| STORE_NAME | 160 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 9,584,580 | 92.5% |
| STORE_FAST | 778,240 | 7.5% |
| POP_TOP | 240 | 0.0% |
| RESUME | 60 | 0.0% |
| JUMP_FORWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,362,880 | 100.0% |
| LOAD_DEREF | 240 | 0.0% |
| LOAD_FAST_LOAD_FAST | 20 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 4,014,020 | 83.8% |
| POP_TOP | 778,240 | 16.2% |
| STORE_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,014,080 | 83.8% |
| JUMP_FORWARD | 778,240 | 16.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 37,068,760 | 63.2% |
| RETURN_CONST | 12,206,080 | 20.8% |
| POP_JUMP_IF_FALSE | 4,792,320 | 8.2% |
| CALL | 3,236,180 | 5.5% |
| CACHE | 614,400 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 37,682,180 | 64.2% |
| LOAD_FAST | 14,376,960 | 24.5% |
| RETURN_CONST | 2,621,500 | 4.5% |
| JUMP_FORWARD | 2,621,440 | 4.5% |
| POP_EXCEPT | 778,240 | 1.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 4,792,220 | 100.0% |
| BINARY_SUBSCR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,792,120 | 100.0% |
| LOAD_GLOBAL | 200 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 68,363,360 | 75.8% |
| LOAD_FAST_LOAD_FAST | 10,485,760 | 11.6% |
| LOAD_DEREF | 3,850,800 | 4.3% |
| LOAD_ATTR | 3,850,540 | 4.3% |
| LOAD_ATTR_MODULE | 2,828,280 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,599,080 | 79.4% |
| LOAD_FAST | 13,723,520 | 15.2% |
| LOAD_CONST | 3,235,840 | 3.6% |
| CALL | 1,599,020 | 1.8% |
| CALL_ALLOC_AND_ENTER_INIT | 40 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 614,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 614,400 | 100.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 119,767,300 | 97.4% |
| BUILD_TUPLE | 2,621,440 | 2.1% |
| CALL_FUNCTION_EX | 614,400 | 0.5% |
| RETURN_VALUE | 240 | 0.0% |
| EXIT_INIT_CHECK | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 59,392,080 | 48.3% |
| CALL_BUILTIN_O | 37,068,720 | 30.1% |
| LOAD_FAST_LOAD_FAST | 10,485,760 | 8.5% |
| STORE_SUBSCR_DICT | 10,485,640 | 8.5% |
| INTERPRETER_EXIT | 2,621,460 | 2.1% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 200 | 29.4% |
| CALL_BUILTIN_O | 200 | 29.4% |
| RETURN_VALUE | 120 | 17.6% |
| LOAD_FAST | 120 | 17.6% |
| LOAD_CONST | 40 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 320 | 47.1% |
| LOAD_FAST | 140 | 20.6% |
| POP_EXCEPT | 60 | 8.8% |
| JUMP_BACKWARD | 60 | 8.8% |
| LOAD_GLOBAL | 60 | 8.8% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,236,160 | 100.0% |
| TO_BOOL | 1,180 | 0.0% |
| CALL | 160 | 0.0% |
| CALL_BUILTIN_FAST | 80 | 0.0% |
| CALL_ISINSTANCE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,236,140 | 100.0% |
| TO_BOOL | 1,180 | 0.0% |
| TO_BOOL_BOOL | 260 | 0.0% |
| TO_BOOL_NONE | 40 | 0.0% |
| POP_JUMP_IF_TRUE | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 36.4% |
| LOAD_FAST | 160 | 36.4% |
| BINARY_OP | 80 | 18.2% |
| BINARY_OP_SUBTRACT_FLOAT | 40 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 160 | 36.4% |
| BINARY_OP | 80 | 18.2% |
| BINARY_OP_SUBTRACT_FLOAT | 80 | 18.2% |
| LOAD_CONST | 80 | 18.2% |
| BINARY_OP_ADD_FLOAT | 40 | 9.1% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 160 | 100.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,628,800 | 45.4% |
| LOAD_FAST_LOAD_FAST | 3,235,840 | 31.7% |
| RESUME_CHECK | 1,556,500 | 15.3% |
| SWAP | 778,240 | 7.6% |
| LOAD_CONST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,864,320 | 77.1% |
| STORE_FAST | 1,556,500 | 15.3% |
| SWAP | 778,240 | 7.6% |
| LOAD_CONST | 320 | 0.0% |
| LOAD_DEREF | 240 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,628,420 | 53.6% |
| POP_JUMP_IF_NOT_NONE | 4,014,080 | 46.4% |
| LOAD_CONST | 80 | 0.0% |
| RESUME | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,642,560 | 100.0% |
| LOAD_CONST | 80 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 2,621,440 | 81.0% |
| LOAD_FAST | 614,640 | 19.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,621,440 | 81.0% |
| LOAD_CONST | 614,560 | 19.0% |
| LOAD_FAST | 80 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,237,360 | 50.0% |
| PUSH_NULL | 1,599,020 | 24.7% |
| ENTER_EXECUTOR | 859,180 | 13.3% |
| LOAD_FAST_LOAD_FAST | 779,000 | 12.0% |
| CALL | 3,260 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 3,236,180 | 49.9% |
| STORE_FAST | 1,229,440 | 19.0% |
| LOAD_FAST | 1,228,960 | 19.0% |
| GET_ITER | 778,400 | 12.0% |
| CALL | 3,260 | 0.1% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 3,850,480 | 54.3% |
| LOAD_FAST | 3,236,080 | 45.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 3,235,920 | 45.7% |
| STORE_FAST | 2,621,440 | 37.0% |
| RESUME_CHECK | 614,500 | 8.7% |
| RETURN_VALUE | 614,400 | 8.7% |
| COPY_FREE_VARS | 240 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 3,850,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 3,850,480 | 100.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 2,621,520 | 81.0% |
| CALL_PY_EXACT_ARGS | 614,380 | 19.0% |
| CALL_FUNCTION_EX | 240 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,621,660 | 81.0% |
| RETURN_GENERATOR | 614,400 | 19.0% |
| RESUME | 100 | 0.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 37,682,180 | 84.8% |
| STORE_FAST | 4,012,720 | 9.0% |
| LIST_APPEND | 2,334,040 | 5.3% |
| FOR_ITER_TUPLE | 327,000 | 0.7% |
| FOR_ITER_RANGE | 61,100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 39,852,280 | 89.7% |
| FOR_ITER_TUPLE | 1,719,540 | 3.9% |
| FOR_ITER_LIST | 1,556,400 | 3.5% |
| CALL | 859,180 | 1.9% |
| STORE_ATTR_INSTANCE_VALUE | 347,780 | 0.8% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 12,329,200 | 69.5% |
| GET_ITER | 5,406,900 | 30.5% |
| FOR_ITER | 5,320 | 0.0% |
| SWAP | 40 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 12,492,600 | 70.4% |
| LOAD_FAST | 5,242,880 | 29.6% |
| FOR_ITER | 5,320 | 0.0% |
| STORE_FAST | 200 | 0.0% |
| UNPACK_SEQUENCE | 200 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 117,760,000 | 97.3% |
| LOAD_CONST | 3,235,840 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 115,752,960 | 95.7% |
| STORE_FAST | 3,235,840 | 2.7% |
| POP_JUMP_IF_TRUE | 2,007,040 | 1.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 10,485,700 | 85.0% |
| POP_JUMP_IF_TRUE | 1,843,200 | 14.9% |
| STORE_FAST | 1,360 | 0.0% |
| POP_TOP | 1,020 | 0.0% |
| LIST_APPEND | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 12,329,200 | 100.0% |
| FOR_ITER_RANGE | 1,500 | 0.0% |
| FOR_ITER_TUPLE | 1,500 | 0.0% |
| FOR_ITER_LIST | 600 | 0.0% |
| ENTER_EXECUTOR | 240 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 55,541,760 | 94.2% |
| POP_TOP | 2,621,440 | 4.4% |
| POP_EXCEPT | 778,240 | 1.3% |
| POP_JUMP_IF_TRUE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 48,291,840 | 81.9% |
| LOAD_GLOBAL_BUILTIN | 8,027,940 | 13.6% |
| LOAD_FAST | 2,621,440 | 4.4% |
| LOAD_GLOBAL | 220 | 0.0% |
| NOP | 20 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,334,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,334,040 | 100.0% |
| JUMP_BACKWARD | 680 | 0.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,850,240 | 100.0% |
| LOAD_DEREF | 240 | 0.0% |
| LOAD_CONST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 3,850,480 | 100.0% |
| LOAD_CONST | 160 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,028,460 | 71.2% |
| LOAD_GLOBAL_MODULE | 3,236,160 | 28.7% |
| LOAD_ATTR | 4,420 | 0.0% |
| LOAD_GLOBAL | 400 | 0.0% |
| BINARY_SUBSCR_DICT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,850,540 | 34.2% |
| LOAD_ATTR_METHOD_NO_DICT | 3,236,040 | 28.7% |
| BUILD_TUPLE | 2,621,440 | 23.3% |
| STORE_FAST | 1,556,480 | 13.8% |
| LOAD_ATTR | 4,420 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,707,540 | 30.4% |
| LOAD_CONST | 6,471,920 | 20.3% |
| LOAD_DEREF | 5,857,280 | 18.3% |
| PUSH_NULL | 3,235,840 | 10.1% |
| RESUME_CHECK | 2,621,560 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 9,707,280 | 30.4% |
| LOAD_FAST | 7,864,480 | 24.6% |
| LOAD_CONST | 6,471,920 | 20.3% |
| IS_OP | 3,235,840 | 10.1% |
| CALL_BUILTIN_O | 3,235,760 | 10.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,086,080 | 42.2% |
| RESUME_CHECK | 5,857,400 | 34.9% |
| POP_JUMP_IF_FALSE | 3,235,840 | 19.3% |
| STORE_FAST | 614,400 | 3.7% |
| NOP | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,857,280 | 34.9% |
| PUSH_NULL | 3,850,800 | 22.9% |
| CALL_PY_WITH_DEFAULTS | 3,850,120 | 22.9% |
| LOAD_GLOBAL_BUILTIN | 3,235,760 | 19.3% |
| LIST_EXTEND | 240 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160,521,760 | 22.8% |
| STORE_FAST | 142,131,940 | 20.2% |
| POP_JUMP_IF_FALSE | 70,983,680 | 10.1% |
| POP_JUMP_IF_NOT_NONE | 64,225,280 | 9.1% |
| POP_JUMP_IF_NONE | 62,464,000 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 119,767,300 | 17.0% |
| CALL_BUILTIN_O | 92,036,400 | 13.1% |
| POP_JUMP_IF_NONE | 68,935,700 | 9.8% |
| LOAD_ATTR_METHOD_NO_DICT | 68,853,520 | 9.8% |
| PUSH_NULL | 68,363,360 | 9.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 778,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 778,240 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 73,790,420 | 25.1% |
| PUSH_NULL | 71,599,080 | 24.4% |
| LOAD_ATTR_METHOD_NO_DICT | 64,225,220 | 21.9% |
| JUMP_FORWARD | 48,291,840 | 16.4% |
| LOAD_GLOBAL_MODULE | 12,820,380 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 117,760,000 | 40.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 64,225,160 | 21.9% |
| CALL_PY_EXACT_ARGS | 50,670,120 | 17.3% |
| CALL_PY_WITH_DEFAULTS | 30,512,960 | 10.4% |
| PUSH_NULL | 10,485,760 | 3.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 700 | 22.6% |
| LOAD_FAST | 600 | 19.4% |
| POP_JUMP_IF_FALSE | 340 | 11.0% |
| JUMP_FORWARD | 220 | 7.1% |
| PUSH_EXC_INFO | 200 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,020 | 32.9% |
| LOAD_FAST | 740 | 23.9% |
| LOAD_GLOBAL_MODULE | 520 | 16.8% |
| LOAD_ATTR | 400 | 12.9% |
| LOAD_FAST_LOAD_FAST | 140 | 4.5% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 3,235,920 | 50.0% |
| MAKE_CELL | 3,235,840 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,235,860 | 50.0% |
| MAKE_CELL | 3,235,840 | 50.0% |
| RESUME | 60 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 115,752,960 | 78.7% |
| TO_BOOL_BOOL | 20,029,180 | 13.6% |
| CHECK_EXC_MATCH | 4,792,320 | 3.3% |
| TO_BOOL | 3,236,140 | 2.2% |
| TO_BOOL_NONE | 3,235,800 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 70,983,680 | 48.3% |
| LOAD_GLOBAL_BUILTIN | 54,599,420 | 37.1% |
| LOAD_FAST_LOAD_FAST | 9,584,640 | 6.5% |
| POP_TOP | 4,792,320 | 3.3% |
| LOAD_DEREF | 3,235,840 | 2.2% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 68,935,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,464,000 | 90.6% |
| LOAD_GLOBAL_BUILTIN | 3,235,760 | 4.7% |
| LOAD_GLOBAL_MODULE | 3,235,760 | 4.7% |
| LOAD_GLOBAL | 160 | 0.0% |
| BUILD_LIST | 20 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 68,239,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,225,280 | 94.1% |
| BUILD_MAP | 4,014,080 | 5.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 2,007,040 | 100.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,843,200 | 91.8% |
| LOAD_GLOBAL_BUILTIN | 163,800 | 8.2% |
| LOAD_GLOBAL | 40 | 0.0% |
| JUMP_FORWARD | 20 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 5,570,500 | 36.1% |
| POP_EXCEPT | 4,014,080 | 26.0% |
| STORE_ATTR_INSTANCE_VALUE | 2,621,560 | 17.0% |
| POP_TOP | 2,621,500 | 17.0% |
| FOR_ITER_TUPLE | 614,400 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 12,206,080 | 79.0% |
| INTERPRETER_EXIT | 3,236,000 | 21.0% |
| EXIT_INIT_CHECK | 80 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 614,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 614,400 | 100.0% |
| LOAD_CONST | 80 | 0.0% |
| STORE_NAME | 80 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 220 | 73.3% |
| LOAD_FAST | 80 | 26.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 140 | 46.7% |
| LOAD_FAST_LOAD_FAST | 40 | 13.3% |
| LOAD_GLOBAL | 40 | 13.3% |
| RETURN_CONST | 40 | 13.3% |
| LOAD_FAST | 20 | 6.7% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 115,752,840 | 34.7% |
| CALL_BUILTIN_O | 71,475,100 | 21.4% |
| RETURN_VALUE | 59,392,080 | 17.8% |
| CALL_TYPE_1 | 51,527,620 | 15.4% |
| CALL_BUILTIN_FAST | 9,707,400 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 142,131,940 | 42.6% |
| LOAD_FAST_LOAD_FAST | 73,790,420 | 22.1% |
| JUMP_FORWARD | 55,541,760 | 16.6% |
| LOAD_GLOBAL_MODULE | 52,757,800 | 15.8% |
| ENTER_EXECUTOR | 4,012,720 | 1.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 778,640 | 100.0% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 778,680 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 12,492,700 | 100.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,485,760 | 83.9% |
| LOAD_FAST_LOAD_FAST | 2,007,040 | 16.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 778,240 | 50.0% |
| LOAD_FAST_AND_CLEAR | 778,240 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 778,240 | 50.0% |
| FOR_ITER_TUPLE | 778,200 | 50.0% |
| FOR_ITER | 40 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 100 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 100 | 50.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 614,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 614,400 | 100.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 200 | 30.3% |
| CALL_PY_WITH_DEFAULTS | 120 | 18.2% |
| COPY_FREE_VARS | 100 | 15.2% |
| CACHE | 80 | 12.1% |
| CALL_FUNCTION_EX | 60 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 27.3% |
| LOAD_DEREF | 120 | 18.2% |
| NOP | 60 | 9.1% |
| BUILD_LIST | 60 | 9.1% |
| BUILD_MAP | 60 | 9.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 1,228,720 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,228,760 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,228,800 | 100.0% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 1,228,720 | 100.0% |
| STORE_FAST | 120 | 0.0% |
| BINARY_OP | 40 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,362,680 | 100.0% |
| BINARY_SUBSCR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 5,570,440 | 53.8% |
| PUSH_EXC_INFO | 4,792,220 | 46.2% |
| LOAD_ATTR | 120 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 40 | 33.3% |
| CALL | 40 | 33.3% |
| LOAD_CONST | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80 | 66.7% |
| STORE_FAST | 40 | 33.3% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 61,760 | 99.6% |
| LOAD_FAST | 120 | 0.2% |
| CALL | 100 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 61,980 | 100.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 9,707,280 | 60.0% |
| LOAD_FAST | 3,235,760 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 3,235,760 | 20.0% |
| CALL | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,707,400 | 60.0% |
| TO_BOOL_BOOL | 6,471,520 | 40.0% |
| TO_BOOL | 80 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,036,400 | 69.5% |
| RETURN_VALUE | 37,068,720 | 28.0% |
| LOAD_CONST | 3,235,760 | 2.4% |
| CALL | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 71,475,100 | 54.0% |
| POP_TOP | 37,068,760 | 28.0% |
| STORE_SUBSCR_DICT | 13,434,480 | 10.2% |
| BINARY_SUBSCR_DICT | 10,362,680 | 7.8% |
| STORE_SUBSCR | 200 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,850,120 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,850,120 | 100.0% |
| TO_BOOL | 60 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,570,440 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,570,500 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 64,225,160 | 55.5% |
| LOAD_FAST | 51,527,560 | 44.5% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 115,752,840 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,628,360 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,628,420 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 50,670,120 | 93.8% |
| LOAD_FAST | 2,621,400 | 4.9% |
| GET_ITER | 614,360 | 1.1% |
| CALL_PY_WITH_DEFAULTS | 106,040 | 0.2% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 53,291,620 | 98.7% |
| COPY_FREE_VARS | 614,380 | 1.1% |
| CALL_PY_WITH_DEFAULTS | 106,020 | 0.2% |
| RESUME | 20 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 39,852,280 | 52.7% |
| LOAD_FAST_LOAD_FAST | 30,512,960 | 40.4% |
| LOAD_DEREF | 3,850,120 | 5.1% |
| LOAD_FAST | 1,229,440 | 1.6% |
| CALL_PY_EXACT_ARGS | 106,020 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 75,445,040 | 99.8% |
| CALL_PY_EXACT_ARGS | 106,040 | 0.1% |
| CALL_PY_WITH_DEFAULTS | 13,640 | 0.0% |
| RESUME | 120 | 0.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,527,560 | 100.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 51,527,620 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,556,440 | 50.0% |
| ENTER_EXECUTOR | 1,556,400 | 50.0% |
| JUMP_BACKWARD | 600 | 0.0% |
| FOR_ITER | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,557,000 | 50.0% |
| LOAD_FAST | 1,556,480 | 50.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 82,100 | 56.4% |
| GET_ITER | 61,980 | 42.5% |
| JUMP_BACKWARD | 1,500 | 1.0% |
| FOR_ITER | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 63,520 | 43.6% |
| ENTER_EXECUTOR | 61,100 | 41.9% |
| LOAD_CONST | 20,480 | 14.1% |
| JUMP_BACKWARD | 340 | 0.2% |
| LOAD_FAST | 80 | 0.1% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,719,540 | 53.8% |
| SWAP | 778,200 | 24.4% |
| LOAD_FAST | 614,380 | 19.2% |
| GET_ITER | 82,140 | 2.6% |
| JUMP_BACKWARD | 1,500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,475,140 | 46.2% |
| STORE_FAST_LOAD_FAST | 778,640 | 24.4% |
| RETURN_CONST | 614,400 | 19.2% |
| ENTER_EXECUTOR | 327,000 | 10.2% |
| JUMP_BACKWARD | 680 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 61,660 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 61,680 | 100.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 68,853,520 | 53.3% |
| LOAD_GLOBAL_MODULE | 51,527,560 | 39.9% |
| BINARY_SUBSCR_DICT | 5,570,440 | 4.3% |
| LOAD_ATTR | 3,236,040 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 64,225,220 | 49.7% |
| LOAD_FAST | 60,333,920 | 46.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 4,628,360 | 3.6% |
| CALL | 60 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,827,980 | 100.0% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,828,280 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 68,239,240 | 39.4% |
| POP_JUMP_IF_FALSE | 54,599,420 | 31.5% |
| LOAD_FAST | 21,462,520 | 12.4% |
| JUMP_FORWARD | 8,027,940 | 4.6% |
| LOAD_FAST_LOAD_FAST | 6,184,760 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160,521,760 | 92.7% |
| CHECK_EXC_MATCH | 4,792,220 | 2.8% |
| CALL_ISINSTANCE | 3,850,120 | 2.2% |
| CALL_BUILTIN_FAST | 3,235,760 | 1.9% |
| LOAD_FAST_LOAD_FAST | 778,200 | 0.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 52,757,800 | 74.9% |
| STORE_SUBSCR_DICT | 9,584,520 | 13.6% |
| POP_JUMP_IF_FALSE | 3,235,760 | 4.6% |
| POP_JUMP_IF_NONE | 3,235,760 | 4.6% |
| LOAD_FAST | 1,228,720 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 51,527,560 | 73.2% |
| LOAD_FAST_LOAD_FAST | 12,820,380 | 18.2% |
| LOAD_ATTR | 3,236,160 | 4.6% |
| LOAD_ATTR_MODULE | 2,827,980 | 4.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 75,445,040 | 54.3% |
| CALL_PY_EXACT_ARGS | 53,291,620 | 38.3% |
| CACHE | 3,235,860 | 2.3% |
| MAKE_CELL | 3,235,860 | 2.3% |
| COPY_FREE_VARS | 2,621,660 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 68,239,240 | 49.1% |
| LOAD_FAST | 45,956,960 | 33.0% |
| NOP | 9,584,580 | 6.9% |
| LOAD_DEREF | 5,857,400 | 4.2% |
| BUILD_MAP | 4,628,420 | 3.3% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,242,960 | 92.3% |
| ENTER_EXECUTOR | 347,780 | 6.1% |
| LOAD_FAST_LOAD_FAST | 82,600 | 1.5% |
| STORE_ATTR_INSTANCE_VALUE | 7,040 | 0.1% |
| STORE_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,621,560 | 46.2% |
| LOAD_CONST | 2,621,500 | 46.1% |
| LOAD_GLOBAL_MODULE | 368,860 | 6.5% |
| LOAD_GLOBAL_BUILTIN | 61,400 | 1.1% |
| STORE_ATTR_INSTANCE_VALUE | 7,040 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 13,434,480 | 40.1% |
| RETURN_VALUE | 10,485,640 | 31.3% |
| LOAD_FAST | 9,584,520 | 28.6% |
| STORE_SUBSCR | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 10,485,700 | 31.3% |
| LOAD_GLOBAL_MODULE | 9,584,520 | 28.6% |
| LOAD_FAST | 9,420,660 | 28.1% |
| POP_EXCEPT | 4,014,020 | 12.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 61,660 | 100.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 61,680 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,707,280 | 48.5% |
| CALL_BUILTIN_FAST | 6,471,520 | 32.3% |
| CALL_ISINSTANCE | 3,850,120 | 19.2% |
| TO_BOOL | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20,029,180 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,235,760 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,235,800 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 12,492,600 | 100.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 12,492,700 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 163,800 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 163,820 | 100.0% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 80 | 100.0% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 80 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 75.0% |
| CALL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 160 | 40.0% |
| LOAD_CONST | 80 | 20.0% |
| SET_FUNCTION_ATTRIBUTE | 80 | 20.0% |
| LOAD_NAME | 80 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 60.0% |
| LOAD_FAST | 80 | 20.0% |
| RETURN_CONST | 80 | 20.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_DEREF | 60 | 100.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,400 | 100.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,420 | 100.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60 | 0.0% |


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
|     deferred | 280 | 0.0% |
|          hit | 2,457,580 | 100.0% |
|         miss | 60 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 75.0% |
| Failure | 40 | 25.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 40 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 0.0% |
|          hit | 10,362,780 | 100.0% |

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
|     deferred | 6,248,260 | 1.3% |
|          hit | 447,689,060 | 96.0% |
|         miss | 11,963,680 | 2.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 227,380 | 98.6% |
| Failure | 3,260 | 1.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 1,500 | 46.0% |
| meth descr varargs keywords | 1,180 | 36.2% |
| class no vectorcall | 580 | 17.8% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 17,735,920 | 73.3% |
|          hit | 6,455,020 | 26.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 4.3% |
| Failure | 5,320 | 95.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 4,280 | 80.5% |
| zip | 1,040 | 19.5% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 11,264,600 | 7.7% |
|          hit | 134,695,820 | 92.3% |
|         miss | 3,180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 680 | 13.6% |
| Failure | 4,320 | 86.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr descriptor | 2,020 | 46.8% |
| method | 1,960 | 45.4% |
| metaclass attribute | 340 | 7.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,560 | 0.0% |
|          hit | 243,652,160 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,540 | 100.0% |
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
|     deferred | 737,869,762,948,382,057,760 | 12,988,789,698,465,750.0% |
|          hit | 5,305,640 | 93.4% |
|         miss | 374,880 | 6.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 7,180 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 340 | 0.0% |
|          hit | 33,566,640 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,236,160 | 12.2% |
|          hit | 23,264,980 | 87.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 300 | 20.3% |
| Failure | 1,180 | 79.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 1,180 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 0.0% |
|          hit | 12,492,700 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 2,011,612,280 | 59.0% |
| Not specialized | 324,961,060 | 9.5% |
| Specialized hits | 1,059,001,640 | 31.1% |
| Specialized misses | 12,341,820 | 0.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| STORE_ATTR | 737,869,762,948,382,057,760 | 100.0% |
| FOR_ITER | 17,735,920 | 0.0% |
| LOAD_ATTR | 11,264,600 | 0.0% |
| CALL | 6,248,260 | 0.0% |
| TO_BOOL | 3,236,160 | 0.0% |
| LOAD_GLOBAL | 1,560 | 0.0% |
| STORE_SUBSCR | 340 | 0.0% |
| BINARY_OP | 280 | 0.0% |
| BINARY_SUBSCR | 100 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 6,343,760 | 51.4% |
| CALL_PY_EXACT_ARGS | 5,619,880 | 45.5% |
| STORE_ATTR_INSTANCE_VALUE | 374,880 | 3.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,180 | 0.0% |
| BINARY_OP_ADD_FLOAT | 60 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 40 | 0.0% |
| RESUME | 20 | 0.0% |
| RESUME_CHECK | 20 | 0.0% |
| CACHE | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 6,471,860 | 4.6% |
| Calls to Python functions inlined | 133,202,480 | 95.4% |
| Calls via PyEval_EvalFrame (total) | 6,471,860 | 4.6% |
| Calls via PyEval_EvalFrame (vector) | 5,243,060 | 3.8% |
| Calls via PyEval_EvalFrame (generator) | 1,228,800 | 0.9% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 5,242,980 | 3.8% |
| Calls via PyEval_EvalFrame (build class) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 3,850,720 | 2.8% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 20 | 0.0% |
| Frame objects created | 4,792,320 | 3.4% |
| Frames pushed | 117,613,400 | 84.2% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 52,949,280 | 24.2% |
| Frees to freelist | 52,988,980 |  |
| Allocations | 165,973,580 | 75.8% |
| Allocations to 512 bytes | 165,973,200 | 75.8% |
| Allocations to 4 kbytes | 380 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 168,267,531 |  |
| New values | 3,235,920 |  |
| Interpreter increfs | 1,684,520,160 | 82.7% |
| Interpreter decrefs | 1,921,767,000 | 85.9% |
| Increfs | 353,235,000 | 17.3% |
| Decrefs | 314,558,365 | 14.1% |
| Materialize dict (on request) | 3,548,920 | 109.7% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 312,920 | 9.7% |
| Method cache hits | 5,784,393 |  |
| Method cache misses | 427 |  |
| Method cache collisions | 1,064 |  |
| Method cache dunder hits | 36,664,751 |  |
| Method cache dunder misses | 969 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 40 | 360 | 14,920 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 6,720 |  |
| Traces created | 240 | 3.6% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 6,480 | 96.4% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 44,417,280 |  |
| Uops executed | 467,263,520 | 10.52 |

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
| <= 32 | 180 | 75.0% |
| <= 64 | 40 | 16.7% |
| <= 128 | 20 | 8.3% |


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
| <= 16 | 160 | 66.7% |
| <= 32 | 40 | 16.7% |
| <= 64 | 40 | 16.7% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 3,275,940 | 7.4% |
| <= 4 | 82,100 | 0.2% |
| <= 8 | 0 | 0.0% |
| <= 16 | 40,793,660 | 91.8% |
| <= 32 | 20,080 | 0.0% |
| <= 64 | 245,500 | 0.6% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 151,177,200 | 32.4% | 32.4% |  |
| PUSH_NULL | 76,223,220 | 16.3% | 48.7% |  |
| STORE_FAST | 41,324,820 | 8.8% | 57.5% |  |
| _EXIT_TRACE | 40,711,460 | 8.7% | 66.2% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 37,068,160 | 7.9% | 74.2% | 4.2% |
| _ITER_CHECK_LIST | 37,068,160 | 7.9% | 82.1% |  |
| _ITER_NEXT_LIST | 35,511,760 | 7.6% | 89.7% |  |
| _SET_IP | 4,870,280 | 1.0% | 90.7% |  |
| _CHECK_VALIDITY | 4,420,320 | 0.9% | 91.7% |  |
| _GUARD_NOT_EXHAUSTED_TUPLE | 3,868,860 | 0.8% | 92.5% | 44.4% |
| _ITER_CHECK_TUPLE | 3,868,860 | 0.8% | 93.3% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 3,745,840 | 0.8% | 94.1% | 2.2% |
| _ITER_CHECK_RANGE | 3,745,840 | 0.8% | 94.9% |  |
| _GUARD_GLOBALS_VERSION | 3,663,740 | 0.8% | 95.7% |  |
| _ITER_NEXT_RANGE | 3,663,740 | 0.8% | 96.5% |  |
| _LOAD_GLOBAL_MODULE | 3,643,660 | 0.8% | 97.3% |  |
| _CHECK_ATTR_MODULE | 3,643,660 | 0.8% | 98.1% |  |
| _LOAD_ATTR_MODULE | 3,643,660 | 0.8% | 98.8% |  |
| _ITER_NEXT_TUPLE | 2,149,320 | 0.5% | 99.3% |  |
| _GUARD_TYPE_VERSION | 838,780 | 0.2% | 99.5% |  |
| _GUARD_DORV_VALUES | 593,280 | 0.1% | 99.6% | 58.6% |
| LOAD_CONST | 511,080 | 0.1% | 99.7% |  |
| GET_ITER | 265,580 | 0.1% | 99.8% |  |
| STORE_SUBSCR_LIST_INT | 245,500 | 0.1% | 99.8% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 245,500 | 0.1% | 99.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 245,500 | 0.1% | 99.9% |  |
| _STORE_ATTR_INSTANCE_VALUE | 245,500 | 0.1% | 100.0% |  |
| CALL_BUILTIN_CLASS | 20,080 | 0.0% | 100.0% |  |
| _GUARD_BUILTINS_VERSION | 20,080 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_BUILTINS | 20,080 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 6,480 |
| CALL_PY_WITH_DEFAULTS | 140 |
| CALL | 100 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 60 |


</details>

---
Stats gathered on: 2023-11-19
