
# Pystats results

- benchmark: go
- fork: brandtbucher
- ref: justin
- commit hash: 898dcc2
- commit date: 2023-10-10T14:45:03+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 362,138,460 | 25.0% | 25.0% |  |
| LOAD_ATTR_WITH_HINT | 148,575,720 | 10.3% | 35.3% |  |
| STORE_FAST | 94,490,280 | 6.5% | 41.8% |  |
| POP_JUMP_IF_FALSE | 76,645,860 | 5.3% | 47.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 71,792,460 | 5.0% | 52.1% |  |
| COMPARE_OP_INT | 59,048,760 | 4.1% | 56.2% | 0.0% |
| RESUME_CHECK | 49,134,000 | 3.4% | 59.6% | 0.0% |
| LOAD_CONST | 40,957,320 | 2.8% | 62.4% |  |
| CALL_PY_EXACT_ARGS | 39,130,620 | 2.7% | 65.1% |  |
| LOAD_FAST_LOAD_FAST | 35,151,960 | 2.4% | 67.6% |  |
| RETURN_VALUE | 35,078,340 | 2.4% | 70.0% |  |
| COPY | 34,855,680 | 2.4% | 72.4% |  |
| STORE_ATTR_WITH_HINT | 30,535,780 | 2.1% | 74.5% | 0.0% |
| TO_BOOL_BOOL | 30,197,460 | 2.1% | 76.6% | 2.1% |
| LOAD_GLOBAL_MODULE | 29,384,500 | 2.0% | 78.6% |  |
| POP_TOP | 24,285,060 | 1.7% | 80.3% |  |
| POP_JUMP_IF_TRUE | 23,333,220 | 1.6% | 81.9% |  |
| LOAD_ATTR | 23,136,820 | 1.6% | 83.5% |  |
| ENTER_EXECUTOR | 21,902,280 | 1.5% | 85.0% |  |
| SWAP | 19,663,740 | 1.4% | 86.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 19,350,720 | 1.3% | 87.7% | 0.0% |
| RETURN_CONST | 19,128,660 | 1.3% | 89.0% |  |
| BINARY_SUBSCR_LIST_INT | 18,781,800 | 1.3% | 90.3% | 0.2% |
| BINARY_OP_SUBTRACT_INT | 15,065,940 | 1.0% | 91.4% |  |
| BINARY_OP_ADD_INT | 14,607,140 | 1.0% | 92.4% | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 13,133,220 | 0.9% | 93.3% |  |
| BINARY_OP | 13,028,160 | 0.9% | 94.2% |  |
| TO_BOOL_INT | 9,947,220 | 0.7% | 94.9% | 6.4% |
| STORE_SUBSCR_LIST_INT | 8,497,080 | 0.6% | 95.5% |  |
| CALL_PY_WITH_DEFAULTS | 6,332,760 | 0.4% | 95.9% |  |
| GET_ITER | 5,761,020 | 0.4% | 96.3% |  |
| FOR_ITER_LIST | 5,717,520 | 0.4% | 96.7% |  |
| CALL | 5,286,540 | 0.4% | 97.1% |  |
| STORE_GLOBAL | 5,201,940 | 0.4% | 97.4% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,478,400 | 0.3% | 97.7% |  |
| JUMP_FORWARD | 3,506,340 | 0.2% | 98.0% |  |
| LOAD_GLOBAL_BUILTIN | 3,067,620 | 0.2% | 98.2% |  |
| CALL_KW | 2,722,020 | 0.2% | 98.4% |  |
| CALL_LEN | 2,122,380 | 0.1% | 98.5% |  |
| STORE_FAST_STORE_FAST | 1,916,880 | 0.1% | 98.7% |  |
| UNARY_NOT | 1,887,540 | 0.1% | 98.8% |  |
| CONTAINS_OP | 1,887,540 | 0.1% | 98.9% |  |
| CALL_LIST_APPEND | 1,858,800 | 0.1% | 99.1% |  |
| PUSH_NULL | 1,748,760 | 0.1% | 99.2% |  |
| LOAD_ATTR_MODULE | 1,702,600 | 0.1% | 99.3% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,296,180 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,296,120 | 0.1% | 99.5% | 0.0% |
| LIST_APPEND | 1,008,660 | 0.1% | 99.5% |  |
| CALL_BUILTIN_CLASS | 932,460 | 0.1% | 99.6% |  |
| CALL_BUILTIN_O | 925,020 | 0.1% | 99.7% |  |
| BINARY_OP_MULTIPLY_INT | 882,960 | 0.1% | 99.7% |  |
| CALL_BUILTIN_FAST | 837,900 | 0.1% | 99.8% |  |
| BINARY_OP_ADD_FLOAT | 837,900 | 0.1% | 99.8% |  |
| TO_BOOL_ALWAYS_TRUE | 825,320 | 0.1% | 99.9% | 2.6% |
| COMPARE_OP_FLOAT | 796,020 | 0.1% | 100.0% | 2.4% |
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
| LOAD_FAST LOAD_ATTR_WITH_HINT | 136,009,560 | 9.4% | 9.4% |
| STORE_FAST LOAD_FAST | 77,856,540 | 5.4% | 14.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 61,244,280 | 4.2% | 19.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 47,734,980 | 3.3% | 22.3% |
| LOAD_ATTR_WITH_HINT LOAD_FAST | 42,245,460 | 2.9% | 25.2% |
| RESUME_CHECK LOAD_FAST | 40,609,980 | 2.8% | 28.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 39,312,160 | 2.7% | 30.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 39,130,620 | 2.7% | 33.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 30,350,400 | 2.1% | 35.6% |
| LOAD_FAST RETURN_VALUE | 29,576,460 | 2.0% | 37.6% |
| RETURN_VALUE STORE_FAST | 29,572,020 | 2.0% | 39.7% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 29,555,340 | 2.0% | 41.7% |
| LOAD_ATTR_WITH_HINT STORE_FAST | 29,381,880 | 2.0% | 43.7% |
| LOAD_FAST COPY | 25,387,620 | 1.8% | 45.5% |
| LOAD_FAST LOAD_ATTR | 23,131,040 | 1.6% | 47.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 23,060,820 | 1.6% | 48.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 22,063,060 | 1.5% | 50.2% |
| STORE_ATTR_WITH_HINT LOAD_FAST | 21,309,380 | 1.5% | 51.7% |
| LOAD_FAST TO_BOOL_BOOL | 21,304,200 | 1.5% | 53.2% |
| LOAD_ATTR LOAD_FAST | 18,387,900 | 1.3% | 54.4% |
| LOAD_ATTR_WITH_HINT LOAD_CONST | 17,688,420 | 1.2% | 55.6% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,674,780 | 1.2% | 56.8% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 15,295,480 | 1.1% | 57.9% |
| RETURN_CONST POP_TOP | 14,737,920 | 1.0% | 58.9% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 13,345,880 | 0.9% | 59.8% |
| POP_TOP LOAD_FAST | 12,286,620 | 0.8% | 60.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 11,678,820 | 0.8% | 61.5% |
| SWAP STORE_ATTR_WITH_HINT | 11,320,080 | 0.8% | 62.2% |
| COPY LOAD_ATTR_WITH_HINT | 11,320,080 | 0.8% | 63.0% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 11,290,860 | 0.8% | 63.8% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 11,289,660 | 0.8% | 64.6% |
| LOAD_CONST BINARY_OP_ADD_INT | 11,033,980 | 0.8% | 65.3% |
| LOAD_FAST STORE_ATTR_WITH_HINT | 10,275,740 | 0.7% | 66.1% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 9,740,880 | 0.7% | 66.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 9,354,660 | 0.6% | 67.4% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 9,022,920 | 0.6% | 68.0% |
| BINARY_OP_SUBTRACT_INT SWAP | 8,638,020 | 0.6% | 68.6% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 8,497,080 | 0.6% | 69.2% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 8,223,420 | 0.6% | 69.8% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 8,223,420 | 0.6% | 70.3% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 8,196,840 | 0.6% | 70.9% |
| BINARY_OP SWAP | 8,196,840 | 0.6% | 71.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 7,650,060 | 0.5% | 72.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_WITH_HINT | 7,499,340 | 0.5% | 72.5% |
| LOAD_CONST COMPARE_OP_INT | 7,403,140 | 0.5% | 73.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 7,061,280 | 0.5% | 73.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 6,763,620 | 0.5% | 74.0% |
| ENTER_EXECUTOR LOAD_FAST | 6,685,980 | 0.5% | 74.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 6,681,400 | 0.5% | 74.9% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 6,612,680 | 0.5% | 75.4% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 6,382,440 | 0.4% | 75.8% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 6,332,760 | 0.4% | 76.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 5,985,300 | 0.4% | 76.6% |
| LOAD_FAST LOAD_CONST | 5,903,040 | 0.4% | 77.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 5,897,160 | 0.4% | 77.5% |
| COPY TO_BOOL_INT | 5,844,120 | 0.4% | 77.9% |
| BINARY_OP_ADD_INT STORE_FAST | 5,828,580 | 0.4% | 78.3% |
| GET_ITER FOR_ITER_LIST | 5,705,280 | 0.4% | 78.7% |
| FOR_ITER_LIST STORE_FAST | 5,693,460 | 0.4% | 79.1% |
| STORE_FAST COPY | 5,662,620 | 0.4% | 79.4% |
| COPY STORE_FAST | 5,662,620 | 0.4% | 79.8% |
| LOAD_ATTR_WITH_HINT GET_ITER | 5,625,660 | 0.4% | 80.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 5,470,440 | 0.4% | 80.6% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 5,237,100 | 0.4% | 81.0% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 5,201,940 | 0.4% | 81.3% |
| BINARY_OP_ADD_INT STORE_GLOBAL | 5,201,940 | 0.4% | 81.7% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 5,156,520 | 0.4% | 82.0% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 5,131,860 | 0.4% | 82.4% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 4,778,700 | 0.3% | 82.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,418,100 | 0.3% | 83.0% |
| POP_TOP RETURN_CONST | 4,369,080 | 0.3% | 83.3% |
| STORE_ATTR_WITH_HINT ENTER_EXECUTOR | 4,345,140 | 0.3% | 83.6% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 4,302,900 | 0.3% | 83.9% |
| POP_JUMP_IF_TRUE POP_TOP | 4,291,380 | 0.3% | 84.2% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 4,138,440 | 0.3% | 84.5% |
| LOAD_ATTR_WITH_HINT BINARY_SUBSCR_LIST_INT | 4,092,360 | 0.3% | 84.8% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 4,074,720 | 0.3% | 85.1% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 4,031,580 | 0.3% | 85.4% |
| STORE_SUBSCR_LIST_INT RETURN_CONST | 3,997,620 | 0.3% | 85.6% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 3,997,620 | 0.3% | 85.9% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_INSTANCE_VALUE | 3,966,720 | 0.3% | 86.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 3,959,120 | 0.3% | 86.5% |
| STORE_GLOBAL LOAD_FAST | 3,917,880 | 0.3% | 86.7% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_INT | 3,775,080 | 0.3% | 87.0% |
| RETURN_CONST TO_BOOL_BOOL | 3,709,980 | 0.3% | 87.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 3,603,300 | 0.2% | 87.5% |
| LOAD_CONST LOAD_FAST | 3,569,460 | 0.2% | 87.7% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 3,547,680 | 0.2% | 88.0% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 3,183,600 | 0.2% | 88.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 3,153,480 | 0.2% | 88.4% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 3,129,060 | 0.2% | 88.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,960,400 | 0.2% | 88.9% |
| CALL_KW RESUME_CHECK | 2,722,020 | 0.2% | 89.0% |
| BINARY_OP_ADD_INT SWAP | 2,708,640 | 0.2% | 89.2% |
| BINARY_SUBSCR_LIST_INT CALL_PY_EXACT_ARGS | 2,640,840 | 0.2% | 89.4% |
| POP_JUMP_IF_FALSE POP_TOP | 2,638,140 | 0.2% | 89.6% |
| ENTER_EXECUTOR CALL | 2,636,280 | 0.2% | 89.8% |
| LOAD_ATTR_WITH_HINT TO_BOOL_BOOL | 2,633,820 | 0.2% | 90.0% |
| CALL STORE_FAST | 2,621,820 | 0.2% | 90.1% |
| CALL LOAD_FAST | 2,621,820 | 0.2% | 90.3% |


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
| LOAD_ATTR_WITH_HINT | 5,625,660 | 97.7% |
| LOAD_ATTR_INSTANCE_VALUE | 67,680 | 1.2% |
| CALL_BUILTIN_CLASS | 33,960 | 0.6% |
| LOAD_FAST | 24,000 | 0.4% |
| LOAD_CONST | 9,720 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 5,705,280 | 99.0% |
| LOAD_FAST_AND_CLEAR | 33,960 | 0.6% |
| FOR_ITER_RANGE | 12,060 | 0.2% |
| FOR_ITER_TUPLE | 9,720 | 0.2% |


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
| RETURN_CONST | 14,737,920 | 60.7% |
| POP_JUMP_IF_TRUE | 4,291,380 | 17.7% |
| POP_JUMP_IF_FALSE | 2,638,140 | 10.9% |
| CALL_METHOD_DESCRIPTOR_O | 1,296,180 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,296,120 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,286,620 | 50.6% |
| RETURN_CONST | 4,369,080 | 18.0% |
| ENTER_EXECUTOR | 2,252,760 | 9.3% |
| LOAD_CONST | 1,887,600 | 7.8% |
| LOAD_FAST_LOAD_FAST | 1,284,060 | 5.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,702,540 | 97.4% |
| LOAD_FAST | 46,140 | 2.6% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 883,920 | 50.5% |
| LOAD_GLOBAL_MODULE | 837,900 | 47.9% |
| CALL | 12,260 | 0.7% |
| LOAD_CONST | 9,780 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 4,860 | 0.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,576,460 | 84.3% |
| CONTAINS_OP | 1,887,540 | 5.4% |
| RETURN_VALUE | 1,349,400 | 3.8% |
| BINARY_OP_ADD_FLOAT | 837,900 | 2.4% |
| POP_JUMP_IF_FALSE | 775,980 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,572,020 | 84.3% |
| RETURN_VALUE | 1,349,400 | 3.8% |
| CALL_PY_EXACT_ARGS | 1,308,120 | 3.7% |
| TO_BOOL_INT | 1,249,740 | 3.6% |
| LOAD_FAST | 863,640 | 2.5% |


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
| BINARY_SUBSCR_LIST_INT | 8,196,840 | 62.9% |
| LOAD_FAST | 2,621,780 | 20.1% |
| CALL_BUILTIN_CLASS | 837,900 | 6.4% |
| BINARY_OP_MULTIPLY_INT | 837,900 | 6.4% |
| ENTER_EXECUTOR | 332,860 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 8,196,840 | 62.9% |
| CALL | 2,621,760 | 20.1% |
| STORE_FAST | 1,344,060 | 10.3% |
| CALL_BUILTIN_O | 837,900 | 6.4% |
| STORE_FAST_STORE_FAST | 9,720 | 0.1% |


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
| ENTER_EXECUTOR | 2,636,280 | 49.9% |
| BINARY_OP | 2,621,760 | 49.6% |
| PUSH_NULL | 12,260 | 0.2% |
| LOAD_CONST | 9,780 | 0.2% |
| CALL_LEN | 4,860 | 0.1% |

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
| LOAD_CONST | 2,584,800 | 95.0% |
| ENTER_EXECUTOR | 137,220 | 5.0% |

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
| LOAD_FAST | 25,387,620 | 72.8% |
| STORE_FAST | 5,662,620 | 16.2% |
| UNARY_NOT | 1,887,540 | 5.4% |
| LOAD_CONST | 1,887,540 | 5.4% |
| SWAP | 18,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 11,320,080 | 32.5% |
| LOAD_ATTR_INSTANCE_VALUE | 8,223,420 | 23.6% |
| TO_BOOL_INT | 5,844,120 | 16.8% |
| STORE_FAST | 5,662,620 | 16.2% |
| TO_BOOL_BOOL | 1,887,540 | 5.4% |


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
| POP_JUMP_IF_TRUE | 9,740,880 | 44.5% |
| STORE_ATTR_WITH_HINT | 4,345,140 | 19.8% |
| POP_TOP | 2,252,760 | 10.3% |
| ENTER_EXECUTOR | 1,824,540 | 8.3% |
| STORE_FAST | 1,348,920 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,685,980 | 30.5% |
| CALL_PY_WITH_DEFAULTS | 4,302,900 | 19.6% |
| CALL | 2,636,280 | 12.0% |
| ENTER_EXECUTOR | 1,824,540 | 8.3% |
| RETURN_CONST | 1,682,400 | 7.7% |


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
| LOAD_FAST | 23,131,040 | 100.0% |
| LOAD_ATTR | 5,680 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,387,900 | 79.5% |
| LOAD_CONST | 2,388,180 | 10.3% |
| CALL_PY_WITH_DEFAULTS | 1,809,720 | 7.8% |
| LOAD_FAST_LOAD_FAST | 504,000 | 2.2% |
| STORE_FAST | 41,160 | 0.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 17,688,420 | 43.2% |
| LOAD_FAST | 5,903,040 | 14.4% |
| LOAD_GLOBAL_MODULE | 5,201,940 | 12.7% |
| LOAD_CONST | 2,584,800 | 6.3% |
| STORE_ATTR_WITH_HINT | 2,573,400 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 11,290,860 | 27.6% |
| BINARY_OP_ADD_INT | 11,033,980 | 26.9% |
| COMPARE_OP_INT | 7,403,140 | 18.1% |
| LOAD_FAST | 3,569,460 | 8.7% |
| LOAD_CONST | 2,584,800 | 6.3% |


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
| STORE_FAST | 77,856,540 | 21.5% |
| POP_JUMP_IF_FALSE | 61,244,280 | 16.9% |
| LOAD_ATTR_WITH_HINT | 42,245,460 | 11.7% |
| RESUME_CHECK | 40,609,980 | 11.2% |
| LOAD_ATTR_INSTANCE_VALUE | 30,350,400 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 136,009,560 | 37.6% |
| LOAD_ATTR_INSTANCE_VALUE | 39,312,160 | 10.9% |
| RETURN_VALUE | 29,576,460 | 8.2% |
| COPY | 25,387,620 | 7.0% |
| LOAD_ATTR | 23,131,040 | 6.4% |


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
| POP_JUMP_IF_FALSE | 7,061,280 | 20.1% |
| STORE_FAST | 6,382,440 | 18.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,897,160 | 16.8% |
| RESUME_CHECK | 4,031,580 | 11.5% |
| STORE_SUBSCR_LIST_INT | 3,997,620 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,674,780 | 47.4% |
| STORE_ATTR_WITH_HINT | 7,499,340 | 21.3% |
| BINARY_OP_SUBTRACT_INT | 3,775,080 | 10.7% |
| CALL_PY_EXACT_ARGS | 3,153,480 | 9.0% |
| COMPARE_OP_INT | 2,565,240 | 7.3% |


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
| COMPARE_OP_INT | 47,734,980 | 62.3% |
| TO_BOOL_BOOL | 23,060,820 | 30.1% |
| TO_BOOL_INT | 4,778,700 | 6.2% |
| ENTER_EXECUTOR | 926,820 | 1.2% |
| COMPARE_OP | 84,240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,244,280 | 79.9% |
| LOAD_FAST_LOAD_FAST | 7,061,280 | 9.2% |
| POP_TOP | 2,638,140 | 3.4% |
| LOAD_GLOBAL_MODULE | 1,894,480 | 2.5% |
| RETURN_CONST | 1,691,940 | 2.2% |


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
| COMPARE_OP_INT | 11,289,660 | 48.4% |
| TO_BOOL_BOOL | 5,237,100 | 22.4% |
| TO_BOOL_INT | 5,156,520 | 22.1% |
| TO_BOOL_ALWAYS_TRUE | 817,780 | 3.5% |
| COMPARE_OP_FLOAT | 795,660 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 9,740,880 | 41.7% |
| LOAD_FAST | 6,763,620 | 29.0% |
| POP_TOP | 4,291,380 | 18.4% |
| RETURN_CONST | 1,432,080 | 6.1% |
| RETURN_VALUE | 507,900 | 2.2% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 4,369,080 | 22.8% |
| STORE_ATTR_INSTANCE_VALUE | 4,138,440 | 21.6% |
| STORE_SUBSCR_LIST_INT | 3,997,620 | 20.9% |
| CALL_LIST_APPEND | 1,805,100 | 9.4% |
| POP_JUMP_IF_FALSE | 1,691,940 | 8.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 14,737,920 | 77.0% |
| TO_BOOL_BOOL | 3,709,980 | 19.4% |
| TO_BOOL_INT | 634,620 | 3.3% |
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
| RETURN_VALUE | 29,572,020 | 31.3% |
| LOAD_ATTR_WITH_HINT | 29,381,880 | 31.1% |
| BINARY_SUBSCR_LIST_INT | 6,612,680 | 7.0% |
| BINARY_OP_ADD_INT | 5,828,580 | 6.2% |
| FOR_ITER_LIST | 5,693,460 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 77,856,540 | 82.4% |
| LOAD_FAST_LOAD_FAST | 6,382,440 | 6.8% |
| COPY | 5,662,620 | 6.0% |
| LOAD_GLOBAL_MODULE | 1,669,600 | 1.8% |
| JUMP_FORWARD | 1,514,700 | 1.6% |


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
| BINARY_OP_SUBTRACT_INT | 8,638,020 | 43.9% |
| BINARY_OP | 8,196,840 | 41.7% |
| BINARY_OP_ADD_INT | 2,708,640 | 13.8% |
| LOAD_FAST_AND_CLEAR | 33,960 | 0.2% |
| ENTER_EXECUTOR | 33,960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_WITH_HINT | 11,320,080 | 57.6% |
| STORE_ATTR_INSTANCE_VALUE | 8,223,420 | 41.8% |
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
| LOAD_CONST | 11,033,980 | 75.5% |
| LOAD_ATTR_INSTANCE_VALUE | 2,514,120 | 17.2% |
| LOAD_ATTR_WITH_HINT | 1,023,600 | 7.0% |
| LOAD_FAST_LOAD_FAST | 19,440 | 0.1% |
| LOAD_FAST | 8,640 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,828,580 | 39.9% |
| STORE_GLOBAL | 5,201,940 | 35.6% |
| SWAP | 2,708,640 | 18.5% |
| CALL_BUILTIN_CLASS | 837,900 | 5.7% |
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
| LOAD_FAST | 13,345,880 | 71.1% |
| LOAD_ATTR_WITH_HINT | 4,092,360 | 21.8% |
| BINARY_OP_SUBTRACT_INT | 1,296,060 | 6.9% |
| RETURN_VALUE | 34,560 | 0.2% |
| LOAD_GLOBAL_MODULE | 12,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 8,196,840 | 43.6% |
| STORE_FAST | 6,612,680 | 35.2% |
| CALL_PY_EXACT_ARGS | 2,640,840 | 14.1% |
| LOAD_FAST | 1,296,060 | 6.9% |
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
| LOAD_ATTR_INSTANCE_VALUE | 1,790,820 | 84.4% |
| LOAD_ATTR_WITH_HINT | 331,560 | 15.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,296,060 | 61.1% |
| LOAD_FAST | 477,840 | 22.5% |
| COMPARE_OP_INT | 331,560 | 15.6% |
| STORE_FAST | 12,060 | 0.6% |
| CALL | 4,860 | 0.2% |


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
| LOAD_FAST | 22,063,060 | 56.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,074,720 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 3,183,600 | 8.1% |
| LOAD_FAST_LOAD_FAST | 3,153,480 | 8.1% |
| BINARY_SUBSCR_LIST_INT | 2,640,840 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 39,130,620 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,302,900 | 67.9% |
| LOAD_ATTR | 1,809,720 | 28.6% |
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
| LOAD_ATTR_WITH_HINT | 29,555,340 | 50.1% |
| LOAD_GLOBAL_MODULE | 15,295,480 | 25.9% |
| LOAD_CONST | 7,403,140 | 12.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,547,680 | 6.0% |
| LOAD_FAST_LOAD_FAST | 2,565,240 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 47,734,980 | 80.8% |
| POP_JUMP_IF_TRUE | 11,289,660 | 19.1% |
| COMPARE_OP | 24,120 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,705,280 | 99.8% |
| SWAP | 12,060 | 0.2% |
| JUMP_BACKWARD | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,693,460 | 99.6% |
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
| LOAD_FAST | 39,312,160 | 54.8% |
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
| LOAD_GLOBAL_MODULE | 1,702,540 | 100.0% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,702,540 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 136,009,560 | 91.5% |
| COPY | 11,320,080 | 7.6% |
| LOAD_ATTR_WITH_HINT | 1,246,080 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,245,460 | 28.4% |
| COMPARE_OP_INT | 29,555,340 | 19.9% |
| STORE_FAST | 29,381,880 | 19.8% |
| LOAD_CONST | 17,688,420 | 11.9% |
| LOAD_GLOBAL_MODULE | 9,022,920 | 6.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,133,960 | 69.6% |
| RESUME_CHECK | 502,020 | 16.4% |
| LOAD_FAST | 331,680 | 10.8% |
| STORE_ATTR_INSTANCE_VALUE | 58,140 | 1.9% |
| LOAD_GLOBAL_BUILTIN | 24,600 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,960,400 | 96.5% |
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
| LOAD_ATTR_WITH_HINT | 9,022,920 | 30.7% |
| LOAD_FAST | 6,681,400 | 22.7% |
| RESUME_CHECK | 3,959,120 | 13.5% |
| POP_JUMP_IF_FALSE | 1,894,480 | 6.4% |
| STORE_FAST | 1,669,600 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 15,295,480 | 52.1% |
| LOAD_FAST | 5,985,300 | 20.4% |
| LOAD_CONST | 5,201,940 | 17.7% |
| LOAD_ATTR_MODULE | 1,702,540 | 5.8% |
| CALL_PY_EXACT_ARGS | 944,760 | 3.2% |


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
| CALL_PY_EXACT_ARGS | 39,130,620 | 79.6% |
| CALL_PY_WITH_DEFAULTS | 6,332,760 | 12.9% |
| CALL_KW | 2,722,020 | 5.5% |
| ENTER_EXECUTOR | 861,180 | 1.8% |
| CALL_ALLOC_AND_ENTER_INIT | 46,140 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,609,980 | 82.7% |
| LOAD_FAST_LOAD_FAST | 4,031,580 | 8.2% |
| LOAD_GLOBAL_MODULE | 3,959,120 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 502,020 | 1.0% |
| LOAD_CONST | 31,260 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 8,223,420 | 62.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,906,680 | 14.5% |
| LOAD_FAST | 1,608,160 | 12.2% |
| LOAD_FAST_LOAD_FAST | 1,394,940 | 10.6% |
| STORE_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,470,440 | 41.7% |
| RETURN_CONST | 4,138,440 | 31.5% |
| LOAD_FAST_LOAD_FAST | 2,582,220 | 19.7% |
| JUMP_FORWARD | 678,300 | 5.2% |
| LOAD_CONST | 118,560 | 0.9% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 11,320,080 | 37.1% |
| LOAD_FAST | 10,275,740 | 33.7% |
| LOAD_FAST_LOAD_FAST | 7,499,340 | 24.6% |
| ENTER_EXECUTOR | 1,440,420 | 4.7% |
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
| LOAD_FAST | 21,304,200 | 70.5% |
| RETURN_CONST | 3,709,980 | 12.3% |
| LOAD_ATTR_WITH_HINT | 2,633,820 | 8.7% |
| COPY | 1,887,540 | 6.3% |
| RETURN_VALUE | 637,800 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 23,060,820 | 76.4% |
| POP_JUMP_IF_TRUE | 5,237,100 | 17.3% |
| UNARY_NOT | 1,887,540 | 6.3% |
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
| specialization.deferred |     13020000 | 27.3% |
| specialization.deopt |         1580 | 0.0% |
|          hit |     34518760 | 72.5% |
|         miss |        83740 | 0.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,600 | 16.4% |
| Failure | 8,140 | 83.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 4,940 | 60.7% |
| xor | 2,040 | 25.1% |
| multiply different types | 640 | 7.9% |
| true divide different types | 400 | 4.9% |
| remainder | 60 | 0.7% |
| floor divide | 60 | 0.7% |


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
|          hit |      5761200 | 100.0% |


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
| specialization.deferred |     23130980 | 7.5% |
| specialization.deopt |          120 | 0.0% |
|          hit |    286975540 | 92.5% |
|         miss |         6360 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 4.7% |
| Failure | 5,680 | 95.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 5,640 | 99.3% |
| method | 40 | 0.7% |


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
| Basic | 713,518,140 | 49.3% |
| Not specialized | 143,066,200 | 9.9% |
| Specialized | 589,808,340 | 40.8% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,032,260 | 100.0% |
| LOAD_ATTR | 23,130,980 | 0.0% |
| BINARY_OP | 13,020,000 | 0.0% |
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
| TO_BOOL_INT | 636,000 | 42.8% |
| TO_BOOL_BOOL | 636,000 | 42.8% |
| BINARY_OP_ADD_INT | 83,740 | 5.6% |
| BINARY_SUBSCR_LIST_INT | 43,040 | 2.9% |
| TO_BOOL_NONE | 21,980 | 1.5% |
| TO_BOOL_ALWAYS_TRUE | 21,580 | 1.5% |
| COMPARE_OP_FLOAT | 19,080 | 1.3% |
| STORE_ATTR_WITH_HINT | 11,280 | 0.8% |
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
| Interpreter increfs | 574,973,300 | 74.2% |
| Interpreter decrefs | 642,637,260 | 79.3% |
| Increfs | 200,407,220 | 25.8% |
| Decrefs | 167,437,680 | 20.7% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 9,720 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 32,051,877 |  |
| Method cache misses | 3 |  |
| Method cache collisions | 3 |  |
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
| Traces executed | 0 |  |
| Uops executed | 0 | 0 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
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
| <= 1 | 0 |  |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|


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
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-10-11
