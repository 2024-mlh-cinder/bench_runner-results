
# Pystats results

- benchmark: deepcopy
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 528,600,360 | 20.7% | 20.7% |  |
| STORE_FAST | 250,353,480 | 9.8% | 30.5% |  |
| LOAD_FAST_LOAD_FAST | 220,185,840 | 8.6% | 39.1% |  |
| LOAD_GLOBAL_BUILTIN | 129,930,540 | 5.1% | 44.2% |  |
| POP_JUMP_IF_FALSE | 110,284,800 | 4.3% | 48.5% |  |
| RESUME_CHECK | 104,294,940 | 4.1% | 52.6% |  |
| CALL_BUILTIN_O | 99,256,320 | 3.9% | 56.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 96,890,880 | 3.8% | 60.3% |  |
| RETURN_VALUE | 92,252,600 | 3.6% | 63.9% |  |
| IS_OP | 90,746,880 | 3.6% | 67.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 86,814,720 | 3.4% | 70.9% |  |
| PUSH_NULL | 67,615,800 | 2.6% | 73.5% |  |
| CALL_PY_WITH_DEFAULTS | 56,674,260 | 2.2% | 75.7% | 8.4% |
| LOAD_GLOBAL_MODULE | 52,808,280 | 2.1% | 77.8% |  |
| POP_JUMP_IF_NONE | 51,701,760 | 2.0% | 79.8% |  |
| POP_JUMP_IF_NOT_NONE | 51,179,520 | 2.0% | 81.8% |  |
| JUMP_FORWARD | 44,206,080 | 1.7% | 83.6% |  |
| POP_TOP | 44,021,940 | 1.7% | 85.3% |  |
| CALL_PY_EXACT_ARGS | 40,508,800 | 1.6% | 86.9% | 10.4% |
| CALL_TYPE_1 | 38,645,760 | 1.5% | 88.4% |  |
| ENTER_EXECUTOR | 33,315,840 | 1.3% | 89.7% |  |
| STORE_SUBSCR_DICT | 25,128,960 | 1.0% | 90.7% |  |
| LOAD_CONST | 23,962,980 | 0.9% | 91.6% |  |
| TO_BOOL_BOOL | 15,022,080 | 0.6% | 92.2% |  |
| FOR_ITER | 13,305,040 | 0.5% | 92.7% |  |
| LOAD_DEREF | 12,595,800 | 0.5% | 93.2% |  |
| CALL_BUILTIN_FAST | 12,134,400 | 0.5% | 93.7% |  |
| RETURN_CONST | 11,581,620 | 0.5% | 94.1% |  |
| STORE_FAST_STORE_FAST | 9,369,600 | 0.4% | 94.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,369,600 | 0.4% | 94.9% |  |
| JUMP_BACKWARD | 9,246,720 | 0.4% | 95.2% |  |
| LOAD_ATTR | 8,450,300 | 0.3% | 95.6% |  |
| NOP | 7,772,340 | 0.3% | 95.9% |  |
| BINARY_SUBSCR_DICT | 7,772,160 | 0.3% | 96.2% |  |
| BUILD_LIST | 7,649,700 | 0.3% | 96.5% |  |
| BUILD_MAP | 6,481,980 | 0.3% | 96.7% |  |
| GET_ITER | 6,374,640 | 0.2% | 97.0% |  |
| CALL_FUNCTION_EX | 5,314,920 | 0.2% | 97.2% |  |
| CALL | 4,855,680 | 0.2% | 97.4% |  |
| INTERPRETER_EXIT | 4,853,860 | 0.2% | 97.6% |  |
| MAKE_CELL | 4,853,820 | 0.2% | 97.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 4,260,340 | 0.2% | 97.9% | 6.6% |
| CALL_LIST_APPEND | 4,177,920 | 0.2% | 98.1% |  |
| CHECK_EXC_MATCH | 3,594,240 | 0.1% | 98.2% |  |
| POP_EXCEPT | 3,594,240 | 0.1% | 98.4% |  |
| PUSH_EXC_INFO | 3,594,240 | 0.1% | 98.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,471,360 | 0.1% | 98.7% |  |
| LIST_EXTEND | 2,887,980 | 0.1% | 98.8% |  |
| CALL_INTRINSIC_1 | 2,887,860 | 0.1% | 98.9% |  |
| CALL_ISINSTANCE | 2,887,680 | 0.1% | 99.0% |  |
| TO_BOOL | 2,427,480 | 0.1% | 99.1% |  |
| COPY_FREE_VARS | 2,427,120 | 0.1% | 99.2% |  |
| BUILD_TUPLE | 2,427,060 | 0.1% | 99.3% |  |
| TO_BOOL_NONE | 2,426,880 | 0.1% | 99.4% |  |
| LOAD_ATTR_MODULE | 2,120,220 | 0.1% | 99.5% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,966,140 | 0.1% | 99.5% | 0.2% |
| LIST_APPEND | 1,751,040 | 0.1% | 99.6% |  |
| POP_JUMP_IF_TRUE | 1,505,280 | 0.1% | 99.7% |  |
| SWAP | 1,167,360 | 0.0% | 99.7% |  |
| FOR_ITER_LIST | 1,167,360 | 0.0% | 99.8% |  |
| FOR_ITER_TUPLE | 1,105,920 | 0.0% | 99.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 921,720 | 0.0% | 99.8% |  |
| BINARY_OP_ADD_FLOAT | 921,600 | 0.0% | 99.9% | 0.0% |
| LOAD_FAST_AND_CLEAR | 583,680 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 583,680 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 461,040 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 460,920 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 460,800 | 0.0% | 100.0% |  |
| YIELD_VALUE | 460,800 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 122,880 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 46,320 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 46,320 | 0.0% | 100.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 46,080 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 46,080 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 300 | 0.0% | 100.0% |  |
| STORE_NAME | 300 | 0.0% | 100.0% |  |
| BINARY_OP | 200 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% | 100.0% | 33.3% |
| BUILD_CONST_KEY_MAP | 120 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 80 | 0.0% | 100.0% |  |
| STORE_ATTR | 60 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 60 | 0.0% | 100.0% |  |
| LOAD_NAME | 60 | 0.0% | 100.0% |  |
| STORE_DEREF | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 120,391,860 | 4.7% | 4.7% |
| STORE_FAST LOAD_FAST | 106,598,520 | 4.2% | 8.9% |
| LOAD_FAST RETURN_VALUE | 89,825,460 | 3.5% | 12.4% |
| LOAD_FAST_LOAD_FAST IS_OP | 88,320,000 | 3.5% | 15.9% |
| IS_OP POP_JUMP_IF_FALSE | 86,814,720 | 3.4% | 19.3% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 86,814,720 | 3.4% | 22.7% |
| LOAD_FAST CALL_BUILTIN_O | 69,027,840 | 2.7% | 25.4% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 56,584,500 | 2.2% | 27.6% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 55,342,140 | 2.2% | 29.8% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 53,698,560 | 2.1% | 31.9% |
| CALL_BUILTIN_O STORE_FAST | 53,606,400 | 2.1% | 34.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 53,237,760 | 2.1% | 36.0% |
| LOAD_FAST POP_JUMP_IF_NONE | 51,701,760 | 2.0% | 38.1% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 51,640,320 | 2.0% | 40.1% |
| LOAD_FAST PUSH_NULL | 51,271,680 | 2.0% | 42.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 51,179,520 | 2.0% | 44.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 51,179,520 | 2.0% | 46.1% |
| LOAD_FAST_LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 48,168,960 | 1.9% | 48.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 48,168,960 | 1.9% | 49.9% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST_LOAD_FAST | 48,168,960 | 1.9% | 51.8% |
| POP_JUMP_IF_NONE LOAD_FAST | 46,848,000 | 1.8% | 53.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 45,250,560 | 1.8% | 55.4% |
| RETURN_VALUE STORE_FAST | 44,544,080 | 1.7% | 57.1% |
| STORE_FAST JUMP_FORWARD | 41,656,320 | 1.6% | 58.7% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 40,949,760 | 1.6% | 60.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 39,968,460 | 1.6% | 61.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 39,567,660 | 1.5% | 63.5% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 38,645,760 | 1.5% | 65.0% |
| LOAD_FAST CALL_TYPE_1 | 38,645,760 | 1.5% | 66.5% |
| CALL_TYPE_1 STORE_FAST | 38,645,760 | 1.5% | 68.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_NO_DICT | 38,645,760 | 1.5% | 69.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 38,002,400 | 1.5% | 71.0% |
| JUMP_FORWARD LOAD_FAST_LOAD_FAST | 36,218,880 | 1.4% | 72.4% |
| RESUME_CHECK LOAD_FAST | 34,467,840 | 1.3% | 73.8% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 29,890,440 | 1.2% | 74.9% |
| POP_TOP ENTER_EXECUTOR | 28,262,400 | 1.1% | 76.1% |
| RETURN_VALUE CALL_BUILTIN_O | 27,801,600 | 1.1% | 77.1% |
| CALL_BUILTIN_O POP_TOP | 27,801,600 | 1.1% | 78.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_WITH_DEFAULTS | 22,884,640 | 0.9% | 79.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 16,097,280 | 0.6% | 79.8% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 15,022,080 | 0.6% | 80.3% |
| POP_TOP LOAD_FAST | 10,782,720 | 0.4% | 80.8% |
| PUSH_NULL LOAD_FAST | 10,291,740 | 0.4% | 81.2% |
| CALL_BUILTIN_O STORE_SUBSCR_DICT | 10,076,160 | 0.4% | 81.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 9,615,360 | 0.4% | 81.9% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 9,369,600 | 0.4% | 82.3% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 9,369,600 | 0.4% | 82.7% |
| JUMP_BACKWARD FOR_ITER | 9,246,720 | 0.4% | 83.0% |
| RETURN_CONST POP_TOP | 9,154,560 | 0.4% | 83.4% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 7,864,320 | 0.3% | 83.7% |
| RETURN_VALUE STORE_SUBSCR_DICT | 7,864,320 | 0.3% | 84.0% |
| LOAD_FAST_LOAD_FAST PUSH_NULL | 7,864,320 | 0.3% | 84.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 7,864,320 | 0.3% | 84.6% |
| STORE_SUBSCR_DICT JUMP_BACKWARD | 7,864,320 | 0.3% | 84.9% |
| NOP LOAD_FAST | 7,772,160 | 0.3% | 85.2% |
| CALL_BUILTIN_O BINARY_SUBSCR_DICT | 7,772,160 | 0.3% | 85.5% |
| LOAD_CONST CALL_BUILTIN_FAST | 7,280,640 | 0.3% | 85.8% |
| LOAD_FAST LOAD_CONST | 7,280,640 | 0.3% | 86.1% |
| LOAD_FAST TO_BOOL_BOOL | 7,280,640 | 0.3% | 86.4% |
| CALL_BUILTIN_FAST STORE_FAST | 7,280,640 | 0.3% | 86.7% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 7,188,540 | 0.3% | 87.0% |
| LOAD_FAST STORE_SUBSCR_DICT | 7,188,480 | 0.3% | 87.2% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 7,188,480 | 0.3% | 87.5% |
| RESUME_CHECK NOP | 7,188,480 | 0.3% | 87.8% |
| STORE_SUBSCR_DICT LOAD_GLOBAL_MODULE | 7,188,480 | 0.3% | 88.1% |
| STORE_SUBSCR_DICT LOAD_FAST | 7,065,600 | 0.3% | 88.4% |
| BUILD_MAP STORE_FAST | 6,481,920 | 0.3% | 88.6% |
| JUMP_FORWARD LOAD_GLOBAL_BUILTIN | 6,021,120 | 0.2% | 88.9% |
| LOAD_FAST LOAD_ATTR | 6,021,120 | 0.2% | 89.1% |
| LOAD_CONST LOAD_FAST | 5,898,360 | 0.2% | 89.3% |
| BUILD_LIST LOAD_FAST | 5,898,240 | 0.2% | 89.6% |
| LOAD_FAST LOAD_DEREF | 5,314,560 | 0.2% | 89.8% |
| LOAD_CONST LOAD_CONST | 4,853,940 | 0.2% | 90.0% |
| CALL_BUILTIN_FAST TO_BOOL_BOOL | 4,853,760 | 0.2% | 90.1% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_BUILTIN | 4,638,720 | 0.2% | 90.3% |
| RESUME_CHECK LOAD_DEREF | 4,393,140 | 0.2% | 90.5% |
| LOAD_DEREF LOAD_CONST | 4,392,960 | 0.2% | 90.7% |
| LOAD_FAST CALL_LIST_APPEND | 4,177,920 | 0.2% | 90.8% |
| BINARY_SUBSCR_DICT LOAD_ATTR_METHOD_NO_DICT | 4,177,920 | 0.2% | 91.0% |
| CALL_LIST_APPEND RETURN_CONST | 4,177,920 | 0.2% | 91.2% |
| GET_ITER FOR_ITER | 4,055,040 | 0.2% | 91.3% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 3,932,280 | 0.2% | 91.5% |
| FOR_ITER LOAD_FAST | 3,932,160 | 0.2% | 91.6% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 3,594,240 | 0.1% | 91.8% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 3,594,240 | 0.1% | 91.9% |
| POP_JUMP_IF_FALSE POP_TOP | 3,594,240 | 0.1% | 92.1% |
| BINARY_SUBSCR_DICT PUSH_EXC_INFO | 3,594,240 | 0.1% | 92.2% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 3,594,240 | 0.1% | 92.3% |
| LOAD_FAST BUILD_LIST | 3,471,600 | 0.1% | 92.5% |
| CALL_METHOD_DESCRIPTOR_NOARGS GET_ITER | 3,471,360 | 0.1% | 92.6% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 3,471,360 | 0.1% | 92.7% |
| RESUME_CHECK BUILD_MAP | 3,471,360 | 0.1% | 92.9% |
| POP_EXCEPT RETURN_CONST | 3,010,560 | 0.1% | 93.0% |
| POP_JUMP_IF_NOT_NONE BUILD_MAP | 3,010,560 | 0.1% | 93.1% |
| STORE_FAST ENTER_EXECUTOR | 3,010,560 | 0.1% | 93.2% |
| STORE_SUBSCR_DICT POP_EXCEPT | 3,010,560 | 0.1% | 93.3% |
| LOAD_DEREF PUSH_NULL | 2,888,100 | 0.1% | 93.5% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 2,887,860 | 0.1% | 93.6% |
| LIST_EXTEND CALL_INTRINSIC_1 | 2,887,860 | 0.1% | 93.7% |
| LOAD_ATTR PUSH_NULL | 2,887,740 | 0.1% | 93.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,594,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,594,240 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,471,360 | 54.5% |
| LOAD_FAST | 2,211,840 | 34.7% |
| CALL | 583,680 | 9.2% |
| LOAD_CONST | 61,440 | 1.0% |
| CALL_BUILTIN_CLASS | 46,320 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 4,055,040 | 63.6% |
| FOR_ITER_LIST | 1,167,360 | 18.3% |
| LOAD_FAST_AND_CLEAR | 583,680 | 9.2% |
| CALL_PY_EXACT_ARGS | 460,800 | 7.2% |
| FOR_ITER_TUPLE | 61,440 | 1.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,188,480 | 92.5% |
| STORE_FAST | 583,680 | 7.5% |
| POP_TOP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,772,160 | 100.0% |
| LOAD_DEREF | 180 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 3,010,560 | 83.8% |
| POP_TOP | 583,680 | 16.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,010,560 | 83.8% |
| JUMP_FORWARD | 583,680 | 16.2% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 27,801,600 | 63.2% |
| RETURN_CONST | 9,154,560 | 20.8% |
| POP_JUMP_IF_FALSE | 3,594,240 | 8.2% |
| CALL | 2,427,060 | 5.5% |
| RESUME_CHECK | 460,800 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 28,262,400 | 64.2% |
| LOAD_FAST | 10,782,720 | 24.5% |
| JUMP_FORWARD | 1,966,080 | 4.5% |
| RETURN_CONST | 1,966,080 | 4.5% |
| POP_EXCEPT | 583,680 | 1.3% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 3,594,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 3,594,240 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,271,680 | 75.8% |
| LOAD_FAST_LOAD_FAST | 7,864,320 | 11.6% |
| LOAD_DEREF | 2,888,100 | 4.3% |
| LOAD_ATTR | 2,887,740 | 4.3% |
| LOAD_ATTR_MODULE | 2,120,220 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 53,698,560 | 79.4% |
| LOAD_FAST | 10,291,740 | 15.2% |
| LOAD_CONST | 2,426,880 | 3.6% |
| CALL | 1,198,580 | 1.8% |
| CALL_ALLOC_AND_ENTER_INIT | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 89,825,460 | 97.4% |
| BUILD_TUPLE | 1,966,080 | 2.1% |
| CALL_FUNCTION_EX | 460,800 | 0.5% |
| RETURN_VALUE | 180 | 0.0% |
| EXIT_INIT_CHECK | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 44,544,080 | 48.3% |
| CALL_BUILTIN_O | 27,801,600 | 30.1% |
| LOAD_FAST_LOAD_FAST | 7,864,320 | 8.5% |
| STORE_SUBSCR_DICT | 7,864,320 | 8.5% |
| INTERPRETER_EXIT | 1,966,080 | 2.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,426,880 | 100.0% |
| TO_BOOL | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,426,880 | 100.0% |
| TO_BOOL | 600 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 60.0% |
| BINARY_OP | 40 | 20.0% |
| LOAD_FAST | 40 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 30.0% |
| STORE_FAST | 60 | 30.0% |
| BINARY_OP | 40 | 20.0% |
| BINARY_OP_SUBTRACT_FLOAT | 40 | 20.0% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 100.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,471,600 | 45.4% |
| LOAD_FAST_LOAD_FAST | 2,426,880 | 31.7% |
| RESUME_CHECK | 1,167,420 | 15.3% |
| SWAP | 583,680 | 7.6% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,898,240 | 77.1% |
| STORE_FAST | 1,167,360 | 15.3% |
| SWAP | 583,680 | 7.6% |
| LOAD_CONST | 240 | 0.0% |
| LOAD_DEREF | 180 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,471,360 | 53.6% |
| POP_JUMP_IF_NOT_NONE | 3,010,560 | 46.4% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,481,920 | 100.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 1,966,080 | 81.0% |
| LOAD_FAST | 460,980 | 19.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,966,080 | 81.0% |
| LOAD_CONST | 460,920 | 19.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,426,940 | 50.0% |
| PUSH_NULL | 1,198,580 | 24.7% |
| ENTER_EXECUTOR | 645,060 | 13.3% |
| LOAD_FAST_LOAD_FAST | 583,680 | 12.0% |
| CALL | 1,380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,427,060 | 50.0% |
| LOAD_FAST | 921,720 | 19.0% |
| STORE_FAST | 921,720 | 19.0% |
| GET_ITER | 583,680 | 12.0% |
| CALL | 1,380 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 2,887,860 | 54.3% |
| LOAD_FAST | 2,427,060 | 45.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 2,426,940 | 45.7% |
| STORE_FAST | 1,966,080 | 37.0% |
| RESUME_CHECK | 460,920 | 8.7% |
| RETURN_VALUE | 460,800 | 8.7% |
| COPY_FREE_VARS | 180 | 0.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 2,887,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 2,887,860 | 100.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 1,966,140 | 81.0% |
| CALL_PY_EXACT_ARGS | 460,800 | 19.0% |
| CALL_FUNCTION_EX | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,966,320 | 81.0% |
| RETURN_GENERATOR | 460,800 | 19.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 28,262,400 | 84.8% |
| STORE_FAST | 3,010,560 | 9.0% |
| LIST_APPEND | 1,751,040 | 5.3% |
| ENTER_EXECUTOR | 291,840 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 29,890,440 | 89.7% |
| LOAD_FAST | 1,167,420 | 3.5% |
| CALL | 645,060 | 1.9% |
| STORE_FAST | 583,680 | 1.8% |
| RETURN_CONST | 460,800 | 1.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 9,246,720 | 69.5% |
| GET_ITER | 4,055,040 | 30.5% |
| FOR_ITER | 3,280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 9,369,600 | 70.4% |
| LOAD_FAST | 3,932,160 | 29.6% |
| FOR_ITER | 3,280 | 0.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 88,320,000 | 97.3% |
| LOAD_CONST | 2,426,880 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 86,814,720 | 95.7% |
| STORE_FAST | 2,426,880 | 2.7% |
| POP_JUMP_IF_TRUE | 1,505,280 | 1.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_DICT | 7,864,320 | 85.0% |
| POP_JUMP_IF_TRUE | 1,382,400 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 9,246,720 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 41,656,320 | 94.2% |
| POP_TOP | 1,966,080 | 4.4% |
| POP_EXCEPT | 583,680 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,218,880 | 81.9% |
| LOAD_GLOBAL_BUILTIN | 6,021,120 | 13.6% |
| LOAD_FAST | 1,966,080 | 4.4% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,751,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,751,040 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,887,680 | 100.0% |
| LOAD_DEREF | 180 | 0.0% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 2,887,860 | 100.0% |
| LOAD_CONST | 120 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,021,120 | 71.3% |
| LOAD_GLOBAL_MODULE | 2,427,020 | 28.7% |
| LOAD_ATTR | 2,100 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,887,740 | 34.2% |
| LOAD_ATTR_METHOD_NO_DICT | 2,426,880 | 28.7% |
| BUILD_TUPLE | 1,966,080 | 23.3% |
| STORE_FAST | 1,167,360 | 13.8% |
| LOAD_ATTR | 2,100 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,280,640 | 30.4% |
| LOAD_CONST | 4,853,940 | 20.3% |
| LOAD_DEREF | 4,392,960 | 18.3% |
| PUSH_NULL | 2,426,880 | 10.1% |
| RESUME_CHECK | 1,966,200 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 7,280,640 | 30.4% |
| LOAD_FAST | 5,898,360 | 24.6% |
| LOAD_CONST | 4,853,940 | 20.3% |
| IS_OP | 2,426,880 | 10.1% |
| CALL_BUILTIN_O | 2,426,880 | 10.1% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,314,560 | 42.2% |
| RESUME_CHECK | 4,393,140 | 34.9% |
| POP_JUMP_IF_FALSE | 2,426,880 | 19.3% |
| STORE_FAST | 460,800 | 3.7% |
| NOP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,392,960 | 34.9% |
| PUSH_NULL | 2,888,100 | 22.9% |
| CALL_PY_WITH_DEFAULTS | 2,887,680 | 22.9% |
| LOAD_GLOBAL_BUILTIN | 2,426,880 | 19.3% |
| LIST_EXTEND | 180 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120,391,860 | 22.8% |
| STORE_FAST | 106,598,520 | 20.2% |
| POP_JUMP_IF_FALSE | 53,237,760 | 10.1% |
| POP_JUMP_IF_NOT_NONE | 48,168,960 | 9.1% |
| POP_JUMP_IF_NONE | 46,848,000 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 89,825,460 | 17.0% |
| CALL_BUILTIN_O | 69,027,840 | 13.1% |
| POP_JUMP_IF_NONE | 51,701,760 | 9.8% |
| LOAD_ATTR_METHOD_NO_DICT | 51,640,320 | 9.8% |
| PUSH_NULL | 51,271,680 | 9.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 583,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 583,680 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 55,342,140 | 25.1% |
| PUSH_NULL | 53,698,560 | 24.4% |
| LOAD_ATTR_METHOD_NO_DICT | 48,168,960 | 21.9% |
| JUMP_FORWARD | 36,218,880 | 16.4% |
| LOAD_GLOBAL_MODULE | 9,615,360 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 88,320,000 | 40.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 48,168,960 | 21.9% |
| CALL_PY_EXACT_ARGS | 38,002,400 | 17.3% |
| CALL_PY_WITH_DEFAULTS | 22,884,640 | 10.4% |
| PUSH_NULL | 7,864,320 | 3.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 40.0% |
| STORE_FAST | 120 | 40.0% |
| ENTER_EXECUTOR | 40 | 13.3% |
| LOAD_CONST | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 160 | 53.3% |
| LOAD_GLOBAL_BUILTIN | 80 | 26.7% |
| LOAD_ATTR | 60 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 86,814,720 | 78.7% |
| TO_BOOL_BOOL | 15,022,080 | 13.6% |
| CHECK_EXC_MATCH | 3,594,240 | 3.3% |
| TO_BOOL | 2,426,880 | 2.2% |
| TO_BOOL_NONE | 2,426,880 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 53,237,760 | 48.3% |
| LOAD_GLOBAL_BUILTIN | 40,949,760 | 37.1% |
| LOAD_FAST_LOAD_FAST | 7,188,480 | 6.5% |
| POP_TOP | 3,594,240 | 3.3% |
| LOAD_DEREF | 2,426,880 | 2.2% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,701,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,848,000 | 90.6% |
| LOAD_GLOBAL_BUILTIN | 2,426,880 | 4.7% |
| LOAD_GLOBAL_MODULE | 2,426,880 | 4.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,179,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 48,168,960 | 94.1% |
| BUILD_MAP | 3,010,560 | 5.9% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 1,505,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,382,400 | 91.8% |
| LOAD_GLOBAL_BUILTIN | 122,880 | 8.2% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 4,177,920 | 36.1% |
| POP_EXCEPT | 3,010,560 | 26.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,966,200 | 17.0% |
| POP_TOP | 1,966,080 | 17.0% |
| ENTER_EXECUTOR | 460,800 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 9,154,560 | 79.0% |
| INTERPRETER_EXIT | 2,426,980 | 21.0% |
| EXIT_INIT_CHECK | 80 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 60 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 86,814,720 | 34.7% |
| CALL_BUILTIN_O | 53,606,400 | 21.4% |
| RETURN_VALUE | 44,544,080 | 17.8% |
| CALL_TYPE_1 | 38,645,760 | 15.4% |
| CALL_BUILTIN_FAST | 7,280,640 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 106,598,520 | 42.6% |
| LOAD_FAST_LOAD_FAST | 55,342,140 | 22.1% |
| JUMP_FORWARD | 41,656,320 | 16.6% |
| LOAD_GLOBAL_MODULE | 39,567,660 | 15.8% |
| ENTER_EXECUTOR | 3,010,560 | 1.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 583,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 583,680 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 9,369,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,864,320 | 83.9% |
| LOAD_FAST_LOAD_FAST | 1,505,280 | 16.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 583,680 | 50.0% |
| LOAD_FAST_AND_CLEAR | 583,680 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 583,680 | 50.0% |
| FOR_ITER_TUPLE | 583,680 | 50.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 921,680 | 100.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 921,600 | 100.0% |
| STORE_FAST | 120 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 7,772,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 4,177,920 | 53.8% |
| PUSH_EXC_INFO | 3,594,240 | 46.2% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 46,140 | 99.6% |
| LOAD_FAST | 120 | 0.3% |
| CALL | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 46,320 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 69,027,840 | 69.5% |
| RETURN_VALUE | 27,801,600 | 28.0% |
| LOAD_CONST | 2,426,880 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 53,606,400 | 54.0% |
| POP_TOP | 27,801,600 | 28.0% |
| STORE_SUBSCR_DICT | 10,076,160 | 10.2% |
| BINARY_SUBSCR_DICT | 7,772,160 | 7.8% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,177,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,177,920 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 48,168,960 | 55.5% |
| LOAD_FAST | 38,645,760 | 44.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 86,814,720 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 3,471,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 3,471,360 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 38,002,400 | 93.8% |
| LOAD_FAST | 1,966,080 | 4.9% |
| GET_ITER | 460,800 | 1.1% |
| CALL_PY_WITH_DEFAULTS | 79,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 39,968,460 | 98.7% |
| COPY_FREE_VARS | 460,800 | 1.1% |
| CALL_PY_WITH_DEFAULTS | 79,540 | 0.2% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 29,890,440 | 52.7% |
| LOAD_FAST_LOAD_FAST | 22,884,640 | 40.4% |
| LOAD_DEREF | 2,887,680 | 5.1% |
| LOAD_FAST | 921,720 | 1.6% |
| CALL_PY_EXACT_ARGS | 79,540 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 56,584,500 | 99.8% |
| CALL_PY_EXACT_ARGS | 79,520 | 0.1% |
| CALL_PY_WITH_DEFAULTS | 10,240 | 0.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 122,880 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,645,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 38,645,760 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,167,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,167,360 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 46,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 46,320 | 100.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 583,680 | 52.8% |
| LOAD_FAST | 460,800 | 41.7% |
| GET_ITER | 61,440 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 583,680 | 52.8% |
| STORE_FAST | 522,240 | 47.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,640,320 | 53.3% |
| LOAD_GLOBAL_MODULE | 38,645,760 | 39.9% |
| BINARY_SUBSCR_DICT | 4,177,920 | 4.3% |
| LOAD_ATTR | 2,426,880 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 48,168,960 | 49.7% |
| LOAD_FAST | 45,250,560 | 46.7% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 3,471,360 | 3.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,120,080 | 100.0% |
| LOAD_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,120,220 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 51,179,520 | 39.4% |
| POP_JUMP_IF_FALSE | 40,949,760 | 31.5% |
| LOAD_FAST | 16,097,280 | 12.4% |
| JUMP_FORWARD | 6,021,120 | 4.6% |
| LOAD_FAST_LOAD_FAST | 4,638,720 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,391,860 | 92.7% |
| CHECK_EXC_MATCH | 3,594,240 | 2.8% |
| CALL_ISINSTANCE | 2,887,680 | 2.2% |
| CALL_BUILTIN_FAST | 2,426,880 | 1.9% |
| LOAD_FAST_LOAD_FAST | 583,680 | 0.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 39,567,660 | 74.9% |
| STORE_SUBSCR_DICT | 7,188,480 | 13.6% |
| POP_JUMP_IF_FALSE | 2,426,880 | 4.6% |
| POP_JUMP_IF_NONE | 2,426,880 | 4.6% |
| LOAD_FAST | 921,600 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 38,645,760 | 73.2% |
| LOAD_FAST_LOAD_FAST | 9,615,360 | 18.2% |
| LOAD_ATTR | 2,427,020 | 4.6% |
| LOAD_ATTR_MODULE | 2,120,080 | 4.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 56,584,500 | 54.3% |
| CALL_PY_EXACT_ARGS | 39,968,460 | 38.3% |
| MAKE_CELL | 2,426,940 | 2.3% |
| CACHE | 2,426,920 | 2.3% |
| COPY_FREE_VARS | 1,966,320 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 51,179,520 | 49.1% |
| LOAD_FAST | 34,467,840 | 33.0% |
| NOP | 7,188,480 | 6.9% |
| LOAD_DEREF | 4,393,140 | 4.2% |
| BUILD_MAP | 3,471,360 | 3.3% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 10,076,160 | 40.1% |
| RETURN_VALUE | 7,864,320 | 31.3% |
| LOAD_FAST | 7,188,480 | 28.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 7,864,320 | 31.3% |
| LOAD_GLOBAL_MODULE | 7,188,480 | 28.6% |
| LOAD_FAST | 7,065,600 | 28.1% |
| POP_EXCEPT | 3,010,560 | 12.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 9,369,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 9,369,600 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,426,920 | 50.0% |
| COPY_FREE_VARS | 1,966,140 | 40.5% |
| POP_TOP | 460,800 | 9.5% |


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

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,426,980 | 50.0% |
| RETURN_VALUE | 1,966,080 | 40.5% |
| YIELD_VALUE | 460,800 | 9.5% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 461,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 460,920 | 100.0% |
| STORE_NAME | 120 | 0.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 460,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 460,800 | 100.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 2,426,940 | 50.0% |
| MAKE_CELL | 2,426,880 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,426,940 | 50.0% |
| MAKE_CELL | 2,426,880 | 50.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 460,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,800 | 100.0% |
| LOAD_CONST | 60 | 0.0% |
| STORE_NAME | 60 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 460,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 460,800 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 921,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 921,600 | 100.0% |


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

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,280,640 | 60.0% |
| LOAD_FAST | 2,426,880 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 2,426,880 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,280,640 | 60.0% |
| TO_BOOL_BOOL | 4,853,760 | 40.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,887,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,887,680 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 46,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 46,080 | 100.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,932,280 | 92.3% |
| ENTER_EXECUTOR | 261,120 | 6.1% |
| LOAD_FAST_LOAD_FAST | 61,560 | 1.4% |
| STORE_ATTR_INSTANCE_VALUE | 5,320 | 0.1% |
| STORE_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,966,200 | 46.2% |
| LOAD_CONST | 1,966,140 | 46.1% |
| LOAD_GLOBAL_MODULE | 276,480 | 6.5% |
| LOAD_GLOBAL_BUILTIN | 46,080 | 1.1% |
| STORE_ATTR_INSTANCE_VALUE | 5,320 | 0.1% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 46,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 46,080 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,280,640 | 48.5% |
| CALL_BUILTIN_FAST | 4,853,760 | 32.3% |
| CALL_ISINSTANCE | 2,887,680 | 19.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 15,022,080 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,426,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,426,880 | 100.0% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 100.0% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 60 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 120 | 40.0% |
| LOAD_CONST | 60 | 20.0% |
| SET_FUNCTION_ATTRIBUTE | 60 | 20.0% |
| LOAD_NAME | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 180 | 60.0% |
| LOAD_FAST | 60 | 20.0% |
| RETURN_CONST | 60 | 20.0% |


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
| LOAD_FAST | 1,966,080 | 100.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,080 | 100.0% |
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
|     deferred | 120 | 0.0% |
|          hit | 1,843,260 | 100.0% |
|         miss | 60 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 50.0% |
| Failure | 40 | 50.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 40 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 7,772,160 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,854,180 | 1.4% |
|        deopt | 169,300 | 0.0% |
|          hit | 335,767,720 | 96.0% |
|         miss | 8,972,880 | 2.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 169,420 | 99.2% |
| Failure | 1,380 | 0.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 620 | 44.9% |
| meth descr varargs keywords | 600 | 43.5% |
| class no vectorcall | 160 | 11.6% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 13,301,760 | 85.1% |
|          hit | 2,319,600 | 14.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 3,280 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict items | 2,780 | 84.8% |
| zip | 500 | 15.2% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 8,448,060 | 7.7% |
|        deopt | 60 | 0.0% |
|          hit | 101,020,140 | 92.3% |
|         miss | 3,180 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 8.7% |
| Failure | 2,100 | 91.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr descriptor | 1,080 | 51.4% |
| method | 900 | 42.9% |
| metaclass attribute | 120 | 5.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 0.0% |
|          hit | 182,738,820 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 100.0% |
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
|        deopt | 5,320 | 0.1% |
|          hit | 3,977,560 | 93.4% |
|         miss | 282,780 | 6.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,380 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 25,175,040 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,426,880 | 12.2% |
|          hit | 17,448,960 | 87.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 600 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| tuple | 600 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 9,369,600 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,499,452,820 | 58.7% |
| Not specialized | 262,216,040 | 10.3% |
| Specialized | 791,727,800 | 31.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER | 13,301,760 | 45.8% |
| LOAD_ATTR | 8,448,060 | 29.1% |
| CALL | 4,854,180 | 16.7% |
| TO_BOOL | 2,426,880 | 8.4% |
| BINARY_OP | 120 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 4,758,000 | 51.4% |
| CALL_PY_EXACT_ARGS | 4,214,840 | 45.5% |
| STORE_ATTR_INSTANCE_VALUE | 282,780 | 3.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,180 | 0.0% |
| BINARY_OP_ADD_FLOAT | 60 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 40 | 0.0% |
| CHECK_EXC_MATCH | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_EXCEPT | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 4,853,860 | 4.6% |
| Calls to Python functions inlined | 99,901,880 | 95.4% |
| Calls via PyEval_EvalFrame (total) | 4,853,860 | 4.6% |
| Calls via PyEval_EvalFrame (vector) | 3,932,260 | 3.8% |
| Calls via PyEval_EvalFrame (generator) | 921,600 | 0.9% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 3,932,200 | 3.8% |
| Calls via PyEval_EvalFrame (build class) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 2,888,040 | 2.8% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 3,594,240 | 3.4% |
| Frames pushed | 103,834,220 | 99.1% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 39,711,800 | 24.2% |
| Frees to freelist | 39,711,580 |  |
| Allocations | 124,479,900 | 75.8% |
| Allocations to 512 bytes | 124,479,660 | 75.8% |
| Allocations to 4 kbytes | 240 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 126,230,110 |  |
| New values | 2,426,920 |  |
| Interpreter increfs | 1,154,383,200 | 75.5% |
| Interpreter decrefs | 1,385,079,300 | 82.6% |
| Increfs | 373,935,900 | 24.5% |
| Decrefs | 292,166,396 | 17.4% |
| Materialize dict (on request) | 2,661,680 | 109.7% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 234,680 | 9.7% |
| Method cache hits | 4,338,716 |  |
| Method cache misses | 124 |  |
| Method cache collisions | 359 |  |
| Method cache dunder hits | 27,499,020 |  |
| Method cache dunder misses | 380 |  |


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
| Optimization attempts | 543,920 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 33,315,840 |  |
| Uops executed | 455,145,060 | 13.66 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 543,920 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,519,220 | 7.6% |
| <= 16 | 30,597,000 | 91.8% |
| <= 32 | 15,300 | 0.0% |
| <= 64 | 184,320 | 0.6% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 113,387,400 | 24.9% | 24.9% |  |
| _SET_IP | 73,082,280 | 16.1% | 41.0% |  |
| PUSH_NULL | 57,169,740 | 12.6% | 53.5% |  |
| _POP_JUMP_IF_TRUE | 33,515,460 | 7.4% | 60.9% |  |
| _EXIT_TRACE | 33,054,720 | 7.3% | 68.2% |  |
| STORE_FAST | 30,996,240 | 6.8% | 75.0% |  |
| _ITER_CHECK_LIST | 27,801,600 | 6.1% | 81.1% |  |
| _IS_ITER_EXHAUSTED_LIST | 27,801,600 | 6.1% | 87.2% |  |
| _ITER_NEXT_LIST | 26,634,240 | 5.9% | 93.0% |  |
| _ITER_CHECK_TUPLE | 2,903,040 | 0.6% | 93.7% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 2,903,040 | 0.6% | 94.3% |  |
| _ITER_CHECK_RANGE | 2,810,820 | 0.6% | 94.9% |  |
| _IS_ITER_EXHAUSTED_RANGE | 2,810,820 | 0.6% | 95.5% |  |
| _GUARD_GLOBALS_VERSION | 2,749,200 | 0.6% | 96.1% |  |
| _ITER_NEXT_RANGE | 2,749,200 | 0.6% | 96.8% |  |
| _LOAD_GLOBAL_MODULE | 2,733,900 | 0.6% | 97.4% |  |
| _CHECK_ATTR_MODULE | 2,733,900 | 0.6% | 98.0% |  |
| _LOAD_ATTR_MODULE | 2,733,900 | 0.6% | 98.6% |  |
| POP_TOP | 2,519,220 | 0.6% | 99.1% |  |
| _ITER_NEXT_TUPLE | 1,612,800 | 0.4% | 99.5% |  |
| _GUARD_TYPE_VERSION | 629,760 | 0.1% | 99.6% |  |
| _GUARD_DORV_VALUES | 445,440 | 0.1% | 99.7% | 58.6% |
| LOAD_CONST | 383,940 | 0.1% | 99.8% |  |
| GET_ITER | 199,620 | 0.0% | 99.8% |  |
| STORE_SUBSCR_LIST_INT | 184,320 | 0.0% | 99.9% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 184,320 | 0.0% | 99.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 184,320 | 0.0% | 99.9% |  |
| _STORE_ATTR_INSTANCE_VALUE | 184,320 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 15,300 | 0.0% | 100.0% |  |
| _GUARD_BUILTINS_VERSION | 15,300 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_BUILTINS | 15,300 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 543,920 |


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
Stats gathered on: 2023-10-09
