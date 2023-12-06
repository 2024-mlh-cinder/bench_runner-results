
# Pystats results

- benchmark: hexiom
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 47,955,480 | 13.3% | 13.3% |  |
| RESUME_CHECK | 30,083,060 | 8.4% | 21.7% |  |
| ENTER_EXECUTOR | 27,917,840 | 7.8% | 29.5% |  |
| LOAD_CONST | 24,359,560 | 6.8% | 36.3% |  |
| POP_TOP | 19,556,720 | 5.4% | 41.7% |  |
| INTERPRETER_EXIT | 19,150,300 | 5.3% | 47.0% |  |
| YIELD_VALUE | 18,191,760 | 5.1% | 52.1% |  |
| BINARY_SUBSCR_LIST_INT | 17,154,020 | 4.8% | 56.9% |  |
| STORE_FAST | 16,086,140 | 4.5% | 61.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 15,876,780 | 4.4% | 65.8% |  |
| COMPARE_OP_INT | 12,146,760 | 3.4% | 69.1% |  |
| RETURN_VALUE | 9,807,260 | 2.7% | 71.9% |  |
| POP_JUMP_IF_FALSE | 8,616,320 | 2.4% | 74.3% |  |
| LOAD_FAST_LOAD_FAST | 8,213,540 | 2.3% | 76.5% |  |
| POP_JUMP_IF_TRUE | 7,718,120 | 2.1% | 78.7% |  |
| CALL_PY_EXACT_ARGS | 6,597,760 | 1.8% | 80.5% |  |
| LOAD_GLOBAL_BUILTIN | 5,832,140 | 1.6% | 82.1% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,784,500 | 1.6% | 83.8% |  |
| TO_BOOL_BOOL | 4,895,740 | 1.4% | 85.1% |  |
| CALL_LEN | 4,721,060 | 1.3% | 86.4% |  |
| BINARY_SUBSCR_GETITEM | 4,622,460 | 1.3% | 87.7% |  |
| BINARY_OP_ADD_INT | 4,511,300 | 1.3% | 89.0% |  |
| LOAD_GLOBAL_MODULE | 4,438,940 | 1.2% | 90.2% |  |
| JUMP_FORWARD | 4,159,500 | 1.2% | 91.4% |  |
| GET_ITER | 3,258,700 | 0.9% | 92.3% |  |
| FOR_ITER_LIST | 3,021,500 | 0.8% | 93.1% | 0.1% |
| LOAD_DEREF | 2,862,060 | 0.8% | 93.9% |  |
| CONTAINS_OP | 2,677,840 | 0.7% | 94.7% |  |
| RETURN_CONST | 2,377,460 | 0.7% | 95.3% |  |
| SWAP | 2,025,520 | 0.6% | 95.9% |  |
| COPY | 1,630,960 | 0.5% | 96.3% |  |
| CALL_BUILTIN_CLASS | 1,389,420 | 0.4% | 96.7% |  |
| FOR_ITER_RANGE | 1,335,720 | 0.4% | 97.1% | 0.3% |
| RETURN_GENERATOR | 957,520 | 0.3% | 97.4% |  |
| COPY_FREE_VARS | 957,520 | 0.3% | 97.6% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 957,420 | 0.3% | 97.9% |  |
| STORE_SUBSCR_LIST_INT | 936,020 | 0.3% | 98.1% |  |
| BINARY_OP_SUBTRACT_INT | 819,720 | 0.2% | 98.4% |  |
| BUILD_TUPLE | 615,800 | 0.2% | 98.5% |  |
| MAKE_FUNCTION | 557,480 | 0.2% | 98.7% |  |
| SET_FUNCTION_ATTRIBUTE | 557,400 | 0.2% | 98.9% |  |
| BUILD_LIST | 487,580 | 0.1% | 99.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 472,040 | 0.1% | 99.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 350,120 | 0.1% | 99.2% |  |
| POP_JUMP_IF_NOT_NONE | 339,500 | 0.1% | 99.3% |  |
| CALL_LIST_APPEND | 298,820 | 0.1% | 99.4% |  |
| BINARY_SLICE | 275,680 | 0.1% | 99.5% |  |
| EXTENDED_ARG | 166,620 | 0.0% | 99.5% |  |
| EXIT_INIT_CHECK | 156,680 | 0.0% | 99.6% |  |
| CALL_ALLOC_AND_ENTER_INIT | 156,680 | 0.0% | 99.6% |  |
| STORE_DEREF | 139,360 | 0.0% | 99.7% |  |
| MAKE_CELL | 128,940 | 0.0% | 99.7% |  |
| BINARY_SUBSCR_TUPLE_INT | 127,620 | 0.0% | 99.7% |  |
| LOAD_ATTR_CLASS | 125,420 | 0.0% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_O | 122,240 | 0.0% | 99.8% |  |
| LIST_APPEND | 105,340 | 0.0% | 99.8% |  |
| STORE_FAST_LOAD_FAST | 104,740 | 0.0% | 99.8% |  |
| LOAD_FAST_AND_CLEAR | 104,320 | 0.0% | 99.9% |  |
| CALL_PY_WITH_DEFAULTS | 102,960 | 0.0% | 99.9% |  |
| STORE_FAST_STORE_FAST | 72,060 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 72,000 | 0.0% | 99.9% |  |
| NOP | 57,340 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 22,040 | 0.0% | 100.0% |  |
| CALL_KW | 19,200 | 0.0% | 100.0% |  |
| BINARY_OP | 17,580 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 12,120 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 8,780 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 8,720 | 0.0% | 100.0% |  |
| CALL_STR_1 | 7,640 | 0.0% | 100.0% |  |
| CALL | 6,120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 4,820 | 0.0% | 100.0% |  |
| LOAD_ATTR | 4,760 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 4,240 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 4,060 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 2,120 | 0.0% | 100.0% |  |
| COMPARE_OP | 1,560 | 0.0% | 100.0% |  |
| FOR_ITER | 1,560 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,300 | 0.0% | 100.0% |  |
| TO_BOOL | 960 | 0.0% | 100.0% |  |
| PUSH_NULL | 840 | 0.0% | 100.0% |  |
| RESUME | 700 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 680 | 0.0% | 100.0% |  |
| BUILD_MAP | 640 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 620 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 620 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 580 | 0.0% | 100.0% |  |
| STORE_ATTR | 560 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 400 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 120 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_TOP ENTER_EXECUTOR | 18,209,980 | 5.1% | 5.1% |
| CACHE RESUME_CHECK | 18,192,640 | 5.1% | 10.1% |
| YIELD_VALUE INTERPRETER_EXIT | 18,191,760 | 5.1% | 15.2% |
| RESUME_CHECK POP_TOP | 18,191,720 | 5.1% | 20.3% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 13,736,940 | 3.8% | 24.1% |
| ENTER_EXECUTOR YIELD_VALUE | 13,181,220 | 3.7% | 27.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 11,003,160 | 3.1% | 30.8% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 10,806,080 | 3.0% | 33.8% |
| STORE_FAST LOAD_FAST | 8,710,960 | 2.4% | 36.2% |
| RESUME_CHECK LOAD_FAST | 6,927,540 | 1.9% | 38.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 5,912,700 | 1.6% | 39.8% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 5,689,780 | 1.6% | 41.4% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 5,622,960 | 1.6% | 43.0% |
| LOAD_CONST COMPARE_OP_INT | 5,462,080 | 1.5% | 44.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 5,241,540 | 1.5% | 45.9% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 5,155,360 | 1.4% | 47.4% |
| CALL_LEN LOAD_CONST | 4,634,040 | 1.3% | 48.7% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 4,622,460 | 1.3% | 49.9% |
| LOAD_FAST LOAD_CONST | 4,467,960 | 1.2% | 51.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 4,430,280 | 1.2% | 52.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 4,424,080 | 1.2% | 53.6% |
| LOAD_CONST BINARY_OP_ADD_INT | 4,413,980 | 1.2% | 54.9% |
| BINARY_OP_ADD_INT STORE_FAST | 4,409,460 | 1.2% | 56.1% |
| JUMP_FORWARD YIELD_VALUE | 4,094,720 | 1.1% | 57.2% |
| LOAD_CONST JUMP_FORWARD | 4,094,720 | 1.1% | 58.4% |
| ENTER_EXECUTOR LOAD_CONST | 4,054,160 | 1.1% | 59.5% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 3,775,740 | 1.1% | 60.6% |
| RETURN_VALUE TO_BOOL_BOOL | 3,681,980 | 1.0% | 61.6% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 3,658,660 | 1.0% | 62.6% |
| RETURN_VALUE LOAD_CONST | 3,602,380 | 1.0% | 63.6% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,528,900 | 1.0% | 64.6% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 3,485,900 | 1.0% | 65.6% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 3,428,900 | 1.0% | 66.5% |
| COMPARE_OP_INT RETURN_VALUE | 3,394,480 | 0.9% | 67.5% |
| BINARY_SUBSCR_LIST_INT CALL_LEN | 3,394,460 | 0.9% | 68.4% |
| STORE_FAST ENTER_EXECUTOR | 3,194,140 | 0.9% | 69.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 3,062,500 | 0.9% | 70.1% |
| LOAD_CONST STORE_FAST | 3,035,800 | 0.8% | 71.0% |
| FOR_ITER_LIST STORE_FAST | 2,849,920 | 0.8% | 71.8% |
| BINARY_SUBSCR_LIST_INT LOAD_GLOBAL_MODULE | 2,820,920 | 0.8% | 72.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 2,625,620 | 0.7% | 73.3% |
| ENTER_EXECUTOR BINARY_SUBSCR_GETITEM | 2,459,980 | 0.7% | 74.0% |
| POP_JUMP_IF_FALSE LOAD_CONST | 2,223,560 | 0.6% | 74.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 2,221,220 | 0.6% | 75.2% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_GETITEM | 2,150,380 | 0.6% | 75.8% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 2,022,020 | 0.6% | 76.4% |
| ENTER_EXECUTOR LOAD_FAST | 1,763,660 | 0.5% | 76.9% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 1,756,540 | 0.5% | 77.3% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 1,684,760 | 0.5% | 77.8% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,664,400 | 0.5% | 78.3% |
| LOAD_DEREF LOAD_FAST | 1,587,160 | 0.4% | 78.7% |
| LOAD_FAST CONTAINS_OP | 1,587,160 | 0.4% | 79.2% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 1,366,840 | 0.4% | 79.5% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 1,335,200 | 0.4% | 79.9% |
| CALL_BUILTIN_CLASS GET_ITER | 1,319,300 | 0.4% | 80.3% |
| STORE_FAST LOAD_CONST | 1,314,960 | 0.4% | 80.6% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 1,309,200 | 0.4% | 81.0% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 1,277,960 | 0.4% | 81.4% |
| GET_ITER FOR_ITER_RANGE | 1,247,520 | 0.3% | 81.7% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 1,236,480 | 0.3% | 82.1% |
| GET_ITER FOR_ITER_LIST | 1,210,460 | 0.3% | 82.4% |
| LOAD_FAST GET_ITER | 1,209,640 | 0.3% | 82.7% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 1,191,680 | 0.3% | 83.1% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 1,180,700 | 0.3% | 83.4% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 1,163,180 | 0.3% | 83.7% |
| FOR_ITER_RANGE STORE_FAST | 1,121,820 | 0.3% | 84.0% |
| LOAD_DEREF BINARY_SUBSCR_LIST_INT | 1,115,180 | 0.3% | 84.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 1,109,420 | 0.3% | 84.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_DEREF | 1,096,760 | 0.3% | 85.0% |
| RETURN_CONST TO_BOOL_BOOL | 1,077,760 | 0.3% | 85.3% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,061,840 | 0.3% | 85.5% |
| LOAD_FAST COMPARE_OP_INT | 1,055,920 | 0.3% | 85.8% |
| BINARY_SUBSCR_LIST_INT CONTAINS_OP | 1,032,900 | 0.3% | 86.1% |
| RETURN_VALUE LOAD_ATTR_INSTANCE_VALUE | 1,003,680 | 0.3% | 86.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,000,220 | 0.3% | 86.7% |
| ENTER_EXECUTOR RETURN_CONST | 978,880 | 0.3% | 87.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_BUILTIN | 974,020 | 0.3% | 87.2% |
| RETURN_CONST INTERPRETER_EXIT | 958,280 | 0.3% | 87.5% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 958,200 | 0.3% | 87.8% |
| STORE_FAST LOAD_DEREF | 957,740 | 0.3% | 88.0% |
| CACHE POP_TOP | 957,520 | 0.3% | 88.3% |
| POP_TOP RESUME_CHECK | 957,480 | 0.3% | 88.6% |
| LOAD_FAST FOR_ITER_LIST | 957,480 | 0.3% | 88.8% |
| COPY_FREE_VARS RETURN_GENERATOR | 957,440 | 0.3% | 89.1% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 957,420 | 0.3% | 89.4% |
| RETURN_GENERATOR CALL_BUILTIN_FAST_WITH_KEYWORDS | 957,400 | 0.3% | 89.6% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 954,800 | 0.3% | 89.9% |
| POP_JUMP_IF_FALSE RETURN_CONST | 942,540 | 0.3% | 90.2% |
| RETURN_VALUE CALL_LEN | 932,440 | 0.3% | 90.4% |
| LOAD_CONST YIELD_VALUE | 915,500 | 0.3% | 90.7% |
| LOAD_ATTR_INSTANCE_VALUE CALL_BUILTIN_CLASS | 888,000 | 0.2% | 90.9% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 817,860 | 0.2% | 91.1% |
| SWAP SWAP | 815,960 | 0.2% | 91.4% |
| SWAP STORE_SUBSCR_LIST_INT | 815,800 | 0.2% | 91.6% |
| COPY COPY | 815,480 | 0.2% | 91.8% |
| COPY BINARY_SUBSCR_LIST_INT | 815,320 | 0.2% | 92.1% |
| BINARY_OP_SUBTRACT_INT SWAP | 809,740 | 0.2% | 92.3% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 784,940 | 0.2% | 92.5% |
| LOAD_ATTR_INSTANCE_VALUE GET_ITER | 696,220 | 0.2% | 92.7% |
| ENTER_EXECUTOR FOR_ITER_LIST | 677,340 | 0.2% | 92.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 273,600 | 99.2% |
| BINARY_OP_ADD_INT | 2,040 | 0.7% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 203,700 | 73.9% |
| LIST_APPEND | 71,980 | 26.1% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,192,640 | 95.0% |
| POP_TOP | 957,520 | 5.0% |
| RESUME | 140 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 680 | 32.1% |
| LOAD_FAST_LOAD_FAST | 680 | 32.1% |
| LOAD_FAST | 440 | 20.8% |
| COPY | 160 | 7.5% |
| LOAD_DEREF | 120 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 620 | 29.2% |
| LOAD_CONST | 460 | 21.7% |
| BINARY_SUBSCR_GETITEM | 260 | 12.3% |
| CALL | 140 | 6.6% |
| LOAD_GLOBAL | 100 | 4.7% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 156,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 156,680 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,319,300 | 40.5% |
| LOAD_FAST | 1,209,640 | 37.1% |
| LOAD_ATTR_INSTANCE_VALUE | 696,220 | 21.4% |
| RETURN_VALUE | 31,340 | 1.0% |
| LOAD_GLOBAL_MODULE | 920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 1,247,520 | 38.3% |
| FOR_ITER_LIST | 1,210,460 | 37.1% |
| CALL_PY_EXACT_ARGS | 557,400 | 17.1% |
| EXTENDED_ARG | 138,240 | 4.2% |
| LOAD_FAST_AND_CLEAR | 104,320 | 3.2% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 18,191,760 | 95.0% |
| RETURN_CONST | 958,280 | 5.0% |
| RETURN_VALUE | 260 | 0.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 557,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 557,400 | 100.0% |
| LOAD_FAST_CHECK | 80 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 56,960 | 99.3% |
| JUMP_BACKWARD | 300 | 0.5% |
| POP_TOP | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 57,180 | 99.7% |
| LOAD_DEREF | 80 | 0.1% |
| LOAD_GLOBAL | 80 | 0.1% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 18,191,720 | 93.0% |
| CACHE | 957,520 | 4.9% |
| RETURN_CONST | 184,620 | 0.9% |
| CALL_METHOD_DESCRIPTOR_O | 122,180 | 0.6% |
| SWAP | 81,280 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 18,209,980 | 93.1% |
| RESUME_CHECK | 957,480 | 4.9% |
| RETURN_CONST | 193,880 | 1.0% |
| RETURN_VALUE | 81,280 | 0.4% |
| LOAD_GLOBAL_MODULE | 72,800 | 0.4% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 580 | 69.0% |
| LOAD_DEREF | 160 | 19.0% |
| LOAD_ATTR | 100 | 11.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 680 | 81.0% |
| LOAD_FAST | 160 | 19.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 957,440 | 100.0% |
| CALL_PY_EXACT_ARGS | 60 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 957,400 | 100.0% |
| CALL | 80 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 5,622,960 | 57.3% |
| COMPARE_OP_INT | 3,394,480 | 34.6% |
| LOAD_FAST | 389,840 | 4.0% |
| EXIT_INIT_CHECK | 156,680 | 1.6% |
| RETURN_VALUE | 104,360 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,681,980 | 37.5% |
| LOAD_CONST | 3,602,380 | 36.7% |
| LOAD_ATTR_INSTANCE_VALUE | 1,003,680 | 10.2% |
| CALL_LEN | 932,440 | 9.5% |
| STORE_FAST | 321,200 | 3.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 160 | 40.0% |
| LOAD_FAST | 120 | 30.0% |
| LOAD_ATTR | 40 | 10.0% |
| LOAD_FAST_LOAD_FAST | 40 | 10.0% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 160 | 40.0% |
| LOAD_FAST | 80 | 20.0% |
| LOAD_FAST_LOAD_FAST | 60 | 15.0% |
| JUMP_BACKWARD | 40 | 10.0% |
| STORE_SUBSCR_DICT | 40 | 10.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 680 | 70.8% |
| LOAD_FAST | 160 | 16.7% |
| RETURN_CONST | 120 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 480 | 50.0% |
| POP_JUMP_IF_FALSE | 340 | 35.4% |
| POP_JUMP_IF_TRUE | 140 | 14.6% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,080 | 74.4% |
| LOAD_CONST | 1,320 | 7.5% |
| BUILD_LIST | 1,280 | 7.3% |
| BINARY_OP_SUBTRACT_INT | 840 | 4.8% |
| BINARY_OP | 620 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,980 | 79.5% |
| STORE_FAST | 1,060 | 6.0% |
| LOAD_FAST | 700 | 4.0% |
| BINARY_OP | 620 | 3.5% |
| BINARY_OP_ADD_INT | 580 | 3.3% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 242,000 | 49.6% |
| STORE_FAST | 136,960 | 28.1% |
| SWAP | 104,320 | 21.4% |
| LOAD_FAST_LOAD_FAST | 2,080 | 0.4% |
| LOAD_CONST | 1,280 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 273,920 | 56.2% |
| LOAD_FAST | 104,960 | 21.5% |
| SWAP | 104,320 | 21.4% |
| CALL_ALLOC_AND_ENTER_INIT | 2,000 | 0.4% |
| BINARY_OP | 1,280 | 0.3% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 620 | 96.9% |
| STORE_ATTR | 20 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 557,400 | 90.5% |
| LOAD_FAST_LOAD_FAST | 39,840 | 6.5% |
| LOAD_GLOBAL_MODULE | 18,540 | 3.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 557,400 | 90.5% |
| LIST_APPEND | 31,520 | 5.1% |
| CALL_LIST_APPEND | 18,520 | 3.0% |
| STORE_FAST | 5,720 | 0.9% |
| CALL_PY_EXACT_ARGS | 1,400 | 0.2% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,680 | 27.5% |
| LOAD_ATTR_INSTANCE_VALUE | 800 | 13.1% |
| PUSH_NULL | 680 | 11.1% |
| LOAD_FAST_LOAD_FAST | 440 | 7.2% |
| LOAD_ATTR | 420 | 6.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,720 | 28.1% |
| CALL_PY_EXACT_ARGS | 900 | 14.7% |
| CALL_BUILTIN_CLASS | 620 | 10.1% |
| GET_ITER | 500 | 8.2% |
| RESUME | 440 | 7.2% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 50.0% |
| LOAD_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 50.0% |
| RESUME_CHECK | 60 | 37.5% |
| RESUME | 20 | 12.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 17,640 | 91.9% |
| ENTER_EXECUTOR | 1,560 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 18,560 | 96.7% |
| RESUME_CHECK | 620 | 3.2% |
| RESUME | 20 | 0.1% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 600 | 38.5% |
| LOAD_FAST_LOAD_FAST | 240 | 15.4% |
| LOAD_GLOBAL | 200 | 12.8% |
| LOAD_GLOBAL_MODULE | 200 | 12.8% |
| LOAD_ATTR | 100 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 680 | 43.6% |
| POP_JUMP_IF_FALSE | 460 | 29.5% |
| POP_JUMP_IF_TRUE | 300 | 19.2% |
| COMPARE_OP_STR | 100 | 6.4% |
| RETURN_VALUE | 20 | 1.3% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,587,160 | 59.3% |
| BINARY_SUBSCR_LIST_INT | 1,032,900 | 38.6% |
| RETURN_VALUE | 56,280 | 2.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,420 | 0.1% |
| BINARY_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,022,020 | 75.5% |
| POP_JUMP_IF_TRUE | 654,380 | 24.4% |
| RETURN_VALUE | 1,440 | 0.1% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 815,480 | 50.0% |
| LOAD_FAST_LOAD_FAST | 642,500 | 39.4% |
| BINARY_SUBSCR_LIST_INT | 172,960 | 10.6% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 815,480 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 815,320 | 50.0% |
| BINARY_SUBSCR | 160 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 557,380 | 58.2% |
| ENTER_EXECUTOR | 400,040 | 41.8% |
| CALL_FUNCTION_EX | 80 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 957,440 | 100.0% |
| RESUME_CHECK | 60 | 0.0% |
| RESUME | 20 | 0.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 18,209,980 | 65.2% |
| POP_JUMP_IF_TRUE | 3,485,900 | 12.5% |
| STORE_FAST | 3,194,140 | 11.4% |
| ENTER_EXECUTOR | 1,277,960 | 4.6% |
| POP_JUMP_IF_FALSE | 1,163,180 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 13,181,220 | 47.2% |
| LOAD_CONST | 4,054,160 | 14.5% |
| BINARY_SUBSCR_GETITEM | 2,459,980 | 8.8% |
| LOAD_FAST | 1,763,660 | 6.3% |
| ENTER_EXECUTOR | 1,277,960 | 4.6% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 138,240 | 83.0% |
| ENTER_EXECUTOR | 26,620 | 16.0% |
| JUMP_BACKWARD | 1,500 | 0.9% |
| FOR_ITER_LIST | 260 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 137,260 | 82.4% |
| ENTER_EXECUTOR | 26,560 | 15.9% |
| FOR_ITER_RANGE | 2,440 | 1.5% |
| JUMP_BACKWARD | 320 | 0.2% |
| FOR_ITER | 40 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 720 | 46.2% |
| GET_ITER | 680 | 43.6% |
| SWAP | 80 | 5.1% |
| EXTENDED_ARG | 40 | 2.6% |
| LOAD_FAST | 40 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 680 | 43.6% |
| FOR_ITER_RANGE | 520 | 33.3% |
| FOR_ITER_LIST | 260 | 16.7% |
| STORE_FAST_LOAD_FAST | 80 | 5.1% |
| STORE_DEREF | 20 | 1.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,640 | 30.1% |
| STORE_FAST | 6,380 | 28.9% |
| POP_TOP | 2,600 | 11.8% |
| POP_JUMP_IF_FALSE | 1,620 | 7.4% |
| ENTER_EXECUTOR | 1,420 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 11,520 | 52.3% |
| FOR_ITER_LIST | 6,660 | 30.2% |
| EXTENDED_ARG | 1,500 | 6.8% |
| ENTER_EXECUTOR | 1,340 | 6.1% |
| FOR_ITER | 720 | 3.3% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,094,720 | 98.4% |
| STORE_FAST | 53,900 | 1.3% |
| CALL_STR_1 | 7,640 | 0.2% |
| CALL_BUILTIN_CLASS | 2,520 | 0.1% |
| POP_JUMP_IF_FALSE | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 4,094,720 | 98.4% |
| LOAD_FAST | 40,320 | 1.0% |
| LOAD_GLOBAL_BUILTIN | 12,080 | 0.3% |
| STORE_FAST | 10,240 | 0.2% |
| LOAD_FAST_LOAD_FAST | 1,420 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 71,980 | 68.3% |
| BUILD_TUPLE | 31,520 | 29.9% |
| BUILD_LIST | 940 | 0.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 880 | 0.8% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 104,080 | 98.8% |
| JUMP_BACKWARD | 1,260 | 1.2% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,240 | 68.1% |
| LOAD_FAST_LOAD_FAST | 360 | 7.6% |
| RETURN_VALUE | 240 | 5.0% |
| LOAD_GLOBAL | 200 | 4.2% |
| LOAD_GLOBAL_MODULE | 200 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,260 | 26.5% |
| LOAD_FAST | 820 | 17.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 680 | 14.3% |
| CALL | 420 | 8.8% |
| STORE_FAST | 320 | 6.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 4,634,040 | 19.0% |
| LOAD_FAST | 4,467,960 | 18.3% |
| ENTER_EXECUTOR | 4,054,160 | 16.6% |
| RETURN_VALUE | 3,602,380 | 14.8% |
| POP_JUMP_IF_FALSE | 2,223,560 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 5,462,080 | 22.4% |
| BINARY_OP_ADD_INT | 4,413,980 | 18.1% |
| JUMP_FORWARD | 4,094,720 | 16.8% |
| BINARY_SUBSCR_LIST_INT | 3,775,740 | 15.5% |
| STORE_FAST | 3,035,800 | 12.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,096,760 | 38.3% |
| STORE_FAST | 957,740 | 33.5% |
| ENTER_EXECUTOR | 623,600 | 21.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 148,460 | 5.2% |
| LOAD_FAST | 29,380 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,587,160 | 55.5% |
| BINARY_SUBSCR_LIST_INT | 1,115,180 | 39.0% |
| CALL_PY_EXACT_ARGS | 159,280 | 5.6% |
| PUSH_NULL | 160 | 0.0% |
| BINARY_SUBSCR | 120 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 11,003,160 | 22.9% |
| STORE_FAST | 8,710,960 | 18.2% |
| RESUME_CHECK | 6,927,540 | 14.4% |
| LOAD_GLOBAL_BUILTIN | 5,241,540 | 10.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,430,280 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 13,736,940 | 28.6% |
| BINARY_SUBSCR_LIST_INT | 10,806,080 | 22.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,155,360 | 10.8% |
| LOAD_CONST | 4,467,960 | 9.3% |
| CALL_PY_EXACT_ARGS | 4,424,080 | 9.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 104,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 104,320 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 40 | 50.0% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 50.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,664,400 | 20.3% |
| ENTER_EXECUTOR | 1,236,480 | 15.1% |
| RESUME_CHECK | 1,191,680 | 14.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,109,420 | 13.5% |
| STORE_FAST | 954,800 | 11.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 2,150,380 | 26.2% |
| COMPARE_OP_INT | 1,756,540 | 21.4% |
| CALL_PY_EXACT_ARGS | 1,180,700 | 14.4% |
| LOAD_ATTR_INSTANCE_VALUE | 1,061,840 | 12.9% |
| COPY | 642,500 | 7.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,340 | 31.6% |
| POP_JUMP_IF_FALSE | 560 | 13.2% |
| LOAD_FAST | 480 | 11.3% |
| POP_TOP | 240 | 5.7% |
| FOR_ITER_RANGE | 220 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,200 | 28.3% |
| LOAD_GLOBAL_BUILTIN | 920 | 21.7% |
| LOAD_FAST | 640 | 15.1% |
| LOAD_FAST_LOAD_FAST | 480 | 11.3% |
| LOAD_CONST | 260 | 6.1% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 127,620 | 99.0% |
| CALL_PY_WITH_DEFAULTS | 1,240 | 1.0% |
| CALL | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 128,920 | 100.0% |
| RESUME | 20 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 3,528,900 | 41.0% |
| COMPARE_OP_INT | 3,062,500 | 35.5% |
| CONTAINS_OP | 2,022,020 | 23.5% |
| COMPARE_OP_STR | 2,100 | 0.0% |
| COMPARE_OP | 460 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,223,560 | 25.8% |
| LOAD_FAST | 2,221,220 | 25.8% |
| LOAD_FAST_LOAD_FAST | 1,664,400 | 19.3% |
| ENTER_EXECUTOR | 1,163,180 | 13.5% |
| RETURN_CONST | 942,540 | 10.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 339,500 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 336,940 | 99.2% |
| LOAD_GLOBAL_BUILTIN | 2,480 | 0.7% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 5,689,780 | 73.7% |
| TO_BOOL_BOOL | 1,366,840 | 17.7% |
| CONTAINS_OP | 654,380 | 8.5% |
| COMPARE_OP_STR | 6,680 | 0.1% |
| COMPARE_OP | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,485,900 | 45.2% |
| LOAD_FAST | 2,625,620 | 34.0% |
| LOAD_FAST_LOAD_FAST | 784,940 | 10.2% |
| LOAD_GLOBAL_BUILTIN | 560,600 | 7.3% |
| LOAD_CONST | 217,260 | 2.8% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 978,880 | 41.2% |
| POP_JUMP_IF_FALSE | 942,540 | 39.6% |
| POP_TOP | 193,880 | 8.2% |
| STORE_ATTR_INSTANCE_VALUE | 156,720 | 6.6% |
| STORE_SUBSCR_LIST_INT | 104,940 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,077,760 | 45.3% |
| INTERPRETER_EXIT | 958,280 | 40.3% |
| POP_TOP | 184,620 | 7.8% |
| EXIT_INIT_CHECK | 156,680 | 6.6% |
| TO_BOOL | 120 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 557,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 557,400 | 100.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280 | 50.0% |
| LOAD_FAST_LOAD_FAST | 280 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 280 | 50.0% |
| LOAD_FAST | 80 | 14.3% |
| RETURN_CONST | 80 | 14.3% |
| LOAD_FAST_LOAD_FAST | 60 | 10.7% |
| LOAD_CONST | 40 | 7.1% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 139,340 | 100.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 139,360 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,409,460 | 27.4% |
| LOAD_CONST | 3,035,800 | 18.9% |
| FOR_ITER_LIST | 2,849,920 | 17.7% |
| BINARY_SUBSCR_LIST_INT | 1,335,200 | 8.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,309,200 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,710,960 | 54.2% |
| ENTER_EXECUTOR | 3,194,140 | 19.9% |
| LOAD_CONST | 1,314,960 | 8.2% |
| LOAD_DEREF | 957,740 | 6.0% |
| LOAD_FAST_LOAD_FAST | 954,800 | 5.9% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 71,960 | 68.7% |
| FOR_ITER_LIST | 32,700 | 31.2% |
| FOR_ITER | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 71,940 | 68.7% |
| LOAD_GLOBAL_MODULE | 31,500 | 30.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,140 | 1.1% |
| LOAD_ATTR | 120 | 0.1% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 72,000 | 99.9% |
| UNPACK_SEQUENCE | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,040 | 98.6% |
| LOAD_GLOBAL_MODULE | 940 | 1.3% |
| LOAD_GLOBAL | 80 | 0.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 815,960 | 40.3% |
| BINARY_OP_SUBTRACT_INT | 809,740 | 40.0% |
| BUILD_LIST | 104,320 | 5.2% |
| LOAD_FAST_AND_CLEAR | 104,320 | 5.2% |
| ENTER_EXECUTOR | 103,560 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 815,960 | 40.3% |
| STORE_SUBSCR_LIST_INT | 815,800 | 40.3% |
| BUILD_LIST | 104,320 | 5.2% |
| STORE_FAST | 103,680 | 5.1% |
| POP_TOP | 81,280 | 4.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 33.3% |
| BINARY_SUBSCR | 20 | 16.7% |
| LOAD_ATTR | 20 | 16.7% |
| BINARY_SUBSCR_DICT | 20 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 50.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 13,181,220 | 72.5% |
| JUMP_FORWARD | 4,094,720 | 22.5% |
| LOAD_CONST | 915,500 | 5.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 300 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 18,191,760 | 100.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 440 | 62.9% |
| CACHE | 140 | 20.0% |
| POP_TOP | 40 | 5.7% |
| CALL_FUNCTION_EX | 20 | 2.9% |
| CALL_KW | 20 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 42.9% |
| LOAD_GLOBAL | 180 | 25.7% |
| LOAD_FAST_LOAD_FAST | 120 | 17.1% |
| POP_TOP | 40 | 5.7% |
| LOAD_CONST | 40 | 5.7% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,413,980 | 97.8% |
| CALL_LEN | 87,000 | 1.9% |
| LOAD_FAST_LOAD_FAST | 5,920 | 0.1% |
| LOAD_ATTR_INSTANCE_VALUE | 2,800 | 0.1% |
| LOAD_FAST | 760 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,409,460 | 97.7% |
| COMPARE_OP_INT | 87,000 | 1.9% |
| SWAP | 6,140 | 0.1% |
| CALL_BUILTIN_CLASS | 3,480 | 0.1% |
| LOAD_CONST | 2,480 | 0.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,760 | 68.0% |
| LOAD_FAST | 600 | 14.8% |
| BINARY_OP_SUBTRACT_INT | 600 | 14.8% |
| BINARY_OP | 100 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,440 | 84.7% |
| LOAD_FAST | 620 | 15.3% |


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
| LOAD_CONST | 817,860 | 99.8% |
| LOAD_FAST_LOAD_FAST | 1,600 | 0.2% |
| BINARY_OP | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 809,740 | 98.8% |
| CALL_BUILTIN_CLASS | 2,760 | 0.3% |
| STORE_FAST | 2,480 | 0.3% |
| LOAD_CONST | 2,460 | 0.3% |
| BINARY_OP | 840 | 0.1% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,640 | 75.5% |
| BUILD_TUPLE | 1,120 | 23.2% |
| BINARY_SUBSCR | 60 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,620 | 75.1% |
| LOAD_ATTR_INSTANCE_VALUE | 1,120 | 23.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 40 | 0.8% |
| LOAD_ATTR | 20 | 0.4% |
| UNPACK_SEQUENCE | 20 | 0.4% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,459,980 | 53.2% |
| LOAD_FAST_LOAD_FAST | 2,150,380 | 46.5% |
| LOAD_FAST | 11,840 | 0.3% |
| BINARY_SUBSCR | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,622,460 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,806,080 | 63.0% |
| LOAD_CONST | 3,775,740 | 22.0% |
| LOAD_DEREF | 1,115,180 | 6.5% |
| COPY | 815,320 | 4.8% |
| LOAD_FAST_LOAD_FAST | 640,600 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 5,622,960 | 32.8% |
| CALL_LEN | 3,394,460 | 19.8% |
| LOAD_GLOBAL_MODULE | 2,820,920 | 16.4% |
| LOAD_CONST | 1,684,760 | 9.8% |
| STORE_FAST | 1,335,200 | 7.8% |


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,640 | 99.1% |
| BINARY_SUBSCR | 80 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,720 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 127,580 | 100.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 127,580 | 100.0% |
| CALL | 40 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 71,640 | 45.7% |
| ENTER_EXECUTOR | 49,540 | 31.6% |
| LOAD_CONST | 32,180 | 20.5% |
| BUILD_LIST | 2,000 | 1.3% |
| LOAD_FAST | 1,200 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 156,680 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 888,000 | 63.9% |
| LOAD_CONST | 422,880 | 30.4% |
| STORE_FAST | 31,320 | 2.3% |
| CALL_BUILTIN_CLASS | 31,320 | 2.3% |
| LOAD_FAST | 8,440 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,319,300 | 95.0% |
| STORE_FAST | 36,260 | 2.6% |
| CALL_BUILTIN_CLASS | 31,320 | 2.3% |
| JUMP_FORWARD | 2,520 | 0.2% |
| CALL | 20 | 0.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 957,400 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 957,420 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 3,394,460 | 71.9% |
| RETURN_VALUE | 932,440 | 19.8% |
| LOAD_FAST | 394,040 | 8.3% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,634,040 | 98.2% |
| BINARY_OP_ADD_INT | 87,000 | 1.8% |
| BINARY_OP | 20 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 206,200 | 69.0% |
| ENTER_EXECUTOR | 72,920 | 24.4% |
| BUILD_TUPLE | 18,520 | 6.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,120 | 0.4% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 279,680 | 93.6% |
| LOAD_FAST | 18,540 | 6.2% |
| JUMP_BACKWARD | 600 | 0.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 860 | 66.2% |
| LOAD_ATTR_METHOD_NO_DICT | 360 | 27.7% |
| CALL | 80 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 880 | 67.7% |
| YIELD_VALUE | 300 | 23.1% |
| STORE_FAST | 120 | 9.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 640 | 94.1% |
| CALL | 40 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 680 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_LAZY_DICT | 600 | 96.8% |
| CALL | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 620 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 122,160 | 99.9% |
| RETURN_GENERATOR | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 122,180 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,424,080 | 67.1% |
| LOAD_FAST_LOAD_FAST | 1,180,700 | 17.9% |
| GET_ITER | 557,400 | 8.4% |
| LOAD_DEREF | 159,280 | 2.4% |
| BINARY_SUBSCR_TUPLE_INT | 127,580 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,912,700 | 89.6% |
| COPY_FREE_VARS | 557,380 | 8.4% |
| MAKE_CELL | 127,620 | 1.9% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 101,680 | 98.8% |
| LOAD_FAST | 1,200 | 1.2% |
| CALL | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 101,720 | 98.8% |
| MAKE_CELL | 1,240 | 1.2% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 7,600 | 99.5% |
| CALL | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 7,640 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,462,080 | 45.0% |
| LOAD_GLOBAL_MODULE | 3,658,660 | 30.1% |
| LOAD_FAST_LOAD_FAST | 1,756,540 | 14.5% |
| LOAD_FAST | 1,055,920 | 8.7% |
| LOAD_ATTR_CLASS | 125,280 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,689,780 | 46.8% |
| RETURN_VALUE | 3,394,480 | 27.9% |
| POP_JUMP_IF_FALSE | 3,062,500 | 25.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,640 | 98.4% |
| COMPARE_OP | 100 | 1.1% |
| LOAD_FAST_LOAD_FAST | 40 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,680 | 76.1% |
| POP_JUMP_IF_FALSE | 2,100 | 23.9% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,210,460 | 40.1% |
| LOAD_FAST | 957,480 | 31.7% |
| ENTER_EXECUTOR | 677,340 | 22.4% |
| EXTENDED_ARG | 137,260 | 4.5% |
| SWAP | 31,960 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,849,920 | 94.3% |
| LOAD_FAST | 137,240 | 4.5% |
| STORE_FAST_LOAD_FAST | 32,700 | 1.1% |
| LOAD_GLOBAL_BUILTIN | 420 | 0.0% |
| EXTENDED_ARG | 260 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,247,520 | 93.4% |
| SWAP | 72,280 | 5.4% |
| JUMP_BACKWARD | 11,520 | 0.9% |
| EXTENDED_ARG | 2,440 | 0.2% |
| ENTER_EXECUTOR | 1,400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,121,820 | 84.0% |
| STORE_DEREF | 139,340 | 10.4% |
| STORE_FAST_LOAD_FAST | 71,960 | 5.4% |
| LOAD_FAST | 1,300 | 0.1% |
| RETURN_CONST | 340 | 0.0% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 125,320 | 99.9% |
| LOAD_ATTR | 100 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 125,280 | 99.9% |
| COMPARE_OP | 80 | 0.1% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,736,940 | 86.5% |
| LOAD_FAST_LOAD_FAST | 1,061,840 | 6.7% |
| RETURN_VALUE | 1,003,680 | 6.3% |
| STORE_FAST_LOAD_FAST | 71,940 | 0.5% |
| LOAD_ATTR | 1,260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,003,160 | 69.3% |
| STORE_FAST | 1,309,200 | 8.2% |
| LOAD_DEREF | 1,096,760 | 6.9% |
| CALL_BUILTIN_CLASS | 888,000 | 5.6% |
| GET_ITER | 696,220 | 4.4% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600 | 96.8% |
| LOAD_ATTR | 20 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 600 | 96.8% |
| CALL | 20 | 3.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 225,400 | 64.4% |
| BINARY_SUBSCR_LIST_INT | 122,160 | 34.9% |
| STORE_FAST_LOAD_FAST | 1,140 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,120 | 0.3% |
| LOAD_ATTR | 220 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 348,080 | 99.4% |
| LOAD_CONST | 940 | 0.3% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 640 | 0.2% |
| CALL_METHOD_DESCRIPTOR_FAST | 360 | 0.1% |
| CALL | 100 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,155,360 | 89.1% |
| LOAD_ATTR_INSTANCE_VALUE | 628,460 | 10.9% |
| LOAD_ATTR | 680 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,430,280 | 76.6% |
| LOAD_FAST_LOAD_FAST | 1,109,420 | 19.2% |
| LOAD_DEREF | 148,460 | 2.6% |
| CALL_PY_EXACT_ARGS | 96,240 | 1.7% |
| CALL | 100 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 480 | 82.8% |
| LOAD_ATTR | 100 | 17.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 580 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,428,900 | 58.8% |
| ENTER_EXECUTOR | 974,020 | 16.7% |
| POP_JUMP_IF_TRUE | 560,600 | 9.6% |
| STORE_FAST | 541,120 | 9.3% |
| POP_JUMP_IF_FALSE | 189,900 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,241,540 | 89.9% |
| LOAD_CONST | 441,700 | 7.6% |
| LOAD_FAST_LOAD_FAST | 117,560 | 2.0% |
| LOAD_GLOBAL_BUILTIN | 31,320 | 0.5% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 2,820,920 | 63.5% |
| LOAD_FAST | 1,000,220 | 22.5% |
| STORE_FAST | 181,840 | 4.1% |
| POP_JUMP_IF_FALSE | 145,920 | 3.3% |
| POP_TOP | 72,800 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 3,658,660 | 82.4% |
| LOAD_FAST_LOAD_FAST | 368,180 | 8.3% |
| LOAD_ATTR_CLASS | 125,320 | 2.8% |
| LOAD_FAST | 80,040 | 1.8% |
| RETURN_VALUE | 52,420 | 1.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 18,192,640 | 60.5% |
| CALL_PY_EXACT_ARGS | 5,912,700 | 19.7% |
| BINARY_SUBSCR_GETITEM | 4,622,460 | 15.4% |
| POP_TOP | 957,480 | 3.2% |
| CALL_ALLOC_AND_ENTER_INIT | 156,680 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 18,191,720 | 60.5% |
| LOAD_FAST | 6,927,540 | 23.0% |
| LOAD_GLOBAL_BUILTIN | 3,428,900 | 11.4% |
| LOAD_FAST_LOAD_FAST | 1,191,680 | 4.0% |
| LOAD_CONST | 277,380 | 0.9% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 253,800 | 53.8% |
| LOAD_FAST | 217,960 | 46.2% |
| STORE_ATTR | 280 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 216,880 | 45.9% |
| RETURN_CONST | 156,720 | 33.2% |
| LOAD_FAST_LOAD_FAST | 96,580 | 20.5% |
| LOAD_CONST | 1,240 | 0.3% |
| BUILD_MAP | 620 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,080 | 99.7% |
| STORE_SUBSCR | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 12,120 | 100.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 815,800 | 87.2% |
| LOAD_FAST | 104,920 | 11.2% |
| LOAD_ATTR_INSTANCE_VALUE | 12,080 | 1.3% |
| LOAD_FAST_LOAD_FAST | 2,520 | 0.3% |
| ENTER_EXECUTOR | 540 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 636,780 | 68.0% |
| ENTER_EXECUTOR | 174,900 | 18.7% |
| RETURN_CONST | 104,940 | 11.2% |
| LOAD_FAST | 18,800 | 2.0% |
| JUMP_BACKWARD | 600 | 0.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 3,681,980 | 75.2% |
| RETURN_CONST | 1,077,760 | 22.0% |
| LOAD_FAST | 135,520 | 2.8% |
| TO_BOOL | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,528,900 | 72.1% |
| POP_JUMP_IF_TRUE | 1,366,840 | 27.9% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 71,000 | 98.6% |
| LOAD_ATTR_INSTANCE_VALUE | 900 | 1.2% |
| UNPACK_SEQUENCE | 60 | 0.1% |
| BINARY_SUBSCR_DICT | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 72,000 | 100.0% |


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
|     deferred | 16,040 | 0.3% |
|          hit | 5,335,140 | 99.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 960 | 62.3% |
| Failure | 580 | 37.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 320 | 55.2% |
| remainder | 260 | 44.8% |


