
# Pystats results

- benchmark: go
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 496,435,280 | 25.1% | 25.1% |  |
| LOAD_ATTR_WITH_HINT | 205,301,380 | 10.4% | 35.4% |  |
| STORE_FAST | 128,499,140 | 6.5% | 41.9% |  |
| POP_JUMP_IF_FALSE | 103,472,820 | 5.2% | 47.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 95,738,560 | 4.8% | 52.0% |  |
| COMPARE_OP_INT | 81,240,860 | 4.1% | 56.1% | 0.0% |
| RESUME_CHECK | 67,711,640 | 3.4% | 59.5% | 0.0% |
| LOAD_CONST | 56,279,180 | 2.8% | 62.3% |  |
| CALL_PY_EXACT_ARGS | 55,521,940 | 2.8% | 65.1% |  |
| RETURN_VALUE | 47,036,000 | 2.4% | 67.5% |  |
| LOAD_FAST_LOAD_FAST | 46,874,580 | 2.4% | 69.9% |  |
| COPY | 46,483,600 | 2.3% | 72.2% |  |
| STORE_ATTR_WITH_HINT | 43,272,860 | 2.2% | 74.4% | 0.0% |
| TO_BOOL_BOOL | 40,528,280 | 2.0% | 76.5% | 2.1% |
| LOAD_ATTR | 40,127,520 | 2.0% | 78.5% |  |
| LOAD_GLOBAL_MODULE | 39,189,360 | 2.0% | 80.5% |  |
| POP_TOP | 32,380,700 | 1.6% | 82.1% |  |
| ENTER_EXECUTOR | 31,777,860 | 1.6% | 83.7% |  |
| POP_JUMP_IF_TRUE | 31,388,420 | 1.6% | 85.3% |  |
| SWAP | 27,520,160 | 1.4% | 86.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 25,801,200 | 1.3% | 88.0% | 0.0% |
| BINARY_SUBSCR_LIST_INT | 25,042,820 | 1.3% | 89.2% | 0.2% |
| RETURN_CONST | 24,269,760 | 1.2% | 90.5% |  |
| BINARY_OP_SUBTRACT_INT | 20,087,760 | 1.0% | 91.5% |  |
| BINARY_OP_ADD_INT | 19,487,560 | 1.0% | 92.5% | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 18,809,000 | 0.9% | 93.4% |  |
| BINARY_OP | 18,666,540 | 0.9% | 94.4% |  |
| TO_BOOL_INT | 13,262,080 | 0.7% | 95.0% | 6.4% |
| STORE_SUBSCR_LIST_INT | 11,329,340 | 0.6% | 95.6% |  |
| CALL_PY_WITH_DEFAULTS | 8,443,640 | 0.4% | 96.0% |  |
| GET_ITER | 7,682,000 | 0.4% | 96.4% |  |
| FOR_ITER_LIST | 7,633,320 | 0.4% | 96.8% |  |
| STORE_GLOBAL | 6,936,240 | 0.4% | 97.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,972,000 | 0.3% | 97.4% |  |
| CALL_BUILTIN_CLASS | 4,738,720 | 0.2% | 97.7% |  |
| JUMP_FORWARD | 4,683,400 | 0.2% | 97.9% |  |
| LOAD_GLOBAL_BUILTIN | 4,091,080 | 0.2% | 98.1% |  |
| CALL_KW | 3,629,360 | 0.2% | 98.3% |  |
| CALL | 3,555,820 | 0.2% | 98.5% |  |
| CALL_LEN | 2,830,360 | 0.1% | 98.6% |  |
| STORE_FAST_STORE_FAST | 2,558,200 | 0.1% | 98.8% |  |
| UNARY_NOT | 2,516,720 | 0.1% | 98.9% |  |
| CONTAINS_OP | 2,516,720 | 0.1% | 99.0% |  |
| CALL_LIST_APPEND | 2,478,300 | 0.1% | 99.1% |  |
| PUSH_NULL | 2,333,180 | 0.1% | 99.3% |  |
| LOAD_ATTR_MODULE | 2,271,180 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,728,200 | 0.1% | 99.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,728,120 | 0.1% | 99.5% | 0.0% |
| LIST_APPEND | 1,345,200 | 0.1% | 99.6% |  |
| CALL_BUILTIN_O | 1,233,600 | 0.1% | 99.7% |  |
| BINARY_OP_MULTIPLY_INT | 1,178,180 | 0.1% | 99.7% |  |
| BINARY_OP_ADD_FLOAT | 1,117,180 | 0.1% | 99.8% |  |
| CALL_BUILTIN_FAST | 1,117,180 | 0.1% | 99.8% |  |
| TO_BOOL_ALWAYS_TRUE | 1,105,660 | 0.1% | 99.9% | 2.6% |
| COMPARE_OP_FLOAT | 1,061,280 | 0.1% | 100.0% | 2.4% |
| COMPARE_OP | 142,200 | 0.0% | 100.0% |  |
| BUILD_LIST | 90,400 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 71,000 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 61,380 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 61,380 | 0.0% | 100.0% |  |
| IS_OP | 54,880 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 54,880 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 50,560 | 0.0% | 100.0% | 60.8% |
| FOR_ITER_RANGE | 46,780 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 45,280 | 0.0% | 100.0% |  |
| STORE_ATTR | 40,780 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 32,400 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,300 | 0.0% | 100.0% |  |
| NOP | 16,080 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 14,860 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 14,540 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 14,120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 3,720 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 3,480 | 0.0% | 100.0% |  |
| TO_BOOL | 960 | 0.0% | 100.0% |  |
| FOR_ITER | 800 | 0.0% | 100.0% |  |
| RESUME | 740 | 0.0% | 100.0% | 10.8% |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 200 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 160 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 160 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 160 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 140 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 80 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 40 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_WITH_HINT | 188,545,320 | 9.5% | 9.5% |
| STORE_FAST LOAD_FAST | 106,316,920 | 5.4% | 14.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 84,169,380 | 4.2% | 19.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 66,149,520 | 3.3% | 22.5% |
| LOAD_ATTR_WITH_HINT LOAD_FAST | 58,824,880 | 3.0% | 25.4% |
| RESUME_CHECK LOAD_FAST | 56,345,960 | 2.8% | 28.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 55,521,940 | 2.8% | 31.1% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 52,423,240 | 2.6% | 33.7% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 41,904,280 | 2.1% | 35.9% |
| LOAD_ATTR_WITH_HINT STORE_FAST | 41,377,500 | 2.1% | 37.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 40,467,740 | 2.0% | 40.0% |
| LOAD_FAST RETURN_VALUE | 39,733,840 | 2.0% | 42.0% |
| RETURN_VALUE STORE_FAST | 39,727,860 | 2.0% | 44.0% |
| LOAD_FAST COPY | 33,857,160 | 1.7% | 45.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 32,764,880 | 1.7% | 47.4% |
| LOAD_FAST LOAD_ATTR | 31,996,500 | 1.6% | 49.0% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 30,749,320 | 1.6% | 50.5% |
| LOAD_FAST TO_BOOL_BOOL | 28,668,640 | 1.4% | 52.0% |
| STORE_ATTR_WITH_HINT LOAD_FAST | 28,412,220 | 1.4% | 53.4% |
| LOAD_ATTR LOAD_FAST | 27,865,160 | 1.4% | 54.8% |
| LOAD_ATTR_WITH_HINT LOAD_CONST | 23,585,020 | 1.2% | 56.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 22,232,760 | 1.1% | 57.1% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 20,401,160 | 1.0% | 58.2% |
| RETURN_CONST POP_TOP | 19,650,560 | 1.0% | 59.2% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 17,794,560 | 0.9% | 60.0% |
| POP_TOP LOAD_FAST | 16,382,180 | 0.8% | 60.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 15,571,680 | 0.8% | 61.7% |
| COPY LOAD_ATTR_WITH_HINT | 15,093,800 | 0.8% | 62.4% |
| SWAP STORE_ATTR_WITH_HINT | 15,093,800 | 0.8% | 63.2% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 15,059,240 | 0.8% | 63.9% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 15,054,240 | 0.8% | 64.7% |
| LOAD_FAST STORE_ATTR_WITH_HINT | 14,980,160 | 0.8% | 65.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 14,718,920 | 0.7% | 66.2% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 12,986,120 | 0.7% | 66.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 12,473,880 | 0.6% | 67.5% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 12,263,240 | 0.6% | 68.1% |
| BINARY_OP SWAP | 12,222,080 | 0.6% | 68.7% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 12,033,620 | 0.6% | 69.3% |
| BINARY_OP_SUBTRACT_INT SWAP | 11,517,300 | 0.6% | 69.9% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 11,329,240 | 0.6% | 70.5% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 10,970,760 | 0.6% | 71.0% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 10,929,380 | 0.6% | 71.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 10,201,120 | 0.5% | 72.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_WITH_HINT | 9,997,720 | 0.5% | 72.6% |
| LOAD_CONST COMPARE_OP_INT | 9,870,700 | 0.5% | 73.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 9,415,040 | 0.5% | 73.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 9,290,360 | 0.5% | 74.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 8,911,800 | 0.4% | 74.5% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 8,817,180 | 0.4% | 75.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 8,511,520 | 0.4% | 75.4% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 8,443,640 | 0.4% | 75.8% |
| LOAD_ATTR CALL_PY_WITH_DEFAULTS | 8,150,120 | 0.4% | 76.2% |
| ENTER_EXECUTOR LOAD_ATTR | 8,117,140 | 0.4% | 76.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 7,980,760 | 0.4% | 77.0% |
| LOAD_FAST LOAD_CONST | 7,871,520 | 0.4% | 77.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 7,862,780 | 0.4% | 77.8% |
| ENTER_EXECUTOR LOAD_FAST | 7,853,040 | 0.4% | 78.2% |
| COPY TO_BOOL_INT | 7,792,000 | 0.4% | 78.6% |
| BINARY_OP_ADD_INT STORE_FAST | 7,772,400 | 0.4% | 79.0% |
| GET_ITER FOR_ITER_LIST | 7,607,380 | 0.4% | 79.4% |
| FOR_ITER_LIST STORE_FAST | 7,599,260 | 0.4% | 79.8% |
| COPY STORE_FAST | 7,550,160 | 0.4% | 80.2% |
| STORE_FAST COPY | 7,550,160 | 0.4% | 80.5% |
| LOAD_ATTR_WITH_HINT GET_ITER | 7,501,100 | 0.4% | 80.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 7,293,780 | 0.4% | 81.3% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 7,246,260 | 0.4% | 81.7% |
| STORE_ATTR_WITH_HINT ENTER_EXECUTOR | 7,073,160 | 0.4% | 82.0% |
| BINARY_OP_ADD_INT STORE_GLOBAL | 6,936,180 | 0.4% | 82.4% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 6,936,180 | 0.4% | 82.7% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 6,875,280 | 0.3% | 83.1% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 6,842,420 | 0.3% | 83.4% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 6,370,820 | 0.3% | 83.7% |
| LOAD_CONST LOAD_FAST | 6,054,440 | 0.3% | 84.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 5,891,500 | 0.3% | 84.3% |
| POP_TOP RETURN_CONST | 5,826,000 | 0.3% | 84.6% |
| POP_JUMP_IF_TRUE POP_TOP | 5,722,360 | 0.3% | 84.9% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 5,517,820 | 0.3% | 85.2% |
| LOAD_ATTR_WITH_HINT BINARY_SUBSCR_LIST_INT | 5,456,440 | 0.3% | 85.5% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,432,160 | 0.3% | 85.7% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 5,375,360 | 0.3% | 86.0% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 5,330,140 | 0.3% | 86.3% |
| STORE_SUBSCR_LIST_INT RETURN_CONST | 5,330,140 | 0.3% | 86.5% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_INSTANCE_VALUE | 5,288,800 | 0.3% | 86.8% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 5,279,000 | 0.3% | 87.1% |
| STORE_GLOBAL LOAD_FAST | 5,224,160 | 0.3% | 87.3% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_INT | 5,033,360 | 0.3% | 87.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 4,805,140 | 0.2% | 87.8% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 4,730,160 | 0.2% | 88.1% |
| STORE_ATTR_WITH_HINT LOAD_CONST | 4,709,340 | 0.2% | 88.3% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 4,244,680 | 0.2% | 88.5% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 4,205,500 | 0.2% | 88.7% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 4,172,960 | 0.2% | 89.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,947,700 | 0.2% | 89.2% |
| RETURN_CONST TO_BOOL_BOOL | 3,712,460 | 0.2% | 89.3% |
| LOAD_CONST CALL_KW | 3,629,360 | 0.2% | 89.5% |
| LOAD_CONST LOAD_CONST | 3,629,360 | 0.2% | 89.7% |
| CALL_KW RESUME_CHECK | 3,629,340 | 0.2% | 89.9% |
| BINARY_OP_ADD_INT SWAP | 3,618,100 | 0.2% | 90.1% |
| BINARY_SUBSCR_LIST_INT CALL_PY_EXACT_ARGS | 3,521,040 | 0.2% | 90.2% |
| POP_JUMP_IF_FALSE POP_TOP | 3,517,680 | 0.2% | 90.4% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME | 100 | 71.4% |
| RESUME_CHECK | 40 | 28.6% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,000 | 57.5% |
| BINARY_SUBSCR_LIST_INT | 1,080 | 31.0% |
| BINARY_SUBSCR | 200 | 5.7% |
| RETURN_VALUE | 40 | 1.1% |
| BINARY_OP | 40 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,780 | 51.1% |
| BINARY_SUBSCR_LIST_INT | 1,340 | 38.5% |
| BINARY_SUBSCR | 200 | 5.7% |
| BINARY_OP | 60 | 1.7% |
| CALL | 60 | 1.7% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 61,380 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 61,380 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 7,501,100 | 97.6% |
| LOAD_ATTR_INSTANCE_VALUE | 90,420 | 1.2% |
| CALL_BUILTIN_CLASS | 45,180 | 0.6% |
| LOAD_FAST | 32,000 | 0.4% |
| LOAD_CONST | 12,960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 7,607,380 | 99.0% |
| LOAD_FAST_AND_CLEAR | 45,280 | 0.6% |
| FOR_ITER_RANGE | 16,040 | 0.2% |
| FOR_ITER_TUPLE | 12,940 | 0.2% |
| FOR_ITER | 360 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 140 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 16,000 | 99.5% |
| POP_TOP | 80 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,000 | 99.5% |
| LOAD_DEREF | 80 | 0.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 19,650,560 | 60.7% |
| POP_JUMP_IF_TRUE | 5,722,360 | 17.7% |
| POP_JUMP_IF_FALSE | 3,517,680 | 10.9% |
| CALL_METHOD_DESCRIPTOR_O | 1,728,200 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,728,120 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,382,180 | 50.6% |
| RETURN_CONST | 5,826,000 | 18.0% |
| ENTER_EXECUTOR | 3,000,960 | 9.3% |
| LOAD_CONST | 2,516,800 | 7.8% |
| JUMP_FORWARD | 1,712,100 | 5.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,271,120 | 97.3% |
| LOAD_FAST | 61,840 | 2.7% |
| LOAD_ATTR | 140 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,178,880 | 50.5% |
| LOAD_GLOBAL_MODULE | 1,117,160 | 47.9% |
| CALL | 17,000 | 0.7% |
| LOAD_CONST | 13,260 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 6,760 | 0.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,733,840 | 84.5% |
| CONTAINS_OP | 2,516,720 | 5.4% |
| RETURN_VALUE | 1,799,200 | 3.8% |
| BINARY_OP_ADD_FLOAT | 1,117,180 | 2.4% |
| POP_JUMP_IF_FALSE | 1,034,640 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 39,727,860 | 84.5% |
| RETURN_VALUE | 1,799,200 | 3.8% |
| CALL_PY_EXACT_ARGS | 1,744,120 | 3.7% |
| TO_BOOL_INT | 1,666,320 | 3.5% |
| LOAD_FAST | 1,151,480 | 2.4% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 100 | 50.0% |
| LOAD_FAST | 60 | 30.0% |
| LOAD_FAST_LOAD_FAST | 20 | 10.0% |
| RETURN_CONST | 20 | 10.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 41.7% |
| COPY | 200 | 20.8% |
| RETURN_CONST | 120 | 12.5% |
| LOAD_ATTR | 100 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 240 | 25.0% |
| POP_JUMP_IF_FALSE | 220 | 22.9% |
| POP_JUMP_IF_TRUE | 220 | 22.9% |
| TO_BOOL_INT | 140 | 14.6% |
| TO_BOOL_ALWAYS_TRUE | 60 | 6.2% |


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 2,516,700 | 100.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,516,720 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 10,929,380 | 58.6% |
| LOAD_FAST | 3,495,800 | 18.7% |
| ENTER_EXECUTOR | 1,736,940 | 9.3% |
| BINARY_OP_MULTIPLY_INT | 1,117,180 | 6.0% |
| CALL_BUILTIN_CLASS | 1,117,180 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 12,222,080 | 65.5% |
| CALL_BUILTIN_CLASS | 3,495,640 | 18.7% |
| STORE_FAST | 1,792,000 | 9.6% |
| CALL_BUILTIN_O | 1,117,160 | 6.0% |
| LOAD_FAST | 13,020 | 0.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 45,280 | 50.1% |
| STORE_ATTR_INSTANCE_VALUE | 16,140 | 17.9% |
| LOAD_FAST | 16,000 | 17.7% |
| STORE_FAST_STORE_FAST | 12,960 | 14.3% |
| STORE_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 45,280 | 50.1% |
| LOAD_FAST | 29,120 | 32.2% |
| STORE_FAST | 16,000 | 17.7% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 120 | 75.0% |
| CALL | 40 | 25.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,513,860 | 98.8% |
| PUSH_NULL | 17,000 | 0.5% |
| LOAD_CONST | 13,320 | 0.4% |
| CALL_LEN | 6,780 | 0.2% |
| CALL | 1,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,495,880 | 98.3% |
| RESUME_CHECK | 55,160 | 1.6% |
| CALL | 1,520 | 0.0% |
| CALL_PY_EXACT_ARGS | 840 | 0.0% |
| RESUME | 600 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,629,360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,629,340 | 100.0% |
| RESUME | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,340 | 28.4% |
| LOAD_FAST_LOAD_FAST | 40,300 | 28.3% |
| COMPARE_OP_INT | 32,100 | 22.6% |
| RETURN_VALUE | 16,000 | 11.3% |
| ENTER_EXECUTOR | 9,520 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 122,260 | 86.0% |
| STORE_FAST | 16,000 | 11.3% |
| COMPARE_OP | 1,600 | 1.1% |
| POP_JUMP_IF_TRUE | 1,000 | 0.7% |
| COMPARE_OP_INT | 860 | 0.6% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,516,700 | 100.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,516,720 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,857,160 | 72.8% |
| STORE_FAST | 7,550,160 | 16.2% |
| UNARY_NOT | 2,516,720 | 5.4% |
| LOAD_CONST | 2,516,720 | 5.4% |
| SWAP | 26,840 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 15,093,800 | 32.5% |
| LOAD_ATTR_INSTANCE_VALUE | 10,970,760 | 23.6% |
| TO_BOOL_INT | 7,792,000 | 16.8% |
| STORE_FAST | 7,550,160 | 16.2% |
| STORE_FAST_STORE_FAST | 2,516,720 | 5.4% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 50.0% |
| CALL_FUNCTION_EX | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 140 | 87.5% |
| RESUME | 20 | 12.5% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 12,986,120 | 40.9% |
| STORE_ATTR_WITH_HINT | 7,073,160 | 22.3% |
| POP_TOP | 3,000,960 | 9.4% |
| ENTER_EXECUTOR | 2,431,080 | 7.7% |
| STORE_FAST | 1,796,980 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 8,117,140 | 25.5% |
| LOAD_FAST | 7,853,040 | 24.7% |
| CALL | 3,513,860 | 11.1% |
| STORE_ATTR_WITH_HINT | 3,200,480 | 10.1% |
| ENTER_EXECUTOR | 2,431,080 | 7.7% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 360 | 45.0% |
| JUMP_BACKWARD | 360 | 45.0% |
| SWAP | 80 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 340 | 42.5% |
| FOR_ITER_LIST | 280 | 35.0% |
| FOR_ITER_RANGE | 100 | 12.5% |
| RETURN_CONST | 20 | 2.5% |
| STORE_FAST_LOAD_FAST | 20 | 2.5% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 54,860 | 100.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 54,880 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,180 | 28.1% |
| POP_TOP | 2,740 | 18.4% |
| STORE_FAST | 2,380 | 16.0% |
| LIST_APPEND | 1,360 | 9.2% |
| STORE_ATTR_WITH_HINT | 960 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 9,600 | 64.6% |
| FOR_ITER_TUPLE | 1,580 | 10.6% |
| FOR_ITER_RANGE | 1,500 | 10.1% |
| ENTER_EXECUTOR | 860 | 5.8% |
| LOAD_FAST | 640 | 4.3% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,019,600 | 43.1% |
| POP_TOP | 1,712,100 | 36.6% |
| STORE_ATTR_INSTANCE_VALUE | 910,440 | 19.4% |
| POP_JUMP_IF_TRUE | 25,240 | 0.5% |
| CALL_LIST_APPEND | 15,980 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,987,580 | 42.4% |
| LOAD_FAST | 1,778,700 | 38.0% |
| LOAD_FAST_LOAD_FAST | 904,400 | 19.3% |
| LOAD_CONST | 12,700 | 0.3% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,276,960 | 94.9% |
| RETURN_VALUE | 51,820 | 3.9% |
| LOAD_CONST | 16,400 | 1.2% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,343,840 | 99.9% |
| JUMP_BACKWARD | 1,360 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,996,500 | 79.7% |
| ENTER_EXECUTOR | 8,117,140 | 20.2% |
| LOAD_ATTR | 12,120 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 500 | 0.0% |
| COPY | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,865,160 | 69.4% |
| CALL_PY_WITH_DEFAULTS | 8,150,120 | 20.3% |
| LOAD_CONST | 3,367,380 | 8.4% |
| LOAD_FAST_LOAD_FAST | 672,100 | 1.7% |
| STORE_FAST | 55,040 | 0.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 23,585,020 | 41.9% |
| LOAD_FAST | 7,871,520 | 14.0% |
| LOAD_GLOBAL_MODULE | 6,936,180 | 12.3% |
| STORE_ATTR_WITH_HINT | 4,709,340 | 8.4% |
| LOAD_CONST | 3,629,360 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 15,054,240 | 26.7% |
| BINARY_OP_ADD_INT | 14,718,920 | 26.2% |
| COMPARE_OP_INT | 9,870,700 | 17.5% |
| LOAD_FAST | 6,054,440 | 10.8% |
| CALL_KW | 3,629,360 | 6.4% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 33.3% |
| STORE_FAST | 80 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 80 | 33.3% |
| LOAD_FAST | 80 | 33.3% |
| STORE_FAST | 80 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 106,316,920 | 21.4% |
| POP_JUMP_IF_FALSE | 84,169,380 | 17.0% |
| LOAD_ATTR_WITH_HINT | 58,824,880 | 11.8% |
| RESUME_CHECK | 56,345,960 | 11.4% |
| LOAD_ATTR_INSTANCE_VALUE | 40,467,740 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 188,545,320 | 38.0% |
| LOAD_ATTR_INSTANCE_VALUE | 52,423,240 | 10.6% |
| RETURN_VALUE | 39,733,840 | 8.0% |
| COPY | 33,857,160 | 6.8% |
| CALL_PY_EXACT_ARGS | 32,764,880 | 6.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 45,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 45,280 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,415,040 | 20.1% |
| STORE_FAST | 8,511,520 | 18.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,862,780 | 16.8% |
| RESUME_CHECK | 5,375,360 | 11.5% |
| STORE_SUBSCR_LIST_INT | 5,330,140 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 22,232,760 | 47.4% |
| STORE_ATTR_WITH_HINT | 9,997,720 | 21.3% |
| BINARY_OP_SUBTRACT_INT | 5,033,360 | 10.7% |
| CALL_PY_EXACT_ARGS | 4,205,500 | 9.0% |
| COMPARE_OP_INT | 3,421,780 | 7.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560 | 15.1% |
| POP_JUMP_IF_FALSE | 520 | 14.0% |
| LOAD_ATTR | 300 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 300 | 8.1% |
| LOAD_GLOBAL | 260 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,380 | 37.1% |
| LOAD_GLOBAL_BUILTIN | 600 | 16.1% |
| LOAD_FAST | 420 | 11.3% |
| COMPARE_OP | 340 | 9.1% |
| LOAD_GLOBAL | 260 | 7.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_SUPER_ATTR_METHOD | 20 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 66,149,520 | 63.9% |
| TO_BOOL_BOOL | 30,749,320 | 29.7% |
| TO_BOOL_INT | 6,370,820 | 6.2% |
| COMPARE_OP | 122,260 | 0.1% |
| IS_OP | 54,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 84,169,380 | 81.3% |
| LOAD_FAST_LOAD_FAST | 9,415,040 | 9.1% |
| POP_TOP | 3,517,680 | 3.4% |
| LOAD_GLOBAL_MODULE | 2,528,400 | 2.4% |
| ENTER_EXECUTOR | 1,753,520 | 1.7% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,880 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 15,059,240 | 48.0% |
| TO_BOOL_BOOL | 7,246,260 | 23.1% |
| TO_BOOL_INT | 6,875,280 | 21.9% |
| TO_BOOL_ALWAYS_TRUE | 1,095,620 | 3.5% |
| COMPARE_OP_FLOAT | 1,060,820 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,986,120 | 41.4% |
| LOAD_FAST | 9,290,360 | 29.6% |
| POP_TOP | 5,722,360 | 18.2% |
| RETURN_CONST | 1,909,440 | 6.1% |
| RETURN_VALUE | 677,200 | 2.2% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,826,000 | 24.0% |
| STORE_ATTR_INSTANCE_VALUE | 5,517,820 | 22.7% |
| STORE_SUBSCR_LIST_INT | 5,330,140 | 22.0% |
| CALL_LIST_APPEND | 2,406,760 | 9.9% |
| ENTER_EXECUTOR | 2,241,860 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 19,650,560 | 81.0% |
| TO_BOOL_BOOL | 3,712,460 | 15.3% |
| TO_BOOL_INT | 845,100 | 3.5% |
| EXIT_INIT_CHECK | 61,380 | 0.3% |
| INTERPRETER_EXIT | 140 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,420 | 50.1% |
| ENTER_EXECUTOR | 11,640 | 28.5% |
| LOAD_FAST_LOAD_FAST | 6,240 | 15.3% |
| STORE_ATTR | 1,620 | 4.0% |
| SWAP | 440 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 23,980 | 58.8% |
| ENTER_EXECUTOR | 11,800 | 28.9% |
| STORE_ATTR | 1,620 | 4.0% |
| LOAD_FAST | 880 | 2.2% |
| STORE_ATTR_INSTANCE_VALUE | 860 | 2.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 41,377,500 | 32.2% |
| RETURN_VALUE | 39,727,860 | 30.9% |
| BINARY_SUBSCR_LIST_INT | 8,817,180 | 6.9% |
| BINARY_OP_ADD_INT | 7,772,400 | 6.0% |
| FOR_ITER_LIST | 7,599,260 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 106,316,920 | 82.7% |
| LOAD_FAST_LOAD_FAST | 8,511,520 | 6.6% |
| COPY | 7,550,160 | 5.9% |
| LOAD_GLOBAL_MODULE | 2,227,160 | 1.7% |
| JUMP_FORWARD | 2,019,600 | 1.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 16,380 | 50.6% |
| COPY | 16,000 | 49.4% |
| FOR_ITER | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 16,360 | 50.5% |
| LOAD_ATTR_INSTANCE_VALUE | 15,960 | 49.3% |
| LOAD_ATTR | 80 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,516,720 | 98.4% |
| BINARY_OP_ADD_INT | 14,120 | 0.6% |
| UNPACK_SEQUENCE_TWO_TUPLE | 14,120 | 0.6% |
| BINARY_OP | 12,980 | 0.5% |
| LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,516,720 | 98.4% |
| LOAD_CONST | 14,140 | 0.6% |
| LOAD_FAST_LOAD_FAST | 14,140 | 0.6% |
| BUILD_LIST | 12,960 | 0.5% |
| JUMP_BACKWARD | 240 | 0.0% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 6,936,180 | 100.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,224,160 | 75.3% |
| LOAD_GLOBAL_MODULE | 1,712,040 | 24.7% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 12,222,080 | 44.4% |
| BINARY_OP_SUBTRACT_INT | 11,517,300 | 41.9% |
| BINARY_OP_ADD_INT | 3,618,100 | 13.1% |
| BUILD_LIST | 45,280 | 0.2% |
| LOAD_FAST_AND_CLEAR | 45,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_WITH_HINT | 15,093,800 | 54.8% |
| STORE_ATTR_INSTANCE_VALUE | 12,263,240 | 44.6% |
| BUILD_LIST | 45,280 | 0.2% |
| STORE_FAST | 45,280 | 0.2% |
| FOR_ITER_RANGE | 29,140 | 0.1% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 20 | 50.0% |
| FOR_ITER_TUPLE | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 600 | 81.1% |
| CACHE | 100 | 13.5% |
| CALL_KW | 20 | 2.7% |
| COPY_FREE_VARS | 20 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 420 | 56.8% |
| LOAD_GLOBAL | 180 | 24.3% |
| LOAD_FAST_LOAD_FAST | 80 | 10.8% |
| LOAD_CONST | 60 | 8.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 1,117,160 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,117,180 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 14,718,920 | 75.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,352,280 | 17.2% |
| LOAD_ATTR_WITH_HINT | 1,364,760 | 7.0% |
| LOAD_FAST_LOAD_FAST | 28,200 | 0.1% |
| LOAD_FAST | 12,500 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,772,400 | 39.9% |
| STORE_GLOBAL | 6,936,180 | 35.6% |
| SWAP | 3,618,100 | 18.6% |
| CALL_BUILTIN_CLASS | 1,117,160 | 5.7% |
| LOAD_FAST_LOAD_FAST | 14,120 | 0.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,117,160 | 94.8% |
| LOAD_GLOBAL_MODULE | 60,900 | 5.2% |
| BINARY_OP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,117,180 | 94.8% |
| CALL_BUILTIN_CLASS | 48,400 | 4.1% |
| LOAD_FAST | 12,520 | 1.1% |
| CALL | 80 | 0.0% |


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
| LOAD_CONST | 15,054,240 | 74.9% |
| LOAD_FAST_LOAD_FAST | 5,033,360 | 25.1% |
| BINARY_OP | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 11,517,300 | 57.3% |
| STORE_FAST | 6,842,420 | 34.1% |
| BINARY_SUBSCR_LIST_INT | 1,728,000 | 8.6% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,794,560 | 71.1% |
| LOAD_ATTR_WITH_HINT | 5,456,440 | 21.8% |
| BINARY_OP_SUBTRACT_INT | 1,728,000 | 6.9% |
| ENTER_EXECUTOR | 33,540 | 0.1% |
| LOAD_GLOBAL_MODULE | 16,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 10,929,380 | 43.6% |
| STORE_FAST | 8,817,180 | 35.2% |
| CALL_PY_EXACT_ARGS | 3,521,040 | 14.1% |
| LOAD_FAST | 1,728,040 | 6.9% |
| CALL_LIST_APPEND | 46,040 | 0.2% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,240 | 52.5% |
| LOAD_GLOBAL_MODULE | 16,080 | 26.2% |
| ENTER_EXECUTOR | 12,480 | 20.3% |
| LOAD_FAST_LOAD_FAST | 440 | 0.7% |
| CALL | 140 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 61,380 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 3,495,640 | 73.8% |
| BINARY_OP_ADD_INT | 1,117,160 | 23.6% |
| BINARY_OP_MULTIPLY_INT | 48,400 | 1.0% |
| CALL_BUILTIN_CLASS | 32,240 | 0.7% |
| LOAD_GLOBAL_BUILTIN | 16,120 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,495,660 | 73.8% |
| BINARY_OP | 1,117,180 | 23.6% |
| LOAD_FAST | 48,420 | 1.0% |
| GET_ITER | 45,180 | 1.0% |
| CALL_BUILTIN_CLASS | 32,240 | 0.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,117,160 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,117,180 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,117,160 | 90.6% |
| LOAD_FAST | 116,360 | 9.4% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 1,117,160 | 90.6% |
| STORE_FAST | 116,420 | 9.4% |
| BINARY_OP | 20 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 120 | 75.0% |
| CALL | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 120 | 75.0% |
| TO_BOOL | 40 | 25.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,388,200 | 84.4% |
| LOAD_ATTR_WITH_HINT | 442,040 | 15.6% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,728,040 | 61.1% |
| LOAD_FAST | 637,100 | 22.5% |
| COMPARE_OP_INT | 442,040 | 15.6% |
| STORE_FAST | 16,380 | 0.6% |
| CALL | 6,780 | 0.2% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,432,160 | 98.1% |
| BINARY_SUBSCR_LIST_INT | 46,040 | 1.9% |
| CALL | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,406,760 | 97.1% |
| ENTER_EXECUTOR | 45,740 | 1.8% |
| JUMP_FORWARD | 15,980 | 0.6% |
| LOAD_FAST | 9,500 | 0.4% |
| JUMP_BACKWARD | 320 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,728,000 | 100.0% |
| CALL | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,728,120 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 70,960 | 99.9% |
| CALL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 54,860 | 77.3% |
| POP_TOP | 16,140 | 22.7% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,728,160 | 100.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 1,728,200 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,764,880 | 59.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,432,160 | 9.8% |
| LOAD_ATTR_INSTANCE_VALUE | 4,244,680 | 7.6% |
| LOAD_FAST_LOAD_FAST | 4,205,500 | 7.6% |
| BINARY_SUBSCR_LIST_INT | 3,521,040 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 55,521,940 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 8,150,120 | 96.5% |
| LOAD_FAST | 293,480 | 3.5% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,443,640 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 75.0% |
| CALL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60 | 75.0% |
| LOAD_GLOBAL | 20 | 25.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,060,800 | 100.0% |
| COMPARE_OP | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,060,820 | 100.0% |
| COMPARE_OP | 460 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 41,904,280 | 51.6% |
| LOAD_GLOBAL_MODULE | 20,401,160 | 25.1% |
| LOAD_CONST | 9,870,700 | 12.1% |
| LOAD_ATTR_INSTANCE_VALUE | 4,730,160 | 5.8% |
| LOAD_FAST_LOAD_FAST | 3,421,780 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 66,149,520 | 81.4% |
| POP_JUMP_IF_TRUE | 15,059,240 | 18.5% |
| COMPARE_OP | 32,100 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 7,607,380 | 99.7% |
| SWAP | 16,060 | 0.2% |
| JUMP_BACKWARD | 9,600 | 0.1% |
| FOR_ITER | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,599,260 | 99.6% |
| RETURN_CONST | 16,700 | 0.2% |
| STORE_FAST_LOAD_FAST | 16,380 | 0.2% |
| LOAD_FAST | 980 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 29,140 | 62.3% |
| GET_ITER | 16,040 | 34.3% |
| JUMP_BACKWARD | 1,500 | 3.2% |
| FOR_ITER | 100 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 46,680 | 99.8% |
| SWAP | 100 | 0.2% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 12,940 | 89.0% |
| JUMP_BACKWARD | 1,580 | 10.9% |
| FOR_ITER | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 14,100 | 97.0% |
| RETURN_CONST | 420 | 2.9% |
| UNPACK_SEQUENCE | 20 | 0.1% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,423,240 | 54.8% |
| LOAD_FAST_LOAD_FAST | 22,232,760 | 23.2% |
| COPY | 10,970,760 | 11.5% |
| LOAD_ATTR_WITH_HINT | 5,288,800 | 5.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,805,140 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,467,740 | 42.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 15,571,680 | 16.3% |
| LOAD_ATTR_METHOD_NO_DICT | 5,891,500 | 6.2% |
| LOAD_ATTR_INSTANCE_VALUE | 4,805,140 | 5.0% |
| COMPARE_OP_INT | 4,730,160 | 4.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,891,500 | 98.7% |
| LOAD_FAST | 80,280 | 1.3% |
| LOAD_ATTR | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,172,960 | 69.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,728,000 | 28.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 70,960 | 1.2% |
| CALL | 80 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 15,571,680 | 60.4% |
| LOAD_FAST | 10,201,120 | 39.5% |
| STORE_FAST_LOAD_FAST | 16,360 | 0.1% |
| ENTER_EXECUTOR | 11,200 | 0.0% |
| LOAD_ATTR | 700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,473,880 | 48.3% |
| LOAD_FAST_LOAD_FAST | 7,862,780 | 30.5% |
| CALL_PY_EXACT_ARGS | 5,432,160 | 21.1% |
| LOAD_GLOBAL_MODULE | 31,920 | 0.1% |
| CALL | 280 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,271,020 | 100.0% |
| LOAD_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,271,120 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 188,545,320 | 91.8% |
| COPY | 15,093,800 | 7.4% |
| LOAD_ATTR_WITH_HINT | 1,661,400 | 0.8% |
| LOAD_ATTR | 860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,824,880 | 28.7% |
| COMPARE_OP_INT | 41,904,280 | 20.4% |
| STORE_FAST | 41,377,500 | 20.2% |
| LOAD_CONST | 23,585,020 | 11.5% |
| LOAD_GLOBAL_MODULE | 12,033,620 | 5.9% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,845,160 | 69.5% |
| RESUME_CHECK | 669,520 | 16.4% |
| LOAD_FAST | 442,160 | 10.8% |
| STORE_ATTR_INSTANCE_VALUE | 77,320 | 1.9% |
| LOAD_GLOBAL_BUILTIN | 32,600 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,947,700 | 96.5% |
| LOAD_GLOBAL_MODULE | 81,080 | 2.0% |
| LOAD_GLOBAL_BUILTIN | 32,600 | 0.8% |
| CALL_BUILTIN_CLASS | 16,120 | 0.4% |
| LOAD_CONST | 13,020 | 0.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 12,033,620 | 30.7% |
| LOAD_FAST | 8,911,800 | 22.7% |
| RESUME_CHECK | 5,279,000 | 13.5% |
| POP_JUMP_IF_FALSE | 2,528,400 | 6.5% |
| STORE_FAST | 2,227,160 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 20,401,160 | 52.1% |
| LOAD_FAST | 7,980,760 | 20.4% |
| LOAD_CONST | 6,936,180 | 17.7% |
| LOAD_ATTR_MODULE | 2,271,020 | 5.8% |
| CALL_PY_EXACT_ARGS | 1,259,560 | 3.2% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 75.0% |
| LOAD_SUPER_ATTR | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 55,521,940 | 82.0% |
| CALL_PY_WITH_DEFAULTS | 8,443,640 | 12.5% |
| CALL_KW | 3,629,340 | 5.4% |
| CALL_ALLOC_AND_ENTER_INIT | 61,380 | 0.1% |
| CALL | 55,160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,345,960 | 83.2% |
| LOAD_FAST_LOAD_FAST | 5,375,360 | 7.9% |
| LOAD_GLOBAL_MODULE | 5,279,000 | 7.8% |
| LOAD_GLOBAL_BUILTIN | 669,520 | 1.0% |
| LOAD_CONST | 41,620 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 12,263,240 | 65.2% |
| LOAD_ATTR_INSTANCE_VALUE | 2,542,160 | 13.5% |
| LOAD_FAST | 2,143,100 | 11.4% |
| LOAD_FAST_LOAD_FAST | 1,859,640 | 9.9% |
| STORE_ATTR | 860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,293,780 | 38.8% |
| RETURN_CONST | 5,517,820 | 29.3% |
| LOAD_FAST_LOAD_FAST | 3,442,860 | 18.3% |
| ENTER_EXECUTOR | 1,333,800 | 7.1% |
| JUMP_FORWARD | 910,440 | 4.8% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 15,093,800 | 34.9% |
| LOAD_FAST | 14,980,160 | 34.6% |
| LOAD_FAST_LOAD_FAST | 9,997,720 | 23.1% |
| ENTER_EXECUTOR | 3,200,480 | 7.4% |
| STORE_ATTR | 700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,412,220 | 65.7% |
| ENTER_EXECUTOR | 7,073,160 | 16.3% |
| LOAD_CONST | 4,709,340 | 10.9% |
| LOAD_FAST_LOAD_FAST | 3,076,840 | 7.1% |
| JUMP_BACKWARD | 960 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,329,240 | 100.0% |
| STORE_SUBSCR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 5,330,140 | 47.0% |
| RETURN_CONST | 5,330,140 | 47.0% |
| LOAD_FAST | 669,060 | 5.9% |


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,035,800 | 93.7% |
| LOAD_ATTR_INSTANCE_VALUE | 35,040 | 3.2% |
| LOAD_FAST | 34,180 | 3.1% |
| TO_BOOL_NONE | 580 | 0.1% |
| TO_BOOL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,095,620 | 99.1% |
| POP_JUMP_IF_FALSE | 9,500 | 0.9% |
| TO_BOOL_NONE | 540 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,668,640 | 70.7% |
| RETURN_CONST | 3,712,460 | 9.2% |
| LOAD_ATTR_WITH_HINT | 3,512,040 | 8.7% |
| COPY | 2,516,680 | 6.2% |
| ENTER_EXECUTOR | 1,235,440 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,749,320 | 75.9% |
| POP_JUMP_IF_TRUE | 7,246,260 | 17.9% |
| UNARY_NOT | 2,516,700 | 6.2% |
| TO_BOOL_INT | 16,000 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 7,792,000 | 58.8% |
| LOAD_FAST | 2,942,520 | 22.2% |
| RETURN_VALUE | 1,666,320 | 12.6% |
| RETURN_CONST | 845,100 | 6.4% |
| TO_BOOL_BOOL | 16,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,875,280 | 51.8% |
| POP_JUMP_IF_FALSE | 6,370,820 | 48.0% |
| TO_BOOL_BOOL | 15,980 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,280 | 99.9% |
| TO_BOOL | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,300 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,340 | 36.3% |
| LOAD_ATTR_INSTANCE_VALUE | 15,920 | 31.5% |
| ENTER_EXECUTOR | 15,720 | 31.1% |
| TO_BOOL_ALWAYS_TRUE | 540 | 1.1% |
| TO_BOOL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 49,980 | 98.9% |
| TO_BOOL_ALWAYS_TRUE | 580 | 1.1% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 14,100 | 99.9% |
| UNPACK_SEQUENCE | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 14,120 | 100.0% |


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
|     deferred | 18,651,140 | 30.8% |
|          hit | 41,758,760 | 69.0% |
|         miss | 111,980 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,880 | 18.7% |
| Failure | 12,520 | 81.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 6,700 | 53.5% |
| xor | 3,540 | 28.3% |
| multiply different types | 1,040 | 8.3% |
| true divide different types | 920 | 7.3% |
| floor divide | 160 | 1.3% |
| remainder | 160 | 1.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 860 | 0.0% |
|          hit | 24,985,420 | 99.8% |
|         miss | 57,400 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,340 | 51.1% |
| Failure | 1,280 | 48.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 1,280 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,552,580 | 4.3% |
|          hit | 79,952,600 | 95.7% |
|         miss | 80 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,780 | 54.9% |
| Failure | 1,460 | 45.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 1,100 | 75.3% |
| bound method | 360 | 24.7% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 138,700 | 0.2% |
|          hit | 82,270,400 | 99.8% |
|         miss | 31,740 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,340 | 38.3% |
| Failure | 2,160 | 61.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 1,240 | 57.4% |
| float long | 560 | 25.9% |
| bool | 200 | 9.3% |
| long float | 160 | 7.4% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 400 | 0.0% |
|          hit | 7,694,640 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 400 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40,112,060 | 10.7% |
|          hit | 335,076,900 | 89.3% |
|         miss | 7,420 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,940 | 25.5% |
| Failure | 11,520 | 74.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 11,320 | 98.3% |
| method | 200 | 1.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,740 | 0.0% |
|          hit | 43,280,440 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,980 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 80 | 80.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
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
|     deferred | 37,260 | 0.1% |
|          hit | 62,062,880 | 99.9% |
|         miss | 18,980 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,560 | 44.3% |
| Failure | 1,960 | 55.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 1,480 | 75.5% |
| not in keys | 480 | 24.5% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 0.0% |
|          hit | 11,329,340 | 100.0% |

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
|     deferred | 368,934,881,474,190,999,680 | 671,231,998,117,655.1% |
|          hit | 53,208,140 | 96.8% |
|         miss | 1,754,740 | 3.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 33,600 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.1% |
|          hit | 14,120 | 99.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 972,074,080 | 49.1% |
| Not specialized | 197,458,200 | 10.0% |
| Specialized hits | 809,345,280 | 40.9% |
| Specialized misses | 1,982,420 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL | 368,934,881,474,190,999,680 | 100.0% |
| LOAD_ATTR | 40,112,060 | 0.0% |
| BINARY_OP | 18,651,140 | 0.0% |
| CALL | 3,552,580 | 0.0% |
| COMPARE_OP | 138,700 | 0.0% |
| STORE_ATTR | 37,260 | 0.0% |
| LOAD_GLOBAL | 1,740 | 0.0% |
| BINARY_SUBSCR | 860 | 0.0% |
| FOR_ITER | 400 | 0.0% |
| STORE_SUBSCR | 100 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_BOOL | 848,000 | 42.8% |
| TO_BOOL_INT | 846,940 | 42.7% |
| BINARY_OP_ADD_INT | 111,980 | 5.6% |
| BINARY_SUBSCR_LIST_INT | 57,400 | 2.9% |
| TO_BOOL_NONE | 30,740 | 1.6% |
| TO_BOOL_ALWAYS_TRUE | 29,060 | 1.5% |
| COMPARE_OP_FLOAT | 25,380 | 1.3% |
| STORE_ATTR_WITH_HINT | 18,980 | 1.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,420 | 0.4% |
| COMPARE_OP_INT | 6,360 | 0.3% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 140 | 0.0% |
| Calls to Python functions inlined | 67,712,240 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 140 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 70,124,760 | 103.6% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 13,325,560 | 30.8% |
| Frees to freelist | 13,324,500 |  |
| Allocations | 29,928,980 | 69.2% |
| Allocations to 512 bytes | 29,848,000 | 69.0% |
| Allocations to 4 kbytes | 64,980 | 0.2% |
| Allocations over 4 kbytes | 16,000 | 0.0% |
| Frees | 29,759,481 |  |
| New values | 140 |  |
| Interpreter increfs | 906,616,760 | 88.0% |
| Interpreter decrefs | 996,067,520 | 92.8% |
| Increfs | 123,715,587 | 12.0% |
| Decrefs | 77,027,317 | 7.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 12,960 | 9,257.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 40,193,128 |  |
| Method cache misses | 1,412 |  |
| Method cache collisions | 1,057 |  |
| Method cache dunder hits | 477 |  |
| Method cache dunder misses | 123 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 140 | 1,920 | 4,809,720 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 860 |  |
| Traces created | 860 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 20 | 2.3% |
| Trace too long | 120 | 14.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 31,777,860 |  |
| Uops executed | 873,183,520 | 27.48 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 2.3% |
| <= 32 | 200 | 23.3% |
| <= 64 | 500 | 58.1% |
| <= 128 | 140 | 16.3% |


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
| <= 16 | 100 | 11.6% |
| <= 32 | 320 | 37.2% |
| <= 64 | 300 | 34.9% |
| <= 128 | 140 | 16.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 6,178,460 | 19.4% |
| <= 16 | 4,081,780 | 12.8% |
| <= 32 | 17,494,500 | 55.1% |
| <= 64 | 528,700 | 1.7% |
| <= 128 | 3,373,240 | 10.6% |
| <= 256 | 76,140 | 0.2% |
| <= 512 | 22,960 | 0.1% |
| <= 1,024 | 22,000 | 0.1% |
| <= 2,048 | 20 | 0.0% |
| <= 4,096 | 60 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 208,195,100 | 23.8% | 23.8% |  |
| LOAD_FAST | 78,719,240 | 9.0% | 32.9% |  |
| _POP_JUMP_IF_TRUE | 48,999,320 | 5.6% | 38.5% |  |
| STORE_FAST | 46,224,060 | 5.3% | 43.8% |  |
| _GUARD_TYPE_VERSION | 44,051,760 | 5.0% | 48.8% |  |
| _GUARD_GLOBALS_VERSION | 32,924,860 | 3.8% | 52.6% |  |
| _ITER_CHECK_LIST | 32,748,000 | 3.8% | 56.3% |  |
| _IS_ITER_EXHAUSTED_LIST | 32,748,000 | 3.8% | 60.1% |  |
| _EXIT_TRACE | 30,263,620 | 3.5% | 63.5% |  |
| _CHECK_ATTR_WITH_HINT | 28,376,160 | 3.2% | 66.8% |  |
| _LOAD_ATTR_WITH_HINT | 28,376,160 | 3.2% | 70.0% |  |
| _LOAD_GLOBAL_MODULE | 27,708,860 | 3.2% | 73.2% |  |
| _ITER_NEXT_LIST | 26,121,700 | 3.0% | 76.2% |  |
| COMPARE_OP_INT | 23,940,840 | 2.7% | 79.0% |  |
| _POP_JUMP_IF_FALSE | 17,814,960 | 2.0% | 81.0% |  |
| LOAD_CONST | 8,425,300 | 1.0% | 82.0% |  |
| POP_TOP | 8,282,540 | 0.9% | 82.9% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 7,900,140 | 0.9% | 83.8% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 7,900,140 | 0.9% | 84.7% |  |
| _GUARD_KEYS_VERSION | 7,741,920 | 0.9% | 85.6% | 0.1% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 7,741,920 | 0.9% | 86.5% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 7,730,720 | 0.9% | 87.4% |  |
| RESUME_CHECK | 6,036,420 | 0.7% | 88.1% |  |
| _CHECK_PEP_523 | 6,036,420 | 0.7% | 88.8% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 6,036,420 | 0.7% | 89.4% |  |
| _CHECK_STACK_SPACE | 6,036,420 | 0.7% | 90.1% |  |
| _INIT_CALL_PY_EXACT_ARGS | 6,036,420 | 0.7% | 90.8% |  |
| _PUSH_FRAME | 6,036,420 | 0.7% | 91.5% |  |
| _SAVE_RETURN_OFFSET | 6,036,420 | 0.7% | 92.2% |  |
| _GUARD_BUILTINS_VERSION | 5,216,000 | 0.6% | 92.8% |  |
| _LOAD_GLOBAL_BUILTINS | 5,216,000 | 0.6% | 93.4% |  |
| _GUARD_BOTH_INT | 4,717,000 | 0.5% | 93.9% | 9.6% |
| _JUMP_TO_TOP | 4,621,340 | 0.5% | 94.5% |  |
| TO_BOOL_BOOL | 4,239,840 | 0.5% | 95.0% |  |
| _BINARY_OP_ADD_INT | 4,231,940 | 0.5% | 95.4% |  |
| PUSH_NULL | 3,517,780 | 0.4% | 95.9% |  |
| _CHECK_ATTR_MODULE | 3,513,860 | 0.4% | 96.3% |  |
| _LOAD_ATTR_MODULE | 3,513,860 | 0.4% | 96.7% |  |
| COPY | 3,270,480 | 0.4% | 97.0% |  |
| _ITER_CHECK_RANGE | 3,112,880 | 0.4% | 97.4% |  |
| _IS_ITER_EXHAUSTED_RANGE | 3,112,880 | 0.4% | 97.7% |  |
| _ITER_NEXT_RANGE | 3,083,700 | 0.4% | 98.1% |  |
| BINARY_SUBSCR_LIST_INT | 2,553,040 | 0.3% | 98.4% |  |
| _POP_FRAME | 2,504,420 | 0.3% | 98.7% |  |
| TO_BOOL_NONE | 2,040,640 | 0.2% | 98.9% | 51.5% |
| SWAP | 1,978,000 | 0.2% | 99.1% |  |
| CALL_LEN | 1,737,040 | 0.2% | 99.3% |  |
| TO_BOOL_INT | 1,727,840 | 0.2% | 99.5% |  |
| LIST_APPEND | 1,286,080 | 0.1% | 99.7% |  |
| GET_ITER | 1,276,160 | 0.1% | 99.8% |  |
| STORE_GLOBAL | 1,260,560 | 0.1% | 100.0% |  |
| _ITER_CHECK_TUPLE | 50,240 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 50,240 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 37,700 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 37,700 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 33,540 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 33,540 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 9,200 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 5,840 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 3,920 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| LOAD_ATTR | 200 |
| CALL | 80 |
| STORE_ATTR_WITH_HINT | 80 |
| BINARY_OP | 60 |
| COMPARE_OP | 40 |
| STORE_ATTR | 20 |
| CALL_ALLOC_AND_ENTER_INIT | 20 |


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
