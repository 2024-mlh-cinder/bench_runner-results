
# Pystats results

- benchmark: go
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 482,875,460 | 25.1% | 25.1% |  |
| LOAD_ATTR_WITH_HINT | 198,110,260 | 10.3% | 35.4% |  |
| STORE_FAST | 126,001,800 | 6.5% | 41.9% |  |
| POP_JUMP_IF_FALSE | 100,965,180 | 5.2% | 47.1% |  |
| LOAD_ATTR_INSTANCE_VALUE | 95,724,700 | 5.0% | 52.1% |  |
| COMPARE_OP_INT | 78,740,020 | 4.1% | 56.2% | 0.0% |
| RESUME_CHECK | 65,513,560 | 3.4% | 59.6% | 0.0% |
| LOAD_CONST | 54,610,860 | 2.8% | 62.4% |  |
| CALL_PY_EXACT_ARGS | 52,176,060 | 2.7% | 65.1% |  |
| LOAD_FAST_LOAD_FAST | 46,871,640 | 2.4% | 67.6% |  |
| RETURN_VALUE | 46,737,480 | 2.4% | 70.0% |  |
| COPY | 46,474,860 | 2.4% | 72.4% |  |
| STORE_ATTR_WITH_HINT | 40,710,980 | 2.1% | 74.5% | 0.0% |
| TO_BOOL_BOOL | 40,265,100 | 2.1% | 76.6% | 2.1% |
| LOAD_GLOBAL_MODULE | 39,186,020 | 2.0% | 78.7% |  |
| POP_TOP | 32,380,660 | 1.7% | 80.3% |  |
| POP_JUMP_IF_TRUE | 31,117,480 | 1.6% | 81.9% |  |
| LOAD_ATTR | 30,860,160 | 1.6% | 83.6% |  |
| ENTER_EXECUTOR | 29,195,000 | 1.5% | 85.1% |  |
| SWAP | 26,218,940 | 1.4% | 86.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 25,801,040 | 1.3% | 87.8% | 0.0% |
| BINARY_SUBSCR_LIST_INT | 25,042,780 | 1.3% | 89.1% | 0.2% |
| RETURN_CONST | 24,269,720 | 1.3% | 90.3% |  |
| BINARY_OP_SUBTRACT_INT | 20,087,760 | 1.0% | 91.4% |  |
| BINARY_OP_ADD_INT | 19,478,540 | 1.0% | 92.4% | 0.6% |
| STORE_ATTR_INSTANCE_VALUE | 17,509,120 | 0.9% | 93.3% |  |
| BINARY_OP | 17,371,100 | 0.9% | 94.2% |  |
| TO_BOOL_INT | 13,262,060 | 0.7% | 94.9% | 6.4% |
| STORE_SUBSCR_LIST_INT | 11,329,340 | 0.6% | 95.5% |  |
| CALL_PY_WITH_DEFAULTS | 8,443,640 | 0.4% | 95.9% |  |
| GET_ITER | 7,680,660 | 0.4% | 96.3% |  |
| FOR_ITER_LIST | 7,632,680 | 0.4% | 96.7% |  |
| STORE_GLOBAL | 6,936,220 | 0.4% | 97.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,971,940 | 0.3% | 97.4% |  |
| CALL_BUILTIN_CLASS | 4,738,720 | 0.2% | 97.6% |  |
| JUMP_FORWARD | 4,676,020 | 0.2% | 97.9% |  |
| LOAD_GLOBAL_BUILTIN | 4,091,000 | 0.2% | 98.1% |  |
| CALL_KW | 3,629,360 | 0.2% | 98.3% |  |
| CALL | 3,555,820 | 0.2% | 98.4% |  |
| CALL_LEN | 2,830,320 | 0.1% | 98.6% |  |
| STORE_FAST_STORE_FAST | 2,554,140 | 0.1% | 98.7% |  |
| UNARY_NOT | 2,516,720 | 0.1% | 98.9% |  |
| CONTAINS_OP | 2,516,720 | 0.1% | 99.0% |  |
| CALL_LIST_APPEND | 2,478,300 | 0.1% | 99.1% |  |
| PUSH_NULL | 2,333,080 | 0.1% | 99.2% |  |
| LOAD_ATTR_MODULE | 2,271,100 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_O | 1,728,200 | 0.1% | 99.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,728,120 | 0.1% | 99.5% | 0.0% |
| LIST_APPEND | 1,345,180 | 0.1% | 99.6% |  |
| CALL_BUILTIN_O | 1,233,580 | 0.1% | 99.7% |  |
| BINARY_OP_MULTIPLY_INT | 1,178,120 | 0.1% | 99.7% |  |
| BINARY_OP_ADD_FLOAT | 1,117,180 | 0.1% | 99.8% |  |
| CALL_BUILTIN_FAST | 1,117,180 | 0.1% | 99.8% |  |
| TO_BOOL_ALWAYS_TRUE | 1,100,180 | 0.1% | 99.9% | 2.6% |
| COMPARE_OP_FLOAT | 1,061,280 | 0.1% | 100.0% | 2.4% |
| COMPARE_OP | 132,660 | 0.0% | 100.0% |  |
| BUILD_LIST | 89,100 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 71,000 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 61,380 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 61,380 | 0.0% | 100.0% |  |
| IS_OP | 54,880 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 54,880 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 49,840 | 0.0% | 100.0% | 59.6% |
| FOR_ITER_RANGE | 46,680 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 45,280 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 32,380 | 0.0% | 100.0% |  |
| STORE_ATTR | 16,700 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 16,280 | 0.0% | 100.0% |  |
| NOP | 16,080 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 14,000 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 13,140 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,740 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_WITH_HINT | 181,354,220 | 9.4% | 9.4% |
| STORE_FAST LOAD_FAST | 103,819,840 | 5.4% | 14.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 81,663,280 | 4.2% | 19.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 63,650,320 | 3.3% | 22.3% |
| LOAD_ATTR_WITH_HINT LOAD_FAST | 56,328,500 | 2.9% | 25.3% |
| RESUME_CHECK LOAD_FAST | 54,147,920 | 2.8% | 28.1% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 52,415,540 | 2.7% | 30.8% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 52,176,060 | 2.7% | 33.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 40,467,680 | 2.1% | 35.6% |
| LOAD_FAST RETURN_VALUE | 39,432,920 | 2.0% | 37.7% |
| RETURN_VALUE STORE_FAST | 39,429,400 | 2.0% | 39.7% |
| LOAD_ATTR_WITH_HINT COMPARE_OP_INT | 39,407,940 | 2.0% | 41.8% |
| LOAD_ATTR_WITH_HINT STORE_FAST | 39,179,420 | 2.0% | 43.8% |
| LOAD_FAST COPY | 33,851,040 | 1.8% | 45.5% |
| LOAD_FAST LOAD_ATTR | 30,848,560 | 1.6% | 47.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 30,749,280 | 1.6% | 48.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 29,419,140 | 1.5% | 50.3% |
| STORE_ATTR_WITH_HINT LOAD_FAST | 28,412,220 | 1.5% | 51.7% |
| LOAD_FAST TO_BOOL_BOOL | 28,405,520 | 1.5% | 53.2% |
| LOAD_ATTR LOAD_FAST | 24,519,480 | 1.3% | 54.5% |
| LOAD_ATTR_WITH_HINT LOAD_CONST | 23,585,000 | 1.2% | 55.7% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 22,232,760 | 1.2% | 56.9% |
| LOAD_GLOBAL_MODULE COMPARE_OP_INT | 20,399,440 | 1.1% | 57.9% |
| RETURN_CONST POP_TOP | 19,650,560 | 1.0% | 59.0% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 17,794,540 | 0.9% | 59.9% |
| POP_TOP LOAD_FAST | 16,382,180 | 0.9% | 60.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 15,571,660 | 0.8% | 61.5% |
| COPY LOAD_ATTR_WITH_HINT | 15,093,780 | 0.8% | 62.3% |
| SWAP STORE_ATTR_WITH_HINT | 15,093,780 | 0.8% | 63.1% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 15,057,600 | 0.8% | 63.9% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 15,054,240 | 0.8% | 64.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 14,712,740 | 0.8% | 65.4% |
| LOAD_FAST STORE_ATTR_WITH_HINT | 13,699,220 | 0.7% | 66.1% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 12,986,200 | 0.7% | 66.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 12,473,800 | 0.6% | 67.5% |
| LOAD_ATTR_WITH_HINT LOAD_GLOBAL_MODULE | 12,033,360 | 0.6% | 68.1% |
| BINARY_OP_SUBTRACT_INT SWAP | 11,517,300 | 0.6% | 68.7% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 11,329,240 | 0.6% | 69.3% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 10,964,660 | 0.6% | 69.8% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 10,964,660 | 0.6% | 70.4% |
| BINARY_OP SWAP | 10,929,580 | 0.6% | 71.0% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 10,929,360 | 0.6% | 71.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 10,201,000 | 0.5% | 72.1% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_WITH_HINT | 9,997,720 | 0.5% | 72.6% |
| LOAD_CONST COMPARE_OP_INT | 9,870,700 | 0.5% | 73.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 9,415,040 | 0.5% | 73.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 9,020,920 | 0.5% | 74.1% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 8,911,560 | 0.5% | 74.5% |
| ENTER_EXECUTOR LOAD_FAST | 8,910,280 | 0.5% | 75.0% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 8,817,160 | 0.5% | 75.4% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 8,511,420 | 0.4% | 75.9% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 8,443,640 | 0.4% | 76.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 7,980,720 | 0.4% | 76.7% |
| LOAD_FAST LOAD_CONST | 7,871,460 | 0.4% | 77.2% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 7,862,780 | 0.4% | 77.6% |
| COPY TO_BOOL_INT | 7,792,000 | 0.4% | 78.0% |
| BINARY_OP_ADD_INT STORE_FAST | 7,772,340 | 0.4% | 78.4% |
| GET_ITER FOR_ITER_LIST | 7,607,340 | 0.4% | 78.8% |
| FOR_ITER_LIST STORE_FAST | 7,598,700 | 0.4% | 79.2% |
| COPY STORE_FAST | 7,550,160 | 0.4% | 79.6% |
| STORE_FAST COPY | 7,550,160 | 0.4% | 79.9% |
| LOAD_ATTR_WITH_HINT GET_ITER | 7,501,080 | 0.4% | 80.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 7,293,780 | 0.4% | 80.7% |
| TO_BOOL_BOOL POP_JUMP_IF_TRUE | 6,983,120 | 0.4% | 81.1% |
| BINARY_OP_ADD_INT STORE_GLOBAL | 6,936,160 | 0.4% | 81.4% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 6,936,160 | 0.4% | 81.8% |
| TO_BOOL_INT POP_JUMP_IF_TRUE | 6,875,280 | 0.4% | 82.2% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 6,842,420 | 0.4% | 82.5% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 6,370,800 | 0.3% | 82.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 5,891,440 | 0.3% | 83.1% |
| POP_TOP RETURN_CONST | 5,825,960 | 0.3% | 83.4% |
| STORE_ATTR_WITH_HINT ENTER_EXECUTOR | 5,792,340 | 0.3% | 83.7% |
| ENTER_EXECUTOR CALL_PY_WITH_DEFAULTS | 5,736,560 | 0.3% | 84.0% |
| POP_JUMP_IF_TRUE POP_TOP | 5,722,320 | 0.3% | 84.3% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 5,517,820 | 0.3% | 84.6% |
| LOAD_ATTR_WITH_HINT BINARY_SUBSCR_LIST_INT | 5,456,440 | 0.3% | 84.9% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 5,432,080 | 0.3% | 85.2% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 5,375,360 | 0.3% | 85.5% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 5,330,140 | 0.3% | 85.7% |
| STORE_SUBSCR_LIST_INT RETURN_CONST | 5,330,140 | 0.3% | 86.0% |
| LOAD_ATTR_WITH_HINT LOAD_ATTR_INSTANCE_VALUE | 5,288,800 | 0.3% | 86.3% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 5,278,980 | 0.3% | 86.6% |
| STORE_GLOBAL LOAD_FAST | 5,224,140 | 0.3% | 86.8% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_INT | 5,033,360 | 0.3% | 87.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_INSTANCE_VALUE | 4,805,080 | 0.2% | 87.4% |
| LOAD_CONST LOAD_FAST | 4,759,320 | 0.2% | 87.6% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 4,730,160 | 0.2% | 87.8% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 4,244,680 | 0.2% | 88.1% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 4,205,440 | 0.2% | 88.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 4,172,900 | 0.2% | 88.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,947,660 | 0.2% | 88.7% |
| RETURN_CONST TO_BOOL_BOOL | 3,712,420 | 0.2% | 88.9% |
| CALL_KW RESUME_CHECK | 3,629,340 | 0.2% | 89.1% |
| BINARY_OP_ADD_INT SWAP | 3,612,000 | 0.2% | 89.3% |
| BINARY_SUBSCR_LIST_INT CALL_PY_EXACT_ARGS | 3,521,040 | 0.2% | 89.5% |
| POP_JUMP_IF_FALSE POP_TOP | 3,517,520 | 0.2% | 89.6% |
| ENTER_EXECUTOR CALL | 3,513,940 | 0.2% | 89.8% |
| LOAD_ATTR_WITH_HINT TO_BOOL_BOOL | 3,512,020 | 0.2% | 90.0% |
| CALL LOAD_FAST | 3,495,880 | 0.2% | 90.2% |
| LOAD_FAST BINARY_OP | 3,495,800 | 0.2% | 90.4% |


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
| LOAD_ATTR_WITH_HINT | 7,501,080 | 97.7% |
| LOAD_ATTR_INSTANCE_VALUE | 90,400 | 1.2% |
| CALL_BUILTIN_CLASS | 45,180 | 0.6% |
| LOAD_FAST | 32,000 | 0.4% |
| LOAD_CONST | 11,660 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 7,607,340 | 99.0% |
| LOAD_FAST_AND_CLEAR | 45,280 | 0.6% |
| FOR_ITER_RANGE | 16,040 | 0.2% |
| FOR_ITER_TUPLE | 11,640 | 0.2% |
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
| POP_JUMP_IF_TRUE | 5,722,320 | 17.7% |
| POP_JUMP_IF_FALSE | 3,517,520 | 10.9% |
| CALL_METHOD_DESCRIPTOR_O | 1,728,200 | 5.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,728,120 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,382,180 | 50.6% |
| RETURN_CONST | 5,825,960 | 18.0% |
| ENTER_EXECUTOR | 3,001,120 | 9.3% |
| LOAD_CONST | 2,516,800 | 7.8% |
| JUMP_FORWARD | 1,712,100 | 5.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,271,040 | 97.3% |
| LOAD_FAST | 61,820 | 2.6% |
| LOAD_ATTR | 140 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,178,860 | 50.5% |
| LOAD_GLOBAL_MODULE | 1,117,160 | 47.9% |
| CALL | 16,960 | 0.7% |
| LOAD_CONST | 13,240 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 6,740 | 0.3% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,432,920 | 84.4% |
| CONTAINS_OP | 2,516,720 | 5.4% |
| RETURN_VALUE | 1,799,200 | 3.8% |
| BINARY_OP_ADD_FLOAT | 1,117,180 | 2.4% |
| POP_JUMP_IF_FALSE | 1,034,640 | 2.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 39,429,400 | 84.4% |
| RETURN_VALUE | 1,799,200 | 3.8% |
| CALL_PY_EXACT_ARGS | 1,744,120 | 3.7% |
| TO_BOOL_INT | 1,666,320 | 3.6% |
| LOAD_FAST | 1,151,480 | 2.5% |


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
| BINARY_SUBSCR_LIST_INT | 10,929,360 | 62.9% |
| LOAD_FAST | 3,495,800 | 20.1% |
| BINARY_OP_MULTIPLY_INT | 1,117,180 | 6.4% |
| CALL_BUILTIN_CLASS | 1,117,180 | 6.4% |
| ENTER_EXECUTOR | 443,180 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 10,929,580 | 62.9% |
| CALL_BUILTIN_CLASS | 3,495,640 | 20.1% |
| STORE_FAST | 1,792,000 | 10.3% |
| CALL_BUILTIN_O | 1,117,160 | 6.4% |
| LOAD_FAST | 11,720 | 0.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 45,280 | 50.8% |
| STORE_ATTR_INSTANCE_VALUE | 16,140 | 18.1% |
| LOAD_FAST | 16,000 | 18.0% |
| STORE_FAST_STORE_FAST | 11,660 | 13.1% |
| STORE_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 45,280 | 50.8% |
| LOAD_FAST | 27,820 | 31.2% |
| STORE_FAST | 16,000 | 18.0% |


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
| ENTER_EXECUTOR | 3,513,940 | 98.8% |
| PUSH_NULL | 16,960 | 0.5% |
| LOAD_CONST | 13,300 | 0.4% |
| CALL_LEN | 6,760 | 0.2% |
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
| LOAD_CONST | 3,446,520 | 95.0% |
| ENTER_EXECUTOR | 182,840 | 5.0% |

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
| LOAD_CONST | 40,340 | 30.4% |
| LOAD_FAST_LOAD_FAST | 40,300 | 30.4% |
| COMPARE_OP_INT | 32,100 | 24.2% |
| RETURN_VALUE | 16,000 | 12.1% |
| COMPARE_OP | 1,580 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 112,740 | 85.0% |
| STORE_FAST | 16,000 | 12.1% |
| COMPARE_OP | 1,580 | 1.2% |
| POP_JUMP_IF_TRUE | 1,000 | 0.8% |
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
| LOAD_FAST | 33,851,040 | 72.8% |
| STORE_FAST | 7,550,160 | 16.2% |
| UNARY_NOT | 2,516,720 | 5.4% |
| LOAD_CONST | 2,516,720 | 5.4% |
| SWAP | 24,220 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 15,093,780 | 32.5% |
| LOAD_ATTR_INSTANCE_VALUE | 10,964,660 | 23.6% |
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
| POP_JUMP_IF_TRUE | 12,986,200 | 44.5% |
| STORE_ATTR_WITH_HINT | 5,792,340 | 19.8% |
| POP_TOP | 3,001,120 | 10.3% |
| ENTER_EXECUTOR | 2,432,660 | 8.3% |
| STORE_FAST | 1,797,060 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,910,280 | 30.5% |
| CALL_PY_WITH_DEFAULTS | 5,736,560 | 19.6% |
| CALL | 3,513,940 | 12.0% |
| ENTER_EXECUTOR | 2,432,660 | 8.3% |
| RETURN_CONST | 2,241,920 | 7.7% |


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
| POP_JUMP_IF_TRUE | 3,940 | 28.1% |
| POP_TOP | 2,580 | 18.4% |
| STORE_FAST | 2,240 | 16.0% |
| LIST_APPEND | 1,280 | 9.1% |
| STORE_ATTR_WITH_HINT | 900 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 9,000 | 64.3% |
| FOR_ITER_TUPLE | 1,480 | 10.6% |
| FOR_ITER_RANGE | 1,400 | 10.0% |
| ENTER_EXECUTOR | 860 | 6.1% |
| LOAD_FAST | 600 | 4.3% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,019,600 | 43.2% |
| POP_TOP | 1,712,100 | 36.6% |
| STORE_ATTR_INSTANCE_VALUE | 904,360 | 19.3% |
| POP_JUMP_IF_TRUE | 23,940 | 0.5% |
| CALL_LIST_APPEND | 15,980 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,987,580 | 42.5% |
| LOAD_FAST | 1,772,560 | 37.9% |
| LOAD_FAST_LOAD_FAST | 904,400 | 19.3% |
| LOAD_CONST | 11,460 | 0.2% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,276,960 | 94.9% |
| RETURN_VALUE | 51,820 | 3.9% |
| LOAD_CONST | 16,380 | 1.2% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,343,900 | 99.9% |
| JUMP_BACKWARD | 1,280 | 0.1% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,848,560 | 100.0% |
| LOAD_ATTR | 9,840 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 500 | 0.0% |
| COPY | 440 | 0.0% |
| LOAD_FAST_LOAD_FAST | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,519,480 | 79.5% |
| LOAD_CONST | 3,184,540 | 10.3% |
| CALL_PY_WITH_DEFAULTS | 2,413,560 | 7.8% |
| LOAD_FAST_LOAD_FAST | 672,100 | 2.2% |
| STORE_FAST | 55,040 | 0.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 23,585,000 | 43.2% |
| LOAD_FAST | 7,871,460 | 14.4% |
| LOAD_GLOBAL_MODULE | 6,936,160 | 12.7% |
| LOAD_CONST | 3,446,520 | 6.3% |
| STORE_ATTR_WITH_HINT | 3,428,460 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 15,054,240 | 27.6% |
| BINARY_OP_ADD_INT | 14,712,740 | 26.9% |
| COMPARE_OP_INT | 9,870,700 | 18.1% |
| LOAD_FAST | 4,759,320 | 8.7% |
| CALL_KW | 3,446,520 | 6.3% |


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
| STORE_FAST | 103,819,840 | 21.5% |
| POP_JUMP_IF_FALSE | 81,663,280 | 16.9% |
| LOAD_ATTR_WITH_HINT | 56,328,500 | 11.7% |
| RESUME_CHECK | 54,147,920 | 11.2% |
| LOAD_ATTR_INSTANCE_VALUE | 40,467,680 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 181,354,220 | 37.6% |
| LOAD_ATTR_INSTANCE_VALUE | 52,415,540 | 10.9% |
| RETURN_VALUE | 39,432,920 | 8.2% |
| COPY | 33,851,040 | 7.0% |
| LOAD_ATTR | 30,848,560 | 6.4% |


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
| STORE_FAST | 8,511,420 | 18.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 7,862,780 | 16.8% |
| RESUME_CHECK | 5,375,360 | 11.5% |
| STORE_SUBSCR_LIST_INT | 5,330,140 | 11.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 22,232,760 | 47.4% |
| STORE_ATTR_WITH_HINT | 9,997,720 | 21.3% |
| BINARY_OP_SUBTRACT_INT | 5,033,360 | 10.7% |
| CALL_PY_EXACT_ARGS | 4,205,440 | 9.0% |
| COMPARE_OP_INT | 3,421,680 | 7.3% |


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
| COMPARE_OP_INT | 63,650,320 | 63.0% |
| TO_BOOL_BOOL | 30,749,280 | 30.5% |
| TO_BOOL_INT | 6,370,800 | 6.3% |
| COMPARE_OP | 112,740 | 0.1% |
| IS_OP | 54,880 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,663,280 | 80.9% |
| LOAD_FAST_LOAD_FAST | 9,415,040 | 9.3% |
| POP_TOP | 3,517,520 | 3.5% |
| LOAD_GLOBAL_MODULE | 2,527,060 | 2.5% |
| ENTER_EXECUTOR | 1,753,560 | 1.7% |


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
| COMPARE_OP_INT | 15,057,600 | 48.4% |
| TO_BOOL_BOOL | 6,983,120 | 22.4% |
| TO_BOOL_INT | 6,875,280 | 22.1% |
| TO_BOOL_ALWAYS_TRUE | 1,090,160 | 3.5% |
| COMPARE_OP_FLOAT | 1,060,820 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 12,986,200 | 41.7% |
| LOAD_FAST | 9,020,920 | 29.0% |
| POP_TOP | 5,722,320 | 18.4% |
| RETURN_CONST | 1,909,440 | 6.1% |
| RETURN_VALUE | 677,200 | 2.2% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 5,825,960 | 24.0% |
| STORE_ATTR_INSTANCE_VALUE | 5,517,820 | 22.7% |
| STORE_SUBSCR_LIST_INT | 5,330,140 | 22.0% |
| CALL_LIST_APPEND | 2,406,760 | 9.9% |
| ENTER_EXECUTOR | 2,241,920 | 9.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 19,650,560 | 81.0% |
| TO_BOOL_BOOL | 3,712,420 | 15.3% |
| TO_BOOL_INT | 845,100 | 3.5% |
| EXIT_INIT_CHECK | 61,380 | 0.3% |
| INTERPRETER_EXIT | 140 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,820 | 52.8% |
| LOAD_FAST_LOAD_FAST | 6,240 | 37.4% |
| STORE_ATTR | 900 | 5.4% |
| SWAP | 440 | 2.6% |
| STORE_ATTR_WITH_HINT | 220 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,360 | 74.0% |
| STORE_ATTR | 900 | 5.4% |
| LOAD_FAST | 880 | 5.3% |
| STORE_ATTR_INSTANCE_VALUE | 860 | 5.1% |
| STORE_ATTR_WITH_HINT | 580 | 3.5% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 39,429,400 | 31.3% |
| LOAD_ATTR_WITH_HINT | 39,179,420 | 31.1% |
| BINARY_SUBSCR_LIST_INT | 8,817,160 | 7.0% |
| BINARY_OP_ADD_INT | 7,772,340 | 6.2% |
| FOR_ITER_LIST | 7,598,700 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 103,819,840 | 82.4% |
| LOAD_FAST_LOAD_FAST | 8,511,420 | 6.8% |
| COPY | 7,550,160 | 6.0% |
| LOAD_GLOBAL_MODULE | 2,227,080 | 1.8% |
| JUMP_FORWARD | 2,019,600 | 1.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 16,360 | 50.5% |
| COPY | 16,000 | 49.4% |
| FOR_ITER | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 16,340 | 50.5% |
| LOAD_ATTR_INSTANCE_VALUE | 15,960 | 49.3% |
| LOAD_ATTR | 80 | 0.2% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,516,720 | 98.5% |
| BINARY_OP_ADD_INT | 12,740 | 0.5% |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,740 | 0.5% |
| BINARY_OP | 11,680 | 0.5% |
| LOAD_FAST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,516,720 | 98.5% |
| LOAD_CONST | 12,760 | 0.5% |
| LOAD_FAST_LOAD_FAST | 12,760 | 0.5% |
| BUILD_LIST | 11,660 | 0.5% |
| JUMP_BACKWARD | 240 | 0.0% |


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 6,936,160 | 100.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,224,140 | 75.3% |
| LOAD_GLOBAL_MODULE | 1,712,040 | 24.7% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 11,517,300 | 43.9% |
| BINARY_OP | 10,929,580 | 41.7% |
| BINARY_OP_ADD_INT | 3,612,000 | 13.8% |
| BUILD_LIST | 45,280 | 0.2% |
| LOAD_FAST_AND_CLEAR | 45,280 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_WITH_HINT | 15,093,780 | 57.6% |
| STORE_ATTR_INSTANCE_VALUE | 10,964,660 | 41.8% |
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
| LOAD_CONST | 14,712,740 | 75.5% |
| LOAD_ATTR_INSTANCE_VALUE | 3,352,260 | 17.2% |
| LOAD_ATTR_WITH_HINT | 1,364,760 | 7.0% |
| LOAD_FAST_LOAD_FAST | 25,440 | 0.1% |
| LOAD_FAST | 12,440 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,772,340 | 39.9% |
| STORE_GLOBAL | 6,936,160 | 35.6% |
| SWAP | 3,612,000 | 18.5% |
| CALL_BUILTIN_CLASS | 1,117,160 | 5.7% |
| LOAD_FAST_LOAD_FAST | 12,740 | 0.1% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,117,160 | 94.8% |
| LOAD_GLOBAL_MODULE | 60,840 | 5.2% |
| BINARY_OP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,117,180 | 94.8% |
| CALL_BUILTIN_CLASS | 48,400 | 4.1% |
| LOAD_FAST | 12,460 | 1.1% |
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
| LOAD_FAST | 17,794,540 | 71.1% |
| LOAD_ATTR_WITH_HINT | 5,456,440 | 21.8% |
| BINARY_OP_SUBTRACT_INT | 1,728,000 | 6.9% |
| ENTER_EXECUTOR | 33,600 | 0.1% |
| LOAD_GLOBAL_MODULE | 16,420 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 10,929,360 | 43.6% |
| STORE_FAST | 8,817,160 | 35.2% |
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
| ENTER_EXECUTOR | 12,500 | 20.4% |
| LOAD_FAST_LOAD_FAST | 420 | 0.7% |
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
| LOAD_FAST | 116,340 | 9.4% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 1,117,160 | 90.6% |
| STORE_FAST | 116,400 | 9.4% |
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
| LOAD_ATTR_INSTANCE_VALUE | 2,388,160 | 84.4% |
| LOAD_ATTR_WITH_HINT | 442,040 | 15.6% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,728,040 | 61.1% |
| LOAD_FAST | 637,100 | 22.5% |
| COMPARE_OP_INT | 442,040 | 15.6% |
| STORE_FAST | 16,360 | 0.6% |
| CALL | 6,760 | 0.2% |


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
| ENTER_EXECUTOR | 45,760 | 1.8% |
| JUMP_FORWARD | 15,980 | 0.6% |
| LOAD_FAST | 9,500 | 0.4% |
| JUMP_BACKWARD | 300 | 0.0% |


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
| LOAD_FAST | 29,419,140 | 56.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,432,080 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 4,244,680 | 8.1% |
| LOAD_FAST_LOAD_FAST | 4,205,440 | 8.1% |
| BINARY_SUBSCR_LIST_INT | 3,521,040 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 52,176,060 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,736,560 | 67.9% |
| LOAD_ATTR | 2,413,560 | 28.6% |
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
| LOAD_ATTR_WITH_HINT | 39,407,940 | 50.0% |
| LOAD_GLOBAL_MODULE | 20,399,440 | 25.9% |
| LOAD_CONST | 9,870,700 | 12.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,730,160 | 6.0% |
| LOAD_FAST_LOAD_FAST | 3,421,680 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 63,650,320 | 80.8% |
| POP_JUMP_IF_TRUE | 15,057,600 | 19.1% |
| COMPARE_OP | 32,100 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 7,607,340 | 99.7% |
| SWAP | 16,060 | 0.2% |
| JUMP_BACKWARD | 9,000 | 0.1% |
| FOR_ITER | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,598,700 | 99.6% |
| RETURN_CONST | 16,680 | 0.2% |
| STORE_FAST_LOAD_FAST | 16,360 | 0.2% |
| LOAD_FAST | 940 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 29,140 | 62.4% |
| GET_ITER | 16,040 | 34.4% |
| JUMP_BACKWARD | 1,400 | 3.0% |
| FOR_ITER | 100 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 46,580 | 99.8% |
| SWAP | 100 | 0.2% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 11,640 | 88.6% |
| JUMP_BACKWARD | 1,480 | 11.3% |
| FOR_ITER | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 12,720 | 96.8% |
| RETURN_CONST | 400 | 3.0% |
| UNPACK_SEQUENCE | 20 | 0.2% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,415,540 | 54.8% |
| LOAD_FAST_LOAD_FAST | 22,232,760 | 23.2% |
| COPY | 10,964,660 | 11.5% |
| LOAD_ATTR_WITH_HINT | 5,288,800 | 5.5% |
| LOAD_ATTR_INSTANCE_VALUE | 4,805,080 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,467,680 | 42.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 15,571,660 | 16.3% |
| LOAD_ATTR_METHOD_NO_DICT | 5,891,440 | 6.2% |
| LOAD_ATTR_INSTANCE_VALUE | 4,805,080 | 5.0% |
| COMPARE_OP_INT | 4,730,160 | 4.9% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,891,440 | 98.7% |
| LOAD_FAST | 80,280 | 1.3% |
| LOAD_ATTR | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,172,900 | 69.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,728,000 | 28.9% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 70,960 | 1.2% |
| CALL | 80 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 15,571,660 | 60.4% |
| LOAD_FAST | 10,201,000 | 39.5% |
| STORE_FAST_LOAD_FAST | 16,340 | 0.1% |
| ENTER_EXECUTOR | 11,200 | 0.0% |
| LOAD_ATTR | 700 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,473,800 | 48.3% |
| LOAD_FAST_LOAD_FAST | 7,862,780 | 30.5% |
| CALL_PY_EXACT_ARGS | 5,432,080 | 21.1% |
| LOAD_GLOBAL_MODULE | 31,920 | 0.1% |
| CALL | 280 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,270,940 | 100.0% |
| LOAD_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,271,040 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 181,354,220 | 91.5% |
| COPY | 15,093,780 | 7.6% |
| LOAD_ATTR_WITH_HINT | 1,661,400 | 0.8% |
| LOAD_ATTR | 860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,328,500 | 28.4% |
| COMPARE_OP_INT | 39,407,940 | 19.9% |
| STORE_FAST | 39,179,420 | 19.8% |
| LOAD_CONST | 23,585,000 | 11.9% |
| LOAD_GLOBAL_MODULE | 12,033,360 | 6.1% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,845,160 | 69.5% |
| RESUME_CHECK | 669,500 | 16.4% |
| LOAD_FAST | 442,160 | 10.8% |
| STORE_ATTR_INSTANCE_VALUE | 77,320 | 1.9% |
| LOAD_GLOBAL_BUILTIN | 32,600 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,947,660 | 96.5% |
| LOAD_GLOBAL_MODULE | 81,040 | 2.0% |
| LOAD_GLOBAL_BUILTIN | 32,600 | 0.8% |
| CALL_BUILTIN_CLASS | 16,120 | 0.4% |
| LOAD_CONST | 13,020 | 0.3% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_WITH_HINT | 12,033,360 | 30.7% |
| LOAD_FAST | 8,911,560 | 22.7% |
| RESUME_CHECK | 5,278,980 | 13.5% |
| POP_JUMP_IF_FALSE | 2,527,060 | 6.4% |
| STORE_FAST | 2,227,080 | 5.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 20,399,440 | 52.1% |
| LOAD_FAST | 7,980,720 | 20.4% |
| LOAD_CONST | 6,936,160 | 17.7% |
| LOAD_ATTR_MODULE | 2,270,940 | 5.8% |
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
| CALL_PY_EXACT_ARGS | 52,176,060 | 79.6% |
| CALL_PY_WITH_DEFAULTS | 8,443,640 | 12.9% |
| CALL_KW | 3,629,340 | 5.5% |
| ENTER_EXECUTOR | 1,147,800 | 1.8% |
| CALL_ALLOC_AND_ENTER_INIT | 61,380 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 54,147,920 | 82.7% |
| LOAD_FAST_LOAD_FAST | 5,375,360 | 8.2% |
| LOAD_GLOBAL_MODULE | 5,278,980 | 8.1% |
| LOAD_GLOBAL_BUILTIN | 669,500 | 1.0% |
| LOAD_CONST | 41,620 | 0.1% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 10,964,660 | 62.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,542,160 | 14.5% |
| LOAD_FAST | 2,141,800 | 12.2% |
| LOAD_FAST_LOAD_FAST | 1,859,640 | 10.6% |
| STORE_ATTR | 860 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,293,780 | 41.7% |
| RETURN_CONST | 5,517,820 | 31.5% |
| LOAD_FAST_LOAD_FAST | 3,442,860 | 19.7% |
| JUMP_FORWARD | 904,360 | 5.2% |
| LOAD_CONST | 156,580 | 0.9% |


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 15,093,780 | 37.1% |
| LOAD_FAST | 13,699,220 | 33.6% |
| LOAD_FAST_LOAD_FAST | 9,997,720 | 24.6% |
| ENTER_EXECUTOR | 1,919,680 | 4.7% |
| STORE_ATTR | 580 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,412,220 | 69.8% |
| ENTER_EXECUTOR | 5,792,340 | 14.2% |
| LOAD_CONST | 3,428,460 | 8.4% |
| LOAD_FAST_LOAD_FAST | 3,076,840 | 7.6% |
| JUMP_BACKWARD | 900 | 0.0% |


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
| ENTER_EXECUTOR | 1,035,800 | 94.1% |
| LOAD_FAST | 34,160 | 3.1% |
| LOAD_ATTR_INSTANCE_VALUE | 29,600 | 2.7% |
| TO_BOOL_NONE | 560 | 0.1% |
| TO_BOOL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,090,160 | 99.1% |
| POP_JUMP_IF_FALSE | 9,500 | 0.9% |
| TO_BOOL_NONE | 520 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,405,520 | 70.5% |
| RETURN_CONST | 3,712,420 | 9.2% |
| LOAD_ATTR_WITH_HINT | 3,512,020 | 8.7% |
| COPY | 2,516,680 | 6.3% |
| ENTER_EXECUTOR | 1,235,460 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 30,749,280 | 76.4% |
| POP_JUMP_IF_TRUE | 6,983,120 | 17.3% |
| UNARY_NOT | 2,516,700 | 6.3% |
| TO_BOOL_INT | 16,000 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 7,792,000 | 58.8% |
| LOAD_FAST | 2,942,500 | 22.2% |
| RETURN_VALUE | 1,666,320 | 12.6% |
| RETURN_CONST | 845,100 | 6.4% |
| TO_BOOL_BOOL | 16,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,875,280 | 51.8% |
| POP_JUMP_IF_FALSE | 6,370,800 | 48.0% |
| TO_BOOL_BOOL | 15,980 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 16,260 | 99.9% |
| TO_BOOL | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 16,280 | 100.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,280 | 36.7% |
| ENTER_EXECUTOR | 15,720 | 31.5% |
| LOAD_ATTR_INSTANCE_VALUE | 15,280 | 30.7% |
| TO_BOOL_ALWAYS_TRUE | 520 | 1.0% |
| TO_BOOL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 49,280 | 98.9% |
| TO_BOOL_ALWAYS_TRUE | 560 | 1.1% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 12,720 | 99.8% |
| UNPACK_SEQUENCE | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 12,740 | 100.0% |


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
|     deferred | 17,356,040 | 29.3% |
|          hit | 41,749,680 | 70.5% |
|         miss | 111,980 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,880 | 19.1% |
| Failure | 12,180 | 80.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 6,700 | 55.0% |
| xor | 3,200 | 26.3% |
| multiply different types | 1,040 | 8.5% |
| true divide different types | 920 | 7.6% |
| floor divide | 160 | 1.3% |
| remainder | 160 | 1.3% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 860 | 0.0% |
|          hit | 24,985,380 | 99.8% |
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
|     deferred | 3,552,580 | 4.4% |
|          hit | 76,606,660 | 95.6% |
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
|     deferred | 129,180 | 0.2% |
|          hit | 79,769,560 | 99.8% |
|         miss | 31,740 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,340 | 38.5% |
| Failure | 2,140 | 61.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 1,240 | 57.9% |
| float long | 560 | 26.2% |
| bool | 180 | 8.4% |
| long float | 160 | 7.5% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 400 | 0.0% |
|          hit | 7,692,500 | 100.0% |

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
|     deferred | 30,846,980 | 8.6% |
|          hit | 327,871,620 | 91.4% |
|         miss | 7,420 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,940 | 29.9% |
| Failure | 9,240 | 70.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| has managed dict | 9,040 | 97.8% |
| method | 200 | 2.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,740 | 0.0% |
|          hit | 43,277,020 | 100.0% |

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
|     deferred | 14,140 | 0.0% |
|          hit | 58,207,240 | 99.9% |
|         miss | 12,860 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,440 | 56.2% |
| Failure | 1,120 | 43.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not in dict | 1,060 | 94.6% |
| not in keys | 60 | 5.4% |


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
|     deferred | 368,934,881,474,190,999,720 | 674,538,429,101,526.2% |
|          hit | 52,940,200 | 96.8% |
|         miss | 1,753,260 | 3.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 33,560 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.2% |
|          hit | 12,740 | 99.7% |

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
| Basic | 950,139,140 | 49.3% |
| Not specialized | 184,083,200 | 9.6% |
| Specialized hits | 789,955,500 | 41.0% |
| Specialized misses | 1,974,820 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL | 368,934,881,474,190,999,720 | 100.0% |
| LOAD_ATTR | 30,846,980 | 0.0% |
| BINARY_OP | 17,356,040 | 0.0% |
| CALL | 3,552,580 | 0.0% |
| COMPARE_OP | 129,180 | 0.0% |
| STORE_ATTR | 14,140 | 0.0% |
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
| TO_BOOL_BOOL | 848,000 | 42.9% |
| TO_BOOL_INT | 846,940 | 42.9% |
| BINARY_OP_ADD_INT | 111,980 | 5.7% |
| BINARY_SUBSCR_LIST_INT | 57,400 | 2.9% |
| TO_BOOL_NONE | 29,680 | 1.5% |
| TO_BOOL_ALWAYS_TRUE | 28,640 | 1.5% |
| COMPARE_OP_FLOAT | 25,380 | 1.3% |
| STORE_ATTR_WITH_HINT | 12,860 | 0.7% |
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
| Calls to Python functions inlined | 64,366,360 | 100.0% |
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
| Frames pushed | 70,124,760 | 108.9% |


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
| Frees | 29,759,493 |  |
| New values | 140 |  |
| Interpreter increfs | 904,033,900 | 87.7% |
| Interpreter decrefs | 993,484,660 | 92.6% |
| Increfs | 126,274,543 | 12.3% |
| Decrefs | 79,586,292 | 7.4% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 12,960 | 9,257.1% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 42,742,458 |  |
| Method cache misses | 4,602 |  |
| Method cache collisions | 4,252 |  |
| Method cache dunder hits | 494 |  |
| Method cache dunder misses | 106 |  |


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
| Trace stack underflow | 40 | 4.7% |
| Trace too long | 160 | 18.6% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 80 | 9.3% |
| Traces executed | 29,195,000 |  |
| Uops executed | 989,056,460 | 33.88 |

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
| <= 32 | 180 | 20.9% |
| <= 64 | 340 | 39.5% |
| <= 128 | 320 | 37.2% |


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
| <= 16 | 80 | 9.3% |
| <= 32 | 280 | 32.6% |
| <= 64 | 220 | 25.6% |
| <= 128 | 280 | 32.6% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 6,146,180 | 21.1% |
| <= 16 | 2,791,640 | 9.6% |
| <= 32 | 13,996,600 | 47.9% |
| <= 64 | 1,286,340 | 4.4% |
| <= 128 | 4,820,720 | 16.5% |
| <= 256 | 76,140 | 0.3% |
| <= 512 | 22,980 | 0.1% |
| <= 1,024 | 22,000 | 0.1% |
| <= 2,048 | 16,200 | 0.1% |
| <= 4,096 | 16,200 | 0.1% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 238,188,800 | 24.1% | 24.1% |  |
| LOAD_FAST | 92,284,960 | 9.3% | 33.4% |  |
| _GUARD_TYPE_VERSION | 52,556,840 | 5.3% | 38.7% |  |
| _POP_JUMP_IF_TRUE | 50,397,060 | 5.1% | 43.8% |  |
| STORE_FAST | 48,729,540 | 4.9% | 48.7% |  |
| _CHECK_ATTR_WITH_HINT | 35,567,280 | 3.6% | 52.3% |  |
| _LOAD_ATTR_WITH_HINT | 35,567,280 | 3.6% | 55.9% |  |
| _GUARD_GLOBALS_VERSION | 32,928,280 | 3.3% | 59.3% |  |
| _ITER_CHECK_LIST | 32,748,640 | 3.3% | 62.6% |  |
| _IS_ITER_EXHAUSTED_LIST | 32,748,640 | 3.3% | 65.9% |  |
| _LOAD_GLOBAL_MODULE | 27,712,200 | 2.8% | 68.7% |  |
| _EXIT_TRACE | 27,680,760 | 2.8% | 71.5% |  |
| COMPARE_OP_INT | 26,441,680 | 2.7% | 74.2% |  |
| _ITER_NEXT_LIST | 26,122,280 | 2.6% | 76.8% |  |
| _POP_JUMP_IF_FALSE | 19,197,940 | 1.9% | 78.7% |  |
| LOAD_CONST | 10,093,660 | 1.0% | 79.8% |  |
| _CHECK_PEP_523 | 9,382,300 | 0.9% | 80.7% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 9,382,300 | 0.9% | 81.7% |  |
| _CHECK_STACK_SPACE | 9,382,300 | 0.9% | 82.6% |  |
| _INIT_CALL_PY_EXACT_ARGS | 9,382,300 | 0.9% | 83.6% |  |
| _PUSH_FRAME | 9,382,300 | 0.9% | 84.5% |  |
| _SAVE_RETURN_OFFSET | 9,382,300 | 0.9% | 85.5% |  |
| _LOAD_ATTR | 9,265,080 | 0.9% | 86.4% |  |
| POP_TOP | 8,282,660 | 0.8% | 87.2% |  |
| RESUME_CHECK | 8,234,500 | 0.8% | 88.1% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 7,914,000 | 0.8% | 88.9% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 7,914,000 | 0.8% | 89.7% |  |
| _GUARD_KEYS_VERSION | 7,742,080 | 0.8% | 90.5% | 0.1% |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 7,742,080 | 0.8% | 91.2% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 7,730,880 | 0.8% | 92.0% |  |
| _JUMP_TO_TOP | 7,205,060 | 0.7% | 92.7% |  |
| _GUARD_BUILTINS_VERSION | 5,216,080 | 0.5% | 93.3% |  |
| _LOAD_GLOBAL_BUILTINS | 5,216,080 | 0.5% | 93.8% |  |
| _GUARD_BOTH_INT | 4,726,080 | 0.5% | 94.3% | 9.6% |
| TO_BOOL_BOOL | 4,503,020 | 0.5% | 94.7% |  |
| _BINARY_OP_ADD_INT | 4,240,960 | 0.4% | 95.2% |  |
| PUSH_NULL | 3,517,880 | 0.4% | 95.5% |  |
| _CHECK_ATTR_MODULE | 3,513,940 | 0.4% | 95.9% |  |
| _LOAD_ATTR_MODULE | 3,513,940 | 0.4% | 96.2% |  |
| COPY | 3,279,220 | 0.3% | 96.6% |  |
| SWAP | 3,279,220 | 0.3% | 96.9% |  |
| _ITER_CHECK_RANGE | 3,112,980 | 0.3% | 97.2% |  |
| _IS_ITER_EXHAUSTED_RANGE | 3,112,980 | 0.3% | 97.5% |  |
| _ITER_NEXT_RANGE | 3,083,800 | 0.3% | 97.8% |  |
| _POP_FRAME | 2,802,980 | 0.3% | 98.1% |  |
| _STORE_ATTR | 2,585,000 | 0.3% | 98.4% |  |
| BINARY_SUBSCR_LIST_INT | 2,553,080 | 0.3% | 98.6% |  |
| TO_BOOL_NONE | 2,040,700 | 0.2% | 98.8% | 51.5% |
| CALL_LEN | 1,737,080 | 0.2% | 99.0% |  |
| TO_BOOL_INT | 1,727,860 | 0.2% | 99.2% |  |
| _GUARD_DORV_VALUES | 1,299,880 | 0.1% | 99.3% |  |
| _STORE_ATTR_INSTANCE_VALUE | 1,299,880 | 0.1% | 99.5% |  |
| _BINARY_OP | 1,295,100 | 0.1% | 99.6% |  |
| LIST_APPEND | 1,286,100 | 0.1% | 99.7% |  |
| GET_ITER | 1,277,500 | 0.1% | 99.8% |  |
| STORE_GLOBAL | 1,260,580 | 0.1% | 100.0% |  |
| _ITER_CHECK_TUPLE | 51,640 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 51,640 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 39,080 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 39,080 | 0.0% | 100.0% |  |
| _BINARY_OP_MULTIPLY_INT | 33,600 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 33,600 | 0.0% | 100.0% |  |
| TO_BOOL_ALWAYS_TRUE | 11,940 | 0.0% | 100.0% |  |
| _COMPARE_OP | 9,520 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 9,220 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 3,940 | 0.0% | 100.0% |  |
| BUILD_LIST | 1,300 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| CALL | 80 |
| CALL_PY_WITH_DEFAULTS | 80 |
| STORE_ATTR_WITH_HINT | 80 |
| CALL_KW | 20 |
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
Stats gathered on: 2023-11-08