</details>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,060 | 0.0% |
|          hit | 21,917,640 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,060 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,740 | 0.0% |
|          hit | 14,356,600 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,140 | 89.9% |
| Failure | 240 | 10.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class no vectorcall | 100 | 41.7% |
| wrong number arguments | 80 | 33.3% |
| cfunc noargs | 60 | 25.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 780 | 0.0% |
|          hit | 12,155,540 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 780 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 660 | 0.0% |
|          hit | 4,350,540 | 99.8% |
|         miss | 6,680 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 900 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,380 | 0.0% |
|          hit | 22,138,020 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,380 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,120 | 0.0% |
|          hit | 10,271,080 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,120 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


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
|     deferred | 280 | 0.1% |
|          hit | 472,040 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 0.0% |
|          hit | 948,140 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 480 | 0.0% |
|          hit | 4,895,740 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 480 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 0.1% |
|          hit | 72,000 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 215,443,160 | 59.9% |
| Not specialized | 16,989,600 | 4.7% |
| Specialized hits | 126,995,540 | 35.3% |
| Specialized misses | 6,680 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 16,040 | 57.7% |
| CALL | 3,740 | 13.5% |
| LOAD_ATTR | 2,380 | 8.6% |
| LOAD_GLOBAL | 2,120 | 7.6% |
| BINARY_SUBSCR | 1,060 | 3.8% |
| COMPARE_OP | 780 | 2.8% |
| FOR_ITER | 660 | 2.4% |
| TO_BOOL | 480 | 1.7% |
| STORE_ATTR | 280 | 1.0% |
| STORE_SUBSCR | 200 | 0.7% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER_RANGE | 4,240 | 63.5% |
| FOR_ITER_LIST | 2,440 | 36.5% |
| CACHE | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| MAKE_FUNCTION | 0 | 0.0% |
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
| Calls to PyEval_EvalDefault | 19,150,300 | 62.5% |
| Calls to Python functions inlined | 11,481,640 | 37.5% |
| Calls via PyEval_EvalFrame (total) | 19,150,300 | 62.5% |
| Calls via PyEval_EvalFrame (vector) | 1,020 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 19,149,280 | 62.5% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,020 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 260 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 29,214,600 | 95.4% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 2,904,300 | 22.7% |
| Frees to freelist | 2,905,560 |  |
| Allocations | 9,862,440 | 77.3% |
| Allocations to 512 bytes | 9,860,840 | 77.2% |
| Allocations to 4 kbytes | 1,600 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 10,078,838 |  |
| New values | 760 |  |
| Interpreter increfs | 329,122,180 | 97.4% |
| Interpreter decrefs | 339,973,060 | 97.1% |
| Increfs | 8,745,525 | 2.6% |
| Decrefs | 10,233,066 | 2.9% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 38,535 |  |
| Method cache misses | 805 |  |
| Method cache collisions | 544 |  |
| Method cache dunder hits | 72,473 |  |
| Method cache dunder misses | 127 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 20 | 1,980 | 160,880 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 1,340 |  |
| Traces created | 1,340 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 80 | 6.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 27,917,840 |  |
| Uops executed | 1,347,332,920 | 48.26 |

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
| <= 32 | 360 | 26.9% |
| <= 64 | 440 | 32.8% |
| <= 128 | 540 | 40.3% |


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
| <= 16 | 40 | 3.0% |
| <= 32 | 380 | 28.4% |
| <= 64 | 620 | 46.3% |
| <= 128 | 300 | 22.4% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 678,740 | 2.4% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,503,820 | 9.0% |
| <= 16 | 18,308,280 | 65.6% |
| <= 32 | 888,460 | 3.2% |
| <= 64 | 2,998,560 | 10.7% |
| <= 128 | 896,880 | 3.2% |
| <= 256 | 326,800 | 1.2% |
| <= 512 | 604,720 | 2.2% |
| <= 1,024 | 695,000 | 2.5% |
| <= 2,048 | 16,580 | 0.1% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 336,821,080 | 25.0% | 25.0% |  |
| LOAD_FAST | 134,500,300 | 10.0% | 35.0% |  |
| _POP_JUMP_IF_TRUE | 77,014,900 | 5.7% | 40.7% |  |
| STORE_FAST | 51,339,880 | 3.8% | 44.5% |  |
| _GUARD_TYPE_VERSION | 47,969,880 | 3.6% | 48.1% |  |
| LOAD_CONST | 40,810,100 | 3.0% | 51.1% |  |
| BINARY_SUBSCR_LIST_INT | 32,808,240 | 2.4% | 53.5% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 30,545,640 | 2.3% | 55.8% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 30,545,640 | 2.3% | 58.1% |  |
| _EXIT_TRACE | 27,239,100 | 2.0% | 60.1% |  |
| _ITER_CHECK_LIST | 25,361,640 | 1.9% | 62.0% |  |
| _IS_ITER_EXHAUSTED_LIST | 25,361,640 | 1.9% | 63.9% |  |
| COMPARE_OP_INT | 23,516,560 | 1.7% | 65.6% |  |
| _ITER_NEXT_LIST | 23,132,080 | 1.7% | 67.3% |  |
| LOAD_DEREF | 22,367,620 | 1.7% | 69.0% |  |
| CONTAINS_OP | 21,644,080 | 1.6% | 70.6% |  |
| _GUARD_GLOBALS_VERSION | 20,272,720 | 1.5% | 72.1% |  |
| _GUARD_BUILTINS_VERSION | 20,018,540 | 1.5% | 73.6% |  |
| _LOAD_GLOBAL_BUILTINS | 20,018,540 | 1.5% | 75.1% |  |
| _ITER_CHECK_RANGE | 19,938,340 | 1.5% | 76.5% | 3.4% |
| _IS_ITER_EXHAUSTED_RANGE | 19,259,600 | 1.4% | 78.0% |  |
| CALL_LEN | 18,750,180 | 1.4% | 79.4% |  |
| _ITER_NEXT_RANGE | 18,006,720 | 1.3% | 80.7% |  |
| _CHECK_PEP_523 | 17,578,060 | 1.3% | 82.0% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 17,578,060 | 1.3% | 83.3% |  |
| _CHECK_STACK_SPACE | 17,578,060 | 1.3% | 84.6% |  |
| _INIT_CALL_PY_EXACT_ARGS | 17,578,060 | 1.3% | 85.9% |  |
| _PUSH_FRAME | 17,578,060 | 1.3% | 87.2% |  |
| _SAVE_RETURN_OFFSET | 17,578,060 | 1.3% | 88.5% |  |
| _JUMP_TO_TOP | 17,345,060 | 1.3% | 89.8% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 17,191,460 | 1.3% | 91.1% |  |
| _GUARD_KEYS_VERSION | 17,191,460 | 1.3% | 92.4% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 17,191,460 | 1.3% | 93.6% |  |
| RESUME_CHECK | 17,168,720 | 1.3% | 94.9% |  |
| _POP_FRAME | 17,032,680 | 1.3% | 96.2% |  |
| TO_BOOL_BOOL | 16,946,340 | 1.3% | 97.4% |  |
| _POP_JUMP_IF_FALSE | 13,404,160 | 1.0% | 98.4% |  |
| POP_TOP | 3,685,060 | 0.3% | 98.7% |  |
| COPY | 2,764,560 | 0.2% | 98.9% |  |
| SWAP | 2,763,600 | 0.2% | 99.1% |  |
| _GUARD_BOTH_INT | 2,159,020 | 0.2% | 99.3% |  |
| _BINARY_OP_SUBTRACT_INT | 1,388,020 | 0.1% | 99.4% |  |
| STORE_SUBSCR_LIST_INT | 1,381,260 | 0.1% | 99.5% |  |
| LIST_APPEND | 1,333,380 | 0.1% | 99.6% |  |
| BINARY_SLICE | 1,310,880 | 0.1% | 99.7% |  |
| STORE_DEREF | 966,560 | 0.1% | 99.7% |  |
| _BINARY_OP_ADD_INT | 770,040 | 0.1% | 99.8% |  |
| BUILD_TUPLE | 572,040 | 0.0% | 99.8% |  |
| GET_ITER | 446,420 | 0.0% | 99.9% |  |
| MAKE_FUNCTION | 400,040 | 0.0% | 99.9% |  |
| SET_FUNCTION_ATTRIBUTE | 400,040 | 0.0% | 99.9% |  |
| _LOAD_GLOBAL_MODULE | 254,180 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 232,780 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 156,840 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 61,120 | 0.0% | 100.0% |  |
| BUILD_LIST | 21,300 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_STR_INT | 15,520 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 15,520 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 11,220 | 0.0% | 100.0% |  |
| MAKE_CELL | 9,300 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 9,300 | 0.0% | 100.0% |  |
| _IS_NONE | 9,300 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 6,520 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,020 | 0.0% | 100.0% |  |
| _BINARY_OP | 1,560 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 960 | 0.0% | 100.0% |  |
| PUSH_NULL | 280 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 280 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 280 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| BINARY_SUBSCR_GETITEM | 340 |
| CALL_ALLOC_AND_ENTER_INIT | 100 |
| CALL_LIST_APPEND | 80 |
| CALL_KW | 40 |
| YIELD_VALUE | 40 |
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
Stats gathered on: 2023-11-08
