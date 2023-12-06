
# Pystats results

- benchmark: go
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 393,024,360 | 24.4% | 24.4% |  |
| LOAD_ATTR_WITH_HINT | 175,258,800 | 10.9% | 35.2% |  |
| STORE_FAST | 107,699,580 | 6.7% | 41.9% |  |
| POP_JUMP_IF_FALSE | 88,194,480 | 5.5% | 47.4% |  |
| COMPARE_OP_INT | 78,739,320 | 4.9% | 52.3% | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 71,799,600 | 4.5% | 56.7% |  |
| RESUME_CHECK | 50,783,040 | 3.1% | 59.9% | 0.0% |
| LOAD_GLOBAL_MODULE | 45,460,180 | 2.8% | 62.7% |  |
| LOAD_CONST | 43,733,340 | 2.7% | 65.4% |  |
| CALL_PY_EXACT_ARGS | 41,640,840 | 2.6% | 68.0% |  |
| LOAD_FAST_LOAD_FAST | 37,071,960 | 2.3% | 70.3% |  |
| COPY | 36,284,160 | 2.2% | 72.5% |  |
| RETURN_VALUE | 35,302,260 | 2.2% | 74.7% |  |
| POP_JUMP_IF_TRUE | 32,618,220 | 2.0% | 76.7% |  |
| TO_BOOL_BOOL | 32,267,340 | 2.0% | 78.7% | 2.0% |
| STORE_ATTR_WITH_HINT | 30,535,780 | 1.9% | 80.6% | 0.0% |
| LOAD_ATTR | 30,088,880 | 1.9% | 82.5% |  |
| POP_TOP | 25,496,340 | 1.6% | 84.1% |  |
| ENTER_EXECUTOR | 24,640,560 | 1.5% | 85.6% |  |
| SWAP | 22,061,820 | 1.4% | 87.0% |  |
| RETURN_CONST | 20,055,480 | 1.2% | 88.2% |  |
| BINARY_SUBSCR_LIST_INT | 19,751,400 | 1.2% | 89.4% | 0.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 19,350,720 | 1.2% | 90.6% | 0.0% |
| BINARY_OP_ADD_INT | 16,963,800 | 1.1% | 91.7% | 1.9% |
| BINARY_OP_SUBTRACT_INT | 15,065,940 | 0.9% | 92.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 14,102,820 | 0.9% | 93.5% |  |
| BINARY_OP | 13,807,540 | 0.9% | 94.4% |  |
| TO_BOOL_INT | 9,947,220 | 0.6% | 95.0% | 6.4% |
| STORE_SUBSCR_LIST_INT | 8,497,080 | 0.5% | 95.5% |  |
| GET_ITER | 6,706,680 | 0.4% | 95.9% |  |
| FOR_ITER_LIST | 6,663,180 | 0.4% | 96.3% |  |
| CALL_PY_WITH_DEFAULTS | 6,332,760 | 0.4% | 96.7% |  |
| CALL | 5,286,540 | 0.3% | 97.0% |  |
| STORE_GLOBAL | 5,201,940 | 0.3% | 97.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,478,400 | 0.3% | 97.6% |  |
| PUSH_NULL | 4,385,040 | 0.3% | 97.9% |  |
| LOAD_ATTR_MODULE | 4,338,880 | 0.3% | 98.2% |  |
| JUMP_FORWARD | 3,506,340 | 0.2% | 98.4% |  |
| LOAD_GLOBAL_BUILTIN | 3,074,760 | 0.2% | 98.6% |  |
| CALL_KW | 2,722,020 | 0.2% | 98.8% |  |
| CALL_LEN | 2,129,520 | 0.1% | 98.9% |  |
| STORE_FAST_STORE_FAST | 1,916,880 | 0.1% | 99.0% |  |
| UNARY_NOT | 1,887,540 | 0.1% | 99.1% |  |
| CONTAINS_OP | 1,887,540 | 0.1% | 99.3% |  |
| CALL_LIST_APPEND | 1,858,800 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,296,180 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,296,120 | 0.1% | 99.5% | 0.0% |
| LIST_APPEND | 1,008,660 | 0.1% | 99.6% |  |
| CALL_BUILTIN_CLASS | 932,460 | 0.1% | 99.6% |  |
| CALL_BUILTIN_O | 925,020 | 0.1% | 99.7% |  |
| BINARY_OP_MULTIPLY_INT | 882,960 | 0.1% | 99.8% |  |
| CALL_BUILTIN_FAST | 837,900 | 0.1% | 99.8% |  |
| BINARY_OP_ADD_FLOAT | 837,900 | 0.1% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 825,320 | 0.1% | 99.9% | 2.6% |
| COMPARE_OP_FLOAT | 796,020 | 0.0% | 100.0% | 2.4% |
| COMPARE_OP | 98,280 | 0.0% | 100.0% |  |
| BUILD_LIST | 67,800 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 53,280 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 46,140 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 46,140 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 41,160 | 0.0% | 100.0% |  |
| IS_OP | 41,160 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 36,380 | 0.0% | 100.0% | 60.4% |
| LOAD_FAST_AND_CLEAR | 33,960 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 33,960 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 24,060 | 0.0% | 100.0% |  |
| NOP | 12,060 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 12,000 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,720 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 9,720 | 0.0% | 100.0% |  |
| STORE_ATTR | 7,940 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 2,280 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 220 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 180 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 120 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 120 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 120 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 60 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_WITH_HINT | 145,158,240 | 9.0% | 9.0% |
| STORE_FAST LOAD_FAST | 88,430,820 | 5.5% | 14.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 72,792,900 | 4.5% | 19.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 59,283,600 | 3.7% | 22.7% |
| LOAD_ATTR_WITH_HINT LOAD_FAST | 44,909,940 | 2.8% | 25.5% |
| RESUME_CHECK LOAD_FAST | 42,259,020 | 2.6% | 28.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 41,640,840 | 2.6% | 30.7% |
| LOAD_ATTR_WITH_HINT STORE_FAST | 40,706,580 | 2.5% | 33.2% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 39,319,300 | 2.4% | 35.6% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 31,428,300 | 1.9% | 37.6% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 30,401,560 | 1.9% | 39.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 30,350,400 | 1.9% | 41.3% |
| LOAD_FAST LOAD_ATTR | 30,081,380 | 1.9% | 43.2% |
| LOAD_FAST RETURN_VALUE | 29,800,380 | 1.8% | 45.0% |
| RETURN_VALUE STORE_FAST | 29,795,940 | 1.8% | 46.9% |
| LOAD_FAST COPY | 26,816,100 | 1.7% | 48.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 24,573,280 | 1.5% | 50.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 23,987,640 | 1.5% | 51.6% |
| LOAD_FAST TO_BOOL_BOOL | 21,501,600 | 1.3% | 52.9% |
| STORE_ATTR_WITH_HINT LOAD_FAST | 21,309,380 | 1.3% | 54.2% |
| LOAD_ATTR LOAD_FAST | 20,898,120 | 1.3% | 55.5% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 19,431,600 | 1.2% | 56.7% |
| LOAD_ATTR_WITH_HINT LOAD_CONST | 19,116,900 | 1.2% | 57.9% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,674,780 | 1.0% | 58.9% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 16,524,060 | 1.0% | 60.0% |
| ENTER_EXECUTOR LOAD_ATTR_WITH_HINT | 16,105,920 | 1.0% | 61.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 15,255,940 | 0.9% | 61.9% |
| RETURN_CONST POP_TOP | 14,737,920 | 0.9% | 62.8% |
| LOAD_CONST BINARY_OP_ADD_INT | 13,392,000 | 0.8% | 63.7% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 13,345,880 | 0.8% | 64.5% |
| SWAP STORE_ATTR_WITH_HINT | 12,748,560 | 0.8% | 65.3% |
| COPY LOAD_ATTR_WITH_HINT | 12,748,560 | 0.8% | 66.1% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 12,603,360 | 0.8% | 66.8% |
| POP_TOP LOAD_FAST | 12,286,620 | 0.8% | 67.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 11,813,880 | 0.7% | 68.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 11,678,820 | 0.7% | 69.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 11,290,860 | 0.7% | 69.8% |
| LOAD_FAST STORE_ATTR_WITH_HINT | 10,275,740 | 0.6% | 70.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 9,354,660 | 0.6% | 71.0% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 9,193,020 | 0.6% | 71.6% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 9,166,440 | 0.6% | 72.1% |
| BINARY_OP SWAP | 9,166,440 | 0.6% | 72.7% |
| BINARY_OP_SUBTRACT_INT SWAP | 8,638,020 | 0.5% | 73.2% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 8,497,080 | 0.5% | 73.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 8,302,440 | 0.5% | 74.3% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 8,223,420 | 0.5% | 74.8% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 7,650,060 | 0.5% | 75.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_WITH_HINT | 7,499,340 | 0.5% | 75.7% |
| LOAD_CONST COMPARE_OP_INT | 7,403,140 | 0.5% | 76.2% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 7,061,280 | 0.4% | 76.6% |
| LOAD_FAST LOAD_CONST | 6,956,700 | 0.4% | 77.0% |
| BINARY_OP_ADD_INT STORE_FAST | 6,752,340 | 0.4% | 77.5% |
| GET_ITER FOR_ITER_LIST | 6,650,940 | 0.4% | 77.9% |
| FOR_ITER_LIST STORE_FAST | 6,639,120 | 0.4% | 78.3% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 6,612,680 | 0.4% | 78.7% |
| LOAD_ATTR_WITH_HINT GET_ITER | 6,571,320 | 0.4% | 79.1% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 6,380,160 | 0.4% | 79.5% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 6,332,760 | 0.4% | 79.9% |
| LOAD_ATTR CALL_PY_WITH_DEFAULTS | 6,112,620 | 0.4% | 80.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 5,985,300 | 0.4% | 80.6% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 5,897,160 | 0.4% | 81.0% |
| COPY TO_BOOL_INT | 5,844,120 | 0.4% | 81.4% |
| STORE_FAST COPY | 5,662,620 | 0.4% | 81.7% |
| COPY STORE_FAST | 5,662,620 | 0.4% | 82.1% |
| POP_TOP RETURN_CONST | 5,580,360 | 0.3% | 82.4% |
| POP_JUMP_IF_TRUE POP_TOP | 5,502,660 | 0.3% | 82.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 5,470,440 | 0.3% | 83.1% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 5,201,940 | 0.3% | 83.4% |
| BINARY_OP_ADD_INT STORE_GLOBAL | 5,201,940 | 0.3% | 83.7% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 5,156,520 | 0.3% | 84.1% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 5,131,860 | 0.3% | 84.4% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 4,778,700 | 0.3% | 84.7% |
| RETURN_CONST TO_BOOL_BOOL | 4,636,800 | 0.3% | 85.0% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 4,485,240 | 0.3% | 85.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,418,100 | 0.3% | 85.5% |
| STORE_ATTR_WITH_HINT ENTER_EXECUTOR | 4,345,140 | 0.3% | 85.8% |
| LOAD_ATTR_MODULE PUSH_NULL | 4,338,820 | 0.3% | 86.1% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 4,138,440 | 0.3% | 86.3% |
| BINARY_OP_ADD_INT SWAP | 4,137,120 | 0.3% | 86.6% |
| LOAD_ATTR_WITH_HINT BINARY_SUBSCR_LIST_INT | 4,092,360 | 0.3% | 86.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,074,720 | 0.3% | 87.1% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 4,031,580 | 0.2% | 87.3% |
| STORE_SUBSCR_LIST_INT RETURN_CONST | 3,997,620 | 0.2% | 87.6% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 3,997,620 | 0.2% | 87.8% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_INSTANCE_VALUE | 3,966,720 | 0.2% | 88.1% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 3,959,120 | 0.2% | 88.3% |
| STORE_GLOBAL LOAD_FAST | 3,917,880 | 0.2% | 88.6% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_INT | 3,775,080 | 0.2% | 88.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 3,603,300 | 0.2% | 89.0% |
| LOAD_ATTR_WITH_HINT TO_BOOL_BOOL | 3,579,480 | 0.2% | 89.2% |
| LOAD_CONST LOAD_FAST | 3,569,460 | 0.2% | 89.5% |
| ENTER_EXECUTOR LOAD_FAST | 3,567,840 | 0.2% | 89.7% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 3,547,680 | 0.2% | 89.9% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 3,183,600 | 0.2% | 90.1% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 3,153,480 | 0.2% | 90.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 3,129,060 | 0.2% | 90.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,967,540 | 0.2% | 90.7% |
| LOAD_CONST LOAD_CONST | 2,722,020 | 0.2% | 90.8% |
| LOAD_CONST CALL_KW | 2,722,020 | 0.2% | 91.0% |
| CALL_KW RESUME_CHECK | 2,722,020 | 0.2% | 91.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,300 | 57.0% |
| BINARY_SUBSCR_LIST_INT | 820 | 36.0% |
| BINARY_SUBSCR | 160 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,300 | 57.0% |
| BINARY_SUBSCR_LIST_INT | 820 | 36.0% |
| BINARY_SUBSCR | 160 | 7.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 46,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 46,140 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 6,571,320 | 98.0% |
| LOAD_ATTR_INSTANCE_VALUE | 67,680 | 1.0% |
| CALL_BUILTIN_CLASS | 33,960 | 0.5% |
| LOAD_FAST | 24,000 | 0.4% |
| LOAD_CONST | 9,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 6,650,940 | 99.2% |
| LOAD_FAST_AND_CLEAR | 33,960 | 0.5% |
| FOR_ITER_RANGE | 12,060 | 0.2% |
| FOR_ITER_TUPLE | 9,720 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,000 | 99.5% |
| POP_TOP | 60 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,000 | 99.5% |
| LOAD_DEREF | 60 | 0.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 14,737,920 | 57.8% |
| POP_JUMP_IF_TRUE | 5,502,660 | 21.6% |
| POP_JUMP_IF_FALSE | 2,638,140 | 10.3% |
| CALL_METHOD_DESCRIPTOR_O | 1,296,180 | 5.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,296,120 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,286,620 | 48.2% |
| RETURN_CONST | 5,580,360 | 21.9% |
| ENTER_EXECUTOR | 2,252,760 | 8.8% |
| LOAD_CONST | 1,887,600 | 7.4% |
| LOAD_FAST_LOAD_FAST | 1,284,060 | 5.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 4,338,820 | 98.9% |
| LOAD_FAST | 46,140 | 1.1% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,621,960 | 59.8% |
| LOAD_FAST | 883,920 | 20.2% |
| LOAD_GLOBAL_MODULE | 837,900 | 19.1% |
| LOAD_CONST | 29,220 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 12,000 | 0.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,800,380 | 84.4% |
| CONTAINS_OP | 1,887,540 | 5.3% |
| RETURN_VALUE | 1,349,400 | 3.8% |
| BINARY_OP_ADD_FLOAT | 837,900 | 2.4% |
| POP_JUMP_IF_FALSE | 775,980 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,795,940 | 84.4% |
| RETURN_VALUE | 1,349,400 | 3.8% |
| CALL_PY_EXACT_ARGS | 1,308,120 | 3.7% |
| TO_BOOL_INT | 1,249,740 | 3.5% |
| LOAD_FAST | 863,640 | 2.4% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,887,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,887,540 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 9,166,440 | 66.4% |
| LOAD_FAST | 2,621,780 | 19.0% |
| CALL_BUILTIN_CLASS | 837,900 | 6.1% |
| BINARY_OP_MULTIPLY_INT | 837,900 | 6.1% |
| LOAD_CONST | 285,420 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,166,440 | 66.4% |
| CALL | 2,621,760 | 19.0% |
| STORE_FAST | 1,135,320 | 8.2% |
| CALL_BUILTIN_O | 837,900 | 6.1% |
| BINARY_OP | 20,660 | 0.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 33,960 | 50.1% |
| STORE_ATTR_INSTANCE_VALUE | 12,120 | 17.9% |
| LOAD_FAST | 12,000 | 17.7% |
| STORE_FAST_STORE_FAST | 9,720 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 33,960 | 50.1% |
| LOAD_FAST | 21,840 | 32.2% |
| STORE_FAST | 12,000 | 17.7% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 120 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,621,960 | 49.6% |
| BINARY_OP | 2,621,760 | 49.6% |
| LOAD_CONST | 29,220 | 0.6% |
| CALL_LEN | 12,000 | 0.2% |
| CALL | 1,440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,621,820 | 49.6% |
| LOAD_FAST | 2,621,820 | 49.6% |
| RESUME_CHECK | 41,160 | 0.8% |
| CALL | 1,440 | 0.0% |
| CALL_PY_EXACT_ARGS | 100 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,722,020 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,722,020 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 30,140 | 30.7% |
| LOAD_FAST_LOAD_FAST | 30,120 | 30.6% |
| COMPARE_OP_INT | 24,120 | 24.5% |
| RETURN_VALUE | 12,000 | 12.2% |
| COMPARE_OP | 980 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 84,240 | 85.7% |
| STORE_FAST | 12,000 | 12.2% |
| COMPARE_OP | 980 | 1.0% |
| POP_JUMP_IF_TRUE | 540 | 0.5% |
| COMPARE_OP_FLOAT | 360 | 0.4% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,887,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,887,540 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,816,100 | 73.9% |
| STORE_FAST | 5,662,620 | 15.6% |
| UNARY_NOT | 1,887,540 | 5.2% |
| LOAD_CONST | 1,887,540 | 5.2% |
| SWAP | 18,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 12,748,560 | 35.1% |
| LOAD_ATTR_INSTANCE_VALUE | 8,223,420 | 22.7% |
| TO_BOOL_INT | 5,844,120 | 16.1% |
| STORE_FAST | 5,662,620 | 15.6% |
| TO_BOOL_BOOL | 1,887,540 | 5.2% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 50.0% |
| CALL | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 12,603,360 | 51.1% |
| STORE_ATTR_WITH_HINT | 4,345,140 | 17.6% |
| POP_TOP | 2,252,760 | 9.1% |
| STORE_FAST | 2,063,940 | 8.4% |
| POP_JUMP_IF_FALSE | 1,315,560 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 16,105,920 | 65.4% |
| LOAD_FAST | 3,567,840 | 14.5% |
| LOAD_ATTR_MODULE | 2,636,280 | 10.7% |
| RETURN_CONST | 1,397,940 | 5.7% |
| TO_BOOL_ALWAYS_TRUE | 777,120 | 3.2% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 41,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 41,160 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 180 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,514,700 | 43.2% |
| POP_TOP | 1,284,060 | 36.6% |
| STORE_ATTR_INSTANCE_VALUE | 678,300 | 19.3% |
| POP_JUMP_IF_TRUE | 17,280 | 0.5% |
| CALL_LIST_APPEND | 12,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,490,700 | 42.5% |
| LOAD_FAST | 1,328,700 | 37.9% |
| LOAD_FAST_LOAD_FAST | 678,300 | 19.3% |
| LOAD_CONST | 8,640 | 0.2% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 957,720 | 94.9% |
| RETURN_VALUE | 38,880 | 3.9% |
| LOAD_CONST | 12,060 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,008,660 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,081,380 | 100.0% |
| LOAD_ATTR | 7,400 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,898,120 | 69.5% |
| CALL_PY_WITH_DEFAULTS | 6,112,620 | 20.3% |
| LOAD_CONST | 2,525,400 | 8.4% |
| LOAD_FAST_LOAD_FAST | 504,000 | 1.7% |
| STORE_FAST | 41,160 | 0.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 19,116,900 | 43.7% |
| LOAD_FAST | 6,956,700 | 15.9% |
| LOAD_GLOBAL_MODULE | 5,201,940 | 11.9% |
| LOAD_CONST | 2,722,020 | 6.2% |
| STORE_ATTR_WITH_HINT | 2,573,400 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 13,392,000 | 30.6% |
| BINARY_OP_SUBTRACT_INT | 11,290,860 | 25.8% |
| COMPARE_OP_INT | 7,403,140 | 16.9% |
| LOAD_FAST | 3,569,460 | 8.2% |
| LOAD_CONST | 2,722,020 | 6.2% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| NOP | 60 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| PUSH_NULL | 60 | 33.3% |
| LOAD_FAST | 60 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 88,430,820 | 22.5% |
| POP_JUMP_IF_FALSE | 72,792,900 | 18.5% |
| LOAD_ATTR_WITH_HINT | 44,909,940 | 11.4% |
| RESUME_CHECK | 42,259,020 | 10.8% |
| LOAD_ATTR_INSTANCE_VALUE | 30,350,400 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 145,158,240 | 36.9% |
| LOAD_ATTR_INSTANCE_VALUE | 39,319,300 | 10.0% |
| LOAD_ATTR | 30,081,380 | 7.7% |
| RETURN_VALUE | 29,800,380 | 7.6% |
| COPY | 26,816,100 | 6.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 33,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 33,960 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,302,440 | 22.4% |
| POP_JUMP_IF_FALSE | 7,061,280 | 19.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,897,160 | 15.9% |
| RESUME_CHECK | 4,031,580 | 10.9% |
| STORE_SUBSCR_LIST_INT | 3,997,620 | 10.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,674,780 | 45.0% |
| STORE_ATTR_WITH_HINT | 7,499,340 | 20.2% |
| COMPARE_OP_INT | 4,485,240 | 12.1% |
| BINARY_OP_SUBTRACT_INT | 3,775,080 | 10.2% |
| CALL_PY_EXACT_ARGS | 3,153,480 | 8.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 18.2% |
| RETURN_VALUE | 40 | 18.2% |
| RESUME_CHECK | 40 | 18.2% |
| STORE_ATTR_INSTANCE_VALUE | 20 | 9.1% |
| POP_TOP | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180 | 81.8% |
| LOAD_GLOBAL_BUILTIN | 20 | 9.1% |
| LOAD_ATTR | 20 | 9.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 59,283,600 | 67.2% |
| TO_BOOL_BOOL | 23,987,640 | 27.2% |
| TO_BOOL_INT | 4,778,700 | 5.4% |
| COMPARE_OP | 84,240 | 0.1% |
| IS_OP | 41,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,792,900 | 82.5% |
| LOAD_FAST_LOAD_FAST | 7,061,280 | 8.0% |
| POP_TOP | 2,638,140 | 3.0% |
| LOAD_GLOBAL_MODULE | 1,894,480 | 2.1% |
| RETURN_CONST | 1,691,940 | 1.9% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,160 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 19,431,600 | 59.6% |
| TO_BOOL_BOOL | 6,380,160 | 19.6% |
| TO_BOOL_INT | 5,156,520 | 15.8% |
| TO_BOOL_ALWAYS_TRUE | 817,780 | 2.5% |
| COMPARE_OP_FLOAT | 795,660 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,603,360 | 38.6% |
| LOAD_FAST | 11,813,880 | 36.2% |
| POP_TOP | 5,502,660 | 16.9% |
| RETURN_CONST | 1,432,080 | 4.4% |
| RETURN_VALUE | 507,900 | 1.6% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,580,360 | 27.8% |
| STORE_ATTR_INSTANCE_VALUE | 4,138,440 | 20.6% |
| STORE_SUBSCR_LIST_INT | 3,997,620 | 19.9% |
| CALL_LIST_APPEND | 1,805,100 | 9.0% |
| POP_JUMP_IF_FALSE | 1,691,940 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,737,920 | 73.5% |
| TO_BOOL_BOOL | 4,636,800 | 23.1% |
| TO_BOOL_INT | 634,620 | 3.2% |
| EXIT_INIT_CHECK | 46,140 | 0.2% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,780 | 47.6% |
| LOAD_FAST_LOAD_FAST | 3,420 | 43.1% |
| STORE_ATTR | 540 | 6.8% |
| STORE_ATTR_WITH_HINT | 200 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,840 | 86.1% |
| STORE_ATTR | 540 | 6.8% |
| LOAD_FAST | 340 | 4.3% |
| STORE_ATTR_WITH_HINT | 200 | 2.5% |
| STORE_ATTR_INSTANCE_VALUE | 20 | 0.3% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 40,706,580 | 37.8% |
| RETURN_VALUE | 29,795,940 | 27.7% |
| BINARY_OP_ADD_INT | 6,752,340 | 6.3% |
| FOR_ITER_LIST | 6,639,120 | 6.2% |
| BINARY_SUBSCR_LIST_INT | 6,612,680 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 88,430,820 | 82.1% |
| LOAD_FAST_LOAD_FAST | 8,302,440 | 7.7% |
| COPY | 5,662,620 | 5.3% |
| ENTER_EXECUTOR | 2,063,940 | 1.9% |
| LOAD_GLOBAL_MODULE | 1,669,600 | 1.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 12,060 | 50.1% |
| COPY | 12,000 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 12,060 | 50.1% |
| LOAD_ATTR_INSTANCE_VALUE | 12,000 | 49.9% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,887,540 | 98.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,720 | 0.5% |
| BINARY_OP_ADD_INT | 9,720 | 0.5% |
| BINARY_OP | 9,720 | 0.5% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,887,540 | 98.5% |
| LOAD_FAST_LOAD_FAST | 9,720 | 0.5% |
| LOAD_CONST | 9,720 | 0.5% |
| BUILD_LIST | 9,720 | 0.5% |
| JUMP_BACKWARD | 180 | 0.0% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 5,201,940 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,917,880 | 75.3% |
| LOAD_GLOBAL_MODULE | 1,284,060 | 24.7% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 9,166,440 | 41.5% |
| BINARY_OP_SUBTRACT_INT | 8,638,020 | 39.2% |
| BINARY_OP_ADD_INT | 4,137,120 | 18.8% |
| LOAD_FAST_AND_CLEAR | 33,960 | 0.2% |
| ENTER_EXECUTOR | 33,960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_WITH_HINT | 12,748,560 | 57.8% |
| STORE_ATTR_INSTANCE_VALUE | 9,193,020 | 41.7% |
| STORE_FAST | 33,960 | 0.2% |
| BUILD_LIST | 33,960 | 0.2% |
| FOR_ITER_RANGE | 21,900 | 0.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 837,900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 837,900 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,392,000 | 78.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,514,120 | 14.8% |
| LOAD_ATTR_WITH_HINT | 1,023,600 | 6.0% |
| LOAD_FAST_LOAD_FAST | 19,440 | 0.1% |
| LOAD_FAST | 8,640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,752,340 | 39.8% |
| STORE_GLOBAL | 5,201,940 | 30.7% |
| SWAP | 4,137,120 | 24.4% |
| CALL_BUILTIN_CLASS | 837,900 | 4.9% |
| STORE_FAST_STORE_FAST | 9,720 | 0.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 837,900 | 94.9% |
| LOAD_GLOBAL_MODULE | 45,060 | 5.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 837,900 | 94.9% |
| CALL_BUILTIN_CLASS | 36,420 | 4.1% |
| LOAD_FAST | 8,640 | 1.0% |


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
| LOAD_CONST | 11,290,860 | 74.9% |
| LOAD_FAST_LOAD_FAST | 3,775,080 | 25.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 8,638,020 | 57.3% |
| STORE_FAST | 5,131,860 | 34.1% |
| BINARY_SUBSCR_LIST_INT | 1,296,060 | 8.6% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,345,880 | 67.6% |
| LOAD_ATTR_WITH_HINT | 4,092,360 | 20.7% |
| BINARY_OP_SUBTRACT_INT | 1,296,060 | 6.6% |
| LOAD_GLOBAL_MODULE | 981,720 | 5.0% |
| RETURN_VALUE | 34,560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 9,166,440 | 46.4% |
| STORE_FAST | 6,612,680 | 33.5% |
| CALL_PY_EXACT_ARGS | 2,640,840 | 13.4% |
| LOAD_FAST | 1,296,060 | 6.6% |
| CALL_LIST_APPEND | 34,560 | 0.2% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,240 | 52.5% |
| LOAD_GLOBAL_MODULE | 12,120 | 26.3% |
| ENTER_EXECUTOR | 9,600 | 20.8% |
| LOAD_FAST_LOAD_FAST | 120 | 0.3% |
| CALL | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 46,140 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 837,900 | 89.9% |
| BINARY_OP_MULTIPLY_INT | 36,420 | 3.9% |
| CALL_BUILTIN_CLASS | 24,240 | 2.6% |
| LOAD_GLOBAL_BUILTIN | 12,120 | 1.3% |
| LOAD_GLOBAL_MODULE | 12,040 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 837,900 | 89.9% |
| LOAD_FAST | 36,360 | 3.9% |
| GET_ITER | 33,960 | 3.6% |
| CALL_BUILTIN_CLASS | 24,240 | 2.6% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 837,900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 837,900 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 837,900 | 90.6% |
| LOAD_FAST | 87,120 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 837,900 | 90.6% |
| STORE_FAST | 87,120 | 9.4% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 120 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,797,960 | 84.4% |
| LOAD_ATTR_WITH_HINT | 331,560 | 15.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,296,060 | 60.9% |
| LOAD_FAST | 477,840 | 22.4% |
| COMPARE_OP_INT | 331,560 | 15.6% |
| STORE_FAST | 12,060 | 0.6% |
| CALL | 12,000 | 0.6% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,824,240 | 98.1% |
| BINARY_SUBSCR_LIST_INT | 34,560 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,805,100 | 97.1% |
| ENTER_EXECUTOR | 34,560 | 1.9% |
| JUMP_FORWARD | 12,000 | 0.6% |
| LOAD_FAST | 7,140 | 0.4% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,296,060 | 100.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,296,120 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 53,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 41,160 | 77.3% |
| POP_TOP | 12,120 | 22.7% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,296,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,296,180 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,573,280 | 59.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,074,720 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 3,183,600 | 7.6% |
| LOAD_FAST_LOAD_FAST | 3,153,480 | 7.6% |
| BINARY_SUBSCR_LIST_INT | 2,640,840 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 41,640,840 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 6,112,620 | 96.5% |
| LOAD_FAST | 220,140 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,332,760 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 795,660 | 100.0% |
| COMPARE_OP | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 795,660 | 100.0% |
| COMPARE_OP | 360 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 31,428,300 | 39.9% |
| LOAD_GLOBAL_MODULE | 30,401,560 | 38.6% |
| LOAD_CONST | 7,403,140 | 9.4% |
| LOAD_FAST_LOAD_FAST | 4,485,240 | 5.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,547,680 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 59,283,600 | 75.3% |
| POP_JUMP_IF_TRUE | 19,431,600 | 24.7% |
| COMPARE_OP | 24,120 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 6,650,940 | 99.8% |
| SWAP | 12,060 | 0.2% |
| JUMP_BACKWARD | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,639,120 | 99.6% |
| STORE_FAST_LOAD_FAST | 12,060 | 0.2% |
| RETURN_CONST | 12,000 | 0.2% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 21,900 | 64.5% |
| GET_ITER | 12,060 | 35.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 33,960 | 100.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 9,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 9,720 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,319,300 | 54.8% |
| LOAD_FAST_LOAD_FAST | 16,674,780 | 23.2% |
| COPY | 8,223,420 | 11.5% |
| LOAD_ATTR_WITH_HINT | 3,966,720 | 5.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,603,300 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,350,400 | 42.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 11,678,820 | 16.3% |
| LOAD_ATTR_METHOD_NO_DICT | 4,418,100 | 6.2% |
| LOAD_ATTR_INSTANCE_VALUE | 3,603,300 | 5.0% |
| COMPARE_OP_INT | 3,547,680 | 4.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,418,100 | 98.7% |
| LOAD_FAST | 60,300 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,129,060 | 69.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,296,060 | 28.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 53,280 | 1.2% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 11,678,820 | 60.4% |
| LOAD_FAST | 7,650,060 | 39.5% |
| STORE_FAST_LOAD_FAST | 12,060 | 0.1% |
| ENTER_EXECUTOR | 9,600 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,354,660 | 48.3% |
| LOAD_FAST_LOAD_FAST | 5,897,160 | 30.5% |
| CALL_PY_EXACT_ARGS | 4,074,720 | 21.1% |
| LOAD_GLOBAL_MODULE | 24,000 | 0.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,636,280 | 60.8% |
| LOAD_GLOBAL_MODULE | 1,702,540 | 39.2% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 4,338,820 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 145,158,240 | 82.8% |
| ENTER_EXECUTOR | 16,105,920 | 9.2% |
| COPY | 12,748,560 | 7.3% |
| LOAD_ATTR_WITH_HINT | 1,246,080 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,909,940 | 25.6% |
| STORE_FAST | 40,706,580 | 23.2% |
| COMPARE_OP_INT | 31,428,300 | 17.9% |
| LOAD_CONST | 19,116,900 | 10.9% |
| LOAD_GLOBAL_MODULE | 16,524,060 | 9.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,133,960 | 69.4% |
| RESUME_CHECK | 502,020 | 16.3% |
| LOAD_FAST | 331,680 | 10.8% |
| STORE_ATTR_INSTANCE_VALUE | 58,140 | 1.9% |
| LOAD_GLOBAL_BUILTIN | 24,600 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,967,540 | 96.5% |
| LOAD_GLOBAL_MODULE | 60,520 | 2.0% |
| LOAD_GLOBAL_BUILTIN | 24,600 | 0.8% |
| CALL_BUILTIN_CLASS | 12,120 | 0.4% |
| LOAD_CONST | 9,780 | 0.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 16,524,060 | 36.3% |
| LOAD_FAST | 15,255,940 | 33.6% |
| RESUME_CHECK | 3,959,120 | 8.7% |
| POP_JUMP_IF_FALSE | 1,894,480 | 4.2% |
| STORE_FAST | 1,669,600 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 30,401,560 | 66.9% |
| LOAD_FAST | 5,985,300 | 13.2% |
| LOAD_CONST | 5,201,940 | 11.4% |
| LOAD_ATTR_MODULE | 1,702,540 | 3.7% |
| BINARY_SUBSCR_LIST_INT | 981,720 | 2.2% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 41,640,840 | 82.0% |
| CALL_PY_WITH_DEFAULTS | 6,332,760 | 12.5% |
| CALL_KW | 2,722,020 | 5.4% |
| CALL_ALLOC_AND_ENTER_INIT | 46,140 | 0.1% |
| CALL | 41,160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,259,020 | 83.2% |
| LOAD_FAST_LOAD_FAST | 4,031,580 | 7.9% |
| LOAD_GLOBAL_MODULE | 3,959,120 | 7.8% |
| LOAD_GLOBAL_BUILTIN | 502,020 | 1.0% |
| LOAD_CONST | 31,260 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 9,193,020 | 65.2% |
| LOAD_ATTR_INSTANCE_VALUE | 1,906,680 | 13.5% |
| LOAD_FAST | 1,608,160 | 11.4% |
| LOAD_FAST_LOAD_FAST | 1,394,940 | 9.9% |
| STORE_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,470,440 | 38.8% |
| RETURN_CONST | 4,138,440 | 29.3% |
| LOAD_FAST_LOAD_FAST | 2,582,220 | 18.3% |
| ENTER_EXECUTOR | 1,000,860 | 7.1% |
| JUMP_FORWARD | 678,300 | 4.8% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 12,748,560 | 41.7% |
| LOAD_FAST | 10,275,740 | 33.7% |
| LOAD_FAST_LOAD_FAST | 7,499,340 | 24.6% |
| ENTER_EXECUTOR | 11,940 | 0.0% |
| STORE_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,309,380 | 69.8% |
| ENTER_EXECUTOR | 4,345,140 | 14.2% |
| LOAD_CONST | 2,573,400 | 8.4% |
| LOAD_FAST_LOAD_FAST | 2,307,660 | 7.6% |
| STORE_ATTR | 200 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,497,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 3,997,620 | 47.0% |
| LOAD_FAST_LOAD_FAST | 3,997,620 | 47.0% |
| LOAD_FAST | 501,840 | 5.9% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 777,120 | 94.2% |
| LOAD_FAST | 25,580 | 3.1% |
| LOAD_ATTR_INSTANCE_VALUE | 22,200 | 2.7% |
| TO_BOOL_NONE | 420 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 817,780 | 99.1% |
| POP_JUMP_IF_FALSE | 7,140 | 0.9% |
| TO_BOOL_NONE | 400 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,501,600 | 66.6% |
| RETURN_CONST | 4,636,800 | 14.4% |
| LOAD_ATTR_WITH_HINT | 3,579,480 | 11.1% |
| COPY | 1,887,540 | 5.8% |
| RETURN_VALUE | 637,800 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,987,640 | 74.3% |
| POP_JUMP_IF_TRUE | 6,380,160 | 19.8% |
| UNARY_NOT | 1,887,540 | 5.8% |
| TO_BOOL_INT | 12,000 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 5,844,120 | 58.8% |
| LOAD_FAST | 2,206,740 | 22.2% |
| RETURN_VALUE | 1,249,740 | 12.6% |
| RETURN_CONST | 634,620 | 6.4% |
| TO_BOOL_BOOL | 12,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,156,520 | 51.8% |
| POP_JUMP_IF_FALSE | 4,778,700 | 48.0% |
| TO_BOOL_BOOL | 12,000 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 12,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,000 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,940 | 35.6% |
| LOAD_ATTR_INSTANCE_VALUE | 11,520 | 31.7% |
| ENTER_EXECUTOR | 11,520 | 31.7% |
| TO_BOOL_ALWAYS_TRUE | 400 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 35,960 | 98.8% |
| TO_BOOL_ALWAYS_TRUE | 420 | 1.2% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 9,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 9,720 | 100.0% |


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
| specialization.deferred |         1300 | 0.0% |
| specialization.deopt |          820 | 0.0% |
|          hit |     20654020 | 99.8% |
|         miss |        43040 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 820 | 45.6% |
| Failure | 980 | 54.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 980 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      8497080 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |        24820 | 0.1% |
|          hit |     45135820 | 97.2% |
|         miss |      1315560 | 2.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 24,820 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     13780860 | 28.3% |
| specialization.deopt |         6000 | 0.0% |
|          hit |     34497660 | 70.9% |
|         miss |       318000 | 0.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,020 | 18.4% |
| Failure | 26,660 | 81.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 23,260 | 87.2% |
| xor | 2,240 | 8.4% |
| multiply different types | 640 | 2.4% |
| true divide different types | 400 | 1.5% |
| remainder | 60 | 0.2% |
| floor divide | 60 | 0.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5284920 | 7.7% |
|          hit |     63177000 | 92.3% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 11.1% |
| Failure | 1,440 | 88.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 700 | 48.6% |
| class no vectorcall | 640 | 44.4% |
| bound method | 100 | 6.9% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        96780 | 0.1% |
| specialization.deopt |          480 | 0.0% |
|          hit |     79657380 | 99.8% |
|         miss |        25440 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 520 | 26.3% |
| Failure | 1,460 | 73.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 960 | 65.8% |
| float long | 420 | 28.8% |
| long float | 40 | 2.7% |
| bool | 40 | 2.7% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      6706860 | 100.0% |


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
| specialization.deferred |     30081320 | 9.5% |
| specialization.deopt |          120 | 0.0% |
|          hit |    286975540 | 90.5% |
|         miss |         6360 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 3.6% |
| Failure | 7,400 | 96.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 7,360 | 99.5% |
| method | 40 | 0.5% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     57155260 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |           60 | 100.0% |


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
| specialization.deferred |         7180 | 0.0% |
| specialization.deopt |          200 | 0.0% |
|          hit |     44631880 | 100.0% |
|         miss |        11280 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 22.9% |
| Failure | 740 | 77.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 740 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |        38880 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 774,818,160 | 48.0% |
| Not specialized | 171,865,520 | 10.7% |
| Specialized | 666,151,760 | 41.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,032,260 | 100.0% |
| LOAD_ATTR | 30,081,320 | 0.0% |
| BINARY_OP | 13,780,860 | 0.0% |
| CALL | 5,284,920 | 0.0% |
| COMPARE_OP | 96,780 | 0.0% |
| STORE_ATTR | 7,180 | 0.0% |
| BINARY_SUBSCR | 1,300 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_INT | 636,000 | 37.0% |
| TO_BOOL_BOOL | 636,000 | 37.0% |
| BINARY_OP_ADD_INT | 318,000 | 18.5% |
| BINARY_SUBSCR_LIST_INT | 43,040 | 2.5% |
| TO_BOOL_NONE | 21,980 | 1.3% |
| TO_BOOL_ALWAYS_TRUE | 21,580 | 1.3% |
| COMPARE_OP_FLOAT | 19,080 | 1.1% |
| STORE_ATTR_WITH_HINT | 11,280 | 0.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,360 | 0.4% |
| COMPARE_OP_INT | 6,360 | 0.4% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 55,311,600 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 55,357,740 | 100.1% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 12,614,560 | 36.0% |
| Frees to freelist | 12,614,580 |  |
| Allocations | 22,455,040 | 64.0% |
| Allocations to 512 bytes | 22,394,800 | 63.9% |
| Allocations to 4 kbytes | 48,240 | 0.1% |
| Allocations over 4 kbytes | 12,000 | 0.0% |
| Frees | 22,325,300 |  |
| New values | 0 |  |
| Interpreter increfs | 611,759,060 | 78.6% |
| Interpreter decrefs | 682,931,700 | 84.0% |
| Increfs | 166,681,958 | 21.4% |
| Decrefs | 130,203,738 | 16.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 9,720 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 31,731,373 |  |
| Method cache misses | 322,227 |  |
| Method cache collisions | 322,227 |  |
| Method cache dunder hits | 300 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 100 | 0 | 3,816,080 |
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
