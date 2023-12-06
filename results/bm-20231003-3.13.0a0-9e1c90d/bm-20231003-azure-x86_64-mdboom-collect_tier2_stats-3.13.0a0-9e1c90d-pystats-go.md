
# Pystats results

- benchmark: go
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 404,036,340 | 24.4% | 24.4% |  |
| LOAD_ATTR_WITH_HINT | 175,258,800 | 10.6% | 35.0% |  |
| STORE_FAST | 109,953,300 | 6.6% | 41.6% |  |
| POP_JUMP_IF_FALSE | 89,525,820 | 5.4% | 47.0% |  |
| COMPARE_OP_INT | 78,766,320 | 4.8% | 51.7% | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 75,438,900 | 4.6% | 56.3% |  |
| RESUME_CHECK | 55,311,600 | 3.3% | 59.6% | 0.0% |
| LOAD_GLOBAL_MODULE | 47,799,880 | 2.9% | 62.5% |  |
| CALL_PY_EXACT_ARGS | 46,169,400 | 2.8% | 65.3% |  |
| LOAD_CONST | 44,679,000 | 2.7% | 68.0% |  |
| LOAD_FAST_LOAD_FAST | 37,097,880 | 2.2% | 70.2% |  |
| COPY | 36,284,160 | 2.2% | 72.4% |  |
| RETURN_VALUE | 35,302,260 | 2.1% | 74.5% |  |
| POP_JUMP_IF_TRUE | 32,649,780 | 2.0% | 76.5% |  |
| TO_BOOL_BOOL | 32,267,340 | 1.9% | 78.5% | 2.0% |
| STORE_ATTR_WITH_HINT | 30,535,780 | 1.8% | 80.3% | 0.0% |
| LOAD_ATTR | 30,088,880 | 1.8% | 82.1% |  |
| POP_TOP | 25,496,340 | 1.5% | 83.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 25,149,480 | 1.5% | 85.2% | 0.0% |
| ENTER_EXECUTOR | 24,633,420 | 1.5% | 86.7% |  |
| SWAP | 22,061,820 | 1.3% | 88.0% |  |
| BINARY_SUBSCR_LIST_INT | 20,697,060 | 1.2% | 89.2% | 0.2% |
| RETURN_CONST | 20,055,480 | 1.2% | 90.5% |  |
| BINARY_OP_ADD_INT | 17,935,380 | 1.1% | 91.5% | 1.8% |
| BINARY_OP_SUBTRACT_INT | 15,065,940 | 0.9% | 92.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 14,107,380 | 0.9% | 93.3% |  |
| BINARY_OP | 13,807,500 | 0.8% | 94.1% |  |
| TO_BOOL_INT | 11,243,340 | 0.7% | 94.8% | 5.7% |
| STORE_SUBSCR_LIST_INT | 8,497,080 | 0.5% | 95.3% |  |
| GET_ITER | 6,718,620 | 0.4% | 95.7% |  |
| FOR_ITER_LIST | 6,675,120 | 0.4% | 96.1% |  |
| CALL_PY_WITH_DEFAULTS | 6,332,760 | 0.4% | 96.5% |  |
| STORE_GLOBAL | 6,147,600 | 0.4% | 96.9% |  |
| LOAD_GLOBAL_BUILTIN | 5,667,000 | 0.3% | 97.2% |  |
| CALL | 5,286,540 | 0.3% | 97.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 4,504,320 | 0.3% | 97.8% |  |
| PUSH_NULL | 4,385,040 | 0.3% | 98.1% |  |
| LOAD_ATTR_MODULE | 4,338,880 | 0.3% | 98.3% |  |
| JUMP_FORWARD | 3,536,820 | 0.2% | 98.6% |  |
| CALL_LEN | 3,425,640 | 0.2% | 98.8% |  |
| CALL_KW | 2,722,020 | 0.2% | 98.9% |  |
| STORE_FAST_STORE_FAST | 1,916,880 | 0.1% | 99.0% |  |
| UNARY_NOT | 1,887,540 | 0.1% | 99.2% |  |
| CONTAINS_OP | 1,887,540 | 0.1% | 99.3% |  |
| CALL_LIST_APPEND | 1,858,800 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,296,180 | 0.1% | 99.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,296,120 | 0.1% | 99.5% | 0.0% |
| LIST_APPEND | 1,008,660 | 0.1% | 99.6% |  |
| CALL_BUILTIN_CLASS | 932,460 | 0.1% | 99.7% |  |
| CALL_BUILTIN_O | 925,020 | 0.1% | 99.7% |  |
| BINARY_OP_MULTIPLY_INT | 908,880 | 0.1% | 99.8% |  |
| CALL_BUILTIN_FAST | 837,900 | 0.1% | 99.8% |  |
| BINARY_OP_ADD_FLOAT | 837,900 | 0.1% | 99.9% |  |
| TO_BOOL_ALWAYS_TRUE | 828,940 | 0.1% | 99.9% | 2.6% |
| COMPARE_OP_FLOAT | 796,020 | 0.0% | 100.0% | 2.4% |
| COMPARE_OP | 98,280 | 0.0% | 100.0% |  |
| BUILD_LIST | 67,800 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 53,280 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 46,140 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 46,140 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 41,160 | 0.0% | 100.0% |  |
| IS_OP | 41,160 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 37,360 | 0.0% | 100.0% | 61.7% |
| LOAD_FAST_AND_CLEAR | 33,960 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 33,960 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 24,060 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 19,140 | 0.0% | 100.0% |  |
| NOP | 12,060 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 9,720 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 9,720 | 0.0% | 100.0% |  |
| STORE_ATTR | 7,940 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 7,320 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 2,280 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 220 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_WITH_HINT | 146,103,900 | 8.8% | 8.8% |
| STORE_FAST LOAD_FAST | 90,672,600 | 5.5% | 14.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 72,792,900 | 4.4% | 18.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 59,283,600 | 3.6% | 22.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 46,169,400 | 2.8% | 25.0% |
| LOAD_ATTR_WITH_HINT LOAD_FAST | 44,909,940 | 2.7% | 27.7% |
| RESUME_CHECK LOAD_FAST | 44,545,800 | 2.7% | 30.4% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 42,932,680 | 2.6% | 33.0% |
| LOAD_ATTR_WITH_HINT STORE_FAST | 40,706,580 | 2.5% | 35.5% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 31,428,300 | 1.9% | 37.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 31,296,060 | 1.9% | 39.3% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 30,428,560 | 1.8% | 41.1% |
| LOAD_FAST LOAD_ATTR | 30,081,380 | 1.8% | 42.9% |
| LOAD_FAST RETURN_VALUE | 29,800,380 | 1.8% | 44.7% |
| RETURN_VALUE STORE_FAST | 29,795,940 | 1.8% | 46.5% |
| LOAD_FAST COPY | 26,816,100 | 1.6% | 48.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 26,471,740 | 1.6% | 49.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 23,987,640 | 1.4% | 51.2% |
| LOAD_FAST TO_BOOL_BOOL | 21,501,600 | 1.3% | 52.5% |
| STORE_ATTR_WITH_HINT LOAD_FAST | 21,309,380 | 1.3% | 53.8% |
| LOAD_ATTR LOAD_FAST | 20,898,120 | 1.3% | 55.0% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 19,458,600 | 1.2% | 56.2% |
| LOAD_ATTR_WITH_HINT LOAD_CONST | 19,116,900 | 1.2% | 57.3% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 16,674,780 | 1.0% | 58.4% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 16,524,060 | 1.0% | 59.4% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 15,281,860 | 0.9% | 60.3% |
| ENTER_EXECUTOR LOAD_ATTR_WITH_HINT | 15,160,260 | 0.9% | 61.2% |
| RETURN_CONST POP_TOP | 14,737,920 | 0.9% | 62.1% |
| LOAD_CONST BINARY_OP_ADD_INT | 14,337,660 | 0.9% | 62.9% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 14,291,540 | 0.9% | 63.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 12,974,940 | 0.8% | 64.6% |
| SWAP STORE_ATTR_WITH_HINT | 12,748,560 | 0.8% | 65.4% |
| COPY LOAD_ATTR_WITH_HINT | 12,748,560 | 0.8% | 66.1% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 12,604,440 | 0.8% | 66.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 12,549,240 | 0.8% | 67.6% |
| POP_TOP LOAD_FAST | 12,286,620 | 0.7% | 68.4% |
| POP_JUMP_IF_TRUE LOAD_FAST | 11,818,440 | 0.7% | 69.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 11,290,860 | 0.7% | 69.8% |
| LOAD_FAST STORE_ATTR_WITH_HINT | 10,287,680 | 0.6% | 70.4% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 9,898,980 | 0.6% | 71.0% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 9,193,020 | 0.6% | 71.5% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 9,166,440 | 0.6% | 72.1% |
| BINARY_OP SWAP | 9,166,440 | 0.6% | 72.7% |
| BINARY_OP_SUBTRACT_INT SWAP | 8,638,020 | 0.5% | 73.2% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 8,497,080 | 0.5% | 73.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 8,302,440 | 0.5% | 74.2% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 8,223,420 | 0.5% | 74.7% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 7,558,340 | 0.5% | 75.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_WITH_HINT | 7,499,340 | 0.5% | 75.6% |
| LOAD_CONST COMPARE_OP_INT | 7,403,140 | 0.4% | 76.0% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 7,061,280 | 0.4% | 76.5% |
| LOAD_FAST LOAD_CONST | 6,956,700 | 0.4% | 76.9% |
| BINARY_OP_ADD_INT STORE_FAST | 6,752,340 | 0.4% | 77.3% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 6,678,900 | 0.4% | 77.7% |
| GET_ITER FOR_ITER_LIST | 6,662,880 | 0.4% | 78.1% |
| FOR_ITER_LIST STORE_FAST | 6,651,060 | 0.4% | 78.5% |
| LOAD_ATTR_WITH_HINT GET_ITER | 6,571,320 | 0.4% | 78.9% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 6,380,160 | 0.4% | 79.3% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 6,332,760 | 0.4% | 79.7% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 6,147,600 | 0.4% | 80.0% |
| BINARY_OP_ADD_INT STORE_GLOBAL | 6,147,600 | 0.4% | 80.4% |
| LOAD_ATTR CALL_PY_WITH_DEFAULTS | 6,112,620 | 0.4% | 80.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 6,074,820 | 0.4% | 81.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 5,997,240 | 0.4% | 81.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 5,897,160 | 0.4% | 81.9% |
| COPY TO_BOOL_INT | 5,844,120 | 0.4% | 82.2% |
| STORE_FAST COPY | 5,662,620 | 0.3% | 82.6% |
| COPY STORE_FAST | 5,662,620 | 0.3% | 82.9% |
| POP_TOP RETURN_CONST | 5,580,360 | 0.3% | 83.2% |
| POP_JUMP_IF_TRUE POP_TOP | 5,502,660 | 0.3% | 83.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 5,470,440 | 0.3% | 83.9% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 5,156,520 | 0.3% | 84.2% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 5,131,860 | 0.3% | 84.5% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 4,904,780 | 0.3% | 84.8% |
| STORE_GLOBAL LOAD_FAST | 4,863,540 | 0.3% | 85.1% |
| RETURN_CONST TO_BOOL_BOOL | 4,636,800 | 0.3% | 85.4% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 4,485,240 | 0.3% | 85.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 4,444,020 | 0.3% | 85.9% |
| STORE_ATTR_WITH_HINT ENTER_EXECUTOR | 4,345,140 | 0.3% | 86.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 4,338,820 | 0.3% | 86.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 4,263,660 | 0.3% | 86.7% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 4,138,440 | 0.2% | 87.0% |
| BINARY_OP_ADD_INT SWAP | 4,137,120 | 0.2% | 87.2% |
| LOAD_ATTR_WITH_HINT BINARY_SUBSCR_LIST_INT | 4,092,360 | 0.2% | 87.5% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 4,031,580 | 0.2% | 87.7% |
| STORE_SUBSCR_LIST_INT RETURN_CONST | 3,997,620 | 0.2% | 87.9% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 3,997,620 | 0.2% | 88.2% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_INSTANCE_VALUE | 3,966,720 | 0.2% | 88.4% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_INT | 3,775,080 | 0.2% | 88.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 3,629,220 | 0.2% | 88.9% |
| LOAD_ATTR_WITH_HINT TO_BOOL_BOOL | 3,579,480 | 0.2% | 89.1% |
| LOAD_CONST LOAD_FAST | 3,569,460 | 0.2% | 89.3% |
| ENTER_EXECUTOR LOAD_FAST | 3,563,280 | 0.2% | 89.5% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 3,547,680 | 0.2% | 89.7% |
| LOAD_FAST TO_BOOL_INT | 3,502,860 | 0.2% | 89.9% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 3,183,600 | 0.2% | 90.1% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 3,179,400 | 0.2% | 90.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 3,154,980 | 0.2% | 90.5% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 3,094,080 | 0.2% | 90.7% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 3,005,800 | 0.2% | 90.9% |


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
| LOAD_ATTR_WITH_HINT | 6,571,320 | 97.8% |
| LOAD_ATTR_INSTANCE_VALUE | 79,620 | 1.2% |
| CALL_BUILTIN_CLASS | 33,960 | 0.5% |
| LOAD_FAST | 24,000 | 0.4% |
| LOAD_CONST | 9,720 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 6,662,880 | 99.2% |
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
| POP_JUMP_IF_FALSE | 2,639,220 | 10.4% |
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
| BINARY_OP | 20,620 | 0.1% |


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
| POP_JUMP_IF_TRUE | 12,604,440 | 51.2% |
| STORE_ATTR_WITH_HINT | 4,345,140 | 17.6% |
| POP_TOP | 2,252,760 | 9.1% |
| STORE_FAST | 2,056,800 | 8.3% |
| POP_JUMP_IF_FALSE | 1,315,560 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 15,160,260 | 61.5% |
| LOAD_FAST | 3,563,280 | 14.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,263,320 | 9.2% |
| RETURN_CONST | 1,397,940 | 5.7% |
| LOAD_ATTR_MODULE | 1,333,020 | 5.4% |


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
| STORE_FAST | 7,140 | 97.5% |
| STORE_FAST_STORE_FAST | 180 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,140 | 97.5% |
| FOR_ITER_LIST | 180 | 2.5% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,514,700 | 42.8% |
| POP_TOP | 1,284,060 | 36.3% |
| STORE_ATTR_INSTANCE_VALUE | 682,860 | 19.3% |
| POP_JUMP_IF_TRUE | 43,200 | 1.2% |
| CALL_LIST_APPEND | 12,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,490,700 | 42.1% |
| LOAD_FAST | 1,359,180 | 38.4% |
| LOAD_FAST_LOAD_FAST | 678,300 | 19.2% |
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
| LOAD_ATTR_WITH_HINT | 19,116,900 | 42.8% |
| LOAD_FAST | 6,956,700 | 15.6% |
| LOAD_GLOBAL_MODULE | 6,147,600 | 13.8% |
| LOAD_CONST | 2,722,020 | 6.1% |
| STORE_ATTR_WITH_HINT | 2,573,400 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 14,337,660 | 32.1% |
| BINARY_OP_SUBTRACT_INT | 11,290,860 | 25.3% |
| COMPARE_OP_INT | 7,403,140 | 16.6% |
| LOAD_FAST | 3,569,460 | 8.0% |
| LOAD_CONST | 2,722,020 | 6.1% |


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
| STORE_FAST | 90,672,600 | 22.4% |
| POP_JUMP_IF_FALSE | 72,792,900 | 18.0% |
| LOAD_ATTR_WITH_HINT | 44,909,940 | 11.1% |
| RESUME_CHECK | 44,545,800 | 11.0% |
| LOAD_ATTR_INSTANCE_VALUE | 31,296,060 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 146,103,900 | 36.2% |
| LOAD_ATTR_INSTANCE_VALUE | 42,932,680 | 10.6% |
| LOAD_ATTR | 30,081,380 | 7.4% |
| RETURN_VALUE | 29,800,380 | 7.4% |
| COPY | 26,816,100 | 6.6% |


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
| LOAD_ATTR_INSTANCE_VALUE | 16,674,780 | 44.9% |
| STORE_ATTR_WITH_HINT | 7,499,340 | 20.2% |
| COMPARE_OP_INT | 4,485,240 | 12.1% |
| BINARY_OP_SUBTRACT_INT | 3,775,080 | 10.2% |
| CALL_PY_EXACT_ARGS | 3,179,400 | 8.6% |


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
| COMPARE_OP_INT | 59,283,600 | 66.2% |
| TO_BOOL_BOOL | 23,987,640 | 26.8% |
| TO_BOOL_INT | 6,074,820 | 6.8% |
| COMPARE_OP | 84,240 | 0.1% |
| IS_OP | 41,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 72,792,900 | 81.3% |
| LOAD_FAST_LOAD_FAST | 7,061,280 | 7.9% |
| POP_TOP | 2,639,220 | 2.9% |
| LOAD_GLOBAL_MODULE | 1,928,620 | 2.2% |
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
| COMPARE_OP_INT | 19,458,600 | 59.6% |
| TO_BOOL_BOOL | 6,380,160 | 19.5% |
| TO_BOOL_INT | 5,156,520 | 15.8% |
| TO_BOOL_ALWAYS_TRUE | 821,380 | 2.5% |
| COMPARE_OP_FLOAT | 795,660 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,604,440 | 38.6% |
| LOAD_FAST | 11,818,440 | 36.2% |
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
| LOAD_ATTR_WITH_HINT | 40,706,580 | 37.0% |
| RETURN_VALUE | 29,795,940 | 27.1% |
| BINARY_SUBSCR_LIST_INT | 7,558,340 | 6.9% |
| BINARY_OP_ADD_INT | 6,752,340 | 6.1% |
| FOR_ITER_LIST | 6,651,060 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 90,672,600 | 82.5% |
| LOAD_FAST_LOAD_FAST | 8,302,440 | 7.6% |
| COPY | 5,662,620 | 5.2% |
| ENTER_EXECUTOR | 2,056,800 | 1.9% |
| LOAD_GLOBAL_MODULE | 1,681,540 | 1.5% |


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
| BINARY_OP_ADD_INT | 6,147,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,863,540 | 79.1% |
| LOAD_GLOBAL_MODULE | 1,284,060 | 20.9% |


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
| LOAD_CONST | 14,337,660 | 79.9% |
| LOAD_ATTR_INSTANCE_VALUE | 2,514,120 | 14.0% |
| LOAD_ATTR_WITH_HINT | 1,023,600 | 5.7% |
| LOAD_FAST | 34,560 | 0.2% |
| LOAD_FAST_LOAD_FAST | 19,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,752,340 | 37.6% |
| STORE_GLOBAL | 6,147,600 | 34.3% |
| SWAP | 4,137,120 | 23.1% |
| CALL_BUILTIN_CLASS | 837,900 | 4.7% |
| RETURN_VALUE | 34,560 | 0.2% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 837,900 | 92.2% |
| LOAD_GLOBAL_MODULE | 70,980 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 837,900 | 92.2% |
| CALL_BUILTIN_CLASS | 36,420 | 4.0% |
| LOAD_FAST | 34,560 | 3.8% |


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
| LOAD_FAST | 14,291,540 | 69.1% |
| LOAD_ATTR_WITH_HINT | 4,092,360 | 19.8% |
| BINARY_OP_SUBTRACT_INT | 1,296,060 | 6.3% |
| LOAD_GLOBAL_MODULE | 981,720 | 4.7% |
| RETURN_VALUE | 34,560 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 9,166,440 | 44.3% |
| STORE_FAST | 7,558,340 | 36.5% |
| CALL_PY_EXACT_ARGS | 2,640,840 | 12.8% |
| LOAD_FAST | 1,296,060 | 6.3% |
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
| LOAD_ATTR_INSTANCE_VALUE | 3,094,080 | 90.3% |
| LOAD_ATTR_WITH_HINT | 331,560 | 9.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,308,180 | 38.2% |
| LOAD_CONST | 1,296,060 | 37.8% |
| LOAD_FAST | 477,840 | 13.9% |
| COMPARE_OP_INT | 331,560 | 9.7% |
| CALL | 12,000 | 0.4% |


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
| LOAD_FAST | 26,471,740 | 57.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,678,900 | 14.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,183,600 | 6.9% |
| LOAD_FAST_LOAD_FAST | 3,179,400 | 6.9% |
| BINARY_SUBSCR_LIST_INT | 2,640,840 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 46,169,400 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 30,428,560 | 38.6% |
| LOAD_CONST | 7,403,140 | 9.4% |
| LOAD_FAST_LOAD_FAST | 4,485,240 | 5.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,547,680 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 59,283,600 | 75.3% |
| POP_JUMP_IF_TRUE | 19,458,600 | 24.7% |
| COMPARE_OP | 24,120 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 6,662,880 | 99.8% |
| SWAP | 12,060 | 0.2% |
| JUMP_BACKWARD | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,651,060 | 99.6% |
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
| LOAD_FAST | 42,932,680 | 56.9% |
| LOAD_FAST_LOAD_FAST | 16,674,780 | 22.1% |
| COPY | 8,223,420 | 10.9% |
| LOAD_ATTR_WITH_HINT | 3,966,720 | 5.3% |
| LOAD_ATTR_INSTANCE_VALUE | 3,629,220 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,296,060 | 41.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,974,940 | 17.2% |
| LOAD_ATTR_METHOD_NO_DICT | 4,444,020 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 3,629,220 | 4.8% |
| COMPARE_OP_INT | 3,547,680 | 4.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,444,020 | 98.7% |
| LOAD_FAST | 60,300 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,154,980 | 70.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,296,060 | 28.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 53,280 | 1.2% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 12,974,940 | 51.6% |
| LOAD_FAST | 9,898,980 | 39.4% |
| ENTER_EXECUTOR | 2,263,320 | 9.0% |
| STORE_FAST_LOAD_FAST | 12,060 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,549,240 | 49.9% |
| CALL_PY_EXACT_ARGS | 6,678,900 | 26.6% |
| LOAD_FAST_LOAD_FAST | 5,897,160 | 23.4% |
| LOAD_GLOBAL_MODULE | 24,000 | 0.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 120 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,005,800 | 69.3% |
| ENTER_EXECUTOR | 1,333,020 | 30.7% |
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
| LOAD_FAST | 146,103,900 | 83.4% |
| ENTER_EXECUTOR | 15,160,260 | 8.7% |
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
| LOAD_ATTR_INSTANCE_VALUE | 2,133,960 | 37.7% |
| RESUME_CHECK | 1,798,140 | 31.7% |
| POP_JUMP_IF_FALSE | 1,308,300 | 23.1% |
| LOAD_FAST | 331,680 | 5.9% |
| STORE_ATTR_INSTANCE_VALUE | 58,140 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,263,660 | 75.2% |
| LOAD_GLOBAL_MODULE | 1,356,640 | 23.9% |
| LOAD_GLOBAL_BUILTIN | 24,600 | 0.4% |
| CALL_BUILTIN_CLASS | 12,120 | 0.2% |
| LOAD_CONST | 9,780 | 0.2% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 16,524,060 | 34.6% |
| LOAD_FAST | 15,281,860 | 32.0% |
| RESUME_CHECK | 4,904,780 | 10.3% |
| POP_JUMP_IF_FALSE | 1,928,620 | 4.0% |
| STORE_FAST | 1,681,540 | 3.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 30,428,560 | 63.7% |
| LOAD_CONST | 6,147,600 | 12.9% |
| LOAD_FAST | 5,997,240 | 12.5% |
| LOAD_ATTR_MODULE | 3,005,800 | 6.3% |
| BINARY_SUBSCR_LIST_INT | 981,720 | 2.1% |


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
| CALL_PY_EXACT_ARGS | 46,169,400 | 83.5% |
| CALL_PY_WITH_DEFAULTS | 6,332,760 | 11.4% |
| CALL_KW | 2,722,020 | 4.9% |
| CALL_ALLOC_AND_ENTER_INIT | 46,140 | 0.1% |
| CALL | 41,160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 44,545,800 | 80.5% |
| LOAD_GLOBAL_MODULE | 4,904,780 | 8.9% |
| LOAD_FAST_LOAD_FAST | 4,031,580 | 7.3% |
| LOAD_GLOBAL_BUILTIN | 1,798,140 | 3.3% |
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
| ENTER_EXECUTOR | 4,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,470,440 | 38.8% |
| RETURN_CONST | 4,138,440 | 29.3% |
| LOAD_FAST_LOAD_FAST | 2,582,220 | 18.3% |
| ENTER_EXECUTOR | 1,000,860 | 7.1% |
| JUMP_FORWARD | 682,860 | 4.8% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 12,748,560 | 41.7% |
| LOAD_FAST | 10,287,680 | 33.7% |
| LOAD_FAST_LOAD_FAST | 7,499,340 | 24.6% |
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
| ENTER_EXECUTOR | 777,120 | 93.7% |
| LOAD_ATTR_INSTANCE_VALUE | 25,800 | 3.1% |
| LOAD_FAST | 25,580 | 3.1% |
| TO_BOOL_NONE | 440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 821,380 | 99.1% |
| POP_JUMP_IF_FALSE | 7,140 | 0.9% |
| TO_BOOL_NONE | 420 | 0.1% |


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
| COPY | 5,844,120 | 52.0% |
| LOAD_FAST | 3,502,860 | 31.2% |
| RETURN_VALUE | 1,249,740 | 11.1% |
| RETURN_CONST | 634,620 | 5.6% |
| TO_BOOL_BOOL | 12,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,074,820 | 54.0% |
| POP_JUMP_IF_TRUE | 5,156,520 | 45.9% |
| TO_BOOL_BOOL | 12,000 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 19,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 19,140 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,940 | 34.6% |
| LOAD_ATTR_INSTANCE_VALUE | 12,480 | 33.4% |
| ENTER_EXECUTOR | 11,520 | 30.8% |
| TO_BOOL_ALWAYS_TRUE | 420 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 36,920 | 98.8% |
| TO_BOOL_ALWAYS_TRUE | 440 | 1.2% |


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
| specialization.deopt |        24860 | 0.1% |
|          hit |     43079400 | 97.0% |
|         miss |      1316720 | 3.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 24,860 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     13780860 | 28.4% |
| specialization.deopt |         6000 | 0.0% |
|          hit |     34430160 | 70.9% |
|         miss |       318000 | 0.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 6,020 | 18.4% |
| Failure | 26,620 | 81.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 23,260 | 87.4% |
| xor | 2,240 | 8.4% |
| multiply different types | 640 | 2.4% |
| true divide different types | 400 | 1.5% |
| remainder | 40 | 0.2% |
| floor divide | 40 | 0.2% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5284920 | 7.7% |
|          hit |     63173820 | 92.3% |
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
|          hit |     79536900 | 99.8% |
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
|          hit |      6718800 | 100.0% |


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
| specialization.deferred |     30081320 | 9.6% |
| specialization.deopt |          120 | 0.0% |
|          hit |    284684020 | 90.4% |
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
|          hit |     53466880 | 100.0% |

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
|          hit |         9720 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 790,036,380 | 47.7% |
| Not specialized | 173,236,680 | 10.5% |
| Specialized | 694,194,280 | 41.9% |

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
| TO_BOOL_NONE | 23,040 | 1.3% |
| TO_BOOL_ALWAYS_TRUE | 21,680 | 1.3% |
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
| Interpreter increfs | 638,045,720 | 82.0% |
| Interpreter decrefs | 692,028,420 | 85.1% |
| Increfs | 140,069,540 | 18.0% |
| Decrefs | 120,781,260 | 14.9% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 9,720 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 32,049,997 |  |
| Method cache misses | 3,603 |  |
| Method cache collisions | 3,606 |  |
| Method cache dunder hits | 297 |  |
| Method cache dunder misses | 3 |  |


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
| Optimization attempts | 420 |  |
| Traces created | 0 | 0.0% |
| Traces executed | 24,633,420 |  |
| Uops executed | 266,299,140 | 10 |
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
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 4,966,680 | 20.2% |
| <= 16 | 18,212,220 | 73.9% |
| <= 32 | 1,342,860 | 5.5% |
| <= 64 | 60,000 | 0.2% |
| <= 128 | 9,360 | 0.0% |
| <= 256 | 7,260 | 0.0% |
| <= 512 | 6,420 | 0.0% |
| <= 1024 | 16,440 | 0.1% |
| <= 2048 | 12,120 | 0.0% |
| <= 4096 | 60 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 64,455,060 | 24.2% | 24.2% |
| _POP_JUMP_IF_TRUE | 28,027,560 | 10.5% | 34.7% |
| _EXIT_TRACE | 23,844,780 | 9.0% | 43.7% |
| _ITER_CHECK_LIST | 23,611,080 | 8.9% | 52.5% |
| _IS_ITER_EXHAUSTED_LIST | 23,611,080 | 8.9% | 61.4% |
| LOAD_FAST | 23,445,900 | 8.8% | 70.2% |
| STORE_FAST | 21,092,880 | 7.9% | 78.1% |
| _ITER_NEXT_LIST | 18,640,080 | 7.0% | 85.1% |
| POP_TOP | 5,002,680 | 1.9% | 87.0% |
| _GUARD_GLOBALS_VERSION | 3,688,380 | 1.4% | 88.4% |
| _JUMP_TO_TOP | 2,669,160 | 1.0% | 89.4% |
| _LOAD_GLOBAL_MODULE | 2,374,800 | 0.9% | 90.3% |
| _ITER_CHECK_RANGE | 2,335,860 | 0.9% | 91.2% |
| _IS_ITER_EXHAUSTED_RANGE | 2,335,860 | 0.9% | 92.1% |
| _ITER_NEXT_RANGE | 2,313,900 | 0.9% | 92.9% |
| _LOAD_ATTR_INSTANCE_VALUE | 2,291,520 | 0.9% | 93.8% |
| _GUARD_TYPE_VERSION | 2,291,520 | 0.9% | 94.6% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 2,291,520 | 0.9% | 95.5% |
| LOAD_CONST | 1,996,200 | 0.7% | 96.3% |
| STORE_ATTR | 1,939,200 | 0.7% | 97.0% |
| TO_BOOL_NONE | 1,531,200 | 0.6% | 97.6% |
| _LOAD_GLOBAL_BUILTINS | 1,313,580 | 0.5% | 98.0% |
| _GUARD_BUILTINS_VERSION | 1,313,580 | 0.5% | 98.5% |
| TO_BOOL_BOOL | 1,308,120 | 0.5% | 99.0% |
| COPY | 1,031,400 | 0.4% | 99.4% |
| LIST_APPEND | 964,800 | 0.4% | 99.8% |
| COMPARE_OP_INT | 120,480 | 0.0% | 99.8% |
| _POP_JUMP_IF_FALSE | 105,960 | 0.0% | 99.9% |
| _GUARD_BOTH_INT | 67,500 | 0.0% | 99.9% |
| _BINARY_OP_ADD_INT | 67,500 | 0.0% | 99.9% |
| SWAP | 61,800 | 0.0% | 99.9% |
| _ITER_CHECK_TUPLE | 38,880 | 0.0% | 100.0% |
| _IS_ITER_EXHAUSTED_TUPLE | 38,880 | 0.0% | 100.0% |
| _ITER_NEXT_TUPLE | 29,160 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 29,160 | 0.0% | 100.0% |
| COMPARE_OP | 7,140 | 0.0% | 100.0% |
| TO_BOOL_ALWAYS_TRUE | 4,620 | 0.0% | 100.0% |
| PUSH_NULL | 3,180 | 0.0% | 100.0% |
| CALL_BUILTIN_O | 3,180 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| LOAD_ATTR_METHOD_WITH_VALUES | 420 |


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
